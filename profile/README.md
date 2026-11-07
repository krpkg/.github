# krpkg

Modular developer toolkits, lightweight TypeScript SDKs, and cyber-minimalist UI systems.

## Ecosystem Overview

The krpkg organization develops open source infrastructure designed for zero extraneous overhead, cross-runtime compatibility (Node.js, Bun, browsers, Tauri, Expo), and developer velocity.

### Repositories

| Repository | Description | Primary Languages |
|---|---|---|
| [cli](https://github.com/krpkg/cli) | Official package installer and runner for the krpkg ecosystem. | Node.js, JavaScript |
| [ui](https://github.com/krpkg/ui) | Cyber-minimalist UI design system and React component library for Web, Tauri, and mobile. | TypeScript, React, CSS |
| [pixivjs](https://github.com/krpkg/pixivjs) | Universal client and SDK for Pixiv artwork metadata extraction and ZIP archiving. | TypeScript |
| [nhentaijs](https://github.com/krpkg/nhentaijs) | Lightweight client and SDK for nHentai API v2 metadata and concurrent ZIP archiving. | TypeScript |

## Quick Installation

Install any krpkg library directly using the krpkg CLI or your package manager:

```bash
# Using krpkg CLI
krpkg install ui
krpkg install pixivjs
krpkg install nhentaijs

# Using Bun
bun add github:krpkg/ui
bun add github:krpkg/pixivjs
bun add github:krpkg/nhentaijs

# Using npm
npm install github:krpkg/ui
npm install github:krpkg/pixivjs
npm install github:krpkg/nhentaijs
```

## Architecture Principles

- Zero Platform Lock-in: Core SDKs rely on standardized web primitives (`fetch`, `Blob`, `ArrayBuffer`, `AbortSignal`).
- Resilience: Built-in multi-endpoint cascading, automatic rate-limit backoff, and CDN server failover.
- Tactical Aesthetics: Unified dark cyber-minimalist design tokens and component specifications.

## License

All krpkg open source repositories are distributed under the Apache-2.0 license unless specified otherwise.
