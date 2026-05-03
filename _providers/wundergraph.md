---
api_count: 1
api_specs:
- filename: wundergraph-cosmo-platform-openapi.yml
  format: yaml
  label: WunderGraph Cosmo Platform API
  slug: cosmo-platform
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wundergraph/refs/heads/main/openapi/wundergraph-cosmo-platform-openapi.yml
apis:
- description: The WunderGraph Cosmo Platform API provides programmatic access to manage federated GraphQL architectures at scale. It powers the Cosmo CLI (wgc) and Cosmo Studio, enabling management of federated gra
  name: WunderGraph Cosmo Platform API
  slug: cosmo-platform
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/wundergraph
- title: ''
  type: Website
  url: https://wundergraph.com/
- title: ''
  type: Pricing
  url: https://wundergraph.com/pricing
- title: ''
  type: Customers
  url: https://wundergraph.com/customers
- title: ''
  type: Blog
  url: https://wundergraph.com/blog
- title: ''
  type: Learning
  url: https://wundergraph.com/learn
- title: ''
  type: Architecture
  url: https://cosmo-docs.wundergraph.com/architecture
- title: ''
  type: Security
  url: https://cosmo-docs.wundergraph.com/security-and-compliance
- title: ''
  type: Compliance
  url: https://cosmo-docs.wundergraph.com/security-and-compliance
- title: ''
  type: Tutorials
  url: https://cosmo-docs.wundergraph.com/tutorial
- title: ''
  type: CLI
  url: https://cosmo-docs.wundergraph.com/cli/intro
- title: ''
  type: Login
  url: https://cosmo.wundergraph.com/login
- title: ''
  type: PrivacyPolicy
  url: https://wundergraph.com/privacy-policy
- title: ''
  type: Trust
  url: https://trust.wundergraph.com/
- title: ''
  type: Support
  url: https://wundergraph.com/contact/sales
- title: ''
  type: Blog
  url: https://wundergraph.com/blog
created: '2025-06-05T00:00:00.000Z'
description: Full Lifecycle API Management for (Federated) GraphQL. Schema Registry, composition checks, analytics, metrics, tracing and routing. Deploy 100% on-prem or use our Managed Service. Apache 2.0 licensed, no vendor-lock.
features:
- name: Advanced Request Tracing
- name: Analytics, Metrics & Tracing
- name: API Gateway
- name: Audit Log
- name: Authentication & Authorization
- name: AWS Lambda Router
- name: Breaking Change Detection
- name: Cache Warmer
- name: Composition Checks
- name: Compositions
- name: Event Driven Federated Subscriptions (Edfs)
- name: Feature Flags
- name: Graph Access Control
- name: Graphql Federation V1 & V2
- name: Graphql Router / Gateway
- name: Graphql Subscriptions for Federation
- name: Managed Service
- name: Mcp Gateway
- name: Oidc
- name: Opentelemetry & Distributed Tracing
- name: Persisted Operations
- name: Pull-Request-Based Schema Workflows
- name: Rbac
- name: Schema Change Notifications
- name: Schema Contracts
- name: Schema Registry
- name: Schema Usage Reporting
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Wundergraph Context
  property_count: 10
  slug: wundergraph-context
layout: provider
modified: '2026-03-14'
name: WunderGraph
skills: []
slug: wundergraph
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wundergraph\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/wundergraph/refs/heads/main/apis.yml\napis:\n  - aid: wundergraph:cosmo-platform\n    name: WunderGraph Cosmo Platform API\n    tags:\n      - Analytics\n      - Composition\n      - Federation\n      - GraphQL\n      - Management\n      - Schema Registry\n    humanURL: https://cosmo-docs.wundergraph.com/\n    properties:\n      - url: https://cosmo-docs.wundergraph.com/\n        type: Documentation\n      - url: openapi/wundergraph-cosmo-platform-openapi.yml\n        type: OpenAPI\n      - url: json-schema/namespace.json\n        type: JSONSchema\n      - url: json-schema/federated-graph.json\n        type: JSONSchema\n      - url: json-schema/subgraph.json\n        type: JSONSchema\n      - url: json-schema/monograph.json\n        type: JSONSchema\n      - url: json-schema/schema-contract.json\n        type: JSONSchema\n      - url: json-schema/feature-flag.json\n        type: JSONSchema\n     \
  \ - url: json-schema/router-token.json\n        type: JSONSchema\n      - url: json-schema/api-key.json\n        type: JSONSchema\n      - url: json-schema/changelog-entry.json\n        type: JSONSchema\n      - url: json-schema/operation-response.json\n        type: JSONSchema\n      - url: json-ld/wundergraph-context.jsonld\n        type: JSONLD\n    description: >-\n      The WunderGraph Cosmo Platform API provides programmatic access to manage\n      federated GraphQL architectures at scale. It powers the Cosmo CLI (wgc)\n      and Cosmo Studio, enabling management of federated graphs, subgraphs,\n      namespaces, schema contracts, feature flags, router configurations, and\n      API keys. The platform includes schema registry, composition checks,\n      analytics, metrics, tracing, and routing capabilities.\nname: WunderGraph\ntags:\n  - Federation\n  - GraphQL\n  - Management\n  - Schema Registry\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  access: 3rd-Party\ncommon:\n  - url: https://github.com/wundergraph\n    name: GitHub Organization\n    type: GitHubOrganization\n  - url: https://wundergraph.com/\n    name: >-\n      WunderGraph Cosmo: The Open-Source GraphQL Federation Solution -\n      WunderGraph\n    type: Website\n    description: 'null'\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: GraphQL Federation\n  - url: https://wundergraph.com/cosmo/features\n    name: WunderGraph Features - WunderGraph\n    type: Features\n    data:\n      - name: Advanced Request Tracing\n      - name: Analytics, Metrics & Tracing\n      - name: API Gateway\n      - name: Audit Log\n      - name: Authentication & Authorization\n      - name: AWS Lambda Router\n      - name: Breaking Change Detection\n      - name: Cache Warmer\n      - name: Composition Checks\n      - name: Compositions\n      - name: Event Driven Federated Subscriptions (Edfs)\n      - name: Feature Flags\n      - name: Graph Access Control\n   \
  \   - name: Graphql Federation V1 & V2\n      - name: Graphql Router / Gateway\n      - name: Graphql Subscriptions for Federation\n      - name: Managed Service\n      - name: Mcp Gateway\n      - name: Oidc\n      - name: Opentelemetry & Distributed Tracing\n      - name: Persisted Operations\n      - name: Pull-Request-Based Schema Workflows\n      - name: Rbac\n      - name: Schema Change Notifications\n      - name: Schema Contracts\n      - name: Schema Registry\n      - name: Schema Usage Reporting\n  - url: https://wundergraph.com/pricing\n    name: Pricing - WunderGraph\n    type: Pricing\n    description: 'null'\n  - url: https://wundergraph.com/customers\n    name: Meet our Customers - WunderGraph\n    type: Customers\n    description: 'null'\n  - url: https://wundergraph.com/blog\n    name: Blog - WunderGraph\n    type: Blog\n    description: 'null'\n  - url: https://wundergraph.com/learn\n    name: Learn GraphQL Federation - WunderGraph\n    type: Learning\n    description:\
  \ 'null'\n  - url: https://cosmo-docs.wundergraph.com/architecture\n    name: Architecture - WunderGraph\n    type: Architecture\n    description: 'null'\n  - url: https://cosmo-docs.wundergraph.com/security-and-compliance\n    name: Security & Compliance - WunderGraph\n    type: Security\n    description: 'null'\n  - url: https://cosmo-docs.wundergraph.com/security-and-compliance\n    name: Security & Compliance - WunderGraph\n    type: Compliance\n    description: 'null'\n  - url: https://cosmo-docs.wundergraph.com/tutorial\n    name: Tutorial - WunderGraph\n    type: Tutorials\n    description: 'null'\n  - url: https://cosmo-docs.wundergraph.com/cli/intro\n    name: Cosmo CLI - WunderGraph\n    type: CLI\n    description: 'null'\n  - url: https://cosmo.wundergraph.com/login\n    name: none\n    type: Login\n    description: 'null'\n  - url: https://wundergraph.com/privacy-policy\n    name: WunderGraph, Inc. Website Privacy Policy - WunderGraph\n    type: PrivacyPolicy\n    description:\
  \ 'null'\n  - url: https://trust.wundergraph.com/\n    name: Trust Center\n    type: Trust\n    description: 'null'\n  - url: https://wundergraph.com/contact/sales\n    name: Talk to GraphQL Federation Experts - WunderGraph\n    type: Support\n    description: 'null'\n  - url: https://wundergraph.com/blog\n    name: Blog - WunderGraph\n    type: Blog\n    description: 'null'\ncreated: '2025-06-05T00:00:00.000Z'\nmodified: '2026-03-14'\nposition: Consuming\ndescription: >-\n  Full Lifecycle API Management for (Federated) GraphQL. Schema Registry,\n  composition checks, analytics, metrics, tracing and routing. Deploy 100%\n  on-prem or use our Managed Service. Apache 2.0 licensed, no vendor-lock.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wundergraph/refs/heads/main/apis.yml
tags:
- Federation
- GraphQL
- Management
- Schema Registry
url: https://raw.githubusercontent.com/api-evangelist/wundergraph/refs/heads/main/apis.yml
use_cases:
- name: GraphQL Federation
---
