---
api_count: 5
apis:
- description: PostgreSQL provides full ACID compliance through its transaction management system including BEGIN, COMMIT, ROLLBACK, SAVEPOINT, and isolation level controls (READ COMMITTED, REPEATABLE READ, SERIALIZ
  name: PostgreSQL Transaction API
  slug: ''
- description: CockroachDB is a distributed SQL database providing serializable ACID transactions across multiple nodes and regions. It uses the Raft consensus algorithm and supports the PostgreSQL wire protocol. Co
  name: CockroachDB Distributed SQL API
  slug: ''
- description: Google Spanner is a globally distributed, externally consistent database providing ACID transactions at global scale using TrueTime clock synchronization (GPS receivers and atomic clocks). The Cloud S
  name: Google Spanner API
  slug: ''
- description: Amazon Aurora provides ACID-compliant transactions for both MySQL-compatible and PostgreSQL-compatible editions. Aurora's distributed storage layer provides durability across 3 availability zones with
  name: Amazon Aurora Transactions API
  slug: ''
- description: Atomikos provides ACID transaction management middleware for distributed microservices, supporting XA transactions across REST services using the Try-Confirm/Cancel (TCC) pattern. It enables ACID guar
  name: Atomikos Transaction API
  slug: ''
common:
- title: ACID Wikipedia Reference
  type: Website
  url: https://en.wikipedia.org/wiki/ACID
- title: CockroachDB Open Source Repository
  type: GitHubRepository
  url: https://github.com/cockroachdb/cockroach
- title: ACID JSON-LD Context
  type: JSON-LD
  url: https://raw.githubusercontent.com/api-evangelist/acid/refs/heads/main/json-ld/acid-context.jsonld
- title: ACID Vocabulary
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/acid/refs/heads/main/vocabulary/acid-vocabulary.yaml
created: '2025-01-01'
description: ACID (Atomicity, Consistency, Isolation, Durability) is a set of properties that guarantee database transactions are processed reliably even in the face of errors, power failures, or system crashes. These four properties ensure that data remains accurate and consistent, making ACID compliance a fundamental requirement for relational databases, distributed systems, and financial APIs.
features:
- description: 'Transactions are all-or-nothing: either all operations in a transaction succeed and are committed, or none are applied and the database is rolled back to its prior state.'
  name: Atomicity
- description: A transaction brings the database from one valid, consistent state to another, enforcing all defined constraints, triggers, and cascades. No transaction can leave data in an invalid state.
  name: Consistency
- description: Concurrent transactions execute as if they were serialized, preventing interference. Isolation levels (READ COMMITTED, REPEATABLE READ, SERIALIZABLE) control the degree of visibility between concurrent transactions.
  name: Isolation
- description: Once a transaction is committed, it remains committed even in the event of system crashes, power failures, or other errors, typically achieved through write-ahead logging (WAL) and replication.
  name: Durability
- description: Modern distributed databases extend ACID guarantees across multiple nodes, regions, and data centers using consensus algorithms (Raft, Paxos) and synchronized clocks (TrueTime).
  name: Distributed ACID
- description: Design patterns for ACID-like guarantees in REST APIs include Two-Phase Commit (2PC), Try-Confirm/Cancel (TCC), and Saga patterns for managing distributed transactions across microservices.
  name: REST API Transaction Patterns
image: /assets/icons/acid.png
integrations:
- description: The most widely deployed open-source RDBMS with full ACID compliance via MVCC and configurable transaction isolation levels.
  name: PostgreSQL
- description: Popular open-source databases providing ACID compliance through the InnoDB storage engine with row-level locking and MVCC.
  name: MySQL / MariaDB
- description: MongoDB added multi-document ACID transactions in version 4.0, extending its document model with ACID guarantees across documents and collections.
  name: MongoDB Multi-Document Transactions
- description: Kafka's transactional API (since 0.11) enables exactly-once semantics with atomic writes to multiple partitions, providing ACID-like guarantees for stream processing pipelines.
  name: Apache Kafka Transactions
- description: The Saga pattern decomposes long-running transactions into a series of local transactions with compensating actions for distributed consistency without 2PC overhead.
  name: Saga Pattern / Orchestration
jsonld:
- class_count: 2
  name: Acid Context
  property_count: 22
  slug: acid-context
layout: provider
modified: '2026-04-19'
name: ACID
skills: []
slug: acid
solutions: []
source_yaml: "aid: acid\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/acid/refs/heads/main/apis.yml\nname: ACID\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - ACID\n  - Database\n  - Transactions\n  - Atomicity\n  - Consistency\n  - Isolation\n  - Durability\n  - Distributed Systems\ndescription: >-\n  ACID (Atomicity, Consistency, Isolation, Durability) is a set of properties\n  that guarantee database transactions are processed reliably even in the face of\n  errors, power failures, or system crashes. These four properties ensure that\n  data remains accurate and consistent, making ACID compliance a fundamental\n  requirement for relational databases, distributed systems, and financial APIs.\ncreated: '2025-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - name: PostgreSQL Transaction API\n    description: >-\n      PostgreSQL provides full ACID compliance through its transaction management\n\
  \      system including BEGIN, COMMIT, ROLLBACK, SAVEPOINT, and isolation level\n      controls (READ COMMITTED, REPEATABLE READ, SERIALIZABLE). PostgreSQL uses\n      Multi-Version Concurrency Control (MVCC) to provide high concurrency while\n      maintaining strong data consistency guarantees.\n    humanURL: https://www.postgresql.org/docs/current/transaction-iso.html\n    baseURL: https://www.postgresql.org/\n    tags:\n      - PostgreSQL\n      - RDBMS\n      - MVCC\n      - ACID\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://www.postgresql.org/docs/current/transaction-iso.html\n      - type: Documentation\n        url: https://www.postgresql.org/docs/current/sql-begin.html\n        title: PostgreSQL BEGIN Transaction\n      - type: GitHubRepository\n        url: https://github.com/postgres/postgres\n  - name: CockroachDB Distributed SQL API\n    description: >-\n      CockroachDB is a distributed SQL database providing serializable ACID\n      transactions\
  \ across multiple nodes and regions. It uses the Raft consensus\n      algorithm and supports the PostgreSQL wire protocol. CockroachDB offers\n      REST and SQL APIs for managing distributed transactions while maintaining\n      global consistency without a central coordinator.\n    humanURL: https://www.cockroachlabs.com/docs/stable/\n    baseURL: https://cockroachlabs.cloud/\n    tags:\n      - CockroachDB\n      - Distributed SQL\n      - ACID\n      - Serializable\n      - Cloud Native\n    properties:\n      - type: Documentation\n        url: https://www.cockroachlabs.com/docs/stable/\n      - type: Documentation\n        url: https://www.cockroachlabs.com/docs/stable/transactions.html\n        title: CockroachDB Transactions\n      - type: GitHubRepository\n        url: https://github.com/cockroachdb/cockroach\n  - name: Google Spanner API\n    description: >-\n      Google Spanner is a globally distributed, externally consistent database\n      providing ACID transactions at\
  \ global scale using TrueTime clock\n      synchronization (GPS receivers and atomic clocks). The Cloud Spanner API\n      offers both read-write transactions and read-only transactions with\n      configurable staleness bounds. It is available via REST and gRPC.\n    humanURL: https://cloud.google.com/spanner/docs/transactions\n    baseURL: https://spanner.googleapis.com/\n    tags:\n      - Google Spanner\n      - Distributed Database\n      - Global Scale\n      - ACID\n      - TrueTime\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/spanner/docs/transactions\n      - type: APIReference\n        url: https://cloud.google.com/spanner/docs/reference/rest\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/googleapis.com/spanner/v1/openapi.yaml\n  - name: Amazon Aurora Transactions API\n    description: >-\n      Amazon Aurora provides ACID-compliant transactions for both MySQL-compatible\n  \
  \    and PostgreSQL-compatible editions. Aurora's distributed storage layer\n      provides durability across 3 availability zones with 6-way replication.\n      The Aurora Data API enables HTTP-based serverless SQL transactions with\n      automatic commit and rollback capabilities.\n    humanURL: https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Aurora.Overview.html\n    baseURL: https://rds.amazonaws.com/\n    tags:\n      - AWS Aurora\n      - MySQL\n      - PostgreSQL\n      - ACID\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Aurora.Overview.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/rdsdataservice/latest/APIReference/\n        title: Aurora Data API Reference\n  - name: Atomikos Transaction API\n    description: >-\n      Atomikos provides ACID transaction management middleware for distributed\n      microservices, supporting XA transactions across\
  \ REST services using the\n      Try-Confirm/Cancel (TCC) pattern. It enables ACID guarantees spanning\n      multiple databases and message brokers without requiring a central\n      coordinator in many scenarios.\n    humanURL: https://www.atomikos.com/\n    baseURL: https://www.atomikos.com/\n    tags:\n      - Atomikos\n      - Distributed Transactions\n      - TCC Pattern\n      - Microservices\n      - XA\n    properties:\n      - type: Documentation\n        url: https://www.atomikos.com/\n      - type: Documentation\n        url: https://www.atomikos.com/Blog/ACIDTransactionsAcrossMicroservices\n        title: ACID Transactions Across Microservices\ncommon:\n  - type: Website\n    url: https://en.wikipedia.org/wiki/ACID\n    title: ACID Wikipedia Reference\n  - type: GitHubRepository\n    url: https://github.com/cockroachdb/cockroach\n    title: CockroachDB Open Source Repository\n  - type: Features\n    data:\n      - name: Atomicity\n        description: >-\n          Transactions\
  \ are all-or-nothing: either all operations in a transaction\n          succeed and are committed, or none are applied and the database is\n          rolled back to its prior state.\n      - name: Consistency\n        description: >-\n          A transaction brings the database from one valid, consistent state to\n          another, enforcing all defined constraints, triggers, and cascades. No\n          transaction can leave data in an invalid state.\n      - name: Isolation\n        description: >-\n          Concurrent transactions execute as if they were serialized, preventing\n          interference. Isolation levels (READ COMMITTED, REPEATABLE READ,\n          SERIALIZABLE) control the degree of visibility between concurrent transactions.\n      - name: Durability\n        description: >-\n          Once a transaction is committed, it remains committed even in the event\n          of system crashes, power failures, or other errors, typically achieved\n          through write-ahead\
  \ logging (WAL) and replication.\n      - name: Distributed ACID\n        description: >-\n          Modern distributed databases extend ACID guarantees across multiple\n          nodes, regions, and data centers using consensus algorithms (Raft,\n          Paxos) and synchronized clocks (TrueTime).\n      - name: REST API Transaction Patterns\n        description: >-\n          Design patterns for ACID-like guarantees in REST APIs include Two-Phase\n          Commit (2PC), Try-Confirm/Cancel (TCC), and Saga patterns for managing\n          distributed transactions across microservices.\n  - type: UseCases\n    data:\n      - name: Financial Transactions\n        description: >-\n          Banking and payment systems require ACID compliance to ensure monetary\n          transfers are atomic — debits and credits always balance — and durable\n          across system failures.\n      - name: Inventory Management\n        description: >-\n          E-commerce and supply chain systems use ACID\
  \ transactions to prevent\n          overselling by ensuring inventory decrements and order creation are\n          atomic.\n      - name: Distributed Microservices Coordination\n        description: >-\n          Microservices architectures use Saga and TCC patterns to achieve\n          eventual consistency with compensating transactions when full ACID\n          across services is not feasible.\n      - name: Multi-Region Database Replication\n        description: >-\n          Global applications use databases like Google Spanner and CockroachDB\n          to maintain ACID consistency across geographic regions without\n          sacrificing availability.\n      - name: Idempotent API Design\n        description: >-\n          REST APIs use database transactions to implement idempotency keys,\n          ensuring duplicate requests produce the same result without double\n          processing.\n  - type: Integrations\n    data:\n      - name: PostgreSQL\n        description: >-\n    \
  \      The most widely deployed open-source RDBMS with full ACID compliance\n          via MVCC and configurable transaction isolation levels.\n      - name: MySQL / MariaDB\n        description: >-\n          Popular open-source databases providing ACID compliance through the\n          InnoDB storage engine with row-level locking and MVCC.\n      - name: MongoDB Multi-Document Transactions\n        description: >-\n          MongoDB added multi-document ACID transactions in version 4.0, extending\n          its document model with ACID guarantees across documents and collections.\n      - name: Apache Kafka Transactions\n        description: >-\n          Kafka's transactional API (since 0.11) enables exactly-once semantics\n          with atomic writes to multiple partitions, providing ACID-like guarantees\n          for stream processing pipelines.\n      - name: Saga Pattern / Orchestration\n        description: >-\n          The Saga pattern decomposes long-running transactions into\
  \ a series of\n          local transactions with compensating actions for distributed consistency\n          without 2PC overhead.\n  - type: JSON-LD\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/acid/refs/heads/main/json-ld/acid-context.jsonld\n    title: ACID JSON-LD Context\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/acid/refs/heads/main/vocabulary/acid-vocabulary.yaml\n    title: ACID Vocabulary\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/acid/refs/heads/main/apis.yml
tags:
- ACID
- Database
- Transactions
- Atomicity
- Consistency
- Isolation
- Durability
- Distributed Systems
url: https://raw.githubusercontent.com/api-evangelist/acid/refs/heads/main/apis.yml
use_cases:
- description: Banking and payment systems require ACID compliance to ensure monetary transfers are atomic — debits and credits always balance — and durable across system failures.
  name: Financial Transactions
- description: E-commerce and supply chain systems use ACID transactions to prevent overselling by ensuring inventory decrements and order creation are atomic.
  name: Inventory Management
- description: Microservices architectures use Saga and TCC patterns to achieve eventual consistency with compensating transactions when full ACID across services is not feasible.
  name: Distributed Microservices Coordination
- description: Global applications use databases like Google Spanner and CockroachDB to maintain ACID consistency across geographic regions without sacrificing availability.
  name: Multi-Region Database Replication
- description: REST APIs use database transactions to implement idempotency keys, ensuring duplicate requests produce the same result without double processing.
  name: Idempotent API Design
---
