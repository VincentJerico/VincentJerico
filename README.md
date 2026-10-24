# Hi, I'm [Vincent](https://github.com/VincentJerico) 👋

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=58A6FF&vCenter=true&width=600&lines=QA+Engineer+%40+BossLabs.AI+%E2%86%92+SDET;Playwright+%C2%B7+API+%C2%B7+Accessibility+%C2%B7+Security;Every+suite+runs+in+CI" alt="QA Engineer at BossLabs.AI, on the path to SDET" />

I'm a QA Engineer at **BossLabs.AI**, where I test client business platforms before they ship. On GitHub
I'm building a public QA automation portfolio: **one repo per testing skill**, each with its own CI,
real targets, and written findings. I'm working toward an **SDET** role, with Cybersecurity and Cloud
Engineering next.

**Highlights**

- **6 public QA repos**, every one green in CI on GitHub Actions
- **7 WCAG 2.2 failures** found by keyboard audit on a site where automated axe-core scans reported 0
- **8 security findings** mapped to the OWASP Top 10, each check with a self-test proving it can fail
- **Cross-browser** Playwright framework (Chromium, Firefox, WebKit) with fixtures, page objects and saved auth

---

## [ ABOUT ]

```yaml
vincentjerico@github ~ $ whoami

  role      : QA Engineer @ BossLabs.AI   # goal → SDET
  degree    : BSc in Information Technology
  focus     : test automation · Playwright · API · performance · accessibility · security
  exploring : Cybersecurity · Cloud Engineering
  location  : Cavite, Philippines
  contact   : vincentjericoalcuran@gmail.com

vincentjerico@github ~ $ cat now.txt

  Next repo: performance-testing (k6 load, stress and soak tests in CI).
```

## [ PROJECTS ]

**`[01]` qa-engineering-journey**<br>
Manual testing, test design, API, UI automation, SQL, performance (k6), security and AI evaluation,
each run against a live target. The automation, SQL checks, k6 scripts and AI evals run in CI.<br>
`stack →` Playwright · k6 · SQL · GitHub Actions &nbsp;·&nbsp; [**‹ code ›**](https://github.com/VincentJerico/qa-engineering-journey)

**`[02]` playwright-framework-template**<br>
A reusable Playwright + TypeScript starter with custom fixtures, page objects, per-environment config,
saved login state, data factories, and CI on Chromium, Firefox and WebKit.<br>
`stack →` Playwright · TypeScript · Faker · GitHub Actions &nbsp;·&nbsp; [**‹ code ›**](https://github.com/VincentJerico/playwright-framework-template)

**`[03]` api-testing-framework**<br>
Typed API tests on Playwright's request API. Zod schemas check each response through a custom
`toMatchSchema` matcher, fixtures handle auth, and every test deletes the data it creates. CI also
runs weekly to catch changes in the live API.<br>
`stack →` Playwright · TypeScript · Zod · Faker &nbsp;·&nbsp; [**‹ code ›**](https://github.com/VincentJerico/api-testing-framework)

**`[04]` taskflow-under-test**<br>
A small task-manager app I built to test. It has unit, API and E2E suites, a written test strategy,
and a set of planted bugs the suite has to catch.<br>
`stack →` Express · SQLite · Vitest · Playwright &nbsp;·&nbsp; [**‹ code ›**](https://github.com/VincentJerico/taskflow-under-test)

**`[05]` accessibility-testing**<br>
WCAG 2.2 AA testing of SauceDemo with axe-core and a keyboard audit. axe-core's WCAG rules reported
0 violations. The keyboard audit found 7 WCAG failures, including a cart that keyboard users can't
reach. Each finding has evidence and a test that tracks it.<br>
`stack →` Playwright · axe-core · TypeScript · WCAG 2.2 &nbsp;·&nbsp; [**‹ code ›**](https://github.com/VincentJerico/accessibility-testing)

**`[06]` security-testing**<br>
Defensive security checks against OWASP Juice Shop, running locally in Docker: a ZAP passive scan,
header, error-page and session-cookie checks, and Trivy dependency scans, all gated in CI. The
findings report maps 8 findings to the OWASP Top 10, and every check has a self-test that proves
it can fail.<br>
`stack →` Playwright · OWASP ZAP · Trivy · Docker &nbsp;·&nbsp; [**‹ code ›**](https://github.com/VincentJerico/security-testing)

## [ STACK ]

| TESTING | AUTOMATION | API | DATA | CLOUD / DEVOPS | SECURITY |
|---|---|---|---|---|---|
| Manual · Exploratory | Playwright | Postman | SQL | GitHub Actions · Docker | OWASP ZAP · Trivy |
| Test design (EP/BVA) | Vitest · Supertest | REST | SQLite | Git · CI/CD | Auth / access control |
| Bug reporting | k6 (performance) | Contract & schema | Data validation | AWS *(learning)* | Security headers |

<img src="https://skillicons.dev/icons?i=playwright,ts,js,nodejs,postman,sqlite,githubactions,docker,git,bash,aws&theme=dark" alt="Playwright, TypeScript, JavaScript, Node.js, Postman, SQLite, GitHub Actions, Docker, Git, Bash, AWS" />

<sub>+ k6 · Vitest · Supertest · Zod · axe-core · OWASP ZAP · Trivy</sub>

## [ CI STATUS ]

| Project | CI | Stars |
|---------|----|-------|
| [qa-engineering-journey](https://github.com/VincentJerico/qa-engineering-journey) | ![CI](https://github.com/VincentJerico/qa-engineering-journey/actions/workflows/ci.yml/badge.svg) | ![Stars](https://img.shields.io/github/stars/VincentJerico/qa-engineering-journey?style=flat-square&labelColor=0d1117&color=1f6feb) |
| [playwright-framework-template](https://github.com/VincentJerico/playwright-framework-template) | ![CI](https://github.com/VincentJerico/playwright-framework-template/actions/workflows/ci.yml/badge.svg) | ![Stars](https://img.shields.io/github/stars/VincentJerico/playwright-framework-template?style=flat-square&labelColor=0d1117&color=1f6feb) |
| [api-testing-framework](https://github.com/VincentJerico/api-testing-framework) | ![CI](https://github.com/VincentJerico/api-testing-framework/actions/workflows/ci.yml/badge.svg) | ![Stars](https://img.shields.io/github/stars/VincentJerico/api-testing-framework?style=flat-square&labelColor=0d1117&color=1f6feb) |
| [taskflow-under-test](https://github.com/VincentJerico/taskflow-under-test) | ![CI](https://github.com/VincentJerico/taskflow-under-test/actions/workflows/ci.yml/badge.svg) | ![Stars](https://img.shields.io/github/stars/VincentJerico/taskflow-under-test?style=flat-square&labelColor=0d1117&color=1f6feb) |
| [accessibility-testing](https://github.com/VincentJerico/accessibility-testing) | ![CI](https://github.com/VincentJerico/accessibility-testing/actions/workflows/ci.yml/badge.svg) | ![Stars](https://img.shields.io/github/stars/VincentJerico/accessibility-testing?style=flat-square&labelColor=0d1117&color=1f6feb) |
| [security-testing](https://github.com/VincentJerico/security-testing) | ![CI](https://github.com/VincentJerico/security-testing/actions/workflows/ci.yml/badge.svg) | ![Stars](https://img.shields.io/github/stars/VincentJerico/security-testing?style=flat-square&labelColor=0d1117&color=1f6feb) |

## [ CONTRIBUTIONS ]

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/VincentJerico/VincentJerico/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/VincentJerico/VincentJerico/output/github-snake.svg" />
    <img alt="snake eating my contribution graph" src="https://raw.githubusercontent.com/VincentJerico/VincentJerico/output/github-snake.svg" />
  </picture>
</p>

## [ CONNECT ]

[![Email](https://img.shields.io/badge/Email-1f6feb?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vincentjericoalcuran@gmail.com)
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-1f6feb?style=for-the-badge&logo=github&logoColor=white)](https://github.com/VincentJerico)

---

```
vincentjerico@github ~ $ ▮
```
