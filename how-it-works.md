# How It Works

## High-level product structure

- A single public homepage with inline selected-work detail instead of separate case-study pages.
- A typed content layer drives public copy, project summaries, media, links, and resume metadata.
- Global metadata, robots, sitemap, social preview images, analytics gating, and security headers are owned by the app.
- Focused tests cover navigation, metadata, accessibility, links, observability, and security headers.

## Technology at a safe public level

- Next.js App Router, React, TypeScript, and Tailwind CSS.
- Vercel-hosted production build from main.
- Vercel Web Analytics and Speed Insights are gated to production.
- Playwright and Lighthouse CI cover focused quality checks.

## What is intentionally not documented here

- Source-code layout beyond broad product areas.
- API implementation details.
- Database schemas or migrations.
- Auth, session, token, or authorization internals.
- Deployment secrets, provider credentials, or private infrastructure.
- Hidden routes, internal prompts, proprietary algorithms, or client-sensitive data.
