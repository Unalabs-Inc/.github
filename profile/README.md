<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:081426,35:0F766E,70:06B6D4,100:2563EB&height=190&section=header&text=Una%20Labs&fontSize=46&fontColor=F8FAFC&animation=fadeIn&fontAlignY=38&desc=AI-powered%20products%20%E2%80%A2%20governed%20delivery%20%E2%80%A2%20measurable%20proof&descAlignY=61&descSize=16" alt="Una Labs" />
</p>

<h2 align="center">From rough request to shipped, supportable product.</h2>

<p align="center">
  Una Labs is a Toronto product studio and delivery platform for founders, teams, and service businesses. We combine structured discovery, product engineering, secure AI workflows, client-facing delivery operations, and evidence-backed release governance.
</p>

<p align="center">
  <a href="https://unalabs.cloud"><img src="https://img.shields.io/badge/WEBSITE-unalabs.cloud-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Una Labs website" /></a>
  <a href="https://unalabs.cloud/start"><img src="https://img.shields.io/badge/START%20A%20PROJECT-2563EB?style=for-the-badge&logo=rocket&logoColor=white" alt="Start a project" /></a>
  <a href="mailto:hello@unalabs.cloud"><img src="https://img.shields.io/badge/EMAIL-hello%40unalabs.cloud-111827?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Una Labs" /></a>
</p>

---

## What Una Labs Does

| Capability | What clients receive |
|---|---|
| **Product discovery** | Structured intake, requirements, workflow mapping, technical options, risk boundaries, and a buildable delivery slice |
| **Product engineering** | Responsive web platforms, mobile applications, APIs, integrations, data models, automation, and release pipelines |
| **AI workflow systems** | Human-governed AI features, approval checkpoints, privacy-conscious prompts, provider boundaries, and measurable outcomes |
| **Delivery operations** | Proposals, milestones, project dashboards, approvals, reports, handover evidence, and production-readiness gates |
| **Platform improvement** | Security hardening, performance work, operational automation, health checks, cost control, and recovery documentation |

## Product and Venture Portfolio

States are stated deliberately: **live** means a public product surface exists; **staging** and **release pipeline** do not mean production readiness.

| Product | Purpose | Engineering scope | Current public position |
|---|---|---|---|
| **Una Labs Platform** | Intake-to-delivery operating system for founders and service teams | Next.js, TypeScript, Cloudflare, Supabase, Stripe, governed project workflows | [Live platform](https://unalabs.cloud) |
| **PeacePad** | Calm, privacy-aware family communication and coordination | React, TypeScript, Node.js, PostgreSQL, Railway, Cloudflare, Capacitor | [Live product](https://peacepad.ca) |
| **PeacePad V2** | Regional native-mobile coordination, secure family identity, messaging, calendar, private records, and bounded offline recovery | React Native, Expo, TypeScript, Deno Edge Functions, dual-region Supabase/Postgres, Terraform controls | **Lab/staging · release blocked** |
| **SayWetin** | Speech, music, and Nigerian-language recognition across web, extension, and mobile tracks | React, React Native, TypeScript, Node.js, PostgreSQL, Railway, Cloudflare | [Live product](https://saywetin.app) |
| **Anion** | Tutoring operations, scheduling, role-based dashboards, billing, and live-classroom workflows | Next.js, Supabase, Stripe, Daily.co, Cloudflare Workers | [Live product](https://anion.unalabs.cloud) |
| **Dispatch** | Operational dispatch, incident monitoring, mobile workflows, and protected administration | React, TypeScript, Node.js, PostgreSQL, Railway, Capacitor | [Product walkthrough](https://unalabs.cloud/demo/dispatch) |
| **ATEAM** | Mission-control and coordinated operational workflows | TypeScript, Node.js, managed runtime patterns, public/private route separation | [Status board](https://unalabs.cloud/status?project=ateam) |
| **CapSigma Growth Desk** | Lead intelligence, outreach operations, approvals, and proof-backed handover | Cloudflare Pages/Functions, D1 patterns, SendGrid, AI workflows | [Live product](https://capsigma-growth-desk.pages.dev) |
| **Garden Cleaners** | Service-business website, booking, client portal, and operational delivery | Next.js, Supabase, Stripe, Cloudflare, production QA | [Live product](https://gardencleaners.ca) |
| **Just Checking In** | Mobile game and Apple release-delivery programme | Unity, C#, iOS export, Xcode signing/archive, TestFlight and App Store workflows | **iOS release track** |

The wider delivery catalogue also includes reusable vertical concepts for skilled trades, cold-chain logistics, brand/design delivery, internal automation, browser extensions, and mobile product experiments. Private client or user-sensitive systems remain private by design.

## Company Architecture

<p align="center">
  <img src="https://raw.githubusercontent.com/Unalabs-Inc/.github/main/assets/company-architecture.svg" alt="Una Labs delivery architecture: client signal, governed delivery, product platform, and trust and release" width="100%" />
</p>

<details>
<summary><b>View the accessible technical flowchart</b></summary>
<br/>

```mermaid
flowchart TB
    subgraph CLIENT["01 · CLIENT AND MARKET ENTRY"]
        direction LR
        FOUNDERS["Founders and product teams"]
        SERVICES["Service businesses"]
        INTERNAL["Una Labs ventures"]
    end

    subgraph DELIVERY["02 · UNA LABS DELIVERY SYSTEM"]
        direction LR
        INTAKE["Structured intake"]
        SCOPE["Scope, proposal and approval"]
        BUILD["Governed product engineering"]
        PORTAL["Client portal, reporting and handover"]
    end

    subgraph PLATFORM["03 · SHARED ENGINEERING PATTERNS"]
        direction LR
        EDGE["Cloudflare edge and static delivery"]
        APIS["TypeScript and Node.js services"]
        DATA["Product-isolated Supabase, Postgres and D1"]
        MOBILE["React Native, Expo, Capacitor and Unity"]
    end

    subgraph TRUST["04 · TRUST, RELEASE AND OPERATIONS"]
        direction LR
        SECURITY["JWT, RLS, validation and least privilege"]
        CI["GitHub Actions and protected environments"]
        PROOF["Tests, health checks and evidence ledgers"]
        RELEASE["Cloudflare, Railway and Apple pipelines"]
    end

    CLIENT --> DELIVERY
    DELIVERY --> PLATFORM
    PLATFORM --> TRUST
    INTAKE --> SCOPE --> BUILD --> PORTAL
    EDGE --> SECURITY
    APIS --> SECURITY
    DATA --> PROOF
    MOBILE --> RELEASE

    classDef entry fill:#172554,stroke:#60A5FA,color:#F8FAFC,stroke-width:2px;
    classDef delivery fill:#083344,stroke:#22D3EE,color:#ECFEFF,stroke-width:2px;
    classDef platform fill:#052E16,stroke:#4ADE80,color:#F0FDF4,stroke-width:2px;
    classDef trust fill:#3B1D0B,stroke:#FB923C,color:#FFF7ED,stroke-width:2px;
    class FOUNDERS,SERVICES,INTERNAL entry;
    class INTAKE,SCOPE,BUILD,PORTAL delivery;
    class EDGE,APIS,DATA,MOBILE platform;
    class SECURITY,CI,PROOF,RELEASE trust;
```

</details>

## Technology Stack

| Layer | Technologies and practices |
|---|---|
| **Web experiences** | TypeScript, JavaScript, React, Next.js, Vite, Astro, Tailwind CSS |
| **Mobile and games** | React Native, Expo, Capacitor, Unity, C#, iOS, Xcode, Android |
| **APIs and edge** | Node.js, Express, Deno Edge Functions, Cloudflare Pages/Functions/Workers, REST, WebSockets |
| **Data and identity** | Supabase, PostgreSQL, D1, JWT, Row Level Security, versioned migrations |
| **Cloud and delivery** | Cloudflare, Railway, Docker, Terraform, GitHub Actions, protected environments |
| **Integrations** | Stripe, Daily.co, SendGrid, webhooks, AI providers with human approval boundaries |
| **Quality and operations** | Jest, Vitest, Playwright, contract tests, health/readiness endpoints, request tracing, proof ledgers |

## How We Build

- **Evidence before claims:** builds and static checks are not represented as production proof.
- **Privacy by design:** product data stays isolated; public repositories expose only intended surfaces.
- **Human-governed AI:** consequential AI workflows retain review and approval checkpoints.
- **Fit-for-purpose infrastructure:** edge delivery for suitable workloads; persistent compute only where required.
- **Cost-conscious operations:** standardize and consolidate before adding another paid platform.
- **Handover-ready delivery:** working software ships with documentation, access boundaries, validation, and the next operational step.

## Open Source and Engineering Evidence

The public engineering portfolio is maintained in [fefejiro/FTC-HOLDING](https://github.com/fefejiro/FTC-HOLDING). It contains product code, shared packages, platform scripts, QA workflows, operational documentation, and release evidence. Some repositories remain private because they contain client-sensitive or product-sensitive implementation details.

## Work With Una Labs

Have a rough request, an operational bottleneck, or a product that needs a reliable delivery path?

<p align="center">
  <a href="https://unalabs.cloud/start"><img src="https://img.shields.io/badge/START%20YOUR%20BUILD-0F766E?style=for-the-badge&logo=rocket&logoColor=white" alt="Start your Una Labs build" /></a>
  <a href="https://unalabs.cloud/product"><img src="https://img.shields.io/badge/EXPLORE%20THE%20PLATFORM-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Explore the Una Labs platform" /></a>
  <a href="mailto:hello@unalabs.cloud"><img src="https://img.shields.io/badge/TALK%20TO%20US-111827?style=for-the-badge&logo=gmail&logoColor=white" alt="Talk to Una Labs" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:081426,35:0F766E,70:06B6D4,100:2563EB&height=110&section=footer" alt="Una Labs footer" />
</p>
