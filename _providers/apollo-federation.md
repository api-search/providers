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
