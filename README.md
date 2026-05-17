# SSME Hub Portal

Landing page and app launcher for **Soon Seng Motors Enterprise (1988) Sdn. Bhd.**  
Kota Bharu, Kelantan.

**Live:** [ssmehub.com](https://ssmehub.com)

---

## What This Is

A single internal portal that links all SSME business modules together. Shows live system status, quick stats, and a roadmap of all planned applications.

---

## Modules

| # | Module | Status |
|---|--------|--------|
| — | Quotation System | ✅ Live |
| 1 | Customer & Fleet Database | Phase 1 |
| 2 | Stock Card & WIP Tracker | Phase 1 |
| 3 | Workshop CRM | Phase 2 |
| 4 | Workshop Operations | Phase 2 |
| 5 | Parts Department | Phase 2 |
| 6 | Document Library | Phase 3 |
| 7 | HDMS Integration | Phase 3 |
| 8 | Second Hand & Trade-In | Phase 3 |
| 9 | Online Marketing | Phase 4 |
| 10 | HR & Training | Phase 4 |

---

## Tech Stack

| Layer | Technology |
|---|---|
| Hosting | Cloudflare Workers (static assets) |
| Domain | ssmehub.com |
| Build | Plain HTML/CSS — no framework |

---

## Deploying

```bash
npx wrangler deploy
```

Deploys to `ssmehub.com` via Cloudflare Workers. No build step — edit `dist/index.html` directly.

---

## Part of SSME Hub

All modules live under the [SSMEHub GitHub org](https://github.com/SSMEHub).  
Internal documentation and decisions are maintained in Obsidian.
