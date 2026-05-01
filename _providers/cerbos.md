---
api_count: 6
api_specs:
- filename: swagger.json
  format: json
  label: Cerbos PDP REST API
  slug: cerbos-pdp-rest-api
  spec_type: OpenAPI
  url: https://docs.cerbos.dev/cerbos/latest/api/swagger.json
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cerbos\nname: Cerbos\ndescription: >-\n  Cerbos is an open-core, language-agnostic, scalable authorization platform\n  that decouples access control from application code by externalizing\n  fine-grained, context-aware permission decisions into policy-as-code.\n  Authorization is expressed in YAML policies supporting RBAC, ABAC, PBAC,\n  and ReBAC, evaluated by a stateless Policy Decision Point (PDP) that\n  delivers sub-millisecond decisions at scale. The platform consists of the\n  open-source Cerbos PDP (Apache 2.0), Cerbos Hub control plane (PAP),\n  Cerbos Synapse enrichment layer, and PEP SDKs for Go, Java, JavaScript /\n  TypeScript, .NET, PHP, Python, Ruby, and Rust. The PDP exposes both REST\n  (port 3592) and gRPC (port 3593) interfaces, an Admin API, and standards-\n  compliant OpenID AuthZEN endpoints, with query-plan adapters for Prisma\n  and SQLAlchemy.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n\
  \  - ABAC\n  - Access Control\n  - Authorization\n  - AuthZEN\n  - Open Source\n  - PBAC\n  - PDP\n  - Permissions\n  - Policy as Code\n  - RBAC\n  - ReBAC\n  - Zero Trust\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cerbos/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: cerbos:cerbos-pdp-rest-api\n    name: Cerbos PDP REST API\n    description: >-\n      The Cerbos PDP REST API is the HTTP/JSON interface for sending\n      authorization requests to a running Cerbos Policy Decision Point. It\n      exposes CheckResources for evaluating principal-against-resource\n      decisions, PlanResources for translating policies into resource-filter\n      query plans, and ServerInfo for runtime metadata. An OpenAPI / Swagger\n      specification is served by every PDP instance.\n    humanURL: https://docs.cerbos.dev/cerbos/latest/api/index\n    baseURL: http://localhost:3592\n    tags:\n      - CheckResources\n\
  \      - PDP\n      - PlanResources\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.cerbos.dev/cerbos/latest/api/index\n      - type: OpenAPI\n        url: https://docs.cerbos.dev/cerbos/latest/api/swagger.json\n      - type: Reference\n        url: https://docs.cerbos.dev/cerbos/latest/api/index#api-resources\n  - aid: cerbos:cerbos-pdp-grpc-api\n    name: Cerbos PDP gRPC API\n    description: >-\n      The Cerbos PDP gRPC API exposes the cerbos.svc.v1.CerbosService and\n      related management services on port 3593, with server reflection\n      enabled. The gRPC interface is the highest-performance way to embed\n      Cerbos as a sidecar or in-process service for service-to-service\n      authorization.\n    humanURL: https://docs.cerbos.dev/cerbos/latest/api/index\n    baseURL: localhost:3593\n    tags:\n      - gRPC\n      - PDP\n      - Protocol Buffers\n    properties:\n      - type: Documentation\n        url: https://docs.cerbos.dev/cerbos/latest/api/index\n\
  \      - type: Protocol\n        url: https://github.com/cerbos/cerbos/tree/main/api/genpb\n  - aid: cerbos:cerbos-authzen-api\n    name: Cerbos AuthZEN API\n    description: >-\n      Cerbos implements the OpenID AuthZEN authorization API specification,\n      exposing standards-compliant single-evaluation, batch-evaluations, and\n      well-known metadata endpoints so that any AuthZEN-conformant client or\n      Policy Enforcement Point can integrate with Cerbos as the decision\n      engine.\n    humanURL: https://docs.cerbos.dev/cerbos/latest/api/index\n    tags:\n      - AuthZEN\n      - OpenID\n      - Standards\n    properties:\n      - type: Documentation\n        url: https://docs.cerbos.dev/cerbos/latest/api/index#authzen\n      - type: Specification\n        url: https://openid.net/specs/authorization-api-1_0.html\n      - type: Discovery\n        url: https://docs.cerbos.dev/cerbos/latest/api/index#authzen\n  - aid: cerbos:cerbos-admin-api\n    name: Cerbos PDP Admin API\n\
  \    description: >-\n      The Cerbos Admin API provides management capabilities such as policy\n      add/get/list, schema management, and audit log access on the running\n      PDP. It is intended for administrative use and is gated by HTTP Basic\n      Auth.\n    humanURL: https://docs.cerbos.dev/cerbos/latest/api/admin_api\n    tags:\n      - Admin\n      - Audit Log\n      - Policy Management\n    properties:\n      - type: Documentation\n        url: https://docs.cerbos.dev/cerbos/latest/api/admin_api\n  - aid: cerbos:cerbos-hub-api\n    name: Cerbos Hub API\n    description: >-\n      Cerbos Hub is the cloud-hosted Policy Administration Point (PAP) that\n      manages policy authoring, versioning, validation, and distribution to\n      Cerbos PDPs across environments. It also provides decision logs,\n      collaborative policy editing, and embedded PDP delivery.\n    humanURL: https://docs.cerbos.dev/cerbos-hub/\n    tags:\n      - Cloud\n      - Hub\n      - Policy Administration\n\
  \      - Policy Distribution\n    properties:\n      - type: Documentation\n        url: https://docs.cerbos.dev/cerbos-hub/\n      - type: Console\n        url: https://hub.cerbos.cloud/\n  - aid: cerbos:cerbos-synapse\n    name: Cerbos Synapse\n    description: >-\n      Cerbos Synapse is the enrichment and orchestration component that\n      fetches identity, resource, and relationship attributes from external\n      systems and translates infrastructure protocols (HTTP, gRPC, GraphQL)\n      into Cerbos authorization checks for ReBAC and ABAC scenarios.\n    humanURL: https://www.cerbos.dev/products/synapse\n    tags:\n      - Enrichment\n      - ReBAC\n      - Synapse\n    properties:\n      - type: Documentation\n        url: https://www.cerbos.dev/products/synapse\ncommon:\n  - type: Website\n    url: https://www.cerbos.dev\n  - type: Documentation\n    url: https://docs.cerbos.dev\n  - type: GettingStarted\n    url: https://docs.cerbos.dev/cerbos/latest/quickstart\n  - type: API\n\
  \    url: https://docs.cerbos.dev/cerbos/latest/api/index\n  - type: OpenAPI\n    url: https://docs.cerbos.dev/cerbos/latest/api/swagger.json\n  - type: Hub\n    url: https://hub.cerbos.cloud/\n  - type: GitHub\n    url: https://github.com/cerbos/cerbos\n  - type: GitHubOrganization\n    url: https://github.com/cerbos\n  - type: SourceCode\n    url: https://github.com/cerbos/cerbos\n  - type: IssueTracker\n    url: https://github.com/cerbos/cerbos/issues\n  - type: Releases\n    url: https://github.com/cerbos/cerbos/releases\n  - type: Blog\n    url: https://www.cerbos.dev/blog\n  - type: Pricing\n    url: https://www.cerbos.dev/pricing\n  - type: CaseStudies\n    url: https://www.cerbos.dev/case-studies\n  - type: Customers\n    url: https://www.cerbos.dev/customers\n  - type: Slack\n    url: https://join.slack.com/t/cerbos/shared_invite/zt-1a99bp8d6-fJiaY7lpDRRUe4UB1u35Yw\n  - type: X\n    url: https://x.com/CerbosDev\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/cerbos\n\
  \  - type: YouTube\n    url: https://www.youtube.com/@cerbos\n  - type: License\n    url: https://github.com/cerbos/cerbos/blob/main/LICENSE\n  - type: SecurityPolicy\n    url: https://www.cerbos.dev/security\n  - type: TermsOfService\n    url: https://www.cerbos.dev/terms\n  - type: PrivacyPolicy\n    url: https://www.cerbos.dev/privacy\n  - type: Playground\n    url: https://play.cerbos.dev\n  - type: DockerHub\n    url: https://hub.docker.com/r/cerbos/cerbos\n  - name: Features\n    type: Features\n    data:\n      - name: Policy as Code\n      - name: YAML Policies\n      - name: RBAC\n      - name: ABAC\n      - name: PBAC\n      - name: ReBAC\n      - name: Derived Roles\n      - name: Sub-Millisecond Decisions\n      - name: Stateless PDP\n      - name: REST and gRPC APIs\n      - name: AuthZEN Standard\n      - name: Query Plan Generation\n      - name: Audit Logs\n      - name: Policy Versioning\n      - name: Schema Validation\n      - name: Multiple Storage Backends\n      -\
  \ name: Sidecar Deployment\n      - name: Embedded PDP\n      - name: Apache 2.0 License\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Multi-Tenant SaaS Authorization\n      - name: API Authorization\n      - name: AI Agent Access Control\n      - name: MCP Server Security\n      - name: RAG Access Control\n      - name: Non-Human Identity Authorization\n      - name: Zero Trust Enforcement\n      - name: Compliance (SOC 2, HIPAA, GDPR, FedRAMP, PCI DSS)\n      - name: Fintech Permissions\n      - name: Healthcare Permissions\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Kong\n      - name: Gravitee\n      - name: Kubernetes\n      - name: Envoy\n      - name: Neo4j\n      - name: Trino\n      - name: Model Context Protocol\n      - name: Anthropic\n      - name: Chroma\n      - name: Pinecone\n      - name: Okta\n      - name: Microsoft Entra ID\n      - name: AWS Cognito\n      - name: Keycloak\n      - name: Auth0\n      - name: Clerk\n\
  \      - name: Stytch\n      - name: WorkOS\n      - name: Zitadel\n      - name: Prisma\n      - name: SQLAlchemy\n  - name: SDKs\n    type: SDKs\n    data:\n      - name: Go SDK\n      - name: Java SDK\n      - name: JavaScript / TypeScript SDK\n      - name: .NET SDK\n      - name: PHP SDK\n      - name: Python SDK\n      - name: Ruby SDK\n      - name: Rust SDK\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cerbos/refs/heads/main/apis.yml
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
