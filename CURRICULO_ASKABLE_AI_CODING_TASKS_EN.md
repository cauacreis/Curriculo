# CAUÃ FELYPE CAETANO REIS
**Software Engineer · AI Coding Tasks, Automated Testing & Multi-Agent Evaluation**  
Goiás, Brazil (Remote Worldwide) · +55 (62) 9 9452-1953 · [caua.reis.dev@gmail.com](mailto:caua.reis.dev@gmail.com)  
[linkedin.com/in/cauafelypereis](https://linkedin.com/in/cauafelypereis) · [github.com/cauacreis](https://github.com/cauacreis) · English: Advanced

---

## PROFESSIONAL SUMMARY

Polyglot Software Engineer with 2+ years of hands-on production and open-source engineering experience across **Python, TypeScript/Node.js, Java 21, C, and SQL**, specializing in **automated test suites, adversarial edge-case verification, and AI model evaluation**. Creator of **PersonalAgro ("Zé Agro")** (15k+ LOC across 30 modules in Node.js/PostgreSQL), hardened with **925 assertions across 4 automated test suites** and multi-provider LLM failover. Co-author of a scientific research paper submitted to the **IEEE Transactions on Software Engineering (IEEE TSE)** on Explainable AI (XAI/SHAP) and Human-in-the-Loop (HITL) evaluation pipelines (**OrenAI**). Architect of **SKZ Trading**, a 24/7 asynchronous Python microservice platform maintaining 99.9% uptime. Power user of AI coding agents (**Google Antigravity, Claude Code, Gemini CLI, OpenAI Codex**) with strong Docker, Linux, and Git workflows, adept at designing strict grading checks and stress-testing model code against lazy or buggy edge-case solutions.

---

## CORE TECHNICAL & EVALUATION SKILLS

- **Languages (Strongest):** Python 3.11+ (AsyncIO, FastAPI, Pytest), TypeScript / JavaScript ESNext (Node.js, Express, React/Next.js, Jest), Java 21 (Spring Boot 3, Virtual Threads, JUnit), C & x86 Assembly (GAS), SQL (PostgreSQL, MySQL, SQLite)
- **Automated Testing & Code Evaluation:** Adversarial edge-case synthesis, grading rubrics, unit & E2E testing (**925 assertions** in PersonalAgro, **37 tests** in Bodega do Vidigal, JUnit/Pytest suites), defensive logic verification, Big-O complexity analysis, static code review & OWASP Top 10 auditing
- **AI Engineering & Coding Tools:** Multi-Agent Systems (MAS / MoE), LLM stress testing, deterministic 0-token & Levenshtein guardrails, XAI (SHAP), HITL workflows; daily operator of AI coding tools (Claude Code, Google Antigravity, Gemini CLI, OpenAI Codex)
- **Infrastructure & Environment Setup:** Docker, Docker Compose, Linux/VPS, PM2, Nginx, Git & GitHub (GitFlow, commit-level reproducible environments, Pull Requests, GitHub Actions CI/CD), Bash/PowerShell, QEMU

---

## ENGINEERING EXPERIENCE & VERIFIED CODEBASES

### **PersonalAgro ("Zé Agro") — NASA Space Apps Challenge (15k+ LOC · 925 Test Assertions)**
*Creator & Full-Stack / AI Engineer | Node.js, Express, Supabase/PostgreSQL, Multi-LLM | 2026*
- **925 Assertions Across 4 Test Suites:** Designed and maintained comprehensive automated test coverage across 30 modular files (15,000+ LOC), validating deterministic crop-rotation rules, geospatial `/rotacao` API endpoints (10 REST routes), and strict agent output contracts.
- **Multi-Agent Architecture & Cost/Token Stress Testing:** Engineered 10 specialist agents and 16 tools integrating Groq, Gemini, and Cerebras with automatic multi-provider failover; combined 0-token deterministic/Levenshtein filters with parallel micro-agents to cut Embrapa RAG context by >55%, tool schemas by up to 75%, and degraded-mode payloads by 98% (`24.2k → 493 chars`).
- **Real-World Multimodal Pipeline & NASA APIs:** Integrated live **NASA POWER** (`GWETROOT`), **NASA GIBS** (MODIS NDVI, SMAP L4), Open-Meteo (FAO ET0 14d), IBGE SIDRA PAM, CEASA, and ANP APIs; implemented accessible `FFmpeg` + Whisper/Gemini + TTS voice translation and anti-herd-effect supply locks validated with **26 real farmers**.

### **SKZ Trading — 24/7 Production Microservices & Defensive Financial Logic**
*Software Architect & Python Backend Engineer | [skztrading.com](https://skztrading.com) | Jul 2026 – Present*
- **Asynchronous Python Services:** Architected and deployed 11 asynchronous microservices (`asyncio`, `aiohttp`) managed via PM2 on Linux VPS, executing 20-second market scans with <100ms API latency and 99.9% uptime across 200+ completed operations.
- **Hard-Coded Defensive Circuit Breakers:** Implemented a 4-layer liquidity scoring algorithm (0–100) with a 12% minimum buy discount, 15% target net margin, and strict anti-loss invariants preventing sales below acquisition cost under volatile edge cases.
- **Security & Financial Reconciliation:** Enforced local Ed25519/AES encryption aligned with OWASP Top 10 and automated MySQL transactional reconciliation via Mercado Pago PIX webhooks.

### **OrenAI — Applied AI Platform & Scientific Research Paper (IEEE TSE)**
*Technical Lead & AI Architecture Researcher | [github.com/cauacreis/OrenAI](https://github.com/cauacreis/OrenAI) | 2025 – Present*
- **Dockerized MAS/MoE & Explainable Benchmarking:** Architected containerized Multi-Agent / Mixture-of-Experts mineral prospectivity pipelines, pairing XGBoost/LightGBM + geospatial CNNs with **SHAP** attributions for 100% mathematically explainable predictions.
- **IEEE TSE Publication & HITL Review:** Co-authored a full paper submitted to *IEEE Transactions on Software Engineering*, formalizing system specifications, data models, and Human-in-the-Loop Active Learning validation flows.

### **Bodega do Vidigal & CoreSync CRM — Transactional Resilience & Automated Suites**
*Systems & Mobile / Backend Engineer | React Native (Expo SDK 58), Java 21, Spring Boot 3 | 2026*
- **Outbox Atomicity & 37 Jest Tests (Bodega do Vidigal):** Built an offline-first P2P POS/KDS via local mobile Wi-Fi WebSockets (<10ms) with SQLite Outbox persistence preventing duplicate orders on abrupt crashes, validated by **37 automated Jest tests**.
- **Java 21 Concurrency & AOP (CoreSync / NexoTrade-OS):** Implemented strict JWT `ThreadLocal` multi-tenant isolation, declarative Spring AOP domain audit logging, and real-time Binance WebSocket trading via Java 21 Virtual Threads.

### **MicroOS — x86 32-bit Microkernel Built from Scratch in C**
*Systems Programmer | [github.com/cauacreis/MicroOS](https://github.com/cauacreis/MicroOS) | 2026*
- Built a bootable x86 microkernel in C and GAS Assembly verified under QEMU/Multiboot, implementing two-level paging, Ring 3 process isolation, preemptive round-robin scheduling (PIT 100Hz), context switching, and port/message IPC.

---

## EDUCATION, LEADERSHIP & CERTIFICATIONS

- **B.S. in Software Engineering** — UniEVANGÉLICA (Anápolis, GO) · *4th Semester (Feb 2025 – Dec 2028) · Evening classes (100% full-time availability)*
  - Vice-President, CodeUp Academic Directory; Director of Arts & Culture (E-games / Robocode); **NASA Space Apps Challenge**; Finalist, Start Agro Innovation 2025; PuzzleWeek 2025.
- **Desktop Programmer Track (C#, Java, Relational Databases/SQL, OOP, UML)** — Instituto Mix *(Oct 2022 – Jun 2024)*
- **Certifications & Languages:** Scrum Fundamentals Certified (SFC™ — 03/2026) · Technical Storytelling (2025) · **English: Advanced** (technical writing, clear code review explanations & fluent collaboration) · **Portuguese: Native**.
