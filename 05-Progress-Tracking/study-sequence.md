# CCIE Enterprise — Study Sequence

> Based on 40 PDFs in `07-Pynet-CCIE-Labs/CCIE Enterprise/`
> Follow this order — each phase builds on the previous.
> Reference books: **ENCOR Official Book.pdf** + **CCNP-ENARSI-300-410-OfficialCertGuide.pdf**

---

## Phase 1 — Layer 2 Foundations (ENCOR 3.1)
*Build switching knowledge before routing*

| # | PDF | Blueprint Topic |
|---|-----|----------------|
| 1 | VLANs.pdf | 3.1.a VLANs & trunking |
| 2 | Configuring Inter-VLAN Routing - ROAS.pdf | 3.1.a Inter-VLAN routing |
| 3 | Configuring Inter-VLAN Routing - SVI.pdf | 3.1.a Inter-VLAN routing |
| 4 | Spanning Tree.pdf | 3.1.b STP/RSTP/MST |
| 5 | Configuring Etherchannels.pdf | 3.1.c EtherChannel LACP/PAgP |
| 6 | Static MAC Address Table Entry.pdf | 3.1 L2 fundamentals |
| 7 | VLAN Access-List (VACL).pdf | 3.1 / 5.2 L2 filtering |

---

## Phase 2 — Layer 2 Security (ENCOR 3.1.d)
*Short phase — all closely related*

| # | PDF | Blueprint Topic |
|---|-----|----------------|
| 8 | Configuring Port Security.pdf | 3.1.d Port security |
| 9 | Configuring DHCP Snooping.pdf | 3.1.d DHCP snooping |
| 10 | DAI (Dynamic ARP Inspection).pdf | 3.1.d DAI |
| 11 | IP Source Guard (IPSG).pdf | 3.1.d IP Source Guard |

---

## Phase 3 — IP Services (ENCOR 3.4)
*Core services needed before routing labs*

| # | PDF | Blueprint Topic |
|---|-----|----------------|
| 12 | Cisco Network Time Protocol (NTP).pdf | 3.4.b NTP |
| 13 | Introduction to CDP.pdf | 3.4 Discovery protocols |
| 14 | Link Layer Discovery Protocol (LLDP).pdf | 3.4 Discovery protocols |
| 15 | Configuring HSRP.pdf | 3.4.e FHRP |
| 16 | Configuring VRRP.pdf | 3.4.e FHRP |

---

## Phase 4 — OSPF Advanced (ENCOR 3.2.a)
*Builds on existing OSPF multi-area knowledge from current EVE-NG lab*

| # | PDF | Blueprint Topic |
|---|-----|----------------|
| 17 | OSPF ABR Type 3 LSA Filtering on Cisco IOS.pdf | 3.2.a OSPF filtering |
| 18 | OSPF Distribute-List Filtering.pdf | 3.2.a OSPF filtering |
| 19 | OSPF LSA Type 5 Filtering on Cisco IOS.pdf | 3.2.a OSPF filtering |

---

## Phase 5 — EIGRP + Redistribution (ENCOR 3.2.b / 3.2.d)

| # | PDF | Blueprint Topic |
|---|-----|----------------|
| 20 | Redistribution between EIGRP and OSPF.pdf | 3.2.d Route redistribution |
| 21 | DMVPN with EIGRP Phase 3.pdf | 2.1.c DMVPN + 3.2.b EIGRP |

---

## Phase 6 — Security & ACLs (ENCOR 5.2)

| # | PDF | Blueprint Topic |
|---|-----|----------------|
| 22 | Configuring ACL - Standard.pdf | 5.2.a ACLs |
| 23 | Configuring ACL - Extended.pdf | 5.2.a ACLs |
| 24 | Unicast Reverse Path Forwarding (uRPF).pdf | 5.2.d uRPF |

---

## Phase 7 — QoS (ENCOR 3.x / ENARSI)
*Study conceptual first, then config*

| # | PDF | Blueprint Topic |
|---|-----|----------------|
| 25 | Introduction to QoS (Quality of Service).pdf | QoS fundamentals |
| 26 | QoS Classification on Cisco IOS Router.pdf | Classification & marking |
| 27 | QoS Marking on Cisco IOS Router.pdf | DSCP/CoS marking |
| 28 | QoS Traffic Policing Explained.pdf | Policing concepts |
| 29 | QoS Policing Configuration Example.pdf | Policing config |
| 30 | QoS Traffic Shaping Explained.pdf | Shaping concepts |
| 31 | QoS LLQ (Low Latency Queueing) on Cisco IOS.pdf | Queuing/LLQ |

---

## Phase 8 — SD-WAN (ENCOR 1.2) — Labs
*7 sequential labs — do in order*

| # | PDF | Topic |
|---|-----|-------|
| 32 | SDWAN-Lab1.pdf | SD-WAN architecture / vManage setup |
| 33 | SDWAN-Lab2.pdf | vBond / vSmart |
| 34 | SDWAN-Lab3.pdf | WAN Edge onboarding |
| 35 | SDWAN-Lab4.pdf | Policies |
| 36 | SDWAN-Lab5.pdf | Advanced policies |
| 37 | SDWAN-Lab6.pdf | Troubleshooting |
| 38 | SDWAN-Lab7.pdf | Full scenario |

---

## Reference Books (use throughout all phases)

| Book | When to use |
|------|------------|
| ENCOR Official Book.pdf | Primary theory reference — read chapters aligned to current phase |
| CCNP-ENARSI-300-410-OfficialCertGuide.pdf | Deep dive on routing (OSPF/EIGRP/BGP/redistribution) during Phases 4-5 |

---

## What's NOT covered by these PDFs (gaps to fill)
- BGP (study from ENCOR book chapters)
- Wireless (study from ENCOR book)
- SD-Access / DNA Center (study from ENCOR book)
- Multicast (study from ENCOR book)
- Automation/Python/Ansible (separate Pynet courses)
- Network Assurance / IP SLA / EEM

---

## Progress

| Phase | Status | Completed |
|-------|--------|-----------|
| Phase 1 — L2 Foundations | 🔲 Not Started | 0/7 |
| Phase 2 — L2 Security | 🔲 Not Started | 0/4 |
| Phase 3 — IP Services | 🔲 Not Started | 0/5 |
| Phase 4 — OSPF Advanced | 🔲 Not Started | 0/3 |
| Phase 5 — EIGRP + Redistribution | 🔲 Not Started | 0/2 |
| Phase 6 — Security & ACLs | 🔲 Not Started | 0/3 |
| Phase 7 — QoS | 🔲 Not Started | 0/7 |
| Phase 8 — SD-WAN Labs | 🔲 Not Started | 0/7 |
