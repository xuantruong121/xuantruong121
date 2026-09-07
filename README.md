<div align="center">

# Hi, I'm Xuan Truong 👋

**Software Engineering Student @ IUH | Fullstack Developer Intern**  
Passionate about backend systems, clean architecture, and practical cloud deployments.

📍 Go Vap District, Ho Chi Minh City, Vietnam

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nguyen_Do_Xuan_Truong-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nguyen-do-xuan-truong-7865b7285/)
[![Email](https://img.shields.io/badge/Email-xtruong121.work%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:xtruong121.work@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-xuantruong121-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/xuantruong121)

</div>

---

## 🎯 About Me

Software Engineering student at **Industrial University of Ho Chi Minh City (IUH)** with hands-on experience building backend APIs, fullstack applications, and deploying real-world systems to cloud/VPS environments (including a live commercial platform at [totobarbershop.vn](https://www.totobarbershop.vn/)).

Comfortable working with **Java Spring Boot 3**, **NestJS / Node.js**, **Next.js**, **React 19**, and **React Native (Expo)**. Actively seeking a **Fullstack / Backend Developer Intern** role at a tech product or outsourcing company where I can contribute to production features and learn from senior engineers.

- **Education:** Software Engineering, IUH (Aug 2022 – Present)
- **Technical Focus:** Backend API Development (Spring Boot 3, NestJS, Express), Database Modeling (PostgreSQL, MySQL), Authentication & Security (JWT, Redis token rotation), and Containerized Deployment (Docker, VPS)
- **Mindset & Learning:** Comfortable reading English technical documentation, RFC specifications, and third-party API references; fast learner and adaptable across different project requirements

---

## 💪 Technical Skills

| Domain | Technologies & Tools |
| :--- | :--- |
| **Backend** | `Java`, `Spring Boot 3`, `NestJS`, `Node.js`, `Express.js`, `Prisma ORM`, `Spring Security`, `RESTful API`, `Hexagonal Architecture`, `Modular Monolith` |
| **Frontend & Mobile** | `Next.js (App Router)`, `TypeScript`, `ReactJS (React 19)`, `React Native (Expo)`, `Tailwind CSS v4`, `Ant Design`, `Zustand`, `TanStack Query / Table`, `Platform View Splitter` |
| **Databases & Cloud** | `PostgreSQL 15`, `MySQL`, `MongoDB`, `Redis 7` (Cache & Rate Limiting), `AWS S3`, `Cloudinary`, `PayOS Payment Gateway` |
| **DevOps & Infrastructure** | `Docker & Docker Compose`, `GitHub Actions (CI/CD)`, `Linux / Ubuntu VPS`, `Caddy v2 (Auto SSL/HTTPS)`, `Postman`, `Swagger / OpenAPI`, `VS Code`, `IntelliJ IDEA` |

---

## 🔥 Featured Projects

### 💈 ToTo Barbershop — Barber. Culture. Craft.
*Live Commercial Platform (Backend Developer & Deployment) • Jul 2026 – Present*  
**Website:** [totobarbershop.vn](https://www.totobarbershop.vn/) • **Backend Repository:** [github.com/toto-barbershop/toto-babershop-backend](https://github.com/toto-barbershop/toto-babershop-backend)

A production e-commerce and booking platform for ToTo Barbershop, operating live at [totobarbershop.vn](https://www.totobarbershop.vn/). Handled the backend API development, database design, payment integration, and VPS deployment pipeline.

- **Backend Development:** Built RESTful APIs using Express 5, TypeScript, and Prisma ORM on PostgreSQL 15; implemented business logic for appointment bookings, product variants (size/color), shopping cart, promo codes, and customer reviews.
- **Security & Caching:** Configured distributed rate-limiting with Redis 7 to protect authentication and checkout routes; applied schema validation with Zod, Helmet security headers, and bcrypt password hashing.
- **Payment Integration:** Integrated the PayOS payment gateway with automated QR-code checkout and verified IPN webhook signatures for real-time order status updates and stock consistency.
- **VPS Deployment & CI/CD:** Deployed services to an Ubuntu 22.04 LTS VPS with Docker Compose and Caddy v2 (automated Let's Encrypt SSL); built a GitHub Actions CI/CD pipeline that runs Vitest unit tests, creates pre-deploy PostgreSQL backups (`pg_dump`), and updates containers with health-check rollbacks.

> **Tech Stack:** `Node.js` • `Express 5` • `TypeScript` • `Prisma ORM` • `PostgreSQL 15` • `Redis 7` • `PayOS` • `Docker Compose` • `Caddy (SSL)` • `Ubuntu VPS` • `GitHub Actions`

---

### 🛒 SEBook — E-Commerce Bookstore Platform
*Team Project (Full-Stack Contributor — Auth & Account Modules) • Jan 2026 – Jun 2026*  
**Repository:** [github.com/xuantruong121/SEBook-E-Commerce-Bookstore-Platform](https://github.com/xuantruong121/SEBook-E-Commerce-Bookstore-Platform)

Modular monolith e-commerce platform built with Hexagonal Architecture (Ports & Adapters) providing online bookstore workflows, secure authentication, and a standardized client data synchronization layer.

- **Authentication & Security:** Implemented a stateless JWT authentication system (RS256-ready) following Hexagonal Architecture; built Refresh Token Rotation with per-device reuse detection in Redis and HMAC-SHA256 OTP (5-minute TTL, single-use) to prevent token theft.
- **Frontend Pages & Account Module:** Developed 6 authentication pages (Login, Register, Forgot/Reset/Change Password, Admin Login) in React 19 + Ant Design with role-based redirects; delivered a full Account module with live avatar preview and cascading Province–District–Ward address CRUD.
- **Shared Query Infrastructure:** Authored reusable `useApiQuery` / `useApiMutation` custom hooks (TanStack Query wrapper with centralized error handling), adopted across 10+ feature modules by all 4 teammates to standardize API interactions.

> **Tech Stack:** `Java` • `Spring Boot 3` • `Spring Security` • `Redis` • `PostgreSQL` • `MySQL` • `React 19` • `TypeScript` • `Ant Design` • `TanStack Query`

---

### 💬 MiniZalo — Real-time Chat Application
*Team Project (Mobile Frontend Contributor) • Feb 2026 – Jun 2026*  
**Repository:** [github.com/xuantruong121/MiniZalo](https://github.com/xuantruong121/MiniZalo)

Cross-platform messaging mobile application inspired by Zalo, unifying mobile and web chat experiences through a single shared codebase with real-time STOMP messaging and offline resilience.

- **Cross-Platform Layout:** Implemented a "Platform View Splitter" using Expo Router and `Platform.OS` to unify Web and Mobile layouts from a single codebase, sharing 100% of Zustand state and API services across platforms.
- **Real-Time Messaging:** Integrated bi-directional chat over WebSocket (STOMP protocol) — including message recall, swipe-to-reply, animated emoji reactions, and synced pinned messages reflected instantly across connected clients.
- **Offline Cache & Optimistic UI:** Built an offline-first message cache (100-entry sliding window with deduplication) with optimistic UI updates and automatic rollback on failed sends, ensuring reliability under unstable network connections.

> **Tech Stack:** `React Native (Expo)` • `TypeScript` • `Zustand` • `WebSocket (STOMP)` • `AWS S3` • `Platform.OS`

---

### 📚 HaiTeBooks — Bookstore REST API (Solo)
*Solo Project (Backend Developer) • Oct 2025 – Nov 2025*  
**Repository:** [github.com/xuantruong121/HaiTeBooks_Backend](https://github.com/xuantruong121/HaiTeBooks_Backend)

A complete RESTful backend system built to power mobile bookstore applications, featuring secure VNPay payment processing, an automated promotion engine, and AI-driven semantic vector search.

- **RESTful API Design:** Independently built a backend of 15 REST controllers (Auth, Books, Orders, Cart, Payments, Promotions, Notifications, Admin), implementing N+1-free order processing, atomic stock deduction, and an automated promotion engine with audit logging.
- **VNPay Payment Integration:** Integrated the VNPay payment gateway with HMAC-SHA512 checksum validation and verified IPN callbacks with a 15-minute expiry window.
- **AI Semantic Search:** Implemented semantic search and RAG chatbot features using the Cohere Embed API, storing vector embeddings in MySQL and performing in-service cosine similarity ranking asynchronously to keep the API non-blocking.

> **Tech Stack:** `Java` • `Spring Boot 3.3` • `MySQL` • `Docker` • `VNPay API` • `Cohere Embed API` • `JPA / Hibernate`

---

## 🎓 Education

| Institution | Degree & Major | Timeline | Location |
| :--- | :--- | :--- | :--- |
| **Industrial University of Ho Chi Minh City (IUH)** | Engineer's Degree in Software Engineering | Aug 2022 – Present | Ho Chi Minh City, Vietnam |

---

## 🌟 Key Practical Highlights

- **Live Production Deployment (ToTo Barbershop — [totobarbershop.vn](https://www.totobarbershop.vn/)):** Built backend APIs with Express 5, Prisma, and PostgreSQL; set up Docker Compose, Caddy (auto-SSL), and automated GitHub Actions CI/CD with database backup on an Ubuntu VPS.
- **Complete REST APIs (HaiTeBooks):** Independently developed 15 REST controllers with N+1-free queries, atomic stock deduction, and VNPay HMAC-SHA512 payment integration.
- **Security & Caching (SEBook):** Implemented RS256-ready JWT auth, Hexagonal domain separation, and per-device Redis token reuse detection.
- **Team Collaboration & Reusability (SEBook):** Authored shared `useApiQuery` / `useApiMutation` hooks adopted across 10+ feature modules by 4 teammates.
- **Cross-Platform Mobile UX (MiniZalo):** Built Platform View Splitter in Expo Router, STOMP WebSocket messaging, and 100-entry sliding window offline cache with rollback.
- **AI Integration (HaiTeBooks):** Built non-blocking semantic search with Cohere Embed API and in-service cosine similarity ranking in MySQL.

---

<div align="center">

## 💬 Let's Connect

I am actively seeking a **Fullstack / Backend Developer Intern** role at an outsourcing or tech product company.

[![Email](https://img.shields.io/badge/Email-xtruong121.work%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:xtruong121.work@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nguyen_Do_Xuan_Truong-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nguyen-do-xuan-truong-7865b7285/)
[![GitHub](https://img.shields.io/badge/GitHub-xuantruong121-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/xuantruong121)

📱 **Phone:** (+84) 352 359 401 &nbsp;•&nbsp; 📍 **Location:** Go Vap District, Ho Chi Minh City, Vietnam

</div>
