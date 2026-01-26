Common Network Commands

ifconfig - Displaying network interface information
iwconfig - view and configure network interfaces specifically for wireless operation
ping 198.x.x.x or ping example.com - to check Tests network connectivity to a host using ICMP packets.
arp -a  - Displays the local Address Resolution Protocol (ARP) cache table (IP address to physical MAC address mappings).
netstat - Shows active network connections, routing tables, and interface statistics. (Often superseded by ss or ip commands).
route   -  Manually views or manipudates the IP routing table. (Deprecated; use ip r or ip route).
ip n    -  Short for ip neighbor. Manages and displays neighbor objects (ARP table/NDP cache).
ip r    -  Short for ip route. Manages and displays the kernel's IP routing tables.

general commands 

sudo apt update && apt upgrade 
apt update - its fetch the latest version ,  
apt upgrade  -  This command installs newer versions of the packages you already have installed on your system
&&    - This shell operator ensures the second command runs only if the first command completes successfully 

apt install cmatrix   - used to install packages
git clone www.github.xxx.com  - used to install packages from github 

Viewing createing & Editing

echo "hello"  - create hello file
echo "HI" > hey.txt   -  this stores the HI in hey file
echo "HI Again" > hey.txt - this overwrite the previous file
cat hey.txt    -  this open the file 

create the text file also using the  nano.txt   


Scripting and Bashing

ping 192.168.x.x -c 1   -  used to count 1 ping
ping 192.162.x.x -c > ip.txt  - means save the 1 ping info to the text file as a data
cat ip.txt | grep "64 bytes"  - it give the single line of command where its exist 
cat ip.txt | grep "64 bytes" | cut -d " " -t 4
example 
          PING google.com (142.250.186.46) 56(84) bytes of data.
          64 bytes from lhr48s21-in-f14.1e100.net (142.250.186.46): icmp_seq=1 ttl=117 time=16.8 ms
          64 bytes from lhr48s21-in-f14.1e100.net (142.250.186.46): icmp_seq=2 ttl=117 time=16.9 ms
          64 bytes from lhr48s21-in-f14.1e100.net (142.250.186.46): icmp_seq=3 ttl=117 time=16.9 ms
          Request timeout for icmp_seq 4

