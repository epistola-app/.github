# Epistola

<img align="left" width="120" height="120" alt="logo" src="https://github.com/user-attachments/assets/3d9ec276-eb56-4ff8-933c-daf1de4bf4c5" />

Epistola is an open-source document generation platform that turns templates into compliant PDFs at scale. It acts as a single-purpose document renderer — you handle the orchestration, Epistola handles the rendering, template management and governance. Built for document-heavy organisations in regulated industries.

<br clear="left"/>

## Repositories

| Repository | Description |
|---|---|
| [epistola-suite](https://github.com/epistola-app/epistola-suite) | The core platform — backend, frontend and all modules |
| [epistola-contract](https://github.com/epistola-app/epistola-contract) | API contracts and shared models |
| [valtimo-epistola-plugin](https://github.com/epistola-app/valtimo-epistola-plugin) | Epistola Plug-In for [Valtimo / gzac](https://www.valtimo.nl/) |

## Demo environments

- **Epistola** — [demo.epistola.app](https://demo.epistola.app)
- **Valtimo integration** — [valtimo-demo.epistola.app](https://valtimo-demo.epistola.app)

### Demo accounts

| Username | Password | Permissions |
|----------|----------|-------------|
| `admin@demo` | `admin` | Full access — manage tenants, templates, themes, publish, generate |
| `reader@demo` | `reader` | View templates, themes, and documents |
| `editor@demo` | `editor` | View + edit templates and themes |
| `generator@demo` | `generator` | View + generate documents |
| `manager@demo` | `manager` | Full tenant access — edit, generate, publish, manage settings |

You can also **register a new account** with any email address. Your email domain becomes your own private tenant (e.g., `you@yourcompany.com` creates tenant `yourcompany-com`) with full access.

Data on demo environments is ephemeral and can be reset at any time. The demo environment is not always available yet.

## Releases

Docker images and Helm charts are published to [GitHub Container Registry (ghcr.io)](https://github.com/orgs/epistola-app/packages).

## Links

- [epistola.app](https://epistola.app) — project website
