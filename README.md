# Computer-Networks
Compter Networks Questions!

## Define network 
A network is a set of devices that are connected with a physical media link. In a network, two or more nodes are connected by a physical link or two or more networks are connected by one or more nodes. A network is a collection of devices connected to each other to allow the sharing of data. 

## What do you mean by network topology, and explain types of them?
Network topology is the arrangement of nodes and links of a network.
Topologies are categorized as either physical network topology or logical network topology.
The topology of a network is key to determining its performance.
Network topology can be categorized into – Bus Topology, Ring Topology, Star Topology, Mesh Topology, Tree Topology.

## Define bandwidth, node and link?
Bandwidth is the data transfer capacity of a computer network in bits per second (Bps). The term may also be used colloquially to indicate a person’s capacity for tasks or deep thoughts at a point in time. A network is a connection setup of two or more computers directly connected by some physical mediums like optical fibre or coaxial cable. This physical medium of connection is known as a link, and the computers that it is connected to are known as nodes.

## Explain TCP model?
It is a compressed version of the OSI model with only 4 layers. It was developed by the US Department of Defence (DoD) in the 1860s. The name of this model is based on 2 standard protocols used i.e. TCP (Transmission Control Protocol) and IP (Internet Protocol).

1. Network Access/Link layer : Decides which links such as serial lines or classic Ethernet must be used to meet the needs of the connectionless internet layer. Ex – Sonet, Ethernet
2. Internet : The internet layer is the most important layer which holds the whole architecture together. It delivers the IP packets where they are supposed to be delivered. Ex – IP, ICMP.
3. Transport : Its functionality is almost the same as the OSI transport layer. It enables peer entities on the network to carry on a conversation. Ex – TCP, UDP(User Datagram Protocol)
4. Application : It contains all the higher-level protocols. Ex – HTTP, SMTP, RTP,DNS.

## Layers of OSI model!
There are majorly 2 main layers in the OSI model:
Physical Layer
Data Link Layer

## Significance of Data Link Layer-

It is used for transferring the data from one node to another node.
It receives the data from the network layer and converts the data into data frames and then attaches the physical address to these frames which are sent to the physical layer.
It enables the error-free transfer of data from one node to another node.

Functions of Data-link layer:

Frame synchronisation: Data-link layer converts the data into frames, and it ensures that the destination must recognize the starting and ending of each frame.
Flow control: Data-link layer controls the data flow within the network.
Error control: It detects and corrects the error occurred during the transmission from source to destination.
Addressing: Data-link layers attach the physical address with the data frames so that the individual machines can be easily identified.
Link management: Data-link layer manages the initiation, maintenance and termination of the link between the source and destination for the effective exchange of data.

## Define gateway, difference between gateway and router:

A node that is connected to two or more networks is commonly known as a gateway. It is also known as a router. It is used to forward messages from one network to another. Both the gateway and router regulate the traffic in the network. Differences between gateway and router: A router sends the data between two similar networks while gateway sends the data between two dissimilar networks. 

## What does ping command do ?

The “ping” is a utility program that allows you to check the connectivity between the network devices. You can ping devices using its IP address or name. 

## What is DNS, DNS forwarder, NIC, ? 

DNS:
1. DNS is an acronym that stands for Domain Name System.DNS was introduced by Paul Mockapetris and Jon Postel in 1983.
2. It is a naming system for all the resources over the internet which includes physical nodes and applications. It is used to locate resources easily over a network.
3. DNS is an internet which maps the domain names to their associated IP addresses.
4. Without DNS, users must know the IP address of the web page that you wanted to access.

DNS Forwarder : A forwarder is used with a DNS server when it receives DNS queries that cannot be resolved quickly. So it forwards those requests to external DNS servers for resolution. A DNS server which is configured as a forwarder will behave differently than the DNS server which is not configured as a forwarder. NIC stands for Network Interface Card. It is a peripheral card attached to the PC to connect to a network. Every NIC has its own MAC address that identifies the PC on the network. It provides a wireless connection to a local area network. NICs were mainly used in desktop computers. 

## What is MAC address ? 

A media access control address (MAC address) is a unique identifier assigned to a network interface controller (NIC) for use as a network address in communications within a network segment. 
