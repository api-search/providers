---
api_count: 7
api_specs:
- filename: sap-integration-suite-cloud-integration-openapi.yml
  format: yaml
  label: SAP Cloud Integration API
  slug: sap-cloud-integration
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-integration-suite/refs/heads/main/openapi/sap-integration-suite-cloud-integration-openapi.yml
- filename: sap-integration-suite-api-management-openapi.yml
  format: yaml
  label: SAP API Management API
  slug: sap-api-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-integration-suite/refs/heads/main/openapi/sap-integration-suite-api-management-openapi.yml
apis:
- description: The SAP Cloud Integration API (Process Integration Runtime API) allows developers to deploy, monitor, and manage integration flows and artifacts on SAP Integration Suite. It provides OData V2 endpoint
  name: SAP Cloud Integration API
  slug: sap-cloud-integration
- description: The SAP API Management API enables programmatic management of APIs, products, applications, and developer portals within SAP Integration Suite. It supports creating and publishing API proxies, managin
  name: SAP API Management API
  slug: sap-api-management
- description: The SAP Integration Advisor API provides access to the library of message implementation guidelines (MIGs) and mapping guidelines (MAGs) used to simplify B2B and A2A integration scenarios. It supports
  name: SAP Integration Advisor API
  slug: sap-integration-advisor
- description: The SAP Open Connectors API (formerly Cloud Elements) provides a unified REST interface to connect to over 160 third-party cloud applications using pre-built connectors. It normalizes disparate API en
  name: SAP Open Connectors API
  slug: sap-open-connectors
- description: The SAP Trading Partner Management API supports setup and management of B2B trading partner relationships, agreements, and communication channels within SAP Integration Suite. It enables automation of
  name: SAP Trading Partner Management API
  slug: sap-trading-partner-management
- description: The SAP Event Mesh API provides access to the event brokering service within SAP Business Technology Platform that enables applications to communicate through asynchronous events. It supports publishi
  name: SAP Event Mesh API
  slug: sap-event-mesh
- description: The SAP Integration Suite Advanced Event Mesh (AEM) REST API provides management capabilities for event brokers, message queues, topic subscriptions, and event broker services. It enables programmatic
  name: SAP Integration Suite Advanced Event Mesh API
  slug: sap-integration-suite-advanced-event-mesh
capabilities:
- description: Unified capability for managing the complete integration lifecycle on SAP Integration Suite. Combines Cloud Integration artifact management with API Management proxy lifecycle for integration develope
  name: SAP Integration Suite - Integration Lifecycle
  slug: integration-lifecycle
common:
- title: ''
  type: Portal
  url: https://api.sap.com/
- title: ''
  type: Documentation
  url: https://help.sap.com/docs/integration-suite
- title: ''
  type: Website
  url: https://www.sap.com/products/technology-platform/integration-suite.html
- title: ''
  type: Getting Started
  url: https://help.sap.com/docs/integration-suite/sap-integration-suite/what-is-sap-integration-suite
- title: ''
  type: Authentication
  url: https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication
- title: ''
  type: Blog
  url: https://blogs.sap.com/tags/73554900100700002542/
- title: ''
  type: Community
  url: https://community.sap.com/topics/integration-suite
- title: ''
  type: Support
  url: https://support.sap.com/en/product/support-by-product/73554900100700002542.html
- title: ''
  type: Status
  url: https://www.sap.com/about/trust-center/cloud-service-status.html
- title: ''
  type: GitHub Organization
  url: https://github.com/SAP-samples
- title: ''
  type: Terms of Service
  url: https://www.sap.com/about/agreements/policies/cloud-platform.html
- title: ''
  type: Privacy Policy
  url: https://www.sap.com/about/legal/privacy.html
- title: ''
  type: YouTube
  url: https://www.youtube.com/@SAPTechnology
- title: ''
  type: Pricing
  url: https://www.sap.com/products/technology-platform/integration-suite/pricing.html
- title: ''
  type: Tutorials
  url: https://developers.sap.com/tutorial-navigator.html?tag=software-product%3Atechnology-platform%2Fsap-integration-suite
- title: ''
  type: Vocabulary
  url: vocabulary/sap-integration-suite-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/integration-lifecycle.yaml
- title: ''
  type: SpectralRules
  url: rules/sap-integration-suite-rules.yml
created: '2026-03-16'
description: SAP Integration Suite is an enterprise integration platform as a service (iPaaS) that connects applications, processes, and people across cloud and on-premises environments. It includes capabilities for Cloud Integration, API Management, Integration Advisor, Open Connectors, Trading Partner Management, and Event Mesh as part of SAP Business Technology Platform (BTP). It enables seamless connectivity between SAP and non-SAP systems.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Sap Integration Suite Context
  property_count: 6
  slug: sap-integration-suite-context
layout: provider
modified: '2026-05-02'
name: SAP Integration Suite
rules:
- name: SAP Integration Suite API Rules
  rule_count: 11
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 10
  slug: sap-integration-suite-rules
skills: []
slug: sap-integration-suite
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sap-integration-suite\nname: SAP Integration Suite\ndescription: >-\n  SAP Integration Suite is an enterprise integration platform as a service\n  (iPaaS) that connects applications, processes, and people across cloud and\n  on-premises environments. It includes capabilities for Cloud Integration,\n  API Management, Integration Advisor, Open Connectors, Trading Partner\n  Management, and Event Mesh as part of SAP Business Technology Platform (BTP).\n  It enables seamless connectivity between SAP and non-SAP systems.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Management\n  - Cloud Integration\n  - Enterprise Integration\n  - Event Mesh\n  - iPaaS\n  - SAP\n  - SAP BTP\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sap-integration-suite/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: sap-integration-suite:sap-cloud-integration\n\
  \    name: SAP Cloud Integration API\n    description: >-\n      The SAP Cloud Integration API (Process Integration Runtime API) allows\n      developers to deploy, monitor, and manage integration flows and artifacts\n      on SAP Integration Suite. It provides OData V2 endpoints for runtime\n      monitoring, message processing logs, artifact lifecycle management,\n      integration package management, and service endpoint discovery.\n    humanURL: https://help.sap.com/docs/integration-suite/sap-integration-suite/cloud-integration\n    baseURL: https://{host}/api/v1\n    tags:\n      - Cloud Integration\n      - Integration Flows\n      - OData\n      - Runtime Monitoring\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/integration-suite/sap-integration-suite/cloud-integration\n      - type: Reference\n        url: https://api.sap.com/api/CloudIntegrationAPI/overview\n      - type: OpenAPI\n        url: openapi/sap-integration-suite-cloud-integration-openapi.yml\n\
  \      - type: JSONSchema\n        url: json-schema/sap-integration-suite-integration-package-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-integration-suite-message-processing-log-schema.json\n      - type: JSONLD\n        url: json-ld/sap-integration-suite-context.jsonld\n      - type: Authentication\n        url: https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication\n\n  - aid: sap-integration-suite:sap-api-management\n    name: SAP API Management API\n    description: >-\n      The SAP API Management API enables programmatic management of APIs,\n      products, applications, and developer portals within SAP Integration\n      Suite. It supports creating and publishing API proxies, managing rate\n      plans, administering the full API lifecycle, configuring policies, and\n      managing developer portal content. Built on REST and OData principles.\n    humanURL: https://help.sap.com/docs/integration-suite/sap-integration-suite/api-management-capability\n\
  \    baseURL: https://{api-portal-host}/apiportal/api/1.0\n    tags:\n      - API Gateway\n      - API Management\n      - API Proxy\n      - Developer Portal\n      - OData\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/integration-suite/sap-integration-suite/api-management-capability\n      - type: Reference\n        url: https://api.sap.com/api/APIMgmt/overview\n      - type: OpenAPI\n        url: openapi/sap-integration-suite-api-management-openapi.yml\n      - type: JSONLD\n        url: json-ld/sap-integration-suite-context.jsonld\n      - type: Authentication\n        url: https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication\n\n  - aid: sap-integration-suite:sap-integration-advisor\n    name: SAP Integration Advisor API\n    description: >-\n      The SAP Integration Advisor API provides access to the library of message\n      implementation guidelines (MIGs) and mapping guidelines (MAGs)\
  \ used to\n      simplify B2B and A2A integration scenarios. It supports querying and\n      managing integration content including type systems, business context,\n      and codelists in the Integration Advisor capability.\n    humanURL: https://help.sap.com/docs/integration-suite/sap-integration-suite/integration-advisor-capability\n    baseURL: https://{host}/api\n    tags:\n      - B2B Integration\n      - EDI\n      - Integration Advisor\n      - Mapping Guidelines\n      - Message Implementation Guidelines\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/integration-suite/sap-integration-suite/integration-advisor-capability\n      - type: Reference\n        url: https://api.sap.com/api/IntegrationAdvisor/overview\n      - type: Authentication\n        url: https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication\n\n  - aid: sap-integration-suite:sap-open-connectors\n    name: SAP Open Connectors\
  \ API\n    description: >-\n      The SAP Open Connectors API (formerly Cloud Elements) provides a unified\n      REST interface to connect to over 160 third-party cloud applications using\n      pre-built connectors. It normalizes disparate API endpoints into consistent\n      resource models for faster integration development. Connectors are available\n      for CRM, ERP, marketing, storage, and collaboration platforms.\n    humanURL: https://help.sap.com/docs/integration-suite/sap-integration-suite/open-connectors-capability\n    baseURL: https://api.openconnectors.ext.hana.ondemand.com\n    tags:\n      - Cloud Connectors\n      - Normalization\n      - Open Connectors\n      - Third-Party Integration\n      - Unified API\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/integration-suite/sap-integration-suite/open-connectors-capability\n      - type: Reference\n        url: https://api.sap.com/api/OpenConnectors/overview\n      - type: Authentication\n\
  \        url: https://help.sap.com/docs/integration-suite/sap-integration-suite/open-connectors-capability\n\n  - aid: sap-integration-suite:sap-trading-partner-management\n    name: SAP Trading Partner Management API\n    description: >-\n      The SAP Trading Partner Management API supports setup and management of\n      B2B trading partner relationships, agreements, and communication channels\n      within SAP Integration Suite. It enables automation of partner onboarding,\n      maintenance of EDI and AS2 communication profiles, and management of\n      certificates and agreements.\n    humanURL: https://help.sap.com/docs/integration-suite/sap-integration-suite/trading-partner-management-capability\n    baseURL: https://{host}/api\n    tags:\n      - AS2\n      - B2B\n      - EDI\n      - Trading Partner Management\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/integration-suite/sap-integration-suite/trading-partner-management-capability\n   \
  \   - type: Reference\n        url: https://api.sap.com/api/TradingPartnerManagement/overview\n      - type: Authentication\n        url: https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication\n\n  - aid: sap-integration-suite:sap-event-mesh\n    name: SAP Event Mesh API\n    description: >-\n      The SAP Event Mesh API provides access to the event brokering service\n      within SAP Business Technology Platform that enables applications to\n      communicate through asynchronous events. It supports publishing and\n      subscribing to events across SAP and third-party applications using\n      CloudEvents standard and AMQP/MQTT/HTTP protocols.\n    humanURL: https://help.sap.com/docs/event-mesh\n    baseURL: https://enterprise-messaging.cfapps.sap.hana.ondemand.com\n    tags:\n      - Asynchronous\n      - CloudEvents\n      - Event Mesh\n      - Messaging\n      - Pub/Sub\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/event-mesh\n\
  \      - type: Reference\n        url: https://api.sap.com/api/SAPEventMesh/overview\n      - type: Authentication\n        url: https://help.sap.com/docs/event-mesh/sap-event-mesh/authentication-and-authorization\n\n  - aid: sap-integration-suite:sap-integration-suite-advanced-event-mesh\n    name: SAP Integration Suite Advanced Event Mesh API\n    description: >-\n      The SAP Integration Suite Advanced Event Mesh (AEM) REST API provides\n      management capabilities for event brokers, message queues, topic\n      subscriptions, and event broker services. It enables programmatic\n      management of messaging infrastructure including creation and monitoring\n      of event brokers and messaging services.\n    humanURL: https://help.pubsub.em.services.cloud.sap/Cloud/cloud-rest-api-lp.htm\n    baseURL: https://api.solacecloud.com/api/v2\n    tags:\n      - Advanced Event Mesh\n      - Broker Management\n      - Event Streaming\n      - Messaging\n      - REST\n    properties:\n    \
  \  - type: Documentation\n        url: https://help.pubsub.em.services.cloud.sap/Cloud/cloud-rest-api-lp.htm\n      - type: Reference\n        url: https://api.sap.com/package/SAPIIntegrationSuiteAdvancedEventMesh/rest\n      - type: Authentication\n        url: https://help.pubsub.em.services.cloud.sap/Cloud/ght_use_rest_api_services.htm\n\ncommon:\n  - type: Portal\n    url: https://api.sap.com/\n  - type: Documentation\n    url: https://help.sap.com/docs/integration-suite\n  - type: Website\n    url: https://www.sap.com/products/technology-platform/integration-suite.html\n  - type: Getting Started\n    url: https://help.sap.com/docs/integration-suite/sap-integration-suite/what-is-sap-integration-suite\n  - type: Authentication\n    url: https://help.sap.com/docs/integration-suite/sap-integration-suite/setting-up-oauth-inbound-authentication\n  - type: Blog\n    url: https://blogs.sap.com/tags/73554900100700002542/\n  - type: Community\n    url: https://community.sap.com/topics/integration-suite\n\
  \  - type: Support\n    url: https://support.sap.com/en/product/support-by-product/73554900100700002542.html\n  - type: Status\n    url: https://www.sap.com/about/trust-center/cloud-service-status.html\n  - type: GitHub Organization\n    url: https://github.com/SAP-samples\n  - type: Terms of Service\n    url: https://www.sap.com/about/agreements/policies/cloud-platform.html\n  - type: Privacy Policy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: YouTube\n    url: https://www.youtube.com/@SAPTechnology\n  - type: Pricing\n    url: https://www.sap.com/products/technology-platform/integration-suite/pricing.html\n  - type: Tutorials\n    url: https://developers.sap.com/tutorial-navigator.html?tag=software-product%3Atechnology-platform%2Fsap-integration-suite\n  - type: Vocabulary\n    url: vocabulary/sap-integration-suite-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/integration-lifecycle.yaml\n  - type: SpectralRules\n    url: rules/sap-integration-suite-rules.yml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap-integration-suite/refs/heads/main/apis.yml
tags:
- API Management
- Cloud Integration
- Enterprise Integration
- Event Mesh
- iPaaS
- SAP
- SAP BTP
url: https://raw.githubusercontent.com/api-evangelist/sap-integration-suite/refs/heads/main/apis.yml
use_cases: []
---
