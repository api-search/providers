---
api_count: 1
api_specs:
- filename: reflect-openapi.yml
  format: yaml
  label: Reflect
  slug: reflect
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reflect/refs/heads/main/openapi/reflect-openapi.yml
apis:
- description: REST API for managing and executing automated end-to-end tests in the Reflect platform. Enables listing available tests, triggering test runs with parameter overrides, and polling execution status for
  name: Reflect
  slug: reflect
capabilities:
- description: Workflow capability for QA engineers and DevOps teams managing and executing automated end-to-end tests through the Reflect API. Supports listing available tests, triggering test runs with parameter o
  name: Reflect Test Automation
  slug: test-automation
common:
- title: ''
  type: Pricing
  url: https://reflect.run/pricing/
- title: ''
  type: Articles
  url: https://reflect.run/articles/
- title: ''
  type: Customers
  url: https://reflect.run/customers/
- title: ''
  type: Login
  url: https://app.reflect.run/login
- title: ''
  type: SignUp
  url: https://app.reflect.run/registration
- title: ''
  type: About
  url: https://reflect.run/about/
- title: ''
  type: TermsOfService
  url: https://reflect.run/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://reflect.run/privacy-policy/
- title: ''
  type: GettingStarted
  url: https://reflect.run/docs/overview/quick-start/
- title: ''
  type: OpenAPI
  url: openapi/reflect-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/reflect-test-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/reflect-execution-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/reflect-api-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/reflect-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/reflect-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/test-automation.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/reflect-vocabulary.yml
created: '2024-11-13'
description: Reflect is an AI-powered automated end-to-end testing platform that enables teams to effortlessly create, execute, and troubleshoot automated browser tests. Reflect provides a no-code test recorder for capturing user workflows and a REST API for integrating test execution into CI/CD pipelines. Tests can be run against any environment using hostname and parameter overrides.
features: []
image: https://reflect.run/assets/logo.png
integrations: []
jsonld:
- class_count: 6
  name: Reflect Context
  property_count: 7
  slug: reflect-context
layout: provider
modified: '2026-05-02'
name: Reflect
rules:
- name: Reflect API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 3
  slug: reflect-rules
skills: []
slug: reflect
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: reflect\nname: Reflect\ndescription: >-\n  Reflect is an AI-powered automated end-to-end testing platform that enables\n  teams to effortlessly create, execute, and troubleshoot automated browser\n  tests. Reflect provides a no-code test recorder for capturing user workflows\n  and a REST API for integrating test execution into CI/CD pipelines. Tests\n  can be run against any environment using hostname and parameter overrides.\ntype: Index\nimage: https://reflect.run/assets/logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/reflect/refs/heads/main/apis.yml\ncreated: '2024-11-13'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - AI Testing\n  - Artificial Intelligence\n  - Automated Testing\n  - CI/CD\n  - End-to-End Testing\n  - QA\n  - Testing\napis:\n  - aid: reflect:reflect\n    name: Reflect\n    description: >-\n      REST API for managing and executing automated end-to-end tests in the\n      Reflect platform. Enables listing available\
  \ tests, triggering test runs\n      with parameter overrides, and polling execution status for CI/CD integration.\n    humanURL: https://reflect.run/\n    baseURL: https://api.reflect.run/v1\n    tags:\n      - AI Testing\n      - Automated Testing\n      - CI/CD\n      - End-to-End Testing\n    properties:\n      - type: Documentation\n        url: https://reflect.run/docs/developer-api/documentation/\n      - type: OpenAPI\n        url: openapi/reflect-openapi.yml\n      - type: GettingStarted\n        url: https://reflect.run/docs/overview/quick-start/\n      - type: Integrations\n        url: https://reflect.run/docs/integrations/\ncommon:\n  - type: Pricing\n    url: https://reflect.run/pricing/\n  - type: Articles\n    url: https://reflect.run/articles/\n  - type: Customers\n    url: https://reflect.run/customers/\n  - type: Login\n    url: https://app.reflect.run/login\n  - type: SignUp\n    url: https://app.reflect.run/registration\n  - type: About\n    url: https://reflect.run/about/\n\
  \  - type: TermsOfService\n    url: https://reflect.run/terms-of-service/\n  - type: PrivacyPolicy\n    url: https://reflect.run/privacy-policy/\n  - type: Integrations\n    url: https://reflect.run/docs/integrations/\n  - type: GettingStarted\n    url: https://reflect.run/docs/overview/quick-start/\n  - type: OpenAPI\n    url: openapi/reflect-openapi.yml\n  - type: JSONSchema\n    url: json-schema/reflect-test-schema.json\n  - type: JSONSchema\n    url: json-schema/reflect-execution-schema.json\n  - type: JSONStructure\n    url: json-structure/reflect-api-structure.json\n  - type: JSONLDContext\n    url: json-ld/reflect-context.jsonld\n  - type: SpectralRules\n    url: rules/reflect-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/test-automation.yaml\n  - type: Vocabulary\n    url: vocabulary/reflect-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/reflect/refs/heads/main/apis.yml
tags:
- AI Testing
- Artificial Intelligence
- Automated Testing
- CI/CD
- End-to-End Testing
- QA
- Testing
url: https://raw.githubusercontent.com/api-evangelist/reflect/refs/heads/main/apis.yml
use_cases: []
---
