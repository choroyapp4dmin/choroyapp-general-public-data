# 🌱 ChoroyApp – Public Access & Platform Overview

Welcome to the **ChoroyApp public access repository**.

This space gathers **public links, documentation, and references** related to the ChoroyApp platform, including its APIs, infrastructure, and administration tools.

> ChoroyApp is a community-driven application designed to connect users with local products, services, and experiences, built using modern and reliable technologies.

---

## 📱 Upcoming Mobile Release

🚀 **ChoroyApp version 1.0.0 will be officially released for:**
- **Android**
- **iOS**

📅 **Release date:** **January 1st, 2026**

The mobile app is built with a cross-platform approach to ensure a consistent experience across devices.

---

## 🌍 Public Services & Access Points

Below you will find the main public services that power ChoroyApp.  
Each section includes a short explanation in plain language.

---

### 📘 Core API – Main Application Backend

- **API Documentation (Swagger UI)**  
  🔗 http://34.176.81.106:8090/choroyapp-api/swagger-ui/index.html  

**What is this?**  
This is the main backend service of ChoroyApp.  
It handles user accounts, products, purchases, and all core application logic.

If you are not a developer, you can think of this as **the brain of the app**.

---

### 🧾 Logging API – System Monitoring & Logs

- **API Documentation (Swagger UI)**  
  🔗 http://34.176.81.106:8070/choroyapp-logger/swagger-ui/index.html  

**What is this?**  
This service stores technical logs and system events.  
It helps monitor the platform, detect issues, and improve stability.

Users do not interact with this directly.

---

### 🛠️ CI / CD – Jenkins Automation

- **Jenkins Dashboard**  
  🔗 http://34.176.81.106/jenkins  

**What is this?**  
Jenkins is an automation tool used to:
- Build new versions of the app
- Create versioned releases (e.g. 1.0.0, 1.0.1)
- Package the backend into Docker containers
- Deploy updates safely

This ensures updates are **reliable and repeatable**.

---

### 🖥️ Control Webpage – Administration Panel

- **Control Panel**  
  🔗 http://34.176.245.177:8082/  

**What is this?**  
This is a web-based administration interface used for:
- Operational control
- Monitoring
- Internal management tasks

It is intended for administrators, not end users.

---

## 🗄️ Data Storage

ChoroyApp uses two types of databases to balance performance and flexibility:

| Purpose | Technology |
|---|---|
| Structured data (users, products, sales) | **PostgreSQL** |
| Messages, logs, flexible documents | **MongoDB** |

---

## ⚙️ Technology Stack (High Level)

### 🔧 Backend
- ☕ Java
- 🌱 Spring Boot
- 🧠 JDK 21
- 🐳 Docker & Docker Compose
- RESTful APIs

### 📱 Mobile Frontend
- ⚛️ React Native
- 🚀 Expo
- 📦 TypeScript

This stack allows fast development while maintaining long-term stability.

---

## 🧩 Platform Architecture (In Simple Terms)

- The backend is split into **independent services**
- Logging is separated to keep the system clean and observable
- Deployments are automated
- APIs are documented and publicly accessible
- The mobile app communicates securely with the backend

---

## 🔐 Security & Privacy

This repository contains **only public information**:
- Public URLs
- Documentation links
- High-level technical descriptions

❌ No passwords  
❌ No tokens  
❌ No private configuration files  

Sensitive data is stored securely in the backend infrastructure.

---

## 📌 Quick Links

- 🌐 Core API Documentation  
  http://34.176.81.106:8090/choroyapp-api/swagger-ui/index.html

- 🧾 Logging API Documentation  
  http://34.176.81.106:8070/choroyapp-logger/swagger-ui/index.html

- 🛠️ Jenkins Automation  
  http://34.176.81.106/jenkins

- 🖥️ Control Webpage  
  http://34.176.245.177:8082/

---

## 👤 Maintainer

**ChoroyApp**  
Designed, built, and maintained using modern software engineering best practices.

---

> _“Build clearly. Deploy safely. Version everything.”_

---

## 🧑‍💻 Development Team

ChoroyApp is developed and maintained by a multidisciplinary team, combining product vision, engineering, and visual design.

- **José Alegría** – Product Owner  
  Responsible for product vision, requirements, and roadmap prioritization.

- **Rodolfo Soto** – Full Stack Software Engineer  
  Backend and mobile application development, system architecture, infrastructure, and CI/CD.

- **Fabián Garrido** – Graphic Designer  
  Visual identity, branding, UI assets, and graphic design.

---

## 🔄 Development Methodology

The development and ongoing maintenance of ChoroyApp follow an **Agile methodology**, focusing on:

- Iterative and incremental delivery
- Continuous integration and deployment (CI/CD)
- Frequent feedback and improvements
- High code quality and system stability

This approach allows ChoroyApp to evolve continuously while adapting to real user needs and technical requirements.

---

> _“Build clearly. Deploy safely. Version everything.”_


