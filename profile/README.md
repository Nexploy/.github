<p align="center">
  <img src="./profile/nexploy-banner.svg" alt="Nexploy — Self-hosted deployment platform for Docker" width="100%" />
</p>

<p align="center">
  <strong>Self-hosted deployment platform for Docker</strong><br />
  Think Vercel/Netlify — but self-hosted, on your own servers.
</p>

<p align="center">
  <a href="https://github.com/Nexploy/nexploy"><img src="https://img.shields.io/github/stars/Nexploy/nexploy?style=flat&color=blue" alt="Stars" /></a>
  <a href="https://github.com/Nexploy/nexploy/actions"><img src="https://img.shields.io/github/actions/workflow/status/Nexploy/nexploy/release.yml?branch=main" alt="Build status" /></a>
  <a href="https://github.com/Nexploy/nexploy/blob/main/LICENSE"><img src="https://img.shields.io/github/license/Nexploy/nexploy" alt="License" /></a>
  <img src="https://img.shields.io/badge/node-%3E%3D22.13-339933?logo=node.js&logoColor=white" alt="Node version" />
</p>

<p align="center">
  <a href="https://github.com/Nexploy/nexploy">Nexploy app</a> ·
  <a href="https://github.com/Nexploy/docs">Documentation</a>
</p>

---

Nexploy deploys applications straight from GitHub/GitLab into Docker containers, fronted by Traefik with automatic HTTPS — no third-party cloud required.

- **Git Integration** — Deploy from GitHub and GitLab with OAuth
- **Automated Build Pipeline** — Resumable, step-by-step builds with real-time log streaming
- **Docker Management** — Containers, images, volumes, and networks from one dashboard
- **Traefik Reverse Proxy** — Automatic routing and Let's Encrypt SSL
- **Real-time Monitoring** — Live container stats, build logs, and Docker events via SSE
- **Encrypted Environment Variables** — AES-256-CBC at rest
- **In-browser Terminal** — WebSocket-powered Docker container terminal
- **Two-Factor Authentication** — TOTP with backup codes
- **Multi-language** — English and French

## Tech Stack

Next.js 16 · React 19 · Tailwind CSS · Hono.js · Prisma 7 · PostgreSQL 18 · Better Auth · Inngest · Docker · Traefik v3 · pnpm + Turborepo

## Repositories

| Repo | Description |
|---|---|
| [`nexploy`](https://github.com/Nexploy/nexploy) | The main application (monorepo: web app, Docker API, desktop app) |
| [`docs`](https://github.com/Nexploy/docs) | Documentation site |

## Getting started

```bash
git clone https://github.com/Nexploy/nexploy.git
cd nexploy
pnpm install
pnpm dev
```

See the [full setup guide](https://github.com/Nexploy/nexploy#readme) for prerequisites and environment configuration.

---

<p align="center">
  <sub>Built by the Nexploy team.</sub>
</p>
