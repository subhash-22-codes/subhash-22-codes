# Subhash Yaganti

Full Stack Engineer with a strong backend focus, building SaaS-grade systems that prioritize security, scalability, and real user experience.

I enjoy designing authentication systems, background workflows, and data pipelines, then connecting them cleanly to the frontend and polishing the UI/UX so the product feels intuitive and useful — not just functional.

---

## About Me

I am a final-year B.Tech student at Malla Reddy College of Engineering & Technology, actively building production-style applications rather than academic demos.

My core interest lies in **backend systems and security**, especially authentication flows, background job processing, and database design. At the same time, I care deeply about how users experience a product — from first load to edge cases — and I invest time in UI/UX refinement after the system logic is solid.

I prefer working close to real-world constraints:

* explicit auth boundaries
* async processing instead of blocking flows
* predictable data models
* deployable systems that don’t break under usage

---

## What I’m Building Now

### **DataPulse — SaaS Data Ingestion & Analytics Platform (Flagship Project)**

DataPulse is an actively developed **SaaS-grade data ingestion, processing, and analytics platform** designed for real operational use, not demos.

The goal of DataPulse is simple but demanding:
**make data workflows secure, asynchronous, and genuinely useful to users.**

Instead of focusing only on “making it work,” the system is built around how users interact with data — upload time, processing feedback, UI responsiveness, and clarity of insights.

#### What DataPulse Does

* Allows authenticated users to upload structured datasets (CSV)
* Processes data asynchronously using background workers
* Stores and serves processed results efficiently
* Visualizes insights using production-grade charts
* Maintains UI responsiveness even during heavy workloads

#### System Design Focus

**Authentication & Security**

* JWT-based access and refresh token flows
* Google OAuth and GitHub OAuth integration
* Secure account linking between OAuth and email-based accounts
* Shared authentication logic across HTTP APIs and WebSockets
* Strong separation of auth, session, and user identity layers

**Background Processing**

* Celery + Redis for long-running data tasks
* Non-blocking uploads and processing
* Clear task lifecycle handling and failure recovery

**Database & Data Layer**

* PostgreSQL with well-defined schemas
* Safe session management to avoid connection leaks
* Predictable query patterns for analytics workloads

**Frontend & UX**

* React + TypeScript with strict typing
* Enterprise-style data visualization using Apache ECharts
* Mobile-first responsive UI
* UX decisions driven by real user interaction, not just technical convenience

**Deployment**

* Fully containerized backend setup
* Frontend deployed on Vercel
* Environment-based configuration for development and production
* Production-ready build and deployment workflows

**Status:** Actively under development. The platform is evolving toward a full multi-tenant SaaS architecture.

* Live: [https://data-pulse-eight.vercel.app](https://data-pulse-eight.vercel.app)
* Repository: [https://github.com/subhash-22-codes](https://github.com/subhash-22-codes)

---

## What I Know (How I Actually Use My Skills)

### Backend & Systems

* Design REST and WebSocket APIs using FastAPI and Flask
* Build secure authentication systems (JWT, OAuth, account linking)
* Implement background job pipelines using Celery and Redis
* Design relational schemas and manage database sessions safely
* Think in terms of system boundaries, failure modes, and scalability

### Frontend

* Build type-safe React applications with clear state flow
* Integrate frontend cleanly with backend APIs
* Implement auth-aware rendering and protected routes
* Polish UI/UX after core system logic is stable

### Data & Visualization

* Work with structured datasets and analytics workflows
* Build interactive dashboards using Apache ECharts and Chart.js
* Optimize charts for usability, clarity, and performance

### Dev, Deployment & Production

* Docker-based local and production deployments
* Environment-based configuration (dev / staging / prod)
* CI-friendly build setups
* Vercel-based frontend deployments
* Comfortable taking a project from local development to live production

---

## Other Notable Work

### **Justice Genie 2.0 — AI-Driven Legal Assistance Platform**

Justice Genie 2.0 bridges the gap between complex legal systems and everyday users by providing AI-powered legal guidance without requiring immediate lawyer consultation.

The platform focuses on **legal awareness, accessibility, and empowerment**, particularly for Indian law.

#### What Justice Genie Does

* Provides instant AI-based legal explanations
* References Indian IPC sections and legal documents
* Estimates win/loss probability for legal scenarios
* Enables interactive, case-based legal learning

#### Key Capabilities

* AI-powered legal assistant using Google Gemini API
* Voice-to-text and text-to-speech support
* Multilingual legal queries
* Win/Loss probability analysis with visual charts
* Chat history export as PDF
* Access to IPC and Indian law documents
* Case-based legal quizzes for learning
* Secure authentication using OTP and hashing
* Fully responsive UI across mobile, tablet, and desktop

#### My Contributions

* Designed and implemented backend APIs using Flask
* Managed database interactions using MongoDB
* Integrated AI workflows and prompt engineering
* Built complete frontend-to-backend data flow
* Designed UI/UX with accessibility and clarity in mind
* Managed deployment and continuous iteration

**Tech Stack:**
React, Tailwind CSS, Flask, MongoDB, Google Gemini API, Chart.js

**Live:** [https://justice-genie-mu.vercel.app/](https://justice-genie-mu.vercel.app/)

---

### MemeGame

A real-time multiplayer web game built to explore WebSockets, real-time state synchronization, and interactive UI flows.

---

## How I Think About Engineering

* Prefer correctness over shortcuts
* Avoid blocking operations in user-facing flows
* Design systems assuming real users and real load
* Treat authentication and data boundaries seriously
* Build products to be **useful**, not just impressive

---

## What I’m Aiming For

I’m currently deepening my focus on:

* backend architecture
* authentication and security systems
* SaaS platform engineering
* building products users genuinely enjoy using

---

## Contact & Profiles

* GitHub: [https://github.com/subhash-22-codes](https://github.com/subhash-22-codes)
* LinkedIn: [https://www.linkedin.com/in/subhash-yaganti-a8b3b626a/](https://www.linkedin.com/in/subhash-yaganti-a8b3b626a/)
* Email: [subashyagantisubbu@gmail.com](mailto:subashyagantisubbu@gmail.com)

---

## Final Note

This README reflects how I actually work and think as an engineer.
DataPulse represents my strongest work and ongoing growth in building production-grade SaaS systems.
