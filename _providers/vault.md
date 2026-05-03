---
api_count: 3
api_specs:
- filename: vault-kv-openapi.yml
  format: yaml
  label: HashiCorp Vault KV Secrets Engine API
  slug: vault-kv
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vault/refs/heads/main/openapi/vault-kv-openapi.yml
- filename: vault-sys-openapi.yml
  format: yaml
  label: HashiCorp Vault System Backend API
  slug: vault-sys
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vault/refs/heads/main/openapi/vault-sys-openapi.yml
apis:
- description: The KV v2 secrets engine provides key-value secret storage with versioning, metadata management, soft delete, and permanent destruction of secret versions. Essential for storing static secrets like AP
  name: HashiCorp Vault KV Secrets Engine API
  slug: vault-kv
- description: The Vault system backend provides management operations for authentication methods, secrets engine mounts, ACL policies, token lifecycle, and lease management. All sys/ endpoints control the core oper
  name: HashiCorp Vault System Backend API
  slug: vault-sys
- description: The complete Vault HTTP API gives full access to all Vault operations via REST. Includes authentication method APIs (AppRole, LDAP, JWT, Kubernetes, AWS, Azure), secrets engine APIs (Database, AWS, PK
  name: Vault HTTP API
  slug: vault-api
capabilities:
- description: Unified workflow capability for platform engineers and DevOps teams managing secrets with HashiCorp Vault. Combines KV secrets CRUD, version management, metadata operations, and system configuration i
  name: HashiCorp Vault Secrets Management
  slug: secrets-management
common:
- title: ''
  type: Portal
  url: https://developer.hashicorp.com/vault
- title: ''
  type: Website
  url: https://www.vaultproject.io
- title: ''
  type: Blog
  url: https://www.hashicorp.com/blog/products/vault
- title: ''
  type: StatusPage
  url: https://status.hashicorp.com
- title: ''
  type: TermsOfService
  url: https://www.hashicorp.com/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.hashicorp.com/privacy
- title: ''
  type: GitHubOrganization
  url: https://github.com/hashicorp
- title: ''
  type: GitHubRepository
  url: https://github.com/hashicorp/vault
- title: ''
  type: Forum
  url: https://discuss.hashicorp.com/c/vault
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/vault
- title: ''
  type: Training
  url: https://developer.hashicorp.com/vault/tutorials
- title: ''
  type: SpectralRules
  url: rules/vault-spectral-rules.yml
- title: Secrets Management
  type: NaftikoCapability
  url: capabilities/secrets-management.yaml
created: '2024-01-01'
description: HashiCorp Vault is an open source tool for securely storing and accessing secrets. A secret is anything you want to tightly control access to, such as API keys, passwords, certificates, and more. Vault provides a unified interface to any secret while providing tight access control via policies and recording a detailed audit log. It supports dynamic secrets, data encryption, PKI, SSH certificate issuance, and identity-based access through a comprehensive REST HTTP API.
features:
- description: Versioned key-value secret storage with soft delete, undelete, and permanent destruction.
  name: KV Secrets Engine
- description: On-demand, time-limited credentials for databases, AWS, Azure, GCP, and other backends.
  name: Dynamic Secrets
- description: Encryption-as-a-Service for application data without storing plaintext in Vault.
  name: Data Encryption (Transit)
- description: Built-in PKI secrets engine for issuing X.509 certificates with configurable TTLs.
  name: PKI Certificate Authority
- description: Dynamic SSH certificates and OTPs for secure machine access management.
  name: SSH Certificate Issuance
- description: Fine-grained HCL-based policies controlling access to any secret path with capabilities.
  name: ACL Policies
- description: Pluggable authentication supporting AppRole, LDAP, JWT/OIDC, Kubernetes, AWS, and more.
  name: Auth Methods
- description: All dynamic secrets have TTL-bound leases that can be renewed or revoked on demand.
  name: Lease Management
- description: Comprehensive audit trail of all API requests and responses for compliance.
  name: Audit Logging
- description: Official HashiCorp Vault MCP server enabling AI-assisted secrets management workflows.
  name: MCP Server
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Terraform Vault provider for managing Vault configuration and policies as code.
  name: Terraform
- description: Vault Secrets Operator and Vault Agent Injector for native Kubernetes integration.
  name: Kubernetes
- description: OIDC-based authentication from GitHub Actions workflows without static credentials.
  name: GitHub Actions
- description: Dynamic AWS IAM credentials and EC2/IAM-based authentication methods.
  name: AWS
- description: Native HashiCorp Consul integration for service mesh secrets and ACL tokens.
  name: Consul
- description: Dynamic database credentials for PostgreSQL with configurable role TTLs.
  name: PostgreSQL
- description: Native HashiCorp Nomad integration for workload identity and secrets.
  name: Nomad
- description: HashiCorp Vault lookup plugin for Ansible playbook secret retrieval.
  name: Ansible
jsonld:
- class_count: 10
  name: Vault Kv Context
  property_count: 15
  slug: vault-kv-context
- class_count: 17
  name: Vault Sys Context
  property_count: 19
  slug: vault-sys-context
layout: provider
modified: '2026-05-03'
name: HashiCorp Vault
rules:
- name: HashiCorp Vault API Rules
  rule_count: 28
  severity_counts:
    error: 11
    hint: 0
    info: 5
    warn: 12
  slug: vault-spectral-rules
skills: []
slug: vault
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vault\nname: HashiCorp Vault\ndescription: >-\n  HashiCorp Vault is an open source tool for securely storing and accessing secrets.\n  A secret is anything you want to tightly control access to, such as API keys,\n  passwords, certificates, and more. Vault provides a unified interface to any\n  secret while providing tight access control via policies and recording a detailed\n  audit log. It supports dynamic secrets, data encryption, PKI, SSH certificate\n  issuance, and identity-based access through a comprehensive REST HTTP API.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - DevOps\n  - Encryption\n  - Open Source\n  - PKI\n  - Secrets Management\n  - Security\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vault/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: vault:vault-kv\n    name: HashiCorp\
  \ Vault KV Secrets Engine API\n    description: >-\n      The KV v2 secrets engine provides key-value secret storage with versioning,\n      metadata management, soft delete, and permanent destruction of secret versions.\n      Essential for storing static secrets like API keys, passwords, and configuration\n      values with full version history and access control.\n    humanURL: https://developer.hashicorp.com/vault/api-docs/secret/kv/kv-v2\n    baseURL: https://vault.example.com/v1\n    tags:\n      - KV Secrets\n      - Secrets Management\n      - Versioning\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/vault/api-docs/secret/kv/kv-v2\n      - type: OpenAPI\n        url: openapi/vault-kv-openapi.yml\n      - type: JSONSchema\n        url: json-schema/vault-kv-secret-data-request-schema.json\n        title: Secret Data Request Schema\n      - type: JSONSchema\n        url: json-schema/vault-kv-secret-data-response-schema.json\n        title:\
  \ Secret Data Response Schema\n      - type: JSONStructure\n        url: json-structure/vault-kv-secret-data-request-structure.json\n        title: Secret Data Request Structure\n      - type: Example\n        url: examples/vault-kv-secret-data-response-example.json\n        title: Secret Data Response Example\n      - type: JSON-LD\n        url: json-ld/vault-kv-context.jsonld\n  - aid: vault:vault-sys\n    name: HashiCorp Vault System Backend API\n    description: >-\n      The Vault system backend provides management operations for authentication\n      methods, secrets engine mounts, ACL policies, token lifecycle, and lease\n      management. All sys/ endpoints control the core operational behavior of Vault.\n    humanURL: https://developer.hashicorp.com/vault/api-docs\n    baseURL: https://vault.example.com/v1\n    tags:\n      - Auth Methods\n      - Leases\n      - Policies\n      - Secrets Engines\n      - System Administration\n    properties:\n      - type: Documentation\n  \
  \      url: https://developer.hashicorp.com/vault/api-docs\n      - type: OpenAPI\n        url: openapi/vault-sys-openapi.yml\n      - type: JSONSchema\n        url: json-schema/vault-sys-health-response-schema.json\n        title: Health Response Schema\n      - type: JSONStructure\n        url: json-structure/vault-sys-health-response-structure.json\n        title: Health Response Structure\n      - type: Example\n        url: examples/vault-sys-health-response-example.json\n        title: Health Response Example\n      - type: JSON-LD\n        url: json-ld/vault-sys-context.jsonld\n  - aid: vault:vault-api\n    name: Vault HTTP API\n    description: >-\n      The complete Vault HTTP API gives full access to all Vault operations via\n      REST. Includes authentication method APIs (AppRole, LDAP, JWT, Kubernetes,\n      AWS, Azure), secrets engine APIs (Database, AWS, PKI, SSH, Transit), and\n      the system backend. The OpenAPI spec is dynamically generated from a running\n      Vault\
  \ instance at /v1/sys/internal/specs/openapi.\n    humanURL: https://developer.hashicorp.com/vault/api-docs\n    baseURL: https://vault.example.com/v1\n    tags:\n      - Auth Methods\n      - Dynamic Secrets\n      - Secrets Management\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/vault/api-docs\n      - type: Authentication\n        url: https://developer.hashicorp.com/vault/docs/auth\n      - type: GettingStarted\n        url: https://developer.hashicorp.com/vault/tutorials/get-started\n      - type: ChangeLog\n        url: https://github.com/hashicorp/vault/blob/main/CHANGELOG.md\ncommon:\n  - type: Portal\n    url: https://developer.hashicorp.com/vault\n  - type: Website\n    url: https://www.vaultproject.io\n  - type: Blog\n    url: https://www.hashicorp.com/blog/products/vault\n  - type: StatusPage\n    url: https://status.hashicorp.com\n  - type: TermsOfService\n    url: https://www.hashicorp.com/terms-of-service\n  - type: PrivacyPolicy\n\
  \    url: https://www.hashicorp.com/privacy\n  - type: GitHubOrganization\n    url: https://github.com/hashicorp\n  - type: GitHubRepository\n    url: https://github.com/hashicorp/vault\n  - type: Forum\n    url: https://discuss.hashicorp.com/c/vault\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/vault\n  - type: Training\n    url: https://developer.hashicorp.com/vault/tutorials\n  - type: SpectralRules\n    url: rules/vault-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/secrets-management.yaml\n    title: Secrets Management\n  - type: Features\n    data:\n      - name: KV Secrets Engine\n        description: Versioned key-value secret storage with soft delete, undelete, and permanent destruction.\n      - name: Dynamic Secrets\n        description: On-demand, time-limited credentials for databases, AWS, Azure, GCP, and other backends.\n      - name: Data Encryption (Transit)\n        description: Encryption-as-a-Service for application\
  \ data without storing plaintext in Vault.\n      - name: PKI Certificate Authority\n        description: Built-in PKI secrets engine for issuing X.509 certificates with configurable TTLs.\n      - name: SSH Certificate Issuance\n        description: Dynamic SSH certificates and OTPs for secure machine access management.\n      - name: ACL Policies\n        description: Fine-grained HCL-based policies controlling access to any secret path with capabilities.\n      - name: Auth Methods\n        description: Pluggable authentication supporting AppRole, LDAP, JWT/OIDC, Kubernetes, AWS, and more.\n      - name: Lease Management\n        description: All dynamic secrets have TTL-bound leases that can be renewed or revoked on demand.\n      - name: Audit Logging\n        description: Comprehensive audit trail of all API requests and responses for compliance.\n      - name: MCP Server\n        description: Official HashiCorp Vault MCP server enabling AI-assisted secrets management workflows.\n\
  \  - type: UseCases\n    data:\n      - name: Application Secret Injection\n        description: Inject database credentials, API keys, and config into applications at runtime via Vault Agent.\n      - name: Kubernetes Secrets Management\n        description: Replace Kubernetes secrets with Vault-managed secrets using the Vault Secrets Operator.\n      - name: Database Credential Rotation\n        description: Automatically rotate database credentials with dynamic secrets engine for zero-knowledge security.\n      - name: PKI Automation\n        description: Automate certificate lifecycle management for internal services and mutual TLS.\n      - name: CI/CD Secret Injection\n        description: Provide short-lived credentials to CI/CD pipelines via AppRole or GitHub Actions OIDC.\n      - name: Secrets as Code\n        description: Manage Vault configuration as code using the Terraform Vault provider.\n      - name: Compliance and Audit\n        description: Meet SOC 2, PCI-DSS, HIPAA,\
  \ and FedRAMP requirements with immutable audit logs.\n  - type: Integrations\n    data:\n      - name: Terraform\n        description: Terraform Vault provider for managing Vault configuration and policies as code.\n      - name: Kubernetes\n        description: Vault Secrets Operator and Vault Agent Injector for native Kubernetes integration.\n      - name: GitHub Actions\n        description: OIDC-based authentication from GitHub Actions workflows without static credentials.\n      - name: AWS\n        description: Dynamic AWS IAM credentials and EC2/IAM-based authentication methods.\n      - name: Consul\n        description: Native HashiCorp Consul integration for service mesh secrets and ACL tokens.\n      - name: PostgreSQL\n        description: Dynamic database credentials for PostgreSQL with configurable role TTLs.\n      - name: Nomad\n        description: Native HashiCorp Nomad integration for workload identity and secrets.\n      - name: Ansible\n        description: HashiCorp\
  \ Vault lookup plugin for Ansible playbook secret retrieval.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vault/refs/heads/main/apis.yml
tags:
- DevOps
- Encryption
- Open Source
- PKI
- Secrets Management
- Security
url: https://raw.githubusercontent.com/api-evangelist/vault/refs/heads/main/apis.yml
use_cases:
- description: Inject database credentials, API keys, and config into applications at runtime via Vault Agent.
  name: Application Secret Injection
- description: Replace Kubernetes secrets with Vault-managed secrets using the Vault Secrets Operator.
  name: Kubernetes Secrets Management
- description: Automatically rotate database credentials with dynamic secrets engine for zero-knowledge security.
  name: Database Credential Rotation
- description: Automate certificate lifecycle management for internal services and mutual TLS.
  name: PKI Automation
- description: Provide short-lived credentials to CI/CD pipelines via AppRole or GitHub Actions OIDC.
  name: CI/CD Secret Injection
- description: Manage Vault configuration as code using the Terraform Vault provider.
  name: Secrets as Code
- description: Meet SOC 2, PCI-DSS, HIPAA, and FedRAMP requirements with immutable audit logs.
  name: Compliance and Audit
---
