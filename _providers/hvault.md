---
api_count: 4
api_specs:
- filename: hvault-system-backend-openapi.yml
  format: yaml
  label: Vault System Backend API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hvault/refs/heads/main/openapi/hvault-system-backend-openapi.yml
- filename: hvault-secrets-engines-openapi.yml
  format: yaml
  label: Vault Secrets Engines API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hvault/refs/heads/main/openapi/hvault-secrets-engines-openapi.yml
- filename: hvault-auth-methods-openapi.yml
  format: yaml
  label: Vault Auth Methods API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hvault/refs/heads/main/openapi/hvault-auth-methods-openapi.yml
- filename: hvault-identity-openapi.yml
  format: yaml
  label: Vault Identity API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hvault/refs/heads/main/openapi/hvault-identity-openapi.yml
apis:
- description: API for system-level operations including authentication, secrets engines, audit devices, and general Vault configuration.
  name: Vault System Backend API
  slug: ''
- description: APIs for various secrets engines including Key/Value, AWS, Azure, databases, PKI, SSH, and more.
  name: Vault Secrets Engines API
  slug: ''
- description: APIs for authentication methods including Token, AppRole, Kubernetes, LDAP, JWT/OIDC, GitHub, and more.
  name: Vault Auth Methods API
  slug: ''
- description: APIs for managing entities, entity aliases, and groups for identity management across authentication methods.
  name: Vault Identity API
  slug: ''
common:
- title: ''
  type: X-website
  url: https://www.vaultproject.io/
- title: ''
  type: X-documentation
  url: https://developer.hashicorp.com/vault/docs
- title: ''
  type: X-api-documentation
  url: https://developer.hashicorp.com/vault/api-docs
- title: ''
  type: X-github
  url: https://github.com/hashicorp/vault
- title: ''
  type: X-tutorials
  url: https://developer.hashicorp.com/vault/tutorials
- title: ''
  type: X-support
  url: https://support.hashicorp.com/
- title: ''
  type: X-terms-of-service
  url: https://www.hashicorp.com/terms-of-service
- title: ''
  type: X-privacy-policy
  url: https://www.hashicorp.com/privacy
- title: ''
  type: X-pricing
  url: https://www.hashicorp.com/products/vault/pricing
- title: ''
  type: X-blog
  url: https://www.hashicorp.com/blog
- title: ''
  type: X-status
  url: https://status.hashicorp.com/
- title: ''
  type: JSON-LD
  url: json-ld/hvault-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/hvault-secret-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/hvault-entity-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/hvault-entity-alias-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/hvault-token-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/hvault-policy-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/hvault-group-schema.json
created: '2024-01-15'
description: HashiCorp Vault secures, stores, and tightly controls access to tokens, passwords, certificates, API keys, and other secrets in modern computing. Vault handles leasing, key revocation, key rolling, and auditing. Through a unified API, users can access an encrypted Key/Value store and network encryption-as-a-service, or generate AWS IAM/STS credentials, SQL/NoSQL databases, X.509 certificates, SSH credentials, and more.
features: []
image: https://www.vaultproject.io/img/logo-hashicorp.svg
integrations: []
jsonld:
- class_count: 0
  name: Hvault Context
  property_count: 10
  slug: hvault-context
layout: provider
modified: '2026-04-28'
name: HashiCorp Vault
skills: []
slug: hvault
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: HashiCorp Vault\ndescription: >-\n  HashiCorp Vault secures, stores, and tightly controls access to tokens, passwords,\n  certificates, API keys, and other secrets in modern computing. Vault handles leasing,\n  key revocation, key rolling, and auditing. Through a unified API, users can access\n  an encrypted Key/Value store and network encryption-as-a-service, or generate AWS\n  IAM/STS credentials, SQL/NoSQL databases, X.509 certificates, SSH credentials, and\n  more.\nimage: https://www.vaultproject.io/img/logo-hashicorp.svg\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.16'\ntags:\n  - Encryption\n  - Identity\n  - Infrastructure\n  - Secrets Management\n  - Security\nurl: https://www.vaultproject.io/api-docs\napis:\n  - name: Vault System Backend API\n    description: >-\n      API for system-level operations including authentication, secrets engines, audit\n      devices, and general Vault configuration.\n    image: https://www.vaultproject.io/img/logo-hashicorp.svg\n\
  \    humanURL: https://www.vaultproject.io/\n    baseURL: https://vault.example.com/v1/sys\n    tags:\n      - Administration\n      - Configuration\n      - System\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/vault/api-docs/system\n      - type: X-openapi\n        url: https://github.com/hashicorp/vault/blob/main/openapi.json\n      - type: Authentication\n        url: https://developer.hashicorp.com/vault/docs/auth\n      - type: OpenAPI\n        url: openapi/hvault-system-backend-openapi.yml\n    contact:\n      - FN: HashiCorp Support\n        email: support@hashicorp.com\n        X-twitter: HashiCorp\n  - name: Vault Secrets Engines API\n    description: >-\n      APIs for various secrets engines including Key/Value, AWS, Azure, databases,\n      PKI, SSH, and more.\n    image: https://www.vaultproject.io/img/logo-hashicorp.svg\n    humanURL: https://developer.hashicorp.com/vault/docs/secrets\n    baseURL: https://vault.example.com/v1\n\
  \    tags:\n      - Cloud\n      - Databases\n      - Kv\n      - Secrets\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/vault/api-docs/secret\n      - type: X-kv-docs\n        url: https://developer.hashicorp.com/vault/api-docs/secret/kv/kv-v2\n      - type: X-aws-docs\n        url: https://developer.hashicorp.com/vault/api-docs/secret/aws\n      - type: X-database-docs\n        url: https://developer.hashicorp.com/vault/api-docs/secret/databases\n      - type: OpenAPI\n        url: openapi/hvault-secrets-engines-openapi.yml\n    contact:\n      - FN: HashiCorp Support\n        email: support@hashicorp.com\n  - name: Vault Auth Methods API\n    description: >-\n      APIs for authentication methods including Token, AppRole, Kubernetes, LDAP,\n      JWT/OIDC, GitHub, and more.\n    image: https://www.vaultproject.io/img/logo-hashicorp.svg\n    humanURL: https://developer.hashicorp.com/vault/docs/auth\n    baseURL: https://vault.example.com/v1/auth\n\
  \    tags:\n      - Access Control\n      - Authentication\n      - Identity\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/vault/api-docs/auth\n      - type: X-token-docs\n        url: https://developer.hashicorp.com/vault/api-docs/auth/token\n      - type: X-approle-docs\n        url: https://developer.hashicorp.com/vault/api-docs/auth/approle\n      - type: X-kubernetes-docs\n        url: https://developer.hashicorp.com/vault/api-docs/auth/kubernetes\n      - type: OpenAPI\n        url: openapi/hvault-auth-methods-openapi.yml\n    contact:\n      - FN: HashiCorp Support\n        email: support@hashicorp.com\n  - name: Vault Identity API\n    description: >-\n      APIs for managing entities, entity aliases, and groups for identity management\n      across authentication methods.\n    image: https://www.vaultproject.io/img/logo-hashicorp.svg\n    humanURL: https://developer.hashicorp.com/vault/docs/secrets/identity\n    baseURL: https://vault.example.com/v1/identity\n\
  \    tags:\n      - Entities\n      - Groups\n      - Identity\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/vault/api-docs/secret/identity\n      - type: OpenAPI\n        url: openapi/hvault-identity-openapi.yml\n    contact:\n      - FN: HashiCorp Support\n        email: support@hashicorp.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: X-website\n    url: https://www.vaultproject.io/\n  - type: X-documentation\n    url: https://developer.hashicorp.com/vault/docs\n  - type: X-api-documentation\n    url: https://developer.hashicorp.com/vault/api-docs\n  - type: X-github\n    url: https://github.com/hashicorp/vault\n  - type: X-tutorials\n    url: https://developer.hashicorp.com/vault/tutorials\n  - type: X-support\n    url: https://support.hashicorp.com/\n  - type: X-terms-of-service\n    url: https://www.hashicorp.com/terms-of-service\n  - type: X-privacy-policy\n    url: https://www.hashicorp.com/privacy\n\
  \  - type: X-pricing\n    url: https://www.hashicorp.com/products/vault/pricing\n  - type: X-blog\n    url: https://www.hashicorp.com/blog\n  - type: X-status\n    url: https://status.hashicorp.com/\n  - type: JSON-LD\n    url: json-ld/hvault-context.jsonld\n  - type: JSONSchema\n    url: json-schema/hvault-secret-schema.json\n  - type: JSONSchema\n    url: json-schema/hvault-entity-schema.json\n  - type: JSONSchema\n    url: json-schema/hvault-entity-alias-schema.json\n  - type: JSONSchema\n    url: json-schema/hvault-token-schema.json\n  - type: JSONSchema\n    url: json-schema/hvault-policy-schema.json\n  - type: JSONSchema\n    url: json-schema/hvault-group-schema.json\ninclude:\n  - name: Vault Client Libraries\n    url: https://developer.hashicorp.com/vault/api-docs/libraries\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hvault/refs/heads/main/apis.yml
tags:
- Encryption
- Identity
- Infrastructure
- Secrets Management
- Security
url: https://www.vaultproject.io/api-docs
use_cases: []
---
