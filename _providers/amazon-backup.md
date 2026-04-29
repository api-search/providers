---
api_count: 1
apis:
- description: 'API for centrally managing and automating backups across AWS services including Amazon EBS, Amazon RDS, Amazon DynamoDB, Amazon EFS, Amazon FSx, Amazon EC2, and AWS Storage Gateway. Supports creating '
  name: Amazon Backup API
  slug: amazon-backup-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/backup/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/aws-backup/
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
  url: https://console.aws.amazon.com/backup/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/aws-backup
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://docs.aws.amazon.com/aws-backup/latest/devguide/security.html
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
created: '2024-01-15'
description: AWS Backup is a fully managed backup service that centralizes and automates the backup of data across AWS services, enabling you to configure backup policies, monitor backup activity, and restore resources with a single, unified console and API. It supports automated backup schedules, lifecycle management, cross-region copy, Vault Lock for WORM compliance, legal holds, compliance frameworks, and automated restore testing.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Amazon Backup Context
  property_count: 4
  slug: amazon-backup-context
layout: provider
modified: '2026-04-19'
name: Amazon Backup
skills: []
slug: amazon-backup
solutions: []
source_yaml: "aid: amazon-backup\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-backup/refs/heads/main/apis.yml\nname: Amazon Backup\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nspecificationVersion: '0.19'\ndescription: >-\n  AWS Backup is a fully managed backup service that centralizes and automates\n  the backup of data across AWS services, enabling you to configure backup\n  policies, monitor backup activity, and restore resources with a single,\n  unified console and API. It supports automated backup schedules, lifecycle\n  management, cross-region copy, Vault Lock for WORM compliance, legal holds,\n  compliance frameworks, and automated restore testing.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\ntags:\n  - AWS\n  - Backup\n  - Data Protection\n  - Disaster Recovery\n  - Storage\n  - Compliance\n  - Governance\n  - Business Continuity\napis:\n  - aid: amazon-backup:amazon-backup-api\n    name: Amazon Backup\
  \ API\n    description: >-\n      API for centrally managing and automating backups across AWS services\n      including Amazon EBS, Amazon RDS, Amazon DynamoDB, Amazon EFS, Amazon\n      FSx, Amazon EC2, and AWS Storage Gateway. Supports creating backup\n      plans, managing backup vaults, starting and monitoring backup jobs,\n      restoring resources, cross-region copy, legal holds, compliance\n      frameworks, and automated restore testing.\n    humanURL: https://aws.amazon.com/backup/\n    baseURL: https://backup.us-east-1.amazonaws.com\n    tags:\n      - AWS\n      - Backup\n      - Data Protection\n      - Disaster Recovery\n      - Storage\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/aws-backup/latest/devguide/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-backup/refs/heads/main/openapi/amazon-backup-openapi.yml\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/backup/2018-11-15/openapi.yaml\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-backup/refs/heads/main/json-schema/amazon-backup-plan-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-backup/refs/heads/main/json-structure/backup-resource-structure.json\n      - type: JSONLD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-backup/refs/heads/main/json-ld/amazon-backup-context.jsonld\n      - type: SpectralRuleset\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-backup/refs/heads/main/spectral/ruleset.yml\n      - type: Capabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-backup/refs/heads/main/capabilities/capabilities.yml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-backup/refs/heads/main/vocabulary/vocabulary.yml\n\
  \      - type: Pricing\n        url: https://aws.amazon.com/backup/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/backup/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/backup/faqs/\n      - type: UserGuide\n        url: https://docs.aws.amazon.com/aws-backup/latest/devguide/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/aws-backup/latest/devguide/API_Reference.html\n      - type: CLIReference\n        url: https://docs.aws.amazon.com/cli/latest/reference/backup/\n      - type: Security\n        url: https://docs.aws.amazon.com/aws-backup/latest/devguide/security.html\n    contact:\n      - FN: Amazon Web Services\n        url: https://aws.amazon.com/contact-us/\n    features:\n      - name: Automated Backup Scheduling\n        description: >-\n          Create backup plans with cron-based schedules to automatically back up\n          AWS resources on a defined cadence with configurable start and completion windows.\n\
  \      - name: Lifecycle Management\n        description: >-\n          Automatically transition recovery points from warm to cold storage and\n          delete them after configurable retention periods to optimize costs.\n      - name: Cross-Region Copy\n        description: >-\n          Copy recovery points to backup vaults in other AWS regions for\n          disaster recovery and geographic redundancy.\n      - name: Cross-Account Management\n        description: >-\n          Centrally manage backup policies across multiple AWS accounts within\n          an AWS Organizations structure.\n      - name: Vault Lock (WORM)\n        description: >-\n          Enforce write-once-read-many protection on backup vaults to prevent\n          deletion or modification of recovery points, supporting regulatory compliance.\n      - name: Legal Holds\n        description: >-\n          Preserve recovery points from deletion during legal discovery or\n          compliance investigations with legal\
  \ hold policies.\n      - name: Compliance Frameworks\n        description: >-\n          Create compliance frameworks with controls that automatically evaluate\n          backup configurations against governance requirements.\n      - name: Automated Restore Testing\n        description: >-\n          Schedule periodic automated restore tests to validate backup\n          recoverability and generate compliance reports.\n      - name: Continuous Backup (PITR)\n        description: >-\n          Enable point-in-time recovery for supported services, allowing restore\n          to any second within the retention window.\n    useCases:\n      - name: Enterprise Backup Automation\n        description: >-\n          Automate backup policies across all AWS resources with tag-based\n          selection rules and centralized management.\n      - name: Regulatory Compliance\n        description: >-\n          Meet compliance requirements for data retention with Vault Lock,\n          compliance\
  \ frameworks, and automated reporting.\n      - name: Disaster Recovery\n        description: >-\n          Replicate backups cross-region and validate restore procedures\n          with automated restore testing plans.\n      - name: Legal Hold Management\n        description: >-\n          Preserve backup data during legal proceedings or investigations\n          with automated legal hold policies.\n    integrations:\n      - name: Amazon CloudWatch\n        description: Monitor backup metrics and create alarms for backup failures\n      - name: Amazon EventBridge\n        description: React to backup events with event-driven workflows\n      - name: AWS CloudTrail\n        description: Audit backup activity with consolidated CloudTrail logs\n      - name: Amazon SNS\n        description: Receive backup event notifications via Amazon Simple Notification Service\n      - name: AWS Organizations\n        description: Apply backup policies centrally across organization accounts\n      -\
  \ name: AWS KMS\n        description: Encrypt backup vaults with customer-managed KMS keys\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/\n  - type: Website\n    url: https://aws.amazon.com/backup/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/aws-backup/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/storage/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/backup/\n  - type: SignUp\n    url: https://signin.aws.amazon.com/signup?request_type=register\n  - type: Login\n    url: https://aws.amazon.com/console/\n  - type: Status\n    url: https://health.aws.amazon.com/health/status\n  - type: KnowledgeCenter\n    url: https://repost.aws/knowledge-center\n  - type: YouTube\n\
  \    url: https://www.youtube.com/user/AmazonWebServices\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/aws-backup\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: Security\n    url: https://docs.aws.amazon.com/aws-backup/latest/devguide/security.html\n  - type: Compliance\n    url: https://aws.amazon.com/compliance/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-backup/refs/heads/main/apis.yml
tags:
- AWS
- Backup
- Data Protection
- Disaster Recovery
- Storage
- Compliance
- Governance
- Business Continuity
url: https://raw.githubusercontent.com/api-evangelist/amazon-backup/refs/heads/main/apis.yml
use_cases: []
---
