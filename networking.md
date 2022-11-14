## Networks Big and Small
- Local area networks (LANs):
- Wide area networks (WANs)
- Metropolitan area networks (MANs):


## Network Topology
- Node: A node is a device that’s connected to the network.
- Packet: A packet is a message that’s sent over the network from one node to
another node.

### Bus topology
In a bus topology, every node on the network can see every packet that’s sent
on the cable. Each node looks at each packet to determine whether the packet
is intended for it. If so, the node claims the packet. If not, the node ignores the
packet. This way, each computer can respond to data sent to it and ignore data
sent to other computers on the network.

### Star topology
In a star topology, each network node is connected to a central device called a hub
or a switch, Star topologies are commonly used with LANs.
Strictly speaking, only networks that use switches have a true star topology. If the
network uses a hub, the network topology has the physical appearance of a star,
but it’s actually a bus. That’s because when a hub is used, each computer on the
network sees all the packets sent over the network, just like in a bus topology.

### Ring topology
 In a ring topology, packets are sent around the circle from computer to computer. Each computer looks at each packet to decide whether the packet was intended for it. If not,
the packet is passed on to the next computer in the ring.

### Mesh topology
has multiple connections
between each of the nodes on the network. The advantage
of a mesh topology is that if one cable breaks, the network can use an alternative
route to deliver its packets.

## (OSI) Reference Model
The OSI Reference Model identifies seven distinct layers at which a protocol may operate
- Physical (layer 1): Describes the mechanical and electrical details of network
components such as cables, connectors, and network interfaces.
- Data link (layer 2): Describes the basic techniques that networks use to
uniquely identify devices on the network (typically via a MAC address) and the
means for one device to send information over the physical layer to another
device, in the form of data packets.
- Network (layer 3): Handles the routing of data across networks. Routers
operate at the network layer.
- Transport (layer 4): Provides for reliable delivery of packets.
- Session (layer 5): Establishes sessions between network applications.
- Presentation (layer 6): Converts data so that systems that use different data
formats can exchange information.
- Application (layer 7): Allows applications to request network services.
    




## What’s Important in a Server
- Scalability
- Reliability
- Availability
- Service and support

## Components of a Server Computer
- Motherboard
- Processor
  - Clock speed refers to how fast the basic clock that drives the processor’s operation ticks. 
  - processor cores utilize a technology called **hyperthreading**, which effectively lets each processor core juggle two threads at once. 
- Memory
- Hard drives
- Network interfaces
- Video
- Power supply
-    
