---
api_count: 8
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Oracle REST Data Services (ORDS)
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/
- filename: openapi.yaml
  format: yaml
  label: Oracle Cloud Infrastructure Database API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/iaas/api/#/en/database/
- filename: oracle-database-soda-openapi.yml
  format: yaml
  label: Oracle SODA (Simple Oracle Document Access)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-database/refs/heads/main/openapi/oracle-database-soda-openapi.yml
- filename: oracle-database-txeventq-asyncapi.yml
  format: yaml
  label: Oracle Transactional Event Queues (TxEventQ)
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-database/refs/heads/main/asyncapi/oracle-database-txeventq-asyncapi.yml
apis:
- description: RESTful API development and data access for Oracle Database.
  name: Oracle REST Data Services (ORDS)
  slug: ''
- description: MongoDB-compatible API for Oracle Database.
  name: Oracle Database API for MongoDB
  slug: ''
- description: API for managing Oracle Database services in Oracle Cloud Infrastructure.
  name: Oracle Cloud Infrastructure Database API
  slug: ''
- description: Java Database Connectivity API for Oracle Database.
  name: Oracle Database JDBC
  slug: ''
- description: C/C++ API for Oracle Database access.
  name: Oracle Call Interface (OCI)
  slug: ''
- description: RESTful services for Oracle SQL Developer.
  name: Oracle SQL Developer REST API
  slug: ''
- description: NoSQL-style document API for Oracle Database.
  name: Oracle SODA (Simple Oracle Document Access)
  slug: ''
- description: Kafka-compatible event streaming and message queuing built into Oracle Database.
  name: Oracle Transactional Event Queues (TxEventQ)
  slug: ''
asyncapis:
- description: Oracle Transactional Event Queues provide Kafka-compatible event streaming and message queuing capabilities built into Oracle Database. TxEventQ enables event-driven architectures with transactional g
  name: Oracle Transactional Event Queues (TxEventQ) API
  slug: oracle-database-txeventq-asyncapi
common:
- title: ''
  type: Portal
  url: https://www.oracle.com/database/technologies/appdev.html
- title: ''
  type: Documentation
  url: https://docs.oracle.com/en/database/oracle/oracle-database/
- title: ''
  type: Getting Started
  url: https://www.oracle.com/database/technologies/appdev/quickstartsandtutorials.html
- title: ''
  type: Support
  url: https://www.oracle.com/support/
- title: ''
  type: Status
  url: https://ocistatus.oraclecloud.com/
- title: ''
  type: Blog
  url: https://blogs.oracle.com/database/
- title: ''
  type: Terms of Service
  url: https://www.oracle.com/legal/terms.html
- title: ''
  type: Privacy Policy
  url: https://www.oracle.com/legal/privacy/
- title: ''
  type: Website
  url: https://www.oracle.com/database/
- title: ''
  type: Console
  url: https://cloud.oracle.com/
- title: ''
  type: Sign Up
  url: https://signup.cloud.oracle.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/oracle
- title: ''
  type: Community
  url: https://forums.oracle.com/ords/apexds/domain/dev-community
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/oracle
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/Oracle
- title: ''
  type: Pricing
  url: https://www.oracle.com/database/technologies/oracle-database-pricing.html
created: '2024-01-20'
description: APIs and interfaces for Oracle Database management, querying, and administration.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 12
  name: Oracle Database Context
  property_count: 30
  slug: oracle-database-context
layout: provider
modified: '2026-04-28'
name: Oracle Database
skills: []
slug: oracle-database
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oracle-database\nname: Oracle Database\ndescription: >-\n  APIs and interfaces for Oracle Database management, querying, and administration.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: '2024-01-20'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-database/refs/heads/main/apis.yml\napis:\n  - name: Oracle REST Data Services (ORDS)\n    description: >-\n      RESTful API development and data access for Oracle Database.\n    image: https://www.oracle.com/asset/web/favicons/favicon-192.png\n    humanUrl: https://www.oracle.com/database/technologies/appdev/rest.html\n    baseUrl: https://example.oracle.com/ords/\n    tags:\n      - Data Access\n      - Database\n      - REST\n      - SQL\n    properties:\n      - type: OpenAPI\n        url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/\n\
  \      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/latest/\n      - type: Swagger\n        url: https://example.oracle.com/ords/metadata-catalog/\n      - type: OpenAPI\n        url: openapi/oracle-database-ords-openapi.yml\n      - type: JSONSchema\n        url: json-schema/oracle-database-table.json\n      - type: JSONSchema\n        url: json-schema/oracle-database-pluggable-database.json\n      - type: JSONLD\n        url: json-ld/oracle-database-context.jsonld\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle Database API for MongoDB\n    description: >-\n      MongoDB-compatible API for Oracle Database.\n    image: https://www.oracle.com/asset/web/favicons/favicon-192.png\n    humanUrl: https://www.oracle.com/database/mongodb-api/\n    baseUrl: https://example.oracle.com:27017/\n    tags:\n      - Database\n      - JSON\n      - MongoDB\n\
  \      - NoSQL\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/mongodb-api/\n      - type: Getting Started\n        url: https://www.oracle.com/database/mongodb-api/get-started/\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n  - name: Oracle Cloud Infrastructure Database API\n    description: >-\n      API for managing Oracle Database services in Oracle Cloud Infrastructure.\n    image: https://www.oracle.com/asset/web/favicons/favicon-192.png\n    humanUrl: https://docs.oracle.com/iaas/database/\n    baseUrl: https://database.{region}.oraclecloud.com/\n    tags:\n      - Autonomous Database\n      - Cloud\n      - Database Management\n      - Infrastructure\n    properties:\n      - type: OpenAPI\n        url: https://docs.oracle.com/iaas/api/#/en/database/\n      - type: Documentation\n        url: https://docs.oracle.com/iaas/Content/Database/home.htm\n      - type: SDK\n        url: https://docs.oracle.com/iaas/Content/API/Concepts/sdks.htm\n\
  \      - type: API Reference\n        url: https://docs.oracle.com/iaas/api/#/en/database/20160918/\n      - type: OpenAPI\n        url: openapi/oracle-database-oci-openapi.yml\n      - type: JSONSchema\n        url: json-schema/oracle-database-autonomous-database.json\n      - type: JSONSchema\n        url: json-schema/oracle-database-pluggable-database.json\n      - type: JSONLD\n        url: json-ld/oracle-database-context.jsonld\n    contact:\n      - FN: Oracle Cloud Support\n        email: cloud-support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle Database JDBC\n    description: >-\n      Java Database Connectivity API for Oracle Database.\n    image: https://www.oracle.com/asset/web/favicons/favicon-192.png\n    humanUrl: https://www.oracle.com/database/technologies/appdev/jdbc.html\n    tags:\n      - Database Driver\n      - Java\n      - JDBC\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/oracle-database/21/jjdbc/\n\
  \      - type: Downloads\n        url: https://www.oracle.com/database/technologies/appdev/jdbc-downloads.html\n      - type: GitHub\n        url: https://github.com/oracle/oracle-db-examples/tree/master/java\n  - name: Oracle Call Interface (OCI)\n    description: >-\n      C/C++ API for Oracle Database access.\n    image: https://www.oracle.com/asset/web/favicons/favicon-192.png\n    humanUrl: https://www.oracle.com/database/technologies/appdev/oci.html\n    tags:\n      - C\n      - C++\n      - Database Driver\n      - Native API\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/oracle-database/21/lnoci/\n      - type: Programming Guide\n        url: https://docs.oracle.com/en/database/oracle/oracle-database/21/lnoci/introduction.html\n  - name: Oracle SQL Developer REST API\n    description: >-\n      RESTful services for Oracle SQL Developer.\n    image: https://www.oracle.com/asset/web/favicons/favicon-192.png\n    humanUrl: https://www.oracle.com/database/sqldeveloper/\n\
  \    tags:\n      - Development Tools\n      - REST\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/sql-developer/\n      - type: User Guide\n        url: https://docs.oracle.com/en/database/oracle/sql-developer/latest/\n  - name: Oracle SODA (Simple Oracle Document Access)\n    description: >-\n      NoSQL-style document API for Oracle Database.\n    image: https://www.oracle.com/asset/web/favicons/favicon-192.png\n    humanUrl: https://docs.oracle.com/en/database/oracle/simple-oracle-document-access/\n    tags:\n      - Document Database\n      - JSON\n      - NoSQL\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/simple-oracle-document-access/\n      - type: REST API\n        url: https://docs.oracle.com/en/database/oracle/simple-oracle-document-access/rest/\n      - type: Java API\n        url: https://docs.oracle.com/en/database/oracle/simple-oracle-document-access/java/\n\
  \      - type: OpenAPI\n        url: openapi/oracle-database-soda-openapi.yml\n      - type: JSONSchema\n        url: json-schema/oracle-database-document.json\n      - type: JSONSchema\n        url: json-schema/oracle-database-collection.json\n      - type: JSONLD\n        url: json-ld/oracle-database-context.jsonld\n  - name: Oracle Transactional Event Queues (TxEventQ)\n    description: >-\n      Kafka-compatible event streaming and message queuing built into Oracle Database.\n    image: https://www.oracle.com/asset/web/favicons/favicon-192.png\n    humanUrl: https://docs.oracle.com/en/database/oracle/oracle-database/23/adque/\n    baseUrl: https://example.oracle.com/ords/{schema}/database/txeventq/\n    tags:\n      - Event Streaming\n      - Kafka\n      - Messaging\n      - Pub/Sub\n      - Queues\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/oracle-database/23/adque/\n      - type: AsyncAPI\n        url: asyncapi/oracle-database-txeventq-asyncapi.yml\n\
  \      - type: JSONSchema\n        url: json-schema/oracle-database-event-message.json\n      - type: JSONLD\n        url: json-ld/oracle-database-context.jsonld\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://www.oracle.com/database/technologies/appdev.html\n  - type: Documentation\n    url: https://docs.oracle.com/en/database/oracle/oracle-database/\n  - type: Getting Started\n    url: https://www.oracle.com/database/technologies/appdev/quickstartsandtutorials.html\n  - type: Support\n    url: https://www.oracle.com/support/\n  - type: Status\n    url: https://ocistatus.oraclecloud.com/\n  - type: Blog\n    url: https://blogs.oracle.com/database/\n  - type: Terms of Service\n    url: https://www.oracle.com/legal/terms.html\n  - type: Privacy Policy\n    url: https://www.oracle.com/legal/privacy/\n  - type:\
  \ Website\n    url: https://www.oracle.com/database/\n  - type: Console\n    url: https://cloud.oracle.com/\n  - type: Sign Up\n    url: https://signup.cloud.oracle.com/\n  - type: GitHub Organization\n    url: https://github.com/oracle\n  - type: Community\n    url: https://forums.oracle.com/ords/apexds/domain/dev-community\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/oracle\n  - type: YouTube\n    url: https://www.youtube.com/user/Oracle\n  - type: Pricing\n    url: https://www.oracle.com/database/technologies/oracle-database-pricing.html\ntags:\n  - Cloud\n  - Database\n  - Enterprise\n  - Oracle\n  - REST API\n  - SQL\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-database/refs/heads/main/apis.yml
tags:
- Cloud
- Database
- Enterprise
- Oracle
- REST API
- SQL
url: https://raw.githubusercontent.com/api-evangelist/oracle-database/refs/heads/main/apis.yml
use_cases: []
---
