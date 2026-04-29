---
api_count: 1
api_specs:
- filename: cast-ai-kubernetes-cost-optimization-openapi.yml
  format: yaml
  label: CAST AI Kubernetes Cost Optimization API
  slug: kubernetes-cost-optimization-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cast-ai/refs/heads/main/openapi/cast-ai-kubernetes-cost-optimization-openapi.yml
apis:
- description: 'The CAST AI REST API provides comprehensive access to the Kubernetes cost optimization platform: cluster management, autoscaling and Karpenter integration, node configuration and templates, workload r'
  name: CAST AI Kubernetes Cost Optimization API
  slug: kubernetes-cost-optimization-api
common:
- title: ''
  type: Website
  url: https://cast.ai/
- title: ''
  type: Documentation
  url: https://docs.cast.ai/docs/
- title: ''
  type: GettingStarted
  url: https://docs.cast.ai/docs/getting-started
- title: ''
  type: Authentication
  url: https://docs.cast.ai/docs/authentication
- title: ''
  type: ChangeLog
  url: https://docs.cast.ai/changelog
- title: ''
  type: Pricing
  url: https://cast.ai/pricing/
- title: ''
  type: Blog
  url: https://cast.ai/blog/
- title: ''
  type: CaseStudies
  url: https://cast.ai/case-studies/
- title: ''
  type: Customers
  url: https://cast.ai/case-studies/
- title: ''
  type: Partners
  url: https://cast.ai/partners/
- title: ''
  type: Support
  url: https://cast.ai/support/
- title: ''
  type: StatusPage
  url: https://status.cast.ai/
- title: ''
  type: SecurityPolicy
  url: https://cast.ai/security/
- title: ''
  type: TermsOfService
  url: https://cast.ai/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://cast.ai/privacy-policy/
- title: ''
  type: GitHub
  url: https://github.com/castai/
- title: ''
  type: Slack
  url: https://castai-community.slack.com/
- title: ''
  type: X
  url: https://x.com/cast_ai/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/cast-ai/
- title: ''
  type: YouTube
  url: https://www.youtube.com/@CASTAI
created: '2024-07-02'
description: CAST AI is an Application Performance Automation (APA) platform for Kubernetes that automates cost optimization, autoscaling, workload rightsizing, GPU/LLM workload placement, spot instance selection, and security posture analysis. The platform works across AWS, GCP, Azure, Oracle Cloud, IBM Cloud, AliCloud and on-premises distributions (EKS, GKE, AKS, OpenShift, Rancher, kOps). Everything available in the console UI is also accessible via the REST API at api.cast.ai.
features:
- name: Kubernetes Automation
- name: Cluster Autoscaling
- name: Karpenter Integration
- name: Workload Rightsizing
- name: Bin Packing
- name: Spot Instance Automation
- name: Spot Interruption Prediction
- name: GPU Optimization
- name: LLM Optimization
- name: Database Optimization
- name: Cost Monitoring
- name: Cost Reporting
- name: Savings Analysis
- name: Security Insights
- name: Posture Management
- name: Hibernation Scheduling
- name: Node Templates
- name: Rebalancing
- name: Self-Healing
- name: Policy Enforcement
- name: Drift Remediation
- name: Container Insights
- name: SLO Monitoring
- name: Performance Observability
- name: Multi-Cloud
- name: Air-Gapped Support
image: https://kinlane-productions2.s3.amazonaws.com/apis-json-icons/swagger-ui-n0PWZL5D.png
integrations:
- name: AWS
- name: Google Cloud
- name: Azure
- name: Oracle Cloud
- name: IBM Cloud
- name: AliCloud
- name: EKS
- name: GKE
- name: AKS
- name: OpenShift
- name: Rancher
- name: kOps
- name: Karpenter
- name: Terraform
- name: Prometheus
- name: Grafana
- name: Datadog
- name: OpenTelemetry
- name: Jira
- name: Slack
- name: PagerDuty
- name: ServiceNow
- name: PostgreSQL
- name: MySQL
jsonld:
- class_count: 0
  name: Cast Ai Context
  property_count: 6
  slug: cast-ai-context
layout: provider
modified: '2026-04-23'
name: CAST AI
skills: []
slug: cast-ai
solutions: []
source_filename: apis.yml
source_yaml: "aid: cast-ai\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cast-ai/refs/heads/main/apis.yml\nname: CAST AI\ntags:\n  - Autoscaling\n  - Cloud Infrastructure\n  - Cost Optimization\n  - DevOps\n  - FinOps\n  - Kubernetes\n  - Observability\ntype: Index\nimage: >-\n  https://kinlane-productions2.s3.amazonaws.com/apis-json-icons/swagger-ui-n0PWZL5D.png\naccess: 3rd-Party\ncreated: '2024-07-02'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  CAST AI is an Application Performance Automation (APA) platform for\n  Kubernetes that automates cost optimization, autoscaling, workload\n  rightsizing, GPU/LLM workload placement, spot instance selection, and\n  security posture analysis. The platform works across AWS, GCP, Azure,\n  Oracle Cloud, IBM Cloud, AliCloud and on-premises distributions (EKS,\n  GKE, AKS, OpenShift, Rancher, kOps). Everything available in the console\n  UI is also accessible via the REST API at api.cast.ai.\napis:\n  - aid: cast-ai:kubernetes-cost-optimization-api\n\
  \    name: CAST AI Kubernetes Cost Optimization API\n    tags:\n      - Autoscaling\n      - Clusters\n      - Cost Optimization\n      - FinOps\n      - Hibernation\n      - Karpenter\n      - Kubernetes\n      - LLM\n      - Metrics\n      - Node Templates\n      - Nodes\n      - Policies\n      - Pricing\n      - Rebalancing\n      - Security\n      - Spot Instances\n      - Workloads\n    image: >-\n      https://kinlane-productions2.s3.amazonaws.com/apis-json-icons/swagger-ui-n0PWZL5D.png\n    baseURL: https://api.cast.ai\n    humanURL: https://docs.cast.ai/docs/api\n    properties:\n      - url: https://docs.cast.ai/docs/api\n        type: Documentation\n      - url: openapi/cast-ai-kubernetes-cost-optimization-openapi.yml\n        type: OpenAPI\n      - url: https://api.cast.ai/v1/spec/\n        type: Swagger\n      - url: https://docs.cast.ai/docs/authentication\n        type: Authentication\n      - url: https://docs.cast.ai/changelog\n        type: ChangeLog\n      - url: json-schema/cluster.json\n\
  \        type: JSONSchema\n      - url: json-schema/node.json\n        type: JSONSchema\n      - url: json-schema/node-template.json\n        type: JSONSchema\n      - url: json-schema/workload.json\n        type: JSONSchema\n      - url: json-schema/rebalancing-schedule.json\n        type: JSONSchema\n      - url: json-schema/cost-report.json\n        type: JSONSchema\n      - url: json-ld/cast-ai-context.jsonld\n        type: JSONLD\n    description: >-\n      The CAST AI REST API provides comprehensive access to the Kubernetes\n      cost optimization platform: cluster management, autoscaling and\n      Karpenter integration, node configuration and templates, workload\n      rightsizing, scheduled rebalancing, cost reporting, security insights,\n      hibernation schedules, AI enabler / LLM workload optimization, and\n      GPU/OMNI compute features. Authentication uses API keys and the API is\n      served at api.cast.ai.\ncommon:\n  - type: Website\n    url: https://cast.ai/\n  -\
  \ type: Documentation\n    url: https://docs.cast.ai/docs/\n  - type: GettingStarted\n    url: https://docs.cast.ai/docs/getting-started\n  - type: Authentication\n    url: https://docs.cast.ai/docs/authentication\n  - type: ChangeLog\n    url: https://docs.cast.ai/changelog\n  - type: Pricing\n    url: https://cast.ai/pricing/\n  - type: Blog\n    url: https://cast.ai/blog/\n  - type: CaseStudies\n    url: https://cast.ai/case-studies/\n  - type: Customers\n    url: https://cast.ai/case-studies/\n  - type: Partners\n    url: https://cast.ai/partners/\n  - type: Support\n    url: https://cast.ai/support/\n  - type: StatusPage\n    url: https://status.cast.ai/\n  - type: SecurityPolicy\n    url: https://cast.ai/security/\n  - type: TermsOfService\n    url: https://cast.ai/terms-of-service/\n  - type: PrivacyPolicy\n    url: https://cast.ai/privacy-policy/\n  - type: GitHub\n    url: https://github.com/castai/\n  - type: Slack\n    url: https://castai-community.slack.com/\n  - type: X\n\
  \    url: https://x.com/cast_ai/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/cast-ai/\n  - type: YouTube\n    url: https://www.youtube.com/@CASTAI\n  - name: Features\n    type: Features\n    data:\n      - name: Kubernetes Automation\n      - name: Cluster Autoscaling\n      - name: Karpenter Integration\n      - name: Workload Rightsizing\n      - name: Bin Packing\n      - name: Spot Instance Automation\n      - name: Spot Interruption Prediction\n      - name: GPU Optimization\n      - name: LLM Optimization\n      - name: Database Optimization\n      - name: Cost Monitoring\n      - name: Cost Reporting\n      - name: Savings Analysis\n      - name: Security Insights\n      - name: Posture Management\n      - name: Hibernation Scheduling\n      - name: Node Templates\n      - name: Rebalancing\n      - name: Self-Healing\n      - name: Policy Enforcement\n      - name: Drift Remediation\n      - name: Container Insights\n      - name: SLO Monitoring\n      - name:\
  \ Performance Observability\n      - name: Multi-Cloud\n      - name: Air-Gapped Support\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Kubernetes Cost Reduction\n      - name: Cluster Right-Sizing\n      - name: Automated Spot Instance Adoption\n      - name: GPU Workload Placement\n      - name: LLM Inference Cost Optimization\n      - name: FinOps Reporting\n      - name: Security Posture Assessment\n      - name: Reserved Instance Planning\n      - name: Multi-Cluster Management\n      - name: Hibernation of Non-Production Clusters\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: AWS\n      - name: Google Cloud\n      - name: Azure\n      - name: Oracle Cloud\n      - name: IBM Cloud\n      - name: AliCloud\n      - name: EKS\n      - name: GKE\n      - name: AKS\n      - name: OpenShift\n      - name: Rancher\n      - name: kOps\n      - name: Karpenter\n      - name: Terraform\n      - name: Prometheus\n      - name: Grafana\n      - name:\
  \ Datadog\n      - name: OpenTelemetry\n      - name: Jira\n      - name: Slack\n      - name: PagerDuty\n      - name: ServiceNow\n      - name: PostgreSQL\n      - name: MySQL\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cast-ai/refs/heads/main/apis.yml
tags:
- Autoscaling
- Cloud Infrastructure
- Cost Optimization
- DevOps
- FinOps
- Kubernetes
- Observability
url: https://raw.githubusercontent.com/api-evangelist/cast-ai/refs/heads/main/apis.yml
use_cases:
- name: Kubernetes Cost Reduction
- name: Cluster Right-Sizing
- name: Automated Spot Instance Adoption
- name: GPU Workload Placement
- name: LLM Inference Cost Optimization
- name: FinOps Reporting
- name: Security Posture Assessment
- name: Reserved Instance Planning
- name: Multi-Cluster Management
- name: Hibernation of Non-Production Clusters
---
