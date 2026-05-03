---
api_count: 6
api_specs:
- filename: oracle-database-19c-ords-openapi.yml
  format: yaml
  label: Oracle REST Data Services (ORDS)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-database-19c/refs/heads/main/openapi/oracle-database-19c-ords-openapi.yml
apis:
- description: RESTful web services for Oracle Database enabling HTTP access to database resources, SQL queries, and PL/SQL procedures.
  name: Oracle REST Data Services (ORDS)
  slug: ''
- description: Document-oriented NoSQL-style API for storing, retrieving, and querying JSON documents in Oracle Database.
  name: Oracle Database SODA (Simple Oracle Document Access)
  slug: ''
- description: Browser-based interface for Oracle Database providing SQL worksheet, data modeler, and database administration capabilities.
  name: Oracle SQL Developer Web
  slug: ''
- description: MongoDB-compatible API allowing MongoDB applications to connect to Oracle Database.
  name: Oracle Database API for MongoDB
  slug: ''
- description: RESTful API for managing JSON document collections with CRUD operations.
  name: Oracle Database JSON Collections API
  slug: ''
- description: REST APIs for Oracle Machine Learning AutoML capabilities including model building and deployment.
  name: Oracle Database REST API for AutoML
  slug: ''
common:
- title: ''
  type: Licensing
  url: https://www.oracle.com/database/technologies/database19c-license.html
- title: ''
  type: Security Alerts
  url: https://www.oracle.com/security-alerts/
- title: ''
  type: Support Portal
  url: https://support.oracle.com
- title: ''
  type: Community Forums
  url: https://community.oracle.com/tech/developers/categories/oracle-database
- title: ''
  type: Downloads
  url: https://www.oracle.com/database/technologies/oracle-database-software-downloads.html
- title: ''
  type: Pricing
  url: https://www.oracle.com/database/technologies/database-pricing.html
created: '2024-01-15'
description: Oracle Database 19c is a multi-model database management system that provides a comprehensive platform for enterprise data management, analytics, and application development.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 11
  name: Oracle Database 19C Context
  property_count: 14
  slug: oracle-database-19c-context
layout: provider
modified: '2026-04-28'
name: Oracle Database 19c
skills: []
slug: oracle-database-19c
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oracle-database-19c\nname: Oracle Database 19c\ndescription: >-\n  Oracle Database 19c is a multi-model database management system that provides\n  a comprehensive platform for enterprise data management, analytics, and\n  application development.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-database-19c/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - name: Oracle REST Data Services (ORDS)\n    description: >-\n      RESTful web services for Oracle Database enabling HTTP access to database\n      resources, SQL queries, and PL/SQL procedures.\n    image: https://www.oracle.com/a/ocom/img/sql.svg\n    humanURL: https://www.oracle.com/database/technologies/appdev/rest.html\n    baseURL: https://example.oracle.com:8443/ords/\n    tags:\n      - Database\n\
  \      - Oracle\n      - Rest\n      - Sql\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/19.2/\n      - type: API Reference\n        url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/19.2/orrst/\n      - type: Authentication\n        url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/19.2/orddg/developing-REST-applications.html\n      - type: OpenAPI\n        url: openapi/oracle-database-19c-ords-openapi.yml\n      - type: JSONLD\n        url: json-ld/oracle-database-19c-context.jsonld\n    contact:\n      - type: Support\n        url: https://support.oracle.com\n  - name: Oracle Database SODA (Simple Oracle Document Access)\n    description: >-\n      Document-oriented NoSQL-style API for storing, retrieving, and querying\n      JSON documents in Oracle Database.\n    image: https://www.oracle.com/a/ocom/img/sql.svg\n    humanURL: https://docs.oracle.com/en/database/oracle/simple-oracle-document-access/\n\
  \    baseURL: https://example.oracle.com:8443/ords/\n    tags:\n      - Document-Store\n      - Json\n      - Nosql\n      - Oracle\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/simple-oracle-document-access/rest/\n      - type: REST API Guide\n        url: https://docs.oracle.com/en/database/oracle/simple-oracle-document-access/rest/adrst/index.html\n      - type: Tutorial\n        url: https://oracle.github.io/json-in-db/\n      - type: JSONSchema\n        url: json-schema/oracle-database-19c-soda-collection.json\n      - type: JSONSchema\n        url: json-schema/oracle-database-19c-soda-document.json\n      - type: JSONLD\n        url: json-ld/oracle-database-19c-context.jsonld\n  - name: Oracle SQL Developer Web\n    description: >-\n      Browser-based interface for Oracle Database providing SQL worksheet,\n      data modeler, and database administration capabilities.\n    image: https://www.oracle.com/a/ocom/img/sql.svg\n\
  \    humanURL: https://www.oracle.com/database/technologies/appdev/sql-developer-web.html\n    baseURL: https://example.oracle.com:8443/ords/sql-developer/\n    tags:\n      - Administration\n      - Development\n      - Sql\n      - Web-Interface\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/sql-developer-web/\n      - type: Getting Started\n        url: https://docs.oracle.com/en/database/oracle/sql-developer-web/sdwad/\n  - name: Oracle Database API for MongoDB\n    description: >-\n      MongoDB-compatible API allowing MongoDB applications to connect to\n      Oracle Database.\n    image: https://www.oracle.com/a/ocom/img/sql.svg\n    humanURL: https://www.oracle.com/database/mongodb-api/\n    baseURL: mongodb://example.oracle.com:27017/\n    tags:\n      - Compatibility\n      - Document-Store\n      - Mongodb\n      - Nosql\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/mongodb-api/\n\
  \      - type: Quick Start\n        url: https://www.oracle.com/database/mongodb-api/quickstart.html\n  - name: Oracle Database JSON Collections API\n    description: >-\n      RESTful API for managing JSON document collections with CRUD operations.\n    image: https://www.oracle.com/a/ocom/img/sql.svg\n    humanURL: https://docs.oracle.com/en/database/oracle/oracle-database/19/adjsn/\n    baseURL: https://example.oracle.com:8443/ords/\n    tags:\n      - Collections\n      - Document-Api\n      - Json\n      - Rest\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/oracle-database/19/adjsn/json-collections.html\n      - type: Developer Guide\n        url: https://docs.oracle.com/en/database/oracle/oracle-database/19/adjsn/\n  - name: Oracle Database REST API for AutoML\n    description: >-\n      REST APIs for Oracle Machine Learning AutoML capabilities including\n      model building and deployment.\n    image: https://www.oracle.com/a/ocom/img/sql.svg\n\
  \    humanURL: https://docs.oracle.com/en/database/oracle/machine-learning/\n    baseURL: https://example.oracle.com:8443/omlmod/\n    tags:\n      - Ai\n      - Analytics\n      - Automl\n      - Machine-Learning\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/machine-learning/oml4sql/19/\n      - type: API Reference\n        url: https://docs.oracle.com/en/cloud/paas/autonomous-database/omlug/rest-endpoints.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Database\n  - Enterprise\n  - Json\n  - Machine-Learning\n  - Nosql\n  - Oracle\n  - Rest\n  - Sql\ninclude:\n  - name: Oracle Database Enterprise Edition Features\n    url: https://www.oracle.com/database/technologies/enterprise-edition.html\n  - name: Oracle Cloud Infrastructure\n    url: https://cloud.oracle.com/\ncommon:\n  - type: Licensing\n    url: https://www.oracle.com/database/technologies/database19c-license.html\n  - type: Security Alerts\n\
  \    url: https://www.oracle.com/security-alerts/\n  - type: Support Portal\n    url: https://support.oracle.com\n  - type: Community Forums\n    url: https://community.oracle.com/tech/developers/categories/oracle-database\n  - type: Downloads\n    url: https://www.oracle.com/database/technologies/oracle-database-software-downloads.html\n  - type: Pricing\n    url: https://www.oracle.com/database/technologies/database-pricing.html\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-database-19c/refs/heads/main/apis.yml
tags:
- Database
- Enterprise
- Json
- Machine-Learning
- Nosql
- Oracle
- Rest
- Sql
url: https://raw.githubusercontent.com/api-evangelist/oracle-database-19c/refs/heads/main/apis.yml
use_cases: []
---
