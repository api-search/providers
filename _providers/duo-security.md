---
api_count: 1
api_specs:
- filename: duo-admin-api-openapi.yml
  format: yaml
  label: Duo Admin API
  slug: duo-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/duo-security/refs/heads/main/openapi/duo-admin-api-openapi.yml
apis:
- description: The Duo Admin API provides programmatic access to manage users, groups, phones, hardware tokens, WebAuthn credentials, bypass codes, and bulk operations across a Duo Security tenant. Requests are auth
  name: Duo Admin API
  slug: duo-admin-api
common:
- title: ''
  type: Website
  url: https://duo.com
- title: ''
  type: Documentation
  url: https://duo.com/docs
- title: ''
  type: GitHub Organization
  url: https://github.com/duosecurity
created: '2026-03-25'
description: Duo Security is a multi-factor authentication and zero trust security platform from Cisco for securing access to applications and APIs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Duo Security
skills: []
slug: duo-security
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: duo-security\nname: Duo Security\ndescription: >-\n  Duo Security is a multi-factor authentication and zero trust security platform from Cisco for securing access to applications and APIs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Authentication\n  - MFA\n  - Zero Trust\n  - Identity\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/duo-security/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: duo-security:duo-admin-api\n    name: Duo Admin API\n    description: >-\n      The Duo Admin API provides programmatic access to manage users, groups,\n      phones, hardware tokens, WebAuthn credentials, bypass codes, and bulk\n      operations across a Duo Security tenant. Requests are authenticated using\n      HMAC-SHA1 signed HTTP Basic credentials derived from your integration key\n      and secret key.\n    humanURL: https://duo.com/docs/adminapi\n\
  \    baseURL: https://api-XXXXXXXX.duosecurity.com\n    tags:\n      - Authentication\n      - MFA\n      - Admin\n      - Identity\n    properties:\n      - type: Documentation\n        url: https://duo.com/docs/adminapi\n      - type: OpenAPI\n        url: openapi/duo-admin-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://duo.com\n  - type: Documentation\n    url: https://duo.com/docs\n  - type: GitHub Organization\n    url: https://github.com/duosecurity\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/duo-security/refs/heads/main/apis.yml
tags:
- Authentication
- MFA
- Zero Trust
- Identity
url: https://raw.githubusercontent.com/api-evangelist/duo-security/refs/heads/main/apis.yml
use_cases: []
---
