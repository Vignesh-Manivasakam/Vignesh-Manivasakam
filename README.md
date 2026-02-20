<h1 align="center">👋 Hi, I'm Vignesh Manivasakam</h1>

<h3 align="center">R&D Digitalization Engineer &nbsp;·&nbsp; Automotive AI &nbsp;·&nbsp; Systems Engineering Automation</h3>

<p align="center">
  <a href="https://linkedin.com/in/vignesh-manivasakam"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:vicky.manivasagam@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/India%20%7C%20Open%20to%20Europe-1F5C99?style=for-the-badge&logo=googlemaps&logoColor=white"/>
</p>

---

## 🎯 What I'm Building

> **I automate the manual cognitive bottlenecks in automotive R&D workflows — using RAG pipelines, Agentic AI, and ML — so engineers can focus on engineering.**

I'm a Systems Engineer with 6+ years in automotive (EPS, Steer-by-Wire) who got frustrated watching skilled engineers spend weeks on tasks that AI can handle in hours. So I started building tools to fix that — one workflow stage at a time.

This GitHub is that body of work.

---

## 🗺️ The Big Picture — Automating the V-Model

Every project here maps to a real stage in the automotive systems engineering V-model. This isn't a collection of side projects — it's a **systematic attempt to build an AI layer on top of the engineering process.**

<p align="center">
  <img src="./vmodel.svg" alt="V-Model Automation Pipeline" width="100%"/>
</p>

> **Left side (Phase 2 · Current @ Bosch):** Automating the requirements engineering workflow — from customer input to reviewed, allocated, safety-validated requirements.
>
> **Right side (Phase 1 · Past @ ZF Rane):** Digitizing the test & validation workflow — from DVP planning through execution to report generation.

---

## 📦 Project Portfolio

### ⬅️ Phase 2 — Requirements Engineering Automation *(Bosch)*

---

#### 🤖 AI Requirement Similarity Assistant
> *"Stop re-inventing requirements that already exist in your legacy projects."*

| | |
|---|---|
| **Problem** | Engineers manually compared new customer requirements against 10+ legacy projects — taking up to 15 days per review cycle |
| **Solution** | RAG pipeline that ingests PDF/Excel requirement files, generates embeddings, and surfaces semantically similar requirements from predecessor projects |
| **Key Innovation** | Exact-Match Filter *before* semantic search — reducing API token usage by 40% |
| **Impact** | Review cycle cut from **15 days → 5 days (~65% reduction in lead time)** |
| **Tech** | `Python` `Azure OpenAI GPT-4` `LangChain` `FAISS` `Streamlit` |
| **Status** | ✅ Deployed internally · 🔗 Public POC on this GitHub |

---

#### 🛡️ Agentic AI System Requirement Reviewer
> *"What if a safety expert reviewed every requirement before a human even saw it?"*

| | |
|---|---|
| **Problem** | Manual reviews missed safety attributes, creating ISO 26262 compliance gaps found late in development |
| **Solution** | Multi-agent system: Safety & Security Agent (ISO 26262/SOTIF), Test Verifiability Agent, Data Layer for input refinement |
| **Impact** | **>90% recall** identifying missing safety attributes vs. manual domain-expert review |
| **Tech** | `Python` `Multi-Agent Systems` `Prompt Engineering` `LLMs` |
| **Status** | ✅ Built · Validated against domain expert benchmark |

---

#### ⚙️ ML-Based Requirement Allocator *(In Progress)*
> *"Given a requirement, which system component or team should own it?"*

| | |
|---|---|
| **Problem** | Allocating customer requirements to the correct system/team is a manual, expert-dependent decision — inconsistent across projects |
| **Solution** | NLP classification model trained on historical allocation decisions to predict ownership with confidence scoring |
| **Tech** | `Python` `NLP` `Scikit-learn` `Transformers` |
| **Status** | 🔄 In Progress — model training ongoing |

---

#### 📥 PDF → RTF → DOORS Import Converter
> *"The tool nobody talks about — but everyone needs."*

| | |
|---|---|
| **Problem** | Importing customer requirement PDFs into IBM DOORS required manual reformatting — repetitive, error-prone, hours per project |
| **Solution** | Automated pipeline: parse PDF structure → generate DOORS-compatible RTF → import ready |
| **Impact** | Document preparation effort reduced by **~80%** across the requirements team |
| **Tech** | `Python` `PDF Parsing` `RTF Generation` `DOORS Integration` |
| **Status** | ✅ Deployed internally · Sanitized open-source version coming soon |

---

### ➡️ Phase 1 — Test & Validation Automation *(ZF Rane)*

---

#### 📊 Digital Test Lab Management System
> *"From paper-based chaos to real-time digital test operations."*

| | |
|---|---|
| **Problem** | The full test lifecycle — request, scheduling, execution, reporting — ran on paper and spreadsheets, causing delays and data loss |
| **Solution** | End-to-end digital system: Request → Scheduling → Execution Tracking → Report Generation |
| **Role** | Project Lead & Process Architect — defined business logic, managed external development team |
| **Impact** | Paper-based processes reduced by **80%** · Real-time equipment utilization tracking enabled |
| **Tech** | `System Architecture` `Process Design` `VBA` `Data Management` |
| **Status** | ✅ Deployed & live in production |

---

## 🏆 Beyond the Pipeline — Domain Exploration

#### 🚗 ADAS Object Detection for Indian Road Scenarios
> *Proving that automotive AI goes beyond NLP — into real-time perception.*

- Built an object detection model tuned specifically for **Indian road conditions** — a harder problem than standard datasets due to traffic diversity, occlusion, and edge cases
- Tackled class imbalance, varied lighting, and mixed urban/rural scenarios
- **🥇 Won 1st Prize** at an internal innovation competition
- **Tech:** `Python` `Computer Vision` `Object Detection` `Deep Learning`

---

## 🛠️ Tech Stack at a Glance

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure_OpenAI-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/FAISS_Vector_DB-00897B?style=flat-square"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG_Pipeline-8B5CF6?style=flat-square"/>
<img src="https://img.shields.io/badge/Agentic_AI-F59E0B?style=flat-square"/>
<img src="https://img.shields.io/badge/NLP-4CAF50?style=flat-square"/>
<img src="https://img.shields.io/badge/ISO_26262-1F5C99?style=flat-square"/>
<img src="https://img.shields.io/badge/ASPICE-1F5C99?style=flat-square"/>
<img src="https://img.shields.io/badge/IBM_DOORS-052FAD?style=flat-square"/>
<img src="https://img.shields.io/badge/SOTIF-1F5C99?style=flat-square"/>
</p>

---

## 📈 What's Next

- **Complete the ML Allocator** — close the gap between import and review stages
- **Right-side AI expansion** — automated test data analysis and AI-assisted DVP generation
- **Pipeline integration** — connecting individual tools into a unified, end-to-end requirements workflow

---

## 🤝 Let's Connect

I'm actively exploring roles in **R&D Digitalization**, **Automotive AI**, and **Systems Engineering Automation** — in India and open to Europe.

<p>
<a href="https://linkedin.com/in/vignesh-manivasakam"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>
