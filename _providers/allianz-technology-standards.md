---
api_count: 2
apis:
- description: Allianz Trade API design guidelines covering REST API conventions, pagination standards (pageSize, page, totalRequired), sorting conventions, asynchronous processing with JobID management, webhook not
  name: Allianz Trade API Design Standards
  slug: allianz-trade-api-standards
- description: Allianz Global Digital Factory backend development standards. Uses Java and Kotlin with Spring Boot for microservices, API-first approach with OpenAPI specifications, Backend for Frontends (BFF) archi
  name: Allianz Backend Development Standards
  slug: allianz-backend-standards
capabilities:
- description: Workflow capability for architects and developers querying Allianz technology standards and checking API compliance against documented guidelines.
  name: Allianz Standards Compliance Workflow
  slug: standards-compliance-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/Allianz
- title: ''
  type: Website
  url: https://www.allianz.com/
- title: ''
  type: Blog
  url: https://globaldigitalfactory.allianz.com/
- title: ''
  type: SpectralRules
  url: rules/allianz-technology-standards-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/allianz-technology-standards-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/standards-compliance-workflow.yaml
created: '2024-01-01'
description: A collection of technology standards and guidelines maintained by Allianz for software development, API design, architecture, and engineering practices. Allianz follows API-first development using OpenAPI specifications, Backend for Frontends (BFF) architecture, and standardized patterns for pagination, sorting, webhooks, and asynchronous processing.
features:
- description: Allianz mandates API-first design using OpenAPI specifications before implementation, enabling frontend teams to work with mock servers independently.
  name: API First Development
- description: Standardized pagination using pageSize (default 20), page (default 1), and totalRequired parameters with Total-Items and Total-Pages response headers.
  name: Pagination Standards
- description: JobID-based pattern for POST/PATCH/DELETE operations returning a job identifier that clients poll until status transitions from pending to processed.
  name: Asynchronous Processing Pattern
- description: Standardized webhook patterns with technical and functional notification types, HTTPS requirement, IP whitelisting, and pre-signed URL support.
  name: Webhook Notification Standards
- description: Allianz Trade APIs standardize on OAuth2 client credentials for programmatic API authentication across all API products.
  name: OAuth2 Security Standard
- description: BFF pattern where each backend service serves a single frontend, enabling clean separation and independent product team decisions.
  name: Backend for Frontends Architecture
image: /assets/icons/allianz-technology-standards.png
integrations:
- description: Allianz follows the OpenAPI Specification as the standard format for API documentation and developer portal integration.
  name: OpenAPI Initiative
- description: Swagger UI used to make API documentation live and executable from OpenAPI specifications.
  name: Swagger UI
- description: Spring Boot is the standard framework for delivering Allianz backend services with REST, security, caching, and logging.
  name: Spring Boot
jsonld:
- class_count: 8
  name: Allianz Technology Standards Context
  property_count: 24
  slug: allianz-technology-standards-context
layout: provider
modified: '2026-04-19'
name: Allianz Technology Standards
rules:
- name: Allianz Technology Standards API Rules
  rule_count: 22
  severity_counts:
    error: 14
    hint: 0
    info: 1
    warn: 7
  slug: allianz-technology-standards-spectral-rules
skills: []
slug: allianz-technology-standards
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: allianz-technology-standards\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/allianz-technology-standards/refs/heads/main/apis.yml\nname: Allianz Technology Standards\ntags:\n  - Best Practices\n  - Enterprise Architecture\n  - Guidelines\n  - Software Development\n  - Technology Standards\n  - API Design\n  - OpenAPI\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  A collection of technology standards and guidelines maintained by Allianz for\n  software development, API design, architecture, and engineering practices.\n  Allianz follows API-first development using OpenAPI specifications, Backend\n  for Frontends (BFF) architecture, and standardized patterns for pagination,\n  sorting, webhooks, and asynchronous processing.\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: allianz-technology-standards:allianz-trade-api-standards\n    name: Allianz\
  \ Trade API Design Standards\n    tags:\n      - API Design\n      - Guidelines\n      - REST API\n      - OpenAPI\n    properties:\n      - url: https://developers.allianz-trade.com/docs/api-design-guidelines\n        type: Documentation\n      - url: https://developers.allianz-trade.com/\n        type: Portal\n    description: >-\n      Allianz Trade API design guidelines covering REST API conventions,\n      pagination standards (pageSize, page, totalRequired), sorting conventions,\n      asynchronous processing with JobID management, webhook notification\n      patterns, and security requirements for API integrations.\n    humanURL: https://developers.allianz-trade.com/docs/api-design-guidelines\n    baseURL: https://developers.allianz-trade.com\n\n  - aid: allianz-technology-standards:allianz-backend-standards\n    name: Allianz Backend Development Standards\n    tags:\n      - Backend\n      - Java\n      - Kotlin\n      - Spring Boot\n      - Architecture\n    properties:\n    \
  \  - url: https://globaldigitalfactory.allianz.com/blog/finally-talking-about-backend-.html\n        type: Documentation\n    description: >-\n      Allianz Global Digital Factory backend development standards. Uses Java\n      and Kotlin with Spring Boot for microservices, API-first approach with\n      OpenAPI specifications, Backend for Frontends (BFF) architecture, and\n      comprehensive automated testing practices.\n    humanURL: https://globaldigitalfactory.allianz.com/blog/finally-talking-about-backend-.html\n    baseURL: https://globaldigitalfactory.allianz.com\n\ncommon:\n  - url: https://github.com/Allianz\n    type: GitHubOrganization\n  - url: https://www.allianz.com/\n    type: Website\n  - url: https://globaldigitalfactory.allianz.com/\n    type: Blog\n  - url: rules/allianz-technology-standards-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/allianz-technology-standards-vocabulary.yaml\n    type: Vocabulary\n  - url: capabilities/standards-compliance-workflow.yaml\n\
  \    type: NaftikoCapability\n  - type: Features\n    data:\n      - name: API First Development\n        description: >-\n          Allianz mandates API-first design using OpenAPI specifications before\n          implementation, enabling frontend teams to work with mock servers\n          independently.\n      - name: Pagination Standards\n        description: >-\n          Standardized pagination using pageSize (default 20), page (default 1),\n          and totalRequired parameters with Total-Items and Total-Pages response\n          headers.\n      - name: Asynchronous Processing Pattern\n        description: >-\n          JobID-based pattern for POST/PATCH/DELETE operations returning a job\n          identifier that clients poll until status transitions from pending to\n          processed.\n      - name: Webhook Notification Standards\n        description: >-\n          Standardized webhook patterns with technical and functional notification\n          types, HTTPS requirement, IP\
  \ whitelisting, and pre-signed URL support.\n      - name: OAuth2 Security Standard\n        description: >-\n          Allianz Trade APIs standardize on OAuth2 client credentials for\n          programmatic API authentication across all API products.\n      - name: Backend for Frontends Architecture\n        description: >-\n          BFF pattern where each backend service serves a single frontend,\n          enabling clean separation and independent product team decisions.\n  - type: UseCases\n    data:\n      - name: API Standards Compliance\n        description: >-\n          Verify that Allianz API implementations conform to documented design\n          guidelines for pagination, sorting, webhooks, and authentication.\n      - name: Developer Onboarding\n        description: >-\n          Guide new developers on Allianz technology conventions for Java/Kotlin\n          backend services, Spring Boot frameworks, and OpenAPI documentation.\n      - name: Architecture Review\n       \
  \ description: >-\n          Use BFF and API-first standards as criteria for architecture reviews\n          and technical decision documentation.\n  - type: Integrations\n    data:\n      - name: OpenAPI Initiative\n        description: >-\n          Allianz follows the OpenAPI Specification as the standard format for\n          API documentation and developer portal integration.\n      - name: Swagger UI\n        description: >-\n          Swagger UI used to make API documentation live and executable from\n          OpenAPI specifications.\n      - name: Spring Boot\n        description: >-\n          Spring Boot is the standard framework for delivering Allianz backend\n          services with REST, security, caching, and logging.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/allianz-technology-standards/refs/heads/main/apis.yml
tags:
- Best Practices
- Enterprise Architecture
- Guidelines
- Software Development
- Technology Standards
- API Design
- OpenAPI
url: https://raw.githubusercontent.com/api-evangelist/allianz-technology-standards/refs/heads/main/apis.yml
use_cases:
- description: Verify that Allianz API implementations conform to documented design guidelines for pagination, sorting, webhooks, and authentication.
  name: API Standards Compliance
- description: Guide new developers on Allianz technology conventions for Java/Kotlin backend services, Spring Boot frameworks, and OpenAPI documentation.
  name: Developer Onboarding
- description: Use BFF and API-first standards as criteria for architecture reviews and technical decision documentation.
  name: Architecture Review
---
