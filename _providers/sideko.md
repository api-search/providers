---
api_count: 4
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Sideko API
  slug: sideko-api
  spec_type: OpenAPI
  url: https://docs.sideko.dev/reference/
apis:
- description: The Sideko REST API allows developers to programmatically interact with the Sideko platform to manage API projects, generate SDKs, create CLI tools, deploy mock servers, and publish API documentation.
  name: Sideko API
  slug: sideko-api
- description: The Sideko CLI provides command-line access to the Sideko platform, enabling developers to generate SDKs, manage API projects, deploy documentation, and run mock servers from the terminal. Built in Ru
  name: Sideko CLI
  slug: sideko-cli
- description: The Sideko Node.js SDK provides TypeScript and JavaScript bindings for the Sideko API. Generated from the Sideko OpenAPI specification, it enables Node.js developers to manage API projects, generate S
  name: Sideko Node.js SDK
  slug: sideko-node-sdk
- description: The Sideko Python SDK provides Python bindings for the Sideko API. Generated from the Sideko OpenAPI specification, it enables Python developers to manage API projects, trigger SDK generation, and aut
  name: Sideko Python SDK
  slug: sideko-python-sdk
capabilities:
- description: 'Unified workflow capability for managing the complete API tooling lifecycle on the Sideko platform. Enables API platform teams to programmatically manage API projects, upload specifications, generate '
  name: Sideko API Tooling Lifecycle
  slug: api-tooling-lifecycle
common:
- title: ''
  type: Website
  url: https://www.sideko.dev/
- title: ''
  type: Documentation
  url: https://docs.sideko.dev/
- title: ''
  type: Sign Up
  url: https://authentication.sideko.dev/sign-up
- title: ''
  type: Pricing
  url: https://sideko.dev/pricing
- title: ''
  type: Blog
  url: https://www.sideko.dev/blog
- title: ''
  type: GitHub
  url: https://github.com/Sideko-Inc
- title: ''
  type: ChangeLog
  url: https://docs.sideko.dev/changelog/
- title: ''
  type: TermsOfService
  url: https://www.sideko.dev/legal/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.sideko.dev/legal/privacy
created: '2025-01-30'
description: Sideko is an API tooling generation platform that uses OpenAPI Specifications to create SDKs, documentation sites, CLIs, and mock servers. The platform enables organizations to offer a complete suite of API developer tools without writing code, as Sideko generates the tooling automatically from OpenAPI specs. Sideko serves some of the largest organizations in the world, helping improve API developer experience at scale.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 15
  name: Sideko Context
  property_count: 8
  slug: sideko-context
layout: provider
modified: '2026-05-02'
name: Sideko
rules:
- name: Sideko API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 6
  slug: sideko-rules
skills: []
slug: sideko
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sideko\nurl: https://raw.githubusercontent.com/api-evangelist/sideko/refs/heads/main/apis.yml\napis:\n  - aid: sideko:sideko-api\n    name: Sideko API\n    tags:\n      - CLI\n      - Documentation\n      - Mock Servers\n      - Platform\n      - SDKs\n    humanURL: https://docs.sideko.dev/\n    baseURL: https://api.sideko.dev\n    properties:\n      - url: https://docs.sideko.dev/\n        type: Documentation\n      - url: https://docs.sideko.dev/reference/\n        type: OpenAPI\n      - url: openapi/sideko-openapi.yml\n        type: OpenAPI\n      - url: rules/sideko-rules.yml\n        type: SpectralRules\n      - url: capabilities/api-tooling-lifecycle.yaml\n        type: Capabilities\n      - url: json-schema/sideko-api-project-schema.json\n        type: JSONSchema\n      - url: json-schema/sideko-sdk-generation-schema.json\n        type: JSONSchema\n      - url: json-ld/sideko-context.jsonld\n        type: JSONLD\n      - url: vocabulary/sideko-vocabulary.yml\n \
  \       type: Vocabulary\n      - url: https://authentication.sideko.dev/sign-up\n        type: Sign Up\n      - url: https://sideko.dev/pricing\n        type: Pricing\n      - url: https://github.com/Sideko-Inc/sideko\n        type: GitHub\n    description: >-\n      The Sideko REST API allows developers to programmatically interact with\n      the Sideko platform to manage API projects, generate SDKs, create CLI\n      tools, deploy mock servers, and publish API documentation. The API enables\n      automation of the entire API tooling lifecycle from spec ingestion through\n      SDK generation and documentation publishing.\n    contact:\n      FN: Sideko Support\n      email: support@sideko.dev\n      url: https://docs.sideko.dev/\n\n  - aid: sideko:sideko-cli\n    name: Sideko CLI\n    tags:\n      - CLI\n      - Developer Tools\n      - SDKs\n    humanURL: https://github.com/Sideko-Inc/sideko\n    properties:\n      - url: https://github.com/Sideko-Inc/sideko\n        type: GitHub\n\
  \      - url: https://docs.sideko.dev/cli/\n        type: Documentation\n    description: >-\n      The Sideko CLI provides command-line access to the Sideko platform,\n      enabling developers to generate SDKs, manage API projects, deploy\n      documentation, and run mock servers from the terminal. Built in Rust,\n      it wraps the Sideko REST API in an ergonomic CLI experience.\n\n  - aid: sideko:sideko-node-sdk\n    name: Sideko Node.js SDK\n    tags:\n      - SDK\n      - Node.js\n      - TypeScript\n      - JavaScript\n    humanURL: https://github.com/Sideko-Inc/sideko-node-sdk\n    properties:\n      - url: https://github.com/Sideko-Inc/sideko-node-sdk\n        type: GitHub\n      - url: https://www.npmjs.com/package/sideko-sdk\n        type: SDK\n    description: >-\n      The Sideko Node.js SDK provides TypeScript and JavaScript bindings for\n      the Sideko API. Generated from the Sideko OpenAPI specification, it\n      enables Node.js developers to manage API projects, generate\
  \ SDKs, and\n      interact with the Sideko platform programmatically.\n\n  - aid: sideko:sideko-python-sdk\n    name: Sideko Python SDK\n    tags:\n      - SDK\n      - Python\n    humanURL: https://github.com/Sideko-Inc/sideko-python-sdk\n    properties:\n      - url: https://github.com/Sideko-Inc/sideko-python-sdk\n        type: GitHub\n      - url: https://pypi.org/project/sideko-sdk/\n        type: SDK\n    description: >-\n      The Sideko Python SDK provides Python bindings for the Sideko API.\n      Generated from the Sideko OpenAPI specification, it enables Python\n      developers to manage API projects, trigger SDK generation, and\n      automate documentation workflows programmatically.\n\nname: Sideko\ntags:\n  - CLI\n  - Documentation\n  - Mock Servers\n  - Platform\n  - SDKs\n  - API Tooling\n  - SDK Generation\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-30'\nmodified: '2026-05-02'\n\
  position: Consuming\nsegments:\n  - Documentation\n  - SDKs\n  - Developer Tools\ndescription: >-\n  Sideko is an API tooling generation platform that uses OpenAPI Specifications\n  to create SDKs, documentation sites, CLIs, and mock servers. The platform\n  enables organizations to offer a complete suite of API developer tools without\n  writing code, as Sideko generates the tooling automatically from OpenAPI specs.\n  Sideko serves some of the largest organizations in the world, helping improve\n  API developer experience at scale.\ncommon:\n  - type: Website\n    url: https://www.sideko.dev/\n  - type: Documentation\n    url: https://docs.sideko.dev/\n  - type: Sign Up\n    url: https://authentication.sideko.dev/sign-up\n  - type: Pricing\n    url: https://sideko.dev/pricing\n  - type: Blog\n    url: https://www.sideko.dev/blog\n  - type: GitHub\n    url: https://github.com/Sideko-Inc\n  - type: ChangeLog\n    url: https://docs.sideko.dev/changelog/\n  - type: TermsOfService\n    url:\
  \ https://www.sideko.dev/legal/terms\n  - type: PrivacyPolicy\n    url: https://www.sideko.dev/legal/privacy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sideko/refs/heads/main/apis.yml
tags:
- CLI
- Documentation
- Mock Servers
- Platform
- SDKs
- API Tooling
- SDK Generation
url: https://raw.githubusercontent.com/api-evangelist/sideko/refs/heads/main/apis.yml
use_cases: []
---
