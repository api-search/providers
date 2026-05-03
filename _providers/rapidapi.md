---
api_count: 6
api_specs:
- filename: rapidapi-rest-platform-api-openapi.yml
  format: yaml
  label: RapidAPI REST Platform API
  slug: rapidapi-rest-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/openapi/rapidapi-rest-platform-api-openapi.yml
- filename: rapidapi-graphql-platform-api-openapi.yml
  format: yaml
  label: RapidAPI GraphQL Platform API
  slug: rapidapi-graphql-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/openapi/rapidapi-graphql-platform-api-openapi.yml
- filename: rapidapi-hub-api-openapi.yml
  format: yaml
  label: RapidAPI Hub API
  slug: rapidapi-hub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/openapi/rapidapi-hub-api-openapi.yml
- filename: rapidapi-testing-api-openapi.yml
  format: yaml
  label: RapidAPI Testing API
  slug: rapidapi-testing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/openapi/rapidapi-testing-api-openapi.yml
- filename: rapidapi-studio-api-openapi.yml
  format: yaml
  label: RapidAPI Studio API
  slug: rapidapi-studio-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/openapi/rapidapi-studio-api-openapi.yml
- filename: rapidapi-gateway-api-openapi.yml
  format: yaml
  label: RapidAPI Gateway API
  slug: rapidapi-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/openapi/rapidapi-gateway-api-openapi.yml
apis:
- description: The RapidAPI REST Platform API allows developers and administrators to programmatically manage their API hub configurations through RESTful endpoints. It provides CRUD operations for organizations, ca
  name: RapidAPI REST Platform API
  slug: rapidapi-rest-platform-api
- description: The RapidAPI GraphQL Platform API exposes the same queries and mutations that RapidAPI uses internally, providing enterprise users with a powerful interface for managing their API hub. It supports cre
  name: RapidAPI GraphQL Platform API
  slug: rapidapi-graphql-platform-api
- description: The RapidAPI Hub is the world's largest API marketplace, enabling developers to discover, test, and connect to thousands of APIs using a single API key. The hub provides a unified interface for browsi
  name: RapidAPI Hub API
  slug: rapidapi-hub-api
- description: 'RapidAPI Testing provides a comprehensive API testing and monitoring solution that supports REST, SOAP, and GraphQL APIs. It offers an interface for creating and running functional tests, performance '
  name: RapidAPI Testing API
  slug: rapidapi-testing-api
- description: RapidAPI Studio is an API design and development environment that enables teams to design, build, and document APIs collaboratively. It supports importing and editing OpenAPI specifications and Postma
  name: RapidAPI Studio API
  slug: rapidapi-studio-api
- description: The RapidAPI Gateway provides enterprise-grade API gateway capabilities for managing API traffic, security, and routing. It enables organizations to configure custom gateways that handle authenticatio
  name: RapidAPI Gateway API
  slug: rapidapi-gateway-api
capabilities:
- description: Workflow capability for API quality engineering teams to create, run, and monitor API tests across environments and global regions using RapidAPI Testing. Enables automated quality gates in CI/CD pipe
  name: RapidAPI API Quality Assurance
  slug: api-quality-assurance
- description: 'Workflow capability for Enterprise Hub administrators to manage their API marketplace: publishing and updating API listings, managing organizations, controlling subscriptions, and monitoring API usage'
  name: RapidAPI Hub Management
  slug: hub-management
common:
- title: ''
  type: Portal
  url: https://rapidapi.com/hub
- title: ''
  type: Documentation
  url: https://docs.rapidapi.com/
- title: ''
  type: Website
  url: https://rapidapi.com/
- title: ''
  type: PrivacyPolicy
  url: https://rapidapi.com/privacy/
- title: ''
  type: TermsOfService
  url: https://rapidapi.com/terms-of-service/
- title: ''
  type: Support
  url: https://rapidapi.com/support/
- title: ''
  type: Blog
  url: https://rapidapi.com/blog/
- title: ''
  type: SignUp
  url: https://rapidapi.com/auth/sign-up
- title: ''
  type: JSONLD
  url: json-ld/rapidapi-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/rapidapi-vocabulary.yml
created: '2026-03-20'
description: RapidAPI operates the world's largest API marketplace, connecting developers to thousands of APIs through a single platform. Their developer platform provides tools for API discovery, testing, management, design, and gateway configuration, enabling both individual developers and enterprises to build, consume, and manage APIs at scale.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Rapidapi Context
  property_count: 11
  slug: rapidapi-context
layout: provider
modified: '2026-05-02'
name: RapidAPI
rules:
- name: RapidAPI API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 1
    info: 0
    warn: 6
  slug: rapidapi-rules
skills: []
slug: rapidapi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rapidapi\nname: RapidAPI\ndescription: >-\n  RapidAPI operates the world's largest API marketplace, connecting developers\n  to thousands of APIs through a single platform. Their developer platform\n  provides tools for API discovery, testing, management, design, and gateway\n  configuration, enabling both individual developers and enterprises to build,\n  consume, and manage APIs at scale.\ntype: Contract\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Marketplace\n  - API Management\n  - API Testing\n  - API Gateway\n  - API Design\n  - Enterprise\ncreated: '2026-03-20'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: rapidapi:rapidapi-rest-platform-api\n    name: RapidAPI REST Platform API\n    description: >-\n      The RapidAPI REST Platform API allows developers\
  \ and administrators to\n      programmatically manage their API hub configurations through RESTful\n      endpoints. It provides CRUD operations for organizations, categories,\n      tags, collections, transactions, subscriptions, and users, enabling\n      automation of tasks normally performed through the Enterprise Hub Admin\n      Panel and integration of hub management into CI/CD pipelines and custom\n      workflows.\n    humanURL: https://docs.rapidapi.com/docs/platform-api-overview\n    tags:\n      - API Management\n      - Platform\n      - Administration\n      - Marketplace\n      - Enterprise\n    properties:\n      - type: Documentation\n        url: https://docs.rapidapi.com/docs/platform-api-overview\n      - type: OpenAPI\n        url: openapi/rapidapi-rest-platform-api-openapi.yml\n      - type: JSONStructure\n        url: json-structure/rapidapi-subscription-structure.json\n      - type: Example\n        url: examples/rapidapi-list-apis-example.json\n      - type: Example\n\
  \        url: examples/rapidapi-list-subscriptions-example.json\n      - type: SpectralRules\n        url: rules/rapidapi-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/hub-management.yaml\n  - aid: rapidapi:rapidapi-graphql-platform-api\n    name: RapidAPI GraphQL Platform API\n    description: >-\n      The RapidAPI GraphQL Platform API exposes the same queries and mutations\n      that RapidAPI uses internally, providing enterprise users with a powerful\n      interface for managing their API hub. It supports creating and updating\n      APIs, managing collections, and configuring hub settings through GraphQL\n      queries and mutations, including integration with GitHub Actions for\n      continuous deployment of API configurations.\n    humanURL: https://docs.rapidapi.com/docs/graphql-platform-api-overview\n    tags:\n      - GraphQL\n      - Platform\n      - API Management\n      - Enterprise\n      - Administration\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.rapidapi.com/docs/graphql-platform-api-overview\n      - type: OpenAPI\n        url: openapi/rapidapi-graphql-platform-api-openapi.yml\n  - aid: rapidapi:rapidapi-hub-api\n    name: RapidAPI Hub API\n    description: >-\n      The RapidAPI Hub is the world's largest API marketplace, enabling\n      developers to discover, test, and connect to thousands of APIs using a\n      single API key. The hub provides a unified interface for browsing APIs\n      across categories such as weather, social media, e-commerce, and finance,\n      with auto-generated code snippets in multiple programming languages and\n      a single dashboard for managing subscriptions and usage analytics.\n    humanURL: https://docs.rapidapi.com/docs/consumer-quick-start-guide\n    tags:\n      - API Discovery\n      - API Marketplace\n      - API Testing\n      - Integration\n      - Search\n    properties:\n      - type: Documentation\n        url: https://docs.rapidapi.com/docs/consumer-quick-start-guide\n\
  \      - type: OpenAPI\n        url: openapi/rapidapi-hub-api-openapi.yml\n  - aid: rapidapi:rapidapi-testing-api\n    name: RapidAPI Testing API\n    description: >-\n      RapidAPI Testing provides a comprehensive API testing and monitoring\n      solution that supports REST, SOAP, and GraphQL APIs. It offers an\n      interface for creating and running functional tests, performance tests,\n      and automated monitoring checks, integrating with CI/CD pipelines and\n      scheduling tests across multiple regions to monitor API health and\n      detect regressions.\n    humanURL: https://docs.rapidapi.com/docs/testing-getting-started\n    tags:\n      - API Testing\n      - Monitoring\n      - Quality Assurance\n      - Automation\n      - CI/CD\n    properties:\n      - type: Documentation\n        url: https://docs.rapidapi.com/docs/testing-getting-started\n      - type: OpenAPI\n        url: openapi/rapidapi-testing-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/rapidapi-test-schema.json\n\
  \      - type: JSONStructure\n        url: json-structure/rapidapi-test-structure.json\n      - type: Example\n        url: examples/rapidapi-list-tests-example.json\n      - type: NaftikoCapabilities\n        url: capabilities/api-quality-assurance.yaml\n  - aid: rapidapi:rapidapi-studio-api\n    name: RapidAPI Studio API\n    description: >-\n      RapidAPI Studio is an API design and development environment that\n      enables teams to design, build, and document APIs collaboratively. It\n      supports importing and editing OpenAPI specifications and Postman\n      Collections, providing a visual interface for defining endpoints,\n      parameters, and response schemas, and integrates with the broader\n      RapidAPI platform to publish designed APIs directly to the hub.\n    humanURL: https://docs.rapidapi.com/docs/studio-overview\n    tags:\n      - API Design\n      - API Development\n      - OpenAPI\n      - Studio\n    properties:\n      - type: Documentation\n        url: https://docs.rapidapi.com/docs/studio-overview\n\
  \      - type: OpenAPI\n        url: openapi/rapidapi-studio-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/rapidapi-api-listing-schema.json\n      - type: JSONStructure\n        url: json-structure/rapidapi-api-listing-structure.json\n  - aid: rapidapi:rapidapi-gateway-api\n    name: RapidAPI Gateway API\n    description: >-\n      The RapidAPI Gateway provides enterprise-grade API gateway capabilities\n      for managing API traffic, security, and routing. It enables organizations\n      to configure custom gateways that handle authentication, rate limiting,\n      and request routing for their APIs, providing a centralized point of\n      control for all API traffic flowing through the RapidAPI platform.\n    humanURL: https://docs.rapidapi.com/docs/gateway-configuration\n    tags:\n      - API Gateway\n      - Traffic Management\n      - Security\n      - Enterprise\n      - Routing\n    properties:\n      - type: Documentation\n        url: https://docs.rapidapi.com/docs/gateway-configuration\n\
  \      - type: OpenAPI\n        url: openapi/rapidapi-gateway-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/rapidapi-gateway-config-schema.json\ncommon:\n  - type: Portal\n    url: https://rapidapi.com/hub\n  - type: Documentation\n    url: https://docs.rapidapi.com/\n  - type: Website\n    url: https://rapidapi.com/\n  - type: PrivacyPolicy\n    url: https://rapidapi.com/privacy/\n  - type: TermsOfService\n    url: https://rapidapi.com/terms-of-service/\n  - type: Support\n    url: https://rapidapi.com/support/\n  - type: Blog\n    url: https://rapidapi.com/blog/\n  - type: SignUp\n    url: https://rapidapi.com/auth/sign-up\n  - type: JSONLD\n    url: json-ld/rapidapi-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/rapidapi-vocabulary.yml\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/apis.yml
tags:
- API Marketplace
- API Management
- API Testing
- API Gateway
- API Design
- Enterprise
url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/apis.yml
use_cases: []
---
