# Subnetting-
- Subnetting is the process of dividing a larger network into smaller subnetworks (subnets) to improve efficiency and security.
- Smaller subnets reduce network congestion and improve performance by limiting broadcast traffic.

# Classful Addressing-
- Classful addressing divides IP addresses into different classes, each with a specific range of addresses and default subnet masks.
- It helps in managing IP addresses and routing them efficiently, but it’s less flexible than modern methods like CIDR (Classless Inter-Domain Routing).
- The 32-bit IP address is divided into five sub-classes. These are given below:
  - Class A
  - Class B
  - Class C
  - Class D
  - Class E

![image](https://github.com/user-attachments/assets/6a264f30-0112-4408-9a23-2deba89d9abf)

## Class A-
- IP addresses belonging to class A are assigned to the networks that contain a large number of hosts. 
  - The network ID is 8 bits long.
  - The host ID is 24 bits long.
 ![image](https://github.com/user-attachments/assets/5ba3d117-54dc-44a2-82d2-368975f44fec)

# Class B-
- IP address belonging to class B is assigned to networks that range from medium-sized to large-sized networks. 
  - The network ID is 14 bits long.
  - The host ID is 16 bits long.
![image](https://github.com/user-attachments/assets/a2b542d1-0b27-4439-9ff6-44886a338842)

# Class C-
- IP addresses belonging to class C are assigned to small-sized networks.
  - The network ID is 24 bits long.
  - The host ID is 8 bits long.
![image](https://github.com/user-attachments/assets/e8949a34-4657-473f-b2eb-dc5184a380c7)

# Class D-
- IP address belonging to class D is reserved for multi-casting.
- The higher-order bits of the first octet of IP addresses belonging to class D is always set to 1110.
- The remaining bits are for the address that interested hosts recognize.

  ![image](https://github.com/user-attachments/assets/d8fb1f30-6c5a-4b26-9b29-e279a6b9015f)

# Class E-
- IP addresses belonging to class E are reserved for experimental and research purposes.
- IP addresses of class E range from 240.0.0.0 – 255.255.255.255.
- This class doesn’t have any subnet mask.
- The higher-order bits of the first octet of class E are always set to 1111.

![image](https://github.com/user-attachments/assets/92eb0433-f635-4951-bba0-f39f46193b24)
![image](https://github.com/user-attachments/assets/09ceffbc-32eb-4dc7-a70d-30dd3d4e9afb)


# Range of Private ip addresses-
- Class A: 10.0.0.0–10.255.255.255
- Class B: 172.16.0.0–172.31.255.255
- Class C: 192.168.0.0–192.168.255.255


# CIDR-
- CIDR stands for Classless Inter-Domain Routing.
- It is a method for allocating IP addresses.
# IP Address Structure: 
### IP addresses are typically divided into two parts:
- the network portion
-  the host portion.
# Subnet Mask: 
- The subnet mask is used to determine which part of an IP address is the network portion and which part is the host portion.
- a.b.c.d/n, n represent network part or fixed bits.
- For example, in the IP address 192.168.1.0/24, /24 denotes that the first 24 bits represent the network part and the remaining 8 bits represent the host part.
- Subnet mask of 255.255.255.0 in decimal translates to 11111111.11111111.11111111.00000000 in binary, indicating that the first 24 bits are network bits and the last 8 bits are host bits.
