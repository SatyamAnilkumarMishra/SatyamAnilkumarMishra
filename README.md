# Hi, I'm Satyam Anilkumar Mishra 👋

**Backend & AI Systems Engineer** based in India.  
I build high-performance backend services, distributed storage engines, and production-grade agentic AI infrastructure.

I care about fundamentals and building from first principles—whether that means implementing low-level C++ distributed storage engines, writing a Model Context Protocol (MCP) server from scratch in vanilla Python rather than relying on SDK abstractions, or designing mathematically verified Medallion data pipelines on Databricks.

---

## 🎯 What I'm Looking For

I am a fresher actively seeking:
- **Full-Time Roles:** Software Engineer (Backend / AI Systems / Data Platform)
- **Remote Opportunities:** Worldwide (flexible with global timezones)
- **Contract / Freelance Work:** Custom MCP servers, agent workflows (LangGraph), FastAPI backend services, and Lakehouse pipelines

If you are building reliable systems or need someone who goes deep into protocol specs and production code, let's talk.

---

## 🛠️ Core Technical Stack

- **Languages:** Python (FastAPI, PySpark, Pydantic), C++17, SQL, TypeScript / JavaScript
- **AI & Agent Systems:** Model Context Protocol (MCP), LangGraph StateGraph, LLM Evaluation Harnesses, Prompt-Injection Defense, Citation Verification
- **Data & Lakehouse:** Databricks, Delta Lake, Unity Catalog, Auto Loader (`cloudFiles`), PySpark
- **Databases & Storage:** PostgreSQL, Redis, POSIX File Systems, SAN Block Storage Architecture
- **DevOps & Engineering Practices:** Git, GitHub Actions, Pytest (automated regression suites), Linux / POSIX, REST APIs, JSON-RPC 2.0

---

## 🚀 Featured Engineering Projects

### 1. [ClaimSense](https://github.com/SatyamAnilkumarMishra/ClaimSense) — Enterprise Lakehouse + Agentic AI Adjudication
*An automated insurance claim adjudication system combining a Medallion Lakehouse with LangGraph agent orchestration.*
- **Zero-Loss Data Reconciliation:** Enforces mathematical pipeline audit invariants across Bronze, Silver, and Gold Delta tables ($\text{Bronze} = \text{Quarantined} + \text{Silver} = \text{Gold}$).
- **Deterministic Anti-Hallucination:** Implements a Citation Verifier validating referenced policy contract clauses before response generation (achieved 0% unverified citations across a 45-claim ground-truth benchmark).
- **Hardened Defense:** XML delimiter encapsulation against prompt injections, closed-world decision taxonomy, and sub-30ms offline heuristic fallback.
- **Stack:** Python, Databricks (Delta Lake, Unity Catalog), LangGraph, Groq LLMs, FastAPI, Streamlit, Pytest (51 passing automated tests).

### 2. [eval-harness-mcp](https://github.com/SatyamAnilkumarMishra/mcp) — Zero-Dependency MCP Server from Scratch
*A Model Context Protocol server built entirely with Python's standard library—no third-party MCP SDK or heavy frameworks.*
- **Protocol-Level Implementation:** Handles raw JSON-RPC 2.0 transport over `stdio`, implementing MCP initialization handshakes, capability negotiation, line-delimited message dispatching, and standard JSON-RPC error codes.
- **Harness Adapter:** Integrates directly with an underlying evaluation harness codebase (`llm_eval_harness`), adapting asynchronous evaluation pipelines into synchronous MCP tool handlers (`run_eval`, `list_datasets`, `get_results`).
- **Regression Suite:** Includes a standalone test runner (`test_server.py`) that boots the server in a separate subprocess and exercises protocol lifecycles and edge cases.
- **Stack:** Python (Standard Library only), JSON-RPC 2.0, `stdio` transport.

### 3. [LustreFS on Network Block Storage](https://github.com/SatyamAnilkumarMishra/LustreFS) — C++17 Distributed Storage Engine
*A low-level storage engine designed for automated SAN provisioning and high-performance filesystem management.*
- **Systems-Level Architecture:** Implemented in modern C++17 targeting direct cache management, raw I/O throughput, and distributed storage semantics on network block devices.
- **Benchmarking & Stress Testing:** Automated provisioning workflows and direct I/O stress benchmarks to evaluate throughput, concurrency, and cache invalidation.
- **Stack:** C++17, Linux / POSIX systems APIs, Block Storage.

### 4. [resilient-file-storage](https://github.com/SatyamAnilkumarMishra/resilient-file-storage) — Fault-Tolerant Storage Engine
*A distributed file storage system built for reliability and high availability.*
- **Core Capabilities:** Data chunking, multi-node replica management, automated failover, and data integrity verification under simulated node dropouts.
- **Stack:** JavaScript / Node.js, Distributed Storage.

---

## 🔬 What I'm Currently Focused On

- Exploring distributed consensus and consistency guarantees in distributed file storage systems.
- Developing zero-hallucination agentic workflows and automated regression harnesses for enterprise LLM applications.
- Writing clean, modular code with rigorous automated tests.

---

## 📬 Let's Connect

- **Email:** [satyamsam2612@gmail.com](mailto:satyamsam2612@gmail.com)
- **GitHub:** [github.com/SatyamAnilkumarMishra](https://github.com/SatyamAnilkumarMishra)
- **Portfolio:** [Check out my deployed projects](https://github.com/SatyamAnilkumarMishra/samportfolio)
- **Location:** India (Available across all global timezones for remote work)
