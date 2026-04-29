---
api_count: 5
apis:
- description: REST API for managing vaults, keys, secrets, and certificates in Azure Key Vault.
  name: Azure Key Vault API
  slug: ''
- description: API for performing cryptographic operations and managing keys, secrets, and certificates within a specific Key Vault instance.
  name: Azure Key Vault Data Plane API
  slug: ''
- description: 'REST API for creating, importing, updating, and performing cryptographic operations with keys in Azure Key Vault. Supports RSA, EC, and symmetric key types with operations including encrypt, decrypt, '
  name: Azure Key Vault Keys API
  slug: ''
- description: REST API for securely storing and managing secrets such as passwords, connection strings, and API keys in Azure Key Vault.
  name: Azure Key Vault Secrets API
  slug: ''
- description: REST API for creating, importing, managing, and renewing certificates in Azure Key Vault.
  name: Azure Key Vault Certificates API
  slug: ''
capabilities:
- description: Unified workflow for managing cryptographic keys, secrets, and certificates with encryption, signing, and certificate lifecycle operations. Used by security engineers and DevOps teams.
  name: Azure Key Vault Secrets and Keys
  slug: secrets-and-keys
common:
- title: ''
  type: StatusPage
  url: https://status.azure.com/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/
- title: ''
  type: TermsOfService
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: ChangeLog
  url: https://docs.microsoft.com/en-us/azure/key-vault/general/whats-new
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/key-vault/
- title: ''
  type: SpectralRules
  url: rules/azure-key-vault-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/azure-key-vault-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/secrets-and-keys.yaml
created: '2024'
description: Azure Key Vault is a cloud service for securely storing and accessing secrets, keys, and certificates. It helps safeguard cryptographic keys and secrets used by cloud applications and services.
features:
- description: Create, import, and manage cryptographic keys with support for RSA, EC, and symmetric key types.
  name: Key Management
- description: Securely store and control access to passwords, connection strings, API keys, and other secrets.
  name: Secrets Management
- description: Automate certificate creation, renewal, and management with certificate authority integration.
  name: Certificate Lifecycle
- description: Perform encrypt, decrypt, sign, verify, wrap, and unwrap operations using managed keys.
  name: Cryptographic Operations
- description: Use hardware security modules for FIPS 140-2 Level 2 validated key protection.
  name: HSM-Backed Keys
- description: Recover accidentally deleted vaults, keys, secrets, and certificates with configurable retention.
  name: Soft Delete and Purge Protection
image: https://azure.microsoft.com/svghandler/key-vault/
integrations:
- description: Reference Key Vault secrets and certificates directly from App Service configuration.
  name: Azure App Service
- description: Mount Key Vault secrets as volumes in AKS pods using the Secrets Store CSI Driver.
  name: Azure Kubernetes Service
- description: Use Key Vault secrets in CI/CD pipelines for secure deployment automation.
  name: Azure DevOps
- description: Encrypt Azure VM disks using customer-managed keys stored in Key Vault.
  name: Azure Disk Encryption
- description: Enable Transparent Data Encryption with customer-managed keys from Key Vault.
  name: Azure SQL Database
jsonld:
- class_count: 0
  name: Azure Key Vault Context
  property_count: 57
  slug: azure-key-vault-context
- class_count: 0
  name: Azure Key Vault Data Plane Context
  property_count: 0
  slug: azure-key-vault-data-plane-context
layout: provider
modified: '2026-04-18'
name: Azure Key Vault
rules:
- name: Azure Key Vault API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: azure-key-vault-spectral-rules
skills: []
slug: azure-key-vault
solutions: []
source_yaml: "name: Azure Key Vault\ndescription: >-\n  Azure Key Vault is a cloud service for securely storing and accessing secrets, keys,\n  and certificates. It helps safeguard cryptographic keys and secrets used by cloud\n  applications and services.\nimage: https://azure.microsoft.com/svghandler/key-vault/\ntags:\n  - Certificates\n  - Cloud Security\n  - Cryptography\n  - Key Management\n  - Secrets Management\n  - Security\ncreated: '2024'\nmodified: '2026-04-18'\nurl: https://azure.microsoft.com/en-us/services/key-vault/\nspecificationVersion: '0.18'\napis:\n  - name: Azure Key Vault API\n    description: >-\n      REST API for managing vaults, keys, secrets, and certificates in Azure Key Vault.\n    image: https://azure.microsoft.com/svghandler/key-vault/\n    humanURL: https://azure.microsoft.com/en-us/services/key-vault/\n    baseURL: https://management.azure.com\n    tags:\n      - Certificates\n      - Keys\n      - Secrets\n      - Vaults\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.microsoft.com/en-us/azure/key-vault/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/keyvault/resource-manager/Microsoft.KeyVault/stable/2023-02-01/keyvault.json\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/key-vault/\n      - type: GettingStarted\n        url: https://docs.microsoft.com/en-us/azure/key-vault/general/overview\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/azure/key-vault/general/authentication\n      - type: BestPractices\n        url: https://docs.microsoft.com/en-us/azure/key-vault/general/best-practices\n      - type: Security\n        url: https://learn.microsoft.com/en-us/azure/key-vault/general/secure-key-vault\n    contact:\n      - type: Support\n        url: https://azure.microsoft.com/en-us/support/\n  - name: Azure Key Vault Data Plane API\n    description: >-\n      API for performing cryptographic\
  \ operations and managing keys, secrets, and\n      certificates within a specific Key Vault instance.\n    image: https://azure.microsoft.com/svghandler/key-vault/\n    humanURL: https://docs.microsoft.com/en-us/rest/api/keyvault/\n    baseURL: https://{vault-name}.vault.azure.net\n    tags:\n      - Certificate Operations\n      - Cryptographic Operations\n      - Key Operations\n      - Secret Operations\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/rest/api/keyvault/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/keyvault/data-plane/Microsoft.KeyVault/stable/7.4/keyvault.json\n      - type: OpenAPI\n        url: openapi/azure-key-vault-data-plane-openapi.yml\n      - type: APIReference\n        url: https://docs.microsoft.com/en-us/rest/api/keyvault/keys\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-secret-schema.json\n      - type: JSONSchema\n\
  \        url: json-schema/azure-key-vault-data-plane-key-bundle-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-key-create-parameters-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-key-item-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-key-list-result-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-key-operation-result-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-key-operations-parameters-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-key-sign-parameters-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-key-update-parameters-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-key-verify-parameters-schema.json\n      - type: JSONSchema\n        url:\
  \ json-schema/azure-key-vault-data-plane-key-verify-result-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-key-attributes-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-key-properties-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-key-release-policy-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-json-web-key-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-json-web-key-type-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-json-web-key-operation-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-json-web-key-curve-name-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-secret-bundle-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-secret-set-parameters-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-secret-update-parameters-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-secret-item-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-secret-list-result-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-secret-attributes-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-secret-properties-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-secret-restore-parameters-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-backup-secret-result-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-certificate-bundle-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-certificate-create-parameters-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-certificate-import-parameters-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-certificate-update-parameters-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-certificate-item-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-certificate-list-result-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-certificate-attributes-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-certificate-operation-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-certificate-policy-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-issuer-parameters-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-lifetime-action-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-subject-alternative-names-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-x509-certificate-properties-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-deleted-key-bundle-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-deleted-secret-bundle-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-deleted-certificate-bundle-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-deletion-recovery-level-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-error-schema.json\n      - type: JSONSchema\n        url: json-schema/azure-key-vault-data-plane-key-vault-error-schema.json\n      - type: JSONLD\n        url: json-ld/azure-key-vault-context.jsonld\n      - type: JSONLD\n     \
  \   url: json-ld/azure-key-vault-data-plane-context.jsonld\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/dotnet/api/overview/azure/security.keyvault.keys-readme\n        title: .NET SDK\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/python/api/overview/azure/keyvault-keys-readme\n        title: Python SDK\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/java/api/overview/azure/security-keyvault-keys-readme\n        title: Java SDK\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/javascript/api/overview/azure/keyvault-keys-readme\n        title: JavaScript SDK\n    contact:\n      - type: Support\n        url: https://azure.microsoft.com/en-us/support/\n  - name: Azure Key Vault Keys API\n    description: >-\n      REST API for creating, importing, updating, and performing cryptographic operations\n      with keys in Azure Key Vault. Supports RSA, EC, and symmetric key types with\n      operations including encrypt,\
  \ decrypt, sign, verify, wrap, and unwrap.\n    image: https://azure.microsoft.com/svghandler/key-vault/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/keyvault/keys\n    baseURL: https://{vault-name}.vault.azure.net\n    tags:\n      - Cryptographic Operations\n      - Encryption\n      - HSM\n      - Keys\n      - Signing\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/key-vault/keys/about-keys\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/keyvault/keys\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/key-vault/keys/quick-create-net\n    contact:\n      - type: Support\n        url: https://azure.microsoft.com/en-us/support/\n  - name: Azure Key Vault Secrets API\n    description: >-\n      REST API for securely storing and managing secrets such as passwords, connection\n      strings, and API keys in Azure Key Vault.\n    image: https://azure.microsoft.com/svghandler/key-vault/\n\
  \    humanURL: https://learn.microsoft.com/en-us/rest/api/keyvault/secrets\n    baseURL: https://{vault-name}.vault.azure.net\n    tags:\n      - Connection Strings\n      - Passwords\n      - Secrets\n      - Secure Storage\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/key-vault/secrets/about-secrets\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/keyvault/secrets\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/key-vault/secrets/quick-create-net\n    contact:\n      - type: Support\n        url: https://azure.microsoft.com/en-us/support/\n  - name: Azure Key Vault Certificates API\n    description: >-\n      REST API for creating, importing, managing, and renewing certificates in Azure\n      Key Vault.\n    image: https://azure.microsoft.com/svghandler/key-vault/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/keyvault/certificates\n    baseURL: https://{vault-name}.vault.azure.net\n\
  \    tags:\n      - Certificate Authorities\n      - Certificate Management\n      - Certificates\n      - SSL\n      - TLS\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/key-vault/certificates/about-certificates\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/keyvault/certificates\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/key-vault/certificates/quick-create-net\n    contact:\n      - type: Support\n        url: https://azure.microsoft.com/en-us/support/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: StatusPage\n    url: https://status.azure.com/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/\n  - type: TermsOfService\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: ChangeLog\n    url: https://docs.microsoft.com/en-us/azure/key-vault/general/whats-new\n\
  \  - type: Portal\n    url: https://portal.azure.com/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/key-vault/\n  - type: SpectralRules\n    url: rules/azure-key-vault-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/azure-key-vault-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/secrets-and-keys.yaml\n  - type: Features\n    data:\n      - name: Key Management\n        description: Create, import, and manage cryptographic keys with support for RSA, EC, and symmetric key types.\n      - name: Secrets Management\n        description: Securely store and control access to passwords, connection strings, API keys, and other secrets.\n      - name: Certificate Lifecycle\n        description: Automate certificate creation, renewal, and management with certificate authority integration.\n      - name: Cryptographic Operations\n        description: Perform encrypt,\
  \ decrypt, sign, verify, wrap, and unwrap operations using managed keys.\n      - name: HSM-Backed Keys\n        description: Use hardware security modules for FIPS 140-2 Level 2 validated key protection.\n      - name: Soft Delete and Purge Protection\n        description: Recover accidentally deleted vaults, keys, secrets, and certificates with configurable retention.\n  - type: UseCases\n    data:\n      - name: Application Secret Management\n        description: Centralize and secure application secrets with audited access and automatic rotation.\n      - name: Data Encryption\n        description: Encrypt data at rest and in transit using customer-managed keys stored in Key Vault.\n      - name: TLS Certificate Management\n        description: Automate TLS certificate provisioning and renewal for web applications and services.\n      - name: Code and Document Signing\n        description: Sign code, documents, and artifacts using keys stored securely in Key Vault.\n  - type: Integrations\n\
  \    data:\n      - name: Azure App Service\n        description: Reference Key Vault secrets and certificates directly from App Service configuration.\n      - name: Azure Kubernetes Service\n        description: Mount Key Vault secrets as volumes in AKS pods using the Secrets Store CSI Driver.\n      - name: Azure DevOps\n        description: Use Key Vault secrets in CI/CD pipelines for secure deployment automation.\n      - name: Azure Disk Encryption\n        description: Encrypt Azure VM disks using customer-managed keys stored in Key Vault.\n      - name: Azure SQL Database\n        description: Enable Transparent Data Encryption with customer-managed keys from Key Vault.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-key-vault/refs/heads/main/apis.yml
tags:
- Certificates
- Cloud Security
- Cryptography
- Key Management
- Secrets Management
- Security
url: https://azure.microsoft.com/en-us/services/key-vault/
use_cases:
- description: Centralize and secure application secrets with audited access and automatic rotation.
  name: Application Secret Management
- description: Encrypt data at rest and in transit using customer-managed keys stored in Key Vault.
  name: Data Encryption
- description: Automate TLS certificate provisioning and renewal for web applications and services.
  name: TLS Certificate Management
- description: Sign code, documents, and artifacts using keys stored securely in Key Vault.
  name: Code and Document Signing
---
