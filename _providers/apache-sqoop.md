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
