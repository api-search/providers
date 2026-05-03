---
api_count: 10
api_specs:
- filename: openapi.yaml
  format: yaml
  label: AWS EC2 API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/ec2/2016-11-15/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: AWS VPC API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/ec2/2016-11-15/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: AWS EKS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/eks/2018-08-23/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Google Compute Engine API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/googleapis.com/compute/v1/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Google Kubernetes Engine API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/googleapis.com/container/v1/openapi.yaml
- filename: resources.json
  format: json
  label: Azure Resource Manager API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/resources/resource-manager/Microsoft.Resources/stable/2023-07-01/resources.json
- filename: managedClusters.json
  format: json
  label: Azure AKS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/containerservice/resource-manager/Microsoft.ContainerService/aks/stable/2024-01-01/managedClusters.json
- filename: DigitalOcean-public.v2.yaml
  format: yaml
  label: DigitalOcean API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/digitalocean/openapi/main/specification/DigitalOcean-public.v2.yaml
apis:
- description: Amazon Elastic Compute Cloud (EC2) provides resizable compute capacity in the cloud. The EC2 API manages instances, AMIs, security groups, VPCs, elastic IP addresses, placement groups, and auto-scalin
  name: AWS EC2 API
  slug: ''
- description: Amazon Virtual Private Cloud (VPC) enables launching AWS resources in a logically isolated virtual network. The VPC API manages subnets, route tables, internet gateways, NAT gateways, VPC peering, Pri
  name: AWS VPC API
  slug: ''
- description: Amazon Elastic Kubernetes Service (EKS) is a managed Kubernetes service. The EKS API manages clusters, node groups, Fargate profiles, add-ons, identity providers, and access entries. Powers scalable c
  name: AWS EKS API
  slug: ''
- description: Google Compute Engine provides virtual machines running in Google's infrastructure. The API manages instances, machine types, disks, snapshots, networks, firewall rules, and managed instance groups. I
  name: Google Compute Engine API
  slug: ''
- description: Google Kubernetes Engine (GKE) is a managed, production-ready Kubernetes service with auto-upgrade, auto-repair, cluster autoscaling, Workload Identity, and Autopilot mode. The GKE API manages cluster
  name: Google Kubernetes Engine API
  slug: ''
- description: Azure Resource Manager (ARM) is the deployment and management service for Azure. The REST API provides a consistent way to create, update, delete, and manage Azure resources across all services includ
  name: Azure Resource Manager API
  slug: ''
- description: Azure Kubernetes Service (AKS) simplifies deploying, managing, and scaling containerized applications using Kubernetes. The AKS API manages clusters, agent pools, node pools, maintenance configuration
  name: Azure AKS API
  slug: ''
- description: DigitalOcean's developer-friendly cloud platform API manages Droplets (VMs), Kubernetes clusters, databases, object storage (Spaces), load balancers, VPCs, firewalls, and app platform deployments. Kno
  name: DigitalOcean API
  slug: ''
- description: The Terraform Registry API provides access to infrastructure-as-code (IaC) modules and providers. HashiCorp Terraform is the leading IaC tool for provisioning and managing cloud infrastructure in a de
  name: Terraform Registry API
  slug: ''
- description: Pulumi is a modern infrastructure as code platform that uses general-purpose programming languages (TypeScript, Python, Go, C#, Java, YAML). The Pulumi Cloud API manages stacks, deployments, environme
  name: Pulumi Cloud API
  slug: ''
common:
- title: ''
  type: GitHub Organization
  url: https://github.com/hashicorp
- title: ''
  type: CNCF Landscape
  url: https://landscape.cncf.io/card-mode?category=provisioning
- title: ''
  type: Blog
  url: https://www.cncf.io/blog/
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/json-schema/scalable-infrastructure-compute-instance-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/json-schema/scalable-infrastructure-kubernetes-cluster-schema.json
- title: ''
  type: JSONLd
  url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/json-ld/scalable-infrastructure-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/vocabulary/scalable-infrastructure-vocabulary.yml
created: '2024-01-15'
description: A subject-matter collection covering APIs, tools, and platforms for building and managing scalable cloud infrastructure. This topic encompasses compute, storage, networking, container orchestration, infrastructure as code (IaC), monitoring, and the major cloud providers (AWS, Azure, GCP, DigitalOcean) that power modern scalable systems.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Scalable Infrastructure Context
  property_count: 6
  slug: scalable-infrastructure-context
layout: provider
modified: '2026-05-02'
name: Scalable Infrastructure
skills: []
slug: scalable-infrastructure
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Scalable Infrastructure\ndescription: >-\n  A subject-matter collection covering APIs, tools, and platforms for building\n  and managing scalable cloud infrastructure. This topic encompasses compute,\n  storage, networking, container orchestration, infrastructure as code (IaC),\n  monitoring, and the major cloud providers (AWS, Azure, GCP, DigitalOcean) that\n  power modern scalable systems.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\ntags:\n  - Cloud Infrastructure\n  - Compute\n  - DevOps\n  - Infrastructure as Code\n  - Kubernetes\n  - Networking\n  - Scalability\n  - Storage\napis:\n\n  - name: AWS EC2 API\n    description: >-\n      Amazon Elastic Compute Cloud (EC2) provides resizable compute capacity in\n      the cloud. The EC2 API manages instances,\
  \ AMIs, security groups, VPCs, elastic\n      IP addresses, placement groups, and auto-scaling groups. The most widely used\n      compute API with a 31% global cloud market share.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanUrl: https://aws.amazon.com/ec2/\n    baseUrl: https://ec2.amazonaws.com\n    tags:\n      - Amazon Web Services\n      - Cloud\n      - Compute\n      - EC2\n      - Infrastructure\n      - Instances\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/ec2/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/ec2/2016-11-15/openapi.yaml\n      - type: Pricing\n        url: https://aws.amazon.com/ec2/pricing/\n      - type: Getting Started\n        url: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html\n      - type: SDK\n        url: https://aws.amazon.com/developer/tools/\n    contact:\n\
  \      - type: Support\n        url: https://aws.amazon.com/contact-us/\n\n  - name: AWS VPC API\n    description: >-\n      Amazon Virtual Private Cloud (VPC) enables launching AWS resources in a\n      logically isolated virtual network. The VPC API manages subnets, route tables,\n      internet gateways, NAT gateways, VPC peering, PrivateLink, and network ACLs.\n      Foundational networking for scalable AWS architectures.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanUrl: https://aws.amazon.com/vpc/\n    baseUrl: https://ec2.amazonaws.com\n    tags:\n      - Amazon Web Services\n      - Cloud\n      - Infrastructure\n      - Networking\n      - Security\n      - VPC\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/vpc/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/ec2/2016-11-15/openapi.yaml\n      - type: Pricing\n \
  \       url: https://aws.amazon.com/vpc/pricing/\n    contact:\n      - type: Support\n        url: https://aws.amazon.com/contact-us/\n\n  - name: AWS EKS API\n    description: >-\n      Amazon Elastic Kubernetes Service (EKS) is a managed Kubernetes service.\n      The EKS API manages clusters, node groups, Fargate profiles, add-ons, identity\n      providers, and access entries. Powers scalable containerized workloads on AWS\n      with automatic Kubernetes control plane management.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanUrl: https://aws.amazon.com/eks/\n    baseUrl: https://eks.amazonaws.com\n    tags:\n      - Amazon Web Services\n      - Cloud\n      - Containers\n      - EKS\n      - Kubernetes\n      - Managed Service\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/eks/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/eks/2018-08-23/openapi.yaml\n\
  \      - type: Pricing\n        url: https://aws.amazon.com/eks/pricing/\n      - type: Getting Started\n        url: https://docs.aws.amazon.com/eks/latest/userguide/getting-started.html\n    contact:\n      - type: Support\n        url: https://aws.amazon.com/contact-us/\n\n  - name: Google Compute Engine API\n    description: >-\n      Google Compute Engine provides virtual machines running in Google's infrastructure.\n      The API manages instances, machine types, disks, snapshots, networks, firewall\n      rules, and managed instance groups. Includes powerful autoscaler and load\n      balancing integration. Google Cloud holds ~12% global cloud market share.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanUrl: https://cloud.google.com/compute\n    baseUrl: https://compute.googleapis.com/compute/v1\n    tags:\n      - Cloud\n      - Compute\n      - Google Cloud\n      - Infrastructure\n      - Instances\n      - Virtual Machines\n\
  \    properties:\n      - type: Documentation\n        url: https://cloud.google.com/compute/docs\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/googleapis.com/compute/v1/openapi.yaml\n      - type: Pricing\n        url: https://cloud.google.com/compute/pricing\n      - type: SDK\n        url: https://cloud.google.com/sdk/docs\n    contact:\n      - type: Support\n        url: https://cloud.google.com/support\n\n  - name: Google Kubernetes Engine API\n    description: >-\n      Google Kubernetes Engine (GKE) is a managed, production-ready Kubernetes\n      service with auto-upgrade, auto-repair, cluster autoscaling, Workload Identity,\n      and Autopilot mode. The GKE API manages clusters, node pools, and operations.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanUrl: https://cloud.google.com/kubernetes-engine\n    baseUrl: https://container.googleapis.com/v1\n    tags:\n  \
  \    - Cloud\n      - Containers\n      - GKE\n      - Google Cloud\n      - Kubernetes\n      - Managed Service\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/kubernetes-engine/docs\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/googleapis.com/container/v1/openapi.yaml\n      - type: Pricing\n        url: https://cloud.google.com/kubernetes-engine/pricing\n    contact:\n      - type: Support\n        url: https://cloud.google.com/support\n\n  - name: Azure Resource Manager API\n    description: >-\n      Azure Resource Manager (ARM) is the deployment and management service for\n      Azure. The REST API provides a consistent way to create, update, delete, and\n      manage Azure resources across all services including VMs, storage, networking,\n      and databases. Microsoft Azure holds ~28% global cloud market share.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanUrl: https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview\n    baseUrl: https://management.azure.com\n    tags:\n      - Azure\n      - Cloud\n      - Infrastructure\n      - Management\n      - Microsoft\n      - Resource Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/resources/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/resources/resource-manager/Microsoft.Resources/stable/2023-07-01/resources.json\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/azure/developer/\n    contact:\n      - type: Support\n        url: https://azure.microsoft.com/en-us/support/\n\n  - name: Azure AKS API\n    description: >-\n      Azure Kubernetes Service (AKS) simplifies deploying, managing, and scaling\n      containerized applications using Kubernetes. The AKS API manages clusters,\n      agent pools, node\
  \ pools, maintenance configurations, and trusted access bindings.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanUrl: https://learn.microsoft.com/en-us/azure/aks/\n    baseUrl: https://management.azure.com\n    tags:\n      - AKS\n      - Azure\n      - Cloud\n      - Containers\n      - Kubernetes\n      - Managed Service\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/aks/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/containerservice/resource-manager/Microsoft.ContainerService/aks/stable/2024-01-01/managedClusters.json\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/kubernetes-service/\n    contact:\n      - type: Support\n        url: https://azure.microsoft.com/en-us/support/\n\n  - name: DigitalOcean API\n    description: >-\n      DigitalOcean's developer-friendly cloud\
  \ platform API manages Droplets (VMs),\n      Kubernetes clusters, databases, object storage (Spaces), load balancers, VPCs,\n      firewalls, and app platform deployments. Known for simplicity, transparent\n      pricing, and developer experience for digital-native applications.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanUrl: https://www.digitalocean.com/\n    baseUrl: https://api.digitalocean.com/v2\n    tags:\n      - Cloud\n      - Compute\n      - Developer-Friendly\n      - DigitalOcean\n      - Infrastructure\n      - Kubernetes\n    properties:\n      - type: Documentation\n        url: https://docs.digitalocean.com/reference/api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/digitalocean/openapi/main/specification/DigitalOcean-public.v2.yaml\n      - type: Pricing\n        url: https://www.digitalocean.com/pricing\n      - type: Getting Started\n        url: https://docs.digitalocean.com/products/getting-started/\n\
  \      - type: SDK\n        url: https://github.com/digitalocean/doctl\n    contact:\n      - type: Support\n        url: https://www.digitalocean.com/support/\n      - type: Community\n        url: https://www.digitalocean.com/community\n\n  - name: Terraform Registry API\n    description: >-\n      The Terraform Registry API provides access to infrastructure-as-code (IaC)\n      modules and providers. HashiCorp Terraform is the leading IaC tool for\n      provisioning and managing cloud infrastructure in a declarative, version-controlled\n      way. Critical to scalable infrastructure automation workflows.\n    image: https://registry.terraform.io/images/logo/logo_vertical_dark.svg\n    humanUrl: https://developer.hashicorp.com/terraform\n    baseUrl: https://registry.terraform.io/v1\n    tags:\n      - Infrastructure as Code\n      - IaC\n      - Open Source\n      - Provisioning\n      - Terraform\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/terraform/docs\n\
  \      - type: GitHub\n        url: https://github.com/hashicorp/terraform\n      - type: API Reference\n        url: https://developer.hashicorp.com/terraform/cloud-docs/api-docs\n      - type: Registry\n        url: https://registry.terraform.io/\n    contact:\n      - type: Community\n        url: https://discuss.hashicorp.com/c/terraform-core/\n\n  - name: Pulumi Cloud API\n    description: >-\n      Pulumi is a modern infrastructure as code platform that uses general-purpose\n      programming languages (TypeScript, Python, Go, C#, Java, YAML). The Pulumi\n      Cloud API manages stacks, deployments, environments, and audit logs. Alternative\n      to Terraform with full-language programming model.\n    image: https://www.pulumi.com/logos/brand/avatar/logo-on-white.png\n    humanUrl: https://www.pulumi.com/\n    baseUrl: https://api.pulumi.com/api\n    tags:\n      - Cloud\n      - Infrastructure as Code\n      - IaC\n      - Open Source\n      - Provisioning\n      - Pulumi\n   \
  \ properties:\n      - type: Documentation\n        url: https://www.pulumi.com/docs/\n      - type: GitHub\n        url: https://github.com/pulumi/pulumi\n      - type: API Reference\n        url: https://www.pulumi.com/docs/pulumi-cloud/cloud-rest-api/\n      - type: Pricing\n        url: https://www.pulumi.com/pricing/\n    contact:\n      - type: Community\n        url: https://slack.pulumi.com/\n      - type: GitHub Issues\n        url: https://github.com/pulumi/pulumi/issues\n\ncommon:\n  - type: GitHub Organization\n    url: https://github.com/hashicorp\n  - type: CNCF Landscape\n    url: https://landscape.cncf.io/card-mode?category=provisioning\n  - type: Blog\n    url: https://www.cncf.io/blog/\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/json-schema/scalable-infrastructure-compute-instance-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/json-schema/scalable-infrastructure-kubernetes-cluster-schema.json\n\
  \  - type: JSONLd\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/json-ld/scalable-infrastructure-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/vocabulary/scalable-infrastructure-vocabulary.yml\n\nmaintainers:\n  - FN: API Evangelist\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n\ninclude:\n  - name: Scalability APIs\n    url: https://raw.githubusercontent.com/api-evangelist/scalability/refs/heads/main/apis.yml\n  - name: Scalable Architecture\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/refs/heads/main/apis.yml
tags:
- Cloud Infrastructure
- Compute
- DevOps
- Infrastructure as Code
- Kubernetes
- Networking
- Scalability
- Storage
url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/refs/heads/main/apis.yml
use_cases: []
---
