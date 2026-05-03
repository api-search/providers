---
api_count: 4
api_specs:
- filename: spire-workload-asyncapi.yml
  format: yaml
  label: SPIRE Workload API
  slug: spire-workload-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/spire/refs/heads/main/asyncapi/spire-workload-asyncapi.yml
- filename: spire-health-openapi.yml
  format: yaml
  label: SPIRE Agent API
  slug: spire-agent-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spire/refs/heads/main/openapi/spire-health-openapi.yml
- filename: spire-oidc-discovery-openapi.yml
  format: yaml
  label: SPIRE OIDC Discovery API
  slug: spire-oidc-discovery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spire/refs/heads/main/openapi/spire-oidc-discovery-openapi.yml
apis:
- description: The SPIRE Agent exposes the SPIFFE Workload API as a Unix domain socket, allowing workloads running on the same node to request their X.509-SVIDs and JWT-SVIDs without requiring any credentials. The W
  name: SPIRE Workload API
  slug: spire-workload-api
- description: The SPIRE Server exposes a gRPC API used by administrators and the SPIRE Agent to manage registration entries, node attestation, bundle federation, and server health. It allows creating and managing w
  name: SPIRE Server API
  slug: spire-server-api
- description: The SPIRE Agent runs on each node and handles workload attestation, caching SVIDs, and serving the Workload API. It exposes a health check endpoint and communicates with the SPIRE Server via node atte
  name: SPIRE Agent API
  slug: spire-agent-api
- description: SPIRE includes an OIDC Discovery Provider that serves an OpenID Connect discovery document and JSON Web Key Set (JWKS) endpoint, enabling workloads to present JWT-SVIDs to systems that support standar
  name: SPIRE OIDC Discovery API
  slug: spire-oidc-discovery-api
asyncapis:
- description: 'The SPIRE Workload API is a gRPC streaming interface exposed by the SPIRE Agent on each node, through which workloads request and receive SPIFFE Verifiable Identity Documents (SVIDs) and trust bundle '
  name: SPIRE Workload API Events
  slug: spire-workload-asyncapi
common:
- title: ''
  type: Website
  url: https://spiffe.io/
- title: ''
  type: Documentation
  url: https://spiffe.io/docs/latest/
- title: ''
  type: Getting Started
  url: https://spiffe.io/docs/latest/try/getting-started-k8s/
- title: ''
  type: GitHub Organization
  url: https://github.com/spiffe
- title: ''
  type: GitHubRepository
  url: https://github.com/spiffe/spire
- title: ''
  type: Community
  url: https://spiffe.io/community/
- title: ''
  type: Slack
  url: https://slack.spiffe.io
- title: ''
  type: Blog
  url: https://spiffe.io/blog/
- title: ''
  type: Change Log
  url: https://github.com/spiffe/spire/blob/main/CHANGELOG.md
- title: ''
  type: Security
  url: https://github.com/spiffe/spire/blob/main/SECURITY.md
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/spiffe
- title: ''
  type: JSONSchema
  url: json-schema/spire-svid-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/spire-registration-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/spire-context.jsonld
created: '2025'
description: SPIRE (SPIFFE Runtime Environment) is the reference implementation of the SPIFFE standard, providing a toolchain for establishing trust between software systems across a wide variety of hosting platforms through automated attestation and workload identity distribution. SPIRE manages a certificate authority, performs node and workload attestation, and issues SVIDs to workloads through the SPIFFE Workload API.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Spire Context
  property_count: 9
  slug: spire-context
layout: provider
modified: '2026-03-18'
name: SPIRE
skills: []
slug: spire
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spire\nname: SPIRE\ndescription: >-\n  SPIRE (SPIFFE Runtime Environment) is the reference implementation of the\n  SPIFFE standard, providing a toolchain for establishing trust between software\n  systems across a wide variety of hosting platforms through automated\n  attestation and workload identity distribution. SPIRE manages a certificate\n  authority, performs node and workload attestation, and issues SVIDs to\n  workloads through the SPIFFE Workload API.\nurl: https://spiffe.io/docs/latest/spire-about/\ntags:\n  - Authentication\n  - Cloud Native\n  - Graduated\n  - Identity\n  - Security\n  - Zero Trust\ncreated: '2025'\nmodified: '2026-03-18'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: spire:spire-workload-api\n    name: SPIRE Workload API\n    description: >-\n      The SPIRE Agent exposes the SPIFFE Workload API as a Unix domain socket,\n      allowing workloads running on the same node to request their X.509-SVIDs\n      and JWT-SVIDs without\
  \ requiring any credentials. The Workload API also\n      delivers trust bundle updates so that workloads can verify the identity\n      of other workloads.\n    humanURL: https://spiffe.io/docs/latest/spire-about/spire-concepts/\n    properties:\n      - type: Documentation\n        url: https://spiffe.io/docs/latest/spire-about/spire-concepts/\n      - type: Reference\n        url: https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Workload_API.md\n      - type: AsyncAPI\n        url: asyncapi/spire-workload-asyncapi.yml\n      - type: GitHubRepository\n        url: https://github.com/spiffe/spire\n    tags:\n      - gRPC\n      - Identity\n      - JWT\n      - Workload\n      - X.509\n  - aid: spire:spire-server-api\n    name: SPIRE Server API\n    description: >-\n      The SPIRE Server exposes a gRPC API used by administrators and the SPIRE\n      Agent to manage registration entries, node attestation, bundle federation,\n      and server health. It allows creating and managing\
  \ workload registration\n      entries that define the SPIFFE IDs issued to workloads matching specified\n      selectors, and supports federation with external SPIFFE trust domains.\n    humanURL: https://spiffe.io/docs/latest/deploying/spire_server/\n    properties:\n      - type: Documentation\n        url: https://spiffe.io/docs/latest/deploying/spire_server/\n      - type: Reference\n        url: https://github.com/spiffe/spire-api-sdk\n      - type: JSONSchema\n        url: json-schema/spire-registration-schema.json\n      - type: GitHubRepository\n        url: https://github.com/spiffe/spire-api-sdk\n    tags:\n      - Administration\n      - Attestation\n      - gRPC\n      - Registration\n      - Server\n  - aid: spire:spire-agent-api\n    name: SPIRE Agent API\n    description: >-\n      The SPIRE Agent runs on each node and handles workload attestation,\n      caching SVIDs, and serving the Workload API. It exposes a health check\n      endpoint and communicates with the SPIRE\
  \ Server via node attestation to\n      establish its own identity before issuing identities to workloads.\n    humanURL: https://spiffe.io/docs/latest/deploying/spire_agent/\n    properties:\n      - type: Documentation\n        url: https://spiffe.io/docs/latest/deploying/spire_agent/\n      - type: Reference\n        url: https://spiffe.io/docs/latest/deploying/spire_agent/\n      - type: GitHubRepository\n        url: https://github.com/spiffe/spire\n      - type: OpenAPI\n        url: openapi/spire-health-openapi.yml\n    tags:\n      - Agent\n      - Attestation\n      - Identity\n      - Node\n      - Security\n  - aid: spire:spire-oidc-discovery-api\n    name: SPIRE OIDC Discovery API\n    description: >-\n      SPIRE includes an OIDC Discovery Provider that serves an OpenID Connect\n      discovery document and JSON Web Key Set (JWKS) endpoint, enabling\n      workloads to present JWT-SVIDs to systems that support standard OIDC\n      token validation. This allows SPIRE-issued\
  \ identities to be used with\n      cloud provider IAM systems such as AWS, GCP, and Azure.\n    humanURL: https://spiffe.io/docs/latest/keyless/oidc-federation-aws/\n    properties:\n      - type: Documentation\n        url: https://spiffe.io/docs/latest/keyless/oidc-federation-aws/\n      - type: GitHubRepository\n        url: https://github.com/spiffe/spire/tree/main/support/oidc-discovery-provider\n      - type: OpenAPI\n        url: openapi/spire-oidc-discovery-openapi.yml\n    tags:\n      - Cloud\n      - Federation\n      - Identity\n      - JWT\n      - OIDC\ncommon:\n  - type: Website\n    url: https://spiffe.io/\n  - type: Documentation\n    url: https://spiffe.io/docs/latest/\n  - type: Getting Started\n    url: https://spiffe.io/docs/latest/try/getting-started-k8s/\n  - type: GitHub Organization\n    url: https://github.com/spiffe\n  - type: GitHubRepository\n    url: https://github.com/spiffe/spire\n  - type: Community\n    url: https://spiffe.io/community/\n  - type: Slack\n\
  \    url: https://slack.spiffe.io\n  - type: Blog\n    url: https://spiffe.io/blog/\n  - type: Change Log\n    url: https://github.com/spiffe/spire/blob/main/CHANGELOG.md\n  - type: Security\n    url: https://github.com/spiffe/spire/blob/main/SECURITY.md\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/spiffe\n  - type: JSONSchema\n    url: json-schema/spire-svid-schema.json\n  - type: JSONSchema\n    url: json-schema/spire-registration-schema.json\n  - type: JSON-LD\n    url: json-ld/spire-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spire/refs/heads/main/apis.yml
tags:
- Authentication
- Cloud Native
- Graduated
- Identity
- Security
- Zero Trust
url: https://spiffe.io/docs/latest/spire-about/
use_cases: []
---
