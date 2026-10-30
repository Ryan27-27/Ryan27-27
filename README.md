<!-- Aryan Adityaa | Profile README | Midnight / cyan / indigo -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0b1020,45:172554,100:0891b2&text=Aryan%20Adityaa&fontColor=ffffff&fontSize=52&fontAlignY=38&desc=Backend%20Systems%20%E2%80%A2%20AI%20Engineering%20%E2%80%A2%20Security&descAlignY=60&descSize=18" width="100%" alt="Aryan Adityaa — Backend Systems, AI Engineering and Security" />
</p>

<p align="center">
  <a href="https://github.com/Ryan27-27"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=900&color=22D3EE&center=true&vCenter=true&width=760&lines=I+build+systems+that+stay+correct+under+load.;I+design+event-driven+backends+and+reliable+APIs.;I+explore+LLM+agents%2C+RAG%2C+and+AI+evaluation.;I+care+about+security+from+design+through+deployment." alt="Engineering focus" /></a>
</p>

<p align="center">
  <a href="https://github.com/Ryan27-27"><img src="https://img.shields.io/badge/GitHub-Ryan27--27-181717?style=for-the-badge&logo=github" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/aryan-adityaa27/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://leetcode.com/RyanLm_27"><img src="https://img.shields.io/badge/LeetCode-Knight-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode Knight" /></a>
  <img src="https://img.shields.io/badge/DSA-1000%2B%20Questions-2563eb?style=for-the-badge" alt="1000 plus DSA questions" />
</p>

---

## About

I'm a Software Engineering undergraduate at **Delhi Technological University (2023–2027)**, interested in the engineering behind dependable backend platforms, distributed workflows, and applied AI systems.

I enjoy working on problems where a system has to do more than return a successful HTTP response: **a retry must not create a duplicate transaction, concurrent requests must not oversell inventory, an event must not disappear between a database commit and message publication, and an AI agent should be evaluated on measurable outcomes rather than a convincing demo.**

My projects span backend engineering, distributed systems, AI infrastructure, application security, and data engineering. I tend to learn by building complete systems, testing failure paths, and documenting the trade-offs behind the implementation.

## Engineering interests

<p align="center">
  <img src="https://img.shields.io/badge/Backend%20%26%20APIs-0f766e?style=for-the-badge&logo=fastapi&logoColor=white" alt="Backend and APIs" />
  <img src="https://img.shields.io/badge/Distributed%20Systems-1d4ed8?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Distributed systems" />
  <img src="https://img.shields.io/badge/AI%20%26%20Agents-6d28d9?style=for-the-badge&logo=openai&logoColor=white" alt="AI and agents" />
  <img src="https://img.shields.io/badge/Application%20Security-b91c1c?style=for-the-badge&logo=owasp&logoColor=white" alt="Application security" />
  <img src="https://img.shields.io/badge/Data%20Engineering-0369a1?style=for-the-badge&logo=apachespark&logoColor=white" alt="Data engineering" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Ryan27-27/Ryan27-27/main/assets/cyber-engineering.svg" width="100%" alt="3D-inspired cybersecurity and engineering systems illustration" />
</p>

## Selected work

Projects are grouped by the engineering problem they explore, rather than by programming language.

### 01 · Backend engineering & distributed systems

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/Reward-Ledger">Pointwise — Wallet & Rewards Ledger</a></h3>
      <p><sub>Node.js · Express · PostgreSQL · React · Docker</sub></p>
      <p>A wallet and rewards platform centred on financial correctness: double-entry journals, idempotent money movement, hash-chained history, refresh-session rotation, and controlled administrative approvals.</p>
      <p><b>Engineering focus:</b> transaction boundaries, auditability, replay safety, and reliable notifications through a transactional outbox.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/order-inventory-system">Distributed Order & Inventory</a></h3>
      <p><sub>Python · FastAPI · PostgreSQL · RabbitMQ</sub></p>
      <p>Two independently deployable services coordinate order fulfilment across warehouses without sharing a database or relying on a synchronous service chain.</p>
      <p><b>Engineering focus:</b> choreographed saga, transactional outbox, idempotent consumers, row-level locking, and warehouse allocation.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/Rate_keeper">RateKeeper</a></h3>
      <p><sub>C++17 · CMake · Concurrency · HTTP</sub></p>
      <p>A rate-limiting service built around a lazy token bucket, a generic O(1) LRU cache, and sharded state to reduce lock contention between unrelated clients.</p>
      <p><b>Engineering focus:</b> concurrency-safe data structures, bounded state, eviction trade-offs, and a load-test harness.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/ledger-service">Fullstack Ledger</a></h3>
      <p><sub>Java 21 · Spring Boot · PostgreSQL · Redis · React</sub></p>
      <p>An append-only points ledger with database-enforced history protection, audit-based balance verification, and separate concurrency strategies for credits and debits.</p>
      <p><b>Engineering focus:</b> pessimistic and optimistic locking, idempotency keys, compensating reversals, and database invariants.</p>
    </td>
  </tr>
</table>

### 02 · AI engineering & agent infrastructure

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/Smart-Shop-AI">ShopSmart AI</a></h3>
      <p><sub>React · FastAPI · LangChain · Groq · ChromaDB · SQLAlchemy</sub></p>
      <p>AI-assisted commerce with product discovery, structured query planning, retrieval, policy Q&amp;A, and transactional checkout. SQL remains authoritative for stock and price while vector retrieval handles policy documents.</p>
      <p><b>Engineering focus:</b> grounded retrieval, validation of LLM-generated filters, transactional order creation, and deterministic fallbacks.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/Agent-Eval">Agent Eval Harness</a></h3>
      <p><sub>Python · MCP · Tool Calling · pytest · Tracing</sub></p>
      <p>An end-to-end agent backend with an MCP tool server, pluggable agent/router, labelled evaluation dataset, scoring metrics, and per-operation latency summaries.</p>
      <p><b>Engineering focus:</b> routing accuracy, argument correctness, tool execution, regression evaluation, and observability.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/RepoSage">RepoSage</a></h3>
      <p><sub>Python · AST · TF-IDF · Retrieval · LLM APIs</sub></p>
      <p>A lightweight codebase assistant for natural-language questions and diff reviews, using AST-aware Python chunking and offline TF-IDF retrieval with optional model backends.</p>
      <p><b>Engineering focus:</b> code-aware indexing, testable retrieval, offline-first workflows, and pluggable LLM providers.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/PulseStream">PulseStream</a></h3>
      <p><sub>FastAPI · RabbitMQ · Parquet · PySpark · PostgreSQL</sub></p>
      <p>A communication-event analytics pipeline: asynchronous ingestion, durable messaging, idempotent processing, partitioned analytical storage, Spark transformations, and an analytics API.</p>
      <p><b>Engineering focus:</b> event processing, retry and dead-letter paths, data quality, and analytical workloads.</p>
    </td>
  </tr>
</table>

### 03 · Application security & AI security

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/Aegis">Aegis — AI Security Scanner</a></h3>
      <p><sub>Python · FastAPI · Go · React · OWASP · Docker</sub></p>
      <p>A security assessment platform for LLM-backed and agentic applications, covering prompt injection, RAG risks, agent misuse, and supply-chain weaknesses. Includes an inline Go runtime firewall and OWASP-mapped report generation.</p>
      <p><b>Engineering focus:</b> AI-specific threat modelling, attack simulation, runtime controls, and evidence-backed reporting.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/Sentinel">Sentinel</a> + <a href="https://github.com/Ryan27-27/Sentinel-Bridge">Sentinel Bridge</a></h3>
      <p><sub>Python · Flask · SQLite · GitHub Actions · MITRE ATT&amp;CK</sub></p>
      <p>A purple-team security lab connecting pre-release AppSec scanning with runtime attack detection, joining pipeline findings and live detections through CWE-to-ATT&amp;CK mappings.</p>
      <p><b>Engineering focus:</b> SAST, DAST, secrets scanning, triage automation, attack simulation, and detection coverage.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/Credential-Vault">Credential Vault</a></h3>
      <p><sub>Python · AES-GCM · Argon2id · MySQL</sub></p>
      <p>A command-line password manager using authenticated encryption, memory-hard key derivation, password-strength checks, secure generation, and breach lookup via Have I Been Pwned.</p>
      <p><b>Engineering focus:</b> key derivation, nonce-based authenticated encryption, and safer credential handling.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/PhishFence">PhishFence</a></h3>
      <p><sub>Python · Flask · Scikit-learn · VirusTotal</sub></p>
      <p>A proxy-based phishing detection prototype that inspects URLs, forms, links, and network indicators to identify suspicious destinations before credentials are submitted.</p>
      <p><b>Engineering focus:</b> layered URL analysis, threat intelligence integration, and traffic inspection.</p>
    </td>
  </tr>
</table>

### 04 · Data engineering & market data

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/Tick-Data_Market_Pipeline">Tick-Data Market Pipeline</a></h3>
      <p><sub>Python · pandas · PyArrow · Parquet · q/kdb+</sub></p>
      <p>A market-data storage model inspired by the RDB → end-of-day writedown → partitioned HDB pattern, implemented in Python/Parquet and separately expressed in q/kdb+.</p>
      <p><b>Engineering focus:</b> time-series storage, partition pruning, OHLCV/VWAP aggregation, and as-of joins.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ryan27-27/etl_weather_pipeline">Weather ETL Pipeline</a></h3>
      <p><sub>Python · ETL · Data Pipelines</sub></p>
      <p>A focused data-engineering project for extracting, transforming, and loading weather data into a more useful structured form.</p>
      <p><b>Engineering focus:</b> repeatable data processing, transformation steps, and pipeline organization.</p>
    </td>
  </tr>
</table>

<p align="center"><i>More experiments and learning repositories are available in the <a href="https://github.com/Ryan27-27?tab=repositories">full repository list</a>.</i></p>

---

## Technical toolkit

<table>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
    </td>
  </tr>
  <tr><td><b>Backend & APIs</b></td><td>Spring Boot · FastAPI · Flask · Node.js · Express · REST · SQLAlchemy</td></tr>
  <tr><td><b>Data & messaging</b></td><td>PostgreSQL · MySQL · SQLite · Redis · RabbitMQ · ChromaDB · Parquet · PySpark</td></tr>
  <tr><td><b>AI & LLM systems</b></td><td>RAG · LLM agents · MCP · Tool calling · LangChain · Hugging Face · Groq · Evaluation harnesses</td></tr>
  <tr><td><b>Security</b></td><td>OWASP · Burp Suite · SAST · DAST · Secrets scanning · MITRE ATT&amp;CK · Slither · Foundry · Applied cryptography</td></tr>
  <tr><td><b>Engineering & operations</b></td><td>Docker · GitHub Actions · pytest · Testcontainers · CMake · Linux · CI/CD · Structured logging</td></tr>
</table>

## How I approach engineering

- **Correctness before cleverness.** Model invariants explicitly and enforce them at the database boundary where possible.
- **Retries are part of the design.** Idempotency belongs at both request and message-consumer boundaries.
- **Distributed systems need failure paths.** Think about outboxes, duplicate delivery, dead-letter queues, and recovery—not only the happy path.
- **AI needs evaluation.** Measure routing, tool use, grounding, latency, and regressions instead of relying only on demos.
- **Security is a lifecycle concern.** Test before release, observe at runtime, and make findings actionable.

## Topics I keep exploring

- **Reliable distributed workflows:** transactional outboxes, sagas, idempotent consumers, and recovery from partial failure.
- **AI systems that can be evaluated:** MCP tool interfaces, agent routing, retrieval quality, and regression harnesses.
- **Secure-by-design software:** applied cryptography, authorization boundaries, AI threat modelling, and runtime controls.
- **Data systems:** event-driven ingestion, time-series storage, partitioning, and analytical query patterns.

## Problem solving

<p align="center">
  <a href="https://leetcode.com/RyanLm_27"><img src="https://img.shields.io/badge/LeetCode-RyanLm__27-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode profile" /></a>
  <img src="https://img.shields.io/badge/Contest%20rank-Knight-6d28d9?style=for-the-badge" alt="Knight rank" />
  <img src="https://img.shields.io/badge/DSA-1000%2B%20Questions-16a34a?style=for-the-badge" alt="1000 plus DSA questions" />
</p>

## GitHub activity

<p align="center">
  <a href="https://github.com/Ryan27-27?tab=repositories"><img src="https://img.shields.io/badge/Explore-Repositories-0ea5e9?style=for-the-badge&logo=github&logoColor=white" alt="Explore repositories" /></a>
  <a href="https://github.com/Ryan27-27?tab=stars"><img src="https://img.shields.io/badge/Interests-Open%20Source-7c3aed?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="Open source interests" /></a>
</p>

<p align="center"><i>If a stats card fails to load, the projects and contribution history remain available directly on GitHub.</i></p>

## Connect

<p align="center">
  <a href="https://github.com/Ryan27-27"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/aryan-adityaa27/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://leetcode.com/RyanLm_27"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode" /></a>
</p>

<p align="center"><i>Interested in building reliable backend platforms, useful AI systems, and security tooling.</i></p>
<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:0891b2,55:172554,100:0b1020" width="100%" alt="" /></p>
