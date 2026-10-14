# Hi, I'm Abdul Rehman

### AI Engineer | Full Stack (TypeScript · Python) | RAG · LLM Apps

I build production-grade AI applications and web systems where **backend architecture, real-time voice and AI workflows, and data integrity actually matter**. My experience spans AI voice agents, AI-powered SaaS products, fintech and banking platforms, multi-tenant CRMs, and e-commerce systems. I work across the full lifecycle of a product, from **database design and API architecture to authentication, asynchronous processing, LLM integrations, Dockerized infrastructure, and production deployment**.

I currently work with **TypeScript, Python, NestJS, FastAPI, React, Next.js, PostgreSQL, Redis, and modern cloud infrastructure**, with a particular interest in building secure, scalable backends and AI-enabled products.

---

## What I Build

* **AI voice agents** with real-time STT, LLM, and TTS pipelines (LiveKit, Twilio SIP, Deepgram, Cartesia, OpenAI)
* **RAG applications and LLM tool-calling workflows** with FastAPI, Gemini, and ChromaDB
* Scalable REST APIs and backend services with **Node.js / NestJS** and **Python / FastAPI**
* Multi-tenant SaaS systems with strict **organization-level data isolation**
* Fintech and payment workflows with **RBAC, authentication, KYC, and transaction processing**
* AI-powered applications using **OpenAI, Gemini, LLM orchestration, and file-ingestion pipelines**
* Real-time systems using **Socket.IO, Pusher, Redis, and BullMQ**
* E-commerce platforms with **payments, inventory, orders, and role-based administration**
* Production deployments using **Docker, Ubuntu, PM2, Nginx, and AWS EC2**

---

## Production Experience

### AI Voice Agents for a Dealership Platform

**NestJS · LiveKit · Twilio SIP · Deepgram · Cartesia · OpenAI · PostgreSQL · PM2**

* Built real-time voice agents with an STT → LLM → TTS pipeline (Deepgram, GPT-4o-mini, Cartesia) and Silero voice activity detection, running inside the NestJS application lifecycle.
* Bridged Twilio SIP trunks to LiveKit rooms for inbound and outbound AI phone conversations.
* Implemented LLM tool calling for vehicle inventory search and test-drive scheduling, synced with Google Calendar and PostgreSQL.
* Built a node-based IVR flow engine with DTMF input, branching, call transfers, and voicemail using Twilio TwiML.
* Moved heavy text-to-speech synthesis into background workers, fixing gateway timeouts on save requests.
* Secured internal worker callbacks with a custom NestJS guard and deployed on Linux with PM2.

### AI-Powered Dealership CRM

**NestJS · React · PostgreSQL · Twilio · OpenAI**

* Built an AI-first lead-routing workflow connecting Twilio TaskRouter with AI-to-human handoff.
* Fixed cross-system email identity issues affecting authentication, billing, and Gmail synchronization.
* Optimized Gmail ingestion through deduplication and cron locking for large datasets.
* Added manual lead intake so offline leads could enter the same AI-powered nurture pipeline.
* Reduced Google OAuth calendar permissions and implemented privacy requirements to unblock production scheduling.

### Amana Pay: Digital Wallet & Banking Platform

**Angular · Node.js · Express · Redis · BullMQ**

* Built full-stack fintech functionality integrating core banking systems and national payment infrastructure.
* Implemented MPIN/device authentication and RBAC.
* Developed secure bank-to-wallet transaction flows.
* Built KYC, QR/bill payment, and real-time transaction functionality.
* Used Redis caching and BullMQ for asynchronous processing.

### Scribe: AI Study Platform

**Next.js · tRPC · OpenAI · PostgreSQL · Prisma · Pusher · Stripe**

Built an AI learning platform capable of transforming PDFs and notes into study guides, flashcards, worksheets, and podcasts, with LLM orchestration, spaced repetition, real-time updates, and subscription billing.

---

## Selected Projects

### FastAPI Gemini RAG Chatbot

**Python · FastAPI · Gemini · ChromaDB · Pydantic**

An AI chatbot backend with streaming responses, per-session conversation memory, model-driven tool calling, and retrieval-augmented generation over a policy document. Structured with a service layer and dependency injection.

* Streams replies token by token
* Lets the model decide when to call tools or search the document via RAG
* Answers "I don't know" instead of guessing when the document has no answer

### Multi-Tenant CRM

**NestJS · Next.js · PostgreSQL · Prisma · JWT · Docker**

A production-oriented multi-tenant CRM designed around strict organization-level data isolation.

* Organization-scoped JWT authentication
* Strict tenant data isolation
* Concurrency-safe customer assignment
* Prisma transactions and row locking
* Database indexing designed for **100k+ customers per organization**

### Black Pearl E-Commerce Platform

**NestJS · Next.js · PostgreSQL · Stripe · Cloudinary**

A complete three-application commerce ecosystem consisting of:

* Customer storefront
* Seller/admin dashboard
* Backend API

Implemented Stripe checkout, Cloudinary media management, role-based authentication, cart and order management, and inventory synchronization.

---

## Technical Stack

### Languages

`TypeScript` `JavaScript` `Python` `SQL`

### Frontend

`React` `Next.js` `Angular` `Tailwind CSS` `MUI` `shadcn/ui` `Vite` `Redux Toolkit` `TanStack Query`

### Backend

`Node.js` `NestJS` `Express` `Fastify` `FastAPI` `REST APIs` `JWT` `RBAC` `tRPC`

### Databases & Data

`PostgreSQL` `MongoDB` `Microsoft SQL Server` `Prisma` `Mongoose` `Redis` `BullMQ` `ChromaDB`

### AI & Real-Time

`OpenAI` `Google Gemini` `RAG` `Embeddings` `LLM Tool Calling` `Streaming Responses` `LiveKit` `Twilio SIP` `Deepgram` `Cartesia` `Socket.IO` `Pusher`

### Cloud & DevOps

`AWS EC2` `Docker` `Ubuntu` `PM2` `Nginx` `Cloudinary` `Supabase` `Stripe` `Git` `GitHub` `CI/CD`

### Testing & API Tooling

`Jest` `Swagger`

---

## Engineering Focus

I am particularly interested in:

* AI engineering: voice agents, RAG, and LLM tool calling
* Backend architecture and scalable APIs
* Distributed and asynchronous processing
* Multi-tenant SaaS architecture
* Fintech and payment systems
* Database design and data integrity
* Real-time communication systems
* Cloud infrastructure and production deployment

---

## Featured Repositories

### FastAPI Gemini RAG Chatbot

FastAPI backend with Gemini streaming, tool calling, and RAG using ChromaDB.

### Black Pearl Backend

NestJS backend for an e-commerce platform covering products, orders, inventory, authentication, and related business workflows.

### Black Pearl Portal

Frontend/admin interface for managing the Black Pearl commerce ecosystem.

### Multi-Tenant CRM

A scalable CRM demonstrating tenant isolation, transactional workflows, concurrency handling, and production-oriented backend architecture.

### Task Manager

A full-stack application demonstrating authentication, CRUD workflows, real-time functionality, and backend/frontend integration.

---

## Professional Links

* **LinkedIn:** linkedin.com/in/rehmaandev
* **GitHub:** github.com/rehmaan4584
* **Portfolio:** rehman-portfolio.duckdns.org
* **Email:** [rehmaan.dev@gmail.com](mailto:rehmaan.dev@gmail.com)

---

## Current Direction

Building deeper expertise in **AI engineering (voice agents, RAG, LLM tool calling), backend architecture, NestJS and FastAPI, distributed systems, PostgreSQL, Redis, and production cloud infrastructure**.

I value systems that are not only functional, but also **secure, maintainable, observable, and capable of handling real production constraints**.
