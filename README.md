## Problem Statement:

Choose a university/college campus and analyze its network topology. Map the network using Cisco Packet Tracer and identify the security controls that are in place, such as network segmentation, intrusion detection systems, firewalls, and authentication and authorization systems. Apply the knowledge gained from the NetAcad cyber security course to conduct an attack surface mapping to identify potential entry points for cyber-attacks. Propose countermeasures to mitigate these risks.

### The tool used: Cisco Packet Tracer

Cisco Packet Tracer is a network simulation and visualization tool developed by Cisco Systems. It is widely used to design, configure, and troubleshoot computer networks for educational and training purposes. Packet Tracer allows users to create virtual network topologies, connect devices, and simulate network behavior without the need for physical hardware.

## Tasks:
<ol>
<li>Campus Network Analysis</li>
<li>Network Mapping </li>
<li>Attack Surface Mapping</li>
<li>Secure Access Controls</li>
</ol>

## CAMPUS NETWORK ANALYSIS

### Network Topology of the campus:

Network topology refers to the arrangement and interconnection of network devices and components in a computer network. This document discusses the topology and various security measures employed in Computer Systems in our Institute. To begin, the campus has sufficient network facilities and security requirements installed priorly.

### Nature of the network:

The computers in a computer lab are linked into a local area network (LAN), which allows individual users to share resources.
<br>
Potential entry points for cyber attack:
<ol>
<li>Unsecure Trunks</li>
<li>Unused Open Ports</li>
<li>Server Vulnerabilities</li>
<li>Unprotected Endpoints</li>
<li>Weak Authentication or Security Software</li></ol> 

### Network Mapping  (with Cisco Packet Tracer)

Network mapping refers to the process of creating a visual representation of a computer network's structure, layout, and connectivity. It involves discovering and documenting various network elements, such as devices, routers, switches, servers, and their interconnections. 
The main purpose of network mapping is to gain a comprehensive understanding of the network's topology, allowing network administrators, engineers, or security professionals to manage, troubleshoot, and secure the network effectively. Here, we use Cisco Packet Tracer for the purpose. The following rooms of the Institute are considered for the network analysis.
<br>
I) Principal Room<ol>
1.1.	1 PC
1.2.	1 Laptop
1.3.	1 Switch
</ol>
II) Staff Room<ol>
2.1.	4 PCs
2.2.	3 Printers
2.3.	1 Switch
</ol>
III) Server Room<ol>
3.1.	3 Servers
3.2.	1 PC
3.3.	1 Switch
</ol>
IV) IT Lab<ol>
4.1.	1 Printer
4.2.	4 x 10 PCs + 1 PC
4.3.	1 Switch
</ol>
CSE Lab<ol>
5.1.	1 Printer
5.2.	4 x 10 PCs + 1 PC
5.3.	1 Switch
</ol>
DS Lab<ol>
6.1.	1 Printer
6.2.	4 x 10 PCs + 1 PC
6.3.	1 Switch
</ol>

### Learnings:

Role of Routers and Switches:
Routers focus on interconnecting multiple networks and making intelligent forwarding decisions based on IP addresses at the network layer. On the other hand, switches are responsible for local network connectivity and use MAC addresses at the data link layer to efficiently forward data frames within the same LAN, while reducing collision domains and creating a single broadcast domain. Both devices play critical roles in ensuring effective and scalable network communication.The switch is the network equipment to which all the computers are connected. A switch can be configured so the clients cannot connect to each other, to limit communication to groups created for a specific project and to grant or refuse access to external resources.

#### Functions of Servers
The function of a server is to receive, store, and share data. From there, you can run virus scans, manage spam filters, and install programs across the network. That makes network security management a lot less demanding, even when you have more members on your team. The server can also be used to filter the external information the clients can access, for example, blocking Facebook but leaving the Library of Congress accessible. The server can also store the profile of each student and back up their work from session to session.The researchers concluded that having a server for the computer laboratory will help the facilitator manage and maintain the security of the client's computers, such as monitoring applications, proper file sharing, and data keeping for better computer laboratory management.

#### Access ports
An access port is a type of switch port that is assigned to a specific VLAN (Virtual Local Area Network). Its primary function is to provide network connectivity to end-user devices, such as computers, printers, IP phones, and other network peripherals, within a local area network (LAN). 

#### Other End Devices
In Cisco Packet Tracer, end devices refer to network devices that serve as the sources or destinations of data packets in a simulated network. These devices are usually located at the edges of the network and represent devices that users interact with directly.
