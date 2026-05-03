---
api_count: 4
api_specs:
- filename: sap-api-management-portal-openapi.yml
  format: yaml
  label: SAP API Management API Portal API
  slug: sap-api-management-api-portal
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-api-management/refs/heads/main/openapi/sap-api-management-portal-openapi.yml
apis:
- description: The SAP API Management API provides programmatic access to manage APIs, API products, developer portal settings, and access control through the SAP API Management platform on SAP Business Technology P
  name: SAP API Management API
  slug: sap-api-management
- description: The SAP API Management API Portal API provides RESTful endpoints for programmatically managing API proxies, API products, applications, developers, policies, and key-value maps within the SAP API Mana
  name: SAP API Management API Portal API
  slug: sap-api-management-api-portal
- description: The SAP API Business Hub Enterprise (also called API Management Developer Portal) API enables programmatic management of the self-service developer portal. It supports managing API catalog content, de
  name: SAP API Business Hub Enterprise API
  slug: sap-api-business-hub-enterprise
- description: The SAP API Management Analytics API provides access to API usage metrics, performance statistics, error rates, and traffic analytics for APIs managed on the SAP API Management platform. It supports b
  name: SAP API Management Analytics API
  slug: sap-api-management-analytics
capabilities:
- description: Unified capability for managing the full API lifecycle in SAP API Management. Combines the API Portal management API to support end-to-end workflows for API platform engineers, integration architects,
  name: SAP API Lifecycle Management
  slug: api-lifecycle-management
common:
- title: ''
  type: Portal
  url: https://api.sap.com/
- title: ''
  type: Documentation
  url: https://help.sap.com/docs/sap-api-management
- title: ''
  type: Website
  url: https://www.sap.com/products/technology-platform/api-management.html
- title: ''
  type: Getting Started
  url: https://help.sap.com/docs/sap-api-management/sap-api-management/what-is-api-management
- title: ''
  type: Authentication
  url: https://help.sap.com/docs/sap-api-management/sap-api-management/user-authentication
- title: ''
  type: Blog
  url: https://blogs.sap.com/tags/73554900100700002381/
- title: ''
  type: Community
  url: https://community.sap.com/topics/api-management
- title: ''
  type: Support
  url: https://support.sap.com/en/product/support-by-product/73554900100700002381.html
- title: ''
  type: Status
  url: https://www.sap.com/about/trust-center/cloud-service-status.html
- title: ''
  type: GitHub Organization
  url: https://github.com/SAP-samples
- title: ''
  type: GitHubRepository
  url: https://github.com/SAP/apibusinesshub-api-recipes
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
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/sap-api-management
- title: ''
  type: Vocabulary
  url: vocabulary/sap-api-management-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/sap-api-management-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/api-lifecycle-management.yaml
- title: ''
  type: JSONLD
  url: json-ld/sap-api-management-context.jsonld
created: '2026-03-16'
description: SAP API Management is an API platform that enables organizations to design, import, publish, secure, and monitor APIs. It provides a self-service developer portal (API Business Hub Enterprise), OpenAPI-based API design tools, policy management, and access to the SAP Business Accelerator Hub for discovering and consuming SAP and partner APIs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Sap Api Management Context
  property_count: 12
  slug: sap-api-management-context
layout: provider
modified: '2026-05-02'
name: SAP API Management
rules:
- name: SAP API Management API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 3
  slug: sap-api-management-rules
skills: []
slug: sap-api-management
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sap-api-management\nname: SAP API Management\ndescription: >-\n  SAP API Management is an API platform that enables organizations to design,\n  import, publish, secure, and monitor APIs. It provides a self-service\n  developer portal (API Business Hub Enterprise), OpenAPI-based API design tools,\n  policy management, and access to the SAP Business Accelerator Hub for\n  discovering and consuming SAP and partner APIs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Management\n  - Developer Portal\n  - Enterprise\n  - SAP\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sap-api-management/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nx-profiled: '2026-05'\nspecificationVersion: '0.19'\napis:\n  - aid: sap-api-management:sap-api-management\n    name: SAP API Management API\n    description: >-\n      The SAP API Management API provides programmatic access to manage APIs,\n\
  \      API products, developer portal settings, and access control through the\n      SAP API Management platform on SAP Business Technology Platform.\n    humanURL: https://help.sap.com/docs/sap-api-management\n    tags:\n      - API Management\n      - Developer Portal\n      - SAP BTP\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/sap-api-management\n      - type: Reference\n        url: https://api.sap.com/package/APIMgmt/overview\n      - type: Getting Started\n        url: https://help.sap.com/docs/sap-api-management/sap-api-management/what-is-api-management\n      - type: Authentication\n        url: https://help.sap.com/docs/sap-api-management/sap-api-management/user-authentication\n  - aid: sap-api-management:sap-api-management-api-portal\n    name: SAP API Management API Portal API\n    description: >-\n      The SAP API Management API Portal API provides RESTful endpoints for\n      programmatically managing API proxies, API products, applications,\n\
  \      developers, policies, and key-value maps within the SAP API Management\n      platform. It is used by administrators and developers to automate the\n      full API lifecycle including creation, versioning, and publishing of APIs.\n      The API uses OData conventions with base URL:\n      https://{tenant-url}/apiportal/api/1.0/Management.svc.\n    humanURL: https://help.sap.com/docs/sap-api-management/sap-api-management/build-apis\n    tags:\n      - API Lifecycle\n      - API Portal\n      - API Proxy\n      - REST\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/sap-api-management/sap-api-management/build-apis\n      - type: Reference\n        url: https://api.sap.com/api/APIMgmt/overview\n      - type: GitHubRepository\n        url: https://github.com/SAP/apibusinesshub-api-recipes\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sap-api-management/refs/heads/main/openapi/sap-api-management-portal-openapi.yml\n\
  \      - type: JSONSchema\n        url: json-schema/sap-api-management-api-proxy-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-api-management-api-product-schema.json\n  - aid: sap-api-management:sap-api-business-hub-enterprise\n    name: SAP API Business Hub Enterprise API\n    description: >-\n      The SAP API Business Hub Enterprise (also called API Management Developer\n      Portal) API enables programmatic management of the self-service developer\n      portal. It supports managing API catalog content, developer registrations,\n      application subscriptions, and portal customizations for consumer-facing\n      API discovery and consumption.\n    humanURL: https://help.sap.com/docs/sap-api-management/sap-api-management/consume-apis\n    tags:\n      - API Catalog\n      - Developer Portal\n      - SAP BTP\n      - Self Service\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/sap-api-management/sap-api-management/consume-apis\n\
  \      - type: Reference\n        url: https://api.sap.com/api/APIMgmtDevPortal/overview\n  - aid: sap-api-management:sap-api-management-analytics\n    name: SAP API Management Analytics API\n    description: >-\n      The SAP API Management Analytics API provides access to API usage metrics,\n      performance statistics, error rates, and traffic analytics for APIs\n      managed on the SAP API Management platform. It supports building custom\n      dashboards and monitoring integrations using aggregated and raw usage data.\n    humanURL: https://help.sap.com/docs/sap-api-management/sap-api-management/analyze-apis\n    tags:\n      - Analytics\n      - Metrics\n      - Monitoring\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/sap-api-management/sap-api-management/analyze-apis\n      - type: Reference\n        url: https://api.sap.com/api/APIMgmtAnalytics/overview\ncommon:\n  - type: Portal\n    url: https://api.sap.com/\n  - type:\
  \ Documentation\n    url: https://help.sap.com/docs/sap-api-management\n  - type: Website\n    url: https://www.sap.com/products/technology-platform/api-management.html\n  - type: Getting Started\n    url: https://help.sap.com/docs/sap-api-management/sap-api-management/what-is-api-management\n  - type: Authentication\n    url: https://help.sap.com/docs/sap-api-management/sap-api-management/user-authentication\n  - type: Blog\n    url: https://blogs.sap.com/tags/73554900100700002381/\n  - type: Community\n    url: https://community.sap.com/topics/api-management\n  - type: Support\n    url: https://support.sap.com/en/product/support-by-product/73554900100700002381.html\n  - type: Status\n    url: https://www.sap.com/about/trust-center/cloud-service-status.html\n  - type: GitHub Organization\n    url: https://github.com/SAP-samples\n  - type: GitHubRepository\n    url: https://github.com/SAP/apibusinesshub-api-recipes\n  - type: Terms of Service\n    url: https://www.sap.com/about/agreements/policies/cloud-platform.html\n\
  \  - type: Privacy Policy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: YouTube\n    url: https://www.youtube.com/@SAPTechnology\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/sap-api-management\n  - type: Vocabulary\n    url: vocabulary/sap-api-management-vocabulary.yml\n  - type: SpectralRules\n    url: rules/sap-api-management-rules.yml\n  - type: Capabilities\n    url: capabilities/api-lifecycle-management.yaml\n  - type: JSONLD\n    url: json-ld/sap-api-management-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap-api-management/refs/heads/main/apis.yml
tags:
- API Management
- Developer Portal
- Enterprise
- SAP
url: https://raw.githubusercontent.com/api-evangelist/sap-api-management/refs/heads/main/apis.yml
use_cases: []
---
