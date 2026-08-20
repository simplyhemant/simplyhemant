# Hi there, I'm Hemant Singh 👋

<p align="left">
  <a href="https://portfolio-two-murex-65.vercel.app/"><img src="https://img.shields.io/badge/-🌐%20Portfolio-0A66C2?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/hemant-singh-a2aaa7208/"><img src="https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn"></a>
  <a href="https://drive.google.com/file/d/14TfX2We5tkviuloP0stGnU6w_XN5Ifq7/view?usp=sharing"><img src="https://img.shields.io/badge/-📄%20Resume-E4405F?style=for-the-badge" alt="Resume"></a>
</p>

### ⚡ Backend & AI Engineer | Java • Spring Boot • Python • Agentic AI Systems
Passionate about architecting distributed backend services, high-concurrency systems, and stateful Agentic AI workflows using LangGraph and LLM orchestration.

---

## 🛠️ Tech Stack  

<img align="right" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExZ20xbThtOXN2cXN3a3U4M3pocnlxMXk5emczNXFwdTd4ZGdhY3U1NCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/78XCFBGOlS6keY1Bil/giphy.gif" width="320"/>

### 💻 Languages & Fundamentals
![](https://img.shields.io/badge/-Java-ED8B00?style=flat&logo=openjdk&logoColor=white) ![](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![](https://img.shields.io/badge/-C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)  
* RESTful API Design, Microservices Architecture, SOLID Principles, System Design (HLD/LLD), Data Structures & Algorithms

### 🤖 Generative AI & Agentic Frameworks
![](https://img.shields.io/badge/-LangGraph-000000?style=flat&logo=langchain&logoColor=white) ![](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white) ![](https://img.shields.io/badge/-Ollama-000000?style=flat&logo=ollama&logoColor=white) ![](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)  
* Multi-Agent Workflows, State Graphs, Dynamic Tool Calling, Conditional Routing, Groq & Gemini APIs, Autonomous Agents

### ⚙️ Backend & Frameworks
![](https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white) ![](https://img.shields.io/badge/-Spring_Cloud-6DB33F?style=flat&logo=spring&logoColor=white) ![](https://img.shields.io/badge/-Hibernate/JPA-59666C?style=flat&logo=hibernate&logoColor=white) ![](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![](https://img.shields.io/badge/-Express.js-000000?style=flat&logo=express&logoColor=white)  
* **Security & Testing:** Spring Security, JWT, OAuth2, RBAC, JUnit 5, Mockito
* **Messaging & Real-time:** Apache Kafka, Resilience4j (Circuit Breakers), WebSockets (STOMP), Socket.IO

### 💾 Databases & Caching
![](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![](https://img.shields.io/badge/-MySQL-4479A1?style=flat&logo=mysql&logoColor=white) ![](https://img.shields.io/badge/-MongoDB-47A248?style=flat&logo=mongodb&logoColor=white) ![](https://img.shields.io/badge/-Redis-DC382D?style=flat&logo=redis&logoColor=white)  
* Schema Design, Data Modeling, In-Memory Caching, Distributed Locking with TTL

### ☁️ DevOps, Cloud & Tools
![](https://img.shields.io/badge/-AWS_EC2-232F3E?style=flat&logo=amazon-aws&logoColor=white) ![](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) ![](https://img.shields.io/badge/-Nginx-009639?style=flat&logo=nginx&logoColor=white) ![](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white) ![](https://img.shields.io/badge/-Postman-FF6C37?style=flat&logo=postman&logoColor=white) ![](https://img.shields.io/badge/-Swagger-85EA2D?style=flat&logo=swagger&logoColor=black)  
* Zipkin (Distributed Tracing), Eureka, Spring Cloud Config, GitHub Actions (CI/CD)

---

## 🚀 Key Projects & Showcases

### 🤖 LangGraph Agentic AI Chatbot
* 🧠 **Stateful Multi-Agent System:** Engineered a stateful conversational agent using **LangGraph**, supporting runtime model switching across **Groq, Gemini, and local Ollama** LLMs.
* 🔍 **Autonomous Tool Calling:** Implemented conditional graph routing with **Tavily Search API** for automated real-time web retrieval and an AI News generation workflow.
* 🧩 **Modular Design:** Decoupled LLM interfaces, graph nodes, tools, and execution state from the **Streamlit UI** for clean extensibility.

### 🎬 SimplyCinema | Movie Booking & Theatre Management Platform
* 🔒 **Race Condition Solution:** Prevented seat double-booking during concurrent checkouts using **Redis TTL distributed locks** combined with **WebSockets (STOMP)** for low-latency live seat updates[cite: 1].
* 🛠️ **Production REST APIs:** Shipped **90+ REST APIs** across 4 roles (Customer, Admin, Owner, Staff), utilizing SOLID principles and global exception handling[cite: 1].
* ☁️ **Security & Deployment:** Secured endpoints via stateless **Spring Security (JWT + OAuth2 + RBAC)** and deployed on **AWS EC2** behind an Nginx reverse proxy with Razorpay payment integration[cite: 1].

### 🛒 SimplyBuy | Distributed E-Commerce Platform
* 🗺️ **Microservice Cluster:** Built an **8-microservice cluster** utilizing **Spring Cloud Gateway**, Eureka Service Discovery, and Spring Cloud Config for dynamic routing and load balancing[cite: 1].
* 🛡️ **Fault Tolerance:** Prevented cascading outages across interdependent services by implementing **Resilience4j Circuit Breakers**[cite: 1].
* ⚡ **Asynchronous Messaging:** Decoupled order and notification pipelines via **Apache Kafka**, removing blocking calls from the critical checkout path[cite: 1].
* 📊 **Observability & Deployment:** Containerized microservices using **Docker Compose** and integrated **Zipkin** for distributed tracing[cite: 1].

---

## 💼 Professional Experience

### **Software Engineer Intern** — *Stakrid Logistics*  
📅 *(Aug 2025 – Jan 2026)*[cite: 1]
* 🏗️ **Layered Backend:** Architected a modular backend from scratch using Java and Spring Boot, optimizing code maintainability and feature velocity[cite: 1].
* 🔒 **Security:** Secured endpoints for 300+ active users using **Spring Security, JWT, OAuth2, and RBAC**, eliminating authorization vulnerabilities prior to production release[cite: 1].
* 🗺️ **API Integration:** Integrated **Google Maps API** for live driver tracking and dynamic route optimization, significantly cutting manual dispatch overhead[cite: 1].
* 👥 **Team Leadership:** Managed Git workflows and conducted code reviews for a 3-person intern engineering team[cite: 1].

---

## 📊 Problem Solving & Core Focus

* 🧩 **Problem Solving:** 150+ Data Structures & Algorithms problems solved[cite: 1].
* 🎯 **Core Focus:** Agentic AI Workflows • Distributed Systems • Concurrency & Locking • System Design • High Availability

---

## 📫 Connect with me:

<p align="left">
  <a href="mailto:hemant23dev@gmail.com"><img src="https://img.shields.io/badge/-Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/hemant-singh-a2aaa7208/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://portfolio-two-murex-65.vercel.app/"><img src="https://img.shields.io/badge/-Portfolio-0052CC?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"></a>
  <a href="https://drive.google.com/file/d/14TfX2We5tkviuloP0stGnU6w_XN5Ifq7/view?usp=sharing"><img src="https://img.shields.io/badge/-Resume-E4405F?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume"></a>
</p>
