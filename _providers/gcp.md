---
api_count: 10
api_specs:
- filename: rest
  format: yaml
  label: Compute Engine API
  slug: compute-engine
  spec_type: OpenAPI
  url: https://compute.googleapis.com/$discovery/rest?version=v1
- filename: rest
  format: yaml
  label: Cloud Storage API
  slug: cloud-storage
  spec_type: OpenAPI
  url: https://storage.googleapis.com/$discovery/rest?version=v1
- filename: rest
  format: yaml
  label: Cloud Functions API
  slug: cloud-functions
  spec_type: OpenAPI
  url: https://cloudfunctions.googleapis.com/$discovery/rest?version=v1
- filename: rest
  format: yaml
  label: Cloud Pub/Sub API
  slug: cloud-pubsub
  spec_type: OpenAPI
  url: https://pubsub.googleapis.com/$discovery/rest?version=v1
- filename: rest
  format: yaml
  label: BigQuery API
  slug: bigquery
  spec_type: OpenAPI
  url: https://bigquery.googleapis.com/$discovery/rest?version=v2
- filename: rest
  format: yaml
  label: Cloud Vision API
  slug: cloud-vision
  spec_type: OpenAPI
  url: https://vision.googleapis.com/$discovery/rest?version=v1
- filename: rest
  format: yaml
  label: Cloud Natural Language API
  slug: cloud-natural-language
  spec_type: OpenAPI
  url: https://language.googleapis.com/$discovery/rest?version=v1
- filename: rest
  format: yaml
  label: Kubernetes Engine API
  slug: kubernetes-engine
  spec_type: OpenAPI
  url: https://container.googleapis.com/$discovery/rest?version=v1
- filename: rest
  format: yaml
  label: Cloud SQL Admin API
  slug: cloud-sql
  spec_type: OpenAPI
  url: https://sqladmin.googleapis.com/$discovery/rest?version=v1
- filename: rest
  format: yaml
  label: Cloud Firestore API
  slug: cloud-firestore
  spec_type: OpenAPI
  url: https://firestore.googleapis.com/$discovery/rest?version=v1
apis:
- description: Create and manage virtual machines on Google's infrastructure.
  name: Compute Engine API
  slug: compute-engine
- description: Object storage service for storing and accessing data on Google Cloud Platform.
  name: Cloud Storage API
  slug: cloud-storage
- description: Event-driven serverless compute platform for building and connecting cloud services.
  name: Cloud Functions API
  slug: cloud-functions
- description: Messaging and ingestion service for event-driven systems and streaming analytics.
  name: Cloud Pub/Sub API
  slug: cloud-pubsub
- description: Serverless, highly scalable data warehouse for analytics.
  name: BigQuery API
  slug: bigquery
- description: Image analysis and machine learning for detecting objects, faces, and text.
  name: Cloud Vision API
  slug: cloud-vision
- description: Natural language understanding and sentiment analysis.
  name: Cloud Natural Language API
  slug: cloud-natural-language
- description: Managed Kubernetes service for deploying containerized applications.
  name: Kubernetes Engine API
  slug: kubernetes-engine
- description: Managed MySQL, PostgreSQL, and SQL Server databases.
  name: Cloud SQL Admin API
  slug: cloud-sql
- description: NoSQL document database for mobile, web, and server development.
  name: Cloud Firestore API
  slug: cloud-firestore
common:
- title: ''
  type: Authentication
  url: https://cloud.google.com/docs/authentication
- title: ''
  type: Console
  url: https://console.cloud.google.com
- title: ''
  type: Status
  url: https://status.cloud.google.com
- title: ''
  type: Support
  url: https://cloud.google.com/support
- title: ''
  type: Getting Started
  url: https://cloud.google.com/docs
- title: ''
  type: SDKs
  url: https://cloud.google.com/sdk
- title: ''
  type: Blog
  url: https://cloud.google.com/blog
- title: ''
  type: Terms of Service
  url: https://cloud.google.com/terms
created: '2024-01-01'
description: Comprehensive collection of Google Cloud Platform APIs for cloud computing, storage, machine learning, and infrastructure management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Google Cloud Platform APIs
skills: []
slug: gcp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: gcp\nname: Google Cloud Platform APIs\ndescription: >-\n  Comprehensive collection of Google Cloud Platform APIs for cloud computing, storage,\n  machine learning, and infrastructure management.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nposition: Consumer\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/gcp/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\ntags:\n  - Cloud Computing\n  - Databases\n  - Infrastructure\n  - Machine Learning\n  - Networking\n  - Security\n  - Serverless\n  - Storage\napis:\n  - aid: gcp:compute-engine\n    name: Compute Engine API\n    description: >-\n      Create and manage virtual machines on Google's infrastructure.\n    humanURL: https://cloud.google.com/compute\n    baseURL: https://compute.googleapis.com\n    tags:\n      - Compute\n      - IaaS\n      - Virtual Machines\n    properties:\n      -\
  \ type: Documentation\n        url: https://cloud.google.com/compute/docs/reference/rest/v1\n      - type: OpenAPI\n        url: https://compute.googleapis.com/$discovery/rest?version=v1\n      - type: Console\n        url: https://console.cloud.google.com/compute\n  - aid: gcp:cloud-storage\n    name: Cloud Storage API\n    description: >-\n      Object storage service for storing and accessing data on Google Cloud Platform.\n    humanURL: https://cloud.google.com/storage\n    baseURL: https://storage.googleapis.com\n    tags:\n      - Data\n      - Object Storage\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/storage/docs/json_api\n      - type: OpenAPI\n        url: https://storage.googleapis.com/$discovery/rest?version=v1\n      - type: Console\n        url: https://console.cloud.google.com/storage\n  - aid: gcp:cloud-functions\n    name: Cloud Functions API\n    description: >-\n      Event-driven serverless compute platform for\
  \ building and connecting cloud services.\n    humanURL: https://cloud.google.com/functions\n    baseURL: https://cloudfunctions.googleapis.com\n    tags:\n      - FaaS\n      - Functions\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/functions/docs/reference/rest\n      - type: OpenAPI\n        url: https://cloudfunctions.googleapis.com/$discovery/rest?version=v1\n      - type: Console\n        url: https://console.cloud.google.com/functions\n  - aid: gcp:cloud-pubsub\n    name: Cloud Pub/Sub API\n    description: >-\n      Messaging and ingestion service for event-driven systems and streaming analytics.\n    humanURL: https://cloud.google.com/pubsub\n    baseURL: https://pubsub.googleapis.com\n    tags:\n      - Events\n      - Messaging\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/pubsub/docs/reference/rest\n      - type: OpenAPI\n        url: https://pubsub.googleapis.com/$discovery/rest?version=v1\n\
  \      - type: Console\n        url: https://console.cloud.google.com/cloudpubsub\n  - aid: gcp:bigquery\n    name: BigQuery API\n    description: >-\n      Serverless, highly scalable data warehouse for analytics.\n    humanURL: https://cloud.google.com/bigquery\n    baseURL: https://bigquery.googleapis.com\n    tags:\n      - Analytics\n      - Big Data\n      - Data Warehouse\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/bigquery/docs/reference/rest\n      - type: OpenAPI\n        url: https://bigquery.googleapis.com/$discovery/rest?version=v2\n      - type: Console\n        url: https://console.cloud.google.com/bigquery\n  - aid: gcp:cloud-vision\n    name: Cloud Vision API\n    description: >-\n      Image analysis and machine learning for detecting objects, faces, and text.\n    humanURL: https://cloud.google.com/vision\n    baseURL: https://vision.googleapis.com\n    tags:\n      - AI\n      - Computer Vision\n      - Machine Learning\n   \
  \ properties:\n      - type: Documentation\n        url: https://cloud.google.com/vision/docs/reference/rest\n      - type: OpenAPI\n        url: https://vision.googleapis.com/$discovery/rest?version=v1\n      - type: Console\n        url: https://console.cloud.google.com/apis/library/vision.googleapis.com\n  - aid: gcp:cloud-natural-language\n    name: Cloud Natural Language API\n    description: >-\n      Natural language understanding and sentiment analysis.\n    humanURL: https://cloud.google.com/natural-language\n    baseURL: https://language.googleapis.com\n    tags:\n      - AI\n      - Machine Learning\n      - NLP\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/natural-language/docs/reference/rest\n      - type: OpenAPI\n        url: https://language.googleapis.com/$discovery/rest?version=v1\n      - type: Console\n        url: https://console.cloud.google.com/apis/library/language.googleapis.com\n  - aid: gcp:kubernetes-engine\n    name: Kubernetes\
  \ Engine API\n    description: >-\n      Managed Kubernetes service for deploying containerized applications.\n    humanURL: https://cloud.google.com/kubernetes-engine\n    baseURL: https://container.googleapis.com\n    tags:\n      - Containers\n      - Kubernetes\n      - Orchestration\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/kubernetes-engine/docs/reference/rest\n      - type: OpenAPI\n        url: https://container.googleapis.com/$discovery/rest?version=v1\n      - type: Console\n        url: https://console.cloud.google.com/kubernetes\n  - aid: gcp:cloud-sql\n    name: Cloud SQL Admin API\n    description: >-\n      Managed MySQL, PostgreSQL, and SQL Server databases.\n    humanURL: https://cloud.google.com/sql\n    baseURL: https://sqladmin.googleapis.com\n    tags:\n      - Database\n      - Managed Service\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/sql/docs/mysql/admin-api\n     \
  \ - type: OpenAPI\n        url: https://sqladmin.googleapis.com/$discovery/rest?version=v1\n      - type: Console\n        url: https://console.cloud.google.com/sql\n  - aid: gcp:cloud-firestore\n    name: Cloud Firestore API\n    description: >-\n      NoSQL document database for mobile, web, and server development.\n    humanURL: https://cloud.google.com/firestore\n    baseURL: https://firestore.googleapis.com\n    tags:\n      - Database\n      - NoSQL\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/firestore/docs/reference/rest\n      - type: OpenAPI\n        url: https://firestore.googleapis.com/$discovery/rest?version=v1\n      - type: Console\n        url: https://console.cloud.google.com/firestore\ncommon:\n  - type: Authentication\n    url: https://cloud.google.com/docs/authentication\n  - type: Console\n    url: https://console.cloud.google.com\n  - type: Status\n    url: https://status.cloud.google.com\n  - type: Support\n\
  \    url: https://cloud.google.com/support\n  - type: Getting Started\n    url: https://cloud.google.com/docs\n  - type: SDKs\n    url: https://cloud.google.com/sdk\n  - type: Blog\n    url: https://cloud.google.com/blog\n  - type: Terms of Service\n    url: https://cloud.google.com/terms\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/gcp/refs/heads/main/apis.yml
tags:
- Cloud Computing
- Databases
- Infrastructure
- Machine Learning
- Networking
- Security
- Serverless
- Storage
url: https://raw.githubusercontent.com/api-evangelist/gcp/refs/heads/main/apis.yml
use_cases: []
---
