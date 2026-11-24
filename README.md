<div align="center">

<img src="https://raw.githubusercontent.com/Studio1HQ/Studio1HQ/main/assets/banners/Velt-Tempo-Starter.webp" alt="Tempo and Velt Starter Kit: A dark analytics dashboard starter with Supabase, Stripe and Velt" width="100%" />

<br />
<br />

# Tempo and Velt Starter Kit

### A dark analytics dashboard starter with Supabase, Stripe and Velt

A React and Vite starter with a dark analytics dashboard, Supabase auth and database, Stripe subscriptions and Velt presence, cursors and comments. Built with TempoLabs.

<br />

[![Built by Studio1](https://img.shields.io/badge/Built_by_Studio1-f97316?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxNjAgMTYwIiBmaWxsPSJub25lIj48cGF0aCBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZD0iTTAgMzVDMCAxNi42ODA3IDE0LjA3NDQgMS42NDg0NCAzMiAwLjEyNjk1M1YxNDFINTEuMDUyM0M1Mi40MzA4IDEzNy4zNDQgNTQuNzQ0NiAxMzMuNjg5IDU3Ljk5MzggMTMwLjAzM0M2MS4xNDQ2IDEyNi41MDggNjQuNjg5MiAxMjMuNDQgNjguNjI3NyAxMjAuODI5QzcyLjU2NjIgMTE4LjM0OSA3Ni4zNTY5IDExNi43ODIgODAgMTE2LjEyOVY4Ni43NTQ0Qzc1LjQ3MDggODcuOTI5MiA3MS4zODQ2IDg5LjY5MTkgNjcuNzQxNSA5Mi4wNDE1QzY0IDk0LjUyMjUgNjAuNzUwOCA5Ny40NiA1Ny45OTM4IDEwMC44NTRDNTYuNTM0NSAxMDIuNzIgNTUuMjU0NSAxMDQuNjU5IDU0LjE1MzkgMTA2LjY3MVYwSDEyNUMxNDQuMzMgMCAxNjAgMTUuNjY5OSAxNjAgMzVWMTI1QzE2MCAxNDQuMzMgMTQ0LjMzIDE2MCAxMjUgMTYwSDEyNFYxOEgxMDQuOTQ4QzEwMy41NjkgMjEuNjgxNiAxMDEuMjU1IDI1LjM2MjggOTguMDA2MiAyOS4wNDQ0Qzk0Ljg1NTQgMzIuNTk0MiA5MS4zMTA4IDM1LjY4NDEgODcuMzcyMyAzOC4zMTRDODMuNDMzOCA0MC44MTIgNzkuNjQzMSA0Mi4zODk2IDc2IDQzLjA0NzRWNzIuNjMwNEM4MC41MjkyIDcxLjQ0NzMgODQuNjE1NCA2OS42NzI0IDg4LjI1ODUgNjcuMzA1N0M5MiA2NC44MDc2IDk1LjI0OTIgNjEuODQ5MSA5OC4wMDYyIDU4LjQzMDdDOTkuNDY1NSA1Ni41NTEzIDEwMC43NDUgNTQuNTk4NiAxMDEuODQ2IDUyLjU3MjNWMTYwSDM1QzE1LjY3IDE2MCAwIDE0NC4zMyAwIDEyNVYzNVoiIGZpbGw9IiNmZmZmZmYiLz48L3N2Zz4K)](https://studio1hq.com)
[![Built with Velt](https://img.shields.io/badge/Built_with_Velt-141414?style=for-the-badge)](https://velt.dev)
[![Live demo](https://img.shields.io/badge/Live_demo-1c1917?style=for-the-badge&logo=vercel&logoColor=white)](https://velt-tempo.vercel.app/)

[Velt docs](https://docs.velt.dev) &nbsp;·&nbsp; [Velt](https://velt.dev) &nbsp;·&nbsp; [More examples](https://github.com/Studio1HQ) &nbsp;·&nbsp; [studio1hq.com](https://studio1hq.com)

</div>

<br />

## Overview

This is a dark-themed analytics dashboard starter built with React, TypeScript, Tailwind CSS, Supabase, Stripe and [Velt](https://velt.dev), created with TempoLabs. It gives you auth, subscription billing and a dashboard, with collaboration already wired in.

Velt adds presence awareness, cursor following and comments to the dashboard pages. `VeltProvider` wraps the app and a `VeltAuth` component identifies the signed-in Supabase user. Dashboard pages set a Velt document with `useSetDocument`.

<p align="center"><img src="https://github.com/user-attachments/assets/bd5a73e6-4cd7-447f-8834-54c3215af2fa" alt="Tempo and Velt starter dashboard" width="100%" /></p>

<p align="center"><a href="https://github.com/user-attachments/assets/68f9ca13-7bab-479c-9c1c-83cbc1d84926">Watch the demo video</a></p>

This repo's default branch is `veltic`.

## Features

- **Dark-themed UI**: A dashboard designed for long sessions.
- **Analytics dashboard**: Metric cards, charts, data visualizations, advanced filters, an activity feed and a task board.
- **Authentication**: Supabase auth with sign up, sign in and protected routes.
- **Subscription payments**: Stripe checkout and webhooks through Supabase Edge Functions, with Basic, Pro and Enterprise plans.
- **Velt collaboration**: `VeltPresence`, `VeltCursor`, `VeltComments`, `VeltCommentTool`, `VeltCommentBubble` and a comments sidebar.
- **UI components**: Radix UI and shadcn/ui components, responsive layout.
- **TempoLabs integration**: A `tempo.config.json` for visual editing and AI tools.

## Tech stack

| Layer | Tool |
| --- | --- |
| Framework | [React](https://react.dev), TypeScript, [Vite](https://vitejs.dev), React Router |
| Collaboration | [Velt](https://velt.dev) (`@veltdev/react`) |
| Backend and auth | [Supabase](https://supabase.com) (Auth, Database, Edge Functions) |
| Payments | [Stripe](https://stripe.com) |
| UI | [Tailwind CSS](https://tailwindcss.com), [shadcn/ui](https://ui.shadcn.com), [Radix UI](https://www.radix-ui.com), React Hook Form with Zod |
| Dev tools | [TempoLabs](https://www.tempo.new/) |
| Deployment | [Vercel](https://vercel.com) |

## Getting started

### Prerequisites

- Node.js 16 or later
- npm or yarn
- A [Supabase](https://supabase.com) account
- A [Stripe](https://stripe.com) account for payments
- A [Velt](https://console.velt.dev) account and API key
- A [TempoLabs](https://www.tempo.new/) account (optional)

### Installation

```bash
git clone https://github.com/Studio1HQ/Velt-Tempo-Starter.git
cd Velt-Tempo-Starter
git checkout veltic
npm install   # or: yarn install
```

### Environment variables

Create a `.env` file in the project root.

| Variable | Description |
| --- | --- |
| `VITE_SUPABASE_URL` | Supabase project URL. |
| `VITE_SUPABASE_ANON_KEY` | Supabase anon key. |
| `VITE_VELT_API_KEY` | Velt API key from the Velt console. |

The Supabase Edge Functions also read `STRIPE_SECRET_KEY`, `STRIPE_WEBHOOK_SECRET`, `SUPABASE_URL` and `SUPABASE_SERVICE_ROLE_KEY` from the function environment.

### Run

```bash
npm run dev    # or: yarn dev
```

Open `http://localhost:5173`. Other scripts: `npm run build`, `npm run preview`, `npm run lint`, and `npm run types:supabase` to regenerate Supabase types (needs `SUPABASE_PROJECT_ID`).

Supabase setup:

1. Create a Supabase project.
2. Set up authentication providers (email, OAuth and so on).
3. Deploy the Edge Functions:

```bash
supabase functions deploy get-plans
supabase functions deploy create-checkout
supabase functions deploy payments-webhook
```

For Velt, create a project in the Velt console and add its API key to `.env`. For TempoLabs, create an account at [tempo.new](https://www.tempo.new/) and follow the Vite, Supabase and Stripe guide linked below.

## How it works

```text
src/
├── components/
│   ├── auth/         login, sign up, layout
│   ├── dashboard/    metric cards, charts, filters, activity feed, task board
│   ├── landing/      hero, features, pricing, testimonials, footer
│   ├── pages/        home, dashboard, analytics dashboard, plans, success
│   ├── ui/           shadcn/ui components
│   └── velt/         VeltAuth: identifies the Supabase user in Velt
├── context/          AuthContext
├── lib/              utilities and constants
└── types/            Supabase types
supabase/
├── functions/        create-checkout, get-plans, payments-webhook
└── migrations/       initial-setup.sql
tempo.config.json     TempoLabs configuration
```

To add a page, create a component in `src/components/pages` and add its route in `App.tsx`. Theme settings are in `tailwind.config.js`, and UI components can be edited in `src/components/ui`. For deployment on Vercel, push the repo, import it in Vercel and set the environment variables.

## Resources

- [Live demo](https://velt-tempo.vercel.app/): the deployed starter.
- [Velt documentation](https://docs.velt.dev): SDK guides.
- [Velt](https://velt.dev): product site.
- [TempoLabs](https://www.tempo.new/): the AI-powered React builder used with this kit.
- [Tempo guide for Vite, Supabase and Stripe](https://tempolabsinc.mintlify.app/ViteSupabaseStripe): setup documentation.
- [Supabase](https://supabase.com/docs): auth and Edge Functions docs.

<br />

---

<div align="center">

<a href="https://studio1hq.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Studio1HQ/website/main/brand/studio1-logo-on-dark.svg" />
    <img src="https://raw.githubusercontent.com/Studio1HQ/website/main/brand/studio1-logo-on-light.svg" alt="Studio1" width="160" />
  </picture>
</a>

Built by **[Studio1](https://studio1hq.com)**, the technical content and DevRel partner for devtool teams. Made with [Velt](https://velt.dev).<br />
Browse more open-source examples at [github.com/Studio1HQ](https://github.com/Studio1HQ).

[![Website](https://img.shields.io/badge/studio1hq.com-0b0807?style=for-the-badge&logo=googlechrome&logoColor=white)](https://studio1hq.com)
[![Book a call](https://img.shields.io/badge/Book_a_strategy_call-f97316?style=for-the-badge&logo=googlecalendar&logoColor=white)](https://cal.com/studio1/collab)
[![X](https://img.shields.io/badge/%40Studio1HQ-141414?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Studio1HQ)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/studio1hq/)

<sub><a href="https://studio1hq.com">studio1hq.com</a> · Technical content, docs, video and DevRel for devtools</sub>

</div>
