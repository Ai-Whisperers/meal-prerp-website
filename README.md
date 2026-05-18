# Meal prep — De Abasto a Casa / Edu Cano Galeano

Monorepo: **business documentation** (numbered folders) plus **public marketing site** (Next.js at repo root).

| Part | Location | Purpose |
|------|----------|---------|
| Operations & Edu program | `01_Admin_Hiring/` … `09_Active_Clients/`, `WEEKLY_CYCLE_SUMMARY.md` | SOPs, pricing, clients, incubation |
| Website copy & brand | `09_Website/` | Spanish copy, brand, image curation (source of truth for marketing text) |
| Public site (code) | `app/`, `public/`, `package.json` | Landing at [prep.paragu-ai.com](https://prep.paragu-ai.com) |

Related repo (full grocery / multi-section site): [Ai-Whisperers/de-abasto-a-casa](https://github.com/Ai-Whisperers/de-abasto-a-casa).

## Local development (website)

```bash
npm install
npm run dev      # http://localhost:3000
npm run build
npm run lint
```

## Docker deploy

```bash
docker compose build
docker compose up -d
```

Service listens on port **3010** (see `Dockerfile`, `docker-compose.yml`).

## Documentation

Start with `09_Website/00_Website_Plan.md` for what is live vs pending on the public site.
