---
api_count: 6
api_specs:
- filename: api.github.com.json
  format: json
  label: GitHub Actions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json
- filename: openapi.json
  format: json
  label: CircleCI API
  slug: ''
  spec_type: OpenAPI
  url: https://circleci.com/api/v2/openapi.json
apis:
- description: REST API for GitHub Actions enabling CI/CD workflow automation, test execution, and status checks as part of TDD workflows on pull requests and commits.
  name: GitHub Actions API
  slug: ''
- description: REST API for CircleCI continuous integration platform, supporting pipeline management, test execution, and workflow orchestration as part of TDD CI/CD workflows.
  name: CircleCI API
  slug: ''
- description: REST API for Jenkins automation server supporting build triggers, test execution, and pipeline management for TDD-based development workflows.
  name: Jenkins API
  slug: ''
- description: REST API for SonarQube code quality and security analysis platform, supporting test coverage metrics, code smells, and quality gate enforcement in TDD pipelines.
  name: SonarQube API
  slug: ''
- description: REST API for Codecov code coverage reporting service, enabling programmatic access to coverage reports, branch comparisons, and coverage trends in TDD workflows.
  name: Codecov API
  slug: ''
- description: REST API for Coveralls code coverage history and statistics service, tracking test coverage over time and integrating with GitHub for TDD feedback loops.
  name: Coveralls API
  slug: ''
common:
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Test-driven_development
- title: ''
  type: Documentation
  url: https://martinfowler.com/bliki/TestDrivenDevelopment.html
- title: ''
  type: JSONSchema
  url: json-schema/test-driven-development-cycle-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/test-driven-development-coverage-report-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/test-driven-development-test-spec-schema.json
- title: ''
  type: JSONLD
  url: json-ld/test-driven-development-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/test-driven-development-vocabulary.yml
created: '2025'
description: A software development approach where tests are written before the actual code, following a red-green-refactor cycle to ensure code quality and maintainability. TDD requires developers to write failing tests first, then write minimal code to make them pass, then refactor. It supports the full software development lifecycle from design through deployment and maintenance and is foundational to agile and extreme programming methodologies.
features:
- description: Write failing tests first, implement minimal code to pass them, then refactor while keeping tests green.
  name: Red-Green-Refactor Cycle
- description: Ensure all production code is covered by tests written before implementation.
  name: Test Coverage Enforcement
- description: Get immediate feedback on code correctness through automated test runs on every change.
  name: Continuous Feedback
- description: Use failing tests to define the API contract and behavior before implementation begins.
  name: Design by Contract
- description: Build a comprehensive regression suite as a side effect of the TDD development process.
  name: Regression Prevention
- description: Refactor code with confidence knowing the full test suite will catch regressions.
  name: Refactoring Safety
image: ''
integrations:
- description: Run TDD test suites automatically on pull requests using GitHub Actions workflows.
  name: GitHub Actions
- description: Use Jest for JavaScript TDD with fast test execution and snapshot testing.
  name: Jest
- description: Use JUnit for Java TDD with test lifecycle management and assertion libraries.
  name: JUnit
- description: Use pytest for Python TDD with fixtures, parametrize, and plugin ecosystem.
  name: pytest
- description: Use RSpec for Ruby TDD with behavior-driven development syntax.
  name: RSpec
jsonld:
- class_count: 3
  name: Test Driven Development Context
  property_count: 39
  slug: test-driven-development-context
layout: provider
modified: '2026-05-03'
name: Test-Driven Development
skills: []
slug: test-driven-development
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Test-Driven Development\ndescription: A software development approach where tests are written before the actual code, following a red-green-refactor cycle to ensure code quality and maintainability. TDD requires developers to write failing tests first, then write minimal code to make them pass, then refactor. It supports the full software development lifecycle from design through deployment and maintenance and is foundational to agile and extreme programming methodologies.\nurl: https://en.wikipedia.org/wiki/Test-driven_development\ntags:\n  - Agile\n  - Best Practices\n  - Continuous Integration\n  - Extreme Programming\n  - Methodology\n  - Software Development\n  - Testing\ncreated: '2025'\nmodified: '2026-05-03'\napis:\n  - name: GitHub Actions API\n    description: REST API for GitHub Actions enabling CI/CD workflow automation, test execution, and status checks as part of TDD workflows on pull requests and commits.\n    humanURL: https://docs.github.com/en/rest/actions\n\
  \    baseURL: https://api.github.com\n    tags:\n      - CI/CD\n      - Continuous Integration\n      - GitHub\n      - Test Automation\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/rest/actions\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json\n  - name: CircleCI API\n    description: REST API for CircleCI continuous integration platform, supporting pipeline management, test execution, and workflow orchestration as part of TDD CI/CD workflows.\n    humanURL: https://circleci.com/docs/api/v2/\n    baseURL: https://circleci.com/api/v2\n    tags:\n      - CI/CD\n      - Continuous Integration\n      - Pipelines\n      - Test Automation\n    properties:\n      - type: Documentation\n        url: https://circleci.com/docs/api/v2/\n      - type: OpenAPI\n        url: https://circleci.com/api/v2/openapi.json\n  - name: Jenkins API\n    description: REST\
  \ API for Jenkins automation server supporting build triggers, test execution, and pipeline management for TDD-based development workflows.\n    humanURL: https://www.jenkins.io/doc/book/using/remote-access-api/\n    baseURL: https://your-jenkins.example.com\n    tags:\n      - Automation\n      - Build Management\n      - CI/CD\n      - Continuous Integration\n    properties:\n      - type: Documentation\n        url: https://www.jenkins.io/doc/book/using/remote-access-api/\n  - name: SonarQube API\n    description: REST API for SonarQube code quality and security analysis platform, supporting test coverage metrics, code smells, and quality gate enforcement in TDD pipelines.\n    humanURL: https://docs.sonarsource.com/sonarqube/latest/extension-guide/web-api/\n    baseURL: https://your-sonar.example.com/api\n    tags:\n      - Code Coverage\n      - Code Quality\n      - Static Analysis\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://docs.sonarsource.com/sonarqube/latest/extension-guide/web-api/\n\
  \  - name: Codecov API\n    description: REST API for Codecov code coverage reporting service, enabling programmatic access to coverage reports, branch comparisons, and coverage trends in TDD workflows.\n    humanURL: https://docs.codecov.com/reference\n    baseURL: https://api.codecov.io/api/v2\n    tags:\n      - Code Coverage\n      - Reporting\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://docs.codecov.com/reference\n      - type: APIReference\n        url: https://docs.codecov.com/reference\n  - name: Coveralls API\n    description: REST API for Coveralls code coverage history and statistics service, tracking test coverage over time and integrating with GitHub for TDD feedback loops.\n    humanURL: https://docs.coveralls.io\n    baseURL: https://coveralls.io\n    tags:\n      - Code Coverage\n      - Reporting\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://docs.coveralls.io\ncommon:\n  - type: Documentation\n\
  \    url: https://en.wikipedia.org/wiki/Test-driven_development\n  - type: Documentation\n    url: https://martinfowler.com/bliki/TestDrivenDevelopment.html\n  - type: Features\n    data:\n      - name: Red-Green-Refactor Cycle\n        description: Write failing tests first, implement minimal code to pass them, then refactor while keeping tests green.\n      - name: Test Coverage Enforcement\n        description: Ensure all production code is covered by tests written before implementation.\n      - name: Continuous Feedback\n        description: Get immediate feedback on code correctness through automated test runs on every change.\n      - name: Design by Contract\n        description: Use failing tests to define the API contract and behavior before implementation begins.\n      - name: Regression Prevention\n        description: Build a comprehensive regression suite as a side effect of the TDD development process.\n      - name: Refactoring Safety\n        description: Refactor code\
  \ with confidence knowing the full test suite will catch regressions.\n  - type: UseCases\n    data:\n      - name: API Design Validation\n        description: Use TDD to validate API contracts before writing implementation code.\n      - name: Bug-Driven Development\n        description: Write a failing test that reproduces a bug before fixing it to prevent recurrence.\n      - name: Legacy Code Modernization\n        description: Apply TDD when refactoring legacy code to ensure behavior is preserved.\n      - name: Microservice Development\n        description: Use TDD to build well-tested microservice APIs with clear contracts.\n      - name: Continuous Integration\n        description: Run TDD test suites automatically on every commit to maintain code quality.\n  - type: Integrations\n    data:\n      - name: GitHub Actions\n        description: Run TDD test suites automatically on pull requests using GitHub Actions workflows.\n      - name: Jest\n        description: Use Jest for\
  \ JavaScript TDD with fast test execution and snapshot testing.\n      - name: JUnit\n        description: Use JUnit for Java TDD with test lifecycle management and assertion libraries.\n      - name: pytest\n        description: Use pytest for Python TDD with fixtures, parametrize, and plugin ecosystem.\n      - name: RSpec\n        description: Use RSpec for Ruby TDD with behavior-driven development syntax.\n  - type: JSONSchema\n    url: json-schema/test-driven-development-cycle-schema.json\n  - type: JSONSchema\n    url: json-schema/test-driven-development-coverage-report-schema.json\n  - type: JSONSchema\n    url: json-schema/test-driven-development-test-spec-schema.json\n  - type: JSONLD\n    url: json-ld/test-driven-development-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/test-driven-development-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/test-driven-development/refs/heads/main/apis.yml
tags:
- Agile
- Best Practices
- Continuous Integration
- Extreme Programming
- Methodology
- Software Development
- Testing
url: https://en.wikipedia.org/wiki/Test-driven_development
use_cases:
- description: Use TDD to validate API contracts before writing implementation code.
  name: API Design Validation
- description: Write a failing test that reproduces a bug before fixing it to prevent recurrence.
  name: Bug-Driven Development
- description: Apply TDD when refactoring legacy code to ensure behavior is preserved.
  name: Legacy Code Modernization
- description: Use TDD to build well-tested microservice APIs with clear contracts.
  name: Microservice Development
- description: Run TDD test suites automatically on every commit to maintain code quality.
  name: Continuous Integration
---
