# QA & Test Automation

**For engineers who don't trust their test suite: catch real bugs and kill the flake.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Reach for this when your suite is green but you don't believe it — high coverage that misses the bug, tests that flake in CI, mocks that pass while production breaks. It takes a suite from "runs" to "trustworthy": prove which gaps actually matter, root-cause flakiness instead of retrying around it, and use mutation testing to expose assertions that verify nothing. Pull it in before a release cut or when a passing build still ships regressions.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/qa-test-automation](https://skillme.dev/pack/qa-test-automation) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/qa-test-automation`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Flaky Test Detangler](skills/flaky-test-detangler/SKILL.md)** — Root-causes intermittently failing tests and eliminates the hidden dependency at its source instead of retrying around it.
- **[Coverage Gap Finder](skills/coverage-gap-finder/SKILL.md)** — Produces a risk-ranked list of untested critical paths and branches, with the specific missing cases and the smallest test that buys the most safety.
- **[Test Data Builder](skills/test-data-builder/SKILL.md)** — Builds realistic domain fixtures, factories, and edge-case datasets with the builder pattern and valid defaults.
- **[Contract Test Writer](skills/contract-test-writer/SKILL.md)** — Write consumer-driven contract tests at service and API boundaries so an incompatible change fails a build instead of breaking integrations silently in production.
- **[E2E Scenario Author](skills/e2e-scenario-author/SKILL.md)** — Converts an acceptance criterion or user story into one maintainable Playwright or Cypress end-to-end test that reads like the journey it covers.
- **[Mock Stub Designer](skills/mock-stub-designer/SKILL.md)** — Designs the minimal set of test doubles for a unit or integration test and decides, per dependency, what to fake versus exercise for real.
- **[Mutation Test Runner](skills/mutation-test-runner/SKILL.md)** — Runs mutation testing on already-covered code and turns each surviving mutant into a specific missing assertion, exposing tests that execute code but verify nothing.
- **[Playwright Testing](skills/playwright-testing/SKILL.md)** — Reliable end-to-end browser tests with resilient selectors and no flaky waits.
- **[TDD Expert](skills/tdd-expert/SKILL.md)** — Enforces Red-Green-Refactor discipline: write the failing test first, then the minimum code to pass it.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
