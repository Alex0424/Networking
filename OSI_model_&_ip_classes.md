# OSI layers

| Layer | Name              | # | Info  |
| ----- | ----------------- | ----- | ----- |
| 7     | Application       | HTTP, SSH, DNS, IRC, FTP|       |
| 6     | Presentation      | SSL, SSH, IMAP, FTP, MPEG, JPEG |       |
| 5     | Session           | API, Socket, WinSock |       |
| 4     | Transport         | TCP, UDP |       |
| 3     | Network           | IP, ICMP, IPSec, IGMP |       |
| 2     | Data Link         | Ethernet, PPP, Switch, Bridge |       |
| 1     | Physical          | Coax, Fiber, Wireless, Hubs, Repeaters |       |

# IP classes

| Class   | Public IP range              | Private IP range               | Subnet mask    | # of Networks | # of hosts per network |
| ------- | ---------------------------- | ------------------------------ | -------------- | ------------- | -----------------------|
| Class A	| 1.0.0.0 to 127.0.0.0	       | 10.0.0.0 to 10.255.255.255     | 255.0.0.0      | 126           | 16,777,214             |
| Class B	| 128.0.0.0 to 191.255.0.0     | 172.16.0.0 to 172.31.255.255   | 255.255.0.0    | 16,382        | 65,534                 |
| Class C	| 192.0.0.0 to 223.255.255.0   | 192.168.0.0 to 192.168.255.255 | 255.255.255.0  | 2,097,150     | 254                    |
