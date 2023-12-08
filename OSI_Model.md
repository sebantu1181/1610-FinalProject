# What is The OSI Model 
Open System Interconnection Model known as OSI Model is a major protocol model that describes various forms of network system or communication.
The OSI model consists of seven layers that display how data is sent and received across a network. 
The primary goal is to demonstrate how the various layers of communications are layered over one another, starting with physical cabling and concluding with the application that interacts with users or other devices on a network. 





## The 7 Layers of OSI Model: 



<br></br>
<br></br>



### Layer 7: Application Layer
Responsible for user interface


<br></br>
<br></br>



### Layer 6: Presentation Layer
Responsible for the receiver understands sent data 


<br></br>
<br></br>



### Layer 5: Session Layer
Responsible for stabilizes connections


<br></br>
<br></br>



### Layer 4: Transport Layer
The Transport Layer is the fourth layer of the OSI model, its essential for assuring end-to-end communication by providing reliable and efficient data transfer services between devices. 
It manages flow control, error detection and correction, and data segmentation, all of which contribute to a more reliable and streamlined communication process.


#### Responsibilities of the Transport Layer
 > **Data or Packet Segmentation**: Process of breaking down data packets into smaller segments or units for transmission and reassembles them at the destination. The segmentation allows for more effecient data transfer.

 > **Flow Control**: Flow control methods manage the rate at which data is transmitted between devices in order to avoid congestion and ensure that the receiving device can process the information without being overloaded.

 > **Error Detection and Correction**: Applies error detection techniques to detect data corruption or loss during transmission. Furthermore, it may use error correction methods to recover from errors without retransmitting the complete message.

**Reliable Data Transfer**: Ensures that data is delivered accurately and in the correct order. It manages acknowledgment and retransmission processes to guarantee reliable communication.

**Multiplexing and Demultiplexing**: Multiplexing allows numerous communication streams to be handled at the same time. Each communication stream is assigned a unique identification by the Transport Layer, and demultiplexing at the receiving end ensures that data reaches the relevant application.

#### Transport Layer Key Protocols
 > *Transmission Control Protocol(TCP)*

 > *User Datagram Proticil(UDP)*

 > *Stream Control Transmission Protocol(SCTP)*

#### Summary
The Transport Layer is essential for creating applications and protocols that demand rapid and reliable information delivery. When creating communication systems, network application developers must consider the properties of protocols such as TCP and UDP. 


<br></br>
<br></br>




### Layer 3: Network Layer
The Network Layer is the third layer of the OSI model, it is in charge of logical addressing, routing, and data forwarding between devices across many networks. 
Its fundamental purpose is to enable end-to-end communication and to make data packet travel between source and destination devices efficiently.

#### Key Functions of Network Layer
**Logical Addressing**: 
 - The Network Layer assigns logical addresses, such as IP (Internet Protocol) addresses, to devices in a network.
 - These addresses are used for uniquely identifying devices and routing data to the correct destination.

**Routing**:
 - Routing involves determining the best path for data to travel from the source to the destination across multiple interconnected networks.
 - Routers, operating at this layer, make decisions based on logical addressing and network topology.

**Packet Forwarding**:
 - Once the routing decision is made, the Network Layer forwards data packets from one device to another.
 - This involves encapsulating data into packets, attaching the destination logical address, and transmitting them across the network.

| Network Layer Associated Protocols |
|:----------------------------------:|
| Internet Protocol(IP) |
| Internet Control Message Protocol(ICMP) |
| Internet Group Management Protocol(IGMP)|
| and more. |



OSI model is known for defining how different applications communicate over connected networks
* Including: 
  * LAN (Local Area Network)
    > A local area network (LAN) connects multiple or a group of network-connected devices with a limited range or localized region, such as a coffee shop, library, or school.
    > This network is mostly used for sharing hardware resources such as computers, printers, televisions, and other devices. In comparison to MAN and WAN, LAN has a greater data transmission speed and implements private network addresses for connectivity and data exchange. It also uses cable for network connection, which reduces mistake and maintains data security.
  * MAN (Metropolitan Area Network)
    > A metropolitan area network connects small areas or regions like cities or towns. This network is larger than a LAN but not as large as a WAN. 
    > MAN can be used to connect numerous LAN networks to form a metropolitan range; for example, a MAN network can connect all of a company's branches in the same city. 
    > The networked region is typically connected by wired networks, such as optical cables and connections.
  * WAN (Wide Area Network)
    > A WAN connects devices across extensive areas such as a state, country, or continent. The WAN network is larger than the LAN and MAN networks, its connection is usually wireless since it uses radio towers for communication, and the geographical area is usually made up of multiple interconnected LAN and MAN networks. 
    > Because of the large distance covered, the speed of WAN data transfer is slower than that of LAN and MAN.
  * etc.

#### Summary
The Network Layer is crucial to the overall operation of the internet and other advanced networks. 
Its capacity to route and forward data between networks guarantees that communication is smooth across diverse environments. 
Understanding the fundamentals of logical addressing, routing, and packet forwarding at this layer is critical.


<br></br>
<br></br>




### Layer 2: Data Link Layer
The second layer in the OSI model is called the Data Link Layer, and it operates as a link between the Physical Layer and the upper layers. 
Its main objective is to ensure that data is reliably and error-free transmitted between two physically-connected nodes on a network.

#### This layer is composed of two parts:
Logical Link Control(LLC):
 * Identifies network protocols
 * Performs error checking
 * Synchronizes frames
Media Access Control(MCC)
 * Uses MAC addressses to connect devices
 * Defines premissions to transmit and receive data


#### Functions of the Data Link Layer

Framing: 
 - The data link layer encapsulates the data obtained from the network layer and converts it into manageable transmission units called frames.
 - These frames contain control information, addressing details, and the actual data payload.

Addressing(MAC addressing):
 - Each device on a network has a unique Media Access Control(MAC) address assigned by the manufacturer.
 - These addresses are used by the Data Link Layer to identify nodes and deliver frames within the same local network.

Error Detection and Correction:
 - Executes error detection procedures, allowing the detection of corrupted frames.
 - While basic error detection is performed, retransmission is often utilized for correction.

Flow Control:
 - Manages data flow between sender and receiver to avoid overloading the receiving device.
 - Flow control mechanisms ensure that data is transferred in an efficient and controlled manner.

Access Control:
 - The Data Link Layer manages channel access and avoids collisions in shared communication channels by using access control methods such as Carrier Sense Multiple Access with Collision Detection (CSMA/CD).


#### Summary
In essence, nderstanding the Data Link Layer reveals how devices within the same local network communicate with one another, ensuring the reliable and efficient exchange of data between directly connected nodes.



<br></br>
<br></br>




### Layer 1: Physical Layer
The physical layer is the first and lowest level of the OSI model, and it deals with the physical connection between devices. It defines hardware components such as cables, wires, connectors, and so on. 
The information is stored in bits (1s and 0s) and is transferred between devices via the node, which is a physical electronic device that is connected to a network.


#### Functions of the Physical Layer

The physical layer is in charge of transferring computer bits from one device to another across the network. 
Its functions involves deciding how physical connections to the network are established, along with how bits are transformed into signals that are transmitted either electrically, optically, or via radio signals.

* Bits: 
  * Data is transmitted in the form of raw bits (0s, and 1s)
  * It defines how these are encoded, transmitted, and received over physical hardware
* Signal:
  * Physical layer manages signals that represent the bits.
  * These can be electrical voltages, light pulses, or radio signals
  * The modulation technique is used to encode bits into signals
* Transmission modes: Defines
  how data is transmitted between devices. Common modes include:
  * simplex: one-way communication
  * Half-duplex: two-way communication, but not simultaneous
  * Full-duplex: two-way and simultaneous communication  
and more (Data synthronization, interface, configuration, modulation, switching mechanism)


#### Physical Topology

Physical layer deals with physical arragement of devices in a network, known as network topology. 
common topogies include:
 * Bus topology
 * Mesh topology
 * Star topology
 * Ring topology

#### Summary
The Physical layer outlines the framework for network connection by handling the physical aspects of data transmission, from translating digital signals to controlling the actual transfer across the specified hardware.



