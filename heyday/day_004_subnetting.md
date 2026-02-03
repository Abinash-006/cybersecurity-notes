#!/bin/bash

#Subnetting
it has 
class A : 255 .  0  .  0  . 0  |  8-bit network ID, 24-bit host ID
class B : 255 . 255 .  0  . 0  |  16-bit network ID, 16-bit host ID
class C : 255 . 255 . 255 . 0  |  24-bit network ID, 8-bit host ID


private ip address space                        notes: hosts double each increment of a CIDR
    From               to                              Always subtract 2 from host total
10.0.0.0       -   10.255.255.255                      Broadcast - Last Address
172.16.0.0     -   172.31.255.255                      Network ID _ First Address             
192.168.0.0    -   192.168.255.255
---
8 bit - 255  : 128 64 32 16 8 4 2 1 
---
example ip - 192.268.1.0

then take it as 128 64 32 16 8 4 2 1 
now by this method       128 64 32 16 8 4 2 1     128 64 32 16 8 4 2 1     128 64 32 16 8 4 2 1     128 64 32 16 8 4 2 1
                          1   1  0  0 0 0 0 0      1  0  1  0  0 0 0 0      0   0  0  0 0 0 0 1      0   0  0  0 0 0 0 0
                         ------  192  --------     ------  268  ------     ---------  1  ------     -------  0  --------

                         continue...


