1.1 Overview of a network

1.2 Benefits of a network

Networks enable resource sharing like files and printers among multiple users.
They support various communication methods including email, voice calls (VoIP), video chats, and instant messaging.
Networks provide redundancy by allowing data backups to different locations, protecting against data loss.
They offer access to the internet, which is essential for many daily activities.
Networks can monitor connected devices and send alerts for issues or security.
Network administrators can manage multiple devices remotely, simplifying administration.

1.3 Day-to-day network examples

Networks connect various devices in our daily lives, enabling activities like streaming TV, online content access, and virtual meetings.
The Internet of Things (IoT) is expanding network connectivity beyond traditional devices to include smart home devices like thermostats, doorbells, and appliances.
Networks enable real-time alerts and remote control of devices, enhancing convenience and security.

1.4 OSI Model

The OSI model divides network functions into seven layers: Physical, Data Link, Network, Transport, Session, Presentation, and Application. Each layer has specific roles, such as cabling at the Physical layer and IP routing at the Network layer.
Different protocols operate at different layers, for example, TCP and UDP at the Transport layer, HTTP and DNS at the Application layer.
Data is referred to by different names at each of the first four layers: bits, frames, packets, and segments.
Memory aids like "Please Do Not Throw Sausage Pizza Away" help remember the layers from bottom to top.
The OSI model is a reference tool to help understand and categorize network components, not a rigid framework.

1.5 TCP/IP Model

The OSI model has seven layers: Physical, Data Link, Network, Transport, Session, Presentation, and Application.
The TCP/IP model typically has four layers, combining some OSI layers: it merges the Physical and Data Link layers into a single Network Access layer.
The OSI's Network layer is called the Internet layer in TCP/IP.
The top three OSI layers (Session, Presentation, Application) are combined into a single Application layer in TCP/IP.
Some variations of TCP/IP show five layers, but the key idea is that TCP/IP is a simpler, more practical reference model.

1.6 Common Network Layer Protocols

Layer 3 of the OSI model is the network layer, where IP (Internet Protocol) and ICMP (Internet Control Message Protocol) operate.
IP assigns addresses to devices and routes data packets to their destinations, similar to mailing a letter with source and destination addresses.
There are two IP versions in use today: IPv4 and IPv6.
ICMP is used for sending error messages and network diagnostics, such as the ping command that checks connectivity by sending Echo Request and receiving Echo Reply messages.

1.8 Common Transport Layer Protocols

Layer 4 of the OSI model is the transport layer, where data segments are handled.
TCP (Transmission Control Protocol) is a reliable, connection-oriented protocol that ensures data is received correctly, adding overhead that can slow transmission slightly.
UDP (User Datagram Protocol) is a faster, connectionless protocol that doesn't guarantee delivery, making it suitable for applications like streaming where occasional data loss is acceptable.

1.9 TCP three-way handshake

TCP establishes a reliable connection through a three-way handshake: the sender sends a SYN message, the receiver responds with SYN-ACK, and the sender replies with an ACK.
After the handshake, data segments are sent cautiously, with the sender waiting for acknowledgements before increasing the number of segments sent, a process managed by the window size.
TCP adjusts the window size exponentially to improve efficiency but reduces it if segments are lost, ensuring reliable data delivery.
Unlike TCP, UDP is connectionless and does not guarantee delivery, making TCP suitable for applications requiring reliability.

1.10 Application layer protocols and port numbers

Application layer protocols provide network services and use either TCP (reliable) or UDP (unreliable) at the transport layer.
Port numbers identify specific services on a server, e.g., HTTP uses TCP port 80, HTTPS uses TCP port 443, DNS uses TCP/UDP port 53, NTP uses UDP port 123, and DHCP uses UDP port 67.
Understanding these protocols and their ports is essential for network communication and security.