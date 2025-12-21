# Replane

**Dynamic configuration manager for apps and services.**

Store feature flags, app settings, and operational config in one place—with version history, optional approvals, and realtime sync to your services. No redeploys needed.

## Why Replane?

- **Feature flags & A/B testing** — roll out features gradually, target specific users or segments
- **Operational tuning** — adjust limits, TTLs, and timeouts without code changes
- **Per-environment config** — different values for production, staging, and development
- **Instant rollback** — restore any previous configuration version during incidents
- **Real-time sync** — SDKs receive changes instantly via Server-Sent Events

## Repositories

| Repository | Description |
|------------|-------------|
| [replane](https://github.com/replane/replane) | Self-hostable server with web UI, versioning, approvals, and audit logs |
| [replane-javascript](https://github.com/replane/replane-javascript) | Official SDKs for Node.js, React, Next.js, and Svelte |
| [replane-python](https://github.com/replane/replane-python) | Official Python SDK with sync and async clients |
| [replane-dotnet](https://github.com/replane/replane-dotnet) | Official .NET SDK |
| [replane-website](https://github.com/replane/replane-website) | Documentation website at [replane.dev](https://replane.dev) |

## Quick Start

### Server

```bash
docker run -p 3000:3000 ghcr.io/replane/replane:latest
```

### SDKs

**JavaScript/TypeScript**
```bash
npm install @replanejs/sdk
```

**React**
```bash
npm install @replanejs/react
```

**Next.js**
```bash
npm install @replanejs/next
```

**Svelte**
```bash
npm install @replanejs/svelte
```

**Python**
```bash
pip install replane
```

**.NET**
```bash
dotnet add package Replane
```

## Features

- **Version history** — every change creates a snapshot; restore any previous state
- **JSON Schema validation** — prevent invalid configs; auto-generate TypeScript types
- **Change proposals** — require review before changes go live
- **Audit log** — track who changed what, when, and why
- **Context-based overrides** — return different values based on user ID, plan, region, or custom attributes
- **Role-based access** — workspace admins, project maintainers, and config editors
- **Self-hosted** — run on your infrastructure with Docker

## Documentation

Visit [replane.dev](https://replane.dev) for full documentation, guides, and API reference.

## License

MIT
