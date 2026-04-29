---
api_count: 1
apis:
- description: Apache Sqoop provides a command-line interface for bulk data transfer between Hadoop and relational databases. Commands include sqoop-import for loading data into HDFS or Hive, sqoop-export for writin
  name: Apache Sqoop CLI
  slug: apache-sqoop-cli
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/sqoop
- title: ''
  type: Documentation
  url: https://sqoop.apache.org/docs/1.4.7/
- title: ''
  type: Portal
  url: https://sqoop.apache.org/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
created: '2026-03-16'
description: 'Apache Sqoop is a command-line tool designed for efficiently transferring bulk data between Apache Hadoop and structured data stores such as relational databases. It supports parallel import and export of data, incremental loads, and direct database connectors for MySQL, PostgreSQL, Oracle, SQL Server, and DB2. Note: Apache Sqoop has been retired to the Apache Attic as of 2021. Users are encouraged to migrate to Apache Spark or Apache NiFi.'
features:
- description: High-throughput parallel import from RDBMS to HDFS, Hive, or HBase.
  name: Bulk Import
- description: Export data from HDFS back to relational database tables.
  name: Bulk Export
- description: Delta-based incremental loading using append or lastmodified strategies.
  name: Incremental Loads
- description: Native database utility-based transfers for MySQL and PostgreSQL.
  name: Direct Import Mode
- description: Auto-create Hive tables and load imported data directly into Hive.
  name: Hive Integration
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Primary target storage for Sqoop imports via HDFS.
  name: Apache Hadoop
- description: Create and populate Hive tables from RDBMS imports.
  name: Apache Hive
- description: MySQL JDBC and direct mysqldump-based connector.
  name: MySQL
- description: Oracle JDBC connector for enterprise database data transfer.
  name: Oracle
layout: provider
modified: '2026-04-19'
name: Apache Sqoop
skills: []
slug: apache-sqoop
solutions: []
source_yaml: "aid: apache-sqoop\nname: Apache Sqoop\ndescription: >-\n  Apache Sqoop is a command-line tool designed for efficiently transferring bulk data between\n  Apache Hadoop and structured data stores such as relational databases. It supports parallel\n  import and export of data, incremental loads, and direct database connectors for MySQL,\n  PostgreSQL, Oracle, SQL Server, and DB2. Note: Apache Sqoop has been retired to the Apache\n  Attic as of 2021. Users are encouraged to migrate to Apache Spark or Apache NiFi.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Big Data\n  - Data Transfer\n  - ETL\n  - Hadoop\n  - RDBMS\n  - Retired\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-sqoop/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-sqoop:apache-sqoop-cli\n    name: Apache Sqoop CLI\n\
  \    description: >-\n      Apache Sqoop provides a command-line interface for bulk data transfer between Hadoop and\n      relational databases. Commands include sqoop-import for loading data into HDFS or Hive,\n      sqoop-export for writing Hadoop data back to RDBMS, sqoop-job for managing saved jobs, and\n      sqoop-eval for executing SQL statements. Sqoop 2 added a REST API server for job management.\n    humanURL: https://sqoop.apache.org/docs/1.4.7/SqoopUserGuide.html\n    tags:\n      - CLI\n      - Data Transfer\n      - ETL\n      - Hadoop\n      - RDBMS\n    properties:\n      - type: Documentation\n        url: https://sqoop.apache.org/docs/1.4.7/SqoopUserGuide.html\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/sqoop\n  - type: Documentation\n    url: https://sqoop.apache.org/docs/1.4.7/\n  - type: Portal\n    url: https://sqoop.apache.org/\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: Features\n    data:\n     \
  \ - name: Bulk Import\n        description: High-throughput parallel import from RDBMS to HDFS, Hive, or HBase.\n      - name: Bulk Export\n        description: Export data from HDFS back to relational database tables.\n      - name: Incremental Loads\n        description: Delta-based incremental loading using append or lastmodified strategies.\n      - name: Direct Import Mode\n        description: Native database utility-based transfers for MySQL and PostgreSQL.\n      - name: Hive Integration\n        description: Auto-create Hive tables and load imported data directly into Hive.\n  - type: UseCases\n    data:\n      - name: Data Warehouse Loading\n        description: Load relational database data into Hadoop-based data warehouses.\n      - name: Database Offloading\n        description: Move historical data from RDBMS to HDFS for cost-effective storage.\n  - type: Integrations\n    data:\n      - name: Apache Hadoop\n        description: Primary target storage for Sqoop imports via\
  \ HDFS.\n      - name: Apache Hive\n        description: Create and populate Hive tables from RDBMS imports.\n      - name: MySQL\n        description: MySQL JDBC and direct mysqldump-based connector.\n      - name: Oracle\n        description: Oracle JDBC connector for enterprise database data transfer.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-sqoop/refs/heads/main/apis.yml
tags:
- Big Data
- Data Transfer
- ETL
- Hadoop
- RDBMS
- Retired
url: https://raw.githubusercontent.com/api-evangelist/apache-sqoop/refs/heads/main/apis.yml
use_cases:
- description: Load relational database data into Hadoop-based data warehouses.
  name: Data Warehouse Loading
- description: Move historical data from RDBMS to HDFS for cost-effective storage.
  name: Database Offloading
---
