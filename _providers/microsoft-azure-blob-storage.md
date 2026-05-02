---
api_count: 3
api_specs:
- filename: blob.json
  format: json
  label: Azure Blob Storage REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/storage/data-plane/Microsoft.BlobStorage/stable/2021-12-02/blob.json
- filename: storage.json
  format: json
  label: Azure Storage Resource Provider REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/storage/resource-manager/Microsoft.Storage/stable/2023-05-01/storage.json
apis:
- description: The REST API for Azure Blob Storage provides operations for working with blobs and containers, including create, read, update, and delete operations.
  name: Azure Blob Storage REST API
  slug: ''
- description: The Azure Data Lake Storage Gen2 REST APIs allow interaction with Azure Blob Storage through a file system interface. They enable creation and management of file systems, directories, and files on sto
  name: Azure Data Lake Storage Gen2 REST API
  slug: ''
- description: The Azure Storage Resource Provider REST API enables programmatic management of storage accounts and related resources through Azure Resource Manager. It supports operations such as creating, updating
  name: Azure Storage Resource Provider REST API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/options/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/topics/storage/
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction
- title: ''
  type: Change Log
  url: https://learn.microsoft.com/en-us/rest/api/storageservices/previous-azure-storage-service-versions
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/storage/blobs/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/rest/api/storageservices/authorize-requests-to-azure-storage
- title: ''
  type: Quotas
  url: https://learn.microsoft.com/en-us/azure/storage/blobs/scalability-targets
- title: ''
  type: Website
  url: https://azure.microsoft.com/en-us/products/storage/blobs/
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/free/
- title: ''
  type: Console
  url: https://portal.azure.com/
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/azure/storage/common/storage-srp-overview
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/azure-blob-storage
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure
- title: ''
  type: Developer Tools
  url: https://azure.microsoft.com/en-us/products/storage/storage-explorer
- title: ''
  type: Security
  url: https://learn.microsoft.com/en-us/security/benchmark/azure/baselines/storage-security-baseline
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/storage/blobs/
created: '2024'
description: Microsoft Azure Blob Storage is a service for storing large amounts of unstructured object data, such as text or binary data, that can be accessed from anywhere in the world via HTTP or HTTPS.
features: []
image: https://azure.microsoft.com/svghandler/storage-blobs/
integrations: []
layout: provider
modified: '2026-04-28'
name: Azure Blob Storage
skills: []
slug: microsoft-azure-blob-storage
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Blob Storage\ndescription: Microsoft Azure Blob Storage is a service for storing large amounts of unstructured object data, such as text or binary data, that can be accessed from anywhere in the world via HTTP or HTTPS.\nimage: https://azure.microsoft.com/svghandler/storage-blobs/\ntags:\n  - Azure\n  - Blobs\n  - Cloud Storage\n  - Microsoft\n  - Object Storage\n  - Storage\ncreated: '2024'\nmodified: '2026-04-28'\nurl: https://azure.microsoft.com/en-us/services/storage/blobs/\napis:\n  - name: Azure Blob Storage REST API\n    description: The REST API for Azure Blob Storage provides operations for working with blobs and containers, including create, read, update, and delete operations.\n    image: https://azure.microsoft.com/svghandler/storage-blobs/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/storageservices/blob-service-rest-api\n    baseURL: https://{accountName}.blob.core.windows.net\n    tags:\n      - Blobs\n      - Containers\n      - REST\
  \ API\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/storageservices/blob-service-rest-api\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/storage/data-plane/Microsoft.BlobStorage/stable/2021-12-02/blob.json\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/rest/api/storageservices/authorize-requests-to-azure-storage\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/storage/blobs/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction#client-libraries\n      - type: Quickstart\n        url: https://learn.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-portal\n      - type: Tutorials\n        url: https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-overview\n      - type: Code Samples\n        url: https://learn.microsoft.com/en-us/azure/storage/blobs/storage-samples-blobs-cli\n\
  \      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/storageservices/operations-on-blobs\n      - type: Change Log\n        url: https://learn.microsoft.com/en-us/rest/api/storageservices/versioning-for-the-azure-storage-services\n      - type: Quotas\n        url: https://learn.microsoft.com/en-us/azure/storage/blobs/scalability-targets\n      - type: GitHubRepository\n        url: https://github.com/Azure/azure-rest-api-specs\n  - name: Azure Data Lake Storage Gen2 REST API\n    description: The Azure Data Lake Storage Gen2 REST APIs allow interaction with Azure Blob Storage through a file system interface. They enable creation and management of file systems, directories, and files on storage accounts with hierarchical namespace enabled, supporting big data analytics workloads.\n    image: https://azure.microsoft.com/svghandler/storage-blobs/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/storageservices/data-lake-storage-gen2\n    baseURL: https://{accountName}.dfs.core.windows.net\n\
  \    tags:\n      - Big Data\n      - Data Lake\n      - File System\n      - Hierarchical Namespace\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/storageservices/data-lake-storage-gen2\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/storageservices/datalakestoragegen2/filesystem\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/rest/api/storageservices/authorize-requests-to-azure-storage\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/storage/blobs/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction#client-libraries\n  - name: Azure Storage Resource Provider REST API\n    description: The Azure Storage Resource Provider REST API enables programmatic\
  \ management of storage accounts and related resources through Azure Resource Manager. It supports operations such as creating, updating, listing, and deleting storage accounts, managing access keys, and configuring storage account properties.\n    image: https://azure.microsoft.com/svghandler/storage-blobs/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/storagerp/\n    baseURL: https://management.azure.com\n    tags:\n      - Administration\n      - Management\n      - Resource Provider\n      - Storage Accounts\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/storagerp/\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/storagerp/storage-accounts\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/storage/common/authorization-resource-provider\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/storage/resource-manager/Microsoft.Storage/stable/2023-05-01/storage.json\n\
  common:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Status\n    url: https://status.azure.com/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/options/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/topics/storage/\n  - type: Terms of Service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction\n  - type: Change Log\n    url: https://learn.microsoft.com/en-us/rest/api/storageservices/previous-azure-storage-service-versions\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/storage/blobs/\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/rest/api/storageservices/authorize-requests-to-azure-storage\n  - type: Quotas\n    url: https://learn.microsoft.com/en-us/azure/storage/blobs/scalability-targets\n\
  \  - type: Website\n    url: https://azure.microsoft.com/en-us/products/storage/blobs/\n  - type: Sign Up\n    url: https://azure.microsoft.com/en-us/free/\n  - type: Console\n    url: https://portal.azure.com/\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/azure/storage/common/storage-srp-overview\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/azure-blob-storage\n  - type: GitHub Organization\n    url: https://github.com/Azure\n  - type: Developer Tools\n    url: https://azure.microsoft.com/en-us/products/storage/storage-explorer\n  - type: Security\n    url: https://learn.microsoft.com/en-us/security/benchmark/azure/baselines/storage-security-baseline\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/storage/blobs/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-blob-storage/refs/heads/main/apis.yml
tags:
- Azure
- Blobs
- Cloud Storage
- Microsoft
- Object Storage
- Storage
url: https://azure.microsoft.com/en-us/services/storage/blobs/
use_cases: []
---
