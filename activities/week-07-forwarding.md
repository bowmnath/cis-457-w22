# General Questions

1. Consider a fast-food drive through lane.
For much of the day,
the drive-through is nearly empty.
Around noon and five o'clock,
the line suddenly becomes very long,
and then eventually dies down again after an hour or so.
If this lane were a link on a network,
would the network be packet-switched or circuit-switched?
How can you tell?

2. To alleviate the crowding issue,
the restaurant emails all of its customers and assigns them a 2-minute time
slot at some point in the day.
The customer is allowed to visit the drive-through at only this point in time.
What are the upsides and downsides to this idea?
How does this relate to networking?

3. Is it easier to provide a minimum bandwidth guarantee in a packet-switched
or a circuit-switched network?
Why?

4. How do two hosts reserve bandwidth ahead of time in a packet-switched
network?

5. The city of Bigsburgh has a six-lane highway running through it.
The residents are grumpy that out-of-state drivers cause a lot of congestion,
so they pass a law stating that Bigsburghians drive only in the left three
lanes and all other drivers are in the right three lanes.
Is this example most closetly related to packet-switching,
circuit-switching with FDM,
or circuit-switching with TDM?
Explain.

6. In which type of network, packet-switched or circuit-switched,
are queueing delays usually more of an issue?
Why?

7. Describe the difference between time-division and frequency-division
multiplexing.
Try to give real-life examples of each.

8. For a given set of sending hosts,
is it ever possible for a packet-switched network to have a lower utilization
than a circuit-switched network?
If so,
give an example.
Otherwise, explain why not.

In the next two questions, assume the network under consideration is
circuit-switched and uses TDM.

9. If there are 5 hosts sharing a 1 Mbps link
and 4 of the hosts are almost always idle,
what is the effective transmission rate of the host that is sending?

10. In the above question,
what percent of the time is the link idle?

11. If there are 5 hosts sharing a 1 Mbps link on a **packet-switched** network
and 4 of the hosts are almost always idle,
what is the effective transmission rate of the host that is sending?

12. In general,
describe a worst-case sending pattern for circuit-switched networks in terms
of resource utilization.
Then, describe a best-case pattern.

13. When a packet moves from the input interface of a router to an output
interface,
this is... (forwarding or routing)?

14. List a few kinds of guarantees that could be provided by a network layer.
What guarantees are provided by the internet's network layer?

15. Where would queueing delays most likely occur in a router under each of the
following circumstances?
(Some of these may not result in excessive queueing at all.)
* The switching fabric is significantly slower than the input ports
* The switching fabric is significantly faster than the input ports
* The routing is done by a single routing processor instead of locally on each
  port

Consider the following routing table.
```
Destination address range           | Link interface
---                                 | ---
10100010 XXXXXXXX XXXXXXXX XXXXXXXX | 0
10100011 XXXXXXXX XXXXXXXX XXXXXXXX | 1
10100011 111XXXXX XXXXXXXX XXXXXXXX | 2
otherwise                           | 3
```
Give the link interface for each of the following addresses:
* 162.224.0.1
* 162.3.2.1
* 161.3.2.1
* 161.253.2.1

Note: `10100010b = 162`, `10100011b = 163`, and `11100000b = 224`.

16. Assume a router has 5 input ports and 5 output ports.
What is the maximum number of packets that can be moved across the switching
fabric at once using
* a bus?
* a crossbar?

For the next few questions, assume five packets arrive in the queue of an
output port of a router at roughly the same time.
We refer to the packets simply as 1, 2, 3, 4, 5, based on the order of their
arrival.

17. How will the packets be scheduled using priority scheduling if odd-numbered
packets are high-priority and even-numbered packets are low-priority?

18. How will the packets be scheduled using round robin scheduling if
packets 1 and 4 are one class and packets 2, 3, and 5 are another class?
