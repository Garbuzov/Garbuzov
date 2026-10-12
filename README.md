# Andrey Garbuzov

**Lead Frontend engineer (TypeScript / React) — hands-on.** 18 years in web, 5+ of them as a technical lead: architecture, code every day, hiring and mentoring.

I write software, and I build the tooling that makes writing software faster. My current focus is running AI coding agents in a way a company can actually approve: local models for closed-source code, measured token budgets, and explicit rules about what an agent is not allowed to touch.

Open to Lead / Staff Frontend roles — remote or hybrid, Saint Petersburg.

---

## What I am building

**[local-ai-dev-harness](https://github.com/Garbuzov/local-ai-dev-harness)** — the agent setup I use daily, published so others can adapt it.

- Two agent presets: light (one MCP server, **~1,307 tokens** of overhead per request) and full (**~15,567**). Choosing per task instead of enabling everything is the single biggest cost lever.
- **10 engineering skills**: code review, browser debugging, performance audits, git workflow, Node API scaffolding, interview preparation, vetting third-party skills.
- **4 tools**: a scanner for untrusted third-party agent instructions, an MCP token-cost meter, a preset validator and a spend report.
- A verified React + TypeScript scaffold with strict types, tests and CI.

Every number in that repository was measured, not estimated.

## What I do at work

- **Architecture of complex SPAs.** Feature-Sliced Design and DDD, React 18 + Vite, MobX. Built an enterprise data dashboard for the public sector, including an interactive SVG map of Russia: smooth zoom and pan, geometry recalculated on every filter change, heavy math moved to Web Workers to keep the UI responsive.
- **Performance with numbers attached.** Custom MobX cache strategy (stale-while-revalidate): −40% network load, +25% navigation speed. On a Norwegian e-commerce build: FCP 0.8 s and −50% image weight after moving to dynamic WebP.
- **Testing where it pays.** Playwright on critical flows (sign-up, chat, file upload) plus Vitest for units — aimed at the regressions that unit tests structurally cannot catch.
- **Cross-stack work.** Reading and patching C# (ASP.NET), and writing a Node.js API layer to unblock integrations without waiting on the backend team.
- **Hiring and growing people.** 40+ interviews, 10+ engineers hired and mentored, plus a set of fundamental questions that separates "knows React" from "understands the web".

## Stack

TypeScript · React · Next.js · Vue · MobX · Redux · Vite · Playwright · Vitest · Node.js · C# (reading and patching) · Docker · CI/CD

MCP · local models (Ollama) · agent presets · prompt and context cost control

## Contact

- Telegram: [@ganeshvara](https://t.me/ganeshvara)
- Email: hypercube@inbox.ru
- Based in Saint Petersburg, Russia
