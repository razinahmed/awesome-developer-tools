<div align="center">

# 🌟 Awesome Developer Tools

<img src="https://placehold.co/900x250/1e1e2e/f38ba8.png?text=Awesome+Developer+Tools+%7C+Curated+List+2025" alt="Awesome Developer Tools Banner" />

<br/>

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)
[![GitHub stars](https://img.shields.io/github/stars/razinahmed/awesome-developer-tools?style=for-the-badge&color=yellow)](https://github.com/razinahmed/awesome-developer-tools/stargazers)
[![Last Updated](https://img.shields.io/badge/Last_Updated-2025-f38ba8?style=for-the-badge)](https://github.com/razinahmed/awesome-developer-tools)
[![License: MIT](https://img.shields.io/badge/License-MIT-f38ba8?style=for-the-badge)](LICENSE)

> A carefully curated, constantly updated list of the absolute best tools, APIs, frameworks, and resources that modern developers use to ship faster, write better code, and build exceptional products.

[UI Libraries](#-ui-libraries--frameworks) · [Deployment](#-deployment--hosting) · [Databases](#%EF%B8%8F-databases--baas) · [AI Tools](#-ai-utilities--apis) · [Dev Tools](#%EF%B8%8F-developer-tools--extensions) · [Contributing](#-contributing)

</div>

---

## 📑 Table of Contents

- [UI Libraries & Frameworks](#-ui-libraries--frameworks)
- [Deployment & Hosting](#-deployment--hosting)
- [Databases & BaaS](#%EF%B8%8F-databases--baas)
- [AI Utilities & APIs](#-ai-utilities--apis)
- [Authentication](#-authentication)
- [Testing & QA](#-testing--qa)
- [Developer Tools & Extensions](#%EF%B8%8F-developer-tools--extensions)
- [Design & Prototyping](#-design--prototyping)
- [Monitoring & Analytics](#-monitoring--analytics)
- [API Development](#-api-development)
- [Contributing](#-contributing)

---

## 🎨 UI Libraries & Frameworks

The best component libraries and CSS tools for building beautiful applications.

| Resource | Description | Tech Stack | Type |
|---|---|---|---|
| **[shadcn/ui](https://ui.shadcn.com/)** | Beautifully designed, accessible components you can copy-paste into your apps. Built on Radix UI. | React, Tailwind | Free |
| **[Tailwind CSS](https://tailwindcss.com/)** | A utility-first CSS framework packed with composable classes for building any design directly in markup. | CSS | Free |
| **[Framer Motion](https://www.framer.com/motion/)** | A production-ready motion library for React with smooth, physics-based spring animations. | React | Free |
| **[Aceternity UI](https://ui.aceternity.com/)** | Trending animated components ready to copy-paste. Hover effects, 3D cards, spotlights, and more. | React, Tailwind | Free |
| **[Radix UI](https://www.radix-ui.com/)** | Unstyled, accessible component primitives for building high-quality design systems. | React | Free |
| **[Magic UI](https://magicui.design/)** | 50+ free animated components built with React, TypeScript, Tailwind CSS, and Framer Motion. | React, Tailwind | Free |
| **[Next UI](https://nextui.org/)** | Beautiful, fast, and modern React UI library with first-class support for Next.js. | React, Tailwind | Free |
| **[Mantine](https://mantine.dev/)** | Full-featured React component library with 100+ hooks and components, dark mode, and form handling. | React | Free |

---

## 🚀 Deployment & Hosting

Where to push your code for the world to see, with the best developer experience.

| Platform | Best For | Free Tier | Key Features |
|---|---|:-:|---|
| **[Vercel](https://vercel.com/)** | Frontend & Next.js apps | ✅ Generous | Edge Network, Serverless Functions, Preview Deploys |
| **[Render](https://render.com/)** | Backend APIs & Docker | ✅ Limited | Auto-deploy from Git, Managed Postgres, Redis |
| **[Railway](https://railway.app/)** | Full-stack deployments | ❌ Trial | Infrastructure as code, zero config, instant deploys |
| **[Fly.io](https://fly.io/)** | Deploy close to users | ✅ Limited | Global Anycast, Firecracker VMs, built-in Postgres |
| **[Netlify](https://www.netlify.com/)** | Static sites & JAMstack | ✅ Generous | Edge Functions, Forms, Identity, Split Testing |
| **[Cloudflare Pages](https://pages.cloudflare.com/)** | Static & full-stack | ✅ Generous | Unlimited bandwidth, Workers integration, global CDN |
| **[AWS Amplify](https://aws.amazon.com/amplify/)** | Full-stack AWS apps | ✅ Limited | CI/CD, Auth, API, Storage, all connected to AWS |

### Comparison at a Glance

| Feature | Vercel | Render | Railway | Fly.io | Netlify |
|---|:-:|:-:|:-:|:-:|:-:|
| Free SSL | ✅ | ✅ | ✅ | ✅ | ✅ |
| Custom Domains | ✅ | ✅ | ✅ | ✅ | ✅ |
| Auto-Deploy | ✅ | ✅ | ✅ | ✅ | ✅ |
| Docker Support | ❌ | ✅ | ✅ | ✅ | ❌ |
| Background Workers | ❌ | ✅ | ✅ | ✅ | ❌ |
| Managed Database | ❌ | ✅ | ✅ | ✅ | ❌ |
| Edge Functions | ✅ | ❌ | ❌ | ✅ | ✅ |

---

## 🗄️ Databases & BaaS

Backend-as-a-Service and database platforms that handle the heavy lifting.

| Platform | Description | Database | Realtime | Free Tier |
|---|---|---|:-:|:-:|
| **[Supabase](https://supabase.com/)** | Open source Firebase alternative. Database, Auth, Storage, Edge Functions. | PostgreSQL | ✅ | ✅ |
| **[PlanetScale](https://planetscale.com/)** | Advanced serverless MySQL platform with branching and zero-downtime schema changes. | MySQL | ❌ | ✅ |
| **[Neon](https://neon.tech/)** | Serverless Postgres built for the cloud. Separates storage and compute for autoscaling. | PostgreSQL | ❌ | ✅ |
| **[Upstash](https://upstash.com/)** | Serverless Redis and Kafka with per-request pricing. Great for rate limiting and caching. | Redis, Kafka | ❌ | ✅ |
| **[Turso](https://turso.tech/)** | Edge-hosted SQLite database. Embedded replicas for ultra-low latency reads. | SQLite (libSQL) | ❌ | ✅ |
| **[Convex](https://www.convex.dev/)** | Reactive backend-as-a-service with real-time queries, mutations, and scheduled functions. | Document DB | ✅ | ✅ |
| **[Firebase](https://firebase.google.com/)** | Google's app development platform with Firestore, Auth, Hosting, and Cloud Functions. | Firestore | ✅ | ✅ |

---

## 🤖 AI Utilities & APIs

The tools to add intelligence and "magic" to your applications.

| Tool | Focus | Pricing | Ease of Use |
|---|---|---|:-:|
| **[OpenAI](https://openai.com/)** | LLMs (GPT-4o), Image Gen (DALL-E 3), TTS, Embeddings | Pay-per-token | ⭐⭐⭐⭐⭐ |
| **[Anthropic Claude](https://www.anthropic.com/)** | Highly capable LLMs with massive context windows (200K tokens) | Pay-per-token | ⭐⭐⭐⭐⭐ |
| **[Hugging Face](https://huggingface.co/)** | Open source model hub, Inference API, Spaces for demos | Free + Pro | ⭐⭐⭐⭐ |
| **[Vercel AI SDK](https://sdk.vercel.ai/)** | Streaming React hooks for building AI chat interfaces with any provider | Free (OSS) | ⭐⭐⭐⭐⭐ |
| **[Replicate](https://replicate.com/)** | Run open source ML models in the cloud via simple API calls | Pay-per-second | ⭐⭐⭐⭐⭐ |
| **[LangChain](https://www.langchain.com/)** | Framework for building LLM-powered applications with chains, agents, and RAG | Free (OSS) | ⭐⭐⭐⭐ |
| **[Pinecone](https://www.pinecone.io/)** | Managed vector database for semantic search and RAG applications | Free tier | ⭐⭐⭐⭐⭐ |

---

## 🔐 Authentication

Authentication and user management solutions for modern applications.

| Platform | Description | Social Login | MFA | Free Tier |
|---|---|:-:|:-:|:-:|
| **[Clerk](https://clerk.com/)** | Drop-in auth with beautiful pre-built components, user management, and organizations. | ✅ | ✅ | ✅ |
| **[NextAuth.js](https://next-auth.js.org/)** | Open source authentication for Next.js. Supports 50+ OAuth providers. | ✅ | ❌ | ✅ (OSS) |
| **[Lucia](https://lucia-auth.com/)** | Lightweight, session-based auth library. Framework agnostic. | ✅ | ❌ | ✅ (OSS) |
| **[Auth0](https://auth0.com/)** | Enterprise identity platform with universal login and fine-grained authorization. | ✅ | ✅ | ✅ |
| **[Supabase Auth](https://supabase.com/auth)** | Built into Supabase. Email, social, phone, and magic link authentication. | ✅ | ✅ | ✅ |

---

## 🧪 Testing & QA

Tools for ensuring your code works correctly and performs well.

| Tool | Type | Description | Language |
|---|---|---|---|
| **[Vitest](https://vitest.dev/)** | Unit Testing | Blazing fast unit test framework powered by Vite. Jest-compatible API. | JS/TS |
| **[Playwright](https://playwright.dev/)** | E2E Testing | Cross-browser end-to-end testing by Microsoft. Supports Chrome, Firefox, Safari. | JS/TS/Python |
| **[Storybook](https://storybook.js.org/)** | Component Testing | Develop, test, and document UI components in isolation. | JS/TS |
| **[Cypress](https://www.cypress.io/)** | E2E Testing | Developer-friendly E2E testing with real-time reloading and time-travel debugging. | JS/TS |
| **[MSW](https://mswjs.io/)** | API Mocking | Mock Service Worker for intercepting and mocking API requests in tests. | JS/TS |

---

## 🛠️ Developer Tools & Extensions

Productivity enhancers for your daily workflow.

| Tool | Category | Platform | Description |
|---|---|---|---|
| **[Raycast](https://www.raycast.com/)** | Launcher | macOS | Blazing fast, extensible launcher with built-in snippets, clipboard history, and AI. |
| **[Warp](https://www.warp.dev/)** | Terminal | macOS/Linux | The modern terminal. Rust-based, with IDE-like editing, AI command search, and workflows. |
| **[Arc Browser](https://arc.net/)** | Browser | macOS/Windows | Reimagined browser with spaces, split views, and automatic tab management. |
| **[Fig](https://fig.io/)** | Terminal | macOS | IDE-style autocomplete for your terminal. Works with bash, zsh, and fish. |
| **[Zed](https://zed.dev/)** | Editor | macOS/Linux | High-performance, multiplayer code editor built in Rust by ex-Atom creators. |
| **[HTTPie](https://httpie.io/)** | API Client | All | User-friendly command-line HTTP client and web-based API testing tool. |
| **[DevToys](https://devtoys.app/)** | Utilities | Windows/macOS | Swiss Army knife for developers. JSON formatter, Base64, hash generators, and more. |
| **[Linear](https://linear.app/)** | Project Mgmt | Web | The issue tracker built for speed. Keyboard-first, with GitHub and Slack integration. |

---

## 🎨 Design & Prototyping

Tools for designing interfaces, creating assets, and prototyping ideas.

| Tool | Focus | Free Tier | Best For |
|---|---|:-:|---|
| **[Figma](https://www.figma.com/)** | UI/UX Design | ✅ | Collaborative interface design, prototyping, dev handoff |
| **[Excalidraw](https://excalidraw.com/)** | Whiteboarding | ✅ | Quick hand-drawn diagrams, architecture sketches |
| **[v0 by Vercel](https://v0.dev/)** | AI UI Generation | ✅ | Generate React + Tailwind components from text prompts |
| **[Coolors](https://coolors.co/)** | Color Palettes | ✅ | Generate and browse beautiful color schemes |
| **[Heroicons](https://heroicons.com/)** | Icons | ✅ | Beautiful hand-crafted SVG icons by the Tailwind team |
| **[Shots.so](https://shots.so/)** | Mockups | ✅ | Create beautiful browser and device mockups for screenshots |

---

## 📊 Monitoring & Analytics

Track performance, errors, and user behavior in production.

| Tool | Focus | Free Tier | Description |
|---|---|:-:|---|
| **[Sentry](https://sentry.io/)** | Error Tracking | ✅ | Real-time error monitoring with stack traces, breadcrumbs, and release tracking. |
| **[PostHog](https://posthog.com/)** | Product Analytics | ✅ | Open source analytics, feature flags, session replays, and A/B testing. |
| **[Vercel Analytics](https://vercel.com/analytics)** | Web Analytics | ✅ | Privacy-friendly, real-time web analytics built for Next.js. |
| **[Grafana](https://grafana.com/)** | Observability | ✅ | Open source dashboards for metrics, logs, and traces from any data source. |
| **[BetterStack](https://betterstack.com/)** | Uptime & Logs | ✅ | Uptime monitoring, incident management, and log aggregation. |

---

## 🔌 API Development

Tools for building, testing, and documenting APIs.

| Tool | Type | Description | Free |
|---|---|---|:-:|
| **[Hoppscotch](https://hoppscotch.io/)** | API Client | Open source API development ecosystem. Lightweight Postman alternative. | ✅ |
| **[Swagger](https://swagger.io/)** | API Docs | Design, build, and document RESTful APIs with the OpenAPI specification. | ✅ |
| **[tRPC](https://trpc.io/)** | API Framework | End-to-end typesafe APIs for TypeScript. No code generation needed. | ✅ |
| **[Insomnia](https://insomnia.rest/)** | API Client | API design, debugging, and testing with GraphQL support. | ✅ |
| **[Apidog](https://apidog.com/)** | API Platform | All-in-one API development tool: design, debug, test, mock, and document. | ✅ |

---

## 🤝 Contributing

This list is for the community, by the community! If you have a tool that saves you hours every week, we want to hear about it.

### How to Contribute

1. **Fork** this repository
2. **Add** your tool to the appropriate category table
3. **Follow** the existing format: `| **[Name](URL)** | Description | Details | Type |`
4. **Ensure** the tool is actively maintained and has a working website
5. **Submit** a Pull Request with a brief explanation of why this tool is awesome

### Guidelines

- One tool per Pull Request for easier review
- Tools must be actively maintained (updated within the last 12 months)
- No affiliate links or paid promotions
- Descriptions should be concise (one sentence)
- Include whether a free tier is available

Read our full [contribution guidelines](CONTRIBUTING.md) for more details.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Maintained with care by [Razin Ahmed](https://github.com/razinahmed)**

Found this list useful? Give it a ⭐ and share it with your developer friends!

<img src="https://komarev.com/ghpvc/?username=razinahmed&style=flat-square&color=f38ba8&label=REPO+VIEWS" alt="Repo Views" />

</div>
