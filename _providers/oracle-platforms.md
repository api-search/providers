---
api_count: 8
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Oracle Cloud Infrastructure (OCI) REST API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en-us/iaas/api/#/en/iaas/latest/
- filename: openapi.yaml
  format: yaml
  label: Oracle Autonomous Database API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en-us/iaas/api/#/en/database/latest/
- filename: api-integration-cloud.html
  format: yaml
  label: Oracle Integration Cloud API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/paas/integration-cloud/rest-api/api-integration-cloud.html
- filename: api-rest.html
  format: yaml
  label: Oracle Analytics Cloud API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/paas/analytics-cloud/acapi/api-rest.html
- filename: openapi.yaml
  format: yaml
  label: Oracle Cloud Infrastructure Data Science API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en-us/iaas/api/#/en/data-science/latest/
apis:
- description: Comprehensive REST API for managing Oracle Cloud Infrastructure resources including compute, storage, networking, and databases.
  name: Oracle Cloud Infrastructure (OCI) REST API
  slug: ''
- description: API for managing Oracle Autonomous Database instances with self-driving, self-securing, and self-repairing capabilities.
  name: Oracle Autonomous Database API
  slug: ''
- description: REST API for Oracle Integration Cloud enabling application integration, process automation, and API management.
  name: Oracle Integration Cloud API
  slug: ''
- description: RESTful API for Oracle Content Management providing digital asset management and content collaboration.
  name: Oracle Content Management API
  slug: ''
- description: REST API for Oracle Fusion Cloud ERP providing access to financial management, procurement, and project management capabilities.
  name: Oracle Fusion Cloud ERP API
  slug: ''
- description: RESTful API for Oracle Analytics Cloud enabling data visualization, analytics, and business intelligence operations.
  name: Oracle Analytics Cloud API
  slug: ''
- description: API for managing machine learning models, notebook sessions, and data science projects.
  name: Oracle Cloud Infrastructure Data Science API
  slug: ''
- description: RESTful services for Oracle Application Express enabling low-code application development.
  name: Oracle APEX REST APIs
  slug: ''
common: []
created: '2024-01-15'
description: A collection of APIs and services provided by Oracle's cloud and enterprise platforms.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-16'
name: Oracle Platforms
skills: []
slug: oracle-platforms
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oracle-platforms\nname: Oracle Platforms\ndescription: >-\n  A collection of APIs and services provided by Oracle's cloud and enterprise platforms.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: '2024-01-15'\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-platforms/refs/heads/main/apis.yml\napis:\n  - name: Oracle Cloud Infrastructure (OCI) REST API\n    description: >-\n      Comprehensive REST API for managing Oracle Cloud Infrastructure resources including\n      compute, storage, networking, and databases.\n    image: https://www.oracle.com/cloud/img/social-og-oracle-cloud.jpg\n    humanURL: https://docs.oracle.com/en-us/iaas/api/\n    baseURL: https://iaas.{region}.oraclecloud.com\n    tags:\n      - Cloud\n      - Compute\n      - IaaS\n      - Infrastructure\n      - Storage\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.oracle.com/en-us/iaas/api/\n      - type: OpenAPI\n        url: https://docs.oracle.com/en-us/iaas/api/#/en/iaas/latest/\n      - type: Authentication\n        url: https://docs.oracle.com/en-us/iaas/Content/API/Concepts/apisigningkey.htm\n      - type: Rate Limits\n        url: https://docs.oracle.com/en-us/iaas/Content/API/Concepts/apithrottling.htm\n      - type: SDK\n        url: https://docs.oracle.com/en-us/iaas/Content/API/Concepts/sdks.htm\n  - name: Oracle Autonomous Database API\n    description: >-\n      API for managing Oracle Autonomous Database instances with self-driving, self-securing,\n      and self-repairing capabilities.\n    humanURL: https://docs.oracle.com/en/cloud/paas/autonomous-database/\n    baseURL: https://database.{region}.oraclecloud.com\n    tags:\n      - Autonomous\n      - Database\n      - DBaaS\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/paas/autonomous-database/adbsa/\n\
  \      - type: OpenAPI\n        url: https://docs.oracle.com/en-us/iaas/api/#/en/database/latest/\n      - type: Pricing\n        url: https://www.oracle.com/cloud/price-list.html\n  - name: Oracle Integration Cloud API\n    description: >-\n      REST API for Oracle Integration Cloud enabling application integration, process\n      automation, and API management.\n    humanURL: https://docs.oracle.com/en/cloud/paas/integration-cloud/\n    baseURL: https://integration.ocp.oraclecloud.com\n    tags:\n      - API Management\n      - Automation\n      - Integration\n      - iPaaS\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/paas/integration-cloud/rest-api/\n      - type: OpenAPI\n        url: https://docs.oracle.com/en/cloud/paas/integration-cloud/rest-api/api-integration-cloud.html\n  - name: Oracle Content Management API\n    description: >-\n      RESTful API for Oracle Content Management providing digital asset management\n      and content\
  \ collaboration.\n    humanURL: https://docs.oracle.com/en/cloud/paas/content-cloud/\n    baseURL: https://www.oraclecloud.com/content/api\n    tags:\n      - CMS\n      - Collaboration\n      - Content Management\n      - Digital Assets\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/paas/content-cloud/rest-api-documents/\n      - type: SDK\n        url: https://github.com/oracle/content-management-sdk\n  - name: Oracle Fusion Cloud ERP API\n    description: >-\n      REST API for Oracle Fusion Cloud ERP providing access to financial management,\n      procurement, and project management capabilities.\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/\n    baseURL: https://servername.fa.us2.oraclecloud.com\n    tags:\n      - Cloud Applications\n      - ERP\n      - Finance\n      - Procurement\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/farsw/\n      - type: WADL\n\
  \        url: https://docs.oracle.com/en/cloud/saas/financials/farsw/rest-endpoints.html\n  - name: Oracle Analytics Cloud API\n    description: >-\n      RESTful API for Oracle Analytics Cloud enabling data visualization, analytics,\n      and business intelligence operations.\n    humanURL: https://docs.oracle.com/en/cloud/paas/analytics-cloud/\n    baseURL: https://{instanceName}.analytics.ocp.oraclecloud.com\n    tags:\n      - Analytics\n      - Business Intelligence\n      - Data Visualization\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/paas/analytics-cloud/acapi/\n      - type: OpenAPI\n        url: https://docs.oracle.com/en/cloud/paas/analytics-cloud/acapi/api-rest.html\n  - name: Oracle Cloud Infrastructure Data Science API\n    description: >-\n      API for managing machine learning models, notebook sessions, and data science\n      projects.\n    humanURL: https://docs.oracle.com/en-us/iaas/data-science/\n\
  \    baseURL: https://datascience.{region}.oraclecloud.com\n    tags:\n      - AI\n      - Data Science\n      - Machine Learning\n      - MLOps\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en-us/iaas/api/#/en/data-science/latest/\n      - type: OpenAPI\n        url: https://docs.oracle.com/en-us/iaas/api/#/en/data-science/latest/\n  - name: Oracle APEX REST APIs\n    description: >-\n      RESTful services for Oracle Application Express enabling low-code application\n      development.\n    humanURL: https://apex.oracle.com/api\n    baseURL: https://{instance}.adb.{region}.oraclecloudapps.com\n    tags:\n      - APEX\n      - Application Development\n      - Low-Code\n      - REST Services\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/apex/latest/\n      - type: Tutorials\n        url: https://apex.oracle.com/en/learn/tutorials/\ninclude:\n  - name: Oracle Developer Portal\n    url: https://developer.oracle.com/\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Analytics\n  - Cloud Computing\n  - Database\n  - Enterprise Software\n  - Infrastructure as a Service\n  - Integration\n  - Machine Learning\n  - Platform as a Service\n  - SaaS\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-platforms/refs/heads/main/apis.yml
tags:
- Analytics
- Cloud Computing
- Database
- Enterprise Software
- Infrastructure as a Service
- Integration
- Machine Learning
- Platform as a Service
- SaaS
url: https://raw.githubusercontent.com/api-evangelist/oracle-platforms/refs/heads/main/apis.yml
use_cases: []
---
