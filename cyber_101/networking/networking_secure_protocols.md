# Cybersecurity Lab Notes — [ROOM NAME]

> **Platform:** TryHackMe  
> **Date:** 2026-23-11
> **Difficulty:** Easy
> **Category:** Networking
> **Lab Type:** Theory

---

## 01 — Overview

**Objective:**  
What was the main objective of this room?

- Learning how to secure the previous protocols

**Key Takeaways:**  
What are the 1–3 most important things I learned?

1. TLS is a on-top protocol that secures our previous protocols
2. By using TLS, we can obtain HTTPS, SMTPS, POP3S, IMAPS, SSH, SFTP and FTPS and VPN connections
3. SFTP (Secure shell) and FTPS (FTP Secure, TLS) are NOT the same

---

## 02 — Technical Knowledge

*Record the concepts, technologies and tools worth remembering.*

| Concept / Tool | Purpose / Explanation |
|---|---|
|TLS|Layer of encrypted security|
|HTTPS, TCP 443|Secure version of HTTP|
|SMTPS|Port 465|
|POP3S|Port 995|
|IMAPS|Port 993|
|SSH, secure remote connection| Port 22 (instead of telnet 23)|
|SFTP, FTP using SSH||Port 22|
|FTPS, FTP over TLS||Port 990|
|VPN||Virtual private tunnels|


**Key Technical Insight:**  
What do I understand now that I didn't understand before?

- How to secure non-secure protocols and how we can inspect encrypted packets on wireshark with public encryption keys

---

---

## 07 — Completion Review

**Knowledge Assessment:**

- [·] I understand the main concepts.
- [·] I can explain the techniques in my own words.
- [·] I understand why the tools and commands were used.
- [·] I could apply this knowledge in a different environment.

**Confidence Level:**

- [·] Beginner — I need more practice.
- [ ] Intermediate — I understand it but need guidance.
- [ ] Confident — I can apply it independently.

---

