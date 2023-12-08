# How is TCP/IP different from OSI?

>[!IMPORTANT]
> - TCP/IP is older than the OSI Model
> - a Key difference between the models is that TCP/IP is simpler, collapsing several layers OSI layers into one
> - Session, presentation, and application layers of the OSI model are combined into one Application Layer of TCP/IP
> - Physical and data link layers of the OSI model are combined into Network Access Layer of TCP/IP 


| OSI Model Layers | TCP/IP Layers |
|:-----:|:-----:|
| Application | Application |
| Presentation | Application |
| Session | Application |
|         |             |
| Transport | Transport |
| Network | Network |
|         |         |
| Data Link | Network Access |
| Physical | Network Access |


<br></br>
<br></br>


## TCP/IP also known as Internet Protocol Suite


* Application layer 
    * Provides network services to end-users or applications
    * Supports communication between software applications
    * Defines the protocols used by specific applications and services
    * Examples of protocols:

        * HTTP (Hypertext Transfer Protocol), 
        * FTP ( File Transfer Protocol), 
        * SMTP (Simple Mail Transfer Protocol), 
        * DNS (Domain Name System)
        * SSH (Secure Shell)

* Transport layer 
    * Ensures reliable end-to-end communication between devices 
    * Manages flow control, error detection, and correction
    * Responsible for segmentation and reassembly of data
    * Example of protocols:

        * TCP (Transmission Control Protocol), 
        * UDP (User Datagram Protocol)

* Network or Internet layer 
    * Handles the routing of data packets between networks
    * Provides logical addresses using IP addresses
    * Responsible for fragmentation and reassembly of data packets
    * Examples of protocol:

        * IP (Internet Protocol), 
        * ICMP (Internet Control Message Protocol),  
        * IGMP (Internet Group Message Protocol), 
        * ARP (Address Resolution Protocol)

* Network Access or Link layer
    * Responsible for the physical connection between devices on the same local network
    * Manages the transmission of data frames over the local network
    * Addresses devices using MAC (Media Access Control) addresses
    * Examples of protocols:
  
      * Ethernet
      * Wi-Fi
      * PPP (Point-to-Point Protocol)

<br></br>
<br></br>


#### Summary






