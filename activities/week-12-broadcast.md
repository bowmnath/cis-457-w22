# General Questions

<!--
1. Give an example of a human protocol for sharing a broadcast medium
   (e.g., the air when we speak).

2. Would your example be most similar to a channel partitioning, random access,
   or turn-taking protocol?
-->

1. Rank the following from worst to best scenarios for using a channel
   partitioning scheme.
   (You can rank some as a tie if they are roughly equivalent.)
   * Many senders, almost all sending
   * Few senders, almost all sending
   * Many senders, only one sending
   * Few senders, only one sending

2. What is the major downside to random access protocols?

3. We often use human analogies for medium access protocols.
   In regular conversation,
   do people use "carrier sense" as part of their protocols?
   If so, what would it look like if they did not use carrier sense?
   If not, how would things change if they did use carrier sense?

4. Finish the sentence:
   A random access protocol will be the most effective type of protocol when...

5. In slotted ALOHA with `p = 0.5`,
   assume two senders send in the same slot,
   leading to a collision.
   What is the probability that there will be a collision between those senders
   in the next slot?
   What is the probability that the next slot will be wasted
   (either neither sends or both send)?

6. What is the purpose of the slots in slotted ALOHA
   (i.e., why are they beneficial)?
   What is a possible downside to using slots?

7. Another 457 student tells you the following:

   When many hosts are connected to a link that is shared with the slotted
   ALOHA protocol,
   the effective rate of the link is much lower than the maximum rate.

   This is almost true,
   but it is imprecise (or makes a hidden assumption).
   What would you need to change about the statement to make it true?

8. A friend and I are at a party discussing our favorite networking protocols.
   While she explains TCP,
   I listen politely.
   Once she is finished,
   I expound on the beauty of IP,
   and she waits for me to say my piece.
   Then, since neither of us is talking,
   we both start speaking at the same time about other protocols.
   Once we have started,
   neither of us stops talking until we have finished our explanation.
   Sadly, nobody can really understand what either of us is saying,
   and they all use it as an excuse to leave and find more interesting
   conversations.

   What useful feature of a medium-access protocol were my friend and I
   missing?

9. Why can collisions still occur when nodes are listening before they send?
   Is this more likely to occur with nodes that are near one another or far
   from one another?

10. What is wrong with the following description?

    Adding collision detection to CSMA increases efficiency by reducing the
    number of collisions between transmitting nodes.

11. Why is the backoff interval after a collision usually chosen randomly?

12. What is exponential backoff?
    Why can it be better than using a fixed set of choices for backoff
    intervals?

13. Assume two CSMA/CD senders have had three collisions in a row with one
    another (and neither has experienced a previous collision).
    What is the probability that they collide with each other a fourth time in
    a row?

<!--
12. How are turn-taking protocols (e.g., polling) similar to TDMA?
    How are they different?

13. Compared to an IP address, a MAC address gives {more, less} information
    about a node's location.

14. What is one reason MAC addresses are useful when sending on a local network?
    In other words, why not just send directly to a certain IP address?

15. What is an ARP table?
    How are the entries in an ARP table determined?

16. Assume host `A` is on one network and host `B` is on a different network
    that is several hops away.
    Which of the following change during a packet's journey from `A` to `B`?
    (There is more than one possible answer depending on what assumptions you
    make.)
    * Source IP address
    * Destination IP address
    * Source MAC address
    * Destination MAC address
-->
