# Gratonite Labs

Building **Gratonite**, a privacy-first, open-source alternative to Discord.

Gratonite is a multi-platform community chat app with real-time messaging, voice/video, guilds, DMs, threads, E2E encryption, federation, moderation, gamification, and self-hosting support. v1.0.0 is live at [gratonite.chat](https://gratonite.chat).

> Built for communities that want more control over their platform.

## What Gratonite Is

- **109** database schemas, **91** API route modules, **51** frontend pages, **77** React components
- End-to-end encryption for all DMs and group DMs (ECDH P-256 + AES-GCM-256)
- Instance federation with Ed25519 HTTP Signatures — self-hosted instances can connect and list on [Discover](https://gratonite.chat/app/discover)
- One-command Docker deployment with automatic HTTPS via Caddy + Let's Encrypt
- Full moderation suite, economy system, gamification, voice/video, and creative tools

## Repositories

### Core

| Repository | Description |
|---|---|
| [CoodayeA/Gratonite](https://github.com/CoodayeA/Gratonite) | **Main monorepo** — all source code, Docker images, docs, and deployment config |
| [api](https://github.com/Gratonite-Labs/api) | Backend API — Express, TypeScript, Socket.IO, PostgreSQL, Redis, LiveKit, federation |
| [web](https://github.com/Gratonite-Labs/web) | Web client — React, TypeScript, Vite |
| [mobile](https://github.com/Gratonite-Labs/mobile) | Mobile client — Expo, React Native |
| [desktop](https://github.com/Gratonite-Labs/desktop) | Desktop client — Electron |

### Infrastructure & Tooling

| Repository | Description |
|---|---|
| [self-hosted](https://github.com/Gratonite-Labs/self-hosted) | Self-hosting guide and quick-start reference |
| [js-sdk](https://github.com/Gratonite-Labs/js-sdk) | JavaScript SDK and shared TypeScript packages |
| [admin](https://github.com/Gratonite-Labs/admin) | Admin and moderation tooling |
| [gratonite.chat](https://github.com/Gratonite-Labs/gratonite.chat) | Marketing site |
| [dev-log](https://github.com/Gratonite-Labs/dev-log) | Development log and architecture notes |

### Platform-Specific

| Repository | Description |
|---|---|
| [ios](https://github.com/Gratonite-Labs/ios) | iOS-specific mobile work |
| [android](https://github.com/Gratonite-Labs/android) | Android-specific mobile work |

## Self-Hosting

Run your own Gratonite instance in minutes. No coding required — everything runs in pre-built Docker containers.

```bash
git clone https://github.com/CoodayeA/Gratonite.git && cd Gratonite
cp deploy/self-host/.env.example deploy/self-host/.env
# Edit .env: set your domain, admin email/password, DB password
docker compose -f deploy/self-host/docker-compose.yml up -d
```

Docker images: `ghcr.io/coodayea/gratonite-api`, `ghcr.io/coodayea/gratonite-web`, `ghcr.io/coodayea/gratonite-setup`

Full guide: [Self-Hosting Guide](https://github.com/CoodayeA/Gratonite/blob/main/docs/federation/self-hosting-guide.md)

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React, TypeScript, Vite |
| Mobile | Expo, React Native |
| Desktop | Electron |
| Backend | Node.js, Express, TypeScript |
| Database | PostgreSQL, Drizzle ORM |
| Cache | Redis |
| Realtime | Socket.IO |
| Voice | LiveKit |
| Auth | JWT, Argon2id, TOTP MFA |
| Federation | HTTP Signatures, Ed25519 |
| Search | PostgreSQL full-text search |
| Metrics | Prometheus |
| Deployment | Docker Compose, Caddy, GitHub Actions |

## Links

- Website: [gratonite.chat](https://gratonite.chat)
- Main repo: [CoodayeA/Gratonite](https://github.com/CoodayeA/Gratonite)
- Self-hosting: [Self-Hosting Guide](https://github.com/CoodayeA/Gratonite/blob/main/docs/federation/self-hosting-guide.md)
- Federation: [Federation Guide](https://github.com/CoodayeA/Gratonite/blob/main/docs/federation/federation-guide.md)
- Releases: [Docker Images](https://github.com/CoodayeA/Gratonite/releases)

## Support

If you want to support Gratonite:

- [Buy Me a Coffee](https://www.buymeacoffee.com/codya)

I'm currently covering hosting, infrastructure, and project costs personally, so any support helps keep the project online and moving.
