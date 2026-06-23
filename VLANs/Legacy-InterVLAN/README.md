# Legacy Inter-VLAN Routing

## Source

This lab topology was inspired by Jeremy's IT Lab CCNA course and was completed as part of my hands-on networking practice.

## Objective

Configure communication between multiple VLANs using separate physical router interfaces.

## VLAN Information

VLAN    Department     Network       

 10     Engineering     10.0.0.0/26   
 20     HR              10.0.0.64/26  
 30     Sales           10.0.0.128/26 

## Gateway Addresses

 VLAN      Gateway    
  
  10       10.0.0.62  
  20       10.0.0.126 
  30       10.0.0.190 

## Tasks Completed

* Configured VLANs
* Assigned switch access ports
* Configured router interfaces
* Configured default gateways
* Verified inter-VLAN communication
* Tested broadcast behavior using Packet Tracer Simulation Mode

## Verification

* Successful ping between VLANs
* Successful gateway connectivity
* Broadcast behavior verified

## Key Learning Points

* Legacy Inter-VLAN Routing requires one physical router interface per VLAN.
* Routing is performed by the router.
* No trunk link is required.
* This design does not scale well for large numbers of VLANs.

## Result

Successful communication between all VLANs using Legacy Inter-VLAN Routing.
