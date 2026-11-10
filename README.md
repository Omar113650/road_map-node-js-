# road_map-node-js-<div align="center">

# Backend Development with Node.js Roadmap

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=black)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)

</div>

Becoming a proficient backend developer with Node.js requires a solid understanding of many concepts, tools, and technologies. This roadmap takes you step by step from the fundamentals of programming and the web, through building and securing real APIs, all the way to running backend systems in production and designing them at scale.

> **The core idea:** understand the foundation before the tool. Databases come before ORMs, Node.js comes before Express, and the advanced topics (architecture, distributed systems, system design) come **after** you understand every building block of the backend, not at the start.

---

## Levels

| Level | What you'll be able to do | Roadmap stages |
|---|---|---|
| [Beginner](#beginner) | Understand the web and write solid JavaScript | Preparation, Entry, Stages 0 – 1 |
| [Intermediate](#intermediate) | Build, secure, and test real APIs with a database | Stages 2 – 7 |
| [Advanced](#advanced) | Make backends fast, scalable, and production-ready | Stages 8 – 15 |
| [Additional Tools](#additional-tools) | Optional tools depending on your path | TypeScript, NestJS, Payments, Scraping |

<details>
<summary><b>Full path at a glance</b></summary>

```
Preparation → Entry & Basics
      │
      ▼
[0] Foundation ─► [1] Node.js ─► [2] Express & API Design ─► [3] Databases ─► [4] ORM & Architecture
      │
      ▼
[5] Auth & Security ─► [6] Production APIs ─► [7] Testing & Docs
      │
      ▼
[8] Redis & Performance ─► [9] Background Jobs ─► [10] Real-Time ─► [11] Concurrency
      │
      ▼
[12] Architecture ─► [13] Docker & Deployment ─► [14] Observability ─► [15] System Design
```

</details>

> **How to use this roadmap:** go in order. For topics where you only need one option (a SQL database, an ORM), pick one and master it instead of learning them all.

---

## Preparation:

<details>
<summary><b>CS Introduction</b></summary>

- CS Introduction

</details>

## Entry & Basics:

<details><summary>How the Internet Works</summary>

- How the Internet Works

</details>

<details><summary>أساسيات ومفاهيم الشبكات</summary>

- أساسيات ومفاهيم الشبكات

</details>

<details><summary>What is HTTP?</summary>

- What is HTTP?
- Related topics: Client / Server, DNS, JSON

</details>

<details><summary>What is API?</summary>

- What is API?

</details>

<details><summary>How does a browser work?</summary>

- How does a browser work?

</details>

<details><summary>ملخص ايه اللي بيحصل من ورا لما بتفتح موقع انترنت</summary>

- ملخص ايه اللي بيحصل من ورا لما بتفتح موقع انترنت

</details>

<details><summary>Command Line</summary>

- Command Line

</details>

---

<a id="beginner"></a>

# Beginner Level

## Stage 0 — Pre-Backend Foundation

> Before starting Node.js, the fundamentals need to be solid first.

<details>
<summary><b>Programming Fundamentals</b></summary>

- Problem Solving
- Data Structures Basics
- Algorithms Basics
- OOP Basics

</details>

### Frontend Basics *(optional, stick to the basics)*

You don't need to be a frontend developer, but you should be able to read HTML/CSS and understand what the browser receives from your server.

**HTML & CSS Crash Courses:**

- HTML Crash Course - Bro Code
- CSS Crash Course - Abdelrahman Gamal
- HTML & CSS Crash Course - Codezilla
- HTML & CSS Crash Course - DesignCourse

**For more details (you can stick to the basics, but you can go deeper):**

- HTML In One Video - Elzero
- CSS In One Video - Elzero
- HTML CSS Design 1 - Elzero
- HTML CSS Design 2 - Elzero

### JavaScript Fundamentals

<details>
<summary><b>Essential concepts to master</b></summary>

- Syntax, Functions
- Arrays / Objects, Array Methods
- Scope, Closures
- Destructuring
- Map / Set

**Advanced JavaScript basics:**

- Asynchronous JavaScript
- Promises
- Async/Await
- Event Loop
- Error Handling
- Modules

</details>

**Resources**

- JavaScript Course - Elzero
- Modern JavaScript Tutorial - Net Ninja
- Asynchronous JavaScript - Net Ninja
- W3Schools JavaScript Tutorial
- ES6 JavaScript - Yallacode
- JavaScript Course - Abdelrahman Gamal
- CodeCademy JavaScript Course
- JavaScript Tutorial - SuperSimpleDev
- JS Advanced Tutorial

**JS OOP**

- JavaScript OOP Course

**JavaScript Behind the Scenes**

- Shadow Coding

### Developer Fundamentals

<details>
<summary><b>Topics</b></summary>

- Git & GitHub
- Command Line
- Environment Variables

</details>

---

## Stage 1 — Node.js Fundamentals

> Understand Node.js itself before working with any framework.

<details>
<summary><b>Topics</b></summary>

- Node.js Runtime
- V8 Engine
- Event Loop
- npm
- Modules (CommonJS / ES Modules)
- `process`
- Environment Variables
- File System
- Path
- Events
- HTTP Module
- Streams & Buffers Basics

</details>

**Resources**

- Node.js Tutorial - codeZone (1:3)
- Node.js - KMR Script (1:6)
- NodeJS - تخاريف مبرمج (1:20)
- NodeJS Crash Course - Net Ninja (1:5)
- Node.js Basics - Academind (1:6)
- W3Schools Node.js Tutorial

---

<a id="intermediate"></a>

# Intermediate Level

## Stage 2 — Backend & Express

> This is where real backend building begins.

<details>
<summary><b>HTTP & API Design</b></summary>

- HTTP Methods, Status Codes, Headers, Cookies
- REST & API Design
- Request / Response
- Pagination, Filtering, Sorting, Searching
- RESTful API design with the JSend specification (success, fail, and error responses)
- CORS & Security Headers

</details>

<details>
<summary><b>Express.js</b></summary>

- Routing
- Middleware
- Controllers & Services
- Error Handling (global error handler, custom error classes)
- Configuration & Environment Management (dotenv)
- API Versioning
- Static Files & Template Engines

</details>

**Express.js Resources**

- Express.js & MongoDB Course - codeZone (4:11)
- Youssef Abbas (7:63)
- KMR Script (13:79)
- Emam Academy
- Express.js Tutorial
- Youssef Abbas - Blog App *(project to practice)*

### API Tools: Postman & Swagger

<details>
<summary><b>Topics</b></summary>

- Postman
- Swagger / OpenAPI
- API documentation rules

</details>

- QAcart - Postman Course
- Automation - Postman
- Muhammed Essa - Swagger API Design and Documentation
- Braintemple - API Documentation with Swagger

### Server-Side Rendering vs. Client-Side Rendering

- Amr Mohamed - Server-Side vs Client-Side Rendering Explained

---

## Stage 3 — Database Fundamentals

> Before any ORM, the database itself needs to be understood first.

<details>
<summary><b>Database Concepts</b></summary>

- DBMS
- Relational vs NoSQL
- Tables & Relationships
- Primary / Foreign Keys
- Normalization
- ERD & UML Diagrams

</details>

**Database Types — pick one SQL database as your primary choice (usually PostgreSQL):**

- Relational (SQL): MySQL / PostgreSQL / SQL Server / SQLite
- Non-Relational (NoSQL): MongoDB, for document-based and unstructured data

<details>
<summary><b>SQL</b></summary>

- CRUD
- SELECT / WHERE
- JOIN
- GROUP BY & Aggregation
- Subqueries
- Views
- Constraints
- Indexes

</details>

<details>
<summary><b>NoSQL (MongoDB)</b></summary>

- Collections & Documents
- Schema Design
- CRUD Operations
- Aggregation Pipeline
- Indexing
- When to choose NoSQL over SQL
- Mongoose ODM: models & schemas, validation, population, middleware

</details>

<details>
<summary><b>Database Internals</b></summary>

- Transactions
- ACID
- Isolation Levels
- Locks
- Concurrency
- Deadlocks

</details>

**Database Design**

- Database Design Course - freeCodeCamp.org
- Database Course
- Database Design - Bedoo Bader
- Database Design - SAF1
- Database Design - Very Academy
- Database Design - Database Star

**MongoDB Courses**

- Mohamed Ramdan - MongoDB Course
- Academind - MongoDB

**SQL inside Node.js**

- SQL in Node.js - KMR Script
- SQL in Node.js - Software3
- Node Postgres Official Website
- Node.js SQL Tutorial

**UML Diagrams**

- UML Diagrams Full Course - freeCodeCamp
- Visual Paradigm UML Guide
- UML Distilled Guide

---

## Stage 4 — ORM & Backend Architecture

<details>
<summary><b>ORM (Object-Relational Mapping)</b></summary>

- The general idea: why use an ORM instead of raw SQL
- Schema, Relations, Querying
- Migrations
- Transactions

</details>

> Prisma, Sequelize, and TypeORM mostly serve the same purpose. **Master one and switch only when needed.**

- What are ORMs - Playlist
- ORM Comparison Tutorial
- ORM Deep Dive
- Prisma
- Sequelize
- TypeORM
- Database Migrations Tutorial

<details>
<summary><b>Backend Architecture</b></summary>

- MVC
- Controller / Service / Repository
- Separation of Concerns
- Dependency Injection (concept)
- Design Patterns Basics
- SOLID
- Clean Code

</details>

**Architecture**

- Introduction to MVC Architecture with Express and Node.js - PedroTech
- Design Patterns - AbuGhazaleh
- MVC Pattern - Piyush Garg

**SOLID Principles**

- SOLID Principles - Omar Ahmed
- SOLID Principles in JS - Mahmoud Abdullah
- SOLID Principles in JS - Rethinking UI

---

## Stage 5 — Authentication & Security

> Once there's an API and a database in place, it's time for security.

<details>
<summary><b>Authentication</b></summary>

- Password Hashing (hashing vs. encryption)
- Sessions
- JWT (Access & Refresh Tokens)
- Token Rotation
- Logout & Account Invalidation

</details>

<details>
<summary><b>Authorization</b></summary>

- RBAC (Role-Based Access Control)
- Permissions
- Guards / Middleware, Protected Routes

</details>

<details>
<summary><b>Security</b></summary>

- CORS
- CSRF
- XSS Basics
- SQL / NoSQL Injection
- Rate Limiting
- Helmet
- Secure Cookies
- Secrets Management

</details>

<details>
<summary><b>Advanced Authentication</b></summary>

- OAuth 2.0 (Google Login, social login)
- Passport.js (Local, JWT, and OAuth strategies)
- Email Verification
- Password Reset

</details>

**Resources**

- Code With Zeyad - Authentication
- Almdrasa - OAuth
- Algorithm Academy - Passport.js

---

## Stage 6 — Building Production APIs

> The shift from junior CRUD developer to backend engineer.

<details>
<summary><b>API Engineering</b></summary>

- Advanced Pagination, Filtering, Sorting, Search
- API Versioning
- Response Standardization
- Validation
- Error Handling & Logging
- Configuration Management

</details>

<details>
<summary><b>Files & External Services</b></summary>

- File Upload with Multer (single, multiple, filtering, storage configuration)
- Cloud Storage
- Email / SMS
- Third-party APIs
- Webhooks

</details>

---

## Stage 7 — Testing & Documentation

<details>
<summary><b>Testing</b></summary>

- Unit Testing
- Integration Testing
- API Testing
- Jest / Supertest
- Mocking
- Test Database
- Test-Driven Development (TDD)

</details>

<details>
<summary><b>Documentation & Development Quality</b></summary>

- Swagger / OpenAPI
- API Contracts
- Linting & Formatting
- Git Branching
- Pull Requests
- Code Review

</details>

**Unit Testing**

- Unit Testing with Jest - Anson the Developer
- Testing a MongoDB-ExpressJS-NodeJS App
- Software Testing - Tresmerge
- JavaScript Unit Testing with Jest - Elzero

---

<a id="advanced"></a>

# Advanced Level

## Stage 8 — Redis & Performance

<details>
<summary><b>Redis</b></summary>

- Caching
- Cache Invalidation
- TTL
- Cache Aside
- Redis Data Structures

</details>

<details>
<summary><b>Performance</b></summary>

- Query Optimization
- Database Indexing
- N+1 Problem
- Connection Pool
- Pagination Optimization
- Response Time
- Load Testing

</details>

<details>
<summary><b>API Protection</b></summary>

- Rate Limiting
- Throttling

</details>

**Redis**

- Redis Fundamentals
- Redis (2)
- Redis (3)

---

## Stage 9 — Background Processing

<details>
<summary><b>Background Jobs</b></summary>

- Job Queues (BullMQ / Redis Queues)
- Retry & Backoff
- Dead Letter Concepts
- Scheduled Jobs / Cron Jobs

</details>

<details>
<summary><b>Event-Driven Basics</b></summary>

- Events
- Producers / Consumers
- Pub/Sub
- RabbitMQ

</details>

**Task Scheduling**

- Task Scheduling (1)
- Task Scheduling (2)
- Task Scheduling in Node.js

---

## Stage 10 — Real-Time Backend

<details>
<summary><b>WebSockets</b></summary>

- WebSocket
- Socket.IO (setup, events, rooms)
- Real-Time Notifications

</details>

<details>
<summary><b>Real-Time Communication</b></summary>

- Presence
- Live Updates
- WebRTC *(optional, not essential for the backend track)*

</details>

---

## Stage 11 — Advanced Database & Concurrency

<details>
<summary><b>Topics</b></summary>

- Transactions & Isolation Levels
- Optimistic / Pessimistic Locking
- Deadlocks & Race Conditions
- Atomic Updates
- Idempotency
- Distributed Locks
- Read Replicas & Database Scaling

</details>

> This is where real System Design questions start to show up:
>
> - What happens if two requests arrive at the same time?
> - What if the operation fails mid-transaction?
> - What if the user clicks **Pay** twice?
> - What if 1000 requests hit the same resource?

---

## Stage 12 — Architecture

> This stage comes after understanding all the backend components.

<details>
<summary><b>Software Architecture</b></summary>

- Modular Monolith
- Layered Architecture
- Clean Architecture
- Repository Pattern
- Dependency Injection
- SOLID & Design Patterns

</details>

<details>
<summary><b>Distributed Systems Basics</b></summary>

- Load Balancing
- Horizontal Scaling
- Stateless Services
- Service Discovery (concept)
- Message Brokers
- Event-Driven Architecture
- Microservices

</details>

---

## Stage 13 — Docker & Deployment

<details>
<summary><b>DevOps Basics</b></summary>

- Linux Basics
- Docker & Docker Compose
- Nginx
- Environment Management

</details>

<details>
<summary><b>CI/CD & Cloud</b></summary>

- GitHub Actions
- Automated Tests
- Build & Deployment
- AWS Basics (Compute, Storage, Database, Networking)

</details>

**Containers**

- Docker - freeCodeCamp (English)
- Docker - TechWorld with Nana (English)
- Docker Practical Course (Arabic)

**Deployment**

- Deployment to Vercel
- Deployment to Azure App Service
- Deployment on Netlify

**Hosting**

- Hosting Explained
- Hosting Practical Guide

**Operating Systems**

- Operating Systems - Berkeley

---

## Stage 14 — Observability & Production

> The difference between "I know backend" and "I know how to run backend in production."

<details>
<summary><b>Observability</b></summary>

- Structured Logging
- Metrics & Monitoring
- Health Checks
- Tracing Basics
- Error Tracking

</details>

<details>
<summary><b>Reliability</b></summary>

- Timeouts & Retries
- Circuit Breaker
- Graceful Shutdown
- Rate Limiting
- Fault Tolerance

</details>

---

## Stage 15 — System Design

> The final stage, once all the backend building blocks are understood.

<details>
<summary><b>Fundamentals & Components</b></summary>

- Requirements & Constraints
- Trade-offs
- Scalability, Availability, Consistency
- Load Balancer, Cache, Database, Queue, Object Storage, Search, CDN

</details>

<details>
<summary><b>Case Studies: design these systems</b></summary>

- E-Commerce
- Booking System
- Notification System
- Ride-Hailing
- Payment System
- Chat System
- URL Shortener

</details>

---

<a id="additional-tools"></a>

# Additional Tools & Technologies

> Not part of the core sequence, but useful depending on your path.

## TypeScript

*Recommended after Stage 2 or 4, since most modern Node.js jobs expect it.*

<details>
<summary><b>Topics</b></summary>

- Syntax & Types
- Interfaces
- Generics
- Using it with Express

</details>

- TS - Elzero
- TS - Youssef Abbas
- TS - Index Academy
- TS - Simple Arab Code
- TS - Scripter Efendi
- Express with TypeScript - Anson the Developer

## NestJS *(optional alternative to Express)*

<details>
<summary><b>Roadmap</b></summary>

**Getting Started**

- Node.js and npm/yarn installation
- TypeScript setup and configuration
- NestJS CLI installation and basic commands
- Project structure and architecture
- Modules, controllers, and providers

**Core Concepts**

- Dependency Injection
- Decorators
- Middleware
- Exception filters
- Pipes and validation
- Guards
- Interceptors

**Database Integration**

- TypeORM: connection, entities and relationships, repository pattern, migrations, query builder
- Mongoose: connection, schemas, models, CRUD

**Authentication & Authorization**

- Passport integration
- JWT implementation
- Guards and strategies
- RBAC
- OAuth2

**Advanced Concepts**

- Swagger/OpenAPI integration
- Testing: unit, E2E, coverage, mocking
- WebSockets: gateways, Socket.IO
- Microservices: message patterns, transport layers, gRPC, Redis/RabbitMQ

**Performance, Security & Deployment**

- Caching (Redis)
- Helmet, CORS, rate limiting
- Logging, monitoring, error handling
- Docker, CI/CD, production best practices

</details>

**Learning Resources**

- NestJS Official Documentation
- NestJS GitHub Repository
- NestJS Courses - Index Academy
- NestJS - Anson the Developer
- NestJS - Sakura Dev
- NestJS - Mahmoud Abdullah
- NestJS - freeCodeCamp.org
- NestJS - Code With tkssharma
- Microservices with NestJS - Mahmoud Abdullah

## Payment Gateways

<details>
<summary><b>Topics</b></summary>

- Payment Integration Concepts
- Stripe / Paymob and others

</details>

- Payment Integration Playlist
- Payment Gateway Tutorial 1
- Payment Gateway Tutorial 2

## Web Scraping & Browser Automation (Puppeteer)

- Puppeteer Automation - Playlist 1
- Puppeteer Scraping - Playlist 2

## Task Scheduling

- Cron Jobs
- Scheduled Tasks in Node.js

## Software Engineering Practices

- SDLC (Software Development Lifecycle)
- Agile Workflow
- DevOps Workflow
- Operating Systems Basics

**Clean Code & Refactoring**

- Clean Code
- Refactoring to Patterns
- Martin Fowler

---

<div align="center">

**Embrace your Node.js journey with curiosity and determination!**

Keep searching for knowledge and new solutions as you build powerful applications and unlock your potential.

**Happy Learning!**

</div>
