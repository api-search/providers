---
api_count: 19
api_specs:
- filename: sap-business-one-service-layer-openapi.yml
  format: yaml
  label: SAP Business One Service Layer API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap/refs/heads/main/openapi/sap-business-one-service-layer-openapi.yml
- filename: sap-s4hana-cloud-business-partner-openapi.yml
  format: yaml
  label: SAP S/4HANA Cloud API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap/refs/heads/main/openapi/sap-s4hana-cloud-business-partner-openapi.yml
- filename: sap-event-mesh-asyncapi.yml
  format: yaml
  label: SAP Event Mesh API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap/refs/heads/main/asyncapi/sap-event-mesh-asyncapi.yml
- filename: sap-ai-core-openapi.yml
  format: yaml
  label: SAP AI Core API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap/refs/heads/main/openapi/sap-ai-core-openapi.yml
apis:
- description: RESTful API for accessing SAP Business One data and business logic.
  name: SAP Business One Service Layer API
  slug: ''
- description: APIs for SAP S/4HANA Cloud enabling integration with intelligent ERP.
  name: SAP S/4HANA Cloud API
  slug: ''
- description: Human Capital Management APIs for employee central, recruiting, and talent management.
  name: SAP SuccessFactors API
  slug: ''
- description: Procurement and supply chain APIs for sourcing, contracts, and supplier management.
  name: SAP Ariba APIs
  slug: ''
- description: Integration APIs for connecting applications, data, and processes.
  name: SAP Cloud Platform Integration Suite
  slug: ''
- description: E-commerce APIs for product catalog, cart, checkout, and order management.
  name: SAP Commerce Cloud API
  slug: ''
- description: APIs for business intelligence, planning, and predictive analytics.
  name: SAP Analytics Cloud API
  slug: ''
- description: APIs for travel and expense management including expense reporting, travel booking, and invoice processing.
  name: SAP Concur API
  slug: ''
- description: Vendor management system APIs for managing external workers, contractors, and service providers.
  name: SAP Fieldglass API
  slug: ''
- description: Core platform APIs for managing accounts, entitlements, and services on SAP Business Technology Platform.
  name: SAP BTP Core Services API
  slug: ''
- description: APIs for data warehousing, catalog access, and consumption of analytical and relational models.
  name: SAP Datasphere API
  slug: ''
- description: Messaging APIs for event-driven architecture supporting AMQP, MQTT, and REST protocols.
  name: SAP Event Mesh API
  slug: ''
- description: APIs for centralizing and harmonizing master data across SAP and third-party applications.
  name: SAP Master Data Integration API
  slug: ''
- description: APIs for process modeling, BPMN diagram management, and process governance automation.
  name: SAP Signavio Process Manager API
  slug: ''
- description: CMIS-based APIs for document management including versioning, access control, and content storage on BTP.
  name: SAP Document Management Service API
  slug: ''
- description: APIs for building, managing, publishing, and monitoring API proxies within SAP Integration Suite.
  name: SAP Integration Suite API Management
  slug: ''
- description: APIs for deploying, managing, and consuming AI models and workflows on SAP Business Technology Platform. Provides endpoints for scenario management, execution orchestration, and model serving.
  name: SAP AI Core API
  slug: ''
- description: REST APIs for marketing automation, customer engagement, and personalized campaign management across email, web, SMS, and mobile channels.
  name: SAP Emarsys Customer Engagement API
  slug: ''
- description: APIs for managing digital workplace experiences, integrating business applications into unified workpages, and administering work zone sites and content.
  name: SAP Build Work Zone API
  slug: ''
asyncapis:
- description: Event-driven messaging API for SAP Business Technology Platform supporting AMQP, MQTT, and REST protocols. Enables publish/subscribe patterns for business events across SAP and third-party application
  name: SAP Event Mesh Events
  slug: sap-event-mesh-asyncapi
capabilities:
- description: Unified workflow combining SAP Business One, S/4HANA Cloud Business Partner, and AI Core APIs for managing business partners, orders, financials, and AI-driven automation across SAP ERP systems.
  name: SAP Enterprise Business Operations
  slug: enterprise-business-operations
common:
- title: ''
  type: DeveloperPortal
  url: https://developers.sap.com/
- title: ''
  type: Hub
  url: https://api.sap.com
- title: ''
  type: Blog
  url: https://community.sap.com/t5/all-sap-community-blogs/ct-p/all-blogs
- title: ''
  type: Support
  url: https://community.sap.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/SAP
- title: ''
  type: StatusPage
  url: https://www.sap.com/about/trust-center/cloud-service-status.html
- title: ''
  type: Support
  url: https://support.sap.com/
- title: ''
  type: PrivacyPolicy
  url: https://www.sap.com/about/legal/privacy.html
- title: ''
  type: TermsOfService
  url: https://www.sap.com/about/legal/terms-of-use.html
- title: ''
  type: GettingStarted
  url: https://developers.sap.com/tutorial-navigator.html
- title: ''
  type: Training
  url: https://learning.sap.com/
- title: ''
  type: Portal
  url: https://www.sap.com
- title: ''
  type: SignUp
  url: https://developers.sap.com/tutorials/hcp-create-trial-account.html
- title: ''
  type: Login
  url: https://accounts.sap.com
- title: ''
  type: SDK
  url: https://developers.sap.com/topics/cloud-sdk.html
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/sap
- title: ''
  type: YouTube
  url: https://www.youtube.com/@SAPTechnology
- title: ''
  type: ChangeLog
  url: https://help.sap.com/whats-new/
- title: ''
  type: JSONLD
  url: json-ld/sap-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/sap-business-partner-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sap-sales-order-schema.json
- title: ''
  type: Rules
  url: rules/sap-spectral-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/shared/ai-core.yaml
- title: ''
  type: Capabilities
  url: capabilities/shared/business-one.yaml
- title: ''
  type: Capabilities
  url: capabilities/shared/s4hana-business-partner.yaml
- title: ''
  type: Capabilities
  url: capabilities/enterprise-business-operations.yaml
created: '2024-01-15'
description: Collection of SAP's enterprise APIs for business applications and cloud services.
features:
- ERP and business suite APIs for finance, HR, procurement, and supply chain
- AI/ML model deployment and serving via AI Core on BTP
- Master data management and integration across SAP and third-party systems
- Event-driven architecture with AMQP, MQTT, and REST messaging
- OData-compatible endpoints for business object CRUD operations
image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg
integrations:
- SAP S/4HANA Cloud with CRM and e-commerce platforms
- SAP AI Core with machine learning frameworks and model registries
- SAP Integration Suite with middleware and iPaaS connectors
- SAP SuccessFactors with HR and talent management systems
- SAP Event Mesh with event-driven microservices architectures
jsonld:
- class_count: 0
  name: Sap Ai Core Context
  property_count: 0
  slug: sap-ai-core-context
- class_count: 0
  name: Sap Business One Service Layer Context
  property_count: 0
  slug: sap-business-one-service-layer-context
- class_count: 0
  name: Sap Context
  property_count: 8
  slug: sap-context
- class_count: 0
  name: Sap S4Hana Cloud Business Partner Context
  property_count: 0
  slug: sap-s4hana-cloud-business-partner-context
layout: provider
modified: '2026-04-18'
name: SAP
rules:
- name: SAP API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: sap-spectral-rules
skills: []
slug: sap
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SAP\ndescription: >-\n  Collection of SAP's enterprise APIs for business applications and cloud services.\nimage: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\nurl: https://api.sap.com\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\napis:\n  - name: SAP Business One Service Layer API\n    description: >-\n      RESTful API for accessing SAP Business One data and business logic.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://help.sap.com/docs/SAP_BUSINESS_ONE_SERVICE_LAYER\n    baseUrl: https://{server}:50000/b1s/v1\n    tags:\n      - Business Management\n      - Enterprise\n      - ERP\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_BUSINESS_ONE_SERVICE_LAYER\n      - type: OpenAPI\n        url: openapi/sap-business-one-service-layer-openapi.yml\n      - type: Authentication\n        url: https://help.sap.com/docs/SAP_BUSINESS_ONE_SERVICE_LAYER/0a7d48c2c45a4732914129e920b0a8c1/Authentication.html\n\
  \      - type: GettingStarted\n        url: https://help.sap.com/docs/SAP_BUSINESS_ONE_SERVICE_LAYER/0a7d48c2c45a4732914129e920b0a8c1/Getting_Started.html\n  - name: SAP S/4HANA Cloud API\n    description: >-\n      APIs for SAP S/4HANA Cloud enabling integration with intelligent ERP.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/package/SAPS4HANACloud\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud\n    tags:\n      - Cloud\n      - Enterprise Resource Planning\n      - ERP\n      - S/4HANA\n    properties:\n      - type: OpenAPI\n        url: openapi/sap-s4hana-cloud-business-partner-openapi.yml\n      - type: Documentation\n        url: https://api.sap.com/package/SAPS4HANACloud\n      - type: Hub\n        url: https://api.sap.com/package/SAPS4HANACloud/rest\n      - type: Sandbox\n        url: https://api.sap.com/api/API_BUSINESS_PARTNER/tryout\n      - type: GettingStarted\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD\n\
  \  - name: SAP SuccessFactors API\n    description: >-\n      Human Capital Management APIs for employee central, recruiting, and talent management.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/package/SAPSuccessFactors\n    baseUrl: https://api.successfactors.com/odata/v2\n    tags:\n      - HCM\n      - HR\n      - Human Resources\n      - Talent Management\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_SUCCESSFACTORS_PLATFORM/d599f15995d348a1b45ba5603e2aba9b/\n      - type: APIReference\n        url: https://api.sap.com/package/SAPSuccessFactors/odata\n      - type: APIReference\n        url: https://help.sap.com/doc/74597e67f54d4f448252bad4c2b601c9/\n      - type: Hub\n        url: https://api.sap.com/package/SAPSuccessFactors\n  - name: SAP Ariba APIs\n    description: >-\n      Procurement and supply chain APIs for sourcing, contracts, and supplier management.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n\
  \    humanUrl: https://developer.ariba.com\n    baseUrl: https://openapi.ariba.com\n    tags:\n      - Procurement\n      - Sourcing\n      - Supplier Management\n      - Supply Chain\n    properties:\n      - type: Documentation\n        url: https://developer.ariba.com/api\n      - type: DeveloperPortal\n        url: https://developer.ariba.com\n      - type: APIReference\n        url: https://developer.ariba.com/api/guides\n  - name: SAP Cloud Platform Integration Suite\n    description: >-\n      Integration APIs for connecting applications, data, and processes.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/package/CloudPlatformIntegration\n    baseUrl: https://{tenant}.it-cpi{xx}.cfapps.{region}.hana.ondemand.com\n    tags:\n      - Cloud Platform\n      - Integration\n      - iPaaS\n      - Middleware\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/CLOUD_INTEGRATION\n      - type:\
  \ Hub\n        url: https://api.sap.com/package/CloudPlatformIntegration\n      - type: Training\n        url: https://help.sap.com/learning-journeys/integrate-applications-and-services\n      - type: GettingStarted\n        url: https://help.sap.com/docs/integration-suite/sap-integration-suite/api-management-capability\n  - name: SAP Commerce Cloud API\n    description: >-\n      E-commerce APIs for product catalog, cart, checkout, and order management.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://help.sap.com/docs/SAP_COMMERCE_CLOUD\n    baseUrl: https://{baseSiteId}.{environment}/rest/v2\n    tags:\n      - Commerce\n      - E-Commerce\n      - OCC\n      - Retail\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/0996ba68e5794b8ab51db8d25d4c9f4a/\n      - type: APIReference\n        url: https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/9d346683b0084da2938be8a285c0c27a/\n\
  \      - type: APIReference\n        url: https://help.sap.com/docs/SAP_COMMERCE_CLOUD/9d346683b0084da2938be8a285c0c27a/swagger.html\n  - name: SAP Analytics Cloud API\n    description: >-\n      APIs for business intelligence, planning, and predictive analytics.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD\n    baseUrl: https://{tenant}.{region}.sapanalytics.cloud/api/v1\n    tags:\n      - Analytics\n      - BI\n      - Business Intelligence\n      - Planning\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/14cac91febef464dbb1efce20e3f1613/\n      - type: APIReference\n        url: https://help.sap.com/doc/14cac91febef464dbb1efce20e3f1613/release/en-US/index.html\n      - type: APIReference\n        url: https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/c7c2d8a03f524126af618f2cdac43595/\n  - name: SAP Concur API\n    description: >-\n      APIs\
  \ for travel and expense management including expense reporting, travel booking,\n      and invoice processing.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://developer.concur.com\n    baseUrl: https://us.api.concursolutions.com\n    tags:\n      - Concur\n      - Expense Management\n      - Invoice\n      - Travel\n    properties:\n      - type: Documentation\n        url: https://developer.concur.com/api-reference/\n      - type: DeveloperPortal\n        url: https://developer.concur.com\n      - type: Authentication\n        url: https://developer.concur.com/api-reference/authentication/getting-started.html\n      - type: Hub\n        url: https://api.sap.com/products/SAPConcur/apis/REST\n      - type: ChangeLog\n        url: https://developer.concur.com/tools-support/release-notes/\n  - name: SAP Fieldglass API\n    description: >-\n      Vendor management system APIs for managing external workers, contractors, and\n      service providers.\n\
  \    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/products/SAPFieldglass/apis/packages\n    baseUrl: https://www.fieldglass.net/api\n    tags:\n      - Contingent Workforce\n      - External Workers\n      - Vendor Management\n      - VMS\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_FIELDGLASS_INTEGRATION\n      - type: Hub\n        url: https://api.sap.com/package/FieldglassAPI\n      - type: APIReference\n        url: https://api.sap.com/package/FieldglassAPI/odata\n      - type: APIReference\n        url: https://api.sap.com/products/SAPFieldglass/apis/all\n  - name: SAP BTP Core Services API\n    description: >-\n      Core platform APIs for managing accounts, entitlements, and services on SAP\n      Business Technology Platform.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/package/SAPCloudPlatformCoreServices/overview\n\
  \    baseUrl: https://accounts-service.cfapps.{region}.hana.ondemand.com\n    tags:\n      - BTP\n      - Cloud Management\n      - Cloud Platform\n      - Platform Services\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/BTP\n      - type: APIReference\n        url: https://api.sap.com/package/SAPCloudPlatformCoreServices/rest\n      - type: Hub\n        url: https://api.sap.com/package/SAPCloudPlatformCoreServices/overview\n      - type: GettingStarted\n        url: https://help.sap.com/docs/btp/btp-developers-guide/apis\n  - name: SAP Datasphere API\n    description: >-\n      APIs for data warehousing, catalog access, and consumption of analytical and\n      relational models.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/package/sapdatasphere/overview\n    baseUrl: https://{tenant}.{region}.hcs.cloud.sap\n    tags:\n      - Analytics\n      - Data Integration\n      - Data Warehousing\n\
  \      - Datasphere\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_DATASPHERE\n      - type: APIReference\n        url: https://api.sap.com/package/sapdatasphere/odatav4\n      - type: Hub\n        url: https://api.sap.com/package/sapdatasphere/overview\n      - type: APIReference\n        url: https://api.sap.com/api/DatasphereCatalog/resource/\n  - name: SAP Event Mesh API\n    description: >-\n      Messaging APIs for event-driven architecture supporting AMQP, MQTT, and REST\n      protocols.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://help.sap.com/docs/event-mesh\n    baseUrl: https://enterprise-messaging-pubsub.cfapps.{region}.hana.ondemand.com\n    tags:\n      - AMQP\n      - Event-Driven\n      - Messaging\n      - MQTT\n    properties:\n      - type: AsyncAPI\n        url: asyncapi/sap-event-mesh-asyncapi.yml\n      - type: Documentation\n        url: https://help.sap.com/docs/event-mesh\n\
  \      - type: APIReference\n        url: https://help.sap.com/docs/event-mesh/event-mesh/rest-apis-for-messaging\n      - type: Hub\n        url: https://api.sap.com/package/SAPEventMeshDefaultPlan/rest\n      - type: GettingStarted\n        url: https://help.sap.com/docs/event-mesh/event-mesh/what-is-sap-event-mesh\n  - name: SAP Master Data Integration API\n    description: >-\n      APIs for centralizing and harmonizing master data across SAP and third-party\n      applications.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/package/sap-mdi-masterDataIntegration/overview\n    baseUrl: https://{tenant}.integrationsuite.{region}.hana.ondemand.com\n    tags:\n      - Data Integration\n      - Data Quality\n      - Master Data\n      - MDI\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_MASTER_DATA_INTEGRATION\n      - type: APIReference\n        url: https://api.sap.com/package/sap-mdi-masterDataIntegration\n\
  \      - type: Hub\n        url: https://api.sap.com/package/sap-mdi-masterDataIntegration/overview\n      - type: APIReference\n        url: https://api.sap.com/api/masterdata/resource\n  - name: SAP Signavio Process Manager API\n    description: >-\n      APIs for process modeling, BPMN diagram management, and process governance automation.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://help.sap.com/docs/signavio-process-manager/sap-signavio-process-manager-api/sap-signavio-process-manager-api-guide\n    baseUrl: https://editor.signavio.com/p\n    tags:\n      - BPM\n      - BPMN\n      - Process Management\n      - Process Mining\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/signavio-process-manager/sap-signavio-process-manager-api/sap-signavio-process-manager-api-guide\n      - type: APIReference\n        url: https://help.sap.com/docs/signavio-process-insights/api-reference/getting-started-with-apis\n\
  \      - type: APIReference\n        url: https://help.sap.com/docs/signavio-process-governance/developer-guide/public-api\n  - name: SAP Document Management Service API\n    description: >-\n      CMIS-based APIs for document management including versioning, access control,\n      and content storage on BTP.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://help.sap.com/docs/document-management-service\n    baseUrl: https://{tenant}.document-center.cfapps.{region}.hana.ondemand.com\n    tags:\n      - BTP\n      - CMIS\n      - Content Management\n      - Document Management\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/document-management-service\n      - type: Hub\n        url: https://api.sap.com/package/SAPDocumentManagementServiceIntegrationOptionCMISAPI/rest\n      - type: GettingStarted\n        url: https://help.sap.com/docs/document-management-service/sap-document-management-service/access-document-management-service-application-option-repository-using-api\n\
  \  - name: SAP Integration Suite API Management\n    description: >-\n      APIs for building, managing, publishing, and monitoring API proxies within SAP\n      Integration Suite.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://help.sap.com/docs/sap-api-management\n    baseUrl: https://{tenant}.{region}.apimanagement.hana.ondemand.com\n    tags:\n      - API Gateway\n      - API Management\n      - API Proxy\n      - Integration Suite\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/integration-suite/sap-integration-suite/api-documentation\n      - type: Hub\n        url: https://api.sap.com/package/APIMgmt/overview\n      - type: GettingStarted\n        url: https://developers.sap.com/group.cp-apim-code-1.html\n      - type: DeveloperPortal\n        url: https://api.sap.com/api/APIPortal_Developer_CF/overview\n  - name: SAP AI Core API\n    description: >-\n      APIs for deploying, managing, and consuming\
  \ AI models and workflows on SAP\n      Business Technology Platform. Provides endpoints for scenario management,\n      execution orchestration, and model serving.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://help.sap.com/docs/sap-ai-core/sap-ai-core-service-guide/about-ai-api\n    baseUrl: https://api.ai.{region}.cfapps.{landscape}.hana.ondemand.com/v2\n    tags:\n      - AI Core\n      - Artificial Intelligence\n      - BTP\n      - Machine Learning\n    properties:\n      - type: OpenAPI\n        url: openapi/sap-ai-core-openapi.yml\n      - type: Documentation\n        url: https://help.sap.com/docs/sap-ai-core/sap-ai-core-service-guide/about-ai-api\n      - type: APIReference\n        url: https://api.sap.com/api/AI_CORE_API/resource\n      - type: Hub\n        url: https://api.sap.com/api/AI_CORE_API/overview\n      - type: SDK\n        url: https://sap.github.io/ai-sdk/docs/js/ai-core/ai-api\n  - name: SAP Emarsys Customer Engagement\
  \ API\n    description: >-\n      REST APIs for marketing automation, customer engagement, and personalized\n      campaign management across email, web, SMS, and mobile channels.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://dev.emarsys.com/\n    baseUrl: https://api.emarsys.net/api/v2\n    tags:\n      - CRM\n      - Customer Engagement\n      - Email Marketing\n      - Marketing Automation\n    properties:\n      - type: Documentation\n        url: https://dev.emarsys.com/\n      - type: APIReference\n        url: https://help.sap.com/docs/SAP_EMARSYS_CUSTOMER_ENGAGEMENT/f8e2fafeea804018a954a8857d9dfff3/fdf6023c74c11014b724bbfdb6028c98.html\n      - type: Hub\n        url: https://api.sap.com/package/SAPEmarsysCustomerEngagement/overview\n  - name: SAP Build Work Zone API\n    description: >-\n      APIs for managing digital workplace experiences, integrating business\n      applications into unified workpages, and administering work\
  \ zone sites and\n      content.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://help.sap.com/docs/build-work-zone-advanced-edition/sap-build-work-zone-advanced-edition/api-documentation\n    baseUrl: https://{tenant}.dt.workzone.cfapps.{region}.hana.ondemand.com\n    tags:\n      - BTP\n      - Digital Workplace\n      - Portal\n      - Work Zone\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/build-work-zone-advanced-edition/sap-build-work-zone-advanced-edition/api-documentation\ninclude:\n  - name: SAP API Business Hub\n    url: https://api.sap.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - AI\n  - BTP\n  - Business Applications\n  - Cloud\n  - Data Management\n  - Enterprise\n  - ERP\n  - Integration\ncommon:\n  - type: DeveloperPortal\n    url: https://developers.sap.com/\n  - type: Hub\n    url: https://api.sap.com\n  - type:\
  \ Blog\n    url: https://community.sap.com/t5/all-sap-community-blogs/ct-p/all-blogs\n  - type: Support\n    url: https://community.sap.com/\n  - type: GitHubOrganization\n    url: https://github.com/SAP\n  - type: StatusPage\n    url: https://www.sap.com/about/trust-center/cloud-service-status.html\n  - type: Support\n    url: https://support.sap.com/\n  - type: PrivacyPolicy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: TermsOfService\n    url: https://www.sap.com/about/legal/terms-of-use.html\n  - type: GettingStarted\n    url: https://developers.sap.com/tutorial-navigator.html\n  - type: Training\n    url: https://learning.sap.com/\n  - type: Portal\n    url: https://www.sap.com\n  - type: SignUp\n    url: https://developers.sap.com/tutorials/hcp-create-trial-account.html\n  - type: Login\n    url: https://accounts.sap.com\n  - type: SDK\n    url: https://developers.sap.com/topics/cloud-sdk.html\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/sap\n\
  \  - type: YouTube\n    url: https://www.youtube.com/@SAPTechnology\n  - type: ChangeLog\n    url: https://help.sap.com/whats-new/\n  - type: Features\n    data:\n      - ERP and business suite APIs for finance, HR, procurement, and supply chain\n      - AI/ML model deployment and serving via AI Core on BTP\n      - Master data management and integration across SAP and third-party systems\n      - Event-driven architecture with AMQP, MQTT, and REST messaging\n      - OData-compatible endpoints for business object CRUD operations\n  - type: UseCases\n    data:\n      - Automating order-to-cash and procure-to-pay business processes\n      - Deploying and serving AI models for intelligent enterprise workflows\n      - Integrating SAP ERP with third-party CRM, e-commerce, and analytics platforms\n      - Managing business partner master data across multi-system landscapes\n      - Building digital workplace experiences with unified work zone portals\n  - type: Integrations\n    data:\n   \
  \   - SAP S/4HANA Cloud with CRM and e-commerce platforms\n      - SAP AI Core with machine learning frameworks and model registries\n      - SAP Integration Suite with middleware and iPaaS connectors\n      - SAP SuccessFactors with HR and talent management systems\n      - SAP Event Mesh with event-driven microservices architectures\n  - type: JSONLD\n    url: json-ld/sap-context.jsonld\n  - type: JSONSchema\n    url: json-schema/sap-business-partner-schema.json\n  - type: JSONSchema\n    url: json-schema/sap-sales-order-schema.json\n  - type: Rules\n    url: rules/sap-spectral-rules.yml\n  - type: Capabilities\n    url: capabilities/shared/ai-core.yaml\n  - type: Capabilities\n    url: capabilities/shared/business-one.yaml\n  - type: Capabilities\n    url: capabilities/shared/s4hana-business-partner.yaml\n  - type: Capabilities\n    url: capabilities/enterprise-business-operations.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap/refs/heads/main/apis.yml
tags:
- AI
- BTP
- Business Applications
- Cloud
- Data Management
- Enterprise
- ERP
- Integration
url: https://api.sap.com
use_cases:
- Automating order-to-cash and procure-to-pay business processes
- Deploying and serving AI models for intelligent enterprise workflows
- Integrating SAP ERP with third-party CRM, e-commerce, and analytics platforms
- Managing business partner master data across multi-system landscapes
- Building digital workplace experiences with unified work zone portals
---
