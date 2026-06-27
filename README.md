I've been writing software for a bit over 11 years. Most of my work sits at the intersection of fintech, clean architecture, and developer tooling. Lately I've also been digging into low-level macOS stuff — recovery mode, pf, launchd, that kind of thing.

I'm based in Arapiraca, Brazil (GMT-3). I speak Portuguese natively and English fluently.

[LinkedIn](https://www.linkedin.com/in/mateussiqueira)

---

**Projects I'm actively maintaining**

[**unleash**](https://github.com/mateussiqueira/unleash) — runs from macOS recovery mode and bypasses MDM enrollment. One script, covers Intel and Apple Silicon from macOS 12 to 15+. Five protection layers, from disk-level DEP spoofing all the way up to kernel pf firewall. Useful if you want actual control over your own machine.

[**banking-stack**](https://github.com/mateussiqueira/banking-stack) — monorepo with 14 fintech challenges modeled after the Brazilian financial market. Includes SPI (ISO 20022), DICT, and ISO 8583 simulators, a double-entry ledger, a workflow engine, and NFS-e invoice generation. TDD since day one, clean architecture throughout.

[**easy-mcp-br**](https://github.com/mateussiqueira/easy-mcp-br) — manages Brazilian and global MCP services for opencode. Organizes 108 services across 20 groups, activates them on demand so agent context doesn't blow up. Can be installed via npm, homebrew, apt, or a direct script.

[**canopy**](https://github.com/mateussiqueira/canopy) — a fork of opencode with recovery for context overflows, accidental deletion protection, and Bedrock Converse support. Comes with a native SwiftUI manager that runs Mistral, LLaMA, Qwen Coder, and DeepSeek locally on Apple Silicon via MLX.

[**nidus**](https://github.com/mateussiqueira/nidus) — self-hosted PaaS in the same vein as Vercel or Railway. Deploys from GitHub webhooks into isolated Docker containers. The worker is written in Go and uses about 80% less memory than an equivalent Node service. SSL handled automatically through Caddy.

[**omni-cli**](https://github.com/mateussiqueira/omni-cli) — Python CLI that acts as a single entry point for scripts, tasks, and Docker containers spread across different workspaces. Basically so I don't have to remember fifteen different command paths.

---

**Things I use almost every day**

<img src="https://skillicons.dev/icons?i=ts,js,go,py,swift,bash,nodejs,bun,nestjs,fastify,graphql,postgres,mongodb,redis,docker,githubactions,cloudflare,aws" alt="tech stack icons" />
