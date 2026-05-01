---
api_count: 2
api_specs:
- filename: gke-on-prem-api-openapi.yml
  format: yaml
  label: GKE On-Prem API
  slug: gke-on-prem-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-anthos/refs/heads/main/openapi/gke-on-prem-api-openapi.yml
apis:
- description: The GKE On-Prem API provides programmatic access to manage the lifecycle of on-premises Kubernetes clusters running on VMware or bare metal infrastructure as part of Google Distributed Cloud. Develope
  name: GKE On-Prem API
  slug: gke-on-prem-api
- description: The Anthos Multicloud API provides programmatic access to manage Anthos clusters running on other public clouds such as AWS and Azure. Developers can use the API to create, update, and delete attached
  name: Anthos Multicloud API
  slug: anthos-multicloud-api
common:
- title: ''
  type: Getting Started
  url: https://cloud.google.com/anthos/docs/setup/overview
- title: ''
  type: Pricing
  url: https://cloud.google.com/anthos/pricing
- title: ''
  type: JSON-LD
  url: json-ld/google-anthos-context.jsonld
created: '2026-03-13'
description: Google Anthos is a managed application platform that extends Google Cloud services and engineering practices to hybrid and multi-cloud environments. Built on Kubernetes, Anthos enables consistent development and operations across on-premises data centers, Google Cloud, and other public clouds like AWS and Azure, with centralized management, policy enforcement, and service mesh capabilities.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Google Anthos Context
  property_count: 3
  slug: google-anthos-context
layout: provider
modified: '2026-04-28'
name: Google Anthos
skills: []
slug: google-anthos
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-anthos\nname: Google Anthos\ndescription: >-\n  Google Anthos is a managed application platform that extends Google Cloud\n  services and engineering practices to hybrid and multi-cloud environments.\n  Built on Kubernetes, Anthos enables consistent development and operations\n  across on-premises data centers, Google Cloud, and other public clouds like\n  AWS and Azure, with centralized management, policy enforcement, and service\n  mesh capabilities.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/google-anthos/refs/heads/main/apis.yml\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Container Platform\n  - Hybrid Cloud\n  - Kubernetes\n  - Multi-Cloud\n  - On-Premises\n  - Service Mesh\napis:\n  - aid: google-anthos:gke-on-prem-api\n    name: GKE On-Prem API\n    description: >-\n      The GKE On-Prem API provides programmatic\
  \ access to manage the lifecycle\n      of on-premises Kubernetes clusters running on VMware or bare metal\n      infrastructure as part of Google Distributed Cloud. Developers can use the\n      API to create, update, delete, and monitor on-premises clusters, manage\n      node pools, and handle cluster enrollment and upgrades through the Google\n      Cloud control plane.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/anthos/clusters/docs/on-prem-api/overview\n    baseURL: https://gkeonprem.googleapis.com\n    tags:\n      - Bare Metal\n      - Clusters\n      - Kubernetes\n      - On-Premises\n      - VMware\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/anthos/clusters/docs/on-prem-api/reference/rest\n      - type: OpenAPI\n        url: openapi/gke-on-prem-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/google-anthos-cluster-schema.json\n  - aid:\
  \ google-anthos:anthos-multicloud-api\n    name: Anthos Multicloud API\n    description: >-\n      The Anthos Multicloud API provides programmatic access to manage Anthos\n      clusters running on other public clouds such as AWS and Azure. Developers\n      can use the API to create, update, and delete attached clusters and manage\n      node pools on external cloud providers while maintaining centralized\n      management through Google Cloud.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/anthos/clusters/docs/multi-cloud\n    baseURL: https://gkemulticloud.googleapis.com\n    tags:\n      - AWS\n      - Azure\n      - Clusters\n      - Multi-Cloud\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/anthos/clusters/docs/multi-cloud\ncommon:\n  - type: Getting Started\n    url: https://cloud.google.com/anthos/docs/setup/overview\n  - type: Pricing\n    url: https://cloud.google.com/anthos/pricing\n\
  \  - type: JSON-LD\n    url: json-ld/google-anthos-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-anthos/refs/heads/main/apis.yml
tags:
- Container Platform
- Hybrid Cloud
- Kubernetes
- Multi-Cloud
- On-Premises
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/google-anthos/refs/heads/main/apis.yml
use_cases: []
---
