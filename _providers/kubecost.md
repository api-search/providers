---
api_count: 6
api_specs:
- filename: kubecost-allocation-openapi.yml
  format: yaml
  label: Kubecost Allocation API
  slug: allocation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/openapi/kubecost-allocation-openapi.yml
- filename: kubecost-assets-openapi.yml
  format: yaml
  label: Kubecost Assets API
  slug: assets-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/openapi/kubecost-assets-openapi.yml
- filename: kubecost-cloud-cost-openapi.yml
  format: yaml
  label: Kubecost Cloud Cost API
  slug: cloud-cost-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/openapi/kubecost-cloud-cost-openapi.yml
- filename: kubecost-budget-openapi.yml
  format: yaml
  label: Kubecost Budget API
  slug: budget-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/openapi/kubecost-budget-openapi.yml
- filename: kubecost-forecast-openapi.yml
  format: yaml
  label: Kubecost Forecast API
  slug: forecast-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/openapi/kubecost-forecast-openapi.yml
- filename: kubecost-savings-openapi.yml
  format: yaml
  label: Kubecost Savings API
  slug: savings-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/openapi/kubecost-savings-openapi.yml
apis:
- description: The Allocation API retrieves cost allocation information for any Kubernetes concept, such as cost by namespace, label, deployment, service, and more. It is directly integrated with the Kubecost ETL ca
  name: Kubecost Allocation API
  slug: allocation-api
- description: The Assets API retrieves backing cost data broken down by individual Kubernetes assets in your cluster, such as nodes, disks, load balancers, and more. It also provides various aggregations of this da
  name: Kubecost Assets API
  slug: assets-api
- description: The Cloud Cost API provides accurate cost information from your cloud service providers (CSPs), including AWS, Azure, and GCP. It offers multiple endpoints for querying, aggregating, and analyzing clo
  name: Kubecost Cloud Cost API
  slug: cloud-cost-api
- description: The Budget API allows you to create, update, and delete recurring budget rules to control your Kubernetes spending. Weekly and monthly budgets can be established on workloads to set limits on cost spe
  name: Kubecost Budget API
  slug: budget-api
- description: The Forecast API provides cost forecasting capabilities for Kubernetes workloads, allowing you to predict future spend based on historical cost data and trends.
  name: Kubecost Forecast API
  slug: forecast-api
- description: The Savings APIs provide cost optimization insights, including cluster-level potential savings estimates, recommendations for right-sizing clusters and containers, listing abandoned workloads, orphane
  name: Kubecost Savings API
  slug: savings-api
common: []
created: '2024-11-13'
description: Kubecost provides real-time cost monitoring and management for Kubernetes environments. Its APIs enable programmatic access to cost allocation data, asset costs, cloud provider spend, budget governance, cost forecasting, and savings recommendations for optimizing Kubernetes and cloud infrastructure spending.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Kubecost Context
  property_count: 7
  slug: kubecost-context
layout: provider
modified: '2026-04-28'
name: Kubecost
skills: []
slug: kubecost
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kubecost\nurl: https://raw.githubusercontent.com/api-search/kubecost/refs/heads/main/apis.yml\napis:\n  - aid: kubecost:allocation-api\n    name: Kubecost Allocation API\n    tags:\n      - Cost Allocation\n      - Kubernetes\n      - Monitoring\n    humanURL: https://docs.kubecost.com/apis/monitoring-apis/api-allocation\n    properties:\n      - url: https://docs.kubecost.com/apis/monitoring-apis/api-allocation\n        type: Documentation\n      - url: openapi/kubecost-allocation-openapi.yml\n        type: OpenAPI\n      - url: json-schema/allocation.json\n        type: JSONSchema\n      - url: json-ld/kubecost-context.jsonld\n        type: JSONLD\n    description: >-\n      The Allocation API retrieves cost allocation information for any\n      Kubernetes concept, such as cost by namespace, label, deployment,\n      service, and more. It is directly integrated with the Kubecost ETL\n      caching layer and CSV pipeline so it can scale for large clusters.\n  - aid: kubecost:assets-api\n\
  \    name: Kubecost Assets API\n    tags:\n      - Assets\n      - Kubernetes\n      - Monitoring\n    humanURL: https://docs.kubecost.com/apis/monitoring-apis/assets-api\n    properties:\n      - url: https://docs.kubecost.com/apis/monitoring-apis/assets-api\n        type: Documentation\n      - url: openapi/kubecost-assets-openapi.yml\n        type: OpenAPI\n      - url: json-schema/asset.json\n        type: JSONSchema\n      - url: json-ld/kubecost-context.jsonld\n        type: JSONLD\n    description: >-\n      The Assets API retrieves backing cost data broken down by individual\n      Kubernetes assets in your cluster, such as nodes, disks, load balancers,\n      and more. It also provides various aggregations of this data.\n  - aid: kubecost:cloud-cost-api\n    name: Kubecost Cloud Cost API\n    tags:\n      - AWS\n      - Azure\n      - Cloud Cost\n      - GCP\n      - Monitoring\n    humanURL: https://docs.kubecost.com/apis/monitoring-apis/cloud-cost-api\n    properties:\n    \
  \  - url: https://docs.kubecost.com/apis/monitoring-apis/cloud-cost-api\n        type: Documentation\n      - url: openapi/kubecost-cloud-cost-openapi.yml\n        type: OpenAPI\n      - url: json-schema/cloud-cost.json\n        type: JSONSchema\n      - url: json-ld/kubecost-context.jsonld\n        type: JSONLD\n    description: >-\n      The Cloud Cost API provides accurate cost information from your cloud\n      service providers (CSPs), including AWS, Azure, and GCP. It offers\n      multiple endpoints for querying, aggregating, and analyzing cloud costs.\n  - aid: kubecost:budget-api\n    name: Kubecost Budget API\n    tags:\n      - Budget\n      - Governance\n      - Spending\n    humanURL: https://docs.kubecost.com/apis/governance-apis/budget-api\n    properties:\n      - url: https://docs.kubecost.com/apis/governance-apis/budget-api\n        type: Documentation\n      - url: openapi/kubecost-budget-openapi.yml\n        type: OpenAPI\n      - url: json-schema/budget.json\n    \
  \    type: JSONSchema\n      - url: json-schema/budget-action.json\n        type: JSONSchema\n      - url: json-ld/kubecost-context.jsonld\n        type: JSONLD\n    description: >-\n      The Budget API allows you to create, update, and delete recurring budget\n      rules to control your Kubernetes spending. Weekly and monthly budgets can\n      be established on workloads to set limits on cost spend, with the option\n      to configure alerts for reaching specified budget thresholds via email,\n      Slack, or Microsoft Teams.\n  - aid: kubecost:forecast-api\n    name: Kubecost Forecast API\n    tags:\n      - Cost Prediction\n      - Forecast\n      - Governance\n    humanURL: https://docs.kubecost.com/apis/governance-apis/forecast-api\n    properties:\n      - url: https://docs.kubecost.com/apis/governance-apis/forecast-api\n        type: Documentation\n      - url: openapi/kubecost-forecast-openapi.yml\n        type: OpenAPI\n      - url: json-schema/forecast.json\n        type:\
  \ JSONSchema\n      - url: json-ld/kubecost-context.jsonld\n        type: JSONLD\n    description: >-\n      The Forecast API provides cost forecasting capabilities for Kubernetes\n      workloads, allowing you to predict future spend based on historical\n      cost data and trends.\n  - aid: kubecost:savings-api\n    name: Kubecost Savings API\n    tags:\n      - Optimization\n      - Right-Sizing\n      - Savings\n    humanURL: https://docs.kubecost.com/apis/savings-apis\n    properties:\n      - url: https://docs.kubecost.com/apis/savings-apis\n        type: Documentation\n      - url: openapi/kubecost-savings-openapi.yml\n        type: OpenAPI\n      - url: json-schema/savings-recommendation.json\n        type: JSONSchema\n      - url: json-ld/kubecost-context.jsonld\n        type: JSONLD\n    description: >-\n      The Savings APIs provide cost optimization insights, including\n      cluster-level potential savings estimates, recommendations for\n      right-sizing clusters and containers,\
  \ listing abandoned workloads,\n      orphaned disks, and orphaned IP addresses.\nname: Kubecost\ntags:\n  - Cloud Cost\n  - Cost Monitoring\n  - Kubernetes\n  - Optimization\n  - Spending\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-13'\nmodified: '2026-04-28'\nposition: Consuming\ndescription: >-\n  Kubecost provides real-time cost monitoring and management for Kubernetes\n  environments. Its APIs enable programmatic access to cost allocation data,\n  asset costs, cloud provider spend, budget governance, cost forecasting,\n  and savings recommendations for optimizing Kubernetes and cloud\n  infrastructure spending.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kubecost/refs/heads/main/apis.yml
tags:
- Cloud Cost
- Cost Monitoring
- Kubernetes
- Optimization
- Spending
url: https://raw.githubusercontent.com/api-search/kubecost/refs/heads/main/apis.yml
use_cases: []
---
