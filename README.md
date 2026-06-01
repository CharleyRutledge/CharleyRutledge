QA engineer building test tooling, compliance products, and small SaaS experiments — mostly TypeScript/React, Python, and Playwright, with AI where it actually saves time.

Writing at [theqaperspective.com](https://theqaperspective.com).

---

## What I'm working on now

**[SpecDrive](https://specdrive.net/)** — Micro-SaaS that turns written requirements into structured test cases. React, Supabase, Stripe, Vercel. Repo: `specdrive-ai-generator`.

**[QA Forge](https://github.com/CharleyRutledge/QA_Forge)** — Autonomous QA agent + dashboard: crawl a site, generate Playwright tests, run them from a React UI backed by a hardened Express API (no managed BaaS).

**[eu-pay](https://github.com/CharleyRutledge/eu-pay)** — EU data-sovereignty scanner (React + Fastify). Shipping product work on GitHub; ISO 27001 / GDPR documentation maintained locally with `isocheck`.

**[spark-connect](https://github.com/CharleyRutledge/spark-connect)** — *Zing or Sting*: mobile-first speed-dating web app (TanStack Start, Supabase realtime chat). Active on `feat/v3-profiles-badges-admin`.

**[5skseries-autopilot](https://github.com/CharleyRutledge/5skseries-autopilot)** — Print-on-demand pipeline: Claude copy → Pillow renders → Notion/Telegram → marketplace upload queues. Current branch adds pixel/cyberpunk character assets.

---

## Other active repos (local `C:\Users\amkei\Repos`)

| Project | What it is |
|--------|------------|
| [Automation_Idea](https://github.com/CharleyRutledge/Automation_Idea) | **domtrace** — learn UI flows from passing Playwright traces, validate runs with dominator-based matching |
| [Game](https://github.com/CharleyRutledge/Game) | Unity Stardew-style farm prototype (side project) |
| [ScreenshotMaster](https://github.com/CharleyRutledge/ScreenshotMaster) | Screenshot capture + workflow export tooling |
| [MoanyMouse](https://github.com/CharleyRutledge/MoanyMouse) | Desktop app: mouse velocity → reactive audio |
| [Job-Application-Applier](https://github.com/CharleyRutledge/Job-Application-Applier) | Chrome extension for LinkedIn QA job applications |
| [linkedin-ai-detector](https://github.com/CharleyRutledge/linkedin-ai-detector) | Detect / redact AI-generated LinkedIn content |
| [isocheck](https://github.com/CharleyRutledge/isocheck) | Local ISO compliance auditor (used against `eu-pay` and other repos) |
| [Playwright-UI-](https://github.com/CharleyRutledge/Playwright-UI-) | Flask/pywebview dashboard for crawl → generate → run Playwright (Python) |

On GitHub but not cloned under `Repos` right now: **ai-obituary-writer-**, **Automation** (Python Playwright POM suite).

---

## Stack I reach for most

- **Test & QA:** Playwright (TS + Python), pytest, Vitest, semantic selectors, Page Object Model
- **App:** React, Vite, Next.js 15, Tailwind, shadcn/ui
- **Backend:** Express, Fastify, Supabase (auth/RLS/realtime where it fits)
- **AI:** Anthropic Claude (`claude-sonnet-4-6`), OpenAI in edge functions where needed
- **Payments:** Stripe Checkout / subscriptions
- **Ops:** Vercel, GitHub Actions, Windows + PowerShell for local automation

---

## How I work

- Monorepo-style folder: `C:\Users\amkei\Repos` — one git repo per project, all synced to GitHub under [@CharleyRutledge](https://github.com/CharleyRutledge)
- Prefer small, reviewable commits; feature branches for anything non-trivial
- MCP- and rules-driven workflows for AI-assisted testing and codegen
