<h1 align="center">Hi, I'm Shakthi Jayan 👋</h1>
<h3 align="center">Backend Software Engineer (Java) | Distributed Systems | Spring Boot & Microservices</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/shakthi-jayan"><img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://shakthi-s-dev-hub.vercel.app"><img src="https://img.shields.io/badge/-Portfolio-000000?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://leetcode.com/u/shakthi_jayan_"><img src="https://img.shields.io/badge/-LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white" alt="LeetCode" /></a>
  <a href="mailto:shakthijayan19@gmail.com"><img src="https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### 🚀 About Me

I am a backend software engineer specializing in Java, Spring Boot, and distributed systems architecture. I build resilient RESTful APIs, microservices, and containerized backend infrastructures, transitioning into software engineering from a Chemical Engineering background through rigorous self-directed learning.

I am passionate about tackling backend challenges like concurrency, rate limiting, and fault tolerance. I am a final-year B.Tech student (expected May 2027) with a strong foundation in Object-Oriented Programming and active DSA problem-solving in Java (80+ LeetCode problems).

**Looking for:** Backend Developer / Java Software Engineer roles at product-based companies to build highly available, scalable backend systems.

---

### 🛠️ Tech Stack

**Languages:** ![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white) 

**Backend Ecosystem:** ![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/-Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white) ![Spring Cloud](https://img.shields.io/badge/-Spring%20Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Hibernate](https://img.shields.io/badge/-Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white) 

**Databases & Caching:** ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Message Brokers & Infrastructure:** ![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

**Architecture & Resilience:** Microservices · Event-Driven Architecture · gRPC · Saga Pattern · JWT Authentication · Bucket4j (Rate Limiting) · Resilience4j (Circuit Breaking)

---

### 📌 Featured Java Projects

#### 1. [Sentinel Gateway — Distributed API Gateway & Rate Limiter](https://github.com/shakthi-jayan/sentinel-gateway)
A distributed API gateway built from scratch in Spring Boot, handling authentication, per-client rate limiting, and fault tolerance across multiple backend microservices.
- Eliminated inconsistent per-client throttling across scaled gateway instances by implementing a distributed token-bucket rate limiter (Bucket4j + Redis) instead of in-memory counters.
- Blocked 100% of unauthenticated requests at the gateway layer by enforcing JWT authentication as a trust boundary before traffic reached downstream microservices.
- Achieved automatic recovery from downstream failures by implementing a Resilience4j circuit breaker that self-recovered without manual intervention.
- Load tested with k6: 10 concurrent virtual users processed 1,200+ requests, with 99% of excess traffic correctly throttled.
- **Stack:** Java, Spring Boot, Spring Cloud Gateway, Redis, Bucket4j, JWT, Resilience4j, Docker Compose, k6

#### 2. [Patient Management System 🚧 In Progress](https://github.com/shakthi-jayan/patient-management)
An enterprise-grade patient management platform being built on a microservices architecture.
- Built a Patient Service with a layered Spring Boot architecture (controller → DTO → mapper → service → repository); verified via manual API testing that patient records are correctly created and persisted to an H2 in-memory database.
- 🚧 *Planned:* asynchronous event-driven communication using Kafka alongside synchronous inter-service communication via gRPC and REST APIs.
- 🚧 *Planned:* a dedicated authentication service using Bearer tokens, with external traffic managed via Spring Cloud Gateway.
- 🚧 *Planned:* containerizing services with Docker and simulating AWS infrastructure (ECS, RDS, MSK) locally using LocalStack.
- **Stack (implemented):** Java, Spring Boot, H2  
  **Stack (planned):** PostgreSQL, Kafka, gRPC, Spring Cloud Gateway, Docker, LocalStack (AWS)
  
#### 3. High-Concurrency Event-Driven System ("Ticketmaster" Clone) *[Just Started]*
A high-concurrency event booking architecture designed to demonstrate asynchronous communication, strict data consistency, and race condition handling.
- Developing a REST-based Order Service to handle incoming booking requests and a gRPC/REST Inventory Service to manage available seats.
- Utilizing Redis distributed locks within the Inventory Service to prevent double-booking anomalies during simultaneous user requests.
- Orchestrating a distributed transaction across microservices using the Saga pattern, publishing `OrderCreated` and `SeatReserved` events via a message broker (Kafka/RabbitMQ).
- **Stack:** Java, Spring Boot, Redis, Kafka/RabbitMQ, REST, gRPC

---

### 🧠 Currently Focused On

- Deepening Java multithreading, concurrency, and distributed system design.
- Structured DSA preparation in Java for product-based SDE interviews (80+ LeetCode problems solved).
- Building scalable event-driven microservices.

---

### 📊 Engineering Footprint

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shakthi-jayan&show_icons=true&theme=tokyonight&hide_border=true" height="165"/>
  <img src="https://streak-stats.demolab.com?user=shakthi-jayan&theme=tokyonight&hide_border=true" height="165"/>
</p>
