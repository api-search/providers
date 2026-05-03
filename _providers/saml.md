---
api_count: 1
api_specs:
- filename: saml-sso-bindings.yml
  format: yaml
  label: SAML 2.0 SSO HTTP Bindings API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/saml/refs/heads/main/openapi/saml-sso-bindings.yml
apis:
- description: API specification for SAML 2.0 Single Sign-On HTTP bindings including the HTTP Redirect Binding and HTTP POST Binding for AuthnRequest and Response exchange, Assertion Consumer Service, Single Logout,
  name: SAML 2.0 SSO HTTP Bindings API
  slug: ''
capabilities:
- description: 'SAML 2.0 Single Sign-On workflow capability implementing the complete SSO lifecycle: SP-initiated SSO via HTTP Redirect Binding and HTTP POST Binding, Assertion Consumer Service (ACS) processing, Sing'
  name: SAML 2.0 Single Sign-On
  slug: single-sign-on
common:
- title: SAML 2.0 OASIS Standard
  type: Documentation
  url: https://www.oasis-open.org/standard/saml/
- title: SAML 2.0 Technical Overview
  type: Documentation
  url: https://docs.oasis-open.org/security/saml/Post2.0/sstc-saml-tech-overview-2.0.html
- title: SAML 2.0 Core Specification
  type: Documentation
  url: https://docs.oasis-open.org/security/saml/v2.0/saml-core-2.0-os.pdf
- title: SAML 2.0 Bindings Specification
  type: Documentation
  url: https://docs.oasis-open.org/security/saml/v2.0/saml-bindings-2.0-os.pdf
- title: SAML 2.0 Profiles Specification
  type: Documentation
  url: https://docs.oasis-open.org/security/saml/v2.0/saml-profiles-2.0-os.pdf
- title: SAML 2.0 EntityDescriptor Metadata
  type: JSONSchema
  url: json-schema/saml-entity-descriptor.json
- title: SAML 2.0 AuthnRequest
  type: JSONSchema
  url: json-schema/saml-authn-request.json
- title: SAML 2.0 Assertion
  type: JSONSchema
  url: json-schema/saml-assertion.json
- title: SAML 2.0 JSON-LD Context
  type: JSONLDContext
  url: json-ld/saml-context.jsonld
- title: SAML 2.0 Assertion Structure
  type: JSONStructure
  url: json-structure/saml-assertion-structure.json
- title: SAML API Spectral Rules
  type: SpectralRules
  url: rules/saml-rules.yml
- title: SAML Single Sign-On Capability
  type: NaftikoCapability
  url: capabilities/single-sign-on.yaml
- title: SAML SSO HTTP Redirect Binding Example
  type: Example
  url: examples/saml-sso-redirect-example.json
- title: SAML 2.0 Vocabulary
  type: Vocabulary
  url: vocabulary/saml-vocabulary.yml
created: '2025-01-01'
description: SAML (Security Assertion Markup Language) is an XML-based open standard for exchanging authentication and authorization data between identity providers and service providers. Ratified as an OASIS Standard in March 2005, SAML 2.0 enables single sign-on (SSO) across different applications and domains, reducing the need for users to manage multiple sets of credentials. It uses XML digital signatures and encryption to secure assertions exchanged between Identity Providers (IdP) and Service Providers (SP).
features: []
image: ''
integrations: []
jsonld:
- class_count: 7
  name: Saml Context
  property_count: 35
  slug: saml-context
layout: provider
modified: '2026-05-02'
name: SAML
rules:
- name: SAML API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 5
  slug: saml-rules
skills: []
slug: saml
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SAML\ndescription: >-\n  SAML (Security Assertion Markup Language) is an XML-based open standard for\n  exchanging authentication and authorization data between identity providers\n  and service providers. Ratified as an OASIS Standard in March 2005, SAML 2.0\n  enables single sign-on (SSO) across different applications and domains,\n  reducing the need for users to manage multiple sets of credentials. It uses\n  XML digital signatures and encryption to secure assertions exchanged between\n  Identity Providers (IdP) and Service Providers (SP).\nurl: https://www.oasis-open.org/standard/saml/\ntags:\n  - Authentication\n  - Authorization\n  - Federation\n  - Identity Management\n  - Open Standard\n  - Security\n  - Single Sign-On\n  - SSO\n  - XML\ncreated: '2025-01-01'\nmodified: '2026-05-02'\napis:\n  - name: SAML 2.0 SSO HTTP Bindings API\n    description: >-\n      API specification for SAML 2.0 Single Sign-On HTTP bindings including the\n      HTTP Redirect Binding\
  \ and HTTP POST Binding for AuthnRequest and Response\n      exchange, Assertion Consumer Service, Single Logout, and metadata retrieval\n      as defined in the OASIS SAML 2.0 Bindings specification (saml-bindings-2.0-os).\n    tags:\n      - Authentication\n      - Bindings\n      - HTTP\n      - Identity Provider\n      - Service Provider\n      - Single Sign-On\n      - SSO\n    properties:\n      - type: OpenAPI\n        url: openapi/saml-sso-bindings.yml\n      - type: Documentation\n        url: https://docs.oasis-open.org/security/saml/v2.0/saml-bindings-2.0-os.pdf\ncommon:\n  - type: Documentation\n    url: https://www.oasis-open.org/standard/saml/\n    title: SAML 2.0 OASIS Standard\n  - type: Documentation\n    url: https://docs.oasis-open.org/security/saml/Post2.0/sstc-saml-tech-overview-2.0.html\n    title: SAML 2.0 Technical Overview\n  - type: Documentation\n    url: https://docs.oasis-open.org/security/saml/v2.0/saml-core-2.0-os.pdf\n    title: SAML 2.0 Core Specification\n\
  \  - type: Documentation\n    url: https://docs.oasis-open.org/security/saml/v2.0/saml-bindings-2.0-os.pdf\n    title: SAML 2.0 Bindings Specification\n  - type: Documentation\n    url: https://docs.oasis-open.org/security/saml/v2.0/saml-profiles-2.0-os.pdf\n    title: SAML 2.0 Profiles Specification\n  - type: JSONSchema\n    url: json-schema/saml-entity-descriptor.json\n    title: SAML 2.0 EntityDescriptor Metadata\n  - type: JSONSchema\n    url: json-schema/saml-authn-request.json\n    title: SAML 2.0 AuthnRequest\n  - type: JSONSchema\n    url: json-schema/saml-assertion.json\n    title: SAML 2.0 Assertion\n  - type: JSONLDContext\n    url: json-ld/saml-context.jsonld\n    title: SAML 2.0 JSON-LD Context\n  - type: JSONStructure\n    url: json-structure/saml-assertion-structure.json\n    title: SAML 2.0 Assertion Structure\n  - type: SpectralRules\n    url: rules/saml-rules.yml\n    title: SAML API Spectral Rules\n  - type: NaftikoCapability\n    url: capabilities/single-sign-on.yaml\n\
  \    title: SAML Single Sign-On Capability\n  - type: Example\n    url: examples/saml-sso-redirect-example.json\n    title: SAML SSO HTTP Redirect Binding Example\n  - type: Vocabulary\n    url: vocabulary/saml-vocabulary.yml\n    title: SAML 2.0 Vocabulary\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/saml/refs/heads/main/apis.yml
tags:
- Authentication
- Authorization
- Federation
- Identity Management
- Open Standard
- Security
- Single Sign-On
- SSO
- XML
url: https://www.oasis-open.org/standard/saml/
use_cases: []
---
