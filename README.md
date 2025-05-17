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
- [CORS Tester](https://cors-error.dev/cors-tester/) - A tool for developers and API testers to check if an API is CORS-enabled for a given domain and identify gaps.
- [HttpMaster](https://www.httpmaster.net) - Professional software tool for HTTP testing and debugging.
- [Keploy](https://github.com/keploy/keploy) - API Testing Platform that automatically generates unit test cases along with dependency mocks.
- [RestQA](https://github.com/restqa/restqa) - REST API testing framework based on Gherkin.
- [Zato API Test](https://zato.io/en/docs/3.2/api-testing/index.html) - API testing in plain English with extendable Python implementation.
- [Tests Coverage Tool](https://github.com/Nikita-Filonov/tests-coverage-tool) - Ultimate tool to measure gRPC service coverage from tests.
- [Swagger Coverage Tool](https://github.com/Nikita-Filonov/swagger-coverage-tool) - The Swagger Coverage Tool is designed to measure API test coverage based on Swagger documentation. It provides automated tracking and reporting of test coverage for APIs, helping ensure that your endpoints and services are well-tested.

### Security Testing
- [BeEF](http://beefproject.com/) - Manipulate the browser by exploiting any XSS vulnerabilities you find.
- [OWASP ZAP](https://github.com/zaproxy/zaproxy) - Intercepting proxy for HTTP traffic manipulation, security scanning, and exploitation.

### Service Virtualization
- [Beeceptor](https://beeceptor.com/) - Easy to use no-code mock servers for service virtualization. Rest, SOAP, GraphQL supported. Create an API mock server from OpenAPI Specification or Postman collection.
- [DeepfakeHTTP](https://github.com/xnbox/DeepfakeHTTP) - Web server using HTTP dumps as a response source for API simulation.
- [WireMock](https://github.com/wiremock/wiremock) - Open source HTTP mock engine written in Java. Embed in your test code, run as a standalone process, or deploy via Docker.

### Visual Testing
- [Fluxguard](https://fluxguard.com) - Screenshot pixel and DOM change comparisons.
- [GoodLooks](https://github.com/dashcamio/goodlooks) - AI-powered visual validation for Playwright tests.
- [TestingBot](https://testingbot.com) - Supports automated, manual, and visual testing.
- [recheck-web](https://github.com/retest/recheck-web) - Change comparison tool with Golden Masters and "unbreakable Selenium" tests.
- [wopee.io](https://wopee.io/) - Autonomous visual regression testing platform.

### UI & End-to-End Testing
- [BugBug](https://bugbug.io) - No-code test automation tool for web applications.
- [Courgette](https://courgette-testing.com) - Declarative BDD UI testing with Gherkin.
- [Ferrum](https://github.com/rubycdp/ferrum) - Chrome automation via CDP with a high-level Ruby API.
- [Hyperbrowser](https://hyperbrowser.ai) - Scalable headless browser testing with built-in session recording.
- [Hercules](https://github.com/test-zeus-ai/testzeus-hercules) - Open-source end-to-end testing agent.
- [LambdaTest](https://www.lambdatest.com) - Unified enterprise test execution cloud platform for browser and mobile testing.
- [Octomind](https://github.com/OctoMind-dev) - AI-powered test case discovery and maintenance.
- [playwright-bdd](https://github.com/vitalets/playwright-bdd) - BDD-style Playwright testing.
- [QA Wolf](https://github.com/qawolf/qawolf) - Node.js library for creating browser tests faster.
- [UI Coverage Tool](https://github.com/Nikita-Filonov/ui-coverage-scenario-tool) - UI Coverage Tool is an innovative, no-overhead solution for tracking and visualizing UI test coverage — directly on your actual application, not static snapshots.
- [Zyntra](https://zyntra.app/) – Unlimited e-mail inboxes with API/UI access. Catch OTPs, reset links, and sign-up emails in your test flows.
  
### Test Management
- [Kiwi TCMS](https://github.com/kiwitcms/Kiwi) - Open-source test case management.
- [TestLink](https://github.com/TestLinkOpenSourceTRMS/testlink-code) - Open-source test case management system.
- [Testomatio](https://testomat.io/) - Modern TCMS allowing sync of manual and automated tests.

### Test Data Management
- [Synth](https://github.com/getsynth/synth) - Open-source test data generator.
- [Touca](https://github.com/trytouca/trytouca) - Continuous regression testing for behavioral and performance comparisons.
- [test-each](https://github.com/ehmicky/test-each) - Data-driven testing framework.

### Browser Extensions & Utilities
- [Bug Magnet](https://chrome.google.com/webstore/detail/bug-magnet/efhedldbjahpgjcneebmbolkalbhckfi) - Field-based value suggestions for form testing.
- [Check All](https://chrispederick.com/work/web-developer/) - Provides a "Select All" function where missing.
- [Full Page Screenshot](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl) - Capture full-page screenshots.
- [Form Filler](https://chrome.google.com/webstore/detail/form-filler/bnjjngeaknajbdcgpfkgnonkmififhfo) - Auto-fill large forms with dummy data.
- [ProxySwitcher](https://chrome.google.com/webstore/detail/proxy-switcher-manager/onnfghpihccifgojkpnnncpagjcdbjod) - Easy proxy switching for test/prod environments.
- [Requestly](https://requestly.io/) - A lightweight proxy to intercept and modify network requests.

### Accessibility & Usability Testing
- [Colour Blindness Simulator](https://altreus.github.io/colourblind/) - Simulate different types of color blindness.

### Performance & Load Testing
- [Yslow](http://yslow.org/) - Analyze web page performance based on Yahoo!'s rules.
- [Load Testing Hub Panel](https://github.com/Nikita-Filonov/load-testing-hub-panel) - Ultimate web UI for visualizing load test results

### Web3 & Blockchain Testing
- [Cannon](https://usecannon.com/) - Continuous configuration automation for Ethereum.
- [Dapp.tools](https://dapp.tools/) - Command-line tools and smart contract libraries for Ethereum.
- [Ganache](https://trufflesuite.com/ganache/) - Personal Ethereum blockchain for running tests.
- [Foundry](https://github.com/foundry-rs/foundry) - Fast, modular toolkit for Ethereum development.
- [Hardhat](https://hardhat.org/) - Ethereum development and testing environment.
- [Truffle Suite](https://trufflesuite.com/) - Comprehensive smart contract development suite.
- [Robot Framework Solidity Testing Toolkit](https://github.com/jg8481/Robot-Framework-Solidity-Testing-Toolkit) - Robot Framework integration for Solidity testing.

### Test Automation Frameworks
- [Robot Framework](https://robotframework.org/) - Generic open-source automation framework for testing and RPA.

### Screen Recording & Session Replays
- [Captura](https://github.com/MathewSachin/Captura) - Open-source video recording tool.
- [Replayable](https://replayable.io) - Desktop dashcam for capturing manual testing sessions.

### Mind Mapping & Documentation
- [Xmind](http://www.xmind.net/) - Mind mapping tool for documenting test cases and strategies.


## Books
- [The Scrum Field Guide, Agile advice for your first year and beyond](https://amzn.to/2OERKEm) - Why you might want to move your company to Agile and great practical advice on how to do it.
- [Fifty quick ideas to improve your Tests](https://amzn.to/2AzMUF7) - Great illustrative examples on how to improve tests and why you should do them. Great as evidence for winning arguments!
- [Agile Testing: A Practical Guide](https://amzn.to/2n1K2aG) - A how to guide for those looking to transition to an Agile as a tester and also how the authors work on their Agile teams.
- [Explore It!: Reduce Risk and Increase Confidence with Exploratory Testing](https://amzn.to/2n8axLn) - A very good book on structuring Exploratory Testing and designing tests.
- [The Domain Testing Workbook](https://amzn.to/2Az4l90) - An in-depth look at the most common test technique, Domain Testing (also called Boundary Analysis and Equivalence Class partitioning) in use today with lots of examples to become better.
- [Don't Make Me Think: A Common Sense Approach to Web Usability](https://amzn.to/2naYmhf) - An incredibly useful book for usability testing.
- [Lessons Learned in Software Testing](https://amzn.to/2LTjM01) - One of the best books on Software Testing, broken into bite size lessons that are as applicable now as when it was published.
- [UI is Communication](https://amzn.to/2vbiALY) - How to make intuitive User Interfaces (UI and Usability Testing).
- [Thinking, Fast and Slow](https://amzn.to/2vcjasX) - About how we make decisions and how to run experiments (experiments == tests).
- [Chaos Engineering: Crash test your applications](https://www.manning.com/books/chaos-engineering) - A book on how to design and execute controlled software failure experiments.
- [Testing JavaScript Applications](https://www.manning.com/books/testing-javascript-applications) - A book about JavaScript testing tools and techniques for developers.
- [Chaos Engineering](https://www.manning.com/books/chaos-engineering) - A book that teaches you to design and execute controlled experiments that uncover hidden problems.
- [The Art of Unit Testing, Third Edition](https://www.manning.com/books/the-art-of-unit-testing-third-edition) - A book that guides you step by step from your first simple unit tests to building complete test sets that are maintainable, readable, and trustworthy.
- [Testing Web APIs](https://www.manning.com/books/testing-web-apis) - Guarantee the quality and consistency of your web APIs by implementing an automated testing process.
- [Effective Software Testing](https://www.manning.com/books/effective-software-testing) - A hands-on guide for developers on how to create high quality tests in a systematic and effective way.

## Training (Includes developer training for automation testers)
- [Learn to Code](https://github.com/karlhorky/learn-to-program) - Another awesome list for developer training
- [The Dojo](https://dojo.ministryoftesting.com/) - Courses and talks directly from the testing community.
- [Guru99](http://www.guru99.com/) - Learn by experience, a bit more fun than video training.
- [Coursera](https://www.coursera.org/) - Online courses from top universities.
- [Cybrary](https://www.cybrary.it/) - Online free security training.
- [BBST Testing Courses](https://bbst.courses/bbst-testingeducation-materials/) - The famous Black Box Software Testing (BBST) courses are university level courses on Software Test Foundations, Bug Reporting and Test Design. These materials have been creative commons licensed for use by anyone. Includes articles, slides and video lectures.

## Blogs
- [James Bach](http://www.satisfice.com/blog/)
- [Michael Bolton](http://www.developsense.com/blog/)
- [Janet Gregory](http://janetgregory.ca/blog/)
- [Nikita Sobolev](https://sobolevn.me/)
- [Softwaretester Blog](https://www.softwaretester.blog/)
- [Automation Panda](https://automationpanda.com/)

## Newsletters
- [Coding Jag](https://www.lambdatest.com/newsletter) - Your weekly dose of the latest in Testing, Development, CI/CD, and Automation—keeping you ahead of the curve."
- [Software Testing Weekly](https://softwaretestingweekly.com/) - A curated round-up of the best software testing news and tools published every Friday.

## Suggested Awesome Lists

### Must Read
- [Falsehoods](https://github.com/kdeldycke/awesome-falsehood) - A funny and educational list of why nothing in Software Development is ever easy. Think you can store a marriage in a DB?
- [Naughty Strings](https://github.com/minimaxir/big-list-of-naughty-strings) - This is the famous list of Naughty Strings. If you're doing some field validation, look no further for inspiration.
- [Unicode](https://github.com/jagracey/Awesome-Unicode) - A great resource for learning how unicode works and the issues it can cause.

### Useful References
- [The Original](https://github.com/sindresorhus/awesome) - The awesome list of awesome lists.
- [Learn to Code](https://github.com/karlhorky/learn-to-program) - Learning to code, for those looking to make the move to automation
- [Application Security](https://github.com/paragonie/awesome-appsec) - Incredibly extensive, but you'll find something to fit the bill.
- [Selenium](https://github.com/christian-bromann/awesome-selenium) - Better than searching Google if you know what you want.
- [Security](https://github.com/sbilly/awesome-security) - This is mostly focused on Infrastructure, but if you're testing a series of systems, this is very useful.
- [Awesome Software Quality](https://github.com/ligurio/awesome-software-quality) - A list of free software testing and verification resources.
- [Awesome Cucumber](https://github.com/virajkulkarni14/awesome-cucumber) - A (relatively-newer) curated list of awesome Cucumber and Gherkin-related resources.
- [Awesome JMeter](https://github.com/aliesbelik/awesome-jmeter) - A curated collection of resources around Apache JMeter.
- [How They Test](https://github.com/abhivaikar/howtheytest) - A curated collection of public resources from tech companies on how they test their software and build a quality culture

## QA and Testing Road Map
- [How to start QA and Testing career](https://github.com/fityanos/Quality-Assurance-Road-Map) - A wide and rich list of strategies, topics, and skills that you need to start a career in software testing and automation.

## Others
- [Testers Rage Playlist](https://play.spotify.com/user/sanchezni/playlist/5yzT0HrymwEeO8ckqgkPiW) - A collaborative playlist from testers for when the red mist descends.
- [Software Testing Conferences](http://testingconferences.org/) - A list of software testing conferences and workshops.
- [Software Testing Interview Tool](https://github.com/TheJambo/ToDoInterviewTest) - A very buggy To Do List to facilitate face to face interviews.

## Contributing
See the *Awesome Testing* [contribution guide](CONTRIBUTING.md) for details on how to contribute.

## Code of Conduct
See the [Code of Conduct](CODE-OF-CONDUCT.md) for details. Basically it comes down to:
>In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and orientation.


## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [the
contributors](https://github.com/TheJambo/awesome-testing/graphs/contributors)
have waived all copyright and related or neighboring rights to this work. See the
[license file](LICENSE) for details.
