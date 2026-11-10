# Public project catalog

This catalog links to the original public repositories and describes observable work in each. The selection shows range; it is not a ranking of quality or maturity.

## Featured projects

- [testes-e2e-com-cypress](https://github.com/AnaCarolinaSantos-qa/testes-e2e-com-cypress) — Cypress scenarios for sign-up, login, sessions, and CRUD. Sign-up uses a local API simulation instead of Mailosaur; [PR #1 CI passed](https://github.com/AnaCarolinaSantos-qa/testes-e2e-com-cypress/actions/runs/42867357417). The remaining scenarios use the project's demo application.
- [Testes_API_NodeJS](https://github.com/AnaCarolinaSantos-qa/Testes_API_NodeJS) — API testing exercises with Node.js, Mocha, Chai, and Supertest; [PR #2 CI passed](https://github.com/AnaCarolinaSantos-qa/Testes_API_NodeJS/actions/runs/42862795387).
- [zapLink](https://github.com/AnaCarolinaSantos-qa/zapLink) — a virtual service-booking app using Vue.js, Node.js, and MongoDB, with API tests run in CI against an ephemeral MongoDB service; [PR #1 CI passed](https://github.com/AnaCarolinaSantos-qa/zapLink/actions/runs/42864983095).

## Other public examples

- [CypressCucumber](https://github.com/AnaCarolinaSantos-qa/CypressCucumber) — Cypress/Cucumber scenario for a local form; [PR #1 CI passed](https://github.com/AnaCarolinaSantos-qa/CypressCucumber/actions/runs/42867393049).
- [cypress_boilerplate](https://github.com/AnaCarolinaSantos-qa/cypress_boilerplate) — Cypress boilerplate with an updated workflow; [PR #1 CI passed](https://github.com/AnaCarolinaSantos-qa/cypress_boilerplate/actions/runs/42861994146).
- [API_Restful_Sinatra](https://github.com/AnaCarolinaSantos-qa/API_Restful_Sinatra) — Sinatra/RSpec API tested with an ephemeral MongoDB service; [PR #1 CI passed](https://github.com/AnaCarolinaSantos-qa/API_Restful_Sinatra/actions/runs/42869479563).
- [robot_framework_qa_starter](https://github.com/AnaCarolinaSantos-qa/robot_framework_qa_starter) — an experimental automation lab. Its workflow has API, UI, mobile, accessibility, and performance jobs, and [PR #37 passed](https://github.com/AnaCarolinaSantos-qa/robot_framework_qa_starter/actions/runs/42866157339). This does not establish broad functional coverage: its current API and UI tests are demonstrations that only log messages.
- [rocklov](https://github.com/AnaCarolinaSantos-qa/rocklov) — course project with API and web scenarios in Ruby/RSpec and Cucumber; execution depends on external Jenkins and Docker services.

## Recent public maintenance

In November 2026, ten maintenance PRs were merged across public repositories. Seven CI checks associated with these PRs passed. The other three PRs updated documentation only and do not have an executable suite in GitHub Actions.

### CI, automation, and configuration

- [cypress_boilerplate — PR #1](https://github.com/AnaCarolinaSantos-qa/cypress_boilerplate/pull/1) · [CI passed](https://github.com/AnaCarolinaSantos-qa/cypress_boilerplate/actions/runs/42861994146): current Actions, Node.js 20, reproducible installation, and pull request runs.
- [Testes_API_NodeJS — PR #2](https://github.com/AnaCarolinaSantos-qa/Testes_API_NodeJS/pull/2) · [CI passed](https://github.com/AnaCarolinaSantos-qa/Testes_API_NodeJS/actions/runs/42862795387): lockfile-based installation, Node.js 20, and a less volatile assertion against the demo API.
- [CypressCucumber — PR #1](https://github.com/AnaCarolinaSantos-qa/CypressCucumber/pull/1) · [CI passed](https://github.com/AnaCarolinaSantos-qa/CypressCucumber/actions/runs/42867393049): local form and server to remove dependency on an unavailable remote site.
- [testes-e2e-com-cypress — PR #1](https://github.com/AnaCarolinaSantos-qa/testes-e2e-com-cypress/pull/1) · [CI passed](https://github.com/AnaCarolinaSantos-qa/testes-e2e-com-cypress/actions/runs/42867357417): sign-up no longer requires Mailosaur; the API response is simulated locally and unused secret variables were removed.
- [zapLink — PR #1](https://github.com/AnaCarolinaSantos-qa/zapLink/pull/1) · [CI passed](https://github.com/AnaCarolinaSantos-qa/zapLink/actions/runs/42864983095): MongoDB URI configured through the environment and API tests with an ephemeral database.
- [API_Restful_Sinatra — PR #1](https://github.com/AnaCarolinaSantos-qa/API_Restful_Sinatra/pull/1) · [RSpec CI passed](https://github.com/AnaCarolinaSantos-qa/API_Restful_Sinatra/actions/runs/42869479563): run the API through Rack and test against ephemeral MongoDB.
- [robot_framework_qa_starter — PR #37](https://github.com/AnaCarolinaSantos-qa/robot_framework_qa_starter/pull/37) · [workflow passed](https://github.com/AnaCarolinaSantos-qa/robot_framework_qa_starter/actions/runs/42866157339): linked the badge to the actual workflow and aligned README paths with the repository.

### Documentation and execution limits

- [NinjaWeek — PR #1](https://github.com/AnaCarolinaSantos-qa/NinjaWeek/pull/1): README aligned with the versioned content; the repository has no executable test suite.
- [RobotFrameworkWeek — PR #1](https://github.com/AnaCarolinaSantos-qa/RobotFrameworkWeek/pull/1): README aligned with the existing files; the repository has no executable test suite.
- [rocklov — PR #1](https://github.com/AnaCarolinaSantos-qa/rocklov/pull/1): Jenkins service prerequisites documented, including the warning that API suite setup deletes the configured database. This setup has no safe standalone GitHub CI.

## Additional public repositories reviewed

[NinjaWeek](https://github.com/AnaCarolinaSantos-qa/NinjaWeek) and [RobotFrameworkWeek](https://github.com/AnaCarolinaSantos-qa/RobotFrameworkWeek) are course examples made up of documentation only. They remain available in their original repositories.
