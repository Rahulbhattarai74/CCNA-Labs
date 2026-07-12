# OSPF Part 3

## Objective

Troubleshoot and resolve common OSPF issues, restore neighbor adjacencies, verify routing, and examine the OSPF Link-State Database (LSDB).

## Tasks Completed

- Configured the new serial link between R1 and R2
- Fixed missing OSPF route on R3
- Restored OSPF neighbor adjacency with R5
- Verified Internet connectivity
- Verified OSPF neighbors
- Verified routing table
- Examined the OSPF LSDB

## Result

Successfully troubleshot and restored OSPF operation. All routers formed neighbor relationships, routing was restored, and end-to-end connectivity was verified.

## Screenshots

### 1. Topology
![Topology](1.topology.png)

### 2. R1-R2 Serial Configuration
![Serial Config](2.r1-r2-serial-config.png)

### 3. R3 Route Fixed
![R3 Route](3.r3-fixed-route.png)

### 4. R5 Neighbor Fix
![Neighbor Fix](4.r5-neighbor-fix.png)

### 5. Internet Ping Verification
![Ping](5.internet-ping-success.png)

### 6. OSPF Neighbor Table
![Neighbor Table](6.show-ip-ospf-neighbor.png)

### 7. Routing Table
![Routing Table](7.show-ip-route.png)

### 8. OSPF Database
![OSPF Database](8.show-ip-ospf-database.png)
