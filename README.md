# Security-Learning-Journal
A daily log of my journey into Open Source Security and documentation basics for GSSoC 2026
# 🛡️ My Security & Documentation Journey
Welcome! This is my personal space where I track everything I’m learning as I prepare for **GSSoC 2026**. I’m proof that you don't need a Computer Science degree to make a difference in tech—you just need curiosity and a willingness to help.

---

## 📅 The Learning Log

### Day 1: Laying the Foundation
**Date:** April 6, 2026

- **The Big Idea**: Today was all about "The Why." I realized that security isn't just for hackers; it’s about protecting people's data and making sure open-source projects are built on trust.
- **What I did**: 
  - Set up my GitHub profile to reflect my interest in **Security Awareness**.
  - Researched how non-coders can contribute through **Technical Documentation** and **Trust & Safety** initiatives.
- **Key Takeaway**: A project is only as strong as its weakest link—and often, that link is a lack of clear security guides. I want to be the person who bridges that gap.
- **Current Curiosity**: I keep hearing about the **OWASP Top 10**. I want to find out why it’s considered the "Gold Standard" for web security.
- **Tomorrow's Goal**: Read a beginner-friendly breakdown of the first few OWASP risks.

---
*"One document at a time, making the internet a little safer."*

----

# Security-Learning-Journal-2

---

Day 2 of my journey into Open Source Security and documentation basis of Gssoc 2026
### Day 2: Understanding Broken Access Control (OWASP #1)
**Date:** April 7, 2026

- **The Big Idea**: Today I learned that "Authentication" (proving who you are) is different from "Authorization" (what you are allowed to do). A "Broken Access Control" bug happens when the second part fails.
- **What I Learned**: 
  - **The "URL Trick" (IDOR)**: I found out that sometimes, if you are logged into a site and see `.../profile?id=123` in the address bar, you can simply change the `123` to `124` to see someone else’s private data. This is a classic example of broken access control.
  - **Privilege Escalation**: This is when a regular user finds a way to access the "Admin" panel just by guessing the URL (like adding `/admin` to the end of a website).
- **Non-Coder Impact**: I realized that as a documentation contributor, I can help by checking if "Admin Only" guides are accidentally public, or by helping write clear "Permission Policies" so developers don't miss these checks.
- **Current Curiosity**: If changing a number in a URL is so easy, why don't all websites have this problem? I want to look into "Deny by Default" tomorrow.
- **Tomorrow's Goal**: Learn about "Cryptographic Failures" (OWASP #2)—basically, how secrets get leaked.

---

# I-m-back
catching up my journal - day 3 to 7
### Day 3 - 7: The Catch-Up & Refocus
- **Status**: Had a small break, but I'm back! Open source is a marathon, not a sprint.
- **What I'm doing now**: I'm shifting my focus to the **OWASP Top 10** basics to prepare for the GSSoC project release.
- **Deep Dive**: Today I looked into **Cryptographic Failures** (OWASP #2). This isn't just about "math"; it's about protecting sensitive data like passwords and credit card numbers through encryption.
- **Non-Coder Insight**: I realized that as a documentation contributor, I can help by ensuring projects have a clear "Privacy Policy" section so users know how their data is handled.
- **What I learned**: Phishing is a type of "social engineering" where attackers trick people into giving away sensitive info (like passwords or JEE portal logins) by pretending to be a trusted source.
- **My Reflection**: Security isn't just about high-tech firewalls; it’s also about staying alert and double-checking links before we click. This is a huge part of the "Security Awareness" I want to promote during GSSoC.

---

# security-learning-journal-day-8
**Concept**: Learned about **Cryptographic Failures** (OWASP #2).- **My Perspective**: As a non-coder, I realized that I can contribute by reviewing "Privacy Policy" docs to ensure they clearly explain to users how their data is being "scrambled" and kept safe. - **Progress**: Staying consistent with my learning streak 
### Day 8: Data Privacy & Encryption (OWASP #2)
- **What I learned**: Cryptographic Failures (OWASP #2) happen when sensitive data like passwords or health records aren't "scrambled" (encrypted) properly. 
- **The Non-Coder Fix**: I can help projects by ensuring their documentation clearly states how user data is stored and what privacy measures are in place. 

---

# security-learning-journal-day-9
dangerous inputs
### Day 9: Understanding Injection Risks (OWASP #3)
- **What I learned**: Injection happens when an attacker sends "hidden commands" through a simple input box (like a search bar or login form) to trick the system into giving away data.
- **The Non-Coder Perspective**: I can help by documenting "Input Validation" rules—making sure the project's guides clearly explain what kind of data users should (and shouldn't) be able to type into the system.
- **Goal**: Learning how to spot these "input gaps" in project descriptions.

---
# security-learning-journal-day-10
### Day 10: Insecure Design (OWASP #4)
- **Concept**: Some security issues aren't "bugs" in the code; they are just bad plans. Like building a house with no locks on the windows.
- **My Thought**: As a non-coder, I can help by suggesting better "workflows" (like asking for a password twice) to make sure the design is safe for everyone

---
# security-learning-journal-day-11
### Day 11: Security Misconfiguration (OWASP #5)
- **Concept**: This happens when a system is left with "default" settings (like a password of 'admin123'). It's like leaving the front door wide open.
- **My Role**: I can help projects by creating "Security Checklists" for their documentation to ensure new users change their default settings immediately.

---
# security-learning-journal-day-12
### Day 12: The "Expired Ingredient" Problem (OWASP #6)
- **Concept**: Vulnerable and Outdated Components happen when a project uses old libraries or "packages" that have known security holes. It’s like cooking with expired ingredients—no matter how good the chef is, the food isn't safe.
- **My Role**: As a non-coder, I can help by checking a project's "Dependencies" list and cross-referencing them with security databases to see if they need an update.
- **Perspective**: In open source, keeping everything updated is a massive task. Documentation that tracks these versions is the first line of defense.

---
# security-learning-journal-day-13
### Day 13: Identification and Authentication Failures (OWASP #7)
- **Concept**: This happens when a system doesn't properly confirm who a user is. It’s like a security guard who recognizes your face but forgets to check your ID card. 
- **The Risk**: Attackers can use "Credential Stuffing" (trying thousands of stolen passwords) to break in if the system doesn't have protections like Multi-Factor Authentication (MFA).
- **My Role**: I can help by documenting the importance of "Password Complexity" and "Lockout Policies" in project setup guides.
- **Reflection**: Even a Tier 3 location can't stop me from learning global security standards. One day at a time! 🛡️

---
# security-learning-journal-day-14
### Day 14: Software and Data Integrity Failures (OWASP #8)
- **Concept**: This happens when code or data is updated without verifying if it's from a trusted source. It’s like accepting a package without checking the seal.
- **C++ Connection**: As I plan to learn C++ in college, I’m realizing how important "Memory Safety" and "Integrity" are. Insecure updates can lead to huge vulnerabilities.
- **My Future Goal**: I want to learn how to write secure C++ code that protects the integrity of the whole system.

---
# security-learning-journal-day-15
### Day 15: Major Milestone & Security Logging (OWASP #9)
- **BIG NEWS**: I officially got accepted into **GSSoC 2026** as a Contributor! 🚀 This proves that even as a non-coder, there is a place for me in the Open Source community.
- **Topic**: Security Logging and Monitoring Failures. This is about keeping a "digital diary" of who does what in an app. If you don't log events, you won't know when an attacker breaks in.
- **My Role**: I can help projects by ensuring their documentation explains how to check logs and set up alerts for suspicious activity.
- **Focus**: Celebrating this win while staying 100% focused on my WBJEE preparation!
