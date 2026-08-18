<h1 align="center">Hi, I'm TRAN LONG TUAN/h1>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img alt="Typing SVG" src="https://readme-typing-svg.demolab.com?font=Roboto&weight=600&size=24&duration=3000&pause=800&center=true&vCenter=true&width=600&height=45&lines=Senior+Web+Developer;TypeScript+%2F+Node.js+%2F+NestJS;React+%2F+Next.js;Self-hosting+%26+homelab+automation" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tranlongtuan/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" />
  </a>
  <a href="tranlongtuan03@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-EA4335?logo=gmail&logoColor=white" />
  </a>
  <!-- <a href="&lt;PORTFOLIO_URL&gt;">
    <img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-111111?logo=vercel&logoColor=white" />
  </a> -->
</p>

---

## About

Senior Web Developer based in Vietnam, currently at **FPT Software**. I build and maintain
production backend services in **TypeScript / NestJS**, and full-stack applications with
**React** and **Next.js**.

Most of my work sits at the boundary between application code and the systems it runs on —
API design, error handling and observability, containerised deployment, and the operational
tooling that keeps all of it debuggable at 2am.

Outside of work I run a small homelab, which is where I test infrastructure ideas I'd rather
not learn about for the first time in production.

**What I care about in code:**

- Errors are surfaced, never swallowed — clear messages for users, diagnostic detail for developers
- Logging and monitoring designed in from the start, not bolted on after the first incident
- Abstraction only where it earns its keep
- Maintainability over cleverness

---

## Tech Stack

**Core**

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" />
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?logo=node.js&logoColor=white" />
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-087EA4?logo=react&logoColor=white" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white" />
</p>

**Data**

<p>
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white" />
  <img alt="Redis" src="https://img.shields.io/badge/Redis-FF4438?logo=redis&logoColor=white" />
</p>

**Infrastructure & Tooling**

<p>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black" />
  <img alt="Nginx" src="https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white" />
  <img alt="Jira" src="https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white" />
</p>

---

## Selected Projects

### Homelab Monitor & Alert Service

A NestJS service that watches container health across my homelab and pushes actionable
alerts to Telegram.

- Container introspection via `dockerode`
- Telegram bot built on `nestjs-telegraf`
- Alert deduplication and state tracking backed by Prisma + PostgreSQL
- GitHub webhook ingestion with HMAC-SHA256 signature verification

**Why it exists:** naive monitoring produces alert fatigue. The interesting problem here is
deduplication and state transition — distinguishing _"still broken"_ from _"broken again"_.

<!-- → [Repository](https://github.com/<GITHUB_USERNAME>/<REPO>) -->

### homelab-config

Version-controlled configuration for my self-hosted stack. Compose files, reverse proxy
config, and service definitions kept in Git so a rebuild is reproducible rather than
archaeological.

<!-- → [Repository](https://github.com/<GITHUB_USERNAME>/homelab-config) -->

---

## Currently

- Running Ubuntu Server with Docker + Portainer as my homelab foundation
- Building out monitoring and alerting as a hands-on distributed-systems exercise
- Deepening Linux server administration, working toward a self-built NAS
- Open to talking about NestJS architecture, TypeScript ergonomics, and observability strategy

<p align="center"><sub>Thanks for stopping by.</sub></p>
