---
api_count: 1
apis:
- description: API providing access to a catalog of architectural design patterns, their descriptions, use cases, implementation examples, and relationships between patterns.
  name: Architectural Design Patterns API
  slug: architectural-design-patterns-api
common:
- title: ''
  type: Portal
  url: https://en.wikipedia.org/wiki/Architectural_pattern
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Architectural_pattern
- title: ''
  type: GitHubOrganization
  url: https://github.com/api-evangelist
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/architectural-design-patterns/refs/heads/main/rules/architectural-design-patterns-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/architectural-design-patterns/refs/heads/main/vocabulary/architectural-design-patterns-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/architectural-design-patterns/refs/heads/main/json-ld/architectural-design-patterns-api-context.jsonld
created: '2025-01-01'
description: Architectural Design Patterns are reusable solutions to commonly occurring problems in software architecture. They provide templates for designing system structure, component interactions, and overall organization of applications across a range of industries and technical contexts.
features:
- description: Comprehensive catalog of architectural patterns including MVC, Event-Driven, Microservices, CQRS, Saga, and more.
  name: Pattern Catalog
- description: Documented relationships and interactions between architectural patterns.
  name: Pattern Relationships
- description: Code examples and implementation guidance for each architectural pattern.
  name: Implementation Examples
- description: Maps architectural patterns to common software design problems and use cases.
  name: Use Case Mapping
- description: Documentation of common anti-patterns and how to avoid them.
  name: Anti-Patterns
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 10
  name: Architectural Design Patterns Api Context
  property_count: 0
  slug: architectural-design-patterns-api-context
layout: provider
modified: '2026-04-19'
name: Architectural Design Patterns
rules:
- name: Architectural Design Patterns API Rules
  rule_count: 12
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 4
  slug: architectural-design-patterns-spectral-rules
skills: []
slug: architectural-design-patterns
solutions: []
source_yaml: "aid: architectural-design-patterns\nname: Architectural Design Patterns\ndescription: Architectural Design Patterns are reusable solutions to commonly occurring problems in software architecture. They provide templates for designing system structure, component interactions, and overall organization of applications across a range of industries and technical contexts.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Design Patterns\n- Software Architecture\n- Best Practices\n- Software Engineering\n- System Design\n- Microservices\nurl: https://raw.githubusercontent.com/api-evangelist/architectural-design-patterns/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: architectural-design-patterns:architectural-design-patterns-api\n  name: Architectural Design Patterns API\n  description: API providing access to a catalog of architectural design patterns, their\
  \ descriptions, use cases, implementation examples, and relationships between patterns.\n  humanURL: https://en.wikipedia.org/wiki/Architectural_pattern\n  tags:\n  - Design Patterns\n  - Software Architecture\n  - Pattern Catalog\n  - Best Practices\n  properties:\n  - type: Documentation\n    url: https://en.wikipedia.org/wiki/Architectural_pattern\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/architectural-design-patterns/refs/heads/main/openapi/architectural-design-patterns-api.yaml\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/architectural-design-patterns/refs/heads/main/json-schema/architectural-design-patterns-api-pattern-schema.json\ncommon:\n- type: Portal\n  url: https://en.wikipedia.org/wiki/Architectural_pattern\n- type: Documentation\n  url: https://en.wikipedia.org/wiki/Architectural_pattern\n- type: GitHubOrganization\n  url: https://github.com/api-evangelist\n- type: Features\n  data:\n  - name: Pattern\
  \ Catalog\n    description: Comprehensive catalog of architectural patterns including MVC, Event-Driven, Microservices, CQRS, Saga, and more.\n  - name: Pattern Relationships\n    description: Documented relationships and interactions between architectural patterns.\n  - name: Implementation Examples\n    description: Code examples and implementation guidance for each architectural pattern.\n  - name: Use Case Mapping\n    description: Maps architectural patterns to common software design problems and use cases.\n  - name: Anti-Patterns\n    description: Documentation of common anti-patterns and how to avoid them.\n- type: UseCases\n  data:\n  - name: System Design\n    description: Reference patterns when designing new software systems or microservices architectures.\n  - name: Architecture Review\n    description: Evaluate existing systems against established patterns for improvement opportunities.\n  - name: Developer Education\n    description: Teach software engineers and architects\
  \ about proven design approaches.\n  - name: Documentation\n    description: Communicate architectural decisions using shared vocabulary from established patterns.\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/architectural-design-patterns/refs/heads/main/rules/architectural-design-patterns-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/architectural-design-patterns/refs/heads/main/vocabulary/architectural-design-patterns-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/architectural-design-patterns/refs/heads/main/json-ld/architectural-design-patterns-api-context.jsonld\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/architectural-design-patterns/refs/heads/main/apis.yml
tags:
- Design Patterns
- Software Architecture
- Best Practices
- Software Engineering
- System Design
- Microservices
url: https://raw.githubusercontent.com/api-evangelist/architectural-design-patterns/refs/heads/main/apis.yml
use_cases:
- description: Reference patterns when designing new software systems or microservices architectures.
  name: System Design
- description: Evaluate existing systems against established patterns for improvement opportunities.
  name: Architecture Review
- description: Teach software engineers and architects about proven design approaches.
  name: Developer Education
- description: Communicate architectural decisions using shared vocabulary from established patterns.
  name: Documentation
---
