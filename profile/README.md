# Replane

**Dynamic configuration manager for apps and services.**

Store feature flags, app settings, and operational config in one place—with version history, optional approvals, and realtime sync to your services. No redeploys needed.

## Why Replane?

- **Feature flags & A/B testing** — roll out features gradually, target specific users or segments
- **Operational tuning** — adjust limits, TTLs, and timeouts without code changes
- **Per-environment config** — different values for production, staging, and development
- **Instant rollback** — restore any previous configuration version during incidents
- **Real-time sync** — SDKs receive changes instantly via Server-Sent Events

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
