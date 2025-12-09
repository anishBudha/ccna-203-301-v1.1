- interfaces and ports
- switches has lots of ports or interfaces
- 10/100/1000Base-T Ports
- Auto-MDIX
- RJ-45, Registered Jack
	- Used at the end of the copper ethernet cable
- Ethernet is a collection of network protocols and standards.
- 8 bits = 1 byte
	- Speed is measured in bits per second not bytes per seconds.
	- Data on drives are measured in bytes per seconds.
	- ![](media/Pasted%20image%2020251209115534.png)
- Ethernet standards are defined by IEEE 802.3 
- Ethernet standards, copper cable:
- ![](media/Pasted%20image%2020251209115713.png)
- BASE refers to baseband signaling and T refers to twisted pair cables.
- UTP, Unshielded Twisted Pairs
	- Vulnerable to electromagnetic interference
	- twist helps to prevent electromagnetic interference
- 10 Base-T and 100 Base-T use 2 pairs(4 wires)
- 1000Base-T and 10GBase-T use 4 pairs(8 wires)
- ![](media/Pasted%20image%2020251209120106.png)
- If tx and rx are opposite on two devices being used, use **straight through cable**.
- If not use **crossover cable**.
- ![](media/Pasted%20image%2020251209120426.png)

| Device         | Tx   | Rx   |
| -------------- | ---- | ---- |
| Router         | 1, 2 | 3, 6 |
| Firewall       | 1, 2 | 3, 6 |
| PC             | 1, 2 | 3, 6 |
| Switch and Hub | 3, 6 | 1, 2 |
- Auto MDI-X used in modern devices, helps devices recognize the pins of opposite device and adjust, so any cable can be used.
- For larger networks, which can greater areas, use fiber-optic connections.
- ![](media/Pasted%20image%2020251209121233.png)
- Fiber optics use lights to transfer data.
- The structure of the cable, Core, Cladding (reflects light), a protective buffer and a outer jacket.
- Multimode fiber, core is wider, allows, multiple angles, longer than copper wire, cheaper than singlemode fiber.
- Singlemode fiber, core is narrower, single angle know as mode, longer than multimode fiber, expensive than multimode fiber.
- ![](media/Pasted%20image%2020251209121616.png)
- ![](media/Pasted%20image%2020251209121649.png)
- To connect multiple hosts available in the shorter distance like an office building, use UTP cable, sinces switches do not have enough SFP interfaces to support many end hosts.