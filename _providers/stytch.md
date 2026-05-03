---
api_count: 2
api_specs:
- filename: stytch-consumer-openapi.yml
  format: yaml
  label: Stytch Consumer Authentication API
  slug: stytch-consumer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stytch/refs/heads/main/openapi/stytch-consumer-openapi.yml
- filename: stytch-b2b-openapi.yml
  format: yaml
  label: Stytch B2B Authentication API
  slug: stytch-b2b-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stytch/refs/heads/main/openapi/stytch-b2b-openapi.yml
apis:
- description: Stytch's Consumer API provides passwordless and password-based authentication for consumer-facing applications. Supports magic links, SMS/email OTP, OAuth social login, TOTP (authenticator apps), WebA
  name: Stytch Consumer Authentication API
  slug: stytch-consumer-api
- description: Stytch's B2B API provides authentication and identity management for organization-based SaaS applications. Supports multi-tenancy with Organizations and Members, SSO via SAML and OIDC, magic links, OT
  name: Stytch B2B Authentication API
  slug: stytch-b2b-api
capabilities:
- description: Unified capability for B2B identity and access management workflows. Combines Stytch's B2B API for organization creation, member management, SSO configuration, and session management. Used by SaaS pla
  name: Stytch B2B Identity Management
  slug: b2b-identity-management
- description: Unified capability for passwordless authentication workflows using Stytch's Consumer API. Combines magic links, OTP, and session management to deliver secure login flows without passwords. Used by con
  name: Stytch Passwordless Authentication
  slug: passwordless-authentication
common:
- title: ''
  type: Website
  url: https://stytch.com
- title: ''
  type: Documentation
  url: https://stytch.com/docs
- title: ''
  type: API Reference
  url: https://stytch.com/docs/api
- title: ''
  type: Sign Up
  url: https://app.stytch.com/register
- title: ''
  type: Portal
  url: https://app.stytch.com
- title: ''
  type: Authentication
  url: https://stytch.com/docs/guides/authentication
- title: ''
  type: Sessions
  url: https://stytch.com/docs/guides/sessions
- title: ''
  type: SDKs
  url: https://stytch.com/docs/sdks
- title: ''
  type: Pricing
  url: https://stytch.com/pricing
- title: ''
  type: Privacy Policy
  url: https://stytch.com/privacy
- title: ''
  type: Terms of Service
  url: https://stytch.com/terms
- title: ''
  type: Webhooks
  url: https://stytch.com/docs/guides/webhooks
- title: ''
  type: GitHub Organization
  url: https://github.com/stytchauth
- title: ''
  type: Postman Workspace
  url: https://www.postman.com/stytch/stytch-public-workspace/overview
- title: ''
  type: Node.js SDK
  url: https://github.com/stytchauth/stytch-node
- title: ''
  type: Python SDK
  url: https://github.com/stytchauth/stytch-python
- title: ''
  type: Java SDK
  url: https://github.com/stytchauth/stytch-java
- title: ''
  type: Go SDK
  url: https://github.com/stytchauth/stytch-go
- title: ''
  type: Ruby SDK
  url: https://github.com/stytchauth/stytch-ruby
- title: ''
  type: PHP SDK
  url: https://github.com/stytchauth/stytch-php
- title: ''
  type: Status
  url: https://status.stytch.com
- title: ''
  type: Blog
  url: https://stytch.com/blog
- title: ''
  type: Spectral Rules
  url: rules/stytch-rules.yml
- title: ''
  type: Naftiko Capability
  url: capabilities/passwordless-authentication.yaml
- title: ''
  type: Naftiko Capability
  url: capabilities/b2b-identity-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/stytch-vocabulary.yml
- title: ''
  type: JSON Schema
  url: json-schema/stytch-user-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/stytch-organization-schema.json
- title: ''
  type: JSON Structure
  url: json-structure/stytch-session-structure.json
- title: ''
  type: JSON-LD Context
  url: json-ld/stytch-context.jsonld
- title: ''
  type: Example
  url: examples/stytch-send-magic-link-example.json
- title: ''
  type: Example
  url: examples/stytch-create-organization-example.json
created: '2024-11-15'
description: Stytch is a company that specializes in providing secure and seamless authentication solutions for businesses. Their platform allows companies to integrate passwordless authentication methods such as magic links, SMS and email OTP, OAuth, TOTP, WebAuthn, and biometrics. Stytch offers both a Consumer API for end-user authentication and a B2B API for multi-tenant SaaS applications with organization management, SSO, and role-based access control.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Stytch Context
  property_count: 17
  slug: stytch-context
layout: provider
modified: '2026-05-02'
name: Stytch
rules:
- name: Stytch API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 5
  slug: stytch-rules
skills: []
slug: stytch
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stytch\nurl: https://raw.githubusercontent.com/api-evangelist/stytch/refs/heads/main/apis.yml\napis:\n  - aid: stytch:stytch-consumer-api\n    name: Stytch Consumer Authentication API\n    tags:\n      - Authentication\n      - Passwordless\n      - Magic Links\n      - OTP\n      - Consumer\n    humanURL: https://stytch.com/docs/api\n    properties:\n      - url: https://stytch.com/docs/api\n        type: Documentation\n      - url: https://stytch.com/docs/api/reference/library/overview\n        type: API Reference\n      - url: openapi/stytch-consumer-openapi.yml\n        type: OpenAPI\n    description: >-\n      Stytch's Consumer API provides passwordless and password-based authentication for\n      consumer-facing applications. Supports magic links, SMS/email OTP, OAuth social login,\n      TOTP (authenticator apps), WebAuthn (biometrics/passkeys), and session management.\n\n  - aid: stytch:stytch-b2b-api\n    name: Stytch B2B Authentication API\n    tags:\n      -\
  \ Authentication\n      - B2B\n      - SSO\n      - Multi-Tenant\n      - Organizations\n    humanURL: https://stytch.com/docs/b2b\n    properties:\n      - url: https://stytch.com/docs/b2b\n        type: Documentation\n      - url: https://stytch.com/docs/b2b/api/overview\n        type: API Reference\n      - url: openapi/stytch-b2b-openapi.yml\n        type: OpenAPI\n    description: >-\n      Stytch's B2B API provides authentication and identity management for organization-based\n      SaaS applications. Supports multi-tenancy with Organizations and Members, SSO via SAML\n      and OIDC, magic links, OTP, OAuth, and organization discovery flows.\n\nname: Stytch\ntags:\n  - Authentication\n  - Identity\n  - Passwordless\n  - Security\n  - Developer Tools\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-15'\nmodified: '2026-05-02'\nposition: Consuming\ndescription: >-\n  Stytch is a company that specializes\
  \ in providing secure and seamless authentication solutions\n  for businesses. Their platform allows companies to integrate passwordless authentication methods\n  such as magic links, SMS and email OTP, OAuth, TOTP, WebAuthn, and biometrics. Stytch offers\n  both a Consumer API for end-user authentication and a B2B API for multi-tenant SaaS applications\n  with organization management, SSO, and role-based access control.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - url: https://stytch.com\n    type: Website\n  - url: https://stytch.com/docs\n    type: Documentation\n  - url: https://stytch.com/docs/api\n    type: API Reference\n  - url: https://app.stytch.com/register\n    type: Sign Up\n  - url: https://app.stytch.com\n    type: Portal\n  - url: https://stytch.com/docs/guides/authentication\n    type: Authentication\n  - url: https://stytch.com/docs/guides/sessions\n    type: Sessions\n  - url: https://stytch.com/docs/sdks\n\
  \    type: SDKs\n  - url: https://stytch.com/pricing\n    type: Pricing\n  - url: https://stytch.com/privacy\n    type: Privacy Policy\n  - url: https://stytch.com/terms\n    type: Terms of Service\n  - url: https://stytch.com/docs/guides/webhooks\n    type: Webhooks\n  - url: https://github.com/stytchauth\n    type: GitHub Organization\n  - url: https://www.postman.com/stytch/stytch-public-workspace/overview\n    type: Postman Workspace\n  - url: https://github.com/stytchauth/stytch-node\n    type: Node.js SDK\n  - url: https://github.com/stytchauth/stytch-python\n    type: Python SDK\n  - url: https://github.com/stytchauth/stytch-java\n    type: Java SDK\n  - url: https://github.com/stytchauth/stytch-go\n    type: Go SDK\n  - url: https://github.com/stytchauth/stytch-ruby\n    type: Ruby SDK\n  - url: https://github.com/stytchauth/stytch-php\n    type: PHP SDK\n  - url: https://status.stytch.com\n    type: Status\n  - url: https://stytch.com/blog\n    type: Blog\n  - url: rules/stytch-rules.yml\n\
  \    type: Spectral Rules\n  - url: capabilities/passwordless-authentication.yaml\n    type: Naftiko Capability\n  - url: capabilities/b2b-identity-management.yaml\n    type: Naftiko Capability\n  - url: vocabulary/stytch-vocabulary.yml\n    type: Vocabulary\n  - url: json-schema/stytch-user-schema.json\n    type: JSON Schema\n  - url: json-schema/stytch-organization-schema.json\n    type: JSON Schema\n  - url: json-structure/stytch-session-structure.json\n    type: JSON Structure\n  - url: json-ld/stytch-context.jsonld\n    type: JSON-LD Context\n  - url: examples/stytch-send-magic-link-example.json\n    type: Example\n  - url: examples/stytch-create-organization-example.json\n    type: Example\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stytch/refs/heads/main/apis.yml
tags:
- Authentication
- Identity
- Passwordless
- Security
- Developer Tools
url: https://raw.githubusercontent.com/api-evangelist/stytch/refs/heads/main/apis.yml
use_cases: []
---
