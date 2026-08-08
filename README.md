# AISec: AI-Powered Network Guardian

##### Your network's 24/7 threat detective — automatically catches attacks before they damage anything.

> [!CAUTION]
> The project is still an ongoing process.
>
> Please be aware that the source code will then be published when the Software has been polished.
>
> I expect the first release in Q3-Q4 in 2027

---

Imagine your business has a security system with cameras, motion detectors, and an alarm. AISec is like that, but for your computer network.

  #### The Problem It Solves

  Every day, bad actors try to break into computer networks:
  - Hackers trying to steal data
  - Malware attempting to infect systems
  - Botnets trying to use your devices for attacks
  - Data thieves looking for passwords and sensitive information

  Traditional firewalls are like a locked front door—they stop some intruders, but determined attackers find other way's in (like through a window). That's where Firewalls and WAF applications fail.

---

  #### How AISec Works

  Think of AISec as a smart security guard that watches all network traffic 24/7:

  *Layer 1: Recognition*

  Like a security guard checking a visitor's ID against a known list of criminals, AISec checks incoming traffic against:
  - Known attack signatures
  - Blacklists of malicious domains
  - Known bad actors

  **Result:** ~70% of attacks are blocked instantly.

  *Layer 2: Learning & Detecting Anomalies*

  The remaining traffic gets analyzed by ML (machine learning) that learns what *"normal"* looks like:
  - Normal: Employee browsing the web, accessing company servers, checking email
  - Abnormal: A computer suddenly sending massive amounts of data at 3am, or connecting to a known criminal server

  **Result:** ~5% more attacks caught by unusual behavior patterns.

  *Layer 3: Pattern Recognition*

  When multiple alerts happen together, AISec connects the dots:
  - "This IP tried 100 failed password attempts, then suddenly accessed the admin panel"
  - "Three different devices are all connecting to the same malicious server"

  **Result:** Confidence scoring—AISec becomes more certain the threat is real.

  *Layer 4: Automatic Response*

  When AISec is confident about a threat, it automatically:
  - Blocks the attacker's IP at the firewall (similar to banning someone from a building)
  - Stops the malicious traffic before it reaches your systems
  - Logs what happened for review by security staff

---
  
  **Real-World Example**
```
  Tuesday, 10am:
  ├─ Attacker tries to exploit a web server vulnerability
  │  └─ AISec recognizes known attack pattern → BLOCKED
  │
  Wednesday, 2am:
  ├─ Malware on infected computer tries to contact command center
  │  ├─ Destination is on "known bad domains" list
  │  └─ AISec recognizes malicious traffic → BLOCKED IP
  │
  Thursday, 11pm:
  ├─ Insider threat: Employee downloads customer database
  │  ├─ AI detects: Normal = 2GB/week, Abnormal = 50GB in 1 hour
  │  ├─ AISec alerts security team
  │  └─ Team reviews and manually blocks the access
  │
  Saturday, 1am:
  ├─ Insider threat: Infected Employee System downloads customer database
  │  ├─ AI detects: Normal = 0GB/weekend, Abnormal = -1MB/1MB+ in 1 min
  │  ├─ AISec recognizes malicious traffic → BLOCKED IP
  │  └─ AISec alerts security team
  │
  
```
---

  **Three Versions are on the roadmap:**

  - Community Edition (Free)
  - Business Edition (Paid/Subscription based)
  - Enterprise Edition (Paid/SaaS Suscription based)

---

  **Key Benefits**

  - ✅ Stops Attacks Automatically — No human needed to block threats
  - ✅ Learns Over Time — Gets smarter at detecting new attack patterns
  - ✅ Works with Your Firewall — No need to replace existing equipment (TP-Link Omada, Ubiquity Unify, Cisco Meraki, pfSense (OPNSense), VyOS, Mikrotik etc.)
  - ✅ Sees Everything — Monitors all network traffic in real-time
  - ✅ Affordable —  Community Edition (free, open source!)
  - ✅ Transparent — You can see exactly what threats were detected
  - ✅ Replaces IDS/IPS on your Firewall

---

  **What You're Protected From**

```
  ┌─────────────────────┬───────────────────────────────────────────────────────────────────────┐
  │       Threat        │                          How AISec Stops It                           │
  ├─────────────────────┼───────────────────────────────────────────────────────────────────────┤
  │ Known malware       │ Recognizes malicious IPs/domains from blocklists                      │
  ├─────────────────────┼───────────────────────────────────────────────────────────────────────┤
  │ Hacking attempts    │ Detects attack signatures (attempted exploits)                        │
  ├─────────────────────┼───────────────────────────────────────────────────────────────────────┤
  │ Data theft          │ Catches unusual data transfers (employee downloading entire database) │
  ├─────────────────────┼───────────────────────────────────────────────────────────────────────┤
  │ Ransomware          │ Blocks command-and-control communication                              │
  ├─────────────────────┼───────────────────────────────────────────────────────────────────────┤
  │ Botnet infection    │ Stops infected device from contacting attacker's server               │
  ├─────────────────────┼───────────────────────────────────────────────────────────────────────┤
  │ Credential stuffing │ Detects rapid login attempts from suspicious IPs                      │
  └─────────────────────┴───────────────────────────────────────────────────────────────────────┘
```
---

  **Simple Analogy**

  Traditional Firewall = Locked front door (blocks obvious intruders)

  AISec = Security guard + locked door (recognizes attackers, spots unusual behavior, and throws out threats before they cause damage)

  ---
  **TLDR:** AISec is automated threat detection that watches your network 24/7, recognizes attacks (both known and
  unusual), and automatically blocks bad actors—like having a paranoid security expert watching everything, all the time,
  for free as in the Community Edition.
