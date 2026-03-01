# Gratonite - Built and Tested by Friends, For Friends.

[![GitHub followers](https://img.shields.io/github/followers/Gratonite-Labs?style=flat&logo=github&label=Follow)](https://github.com/Gratonite-Labs)
[![API issues](https://img.shields.io/github/issues/Gratonite-Labs/api?logo=github&label=open%20issues)](https://github.com/Gratonite-Labs/api/issues)
[![License](https://img.shields.io/github/license/Gratonite-Labs/api)](https://github.com/Gratonite-Labs/api/blob/main/LICENSE)

Welcome to **Gratonite Labs** — home of the Gratonite real-time community platform. We're building the next generation of communication tools for teams, creators, and communities.

Donate to Gratonite: https://www.buymeacoffee.com/codya

> **Gratonite** is a modern, multi-platform chat app with portals (servers), rich profiles, voice/video, a gamified economy, and a native mobile experience — all powered by a TypeScript-first stack.

---

## 🧱 Repositories

| Repository | Description | Stack |
|------------|-------------|-------|
| [api](https://github.com/Gratonite-Labs/api) | Core REST + tRPC backend — auth, WebSockets, voice rooms, economy | Node.js · Express 5 · PostgreSQL · Redis |
| [web](https://github.com/Gratonite-Labs/web) | Browser client | React 18 · Vite · Zustand · TanStack Query |
| [desktop](https://github.com/Gratonite-Labs/desktop) | Desktop client (macOS · Windows · Linux) | Electron 31 |
| [mobile](https://github.com/Gratonite-Labs/mobile) | iOS & Android app | Expo 54 · React Native 0.81 |
| [js-sdk](https://github.com/Gratonite-Labs/js-sdk) | Shared TypeScript packages (types, DB schema, utilities) | Drizzle ORM · TypeScript |
| [self-hosted](https://github.com/Gratonite-Labs/self-hosted) | Self-hosted deployment via Docker Compose | Docker |
| [gratonite.chat](https://github.com/Gratonite-Labs/gratonite.chat) | Landing page and marketing site | — |
| [dev-log](https://github.com/Gratonite-Labs/dev-log) | Architecture decisions, development log, status updates | — |

**Browse all →** [github.com/orgs/Gratonite-Labs/repositories](https://github.com/orgs/Gratonite-Labs/repositories)

---

## 🚀 Quick Start

```bash
# Clone and run the API locally
git clone https://github.com/Gratonite-Labs/api.git
cd api
cp .env.example .env   # fill in your DB / Redis / MinIO / LiveKit values
pnpm install
pnpm dev               # starts on http://localhost:4000

# Clone and run the web client
git clone https://github.com/Gratonite-Labs/web.git
cd web
cp .env.example .env
pnpm install
pnpm dev               # starts on http://localhost:5173/app/
```

> Each repo has a full setup guide, environment variable reference, and troubleshooting section in its own `README.md`.

---

## 🛠️ Tech Stack

```
Language:     TypeScript (all apps)

Frontend:     React 18 · Vite · React Router 6 · Zustand · TanStack Query
Mobile:       React Native 0.81 · Expo SDK 54 · React Navigation 7
Desktop:      Electron 31

Backend:      Node.js ≥ 20 · Express 5 · tRPC 11
Database:     PostgreSQL 16 · Drizzle ORM
Cache:        Redis 7
Real-time:    Socket.IO 4
Voice/Video:  LiveKit
File Storage: MinIO (S3-compatible)
Auth:         JWT · Argon2 · TOTP (MFA)
Email:        Nodemailer

Infrastructure: Docker Compose (local + self-hosted)
Monorepo:     pnpm workspaces · Turborepo
```

---

## ✅ Features

| Status | Feature |
|--------|---------|
| ✅ | Real-time text messaging |
| ✅ | Voice & video rooms (LiveKit) |
| ✅ | Portals (servers) · channels · roles |
| ✅ | Rich user profiles & cosmetics shop |
| ✅ | Friends, DMs & notifications |
| ✅ | Virtual economy & daily rewards |
| ✅ | Custom server emojis & reactions |
| ✅ | MFA (TOTP) & bot accounts |
| 🔄 | Mobile apps — iOS & Android (in progress) |
| 🔄 | Desktop app — macOS, Windows, Linux (in progress) |
| ⏳ | Self-hosted one-click deploy |
| ⏳ | Polls, events & server analytics |

---

## 🤝 Contributing

1. **Star** repos you find useful
2. **Report bugs** via [GitHub Issues](https://github.com/Gratonite-Labs/api/issues)
3. **Submit a PR** — fork → feature branch → pull request
4. Read [`CONTRIBUTING.md`](https://github.com/Gratonite-Labs/api/blob/main/CONTRIBUTING.md) before you start

We follow the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org).

---

## 📬 Stay Connected

- 🐦 **X (Twitter):** [@GratoniteLabs](https://x.com/GratoniteLabs)
- 📧 **Email:** [labs@gratonite.com](mailto:labs@gratonite.com)
- 🌐 **Website:** [gratonite.chat](https://gratonite.chat)

---

<div align="center">
  Made with ❤️ by Gratonite Labs - Want to Support:Buy me and my wife a coffee - https://www.buymeacoffee.com/codya
  <br/><br/>
  <a href="https://github.com/Gratonite-Labs">
    <img src="https://img.shields.io/github/followers/Gratonite-Labs?style=social" alt="GitHub followers"/>
  </a>
</div>
