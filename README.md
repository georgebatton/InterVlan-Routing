# Inter VLAN Routing -CCNA 

Tools used **: Cisco Packet Tracer
Topics Covered**: Static Routes, Variable Length Subnetting, VLAN configuration, Router Subinterfaces, Access Ports, Trunk Ports


## Topology
-8 PCs
-2 Switches
-2 Routers

## Configuration Steps
1. Created Subnets 192.168.1.0/26, 192.168.2.0/26, and 192.168.3.0/30
2. Identified ports with CDP
3. Assigned PC and Router ports to IP addresses, Default Gateways, and Subnets
4. Created static route on PTP connection
5. Assigned ports on switch connected to hosts as access ports
6. Created 3 seperate Vlans with one spanning across 2 seperate LANs.
7. Created trunk ports between SW2 and R2 and same for SW1 and R1
8. Created subinterfaces on R1 and R2 for each vlan using encapsulation dot1q
9. Changed native vlan to 10
10. Tested connectivity.
11. Was unable to connect to Vlan 4 from 192.168.2.0 subnet so added ip address 192.168.1.62 255.255.255.192 to subinterfacef0/1.4 on R1

##File Point to Point InterVlan Routing original.pkt

