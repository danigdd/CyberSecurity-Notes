# Cybersecurity Lab Notes — Networking Core Protocols

> **Platform:** TryHackMe  
> **Date:** 2026-11-23 
> **Difficulty:** Easy
> **Category:** Networking  
> **Lab Type:** Theory

---

## 01 — Overview

**Objective:**  
What was the main objective of this room?

- To learn the main networking protocols that we use daily on the internet: DNS, HTTP(S), FTP, SMTP, POP3, IMAP

**Key Takeaways:**  
What are the 1–3 most important things I learned?

1. The daily operations we do are ruled by a set of protocols as retrieving html files from the internet, sending an email or resolving a hostname.

---

## 02 — Technical Knowledge

*Record the concepts, technologies and tools worth remembering.*

| Concept / Tool | Purpose / Explanation |
|---|---|
|DNS, UDP 53|Resolving domains|
|HTTP, TCP 80|Retrieving web html data|
|FTP, TCP 21|Transfering files|
|SMTP, TCP 25||Sending emails|
|POP3, TCP 110||Retrieving emails|
|IMAP, TCP 143||Synchronizing Email|

**Key Technical Insight:**  
What do I understand now that I didn't understand before?

- Different DNS records: A (translating domains into Ipv4), AAAA, (same but for Ipv6), CNAME (for mapping a domain name into another one), MX (mail exchange).

- HTTP is used for accessing the internet. Its main commands are GET, POST, PUT, DELETE. Ex. GET / HTTP/1.1

- FTP is used for file transfering between to servers. USER, PASS, RETR (download), STORE (upload)

- SMTP is a protocol used for sending emails. Useful commands are HELO, MAIL FROM, RCPT TO, DATA (. FOR FINALIZING), QUIT

-POP3 is for receicing emails. Useful commands: STAT, LIST, RETR (ID), QUIT

- IMAP is for synchronizing emails across different servers
---




## 05 — Practical Reference

*Complete when relevant. Keep commands and procedures reusable.*

**Commands / Syntax:**

```bash
nslookup webpage
```

**Purpose:**  
- Retrieving an IP address along other information from a webpage

**Commands / Syntax:**

```bash
ftp ip_machine
```

**Purpose:**  
- Establishing a ftp connection for retrieving or uploading files. Commands such as ls are useful

**Commands / Syntax:**

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

**Overall Lesson:**  
What is the single most valuable thing I will take away from this room?

- There is a vast amount of protocols and ports to remember, but they are assential and rule the everyday internet communications

---


