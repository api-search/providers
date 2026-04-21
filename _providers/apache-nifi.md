---
api_count: 3
apis:
- description: The NiFi REST API provides comprehensive JWT-authenticated endpoints for managing processors, connections, controller services, process groups, reporting tasks, provenance, flow versions, system diagn
  name: Apache NiFi REST API
  slug: apache-nifi-rest-api
- description: NiFi Registry provides a central location for storage and management of shared NiFi flow resources, enabling versioned flows across NiFi environments. It provides its own REST API for managing buckets
  name: Apache NiFi Registry
  slug: apache-nifi-registry
- description: MiNiFi is a lightweight agent for edge data collection that is a subproject of NiFi. MiNiFi C++ (nifi-minifi-cpp) provides a small-footprint agent for IoT edge data collection with local processing an
  name: Apache MiNiFi
  slug: apache-minifi
common:
- title: ''
  type: Portal
  url: https://nifi.apache.org/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/nifi
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/nifi-minifi-cpp
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/nifi-api
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/nifi-site
- title: ''
  type: Wiki
  url: https://cwiki.apache.org/confluence/display/NIFI
- title: ''
  type: IssueTracker
  url: https://issues.apache.org/jira/browse/NIFI
- title: ''
  type: Slack
  url: https://join.slack.com/t/apachenifi/shared_invite/zt-11njbtkdx-ZRU8FKYSWoEHRJetidy0zA
- title: ''
  type: Blog
  url: https://nifi.apache.org/blog/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
created: '2026-03-16'
description: Apache NiFi is a dataflow management system designed to automate the flow of data between systems. It provides a web-based user interface for designing, controlling, and monitoring data flows with real-time operational control, data provenance tracking, and support for hundreds of processors. NiFi Version 2 is the current major version with enhanced security and performance.
features:
- description: Browser-based drag-and-drop interface for designing, controlling, and monitoring data flows without coding.
  name: Visual Dataflow Designer
- description: Complete lineage tracking of every piece of data that flows through the system from ingestion to destination.
  name: Data Provenance Tracking
- description: Extensive library of processors for data ingestion, transformation, routing, and delivery to diverse systems and cloud platforms.
  name: Hundreds of Built-in Processors
- description: Loss-tolerant and guaranteed delivery options with configurable prioritization and backpressure control.
  name: Guaranteed Delivery
- description: Comprehensive JWT-authenticated REST API for programmatic management of all NiFi resources and operations.
  name: REST API
- description: Version control for data flows via NiFi Registry, enabling flow promotion across development, test, and production environments.
  name: Flow Versioning
- description: Fine-grained multi-tenant authorization with HTTPS, TLS, and SSH support for secure deployments.
  name: Multi-Tenant Security
- description: Zero-master cluster architecture for high-availability and load-balanced dataflow execution.
  name: Clustering
- description: Externalize configuration using parameter contexts that can be applied across multiple processors and process groups.
  name: Parameter Contexts
- description: Lightweight MiNiFi agents for edge data collection at IoT endpoints, managed centrally from NiFi.
  name: MiNiFi Edge Agents
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native ConsumeKafka and PublishKafka processors for streaming data between NiFi and Kafka topics.
  name: Apache Kafka
- description: PutS3Object and FetchS3Object processors for reading and writing data to AWS S3 buckets.
  name: Amazon S3
- description: PutAzureBlobStorage and FetchAzureBlobStorage processors for Azure cloud storage integration.
  name: Azure Blob Storage
- description: Native GCS processors for reading and writing Google Cloud Storage objects.
  name: Google Cloud Storage
- description: PutMongo and GetMongo processors for reading and writing documents to MongoDB collections.
  name: MongoDB
- description: PutElasticsearchRecord and FetchElasticsearch processors for indexing and querying Elasticsearch.
  name: Elasticsearch
- description: Native Salesforce processors for querying and publishing data to Salesforce CRM.
  name: Salesforce
- description: ConsumeMQTT and PublishMQTT processors for IoT messaging protocol support.
  name: Apache MQTT
layout: provider
modified: '2026-04-19'
name: Apache NiFi
skills: []
slug: apache-nifi
solutions: []
tags:
- Data Integration
- Dataflow
- ETL
- IoT
- Streaming
- Data Pipeline
url: https://raw.githubusercontent.com/api-evangelist/apache-nifi/refs/heads/main/apis.yml
use_cases:
- description: Build pipelines ingesting data from files, databases, message queues, cloud storage, and APIs into data lakes and warehouses.
  name: Data Ingestion Pipelines
- description: Collect and route security telemetry, logs, and threat intelligence feeds for SIEM and analytics platforms.
  name: Cybersecurity Data Collection
- description: Deploy MiNiFi agents at IoT edge locations to collect, filter, and forward sensor data to central NiFi clusters.
  name: IoT Edge Data Collection
- description: Build event streaming pipelines consuming from Kafka, Kinesis, and other message brokers for real-time data processing.
  name: Real-Time Event Streaming
- description: Build data preparation and vector database ingestion pipelines for generative AI and RAG applications.
  name: Generative AI Data Pipelines
- description: Move and transform data between AWS, Azure, and GCP services with built-in cloud processor libraries.
  name: Cloud Data Integration
---
