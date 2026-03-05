##Project Overview

In this lab, i used Cisco Packet Tracer to simulate a small healthcare network environment.Network segmentation was imlemented using VLANs to separate different departments.

Two departments were created:

VLAN 10 – PRESCRIPTIONS
VLAN 20 – BILLING

The router performs Inter-VLAN routing using Router-on-a-Stick configuration.

##Network Topology
1 Router → 1 Switch → 4 PCs

##STEPS
1. Create VLANs on the switch.
2. Assign access ports to VLANS.
3. Configure trunk port from switch to router.
4. Configure router-on-a-stick.
5. Configure IP addresses to PCs (IPv4 and default gateway)

##VERIFICATION COMMANDS in every step:

1&2. show vlan brief 
3. show interfaces trunk
4. show ip interface brief
5. Ping  to test connectivity from PC0 to PC1 (same vlan) and from PC0 to PC3 (inter-vlan)
   











   
