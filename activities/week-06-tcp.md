# General Questions

7. Explain why flow control is used in TCP and how it differs from congestion
control.

8. The formula for determining whether a host can send data into the TCP
connection based on flow control is
```
LastByteSent - LastByteAcked <= rwnd
```
Explain in your own words
* what the left-hand side of the formula means,
* what the right-hand side of the formula means, and
* how this formula works to institute flow control.

9. Does the above formula apply to flow control in UDP?
Why or why not?

10. When closing a TCP connection,
the host that sends the final segment
(an ACK to the final FIN)
waits for a period of time before actually closing the connection.
Why is this done (i.e., what problem could arise if it were not done)?
If this step were skipped,
would there be any way for the other side to close the connection?

11. Describe the similarities and differences in the mechanism for
rate-limiting in flow control vs congestion control.

12. Why is a triple duplicate ACK treated differently than a timeout for
purposes of congestion control?
