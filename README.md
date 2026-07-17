# Fabio Chippari

Computer Engineering student at Mackenzie (São Paulo, Brazil), graduating 2029.
I build systems that run in production — data pipelines, automations, and the
infrastructure around them. Moving toward AI engineering.

**Italian (EU) and Brazilian citizen.** No visa sponsorship required to work in the EU.

---

## Now

Working through Andrej Karpathy's *Neural Networks: Zero to Hero* by hand — no AI
assistance, no copying from the reference repo.
→ [`nn-zero-to-hero-notes`](https://github.com/chippari/nn-zero-to-hero-notes)

---

## Work

### Capitech Store — IT lead & systems developer · 2026–present
Importer and reseller operating across Shopee, Mercado Livre, Amazon and TikTok Shop.
Sole engineer: I own IT end to end — systems development, automation, and the technical
side of the operation.

- **Marketplace financial reporting SaaS** — consolidates raw financial exports from four
  marketplaces, each with its own schema and financial semantics, into a single report
  with COGS and tax applied per SKU. Dedicated parser per marketplace, canonical SKU model
  with alias learning, template-preserving Excel generation, zero retention of financial
  data (in-memory only). Running in production.
  *FastAPI · Next.js · Supabase · Docker · Coolify · GitHub Actions → GHCR*
- **Internal operations system** — automated Instagram publishing and a Mercado Livre
  scraper for trending products. In production.
  *TypeScript · Next.js*
- **E-commerce storefront** — WordPress/WooCommerce sales channel with a custom child
  theme, Brazilian checkout, LGPD-compliant.

### Razorbil Consulting — IT lead & systems developer · 2026–present · [razorbil.com.br](https://razorbil.com.br)
Boutique strategy and technology consultancy for companies going through
professionalization. Sole engineer: I build the software it delivers with.

- **Transit-benefit optimization platform** — data pipeline plus a web operations
  interface that turns raw client data into a finished report. Used in production by the
  consultancy to deliver a client-facing service.
  *Python*
- **Daily collection bot** — Telegram bot that proactively runs a structured 22-step daily
  collection with school units for billing. Engine/channel separation (the conversation
  loop is testable without a Telegram token), state anchored in Postgres so it survives
  restarts mid-conversation, configuration as data (new unit = new CSV, not new code),
  escalation ladder with scheduled reminders and fallback contacts.
  *TypeScript · grammY · Prisma · BullMQ · Redis · Docker*
- **Institutional website** — [razorbil.com.br](https://razorbil.com.br). Next.js,
  TypeScript, accessible markup, LGPD-compliant contact flow.

Company and client work is private. Happy to walk through architecture and decisions —
just reach out.

---

## Stack

**Languages** Python · TypeScript · JavaScript
**Backend** FastAPI · Node.js · PostgreSQL · Prisma · Redis
**Frontend** Next.js · React · Tailwind
**Infra** Docker · Coolify · GitHub Actions · Supabase
**Learning** PyTorch · neural networks from scratch

---

## Contact

[LinkedIn](https://www.linkedin.com/in/fabio-chippari-brito-0a194a261/) ·
[fabiochipparibrito@gmail.com](mailto:fabiochipparibrito@gmail.com)

Open to summer 2027 internships in AI engineering — Dublin, Zurich, Amsterdam, Munich.
