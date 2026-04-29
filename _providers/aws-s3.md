---
api_count: 1
api_specs:
- filename: aws-s3-openapi.yaml
  format: yaml
  label: Amazon S3 REST API
  slug: amazon-s3-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-s3/refs/heads/main/openapi/aws-s3-openapi.yaml
apis:
- description: RESTful API for Amazon S3 object storage operations including bucket management, object CRUD, access control, versioning, lifecycle policies, and multipart uploads.
  name: Amazon S3 REST API
  slug: amazon-s3-rest-api
capabilities:
- description: Workflow capability for managing Amazon S3 buckets and objects for scalable object storage.
  name: Amazon S3 Object Storage Workflow
  slug: object-storage-workflow
common:
- title: ''
  type: Website
  url: https://aws.amazon.com/s3/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/storage/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/s3/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Pricing
  url: https://aws.amazon.com/s3/pricing/
- title: ''
  type: ChangeLog
  url: https://aws.amazon.com/releasenotes/Amazon-S3/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/s3/
- title: ''
  type: SpectralRules
  url: rules/aws-s3-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/aws-s3-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/object-storage-workflow.yaml
created: '2024-01-15'
description: Amazon Simple Storage Service (S3) is an object storage service offering industry-leading scalability, data availability, security, and performance for storing and retrieving any amount of data.
features:
- description: Store and retrieve any amount of data, at any time, from anywhere.
  name: Scalable Object Storage
- description: Keep multiple variants of an object in the same bucket to recover from unintended actions.
  name: Versioning
- description: Automatically transition objects to cheaper storage classes or expire them after a defined period.
  name: Lifecycle Policies
- description: Automatically replicate objects across AWS Regions for compliance and disaster recovery.
  name: Cross-Region Replication
- description: Encrypt objects at rest using SSE-S3, SSE-KMS, or SSE-C managed keys.
  name: Server-Side Encryption
- description: Fine-grained access via bucket policies, ACLs, and IAM policies.
  name: Access Control
- description: Trigger Lambda functions, SQS messages, or SNS topics on bucket events.
  name: Event Notifications
- description: Retrieve a subset of data from an object using SQL expressions.
  name: S3 Select
- description: Speed up uploads using CloudFront's globally distributed edge locations.
  name: Transfer Acceleration
- description: Automatically move objects to the most cost-effective access tier based on usage patterns.
  name: Intelligent-Tiering
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Trigger serverless functions on S3 object events.
  name: AWS Lambda
- description: Distribute S3 content globally with low-latency delivery.
  name: Amazon CloudFront
- description: Catalog and ETL data in S3 for analytics workflows.
  name: AWS Glue
- description: Query data stored in S3 using standard SQL without loading.
  name: Amazon Athena
- description: Query S3 data lake files from Redshift without data movement.
  name: Amazon Redshift Spectrum
- description: Route S3 events to downstream AWS services using EventBridge rules.
  name: Amazon EventBridge
jsonld:
- class_count: 30
  name: Aws S3 Context
  property_count: 0
  slug: aws-s3-context
layout: provider
modified: '2026-04-19'
name: Amazon S3 API
rules:
- name: Amazon S3 API API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: aws-s3-spectral-rules
skills: []
slug: aws-s3
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: aws-s3\nname: Amazon S3 API\ndescription: >-\n  Amazon Simple Storage Service (S3) is an object storage service offering\n  industry-leading scalability, data availability, security, and performance\n  for storing and retrieving any amount of data.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Cloud Storage\n  - Object Storage\n  - Storage\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aws-s3/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: aws-s3:amazon-s3-rest-api\n    name: Amazon S3 REST API\n    description: RESTful API for Amazon S3 object storage operations including bucket management, object CRUD, access control, versioning, lifecycle policies, and multipart uploads.\n    humanURL: https://aws.amazon.com/s3/\n    baseURL: https://s3.amazonaws.com\n    tags:\n      - Buckets\n      - Objects\n      - REST\n   \
  \   - Storage\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/Welcome.html\n      - type: OpenAPI\n        url: openapi/aws-s3-openapi.yaml\n      - type: Authentication\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/sig-v4-authenticating-requests.html\n      - type: GettingStarted\n        url: https://aws.amazon.com/s3/getting-started/\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n        title: AWS SDKs\ncommon:\n  - type: Website\n    url: https://aws.amazon.com/s3/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/storage/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Console\n    url: https://console.aws.amazon.com/s3/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Pricing\n\
  \    url: https://aws.amazon.com/s3/pricing/\n  - type: ChangeLog\n    url: https://aws.amazon.com/releasenotes/Amazon-S3/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/s3/\n  - type: SpectralRules\n    url: rules/aws-s3-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/aws-s3-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/object-storage-workflow.yaml\n  - type: Features\n    data:\n      - name: Scalable Object Storage\n        description: Store and retrieve any amount of data, at any time, from anywhere.\n      - name: Versioning\n        description: Keep multiple variants of an object in the same bucket to recover from unintended actions.\n      - name: Lifecycle Policies\n        description: Automatically transition objects to cheaper storage classes or expire them after a defined period.\n      - name: Cross-Region Replication\n        description: Automatically replicate objects across AWS Regions for compliance and disaster recovery.\n\
  \      - name: Server-Side Encryption\n        description: Encrypt objects at rest using SSE-S3, SSE-KMS, or SSE-C managed keys.\n      - name: Access Control\n        description: Fine-grained access via bucket policies, ACLs, and IAM policies.\n      - name: Event Notifications\n        description: Trigger Lambda functions, SQS messages, or SNS topics on bucket events.\n      - name: S3 Select\n        description: Retrieve a subset of data from an object using SQL expressions.\n      - name: Transfer Acceleration\n        description: Speed up uploads using CloudFront's globally distributed edge locations.\n      - name: Intelligent-Tiering\n        description: Automatically move objects to the most cost-effective access tier based on usage patterns.\n  - type: UseCases\n    data:\n      - name: Data Lake Storage\n        description: Store raw data for analytics pipelines using AWS Glue, Athena, and Redshift Spectrum.\n      - name: Static Website Hosting\n        description: Host\
  \ static websites and single-page applications directly from S3.\n      - name: Backup and Archive\n        description: Store backups and archives with lifecycle policies to move data to Glacier for long-term retention.\n      - name: Media Storage and Distribution\n        description: Store and serve images, videos, and documents globally via CloudFront CDN.\n      - name: Application Data Storage\n        description: Store user-generated content, application logs, and configuration files.\n  - type: Integrations\n    data:\n      - name: AWS Lambda\n        description: Trigger serverless functions on S3 object events.\n      - name: Amazon CloudFront\n        description: Distribute S3 content globally with low-latency delivery.\n      - name: AWS Glue\n        description: Catalog and ETL data in S3 for analytics workflows.\n      - name: Amazon Athena\n        description: Query data stored in S3 using standard SQL without loading.\n      - name: Amazon Redshift Spectrum\n    \
  \    description: Query S3 data lake files from Redshift without data movement.\n      - name: Amazon EventBridge\n        description: Route S3 events to downstream AWS services using EventBridge rules.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aws-s3/refs/heads/main/apis.yml
tags:
- AWS
- Cloud Storage
- Object Storage
- Storage
url: https://raw.githubusercontent.com/api-evangelist/aws-s3/refs/heads/main/apis.yml
use_cases:
- description: Store raw data for analytics pipelines using AWS Glue, Athena, and Redshift Spectrum.
  name: Data Lake Storage
- description: Host static websites and single-page applications directly from S3.
  name: Static Website Hosting
- description: Store backups and archives with lifecycle policies to move data to Glacier for long-term retention.
  name: Backup and Archive
- description: Store and serve images, videos, and documents globally via CloudFront CDN.
  name: Media Storage and Distribution
- description: Store user-generated content, application logs, and configuration files.
  name: Application Data Storage
---
