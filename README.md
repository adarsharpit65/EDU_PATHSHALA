# EDU_PATHSHALA
PATHSHALA— A modern web platform connecting learners and tutors. Features animated UI, role-based signup (Learner/Tutor/Both), file uploads, dropdowns, and a responsive dashboard for collaborative learning and progress tracking. 🚀

# PATHSHALA — Collaborative Tutor-Learner Platform

## Project Description
PeerLearn is a front-end prototype for a collaborative learning platform that connects learners and tutors. It supports role-based signups (Learner, Tutor, Both), profile & certificate uploads, tutor matching, a study-chatbot, simulated 1-on-1 call flow, and subscription plan UI. The project is built as a modular web app (HTML/CSS/JS) and is ready to be extended with a backend, database, and real-time services.

---

## Problem Statement
Students often struggle to find the right tutor matching their strengths, weaknesses, schedule and budget. Tutors lack a simple platform to showcase qualifications, verify credentials, and accept session requests. Existing systems can be fragmented and non-personalized.

---

## Solution Approach
PeerLearn addresses these problems by:
- Providing role-specific sign-up flows (Learner, Tutor, Both) with dropdowns and file uploads for profile & verification.
- Displaying a clean dashboard with study streaks, personalized goals, and progress visualization.
- Implementing a lightweight AI-like chatbot (rule-based) to identify weak subjects and recommend tutors.
- Offering a simulated 1-on-1 call request flow and a subscription purchase flow (demo).
- Enabling front-end tutor matching by subject and rating, and a visual, animated UI to improve usability.

This repository contains a complete front-end reference implementation. Backend integration for real matching, payments, and video calls can be added later.

---

## Technology Stack
- **Frontend:** HTML, CSS, JavaScript (vanilla)
- **Optional Backend (recommended for production):** Node.js + Express
- **Optional Database:** MongoDB / Firebase
- **Optional Payment Integration:** Stripe (for subscriptions)
- **Optional AI Chatbot:** OpenAI / other LLM APIs (requires backend)

---

## Project Structure
PATHSHALA/ (root)
├─ assets/
│ ├─ css/
│ ├─ js/
│ └─ img/
├─ learner/
│ └─ signup.html
├─ tutor/
│ └─ signup.html
├─ both/
│ └─ signup.html
├─ dashboard/
│ └─ dashboard.html
└─ index.html
(Optional) Install Live Server in VS Code for a smooth local preview, or use any static server.

Open index.html in your browser or run Live Server:

In VS Code: right-click index.html → Open with Live Server

Navigate and test:

index.html → role selection

learner/signup.html, tutor/signup.html, both/signup.html → signups

dashboard/dashboard.html → demo dashboard with chatbot, tutor list, call & subscription modals

Team Members

ADARSH KUMAR — Frontend 

SANNY RAI — PPT

AYUSH RAJ — UI/UX
