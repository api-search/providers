---
api_count: 2
api_specs:
- filename: dev
  format: yaml
  label: Densify Public Cloud API
  slug: public-cloud-api
  spec_type: Postman
  url: https://www.densify.com/dev
apis:
- description: The Densify Public Cloud REST API exposes optimization analysis, recommendations, account and instance inventory, and systems data for AWS, Azure, and Google Cloud environments. The API uses JSON over
  name: Densify Public Cloud API
  slug: public-cloud-api
- description: The Densify Container Optimization REST API provides programmatic access to container right-sizing recommendations across Amazon EKS, AKS, GKE, OpenShift, and self-managed Kubernetes footprints. It ex
  name: Densify Container Optimization API
  slug: container-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.densify.com
- title: ''
  type: Portal
  url: https://portal.densify.com/
- title: ''
  type: Documentation
  url: https://docs.densify.com
- title: ''
  type: Developer Resources
  url: https://www.densify.com/dev
- title: ''
  type: Documentation Landing
  url: https://portal.densify.com/docs-landing/
- title: ''
  type: Resources
  url: https://www.densify.com/resources
- title: ''
  type: Blog
  url: https://www.densify.com/blog
- title: ''
  type: Pricing
  url: https://www.densify.com/pricing
- title: ''
  type: Free Trial
  url: https://www.densify.com/free-trial
- title: ''
  type: Support
  url: https://www.densify.com/support
- title: ''
  type: GitHub Organization
  url: https://github.com/densify-dev
- title: ''
  type: Terms of Service
  url: https://www.densify.com/legal
- title: ''
  type: Privacy Policy
  url: https://www.densify.com/privacy-policy
- title: ''
  type: Contact
  url: https://www.densify.com/contact
- title: ''
  type: JSON-LD
  url: json-ld/densify-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/densify-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/densify-capabilities.yml
created: '2026-03-16'
description: Densify (now Kubex) provides a machine learning powered cloud and container optimization platform that continuously right-sizes resources to reduce cost and improve performance across Kubernetes, public cloud, and virtualized environments. The Densify REST API exposes optimization analysis, recommendations, account and cluster inventory, and systems data so that optimization can be embedded into CI/CD pipelines, infrastructure as code templates, and FinOps workflows.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Densify Context
  property_count: 6
  slug: densify-context
layout: provider
modified: '2026-04-28'
name: Densify
skills: []
slug: densify
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: densify\nname: Densify\ndescription: >-\n  Densify (now Kubex) provides a machine learning powered cloud and container\n  optimization platform that continuously right-sizes resources to reduce cost\n  and improve performance across Kubernetes, public cloud, and virtualized\n  environments. The Densify REST API exposes optimization analysis,\n  recommendations, account and cluster inventory, and systems data so that\n  optimization can be embedded into CI/CD pipelines, infrastructure as code\n  templates, and FinOps workflows.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Cost\n  - Container Optimization\n  - FinOps\n  - Kubernetes\n  - Machine Learning\n  - Recommendations\n  - Right-Sizing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/densify/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: company\nposition: Producer\naccess:\
  \ 3rd-Party\napis:\n  - aid: densify:public-cloud-api\n    name: Densify Public Cloud API\n    description: >-\n      The Densify Public Cloud REST API exposes optimization analysis, recommendations,\n      account and instance inventory, and systems data for AWS, Azure, and Google\n      Cloud environments. The API uses JSON over HTTPS, follows a resource-oriented\n      design under the /api/v2/ path, and authenticates with JWT bearer tokens\n      obtained from the /authorize endpoint. Common use cases include integrating\n      right-sizing recommendations into Terraform, CloudFormation, and CI/CD pipelines.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.densify.com/docs-api/WebHelp_Densify_API_Cloud/Content/API_Guide/Introduction.htm\n    baseURL: https://api.densify.com/api/v2\n    tags:\n      - Cloud\n      - FinOps\n      - Optimization\n      - Recommendations\n      - Right-Sizing\n    properties:\n      - type:\
  \ Documentation\n        url: https://www.densify.com/docs-api/WebHelp_Densify_API_Cloud/Content/API_Guide/Introduction.htm\n      - type: Reference\n        url: https://www.densify.com/docs/WebHelp_Densify_Cloud/Content/Resources/PDFs/Densify-API-Reference-Guide.pdf\n      - type: Postman\n        url: https://www.densify.com/dev\n    contact:\n      - FN: Densify Support\n        email: support@densify.com\n        url: https://www.densify.com/contact\n  - aid: densify:container-api\n    name: Densify Container Optimization API\n    description: >-\n      The Densify Container Optimization REST API provides programmatic access\n      to container right-sizing recommendations across Amazon EKS, AKS, GKE,\n      OpenShift, and self-managed Kubernetes footprints. It exposes endpoints\n      for clusters, namespaces, controllers, container groups, and recommended\n      requests/limits for CPU and memory based on machine learned utilization\n      patterns.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://www.densify.com/docs-api/WebHelp_Densify_API/Content/Densify_API.htm\n    baseURL: https://api.densify.com/api/v2\n    tags:\n      - Containers\n      - Kubernetes\n      - Optimization\n      - Recommendations\n      - Right-Sizing\n    properties:\n      - type: Documentation\n        url: https://www.densify.com/docs-api/WebHelp_Densify_API/Content/Densify_API.htm\n      - type: Developer Resources\n        url: https://www.densify.com/dev\n    contact:\n      - FN: Densify Support\n        email: support@densify.com\n        url: https://www.densify.com/contact\ncommon:\n  - type: Website\n    url: https://www.densify.com\n  - type: Portal\n    url: https://portal.densify.com/\n  - type: Documentation\n    url: https://docs.densify.com\n  - type: Developer Resources\n    url: https://www.densify.com/dev\n  - type: Documentation Landing\n    url: https://portal.densify.com/docs-landing/\n  - type: Resources\n    url: https://www.densify.com/resources\n  - type:\
  \ Blog\n    url: https://www.densify.com/blog\n  - type: Pricing\n    url: https://www.densify.com/pricing\n  - type: Free Trial\n    url: https://www.densify.com/free-trial\n  - type: Support\n    url: https://www.densify.com/support\n  - type: GitHub Organization\n    url: https://github.com/densify-dev\n  - type: Terms of Service\n    url: https://www.densify.com/legal\n  - type: Privacy Policy\n    url: https://www.densify.com/privacy-policy\n  - type: Contact\n    url: https://www.densify.com/contact\n  - type: JSON-LD\n    url: json-ld/densify-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/densify-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/densify-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/densify/refs/heads/main/apis.yml
tags:
- Cloud Cost
- Container Optimization
- FinOps
- Kubernetes
- Machine Learning
- Recommendations
- Right-Sizing
url: https://raw.githubusercontent.com/api-evangelist/densify/refs/heads/main/apis.yml
use_cases: []
---
