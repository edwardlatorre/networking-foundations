# Glossary of Key Terms 

Below are some useful terms related to computer hardware, software, and networking. This glossary is available for download from the Exercise Files folder. 

**auto MDI-X:** a feature typically found on Ethernet switches that automatically detects the required cable connection type (example: straight-through or crossover) and configures the connection appropriately
**autonomous AP:** a wireless access point that is individually managed and operates independently of other APs
**auxiliary port:** a port on some network devices (typically routers), traditionally used for remote access via a modem
**BiDi (bidirectional) transceiver:** a type of transceiver that can transmit and receive data on a single strand of fiber using different wavelengths of light
**broadcast domain:** a logical division of a network, where all devices can receive broadcast messages from any other device in the same domain; a broadcast domain does not span a router, because a router blocks broadcast traffic
**bus topology:** a network configuration where all devices are connected to a single cable, allowing only one device to transmit at a time; bus topologies are now considered legacy, but used to be found in 10BASE2 and 10BASE5 networks
**CAN (campus area network):** a network that interconnects multiple LANs within a limited geographical area, such as a university or business campus
**CAPWAP (control and provisioning of wireless access points):** a more recent protocol (as compared to LWAPP) used for communication between wireless LAN controllers and lightweight access points
**CSMA/CA (carrier sense multiple access with collision avoidance):** a network protocol used in wireless networks to reduce the likelihood of collisions
**CSMA/CD (carrier sense multiple access with collision detection):** a network protocol used in early Ethernet networks to manage access to a shared medium and handle collisions. Note that CSMA/CD was typically found in networks with either a bus topology or an Ethernet hub
**Cisco IOS (internetwork operating system):** the software used on Cisco Systems routers and current Cisco network switches
**Cisco IOS XE:** an evolution of Cisco IOS that uses a Linux kernel to enable some of the latest networking innovations
**collision domain:** a network segment where only one device can transmit at a time without causing a collision
**console port:** a port on network devices used for out-of-band management, typically requiring a special cable and terminal emulation software
**crossover cable:** an Ethernet cable where the transmit and receive pairs are crossed, typically used to connect similar devices directly (example: interconnecting two PCs)
**DHCP (dynamic host configuration protocol):** a network management protocol used to automate the process of configuring IP addressing on network devices
**DNS (domain name system):** a hierarchical and decentralized naming system for computers, services, or other resources connected to the Internet or a private network
**default route:** a routing table entry that specifies where to send packets when no other specific route matches the destination IP address
**EMI (electromagnetic interference):** disturbance that affects electrical circuits due to electromagnetic radiation or electromagnetic conduction
**Ethernet:** a widely used networking technology for local area networks (LANs), often using RJ-45 connectors and Cat5, Cat5e, or Cat6 cables
**firewall:** a network security device that monitors and controls incoming and outgoing network traffic based on predetermined security rules
**flooding:** the process where a switch sends a frame out all ports except the one it was received on when the frame’s destination MAC address is unknown
**full mesh:** a mesh topology where every node is connected directly to every other node.
**global configuration mode:** a configuration mode on Cisco devices where changes affect the entire system
**HTTP (hypertext transfer protocol):** an application-layer protocol for transmitting hypermedia documents, such as HTML, used as the foundation of data communication on the World Wide Web
**HTTPS (hypertext transfer protocol secure):** a secure version of HTTP that encrypts the data sent between a web browser and a website
hidden node problem: a situation in wireless networks where two clients can communicate with an access point but not with each other, potentially leading to collisions
**hub:** a basic Ethernet networking device that operates at Layer 1, repeating incoming signals to all connected devices without any intelligent forwarding
**ICMP (internet control message protocol):** a network layer protocol used by network devices to diagnose network communication issues
**IDS (intrusion detection system):** a network security appliance that monitors network traffic for suspicious activity and issues alerts when such activity is discovered
**IP (internet protocol):** a protocol used for addressing and routing packets of data so that they can travel across networks and arrive at the correct destination
**IPS (intrusion prevention system):** a network security appliance that monitors network traffic for suspicious activity and can automatically take action to prevent or block detected threats
**interface configuration mode:** a configuration mode on Cisco devices specific to configuring individual network interfaces
**IoT (internet of things):** the interconnection of everyday devices (example: thermostats, doorbells, televisions, or light bulbs) to the Internet, allowing them to be controlled over their network connections
**LAN (local area network):** a network that interconnects computers within a limited area, such as a home, office, or small group of buildings
**LWAPP (lightweight access point protocol):** a protocol that enables wireless LAN controllers to manage a collection of wireless access points. Note that LWAPP has mostly been replaced with the newer CAPWAP protocol
**lambda:** in networking, refers to a specific wavelength of light used in fiber-optic communication, often to separate traffic in a MAN.
**lightweight AP:** a wireless access point that is centrally managed by a wireless LAN controller
line configuration mode: a configuration mode on Cisco devices used to configure console, auxiliary, or virtual terminal lines
**MAC address table:** a table maintained by a switch that maps MAC addresses to specific ports, allowing for intelligent frame forwarding
**MAC address:** a unique identifier assigned to network interface hardware by the manufacturer
**MAN (metropolitan area network):** a computer network that interconnects users with computer resources in a geographic region of the size of a metropolitan area
**mesh topology:** a network configuration where each device is connected directly to every other device in the network
**multimode fiber (MMF):** a type of optical fiber that can carry multiple light rays, typically used for shorter distance communication
**NTP (network time protocol):** a networking protocol for clock synchronization between network devices, where the believability of a time source is measured by its stratum value (lower stratum values are more believable)
**NVRAM (non-volatile random access memory):** a type of memory that retains its information when power is turned off
network: a collection of interconnected devices communicating via various mediums such as copper cabling, optical fiber, or wireless connections
next-generation firewall (NGFW): a advanced firewall that combines traditional firewall capabilities with additional features such as deep packet inspection and application-level filtering
OSI model: a conceptual framework used to describe the functions of a networking system, consisting of seven layers
PAN (personal area network): a very small network that interconnects just two devices, such as a gaming console and its wireless controller
packet filter: a basic type of firewall that applies a set of rules to individual packets without considering the context of the traffic flow (example: whether a session was originated inside or outside of a trusted network)
partial mesh: a mesh topology where some nodes are connected to multiple other nodes, while some are connected only to those nodes with which they exchange the most data
plenum-rated cable: network cabling designed for use in plenum spaces of buildings, with special fire-retardant properties
privileged EXEC mode: an elevated access mode on Cisco devices that allows all commands and system modifications
RJ-45 connector: an 8-pin connector used for connecting computers into a network, commonly used with Ethernet cables
ring topology: a network configuration where each device is connected to two other devices, forming a ring
routing table: a data structure maintained by a router that contains information about known network destinations and how to reach them
running configuration: the current, active configuration on a Cisco device, stored in RAM
SCP (secure copy protocol): a network protocol that supports file transfers between hosts on a network using SSH for data transfer
SFP (small form-factor pluggable): a compact, hot-pluggable network interface module often found in Ethernet switches, which is available in a variety of media types (example: twisted pair or fiber optic)
STP (shielded twisted pair): a type of twisted pair cable that includes additional metallic shielding to further reduce electromagnetic interference
single-mode fiber (SMF): a type of optical fiber designed to carry only one path of light, in order to eliminate multi-mode delay distortion; SMF cabling is typically used for longer distance communication.
star topology: a network configuration where devices are connected to a central point, typically an Ethernet switch, forming a star-like pattern
startup configuration: the configuration stored in a Cisco device’s NVRAM, which loads when the device boots
stateful firewall: a type of firewall that keeps track of the state of network connections and makes filtering decisions based on the context of the traffic (example: whether a session was initiated from inside or outside of a trusted network)
straight-through cable: an Ethernet cable where the pin connections on both ends are identical, typically used to interconnect a network host with an Ethernet switch or to interconnect an Ethernet switch with a router
T568A and T568B: two standardized wiring schemes for terminating twisted pair cable in 8P8
TCP (transmission control protocol): a connection-oriented protocol that provides reliable, ordered, and error-checked delivery of data between applications running on hosts communicating over an IP network.
TFTP (trivial file transfer protocol): a simple file transfer protocol that allows a client to get a file from or put a file onto a remote host
transceiver: a device that can both transmit and receive signals, often used in network switches to provide flexible connectivity options
twisted pair cabling: a type of wiring in which wires in a cable are grouped into pairs (example: grouping an 8-conductor Ethernet cable into four pairs of wires), with each pair of wires twisted together to improve protection from electromagnetic interference.
UDP (user datagram protocol): a connectionless protocol that provides a way to send messages (example: datagrams) to other hosts on an IP network without requiring prior communications (example: as in the case of TCP’s three-way handshake) and without requiring acknowledgment that data successfully reaches the far end of a connection
UTP (unshielded twisted pair): a type of twisted pair cable that does not include additional shielding
user EXEC mode: the default privilege mode when accessing a Cisco device, providing limited access to basic monitoring commands; this mode is known as EXEC Level 1
VLAN (virtual local area network): a method of creating independent logical networks within a single physical network; typically, devices in a VLAN all belong to the same IP address space (example: a subnet) and comprise a broadcast domain
WAN (wide area network): a network that interconnects other networks over large geographical regions, often connecting offices in different locations
Wi-Fi: Refers to a collection of wireless networking protocols, based on the IEEE 802.11 standards, which allow devices to connect to a network using radio signals rather than cables
wireless access point (AP): a networking device that allows wireless devices to connect to a wired network using Wi-Fi