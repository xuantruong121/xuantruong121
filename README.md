# Hi, I'm Xuan Truong 👨‍💻

**Software Engineering Student @ IUH | Fullstack Developer Intern**  
Building production-ready backend systems, modular software architectures, and cross-platform applications.

📍 Go Vap District, Ho Chi Minh City, Vietnam

[![Portfolio Demo](https://img.shields.io/badge/Live_Portfolio-xuantruong121.github.io-2563eb?style=flat-square)](https://xuantruong121.github.io/portfolio-software-engineer/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nguyen_Do_Xuan_Truong-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nguyen-do-xuan-truong-7865b7285/)
[![Email](https://img.shields.io/badge/Email-xtruong121.work%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:xtruong121.work@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-xuantruong121-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/xuantruong121)

---

## 🎯 About Me

**Quick Tech Stack:** Java • Spring Boot 3 • ReactJS (React 19) • React Native (Expo) • MySQL • PostgreSQL • Redis • Docker • AWS S3 • Cloudinary

- 👨‍🎓 Software Engineering student at Industrial University of Ho Chi Minh City (IUH, Aug 2022 – Present) — **GPA: 3.19 / 4.0**
- 💻 Fullstack Developer with hands-on experience across Spring Boot, React, and React Native
- 🎯 Seeking a **Fullstack / Backend Developer Intern** role at an outsourcing or tech product company
- 🌍 Based in Go Vap District, Ho Chi Minh City, Vietnam
- 📚 Comfortable reading English technical documentation, RFC specifications, and adapting quickly across tech stacks and client requirements

I focus on building production-oriented full-stack web and mobile applications, designing secure RESTful APIs, and implementing clean software architectures. My primary expertise centers around Java Spring Boot 3 backends, React 19 & React Native cross-platform clients, relational and NoSQL databases, asymmetric JWT authentication, and resilient offline-first data caching.

I am especially interested in:
- **Backend Architecture:** Modular Monolith & Hexagonal Architecture (Ports & Adapters)
- **Security & Auth:** Stateless RS256-ready JWT, Refresh Token Rotation with per-device reuse detection in Redis, and HMAC-SHA256 OTP
- **Real-time Communication:** WebSocket with STOMP protocol for low-latency chat sync
- **Cross-platform Development:** Platform View Splitter pattern with Expo Router and React 19
- **Resilient Client State:** Standardized TanStack Query wrapper hooks and Zustand offline caching
- **Payment & Cloud Integration:** VNPay payment gateway (HMAC-SHA512), AWS S3, Cloudinary, and Docker containerization
- **AI-assisted Services:** Asynchronous semantic vector search with Cohere Embed API and RAG chatbot

---

## 🔥 Featured Projects

### 🛒 SEBook — E-Commerce Bookstore Platform
**Team Project** | **Full-Stack Contributor (Auth & Account Modules)** | **Jan 2026 – Jun 2026**  
**Stack:** Java, Spring Boot 3, Spring Security, Redis, PostgreSQL, MySQL, React 19, TypeScript, Ant Design, TanStack Query

SEBook is a modular monolith e-commerce bookstore platform engineered with Hexagonal Architecture (Ports & Adapters). The platform delivers resilient authentication, account management with cascading address structures, and a standardized client-side data-fetching layer adopted team-wide.

**Repository:** [SEBook-E-Commerce-Bookstore-Platform](https://github.com/xuantruong121/SEBook-E-Commerce-Bookstore-Platform)

**My Role:**
- Full-Stack Contributor in a 5-member team, leading the end-to-end implementation of the Auth & Account modules.
- Architected a stateless JWT authentication system (RS256-ready) using Hexagonal Architecture (Ports & Adapters), implementing Refresh Token Rotation with per-device reuse detection in Redis and HMAC-SHA256 OTP (5-minute TTL, single-use) to prevent token theft and replay attacks.
- Built 6 production-ready authentication pages (Login, Register, Forgot/Reset/Change Password, Admin Login) in React 19 + Ant Design with role-based redirects.
- Delivered a complete Account module with live avatar preview and cascading Province–District–Ward address CRUD.
- Designed and published reusable `useApiQuery` and `useApiMutation` hooks (TanStack Query wrapper with centralized error handling), adopted by all 4 team members across 10+ feature modules — eliminating ad-hoc fetch logic and standardizing API calls project-wide.

**Key Features:**
- Hexagonal Architecture (Ports & Adapters) enforcing strict boundary separation
- Stateless RS256-ready JWT authentication & authorization
- Per-device Refresh Token Rotation with reuse detection in Redis
- HMAC-SHA256 OTP with 5-minute TTL and single-use invalidation
- 6 authentication views with role-based routing and guard redirects
- Cascading Province–District–Ward address management and live avatar preview
- Centralized `useApiQuery` / `useApiMutation` data-fetching infrastructure

**Technical Summary:**
- **Tech Stack:** Java, Spring Boot 3, Redis, PostgreSQL, MySQL, React 19, TypeScript, Ant Design, TanStack Query
- **Architecture:** Modular Monolith, Hexagonal Architecture (Ports & Adapters)
- **Security:** RS256-ready JWT, Redis Per-Device Token Reuse Detection, HMAC-SHA256 OTP
- **Frontend:** React 19, TypeScript, Ant Design, Custom TanStack Query Hooks Wrapper
- **Teamwork:** 5-member team; authored shared query library adopted across 10+ feature modules

---

### 💬 MiniZalo — Real-time Chat Application
**Team Project** | **Mobile Frontend Contributor** | **Feb 2026 – Jun 2026**  
**Stack:** React Native (Expo), TypeScript, Zustand, WebSocket (STOMP), Platform.OS, AWS S3

MiniZalo is a cross-platform messaging application inspired by Zalo, unifying mobile and web chat experiences through a single shared codebase with real-time STOMP messaging and offline resilience.

**Repository:** [MiniZalo](https://github.com/xuantruong121/MiniZalo)

**My Role:**
- Mobile Frontend Contributor in a 5-member team.
- Engineered a cross-platform "Platform View Splitter" using Expo Router and `Platform.OS` to unify Web and Mobile experiences from a single codebase, sharing 100% of Zustand state and API services across platforms.
- Built real-time chat features over WebSocket (STOMP protocol) — including message recall, swipe-to-reply, animated emoji reactions, and synced pinned messages — reflected instantly across all connected devices.
- Developed an offline-first message cache (100-entry sliding window with deduplication) with optimistic UI updates and automatic rollback on failed sends, ensuring reliability under unstable network conditions.

**Key Features:**
- "Platform View Splitter" architecture unifying Web and Mobile from a single codebase
- 100% shared Zustand state management and REST/WebSocket API services across platforms
- Instant bi-directional messaging over WebSocket using STOMP protocol
- Interactive chat UX: message recall, swipe-to-reply, animated emoji reactions, and synced pinned messages
- Offline-first message cache with a 100-entry sliding window and deduplication
- Optimistic UI updates with automatic rollback on network failure
- Media uploads and static asset delivery integrated with AWS S3

**Technical Summary:**
- **Tech Stack:** React Native (Expo), TypeScript, Zustand, WebSocket (STOMP), AWS S3
- **Architecture:** Platform View Splitter (Expo Router + `Platform.OS`)
- **Real-time Protocol:** STOMP over WebSocket for instantaneous multi-device sync
- **Offline & Cache:** 100-entry sliding window with deduplication, optimistic UI & rollback
- **Teamwork:** 5-member team, core cross-platform mobile frontend contributor

---

### 📚 HaiTeBooks — Bookstore REST API (Solo)
**Solo Project** | **Backend Developer** | **Oct 2025 – Nov 2025**  
**Stack:** Java, Spring Boot 3.3, MySQL, Docker, VNPay API, Cohere Embed API, JPA/Hibernate

HaiTeBooks is a comprehensive RESTful backend system built to power mobile bookstore client applications, featuring secure VNPay payment processing, an automated promotion engine, and non-blocking AI-driven semantic vector search.

**Repository:** [HaiTeBooks_Backend](https://github.com/xuantruong121/HaiTeBooks_Backend)

**My Role:**
- Independently designed and built the complete backend system consisting of 15 REST controllers (Auth, Books, Orders, Cart, Payments, Promotions, Notifications, Admin, and more).
- Implemented high-efficiency database queries: N+1-free order processing, atomic stock deduction, and an automated promotion engine with scheduled auto-deactivation and audit logging.
- Integrated the VNPay payment gateway with HMAC-SHA512 signed transaction URLs and verified IPN callbacks, enforcing a 15-minute expiry window to prevent replay attacks.
- Built a lightweight AI-powered semantic search and RAG chatbot using the Cohere Embed API, storing vector embeddings in MySQL and performing in-service cosine similarity ranking, with all embedding generation processed asynchronously to keep the API non-blocking.
- Containerized the entire backend with Docker for reproducible deployment.

**Key Features:**
- 15 production REST controllers handling end-to-end bookstore operations
- N+1-free query optimization and atomic stock deduction during checkout
- Automated promotion engine with scheduled deactivation and audit logging
- VNPay payment integration with HMAC-SHA512 signature validation and 15-minute expiry window
- AI-powered semantic search with Cohere Embed vector embeddings in MySQL
- In-service cosine similarity ranking algorithm with asynchronous non-blocking embedding pipelines
- Docker containerization for predictable environments

**Technical Summary:**
- **Tech Stack:** Java, Spring Boot 3.3, MySQL, Docker, VNPay API, Cohere Embed API
- **Backend:** 15 REST Controllers, Spring Security, JPA/Hibernate, Promotion Engine, Audit Logging
- **Payment:** VNPay Payment Gateway (HMAC-SHA512 signed URLs, IPN callbacks, 15-min TTL)
- **AI & Search:** Cohere Embed API, MySQL Vector Storage, In-service Cosine Similarity, Async Non-blocking Processing
- **Deployment:** Docker

---

### 🌐 Personal Web Portfolio
**Personal Project** | **Frontend & UI/UX** | **React 19** | **TypeScript** | **Vite** | **GitHub Pages**

Interactive web portfolio showcasing my engineering projects, skills matrix, and professional background.

- **Website:** [xuantruong121.github.io/portfolio-software-engineer](https://xuantruong121.github.io/portfolio-software-engineer/)
- **Repository:** [xuantruong121](https://github.com/xuantruong121/xuantruong121)

**Key Features:**
- Custom Vanilla CSS dark glassmorphism design system with fluid typography and ambient glow
- Smooth scroll reveals and micro-interactions powered by Framer Motion
- Runtime dual-language switching (English / Vietnamese) via custom React Context
- Fully responsive layout across mobile, tablet, and desktop
- Automated static deployment workflow via GitHub Pages (`gh-pages`)

---

## 💪 Technical Skills

### Backend
- Java
- Spring Boot 3
- Spring Security
- RESTful API
- Stateless JWT (RS256-ready)
- Refresh Token Rotation & Reuse Detection
- JPA / Hibernate
- Hexagonal Architecture (Ports & Adapters)
- Modular Monolith

### Frontend
- TypeScript
- ReactJS (React 19)
- React Native (Expo)
- Ant Design
- TanStack Query (`useApiQuery` / `useApiMutation` custom wrapper)
- Zustand
- Platform View Splitter (Expo Router + `Platform.OS`)
- Responsive Web Design

### Database & Cloud Storage
- MySQL
- MongoDB
- PostgreSQL
- Redis (Token rotation & caching)
- AWS S3
- Cloudinary

### Tools & DevOps
- Git / GitHub
- Docker
- Postman
- Swagger / OpenAPI
- GitHub Pages (`gh-pages`)
- VS Code
- IntelliJ IDEA

---

## 📊 What I'm Working On

- 🏗️ Deepening Modular Monolith & Hexagonal Architecture (Ports & Adapters) domain boundaries
- 🔐 Advancing API security: asymmetric RS256 JWT, per-device Redis token reuse detection, and HMAC OTP
- 📱 Cross-platform architecture: Platform View Splitter with Expo Router, shared Zustand state, and offline caching
- ⚡ High-performance backend engineering: N+1-free queries, atomic transactions, and non-blocking async tasks
- 🐳 Production deployment: Docker containerization and cloud media integration (AWS S3, Cloudinary)
- 📚 Actively preparing for Fullstack / Backend Developer Internship opportunities

---

## 🎓 Education

**Industrial University of Ho Chi Minh City (IUH)**  
*Aug 2022 – Present*  
- **Major:** Software Engineering  
- **GPA:** **3.19 / 4.0**  
- **Location:** Ho Chi Minh City, Vietnam

---

## 🌟 Highlights

- ✅ **HaiTeBooks:** Independently engineered 15 REST controllers with N+1-free order processing, atomic stock deduction, and VNPay HMAC-SHA512 signed payment integration with a 15-minute replay window.
- ✅ **AI Semantic Search:** Implemented non-blocking AI vector search with Cohere Embed API, storing embeddings in MySQL and executing in-service cosine similarity ranking asynchronously.
- ✅ **SEBook:** Architected stateless RS256-ready JWT auth with Hexagonal Architecture and per-device Redis token reuse detection.
- ✅ **Reusable Query Library:** Designed and published unified `useApiQuery`/`useApiMutation` hooks adopted across 10+ feature modules by all 4 team members.
- ✅ **Production UI:** Built 6 production auth pages in React 19 + Ant Design with role-based redirects and cascading Province–District–Ward address CRUD.
- ✅ **MiniZalo:** Engineered cross-platform "Platform View Splitter" with Expo Router and WebSocket STOMP real-time chat.
- ✅ **Offline Resilience:** Developed a 100-entry sliding window message cache with deduplication, optimistic UI updates, and automatic rollback on network failure.
- ✅ **Academic Standing:** Maintained a cumulative GPA of **3.19 / 4.0** in Software Engineering at IUH.

---

## 💬 Let's Connect

I'm actively seeking an **Intern role (Fullstack / Backend Developer)** at an outsourcing or tech product company.

- 📧 **Email:** [xtruong121.work@gmail.com](mailto:xtruong121.work@gmail.com)
- 💼 **LinkedIn:** [linkedin.com/in/nguyen-do-xuan-truong-7865b7285](https://www.linkedin.com/in/nguyen-do-xuan-truong-7865b7285/)
- 🐙 **GitHub:** [github.com/xuantruong121](https://github.com/xuantruong121)
- 🌐 **Portfolio:** [xuantruong121.github.io/portfolio-software-engineer](https://xuantruong121.github.io/portfolio-software-engineer/)
- 📱 **Phone:** (+84) 352 359 401
- 📍 **Location:** Go Vap District, Ho Chi Minh City, Vietnam

---

*Thank you for visiting my profile! Feel free to explore my repositories and reach out if you would like to connect.*
