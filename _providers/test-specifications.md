---
api_count: 8
apis:
- description: The OpenAPI Specification (OAS) is the de-facto standard for describing RESTful APIs. OpenAPI documents serve as machine-readable test specifications that tools such as Dredd, Schemathesis, and Postma
  name: OpenAPI Initiative
  slug: ''
- description: AsyncAPI is an open specification standard for event-driven and message-based APIs. AsyncAPI documents define the channels, messages, and schemas of asynchronous interfaces, providing a test specifica
  name: AsyncAPI Initiative
  slug: ''
- description: JSON Schema provides a vocabulary for annotating and validating JSON documents. Used extensively as the payload specification layer in test specifications, JSON Schema enables both human-readable docu
  name: JSON Schema
  slug: ''
- description: Gherkin is a plain-text language used to write behavior-driven test specifications in Given-When-Then format. Cucumber and Karate consume Gherkin feature files as executable test specifications that b
  name: Gherkin / Cucumber BDD
  slug: ''
- description: 'Pact is a consumer-driven contract testing tool where consumers write test specifications (pacts) that define what responses they expect from provider APIs. Providers then verify their implementation '
  name: Pact Contract Testing
  slug: ''
- description: Swagger Editor is an open-source web-based editor for designing OpenAPI specifications that double as test specifications. It provides real-time validation, mock server generation, and exportable spec
  name: Swagger Editor
  slug: ''
- description: 'Optic is a developer tool that uses API specifications as the source of truth for testing. It tracks specification changes, generates changelog diffs, and validates live traffic against OpenAPI specs '
  name: Optic API
  slug: ''
- description: Spectral is an open-source JSON/YAML linter and specification validator. It evaluates OpenAPI, AsyncAPI, and custom specification documents against rulesets, serving as a static test specification com
  name: Spectral
  slug: ''
common:
- title: ''
  type: GitHubOrg
  url: https://github.com/api-evangelist/test-specifications
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/test-specifications/main/json-schema/test-specifications-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/test-specifications/main/json-structure/test-specifications-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/test-specifications/main/json-ld/test-specifications-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/test-specifications/main/vocabulary/test-specifications-vocabulary.yml
created: '2025'
description: Documentation that defines the requirements, procedures, and expected outcomes for testing software systems and APIs. Test specifications establish the criteria that implementations must satisfy, bridging the gap between product requirements and executable test cases. They include test plans, test case definitions, acceptance criteria, and conformance requirements. Effective use of this practice reduces bugs in production, supports contract testing, and enables a culture of quality-driven development aligned with OpenAPI, AsyncAPI, and JSON Schema standards.
features: []
image: ''
integrations: []
jsonld:
- class_count: 13
  name: Test Specifications Context
  property_count: 8
  slug: test-specifications-context
layout: provider
modified: '2026-05-03'
name: Test Specifications
skills: []
slug: test-specifications
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Test Specifications\ndescription: >-\n  Documentation that defines the requirements, procedures, and expected outcomes\n  for testing software systems and APIs. Test specifications establish the criteria\n  that implementations must satisfy, bridging the gap between product requirements\n  and executable test cases. They include test plans, test case definitions, acceptance\n  criteria, and conformance requirements. Effective use of this practice reduces\n  bugs in production, supports contract testing, and enables a culture of\n  quality-driven development aligned with OpenAPI, AsyncAPI, and JSON Schema standards.\nurl: https://en.wikipedia.org/wiki/Test_specification\ntags:\n  - Acceptance Testing\n  - Contract Testing\n  - Documentation\n  - OpenAPI\n  - Quality Assurance\n  - Testing\ncreated: '2025'\nmodified: '2026-05-03'\napis:\n  - name: OpenAPI Initiative\n    description: >-\n      The OpenAPI Specification (OAS) is the de-facto standard for describing RESTful\n\
  \      APIs. OpenAPI documents serve as machine-readable test specifications that tools\n      such as Dredd, Schemathesis, and Postman use to auto-generate and validate test\n      suites against live API implementations.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.openapis.org/\n    baseURL: https://spec.openapis.org/oas/v3.1.0\n    tags:\n      - REST\n      - Specification\n      - Standards\n    properties:\n      - type: Documentation\n        url: https://spec.openapis.org/oas/v3.1.0\n      - type: GitHubOrg\n        url: https://github.com/OAI/OpenAPI-Specification\n\n  - name: AsyncAPI Initiative\n    description: >-\n      AsyncAPI is an open specification standard for event-driven and message-based\n      APIs. AsyncAPI documents define the channels, messages, and schemas of asynchronous\n      interfaces, providing a test specification baseline for contract and integration\n      testing of Kafka, WebSocket,\
  \ AMQP, and MQTT APIs.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.asyncapi.com/\n    baseURL: https://www.asyncapi.com/\n    tags:\n      - AsyncAPI\n      - Event-Driven\n      - Specification\n    properties:\n      - type: Documentation\n        url: https://www.asyncapi.com/docs\n      - type: GitHubOrg\n        url: https://github.com/asyncapi/spec\n\n  - name: JSON Schema\n    description: >-\n      JSON Schema provides a vocabulary for annotating and validating JSON documents.\n      Used extensively as the payload specification layer in test specifications,\n      JSON Schema enables both human-readable documentation and machine-executable\n      validation of API request and response bodies.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://json-schema.org/\n    baseURL: https://json-schema.org/\n    tags:\n      - JSON\n      - Schema Validation\n \
  \     - Specification\n    properties:\n      - type: Documentation\n        url: https://json-schema.org/learn/getting-started-step-by-step\n      - type: GitHubOrg\n        url: https://github.com/json-schema-org/json-schema-spec\n\n  - name: Gherkin / Cucumber BDD\n    description: >-\n      Gherkin is a plain-text language used to write behavior-driven test specifications\n      in Given-When-Then format. Cucumber and Karate consume Gherkin feature files\n      as executable test specifications that bridge business requirements and automated\n      test implementation for API testing.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cucumber.io/docs/gherkin/\n    baseURL: https://cucumber.io/\n    tags:\n      - BDD\n      - Gherkin\n      - Test Specification\n    properties:\n      - type: Documentation\n        url: https://cucumber.io/docs/gherkin/reference/\n      - type: GitHubOrg\n        url: https://github.com/cucumber/cucumber\n\
  \n  - name: Pact Contract Testing\n    description: >-\n      Pact is a consumer-driven contract testing tool where consumers write test\n      specifications (pacts) that define what responses they expect from provider APIs.\n      Providers then verify their implementation satisfies all consumer-authored\n      specifications via the Pact Broker.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://pact.io/\n    baseURL: https://pact.io/\n    tags:\n      - Consumer-Driven Contracts\n      - Contract Testing\n      - Specification\n    properties:\n      - type: Documentation\n        url: https://docs.pact.io/\n      - type: GitHubOrg\n        url: https://github.com/pact-foundation/pact-specification\n\n  - name: Swagger Editor\n    description: >-\n      Swagger Editor is an open-source web-based editor for designing OpenAPI\n      specifications that double as test specifications. It provides real-time\n      validation, mock\
  \ server generation, and exportable spec files that integrate\n      with testing pipelines.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://editor.swagger.io/\n    baseURL: https://editor.swagger.io/\n    tags:\n      - API Design\n      - OpenAPI\n      - Test Specification\n    properties:\n      - type: Documentation\n        url: https://swagger.io/docs/specification/about/\n      - type: GitHubOrg\n        url: https://github.com/swagger-api/swagger-editor\n\n  - name: Optic API\n    description: >-\n      Optic is a developer tool that uses API specifications as the source of truth\n      for testing. It tracks specification changes, generates changelog diffs, and\n      validates live traffic against OpenAPI specs to detect contract drift between\n      specifications and implementations.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.useoptic.com/\n  \
  \  baseURL: https://api.useoptic.com\n    tags:\n      - API Governance\n      - Contract Testing\n      - OpenAPI\n    properties:\n      - type: Documentation\n        url: https://www.useoptic.com/docs\n      - type: GitHubOrg\n        url: https://github.com/opticdev/optic\n\n  - name: Spectral\n    description: >-\n      Spectral is an open-source JSON/YAML linter and specification validator. It\n      evaluates OpenAPI, AsyncAPI, and custom specification documents against rulesets,\n      serving as a static test specification compliance checker integrated into CI/CD\n      pipelines via the Spectral CLI.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://stoplight.io/open-source/spectral\n    baseURL: https://stoplight.io/open-source/spectral\n    tags:\n      - API Governance\n      - Linting\n      - OpenAPI\n      - Specification\n    properties:\n      - type: Documentation\n        url: https://docs.stoplight.io/docs/spectral\n\
  \      - type: GitHubOrg\n        url: https://github.com/stoplightio/spectral\n\ncommon:\n  - type: GitHubOrg\n    url: https://github.com/api-evangelist/test-specifications\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/test-specifications/main/json-schema/test-specifications-schema.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/test-specifications/main/json-structure/test-specifications-structure.json\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/test-specifications/main/json-ld/test-specifications-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/test-specifications/main/vocabulary/test-specifications-vocabulary.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/test-specifications/refs/heads/main/apis.yml
tags:
- Acceptance Testing
- Contract Testing
- Documentation
- OpenAPI
- Quality Assurance
- Testing
url: https://en.wikipedia.org/wiki/Test_specification
use_cases: []
---
