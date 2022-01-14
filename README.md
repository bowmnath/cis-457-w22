## Welcome to CIS 457!

This is the main website for the course.
The slides, schedule, and links to assignments, labs, projects, and videos,
as well as the official course policies,
will be posted here.
The course also uses other websites for specific purposes.
* [Piazza](https://www.piazza.com/gvsu/winter2022/cis457/home) is a question-and-answer forum.
*All official announcements will be sent through Piazza*,
and you are responsible for monitoring Piazza to keep up to date with
announcements
(Piazza by default will send an email when an announcement is posted).
    * Signup link:
      [https://www.piazza.com/gvsu/winter2022/cis457](https://www.piazza.com/gvsu/winter2022/cis457).
    * You can read the following [Piazza FAQ](misc/piazza-faq.md) if you have
      questions.
* [Prairielearn](https://prairielearn.engr.illinois.edu/pl/) is where you will
submit all of your assignments, labs, and projects.
After submitting to Prairielearn, don't forget to update the
["Grade me" spreadsheet](https://docs.google.com/spreadsheets/d/1FF58ERCKb0UBHvipfZFfY2RrHKgqX_KO0SnPn22OZLI/edit?usp=sharing)
as described in the syllabus.
* [ClassTranscribe](https://classtranscribe.illinois.edu/) is where the videos
will be hosted.

That seems like a lot to monitor,
but don't worry -- you really need only actively follow Piazza.
I will release announcements there any time assignments or videos are assigned,
and I will post links to them directly on this page.

Be sure to read through the [syllabus](syllabus.md) for course policies,
contact information, and other important info.

## Schedule

** Note: This is an estimated timeline and subject to change. **

| Week | Topics | Readings | Deliverables |
| ---- | ------ | -------- | ------------ |
|  1   | Introduction to Networking<br>[intro slides](slides/intro-intro.pdf)<br>[network core slides](slides/intro-core.pdf)<br>[protocol stack slides](slides/intro-protocols.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=ebdb1fdc-4043-4830-bd71-efc229385333) | Chapter 1<br>[In-class activities](activities/week-01-intro.md) | |
|  2   | Application Layer<br>[application-layer intro slides](slides/app-intro.pdf)<br>[application-transport interface slides](slides/app-transport.pdf)<br>HTTP<br>[HTTP slides](slides/app-http-intro.pdf)<br>[HTTP format slides](slides/app-http-format.pdf)<br>[cookies slides](slides/app-http-cookies.pdf)<br>[delay slides](slides/intro-delay-intensity.pdf)<br>[throughput slides](slides/intro-throughput.pdf)<br>[web cache slides](slides/app-http-cache.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=296dd3bf-3e8c-457e-b44c-98498a10bb85) | | [Lab partner survey](https://forms.gle/HZidE7WVyYJSkunY8) -- Monday at the latest<br>[Intro Lab](https://www.prairielearn.org/pl/course_instance/128994) -- Tuesday, Jan. 18 (suggested)<br>[Syllabus quiz](https://www.prairielearn.org/pl/course_instance/128994/assessment/2316403) -- Wednesday, Jan. 19 |
|  3   | Application Layer<br><br>DNS<br>[dns intro slides](slides/app-dns-intro.pdf)<br>[dns structure slides](slides/app-dns-architecture.pdf)<br>[dns protocol slides](slides/app-dns-protocol.pdf)<br>Email<br>[email intro slides](slides/app-smtp-intro.pdf)<br>[SMTP slides](slides/app-smtp-protocol.pdf)<br>[access protocol slides](slides/app-smtp-access.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=23cc90af-7ba4-48e5-8643-b1dd6bf2d6ca) | | |
|  4   | Socket Programming<br>[socket programming slides](slides/app-socket.pdf)<br><br>Transport Layer<br>[multiplexing slides](slides/tr-multiplexing.pdf)<br>[UDP slides](slides/tr-udp.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=a26da01d-d411-41af-ac59-822cd72d0f87) | | |
|  5   | Transport Layer<br>[reliable data transfer slides](slides/tr-reliable.pdf)<br>[pipelined reliable transfer slides](slides/tr-pipeline.pdf)<br>[Go-Back-N slides](slides/tr-gbn.pdf)<br>[Selective Repeat slides](slides/tr-sr.pdf)<br>TCP<br>[TCP slides](slides/tr-tcp-general.pdf)<br>[sequence number and ACK slides](slides/tr-tcp-ack.pdf)<br>[reliable transfer in TCP slides](slides/tr-tcp-reliable.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=283bab64-c2c7-44de-bc95-33dcb5b66e6d) | | |
|  6   | Transport Layer<br><br>TCP<br>[flow control slides](slides/tr-flow-control.pdf)<br>[TCP connection slides](slides/tr-connection.pdf)<br>TCP congestion control<br>[congestion slides](slides/tr-congestion.pdf)<br>[congestion control intro](slides/tr-cong-control-basics.pdf)<br>[congestion control policy](slides/tr-cong-control-policy.pdf)<br>[congestion control performance](slides/tr-cong-control-perf.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=9d94065b-83b9-45cd-8cd2-6925a71baea6) | | |
|  7   | Network Layer<br>[switching](slides/intro-switching.pdf)<br>[network intro](slides/net-intro.pdf)<br>[routers](slides/net-routers.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=c4ef3fdd-5885-4e63-a2ff-76226211bc52) | | |
|  8   | Network Layer<br>[IPv4](slides/net-datagram.pdf)<br>[Subnets](slides/net-addressing.pdf)<br>[DHCP](slides/net-dhcp.pdf)<br>[NAT](slides/net-nat.pdf)<br>[IPv6](slides/net-ipv6.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=fad1d787-6f4a-46e6-bff4-818e19e8eac9) | | **Midterm Exam** - Tuesday, March 1 |
|  9   | **Spring Break** | | |
|  10  | Network Layer (Routing)<br>[control plane intro](slides/net-control-intro.pdf)<br>[link state](slides/net-link-state.pdf)<br>[distance vector](slides/net-distance-vector.pdf)<br>[OSPF](slides/net-ospf.pdf)<br>[BGP](slides/net-bgp.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=bef00e2a-1d46-4edd-9c83-de71441cb903) | | |
|  11  | Network Control and Management<br>[ICMP and SNMP](slides/net-management.pdf)<br><br>Link Layer<br>[intro](slides/link-intro.pdf)<br>[error detection](slides/link-error-detection.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=c3899d63-20ad-49d6-ae5c-4df98094b7c3) | | |
|  12  | Link Layer -- Multiple Access<br>[TDMA and FDMA](slides/link-multiple-access-partition.pdf)<br>[ALOHA](slides/link-multiple-access-aloha.pdf)<br>[CSMA](slides/link-multiple-access-csma.pdf)<br>[taking turns](slides/link-multiple-access-turns.pdf)<br><br>MAC addressing and ARP<br>[MAC and ARP](slides/link-mac-arp.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=6d8db068-72a4-40dd-b99e-e65512dc27b1) | | |
|  13  | Ethernet<br>[ethernet](slides/link-ethernet.pdf)<br>[switches](slides/link-switches.pdf)<br>[web request](slides/link-web-request.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=60791c57-82d0-4382-a24b-eaa8ce5aea85) | | |
|  14  | Wireless and Mobile Networks<br>[intro](slides/wireless-intro.pdf)<br>[issues](slides/wireless-issues.pdf)<br>[CDMA](slides/wireless-cdma.pdf)<br>[WiFi (802.11)](slides/wireless-wifi-intro.pdf)<br>[CSMA/CA](slides/wireless-wifi-csma.pdf)<br>[802.11 frame](slides/wireless-wifi-frame.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=858c3622-1cbd-4e56-ab78-be765d53e582) | | |
|  15  | Security<br>[intro](slides/security-intro.pdf)<br>[symmetric-key cryptography](slides/security-encryption-symmetric.pdf)<br>[public-key cryptography](slides/security-encryption-public.pdf)<br>[digital signatures](slides/security-digital-signature.pdf)<br>[securing email](slides/security-email.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=67a5e89a-be16-4038-aeeb-79bbc86e438a) | | |
|  16  | **Final Exam** | | |
