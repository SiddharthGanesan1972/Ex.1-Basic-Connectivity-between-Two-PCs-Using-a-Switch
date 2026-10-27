## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch		

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1366" height="720" alt="Screenshot 2026-10-21 200505" src="https://github.com/user-attachments/assets/e4291a66-ea41-4269-89e1-b73f21f4d820" />


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


<img width="1366" height="720" alt="Screenshot 2026-10-21 200048" src="https://github.com/user-attachments/assets/4327ec4d-17a6-4223-b9ee-0cbff02dc873" />

<img width="1366" height="720" alt="Screenshot 2026-10-21 200055" src="https://github.com/user-attachments/assets/a7b0dcf4-ae5b-4559-9330-c9830769557a" />

<img width="1366" height="720" alt="Screenshot 2026-10-21 200104" src="https://github.com/user-attachments/assets/01a98da9-e125-4936-97df-2eccda82999f" />

<img width="1366" height="720" alt="Screenshot 2026-10-21 200352" src="https://github.com/user-attachments/assets/116433fc-29bb-422b-8e9a-6144e0faf32b" />

<img width="1366" height="720" alt="Screenshot 2026-10-21 200505" src="https://github.com/user-attachments/assets/9472d276-f4d7-4164-8795-398a0399fe68" />







________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
