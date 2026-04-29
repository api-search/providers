---
api_count: 6
apis:
- description: The Confluent Cloud REST API is the management plane for Confluent Cloud. It is used to manage organizations, environments, Kafka and Flink clusters, service accounts, API keys, role bindings, network
  name: Confluent Cloud REST API
  slug: cloud-rest-api
- description: The Kafka REST API (Confluent REST Proxy in self-managed deployments, Kafka REST in Cloud) provides HTTP access to Apache Kafka topics, consumers, partitions, brokers, and ACLs. Clients without a nati
  name: Confluent Kafka REST API
  slug: kafka-rest-api
- description: The Schema Registry REST API stores and serves Avro, JSON Schema, and Protobuf schemas with versioning and compatibility enforcement. It is available both as a managed Confluent Cloud service and as a
  name: Confluent Schema Registry REST API
  slug: schema-registry-api
- description: The Kafka Connect REST API manages connectors, tasks, and worker configuration. Operators use it to deploy, configure, pause, resume, and delete source and sink connectors, inspect task status, and re
  name: Kafka Connect REST API
  slug: connect-rest-api
- description: The ksqlDB REST API exposes ksqlDB, Confluent's streaming SQL engine, over HTTP. Clients submit streaming SQL statements, query streams and tables (push and pull queries), and inspect server status.
  name: ksqlDB REST API
  slug: ksqldb-rest-api
- description: The Confluent Cloud for Apache Flink REST API manages Flink compute pools, statements, and workspaces for stateful stream processing on Confluent Cloud. It is part of the Confluent Cloud REST surface.
  name: Confluent Cloud for Apache Flink REST API
  slug: flink-rest-api
common:
- title: ''
  type: Website
  url: https://www.confluent.io/
- title: ''
  type: Developer Portal
  url: https://developer.confluent.io/
- title: ''
  type: Documentation
  url: https://docs.confluent.io/
- title: ''
  type: Cloud API Reference
  url: https://docs.confluent.io/cloud/current/api.html
- title: ''
  type: GitHub
  url: https://github.com/confluentinc
- title: ''
  type: Blog
  url: https://www.confluent.io/blog/
- title: ''
  type: Pricing
  url: https://www.confluent.io/pricing/
- title: ''
  type: Status
  url: https://status.confluent.cloud/
- title: ''
  type: Login
  url: https://confluent.cloud/login
- title: ''
  type: Marketplace
  url: https://www.confluent.io/hub/
- title: ''
  type: Training
  url: https://training.confluent.io/
- title: ''
  type: Terms of Service
  url: https://www.confluent.io/terms-of-service/
- title: ''
  type: Privacy Policy
  url: https://www.confluent.io/privacy-policy/
created: '2025-08-19'
description: Confluent is a fully managed data streaming platform built by the original creators of Apache Kafka. It lets organizations stream, connect, process, and govern data in motion through a cloud-native service (Confluent Cloud) and the on-prem/self-managed Confluent Platform. Confluent's developer surface includes the Confluent Cloud REST API for managing clusters, environments, and access; the Kafka REST Proxy for producing and consuming events over HTTP; the Schema Registry REST API for governance of Avro, JSON Schema, and Protobuf schemas; the Kafka Connect REST API for managing connectors; the ksqlDB REST API for stream processing; and managed Apache Flink. Authentication is API-key based (Cloud) or HTTP/mTLS/OAuth (Platform).
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Confluent | the Data Streaming Platform
skills: []
slug: confluent-the-data-streaming-platform
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: confluent-the-data-streaming-platform\nname: Confluent | the Data Streaming Platform\ndescription: >-\n  Confluent is a fully managed data streaming platform built by the original\n  creators of Apache Kafka. It lets organizations stream, connect, process,\n  and govern data in motion through a cloud-native service (Confluent Cloud)\n  and the on-prem/self-managed Confluent Platform. Confluent's developer\n  surface includes the Confluent Cloud REST API for managing clusters,\n  environments, and access; the Kafka REST Proxy for producing and consuming\n  events over HTTP; the Schema Registry REST API for governance of Avro,\n  JSON Schema, and Protobuf schemas; the Kafka Connect REST API for managing\n  connectors; the ksqlDB REST API for stream processing; and managed Apache\n  Flink. Authentication is API-key based (Cloud) or HTTP/mTLS/OAuth (Platform).\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  url: >-\n  https://raw.githubusercontent.com/api-evangelist/confluent-the-data-streaming-platform/refs/heads/main/apis.yml\ncreated: '2025-08-19'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nx-type: company\ntags:\n  - Apache Flink\n  - Apache Kafka\n  - Confluent Cloud\n  - Connectors\n  - Data Streaming\n  - Event Streaming\n  - Kafka Connect\n  - ksqlDB\n  - Real-Time Data\n  - REST\n  - Schema Registry\n  - Stream Processing\napis:\n  - aid: confluent-the-data-streaming-platform:cloud-rest-api\n    name: Confluent Cloud REST API\n    description: >-\n      The Confluent Cloud REST API is the management plane for Confluent\n      Cloud. It is used to manage organizations, environments, Kafka and\n      Flink clusters, service accounts, API keys, role bindings, networking,\n      schema registry clusters, and connector instances. The API uses Cloud\n      API keys for authentication and follows Confluent's resource-oriented\n      v2 conventions.\n    humanURL: https://docs.confluent.io/cloud/current/api.html\n\
  \    baseURL: https://api.confluent.cloud\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Confluent Cloud\n      - Management\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.confluent.io/cloud/current/api.html\n      - type: API Reference\n        url: https://docs.confluent.io/cloud/current/api.html\n    x-features:\n      - Cluster Lifecycle Management\n      - Environments and Organizations\n      - API Key Management\n      - RBAC and Service Accounts\n      - Networking and Private Link\n      - Schema Registry Cluster Management\n      - Connector Provisioning\n      - Flink Compute Pools\n    x-use-cases:\n      - Provision Kafka clusters in Confluent Cloud\n      - Automate environment and access management\n      - Rotate API keys and manage service accounts\n      - Wire up private networking for clusters\n      - Manage Flink compute pools and statements\n  - aid: confluent-the-data-streaming-platform:kafka-rest-api\n\
  \    name: Confluent Kafka REST API\n    description: >-\n      The Kafka REST API (Confluent REST Proxy in self-managed deployments,\n      Kafka REST in Cloud) provides HTTP access to Apache Kafka topics,\n      consumers, partitions, brokers, and ACLs. Clients without a native\n      Kafka library can produce and consume records, manage topics, and\n      inspect metadata over HTTP. Cloud variants additionally enforce\n      RBAC and Confluent Cloud authentication.\n    humanURL: https://docs.confluent.io/platform/current/kafka-rest/api.html\n    baseURL: https://pkc-XXXXX.region.aws.confluent.cloud\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Apache Kafka\n      - Producer\n      - Consumer\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.confluent.io/platform/current/kafka-rest/api.html\n      - type: Cloud Documentation\n        url: https://docs.confluent.io/cloud/current/kafka-rest/index.html\n\
  \    x-features:\n      - Topic Management\n      - Produce and Consume over HTTP\n      - Partition Inspection\n      - Consumer Group Management\n      - Broker Metadata\n      - ACL Management\n    x-use-cases:\n      - Produce events from clients without a Kafka library\n      - Bridge legacy systems to Kafka over HTTP\n      - Inspect topic and partition metadata from web tools\n      - Manage ACLs from automation scripts\n  - aid: confluent-the-data-streaming-platform:schema-registry-api\n    name: Confluent Schema Registry REST API\n    description: >-\n      The Schema Registry REST API stores and serves Avro, JSON Schema, and\n      Protobuf schemas with versioning and compatibility enforcement. It is\n      available both as a managed Confluent Cloud service and as a\n      self-managed component of Confluent Platform. The full developer\n      profile lives in the api-evangelist/confluent-schema-registry repository.\n    humanURL: https://docs.confluent.io/platform/current/schema-registry/develop/api.html\n\
  \    baseURL: https://psrc-XXXXX.region.aws.confluent.cloud\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Avro\n      - JSON Schema\n      - Protobuf\n      - Schema Registry\n    properties:\n      - type: Documentation\n        url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html\n      - type: Companion Repo\n        url: https://github.com/api-evangelist/confluent-schema-registry\n    x-features:\n      - Avro/JSON Schema/Protobuf Support\n      - Compatibility Enforcement\n      - Schema Versioning\n      - Schema References\n      - Schema Linking\n    x-use-cases:\n      - Govern data contracts across producers and consumers\n      - Evolve schemas with backward and forward compatibility\n      - Share schemas across environments via Schema Linking\n  - aid: confluent-the-data-streaming-platform:connect-rest-api\n    name: Kafka Connect REST API\n    description: >-\n      The Kafka Connect\
  \ REST API manages connectors, tasks, and worker\n      configuration. Operators use it to deploy, configure, pause, resume,\n      and delete source and sink connectors, inspect task status, and\n      restart failed tasks. In Confluent Cloud, managed connectors are\n      provisioned through the Cloud REST API while runtime status is\n      exposed via the Connect REST surface.\n    humanURL: https://docs.confluent.io/platform/current/connect/references/restapi.html\n    baseURL: https://localhost:8083\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Connectors\n      - Kafka Connect\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.confluent.io/platform/current/connect/references/restapi.html\n    x-features:\n      - Connector Lifecycle Management\n      - Task Status and Restart\n      - Plugin Discovery\n      - Configuration Validation\n    x-use-cases:\n      - Deploy and operate source/sink\
  \ connectors\n      - Restart failed tasks programmatically\n      - Validate connector configurations in CI\n  - aid: confluent-the-data-streaming-platform:ksqldb-rest-api\n    name: ksqlDB REST API\n    description: >-\n      The ksqlDB REST API exposes ksqlDB, Confluent's streaming SQL engine,\n      over HTTP. Clients submit streaming SQL statements, query streams\n      and tables (push and pull queries), and inspect server status.\n    humanURL: https://docs.ksqldb.io/en/latest/developer-guide/api/\n    baseURL: https://localhost:8088\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - ksqlDB\n      - REST\n      - Streaming SQL\n    properties:\n      - type: Documentation\n        url: https://docs.ksqldb.io/en/latest/developer-guide/api/\n    x-features:\n      - Push and Pull Queries\n      - Streaming SQL Execution\n      - Server Health and Status\n    x-use-cases:\n      - Run streaming SQL from web applications\n    \
  \  - Build real-time materialized views\n      - Power dashboards with push queries\n  - aid: confluent-the-data-streaming-platform:flink-rest-api\n    name: Confluent Cloud for Apache Flink REST API\n    description: >-\n      The Confluent Cloud for Apache Flink REST API manages Flink compute\n      pools, statements, and workspaces for stateful stream processing on\n      Confluent Cloud. It is part of the Confluent Cloud REST surface.\n    humanURL: https://docs.confluent.io/cloud/current/flink/index.html\n    baseURL: https://flink.region.aws.confluent.cloud\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Apache Flink\n      - Stream Processing\n    properties:\n      - type: Documentation\n        url: https://docs.confluent.io/cloud/current/flink/index.html\n    x-features:\n      - Flink Compute Pools\n      - Flink SQL Statements\n      - Workspace Management\n    x-use-cases:\n      - Run stateful stream processing on\
  \ Confluent Cloud\n      - Deploy Flink SQL jobs through automation\ncommon:\n  - type: Website\n    url: https://www.confluent.io/\n  - type: Developer Portal\n    url: https://developer.confluent.io/\n  - type: Documentation\n    url: https://docs.confluent.io/\n  - type: Cloud API Reference\n    url: https://docs.confluent.io/cloud/current/api.html\n  - type: GitHub\n    url: https://github.com/confluentinc\n  - type: Blog\n    url: https://www.confluent.io/blog/\n  - type: Pricing\n    url: https://www.confluent.io/pricing/\n  - type: Status\n    url: https://status.confluent.cloud/\n  - type: Login\n    url: https://confluent.cloud/login\n  - type: Marketplace\n    url: https://www.confluent.io/hub/\n  - type: Training\n    url: https://training.confluent.io/\n  - type: Terms of Service\n    url: https://www.confluent.io/terms-of-service/\n  - type: Privacy Policy\n    url: https://www.confluent.io/privacy-policy/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/confluent-the-data-streaming-platform/refs/heads/main/apis.yml
tags:
- Apache Flink
- Apache Kafka
- Confluent Cloud
- Connectors
- Data Streaming
- Event Streaming
- Kafka Connect
- ksqlDB
- Real-Time Data
- REST
- Schema Registry
- Stream Processing
url: https://raw.githubusercontent.com/api-evangelist/confluent-the-data-streaming-platform/refs/heads/main/apis.yml
use_cases: []
---
