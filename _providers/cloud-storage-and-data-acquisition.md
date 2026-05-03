---
api_count: 6
apis:
- description: 'The object-storage surface includes Amazon S3, Google Cloud Storage, and Azure Blob Storage REST APIs. These APIs provide the canonical landing zone for cloud data acquisition and are the most common '
  name: Object Storage Surface
  slug: object-storage
- description: The streaming-ingest surface covers Amazon Kinesis Data Streams, Google Cloud Pub/Sub, and Azure Event Hubs. These services ingest high-volume event streams and make them durable for downstream landin
  name: Streaming Ingest Surface
  slug: streaming-ingest
- description: Managed ingestion pipelines such as AWS Glue, Google Cloud Dataflow, and Azure Data Factory expose REST APIs for orchestrating extract-transform-load and extract-load-transform jobs that land source d
  name: Managed Ingestion Pipelines
  slug: managed-ingestion
- description: 'Change Data Capture connectors (Debezium, AWS DMS, Fivetran, Striim) replicate row-level changes from operational databases to cloud storage and warehouses, providing a low-latency feed for analytics '
  name: Change Data Capture Connectors
  slug: change-data-capture
- description: Bulk transfer services (AWS DataSync and Snow family, Google Storage Transfer Service, Azure Data Box) move large datasets from on-premises and edge locations into cloud storage over network or via of
  name: Bulk Transfer Services
  slug: transfer-services
- description: Data marketplaces and open-data registries expose third-party datasets through REST APIs, subscription delivery, and shared buckets. They are an increasingly common acquisition channel for cloud-stora
  name: Data Marketplaces
  slug: data-marketplaces
common:
- title: ''
  type: Topic
  url: https://apievangelist.com/topics/cloud-storage-and-data-acquisition/
- title: ''
  type: API Evangelist
  url: https://apievangelist.com/
- title: ''
  type: Network
  url: https://network.apievangelist.com/
- title: ''
  type: GitHub
  url: https://github.com/api-evangelist
- title: ''
  type: JSON-LD
  url: json-ld/cloud-storage-and-data-acquisition-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloud-storage-and-data-acquisition-rules.yml
created: '2024-01-01'
description: Cloud Storage and Data Acquisition is a topic profile in the API Evangelist Network covering APIs and tooling for ingesting, moving, and persisting bulk and streaming data into cloud-resident storage. It groups object storage services, data-lake foundations, managed ingestion pipelines, change-data-capture connectors, transfer appliances, and data-broker APIs that provide source material for cloud-storage workloads. The topic is intended as an entry point for developers and architects evaluating how data lands in cloud storage from on-premises systems, SaaS APIs, IoT devices, public data sources, and partner exchanges.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloud Storage And Data Acquisition Context
  property_count: 5
  slug: cloud-storage-and-data-acquisition-context
layout: provider
modified: '2026-04-23'
name: Cloud Storage and Data Acquisition
rules:
- name: Cloud Storage and Data Acquisition API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 4
  slug: cloud-storage-and-data-acquisition-rules
skills: []
slug: cloud-storage-and-data-acquisition
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloud-storage-and-data-acquisition\nname: Cloud Storage and Data Acquisition\ndescription: >-\n  Cloud Storage and Data Acquisition is a topic profile in the API\n  Evangelist Network covering APIs and tooling for ingesting, moving,\n  and persisting bulk and streaming data into cloud-resident storage.\n  It groups object storage services, data-lake foundations, managed\n  ingestion pipelines, change-data-capture connectors, transfer\n  appliances, and data-broker APIs that provide source material for\n  cloud-storage workloads. The topic is intended as an entry point\n  for developers and architects evaluating how data lands in cloud\n  storage from on-premises systems, SaaS APIs, IoT devices, public\n  data sources, and partner exchanges.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/cloud-storage-and-data-acquisition/refs/heads/main/apis.yml\ncreated: '2024-01-01'\n\
  modified: '2026-04-23'\nspecificationVersion: '0.19'\nx-type: topic\ntags:\n  - Bulk Transfer\n  - Change Data Capture\n  - Cloud Storage\n  - Data Acquisition\n  - Data Ingestion\n  - Data Lake\n  - ETL\n  - Object Storage\n  - Pipelines\n  - Streaming\napis:\n  - aid: cloud-storage-and-data-acquisition:object-storage\n    name: Object Storage Surface\n    tags:\n      - Object Storage\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://aws.amazon.com/s3/\n    properties:\n      - url: https://docs.aws.amazon.com/AmazonS3/latest/API/Welcome.html\n        type: Documentation\n      - url: https://cloud.google.com/storage/docs/json_api/v1\n        type: Documentation\n      - url: https://learn.microsoft.com/en-us/rest/api/storageservices/blob-service-rest-api\n        type: Documentation\n    description: >-\n      The object-storage surface includes Amazon S3, Google Cloud\n      Storage, and Azure Blob Storage REST\
  \ APIs. These APIs provide\n      the canonical landing zone for cloud data acquisition and are\n      the most common targets for ingestion pipelines.\n  - aid: cloud-storage-and-data-acquisition:streaming-ingest\n    name: Streaming Ingest Surface\n    tags:\n      - Pub/Sub\n      - Real-time\n      - Streaming\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://aws.amazon.com/kinesis/data-streams/\n    properties:\n      - url: https://docs.aws.amazon.com/kinesis/latest/APIReference/\n        type: Documentation\n      - url: https://cloud.google.com/pubsub/docs/reference/rest\n        type: Documentation\n      - url: https://learn.microsoft.com/en-us/rest/api/eventhub/\n        type: Documentation\n    description: >-\n      The streaming-ingest surface covers Amazon Kinesis Data Streams,\n      Google Cloud Pub/Sub, and Azure Event Hubs. These services\n      ingest high-volume event streams and make them durable for\n  \
  \    downstream landing into object storage and analytics systems.\n  - aid: cloud-storage-and-data-acquisition:managed-ingestion\n    name: Managed Ingestion Pipelines\n    tags:\n      - Data Pipelines\n      - ETL\n      - Managed\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://aws.amazon.com/glue/\n    properties:\n      - url: https://docs.aws.amazon.com/glue/latest/webapi/Welcome.html\n        type: Documentation\n      - url: https://cloud.google.com/dataflow/docs/reference/rest\n        type: Documentation\n      - url: https://learn.microsoft.com/en-us/rest/api/datafactory/\n        type: Documentation\n    description: >-\n      Managed ingestion pipelines such as AWS Glue, Google Cloud\n      Dataflow, and Azure Data Factory expose REST APIs for\n      orchestrating extract-transform-load and extract-load-transform\n      jobs that land source data in cloud storage.\n  - aid: cloud-storage-and-data-acquisition:change-data-capture\n\
  \    name: Change Data Capture Connectors\n    tags:\n      - CDC\n      - Connectors\n      - Replication\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://debezium.io/\n    properties:\n      - url: https://debezium.io/documentation/\n        type: Documentation\n      - url: https://docs.aws.amazon.com/dms/\n        type: Documentation\n    description: >-\n      Change Data Capture connectors (Debezium, AWS DMS, Fivetran,\n      Striim) replicate row-level changes from operational databases\n      to cloud storage and warehouses, providing a low-latency feed\n      for analytics and data-lake hydration.\n  - aid: cloud-storage-and-data-acquisition:transfer-services\n    name: Bulk Transfer Services\n    tags:\n      - Bulk Transfer\n      - Migration\n      - Offline\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://aws.amazon.com/datasync/\n    properties:\n    \
  \  - url: https://docs.aws.amazon.com/datasync/latest/userguide/API_Reference.html\n        type: Documentation\n      - url: https://cloud.google.com/storage-transfer/docs/reference/rest\n        type: Documentation\n      - url: https://learn.microsoft.com/en-us/azure/databox/\n        type: Documentation\n    description: >-\n      Bulk transfer services (AWS DataSync and Snow family, Google\n      Storage Transfer Service, Azure Data Box) move large datasets\n      from on-premises and edge locations into cloud storage over\n      network or via offline appliances.\n  - aid: cloud-storage-and-data-acquisition:data-marketplaces\n    name: Data Marketplaces\n    tags:\n      - Datasets\n      - Marketplace\n      - Open Data\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://aws.amazon.com/data-exchange/\n    properties:\n      - url: https://aws.amazon.com/data-exchange/\n        type: Documentation\n      - url: https://cloud.google.com/marketplace\n\
  \        type: Documentation\n      - url: https://registry.opendata.aws/\n        type: Open Data Registry\n    description: >-\n      Data marketplaces and open-data registries expose third-party\n      datasets through REST APIs, subscription delivery, and shared\n      buckets. They are an increasingly common acquisition channel\n      for cloud-storage data lakes.\ncommon:\n  - type: Topic\n    url: https://apievangelist.com/topics/cloud-storage-and-data-acquisition/\n  - type: API Evangelist\n    url: https://apievangelist.com/\n  - type: Network\n    url: https://network.apievangelist.com/\n  - type: GitHub\n    url: https://github.com/api-evangelist\n  - type: JSON-LD\n    url: json-ld/cloud-storage-and-data-acquisition-context.jsonld\n  - type: Spectral\n    url: rules/cloud-storage-and-data-acquisition-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloud-storage-and-data-acquisition/refs/heads/main/apis.yml
tags:
- Bulk Transfer
- Change Data Capture
- Cloud Storage
- Data Acquisition
- Data Ingestion
- Data Lake
- ETL
- Object Storage
- Pipelines
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/cloud-storage-and-data-acquisition/refs/heads/main/apis.yml
use_cases: []
---
