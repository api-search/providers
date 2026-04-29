---
api_count: 31
api_specs:
- filename: rest-api.yml
  format: yaml
  label: PeopleSoft REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/rest-api.yml
- filename: application-services-framework.yml
  format: yaml
  label: PeopleSoft Application Services Framework API
  slug: application-services-framework-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/application-services-framework.yml
- filename: integration-broker.yml
  format: yaml
  label: PeopleSoft Integration Broker
  slug: integration-broker
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/integration-broker.yml
- filename: query.yml
  format: yaml
  label: PeopleSoft Query API
  slug: query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/query.yml
- filename: component-interface.yml
  format: yaml
  label: PeopleSoft Component Interface API
  slug: component-interface-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/component-interface.yml
- filename: search-framework.yml
  format: yaml
  label: PeopleSoft Search Framework API
  slug: search-framework-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/search-framework.yml
- filename: notification-framework.yml
  format: yaml
  label: PeopleSoft Notification Framework API
  slug: notification-framework-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/notification-framework.yml
- filename: chatbot-integration.yml
  format: yaml
  label: PeopleSoft Chatbot Integration Framework API
  slug: chatbot-integration-framework-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/chatbot-integration.yml
- filename: approval-workflow-engine.yml
  format: yaml
  label: PeopleSoft Approval Workflow Engine API
  slug: approval-workflow-engine-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/approval-workflow-engine.yml
- filename: process-scheduler.yml
  format: yaml
  label: PeopleSoft Process Scheduler API
  slug: process-scheduler-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/process-scheduler.yml
- filename: cloud-manager.yml
  format: yaml
  label: PeopleSoft Cloud Manager API
  slug: cloud-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/cloud-manager.yml
- filename: update-manager.yml
  format: yaml
  label: PeopleSoft Update Manager API
  slug: update-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/update-manager.yml
- filename: pivot-grid.yml
  format: yaml
  label: PeopleSoft Pivot Grid API
  slug: pivot-grid-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/pivot-grid.yml
- filename: hcm.yml
  format: yaml
  label: PeopleSoft HCM API
  slug: hcm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/hcm.yml
- filename: recruiting-talent-management.yml
  format: yaml
  label: PeopleSoft Recruiting and Talent Management API
  slug: recruiting-and-talent-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/recruiting-talent-management.yml
- filename: financials.yml
  format: yaml
  label: PeopleSoft Financials API
  slug: financials-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/financials.yml
- filename: supply-chain-management.yml
  format: yaml
  label: PeopleSoft Supply Chain Management API
  slug: supply-chain-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/supply-chain-management.yml
- filename: crm.yml
  format: yaml
  label: PeopleSoft CRM API
  slug: crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/crm.yml
- filename: campus-solutions.yml
  format: yaml
  label: PeopleSoft Campus Solutions API
  slug: campus-solutions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/campus-solutions.yml
- filename: enterprise-performance-management.yml
  format: yaml
  label: PeopleSoft Enterprise Performance Management API
  slug: enterprise-performance-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/enterprise-performance-management.yml
- filename: interaction-hub.yml
  format: yaml
  label: PeopleSoft Interaction Hub API
  slug: interaction-hub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/openapi/interaction-hub.yml
apis:
- description: RESTful web services for PeopleSoft applications enabling integration with external systems via the PeopleTools platform.
  name: PeopleSoft REST API
  slug: rest-api
- description: Modern REST API layer introduced in PeopleTools 8.59 that produces fully compliant OpenAPI/Swagger specifications, supports proper HTTP status codes, uniform URLs, and JSON payloads for integration wi
  name: PeopleSoft Application Services Framework API
  slug: application-services-framework-api
- description: Message-based integration framework for synchronous and asynchronous communication supporting both SOAP and REST protocols.
  name: PeopleSoft Integration Broker
  slug: integration-broker
- description: Execute PeopleSoft Query definitions and retrieve results via REST including the Query Access Service operations for listing, executing, and managing queries.
  name: PeopleSoft Query API
  slug: query-api
- description: Programmatic access to PeopleSoft components for data manipulation providing CRUD operations on component data via REST.
  name: PeopleSoft Component Interface API
  slug: component-interface-api
- description: Search indexing and query capabilities powered by OpenSearch (previously Elasticsearch) for full-text search, analytics dashboards, and PeopleSoft Insights.
  name: PeopleSoft Search Framework API
  slug: search-framework-api
- description: Framework for extracting and flattening PeopleSoft data for machine learning and analytics purposes. Uses PeopleSoft Search Framework technology with OpenSearch to build, index, and register data mode
  name: PeopleSoft Data Distribution Framework API
  slug: data-distribution-framework-api
- description: Push notification and event-driven notification services including the Notification Composer for email, text, and in-app notifications. Requires PeopleTools 8.59.19+.
  name: PeopleSoft Notification Framework API
  slug: notification-framework-api
- description: Integration framework for connecting PeopleSoft with Oracle Digital Assistant (ODA) including REST services for chatbot data retrieval and embedded chatbot UI on Fluid pages (PICASO). Requires PeopleT
  name: PeopleSoft Chatbot Integration Framework API
  slug: chatbot-integration-framework-api
- description: Framework for creating, running, and managing approval processes exposable via REST service operations through Integration Broker or ASF.
  name: PeopleSoft Approval Workflow Engine API
  slug: approval-workflow-engine-api
- description: Process request APIs for submitting and scheduling batch jobs, monitoring process run status, viewing logs, and Application Engine batch processing statistics.
  name: PeopleSoft Process Scheduler API
  slug: process-scheduler-api
- description: REST APIs for automated environment provisioning and deployment on Oracle Cloud Infrastructure including PeopleTools upgrades, update management, and self-service provisioning templates.
  name: PeopleSoft Cloud Manager API
  slug: cloud-manager-api
- description: REST services for automated update image management, change package generation, and PeopleSoft Automated Updates (PAU).
  name: PeopleSoft Update Manager API
  slug: update-manager-api
- description: Operational dashboard reporting using PS Query, Composite Query, or component data sources accessible via web services for analytics and visualization.
  name: PeopleSoft Pivot Grid API
  slug: pivot-grid-api
- description: Human Capital Management APIs for employee data, benefits, payroll, workforce administration, and talent management.
  name: PeopleSoft HCM API
  slug: hcm-api
- description: REST API for retrieving employee details by name or employee ID, and for looking up direct reports based on manager name or ID. Supports the Employee Directory chatbot skill and integration with exter
  name: PeopleSoft Employee Directory API
  slug: employee-directory-api
- description: REST API for creating, updating, and retrieving absence requests, viewing employee absence balances by type, and retrieving absence configuration rules. Supports Absence Management chatbot skill and s
  name: PeopleSoft Absence Management API
  slug: absence-management-api
- description: REST endpoints for job search services, Candidate Gateway self-service, recruiting solutions, and talent management workflows.
  name: PeopleSoft Recruiting and Talent Management API
  slug: recruiting-and-talent-management-api
- description: Delivered REST API endpoints for retrieving paycheck header details, earnings, deductions, taxes, direct deposits, employer paid benefits, garnishments, and year-end forms for North American payroll p
  name: PeopleSoft Payroll for North America API
  slug: payroll-for-north-america-api
- description: REST API endpoints for the Global Payroll skill, providing access to payroll data, product profile information, and chatbot framework resources for international payroll processing across multiple cou
  name: PeopleSoft Global Payroll API
  slug: global-payroll-api
- description: REST API for retrieving employee country and business partner contact details. Shared utility services used across all delivered HCM skills and integration scenarios.
  name: PeopleSoft HR Common Utility Services API
  slug: hr-common-utility-services-api
- description: Financial Management APIs for general ledger, accounts payable, accounts receivable, expenses, asset management, and financial reporting.
  name: PeopleSoft Financials API
  slug: financials-api
- description: 'Delivered REST API endpoints for expense report management including fetching expense reports by status, creation date, or sheet name, retrieving transaction details, managing wallet entries, expense '
  name: PeopleSoft Expenses API
  slug: expenses-api
- description: Delivered REST API endpoints for invoice and payment management including fetching disputed invoices, invoice status inquiries, payment status tracking, payment inquiries, and payment difference resol
  name: PeopleSoft eSettlements API
  slug: esettlements-api
- description: REST API endpoints for procurement, inventory management, order fulfillment, logistics, and enterprise integration points for warehouse management systems.
  name: PeopleSoft Supply Chain Management API
  slug: supply-chain-management-api
- description: Delivered REST API endpoints for requisition management including retrieving requisitions for items, getting requester lists and names, and checking requisition status. Supports the full procure-to-pa
  name: PeopleSoft eProcurement API
  slug: eprocurement-api
- description: Comprehensive REST API for the Supplier Portal providing access to bid details, managed content such as announcements and events, overdue shipment tracking, purchase order acknowledgement, invoice and
  name: PeopleSoft Supplier Portal API
  slug: supplier-portal-api
- description: Customer Relationship Management REST API endpoints and integration points for customer data, case management, sales, and marketing.
  name: PeopleSoft CRM API
  slug: crm-api
- description: Campus Solutions APIs for student records, admissions, enrollment, financial aid, and academic advising.
  name: PeopleSoft Campus Solutions API
  slug: campus-solutions-api
- description: Analytics, budgeting, forecasting, and planning APIs with events and notifications framework for financial and operational performance management.
  name: PeopleSoft Enterprise Performance Management API
  slug: enterprise-performance-management-api
- description: Content management, branding, and portal administration APIs for the PeopleSoft Interaction Hub (formerly Enterprise Portal) with Integration Broker services.
  name: PeopleSoft Interaction Hub API
  slug: interaction-hub-api
capabilities:
- description: Unified workflow for campus administrators combining student records, admissions, enrollment, financial aid, and approval workflows across PeopleSoft Campus Solutions and Approval Workflow Engine APIs
  name: PeopleSoft Campus Administration
  slug: campus-administration
- description: Unified workflow for CRM users combining customer management, case management, sales, chatbot integration, and notifications across PeopleSoft CRM, Chatbot Integration, and Notification Framework APIs
  name: PeopleSoft Customer Engagement
  slug: customer-engagement
- description: Unified workflow for finance controllers combining general ledger, accounts payable, accounts receivable, expenses, budgeting, forecasting, analytics, and approval workflows across PeopleSoft Financia
  name: PeopleSoft Finance And Accounting
  slug: finance-and-accounting
- description: 'Unified workflow for HR administrators combining employee management, benefits, payroll, recruiting, talent management, and approval workflows across PeopleSoft HCM, Recruiting, and Approval Workflow '
  name: PeopleSoft Human Resources
  slug: human-resources
- description: Unified workflow for IT administrators combining environment provisioning, update management, process scheduling, integration broker, REST API management, application services framework, and component
  name: PeopleSoft Platform Administration
  slug: platform-administration
- description: Unified workflow for content managers combining portal content management, branding, chatbot integration, and notification services across PeopleSoft Interaction Hub, Chatbot Integration, and Notifica
  name: PeopleSoft Portal And Communications
  slug: portal-and-communications
- description: Unified workflow for analysts combining query execution, pivot grid dashboards, full-text search, and performance analytics across PeopleSoft Query, Pivot Grid, Search Framework, and EPM APIs.
  name: PeopleSoft Reporting And Analytics
  slug: reporting-and-analytics
- description: Unified workflow for supply chain managers combining procurement, inventory, order fulfillment, and approval workflows across PeopleSoft Supply Chain Management and Approval Workflow Engine APIs.
  name: PeopleSoft Supply Chain And Procurement
  slug: supply-chain-and-procurement
common:
- title: ''
  type: Portal
  url: https://www.oracle.com/applications/peoplesoft/
- title: ''
  type: Documentation
  url: https://docs.oracle.com/en/applications/peoplesoft/index.html
- title: ''
  type: GettingStarted
  url: https://docs.oracle.com/en/applications/peoplesoft/peopletools/index.html
- title: ''
  type: Information Portal
  url: https://docs.oracle.com/cd/E52319_01/infoportal/
- title: ''
  type: Authentication
  url: https://docs.oracle.com/cd/F30998_01/pt858pbr2/eng/pt/tsec/concept_UnderstandingOAuth2_0.html
- title: ''
  type: Blog
  url: https://blogs.oracle.com/peoplesoft/
- title: ''
  type: ChangeLog
  url: https://blogs.oracle.com/peoplesoft/category/ps-image-and-release-updates
- title: ''
  type: PeopleCode API Reference
  url: https://docs.oracle.com/cd/E25688_01/pt852pbr0/eng/psbooks/tpcr/book.htm
- title: ''
  type: Security
  url: https://www.oracle.com/security-alerts/
- title: ''
  type: Support
  url: https://support.oracle.com/
- title: ''
  type: Knowledge Base
  url: https://docs.oracle.com/en/applications/peoplesoft/
- title: ''
  type: Community
  url: https://community.oracle.com/customerconnect/categories/peoplesoft
- title: ''
  type: Forum
  url: https://forums.oracle.com/ords/apexds/domain/dev-community/category/peoplesoft_enterprise
- title: ''
  type: PeopleSoft on OCI
  url: https://docs.oracle.com/cd/E52319_01/infoportal/opc.html
- title: ''
  type: Training
  url: https://education.oracle.com/peoplesoft
- title: ''
  type: Videos
  url: https://docs.oracle.com/cd/E52319_01/infoportal/videos.html
- title: ''
  type: Pricing
  url: https://www.oracle.com/corporate/pricing/
- title: ''
  type: TermsOfService
  url: https://www.oracle.com/contracts/
- title: ''
  type: PrivacyPolicy
  url: https://www.oracle.com/legal/privacy/services-privacy-policy/
- title: ''
  type: News
  url: https://docs.oracle.com/cd/E52319_01/infoportal/news.html
- title: ''
  type: StatusPage
  url: https://ocistatus.oraclecloud.com/
- title: ''
  type: Website
  url: https://www.oracle.com/applications/peoplesoft/
- title: ''
  type: Login
  url: https://cloud.oracle.com/
- title: ''
  type: SignUp
  url: https://cloud.oracle.com/
- title: ''
  type: REST API Endpoints
  url: https://docs.oracle.com/cd/G36917_01/ps91pbr20/eng/ps/eccp/UnderstandingRestApiEndpointsForPeoplesoft.html
created: '2024-01-15'
description: Collection of Oracle PeopleSoft Enterprise application APIs for Human Capital Management, Financial Management, Supply Chain Management, CRM, Campus Solutions, and engineering intelligence across PeopleTools platform services.
features:
- description: RESTful APIs via PeopleTools Integration Broker for JSON-based integration with external systems.
  name: REST Web Services
- description: Modern REST API layer with OpenAPI spec generation, proper HTTP status codes, and JSON payloads.
  name: Application Services Framework
- description: Enterprise messaging and integration platform supporting SOAP, REST, and asynchronous messaging.
  name: Integration Broker
- description: Programmatic access to PeopleSoft component business logic for data entry and validation.
  name: Component Interface API
- description: Execute PeopleSoft queries and retrieve results via REST for reporting and analytics.
  name: Query API
- description: Human Capital Management APIs for workforce administration, benefits, payroll, and talent management.
  name: HCM APIs
- description: APIs for general ledger, accounts payable/receivable, asset management, and procurement.
  name: Financial Management APIs
- description: APIs for inventory, purchasing, order management, and supplier collaboration.
  name: Supply Chain Management APIs
- description: APIs for student records, admissions, financial aid, and academic advisement.
  name: Campus Solutions APIs
- description: Standards-based OAuth 2.0 authentication for secure API access.
  name: OAuth 2.0 Authentication
- description: APIs for integrating with PeopleSoft Fluid user interface framework.
  name: Fluid UI Integration
- description: Digital assistant and chatbot framework APIs for conversational PeopleSoft interactions.
  name: Chatbot Integration
image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg
integrations: []
jsonld:
- class_count: 8
  name: Peoplesoft Context
  property_count: 77
  slug: peoplesoft-context
layout: provider
modified: '2026-04-17'
name: PeopleSoft
rules:
- name: PeopleSoft API Rules
  rule_count: 19
  severity_counts:
    error: 14
    hint: 0
    info: 1
    warn: 4
  slug: peoplesoft-spectral-rules
skills: []
slug: peoplesoft
solutions:
- description: Human Capital Management for workforce administration, benefits, payroll, talent, and workforce planning.
  name: PeopleSoft HCM
- description: Financial and Supply Chain Management for general ledger, AP/AR, procurement, and inventory.
  name: PeopleSoft FSCM
- description: Higher education platform for student records, admissions, financial aid, and academic management.
  name: PeopleSoft Campus Solutions
- description: Customer Relationship Management for sales, marketing, and service automation.
  name: PeopleSoft CRM
source_filename: apis.yml
source_yaml: "name: PeopleSoft\ndescription: Collection of Oracle PeopleSoft Enterprise application APIs for Human\n  Capital Management, Financial Management, Supply Chain Management, CRM, Campus Solutions,\n  and engineering intelligence across PeopleTools platform services.\nimage: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\ncreated: '2024-01-15'\nmodified: '2026-04-17'\nspecificationVersion: '0.19'\nurl: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/apis.yml\ntags:\n- Campus Solutions\n- CRM\n- Enterprise Software\n- ERP\n- Financial Management\n- HCM\n- Supply Chain Management\napis:\n- name: PeopleSoft REST API\n  description: RESTful web services for PeopleSoft applications enabling integration\n    with external systems via the PeopleTools platform.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/en/applications/peoplesoft/\n  baseURL: https://{hostname}:{port}/psft/api/v1\n  tags:\n  - Integration\n\
  \  - REST\n  - Web Services\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/tpcl/index.html\n  - type: Authentication\n    url: https://docs.oracle.com/cd/F30998_01/pt858pbr2/eng/pt/tsec/concept_UnderstandingOAuth2_0.html\n  - type: OpenAPI\n    url: openapi/rest-api.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:rest-api\n- name: PeopleSoft Application Services Framework API\n  description: Modern REST API layer introduced in PeopleTools 8.59 that produces\n    fully compliant OpenAPI/Swagger specifications, supports proper HTTP status codes,\n    uniform URLs, and JSON payloads for integration with Oracle Integration Cloud,\n    mobile apps, and microservices.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/E52319_01/infoportal/asf.html\n  baseURL: https://{hostname}:{port}/psft/asf/v1\n  tags:\n\
  \  - Integration\n  - Modern\n  - OpenAPI\n  - REST\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E52319_01/infoportal/asf.html\n  - type: OpenAPI\n    url: openapi/application-services-framework.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:application-services-framework-api\n- name: PeopleSoft Integration Broker\n  description: Message-based integration framework for synchronous and asynchronous\n    communication supporting both SOAP and REST protocols.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/tibr/index.html\n  baseURL: https://{hostname}:{port}/PSIGW/RESTListeningConnector\n  tags:\n  - Integration\n  - Messaging\n  - REST\n  - SOAP\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/en/applications/peoplesoft/integration-broker/\n  - type: OpenAPI\n    url: openapi/integration-broker.yml\n\
  \  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:integration-broker\n- name: PeopleSoft Query API\n  description: Execute PeopleSoft Query definitions and retrieve results via REST\n    including the Query Access Service operations for listing, executing, and managing\n    queries.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/en/applications/peoplesoft/query-api/\n  baseURL: https://{hostname}:{port}/psft/api/query/v1\n  tags:\n  - Data Access\n  - QAS\n  - Query\n  - Reporting\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/trws/concept_QueryAccessServiceOperations-1f7e36.html\n  - type: OpenAPI\n    url: openapi/query.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:query-api\n- name: PeopleSoft Component Interface API\n  description:\
  \ Programmatic access to PeopleSoft components for data manipulation\n    providing CRUD operations on component data via REST.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/en/applications/peoplesoft/component-interfaces/\n  baseURL: https://{hostname}:{port}/psft/api/componentinterface/v1\n  tags:\n  - Component Interface\n  - CRUD Operations\n  - Data Access\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/tcpi/index.html\n  - type: OpenAPI\n    url: openapi/component-interface.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:component-interface-api\n- name: PeopleSoft Search Framework API\n  description: Search indexing and query capabilities powered by OpenSearch (previously\n    Elasticsearch) for full-text search, analytics dashboards, and PeopleSoft Insights.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n\
  \  humanURL: https://docs.oracle.com/cd/E52319_01/infoportal/search.html\n  baseURL: https://{hostname}:{port}/psft/api/search/v1\n  tags:\n  - Analytics\n  - Insights\n  - OpenSearch\n  - Search\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E52319_01/infoportal/search.html\n  - type: OpenAPI\n    url: openapi/search-framework.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:search-framework-api\n- name: PeopleSoft Data Distribution Framework API\n  description: Framework for extracting and flattening PeopleSoft data for machine\n    learning and analytics purposes. Uses PeopleSoft Search Framework technology with\n    OpenSearch to build, index, and register data models that can be exposed as REST\n    APIs.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/F44200_01/pt859pbr2/eng/pt/tmlf/concept_UnderstandingDataDistributionFramework.html\n\
  \  baseURL: https://{hostname}:{port}/psft/api/ddf/v1\n  tags:\n  - Analytics\n  - Data Distribution\n  - Data Extraction\n  - Machine Learning\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/F44200_01/pt859pbr2/eng/pt/tmlf/concept_UnderstandingDataDistributionFramework.html\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:data-distribution-framework-api\n- name: PeopleSoft Notification Framework API\n  description: Push notification and event-driven notification services including\n    the Notification Composer for email, text, and in-app notifications. Requires\n    PeopleTools 8.59.19+.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/E41507_01/epm91pbr3/eng/epm/eewe/concept_PeopleSoftEventsandNotificationsFrameworkOverview-227ff2.html\n  baseURL: https://{hostname}:{port}/psft/api/notifications/v1\n  tags:\n  - Events\n  - Messaging\n\
  \  - Notifications\n  - Push Notifications\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E41507_01/epm91pbr3/eng/epm/eewe/concept_PeopleSoftEventsandNotificationsFrameworkOverview-227ff2.html\n  - type: OpenAPI\n    url: openapi/notification-framework.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:notification-framework-api\n- name: PeopleSoft Chatbot Integration Framework API\n  description: Integration framework for connecting PeopleSoft with Oracle Digital\n    Assistant (ODA) including REST services for chatbot data retrieval and embedded\n    chatbot UI on Fluid pages (PICASO). Requires PeopleTools 8.57.07+.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/E52319_01/infoportal/chatbot.html\n  baseURL: https://{hostname}:{port}/psft/api/chatbot/v1\n  tags:\n  - Chatbot\n  - Conversational AI\n  - Digital Assistant\n  -\
  \ PICASO\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E52319_01/infoportal/chatbot.html\n  - type: FAQ\n    url: https://docs.oracle.com/cd/E52319_01/infoportal/peoplesoft_chatbot_faq.html\n  - type: OpenAPI\n    url: openapi/chatbot-integration.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:chatbot-integration-framework-api\n- name: PeopleSoft Approval Workflow Engine API\n  description: Framework for creating, running, and managing approval processes exposable\n    via REST service operations through Integration Broker or ASF.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/en/applications/peoplesoft/\n  baseURL: https://{hostname}:{port}/psft/api/approvals/v1\n  tags:\n  - Approvals\n  - AWE\n  - Workflow\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/en/applications/peoplesoft/\n  - type: OpenAPI\n\
  \    url: openapi/approval-workflow-engine.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:approval-workflow-engine-api\n- name: PeopleSoft Process Scheduler API\n  description: Process request APIs for submitting and scheduling batch jobs, monitoring\n    process run status, viewing logs, and Application Engine batch processing statistics.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/E24150_01/pt851h2/eng/psbooks/tprs/htm/tprs05.htm\n  baseURL: https://{hostname}:{port}/psft/api/scheduler/v1\n  tags:\n  - Batch Processing\n  - Process Monitor\n  - Scheduling\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E24150_01/pt851h2/eng/psbooks/tprs/htm/tprs05.htm\n  - type: OpenAPI\n    url: openapi/process-scheduler.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid:\
  \ peoplesoft:process-scheduler-api\n- name: PeopleSoft Cloud Manager API\n  description: REST APIs for automated environment provisioning and deployment on\n    Oracle Cloud Infrastructure including PeopleTools upgrades, update management,\n    and self-service provisioning templates.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/E52319_01/infoportal/cloudmgr.html\n  baseURL: https://{hostname}:{port}/psft/api/cloudmgr/v1\n  tags:\n  - Cloud\n  - Deployment\n  - OCI\n  - Provisioning\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E52319_01/infoportal/cloudmgr.html\n  - type: OpenAPI\n    url: openapi/cloud-manager.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:cloud-manager-api\n- name: PeopleSoft Update Manager API\n  description: REST services for automated update image management, change package\n    generation, and PeopleSoft\
  \ Automated Updates (PAU).\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/E52319_01/infoportal/pum.html\n  baseURL: https://{hostname}:{port}/psft/api/pum/v1\n  tags:\n  - Lifecycle Management\n  - Patching\n  - Updates\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E52319_01/infoportal/pum.html\n  - type: OpenAPI\n    url: openapi/update-manager.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:update-manager-api\n- name: PeopleSoft Pivot Grid API\n  description: Operational dashboard reporting using PS Query, Composite Query, or\n    component data sources accessible via web services for analytics and visualization.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/F28299_01/pt857pbr3/eng/pt/tpvg/concept_PeopleSoftPivotGridOverview-1e7c6b.html\n  baseURL: https://{hostname}:{port}/psft/api/pivotgrid/v1\n\
  \  tags:\n  - Analytics\n  - Dashboards\n  - Pivot Grid\n  - Reporting\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/F28299_01/pt857pbr3/eng/pt/tpvg/concept_PeopleSoftPivotGridOverview-1e7c6b.html\n  - type: OpenAPI\n    url: openapi/pivot-grid.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:pivot-grid-api\n- name: PeopleSoft HCM API\n  description: Human Capital Management APIs for employee data, benefits, payroll,\n    workforce administration, and talent management.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/en/applications/peoplesoft/human-capital-management/index.html\n  baseURL: https://{hostname}:{port}/psft/api/hcm/v1\n  tags:\n  - Benefits\n  - HCM\n  - HR\n  - Payroll\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/en/applications/peoplesoft/human-capital-management/index.html\n  - type:\
  \ APIReference\n    url: https://docs.oracle.com/cd/F58024_01/hcm92pbr43/eng/hcm/ecch/UnderstandingRestApiEndpointsForPeoplesoftSkills.html\n  - type: OpenAPI\n    url: openapi/hcm.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:hcm-api\n- name: PeopleSoft Employee Directory API\n  description: REST API for retrieving employee details by name or employee ID, and\n    for looking up direct reports based on manager name or ID. Supports the Employee\n    Directory chatbot skill and integration with external directories.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/G20540_01/hcm92pbr51/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeoplesoftEmployeeDirectoryemployeedirectory.html\n  baseURL: https://{hostname}:{port}/psft/api/hcm/employeedirectory/v1\n  tags:\n  - Employee Directory\n  - HCM\n  - Workforce Data\n  properties:\n  - type: Documentation\n   \
  \ url: https://docs.oracle.com/cd/G20540_01/hcm92pbr51/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeoplesoftEmployeeDirectoryemployeedirectory.html\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:employee-directory-api\n- name: PeopleSoft Absence Management API\n  description: REST API for creating, updating, and retrieving absence requests, viewing\n    employee absence balances by type, and retrieving absence configuration rules.\n    Supports Absence Management chatbot skill and self-service integrations.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/F70351_01/cs92pbr27/eng/cs/eccs/UnderstandingRESTAPIEndpointsForPeopleSoftAbsenceManagementApplicationServicesabsence.html\n  baseURL: https://{hostname}:{port}/psft/api/hcm/absence/v1\n  tags:\n  - Absence Management\n  - HCM\n  - Leave\n  - Time Off\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/F70351_01/cs92pbr27/eng/cs/eccs/UnderstandingRESTAPIEndpointsForPeopleSoftAbsenceManagementApplicationServicesabsence.html\n\
  \  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:absence-management-api\n- name: PeopleSoft Recruiting and Talent Management API\n  description: REST endpoints for job search services, Candidate Gateway self-service,\n    recruiting solutions, and talent management workflows.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/F85027_01/hcm92pbr47/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeopleSoftJobSearchServiceshrsjobs.html\n  baseURL: https://{hostname}:{port}/psft/api/hcm/recruiting/v1\n  tags:\n  - Candidate Gateway\n  - Job Search\n  - Recruiting\n  - Talent Management\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/F85027_01/hcm92pbr47/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeopleSoftJobSearchServiceshrsjobs.html\n  - type: OpenAPI\n    url: openapi/recruiting-talent-management.yml\n  contact:\n  - FN: Oracle Support\n\
  \    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:recruiting-and-talent-management-api\n- name: PeopleSoft Payroll for North America API\n  description: Delivered REST API endpoints for retrieving paycheck header details,\n    earnings, deductions, taxes, direct deposits, employer paid benefits, garnishments,\n    and year-end forms for North American payroll processing.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/F57918_01/ps91pbr14/eng/ps/eccp/UnderstandingRestApiEndpointsForPeoplesoftPayrollForNorthAmericaSkill.html\n  baseURL: https://{hostname}:{port}/psft/api/hcm/payrollbankingyearendforms/v1\n  tags:\n  - Compensation\n  - HCM\n  - North America\n  - Payroll\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/F57918_01/ps91pbr14/eng/ps/eccp/UnderstandingRestApiEndpointsForPeoplesoftPayrollForNorthAmericaSkill.html\n  - type: APIReference\n    url: https://docs.oracle.com/cd/F82673_01/elm92pbr23/eng/elm/eccl/UnderstandingRESTAPIEndpointsForPeoplesoftPayrollForNorthAmericaServicespayrollbankingyearendforms.html\n\
  \  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:payroll-for-north-america-api\n- name: PeopleSoft Global Payroll API\n  description: REST API endpoints for the Global Payroll skill, providing access to\n    payroll data, product profile information, and chatbot framework resources for\n    international payroll processing across multiple countries.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/F58738_01/cs92pbr26/eng/cs/eccs/UnderstandingRestApiEndpointsForPeoplesoftGlobalPayrollSkill.html\n  baseURL: https://{hostname}:{port}/psft/api/hcm/globalpayroll/v1\n  tags:\n  - Global Payroll\n  - HCM\n  - International\n  - Payroll\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/F58738_01/cs92pbr26/eng/cs/eccs/UnderstandingRestApiEndpointsForPeoplesoftGlobalPayrollSkill.html\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n\
  \    url: https://support.oracle.com\n  aid: peoplesoft:global-payroll-api\n- name: PeopleSoft HR Common Utility Services API\n  description: REST API for retrieving employee country and business partner contact\n    details. Shared utility services used across all delivered HCM skills and integration\n    scenarios.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/F85282_01/cs92pbr30/eng/cs/eccs/UnderstandingRESTAPIEndpointsforPeopleSoftHRCommonUtilityServices.html\n  baseURL: https://{hostname}:{port}/psft/api/hcm/hcmcommonutilities/v1\n  tags:\n  - Employee Data\n  - HCM\n  - Utilities\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/F85282_01/cs92pbr30/eng/cs/eccs/UnderstandingRESTAPIEndpointsforPeopleSoftHRCommonUtilityServices.html\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:hr-common-utility-services-api\n- name: PeopleSoft\
  \ Financials API\n  description: Financial Management APIs for general ledger, accounts payable, accounts\n    receivable, expenses, asset management, and financial reporting.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/en/applications/peoplesoft/financial-management/index.html\n  baseURL: https://{hostname}:{port}/psft/api/financials/v1\n  tags:\n  - AP\n  - AR\n  - Expenses\n  - Financials\n  - General Ledger\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/en/applications/peoplesoft/financial-management/index.html\n  - type: OpenAPI\n    url: openapi/financials.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:financials-api\n- name: PeopleSoft Expenses API\n  description: Delivered REST API endpoints for expense report management including\n    fetching expense reports by status, creation date, or sheet name, retrieving transaction\n\
  \    details, managing wallet entries, expense type validation, and notification services\n    for travel and expense processing.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/F48195_01/cs92pbr23/eng/cs/eccs/UnderstandingRestApiEndpointsForPeoplesoftExpenseSkill.html\n  baseURL: https://{hostname}:{port}/psft/api/fscm/expenses/v1\n  tags:\n  - Expense Reports\n  - Expenses\n  - Financials\n  - Travel\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/F48195_01/cs92pbr23/eng/cs/eccs/UnderstandingRestApiEndpointsForPeoplesoftExpenseSkill.html\n  - type: APIReference\n    url: https://docs.oracle.com/cd/G47724_01/fscm92pbr55/eng/fscm/eccf/UnderstandingRESTAPIEndpointsForPeopleSoftGetTransactionDetailsexgettransdetails.html\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:expenses-api\n- name: PeopleSoft eSettlements API\n  description:\
  \ Delivered REST API endpoints for invoice and payment management including\n    fetching disputed invoices, invoice status inquiries, payment status tracking,\n    payment inquiries, and payment difference resolution for supplier settlement processing.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/F57918_01/ps91pbr14/eng/ps/eccp/UnderstandingRESTAPIEndpointsforPeopleSofteSettlementsSkill.html\n  baseURL: https://{hostname}:{port}/psft/api/fscm/esettlements/v1\n  tags:\n  - eSettlements\n  - Financials\n  - Invoices\n  - Payments\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/F57918_01/ps91pbr14/eng/ps/eccp/UnderstandingRESTAPIEndpointsforPeopleSofteSettlementsSkill.html\n  - type: APIReference\n    url: https://docs.oracle.com/cd/G35227_01/fscm92pbr54/eng/fscm/eccf/UnderstandingRESTAPIEndpointsForPeopleSoftFetchPaymentStatusespaymentstatus.html\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n\
  \    url: https://support.oracle.com\n  aid: peoplesoft:esettlements-api\n- name: PeopleSoft Supply Chain Management API\n  description: REST API endpoints for procurement, inventory management, order fulfillment,\n    logistics, and enterprise integration points for warehouse management systems.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/F92336_01/fscm92pbr50/eng/fscm/eccf/UnderstandingRestApiEndpointsForPeoplesoft.html\n  baseURL: https://{hostname}:{port}/psft/api/scm/v1\n  tags:\n  - Inventory\n  - Logistics\n  - Order Fulfillment\n  - Procurement\n  - Supply Chain\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/F92336_01/fscm92pbr50/eng/fscm/eccf/UnderstandingRestApiEndpointsForPeoplesoft.html\n  - type: OpenAPI\n    url: openapi/supply-chain-management.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:supply-chain-management-api\n\
  - name: PeopleSoft eProcurement API\n  description: Delivered REST API endpoints for requisition management including retrieving\n    requisitions for items, getting requester lists and names, and checking requisition\n    status. Supports the full procure-to-pay lifecycle from requisition creation through\n    purchase order dispatch and receiving.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/F92336_01/fscm92pbr50/eng/fscm/eccf/UnderstandingRestApiEndpointsForPeoplesoft.html\n  baseURL: https://{hostname}:{port}/psft/api/fscm/eprocurement/v1\n  tags:\n  - eProcurement\n  - Purchasing\n  - Requisitions\n  - Supply Chain\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/F92336_01/fscm92pbr50/eng/fscm/eccf/UnderstandingRestApiEndpointsForPeoplesoft.html\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:eprocurement-api\n- name: PeopleSoft\
  \ Supplier Portal API\n  description: Comprehensive REST API for the Supplier Portal providing access to\n    bid details, managed content such as announcements and events, overdue shipment\n    tracking, purchase order acknowledgement, invoice and payment inquiries, and sourcing\n    operations across secure and public supplier collaboration channels.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/G20540_01/hcm92pbr51/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeopleSoftSupplierComprehensivePortalServicescp.html\n  baseURL: https://{hostname}:{port}/psft/api/fscm/scp/v1\n  tags:\n  - Sourcing\n  - Supplier Collaboration\n  - Supplier Portal\n  - Supply Chain\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/G20540_01/hcm92pbr51/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeopleSoftSupplierComprehensivePortalServicescp.html\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n\
  \  aid: peoplesoft:supplier-portal-api\n- name: PeopleSoft CRM API\n  description: Customer Relationship Management REST API endpoints and integration\n    points for customer data, case management, sales, and marketing.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/F95753_01/crm92pbr22/eng/crm/eccc/UnderstandingRestApiEndpointsForPeoplesoft.html\n  baseURL: https://{hostname}:{port}/psft/api/crm/v1\n  tags:\n  - Case Management\n  - CRM\n  - Customer Data\n  - Marketing\n  - Sales\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/F95753_01/crm92pbr22/eng/crm/eccc/UnderstandingRestApiEndpointsForPeoplesoft.html\n  - type: OpenAPI\n    url: openapi/crm.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:crm-api\n- name: PeopleSoft Campus Solutions API\n  description: Campus Solutions APIs for student records, admissions, enrollment,\n\
  \    financial aid, and academic advising.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/en/applications/peoplesoft/campus-solutions/index.html\n  baseURL: https://{hostname}:{port}/psft/api/campus/v1\n  tags:\n  - Admissions\n  - Campus Solutions\n  - Education\n  - Financial Aid\n  - Student Records\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/en/applications/peoplesoft/campus-solutions/index.html\n  - type: OpenAPI\n    url: openapi/campus-solutions.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:campus-solutions-api\n- name: PeopleSoft Enterprise Performance Management API\n  description: Analytics, budgeting, forecasting, and planning APIs with events and\n    notifications framework for financial and operational performance management.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/E41507_01/epm91pbr3/eng/epm/penw/index.html\n\
  \  baseURL: https://{hostname}:{port}/psft/api/epm/v1\n  tags:\n  - Analytics\n  - Budgeting\n  - EPM\n  - Forecasting\n  - Planning\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E41507_01/epm91pbr3/eng/epm/penw/index.html\n  - type: OpenAPI\n    url: openapi/enterprise-performance-management.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:enterprise-performance-management-api\n- name: PeopleSoft Interaction Hub API\n  description: Content management, branding, and portal administration APIs for the\n    PeopleSoft Interaction Hub (formerly Enterprise Portal) with Integration Broker\n    services.\n  image: https://www.oracle.com/a/ocom/img/cb71-psft-logo.jpg\n  humanURL: https://docs.oracle.com/cd/F75142_01/ps91pbr15/eng/ps/psad/PeopleSoftInteractionHubOverview.html\n  baseURL: https://{hostname}:{port}/psft/api/hub/v1\n  tags:\n  - Branding\n  - Content Management\n  - Interaction\
  \ Hub\n  - Portal\n  properties:\n  - type: Documentation\n    url: https://docs.oracle.com/cd/F75142_01/ps91pbr15/eng/ps/psad/PeopleSoftInteractionHubOverview.html\n  - type: OpenAPI\n    url: openapi/interaction-hub.yml\n  contact:\n  - FN: Oracle Support\n    email: support@oracle.com\n    url: https://support.oracle.com\n  aid: peoplesoft:interaction-hub-api\ncommon:\n- type: Portal\n  url: https://www.oracle.com/applications/peoplesoft/\n- type: Documentation\n  url: https://docs.oracle.com/en/applications/peoplesoft/index.html\n- type: GettingStarted\n  url: https://docs.oracle.com/en/applications/peoplesoft/peopletools/index.html\n- type: Information Portal\n  url: https://docs.oracle.com/cd/E52319_01/infoportal/\n- type: Authentication\n  url: https://docs.oracle.com/cd/F30998_01/pt858pbr2/eng/pt/tsec/concept_UnderstandingOAuth2_0.html\n- type: Blog\n  url: https://blogs.oracle.com/peoplesoft/\n- type: ChangeLog\n  url: https://blogs.oracle.com/peoplesoft/category/ps-image-and-release-updates\n\
  - type: PeopleCode API Reference\n  url: https://docs.oracle.com/cd/E25688_01/pt852pbr0/eng/psbooks/tpcr/book.htm\n- type: Security\n  url: https://www.oracle.com/security-alerts/\n- type: Support\n  url: https://support.oracle.com/\n- type: Knowledge Base\n  url: https://docs.oracle.com/en/applications/peoplesoft/\n- type: Community\n  url: https://community.oracle.com/customerconnect/categories/peoplesoft\n- type: Forum\n  url: https://forums.oracle.com/ords/apexds/domain/dev-community/category/peoplesoft_enterprise\n- type: PeopleSoft on OCI\n  url: https://docs.oracle.com/cd/E52319_01/infoportal/opc.html\n- type: Training\n  url: https://education.oracle.com/peoplesoft\n- type: Videos\n  url: https://docs.oracle.com/cd/E52319_01/infoportal/videos.html\n- type: Pricing\n  url: https://www.oracle.com/corporate/pricing/\n- type: TermsOfService\n  url: https://www.oracle.com/contracts/\n- type: PrivacyPolicy\n  url: https://www.oracle.com/legal/privacy/services-privacy-policy/\n- type:\
  \ News\n  url: https://docs.oracle.com/cd/E52319_01/infoportal/news.html\n- type: StatusPage\n  url: https://ocistatus.oraclecloud.com/\n- type: Website\n  url: https://www.oracle.com/applications/peoplesoft/\n- type: Login\n  url: https://cloud.oracle.com/\n- type: SignUp\n  url: https://cloud.oracle.com/\n- type: REST API Endpoints\n  url: https://docs.oracle.com/cd/G36917_01/ps91pbr20/eng/ps/eccp/UnderstandingRestApiEndpointsForPeoplesoft.html\n- type: Features\n  data:\n  - name: REST Web Services\n    description: RESTful APIs via PeopleTools Integration Broker for JSON-based integration\n      with external systems.\n  - name: Application Services Framework\n    description: Modern REST API layer with OpenAPI spec generation, proper HTTP status\n      codes, and JSON payloads.\n  - name: Integration Broker\n    description: Enterprise messaging and integration platform supporting SOAP, REST,\n      and asynchronous messaging.\n  - name: Component Interface API\n    description: Programmatic\
  \ access to PeopleSoft component business logic for data\n      entry and validation.\n  - name: Query API\n    description: Execute PeopleSoft queries and retrieve results via REST for reporting\n      and analytics.\n  - name: HCM APIs\n    description: Human Capital Management APIs for workforce administration, benefits,\n      payroll, and talent management.\n  - name: Financial Management APIs\n    description: APIs for general ledger, accounts payable/receivable, asset management,\n      and procurement.\n  - name: Supply Chain Management APIs\n    description: APIs for inventory, purchasing, order management, and supplier collaboration.\n  - name: Campus Solutions APIs\n    description: APIs for student records, admissions, financial aid, and academic\n      advisement.\n  - name: OAuth 2.0 Authentication\n    description: Standards-based OAuth 2.0 authentication for secure API access.\n  - name: Fluid UI Integration\n    description: APIs for integrating with PeopleSoft Fluid user\
  \ interface framework.\n  - name: Chatbot Integration\n    description: Digital assistant and chatbot framework APIs for conversational PeopleSoft\n      interactions.\n- type: UseCases\n  data:\n  - name: HR System Integration\n    description: Integrate HCM data with payroll, benefits, and talent management\n      platforms.\n  - name: Financial Data Exchange\n    description: Exchange financial transactions and reporting data with external\n      ERP and accounting systems.\n  - name: Student Information System\n    description: Integrate campus solutions with learning management and student portal\n      systems.\n  - name: Supply Chain Automation\n    description: Automate procurement, inventory, and supplier management workflows.\n  - name: Self-Service Portals\n    description: Build employee and student self-service applications using PeopleSoft\n      APIs.\n  - name: Mobile Applications\n    description: Power mobile apps for employee self-\n\n# --- truncated at 32 KB (32 KB\
  \ total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/apis.yml
tags:
- Campus Solutions
- CRM
- Enterprise Software
- ERP
- Financial Management
- HCM
- Supply Chain Management
url: https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/apis.yml
use_cases:
- description: Integrate HCM data with payroll, benefits, and talent management platforms.
  name: HR System Integration
- description: Exchange financial transactions and reporting data with external ERP and accounting systems.
  name: Financial Data Exchange
- description: Integrate campus solutions with learning management and student portal systems.
  name: Student Information System
- description: Automate procurement, inventory, and supplier management workflows.
  name: Supply Chain Automation
- description: Build employee and student self-service applications using PeopleSoft APIs.
  name: Self-Service Portals
- description: Power mobile apps for employee self-service, approvals, and time entry.
  name: Mobile Applications
- description: Connect PeopleSoft with Oracle Integration Cloud and other cloud platforms.
  name: Cloud Integration
- description: Extract data via Query API for business intelligence and analytics platforms.
  name: Reporting and Analytics
---
