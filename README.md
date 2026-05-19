# CSIA-210 — Network Protocol Analysis

My Spring 2026 coursework for **Ivy Tech CSIA 210 — Network Protocol Analysis** at Ivy Tech Kokomo. Packet capture and protocol analysis using Wireshark, tcpdump, and Nmap. The course follows the textbook chapter-by-chapter — every module is a chapter (or two), and the work is `Hands On` lab submissions plus two capstone assessments (midterm and final).

## What's covered

IP packet structure (headers, payloads), data link and network-layer protocols, hardware addressing / ARP / Neighbor Discovery, routing protocol behavior (RIP, OSPF, EIGRP, BGP for both IPv4 and IPv6), ICMP types and codes, IPv6 neighbor discovery, host and interface address determination, all the auto-addressing schemes (APIPA, SLAAC, stateful DHCPv6, ISATAP, 6to4, Teredo), DNS, TCP vs UDP design choices, IPv4 / IPv6 coexistence and tunneling, DHCPv4 and DHCPv6, and network security at the perimeter / infrastructure / host layers.

## Tools used

- **Wireshark** — main packet-capture and protocol-analysis tool. There's a saved `ch01_MyCapture.pcapng` from the first session in `Module01/` for reference.
- **tcpdump** — command-line packet capture.
- **Nmap** — reconnaissance scans.
- OSI / TCP-IP layer framing applied throughout the labs.

## Repository layout

```
CSIA210/
  Module01/  Chapters 1-2 hands-on + a saved Wireshark capture
  Module02/  Chapters 3-4 hands-on
  Module03/  Chapters 5-6 hands-on
  Module04/  Chapters 7-8 hands-on + Midterm Capstone
  Module05/  Chapter 9 hands-on
  Module06/  Chapters 10-11 hands-on
  Module07/  Chapters 12-13 hands-on
  Module08/  Chapter 14 hands-on + Final Capstone
```

## Module walkthrough

- **Module 1 (Chs 1–2).** Intro to protocol analysis; IP packet structure. The `.pcapng` from the first capture session is here.
- **Module 2 (Chs 3–4).** Data Link layer and Network Layer mechanics.
- **Module 3 (Chs 5–6).** Hardware addressing, ARP, IPv6 Neighbor Discovery.
- **Module 4 (Chs 7–8) + Midterm Capstone.** Routing protocols (RIP / OSPF / EIGRP / BGP) and host / interface address determination, plus the midterm capstone deliverable.
- **Module 5 (Ch 9).** Auto-addressing — APIPA, SLAAC, stateful DHCPv6, ISATAP, 6to4, Teredo.
- **Module 6 (Chs 10–11).** DNS; TCP vs UDP comparison and design considerations.
- **Module 7 (Chs 12–13).** IPv4 / IPv6 coexistence and tunneling; DHCPv4 / DHCPv6 behavior.
- **Module 8 (Ch 14) + Final Capstone.** Network security across the perimeter, infrastructure, and host layers, plus the final capstone.

## Outcome

Course completed Spring 2026 — counts toward the Cyber Security & Information Assurance Technical Certificate at Ivy Tech Kokomo. Both capstone assessments (midterm and final) passed.

## Related repos

- [Networking-109](https://github.com/jkosber/Networking-109) — CCNA networking foundations this course builds on.
- [CyberOps-115](https://github.com/jkosber/CyberOps-115) — SOC / security-operations work that uses these protocols in anger.
- [IntroToCybersecurity-105](https://github.com/jkosber/IntroToCybersecurity-105) — broader cybersecurity context.
