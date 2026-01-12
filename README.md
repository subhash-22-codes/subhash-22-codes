# Subhash Yaganti

Full-stack developer with a strong preference for backend work. I mostly build systems around authentication, async processing, and handling data that changes over time.

---

## About

Final-year Computer Science undergraduate (B.Tech, graduating 2026).

I focus on building real projects end to end, from backend logic and APIs to frontend integration and deployment. 
Most of my work comes from learning by shipping and maintaining systems rather than stopping at demos.

More details and projects: https://subhashportfolio-y.netlify.app/

---

## Skills & Technologies

**Backend**

* Python with Flask and FastAPI for API-driven services
* REST APIs and WebSockets for request-based and real-time flows
* JWT-based authentication with access and refresh tokens, rotation, and session control
* OAuth integrations (Google, GitHub) with backend token verification
* Background job processing using Celery to isolate long-running tasks
* Redis for task coordination and transient state

**Data / Storage**

* PostgreSQL schema design with migrations and support for evolving data models
* MongoDB Atlas for managed MongoDB deployment

**Frontend**

* React with TypeScript for state-driven, auth-aware interfaces
* Client-side session handling aligned with backend authentication state
* Basic data visualization using Recharts

**Infra / Deployment**

* Docker for local service isolation and reproducible development environments
* Backend deployment on Render with environment-based configuration
* GitHub Actions for basic CI workflows (linting, checks, controlled deploys)
* Supabase for managed PostgreSQL with access control
* Vercel for frontend deployment

---

## DataPulse — Real-Time Data & Schema Monitoring (Active Project)

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

Credits:
- Subhash Yaganti — System ownership, backend architecture, frontend integration, deployment
- Siri Mahalaxmi Vemula — Co-founder, primary contributor, backend development, system design

Live: https://data-pulse-eight.vercel.app

---

## Other Projects

### Justice Genie

Justice Genie is an assistive legal information tool focused on Indian law
awareness. It helps users understand legal concepts and possible directions
based on scenario-based inputs, without acting as a predictive or decision-making system.

The project was built to explore real-world API design, data handling, and
AI-assisted explanations in a sensitive domain where correctness and clarity
matter.

Credits:
- Siri Mahalaxmi Vemula — Idea, system architecture, backend implementation, Gemini integration
- Subhash Yaganti — Frontend–backend integration, additional features (quiz, account management), and UI/UX

Live: https://justice-genie-mu.vercel.app

---

### MemeGame

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

