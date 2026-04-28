---
api_count: 7
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
