<p align="center">
  <a href="https://github.com/FahadBinNasir">
    <img
      src="https://capsule-render.vercel.app/api?type=transparent&fontColor=2f81f7&fontSize=52&height=90&width=1018&text=Fahad%20Bin%20Nasir"
      alt="Fahad Bin Nasir"
    />
  </a>
</p>

<h3 align="center">
  Software Engineering Undergraduate | Full-Stack • AI/ML • Mobile
</h3>

<p align="center">
  Building secure, intelligent, and practical software systems.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/fahad-bin-nasir-580948290/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://fahad-portfolio-tawny.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-2F81F7?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="mailto:fahadabbasi17025@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

## 👨‍💻 About Me

I'm a Software Engineering undergraduate at **Bahria University**, focused on building full-stack and AI-powered software systems.

My work spans backend engineering, retrieval-augmented generation, machine learning, computer vision, mobile development, security, cloud infrastructure, and IoT. I enjoy taking projects beyond prototypes by focusing on architecture, security, data flow, testing, and usable interfaces.

- 🔭 Building **Unified Knowledge Brain**, a secure multi-tenant enterprise RAG platform
- 🌱 Exploring **MLOps, RAG evaluation, distributed processing, observability, and scalable AI architecture**
- 💬 Ask me about **Python, FastAPI, Next.js, TypeScript, Flutter, REST APIs, RAG systems, computer vision, and applied AI/ML**
- 👯 Open to collaborating on **AI/ML, full-stack, developer tooling, and open-source projects**
- 🎯 Interested in **Software Engineering, Backend, Full-Stack, and AI/ML opportunities**

---

# 🚀 Featured Projects

## 🧠 Unified Knowledge Brain

### Secure Multi-Tenant Enterprise RAG Platform
**Final Year Project**

Enterprise knowledge platform for securely ingesting, protecting, retrieving, and querying organizational data across multiple external services.

`Python` `FastAPI` `Next.js` `React` `TypeScript` `PostgreSQL` `pgvector` `Redis` `Groq` `Presidio` `Nango` `Docker` `AWS`

### Architecture

```text
                        UNIFIED KNOWLEDGE BRAIN

 ┌──────────────────────────────────────────────────────────────┐
 │                    Next.js + React Frontend                  │
 │ Dashboard • Search/Chat • Vault • Connectors • Admin        │
 └──────────────────────────────┬───────────────────────────────┘
                                │
                          REST API / SSE
                                │
                                ▼
 ┌──────────────────────────────────────────────────────────────┐
 │                       FastAPI Backend                        │
 │ Auth • RBAC • Retrieval • Ingestion • Privacy • Audit       │
 └──────────┬───────────────────┬───────────────────┬───────────┘
            │                   │                   │
            ▼                   ▼                   ▼
 ┌────────────────┐   ┌─────────────────┐   ┌──────────────────┐
 │ PostgreSQL 16  │   │     Redis 7     │   │     Groq LLM     │
 │   + pgvector   │   │                 │   │                  │
 │                │   │ Sessions        │   │ LLM-assisted     │
 │ Tenants        │   │ OTP             │   │ responses        │
 │ Documents      │   │ Rate Limits     │   │                  │
 │ Audit Records  │   │                 │   │                  │
 └───────▲────────┘   └─────────────────┘   └──────────────────┘
         │
         │ Secure Ingestion
         │
 ┌───────┴──────────────────────────────────────────────────────┐
 │                  Security & Privacy Pipeline                 │
 │ Presidio • PII Redaction • Secret Detection • Classification│
 │ Fernet Encryption • Tenant Isolation • Clearance Filtering  │
 └──────────────────────────────▲───────────────────────────────┘
                                │
                         Nango / Direct APIs
                                │
       ┌─────────┬─────────┬────┴─────┬─────────┬─────────┐
       ▼         ▼         ▼          ▼         ▼         ▼
    GitHub     Slack     Gmail    Google Drive Dropbox  Zendesk


                     INFRASTRUCTURE

 Docker • Docker Compose • Caddy • Pulumi • AWS EC2
 VPC • IAM • Secrets Manager • CloudWatch • Encrypted EBS
```

### Engineering Highlights

- 🏢 **Multi-tenant architecture** with PostgreSQL-authoritative tenant isolation
- 🛡️ **3 application roles** with **5 security clearance levels**
- 🔌 **6 external integrations:** GitHub, Slack, Gmail, Google Drive, Dropbox, and Zendesk
- 🔐 Security-first ingestion using **Microsoft Presidio**, secret detection, PII masking, classification, and Fernet encryption
- 🧠 **PostgreSQL + pgvector** retrieval with tenant, clearance, and metadata filtering
- 🤖 **Groq-powered** LLM-assisted responses using retrieved organizational knowledge
- ⚡ **Server-Sent Events** for live observability, connector activity, and Slack updates
- 🚀 Containerized using **Docker Compose**
- ☁️ AWS infrastructure defined with **Pulumi**, including EC2, VPC, IAM, encrypted EBS, Secrets Manager, and CloudWatch
- 🧪 **20 backend test files with ~121 tests** covering authentication, RBAC, tenant isolation, connector security, privacy, and system behavior

> 🔒 The project is under active development. Public repository/demo links can be added when available.

---

## 👁️ AuthentiQ

### AI-Powered Exam Proctoring & Cheating Detection

Computer-vision and behavioral-analysis system designed to identify suspicious activity during digital examinations.

`Python` `OpenCV` `MediaPipe` `Machine Learning` `Tkinter`

<p>
  <a href="https://github.com/FahadBinNasir/AuthentiQ">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="AuthentiQ Source Code" />
  </a>
  <a href="https://authenti-q-six.vercel.app">
    <img src="https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="AuthentiQ Live Demo" />
  </a>
</p>

- 👁️ Real-time face and gaze analysis using **OpenCV + MediaPipe**
- ⌨️ Combines visual monitoring with **tab-switch and keystroke anomaly detection**
- 🚨 Automatically identifies and records suspicious examination activity
- 📊 Administrator dashboard for reviewing session statistics
- 📁 Generates structured evidence logs and reports

---

## 🏋️ DesiFit

### AI-Assisted Pakistani Fitness Platform

Fitness application designed around Pakistani food and lifestyle, combining local nutrition data with personalized AI-assisted planning.

`Flutter` `Dart` `AI` `Firebase` `REST APIs`

<p>
  <a href="https://github.com/FahadBinNasir/desi_fit">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="DesiFit Source Code" />
  </a>
  <a href="https://desi-fit.vercel.app">
    <img src="https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="DesiFit Live Demo" />
  </a>
</p>

- 🍛 Pakistani-focused food and nutrition database
- 🤖 AI-assisted personalized meal and workout planning
- 📱 Built with Flutter and Dart
- 💾 Offline-oriented application functionality
- 🔗 Integration-oriented architecture for external services

---

## 📊 ChurnVision Pro

### Customer Churn Prediction & Model Evaluation

Machine-learning application for predicting telecom customer churn and comparing traditional ML with neural-network approaches.

`Python` `Scikit-learn` `TensorFlow` `Keras` `Streamlit` `SMOTE`

- 📊 Trained on **7,043 telecom customer records**
- 🌲 Optimized a **Random Forest** model using GridSearchCV and cross-validation
- 🧠 Built and evaluated an **Artificial Neural Network**
- ⚖️ Applied **SMOTE** for class-imbalance handling
- 📈 Evaluated models using accuracy, precision, recall, F1 score, and confusion matrices
- 🖥️ Built an interactive Streamlit interface for live predictions and model comparison

---

<details>
<summary><b>📦 More Projects</b></summary>

<br>

### 🌦️ Weather App
`Flutter` `Dart` `REST APIs`

Global weather application featuring city search, hourly conditions, and seven-day forecasts.

### 🛒 E-Commerce App
`Flutter` `Dart` `Provider`

Mobile commerce application with centralized cart/wishlist state, checkout logic, and order workflows.

### 💰 Expense Tracker
`Flutter` `Dart`

Offline-first personal finance application with transaction CRUD, persistence, and budget analytics.

### 📦 Smart Inventory Management
`NodeMCU ESP8266` `RFID` `Arduino` `HTTPS`

IoT inventory system featuring RFID identification, real-time HTTPS communication, LCD feedback, and embedded-device networking.

</details>

---

# 🛠️ Technical Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=python,ts,js,dart,cs,cpp" alt="Languages" />
</p>

`Python` `TypeScript` `JavaScript` `Dart` `C#` `C++` `SQL`

### Frontend & Mobile

<p>
  <img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,flutter" alt="Frontend and Mobile" />
</p>

`Next.js` `React` `TypeScript` `Tailwind CSS` `Flutter` `Provider`

### Backend & APIs

<p>
  <img src="https://skillicons.dev/icons?i=fastapi" alt="Backend" />
</p>

`FastAPI` `REST APIs` `SSE` `JWT` `OAuth 2.0` `Nango`

### AI / ML & Data

<p>
  <img src="https://skillicons.dev/icons?i=tensorflow,opencv" alt="AI and Machine Learning" />
</p>

`Scikit-learn` `TensorFlow` `Keras` `OpenCV` `MediaPipe` `Pandas` `NumPy` `Microsoft Presidio` `Groq` `RAG`

### Databases & Data Infrastructure

<p>
  <img src="https://skillicons.dev/icons?i=postgres,redis,firebase" alt="Databases" />
</p>

`PostgreSQL` `pgvector` `Redis` `Firebase`

### Cloud & DevOps

<p>
  <img src="https://skillicons.dev/icons?i=aws,docker" alt="Cloud and DevOps" />
</p>

`AWS` `Docker` `Docker Compose` `Pulumi` `Caddy` `AWS Secrets Manager` `CloudWatch`

### Development Tools

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman" alt="Development Tools" />
</p>

`Git` `GitHub` `VS Code` `Postman` `Pytest` `Arduino IDE` `Cisco Packet Tracer`

---

# 🔐 Engineering Interests

```text
AI Engineering       RAG • LLM Integration • Computer Vision • ML
Backend Engineering  APIs • Authentication • Multi-Tenancy • Data
Security & Privacy   RBAC • PII Protection • Tenant Isolation
Full-Stack           Next.js • React • TypeScript • FastAPI
Cloud & DevOps       Docker • AWS • IaC • Observability
Mobile               Flutter • Dart • Firebase • State Management
```

---

# 🌱 Currently Exploring

`MLOps` • `RAG Evaluation` • `Distributed Job Processing` • `Production Observability` • `Scalable AI Architecture` • `Information Security`

I'm currently focused on moving AI-powered applications from functional prototypes toward **secure, observable, scalable, and maintainable production systems**.

---

# 📊 GitHub Stats

<p align="center">
  <img
    width="49%"
    src="https://github-readme-stats-five-sigma-99.vercel.app/api?username=FahadBinNasir&show_icons=true&theme=github_dark&hide_border=true&bg_color=00000000&title_color=2f81f7&icon_color=2f81f7&text_color=c9d1d9&ring_color=2f81f7&include_all_commits=true&count_private=true"
    alt="Fahad Bin Nasir GitHub Stats"
  />
  <img
    width="49%"
    src="https://github-readme-stats-five-sigma-99.vercel.app/api/top-langs/?username=FahadBinNasir&layout=compact&theme=github_dark&hide_border=true&bg_color=00000000&title_color=2f81f7&text_color=c9d1d9&langs_count=8&hide=html,css"
    alt="Fahad Bin Nasir Top Languages"
  />
</p>

<p align="center">
  <img
    width="70%"
    src="https://streak-stats.demolab.com?user=FahadBinNasir&theme=github-dark-blue&hide_border=true&background=00000000&ring=2F81F7&fire=2F81F7&currStreakLabel=2F81F7"
    alt="Fahad Bin Nasir GitHub Streak"
  />
</p>

### 📈 Contribution Activity

<p align="center">
  <img
    width="100%"
    src="https://github-readme-activity-graph-gold-gamma.vercel.app/graph?username=FahadBinNasir&bg_color=00000000&color=c9d1d9&line=2f81f7&point=2f81f7&area=true&area_color=2f81f7&hide_border=true&custom_title=Contribution%20Activity"
    alt="Fahad Bin Nasir Contribution Activity Graph"
  />
</p>

---

# 🤝 Let's Connect

I'm interested in **software engineering, backend, full-stack, and AI/ML opportunities** where I can contribute to real products, solve meaningful engineering problems, and continue developing production-level systems.

<p align="center">
  <a href="https://www.linkedin.com/in/fahad-bin-nasir-580948290/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://fahad-portfolio-tawny.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-Visit-2F81F7?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="mailto:fahadabbasi17025@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<p align="center">
  <sub>Building software that solves real problems.</sub>
</p>
