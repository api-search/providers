---
api_count: 4
api_specs:
- filename: spiffe-workload-asyncapi.yml
  format: yaml
  label: SPIFFE Workload API
  slug: spiffe-workload-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/spiffe/refs/heads/main/asyncapi/spiffe-workload-asyncapi.yml
- filename: spiffe-federation-openapi.yml
  format: yaml
  label: SPIFFE Federation API
  slug: spiffe-federation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spiffe/refs/heads/main/openapi/spiffe-federation-openapi.yml
apis:
- description: 'The SPIFFE Workload API is a gRPC-based interface through which workloads request and receive SPIFFE Verifiable Identity Documents (SVIDs) including X.509-SVIDs and JWT-SVIDs, as well as trust bundle '
  name: SPIFFE Workload API
  slug: spiffe-workload-api
- description: The SPIFFE X.509 SVID (SPIFFE Verifiable Identity Document) is a standard for encoding SPIFFE identities into X.509 certificates. The Subject Alternative Name field carries the SPIFFE ID URI, enabling
  name: SPIFFE X.509 SVID
  slug: spiffe-x509-svid-api
- description: The SPIFFE JWT SVID standard defines a format for encoding SPIFFE identities as JSON Web Tokens. JWT-SVIDs are used in scenarios where X.509 certificates are not practical, such as HTTP header-based a
  name: SPIFFE JWT SVID
  slug: spiffe-jwt-svid-api
- description: The SPIFFE Federation API defines how SPIFFE trust domains exchange trust bundle information to enable cross-domain workload authentication. It specifies the SPIFFE Trust Domain and Bundle endpoint fo
  name: SPIFFE Federation API
  slug: spiffe-federation-api
asyncapis:
- description: 'The SPIFFE Workload API is a gRPC streaming interface through which workloads request and receive SPIFFE Verifiable Identity Documents (SVIDs) and trust bundle updates. Workloads subscribe to the API '
  name: SPIFFE Workload API Events
  slug: spiffe-workload-asyncapi
common:
- title: ''
  type: JSONSchema
  url: json-schema/spiffe-svid-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/spiffe-context.jsonld
- title: ''
  type: Website
  url: https://spiffe.io/
- title: ''
  type: Documentation
  url: https://spiffe.io/docs/latest/
- title: ''
  type: Getting Started
  url: https://spiffe.io/docs/latest/spiffe-about/spiffe-concepts/
- title: ''
  type: GitHub Organization
  url: https://github.com/spiffe
- title: ''
  type: GitHubRepository
  url: https://github.com/spiffe/spiffe
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
  type: Security
  url: https://github.com/spiffe/spiffe/blob/main/SECURITY.md
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/spiffe
created: '2025'
description: Secure Production Identity Framework for Everyone (SPIFFE) is a set of open-source standards for securely identifying software systems in dynamic and heterogeneous environments through platform-agnostic, cryptographic identities. SPIFFE defines the SPIFFE ID URI format, the X.509 SVID and JWT SVID identity document formats, and the Workload API for issuing and rotating identities without secrets or passwords.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Spiffe Context
  property_count: 7
  slug: spiffe-context
layout: provider
modified: '2026-03-18'
name: SPIFFE
skills: []
slug: spiffe
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spiffe\nname: SPIFFE\ndescription: >-\n  Secure Production Identity Framework for Everyone (SPIFFE) is a set of\n  open-source standards for securely identifying software systems in dynamic\n  and heterogeneous environments through platform-agnostic, cryptographic\n  identities. SPIFFE defines the SPIFFE ID URI format, the X.509 SVID and\n  JWT SVID identity document formats, and the Workload API for issuing and\n  rotating identities without secrets or passwords.\nurl: https://spiffe.io/\ntags:\n  - Authentication\n  - Cloud Native\n  - Graduated\n  - Identity\n  - Security\n  - Zero Trust\ncreated: '2025'\nmodified: '2026-03-18'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: spiffe:spiffe-workload-api\n    name: SPIFFE Workload API\n    description: >-\n      The SPIFFE Workload API is a gRPC-based interface through which workloads\n      request and receive SPIFFE Verifiable Identity Documents (SVIDs) including\n      X.509-SVIDs and JWT-SVIDs, as well\
  \ as trust bundle updates. It enables\n      software to obtain cryptographic identities at runtime without requiring\n      secrets to be embedded in configuration or code.\n    humanURL: https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Workload_API.md\n    properties:\n      - type: Documentation\n        url: https://spiffe.io/docs/latest/spiffe-about/spiffe-concepts/\n      - type: Reference\n        url: https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Workload_API.md\n      - type: AsyncAPI\n        url: asyncapi/spiffe-workload-asyncapi.yml\n      - type: GitHubRepository\n        url: https://github.com/spiffe/spiffe\n    tags:\n      - gRPC\n      - Identity\n      - JWT\n      - Workload\n      - X.509\n  - aid: spiffe:spiffe-x509-svid-api\n    name: SPIFFE X.509 SVID\n    description: >-\n      The SPIFFE X.509 SVID (SPIFFE Verifiable Identity Document) is a standard\n      for encoding SPIFFE identities into X.509 certificates. The Subject\n      Alternative\
  \ Name field carries the SPIFFE ID URI, enabling mutual TLS\n      authentication between workloads using standard X.509 certificate\n      validation libraries.\n    humanURL: https://github.com/spiffe/spiffe/blob/main/standards/X509-SVID.md\n    properties:\n      - type: Documentation\n        url: https://spiffe.io/docs/latest/spiffe-about/svid/\n      - type: Reference\n        url: https://github.com/spiffe/spiffe/blob/main/standards/X509-SVID.md\n      - type: GitHubRepository\n        url: https://github.com/spiffe/spiffe\n    tags:\n      - Certificate\n      - Identity\n      - mTLS\n      - Security\n      - X.509\n  - aid: spiffe:spiffe-jwt-svid-api\n    name: SPIFFE JWT SVID\n    description: >-\n      The SPIFFE JWT SVID standard defines a format for encoding SPIFFE\n      identities as JSON Web Tokens. JWT-SVIDs are used in scenarios where\n      X.509 certificates are not practical, such as HTTP header-based\n      authentication between services or for passing identity\
  \ across\n      trust domain boundaries.\n    humanURL: https://github.com/spiffe/spiffe/blob/main/standards/JWT-SVID.md\n    properties:\n      - type: Documentation\n        url: https://spiffe.io/docs/latest/spiffe-about/svid/\n      - type: Reference\n        url: https://github.com/spiffe/spiffe/blob/main/standards/JWT-SVID.md\n      - type: GitHubRepository\n        url: https://github.com/spiffe/spiffe\n    tags:\n      - Authentication\n      - Identity\n      - JWT\n      - Security\n  - aid: spiffe:spiffe-federation-api\n    name: SPIFFE Federation API\n    description: >-\n      The SPIFFE Federation API defines how SPIFFE trust domains exchange\n      trust bundle information to enable cross-domain workload authentication.\n      It specifies the SPIFFE Trust Domain and Bundle endpoint format, allowing\n      systems in different trust domains to establish mutual trust and authenticate\n      workloads across organizational or infrastructure boundaries.\n    humanURL: https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Trust_Domain_and_Bundle.md\n\
  \    properties:\n      - type: Documentation\n        url: https://spiffe.io/docs/latest/spiffe-about/spiffe-concepts/\n      - type: Reference\n        url: https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Trust_Domain_and_Bundle.md\n      - type: OpenAPI\n        url: openapi/spiffe-federation-openapi.yml\n      - type: GitHubRepository\n        url: https://github.com/spiffe/spiffe\n    tags:\n      - Cross-Domain\n      - Federation\n      - Identity\n      - Security\n      - Trust Domain\ncommon:\n  - type: JSONSchema\n    url: json-schema/spiffe-svid-schema.json\n  - type: JSON-LD\n    url: json-ld/spiffe-context.jsonld\n  - type: Website\n    url: https://spiffe.io/\n  - type: Documentation\n    url: https://spiffe.io/docs/latest/\n  - type: Getting Started\n    url: https://spiffe.io/docs/latest/spiffe-about/spiffe-concepts/\n  - type: GitHub Organization\n    url: https://github.com/spiffe\n  - type: GitHubRepository\n    url: https://github.com/spiffe/spiffe\n  -\
  \ type: Community\n    url: https://spiffe.io/community/\n  - type: Slack\n    url: https://slack.spiffe.io\n  - type: Blog\n    url: https://spiffe.io/blog/\n  - type: Security\n    url: https://github.com/spiffe/spiffe/blob/main/SECURITY.md\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/spiffe\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spiffe/refs/heads/main/apis.yml
tags:
- Authentication
- Cloud Native
- Graduated
- Identity
- Security
- Zero Trust
url: https://spiffe.io/
use_cases: []
---
