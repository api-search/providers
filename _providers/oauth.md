---
api_count: 1
api_specs:
- filename: oauth-token-endpoint.yml
  format: yaml
  label: OAuth 2.0 Authorization Server API
  slug: oauth-2-authorization-server
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oauth/refs/heads/main/openapi/oauth-token-endpoint.yml
apis:
- description: API specification for an OAuth 2.0 authorization server implementing the authorization endpoint, token endpoint, and token revocation endpoint as defined in RFC 6749, RFC 6750, and RFC 7009.
  name: OAuth 2.0 Authorization Server API
  slug: oauth-2-authorization-server
common:
- title: ''
  type: Website
  url: https://oauth.net/
- title: ''
  type: Documentation
  url: https://oauth.net/2/
- title: ''
  type: Reference
  url: https://datatracker.ietf.org/doc/html/rfc6749
created: '2025-01-01'
description: OAuth is an open authorization framework that enables third-party applications to access user resources without exposing credentials. It provides a secure, token-based delegation mechanism widely used across the web for granting limited access to APIs and services on behalf of users.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Oauth Context
  property_count: 28
  slug: oauth-context
layout: provider
modified: '2026-04-28'
name: OAuth
skills: []
slug: oauth
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oauth\nname: OAuth\ndescription: >-\n  OAuth is an open authorization framework that enables third-party applications\n  to access user resources without exposing credentials. It provides a secure,\n  token-based delegation mechanism widely used across the web for granting\n  limited access to APIs and services on behalf of users.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Access Control\n  - Authorization\n  - OAuth\n  - Security\n  - Tokens\nurl: https://raw.githubusercontent.com/api-evangelist/oauth/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: oauth:oauth-2-authorization-server\n    name: OAuth 2.0 Authorization Server API\n    description: >-\n      API specification for an OAuth 2.0 authorization server implementing the\n      authorization endpoint, token endpoint, and token revocation endpoint as\n      defined in RFC 6749, RFC\
  \ 6750, and RFC 7009.\n    humanURL: https://oauth.net/2/\n    tags:\n      - Authorization\n      - OAuth 2.0\n    properties:\n      - type: Documentation\n        url: https://oauth.net/2/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/oauth/refs/heads/main/openapi/oauth-token-endpoint.yml\n      - type: JSON Schema\n        url: https://raw.githubusercontent.com/api-evangelist/oauth/refs/heads/main/json-schema/oauth-authorization-request.json\n      - type: JSON Schema\n        url: https://raw.githubusercontent.com/api-evangelist/oauth/refs/heads/main/json-schema/oauth-token-response.json\n      - type: JSON Schema\n        url: https://raw.githubusercontent.com/api-evangelist/oauth/refs/heads/main/json-schema/oauth-error-response.json\n      - type: JSON-LD Context\n        url: https://raw.githubusercontent.com/api-evangelist/oauth/refs/heads/main/json-ld/oauth-context.jsonld\ncommon:\n  - type: Website\n    url: https://oauth.net/\n  - type:\
  \ Documentation\n    url: https://oauth.net/2/\n  - type: Reference\n    url: https://datatracker.ietf.org/doc/html/rfc6749\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oauth/refs/heads/main/apis.yml
tags:
- Access Control
- Authorization
- OAuth
- Security
- Tokens
url: https://raw.githubusercontent.com/api-evangelist/oauth/refs/heads/main/apis.yml
use_cases: []
---
