<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/JeyaViknan/JeyaViknan/main/assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/JeyaViknan/JeyaViknan/main/assets/header-light.svg">
  <img alt="Jeya Viknan — Software Engineer: automation, applied AI, retrieval, full-stack, testing" src="https://raw.githubusercontent.com/JeyaViknan/JeyaViknan/main/assets/header-light.svg" width="100%">
</picture>

<br>

[LinkedIn](https://www.linkedin.com/in/jeya-viknan/) &nbsp;·&nbsp; [Email](mailto:jeyaviknan11@gmail.com) &nbsp;·&nbsp; [Résumé](https://drive.google.com/file/d/1h0M4gDnAb7ONofLrCaxShPNXvq43ftnP/view?usp=sharing)

</div>

<br>

I work across the whole path a system takes to production — the backend and the interface, the retrieval layer that makes it useful, the tests that prove it works, and the automation that ships it. The through-line is the same everywhere: build the thing, then build the evidence it holds.

Currently finishing a B.Tech in CS at VIT Chennai alongside a BS in Data Science at IIT Madras.

<br>

---

<br>

## Selected work

<br>

### Penny

**A ledger that refuses to lose money.**

Double-entry postings where balances are a derived database view, never a mutable field. Concurrent transfers hold ordered row locks, every write carries an idempotency key, and the audit log is append-only — enforced by a database trigger rather than a code convention. Four role tiers, each scoped at the query layer.

Correctness is the feature, so it is tested like one: integration tests run against real PostgreSQL through Testcontainers, and the build fails below 85% coverage.

`Java 17` `Spring Boot 3` `Spring Data JDBC` `PostgreSQL` `Flyway` `React 19` `TypeScript`

[View repository →](https://github.com/JeyaViknan/ledgerLite)

<br>

### AutoRAG

**Retrieval that diagnoses its own weak answers.**

A self-healing knowledge assistant built on semantic chunking and a reranking stage, served behind FastAPI. When retrieval confidence drops, the pipeline re-queries rather than answering anyway — measured at 15% higher retrieval accuracy than baseline across a 100-query evaluation set.

`Python` `FastAPI` `FAISS` `HuggingFace`

[View repository →](https://github.com/JeyaViknan/AutoRAG-Self-Healing-Knowledge-Assistant)

<br>

### Sorry, No Proxy

**Attendance you can't mark for a friend.**

Rotating QR authentication layered with facial verification, closing the two gaps that make classroom attendance trivially forgeable. In live use at 500+ verifications a day.

`Python` `Computer Vision` `React`

[View repository →](https://github.com/JeyaViknan/sorry-no-proxy-pro)

<br>

---

<br>

## Experience

<br>

**AI Engineering Intern** — Integra Global Solutions
<sub>May 2026 – July 2026</sub>

Built a production search and retrieval platform over 5,000+ accounting and BPO documents as one of three engineers. Retrieval time fell 40%; release cycles shortened 30% after moving the team onto GitHub Actions CI/CD.

<sub>`FastAPI` · `PostgreSQL` · `FAISS` · `React` · `Docker` · `PyTest`</sub>

<br>

**AI Research Intern** — NIT Trichy
<sub>May 2025 – July 2025</sub>

Designed an end-to-end NLP pipeline for sarcasm detection, from preprocessing through feature extraction and evaluation. 86.8% accuracy on a 2,000+ sample dataset.

<sub>`Python` · `Scikit-Learn` · `NLP`</sub>

<br>

---

<br>

## Research

<br>

**HC-WF — Hierarchical Context-Aware Website Fingerprinting**
<sub>Ongoing</sub>

A Transformer-based framework for identifying websites from encrypted Tor traffic. 92.4% closed-world accuracy and 84.6% open-world F1, evaluated across 1,000+ unmonitored sites and multi-tab browsing scenarios.

<br>

**F.O.R.G.E — Fog-Orchestrated Real-Time Guidance for Fire Evacuation**
<sub>Patent filing in progress · Co-inventor</sub>

Evacuation routing computed at the fog layer, so guidance survives the loss of cloud connectivity that fires tend to cause. Hazard-aware graph traversal recomputes paths against live fire-location and occupancy data. Prototyped on Raspberry Pi and Arduino with IoT sensing and dynamic LED guidance.

<br>

---

<br>

## Technical specifications

<br>

| | |
|:---|:---|
| **Languages** | Java · Python · TypeScript · JavaScript · C++ · C · SQL |
| **Backend** | Spring Boot 3 · Spring Security · Spring Data JDBC · FastAPI · Node.js · Express · REST · JWT · OpenAPI |
| **Frontend** | React 19 · Vite · Tailwind CSS · HTML · CSS |
| **Data & storage** | PostgreSQL · MySQL · MongoDB · Redis · Flyway · FAISS |
| **AI & ML** | PyTorch · HuggingFace · scikit-learn · RAG · LoRA · semantic retrieval · reranking |
| **Testing & automation** | JUnit 5 · MockMvc · Testcontainers · JaCoCo · PyTest · Postman · CI pipelines · coverage gating |
| **Infrastructure** | Docker · Kubernetes · AWS · GitHub Actions · Git · Linux · Maven |

<br>

---

<br>

## Leadership

<br>

**Technical Head** — VITeach
<sub>December 2024 – Present</sub>

Lead a team of 10+ developers building platforms used by 1,000+ students. Introduced branching conventions, mandatory pull-request review, and CI/CD — the difference between a codebase and a release process.

<br>

---

<br>

## Education

<br>

| | | |
|:---|:---|:---|
| **Vellore Institute of Technology, Chennai** | B.Tech, Computer Science Engineering | 2023 – 2027 · CGPA 8.5 |
| **Indian Institute of Technology, Madras** | BS, Data Science *(concurrent)* | 2023 – 2027 · CGPA 8.0 |

<br>

---

<br>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/JeyaViknan/JeyaViknan/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/JeyaViknan/JeyaViknan/output/github-contribution-grid-snake.svg">
  <img alt="Contribution graph" src="https://raw.githubusercontent.com/JeyaViknan/JeyaViknan/output/github-contribution-grid-snake.svg">
</picture>

<br><br>

<sub>Open to software engineering roles — backend, full-stack, automation, SDET, and applied AI.</sub>

</div>
