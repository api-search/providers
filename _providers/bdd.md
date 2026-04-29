---
api_count: 5
apis:
- description: Cucumber is the world's most popular BDD framework, supporting Java, JavaScript, Ruby, Python, and C#. It uses Gherkin syntax for writing human-readable test scenarios and provides integrations with a
  name: Cucumber
  slug: cucumber
- description: SpecFlow is a BDD framework for .NET developers, enabling teams to write behavior specifications in Gherkin and execute them in C# applications. SpecFlow+ Runner and SpecFlow+ LivingDoc provide enhanc
  name: SpecFlow
  slug: specflow
- description: Behave is a Python BDD framework inspired by Cucumber that enables teams to write behavior specifications in Gherkin syntax and execute them using Python. It integrates with Django, Flask, FastAPI, an
  name: Behave
  slug: behave
- description: Karate is a modern open-source BDD framework that unifies API testing, UI automation, performance testing, and mocking in a single framework. It uses a Gherkin-like DSL and is particularly powerful fo
  name: Karate
  slug: karate
- description: JBehave is a pioneering BDD framework for Java and JVM languages. It supports web, REST API, and microservices testing with integration for JUnit, Spring, Maven, and Gradle. JBehave Web extends the fr
  name: JBehave
  slug: jbehave
common:
- title: ''
  type: Website
  url: https://cucumber.io/
- title: ''
  type: Documentation
  url: https://cucumber.io/docs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/cucumber
created: '2025-01-01'
description: Behavior-Driven Development (BDD) is a software development methodology that combines test-driven development with domain-driven design, encouraging collaboration between developers, QA, and business stakeholders through human-readable test scenarios. The BDD ecosystem includes frameworks, tools, and data providers that enable teams to write specifications in Gherkin syntax (Given-When-Then) and automate those scenarios as executable tests across APIs, UIs, and microservices.
features:
- description: Human-readable Given-When-Then scenario language for describing software behavior as executable specifications.
  name: Gherkin Syntax
- description: BDD frameworks available for Java, JavaScript, Python, Ruby, C#, Go, and most other programming languages.
  name: Multi-Language Support
- description: Frameworks like Karate and Cucumber enable BDD-style API testing for REST, GraphQL, and SOAP services.
  name: API Testing Integration
- description: BDD scenarios serve as living documentation that stays synchronized with the actual system behavior.
  name: Living Documentation
- description: All major BDD frameworks integrate with Jenkins, GitHub Actions, GitLab CI, CircleCI, and other CI/CD platforms.
  name: CI/CD Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Java test runner integration for executing Cucumber and JBehave scenarios in Java projects.
  name: JUnit
- description: Browser automation integration for UI-level BDD testing with Cucumber or SpecFlow.
  name: Playwright
- description: Java DSL for REST API testing commonly used with Cucumber for BDD-style API test suites.
  name: REST Assured
- description: API testing platform that supports BDD-style test writing in the test scripts section.
  name: Postman
- description: Test reporting framework that integrates with Cucumber, SpecFlow, and other BDD frameworks for rich HTML reports.
  name: Allure
layout: provider
modified: '2026-04-19'
name: BDD (Behavior-Driven Development)
skills: []
slug: bdd
solutions: []
source_yaml: "aid: bdd\nname: BDD (Behavior-Driven Development)\ndescription: >-\n  Behavior-Driven Development (BDD) is a software development methodology that\n  combines test-driven development with domain-driven design, encouraging\n  collaboration between developers, QA, and business stakeholders through\n  human-readable test scenarios. The BDD ecosystem includes frameworks, tools,\n  and data providers that enable teams to write specifications in Gherkin syntax\n  (Given-When-Then) and automate those scenarios as executable tests across APIs,\n  UIs, and microservices.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - BDD\n  - Software Development\n  - Testing\n  - Gherkin\n  - Quality Assurance\nurl: https://raw.githubusercontent.com/api-evangelist/bdd/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: bdd:cucumber\n    name: Cucumber\n    description:\
  \ >-\n      Cucumber is the world's most popular BDD framework, supporting Java, JavaScript,\n      Ruby, Python, and C#. It uses Gherkin syntax for writing human-readable\n      test scenarios and provides integrations with all major test runners, CI/CD\n      platforms, and API testing tools. Cucumber School offers learning resources\n      and the Cucumber Open platform provides team-based BDD tooling.\n    humanURL: https://cucumber.io/\n    tags:\n      - BDD\n      - Testing\n      - Gherkin\n      - Java\n      - JavaScript\n    properties:\n      - type: Documentation\n        url: https://cucumber.io/docs/cucumber/\n      - type: GettingStarted\n        url: https://cucumber.io/docs/guides/10-minute-tutorial/\n      - type: GitHubRepository\n        url: https://github.com/cucumber/cucumber-jvm\n\n  - aid: bdd:specflow\n    name: SpecFlow\n    description: >-\n      SpecFlow is a BDD framework for .NET developers, enabling teams to write\n      behavior specifications in Gherkin\
  \ and execute them in C# applications.\n      SpecFlow+ Runner and SpecFlow+ LivingDoc provide enhanced test execution\n      and living documentation capabilities.\n    humanURL: https://specflow.org/\n    tags:\n      - BDD\n      - Testing\n      - Gherkin\n      - .NET\n      - C#\n    properties:\n      - type: Documentation\n        url: https://docs.specflow.org/\n      - type: GettingStarted\n        url: https://docs.specflow.org/projects/specflow/en/latest/Getting-Started/\n\n  - aid: bdd:behave\n    name: Behave\n    description: >-\n      Behave is a Python BDD framework inspired by Cucumber that enables teams to\n      write behavior specifications in Gherkin syntax and execute them using Python.\n      It integrates with Django, Flask, FastAPI, and REST API testing tools.\n    humanURL: https://behave.readthedocs.io/\n    tags:\n      - BDD\n      - Testing\n      - Gherkin\n      - Python\n    properties:\n      - type: Documentation\n        url: https://behave.readthedocs.io/en/stable/\n\
  \      - type: GitHubRepository\n        url: https://github.com/behave/behave\n\n  - aid: bdd:karate\n    name: Karate\n    description: >-\n      Karate is a modern open-source BDD framework that unifies API testing, UI\n      automation, performance testing, and mocking in a single framework. It uses\n      a Gherkin-like DSL and is particularly powerful for REST and GraphQL API\n      testing with JSON/XML validation, JavaScript scripting, and parallel execution.\n    humanURL: https://karatelabs.github.io/karate/\n    tags:\n      - BDD\n      - API Testing\n      - REST Testing\n      - Performance Testing\n    properties:\n      - type: Documentation\n        url: https://karatelabs.github.io/karate/\n      - type: GitHubRepository\n        url: https://github.com/karatelabs/karate\n\n  - aid: bdd:jbehave\n    name: JBehave\n    description: >-\n      JBehave is a pioneering BDD framework for Java and JVM languages. It supports\n      web, REST API, and microservices testing with\
  \ integration for JUnit, Spring,\n      Maven, and Gradle. JBehave Web extends the framework for browser-based BDD testing.\n    humanURL: https://jbehave.org/\n    tags:\n      - BDD\n      - Testing\n      - Java\n      - JVM\n    properties:\n      - type: Documentation\n        url: https://jbehave.org/reference/latest/\n      - type: GitHubRepository\n        url: https://github.com/jbehave/jbehave-core\n\ncommon:\n  - type: Website\n    url: https://cucumber.io/\n  - type: Documentation\n    url: https://cucumber.io/docs/\n  - type: GitHubOrganization\n    url: https://github.com/cucumber\n  - type: Features\n    data:\n      - name: Gherkin Syntax\n        description: Human-readable Given-When-Then scenario language for describing software behavior as executable specifications.\n      - name: Multi-Language Support\n        description: BDD frameworks available for Java, JavaScript, Python, Ruby, C#, Go, and most other programming languages.\n      - name: API Testing Integration\n\
  \        description: Frameworks like Karate and Cucumber enable BDD-style API testing for REST, GraphQL, and SOAP services.\n      - name: Living Documentation\n        description: BDD scenarios serve as living documentation that stays synchronized with the actual system behavior.\n      - name: CI/CD Integration\n        description: All major BDD frameworks integrate with Jenkins, GitHub Actions, GitLab CI, CircleCI, and other CI/CD platforms.\n  - type: UseCases\n    data:\n      - name: API Contract Testing\n        description: Use BDD frameworks to write executable API contract tests that verify request/response behavior from a business perspective.\n      - name: Acceptance Testing\n        description: Write acceptance tests in Gherkin that business stakeholders can read and validate before implementation begins.\n      - name: Regression Testing\n        description: Build a regression test suite using BDD scenarios that can be run automatically on every code change.\n     \
  \ - name: Microservices Testing\n        description: Test microservice integrations using BDD frameworks with HTTP clients and mock servers.\n  - type: Integrations\n    data:\n      - name: JUnit\n        description: Java test runner integration for executing Cucumber and JBehave scenarios in Java projects.\n      - name: Playwright\n        description: Browser automation integration for UI-level BDD testing with Cucumber or SpecFlow.\n      - name: REST Assured\n        description: Java DSL for REST API testing commonly used with Cucumber for BDD-style API test suites.\n      - name: Postman\n        description: API testing platform that supports BDD-style test writing in the test scripts section.\n      - name: Allure\n        description: Test reporting framework that integrates with Cucumber, SpecFlow, and other BDD frameworks for rich HTML reports.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bdd/refs/heads/main/apis.yml
tags:
- Automation
- BDD
- Software Development
- Testing
- Gherkin
- Quality Assurance
url: https://raw.githubusercontent.com/api-evangelist/bdd/refs/heads/main/apis.yml
use_cases:
- description: Use BDD frameworks to write executable API contract tests that verify request/response behavior from a business perspective.
  name: API Contract Testing
- description: Write acceptance tests in Gherkin that business stakeholders can read and validate before implementation begins.
  name: Acceptance Testing
- description: Build a regression test suite using BDD scenarios that can be run automatically on every code change.
  name: Regression Testing
- description: Test microservice integrations using BDD frameworks with HTTP clients and mock servers.
  name: Microservices Testing
---
