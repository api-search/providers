---
api_count: 6
apis:
- description: Cassandra Query Language (CQL) is the primary interface to Apache Cassandra. Clients speak the binary CQL native protocol over TCP (default port 9042). Official drivers are maintained for Java, Python
  name: Apache Cassandra CQL Native Protocol
  slug: cassandra-cql-native-protocol
- description: HTTP/JSON REST API for Cassandra provided by the Stargate data gateway. Enables CRUD operations and SQL-like query via REST without the CQL driver.
  name: Cassandra REST API (Stargate)
  slug: cassandra-rest-api-stargate
- description: GraphQL endpoint for Cassandra, enabling flexible, typed queries and mutations against Cassandra tables through the Stargate gateway.
  name: Cassandra GraphQL API (Stargate)
  slug: cassandra-graphql-api-stargate
- description: Schemaless Document API that stores JSON documents in Cassandra, offering a MongoDB-like developer experience backed by Cassandra.
  name: Cassandra Document API (Stargate)
  slug: cassandra-document-api-stargate
- description: High-performance gRPC API for Cassandra through Stargate, designed for low-latency service-to-service communication.
  name: Cassandra gRPC API (Stargate)
  slug: cassandra-grpc-api-stargate
- description: Java Management Extensions (JMX) interface for monitoring and administering Cassandra nodes, including metrics, compaction, repairs, and configuration.
  name: Cassandra JMX Management Interface
  slug: cassandra-jmx-metrics
common:
- title: ''
  type: Website
  url: https://cassandra.apache.org/
- title: ''
  type: Documentation
  url: https://cassandra.apache.org/doc/latest/
- title: ''
  type: GettingStarted
  url: https://cassandra.apache.org/doc/latest/cassandra/getting_started/
- title: ''
  type: Download
  url: https://cassandra.apache.org/download/
- title: ''
  type: SourceCode
  url: https://github.com/apache/cassandra
- title: ''
  type: GitHub
  url: https://github.com/apache/cassandra
- title: ''
  type: IssueTracker
  url: https://issues.apache.org/jira/projects/CASSANDRA
- title: ''
  type: Blog
  url: https://cassandra.apache.org/blog/
- title: ''
  type: Community
  url: https://cassandra.apache.org/community/
- title: ''
  type: MailingList
  url: https://cassandra.apache.org/community/#discussions
- title: ''
  type: Slack
  url: https://cassandra.apache.org/community/#slack
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/cassandra
- title: ''
  type: X
  url: https://twitter.com/cassandra
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/apache-cassandra/
- title: ''
  type: YouTube
  url: https://www.youtube.com/@PlanetCassandra
- title: ''
  type: DockerHub
  url: https://hub.docker.com/_/cassandra
- title: ''
  type: PackageRegistry
  url: https://central.sonatype.com/artifact/org.apache.cassandra/cassandra-all
- title: ''
  type: License
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Governance
  url: https://www.apache.org/foundation/governance/
- title: ''
  type: SecurityPolicy
  url: https://cassandra.apache.org/_/security.html
- title: ''
  type: PrivacyPolicy
  url: https://www.apache.org/privacy/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/foundation/license-faq.html
- title: ''
  type: Ecosystem
  url: https://cassandra.apache.org/_/ecosystem.html
- title: ''
  type: ThirdParty
  url: https://cassandra.apache.org/_/ecosystem.html
created: '2024-01-01'
description: Apache Cassandra is a highly scalable, distributed open-source NoSQL database designed to handle massive amounts of data across many commodity servers, providing high availability with no single point of failure. It is governed by the Apache Software Foundation (ASF) under the Apache License 2.0 and is used in production by Netflix, Apple, Bloomberg, Backblaze, and many others. Cassandra exposes its CQL native protocol for clients and a family of HTTP, REST, GraphQL, Document, and gRPC APIs via the Stargate data gateway.
features:
- name: Distributed
- name: Masterless
- name: Linear Scalability
- name: Multi-Datacenter Replication
- name: High Availability
- name: Fault Tolerance
- name: Tunable Consistency
- name: CQL Query Language
- name: Secondary Indexes
- name: Materialized Views
- name: User Defined Types
- name: User Defined Functions
- name: Vector Search
- name: Time Series Storage
- name: Cross-Region Replication
- name: Role Based Access Control
- name: TLS/SSL Encryption
- name: At-Rest Encryption
- name: Snapshot Backups
- name: Incremental Repairs
- name: Apache License 2.0
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Apache Cassandra
skills: []
slug: cassandra
solutions: []
source_filename: apis.yml
source_yaml: "aid: cassandra\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cassandra/refs/heads/main/apis.yml\nname: Apache Cassandra\ntags:\n  - Apache\n  - Big Data\n  - Database\n  - Distributed\n  - NoSQL\n  - Open Source\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-01-01'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  Apache Cassandra is a highly scalable, distributed open-source NoSQL database\n  designed to handle massive amounts of data across many commodity servers,\n  providing high availability with no single point of failure. It is governed\n  by the Apache Software Foundation (ASF) under the Apache License 2.0 and is\n  used in production by Netflix, Apple, Bloomberg, Backblaze, and many others.\n  Cassandra exposes its CQL native protocol for clients and a family of HTTP,\n  REST, GraphQL, Document, and gRPC APIs via the Stargate data gateway.\napis:\n  - aid:\
  \ cassandra:cassandra-cql-native-protocol\n    name: Apache Cassandra CQL Native Protocol\n    tags:\n      - CQL\n      - Database\n      - Native Protocol\n      - Query\n    humanURL: https://cassandra.apache.org/doc/latest/cassandra/cql/\n    properties:\n      - url: https://cassandra.apache.org/doc/latest/cassandra/cql/\n        type: Documentation\n      - url: https://github.com/apache/cassandra/blob/trunk/doc/native_protocol_v5.spec\n        type: Specification\n      - url: https://cassandra.apache.org/doc/latest/cassandra/cql/ddl.html\n        type: Reference\n    description: >-\n      Cassandra Query Language (CQL) is the primary interface to Apache\n      Cassandra. Clients speak the binary CQL native protocol over TCP\n      (default port 9042). Official drivers are maintained for Java, Python,\n      Go, C/C++, C#, Node.js, Ruby, and Rust.\n  - aid: cassandra:cassandra-rest-api-stargate\n    name: Cassandra REST API (Stargate)\n    tags:\n      - Database\n      - REST\n\
  \      - Stargate\n    humanURL: https://stargate.io/docs/latest/develop/api-rest/\n    properties:\n      - url: https://stargate.io/docs/latest/develop/api-rest/\n        type: Documentation\n      - url: https://stargate.io/docs/latest/develop/api-rest/swagger.html\n        type: Swagger\n      - url: https://github.com/stargate/stargate\n        type: SourceCode\n    description: >-\n      HTTP/JSON REST API for Cassandra provided by the Stargate data gateway.\n      Enables CRUD operations and SQL-like query via REST without the CQL\n      driver.\n  - aid: cassandra:cassandra-graphql-api-stargate\n    name: Cassandra GraphQL API (Stargate)\n    tags:\n      - Database\n      - GraphQL\n      - Stargate\n    humanURL: https://stargate.io/docs/latest/develop/api-graphql/\n    properties:\n      - url: https://stargate.io/docs/latest/develop/api-graphql/\n        type: Documentation\n      - url: https://stargate.io/docs/latest/develop/api-graphql/graphql-using.html\n        type: Reference\n\
  \    description: >-\n      GraphQL endpoint for Cassandra, enabling flexible, typed queries and\n      mutations against Cassandra tables through the Stargate gateway.\n  - aid: cassandra:cassandra-document-api-stargate\n    name: Cassandra Document API (Stargate)\n    tags:\n      - Database\n      - Document\n      - JSON\n      - Stargate\n    humanURL: https://stargate.io/docs/latest/develop/api-doc/\n    properties:\n      - url: https://stargate.io/docs/latest/develop/api-doc/\n        type: Documentation\n      - url: https://stargate.io/docs/latest/develop/api-doc/doc-using.html\n        type: Reference\n    description: >-\n      Schemaless Document API that stores JSON documents in Cassandra,\n      offering a MongoDB-like developer experience backed by Cassandra.\n  - aid: cassandra:cassandra-grpc-api-stargate\n    name: Cassandra gRPC API (Stargate)\n    tags:\n      - Database\n      - gRPC\n      - Stargate\n    humanURL: https://stargate.io/docs/latest/develop/api-grpc/\n\
  \    properties:\n      - url: https://stargate.io/docs/latest/develop/api-grpc/\n        type: Documentation\n      - url: https://github.com/stargate/stargate/tree/main/grpc/proto\n        type: Protocol\n    description: >-\n      High-performance gRPC API for Cassandra through Stargate, designed for\n      low-latency service-to-service communication.\n  - aid: cassandra:cassandra-jmx-metrics\n    name: Cassandra JMX Management Interface\n    tags:\n      - JMX\n      - Management\n      - Metrics\n      - Monitoring\n    humanURL: https://cassandra.apache.org/doc/latest/cassandra/operating/metrics.html\n    properties:\n      - url: https://cassandra.apache.org/doc/latest/cassandra/operating/metrics.html\n        type: Documentation\n      - url: https://cassandra.apache.org/doc/latest/cassandra/operating/\n        type: OperationsGuide\n    description: >-\n      Java Management Extensions (JMX) interface for monitoring and\n      administering Cassandra nodes, including metrics,\
  \ compaction, repairs,\n      and configuration.\ncommon:\n  - type: Website\n    url: https://cassandra.apache.org/\n  - type: Documentation\n    url: https://cassandra.apache.org/doc/latest/\n  - type: GettingStarted\n    url: https://cassandra.apache.org/doc/latest/cassandra/getting_started/\n  - type: Download\n    url: https://cassandra.apache.org/download/\n  - type: SourceCode\n    url: https://github.com/apache/cassandra\n  - type: GitHub\n    url: https://github.com/apache/cassandra\n  - type: IssueTracker\n    url: https://issues.apache.org/jira/projects/CASSANDRA\n  - type: Blog\n    url: https://cassandra.apache.org/blog/\n  - type: Community\n    url: https://cassandra.apache.org/community/\n  - type: MailingList\n    url: https://cassandra.apache.org/community/#discussions\n  - type: Slack\n    url: https://cassandra.apache.org/community/#slack\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/cassandra\n  - type: X\n    url: https://twitter.com/cassandra\n\
  \  - type: LinkedIn\n    url: https://www.linkedin.com/company/apache-cassandra/\n  - type: YouTube\n    url: https://www.youtube.com/@PlanetCassandra\n  - type: DockerHub\n    url: https://hub.docker.com/_/cassandra\n  - type: PackageRegistry\n    url: https://central.sonatype.com/artifact/org.apache.cassandra/cassandra-all\n  - type: License\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Governance\n    url: https://www.apache.org/foundation/governance/\n  - type: SecurityPolicy\n    url: https://cassandra.apache.org/_/security.html\n  - type: PrivacyPolicy\n    url: https://www.apache.org/privacy/\n  - type: TermsOfService\n    url: https://www.apache.org/foundation/license-faq.html\n  - type: Ecosystem\n    url: https://cassandra.apache.org/_/ecosystem.html\n  - type: ThirdParty\n    url: https://cassandra.apache.org/_/ecosystem.html\n  - name: Features\n    type: Features\n    data:\n      - name: Distributed\n      - name: Masterless\n      - name: Linear Scalability\n\
  \      - name: Multi-Datacenter Replication\n      - name: High Availability\n      - name: Fault Tolerance\n      - name: Tunable Consistency\n      - name: CQL Query Language\n      - name: Secondary Indexes\n      - name: Materialized Views\n      - name: User Defined Types\n      - name: User Defined Functions\n      - name: Vector Search\n      - name: Time Series Storage\n      - name: Cross-Region Replication\n      - name: Role Based Access Control\n      - name: TLS/SSL Encryption\n      - name: At-Rest Encryption\n      - name: Snapshot Backups\n      - name: Incremental Repairs\n      - name: Apache License 2.0\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Event Logging\n      - name: IoT Telemetry\n      - name: Time Series Data\n      - name: Product Catalogs\n      - name: Messaging Platforms\n      - name: Fraud Detection\n      - name: Recommendation Engines\n      - name: Activity Feeds\n      - name: Audit Logs\n      - name: Real-Time Analytics\n\
  \      - name: Mobile Application Backends\n      - name: Vector Similarity Search\nmaintainers:\n  - FN: Apache Cassandra Community\n    email: dev@cassandra.apache.org\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cassandra/refs/heads/main/apis.yml
tags:
- Apache
- Big Data
- Database
- Distributed
- NoSQL
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/cassandra/refs/heads/main/apis.yml
use_cases:
- name: Event Logging
- name: IoT Telemetry
- name: Time Series Data
- name: Product Catalogs
- name: Messaging Platforms
- name: Fraud Detection
- name: Recommendation Engines
- name: Activity Feeds
- name: Audit Logs
- name: Real-Time Analytics
- name: Mobile Application Backends
- name: Vector Similarity Search
---
