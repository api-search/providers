---
api_count: 3
apis:
- description: The Delta Lake storage framework defines the on-disk transaction log and protocol that adds ACID transactions, schema enforcement, and time travel to Parquet-based data lakes. Delta Lake exposes Spark
  name: Delta Lake Storage Framework
  slug: delta-lake-storage
- description: Delta Sharing is an open protocol for secure data sharing across organizations, defined as a REST API specification. Sharing servers expose endpoints for listing shares, schemas, and tables, and for r
  name: Delta Sharing Protocol
  slug: delta-sharing
- description: Catalog-managed Delta tables delegate table scan planning to an external catalog using the Iceberg REST Catalog protocol, enabling interoperability with Unity Catalog and other catalog services.
  name: Delta Catalog-Managed Tables
  slug: delta-catalog
common:
- title: ''
  type: Website
  url: https://delta.io/
- title: ''
  type: Documentation
  url: https://docs.delta.io/
- title: ''
  type: GitHubOrg
  url: https://github.com/delta-io
- title: ''
  type: Blog
  url: https://delta.io/blog/
- title: ''
  type: LinuxFoundation
  url: https://lfaidata.foundation/projects/delta-lake/
- title: ''
  type: Slack
  url: https://go.delta.io/slack
- title: ''
  type: Vocabulary
  url: vocabulary/delta-lake-vocabulary.yml
created: '2026-03-16'
description: Delta Lake is a graduated project of the Linux Foundation AI & Data Foundation providing an open source storage framework for building Lakehouse architectures. Originally contributed by Databricks, it adds reliability, quality, and performance to data lakes with ACID transactions, schema enforcement, time travel, and Iceberg/Hudi interoperability via UniForm. Delta Lake projects also include Delta Sharing (an open protocol for secure data sharing) and catalog-managed tables built on the Iceberg REST Catalog protocol.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Delta Lake
skills: []
slug: delta-lake
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: delta-lake\nname: Delta Lake\ndescription: >-\n  Delta Lake is a graduated project of the Linux Foundation AI & Data\n  Foundation providing an open source storage framework for building\n  Lakehouse architectures. Originally contributed by Databricks, it adds\n  reliability, quality, and performance to data lakes with ACID\n  transactions, schema enforcement, time travel, and Iceberg/Hudi\n  interoperability via UniForm. Delta Lake projects also include\n  Delta Sharing (an open protocol for secure data sharing) and\n  catalog-managed tables built on the Iceberg REST Catalog protocol.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data\n  - Data Lake\n  - Lakehouse\n  - Linux Foundation\n  - Open Source\n  - Storage\n  - Streaming\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/delta-lake/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\nxType: opensource\napis:\n  - aid: delta-lake:delta-lake-storage\n    name: Delta Lake Storage Framework\n    description: >-\n      The Delta Lake storage framework defines the on-disk transaction log\n      and protocol that adds ACID transactions, schema enforcement, and\n      time travel to Parquet-based data lakes. Delta Lake exposes Spark,\n      Rust, and Python APIs (delta-spark, delta-rs, deltalake) rather\n      than a network API.\n    humanURL: https://docs.delta.io/\n    tags:\n      - Lakehouse\n      - Protocol\n      - Storage\n      - Transaction Log\n    properties:\n      - type: Documentation\n        url: https://docs.delta.io/\n      - type: Protocol\n        url: https://github.com/delta-io/delta/blob/master/PROTOCOL.md\n      - type: SourceCode\n        url: https://github.com/delta-io/delta\n      - type: Releases\n        url: https://github.com/delta-io/delta/releases\n  - aid: delta-lake:delta-sharing\n    name: Delta Sharing Protocol\n\
  \    description: >-\n      Delta Sharing is an open protocol for secure data sharing across\n      organizations, defined as a REST API specification. Sharing servers\n      expose endpoints for listing shares, schemas, and tables, and for\n      retrieving signed URLs to underlying data files.\n    humanURL: https://delta.io/sharing/\n    tags:\n      - Data Sharing\n      - Open Protocol\n      - REST\n    properties:\n      - type: Documentation\n        url: https://github.com/delta-io/delta-sharing\n      - type: Protocol\n        url: https://github.com/delta-io/delta-sharing/blob/main/PROTOCOL.md\n      - type: SourceCode\n        url: https://github.com/delta-io/delta-sharing\n  - aid: delta-lake:delta-catalog\n    name: Delta Catalog-Managed Tables\n    description: >-\n      Catalog-managed Delta tables delegate table scan planning to an\n      external catalog using the Iceberg REST Catalog protocol, enabling\n      interoperability with Unity Catalog and other catalog services.\n\
  \    humanURL: https://delta.io/blog/2026-02-02-delta-catalog-managed-tables/\n    tags:\n      - Catalog\n      - Iceberg REST\n      - Interoperability\n    properties:\n      - type: Documentation\n        url: https://delta.io/blog/2026-02-02-delta-catalog-managed-tables/\n      - type: Protocol\n        url: https://github.com/delta-io/delta/blob/master/PROTOCOL.md\ncommon:\n  - type: Website\n    url: https://delta.io/\n  - type: Documentation\n    url: https://docs.delta.io/\n  - type: GitHubOrg\n    url: https://github.com/delta-io\n  - type: Blog\n    url: https://delta.io/blog/\n  - type: LinuxFoundation\n    url: https://lfaidata.foundation/projects/delta-lake/\n  - type: Slack\n    url: https://go.delta.io/slack\n  - type: Vocabulary\n    url: vocabulary/delta-lake-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/delta-lake/refs/heads/main/apis.yml
tags:
- Data
- Data Lake
- Lakehouse
- Linux Foundation
- Open Source
- Storage
- Streaming
url: https://raw.githubusercontent.com/api-evangelist/delta-lake/refs/heads/main/apis.yml
use_cases: []
---
