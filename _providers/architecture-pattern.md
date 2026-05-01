---
api_count: 1
api_specs:
- filename: architecture-pattern-api.yaml
  format: yaml
  label: Architecture Pattern API
  slug: architecture-pattern-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/openapi/architecture-pattern-api.yaml
apis:
- description: API providing access to a curated reference library of architecture patterns for distributed systems, microservices, cloud-native applications, and enterprise software.
  name: Architecture Pattern API
  slug: architecture-pattern-api
common:
- title: ''
  type: Portal
  url: https://microservices.io/patterns/
- title: ''
  type: Documentation
  url: https://microservices.io/patterns/
- title: ''
  type: GitHubOrganization
  url: https://github.com/api-evangelist
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/rules/architecture-pattern-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/vocabulary/architecture-pattern-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/json-ld/architecture-pattern-api-context.jsonld
created: '2025-01-01'
description: Architecture Patterns provide reusable solutions to commonly occurring software and system design problems. They offer proven templates for organizing code, components, and interactions across distributed systems, microservices, cloud-native applications, and enterprise software.
features:
- description: Comprehensive catalog of architecture patterns for microservices, distributed systems, and cloud-native applications.
  name: Pattern Catalog
- description: Each pattern includes problem statement, solution approach, and known trade-offs.
  name: Problem-Solution Framework
- description: Related patterns organized into a coherent pattern language for navigating complex architecture decisions.
  name: Pattern Language
- description: Patterns illustrated with real-world implementations from production systems.
  name: Real-World Examples
- description: Guidance for selecting appropriate patterns based on context and constraints.
  name: Decision Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Architecture Pattern Api Context
  property_count: 0
  slug: architecture-pattern-api-context
layout: provider
modified: '2026-04-19'
name: Architecture Pattern
rules:
- name: Architecture Pattern API Rules
  rule_count: 12
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 5
  slug: architecture-pattern-spectral-rules
skills: []
slug: architecture-pattern
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: architecture-pattern\nname: Architecture Pattern\ndescription: Architecture Patterns provide reusable solutions to commonly occurring software and system design problems. They offer proven templates for organizing code, components, and interactions across distributed systems, microservices, cloud-native applications, and enterprise software.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Architecture Patterns\n- Software Architecture\n- Design Patterns\n- System Design\n- Microservices\n- Cloud Native\nurl: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: architecture-pattern:architecture-pattern-api\n  name: Architecture Pattern API\n  description: API providing access to a curated reference library of architecture patterns for distributed systems, microservices, cloud-native\
  \ applications, and enterprise software.\n  humanURL: https://microservices.io/patterns/\n  tags:\n  - Architecture Patterns\n  - Reference Library\n  - Microservices\n  - Cloud Native\n  properties:\n  - type: Documentation\n    url: https://microservices.io/patterns/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/openapi/architecture-pattern-api.yaml\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/json-schema/architecture-pattern-api-pattern-schema.json\ncommon:\n- type: Portal\n  url: https://microservices.io/patterns/\n- type: Documentation\n  url: https://microservices.io/patterns/\n- type: GitHubOrganization\n  url: https://github.com/api-evangelist\n- type: Features\n  data:\n  - name: Pattern Catalog\n    description: Comprehensive catalog of architecture patterns for microservices, distributed systems, and cloud-native applications.\n  - name:\
  \ Problem-Solution Framework\n    description: Each pattern includes problem statement, solution approach, and known trade-offs.\n  - name: Pattern Language\n    description: Related patterns organized into a coherent pattern language for navigating complex architecture decisions.\n  - name: Real-World Examples\n    description: Patterns illustrated with real-world implementations from production systems.\n  - name: Decision Support\n    description: Guidance for selecting appropriate patterns based on context and constraints.\n- type: UseCases\n  data:\n  - name: Microservices Design\n    description: Apply patterns for decomposing monolithic applications into microservices.\n  - name: Distributed Systems\n    description: Reference patterns for handling distributed computing challenges like consistency and availability.\n  - name: Cloud Migration\n    description: Select cloud-native patterns when migrating on-premises applications to cloud platforms.\n  - name: Architecture Review\n\
  \    description: Evaluate architecture decisions against proven patterns and identify improvement areas.\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/rules/architecture-pattern-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/vocabulary/architecture-pattern-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/json-ld/architecture-pattern-api-context.jsonld\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/apis.yml
tags:
- Architecture Patterns
- Software Architecture
- Design Patterns
- System Design
- Microservices
- Cloud Native
url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/apis.yml
use_cases:
- description: Apply patterns for decomposing monolithic applications into microservices.
  name: Microservices Design
- description: Reference patterns for handling distributed computing challenges like consistency and availability.
  name: Distributed Systems
- description: Select cloud-native patterns when migrating on-premises applications to cloud platforms.
  name: Cloud Migration
- description: Evaluate architecture decisions against proven patterns and identify improvement areas.
  name: Architecture Review
---
