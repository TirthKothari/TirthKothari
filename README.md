<div align="center">

  <h1>Hey there, I'm <a href="https://github.com/TirthKothari">Tirth Kothari</a> 👋</h1>
  <p><b>Software Developer &bull; Backend & Distributed Systems &bull; AI / ML Infrastructure</b></p>
  <p><i>Specializing in Python & Django ecosystems, high-concurrency distributed workflows, and backend architectures for AI/LLM models.</i></p>

  <br/>

  <!-- Fast Access Badges (100% Reliable Shields.io CDN) -->
  <a href="mailto:tirth.n.kothari@gmail.com">
    <img src="https://img.shields.io/badge/Email-tirth.n.kothari%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/tirthkothari/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://github.com/TirthKothari">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Location-Mumbai%2C%20India-0284C7?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />

  <br/><br/>

  <!-- Target Roles Badges -->
  <img src="https://img.shields.io/badge/Target%20Roles-Python%20Developer%20%7C%20Backend%20Engineer%20%7C%20Software%20Developer%20%7C%20AI%2FML%20Engineer%20%7C%20Cloud%20Engineer-6366F1?style=flat-square" alt="Target Roles" />

</div>

---

### 💡 About Me

I am a **Software Developer** with a deep focus on **Python & Django backends**, distributed systems, and cloud infrastructure. I have hands-on startup experience designing and deploying high-concurrency microservices, automated cloud virtualization pipelines, and real-time streaming architectures.

- 🐍 **Primary Language & Framework**: **Python** is my core language, and **Django / Django REST Framework** is my primary framework for engineering enterprise-grade, clean-architecture backends.
- ⚡ **Distributed Systems & Concurrency**: Experienced with **Celery**, **Redis** (atomic Lua scripting), and **WebSockets** for building real-time, event-driven pipelines that prevent race conditions.
- 🧠 **Currently Exploring**: Actively diving into **Backend Systems for AI Models & Large Language Models (LLMs)** — investigating high-throughput model serving architectures, agentic orchestration, streaming token backends, and vector search indexing.
- ☁️ **Cloud & Virtualization**: Skilled in containerizing and orchestrating services with **Docker** and **Kubernetes** on **GCP** & **AWS**, including hardware-accelerated **KVM** virtualization.
- 🎓 **Education**: Pursuing B.Tech in Information Technology (**Honors in Artificial Intelligence & Machine Learning**) at **K.J. Somaiya Institute of Technology**, Mumbai.

---

### 🎯 Core Roles & Competencies

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                                   CORE COMPETENCIES                                    │
├──────────────────────────┬─────────────────────────────┬───────────────────────────────┤
│ 🐍 Python / Backend      │ ☁️ Cloud & Distributed      │ 🤖 AI / ML Systems            │
│  • Django & DRF (Core)   │  • Celery & Redis Queues    │  • LLM Backend Systems        │
│  • FastAPI & Flask       │  • Docker & Kubernetes (K8s)│  • Gemini & OpenAI APIs       │
│  • GeoDjango & PostGIS   │  • KVM Virtualization (GCP) │  • PaddleOCR Document Parsing │
│  • REST APIs & JWT Auth  │  • OpenResty / Nginx & Lua  │  • Computer Vision (OpenCV)   │
│  • Razorpay Payments     │  • GitHub Actions CI/CD     │  • LangChain & Vector Search  │
└──────────────────────────┴─────────────────────────────┴───────────────────────────────┘
```

---

### 🛠️ Tech Stack & Tooling

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,django,fastapi,flask,react,js,postgres,mysql,mongodb,redis,docker,kubernetes,gcp,aws,nginx,linux,git,githubactions,tensorflow,postman&perline=10" alt="Tech Stack Ribbon" />
</div>

<br/>

<details open>
<summary><b>📂 Categorized Technical Proficiency</b></summary>
<br/>

| Category | Technologies & Tools |
| :--- | :--- |
| **Core Languages** | `Python (Primary)` `JavaScript` `C` `C++` `SQL` `Lua` |
| **Backend Frameworks** | `Django (Primary)` `Django REST Framework (DRF)` `FastAPI` `Flask` `Node.js` |
| **Frontend Frameworks** | `React.js` `HTML5` `CSS3` `JavaScript (ES6+)` |
| **Distributed Systems & Concurrency** | `Celery` `Redis (In-Memory & Lua Scripting)` `Django Channels (WebSockets)` |
| **Databases & Storage** | `PostgreSQL (PostGIS Spatial Queries)` `MySQL` `MongoDB` `AWS S3` `Backblaze B2` |
| **Cloud, DevOps & Virtualization** | `Docker` `Kubernetes` `Google Cloud Platform (GCP)` `AWS` `Nginx` `OpenResty` `Linux / KVM` `GitHub Actions (CI/CD)` |
| **AI, Machine Learning & OCR** | `LLM Integrations (Gemini, OpenAI)` `PaddleOCR` `LangChain` `TensorFlow` `Scikit-Learn` `OpenCV` `MediaPipe` `FAISS` |
| **Automation & QA Testing** | `Playwright` `Selenium` `Appium` `Sikuli` `Python Scripting` |

</details>

---

### 🚀 Featured Engineering Projects

#### 1. 🏢 [ErgoSpace — Workspace Booking & Geospatial Reservation Engine](https://github.com/TirthKothari)
> *Scalable co-working and café discovery platform powered by GeoDjango spatial search and dynamic availability handling.*

```
               [ Client Applications ]
                         │
                         ▼
        [ Django / DRF Application Layer ]
         ├── JWT Authentication & Provider Permissions
         ├── Booking & Availability State Machine (Hourly/Daily/Monthly)
         └── Razorpay Payment Gateway & Cryptographic Signature Verification
                         │
        ┌────────────────┴────────────────┐
        ▼                                 ▼
[ PostgreSQL + PostGIS ]          [ Provider Portal & Asset S3 ]
(Spatial Radius Indexing & Filter) (Listings, Pricing & Revenue Tracking)
```

- **Geospatial Search Engine**: Implemented location-based discovery using **GeoDjango** and **PostgreSQL/PostGIS**, enabling fast distance-based radius queries for workspaces and cafes.
- **Dynamic Pricing & Booking Workflows**: Built booking state machines featuring seat layout selection, dynamic pricing tiers (hourly, daily, and monthly), and conflict-free availability locks.
- **Payment Verification**: Integrated **Razorpay Payment Gateway** with server-side order creation and cryptographic signature verification to ensure secure transactions.
- **Provider Dashboard APIs**: Created a complete API suite for workspace owners to manage amenities, seat configurations, photo uploads, pricing rules, and revenue analytics.
- **Stack**: `Python` • `Django` • `Django REST Framework` • `PostgreSQL` • `PostGIS` • `GeoDjango` • `Razorpay` • `Redis`

---

#### 2. 💼 [KACU — Full-Stack Business Loan Application & Workflow Platform](https://github.com/TirthKothari)
> *Comprehensive loan origination platform featuring a React frontend, Django REST API backend, 4-tier RBAC, and automated CI/CD.*

- **Full-Stack Architecture**: Developed both the **React** client application and the complete **Django REST Framework** backend for end-to-end loan application lifecycle management.
- **Fine-Grained RBAC**: Designed Role-Based Access Control enforcing strict separation of permissions across 4 distinct tiers: **Applicants**, **Loan Agents**, **Financial Partners**, and **Administrators**.
- **Stateful Application Pipelines**: Engineered multi-step submission workflows handling company verification, funding requirements, identity verification, and multi-stage approval/rejection workflows.
- **Secure Document Storage**: Integrated **Backblaze B2** (S3-compatible object storage) for tamper-evident storage and encrypted retrieval of confidential loan documents.
- **Automated Multi-Service CI/CD**: Established automated **GitHub Actions** deployment pipelines deploying React to **Vercel**, Django to **Render**, and database to **Aiven (Managed PostgreSQL)**.
- **Stack**: `React.js` • `Python` • `Django` • `Django REST Framework` • `PostgreSQL (Aiven)` • `Backblaze B2` • `GitHub Actions`

---

#### 3. 🔍 [Precise Extract — AI Document Table Extraction & Natural Language Query System](https://github.com/TirthKothari)
> *Intelligent document parsing engine transforming unstructured PDFs and images into databases with a natural-language-to-SQL query interface.*

- **Tabular OCR Pipeline**: Built an asynchronous extraction service with **FastAPI** and **Flask** that parses complex, multi-page PDFs and scanned document images into structured tabular data using **PaddleOCR**.
- **Bulk Ingestion & Persistence**: Engineered a secure backend pipeline to process bulk file uploads and persist validated tabular records into **MySQL**.
- **LLM-Powered SQL Synthesis**: Integrated **Google Gemini** and **OpenAI ChatGPT** APIs to translate plain-English business questions into executable SQL queries, enabling real-time querying and one-click **Excel export**.
- **Stack**: `FastAPI` • `Flask` • `PaddleOCR` • `Gemini API` • `OpenAI API` • `MySQL` • `Pandas` • `Python`

---

#### 4. 🤖 [Cloud Emulator & Automated Test Infrastructure](https://github.com/TirthKothari)
> *Cloud-native Android virtualization cluster and real-time streaming infrastructure for AI-driven test execution.*

- **KVM-Accelerated Cloud Emulation**: Built containerized Android emulator infrastructure deployed on **GCP** using **Docker** and **Kubernetes**, leveraging Kernel-based Virtual Machine (**KVM**) for accelerated hardware execution.
- **Atomic Concurrency Control**: Implemented distributed task orchestration using **Celery** and **Redis**, authoring atomic **Redis Lua scripts** to eliminate race conditions during concurrent virtual device allocation.
- **Real-Time Video Streaming Gateway**: Architected an **Nginx/OpenResty** reverse proxy with custom **Lua scripts** for authenticated, low-latency routing of live emulator video streams alongside **Django Channels** and **WebSockets**.
- **Autonomous Testing**: Integrated **Appium** into an open-source testing framework, enabling natural-language commands to drive cross-platform Android and browser UI testing.
- **Stack**: `Docker` • `Kubernetes` • `GCP` • `KVM` • `Celery` • `Redis Lua` • `Django Channels` • `OpenResty` • `Appium`

---

### ⚡ Automation & Utility Tools

| Project | Overview & Architecture | Technologies |
| :--- | :--- | :--- |
| 📸 **InstaBot** | Python-based social automation bot featuring session handling, automated interaction pipelines, and task scheduling with anti-rate-limit throttling. | `Python` `Automation Scripting` `Requests` `Selenium` |
| ☁️ **AWS re/Start Automation** | Automation toolset developed to orchestrate, provision, and manage cloud lab resources and recurring workflows for AWS re/Start environments. | `Python` `AWS CLI` `Boto3` `Bash Scripting` |

---

### 💼 Experience

#### **Backend Engineer Intern** | **BugOwl AI** *(Startup)*
*Jun 2025 – Dec 2025 • Mumbai, India*

- **Platform Architecture**: Led a team of 3 engineers in developing the backend architecture for an AI-powered QA automation platform using **Python** and **Django**, enabling natural-language-driven browser and mobile test execution.
- **Concurrency & Task Processing**: Engineered asynchronous task pipelines using **Celery** and **Redis**, writing atomic **Redis Lua scripts** to resolve concurrency bottlenecks and race conditions during on-demand emulator provisioning.
- **Cloud Infrastructure & KVM**: Built and deployed scalable Android emulator infrastructure on **GCP** using **Docker** and **Kubernetes**, utilizing **KVM** for hardware-accelerated device virtualization.
- **Real-Time Video Gateway**: Implemented real-time communication via **Django Channels** and **WebSockets**, and built an **Nginx/OpenResty** reverse proxy using **Lua** for authenticated routing of live emulator video streams.
- **Test Automation Integration**: Extended an open-source testing engine with **Appium** to support automated Android application testing.

---

### 🏆 Hackathon Achievements & Awards

| Event | Organization / Institution | Project & Contribution |
| :--- | :--- | :--- |
| 🥇 **CODEVERSE '23 Hackathon** *(24-Hour)* | Vidyavardhini’s Bhausaheb Vartak Polytechnic | Engineered a computer vision application in Python translating sign language gestures into text in real time. |
| 🏅 **DATAHACK 2.0 Hackathon** *(24-Hour)* | Dwarkadas J. Sanghvi College of Engineering | Developed an AI-powered recommendation system matching legal cases with suitable legal counsel based on case attributes. |

---

### 🎓 Education

- **Bachelor of Technology (B.Tech) in Information Technology**
  - **K.J. Somaiya Institute of Technology**, Mumbai | *2024 – 2027 (Expected)*
  - **Honors**: Artificial Intelligence and Machine Learning

- **Diploma in Computer Engineering**
  - **Shri Bhagubhai Mafatlal Polytechnic**, Mumbai | *2021 – 2024*

---

### 📬 Connect & Collaborate

<div align="center">

  <p>Looking for a Software Developer with strong foundations in Python, Django, Distributed Systems, or AI/ML Backends? Let's talk!</p>

  <a href="mailto:tirth.n.kothari@gmail.com">
    <img src="https://img.shields.io/badge/Email-tirth.n.kothari%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/tirthkothari/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/TirthKothari">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>

</div>
