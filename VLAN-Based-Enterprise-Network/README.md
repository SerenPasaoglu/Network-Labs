## VLAN-Based Enterprise Network
## Objective
The purpose of this lab study is to design a VLAN-based enterprise network that enables secure communication between users within the same department while logically separating departments and preventing access from different buildings.

## Network Design
This lab simulates an enterprise environment with two office buildings. Each building contains Human Resources (HR) and Information Technology (IT) departments. 
The network was segmented using VLANs to improve security and reduce unnecessary broadcast traffic.
A trunk link was configured between the switches to extend VLAN connectivity across both buildings while maintaining logical separation between departments.

## Topology
- 2 buildings
- 2 switches
- 8 laptops
- VLAN 10 (HR)
- VLAN 20 (IT)

## Configuration
- Designed a network topology consisting of two building which names are A_Binası and B_Binası, connected through switches.
- Created VLAN 10 for the HR department and assigned ports between 1 and 10.
- Created VLAN 20 for the IT department and assigned ports between 11 and 20.
- Access mode was used to allow laptops to be reached via the switch.
- Configured the inter-switch connection as a trunk port to allow VLAN traffic between the two buildings.
- To allow VLAN traffic between the two buildings, I configured the connection between the switches as a trunk port
- Assigned IP addresses to all end devices according to their corresponding VLAN subnet.
- Verified that all devices were connected to the correct switch interfaces and VLANs.

## Testing
- Verified successful communication between HR devices located in different buildings.
- Verified successful communication between IT devices located in different buildings.
- Confirmed that communication between different VLANs was blocked, not allowed to communicate with each other, demonstrating proper VLAN isolation.
- Performed connectivity tests using ping to validate network behavior.
- Verified that trunk links successfully carried traffic for both VLANs.
- Confirmed that all end devices received connectivity only within their assigned VLAN.

## Result
This lab work demonstrated how VLANs can logically separate departments in different buildings while maintaining secure communication between users belonging to the same department within the VLAN. 
The simulation showed how logical separation is necessary to ensure that communication reaches the required departments without causing data pollution in others. 
I gained practical experience in creating VLANs, configuring access and trunk ports, and traffic isolation in an enterprise network.


