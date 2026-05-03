---
api_count: 2
api_specs:
- filename: sso-saml-openapi.yml
  format: yaml
  label: SAML SSO Authentication API
  slug: saml-authentication
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sso/refs/heads/main/openapi/sso-saml-openapi.yml
- filename: sso-oidc-openapi.yml
  format: yaml
  label: OpenID Connect (OIDC) Authentication API
  slug: oidc-authentication
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sso/refs/heads/main/openapi/sso-oidc-openapi.yml
apis:
- description: 'The SAML 2.0 Single Sign-On API enables service providers and identity providers to exchange authentication assertions via XML-signed messages. It supports HTTP Redirect Binding and HTTP POST Binding '
  name: SAML SSO Authentication API
  slug: saml-authentication
- description: 'The OpenID Connect (OIDC) API is a lightweight identity layer built on top of OAuth 2.0. It enables applications to verify user identity through the Authorization Code Flow, Implicit Flow, and Hybrid '
  name: OpenID Connect (OIDC) Authentication API
  slug: oidc-authentication
capabilities:
- description: Workflow capability for Single Sign-On identity federation using OpenID Connect (OIDC). Enables applications to integrate SSO authentication flows including authorization code exchange, user profile r
  name: SSO Identity Federation
  slug: identity-federation
common:
- title: ''
  type: Specification
  url: https://www.oasis-open.org/standards#samlv2.0
- title: ''
  type: Specification
  url: https://openid.net/connect/
- title: ''
  type: Specification
  url: https://oauth.net/2/
- title: ''
  type: GitHubOrg
  url: https://github.com/api-evangelist/sso
- title: ''
  type: JSON-LD
  url: json-ld/sso-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/sso-saml-assertion-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sso-oidc-token-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/sso-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/sso-rules.yml
created: '2025-01-01'
description: Single Sign-On (SSO) is an authentication technology that allows users to log in once and gain access to multiple related applications and services without re-authenticating. SSO implementations rely on protocols such as SAML 2.0, OpenID Connect (OIDC), and OAuth 2.0. Major identity providers including Okta, Microsoft Entra ID, Google, Ping Identity, Auth0, and Keycloak expose SSO APIs that allow applications to integrate federated authentication, token exchange, assertion validation, and session management.
features: []
image: ''
integrations: []
jsonld:
- class_count: 32
  name: Sso Context
  property_count: 5
  slug: sso-context
layout: provider
modified: '2026-05-02'
name: SSO
rules:
- name: SSO API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 7
  slug: sso-rules
skills: []
slug: sso
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SSO\ndescription: >-\n  Single Sign-On (SSO) is an authentication technology that allows users to log\n  in once and gain access to multiple related applications and services without\n  re-authenticating. SSO implementations rely on protocols such as SAML 2.0,\n  OpenID Connect (OIDC), and OAuth 2.0. Major identity providers including\n  Okta, Microsoft Entra ID, Google, Ping Identity, Auth0, and Keycloak expose\n  SSO APIs that allow applications to integrate federated authentication,\n  token exchange, assertion validation, and session management.\nurl: https://github.com/api-evangelist/sso\ntags:\n  - Authentication\n  - Authorization\n  - Identity\n  - OAuth\n  - OIDC\n  - SAML\n  - Security\n  - Single Sign-On\n  - SSO\ncreated: '2025-01-01'\nmodified: '2026-05-02'\napis:\n  - aid: sso:saml-authentication\n    name: SAML SSO Authentication API\n    tags:\n      - Authentication\n      - Federation\n      - Identity\n      - SAML\n      - Single Sign-On\n      - SSO\n\
  \    baseURL: https://your-idp.example.com\n    humanURL: https://www.oasis-open.org/standards#samlv2.0\n    description: >-\n      The SAML 2.0 Single Sign-On API enables service providers and identity\n      providers to exchange authentication assertions via XML-signed messages.\n      It supports HTTP Redirect Binding and HTTP POST Binding for AuthnRequest\n      and Response flows, Assertion Consumer Service (ACS) endpoints, Single\n      Logout (SLO), and IdP metadata retrieval as defined by the OASIS SAML\n      2.0 specification.\n    properties:\n      - url: https://www.oasis-open.org/standards#samlv2.0\n        type: Documentation\n      - url: https://wiki.oasis-open.org/security/FrontPage\n        type: Documentation\n      - url: openapi/sso-saml-openapi.yml\n        type: OpenAPI\n  - aid: sso:oidc-authentication\n    name: OpenID Connect (OIDC) Authentication API\n    tags:\n      - Authentication\n      - Identity\n      - JWT\n      - OAuth\n      - OIDC\n      - Single\
  \ Sign-On\n      - SSO\n    baseURL: https://your-idp.example.com\n    humanURL: https://openid.net/connect/\n    description: >-\n      The OpenID Connect (OIDC) API is a lightweight identity layer built on\n      top of OAuth 2.0. It enables applications to verify user identity through\n      the Authorization Code Flow, Implicit Flow, and Hybrid Flow. Key\n      endpoints include the Authorization Endpoint, Token Endpoint, UserInfo\n      Endpoint, and JWKS URI for token signature verification. OIDC is\n      supported by all major identity providers.\n    properties:\n      - url: https://openid.net/connect/\n        type: Documentation\n      - url: https://openid.net/developers/specs/\n        type: Specification\n      - url: openapi/sso-oidc-openapi.yml\n        type: OpenAPI\ncommon:\n  - url: https://www.oasis-open.org/standards#samlv2.0\n    type: Specification\n  - url: https://openid.net/connect/\n    type: Specification\n  - url: https://oauth.net/2/\n    type: Specification\n\
  \  - url: https://github.com/api-evangelist/sso\n    type: GitHubOrg\n  - url: json-ld/sso-context.jsonld\n    type: JSON-LD\n  - url: json-schema/sso-saml-assertion-schema.json\n    type: JSONSchema\n  - url: json-schema/sso-oidc-token-schema.json\n    type: JSONSchema\n  - url: vocabulary/sso-vocabulary.yml\n    type: Vocabulary\n  - url: rules/sso-rules.yml\n    type: SpectralRules\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sso/refs/heads/main/apis.yml
tags:
- Authentication
- Authorization
- Identity
- OAuth
- OIDC
- SAML
- Security
- Single Sign-On
- SSO
url: https://github.com/api-evangelist/sso
use_cases: []
---
