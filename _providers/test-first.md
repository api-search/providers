---
api_count: 5
api_specs:
- filename: pact_broker.json
  format: json
  label: Pact Broker API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/pact-foundation/pact_broker/master/lib/pact_broker/api/pact_broker.json
apis:
- description: REST API and tooling for Cucumber BDD framework supporting test-first development with Gherkin feature files, scenario definitions, and step implementations.
  name: Cucumber API
  slug: ''
- description: REST API for Pact Broker contract testing service, enabling consumer-driven contract testing where consumer tests define the API contract before providers implement it.
  name: Pact Broker API
  slug: ''
- description: API design-first platform enabling teams to write API specifications before implementation, supporting test-first development with mock servers, contract testing, and API style guides.
  name: Stoplight API
  slug: ''
- description: Open-source cloud-native tool for API mocking and contract testing, supporting test-first development by generating mocks from OpenAPI, Postman, and gRPC specifications.
  name: Microcks API
  slug: ''
- description: Command-line HTTP API testing framework that validates API implementations against API Blueprint or OpenAPI descriptions, enabling test-first API development.
  name: Dredd API
  slug: ''
common:
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Test-driven_development
- title: ''
  type: Documentation
  url: https://www.agilealliance.org/glossary/tdd/
- title: ''
  type: JSONSchema
  url: json-schema/test-first-specification-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/test-first-contract-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/test-first-mock-schema.json
- title: ''
  type: JSONLD
  url: json-ld/test-first-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/test-first-vocabulary.yml
created: '2025'
description: A software development approach where tests are written before the implementation code, ensuring code quality and driving design decisions through test requirements. Test-first development is the foundational principle behind test-driven development (TDD) and behavior-driven development (BDD), where the specification of expected behavior is captured in executable tests before any production code is written.
features:
- description: Write executable test specifications that define expected behavior before writing any production code.
  name: Specification Before Implementation
- description: Define the API contract through tests before the implementation exists, ensuring design clarity.
  name: API Contract Definition
- description: Use mock servers generated from specifications to enable parallel frontend and backend development.
  name: Mock-First Development
- description: Tests serve as up-to-date documentation of how the system is expected to behave.
  name: Living Documentation
- description: Discover design issues early by specifying tests before implementation reveals constraints.
  name: Fail Fast Feedback
- description: Let API consumers define their expectations as tests that the API provider must satisfy.
  name: Consumer-Driven Contracts
image: ''
integrations:
- description: Generate test-first stubs and mocks directly from OpenAPI specifications.
  name: OpenAPI
- description: Use Gherkin scenarios as the test-first specification for behavior-driven development.
  name: Cucumber
- description: Apply consumer-driven contract testing where consumer tests define provider expectations.
  name: Pact
- description: Use Stoplight Prism to mock APIs from OpenAPI specs enabling test-first development.
  name: Prism
jsonld:
- class_count: 3
  name: Test First Context
  property_count: 37
  slug: test-first-context
layout: provider
modified: '2026-05-03'
name: Test First
skills: []
slug: test-first
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Test First\ndescription: A software development approach where tests are written before the implementation code, ensuring code quality and driving design decisions through test requirements. Test-first development is the foundational principle behind test-driven development (TDD) and behavior-driven development (BDD), where the specification of expected behavior is captured in executable tests before any production code is written.\nurl: https://en.wikipedia.org/wiki/Test-driven_development\ntags:\n  - Behavior-Driven Development\n  - Best Practices\n  - Methodology\n  - Software Design\n  - Software Development\n  - Testing\ncreated: '2025'\nmodified: '2026-05-03'\napis:\n  - name: Cucumber API\n    description: REST API and tooling for Cucumber BDD framework supporting test-first development with Gherkin feature files, scenario definitions, and step implementations.\n    humanURL: https://cucumber.io\n    baseURL: https://cucumber.io\n    tags:\n      - Behavior-Driven\
  \ Development\n      - Gherkin\n      - Test Automation\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://cucumber.io/docs/cucumber/\n      - type: GitHubRepository\n        url: https://github.com/cucumber/cucumber-js\n  - name: Pact Broker API\n    description: REST API for Pact Broker contract testing service, enabling consumer-driven contract testing where consumer tests define the API contract before providers implement it.\n    humanURL: https://docs.pact.io\n    baseURL: https://your-pact-broker.example.com\n    tags:\n      - Consumer-Driven Contracts\n      - Contract Testing\n      - Microservices\n      - Test-First\n    properties:\n      - type: Documentation\n        url: https://docs.pact.io\n      - type: GitHubRepository\n        url: https://github.com/pact-foundation/pact_broker\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/pact-foundation/pact_broker/master/lib/pact_broker/api/pact_broker.json\n  - name: Stoplight\
  \ API\n    description: API design-first platform enabling teams to write API specifications before implementation, supporting test-first development with mock servers, contract testing, and API style guides.\n    humanURL: https://stoplight.io\n    baseURL: https://api.stoplight.io\n    tags:\n      - API Design\n      - Contract Testing\n      - Mock Servers\n      - Test-First\n    properties:\n      - type: Documentation\n        url: https://meta.stoplight.io/docs/platform\n      - type: APIReference\n        url: https://meta.stoplight.io/docs/stoplight-api\n  - name: Microcks API\n    description: Open-source cloud-native tool for API mocking and contract testing, supporting test-first development by generating mocks from OpenAPI, Postman, and gRPC specifications.\n    humanURL: https://microcks.io\n    baseURL: https://your-microcks.example.com/api\n    tags:\n      - API Mocking\n      - Contract Testing\n      - Open Source\n      - Test-First\n    properties:\n      - type:\
  \ Documentation\n        url: https://microcks.io/documentation/\n      - type: GitHubRepository\n        url: https://github.com/microcks/microcks\n  - name: Dredd API\n    description: Command-line HTTP API testing framework that validates API implementations against API Blueprint or OpenAPI descriptions, enabling test-first API development.\n    humanURL: https://dredd.org\n    baseURL: https://dredd.org\n    tags:\n      - API Testing\n      - Contract Testing\n      - OpenAPI\n      - Test-First\n    properties:\n      - type: Documentation\n        url: https://dredd.readthedocs.io\n      - type: GitHubRepository\n        url: https://github.com/apiaryio/dredd\ncommon:\n  - type: Documentation\n    url: https://en.wikipedia.org/wiki/Test-driven_development\n  - type: Documentation\n    url: https://www.agilealliance.org/glossary/tdd/\n  - type: Features\n    data:\n      - name: Specification Before Implementation\n        description: Write executable test specifications that define\
  \ expected behavior before writing any production code.\n      - name: API Contract Definition\n        description: Define the API contract through tests before the implementation exists, ensuring design clarity.\n      - name: Mock-First Development\n        description: Use mock servers generated from specifications to enable parallel frontend and backend development.\n      - name: Living Documentation\n        description: Tests serve as up-to-date documentation of how the system is expected to behave.\n      - name: Fail Fast Feedback\n        description: Discover design issues early by specifying tests before implementation reveals constraints.\n      - name: Consumer-Driven Contracts\n        description: Let API consumers define their expectations as tests that the API provider must satisfy.\n  - type: UseCases\n    data:\n      - name: API-First Design\n        description: Write OpenAPI specifications and generate tests from them before building the implementation.\n      -\
  \ name: Consumer-Driven Contract Testing\n        description: API consumers publish test expectations that API providers must verify in their CI pipelines.\n      - name: Behavior-Driven Development\n        description: Use Gherkin feature files to define expected system behavior before writing implementation.\n      - name: Parallel Development\n        description: Enable frontend and backend teams to develop in parallel using mock servers from specifications.\n      - name: Specification Compliance\n        description: Validate that API implementations comply with their published specifications using test-first assertions.\n  - type: Integrations\n    data:\n      - name: OpenAPI\n        description: Generate test-first stubs and mocks directly from OpenAPI specifications.\n      - name: Cucumber\n        description: Use Gherkin scenarios as the test-first specification for behavior-driven development.\n      - name: Pact\n        description: Apply consumer-driven contract testing\
  \ where consumer tests define provider expectations.\n      - name: Prism\n        description: Use Stoplight Prism to mock APIs from OpenAPI specs enabling test-first development.\n  - type: JSONSchema\n    url: json-schema/test-first-specification-schema.json\n  - type: JSONSchema\n    url: json-schema/test-first-contract-schema.json\n  - type: JSONSchema\n    url: json-schema/test-first-mock-schema.json\n  - type: JSONLD\n    url: json-ld/test-first-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/test-first-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/test-first/refs/heads/main/apis.yml
tags:
- Behavior-Driven Development
- Best Practices
- Methodology
- Software Design
- Software Development
- Testing
url: https://en.wikipedia.org/wiki/Test-driven_development
use_cases:
- description: Write OpenAPI specifications and generate tests from them before building the implementation.
  name: API-First Design
- description: API consumers publish test expectations that API providers must verify in their CI pipelines.
  name: Consumer-Driven Contract Testing
- description: Use Gherkin feature files to define expected system behavior before writing implementation.
  name: Behavior-Driven Development
- description: Enable frontend and backend teams to develop in parallel using mock servers from specifications.
  name: Parallel Development
- description: Validate that API implementations comply with their published specifications using test-first assertions.
  name: Specification Compliance
---
