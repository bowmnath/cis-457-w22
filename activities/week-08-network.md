# General Questions

8. Consider the host 223.1.4.8 on a subnet identified by 223.1.0.0/16.
Which part of the IP address specifies the subnet and which part specifies the
host on that subnet?
How many hosts can there be on that subnet?

9. Why is it important that DHCP requests and replies include a transaction ID?

10. Why are DHCP addresses leased as opposed to given permanently?

11. ISP A advertises that it services hosts 180.23.0.0/16.
ISP B advertises that it services hosts 180.23.17.0/24.
Where will packets to the following destinations be routed?
* 180.23.16.5
* 180.23.17.2

12. Consider a subnet 10.0.0.0/24 residing behind a NAT.
The internet-facing IP address of the gateway router is 270.33.9.4.
Host 10.0.0.2 sends a DNS query (port 53) to 138.75.90.2.
Give the source IP, source port, destination IP, and destination port of the
resulting IP datagrams at each of the following points.
If we do not have enough information to determine one of these numbers,
choose a random number that is sensible.
* DNS query while within subnet
* DNS query while in public internet
* DNS response while in public internet
* DNS response within subnet

13. Why is it possible (sort of) for two hosts on the internet to have the IP
address 192.168.2.2?

14. What is the main reason for the transition to IPv6?
Why might routers be able to handle IPv6 packets more efficiently than IPv4
packets?
