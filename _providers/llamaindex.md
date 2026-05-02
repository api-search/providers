---
api_count: 6
api_specs:
- filename: llamaindex-llamacloud-api-openapi.yml
  format: yaml
  label: LlamaIndex LlamaCloud API
  slug: llamacloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/openapi/llamaindex-llamacloud-api-openapi.yml
- filename: llamaindex-llamaparse-api-openapi.yml
  format: yaml
  label: LlamaIndex LlamaParse API
  slug: llamaparse-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/openapi/llamaindex-llamaparse-api-openapi.yml
- filename: llamaindex-llamaextract-api-openapi.yml
  format: yaml
  label: LlamaIndex LlamaExtract API
  slug: llamaextract-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/openapi/llamaindex-llamaextract-api-openapi.yml
- filename: llamaindex-llamacloud-index-api-openapi.yml
  format: yaml
  label: LlamaIndex LlamaCloud Index API
  slug: llamacloud-index-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/openapi/llamaindex-llamacloud-index-api-openapi.yml
apis:
- description: The LlamaCloud API is the central REST API for LlamaIndex's cloud platform, providing programmatic access to managed document processing, indexing, and retrieval services. It enables developers to bui
  name: LlamaIndex LlamaCloud API
  slug: llamacloud-api
- description: LlamaParse is a GenAI-native document parsing API that can parse complex document data for any downstream LLM use case including agents, RAG pipelines, and data processing workflows. The v2 API provid
  name: LlamaIndex LlamaParse API
  slug: llamaparse-api
- description: LlamaExtract is a prebuilt agentic data extraction API that transforms unstructured document data into structured JSON representations. The REST API allows developers to create extraction agents, uplo
  name: LlamaIndex LlamaExtract API
  slug: llamaextract-api
- description: 'The LlamaCloud Index API provides a fully automated document ingestion pipeline with built-in retrieval capabilities. It allows developers to create and manage indexes, upload documents for automatic '
  name: LlamaIndex LlamaCloud Index API
  slug: llamacloud-index-api
- description: LlamaIndex is an open-source Python framework for building LLM-powered applications including agents, RAG pipelines, and custom workflows. It provides data connectors for ingesting data from various s
  name: LlamaIndex Python Framework
  slug: python-framework
- description: LlamaIndex TypeScript is the JavaScript and TypeScript implementation of the LlamaIndex framework for building LLM-powered applications. It provides server-side TypeScript support for building agents,
  name: LlamaIndex TypeScript Framework
  slug: typescript-framework
common:
- title: ''
  type: JSON-LD
  url: json-ld/llamaindex-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/llamaindex-pipeline-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/llamaindex-extraction-agent-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/llamaindex-parse-job-schema.json
created: ''
description: LlamaCloud is a hosted service for document processing and search, powered by LlamaIndex.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Llamaindex Context
  property_count: 9
  slug: llamaindex-context
layout: provider
modified: '2026-04-28'
name: llamaindex
skills: []
slug: llamaindex
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: llamaindex\nurl: https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/apis.yml\nmodified: '2026-04-28'\napis:\n  - aid: llamaindex:llamacloud-api\n    name: LlamaIndex LlamaCloud API\n    tags:\n      - Agents\n      - Artificial Intelligence\n      - Cloud\n      - Documents\n      - LLM\n      - RAG\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloud.llamaindex.ai\n    humanURL: https://developers.api.llamaindex.ai/\n    properties:\n      - url: https://developers.api.llamaindex.ai/\n        type: Documentation\n      - url: openapi/llamaindex-llamacloud-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The LlamaCloud API is the central REST API for LlamaIndex's cloud platform,\n      providing\n      programmatic access to managed document processing, indexing, and retrieval\n      services. It\n      enables developers to build production-grade LLM applications\
  \ by leveraging\n      cloud-hosted\n      infrastructure for document ingestion, knowledge management, and agent orchestration.\n      The\n      API supports authentication via API keys and is available in both US and EU\n      regions.\n  - aid: llamaindex:llamaparse-api\n    name: LlamaIndex LlamaParse API\n    tags:\n      - Artificial Intelligence\n      - Document Parsing\n      - LLM\n      - OCR\n      - PDF\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloud.llamaindex.ai\n    humanURL: https://developers.llamaindex.ai/python/cloud/llamaparse/api-v2-guide/\n    properties:\n      - url: https://developers.llamaindex.ai/python/cloud/llamaparse/api-v2-guide/\n        type: Documentation\n      - url: openapi/llamaindex-llamaparse-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      LlamaParse is a GenAI-native document parsing API that can parse complex document\n      data\n      for any downstream\
  \ LLM use case including agents, RAG pipelines, and data processing\n      workflows. The v2 API provides two main endpoints for parsing: one for JSON\n      requests\n      accepting file IDs or URLs, and another for multipart file uploads. It supports\n      multiple\n      parsing tiers including fast, cost-effective, agentic, and agentic-plus modes,\n      and returns\n      results asynchronously via job polling.\n  - aid: llamaindex:llamaextract-api\n    name: LlamaIndex LlamaExtract API\n    tags:\n      - Artificial Intelligence\n      - Data Extraction\n      - Documents\n      - JSON\n      - Structured Data\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloud.llamaindex.ai\n    humanURL: https://developers.llamaindex.ai/python/cloud/llamaextract/getting_started/api/\n    properties:\n      - url: https://developers.llamaindex.ai/python/cloud/llamaextract/getting_started/api/\n        type: Documentation\n    \
  \  - url: openapi/llamaindex-llamaextract-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      LlamaExtract is a prebuilt agentic data extraction API that transforms unstructured\n      document data into structured JSON representations. The REST API allows developers\n      to\n      create extraction agents, upload documents, and run extraction jobs programmatically.\n      Jobs are processed asynchronously, and developers can poll for job status and\n      retrieve\n      structured results. It is designed for use cases where documents need to be\n      converted\n      into well-defined schemas for downstream processing.\n  - aid: llamaindex:llamacloud-index-api\n    name: LlamaIndex LlamaCloud Index API\n    tags:\n      - Document Ingestion\n      - Indexing\n      - RAG\n      - Retrieval\n      - Vector Store\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloud.llamaindex.ai\n    humanURL: https://developers.llamaindex.ai/python/cloud/llamacloud/guides/api_sdk/\n\
  \    properties:\n      - url: https://developers.llamaindex.ai/python/cloud/llamacloud/guides/api_sdk/\n        type: Documentation\n      - url: openapi/llamaindex-llamacloud-index-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The LlamaCloud Index API provides a fully automated document ingestion pipeline\n      with\n      built-in retrieval capabilities. It allows developers to create and manage indexes,\n      upload documents for automatic parsing and embedding, and perform retrieval\n      queries\n      against indexed content. The API supports customizable pipeline configurations\n      and\n      integrates with various vector stores, making it suitable for building production\n      RAG applications without managing infrastructure.\n  - aid: llamaindex:python-framework\n    name: LlamaIndex Python Framework\n    tags:\n      - Agents\n      - Framework\n      - LLM\n      - Open Source\n      - Python\n      - RAG\n      - SDK\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.example.com\n    humanURL: https://developers.llamaindex.ai/python/framework/\n    properties:\n      - url: https://developers.llamaindex.ai/python/framework/\n        type: Documentation\n    description: >-\n      LlamaIndex is an open-source Python framework for building LLM-powered applications\n      including agents, RAG pipelines, and custom workflows. It provides data connectors\n      for ingesting data from various sources such as APIs, PDFs, databases, and more.\n      The framework offers high-level abstractions like query engines, chat engines,\n      and agent classes (FunctionAgent, ReActAgent, CodeActAgent), as well as lower-level\n      APIs for advanced customization.\n  - aid: llamaindex:typescript-framework\n    name: LlamaIndex TypeScript Framework\n    tags:\n      - Agents\n      - Framework\n      - JavaScript\n      - LLM\n      - Open Source\n      - RAG\n      - SDK\n      - TypeScript\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.example.com\n    humanURL: https://developers.llamaindex.ai/typescript/framework/\n    properties:\n      - url: https://developers.llamaindex.ai/typescript/framework/\n        type: Documentation\n    description: >-\n      LlamaIndex TypeScript is the JavaScript and TypeScript implementation of the\n      LlamaIndex\n      framework for building LLM-powered applications. It provides server-side TypeScript\n      support for building agents, RAG pipelines, and agentic workflows with the same\n      core\n      abstractions as the Python framework. The library supports integration with\n      LlamaCloud\n      services and offers convenient access to cloud APIs for document parsing, extraction,\n      and indexing from Node.js environments.\ncommon:\n  - type: JSON-LD\n    url: json-ld/llamaindex-context.jsonld\n  - type: JSONSchema\n    url: json-schema/llamaindex-pipeline-schema.json\n  - type: JSONSchema\n    url: json-schema/llamaindex-extraction-agent-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/llamaindex-parse-job-schema.json\ndescription: >-\n  LlamaCloud is a hosted service for document processing and search, powered by LlamaIndex.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/apis.yml
use_cases: []
---
