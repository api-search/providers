---
api_count: 2
apis:
- description: Open Database Connectivity (ODBC) is a standard C-language API for accessing database management systems. ODBC allows applications to connect to any ODBC-compliant database using a unified programming
  name: ODBC API
  slug: ''
- description: Java Database Connectivity (JDBC) is the standard Java API for connecting Java applications to relational databases. JDBC provides a uniform interface for executing SQL queries, managing transactions,
  name: JDBC API
  slug: ''
common:
- title: ''
  type: JSONSchema
  url: json-schema/sql-query-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sql-result-schema.json
- title: ''
  type: JSONLD
  url: json-ld/sql-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/sql-vocabulary.yml
- title: ''
  type: ISO Standard
  url: https://www.iso.org/standard/76583.html
- title: ''
  type: ANSI Standard
  url: https://www.ansi.org/
- title: ''
  type: Wikipedia
  url: https://en.wikipedia.org/wiki/SQL
- title: ''
  type: W3Schools Tutorial
  url: https://www.w3schools.com/sql/
- title: ''
  type: MDN Web Docs
  url: https://developer.mozilla.org/en-US/docs/Learn/Server-side/SQL
created: '2026-05-02'
description: SQL (Structured Query Language) is the ANSI/ISO standard language for managing and querying relational databases. SQL defines the interface for creating, reading, updating, and deleting data in relational database management systems (RDBMS). Database connectivity standards including ODBC (Open Database Connectivity) and JDBC (Java Database Connectivity) expose SQL capabilities as programmatic APIs, enabling applications to connect to and interact with SQL-compliant databases. Major implementations include MySQL, PostgreSQL, Microsoft SQL Server, Oracle, SQLite, and many others.
features: []
image: https://upload.wikimedia.org/wikipedia/commons/8/87/Sql_data_base_with_logo.png
integrations: []
jsonld:
- class_count: 17
  name: Sql Context
  property_count: 6
  slug: sql-context
layout: provider
modified: '2026-05-02'
name: SQL
skills: []
slug: sql
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sql\nname: SQL\ndescription: >-\n  SQL (Structured Query Language) is the ANSI/ISO standard language for managing\n  and querying relational databases. SQL defines the interface for creating,\n  reading, updating, and deleting data in relational database management systems\n  (RDBMS). Database connectivity standards including ODBC (Open Database Connectivity)\n  and JDBC (Java Database Connectivity) expose SQL capabilities as programmatic APIs,\n  enabling applications to connect to and interact with SQL-compliant databases.\n  Major implementations include MySQL, PostgreSQL, Microsoft SQL Server, Oracle,\n  SQLite, and many others.\nimage: https://upload.wikimedia.org/wikipedia/commons/8/87/Sql_data_base_with_logo.png\nurl: https://www.iso.org/standard/76583.html\ncreated: '2026-05-02'\nmodified: '2026-05-02'\napis:\n  - name: ODBC API\n    description: >-\n      Open Database Connectivity (ODBC) is a standard C-language API for accessing\n      database management systems.\
  \ ODBC allows applications to connect to any\n      ODBC-compliant database using a unified programming interface, abstracting\n      database-specific details through drivers. Originally developed by Microsoft\n      and standardized by ISO/IEC in SQL/CLI (Call Level Interface).\n    humanUrl: https://learn.microsoft.com/en-us/sql/odbc/reference/odbc-programmer-s-reference\n    baseUrl: ''\n    tags:\n      - Database Connectivity\n      - ODBC\n      - Standard\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/odbc/reference/odbc-programmer-s-reference\n      - type: Wikipedia\n        url: https://en.wikipedia.org/wiki/Open_Database_Connectivity\n      - type: Specification\n        url: https://www.iso.org/standard/53681.html\n  - name: JDBC API\n    description: >-\n      Java Database Connectivity (JDBC) is the standard Java API for connecting\n      Java applications to relational databases. JDBC provides a uniform interface\n    \
  \  for executing SQL queries, managing transactions, and retrieving results,\n      regardless of the underlying database system. It is part of the Java SE\n      standard library.\n    humanUrl: https://docs.oracle.com/en/java/javase/21/docs/api/java.sql/java/sql/package-summary.html\n    baseUrl: ''\n    tags:\n      - Database Connectivity\n      - Java\n      - JDBC\n      - Standard\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/java/javase/21/docs/api/java.sql/java/sql/package-summary.html\n      - type: Wikipedia\n        url: https://en.wikipedia.org/wiki/Java_Database_Connectivity\n      - type: Specification\n        url: https://jcp.org/en/jsr/detail?id=221\ncommon:\n  - type: JSONSchema\n    url: json-schema/sql-query-schema.json\n  - type: JSONSchema\n    url: json-schema/sql-result-schema.json\n  - type: JSONLD\n    url: json-ld/sql-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/sql-vocabulary.yml\n  - type: ISO Standard\n\
  \    url: https://www.iso.org/standard/76583.html\n  - type: ANSI Standard\n    url: https://www.ansi.org/\n  - type: Wikipedia\n    url: https://en.wikipedia.org/wiki/SQL\n  - type: W3Schools Tutorial\n    url: https://www.w3schools.com/sql/\n  - type: MDN Web Docs\n    url: https://developer.mozilla.org/en-US/docs/Learn/Server-side/SQL\nmaintainers:\n  - name: ISO/IEC JTC 1/SC 32\n    url: https://www.iso.org/committee/45342.html\ntags:\n  - ANSI Standard\n  - Data Management\n  - Database\n  - ISO Standard\n  - Query Language\n  - Relational Database\n  - SQL\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sql/refs/heads/main/apis.yml
tags:
- ANSI Standard
- Data Management
- Database
- ISO Standard
- Query Language
- Relational Database
- SQL
url: https://www.iso.org/standard/76583.html
use_cases: []
---
