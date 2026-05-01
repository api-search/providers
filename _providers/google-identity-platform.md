---
api_count: 3
api_specs:
- filename: identity-toolkit-openapi.yml
  format: yaml
  label: Identity Toolkit API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-identity-platform/refs/heads/main/openapi/identity-toolkit-openapi.yml
apis:
- description: 'The Identity Toolkit API (v3) provides REST endpoints for managing user authentication in Google Identity Platform. It supports creating and signing in users with email/password, phone, and federated '
  name: Identity Toolkit API
  slug: ''
- description: The Tenant Management API enables developers to create and manage tenants for multi-tenant Identity Platform configurations. Each tenant can have its own set of identity providers, authentication sett
  name: Identity Platform Tenant Management API
  slug: ''
- description: The OAuth Configuration API allows developers to programmatically manage OAuth identity provider configurations for Identity Platform projects. It supports configuring Google, Facebook, Apple, Microso
  name: Identity Platform OAuth Configuration API
  slug: ''
common:
- title: ''
  type: GettingStarted
  url: https://cloud.google.com/identity-platform/docs/quickstarts
- title: ''
  type: Pricing
  url: https://cloud.google.com/identity-platform/pricing
- title: ''
  type: Authentication
  url: https://cloud.google.com/identity-platform/docs/concepts
- title: ''
  type: Console
  url: https://console.cloud.google.com/customer-identity
- title: ''
  type: SDKs
  url: https://cloud.google.com/identity-platform/docs/reference/libraries
- title: ''
  type: Support
  url: https://cloud.google.com/identity-platform/docs/support
- title: ''
  type: Status
  url: https://status.cloud.google.com
- title: ''
  type: JSON-LD
  url: json-ld/google-identity-platform-context.jsonld
created: '2026-03-13'
description: Google Identity Platform provides authentication and identity management APIs that enable developers to add sign-in, user management, and multi-tenancy capabilities to applications using industry-standard protocols including OAuth 2.0, OpenID Connect, and SAML.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Google Identity Platform Context
  property_count: 3
  slug: google-identity-platform-context
layout: provider
modified: '2026-04-28'
name: Google Identity Platform
skills: []
slug: google-identity-platform
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-identity-platform\nname: Google Identity Platform\ndescription: Google Identity Platform provides authentication and identity management APIs that enable developers to add sign-in, user management, and multi-tenancy capabilities to applications using industry-standard protocols including OAuth 2.0, OpenID Connect, and SAML.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/google-identity-platform/refs/heads/main/apis.yml\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Authentication\n  - Google Cloud\n  - Identity\n  - Multi-Tenancy\n  - OAuth\n  - OpenID Connect\n  - SAML\napis:\n  - name: Identity Toolkit API\n    description: >-\n      The Identity Toolkit API (v3) provides REST endpoints for managing user\n      authentication in Google Identity Platform. It supports creating and signing\n      in users with email/password,\
  \ phone, and federated identity providers. The\n      API handles token verification, password resets, email verification, account\n      linking, and multi-factor authentication enrollment and sign-in.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/identity-platform/docs/reference/rest\n    baseURL: https://identitytoolkit.googleapis.com\n    tags:\n      - Authentication\n      - Identity\n      - Sign-In\n      - Users\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/identity-platform/docs/reference/rest\n      - type: OpenAPI\n        url: openapi/identity-toolkit-openapi.yml\n      - type: JSONSchema\n        url: json-schema/google-identity-platform-user-schema.json\n  - name: Identity Platform Tenant Management API\n    description: >-\n      The Tenant Management API enables developers to create and manage tenants\n      for multi-tenant Identity Platform configurations.\
  \ Each tenant can have its\n      own set of identity providers, authentication settings, and user pools,\n      allowing SaaS applications to isolate authentication for different customers\n      or organizational units.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/identity-platform/docs/multi-tenancy\n    baseURL: https://identitytoolkit.googleapis.com\n    tags:\n      - Multi-Tenancy\n      - SaaS\n      - Tenant Management\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/identity-platform/docs/multi-tenancy\n  - name: Identity Platform OAuth Configuration API\n    description: >-\n      The OAuth Configuration API allows developers to programmatically manage\n      OAuth identity provider configurations for Identity Platform projects.\n      It supports configuring Google, Facebook, Apple, Microsoft, Twitter, GitHub,\n      and other OIDC and SAML providers for federated\
  \ authentication.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/identity-platform/docs/federated-login\n    baseURL: https://identitytoolkit.googleapis.com\n    tags:\n      - Federation\n      - Identity Providers\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/identity-platform/docs/reference/rest/v2/projects.defaultSupportedIdpConfigs\ncommon:\n  - type: GettingStarted\n    url: https://cloud.google.com/identity-platform/docs/quickstarts\n  - type: Pricing\n    url: https://cloud.google.com/identity-platform/pricing\n  - type: Authentication\n    url: https://cloud.google.com/identity-platform/docs/concepts\n  - type: Console\n    url: https://console.cloud.google.com/customer-identity\n  - type: SDKs\n    url: https://cloud.google.com/identity-platform/docs/reference/libraries\n  - type: Support\n    url: https://cloud.google.com/identity-platform/docs/support\n\
  \  - type: Status\n    url: https://status.cloud.google.com\n  - type: JSON-LD\n    url: json-ld/google-identity-platform-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-identity-platform/refs/heads/main/apis.yml
tags:
- Authentication
- Google Cloud
- Identity
- Multi-Tenancy
- OAuth
- OpenID Connect
- SAML
url: https://raw.githubusercontent.com/api-evangelist/google-identity-platform/refs/heads/main/apis.yml
use_cases: []
---
