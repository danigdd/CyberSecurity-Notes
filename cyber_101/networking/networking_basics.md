# Cybersecurity Lab Notes — Networking Concepts

> **Platform:** TryHackMe  
> **Date:** 16-11-2016
> **Difficulty:** Easy
> **Category:** Networking
> **Lab Type:** Theory

---

## 01 — Overview

**Objective:**  
What was the main objective of this room?

- The objective of this room was to learn in detail the OSI Model, the TCP/IP Model, IP Addresses and Subnets, UDP  and TCP, encapsulation concepts and a practical scenario with telnet.

**Key Takeaways:**  
What are the 1–3 most important things I learned?

1. The whole internet uses a convention called the OSI Model (Open Systems Intercommunication Model) for networking operations.
2. We have different transport models, the most important ones are TCP and UDP
3. The way a packet is created and transported is really complex, going through different stages: we start with the data itself, add the transportation method, then adding an IP Header and finally encapsulating it within a frame (adding the ethernet or wifi header).

---

## 02 — Technical Knowledge

*Record the concepts, technologies and tools worth remembering.*

| Concept / Tool | Purpose / Explanation |
|---|---|
|OSI Model| A convention for how communications should occur in a network |
|TCP/IP Model| An implemented model for how TCP connections work|
|IP Addresses and Subnets| Private or public identifiers for devices in a network|
| UCP and TCP| Two different transport protocols with its own advantages and disadvantages|
| Encapsulation| Process which describes how the data should be presented before sending it over|

**Key Technical Insight:**  
What do I understand now that I didn't understand before?

- Now I understand that the TCP/IP model is an implemented model for the OSI Model convention and can combine different layers into one.

- I understand now the subnet concept. If we have an IP address `192.168.32.3` and a subnet `255.255.255.0`, it indicaters to us that the 24 left-most bits of the IP address identify the network, and the remaining bits are exclusive to a specific device.

- I did understand the differences between UDP and TCP, but now I can understand why they can only support approximately 65.000 different ports each one.

- I have a clearer understanding of the encapsulation process, how the data we want to send over is attached to a TCP/UDP Header, along an IP Header and finally a Wifi/Ethernet header, combining it all within a frame. Basically, a packet contains the IP Address and the data and how it should be sent, and whenever we add the data link layer we obtain a Frame that encapsulates everything.

- Now I understand how to use the telnet command and what are its uses. We can use a TCP connection to connect to a remote machine (in a plain manner, not a secure manner like SSH). The syntax is `telnet IP PORT`.
---

## 03 — Methodology & Reasoning

**Problem:**  
What was I trying to identify, understand or achieve?
I was trying to understand different networking concepts such as TCP/IP model, TCP and UDP connections, IP addresses and packet encapsulation.
- 

**Approach:**  
What steps or techniques did I use?

I was just studying and grasping the concepts with my own research.

**Key Finding:**  
What information or evidence helped me move forward?

- For encapsulation, the analogy of wanting to send a letter with its final destination (the data and the IP header) and enveloping it (the frame).
- For subnetting, identyfing that the 255 bytes identify which bytes are "switched on" for our IP address, i.e. , which bits or bytes identify the network address.

**Lessons Learned:**  
What mistake, obstacle or misunderstanding did I encounter?

- Not understanding the previous concepts at it's core.

---


## 06 — Further Learning

**What do I still need to understand?**

- I need to learn at its core all these protocols and models.

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

- There are a lot of different models, protocols and processes that are crucial for our everyday network communications.

---

## 08 — Technical Findings (Optional)

- telnet IP_address PORT
