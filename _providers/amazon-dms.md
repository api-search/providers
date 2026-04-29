---
api_count: 1
apis:
- description: 'The AWS Database Migration Service API provides programmatic access to create and manage replication instances, endpoints, replication tasks, and monitor migration progress for database migrations to '
  name: Amazon DMS API
  slug: amazon-dms-api
capabilities:
- description: Workflow capability for database engineers and cloud architects to manage end-to-end database migrations using AWS Database Migration Service. Covers replication instance provisioning, source and targ
  name: Amazon DMS Database Migration Management
  slug: database-migration-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/dms/
- title: ''
  type: Website
  url: https://aws.amazon.com/dms/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/dms/
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
  url: https://aws.amazon.com/blogs/database/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/dms/
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
  url: https://raw.githubusercontent.com/api-evangelist/amazon-dms/refs/heads/main/rules/amazon-dms-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amazon-dms/refs/heads/main/vocabulary/amazon-dms-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amazon-dms/refs/heads/main/capabilities/database-migration-management.yaml
created: '2024-01-15'
description: AWS Database Migration Service (AWS DMS) helps you migrate databases to AWS quickly and securely. The source database remains fully operational during the migration, minimizing downtime to applications that rely on the database. AWS DMS can migrate your data to and from the most widely used commercial and open-source databases, supporting homogeneous and heterogeneous migrations with continuous data replication.
features:
- description: Migrate between databases of the same engine type with minimal conversion
  name: Homogeneous Migration
- description: Migrate between different database engines using Schema Conversion Tool
  name: Heterogeneous Migration
- description: Continuously replicate data changes using change data capture (CDC)
  name: Continuous Data Replication
- description: Keep source database operational during migration for high availability
  name: Minimal Downtime Migration
- description: Provision replication instances across multiple Availability Zones for resilience
  name: Multi-AZ Replication
- description: Run automated assessments to identify migration issues before starting
  name: Premigration Assessment
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Target Aurora MySQL and Aurora PostgreSQL for cost-efficient managed databases
  name: Amazon Aurora
- description: Migrate to RDS instances for fully managed relational database hosting
  name: Amazon RDS
- description: Migrate data warehouses or replicate transactional data for analytics
  name: Amazon Redshift
- description: Convert database schemas for heterogeneous migrations between engine types
  name: AWS Schema Conversion Tool
- description: Stream migration data to S3 for archival or downstream processing
  name: Amazon S3
jsonld:
- class_count: 25
  name: Amazon Dms Context
  property_count: 198
  slug: amazon-dms-context
layout: provider
modified: '2026-04-19'
name: Amazon DMS
rules:
- name: Amazon DMS API Rules
  rule_count: 18
  severity_counts:
    error: 11
    hint: 0
    info: 3
    warn: 4
  slug: amazon-dms-spectral-rules
skills: []
slug: amazon-dms
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-dms\nname: Amazon DMS\ndescription: >-\n  AWS Database Migration Service (AWS DMS) helps you migrate databases to AWS\n  quickly and securely. The source database remains fully operational during the\n  migration, minimizing downtime to applications that rely on the database. AWS\n  DMS can migrate your data to and from the most widely used commercial and\n  open-source databases, supporting homogeneous and heterogeneous migrations\n  with continuous data replication.\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Data Replication\n  - Database\n  - Database Migration\n  - Migration\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-dms/refs/heads/main/apis.yml\ncreated: \"2024-01-15\"\nmodified: \"2026-04-19\"\nspecificationVersion: \"0.19\"\napis:\n  - aid: amazon-dms:amazon-dms-api\n    name: Amazon DMS API\n    description: >-\n      The AWS Database Migration\
  \ Service API provides programmatic access to\n      create and manage replication instances, endpoints, replication tasks,\n      and monitor migration progress for database migrations to AWS.\n    humanURL: https://aws.amazon.com/dms/\n    baseURL: https://dms.amazonaws.com\n    tags:\n      - Database Migration\n      - Data Replication\n      - AWS\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/dms/latest/APIReference/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-dms/refs/heads/main/openapi/amazon-dms-openapi.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/dms/getting-started/\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/dms/\n  - type: Website\n    url: https://aws.amazon.com/dms/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/dms/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n\
  \    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/database/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/dms/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/amazon-dms/refs/heads/main/rules/amazon-dms-spectral-rules.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/amazon-dms/refs/heads/main/vocabulary/amazon-dms-vocabulary.yaml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/amazon-dms/refs/heads/main/capabilities/database-migration-management.yaml\n\
  \  - type: Features\n    data:\n      - name: Homogeneous Migration\n        description: Migrate between databases of the same engine type with minimal conversion\n      - name: Heterogeneous Migration\n        description: Migrate between different database engines using Schema Conversion Tool\n      - name: Continuous Data Replication\n        description: Continuously replicate data changes using change data capture (CDC)\n      - name: Minimal Downtime Migration\n        description: Keep source database operational during migration for high availability\n      - name: Multi-AZ Replication\n        description: Provision replication instances across multiple Availability Zones for resilience\n      - name: Premigration Assessment\n        description: Run automated assessments to identify migration issues before starting\n  - type: UseCases\n    data:\n      - name: Database Consolidation\n        description: Consolidate multiple databases into a single AWS-managed database\n   \
  \   - name: Cross-Engine Migration\n        description: Migrate from Oracle or SQL Server to open-source Aurora or PostgreSQL\n      - name: Development and Testing\n        description: Continuously replicate production data to development environments\n      - name: Active-Active Replication\n        description: Maintain synchronized database replicas across regions for failover\n      - name: Analytics Migration\n        description: Migrate transactional databases to analytical data warehouses like Redshift\n  - type: Integrations\n    data:\n      - name: Amazon Aurora\n        description: Target Aurora MySQL and Aurora PostgreSQL for cost-efficient managed databases\n      - name: Amazon RDS\n        description: Migrate to RDS instances for fully managed relational database hosting\n      - name: Amazon Redshift\n        description: Migrate data warehouses or replicate transactional data for analytics\n      - name: AWS Schema Conversion Tool\n        description: Convert database\
  \ schemas for heterogeneous migrations between engine types\n      - name: Amazon S3\n        description: Stream migration data to S3 for archival or downstream processing\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-dms/refs/heads/main/apis.yml
tags:
- AWS
- Data Replication
- Database
- Database Migration
- Migration
url: https://raw.githubusercontent.com/api-evangelist/amazon-dms/refs/heads/main/apis.yml
use_cases:
- description: Consolidate multiple databases into a single AWS-managed database
  name: Database Consolidation
- description: Migrate from Oracle or SQL Server to open-source Aurora or PostgreSQL
  name: Cross-Engine Migration
- description: Continuously replicate production data to development environments
  name: Development and Testing
- description: Maintain synchronized database replicas across regions for failover
  name: Active-Active Replication
- description: Migrate transactional databases to analytical data warehouses like Redshift
  name: Analytics Migration
---
