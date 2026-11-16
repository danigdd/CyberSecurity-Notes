# Cybersecurity Lab Notes — Networking Essentials

> **Platform:** TryHackMe  
> **Date:** 16-11-2026 
> **Difficulty:** Easy 
> **Category:** Networking
> **Lab Type:** Theory

---

## 01 — Overview

**Objective:**  
What was the main objective of this room?

- Learn the networking essential protocols

**Key Takeaways:**  
What are the 1–3 most important things I learned?

1. How DHCP, ARP and ICMP work and why are they used for
2. How Routing works and different routing protocols
3. What is NAT, PAT and why are they necessary

---

## 02 — Technical Knowledge

*Record the concepts, technologies and tools worth remembering.*

| Concept / Tool | Purpose / Explanation |
|---|---|
|DCHP Protocol|How new devices obtain their network configuration automatically|
|ARP Protocol|How devices search for MAC Addresses within a network|
|ICMP|Troubleshooting networks using IP addresses|

**Key Technical Insight:**  
What do I understand now that I didn't understand before?

- I understand now in detail the DCHP and ARP protocols
- I understand how to troubleshoot networks using ping and traceroute commands
- I understand how routing works and main routing protocols used on the Internet
- I understand why NAT and PAT are necessary and how they can translate private addresses into a single public address using ports.

---

## 03 — Methodology & Reasoning

**Problem:**  
What was I trying to identify, understand or achieve?

- I was trying to understand the networking main concepts and protocols

**Approach:**  
What steps or techniques did I use?

- I did my own research for the concepts.



## 06 — Further Learning

**What do I still need to understand?**

- The core details of DHCP, ARP, ICMP, Routing and NAT

**What should I practise next?**

- Keep learning on TryHackMe

---

## 07 — Completion Review

**Knowledge Assessment:**

- [·] I understand the main concepts.
- [·] I can explain the techniques in my own words.
- [·] I understand why the tools and commands were used.
- [·] I could apply this knowledge in a different environment.

**Confidence Level:**

- [ ] Beginner — I need more practice.
- [·] Intermediate — I understand it but need guidance.
- [ ] Confident — I can apply it independently.

**Overall Lesson:**  
What is the single most valuable thing I will take away from this room?

- Now I can understand the different main networking protocols and what are they used for

---

## 08 — Technical Findings (Optional)

ping ip -c (how many times)
traceroute dns_name/ip

ping tipically sends 56 bytes along the ICMP and IP headers (84 total)
there can be private and public routers on the routing process (which we can study with traceroute)

