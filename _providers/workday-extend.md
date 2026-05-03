---
api_count: 6
api_specs:
- filename: openapi.json
  format: json
  label: Workday Extend REST API
  slug: ''
  spec_type: OpenAPI
  url: https://api.workday.com/extend/openapi.json
apis:
- description: RESTful APIs for building and managing Workday Extend applications, including orchestrations, integrations, and custom objects.
  name: Workday Extend REST API
  slug: ''
- description: APIs for creating and managing orchestrations that automate business processes and integrate with external systems. Developers visually build orchestrations using an intuitive drag-and-drop Orchestrat
  name: Workday Orchestration API
  slug: ''
- description: APIs for defining and managing custom objects that extend Workday's data model to meet specific business needs. As new objects and business processes are built, a public REST API is automatically crea
  name: Workday Custom Objects API
  slug: ''
- description: Graph API for querying and traversing Workday data using a graph-based approach. Provides a flexible query interface for accessing interconnected Workday business objects and their relationships acros
  name: Workday Graph API
  slug: ''
- description: API for accessing orchestration execution data and monitoring information. Provides insights into orchestration performance, run history, and operational metrics for troubleshooting and optimization.
  name: Workday Orchestrate Insights API
  slug: ''
- description: AI-powered APIs within Workday Illuminate that provide skills and sentiment analysis, document intelligence, natural language WQL queries, and machine learning forecasting capabilities. Enables develo
  name: Workday Illuminate AI API
  slug: ''
common:
- title: ''
  type: Getting Started
  url: https://doc.workday.com/extend/getting-started/
- title: ''
  type: Portal
  url: https://developer.workday.com/
- title: ''
  type: Documentation
  url: https://developer.workday.com/documentation
- title: ''
  type: Reference
  url: https://developer.workday.com/documentation/GUID-04def314-83a7-4edf-b84c-c0a5f005b23c-enHYPHENus
- title: ''
  type: API Reference
  url: https://doc.workday.com/extend/reference/
- title: ''
  type: SDK
  url: https://doc.workday.com/extend/sdk/
- title: ''
  type: Code Samples
  url: https://github.com/Workday/extend-js-example
- title: ''
  type: Community
  url: https://forum.developer.workday.com
- title: ''
  type: Support
  url: https://support.developer.workday.com/s/
- title: ''
  type: Change Log
  url: https://doc.workday.com/extend/release-notes/
- title: ''
  type: Status
  url: https://status.workday.com/
- title: ''
  type: Terms of Service
  url: https://www.workday.com/en-us/legal.html
- title: ''
  type: Privacy Policy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: Authentication
  url: https://doc.workday.com/extend/authentication/
- title: ''
  type: Rate Limits
  url: https://doc.workday.com/extend/rate-limits/
- title: ''
  type: Blog
  url: https://blog.workday.com/en-us/introducing-workday-build-developer-platform-build-future-work-ai.html
- title: ''
  type: Website
  url: https://www.workday.com/en-us/products/platform-product-extensions/app-development.html
- title: ''
  type: Login
  url: https://developer.workday.com/login
- title: ''
  type: Console
  url: https://developer.workday.com/about
- title: ''
  type: GitHub Organization
  url: https://github.com/Workday
- title: ''
  type: Marketplace
  url: https://marketplace.workday.com/en-US/home
- title: ''
  type: Developer Tools
  url: https://api.developer.workday.com/devtools
- title: ''
  type: Partners
  url: https://www.workday.com/en-us/company/partners/software-partners.html
created: 2025-03-14 00:00:00+00:00
description: Workday Extend is a platform that enables developers to build custom applications that integrate seamlessly with Workday. It provides APIs, development tools, and a runtime environment for creating tailored solutions that extend Workday's core functionality.
features: []
image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg
integrations: []
layout: provider
modified: 2026-03-04 00:00:00+00:00
name: Workday Extend
skills: []
slug: workday-extend
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Workday Extend\ndescription: Workday Extend is a platform that enables developers to build custom applications that integrate seamlessly with Workday. It provides APIs, development tools, and a runtime environment for creating tailored solutions that extend Workday's core functionality.\nimage: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\nurl: https://www.workday.com/en-us/products/platform-product-extensions/app-development.html\ntype: Index\ncreated: 2025-03-14 00:00:00+00:00\nmodified: 2026-03-04 00:00:00+00:00\nspecificationVersion: '0.18'\napis:\n  - name: Workday Extend REST API\n    description: RESTful APIs for building and managing Workday Extend applications, including orchestrations, integrations, and custom objects.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanURL: https://doc.workday.com/extend/\n    baseURL: https://api.workday.com/extend/v1\n    tags:\n      - Custom Applications\n\
  \      - Extensions\n      - Integration\n      - Orchestrations\n    properties:\n      - type: Documentation\n        url: https://doc.workday.com/extend/\n      - type: OpenAPI\n        url: https://api.workday.com/extend/openapi.json\n      - type: Authentication\n        url: https://doc.workday.com/extend/reference/authentication.html\n      - type: Reference\n        url: https://developer.workday.com/rest-api-explorer\n  - name: Workday Orchestration API\n    description: APIs for creating and managing orchestrations that automate business processes and integrate with external systems. Developers visually build orchestrations using an intuitive drag-and-drop Orchestration Builder to define flows, map data, and perform transformations.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanURL: https://doc.workday.com/extend/orchestrations/\n    baseURL: https://api.workday.com/orchestrate/v1\n    tags:\n      - Automation\n      - Business\
  \ Processes\n      - Orchestrations\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://doc.workday.com/extend/orchestrations/\n      - type: Tutorials\n        url: https://doc.workday.com/extend/tutorials/orchestrations/\n      - type: Reference\n        url: https://developer.workday.com/documentation/GUID-1293c9bb-ea02-48cd-a523-254b5060b3a6-enHYPHENus\n  - name: Workday Custom Objects API\n    description: APIs for defining and managing custom objects that extend Workday's data model to meet specific business needs. As new objects and business processes are built, a public REST API is automatically created for other developers and processes to use.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanURL: https://doc.workday.com/extend/custom-objects/\n    baseURL: https://api.workday.com/customObjects/v1\n    tags:\n      - Custom Fields\n      - Custom Objects\n      - Data Model\n      - Schema\n  \
  \  properties:\n      - type: Documentation\n        url: https://doc.workday.com/extend/custom-objects/\n      - type: Examples\n        url: https://doc.workday.com/extend/examples/custom-objects/\n  - name: Workday Graph API\n    description: >-\n      Graph API for querying and traversing Workday data using a graph-based\n      approach. Provides a flexible query interface for accessing interconnected\n      Workday business objects and their relationships across the platform.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanURL: https://developer.workday.com/graph-api-explorer\n    baseURL: https://api.workday.com/\n    tags:\n      - Business Objects\n      - Data Query\n      - Graph API\n      - Relationships\n    properties:\n      - type: Documentation\n        url: https://developer.workday.com/graph-api-explorer\n      - type: Reference\n        url: https://developer.workday.com/graph-api-explorer\n  - name: Workday Orchestrate\
  \ Insights API\n    description: >-\n      API for accessing orchestration execution data and monitoring information.\n      Provides insights into orchestration performance, run history, and\n      operational metrics for troubleshooting and optimization.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanURL: https://api.workday.com/orchestrate/insights\n    baseURL: https://api.workday.com/orchestrate/insights\n    tags:\n      - Analytics\n      - Insights\n      - Monitoring\n      - Orchestrations\n    properties:\n      - type: Documentation\n        url: https://developer.workday.com/documentation/GUID-1293c9bb-ea02-48cd-a523-254b5060b3a6-enHYPHENus\n  - name: Workday Illuminate AI API\n    description: >-\n      AI-powered APIs within Workday Illuminate that provide skills and sentiment\n      analysis, document intelligence, natural language WQL queries, and machine\n      learning forecasting capabilities. Enables developers to\
  \ build intelligent\n      Extend applications leveraging Workday AI services.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanURL: https://www.workday.com/en-us/products/platform-product-extensions/app-development.html\n    baseURL: https://api.workday.com/\n    tags:\n      - Artificial Intelligence\n      - Document Intelligence\n      - Machine Learning\n      - Natural Language Processing\n    properties:\n      - type: Documentation\n        url: https://developer.workday.com/documentation\ncommon:\n  - type: Getting Started\n    url: https://doc.workday.com/extend/getting-started/\n  - type: Portal\n    url: https://developer.workday.com/\n  - type: Documentation\n    url: https://developer.workday.com/documentation\n  - type: Reference\n    url: https://developer.workday.com/documentation/GUID-04def314-83a7-4edf-b84c-c0a5f005b23c-enHYPHENus\n  - type: API Reference\n    url: https://doc.workday.com/extend/reference/\n  - type: SDK\n\
  \    url: https://doc.workday.com/extend/sdk/\n  - type: Code Samples\n    url: https://github.com/Workday/extend-js-example\n  - type: Community\n    url: https://forum.developer.workday.com\n  - type: Support\n    url: https://support.developer.workday.com/s/\n  - type: Change Log\n    url: https://doc.workday.com/extend/release-notes/\n  - type: Status\n    url: https://status.workday.com/\n  - type: Terms of Service\n    url: https://www.workday.com/en-us/legal.html\n  - type: Privacy Policy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: Authentication\n    url: https://doc.workday.com/extend/authentication/\n  - type: Rate Limits\n    url: https://doc.workday.com/extend/rate-limits/\n  - type: Blog\n    url: https://blog.workday.com/en-us/introducing-workday-build-developer-platform-build-future-work-ai.html\n  - type: Website\n    url: https://www.workday.com/en-us/products/platform-product-extensions/app-development.html\n  - type: Login\n    url: https://developer.workday.com/login\n\
  \  - type: Console\n    url: https://developer.workday.com/about\n  - type: GitHub Organization\n    url: https://github.com/Workday\n  - type: Marketplace\n    url: https://marketplace.workday.com/en-US/home\n  - type: Developer Tools\n    url: https://api.developer.workday.com/devtools\n  - type: Partners\n    url: https://www.workday.com/en-us/company/partners/software-partners.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Automation\n  - Custom Applications\n  - Enterprise\n  - Extensions\n  - HCM\n  - Human Capital Management\n  - Integration\n  - Orchestration\n  - PaaS\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday-extend/refs/heads/main/apis.yml
tags:
- Automation
- Custom Applications
- Enterprise
- Extensions
- HCM
- Human Capital Management
- Integration
- Orchestration
- PaaS
url: https://www.workday.com/en-us/products/platform-product-extensions/app-development.html
use_cases: []
---
