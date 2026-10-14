# RIP Routing Lab — Four Routers

## Objective

Configure RIP Version 2 across four interconnected routers and practice dynamic route exchange between multiple LANs.

## Topology

Four routers connected in a square topology, with four LAN networks.

## Technologies

* Cisco IOS
* IPv4
* RIP Version 2
* Cisco Packet Tracer

## Networks

* LAN 1: `172.16.1.0`
* LAN 2: `192.168.2.0`
* LAN 3: `192.168.3.0`
* LAN 4: `192.168.4.0`
* Inter-router networks: `10.0.12.0`, `10.0.13.0`, `10.0.24.0`, `10.0.34.0`

## Configuration

```text
enable
configure terminal

router rip
version 2
no auto-summary
network 10.0.0.0
```

Configure the appropriate LAN network statement on each router according to its connected network.

## Verification Commands

```text
show ip protocols
show ip route
show ip route rip
show ip interface brief
show running-config
show ip rip database
ping <DESTINATION_IP>
traceroute <DESTINATION_IP>
```

## Practical Work Completed

* Configured RIP Version 2 across multiple routers.
* Practiced network advertisements and dynamic route learning.
* Inspected routing tables and RIP-learned routes.
* Verified interface status and running configuration.
* Tested connectivity between remote networks.
* Practiced traceroute and troubleshooting commands.
* Tested the relevant verification commands in Cisco Packet Tracer.

## Learning Outcome

Practiced dynamic routing and route verification across a four-router topology.

## Files

* `RIP_ProtocolLab2.pkt` — Packet Tracer lab file
* `topology.png` — Network topology
* `verification.png` — Command outputs and connectivity tests
* 
