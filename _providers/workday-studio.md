---
api_count: 5
api_specs:
- filename: api-specifications
  format: yaml
  label: Workday Studio Integration API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/api-specifications
apis:
- description: API for building and deploying custom integrations using Workday Studio, an Eclipse-based IDE that provides a graphical development environment with drag-and-drop reusable components for creating soph
  name: Workday Studio Integration API
  slug: ''
- description: SOAP and REST web services for integrating with Workday applications, providing programmatic access to business management services with WSDL and XML Schema definitions across 55 service areas includi
  name: Workday Web Services API
  slug: ''
- description: RESTful API providing modern JSON-based access to Workday data and services. Uses OAuth 2.0 authentication and standard HTTP methods for operations across HCM, financial management, recruiting, payrol
  name: Workday REST API
  slug: ''
- description: API for creating and executing custom reports built in Workday Studio. Exposes custom reports as RESTful web services through Report-as-a-Service (RaaS), enabling programmatic access to report data wi
  name: Workday Custom Reports API
  slug: ''
- description: Low-code integration and automation platform for building event-driven and batch integrations using a visual drag-and-drop builder. Enables developers to create workflows that connect Workday with ext
  name: Workday Orchestrate API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://community.workday.com/
- title: ''
  type: Login
  url: https://www.myworkday.com/
- title: ''
  type: Support
  url: https://www.workday.com/en-us/customer-experience/support.html
- title: ''
  type: Terms of Service
  url: https://www.workday.com/en-us/legal.html
- title: ''
  type: Privacy Policy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: Status
  url: https://status.workday.com/
- title: ''
  type: Blog
  url: https://blog.workday.com/
- title: ''
  type: Contact
  url: https://www.workday.com/en-us/company/about-workday/contact-us.html
- title: ''
  type: Getting Started
  url: https://community.workday.com/node/97816
- title: ''
  type: Documentation
  url: https://doc.workday.com/en-us/guides.html
- title: ''
  type: Console
  url: https://developer.workday.com/about
- title: ''
  type: Website
  url: https://www.workday.com/
- title: ''
  type: Sign Up
  url: https://community.workday.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/Workday
- title: ''
  type: Developer Blog
  url: https://workday.github.io/
- title: ''
  type: Marketplace
  url: https://marketplace.workday.com/en-US/home
- title: ''
  type: Training
  url: https://www.workday.com/en-us/services/training-certifications.html
- title: ''
  type: Authentication
  url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication
- title: ''
  type: Reference
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html
- title: ''
  type: Studio Download
  url: https://community.workday.com/studio-download
created: '2024-01-01'
description: Workday Studio is an integrated development environment (IDE) for building custom integrations and applications on the Workday platform. It provides tools for creating web services, custom reports, and integration solutions.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-16'
name: Workday Studio
skills: []
slug: workday-studio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: workday-studio\nname: Workday Studio\ndescription: Workday Studio is an integrated development environment (IDE) for building custom integrations and applications on the Workday platform. It provides tools for creating web services, custom reports, and integration solutions.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday-studio/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\ntags:\n  - Cloud\n  - Development\n  - Enterprise\n  - Finance\n  - HR\n  - IDE\n  - Integration\napis:\n  - name: Workday Studio Integration API\n    description: API for building and deploying custom integrations using Workday Studio, an Eclipse-based IDE that provides a graphical development environment with drag-and-drop reusable components for creating sophisticated integrations with flow control, data transformation, error handling, and\
  \ scripting.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanUrl: https://doc.workday.com/\n    baseUrl: https://{tenant}.workday.com/ccx/service\n    tags:\n      - Custom\n      - Development\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://doc.workday.com/reader/wsiU0cnNjCc_k7shLNxLEA/HdIduH8HQGat1qdv1nXNVQ\n      - type: OpenAPI\n        url: https://community.workday.com/api-specifications\n      - type: Swagger\n        url: https://community.workday.com/api-specifications\n      - type: Authentication\n        url: https://doc.workday.com/reader/wsiU0cnNjCc_k7shLNxLEA/rvVKnUi_v3MwKZ1VqF_1Jw\n      - type: Getting Started\n        url: https://doc.workday.com/reader/wsiU0cnNjCc_k7shLNxLEA/z~y4T3OBwNz42E1hT8azSA\n      - type: SDK\n        url: https://doc.workday.com/reader/wsiU0cnNjCc_k7shLNxLEA/HdIduH8HQGat1qdv1nXNVQ\n      - type: Reference\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Integrations/v17/Integrations.html\n\
  \  - name: Workday Web Services API\n    description: SOAP and REST web services for integrating with Workday applications, providing programmatic access to business management services with WSDL and XML Schema definitions across 55 service areas including Human Resources, Payroll, Benefits, and Financial Management.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanUrl: https://doc.workday.com/\n    baseUrl: https://{tenant}.workday.com/ccx/service/{tenant}\n    tags:\n      - Enterprise\n      - REST\n      - SOAP\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://doc.workday.com/reader/J1YvL9yFQMumSgoRA4j4bA/root\n      - type: WSDL\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/\n      - type: API Reference\n        url: https://community.workday.com/api\n      - type: Rate Limits\n        url: https://doc.workday.com/reader/J1YvL9yFQMumSgoRA4j4bA/L~jJl~pFV91hFVm2h3UFWQ\n\
  \      - type: Reference\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n  - name: Workday REST API\n    description: RESTful API providing modern JSON-based access to Workday data and services. Uses OAuth 2.0 authentication and standard HTTP methods for operations across HCM, financial management, recruiting, payroll, and other Workday domains.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanUrl: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseUrl: https://{tenant}.workday.com/ccx/api\n    tags:\n      - Data Access\n      - JSON\n      - OAuth\n      - REST\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: Reference\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: Authentication\n\
  \        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication\n  - name: Workday Custom Reports API\n    description: API for creating and executing custom reports built in Workday Studio. Exposes custom reports as RESTful web services through Report-as-a-Service (RaaS), enabling programmatic access to report data with support for query parameters and multiple output formats.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanUrl: https://doc.workday.com/\n    baseUrl: https://{tenant}.workday.com/ccx/service/customreport2/{tenant}\n    tags:\n      - Analytics\n      - Custom\n      - Report as a Service\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://doc.workday.com/reader/J1YvL9yFQMumSgoRA4j4bA/ziYjYJxh2YKGvz8I5V46bQ\n      - type: Tutorial\n        url: https://doc.workday.com/reader/wsiU0cnNjCc_k7shLNxLEA/kPBEj3_Lz04YDSUvAEKl4w\n  - name: Workday Orchestrate\
  \ API\n    description: Low-code integration and automation platform for building event-driven and batch integrations using a visual drag-and-drop builder. Enables developers to create workflows that connect Workday with external systems, automate business processes, and handle real-time data synchronization.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanUrl: https://www.workday.com/en-us/products/platform-product-extensions/integrations.html\n    baseUrl: https://{tenant}.workday.com/ccx/api\n    tags:\n      - Automation\n      - Event Driven\n      - Low Code\n      - Orchestration\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://www.workday.com/en-us/products/platform-product-extensions/integrations.html\ncommon:\n  - type: Portal\n    url: https://community.workday.com/\n  - type: Login\n    url: https://www.myworkday.com/\n  - type: Support\n    url: https://www.workday.com/en-us/customer-experience/support.html\n\
  \  - type: Terms of Service\n    url: https://www.workday.com/en-us/legal.html\n  - type: Privacy Policy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: Status\n    url: https://status.workday.com/\n  - type: Blog\n    url: https://blog.workday.com/\n  - type: Contact\n    url: https://www.workday.com/en-us/company/about-workday/contact-us.html\n  - type: Getting Started\n    url: https://community.workday.com/node/97816\n  - type: Documentation\n    url: https://doc.workday.com/en-us/guides.html\n  - type: Console\n    url: https://developer.workday.com/about\n  - type: Website\n    url: https://www.workday.com/\n  - type: Sign Up\n    url: https://community.workday.com/\n  - type: GitHub Organization\n    url: https://github.com/Workday\n  - type: Developer Blog\n    url: https://workday.github.io/\n  - type: Marketplace\n    url: https://marketplace.workday.com/en-US/home\n  - type: Training\n    url: https://www.workday.com/en-us/services/training-certifications.html\n\
  \  - type: Authentication\n    url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication\n  - type: Reference\n    url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n  - type: Studio Download\n    url: https://community.workday.com/studio-download\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday-studio/refs/heads/main/apis.yml
tags:
- Cloud
- Development
- Enterprise
- Finance
- HR
- IDE
- Integration
url: https://raw.githubusercontent.com/api-evangelist/workday-studio/refs/heads/main/apis.yml
use_cases: []
---
