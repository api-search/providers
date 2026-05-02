---
api_count: 2
apis:
- description: Azure AI Search provides REST APIs for creating and managing search indexes, loading documents, running full-text and vector queries, configuring AI enrichment pipelines with skillsets, and managing i
  name: Azure AI Search REST API
  slug: rest-api
- description: The management REST API provides operations for creating and managing Azure AI Search service instances, scaling replicas and partitions, and managing keys and shared private link resources.
  name: Azure AI Search Management REST API
  slug: management-api
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/search/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/search/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/search/search-get-started-portal
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/azure/search/search-howto-dotnet-sdk
- title: ''
  type: Status
  url: https://azure.status.microsoft/en-us/status
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Support
  url: https://support.microsoft.com/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/product/azure-cognitive-search/
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/azure-cognitive-search
created: '2026-03-13'
description: Azure AI Search (formerly Azure Cognitive Search) is a cloud search service with built-in AI capabilities for enriching content and enabling vector and semantic search over heterogeneous data. It indexes content from Azure data sources and supports full-text, faceted, geospatial, vector, and hybrid retrieval.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Azure AI Search
skills: []
slug: microsoft-azure-search
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-azure-search\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-search/refs/heads/main/apis.yml\nname: Azure AI Search\ndescription: >-\n  Azure AI Search (formerly Azure Cognitive Search) is a cloud search service with\n  built-in AI capabilities for enriching content and enabling vector and semantic\n  search over heterogeneous data. It indexes content from Azure data sources and\n  supports full-text, faceted, geospatial, vector, and hybrid retrieval.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI Search\n  - Cognitive Search\n  - Hybrid Search\n  - Search\n  - Semantic Search\n  - Vector Search\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\napis:\n  - aid: microsoft-azure-search:rest-api\n    name: Azure AI Search REST API\n    description: >-\n      Azure AI Search provides REST APIs for creating and managing search indexes,\n      loading documents, running\
  \ full-text and vector queries, configuring AI\n      enrichment pipelines with skillsets, and managing indexers for automatic\n      data ingestion from Azure data sources.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/rest/api/searchservice/\n    baseURL: https://{search-service}.search.windows.net/\n    tags:\n      - Indexers\n      - Indexes\n      - Search\n      - Skillsets\n      - Vector Search\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/searchservice/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/search/search-security-api-keys\n      - type: Versioning\n        url: https://learn.microsoft.com/en-us/rest/api/searchservice/search-service-api-versions\n  - aid: microsoft-azure-search:management-api\n    name: Azure AI Search Management REST API\n    description: >-\n      The management REST API\
  \ provides operations for creating and managing\n      Azure AI Search service instances, scaling replicas and partitions,\n      and managing keys and shared private link resources.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/rest/api/searchmanagement/\n    baseURL: https://management.azure.com/\n    tags:\n      - Management\n      - Provisioning\n      - Search\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/searchmanagement/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/authentication-flows-app-scenarios\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/search/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/search/\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/search/search-get-started-portal\n\
  \  - type: SDKs\n    url: https://learn.microsoft.com/en-us/azure/search/search-howto-dotnet-sdk\n  - type: Status\n    url: https://azure.status.microsoft/en-us/status\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Support\n    url: https://support.microsoft.com/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/product/azure-cognitive-search/\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/azure-cognitive-search\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-search/refs/heads/main/apis.yml
tags:
- AI Search
- Cognitive Search
- Hybrid Search
- Search
- Semantic Search
- Vector Search
url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-search/refs/heads/main/apis.yml
use_cases: []
---
