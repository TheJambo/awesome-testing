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

### Security
- [BeEF](http://beefproject.com/) - Manipulate the browser exploiting any XSS vulns you find.
- [OWASP ZAP](https://github.com/zaproxy/zaproxy) - This intercepting proxy allows you to see all HTTP traffic and manipulate it in real time. Easy to scan, catalog and exploit security issues.

### Make your life easier
- [LambdaTest](https://www.lambdatest.com) - An AI-powered unified enterprise test execution cloud platform that helps businesses drastically reduce time to market through faster test execution, ensuring quality releases and accelerated digital transformation
- [GoodLooks](https://github.com/dashcamio/goodlooks) - Visually validate Playwright tests using AI vision instead of flaky selectors.
- [Octomind](https://github.com/OctoMind-dev) - auto-generated, run and maintained Playwright tests with AI-powered test case discovery.
- [Courgette](https://courgette-testing.com) - Beautifully simple UI testing. Proper declarative BDD scenarios using Gherkin, Gherkin templates and composable YAML-style page and component objects.
- [Ferrum](https://github.com/rubycdp/ferrum) - very simple and easy to get started with frontend/UI testing in small Ruby scripts, high-level API to control Chrome with the CDP - Chrome DevTools Protocol (NO Selenium dependency)
- [BareTail](https://www.baremetalsoft.com/baretail/) - Brings the tail linux command to Windows, coloured lines and REGEX search and loads of other features.
- [ProxySwitcher](https://chrome.google.com/webstore/detail/proxy-switcher-manager/onnfghpihccifgojkpnnncpagjcdbjod) - We all have to mess with proxies, this makes it a lot easier when using Test/Prod/localhost proxies.
- [Full Page Screenshot](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl) - For when PrintScreen isn't big enough.
- [Form Filler](https://chrome.google.com/webstore/detail/form-filler/bnjjngeaknajbdcgpfkgnonkmififhfo) - Large forms can be really irritating to fill out each time, speed it up with dummy data.
- [Bug Magnet](https://chrome.google.com/webstore/detail/bug-magnet/efhedldbjahpgjcneebmbolkalbhckfi) - Suggests values based on the field type.
- [Check All](https://chrispederick.com/work/web-developer/) - "Select All" is often not available. Why not bring your own?
- [Xmind](http://www.xmind.net/) - The best (free) Mindmapping tool for documenting your tests.
- [TestLink](https://github.com/TestLinkOpenSourceTRMS/testlink-code) - Open Source test case management system
- [Fluxguard](https://fluxguard.com) - Screenshot pixel and DOM change comparisons and regressions.
- [recheck-web](https://github.com/retest/recheck-web) - Open Source change comparison tool with local Golden Masters, git-like ignore syntax and "unbreakable selenium" tests.
- [Kiwi TCMS](https://github.com/kiwitcms/Kiwi) - Open Source test case management system.
- [Testomatio](https://testomat.io/) Modern TCMS allows sync of manual and automated tests in one place. Allure, TestRail, Xray alternative. FREE subscription forever is available.
- [Captura](https://github.com/MathewSachin/Captura) - Open Source video recording tool.
- [QA Wolf](https://github.com/qawolf/qawolf) - Open Source Node.js library for creating browser tests 10x faster.
- [Synth](https://github.com/getsynth/synth) - Open Source test data generator.
- [Requestly](https://requestly.io/) - A lightweight proxy as a browser extension & desktop app to intercept & modify network requests. You can Modify Headers, Redirect Url, Mock API response, Delay/Throttle requests, etc.
- [Robot Framework](https://robotframework.org/) - Generic open source automation framework. It can be used for testing and robotic process automation (RPA).
- [wopee.io](https://wopee.io/) - Autonomous testing platform providing bot for autonomous visual regression testing.
- [DeepfakeHTTP](https://github.com/xnbox/DeepfakeHTTP) - DeepfakeHTTP is a web server that uses HTTP dumps as a source for responses. This tool allows you to test clients against REST, GraphQL, and other APIs.
- [Keploy](https://github.com/keploy/keploy) - API Testing Platform that automatically generates unit test cases along with dependency mocks(test data) from API calls.
- [BugBug](https://bugbug.io) - Lightweight test automation tool for web applications. Easy to learn and doesn't require coding. It's free, with unlimited tests. For an additional monthly fee, you also get cloud monitoring and CI/CD integration.
- [Touca](https://github.com/trytouca/trytouca) - Open source continuous regression testing to compare the behavior and performance of software against a previous baseline version.
- [test-each](https://github.com/ehmicky/test-each) - Repeats tests using different inputs (Data-Driven Testing).
- [Replayable](https://replayable.io) - Desktop dashcam that helps you capture unexpected bugs during manual testing.
- [RestQA](https://github.com/restqa/restqa) - A REST API testing Framework based on ghekin to manage microservice local testing using the best in class Developer experience.
- [playwright-bdd](https://github.com/vitalets/playwright-bdd) - A module for running Behaviour-Driven Development (BDD) tests with Playwright runner.
- [Zato API Test](https://zato.io/en/docs/3.2/api-testing/index.html) - API testing in pure English. No programming needed. Implemented and extendable in Python.
- [HttpMaster](https://www.httpmaster.net) - Professional software tool for HTTP testing and debugging.

### Web3 and Blockchain
- [Dapp.tools](https://dapp.tools/) - Command line tools and smart contract libraries for Ethereum smart contract development.
- [Ganache](https://trufflesuite.com/ganache/) - Personal Ethereum blockchain which you can use to run tests, execute commands, and inspect state while controlling how the chain operates.
- [Foundry](https://github.com/foundry-rs/foundry) - Blazing fast, portable and modular toolkit for Ethereum application development written in Rust.
- [Hardhat](https://hardhat.org/) - Multichain Ethereum development environment.
- [Robot Framework Solidity Testing Toolkit](https://github.com/jg8481/Robot-Framework-Solidity-Testing-Toolkit) - This combines popular smart contract testing and deployment libraries with Robot Framework.
- [Truffle Suite](https://trufflesuite.com/) - Comprehensive suite of tools for smart contract development.
- [Cannon](https://usecannon.com/) - Continuous configuration automation & development cli multi-tool. Like Terraform, Docker and NPM for Ethereum.

### Other
- [Colour Blindness Simulator](https://altreus.github.io/colourblind/) - Simulate all types of Colour Blindness instantly!
- [Yslow](http://yslow.org/) - Analyse why web pages are slow based on Yahoo!'s rules for performance.

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
