As a Communication Engineering student, keen on learning and growing, I took the TCP/IP course offered by Yonsei University courtesy of Coursera. Well, for starters, TCP stands for Transmission Control Protocol, whilst IP stands for Internet Protocol. These protocols are necessary for packet routing operations across the internet.

I would say that the course was self-explanatory, although some concepts would sound vague and hard to grasp if you do not have pre-knowledge of networking concepts. It is quite intriguing how TCP/IP is an important aspect of the CCNA exams. I wouldn't want to go deeply into explaining certain concepts for now as this is just a summary of what I learned.

The course started with an introduction to terminologies like Subnet mask, DNS, DHCP, IP address, etc.

Imagine a subnet mask as a filter that is used to determine if a particular IP address belongs to a subnet.

It is expedient to state at this point that a subnet refers to a subsidiary of a large network. More like a smaller portion of a large network.

Domain Name Servers (DNS) convert hostnames. eg: google.com to IP addresses. It is important to say at this point IPv4 (IP Version 4) addresses are ephemeral. They are used as identity tags when using the internet.

Picture IP address as a car plate number but in this case, it is only issued by a DHCP server when you want to use it for internet use and after that, it is taken back to be issued to another user.

Although DHCP servers try to reissue the same IP address to the same user when requested, if that IP address is free (not in use).

DHCP - Dynamic Host Configuration Protocol is basically a network management protocol that is used to assign network parameters (IP addresses, DNS, etc) using a client-server network model).

The course further went on to explain the DHCP operation, and IP Routing as well as explaining processes needed to design a network containing different subnets and a specified number of IP addresses.

The concept of CIDR (Classless Inter-Domain Routing) was also introduced. It basically refers to a notation structure where one could represent a network destination and subnet mask in one notation. Eg: 165.132.9.0/25 - where 165.132.9.0 is the network destination and /25 is the subnet mask, with a DNS notation of 255.255.255.128 (I would explain this in a later article. If you know how this was gotten, feel free to let me know in the comment section)

The course also compared the OSI/TCP model side by side, with each model layer explained, and further went on to explain what happens in a file transfer scenario.

I also played with the tracert command and critically analyzed the network hops from my home router to across various routers till it got to a particular server of interest. Another fun website I discovered was infosniper.net - which I used to check the location of IP addresses.

During the course, I learned about Explicit Congestion Notification, Differentiated services, ICMP, IGMP, UDP, OSPF, SCTP, and other networking protocols.

I also learned about internet routing, OSPF routing types, and functions. Here, concepts like IGP (Interior Gateway Protocol), EGP (Exterior Gateway Protocol), and BGP4 (Border Gateway Protocol version 4) were introduced.

Another interesting portion of the course was when the concept of the Dijkstra Shortest Path Algorithm was introduced. I quickly remembered learning Dynamic Programming - A course I offered during my middle year in Engineering Mathematics.

Concepts like Border Gateway Protocol (BGP), Address Resolution Protocol (ARP), Network Address Translation (NAT), Remote Procedure Call (RPC), File Transfer Protocol (FTP) as well as other protocols used for emails (POP, IMAP, SMTP) were also introduced.

Security and threat issues faced by internet users and how these threats can be reduced by applying appropriate security measures were discussed. The concept of TLS (Transport Layer Security), Wired Equivalent Privacy (WEP), and WPA (WiFi Protected Access) was also explained.

The course ended with an internet packet analysis using Wireshark.

I would recommend the course for network engineering enthusiasts who already have foreknowledge of networking concepts. You could as well combine the course with text-based materials or other video courses.

Until next time.....
