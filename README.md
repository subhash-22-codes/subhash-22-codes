# Subhash Yaganti

Final-year Computer Science student focused on building **secure, asynchronous, backend-heavy systems** with a strong focus on authentication, background processing, and data evolution.

I enjoy working on the parts of systems that usually fail first—auth flows, async jobs, schema changes—and then connecting them cleanly to the frontend.

---

## About Me

I’m a final-year B.Tech student at Malla Reddy College of Engineering & Technology (graduating 2026).

Instead of small demo apps, I focus on **end-to-end systems** that deal with real constraints:

* authentication edge cases
* background workloads
* evolving schemas
* deployment limitations

I design with the assumption that **data will change, users will do unexpected things, and systems must recover cleanly**.
My goal is not to eliminate failures, but to build systems that fail predictably and recover cleanly.

---

## Skills & Technologies

**Backend**

* Python, Flask, FastAPI
* REST APIs, WebSockets
* JWT authentication (Access & Refresh Tokens)
* OAuth (Google, GitHub)
* Background processing with **Celery**
* Task coordination using **Redis**
* PostgreSQL schema design

**Frontend**

* React
* TypeScript, JavaScript
* Auth-aware UI flows
* Data visualization with **Recharts**

**Infra / Deployment**

* **Docker** (local services & orchestration)
* Supabase (managed PostgreSQL)
* Vercel (frontend deployment)

---

## What I’m Building Now

## **DataPulse — Real-time Data and Schema Monitoring System**

DataPulse monitors **how data and schemas change over time**.

It focuses on detecting:

* schema drift
* structural changes
* metric shifts
* smart alerts

across recurring datasets and live data sources.

The project treats **data stability as a first-class concern**, moving beyond the static datasets common in academic projects.

---

### Key Capabilities

* Monitor recurring CSV uploads (daily / monthly)
* Securely connect to **external PostgreSQL and MySQL databases** (read-only)
* Track schema and structural changes over time
* Ingest data from open and secured APIs
* Asynchronous processing so the UI never blocks
* Email alerts for detected changes

---

### Tech Notes (High Level)

* Background execution handled via **Celery + Redis**
* Auth implemented using JWT(Refresh token and Access token) and OAuth(Google/Github)
* Frontend built with React + TypeScript
* Local services containerized with Docker
* Deployed with cloud-aware constraints in mind

---

**Live:** [https://data-pulse-eight.vercel.app](https://data-pulse-eight.vercel.app)

---

## Other Projects

### **Justice Genie**

AI-assisted legal information tool focused on **Indian law awareness**.

Provides guided explanations and outcome tendency indicators based on user-provided scenarios.
Built as an **assistive system**, not a predictive engine.

* Backend APIs: Flask
* Database: MongoDB
* Frontend: React
* Deployment: Vercel

**Live:** [https://justice-genie-mu.vercel.app/](https://justice-genie-mu.vercel.app/)

---

### MemeGame

Real-time multiplayer web game built to explore:

* WebSockets
* shared state
* live UI updates

---

## How I Think About Engineering

* Async > blocking
* Secure by default, not patched later
* Schema changes are inevitable—systems should expect them
* If it only works locally, it doesn’t really work

---

## Contact

* GitHub: [https://github.com/subhash-22-codes](https://github.com/subhash-22-codes)
* LinkedIn: [https://www.linkedin.com/in/subhash-yaganti-a8b3b626a/](https://www.linkedin.com/in/subhash-yaganti-a8b3b626a/)
* Email: [subashyagantisubbu@gmail.com](mailto:subashyagantisubbu@gmail.com)

---

## Final Note

I’m still a student, but I intentionally build systems with **real failure modes and real constraints** in mind.

DataPulse is my strongest example of that approach.
