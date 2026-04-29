---
api_count: 6
apis:
- description: RESTful API for managing Oracle GoldenGate Microservices Architecture, including deployment configuration, process management, and monitoring.
  name: Oracle GoldenGate REST API
  slug: ''
- description: API for managing Oracle GoldenGate for Big Data deployments, allowing integration with Hadoop, Kafka, and other big data targets.
  name: Oracle GoldenGate for Big Data REST API
  slug: ''
- description: API for Oracle GoldenGate Veridata to verify and compare data between source and target systems.
  name: Oracle GoldenGate Veridata REST API
  slug: ''
- description: Oracle Cloud Infrastructure API for managing GoldenGate deployments in OCI.
  name: Oracle GoldenGate Cloud Service API
  slug: ''
- description: REST API for managing Oracle GoldenGate Stream Analytics pipelines, enabling real-time event stream processing, monitoring, and dashboard creation.
  name: Oracle GoldenGate Stream Analytics REST API
  slug: ''
- description: REST API for distributing and managing Oracle GoldenGate data streams, enabling real-time data distribution to downstream consumers.
  name: Oracle GoldenGate Data Streams REST API
  slug: ''
capabilities:
- description: Unified workflow for managing Oracle GoldenGate cloud deployments in OCI. Combines the OCI Cloud Service API with Stream Analytics for cloud platform administrators managing deployment lifecycle, conn
  name: Oracle GoldenGate Cloud Management
  slug: cloud-management
- description: Unified workflow for managing real-time data replication across on-premises and cloud environments. Combines the core GoldenGate REST API, Big Data API, and Data Streams API for data integration engin
  name: Oracle GoldenGate Data Replication
  slug: data-replication
- description: Unified workflow for verifying data consistency between source and target databases. Combines Veridata for data comparison and repair with core GoldenGate monitoring for data quality engineers and DBA
  name: Oracle GoldenGate Data Verification
  slug: data-verification
common:
- title: ''
  type: Portal
  url: https://www.oracle.com/integration/goldengate/
- title: ''
  type: Blog
  url: https://blogs.oracle.com/dataintegration/
- title: ''
  type: Pricing
  url: https://www.oracle.com/integration/goldengate/pricing/
- title: ''
  type: GettingStarted
  url: https://docs.oracle.com/en/middleware/goldengate/core/21.3/index.html
- title: ''
  type: TermsOfService
  url: https://www.oracle.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.oracle.com/legal/privacy/
- title: ''
  type: Documentation
  url: https://docs.oracle.com/en/cloud/paas/goldengate-service/docs.html
- title: ''
  type: SignUp
  url: https://www.oracle.com/cloud/free/
- title: ''
  type: Login
  url: https://cloud.oracle.com/
- title: ''
  type: StatusPage
  url: https://ocistatus.oraclecloud.com/
- title: ''
  type: Support
  url: https://support.oracle.com
- title: ''
  type: KnowledgeCenter
  url: https://www.oracle.com/integration/goldengate/knowledge-hub/
- title: ''
  type: GitHubOrganization
  url: https://github.com/oracle
- title: ''
  type: GitHubRepository
  url: https://github.com/oracle/docker-images/tree/main/OracleGoldenGate
- title: ''
  type: Training
  url: https://education.oracle.com/data-integration/goldengate/product_148
- title: ''
  type: Tutorials
  url: https://docs.oracle.com/en/cloud/paas/goldengate-service/tutorials.html
- title: ''
  type: ReleaseNotes
  url: https://docs.oracle.com/en/database/goldengate/core/26/release-notes/
- title: ''
  type: JSONSchema
  url: json-schema/oracle-goldengate-deployment-schema.json
- title: ''
  type: JSONLD
  url: json-ld/oracle-goldengate-context.jsonld
created: '2024-01-15'
description: Oracle GoldenGate enables real-time data integration and replication in heterogeneous IT environments. These APIs provide programmatic access to manage and monitor GoldenGate deployments, processes, and configurations.
features:
- Real-time data replication across heterogeneous databases
- Change data capture (CDC) with minimal impact on source systems
- Zero-downtime migration and database upgrades
- Multi-cloud and hybrid cloud data integration
- Bidirectional replication for active-active architectures
- Stream analytics for real-time event processing
- Data verification and repair with Veridata
- Big data target support including Kafka, HDFS, and MongoDB
image: /assets/icons/oracle-goldengate.png
integrations:
- Oracle Database
- MySQL
- PostgreSQL
- SQL Server
- MongoDB
- Apache Kafka
- Apache Hadoop / HDFS
- Elasticsearch
- Google BigQuery
- Amazon Kinesis
- Snowflake
- Oracle Cloud Infrastructure
jsonld:
- class_count: 0
  name: Oracle Goldengate Big Data Rest Context
  property_count: 0
  slug: oracle-goldengate-big-data-rest-context
- class_count: 0
  name: Oracle Goldengate Cloud Service Context
  property_count: 0
  slug: oracle-goldengate-cloud-service-context
- class_count: 0
  name: Oracle Goldengate Context
  property_count: 16
  slug: oracle-goldengate-context
- class_count: 0
  name: Oracle Goldengate Data Streams Rest Context
  property_count: 0
  slug: oracle-goldengate-data-streams-rest-context
- class_count: 0
  name: Oracle Goldengate Rest Context
  property_count: 0
  slug: oracle-goldengate-rest-context
- class_count: 0
  name: Oracle Goldengate Stream Analytics Rest Context
  property_count: 0
  slug: oracle-goldengate-stream-analytics-rest-context
- class_count: 0
  name: Oracle Goldengate Veridata Rest Context
  property_count: 0
  slug: oracle-goldengate-veridata-rest-context
layout: provider
modified: '2026-04-18'
name: Oracle GoldenGate
rules:
- name: Oracle GoldenGate API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: oracle-goldengate-spectral-rules
skills: []
slug: oracle-goldengate
solutions: []
source_yaml: "aid: oracle-goldengate\nname: Oracle GoldenGate\ndescription: >-\n  Oracle GoldenGate enables real-time data integration and replication in\n  heterogeneous IT environments. These APIs provide programmatic access to\n  manage and monitor GoldenGate deployments, processes, and configurations.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-goldengate/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - name: Oracle GoldenGate REST API\n    description: >-\n      RESTful API for managing Oracle GoldenGate Microservices Architecture, including\n      deployment configuration, process management, and monitoring.\n    image: https://www.oracle.com/a/ocom/img/cb71-oracle-goldengate.jpg\n    humanURL: https://docs.oracle.com/en/middleware/goldengate/core/\n    baseURL:\
  \ https://<goldengate-host>:<port>/services/v2\n    tags:\n      - CDC\n      - Data Replication\n      - ETL\n      - Microservices\n      - Real-Time Data Integration\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/goldengate/core/21.3/oggra/index.html\n      - type: OpenAPI\n        url: openapi/oracle-goldengate-rest-api-openapi.yml\n      - type: Authentication\n        url: https://docs.oracle.com/en/middleware/goldengate/core/21.3/oggra/authentication.html\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/goldengate/core/26/oggra/index.html\n      - type: Authentication\n        url: https://docs.oracle.com/en/database/goldengate/core/26/oggra/authenticate.html\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/database/goldengate/core/26/\n      - type: Tutorials\n        url: https://docs.oracle.com/en/database/goldengate/core/26/tutorials.html\n      - type: ChangeLog\n        url:\
  \ https://docs.oracle.com/en/database/goldengate/core/26/release-notes/\n    contact:\n      - type: Support\n        url: https://support.oracle.com\n  - name: Oracle GoldenGate for Big Data REST API\n    description: >-\n      API for managing Oracle GoldenGate for Big Data deployments, allowing integration\n      with Hadoop, Kafka, and other big data targets.\n    image: https://www.oracle.com/a/ocom/img/cb71-oracle-goldengate.jpg\n    humanURL: https://docs.oracle.com/en/middleware/goldengate/big-data/\n    baseURL: https://<goldengate-host>:<port>/services/v2\n    tags:\n      - Big Data\n      - Hadoop\n      - Kafka\n      - NoSQL\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/goldengate/big-data/21.3/gadbd/index.html\n      - type: OpenAPI\n        url: openapi/oracle-goldengate-big-data-rest-api-openapi.yml\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/middleware/goldengate/big-data/21.3/gadbd/getting-started.html\n\
  \    contact:\n      - type: Support\n        url: https://support.oracle.com\n  - name: Oracle GoldenGate Veridata REST API\n    description: >-\n      API for Oracle GoldenGate Veridata to verify and compare data between source\n      and target systems.\n    image: https://www.oracle.com/a/ocom/img/cb71-oracle-goldengate.jpg\n    humanURL: https://docs.oracle.com/en/middleware/goldengate/veridata/\n    baseURL: https://<veridata-host>:<port>/veridata/v1\n    tags:\n      - Comparison\n      - Data Quality\n      - Data Validation\n      - Data Verification\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/goldengate/veridata/12.2.1.4/gvdug/index.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/middleware/goldengate/veridata/12.2.1.4/gvdra/index.html\n      - type: OpenAPI\n        url: openapi/oracle-goldengate-veridata-rest-api-openapi.yml\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/goldengate/veridata/26/\n\
  \      - type: ChangeLog\n        url: https://docs.oracle.com/en/database/goldengate/veridata/26/gvdrn/index.html\n    contact:\n      - type: Support\n        url: https://support.oracle.com\n  - name: Oracle GoldenGate Cloud Service API\n    description: >-\n      Oracle Cloud Infrastructure API for managing GoldenGate deployments in OCI.\n    image: https://www.oracle.com/a/ocom/img/cb71-oracle-goldengate.jpg\n    humanURL: https://docs.oracle.com/en-us/iaas/goldengate/\n    baseURL: https://goldengate.{region}.oci.oraclecloud.com\n    tags:\n      - Cloud\n      - Cloud Integration\n      - Database Migration\n      - OCI\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en-us/iaas/api/#/en/goldengate/latest/\n      - type: OpenAPI\n        url: openapi/oracle-goldengate-cloud-service-api-openapi.yml\n      - type: SDK\n        url: https://docs.oracle.com/en-us/iaas/Content/API/Concepts/sdks.htm\n      - type: CLI\n        url: https://docs.oracle.com/en-us/iaas/Content/API/Concepts/cliconcepts.htm\n\
  \      - type: GettingStarted\n        url: https://docs.oracle.com/en/cloud/paas/goldengate-service/index.html\n      - type: Authentication\n        url: https://docs.oracle.com/en-us/iaas/Content/API/Concepts/apisigningkey.htm\n      - type: Tutorials\n        url: https://docs.oracle.com/en/cloud/paas/goldengate-service/tutorials.html\n      - type: ChangeLog\n        url: https://docs.oracle.com/en-us/iaas/releasenotes/services/goldengate/\n      - type: SDK\n        url: https://docs.oracle.com/en-us/iaas/tools/python/latest/api/golden_gate.html\n      - type: APIReference\n        url: https://docs.oracle.com/en-us/iaas/goldengate/doc/using-rest-api.html\n    contact:\n      - type: Support\n        url: https://support.oracle.com\n  - name: Oracle GoldenGate Stream Analytics REST API\n    description: >-\n      REST API for managing Oracle GoldenGate Stream Analytics pipelines, enabling\n      real-time event stream processing, monitoring, and dashboard creation.\n    image: https://www.oracle.com/a/ocom/img/cb71-oracle-goldengate.jpg\n\
  \    humanURL: https://docs.oracle.com/en/database/goldengate/stream-analytics/index.html\n    baseURL: https://<ggsa-host>:<port>/osa\n    tags:\n      - Dashboards\n      - Event Processing\n      - Real-Time Analytics\n      - Spark\n      - Stream Analytics\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/goldengate/stream-analytics/26/\n      - type: APIReference\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/osa/19.1/ggsa-rest-api/quick-start.html\n      - type: OpenAPI\n        url: openapi/oracle-goldengate-stream-analytics-rest-api-openapi.yml\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/database/goldengate/stream-analytics/26/\n      - type: ChangeLog\n        url: https://docs.oracle.com/en/database/goldengate/stream-analytics/26/release-notes/release-notes-goldengate-stream-analytics.pdf\n    contact:\n      - type: Support\n        url: https://support.oracle.com\n  - name: Oracle\
  \ GoldenGate Data Streams REST API\n    description: >-\n      REST API for distributing and managing Oracle GoldenGate data streams, enabling\n      real-time data distribution to downstream consumers.\n    image: https://www.oracle.com/a/ocom/img/cb71-oracle-goldengate.jpg\n    humanURL: https://docs.oracle.com/en/database/goldengate/core/26/coredoc/distribute-datastream-rest-api.html\n    baseURL: https://<goldengate-host>:<port>/services/v2\n    tags:\n      - Data Distribution\n      - Data Streams\n      - Real-Time\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/goldengate/core/26/coredoc/distribute-datastream-rest-api.html\n      - type: OpenAPI\n        url: openapi/oracle-goldengate-data-streams-rest-api-openapi.yml\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/database/goldengate/core/26/\n    contact:\n      - type: Support\n        url: https://support.oracle.com\ncommon:\n  - type:\
  \ Portal\n    url: https://www.oracle.com/integration/goldengate/\n  - type: Blog\n    url: https://blogs.oracle.com/dataintegration/\n  - type: Pricing\n    url: https://www.oracle.com/integration/goldengate/pricing/\n  - type: GettingStarted\n    url: https://docs.oracle.com/en/middleware/goldengate/core/21.3/index.html\n  - type: TermsOfService\n    url: https://www.oracle.com/legal/terms.html\n  - type: PrivacyPolicy\n    url: https://www.oracle.com/legal/privacy/\n  - type: Documentation\n    url: https://docs.oracle.com/en/cloud/paas/goldengate-service/docs.html\n  - type: SignUp\n    url: https://www.oracle.com/cloud/free/\n  - type: Login\n    url: https://cloud.oracle.com/\n  - type: StatusPage\n    url: https://ocistatus.oraclecloud.com/\n  - type: Support\n    url: https://support.oracle.com\n  - type: KnowledgeCenter\n    url: https://www.oracle.com/integration/goldengate/knowledge-hub/\n  - type: GitHubOrganization\n    url: https://github.com/oracle\n  - type: GitHubRepository\n\
  \    url: https://github.com/oracle/docker-images/tree/main/OracleGoldenGate\n  - type: Features\n    url: https://www.oracle.com/integration/goldengate/features/\n    data:\n      - Real-time data replication across heterogeneous databases\n      - Change data capture (CDC) with minimal impact on source systems\n      - Zero-downtime migration and database upgrades\n      - Multi-cloud and hybrid cloud data integration\n      - Bidirectional replication for active-active architectures\n      - Stream analytics for real-time event processing\n      - Data verification and repair with Veridata\n      - Big data target support including Kafka, HDFS, and MongoDB\n  - type: UseCases\n    url: https://www.oracle.com/integration/goldengate/\n    data:\n      - Real-time data warehouse loading and synchronization\n      - Database migration with zero downtime\n      - Active-active database replication for high availability\n      - Streaming data to big data platforms (Kafka, Hadoop, Elasticsearch)\n\
  \      - Cloud migration from on-premises Oracle databases to OCI\n      - Data verification and compliance auditing\n      - Real-time analytics pipeline construction\n  - type: Integrations\n    url: https://www.oracle.com/integration/goldengate/\n    data:\n      - Oracle Database\n      - MySQL\n      - PostgreSQL\n      - SQL Server\n      - MongoDB\n      - Apache Kafka\n      - Apache Hadoop / HDFS\n      - Elasticsearch\n      - Google BigQuery\n      - Amazon Kinesis\n      - Snowflake\n      - Oracle Cloud Infrastructure\n  - type: Training\n    url: https://education.oracle.com/data-integration/goldengate/product_148\n  - type: Tutorials\n    url: https://docs.oracle.com/en/cloud/paas/goldengate-service/tutorials.html\n  - type: ReleaseNotes\n    url: https://docs.oracle.com/en/database/goldengate/core/26/release-notes/\n  - type: JSONSchema\n    url: json-schema/oracle-goldengate-deployment-schema.json\n  - type: JSONLD\n    url: json-ld/oracle-goldengate-context.jsonld\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - CDC\n  - Data Integration\n  - Data Synchronization\n  - Database\n  - Enterprise\n  - Real-Time Replication\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-goldengate/refs/heads/main/apis.yml
tags:
- CDC
- Data Integration
- Data Synchronization
- Database
- Enterprise
- Real-Time Replication
url: https://raw.githubusercontent.com/api-evangelist/oracle-goldengate/refs/heads/main/apis.yml
use_cases:
- Real-time data warehouse loading and synchronization
- Database migration with zero downtime
- Active-active database replication for high availability
- Streaming data to big data platforms (Kafka, Hadoop, Elasticsearch)
- Cloud migration from on-premises Oracle databases to OCI
- Data verification and compliance auditing
- Real-time analytics pipeline construction
---
