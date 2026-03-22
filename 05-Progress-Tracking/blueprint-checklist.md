# ENCOR 350-401 Blueprint Checklist

> Legend: 🔲 Not Started | 🔄 In Progress | ✅ Done | ⭐ Needs Review

---

## 1.0 Architecture (15%)

### 1.1 SD-Access
- [ ] 1.1.a Fabric design
- [ ] 1.1.b Underlay (IS-IS, OSPF)
- [ ] 1.1.c Overlay (VXLAN, LISP)
- [ ] 1.1.d Fabric roles (edge, border, control plane)

### 1.2 SD-WAN
- [ ] 1.2.a Architecture (vManage, vSmart, vBond, vEdge)
- [ ] 1.2.b WAN Edge onboarding
- [ ] 1.2.c Policies (centralized, localized)

### 1.3 Cisco Cloud Offerings
- [ ] 1.3.a Cloud deployment models (IaaS, PaaS, SaaS)
- [ ] 1.3.b Cisco cloud solutions overview

---

## 2.0 Virtualization (10%)

### 2.1 Device Virtualization
- [ ] 2.1.a VRF-Lite
- [ ] 2.1.b GRE / IPsec tunnels
- [ ] 2.1.c DMVPN (phases 1, 2, 3)

### 2.2 Virtualization Technologies
- [ ] 2.2.a Type 1 vs Type 2 hypervisors
- [ ] 2.2.b Containers (Docker, Kubernetes basics)
- [ ] 2.2.c Virtual switching (vSwitch, Nexus 1000V)

---

## 3.0 Infrastructure (30%)

### 3.1 Layer 2
- [ ] 3.1.a VLANs, trunking (802.1Q), DTP
- [ ] 3.1.b STP (RSTP, MST, PVST+, Rapid PVST+)
- [ ] 3.1.c EtherChannel (LACP, PAgP, static)
- [ ] 3.1.d Port security, DHCP snooping, DAI, IP Source Guard

### 3.2 IP Routing
- [ ] 3.2.a OSPF v2/v3 (multi-area, LSA types, path selection)
- [ ] 3.2.b EIGRP (named mode, DUAL, summarization)
- [ ] 3.2.c BGP (iBGP, eBGP, attributes, path selection, communities)
- [ ] 3.2.d Route redistribution and filtering
- [ ] 3.2.e PBR (Policy-Based Routing)
- [ ] 3.2.f VRF-Lite routing

### 3.3 Wireless
- [ ] 3.3.a 802.11 standards (a/b/g/n/ac/ax)
- [ ] 3.3.b Autonomous vs Lightweight (FlexConnect, Local mode)
- [ ] 3.3.c WLC architecture
- [ ] 3.3.d SSID, WLAN profiles, QoS wireless

### 3.4 IP Services
- [ ] 3.4.a NAT (static, dynamic, PAT)
- [ ] 3.4.b NTP (stratum, authentication)
- [ ] 3.4.c DHCP (server, relay, option 82)
- [ ] 3.4.d DNS
- [ ] 3.4.e FHRP (HSRP, VRRP, GLBP)
- [ ] 3.4.f Syslog
- [ ] 3.4.g SNMP (v2c, v3)
- [ ] 3.4.h Netflow / IPFIX

### 3.5 Multicast
- [ ] 3.5.a PIM (Sparse, Dense, Auto-RP, BSR)
- [ ] 3.5.b IGMP (v1, v2, v3)
- [ ] 3.5.c RP placement and redundancy

---

## 4.0 Network Assurance (10%)

- [ ] 4.1 Diagnose network problems using tools (debug, ping, traceroute, SNMP, syslog)
- [ ] 4.2 Configure and verify Netflow/IPFIX
- [ ] 4.3 IP SLA (ICMP echo, jitter, HTTP)
- [ ] 4.4 Cisco DNA Center assurance (basic)
- [ ] 4.5 Span / RSPAN / ERSPAN
- [ ] 4.6 Embedded Event Manager (EEM) basics

---

## 5.0 Security (20%)

### 5.1 Device Access Control
- [ ] 5.1.a AAA (TACACS+, RADIUS)
- [ ] 5.1.b 802.1X (EAP, ISE integration)
- [ ] 5.1.c Local RBAC, privilege levels, parser views

### 5.2 Network Security
- [ ] 5.2.a ACLs (standard, extended, named, reflexive, time-based)
- [ ] 5.2.b Zone-Based Firewall (ZBF)
- [ ] 5.2.c CoPP (Control Plane Policing)
- [ ] 5.2.d uRPF (Unicast Reverse Path Forwarding)
- [ ] 5.2.e Dynamic ARP Inspection

### 5.3 Infrastructure Security
- [ ] 5.3.a SSH, console, VTY hardening
- [ ] 5.3.b SNMP v3 auth/encryption
- [ ] 5.3.c NTP authentication

---

## 6.0 Automation (15%)

### 6.1 Python & APIs
- [ ] 6.1.a Python basics for networking (loops, functions, file I/O)
- [ ] 6.1.b REST APIs (GET, POST, PUT, DELETE, JSON parsing)
- [ ] 6.1.c RESTCONF / NETCONF / YANG

### 6.2 Automation Tools
- [ ] 6.2.a Ansible (playbooks, inventory, modules, roles)
- [ ] 6.2.b Terraform basics
- [ ] 6.2.c Git (version control workflows)

### 6.3 Cisco Automation Platforms
- [ ] 6.3.a Cisco DNA Center APIs
- [ ] 6.3.b Cisco SD-WAN APIs (vManage)
- [ ] 6.3.c Cisco NSO basics

---

## Score Tracking

| Date | Mock Exam | Score | Target | Notes |
|------|-----------|-------|--------|-------|
| | | | 85%+ | |
