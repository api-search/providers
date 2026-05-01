---
api_count: 1
api_specs:
- filename: amazon-batch-openapi.yml
  format: yaml
  label: Amazon Batch API
  slug: amazon-batch-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-batch/refs/heads/main/openapi/amazon-batch-openapi.yml
apis:
- description: The AWS Batch API enables programmatic management of batch computing workloads, including creating and managing compute environments, job queues, job definitions, scheduling policies, and submitting a
  name: Amazon Batch API
  slug: amazon-batch-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://console.aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/batch/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/batch/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/hpc/category/compute/aws-batch/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/batch
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: ServiceStatus
  url: https://status.aws.amazon.com/
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/aws-batch
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://aws.amazon.com/security/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
created: '2024-01-15'
description: AWS Batch enables developers, scientists, and engineers to easily and efficiently run hundreds of thousands of batch computing jobs on AWS. AWS Batch dynamically provisions the optimal quantity and type of compute resources (EC2 On-Demand, EC2 Spot, Fargate, EKS) based on the volume and specific resource requirements of the batch jobs submitted, with no need to install or manage batch computing software or server clusters.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Amazon Batch Context
  property_count: 5
  slug: amazon-batch-context
layout: provider
modified: '2026-04-19'
name: Amazon Batch
skills: []
slug: amazon-batch
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-batch\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-batch/refs/heads/main/apis.yml\nname: Amazon Batch\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nspecificationVersion: '0.19'\ndescription: >-\n  AWS Batch enables developers, scientists, and engineers to easily and\n  efficiently run hundreds of thousands of batch computing jobs on AWS.\n  AWS Batch dynamically provisions the optimal quantity and type of compute\n  resources (EC2 On-Demand, EC2 Spot, Fargate, EKS) based on the volume\n  and specific resource requirements of the batch jobs submitted, with no\n  need to install or manage batch computing software or server clusters.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\ntags:\n  - AWS\n  - Batch Computing\n  - Compute\n  - Containers\n  - HPC\n  - Job Scheduling\n  - Serverless\n  - Fargate\n  - EKS\n  - Spot Instances\napis:\n  - aid: amazon-batch:amazon-batch-api\n    name: Amazon\
  \ Batch API\n    description: >-\n      The AWS Batch API enables programmatic management of batch computing\n      workloads, including creating and managing compute environments, job\n      queues, job definitions, scheduling policies, and submitting and\n      monitoring batch jobs at any scale. Supports single-node jobs, array\n      jobs for parameter sweeps, and multi-node parallel jobs for HPC.\n    humanURL: https://aws.amazon.com/batch/\n    baseURL: https://batch.amazonaws.com\n    tags:\n      - Batch Computing\n      - Compute\n      - HPC\n      - Job Scheduling\n      - Containers\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/batch/latest/userguide/what-is-batch.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-batch/refs/heads/main/openapi/amazon-batch-openapi.yml\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/batch/2016-08-10/openapi.json\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-batch/refs/heads/main/json-schema/amazon-batch-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-batch/refs/heads/main/json-structure/batch-resource-structure.json\n      - type: JSONLD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-batch/refs/heads/main/json-ld/amazon-batch-context.jsonld\n      - type: SpectralRuleset\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-batch/refs/heads/main/spectral/ruleset.yml\n      - type: Capabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-batch/refs/heads/main/capabilities/capabilities.yml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-batch/refs/heads/main/vocabulary/vocabulary.yml\n     \
  \ - type: Pricing\n        url: https://aws.amazon.com/batch/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/batch/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/batch/faqs/\n      - type: UserGuide\n        url: https://docs.aws.amazon.com/batch/latest/userguide/what-is-batch.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/batch/latest/APIReference/Welcome.html\n      - type: CLIReference\n        url: https://docs.aws.amazon.com/cli/latest/reference/batch/\n      - type: Security\n        url: https://docs.aws.amazon.com/batch/latest/userguide/security.html\n    contact:\n      - FN: Amazon Web Services\n        url: https://aws.amazon.com/contact-us/\n    features:\n      - name: Managed Compute Environments\n        description: >-\n          Automatically provision, scale, and terminate EC2 On-Demand, Spot,\n          Fargate, or EKS compute resources based on job demand.\n      - name: Array Jobs\n \
  \       description: >-\n          Run N identical parallel job instances with unique array indices for\n          parameter sweeps, data parallelism, and large-scale simulations.\n      - name: Multi-Node Parallel Jobs\n        description: >-\n          Execute tightly-coupled HPC workloads (MPI) across multiple EC2\n          instances in a single coordinated job.\n      - name: Spot Instance Integration\n        description: >-\n          Run batch jobs on EC2 Spot Instances with automatic retry on\n          interruption, reducing compute costs by up to 90%.\n      - name: Fair-Share Scheduling\n        description: >-\n          Distribute compute resources equitably across users and teams using\n          configurable share weights and usage tracking.\n      - name: GPU Support\n        description: >-\n          Run GPU-accelerated workloads including machine learning training\n          and scientific simulations on GPU instance types.\n      - name: EKS Integration\n        description:\
  \ >-\n          Run batch jobs on Amazon EKS clusters with Kubernetes-native\n          pod specifications and resource management.\n    useCases:\n      - name: Scientific Computing\n        description: >-\n          Run genomics, climate modeling, and other large-scale simulations\n          with HPC array jobs on managed compute environments.\n      - name: Data Processing Pipelines\n        description: >-\n          Process large datasets in parallel with array jobs and Spot Instances\n          for cost-efficient ETL and analytics workloads.\n      - name: Machine Learning Training\n        description: >-\n          Run distributed ML training jobs across GPU instances with\n          multi-node parallel job support.\n      - name: Media Transcoding\n        description: >-\n          Process large volumes of media files in parallel using containerized\n          transcoding jobs on managed compute environments.\n    integrations:\n      - name: Amazon ECR\n        description:\
  \ Store and pull container images for batch job definitions from Amazon Elastic Container Registry\n      - name: Amazon S3\n        description: Read input data and write job output to Amazon S3 storage\n      - name: Amazon ECS\n        description: AWS Batch uses ECS under the hood for container orchestration on EC2 and Fargate\n      - name: Amazon EKS\n        description: Run batch jobs on Kubernetes clusters via Amazon Elastic Kubernetes Service\n      - name: AWS CloudWatch Logs\n        description: Stream job container logs to CloudWatch Logs for monitoring and debugging\n      - name: AWS Step Functions\n        description: Orchestrate multi-step workflows with AWS Batch jobs as workflow tasks\n      - name: Amazon EventBridge\n        description: Trigger batch jobs on schedule or in response to events\n    solutions:\n      - name: Cost-Optimized HPC\n        description: >-\n          Use Spot Instances with SPOT_CAPACITY_OPTIMIZED allocation strategy\n          to run HPC\
  \ workloads at a fraction of On-Demand pricing.\n      - name: Serverless Batch\n        description: >-\n          Use Fargate compute environments to run batch jobs with no EC2\n          instance management and per-second billing.\ncommon:\n  - type: Portal\n    url: https://console.aws.amazon.com/\n  - type: Website\n    url: https://aws.amazon.com/batch/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/batch/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/hpc/category/compute/aws-batch/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/batch\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: ServiceStatus\n\
  \    url: https://status.aws.amazon.com/\n  - type: KnowledgeCenter\n    url: https://repost.aws/knowledge-center\n  - type: YouTube\n    url: https://www.youtube.com/user/AmazonWebServices\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/aws-batch\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: Security\n    url: https://aws.amazon.com/security/\n  - type: Compliance\n    url: https://aws.amazon.com/compliance/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-batch/refs/heads/main/apis.yml
tags:
- Batch Computing
- Compute
- Containers
- HPC
- Job Scheduling
- Serverless
- Fargate
- EKS
- Spot Instances
url: https://raw.githubusercontent.com/api-evangelist/amazon-batch/refs/heads/main/apis.yml
use_cases: []
---
