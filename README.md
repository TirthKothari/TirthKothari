<div align="center">

  <h1>Hi there, I'm <a href="https://github.com/TirthKothari">Tirth Kothari</a> 👋</h1>
  <p><b>Software Engineer &bull; Backend & Distributed Systems &bull; Applied AI</b></p>
  <p><i>Building high-throughput APIs, scalable distributed workflows, and intelligent applications.</i></p>

  <br/>

  <!-- Status & Quick Contact Badges (100% Reliable Shields.io CDN) -->
  <a href="mailto:tirth.n.kothari@gmail.com">
    <img src="https://img.shields.io/badge/Email-tirth.n.kothari%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://linkedin.com/in/tirthkothari" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/TirthKothari">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <img src="https://img.shields.io/badge/Location-Mumbai%2C%20India-blue?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Focus-Backend%20%26%20Distributed%20Systems-6366F1?style=flat-square" alt="Focus" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-blueviolet?style=flat-square" alt="Status" />

</div>

---

### 👨‍💻 About Me

I am a **Software Engineer** specializing in backend development, distributed systems, and applied AI. I focus on building scalable web architectures, resilient microservices, and high-concurrency event-driven workflows.

- 🚀 **Industry Experience**: Hands-on experience working in a fast-paced AI startup environment—architecting containerized emulator infrastructure with Kubernetes & KVM, low-latency live streaming gateways with OpenResty/Lua, and asynchronous task queues with Celery & Redis.
- 🛠️ **Full-Lifecycle Backend**: Strong expertise in designing robust RESTful APIs with **Python (Django, FastAPI, Flask)**, implementing fine-grained RBAC, and integrating third-party systems (payment gateways, cloud storage, LLM APIs).
- 📍 **Data & Storage**: Skilled with **PostgreSQL (PostGIS spatial queries)**, **MySQL**, **MongoDB**, and **Redis** for in-memory caching and atomic operations.
- 🎓 **Education**: Pursuing B.Tech in Information Technology (**Honors in Artificial Intelligence and Machine Learning**) at **K.J. Somaiya Institute of Technology**.
- 🏆 **Hackathons**: 2x 24-Hour Hackathon Winner/Finalist (Codeverse '23, DataHack 2.0).

---

### ⚡ Core Technical Competencies

<div align="center">

| Domain | Key Skills & Architectures |
| :--- | :--- |
| **Backend & APIs** | Scalable REST APIs, Clean Architecture, Role-Based Access Control (RBAC), WebSockets / Real-Time Streams, Payment Integrations |
| **Distributed Systems & Concurrency** | Asynchronous Task Queues (Celery), In-Memory Caching & Atomic Scripting (Redis/Lua), Event-Driven Workflows |
| **Cloud & DevOps** | Containerization (Docker), Orchestration (Kubernetes), Cloud Infrastructure (GCP, AWS), Reverse Proxies (Nginx, OpenResty), CI/CD (GitHub Actions) |
| **Databases & Spatial Search** | Geospatial Search & Distance Filtering (GeoDjango, PostGIS), Relational Modeling (PostgreSQL, MySQL), NoSQL (MongoDB) |
| **Applied AI & Automation** | LLM API Integration (Gemini, OpenAI), OCR Document Parsing (PaddleOCR), End-to-End Testing (Playwright, Selenium, Appium) |

</div>

---

### 🛠️ Tech Stack & Tooling

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,c,cpp,js,django,fastapi,flask,nodejs,postgres,mysql,mongodb,redis,docker,kubernetes,gcp,aws,nginx,linux,git,githubactions,tensorflow,scikitlearn,postman&perline=12" alt="Skill Icons" />
</div>

<br/>

<details open>
<summary><b>📂 Categorized Technical Proficiency</b></summary>
<br/>

| Category | Technologies & Tools |
| :--- | :--- |
| **Programming Languages** | `Python` `C` `C++` `JavaScript` `CPython` `SQL` `Lua` |
| **Backend Frameworks** | `Django` `Django REST Framework` `FastAPI` `Flask` `Node.js` |
| **Asynchronous & Real-Time** | `Celery` `Redis` `Django Channels (WebSockets)` `REST APIs` |
| **Databases & Object Storage** | `PostgreSQL (PostGIS)` `MySQL` `MongoDB` `Redis` `AWS S3` `Backblaze B2` |
| **Cloud, DevOps & Virtualization** | `Docker` `Kubernetes` `Google Cloud Platform (GCP)` `AWS` `Nginx` `OpenResty` `Linux / KVM` `GitHub Actions (CI/CD)` |
| **AI, Machine Learning & OCR** | `LangChain` `Gemini API` `ChatGPT / OpenAI API` `TensorFlow` `Scikit-Learn` `FAISS` `MediaPipe` `PaddleOCR` |
| **Testing & Automation** | `Playwright` `Appium` `Selenium` `Sikuli` |

</details>

---

### 🚀 Featured Engineering Projects

#### 1. 🏢 [ErgoSpace — Workspace Booking & Geospatial Reservation Platform](https://github.com/TirthKothari)
> *Scalable co-working and café workspace discovery & reservation platform powered by GeoDjango and PostGIS.*

```
               [ Client Applications ]
                         │
                         ▼
        [ Django / DRF Application Layer ]
         ├── JWT Auth & Role-Based Permissions
         ├── Booking & Dynamic Availability State Machine (Hourly/Daily/Monthly)
         └── Razorpay Payment Gateway & Cryptographic Verification
                         │
        ┌────────────────┴────────────────┐
        ▼                                 ▼
[ PostgreSQL + PostGIS ]          [ Provider Portal & Asset Storage ]
(Spatial Indexing & Radius Search) (Listings, Amenities & Revenue Tracking)
```

- **Geospatial Discovery Engine**: Engineered location-based workspace discovery using **GeoDjango** and **PostgreSQL/PostGIS**, enabling fast distance-based radius filtering of cafes and co-working hubs.
- **Dynamic Reservation Workflows**: Built comprehensive booking and availability state machines with seat selection, dynamic pricing tiers (hourly/daily/monthly), and reservation locks.
- **Secure Financial Transactions**: Integrated **Razorpay Payment Gateway** with order generation and cryptographic payment signature verification to guarantee transaction integrity.
- **Provider Analytics & Management**: Designed RESTful APIs for workspace owners to configure seat layouts, pricing plans, amenities, photo assets, and revenue reporting.
- **Stack**: `Python` • `Django` • `Django REST Framework` • `PostgreSQL` • `PostGIS` • `GeoDjango` • `Razorpay`

---

#### 2. 💼 [KACU — Business Loan Application & Workflow Platform](https://github.com/TirthKothari)
> *Multi-tenant business loan origination system with multi-step verification, RBAC, and automated CI/CD pipelines.*

- **Role-Based Access Control (RBAC)**: Implemented fine-grained permission controls across 4 distinct user tiers: **Applicants**, **Loan Agents**, **Financial Partners**, and **Administrators**.
- **Stateful Onboarding Workflows**: Engineered multi-step application pipelines capturing business data, funding parameters, ownership verification, and approval/rejection state transitions.
- **Secure Document Storage**: Integrated **Backblaze B2** (S3-compatible object storage) for encrypted upload, storage, and retrieval of confidential business documentation.
- **Automated CI/CD Pipeline**: Configured **GitHub Actions** deployment pipelines with automated testing, deploying the React frontend on **Vercel**, Django backend on **Render**, and managed PostgreSQL on **Aiven**.
- **Stack**: `Python` • `Django` • `Django REST Framework` • `React` • `PostgreSQL` • `Backblaze B2` • `GitHub Actions` • `Render`

---

#### 3. 🔍 [Precise Extract — AI Document Table Extraction & Natural Language Query System](https://github.com/TirthKothari)
> *Data extraction platform parsing unstructured PDFs and images into structured databases with an integrated natural language query interface.*

- **Tabular OCR Pipeline**: Developed an asynchronous data extraction engine using **FastAPI** and **Flask** that extracts structured tabular data from complex PDFs and scanned images via **PaddleOCR**.
- **Bulk Ingestion & Persistence**: Built a secure backend pipeline to process bulk file uploads, validate extracted data schemas, and persist structured records into **MySQL**.
- **Natural Language to SQL**: Integrated **Google Gemini** and **OpenAI ChatGPT** APIs to translate plain English user queries into executable, parameterized SQL commands, enabling dynamic data exploration and one-click **Excel export**.
- **Stack**: `FastAPI` • `Flask` • `PaddleOCR` • `Gemini API` • `OpenAI API` • `MySQL` • `Pandas` • `Python`

---

#### 4. 🤖 [Cloud Emulator & Automated Test Infrastructure](https://github.com/TirthKothari)
> *Cloud-native Android virtualization cluster and real-time streaming infrastructure for automated testing.*

- **Hardware-Accelerated Virtualization**: Built containerized Android emulator infrastructure deployed on **Google Cloud Platform (GCP)** via **Docker** and **Kubernetes**, leveraging Kernel-based Virtual Machine (**KVM**) for accelerated execution.
- **Concurrency & Race Condition Prevention**: Designed asynchronous task processing with **Celery** and **Redis**, utilizing atomic **Redis Lua scripts** to eliminate race conditions during concurrent virtual device allocation.
- **Low-Latency Streaming Gateway**: Configured an **Nginx/OpenResty** gateway using custom **Lua scripts** for authenticated routing of live emulator video streams alongside **Django Channels** and **WebSockets**.
- **Cross-Platform Automation**: Integrated **Appium** into an open-source testing framework, enabling natural-language-driven automation across both mobile and browser environments.
- **Stack**: `Docker` • `Kubernetes` • `GCP` • `KVM` • `Celery` • `Redis Lua` • `Django Channels` • `OpenResty` • `Appium`

---

### 💼 Experience

#### **Backend Engineer Intern** | **BugOwl AI** *(Startup)*
*Jun 2025 – Dec 2025 • Mumbai, India*

- **Platform Architecture**: Led a team of 3 engineers in developing the backend architecture for an AI-powered QA automation platform using **Python** and **Django**, enabling natural-language-driven browser and mobile test execution.
- **Concurrency & Queue Management**: Engineered asynchronous task pipelines using **Celery** and **Redis**, writing atomic **Redis Lua scripts** to resolve concurrency bottlenecks and race conditions during on-demand emulator provisioning.
- **Cloud Infrastructure**: Built and deployed scalable Android emulator infrastructure on **GCP** using **Docker** and **Kubernetes**, utilizing **KVM** for hardware-accelerated device virtualization.
- **Real-Time Video Gateway**: Implemented real-time communication via **Django Channels** and **WebSockets**, and built an **Nginx/OpenResty** reverse proxy using **Lua** for authenticated routing of live emulator streams.
- **Test Automation Integration**: Extended an open-source testing engine with **Appium** to support automated Android application testing.

---

### 🏆 Hackathon Achievements & Awards

| Event | Organization / Institution | Project & Contribution |
| :--- | :--- | :--- |
| 🥇 **CODEVERSE '23 Hackathon** *(24-Hour)* | Vidyavardhini’s Bhausaheb Vartak Polytechnic | Developed a computer vision application in Python translating sign language gestures into text in real time. |
| 🏅 **DATAHACK 2.0 Hackathon** *(24-Hour)* | Dwarkadas J. Sanghvi College of Engineering | Built an AI-powered recommendation system matching legal cases with suitable legal counsel based on case attributes. |

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

  <p>Looking for a dedicated Software Engineer with a passion for Backend Systems, Cloud Infrastructure, or AI? Let's talk!</p>

  <a href="mailto:tirth.n.kothari@gmail.com">
    <img src="https://img.shields.io/badge/Email-tirth.n.kothari%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;&nbsp;
  <a href="https://linkedin.com/in/tirthkothari" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/TirthKothari">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>

</div>
