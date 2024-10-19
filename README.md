# Simulation-of-a-university-building-in-Packet-Tracer


Simulation of a section of a university building in Packet Tracer 8.0 using IoT technology


## Description
The building has four conventional floors. Each floor contains an activity room and a section of the hallway in front of the room. In addition, a university employee's office has been placed on the first floor.

The computer network consists of a router, five switches, desktop computers, a laptop and a printer. These devices belong to one of five VLANs: Vlan10 for floor 1, Vlan20 for floor 2, Vlan30 for floor 3, Vlan40 for floor 4, and Vlan99 for university staff computers.

Switch “P” supports a VTP server so that you don't have to create all the VLANs separately on each switch. The other switches act as client devices and VLANs cannot be modified on them. In addition, outgoing connections from switch “P” are in trunk mode.

The router acts as a DHCP server, so that all computers in the topology were automatically assigned IP addresses. On the router's g0/1 interface, subinterfaces for VLANs have been created. VLAN access for computers was configured on their interfaces.

IOT devices in the building are operated using the Home Gateway and a smartphone. Connections between IOT devices and the Home Gateway are wireless, while those between the router, switches and PCs are wired.


## Description
