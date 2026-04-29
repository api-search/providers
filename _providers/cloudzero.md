---
api_count: 7
api_specs:
- filename: cloudzero-api-openapi.yml
  format: yaml
  label: CloudZero API
  slug: api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cloudzero/refs/heads/main/openapi/cloudzero-api-openapi.yml
apis:
- description: The CloudZero API V2 enables you to automate the collection, allocation, and analysis of your infrastructure spend. It provides endpoints for querying billing costs and dimensions, managing insights a
  name: CloudZero API
  slug: api
- description: The Billing API exposes cost and dimension data for analysis. Endpoints under /v2/billing return cost rows over a date range with selectable dimensions (account, service, region, custom dimension) and
  name: CloudZero Billing API
  slug: billing
- description: The Insights API stores and surfaces actionable cost insights and recommendations. Endpoints under /v2/insights support listing, creating, updating, and deleting insight records, including assigned ow
  name: CloudZero Insights API
  slug: insights
- description: The Budgets API manages cost-and-usage budgets, alerts, thresholds, and actuals tracking. Endpoints under /v2/budgets list, create, update, and delete budgets and surface current consumption against l
  name: CloudZero Budgets API
  slug: budgets
- description: Allocation Telemetry sends, edits, and deletes allocation telemetry data for splitting cloud cost across custom allocation dimensions. Endpoints under /v1/telemetry/allocation/{stream_name} support su
  name: CloudZero Allocation Telemetry API
  slug: allocation-telemetry
- description: Unit Metric Telemetry ingests business metrics that drive unit-economics calculations (cost per customer, cost per transaction, cost per tenant). Endpoints under /v1/telemetry/{stream_name} support su
  name: CloudZero Unit Metric Telemetry API
  slug: unit-metric-telemetry
- description: AnyCost ingests cost data from any source using the AnyCost Stream Adaptor and Common Bill Format (CBF). Endpoints under /v2/connections/billing/anycost/{connection_id}/billing_drops accept uploads of
  name: CloudZero AnyCost API
  slug: anycost
capabilities:
- description: ''
  name: Cloud Cost Finops
  slug: cloud-cost-finops
common:
- title: ''
  type: Website
  url: https://www.cloudzero.com/
- title: ''
  type: Portal
  url: https://app.cloudzero.com/
- title: ''
  type: Documentation
  url: https://docs.cloudzero.com/
- title: ''
  type: Pricing
  url: https://www.cloudzero.com/pricing/
- title: ''
  type: Status
  url: https://status.cloudzero.com/
- title: ''
  type: GitHub
  url: https://github.com/Cloudzero
- title: ''
  type: Terms of Service
  url: https://www.cloudzero.com/terms-of-service/
- title: ''
  type: Privacy
  url: https://www.cloudzero.com/privacy-policy/
created: '2026-01-02'
description: CloudZero is a cloud cost intelligence and FinOps platform that automates the collection, allocation, and analysis of infrastructure spend to uncover waste and improve unit economics. The CloudZero API V2 is REST-oriented, uses API key authentication, and exposes endpoints for querying billing costs and dimensions, managing insights and budgets, sending unit metric and allocation telemetry, and ingesting cost data from any source via the AnyCost framework.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 2
  name: Cloudzero Context
  property_count: 11
  slug: cloudzero-context
layout: provider
modified: '2026-04-23'
name: CloudZero
rules:
- name: CloudZero API Rules
  rule_count: 12
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 7
  slug: cloudzero-rules
skills: []
slug: cloudzero
solutions: []
source_filename: apis.yml
source_yaml: "aid: cloudzero\nurl: https://raw.githubusercontent.com/api-evangelist/cloudzero/refs/heads/main/apis.yml\nname: CloudZero\ncreated: '2026-01-02'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nx-type: company\ntags:\n  - Budgets\n  - Cloud Cost Management\n  - Cost Allocation\n  - Cost Optimization\n  - FinOps\n  - Telemetry\n  - Unit Economics\ndescription: >-\n  CloudZero is a cloud cost intelligence and FinOps platform that automates\n  the collection, allocation, and analysis of infrastructure spend to uncover\n  waste and improve unit economics. The CloudZero API V2 is REST-oriented,\n  uses API key authentication, and exposes endpoints for querying billing\n  costs and dimensions, managing insights and budgets, sending unit metric\n  and allocation telemetry, and ingesting cost data from any source via the\n  AnyCost framework.\n\
  apis:\n  - aid: cloudzero:api\n    name: CloudZero API\n    description: >-\n      The CloudZero API V2 enables you to automate the collection, allocation,\n      and analysis of your infrastructure spend. It provides endpoints for\n      querying billing costs and dimensions, managing insights and budgets,\n      sending unit metric and allocation telemetry data, and ingesting cost\n      data from any source via the AnyCost framework.\n    humanURL: https://docs.cloudzero.com/reference/introduction\n    baseURL: https://api.cloudzero.com\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Billing\n      - Budgets\n      - Cloud Costs\n      - Cost Allocation\n      - FinOps\n      - Insights\n      - Telemetry\n      - Unit Economics\n    properties:\n      - type: Documentation\n        url: https://docs.cloudzero.com/reference/introduction\n      - type: OpenAPI\n        url: openapi/cloudzero-api-openapi.yml\n      - type: Authorization\n\
  \        url: https://docs.cloudzero.com/reference/authorization\n      - type: JSONSchema\n        url: json-schema/cloudzero-cost.json\n      - type: JSONSchema\n        url: json-schema/cloudzero-insight.json\n      - type: JSONSchema\n        url: json-schema/cloudzero-budget.json\n      - type: JSONSchema\n        url: json-schema/cloudzero-telemetry-record.json\n      - type: JSONSchema\n        url: json-schema/cloudzero-billing-drop.json\n      - type: JSONLD\n        url: json-ld/cloudzero-context.jsonld\n      - type: Spectral\n        url: rules/cloudzero-rules.yml\n      - type: Naftiko Capabilities\n        url: capabilities/cloud-cost-finops.yaml\n\n  - aid: cloudzero:billing\n    name: CloudZero Billing API\n    description: >-\n      The Billing API exposes cost and dimension data for analysis. Endpoints\n      under /v2/billing return cost rows over a date range with selectable\n      dimensions (account, service, region, custom dimension) and metrics\n      (real_cost,\
  \ billed_cost). Pagination uses page and page_size query\n      parameters.\n    humanURL: https://docs.cloudzero.com/reference/billing\n    baseURL: https://api.cloudzero.com/v2/billing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Billing\n      - Cost Reporting\n      - Dimensions\n    properties:\n      - type: Documentation\n        url: https://docs.cloudzero.com/reference/billing\n\n  - aid: cloudzero:insights\n    name: CloudZero Insights API\n    description: >-\n      The Insights API stores and surfaces actionable cost insights and\n      recommendations. Endpoints under /v2/insights support listing, creating,\n      updating, and deleting insight records, including assigned owners,\n      severity, status, and estimated savings.\n    humanURL: https://docs.cloudzero.com/reference/insights\n    baseURL: https://api.cloudzero.com/v2/insights\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    tags:\n      - Cost Optimization\n      - Insights\n      - Recommendations\n    properties:\n      - type: Documentation\n        url: https://docs.cloudzero.com/reference/insights\n\n  - aid: cloudzero:budgets\n    name: CloudZero Budgets API\n    description: >-\n      The Budgets API manages cost-and-usage budgets, alerts, thresholds, and\n      actuals tracking. Endpoints under /v2/budgets list, create, update, and\n      delete budgets and surface current consumption against limits.\n    humanURL: https://docs.cloudzero.com/reference/budgets\n    baseURL: https://api.cloudzero.com/v2/budgets\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Alerts\n      - Budgets\n      - FinOps\n    properties:\n      - type: Documentation\n        url: https://docs.cloudzero.com/reference/budgets\n\n  - aid: cloudzero:allocation-telemetry\n    name: CloudZero Allocation Telemetry API\n    description: >-\n      Allocation Telemetry\
  \ sends, edits, and deletes allocation telemetry\n      data for splitting cloud cost across custom allocation dimensions.\n      Endpoints under /v1/telemetry/allocation/{stream_name} support sum,\n      replace, and delete operations against a named telemetry stream.\n    humanURL: https://docs.cloudzero.com/reference/allocation-telemetry\n    baseURL: https://api.cloudzero.com/v1/telemetry/allocation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Allocation\n      - Cost Splitting\n      - Telemetry\n    properties:\n      - type: Documentation\n        url: https://docs.cloudzero.com/reference/allocation-telemetry\n\n  - aid: cloudzero:unit-metric-telemetry\n    name: CloudZero Unit Metric Telemetry API\n    description: >-\n      Unit Metric Telemetry ingests business metrics that drive unit-economics\n      calculations (cost per customer, cost per transaction, cost per\n      tenant). Endpoints under /v1/telemetry/{stream_name}\
  \ support submitting\n      records, deleting, and replacing values for named streams.\n    humanURL: https://docs.cloudzero.com/reference/unit-metric-telemetry\n    baseURL: https://api.cloudzero.com/v1/telemetry\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Telemetry\n      - Unit Economics\n      - Unit Metrics\n    properties:\n      - type: Documentation\n        url: https://docs.cloudzero.com/reference/unit-metric-telemetry\n\n  - aid: cloudzero:anycost\n    name: CloudZero AnyCost API\n    description: >-\n      AnyCost ingests cost data from any source using the AnyCost Stream\n      Adaptor and Common Bill Format (CBF). Endpoints under\n      /v2/connections/billing/anycost/{connection_id}/billing_drops accept\n      uploads of normalized billing drops alongside native AWS, Azure, and\n      GCP integrations.\n    humanURL: https://docs.cloudzero.com/reference/anycost\n    baseURL: https://api.cloudzero.com/v2/connections/billing/anycost\n\
  \    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - AnyCost\n      - Billing Drop\n      - CBF\n      - Common Bill Format\n      - Ingestion\n    properties:\n      - type: Documentation\n        url: https://docs.cloudzero.com/reference/anycost\ncommon:\n  - type: Website\n    url: https://www.cloudzero.com/\n  - type: Portal\n    url: https://app.cloudzero.com/\n  - type: Documentation\n    url: https://docs.cloudzero.com/\n  - type: Pricing\n    url: https://www.cloudzero.com/pricing/\n  - type: Status\n    url: https://status.cloudzero.com/\n  - type: GitHub\n    url: https://github.com/Cloudzero\n  - type: Terms of Service\n    url: https://www.cloudzero.com/terms-of-service/\n  - type: Privacy\n    url: https://www.cloudzero.com/privacy-policy/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudzero/refs/heads/main/apis.yml
tags:
- Budgets
- Cloud Cost Management
- Cost Allocation
- Cost Optimization
- FinOps
- Telemetry
- Unit Economics
url: https://raw.githubusercontent.com/api-evangelist/cloudzero/refs/heads/main/apis.yml
use_cases: []
---
