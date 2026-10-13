# HEYYY FOLKS !

### C++ • Systems Programming • Go Backend Engineering

Computer Science undergraduate at **Indian Institute Of Information Technology Senapati, Manipur**  
Software Development Fellow at **TEXMiN-IIIT Manipur Mining CPS Centre of Excellence**

I build software with a focus on **performance, reliability, and clean engineering** — from C++ problem-solving to backend services in Go.

<p>
  <a href="https://www.linkedin.com/in/saurabh-sati-709b09313/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="mailto:saurabhsati38@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-informational?style=for-the-badge&logo=gmail" alt="Email">
  </a>
</p>

</div>

---

## About me

I'm driven by two things: **solving hard problems and building systems that can scale**. Competitive programming has taught me to break down complex problems, reason about trade-offs, and turn ideas into efficient implementations. I'm particularly interested in **C++ and systems programming**, where performance and understanding what happens under the hood matter, and **Go backend engineering**, where concurrency, reliability, and thoughtful architecture come together.

I'm currently focused on sharpening my problem-solving skills while building backend projects and exploring how complex systems fit together—from APIs and databases to asynchronous processing and failure handling. I enjoy going beyond making something work to understanding why it works, identifying bottlenecks, and figuring out how to make it better.

I've solved **500+ algorithmic problems** across coding platforms and currently hold a **1407 Codeforces rating (Specialist)**. My goal is to keep pushing both sides of the craft: becoming better at solving challenging problems and learning to design, build, test, and scale increasingly complex software.


## Tech stack

<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
</p>

## 💻 Competitive Programming

<p align="center">
  <a href="https://codolio.com/profile/Saurbh07">
    <img src="https://img.shields.io/badge/Codolio-View%20My%20Portfolio-6C5CE7?style=for-the-badge&logo=codeforces&logoColor=white" alt="View Codolio Portfolio">
  </a>
  <a href="https://codeforces.com/profile/Saurabh-0720">
    <img src="https://img.shields.io/badge/Codeforces-Specialist%20%7C%201407-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces Profile">
  </a>
</p>

- **Problems solved:** 500+ across coding platforms
- **Codeforces rating:** 1407 (Specialist)
- **Coding portfolio:** [View my Codolio profile](https://codolio.com/profile/Saurbh07)
  
## Featured project

### ⚙️ JobHarbor — Distributed Job Queue in Go
*A Redis-backed background job queue with multi-node workers, failure handling, and a live dashboard*

<p align="center">
  <img src="https://raw.githubusercontent.com/Saurabh-0720/JobHarbor/main/docs/dashboard-redis.png" alt="JobHarbor dashboard running on real Redis with four worker nodes" width="760">
</p>

- **Atomic claiming:** Redis Lua scripts let worker nodes on different machines pull from one queue without ever taking the same job
- **Reliability:** priorities, delayed jobs, retries with exponential backoff and jitter, a dead-letter queue, idempotency keys, and lease-based crash recovery (at-least-once delivery)
- **Observability:** live dashboard, p50/p90/p99 queue-wait and run-time latency, and a Prometheus `/metrics` endpoint
- **Tested and measured:** Go tests against an in-memory Redis cover priority order, retries, dead-lettering, idempotency, and crashed-worker recovery. In demo runs, median queue wait was about **110 ms** across 4 worker containers sharing one Redis, and **188 ms** at roughly 20 jobs/s with 32 workers. I also reproduced saturation with 4 workers to see how the backlog grows.
- Run modes: single process with embedded Redis, or real Redis with `docker compose up --scale worker=4`

*Go · Redis · Lua · Docker · Prometheus metrics*

**Repository:** [JobHarbor](https://github.com/Saurabh-0720/JobHarbor)

## Other projects

### 🗺️ GeoProspect (UNDER DEVELOPMENT)
Developing modular software for mineral prospectivity mapping using geological and geophysical datasets, including data processing, feature engineering, model integration, and visualization.

### 🚢 POMS — Port Operations Management System
An operational platform integrating shipment tracking, storage management, workforce planning, and logistics workflows, with delay prediction and rerouting support. Selected in the **Google Solution Challenge 2026 Top 106**.

[Live demo](https://gsc-app-630083017128.us-central1.run.app/)

### 🛠️ PipeGuard — Pipeline Leak Detection
A sensor-based anomaly detection system with an interactive geospatial monitoring dashboard.

[GitHub repository](https://github.com/Saurabh-0720/Pipeline_Leak_Detection)

**Currently focusing on:** C++ · Go · Data Structures & Algorithms · Concurrency · Operating Systems · DBMS · Computer Networks

<div align="center">

### Always learning. Always building.

*Interested in Systems programming, Backend engineering, and Performance-focused software.*

</div>
