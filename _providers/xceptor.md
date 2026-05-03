---
api_count: 5
api_specs:
- filename: openapi.json
  format: json
  label: Xceptor REST API
  slug: ''
  spec_type: OpenAPI
  url: https://api.xceptor.com/v1/openapi.json
- filename: workflows
  format: yaml
  label: Xceptor Workflow API
  slug: ''
  spec_type: Postman
  url: https://www.postman.com/xceptor/workspace/workflows
apis:
- description: RESTful API for managing data processing workflows, document ingestion, and data extraction in Xceptor. Provides programmatic access to the Xceptor data automation platform for integrating with existi
  name: Xceptor REST API
  slug: ''
- description: API for creating, managing, and executing data processing workflows within the Xceptor platform. Enables programmatic orchestration of automated data processing pipelines including event-driven trigge
  name: Xceptor Workflow API
  slug: ''
- description: API for uploading and processing documents through Xceptor's data extraction engine. Supports intelligent document processing using NLP, OCR, and generative AI to transform unstructured documents incl
  name: Xceptor Document Upload API
  slug: ''
- description: API for exporting processed data in various formats. Supports output to multiple downstream systems and data formats including XML, JSON, CSV, and Excel for integration with trading platforms, data wa
  name: Xceptor Data Export API
  slug: ''
- description: API and connector framework for integrating Xceptor with external systems and data sources. Provides pre-built connectors for cloud storage (AWS S3, Azure Blob, Google Cloud Storage), messaging system
  name: Xceptor Connector API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://portal.xceptor.com
- title: ''
  type: Getting Started
  url: https://docs.xceptor.com/getting-started
- title: ''
  type: Authentication
  url: https://docs.xceptor.com/authentication
- title: ''
  type: Rate Limits
  url: https://docs.xceptor.com/rate-limits
- title: ''
  type: Status Page
  url: https://status.xceptor.com
- title: ''
  type: Terms of Service
  url: https://www.xceptor.com/legal-tcs
- title: ''
  type: Privacy Policy
  url: https://www.xceptor.com/privacy-policy
- title: ''
  type: Contact
  url: https://www.xceptor.com/contact-us
- title: ''
  type: Website
  url: https://www.xceptor.com
- title: ''
  type: Platform
  url: https://www.xceptor.com/platform
- title: ''
  type: Blog
  url: https://www.xceptor.com/blogs
- title: ''
  type: Newsroom
  url: https://www.xceptor.com/company/newsroom
- title: ''
  type: Support
  url: https://xceptor.zendesk.com/hc/en-gb
- title: ''
  type: Training
  url: https://www.xceptor.com/support/training
- title: ''
  type: Community
  url: https://connect.xceptor.com
- title: ''
  type: Academy
  url: https://academy.xceptor.com/learn
- title: ''
  type: Resources
  url: https://www.xceptor.com/resources
- title: ''
  type: Glossary
  url: https://www.xceptor.com/resources/glossary
- title: ''
  type: Webinars
  url: https://www.xceptor.com/resources/webinars
- title: ''
  type: Videos
  url: https://www.xceptor.com/resources/videos
- title: ''
  type: About
  url: https://www.xceptor.com/about
- title: ''
  type: Partners
  url: https://www.xceptor.com/find-a-partner
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/xceptor
- title: ''
  type: X
  url: https://x.com/xceptor
- title: ''
  type: Connector Marketplace
  url: https://app.xceptor.cloud/xsllibrary/mx/home/
- title: ''
  type: Azure Marketplace
  url: https://azuremarketplace.microsoft.com/en-us/marketplace/apps/xceptor.xceptor
created: '2024-01-01'
description: Xceptor is a data automation platform that helps organizations extract, transform, and integrate data from various sources, particularly focused on document processing and financial data automation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-16'
name: Xceptor
skills: []
slug: xceptor
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: xceptor\nname: Xceptor\ndescription: >-\n  Xceptor is a data automation platform that helps organizations extract, transform,\n  and integrate data from various sources, particularly focused on document processing\n  and financial data automation.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/xceptor/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\ntags:\n  - API Integration\n  - Data Automation\n  - Data Extraction\n  - Document Processing\n  - ETL\n  - Financial Data\n  - Financial Services\n  - Intelligent Document Processing\n  - Reconciliations\n  - Trade Operations\napis:\n  - name: Xceptor REST API\n    description: >-\n      RESTful API for managing data processing workflows, document ingestion,\n      and data extraction in Xceptor. Provides programmatic access to the\n      Xceptor data automation platform for\
  \ integrating with existing systems\n      and orchestrating automated data processing pipelines.\n    image: https://www.xceptor.com/images/xceptor-logo.png\n    baseURL: https://api.xceptor.com/v1\n    humanURL: https://www.xceptor.com/api\n    documentation: https://docs.xceptor.com/api/rest\n    properties:\n      - type: Documentation\n        url: https://docs.xceptor.com/api/rest\n      - type: OpenAPI\n        url: https://api.xceptor.com/v1/openapi.json\n      - type: Authentication\n        url: https://docs.xceptor.com/api/authentication\n    contact:\n      - type: Support\n        url: https://www.xceptor.com/support\n      - type: Email\n        url: mailto:api-support@xceptor.com\n    tags:\n      - Data Processing\n      - Documents\n      - REST\n      - Workflows\n  - name: Xceptor Workflow API\n    description: >-\n      API for creating, managing, and executing data processing workflows\n      within the Xceptor platform. Enables programmatic orchestration of\n    \
  \  automated data processing pipelines including event-driven triggers\n      and business rules execution.\n    image: https://www.xceptor.com/images/xceptor-logo.png\n    baseURL: https://api.xceptor.com/v1/workflows\n    humanURL: https://www.xceptor.com/workflows\n    documentation: https://docs.xceptor.com/api/workflows\n    properties:\n      - type: Documentation\n        url: https://docs.xceptor.com/api/workflows\n      - type: Postman Collection\n        url: https://www.postman.com/xceptor/workspace/workflows\n    tags:\n      - Automation\n      - Orchestration\n      - Workflows\n  - name: Xceptor Document Upload API\n    description: >-\n      API for uploading and processing documents through Xceptor's data\n      extraction engine. Supports intelligent document processing using NLP,\n      OCR, and generative AI to transform unstructured documents including\n      PDFs, emails, and spreadsheets into structured, trusted data.\n    image: https://www.xceptor.com/images/xceptor-logo.png\n\
  \    baseURL: https://api.xceptor.com/v1/documents\n    humanURL: https://www.xceptor.com/documents\n    documentation: https://docs.xceptor.com/api/documents\n    properties:\n      - type: Documentation\n        url: https://docs.xceptor.com/api/documents\n      - type: Examples\n        url: https://docs.xceptor.com/api/examples/documents\n    tags:\n      - Documents\n      - Extraction\n      - OCR\n      - Upload\n  - name: Xceptor Data Export API\n    description: >-\n      API for exporting processed data in various formats. Supports output to\n      multiple downstream systems and data formats including XML, JSON, CSV,\n      and Excel for integration with trading platforms, data warehouses, and\n      regulatory reporting systems.\n    image: https://www.xceptor.com/images/xceptor-logo.png\n    baseURL: https://api.xceptor.com/v1/export\n    humanURL: https://www.xceptor.com/export\n    documentation: https://docs.xceptor.com/api/export\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.xceptor.com/api/export\n      - type: Formats\n        url: https://docs.xceptor.com/api/export-formats\n    tags:\n      - Data\n      - Export\n      - Integration\n  - name: Xceptor Connector API\n    description: >-\n      API and connector framework for integrating Xceptor with external systems\n      and data sources. Provides pre-built connectors for cloud storage (AWS S3,\n      Azure Blob, Google Cloud Storage), messaging systems (Kafka, RabbitMQ),\n      databases (SQL Server, Snowflake), and financial industry protocols\n      (SWIFT 15022 and 20022). Enables bidirectional data exchange with the\n      Xceptor platform.\n    image: https://www.xceptor.com/images/xceptor-logo.png\n    baseURL: https://api.xceptor.com/v1\n    humanURL: https://www.xceptor.com/platform/connectors\n    properties:\n      - type: Documentation\n        url: https://www.xceptor.com/platform/connectors\n    tags:\n      - Cloud\n      - Connectors\n      - Financial Data\n\
  \      - Integration\n      - SWIFT\ncommon:\n  - type: Portal\n    url: https://portal.xceptor.com\n  - type: Getting Started\n    url: https://docs.xceptor.com/getting-started\n  - type: Authentication\n    url: https://docs.xceptor.com/authentication\n  - type: Rate Limits\n    url: https://docs.xceptor.com/rate-limits\n  - type: Status Page\n    url: https://status.xceptor.com\n  - type: Terms of Service\n    url: https://www.xceptor.com/legal-tcs\n  - type: Privacy Policy\n    url: https://www.xceptor.com/privacy-policy\n  - type: Contact\n    url: https://www.xceptor.com/contact-us\n  - type: Website\n    url: https://www.xceptor.com\n  - type: Platform\n    url: https://www.xceptor.com/platform\n  - type: Solutions\n    url: https://www.xceptor.com/solutions\n  - type: Blog\n    url: https://www.xceptor.com/blogs\n  - type: Newsroom\n    url: https://www.xceptor.com/company/newsroom\n  - type: Support\n    url: https://xceptor.zendesk.com/hc/en-gb\n  - type: Training\n    url: https://www.xceptor.com/support/training\n\
  \  - type: Community\n    url: https://connect.xceptor.com\n  - type: Academy\n    url: https://academy.xceptor.com/learn\n  - type: Resources\n    url: https://www.xceptor.com/resources\n  - type: Glossary\n    url: https://www.xceptor.com/resources/glossary\n  - type: Webinars\n    url: https://www.xceptor.com/resources/webinars\n  - type: Videos\n    url: https://www.xceptor.com/resources/videos\n  - type: About\n    url: https://www.xceptor.com/about\n  - type: Partners\n    url: https://www.xceptor.com/find-a-partner\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/xceptor\n  - type: X\n    url: https://x.com/xceptor\n  - type: Connector Marketplace\n    url: https://app.xceptor.cloud/xsllibrary/mx/home/\n  - type: Azure Marketplace\n    url: https://azuremarketplace.microsoft.com/en-us/marketplace/apps/xceptor.xceptor\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/xceptor/refs/heads/main/apis.yml
tags:
- API Integration
- Data Automation
- Data Extraction
- Document Processing
- ETL
- Financial Data
- Financial Services
- Intelligent Document Processing
- Reconciliations
- Trade Operations
url: https://raw.githubusercontent.com/api-evangelist/xceptor/refs/heads/main/apis.yml
use_cases: []
---
