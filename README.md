# Hi, I'm Tuan Huynh 👋

**SDET / Test Automation Engineer** · Da Nang, Viet Nam · Open to opportunities

I design test-automation frameworks that stay maintainable as the product grows, and I write
enough production code to understand exactly what I'm testing.

## 🧪 What I do

- **Automation framework architecture**: layered UI + API frameworks built on SOLID, page/section
  objects scoped to their parent, one composition root (fixtures/DI), and idempotent data teardown
- **UI & API testing**: Playwright (TypeScript), Selenium + TestNG / Guice (Java), Serenity
  (Page Object & Screenplay), Cypress, Postman, Appium-based mobile testing
- **Security testing**: OWASP Top 10 test suites, authorization / data-scope (BOLA) tests,
  web-pentest study notes
- **Test design & QA process**: requirements → test cases traced to acceptance criteria → automation → CI
- **AI-assisted QA**: Claude Code skills and agents that turn user stories into test cases and run
  them with human approval gates

## 🚀 Featured projects

| Project | What it shows |
| --- | --- |
| [playwright-poc](https://github.com/huynhviettuan/playwright-poc) | Playwright + TypeScript framework: SOLID, container-based page objects, controller-pattern API services, Report Portal |
| [sdet-skills](https://github.com/huynhviettuan/sdet-skills) | Portable Claude Code skills that cover the whole SDET lifecycle, from requirements and test design to framework scaffolding, performance and security testing |
| [manual-qa-agent](https://github.com/huynhviettuan/manual-qa-agent) | AI agent for manual QA: stories → cited test cases → browser runs with evidence → failure triage, with human gates |
| [fitness-crm](https://github.com/huynhviettuan/fitness-crm) | Full-stack multi-branch gym CRM (Next.js + NestJS + PostgreSQL) with unit, integration, Playwright E2E and OWASP security suites |
| [selenium-using-guice](https://github.com/huynhviettuan/selenium-using-guice) | Selenium/Java framework with Guice DI, run in Docker with scalable browser instances |
| [web-pentester](https://github.com/huynhviettuan/web-pentester) | Structured web-security learning path: OWASP, SQLi, CSRF, JWT and more |

## 🛠️ Tech stack

**Testing:** Playwright · Selenium WebDriver · TestNG · Serenity BDD · Cypress · RestAssured · Postman · Appium · Percy
**Languages:** TypeScript · JavaScript · Java
**Dev:** Next.js · NestJS · Prisma · PostgreSQL · Zod
**CI / tooling:** GitHub Actions · Jenkins · Docker · Report Portal · Allure · ESLint / Prettier

## 💡 How I work

- Assert on what users can observe, and only mock at the external boundary
- Wait on the real signal instead of sleeping, so race conditions aren't hidden
- Whoever creates test data cleans it up, so parallel runs are safe
- YAGNI: a helper gets extracted when a second real use shows up, not before

---
*"Even a pig can fly if it stands at the center of a whirlwind."*