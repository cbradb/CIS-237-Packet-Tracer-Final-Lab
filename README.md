**Overview:**
	This is the culminating test across two Cisco courses, relying on skills and tools learned throughout both. The task is setting up a secure, optimized network in Packet Tracer.
  
**Requirements:**
- configure all routers and switches
	- interfaces/subinterfaces/SVIs
	- VLANs
	- SSH
	- Port Security
	- EtherChannel
	- DHCP Server and Relays
	- OSPF and Default Route
	- HSRP

**Tools & Skills Used:**
	I was fully prepared for this, and leaned on my extensive notes and everything I've learned about Cisco IOS. 

**Quick Rundown of Development:**
	For the most part it was smooth sailing. First I outlined each section, planning every necessary command on each device. Then I organized all those by device, except leaving HSRP and OSPF for last. 
	Executing the commands after all that planning went very smoothly, except one end-device was not pinging or receiving an address via DHCP. After a bit of digging around, I found that I simply overlooked the dhcp helper-address command on that section of the network.
	Overall, had fun, can't wait for the next course. 
