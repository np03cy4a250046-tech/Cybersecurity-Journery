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
  
