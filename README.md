# Subhash Yaganti

    (•_•)
    <| |>
     / \   > design, ship, debug

Full-stack developer with a strong preference for backend work.
I build systems around authentication, async processing, and data that changes over time.

---

## About

Final-year Computer Science undergraduate (B.Tech, graduating 2026).

I focus on building real projects end to end, from backend logic and APIs to frontend integration and deployment. 
Most of my work comes from learning by shipping and maintaining systems rather than stopping at demos.

More details and projects: https://subhashportfolio-y.netlify.app/

---

## Skills & Technologies

### Backend
`Python` • `FastAPI` • `Flask`  
`REST` • `WebSockets`  
`JWT (access + refresh + rotation)` • `OAuth (Google/GitHub)`  
`Celery` • `Redis`

### Data / Storage
`PostgreSQL (migrations, evolving schemas)`  
`MongoDB Atlas`

### Frontend
`React` • `TypeScript`  
`Auth-aware state`  
`Recharts`

### Infra / Deployment
`Docker`  
`Render (backend)`  
`Vercel (frontend)`  
`GitHub Actions`  
`Supabase (managed Postgres)`

---

### Same stack, visual grid

Backend → `Python | FastAPI | Flask | REST | WebSockets | JWT | OAuth | Celery | Redis`  
Data → `PostgreSQL | MongoDB Atlas`  
Frontend → `React | TypeScript | Recharts`  
Infra → `Docker | Render | Vercel | GitHub Actions | Supabase`

---

## DataPulse — Real-Time Data & Schema Monitoring

<sub><em>Timeline: July 2025 to Present</em></sub>  
<sub><em>Status: Production-deployed, actively developed</em></sub>

DataPulse is a system designed to track how data changes over time, with a focus
on schema drift, structural changes, and unexpected shifts in recurring datasets.

It is built around the assumption that data formats evolve silently and that
integrations can break without obvious failures. Instead of treating data as
static, DataPulse treats change itself as a first-class concern.

### What the system handles

* Monitoring recurring CSV uploads (daily / monthly)
* Read-only connections to external relational databases
* Detection of schema and structural changes over time
* Ingestion from public and authenticated APIs
* Non-blocking processing for long-running data checks
* Email notifications when changes or anomalies are detected

Credits
- Subhash Yaganti — Project creator and system architect; backend systems, security design, data modeling, background execution, and deployment
- Siri Mahalaxmi Vemula — Backend development,  frontend functionality, UI/UX contributions and DataPulse AI help bot for chat-based Q&A (Gemini model integration)

Live: https://data-pulse-eight.vercel.app

---

## Other Projects

### Justice Genie

<sub><em>Timeline: Mar 2024 to Oct 2024</em></sub><br />
<sub><em>Status: Live - Maintenance</em></sub>


Justice Genie is an assistive legal information tool focused on Indian law
awareness. It helps users understand legal concepts and possible directions
based on scenario-based inputs, without acting as a predictive or decision-making system.

The project was built to explore real-world API design, data handling, and
AI-assisted explanations in a sensitive domain where correctness and clarity
matter.

Credits
- Siri Mahalaxmi Vemula — Project creator and system architect; primary NLP pipeline design, backend implementation and Gemini integration
- Subhash Yaganti — NLP pipeline support, frontend–backend integration, additional features (quiz, account management), and UI/UX contributions

Live: https://justice-genie-mu.vercel.app

---

### MemeGame

<sub><em>Timeline: Feb 2025 to May 2025</em></sub><br />
<sub><em>Status: Near release</em></sub>

MemeGame is a real-time multiplayer web game built to explore shared state,
WebSocket-based communication, and live UI synchronization across multiple users.

The project focuses on handling concurrent interactions, room-based game flow,
and consistent client updates in a fast-changing, event-driven environment.

Repo: https://github.com/subhash-22-codes/MemeGame

---

## Design Boundaries

* Async > blocking
* Secure by default, not patched later
* Schema changes are inevitable—systems should expect them
* If it only works locally, it doesn’t really work

---

## Contact

LinkedIn: https://www.linkedin.com/in/subhash-yaganti-a8b3b626a/  
Email: subashyagantisubbu@gmail.com

---

## Closing Note

The projects in this repository reflect an approach focused on building systems
that hold up under real constraints rather than ideal assumptions.

DataPulse is the clearest example of that mindset.

