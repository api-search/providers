---
api_count: 1
api_specs:
- filename: amazon-efs-openapi.yml
  format: yaml
  label: Amazon EFS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-efs/refs/heads/main/openapi/amazon-efs-openapi.yml
apis:
- description: API for managing Amazon EFS file systems, mount targets, and related resources.
  name: Amazon EFS API
  slug: ''
capabilities:
- description: Unified capability for managing EFS file systems, mount targets, and access points for storage administrators.
  name: Amazon EFS Elastic File System Management
  slug: efs-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://status.aws.amazon.com/
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-web-services
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://aws.amazon.com/security/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-efs-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-efs-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/efs-management.yaml
created: '2024-01-15'
description: Amazon Elastic File System (EFS) provides a simple, serverless, set-and-forget elastic file system for use with AWS cloud services and on-premises resources. EFS is built to scale on demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files.
features:
- description: Automatically grows and shrinks as you add and remove files with no provisioning required.
  name: Elastic Scalability
- description: Standard, Infrequent Access, and Archive storage classes with automatic lifecycle management.
  name: Multiple Storage Classes
- description: Data automatically replicated across multiple Availability Zones for 99.999999999% durability.
  name: Multi-AZ Replication
- description: Thousands of EC2 instances and Lambda functions can access the same file system simultaneously.
  name: Concurrent Access
- description: Application-specific entry points with customized directory access and POSIX permissions.
  name: EFS Access Points
- description: Centralized backup management for EFS file systems with policy-based retention.
  name: AWS Backup Integration
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Mount EFS file systems on EC2 instances using the NFS protocol.
  name: Amazon EC2
- description: Provide persistent shared storage for ECS tasks with EFS volume drivers.
  name: Amazon ECS
- description: Use the Amazon EFS CSI driver to mount EFS file systems as Kubernetes persistent volumes.
  name: Amazon EKS
- description: Access EFS file systems from Lambda functions for shared data storage and large model loading.
  name: AWS Lambda
- description: Automated backup of EFS file systems with centralized policy management.
  name: AWS Backup
jsonld:
- class_count: 4
  name: Amazon Efs Context
  property_count: 30
  slug: amazon-efs-context
layout: provider
modified: '2026-04-19'
name: Amazon EFS
rules:
- name: Amazon EFS API Rules
  rule_count: 28
  severity_counts:
    error: 11
    hint: 0
    info: 4
    warn: 13
  slug: amazon-efs-spectral-rules
skills: []
slug: amazon-efs
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon EFS\ndescription: Amazon Elastic File System (EFS) provides a simple, serverless, set-and-forget elastic file system for use with AWS cloud services and on-premises resources. EFS is built to scale on \n  demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/efs/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\ntags:\n- Amazon Web Services\n- AWS\n- EFS\n- Elastic File System\n- File Storage\n- NFS\n- Serverless\n- Storage\napis:\n- name: Amazon EFS API\n  description: API for managing Amazon EFS file systems, mount targets, and related resources.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  url: https://aws.amazon.com/efs/\n  baseURL: https://elasticfilesystem.amazonaws.com\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/efs/latest/ug/\n\
  \  - type: OpenAPI\n    url: openapi/amazon-efs-openapi.yml\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/elasticfilesystem/2015-02-01/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-efs-filesystem-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-efs-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/efs/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/efs/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/efs/faqs/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/efs/latest/ug/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/efs/latest/ug/API_Reference.html\n  - type: Documentation\n    url: https://docs.aws.amazon.com/cli/latest/reference/efs/\n  - type: Security\n    url: https://docs.aws.amazon.com/efs/latest/ug/security.html\n  - type: JSONStructure\n    url: json-structure/amazon-efs-filesystem-structure.json\n  - type: Example\n    url: examples/amazon-efs-filesystem-example.json\n\
  common:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: DeveloperPortal\n  url: https://aws.amazon.com/\n- type: Documentation\n  url: https://docs.aws.amazon.com/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/support/\n- type: Blog\n  url: https://aws.amazon.com/blogs/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://status.aws.amazon.com/\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-web-services\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n\
  - type: Security\n  url: https://aws.amazon.com/security/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Features\n  data:\n  - name: Elastic Scalability\n    description: Automatically grows and shrinks as you add and remove files with no provisioning required.\n  - name: Multiple Storage Classes\n    description: Standard, Infrequent Access, and Archive storage classes with automatic lifecycle management.\n  - name: Multi-AZ Replication\n    description: Data automatically replicated across multiple Availability Zones for 99.999999999% durability.\n  - name: Concurrent Access\n    description: Thousands of EC2 instances and Lambda functions can access the same file system simultaneously.\n  - name: EFS Access Points\n    description: Application-specific entry points with customized directory access and POSIX permissions.\n  - name: AWS Backup Integration\n    description: Centralized backup management for EFS file systems with policy-based retention.\n- type:\
  \ UseCases\n  data:\n  - name: Containerized Application Storage\n    description: Persistent shared storage for containerized applications running on ECS or EKS.\n  - name: Machine Learning\n    description: Shared training data storage accessible simultaneously by multiple compute instances.\n  - name: Content Management\n    description: Shared file storage for web servers and CMS platforms requiring concurrent file access.\n  - name: DevOps and Code Sharing\n    description: Centralized code and configuration storage accessible by development teams and CI/CD pipelines.\n  - name: Big Data Analytics\n    description: High-throughput shared storage for analytics workloads requiring parallel data access.\n- type: Integrations\n  data:\n  - name: Amazon EC2\n    description: Mount EFS file systems on EC2 instances using the NFS protocol.\n  - name: Amazon ECS\n    description: Provide persistent shared storage for ECS tasks with EFS volume drivers.\n  - name: Amazon EKS\n    description:\
  \ Use the Amazon EFS CSI driver to mount EFS file systems as Kubernetes persistent volumes.\n  - name: AWS Lambda\n    description: Access EFS file systems from Lambda functions for shared data storage and large model loading.\n  - name: AWS Backup\n    description: Automated backup of EFS file systems with centralized policy management.\n- type: SpectralRules\n  url: rules/amazon-efs-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-efs-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/efs-management.yaml\nmaintainer:\n  name: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-efs/refs/heads/main/apis.yml
tags:
- Amazon Web Services
- EFS
- Elastic File System
- File Storage
- NFS
- Serverless
- Storage
url: https://aws.amazon.com/efs/
use_cases:
- description: Persistent shared storage for containerized applications running on ECS or EKS.
  name: Containerized Application Storage
- description: Shared training data storage accessible simultaneously by multiple compute instances.
  name: Machine Learning
- description: Shared file storage for web servers and CMS platforms requiring concurrent file access.
  name: Content Management
- description: Centralized code and configuration storage accessible by development teams and CI/CD pipelines.
  name: DevOps and Code Sharing
- description: High-throughput shared storage for analytics workloads requiring parallel data access.
  name: Big Data Analytics
---
