---
api_count: 4
api_specs:
- filename: rest-catalog-open-api.yaml
  format: yaml
  label: Apache Iceberg REST Catalog API
  slug: apache-iceberg-rest-catalog
  spec_type: OpenAPI
  url: https://github.com/apache/iceberg/blob/main/open-api/rest-catalog-open-api.yaml
- filename: all.yaml
  format: yaml
  label: Unity Catalog
  slug: unity-catalog
  spec_type: OpenAPI
  url: https://github.com/unitycatalog/unitycatalog/blob/main/api/all.yaml
apis:
- description: The Apache Iceberg REST Catalog API is an open OpenAPI specification that defines a standard interface for interacting with Apache Iceberg table catalogs. It enables catalog operations including names
  name: Apache Iceberg REST Catalog API
  slug: apache-iceberg-rest-catalog
- description: Delta Lake is an open-source storage framework developed by Databricks that adds reliability, performance, and ACID compliance to data lakes. It uses a transaction log (delta log) to record all change
  name: Delta Lake
  slug: delta-lake
- description: Apache Hudi (Hadoop Upserts Deletes and Incrementals) is an open-source data lakehouse platform optimized for upserts, deletes, and incremental data processing. It supports Copy-on-Write (COW) and Mer
  name: Apache Hudi
  slug: apache-hudi
- description: Unity Catalog is an open-source, multi-modal catalog for data and AI that supports Apache Iceberg REST Catalog API, Apache Hive Metastore (HMS) API, and Delta Sharing. It provides unified governance a
  name: Unity Catalog
  slug: unity-catalog
common:
- title: ''
  type: Wikipedia
  url: https://en.wikipedia.org/wiki/Apache_Iceberg
- title: ''
  type: Apache Iceberg
  url: https://iceberg.apache.org/
- title: ''
  type: Delta Lake
  url: https://delta.io/
- title: ''
  type: Apache Hudi
  url: https://hudi.apache.org/
- title: ''
  type: Unity Catalog
  url: https://www.unitycatalog.io/
- title: ''
  type: Apache Iceberg GitHub
  url: https://github.com/apache/iceberg
- title: ''
  type: Delta Lake GitHub
  url: https://github.com/delta-io/delta
- title: ''
  type: Apache Hudi GitHub
  url: https://github.com/apache/hudi
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/table-format/refs/heads/main/vocabulary/table-format-vocabulary.yml
created: '2025'
description: Open Table Format is a category of open standards for organizing and managing data in data lakehouses. The three dominant formats are Apache Iceberg (the emerging industry standard with snapshot-based metadata and broad engine support), Delta Lake (Databricks-originated, transaction-log-based), and Apache Hudi (upsert-optimized with Copy-on-Write and Merge-on-Read modes). These formats bring ACID transactions, schema evolution, time travel, and efficient query planning to data lake storage. Apache Iceberg defines a REST Catalog API (OpenAPI spec) that enables standardized catalog operations across implementations like Polaris, Nessie, AWS Glue, and Google BigLake.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 26
  name: Table Format Context
  property_count: 0
  slug: table-format-context
layout: provider
modified: '2026-05-03'
name: Table Format
skills: []
slug: table-format
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: table-format\nname: Table Format\ndescription: >-\n  Open Table Format is a category of open standards for organizing and managing\n  data in data lakehouses. The three dominant formats are Apache Iceberg (the\n  emerging industry standard with snapshot-based metadata and broad engine\n  support), Delta Lake (Databricks-originated, transaction-log-based), and\n  Apache Hudi (upsert-optimized with Copy-on-Write and Merge-on-Read modes).\n  These formats bring ACID transactions, schema evolution, time travel, and\n  efficient query planning to data lake storage. Apache Iceberg defines a REST\n  Catalog API (OpenAPI spec) that enables standardized catalog operations across\n  implementations like Polaris, Nessie, AWS Glue, and Google BigLake.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Lakehouse\n  - Open Table Format\n  - Apache Iceberg\n  - Delta Lake\n  - Apache Hudi\n  - Data Lake\n  - ACID Transactions\n\
  \  - Schema Evolution\n  - Time Travel\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/table-format/refs/heads/main/apis.yml\ncreated: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: table-format:apache-iceberg-rest-catalog\n    name: Apache Iceberg REST Catalog API\n    description: >-\n      The Apache Iceberg REST Catalog API is an open OpenAPI specification that\n      defines a standard interface for interacting with Apache Iceberg table\n      catalogs. It enables catalog operations including namespace management,\n      table creation, schema updates, and metadata retrieval across any\n      compliant catalog implementation (Polaris, Nessie, AWS Glue, Google BigLake).\n    humanURL: https://iceberg.apache.org/rest-catalog-spec/\n    baseURL: https://catalog-service/\n    tags:\n      - Apache Iceberg\n      - Data Catalog\n      - REST Catalog\n      - Data Lakehouse\n    properties:\n      - type: Documentation\n        url: https://iceberg.apache.org/rest-catalog-spec/\n\
  \      - type: OpenAPI\n        url: https://github.com/apache/iceberg/blob/main/open-api/rest-catalog-open-api.yaml\n      - type: GitHub\n        url: https://github.com/apache/iceberg\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/table-format/refs/heads/main/openapi/apache-iceberg-rest-catalog-openapi.yml\n\n  - aid: table-format:delta-lake\n    name: Delta Lake\n    description: >-\n      Delta Lake is an open-source storage framework developed by Databricks\n      that adds reliability, performance, and ACID compliance to data lakes. It\n      uses a transaction log (delta log) to record all changes to data. Delta\n      Lake is deeply integrated with Apache Spark and supports batch and\n      streaming workloads, schema enforcement, time travel, and MERGE operations.\n    humanURL: https://delta.io/\n    tags:\n      - Delta Lake\n      - Data Lake\n      - ACID Transactions\n      - Apache Spark\n      - Databricks\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.delta.io/\n      - type: GitHub\n        url: https://github.com/delta-io/delta\n\n  - aid: table-format:apache-hudi\n    name: Apache Hudi\n    description: >-\n      Apache Hudi (Hadoop Upserts Deletes and Incrementals) is an open-source\n      data lakehouse platform optimized for upserts, deletes, and incremental\n      data processing. It supports Copy-on-Write (COW) and Merge-on-Read (MOR)\n      table types and is used for CDC-based data pipelines and streaming analytics.\n    humanURL: https://hudi.apache.org/\n    tags:\n      - Apache Hudi\n      - Data Lake\n      - CDC\n      - Incremental Processing\n    properties:\n      - type: Documentation\n        url: https://hudi.apache.org/docs/overview/\n      - type: GitHub\n        url: https://github.com/apache/hudi\n\n  - aid: table-format:unity-catalog\n    name: Unity Catalog\n    description: >-\n      Unity Catalog is an open-source, multi-modal catalog for data and\
  \ AI that\n      supports Apache Iceberg REST Catalog API, Apache Hive Metastore (HMS) API,\n      and Delta Sharing. It provides unified governance across Delta Lake, Iceberg,\n      and Hudi tables with an OpenAPI specification under Apache 2.0 license.\n    humanURL: https://www.unitycatalog.io/\n    tags:\n      - Data Catalog\n      - Unity Catalog\n      - Data Governance\n      - Multi-format\n    properties:\n      - type: Documentation\n        url: https://www.unitycatalog.io/\n      - type: OpenAPI\n        url: https://github.com/unitycatalog/unitycatalog/blob/main/api/all.yaml\n      - type: GitHub\n        url: https://github.com/unitycatalog/unitycatalog\n\ncommon:\n  - type: Wikipedia\n    url: https://en.wikipedia.org/wiki/Apache_Iceberg\n  - type: Apache Iceberg\n    url: https://iceberg.apache.org/\n  - type: Delta Lake\n    url: https://delta.io/\n  - type: Apache Hudi\n    url: https://hudi.apache.org/\n  - type: Unity Catalog\n    url: https://www.unitycatalog.io/\n\
  \  - type: Apache Iceberg GitHub\n    url: https://github.com/apache/iceberg\n  - type: Delta Lake GitHub\n    url: https://github.com/delta-io/delta\n  - type: Apache Hudi GitHub\n    url: https://github.com/apache/hudi\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/table-format/refs/heads/main/vocabulary/table-format-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/table-format/refs/heads/main/apis.yml
tags:
- Data Lakehouse
- Open Table Format
- Apache Iceberg
- Delta Lake
- Apache Hudi
- Data Lake
- ACID Transactions
- Schema Evolution
- Time Travel
url: https://raw.githubusercontent.com/api-evangelist/table-format/refs/heads/main/apis.yml
use_cases: []
---
