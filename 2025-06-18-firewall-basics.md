---
title: "🔥 Firewall Basics – A Beginner's Guide"
date: 2025-06-18
categories: [Cybersecurity, Networking]
tags: [firewall, linux, ufw]
author: Zawad
---

A **firewall** is your system’s first line of defense. In this blog, I explain the different types of firewalls, how they work, and how to set them up in Linux using UFW.

## 🧱 Types of Firewalls

- Packet Filtering
- Stateful Inspection
- Application Layer (Proxy)
- Next-Gen Firewall (NGFW)

## 💻 UFW Example (Linux)

```bash
sudo ufw enable
sudo ufw allow ssh
sudo ufw default deny incoming
sudo ufw status
```

> Firewalls are essential for both SOC Analysts and Penetration Testers. Practice using them on virtual machines or TryHackMe labs.
