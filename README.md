# GymSurvey
This project is going to be about a gym survey, it will be made mostly for my resume


Frontend
    Next.js (App Router)
    — React framework for hybrid static & server rendering
    TypeScript — Type-safe development across frontend and backend
    React Hook Form
    + Zod
    — Schema-driven form validation
    Tailwind CSS
    — Utility-first styling for rapid UI development
    Radix UI
    — Accessible UI primitives
    TanStack Query
    — Server state management (data fetching, caching, mutation)


Backend
    Next.js Route Handlers — RESTful API endpoints with server actions where useful
    PostgreSQL (Supabase) — Managed relational database with RLS and migrations
    Prisma ORM
    — Type-safe queries and schema migrations
    Auth.js
    — Authentication (Email/Password + OAuth) with multi-tenant org support
    Upstash Redis
    — For rate limiting, caching, and background job queue (via BullMQ)
    Cloudflare Turnstile
    — Anti-bot verification on public endpoints
    Plausible Analytics
    (or PostHog
    if preferred) — Privacy-friendly analytics & feature flags
    Object Storage: Supabase Storage (for survey file uploads, images, etc.)

DevOps / Quality
    GitHub Actions
    — CI/CD pipeline (typecheck, lint, test, migrate, deploy)
    Vitest
    — Unit testing
    Testing Library
    — Component testing
    Playwright
    — End-to-end testing
    Zod + OpenAPI
    — Contract tests between client and server
    Sentry
    — Error tracking and performance monitoring
    OpenTelemetry (optional) — Distributed tracing to OTLP
    Docker Compose — Local development setup for Postgres + Redis

Infrastructure:
    Vercel
    — Hosting for the web app
    Supabase
    — Managed PostgreSQL + Authentication + Storage
    Upstash Redis
    — Managed Redis (serverless)
    Cloudflare Turnstile — Anti-bot verification
    (Optional) R2 (Cloudflare Object Storage) — Alternative to Supabase Storage for large or static asset