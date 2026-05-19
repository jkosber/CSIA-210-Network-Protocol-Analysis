# CSIA-210 — Network Protocol Analysis

Coursework for **Ivy Tech CSIA 210: Network Protocol Analysis**, completed Spring 2026 at Ivy Tech Kokomo. Packet capture and protocol analysis with industry-standard tools, working chapter-by-chapter through the course textbook with hands-on submissions for each chapter and two capstone assessments at midterm and finals.

## Topics covered

- IP packet structure (headers, payloads)
- Data Link and Network Layer protocols
- Hardware addressing, ARP, and the Neighbor Discovery Protocol (NDP)
- Routing protocols — RIPv1/v2, OSPF, EIGRP, BGP (IPv4 and IPv6 behavior)
- ICMP testing, troubleshooting methods, security implications, message types and codes
- IPv6 Neighbor Discovery
- Host and interface address determination
- Auto-addressing — APIPA, stateless and stateful autoconfiguration, ISATAP, 6to4, Teredo
- DNS — symbolic name resolution
- TCP vs UDP — appropriate use cases
- IPv4 / IPv6 coexistence and tunneling
- DHCPv4 / DHCPv6
- Network security basics — perimeter, infrastructure, host

## Tools and technologies

- **Wireshark** — packet capture and protocol analysis (includes a saved `ch01_MyCapture.pcapng` reference capture)
- **tcpdump** — command-line packet capture
- **Nmap** — network reconnaissance
- OSI / TCP-IP model framing applied throughout

## Repository layout

```
CSIA210/
  Module01/  Chapters 1-2 hands-on projects + a saved Wireshark capture
  Module02/  Chapters 3-4 hands-on projects
  Module03/  Chapters 5-6 hands-on projects
  Module04/  Chapters 7-8 hands-on projects + Midterm Capstone
  Module05/  Chapter 9 hands-on project
  Module06/  Chapters 10-11 hands-on projects
  Module07/  Chapters 12-13 hands-on projects
  Module08/  Chapter 14 hands-on project + Final Capstone
```

## Module guide

- **Module 1 (Chs 1–2)** — Introduction to protocol analysis; IP packet structure. Includes a saved `.pcapng` from the first capture session.
- **Module 2 (Chs 3–4)** — Data Link layer and Network Layer mechanics.
- **Module 3 (Chs 5–6)** — Hardware addressing, ARP, IPv6 Neighbor Discovery.
- **Module 4 (Chs 7–8) + Midterm Capstone** — Routing protocols (RIP / OSPF / EIGRP / BGP) and host/interface address determination, consolidated into the midterm capstone submission.
- **Module 5 (Ch 9)** — Auto-addressing schemes (APIPA, SLAAC / stateful DHCPv6, ISATAP, 6to4, Teredo).
- **Module 6 (Chs 10–11)** — DNS resolution; TCP vs UDP comparison and use-case analysis.
- **Module 7 (Chs 12–13)** — IPv4 / IPv6 coexistence and tunneling; DHCPv4 / DHCPv6 behavior.
- **Module 8 (Ch 14) + Final Capstone** — Network security fundamentals across perimeter, infrastructure, and host layers, consolidated into the final capstone submission.

## Status

Course completed Spring 2026 — counted toward the Cyber Security & Information Assurance Technical Certificate at Ivy Tech Kokomo. Two capstone assessments (midterm and final) passed.

## Related

- [Networking-109](https://github.com/jkosber/Networking-109) — CCNA Part 1, the networking foundations this course builds on
- [CyberOps-115](https://github.com/jkosber/CyberOps-115) — applied SOC/security operations work that uses these same protocols
- [IntroToCybersecurity-105](https://github.com/jkosber/IntroToCybersecurity-105) — broader cybersecurity context
