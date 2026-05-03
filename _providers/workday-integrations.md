---
api_count: 4
api_specs:
- filename: openapi.json
  format: json
  label: Workday REST API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/restapi/openapi.json
- filename: workday-integrations-raas-openapi.yml
  format: yaml
  label: Workday RaaS (Report-as-a-Service)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-integrations/refs/heads/main/openapi/workday-integrations-raas-openapi.yml
- filename: workday-integrations-prism-analytics-openapi.yml
  format: yaml
  label: Workday Prism Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workday-integrations/refs/heads/main/openapi/workday-integrations-prism-analytics-openapi.yml
apis:
- description: Modern REST API for accessing Workday business objects including employees, organizations, positions, and more.
  name: Workday REST API
  slug: ''
- description: Comprehensive SOAP-based web services for deep integration with Workday including Human Capital Management, Financial Management, and custom integrations.
  name: Workday SOAP Web Services
  slug: ''
- description: Access custom and standard Workday reports as web services, enabling report data to be consumed by external systems.
  name: Workday RaaS (Report-as-a-Service)
  slug: ''
- description: API for loading external data into Workday Prism Analytics for advanced reporting and analytics capabilities.
  name: Workday Prism Analytics API
  slug: ''
common:
- title: ''
  type: Developer Portal
  url: https://community.workday.com/developer
- title: ''
  type: Authentication Guide
  url: https://doc.workday.com/admin-guide/en-us/integration/integration-security/authentication-overview.html
- title: ''
  type: Integration Cloud Platform
  url: https://www.workday.com/en-us/products/platform-product-extensions/workday-integration-cloud.html
- title: ''
  type: Studio
  url: https://doc.workday.com/admin-guide/en-us/integration/workday-studio/workday-studio-overview.html
- title: ''
  type: Community
  url: https://community.workday.com/
- title: ''
  type: Support
  url: https://www.workday.com/en-us/customer-experience/support.html
- title: ''
  type: Status Page
  url: https://status.workday.com/
- title: ''
  type: Terms of Service
  url: https://www.workday.com/en-us/legal.html
- title: ''
  type: Privacy Policy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: JSON-LD
  url: json-ld/workday-integrations-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/workday-integrations-worker-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/workday-integrations-organization-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/workday-integrations-position-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/workday-integrations-compensation-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/workday-integrations-dataset-schema.json
created: '2025-03-15'
description: Workday provides cloud-based enterprise software for finance, HR, and planning. This APIs.json file describes the integration capabilities and APIs available for connecting Workday with other systems.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Workday Integrations Context
  property_count: 11
  slug: workday-integrations-context
layout: provider
modified: '2026-03-16'
name: Workday Integrations
skills: []
slug: workday-integrations
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: workday-integrations\nname: Workday Integrations\ndescription: Workday provides cloud-based enterprise software for finance, HR, and planning. This APIs.json file describes the integration capabilities and APIs available for connecting Workday with other systems.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: '2025-03-15'\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday-integrations/refs/heads/main/apis.yml\napis:\n  - name: Workday REST API\n    description: Modern REST API for accessing Workday business objects including employees, organizations, positions, and more.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/v1/{tenant}\n    tags:\n      - Enterprise\n\
  \      - Finance\n      - HR\n      - REST\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/openapi.json\n      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-authentication.html\n      - type: Rate Limits\n        url: https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-rate-limiting.html\n      - type: OpenAPI\n        url: openapi/workday-integrations-rest-api-openapi.yml\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n        url: https://www.workday.com/en-us/customer-experience/support.html\n  - name: Workday SOAP Web Services\n    description: Comprehensive SOAP-based web services for deep integration with Workday including Human Capital Management, Financial Management,\
  \ and custom integrations.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service/{tenant}\n    tags:\n      - Finance\n      - HCM\n      - Integration\n      - SOAP\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: WSDL\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/versions.html\n      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/integration/web-services/web-services-authentication.html\n      - type: Integration Guide\n        url: https://doc.workday.com/admin-guide/en-us/integration/integration-overview.html\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n\
  \        url: https://www.workday.com/en-us/customer-experience/support.html\n  - name: Workday RaaS (Report-as-a-Service)\n    description: Access custom and standard Workday reports as web services, enabling report data to be consumed by external systems.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanURL: https://doc.workday.com/admin-guide/en-us/integration/workday-reports/report-as-a-service-raas.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service/customreport2/{tenant}\n    tags:\n      - Analytics\n      - Custom Reports\n      - Data Export\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://doc.workday.com/admin-guide/en-us/integration/workday-reports/report-as-a-service-raas.html\n      - type: Tutorial\n        url: https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/CIe8xMH~H~b1Cq7IqRfGHQ\n      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/integration/web-services/web-services-authentication.html\n\
  \      - type: OpenAPI\n        url: openapi/workday-integrations-raas-openapi.yml\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\n  - name: Workday Prism Analytics API\n    description: API for loading external data into Workday Prism Analytics for advanced reporting and analytics capabilities.\n    image: https://www.workday.com/content/dam/web/en-us/images/logos/workday-logo.svg\n    humanURL: https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/prismAnalytics/v2/{tenant}\n    tags:\n      - Analytics\n      - Data Loading\n      - External Data\n      - Prism\n    properties:\n      - type: Documentation\n        url: https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html\n      - type: API Reference\n        url: https://community.workday.com/sites/default/files/file-hosting/prism-analytics-api/index.html\n\
  \      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-authentication.html\n      - type: OpenAPI\n        url: openapi/workday-integrations-prism-analytics-openapi.yml\n    contact:\n      - FN: Workday Support\n        email: support@workday.com\ncommon:\n  - type: Developer Portal\n    url: https://community.workday.com/developer\n  - type: Authentication Guide\n    url: https://doc.workday.com/admin-guide/en-us/integration/integration-security/authentication-overview.html\n  - type: Integration Cloud Platform\n    url: https://www.workday.com/en-us/products/platform-product-extensions/workday-integration-cloud.html\n  - type: Studio\n    url: https://doc.workday.com/admin-guide/en-us/integration/workday-studio/workday-studio-overview.html\n  - type: Community\n    url: https://community.workday.com/\n  - type: Support\n    url: https://www.workday.com/en-us/customer-experience/support.html\n  - type: Status Page\n   \
  \ url: https://status.workday.com/\n  - type: Terms of Service\n    url: https://www.workday.com/en-us/legal.html\n  - type: Privacy Policy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: JSON-LD\n    url: json-ld/workday-integrations-context.jsonld\n  - type: JSONSchema\n    url: json-schema/workday-integrations-worker-schema.json\n  - type: JSONSchema\n    url: json-schema/workday-integrations-organization-schema.json\n  - type: JSONSchema\n    url: json-schema/workday-integrations-position-schema.json\n  - type: JSONSchema\n    url: json-schema/workday-integrations-compensation-schema.json\n  - type: JSONSchema\n    url: json-schema/workday-integrations-dataset-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Cloud\n  - Enterprise Software\n  - ERP\n  - Finance\n  - HCM\n  - HR\n  - Integration\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday-integrations/refs/heads/main/apis.yml
tags:
- Cloud
- Enterprise Software
- ERP
- Finance
- HCM
- HR
- Integration
url: https://raw.githubusercontent.com/api-evangelist/workday-integrations/refs/heads/main/apis.yml
use_cases: []
---
