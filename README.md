# CSIA-210 — Network Protocol Analysis

My Spring 2026 coursework at Ivy Tech Kokomo. Packet capture and TCP/IP protocol analysis with Wireshark, tcpdump, and Nmap. The course follows the textbook chapter-by-chapter — each course module covers two book chapters plus the related hands-on labs, with a midterm capstone wrapping Module 4 and a final capstone wrapping Module 8.

## Tools

- **Wireshark** — main packet-capture and protocol-analysis tool. `Module01/ch01_MyCapture.pcapng` is the saved capture from the first session.
- **tcpdump** — command-line packet capture.
- **Nmap** — reconnaissance scans.
- OSI / TCP-IP layer framing applied throughout the labs.

## Repository layout

```
CSIA210/
  Module01/  Chapters 1-2 hands-on + a saved Wireshark capture (ch01_MyCapture.pcapng)
  Module02/  Chapters 3-4 hands-on
  Module03/  Chapters 5-6 hands-on
  Module04/  Chapters 7-8 hands-on + Midterm Capstone
  Module05/  Chapter 9 hands-on
  Module06/  Chapters 10-11 hands-on
  Module07/  Chapters 12-13 hands-on
  Module08/  Chapter 14 hands-on + Final Capstone
```

## Module walkthrough

- **Module 1 — Introducing TCP/IP and IP Addressing (Chs 1–2).** Intro to TCP/IP, packet structure fundamentals, IP addressing. Includes the `.pcapng` from the first Wireshark capture session.
- **Module 2 — Basic IP Packet Structures and Data Link / Network Layer Protocols (Chs 3–4).** Headers and payloads in depth; Data Link layer and Network Layer mechanics.
- **Module 3 — ICMP and IPv6 Neighbor Discovery (Chs 5–6).** ICMP testing, troubleshooting, message types and codes; IPv6 Neighbor Discovery.
- **Module 4 — Name Resolution + IP Address Autoconfiguration + Midterm Capstone (Chs 7–8 + Midterm).** DNS and other name-resolution services; auto-addressing schemes including APIPA, SLAAC, stateful DHCPv6, ISATAP, 6to4, and Teredo. Midterm capstone wraps the module.
- **Module 5 — TCP/IP Transport Layer Protocols (Ch 9).** TCP vs UDP — common and appropriate uses, behavior under inspection.
- **Module 6 — Transitioning IPv4→IPv6 and Deploying IPv6 (Chs 10–11).** Coexistence issues and techniques; tunneling mechanisms and protocols; planning, deploying, and operating IPv6 on modern networks.
- **Module 7 — Securing TCP/IP Environments and Troubleshooting TCP/IP (Chs 12–13).** Network security fundamentals with IP-security emphasis (perimeter, infrastructure, host); TCP/IP troubleshooting techniques.
- **Module 8 — IPv6 Real-World Applications + Final Capstone (Ch 14 + Final).** IPv6 best practices and real-world deployments. Final capstone wraps the course.

## Outcome

Both capstone assessments (midterm and final) passed.

## Related repos

- [Networking-109](https://github.com/jkosber/Networking-109) — CCNA networking foundations, the prereq for this course.
- [CyberOps-115](https://github.com/jkosber/CyberOps-115) — SOC / security-operations work that uses these protocols in anger.
- [IntroToCybersecurity-105](https://github.com/jkosber/IntroToCybersecurity-105) — broader cybersecurity context.
