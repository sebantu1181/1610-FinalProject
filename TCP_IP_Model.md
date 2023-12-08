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


* **Application layer** 
    * Provides network services to end-users or applications
    * Supports communication between software applications
    * Defines the protocols used by specific applications and services

   <details>
   <summary>Examples of protocols:</summary>

        HTTP (Hypertext Transfer Protocol) 
        FTP ( File Transfer Protocol) 
        SMTP (Simple Mail Transfer Protocol) 
        DNS (Domain Name System)
        SSH (Secure Shell)

   <details>

<br></br>


* **Transport layer** 
    * Ensures reliable end-to-end communication between devices 
    * Manages flow control, error detection, and correction
    * Responsible for segmentation and reassembly of data

   <details>
   <summary>Example of protocols:</summary>

        TCP (Transmission Control Protocol) 
        UDP (User Datagram Protocol)
  
     </details>

* **Network or Internet layer**
    * Handles the routing of data packets between networks
    * Provides logical addresses using IP addresses
    * Responsible for fragmentation and reassembly of data packets
 
   <details>
   <summary>Examples of protocol:</summary>

        IP (Internet Protocol) 
        ICMP (Internet Control Message Protocol)  
        IGMP (Internet Group Message Protocol) 
        ARP (Address Resolution Protocol)
  
</details>


<br></br>



* **Network Access or Link layer**
    * Responsible for the physical connection between devices on the same local network
    * Manages the transmission of data frames over the local network
    * Addresses devices using MAC (Media Access Control) addresses
 
   <details>
   <summary>Examples of protocols:</summary>
  
      Ethernet
      Wi-Fi
      PPP (Point-to-Point Protocol)

   </details>

<br></br>
<br></br>


#### Summary
The TCP/IP paradigm consists of four layers: the Network Access Layer for local network connections, the Network Layer for logical addressing and routing, the Transport Layer for end-to-end communication, and the Application Layer for user applications and services. These layers collaborate to allow for successful communication in computer networks.



[Next: OSI Model](OSI_Model.md)

