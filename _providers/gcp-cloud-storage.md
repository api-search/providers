---
api_count: 2
api_specs:
- filename: gcp-cloud-storage-json-api-openapi.yml
  format: yaml
  label: Google Cloud Storage JSON API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gcp-cloud-storage/refs/heads/main/openapi/gcp-cloud-storage-json-api-openapi.yml
apis:
- description: RESTful API for interacting with Google Cloud Storage buckets and objects.
  name: Google Cloud Storage JSON API
  slug: ''
- description: Amazon S3-compatible XML API for Google Cloud Storage.
  name: Google Cloud Storage XML API
  slug: ''
capabilities:
- description: Unified workflow for managing cloud storage buckets, objects, access controls, and IAM policies. Used by cloud engineers and data platform teams.
  name: Google Cloud Storage Management
  slug: cloud-storage
common:
- title: ''
  type: GettingStarted
  url: https://cloud.google.com/storage/docs/quickstarts
- title: ''
  type: SDK
  url: https://cloud.google.com/storage/docs/reference/libraries
- title: ''
  type: Console
  url: https://console.cloud.google.com/storage
- title: ''
  type: Blog
  url: https://cloud.google.com/blog/products/storage-data-transfer
- title: ''
  type: ChangeLog
  url: https://cloud.google.com/storage/docs/release-notes
- title: ''
  type: BestPractices
  url: https://cloud.google.com/storage/docs/best-practices
- title: ''
  type: Security
  url: https://cloud.google.com/storage/docs/security
- title: ''
  type: Compliance
  url: https://cloud.google.com/security/compliance
- title: ''
  type: APIReference
  url: https://cloud.google.com/storage/docs/apis
- title: ''
  type: CLI
  url: https://cloud.google.com/storage/docs/discover-object-storage-gsutil
- title: ''
  type: SpectralRules
  url: rules/gcp-cloud-storage-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/gcp-cloud-storage-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/cloud-storage.yaml
created: '2024-01-01'
description: Object storage service offering high durability, availability, and scalability for storing and accessing data on Google Cloud Platform.
features:
- description: Store data across multiple regions for high availability and low-latency access worldwide.
  name: Multi-Regional Storage
- description: Automatically transition objects between storage classes or delete them based on configurable rules.
  name: Object Lifecycle Management
- description: Maintain multiple versions of objects for data protection and recovery.
  name: Versioning
- description: Control access using IAM policies, ACLs, and signed URLs for secure data sharing.
  name: Fine-Grained Access Control
- description: Compose multiple objects into a single object without downloading and re-uploading data.
  name: Object Composition
- description: Watch for changes to objects in a bucket and receive push notifications.
  name: Change Notifications
- description: Lock retention policies to prevent object deletion for regulatory compliance.
  name: Retention Policies
image: https://cloud.google.com/images/social-icon-google-cloud-1200-630.png
integrations:
- description: Load data directly from Cloud Storage into BigQuery for analytics and data warehousing.
  name: BigQuery
- description: Trigger serverless functions on object creation, deletion, or metadata changes.
  name: Cloud Functions
- description: Process data stored in Cloud Storage using Apache Beam pipelines.
  name: Dataflow
- description: Transfer data between on-premises storage, other clouds, and Cloud Storage.
  name: Transfer Service
- description: Cache and serve Cloud Storage content through Google's global edge network.
  name: Cloud CDN
jsonld:
- class_count: 0
  name: Gcp Cloud Storage Context
  property_count: 6
  slug: gcp-cloud-storage-context
- class_count: 0
  name: Gcp Cloud Storage Json Context
  property_count: 0
  slug: gcp-cloud-storage-json-context
layout: provider
modified: '2026-04-18'
name: Google Cloud Storage
rules:
- name: Google Cloud Storage API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: gcp-cloud-storage-spectral-rules
skills: []
slug: gcp-cloud-storage
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Google Cloud Storage\ndescription: >-\n  Object storage service offering high durability, availability, and scalability for\n  storing and accessing data on Google Cloud Platform.\nimage: https://cloud.google.com/images/social-icon-google-cloud-1200-630.png\nurl: https://cloud.google.com/storage\ncreated: '2024-01-01'\nmodified: '2026-04-18'\ntags:\n  - Archival\n  - Backup\n  - Blob Storage\n  - Cloud Storage\n  - Data\n  - File Storage\n  - Google Cloud\n  - Object Storage\n  - Storage\napis:\n  - name: Google Cloud Storage JSON API\n    description: >-\n      RESTful API for interacting with Google Cloud Storage buckets and objects.\n    image: https://cloud.google.com/images/storage/storage-icon.svg\n    humanURL: https://cloud.google.com/storage/docs/json_api\n    baseURL: https://storage.googleapis.com/storage/v1\n    tags:\n      - Buckets\n      - Objects\n      - Access Control\n      - IAM\n      - Storage\n    properties:\n      - type: Documentation\n    \
  \    url: https://cloud.google.com/storage/docs/json_api\n      - type: OpenAPI\n        url: https://storage.googleapis.com/$discovery/rest?version=v1\n      - type: OpenAPI\n        url: openapi/gcp-cloud-storage-json-api-openapi.yml\n      - type: Authentication\n        url: https://cloud.google.com/storage/docs/authentication\n      - type: Pricing\n        url: https://cloud.google.com/storage/pricing\n      - type: RateLimits\n        url: https://cloud.google.com/storage/quotas\n      - type: StatusPage\n        url: https://status.cloud.google.com/\n      - type: TermsOfService\n        url: https://cloud.google.com/terms\n      - type: APIReference\n        url: https://cloud.google.com/storage/docs/json_api/v1\n      - type: JSONSchema\n        url: json-schema/gcp-cloud-storage-bucket-schema.json\n      - type: JSONSchema\n        url: json-schema/gcp-cloud-storage-json-bucket-schema.json\n      - type: JSONSchema\n        url: json-schema/gcp-cloud-storage-json-bucket-access-control-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/gcp-cloud-storage-json-bucket-list-schema.json\n      - type: JSONSchema\n        url: json-schema/gcp-cloud-storage-json-channel-schema.json\n      - type: JSONSchema\n        url: json-schema/gcp-cloud-storage-json-compose-request-schema.json\n      - type: JSONSchema\n        url: json-schema/gcp-cloud-storage-json-error-schema.json\n      - type: JSONSchema\n        url: json-schema/gcp-cloud-storage-json-object-access-control-schema.json\n      - type: JSONSchema\n        url: json-schema/gcp-cloud-storage-json-object-list-schema.json\n      - type: JSONSchema\n        url: json-schema/gcp-cloud-storage-json-object-schema.json\n      - type: JSONSchema\n        url: json-schema/gcp-cloud-storage-json-policy-schema.json\n      - type: JSONSchema\n        url: json-schema/gcp-cloud-storage-json-rewrite-response-schema.json\n      - type: JSONLD\n        url: json-ld/gcp-cloud-storage-context.jsonld\n      - type: JSONLD\n        url:\
  \ json-ld/gcp-cloud-storage-json-context.jsonld\n    contact:\n      - type: Support\n        url: https://cloud.google.com/storage/docs/getting-support\n  - name: Google Cloud Storage XML API\n    description: >-\n      Amazon S3-compatible XML API for Google Cloud Storage.\n    image: https://cloud.google.com/images/storage/storage-icon.svg\n    humanURL: https://cloud.google.com/storage/docs/xml-api\n    baseURL: https://storage.googleapis.com\n    tags:\n      - S3 Compatible\n      - XML\n      - Interoperability\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/storage/docs/xml-api/overview\n      - type: Authentication\n        url: https://cloud.google.com/storage/docs/authentication/hmackeys\n      - type: APIReference\n        url: https://cloud.google.com/storage/docs/xml-api/reference-methods\n      - type: Pricing\n        url: https://cloud.google.com/storage/pricing\n      - type: RateLimits\n        url: https://cloud.google.com/storage/quotas\n\
  \      - type: TermsOfService\n        url: https://cloud.google.com/terms\n    contact:\n      - type: Support\n        url: https://cloud.google.com/storage/docs/getting-support\ncommon:\n  - type: GettingStarted\n    url: https://cloud.google.com/storage/docs/quickstarts\n  - type: SDK\n    url: https://cloud.google.com/storage/docs/reference/libraries\n  - type: Console\n    url: https://console.cloud.google.com/storage\n  - type: Blog\n    url: https://cloud.google.com/blog/products/storage-data-transfer\n  - type: ChangeLog\n    url: https://cloud.google.com/storage/docs/release-notes\n  - type: BestPractices\n    url: https://cloud.google.com/storage/docs/best-practices\n  - type: Security\n    url: https://cloud.google.com/storage/docs/security\n  - type: Compliance\n    url: https://cloud.google.com/security/compliance\n  - type: APIReference\n    url: https://cloud.google.com/storage/docs/apis\n  - type: CLI\n    url: https://cloud.google.com/storage/docs/discover-object-storage-gsutil\n\
  \  - type: SpectralRules\n    url: rules/gcp-cloud-storage-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/gcp-cloud-storage-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/cloud-storage.yaml\n  - type: Features\n    data:\n      - name: Multi-Regional Storage\n        description: Store data across multiple regions for high availability and low-latency access worldwide.\n      - name: Object Lifecycle Management\n        description: Automatically transition objects between storage classes or delete them based on configurable rules.\n      - name: Versioning\n        description: Maintain multiple versions of objects for data protection and recovery.\n      - name: Fine-Grained Access Control\n        description: Control access using IAM policies, ACLs, and signed URLs for secure data sharing.\n      - name: Object Composition\n        description: Compose multiple objects into a single object without downloading and re-uploading data.\n      - name:\
  \ Change Notifications\n        description: Watch for changes to objects in a bucket and receive push notifications.\n      - name: Retention Policies\n        description: Lock retention policies to prevent object deletion for regulatory compliance.\n  - type: UseCases\n    data:\n      - name: Data Lake Storage\n        description: Store structured and unstructured data at scale for analytics and machine learning pipelines.\n      - name: Backup and Disaster Recovery\n        description: Store backups with configurable retention and cross-region replication for business continuity.\n      - name: Static Website Hosting\n        description: Serve static web content directly from Cloud Storage buckets with custom domains.\n      - name: Media Content Delivery\n        description: Store and serve media assets with CDN integration for low-latency content delivery.\n  - type: Integrations\n    data:\n      - name: BigQuery\n        description: Load data directly from Cloud Storage into\
  \ BigQuery for analytics and data warehousing.\n      - name: Cloud Functions\n        description: Trigger serverless functions on object creation, deletion, or metadata changes.\n      - name: Dataflow\n        description: Process data stored in Cloud Storage using Apache Beam pipelines.\n      - name: Transfer Service\n        description: Transfer data between on-premises storage, other clouds, and Cloud Storage.\n      - name: Cloud CDN\n        description: Cache and serve Cloud Storage content through Google's global edge network.\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/gcp-cloud-storage/refs/heads/main/apis.yml
tags:
- Archival
- Backup
- Blob Storage
- Cloud Storage
- Data
- File Storage
- Google Cloud
- Object Storage
- Storage
url: https://cloud.google.com/storage
use_cases:
- description: Store structured and unstructured data at scale for analytics and machine learning pipelines.
  name: Data Lake Storage
- description: Store backups with configurable retention and cross-region replication for business continuity.
  name: Backup and Disaster Recovery
- description: Serve static web content directly from Cloud Storage buckets with custom domains.
  name: Static Website Hosting
- description: Store and serve media assets with CDN integration for low-latency content delivery.
  name: Media Content Delivery
---
