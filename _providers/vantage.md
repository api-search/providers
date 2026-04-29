---
api_count: 2
api_specs:
- filename: vantage-cost-management-api-openapi.yml
  format: yaml
  label: Vantage Cost Management API
  slug: cost-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vantage/refs/heads/main/openapi/vantage-cost-management-api-openapi.yml
- filename: vantage-cloud-pricing-api-openapi.yml
  format: yaml
  label: Vantage Cloud Pricing API
  slug: cloud-pricing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vantage/refs/heads/main/openapi/vantage-cloud-pricing-api-openapi.yml
apis:
- description: The Vantage Cost Management API (v2) provides programmatic access to cloud cost data and enables automation of cost management workflows. Create and manage Cost Reports, Folders, Dashboards, Saved Fil
  name: Vantage Cost Management API
  slug: cost-management-api
- description: The Vantage Cloud Pricing API (v1) provides programmatic access to cloud infrastructure pricing data across multiple providers including AWS, Azure, and GCP. Query providers, services, products, and p
  name: Vantage Cloud Pricing API
  slug: cloud-pricing-api
capabilities:
- description: Unified workflow for cloud cost management combining cost reporting, alerting, optimization recommendations, and cloud pricing comparison. Used by FinOps teams and cloud engineers to monitor, optimize
  name: Vantage Cloud Cost Management
  slug: cloud-cost-management
common:
- title: ''
  type: DeveloperPortal
  url: https://www.vantage.sh/
- title: ''
  type: Documentation
  url: https://docs.vantage.sh/
- title: ''
  type: Blog
  url: https://www.vantage.sh/blog
- title: ''
  type: Pricing
  url: https://www.vantage.sh/pricing
- title: ''
  type: Documentation
  url: https://www.vantage.sh/about
- title: ''
  type: Partners
  url: https://www.vantage.sh/vantage-partners
- title: ''
  type: ChangeLog
  url: https://docs.vantage.sh/changelog
- title: ''
  type: GettingStarted
  url: https://docs.vantage.sh/getting_started
- title: ''
  type: APIReference
  url: https://vantage.readme.io/reference/general
- title: ''
  type: SDK
  url: https://github.com/vantage-sh/vantage-python
- title: ''
  type: SDK
  url: https://github.com/vantage-sh/vantage-js
- title: ''
  type: GitHubOrganization
  url: https://github.com/vantage-sh
- title: ''
  type: SDK
  url: https://github.com/vantage-sh/terraform-provider-vantage
- title: ''
  type: Rules
  url: rules/vantage-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/vantage-vocabulary.yaml
- title: ''
  type: Capabilities
  url: capabilities/shared/cost-management.yaml
- title: ''
  type: Capabilities
  url: capabilities/shared/cloud-pricing.yaml
- title: ''
  type: Capabilities
  url: capabilities/cloud-cost-management.yaml
created: '2026-01-02'
description: Vantage is a cloud cost management platform designed for modern engineering teams to monitor, optimize, and control their cloud infrastructure spending across multiple providers. The platform helps companies identify immediate cost savings through features like automated purchasing of savings plans, cost recommendations, and Kubernetes rightsizing, while also preventing future cost overruns with anomaly detection, custom alerts, and budget tracking.
features:
- name: Cost Reports
- name: Cost Dashboards
- name: Budget Alerts
- name: Anomaly Detection
- name: Cost Recommendations
- name: Saved Filters
- name: Vantage Query Language (VQL)
- name: Multi-Cloud Support
- name: Kubernetes Cost Tracking
- name: Network Flow Reports
- name: Financial Commitment Reports
- name: Resource Reports
- name: Business Metrics
- name: Segments
- name: Teams and Access Control
- name: Cloud Pricing Database
image: /assets/icons/vantage.png
integrations:
- name: AWS
- name: Azure
- name: Google Cloud
- name: Kubernetes
- name: Datadog
- name: Snowflake
- name: Databricks
- name: MongoDB Atlas
- name: New Relic
- name: Oracle Cloud
- name: Confluent
jsonld:
- class_count: 0
  name: Vantage Cloud Pricing Context
  property_count: 0
  slug: vantage-cloud-pricing-context
- class_count: 0
  name: Vantage Context
  property_count: 25
  slug: vantage-context
- class_count: 0
  name: Vantage Cost Management Context
  property_count: 0
  slug: vantage-cost-management-context
layout: provider
modified: '2026-04-18'
name: Vantage
rules:
- name: Vantage API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: vantage-spectral-rules
skills: []
slug: vantage
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vantage\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vantage/refs/heads/main/apis.yml\napis:\n  - aid: vantage:cost-management-api\n    name: Vantage Cost Management API\n    tags:\n      - Anomaly Detection\n      - Budgets\n      - Cloud Costs\n      - Cost Reports\n      - Dashboards\n      - FinOps\n    humanURL: https://docs.vantage.sh/api\n    properties:\n      - url: https://vantage.readme.io/reference/general\n        type: Documentation\n      - url: openapi/vantage-cost-management-api-openapi.yml\n        type: OpenAPI\n      - url: https://api.vantage.sh/v2/oas_v3.json\n        type: OpenAPI\n      - url: https://api.vantage.sh/v2/swagger.json\n        type: OpenAPI\n      - url: json-schema/cost-report.json\n        type: JSONSchema\n      - url: json-schema/cost.json\n        type: JSONSchema\n      - url: json-schema/folder.json\n        type: JSONSchema\n      - url: json-schema/dashboard.json\n        type: JSONSchema\n      - url: json-schema/saved-filter.json\n\
  \        type: JSONSchema\n      - url: json-schema/workspace.json\n        type: JSONSchema\n      - url: json-schema/team.json\n        type: JSONSchema\n      - url: json-schema/access-grant.json\n        type: JSONSchema\n      - url: json-schema/budget-alert.json\n        type: JSONSchema\n      - url: json-schema/anomaly-alert.json\n        type: JSONSchema\n      - url: json-schema/recommendation.json\n        type: JSONSchema\n      - url: json-schema/segment.json\n        type: JSONSchema\n      - url: json-schema/integration.json\n        type: JSONSchema\n      - url: json-schema/managed-account.json\n        type: JSONSchema\n      - url: json-schema/cost-provider.json\n        type: JSONSchema\n      - url: json-schema/business-metric.json\n        type: JSONSchema\n      - url: json-schema/resource-report.json\n        type: JSONSchema\n      - url: json-schema/resource.json\n        type: JSONSchema\n      - url: json-schema/network-flow-report.json\n        type: JSONSchema\n\
  \      - url: json-schema/financial-commitment-report.json\n        type: JSONSchema\n      - url: json-schema/kubernetes-efficiency-report.json\n        type: JSONSchema\n      - url: json-ld/vantage-context.jsonld\n        type: JSONLD\n    description: >-\n      The Vantage Cost Management API (v2) provides programmatic access to cloud\n      cost data and enables automation of cost management workflows. Create and\n      manage Cost Reports, Folders, Dashboards, Saved Filters, Teams, Budgets,\n      Anomaly Alerts, Business Metrics, Network Flow Reports, Financial\n      Commitment Reports, Resource Reports, Segments, Integrations, and more.\n      Supports the Vantage Query Language (VQL) for filtering cost data across\n      multiple cloud providers.\n    baseURL: https://api.vantage.sh/v2\n  - aid: vantage:cloud-pricing-api\n    name: Vantage Cloud Pricing API\n    tags:\n      - AWS\n      - Azure\n      - Cloud Pricing\n      - GCP\n      - Infrastructure Pricing\n    humanURL:\
  \ https://docs.vantage.sh/api\n    properties:\n      - url: https://vantage.readme.io/reference/general\n        type: Documentation\n      - url: openapi/vantage-cloud-pricing-api-openapi.yml\n        type: OpenAPI\n      - url: https://api.vantage.sh/v1/swagger.json\n        type: OpenAPI\n      - url: json-schema/provider.json\n        type: JSONSchema\n      - url: json-schema/service.json\n        type: JSONSchema\n      - url: json-schema/product.json\n        type: JSONSchema\n      - url: json-schema/price.json\n        type: JSONSchema\n      - url: json-ld/vantage-context.jsonld\n        type: JSONLD\n    description: >-\n      The Vantage Cloud Pricing API (v1) provides programmatic access to cloud\n      infrastructure pricing data across multiple providers including AWS, Azure,\n      and GCP. Query providers, services, products, and prices to retrieve\n      up-to-date pricing information for cloud infrastructure. The API is free\n      for all registered Vantage users.\n\
  \    baseURL: https://api.vantage.sh/v1\nname: Vantage\ntags:\n  - Budgets\n  - Cloud Pricing\n  - Cost Management\n  - Costs\n  - FinOps\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-01-02'\nmodified: '2026-04-18'\nposition: Consumer\ndescription: >-\n  Vantage is a cloud cost management platform designed for modern engineering\n  teams to monitor, optimize, and control their cloud infrastructure spending\n  across multiple providers. The platform helps companies identify immediate\n  cost savings through features like automated purchasing of savings plans, cost\n  recommendations, and Kubernetes rightsizing, while also preventing future cost\n  overruns with anomaly detection, custom alerts, and budget tracking.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: 'Vantage: Multi Cloud Cost Management & Optimization Tool'\n    description:\
  \ 'null'\n    url: https://www.vantage.sh/\n    type: DeveloperPortal\n  - name: Integrations | Vantage\n    description: 'null'\n    url: https://www.vantage.sh/integrations\n    type: Integrations\n  - name: Vantage Documentation - Vantage\n    description: 'null'\n    url: https://docs.vantage.sh/\n    type: Documentation\n  - name: Blog | Vantage\n    description: 'null'\n    url: https://www.vantage.sh/blog\n    type: Blog\n  - name: Pricing | Vantage\n    description: 'null'\n    url: https://www.vantage.sh/pricing\n    type: Pricing\n  - name: About Vantage | Vantage\n    description: 'null'\n    url: https://www.vantage.sh/about\n    type: Documentation\n  - name: Partners | Vantage\n    description: 'null'\n    url: https://www.vantage.sh/vantage-partners\n    type: Partners\n  - name: Vantage Changelog - Vantage\n    description: 'null'\n    url: https://docs.vantage.sh/changelog\n    type: ChangeLog\n  - name: Quickstart - Vantage\n    description: 'null'\n    url: https://docs.vantage.sh/getting_started\n\
  \    type: GettingStarted\n  - name: Vantage API Reference\n    description: 'null'\n    url: https://vantage.readme.io/reference/general\n    type: APIReference\n  - name: Vantage Python SDK\n    description: 'null'\n    url: https://github.com/vantage-sh/vantage-python\n    type: SDK\n  - name: Vantage JavaScript SDK\n    description: 'null'\n    url: https://github.com/vantage-sh/vantage-js\n    type: SDK\n  - name: GitHubOrganization\n    url: https://github.com/vantage-sh\n    type: GitHubOrganization\n  - name: Vantage Terraform Provider\n    url: https://github.com/vantage-sh/terraform-provider-vantage\n    type: SDK\n  - name: Features\n    type: Features\n    data:\n      - name: Cost Reports\n      - name: Cost Dashboards\n      - name: Budget Alerts\n      - name: Anomaly Detection\n      - name: Cost Recommendations\n      - name: Saved Filters\n      - name: Vantage Query Language (VQL)\n      - name: Multi-Cloud Support\n      - name: Kubernetes Cost Tracking\n      - name:\
  \ Network Flow Reports\n      - name: Financial Commitment Reports\n      - name: Resource Reports\n      - name: Business Metrics\n      - name: Segments\n      - name: Teams and Access Control\n      - name: Cloud Pricing Database\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Monitor Cloud Spending\n      - name: Optimize Cloud Costs\n      - name: Detect Cost Anomalies\n      - name: Set Budget Alerts\n      - name: Track Kubernetes Costs\n      - name: Compare Cloud Pricing\n      - name: Generate Financial Reports\n      - name: Allocate Costs by Team\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: AWS\n      - name: Azure\n      - name: Google Cloud\n      - name: Kubernetes\n      - name: Datadog\n      - name: Snowflake\n      - name: Databricks\n      - name: MongoDB Atlas\n      - name: New Relic\n      - name: Oracle Cloud\n      - name: Confluent\n  - url: rules/vantage-spectral-rules.yml\n    type: Rules\n  - url: vocabulary/vantage-vocabulary.yaml\n\
  \    type: Vocabulary\n  - url: capabilities/shared/cost-management.yaml\n    type: Capabilities\n  - url: capabilities/shared/cloud-pricing.yaml\n    type: Capabilities\n  - url: capabilities/cloud-cost-management.yaml\n    type: Capabilities\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vantage/refs/heads/main/apis.yml
tags:
- Budgets
- Cloud Pricing
- Cost Management
- Costs
- FinOps
url: https://raw.githubusercontent.com/api-evangelist/vantage/refs/heads/main/apis.yml
use_cases:
- name: Monitor Cloud Spending
- name: Optimize Cloud Costs
- name: Detect Cost Anomalies
- name: Set Budget Alerts
- name: Track Kubernetes Costs
- name: Compare Cloud Pricing
- name: Generate Financial Reports
- name: Allocate Costs by Team
---
