### Hey there 👋 I'm Mateus Siqueira

**Software Architect & Principal Engineer** | *Fintech Infrastructure • AI Agents & Dev Tooling • macOS Security & Low-Level Systems*

```
11+ years building robust, scalable software.
Specialized in Clean Architecture, core financial systems, and secure developer tooling.
```

<p align="left">
  <a href="https://github.com/mateussiqueira"><img src="https://github-readme-stats.vercel.app/api?username=mateussiqueira&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="GitHub Stats" height="150" /></a>
  <a href="https://github.com/mateussiqueira"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mateussiqueira&layout=compact&theme=dark&hide_border=true" alt="Top Langs" height="150" /></a>
</p>

---

## 🛠️ Focus Areas

### 🏦 Fintech & Banking Systems
Building resilient ledger architectures, real-time transaction processing, and central bank integrations. Deep knowledge of Brazilian payment protocols (Pix, SPI, DICT), Open Finance, and ISO messaging standards.

### 🧠 AI Agents & Developer Tools
Creating context-aware developer tooling, local inference runtimes, and advanced AI agents. Optimizing token budgets, context management, and CLI development workflows.

### 🛡️ macOS Low-Level & Security
Developing recovery-level systems, kernel-level packet filter automation (`pf`), launchd daemon overrides, and secure configuration profiles for MDM/DEP control.

---

## 🚀 Featured Projects

### 🏦 [Banking Stack](https://github.com/mateussiqueira/banking-stack)
*A high-performance monorepo implementing 14 core fintech challenges simulating real-world Brazilian financial markets.*

*   **Financial Protocols**: Includes full simulators for **SPI** (ISO 20022 XML), **DICT** (Pix Directory), and **ISO 8583** (binary card network messaging).
*   **Ledger Architecture**: Features a robust, transactional double-entry Ledger using GraphQL and Relay.
*   **Production Engine**: Integrates a custom Node-based Workflow Engine, Open Finance API (OAuth 2.0/REST), electronic service invoice engine (NFS-e via SOAP/XML), and Leaky Bucket rate limiters.
*   **Pillars**: Implements strict Clean Architecture, comprehensive test suites, and Turborepo monorepo management.
*   **Stack**: Turborepo, TypeScript, Node.js (20+), Fastify, Koa, GraphQL, PostgreSQL, MongoDB, Redis, Docker, Next.js 14, Storybook.

---

### 🧠 [easy-mcp-br](https://github.com/mateussiqueira/easy-mcp-br)
*Second brain and token-conscious manager for Brazilian and global Model Context Protocol (MCP) servers in AI agents.*

*   **Token Efficiency**: Prevents LLM context saturation by utilizing an on-demand activation strategy, cutting token footprint by up to 90%.
*   **Scientific Design**: Directly implements strategies from peer-reviewed research (Lost in the Middle, Working Memory limits, Cognitive Load Theory).
*   **Ecosystem Integration**: Orchestrates 108 services across 20 logical groups (Payments, ERPs, BR Data, Infrastructure). Supports installation via Homebrew, APT, npm, or direct scripts.
*   **Stack**: Node.js, TypeScript, CLI Parser, opencode integration.

---

### 🤖 [Canopy](https://github.com/mateussiqueira/canopy) & [Canopy Manager](https://github.com/mateussiqueira/canopy-manager)
*An optimized, highly resilient coding agent fork of OpenCode accompanied by a native macOS control center.*

*   **Canopy Agent**: Engineered with Bun + TypeScript. Features recovery protocols for long-session context overflows, data-safe file deletion prevention, and Bedrock Converse thinking support.
*   **Canopy Manager**: A native SwiftUI macOS menu bar application to spin up local inference servers, manage MLX models, and integrate with the Canopy CLI.
*   **Local Inference**: Supports local execution of Mistral 7B, LLaMA, Qwen Coder, and DeepSeek models on Apple Silicon.
*   **Stack**: Bun, TypeScript, Bedrock Converse, Swift, SwiftUI (macOS), MLX.

---

### 🛡️ [Unleash](https://github.com/mateussiqueira/unleash)
*Resilient, single-script MDM bypass and control suite for macOS, executing from Recovery Mode.*

*   **5-Layer Security Control**: 
    1.  *DEP Decoy*: Spoofs `.cloudConfigHasActivationRecord` markers to prevent enrollment assistant triggers.
    2.  *Hosts DNS Block*: Restricts access to 13+ Apple MDM and enrollment servers.
    3.  *launchd Override*: Disables enrollment daemons (`ManagedClient`, `activationd`) at the configuration level.
    4.  *User-level Cleanup*: Scrubs preferences and LaunchAgents from target user directories to survive Migration Assistant.
    5.  *Kernel-level pf Firewall*: Adds persistent whitelists/blocks operating below DNS to block MDM while keeping iCloud.
*   **Portability**: Compiled from modular library components into a single standalone shell script.
*   **Stack**: Shell/Bash, macOS Recovery, pf packet filter.

---

### ⚡ [Nidus](https://github.com/mateussiqueira/nidus)
*Self-hosted open-source PaaS engine mimicking Vercel and Railway workflows.*

*   **Architecture**: Automates builds and deployments directly from GitHub webhooks, running applications in isolated Docker containers.
*   **Inference Server**: Incorporates a lightweight agent/worker daemon written in Go (saving 80%+ memory compared to typical Node agents) and uses Caddy for automated SSL/HTTPS.
*   **Stack**: Next.js 16, NestJS, Go, Prisma, PostgreSQL, Redis, Docker.

---

## 💻 Tech Stack

### Languages
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Shell Script](https://img.shields.io/badge/Shell%20Script-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

### Backend, APIs & Protocols
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![GraphQL (Relay)](https://img.shields.io/badge/GraphQL%20(Relay)-E10098?style=flat-square&logo=graphql&logoColor=white)
![OAuth 2.0](https://img.shields.io/badge/OAuth%202.0-4285F4?style=flat-square)
![ISO 20022 XML](https://img.shields.io/badge/ISO%2020022-FF6B6B?style=flat-square)
![ISO 8583](https://img.shields.io/badge/ISO%208583-FF6B6B?style=flat-square)

### Databases & Cache
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-13AA52?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![MinIO (S3)](https://img.shields.io/badge/MinIO%20(S3)-C92847?style=flat-square&logo=minio&logoColor=white)

### DevOps & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088F0?style=flat-square&logo=github-actions&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![Proxmox VE](https://img.shields.io/badge/Proxmox%20VE-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)

---

## 📐 Architectural Standards

1.  **Clean Architecture First**: Strongly aligned with Clean Architecture principles (inspired by Rodrigo Manguinho/Uncle Bob). Codebases are cleanly separated: frameworks (NestJS, Fastify, Next.js) remain isolated within delivery/infrastructure adapters, keeping domain/business logic completely pure and framework-agnostic.
2.  **Strict Typing & Reliability**: Strict linting, Zero `any` policies, explicit type definitions, and compiler-first development.
3.  **TDD Workflow**: Test-Driven Development (TDD) as a rule for business logic, maintaining high coverage across ledger and financial computations.
4.  **Hardware & Token Resource Consciousness**: Designing systems to respect environmental limits—whether that means writing Go workers to run on 15MB RSS instead of heavy JS runtimes, or designing "second-brain" architectures to keep LLM context prompts under strict limits.

---

## 📈 By the Numbers

*   **Experience**: 11+ Years of professional engineering.
*   **Production Financial Challenges**: 14 fully implemented banking challenges (`banking-stack`).
*   **MCP Support**: 108 services / 115 packages managed locally (`easy-mcp-br`).
*   **macOS Bypass Coverage**: Native support for Intel and Apple Silicon (M1 to M5 architectures) on macOS 12 to 15+.
*   **Commits**: 1000+ yearly contributions.

---

## 📬 Contact & Location

*   🐙 **GitHub**: [@mateussiqueira](https://github.com/mateussiqueira)
*   🇧🇷 **Based in**: Brazil (GMT-3)
*   🗣️ **Languages**: Portuguese (Native), English (Fluent)

*Fast, secure, and clean code is not an option. It's the job.*
