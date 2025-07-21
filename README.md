# 🔐 Zuhsyn Edubox - Threat Model Report

**Project Role**: Cybersecurity Analyst  
**Prepared by**: Ibrahim Idris  
**Date**: July 21, 2025  
**Report Version**: 1.0.0  

---

## 📌 Project Overview

**Zuhsyn Edubox** is a mobile learning platform built by my team, designed to help students access lessons, take quizzes, and track their learning progress through a gamified experience.

While the development team handled the frontend (React Native) and backend (Django REST Framework), I was responsible for conducting a **comprehensive threat model** to ensure the application is secure before deployment.

---

## 🎯 Objective of This Repository

This repository documents the security assessment and threat modeling work I performed for the Zuhsyn Edubox project.

It includes:

- A full **Threat Model Report** (PDF)
- STRIDE-based threat breakdown
- Identified risks and mitigation strategies
- Recommendations for improving application security

---

## 🔍 What's Inside

| File | Description |
|------|-------------|
| `Zuhsyn_Edubox_Threat_Model_Report.pdf` | Full PDF report including STRIDE threats, risk scenarios, and mitigations |
| `README.md` | This file, describing the project and my contribution |
---

## 🛡️ Key Threat Areas Covered

- **Authentication & Token Handling (JWT)**
- **Insecure API communications**
- **User Data Protection**
- **Leaderboard Tampering & Quiz Forgery**
- **Password Reset Abuse**
- **Recommendations for Secure Storage on Mobile**

---

## 🧠 My Contribution

As the security analyst on this project, I:

- Created a detailed **Threat Model Report** following STRIDE methodology.
- Identified real-world risks (e.g., token theft, quiz manipulation, email abuse).
- Proposed actionable mitigations for the dev team.
- Helped the team align with OWASP and secure development practices.

---

## 🚀 Technologies Involved in the App

Though I did not build the application codebase, understanding the tech stack helped shape my threat analysis:

- **Frontend**: React Native
- **Backend**: Django + Django REST Framework
- **Auth**: JWT (SimpleJWT)
- **Database**: PostgreSQL/MySQL
- **Mobile Storage**: AsyncStorage
- **Email Service**: Gmail SMTP

---

## 📎 Related Links

- [STRIDE Threat Modeling](https://owasp.org/www-community/Threat_Modeling_Process)
- [OWASP Mobile Top 10](https://owasp.org/www-project-mobile-top-10/)
- [Django Security Best Practices](https://cheatsheetseries.owasp.org/cheatsheets/Django_Security_Cheat_Sheet.html)

---

## ✨ About Me

I'm **Ibrahim Idris**, a young cybersecurity analyst passionate about building and securing real-world applications.  
This project is part of my growing portfolio in secure software development, penetration testing, and threat modeling.

> **"Security should not be an afterthought — it should be built into every app from the first line of code."**

---


