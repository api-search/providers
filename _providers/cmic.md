---
api_count: 2
api_specs:
- filename: cmic-construction-erp-openapi.yml
  format: yaml
  label: CMiC Construction ERP API
  slug: cmic-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cmic/refs/heads/main/openapi/cmic-construction-erp-openapi.yml
apis:
- description: CMiC provides enterprise ERP and project management software for the construction industry. The REST API uses OAuth 2.0 (client credentials flow) with support for third-party identity providers like M
  name: CMiC Construction ERP API
  slug: cmic-api
- description: CMiC's Power BI Connector allows users to connect Microsoft Power BI directly to CMiC ERP data through the CMiC API, enabling business intelligence dashboards and reports for construction project fina
  name: CMiC API Power BI Connector
  slug: cmic-power-bi-connector
capabilities: []
common:
- title: ''
  type: Website
  url: https://cmicglobal.com/
- title: ''
  type: OpenAPI
  url: openapi/cmic-construction-erp-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/cmic-project-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/cmic-context.jsonld
- title: ''
  type: SpectralRuleset
  url: rules/cmic-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/cmic-construction-erp-capabilities.yml
- title: ''
  type: Portal
  url: https://developers.cmicglobal.com/
- title: ''
  type: Documentation
  url: https://docs.cmicglobal.com/portal/Content/Home.htm
- title: ''
  type: Authentication
  url: https://developers.cmicglobal.com/v1/docs/authentication
- title: ''
  type: GettingStarted
  url: https://developers.cmicglobal.com/docs/developer-api-account
- title: ''
  type: PrivacyPolicy
  url: https://cmicglobal.com/privacy-policy
- title: ''
  type: Blog
  url: https://cmicglobal.com/resources/
created: '2026-03-18'
description: CMiC is a unified construction-industry ERP and project management platform used by general contractors, civil contractors, and heavy/highway builders. CMiC exposes an OAuth 2.0 secured REST API (api.cmic.ca) along with a Power BI connector for accessing project financials, job costing, subcontractor and vendor management, equipment tracking, and document management with application-level security applied across company, job, project, and employee scopes.
features: []
image: https://raw.githubusercontent.com/api-evangelist/cmic/refs/heads/main/image.png
integrations: []
jsonld:
- class_count: 9
  name: Cmic Context
  property_count: 21
  slug: cmic-context
layout: provider
modified: '2026-04-23'
name: CMiC
rules:
- name: CMiC API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 5
  slug: cmic-rules
skills: []
slug: cmic
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cmic\nurl: https://raw.githubusercontent.com/api-evangelist/cmic/refs/heads/main/apis.yml\nname: CMiC\nx-type: company\ntags:\n  - Construction\n  - ERP\n  - Finance\n  - Project Management\ntype: Index\nimage: https://raw.githubusercontent.com/api-evangelist/cmic/refs/heads/main/image.png\naccess: 3rd-Party\ncreated: '2026-03-18'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\ndescription: >-\n  CMiC is a unified construction-industry ERP and project management platform\n  used by general contractors, civil contractors, and heavy/highway builders.\n  CMiC exposes an OAuth 2.0 secured REST API (api.cmic.ca) along with a Power BI\n  connector for accessing project financials, job costing, subcontractor and\n  vendor management, equipment tracking, and document management with\n  application-level security applied across company, job, project, and employee\n  scopes.\napis:\n  - aid: cmic:cmic-api\n    name: CMiC Construction ERP API\n    tags:\n      - Construction\n\
  \      - ERP\n      - Finance\n      - OAuth2\n      - Project Management\n    image: https://raw.githubusercontent.com/api-evangelist/cmic/refs/heads/main/image.png\n    humanURL: https://developers.cmicglobal.com/\n    baseURL: https://api.cmic.ca\n    properties:\n      - url: https://developers.cmicglobal.com/docs/overview\n        type: Documentation\n      - url: https://developers.cmicglobal.com/v1/docs/authentication\n        type: Authentication\n      - url: https://developers.cmicglobal.com/docs/developer-api-account\n        type: GettingStarted\n      - url: https://docs.cmicglobal.com/portal/Content/E_Reference_Material/CMiC_API/Reference/API_and_OAuth2/API_and_OAuth2.htm\n        type: Reference\n      - url: openapi/cmic-construction-erp-openapi.yml\n        type: OpenAPI\n      - url: json-schema/cmic-project-schema.json\n        type: JSONSchema\n      - url: json-ld/cmic-context.jsonld\n        type: JSONLDContext\n      - url: rules/cmic-rules.yml\n        type: SpectralRuleset\n\
  \      - url: capabilities/cmic-construction-erp-capabilities.yml\n        type: NaftikoCapabilities\n    description: >-\n      CMiC provides enterprise ERP and project management software for the\n      construction industry. The REST API uses OAuth 2.0 (client credentials\n      flow) with support for third-party identity providers like Microsoft\n      Azure. APIs enable access to project financials, subcontractor management,\n      job costing, equipment tracking, and document management.\n      Application-level security is enforced across all endpoints respecting\n      company, job, project, and employee access rules.\n    x-features:\n      - name: Project Management\n        description: List, create, retrieve, and update construction projects.\n      - name: Job Cost Tracking\n        description: Track jobs, cost codes, budgets, and committed costs.\n      - name: Subcontractor and Vendor Management\n        description: List and manage vendors and subcontractors per company.\n\
  \      - name: Equipment Tracking\n        description: Track equipment, usage, and assignment.\n      - name: Document Management\n        description: List and retrieve project documents and approvals.\n      - name: OAuth 2.0 Authentication\n        description: Client credentials flow with Microsoft Azure / external IdP support.\n    x-useCases:\n      - name: Project Financials Dashboard\n        description: Surface project, job, and cost-code data in BI tools.\n      - name: Subcontractor Onboarding\n        description: Sync vendor and subcontractor records into procurement systems.\n      - name: Equipment Utilization\n        description: Drive equipment-utilization reporting and predictive maintenance.\n      - name: Document Workflow Automation\n        description: Push and pull project documents into external review workflows.\n  - aid: cmic:cmic-power-bi-connector\n    name: CMiC API Power BI Connector\n    tags:\n      - Analytics\n      - Business Intelligence\n      -\
  \ Construction\n      - ERP\n      - Power BI\n    image: https://raw.githubusercontent.com/api-evangelist/cmic/refs/heads/main/image.png\n    humanURL: https://docs.cmicglobal.com/portal/Content/Home.htm\n    baseURL: https://api.cmic.ca\n    properties:\n      - url: https://docs.cmicglobal.com/portal/Content/Home.htm\n        type: Documentation\n    description: >-\n      CMiC's Power BI Connector allows users to connect Microsoft Power BI\n      directly to CMiC ERP data through the CMiC API, enabling business\n      intelligence dashboards and reports for construction project financials,\n      job costing, and operational metrics.\n    x-features:\n      - name: Power BI Native\n        description: Native Power BI connector for CMiC ERP data.\n      - name: Pre-Modeled Datasets\n        description: Pre-modeled construction-financial datasets out of the box.\n    x-useCases:\n      - name: Executive Dashboards\n        description: Build executive dashboards on CMiC project and\
  \ financial data.\n      - name: Job Profitability Analysis\n        description: Analyze profitability across jobs, cost codes, and projects.\ncommon:\n  - url: https://cmicglobal.com/\n    type: Website\n  - url: openapi/cmic-construction-erp-openapi.yml\n    type: OpenAPI\n  - url: json-schema/cmic-project-schema.json\n    type: JSONSchema\n  - url: json-ld/cmic-context.jsonld\n    type: JSONLDContext\n  - url: rules/cmic-rules.yml\n    type: SpectralRuleset\n  - url: capabilities/cmic-construction-erp-capabilities.yml\n    type: NaftikoCapabilities\n  - url: https://developers.cmicglobal.com/\n    type: Portal\n  - url: https://docs.cmicglobal.com/portal/Content/Home.htm\n    type: Documentation\n  - url: https://developers.cmicglobal.com/v1/docs/authentication\n    type: Authentication\n  - url: https://developers.cmicglobal.com/docs/developer-api-account\n    type: GettingStarted\n  - url: https://cmicglobal.com/integrations/api-bundles/\n    type: Integrations\n  - url: https://cmicglobal.com/privacy-policy\n\
  \    type: PrivacyPolicy\n  - url: https://cmicglobal.com/resources/\n    type: Blog\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cmic/refs/heads/main/apis.yml
tags:
- Construction
- ERP
- Finance
- Project Management
url: https://raw.githubusercontent.com/api-evangelist/cmic/refs/heads/main/apis.yml
use_cases: []
---
