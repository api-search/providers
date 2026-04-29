---
api_count: 1
apis:
- description: Derby provides a standard JDBC API for database operations in both embedded (org.apache.derby.jdbc.EmbeddedDriver) and client/server (org.apache.derby.jdbc.ClientDriver) modes, supporting full SQL, st
  name: Apache Derby
  slug: apache-derby
common:
- title: ''
  type: Portal
  url: https://db.apache.org/derby/
- title: ''
  type: Documentation
  url: https://db.apache.org/derby/manuals/index.html
- title: ''
  type: GettingStarted
  url: https://db.apache.org/derby/quick_start.html
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/derby
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/apache-derby
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/vocabulary/apache-derby-vocabulary.yaml
created: '2026-03-16'
description: Apache Derby is an open-source relational database implemented entirely in Java, formerly governed by the Apache Software Foundation (retired October 2025). It provides a small-footprint (~3.5MB) database engine with full SQL support, JDBC compliance, ACID transactions, stored procedures, and triggers. Derby operates in both embedded mode (bundled inside Java applications) and client/server mode via the Derby Network Server.
features:
- description: Derby can be embedded directly in Java applications as a library, providing a zero-administration database with no separate server process required.
  name: Embedded Mode
- description: Derby Network Server supports multiple concurrent JDBC clients connecting over TCP/IP using the Derby Network Client driver.
  name: Client/Server Mode
- description: Supports ANSI SQL-92 with extensions including subqueries, joins, constraints, triggers, views, stored procedures, and user-defined functions.
  name: Full SQL Support
- description: Full ACID transaction support with row-level locking, MVCC-style isolation levels, and savepoints.
  name: ACID Transactions
- description: The base Derby engine and embedded JDBC driver is approximately 3.5MB, making it suitable for desktop and embedded applications.
  name: Small Footprint
- description: Supports Java-based stored procedures and functions callable directly from SQL using standard JDBC interfaces.
  name: Java Stored Procedures
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Derby provides JDBC 4.0/4.1/4.2 compliant embedded and network client drivers.
  name: JDBC
- description: Commonly used with Spring DataSource and JPA/Hibernate for test database configuration.
  name: Spring Framework
- description: Derby has a Hibernate dialect (DerbyDialect) for ORM integration.
  name: Hibernate / JPA
- description: Derby artifacts are available on Maven Central under org.apache.derby group ID.
  name: Apache Maven
- description: Eclipse IDE includes Derby as a built-in SQL explorer and development database.
  name: Eclipse IDE
jsonld:
- class_count: 2
  name: Apache Derby Context
  property_count: 15
  slug: apache-derby-context
layout: provider
modified: '2026-04-19'
name: Apache Derby
skills: []
slug: apache-derby
solutions: []
source_yaml: "aid: apache-derby\nname: Apache Derby\ndescription: >-\n  Apache Derby is an open-source relational database implemented entirely in Java, formerly governed by the Apache Software Foundation (retired October 2025). It provides a small-footprint (~3.5MB) database\n  engine with full SQL support, JDBC compliance, ACID transactions, stored procedures, and triggers. Derby operates in both embedded mode (bundled inside Java applications) and client/server mode via the\n  Derby Network Server.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Apache\n- Database\n- Embedded\n- Java\n- JDBC\n- Open Source\n- Relational\n- SQL\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-derby:apache-derby\n  name: Apache Derby\n  description: >-\n    Derby\
  \ provides a standard JDBC API for database operations in both embedded (org.apache.derby.jdbc.EmbeddedDriver) and client/server (org.apache.derby.jdbc.ClientDriver) modes, supporting full SQL,\n    stored procedures, triggers, views, indexes, and complete ACID transaction management. The Derby Network Server also exposes a simple text-based administrative protocol.\n  humanURL: https://db.apache.org/derby/manuals/index.html\n  tags:\n  - Embedded\n  - Java\n  - JDBC\n  - Network Server\n  - SQL\n  - Transactions\n  properties:\n  - type: Documentation\n    url: https://db.apache.org/derby/manuals/index.html\n  - type: GettingStarted\n    url: https://db.apache.org/derby/quick_start.html\n  - type: APIReference\n    url: https://db.apache.org/derby/javadoc/publishedapi/jdbc4/\n  - type: GitHubRepository\n    url: https://github.com/apache/derby\n  - type: SDK\n    url: https://mvnrepository.com/artifact/org.apache.derby/derby\n    title: derby (Maven Central)\n  - type: SDK\n    url: https://mvnrepository.com/artifact/org.apache.derby/derbyclient\n\
  \    title: derbyclient (Maven Central)\n  - type: SDK\n    url: https://mvnrepository.com/artifact/org.apache.derby/derbynet\n    title: derbynet Network Server (Maven Central)\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/json-schema/apache-derby-connection-config-schema.json\n    title: Connection Config\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/json-schema/apache-derby-table-info-schema.json\n    title: Table Info\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/json-structure/apache-derby-connection-config-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/json-structure/apache-derby-table-info-structure.json\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/json-ld/apache-derby-context.jsonld\n\
  \  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/examples/apache-derby-connection-config-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/examples/apache-derby-table-info-example.json\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: Portal\n  url: https://db.apache.org/derby/\n- type: Documentation\n  url: https://db.apache.org/derby/manuals/index.html\n- type: GettingStarted\n  url: https://db.apache.org/derby/quick_start.html\n- type: GitHubRepository\n  url: https://github.com/apache/derby\n- type: GitHubOrganization\n  url: https://github.com/apache\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/apache-derby\n- type: Features\n  data:\n  - name: Embedded Mode\n    description: Derby can be embedded directly in Java applications as a library, providing a zero-administration database with no separate\
  \ server process required.\n  - name: Client/Server Mode\n    description: Derby Network Server supports multiple concurrent JDBC clients connecting over TCP/IP using the Derby Network Client driver.\n  - name: Full SQL Support\n    description: Supports ANSI SQL-92 with extensions including subqueries, joins, constraints, triggers, views, stored procedures, and user-defined functions.\n  - name: ACID Transactions\n    description: Full ACID transaction support with row-level locking, MVCC-style isolation levels, and savepoints.\n  - name: Small Footprint\n    description: The base Derby engine and embedded JDBC driver is approximately 3.5MB, making it suitable for desktop and embedded applications.\n  - name: Java Stored Procedures\n    description: Supports Java-based stored procedures and functions callable directly from SQL using standard JDBC interfaces.\n- type: UseCases\n  data:\n  - name: Embedded Application Database\n    description: Embed Derby in desktop Java applications,\
  \ IDEs, or tools that need a local SQL database without a separate server.\n  - name: Unit and Integration Testing\n    description: Use Derby as an in-memory or on-disk test database for Java application integration tests with JDBC.\n  - name: Lightweight Development Database\n    description: Use Derby as a development database when production uses a heavier RDBMS, without installing MySQL or PostgreSQL.\n  - name: Data Migration and ETL\n    description: Use Derby as a staging database for ETL processes in Java-based data pipelines.\n- type: Integrations\n  data:\n  - name: JDBC\n    description: Derby provides JDBC 4.0/4.1/4.2 compliant embedded and network client drivers.\n  - name: Spring Framework\n    description: Commonly used with Spring DataSource and JPA/Hibernate for test database configuration.\n  - name: Hibernate / JPA\n    description: Derby has a Hibernate dialect (DerbyDialect) for ORM integration.\n  - name: Apache Maven\n    description: Derby artifacts are available\
  \ on Maven Central under org.apache.derby group ID.\n  - name: Eclipse IDE\n    description: Eclipse IDE includes Derby as a built-in SQL explorer and development database.\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/vocabulary/apache-derby-vocabulary.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/apis.yml
tags:
- Apache
- Database
- Embedded
- Java
- JDBC
- Open Source
- Relational
- SQL
url: https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/apis.yml
use_cases:
- description: Embed Derby in desktop Java applications, IDEs, or tools that need a local SQL database without a separate server.
  name: Embedded Application Database
- description: Use Derby as an in-memory or on-disk test database for Java application integration tests with JDBC.
  name: Unit and Integration Testing
- description: Use Derby as a development database when production uses a heavier RDBMS, without installing MySQL or PostgreSQL.
  name: Lightweight Development Database
- description: Use Derby as a staging database for ETL processes in Java-based data pipelines.
  name: Data Migration and ETL
---
