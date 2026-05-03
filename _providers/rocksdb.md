---
api_count: 2
apis:
- description: RocksDB C++ library API providing key-value storage operations including Get, Put, Delete, Merge, iterators, snapshots, column families, transactions, compaction, and backup. The primary interface for
  name: RocksDB Embedded API
  slug: rocksdb-embedded-api
- description: Official Java bindings for RocksDB providing full access to the RocksDB feature set from Java applications. Used in distributed systems like Apache Kafka Streams, Flink, and Cassandra as the underlyin
  name: RocksJava API
  slug: rocksjava-api
common:
- title: ''
  type: Website
  url: https://rocksdb.org/
- title: ''
  type: GitHubRepository
  url: https://github.com/facebook/rocksdb
- title: ''
  type: Documentation
  url: https://github.com/facebook/rocksdb/wiki
- title: ''
  type: GettingStarted
  url: https://rocksdb.org/docs/getting-started.html
- title: ''
  type: Examples
  url: https://github.com/facebook/rocksdb/tree/main/examples
- title: ''
  type: PackageManager
  url: https://mvnrepository.com/artifact/org.rocksdb/rocksdbjni
- title: ''
  type: JSONSchema
  url: json-schema/rocksdb-options-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/rocksdb-key-value-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/rocksdb-options-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/rocksdb-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/rocksdb-vocabulary.yml
created: '2025-01-01'
description: RocksDB is an embeddable persistent key-value store for fast storage, developed at Facebook (Meta) based on LevelDB. It uses a Log-Structured Merge (LSM) tree design optimized for fast, low-latency storage on flash and RAM. RocksDB provides a C++ library with language bindings for Java, Python, Ruby, Rust, and other languages, and is widely used as the storage engine inside databases, data streaming systems, and distributed key-value stores.
features: []
image: ''
integrations: []
jsonld:
- class_count: 13
  name: Rocksdb Context
  property_count: 14
  slug: rocksdb-context
layout: provider
modified: '2026-05-02'
name: RocksDB
skills: []
slug: rocksdb
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rocksdb\nname: RocksDB\ndescription: >-\n  RocksDB is an embeddable persistent key-value store for fast storage, developed\n  at Facebook (Meta) based on LevelDB. It uses a Log-Structured Merge (LSM) tree\n  design optimized for fast, low-latency storage on flash and RAM. RocksDB provides\n  a C++ library with language bindings for Java, Python, Ruby, Rust, and other\n  languages, and is widely used as the storage engine inside databases, data streaming\n  systems, and distributed key-value stores.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/rocksdb/refs/heads/main/apis.yml\ntags:\n  - RocksDB\n  - Key-Value Store\n  - Embedded Database\n  - Storage Engine\n  - Open Source\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rocksdb:rocksdb-embedded-api\n    name: RocksDB Embedded API\n    description: >-\n      RocksDB C++ library API providing key-value storage operations including\n      Get, Put, Delete,\
  \ Merge, iterators, snapshots, column families, transactions,\n      compaction, and backup. The primary interface for embedding RocksDB in\n      applications as a persistent key-value store.\n    tags:\n      - Key-Value Store\n      - Embedded Database\n      - Storage Engine\n      - C++\n      - Open Source\n    humanURL: https://rocksdb.org/\n    baseURL: https://github.com/facebook/rocksdb\n    properties:\n      - url: https://rocksdb.org/\n        type: Documentation\n      - url: https://github.com/facebook/rocksdb/wiki\n        type: Documentation\n      - url: https://rocksdb.org/docs/getting-started.html\n        type: GettingStarted\n      - url: https://github.com/facebook/rocksdb\n        type: GitHubRepository\n    solutions:\n      - Fast Storage Engine\n      - Embedded Database\n      - Write-Heavy Workloads\n      - Time-Series Storage\n      - Log-Structured Storage\n    features:\n      - Key-Value Operations (Get, Put, Delete, Merge)\n      - Column Families\n \
  \     - Transactions and ACID Properties\n      - Snapshots and Iterators\n      - Compaction (Leveled, Universal, FIFO)\n      - Write-Ahead Log (WAL)\n      - Backup and Restore\n      - Compression Support\n      - TTL (Time to Live)\n      - BlobDB for Large Values\n      - Rate Limiting\n      - Block Cache\n      - Direct I/O\n      - Statistics and Monitoring\n\n  - aid: rocksdb:rocksjava-api\n    name: RocksJava API\n    description: >-\n      Official Java bindings for RocksDB providing full access to the RocksDB\n      feature set from Java applications. Used in distributed systems like Apache\n      Kafka Streams, Flink, and Cassandra as the underlying storage engine.\n    tags:\n      - Key-Value Store\n      - Java\n      - Embedded Database\n      - Storage Engine\n    humanURL: https://github.com/facebook/rocksdb/wiki/RocksJava-Basics\n    baseURL: https://github.com/facebook/rocksdb\n    properties:\n      - url: https://github.com/facebook/rocksdb/wiki/RocksJava-Basics\n\
  \        type: Documentation\n      - url: https://github.com/facebook/rocksdb\n        type: GitHubRepository\n      - url: https://mvnrepository.com/artifact/org.rocksdb/rocksdbjni\n        type: PackageManager\n\ncommon:\n  - url: https://rocksdb.org/\n    type: Website\n  - url: https://github.com/facebook/rocksdb\n    type: GitHubRepository\n  - url: https://github.com/facebook/rocksdb/wiki\n    type: Documentation\n  - url: https://rocksdb.org/docs/getting-started.html\n    type: GettingStarted\n  - url: https://github.com/facebook/rocksdb/tree/main/examples\n    type: Examples\n  - url: https://mvnrepository.com/artifact/org.rocksdb/rocksdbjni\n    type: PackageManager\n  - url: json-schema/rocksdb-options-schema.json\n    type: JSONSchema\n  - url: json-schema/rocksdb-key-value-schema.json\n    type: JSONSchema\n  - url: json-structure/rocksdb-options-structure.json\n    type: JSONStructure\n  - url: json-ld/rocksdb-context.jsonld\n    type: JSONLDContext\n  - url: vocabulary/rocksdb-vocabulary.yml\n\
  \    type: Vocabulary\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rocksdb/refs/heads/main/apis.yml
tags:
- RocksDB
- Key-Value Store
- Embedded Database
- Storage Engine
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/rocksdb/refs/heads/main/apis.yml
use_cases: []
---
