<div align="center">

# Umashankar Kushwaha

### Backend-focused Software Engineer — polyglot systems, query optimization, statistical pipelines

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Umashankar620)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/umashankar-kushwaha-2a06)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:umashankar62069@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/umashankar062/)
[![Resume](https://img.shields.io/badge/Resume-000000?style=flat-square&logo=readdotcv&logoColor=white)](https://drive.google.com/drive/folders/1VOXX9Iv24wluMr34IexwZcE0lFHYa_ro?usp=drive_link)

</div>

---

## About

B.Tech CSE undergraduate at NIT Hamirpur. I build backend and full-stack systems where the interesting problems are underneath the API — schema design, query performance, and turning messy real-world data into something a service can rely on. RankSetu, a NEET counselling platform processing 40,000+ real government records, is the project I'd point to first.

## Current Focus

- Query-level performance: indexing strategy, eliminating N+1 patterns, caching layers
- Statistical forecasting for real-world decision systems
- Service boundaries between I/O-bound and compute-bound workloads
- ETL pipelines for inconsistent, semi-structured source data

---

## Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Database**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Data & Tools**
![Pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**CS Fundamentals**
`Data Structures` `Algorithms` `DBMS` `Operating Systems` `Computer Networks` `OOP`

---

## Featured Projects

### RankSetu
**NEET counselling intelligence platform — Next.js · Node/Express · Python/FastAPI · MySQL**

Production system serving real users, processing 40,000+ counselling records collected from inconsistent government PDF reports.

**Problem**
NEET aspirants need to predict, from historical MCC counselling data, which colleges are realistic to expect an admission offer at — a problem that mixes messy source data, statistical forecasting, and read-heavy query performance at scale.

**Architecture**
A polyglot 3-tier system: Next.js frontend, a Node/Express API gateway, and a separate Python/FastAPI prediction service. I/O-bound request handling and compute-bound statistical work are split across services so each can scale independently.

**Engineering Highlights**
- Diagnosed and fixed an N+1 query bottleneck in the upgrade-probability engine — replaced thousands of per-institute round-trips with a single bulk fetch and in-memory aggregation, cutting response time from minutes to seconds.
- Designed a composite MySQL indexing strategy across 5 filter dimensions (institute, year, round, category, quota), paired with an in-memory TTL caching layer to keep multi-filter search fast at scale.
- Built an end-to-end ETL pipeline (pdfplumber, pandas, regex normalization) to clean and deduplicate inconsistent government PDF data spanning 6+ years of counselling records — cutting manual processing effort by over 99%.

**Statistical Forecasting Engine**
Predicts college closing ranks and classifies options into Dream / Target / Safe tiers using weighted OLS regression, Holt's exponential smoothing, IQR-based outlier filtering, and R²-based confidence scoring.

**Links:** [GitHub](https://github.com/Umashankar620/RankSetu.git) · [Live Demo](https://rank-setu.vercel.app/)

---

### College Course Allotment Portal
**Multi-role allocation system — TypeScript · Express.js · MySQL · React**

Built with a 3-member team; independently owned the backend API, database design, and allotment logic.

**Problem**
Automate course allocation across compulsory departmental assignments and elective requests, respecting seat capacity and student preference ranking, with clean separation between student and admin capabilities.

**Engineering Highlights**
- Designed a normalized MySQL schema (EER modeling) for students, courses, requests, and enrollments.
- Built REST API routes with role-based middleware separating student and admin access.
- Implemented the core allotment algorithm: auto-assigns compulsory courses by department, then resolves elective requests against seat availability and preference rank.
- Built authentication and role-based authorization securing admin-only operations (course/student management).

**Links:** [GitHub](https://github.com/Umashankar620/College-Course-Allotment-Portal.git)

---

## DSA & Problem Solving

300+ problems solved on [LeetCode](https://leetcode.com/u/umashankar062/), with continued focus on algorithmic problem-solving alongside system design.

## Open Source

*Currently focused on original systems (RankSetu, Course Allotment Portal). Open to contributing — this section will track it as it happens.*

## Achievements

- AIR 14526 (CRL) and AIR 3415 (Category) — JEE Mains, 99.15 percentile in Mathematics
- 300+ DSA problems solved on LeetCode
- Joint Secretary, Hostel Common Room Committee — led coordination for 500+ resident students

---

<!--
## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Umashankar620&show_icons=true&theme=default&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Umashankar620&layout=compact&hide_border=true)
![Streak](https://github-readme-streak-stats.herokuapp.com/?user=Umashankar620&hide_border=true)

</div>

---
-->


## Contact

- **Email:** umashankar62069@gmail.com
- **LinkedIn:** [umashankar-kushwaha-2a06](https://www.linkedin.com/in/umashankar-kushwaha-2a06)
- **GitHub:** [Umashankar620](https://github.com/Umashankar620)
- **LeetCode:** [umashankar062](https://leetcode.com/u/umashankar062/)
- **Resume:** [View Resume](https://drive.google.com/drive/folders/1VOXX9Iv24wluMr34IexwZcE0lFHYa_ro?usp=drive_link)
