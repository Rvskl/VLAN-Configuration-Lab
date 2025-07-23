# VLAN Configuration Lab

This lab demonstrates how to:
- Create VLANs for different departments (HR, Sales, Marketing)
- Assign switch ports to each VLAN
- Configure trunk ports between switches
- Enable inter-VLAN routing using a Layer 3 switch

### Tools Used
- Cisco Packet Tracer 8.2
- Switches and Router (PT Model)
- PC Hosts with assigned VLANs

### Key Commands Used
```bash
Switch(config)# vlan 10
Switch(config-vlan)# name HR
Switch(config-if)# switchport access vlan 10
Switch(config-if)# switchport mode trunk
