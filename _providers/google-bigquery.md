---
api_count: 5
api_specs:
- filename: bigquery-api-openapi.yml
  format: yaml
  label: BigQuery API
  slug: bigquery
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-bigquery/refs/heads/main/openapi/bigquery-api-openapi.yml
apis:
- description: The BigQuery API provides programmatic access to Google BigQuery for creating, managing, and querying datasets, tables, jobs, and other BigQuery resources. Developers can use the API to load data, run
  name: BigQuery API
  slug: bigquery
- description: The BigQuery Connection API enables developers to create and manage connections between BigQuery and external data sources such as Cloud SQL, Cloud Spanner, and other databases. These connections allo
  name: BigQuery Connection API
  slug: bigquery-connection
- description: 'The BigQuery Migration API provides tools for migrating data warehouse workloads to BigQuery from other platforms. It supports assessment and planning of migration tasks, translation of SQL dialects, '
  name: BigQuery Migration API
  slug: bigquery-migration
- description: The BigQuery Reservation API allows developers to manage slot reservations and capacity commitments for BigQuery compute resources. It provides programmatic control over how compute capacity is alloca
  name: BigQuery Reservation API
  slug: bigquery-reservation
- description: 'The BigQuery Storage API provides high-throughput read and write access to BigQuery managed storage. It enables developers to read data from BigQuery tables using an efficient streaming protocol that '
  name: BigQuery Storage API
  slug: bigquery-storage
common:
- title: ''
  type: Getting Started
  url: https://cloud.google.com/bigquery/docs/quickstarts
- title: ''
  type: Pricing
  url: https://cloud.google.com/bigquery/pricing
- title: ''
  type: Authentication
  url: https://cloud.google.com/bigquery/docs/authentication
- title: ''
  type: Console
  url: https://console.cloud.google.com/bigquery
- title: ''
  type: CLI
  url: https://cloud.google.com/bigquery/docs/reference/bq-cli-reference
- title: ''
  type: SDKs
  url: https://cloud.google.com/bigquery/docs/reference/libraries
- title: ''
  type: Support
  url: https://cloud.google.com/bigquery/docs/support
- title: ''
  type: Status
  url: https://status.cloud.google.com
- title: ''
  type: JSON-LD
  url: json-ld/google-bigquery-context.jsonld
created: '2026-03-13'
description: Google BigQuery is a fully managed, serverless data warehouse that enables scalable analysis over petabytes of data using SQL.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Google Bigquery Context
  property_count: 5
  slug: google-bigquery-context
layout: provider
modified: '2026-04-28'
name: Google BigQuery
skills: []
slug: google-bigquery
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-bigquery\nname: Google BigQuery\ndescription: Google BigQuery is a fully managed, serverless data warehouse that enables scalable analysis over petabytes of data using SQL.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/google-bigquery/refs/heads/main/apis.yml\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Analytics\n  - Big Data\n  - Cloud\n  - Data Warehouse\n  - Serverless\n  - SQL\napis:\n  - aid: google-bigquery:bigquery\n    name: BigQuery API\n    description: >-\n      The BigQuery API provides programmatic access to Google BigQuery for creating,\n      managing, and querying datasets, tables, jobs, and other BigQuery resources.\n      Developers can use the API to load data, run queries, export results, and manage\n      access control on BigQuery resources. The API supports SQL-based analytics over\n      petabytes\
  \ of data with serverless infrastructure.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/bigquery/docs\n    baseURL: https://bigquery.googleapis.com\n    tags:\n      - Analytics\n      - Data Warehouse\n      - Datasets\n      - Queries\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/bigquery/docs/reference/rest\n      - type: OpenAPI\n        url: openapi/bigquery-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/google-bigquery-query-schema.json\n      - type: JSONSchema\n        url: json-schema/google-bigquery-table-schema.json\n  - aid: google-bigquery:bigquery-connection\n    name: BigQuery Connection API\n    description: >-\n      The BigQuery Connection API enables developers to create and manage connections\n      between BigQuery and external data sources such as Cloud SQL, Cloud Spanner, and\n      other databases. These connections\
  \ allow BigQuery to query data in external sources\n      without moving or copying data. The API supports creating, updating, deleting,\n      and listing connections as well as managing IAM policies on connections.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/bigquery/docs/reference/bigqueryconnection/rest\n    baseURL: https://bigqueryconnection.googleapis.com\n    tags:\n      - Connections\n      - External Data\n      - Federation\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/bigquery/docs/reference/bigqueryconnection/rest\n  - aid: google-bigquery:bigquery-migration\n    name: BigQuery Migration API\n    description: >-\n      The BigQuery Migration API provides tools for migrating data warehouse workloads\n      to BigQuery from other platforms. It supports assessment and planning of migration\n      tasks, translation of SQL dialects, and orchestration of migration\
  \ workflows. The\n      API helps enterprises move their analytics workloads to BigQuery with automated\n      tooling and migration tracking.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/bigquery/docs/reference/migration/rest\n    baseURL: https://bigquerymigration.googleapis.com\n    tags:\n      - Data Migration\n      - Migration\n      - SQL Translation\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/bigquery/docs/reference/migration/rest\n  - aid: google-bigquery:bigquery-reservation\n    name: BigQuery Reservation API\n    description: >-\n      The BigQuery Reservation API allows developers to manage slot reservations and\n      capacity commitments for BigQuery compute resources. It provides programmatic\n      control over how compute capacity is allocated across projects and organizations,\n      enabling cost optimization and workload management. The API supports\
  \ creating\n      reservations, managing assignments, and purchasing capacity commitments.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/bigquery/docs/reference/reservations/rest\n    baseURL: https://bigqueryreservation.googleapis.com\n    tags:\n      - Capacity\n      - Compute\n      - Reservations\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/bigquery/docs/reference/reservations/rest\n  - aid: google-bigquery:bigquery-storage\n    name: BigQuery Storage API\n    description: >-\n      The BigQuery Storage API provides high-throughput read and write access to BigQuery\n      managed storage. It enables developers to read data from BigQuery tables using an\n      efficient streaming protocol that is significantly faster than the traditional\n      tabledata.list method. The API supports parallel reads, column filtering, and row\n      filtering to optimize data transfer\
  \ performance.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/bigquery/docs/reference/storage\n    baseURL: https://bigquerystorage.googleapis.com\n    tags:\n      - High Throughput\n      - Storage\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/bigquery/docs/reference/storage\ncommon:\n  - type: Getting Started\n    url: https://cloud.google.com/bigquery/docs/quickstarts\n  - type: Pricing\n    url: https://cloud.google.com/bigquery/pricing\n  - type: Authentication\n    url: https://cloud.google.com/bigquery/docs/authentication\n  - type: Console\n    url: https://console.cloud.google.com/bigquery\n  - type: CLI\n    url: https://cloud.google.com/bigquery/docs/reference/bq-cli-reference\n  - type: SDKs\n    url: https://cloud.google.com/bigquery/docs/reference/libraries\n  - type: Support\n    url: https://cloud.google.com/bigquery/docs/support\n \
  \ - type: Status\n    url: https://status.cloud.google.com\n  - type: JSON-LD\n    url: json-ld/google-bigquery-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-bigquery/refs/heads/main/apis.yml
tags:
- Analytics
- Big Data
- Cloud
- Data Warehouse
- Serverless
- SQL
url: https://raw.githubusercontent.com/api-evangelist/google-bigquery/refs/heads/main/apis.yml
use_cases: []
---
