# Hi, I'm Henrique Medeiros ⚡

**Full-stack Engineer — automation, payments and desktop apps**

Software Engineering student (Class of 2028) in Brazil. I build complete products
instead of isolated exercises: the automation engine, the web platform that sells it,
the licensing that protects it, and the pipeline that ships it.

---

## 🚀 Featured Work

### Pantero IA — automation platform (desktop · web · browser extension)

A commercial product across three integrated surfaces. Designed, built and maintained solo.

**Desktop app — Python · FastAPI · Tauri (Rust) · Next.js**
- Decoupled architecture: FastAPI backend and Next.js/TypeScript frontend bundled as a
  native Windows app via Tauri, with the Python services shipped as sidecar binaries.
- Headless browser orchestration (Selenium) driven by async task queues, with a driver
  lock serializing access to the shared browser session.
- **Trade-off:** chose SQLite in WAL mode over a client/server database — the app runs
  entirely on the user's machine, so WAL gave me concurrent reads during writes without
  forcing an external dependency onto the install.
- Custom signed auto-update pipeline: minisign-signed artifacts, manifest proxied through
  the website, binaries distributed via GitHub Releases.

**Web platform — Next.js · Prisma · PostgreSQL**
- Automated provisioning: payment confirmed → user created → license issued → welcome
  email, with no manual step in between.
- PIX checkout (Mercado Pago), webhooks verified with HMAC SHA-256 and retried on failure.
- Redis-backed rate limiting, Cloudflare Turnstile, disposable-email blocking, and
  first-touch attribution (UTMs + click IDs).
- Referral system: unique codes, 90-day attribution cookie, recurring commission computed
  per payment.

**Browser extension — Chrome/Edge**
- Generates the affiliate link and a ready-to-post message straight from the product page,
  talking to the app's local backend — same license, no separate login.

**Licensing & infra**
- Hardware-locked (HWID) licensing via KeyAuth, with plan-based feature gating enforced
  server-side rather than in the UI.
- Cloudflare Worker for click tracking on a custom domain, cron jobs, Sentry, admin panel.

---

### Rage Store — automated digital delivery

- **Node.js** service integrated with the **Mercado Pago API**.
- Zero-touch sales cycle: real-time PIX validation, webhook handling and instant
  automated product delivery.

---

## 🛠️ Tech Stack

**Languages:** Python · TypeScript · JavaScript · C#
**Backend:** FastAPI · Node.js · REST APIs · async task queues
**Frontend & Desktop:** Next.js · React · Tauri (Rust) · Tailwind CSS
**Data & Infra:** PostgreSQL (Prisma) · SQLite (WAL) · Cloudflare Workers · Vercel · Git

---

*Open to Software Engineering internships and junior roles — remote or São Luís/MA, Brazil.*

📫 [LinkedIn](https://www.linkedin.com/in/ryk-medeiros) · ✉️ Email: rick.medeiros223@icloud.com
