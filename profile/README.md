# Gratonite Labs

Building **Gratonite**, a privacy-first, open-source alternative to Discord.

Gratonite is a multi-platform community chat product with real-time messaging, guilds, DMs, threads, voice, moderation tooling, events, and self-hosting support. This organization contains the product repos, platform clients, deployment assets, and project documentation behind that work.

## Core repositories

| Repository | Purpose |
|---|---|
| [api](https://github.com/Gratonite-Labs/api) | Backend API for auth, messaging, guilds, voice, moderation, and realtime events |
| [web](https://github.com/Gratonite-Labs/web) | Web client built with React and Vite |
| [mobile](https://github.com/Gratonite-Labs/mobile) | Mobile client built with Expo and React Native |
| [desktop](https://github.com/Gratonite-Labs/desktop) | Desktop client built with Electron |
| [js-sdk](https://github.com/Gratonite-Labs/js-sdk) | JavaScript SDK and shared TypeScript packages |
| [self-hosted](https://github.com/Gratonite-Labs/self-hosted) | Self-hosted deployment assets and Docker Compose setup |
| [gratonite.chat](https://github.com/Gratonite-Labs/gratonite.chat) | Marketing site and public-facing content |
| [admin](https://github.com/Gratonite-Labs/admin) | Admin and moderation tooling |
| [dev-log](https://github.com/Gratonite-Labs/dev-log) | Development log, architecture notes, and project status |

## Additional platform repos

These repos are public because they support platform-specific work around the mobile product:

| Repository | Purpose |
|---|---|
| [ios](https://github.com/Gratonite-Labs/ios) | iOS-focused Gratonite mobile work |
| [android](https://github.com/Gratonite-Labs/android) | Android-focused Gratonite mobile work |

## Product direction

Gratonite is being built around a few hard constraints:

- no phone-number gate just to join communities
- no ad-driven product incentives
- no paywall around basic social features
- a better default for friends, communities, guilds, and online groups

## Stack

- Frontend: React, TypeScript, Vite
- Mobile: Expo, React Native
- Desktop: Electron
- Backend: Node.js, Express, TypeScript
- Data: PostgreSQL, Drizzle ORM, Redis
- Realtime: Socket.IO, LiveKit
- Deployment: Docker Compose and GitHub Actions

## Start here

- Main product site: [gratonite.chat](https://gratonite.chat)
- Main personal repo: [CoodayeA/Gratonite](https://github.com/CoodayeA/Gratonite)
- Org repositories: [github.com/orgs/Gratonite-Labs/repositories](https://github.com/orgs/Gratonite-Labs/repositories)

## Notes

The most current cross-project documentation lives in [CoodayeA/Gratonite](https://github.com/CoodayeA/Gratonite). Repository-level READMEs are the source of truth for setup, local development, and deployment details. This profile is intentionally high level and reflects the current public structure of the organization.
