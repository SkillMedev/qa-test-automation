# QA & Test Automation

**Build a test suite that actually catches bugs — and stops flaking.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Beyond unit tests and TDD: detangle flaky tests at the root, find risk-weighted coverage gaps, build clean fixtures and factories, write consumer-driven contract tests, author maintainable Playwright/Cypress E2E, design mocks without over-mocking, and use mutation testing to expose assertions that verify nothing.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/qa-test-automation](https://skillme.dev/pack/qa-test-automation) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add aouellets/qa-test-automation`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Flaky Test Detangler](skills/flaky-test-detangler/SKILL.md)** — Diagnoses the root cause of intermittently failing tests and fixes them at the source instead of retrying.
- **[Coverage Gap Finder](skills/coverage-gap-finder/SKILL.md)** — Identifies untested critical paths and branches and prioritizes them by risk rather than chasing a line-coverage percentage.
- **[Test Data Builder](skills/test-data-builder/SKILL.md)** — Generates realistic fixtures, factories, and edge-case datasets using the builder pattern while avoiding shared mutable fixtures.
- **[Contract Test Writer](skills/contract-test-writer/SKILL.md)** — Writes consumer-driven contract tests for service and API boundaries so integrations break loudly at build time instead of silently in production.
- **[E2E Scenario Author](skills/e2e-scenario-author/SKILL.md)** — Converts an acceptance criterion into a maintainable Playwright or Cypress end-to-end test using role-based selectors and the page-object or fixture pattern.
- **[Mock Stub Designer](skills/mock-stub-designer/SKILL.md)** — Sets up the right mocks, stubs, and fakes for external dependencies without over-mocking, and decides what to fake versus use for real.
- **[Mutation Test Runner](skills/mutation-test-runner/SKILL.md)** — Uses mutation testing to expose tests that execute code but assert nothing, and interprets surviving mutants into concrete missing assertions.
- **[Playwright Testing](skills/playwright-testing/SKILL.md)** — Reliable end-to-end browser tests with resilient selectors and no flaky waits.
- **[TDD Expert](skills/tdd-expert/SKILL.md)** — Enforces Red-Green-Refactor discipline: write the failing test first, then the minimum code to pass it.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
