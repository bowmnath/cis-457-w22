# General Questions

1. Cities A and C are joined by a road that goes through City B.
   City B has a law against driving personal cars on their roads --
   they allow only semis.
   A driver who wants to get from City A to City C must load their car into
   a semi to travel through City B.
   When they arrive at City C, they can unload their car and continue as usual.
   How does this relate to routers and IP?

2. How many IPv6 addresses are there?
   How does this compare to the number of IPv4 addresses?

   Assume every IPv4 address were used up.
   How many IPv6 addresses could be assigned to every single IPv4-addressed
   host before the IPv6 address space was exhausted?

3. Are there more IPv6 addresses or...
    * stars in the known universe?
    * grains of sand on the earth?
    * Pokemon?

4. If you order a meal at SimpleBurger,
   you do not get to choose much about your food.
   Every meal is a plain beef patty and a side of plain fries.
   At BetterBurger,
   you can customize by adding pickles, onions, ketchup, and so on to your
   order.
   What might be an advantage to ordering at SimpleBurger?
   Is there any way to get the "features" of BetterBurger while retaining the
   advantages of SimpleBurger?
   What does this have to do with IP?

5. Your professors at GVSU have come up with a new IP version (IPv457) that is
   obviously superior to IPv6.
   They propose that this new version be adopted throughout the Internet by
   2025.
   Does this strike you as reasonable?
   Why or why not?

6. IPv6 does not include fragmentation.
   However, it is still possible that an IPv6 datagram ends up fragmented
   as it travels from its source to its destination.
   How can this happen?

<!--
7. An IPv6 address is usually broken into chunks of four hex digits with the
   chunks separated by colons.
   How many chunks of four are the addresses broken into?
   (Try to figure this out without looking it up --
   use what you know about the number of possible IPv6 addresses).
-->

1. Explain the relationship between forwarding and routing.

2. What are some different criteria that might be used in determining which
   path to take through the network?

3. What is the difference between static and dynamic routing?
   Give an advantage and disadvantage of each.

4. Consider a router that knows the minimum distance from each of its neighbors
   to each end host on the system.
   That router is running a... (link state or distance vector)
   ...routing algorithm.

5. Running Dijkstra's algorithm with node `u` as the starting point results in
   the following table of distances and predecessors in the format used in the
   lecture video once the algorithm has finished.
   ```
   | v   | w   | x   | y   | z   |
   | --- | --- | --- | --- | --- |
   | 5,z | 2,u | 3,u | 9,x | 4,w |
   ```
   What is the least-cost path from `u` to `v`?
   What is the cost of that path?

6. Using the results above,
   write out the forwarding table for the router `u`.

7. Which of the following could be sensible choices to use as link costs?
   * Physical distance
   * 1/(Physical distance)
   * Congestion
   * Link bandwidth
   * 1/(Link bandwidth)

8. Explain how using current congestion to determine link weights can cause an
   algorithm to fail if it is not implemented carefully.

9. Consider a three-router network with routers `A`, `B`, and `C`.
   The initial distance vector for `A` is given below.
   ```
   |    | A   | B   | C   |
   | ---| --- | --- | --- |
   |  A | 0   | 5   | 2   |
   ```
   `A` then receives these two distance vectors from its neighbors.
   ```
   |    | A   | B   | C   |
   | ---| --- | --- | --- |
   |  B | 5   | 0   | 1   |
   |  C | 2   | 1   | 0   |
   ```
   What is the updated distance vector for `A`?

10. Why is it useful to have different protocols for intra-AS vs inter-AS
   routing?

11. Why is it useful for OSPF to authenticate its messages?

12. In your own words, what do the `AS-PATH` and `NEXT-HOP` attributes of BGP
   messages mean?
   Why are they important?

13. Consider routing a packet to a distant prefix `X`.
   For each of the following, state whether it is the responsibility of BGP
   or OSPF.
   * Determining which ASes packet will go through along the way.
   * Determining which gateway router with local AS packet should be sent to.
   * Determining which outgoing link is used to forward packets toward gateway
     router.

14. Explain a few ways in which pure hot-potato routing,
   without consideration of the other factors that go into BGP route selection,
   could lead to a "bad" choice of path.
