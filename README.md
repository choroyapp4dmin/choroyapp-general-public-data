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



------------------------------------------------------------------------------------------------------
# 🌱 ChoroyApp – Acceso Público y Visión General de la Plataforma

Bienvenido al **repositorio de acceso público de ChoroyApp**.

Este repositorio reúne **enlaces públicos, documentación y referencias técnicas** relacionadas con la plataforma ChoroyApp, incluyendo sus APIs, infraestructura en la nube, pipelines de CI/CD y herramientas de administración.

> **ChoroyApp** es una plataforma impulsada por la comunidad, diseñada para conectar a las personas con productos, servicios y experiencias locales. Está construida sobre una **arquitectura de microservicios que se ejecuta en Google Cloud Platform (GCP)**, utilizando tecnologías modernas, confiables y escalables.

---

## 📱 Próximo Lanzamiento Móvil

🚀 **ChoroyApp versión 1.0.0 será lanzada oficialmente para:**
- **Android**
- **iOS**

📅 **Fecha de lanzamiento:** **1 de enero de 2026**

La aplicación móvil está desarrollada con un enfoque **multiplataforma**, garantizando una experiencia consistente y de alta calidad en todos los dispositivos.

---

## 🌍 Servicios Públicos y Puntos de Acceso

A continuación se presentan los principales **servicios públicos** que impulsan ChoroyApp.  
Cada sección incluye una breve explicación en lenguaje simple.

---

### 📘 API Principal – Backend Central de la Aplicación

- **Documentación de la API (Swagger UI)**  
  🔗 http://34.176.81.106:8090/choroyapp-api/swagger-ui/index.html  

**¿Qué es esto?**  
Este es el **microservicio backend principal** de ChoroyApp.  
Se encarga de la gestión de usuarios, productos, compras, ventas y toda la lógica central de la aplicación.

Para usuarios no técnicos, este servicio puede entenderse como **el cerebro de la aplicación**.

---

### 🧾 API de Logs – Monitoreo del Sistema y Observabilidad

- **Documentación de la API (Swagger UI)**  
  🔗 http://34.176.81.106:8070/choroyapp-logger/swagger-ui/index.html  

**¿Qué es esto?**  
Es un **microservicio dedicado al registro de logs**, responsable de almacenar:
- Registros de la aplicación
- Eventos del sistema
- Diagnósticos operacionales

Este servicio mejora la estabilidad y la observabilidad de la plataforma y **no es accedido directamente por los usuarios finales**.

---

### 🛠️ CI / CD – Automatización con Jenkins

- **Panel de Jenkins**  
  🔗 http://34.176.81.106/jenkins  

**¿Qué es esto?**  
Jenkins se utiliza para automatizar todo el flujo de entrega:
- Compilación y pruebas de microservicios backend
- Generación de versiones (por ejemplo `1.0.0`, `1.0.1`)
- Empaquetado de servicios en imágenes Docker
- Despliegue de actualizaciones en la infraestructura en la nube

Esto asegura que los despliegues sean **repetibles, trazables y confiables**.

---

### 🖥️ Página de Control – Panel de Administración

- **Panel de Control**  
  🔗 http://34.176.245.177:8082/  

**¿Qué es esto?**  
Es una interfaz web de administración utilizada internamente para:
- Control operacional
- Monitoreo del comportamiento del sistema
- Tareas administrativas y de soporte

Esta interfaz está destinada **exclusivamente a administradores**, no a usuarios finales.

---

## 🗄️ Almacenamiento de Datos

ChoroyApp utiliza múltiples bases de datos para equilibrar **rendimiento, consistencia y flexibilidad**:

| Propósito | Tecnología |
|---------|------------|
| Datos estructurados (usuarios, productos, ventas, pagos) | **PostgreSQL** |
| Mensajes, logs y documentos flexibles | **MongoDB** |

---

## ☁️ Nube e Infraestructura

ChoroyApp se desarrolla y despliega utilizando una **arquitectura de microservicios nativa en la nube sobre Google Cloud Platform (GCP)**.

### 🧩 Características Clave
- Microservicios backend independientes
- Servicios contenerizados mediante Docker
- Máquinas virtuales alojadas en la nube
- Configuración por entornos
- Comunicación interna segura entre servicios

Esta arquitectura permite **escalabilidad, aislamiento de fallos y entrega continua**.

---

## ⚙️ Stack Tecnológico (Vista General)

### 🔧 Backend
- ☕ Java
- 🌱 Spring Boot
- 🧠 JDK 21
- 🐳 Docker y Docker Compose
- APIs REST
- Arquitectura de microservicios

### 📱 Frontend Móvil
- ⚛️ React Native
- 🚀 Expo
- 📦 TypeScript

Este stack permite un **desarrollo rápido** sin comprometer la **estabilidad y mantenibilidad a largo plazo**.

---

## 🧩 Arquitectura de la Plataforma (En Términos Simples)

- El backend está compuesto por **microservicios independientes**
- La lógica de negocio principal y el sistema de logs están separados
- Los servicios se despliegan en **Google Cloud Platform**
- CI/CD automatiza compilaciones y despliegues
- Las APIs están documentadas y disponibles públicamente
- La aplicación móvil se comunica de forma segura con los servicios backend

---

## 🔐 Seguridad y Privacidad

Este repositorio contiene **únicamente información pública**, como:
- URLs públicas
- Enlaces a documentación de APIs
- Descripciones de arquitectura a alto nivel

❌ No contraseñas  
❌ No tokens  
❌ No archivos de configuración privados  

Toda la información sensible se almacena de forma segura dentro de la infraestructura en la nube.

---

## 📌 Enlaces Rápidos

- 🌐 Documentación API Principal  
  http://34.176.81.106:8090/choroyapp-api/swagger-ui/index.html

- 🧾 Documentación API de Logs  
  http://34.176.81.106:8070/choroyapp-logger/swagger-ui/index.html

- 🛠️ Automatización Jenkins  
  http://34.176.81.106/jenkins

- 🖥️ Página de Control  
  http://34.176.245.177:8082/

---

## 🧑‍💻 Equipo de Desarrollo

ChoroyApp es desarrollada y mantenida por un equipo multidisciplinario que combina **visión de producto, ingeniería y diseño**.

- **José Alegría** – Product Owner  
  Responsable de la visión del producto, definición de requerimientos y priorización del roadmap.

- **Rodolfo Soto** – Ingeniero de Software Full Stack  
  Desarrollo backend y móvil, arquitectura de microservicios, infraestructura en la nube (GCP) y pipelines de CI/CD.

- **Fabián Garrido** – Diseñador Gráfico  
  Identidad visual, branding, recursos UI y diseño gráfico.

---

## 🔄 Metodología de Desarrollo

ChoroyApp sigue una **metodología de desarrollo ágil**, enfocada en:

- Entregas iterativas e incrementales
- Integración y despliegue continuo (CI/CD)
- Ciclos de retroalimentación frecuentes
- Alta calidad de código y confiabilidad del sistema

Este enfoque permite que la plataforma **evolucione de forma continua**, adaptándose tanto a las necesidades de los usuarios como a los requerimientos técnicos.

---

## 👤 Mantenedor

**ChoroyApp**  
Diseñada, desarrollada y mantenida utilizando buenas prácticas modernas de ingeniería de software.

> _“Construir con claridad. Desplegar con seguridad. Versionar todo.”_
> 

---

## 🇨🇱 Orgullo Chileno / Chilean Pride

**ChoroyApp** es un producto **100% chileno**, diseñado y desarrollado en Chile con una fuerte identidad local y una visión global.

Creemos en la tecnología como una herramienta para **fortalecer las comunidades**, potenciar el comercio local y crear soluciones digitales con impacto real.

---

**ChoroyApp** is a **100% Chilean product**, designed and developed in Chile with strong local roots and a global vision.

We believe technology is a tool to **empower communities**, support local commerce, and build digital solutions with real-world impact.

> 🌱 _Product made in Chile. Built with care, quality, and purpose._ 🇨🇱
