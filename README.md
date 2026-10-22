# Multi-Area OSPF Enterprise Network

A Cisco Packet Tracer project demonstrating enterprise network design, routing, VLAN segmentation, and access control.

## Features

- Multi-area OSPF routing (Areas 0, 1, and 2)
- VLAN segmentation and router-on-a-stick inter-VLAN routing
- OSPF route advertisement and routing table verification
- Spanning Tree Protocol (STP) and redundant network links
- Extended ACLs to restrict access between server networks
- Separate server subnets for Area 1 and Area 2

## Testing & Verification

The network was tested in Cisco Packet Tracer using:

- OSPF neighbor and routing table verification
- End-to-end connectivity tests using ICMP ping
- VLAN and interface status checks
- ACL verification and access restriction tests between server networks
- Connectivity troubleshooting and IP addressing validation

## Tools

- Cisco Packet Tracer
- Cisco IOS CLI
- OSPF, VLANs, STP, ACLs, IPv4 subnetting

## Files

- `.pkt` — Cisco Packet Tracer network topology
- Screenshots — Topology, routing, and connectivity/security test results

- ## Lessons Learned & Conclusion

This project reinforced the importance of careful network planning, including IP addressing, subnetting, VLAN design, and OSPF area configuration.

During implementation and testing, several issues had to be identified and resolved, including missing OSPF network advertisements and incorrect IP addressing between routers. These problems affected routing and end-to-end connectivity.

The biggest takeaway was that **even a well-planned network can encounter unexpected issues during implementation**. A solid plan provides a foundation, but systematic troubleshooting, verification, and patience are essential to make the network work as intended.

This project improved my understanding of multi-area OSPF, network segmentation, access control, and practical Cisco network troubleshooting.


Screenshots:

<img width="1920" height="1080" alt="Lab 6 Topology" src="https://github.com/user-attachments/assets/bad251df-5b6b-46d9-aa8a-8d948fcb648c" />
<img width="1920" height="1080" alt="OSPF Neighbors" src="https://github.com/user-attachments/assets/2ae52ad7-f484-4fb3-9e6f-d479b12eb60a" />
<img width="1920" height="1080" alt="Access-list R3" src="https://github.com/user-attachments/assets/1baed198-87e7-4f1d-9c73-533d3c102f5a" />
<img width="1920" height="1080" alt="ACL test" src="https://github.com/user-attachments/assets/00c44515-fddb-4087-93bf-03623b4dcc80" />
