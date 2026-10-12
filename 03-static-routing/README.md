# Static Routing Lab

## Objective

Configure static routes between multiple routers to enable communication between different networks.

## Topology

LAN → Router 1 → Router 2 → LAN

## Technologies

- Cisco IOS
- IPv4
- Static Routing
- Cisco Packet Tracer

## Configuration

```text
enable
configure terminal

ip route 192.168.3.0 255.255.255.0 192.168.1.254
```

## Verification

```text
show ip route
show ip interface brief
ping 192.168.3.3
```

## Result

Successfully configured static routing between the routers and verified connectivity between different networks.
