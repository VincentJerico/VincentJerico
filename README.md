# Hi, I'm VJ

I'm a QA engineer at BossLabs.AI, where I test client business platforms before they go live. On
GitHub I'm building the repos below: one per kind of testing, each run against a real target, each
with its own CI and a write-up of what I found. I want to move into an SDET role next,
and later into security and cloud work.

I have a BSc in Information Technology and I'm based in Cavite, Philippines.

## A few things I've found

On TaskFlow, a small app I wrote so I'd have something of my own to break, 60 logins a second made an
unrelated 2 ms request take 12 seconds. Password hashing was synchronous, so every login blocked Node's
only thread. I switched it to async `scrypt` and added rate limiting to login and sign-up.
([write-up](https://github.com/VincentJerico/performance-testing/blob/main/docs/FINDINGS.md#perf-001-login-traffic-stalls-every-other-request),
[fix](https://github.com/VincentJerico/taskflow-under-test/pull/18))

On SauceDemo, axe-core reported no WCAG violations. Going through the site with only a keyboard found
7, including a cart you can't reach without a mouse, which means you can't check out.
([audit](https://github.com/VincentJerico/accessibility-testing/blob/main/docs/FINDINGS.md))

Against a local copy of OWASP Juice Shop I wrote up 8 findings that map to the OWASP Top 10. Each
check in that repo has a test that proves it can fail, so a passing run actually means something.
([report](https://github.com/VincentJerico/security-testing/blob/main/docs/FINDINGS.md))

## Contributions

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/VincentJerico/VincentJerico/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/VincentJerico/VincentJerico/output/github-snake.svg" />
    <img alt="snake eating my contribution graph" src="https://raw.githubusercontent.com/VincentJerico/VincentJerico/output/github-snake.svg" />
  </picture>
</p>

## Projects

- [qa-engineering-journey](https://github.com/VincentJerico/qa-engineering-journey) is where I
  started: manual test plans, test design, API testing, UI automation, SQL, k6, security and AI
  evals, each tried on a live site.
- [playwright-framework-template](https://github.com/VincentJerico/playwright-framework-template)
  is the setup I'd start a new UI test suite from. It has fixtures, page objects, a saved login and
  CI on Chromium, Firefox and WebKit.
- [api-testing-framework](https://github.com/VincentJerico/api-testing-framework) runs API tests on
  Playwright's request API, with Zod schemas checking every response. Each test deletes the data it
  creates.
- [taskflow-under-test](https://github.com/VincentJerico/taskflow-under-test) is the task app
  mentioned above. It has unit, API and E2E tests, plus a few bugs I planted to make sure the tests
  catch them.
- [accessibility-testing](https://github.com/VincentJerico/accessibility-testing) is the SauceDemo
  audit.
- [security-testing](https://github.com/VincentJerico/security-testing) runs ZAP, Trivy and header
  and cookie checks against Juice Shop in Docker.
- [performance-testing](https://github.com/VincentJerico/performance-testing) is the k6 suite for
  TaskFlow. Smoke and load tests run on every push and fail the build if an endpoint gets too slow.
  The heavier tests run every night.

All seven run in GitHub Actions.

## Tools

Mostly Playwright and TypeScript. I also use k6, axe-core, Zod, Vitest, Supertest, Postman, SQL,
OWASP ZAP, Trivy, Docker and GitHub Actions, and I'm learning AWS.

## Contact

The easiest way to reach me is email: [vincentjericoalcuran@gmail.com](mailto:vincentjericoalcuran@gmail.com).
