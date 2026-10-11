# Basic Router Configuration Lab

## Objective

Configure a Cisco router with an IPv4 address and establish basic network connectivity between connected devices.

## Topology

PC → Switch → Router

## Technologies

- Cisco IOS
- IPv4
- Cisco Packet Tracer

## Configuration

```text
enable
configure terminal

interface gigabitEthernet 0/0
ip address <IP_ADDRESS> <SUBNET_MASK>
no shutdown
```

## Verification

```text
show ip interface brief
show running-config
ping <DESTINATION_IP>
```

## Result

Successfully configured the router interface and verified network connectivity.
