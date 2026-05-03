---
api_count: 3
api_specs:
- filename: ssl-tls-certificate-management-openapi.yml
  format: yaml
  label: Let's Encrypt ACME API
  slug: lets-encrypt-acme
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/openapi/ssl-tls-certificate-management-openapi.yml
apis:
- description: Let's Encrypt provides free, automated SSL/TLS certificates via the ACME (Automatic Certificate Management Environment) protocol (RFC 8555). The ACME API enables automated certificate issuance, renewa
  name: Let's Encrypt ACME API
  slug: lets-encrypt-acme
- description: DigiCert provides enterprise certificate management through a REST API supporting issuance, renewal, revocation, and lifecycle management for OV, EV, DV, and private certificates. Supports CT log inte
  name: DigiCert Certificate Management API
  slug: digicert-api
- description: Sectigo (formerly Comodo CA) provides certificate lifecycle management APIs for enterprise PKI, including S/MIME, code signing, and TLS certificates.
  name: Sectigo Certificate Manager API
  slug: sectigo-api
capabilities:
- description: Unified workflow capability for SSL/TLS certificate lifecycle management. Enables security and infrastructure teams to request, monitor, renew, and revoke TLS certificates across domains. Combines cer
  name: SSL/TLS Certificate Lifecycle
  slug: certificate-lifecycle
common:
- title: ''
  type: Website
  url: https://letsencrypt.org/
- title: ''
  type: Documentation
  url: https://letsencrypt.org/docs/
- title: ''
  type: GitHub Organization
  url: https://github.com/letsencrypt
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/openapi/ssl-tls-certificate-management-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/json-schema/ssl-tls-certificate-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/json-structure/ssl-tls-certificate-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/json-ld/ssl-tls-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/rules/ssl-tls-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/capabilities/certificate-lifecycle.yaml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/vocabulary/ssl-tls-vocabulary.yml
created: '2025-01-01'
description: SSL/TLS (Secure Sockets Layer / Transport Layer Security) is the cryptographic protocol that secures communications over the internet. TLS 1.3 is the current standard, providing authentication, confidentiality, and integrity for HTTPS, email, VoIP, and other protocols. This covers certificate management, public key infrastructure (PKI), certificate authorities, and TLS configuration APIs from major vendors and open source projects.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Ssl Tls Context
  property_count: 7
  slug: ssl-tls-context
layout: provider
modified: '2026-05-02'
name: SSL/TLS
rules:
- name: SSL/TLS API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 4
  slug: ssl-tls-rules
skills: []
slug: ssl-tls
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ssl-tls\nname: SSL/TLS\ndescription: >-\n  SSL/TLS (Secure Sockets Layer / Transport Layer Security) is the cryptographic\n  protocol that secures communications over the internet. TLS 1.3 is the current\n  standard, providing authentication, confidentiality, and integrity for HTTPS,\n  email, VoIP, and other protocols. This covers certificate management, public\n  key infrastructure (PKI), certificate authorities, and TLS configuration APIs\n  from major vendors and open source projects.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - SSL/TLS\n  - TLS\n  - Certificates\n  - PKI\n  - Cryptography\n  - Certificate Authority\n  - HTTPS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: ssl-tls:lets-encrypt-acme\n    name: Let's Encrypt ACME API\n    description: >-\n      Let's\
  \ Encrypt provides free, automated SSL/TLS certificates via the ACME\n      (Automatic Certificate Management Environment) protocol (RFC 8555). The\n      ACME API enables automated certificate issuance, renewal, and revocation\n      using HTTP-01, DNS-01, and TLS-ALPN-01 challenges to verify domain\n      ownership.\n    humanURL: https://letsencrypt.org/\n    baseURL: https://acme-v02.api.letsencrypt.org/directory\n    tags:\n      - SSL/TLS\n      - Certificate Authority\n      - ACME\n      - Let's Encrypt\n      - HTTPS\n    properties:\n      - type: Documentation\n        url: https://letsencrypt.org/docs/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/openapi/ssl-tls-certificate-management-openapi.yml\n  - aid: ssl-tls:digicert-api\n    name: DigiCert Certificate Management API\n    description: >-\n      DigiCert provides enterprise certificate management through a REST API\n      supporting issuance,\
  \ renewal, revocation, and lifecycle management for\n      OV, EV, DV, and private certificates. Supports CT log integration and\n      ACME protocol.\n    humanURL: https://www.digicert.com/\n    baseURL: https://www.digicert.com/services/v2\n    tags:\n      - SSL/TLS\n      - Certificate Authority\n      - Enterprise PKI\n      - DigiCert\n    properties:\n      - type: Documentation\n        url: https://dev.digicert.com/\n  - aid: ssl-tls:sectigo-api\n    name: Sectigo Certificate Manager API\n    description: >-\n      Sectigo (formerly Comodo CA) provides certificate lifecycle management\n      APIs for enterprise PKI, including S/MIME, code signing, and TLS\n      certificates.\n    humanURL: https://sectigo.com/\n    baseURL: https://cert-manager.com/api\n    tags:\n      - SSL/TLS\n      - Certificate Authority\n      - Enterprise PKI\n    properties:\n      - type: Documentation\n        url: https://sectigo.com/knowledge-base\ncommon:\n  - type: Website\n    url: https://letsencrypt.org/\n\
  \  - type: Documentation\n    url: https://letsencrypt.org/docs/\n  - type: GitHub Organization\n    url: https://github.com/letsencrypt\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/openapi/ssl-tls-certificate-management-openapi.yml\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/json-schema/ssl-tls-certificate-schema.json\n  - type: JSONStructure\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/json-structure/ssl-tls-certificate-structure.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/json-ld/ssl-tls-context.jsonld\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/rules/ssl-tls-rules.yml\n  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/capabilities/certificate-lifecycle.yaml\n\
  \  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/vocabulary/ssl-tls-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/apis.yml
tags:
- SSL/TLS
- TLS
- Certificates
- PKI
- Cryptography
- Certificate Authority
- HTTPS
url: https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/apis.yml
use_cases: []
---
