---
api_count: 5
api_specs:
- filename: spot-administration-api-openapi.yml
  format: yaml
  label: Spot Administration API
  slug: administration-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/openapi/spot-administration-api-openapi.yml
- filename: spot-elastigroup-api-openapi.yml
  format: yaml
  label: Spot Elastigroup API
  slug: elastigroup-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/openapi/spot-elastigroup-api-openapi.yml
- filename: spot-ocean-api-openapi.yml
  format: yaml
  label: Spot Ocean API
  slug: ocean-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/openapi/spot-ocean-api-openapi.yml
- filename: spot-eco-api-openapi.yml
  format: yaml
  label: Spot Eco API
  slug: eco-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/openapi/spot-eco-api-openapi.yml
- filename: spot-billing-engine-api-openapi.yml
  format: yaml
  label: Spot Billing Engine API
  slug: billing-engine-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/openapi/spot-billing-engine-api-openapi.yml
apis:
- description: The Spot Administration API provides endpoints for managing organizations, accounts, users, access policies, cloud credentials, subscriptions, and event notifications within the Spot by Flexera platfo
  name: Spot Administration API
  slug: administration-api
- description: The Spot Elastigroup API enables programmatic management of Elastigroup compute groups across AWS, Azure, and GCP. Elastigroup simplifies and automates cloud infrastructure for scale-out applications,
  name: Spot Elastigroup API
  slug: elastigroup-api
- description: The Spot Ocean API provides programmatic management of Ocean Kubernetes clusters across AWS EKS, Azure AKS, GCP GKE, and Amazon ECS. Ocean is a serverless Kubernetes infrastructure engine that automat
  name: Spot Ocean API
  slug: ocean-api
- description: The Spot Eco API provides programmatic access to cloud commitment management and optimization across AWS, Azure, and GCP. Eco automates the purchase, management, and optimization of reserved instances
  name: Spot Eco API
  slug: eco-api
- description: The Spot Billing Engine API provides programmatic access to cloud billing management, cost allocation, and invoicing capabilities. Billing Engine streamlines multi-cloud invoicing with intelligent cos
  name: Spot Billing Engine API
  slug: billing-engine-api
capabilities:
- description: Unified workflow for managing cloud compute optimization across Elastigroup and Ocean, combining instance management, autoscaling, and Kubernetes infrastructure automation. Used by DevOps engineers an
  name: Spot Compute Optimization
  slug: compute-optimization
- description: Unified workflow for cloud financial operations combining commitment management (Eco), billing analytics (Billing Engine), and cost optimization. Used by FinOps teams, cloud finance analysts, and plat
  name: Spot FinOps
  slug: finops
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/spotinst
- title: ''
  type: Documentation
  url: https://docs.spot.io/
- title: ''
  type: APIReference
  url: https://docs.spot.io/api/
- title: ''
  type: OpenAPI
  url: https://github.com/spotinst/openapi
- title: ''
  type: Authentication
  url: https://docs.spot.io/administration/api/create-api-token
- title: ''
  type: Blog
  url: https://spot.io/blog/
- title: ''
  type: TermsOfService
  url: https://spot.io/terms-of-use/
created: '2026-01-02'
description: Spot by Flexera provides cloud infrastructure automation and optimization solutions. The platform includes Elastigroup for compute workload management across spot, reserved, and on-demand instances, Ocean for Kubernetes and container infrastructure automation, and Eco for cloud commitment management. The Spot API enables programmatic control over all platform capabilities including administration, compute groups, Kubernetes clusters, and cost optimization.
features:
- description: Automated management of compute workloads across spot, reserved, and on-demand instances for optimal cost and availability.
  name: Elastigroup Compute Management
- description: Serverless container infrastructure that automatically right-sizes and scales Kubernetes node pools using the lowest-cost compute.
  name: Ocean Kubernetes Automation
- description: Automated purchase and management of reserved instances, savings plans, and committed use discounts across clouds.
  name: Eco Commitment Optimization
- description: Multi-cloud billing management with cost allocation, chargeback, showback, and invoicing analytics.
  name: Billing Engine
- description: Unified management across AWS, Azure, and GCP with consistent APIs and optimization strategies.
  name: Multi-Cloud Support
- description: Predictive and reactive autoscaling that analyzes workload patterns to optimize resource provisioning.
  name: Intelligent Autoscaling
- description: Support for stateful applications with persistent storage, ENI, and IP preservation during instance replacements.
  name: Stateful Workload Management
image: /assets/icons/spot.png
integrations:
- description: Deep integration with EC2, EKS, ECS, EMR, Auto Scaling Groups, and Savings Plans for AWS workload optimization.
  name: AWS
- description: Integration with Azure VMs, AKS, Virtual Machine Scale Sets, and Azure Reserved VM Instances.
  name: Azure
- description: Support for GCP Compute Engine, GKE, and Committed Use Discounts for Google Cloud optimization.
  name: Google Cloud
- description: Native integration with EKS, AKS, GKE, and self-managed Kubernetes clusters through the Ocean controller.
  name: Kubernetes
- description: Official Terraform provider for managing Elastigroup, Ocean, and Eco resources as infrastructure as code.
  name: Terraform
- description: Jenkins plugin for scaling CI/CD build agents dynamically using Elastigroup spot instances.
  name: Jenkins
- description: Ansible modules for automating Spot resource provisioning and configuration management.
  name: Ansible
jsonld:
- class_count: 0
  name: Spot Administration Context
  property_count: 0
  slug: spot-administration-context
- class_count: 0
  name: Spot Billing Engine Context
  property_count: 0
  slug: spot-billing-engine-context
- class_count: 0
  name: Spot Context
  property_count: 9
  slug: spot-context
- class_count: 0
  name: Spot Eco Context
  property_count: 0
  slug: spot-eco-context
- class_count: 0
  name: Spot Elastigroup Context
  property_count: 0
  slug: spot-elastigroup-context
- class_count: 0
  name: Spot Ocean Context
  property_count: 0
  slug: spot-ocean-context
layout: provider
modified: '2026-04-28'
name: Spot
rules:
- name: Spot API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: spot-spectral-rules
skills: []
slug: spot
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spot\nname: Spot\ndescription: >-\n  Spot by Flexera provides cloud infrastructure automation and optimization\n  solutions. The platform includes Elastigroup for compute workload management\n  across spot, reserved, and on-demand instances, Ocean for Kubernetes and\n  container infrastructure automation, and Eco for cloud commitment management.\n  The Spot API enables programmatic control over all platform capabilities\n  including administration, compute groups, Kubernetes clusters, and cost\n  optimization.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/apis.yml\ncreated: '2026-01-02'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - Autoscaling\n  - Cloud Infrastructure\n  - Containers\n  - Cost Optimization\n  - FinOps\n  - Kubernetes\n  - Spot Instances\napis:\n  - aid: spot:administration-api\n\
  \    name: Spot Administration API\n    description: >-\n      The Spot Administration API provides endpoints for managing organizations,\n      accounts, users, access policies, cloud credentials, subscriptions,\n      and event notifications within the Spot by Flexera platform. It enables\n      programmatic control over user permissions, account setup, and cloud\n      provider credential linking for AWS, Azure, and GCP.\n    humanURL: https://docs.spot.io/api/\n    baseURL: https://api.spotinst.io\n    tags:\n      - Access Control\n      - Accounts\n      - Administration\n      - Cloud Credentials\n      - Organizations\n      - Users\n    properties:\n      - type: Documentation\n        url: https://docs.spot.io/api/\n      - type: OpenAPI\n        url: openapi/spot-administration-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/organization.json\n      - type: JSONSchema\n        url: json-schema/account.json\n      - type: JSONSchema\n        url: json-schema/user.json\n\
  \      - type: JSONSchema\n        url: json-schema/access-policy.json\n      - type: JSONSchema\n        url: json-schema/subscription.json\n      - type: JSONLD\n        url: json-ld/spot-context.jsonld\n      - type: JSONLD\n        url: json-ld/spot-administration-context.jsonld\n  - aid: spot:elastigroup-api\n    name: Spot Elastigroup API\n    description: >-\n      The Spot Elastigroup API enables programmatic management of Elastigroup\n      compute groups across AWS, Azure, and GCP. Elastigroup simplifies and\n      automates cloud infrastructure for scale-out applications, continuously\n      analyzing resource usage and optimizing compute resources to ensure\n      availability while leveraging the lowest-cost compute options including\n      spot instances, reserved instances, and on-demand capacity.\n    humanURL: https://docs.spot.io/api/\n    baseURL: https://api.spotinst.io\n    tags:\n      - Autoscaling\n      - AWS\n      - Azure\n      - Compute\n      - Elastigroup\n\
  \      - EMR\n      - GCP\n      - Spot Instances\n    properties:\n      - type: Documentation\n        url: https://docs.spot.io/api/\n      - type: OpenAPI\n        url: openapi/spot-elastigroup-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/elastigroup.json\n      - type: JSONLD\n        url: json-ld/spot-context.jsonld\n      - type: JSONLD\n        url: json-ld/spot-elastigroup-context.jsonld\n  - aid: spot:ocean-api\n    name: Spot Ocean API\n    description: >-\n      The Spot Ocean API provides programmatic management of Ocean Kubernetes\n      clusters across AWS EKS, Azure AKS, GCP GKE, and Amazon ECS. Ocean is\n      a serverless Kubernetes infrastructure engine that automatically manages\n      and optimizes cloud infrastructure for containers, handling node\n      provisioning, scaling, and cost optimization with intelligent use of\n      spot instances, reserved capacity, and on-demand resources.\n    humanURL: https://docs.spot.io/api/\n    baseURL:\
  \ https://api.spotinst.io\n    tags:\n      - AKS\n      - Apache Spark\n      - Autoscaling\n      - Containers\n      - ECS\n      - EKS\n      - GKE\n      - Kubernetes\n      - Ocean\n    properties:\n      - type: Documentation\n        url: https://docs.spot.io/api/\n      - type: OpenAPI\n        url: openapi/spot-ocean-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/ocean-cluster.json\n      - type: JSONSchema\n        url: json-schema/virtual-node-group.json\n      - type: JSONLD\n        url: json-ld/spot-context.jsonld\n      - type: JSONLD\n        url: json-ld/spot-ocean-context.jsonld\n  - aid: spot:eco-api\n    name: Spot Eco API\n    description: >-\n      The Spot Eco API provides programmatic access to cloud commitment\n      management and optimization across AWS, Azure, and GCP. Eco automates\n      the purchase, management, and optimization of reserved instances,\n      savings plans, and committed use discounts to maximize cloud cost\n      savings\
  \ while maintaining flexibility.\n    humanURL: https://docs.spot.io/api/\n    baseURL: https://api.spotinst.io\n    tags:\n      - AWS\n      - Azure\n      - Commitments\n      - Cost Optimization\n      - FinOps\n      - GCP\n      - Reserved Instances\n      - Savings Plans\n    properties:\n      - type: Documentation\n        url: https://docs.spot.io/api/\n      - type: OpenAPI\n        url: openapi/spot-eco-api-openapi.yml\n      - type: JSONLD\n        url: json-ld/spot-context.jsonld\n      - type: JSONLD\n        url: json-ld/spot-eco-context.jsonld\n  - aid: spot:billing-engine-api\n    name: Spot Billing Engine API\n    description: >-\n      The Spot Billing Engine API provides programmatic access to cloud billing\n      management, cost allocation, and invoicing capabilities. Billing Engine\n      streamlines multi-cloud invoicing with intelligent cost allocation,\n      chargeback and showback reporting, and comprehensive billing analytics\n      across AWS, Azure, and\
  \ GCP accounts.\n    humanURL: https://docs.spot.io/api/\n    baseURL: https://api.spotinst.io\n    tags:\n      - Billing\n      - Chargeback\n      - Cost Allocation\n      - Cost Intelligence\n      - FinOps\n      - Invoicing\n    properties:\n      - type: Documentation\n        url: https://docs.spot.io/api/\n      - type: OpenAPI\n        url: openapi/spot-billing-engine-api-openapi.yml\n      - type: JSONLD\n        url: json-ld/spot-context.jsonld\n      - type: JSONLD\n        url: json-ld/spot-billing-engine-context.jsonld\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/spotinst\n  - type: Documentation\n    url: https://docs.spot.io/\n  - type: APIReference\n    url: https://docs.spot.io/api/\n  - type: OpenAPI\n    url: https://github.com/spotinst/openapi\n  - type: Authentication\n    url: https://docs.spot.io/administration/api/create-api-token\n  - type: Blog\n    url: https://spot.io/blog/\n  - type: TermsOfService\n    url: https://spot.io/terms-of-use/\n\
  \  - type: Features\n    data:\n      - name: Elastigroup Compute Management\n        description: Automated management of compute workloads across spot, reserved, and on-demand instances for optimal cost and availability.\n      - name: Ocean Kubernetes Automation\n        description: Serverless container infrastructure that automatically right-sizes and scales Kubernetes node pools using the lowest-cost compute.\n      - name: Eco Commitment Optimization\n        description: Automated purchase and management of reserved instances, savings plans, and committed use discounts across clouds.\n      - name: Billing Engine\n        description: Multi-cloud billing management with cost allocation, chargeback, showback, and invoicing analytics.\n      - name: Multi-Cloud Support\n        description: Unified management across AWS, Azure, and GCP with consistent APIs and optimization strategies.\n      - name: Intelligent Autoscaling\n        description: Predictive and reactive autoscaling\
  \ that analyzes workload patterns to optimize resource provisioning.\n      - name: Stateful Workload Management\n        description: Support for stateful applications with persistent storage, ENI, and IP preservation during instance replacements.\n  - type: UseCases\n    data:\n      - name: Cloud Cost Optimization\n        description: Reduce cloud compute costs by up to 90% by leveraging spot instances with automated fallback to on-demand capacity.\n      - name: Kubernetes Cost Management\n        description: Optimize Kubernetes infrastructure costs with bin-packing, right-sizing, and intelligent node pool management.\n      - name: FinOps Reporting\n        description: Centralized cloud cost visibility with chargeback, showback, and commitment utilization reporting across teams.\n      - name: Big Data Cost Reduction\n        description: Run Apache Spark and EMR workloads on spot instances with automatic scaling and cost optimization.\n      - name: Reserved Instance Management\n\
  \        description: Automate the lifecycle of cloud commitments including purchasing, exchanging, and selling unused reservations.\n      - name: Multi-Cloud Governance\n        description: Unified access control, audit logging, and policy management across AWS, Azure, and GCP accounts.\n  - type: Integrations\n    data:\n      - name: AWS\n        description: Deep integration with EC2, EKS, ECS, EMR, Auto Scaling Groups, and Savings Plans for AWS workload optimization.\n      - name: Azure\n        description: Integration with Azure VMs, AKS, Virtual Machine Scale Sets, and Azure Reserved VM Instances.\n      - name: Google Cloud\n        description: Support for GCP Compute Engine, GKE, and Committed Use Discounts for Google Cloud optimization.\n      - name: Kubernetes\n        description: Native integration with EKS, AKS, GKE, and self-managed Kubernetes clusters through the Ocean controller.\n      - name: Terraform\n        description: Official Terraform provider for managing\
  \ Elastigroup, Ocean, and Eco resources as infrastructure as code.\n      - name: Jenkins\n        description: Jenkins plugin for scaling CI/CD build agents dynamically using Elastigroup spot instances.\n      - name: Ansible\n        description: Ansible modules for automating Spot resource provisioning and configuration management.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/apis.yml
tags:
- Autoscaling
- Cloud Infrastructure
- Containers
- Cost Optimization
- FinOps
- Kubernetes
- Spot Instances
url: https://raw.githubusercontent.com/api-evangelist/spot/refs/heads/main/apis.yml
use_cases:
- description: Reduce cloud compute costs by up to 90% by leveraging spot instances with automated fallback to on-demand capacity.
  name: Cloud Cost Optimization
- description: Optimize Kubernetes infrastructure costs with bin-packing, right-sizing, and intelligent node pool management.
  name: Kubernetes Cost Management
- description: Centralized cloud cost visibility with chargeback, showback, and commitment utilization reporting across teams.
  name: FinOps Reporting
- description: Run Apache Spark and EMR workloads on spot instances with automatic scaling and cost optimization.
  name: Big Data Cost Reduction
- description: Automate the lifecycle of cloud commitments including purchasing, exchanging, and selling unused reservations.
  name: Reserved Instance Management
- description: Unified access control, audit logging, and policy management across AWS, Azure, and GCP accounts.
  name: Multi-Cloud Governance
---
