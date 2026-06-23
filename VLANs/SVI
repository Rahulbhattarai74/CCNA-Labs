# Switch Virtual Interface (SVI)

## Source

This lab topology was inspired by Jeremy's IT Lab CCNA course and was completed as part of my hands-on networking practice.

## Objective

Configure inter-VLAN routing using a multilayer switch (SVI) instead of Router-on-a-Stick.

## Technologies Used

- VLANs
- Trunk Links
- Layer 3 Switching
- SVIs
- Static Routing

## VLANs

| VLAN | Network | Gateway |
|--------|----------|----------|
| 10 | 10.0.0.0/26 | 10.0.0.62 |
| 20 | 10.0.0.64/26 | 10.0.0.126 |
| 30 | 10.0.0.128/26 | 10.0.0.190 |

## Tasks Completed

- Configured VLANs
- Configured trunk links
- Converted switch port to routed Layer 3 port
- Configured SVIs
- Enabled IP routing
- Configured default route
- Verified inter-VLAN connectivity
- Verified Internet connectivity

## Key Learning Points

- SVIs allow multilayer switches to perform routing.
- A multilayer switch can replace Router-on-a-Stick.
- Inter-VLAN routing is performed locally on the switch.
- This design is more scalable than Legacy Inter-VLAN Routing and ROAS.

## Result

Successful inter-VLAN routing and Internet connectivity using SVI-based routing.

## Screenshots

### Topology

![](1.topology.png)

### SW2 Interface Status

![](2.show-ip-interface-brief-sw2.png)

### Routing Table

![](3.show-ip-route.png)

### R1 Layer 3 Link

![](4.show-ip-interface-brief-r1.png)

### Inter-VLAN Connectivity

![](5.inter-vlan-ping.png)

### Internet Connectivity

![](6.internet-ping.png)
