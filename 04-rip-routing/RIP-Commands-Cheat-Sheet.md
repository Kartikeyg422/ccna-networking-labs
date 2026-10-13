
# RIP Commands Cheat Sheet

This document records the Cisco IOS commands I practiced and tested in Cisco Packet Tracer.

## 1. RIP Configuration

```text
enable
configure terminal
router rip
version 2
no auto-summary
network 10.0.0.0
end
```

## 2. RIP Verification

```text
show ip protocols
show ip route
show ip route rip
show ip rip database
show running-config
show running-config | section router rip
```

## 3. Interface Verification

```text
show ip interface brief
show interfaces
show cdp neighbors
show cdp neighbors detail
```

## 4. Connectivity Testing

```text
ping <DESTINATION_IP>
traceroute <DESTINATION_IP>
show arp
show ip route <DESTINATION_IP>
```

## 5. PC Commands

```text
ipconfig
ping <DEFAULT_GATEWAY>
ping <REMOTE_PC_IP>
tracert <REMOTE_PC_IP>
```

## 6. Interface Configuration

```text
configure terminal
interface gigabitEthernet 0/0
ip address <IP_ADDRESS> <SUBNET_MASK>
no shutdown
end
```

## 7. Save Configuration

```text
copy running-config startup-config
```

## 8. Debugging

```text
debug ip rip
undebug all
```

## Practical Experience
I practiced the listed commands to inspect routing information, verify interfaces, test connectivity, and troubleshoot networking issues.
