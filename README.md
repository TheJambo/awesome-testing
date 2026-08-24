![](https://github.com/TheJambo/awesome-testing/blob/master/AwesomeTesting.jpg?raw=true)




# Awesome Testing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Dead link checker](https://github.com/TheJambo/awesome-testing/actions/workflows/404-links.yml/badge.svg)](https://github.com/TheJambo/awesome-testing/actions/workflows/404-links.yml)
> A curated list of testing software, extensions and resources




## Foreword
This is intended to be a curation of resources for the new among the software testing community. It is not tailored to a specific area (Usability/Performance) or role (Automation/Management). The idea is that you could hand this list to a CS graduate and it would greatly improve their testing skills, efficiency and overall breadth of knowledge. Note that this is for all areas of software testing after the code in question is written (no unit tests/static analysis!).




Finally, I'm sure everyone who reads this list has one thing they want to add. Please read the [How to Contribute](https://github.com/TheJambo/awesome-testing/blob/master/CONTRIBUTING.md) page and add to the list. :)




## Contents




- [Software](#software)
- [Books](#books)
- [Training](#training-includes-developer-training-for-automation-testers)
- [Blogs](#blogs)
- [Newsletters](#newsletters)
- [Suggested Awesome Lists](#suggested-awesome-lists)
- [QA & Testing Road Map](#qa-and-testing-road-map)
- [Others](#others)
- [Contributing](#contributing)
- [Code of Conduct](#code-of-conduct)
- [License](#license)








## Software




### API Testing
- [Bruno](https://github.com/usebruno/bruno) - Open-source API client for exploring and testing APIs.
- [API Status Check](https://apistatuscheck.com) - Real-time status monitoring dashboard for 188+ third-party APIs (OpenAI, Stripe, AWS, GitHub, etc.) with response time tracking and free alert tiers.
- [Polarity](https://www.polarity.so) - The First AI QA Engineer that does full E2E, API, UI testing. Understands your entire codebase and ensures all relavent tests are conducted with our long running agent setup.
- [BitDive](https://bitdive.io/) - Zero-code API testing platform for Java/Kotlin. Captures deep runtime context (HTTP, SQL, methods), auto-generates mocks from real traffic, and enables Live Context Replay for E2E testing and debugging.
- [CORS Tester](https://cors-error.dev/cors-tester/) - A tool for developers and API testers to check if an API is CORS-enabled for a given domain and identify gaps.
- [HttpMaster](https://www.httpmaster.net) - Professional software tool for HTTP testing and debugging.
- [Keploy](https://github.com/keploy/keploy) - API Testing Platform that automatically generates unit test cases along with dependency mocks.
- [RestQA](https://github.com/restqa/restqa) - REST API testing framework based on Gherkin.
- [SpecTest](https://github.com/justiceo/spectest) - Truly declarative API testing framework in Js, or plain JSON.
- [Tests Coverage Tool](https://github.com/Nikita-Filonov/tests-coverage-tool) - Ultimate tool to measure gRPC service coverage from tests.
- [Swagger Coverage Tool](https://github.com/Nikita-Filonov/swagger-coverage-tool) - The Swagger Coverage Tool is designed to measure API test coverage based on Swagger documentation. It provides automated tracking and reporting of test coverage for APIs, helping ensure that your endpoints and services are well-tested.
- [Webhook Debugger & Logger](https://apify.com/ar27111994/webhook-debugger-logger) - Enterprise-grade tool for testing, debugging, and logging incoming webhooks in real-time.
- [Webhook Debugger](https://github.com/brancogao/webhook-debugger) - Open-source, self-hosted webhook inspector with signature verification support.
- [Spiderhash](https://spiderhash.io/) - Webhook debugging and request inspection tool for testing callback payloads, headers, and delivery behavior.
- [KushoAI](https://kusho.ai/) - AI-native platform for API contract testing, end-to-end testing, UI testing, and continuous security scanning, with self-healing tests that automatically adapt to code changes in CI/CD.
- [postman2pytest](https://github.com/golikovichev/postman2pytest) - Convert a Postman Collection v2.1 JSON file into a ready-to-run pytest test suite.
- [funapi] (https://funapi.dev) - A free mock REST API service designed for practicing API testing, automation, and integration with realistic scenarios and endpoints.
- [JSON Diff](https://alltoolsverse.com/tools/json-diff/) - Browser-based tool for comparing two JSON values and listing added, removed, and changed values by path.


### Security Testing
- [BeEF](http://beefproject.com/) - Manipulate the browser by exploiting any XSS vulnerabilities you find.
- [OWASP ZAP](https://github.com/zaproxy/zaproxy) - Intercepting proxy for HTTP traffic manipulation, security scanning, and exploitation.
- [BurpSuite](https://portswigger.net/burp/communitydownload) - Intercept API and Reply with changes in realtime with according api manipulations.
- [Nuclei Scanner](https://github.com/projectdiscovery/nuclei) - nuclie is automated scanner for common vulnerbilty finding on site.




### AI & LLM Testing
- [promptfoo](https://github.com/promptfoo/promptfoo) - Open-source framework for testing and red teaming LLM applications. Compare prompts, test RAG architectures, run multi-turn adversarial attacks, and catch security vulnerabilities with CI/CD integration.
- [Tenro](https://github.com/tenro-ai/tenro-python) - Open-source testing framework for AI agents. Simulate LLM and tool calls to test edge cases, failure paths, and agent logic without live API calls.
- [voicetest](https://github.com/voicetestdev/voicetest) - Open-source test harness for voice AI agents supporting Retell, VAPI, LiveKit, and Bland with autonomous simulations and LLM-based evaluation.
- [AgentSkeptic](https://github.com/jwekavanagh/agentskeptic) - Verifies AI/agent workflows by checking database state after execution, comparing expected vs observed outcomes with read-only SQL.
- [Evaliphy](https://github.com/evaliphy/evaliphy) - Test your AI system end-to-end with Evaliphy. It uses a Playwright-style testing approach and generates HTML reports.
- [QASkills.sh](https://qaskills.sh) - Open registry of 400+ QA and testing skills (Playwright, API, LLM evaluation, accessibility, performance) that AI coding agents install and follow via the qaskills CLI. Works with Claude Code, Cursor, and 30+ other agents.
- [nika](https://github.com/supernovae-st/nika) - Workflow engine for AI with testing built in: `nika test` pins a workflow's offline behavior as a golden snapshot (deterministic mock provider, zero keys) and replays it in CI; every run also leaves a hash-chained trace for post-hoc verification.
