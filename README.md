### Hey there 👋🏻 I'm Mateus Siqueira

**Backend Engineer | Fintech Specialist | Performance & Algorithms**

```
11+ years building robust, scalable systems.
Focused on financial architecture, security, and real-world optimization.
```

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mateussiqueira&show_icons=true&theme=dark&hide_border=true&count_private=true)](https://github.com/mateussiqueira)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mateussiqueira&layout=compact&theme=dark&hide_border=true)](https://github.com/mateussiqueira)

---

## What I do

I build fast backends and secure financial systems:

- 🏦 **Financial Systems**: SPI, DICT, ISO 8583, ISO 20022, Open Finance, Pix
- 🔒 **Security**: Encryption, OAuth 2.0, KYC, data protection
- ⚡ **Performance**: Algorithms, caching, rate limiting, real-time processing
- 🏗️ **Architecture**: Monorepo, microservices, distributed systems
- 🔐 **Compliance**: PCI-DSS, Open Banking, Brazilian fintech regulations

---

## Stack

### Backend
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![Koa](https://img.shields.io/badge/Koa-33333D?style=flat-square&logo=koa&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

### Data
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-13AA52?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)

### Finance & Security
![ISO 8583](https://img.shields.io/badge/ISO%208583-FF6B6B?style=flat-square)
![ISO 20022](https://img.shields.io/badge/ISO%2020022-FF6B6B?style=flat-square)
![OAuth 2.0](https://img.shields.io/badge/OAuth%202.0-4285F4?style=flat-square)
![Criptografia](https://img.shields.io/badge/Criptografia-FF6B6B?style=flat-square)
![SOAP/XML](https://img.shields.io/badge/SOAP%2FXML-FF9900?style=flat-square)

### DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088F0?style=flat-square&logo=github-actions&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)

### Frontend (when needed)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white)

### Mobile background
![React Native](https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

---

## Projects

### 🏦 Banking Stack
14 fintech challenges simulating real Brazilian financial market problems.

**What's in it:**
- SPI/ICOM Simulator (ISO 20022)
- DICT Simulator (Pix directory)
- ISO 8583 messaging
- GraphQL Ledger with Relay
- Workflow Engine
- Open Finance Simulator
- NFS-e Integration
- KYC System
- Rate Limiting (Leaky Bucket)
- Report System

**Stack:** Turborepo, TypeScript, Node 20+, Fastify, Koa, GraphQL, PostgreSQL, MongoDB, Redis, Docker, Next.js 14

https://github.com/mateussiqueira/banking-stack

---

### ⚡ Nidus
Self-hosted deploy platform. Push to GitHub, it builds and runs automatically.

**How it works:**
- Docker container isolation
- GitHub webhook integration
- Worker written in Go (15MB vs 100MB+ in Node)
- Multi-language support
- Built-in HTTPS (Caddy)

**Stack:** Next.js 16, NestJS, Prisma, PostgreSQL, Redis, Docker, Go

https://github.com/mateussiqueira/nidus

---

### 🤖 Canopy
Improved fork of OpenCode. AI agent for coding focused on efficiency.

**Key improvements:**
- Overflow recovery for long sessions
- Optimized memory usage (lower RSS)
- Accidental deletion protection
- Extended thinking with Bedrock Converse
- Faster performance across the board

**Stack:** TypeScript, Bun, Bedrock Converse

https://github.com/mateussiqueira/canopy

---

### 🔐 Unleash
Single-script MDM bypass for macOS. Works from Recovery on Apple Silicon and Intel.

**How it works:**
- Removes DEP activation records
- Blocks MDM network access
- Disables enrollment daemons
- Cleans user-level artifacts
- Optional pf firewall (kernel-level blocking)

**Features:**
- Reversible (backup/restore)
- Idempotent (safe to run multiple times)
- Auto-heal daemon
- Survives macOS updates
- Migration Assistant safe

**Stack:** Shell, macOS recovery, pf firewall

https://github.com/mateussiqueira/unleash

---

### 🧠 MLX Server
MCP server that exposes local LLM models as tools for AI agents.

**Models included:**
- Mistral 7B, LLaMA 3.1 8B
- Qwen 2.5 Coder 14B
- DeepSeek R1 7B, Coder V2
- Gemma 2 9B
- Qwen 2.5 VL 7B

**Tools:**
- Chat with any model
- Specialized code review
- Model management
- MCP Protocol integration

**Stack:** Python, MLX, MCP

https://github.com/mateussiqueira/mlx-server

---

## Skills

### Financial Systems
- SPI (Instant Payment System)
- DICT (Pix Directory)
- ISO 8583 (binary financial messages)
- ISO 20022 (modern XML standard)
- Open Finance & ABNT standards
- NFS-e integration

### Security
- PCI-DSS compliance
- AES-256, RSA, ECDSA encryption
- OAuth 2.0, OpenID Connect
- KYC/AML systems
- Rate limiting & DDoS protection
- Secure logging & auditability

### Performance & Algorithms
- Algorithm optimization (sorting, hashing, graphs, trees)
- Cache patterns (LRU, Leaky Bucket, Token Bucket)
- Query optimization & indexing
- Memory profiling & GC tuning
- Load balancing & sharding
- Compression techniques

### Architecture
- Monorepo design (Turborepo, pnpm)
- Microservices & service mesh
- Event-driven systems
- CQRS & Event Sourcing
- GraphQL Federation
- CI/CD & Infrastructure as Code

---

## By the numbers

| | |
|---|---|
| **Experience** | 11+ years |
| **Public repos** | 30+ |
| **Languages** | 7+ |
| **Fintech projects** | 5+ |
| **Implemented challenges** | 14 |
| **Annual commits** | 1000+ |

---

## What's different

1. Performance matters from day one
2. Security is in every decision
3. Deep knowledge of Brazilian fintech
4. Algorithms & optimization are my thing
5. Understand systems end-to-end
6. Build things that actually scale

---

## Get in touch

- 🐙 **GitHub:** [@mateussiqueira](https://github.com/mateussiqueira)
- 💙 **Interests:** Backend, fintech, performance, security
- 🇧🇷 **Based in:** Brazil (GMT-3)
- 🗣️ **Languages:** Portuguese, English

---

*Fast, secure code is not optional. It's the job.*
