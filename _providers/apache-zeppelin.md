---
api_count: 1
apis:
- description: 'The Zeppelin REST API provides HTTP endpoints for managing notebooks, notes, paragraphs, interpreters, and credentials. Key endpoints include: GET/POST /api/notebook for notebook CRUD, GET/POST /api/n'
  name: Apache Zeppelin REST API
  slug: apache-zeppelin-rest-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/zeppelin
- title: ''
  type: Documentation
  url: https://zeppelin.apache.org/docs/latest/
- title: ''
  type: Portal
  url: https://zeppelin.apache.org/
- title: ''
  type: GettingStarted
  url: https://zeppelin.apache.org/docs/latest/quickstart/install.html
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/zeppelin/releases
- title: ''
  type: Support
  url: https://zeppelin.apache.org/community.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
created: '2026-03-16'
description: Apache Zeppelin is a web-based notebook that enables data-driven, interactive data analytics and collaborative documents with SQL, Scala, Python, R, and more. It provides built-in data visualization, collaboration features, and interpreter integration with Apache Spark, JDBC, Python, R, Shell, and 20+ other backends. Zeppelin exposes a REST API for notebook management, interpreter configuration, and job execution. It is maintained by the Apache Software Foundation.
features:
- description: Execute code in Scala, Python, R, SQL, Shell, and 20+ languages in the same notebook.
  name: Multi-Language Support
- description: Bar, line, pie, scatter, and map charts from query results without additional tools.
  name: Built-In Visualization
- description: Real-time collaborative editing of notebooks with user management and permissions.
  name: Collaborative Notebooks
- description: Native Apache Spark interpreter for Scala, Python (PySpark), and SQL queries.
  name: Spark Integration
- description: Universal JDBC interpreter for any SQL database including MySQL, PostgreSQL, Hive.
  name: JDBC Interpreter
- description: Schedule notebook paragraphs with cron expressions for automated execution.
  name: Paragraph Scheduling
- description: Interactive input forms within notebook paragraphs for parameterized execution.
  name: Dynamic Forms
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Spark interpreter for Scala, PySpark, and SparkSQL workloads.
  name: Apache Spark
- description: Hive JDBC and HiveQL interpreter for Hive data warehouse queries.
  name: Apache Hive
- description: Apache Flink interpreter for stream processing in Zeppelin notebooks.
  name: Apache Flink
- description: Zeppelin on Kubernetes with per-notebook pod isolation for interpreter processes.
  name: Kubernetes
- description: Elasticsearch interpreter for indexing and querying Elasticsearch data.
  name: Elasticsearch
layout: provider
modified: '2026-04-19'
name: Apache Zeppelin
skills: []
slug: apache-zeppelin
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-zeppelin\nname: Apache Zeppelin\ndescription: >-\n  Apache Zeppelin is a web-based notebook that enables data-driven, interactive data analytics\n  and collaborative documents with SQL, Scala, Python, R, and more. It provides built-in data\n  visualization, collaboration features, and interpreter integration with Apache Spark, JDBC,\n  Python, R, Shell, and 20+ other backends. Zeppelin exposes a REST API for notebook management,\n  interpreter configuration, and job execution. It is maintained by the Apache Software Foundation.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Analytics\n  - Interactive Computing\n  - Notebook\n  - Visualization\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-zeppelin/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-zeppelin:apache-zeppelin-rest-api\n\
  \    name: Apache Zeppelin REST API\n    description: >-\n      The Zeppelin REST API provides HTTP endpoints for managing notebooks, notes, paragraphs,\n      interpreters, and credentials. Key endpoints include: GET/POST /api/notebook for notebook\n      CRUD, GET/POST /api/notebook/{noteId}/paragraph for paragraph management, POST\n      /api/notebook/job/{noteId} for running all paragraphs, GET /api/interpreter/setting for\n      interpreter listing, and POST /api/interpreter/setting/restart for restarting interpreters.\n      Returns JSON responses with status codes.\n    humanURL: https://zeppelin.apache.org/docs/latest/usage/rest_api/notebook.html\n    tags:\n      - REST\n      - Notebooks\n      - Paragraphs\n      - Interpreter\n    properties:\n      - type: Documentation\n        url: https://zeppelin.apache.org/docs/latest/usage/rest_api/notebook.html\n      - type: Documentation\n        url: https://zeppelin.apache.org/docs/latest/usage/rest_api/interpreter.html\ncommon:\n\
  \  - type: GitHubRepository\n    url: https://github.com/apache/zeppelin\n  - type: Documentation\n    url: https://zeppelin.apache.org/docs/latest/\n  - type: Portal\n    url: https://zeppelin.apache.org/\n  - type: GettingStarted\n    url: https://zeppelin.apache.org/docs/latest/quickstart/install.html\n  - type: ReleaseNotes\n    url: https://github.com/apache/zeppelin/releases\n  - type: Support\n    url: https://zeppelin.apache.org/community.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: Features\n    data:\n      - name: Multi-Language Support\n        description: Execute code in Scala, Python, R, SQL, Shell, and 20+ languages in the same notebook.\n      - name: Built-In Visualization\n        description: Bar, line, pie, scatter, and map charts from query results without additional tools.\n      - name: Collaborative Notebooks\n        description: Real-time collaborative editing of notebooks with user management and permissions.\n      -\
  \ name: Spark Integration\n        description: Native Apache Spark interpreter for Scala, Python (PySpark), and SQL queries.\n      - name: JDBC Interpreter\n        description: Universal JDBC interpreter for any SQL database including MySQL, PostgreSQL, Hive.\n      - name: Paragraph Scheduling\n        description: Schedule notebook paragraphs with cron expressions for automated execution.\n      - name: Dynamic Forms\n        description: Interactive input forms within notebook paragraphs for parameterized execution.\n  - type: UseCases\n    data:\n      - name: Interactive Data Exploration\n        description: Exploratory data analysis with Spark SQL, Python, and R in a collaborative notebook.\n      - name: Data Science Prototyping\n        description: Rapid ML prototyping and model development with live results visualization.\n      - name: SQL Analytics\n        description: Interactive SQL queries against Hive, Spark SQL, or any JDBC database.\n      - name: Automated Reporting\n\
  \        description: Scheduled notebook execution for automated data report generation.\n  - type: Integrations\n    data:\n      - name: Apache Spark\n        description: Native Spark interpreter for Scala, PySpark, and SparkSQL workloads.\n      - name: Apache Hive\n        description: Hive JDBC and HiveQL interpreter for Hive data warehouse queries.\n      - name: Apache Flink\n        description: Apache Flink interpreter for stream processing in Zeppelin notebooks.\n      - name: Kubernetes\n        description: Zeppelin on Kubernetes with per-notebook pod isolation for interpreter processes.\n      - name: Elasticsearch\n        description: Elasticsearch interpreter for indexing and querying Elasticsearch data.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-zeppelin/refs/heads/main/apis.yml
tags:
- Data Analytics
- Interactive Computing
- Notebook
- Visualization
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-zeppelin/refs/heads/main/apis.yml
use_cases:
- description: Exploratory data analysis with Spark SQL, Python, and R in a collaborative notebook.
  name: Interactive Data Exploration
- description: Rapid ML prototyping and model development with live results visualization.
  name: Data Science Prototyping
- description: Interactive SQL queries against Hive, Spark SQL, or any JDBC database.
  name: SQL Analytics
- description: Scheduled notebook execution for automated data report generation.
  name: Automated Reporting
---
