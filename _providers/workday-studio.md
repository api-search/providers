---
api_count: 5
api_specs:
- filename: workday-studio-integration-openapi.yml
  format: yaml
  label: Workday Studio Integration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-studio/refs/heads/main/openapi/workday-studio-integration-openapi.yml
- filename: workday-studio-web-services-openapi.yml
  format: yaml
  label: Workday Web Services API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-studio/refs/heads/main/openapi/workday-studio-web-services-openapi.yml
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
  type: Website
  url: https://www.workday.com/
- title: ''
  type: Portal
  url: https://community.workday.com/
- title: ''
  type: Console
  url: https://developer.workday.com/about
- title: ''
  type: Login
  url: https://www.myworkday.com/
- title: ''
  type: SignUp
  url: https://community.workday.com/
- title: ''
  type: Documentation
  url: https://doc.workday.com/en-us/guides.html
- title: ''
  type: GettingStarted
  url: https://community.workday.com/node/97816
- title: ''
  type: Authentication
  url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication
- title: ''
  type: APIReference
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html
- title: ''
  type: Support
  url: https://www.workday.com/en-us/customer-experience/support.html
- title: ''
  type: TermsOfService
  url: https://www.workday.com/en-us/legal.html
- title: ''
  type: PrivacyPolicy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: StatusPage
  url: https://status.workday.com/
- title: ''
  type: Blog
  url: https://blog.workday.com/
- title: ''
  type: DeveloperBlog
  url: https://workday.github.io/
- title: ''
  type: Contact
  url: https://www.workday.com/en-us/company/about-workday/contact-us.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/Workday
- title: ''
  type: Marketplace
  url: https://marketplace.workday.com/en-US/home
- title: ''
  type: Training
  url: https://www.workday.com/en-us/services/training-certifications.html
- title: ''
  type: StudioDownload
  url: https://community.workday.com/studio-download
- title: ''
  type: SpectralRules
  url: rules/workday-studio-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/workday-studio-vocabulary.yaml
created: '2024-01-01'
description: Workday Studio is an integrated development environment (IDE) for building custom integrations and applications on the Workday platform. It provides tools for creating web services, custom reports, and integration solutions.
features:
- description: Workday Studio is an Eclipse-based development environment with a graphical, drag-and-drop interface for designing custom integrations.
  name: Eclipse-based IDE
- description: Provides a library of reusable integration components for transports, transformations, splitters, and routing logic that accelerate integration development.
  name: Reusable Components
- description: Includes constructs for branching, looping, retries, and structured error handling to build resilient integrations.
  name: Flow Control and Error Handling
- description: Supports XSLT, XPath, and scripting for mapping and transforming data between Workday and external systems.
  name: Data Transformation
- description: Exposes custom Workday reports as RESTful web services through Report-as-a-Service (RaaS) for downstream consumption.
  name: Custom Report-as-a-Service
- description: Provides SOAP and REST access to 55+ Workday service areas including HCM, Financial Management, Payroll, and Benefits.
  name: Workday Web Services
- description: Offers OAuth 2.0-secured JSON REST endpoints for accessing Workday data and triggering business actions.
  name: Modern REST API
- description: Workday Orchestrate enables building event-driven and batch integrations through a visual workflow builder without writing code.
  name: Orchestrate Low-Code Integrations
- description: Integrations are deployed against tenant-specific endpoints with environment isolation between sandbox and production tenants.
  name: Tenant-Based Deployment
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Workday Studio runs as an Eclipse-based plug-in providing the development surface for building integrations.
  name: Eclipse IDE
- description: Common integration target for syncing customer, opportunity, and worker data between Workday and Salesforce.
  name: Salesforce
- description: Connect Workday to ServiceNow for IT service management and HR case management workflows.
  name: ServiceNow
- description: Integrate Workday HCM with ADP and other third-party payroll providers for payroll data exchange.
  name: ADP
- description: Sync worker data with Microsoft 365 and Azure Active Directory for identity provisioning and collaboration tooling.
  name: Microsoft 365 and Azure AD
- description: Bridge Workday financial and HR data with SAP ERP systems for organizations running mixed environments.
  name: SAP
- description: Use Workday integrations to push and pull data from cloud storage, messaging, and data warehouses.
  name: AWS, Azure, and Google Cloud
- description: Stream Workday data into Snowflake, BigQuery, and other warehouses for analytics and reporting.
  name: Snowflake and Data Warehouses
layout: provider
modified: '2026-05-03'
name: Workday Studio
rules:
- name: Workday Studio API Rules
  rule_count: 64
  severity_counts:
    error: 25
    hint: 0
    info: 9
    warn: 30
  slug: workday-studio-spectral-rules
skills: []
slug: workday-studio
solutions:
- description: Cloud-based human capital management covering core HR, talent, learning, recruiting, and workforce planning.
  name: Workday HCM
- description: Cloud financial management for accounting, revenue, expenses, projects, and analytics.
  name: Workday Financial Management
- description: Native payroll for the United States, Canada, United Kingdom, and France integrated with Workday HCM.
  name: Workday Payroll
- description: Enterprise planning, budgeting, and forecasting platform that integrates with Workday Financials and HCM.
  name: Workday Adaptive Planning
- description: Platform for building custom apps that extend Workday functionality using the same data model and security.
  name: Workday Extend
- description: Low-code integration and automation platform for building workflows across Workday and external systems.
  name: Workday Orchestrate
- description: Curated catalog of partner-built integrations and apps that extend the Workday platform.
  name: Workday Marketplace
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: workday-studio\nname: Workday Studio\ndescription: Workday Studio is an integrated development environment (IDE) for building custom integrations and applications on the Workday platform. It provides tools for creating web services, custom reports, and integration solutions.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday-studio/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Cloud\n  - Development\n  - Enterprise\n  - Finance\n  - HR\n  - IDE\n  - Integration\napis:\n  - name: Workday Studio Integration API\n    description: API for building and deploying custom integrations using Workday Studio, an Eclipse-based IDE that provides a graphical development environment with drag-and-drop reusable components for creating sophisticated integrations with flow control, data transformation, error handling, and\
  \ scripting.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanUrl: https://doc.workday.com/\n    baseUrl: https://{tenant}.workday.com/ccx/service\n    tags:\n      - Custom\n      - Development\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://doc.workday.com/reader/wsiU0cnNjCc_k7shLNxLEA/HdIduH8HQGat1qdv1nXNVQ\n      - type: OpenAPI\n        url: openapi/workday-studio-integration-openapi.yml\n      - type: APIReference\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Integrations/v17/Integrations.html\n      - type: Authentication\n        url: https://doc.workday.com/reader/wsiU0cnNjCc_k7shLNxLEA/rvVKnUi_v3MwKZ1VqF_1Jw\n      - type: GettingStarted\n        url: https://doc.workday.com/reader/wsiU0cnNjCc_k7shLNxLEA/z~y4T3OBwNz42E1hT8azSA\n      - type: SDK\n        url: https://doc.workday.com/reader/wsiU0cnNjCc_k7shLNxLEA/HdIduH8HQGat1qdv1nXNVQ\n  - name:\
  \ Workday Web Services API\n    description: SOAP and REST web services for integrating with Workday applications, providing programmatic access to business management services with WSDL and XML Schema definitions across 55 service areas including Human Resources, Payroll, Benefits, and Financial Management.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanUrl: https://doc.workday.com/\n    baseUrl: https://{tenant}.workday.com/ccx/service/{tenant}\n    tags:\n      - Enterprise\n      - REST\n      - SOAP\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://doc.workday.com/reader/J1YvL9yFQMumSgoRA4j4bA/root\n      - type: OpenAPI\n        url: openapi/workday-studio-web-services-openapi.yml\n      - type: WSDL\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/\n      - type: APIReference\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n\
  \      - type: RateLimits\n        url: https://doc.workday.com/reader/J1YvL9yFQMumSgoRA4j4bA/L~jJl~pFV91hFVm2h3UFWQ\n  - name: Workday REST API\n    description: RESTful API providing modern JSON-based access to Workday data and services. Uses OAuth 2.0 authentication and standard HTTP methods for operations across HCM, financial management, recruiting, payroll, and other Workday domains.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanUrl: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseUrl: https://{tenant}.workday.com/ccx/api\n    tags:\n      - Data Access\n      - JSON\n      - OAuth\n      - REST\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: APIReference\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: Authentication\n\
  \        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication\n  - name: Workday Custom Reports API\n    description: API for creating and executing custom reports built in Workday Studio. Exposes custom reports as RESTful web services through Report-as-a-Service (RaaS), enabling programmatic access to report data with support for query parameters and multiple output formats.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanUrl: https://doc.workday.com/\n    baseUrl: https://{tenant}.workday.com/ccx/service/customreport2/{tenant}\n    tags:\n      - Analytics\n      - Custom\n      - Report as a Service\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://doc.workday.com/reader/J1YvL9yFQMumSgoRA4j4bA/ziYjYJxh2YKGvz8I5V46bQ\n      - type: Tutorial\n        url: https://doc.workday.com/reader/wsiU0cnNjCc_k7shLNxLEA/kPBEj3_Lz04YDSUvAEKl4w\n  - name: Workday Orchestrate\
  \ API\n    description: Low-code integration and automation platform for building event-driven and batch integrations using a visual drag-and-drop builder. Enables developers to create workflows that connect Workday with external systems, automate business processes, and handle real-time data synchronization.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanUrl: https://www.workday.com/en-us/products/platform-product-extensions/integrations.html\n    baseUrl: https://{tenant}.workday.com/ccx/api\n    tags:\n      - Automation\n      - Event Driven\n      - Low Code\n      - Orchestration\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://www.workday.com/en-us/products/platform-product-extensions/integrations.html\ncommon:\n  - type: Website\n    url: https://www.workday.com/\n  - type: Portal\n    url: https://community.workday.com/\n  - type: Console\n    url: https://developer.workday.com/about\n  -\
  \ type: Login\n    url: https://www.myworkday.com/\n  - type: SignUp\n    url: https://community.workday.com/\n  - type: Documentation\n    url: https://doc.workday.com/en-us/guides.html\n  - type: GettingStarted\n    url: https://community.workday.com/node/97816\n  - type: Authentication\n    url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication\n  - type: APIReference\n    url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n  - type: Support\n    url: https://www.workday.com/en-us/customer-experience/support.html\n  - type: TermsOfService\n    url: https://www.workday.com/en-us/legal.html\n  - type: PrivacyPolicy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: StatusPage\n    url: https://status.workday.com/\n  - type: Blog\n    url: https://blog.workday.com/\n  - type: DeveloperBlog\n    url: https://workday.github.io/\n  - type: Contact\n    url: https://www.workday.com/en-us/company/about-workday/contact-us.html\n\
  \  - type: GitHubOrganization\n    url: https://github.com/Workday\n  - type: Marketplace\n    url: https://marketplace.workday.com/en-US/home\n  - type: Training\n    url: https://www.workday.com/en-us/services/training-certifications.html\n  - type: StudioDownload\n    url: https://community.workday.com/studio-download\n  - type: SpectralRules\n    url: rules/workday-studio-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/workday-studio-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Eclipse-based IDE\n        description: Workday Studio is an Eclipse-based development environment with a graphical, drag-and-drop interface for designing custom integrations.\n      - name: Reusable Components\n        description: Provides a library of reusable integration components for transports, transformations, splitters, and routing logic that accelerate integration development.\n      - name: Flow Control and Error Handling\n        description: Includes constructs for\
  \ branching, looping, retries, and structured error handling to build resilient integrations.\n      - name: Data Transformation\n        description: Supports XSLT, XPath, and scripting for mapping and transforming data between Workday and external systems.\n      - name: Custom Report-as-a-Service\n        description: Exposes custom Workday reports as RESTful web services through Report-as-a-Service (RaaS) for downstream consumption.\n      - name: Workday Web Services\n        description: Provides SOAP and REST access to 55+ Workday service areas including HCM, Financial Management, Payroll, and Benefits.\n      - name: Modern REST API\n        description: Offers OAuth 2.0-secured JSON REST endpoints for accessing Workday data and triggering business actions.\n      - name: Orchestrate Low-Code Integrations\n        description: Workday Orchestrate enables building event-driven and batch integrations through a visual workflow builder without writing code.\n      - name: Tenant-Based\
  \ Deployment\n        description: Integrations are deployed against tenant-specific endpoints with environment isolation between sandbox and production tenants.\n  - type: UseCases\n    data:\n      - name: Custom Integrations\n        description: Build bespoke integrations between Workday and external HR, payroll, benefits, and financial systems.\n      - name: Payroll and Benefits Connectivity\n        description: Connect Workday HCM and Payroll to third-party payroll providers, banks, and benefits carriers for data exchange.\n      - name: Employee Data Synchronization\n        description: Keep worker records, organizational data, and position information in sync between Workday and downstream systems.\n      - name: Custom Reporting\n        description: Generate custom reports in Workday Studio and expose them through Report-as-a-Service for use in BI tools and dashboards.\n      - name: Business Process Automation\n        description: Automate cross-system HR and finance business\
  \ processes using Workday Orchestrate event-driven workflows.\n      - name: ERP and CRM Integration\n        description: Integrate Workday Financial Management with downstream ERPs, CRMs, and procurement systems for invoicing and revenue management.\n      - name: Identity and Access Provisioning\n        description: Synchronize worker lifecycle events from Workday into identity providers and downstream applications for user provisioning.\n  - type: Integrations\n    data:\n      - name: Eclipse IDE\n        description: Workday Studio runs as an Eclipse-based plug-in providing the development surface for building integrations.\n      - name: Salesforce\n        description: Common integration target for syncing customer, opportunity, and worker data between Workday and Salesforce.\n      - name: ServiceNow\n        description: Connect Workday to ServiceNow for IT service management and HR case management workflows.\n      - name: ADP\n        description: Integrate Workday HCM with\
  \ ADP and other third-party payroll providers for payroll data exchange.\n      - name: Microsoft 365 and Azure AD\n        description: Sync worker data with Microsoft 365 and Azure Active Directory for identity provisioning and collaboration tooling.\n      - name: SAP\n        description: Bridge Workday financial and HR data with SAP ERP systems for organizations running mixed environments.\n      - name: AWS, Azure, and Google Cloud\n        description: Use Workday integrations to push and pull data from cloud storage, messaging, and data warehouses.\n      - name: Snowflake and Data Warehouses\n        description: Stream Workday data into Snowflake, BigQuery, and other warehouses for analytics and reporting.\n  - type: Solutions\n    data:\n      - name: Workday HCM\n        description: Cloud-based human capital management covering core HR, talent, learning, recruiting, and workforce planning.\n      - name: Workday Financial Management\n        description: Cloud financial management\
  \ for accounting, revenue, expenses, projects, and analytics.\n      - name: Workday Payroll\n        description: Native payroll for the United States, Canada, United Kingdom, and France integrated with Workday HCM.\n      - name: Workday Adaptive Planning\n        description: Enterprise planning, budgeting, and forecasting platform that integrates with Workday Financials and HCM.\n      - name: Workday Extend\n        description: Platform for building custom apps that extend Workday functionality using the same data model and security.\n      - name: Workday Orchestrate\n        description: Low-code integration and automation platform for building workflows across Workday and external systems.\n      - name: Workday Marketplace\n        description: Curated catalog of partner-built integrations and apps that extend the Workday platform.\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
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
use_cases:
- description: Build bespoke integrations between Workday and external HR, payroll, benefits, and financial systems.
  name: Custom Integrations
- description: Connect Workday HCM and Payroll to third-party payroll providers, banks, and benefits carriers for data exchange.
  name: Payroll and Benefits Connectivity
- description: Keep worker records, organizational data, and position information in sync between Workday and downstream systems.
  name: Employee Data Synchronization
- description: Generate custom reports in Workday Studio and expose them through Report-as-a-Service for use in BI tools and dashboards.
  name: Custom Reporting
- description: Automate cross-system HR and finance business processes using Workday Orchestrate event-driven workflows.
  name: Business Process Automation
- description: Integrate Workday Financial Management with downstream ERPs, CRMs, and procurement systems for invoicing and revenue management.
  name: ERP and CRM Integration
- description: Synchronize worker lifecycle events from Workday into identity providers and downstream applications for user provisioning.
  name: Identity and Access Provisioning
---
