<div align="center">

# Hi, I'm Xuan Truong 👋

**Software Engineering Student @ IUH | Fullstack Developer Intern**  
Building production-ready backend systems, modular software architectures, and cloud-deployed applications.

📍 Go Vap District, Ho Chi Minh City, Vietnam

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nguyen_Do_Xuan_Truong-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nguyen-do-xuan-truong-7865b7285/)
[![Email](https://img.shields.io/badge/Email-xtruong121.work%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:xtruong121.work@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-xuantruong121-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/xuantruong121)
[![GPA](https://img.shields.io/badge/GPA-3.19%20%2F%204.0-059669?style=flat-square)](https://github.com/xuantruong121)

</div>

---

## 🎯 About Me

Software Engineering senior at **Industrial University of Ho Chi Minh City (IUH)** with hands-on experience as the sole Backend and DevOps engineer behind live commercial platforms (such as [totobarbershop.vn](https://www.totobarbershop.vn/)), alongside robust fullstack systems built with **Java Spring Boot 3**, **React 19**, and **React Native (Expo)**. Actively seeking a **Fullstack / Backend Developer Intern** role at an outsourcing or tech product company.

- **Academic Standing:** Software Engineering, IUH (Aug 2022 – Present) • Cumulative GPA: **3.19 / 4.0**
- **Engineering Focus:** Production Backend Engineering, Modular Monolith & Hexagonal Architecture, Asymmetric JWT (RS256), CI/CD Automation, Redis Caching & Rate Limiting, and Offline-first Mobile UX
- **Documentation & Adaptability:** Comfortable reading English technical specifications, RFC standards, and API documentation; adaptable across different tech stacks and project requirements

---

## 💪 Technical Skills

| Domain | Technologies & Tools |
| :--- | :--- |
| **Backend** | `Java`, `Spring Boot 3`, `Node.js`, `Express.js`, `Prisma ORM`, `Spring Security`, `RESTful API`, `Hexagonal Architecture`, `Modular Monolith` |
| **Frontend & Mobile** | `TypeScript`, `ReactJS (React 19)`, `React Native (Expo)`, `Tailwind CSS v4`, `Ant Design`, `Zustand`, `TanStack Query / Table` |
| **Databases & Cloud** | `PostgreSQL 15`, `MySQL`, `MongoDB`, `Redis 7` (Cache & Rate Limiting), `AWS S3`, `Cloudinary`, `PayOS Payment Gateway` |
| **DevOps & Infrastructure** | `Docker & Docker Compose`, `GitHub Actions (CI/CD)`, `Linux / Ubuntu VPS`, `Caddy v2 (Auto SSL/HTTPS)`, `Postman`, `Swagger / OpenAPI`, `VS Code`, `IntelliJ IDEA` |

---

## 🔥 Featured Projects

### 💈 ToTo Barbershop — Barber. Culture. Craft.
*Live Commercial Platform (Backend Developer & DevOps Lead) • Jul 2026 – Present*  
**Website:** [totobarbershop.vn](https://www.totobarbershop.vn/)  
**Backend Repository:** [github.com/toto-barbershop/toto-babershop-backend](https://github.com/toto-barbershop/toto-babershop-backend) • **Production API:** `https://160-30-157-229.sslip.io`

Production e-commerce and booking platform for ToTo Barbershop, operating live at [totobarbershop.vn](https://www.totobarbershop.vn/). Solely responsible for the entire backend architecture, database modeling, payment integrations, and end-to-end VPS deployment pipeline.

- **Full Backend Ownership:** Independently architected and implemented the complete RESTful backend using Express 5, TypeScript, and Prisma ORM on PostgreSQL 15; designed business flows for appointment bookings, multi-variant streetwear products, shopping carts, promo codes, and customer reviews.
- **Security & Distributed Rate Limiting:** Enforced distributed rate-limiting via Redis 7 to protect authentication and checkout endpoints from abuse; implemented strict request schema validation via Zod, Helmet security headers, and bcrypt password hashing.
- **Payment Gateway & Webhook Automation:** Integrated the PayOS payment gateway with automated QR-code checkout and verified IPN webhook signatures for atomic order state transitions and inventory integrity.
- **Production DevOps & CI/CD on VPS:** Configured and maintained an Ubuntu 22.04 LTS VPS environment using Docker Compose and Caddy v2 (automated Let's Encrypt SSL/HTTPS); engineered a GitHub Actions CI/CD pipeline that automates Vitest testing, pre-deploy PostgreSQL backups (`pg_dump`), and zero-downtime container updates with health-check rollbacks.

> **Tech Stack:** `Node.js` • `Express 5` • `TypeScript` • `Prisma ORM` • `PostgreSQL 15` • `Redis 7` • `PayOS` • `Docker Compose` • `Caddy (SSL)` • `Ubuntu VPS` • `GitHub Actions`

---

### 🛒 SEBook — E-Commerce Bookstore Platform
*Team Project (Auth & Account Lead) • Jan 2026 – Jun 2026*  
**Repository:** [github.com/xuantruong121/SEBook-E-Commerce-Bookstore-Platform](https://github.com/xuantruong121/SEBook-E-Commerce-Bookstore-Platform)

Modular monolith e-commerce platform built with Hexagonal Architecture (Ports & Adapters) delivering secure authentication, cascading address management, and a standardized client data synchronization layer.

- **Security & Auth Architecture:** Architected a stateless JWT authentication system (RS256-ready) using Hexagonal Architecture, implementing Refresh Token Rotation with per-device reuse detection in Redis and HMAC-SHA256 OTP (5-minute TTL, single-use) to prevent token theft and replay attacks.
- **Production UI & Account Module:** Built 6 production-ready authentication pages (Login, Register, Forgot/Reset/Change Password, Admin Login) in React 19 + Ant Design with role-based redirects; delivered full Account module with live avatar preview and cascading Province–District–Ward address CRUD.
- **Team Data Layer:** Designed and published reusable `useApiQuery` / `useApiMutation` hooks (TanStack Query wrapper with centralized error handling), adopted across 10+ feature modules by all 4 teammates — standardizing API calls project-wide.

> **Tech Stack:** `Java` • `Spring Boot 3` • `Spring Security` • `Redis` • `PostgreSQL` • `MySQL` • `React 19` • `TypeScript` • `Ant Design` • `TanStack Query`

---

### 💬 MiniZalo — Real-time Chat Application
*Team Project (Mobile Frontend Contributor) • Feb 2026 – Jun 2026*  
**Repository:** [github.com/xuantruong121/MiniZalo](https://github.com/xuantruong121/MiniZalo)

Cross-platform messaging application inspired by Zalo, unifying mobile and web chat experiences through a single shared codebase with real-time STOMP messaging and offline resilience.

- **Cross-Platform Unification:** Engineered a "Platform View Splitter" using Expo Router and `Platform.OS` to unify Web and Mobile from a single codebase, sharing 100% of Zustand state and API services across platforms.
- **Real-Time Communication:** Integrated real-time chat over WebSocket (STOMP protocol) — including message recall, swipe-to-reply, animated emoji reactions, and synchronized pinned messages reflected instantly across all connected devices.
- **Offline Resilience:** Developed an offline-first message cache (100-entry sliding window with deduplication) with optimistic UI updates and automatic rollback on failed sends, ensuring reliability under unstable networks.

> **Tech Stack:** `React Native (Expo)` • `TypeScript` • `Zustand` • `WebSocket (STOMP)` • `AWS S3` • `Platform.OS`

---

### 📚 HaiTeBooks — Bookstore REST API (Solo)
*Solo Project (Backend Developer) • Oct 2025 – Nov 2025*  
**Repository:** [github.com/xuantruong121/HaiTeBooks_Backend](https://github.com/xuantruong121/HaiTeBooks_Backend)

Comprehensive RESTful backend system designed to power mobile bookstore clients, featuring secure VNPay payment processing, an automated promotion engine, and non-blocking AI-driven semantic vector search.

- **Controller & Query Architecture:** Independently designed and built a complete backend system of 15 REST controllers (Auth, Books, Orders, Cart, Payments, Promotions, Notifications, Admin, and more), including N+1-free order processing, atomic stock deduction, and a promotion engine with scheduled auto-deactivation and audit logging.
- **Secure Payment Integration:** Integrated the VNPay payment gateway with HMAC-SHA512 signed transaction URLs and verified IPN callbacks, enforcing a 15-minute expiry window to prevent replay attacks.
- **AI Vector Search:** Built a lightweight AI-powered semantic search and RAG chatbot using the Cohere Embed API, storing vector embeddings in MySQL and performing in-service cosine similarity ranking asynchronously to keep the API non-blocking.

> **Tech Stack:** `Java` • `Spring Boot 3.3` • `MySQL` • `Docker` • `VNPay API` • `Cohere Embed API` • `JPA / Hibernate`

---

## 🎓 Education

| Institution | Degree & Major | Timeline | GPA | Location |
| :--- | :--- | :--- | :--- | :--- |
| **Industrial University of Ho Chi Minh City (IUH)** | Engineer's Degree in Software Engineering | Aug 2022 – Present | **3.19 / 4.0** | Ho Chi Minh City, Vietnam |

---

## 🌟 Key Engineering Highlights

- **Commercial Production Backend & VPS Deployment (ToTo Barbershop — [totobarbershop.vn](https://www.totobarbershop.vn/)):** Sole backend and DevOps engineer for a live commercial platform; designed complete REST APIs and database with Express 5, Prisma, and PostgreSQL; built automated GitHub Actions CI/CD with database backups and zero-downtime Docker rollout on an Ubuntu VPS with Caddy auto-SSL.
- **15 REST Controllers (HaiTeBooks):** Independently engineered end-to-end backend with N+1-free queries, atomic stock deduction, and VNPay HMAC-SHA512 signed payment integration.
- **Asymmetric JWT Security (SEBook):** Implemented RS256-ready JWT auth, Hexagonal domain boundaries, and per-device Redis token reuse detection.
- **Shared Query Infrastructure (SEBook):** Published unified `useApiQuery` / `useApiMutation` hooks adopted across 10+ feature modules by 4 team members.
- **Cross-Platform Architecture (MiniZalo):** Engineered "Platform View Splitter" in Expo Router, STOMP WebSocket messaging, and 100-entry sliding window offline cache.
- **AI Vector Search (HaiTeBooks):** Built non-blocking semantic search with Cohere Embed API and in-service cosine similarity ranking.

---

<div align="center">

## 💬 Let's Connect

I am actively seeking a **Fullstack / Backend Developer Intern** role at an outsourcing or tech product company.

[![Email](https://img.shields.io/badge/Email-xtruong121.work%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:xtruong121.work@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nguyen_Do_Xuan_Truong-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nguyen-do-xuan-truong-7865b7285/)
[![GitHub](https://img.shields.io/badge/GitHub-xuantruong121-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/xuantruong121)

📱 **Phone:** (+84) 352 359 401 &nbsp;•&nbsp; 📍 **Location:** Go Vap District, Ho Chi Minh City, Vietnam

</div>
