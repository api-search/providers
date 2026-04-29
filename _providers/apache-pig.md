---
api_count: 1
api_specs:
- filename: apache-pig-api.yaml
  format: yaml
  label: Apache Pig
  slug: apache-pig
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-pig/refs/heads/main/openapi/apache-pig-api.yaml
apis:
- description: Pig provides the Pig Latin scripting language for data analysis, an embedded Pig API for programmatic execution from Java, and a UDF (User Defined Function) API for custom data transformation function
  name: Apache Pig
  slug: apache-pig
capabilities:
- description: Workflow for submitting, monitoring, and managing Pig Latin data analysis jobs on Hadoop clusters.
  name: Apache Pig Data Processing Workflow
  slug: pig-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/pig
- title: ''
  type: Documentation
  url: https://pig.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-pig-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-pig-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/pig-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-pig-context.jsonld
created: '2026-03-16'
description: Apache Pig is a platform for analyzing large data sets that provides a high-level language (Pig Latin) for expressing data analysis programs. It compiles Pig Latin programs into MapReduce/Tez jobs and runs them on Hadoop clusters.
features:
- description: High-level dataflow language for expressing data transformations
  name: Pig Latin Language
- description: Compiles Pig Latin to MapReduce or Apache Tez execution plans
  name: MapReduce/Tez Backend
- description: User-defined functions in Java, Python, JavaScript, and Ruby
  name: UDF Support
- description: Process data through external programs using STREAM operator
  name: Streaming
- description: Flexible schema handling for semi-structured data
  name: Schema Evolution
- description: Automatic logical and physical plan optimization
  name: Optimization
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native MapReduce execution on YARN/HDFS
  name: Apache Hadoop
- description: High-performance Tez execution engine support
  name: Apache Tez
- description: HBase storage handler for reading/writing HBase tables
  name: Apache HBase
- description: HCatalog integration for Hive metastore access
  name: Apache Hive
- description: S3 input/output for cloud-based data processing
  name: Amazon S3
jsonld:
- class_count: 7
  name: Apache Pig Context
  property_count: 19
  slug: apache-pig-context
layout: provider
modified: '2026-04-19'
name: Apache Pig
rules:
- name: Apache Pig API Rules
  rule_count: 5
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 0
  slug: apache-pig-spectral-rules
skills: []
slug: apache-pig
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-pig\nname: Apache Pig\ndescription: >-\n  Apache Pig is a platform for analyzing large data sets that provides a high-level language (Pig Latin) for expressing data analysis programs. It compiles Pig Latin programs into MapReduce/Tez jobs and\n  runs them on Hadoop clusters.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Big Data\n- Data Analysis\n- ETL\n- Hadoop\n- Scripting\n- Apache\n- Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-pig/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-pig:apache-pig\n  name: Apache Pig\n  description: >-\n    Pig provides the Pig Latin scripting language for data analysis, an embedded Pig API for programmatic execution from Java, and a UDF (User Defined Function) API for custom data transformation functions.\n  humanURL: https://pig.apache.org/docs/latest/\n\
  \  tags:\n  - Data Analysis\n  - Java\n  - Pig Latin\n  - UDF\n  - Apache\n  - Open Source\n  properties:\n  - type: Documentation\n    url: https://pig.apache.org/docs/latest/\n  - type: OpenAPI\n    url: openapi/apache-pig-api.yaml\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: GitHubOrganization\n  url: https://github.com/apache/pig\n- type: Documentation\n  url: https://pig.apache.org/\n- type: SpectralRules\n  url: rules/apache-pig-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/apache-pig-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/pig-workflow.yaml\n- type: JSON-LD\n  url: json-ld/apache-pig-context.jsonld\n- type: Features\n  data:\n  - name: Pig Latin Language\n    description: High-level dataflow language for expressing data transformations\n  - name: MapReduce/Tez Backend\n    description: Compiles Pig Latin to MapReduce or Apache Tez execution plans\n  - name: UDF Support\n    description: User-defined functions\
  \ in Java, Python, JavaScript, and Ruby\n  - name: Streaming\n    description: Process data through external programs using STREAM operator\n  - name: Schema Evolution\n    description: Flexible schema handling for semi-structured data\n  - name: Optimization\n    description: Automatic logical and physical plan optimization\n- type: UseCases\n  data:\n  - name: ETL Pipelines\n    description: Build data transformation pipelines from raw logs to structured data\n  - name: Ad-hoc Data Analysis\n    description: Analyze large datasets with ad-hoc Pig Latin queries\n  - name: Data Preparation\n    description: Clean and prepare data for machine learning workflows\n  - name: Log Processing\n    description: Process and aggregate web server and application logs\n- type: Integrations\n  data:\n  - name: Apache Hadoop\n    description: Native MapReduce execution on YARN/HDFS\n  - name: Apache Tez\n    description: High-performance Tez execution engine support\n  - name: Apache HBase\n    description:\
  \ HBase storage handler for reading/writing HBase tables\n  - name: Apache Hive\n    description: HCatalog integration for Hive metastore access\n  - name: Amazon S3\n    description: S3 input/output for cloud-based data processing\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-pig/refs/heads/main/apis.yml
tags:
- Big Data
- Data Analysis
- ETL
- Hadoop
- Scripting
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-pig/refs/heads/main/apis.yml
use_cases:
- description: Build data transformation pipelines from raw logs to structured data
  name: ETL Pipelines
- description: Analyze large datasets with ad-hoc Pig Latin queries
  name: Ad-hoc Data Analysis
- description: Clean and prepare data for machine learning workflows
  name: Data Preparation
- description: Process and aggregate web server and application logs
  name: Log Processing
---
