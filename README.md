# SSH Bruteforcer (Made for educational purposes only please do not misuse)

© SSH Bruteforcer

---
## Members:

### 24BCY10159 - Bhoomik Khetwani
### 24BCY10297 - Dixant Paptwan
### 24BCY10119 - Vagesh Sharma
### 24BCY10146 - Piyus Kumar Swain
### 24BCY10324 - Anshul
---

---

## Disclaimer

This tool is developed **strictly for educational and research purposes** as part of a cybersecurity coursework project.  
It must **only** be used against systems you **own** or have **explicit written permission** to test.  

Unauthorized usage against external systems may be **illegal** and could result in **criminal charges**.  
Use responsibly and ethically.

---

## Overview

This project is a simple SSH brute-forcing script built in Python.  
It demonstrates how attackers might attempt to guess credentials by automating SSH login attempts.  

The project helps students understand:
- Risks of weak credentials.
- How brute force attacks operate.
- Why implementing secure authentication (e.g., SSH keys, fail2ban, lockouts) is critical.

---

## Features

- Supports **three attack modes**:
  1. **Wordlist mode** – same list used for both usernames and passwords.
  2. **Separated lists mode** – independent user list and password list.
  3. **User:Pass combo list** – credentials provided in `username:password` format.

- Adjustable **timeout** between attempts (default 0.1–2 seconds).  
- Optional **verbose mode** to print failed attempts.  
- Tracks number of attempts and failures.  

---

## Requirements

- Python 3.8+
- `pexpect` library  

Install dependencies:

```bash
pip install -r requirements.txt
```

### NOTE:
**_Please Note, More cahanges are yet to be made, more features are yet to be added_**
