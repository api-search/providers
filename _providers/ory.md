---
api_count: 4
api_specs:
- filename: ory-hydra-openapi.json
  format: json
  label: Ory Hydra
  slug: hydra
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ory/refs/heads/main/openapi/ory-hydra-openapi.json
- filename: ory-kratos-openapi.json
  format: json
  label: Ory Kratos
  slug: kratos
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ory/refs/heads/main/openapi/ory-kratos-openapi.json
- filename: ory-keto-openapi.json
  format: json
  label: Ory Keto
  slug: keto
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ory/refs/heads/main/openapi/ory-keto-openapi.json
- filename: ory-oathkeeper-openapi.json
  format: json
  label: Ory Oathkeeper
  slug: oathkeeper
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ory/refs/heads/main/openapi/ory-oathkeeper-openapi.json
apis:
- description: Ory Hydra is an OAuth 2.0 and OpenID Connect server. It implements OAuth 2.0 authorization, OpenID Connect Core 1.0, and OpenID Connect Discovery for issuing and managing access tokens, refresh tokens
  name: Ory Hydra
  slug: hydra
- description: 'Ory Kratos is an identity and user management system. It handles registration, login, multi-factor authentication, account recovery, verification, profile management, and identity schemas with strong '
  name: Ory Kratos
  slug: kratos
- description: Ory Keto is a permission and authorization server inspired by Google Zanzibar. It provides relationship-based access control (ReBAC), role-based access control (RBAC), and access control list (ACL) ch
  name: Ory Keto
  slug: keto
- description: Ory Oathkeeper is an identity and access proxy that authenticates, authorizes, and mutates incoming HTTP(S) requests using configurable access rules backed by Hydra, Kratos, and Keto.
  name: Ory Oathkeeper
  slug: oathkeeper
common:
- title: ''
  type: Website
  url: https://www.ory.sh
- title: ''
  type: Documentation
  url: https://www.ory.sh/docs/
- title: ''
  type: GitHub Organization
  url: https://github.com/ory
- title: ''
  type: Blog
  url: https://www.ory.sh/blog/
created: '2026-03-25'
description: Ory is an open source identity infrastructure platform providing OAuth2 and OpenID Connect (Hydra), identity and user management (Kratos), permissions and authorization (Keto), and a reverse proxy with policy enforcement (Oathkeeper).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Ory
skills: []
slug: ory
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ory\nname: Ory\ndescription: >-\n  Ory is an open source identity infrastructure platform providing OAuth2 and\n  OpenID Connect (Hydra), identity and user management (Kratos), permissions\n  and authorization (Keto), and a reverse proxy with policy enforcement\n  (Oathkeeper).\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Authentication\n  - Authorization\n  - Identity\n  - OAuth2\n  - OpenID Connect\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ory/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: ory:hydra\n    name: Ory Hydra\n    description: >-\n      Ory Hydra is an OAuth 2.0 and OpenID Connect server. It implements OAuth\n      2.0 authorization, OpenID Connect Core 1.0, and OpenID Connect Discovery\n      for issuing and managing access tokens, refresh tokens, ID tokens, and\n      OAuth2 clients.\n \
  \   humanURL: https://www.ory.sh/hydra/\n    tags:\n      - OAuth2\n      - OpenID Connect\n      - Authentication\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/ory/refs/heads/main/openapi/ory-hydra-openapi.json\n      - type: Documentation\n        url: https://www.ory.sh/docs/hydra/\n      - type: GitHub Repository\n        url: https://github.com/ory/hydra\n  - aid: ory:kratos\n    name: Ory Kratos\n    description: >-\n      Ory Kratos is an identity and user management system. It handles\n      registration, login, multi-factor authentication, account recovery,\n      verification, profile management, and identity schemas with strong\n      security defaults.\n    humanURL: https://www.ory.sh/kratos/\n    tags:\n      - Identity\n      - Authentication\n      - User Management\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/ory/refs/heads/main/openapi/ory-kratos-openapi.json\n\
  \      - type: Documentation\n        url: https://www.ory.sh/docs/kratos/\n      - type: GitHub Repository\n        url: https://github.com/ory/kratos\n  - aid: ory:keto\n    name: Ory Keto\n    description: >-\n      Ory Keto is a permission and authorization server inspired by Google\n      Zanzibar. It provides relationship-based access control (ReBAC), role-based\n      access control (RBAC), and access control list (ACL) checks at scale.\n    humanURL: https://www.ory.sh/keto/\n    tags:\n      - Authorization\n      - Permissions\n      - Access Control\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/ory/refs/heads/main/openapi/ory-keto-openapi.json\n      - type: Documentation\n        url: https://www.ory.sh/docs/keto/\n      - type: GitHub Repository\n        url: https://github.com/ory/keto\n  - aid: ory:oathkeeper\n    name: Ory Oathkeeper\n    description: >-\n      Ory Oathkeeper is an identity and access\
  \ proxy that authenticates,\n      authorizes, and mutates incoming HTTP(S) requests using configurable\n      access rules backed by Hydra, Kratos, and Keto.\n    humanURL: https://www.ory.sh/oathkeeper/\n    tags:\n      - Reverse Proxy\n      - Authentication\n      - Authorization\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/ory/refs/heads/main/openapi/ory-oathkeeper-openapi.json\n      - type: Documentation\n        url: https://www.ory.sh/docs/oathkeeper/\n      - type: GitHub Repository\n        url: https://github.com/ory/oathkeeper\ncommon:\n  - type: Website\n    url: https://www.ory.sh\n  - type: Documentation\n    url: https://www.ory.sh/docs/\n  - type: GitHub Organization\n    url: https://github.com/ory\n  - type: Blog\n    url: https://www.ory.sh/blog/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ory/refs/heads/main/apis.yml
tags:
- Authentication
- Authorization
- Identity
- OAuth2
- OpenID Connect
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/ory/refs/heads/main/apis.yml
use_cases: []
---
