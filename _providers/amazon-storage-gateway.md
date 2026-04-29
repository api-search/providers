---
api_count: 1
api_specs:
- filename: amazon-storage-gateway.yaml
  format: yaml
  label: Amazon Storage Gateway REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-storage-gateway/refs/heads/main/openapi/amazon-storage-gateway.yaml
apis:
- description: RESTful API for AWS Storage Gateway enabling management of gateways, volumes, tapes, file shares, and cached storage for hybrid cloud storage architectures.
  name: Amazon Storage Gateway REST API
  slug: ''
capabilities: []
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/storagegateway/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/storagegateway/latest/APIReference/Welcome.html
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
  url: https://aws.amazon.com/blogs/storage/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/storagegateway/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-storage-gateway-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-storage-gateway-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/amazon-storage-gateway.yaml
created: '2024-01-15'
description: AWS Storage Gateway is a hybrid cloud storage service that provides on-premises access to virtually unlimited cloud storage. It seamlessly connects on-premises environments to AWS cloud storage, providing low-latency data access with local caching.
features:
- description: Provides NFS and SMB access to objects stored in Amazon S3.
  name: File Gateway
- description: Provides iSCSI block storage backed by Amazon S3 and Glacier.
  name: Volume Gateway
- description: Virtual tape library backed by S3 and Glacier for backup.
  name: Tape Gateway
- description: Seamlessly integrate on-premises environments with AWS storage.
  name: Hybrid Storage
- description: Cache frequently accessed data locally for low-latency access.
  name: Local Caching
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Store all gateway data in S3 with intelligent tiering.
  name: Amazon S3
- description: Archive tape data to Glacier for long-term retention.
  name: Amazon Glacier
- description: Centralized backup of Storage Gateway volumes and file shares.
  name: AWS Backup
- description: Monitor gateway metrics and set alarms via CloudWatch.
  name: Amazon CloudWatch
- description: Audit all Storage Gateway API calls for compliance.
  name: AWS CloudTrail
jsonld:
- class_count: 205
  name: Amazon Storage Gateway Context
  property_count: 220
  slug: amazon-storage-gateway-context
layout: provider
modified: '2026-04-19'
name: Amazon Storage Gateway
rules:
- name: Amazon Storage Gateway API Rules
  rule_count: 19
  severity_counts:
    error: 11
    hint: 0
    info: 1
    warn: 7
  slug: amazon-storage-gateway-spectral-rules
skills: []
slug: amazon-storage-gateway
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon Storage Gateway\ndescription: AWS Storage Gateway is a hybrid cloud storage service that provides on-premises access to virtually unlimited cloud storage. It seamlessly connects on-premises environments to AWS cloud \n  storage, providing low-latency data access with local caching.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/storagegateway/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon Storage Gateway REST API\n  description: RESTful API for AWS Storage Gateway enabling management of gateways, volumes, tapes, file shares, and cached storage for hybrid cloud storage architectures.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/storagegateway/\n  baseURL: https://storagegateway.amazonaws.com\n  tags:\n  - AWS\n  - Gateway\n  - Hybrid Cloud\n  - Storage\n  properties:\n  - type: Documentation\n    url:\
  \ https://docs.aws.amazon.com/storagegateway/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-storage-gateway.yaml\n  - type: GettingStarted\n    url: https://aws.amazon.com/storagegateway/\n  - type: Pricing\n    url: https://aws.amazon.com/storagegateway/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/storagegateway/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/storagegateway/\n- type: Documentation\n  url: https://docs.aws.amazon.com/storagegateway/latest/APIReference/Welcome.html\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/storage/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/storagegateway/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n\
  - type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-storage-gateway-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-storage-gateway-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/amazon-storage-gateway.yaml\n- type: Features\n  data:\n  - name: File Gateway\n    description: Provides NFS and SMB access to objects stored in Amazon S3.\n  - name: Volume Gateway\n    description: Provides iSCSI block storage backed by Amazon S3 and Glacier.\n  - name: Tape Gateway\n    description: Virtual tape library backed by S3 and Glacier for backup.\n  - name: Hybrid Storage\n    description: Seamlessly integrate on-premises environments with AWS storage.\n  - name: Local Caching\n    description: Cache frequently accessed data locally for low-latency access.\n- type: UseCases\n  data:\n\
  \  - name: Cloud Backup\n    description: Back up on-premises data to AWS using existing backup workflows.\n  - name: Disaster Recovery\n    description: Store data in AWS for disaster recovery with low RTO.\n  - name: Data Archiving\n    description: Archive cold data to Amazon Glacier through virtual tape library.\n  - name: Hybrid File Storage\n    description: Share files between on-premises and cloud with NFS/SMB access.\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Store all gateway data in S3 with intelligent tiering.\n  - name: Amazon Glacier\n    description: Archive tape data to Glacier for long-term retention.\n  - name: AWS Backup\n    description: Centralized backup of Storage Gateway volumes and file shares.\n  - name: Amazon CloudWatch\n    description: Monitor gateway metrics and set alarms via CloudWatch.\n  - name: AWS CloudTrail\n    description: Audit all Storage Gateway API calls for compliance.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n\
  \  url: https://apievangelist.com\ntags:\n- AWS\n- Backup\n- File Storage\n- Gateway\n- Hybrid Cloud\n- Storage\nx-type: company\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-storage-gateway/refs/heads/main/apis.yml
tags:
- AWS
- Backup
- File Storage
- Gateway
- Hybrid Cloud
- Storage
url: https://aws.amazon.com/storagegateway/
use_cases:
- description: Back up on-premises data to AWS using existing backup workflows.
  name: Cloud Backup
- description: Store data in AWS for disaster recovery with low RTO.
  name: Disaster Recovery
- description: Archive cold data to Amazon Glacier through virtual tape library.
  name: Data Archiving
- description: Share files between on-premises and cloud with NFS/SMB access.
  name: Hybrid File Storage
---
