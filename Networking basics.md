Networking basics
=

![](https://gitlab.dclabra.fi/wiki/uploads/upload_26251536b01fc4cf3714cc6643800009.png)

## Physical layer (Layer 1)
![](https://gitlab.dclabra.fi/wiki/uploads/upload_10775124bda471046d298f9a135f3c5a.png)
### Network topologies
The three basic network topologies in common use at the Physical Layer today are **bus, star, and ring**. Although many variations of the four basic types (meshed, Fiber Distributed Data Interface [FDDI], star-bus, star-ring) exist, we stick to the basics here.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_f1857c63c2799fac76a20dc619bf167e.png)

#### Bus

In a bus (or linear bus) topology, all devices are connected to a single cable (the backbone) that’s terminated on both ends. Bus networks are ideal for smaller networks because they’re inexpensive and easy to install. However, in a larger environment, they’re impractical because the media have physical limitations, the backbone is a single point of failure (a break anywhere on the network affects the entire network), and tracing a fault in a large network can be extremely difficult.

#### Star

In a star topology, each individual node on the network is directly connected to a central hub or concentrator. All data communications must pass through the hub, which can become a bottleneck or single point of failure. Star topologies are more expensive than bus topologies because of the additional hardware (hubs) and cable lengths. However, a star topology is ideal for larger environments and is the most common basic topology in use today. A star topology is also easy to install and maintain, and network faults are easily isolated without affecting the rest of the network.

#### Ring

A ring topology is a closed loop connecting end devices in a continuous ring. Functionally, this is achieved by connecting individual devices to a Multistation Access Unit (MSAU or MAU). Physically, this gives the ring topology the appearance of a star topology. Ring topologies are common in token-ring and FDDI networks.

### Analog and digital signaling
* Analog signaling conveys information through a continuous signal by using variations of wave amplitude, frequency, and phase.
* Digital signaling conveys information in pulses through the presence or absence (on-off) of electrical signals.

### Cable and connector types

Cables carry the electrical or light signals that represent data between devices on a network. Signaling over cable medium is classified as either baseband or broadband. Baseband signaling uses a single channel for transmission of digital signals and is common in LANs using twisted pair cabling. Broadband signaling uses many channels over a range of frequencies for transmission of analog signals including voice, video, and data. The three basic cable types used in networks are coaxial, twisted pair, and fiber optic

#### Coaxial cable

Using coaxial (abbreviated as coax and pronounced koh-axe) cable was very common in the early days of LANs and is rebounding (sort of) with the emergence of broadband networks. Coax cable consists of a single, solid copper-wire core, surrounded by a plastic or Teflon insulator, braided-metal shielding, and (sometimes) a metal foil wrap, all covered with a plastic sheath. This construction makes the cable very durable and resistant to Electromagnetic Interference (EMI) and Radio Frequency Interference (RFI) signals.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_68bb41ad6f844148e0c9756e3af8e86b.png)

Coax cable comes in two flavors, thick and thin:

* Thick: Also known as RG8 or RG11 or thicknet. Thicknet cable uses a screw-type connector, known as an Attachment Unit Interface (AUI).
* Thin: Also known as RG58 or thinnet. Thinnet cable is typically connected to network devices by using a bayonet-type connector, known as a BNC connector.

#### Twisted pair cable

Twisted pair cable is the most popular LAN cable in use today because it’s lightweight, flexible, inexpensive, and easy to install. One easily recognized example of twisted pair cable is common telephone wire. Twisted pair cable consists of copper-wire pairs that are twisted together to improve the transmission quality of the cable. Currently, seven classes of twisted pair cable are defined. However, only CAT-5, CAT-5e, and CAT-6 cable are typically used for networking.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_ea45a5f07ff460b523fd243ef4c38ee8.png)
![](https://gitlab.dclabra.fi/wiki/uploads/upload_cc9f74068dd830a8161d506fa86a2d5f.png)

Twisted pair cable is terminated with an RJ-type terminator. The three common types of RJ-type connectors are RJ-11, RJ-45, and RJ-49. Although these connectors are all similar in appearance (particularly RJ-45 and RJ-49), only RJ-45 connectors are used for LANs. RJ-11 connectors are used for analog phone lines, and RJ-49 connectors are commonly used for Integrated Services Digital Network (ISDN) lines and WAN interfaces.

#### Fiber optic cable

Fiber optic cable, the most expensive type of network cabling - but also the most reliable - is typically used in backbone networks and high-availability (FDDI) networks. Fiber optic cable carries data as light signals rather than as electrical signals. Fiber optic cable consists of a glass core or bundle, a glass insulator (commonly known as cladding), Kevlar fiber strands (for strength) and a polyvinyl chloride (PVC) or Teflon outer sheath. Advantages of fiber optic cable include higher speeds, longer distances, and resistance to interception and interference. Fiber optic cable is terminated with an SC-type, ST-type, or LC-type connector.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_ccffd6b9d2a9ff2c405975617bb35e92.png)
![](https://gitlab.dclabra.fi/wiki/uploads/upload_2e26735288ceeccfe97807a94481c93a.png)

### Interface types

The interface between the Data Terminal Equipment (DTE) and Data Communications Equipment (DCE), which we discuss in the upcoming section “Networking equipment,” is specified at the Physical Layer.

Network topologies, cable and connector types, and interfaces are defined at the Physical Layer of the OSI model.

Common interface standards include:

* EIA/TIA-232: This standard supports unbalanced circuits at signal speeds of up to 64 Kbps (formerly known as RS-232).
* EIA/TIA-449: A faster version of EIA/TIA-232, this standard supports longer cable runs and speeds of up to 2 Mbps.
* V.24. CCITT: (Formerly ITU-T.) This standard is essentially the same as the EIA/TIA-232 standard.
* V.35. CCITT: (Formerly ITU-T.) This standard describes a synchronous communications protocol between network access devices and a packet network with speeds of up to 48 Kbps.
* X.21bis. CCITT: (Formerly ITU-T.) This standard defines the communications protocol between DCE and DTE in an X.25 network. It is essentially the same as the EIA/TIA-232 standard.
* High-Speed Serial Interface (HSSI): This network standard was developed to address the need for high-speed (up to 52 Mbps) serial connections over WAN links.

### Networking equipment


Networking devices that operate at the Physical Layer include Network Interface Cards (NICs), network media (cabling/connectors/interfaces, which we discuss in the earlier section “Cable and connector types”), repeaters, and hubs.

**Network Interface Cards (NICs)** are used to connect a computer to the network. NICs may be integrated on a computer motherboard or installed as an adapter card, such as an ISA, PCI, or PC card.

**A repeater** is a nonintelligent device that simply amplifies a signal to compensate for attenuation (signal loss) and extend the length of the cable segment.

**A hub** (or concentrator) is used to connect multiple LAN devices together, such as servers and workstations. The two basic types of hubs are


* Passive: Data enters one port and exits all other ports without any signal amplification or regeneration.
* Active: Combines the features of a passive hub and repeater. Also known as a multi-port repeater.

**A switch** is used to connect multiple LAN devices together. Unlike a hub, a switch does not send outgoing packets to all devices on the network, but instead sends packets only to actual destination devices.

## Data Link Layer (Layer 2)

The Data Link Layer ensures that messages are delivered to the proper device across a physical network link. This layer also defines the networking protocol (for example, Ethernet and token-ring) used for sending and receiving data between individual devices. The Data Link Layer formats messages from layers above into frames for transmission, handles point-to-point synchronization and error control, and can perform link encryption.

The Data Link Layer consists of two sublayers: the Logical Link Control (LLC) and Media Access Control (MAC) sublayers.

The Logical Link Control (LLC) sublayer is defined in Institute of Electrical and Electronic Engineers (IEEE) standards 802.1 (Internetworking) and 802.2 (Logical Link Control). The LLC sublayer operates between the Network Layer above and the MAC sublayer below. The LLC sublayer performs the following three functions:


* Provides an interface for the MAC sublayer by using Source Service Access Points (SSAPs) and Destination Service Access Points (DSAPs)
* Manages the control, sequencing, and acknowledgement of frames being passed up to the Network Layer or down to the Physical Layer
* Bears responsibility for timing and flow control. Flow control monitors the flow of data between devices to ensure that a receiving device, which may not necessarily be operating at the same speed as the transmitting device, is not overwhelmed

The Media Access Control (MAC) sublayer is defined in IEEE standards 802.3 (Ethernet), 802.4 (Physical Bus), 802.5 (Token Ring), and 802.12 (High-speed Networks).

The Logical Link Control (LLC) and Media Access Control (MAC) are sublayers of the Data Link Layer.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_2d9587f5e0ebedec8617232041eb3e54.png)

The MAC sublayer operates between the LLC sublayer above and the Physical Layer below. It is primarily responsible for framing and performs the following three functions:

* Performs error control: Error control is performed by using a cyclic redundancy check (CRC). A CRC is a simple mathematical calculation or checksum used to create a message profile (analogous to a simple message digest, which we discuss in Chapter 8). The CRC is re-calculated by the receiving device. If the calculated CRC doesn’t match the received CRC, the packet is dropped and a request to resend is transmitted.
* Identifies hardware device (or MAC) addresses: A MAC address (also known as a hardware address or physical address) is a 48-bit address that is encoded on each device by its manufacturer. The first 24 bits identify the manufacturer or vendor. The second 24 bits uniquely identify the device.
* Controls media access: The three basic types of media access are as follows:
* Contention: In contention-based networks, individual devices must vie for control of the physical network medium. This type of network is ideally suited for networks characterized by small bursts of traffic. Ethernet networks use a contention-based method, known as Carrier-Sense Multiple Access Collision Detect (CSMA/CD), in which all stations listen for traffic on the physical network medium. If the line is clear, any station can transmit data. However, if another station attempts to transmit data at the same time, a collision occurs, the traffic is dropped, and both stations must wait a random period of time before attempting to re-transmit. Another slight variation of the CSMA/CD method, used in Apple LocalTalk networks, is known as Carrier-Sense Multiple Access Collision Avoidance (CSMA/CA).
* Token passing: In token-passing networks, individual devices must wait for a special frame, known as a token, before transmitting data across the physical network medium. This type of network is considered deterministic (transmission delay can be reliably calculated and collisions don’t occur) and is ideally suited for networks with large, bandwidth-consuming applications that are delay sensitive. Token Ring, FDDI, and ARCnet networks all use various token-passing methods for media access control.
* Polling: In polling networks, individual devices (secondary hosts) are polled by a primary host to see whether they have data to be transmitted. Secondary hosts can’t transmit until permission is granted by the primary host. Polling is typically used in mainframe environments.
* 
The Logical Link Control (LLC) and Media Access Control (MAC) are sub-layers of the Data Link Layer.

### LAN protocols and transmission methods

Common LAN protocols are defined at the Data Link (and Physical) Layer. They include the following:


* ARCnet: The ARCnet protocol is one of the earliest LAN technologies developed. It transports data to the physical LAN medium by using the token-passing media access method that we discuss in the preceding section. It is implemented in a star topology by using coaxial cable. ARCnet provides slow but predictable network performance.
* Ethernet: The Ethernet protocol transports data to the physical LAN medium by using CSMA/CD (which we discuss in the preceding section) and is designed for networks characterized by sporadic, sometimes heavy traffic requirements. Ethernet is the most common LAN protocol used today and is implemented in a bus topology over coaxial or twisted pair cabling (which we also discuss in the preceding section). Ethernet operates at speeds up to 10 Mbps. Two recent enhancements to the Ethernet protocol include Fast Ethernet (speeds up to 100 Mbps over CAT-5 twisted pair or fiber optic cabling) and Gigabit Ethernet (speeds up to 1000 Mbps over CAT-5e or CAT-6 twisted pair or fiber optic cabling).
* Token-Ring: The Token-Ring protocol transports data to the physical LAN medium by using the token-passing media access method that we discuss in the preceding section. Originally developed by IBM, token-ring refers to both IBM Token-Ring and IEEE 802.5. All nodes are attached to a Multistation Access Unit (MSAU) in a logical ring (physical star) topology. One node on the token-ring network is designated as the active monitor and ensures that no more than one token is on the network at any given time. (Variations permit more than one token on the network.) If the token is lost, the active monitor is responsible for ensuring that a replacement token is generated. Token-ring networks operate at speeds of 4 and 16 Mbps.
* Fiber Distributed Data Interface (FDDI): The FDDI protocol transports data to the physical LAN medium by using the token-passing media access method that we discuss in the preceding section. It’s implemented as a dual counter-rotating ring over fiber optic cabling at speeds up to 100 Mbps. All stations on a FDDI network are connected to both rings. During normal operation, only one ring is active. In the event of a network break or fault, the ring wraps back through the nearest node onto the second ring.
* 
LAN data transmissions are classified as:


* **Unicast:** Packets are sent from the source to a single destination device by using a specific destination IP address
* **Multicast:** Packets are copied and sent from the source to multiple destination devices by using a special multicast IP address that the destination stations have been specifically configured to use
* **Broadcast:** Packets are copied and sent from the source to every device on a destination network by using a broadcast IP address

WAN technologies and protocols

WAN technologies function at the lower three layers of the OSI Reference Model (the Physical, Data Link, and Network Layers), primarily at the Data Link Layer. WAN protocols define how frames are carried across a single data link between two devices. These include


* Point-to-point links: Provide a single, preestablished WAN communications path from the customer’s network, across a carrier network (such as a Public Switched Telephone Network [PSTN]), to a remote network. These include:
    * Leased lines: A transmission line reserved by a communications carrier for the exclusive use of a customer
    * Serial Line IP (SLIP): The predecessor of Point-to-Point Protocol (PPP), SLIP was originally developed to support TCP/IP networking over low-speed asynchronous serial lines (such as dial-up modems) for Berkeley UNIX computers
    * Point-to-Point Protocol (PPP): The successor to SLIP, PPP provides router-to-router and host-to-network connections over synchronous and asynchronous circuits. It is a more robust protocol than SLIP and provides additional built-in security mechanisms. PPP is far more common than SLIP in modern networking environments
* Circuit-switched networks: In a circuit-switched network, a dedicated physical circuit path is established, maintained, and terminated between the sender and receiver across a carrier network for each communications session (the call). This network type is used extensively in telephone company networks and functions similarly to a regular telephone call. Circuit-switched networks are ideally suited for always-on connections with constant traffic. Examples include
    * Integrated Services Digital Network (ISDN): ISDN is a communications protocol that operates over analog phone lines that have been converted to use digital signaling. ISDN lines are capable of transmitting both voice and data traffic. ISDN defines a B-channel for data, voice, and other services, and a D-channel for control and signaling information. With the introduction and widespread adoption of DSL, ISDN has largely fallen out of favor in the United States and is no longer available in many areas
    * Digital Subscriber Lines (xDSL): xDSL uses existing analog phone lines to deliver high bandwidth connectivity to remote customers. Table 5-7 describes several types of xDSL lines that are currently available
* Packet-switched networks: In a packet-switched network, devices share bandwidth (by using statistical multiplexing) on communications links to transport packets between a sender and receiver across a carrier network. This type of network is more resilient to error and congestion than circuit-switched networks. Packet-switched networks are ideally suited for on-demand connections with bursty traffic. Examples of packet-switched networks include:
    * Frame Relay: Frame Relay is a packet-switched, standard protocol that handles multiple virtual circuits by using High-level Data Link Control (HDLC) encapsulation (which we discuss later in this section) between connected devices. Frame Relay utilizes a simplified framing approach with no error correction and Data Link Connection Identifiers (DLCI) addressing to achieve high speeds across the WAN. Frame Relay can be used on Switched Virtual Circuits (SVCs) or Permanent Virtual Circuits (PVCs). An SVC is a temporary connection that’s dynamically created (circuit establishment phase) to transmit data (data transfer phase) and then disconnected (circuit termination phase). PVCs are permanently established connections. Because the connection is permanent, a PVC doesn’t require the bandwidth overhead associated with circuit establishment and termination.Switched Multimegabit Data Service (SMDS): SMDS is a high-speed, packet-switched, connectionless-oriented, datagram-based technology available over public switched networks. Typically, companies that exchange large amounts of data bursts with other remote networks use it.
    * Asynchronous Transfer Mode (ATM): ATM is a very high-speed, low-delay technology that uses switching and multiplexing techniques to rapidly relay fixed-length (53-byte) cells containing voice, video, or data. Cell processing occurs in hardware that reduces transit delays. ATM is ideally suited for fiber optic networks with bursty applications.


* Other WAN protocols: Two other important WAN protocols defined at the Data Link Layer include
    * Synchronous Data Link Control (SDLC): The SDLC protocol is a bit-oriented, full-duplex serial protocol that was developed by IBM to facilitate communications between mainframes and remote offices. It defines and implements a polling media-access method, in which the primary (front-end) polls the secondaries (remote stations) to determine whether communication is required
    * High-level Data Link Control (HDLC): The HDLC protocol is a bit-oriented, synchronous protocol that was created by the ISO to support point-to-point and multipoint configurations. Derived from SDLC, it specifies a data encapsulation method for synchronous serial links and is the default for serial links on Cisco routers. Unfortunately, various vendor implementations of the HDLC protocol are incompatible.

### Networking equipment at the Data Link Layer


Networking devices that operate at the Data Link Layer include bridges, switches, DTEs, and DCEs.


* A bridge is a semi-intelligent repeater used to connect two or more (similar or dissimilar) network segments. A bridge maintains an Address Resolution Protocol (ARP) cache containing the MAC addresses of individual devices on connected network segments. When a bridge receives a data signal, it checks its ARP cache to determine whether the destination MAC address is on the local network segment. If it’s determined to be local, the data signal isn’t forwarded. However, if the MAC address isn’t local, the bridge forwards (and amplifies) the data signal to all other connected network segments. A serious networking problem associated with bridges is a broadcast storm, in which broadcast traffic is automatically forwarded by a bridge, thus effectively flooding a network.
* A switch is essentially an intelligent hub that uses MAC addresses to route traffic. Unlike a hub, a switch transmits data only to the port connected to the destination MAC address. This transmission method creates separate collision domains (called network segments) and effectively increases the data transmission rates available on the individual network segments. Additionally, a switch can be used to implement Virtual LANs (VLANs) to logically segregate a network and limit broadcast domains. Switches are traditionally considered to be Layer 2 (or Data Link Layer) devices, although newer technologies allow switches to function at the upper layers including Layer 3 (the Network Layer) and Layer 7 (the Application Layer).

### Asynchronous and synchronous communications

Asynchronous communication transmits data in a serial stream with control data (start and stop bits) embedded in the stream to indicate the beginning and end of characters. Asynchronous devices must communicate at the same speed, which is controlled by the slower of the two communicating devices. Because no internal clocking signal is used, parity bits are used to reduce transmission errors.

Synchronous communications utilize an internal clocking signal to transmit large blocks of data, known as frames. Synchronous communication is characterized by very high-speed transmission rates.


Data Terminal Equipment (DTE) is a general term used to classify devices at the user end of a user-to-network interface (such as computers). A DTE connects to Data Communications Equipment (DCE; also know as a Data Circuit-Terminating Equipment), which consists of devices at the network end of a user-to-network interface. The DCE provides the physical connection to the network, forwards network traffic, and provides a clocking signal to synchronize transmissions between the DCE and DTE. Examples of DCEs include NICs (Network Interface Cards), modems, and CSU/DSUs (Channel Service Unit/Data Service Unit).

## Network Layer (Layer 3)
The Network Layer (Layer 3) provides routing and related functions that enable data to be transported between systems on the same network or on interconnected networks or internetworks. Routing protocols, such as the Routing Information Protocol (RIP), Open Shortest Path First (OSPF), and Border Gateway Protocol (BGP) are defined at this layer. Logical addressing of devices on the network is accomplished at this layer by using routed protocols, including the Internet Protocol (IP) and Internetwork Packet Exchange (IPX).

The Network Layer is primarily responsible for routing.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_69e4bbcb1291e25011dea3f0cb2a5863.png)

### Internet Protocol (IP)

Internet Protocol (IP) contains addressing information that enables packets to be routed. IP is documented in RFC 791 and is part of the TCP/IP protocol suite, which is the language of the Internet. IP has two primary responsibilities:

* Connectionless, best-effort delivery of datagrams
* Fragmentation and reassembly of datagrams

IP Version 4 (IPv4), which is currently the most commonly used, uses a 32-bit logical IP address that’s divided into four 8-bit sections (octets) and consists of two main parts: the network number and the host number.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_c12592411e7c906e4af200cd435df81f.png)

Several IP address ranges are also reserved for use in private networks (for example, 10.x.x.x, 172.16.x.x to 172.31.x.x, and 192.168.x.x). These addresses aren’t routable on the Internet and are thus often implemented on firewalls and gateways by using Network Address Translation (NAT) to conserve IP addresses, mask the network architecture, and enhance security. NAT translates private, non-routable addresses on internal network devices to registered IP addresses when communication across the Internet is required.

IP Version 6 (IPv6) uses a 128-bit logical IP address and incorporates additional functionality to provide security, multimedia support, plug-and-play compatibility, and backward compatibility with IPv4. IPv6 hasn’t yet been widely implemented on the Internet.

The Network layer is also responsible for converting logical addresses into physical addresses.The Address Resolution Protocol (ARP) and Reverse Address Resolution Protocol (RARP) accomplish this.

### Address Resolution Protocol (ARP)

The Address Resolution Protocol (ARP), defined in RFC 826, maps Network Layer IP addresses to MAC addresses. ARP discovers physical addresses of attached devices by broadcasting ARP query messages on the network segment. IP address to MAC address translations are then maintained in a dynamic table that is cached on the system.

### Reverse Address Resolution Protocol (RARP)

The Reverse Address Resolution Protocol (RARP) maps MAC addresses to IP addresses. This is necessary when a system, such as a diskless machine, needs to discover its IP address. The system broadcasts a RARP message providing its MAC address and requests to be informed of its IP address. A RARP server replies with the requested information.

The Network Layer also defines a management protocol for IP known as the Internet Control Message Protocol (ICMP).

### Internet Control Message Protocol (ICMP)

The Internet Control Message Protocol (ICMP) reports errors and other information back to the source regarding the processing of transmitted IP packets. ICMP is documented in RFC 792.

Common ICMP messages include Destination Unreachable, Echo Request and Reply, Redirect, and Time Exceeded. The Packet Internet Groper (PING) is a popular utility that uses ICMP messages to test the reachability of network device.

### Networking equipment at the Network Layer

The primary networking equipment defined at Layer 3 are routers and gateways.

### Routers

Routers are intelligent devices that link dissimilar networks and forward data packets based on logical or physical addresses to the destination network only (or along the network path). Routers consist of both hardware and software components and employ various routing algorithms (for example, RIP, OSPF, and BGP) to determine the best path to a destination based on different variables including bandwidth, cost, delay, and distance.

### Gateways

Gateways are created with software running on a PC (workstation or server) or router. Gateways link dissimilar programs and protocols by examining the entire data packet to translate incompatibilities. For example, a gateway can be used to link an IP network to an IPX network or a Microsoft Exchange mail server to a Lotus Notes server (a mail gateway).

## Transport Layer (Layer 4)
The Transport Layer (Layer 4) provides transparent, reliable data transport and end-to-end transmission control. The Transport Layer hides the details of the lower layer functions from the upper layers.

Specific Transport Layer functions include


* Flow control: Manages data transmission between devices, ensuring that the transmitting device doesn’t send more data than the receiving device can process
* Multiplexing: Enables data from multiple applications to be transmitted over a single physical link
* Virtual circuit management: Establishes, maintains, and terminates virtual circuits
* Error checking and recovery: Implements various mechanisms for detecting transmission errors and taking action to resolve any errors that occur, such as requesting that data be retransmitted

![](https://gitlab.dclabra.fi/wiki/uploads/upload_b834d9f6479bc9e2e7e661ffefed88a5.png)

The Transport Layer is responsible for providing transparent, reliable data transport and end-to-end transmission control. Two important host-to-host protocols defined at the Transport Layer include:


* Transmission Control Protocol (TCP): TCP is a full-duplex, connection-oriented protocol that provides reliable delivery of packets across a network. A connection-oriented protocol requires a direct connection between two communicating devices before any data transfer occurs. In TCP, this is accomplished via a three-way handshake. The receiving device acknowledges packets, and packets are retransmitted if an error occurs. The following characteristics and features are associated with TCP:
    * Connection-oriented: Establishes and manages a direct virtual connection to the remote device.
    * Reliable: Guarantees delivery by acknowledging received packets and requesting retransmission of missing or corrupted packets.
    * Slow: Because of the additional overhead associated with initial handshaking, acknowledging packets, and error correction, TCP is generally slower than other connectionless protocols such as User Datagram Protocol (UDP).
* User Datagram Protocol (UDP): User Datagram Protocol is a connectionless protocol that provides fast best-effort delivery of datagrams across a network. A connectionless protocol doesn’t guarantee delivery of transmitted packets (datagrams) and is thus considered unreliable. It doesn’t attempt to establish a connection with the destination network prior to transmitting data, acknowledge received datagrams, perform resequencing, and perform error checking or recovery. UDP is ideally suited for data requiring fast delivery, which is not sensitive to packet loss and doesn’t need to be fragmented. Examples of applications using UDP include Domain Name System (DNS), Simple Network Management Protocol (SNMP), and streaming audio or video. The following characteristics and features are associated with UDP:
    * Connectionless: Doesn’t preestablish a communication circuit with the destination network.
    * Best effort: Doesn’t guarantee delivery and is thus considered unreliable.
    * Fast: Has no overhead associated with circuit establishment, acknowledgement, sequencing, or error checking and recovery.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_c4957fc0f5bcb70c48972cb750a721a6.png)

Transport Layer security protocols include the following:

* Secure Shell (SSH and SSH-2): SSH provides a secure alternative to Telnet for remote access. SSH establishes an encrypted tunnel between the client and server and can also authenticate the client to the server
* Secure Sockets Layer/Transport Layer Security (SSL/TLS): The SSL protocol, developed by Netscape in 1994, provides session-based encryption and authentication for secure communication between clients and servers on the Internet. SSL provides server authentication with optional client authentication
* Simple Key Management for Internet Protocols (SKIP): SKIP is similar to SSL but doesn’t require prior communication to establish a connection or exchange keys

## Session Layer (Layer 5)
The Session Layer (Layer 5) establishes, coordinates, and terminates communication sessions (service requests and service responses) between networked systems. The Session Layer is responsible for establishing, coordinating, and terminating communication sessions.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_f7cb939ff0402e50aef3f2a5e8c9df6c.png)

A communication session is divided into three distinct phases, as follows:


* Connection establishment: Initial contact between communicating systems is made, and the end devices agree upon communications parameters and protocols to be used, including the mode of operation:
    * Simplex mode: In simplex mode, a one-way communications path is established with a transmitter at one end of the connection and a receiver at the other end. An analogy is an AM radio on which a radio station broadcasts music and the radio receiver can only receive the broadcast
    * Half-duplex mode: In half-duplex mode, both communicating devices are capable of transmitting and receiving but not at the same time. An analogy is a two-way radio in which a button must be pressed to transmit and then released to receive a signal
    * Full-duplex mode: In full-duplex mode, both communicating devices are capable of transmitting and receiving simultaneously. An analogy is a telephone with which you can transmit and receive signals (but not necessarily communicate) at the same time
* Data transfer: Information is exchanged between end devices
* Connection release: After data transfer is completed, end devices systematically end the session

Some examples of Session Layer protocols include:


* Network File System (NFS): Developed by Sun Microsystems to facilitate transparent user access to remote resources on a UNIX-based network by using TCP/IP
* File transfer protocol (FTP): A program used to copy files from one system to another over a network
* Structured Query Language (SQL): Developed by IBM to provide users with a simplified method for defining its data requirements on both local and remote database systems
* Voice over IP (VoIP): VoIP transports various data types (such as voice, telephony, audio, and video) in IP packets providing major cost, interoperability, and performance benefits
* Remote Procedure Call (RPC): A client/server network redirection tool

Procedures are created on clients and performed on servers.

## Presentation Layer (Layer 6)
The Presentation Layer (Layer 6) provides coding and conversion functions that are applied to data being presented to the Application Layer (Layer 7). These functions ensure that data sent from the Application Layer of one system are compatible with the Application Layer of the receiving system.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_a8feb9796850157521228cee66626f24.png)

Tasks associated with this layer include:


* Data representation: Use of common data representation formats (standard image, sound, and video formats) enable application data to be exchanged between different types of computer systems. Some examples include Graphics Interchange Format (GIF), Musical Instrument Data Interface (MIDI), and Motion Picture Experts Group (MPEG)
* Character conversion: Information is exchanged between different systems by using common character conversion schemes, such as Extended Binary-Coded Decimal Interchange Mode (EBCDIC) or American Standard Code for Information Interchange (ASCII)
* Data compression: Common data compression schemes enable compressed data to be properly decompressed at the destination
* Data encryption: Common data encryption schemes enable encrypted data to be properly decrypted at the destination

## Application Layer (Layer 7)
The application layer is the OSI layer closest to the end user, which means both the OSI application layer and the user interact directly with the software application. This layer interacts with software applications that implement a communicating component. Such application programs fall outside the scope of the OSI model. Application-layer functions typically include identifying communication partners, determining resource availability, and synchronizing communication. When identifying communication partners, the application layer determines the identity and availability of communication partners for an application with data to transmit. When determining resource availability, the application layer must decide whether sufficient network resources for the requested communication exist. In synchronizing communication, all communication between applications requires cooperation that is managed by the application layer. This layer supports application and end-user processes. Communication partners are identified, quality of service is identified, user authentication and privacy are considered, and any constraints on data syntax are identified. Everything at this layer is application-specific.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_42e314c57486d2139d76c15168c39d9b.png)

The Application Layer is responsible for the following:


* Identifying and establishing availability of communication partners
* Determining resource availability
* Synchronizing communication

The Application Layer is responsible for identifying and establishing availability of communication partners, determining resource availability, and synchronizing communication.

Don’t confuse the Application Layer with software applications such as Microsoft Word or WordPerfect. Applications that function at the Application Layer include operating systems (such as Windows and NetWare), OSI applications, such as File Transfer, Access, and Management (FTAM) and Virtual Terminal Protocol (VTP), and TCP/IP applications, including:


* HyperText Transfer Protocol (HTTP): The language of the World Wide Web (WWW). Attacks typically exploit vulnerabilities in Web browsers or programming languages such as CGI, Java, and ActiveX. HTTP operates on TCP port 80
* Trivial File Transfer Protocol (TFTP): A lean, mean version of FTP without directory browsing capabilities or user authentication. Generally considered less secure than FTP, TFTP operates on UDP port 69
* Simple Mail Transfer Protocol (SMTP): Used to send and receive e-mail across the Internet. This protocol has several well-known vulnerabilities that make it inherently insecure. SMTP operates on TCP/UDP port 25
* Simple Network Management Protocol (SNMP): Used to collect network information by polling stations and sending traps (or alerts) to a management station. SNMP has many well-known vulnerabilities, including default clear-text community strings (passwords). SNMP operates on TCP/UDP port 161
* Telnet: Provides terminal emulation for remote access to system resources. Passwords are sent in clear text. Telnet operates on TCP/UDP port 23

Application Layer security protocols include the following:


* Secure Multipurpose Internet Mail Extensions (S/MIME): S/MIME is a secure method of sending e-mail incorporated into several popular browsers and e-mail applications.
* Privacy Enhanced Mail (PEM): PEM is a proposed IETF (Internet Engineering Task Force) standard for providing e-mail confidentiality and authentication.
* Secure Electronic Transaction (SET): The SET specification was developed by MasterCard and Visa to provide secure e-commerce transactions by implementing authentication mechanisms while protecting the confidentiality and integrity of cardholder data.
* Secure HyperText Transfer Protocol (S-HTTP): S-HTTP is an Internet protocol that provides a method for secure communications with a Web server. S-HTTP is a connectionless-oriented protocol that encapsulates data after security properties for the session have been successfully negotiated.
* Secure Remote Procedure Call (S-RPC): S-RPC is a secure client-server protocol that’s defined at the upper layers of the OSI model, including the Application Layer. RPC is used to request services from another computer on the network. S-RPC provides public and private keys to clients and servers by using Diffie-Hellman. After initially authenticating, S-RPC operations are transparent to the end user.

## The TCP/IP Model
The TCP/IP model separates the networking functions into distinct layers & each layer performs a specific function. Network-model is used to conceptualize how networks should work, so that the hardware & network-protocols can interoperate. It is the closest model of Internet, which uses TCP/IP.

The Transmission Control Protocol/Internet Protocol (TCP/IP) Model is similar to the OSI Reference Model. However, the big difference is that it consists of only four layers rather than seven.

![](https://gitlab.dclabra.fi/wiki/uploads/upload_7d0090c62052cf6082393fa5cbf2698a.png)

* Application Layer: Consists of network applications and processes and loosely corresponds to the upper layers of the OSI model (Application, Presentation, and Session Layers)
* Host-to-Host Transport Layer: Provides end-to-end delivery and corresponds to the OSI Transport Layer
* Internet Layer: Defines the IP datagram and routing and corresponds to the OSI Network Layer
* Network Access (or Link) Layer: Contains routines for accessing physical networks and corresponds to the OSI Data Link and Physical Layers

## TCP/IP protocols and port numbers
TCP/IP protocols are like protocols in real life.For example:

* a phone call starts with saying "hello" - SMTP protocol EHLO or HELO
* HTTP and HTTPS are most commonly used protocols

![](https://gitlab.dclabra.fi/wiki/uploads/upload_896637edfe480ced2cf2ce39206477b7.png)

## TCP/IP Routing Protocols
Routing protocols are defined at the network level and specify how routers communicate with one another or a WAN. Routing prototocols are router-to-router communication protocols used by routers to help determine the most efficient network routes between nodes on a network. Routing protocols are classified as static or dynamic.


* A static routing protocol requieres an administrator to create and update routes manually on the router
* A dynamic routing protocol can discover routes and determine the best route to a given destination at any given time

Metrics are used to determine the “best” route across a network. The simplest metric is hop count.

Distance vector routing protocols use simple metrics such as hop count, and are prone to routing loops, where packets loop between two routers.

Some examples of routing protocols are listed below:

* RIP (Routing Information Protocol) - one of the early routing protocols
    * Hop count is the metric, maximum = 15
* IGRP (Interior Gateway Routing Protocols) - Cisco proprietary, obsolete
    * Multiple metrics: bandwidth, delay, load and reliability
* EIGRP (Enhanced Interior Gateway Routing Protocol) - Cisco proprietary
    * Advance over IGRP including VLSM (Variable Length Subnet Mask)
* OSPF (Open Shortest Path First) - Open standard for enterprise networks
    * Metric is "path cost" (primarily used)
    * Can use authentication to prevent route spoofing
* BGP (Border Gateway Protocol) - the dominant Internet routing algorithm
* IS-IS (Intermediate system to intermediate system) - used primarily by large ISP networks

