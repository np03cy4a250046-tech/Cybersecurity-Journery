# IP ADDRESS
- An IP address is an unique numeric label assigned to every devices that are connected to the network for communicating and sharing the data.
- it is used to identify the devices that are connected to the Network
-  there are various  types of ip address they are IPv4(old version) IPv6(New version), static vs dynamic, Public vs Private IP  
- # DETAIL PROCESS OF HOW IP ADDRESS WORK
- As we all know we have router in our home it has it own public ip address and private ip address public ip address is determined by the ISP(INTERNET SERVICE PROVIDER) where as the private IP is determined by the router's manufacture the public ip is what it uses to communicate with the WAN(network) let's suppose u connect ur Laptop to the WLAN(Ur router) the router decides your Private IP using DHCP(Dynamic Host Configuration Protocol) so that it can be used for communication and when u request for the website for example youtube.com the request goes from your laptop's private IP to Router's Private IP after that it performs NAT(Network address translation) to translate your phone's private IP to network's public IP and then it requests for the youtube.com to WAN and from there it receives the answer and it goes back to router, router's private Ip and then your laptops private IP so finally ur laptop receives the request

# IPv4 vs IPv6
- IPv4 uses 32-bit addresses written in dotted-decimal format(eg:192.186.1.1) Whereas IPv6 uses  128-bit addresses written in hexadecimal colon notation(eg:2001:0db8::1)

- IPv4 provides about 4.3 billion unique addresses, which have already run out globally whereas  IPv6 Provides 340 undecillion (3.4 × 10³⁸) addresses, making exhaustion practically impossible

- IPv4 Relies heavily on NAT to let multiple private devices share a single public IP address due to shortages whereas, IPv6 Eliminates the need for NAT, allowing end-to-end direct connectivity
  
- therefore we can confirm that IPv6 is more reliable than IPv4 in today's world

# Static vs Dynamic IP
- static IP is a type of ip address where the IP address stays the same permanently unless updated manually whereas , Dyanamic IP address is a type of IP address where the IP address changes automatcially overtime (usually done by DHCP)

-  Dynamic IPs offer better privacy and security because your address shifts frequently, making it harder for hackers or trackers to follow you. Static IPs are easier to track

  # Private vs Public IP
  - A public IP address is a globally unique identifier assigned by your Internet Service Provider to connect your network , while a private IP address is an internal identifier used by your router to recognize individual devices within your local network
  - 10.0.0.0-10.255.255.255
  - 172.16.0.0-172.31.0.0
  - 192.168.0.0-192.168.255.255
    

# Classes of IP address
- IP address is divided into 5 classes it was an early method (1981–1993) used to assign IP addresses and divide the IPv4 address space into fixed classes. Each      IP address was categorised based on its leading bits, and the class determined its network and host portions.

- IP addresses are divided into 5 classes A,B,C,D,E
- The class of an IP address was identified by its first few bits
- Classes A, B, and C were used for unicast communication, supporting large, medium, and small networks, respectively
- Class D was reserved for multicast communication
- Class E was intended for experimental and research purposes
 
- Class A IP address is used whenever there are large number of host connected to the network because it only has 8 bit network address and 24 bit Host address. A   Class A IPv4 address has 8 network prefix bits. For example, consider 44.0.0.1, where 44 is the network address, and 0.0.1 is the host address.

 -Class B IP address is used for medium sized to large size of organization as it has 16 network prefix bits and 16 bit of host address. A Class B IPv4 address       has 16 network prefix bits. For example, consider 128.16.0.2, where 128.16 is the network address, and 0.2 is the host address.
 
 -Class C IP address is used for small to medium size organization as it has 24 network prefix bits 8 bit of host a address. A Class C IPv4 address has 24 network   prefix bits. For instance, consider 192.168.1.100, where 192.168.1 is the network address, and 100 is the host address.  
  

# Relation between IPv4 address and subnet mask 
- suppose your IP address is 192.168.1.34 and ur subnet mask is 255.255.255.0. We can see the corelation 192->255 168->255 1->255 34->0 so the octets that corelates to 255 stays the same forever but the octets the corelates to 0 change(between 0-255).
- the the portion of IP address that doesn't change is called Network portion and the IP address that changes is called Host portion.
  
-An IP address has two parts:

-The network address is a series of numerical digits pointing to the network's unique identifier 

-The host address is a series of numbers indicating the host or individual device identifier on the network

-only 253 ip addresses are usable for network instead of 256 (0-255) as 192.168.1.0 and 192.168.1.255 (first octet is the network itself and last octet is broadcast network to all devices.) and last one is reserved for router.

# CIDR
- CIDR(CLASSLESS INTER DOMAIN ROUTING) is a method of IP address allocation and routing that allows more efficient use of IP address unlike traditional class based routing system.

# What are the benefits of CIDR over Classing IP address
- Reduce IP wastage
- Simplify routing and network security

# Identify different special IP address
-address or range	Type     / purpose
-127.0.0.1	              Loopback — your own computer
-0.0.0.0	                Unspecified address; meaning depends on context
-169.254.x.x	            Link-local — often assigned when DHCP fails
-255.255.255.255	                   Limited broadcast
-224.0.0.0 – 239.255.255.255	         Multicast
-100.64.0.0 – 100.127.255.255	       Shared address space, often used by ISPs for CGNAT
