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

---
# security-learning-journal-day-16
### Day 16: Intro to SSRF (OWASP #10)
- **Concept**: Server-Side Request Forgery (SSRF) happens when an attacker tricks a server into making a request to a place it shouldn't go (like its own internal files).
- **The "Human" Version**: It's like tricking a delivery driver into entering the restricted back-office of a building instead of just dropping the package at the front desk.
- **My Plan**: I've noted this as a high-level topic. I will dive deeper into the technical "how-to" after my competitive exams are over!

---
# security-learning-journal-day-17
### Day 17: Discipline & The Road Ahead 🚀
- **Status**: Focusing hard on WBJEE revision. 
- **Reflections**: Learning that "consistency" is the most important skill for an engineer. Whether it's solving Math puzzles or maintaining this journal, showing up every day is what counts.
- **Mental Health**: Taking small breaks to celebrate my GSSoC selection. It’s a reminder that hard work pays off, even when the journey feels long.

---
# security-learning-journal-day-18
### Day 18: The Digital "Security Camera" (Logging & Monitoring)
- **Concept**: Security Logging (OWASP #9) is about keeping a record of everything that happens in an app. If a "hacker" tries to log in 100 times, the log should catch it.
- **Why it matters**: Without logs, an attacker could be inside a system for weeks and nobody would know. 
- **Non-Coder Role**: I can help projects by documenting how users should report suspicious activity and ensuring the "Admin Guides" explain how to check logs.
- **June Goal**: I plan to check multiple GSSoC projects to see if they have clear "Reporting" instructions! 🛡️

---
# security-learning-journal-day-19
### Day 19: Social Engineering — The Human Firewall
- **The Concept**: Social Engineering is the art of manipulating people into giving up confidential info. It's often easier to trick a human than to break a 128-bit encryption.
- **Why it matters**: A project can have perfect code, but if a contributor is tricked into sharing their password, the whole project is at risk.
- **My Role**: As a Security Awareness focused contributor, I want to help projects create "Contributor Safety Guides" to prevent these kinds of human-targeted attacks.
- **Reflection**: Learning GitHub etiquette is also a form of "Social" skill—knowing how to talk to maintainers professionally is key!

---
# security-learning-journal-day-20
### Day 20: Security and Human Logic 🛡️
- **Topic**: Social Engineering & Awareness.
- **The Concept**: Realized that the "weakest link" in any security system is often human error, not code. Attackers use trickery (Phishing, Pretexting) to get what they want.
- **My Mission**: As a GSSoC contributor, I want to focus on making "Human-Centric" documentation that helps people stay alert.
- **Study Update**: Trigonometry is in full swing! Linking mathematical patterns to security patterns. Flow state: Active. 🧠

---
# security-learning-journal-day-21
### Day 21: Personal Security & Boundary Setting 🛡️
- **Learning**: Realized that "Social Engineering" isn't just a tech concept—it's a real-world risk. Predators use psychological manipulation to bypass our personal "firewalls."
- **Key Takeaway**: Trusting your gut is the most important security tool. If someone is faking their behavior or pushing your boundaries (like staying up too late), it's a sign of a "security breach."
- **Action**: Successfully identified a risk, sanitized my data (deleted texts), and blocked the threat. 
- **Focus**: Reclaiming my time and my sleep for my WBJEE goals. My peace of mind is my priority

---
# security-learning-journal-day-22
### Day 22: The Power of Information & Mentorship 🌐
- **Observation**: Realized that many students, even in 2nd year of college, aren't aware of global opportunities like Google STEP or GSoC. 
- **My Advantage**: Starting early (pre-college) gives me the "Time Advantage." I’m building my roadmap now so I can be ready when the doors open.
- **Goal**: I want to not only contribute code/docs but also help bridge this "Information Gap" for others in my community.
- **Status**: Balancing WBJEE Trigonometry and GSSoC networking. One step at a time!

---
# security-learning-journal-day-23
### Day 23: The Impact of Early Awareness 🚀
- **Reflection**: Had an amazing conversation with a 2nd-year B.Tech student today. I realized that my "Pre-College" start is a huge advantage. 
- **Observation**: Many students only start exploring GitHub and global internships in their 2nd year. By starting now, I am building a foundation that puts me years ahead.
- **My Mission**: Stay curious, stay humble, and keep sharing knowledge. Helping others grow is a key part of the Open Source spirit!
- **Status**: Feeling motivated! Back to the Math puzzles with fresh energy. 🧠✨

---
# security-learning-journal-day-24
### Day 24: The Power of the "Early Start" 📈
- **Observation**: Noticed that most GSSoC participants are already in 2nd or 3rd year of B.Tech. Being a pre-college contributor feels unique and a bit like being a "pioneer."
- **Niche Focus**: While others are focusing on college credits, I'm focusing on building a "Security Mindset" from scratch. 
- **Growth**: Realized that being the youngest in the room isn't a weakness; it's a chance to learn from everyone while having the most time to grow.
- **Status**: Back to Trigonometry puzzles. Building the mathematical logic I'll need for C++ in a few months! 🛡️

---
# security-learning-journal-day-25
### Day 25: Access Control & The "Early Bird" Path 🛡️
- **The Concept**: Broken Access Control (OWASP #1) is when a system fails to restrict what a user can do. It allows users to "bypass" permissions to reach sensitive data.
- **My Reflection**: I’m realizing that in my career, I’ve "bypassed" the typical timeline. While most start in 2nd or 3rd year, I’ve accessed the Open Source world pre-college. 
- **The Goal**: As a non-coder, I want to audit project documentation to ensure "Permission Levels" are clearly explained so users don't accidentally cause security leaks.
- **Status**: Trigonometry is getting tougher, but so is my resolve! 🧠✨

---
# security-learning-journal-day-26
### Day 25: Building Career Momentum 🚀
- **Observation**: Realized that 70% of students start their technical journey in their 3rd year out of necessity. By starting now, I'm building "Inertia"—it's easier to keep moving than to start from zero later.
- **Physics Connection**: Just like in mechanics, the work I'm doing now (Pre-College) is my "Potential Energy" that will turn into "Kinetic Energy" (internships/GSoC) in the future.
- **Status**: Focusing on Physics revision for WBJEE. Keeping my GitHub streak alive with just 5 mins of reflection daily. 🛡️

---
# security-learning-journal-day-27
### Day 27: Defining My Own Pace 🛡️
- **Reflection**: Received advice today to "slow down" and wait for college to start my journey. I realized that "starting early" isn't about rushing—it's about having the luxury of time to learn deeply and calmly.
- **My Philosophy**: In Open Source, there is no "too early." By building my foundation now, I am ensuring that my college years are spent exploring high-level research rather than panicking over basics.
- **Status**: Physics revision in progress. Applying the logic of "Inertia"—it's easier to maintain momentum than to start from rest. 🚀

---
# security-learning-journal-day-28
###Day 28: Patterns, Math, and Security 🔐
- **The Concept**: Today I realized that Trigonometry and Physics aren't just for exams—they are the language of patterns. In Cybersecurity, "Cryptography" relies on these same complex mathematical patterns to keep data safe.
- **Reflection**: Sometimes the hardest chapters (like Trig!) are the most rewarding because they train the brain to see through "noise" to find the solution. This is exactly what a Security Analyst does.
- **Status**: Tackling Trigonometric transformations today.
- **Mindset**: Even when I feel alone in my room, I am not standing still. Every problem solved is a "commit" to my future self. 🛡️✨





