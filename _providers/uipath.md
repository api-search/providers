---
api_count: 6
api_specs:
- filename: uipath-orchestrator-openapi.yml
  format: yaml
  label: UiPath Orchestrator API
  slug: uipath-orchestrator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-orchestrator-openapi.yml
- filename: uipath-automation-hub-openapi.yml
  format: yaml
  label: UiPath Automation Hub API
  slug: uipath-automation-hub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-automation-hub-openapi.yml
- filename: uipath-document-understanding-openapi.yml
  format: yaml
  label: UiPath Document Understanding API
  slug: uipath-document-understanding-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-document-understanding-openapi.yml
- filename: uipath-data-service-openapi.yml
  format: yaml
  label: UiPath Data Service API
  slug: uipath-data-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-data-service-openapi.yml
- filename: uipath-platform-management-openapi.yml
  format: yaml
  label: UiPath Platform Management API
  slug: uipath-platform-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-platform-management-openapi.yml
- filename: uipath-test-manager-openapi.yml
  format: yaml
  label: UiPath Test Manager API
  slug: uipath-test-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-test-manager-openapi.yml
apis:
- description: The UiPath Orchestrator API provides programmatic access to the core automation management platform, enabling developers to manage robots, jobs, processes, queues, assets, schedules, and more. Built o
  name: UiPath Orchestrator API
  slug: uipath-orchestrator-api
- description: 'The UiPath Automation Hub API provides access to the automation pipeline and idea management platform, allowing developers to programmatically create, retrieve, and manage automation ideas, projects, '
  name: UiPath Automation Hub API
  slug: uipath-automation-hub-api
- description: The UiPath Document Understanding API enables intelligent document processing using machine learning and AI models. Developers can submit documents for digitization, classification, and data extractio
  name: UiPath Document Understanding API
  slug: uipath-document-understanding-api
- description: The UiPath Data Service API provides programmatic access to structured data storage within the UiPath Platform. Developers can create, read, update, and delete records in custom data entities, enablin
  name: UiPath Data Service API
  slug: uipath-data-service-api
- description: 'The UiPath Platform Management API provides administrative access to organization and tenant management capabilities, including user management, license management, and account configuration. Used by '
  name: UiPath Platform Management API
  slug: uipath-platform-management-api
- description: The UiPath Test Manager API enables programmatic interaction with the automated testing platform, allowing CI/CD pipelines and external tools to create test sets, execute tests, and retrieve test resu
  name: UiPath Test Manager API
  slug: uipath-test-manager-api
asyncapis:
- description: The UiPath Orchestrator webhook system delivers real-time event notifications to registered HTTP endpoints when automation events occur within the platform. Webhooks cover events for jobs, robots, que
  name: UiPath Orchestrator Webhook Events
  slug: uipath-orchestrator-webhooks-asyncapi
capabilities:
- description: Unified workflow for automation governance combining Automation Hub for pipeline management, Platform Management for user and license administration, and Test Manager for quality assurance. Used by Ce
  name: UiPath Automation Governance
  slug: automation-governance
- description: Unified workflow for automation operators managing robots, jobs, queues, and assets in the UiPath Orchestrator. Used by RPA developers and operations teams to deploy, monitor, and manage running autom
  name: UiPath Automation Operations
  slug: automation-operations
- description: End-to-end workflow for intelligent document processing combining Document Understanding for OCR and data extraction with Orchestrator for automation orchestration. Used by document processing teams a
  name: UiPath Intelligent Document Processing
  slug: intelligent-document-processing
common:
- title: ''
  type: Website
  url: https://www.uipath.com
- title: ''
  type: Documentation
  url: https://docs.uipath.com
- title: ''
  type: Portal
  url: https://cloud.uipath.com
- title: ''
  type: Blog
  url: https://www.uipath.com/blog
- title: ''
  type: Pricing
  url: https://www.uipath.com/pricing
- title: ''
  type: TermsOfService
  url: https://www.uipath.com/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.uipath.com/legal/privacy-policy
- title: ''
  type: Support
  url: https://support.uipath.com
- title: ''
  type: StatusPage
  url: https://status.uipath.com
- title: ''
  type: Academy
  url: https://academy.uipath.com
- title: ''
  type: Forum
  url: https://forum.uipath.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/UiPath
- title: Python SDK
  type: SDK
  url: https://pypi.org/project/uipath/
- title: Python SDK GitHub
  type: SDK
  url: https://github.com/UiPath/uipath-python
- title: LangChain Python SDK
  type: SDK
  url: https://github.com/UiPath/uipath-langchain-python
- title: TypeScript SDK
  type: SDK
  url: https://github.com/UiPath/uipath-typescript
- title: Python Integrations SDK
  type: SDK
  url: https://github.com/UiPath/uipath-integrations-python
- title: MCP Server
  type: Tools
  url: https://github.com/UiPath/uipath-mcp-python
- title: UiPath CLI
  type: CLI
  url: https://github.com/UiPath/uipathcli
- title: ''
  type: CLI
  url: https://docs.uipath.com/automation-cloud/docs/uipath-cli
- title: ''
  type: Signup
  url: https://cloud.uipath.com/portal_/cloudrpa
- title: ''
  type: GettingStarted
  url: https://docs.uipath.com/automation-cloud/docs/introduction
- title: ''
  type: Authentication
  url: https://docs.uipath.com/automation-cloud/automation-cloud/latest/api-guide/accessing-uipath-resources-using-external-apps
- title: ''
  type: SpectralRules
  url: rules/uipath-spectral-rules.yml
- title: Automation Operations
  type: NaftikoCapability
  url: capabilities/automation-operations.yaml
- title: Intelligent Document Processing
  type: NaftikoCapability
  url: capabilities/intelligent-document-processing.yaml
- title: Automation Governance
  type: NaftikoCapability
  url: capabilities/automation-governance.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/uipath-vocabulary.yaml
created: '2025-01-01'
description: UiPath is an enterprise automation platform offering robotic process automation (RPA), AI-powered automation, and agentic automation capabilities. The platform includes Orchestrator for managing robots and automation jobs, Studio for developing automation workflows, Document Understanding for intelligent document processing, Data Service for structured data storage, Automation Hub for pipeline management and governance, Test Manager for automated testing, and Platform Management for organization and tenant administration. UiPath provides Python SDKs, REST APIs, and a rich integration ecosystem supporting enterprise automation at scale.
features:
- description: Automate repetitive tasks across any application using software robots with no-code, low-code, and coded automation options.
  name: Robotic Process Automation
- description: Integrate AI capabilities including document understanding, computer vision, and natural language processing into automation workflows.
  name: AI-Powered Automation
- description: Build and deploy intelligent agents using Python, LangGraph, or LlamaIndex frameworks on the UiPath Agent Cloud.
  name: Agentic Automation
- description: Extract structured data from unstructured documents using ML models for OCR, classification, and field extraction.
  name: Document Understanding
- description: Centrally manage and monitor automation robots, jobs, queues, schedules, and assets across the enterprise.
  name: Orchestration
- description: Discover and analyze business processes to identify automation opportunities and measure impact.
  name: Process Mining
- description: Create, manage, and execute automated tests for RPA and application testing with enterprise CI/CD integration.
  name: Test Automation
- description: Connect to 1,000+ applications and services through pre-built connectors for enterprise integration.
  name: Integration Service
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Automate CRM operations, data sync, and customer workflows with native Salesforce integration.
  name: Salesforce
- description: Connect with SAP ERP and S/4HANA for automated finance, HR, and supply chain processes.
  name: SAP
- description: Automate Office applications, SharePoint, Teams, and Azure services through Microsoft 365 integration.
  name: Microsoft 365
- description: Integrate with ServiceNow for ITSM automation, ticket management, and service catalog workflows.
  name: ServiceNow
- description: Connect with Workday HCM for HR automation, payroll processing, and workforce management.
  name: Workday
- description: Build and deploy AI agents using LangChain and LangGraph frameworks on the UiPath platform.
  name: LangChain and LangGraph
jsonld:
- class_count: 18
  name: Uipath Automation Hub Context
  property_count: 24
  slug: uipath-automation-hub-context
- class_count: 0
  name: Uipath Context
  property_count: 15
  slug: uipath-context
- class_count: 7
  name: Uipath Data Service Context
  property_count: 19
  slug: uipath-data-service-context
- class_count: 19
  name: Uipath Document Understanding Context
  property_count: 35
  slug: uipath-document-understanding-context
- class_count: 2
  name: Uipath General Context
  property_count: 3
  slug: uipath-general-context
- class_count: 27
  name: Uipath Orchestrator Context
  property_count: 77
  slug: uipath-orchestrator-context
- class_count: 14
  name: Uipath Platform Management Context
  property_count: 29
  slug: uipath-platform-management-context
- class_count: 16
  name: Uipath Test Manager Context
  property_count: 26
  slug: uipath-test-manager-context
layout: provider
modified: '2026-05-03'
name: UiPath
rules:
- name: UiPath API Rules
  rule_count: 40
  severity_counts:
    error: 15
    hint: 0
    info: 5
    warn: 20
  slug: uipath-spectral-rules
skills: []
slug: uipath
solutions:
- description: Entry-level cloud automation for individuals and small teams with basic RPA and limited scale.
  name: Automation Cloud Basic
- description: Professional automation platform for businesses with unlimited users, robots, and enterprise data extraction.
  name: Automation Cloud Standard
- description: Strategic enterprise automation with full infrastructure control, BYOK, multi-region deployment, and advanced AI capabilities.
  name: Automation Cloud Enterprise
- description: FedRAMP Moderate authorized automation solution for U.S. government and public sector organizations.
  name: Automation Cloud Public Sector
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: uipath\nname: UiPath\ndescription: >-\n  UiPath is an enterprise automation platform offering robotic process automation\n  (RPA), AI-powered automation, and agentic automation capabilities. The platform\n  includes Orchestrator for managing robots and automation jobs, Studio for\n  developing automation workflows, Document Understanding for intelligent document\n  processing, Data Service for structured data storage, Automation Hub for\n  pipeline management and governance, Test Manager for automated testing, and\n  Platform Management for organization and tenant administration. UiPath provides\n  Python SDKs, REST APIs, and a rich integration ecosystem supporting enterprise\n  automation at scale.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - Robotic Process Automation\n  - RPA\n  - Artificial Intelligence\n  - Document Processing\n  - Enterprise Automation\n  - Orchestration\n  - Testing\n\
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: uipath:uipath-orchestrator-api\n    name: UiPath Orchestrator API\n    description: >-\n      The UiPath Orchestrator API provides programmatic access to the core\n      automation management platform, enabling developers to manage robots, jobs,\n      processes, queues, assets, schedules, and more. Built on the OData protocol,\n      the API supports RESTful operations with filtering, sorting, and pagination\n      across all resources. Authentication uses OAuth 2.0 tokens from the UiPath\n      Identity Server.\n    humanURL: https://docs.uipath.com/orchestrator/automation-cloud/latest/api-guide/read-me\n    baseURL: https://cloud.uipath.com/{organizationName}/{tenantName}/orchestrator_\n    tags:\n      - Orchestrator\n      - Robots\n      - Jobs\n      - Queues\n      - Automation\n    properties:\n    \
  \  - type: Documentation\n        url: https://docs.uipath.com/orchestrator/automation-cloud/latest/api-guide/read-me\n      - type: OpenAPI\n        url: openapi/uipath-orchestrator-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/uipath-orchestrator-webhooks-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/uipath-orchestrator-schema.json\n      - type: JSONSchema\n        url: json-schema/orchestrator-job-schema.json\n      - type: JSONSchema\n        url: json-schema/orchestrator-robot-schema.json\n      - type: JSONSchema\n        url: json-schema/orchestrator-queue-definition-schema.json\n      - type: JSONSchema\n        url: json-schema/orchestrator-queue-item-schema.json\n      - type: JSONSchema\n        url: json-schema/orchestrator-asset-schema.json\n      - type: JSONStructure\n        url: json-structure/orchestrator-job-structure.json\n      - type: JSON-LD\n        url: json-ld/uipath-orchestrator-context.jsonld\n  - aid: uipath:uipath-automation-hub-api\n\
  \    name: UiPath Automation Hub API\n    description: >-\n      The UiPath Automation Hub API provides access to the automation pipeline\n      and idea management platform, allowing developers to programmatically\n      create, retrieve, and manage automation ideas, projects, and pipeline data.\n      Designed for organizations building Center of Excellence workflows and\n      integrating Automation Hub with external tools.\n    humanURL: https://docs.uipath.com/automation-hub/automation-cloud/latest/api-guide/introduction-to-automation-hub-api-1\n    baseURL: https://cloud.uipath.com/{orgName}/{tenantName}/automationhub_/api/v1\n    tags:\n      - Automation Hub\n      - Pipeline Management\n      - Center of Excellence\n      - Ideas\n    properties:\n      - type: Documentation\n        url: https://docs.uipath.com/automation-hub/automation-cloud/latest/api-guide/introduction-to-automation-hub-api-1\n      - type: OpenAPI\n        url: openapi/uipath-automation-hub-openapi.yml\n\
  \      - type: JSONSchema\n        url: json-schema/automation-hub-automation-schema.json\n      - type: JSONStructure\n        url: json-structure/automation-hub-automation-structure.json\n      - type: JSON-LD\n        url: json-ld/uipath-automation-hub-context.jsonld\n  - aid: uipath:uipath-document-understanding-api\n    name: UiPath Document Understanding API\n    description: >-\n      The UiPath Document Understanding API enables intelligent document\n      processing using machine learning and AI models. Developers can submit\n      documents for digitization, classification, and data extraction, as well\n      as manage custom ML models and training datasets.\n    humanURL: https://docs.uipath.com/document-understanding/automation-cloud/latest/api-guide/api-overview\n    baseURL: https://cloud.uipath.com/{organizationName}/{tenantName}/du_\n    tags:\n      - Document Understanding\n      - Machine Learning\n      - OCR\n      - Data Extraction\n      - Intelligent Document Processing\n\
  \    properties:\n      - type: Documentation\n        url: https://docs.uipath.com/document-understanding/automation-cloud/latest/api-guide/api-overview\n      - type: OpenAPI\n        url: openapi/uipath-document-understanding-openapi.yml\n      - type: JSONSchema\n        url: json-schema/uipath-document-understanding-schema.json\n      - type: JSONStructure\n        url: json-structure/document-understanding-digitization-result-structure.json\n      - type: JSON-LD\n        url: json-ld/uipath-document-understanding-context.jsonld\n  - aid: uipath:uipath-data-service-api\n    name: UiPath Data Service API\n    description: >-\n      The UiPath Data Service API provides programmatic access to structured\n      data storage within the UiPath Platform. Developers can create, read,\n      update, and delete records in custom data entities, enabling automation\n      workflows to read from and write to persistent cloud-based data stores.\n    humanURL: https://docs.uipath.com/data-service/automation-cloud/latest/api-guide/about-the-data-service-api\n\
  \    baseURL: https://cloud.uipath.com/{organizationName}/{tenantName}/dataservice_\n    tags:\n      - Data Service\n      - Data Storage\n      - Records\n      - Entities\n    properties:\n      - type: Documentation\n        url: https://docs.uipath.com/data-service/automation-cloud/latest/api-guide/about-the-data-service-api\n      - type: OpenAPI\n        url: openapi/uipath-data-service-openapi.yml\n      - type: JSONSchema\n        url: json-schema/data-service-entity-record-schema.json\n      - type: JSONStructure\n        url: json-structure/data-service-entity-record-structure.json\n      - type: JSON-LD\n        url: json-ld/uipath-data-service-context.jsonld\n  - aid: uipath:uipath-platform-management-api\n    name: UiPath Platform Management API\n    description: >-\n      The UiPath Platform Management API provides administrative access to\n      organization and tenant management capabilities, including user management,\n      license management, and account configuration.\
  \ Used by platform\n      administrators to manage UiPath Automation Cloud organizations programmatically.\n    humanURL: https://docs.uipath.com/automation-cloud/automation-cloud/latest/api-guide/accessing-uipath-resources-using-external-apps\n    baseURL: https://cloud.uipath.com\n    tags:\n      - Platform Management\n      - Administration\n      - Organizations\n      - Tenants\n      - Licensing\n    properties:\n      - type: Documentation\n        url: https://docs.uipath.com/automation-cloud/automation-cloud/latest/api-guide/accessing-uipath-resources-using-external-apps\n      - type: OpenAPI\n        url: openapi/uipath-platform-management-openapi.yml\n      - type: JSONStructure\n        url: json-structure/platform-management-user-structure.json\n      - type: JSON-LD\n        url: json-ld/uipath-platform-management-context.jsonld\n  - aid: uipath:uipath-test-manager-api\n    name: UiPath Test Manager API\n    description: >-\n      The UiPath Test Manager API enables programmatic\
  \ interaction with the\n      automated testing platform, allowing CI/CD pipelines and external tools\n      to create test sets, execute tests, and retrieve test results. Supports\n      enterprise-grade test management and reporting workflows.\n    humanURL: https://docs.uipath.com/test-manager/automation-cloud/latest/api-guide/test-manager-api\n    baseURL: https://cloud.uipath.com/{organizationName}/{tenantName}/testmanager_\n    tags:\n      - Testing\n      - Quality Assurance\n      - CI/CD\n      - Test Automation\n    properties:\n      - type: Documentation\n        url: https://docs.uipath.com/test-manager/automation-cloud/latest/api-guide/test-manager-api\n      - type: OpenAPI\n        url: openapi/uipath-test-manager-openapi.yml\n      - type: JSONSchema\n        url: json-schema/test-manager-test-case-schema.json\n      - type: JSONStructure\n        url: json-structure/test-manager-test-case-structure.json\n      - type: JSON-LD\n        url: json-ld/uipath-test-manager-context.jsonld\n\
  common:\n  - type: Website\n    url: https://www.uipath.com\n  - type: Documentation\n    url: https://docs.uipath.com\n  - type: Portal\n    url: https://cloud.uipath.com\n  - type: Blog\n    url: https://www.uipath.com/blog\n  - type: Pricing\n    url: https://www.uipath.com/pricing\n  - type: TermsOfService\n    url: https://www.uipath.com/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.uipath.com/legal/privacy-policy\n  - type: Support\n    url: https://support.uipath.com\n  - type: StatusPage\n    url: https://status.uipath.com\n  - type: Academy\n    url: https://academy.uipath.com\n  - type: Forum\n    url: https://forum.uipath.com\n  - type: GitHubOrganization\n    url: https://github.com/UiPath\n  - type: SDK\n    url: https://pypi.org/project/uipath/\n    title: Python SDK\n  - type: SDK\n    url: https://github.com/UiPath/uipath-python\n    title: Python SDK GitHub\n  - type: SDK\n    url: https://github.com/UiPath/uipath-langchain-python\n    title: LangChain\
  \ Python SDK\n  - type: SDK\n    url: https://github.com/UiPath/uipath-typescript\n    title: TypeScript SDK\n  - type: SDK\n    url: https://github.com/UiPath/uipath-integrations-python\n    title: Python Integrations SDK\n  - type: Tools\n    url: https://github.com/UiPath/uipath-mcp-python\n    title: MCP Server\n  - type: CLI\n    url: https://github.com/UiPath/uipathcli\n    title: UiPath CLI\n  - type: CLI\n    url: https://docs.uipath.com/automation-cloud/docs/uipath-cli\n  - type: Signup\n    url: https://cloud.uipath.com/portal_/cloudrpa\n  - type: GettingStarted\n    url: https://docs.uipath.com/automation-cloud/docs/introduction\n  - type: Authentication\n    url: https://docs.uipath.com/automation-cloud/automation-cloud/latest/api-guide/accessing-uipath-resources-using-external-apps\n  - type: SpectralRules\n    url: rules/uipath-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/automation-operations.yaml\n    title: Automation Operations\n  - type: NaftikoCapability\n\
  \    url: capabilities/intelligent-document-processing.yaml\n    title: Intelligent Document Processing\n  - type: NaftikoCapability\n    url: capabilities/automation-governance.yaml\n    title: Automation Governance\n  - type: Vocabulary\n    url: vocabulary/uipath-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Robotic Process Automation\n        description: Automate repetitive tasks across any application using software robots with no-code, low-code, and coded automation options.\n      - name: AI-Powered Automation\n        description: Integrate AI capabilities including document understanding, computer vision, and natural language processing into automation workflows.\n      - name: Agentic Automation\n        description: Build and deploy intelligent agents using Python, LangGraph, or LlamaIndex frameworks on the UiPath Agent Cloud.\n      - name: Document Understanding\n        description: Extract structured data from unstructured documents using ML models for OCR,\
  \ classification, and field extraction.\n      - name: Orchestration\n        description: Centrally manage and monitor automation robots, jobs, queues, schedules, and assets across the enterprise.\n      - name: Process Mining\n        description: Discover and analyze business processes to identify automation opportunities and measure impact.\n      - name: Test Automation\n        description: Create, manage, and execute automated tests for RPA and application testing with enterprise CI/CD integration.\n      - name: Integration Service\n        description: Connect to 1,000+ applications and services through pre-built connectors for enterprise integration.\n  - type: UseCases\n    data:\n      - name: Finance and Accounting Automation\n        description: Automate invoice processing, accounts payable/receivable, financial reporting, and compliance workflows.\n      - name: HR Onboarding Automation\n        description: Streamline employee onboarding, offboarding, payroll processing,\
  \ and HR data management across systems.\n      - name: Customer Service Automation\n        description: Automate customer inquiry routing, case management, data lookup, and response generation.\n      - name: IT Process Automation\n        description: Automate IT service desk tickets, provisioning, monitoring alerts, and infrastructure management tasks.\n      - name: Healthcare Administration\n        description: Automate patient data management, claims processing, prior authorization, and regulatory reporting.\n      - name: Supply Chain Automation\n        description: Automate procurement, order management, inventory tracking, and logistics workflows.\n  - type: Integrations\n    data:\n      - name: Salesforce\n        description: Automate CRM operations, data sync, and customer workflows with native Salesforce integration.\n      - name: SAP\n        description: Connect with SAP ERP and S/4HANA for automated finance, HR, and supply chain processes.\n      - name: Microsoft\
  \ 365\n        description: Automate Office applications, SharePoint, Teams, and Azure services through Microsoft 365 integration.\n      - name: ServiceNow\n        description: Integrate with ServiceNow for ITSM automation, ticket management, and service catalog workflows.\n      - name: Workday\n        description: Connect with Workday HCM for HR automation, payroll processing, and workforce management.\n      - name: LangChain and LangGraph\n        description: Build and deploy AI agents using LangChain and LangGraph frameworks on the UiPath platform.\n  - type: Solutions\n    data:\n      - name: Automation Cloud Basic\n        description: Entry-level cloud automation for individuals and small teams with basic RPA and limited scale.\n      - name: Automation Cloud Standard\n        description: Professional automation platform for businesses with unlimited users, robots, and enterprise data extraction.\n      - name: Automation Cloud Enterprise\n        description: Strategic enterprise\
  \ automation with full infrastructure control, BYOK, multi-region deployment, and advanced AI capabilities.\n      - name: Automation Cloud Public Sector\n        description: FedRAMP Moderate authorized automation solution for U.S. government and public sector organizations.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/apis.yml
tags:
- Automation
- Robotic Process Automation
- RPA
- Artificial Intelligence
- Document Processing
- Enterprise Automation
- Orchestration
- Testing
url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/apis.yml
use_cases:
- description: Automate invoice processing, accounts payable/receivable, financial reporting, and compliance workflows.
  name: Finance and Accounting Automation
- description: Streamline employee onboarding, offboarding, payroll processing, and HR data management across systems.
  name: HR Onboarding Automation
- description: Automate customer inquiry routing, case management, data lookup, and response generation.
  name: Customer Service Automation
- description: Automate IT service desk tickets, provisioning, monitoring alerts, and infrastructure management tasks.
  name: IT Process Automation
- description: Automate patient data management, claims processing, prior authorization, and regulatory reporting.
  name: Healthcare Administration
- description: Automate procurement, order management, inventory tracking, and logistics workflows.
  name: Supply Chain Automation
---
