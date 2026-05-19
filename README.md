# CSIA-210 — Network Protocol Analysis

My Spring 2026 coursework for **Ivy Tech CSIA 210 — Network Protocol Analysis** at Ivy Tech Kokomo. Packet capture and TCP/IP protocol analysis with Wireshark, tcpdump, and Nmap. The course follows the textbook chapter-by-chapter — each module covers two book chapters plus the related hands-on labs, with a midterm capstone wrapping Module 4 and a final capstone wrapping Module 8.

## Course information

| Field            | Detail                                                                |
| :--------------- | :-------------------------------------------------------------------- |
| Course number    | CSIA 210                                                              |
| Course title     | Network Protocol Analysis                                             |
| School / program | Computing and Informatics — Cyber Security / Information Assurance *(per current outline)* |
| Credit hours     | 3                                                                     |
| Contact hours    | Lecture 2, Lab 2                                                      |
| Prerequisites    | NETI 104 *Introduction to Networking* or NETI 109 *Networking I*      |
| Term             | Spring 2026                                                           |
| Outline revision | Fall 2014 (date of last revision Fall 2013)                           |

## Catalog description

> Offers in-depth coverage of all the salient models, protocols, services, and standards that govern TCP/IP and that guide its behavior on modern networks. Specific guidance is given to reinforce the concepts introduced and to help prepare students to interact with TCP/IP on the vast majority of networks in use today. As a hands-on course, students are provided firsthand experience in installing, configuring, analyzing, using, and managing TCP/IP on a network. Included are case projects that pose problems and require creative solutions that should prepare students for the kinds of situations faced on a real, live network.

## What you're supposed to be able to do by the end

1. Develop an understanding of basic IP packet structures.
2. Explore and explain the Data Link and Network Layer protocols — packet / frame types, hardware addresses, and Neighbor Discovery.
3. Analyze routing and routed protocols for both IPv4 and IPv6.
4. Examine ICMP testing and troubleshooting methods, security issues, and ICMP message types and codes.
5. Explain how Neighbor Discovery works on IPv6.
6. Describe various auto-addressing schemes on IPv4 and IPv6 networks.
7. Explain key services that resolve symbolic, human-readable network names into machine-intelligible network addresses.
8. Examine the common and appropriate uses of the TCP and UDP protocols.
9. Describe issues and techniques when IPv4 and IPv6 coexist on the same network.
10. Examine tunneling mechanisms and protocols.
11. Understand, plan, deploy, and use IPv6 on modern TCP/IP networks.
12. Appraise general network security basics with emphasis on IP security topics.
13. Review perimeter security, infrastructure security, and host device security.

## Topical content

Headers · Payloads · ARP · RARP · IPv4 · IPv6 · RIPv1 / v2 · OSPF · EIGRP · BGP · DHCPv4 / v6 · Host and interface address determination · Stateless and stateful autoconfiguration · APIPA · ISATAP · 6to4 · Teredo · OSI model · TCP/IP model · Wireshark · tcpdump · Nmap.

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

Course completed Spring 2026 — counts toward the Cyber Security & Information Assurance Technical Certificate at Ivy Tech Kokomo. Both capstone assessments (midterm and final) passed.

## Related repos

- [Networking-109](https://github.com/jkosber/Networking-109) — CCNA networking foundations, the prereq for this course.
- [CyberOps-115](https://github.com/jkosber/CyberOps-115) — SOC / security-operations work that uses these protocols in anger.
- [IntroToCybersecurity-105](https://github.com/jkosber/IntroToCybersecurity-105) — broader cybersecurity context.
