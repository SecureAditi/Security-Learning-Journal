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
