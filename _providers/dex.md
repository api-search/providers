---
api_count: 1
apis:
- description: gRPC management API for Dex covering OAuth2 client lifecycle (Create, Get, Update, Delete, List), password management (Create, Update, Delete, List, Verify), identity provider connector management (Cr
  name: Dex gRPC API
  slug: grpc-api
common:
- title: ''
  type: Website
  url: https://dexidp.io/
- title: ''
  type: Documentation
  url: https://dexidp.io/docs/
- title: ''
  type: GitHub Organization
  url: https://github.com/dexidp
- title: ''
  type: Repository
  url: https://github.com/dexidp/dex
- title: ''
  type: License
  url: https://github.com/dexidp/dex/blob/master/LICENSE
created: '2025-01-01'
description: A federated OpenID Connect provider that connects to other identity providers through connectors, enabling authentication for applications without handling passwords directly. Dex acts as a portal to other identity providers through connectors, making it easy to implement SSO across multiple providers. Dex is a single Go binary with pluggable storage and ships with a gRPC management API (api/v2/api.proto) for managing OAuth2 clients, passwords, connectors, and refresh tokens, alongside the standard set of OIDC endpoints.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Dex
skills: []
slug: dex
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dex\nname: Dex\ndescription: >-\n  A federated OpenID Connect provider that connects to other identity providers\n  through connectors, enabling authentication for applications without handling\n  passwords directly. Dex acts as a portal to other identity providers through\n  connectors, making it easy to implement SSO across multiple providers. Dex is\n  a single Go binary with pluggable storage and ships with a gRPC management API\n  (api/v2/api.proto) for managing OAuth2 clients, passwords, connectors, and\n  refresh tokens, alongside the standard set of OIDC endpoints.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Authentication\n  - Connectors\n  - Federation\n  - gRPC\n  - Identity Provider\n  - LDAP\n  - OAuth 2.0\n  - OIDC\n  - OpenID Connect\n  - SAML\n  - Single Sign-On\n  - SSO\nurl: https://dexidp.io/\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: dex:grpc-api\n\
  \    name: Dex gRPC API\n    description: >-\n      gRPC management API for Dex covering OAuth2 client lifecycle (Create,\n      Get, Update, Delete, List), password management (Create, Update, Delete,\n      List, Verify), identity provider connector management (Create, Update,\n      Delete, List), refresh token listing and revocation, OpenID Connect\n      discovery retrieval, and version reporting. The canonical schema lives\n      in api/v2/api.proto in the dexidp/dex repository.\n    humanURL: https://dexidp.io/docs/configuration/api/\n    baseURL: https://dexidp.io\n    tags:\n      - Authentication\n      - gRPC\n      - Identity\n      - Management API\n      - OIDC\n    properties:\n      - type: Documentation\n        url: https://dexidp.io/docs/configuration/api/\n      - type: SourceCode\n        url: https://github.com/dexidp/dex/blob/master/api/v2/api.proto\n      - type: Repository\n        url: https://github.com/dexidp/dex\ncommon:\n  - type: Website\n    url: https://dexidp.io/\n\
  \  - type: Documentation\n    url: https://dexidp.io/docs/\n  - type: GitHub Organization\n    url: https://github.com/dexidp\n  - type: Repository\n    url: https://github.com/dexidp/dex\n  - type: License\n    url: https://github.com/dexidp/dex/blob/master/LICENSE\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dex/refs/heads/main/apis.yml
tags:
- Authentication
- Connectors
- Federation
- gRPC
- Identity Provider
- LDAP
- OAuth 2.0
- OIDC
- OpenID Connect
- SAML
- Single Sign-On
- SSO
url: https://dexidp.io/
use_cases: []
---
