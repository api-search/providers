---
api_count: 2
apis:
- description: 'StormForge Optimize Live is a Kubernetes resource rightsizing product that uses machine learning to automatically generate CPU and memory recommendations for container workloads. An agent deployed to '
  name: StormForge Optimize Live
  slug: optimize-live
- description: Command-line interface for interacting with the StormForge platform to manage clusters, workloads, and optimization recommendations. Supports authentication, resource inspection, recommendation genera
  name: StormForge CLI
  slug: stormforge-cli
common:
- title: ''
  type: Website
  url: https://www.stormforge.io/
- title: ''
  type: Documentation
  url: https://docs.stormforge.io/
- title: ''
  type: Pricing
  url: https://www.stormforge.io/pricing/
- title: ''
  type: Blog
  url: https://www.stormforge.io/blog/
- title: ''
  type: About
  url: https://www.stormforge.io/about/
- title: ''
  type: Contact
  url: https://www.stormforge.io/contact/
- title: ''
  type: GettingStarted
  url: https://docs.stormforge.io/docs/get-started/
- title: ''
  type: Sign Up
  url: https://app.stormforge.io/
- title: ''
  type: GitHubOrg
  url: https://github.com/thestormforge
- title: ''
  type: Sandbox
  url: https://docs.stormforge.io/docs/sandbox/
- title: ''
  type: FinOps
  url: https://www.finops.org/members/stormforge/
created: '2026-03-27'
description: StormForge provides machine learning-based Kubernetes resource optimization (rightsizing) for reducing cloud infrastructure costs while maintaining application performance. The Optimize Live product deploys an agent to Kubernetes clusters that collects workload metrics, applies ML algorithms, and generates CPU and memory recommendations for containers. Recommendations can be applied automatically, on-demand, or exported as Kubernetes patches for GitOps workflows. StormForge supports Deployments, StatefulSets, DaemonSets, ReplicaSets, and custom workload types, and integrates with Karpenter, HPA, VPA, Argo CD, and APM tools.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Stormforge Context
  property_count: 19
  slug: stormforge-context
layout: provider
modified: '2026-05-02'
name: StormForge
skills: []
slug: stormforge
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stormforge\nname: StormForge\ndescription: >-\n  StormForge provides machine learning-based Kubernetes resource optimization (rightsizing)\n  for reducing cloud infrastructure costs while maintaining application performance.\n  The Optimize Live product deploys an agent to Kubernetes clusters that collects\n  workload metrics, applies ML algorithms, and generates CPU and memory recommendations\n  for containers. Recommendations can be applied automatically, on-demand, or exported\n  as Kubernetes patches for GitOps workflows. StormForge supports Deployments, StatefulSets,\n  DaemonSets, ReplicaSets, and custom workload types, and integrates with Karpenter,\n  HPA, VPA, Argo CD, and APM tools.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Cost Optimization\n  - DevOps\n  - FinOps\n  - Kubernetes\n  - Machine Learning\n  - Resource Management\n  - Rightsizing\ncreated:\
  \ '2026-03-27'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/stormforge/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: stormforge:optimize-live\n    name: StormForge Optimize Live\n    description: >-\n      StormForge Optimize Live is a Kubernetes resource rightsizing product that uses\n      machine learning to automatically generate CPU and memory recommendations for\n      container workloads. An agent deployed to the cluster collects observability\n      metrics, which are processed by StormForge's ML platform to produce rightsizing\n      recommendations. Recommendations can be applied automatically, previewed in the\n      web UI, or exported as Kubernetes patches for GitOps. Supports Deployments,\n      StatefulSets, DaemonSets, ReplicaSets, custom CRD workloads, and HPA-managed workloads.\n    humanURL: https://www.stormforge.io/optimize-live/\n    tags:\n      - Cloud Cost Optimization\n      - FinOps\n      - Kubernetes\n\
  \      - Machine Learning\n      - Rightsizing\n    properties:\n      - type: Documentation\n        url: https://docs.stormforge.io/docs/\n      - type: GettingStarted\n        url: https://docs.stormforge.io/docs/get-started/\n      - type: Pricing\n        url: https://www.stormforge.io/pricing/\n      - type: Sign Up\n        url: https://app.stormforge.io/\n      - type: HelmChart\n        url: https://github.com/thestormforge/helm-charts\n  - aid: stormforge:stormforge-cli\n    name: StormForge CLI\n    description: >-\n      Command-line interface for interacting with the StormForge platform to manage\n      clusters, workloads, and optimization recommendations. Supports authentication,\n      resource inspection, recommendation generation and application, GitOps patch export,\n      Helm post-renderer integration, and an MCP server for AI integration. Available\n      via Homebrew (macOS/Linux) and direct download.\n    humanURL: https://docs.stormforge.io/docs/stormforge-cli/reference/\n\
  \    tags:\n      - CLI\n      - DevOps\n      - Kubernetes\n      - FinOps\n    properties:\n      - type: Documentation\n        url: https://docs.stormforge.io/docs/stormforge-cli/reference/\n      - type: GitHubRepository\n        url: https://github.com/thestormforge\n      - type: Homebrew\n        url: https://github.com/thestormforge/homebrew-tap\ncommon:\n  - type: Website\n    url: https://www.stormforge.io/\n  - type: Documentation\n    url: https://docs.stormforge.io/\n  - type: Pricing\n    url: https://www.stormforge.io/pricing/\n  - type: Blog\n    url: https://www.stormforge.io/blog/\n  - type: About\n    url: https://www.stormforge.io/about/\n  - type: Contact\n    url: https://www.stormforge.io/contact/\n  - type: GettingStarted\n    url: https://docs.stormforge.io/docs/get-started/\n  - type: Sign Up\n    url: https://app.stormforge.io/\n  - type: GitHubOrg\n    url: https://github.com/thestormforge\n  - type: Sandbox\n    url: https://docs.stormforge.io/docs/sandbox/\n\
  \  - type: FinOps\n    url: https://www.finops.org/members/stormforge/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stormforge/refs/heads/main/apis.yml
tags:
- Cloud Cost Optimization
- DevOps
- FinOps
- Kubernetes
- Machine Learning
- Resource Management
- Rightsizing
url: https://raw.githubusercontent.com/api-evangelist/stormforge/refs/heads/main/apis.yml
use_cases: []
---
