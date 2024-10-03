# TCP/IP Five-Layer Network Model
![[Pasted image 20240320070206.png]]
- **Physical Layer**
  Represents the physical devices that interconnect computers
- **Data Link Layer**
  Responsible for defining a common way of interpreting these signals so network devices can communicate
- **Network/ Internet Layer**
  A collection of networks connected together through routers, the most famous of these being the Internet
- **Transport Layer** 
  Sorts out which client and server programs are supposed to get that data
* **Application**
  Many protocols, application specific
![[Pasted image 20240320071320.png]]

# OSI Seven-Layer Network Model
7. **Application**
   Provides different services to the application
6. **Presentation**
   Converts the information
5. **Session**
   Handles problems which are not communication issues
4. **Transport**
   Provides end to end communication control
3. **Network**
   Routs the information in the network
2. **Data Link**
   Provides error control
1. **Physical**
   Connects the entity to the transmission media
# Cables
Copper & Fiber

most common forms of copper twisted pair cables used in networking, are Cat 5, Cat 5e, and Cat 6 cables.

Cat 5 is older and has been mostly replaced by Cat 5e and Cat 6 cables.

![[Pasted image 20240320072716.png]]
because of Crosstalk
when an electrical pulse on one wire is accidentally detedcted on another wire

**Fiber cables**
Contain individual optical fibers, which are tiny tubes made out of glass about the width of a human hair
# Hubs and Switches
**Hub**
A physical layer device that allows for connections from many computers at once.
![[Pasted image 20240320073704.png]]

**Collision domain**
A network segment where only one device can communicate at a time

If multiple systems try sending data at the same time, the electrical pulses sent across the cable can interfere with each other.

![[Screenshot 2024-03-20 at 7.39.31 AM.png]]Hubs are rare because of the Collision domain, making them slow

Hub is mostly historical artifact now, more used becuase of less collision domain issues

**Network switch**
Layer 2 device vs Hub being Layer 1  
![[Pasted image 20240320074319.png]]The Switch can inspect the contents of the ethernet protocol data being sent around the network, determine which system the data is intended for and then only send that data to that one system. This reduces or even completely eliminates the size of collision domains to that one system.

Leads to fewer re-transmissions and higher overall throughput,



# Routers
## Hubs and switches
The primary devices used to connect computers on a single network, usually refferred to as a LAN, or local area network

## Router
A device that knows how to forward data between independent networks

Router are Level 3 devices