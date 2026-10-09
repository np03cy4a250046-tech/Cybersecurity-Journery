# What is TCP/IP model?
TCP/IP model is a layered networking framework which tells us how computer communicate to each other and how data is sent over the network between computers.

# Layers of TCP/IP model

# 1.Application layer
- This is the top layer of the TCP/IP model where applications like web browsers email interact with the network.
- Acts as a bridge between user applications and lower network layers.
- Supports protocols such as HTTP, FTP, SMTP, and DNS.
- Handles data formatting so information is correctly understood by both sender and receiver.
- Provides encryption for secure communication.
- Manages sessions to track ongoing connections.

# 2.Transport layer
- It ensures there is reliable data transmission between devices also it help in retransmission of the data if needed.
- Breaks down large data into smaller packets and reassembles them at the destination
- Uses protocol like TCP or UDP for efficient data communication
- TCP is used when we need 100% of the data if some data is missed it retransmits the whole data
- UDP is used when we need faster data and some data missed is fine.


  # 3 Internet layer
  - This layer is all about addressing routing and packaging of the data packets so the data can reached the required destination
  - Assigns IP addresses to identify source and destination devices.
  - Determines the best path for data to travel across networks.
  - Breaks large packets into smaller ones for transmission and reassembles them at the destination.
 
  # 4 Network Access (Link layer)
  - Responsible for physically transmitting data over network hardware, including cables, switches, and wireless connections.
  - Uses hardware(MAC) addresses to identify devices within the same network segment.

