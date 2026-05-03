---
api_count: 1
api_specs:
- filename: spot-by-netapp-openapi.yml
  format: yaml
  label: Spot by NetApp API
  slug: spot-by-netapp
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spot-by-netapp/refs/heads/main/openapi/spot-by-netapp-openapi.yml
apis:
- description: The Spot by NetApp REST API enables programmatic management of cloud infrastructure optimization resources. Manage Elastigroup auto-scaling groups across AWS, Azure, and GCP; create and configure Ocea
  name: Spot by NetApp API
  slug: spot-by-netapp
capabilities:
- description: Unified cloud infrastructure cost optimization capability composing Spot by NetApp APIs for Elastigroup management, Ocean Kubernetes optimization, rightsizing analysis, cost reporting, and account adm
  name: Spot by NetApp Cloud Cost Optimization
  slug: cloud-cost-optimization
common:
- title: ''
  type: Website
  url: https://spot.io/
- title: ''
  type: Portal
  url: https://docs.spot.io/
- title: ''
  type: Documentation
  url: https://docs.spot.io/
- title: ''
  type: Reference
  url: https://docs.spot.io/api/
- title: ''
  type: GitHub
  url: https://github.com/spotinst
- title: ''
  type: SDK
  url: https://github.com/spotinst/spotinst-sdk-go
- title: ''
  type: SDK
  url: https://github.com/spotinst/spotinst-sdk-java
- title: ''
  type: SDK
  url: https://github.com/spotinst/spotinst-sdk-nodejs
- title: ''
  type: SDK
  url: https://github.com/spotinst/spotinst-sdk-python
- title: ''
  type: Terraform
  url: https://github.com/spotinst/terraform-provider-spotinst
- title: ''
  type: Helm
  url: https://github.com/spotinst/spotinst-kubernetes-helm-charts
- title: ''
  type: CLI
  url: https://github.com/spotinst/spotctl
- title: ''
  type: Console
  url: https://console.spotinst.com/
- title: ''
  type: Login
  url: https://console.spotinst.com/
created: '2026-03-27'
description: Spot by NetApp (formerly Spot by Flexera, originally Spotinst) is a cloud infrastructure optimization platform providing automated cost optimization, scaling, and intelligent management for cloud workloads across AWS, Azure, and GCP. The Spot platform includes Elastigroup for intelligent auto-scaling using Spot instances, Ocean for Kubernetes and container cost optimization, Stateful Nodes for stateful workloads, EMR Scaler for Hadoop workloads, and Ocean CD for progressive delivery. The platform delivers FinOps capabilities including rightsizing recommendations, cost analysis, and cloud spend visibility.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 39
  name: Spot By Netapp Context
  property_count: 3
  slug: spot-by-netapp-context
layout: provider
modified: '2026-05-02'
name: Spot by NetApp
rules:
- name: Spot by NetApp API Rules
  rule_count: 11
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 5
  slug: spot-by-netapp-rules
skills: []
slug: spot-by-netapp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spot-by-netapp\nname: Spot by NetApp\ndescription: >-\n  Spot by NetApp (formerly Spot by Flexera, originally Spotinst) is a cloud infrastructure\n  optimization platform providing automated cost optimization, scaling, and intelligent\n  management for cloud workloads across AWS, Azure, and GCP. The Spot platform includes\n  Elastigroup for intelligent auto-scaling using Spot instances, Ocean for Kubernetes and\n  container cost optimization, Stateful Nodes for stateful workloads, EMR Scaler for\n  Hadoop workloads, and Ocean CD for progressive delivery. The platform delivers FinOps\n  capabilities including rightsizing recommendations, cost analysis, and cloud spend visibility.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Optimization\n  - FinOps\n  - Kubernetes\n  - AWS\n  - Azure\n  - GCP\n  - Cost Optimization\n  - Auto Scaling\ncreated: '2026-03-27'\nmodified:\
  \ '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/spot-by-netapp/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: spot-by-netapp:spot-by-netapp\n    name: Spot by NetApp API\n    description: >-\n      The Spot by NetApp REST API enables programmatic management of cloud infrastructure\n      optimization resources. Manage Elastigroup auto-scaling groups across AWS, Azure, and\n      GCP; create and configure Ocean clusters for Kubernetes cost optimization; set up\n      Stateful Nodes for persistent workloads; retrieve cost analysis and savings reports;\n      access rightsizing recommendations; and manage account configuration, API tokens,\n      audit logs, and notification subscriptions. Bearer token authentication required.\n    humanURL: https://spot.io/\n    baseURL: https://api.spotinst.io\n    tags:\n      - Cloud Optimization\n      - FinOps\n      - Kubernetes\n      - AWS\n      - Azure\n      - GCP\n      - Auto Scaling\n   \
  \   - Spot Instances\n      - Cost Management\n      - DevOps\n    properties:\n      - type: Documentation\n        url: https://docs.spot.io/\n      - type: Reference\n        url: https://docs.spot.io/api/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/spot-by-netapp/refs/heads/main/openapi/spot-by-netapp-openapi.yml\n      - type: Getting Started\n        url: https://docs.spot.io/\n      - type: GitHub\n        url: https://github.com/spotinst/openapi\ncommon:\n  - type: Website\n    url: https://spot.io/\n  - type: Portal\n    url: https://docs.spot.io/\n  - type: Documentation\n    url: https://docs.spot.io/\n  - type: Reference\n    url: https://docs.spot.io/api/\n  - type: GitHub\n    url: https://github.com/spotinst\n  - type: SDK\n    url: https://github.com/spotinst/spotinst-sdk-go\n  - type: SDK\n    url: https://github.com/spotinst/spotinst-sdk-java\n  - type: SDK\n    url: https://github.com/spotinst/spotinst-sdk-nodejs\n\
  \  - type: SDK\n    url: https://github.com/spotinst/spotinst-sdk-python\n  - type: Terraform\n    url: https://github.com/spotinst/terraform-provider-spotinst\n  - type: Helm\n    url: https://github.com/spotinst/spotinst-kubernetes-helm-charts\n  - type: CLI\n    url: https://github.com/spotinst/spotctl\n  - type: Console\n    url: https://console.spotinst.com/\n  - type: Login\n    url: https://console.spotinst.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spot-by-netapp/refs/heads/main/apis.yml
tags:
- Cloud Optimization
- FinOps
- Kubernetes
- Azure
- GCP
- Cost Optimization
- Auto Scaling
url: https://raw.githubusercontent.com/api-evangelist/spot-by-netapp/refs/heads/main/apis.yml
use_cases: []
---
