<div align="center">

# Lakshya Pandey
### Software Engineer — Full-Stack, Distributed Systems & Applied Machine Learning

Full-stack engineer building production-shaped software across three areas: distributed systems and consensus protocols, applied ML (fraud detection, LLM orchestration, multi-agent architectures), and secure full-stack web platforms. Focused on correctness, testing depth, and systems that hold up under real concurrency and failure — not just demos.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lakshyapandeybn/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pandeylakshya207-max)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:pandeylakshya207@gmail.com)

</div>

---

## Currently

- 🔭 Building AI-powered applications spanning LLM orchestration and multi-agent systems
- 🧪 Exploring distributed systems fundamentals — consensus, replication, linearizability
- 🤝 Open to collaboration on backend, distributed systems, and applied ML projects

---

## Skills

| Category | Technologies |
|---|---|
| **Languages** | Python, Go, TypeScript, JavaScript |
| **AI / ML** | LangGraph, Multi-Agent Systems, LLM Routing & Orchestration, Scikit-learn |
| **Backend** | FastAPI, Express.js, Node.js |
| **Frontend** | React, Vite, Tailwind CSS |
| **Data & Cache** | SQLite, Redis |
| **Systems** | Raft Consensus, Distributed Key-Value Stores, Linearizability Testing |
| **Infra / Tooling** | Docker, Git, GitHub Actions, Netlify, Capacitor |

---

## Featured Work

### [raftkv](https://github.com/pandeylakshya207-max/raftkv) — Distributed Key-Value Store
A linearizable, distributed KV store built on a **from-scratch Raft consensus implementation** in Go — no consensus library, no framework. Implements leader election, log replication with conflict-backtracking, linearizable reads via the read-index protocol, snapshotting, live cluster membership changes, and exactly-once client semantics.

Includes a custom **Jepsen-style linearizability checker** (Wing & Gong's backtracking algorithm, written from scratch) that runs concurrent clients against a real 5-node cluster while injecting real leader failures — the strongest correctness evidence a distributed system can offer. Two independent transport implementations (HTTP/JSON and binary RPC over gob) prove the transport interface is a genuine abstraction, with the binary path delivering ~52% smaller payloads and ~2.1x lower latency.

~9,000 lines of Go, 26 test files, coverage between 78–96% across all core packages.

`Go` `Raft Consensus` `Distributed Systems` `Linearizability Testing`

---

### [Nirog Health](https://github.com/pandeylakshya207-max/Nirog-Health) — AI Healthcare Assistant *(Team Project)*
An AI-powered healthcare assistant that maps user-reported symptoms to probable conditions via a trained ML classifier, paired with actionable health guidance. Built and shipped with a co-contributor (Aaryan Sharma — UI/UX & Integration).

Full-stack: React 18 + TypeScript frontend with Radix UI and a 3D interactive layer (Three.js / React Three Fiber), an Express backend, a Scikit-learn classification pipeline across 40+ disease categories, and native Android packaging via Capacitor. Containerized with Docker and deployed on Netlify.

`React` `TypeScript` `Express` `Scikit-learn` `Docker` `Capacitor`

---

### [routellm-pro](https://github.com/pandeylakshya207-max/routellm-pro) — LLM Routing System
Multi-tier LLM routing system with Groq + Gemini integration, Redis-backed logging, and cost-aware request routing across providers.

`Python` `Redis` `LLM Orchestration`

---

### [PRANAVYU](https://github.com/pandeylakshya207-max/PRANAVYU) — Multi-Agent Air Quality Platform
Multi-agent urban air quality intelligence platform, built for the ET AI Hackathon 2026.

`Python` `LangGraph` `FastAPI` `React`

---

### [Credit Card Fraud Detector](https://github.com/pandeylakshya207-max/Credit-card-fraud-detector)
AI-based fraud detection system for identifying anomalous transaction patterns in real time.

`Python` `Machine Learning`

---

### [AI Money Mentor](https://github.com/pandeylakshya207-max/AI-Money-Mentor-)
Chat-based personal finance assistant using a multi-agent architecture to deliver personalized investment, tax, and financial planning guidance.

`TypeScript` `Multi-Agent Systems`

---

### [EventSphere](https://github.com/pandeylakshya207-max/EventSphere)
Full-stack event ticketing platform with bcrypt + JWT authentication, concurrency-safe ticket registration, role-based authorization, and 12+ integration tests.

`React` `TypeScript` `Express` `SQLite`

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=pandeylakshya207-max&show_icons=true&theme=default&hide_border=true&count_private=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pandeylakshya207-max&layout=compact&theme=default&hide_border=true" height="165" />

</div>

---

<div align="center">

**[LinkedIn](https://www.linkedin.com/in/lakshyapandeybn/) · [GitHub](https://github.com/pandeylakshya207-max) · [Email](mailto:pandeylakshya207@gmail.com)**

</div>
