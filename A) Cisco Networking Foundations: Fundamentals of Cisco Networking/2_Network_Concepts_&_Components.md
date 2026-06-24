# 2. Network Concepts & Components

**2.1  CSMA/CD vs. CSMA/CA**

* In early bus topologies, devices shared a single cable and used CSMA/CD (Carrier Sense Multiple Access with Collision Detection) to listen before transmitting and detect collisions, retransmitting data after random delays.
* Hubs created star topologies but still relied on CSMA/CD, with hubs sending jamming signals to notify devices of collisions.
* Switches largely replaced hubs, reducing collisions by creating separate collision domains for each port.
* Wireless networks use CSMA/CA (Carrier Sense Multiple Access with Collision Avoidance) because devices can't detect collisions directly; they try to avoid collisions and rely on higher-layer protocols for error correction.
* The "hidden node problem" in wireless networks occurs when devices are out of range of each other but still communicate with the access point, potentially causing collisions.

**2.2 Hubs & Switches**

* Unlike hubs, switches learn which devices (MAC addresses) are connected to each port and use this information to forward frames only to the intended recipient, reducing unnecessary network traffic.
* Initially, when a switch doesn't know a device's location, it floods the frame to all ports except the one it came from, allowing it to learn the device's MAC address when it responds.
* Once the switch's MAC address table is populated, communication between devices is efficient and direct, improving network performance and scalability.

**2.3 Routers **

* Routers interconnect different networks and use IP routing tables to decide where to send packets based on their destination IP addresses.
* A default route is used by routers to forward packets when no specific route to the destination is known, typically pointing to the internet.
* When multiple routes exist, routers choose the most specific route with the longest subnet mask prefix.
* Routers operate at Layer 3 of the OSI model, handling packets and IP addresses, unlike switches (Layer 2, frames and MAC addresses) and hubs (Layer 1, bits).

**2.4 Collision and broadcast domains**

* A collision domain is a network segment where only one frame can be sent at a time; hubs create a single collision domain for all connected devices, while switches provide separate collision domains per port.
* A broadcast domain is a network area where a broadcast packet is sent to all devices; all ports on a switch belong to the same broadcast domain by default, but routers separate broadcast domains by not forwarding broadcasts between their ports.
* VLANs (Virtual Local Area Networks) can logically segment a switch into multiple broadcast domains, requiring routing to communicate between them.

**2.5 Wireless access points (APs)**

* Wireless networking (often called WiFi) allows devices to connect via radio signals to wireless access points (APs), which then connect to the wired network through switches.
* APs can have multiple antennas to communicate with several devices at once, and some APs use mesh mode to extend wireless coverage without direct wired connections.
* There are two main ways to manage APs: autonomous APs are managed individually, suitable for small setups, while lightweight APs are centrally managed via a wireless LAN controller, offering easier administration for larger networks.
* Protocols like LWAPP (older) and CAPWAP (newer) are used for communication between lightweight APs and controllers.

**2.6 Firewalls**

* Firewalls protect internal networks from outside threats by controlling incoming and outgoing traffic.
* Packet filter firewalls use basic rules but can't track session return traffic, making them less effective for internet access.
* Stateful firewalls track outgoing sessions and allow corresponding return traffic, improving security.
* Next generation firewalls offer deep packet inspection, content filtering, and can detect threats even in encrypted traffic for more granular protection.

**2.8 Intrusion detection and prevention systems**

* An IDS sensor monitors copies of network traffic to detect known attack signatures and alerts the firewall to block malicious sources, but it does not block traffic itself.
* An IPS sensor sits inline with network traffic, actively inspecting and blocking malicious packets before they reach the network.
* IDS provides detection and alerting after traffic passes through, while IPS provides proactive prevention by stopping attacks in real time.

**2.9 Examples of network topologies**

* Star topology is the most common today, with devices connected to a central switch. It offers simplified wiring and fault tolerance if one link fails, but the central switch can be a single point of failure unless redundancy is added.
* Ring topology is often used in metropolitan area networks (MANs), using fiber optics with different wavelengths (Lambdas) to keep customer traffic separate and dual rings for redundancy.
* Bus topology connects multiple devices on a single segment but allows only one device to communicate at a time; it's rarely used in modern networks due to its limitations.

**2.10 Mesh topologies**

* A full mesh topology connects every site directly to every other site, providing optimal communication paths but requiring many links, which makes it expensive and hard to scale.
* The number of links needed in a full mesh grows quickly with more sites (e.g., 10 links for 5 sites, 45 links for 10 sites).
* Partial mesh topology reduces the number of links by removing less-used connections, which helps scalability and lowers costs, but some traffic may take less direct paths.