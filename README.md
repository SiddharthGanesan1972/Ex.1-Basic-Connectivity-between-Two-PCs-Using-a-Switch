## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 	10/15/2026

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram



________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)



<img width="1547" height="777" alt="Screenshot 2026-07-22 110108" src="https://github.com/user-attachments/assets/246c7952-de95-46bb-a891-c17cf67d9bb2" />
<img width="733" height="630" alt="Screenshot 2026-07-22 105303" src="https://github.com/user-attachments/assets/536f0843-780a-426b-8b9b-45fbb43cb173" />
<img width="1907" height="1001" alt="Screenshot 2026-07-22 105905" src="https://github.com/user-attachments/assets/020654b0-0a4b-4fca-94a6-a77e7ec832c2" />



________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
