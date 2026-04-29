---
api_count: 3
api_specs:
- filename: amazon-s3-rest-api-openapi.yml
  format: yaml
  label: Amazon S3 REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-s3/refs/heads/main/openapi/amazon-s3-rest-api-openapi.yml
- filename: amazon-s3-control-api-openapi.yml
  format: yaml
  label: Amazon S3 Control API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-s3/refs/heads/main/openapi/amazon-s3-control-api-openapi.yml
- filename: amazon-s3-tables-api-openapi.yml
  format: yaml
  label: Amazon S3 Tables API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-s3/refs/heads/main/openapi/amazon-s3-tables-api-openapi.yml
apis:
- description: RESTful API for Amazon S3 storage operations including bucket management, object operations, and access control.
  name: Amazon S3 REST API
  slug: ''
- description: Amazon S3 Control provides API operations for managing S3 account-level settings, access points, Batch Operations jobs, S3 Access Grants, Multi-Region Access Points, and Storage Lens configurations.
  name: Amazon S3 Control API
  slug: ''
- description: Amazon S3 Tables API provides operations for managing table buckets and tables stored in Apache Iceberg format, enabling structured tabular data storage in Apache Parquet format within Amazon S3.
  name: Amazon S3 Tables API
  slug: ''
capabilities:
- description: Unified capability for Amazon S3 storage management combining object storage operations, account-level controls, and tabular data management. Used by cloud engineers, data engineers, and platform team
  name: Amazon S3 Storage Management
  slug: storage-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/s3/
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
  url: https://console.aws.amazon.com/s3/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-s3
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://docs.aws.amazon.com/AmazonS3/latest/userguide/security.html
- title: ''
  type: Compliance
  url: https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-compliance.html
- title: ''
  type: ChangeLog
  url: https://docs.aws.amazon.com/AmazonS3/latest/API/WhatsNew.html
created: '2024-01-15'
description: Amazon Simple Storage Service (S3) is an object storage service offering industry-leading scalability, data availability, security, and performance.
features:
- Industry-leading scalability and 99.999999999% durability
- Multiple storage classes for cost optimization
- Object versioning and lifecycle management
- Server-side encryption and access control
- S3 Object Lock for WORM compliance
- Cross-region and same-region replication
- S3 Tables for Apache Iceberg tabular data
- S3 Access Grants for identity-based access
- Storage Lens analytics and insights
- Batch Operations for large-scale object processing
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- AWS Lambda
- Amazon CloudFront
- Amazon Athena
- AWS Glue
- Amazon EMR
- Amazon Redshift
- AWS CloudTrail
- Amazon EventBridge
jsonld:
- class_count: 10
  name: Amazon S3 Context
  property_count: 11
  slug: amazon-s3-context
- class_count: 0
  name: Amazon S3 Control Context
  property_count: 0
  slug: amazon-s3-control-context
- class_count: 0
  name: Amazon S3 Rest Context
  property_count: 0
  slug: amazon-s3-rest-context
- class_count: 0
  name: Amazon S3 Tables Context
  property_count: 0
  slug: amazon-s3-tables-context
layout: provider
modified: '2026-04-18'
name: Amazon S3
rules:
- name: Amazon S3 API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: amazon-s3-spectral-rules
skills: []
slug: amazon-s3
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon S3\ndescription: Amazon Simple Storage Service (S3) is an object storage service offering industry-leading scalability, data availability, security, and performance.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/s3/\ncreated: '2024-01-15'\nmodified: '2026-04-18'\napis:\n  - name: Amazon S3 REST API\n    description: >-\n      RESTful API for Amazon S3 storage operations including bucket management, object\n      operations, and access control.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/s3/\n    baseURL: https://s3.amazonaws.com\n    tags:\n      - AWS\n      - Cloud Storage\n      - Object Storage\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/\n      - type: OpenAPI\n        url: openapi/amazon-s3-rest-api-openapi.yml\n      - type: OpenAPI\n\
  \        url: https://api.apis.guru/v2/specs/amazonaws.com/s3/2006-03-01/openapi.yaml\n      - type: JSONSchema\n        url: json-schema/amazon-s3-bucket-schema.json\n      - type: JSONSchema\n        url: json-schema/amazon-s3-object-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-s3-context.jsonld\n      - type: Pricing\n        url: https://aws.amazon.com/s3/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/s3/getting-started/\n      - type: Authentication\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/sig-v4-authenticating-requests.html\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n      - type: StatusPage\n        url: https://status.aws.amazon.com/\n      - type: BestPractices\n        url: https://docs.aws.amazon.com/AmazonS3/latest/userguide/best-practices.html\n      - type: FAQ\n        url: https://aws.amazon.com/s3/faqs/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/Welcome.html\n\
  \      - type: ChangeLog\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/WhatsNew.html\n      - type: CodeExamples\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/service_code_examples.html\n      - type: Security\n        url: https://docs.aws.amazon.com/AmazonS3/latest/userguide/security.html\n  - name: Amazon S3 Control API\n    description: Amazon S3 Control provides API operations for managing S3 account-level settings, access points, Batch Operations jobs, S3 Access Grants, Multi-Region Access Points, and Storage Lens configurations.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/AmazonS3/latest/API/API_Types_AWS_S3_Control.html\n    baseURL: https://s3-control.amazonaws.com\n    tags:\n      - Access Control\n      - AWS\n      - Batch Operations\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/API_Types_AWS_S3_Control.html\n\
  \      - type: OpenAPI\n        url: openapi/amazon-s3-control-api-openapi.yml\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/s3control/2018-08-20/openapi.yaml\n      - type: JSONLD\n        url: json-ld/amazon-s3-context.jsonld\n      - type: Pricing\n        url: https://aws.amazon.com/s3/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/s3/getting-started/\n      - type: Authentication\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/sig-v4-authenticating-requests.html\n      - type: SDK\n        url: https://aws.amazon.com/tools/\n      - type: FAQ\n        url: https://aws.amazon.com/s3/faqs/\n      - type: ChangeLog\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/WhatsNew.html\n  - name: Amazon S3 Tables API\n    description: Amazon S3 Tables API provides operations for managing table buckets and tables stored in Apache Iceberg format, enabling structured tabular data storage in Apache Parquet\
  \ format within Amazon S3.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/AmazonS3/latest/API/API_Operations_Amazon_S3_Tables.html\n    baseURL: https://s3tables.amazonaws.com\n    tags:\n      - Apache Iceberg\n      - AWS\n      - Data Lake\n      - Storage\n      - Tables\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/API_Operations_Amazon_S3_Tables.html\n      - type: OpenAPI\n        url: openapi/amazon-s3-tables-api-openapi.yml\n      - type: JSONLD\n        url: json-ld/amazon-s3-context.jsonld\n      - type: APIReference\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/API_Operations_Amazon_S3_Tables.html\n      - type: Pricing\n        url: https://aws.amazon.com/s3/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/s3/getting-started/\n      - type: Authentication\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/sig-v4-authenticating-requests.html\n\
  \      - type: SDK\n        url: https://aws.amazon.com/tools/\n      - type: FAQ\n        url: https://aws.amazon.com/s3/faqs/\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/s3/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/storage/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/s3/\n  - type: SignUp\n    url: https://signin.aws.amazon.com/signup?request_type=register\n  - type: Login\n    url: https://aws.amazon.com/console/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: KnowledgeCenter\n    url: https://repost.aws/knowledge-center\n  - type: YouTube\n    url: https://www.youtube.com/user/AmazonWebServices\n\
  \  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/amazon-s3\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: Security\n    url: https://docs.aws.amazon.com/AmazonS3/latest/userguide/security.html\n  - type: Compliance\n    url: https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-compliance.html\n  - type: ChangeLog\n    url: https://docs.aws.amazon.com/AmazonS3/latest/API/WhatsNew.html\n  - type: Features\n    data:\n      - Industry-leading scalability and 99.999999999% durability\n      - Multiple storage classes for cost optimization\n      - Object versioning and lifecycle management\n      - Server-side encryption and access control\n      - S3 Object Lock for WORM compliance\n      - Cross-region and same-region replication\n      - S3 Tables for Apache Iceberg tabular data\n      - S3 Access Grants for identity-based access\n      - Storage Lens analytics and insights\n      - Batch Operations for large-scale object processing\n\
  \  - type: UseCases\n    data:\n      - Storing and serving static website content\n      - Data lake foundation for analytics workloads\n      - Backup and disaster recovery storage\n      - Archive storage with Glacier integration\n      - Hosting machine learning training datasets\n      - Storing application logs and audit trails\n  - type: Integrations\n    data:\n      - AWS Lambda\n      - Amazon CloudFront\n      - Amazon Athena\n      - AWS Glue\n      - Amazon EMR\n      - Amazon Redshift\n      - AWS CloudTrail\n      - Amazon EventBridge\nproperties:\n  - type: Capabilities\n    url: capabilities/storage-management.yaml\n    title: Storage Management Capability\n  - type: Capabilities\n    url: capabilities/shared/s3-rest.yaml\n    title: S3 REST API Shared Definition\n  - type: Capabilities\n    url: capabilities/shared/s3-control.yaml\n    title: S3 Control API Shared Definition\n  - type: Capabilities\n    url: capabilities/shared/s3-tables.yaml\n    title: S3 Tables API\
  \ Shared Definition\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Archive\n  - AWS\n  - Backup\n  - Cloud Storage\n  - Data Storage\n  - Object Storage\n  - Scalable Storage\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-s3/refs/heads/main/apis.yml
tags:
- Archive
- AWS
- Backup
- Cloud Storage
- Data Storage
- Object Storage
- Scalable Storage
url: https://aws.amazon.com/s3/
use_cases:
- Storing and serving static website content
- Data lake foundation for analytics workloads
- Backup and disaster recovery storage
- Archive storage with Glacier integration
- Hosting machine learning training datasets
- Storing application logs and audit trails
---
