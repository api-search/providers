---
api_count: 2
api_specs:
- filename: cch-tagetik-odata-openapi.yml
  format: yaml
  label: CCH Tagetik OData API
  slug: cch-tagetik-odata-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/openapi/cch-tagetik-odata-openapi.yml
apis:
- description: OData v4 REST API providing read access to CCH Tagetik financial and analytical workspace data. Enables external tools such as Power BI, Qlik, and custom integrations to query financial models, consol
  name: CCH Tagetik OData API
  slug: cch-tagetik-odata-api
- description: 'SCIM v2 (System for Cross-domain Identity Management) API for automated user provisioning and deprovisioning in CCH Tagetik. Supports synchronizing users and groups from Microsoft Entra ID (Azure AD) '
  name: CCH Tagetik SCIM API
  slug: cch-tagetik-scim-api
capabilities:
- description: Workflow capability for finance teams and BI analysts to query CCH Tagetik financial consolidation and analytical workspace data. Covers actual results, budget comparisons, forecasts, and multi-dimens
  name: CCH Tagetik Financial Reporting
  slug: financial-reporting
common:
- title: ''
  type: Website
  url: https://www.wolterskluwer.com/en/solutions/cch-tagetik
- title: ''
  type: Documentation
  url: https://help.tagetik.com
- title: ''
  type: Technology Integrations
  url: https://www.wolterskluwer.com/en/solutions/cch-tagetik/technology-integrations
- title: ''
  type: Support
  url: https://www.wolterskluwer.com/en/solutions/cch-tagetik/services/support
- title: ''
  type: Power BI Integration
  url: https://learn.microsoft.com/en-us/power-query/connectors/wolters-kluwer-cch-tagetik
- title: ''
  type: Azure AD SSO Tutorial
  url: https://learn.microsoft.com/azure/active-directory/saas-apps/cch-tagetik-tutorial
- title: ''
  type: Training
  url: https://www.academy.registration.tagetik.com
- title: ''
  type: JSON Schema
  url: https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/json-schema/cch-tagetik-financial-record-schema.json
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/vocabulary/tagetik-vocabulary.yml
created: '2025-01-15'
description: CCH Tagetik (a Wolters Kluwer solution) is a comprehensive Corporate Performance Management platform covering financial close and consolidation, extended planning and analysis, ESG and regulatory reporting, and corporate tax management. The platform exposes data via OData v4 REST APIs and SCIM, enabling integration with Power BI, Qlik, SAP HANA, and other BI tools. OAuth 2.0 and Basic Authentication are supported for secure access.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Tagetik Context
  property_count: 20
  slug: tagetik-context
layout: provider
modified: '2026-05-03'
name: CCH Tagetik
rules:
- name: CCH Tagetik API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 4
  slug: cch-tagetik-odata-rules
skills: []
slug: tagetik
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tagetik\nname: CCH Tagetik\ndescription: >-\n  CCH Tagetik (a Wolters Kluwer solution) is a comprehensive Corporate\n  Performance Management platform covering financial close and consolidation,\n  extended planning and analysis, ESG and regulatory reporting, and corporate\n  tax management. The platform exposes data via OData v4 REST APIs and SCIM,\n  enabling integration with Power BI, Qlik, SAP HANA, and other BI tools.\n  OAuth 2.0 and Basic Authentication are supported for secure access.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Budgeting\n  - Corporate Performance Management\n  - ESG\n  - Financial Close\n  - Financial Consolidation\n  - Financial Planning\n  - OData\n  - Reporting\ncreated: '2025-01-15'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\n\
  apis:\n  - aid: tagetik:cch-tagetik-odata-api\n    name: CCH Tagetik OData API\n    description: >-\n      OData v4 REST API providing read access to CCH Tagetik financial and\n      analytical workspace data. Enables external tools such as Power BI, Qlik,\n      and custom integrations to query financial models, consolidation data,\n      and analytical workspace datasets. Supports Basic Authentication and\n      OAuth 2.0 Client Credentials flow. Available from CCH Tagetik Service\n      Pack 23 (version 5.3+).\n    humanURL: https://www.wolterskluwer.com/en/solutions/cch-tagetik/technology-integrations\n    baseURL: https://{your-tagetik-environment}/\n    tags:\n      - Financial Data\n      - Integration\n      - OData\n      - REST\n    properties:\n      - type: Documentation\n        url: https://help.tagetik.com\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-query/connectors/wolters-kluwer-cch-tagetik\n      - type: Power BI Connector\n   \
  \     url: https://learn.microsoft.com/en-us/power-query/connectors/wolters-kluwer-cch-tagetik\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/openapi/cch-tagetik-odata-openapi.yml\n  - aid: tagetik:cch-tagetik-scim-api\n    name: CCH Tagetik SCIM API\n    description: >-\n      SCIM v2 (System for Cross-domain Identity Management) API for automated\n      user provisioning and deprovisioning in CCH Tagetik. Supports\n      synchronizing users and groups from Microsoft Entra ID (Azure AD) and\n      other identity providers.\n    humanURL: https://www.wolterskluwer.com/en/solutions/cch-tagetik/technology-integrations\n    baseURL: https://{your-tagetik-environment}/scim/v2\n    tags:\n      - Identity Management\n      - SCIM\n      - User Provisioning\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/azure/active-directory/saas-apps/cch-tagetik-tutorial\ncommon:\n  - type:\
  \ Website\n    url: https://www.wolterskluwer.com/en/solutions/cch-tagetik\n  - type: Documentation\n    url: https://help.tagetik.com\n  - type: Technology Integrations\n    url: https://www.wolterskluwer.com/en/solutions/cch-tagetik/technology-integrations\n  - type: Support\n    url: https://www.wolterskluwer.com/en/solutions/cch-tagetik/services/support\n  - type: Power BI Integration\n    url: https://learn.microsoft.com/en-us/power-query/connectors/wolters-kluwer-cch-tagetik\n  - type: Azure AD SSO Tutorial\n    url: https://learn.microsoft.com/azure/active-directory/saas-apps/cch-tagetik-tutorial\n  - type: Training\n    url: https://www.academy.registration.tagetik.com\n  - type: JSON Schema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/json-schema/cch-tagetik-financial-record-schema.json\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/vocabulary/tagetik-vocabulary.yml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/apis.yml
tags:
- Analytics
- Budgeting
- Corporate Performance Management
- ESG
- Financial Close
- Financial Consolidation
- Financial Planning
- OData
- Reporting
url: https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/apis.yml
use_cases: []
---
