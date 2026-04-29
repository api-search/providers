---
api_count: 3
apis:
- description: The 1Password Connect Server API provides secure access to 1Password items and vaults in your company's apps and cloud infrastructure through a private REST API. Connect Servers bridge the gap between
  name: 1Password Connect Server API
  slug: 1password-connect-api
- description: The 1Password Events API provides programmatic access to event data generated within a 1Password account. It enables security teams and administrators to retrieve sign-in attempts, item usage records,
  name: 1Password Events API
  slug: 1password-events-api
- description: You can use the 1Password Partnership API to manage the provisioning and deprovisioning of third-party partner billing accounts for your customers. The API supports partner billing accounts for 1Passw
  name: 1Password Partnership API
  slug: 1password-partnership-api
capabilities:
- description: Unified secrets management and security monitoring workflow for 1Password. Combines the Connect Server API (vault and item management), Events API (audit log and sign-in monitoring), and Partnership A
  name: 1Password Secrets Management
  slug: 1password-secrets-management
common:
- title: ''
  type: Website
  url: https://1password.com/
- title: ''
  type: Portal
  url: https://developer.1password.com/
- title: ''
  type: Documentation
  url: https://developer.1password.com/docs/
- title: ''
  type: GettingStarted
  url: https://developer.1password.com/docs/get-started/
- title: ''
  type: Authentication
  url: https://developer.1password.com/docs/connect/connect-api-reference/#authentication
- title: Official SDKs
  type: SDK
  url: https://developer.1password.com/docs/sdks/
- title: Python SDK
  type: SDK
  url: https://pypi.org/project/onepassword-sdk/
- title: JavaScript SDK
  type: SDK
  url: https://www.npmjs.com/package/@1password/sdk
- title: Go SDK
  type: SDK
  url: https://pkg.go.dev/github.com/1Password/onepassword-sdk-go
- title: Connect Python SDK
  type: SDK
  url: https://pypi.org/project/onepassword-connect-sdk/
- title: Connect Node.js SDK
  type: SDK
  url: https://www.npmjs.com/package/@1password/connect
- title: Connect Go SDK
  type: SDK
  url: https://pkg.go.dev/github.com/1Password/connect-sdk-go
- title: 1Password CLI
  type: CLI
  url: https://developer.1password.com/docs/cli/
- title: ''
  type: Blog
  url: https://blog.1password.com/
- title: ''
  type: Support
  url: https://support.1password.com/
- title: ''
  type: PrivacyPolicy
  url: https://1password.com/legal/privacy/
- title: ''
  type: TermsOfService
  url: https://1password.com/legal/terms-of-service/
- title: ''
  type: SignUp
  url: https://start.1password.com/sign-up/
- title: ''
  type: ChangeLog
  url: https://developer.1password.com/docs/events-api/changelog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/1Password
- title: ''
  type: SpectralRules
  url: rules/1password-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/1password-secrets-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/1password-vocabulary.yaml
created: '2025-02-08'
description: 1Password is a password manager that helps individuals and businesses securely store and manage passwords, credentials, and sensitive information. The platform provides a Connect Server API for programmatic secrets management, an Events API for security monitoring and audit logging, and a Partnership API for managing partner billing accounts.
features:
- description: Programmatic access to 1Password vaults and items via Connect Server API
  name: Secrets Management
- description: Real-time audit log streaming of sign-in events, item usage, and audit trails
  name: Security Monitoring
- description: Provision and deprovision 1Password accounts for partner customers
  name: Partner Billing Management
- description: Official SDKs for Python, JavaScript/TypeScript, Go, and Connect-specific clients
  name: SDKs
- description: 1Password CLI for command-line secrets management and automation
  name: CLI
- description: Kubernetes operator and secrets injector for cloud-native deployments
  name: Kubernetes Integration
- description: Terraform provider to manage 1Password vault items as infrastructure
  name: Terraform Provider
- description: Load secrets from 1Password directly into GitHub Actions CI/CD pipelines
  name: GitHub Actions
image: /assets/icons/1password.png
integrations:
- description: Native integration via operator and secrets injector for Kubernetes deployments
  name: Kubernetes
- description: Terraform provider for managing 1Password items as infrastructure resources
  name: Terraform
- description: Ansible collection for 1Password Connect integration
  name: Ansible
- description: GitHub Actions to load and install 1Password secrets in CI/CD workflows
  name: GitHub Actions
- description: Events API Splunk integration for security event streaming
  name: Splunk
- description: Vault plugin for 1Password Connect secrets retrieval
  name: HashiCorp Vault
- description: Official Helm charts for deploying 1Password Connect on Kubernetes
  name: Helm Charts
jsonld:
- class_count: 15
  name: 1Password Connect Context
  property_count: 46
  slug: 1password-connect-context
- class_count: 0
  name: 1Password Context
  property_count: 8
  slug: 1password-context
- class_count: 13
  name: 1Password Events Context
  property_count: 43
  slug: 1password-events-context
- class_count: 4
  name: 1Password Partnership Context
  property_count: 6
  slug: 1password-partnership-context
layout: provider
modified: '2026-04-19'
name: 1Password
rules:
- name: 1Password API Rules
  rule_count: 30
  severity_counts:
    error: 13
    hint: 0
    info: 6
    warn: 11
  slug: 1password-spectral-rules
skills: []
slug: 1password
solutions: []
source_yaml: "aid: 1password\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/apis.yml\nname: 1Password\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Password Manager\n  - Passwords\n  - Security\n  - Secrets\ndescription: >-\n  1Password is a password manager that helps individuals and businesses securely\n  store and manage passwords, credentials, and sensitive information. The platform\n  provides a Connect Server API for programmatic secrets management, an Events API\n  for security monitoring and audit logging, and a Partnership API for managing\n  partner billing accounts.\ncreated: '2025-02-08'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: 1password:1password-connect-api\n    name: 1Password Connect Server API\n    tags:\n      - Items\n      - Passwords\n      - Secrets\n      - Vaults\n    humanURL: https://developer.1password.com/docs/connect/api-reference/\n\
  \    baseURL: http://localhost:8080\n    properties:\n      - url: https://developer.1password.com/docs/connect/api-reference/\n        type: Documentation\n      - url: openapi/1password-connect-openapi.yml\n        type: OpenAPI\n      - url: json-schema/1password-connect-vault-schema.json\n        type: JSONSchema\n      - url: json-schema/1password-connect-item-schema.json\n        type: JSONSchema\n      - url: json-schema/1password-connect-full-item-schema.json\n        type: JSONSchema\n      - url: json-ld/1password-connect-context.jsonld\n        type: JSON-LD\n    description: >-\n      The 1Password Connect Server API provides secure access to 1Password\n      items and vaults in your company's apps and cloud infrastructure through\n      a private REST API. Connect Servers bridge the gap between 1Password and\n      your infrastructure by enabling programmatic access to secrets stored in\n      shared vaults. You can create, read, update, and delete items, manage\n      vaults,\
  \ and retrieve files attached to items.\n  - aid: 1password:1password-events-api\n    name: 1Password Events API\n    tags:\n      - Audit\n      - Events\n      - Monitoring\n      - Security\n    humanURL: https://developer.1password.com/docs/events-api/reference/\n    baseURL: https://events.1password.com\n    properties:\n      - url: https://developer.1password.com/docs/events-api/reference/\n        type: Documentation\n      - url: openapi/1password-events-openapi.yml\n        type: OpenAPI\n      - url: json-schema/1password-events-sign-in-attempt-schema.json\n        type: JSONSchema\n      - url: json-schema/1password-events-item-usage-schema.json\n        type: JSONSchema\n      - url: json-ld/1password-events-context.jsonld\n        type: JSON-LD\n    description: >-\n      The 1Password Events API provides programmatic access to event data\n      generated within a 1Password account. It enables security teams and\n      administrators to retrieve sign-in attempts, item usage\
  \ records, and\n      audit events for monitoring, compliance, and security analysis. The API\n      uses cursor-based pagination with POST requests to efficiently stream\n      large volumes of event data.\n  - aid: 1password:1password-partnership-api\n    name: 1Password Partnership API\n    tags:\n      - Billing\n      - Partners\n      - Passwords\n    humanURL: https://developer.1password.com/docs/partnership-api/reference/\n    baseURL: https://billing.b5test.eu/api/v1\n    properties:\n      - url: https://developer.1password.com/docs/partnership-api/reference/\n        type: Documentation\n      - url: openapi/1password-partnership-openapi.yml\n        type: OpenAPI\n      - url: json-ld/1password-partnership-context.jsonld\n        type: JSON-LD\n    description: >-\n      You can use the 1Password Partnership API to manage the provisioning and\n      deprovisioning of third-party partner billing accounts for your customers.\n      The API supports partner billing accounts for\
  \ 1Password individual and\n      family accounts. The Partnership API does not support 1Password team or\n      business accounts.\ncommon:\n  - type: Website\n    url: https://1password.com/\n  - type: Portal\n    url: https://developer.1password.com/\n  - type: Documentation\n    url: https://developer.1password.com/docs/\n  - type: GettingStarted\n    url: https://developer.1password.com/docs/get-started/\n  - type: Authentication\n    url: https://developer.1password.com/docs/connect/connect-api-reference/#authentication\n  - type: SDK\n    url: https://developer.1password.com/docs/sdks/\n    title: Official SDKs\n  - type: SDK\n    url: https://pypi.org/project/onepassword-sdk/\n    title: Python SDK\n  - type: SDK\n    url: https://www.npmjs.com/package/@1password/sdk\n    title: JavaScript SDK\n  - type: SDK\n    url: https://pkg.go.dev/github.com/1Password/onepassword-sdk-go\n    title: Go SDK\n  - type: SDK\n    url: https://pypi.org/project/onepassword-connect-sdk/\n    title:\
  \ Connect Python SDK\n  - type: SDK\n    url: https://www.npmjs.com/package/@1password/connect\n    title: Connect Node.js SDK\n  - type: SDK\n    url: https://pkg.go.dev/github.com/1Password/connect-sdk-go\n    title: Connect Go SDK\n  - type: CLI\n    url: https://developer.1password.com/docs/cli/\n    title: 1Password CLI\n  - type: Blog\n    url: https://blog.1password.com/\n  - type: Support\n    url: https://support.1password.com/\n  - type: PrivacyPolicy\n    url: https://1password.com/legal/privacy/\n  - type: TermsOfService\n    url: https://1password.com/legal/terms-of-service/\n  - type: SignUp\n    url: https://start.1password.com/sign-up/\n  - type: ChangeLog\n    url: https://developer.1password.com/docs/events-api/changelog/\n  - type: GitHubOrganization\n    url: https://github.com/1Password\n  - type: SpectralRules\n    url: rules/1password-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/1password-secrets-management.yaml\n  - type: Vocabulary\n \
  \   url: vocabulary/1password-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Secrets Management\n        description: Programmatic access to 1Password vaults and items via Connect Server API\n      - name: Security Monitoring\n        description: Real-time audit log streaming of sign-in events, item usage, and audit trails\n      - name: Partner Billing Management\n        description: Provision and deprovision 1Password accounts for partner customers\n      - name: SDKs\n        description: Official SDKs for Python, JavaScript/TypeScript, Go, and Connect-specific clients\n      - name: CLI\n        description: 1Password CLI for command-line secrets management and automation\n      - name: Kubernetes Integration\n        description: Kubernetes operator and secrets injector for cloud-native deployments\n      - name: Terraform Provider\n        description: Terraform provider to manage 1Password vault items as infrastructure\n      - name: GitHub Actions\n        description:\
  \ Load secrets from 1Password directly into GitHub Actions CI/CD pipelines\n  - type: UseCases\n    data:\n      - name: Secrets Injection\n        description: Inject secrets from 1Password into applications and containers at runtime\n      - name: Security Audit\n        description: Stream and analyze sign-in events and item usage for security incident response\n      - name: Compliance Reporting\n        description: Export audit trails for SOC2, GDPR, and other compliance frameworks\n      - name: CI/CD Secrets\n        description: Securely provide secrets to CI/CD pipelines without hardcoding credentials\n      - name: Infrastructure as Code\n        description: Manage secrets as part of Terraform or Ansible automation workflows\n      - name: Partner Account Provisioning\n        description: Automate provisioning of 1Password accounts for partner customer bases\n  - type: Integrations\n    data:\n      - name: Kubernetes\n        description: Native integration via operator and\
  \ secrets injector for Kubernetes deployments\n      - name: Terraform\n        description: Terraform provider for managing 1Password items as infrastructure resources\n      - name: Ansible\n        description: Ansible collection for 1Password Connect integration\n      - name: GitHub Actions\n        description: GitHub Actions to load and install 1Password secrets in CI/CD workflows\n      - name: Splunk\n        description: Events API Splunk integration for security event streaming\n      - name: HashiCorp Vault\n        description: Vault plugin for 1Password Connect secrets retrieval\n      - name: Helm Charts\n        description: Official Helm charts for deploying 1Password Connect on Kubernetes\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/apis.yml
tags:
- Password Manager
- Passwords
- Security
- Secrets
url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/apis.yml
use_cases:
- description: Inject secrets from 1Password into applications and containers at runtime
  name: Secrets Injection
- description: Stream and analyze sign-in events and item usage for security incident response
  name: Security Audit
- description: Export audit trails for SOC2, GDPR, and other compliance frameworks
  name: Compliance Reporting
- description: Securely provide secrets to CI/CD pipelines without hardcoding credentials
  name: CI/CD Secrets
- description: Manage secrets as part of Terraform or Ansible automation workflows
  name: Infrastructure as Code
- description: Automate provisioning of 1Password accounts for partner customer bases
  name: Partner Account Provisioning
---
