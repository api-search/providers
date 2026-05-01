---
api_count: 1
api_specs:
- filename: amazon-fsx-openapi.yml
  format: yaml
  label: Amazon FSx API
  slug: amazon-fsx-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-fsx/refs/heads/main/openapi/amazon-fsx-openapi.yml
apis:
- description: The Amazon FSx API enables programmatic access to create, manage, and monitor fully managed file systems. You can create file systems, manage backups, configure data repositories, create snapshots, an
  name: Amazon FSx API
  slug: amazon-fsx-api
capabilities:
- description: Manage fully managed Amazon FSx file systems including Lustre, Windows File Server, NetApp ONTAP, and OpenZFS.
  name: Amazon FSx File System Management
  slug: amazon-fsx-file-system-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/fsx/
- title: ''
  type: Website
  url: https://aws.amazon.com/fsx/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/fsx/
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
  url: https://aws.amazon.com/blogs/storage/category/storage/amazon-fsx/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/fsx/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-fsx
- title: ''
  type: SpectralRules
  url: rules/amazon-fsx-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/fsx.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-fsx-file-system-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-fsx-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-fsx-context.jsonld
created: '2024-01-15'
description: Amazon FSx provides fully managed file systems with the native compatibility and feature sets for workloads that require shared file storage. FSx supports four widely-used file systems including NetApp ONTAP, OpenZFS, Windows File Server, and Lustre, delivering high performance and low latency access to data.
features:
- description: Choose from Lustre, Windows File Server, NetApp ONTAP, and OpenZFS based on workload requirements.
  name: Multiple File System Types
- description: FSx for Lustre delivers hundreds of GB/s throughput and millions of IOPS for HPC and ML workloads.
  name: High Performance
- description: Fully compatible with each file system protocol — SMB for Windows, NFS for Linux, POSIX for Lustre.
  name: Native Compatibility
- description: Daily automatic backups stored in Amazon S3 with user-initiated backup support for disaster recovery.
  name: Automatic Backups
- description: FSx for Windows File Server and ONTAP support Multi-AZ configurations for high availability.
  name: Multi-AZ Deployment
- description: FSx for Lustre integrates natively with Amazon S3 for transparent data import, export, and auto-release.
  name: Data Repository Integration
- description: All file systems are encrypted at rest using AWS KMS with customer-managed key support.
  name: Encryption at Rest
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: FSx for Lustre integrates with S3 as a data repository for transparent file import and export.
  name: Amazon S3
- description: Use FSx for Lustre as shared scratch storage for parallel AWS Batch compute jobs.
  name: AWS Batch
- description: Mount FSx for Lustre directly to SageMaker training instances for fast ML dataset access.
  name: Amazon SageMaker
- description: Mount FSx volumes as persistent volumes in containerized workloads.
  name: Amazon ECS and EKS
- description: Integrate FSx for Windows File Server and ONTAP with Active Directory for user authentication.
  name: AWS Directory Service
- description: Centrally manage FSx backup policies across file systems using AWS Backup.
  name: AWS Backup
- description: Encrypt all FSx file systems with customer-managed keys stored in AWS KMS.
  name: AWS KMS
- description: Monitor FSx throughput, IOPS, and latency metrics with CloudWatch dashboards and alarms.
  name: Amazon CloudWatch
jsonld:
- class_count: 0
  name: Amazon Fsx Context
  property_count: 2
  slug: amazon-fsx-context
layout: provider
modified: '2026-04-19'
name: Amazon FSx
rules:
- name: Amazon FSx API Rules
  rule_count: 26
  severity_counts:
    error: 7
    hint: 0
    info: 3
    warn: 16
  slug: amazon-fsx-spectral-rules
skills: []
slug: amazon-fsx
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon FSx\ndescription: >-\n  Amazon FSx provides fully managed file systems with the native\n  compatibility and feature sets for workloads that require shared file\n  storage. FSx supports four widely-used file systems including NetApp ONTAP,\n  OpenZFS, Windows File Server, and Lustre, delivering high performance and\n  low latency access to data.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/fsx/\ntype: Index\ncreated: '2024-01-15'\nmodified: '2026-04-19'\ntags:\n- AWS\n- File Systems\n- Lustre\n- NetApp\n- OpenZFS\n- Storage\n- Windows\napis:\n- name: Amazon FSx API\n  description: >-\n    The Amazon FSx API enables programmatic access to create, manage, and\n    monitor fully managed file systems. You can create file systems, manage\n    backups, configure data repositories, create snapshots, and manage\n    storage virtual machines across multiple file system types.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n\
  \  humanURL: https://aws.amazon.com/fsx/\n  baseURL: https://fsx.amazonaws.com\n  tags:\n  - File Systems\n  - High Performance\n  - Managed Services\n  - Storage\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/fsx/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-fsx-openapi.yml\n  - type: JSONSchema\n    url: json-schema/amazon-fsx-file-system-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fsx-backup-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fsx-snapshot-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fsx-storage-virtual-machine-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fsx-tag-schema.json\n  - type: JSONStructure\n    url: json-structure/amazon-fsx-file-system-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-fsx-backup-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-fsx-snapshot-structure.json\n  - type: JSONStructure\n\
  \    url: json-structure/amazon-fsx-storage-virtual-machine-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-fsx-tag-structure.json\n  - type: Example\n    url: examples/amazon-fsx-file-system-example.json\n  - type: Example\n    url: examples/amazon-fsx-backup-example.json\n  - type: Example\n    url: examples/amazon-fsx-snapshot-example.json\n  - type: Example\n    url: examples/amazon-fsx-storage-virtual-machine-example.json\n  - type: Example\n    url: examples/amazon-fsx-tag-example.json\n  - type: GettingStarted\n    url: https://aws.amazon.com/fsx/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/fsx/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/fsx/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/fsx/latest/APIReference/Welcome.html\n  aid: amazon-fsx:amazon-fsx-api\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/fsx/\n- type: Website\n  url: https://aws.amazon.com/fsx/\n- type: Documentation\n  url:\
  \ https://docs.aws.amazon.com/fsx/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/storage/category/storage/amazon-fsx/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/fsx/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-fsx\n- type: SpectralRules\n  url: rules/amazon-fsx-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/shared/fsx.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-fsx-file-system-management.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-fsx-vocabulary.yaml\n\
  - type: JSON-LD\n  url: json-ld/amazon-fsx-context.jsonld\n- type: Features\n  data:\n  - name: Multiple File System Types\n    description: Choose from Lustre, Windows File Server, NetApp ONTAP, and OpenZFS based on workload requirements.\n  - name: High Performance\n    description: FSx for Lustre delivers hundreds of GB/s throughput and millions of IOPS for HPC and ML workloads.\n  - name: Native Compatibility\n    description: Fully compatible with each file system protocol — SMB for Windows, NFS for Linux, POSIX for Lustre.\n  - name: Automatic Backups\n    description: Daily automatic backups stored in Amazon S3 with user-initiated backup support for disaster recovery.\n  - name: Multi-AZ Deployment\n    description: FSx for Windows File Server and ONTAP support Multi-AZ configurations for high availability.\n  - name: Data Repository Integration\n    description: FSx for Lustre integrates natively with Amazon S3 for transparent data import, export, and auto-release.\n  - name: Encryption\
  \ at Rest\n    description: All file systems are encrypted at rest using AWS KMS with customer-managed key support.\n- type: UseCases\n  data:\n  - name: HPC and ML Training\n    description: Use FSx for Lustre for fast scratch storage in high-performance computing and distributed ML training jobs.\n  - name: Windows Workloads\n    description: Migrate on-premises Windows file shares to FSx for Windows File Server with Active Directory integration.\n  - name: Enterprise NAS\n    description: Use FSx for NetApp ONTAP for enterprise NAS with SnapMirror replication, FlexClone, and multi-protocol access.\n  - name: DevOps and CI/CD\n    description: Use FSx for OpenZFS for fast NFS shared storage in development, testing, and containerized workflows.\n  - name: Media Processing\n    description: Process high-resolution video and media assets using FSx for Lustre with S3 data repository tiering.\n  - name: Database Backup Storage\n    description: Use FSx for Windows File Server or ONTAP as\
  \ high-performance backup targets for Oracle, SQL Server, and SAP.\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: FSx for Lustre integrates with S3 as a data repository for transparent file import and export.\n  - name: AWS Batch\n    description: Use FSx for Lustre as shared scratch storage for parallel AWS Batch compute jobs.\n  - name: Amazon SageMaker\n    description: Mount FSx for Lustre directly to SageMaker training instances for fast ML dataset access.\n  - name: Amazon ECS and EKS\n    description: Mount FSx volumes as persistent volumes in containerized workloads.\n  - name: AWS Directory Service\n    description: Integrate FSx for Windows File Server and ONTAP with Active Directory for user authentication.\n  - name: AWS Backup\n    description: Centrally manage FSx backup policies across file systems using AWS Backup.\n  - name: AWS KMS\n    description: Encrypt all FSx file systems with customer-managed keys stored in AWS KMS.\n  - name: Amazon CloudWatch\n\
  \    description: Monitor FSx throughput, IOPS, and latency metrics with CloudWatch dashboards and alarms.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\naid: amazon-fsx\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-fsx/refs/heads/main/apis.yml
tags:
- File Systems
- Lustre
- NetApp
- OpenZFS
- Storage
- Windows
url: https://aws.amazon.com/fsx/
use_cases:
- description: Use FSx for Lustre for fast scratch storage in high-performance computing and distributed ML training jobs.
  name: HPC and ML Training
- description: Migrate on-premises Windows file shares to FSx for Windows File Server with Active Directory integration.
  name: Windows Workloads
- description: Use FSx for NetApp ONTAP for enterprise NAS with SnapMirror replication, FlexClone, and multi-protocol access.
  name: Enterprise NAS
- description: Use FSx for OpenZFS for fast NFS shared storage in development, testing, and containerized workflows.
  name: DevOps and CI/CD
- description: Process high-resolution video and media assets using FSx for Lustre with S3 data repository tiering.
  name: Media Processing
- description: Use FSx for Windows File Server or ONTAP as high-performance backup targets for Oracle, SQL Server, and SAP.
  name: Database Backup Storage
---
