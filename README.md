# Simulation-of-a-university-building-in-Packet-Tracer


Simulation of a section of a university building in Packet Tracer 8.0 using IoT technology


## Description
The building has four conventional floors. Each floor contains an activity room and a section of the hallway in front of the room. In addition, a university employee's office has been placed on the first floor.

The computer network consists of a router, five switches, desktop computers, a laptop and a printer. These devices belong to one of five VLANs: Vlan10 for floor 1, Vlan20 for floor 2, Vlan30 for floor 3, Vlan40 for floor 4, and Vlan99 for university staff computers.

Switch “P” supports a VTP server so that you don't have to create all the VLANs separately on each switch. The other switches act as client devices and VLANs cannot be modified on them. In addition, outgoing connections from switch “P” are in trunk mode.

The router acts as a DHCP server, so that all computers in the topology were automatically assigned IP addresses. On the router's g0/1 interface, subinterfaces for VLANs have been created. VLAN access for computers was configured on their interfaces.

IOT devices in the building are operated using the Home Gateway and a smartphone. Connections between IOT devices and the Home Gateway are wireless, while those between the router, switches and PCs are wired.


## IOT DEVICES
Various IOT devices have been placed and configured in the topology. All of them are managed remotely using a smartphone (it is located next to the Home Gateway).

IoT Monitor:
login: admin
password: admin
The server address is the default gateway address - 192.168.25.1.

1. Temperature sensor

- The temperature begins to rise after 6:00 a.m., while it falls after 6:00 p.m. When the temperature reaches 10 degrees Celsius, all the windows in the building open. When the temperature drops below 10 degrees, the windows close. Above 15 degrees, all ceiling fans in the building start up. They, too, will automatically turn off when the temperature drops below 15 degrees.
  
2. Motion sensors and lamps 

- The lamp turns on automatically when the sensor detects movement on the floor. To simulate movement, press the left mouse button on the pictogram of the sensor while holding down ALT. The lamps turn off by themselves after a few seconds.

3.Smoke detectors

- When they detect smoke levels greater than 0.2, a window opens in the room and the building's main siren is activated. Cars are used as the source of smoke. To simulate a smoke incident, start them (left key + ALT) and drag them into the selected room in the topology. The test is best done with the windows closed, otherwise the smoke level may not be sufficient to trigger the alarm.

4.Simulating a fire

- It is also possible to simulate a fire. To do this, drag a fire (“Fire” object) into any room. The fire sensor detects the fire and the sprinkler and alarm siren are immediately activated.

5.RFID card reader

- The lock on the door from the university employee's room is opened with an RFID card reader. Card number 501 opens the lock when it is swiped against the reader. In comparison, there is also a card with the number 101 next to it, which does not open the lock because it has an ID incompatible with the lock ID. Exceptionally, the RFID reader is controlled not by a smartphone, but by a laptop in the employee's office.

6.Coffee maker

- There is a coffee maker in the room on floor 2. It turns on automatically when someone enters the room - it is activated by opening the door (to do this, click on the door with the ALT button). The coffee maker stays on, you can turn it off manually at any time (click, ALT button).

