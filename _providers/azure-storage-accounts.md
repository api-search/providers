---
api_count: 2
apis:
- description: REST API for operations on blobs in Azure Storage.
  name: Azure Storage Blob Service API
  slug: azure-storage-blob-service-api
- description: REST API for managing Azure Storage accounts and resources.
  name: Azure Storage Management API
  slug: azure-storage-management-api
capabilities:
- description: Workflow capability for managing Azure Storage Accounts resources. Used by cloud engineers and DevOps teams.
  name: Azure Storage Accounts Management
  slug: azure-storage-accounts-management
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/#blade/HubsExtension/BrowseResource/resourceType/Microsoft.Storage%2FStorageAccounts
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/storage/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/storage/common/storage-account-create
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/rest/api/storageservices/authorize-requests-to-azure-storage
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/azure/storage/common/storage-apis-and-sdks
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/rules/azure-storage-accounts-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/vocabulary/azure-storage-accounts-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/json-ld/azure-storage-accounts-context.jsonld
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/capabilities/azure-storage-accounts-management.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/capabilities/shared/azure-storage-accounts.yaml
created: '2024-01-01'
description: Azure Storage is Microsoft's cloud storage solution for modern data storage scenarios offering highly available, massively scalable, durable, and secure storage for blobs, files, queues, tables, and disks.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Azure Storage Accounts Context
  property_count: 56
  slug: azure-storage-accounts-context
layout: provider
modified: '2026-04-19'
name: Azure Storage Accounts
rules:
- name: Azure Storage Accounts API Rules
  rule_count: 15
  severity_counts:
    error: 5
    hint: 0
    info: 4
    warn: 6
  slug: azure-storage-accounts-spectral-rules
skills: []
slug: azure-storage-accounts
solutions: []
source_yaml: "aid: azure-storage-accounts\nname: Azure Storage Accounts\ndescription: >-\n  Azure Storage is Microsoft's cloud storage solution for modern data storage\n  scenarios offering highly available, massively scalable, durable, and secure\n  storage for blobs, files, queues, tables, and disks.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Azure\n- Blob Storage\n- Cloud Storage\n- File Storage\n- Queue Storage\n- Storage\n- Table Storage\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: azure-storage-accounts:azure-storage-blob-service-api\n  name: Azure Storage Blob Service API\n  description: REST API for operations on blobs in Azure Storage.\n  humanURL: https://learn.microsoft.com/en-us/rest/api/storageservices/blob-service-rest-api\n  baseURL: https://{accountName}.blob.core.windows.net\n\
  \  tags:\n  - Binary Data\n  - Blob Storage\n  - Object Storage\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/rest/api/storageservices/blob-service-rest-api\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/storage/data-plane/Microsoft.BlobStorage/stable/2023-11-03/blob.json\n- aid: azure-storage-accounts:azure-storage-management-api\n  name: Azure Storage Management API\n  description: REST API for managing Azure Storage accounts and resources.\n  humanURL: https://learn.microsoft.com/en-us/rest/api/storagerp/\n  baseURL: https://management.azure.com\n  tags:\n  - Azure Resource Manager\n  - Management\n  - Resource Provider\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/rest/api/storagerp/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/storage/resource-manager/Microsoft.Storage/stable/2023-01-01/storage.json\n\
  common:\n- type: Portal\n  url: https://portal.azure.com/#blade/HubsExtension/BrowseResource/resourceType/Microsoft.Storage%2FStorageAccounts\n- type: Documentation\n  url: https://learn.microsoft.com/en-us/azure/storage/\n- type: Getting Started\n  url: https://learn.microsoft.com/en-us/azure/storage/common/storage-account-create\n- type: Authentication\n  url: https://learn.microsoft.com/en-us/rest/api/storageservices/authorize-requests-to-azure-storage\n- type: SDKs\n  url: https://learn.microsoft.com/en-us/azure/storage/common/storage-apis-and-sdks\n- type: Status\n  url: https://status.azure.com/\n- type: Support\n  url: https://azure.microsoft.com/en-us/support/\n- type: Terms of Service\n  url: https://azure.microsoft.com/en-us/support/legal/\n- type: Privacy Policy\n  url: https://privacy.microsoft.com/en-us/privacystatement\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/rules/azure-storage-accounts-spectral-rules.yml\n\
  - type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/vocabulary/azure-storage-accounts-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/json-ld/azure-storage-accounts-context.jsonld\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/capabilities/azure-storage-accounts-management.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/capabilities/shared/azure-storage-accounts.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/apis.yml
tags:
- Azure
- Blob Storage
- Cloud Storage
- File Storage
- Queue Storage
- Storage
- Table Storage
url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/apis.yml
use_cases: []
---
