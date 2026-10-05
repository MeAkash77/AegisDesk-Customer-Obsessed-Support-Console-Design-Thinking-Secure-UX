<img src="./.github/screenshots/header.png#gh-light-mode-only" width="100%" alt="Header light mode"/>
<img src="./.github/screenshots/header-dark.png#gh-dark-mode-only" width="100%" alt="Header dark mode"/>

___

# AegisDesk

The modern customer support platform, an open-source alternative to Intercom, Zendesk, Salesforce Service Cloud etc.

<p>
  <img src="https://img.shields.io/circleci/build/github/chatwoot/chatwoot" alt="CircleCI Badge">
    <a href="https://hub.docker.com/r/chatwoot/chatwoot/"><img src="https://img.shields.io/docker/pulls/chatwoot/chatwoot" alt="Docker Pull Badge"></a>
  <a href="https://hub.docker.com/r/chatwoot/chatwoot/"><img src="https://img.shields.io/docker/cloud/build/chatwoot/chatwoot" alt="Docker Build Badge"></a>
  <img src="https://img.shields.io/github/commit-activity/m/chatwoot/chatwoot" alt="Commits-per-month">
  <a title="Crowdin" target="_self" href="https://chatwoot.crowdin.com/chatwoot"><img src="https://badges.crowdin.net/e/37ced7eba411064bd792feb3b7a28b16/localized.svg"></a>
  <a href="https://discord.gg/cJXdrwS"><img src="https://img.shields.io/discord/647412545203994635" alt="Discord"></a>
  <a href="https://status.chatwoot.com"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fchatwoot%2Fstatus%2Fmaster%2Fapi%2Fchatwoot%2Fuptime.json" alt="uptime"></a>
  <a href="https://status.chatwoot.com"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fchatwoot%2Fstatus%2Fmaster%2Fapi%2Fchatwoot%2Fresponse-time.json" alt="response time"></a>
  <a href="https://artifacthub.io/packages/helm/chatwoot/chatwoot"><img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/artifact-hub" alt="Artifact HUB"></a>
</p>


<p>
  <a href="https://heroku.com/deploy?template=https://github.com/chatwoot/chatwoot/tree/master" alt="Deploy to Heroku">
     <img width="150" alt="Deploy" src="https://www.herokucdn.com/deploy/button.svg"/>
  </a>
  <a href="https://marketplace.digitalocean.com/apps/chatwoot?refcode=f2238426a2a8" alt="Deploy to DigitalOcean">
     <img width="200" alt="Deploy to DO" src="https://www.deploytodo.com/do-btn-blue.svg"/>
  </a>
</p>

<img src="./.github/screenshots/dashboard.png#gh-light-mode-only" width="100%" alt="Chat dashboard dark mode"/>
<img src="./.github/screenshots/dashboard-dark.png#gh-dark-mode-only" width="100%" alt="Chat dashboard"/>

---

Chatwoot is the modern, open-source, and self-hosted customer support platform designed to help businesses deliver exceptional customer support experience. Built for scale and flexibility, Chatwoot gives you full control over your customer data while providing powerful tools to manage conversations across channels.

### ✨ Captain – AI Agent for Support

Supercharge your support with Captain, Chatwoot’s AI agent. Captain helps automate responses, handle common queries, and reduce agent workload—ensuring customers get instant, accurate answers. With Captain, your team can focus on complex conversations while routine questions are resolved automatically. Read more about Captain [here](https://chwt.app/captain-docs).

### 💬 Omnichannel Support Desk

Chatwoot centralizes all customer conversations into one powerful inbox, no matter where your customers reach out from. It supports live chat on your website, email, Facebook, Instagram, Twitter, WhatsApp, Telegram, Line, SMS etc.

### 📚 Help center portal

Publish help articles, FAQs, and guides through the built-in Help Center Portal. Enable customers to find answers on their own, reduce repetitive queries, and keep your support team focused on more complex issues.

### 🗂️ Other features

#### Collaboration & Productivity

- Private Notes and @mentions for internal team discussions.
- Labels to organize and categorize conversations.
- Keyboard Shortcuts and a Command Bar for quick navigation.
- Canned Responses to reply faster to frequently asked questions.
- Auto-Assignment to route conversations based on agent availability.
- Multi-lingual Support to serve customers in multiple languages.
- Custom Views and Filters for better inbox organization.
- Business Hours and Auto-Responders to manage response expectations.
- Teams and Automation tools for scaling support workflows.
- Agent Capacity Management to balance workload across the team.

#### Customer Data & Segmentation
- Contact Management with profiles and interaction history.
- Contact Segments and Notes for targeted communication.
- Campaigns to proactively engage customers.
- Custom Attributes for storing additional customer data.
- Pre-Chat Forms to collect user information before starting conversations.

#### Integrations
- Slack Integration to manage conversations directly from Slack.
- Dialogflow Integration for chatbot automation.
- Dashboard Apps to embed internal tools within Chatwoot.
- Shopify Integration to view and manage customer orders right within Chatwoot.
- Use Google Translate to translate messages from your customers in realtime.
- Create and manage Linear tickets within Chatwoot.

#### Reports & Insights
- Live View of ongoing conversations for real-time monitoring.
- Conversation, Agent, Inbox, Label, and Team Reports for operational visibility.
- CSAT Reports to measure customer satisfaction.
- Downloadable Reports for offline analysis and reporting.


## Documentation

Detailed documentation is available at [chatwoot.com/help-center](https://www.chatwoot.com/help-center).

## Translation process

The translation process for Chatwoot web and mobile app is managed at [https://translate.chatwoot.com](https://translate.chatwoot.com) using Crowdin. Please read the [translation guide](https://www.chatwoot.com/docs/contributing/translating-chatwoot-to-your-language) for contributing to Chatwoot.

## Branching model

We use the [git-flow](https://nvie.com/posts/a-successful-git-branching-model/) branching model. The base branch is `develop`.
If you are looking for a stable version, please use the `master` or tags labelled as `v1.x.x`.

## Deployment

### Heroku one-click deploy

Deploying Chatwoot to Heroku is a breeze. It's as simple as clicking this button:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/chatwoot/chatwoot/tree/master)

Follow this [link](https://www.chatwoot.com/docs/environment-variables) to understand setting the correct environment variables for the app to work with all the features. There might be breakages if you do not set the relevant environment variables.


### DigitalOcean 1-Click Kubernetes deployment

Chatwoot now supports 1-Click deployment to DigitalOcean as a kubernetes app.

<a href="https://marketplace.digitalocean.com/apps/chatwoot?refcode=f2238426a2a8" alt="Deploy to DigitalOcean">
  <img width="200" alt="Deploy to DO" src="https://www.deploytodo.com/do-btn-blue.svg"/>
</a>

### Other deployment options

For other supported options, checkout our [deployment page](https://chatwoot.com/deploy).

## Security

Looking to report a vulnerability? Please refer our [SECURITY.md](./SECURITY.md) file.

## Community

If you need help or just want to hang out, come, say hi on our [Discord](https://discord.gg/cJXdrwS) server.

## Contributors

Thanks goes to all these [wonderful people](https://www.chatwoot.com/docs/contributors):

<a href="https://github.com/chatwoot/chatwoot/graphs/contributors"><img src="https://opencollective.com/chatwoot/contributors.svg?width=890&button=false" /></a>


*Chatwoot* &copy; 2017-2026, Chatwoot Inc - Released under the MIT License.



<img src="./.github/screenshots/header.png#gh-light-mode-only" width="100%" alt="AegisDesk header (light mode)"/>
<img src="./.github/screenshots/header-dark.png#gh-dark-mode-only" width="100%" alt="AegisDesk header (dark mode)"/>

<div align="center">

# 🛡️ AegisDesk

### Customer-Obsessed Support Console · Design Thinking & Secure UX

**An open-source, self-hosted, omnichannel support desk — designed around the people who use it and hardened around the data it protects.**

<br/>

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](./LICENSE)
[![Ruby](https://img.shields.io/badge/Ruby-3.4.4-CC342D?style=for-the-badge&logo=ruby&logoColor=white)](./.ruby-version)
[![Rails](https://img.shields.io/badge/Rails-7.2-D30001?style=for-the-badge&logo=rubyonrails&logoColor=white)](./Gemfile)
[![Vue](https://img.shields.io/badge/Vue-3.5-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)](./package.json)
[![Node](https://img.shields.io/badge/Node-24.x-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](./.nvmrc)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](./docker-compose.yaml)
[![Redis](https://img.shields.io/badge/Redis-Sidekiq-DC382D?style=for-the-badge&logo=redis&logoColor=white)](./config/sidekiq.yml)

[![Stars](https://img.shields.io/github/stars/YOUR_USERNAME/AegisDesk-Customer-Obsessed-Support-Console-Design-Thinking-Secure-UX?style=social)](https://github.com/YOUR_USERNAME/AegisDesk-Customer-Obsessed-Support-Console-Design-Thinking-Secure-UX/stargazers)
[![Forks](https://img.shields.io/github/forks/YOUR_USERNAME/AegisDesk-Customer-Obsessed-Support-Console-Design-Thinking-Secure-UX?style=social)](https://github.com/YOUR_USERNAME/AegisDesk-Customer-Obsessed-Support-Console-Design-Thinking-Secure-UX/network/members)
[![Issues](https://img.shields.io/github/issues/YOUR_USERNAME/AegisDesk-Customer-Obsessed-Support-Console-Design-Thinking-Secure-UX)](https://github.com/YOUR_USERNAME/AegisDesk-Customer-Obsessed-Support-Console-Design-Thinking-Secure-UX/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)
[![Last Commit](https://img.shields.io/github/last-commit/YOUR_USERNAME/AegisDesk-Customer-Obsessed-Support-Console-Design-Thinking-Secure-UX)](https://github.com/YOUR_USERNAME/AegisDesk-Customer-Obsessed-Support-Console-Design-Thinking-Secure-UX/commits)

<br/>

[**🚀 Live Demo**](#-live-demo) ·
[**✨ Features**](#-features) ·
[**🧠 Design Thinking**](#-design-thinking-process) ·
[**🔐 Secure UX**](#-secure-ux-by-design) ·
[**⚡ Quick Start**](#-quick-start) ·
[**🏗️ Architecture**](#️-architecture) ·
[**🤝 Contributing**](#-contributing)

</div>

---

<img src="./.github/screenshots/dashboard.png#gh-light-mode-only" width="100%" alt="AegisDesk dashboard (light mode)"/>
<img src="./.github/screenshots/dashboard-dark.png#gh-dark-mode-only" width="100%" alt="AegisDesk dashboard (dark mode)"/>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Live Demo](#-live-demo)
- [Features](#-features)
- [Design Thinking Process](#-design-thinking-process)
- [Secure UX by Design](#-secure-ux-by-design)
- [Architecture](#️-architecture)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#-project-structure)
- [Quick Start](#-quick-start)
- [Configuration](#️-configuration)
- [Deployment](#-deployment)
- [Testing & Quality](#-testing--quality)
- [Roadmap](#️-roadmap)
- [Contributing](#-contributing)
- [Security Policy](#-security-policy)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)

---

## 🎯 Overview

**AegisDesk** is a modern customer support console that puts the customer at the center of every interaction — and protects them while doing it. It unifies conversations from every channel into a single, fast inbox, then layers on automation, AI assistance, analytics, and a self-service help center.

The project is guided by two principles:

| Principle | What it means in practice |
|---|---|
| **Customer-obsessed** | Every screen is shaped by the agent's workflow and the customer's context: one inbox, full conversation history, instant canned replies, private notes, and satisfaction feedback loops. |
| **Secure by default** | Security is part of the interface, not an afterthought: multi-factor authentication, layered rate limiting, role-based policies, audit trails, and SAML SSO support. |

> **Why "Aegis"?** In mythology, the aegis is a shield. AegisDesk is a support desk built to shield customer data and agent focus at the same time.

---

## 🚀 Live Demo

> 🔧 **Replace the placeholders below with your own deployment once it's live.**

| Resource | Link |
|---|---|
| 🌐 Live app | `https://YOUR-DEPLOYMENT-URL` |
| 📚 Docs | `https://YOUR-DOCS-URL` |
| 🎥 Walkthrough video | `https://YOUR-VIDEO-URL` |

**Running locally?** The development seed creates a demo super-admin so you can explore immediately:

```text
Email:    john@acme.inc
Password: Password1!
```

> ⚠️ **Development only.** These credentials come from `db/seeds.rb`. Never use them in production, and change or delete the seeded account on any shared environment.

---

## ✨ Features

### 💬 Omnichannel Inbox
Centralize every customer conversation in one place. Channels implemented in this codebase (`app/models/channel`):

| Channel | Channel | Channel |
|---|---|---|
| 🌐 Website live chat widget | 📧 Email | 💚 WhatsApp |
| 📘 Facebook Messenger | 📸 Instagram | 🎵 TikTok |
| 🐦 Twitter / X | ✈️ Telegram | 💬 LINE |
| 📱 SMS (incl. Twilio) | 🔌 API channel | |

### 🤖 Captain — AI Agent for Support
AI-assisted responses to automate common queries and reduce agent workload, backed by vector search (`pgvector`) and the `ai-agents` / OpenAI integrations in the Gemfile.

### 📚 Help Center Portal
Publish articles, FAQs, and guides so customers can solve problems on their own and agents can focus on complex issues.

### 🤝 Collaboration & Productivity
- **Private notes & @mentions** for internal discussion
- **Labels**, **custom views**, and **filters** to organize the inbox
- **Canned responses** and **macros** for faster replies
- **Keyboard shortcuts** and a **command bar** for quick navigation
- **Auto-assignment**, **teams**, and **agent capacity management**
- **Automation rules** to scale repetitive workflows
- **Business hours** and **auto-responders** to set expectations
- **Multi-lingual** interface

### 🧑‍🤝‍🧑 Customer Data & Segmentation
- Contact profiles with full interaction history
- Contact segments, notes, and **custom attributes**
- **Pre-chat forms** to capture context before a conversation begins
- Proactive **campaigns**
- Company records and CSV **data import**

### 🔗 Integrations
- **Slack** — manage conversations from Slack
- **Dialogflow** — chatbot automation
- **Shopify** — view customer orders inside the console
- **Linear** — create and manage tickets
- **Google Translate** — real-time message translation
- **Dashboard Apps** — embed internal tools
- **Webhooks** and **agent bots** for custom workflows
- **Web Push** / **FCM** notifications

### 📊 Reports & Insights
- Live view of ongoing conversations
- Conversation, agent, inbox, label, and team reports
- **CSAT** surveys and reports
- Downloadable reports for offline analysis

---

## 🧠 Design Thinking Process

AegisDesk's product approach follows the five stages of Design Thinking. The table maps each stage to concrete capabilities in the console.

> 📝 *This section describes the product philosophy and how it maps to shipped features. Add your own research artifacts (personas, journey maps, interview notes) under `docs/` and link them here to make it fully yours.*

| Stage | Question we ask | How it shows up in AegisDesk |
|:---:|---|---|
| **1. Empathize** | *Who is on the other side of the conversation?* | Contact profiles, conversation history, custom attributes, and pre-chat forms surface customer context right where the agent replies. |
| **2. Define** | *What is the real problem to solve?* | Agents lose time switching tools and re-asking questions → unified inbox, labels, filters, and custom views. Customers want fast, accurate answers → Help Center + Captain AI. |
| **3. Ideate** | *How might we remove friction?* | Keyboard shortcuts, command bar, canned responses, macros, automation rules, and auto-assignment. |
| **4. Prototype** | *Can we make it tangible quickly?* | A dedicated component library with [Histoire](https://histoire.dev) stories (`pnpm story:dev`) lets designers and engineers iterate on UI in isolation. |
| **5. Test** | *Did it actually help?* | CSAT surveys, agent/inbox/team reports, and live view close the loop with measurable feedback. |

### 🧑‍💻 Who we design for

| Persona | Needs | Supported by |
|---|---|---|
| **Support Agent** | Speed, context, low cognitive load | Unified inbox, shortcuts, canned replies, private notes |
| **Team Lead / Administrator** | Visibility, routing, control | Reports, teams, automation, capacity management, roles |
| **Customer** | Quick resolution, privacy, choice of channel | Omnichannel widget, Help Center, CSAT, secure data handling |
| **Developer / Integrator** | Extensibility | REST API, webhooks, agent bots, dashboard apps, JS SDK |

---

## 🔐 Secure UX by Design

Good security *feels* effortless to the people using it. The codebase includes the following controls (verified in source):

### Authentication & Access
| Control | Details | Where to look |
|---|---|---|
| **Multi-factor authentication (MFA/2FA)** | TOTP-based via `devise-two-factor`, with setup, verification, and trusted-device flows | `app/services/mfa/`, `app/controllers/api/v1/profile/mfa_controller.rb` |
| **Token-based API auth** | `devise_token_auth` with per-user access tokens | `config/initializers/devise_token_auth.rb` |
| **SAML SSO** | `omniauth-saml` support | `config/initializers/omniauth.rb` |
| **Role-based authorization** | Roles (`agent`, `administrator`) plus Pundit policies for 25+ resources | `app/models/account_user.rb`, `app/policies/` |

### Abuse Protection (Rack::Attack)
Layered throttling in `config/initializers/rack_attack.rb`:

| Surface | Limit |
|---|---|
| Global requests per IP | 3000 / minute (override with `RACK_ATTACK_LIMIT`) |
| Login (per IP) | 5 / 5 min |
| Login (per email) | 10 / 15 min |
| Super-admin login (per IP / per email) | 5 / 5 min · 5 / 15 min |
| Password reset (per IP / per email) | 5 / 30 min · 5 / 1 hr |
| Confirmation resend (per IP / per email) | 5 / 30 min · 5 / 1 hr |
| MFA verification (per IP) | 5 / minute |
| MFA login & setup (per IP / token) | 10 / minute |
| Account signup (per IP) | 5 / 30 min |

Trusted IPs can be safelisted with `RACK_ATTACK_ALLOWED_IPS`, and health checks bypass throttling.

### Data Integrity & Observability
- **Audit trail** via the `audited` gem
- **CSV injection protection** via `csv-safe` on exports
- **Parameter filtering** in logs (`filter_parameter_logging.rb`)
- **Static analysis** with Brakeman and `bundler-audit` (see `.bundler-audit.yml`)
- **Error monitoring** with Sentry (optional) and structured logging with Lograge
- **`ENABLE_ACCOUNT_SIGNUP=false`** by default in `.env.example`, so new deployments aren't open to public sign-up

### Secure UX Principles Applied
1. **Progressive friction** — stricter checks on risky actions (login, reset, MFA), none on routine work.
2. **Clear feedback** — rate-limit and MFA flows return actionable states instead of silent failures.
3. **Least privilege** — agents see what they need; administrators manage the rest.
4. **Secure defaults** — conservative `.env.example` values; secrets never committed.
5. **Fail safe** — throttles fail open on unparseable input while the per-IP limit still applies.

---

## 🏗️ Architecture

```mermaid
flowchart LR
    subgraph Channels["Customer Channels"]
        W[Web Widget]
        E[Email]
        WA[WhatsApp]
        S[Social: FB / IG / X / TikTok]
        M[Telegram / LINE / SMS]
        API[API Channel]
    end

    subgraph Edge["Edge & Security"]
        RA[Rack::Attack<br/>Rate Limiting]
        AUTH[Devise + MFA<br/>Token Auth / SAML]
        POL[Pundit Policies]
    end

    subgraph App["Rails 7.2 Application"]
        CTRL[REST API<br/>Controllers]
        SVC[Services & Listeners]
        WS[ActionCable<br/>Real-time]
        SK[Sidekiq Workers]
    end

    subgraph Data["Data Layer"]
        PG[(PostgreSQL<br/>+ pgvector)]
        R[(Redis)]
        OBJ[(Object Storage<br/>S3 / GCS / Local)]
    end

    subgraph UI["Front-end (Vue 3 + Vite)"]
        DASH[Agent Dashboard]
        WID[Chat Widget]
        PORT[Help Center Portal]
        SDK[JS SDK]
    end

    Channels --> RA --> AUTH --> POL --> CTRL
    CTRL --> SVC --> PG
    SVC --> SK --> R
    SVC --> OBJ
    WS --> R
    CTRL <--> UI
    WS <--> UI
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Backend** | Ruby 3.4.4 · Rails 7.2 · Sidekiq 7 · ActionCable |
| **Frontend** | Vue 3 · Vuex & Pinia · Vue Router 4 · Vue I18n · Tailwind CSS 3 · Vite 6 |
| **Database** | PostgreSQL (pgvector) · Redis |
| **Auth & Security** | Devise · devise-two-factor · devise_token_auth · OmniAuth SAML · Pundit · Rack::Attack |
| **AI** | `ruby-openai` · `ai-agents` · `pgvector` / `neighbor` |
| **Storage** | Local · AWS S3 · Google Cloud Storage (Active Storage) |
| **Testing** | RSpec · Vitest · Histoire (component stories) |
| **Quality** | RuboCop · ESLint · Prettier · Brakeman · bundler-audit · Husky · Qlty |
| **DevOps** | Docker · Docker Compose · CircleCI · GitHub Actions · Dev Containers / Codespaces |

---

## 📁 Project Structure

```text
.
├── app/
│   ├── controllers/        # REST API & web controllers
│   ├── models/             # Domain models (incl. 11 channel types)
│   ├── policies/           # Pundit authorization policies
│   ├── services/           # Business logic (MFA, messaging, integrations…)
│   ├── jobs/               # Sidekiq background jobs
│   └── javascript/
│       ├── dashboard/      # Agent console (Vue 3)
│       ├── widget/         # Customer-facing live chat widget
│       ├── portal/         # Help Center portal
│       ├── survey/         # CSAT survey UI
│       ├── sdk/            # Embeddable JS SDK
│       ├── design-system/  # Shared design tokens & styles
│       └── superadmin_pages/
├── config/                 # Rails config, initializers (rack_attack, devise…)
├── db/                     # Migrations & seeds
├── enterprise/             # Enterprise-licensed modules (separate license)
├── lib/                    # Shared Ruby libraries
├── spec/                   # RSpec suite (~950 spec files)
├── swagger/                # OpenAPI definitions
├── theme/                  # Color & icon tokens
├── docker/                 # Dockerfiles & entrypoints
├── deployment/             # Linux systemd / nginx deployment assets
├── .github/                # CI workflows, issue & PR templates, screenshots
└── docs/                   # Engineering notes
```

---

## ⚡ Quick Start

### Prerequisites

| Tool | Version |
|---|---|
| Ruby | `3.4.4` (see `.ruby-version`) |
| Node.js | `24.x` (see `.nvmrc`) |
| pnpm | `10.x` |
| PostgreSQL | 16+ with the `pgvector` extension |
| Redis | any recent version |
| Overmind (or Foreman) | for running the dev processes |

### Option A — Local development

```bash
# 1. Clone
git clone https://github.com/YOUR_USERNAME/AegisDesk-Customer-Obsessed-Support-Console-Design-Thinking-Secure-UX.git
cd AegisDesk-Customer-Obsessed-Support-Console-Design-Thinking-Secure-UX

# 2. Configure environment
cp .env.example .env
#   → edit .env: set SECRET_KEY_BASE, POSTGRES_*, REDIS_URL, FRONTEND_URL

# 3. Install Ruby & JS dependencies
make setup            # bundle install + pnpm install

# 4. Prepare the database (create, migrate, seed)
make db

# 5. Start Rails, Sidekiq, and Vite together
make run              # uses Overmind + Procfile.dev
```

Then open **http://localhost:3000**.

| Command | Purpose |
|---|---|
| `make run` | Start backend (`:3000`), Sidekiq worker, and Vite dev server |
| `make force_run` | Clean up stale processes/sockets, then start |
| `make console` | Open a Rails console |
| `make db_reset` | Drop, recreate, and reseed the database |
| `make debug` / `make debug_worker` | Attach to the backend / worker process |

### Option B — Docker Compose

```bash
cp .env.example .env
# Edit .env, then:
docker compose up
```

A production-oriented stack (Rails, Sidekiq, `pgvector/pgvector:pg16`, Redis) is provided in `docker-compose.production.yaml`.

### Option C — Dev Container / GitHub Codespaces

Open the repository in VS Code and choose **"Reopen in Container"**, or launch a Codespace. Configuration lives in `.devcontainer/`.

---

## ⚙️ Configuration

All configuration is environment-driven via `.env` (see [`.env.example`](./.env.example) for the full, documented list). Key variables:

| Variable | Description |
|---|---|
| `SECRET_KEY_BASE` | Long random secret for signing sessions/tokens. **Required.** |
| `FRONTEND_URL` | Public URL of your deployment |
| `FORCE_SSL` | Set to `true` in production |
| `ENABLE_ACCOUNT_SIGNUP` | Allow public account creation (`false` recommended) |
| `POSTGRES_HOST` / `POSTGRES_*` | Database connection |
| `REDIS_URL` | Redis connection (Sidekiq, ActionCable, rate limiting) |
| `ACTIVE_STORAGE_SERVICE` | `local`, `amazon`, `google`, … |
| `RACK_ATTACK_LIMIT` | Global requests/minute/IP |
| `RACK_ATTACK_ALLOWED_IPS` | Comma-separated safelist |
| `SENTRY_DSN` | Optional error monitoring |
| `LOG_LEVEL` | `info` by default |

Generate a strong secret:

```bash
bundle exec rails secret
```

---

## 🌍 Deployment

| Target | How |
|---|---|
| **Docker** | `docker compose -f docker-compose.production.yaml up -d` |
| **Linux VM (systemd + nginx)** | Assets in `deployment/` (service units and `nginx_chatwoot.conf`) |
| **Heroku** | `app.json` is included for template-based deploys |
| **Clever Cloud** | Config in `clevercloud/` |
| **Kubernetes** | Build from `docker/Dockerfile` and supply Postgres + Redis |

**Production checklist**

- [ ] Strong, unique `SECRET_KEY_BASE`
- [ ] `FORCE_SSL=true` and TLS terminated at your proxy
- [ ] `ENABLE_ACCOUNT_SIGNUP=false` unless you intend open registration
- [ ] Seeded demo user removed or password changed
- [ ] Managed PostgreSQL with backups, plus persistent Redis
- [ ] Object storage (S3/GCS) configured for attachments
- [ ] `RACK_ATTACK_ALLOWED_IPS` set for trusted infrastructure
- [ ] MFA enabled for all administrators
- [ ] Error monitoring (`SENTRY_DSN`) configured

---

## 🧪 Testing & Quality

```bash
# Backend (RSpec)
bundle exec rspec

# Frontend (Vitest)
pnpm test
pnpm test:coverage

# Linting
bundle exec rubocop
pnpm eslint

# Security scanning
bundle exec brakeman
bundle exec bundle-audit check --update

# Component library (Histoire)
pnpm story:dev
```

**Continuous integration** (`.github/workflows/` and `.circleci/`) covers CE test runs, a dedicated MFA test workflow, frontend lint & test, bundle size limits, Docker build verification, PR linting, and nightly installer checks. Husky pre-commit hooks keep style consistent locally.

---

## 🗺️ Roadmap

- [ ] Publish Design Thinking research artifacts (personas, journey maps) under `docs/`
- [ ] Accessibility audit & documented conformance report
- [ ] Hosted public demo with resettable sandbox data
- [ ] Expanded Secure-UX guide (security UX patterns & copy guidelines)
- [ ] Additional analytics for CSAT trends and first-response time
- [ ] More Help Center themes

Have an idea? [Open a feature request](../../issues/new/choose).

---

## 🤝 Contributing

Contributions of all kinds are welcome — code, design, docs, translations, and bug reports.

1. **Fork** the repository
2. **Create a branch**: `git checkout -b feat/your-feature`
3. **Commit** using clear, conventional messages
4. **Run** the linters and tests locally
5. **Open a Pull Request** against the base branch using the PR template

Please read [`CONTRIBUTING.md`](./CONTRIBUTING.md) and our [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md) first. Issue templates for bugs and feature requests are in `.github/ISSUE_TEMPLATE/`.

---

## 🔒 Security Policy

Found a vulnerability? **Please don't open a public issue.** Follow the process in [`SECURITY.md`](./SECURITY.md) and report privately through GitHub Security Advisories on this repository.

Areas of particular interest: remote code execution, SQL injection, authentication bypass, privilege escalation, XSS, CSRF, and unauthorized admin actions. Please test only against a self-hosted instance.

---

## 📄 License

This project is released under the **MIT License** — see [`LICENSE`](./LICENSE).

Content under the `enterprise/` directory (if present) is covered by its own license in [`enterprise/LICENSE`](./enterprise/LICENSE).

---

## 🙏 Acknowledgements

AegisDesk is built on the shoulders of the open-source **[Chatwoot](https://github.com/chatwoot/chatwoot)** project (© 2017–2026 Chatwoot Inc., MIT License). Huge thanks to the Chatwoot maintainers and the wider contributor community whose work makes this possible.

Also powered by the incredible Ruby on Rails, Vue.js, PostgreSQL, Redis, Sidekiq, and Vite ecosystems.

---

<div align="center">

**If AegisDesk helps you, please consider giving it a ⭐**

Made with care for support teams and the customers they serve.

[⬆ Back to top](#️-aegisdesk)

</div>
