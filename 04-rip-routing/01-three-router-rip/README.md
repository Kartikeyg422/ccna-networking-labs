# RIP Routing Lab — Three Routers

## Objective
Configure RIP Version 2 between three interconnected routers and practice dynamic routing between different LAN networks.

## Topology
Three routers connected in a triangular topology with three LAN networks.

## Technologies
- Cisco IOS
- IPv4
- RIP Version 2
- Cisco Packet Tracer

## Networks
- LAN 1: `192.168.1.0`
- LAN 2: `192.168.2.0`
- LAN 3: `192.168.3.0`
- Inter-router networks: `10.0.20.0`, `10.0.30.0`, `10.0.40.0`

## Configuration

```text
enable
configure terminal
router rip
version 2
no auto-summary
network 10.0.0.0
```

Configure the appropriate LAN network statement on each router according to its connected networks.

## Verification

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
- Configured and tested RIP Version 2.
- Practiced RIP network statements and `no auto-summary`.
- Checked routing tables and RIP-learned routes.
- Verified router interfaces and configurations.
- Tested connectivity using ping and traceroute.
- Practiced routing troubleshooting commands.

## Learning Outcome
Practiced dynamic routing and route verification between three routers.

## Files
- `RIP_ProtocolLab(2).pkt`
- `topology.png`
- `verification.png`

