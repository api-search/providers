---
api_count: 3
apis:
- description: 'Apache DataSketches is the open-source library providing production-quality implementations of sketch algorithms including Theta Sketches (set operations), Quantiles Sketches (percentile estimation), '
  name: Apache DataSketches API
  slug: apache-datasketches-api
- description: Redis provides native probabilistic data structure commands through the Redis Stack (RedisBloom module), offering server-side implementations of Bloom Filter, Cuckoo Filter, Count-Min Sketch, Top-K, a
  name: Redis Probabilistic Data Structures API
  slug: redis-probabilistic-api
- description: Amazon Redshift supports approximate query processing using HyperLogLog sketch functions (HLL_CREATE_SKETCH, HLL_COMBINE, HLL_CARDINALITY) for fast cardinality estimation on large datasets. These nati
  name: Amazon Redshift Approximate Query API
  slug: amazon-redshift-sketches-api
common:
- title: ''
  type: Website
  url: https://datasketches.apache.org
- title: ''
  type: JSON-LD
  url: json-ld/sketches-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/sketches-vocabulary.yml
created: '2025'
description: Sketches are probabilistic data structures used in computing and data engineering to approximate answers to queries over large data streams with controlled error bounds and dramatically reduced memory requirements. Common sketches include Count-Min Sketch (frequency estimation), HyperLogLog (cardinality estimation), Bloom Filter (membership testing), and T-Digest (quantile estimation). APIs in this domain include sketch-native databases like Apache DataSketches, Redis probabilistic data structures, and cloud analytics services that implement sketch algorithms for real-time analytics, approximate query processing, and streaming analytics.
features: []
image: ''
integrations: []
jsonld:
- class_count: 31
  name: Sketches Context
  property_count: 2
  slug: sketches-context
layout: provider
modified: '2026-05-02'
name: Sketches
skills: []
slug: sketches
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sketches\nurl: https://raw.githubusercontent.com/api-evangelist/sketches/refs/heads/main/apis.yml\nname: Sketches\ndescription: >-\n  Sketches are probabilistic data structures used in computing and data engineering\n  to approximate answers to queries over large data streams with controlled error bounds\n  and dramatically reduced memory requirements. Common sketches include Count-Min Sketch\n  (frequency estimation), HyperLogLog (cardinality estimation), Bloom Filter (membership\n  testing), and T-Digest (quantile estimation). APIs in this domain include sketch-native\n  databases like Apache DataSketches, Redis probabilistic data structures, and cloud\n  analytics services that implement sketch algorithms for real-time analytics, approximate\n  query processing, and streaming analytics.\ntags:\n  - Data Structures\n  - Probabilistic Algorithms\n  - Streaming Analytics\n  - Approximate Query Processing\n  - Big Data\n  - Real-Time Analytics\ncreated: '2025'\nmodified:\
  \ '2026-05-02'\n\napis:\n  - aid: sketches:apache-datasketches-api\n    name: Apache DataSketches API\n    description: >-\n      Apache DataSketches is the open-source library providing production-quality\n      implementations of sketch algorithms including Theta Sketches (set operations),\n      Quantiles Sketches (percentile estimation), HLL (HyperLogLog for cardinality),\n      CPC, Frequency, and Tuple sketches. It is widely used in data warehouses and\n      OLAP systems including Apache Druid, Apache Spark, and Amazon Redshift. The\n      library provides Java, C++, and Python APIs.\n    humanURL: https://datasketches.apache.org\n    baseURL: https://datasketches.apache.org\n    tags:\n      - Open Source\n      - Apache\n      - Data Structures\n      - Probabilistic Algorithms\n      - Analytics\n    properties:\n      - url: https://datasketches.apache.org\n        type: Documentation\n      - url: https://github.com/apache/datasketches-java\n        type: GitHubOrg\n\n  - aid:\
  \ sketches:redis-probabilistic-api\n    name: Redis Probabilistic Data Structures API\n    description: >-\n      Redis provides native probabilistic data structure commands through the Redis\n      Stack (RedisBloom module), offering server-side implementations of Bloom Filter,\n      Cuckoo Filter, Count-Min Sketch, Top-K, and HyperLogLog. These are accessible\n      via the Redis command interface and all official Redis client libraries, enabling\n      high-throughput approximate data processing without external dependencies.\n    humanURL: https://redis.io/docs/data-types/probabilistic/\n    baseURL: https://redis.io\n    tags:\n      - Redis\n      - Probabilistic Data Structures\n      - Real-Time\n      - In-Memory\n    properties:\n      - url: https://redis.io/docs/data-types/probabilistic/\n        type: Documentation\n      - url: https://redis.io\n        type: Website\n\n  - aid: sketches:amazon-redshift-sketches-api\n    name: Amazon Redshift Approximate Query API\n    description:\
  \ >-\n      Amazon Redshift supports approximate query processing using HyperLogLog sketch\n      functions (HLL_CREATE_SKETCH, HLL_COMBINE, HLL_CARDINALITY) for fast cardinality\n      estimation on large datasets. These native SQL functions enable analytics teams\n      to run near-instantaneous approximate COUNT DISTINCT queries on billions of rows\n      with controlled error bounds.\n    humanURL: https://docs.aws.amazon.com/redshift/latest/dg/r_HLL_function.html\n    baseURL: https://aws.amazon.com\n    tags:\n      - AWS\n      - Redshift\n      - Analytics\n      - HyperLogLog\n      - SQL\n    properties:\n      - url: https://docs.aws.amazon.com/redshift/latest/dg/r_HLL_function.html\n        type: Documentation\n\ncommon:\n  - type: Website\n    url: https://datasketches.apache.org\n  - type: JSON-LD\n    url: json-ld/sketches-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/sketches-vocabulary.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sketches/refs/heads/main/apis.yml
tags:
- Data Structures
- Probabilistic Algorithms
- Streaming Analytics
- Approximate Query Processing
- Big Data
- Real-Time Analytics
url: https://raw.githubusercontent.com/api-evangelist/sketches/refs/heads/main/apis.yml
use_cases: []
---
