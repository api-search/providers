---
api_count: 1
api_specs:
- filename: nops-nops-openapi.yml
  format: yaml
  label: nOps
  slug: nops
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nops/refs/heads/main/openapi/nops-nops-openapi.yml
apis:
- description: nOps is an AWS-focused cloud management platform that helps engineering and FinOps teams cut costs, improve governance, and keep environments well-architected. It ingests AWS billing and telemetry dat
  name: nOps
  slug: nops
capabilities:
- description: Unified cloud cost optimization capability combining MAP migration tracking, scheduler automation, and cost recommendations. Used by FinOps teams and cloud operations engineers.
  name: nOps Cloud Cost Optimization
  slug: cloud-cost-optimization
common:
- title: ''
  type: Blog
  url: https://www.nops.io/blog/
- title: ''
  type: Webinars
  url: https://www.nops.io/webinars-and-workshops/
- title: ''
  type: Resources
  url: https://www.nops.io/ncast/
- title: ''
  type: Documentation
  url: https://help.nops.io/docs/introduction/platform-introduction
- title: ''
  type: Documentation
  url: https://help.nops.io/docs/support/customer-service-sla
- title: ''
  type: Support
  url: https://help.nops.io/docs/support/open-support-case
created: '2026-01-02'
description: nOps is an AI-powered cloud cost visibility and optimization platform that helps organizations reduce their AWS spending by 50% or more through autonomous management and automation. The platform provides 100% visibility into cloud costs across AWS, GCP, Azure, Kubernetes, GenAI, and SaaS applications, enabling teams to allocate and track spending by customer, product, cost center, or any other dimension even without complete tagging.
features:
- description: AI-powered autonomous management that identifies and implements cost savings without manual intervention.
  name: Autonomous Cost Optimization
- description: Complete visibility into cloud costs across AWS, GCP, Azure, Kubernetes, GenAI, and SaaS applications.
  name: 100% Cost Visibility
- description: Automated scheduling of non-production workloads to eliminate idle resource costs.
  name: Essentials Scheduler
- description: AWS Migration Acceleration Program tracking for migration projects, products, and resources.
  name: MAP Migration Support
- description: Intelligent spot instance management for maximizing cost savings on compute workloads.
  name: Spot Instance Optimization
image: /assets/icons/nops.png
integrations:
- description: Deep integration with AWS billing, CUR, CloudTrail, CloudWatch, and resource management services.
  name: AWS Services
- description: Container cost visibility and optimization for EKS and self-managed Kubernetes clusters.
  name: Kubernetes
- description: Notification integrations for cost alerts, optimization recommendations, and scheduler events.
  name: Slack and Teams
jsonld:
- class_count: 0
  name: Nops Context
  property_count: 4
  slug: nops-context
- class_count: 0
  name: Nops Nops Context
  property_count: 0
  slug: nops-nops-context
layout: provider
modified: '2026-04-18'
name: nOps
rules:
- name: nOps API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: nops-spectral-rules
skills: []
slug: nops
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nops\nurl: https://raw.githubusercontent.com/api-evangelist/nops/refs/heads/main/apis.yml\napis:\n  - aid: nops:nops\n    name: nOps\n    tags:\n      - Costs\n      - FinOps\n    humanURL: ' https://www.nops.io/'\n    baseURL: https://app.nops.io\n    properties:\n      - url: ' https://www.nops.io/'\n        type: Documentation\n      - url: https://app.nops.io/public_redoc/\n        type: Documentation\n      - url: openapi/nops-nops-openapi.yml\n        type: OpenAPI\n      - url: json-schema/map-migration-project.json\n        type: JSONSchema\n      - url: json-schema/map-migration-product.json\n        type: JSONSchema\n      - url: json-schema/map-migration-resource.json\n        type: JSONSchema\n      - url: json-schema/scheduler.json\n        type: JSONSchema\n      - url: json-ld/nops-context.jsonld\n        type: JSONLD\n    description: >-\n      nOps is an AWS-focused cloud management platform that helps engineering and\n      FinOps teams cut costs, improve\
  \ governance, and keep environments well-architected.\n      It ingests AWS billing and telemetry data (such as CUR, CloudTrail, and CloudWatch)\n      to surface real-time insights, flag anomalies, and recommend actions like rightsizing,\n      eliminating idle resources, scheduling non‑production workloads, optimizing\n      EBS/S3, and increasing efficient use of Spot.\nname: nOps\ntags:\n  - Costs\n  - FinOps\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-01-02'\nmodified: '2026-04-18'\nposition: Consuming\ndescription: >-\n  nOps is an AI-powered cloud cost visibility and optimization platform that helps\n  organizations reduce their AWS spending by 50% or more through autonomous management\n  and automation. The platform provides 100% visibility into cloud costs across AWS,\n  GCP, Azure, Kubernetes, GenAI, and SaaS applications, enabling teams to allocate\n  and track spending by customer, product,\
  \ cost center, or any other dimension even\n  without complete tagging.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: Technical Blogs & Tutorials | nOps\n    description: 'null'\n    url: https://www.nops.io/blog/\n    type: Blog\n  - name: Webcasts and Podcasts | Live & On-Demand | nOps\n    description: 'null'\n    url: https://www.nops.io/webinars-and-workshops/\n    type: Webinars\n  - name: nCast | nOps\n    description: 'null'\n    url: https://www.nops.io/ncast/\n    type: Resources\n  - name: Welcome to the nOps Docs | nOps docs\n    description: 'null'\n    url: https://help.nops.io/docs/introduction/platform-introduction\n    type: Documentation\n  - name: nOps Customer Service SLAs | nOps docs\n    description: 'null'\n    url: https://help.nops.io/docs/support/customer-service-sla\n    type: Documentation\n  - name: Open a support case with nOps | nOps docs\n    description: 'null'\n    url: https://help.nops.io/docs/support/open-support-case\n\
  \    type: Support\n  - name: Integrations Overview | nOps docs\n    description: 'null'\n    url: https://help.nops.io/docs/agents-integrations/integrations\n    type: Integrations\n  - type: Features\n    data:\n      - name: Autonomous Cost Optimization\n        description: AI-powered autonomous management that identifies and implements cost savings without manual intervention.\n      - name: 100% Cost Visibility\n        description: Complete visibility into cloud costs across AWS, GCP, Azure, Kubernetes, GenAI, and SaaS applications.\n      - name: Essentials Scheduler\n        description: Automated scheduling of non-production workloads to eliminate idle resource costs.\n      - name: MAP Migration Support\n        description: AWS Migration Acceleration Program tracking for migration projects, products, and resources.\n      - name: Spot Instance Optimization\n        description: Intelligent spot instance management for maximizing cost savings on compute workloads.\n  - type:\
  \ UseCases\n    data:\n      - name: FinOps Automation\n        description: Automate cloud cost allocation, tracking, and optimization across teams and business units.\n      - name: Cloud Migration Tracking\n        description: Track MAP migration projects and measure cost savings from AWS migration programs.\n      - name: Idle Resource Elimination\n        description: Identify and schedule or terminate idle resources to reduce wasted cloud spending.\n      - name: Cost Anomaly Detection\n        description: Real-time detection and alerting on unusual cost spikes and billing anomalies.\n  - type: Integrations\n    data:\n      - name: AWS Services\n        description: Deep integration with AWS billing, CUR, CloudTrail, CloudWatch, and resource management services.\n      - name: Kubernetes\n        description: Container cost visibility and optimization for EKS and self-managed Kubernetes clusters.\n      - name: Slack and Teams\n        description: Notification integrations for\
  \ cost alerts, optimization recommendations, and scheduler events.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nops/refs/heads/main/apis.yml
tags:
- Costs
- FinOps
url: https://raw.githubusercontent.com/api-evangelist/nops/refs/heads/main/apis.yml
use_cases:
- description: Automate cloud cost allocation, tracking, and optimization across teams and business units.
  name: FinOps Automation
- description: Track MAP migration projects and measure cost savings from AWS migration programs.
  name: Cloud Migration Tracking
- description: Identify and schedule or terminate idle resources to reduce wasted cloud spending.
  name: Idle Resource Elimination
- description: Real-time detection and alerting on unusual cost spikes and billing anomalies.
  name: Cost Anomaly Detection
---
