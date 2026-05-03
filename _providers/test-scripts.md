---
api_count: 9
api_specs:
- filename: 72a32ca1-f3a2-4a5e-91f2-token
  format: yaml
  label: Postman API
  slug: ''
  spec_type: OpenAPI
  url: https://www.postman.com/postman/postman-public-workspace/api/72a32ca1-f3a2-4a5e-91f2-token
- filename: openapi.yaml
  format: yaml
  label: k6 Performance Testing
  slug: ''
  spec_type: OpenAPI
  url: https://grafana.com/docs/k6/latest/misc/k6-rest-api/
apis:
- description: The Postman API enables programmatic access to Postman collections, environments, monitors, and test scripts. It allows teams to manage and execute API test scripts as part of CI/CD pipelines, retriev
  name: Postman API
  slug: ''
- description: Newman is the command-line companion for Postman, enabling Postman collections and test scripts to be run directly from the terminal or integrated into CI/CD pipelines such as GitHub Actions, Jenkins,
  name: Newman CLI
  slug: ''
- description: Karate is an open-source framework that combines API test automation, mocks, performance testing, and UI automation into a single framework. Test scripts are written in plain-text Gherkin syntax, maki
  name: Karate API Testing Framework
  slug: ''
- description: REST Assured is a Java-based DSL for simplifying testing of REST services. It integrates with JUnit and TestNG, and supports BDD-style test scripting with a fluent API for validating HTTP responses, h
  name: REST Assured
  slug: ''
- description: 'Dredd is an open-source language-agnostic command-line tool for validating API documentation written in OpenAPI or API Blueprint against its backend implementation. It reads test scripts derived from '
  name: Dredd API Testing Framework
  slug: ''
- description: k6 is a modern load-testing tool that uses JavaScript test scripts to simulate concurrent users hitting APIs. Its scripting model allows teams to write reusable, version-controlled performance test sc
  name: k6 Performance Testing
  slug: ''
- description: Playwright is a cross-browser end-to-end testing framework from Microsoft that supports writing test scripts in JavaScript, TypeScript, Python, Java, and .NET. It is widely used for API testing, brows
  name: Playwright Test
  slug: ''
- description: 'Cypress is a JavaScript end-to-end testing framework designed for modern web applications. Its test scripting API supports both API testing and browser automation, with real-time test runner feedback '
  name: Cypress
  slug: ''
- description: Schemathesis is a property-based testing tool for web APIs. It reads OpenAPI or GraphQL schemas and automatically generates test scripts to discover edge cases, crashes, and specification violations t
  name: Schemathesis
  slug: ''
common:
- title: ''
  type: GitHubOrg
  url: https://github.com/api-evangelist/test-scripts
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/test-scripts/main/json-schema/test-scripts-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/test-scripts/main/json-structure/test-scripts-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/test-scripts/main/json-ld/test-scripts-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/test-scripts/main/vocabulary/test-scripts-vocabulary.yml
created: '2025'
description: Automated scripts used to verify software functionality, validate code behavior, and ensure quality through repeatable testing procedures. Test scripts encode testing logic in executable form, enabling continuous integration pipelines to run validation automatically on every code change. They support unit testing, integration testing, end-to-end testing, contract testing, performance testing, and security scanning across REST, GraphQL, SOAP, and gRPC APIs.
features: []
image: ''
integrations: []
jsonld:
- class_count: 22
  name: Test Scripts Context
  property_count: 9
  slug: test-scripts-context
layout: provider
modified: '2026-05-03'
name: Test Scripts
skills: []
slug: test-scripts
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Test Scripts\ndescription: >-\n  Automated scripts used to verify software functionality, validate code behavior,\n  and ensure quality through repeatable testing procedures. Test scripts encode\n  testing logic in executable form, enabling continuous integration pipelines to\n  run validation automatically on every code change. They support unit testing,\n  integration testing, end-to-end testing, contract testing, performance testing,\n  and security scanning across REST, GraphQL, SOAP, and gRPC APIs.\nurl: https://en.wikipedia.org/wiki/Test_automation\ntags:\n  - Automation\n  - CI/CD\n  - Contract Testing\n  - Quality Assurance\n  - Software Development\n  - Testing\ncreated: '2025'\nmodified: '2026-05-03'\napis:\n  - name: Postman API\n    description: >-\n      The Postman API enables programmatic access to Postman collections, environments,\n      monitors, and test scripts. It allows teams to manage and execute API test\n      scripts as part of CI/CD pipelines,\
  \ retrieve test run results, and integrate\n      Postman with other DevOps tooling.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.postman.com/postman/postman-public-workspace/\n    baseURL: https://api.getpostman.com\n    tags:\n      - API Testing\n      - Collections\n      - Test Execution\n    properties:\n      - type: Documentation\n        url: https://learning.postman.com/docs/introduction/overview/\n      - type: OpenAPI\n        url: https://www.postman.com/postman/postman-public-workspace/api/72a32ca1-f3a2-4a5e-91f2-token\n\n  - name: Newman CLI\n    description: >-\n      Newman is the command-line companion for Postman, enabling Postman collections\n      and test scripts to be run directly from the terminal or integrated into CI/CD\n      pipelines such as GitHub Actions, Jenkins, and GitLab CI.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/postmanlabs/newman\n\
  \    baseURL: https://github.com/postmanlabs/newman\n    tags:\n      - CLI\n      - CI/CD\n      - Test Execution\n    properties:\n      - type: Documentation\n        url: https://learning.postman.com/docs/collections/using-newman-cli/command-line-integration-with-newman/\n      - type: GitHubOrg\n        url: https://github.com/postmanlabs/newman\n\n  - name: Karate API Testing Framework\n    description: >-\n      Karate is an open-source framework that combines API test automation, mocks,\n      performance testing, and UI automation into a single framework. Test scripts\n      are written in plain-text Gherkin syntax, making them readable by non-programmers\n      while offering powerful assertion and data-driven capabilities.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://karatelabs.github.io/karate/\n    baseURL: https://karatelabs.github.io/karate/\n    tags:\n      - BDD\n      - Gherkin\n      - API Testing\n   \
  \   - Test Automation\n    properties:\n      - type: Documentation\n        url: https://karatelabs.github.io/karate/\n      - type: GitHubOrg\n        url: https://github.com/karatelabs/karate\n\n  - name: REST Assured\n    description: >-\n      REST Assured is a Java-based DSL for simplifying testing of REST services.\n      It integrates with JUnit and TestNG, and supports BDD-style test scripting\n      with a fluent API for validating HTTP responses, headers, and JSON/XML payloads.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://rest-assured.io/\n    baseURL: https://rest-assured.io/\n    tags:\n      - Java\n      - BDD\n      - REST\n      - Test Automation\n    properties:\n      - type: Documentation\n        url: https://github.com/rest-assured/rest-assured/wiki/Usage\n      - type: GitHubOrg\n        url: https://github.com/rest-assured/rest-assured\n\n  - name: Dredd API Testing Framework\n    description: >-\n\
  \      Dredd is an open-source language-agnostic command-line tool for validating\n      API documentation written in OpenAPI or API Blueprint against its backend\n      implementation. It reads test scripts derived from API specifications and\n      automatically verifies that server responses match documented behavior.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://dredd.org/\n    baseURL: https://dredd.org/\n    tags:\n      - Contract Testing\n      - OpenAPI\n      - Test Automation\n    properties:\n      - type: Documentation\n        url: https://dredd.org/en/latest/\n      - type: GitHubOrg\n        url: https://github.com/apiaryio/dredd\n\n  - name: k6 Performance Testing\n    description: >-\n      k6 is a modern load-testing tool that uses JavaScript test scripts to simulate\n      concurrent users hitting APIs. Its scripting model allows teams to write\n      reusable, version-controlled performance test scripts\
  \ that integrate natively\n      with CI/CD pipelines and output detailed performance metrics.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://k6.io/\n    baseURL: https://api.k6.io\n    tags:\n      - Load Testing\n      - Performance Testing\n      - JavaScript\n      - Test Automation\n    properties:\n      - type: Documentation\n        url: https://grafana.com/docs/k6/latest/\n      - type: OpenAPI\n        url: https://grafana.com/docs/k6/latest/misc/k6-rest-api/\n\n  - name: Playwright Test\n    description: >-\n      Playwright is a cross-browser end-to-end testing framework from Microsoft that\n      supports writing test scripts in JavaScript, TypeScript, Python, Java, and .NET.\n      It is widely used for API testing, browser automation, and full-stack\n      integration test scripting in CI/CD pipelines.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://playwright.dev/\n\
  \    baseURL: https://playwright.dev/\n    tags:\n      - End-to-End Testing\n      - Browser Automation\n      - JavaScript\n      - Test Automation\n    properties:\n      - type: Documentation\n        url: https://playwright.dev/docs/intro\n      - type: GitHubOrg\n        url: https://github.com/microsoft/playwright\n\n  - name: Cypress\n    description: >-\n      Cypress is a JavaScript end-to-end testing framework designed for modern web\n      applications. Its test scripting API supports both API testing and browser\n      automation, with real-time test runner feedback and built-in parallelization\n      for CI/CD environments.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cypress.io/\n    baseURL: https://www.cypress.io/\n    tags:\n      - End-to-End Testing\n      - JavaScript\n      - Test Automation\n    properties:\n      - type: Documentation\n        url: https://docs.cypress.io/\n      - type: GitHubOrg\n\
  \        url: https://github.com/cypress-io/cypress\n\n  - name: Schemathesis\n    description: >-\n      Schemathesis is a property-based testing tool for web APIs. It reads OpenAPI\n      or GraphQL schemas and automatically generates test scripts to discover edge\n      cases, crashes, and specification violations through stateful, hypothesis-driven\n      testing.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://schemathesis.io/\n    baseURL: https://schemathesis.io/\n    tags:\n      - Property-Based Testing\n      - OpenAPI\n      - Fuzz Testing\n    properties:\n      - type: Documentation\n        url: https://schemathesis.readthedocs.io/\n      - type: GitHubOrg\n        url: https://github.com/schemathesis/schemathesis\n\ncommon:\n  - type: GitHubOrg\n    url: https://github.com/api-evangelist/test-scripts\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/test-scripts/main/json-schema/test-scripts-schema.json\n\
  \  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/test-scripts/main/json-structure/test-scripts-structure.json\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/test-scripts/main/json-ld/test-scripts-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/test-scripts/main/vocabulary/test-scripts-vocabulary.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/test-scripts/refs/heads/main/apis.yml
tags:
- Automation
- CI/CD
- Contract Testing
- Quality Assurance
- Software Development
- Testing
url: https://en.wikipedia.org/wiki/Test_automation
use_cases: []
---
