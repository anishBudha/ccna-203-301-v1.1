- protocol is a set up rule defining how data should be communicated.
- computer network development started in the 1960s.
- Advanced Research Projects Agency, ARPANET, came online in 1969.
- Ethernet 802.3
- Wi-Fi 802.11
-  ![](media/Pasted%20image%2020251210224112.png)
-  Comparing these layers with a real life example:
- ![](media/Pasted%20image%2020251210224756.png)

1. Application layer: Protocols for communication between application processes; create and interpret data.
	 - HTTP/HTTPS, FTP, DNS, SSH, Telnet, SMTP
2. Transport layer: Provides end to end communication between application processes using port numbers.
	- TCP, UDP, SCTP (Stream Control Transmission Protocol)
3. Internet layer: Provides end to end communication between hosts across networks using IP addresses and routers.
	- IP, ICMP, ARP
4. Local Network layer: Provides hop to hop delivery within a local network using MAC addresses and switches.
	- Ethernet, PPP, MAC, Frame Relay
5. Physical layer: Sends bits as electrical, optical, or radio signals over the physical medium.

- Switches are not counted as hops, they are just for extended the network.
- Application is usually called layer 7 due to OSI model.
- ![](media/Pasted%20image%2020251211000454.png)
- L4 + Data is called segment (TCP) or datagram (UDP), layer 4 PDU
- L3 + L4 + Data is called packet, layer 3 PDU
- L2 header + L3 + L4 + Data + L2 trailer, layer 2 PDU
- A payload means the data encapsulated by the PDU
- ![](media/Pasted%20image%2020251211001000.png)
- if a layer communicates with the same layer of the other device is called same layer interaction.
- ![](media/Pasted%20image%2020251211001528.png)
