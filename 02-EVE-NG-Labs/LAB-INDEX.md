# EVE-NG Lab Index

**EVE-NG PRO:** 192.168.1.100
**Login:** admin / (password)

---

| # | Lab Name | Domain | Topology | Status | Notes |
|---|----------|--------|----------|--------|-------|
| 01 | OSPF Multi-Area | 3.2.a | R1-R4, 3 areas | 🔄 In Progress | Pynet Module 1 |
| 02 | | | | 🔲 | |

---

## Lab Naming Convention
```
[Domain]-[Topic]-[Variant].unl
Example: 3.2-OSPF-MultiArea-v1.unl
```

## Standard Verification Commands
```
# OSPF
show ip ospf neighbor
show ip ospf database
show ip route ospf

# BGP
show bgp summary
show bgp ipv4 unicast

# STP
show spanning-tree summary
show spanning-tree vlan X detail

# Save config
write memory  (or)  copy run start
```
