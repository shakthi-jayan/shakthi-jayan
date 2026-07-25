<div align="center">

# Hi, I'm Shakthi Jayan 👋
### Backend-Focused Full-Stack Developer | Spring Boot, Distributed Systems, MERN

I build backend systems and full-stack applications, with a growing focus on distributed systems, API infrastructure, and resilience patterns. Currently deep in Spring Boot, Redis, and Docker while preparing for product-based SDE roles -- transitioning into software engineering from a Chemical Engineering background through self-driven backend projects.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shakthi-jayan/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shakthi-jayan)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://shakthi-s-dev-hub.vercel.app/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shakthijayan19@gmail.com)

</div>

---

## Technical Expertise

* **Core Languages:** Java, Python, JavaScript (ES6+), C++, SQL
* **Backend & Systems:** Spring Boot, Spring Cloud Gateway, Node.js, Express.js, Django, Django REST Framework, Flask, RESTful API Design
* **Frontend Engineering:** React, Next.js, Tailwind CSS
* **Databases & Infra:** Redis, PostgreSQL, MySQL, MongoDB, Docker, Docker Compose, Firebase
* **Resilience & Distributed Systems:** Bucket4j (rate limiting), Resilience4j (circuit breaking), JWT authentication
* **Tools & Testing:** Git, GitHub, Postman, k6 (load testing)

---

## Featured Project

### Sentinel Gateway -- Distributed API Gateway & Rate Limiter
A distributed API gateway built from scratch in Spring Boot, handling authentication, per-client rate limiting, and fault tolerance across multiple backend microservices.

* **Distributed rate limiting:** Token-bucket algorithm (Bucket4j) backed by Redis, so the rate limit holds consistently even across multiple gateway instances -- not just an in-memory counter.
* **JWT authentication as a trust boundary:** requests are validated at the gateway before ever reaching a downstream service.
* **Circuit breaker (Resilience4j):** detects downstream failures, fails fast with a fallback, and automatically recovers -- verified by killing a service mid-traffic and confirming self-recovery.
* **Load tested with k6:** 1,206 requests from 10 concurrent virtual users in 15 seconds, with 99% correctly throttled once the rate limit was reached.
* **Fully containerized** with Docker Compose on a custom bridge network.

**Stack:** Java 25, Spring Boot 4.1, Spring Cloud Gateway, Redis, Bucket4j, JWT, Resilience4j, Docker Compose, k6
🔗 [Repository](https://github.com/shakthi-jayan/sentinel-gateway)

---

## Other Projects

### CodeCommerce -- Full Stack E-Commerce Platform
* Reduced checkout drop-offs by 25% by integrating Razorpay payment gateway with an asynchronous cart management pipeline.
* Improved frontend media delivery speed by 40% via Cloudinary automated processing and image lazy-loading.
* Refactored Express routes into a modular architecture and indexed high-traffic MongoDB Atlas fields for scalability.

**Stack:** React, Node.js, Express.js, MongoDB, Razorpay, Cloudinary
🔗 [Repository](https://github.com/shakthi-jayan/commerce-core) · 🌐 [Live Demo](https://commerce-core-frontend.vercel.app/)

### Task Manager -- Full Stack MERN Application
* Secured user session routes with custom JWT middleware validation, preventing unauthorized data access.
* Reduced frontend rendering latency by 15% through decoupled React state and reusable component design.
* Built automated Postman regression suites covering CRUD API routes.

**Stack:** React, Node.js, Express.js, MongoDB, JWT
🔗 [Repository](https://github.com/shakthi-jayan/task-manager-fullstack) · 🌐 Live Demo

---

## Currently Focused On

* Deepening backend and distributed-systems fundamentals (rate limiting, resilience patterns, gateway architecture)
* Structured DSA preparation in Java for product-based SDE interviews (80+ LeetCode problems solved so far)
* Extending Sentinel Gateway with observability (Prometheus metrics) and environment-based secrets management

---

## Engineering Footprint

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=shakthi-jayan&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=shakthi-jayan&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="48%" />
</div>

---

<div align="center">

*"First solve the problem, then write the code."*

</div>
