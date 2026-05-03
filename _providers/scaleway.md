---
api_count: 11
api_specs:
- filename: scaleway-instance-openapi.yml
  format: yaml
  label: Scaleway Instance API
  slug: scaleway-instance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-instance-openapi.yml
- filename: scaleway-kubernetes-openapi.yml
  format: yaml
  label: Scaleway Kubernetes API
  slug: scaleway-kubernetes-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-kubernetes-openapi.yml
- filename: scaleway-iam-openapi.yml
  format: yaml
  label: Scaleway IAM API
  slug: scaleway-iam-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-iam-openapi.yml
- filename: scaleway-load-balancer-openapi.yml
  format: yaml
  label: Scaleway Load Balancer API
  slug: scaleway-load-balancer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-load-balancer-openapi.yml
- filename: scaleway-database-openapi.yml
  format: yaml
  label: Scaleway Managed Database API
  slug: scaleway-database-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-database-openapi.yml
- filename: scaleway-vpc-openapi.yml
  format: yaml
  label: Scaleway VPC API
  slug: scaleway-vpc-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-vpc-openapi.yml
- filename: scaleway-serverless-containers-openapi.yml
  format: yaml
  label: Scaleway Serverless Containers API
  slug: scaleway-serverless-containers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-serverless-containers-openapi.yml
- filename: scaleway-serverless-functions-openapi.yml
  format: yaml
  label: Scaleway Serverless Functions API
  slug: scaleway-serverless-functions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-serverless-functions-openapi.yml
- filename: scaleway-secret-manager-openapi.yml
  format: yaml
  label: Scaleway Secret Manager API
  slug: scaleway-secret-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-secret-manager-openapi.yml
- filename: scaleway-transactional-email-openapi.yml
  format: yaml
  label: Scaleway Transactional Email API
  slug: scaleway-transactional-email-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-transactional-email-openapi.yml
apis:
- description: The Scaleway Instance API allows you to create, manage, and delete virtual machine instances, manage IP addresses, security groups, images, snapshots, volumes, and other compute resources across Scale
  name: Scaleway Instance API
  slug: scaleway-instance-api
- description: The Scaleway Kubernetes API (Kapsule and Kosmos) allows you to create and manage fully-managed Kubernetes clusters on Scaleway infrastructure, including cluster lifecycle management, node pool configu
  name: Scaleway Kubernetes API
  slug: scaleway-kubernetes-api
- description: The Scaleway IAM API provides identity and access management for Scaleway organizations. Manage API keys, users, groups, applications, policies, and permission sets to control access to Scaleway resou
  name: Scaleway IAM API
  slug: scaleway-iam-api
- description: The Scaleway Load Balancer API allows you to create and manage highly available load balancers that distribute incoming traffic across multiple backend servers. Supports TCP, HTTP, and HTTPS load bala
  name: Scaleway Load Balancer API
  slug: scaleway-load-balancer-api
- description: The Scaleway Managed Database API provides access to fully managed PostgreSQL, MySQL, and Redis database services. Create and manage database instances, backups, read replicas, and snapshots with auto
  name: Scaleway Managed Database API
  slug: scaleway-database-api
- description: The Scaleway VPC API enables creation and management of Virtual Private Clouds and regional Private Networks for interconnecting Scaleway resources such as Instances, Load Balancers, and Managed Datab
  name: Scaleway VPC API
  slug: scaleway-vpc-api
- description: The Scaleway Serverless Containers API allows deployment of containerized applications as serverless workloads. Manage namespaces, containers, CRON triggers, and domains with pay-per-use pricing.
  name: Scaleway Serverless Containers API
  slug: scaleway-serverless-containers-api
- description: The Scaleway Serverless Functions API enables deployment of function-as-a-service workloads. Manage function namespaces, functions, triggers, CRON schedules, and custom domains with event-driven execu
  name: Scaleway Serverless Functions API
  slug: scaleway-serverless-functions-api
- description: The Scaleway Secret Manager API provides secure storage and access management for secrets such as API keys, passwords, and certificates. Manage secrets, their versions, and access policies within Scal
  name: Scaleway Secret Manager API
  slug: scaleway-secret-manager-api
- description: The Scaleway Transactional Email API (TEM) provides reliable transactional email delivery services. Manage domains, send emails, track statistics, and monitor email delivery for application notificati
  name: Scaleway Transactional Email API
  slug: scaleway-transactional-email-api
- description: Scaleway Generative APIs provide access to AI language models and generative AI services hosted on Scaleway's European cloud infrastructure. Compatible with the OpenAI API format for easy integration.
  name: Scaleway Generative APIs
  slug: scaleway-generative-apis
capabilities:
- description: Unified workflow capability for managing Scaleway cloud infrastructure including virtual machine instances, Kubernetes clusters, node pools, and secret management. Used by cloud engineers and DevOps t
  name: Scaleway Cloud Infrastructure
  slug: cloud-infrastructure
- description: Unified workflow capability for managing Scaleway managed database services including PostgreSQL, MySQL, and Redis instances, backups, and notifications via transactional email. Used by database admin
  name: Scaleway Database Management
  slug: database-management
- description: Unified workflow capability for managing Scaleway identity and access management, combining IAM policies, API keys, users, groups, applications, and secret storage. Used by platform administrators and
  name: Scaleway Identity and Access
  slug: identity-and-access
- description: Unified workflow capability for managing Scaleway networking infrastructure including Virtual Private Clouds, private networks, subnets, and load balancers. Used by network engineers and cloud archite
  name: Scaleway Networking
  slug: networking
- description: Unified workflow capability for deploying and managing serverless workloads on Scaleway, combining Serverless Containers and Serverless Functions. Used by developers and DevOps teams to deploy event-d
  name: Scaleway Serverless
  slug: serverless
common:
- title: ''
  type: Portal
  url: https://www.scaleway.com/en/developers/
- title: ''
  type: Documentation
  url: https://www.scaleway.com/en/docs/
- title: ''
  type: API Reference
  url: https://www.scaleway.com/en/developers/api/
- title: ''
  type: GitHub
  url: https://github.com/scaleway
- title: ''
  type: SDK
  url: https://github.com/scaleway/scaleway-sdk-go
- title: ''
  type: SDK
  url: https://github.com/scaleway/scaleway-sdk-js
- title: ''
  type: SDK
  url: https://github.com/scaleway/scaleway-sdk-python
- title: ''
  type: CLI
  url: https://github.com/scaleway/scaleway-cli
- title: ''
  type: Terraform Provider
  url: https://github.com/scaleway/terraform-provider-scaleway
- title: ''
  type: Postman
  url: https://www.scaleway.com/en/docs/tutorials/postman-api/
- title: ''
  type: Pricing
  url: https://www.scaleway.com/en/pricing/
- title: ''
  type: Status
  url: https://status.scaleway.com/
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/vocabulary/scaleway-vocabulary.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/json-schema/scaleway-instance-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/json-schema/scaleway-cluster-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/json-schema/scaleway-secret-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/json-ld/scaleway-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/rules/scaleway-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/capabilities/cloud-infrastructure.yaml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/capabilities/networking.yaml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/capabilities/serverless.yaml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/capabilities/identity-and-access.yaml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/capabilities/database-management.yaml
created: '2026-05-02'
description: Scaleway is a European cloud provider offering a full suite of compute, storage, networking, AI, and serverless infrastructure services. Scaleway provides a comprehensive REST API for programmatic management of all cloud resources including Instances, Kubernetes clusters (Kapsule and Kosmos), managed databases, load balancers, VPC networking, object storage, secret management, serverless containers, serverless functions, IAM, generative AI inference, and more. The Scaleway API uses X-Auth-Token header authentication and provides OpenAPI specifications for every product via the developer portal.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 1
  name: Scaleway Context
  property_count: 31
  slug: scaleway-context
layout: provider
modified: '2026-05-02'
name: Scaleway
rules:
- name: Scaleway API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 2
    info: 0
    warn: 6
  slug: scaleway-rules
skills: []
slug: scaleway
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scaleway\nname: Scaleway\ndescription: >-\n  Scaleway is a European cloud provider offering a full suite of compute, storage,\n  networking, AI, and serverless infrastructure services. Scaleway provides a comprehensive\n  REST API for programmatic management of all cloud resources including Instances, Kubernetes\n  clusters (Kapsule and Kosmos), managed databases, load balancers, VPC networking, object\n  storage, secret management, serverless containers, serverless functions, IAM, generative\n  AI inference, and more. The Scaleway API uses X-Auth-Token header authentication and\n  provides OpenAPI specifications for every product via the developer portal.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Cloud Computing\n  - Containers\n  - Database\n  - European Cloud\n  - Infrastructure\n  - Kubernetes\n  - Serverless\n  - Storage\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/apis.yml\n\
  created: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: scaleway:scaleway-instance-api\n    name: Scaleway Instance API\n    description: >-\n      The Scaleway Instance API allows you to create, manage, and delete virtual machine\n      instances, manage IP addresses, security groups, images, snapshots, volumes, and\n      other compute resources across Scaleway's infrastructure zones.\n    humanURL: https://www.scaleway.com/en/developers/api/instances/\n    tags:\n      - Compute\n      - Images\n      - Instances\n      - Security Groups\n      - Snapshots\n      - Virtual Machines\n    properties:\n      - type: Documentation\n        url: https://www.scaleway.com/en/developers/api/instances/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-instance-openapi.yml\n  - aid: scaleway:scaleway-kubernetes-api\n    name: Scaleway Kubernetes API\n    description:\
  \ >-\n      The Scaleway Kubernetes API (Kapsule and Kosmos) allows you to create and manage\n      fully-managed Kubernetes clusters on Scaleway infrastructure, including cluster\n      lifecycle management, node pool configuration, maintenance windows, and upgrades.\n    humanURL: https://www.scaleway.com/en/developers/api/kubernetes/\n    tags:\n      - Containers\n      - Kapsule\n      - Kubernetes\n      - Node Pools\n      - Orchestration\n    properties:\n      - type: Documentation\n        url: https://www.scaleway.com/en/developers/api/kubernetes/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-kubernetes-openapi.yml\n  - aid: scaleway:scaleway-iam-api\n    name: Scaleway IAM API\n    description: >-\n      The Scaleway IAM API provides identity and access management for Scaleway\n      organizations. Manage API keys, users, groups, applications, policies, and\n      permission sets\
  \ to control access to Scaleway resources.\n    humanURL: https://www.scaleway.com/en/developers/api/iam/\n    tags:\n      - Access Control\n      - API Keys\n      - Groups\n      - IAM\n      - Identity\n      - Permissions\n      - Policies\n    properties:\n      - type: Documentation\n        url: https://www.scaleway.com/en/developers/api/iam/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-iam-openapi.yml\n  - aid: scaleway:scaleway-load-balancer-api\n    name: Scaleway Load Balancer API\n    description: >-\n      The Scaleway Load Balancer API allows you to create and manage highly available\n      load balancers that distribute incoming traffic across multiple backend servers.\n      Supports TCP, HTTP, and HTTPS load balancing with health checks, SSL termination,\n      and session persistence.\n    humanURL: https://www.scaleway.com/en/developers/api/load-balancer/zoned-api/\n   \
  \ tags:\n      - Backend\n      - Health Checks\n      - Load Balancing\n      - Networking\n      - SSL\n    properties:\n      - type: Documentation\n        url: https://www.scaleway.com/en/developers/api/load-balancer/zoned-api/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-load-balancer-openapi.yml\n  - aid: scaleway:scaleway-database-api\n    name: Scaleway Managed Database API\n    description: >-\n      The Scaleway Managed Database API provides access to fully managed PostgreSQL,\n      MySQL, and Redis database services. Create and manage database instances, backups,\n      read replicas, and snapshots with automated patch management.\n    humanURL: https://www.scaleway.com/en/developers/api/managed-databases-for-postgresql-and-mysql/\n    tags:\n      - Backup\n      - Database\n      - MySQL\n      - PostgreSQL\n      - Redis\n      - Relational Database\n    properties:\n      -\
  \ type: Documentation\n        url: https://www.scaleway.com/en/developers/api/managed-databases-for-postgresql-and-mysql/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-database-openapi.yml\n  - aid: scaleway:scaleway-vpc-api\n    name: Scaleway VPC API\n    description: >-\n      The Scaleway VPC API enables creation and management of Virtual Private Clouds\n      and regional Private Networks for interconnecting Scaleway resources such as\n      Instances, Load Balancers, and Managed Databases within a private L2 network.\n    humanURL: https://www.scaleway.com/en/developers/api/vpc/\n    tags:\n      - Network Isolation\n      - Networking\n      - Private Networks\n      - VPC\n      - Virtual Private Cloud\n    properties:\n      - type: Documentation\n        url: https://www.scaleway.com/en/developers/api/vpc/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-vpc-openapi.yml\n\
  \  - aid: scaleway:scaleway-serverless-containers-api\n    name: Scaleway Serverless Containers API\n    description: >-\n      The Scaleway Serverless Containers API allows deployment of containerized applications\n      as serverless workloads. Manage namespaces, containers, CRON triggers, and domains\n      with pay-per-use pricing.\n    humanURL: https://www.scaleway.com/en/developers/api/serverless-containers/\n    tags:\n      - Containers\n      - CRON\n      - Docker\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://www.scaleway.com/en/developers/api/serverless-containers/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-serverless-containers-openapi.yml\n  - aid: scaleway:scaleway-serverless-functions-api\n    name: Scaleway Serverless Functions API\n    description: >-\n      The Scaleway Serverless Functions API enables deployment of function-as-a-service\n\
  \      workloads. Manage function namespaces, functions, triggers, CRON schedules, and\n      custom domains with event-driven execution.\n    humanURL: https://www.scaleway.com/en/developers/api/serverless-functions/\n    tags:\n      - Event-Driven\n      - FaaS\n      - Functions\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://www.scaleway.com/en/developers/api/serverless-functions/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-serverless-functions-openapi.yml\n  - aid: scaleway:scaleway-secret-manager-api\n    name: Scaleway Secret Manager API\n    description: >-\n      The Scaleway Secret Manager API provides secure storage and access management\n      for secrets such as API keys, passwords, and certificates. Manage secrets, their\n      versions, and access policies within Scaleway projects.\n    humanURL: https://www.scaleway.com/en/developers/api/secret-manager/\n\
  \    tags:\n      - Certificates\n      - Credentials\n      - Secrets\n      - Security\n      - Vault\n    properties:\n      - type: Documentation\n        url: https://www.scaleway.com/en/developers/api/secret-manager/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-secret-manager-openapi.yml\n  - aid: scaleway:scaleway-transactional-email-api\n    name: Scaleway Transactional Email API\n    description: >-\n      The Scaleway Transactional Email API (TEM) provides reliable transactional\n      email delivery services. Manage domains, send emails, track statistics, and\n      monitor email delivery for application notifications and alerts.\n    humanURL: https://www.scaleway.com/en/developers/api/transactional-email/\n    tags:\n      - Email\n      - Messaging\n      - Notifications\n      - SMTP\n      - Transactional Email\n    properties:\n      - type: Documentation\n        url: https://www.scaleway.com/en/developers/api/transactional-email/\n\
  \      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/openapi/scaleway-transactional-email-openapi.yml\n  - aid: scaleway:scaleway-generative-apis\n    name: Scaleway Generative APIs\n    description: >-\n      Scaleway Generative APIs provide access to AI language models and generative AI\n      services hosted on Scaleway's European cloud infrastructure. Compatible with the\n      OpenAI API format for easy integration.\n    humanURL: https://www.scaleway.com/en/docs/generative-apis/\n    tags:\n      - AI\n      - Artificial Intelligence\n      - Generative AI\n      - Language Models\n      - LLM\n    properties:\n      - type: Documentation\n        url: https://www.scaleway.com/en/docs/generative-apis/\n      - type: Getting Started\n        url: https://www.scaleway.com/en/docs/generative-apis/quickstart/\n      - type: OpenAI Compatibility\n        url: https://www.scaleway.com/en/docs/managed-inference/reference-content/openai-compatibility/\n\
  common:\n  - type: Portal\n    url: https://www.scaleway.com/en/developers/\n  - type: Documentation\n    url: https://www.scaleway.com/en/docs/\n  - type: API Reference\n    url: https://www.scaleway.com/en/developers/api/\n  - type: GitHub\n    url: https://github.com/scaleway\n  - type: SDK\n    url: https://github.com/scaleway/scaleway-sdk-go\n  - type: SDK\n    url: https://github.com/scaleway/scaleway-sdk-js\n  - type: SDK\n    url: https://github.com/scaleway/scaleway-sdk-python\n  - type: CLI\n    url: https://github.com/scaleway/scaleway-cli\n  - type: Terraform Provider\n    url: https://github.com/scaleway/terraform-provider-scaleway\n  - type: Postman\n    url: https://www.scaleway.com/en/docs/tutorials/postman-api/\n  - type: Pricing\n    url: https://www.scaleway.com/en/pricing/\n  - type: Status\n    url: https://status.scaleway.com/\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/vocabulary/scaleway-vocabulary.yml\n\
  \  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/json-schema/scaleway-instance-schema.json\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/json-schema/scaleway-cluster-schema.json\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/json-schema/scaleway-secret-schema.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/json-ld/scaleway-context.jsonld\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/rules/scaleway-rules.yml\n  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/capabilities/cloud-infrastructure.yaml\n  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/capabilities/networking.yaml\n\
  \  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/capabilities/serverless.yaml\n  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/capabilities/identity-and-access.yaml\n  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/capabilities/database-management.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/apis.yml
tags:
- AI
- Cloud Computing
- Containers
- Database
- European Cloud
- Infrastructure
- Kubernetes
- Serverless
- Storage
url: https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/apis.yml
use_cases: []
---
