---
api_count: 8
api_specs:
- filename: nutanix-prism-central-v3-openapi.yml
  format: yaml
  label: Nutanix Prism Central API V3
  slug: prism-central-v3
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nutanix/refs/heads/main/openapi/nutanix-prism-central-v3-openapi.yml
- filename: nutanix-prism-element-v2-openapi.yml
  format: yaml
  label: Nutanix Prism Element API V2
  slug: prism-element-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nutanix/refs/heads/main/openapi/nutanix-prism-element-v2-openapi.yml
apis:
- description: RESTful API for managing Nutanix clusters, VMs, storage, networking, and other infrastructure components through Prism Central. The v3 API uses an intent-based model where resources are defined by the
  name: Nutanix Prism Central API V3
  slug: prism-central-v3
- description: The next-generation v4 API for managing the Nutanix Cloud Platform through Prism Central with GA SDKs for Python, Java, Go, and JavaScript. The v4 API is now the recommended version for production env
  name: Nutanix Prism Central API V4
  slug: prism-central-v4
- description: Cluster-local API for managing individual Nutanix clusters through Prism Element, including storage containers, hosts, virtual machines, and cluster operations.
  name: Nutanix Prism Element API V2
  slug: prism-element-v2
- description: API for managing Kubernetes clusters through Nutanix Karbon, including cluster lifecycle, upgrades, and configuration.
  name: Nutanix Karbon API
  slug: karbon
- description: REST API for Nutanix Database Service (NDB) providing database-as-a-service capabilities for PostgreSQL, MySQL, SQL Server, Oracle, and MongoDB.
  name: Nutanix Database Service API
  slug: ndb
- description: REST API for Nutanix Cloud Clusters (NC2), enabling creation and management of Nutanix clusters on AWS and Azure public clouds.
  name: Nutanix Cloud Clusters API
  slug: nc2
- description: API for Nutanix Cloud Manager Self-Service (formerly Calm), enabling automation of application deployment and lifecycle management through blueprints and runbooks.
  name: Nutanix NCM Self-Service API
  slug: ncm-self-service
- description: API for Foundation and Foundation Central, enabling automated cluster deployment and remote node imaging.
  name: Nutanix Foundation API
  slug: foundation
common:
- title: ''
  type: Website
  url: https://www.nutanix.com
- title: ''
  type: Documentation
  url: https://www.nutanix.dev/
- title: ''
  type: Getting Started
  url: https://www.nutanix.dev/nutanix-api-user-guide/
- title: ''
  type: SDKs
  url: https://www.nutanix.dev/sdk_reference/
- title: ''
  type: Reference
  url: https://www.nutanix.dev/api_references/
- title: ''
  type: Code Samples
  url: https://www.nutanix.dev/code_samples/
- title: ''
  type: Change Log
  url: https://www.nutanix.dev/api-versions/
- title: ''
  type: Blog
  url: https://www.nutanix.dev/blog/
- title: ''
  type: Community
  url: https://next.nutanix.com/
- title: ''
  type: Support
  url: https://www.nutanix.com/support-services/product-support
- title: ''
  type: Status
  url: https://status.nutanix.com/
- title: ''
  type: Login
  url: https://my.nutanix.com/
- title: ''
  type: Sign Up
  url: https://my.nutanix.com/page/signup
- title: ''
  type: GitHub Organization
  url: https://github.com/nutanix
- title: ''
  type: Developer Portal
  url: https://developers.nutanix.com/
- title: ''
  type: Terms of Service
  url: https://www.nutanix.com/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://www.nutanix.com/legal/privacy-notice
created: '2025-03-14'
description: Nutanix is a hyper-converged infrastructure solution that integrates compute, virtualization, storage, networking, and security to power enterprise applications. Nutanix provides public APIs for managing and automating infrastructure including Prism Central, Prism Element, Karbon Kubernetes, Nutanix Database Service (NDB), Cloud Clusters (NC2), NCM Self-Service, and the GA v4 API platform.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Nutanix
skills: []
slug: nutanix
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nutanix\nname: Nutanix\ndescription: >-\n  Nutanix is a hyper-converged infrastructure solution that integrates compute,\n  virtualization, storage, networking, and security to power enterprise applications.\n  Nutanix provides public APIs for managing and automating infrastructure including\n  Prism Central, Prism Element, Karbon Kubernetes, Nutanix Database Service (NDB),\n  Cloud Clusters (NC2), NCM Self-Service, and the GA v4 API platform.\ntype: Index\nposition: Producer\naccess: 1st-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Management\n  - Hyperconverged\n  - Infrastructure\n  - Virtualization\n  - Kubernetes\n  - Database\nurl: https://raw.githubusercontent.com/api-evangelist/nutanix/refs/heads/main/apis.yml\ncreated: '2025-03-14'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: nutanix:prism-central-v3\n    name: Nutanix Prism Central API V3\n    description: >-\n      RESTful\
  \ API for managing Nutanix clusters, VMs, storage, networking, and\n      other infrastructure components through Prism Central. The v3 API uses\n      an intent-based model where resources are defined by their desired state.\n    humanURL: https://www.nutanix.dev/api_references/prism-central-v3/\n    baseURL: https://{{prism-central-ip}}:9440/api/nutanix/v3\n    tags:\n      - Cloud Management\n      - Infrastructure\n      - Virtualization\n    properties:\n      - type: Documentation\n        url: https://www.nutanix.dev/api_references/prism-central-v3/\n      - type: Authentication\n        url: https://www.nutanix.dev/api_references/prism-central-v3/#authentication\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/nutanix/refs/heads/main/openapi/nutanix-prism-central-v3-openapi.yml\n  - aid: nutanix:prism-central-v4\n    name: Nutanix Prism Central API V4\n    description: >-\n      The next-generation v4 API for managing the Nutanix Cloud Platform\
  \ through\n      Prism Central with GA SDKs for Python, Java, Go, and JavaScript. The v4\n      API is now the recommended version for production environments.\n    humanURL: https://www.nutanix.dev/api-reference-v4/\n    baseURL: https://{{prism-central-ip}}:9440/api\n    tags:\n      - Cloud Management\n      - Infrastructure\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://www.nutanix.dev/api-reference-v4/\n      - type: Getting Started\n        url: https://www.nutanix.dev/nutanix-api-user-guide/\n      - type: SDKs\n        url: https://www.nutanix.dev/sdk_reference/\n      - type: Change Log\n        url: https://www.nutanix.dev/api-versions/\n      - type: Developer Portal\n        url: https://developers.nutanix.com/\n  - aid: nutanix:prism-element-v2\n    name: Nutanix Prism Element API V2\n    description: >-\n      Cluster-local API for managing individual Nutanix clusters through Prism\n      Element, including storage containers, hosts, virtual\
  \ machines, and\n      cluster operations.\n    humanURL: https://www.nutanix.dev/api_references/prism-element/\n    baseURL: https://{{cluster-ip}}:9440/PrismGateway/services/rest/v2.0\n    tags:\n      - Cluster Management\n      - Infrastructure\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://www.nutanix.dev/api_references/prism-element/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/nutanix/refs/heads/main/openapi/nutanix-prism-element-v2-openapi.yml\n  - aid: nutanix:karbon\n    name: Nutanix Karbon API\n    description: >-\n      API for managing Kubernetes clusters through Nutanix Karbon, including\n      cluster lifecycle, upgrades, and configuration.\n    humanURL: https://www.nutanix.dev/api_references/karbon/\n    tags:\n      - Container Management\n      - Kubernetes\n      - Orchestration\n    properties:\n      - type: Documentation\n        url: https://www.nutanix.dev/api_references/karbon/\n \
  \ - aid: nutanix:ndb\n    name: Nutanix Database Service API\n    description: >-\n      REST API for Nutanix Database Service (NDB) providing database-as-a-service\n      capabilities for PostgreSQL, MySQL, SQL Server, Oracle, and MongoDB.\n    humanURL: https://www.nutanix.dev/api_reference/apis/ndb0.9.html\n    tags:\n      - Database\n      - DBaaS\n    properties:\n      - type: Documentation\n        url: https://www.nutanix.dev/api_reference/apis/ndb0.9.html\n  - aid: nutanix:nc2\n    name: Nutanix Cloud Clusters API\n    description: >-\n      REST API for Nutanix Cloud Clusters (NC2), enabling creation and management\n      of Nutanix clusters on AWS and Azure public clouds.\n    humanURL: https://www.nutanix.dev/api_reference/apis/nc2.html\n    baseURL: https://api.nutanix.com\n    tags:\n      - AWS\n      - Azure\n      - Hybrid Cloud\n    properties:\n      - type: Documentation\n        url: https://www.nutanix.dev/api_reference/apis/nc2.html\n  - aid: nutanix:ncm-self-service\n\
  \    name: Nutanix NCM Self-Service API\n    description: >-\n      API for Nutanix Cloud Manager Self-Service (formerly Calm), enabling\n      automation of application deployment and lifecycle management through\n      blueprints and runbooks.\n    humanURL: https://www.nutanix.dev/api_references/ncm-self-service/\n    tags:\n      - Automation\n      - Application Management\n      - Orchestration\n      - DevOps\n    properties:\n      - type: Documentation\n        url: https://www.nutanix.dev/api_references/ncm-self-service/\n  - aid: nutanix:foundation\n    name: Nutanix Foundation API\n    description: >-\n      API for Foundation and Foundation Central, enabling automated cluster\n      deployment and remote node imaging.\n    humanURL: https://www.nutanix.dev/api_references/foundation/\n    tags:\n      - Cluster Deployment\n      - Automation\n    properties:\n      - type: Documentation\n        url: https://www.nutanix.dev/api_references/foundation/\ncommon:\n  - type: Website\n\
  \    url: https://www.nutanix.com\n  - type: Documentation\n    url: https://www.nutanix.dev/\n  - type: Getting Started\n    url: https://www.nutanix.dev/nutanix-api-user-guide/\n  - type: SDKs\n    url: https://www.nutanix.dev/sdk_reference/\n  - type: Reference\n    url: https://www.nutanix.dev/api_references/\n  - type: Code Samples\n    url: https://www.nutanix.dev/code_samples/\n  - type: Change Log\n    url: https://www.nutanix.dev/api-versions/\n  - type: Blog\n    url: https://www.nutanix.dev/blog/\n  - type: Community\n    url: https://next.nutanix.com/\n  - type: Support\n    url: https://www.nutanix.com/support-services/product-support\n  - type: Status\n    url: https://status.nutanix.com/\n  - type: Login\n    url: https://my.nutanix.com/\n  - type: Sign Up\n    url: https://my.nutanix.com/page/signup\n  - type: GitHub Organization\n    url: https://github.com/nutanix\n  - type: Developer Portal\n    url: https://developers.nutanix.com/\n  - type: Terms of Service\n    url:\
  \ https://www.nutanix.com/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://www.nutanix.com/legal/privacy-notice\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nutanix/refs/heads/main/apis.yml
tags:
- Cloud Management
- Hyperconverged
- Infrastructure
- Virtualization
- Kubernetes
- Database
url: https://raw.githubusercontent.com/api-evangelist/nutanix/refs/heads/main/apis.yml
use_cases: []
---
