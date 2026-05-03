---
api_count: 1
api_specs:
- filename: trino-client-api-openapi.yml
  format: yaml
  label: Trino Client REST API
  slug: trino-client-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trino/refs/heads/main/openapi/trino-client-api-openapi.yml
apis:
- description: The Trino Client REST API enables clients to submit SQL queries to a Trino coordinator and retrieve results. Clients POST SQL to /v1/statement, then poll GET on the returned nextUri, and may DELETE ne
  name: Trino Client REST API
  slug: trino-client-api
capabilities:
- description: Workflow capability for submitting distributed SQL queries to Trino, monitoring query execution, retrieving results, and managing the Trino cluster. Designed for data engineers, analysts, and data pla
  name: Trino SQL Analytics
  slug: sql-analytics
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/trinodb
- title: ''
  type: PythonSDK
  url: https://github.com/trinodb/trino-python-client
- title: ''
  type: GoSDK
  url: https://github.com/trinodb/trino-go-client
- title: ''
  type: JavaScriptSDK
  url: https://github.com/trinodb/trino-js-client
- title: ''
  type: HelmChart
  url: https://github.com/trinodb/charts
- title: ''
  type: CLI
  url: https://github.com/trinodb/trino-admin
- title: ''
  type: JSONLDContext
  url: json-ld/trino-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/trino-query-results-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/trino-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/trino-rules.yml
- title: ''
  type: Website
  url: https://trino.io/
- title: ''
  type: Documentation
  url: https://trino.io/docs/current/
- title: ''
  type: Security
  url: https://trino.io/docs/current/security.html
- title: ''
  type: Glossary
  url: https://trino.io/docs/current/glossary.html
- title: ''
  type: ChangeLog
  url: https://trino.io/docs/current/release.html
- title: ''
  type: GettingStarted
  url: https://trino.io/download
- title: ''
  type: Events
  url: https://trino.io/community#events
- title: ''
  type: Blog
  url: https://trino.io/blog/
- title: ''
  type: Discussions
  url: https://trino.io/community
created: '2025-06-05'
description: Trino is an open-source, distributed SQL query engine built for lightning-fast analytics over large, heterogeneous data sets. Originally forked from Presto (which emerged at Facebook), it supports ANSI-compliant SQL across a wide range of storage systems from data lakes (S3, HDFS, Iceberg) to relational and NoSQL databases (MySQL, PostgreSQL, Cassandra, MongoDB, Elasticsearch, Kafka, and more).
features:
- name: C# Client Driver
- name: Go Client Driver
- name: JDBC
- name: ODBC
- name: Python Client Driver
- name: Elixir Client Driver
- name: Simba JDBC Client Driver
- name: R Client Driver
- name: Ruby Client Driver
- name: Rust Client Driver
- name: Command Line Interface
- name: Grafana
- name: Apache Airflow
- name: Apache DolphinScheduler
- name: Coginiti
- name: Cube
- name: DBeaver
- name: dbt
- name: DbVisualizer
- name: Emacs
- name: FugueSQL
- name: Great Expectations
- name: Harlequin
- name: Hue
- name: Ibis
- name: IBM Cognos Analytics
- name: JetBrains Datagrip
- name: Jupy SQL
- name: Logi Symphony
- name: Looker
- name: Metabase
- name: Microstrategy
- name: Mitzu
- name: Mode
- name: PopSQL
- name: Power BI
- name: Querybook
- name: Quix
- name: Redash
- name: SQuirrel SQL
- name: Tableau
- name: VSCode
- name: waii
- name: Wren AI
- name: yanagishima
- name: Zing Data
- name: Spill to disk
- name: Resource groups
- name: Session property managers
- name: Distributed sort
- name: Dynamic filtering
- name: Graceful shutdown
- name: Fault-tolerant execution
- name: HTTP event listener
- name: Kafka event listener
- name: MySQL event listener
- name: OpenLineage event listener
- name: Client protocol
- name: HTTP server
- name: Resource management
- name: Query management
- name: Catalog management
- name: SQL environment
- name: Spilling
- name: Exchange
- name: Task
- name: Write partitioning
- name: Writer scaling
- name: Node scheduler
- name: Optimizer
- name: Logging
- name: Web UI
- name: Regular expression function
- name: HTTP client
- name: Table statistics
- name: Cost in EXPLAIN
- name: Cost-based optimizations
- name: Pushdown
- name: Adaptive plan optimizations
- name: Amazon Redshift
- name: Apache Cassandra
- name: Apache Druid
- name: Apache Ignite
- name: Apache Kafka
- name: Apache Pinot
- name: Clickhouse
- name: Datafaker
- name: Elasticsearch
- name: Exasol
- name: Google BigQuery
- name: Google Sheets
- name: MariaDB
- name: Microsoft SQL Server
- name: MongoDB
- name: MySQL
- name: OpenSearch
- name: Oracle
- name: PostgreSQL
- name: Prometheus
- name: Redis
- name: SingleStore
- name: Snowflake
- name: TPC
- name: Vertica
- name: Amazon Kinesis
- name: Apache Accumulo
- name: Apache Kudu
- name: Apache Phoenix
- name: Git
- name: OpenAPI
- name: VAST
- name: JMX
- name: Kubernetes
- name: OpenLineage
- name: Open Policy Agent
- name: OpenTelemetry
- name: Trino Gateway
- name: Datadog
- name: Gurubase
- name: jOOQ
- name: Minitrino
- name: RudderStack
- name: SQL Formatter
- name: Testcontainers
- name: Trino-lb
- name: Workload Analyzer
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: BigQuery
- name: Black Hole
- name: Cassandra
- name: ClickHouse
- name: Delta Lake
- name: Druid
- name: DuckDB
- name: Elasticsearch
- name: Exasol
- name: Faker
- name: Google Sheets
- name: Hive
- name: Hudi
- name: Iceberg
- name: Ignite
- name: JMX
- name: Kafka
- name: Loki
- name: MariaDB
- name: Memory
- name: MongoDB
- name: MySQL
- name: OpenSearch
- name: Oracle
- name: Pinot
- name: PostgreSQL
- name: Prometheus
- name: Redis
- name: Redshift
- name: SingleStore
- name: Snowflake
- name: SQL Server
- name: System
- name: Thrift
- name: TPC-DS
- name: TPC-H
- name: Vertica
jsonld:
- class_count: 25
  name: Trino Context
  property_count: 21
  slug: trino-context
layout: provider
modified: '2026-05-03'
name: Trino
rules:
- name: Trino API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 6
  slug: trino-rules
skills: []
slug: trino
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trino\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/trino/refs/heads/main/apis.yml\napis:\n  - aid: trino:trino-client-api\n    name: Trino Client REST API\n    tags:\n      - Analytics\n      - Big Data\n      - Queries\n      - SQL\n    humanURL: https://trino.io/docs/current/develop/client-protocol.html\n    baseURL: http://localhost:8080\n    properties:\n      - url: https://trino.io/docs/current/develop/client-protocol.html\n        type: Documentation\n      - url: openapi/trino-client-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Trino Client REST API enables clients to submit SQL queries to a Trino coordinator\n      and retrieve results. Clients POST SQL to /v1/statement, then poll GET on the returned\n      nextUri, and may DELETE nextUri to cancel. Used by all Trino client drivers (Python,\n      Go, Java, JavaScript) and data tools like dbt, Grafana, and Apache Superset.\nname: Trino\ntags:\n  - Analytics\n  - Big Data\n\
  \  - Distributed SQL\n  - MySQL\n  - NoSQL\n  - Queries\n  - SQL\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncommon:\n  - url: https://github.com/trinodb\n    name: GitHub Organization\n    type: GitHubOrganization\n  - url: https://github.com/trinodb/trino-python-client\n    name: Trino Python Client\n    type: PythonSDK\n  - url: https://github.com/trinodb/trino-go-client\n    name: Trino Go Client\n    type: GoSDK\n  - url: https://github.com/trinodb/trino-js-client\n    name: Trino JavaScript Client\n    type: JavaScriptSDK\n  - url: https://github.com/trinodb/charts\n    name: Trino Helm Charts\n    type: HelmChart\n  - url: https://github.com/trinodb/trino-admin\n    name: Trino Admin Tool\n    type: CLI\n  - url: json-ld/trino-context.jsonld\n    name: Trino JSON-LD Context\n    type: JSONLDContext\n  - url: json-schema/trino-query-results-schema.json\n    name: Trino Query Results Schema\n    type: JSONSchema\n  - url: vocabulary/trino-vocabulary.yml\n\
  \    name: Trino Vocabulary\n    type: Vocabulary\n  - url: rules/trino-rules.yml\n    name: Trino Spectral Rules\n    type: SpectralRules\n  - url: https://trino.io/\n    name: \"Trino | Distributed SQL query engine for big data\"\n    type: Website\n    description: 'null'\n  - url: https://trino.io/docs/current/\n    name: Trino documentation  Trino 476 Documentation\n    type: Documentation\n    description: 'null'\n  - url: https://trino.io/docs/current/security.html\n    name: Security  Trino 476 Documentation\n    type: Security\n    description: 'null'\n  - url: https://trino.io/docs/current/connector.html\n    name: Connectors  Trino 476 Documentation\n    type: Integrations\n    description: 'null'\n  - url: https://trino.io/docs/current/glossary.html\n    name: Glossary  Trino 476 Documentation\n    type: Glossary\n    description: 'null'\n  - url: https://trino.io/docs/current/release.html\n    name: Release notes  Trino 476 Documentation\n    type: ChangeLog\n    description:\
  \ 'null'\n  - url: https://trino.io/download\n    name: \"Trino | Get started with Trino\"\n    type: GettingStarted\n    description: 'null'\n  - url: https://trino.io/community#events\n    name: \"Trino | Trino Community\"\n    type: Events\n    description: 'null'\n  - url: https://trino.io/blog/\n    name: Trino | Trino blog\n    type: Blog\n    description: 'null'\n  - url: https://trino.io/community\n    name: \"Trino | Trino Community\"\n    type: Discussions\n    description: 'null'\n  - name: Features\n    type: Features\n    data:\n      - name: C# Client Driver\n      - name: Go Client Driver\n      - name: JDBC\n      - name: ODBC\n      - name: Python Client Driver\n      - name: Elixir Client Driver\n      - name: Simba JDBC Client Driver\n      - name: R Client Driver\n      - name: Ruby Client Driver\n      - name: Rust Client Driver\n      - name: Command Line Interface\n      - name: Grafana\n      - name: Apache Airflow\n      - name: Apache DolphinScheduler\n      -\
  \ name: Coginiti\n      - name: Cube\n      - name: DBeaver\n      - name: dbt\n      - name: DbVisualizer\n      - name: Emacs\n      - name: FugueSQL\n      - name: Great Expectations\n      - name: Harlequin\n      - name: Hue\n      - name: Ibis\n      - name: IBM Cognos Analytics\n      - name: JetBrains Datagrip\n      - name: Jupy SQL\n      - name: Logi Symphony\n      - name: Looker\n      - name: Metabase\n      - name: Microstrategy\n      - name: Mitzu\n      - name: Mode\n      - name: PopSQL\n      - name: Power BI\n      - name: Querybook\n      - name: Quix\n      - name: Redash\n      - name: SQuirrel SQL\n      - name: Tableau\n      - name: VSCode\n      - name: waii\n      - name: Wren AI\n      - name: yanagishima\n      - name: Zing Data\n      - name: Spill to disk\n      - name: Resource groups\n      - name: Session property managers\n      - name: Distributed sort\n      - name: Dynamic filtering\n      - name: Graceful shutdown\n      - name: Fault-tolerant execution\n\
  \      - name: HTTP event listener\n      - name: Kafka event listener\n      - name: MySQL event listener\n      - name: OpenLineage event listener\n      - name: Client protocol\n      - name: HTTP server\n      - name: Resource management\n      - name: Query management\n      - name: Catalog management\n      - name: SQL environment\n      - name: Spilling\n      - name: Exchange\n      - name: Task\n      - name: Write partitioning\n      - name: Writer scaling\n      - name: Node scheduler\n      - name: Optimizer\n      - name: Logging\n      - name: Web UI\n      - name: Regular expression function\n      - name: HTTP client\n      - name: Table statistics\n      - name: Cost in EXPLAIN\n      - name: Cost-based optimizations\n      - name: Pushdown\n      - name: Adaptive plan optimizations\n      - name: Amazon Redshift\n      - name: Apache Cassandra\n      - name: Apache Druid\n      - name: Apache Ignite\n      - name: Apache Kafka\n      - name: Apache Pinot\n      - name:\
  \ Clickhouse\n      - name: Datafaker\n      - name: Elasticsearch\n      - name: Exasol\n      - name: Google BigQuery\n      - name: Google Sheets\n      - name: MariaDB\n      - name: Microsoft SQL Server\n      - name: MongoDB\n      - name: MySQL\n      - name: OpenSearch\n      - name: Oracle\n      - name: PostgreSQL\n      - name: Prometheus\n      - name: Redis\n      - name: SingleStore\n      - name: Snowflake\n      - name: TPC\n      - name: Vertica\n      - name: Amazon Kinesis\n      - name: Apache Accumulo\n      - name: Apache Kudu\n      - name: Apache Phoenix\n      - name: Git\n      - name: OpenAPI\n      - name: VAST\n      - name: JMX\n      - name: Kubernetes\n      - name: OpenLineage\n      - name: Open Policy Agent\n      - name: OpenTelemetry\n      - name: Trino Gateway\n      - name: Datadog\n      - name: Gurubase\n      - name: jOOQ\n      - name: Minitrino\n      - name: RudderStack\n      - name: SQL Formatter\n      - name: Testcontainers\n      - name:\
  \ Trino-lb\n      - name: Workload Analyzer\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: BigQuery\n      - name: Black Hole\n      - name: Cassandra\n      - name: ClickHouse\n      - name: Delta Lake\n      - name: Druid\n      - name: DuckDB\n      - name: Elasticsearch\n      - name: Exasol\n      - name: Faker\n      - name: Google Sheets\n      - name: Hive\n      - name: Hudi\n      - name: Iceberg\n      - name: Ignite\n      - name: JMX\n      - name: Kafka\n      - name: Loki\n      - name: MariaDB\n      - name: Memory\n      - name: MongoDB\n      - name: MySQL\n      - name: OpenSearch\n      - name: Oracle\n      - name: Pinot\n      - name: PostgreSQL\n      - name: Prometheus\n      - name: Redis\n      - name: Redshift\n      - name: SingleStore\n      - name: Snowflake\n      - name: SQL Server\n      - name: System\n      - name: Thrift\n      - name: TPC-DS\n      - name: TPC-H\n      - name: Vertica\ncreated: '2025-06-05'\nmodified: '2026-05-03'\n\
  description: >-\n  Trino is an open-source, distributed SQL query engine built for lightning-fast analytics\n  over large, heterogeneous data sets. Originally forked from Presto (which emerged\n  at Facebook), it supports ANSI-compliant SQL across a wide range of storage systems from\n  data lakes (S3, HDFS, Iceberg) to relational and NoSQL databases (MySQL, PostgreSQL,\n  Cassandra, MongoDB, Elasticsearch, Kafka, and more).\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trino/refs/heads/main/apis.yml
tags:
- Analytics
- Big Data
- Distributed SQL
- MySQL
- NoSQL
- Queries
- SQL
url: https://raw.githubusercontent.com/api-evangelist/trino/refs/heads/main/apis.yml
use_cases: []
---
