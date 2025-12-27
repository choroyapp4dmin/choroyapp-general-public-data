# 🌱 ChoroyApp – Public Access & Platform Overview

Welcome to the **ChoroyApp public access repository**.

This repository gathers **public links, documentation, and technical references** related to the ChoroyApp platform, including its APIs, cloud infrastructure, CI/CD pipelines, and administration tools.

> **ChoroyApp** is a community-driven platform designed to connect users with local products, services, and experiences, built on a **microservices architecture running on Google Cloud Platform (GCP)** using modern, reliable, and scalable technologies.

---

## 📱 Upcoming Mobile Release

🚀 **ChoroyApp version 1.0.0 will be officially released for:**
- **Android**
- **iOS**

📅 **Release date:** **January 1st, 2026**

The mobile application is built with a **cross-platform approach**, ensuring a consistent and high-quality experience across devices.

---

## 🌍 Public Services & Access Points

Below you will find the main **public services** that power ChoroyApp.  
Each section includes a short explanation in plain language.

---

### 📘 Core API – Main Application Backend

- **API Documentation (Swagger UI)**  
  🔗 http://34.176.81.106:8090/choroyapp-api/swagger-ui/index.html  

**What is this?**  
This is the **main backend microservice** of ChoroyApp.  
It handles user accounts, products, purchases, sales, and all core application logic.

For non-technical users, this service can be thought of as **the brain of the app**.

---

### 🧾 Logging API – System Monitoring & Observability

- **API Documentation (Swagger UI)**  
  🔗 http://34.176.81.106:8070/choroyapp-logger/swagger-ui/index.html  

**What is this?**  
This is a **dedicated logging microservice** responsible for storing:
- Application logs
- System events
- Operational diagnostics

It improves platform stability and observability and is **not directly accessed by end users**.

---

### 🛠️ CI / CD – Jenkins Automation

- **Jenkins Dashboard**  
  🔗 http://34.176.81.106/jenkins  

**What is this?**  
Jenkins is used to automate the entire delivery pipeline:
- Build and test backend microservices
- Generate versioned releases (e.g. `1.0.0`, `1.0.1`)
- Package services into Docker images
- Deploy updates to the cloud infrastructure

This ensures deployments are **repeatable, traceable, and reliable**.

---

### 🖥️ Control Webpage – Administration Panel

- **Control Panel**  
  🔗 http://34.176.245.177:8082/  

**What is this?**  
A web-based administration interface used internally for:
- Operational control
- Monitoring system behavior
- Administrative and support tasks

This interface is intended **only for administrators**, not end users.

---

## 🗄️ Data Storage

ChoroyApp uses multiple databases to balance **performance, consistency, and flexibility**:

| Purpose | Technology |
|---|---|
| Structured data (users, products, sales, payments) | **PostgreSQL** |
| Messages, logs, flexible documents | **MongoDB** |

---

## ☁️ Cloud & Infrastructure

ChoroyApp is developed and deployed using a **cloud-native microservices architecture on Google Cloud Platform (GCP)**.

### 🧩 Key Characteristics
- Independent backend microservices
- Containerized services using Docker
- Cloud-hosted virtual machines
- Environment-based configuration
- Secure internal communication between services

This architecture enables **scalability, fault isolation, and continuous delivery**.

---

## ⚙️ Technology Stack (High Level)

### 🔧 Backend
- ☕ Java
- 🌱 Spring Boot
- 🧠 JDK 21
- 🐳 Docker & Docker Compose
- RESTful APIs
- Microservices architecture

### 📱 Mobile Frontend
- ⚛️ React Native
- 🚀 Expo
- 📦 TypeScript

This stack supports **rapid development** while maintaining **long-term stability and maintainability**.

---

## 🧩 Platform Architecture (In Simple Terms)

- The backend is composed of **independent microservices**
- Core business logic and logging are separated
- Services are deployed on **Google Cloud Platform**
- CI/CD automates builds and deployments
- APIs are documented and publicly accessible
- The mobile app communicates securely with the backend services

---

## 🔐 Security & Privacy

This repository contains **only public information**, such as:
- Public URLs
- API documentation links
- High-level architectural descriptions

❌ No passwords  
❌ No tokens  
❌ No private configuration files  

All sensitive data is stored securely within the cloud infrastructure.

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

## 🧑‍💻 Development Team

ChoroyApp is developed and maintained by a multidisciplinary team combining **product vision, engineering, and design**.

- **José Alegría** – Product Owner  
  Responsible for product vision, requirements, and roadmap prioritization.

- **Rodolfo Soto** – Full Stack Software Engineer  
  Backend and mobile development, microservices architecture, cloud infrastructure (GCP), and CI/CD pipelines.

- **Fabián Garrido** – Graphic Designer  
  Visual identity, branding, UI assets, and graphic design.

---

## 🔄 Development Methodology

ChoroyApp follows an **Agile development methodology**, focused on:

- Iterative and incremental delivery
- Continuous integration and deployment (CI/CD)
- Frequent feedback loops
- High code quality and system reliability

This approach allows the platform to **evolve continuously** while adapting to both user needs and technical requirements.

---

## 👤 Maintainer

**ChoroyApp**  
Designed, built, and maintained using modern software engineering best practices.

> _“Build clearly. Deploy safely. Version everything.”_
