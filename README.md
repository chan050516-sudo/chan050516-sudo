<div align="center">

# Hi, I'm David Chan 👋

**Software Engineering Undergraduate · AI Systems & Decision Engineering**  
*Universiti Teknologi Malaysia (UTM)*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/david-chan-6367ab394/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat&logo=gmail)](mailto:chan050516@gmail.com)

> *"Tools calculate the world. Models reason about the world."*

</div>

---

### 🧭 About Me

I am a Software Engineering undergraduate at Universiti Teknologi Malaysia (UTM), interested in building intelligent systems that connect AI reasoning, data engineering, algorithms, and real-world decision-making.

My projects span document forensics, compiler-inspired data migration, geospatial simulation, and resource-constrained multi-agent systems. Across these domains, I focus on designing end-to-end architectures that make complex workflows **traceable, modular, and verifiable**.

My engineering approach combines:
- **Systems thinking:** decomposing complex workflows into well-defined components, interfaces, and data flows.
- **AI–algorithm integration:** assigning language models, statistical methods, and deterministic algorithms the roles they are best suited for.
- **Reliability by design:** making assumptions explicit and validating critical outputs, constraints, and state transitions where correctness matters.

---

### 📌 Featured Systems

#### 🔍 [TrustLens v2](https://github.com/chan050516-sudo/TrustLens_v2) — Multi-Engine Document Forensics
*Independent Research & Engineering · Evolved from TrustLens (KitaHack 2026, 3rd Place)*
- **Problem:** Document authenticity checks fail when relying on single signals; real-world tampering frequently masks visual flaws while violating internal arithmetic or container metadata.
- **Architecture:** A multi-engine forensic pipeline sharing a unified physical `DocumentIR`, routing machine-verifiable findings and structural context to a VLM-assisted evidence synthesis stage that compiles a cited `CaseFile`.
- **Key Engineering:** PDF structural and container forensics (`pikepdf`, `qpdf`, `ExifTool`); deterministic visual anomaly analysis (MAD outlier detection, RANSAC baseline fitting); constraint-based reconciliation across accounting topologies; authoritative grounding against registry whitelists; and end-to-end cross-stage traceability anchored by a shared observation_id scheme.
- **Stack:** Python · PyMuPDF · pikepdf · Docling · RapidOCR · ExifTool · Vertex AI

#### 🔄 [Enterprise Data Compiler](https://github.com/chan050516-sudo/Enterprise-Data-Compiler) — Compiler-Inspired ERP Data Migration
*Compiler-Inspired Data Engineering · Iterative Development*
- **Problem:** Enterprise ERP migrations demand massive engineering effort to map messy, heterogeneous source files into rigid target schemas, while LLM-based code generation risks catastrophic unverified schema mutations.
- **Architecture:** A compiler-inspired staged pipeline that progresses from statistical data profiling to evidence-based relationship discovery, candidate mapping, deterministic validation, and declarative execution.
- **Key Engineering:** Column profiling with conflict-resolved pattern detectors (`ColumnProfileIR`); behavior blocking for schema relationship discovery; graph-based dependency analysis; and validation of types, keys, and contract invariants prior to transformation.
- **Stack:** Python · Pandas · NetworkX · Pydantic · SQLite · Gemini

#### 🏙️ [Living Masterplan](https://github.com/chan050516-sudo/Living_Masterplan) — Time-Aware Township Decision Engine
*Sime Darby Property University Hackathon 2026 (Planet Track) · Team Airost*
- **Problem:** Static master plans strand capital in underperforming township "Deadspace," defaulting to carbon-intensive demolition rather than circular adaptive reuse.
- **Architecture:** A geospatial decision pipeline integrating spatial network analysis, diagnostic asset triage, multi-year counterfactual simulation, and constrained LLM orchestration.
- **Key Engineering:** Walking graph integration with spatial detour bridging; gravity-based accessibility and demand modeling; localized embodied/operational carbon accounting; and an LLM constrained to strategy formulation while simulation kernels validate budget, zoning, and capacity deltas.
- **Stack:** Python · FastAPI · GeoPandas · NetworkX · Shapely · MapLibre GL JS · Gemini

#### 🛸 [AeroControl](https://github.com/leehom22/drone-rescue) — Constrained Autonomous UAV Swarm Orchestration
*VHACK 2026 (Case Study 3) · Team Airost*
- **Problem:** Post-disaster search-and-rescue operations face communication blackouts, severe battery constraints, and deceptive sensor noise across degraded environments.
- **Architecture:** A decoupled, event-driven swarm control platform integrating an agentic OODA decision loop with simulation engines via the Model Context Protocol (FastMCP).
- **Key Engineering:** Information economy task separation (fast-scanning Scout drones for exploration vs. heavy Carrier drones reserved for high-probability targets); dynamic Bayesian probability grid updates combining multi-modal sensor inputs; wind and terrain-aware $A^*$ battery feasibility audits; and failure-tolerant recovery under simulated sensor jamming and node loss.
- **Stack:** Python · FastMCP · FastAPI · Vertex AI · React · TypeScript

---

### 🛠️ Tech Stack

- **Languages:** Python, TypeScript, Java, C++, SQL
- **AI & Systems Orchestration:** FastMCP, LangGraph, Vertex AI SDK, Gemini API， Agentic OODA Workflow
- **Backend & APIs:** FastAPI, Node.js, Express.js, PyTest
- **Databases & Cloud Data:** PostgreSQL (Supabase), Firebase, SQLite, MySQL
- **Libraries & Tools:** OpenCV,, scikit-learn, Pandas, numpy, Pydantic v2, Git, Docker, Vercel, Railway

---

<div align="center">

*Deterministic where possible. Probabilistic where useful. Traceable by design.*

</div>
