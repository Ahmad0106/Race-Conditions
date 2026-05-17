#  Race Conditions - PortSwigger Complete Guide

race-conditions-portswigger-guide/

This repository contains a structured and practical breakdown of Race Condition vulnerabilities from PortSwigger Web Security Academy.

It focuses on real-world exploitation patterns, methodology, and defensive strategies used in web security testing and bug bounty research.

---


##  Core Concepts
-  [Introduction](01-introduction.md)
-  [Limit Overrun Race Conditions](02-limit-overrun-race-conditions.md)
-  [Multi-endpoint Race Conditions](03-multi-endpoint-race-conditions.md)
-  [Aligning Race Windows](04-aligning-race-windows.md)

---

##  Exploitation Techniques
-  [Connection Warming](05-connection-warming.md)
-  [Abusing Rate Limits](06-abusing-rate-limits.md)
-  [Single-endpoint Race Conditions](07-single-endpoint-race-conditions.md)
-  [Partial Construction Races](08-partial-construction-races.md)

---

##  Advanced Topics
-  [Time-sensitive Attacks](09-time-sensitive-attacks.md)
-  [Session Locking Mechanisms](10-session-locking.md)

---

##  Defense & Prevention
- [Prevention Strategies](11-prevention.md)

---

##  Practice & Methodology
-  [Examples & Attack Methodology](examples.md)

---

## Methodology

1. Predict potential collision  
2. Probe for clues  
3. Prove the concept  

---

## Learning Goals

- Detect race condition vulnerabilities
- Exploit timing-based security flaws
- Bypass application state logic
- Understand hidden sub-state transitions

---

## ⚠️ Disclaimer

This repository is intended for educational and ethical security research only.
