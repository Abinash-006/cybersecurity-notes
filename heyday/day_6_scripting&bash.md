# Common Network Commands

*   `ifconfig` - Displaying network interface information
*   `iwconfig` - View and configure network interfaces specifically for wireless operation
*   `ping 198.x.x.x` or `ping example.com` - Tests network connectivity to a host using ICMP packets.
*   `arp -a` - Displays the local Address Resolution Protocol (ARP) cache table (IP address to physical MAC address mappings).
*   `netstat` - Shows active network connections, routing tables, and interface statistics. (Often superseded by `ss` or `ip` commands).
*   `route` - Manually views or manipulates the IP routing table. (Deprecated; use `ip r` or `ip route`).
*   `ip n` - Short for `ip neighbor`. Manages and displays neighbor objects (ARP table/NDP cache).
*   `ip r` - Short for `ip route`. Manages and displays the kernel's IP routing tables.

# General Commands

*   `sudo apt update && apt upgrade`
    *   `apt update` - Fetches the latest version lists from repositories.
    *   `apt upgrade` - Installs newer versions of already installed packages.
    *   `&&` - Ensures the second command runs only if the first completes successfully.
*   `apt install cmatrix` - Used to install packages.
*   `git clone www.github.xxx.com` - Used to download packages/repositories from GitHub.

# Viewing, Creating & Editing Files

*   `echo "hello"` - Prints "hello" to the terminal output.
*   `echo "HI" > hey.txt` - Creates or overwrites `hey.txt` with the text "HI".
*   `echo "HI Again" > hey.txt` - Overwrites the previous `hey.txt` file content.
*   `cat hey.txt` - Displays the entire content of the file.
*   `nano nano.txt` - Opens a simple text editor to create/edit `nano.txt`.

# Scripting and Bashing

*   `ping 192.168.x.x -c 1` - Used to send only 1 ping packet.
*   `ping 192.162.x.x -c 1 > ip.txt` - Saves the output of 1 ping to the `ip.txt` file as data.
*   `cat ip.txt | grep "64 bytes"` - Displays only lines in `ip.txt` that indicate a successful ping reply.
*   `cat ip.txt | grep "64 bytes" | cut -d " " -t 4` - A complex command pipeline to extract the hostname or IP address from ping results
*   
example 
          PING google.com (142.250.186.46) 56(84) bytes of data.
          64 bytes from lhr48s21-in-f14.1e100.net (142.250.186.46): icmp_seq=1 ttl=117 time=16.8 ms
          64 bytes from lhr48s21-in-f14.1e100.net (142.250.186.46): icmp_seq=2 ttl=117 time=16.9 ms
          64 bytes from lhr48s21-in-f14.1e100.net (142.250.186.46): icmp_seq=3 ttl=117 time=16.9 ms
          Request timeout for icmp_seq 4

