## Inter-VLAN Routing

## Objective
The purpose of this lab exercise is to enable communication between devices located in different VLANs using 
Inter-VLAN Routing while maintaining logical network segmentation.

## Scenario
This lab simulates two different buildings. Each building has Human Resources (HR) and Information Technology (IT) departments.
With only switches, departments could communicate only with devices in the same VLAN within the same department.
By attaching a router and configuring inter-VLAN routing, communication between two different VLANs was successfully established.

## Topology
- 2 buildings
- 2 switches
- 1 router
- 8 client PCs
- VLAN 10 - HR
- VLAN 20 - IT

## Technologies Used
- Cisco Packet Tracer
- VLAN
- Inter-VLAN routing
- Router-on-a-stick
- Encapsulation
- Access ports
- Trunk ports
- Router configuration
- Switch configuration
- IPv4 addressing

## Configuration
- Created VLAN 10 for the Human Resources department.
- Created VLAN 20 for the Information Technology department.
- Assigned switch ports to the VLANs using access mode.
- Configured a trunk connection between the two switches.
- Connected the router to the switches through a trunk port.
- Defined a default gateway IP address to be able to communicate between the switch and the router.
- Created router subinterfaces for each VLAN.
- Configured encapsulation on each router subinterface.
- Verified that all hosts were assigned to the correct VLAN and subnet.

## Testing
- Verified communication between devices within the same VLAN.
- Verified successful communication between VLAN 10 and VLAN 20 through the router.
- Confirmed that router subinterfaces correctly forwarded traffic between VLANs.
- Performed connectivity tests using ping.
- Verified correct operation of trunk links and router interfaces.

## Result
This lab successfully demonstrated how Inter-VLAN communication can be achieved using the Router-on-a-Stick method. 
By configuring router subinterfaces with encapsulation and establishing trunk links between network devices, 
seamless communication between VLAN 10 and VLAN 20 was enabled.
The network maintained logical segmentation while allowing controlled data exchange between departments, 
reflecting a real-world enterprise network implementation.
