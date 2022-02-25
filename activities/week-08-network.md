# General Questions

1. Explain the purpose of the time-to-live field in an IPv4 datagram header.

2. If a single faulty router on a network *incremented* TTL instead of
decrementing it,
how bad would it be for the network as a whole?

3. Why does including both TTL and a checksum make IPv4 less efficient?

4. There are two ways that an IPv4 receiver can tell that a datagram it
receives is a fragment.
What are they?
Must both indications be present in every fragment?

5. Is it possible for an IP datagram successfully traverse several links
before being fragmented,
or must fragmentation occur at the first link?
If it is possible, explain why or give an example of how this could happen.
If it is not possible, explain why not.

6. Two movers are trying to get a treadmill out of a house.
They get into a narrow doorway and need to disassemble it before they can
continue.
Should they reassemble the treadmill as soon as they get through the doorway?
Why or why not?
What does this have to do with IP datagrams?

7. A datagram has a length of 4500 bytes and it reaches a link with a MTU of
1500 bytes.
How many fragments will it be broken into? (Careful.)

8. Give the `length`, `fragflag`, and `offset` for each of the datagrams
resulting from the scenario in the previous question.

9. An IP receiver receives packets with the following fields:
```
length |  ID | fragflag | offset |
   --- | --- |      --- |    --- |
  1500 |   0 |        1 |      0 |
  1500 |   1 |        0 |    185 |
```

Are there any fragments that have not yet been received?
If so, what values for these fields would the missing packet(s) need to have to
be sure everything was received?
If not, how can you tell?

10. Imagine you are in elementary school and want to know if some like-likes
you.
If the person you want to ask is in your classroom,
you can pass them a note yourself.
Otherwise, you need to hand it to the hallway monitor and hope they pass it
on for you.
What is the networking analogy for this situation?

11. Even though it is just one device,
a router will generally have more IP addresses than an end host.
Why?

12. Consider the host 223.1.4.8 on a subnet identified by 223.1.0.0/16.
Which part of the IP address specifies the subnet and which part specifies the
host on that subnet?
How many hosts can there be on that subnet?

13. Host A is on a subnet with subnet mask ending in `/24`.
Host B is on a subnet with subnet mask ending in `/8`.
Which subnet has the potential to be bigger
(i.e., has more available addresses for hosts on that subnet)?

13. Why are IPv4 addresses represented as combinations of numbers from 0 - 255?
I.e., why is 320.2.900.4 not a valid IP address?
Is there any other way that IP addresses could be written besides
`[0-255].[0-255].[0-255].[0-255]`?

14. Host A has IP address 200.90.1.5.
Host B has IP address 200.90.2.5.
Can Host A contact Host B without going through a router?
Why or why not?

15. Consider two end hosts connected by a chain of five routers.
If you were to sketch out this situation,
what is the minimum number of subnets that would be included in your drawing?

16. With the subnet mask `255.255.252.0`,
what is the maximum number of hosts on the subnet?
If the mask were written in the other format,
`a.b.c.d/x`,
what would be the value of `x`?

17. With the subnet mask above,
find two addresses that have the same first two numbers (`a` and `b`)
but would reside on different subnets.
Then, find two addresses that have the same `a` and `b`,
have different `c`,
and reside on the same subnet as one another.

18. Why is it important that DHCP requests and replies include a transaction ID?

19. Why are DHCP addresses leased as opposed to given permanently?

20. ISP A advertises that it services hosts 180.23.0.0/16.
ISP B advertises that it services hosts 180.23.17.0/24.
Where will packets to the following destinations be routed?
* 180.23.16.5
* 180.23.17.2

21. Consider a subnet 10.0.0.0/24 residing behind a NAT.
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

22. Why is it possible (sort of) for two hosts on the internet to have the IP
address 192.168.2.2?

23. What is the main reason for the transition to IPv6?
Why might routers be able to handle IPv6 packets more efficiently than IPv4
packets?
