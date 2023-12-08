# What is The OSI Model 
> [!IMPORTANT]
> Open System Interconnection Model known as OSI Model is a major protocol model that describes various forms of network system or communication.
The OSI model consists of seven layers that display how data is sent and received across a network. 
The primary goal is to demonstrate how the various layers of communications are layered over one another, starting with physical cabling and concluding with the application that interacts with users or other devices on a network. 


<br></br>
<br></br>


## The 7 Layers of OSI Model: 
> [!TIP]
> Application Layer
> Presentation Layer
> Session Layer
> Transport Layer
> Network Layer
> Data Link  Layer
> Physical Layer  

<br></br>



### Layer 7: Application Layer
The Application or Interface Layer is the seventh and highest layer of the OSI model, it is the interface between the network and the software application running on a device. It provides network services directly to end users and serves as the entry point for network programs.



#### Application layer Functionality
User Interface: 
   - The Application Layer provides a user interface through which the user and the application can communicate.
   - It can include graphical interfaces, command-line interfaces, or any other type of user interface.

Network Services: 
   - It provides applications with network services such as email, file transfer, and network browsing.
   - These services facilitate communication and data sharing between network devices. 

Communication Protocols: 
   - The Application Layer facilitates communication between programs by utilizing various communication protocols.
   - Examples include HTTP for web browsing, SMTP for email, and FTP for file transfer.

Data Exchange and Encryption: 
   - This layer facilitates exchange of information between apps.
   - It can also manage data encryption and decryption, ensuring safe connection.

Network Virtual Terminal: 
   - The Application Layer provides a network virtual terminal, which allows devices to log into other devices on the network and remotely execute commands.


<details>
   <summary>Application Layer protocols</summary>

| Protocols |
|:---------------- |
| HTTP/HTTPS(Hypertext Transfer Protocol/Secure) |
| SMTP(Simple Mail Transfer Protocol) |
| POP3(Post Office Protocol) |
| IMAP(Internet Message Access Protocol) |
| FTP(File Transfer Protocol) |
| DNS(Domain Name System) |

</details>


#### Summary
The Application Layer serves as the interface between users and the network. It ensures application communication across the network, provides a consistent interface, and supports a wide range of network services. It is critical in making many different apps accessible and useable in a networked setting.


<br></br>
<br></br>



### Layer 6: Presentation Layer
The Presentation Layer is the sixth layer of the OSI structures, focuses on the logic and syntax of data transmitted between computers. It is in charge of translating, encrypting, or compressing data so that programs on various devices may comprehend each other's formats. 

#### Importance of Presentation Layer
> **Translation**:
   > The Presentation Layer interprets data between the application layer and the lower layers, ensuring that the recipient understands the sender's format. This translation may include character set conversions to ensure compatibility with various framing systems.

> **Encryption and Decryption**:
   > Data transmission security is extremely important. Hence, The Presentation Layer encrypts data before transmission and decrypt it at the receiving end.
   > This helps in protecting sensitive information from unauthorized access during communication. 

> **Compression**:
   > The Presentation Layer can compress data before transmission and decompress it upon reception to optimize bandwidth utilization.
   > This minimizes the amount of data sent across the network, improving overall efficiency. 

> **Format Syntax**:
   > The layer is concerned with data syntax, such as how integers, floating-point numbers, and strings are represented.
   >  It ensures that application layer data is delivered in a consistent and intelligible manner.

> **Data Structure**:
   > Different data structures may be used by different systems.
   > The Presentation Layer unifies various structures, allowing data to be rendered consistently throughout the network.



#### Protocols and Formats
- JPEG, GIF, and MPEG:
   - The Presentation Layer is in charge of image and video compression standards.
   - For efficient presentation of multimedia data, formats such as
      - JPEG (Joint Photographic Experts Group),
      - GIF (Graphics Interchange Format), and
      - MPEG (Moving Picture Experts Group) are utilized.

- SSL/TLS (Secure Sockets Layer/Transport Layer Security):
   - SSL/TLS protocols are widely used for encryption and decryption procedures; they are critical for preserving data during transmission and for secure internet communication.


#### Summary
The Presentation Layer guarantees that data is displayed in a format that is globally accessible, allowing for seamless communication between various systems. It is critical in data translation, encryption, and compression, hence enhancing the interoperability and security of networked applications.



<br></br>
<br></br>






### Layer 5: Session Layer
The Session Layer is the fifth layer of the OSI model, it is in charge of establishing, managing, and terminating sessions or connections between applications. It guarantees that data interchange between programs is fluid, with features that help in coordination and synchronization.

#### Session Layer Major Functions 
**Dialog Control**: 
   - The Session Layer handles the communication or dialog between two devices, ensuring that data is transmitted in an orderly and structured manner.
   - It specifies how long each device can communicate before handing over control.

**Session Establishment, Maintenance, and Termination**: 
   - This layer creates sessions, keeps them active during data exchange, and terminates them when the connection is finished.
   - It facilitates in the coordination of the start and end of communication between applications.

**Synchromization**: 
   - Data synchronization entails keeping data consistent during communication.
   - The Session Layer ensures that the sender and recipient remain in sync, preventing issues such as data duplication or out-of-order transmission.

**Checkpointing**:
   - Checkpointing allows the Session Layer to save the current state of a session on a regular basis.
   - In the event of a failure, the session can be recovered from the most recent checkpoint, minimizing data loss and preserving continuation.

**Token Management**: 
   - The Session Layer controls token-based communication, providing fair access and avoiding conflicts; it prevents two users from accessing or attempting the same critical operation at the same time.


#### Protocols Related to Session Layer
 > *Remote Procedure Call(RPC)*

 > *NetBIOS(Network Basic Input/Output System)*


#### Summary
The Session Layer's role in maintaining sessions and ensuring coordinated communication between applications is critical for many networks. It allows for the orderly and controlled flow of data, improving the reliability and efficiency of communication in connected situations.



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

1. Framing: 
   - The data link layer encapsulates the data obtained from the network layer and converts it into manageable transmission units called frames.
   - These frames contain control information, addressing details, and the actual data payload.

2. Addressing(MAC addressing):
   - Each device on a network has a unique Media Access Control(MAC) address assigned by the manufacturer.
   - These addresses are used by the Data Link Layer to identify nodes and deliver frames within the same local network.

3. Error Detection and Correction:
   - Executes error detection procedures, allowing the detection of corrupted frames.
   - While basic error detection is performed, retransmission is often utilized for correction.

4. Flow Control:
   - Manages data flow between sender and receiver to avoid overloading the receiving device.
   - Flow control mechanisms ensure that data is transferred in an efficient and controlled manner.

5. Access Control:
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



