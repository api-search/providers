---
api_count: 4
apis:
- description: REST API for storing and managing unstructured data as blobs.
  name: Azure Blob Storage API
  slug: azure-blob-storage-api
- description: REST API for storing and retrieving messages in queues.
  name: Azure Queue Storage API
  slug: azure-queue-storage-api
- description: REST API for storing structured NoSQL data in the cloud.
  name: Azure Table Storage API
  slug: azure-table-storage-api
- description: REST API for managed file shares using SMB and NFS protocols.
  name: Azure File Storage API
  slug: azure-file-storage-api
capabilities:
- description: Workflow capability for managing Azure Storage Account resources. Used by cloud engineers and DevOps teams.
  name: Azure Storage Account Management
  slug: azure-storage-account-management
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/storage/
- title: ''
  type: SDKs
  url: https://azure.microsoft.com/en-us/downloads/
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
  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/rules/azure-storage-account-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/vocabulary/azure-storage-account-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/json-ld/azure-storage-account-context.jsonld
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/capabilities/azure-storage-account-management.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/capabilities/shared/azure-storage-account.yaml
created: '2024-01-01'
description: Collection of APIs for Azure Storage Account services including Blob, Queue, Table, and File storage, providing highly available, massively scalable, durable, and secure storage for a variety of data objects.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Azure Storage Account Context
  property_count: 56
  slug: azure-storage-account-context
layout: provider
modified: '2026-04-19'
name: Azure Storage Account
rules:
- name: Azure Storage Account API Rules
  rule_count: 15
  severity_counts:
    error: 5
    hint: 0
    info: 4
    warn: 6
  slug: azure-storage-account-spectral-rules
skills: []
slug: azure-storage-account
solutions: []
source_filename: apis.yml
source_yaml: "aid: azure-storage-account\nname: Azure Storage Account\ndescription: >-\n  Collection of APIs for Azure Storage Account services including Blob, Queue,\n  Table, and File storage, providing highly available, massively scalable,\n  durable, and secure storage for a variety of data objects.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Azure\n- Blob Storage\n- Cloud Storage\n- File Storage\n- Microsoft\n- Storage\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: azure-storage-account:azure-blob-storage-api\n  name: Azure Blob Storage API\n  description: REST API for storing and managing unstructured data as blobs.\n  humanURL: https://learn.microsoft.com/en-us/rest/api/storageservices/blob-service-rest-api\n  baseURL: https://{account}.blob.core.windows.net\n  tags:\n \
  \ - Blob Storage\n  - Object Storage\n  - Unstructured Data\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/storage/blobs/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/storage/data-plane/Microsoft.BlobStorage/stable/2021-12-02/blob.json\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/rest/api/storageservices/authorize-requests-to-azure-storage\n- aid: azure-storage-account:azure-queue-storage-api\n  name: Azure Queue Storage API\n  description: REST API for storing and retrieving messages in queues.\n  humanURL: https://learn.microsoft.com/en-us/rest/api/storageservices/queue-service-rest-api\n  baseURL: https://{account}.queue.core.windows.net\n  tags:\n  - Asynchronous Processing\n  - Message Queue\n  - Queue Storage\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/storage/queues/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/openapi/azure-storage-account-management-openapi.yaml\n\
  \  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/openapi/azure-storage-account-blob-openapi.yaml\n- aid: azure-storage-account:azure-table-storage-api\n  name: Azure Table Storage API\n  description: REST API for storing structured NoSQL data in the cloud.\n  humanURL: https://learn.microsoft.com/en-us/rest/api/storageservices/table-service-rest-api\n  baseURL: https://{account}.table.core.windows.net\n  tags:\n  - NoSQL\n  - Structured Data\n  - Table Storage\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/storage/tables/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/openapi/azure-storage-account-management-openapi.yaml\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/openapi/azure-storage-account-blob-openapi.yaml\n- aid: azure-storage-account:azure-file-storage-api\n\
  \  name: Azure File Storage API\n  description: REST API for managed file shares using SMB and NFS protocols.\n  humanURL: https://learn.microsoft.com/en-us/rest/api/storageservices/file-service-rest-api\n  baseURL: https://{account}.file.core.windows.net\n  tags:\n  - File Shares\n  - File Storage\n  - SMB\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/storage/files/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/openapi/azure-storage-account-management-openapi.yaml\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/openapi/azure-storage-account-blob-openapi.yaml\ncommon:\n- type: Portal\n  url: https://portal.azure.com\n- type: Documentation\n  url: https://learn.microsoft.com/en-us/azure/storage/\n- type: SDKs\n  url: https://azure.microsoft.com/en-us/downloads/\n- type: Status\n  url: https://status.azure.com/\n\
  - type: Support\n  url: https://azure.microsoft.com/en-us/support/\n- type: Terms of Service\n  url: https://azure.microsoft.com/en-us/support/legal/\n- type: Privacy Policy\n  url: https://privacy.microsoft.com/en-us/privacystatement\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/rules/azure-storage-account-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/vocabulary/azure-storage-account-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/json-ld/azure-storage-account-context.jsonld\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/capabilities/azure-storage-account-management.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/capabilities/shared/azure-storage-account.yaml\n\
  maintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/apis.yml
tags:
- Azure
- Blob Storage
- Cloud Storage
- File Storage
- Microsoft
- Storage
url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/apis.yml
use_cases: []
---
