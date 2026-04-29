---
api_count: 1
api_specs:
- filename: productiv-developer-openapi.yml
  format: yaml
  label: Productiv Developer API
  slug: developer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/productiv/refs/heads/main/openapi/productiv-developer-openapi.yml
apis:
- description: The Productiv Developer APIs support integrating custom applications into the Productiv platform, allowing external developers to define and publish new connected applications. Includes APIs for pushi
  name: Productiv Developer API
  slug: developer-api
capabilities:
- description: Unified workflow for managing SaaS applications, tracking usage and spend, provisioning users, and auditing platform activity using the Productiv Developer API.
  name: Productiv SaaS Management
  slug: saas-management
common:
- title: ''
  type: Documentation
  url: https://docs.app.productiv.com/
- title: ''
  type: DeveloperPortal
  url: https://productiv.com/
- title: ''
  type: Authentication
  url: https://docs.app.productiv.com/developer-api/authorization.html
- title: ''
  type: Rules
  url: rules/productiv-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/productiv-vocabulary.yaml
- title: ''
  type: Capabilities
  url: capabilities/shared/developer-api.yaml
- title: ''
  type: Capabilities
  url: capabilities/saas-management.yaml
created: '2025-07-11'
description: The SaaS Management Platform that delivers the industrys most comprehensive view of your SaaS portfolio with deep usage analytics, spend data, and feature-level insights to power the technology decisions that support your business.
features:
- name: SaaS Portfolio Management
- name: Usage Analytics
- name: Spend Data Tracking
- name: Provisioning Workflows
- name: Audit Events
- name: Org Chart Integration
- name: Custom Application Connectors
- name: Batch File Upload
- name: Data Export
- name: OAuth2 Authentication
image: /assets/icons/productiv.png
integrations:
- name: Okta
- name: Azure Active Directory
- name: Salesforce
- name: ServiceNow
- name: Workday
- name: Slack
jsonld:
- class_count: 49
  name: Productiv Context
  property_count: 5
  slug: productiv-context
- class_count: 0
  name: Productiv Developer Context
  property_count: 0
  slug: productiv-developer-context
layout: provider
modified: '2026-04-18'
name: Productiv
rules:
- name: Productiv API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: productiv-spectral-rules
skills: []
slug: productiv
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: productiv\nname: Productiv\ndescription: >-\n  The SaaS Management Platform that delivers the industrys most comprehensive\n  view of your SaaS portfolio with deep usage analytics, spend data, and\n  feature-level insights to power the technology decisions that support your\n  business.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Application Portfolio\n  - Provisioning\n  - SaaS Management\n  - Spend Management\n  - Usage Analytics\ncreated: '2025-07-11'\nmodified: '2026-04-18'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/productiv/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: productiv:developer-api\n    name: Productiv Developer API\n    description: >-\n      The Productiv Developer APIs support integrating custom applications into\n      the Productiv platform, allowing external developers to define and publish\n      new connected\
  \ applications. Includes APIs for pushing usage events and\n      user information, Data Export APIs for fetching app portfolio details,\n      provisioning workflows, and audit events.\n    humanURL: https://docs.app.productiv.com/developer-api/index.html\n    baseURL: https://public-api.productiv.com\n    tags:\n      - Application Portfolio\n      - Audit Events\n      - Data Export\n      - Provisioning\n      - SaaS Management\n      - Spend Data\n      - Usage Analytics\n    properties:\n      - type: Documentation\n        url: https://docs.app.productiv.com/developer-api/index.html\n      - type: OpenAPI\n        url: openapi/productiv-developer-openapi.yml\n      - type: Authentication\n        url: https://docs.app.productiv.com/developer-api/authorization.html\n      - type: GettingStarted\n        url: https://docs.app.productiv.com/developer-api/data-export-getting-started.html\n      - type: JSONSchema\n        url: json-schema/application.json\n      - type: JSONSchema\n\
  \        url: json-schema/app-summary.json\n      - type: JSONSchema\n        url: json-schema/app-details.json\n      - type: JSONSchema\n        url: json-schema/usage-event.json\n      - type: JSONSchema\n        url: json-schema/spend-data.json\n      - type: JSONSchema\n        url: json-schema/provisioned-user.json\n      - type: JSONSchema\n        url: json-schema/org-chart-user.json\n      - type: JSONSchema\n        url: json-schema/provisioning-workflow.json\n      - type: JSONSchema\n        url: json-schema/audit-event.json\n      - type: JSONLD\n        url: json-ld/productiv-context.jsonld\ncommon:\n  - url: https://docs.app.productiv.com/\n    name: Documentation\n    type: Documentation\n    description: 'null'\n  - url: https://productiv.com/\n    name: Website\n    type: DeveloperPortal\n    description: 'null'\n  - url: https://docs.app.productiv.com/developer-api/authorization.html\n    name: Authentication\n    type: Authentication\n    description: 'null'\n  - name:\
  \ Features\n    type: Features\n    data:\n      - name: SaaS Portfolio Management\n      - name: Usage Analytics\n      - name: Spend Data Tracking\n      - name: Provisioning Workflows\n      - name: Audit Events\n      - name: Org Chart Integration\n      - name: Custom Application Connectors\n      - name: Batch File Upload\n      - name: Data Export\n      - name: OAuth2 Authentication\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Track SaaS Application Usage\n      - name: Optimize Software Spend\n      - name: Automate User Provisioning\n      - name: Audit Platform Activity\n      - name: Integrate Custom Applications\n      - name: Export App Portfolio Data\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Okta\n      - name: Azure Active Directory\n      - name: Salesforce\n      - name: ServiceNow\n      - name: Workday\n      - name: Slack\n  - url: rules/productiv-spectral-rules.yml\n    type: Rules\n  - url: vocabulary/productiv-vocabulary.yaml\n\
  \    type: Vocabulary\n  - url: capabilities/shared/developer-api.yaml\n    type: Capabilities\n  - url: capabilities/saas-management.yaml\n    type: Capabilities\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/productiv/refs/heads/main/apis.yml
tags:
- Application Portfolio
- Provisioning
- SaaS Management
- Spend Management
- Usage Analytics
url: https://raw.githubusercontent.com/api-evangelist/productiv/refs/heads/main/apis.yml
use_cases:
- name: Track SaaS Application Usage
- name: Optimize Software Spend
- name: Automate User Provisioning
- name: Audit Platform Activity
- name: Integrate Custom Applications
- name: Export App Portfolio Data
---
