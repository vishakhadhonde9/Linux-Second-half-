# Networking in linux-
# Network-
- Network is system that connrcts two or more computing devices and establish connection between them.
- Networks allow devices to communicate with each other, whether they are in close proximity or across the globe, using various technologies and protocols.

# Protocol- 
- The protocol specifies the rules and format that used for communication.
- Common protocols include TCP (Transmission Control Protocol) and UDP (User Datagram Protocol).
- TCP is connection-oriented and ensures reliable data delivery through mechanisms like acknowledgment and retransmission.
- On the other hand, UDP is connectionless and does not guarantee delivery but is faster and more lightweight.
- The protocol determines how data is formatted, transmitted, and received between devices.

# IP address-
- An IP (Internet Protocol) address is a numerical label assigned to each device connected to a computer network.
- IP addresses are used to identify and locate devices within a network.
- IPv4 addresses are typically written as four decimal numbers separated by dots (e.g., 192.168.1.1), while IPv6 addresses are written in hexadecimal format with colons separating each group (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).

# Port Number-
- A port number is the logical address of each application or process that uses a network or the Internet to communicate.
-  A port number uniquely identifies a network-based application on a computer.
* Examples-
    - SSH: 22
    - HTTP: 80
    - HTTPS: 443
    - MySQL: 3306

# Networking Utilities-

# ifconfig: 
- Used to configure network interfaces, display their configuration.
- It display ip address and mac address of system.

# ip:
- Provides more advanced network configuration options than ifconfig, including routing, addressing.
- ip addr
  - This command displays information about all network interfaces on your system, including their IP addresses, MAC addresses, and other configuration details.
- ip link
  - Displays information about network interfaces (links), such as their state (UP or DOWN), MTU (Maximum Transmission Unit), and Ethernet address (MAC address).

# ping: 
- Test connectivity.
- Verify that a specific host is reachable over the network.
- Diagnose network connectivity issues, such as packet loss or high latency.
- ping <host>

# traceroute / tracepath: 
- Traces the route taken by packets from the source to the destination, showing intermediate hops and round-trip times.
- traceroute [destination]
  
# netstat-
- Displays various network-related information, such as active network connections, routing tables, interface statistics, and more.
### Options:
- -u: instructs netstat to display UDP (User Datagram Protocol) connections. UDP is a connectionless protocol used for sending data in a network.
- -t: netstat to display TCP (Transmission Control Protocol) connections. TCP is a connection-oriented protocol used for reliable communication over a network.
# wget / curl:
- Command-line tools for downloading files from the internet using HTTP, HTTPS, FTP, and other protocols.


# OSI Model-
![image](https://github.com/user-attachments/assets/a3feeb5e-4029-4b3f-b8f5-365132c4c68a)


- The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network.
- It breaks down the process of network communication into seven distinct layers, each with specific functions.

### 1] Physical Layer-
- The physical layer is responsible for the physical cable or wireless connection between network nodes.
- It defines the connector, the electrical cable or wireless technology connecting the devices, and is responsible for transmission of the raw data, which is simply a series of 0s and 1s, while taking care of bit rate control.

### 2] Data Link Layer-
- The data link layer establishes and terminates a connection between two physically-connected nodes on a network.
- It breaks up packets into frames and sends them from source to destination.

### 3] 3. Network Layer-
- The network layer has two main functions. One is forwarding (divide large data in small, manageable packet) and addressing packets, and reassembling the packets on the receiving end.
- The other is routing packets by discovering the best path across a physical network. The network layer uses network addresses to route packets to a destination node.

### 4] Transport Layer-
- The transport layer takes data transferred in the session layer and breaks it into “segments” on the transmitting end.
- It is responsible for reassembling the segments on the receiving end, turning it back into data that can be used by the session layer.
- The transport layer carries out flow control, sending data at a rate that matches the connection speed of the receiving device, and error control, checking if data was received incorrectly and if not, requesting it again.

# 5] Session Layer-
- The session layer creates communication channels, called sessions, between devices.
- It is responsible for opening sessions, ensuring they remain open and functional while data is being transferred, and closing them when communication ends.
- The session layer can also set checkpoints during a data transfer if the session is interrupted, devices can resume data transfer from the last checkpoint.

# 6] Presentation Layer-
- The presentation layer prepares data for the application layer.
- It defines how two devices should encode, encrypt, and compress data so it is received correctly on the other end.
- The presentation layer takes any data transmitted by the application layer and prepares it for transmission over the session layer.

# 7] Application Layer

The application layer is used by end-user software such as web browsers and email clients. It provides protocols that allow software to send and receive information and present meaningful data to users. A few examples of application layer protocols are the Hypertext Transfer Protocol (HTTP), File Transfer Protocol (FTP), Post Office Protocol (POP), Simple Mail Transfer Protocol (SMTP), and Domain Name System (DNS).


![image](https://github.com/user-attachments/assets/01bd19dc-51a4-42a5-8626-d7ed323755ec)


# TCP-IP Model-
- The TCP/IP model defines how devices should transmit data between them and enables communication over networks and large distances.
- The TCP/IP model consists of five layers: the application layer, transport layer, network layer, data link layer and physical layer.

![image](https://github.com/user-attachments/assets/d37bf78f-702a-4aaf-8532-fc1b83f4e5ed)


