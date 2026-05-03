---
api_count: 1
api_specs:
- filename: oidc.yml
  format: yaml
  label: OpenID Connect API
  slug: openid-connect
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oidc/refs/heads/main/openapi/oidc.yml
apis:
- description: Core OpenID Connect API endpoints for authentication and identity, including discovery, authorization, token exchange, and user information.
  name: OpenID Connect API
  slug: openid-connect
common:
- title: ''
  type: Website
  url: https://openid.net/
- title: ''
  type: Documentation
  url: https://openid.net/developers/specs/
- title: ''
  type: Reference
  url: https://openid.net/specs/openid-connect-core-1_0.html
created: '2025-01-01'
description: OpenID Connect (OIDC) is an identity layer built on top of OAuth 2.0 that enables clients to verify the identity of end-users based on authentication performed by an authorization server. It provides a standardized way to obtain basic profile information about users through RESTful endpoints including discovery, authorization, token, userinfo, and JWKS.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: OIDC
skills: []
slug: oidc
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oidc\nname: OIDC\ndescription: >-\n  OpenID Connect (OIDC) is an identity layer built on top of OAuth 2.0 that\n  enables clients to verify the identity of end-users based on authentication\n  performed by an authorization server. It provides a standardized way to\n  obtain basic profile information about users through RESTful endpoints\n  including discovery, authorization, token, userinfo, and JWKS.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Authentication\n  - Identity\n  - JWT\n  - OAuth\n  - OIDC\n  - OpenID Connect\nurl: https://raw.githubusercontent.com/api-evangelist/oidc/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: oidc:openid-connect\n    name: OpenID Connect API\n    description: >-\n      Core OpenID Connect API endpoints for authentication and identity,\n      including discovery, authorization, token exchange, and user\
  \ information.\n    humanURL: https://openid.net/specs/openid-connect-core-1_0.html\n    tags:\n      - Authentication\n      - Identity\n      - OIDC\n    properties:\n      - type: Documentation\n        url: https://openid.net/specs/openid-connect-core-1_0.html\n      - type: OpenAPI\n        url: openapi/oidc.yml\ncommon:\n  - type: Website\n    url: https://openid.net/\n  - type: Documentation\n    url: https://openid.net/developers/specs/\n  - type: Reference\n    url: https://openid.net/specs/openid-connect-core-1_0.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oidc/refs/heads/main/apis.yml
tags:
- Authentication
- Identity
- JWT
- OAuth
- OIDC
- OpenID Connect
url: https://raw.githubusercontent.com/api-evangelist/oidc/refs/heads/main/apis.yml
use_cases: []
---
