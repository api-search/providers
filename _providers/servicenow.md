---
api_count: 57
api_specs:
- filename: servicenow-table-api-openapi.yml
  format: yaml
  label: ServiceNow Table API
  slug: servicenow-table-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-table-api-openapi.yml
- filename: servicenow-aggregate-api-openapi.yml
  format: yaml
  label: ServiceNow Aggregate API
  slug: servicenow-aggregate-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-aggregate-api-openapi.yml
- filename: servicenow-attachment-api-openapi.yml
  format: yaml
  label: ServiceNow Attachment API
  slug: servicenow-attachment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-attachment-api-openapi.yml
- filename: servicenow-import-set-api-openapi.yml
  format: yaml
  label: ServiceNow Import Set API
  slug: servicenow-import-set-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-import-set-api-openapi.yml
- filename: servicenow-change-management-api-openapi.yml
  format: yaml
  label: ServiceNow Change Management API
  slug: servicenow-change-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-change-management-api-openapi.yml
- filename: servicenow-service-catalog-api-openapi.yml
  format: yaml
  label: ServiceNow Service Catalog API
  slug: servicenow-service-catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-service-catalog-api-openapi.yml
- filename: servicenow-cmdb-instance-api-openapi.yml
  format: yaml
  label: ServiceNow CMDB Instance API
  slug: servicenow-cmdb-instance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-cmdb-instance-api-openapi.yml
- filename: contact-api-openapi.yaml
  format: yaml
  label: ServiceNow Contact API
  slug: servicenow-contact-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/contact-api-openapi.yaml
- filename: trouble-ticket-openapi.yaml
  format: yaml
  label: ServiceNow Trouble Ticket Open API
  slug: servicenow-trouble-ticket-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/trouble-ticket-openapi.yaml
- filename: servicenow-events-asyncapi.yml
  format: yaml
  label: ServiceNow Event Management Topic Open API
  slug: servicenow-event-management-topic-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/asyncapi/servicenow-events-asyncapi.yml
apis:
- description: 'The ServiceNow Table API provides endpoints to perform create, read, update, and delete (CRUD) operations on records within any ServiceNow table. It is the primary REST interface for interacting with '
  name: ServiceNow Table API
  slug: servicenow-table-api
- description: The ServiceNow Aggregate API provides endpoints to compute aggregate statistics (count, average, min, max, sum) against records in any ServiceNow table. It supports grouping and filtering results, mak
  name: ServiceNow Aggregate API
  slug: servicenow-aggregate-api
- description: The ServiceNow Attachment API enables uploading, retrieving, and deleting file attachments associated with records in ServiceNow tables. It supports uploading files via multipart/form-data or binary s
  name: ServiceNow Attachment API
  slug: servicenow-attachment-api
- description: The ServiceNow Import Set API allows external systems to push data into ServiceNow import set tables, which can then be synchronously or asynchronously transformed and loaded into target tables. It is
  name: ServiceNow Import Set API
  slug: servicenow-import-set-api
- description: The ServiceNow Batch API enables sending multiple REST API requests in a single HTTP call, reducing network overhead and improving integration performance. Each request in the batch is executed indepe
  name: ServiceNow Batch API
  slug: servicenow-batch-api
- description: The ServiceNow Change Management API provides REST endpoints for creating, retrieving, updating, and managing change requests and their associated tasks and approvals. It supports the full change life
  name: ServiceNow Change Management API
  slug: servicenow-change-management-api
- description: The ServiceNow Knowledge Management REST API provides endpoints for searching and retrieving knowledge articles, including most-viewed and featured articles. It supports public and authenticated acces
  name: ServiceNow Knowledge Management API
  slug: servicenow-knowledge-management-api
- description: The ServiceNow Service Catalog API provides REST endpoints for browsing catalog categories and items, retrieving catalog item details and variables, and submitting catalog requests. It enables externa
  name: ServiceNow Service Catalog API
  slug: servicenow-service-catalog-api
- description: The ServiceNow CMDB Instance API provides REST endpoints for retrieving configuration item (CI) records from the Configuration Management Database by class name and sys_id. It is used to query and acc
  name: ServiceNow CMDB Instance API
  slug: servicenow-cmdb-instance-api
- description: The ServiceNow Identification and Reconciliation API provides a REST endpoint for creating or updating configuration items (CIs) in the CMDB using the platform's identification and reconciliation engi
  name: ServiceNow Identification and Reconciliation API
  slug: servicenow-identification-reconciliation-api
- description: The ServiceNow Performance Analytics API provides REST endpoints for retrieving performance analytics data including scores, breakdowns, and widget data. It enables integration with external dashboard
  name: ServiceNow Performance Analytics API
  slug: servicenow-performance-analytics-api
- description: 'The ServiceNow Contact API provides endpoints for retrieving and updating Customer Service Management (CSM) contact records. It also supports generating new social media profile records when creating '
  name: ServiceNow Contact API
  slug: servicenow-contact-api
- description: The ServiceNow Trouble Ticket Open API provides endpoints to create, update, and retrieve data from Case, Incident, and Service Problem Case tables. It is a ServiceNow implementation of the TM Forum T
  name: ServiceNow Trouble Ticket Open API
  slug: servicenow-trouble-ticket-api
- description: ServiceNow Scripted REST APIs allow developers to create custom REST API endpoints on the Now Platform using server-side JavaScript. They support custom request processing logic, authentication, and r
  name: ServiceNow Scripted REST APIs
  slug: servicenow-scripted-rest-apis
- description: The ServiceNow GraphQL API framework allows developers to create custom GraphQL API schemas on the Now Platform for querying record data from components or external systems. It supports defining resol
  name: ServiceNow GraphQL API
  slug: servicenow-graphql-api
- description: The ServiceNow Application Service API provides REST endpoints to create, modify, and update application services in the CMDB. It requires users to have the app_service_admin role and enables programm
  name: ServiceNow Application Service API
  slug: servicenow-application-service-api
- description: The ServiceNow Case API provides REST endpoints for creating, retrieving, and updating Customer Service Management (CSM) case records. It supports the full case lifecycle including case creation, assi
  name: ServiceNow Case API
  slug: servicenow-case-api
- description: The ServiceNow Account API provides REST endpoints for retrieving and managing customer account records within Customer Service Management (CSM). It enables external systems to query and update accoun
  name: ServiceNow Account API
  slug: servicenow-account-api
- description: The ServiceNow Consumer API provides REST endpoints for retrieving and updating CSM consumer records. It supports managing individual consumer profiles and can generate new social media profile record
  name: ServiceNow Consumer API
  slug: servicenow-consumer-api
- description: The ServiceNow CSM Attachment API provides REST endpoints for uploading and managing file attachments on Customer Service Management records such as cases and interactions. It extends the base Attachm
  name: ServiceNow CSM Attachment API
  slug: servicenow-csm-attachment-api
- description: The ServiceNow Email API provides REST endpoints for sending email messages from the Now Platform. It allows external systems and integrations to trigger email notifications and communications through
  name: ServiceNow Email API
  slug: servicenow-email-api
- description: The ServiceNow CI/CD API provides REST endpoints for integrating ServiceNow application development with continuous integration and continuous delivery pipelines. It supports operations such as applyi
  name: ServiceNow CI/CD API
  slug: servicenow-cicd-api
- description: The ServiceNow CI/CD Update Set API provides REST methods to create, retrieve, preview, commit, and back out update sets. It enables automated deployment workflows by allowing CI/CD pipelines to manag
  name: ServiceNow CI/CD Update Set API
  slug: servicenow-cicd-update-set-api
- description: The ServiceNow DevOps API provides REST endpoints for integrating external DevOps toolchains with ServiceNow's DevOps Change Velocity product. It enables automated change request creation, artifact an
  name: ServiceNow DevOps API
  slug: servicenow-devops-api
- description: The ServiceNow DevOps Config API provides REST endpoints for managing DevOps configuration data and policies. It supports configuration validation and compliance checks as part of the DevOps change ac
  name: ServiceNow DevOps Config API
  slug: servicenow-devops-config-api
- description: The ServiceNow CMDB Meta API provides REST endpoints for retrieving metadata about CMDB classes, including their attributes, relationships, and hierarchy. It enables developers to programmatically dis
  name: ServiceNow CMDB Meta API
  slug: servicenow-cmdb-meta-api
- description: The ServiceNow CMDB Data Ingestion API provides REST endpoints for bulk ingesting configuration item data into the CMDB from external data sources. It supports high-volume CI data loading with built-i
  name: ServiceNow CMDB Data Ingestion API
  slug: servicenow-cmdb-data-ingestion-api
- description: The ServiceNow MetricBase Time Series API (formerly Clotho) provides REST endpoints for storing, retrieving, and transforming time series metric data on the Now Platform. It is used by IT Operations M
  name: ServiceNow MetricBase Time Series API
  slug: servicenow-metricbase-time-series-api
- description: The ServiceNow Interaction Management API provides REST endpoints for creating and managing customer interactions across multiple channels. It supports omnichannel routing and enables external contact
  name: ServiceNow Interaction Management API
  slug: servicenow-interaction-management-api
- description: The ServiceNow Voice Interaction Resource API provides REST endpoints for integrating telephony and voice systems with ServiceNow. It enables Contact Center as a Service (CCaaS) providers to manage vo
  name: ServiceNow Voice Interaction Resource API
  slug: servicenow-voice-interaction-resource-api
- description: The ServiceNow User Role Inheritance API provides REST endpoints for querying the role inheritance hierarchy for users and groups. It enables external systems to determine effective roles and permissi
  name: ServiceNow User Role Inheritance API
  slug: servicenow-user-role-inheritance-api
- description: The ServiceNow HR API provides REST endpoints for managing Human Resources Service Delivery (HRSD) data including employee cases, lifecycle events, and HR service requests. It enables integration with
  name: ServiceNow HR API
  slug: servicenow-hr-api
- description: The ServiceNow Event Management Topic Open API provides REST endpoints for managing event topics and subscriptions within IT Operations Management. It enables external monitoring tools to publish even
  name: ServiceNow Event Management Topic Open API
  slug: servicenow-event-management-topic-api
- description: The ServiceNow Predictive Intelligence API provides REST endpoints for accessing machine learning prediction models on the Now Platform. It supports classification, similarity matching, and regression
  name: ServiceNow Predictive Intelligence API
  slug: servicenow-predictive-intelligence-api
- description: The ServiceNow AWA Agent API provides REST endpoints for managing agent availability, presence, and capacity within Advanced Work Assignment (AWA). It enables external systems to query and update agen
  name: ServiceNow AWA Agent API
  slug: servicenow-awa-agent-api
- description: 'The ServiceNow AWA Offer Work API provides REST endpoints to assign or transfer work items to agents through the Advanced Work Assignment engine. It enables programmatic distribution of tasks, cases, '
  name: ServiceNow AWA Offer Work API
  slug: servicenow-awa-offer-work-api
- description: The ServiceNow Virtual Agent Bot Integration API provides REST endpoints for integrating external messaging platforms and chatbot frameworks with ServiceNow Virtual Agent. It enables sending and recei
  name: ServiceNow Virtual Agent Bot Integration API
  slug: servicenow-virtual-agent-bot-integration-api
- description: The ServiceNow Openframe API provides REST endpoints that enable Contact Center as a Service (CCaaS) providers to create and update interaction records without using the Operation Handler. It supports
  name: ServiceNow Openframe API
  slug: servicenow-openframe-api
- description: The ServiceNow AI Assets API provides REST endpoints to retrieve, update, and create AI assets such as systems, data sets, prompts, and models. It supports AI governance and inventory management by en
  name: ServiceNow AI Assets API
  slug: servicenow-ai-assets-api
- description: 'The ServiceNow Lead API provides REST endpoints to create, update, and retrieve marketing leads and their associated lead line items. It enables integration with external marketing automation and CRM '
  name: ServiceNow Lead API
  slug: servicenow-lead-api
- description: The ServiceNow Sales Agreement API provides REST methods for creating new sales agreements and retrieving existing sales agreements by sys_id. It supports contract management workflows within ServiceN
  name: ServiceNow Sales Agreement API
  slug: servicenow-sales-agreement-api
- description: The ServiceNow Agent Client Collector (ACC) API provides REST endpoints for managing agent client collectors used in IT Operations Management. It enables programmatic interaction with ACC agents for d
  name: ServiceNow Agent Client Collector API
  slug: servicenow-agent-client-collector-api
- description: The ServiceNow Agent Mapping API provides REST endpoints for managing agent mapping configurations. It enables external systems to create and manage mappings between external agent identifiers and Ser
  name: ServiceNow Agent Mapping API
  slug: servicenow-agent-mapping-api
- description: The ServiceNow Automation Center API provides REST endpoints for managing and executing automation workflows on the Now Platform. It supports programmatic control of automation tasks, enabling externa
  name: ServiceNow Automation Center API
  slug: servicenow-automation-center-api
- description: The ServiceNow AP Invoice API provides REST endpoints for managing accounts payable invoice records on the Now Platform. It enables external financial systems to create, retrieve, and update invoice d
  name: ServiceNow AP Invoice API
  slug: servicenow-ap-invoice-api
- description: The ServiceNow CSM Order API provides REST endpoints for managing order records within Customer Service Management. It enables external systems to create, retrieve, and update customer orders and asso
  name: ServiceNow CSM Order API
  slug: servicenow-csm-order-api
- description: The ServiceNow CI Lifecycle Management API provides REST endpoints for managing the lifecycle states of configuration items (CIs) in the CMDB. It enables programmatic tracking and transition of CI sta
  name: ServiceNow CI Lifecycle Management API
  slug: servicenow-ci-lifecycle-management-api
- description: The ServiceNow Alarm Management Open API provides REST endpoints for managing alarm records within IT Operations Management. It supports creating, retrieving, and updating alarm data from external mon
  name: ServiceNow Alarm Management Open API
  slug: servicenow-alarm-management-open-api
- description: The ServiceNow SAM Software Usage Data Integration API provides REST endpoints for importing software usage and metering data into Software Asset Management. It enables third-party software usage trac
  name: ServiceNow SAM Software Usage Data Integration API
  slug: servicenow-sam-software-usage-api
- description: The ServiceNow Product Catalog Open API provides REST endpoints for managing product catalog data based on the TM Forum TMF620 specification. It enables querying and managing product specifications, o
  name: ServiceNow Product Catalog Open API
  slug: servicenow-product-catalog-open-api
- description: The ServiceNow Service Catalog Open API provides REST endpoints for managing service catalog data based on the TM Forum TMF633 specification. It supports querying and managing service specifications a
  name: ServiceNow Service Catalog Open API
  slug: servicenow-service-catalog-open-api
- description: The ServiceNow Product Order Open API provides REST endpoints for managing product orders based on the TM Forum TMF622 specification. It enables creating, retrieving, and updating product orders for t
  name: ServiceNow Product Order Open API
  slug: servicenow-product-order-open-api
- description: The ServiceNow Service Order Open API provides REST endpoints for managing service orders based on the TM Forum TMF641 specification. It enables creating, retrieving, and updating service orders for t
  name: ServiceNow Service Order Open API
  slug: servicenow-service-order-open-api
- description: The ServiceNow Resource Inventory Open API provides REST endpoints for managing resource inventory data based on TM Forum specifications. It supports querying and managing physical and logical resourc
  name: ServiceNow Resource Inventory Open API
  slug: servicenow-resource-inventory-open-api
- description: The ServiceNow Product Inventory Open API provides REST endpoints for managing product inventory data based on TM Forum specifications. It supports querying and managing product instances and their li
  name: ServiceNow Product Inventory Open API
  slug: servicenow-product-inventory-open-api
- description: The ServiceNow Service Test Management Open API provides REST endpoints for managing service test records based on TM Forum specifications. It supports creating and managing service test definitions a
  name: ServiceNow Service Test Management Open API
  slug: servicenow-service-test-management-open-api
- description: The ServiceNow Project Portfolio Management API provides REST endpoints for managing projects, demands, and resource plans within Strategic Portfolio Management (SPM). It enables external systems to c
  name: ServiceNow Project Portfolio Management API
  slug: servicenow-project-portfolio-management-api
asyncapis:
- description: ServiceNow supports outbound event-driven integrations through business rules, event management, and outbound REST messages. When records are created, updated, or deleted in ServiceNow tables, busines
  name: ServiceNow Events and Notifications
  slug: servicenow-events-asyncapi
capabilities:
- description: Unified workflow for customer service operations combining contact management, service catalog browsing and ordering, and trouble ticket handling. Used by customer service agents and self-service port
  name: ServiceNow Customer Service
  slug: customer-service
- description: Unified workflow for data integration and configuration management combining import sets for ETL, CMDB for configuration items, and attachment management. Used by integration engineers and CMDB admini
  name: ServiceNow Data Integration And Configuration
  slug: data-integration-and-configuration
- description: Unified workflow for IT Service Management operations combining table records, aggregate analytics, change management, and trouble tickets. Used by ITSM administrators and service desk agents to manag
  name: ServiceNow ITSM Operations
  slug: itsm-operations
common:
- title: ''
  type: JSONLD
  url: json-ld/servicenow-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/servicenow-incident-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/servicenow-change-request-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/servicenow-configuration-item-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/servicenow-catalog-request-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/servicenow-user-schema.json
- title: ''
  type: Website
  url: https://www.servicenow.com/
- title: ''
  type: Portal
  url: https://developer.servicenow.com
- title: ''
  type: Blog
  url: https://www.servicenow.com/community/developer-blog/bg-p/developer-blog
- title: ''
  type: Events
  url: https://www.servicenow.com/community/events/ct-p/TopLevel_Events
- title: ''
  type: Forums
  url: https://www.servicenow.com/community/developer-forum/bd-p/developer-forum
- title: ''
  type: Community
  url: https://www.servicenow.com/community/
- title: ''
  type: Documentation
  url: https://www.servicenow.com/docs/
- title: ''
  type: APIReference
  url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html
- title: ''
  type: GettingStarted
  url: https://developer.servicenow.com/dev.do#!/learn/learning-plans/tokyo/new_to_servicenow/app_store_learnv2_rest_tokyo_rest_api_explorer
- title: ''
  type: Authentication
  url: https://www.servicenow.com/docs/bundle/yokohama-platform-security/page/administer/security/concept/c_OAuthApplications.html
- title: ''
  type: RateLimits
  url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html
- title: ''
  type: StatusPage
  url: https://status.servicenow.com
- title: ''
  type: Support
  url: https://support.servicenow.com
- title: ''
  type: Pricing
  url: https://www.servicenow.com/products/pricing.html
- title: ''
  type: TermsOfService
  url: https://www.servicenow.com/terms-of-use.html
- title: ''
  type: PrivacyPolicy
  url: https://www.servicenow.com/privacy-statement.html
- title: ''
  type: ChangeLog
  url: https://www.servicenow.com/docs/bundle/yokohama-release-notes/page/release-notes/family-release-notes.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/ServiceNow
- title: ''
  type: GitHubOrganization
  url: https://github.com/ServiceNowDevProgram
- title: ''
  type: GitHubRepository
  url: https://github.com/ServiceNow/sdk
- title: ''
  type: SDK
  url: https://www.npmjs.com/package/@servicenow/sdk
- title: ''
  type: Documentation
  url: https://www.servicenow.com/docs/bundle/yokohama-application-development/page/build/servicenow-sdk/concept/servicenow-sdk-landing.html
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/servicenow
- title: ''
  type: SignUp
  url: https://developer.servicenow.com/dev.do
- title: ''
  type: Login
  url: https://developer.servicenow.com/dev.do
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/serviceaborad
- title: ''
  type: RateLimits
  url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/inbound-REST-API-rate-limiting.html
- title: ''
  type: Documentation
  url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/use-REST-API-Explorer.html
- title: ''
  type: Documentation
  url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/task/export-openapi-specification.html
- title: ''
  type: GitHubRepository
  url: https://github.com/ServiceNow/PySNC
- title: ''
  type: SDK
  url: https://pypi.org/project/pysnc/
- title: ''
  type: Documentation
  url: https://servicenow.github.io/PySNC/
- title: ''
  type: Authentication
  url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/task/t_EnableOAuthWithREST.html
- title: ''
  type: X
  url: https://x.com/ServiceNow
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/servicenow
- title: ''
  type: GettingStarted
  url: https://www.servicenow.com/university/training-and-certification.html
- title: ''
  type: Documentation
  url: https://www.servicenow.com/products/api-integrations.html
- title: ''
  type: APIReference
  url: https://developer.servicenow.com/dev.do#!/reference/api/yokohama/rest/
- title: ''
  type: JSONLD
  url: json-ld/contact-context.jsonld
- title: ''
  type: JSONLD
  url: json-ld/servicenow-aggregate-context.jsonld
- title: ''
  type: JSONLD
  url: json-ld/servicenow-attachment-context.jsonld
- title: ''
  type: JSONLD
  url: json-ld/servicenow-change-management-context.jsonld
- title: ''
  type: JSONLD
  url: json-ld/servicenow-cmdb-instance-context.jsonld
- title: ''
  type: JSONLD
  url: json-ld/servicenow-import-set-context.jsonld
- title: ''
  type: JSONLD
  url: json-ld/servicenow-service-catalog-context.jsonld
- title: ''
  type: JSONLD
  url: json-ld/servicenow-table-context.jsonld
- title: ''
  type: JSONLD
  url: json-ld/trouble-ticket-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/servicenow-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/servicenow-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/itsm-operations.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/customer-service.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-integration-and-configuration.yaml
created: '2025-01-08'
description: ServiceNow provides cloud-based platform services that automate enterprise IT operations.
features:
- description: Universal Table API for CRUD operations on any ServiceNow table including incidents, changes, and custom tables.
  name: Table-Driven Architecture
- description: Complete ITSM capabilities with dedicated APIs for incident, change, problem, and knowledge management.
  name: IT Service Management
- description: CMDB APIs for managing configuration items, relationships, and service mappings with identification and reconciliation.
  name: Configuration Management Database
- description: Service Catalog APIs for browsing items, submitting requests, and managing cart operations.
  name: Service Catalog And Self-Service
- description: CSM APIs for cases, contacts, accounts, and consumer management with omnichannel routing.
  name: Customer Service Management
- description: AWA APIs for intelligent work routing, agent management, and capacity-based assignment.
  name: Advanced Work Assignment
- description: Bot Integration APIs for connecting external messaging platforms with ServiceNow conversational AI.
  name: Virtual Agent Integration
- description: CI/CD and DevOps APIs for automated application deployment, testing, and change velocity management.
  name: CI/CD And DevOps
- description: Event Management APIs for ingesting alerts and events from external monitoring systems.
  name: Event Management
- description: ML-powered APIs for automated classification, assignment, and prioritization of records.
  name: Predictive Intelligence
image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg
integrations:
- description: Bidirectional synchronization of incidents and issues between ServiceNow and Atlassian Jira.
  name: Jira
- description: Virtual Agent and notification integration for managing IT requests directly from Microsoft Teams.
  name: Microsoft Teams
- description: Conversational IT support and incident management through Slack channel integrations.
  name: Slack
- description: CI/CD pipeline integration for automated change request creation and deployment tracking.
  name: Jenkins
- description: DevOps pipeline integration for change velocity and automated deployment workflows.
  name: Azure DevOps
- description: Event and alert ingestion from Splunk for centralized IT operations monitoring.
  name: Splunk
- description: Incident alerting and on-call management integration for streamlined incident response.
  name: PagerDuty
- description: Cloud resource discovery and CMDB synchronization for AWS infrastructure management.
  name: AWS
jsonld:
- class_count: 0
  name: Contact Context
  property_count: 3
  slug: contact-context
- class_count: 0
  name: Servicenow Aggregate Context
  property_count: 2
  slug: servicenow-aggregate-context
- class_count: 0
  name: Servicenow Attachment Context
  property_count: 2
  slug: servicenow-attachment-context
- class_count: 0
  name: Servicenow Change Management Context
  property_count: 5
  slug: servicenow-change-management-context
- class_count: 0
  name: Servicenow Cmdb Instance Context
  property_count: 3
  slug: servicenow-cmdb-instance-context
- class_count: 7
  name: Servicenow Context
  property_count: 8
  slug: servicenow-context
- class_count: 0
  name: Servicenow Import Set Context
  property_count: 2
  slug: servicenow-import-set-context
- class_count: 0
  name: Servicenow Service Catalog Context
  property_count: 10
  slug: servicenow-service-catalog-context
- class_count: 0
  name: Servicenow Table Context
  property_count: 2
  slug: servicenow-table-context
- class_count: 0
  name: Trouble Ticket Context
  property_count: 12
  slug: trouble-ticket-context
layout: provider
modified: '2026-04-18'
name: ServiceNow
rules:
- name: ServiceNow API Rules
  rule_count: 21
  severity_counts:
    error: 19
    hint: 0
    info: 1
    warn: 1
  slug: servicenow-spectral-rules
skills: []
slug: servicenow
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: servicenow\nurl: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/apis.yml\napis:\n  - aid: servicenow:servicenow-table-api\n    name: ServiceNow Table API\n    tags:\n      - CRUD\n      - Data\n      - ITSM\n      - Records\n      - Tables\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_TableAPI.html\n    baseURL: https://{instance}.service-now.com/api/now/table\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_TableAPI.html\n        type: Documentation\n      - url: https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/c_TableAPI.html\n        type: APIReference\n      - url: openapi/servicenow-table-api-openapi.yml\n        type: OpenAPI\n    description:\
  \ The ServiceNow Table API provides endpoints to perform create, read, update, and delete (CRUD) operations on records within any ServiceNow table. It is the primary REST interface for interacting with ServiceNow platform data such as incidents, problems, changes, and custom tables.\n  - aid: servicenow:servicenow-aggregate-api\n    name: ServiceNow Aggregate API\n    tags:\n      - Aggregation\n      - Analytics\n      - Reporting\n      - Statistics\n      - Tables\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AggregateAPI.html\n    baseURL: https://{instance}.service-now.com/api/now/stats\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AggregateAPI.html\n        type: Documentation\n      - url: openapi/servicenow-aggregate-api-openapi.yml\n\
  \        type: OpenAPI\n    description: The ServiceNow Aggregate API provides endpoints to compute aggregate statistics (count, average, min, max, sum) against records in any ServiceNow table. It supports grouping and filtering results, making it useful for reporting and dashboard data retrieval.\n  - aid: servicenow:servicenow-attachment-api\n    name: ServiceNow Attachment API\n    tags:\n      - Attachments\n      - Files\n      - Records\n      - Upload\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AttachmentAPI.html\n    baseURL: https://{instance}.service-now.com/api/now/attachment\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AttachmentAPI.html\n        type: Documentation\n      - url: openapi/servicenow-attachment-api-openapi.yml\n\
  \        type: OpenAPI\n    description: The ServiceNow Attachment API enables uploading, retrieving, and deleting file attachments associated with records in ServiceNow tables. It supports uploading files via multipart/form-data or binary streams and allows up to 1024 MB file size by default.\n  - aid: servicenow:servicenow-import-set-api\n    name: ServiceNow Import Set API\n    tags:\n      - Data Loading\n      - ETL\n      - Import\n      - Integration\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ImportSetAPI.html\n    baseURL: https://{instance}.service-now.com/api/now/import\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ImportSetAPI.html\n        type: Documentation\n      - url: openapi/servicenow-import-set-api-openapi.yml\n\
  \        type: OpenAPI\n    description: The ServiceNow Import Set API allows external systems to push data into ServiceNow import set tables, which can then be synchronously or asynchronously transformed and loaded into target tables. It is commonly used for integrating external data sources with ServiceNow using transform maps.\n  - aid: servicenow:servicenow-batch-api\n    name: ServiceNow Batch API\n    tags:\n      - Batch\n      - Integration\n      - Performance\n      - REST\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/batch-api.html\n    baseURL: https://{instance}.service-now.com/api/now/v1/batch\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/batch-api.html\n        type: Documentation\n    description: The ServiceNow Batch API\
  \ enables sending multiple REST API requests in a single HTTP call, reducing network overhead and improving integration performance. Each request in the batch is executed independently, and the API returns a stream of corresponding responses.\n  - aid: servicenow:servicenow-change-management-api\n    name: ServiceNow Change Management API\n    tags:\n      - Change Management\n      - IT Operations\n      - ITSM\n      - Workflows\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/change-management-api.html\n    baseURL: https://{instance}.service-now.com/api/sn_chg_rest/v1/change\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/change-management-api.html\n        type: Documentation\n      - url: https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/change-management-api.html\n\
  \        type: APIReference\n      - url: openapi/servicenow-change-management-api-openapi.yml\n        type: OpenAPI\n    description: The ServiceNow Change Management API provides REST endpoints for creating, retrieving, updating, and managing change requests and their associated tasks and approvals. It supports the full change lifecycle including normal, standard, and emergency change types.\n  - aid: servicenow:servicenow-knowledge-management-api\n    name: ServiceNow Knowledge Management API\n    tags:\n      - Articles\n      - Knowledge Base\n      - Knowledge Management\n      - Self-Service\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/knowledge-api.html\n    baseURL: https://{instance}.service-now.com/api/sn_km_api/knowledge\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/knowledge-api.html\n\
  \        type: Documentation\n      - url: https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/knowledge-api.html\n        type: APIReference\n    description: The ServiceNow Knowledge Management REST API provides endpoints for searching and retrieving knowledge articles, including most-viewed and featured articles. It supports public and authenticated access to knowledge bases and requires the Knowledge API (sn_km_api) plugin to be activated.\n  - aid: servicenow:servicenow-service-catalog-api\n    name: ServiceNow Service Catalog API\n    tags:\n      - ITSM\n      - Requests\n      - Self-Service\n      - Service Catalog\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ServiceCatalogAPI.html\n    baseURL: https://{instance}.service-now.com/api/sn_sc/servicecatalog\n    properties:\n\
  \      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ServiceCatalogAPI.html\n        type: Documentation\n      - url: https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/c_ServiceCatalogAPI.html\n        type: APIReference\n      - url: openapi/servicenow-service-catalog-api-openapi.yml\n        type: OpenAPI\n    description: The ServiceNow Service Catalog API provides REST endpoints for browsing catalog categories and items, retrieving catalog item details and variables, and submitting catalog requests. It enables external applications and portals to integrate with ServiceNow's self-service request capabilities.\n  - aid: servicenow:servicenow-cmdb-instance-api\n    name: ServiceNow CMDB Instance API\n    tags:\n      - Assets\n      - CMDB\n      - Configuration Management\n      - IT Operations\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n\
  \    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-instance-api.html\n    baseURL: https://{instance}.service-now.com/api/now/cmdb/instance\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-instance-api.html\n        type: Documentation\n      - url: https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/cmdb-instance-api.html\n        type: APIReference\n      - url: openapi/servicenow-cmdb-instance-api-openapi.yml\n        type: OpenAPI\n    description: The ServiceNow CMDB Instance API provides REST endpoints for retrieving configuration item (CI) records from the Configuration Management Database by class name and sys_id. It is used to query and access infrastructure and application CI data stored in ServiceNow's CMDB.\n  - aid: servicenow:servicenow-identification-reconciliation-api\n    name:\
  \ ServiceNow Identification and Reconciliation API\n    tags:\n      - CMDB\n      - Configuration Management\n      - Discovery\n      - Reconciliation\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_IdentifyReconcileAPI.html\n    baseURL: https://{instance}.service-now.com/api/now/identifyreconcile\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_IdentifyReconcileAPI.html\n        type: Documentation\n      - url: https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/c_IdentifyReconcileAPI.html\n        type: APIReference\n    description: The ServiceNow Identification and Reconciliation API provides a REST endpoint for creating or updating configuration items (CIs) in the CMDB using the platform's\
  \ identification and reconciliation engine. It ensures that CI data from external discovery sources is correctly identified, deduplicated, and reconciled against existing CMDB records.\n  - aid: servicenow:servicenow-performance-analytics-api\n    name: ServiceNow Performance Analytics API\n    tags:\n      - Analytics\n      - Dashboards\n      - Performance\n      - Reporting\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_PerformanceAnalyticsAPI.html\n    baseURL: https://{instance}.service-now.com/api/now/pa\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_PerformanceAnalyticsAPI.html\n        type: Documentation\n    description: The ServiceNow Performance Analytics API provides REST endpoints for retrieving performance analytics data\
  \ including scores, breakdowns, and widget data. It enables integration with external dashboards and reporting tools to access historical and real-time KPI data collected by the Now Platform.\n  - aid: servicenow:servicenow-contact-api\n    name: ServiceNow Contact API\n    tags:\n      - Contacts\n      - CSM\n      - Customer Service\n      - Records\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/r/xanadu/api-reference/rest-apis/contact-api.html\n    baseURL: https://{instance}.service-now.com/api/now/contact\n    properties:\n      - url: https://www.servicenow.com/docs/r/xanadu/api-reference/rest-apis/contact-api.html\n        type: Documentation\n      - url: openapi/contact-api-openapi.yaml\n        type: OpenAPI\n    description: The ServiceNow Contact API provides endpoints for retrieving and updating Customer Service Management (CSM) contact records. It also supports generating\
  \ new social media profile records when creating a contact, and requires the Customer Service plugin (com.sn_customerservice).\n  - aid: servicenow:servicenow-trouble-ticket-api\n    name: ServiceNow Trouble Ticket Open API\n    tags:\n      - Customer Service\n      - Incidents\n      - TM Forum\n      - Trouble Tickets\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html\n    baseURL: https://{instance}.service-now.com/api/now/troubleticket\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html\n        type: Documentation\n      - url: openapi/trouble-ticket-openapi.yaml\n        type: OpenAPI\n    description: The ServiceNow Trouble Ticket Open API provides endpoints to create, update, and retrieve data from Case, Incident,\
  \ and Service Problem Case tables. It is a ServiceNow implementation of the TM Forum Trouble Ticket Management API REST specification for managing ticket information between external ticketing systems and the ServiceNow AI Platform.\n  - aid: servicenow:servicenow-scripted-rest-apis\n    name: ServiceNow Scripted REST APIs\n    tags:\n      - Custom APIs\n      - Integration\n      - Platform\n      - Scripting\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/custom-web-services/concept/c_CustomWebServices.html\n    baseURL: https://{instance}.service-now.com/api/{namespace}/{api_id}\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/custom-web-services/concept/c_CustomWebServices.html\n        type: Documentation\n    description: ServiceNow Scripted REST APIs allow developers to create\
  \ custom REST API endpoints on the Now Platform using server-side JavaScript. They support custom request processing logic, authentication, and response handling, enabling organizations to expose business-specific functionality as web services to external consumers.\n  - aid: servicenow:servicenow-graphql-api\n    name: ServiceNow GraphQL API\n    tags:\n      - Custom APIs\n      - GraphQL\n      - Integration\n      - Platform\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://docs.servicenow.com/bundle/tokyo-application-development/page/integrate/graphql/concept/scripted-graph-ql.html\n    baseURL: https://{instance}.service-now.com/api/now/graphql\n    properties:\n      - url: https://docs.servicenow.com/bundle/tokyo-application-development/page/integrate/graphql/concept/scripted-graph-ql.html\n        type: Documentation\n      - url: https://www.servicenow.com/community/developer-articles/getting-started-graphql-api-framework/ta-p/2312207\n\
  \        type: GettingStarted\n    description: The ServiceNow GraphQL API framework allows developers to create custom GraphQL API schemas on the Now Platform for querying record data from components or external systems. It supports defining resolvers with server-side scripts and enables flexible, client-driven queries as an alternative to REST-based integration.\n  - aid: servicenow:servicenow-application-service-api\n    name: ServiceNow Application Service API\n    tags:\n      - Application Services\n      - CMDB\n      - IT Operations\n      - Service Mapping\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/application-service-api.html\n    baseURL: https://{instance}.service-now.com/api/now/cmdb/app_service\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/application-service-api.html\n\
  \        type: Documentation\n    description: The ServiceNow Application Service API provides REST endpoints to create, modify, and update application services in the CMDB. It requires users to have the app_service_admin role and enables programmatic management of business application service mappings and their associated configuration items.\n  - aid: servicenow:servicenow-case-api\n    name: ServiceNow Case API\n    tags:\n      - Cases\n      - CSM\n      - Customer Service\n      - Support\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/case-api.html\n    baseURL: https://{instance}.service-now.com/api/sn_customerservice/case\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/case-api.html\n        type: Documentation\n    description: The\
  \ ServiceNow Case API provides REST endpoints for creating, retrieving, and updating Customer Service Management (CSM) case records. It supports the full case lifecycle including case creation, assignment, escalation, and resolution within the CSM application.\n  - aid: servicenow:servicenow-account-api\n    name: ServiceNow Account API\n    tags:\n      - Accounts\n      - CSM\n      - Customer Service\n      - Records\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/account-api.html\n    baseURL: https://{instance}.service-now.com/api/now/account\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/account-api.html\n        type: Documentation\n    description: The ServiceNow Account API provides REST endpoints for retrieving and managing customer\
  \ account records within Customer Service Management (CSM). It enables external systems to query and update account information used for B2B customer relationship tracking.\n  - aid: servicenow:servicenow-consumer-api\n    name: ServiceNow Consumer API\n    tags:\n      - Consumers\n      - CSM\n      - Customer Service\n      - Self-Service\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html\n    baseURL: https://{instance}.service-now.com/api/now/consumer\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html\n        type: Documentation\n    description: The ServiceNow Consumer API provides REST endpoints for retrieving and updating CSM consumer records. It supports managing individual consumer profiles and can generate\
  \ new social media profile records when creating a consumer entry within the Customer Service Management application.\n  - aid: servicenow:servicenow-csm-attachment-api\n    name: ServiceNow CSM Attachment API\n    tags:\n      - Attachments\n      - CSM\n      - Customer Service\n      - Files\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/attachment_csm-api.html\n    baseURL: https://{instance}.service-now.com/api/sn_customerservice/attachment\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/attachment_csm-api.html\n        type: Documentation\n    description: The ServiceNow CSM Attachment API provides REST endpoints for uploading and managing file attachments on Customer Service Management records such as cases and interactions. It extends\
  \ the base Attachment API with CSM-specific functionality and access controls.\n  - aid: servicenow:servicenow-email-api\n    name: ServiceNow Email API\n    tags:\n      - Email\n      - Messaging\n      - Notifications\n      - Platform\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/email-api.html\n    baseURL: https://{instance}.service-now.com/api/now/email\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/email-api.html\n        type: Documentation\n    description: The ServiceNow Email API provides REST endpoints for sending email messages from the Now Platform. It allows external systems and integrations to trigger email notifications and communications through ServiceNow's email infrastructure.\n  - aid: servicenow:servicenow-cicd-api\n\
  \    name: ServiceNow CI/CD API\n    tags:\n      - Automation\n      - CI/CD\n      - Deployment\n      - DevOps\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-api.html\n    baseURL: https://{instance}.service-now.com/api/sn_cicd\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-api.html\n        type: Documentation\n    description: The ServiceNow CI/CD API provides REST endpoints for integrating ServiceNow application development with continuous integration and continuous delivery pipelines. It supports operations such as applying changes, running ATF test suites, activating plugins, and managing application installations from external CI/CD tools.\n  - aid: servicenow:servicenow-cicd-update-set-api\n    name: ServiceNow CI/CD Update\
  \ Set API\n    tags:\n      - CI/CD\n      - Deployment\n      - DevOps\n      - Update Sets\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-update-set-api.html\n    baseURL: https://{instance}.service-now.com/api/sn_cicd/update_set\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-update-set-api.html\n        type: Documentation\n    description: The ServiceNow CI/CD Update Set API provides REST methods to create, retrieve, preview, commit, and back out update sets. It enables automated deployment workflows by allowing CI/CD pipelines to manage update set transfers between ServiceNow instances.\n  - aid: servicenow:servicenow-devops-api\n    name: ServiceNow DevOps API\n    tags:\n      - Change Velocity\n      - CI/CD\n      - DevOps\n\
  \      - Pipelines\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-api.html\n    baseURL: https://{instance}.service-now.com/api/sn_devops\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-api.html\n        type: Documentation\n    description: The ServiceNow DevOps API provides REST endpoints for integrating external DevOps toolchains with ServiceNow's DevOps Change Velocity product. It enables automated change request creation, artifact and package tracking, and pipeline orchestration from tools such as Jenkins, Azure DevOps, and GitLab.\n  - aid: servicenow:servicenow-devops-config-api\n    name: ServiceNow DevOps Config API\n    tags:\n      - Automation\n      - Change Management\n      - Configuration\n      - DevOps\n   \
  \ image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-config-api.html\n    baseURL: https://{instance}.service-now.com/api/sn_devops_config\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-config-api.html\n        type: Documentation\n    description: The ServiceNow DevOps Config API provides REST endpoints for managing DevOps configuration data and policies. It supports configuration validation and compliance checks as part of the DevOps change acceleration workflow.\n  - aid: servicenow:servicenow-cmdb-meta-api\n    name: ServiceNow CMDB Meta API\n    tags:\n      - CMDB\n      - Configuration Management\n      - Metadata\n      - Schema\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n\
  \    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-meta-api.html\n    baseURL: https://{instance}.service-now.com/api/now/cmdb/meta\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-meta-api.html\n        type: Documentation\n    description: The ServiceNow CMDB Meta API provides REST endpoints for retrieving metadata about CMDB classes, including their attributes, relationships, and hierarchy. It enables developers to programmatically discover the CMDB data model and schema for building integrations and reporting tools.\n  - aid: servicenow:servicenow-cmdb-data-ingestion-api\n    name: ServiceNow CMDB Data Ingestion API\n    tags:\n      - CMDB\n      - Configuration Management\n      - Data Ingestion\n      - Integration\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL:\
  \ https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-ingest-api.html\n    baseURL: https://{instance}.service-now.com/api/now/cmdb/ingest\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-ingest-api.html\n        type: Documentation\n    description: The ServiceNow CMDB Data Ingestion API provides REST endpoints for bulk ingesting configuration item data into the CMDB from external data sources. It supports high-volume CI data loading with built-in identification and reconciliation processing.\n  - aid: servicenow:servicenow-metricbase-time-series-api\n    name: ServiceNow MetricBase Time Series API\n    tags:\n      - ITOM\n      - Metrics\n      - Monitoring\n      - Time Series\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/Clotho-Time-Series-API.html\n\
  \    baseURL: https://{instance}.service-now.com/api/now/clotho\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/Clotho-Time-Series-API.html\n        type: Documentation\n    description: The ServiceNow MetricBase Time Series API (formerly Clotho) provides REST endpoints for storing, retrieving, and transforming time series metric data on the Now Platform. It is used by IT Operations Management to ingest and query monitoring data such as CPU usage, memory utilization, and custom metrics.\n  - aid: servicenow:servicenow-interaction-management-api\n    name: ServiceNow Interaction Management API\n    tags:\n      - Agent Workspace\n      - Customer Service\n      - Interactions\n      - Omnichannel\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/interaction-management-api.html\n\
  \    baseURL: https://{instance}.service-now.com/api/interaction\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/interaction-management-api.html\n        type: Documentation\n    description: The ServiceNow Interaction Management API provides REST endpoints for creating and managing customer interactions across multiple channels. It supports omnichannel routing and enables external contact center systems to create and update interaction records in ServiceNow Agent Workspace.\n  - aid: servicenow:servicenow-voice-interaction-resource-api\n    name: ServiceNow Voice Interaction Resource API\n    tags:\n      - Contact Center\n      - Interactions\n      - Telephony\n      - Voice\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/voice-interaction-resource-api.html\n\
  \    baseURL: https://{instance}.service-now.com/api/now/voice\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/voice-interaction-resource-api.html\n        type: Documentation\n    description: The ServiceNow Voice Interaction Resource API provides REST endpoints for integrating telephony and voice systems with ServiceNow. It enables Contact Center as a Service (CCaaS) providers to manage voice interactions and route calls to agents within Agent Workspace.\n  - aid: servicenow:servicenow-user-role-inheritance-api\n    name: ServiceNow User Role Inheritance API\n    tags:\n      - Access Control\n      - Roles\n      - Security\n      - Users\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/user-role-inheritance-api.html\n    baseURL: https://{instance}.service-now.com/api/now/user_role_inheritance\n\
  \    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/user-role-inheritance-api.html\n        type: Documentation\n    description: The ServiceNow User Role Inheritance API provides REST endpoints for querying the role inheritance hierarchy for users and groups. It enables external systems to determine effective roles and permissions assigned through direct assignment or group membership inheritance.\n  - aid: servicenow:servicenow-hr-api\n    name: ServiceNow HR API\n    tags:\n      - Employee Services\n      - HR Service Delivery\n      - HRSD\n      - Human Resources\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/hr-core-api.html\n    baseURL: https://{instance}.service-now.com/api/sn_hr_core\n    properties:\n      - url: https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/hr-core-api.html\n\
  \        type: Documentation\n    description: The ServiceNow HR API provides REST endpoints for managing Human Resources Service Delivery (HRSD) data including employee cases, lifecycle events, and HR service requests. It enables integration with external HR systems such as Workday and SuccessFactors for employee data synchronization.\n  - aid: servicenow:servicenow-event-management-topic-api\n    name: ServiceNow Event Management Topic Open API\n    tags:\n      - Alerts\n      - Event Management\n      - ITOM\n      - Monitoring\n    image: https://www.servicenow.com/content/dam/servicenow-assets/images/meganav/servicenow-logo.svg\n    humanURL: https://www.servicenow.com/\n\n# --- truncated at 32 KB (66 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/apis.yml
tags:
- Automation
- Cloud Services
- Digital Workflows
- Enterprise Platform
- IT Service Management
- ITSM
- Processes
- T1
- Workflow Automation
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/apis.yml
use_cases:
- description: Automate incident creation, assignment, escalation, and resolution through Table and Predictive Intelligence APIs.
  name: Incident Management Automation
- description: Integrate external CI/CD pipelines with ServiceNow change management for automated change request workflows.
  name: Change Management Integration
- description: Keep the CMDB in sync with external discovery and monitoring tools using Identification and Reconciliation APIs.
  name: CMDB Synchronization
- description: Build custom portals that browse service catalogs, submit requests, and track order status.
  name: Self-Service Portal Integration
- description: Manage customer cases, contacts, and interactions across channels with CSM and Virtual Agent APIs.
  name: Customer Service Orchestration
- description: Ingest events and metrics from monitoring tools for centralized alert management and correlation.
  name: IT Operations Monitoring
- description: Load data from external sources using Import Set APIs with transform maps for automated field mapping.
  name: Data Migration And ETL
- description: Manage agent availability and route work items based on skills and capacity using AWA APIs.
  name: Workforce Optimization
---
