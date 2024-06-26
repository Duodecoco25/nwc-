Network Architecture 
=========
Have you ever been busy working online, only to have “the internet go down”? As you know by now, the internet did not go down, you just lost your connection to it. It is very frustrating. With so many people in the world relying on network access to work and learn, it is imperative that networks are reliable. In this context, reliability means more than your connection to the internet. This topic focuses on the four aspects of network reliability.

The role of the network has changed from a data-only network to a system that enables the connections of people, devices, and information in a media-rich, converged network environment. For networks to function efficiently and grow in this type of environment, the network must be built upon a standard network architecture.

Networks also support a wide range of applications and services. They must operate over many different types of cables and devices, which make up the physical infrastructure. The term network architecture, in this context, refers to the technologies that support the infrastructure and the programmed services and rules, or protocols, that move data across the network.

As networks evolve, we have learned that there are four basic characteristics that network architects must address to meet user expectations:
Fault Tolerance
Scalability
Quality of Service (QoS)
Security

Fault Tolerance 
========
Scalability
Quality of Service (QoS)
Security

Fault Tolerance
A fault tolerant network is one that limits the number of affected devices during a failure. It is built to allow quick recovery when such a failure occurs. These networks depend on multiple paths between the source and destination of a message. If one path fails, the messages are instantly sent over a different link. Having multiple paths to a destination is known as redundancy.

Implementing a packet-switched network is one way that reliable networks provide redundancy. Packet switching splits traffic into packets that are routed over a shared network. A single message, such as an email or a video stream, is broken into multiple message blocks, called packets. Each packet has the necessary addressing information of the source and destination of the message. The routers within the network switch the packets based on the condition of the network at that moment. This means that all the packets in a single message could take very different paths to the same destination. In the figure, the user is unaware and unaffected by the router that is dynamically changing the route when a link fails.

The network topology consists of four routers with redundant links. At the top of the diagram is the Internet cloud with two connections at the bottom, each leading to a router. Below these routers is a connection to another router. Each bottom router connects back to both routers that connect to the Internet. The router on the bottom left is connected to a switch with three desktops and three IP phones. The router on the bottom right is connected to a switch with three desktops. The top left router has a red circle with a diagonal line. The top right router has a green arrow leading to the Internet. A text box reads: redundant connections allow for alternative paths if a device fails; the user exerience is unaffected.

![image](https://github.com/Duodecoco25/nwc-/assets/167957954/04f8e94d-2151-4e46-8794-db2975d3a148)

Scalability
=========
A scalable network expands quickly to support new users and applications. It does this without degrading the performance of services that are being accessed by existing users. The figure shows how a new network is easily added to an existing network. These networks are scalable because the designers follow accepted standards and protocols. This lets software and hardware vendors focus on improving products and services without having to design a new set of rules for operating within the network.

![image](https://github.com/Duodecoco25/nwc-/assets/167957954/7235385d-053f-45d0-8a98-9cf36ec4b8d5)


Quality of Service
=============
Quality of Service (QoS) is an increasing requirement of networks today. New applications available to users over networks, such as voice and live video transmissions, create higher expectations for the quality of the delivered services. Have you ever tried to watch a video with constant breaks and pauses? As data, voice, and video content continue to converge onto the same network, QoS becomes a primary mechanism for managing congestion and ensuring reliable delivery of content to all users.

Congestion occurs when the demand for bandwidth exceeds the amount available. Network bandwidth is measured in the number of bits that can be transmitted in a single second, or bits per second (bps). When simultaneous communications are attempted across the network, the demand for network bandwidth can exceed its availability, creating network congestion.

When the volume of traffic is greater than what can be transported across the network, devices will hold the packets in memory until resources become available to transmit them. In the figure, one user is requesting a web page, and another is on a phone call. With a QoS policy in place, the router can manage the flow of data and voice traffic, giving priority to voice communications if the network experiences congestion.The focus of QoS is to prioritize time-sensitive traffic. The type of traffic, not the content of the traffic, is what is important.

![image](https://github.com/Duodecoco25/nwc-/assets/167957954/56646ba7-0226-44de-8c3f-e260a1a76b23)


Network Security
=========
The network infrastructure, services, and the data contained on network-attached devices are crucial personal and business assets. Network administrators must address two types of network security concerns: network infrastructure security and information security.

Securing the network infrastructure includes physically securing devices that provide network connectivity and preventing unauthorized access to the management software that resides on them, as shown in the figure.

network topology with PCs and IP phones connected to a switch which is connected to a router that can protect the network with software and hardware security and by preventing physical access to network devices.

![image](https://github.com/Duodecoco25/nwc-/assets/167957954/c6de325a-08c4-467d-89cf-0be0209922e7)

Network administrators must also protect the information contained within the packets being transmitted over the network, and the information stored on network attached devices. In order to achieve the goals of network security, there are three primary requirements.

Confidentiality - Data confidentiality means that only the intended and authorized recipients can access and read data.
Integrity - Data integrity assures users that the information has not been altered in transmission, from origin to destination.
Availability - Data availability assures users of timely and reliable access to data services for authorized users.

Recent Trends
==========
You know a lot about networks now, what they are made of, how they connect us, and what is needed to keep them reliable. But networks, like everything else, continue to change. There are a few trends in networking that you, as a NetAcad student, should know about.

As new technologies and end-user devices come to market, businesses and consumers must continue to adjust to this ever-changing environment. There are several networking trends that affect organizations and consumers:

Bring Your Own Device (BYOD)
Online collaboration
Video communications
Cloud Computing


Bring Your Own Device (BYOD)
=========



The concept of any device, for any content, in any manner, is a major global trend that requires significant changes to the way we use devices and safely connect them to networks. This is called Bring Your Own Device (BYOD).

BYOD enables end users the freedom to use personal tools to access information and communicate across a business or campus network. With the growth of consumer devices, and the related drop in cost, employees and students may have advanced computing and networking devices for personal use. These include laptops, notebooks, tablets, smart phones, and e-readers. These may be purchased by the company or school, purchased by the individual, or both.

BYOD means any device, with any ownership, used anywhere.


