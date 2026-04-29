---
api_count: 1
apis:
- description: REST API for AWS Application Migration Service covering source servers, replication configuration, launch configuration, jobs, applications, and waves for lift-and-shift cloud migration.
  name: Amazon Application Migration Service API
  slug: amazon-application-migration-service-api
capabilities:
- description: Workflow capability for executing lift-and-shift migrations from on-premises to AWS using Application Migration Service.
  name: Lift And Shift Migration Workflow
  slug: lift-and-shift-migration
common: []
created: '2026-03-16'
description: AWS Application Migration Service (MGN) is the primary migration service recommended for lift-and-shift migrations to AWS. It allows organizations to quickly realize the benefits of migrating applications to the cloud without changes and with minimal downtime.
features:
- Continuous block-level replication with near-zero RPO
- Automated lift-and-shift migration without application changes
- Test migration capability without impacting production servers
- Wave and application grouping for phased migration management
- Agentless migration via VMware vCenter connector
- Post-launch automation via AWS Systems Manager documents
- Right-sizing recommendations for target instance types
- Cross-account and cross-region migration support
- Integration with AWS Migration Hub for centralized tracking
- Automatic EC2 launch template creation for migrated servers
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- AWS Migration Hub
- Amazon EC2
- Amazon EBS
- AWS Systems Manager
- VMware vCenter
- AWS IAM
- Amazon CloudWatch
- AWS CloudTrail
- Amazon S3
- AWS KMS
jsonld:
- class_count: 100
  name: Amazon Application Migration Service Context
  property_count: 0
  slug: amazon-application-migration-service-context
layout: provider
modified: '2026-04-19'
name: Amazon Application Migration Service
rules:
- name: Amazon Application Migration Service API Rules
  rule_count: 21
  severity_counts:
    error: 13
    hint: 0
    info: 2
    warn: 6
  slug: amazon-application-migration-service-spectral-rules
skills: []
slug: amazon-application-migration-service
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-application-migration-service\nname: Amazon Application Migration Service\ndescription: >-\n  AWS Application Migration Service (MGN) is the primary migration service recommended for lift-and-shift migrations to AWS. It allows organizations to quickly realize the benefits of migrating applications to the cloud without changes and with minimal downtime.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Amazon Application Migration Service\n  - Migration\n  - Lift And Shift\n  - AWS\n  - Cloud Migration\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-application-migration-service:amazon-application-migration-service-api\n    name: Amazon Application Migration Service API\n    description: >-\n      REST API for AWS Application Migration\
  \ Service covering source servers, replication configuration, launch configuration, jobs, applications, and waves for lift-and-shift cloud migration.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.aws.amazon.com/mgn/latest/APIReference/Welcome.html\n    baseURL: https://mgn.us-east-1.amazonaws.com\n    tags:\n      - Amazon Application Migration Service\n      - Migration\n      - Lift And Shift\n      - AWS\n      - Cloud Migration\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/openapi/amazon-application-migration-service-openapi.yml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/rules/amazon-application-migration-service-spectral-rules.yml\n      - type: NaftikoCapability\n        url: >-\n\
  \          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/capabilities/shared/application-migration-service-api.yaml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/capabilities/lift-and-shift-migration.yaml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/vocabulary/amazon-application-migration-service-vocabulary.yaml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/json-schema/application-migration-service-source-server-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/json-schema/application-migration-service-replication-configuration-schema.json\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/json-schema/application-migration-service-launch-configuration-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/json-schema/application-migration-service-job-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/json-structure/application-migration-service-source-server-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/json-structure/application-migration-service-job-structure.json\n      - type: JSONLD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/json-ld/amazon-application-migration-service-context.jsonld\n\
  \      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/examples/application-migration-service-source-server-example.json\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/examples/application-migration-service-job-example.json\ncommon:\n  - type: Features\n    data:\n      - Continuous block-level replication with near-zero RPO\n      - Automated lift-and-shift migration without application changes\n      - Test migration capability without impacting production servers\n      - Wave and application grouping for phased migration management\n      - Agentless migration via VMware vCenter connector\n      - Post-launch automation via AWS Systems Manager documents\n      - Right-sizing recommendations for target instance types\n      - Cross-account and cross-region migration support\n      -\
  \ Integration with AWS Migration Hub for centralized tracking\n      - Automatic EC2 launch template creation for migrated servers\n  - type: UseCases\n    data:\n      - Migrate on-premises data center servers to AWS with minimal downtime\n      - Execute phased migrations organized by application waves\n      - Test migration outcomes before executing production cutover\n      - Migrate VMware virtual machines to EC2 instances without agent installation\n      - Standardize migration configuration across hundreds of servers with templates\n      - Automate post-migration software installation and configuration with SSM\n  - type: Integrations\n    data:\n      - AWS Migration Hub\n      - Amazon EC2\n      - Amazon EBS\n      - AWS Systems Manager\n      - VMware vCenter\n      - AWS IAM\n      - Amazon CloudWatch\n      - AWS CloudTrail\n      - Amazon S3\n      - AWS KMS\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/apis.yml
tags:
- Amazon Application Migration Service
- Migration
- Lift And Shift
- AWS
- Cloud Migration
url: https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/apis.yml
use_cases:
- Migrate on-premises data center servers to AWS with minimal downtime
- Execute phased migrations organized by application waves
- Test migration outcomes before executing production cutover
- Migrate VMware virtual machines to EC2 instances without agent installation
- Standardize migration configuration across hundreds of servers with templates
- Automate post-migration software installation and configuration with SSM
---
