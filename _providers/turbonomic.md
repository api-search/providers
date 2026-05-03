---
api_count: 1
api_specs:
- filename: turbonomic-rest-api-openapi.yml
  format: yaml
  label: Turbonomic REST API
  slug: turbonomic-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/turbonomic/refs/heads/main/openapi/turbonomic-rest-api-openapi.yml
apis:
- description: The Turbonomic REST API provides programmatic access to the Turbonomic Application Resource Management platform. It enables automation of resource optimization actions, querying of entities (VMs, cont
  name: Turbonomic REST API
  slug: turbonomic-rest-api
capabilities:
- description: Workflow capability for automated resource optimization using IBM Turbonomic. Combines entity management, action automation, group scoping, and policy control to enable cloud architects and platform e
  name: Turbonomic Resource Optimization
  slug: resource-optimization
common:
- title: ''
  type: Website
  url: https://www.ibm.com/products/turbonomic
- title: ''
  type: Documentation
  url: https://www.ibm.com/docs/en/tarm/8.19.3
- title: ''
  type: SwaggerUI
  url: https://try.turbonomic.io/apidoc/
- title: ''
  type: GettingStarted
  url: https://www.ibm.com/docs/en/tarm/8.13.0?topic=reference-getting-started-turbonomic-rest-api
- title: ''
  type: GitHub Organization
  url: https://github.com/turbonomic
- title: ''
  type: Blog
  url: https://www.ibm.com/blog/turbonomic/
- title: ''
  type: Pricing
  url: https://www.ibm.com/products/turbonomic/pricing
- title: ''
  type: Marketplace
  url: https://aws.amazon.com/marketplace/pp/prodview-5r3k3snu4ttnm
- title: ''
  type: Support
  url: https://www.ibm.com/mysupport/s/topic/0TO0z000000ZnCCGA0/turbonomic-application-resource-management
- title: ''
  type: Community
  url: https://developer.ibm.com/components/turbonomic/
- title: ''
  type: Terms of Service
  url: https://www.ibm.com/terms
- title: ''
  type: Privacy Policy
  url: https://www.ibm.com/privacy
- title: ''
  type: OpenAPI
  url: openapi/turbonomic-rest-api-openapi.yml
- title: ''
  type: KubernetesCRD
  url: crd/charts.helm.k8s.io_xls.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/turbonomic-vocabulary.yml
- title: ''
  type: JSON-LD
  url: json-ld/turbonomic-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/turbonomic-entity-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/turbonomic-action-schema.json
created: '2026-03-16'
description: IBM Turbonomic is an Application Resource Management (ARM) platform that uses AI-powered automation to continuously analyze and optimize application performance and cloud costs across hybrid and multi-cloud environments. Turbonomic provides a comprehensive REST API enabling programmatic access to resource management data, workload actions, markets, policies, groups, templates, and topology information. The platform integrates with AWS, Azure, GCP, Kubernetes, VMware, and dozens of APM and ITSM tools.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Turbonomic Context
  property_count: 7
  slug: turbonomic-context
layout: provider
modified: '2026-05-03'
name: IBM Turbonomic
rules:
- name: IBM Turbonomic API Rules
  rule_count: 12
  severity_counts:
    error: 2
    hint: 0
    info: 3
    warn: 7
  slug: turbonomic-rest-api-rules
skills: []
slug: turbonomic
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: turbonomic\nname: IBM Turbonomic\ndescription: >-\n  IBM Turbonomic is an Application Resource Management (ARM) platform that uses AI-powered\n  automation to continuously analyze and optimize application performance and cloud costs across\n  hybrid and multi-cloud environments. Turbonomic provides a comprehensive REST API enabling\n  programmatic access to resource management data, workload actions, markets, policies, groups,\n  templates, and topology information. The platform integrates with AWS, Azure, GCP, Kubernetes,\n  VMware, and dozens of APM and ITSM tools.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://www.ibm.com/products/turbonomic\ntags:\n  - Application Resource Management\n  - Cloud Cost Optimization\n  - Cloud Management\n  - Hybrid Cloud\n  - IBM\n  - Kubernetes\n  - Multi-Cloud\n  - Workload Optimization\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntype: Index\napis:\n\
  \  - aid: turbonomic:turbonomic-rest-api\n    name: Turbonomic REST API\n    description: >-\n      The Turbonomic REST API provides programmatic access to the Turbonomic Application\n      Resource Management platform. It enables automation of resource optimization actions,\n      querying of entities (VMs, containers, applications, storage), management of markets\n      and policies, retrieval of statistics and analytics, group management, template\n      administration, and topology exploration across hybrid cloud environments. The API\n      uses bearer token authentication obtained via a login endpoint.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.ibm.com/docs/en/tarm/8.19.3?topic=reference-turbonomic-rest-api-endpoints\n    baseURL: https://{turbonomic_host}/api/v3\n    tags:\n      - Actions\n      - Application Resource Management\n      - Automation\n      - Cloud Cost Optimization\n      - Entities\n      -\
  \ Groups\n      - Markets\n      - Policies\n      - Statistics\n      - Topology\n      - Workload Optimization\n    properties:\n      - type: Documentation\n        url: https://www.ibm.com/docs/en/tarm/8.19.3?topic=reference-turbonomic-rest-api-endpoints\n      - type: SwaggerUI\n        url: https://try.turbonomic.io/apidoc/\n      - type: GettingStarted\n        url: https://www.ibm.com/docs/en/tarm/8.13.0?topic=reference-getting-started-turbonomic-rest-api\n      - type: Reference\n        url: https://www.ibm.com/docs/en/tarm/8.19.3?topic=reference-turbonomic-rest-api-endpoints\n      - type: OpenAPI\n        url: openapi/turbonomic-rest-api-openapi.yml\n      - type: KubernetesCRD\n        url: crd/charts.helm.k8s.io_xls.yaml\n    features:\n      - name: AI-Powered Actions\n        description: >-\n          Retrieve, approve, and execute resource optimization actions recommended by\n          Turbonomic's AI engine across VMs, containers, and cloud resources.\n      - name:\
  \ Entity Management\n        description: >-\n          Query and manage entities including virtual machines, containers, applications,\n          storage, and cloud services across hybrid environments.\n      - name: Market Analytics\n        description: >-\n          Access Turbonomic markets to retrieve projected states, action impacts, and\n          optimization scenarios for capacity planning.\n      - name: Policy Management\n        description: >-\n          Create and manage automation policies that govern how Turbonomic executes\n          optimization actions for different entity types and scopes.\n      - name: Statistics and Reporting\n        description: >-\n          Retrieve historical and projected statistics for resource utilization,\n          cost metrics, and performance data across the managed environment.\n      - name: Group Management\n        description: >-\n          Create and manage logical groups of entities for scoped policy application,\n          reporting,\
  \ and workflow automation.\n      - name: Template Management\n        description: >-\n          Define and manage resource templates used for workload placement and\n          hardware refresh planning.\n      - name: Topology Discovery\n        description: >-\n          Explore the topology of managed environments including supply chains,\n          dependencies, and infrastructure relationships.\n    useCases:\n      - name: Automated Right-Sizing\n        description: >-\n          Automate VM and container right-sizing actions to eliminate waste and\n          ensure application performance SLAs.\n      - name: Cloud Cost Optimization\n        description: >-\n          Continuously identify and execute cost-saving actions across AWS, Azure,\n          GCP, and hybrid cloud environments.\n      - name: Kubernetes Resource Optimization\n        description: >-\n          Optimize container resource limits and requests in Kubernetes clusters\n          to reduce costs and prevent\
  \ out-of-memory issues.\n      - name: ITSM Integration\n        description: >-\n          Integrate Turbonomic action recommendations with ITSM platforms like\n          ServiceNow to route actions through change management workflows.\n      - name: Capacity Planning\n        description: >-\n          Use market simulations and statistics APIs to plan infrastructure\n          capacity for future workload demands.\n    integrations:\n      - name: AWS\n        description: Cloud resource management and optimization for EC2, RDS, ECS, and EKS.\n        url: https://aws.amazon.com/marketplace/pp/prodview-5r3k3snu4ttnm\n      - name: Microsoft Azure\n        description: Cloud resource management and optimization for Azure VMs and AKS.\n        url: https://www.ibm.com/products/turbonomic\n      - name: Google Cloud\n        description: GCP compute and GKE container optimization.\n        url: https://www.ibm.com/products/turbonomic\n      - name: Kubernetes\n        description: Native\
  \ Kubernetes integration via kubeturbo for pod and container optimization.\n        url: https://github.com/turbonomic/kubeturbo\n      - name: VMware\n        description: vSphere VM right-sizing and datacenter optimization.\n        url: https://www.ibm.com/products/turbonomic\n      - name: HashiCorp Terraform\n        description: Infrastructure-as-code optimization for cloud-defined workloads.\n        url: https://www.ibm.com/new/announcements/ibm-turbonomic-with-hashicorp-terraform\n      - name: ServiceNow\n        description: ITSM integration for action change management and approval workflows.\n        url: https://www.ibm.com/products/turbonomic\n      - name: IBM Kubecost\n        description: Container cost visibility integrated with Kubernetes optimization actions.\n        url: https://www.ibm.com/products/turbonomic\ncommon:\n  - type: Website\n    url: https://www.ibm.com/products/turbonomic\n  - type: Documentation\n    url: https://www.ibm.com/docs/en/tarm/8.19.3\n\
  \  - type: SwaggerUI\n    url: https://try.turbonomic.io/apidoc/\n  - type: GettingStarted\n    url: https://www.ibm.com/docs/en/tarm/8.13.0?topic=reference-getting-started-turbonomic-rest-api\n  - type: GitHub Organization\n    url: https://github.com/turbonomic\n  - type: Blog\n    url: https://www.ibm.com/blog/turbonomic/\n  - type: Pricing\n    url: https://www.ibm.com/products/turbonomic/pricing\n  - type: Marketplace\n    url: https://aws.amazon.com/marketplace/pp/prodview-5r3k3snu4ttnm\n  - type: Support\n    url: https://www.ibm.com/mysupport/s/topic/0TO0z000000ZnCCGA0/turbonomic-application-resource-management\n  - type: Community\n    url: https://developer.ibm.com/components/turbonomic/\n  - type: Terms of Service\n    url: https://www.ibm.com/terms\n  - type: Privacy Policy\n    url: https://www.ibm.com/privacy\n  - type: OpenAPI\n    url: openapi/turbonomic-rest-api-openapi.yml\n  - type: KubernetesCRD\n    url: crd/charts.helm.k8s.io_xls.yaml\n  - type: Vocabulary\n    url:\
  \ vocabulary/turbonomic-vocabulary.yml\n  - type: JSON-LD\n    url: json-ld/turbonomic-context.jsonld\n  - type: JSONSchema\n    url: json-schema/turbonomic-entity-schema.json\n  - type: JSONSchema\n    url: json-schema/turbonomic-action-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/turbonomic/refs/heads/main/apis.yml
tags:
- Application Resource Management
- Cloud Cost Optimization
- Cloud Management
- Hybrid Cloud
- IBM
- Kubernetes
- Multi-Cloud
- Workload Optimization
url: https://www.ibm.com/products/turbonomic
use_cases: []
---
