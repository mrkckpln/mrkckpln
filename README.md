# Software Engineer & AI Systems Architect

> Architecting resilient, high-throughput distributed backends, parameter-efficient LLM pipelines, and production-grade intelligent SaaS platforms.
<hr/>

<table>
  <tr>
    <td valign="top" width="54%">
      <h3>Selected Projects</h3>
      <ul>
        <li>
          <a href="https://github.com/OTU-Capstone-Project"><b>Rotakur: Unified Mobility & Fleet SaaS</b></a>
          <br />
          <i>Enterprise B2B Fleet Management + B2C Mobility Marketplace</i>
          <br />
          A resilient, multi-tenant hybrid system orchestrating enterprise fleet operations, corporate logistics, and public mobility bookings.
          <ul style="margin-top: 5px; margin-bottom: 5px; padding-left: 20px;">
            <li><b>AI Dispatch & Spatial Routing:</b> Engineered an NLP Smart Dispatcher (Gemini Flash + pgvector) to extract structured reservation profiles from raw chat text. Coupled with OSRM multi-stop road-network polyline decoding, dynamic geofencing, and strict POI validation to eliminate phantom bookings.</li>
            <li><b>Dual-Tenant Governance & P&L Engine:</b> Governs multi-entity corporate procurement via a locked state machine (DRAFT -> APPROVED) with strict data isolation. Integrated an AI Surge Pricing engine calculating real-time binding fares and exact Net P&L margins prior to trip onset.</li>
            <li><b>Regulatory Compliance & Telemetry:</b> Built a smart carpooling engine pairing B2C orders (±2h window / 20km radius) tracking DEFRA-compliant CO2 savings. Automates U-ETDS transport ministry reporting and executes UBL-TR 2.1 e-invoicing with DLQ-safe fallbacks.</li>
          </ul>
          <b>Stack:</b> <i>Python, FastAPI, SQLAlchemy 2.0, PostgreSQL, pgvector, WebSockets, Redis, OSRM, Docker</i>
        </li>
        <br />
        <li>
          <b>♟️AI Chess Intelligence & Analytics</b>
          <br />
          <i>Proprietary Hybrid-Engine B2C SaaS & OTB Tournament Platform</i>
          <br />
          High-performance analytics ecosystem bridging brute-force engine computation with abstract human positional and psychological understanding.
          <ul style="margin-top: 5px; margin-bottom: 5px; padding-left: 20px;">
            <li><b>Two-Tier Hybrid Engine:</b> Orchestrated an ultra-low-cost Tier-1 client exploration layer (Stockfish 16 NNUE Wasm, 0 DAK cost) and decoupled Tier-2 deep server analytics (RQ worker pool, depth 20+) protected by transactional credit (DAK) quotas.</li>
            <li><b>OTB Intelligence & Scouting:</b> Built custom telemetry modules parsing %clk zeitnot time-trouble, round-by-round cognitive fatigue curves, and automated FIDE profile scraping for pre-match tactical dossiers.</li>
            <li><b>Resilient Data Integrity:</b> Enforced composite uniqueness <code>(uploaded_by_id, checksum)</code> for collision-free multi-user archives and atomic SQL-level XP progression pipelines with zero Alembic schema drift.</li>
          </ul>
          <b>Stack:</b> <i>FastAPI, Next.js 15, PostgreSQL, Redis Queue (RQ), Stockfish 16 NNUE, WebAssembly, GPT-4o, fpdf2</i>
        </li>
        <br />
        <li>
          <b>👁️ Autonomous AI Sentry (Long-term Internship Project)</b>
          <br />
          <i>Real-Time Anomaly & Spatial Variance Perception</i>
          <br />
          An autonomous perception engine designed for millisecond-latency behavioral monitoring and spatial safety tracking in mission-critical environments.
          <ul style="margin-top: 5px; margin-bottom: 5px; padding-left: 20px;">
            <li><b>Perception Architecture:</b> Deployed YOLO-OBB and Pose architectures to infer anomalous trajectories, falls, and perimeter breaches with high temporal consistency.</li>
            <li><b>System Optimization:</b> Streamlined computational graphs and data pipelines on Arch/CachyOS to minimize memory footprint and maximize frame throughput.</li>
          </ul>
          <b>Stack:</b> <i>Python, PyTorch, OpenCV, Linux (CachyOS), FastAPI</i>
        </li>
      </ul>
    </td>
    <td valign="top" width="46%">
      <h3>Technical Focus</h3>
      <ul>
        <li><b>Distributed Systems & Data-Intensive Backends:</b> Designing resilient, concurrent services adhering to strict Router → Service → Repository patterns, ACID isolation, transactional state machines, and asynchronous worker queues (Redis/RQ).</li>
        <li><b>First-Principles Deep Learning & Mathematics:</b> Deconstructing computational graphs, reverse-mode autodiff engines, loss gradients (MSE, Cross-Entropy), adaptive optimizers (SGD to AdamW), and Transformer Self-Attention mechanics from scratch.</li>
        <li><b>Model Adaptation, PEFT & Alignment:</b> Modifying pretrained foundation architectures via Parameter-Efficient Fine-Tuning (LoRA, QLoRA 4-bit NF4, paged optimizers), instruction tuning (Alpaca/ShareGPT JSONL formatting), DPO alignment, and model compression (AWQ/GGUF).</li>
        <li><b>AI Engineering & High-Throughput Inference:</b> Architecting low-latency serving pipelines leveraging KV-caching, continuous batching (vLLM PagedAttention), Advanced Hybrid RAG (Dense HNSW + Sparse BM25 with Cross-Encoder reranking), and deterministic ReAct agentic workflows.</li>
      </ul>
      <br />
      <h3>Ongoing Development & Discipline</h3>
      <ul>
        <li><b>Systems Rigor (DDIA & Concurrency):</b> Systematically studying distributed consensus, replication strategies, and fault-tolerant data pipelines via Martin Kleppmann's DDIA and low-level concurrency models.</li>
        <li><b>Strategic System Foresight:</b> Translating 15+ years of licensed competitive chess expertise into engineering — proactively mitigating race conditions, architectural drift, and system bottlenecks before they manifest.</li>
        <li><b>First-Principles Mathematical Formulation:</b> Practicing the Feynman technique to deconstruct complex ML architectures, loss surfaces, and vector calculus into executable codebases from scratch.</li>
        <li><b>Multilingual Global Engineering:</b> Operating with professional fluency in English and actively acquiring German (B-level) for cross-border technical communication.</li>
      </ul>
    </td>
  </tr>
</table>

<h3>🛠 Tech Stack & Tooling</h3>
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/Alembic-000000?style=flat&logo=alembic&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js%2015-000000?style=flat&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React%2019-20232A?style=flat&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=flat&logo=webassembly&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/Linux-CachyOS%20%2F%20Arch-00CCFF?style=flat&logo=arch-linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
</p>

### 🏆 Credentials & Background
[![AI Engineer](https://img.shields.io/badge/DataCamp-Associate%20AI%20Engineer-2ea44f?logo=datacamp)](https://www.datacamp.com/certificate/AEDS0017948040137)
[![FIDE Profile](https://img.shields.io/badge/FIDE-Licensed%20Competitive%20Player-00529B?logo=chess&logoColor=white)](https://ratings.fide.com/profile/34583661)
