---
api_count: 8
api_specs:
- filename: automation-anywhere-control-room-openapi.yml
  format: yaml
  label: Automation Anywhere Control Room API
  slug: control-room-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-control-room-openapi.yml
- filename: automation-anywhere-bot-deploy-openapi.yml
  format: yaml
  label: Automation Anywhere Bot Deploy API
  slug: bot-deploy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-bot-deploy-openapi.yml
- filename: automation-anywhere-workload-management-openapi.yml
  format: yaml
  label: Automation Anywhere Workload Management API
  slug: workload-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-workload-management-openapi.yml
- filename: automation-anywhere-bot-insight-openapi.yml
  format: yaml
  label: Automation Anywhere Bot Insight API
  slug: bot-insight-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-bot-insight-openapi.yml
- filename: automation-anywhere-api-task-execution-openapi.yml
  format: yaml
  label: Automation Anywhere API Task Execution API
  slug: api-task-execution-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-api-task-execution-openapi.yml
- filename: automation-anywhere-credential-vault-openapi.yml
  format: yaml
  label: Automation Anywhere Credential Vault API
  slug: credential-vault-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-credential-vault-openapi.yml
- filename: automation-anywhere-repository-management-openapi.yml
  format: yaml
  label: Automation Anywhere Repository Management API
  slug: repository-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-repository-management-openapi.yml
apis:
- description: 'The Automation Anywhere Control Room API is a comprehensive set of RESTful APIs that enable programmatic management and administration of the Automation 360 RPA platform. It provides endpoints across '
  name: Automation Anywhere Control Room API
  slug: control-room-api
- description: The Automation Anywhere Bot Deploy API (v3/v4) enables external applications and workflows to programmatically trigger the deployment of bots to unattended Bot Runner devices. It supports deploying bo
  name: Automation Anywhere Bot Deploy API
  slug: bot-deploy-api
- description: The Automation Anywhere Workload Management API provides programmatic control over work item queues used to distribute high-volume automation workloads across multiple Bot Runner devices. Developers c
  name: Automation Anywhere Workload Management API
  slug: workload-management-api
- description: The Automation Anywhere Bot Insight API exposes real-time business process analytics and operational intelligence data collected during bot execution. It allows developers to retrieve KPIs, bot run hi
  name: Automation Anywhere Bot Insight API
  slug: bot-insight-api
- description: The Automation Anywhere API Task Execution API enables developers to invoke API Tasks — a specialized type of bot designed to be called synchronously from external applications like a REST service. It
  name: Automation Anywhere API Task Execution API
  slug: api-task-execution-api
- description: The Automation Anywhere Credential Vault API provides programmatic access to the Control Room's centralized secrets management system. It supports creating, reading, updating, and deleting credentials
  name: Automation Anywhere Credential Vault API
  slug: credential-vault-api
- description: The Automation Anywhere Package SDK is a Java-based development toolkit that enables developers to build custom action packages and triggers for the Automation 360 bot editor. Developers use the SDK i
  name: Automation Anywhere Package SDK
  slug: package-sdk
- description: The Automation Anywhere Repository Management API provides programmatic access to the Control Room's bot and file repository. It allows developers and administrators to list, search, upload, and manag
  name: Automation Anywhere Repository Management API
  slug: repository-management-api
common:
- title: ''
  type: Portal
  url: https://developer.automationanywhere.com
- title: ''
  type: Website
  url: https://www.automationanywhere.com
- title: ''
  type: Documentation
  url: https://docs.automationanywhere.com
- title: ''
  type: Authentication
  url: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/enterprise-cloud/topics/control-room/control-room-api/cloud-authentication.html
- title: ''
  type: TermsOfService
  url: https://www.automationanywhere.com/legal/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.automationanywhere.com/legal/privacy-policy
- title: ''
  type: Support
  url: https://support.automationanywhere.com
- title: ''
  type: Blog
  url: https://www.automationanywhere.com/blog
- title: ''
  type: JSON-LD
  url: json-ld/automation-anywhere-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/automation-anywhere-bot-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/automation-anywhere-deployment-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/automation-anywhere-work-item-schema.json
created: ''
description: Automation Anywhere is an enterprise robotic process automation (RPA) platform that enables organizations to automate business processes using software bots. Their developer platform, centered around the Automation 360 Control Room, provides a comprehensive suite of REST APIs for managing bot deployment, workload queues, credentials, repositories, and analytics, as well as an SDK for building custom action packages.
features:
- description: All Control Room APIs use JWT-based authentication. Tokens are obtained via the Authentication API and passed in the X-Authorization or Authorization Bearer header. OAuth 2.0 is supported from v.27 onwards.
  name: JWT Authentication
- description: APIs are versioned (v1, v2, v3, v4) with backwards compatibility maintained for at least two years. Deprecated endpoints are announced with at least one additional year of availability.
  name: Versioned API Endpoints
- description: Each Control Room instance exposes a Swagger UI at /swagger/ for interactive API exploration and testing with live credentials.
  name: Swagger UI Explorer
- description: API Tasks allow RPA bots to be exposed as synchronous REST endpoints, enabling external applications to call bots as microservices with input/output parameter exchange.
  name: API Task Execution
- description: Work item queues allow high-volume data to be fed into RPA pipelines from ERP, CRM, and BPM systems with status tracking and result retrieval.
  name: Workload Queuing
image: ''
integrations:
- description: Pre-built SAP integration package for Automation 360 enabling bots to interact with SAP GUI, SAP BAPIs, and S/4HANA REST APIs.
  name: SAP
- description: Automation Anywhere connector for Salesforce CRM enabling bots to create, update, and query Salesforce records via REST APIs.
  name: Salesforce
- description: Integration with ServiceNow for IT service automation including incident creation, ticket routing, and CMDB updates from RPA bots.
  name: ServiceNow
- description: Action packages for interacting with Microsoft 365 services including Outlook, SharePoint, Teams, and Excel via Microsoft Graph API.
  name: Microsoft Office 365
- description: Migration APIs for moving automations from other RPA platforms to Automation 360 with bot conversion and compatibility tooling.
  name: Blue Prism and UiPath
jsonld:
- class_count: 0
  name: Automation Anywhere Context
  property_count: 10
  slug: automation-anywhere-context
layout: provider
modified: '2026-04-19'
name: automation-anywhere
skills: []
slug: automation-anywhere
solutions: []
source_filename: apis.yml
source_yaml: "aid: automation-anywhere\nurl: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/apis.yml\napis:\n  - aid: automation-anywhere:control-room-api\n    name: Automation Anywhere Control Room API\n    tags:\n      - Automation\n      - Bot Management\n      - Enterprise\n      - REST\n      - RPA\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://automationanywhere-be-prod.automationanywhere.com\n    humanURL: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/enterprise-cloud/topics/control-room/control-room-api/cloud-control-room-apis.html\n    properties:\n      - url: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/enterprise-cloud/topics/control-room/control-room-api/cloud-control-room-apis.html\n        type: Documentation\n      - url: openapi/automation-anywhere-control-room-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Automation\
  \ Anywhere Control Room API is a comprehensive set of RESTful APIs\n      that enable programmatic management and administration of the Automation 360\n      RPA platform. It provides endpoints across multiple versioned groups covering\n      authentication, user management, credential vault, repository management, device\n      pools, licensing, policy management, and scheduled automations.\n\n  - aid: automation-anywhere:bot-deploy-api\n    name: Automation Anywhere Bot Deploy API\n    tags:\n      - Automation\n      - Bot Deployment\n      - Enterprise\n      - Orchestration\n      - RPA\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://automationanywhere-be-prod.automationanywhere.com\n    humanURL: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/deploy-api-supported-v4.html\n    properties:\n      - url: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/deploy-api-supported-v4.html\n      \
  \  type: Documentation\n      - url: openapi/automation-anywhere-bot-deploy-openapi.yml\n        type: OpenAPI\n      - url: json-schema/automation-anywhere-deployment-schema.json\n        type: JSONSchema\n    description: >-\n      The Automation Anywhere Bot Deploy API (v3/v4) enables external applications\n      and workflows to programmatically trigger the deployment of bots to unattended\n      Bot Runner devices. It supports deploying bots from the public workspace, specifying\n      target devices or device pools, and passing input variables at runtime. This\n      API is typically combined with the Authentication API to obtain a JWT token\n      before invoking deployment endpoints.\n\n  - aid: automation-anywhere:workload-management-api\n    name: Automation Anywhere Workload Management API\n    tags:\n      - Automation\n      - Queues\n      - RPA\n      - Work Items\n      - Workload Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://automationanywhere-be-prod.automationanywhere.com\n    humanURL: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/wlm-api-supported-v4.html\n    properties:\n      - url: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/wlm-api-supported-v4.html\n        type: Documentation\n      - url: openapi/automation-anywhere-workload-management-openapi.yml\n        type: OpenAPI\n      - url: json-schema/automation-anywhere-work-item-schema.json\n        type: JSONSchema\n    description: >-\n      The Automation Anywhere Workload Management API provides programmatic control\n      over work item queues used to distribute high-volume automation workloads across\n      multiple Bot Runner devices. Developers can create and manage work item models\n      and queues, add or update individual work items, and retrieve queue status and\n      processing results. This API enables enterprise systems such as ERP, CRM, and\n      BPM platforms to feed\
  \ structured data into RPA queues and track processing outcomes\n      in real time.\n\n  - aid: automation-anywhere:bot-insight-api\n    name: Automation Anywhere Bot Insight API\n    tags:\n      - Analytics\n      - Bot Monitoring\n      - Business Intelligence\n      - Reporting\n      - RPA\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://automationanywhere-be-prod.automationanywhere.com\n    humanURL: https://docs.automationanywhere.com/bundle/enterprise-v11.3/page/enterprise/topics/bot-insight/user/bot-insight-apis.html\n    properties:\n      - url: https://docs.automationanywhere.com/bundle/enterprise-v11.3/page/enterprise/topics/bot-insight/user/bot-insight-apis.html\n        type: Documentation\n      - url: openapi/automation-anywhere-bot-insight-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Automation Anywhere Bot Insight API exposes real-time business process analytics\n      and operational\
  \ intelligence data collected during bot execution. It allows\n      developers to retrieve KPIs, bot run histories, performance rankings, and failure\n      analytics from the Control Room programmatically. Results are paginated in sets\n      of 1000 records and can be filtered by date ranges in ISO 8601 format.\n\n  - aid: automation-anywhere:api-task-execution-api\n    name: Automation Anywhere API Task Execution API\n    tags:\n      - API Task\n      - Automation\n      - Bot Execution\n      - Integration\n      - RPA\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://automationanywhere-be-prod.automationanywhere.com\n    humanURL: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/api-task-real-time-endpoint.html\n    properties:\n      - url: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/api-task-real-time-endpoint.html\n        type: Documentation\n      - url: openapi/automation-anywhere-api-task-execution-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The Automation Anywhere API Task Execution API enables developers to invoke\n      API Tasks — a specialized type of bot designed to be called synchronously from\n      external applications like a REST service. It generates execution URLs and tokens\n      that allow applications to trigger a bot task, pass input parameters, and receive\n      output values in a single request-response cycle.\n\n  - aid: automation-anywhere:credential-vault-api\n    name: Automation Anywhere Credential Vault API\n    tags:\n      - Credentials\n      - Enterprise\n      - RPA\n      - Secrets Management\n      - Security\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://automationanywhere-be-prod.automationanywhere.com\n    humanURL: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/cv-api-supported.html\n    properties:\n      - url: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/cv-api-supported.html\n\
  \        type: Documentation\n      - url: openapi/automation-anywhere-credential-vault-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Automation Anywhere Credential Vault API provides programmatic access to\n      the Control Room's centralized secrets management system. It supports creating,\n      reading, updating, and deleting credentials, credential attributes, Lockers,\n      and Locker Keys used by bots during execution. Credentials stored in the Vault\n      are encrypted and access-controlled through role-based permissions, ensuring\n      bots can retrieve sensitive values such as passwords and API keys without exposing\n      them in automation scripts.\n\n  - aid: automation-anywhere:package-sdk\n    name: Automation Anywhere Package SDK\n    tags:\n      - Bot Development\n      - Custom Packages\n      - Extensions\n      - Java\n      - SDK\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n\
  \    humanURL: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/enterprise-cloud/topics/developer/cloud-create-package-overview.html\n    properties:\n      - url: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/enterprise-cloud/topics/developer/cloud-create-package-overview.html\n        type: Documentation\n    description: >-\n      The Automation Anywhere Package SDK is a Java-based development toolkit that\n      enables developers to build custom action packages and triggers for the Automation\n      360 bot editor. Developers use the SDK in a Java IDE to implement custom actions,\n      compile the code into a JAR file, and upload the resulting package to the Control\n      Room for use in bot workflows.\n\n  - aid: automation-anywhere:repository-management-api\n    name: Automation Anywhere Repository Management API\n    tags:\n      - Bot Lifecycle\n      - DevOps\n      - File Management\n      - Repository\n      - RPA\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://automationanywhere-be-prod.automationanywhere.com\n    humanURL: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/repository-management-api.html\n    properties:\n      - url: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/repository-management-api.html\n        type: Documentation\n      - url: openapi/automation-anywhere-repository-management-openapi.yml\n        type: OpenAPI\n      - url: json-schema/automation-anywhere-bot-schema.json\n        type: JSONSchema\n    description: >-\n      The Automation Anywhere Repository Management API provides programmatic access\n      to the Control Room's bot and file repository. It allows developers and administrators\n      to list, search, upload, and manage bots, folders, and dependent files stored\n      in both the public and private workspaces. This API supports bot lifecycle management\n      use cases including automated promotion of bots between environments, bulk file\n      operations,\
  \ and integration with source control systems.\n\ncommon:\n  - type: Portal\n    url: https://developer.automationanywhere.com\n  - type: Website\n    url: https://www.automationanywhere.com\n  - type: Documentation\n    url: https://docs.automationanywhere.com\n  - type: Authentication\n    url: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/enterprise-cloud/topics/control-room/control-room-api/cloud-authentication.html\n  - type: TermsOfService\n    url: https://www.automationanywhere.com/legal/terms\n  - type: PrivacyPolicy\n    url: https://www.automationanywhere.com/legal/privacy-policy\n  - type: Support\n    url: https://support.automationanywhere.com\n  - type: Blog\n    url: https://www.automationanywhere.com/blog\n  - type: JSON-LD\n    url: json-ld/automation-anywhere-context.jsonld\n  - type: JSONSchema\n    url: json-schema/automation-anywhere-bot-schema.json\n  - type: JSONSchema\n    url: json-schema/automation-anywhere-deployment-schema.json\n  - type:\
  \ JSONSchema\n    url: json-schema/automation-anywhere-work-item-schema.json\n  - type: Features\n    data:\n      - name: JWT Authentication\n        description: >-\n          All Control Room APIs use JWT-based authentication. Tokens are obtained\n          via the Authentication API and passed in the X-Authorization or\n          Authorization Bearer header. OAuth 2.0 is supported from v.27 onwards.\n      - name: Versioned API Endpoints\n        description: >-\n          APIs are versioned (v1, v2, v3, v4) with backwards compatibility\n          maintained for at least two years. Deprecated endpoints are announced\n          with at least one additional year of availability.\n      - name: Swagger UI Explorer\n        description: >-\n          Each Control Room instance exposes a Swagger UI at /swagger/ for\n          interactive API exploration and testing with live credentials.\n      - name: API Task Execution\n        description: >-\n          API Tasks allow RPA bots to be\
  \ exposed as synchronous REST endpoints,\n          enabling external applications to call bots as microservices with\n          input/output parameter exchange.\n      - name: Workload Queuing\n        description: >-\n          Work item queues allow high-volume data to be fed into RPA pipelines\n          from ERP, CRM, and BPM systems with status tracking and result retrieval.\n  - type: UseCases\n    data:\n      - name: DevOps Bot Pipeline\n        description: >-\n          Automate bot deployment across dev, test, and production environments\n          using the Bot Deploy and Repository Management APIs in CI/CD pipelines.\n      - name: Enterprise System Integration\n        description: >-\n          Connect ERP, CRM, and BPM systems to RPA workload queues to distribute\n          and process high-volume transactional data with Automation Anywhere bots.\n      - name: Bot Performance Monitoring\n        description: >-\n          Feed Bot Insight API data into Tableau, Power\
  \ BI, or Splunk for\n          real-time RPA operational dashboards and business KPI tracking.\n      - name: Credential Governance\n        description: >-\n          Programmatically provision and rotate bot credentials in the Credential\n          Vault from enterprise secrets management systems like CyberArk or HashiCorp Vault.\n      - name: Custom Action Packages\n        description: >-\n          Build proprietary Java action packages using the Package SDK to extend\n          Automation 360 with custom connectors for legacy or specialized systems.\n  - type: Integrations\n    data:\n      - name: SAP\n        description: >-\n          Pre-built SAP integration package for Automation 360 enabling bots to\n          interact with SAP GUI, SAP BAPIs, and S/4HANA REST APIs.\n      - name: Salesforce\n        description: >-\n          Automation Anywhere connector for Salesforce CRM enabling bots to\n          create, update, and query Salesforce records via REST APIs.\n      - name:\
  \ ServiceNow\n        description: >-\n          Integration with ServiceNow for IT service automation including\n          incident creation, ticket routing, and CMDB updates from RPA bots.\n      - name: Microsoft Office 365\n        description: >-\n          Action packages for interacting with Microsoft 365 services including\n          Outlook, SharePoint, Teams, and Excel via Microsoft Graph API.\n      - name: Blue Prism and UiPath\n        description: >-\n          Migration APIs for moving automations from other RPA platforms to\n          Automation 360 with bot conversion and compatibility tooling.\n\nmodified: '2026-04-19'\ndescription: >-\n  Automation Anywhere is an enterprise robotic process automation (RPA) platform\n  that enables organizations to automate business processes using software bots.\n  Their developer platform, centered around the Automation 360 Control Room, provides\n  a comprehensive suite of REST APIs for managing bot deployment, workload queues,\n \
  \ credentials, repositories, and analytics, as well as an SDK for building custom\n  action packages.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/apis.yml
use_cases:
- description: Automate bot deployment across dev, test, and production environments using the Bot Deploy and Repository Management APIs in CI/CD pipelines.
  name: DevOps Bot Pipeline
- description: Connect ERP, CRM, and BPM systems to RPA workload queues to distribute and process high-volume transactional data with Automation Anywhere bots.
  name: Enterprise System Integration
- description: Feed Bot Insight API data into Tableau, Power BI, or Splunk for real-time RPA operational dashboards and business KPI tracking.
  name: Bot Performance Monitoring
- description: Programmatically provision and rotate bot credentials in the Credential Vault from enterprise secrets management systems like CyberArk or HashiCorp Vault.
  name: Credential Governance
- description: Build proprietary Java action packages using the Package SDK to extend Automation 360 with custom connectors for legacy or specialized systems.
  name: Custom Action Packages
---
