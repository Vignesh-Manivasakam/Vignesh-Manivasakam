<h1 align="center">👋 Hi, I'm Vignesh Manivasakam</h1>

<h3 align="center">R&D Digitalization Engineer · Automotive AI · Systems Engineering Automation</h3>

<p align="center">
  <a href="https://linkedin.com/in/vignesh-manivasakam"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:vicky.manivasagam@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Location-India%20%7C%20Open%20to%20Europe-1F5C99?style=for-the-badge"/>
</p>

---

## 🎯 What I'm Building

> **I automate the manual cognitive bottlenecks in automotive R&D workflows — using RAG pipelines, Agentic AI, and ML — so engineers can focus on engineering.**

I'm a Systems Engineer with 6+ years in automotive (EPS, Steer-by-Wire) who got frustrated watching skilled engineers spend weeks on tasks that AI can handle in hours. So I started building tools to fix that — one workflow stage at a time.

This GitHub is that body of work.

---

## 🗺️ The Big Picture — Automating the V-Model

Every project here maps to a real stage in the automotive systems engineering V-model. This isn't a collection of side projects — it's a **systematic attempt to build an AI layer on top of the engineering process.**

```mermaid
flowchart TD
    A(["📋 Customer\nRequirements"]):::customer

    subgraph LEFT ["⬅️  PHASE 2 · Current Focus — Requirements Engineering Automation (Bosch)"]
        B["📥 STEP 1 · Import\nPDF → RTF → DOORS\n🔧 PDF-DOORS Converter"]:::done
        C["🔍 STEP 2 · Similarity Check\nIs this req new or redundant?\n🤖 AI Similarity Assistant"]:::done
        D["🗂️ STEP 3 · Allocation\nWho owns this requirement?\n⚙️ ML Req Allocator"]:::wip
        E["✍️ STEP 4 · Authoring\nRequirement writing & refinement\n👥 Team Workflow"]:::team
        F["🛡️ STEP 5 · Review\nSafety · Verifiability · SOTIF\n🤖 Agentic AI Reviewer"]:::done
    end

    subgraph RIGHT ["➡️  PHASE 1 · Past Work — Test & Validation Automation (ZF Rane)"]
        G["📐 Test Planning\nDVP scheduling & rig allocation\n📊 Digital Test Lab System"]:::done
        H["🔬 Test Execution\nData acquisition & analysis\n📈 RLDA Analysis Tools"]:::done
        I["📄 Reporting\nRequest → Report digitization\n✅ Digital Test Lab System"]:::done
    end

    J(["🚗 Validated\nProduct"]):::customer

    A --> B --> C --> D --> E --> F
    F -. "System Integration" .-> G
    G --> H --> H --> I --> J

    classDef done fill:#1a7a4a,color:#fff,stroke:#145c37
    classDef wip fill:#b45309,color:#fff,stroke:#92400e
    classDef team fill:#374151,color:#fff,stroke:#1f2937
    classDef customer fill:#1F5C99,color:#fff,stroke:#174880
```

**Legend:**  🟢 Built & Live &nbsp;|&nbsp; 🟠 In Progress &nbsp;|&nbsp; ⚫ Team Ownership

---

## 📦 Project Portfolio

### ⬅️ Phase 2 — Requirements Engineering Automation

---

#### 🤖 AI Requirement Similarity Assistant
> *"Stop re-inventing requirements that already exist in your legacy projects."*

| | |
|---|---|
| **Problem** | Engineers manually compared new customer requirements against 10+ legacy projects — taking up to 15 days per review cycle |
| **Solution** | RAG pipeline that ingests PDF/Excel requirement files, generates embeddings, and surfaces semantically similar requirements from predecessor projects |
| **Key Innovation** | Built an Exact-Match Filter *before* semantic search — reducing API token usage by 40% |
| **Impact** | Review cycle cut from **15 days → 5 days (~65% reduction)** |
| **Tech** | `Python` `Azure OpenAI GPT-4` `LangChain` `FAISS` `Streamlit` |
| **Status** | ✅ Deployed internally · 🔗 Public POC available |

---

#### 🛡️ Agentic AI System Requirement Reviewer
> *"What if a safety expert reviewed every requirement before a human even saw it?"*

| | |
|---|---|
| **Problem** | Manual requirement reviews missed safety attributes, creating compliance gaps discovered late in the development cycle |
| **Solution** | Multi-agent system with specialized roles: Safety & Security Agent (ISO 26262 / SOTIF), Verifiability Agent, and a Data Layer for input refinement |
| **Impact** | **>90% recall** in identifying missing safety attributes vs. manual domain expert review |
| **Tech** | `Python` `Multi-Agent Systems` `Prompt Engineering` `LLMs` |
| **Status** | ✅ Built · Results validated against domain expert benchmark |

---

#### ⚙️ ML-Based Requirement Allocator *(In Progress)*
> *"Given a requirement, which system component or team should own it?"*

| | |
|---|---|
| **Problem** | Allocating customer requirements to the correct system/team is a manual, expert-dependent decision prone to inconsistency across projects |
| **Solution** | NLP classification model trained on historical allocation decisions to predict ownership with confidence scoring |
| **Approach** | Feature engineering on requirement text + metadata → classification pipeline with explainability layer |
| **Tech** | `Python` `NLP` `Scikit-learn` `Transformers` |
| **Status** | 🔄 In Progress — model training ongoing |

---

#### 📥 PDF → RTF → DOORS Import Converter
> *"The tool nobody talks about — but everyone needs."*

| | |
|---|---|
| **Problem** | Importing customer requirement PDFs into IBM DOORS required manual reformatting — a repetitive, error-prone process eating hours per project |
| **Solution** | Automated conversion pipeline: parse PDF structure → generate DOORS-compatible RTF → direct import ready |
| **Impact** | Reduced document preparation effort by **~80%** across the requirements team |
| **Tech** | `Python` `PDF Parsing` `RTF Generation` `DOORS Integration` |
| **Status** | ✅ Deployed internally · Sanitized version coming to GitHub |

---

### ➡️ Phase 1 — Test & Validation Automation *(ZF Rane)*

---

#### 📊 Digital Test Lab Management System
> *"From paper-based chaos to real-time digital test operations."*

| | |
|---|---|
| **Problem** | The entire test lifecycle — request, scheduling, execution, reporting — ran on paper and spreadsheets, causing delays and data loss |
| **Solution** | End-to-end digital system covering the full workflow: Request → Scheduling → Execution Tracking → Report Generation |
| **Role** | Project Lead & Process Architect — defined business logic, managed external dev team |
| **Impact** | Reduced paper-based processes by **80%** · Enabled real-time equipment utilization tracking |
| **Tech** | `System Architecture` `Process Design` `VBA` `Data Management` |
| **Status** | ✅ Deployed & live in production |

---

## 🏆 Beyond the Pipeline — Domain Exploration

#### 🚗 ADAS Object Detection for Indian Road Scenarios
> *Proving that automotive AI goes beyond NLP and text — into real-time perception.*

- Built an object detection model specifically trained and tuned for **Indian road conditions** — a significantly harder problem than standard Western road datasets due to road diversity, mixed traffic, and edge cases
- Tackled data challenges: class imbalance, occlusion, varied lighting across urban/rural scenarios
- **🥇 Won 1st Prize** at an internal innovation competition
- **Tech:** `Python` `Computer Vision` `Object Detection` `Deep Learning`

---

## 🛠️ Tech Stack

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure OpenAI-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/FAISS-Vector DB-00897B?style=flat-square"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG Pipeline-8B5CF6?style=flat-square"/>
<img src="https://img.shields.io/badge/Agentic AI-F59E0B?style=flat-square"/>
<img src="https://img.shields.io/badge/NLP-4CAF50?style=flat-square"/>
<img src="https://img.shields.io/badge/ISO 26262-1F5C99?style=flat-square"/>
<img src="https://img.shields.io/badge/ASPICE-1F5C99?style=flat-square"/>
<img src="https://img.shields.io/badge/IBM DOORS-052FAD?style=flat-square"/>
<img src="https://img.shields.io/badge/SOTIF-1F5C99?style=flat-square"/>
</p>

---

## 📈 What's Next

The V-model pipeline is taking shape on both sides. The natural next frontier:

- **Complete the ML Allocator** — close the gap between import and review
- **Right-side AI expansion** — applying AI to test data analysis and automated DVP generation
- **Pipeline integration** — connecting the individual tools into a unified requirements workflow

---

## 🤝 Let's Connect

I'm actively exploring roles in **R&D Digitalization**, **Automotive AI**, and **Systems Engineering Automation** — in India and Europe.

If you're working on similar problems, or hiring for teams that are — let's talk.

<p>
<a href="https://linkedin.com/in/vignesh-manivasakam"><img src="https://img.shields.io/badge/Connect on LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>
