<h1 align="center">Hi, I'm Shakthi Jayan 👋</h1>
<h3 align="center">Software Development Engineer (Fresher, 2027) | Backend & Distributed Systems | Java · Spring Boot · React · Node.js</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/shakthi-jayan"><img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://shakthi-s-dev-hub.vercel.app"><img src="https://img.shields.io/badge/-Portfolio-000000?style=flat-square&logo=vercel&logoColor=white" /></a>
  <a href="https://leetcode.com/u/shakthi_jayan_"><img src="https://img.shields.io/badge/-LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white" /></a>
  <a href="mailto:shakthijayan19@gmail.com"><img src="https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>

---

### 🚀 About Me

I'm a software developer specializing in backend and full-stack systems (Spring Boot, Node.js, MERN), transitioning into software engineering from a Chemical Engineering background through self-driven, project-based learning.

Most recently, I built **Sentinel Gateway** — a distributed API gateway built from scratch in Spring Boot — with JWT authentication, Redis-backed rate limiting, and a circuit breaker verified by killing a service mid-traffic and confirming self-recovery. Load tested with k6: 1,194 of 1,206 requests correctly throttled (99%) under sustained load.

I'm a final-year B.Tech student (Chemical Engineering, expected May 2027) who taught myself backend engineering and shipped production-style systems along the way, with active DSA preparation (80+ LeetCode problems) for product-based SDE roles.

**Looking for:** Software Engineer / Backend Developer roles at product-based companies where I can keep building systems that scale and learn from strong engineering teams.

---

### 🛠️ Tech Stack

**Languages:** ![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Backend & APIs:** ![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Spring Cloud Gateway](https://img.shields.io/badge/-Spring%20Cloud%20Gateway-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/-Express.js-000000?style=flat-square&logo=express&logoColor=white) ![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white) ![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)

**Frontend:** ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Tailwind](https://img.shields.io/badge/-Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

**Data & Infra:** ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Resilience & Testing:** Bucket4j (rate limiting) · Resilience4j (circuit breaking) · JWT · Git/GitHub · Postman · k6 (load testing) · Linux · Vercel

---

### 📌 Featured Project

#### [Sentinel Gateway — Distributed API Gateway & Rate Limiter](https://github.com/shakthi-jayan/sentinel-gateway)
A distributed API gateway built from scratch in Spring Boot, handling authentication, per-client rate limiting, and fault tolerance across multiple backend microservices.

- **Distributed rate limiting:** Token-bucket algorithm (Bucket4j) backed by Redis, so limits hold consistently across multiple gateway instances — not just an in-memory counter
- **JWT authentication as a trust boundary:** requests are validated at the gateway before ever reaching a downstream service
- **Circuit breaker (Resilience4j):** detects downstream failures, fails fast with a fallback, and recovers automatically — verified by killing a service mid-traffic
- **Load tested with k6:** 1,206 requests from 10 concurrent virtual users in 15 seconds, with 99% correctly throttled once the rate limit was reached
- **Fully containerized** with Docker Compose on a custom bridge network

**Stack:** Java 25, Spring Boot 4.1, Spring Cloud Gateway, Redis, Bucket4j, JWT, Resilience4j, Docker Compose, k6

---

### 💼 Other Projects

#### [CodeCommerce — Full Stack E-Commerce Platform](https://commerce-core-frontend.vercel.app) · [GitHub](https://github.com/shakthi-jayan/commerce-core)
- Reduced checkout drop-offs by 25% by integrating Razorpay with an asynchronous cart pipeline
- Improved frontend media delivery speed by 40% via Cloudinary automated processing and lazy-loading
- Refactored Express routes into a modular architecture and indexed high-traffic MongoDB Atlas fields for scalability
- **Stack:** React, Node.js, Express.js, MongoDB, Razorpay, Cloudinary

#### [Pecafoo — Hyperlocal Food Delivery Platform](https://github.com/shakthi-jayan/pecafoo) · *Live in production*
- Real-time order tracking via Django Channels
- OSRM-based delivery routing
- **Stack:** Django REST Framework, PostgreSQL/PostGIS, Redis, Celery, React

#### Spring Boot Authentication Microservice
- 9-module microservice covering JWT rotation, RBAC, OAuth2, and 2FA
- **Stack:** Java, Spring Boot, Spring Security

#### [Task Manager — Full Stack MERN Application](https://github.com/shakthi-jayan/task-manager) · [Live Demo](https://task-manager-demo.vercel.app)
- Secured user session routes with custom JWT middleware validation
- Reduced frontend rendering latency by 15% through decoupled React state and reusable components
- Built automated Postman regression suites covering CRUD API routes
- **Stack:** React, Node.js, Express.js, MongoDB, JWT

---

### 💼 Experience

**Full Stack Development Tutor** — CSC Computer Science College, Chennai *(Oct 2023 – Present)*
- Mentored and code-reviewed 100+ students, achieving a 95% project completion and graduation rate across Python, React.js, and modern JavaScript modules
- Designed structured workshops on debugging environments, Git branching, and REST architecture patterns

**Python Programming Virtual Intern** — CodSoft (Remote) *(Aug 2024 – Sep 2024)*
- Built individual software utilities focused on performance profiling and OOP module separation
- Maintained a 100% milestone compliance record across remote team repositories using version control tracking protocols

---

### 🎓 Education

**B.Tech, Chemical Engineering** — Vel Tech High Tech Dr. Rangarajan Engineering College, Chennai *(Expected May 2027)* · CGPA 7.40
**Honours Diploma in Computer Applications (HDCA)** — CSC Computer Science College, Chennai *(2023)*

*Core software engineering skills developed through self-directed, project-based learning outside formal coursework — see Projects & Tech Stack above.*

---

### 🧠 Currently Focused On

- Deepening backend and distributed-systems fundamentals (rate limiting, resilience patterns, gateway architecture)
- Structured DSA preparation in Java for product-based SDE interviews (80+ LeetCode problems solved so far)
- Extending Sentinel Gateway with observability (Prometheus metrics) and environment-based secrets management

---

### 📊 Engineering Footprint

<p align="center">
  <img src="https://github-readme-stats.herokuapp.app/api?username=shakthi-jayan&show_icons=true&theme=tokyonight&hide_border=true" height="165"/>
  <img src="https://streak-stats.demolab.com?user=shakthi-jayan&theme=tokyonight&hide_border=true" height="165"/>
</p>

<p align="center"><i>"First solve the problem, then write the code."</i></p>
