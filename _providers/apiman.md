---
api_count: 1
apis:
- description: Apiman is an open source API management platform with a developer portal, API gateway, and management UI supporting policies, plans, organizations, multi-tenancy, and extensible Java-based plugin arch
  name: Apiman
  slug: apiman
common:
- title: ''
  type: Website
  url: https://www.apiman.io
- title: ''
  type: Documentation
  url: https://www.apiman.io/api-manager/latest/index.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/apiman
- title: ''
  type: GitHubRepository
  url: https://github.com/apiman/apiman
created: '2026-03-25'
description: Apiman is an open source API management platform featuring a REST API, manager UI, and standalone developer portal with multi-tenancy, events, notifications, permissions, and approval workflows. It provides extensible API gateway capabilities through a simple Java plugin architecture with support for policies, plans, organizations, and client management.
features:
- description: Full REST API for managing organizations, APIs, plans, clients, and policies programmatically.
  name: REST API Manager
- description: Extensible API gateway that enforces policies at runtime for authentication, rate limiting, and transformation.
  name: API Gateway
- description: Standalone developer portal for API discovery, documentation, and self-service subscription management.
  name: Developer Portal
- description: Pluggable Java-based policy engine supporting rate limiting, quotas, IP whitelisting, authentication, and custom policies.
  name: Policy Engine
- description: Organization-based multi-tenancy allowing separate API management namespaces within a single platform.
  name: Multi-Tenancy
- description: Configurable approval workflows for API subscriptions with notification and event support.
  name: Approval Workflows
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 11
  name: Apiman Context
  property_count: 1
  slug: apiman-context
layout: provider
modified: '2026-04-19'
name: Apiman
skills: []
slug: apiman
solutions:
- description: Free, Apache-licensed API management platform deployable on any JVM-based infrastructure.
  name: Open Source
- description: High-performance async API gateway implementation using Eclipse Vert.x.
  name: Vert.x Gateway
- description: Apiman overlay for WildFly/EAP application server deployments.
  name: WildFly Overlay
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apiman\nname: Apiman\ndescription: >-\n  Apiman is an open source API management platform featuring a REST API,\n  manager UI, and standalone developer portal with multi-tenancy, events,\n  notifications, permissions, and approval workflows. It provides extensible\n  API gateway capabilities through a simple Java plugin architecture with\n  support for policies, plans, organizations, and client management.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - API Management\n  - Developer Portal\n  - Java\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apiman/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apiman:apiman\n    name: Apiman\n    description: >-\n      Apiman is an open source API management platform with a developer portal,\n      API gateway, and management UI supporting policies, plans,\
  \ organizations,\n      multi-tenancy, and extensible Java-based plugin architecture.\n    humanURL: https://github.com/apiman/apiman\n    baseURL: https://localhost:8080/apiman\n    tags:\n      - API Gateway\n      - API Management\n      - Developer Portal\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://www.apiman.io/api-manager/latest/index.html\n      - type: GitHubRepository\n        url: https://github.com/apiman/apiman\n      - type: JSONSchema\n        url: json-schema/apiman-api-schema.json\n      - type: JSONSchema\n        url: json-schema/apiman-plan-schema.json\n      - type: JSON-LD\n        url: json-ld/apiman-context.jsonld\ncommon:\n  - type: Website\n    url: https://www.apiman.io\n  - type: Documentation\n    url: https://www.apiman.io/api-manager/latest/index.html\n  - type: GitHubOrganization\n    url: https://github.com/apiman\n  - type: GitHubRepository\n    url: https://github.com/apiman/apiman\n  - type: Features\n    data:\n\
  \      - name: REST API Manager\n        description: Full REST API for managing organizations, APIs, plans, clients, and policies programmatically.\n      - name: API Gateway\n        description: Extensible API gateway that enforces policies at runtime for authentication, rate limiting, and transformation.\n      - name: Developer Portal\n        description: Standalone developer portal for API discovery, documentation, and self-service subscription management.\n      - name: Policy Engine\n        description: Pluggable Java-based policy engine supporting rate limiting, quotas, IP whitelisting, authentication, and custom policies.\n      - name: Multi-Tenancy\n        description: Organization-based multi-tenancy allowing separate API management namespaces within a single platform.\n      - name: Approval Workflows\n        description: Configurable approval workflows for API subscriptions with notification and event support.\n  - type: UseCases\n    data:\n      - name: On-Premise\
  \ API Management\n        description: Deploy Apiman on-premise to manage APIs across internal services with full control over infrastructure.\n      - name: Developer Portal Hosting\n        description: Provide developers with a self-service portal for discovering and subscribing to APIs.\n      - name: API Policy Enforcement\n        description: Enforce security, rate limiting, and transformation policies on API traffic through the gateway.\n      - name: Multi-Team API Governance\n        description: Use organizations and plans to provide isolated API management environments for multiple teams.\n  - type: Solutions\n    data:\n      - name: Open Source\n        description: Free, Apache-licensed API management platform deployable on any JVM-based infrastructure.\n      - name: Vert.x Gateway\n        description: High-performance async API gateway implementation using Eclipse Vert.x.\n      - name: WildFly Overlay\n        description: Apiman overlay for WildFly/EAP application server\
  \ deployments.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apiman/refs/heads/main/apis.yml
tags:
- API Gateway
- API Management
- Developer Portal
- Java
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apiman/refs/heads/main/apis.yml
use_cases:
- description: Deploy Apiman on-premise to manage APIs across internal services with full control over infrastructure.
  name: On-Premise API Management
- description: Provide developers with a self-service portal for discovering and subscribing to APIs.
  name: Developer Portal Hosting
- description: Enforce security, rate limiting, and transformation policies on API traffic through the gateway.
  name: API Policy Enforcement
- description: Use organizations and plans to provide isolated API management environments for multiple teams.
  name: Multi-Team API Governance
---
