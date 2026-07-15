# Quality Assurance Architect

_Test Automation Architect · Agentic Quality Assurance_ <br>

With **7+ years** across test automation, QA leadership and software delivery, I architect quality assurance for organisations — the SDLC, the strategy, the frameworks and the teams. My focus is raising quality while cutting the cost of recurring engineering work: test management, test automation architecture across every platform, and — for the past year — **designing and building autonomous QA agents for fully agentic quality assurance**, where a single install turns an AI agent loose to discover an application, author its test suite, expand coverage, hunt bugs, triage failures and report to stakeholders. I design the architecture, build the frameworks and agents, and grow the culture that delivers it.

## CORE EXPERTISE

- **QA Strategy & Leadership** — Test Maturity Models, SDLC design, QA team formation, performance frameworks, supplier governance.
- **Test Automation Architecture** — Web, mobile (iOS / Android), desktop, API, database and email, unified under single cross-platform frameworks.
- **AI-Assisted Quality Engineering** — Staged autonomous agentic QA pipeline (journey mapping → authoring → coverage expansion → bug discovery → failure diagnosis), adversarial / red-team AI testing, and model-agnostic LLM orchestration.
- **Open-Source Library Design** — Published multiple Maven Central and npm libraries used in production testing ecosystems.
- **CI/CD & DevOps for QA** — Azure DevOps, GitHub Actions, GitLab CI, Jenkins, custom parallelisation, Docker, Allure / Calliope / Slack reporting integrations.
- **Languages & Stacks** — Java, TypeScript / Node, Python, Swift. Spring Boot, Playwright, Selenium, Appium, Cucumber, Retrofit, React, Vue, Next.js.

## WORK EXPERIENCE

**Quality Assurance Architect & Managing Consultant** ***@[spriteCloud](https://www.spritecloud.com)*** _(01.01.2024 - present)_ <br>
SpriteCloud is a consultancy providing software testing services & test results dashboards.
- **Architect clients' QA landscapes end-to-end**: assess practices through **Test Maturity Models** (TMM), design Software Development Lifecycle (SDLC) models that embed an effective quality assurance discipline, and size the QA capacity each work stream needs.
- **Architected a desktop-to-database end-to-end test automation solution** that secured a major client engagement with **Ahold Delhaize**.
- **BlueHero** (AI-powered applicant tracking system — Next.js, NestJS, Supabase):
  - Designed and built a **Playwright + TypeScript E2E suite of 186+ tests across 16 feature areas**, reaching ~85% functional coverage of a bilingual (Dutch/English) staff portal within hours.
  - Pioneered an **AI-vs-AI testing methodology**: an LLM simulates real employers through five stress-test personas to drive the product's AI chat assistant, and an **LLM-as-judge** verifies the published job against every fact the simulated employer stated.
  - Authored an **adversarial AI guardrails suite** running categorised attacks against the assistant, with structured LLM verdicts covering pass/fail, severity, violations and recommendations.
  - Designed a two-stage GitHub Actions pipeline (core E2E in ~2 minutes, AI run in ~25 minutes) that auto-posts transcripts and verdicts to pull requests.
- **Farmedvisie / Medicheck** (two-portal medication-administration platform, healthcare):
  - Delivered a **durable E2E suite covering 34 user journeys — 528 passing tests, 0 failing** across both portals, written against an intent-level API so it survives UI re-renders, in a run of ~18 minutes against the live acceptance environment.
  - Ran an **adversarial security audit surfacing ~470 findings (36 critical, 71 high)** with live reproductions — including a cross-tenant IDOR family exposing patient records and Dutch-regulated BSN identifiers across organisations, and a Spring Boot Actuator account-takeover chain.
  - Engineered a **regression-sentinel layer of 211 tests** — each documents a confirmed bug and turns green automatically the moment its backend fix ships, with no manual re-test.
- **[MR MARVIS](https://www.mrmarvis.com)**: designed and rolled out a **new SDLC** aligning development, QA and release practices, delivered an easy-to-scale Playwright solution for developers, and built an **AI Playwright Test Writer** generating ready-to-run test scenarios from user journeys gathered in a spreadsheet.
- Built performance measurement frameworks and KPIs for my team of consultants; trained & mentored QA Engineers in software development and test automation.
- Drive innovation as the **Guild Lead of Innovation**:
  - Designed and delivered a **multi-model AI QA agent** combining vision models, LLMs and structured prompting for autonomous test scenario generation and test maintenance.
  - Led the design of **AI-native test authoring workflows** adopted internally by consultants, bringing LLM-assisted test generation into day-to-day delivery.
  - Architected an easy-to-deploy **CV solution** modernising consultancy CV practices (the system rendering this document).
<br><br>

**Quality Assurance Solution Owner** ***@[citizenM hotels](https://www.citizenm.com/company/overview)*** _(01.03.2022 - 31.01.2026)_ <br>
citizenM is a Netherlands-based hotel developer, investor, and hotel chain.
- ***Architect-scope ownership of quality across the organisation:*** audited the entirety of citizenM's software development practices to produce a five-stage **Test Maturity Model**, then designed the centralised QA approach it called for and managed the transition.
- ***Founded the QA team*** to raise quality standards across citizenM's product lineup:
  - Hired, trained and managed engineers providing QA to several product teams, reallocating resources as test workload shifted.
  - Ran an agile work environment with a continuous performance feedback cycle to ensure career development.
- ***Redesigned the software development lifecycle*** to enable a solid test strategy:
  - Analysed the existing SDLC model, designed a replacement compensating for its shortcomings, and ***guided citizenM & its suppliers*** through the migration.
  - Enabled a test architecture separating development, test and acceptance environments while integrating test automation into deployment pipelines.
- ***Led Quality Assurance*** through citizenM's backend migration.
  - Owned strategy, budget planning and hiring.
  - Designed & implemented a ***performance test suite*** (JMeter, Octaperf).
  - Designed a ***data migration audit*** and defined the ***UAT strategy*** between citizenM & its suppliers.
- Architected ***clean, efficient, scalable & unified*** test automation solutions for various teams.
  - API test automation for the entirety of citizenM's backend services & web UI test automation for citizenM's website.
  - Enabled cross-layer verification between frontends, backends, databases, customer emails and the analytics layer.
  - Established continuous integration on ***Azure DevOps***, with a custom script enabling **test parallelisation** at the **DevOps** level.
  - ***Slack integrations:*** live pipeline monitoring, a results-posting bot with slash-command remote triggers, and Calliope.pro → Slack reporting.
  - ***Established a single test automation framework that simultaneously tested frontends, middleware, emails, analytics layer and the database against each other, enabling true E2E test automation*** — scaled with the QA team I founded to cover **5000+ test steps**.
<br><br>

**Senior Test Automation Engineer** ***@[spriteCloud](https://www.spritecloud.com)*** _(01.12.2021 - 01.01.2024)_ <br>
SpriteCloud is a consultancy providing software testing services & test results dashboards.
- Delivered client engagements across ***GitLab CI***, ***Knapsack*** parallelisation (Cypress, Jest, RSpec), automated vulnerability & security testing (***ZAProxy***, ***Burp Suite***), **Cypress** & **Jest** automation, and automated bug reporting via ***Jira*** & ***Trello*** integrations.
- Published a ***[Mobile UI Test Automation Template](https://github.com/Umutayb/Mobile-Automation-Sample)*** utilising my mobile automation library ***[Mobileib](https://github.com/Umutayb/Mobileib)***, built on **Java & Appium**, capable of ***parallel test execution*** (multithreaded and/or via BrowserStack).
- Published an ***[API Automation Template](https://github.com/Umutayb/Api-Automation-Sample)*** utilising my API automation library ***[Api Assured](https://github.com/Umutayb/Api-Assured)***, built on ***Java***, ***Retrofit2*** & ***OkHttp3***, capable of ***parallel test execution***, ***request interception*** & ***advanced header management***.
- Improved upon the ***[Web UI Automation Template](https://github.com/Umutayb/Web-Automation-Sample-Cucumber)*** & the web UI automation library ***[Pickleib](https://github.com/Umutayb/Pickleib)***.
- Improved test result monitoring using Calliope.pro & Allure for more insightful reporting.
<br><br>

**Software QA Automation Engineer** ***@[Getir](https://www.linkedin.com/company/getir/)*** _(02.06.2021 - 01.12.2021)_ <br>
Getir is a technology company that provides solutions for the delivery of goods in urban areas.
- Delivered ***web automation***, ***backend automation*** & ***backend development*** with ***JPA*** and ***Spring Boot***: testing infrastructure for developers & testers, Dockerised virtual courier services, easily triggered regression suites and backend services for other teams — including a **candidate-assessment backend built from the ground up**, used by Getir to evaluate engineering candidates.
- Single-handedly programmed the entire web UI regression suite for one of Getir's sub-brands, with a scaling adaptation of the ***Abstract Factory*** pattern enabling the project to support multiple sub-brand domains.
- Set up CI jobs and used Portainer slaves to pick up available jobs from Jenkins.
- Prepared Quickstart libraries combining BDD (**Cucumber & Gauge**) and **Page Object Model**, allowing entire automation frameworks to be bootstrapped within minutes.
- Implemented parallel execution as standard on every project.
- Authored an experimental automation framework that automatically acquires all elements & attributes with auto-generated xPaths into a project JSON file — interpreted by the framework — allowing automation without any manual page inspection (the conceptual ancestor of my current JSON-repository-based frameworks).
- Helped over **50 QA engineers** at Getir **learn test automation** through a three-week bootcamp, complete with examinations and Getir certification. Sessions were captured and are reused for ongoing onboarding.
<br><br>

**Software Test Automation Engineer** ***@[Pixery](https://www.pixerylabs.com)*** _(15.07.2020 - 02.06.2021)_ <br>
Pixery develops next-generation mobile applications for content creators. Worked on both [**Funimate**](https://www.pixerylabs.com) (a social video editing platform used by millions of active users daily) & [**Impresso**](https://www.pixerylabs.com) (an all-in-one video editing tool for influencers and businesses).
- Ensured end-product quality through comprehensive tests with creative test cases for each functional task, and integration tests before each release.
- Provided a flexible automation framework (***Java***, ***TestNG***, ***Cucumber***, ***Selenium***, ***Appium***, ***Jenkins CI***) simultaneously usable across several mobile & web projects and API tests, with BDD scenarios writable by non-technical team members.
- Developed Swift-based mobile test tools used to measure the accuracy of the video editing engines.
<br><br>

**Software QA Engineer** ***@[JustSnap](https://justsnap.co)*** _(04.10.2018 – 01.07.2020)_ <br>
Justsnap provides campaign solutions based on its in-house receipt-scanning ML technology.
- Participated in development, QA and BA processes of campaign projects for P&G, Philips and Pepsi.
- Responsible for quality assurance activities across **17+ campaign projects**.
- Worked on cross-platform mobile applications; explored mobile automation with **Selenium** & **Katalon Studio**.
- Created test scenarios, performed sanity and regression tests.
- Implemented flexible web UI test automation solutions that were easy to set up, keeping pace with fast delivery schedules.
<br><br>

## PROJECTS & OPEN SOURCE

Programming is my passion — I build reusable modules and publish them as open source under the **Civitas Cerebrum** ecosystem (npm, `@civitas-cerebrum/*`): an AI-native test automation stack that separates selectors from test logic, unifies execution across web / mobile / desktop, and gives LLM assistants the structured primitives they need to author reliable tests. It is the engine behind my client QA deliveries (BlueHero, Farmedvisie/Medicheck, MR MARVIS). Selected projects:

- **[Achilles](https://civitas-cerebrum.github.io/achilles/)** — Autonomous quality assurance, shipped as a single npm install. One plain-English sentence — *"complete E2E test automation of example.com"* — and the agent owns the whole lifecycle: scaffold, crawl, journey-map, compose coverage, run adversarial bug-hunts, and produce a stakeholder deck, with no babysitting. Its distinguishing work is the **harness engineering** that makes an LLM agent trustworthy on real delivery: [![npm](https://img.shields.io/npm/v/@civitas-cerebrum/achilles?color=brightgreen&label=%40civitas-cerebrum%2Fachilles)](https://www.npmjs.com/package/@civitas-cerebrum/achilles)
  - A **hook-enforced state machine** (30+ hooks that self-register in the agent runtime on install) gates every phase, pass and cycle transition — the agent cannot skip, shortcut or renegotiate scope; it either completes each phase or surfaces a blocker for human triage.
  - **Tamper-evident, hash-chained ledgers** plus self-protection guards stop the agent from editing the harness or forging its own progress state.
  - **Schema-validated subagent contracts** (JSON Schema) — every dispatched agent must return structured, validated output before the pipeline advances, with adversarial workflow-reviewer gates and attestation before any phase closes.
  - An **8-step selector-development guardrail** safely injects test attributes using AST-diff and visual-diff verification across React / Vue / Svelte, reverting on any structural change.
  - **Public-package contamination scanning** keeps internal IP out of the published build; the harness itself is covered by **60+ hook tests**.
- **[sql-client](https://github.com/civitas-cerebrum/sql-client)** — Lightweight **multi-engine** SQL client (PostgreSQL, MySQL/MariaDB, SQLite, SQL Server, Oracle) with one API, a fluent query builder, typed results and always-parametrised queries — the data-layer oracle behind the Steps API. [![npm](https://img.shields.io/npm/v/@civitas-cerebrum/sql-client?color=brightgreen&label=%40civitas-cerebrum%2Fsql-client)](https://www.npmjs.com/package/@civitas-cerebrum/sql-client)
- **[test-coverage](https://github.com/civitas-cerebrum/test-coverage)** — Static-analysis tool (TypeScript AST) enforcing **100% API coverage** in test suites, with CI-friendly reporters. [![npm](https://img.shields.io/npm/v/@civitas-cerebrum/test-coverage?color=brightgreen&label=%40civitas-cerebrum%2Ftest-coverage)](https://www.npmjs.com/package/@civitas-cerebrum/test-coverage)
- **[email-client](https://github.com/civitas-cerebrum/email-client)** — Zero-dependency TypeScript SMTP/IMAP client purpose-built for E2E flows (signup → verification → click-through). [![npm](https://img.shields.io/npm/v/@civitas-cerebrum/email-client?color=brightgreen&label=%40civitas-cerebrum%2Femail-client)](https://www.npmjs.com/package/@civitas-cerebrum/email-client)
- **[Pickleib](https://github.com/Umutayb/pickleib)** — Utility library for Selenium WebDriver automation: driver setup, a clean interaction API, POM support, email testing and database connections. [![Maven Central](https://img.shields.io/maven-central/v/io.github.umutayb/Pickleib?color=brightgreen&label=pickleib)](https://mvnrepository.com/artifact/io.github.umutayb/pickleib/latest)
- **[Wasapi](https://github.com/Umutayb/wasapi)** — Lightweight Java library simplifying HTTP service generation and API calls with Retrofit — centralised configuration, no boilerplate. [![Maven Central](https://img.shields.io/maven-central/v/io.github.umutayb/wasapi?color=brightgreen&label=wasapi)](https://mvnrepository.com/artifact/io.github.umutayb/wasapi/latest)
- ***Napoleon*** — Java-based autonomous web agent: Selenium control through Pickleib, vision-based UI understanding and LLM decision-making, with a dedicated **Nexus** reasoning core — perceive → classify → decide → validate → act, fully in Java.
- ***EMTP (Expert Model Training Pipeline)*** — Python pipeline producing training datasets for domain-expert AI models: modular acquisition → enrichment → Q&A-pair generation.
- **[Easy Secret Santa 🎅](https://github.com/Umutayb/secret-santa)** — Java app automating Secret Santa gift exchanges: pairs participants and sends personalised emails via SMTP. Built for my team, now used by multiple organisations.

## PRODUCT & FULL-STACK PROJECTS

- **BookHive** — A production-grade full-stack bookstore (React 18, Spring Boot 3, MongoDB, Docker Compose) intentionally designed as an automation-friendly reference app: stable `data-testid` attributes, deterministic `/api/seed` and `/api/reset` endpoints, JWT + HttpOnly-cookie dual auth, and a real cart/order flow used as a canonical target for the Civitas Cerebrum ecosystem.
- **Vue / Android / iOS Test Apps** — A family of multi-platform reference applications (Vue 3 playground, native Android, native iOS) used as public testing sandboxes for validating cross-platform automation frameworks.
- **Food Planner** — Lightweight personal web app exploring productivity and lifestyle workflows.

## EDUCATION

**Istanbul Technical University** — Geological Engineering
