---
layout: project
type: project
image: images/Nw.png
title: Networking
permalink: projects/networking
# All dates must be YYYY-MM-DD format!
date: 2021-01-20
labels:
  - Network
  - Cisco Packet Tracer
summary: Network design and test using cisco packet tracer.
---

<img class="ui image" src="{{ site.baseurl }}/images/network.png">





## Networking Project

The above diagram is the network project that I've been working on in the spare time. 
The application that I'm using to build and test network components is the cisco packet tracer.
The packet tracer allows simulation of network connection to design and implement the network
topology based on the requirement. The network topology consists of routers, switches, and
servers that are communicating with each other. There are many servers where each has distinct 
functions such as DNS, Syslog, DHCP, etc. Routers implement OSPF routing protocols that allow 
devices on different networks to communicate with each other.


## Working Overview

The objective of this program is to set up an office network and communicate with other devices on a different network. Whenever there is a request for an IP address, the network will find the DHCP source and assign a new IP address to the requesting client. Likewise, there are centralized servers that serve various purposes; for example, the Syslog server is the centralized server whose task is to store log files from the different network components. The router has the required information for inter-network routing saved on its routing table, knowing where and how the data is being sent and received. 

 Upon completion of the project, I enhanced my networking knowledge and abilities. The project is a work in progress, so I will be updating the network over time.










    
