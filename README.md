# Hi, I'm Satyam Anilkumar Mishra 👋

**Backend & AI Systems Engineer** based in India.  
I build high-performance backend services, distributed storage tooling, and production-grade agentic AI systems.

I care about fundamentals and building from first principles—whether that means orchestrating enterprise RAG platforms with embedded Model Context Protocol (MCP) servers, writing zero-dependency protocol servers in vanilla Python, automating Linux SAN provisioning and distributed Lustre filesystems, or enforcing mathematically verified data pipelines on Databricks.

---

## 🎯 What I'm Looking For

I am a fresher actively seeking:
- **Full-Time Roles:** Software Engineer (Backend / AI Systems / Data Platform)
- **Remote Opportunities:** Worldwide (flexible across global timezones)
- **Contract / Freelance Work:** Custom MCP servers, agent workflows (LangGraph), FastAPI backend services, and Lakehouse pipelines

If you are building reliable systems or need someone who goes deep into protocol specs and production code, let's talk.

---

## 🛠️ Core Technical Stack

- **Languages:** Python (FastAPI, PySpark, Pydantic), C++, SQL, TypeScript / JavaScript
- **AI & Agent Systems:** Model Context Protocol (MCP), LangChain / LangGraph, RAG (ChromaDB, sentence-transformers), Evaluation Harnesses, Anti-Hallucination Guardrails
- **Data & Lakehouse:** Databricks, Delta Lake, Unity Catalog, Auto Loader (`cloudFiles`), PySpark
- **Distributed Storage & Infrastructure:** Lustre Distributed Filesystem, iSCSI SAN Provisioning, POSIX File Systems, Linux System Administration
- **DevOps & Engineering Practices:** Git, GitHub Actions, Pytest (automated regression suites), Linux / POSIX, REST APIs, JSON-RPC 2.0

---

## 🚀 Featured Engineering Projects

### 1. [Career Advisor](https://github.com/SatyamAnilkumarMishra/career-advisor) — AI Career Intelligence Platform & MCP Server
*A dual-tier career platform combining grounded RAG, ATS resume parsing, and live job matching with an embedded Model Context Protocol server.*
- **RAG & Grounded Retrieval:** Indexes domain guides and user documents via ChromaDB and `sentence-transformers`, with query-intent classification and relevance-threshold filtering.
- **Embedded MCP Server:** Exposes career tools over `stdio` via JSON-RPC 2.0, enabling AI assistants (Claude Desktop, Claude Code) to invoke resume audits, skill gap matrix diffing, and roadmap generators directly.
- **Enterprise Backend:** FastAPI service equipped with LangSmith tracing, automated evaluation harnesses, retry/backoff policies, and 87 passing unit/integration tests.
- **Stack:** Python, FastAPI, Next.js 16 / React 19, TypeScript, ChromaDB, LangChain, Groq / Google Gemini, Pytest.

### 2. [ClaimSense](https://github.com/SatyamAnilkumarMishra/ClaimSense) — Enterprise Lakehouse + Agentic AI Adjudication
*An automated insurance claim adjudication system combining a Medallion Lakehouse with LangGraph agent orchestration.*
- **Zero-Loss Data Reconciliation:** Enforces mathematical pipeline audit invariants across Bronze, Silver, and Gold Delta tables (Bronze = Quarantined + Silver = Gold).
- **Deterministic Anti-Hallucination:** Implements a Citation Verifier validating referenced policy contract clauses before response generation (achieved 0% unverified citations across a 45-claim ground-truth benchmark).
- **Hardened Defense:** XML delimiter encapsulation against prompt injections, closed-world decision taxonomy, and sub-30ms offline heuristic fallback.
- **Stack:** Python, Databricks (Delta Lake, Unity Catalog), LangGraph, Groq LLMs, FastAPI, Streamlit, Pytest (51 passing automated tests).

### 3. [eval-harness-mcp](https://github.com/SatyamAnilkumarMishra/mcp) — Zero-Dependency MCP Server from Scratch
*A Model Context Protocol server built entirely with Python's standard library—no third-party MCP SDK or heavy frameworks.*
- **Protocol-Level Implementation:** Handles raw JSON-RPC 2.0 transport over `stdio`, implementing MCP initialization handshakes, capability negotiation, line-delimited message dispatching, and standard JSON-RPC error codes.
- **Harness Adapter:** Integrates directly with an underlying evaluation harness codebase (`llm_eval_harness`), adapting asynchronous evaluation pipelines into synchronous MCP tool handlers (`run_eval`, `list_datasets`, `get_results`).
- **Regression Suite:** Includes a standalone test runner (`test_server.py`) that boots the server in a separate subprocess and exercises protocol lifecycles and edge cases.
- **Stack:** Python (Standard Library only), JSON-RPC 2.0, `stdio` transport.

### 4. [lustre-cli](https://github.com/SatyamAnilkumarMishra/lustre-cli) — Distributed Lustre Filesystem & SAN Automation CLI
*A Python-based systems orchestration CLI for automated Linux SAN provisioning and high-performance Lustre distributed storage deployment.*
- **Automated SAN Provisioning:** Orchestrates iSCSI target/initiator lifecycles, LUN discovery, and multi-node portal authentication from the terminal.
- **Filesystem Deployment & Striping:** Formats and mounts Lustre components (MGS, MDT, OST) across network block devices with automated striping configuration and POSIX compliance validation.
- **Benchmarking & Fault Injection:** Built-in benchmarking engine (`dd`, direct I/O throughput) and fault simulation routines (OST failover, network drops, corrupted configuration recovery).
- **Stack:** Python, Lustre Distributed FS, iSCSI, Linux Storage / Block Layer, Bash.

### 5. [resilient-file-storage](https://github.com/SatyamAnilkumarMishra/resilient-file-storage) — Fault-Tolerant Storage Engine
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
