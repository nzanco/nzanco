## Nikolaj Sankov

Informatik B.Sc. student at **TU Berlin**. I design and ship full-stack web applications
that real businesses run on — mostly **Next.js, TypeScript, PostgreSQL** and **Prisma**,
deployed on Vercel.


---

### Selected work

#### XStudio — booking platform for a Berlin barber studio
**[xstudio-zyron.vercel.app](https://xstudio-zyron.vercel.app)** · solo project · 305 commits

A production booking system, built end to end:

- Multilingual public site and booking flow (**DE / EN / RU**) with localized routing
- Customer account area and a full admin application — calendar, appointments,
  customers, barbers, services, settings
- Authentication and role authorization (Clerk + Prisma)
- Transactional email through a persisted **notification outbox with a retry worker**
- Durable **Clerk webhook processing**, replayable after failure
- Correct `Europe/Berlin` timezone handling across booking, calendar and admin
- Unit, database-backed, stress, security and browser test suites

`Next.js App Router` `TypeScript` `PostgreSQL` `Prisma` `Clerk` `Resend` `Playwright` `Docker`

---

#### ruplatform — directory of Russian-speaking service providers in Germany
**[ru-platform.vercel.app](https://ru-platform.vercel.app)** · with [@alexzanco](https://github.com/alexzanco)

Berlin-first, SEO-driven directory of lawyers, doctors and tax advisors, with a
provider self-serve onboarding pipeline and an editorial blog/content system.

- Next.js App Router application in a **Turborepo monorepo**
- Provider claim and verification flow with OTP and document upload
- Curation tooling with duplicate detection and match grading
- Editorial content system with structured taxonomy
- Architecture documentation and written PRDs; **zero-warning ESLint policy**

`Next.js` `TypeScript` `Turborepo` `pnpm` `PostgreSQL` `Prisma` `MinIO` `Docker` `Vitest`

---

#### Neuronka — learning platform for the coding school I co-run
**[neuronka.de](https://www.neuronka.de)** · [platform](https://neuronka-platform-web.vercel.app) · with [@alexzanco](https://github.com/alexzanco)

A browser-based lesson runner and homework surface replacing the printed worksheet.
Piloted with the autumn 2026 cohort.

- **Pyodide runtime** running Python in the browser, with an AST and
  namespace-based assertion engine for automatic exercise checking
- **17 task formats** built against a versioned capability manifest and
  JSON-Schema lesson-bundle contract
- Learner runner, progress summary and a teacher board
- MakeCode tracks for Minecraft Education (ages 8–10) and Arcade → Python (10–12)

`Next.js` `TypeScript` `Pyodide` `Python` `JSON Schema` `pnpm workspaces`

---

#### C&L Facility Management — client website
**[cl-fm-website2.vercel.app](https://cl-fm-website2.vercel.app)** · solo project · 153 commits

Bilingual (DE/EN) marketing site for a facility management company serving
Berlin and Brandenburg — custom design, SEO, and contact/enquiry forms.

`Next.js` `TypeScript` `i18n` `SEO`

---

### A note on my repositories

Most of my work lives in **private client repositories** — roughly **1.100 commits**
and **46 reviewed pull requests** in 2026. The code isn't public because it belongs to
running businesses, but I'm glad to walk through any of it, or through specific pull
requests, on request.

---

### Also here

- **[Real-time person tracking](https://github.com/nzanco/Real-Time-Person-Tracking-and-Gate-Crossing-Detection)** — gate-crossing detection with YOLO and a custom tracker (Python)
- **[MakeCode Arcade](https://github.com/nzanco/makecode-arcade-ru-tutorials)** and **[Minecraft](https://github.com/nzanco/makecode-minecraft-ru-tasks)** translations — Russian lesson content loaded by the Neuronka platform

---

### Background

Alongside my studies I completed **1.425 teaching units** at Tel-Ran.de Berlin in
programming fundamentals, Java/Web/Mobile development, and **QA / test automation**
(Selenium WebDriver, PageObject, JUnit & TestNG, Maven, Jenkins, Jira).

📍 Berlin, Germany · 💼 open to Werkstudent roles
