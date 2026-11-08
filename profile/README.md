# krpkg

**krpkg** stands for **Kur Package Manager**, an open source ecosystem created by **Kur Zagin** ([@Kurzagin](https://github.com/Kurzagin) • [kurzagin.com](https://kurzagin.com)).

Modular developer toolkits, lightweight TypeScript SDKs, and cyber-minimalist UI systems.

## Ecosystem Overview

The krpkg organization develops open source infrastructure designed for zero extraneous overhead, cross-runtime compatibility (Node.js, Bun, browsers, Tauri, Expo), and developer velocity.

### Packages & Repositories

| Package | Repository | Description | Primary Languages |
|---|---|---|---|
| `@krpkg/ui` | [krpkg/ui](https://github.com/krpkg/ui) | Cyber-minimalist UI design system and React component library for Web, Tauri, and mobile. | TypeScript, React, CSS |
| `@krpkg/pixivjs` | [krpkg/pixivjs](https://github.com/krpkg/pixivjs) | Universal client and SDK for Pixiv artwork metadata extraction and ZIP archiving. | TypeScript |
| `@krpkg/nhentaijs` | [krpkg/nhentaijs](https://github.com/krpkg/nhentaijs) | Lightweight client and SDK for nHentai API v2 metadata and concurrent ZIP archiving. | TypeScript |

## Installation

Install any `@krpkg` library from npm:

```bash
# Using npm
npm install @krpkg/ui
npm install @krpkg/pixivjs
npm install @krpkg/nhentaijs

# Using Bun
bun add @krpkg/ui
bun add @krpkg/pixivjs
bun add @krpkg/nhentaijs

# Using pnpm
pnpm add @krpkg/ui
pnpm add @krpkg/pixivjs
pnpm add @krpkg/nhentaijs
```

## Architecture Principles

- **Zero Platform Lock-in**: Core SDKs rely on standardized web primitives (`fetch`, `Blob`, `ArrayBuffer`, `AbortSignal`).
- **Resilience**: Built-in multi-endpoint cascading, automatic rate-limit backoff, and CDN server failover.
- **Tactical Aesthetics**: Unified dark cyber-minimalist design tokens and component specifications.

## Author & Maintainer

Created and maintained by **Kur Zagin**:
- GitHub: [@Kurzagin](https://github.com/Kurzagin)
- Website: [kurzagin.com](https://kurzagin.com)

## License

All krpkg open source repositories are distributed under the Apache-2.0 license unless specified otherwise.
