
<div align="center">

# Raghav Sharma

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vcenter=true&width=650&lines=Autonomous+AI+%26+Agentic+Systems;In-Memory+Systems+%26+Compilers;Codeforces+Specialist+(Max+1569);Full-Stack+%26+Systems+Engineering)](https://git.io/typing-svg)

<p align="center">
  <b>Software & AI Systems Engineer</b> | Undergraduate at <b>IIT Ropar</b>
  <br />
  Building production-grade autonomous agent workflows (LangGraph, MCP),
  zero-disk in-memory streaming engines, and low-latency developer
  infrastructure.
</p>

[![GitHub](https://img.shields.io/badge/GitHub-raghav8218-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/raghav8218)
[![Codeforces](https://img.shields.io/badge/Codeforces-Specialist_(1569)-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/raghav8218)
[![LeetCode](https://img.shields.io/badge/LeetCode-700+_Solved-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/raghav8218)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raghav-sharma-6a7596288/)
[![Email](https://img.shields.io/badge/Email-raghavsharma8218@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:raghavsharma8218@gmail.com)

</div>

---

## Technical Focus

- **Autonomous AI & Agent Workflows**: Architecting stateful directed graphs using **LangGraph**, Model Context Protocol (**MCP**) control planes, multimodal LLM vision parsers, and agent-to-cluster IPC bridges.
- **In-Memory & Systems Engineering**: Designing zero-disk streaming tarball pipelines (`io.BytesIO`), AST-level code intelligence (Tree-Sitter, Python AST), and multi-process SQLite WAL caching (< 2 ms reloads).
- **Competitive Programming & Algorithms**: Codeforces Specialist with **1000+ problems solved** across platforms.
- **Full-Stack & Security**: Building high-throughput backend services and reactive UIs using FastAPI, React, Node.js/Express, TypeScript, and real-time cybersecurity extensions.

---

## Technical Skills

<div align="center">

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Languages** | `Python` `C` `C++` `TypeScript` `JavaScript` `SQL (PostgreSQL, SQLite)` `RISC-V Assembly` `HTML5/CSS3` |
| **AI & Agentic Systems** | `LangGraph` `LangChain` `LLMs` `Autonomous Agents` `Model Context Protocol (MCP)` `RAG Pipelines` `ChromaDB` `Sentence Transformers` |
| **Web & Frameworks** | `FastAPI` `React` `Node.js` `Express.js` `Vite` `Streamlit` `D3.js` `REST APIs` `Server-Sent Events (SSE)` |
| **Databases & Caching** | `SQLite (WAL mode)` `PostgreSQL` `MongoDB` `pgvector` |
| **DevOps & Tooling** | `Git` `GitHub Actions (CI/CD)` `Docker` `Linux / SSH` `Socket IPC` `Vercel` `Render` `Tree-Sitter` |
| **Hardware & EDA** | `Cadence Virtuoso` `Calibre DRC/LVS/PEX` `SPICE Simulation` `Arduino` `ESP32` `Digital Systems` |

</div>

---

## Featured Projects

### 1. [DigGit — Zero-Disk Code Intelligence Engine](https://github.com/raghav8218/diggit)

> **Interactive codebase architecture visualizer with commit-grounded AI copilot**

[![Demo](https://img.shields.io/badge/Live_Demo-Vercel-black?style=flat-square&logo=vercel)](https://diggit-beta.vercel.app/)
[![Backend](https://img.shields.io/badge/API_Engine-Render-46E3B7?style=flat-square&logo=render)](https://github.com/raghav8218/diggit)

- **Zero-Disk Ingestion**: Streams GitHub CDN repository tarballs directly into RAM buffers (`io.BytesIO`) with **0 KB disk footprint**, achieving **4x acceleration** over `git clone`.
- **Compound Graph Synthesis**: Maps **14,000+ edges and 8,300+ nodes** using Tree-Sitter and Python AST; computes keystone symbols via **NetworkX PageRank** and circular dependencies via **Tarjan's SCC**.
- **Instant Persistence**: Leverages SQLite in WAL mode for **< 2 ms** subsequent reloads, paired with an LLM copilot grounded in AST nodes and commit diffs.

---

### 2. [virtuoso-mcp — Autonomous Silicon Design Control Plane](https://github.com/raghav8218/virtuoso-mcp)

> **High-throughput MCP bridge connecting AI agents to Cadence Virtuoso EDA clusters**

[![Protocol](https://img.shields.io/badge/Protocol-Model_Context_Protocol-8A2BE2?style=flat-square)](https://github.com/raghav8218/virtuoso-mcp)
[![PDK](https://img.shields.io/badge/PDK-65nm_Foundry-blue?style=flat-square)](https://github.com/raghav8218/virtuoso-mcp)

- **Agentic EDA Control Plane**: Built an MCP server empowering AI coding assistants to execute closed-loop IC design over secure SSH tunnels.
- **End-to-End IC Flow**: Automates schematic capture, 65nm PDK transistor sizing, and analog SPICE simulations (AC/DC sweeps, gain, phase margin).
- **Physical Verification**: Programmatically runs Calibre DRC/LVS and xRC parasitic extraction (**700+ R/C parasitics**) with **0 design rule errors** and zero layout-vs-schematic mismatches.

---

### 3. [Vouchr — Autonomous Invoice Agent](https://github.com/raghav8218/invoice-agent)

> **Multi-node agentic workflow for automated document ingestion, verification, and triage**

[![LangGraph](https://img.shields.io/badge/Orchestrator-LangGraph-FF4F00?style=flat-square)](https://github.com/raghav8218/invoice-agent)
[![Streamlit](https://img.shields.io/badge/Dashboard-Streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://github.com/raghav8218/invoice-agent)

- **6-Node State Machine**: Built a stateful directed graph in **LangGraph** (`Extract` → `Validate` → `Duplicate Check` → `Save` → `Verify` → `Review`).
- **Multimodal Visual Extraction**: Leverages multimodal LLM vision to extract invoice data immune to OCR/PDF font rendering corruptions, backed by strict decimal currency and date validations.
- **Automated Pipeline**: Integrates Gmail API ingestion, idempotent SQLite storage with duplicate detection, and independent row verification ensuring **100% data consistency**.

---

### 4. [NetGuard Pro — Real-Time URL Safety Extension](https://github.com/raghav8218/NetGuardPro)

> **Real-time cybersecurity browser extension & threat detection backend**

[![React](https://img.shields.io/badge/Frontend-React_Vite-61DAFB?style=flat-square&logo=react)](https://github.com/raghav8218/NetGuardPro)
[![NodeJS](https://img.shields.io/badge/Backend-Node.js_Express-339933?style=flat-square&logo=nodedotjs)](https://github.com/raghav8218/NetGuardPro)

- **Low-Latency Interception**: Full-stack Chrome extension and Node.js/Express REST backend inspecting and classifying malicious web URLs in **< 50 ms**.
- **Threat Scoring Heuristics**: Analyzed **100+ phishing attack vectors** to design proactive zero-day detection models.
- **Cross-Functional Leadership**: Led system architecture across an 11-member team with indexed MongoDB threat stores, modular API contracts, and automated CI/CD.

---

## Competitive Programming

- **Codeforces**: [raghav8218](https://codeforces.com/profile/raghav8218) — **Specialist** (Max Rating: **1569**)
- **Global Standing**: Global Rank **601** in Codeforces Round 1132 (Div. 2)
- **Problem Solving**: **1000+ algorithmic problems solved** across Codeforces and LeetCode


<div align="center">
  <b>Contact:</b> <a href="mailto:raghavsharma8218@gmail.com">raghavsharma8218@gmail.com</a>
</div>
