---
api_count: 6
apis:
- description: The Cerbos PDP REST API is the HTTP/JSON interface for sending authorization requests to a running Cerbos Policy Decision Point. It exposes CheckResources for evaluating principal-against-resource dec
  name: Cerbos PDP REST API
  slug: cerbos-pdp-rest-api
- description: The Cerbos PDP gRPC API exposes the cerbos.svc.v1.CerbosService and related management services on port 3593, with server reflection enabled. The gRPC interface is the highest-performance way to embed
  name: Cerbos PDP gRPC API
  slug: cerbos-pdp-grpc-api
- description: Cerbos implements the OpenID AuthZEN authorization API specification, exposing standards-compliant single-evaluation, batch-evaluations, and well-known metadata endpoints so that any AuthZEN-conforman
  name: Cerbos AuthZEN API
  slug: cerbos-authzen-api
- description: The Cerbos Admin API provides management capabilities such as policy add/get/list, schema management, and audit log access on the running PDP. It is intended for administrative use and is gated by HTT
  name: Cerbos PDP Admin API
  slug: cerbos-admin-api
- description: Cerbos Hub is the cloud-hosted Policy Administration Point (PAP) that manages policy authoring, versioning, validation, and distribution to Cerbos PDPs across environments. It also provides decision l
  name: Cerbos Hub API
  slug: cerbos-hub-api
- description: Cerbos Synapse is the enrichment and orchestration component that fetches identity, resource, and relationship attributes from external systems and translates infrastructure protocols (HTTP, gRPC, Gra
  name: Cerbos Synapse
  slug: cerbos-synapse
common:
- title: ''
  type: Website
  url: https://www.cerbos.dev
- title: ''
  type: Documentation
  url: https://docs.cerbos.dev
- title: ''
  type: GettingStarted
  url: https://docs.cerbos.dev/cerbos/latest/quickstart
- title: ''
  type: API
  url: https://docs.cerbos.dev/cerbos/latest/api/index
- title: ''
  type: OpenAPI
  url: https://docs.cerbos.dev/cerbos/latest/api/swagger.json
- title: ''
  type: Hub
  url: https://hub.cerbos.cloud/
- title: ''
  type: GitHub
  url: https://github.com/cerbos/cerbos
- title: ''
  type: GitHubOrganization
  url: https://github.com/cerbos
- title: ''
  type: SourceCode
  url: https://github.com/cerbos/cerbos
- title: ''
  type: IssueTracker
  url: https://github.com/cerbos/cerbos/issues
- title: ''
  type: Releases
  url: https://github.com/cerbos/cerbos/releases
- title: ''
  type: Blog
  url: https://www.cerbos.dev/blog
- title: ''
  type: Pricing
  url: https://www.cerbos.dev/pricing
- title: ''
  type: CaseStudies
  url: https://www.cerbos.dev/case-studies
- title: ''
  type: Customers
  url: https://www.cerbos.dev/customers
- title: ''
  type: Slack
  url: https://join.slack.com/t/cerbos/shared_invite/zt-1a99bp8d6-fJiaY7lpDRRUe4UB1u35Yw
- title: ''
  type: X
  url: https://x.com/CerbosDev
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/cerbos
- title: ''
  type: YouTube
  url: https://www.youtube.com/@cerbos
- title: ''
  type: License
  url: https://github.com/cerbos/cerbos/blob/main/LICENSE
- title: ''
  type: SecurityPolicy
  url: https://www.cerbos.dev/security
- title: ''
  type: TermsOfService
  url: https://www.cerbos.dev/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.cerbos.dev/privacy
- title: ''
  type: Playground
  url: https://play.cerbos.dev
- title: ''
  type: DockerHub
  url: https://hub.docker.com/r/cerbos/cerbos
- title: ''
  type: SDKs
  url: ''
created: '2026-03-25'
description: Cerbos is an open-core, language-agnostic, scalable authorization platform that decouples access control from application code by externalizing fine-grained, context-aware permission decisions into policy-as-code. Authorization is expressed in YAML policies supporting RBAC, ABAC, PBAC, and ReBAC, evaluated by a stateless Policy Decision Point (PDP) that delivers sub-millisecond decisions at scale. The platform consists of the open-source Cerbos PDP (Apache 2.0), Cerbos Hub control plane (PAP), Cerbos Synapse enrichment layer, and PEP SDKs for Go, Java, JavaScript / TypeScript, .NET, PHP, Python, Ruby, and Rust. The PDP exposes both REST (port 3592) and gRPC (port 3593) interfaces, an Admin API, and standards- compliant OpenID AuthZEN endpoints, with query-plan adapters for Prisma and SQLAlchemy.
features:
- name: Policy as Code
- name: YAML Policies
- name: RBAC
- name: ABAC
- name: PBAC
- name: ReBAC
- name: Derived Roles
- name: Sub-Millisecond Decisions
- name: Stateless PDP
- name: REST and gRPC APIs
- name: AuthZEN Standard
- name: Query Plan Generation
- name: Audit Logs
- name: Policy Versioning
- name: Schema Validation
- name: Multiple Storage Backends
- name: Sidecar Deployment
- name: Embedded PDP
- name: Apache 2.0 License
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Kong
- name: Gravitee
- name: Kubernetes
- name: Envoy
- name: Neo4j
- name: Trino
- name: Model Context Protocol
- name: Anthropic
- name: Chroma
- name: Pinecone
- name: Okta
- name: Microsoft Entra ID
- name: AWS Cognito
- name: Keycloak
- name: Auth0
- name: Clerk
- name: Stytch
- name: WorkOS
- name: Zitadel
- name: Prisma
- name: SQLAlchemy
layout: provider
modified: '2026-04-23'
name: Cerbos
skills: []
slug: cerbos
solutions: []
tags:
- ABAC
- Access Control
- Authorization
- AuthZEN
- Open Source
- PBAC
- PDP
- Permissions
- Policy as Code
- RBAC
- ReBAC
- Zero Trust
url: https://raw.githubusercontent.com/api-evangelist/cerbos/refs/heads/main/apis.yml
use_cases:
- name: Multi-Tenant SaaS Authorization
- name: API Authorization
- name: AI Agent Access Control
- name: MCP Server Security
- name: RAG Access Control
- name: Non-Human Identity Authorization
- name: Zero Trust Enforcement
- name: Compliance (SOC 2, HIPAA, GDPR, FedRAMP, PCI DSS)
- name: Fintech Permissions
- name: Healthcare Permissions
---
