---
api_count: 1
apis:
- description: Apollo Federation enables declarative composition of multiple subgraph APIs into a single federated supergraph. The Apollo Router orchestrates requests across subgraphs, combining GraphQL APIs and RES
  name: Apollo Federation
  slug: apollo-federation
common:
- title: ''
  type: Documentation
  url: https://www.apollographql.com/docs/federation/
- title: ''
  type: GettingStarted
  url: https://www.apollographql.com/docs/federation/quickstart/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apollographql
- title: Federation Spec
  type: GitHubRepository
  url: https://github.com/apollographql/federation
- title: Apollo Router
  type: GitHubRepository
  url: https://github.com/apollographql/router
- title: Rover CLI
  type: GitHubRepository
  url: https://github.com/apollographql/rover
- title: Subgraph Compatibility Tests
  type: GitHubRepository
  url: https://github.com/apollographql/apollo-federation-subgraph-compatibility
- title: JVM Support
  type: SDK
  url: https://github.com/apollographql/federation-jvm
- title: ''
  type: Blog
  url: https://www.apollographql.com/blog/
- title: ''
  type: Pricing
  url: https://www.apollographql.com/pricing/
- title: ''
  type: SignUp
  url: https://studio.apollographql.com/signup
created: '2026-03-26'
description: Apollo Federation is an architecture and platform for building a unified supergraph that composes multiple GraphQL APIs (subgraphs) into a single distributed GraphQL endpoint, enabling teams to work independently on different parts of the graph while delivering a unified API to consumers. Federation 2 is the current stable version, supported by the Apollo Router written in Rust and the Rover CLI for schema management.
features:
- description: Compose multiple subgraph schemas into a single unified supergraph schema.
  name: Supergraph Composition
- description: Declarative federation directives (@key, @external, @requires, @provides, @shareable, @link) for schema coordination.
  name: Federation Directives
- description: High-performance Rust-based router that orchestrates queries across subgraphs.
  name: Apollo Router
- description: Declarative integration of REST APIs into federated graphs without writing a separate GraphQL server.
  name: Apollo Connectors
- description: Apollo GraphOS schema registry for publishing, checking, and managing supergraph schemas.
  name: Schema Registry
- description: Command-line tool for publishing subgraph schemas, running checks, and managing the supergraph.
  name: Rover CLI
- description: Intelligent query planning that decomposes client queries into efficient subgraph requests.
  name: Query Planning
- description: Federation-compatible subgraphs can be built in any language or framework.
  name: Subgraph Compatibility
- description: Progressive schema rollout with incremental migration from monolith to federated graph.
  name: Gray Release Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Apollo Connector for integrating Anthropic AI APIs into the supergraph.
  name: Anthropic
- description: Apollo Connector for integrating OpenAI APIs into the supergraph.
  name: OpenAI
- description: Apollo Connector for AWS DynamoDB via REST API integration.
  name: AWS DynamoDB
- description: Apollo Connector for AWS Lambda function invocation.
  name: AWS Lambda
- description: Apollo Connector for Stripe payment API integration.
  name: Stripe
- description: Apollo Connector for OData REST API integration.
  name: OData
- description: Apollo Connector for Strapi CMS API integration.
  name: Strapi
- description: Deploy Apollo Router as a Kubernetes service via Helm charts and operator patterns.
  name: Kubernetes
- description: Official Terraform provider for Apollo GraphOS management.
  name: Terraform
layout: provider
modified: '2026-04-19'
name: Apollo Federation
skills: []
slug: apollo-federation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apollo-federation\nname: Apollo Federation\ndescription: >-\n  Apollo Federation is an architecture and platform for building a unified\n  supergraph that composes multiple GraphQL APIs (subgraphs) into a single\n  distributed GraphQL endpoint, enabling teams to work independently on\n  different parts of the graph while delivering a unified API to consumers.\n  Federation 2 is the current stable version, supported by the Apollo Router\n  written in Rust and the Rover CLI for schema management.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - Federation\n  - GraphQL\n  - Microservices\n  - Open Source\n  - Subgraphs\n  - Supergraph\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apollo-federation/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apollo-federation:apollo-federation\n    name: Apollo Federation\n   \
  \ description: >-\n      Apollo Federation enables declarative composition of multiple subgraph APIs\n      into a single federated supergraph. The Apollo Router orchestrates requests\n      across subgraphs, combining GraphQL APIs and REST APIs (via Apollo Connectors)\n      into a unified endpoint. Federation 2 defines the supergraph schema, federation\n      directives, and composition rules. The Rover CLI manages schema publishing and\n      checks.\n    humanURL: https://www.apollographql.com/docs/federation/\n    tags:\n      - API Gateway\n      - Federation\n      - GraphQL\n      - Microservices\n      - Open Source\n      - REST Integration\n      - Router\n      - Subgraphs\n      - Supergraph\n    properties:\n      - type: Documentation\n        url: https://www.apollographql.com/docs/federation/\n      - type: GettingStarted\n        url: https://www.apollographql.com/docs/federation/quickstart/\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apollo-federation/refs/heads/main/json-schema/supergraph-configuration.json\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apollo-federation/refs/heads/main/json-schema/router-configuration.json\n      - type: GitHubRepository\n        url: https://github.com/apollographql/federation\n      - type: ChangeLog\n        url: https://www.apollographql.com/docs/graphos/reference/federation/versions\ncommon:\n  - type: Documentation\n    url: https://www.apollographql.com/docs/federation/\n  - type: GettingStarted\n    url: https://www.apollographql.com/docs/federation/quickstart/\n  - type: GitHubOrganization\n    url: https://github.com/apollographql\n  - type: GitHubRepository\n    url: https://github.com/apollographql/federation\n    title: Federation Spec\n  - type: GitHubRepository\n    url: https://github.com/apollographql/router\n    title: Apollo Router\n  - type: GitHubRepository\n    url: https://github.com/apollographql/rover\n    title: Rover CLI\n  - type: GitHubRepository\n    url: https://github.com/apollographql/apollo-federation-subgraph-compatibility\n\
  \    title: Subgraph Compatibility Tests\n  - type: SDK\n    url: https://github.com/apollographql/federation-jvm\n    title: JVM Support\n  - type: Blog\n    url: https://www.apollographql.com/blog/\n  - type: Pricing\n    url: https://www.apollographql.com/pricing/\n  - type: SignUp\n    url: https://studio.apollographql.com/signup\n  - type: Features\n    data:\n      - name: Supergraph Composition\n        description: Compose multiple subgraph schemas into a single unified supergraph schema.\n      - name: Federation Directives\n        description: Declarative federation directives (@key, @external, @requires, @provides, @shareable, @link) for schema coordination.\n      - name: Apollo Router\n        description: High-performance Rust-based router that orchestrates queries across subgraphs.\n      - name: Apollo Connectors\n        description: Declarative integration of REST APIs into federated graphs without writing a separate GraphQL server.\n      - name: Schema Registry\n \
  \       description: Apollo GraphOS schema registry for publishing, checking, and managing supergraph schemas.\n      - name: Rover CLI\n        description: Command-line tool for publishing subgraph schemas, running checks, and managing the supergraph.\n      - name: Query Planning\n        description: Intelligent query planning that decomposes client queries into efficient subgraph requests.\n      - name: Subgraph Compatibility\n        description: Federation-compatible subgraphs can be built in any language or framework.\n      - name: Gray Release Support\n        description: Progressive schema rollout with incremental migration from monolith to federated graph.\n  - type: UseCases\n    data:\n      - name: Distributed Team Development\n        description: Enable independent teams to own and develop separate subgraphs while delivering a unified API.\n      - name: REST API Modernization\n        description: Gradually expose existing REST APIs as GraphQL via Apollo Connectors\
  \ without full rewrites.\n      - name: API Consolidation\n        description: Consolidate multiple disparate APIs into a single unified supergraph for consumers.\n      - name: Microservices GraphQL Layer\n        description: Add a federated GraphQL layer over existing microservice architectures.\n      - name: Schema Governance\n        description: Enforce schema design standards across all subgraphs via composition checks.\n  - type: Integrations\n    data:\n      - name: Anthropic\n        description: Apollo Connector for integrating Anthropic AI APIs into the supergraph.\n      - name: OpenAI\n        description: Apollo Connector for integrating OpenAI APIs into the supergraph.\n      - name: AWS DynamoDB\n        description: Apollo Connector for AWS DynamoDB via REST API integration.\n      - name: AWS Lambda\n        description: Apollo Connector for AWS Lambda function invocation.\n      - name: Stripe\n        description: Apollo Connector for Stripe payment API integration.\n\
  \      - name: OData\n        description: Apollo Connector for OData REST API integration.\n      - name: Strapi\n        description: Apollo Connector for Strapi CMS API integration.\n      - name: Kubernetes\n        description: Deploy Apollo Router as a Kubernetes service via Helm charts and operator patterns.\n      - name: Terraform\n        description: Official Terraform provider for Apollo GraphOS management.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apollo-federation/refs/heads/main/apis.yml
tags:
- API Gateway
- Federation
- GraphQL
- Microservices
- Open Source
- Subgraphs
- Supergraph
url: https://raw.githubusercontent.com/api-evangelist/apollo-federation/refs/heads/main/apis.yml
use_cases:
- description: Enable independent teams to own and develop separate subgraphs while delivering a unified API.
  name: Distributed Team Development
- description: Gradually expose existing REST APIs as GraphQL via Apollo Connectors without full rewrites.
  name: REST API Modernization
- description: Consolidate multiple disparate APIs into a single unified supergraph for consumers.
  name: API Consolidation
- description: Add a federated GraphQL layer over existing microservice architectures.
  name: Microservices GraphQL Layer
- description: Enforce schema design standards across all subgraphs via composition checks.
  name: Schema Governance
---
