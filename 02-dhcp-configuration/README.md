# DHCP Configuration Lab

## Objective

Configure a Cisco router as a DHCP server and automatically assign IP addresses to client devices.

## Topology

Router → Switch → PCs

## Technologies

- Cisco IOS
- IPv4
- DHCP
- Cisco Packet Tracer

## Configuration

```text
enable
configure terminal

ip dhcp excluded-address 192.168.1.1 192.168.1.10

ip dhcp pool LAN
network 192.168.1.0 255.255.255.0
default-router 192.168.1.1
dns-server 8.8.8.8
```

## Verification

```text
show ip dhcp binding
show ip dhcp pool
show ip interface brief
```

## Result

Successfully configured the Cisco router as a DHCP server and verified automatic IP address assignment to client devices.
