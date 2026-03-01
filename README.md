<h1 align="center">👋 Hi, I'm Vignesh Manivasakam</h1>

<h3 align="center">R&D Digitalization Engineer &nbsp;·&nbsp; Automotive AI &nbsp;·&nbsp; GenAI & Agentic Systems</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/vignesh-manivasakam-17b0a2128/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:vicky.manivasagam@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/Vignesh-Manivasakam"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

## ⚡ TL;DR — What I Do

> **6+ years in automotive systems engineering (EPS, Steer-by-Wire) × AI/ML — I build production-grade AI tools that eliminate manual bottlenecks inside the automotive V-Model.**
> Currently automating Requirements Engineering @ Bosch. Previously digitalized the full Test & Validation lifecycle @ ZF Rane.

---

## 🏆 Impact at a Glance

| Metric | Result |
|---|---|
| ⏱️ Lead time reduction (Requirement Reviews) | **15 days → 5 days (65% cut)** |
| 💰 Cost avoidance across 3 global OEM programs | **$8,880 USD + 280 engineering hours saved** |
| ♻️ NFR reusability improvement (10+ projects) | **>80% increase** |
| 📄 Paper-based process reduction | **80% paperless** |
| 🛡️ Safety attribute recall vs. manual expert review | **>90%** |
| 🥇 ADAS Hackathon | **1st Prize — YOLOv8 on Indian Roads** |

---

## 🗺️ The Big Picture — Automating the Automotive V-Model

<p align="center">
  <img src="./vmodel.svg" alt="Automotive V-Model Automation Map" width="100%"/>
</p>

| Phase | Company | Period | Focus |
|---|---|---|---|
| **Phase 2 (Current)** | Bosch | 2023–Present | Requirements Engineering Automation |
| **Phase 1** | ZF Rane | 2019–2023 | Test & Validation Digitalization |

---

## 📦 Project Portfolio

### ⬅️ Phase 2 — Requirements Engineering @ Bosch

---

#### 📥 Step 1 · PDF → RTF → DOORS Import Converter

> *"The tool nobody talks about — but every requirements engineer desperately needs."*

| | |
|---|---|
| **Problem** | Importing customer PDFs into IBM DOORS required manual reformatting — hours of error-prone work per project |
| **Solution** | Automated pipeline: PDF parse → DOORS-compatible RTF → human-in-loop import |
| **Impact** | **~70% reduction** in document preparation effort |
| **Tech** | `Python` `PDF Parsing` `RTF Generation` `IBM DOORS` |
| **Status** | ![Internal](https://img.shields.io/badge/DEPLOYED-INTERNAL-grey) Confidential — metrics shared |

---

#### 🔍 Step 2 · AI Requirement Similarity Assistant

> *"Stop re-inventing requirements that already exist in your legacy projects."*

| | |
|---|---|
| **Problem** | Engineers manually compared incoming requirements against 10+ legacy projects — up to 15 days per cycle, zero consistency |
| **Solution** | RAG pipeline ingesting PDF/Excel files, with an **Exact-Match Filter before semantic search** (cutting API token usage by 40%) |
| **Impact** | **65% lead-time cut** · **$8,880 cost avoidance** · **280 engineering hours saved** across 3 OEM programs |
| **Tech** | `Python` `Azure OpenAI GPT-4` `RAG` `FAISS` `Streamlit` |
| **Status** | ![Live](https://img.shields.io/badge/LIVE-green) Deployed internally · 🔗 [Public POC](https://github.com/Vignesh-Manivasakam/Requirement-Similarity-Assistant-POC) |

---

#### ⚙️ Step 3 · ML-Based Requirement Allocator *(In Progress)*

> *"Once you know a requirement is valid — who should own it?"*

| | |
|---|---|
| **Problem** | Requirement-to-component allocation is a manual, expert-dependent decision — inconsistent across projects and OEMs |
| **Solution** | NLP classifier trained on historical allocation data to predict ownership with a confidence score |
| **Tech** | `Python` `NLP` `Scikit-learn` `Transformers` `LLMs` |
| **Status** | ![In Progress](https://img.shields.io/badge/IN%20PROGRESS-orange) Model training ongoing |

---

#### 🛡️ Step 4 · Agentic Multi-Domain Requirement Reviewer *(POC)*

> *"Safety expert + Test engineer + Architect — reviewing every requirement simultaneously, before a human sees it."*

| | |
|---|---|
| **Problem** | Manual reviews missed safety attributes and consumed significant time in the development cycle |
| **Solution** | Multi-agent system: Safety & Security Agent (ISO 26262) + Test Verifiability Agent + Data Layer orchestration |
| **Impact** | **>90% recall** on missing safety attributes vs. domain-expert manual review |
| **Tech** | `Python` `LangGraph` `Multi-Agent Systems` `Prompt Engineering` `LLMs` |
| **Status** | ![POC Built](https://img.shields.io/badge/POC%20BUILT-blue) Validated against domain-expert benchmark |

---

### ➡️ Phase 1 — Test & Validation @ ZF Rane

---

#### 📊 Step 5 · Digital Test Lab Management System

> *"From paper-based chaos to real-time digital test operations."*

| | |
|---|---|
| **Problem** | The entire test lifecycle — request, scheduling, execution, reporting — ran on paper and spreadsheets |
| **Solution** | End-to-end system: Request → Scheduling → Execution Tracking → Automated Report Generation |
| **Role** | **Project Lead & Process Architect** — defined business logic, system architecture, managed external dev team |
| **Impact** | **80% paperless** · Real-time equipment utilization tracking across the test organization |
| **Tech** | `Process Design` `.NET` `Data Management` |
| **Status** | ![Live](https://img.shields.io/badge/LIVE-green) Deployed in production |

---

## 🏅 Beyond the Pipeline

#### 🚗 ADAS Object Detection for Indian Road Scenarios

- YOLOv8m trained on IDD dataset with progressive resolution + heavy weather augmentation
- **mAP@50-95: 0.420 · Precision: 0.773 · Recall: 0.569**
- Addressed class imbalance, occlusion, and mixed urban/rural traffic — uniquely hard vs. standard benchmarks
- **🥇 1st Prize** — Internal ADAS Innovation Hackathon
- 🔗 [Full Repository](https://github.com/Vignesh-Manivasakam/ADAS-Object-Detection-Indian-Roads)

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure_OpenAI-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white"/>
  <img src="https://img.shields.io/badge/RAG_Pipeline-8B5CF6?style=flat-square"/>
  <img src="https://img.shields.io/badge/Agentic_AI-F59E0B?style=flat-square"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square"/>
  <img src="https://img.shields.io/badge/FAISS_Vector_DB-00897B?style=flat-square"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/YOLOv8-00C9FF?style=flat-square"/>
  <img src="https://img.shields.io/badge/NLP-4CAF50?style=flat-square"/>
  <img src="https://img.shields.io/badge/ISO_26262-1F5C99?style=flat-square"/>
  <img src="https://img.shields.io/badge/ASPICE-1F5C99?style=flat-square"/>
  <img src="https://img.shields.io/badge/IBM_DOORS-052FAD?style=flat-square"/>
</p>

---

## 📈 What's Next

- 🔄 Complete the **ML Requirement Allocator** — close the gap between import and review stages
- 🔬 Expand **right-side AI** — automated test data analysis & AI-assisted DVP generation
- 🔗 **Pipeline integration** — connecting all tools into a unified, end-to-end requirements workflow

---

## 🤝 Let's Connect

**Actively seeking roles in R&D Digitalization · GenAI Systems Engineering · Automotive AI** *(open to relocation)*

If you're building next-gen automotive R&D platforms — let's talk.

<p align="center">
  <a href="https://www.linkedin.com/in/vignesh-manivasakam-17b0a2128/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

<p align="center"><sub>Built with ❤️ for safer, faster, and smarter automotive engineering</sub></p>
