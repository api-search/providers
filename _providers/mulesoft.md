---
api_count: 6
api_specs:
- filename: mulesoft-anypoint-platform-openapi.yml
  format: yaml
  label: MuleSoft Anypoint Platform Management API
  slug: mulesoft-anypoint-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mulesoft/refs/heads/main/openapi/mulesoft-anypoint-platform-openapi.yml
apis:
- description: MuleSoft Anypoint Platform unifies API management with integration, providing a complete solution to connect any application, data source, or device with reusable APIs and integrations.
  name: MuleSoft Anypoint Platform
  slug: mulesoft
- description: The Anypoint Platform Management API provides programmatic access to manage organizations, business groups, environments, and users within the MuleSoft Anypoint Platform. It enables automation of plat
  name: MuleSoft Anypoint Platform Management API
  slug: mulesoft-anypoint-platform-api
- description: The Anypoint Exchange API provides programmatic access to MuleSoft's asset marketplace, enabling discovery, publishing, and management of reusable integration assets including APIs, connectors, templa
  name: MuleSoft Anypoint Exchange API
  slug: mulesoft-anypoint-exchange-api
- description: The Anypoint Runtime Manager API provides programmatic control over Mule application deployments across CloudHub, Runtime Fabric, and hybrid deployment targets. It enables CI/CD automation for deployi
  name: MuleSoft Anypoint Runtime Manager API
  slug: mulesoft-anypoint-runtime-manager-api
- description: The Anypoint MQ API provides a cloud messaging service built on the Anypoint Platform for asynchronous messaging between Mule applications and other systems. It supports queues, exchanges, and dead-le
  name: MuleSoft Anypoint MQ API
  slug: mulesoft-anypoint-mq-api
- description: The Anypoint Design Center API provides access to the MuleSoft web-based API design environment for creating and editing API specifications in RAML and OAS formats. It supports project management, fil
  name: MuleSoft Anypoint Design Center API
  slug: mulesoft-anypoint-design-center-api
common:
- title: ''
  type: Portal
  url: https://www.mulesoft.com/
- title: ''
  type: DeveloperPortal
  url: https://anypoint.mulesoft.com/exchange/portals/anypoint-platform/
- title: ''
  type: Documentation
  url: https://docs.mulesoft.com/
- title: ''
  type: GettingStarted
  url: https://docs.mulesoft.com/general/
- title: ''
  type: Authentication
  url: https://docs.mulesoft.com/access-management/connected-apps-overview
- title: ''
  type: Console
  url: https://anypoint.mulesoft.com/
- title: ''
  type: Blog
  url: https://blogs.mulesoft.com/
- title: ''
  type: ChangeLog
  url: https://docs.mulesoft.com/release-notes/
- title: ''
  type: StatusPage
  url: https://trust.mulesoft.com/
- title: ''
  type: Support
  url: https://help.mulesoft.com/s/support
- title: ''
  type: Pricing
  url: https://www.mulesoft.com/platform/mule-esb-open-source-esb/pricing
- title: ''
  type: TermsOfService
  url: https://www.mulesoft.com/legal/terms/EULA
- title: ''
  type: PrivacyPolicy
  url: https://www.mulesoft.com/legal/privacy
- title: ''
  type: GitHubOrganization
  url: https://github.com/mulesoft
- title: ''
  type: GitHubRepository
  url: https://github.com/mulesoft/anypoint-examples
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/mule
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/mulesofttv
- title: ''
  type: SDK
  url: https://docs.mulesoft.com/mule-sdk/latest/
- title: ''
  type: Glossary
  url: https://docs.mulesoft.com/general/glossary
- title: ''
  type: SignUp
  url: https://anypoint.mulesoft.com/login/signup?apintent=generic
- title: ''
  type: Login
  url: https://anypoint.mulesoft.com/login/signin?apintent=generic
- title: ''
  type: Partners
  url: https://www.mulesoft.com/integration-partner/partnermax-retirement
- title: ''
  type: SpectralRules
  url: rules/mulesoft-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/mulesoft-vocabulary.yaml
created: '2026-03-18'
description: MuleSoft Anypoint Platform is an enterprise integration and API management platform offering an API gateway, design center, exchange marketplace, and monitoring for hybrid deployments connecting applications and data.
features:
- description: Enterprise-grade API gateway for securing, governing, and managing API traffic across cloud and on-premises environments.
  name: API Gateway
- description: Centralized marketplace for discovering, sharing, and reusing APIs, connectors, templates, and integration assets across the organization.
  name: Anypoint Exchange
- description: Web-based API design environment for creating and editing API specifications in RAML and OAS formats with real-time collaboration.
  name: Design Center
- description: Unified management console for deploying, monitoring, and managing Mule applications across CloudHub, Runtime Fabric, and hybrid targets.
  name: Runtime Manager
- description: Cloud-native messaging service supporting queues, exchanges, and dead-letter queues for reliable asynchronous integration patterns.
  name: Anypoint MQ
- description: Powerful data transformation language for mapping and converting data between formats within Mule integration flows.
  name: DataWeave
- description: Eclipse-based IDE for building Mule applications with visual flow design and integrated debugging capabilities.
  name: Anypoint Studio
- description: Browser-based low-code tool for building simple integrations and automations without needing Anypoint Studio.
  name: Flow Designer
- description: Policy enforcement and governance framework for ensuring API consistency, security, and compliance across the platform.
  name: API Governance
- description: Real-time visibility into API and integration performance with dashboards, alerts, and log management.
  name: Anypoint Monitoring
image: /assets/icons/mulesoft.png
integrations:
- description: Native integration with Salesforce CRM, Service Cloud, and Marketing Cloud for bidirectional data sync and event-driven workflows.
  name: Salesforce
- description: Pre-built connector for SAP ERP, S/4HANA, and BTP enabling real-time data exchange with SAP systems.
  name: SAP
- description: Connector for syncing HR, finance, and planning data between Workday and other enterprise applications.
  name: Workday
- description: Integration with ServiceNow ITSM and ITOM for automated ticket creation, incident management, and CMDB sync.
  name: ServiceNow
- description: Connectors for Amazon S3, SQS, SNS, Lambda, and other AWS services for hybrid cloud integration.
  name: AWS
- description: Integration with Azure Service Bus, Blob Storage, SQL Database, and Active Directory services.
  name: Microsoft Azure
- description: Connector for sending notifications, creating channels, and automating workflows within Slack workspaces.
  name: Slack
- description: Pre-built connector for Oracle NetSuite ERP enabling financial, inventory, and order management integration.
  name: NetSuite
jsonld:
- class_count: 0
  name: Mulesoft Anypoint Platform Context
  property_count: 0
  slug: mulesoft-anypoint-platform-context
- class_count: 0
  name: Mulesoft Context
  property_count: 7
  slug: mulesoft-context
layout: provider
modified: '2026-04-18'
name: MuleSoft
rules:
- name: MuleSoft API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: mulesoft-spectral-rules
skills: []
slug: mulesoft
solutions: []
source_filename: apis.yml
source_yaml: "aid: mulesoft\nname: MuleSoft\ndescription: >-\n  MuleSoft Anypoint Platform is an enterprise integration and API management\n  platform offering an API gateway, design center, exchange marketplace,\n  and monitoring for hybrid deployments connecting applications and data.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - API Management\n  - Enterprise\n  - Integration\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/mulesoft/refs/heads/main/apis.yml\ncreated: '2026-03-18'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - aid: mulesoft:mulesoft\n    name: MuleSoft Anypoint Platform\n    description: >-\n      MuleSoft Anypoint Platform unifies API management with integration,\n      providing a complete solution to connect any application, data source,\n      or device with reusable APIs and integrations.\n    humanURL: https://www.mulesoft.com/platform/api\n    tags:\n   \
  \   - API Gateway\n      - API Management\n      - Enterprise\n    properties:\n      - type: Documentation\n        url: https://docs.mulesoft.com/\n      - type: GettingStarted\n        url: https://docs.mulesoft.com/general/\n  - aid: mulesoft:mulesoft-anypoint-platform-api\n    name: MuleSoft Anypoint Platform Management API\n    description: >-\n      The Anypoint Platform Management API provides programmatic access to\n      manage organizations, business groups, environments, and users within\n      the MuleSoft Anypoint Platform. It enables automation of platform\n      administration tasks including configuring access management, managing\n      connected applications, and controlling role-based access control across\n      the platform.\n    humanURL: https://docs.mulesoft.com/access-management/\n    baseURL: https://anypoint.mulesoft.com\n    tags:\n      - Administration\n      - API Management\n      - Enterprise\n      - REST\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.mulesoft.com/access-management/\n      - type: APIReference\n        url: https://anypoint.mulesoft.com/exchange/portals/anypoint-platform/\n      - type: Authentication\n        url: https://docs.mulesoft.com/access-management/connected-apps-overview\n      - type: OpenAPI\n        url: openapi/mulesoft-anypoint-platform-openapi.yml\n      - type: JSONSchema\n        url: json-schema/mulesoft-application-schema.json\n      - type: JSONLD\n        url: json-ld/mulesoft-context.jsonld\n  - aid: mulesoft:mulesoft-anypoint-exchange-api\n    name: MuleSoft Anypoint Exchange API\n    description: >-\n      The Anypoint Exchange API provides programmatic access to MuleSoft's\n      asset marketplace, enabling discovery, publishing, and management of\n      reusable integration assets including APIs, connectors, templates,\n      examples, and custom pages. It allows organizations to automate asset\n      lifecycle management and promote API reuse across teams.\n  \
  \  humanURL: https://docs.mulesoft.com/exchange/\n    baseURL: https://anypoint.mulesoft.com/exchange/api/v2\n    tags:\n      - API Catalog\n      - Asset Management\n      - Enterprise\n      - Marketplace\n    properties:\n      - type: Documentation\n        url: https://docs.mulesoft.com/exchange/\n      - type: APIReference\n        url: https://anypoint.mulesoft.com/exchange/portals/anypoint-platform/f1e97bc6-315a-4490-82a7-23abe036327a.anypoint-platform/exchange-experience-api/\n      - type: GettingStarted\n        url: https://docs.mulesoft.com/exchange/to-publish-assets-maven\n  - aid: mulesoft:mulesoft-anypoint-runtime-manager-api\n    name: MuleSoft Anypoint Runtime Manager API\n    description: >-\n      The Anypoint Runtime Manager API provides programmatic control over\n      Mule application deployments across CloudHub, Runtime Fabric, and\n      hybrid deployment targets. It enables CI/CD automation for deploying,\n      updating, starting, stopping, and monitoring Mule\
  \ applications and\n      their runtime environments.\n    humanURL: https://docs.mulesoft.com/runtime-manager/\n    baseURL: https://anypoint.mulesoft.com/cloudhub/api\n    tags:\n      - CI/CD\n      - CloudHub\n      - Deployment\n      - Runtime Manager\n    properties:\n      - type: Documentation\n        url: https://docs.mulesoft.com/runtime-manager/\n      - type: APIReference\n        url: https://docs.mulesoft.com/runtime-manager/cloudhub-api\n      - type: GettingStarted\n        url: https://docs.mulesoft.com/runtime-manager/deploying-to-cloudhub\n  - aid: mulesoft:mulesoft-anypoint-mq-api\n    name: MuleSoft Anypoint MQ API\n    description: >-\n      The Anypoint MQ API provides a cloud messaging service built on the\n      Anypoint Platform for asynchronous messaging between Mule applications\n      and other systems. It supports queues, exchanges, and dead-letter queues\n      for reliable message delivery and decoupled integration patterns.\n    humanURL: https://docs.mulesoft.com/mq/\n\
  \    baseURL: https://anypoint.mulesoft.com/mq/stats/api/v1\n    tags:\n      - Async\n      - Cloud\n      - Messaging\n      - Queue\n    properties:\n      - type: Documentation\n        url: https://docs.mulesoft.com/mq/\n      - type: APIReference\n        url: https://docs.mulesoft.com/mq/mq-apis\n      - type: GettingStarted\n        url: https://docs.mulesoft.com/mq/mq-tutorial\n  - aid: mulesoft:mulesoft-anypoint-design-center-api\n    name: MuleSoft Anypoint Design Center API\n    description: >-\n      The Anypoint Design Center API provides access to the MuleSoft web-based\n      API design environment for creating and editing API specifications in\n      RAML and OAS formats. It supports project management, file operations,\n      and publishing designed APIs to Anypoint Exchange for reuse across\n      the organization.\n    humanURL: https://docs.mulesoft.com/design-center/\n    baseURL: https://anypoint.mulesoft.com/designcenter/api-designer\n    tags:\n      - API Design\n\
  \      - Design Center\n      - OpenAPI\n      - RAML\n    properties:\n      - type: Documentation\n        url: https://docs.mulesoft.com/design-center/\n      - type: GettingStarted\n        url: https://docs.mulesoft.com/design-center/design-create-publish-api-specs\ncommon:\n  - type: Portal\n    url: https://www.mulesoft.com/\n  - type: DeveloperPortal\n    url: https://anypoint.mulesoft.com/exchange/portals/anypoint-platform/\n  - type: Documentation\n    url: https://docs.mulesoft.com/\n  - type: GettingStarted\n    url: https://docs.mulesoft.com/general/\n  - type: Authentication\n    url: https://docs.mulesoft.com/access-management/connected-apps-overview\n  - type: Console\n    url: https://anypoint.mulesoft.com/\n  - type: Blog\n    url: https://blogs.mulesoft.com/\n  - type: ChangeLog\n    url: https://docs.mulesoft.com/release-notes/\n  - type: StatusPage\n    url: https://trust.mulesoft.com/\n  - type: Support\n    url: https://help.mulesoft.com/s/support\n  - type: Pricing\n\
  \    url: https://www.mulesoft.com/platform/mule-esb-open-source-esb/pricing\n  - type: TermsOfService\n    url: https://www.mulesoft.com/legal/terms/EULA\n  - type: PrivacyPolicy\n    url: https://www.mulesoft.com/legal/privacy\n  - type: GitHubOrganization\n    url: https://github.com/mulesoft\n  - type: GitHubRepository\n    url: https://github.com/mulesoft/anypoint-examples\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/mule\n  - type: YouTube\n    url: https://www.youtube.com/user/mulesofttv\n  - type: SDK\n    url: https://docs.mulesoft.com/mule-sdk/latest/\n  - type: Glossary\n    url: https://docs.mulesoft.com/general/glossary\n  - type: SignUp\n    url: https://anypoint.mulesoft.com/login/signup?apintent=generic\n  - type: Login\n    url: https://anypoint.mulesoft.com/login/signin?apintent=generic\n  - type: Partners\n    url: https://www.mulesoft.com/integration-partner/partnermax-retirement\n  - type: SpectralRules\n    url: rules/mulesoft-spectral-rules.yml\n\
  \  - type: Vocabulary\n    url: vocabulary/mulesoft-vocabulary.yaml\n  - type: Features\n    url: https://www.mulesoft.com/platform\n    data:\n      - name: API Gateway\n        description: Enterprise-grade API gateway for securing, governing, and managing API traffic across cloud and on-premises environments.\n      - name: Anypoint Exchange\n        description: Centralized marketplace for discovering, sharing, and reusing APIs, connectors, templates, and integration assets across the organization.\n      - name: Design Center\n        description: Web-based API design environment for creating and editing API specifications in RAML and OAS formats with real-time collaboration.\n      - name: Runtime Manager\n        description: Unified management console for deploying, monitoring, and managing Mule applications across CloudHub, Runtime Fabric, and hybrid targets.\n      - name: Anypoint MQ\n        description: Cloud-native messaging service supporting queues, exchanges, and dead-letter\
  \ queues for reliable asynchronous integration patterns.\n      - name: DataWeave\n        description: Powerful data transformation language for mapping and converting data between formats within Mule integration flows.\n      - name: Anypoint Studio\n        description: Eclipse-based IDE for building Mule applications with visual flow design and integrated debugging capabilities.\n      - name: Flow Designer\n        description: Browser-based low-code tool for building simple integrations and automations without needing Anypoint Studio.\n      - name: API Governance\n        description: Policy enforcement and governance framework for ensuring API consistency, security, and compliance across the platform.\n      - name: Anypoint Monitoring\n        description: Real-time visibility into API and integration performance with dashboards, alerts, and log management.\n  - type: UseCases\n    url: https://www.mulesoft.com/integration-solutions\n    data:\n      - name: Application Integration\n\
  \        description: Connect SaaS and on-premises applications to create unified business processes and eliminate data silos.\n      - name: API-Led Connectivity\n        description: Build reusable APIs organized in system, process, and experience layers to accelerate digital transformation.\n      - name: B2B Integration\n        description: Automate partner onboarding and EDI/AS2 data exchange with trading partners using pre-built connectors.\n      - name: Cloud Migration\n        description: Migrate on-premises integrations to the cloud while maintaining connectivity with legacy systems.\n      - name: Customer 360\n        description: Unify customer data across CRM, ERP, and marketing systems to create a single view of the customer.\n      - name: AI Agent Integration\n        description: Connect AI agents to enterprise systems, models, and vector stores to orchestrate complex agentic workflows.\n  - type: Integrations\n    url: https://www.mulesoft.com/exchange/\n    data:\n\
  \      - name: Salesforce\n        description: Native integration with Salesforce CRM, Service Cloud, and Marketing Cloud for bidirectional data sync and event-driven workflows.\n      - name: SAP\n        description: Pre-built connector for SAP ERP, S/4HANA, and BTP enabling real-time data exchange with SAP systems.\n      - name: Workday\n        description: Connector for syncing HR, finance, and planning data between Workday and other enterprise applications.\n      - name: ServiceNow\n        description: Integration with ServiceNow ITSM and ITOM for automated ticket creation, incident management, and CMDB sync.\n      - name: AWS\n        description: Connectors for Amazon S3, SQS, SNS, Lambda, and other AWS services for hybrid cloud integration.\n      - name: Microsoft Azure\n        description: Integration with Azure Service Bus, Blob Storage, SQL Database, and Active Directory services.\n      - name: Slack\n        description: Connector for sending notifications, creating\
  \ channels, and automating workflows within Slack workspaces.\n      - name: NetSuite\n        description: Pre-built connector for Oracle NetSuite ERP enabling financial, inventory, and order management integration.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/mulesoft/refs/heads/main/apis.yml
tags:
- API Gateway
- API Management
- Enterprise
- Integration
url: https://raw.githubusercontent.com/api-evangelist/mulesoft/refs/heads/main/apis.yml
use_cases:
- description: Connect SaaS and on-premises applications to create unified business processes and eliminate data silos.
  name: Application Integration
- description: Build reusable APIs organized in system, process, and experience layers to accelerate digital transformation.
  name: API-Led Connectivity
- description: Automate partner onboarding and EDI/AS2 data exchange with trading partners using pre-built connectors.
  name: B2B Integration
- description: Migrate on-premises integrations to the cloud while maintaining connectivity with legacy systems.
  name: Cloud Migration
- description: Unify customer data across CRM, ERP, and marketing systems to create a single view of the customer.
  name: Customer 360
- description: Connect AI agents to enterprise systems, models, and vector stores to orchestrate complex agentic workflows.
  name: AI Agent Integration
---
