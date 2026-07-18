# Software Engineer & Focused on AI Automation

> Architecting secure, high-performance, and data-driven intelligent systems across Software 2.0 and MLOps.
<hr/>

<table>
  <tr>
    <td valign="top" width="54%">
      <h3>Projects</h3>
      <ul>
        <li>
          <a href="https://github.com/OTU-Capstone-Project"><b> Rotakur: Unified Mobility & Fleet SaaS</b></a>
          <br />
          <i>Graduation Project — Enterprise B2B SaaS + B2C Marketplace</i>
          <br />
          A resilient, multi-tenant hybrid system orchestrating corporate fleet operations, organization event logistics, and public mobility bookings.
          <ul style="margin-top: 5px; margin-bottom: 5px; padding-left: 20px;">
            <li><b>AI Dispatch & Spatial Routing:</b> Deployed an NLP Smart Dispatcher (Gemini 2.5 Flash + pgvector) to extract structured reservation profiles from raw chat text. Coupled with OSRM multi-stop road-network polyline decoding, dynamic geofencing, and strict POI constraints (airports/terminals) to eliminate phantom bookings.</li>
            <li><b>Dual-Tenant Governance & P&L Engine:</b> Governs multi-entity corporate procurement via a locked state machine (DRAFT -> APPROVED) with strict data isolation. Integrated an AI Surge Pricing engine calculating real-time binding fares and exact Net P&L margins (fuel + depreciation) prior to trip onset.</li>
            <li><b>Sustainability & Regulatory Compliance:</b> Built a smart carpooling matching engine pairing B2C orders (within ±2h window / 20km radius) to track DEFRA-compliant CO2 savings for ESG reporting. Automates U-ETDS reporting for the Turkish Ministry of Transport and executes UBL-TR 2.1 e-invoicing via DLQ-safe fallbacks.</li>
          </ul>
          <b>Stack:</b> <i>Python, FastAPI, SQLAlchemy 2.0, PostgreSQL, pgvector, WebSockets, Redis, OSRM, Docker</i>
        </li>
        <br />
        <li>
          <b>👁️ Autonomous AI Sentry (AI Bekçi)</b>
          <br />
          <i>Edge CV · Millisecond Anomaly & Environmental Variance Detection</i>
          <br />
          An intelligent autonomous perception engine designed to act as an unblinking AI Sentry in critical environments.
          <ul style="margin-top: 5px; margin-bottom: 5px; padding-left: 20px;">
            <li><b>Sentry Architecture:</b> Deployed YOLOv11-OBB and YOLO-Pose models to infer behavioral anomalies, falls, and environmental variations within milliseconds.</li>
            <li><b>HPC Optimization:</b> Fully accelerated via TensorRT FP16 quantization and CUDA execution layers to minimize edge latency and maximize hardware throughput.</li>
          </ul>
          <b>Stack:</b> <i>C++, Python, PyTorch, TensorRT, CUDA, FastAPI, Next.js</i>
        </li>
        <br />
        <li>
          <b>♟️ Intelligent Chess Workstation</b>
          <br />
          <i>Asynchronous Multi-Tenant Micro-SaaS</i>
          <br />
          AI-driven analytics platform bridging brute-force engine data with abstract human positional understanding.
          <ul style="margin-top: 5px; margin-bottom: 5px; padding-left: 20px;">
            <li><b>Async Core:</b> Engineered a decoupled Redis Queue (RQ) pipeline for per-ply Stockfish and LLM analysis.</li>
            <li><b>Advanced Reports:</b> Generated grandmaster-level heuristic feedback alongside publication-quality PDFs.</li>
          </ul>
          <b>Stack:</b> <i>Python, FastAPI, Next.js 15, Redis, Stockfish, OpenAI/Gemini API, fpdf2</i>
        </li>
        <br />
        <li>
          <a href="https://github.com/Otu-Data-ML-Projects/LegalLens"><b>⚖️ LegalLens — AI Contract Analyzer</b></a>
          <br />
          <i>Neural Network Chrome Extension</i>
          <br />
          Detects high-risk clauses using a custom <b>Bi-LSTM + Attention</b> model and Google Gemini for deep summary.
          <br />
          <b>Stack:</b> <i>Python, PyTorch, FastAPI, Chrome API</i>
        </li>
      </ul>
    </td>
    <td valign="top" width="46%">
      <h3>Technical Focus</h3>
      <ul>
        <li><b>Distributed Systems & Multi-Tenant SaaS:</b> Engineering asynchronous, high-concurrency backend infrastructures with FastAPI, SQLAlchemy 2.0, and robust tenant-isolated PostgreSQL databases.</li>
        <li><b>Production-Grade AI & Edge CV:</b> Constructing end-to-end computer vision pipelines (YOLO-OBB/Pose) and custom sequential models structured for real-time inference in critical environments.</li>
        <li><b>Inference Optimization & HPC:</b> Optimizing deep learning models via TensorRT FP16 quantization, minimizing latency, and maximizing hardware throughput utilizing CUDA acceleration.</li>
        <li><b>Spatial Computing & Telemetry:</b> Designing custom multi-stop routing logic, geographic validation systems (OSRM), and live operational telemetry pipelines via persistent WebSockets in Rotakur.</li>
      </ul>
      <br />
      <h3>Ongoing Development & Discipline</h3>
      <ul>
        <li><b>Agentic Engineering:</b> Architecting strict system guidelines and advanced prompt workflows to orchestrate AI-assisted development across large-scale production codebases.</li>
        <li><b>Strategic System Foresight:</b> Translating professional-level chess foresight (15+ years, 2000 FIDE) into software engineering — anticipating architectural edge cases, race conditions, and system bottlenecks before they occur.</li>
        <li><b>High-Performance Architectures:</b> Deepening expertise in hardware-level performance tuning, Linux-native optimizations, and high-throughput data processing layers using Modern C++.</li>
      </ul>
    </td>
  </tr>
</table>

<h3>🛠 My Tech Stack</h3>
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/YOLOv11-00A65A?style=flat&logo=ultralytics&logoColor=white" />
  <img src="https://img.shields.io/badge/NVIDIA_CUDA-76B900?style=flat&logo=nvidia&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon_S3-569A31?style=flat&logo=amazon-s3&byteColor=white" />
  <br>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/CachyOS-Arch_Based-00CCFF?style=flat&logo=arch-linux&logoColor=white" />
</p>

### 🏆 Certifications & Achievements
[![AI Engineer](https://img.shields.io/badge/DataCamp-Associate%20AI%20Engineer-2ea44f?logo=datacamp)](https://www.datacamp.com/certificate/AEDS0017948040137)
[![FIDE Profile](https://img.shields.io/badge/FIDE-Profile-00529B?logo=chess&logoColor=white)](https://ratings.fide.com/profile/34583661)
