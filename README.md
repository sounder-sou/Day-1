# Day-1
Scanning local network for open host
This project demonstrates basic network reconnaissance using "Nmap" and packet analysis using "Wireshark*". A TCP SYN scan was performed on the local subnet (`192.168.1.0/24`) to discover active hosts and identify open ports.
The scan revealed multiple services, including DNS, HTTP, HTTPS, SMB, and NetBIOS. Network traffic generated during the scan was captured and analyzed in Wireshark using filters such as `tcp.flags.syn == 1`, `tcp.flags.syn == 1 && tcp.flags.ack == 1`, and `tcp.flags.reset == 1`.
The project includes:
* Nmap scan results
* Wireshark packet analysis screenshots
* Security risk assessment of discovered services
* HTML report containing the complete findings
This exercise provided hands-on experience in network scanning, service identification, packet analysis, and basic security assessment.
