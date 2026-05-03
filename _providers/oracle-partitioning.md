---
api_count: 3
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Oracle Database REST API - Partitioning
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/
- filename: database.json
  format: json
  label: Oracle Cloud Infrastructure Database API - Partitioning
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en-us/iaas/api/swagger/database.json
apis:
- description: REST API endpoints for managing and monitoring Oracle Database partitioning operations.
  name: Oracle Database REST API - Partitioning
  slug: ''
- description: REST services for partition management through SQL Developer.
  name: Oracle SQL Developer REST Services - Partitioning
  slug: ''
- description: OCI API for managing partitioned databases in Oracle Cloud.
  name: Oracle Cloud Infrastructure Database API - Partitioning
  slug: ''
common:
- title: ''
  type: Getting Started
  url: https://docs.oracle.com/en/database/oracle/oracle-database/19/vldbg/partition-intro.html
- title: ''
  type: Best Practices
  url: https://docs.oracle.com/en/database/oracle/oracle-database/19/vldbg/partition-strategies.html
- title: ''
  type: White Papers
  url: https://www.oracle.com/technetwork/database/options/partitioning/
- title: ''
  type: Pricing
  url: https://www.oracle.com/database/technologies/partitioning/pricing.html
- title: ''
  type: Support
  url: https://support.oracle.com
- title: ''
  type: Authentication
  url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/19.2/orrst/authentication.html
- title: ''
  type: Status
  url: https://status.oracle.com
- title: ''
  type: Terms of Service
  url: https://www.oracle.com/legal/terms.html
- title: ''
  type: Privacy Policy
  url: https://www.oracle.com/legal/privacy/
created: '2024-01-01'
description: Oracle Partitioning enables tables and indexes to be partitioned into smaller, more manageable pieces, improving performance, availability, and manageability of large database objects.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-16'
name: Oracle Partitioning
skills: []
slug: oracle-partitioning
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oracle-partitioning\nname: Oracle Partitioning\ndescription: >-\n  Oracle Partitioning enables tables and indexes to be partitioned into smaller,\n  more manageable pieces, improving performance, availability, and manageability\n  of large database objects.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-partitioning/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\napis:\n  - name: Oracle Database REST API - Partitioning\n    description: >-\n      REST API endpoints for managing and monitoring Oracle Database partitioning\n      operations.\n    image: https://www.oracle.com/a/ocom/img/cb71-oracle-database.jpg\n    baseURL: https://your-oracle-instance.com:8443/ords\n    humanURL: https://docs.oracle.com/en/database/oracle/oracle-database/\n    properties:\n     \
  \ - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/oracle-database/19/vldbg/partition-concepts.html\n      - type: OpenAPI\n        url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/\n      - type: Swagger\n        url: https://your-oracle-instance.com:8443/ords/swagger-ui.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle SQL Developer REST Services - Partitioning\n    description: >-\n      REST services for partition management through SQL Developer.\n    image: https://www.oracle.com/a/ocom/img/sql-dev.jpg\n    baseURL: https://your-oracle-instance.com/ords\n    humanURL: https://www.oracle.com/database/sqldeveloper/\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/oracle/sql-developer/\n      - type: Tutorial\n        url: https://docs.oracle.com/en/database/oracle/oracle-database/19/vldbg/partition-admin.html\n\
  \  - name: Oracle Cloud Infrastructure Database API - Partitioning\n    description: >-\n      OCI API for managing partitioned databases in Oracle Cloud.\n    image: https://www.oracle.com/a/ocom/img/oci-logo.png\n    baseURL: https://database.{region}.oraclecloud.com\n    humanURL: https://www.oracle.com/cloud/\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en-us/iaas/api/#/en/database/\n      - type: OpenAPI\n        url: https://docs.oracle.com/en-us/iaas/api/swagger/database.json\n      - type: SDKs\n        url: https://docs.oracle.com/en-us/iaas/Content/API/SDKDocs/sdks.htm\n    contact:\n      - FN: Oracle Cloud Support\n        email: cloud-support@oracle.com\n        url: https://www.oracle.com/support/\ncommon:\n  - type: Getting Started\n    url: https://docs.oracle.com/en/database/oracle/oracle-database/19/vldbg/partition-intro.html\n  - type: Best Practices\n    url: https://docs.oracle.com/en/database/oracle/oracle-database/19/vldbg/partition-strategies.html\n\
  \  - type: White Papers\n    url: https://www.oracle.com/technetwork/database/options/partitioning/\n  - type: Pricing\n    url: https://www.oracle.com/database/technologies/partitioning/pricing.html\n  - type: Support\n    url: https://support.oracle.com\n  - type: Authentication\n    url: https://docs.oracle.com/en/database/oracle/oracle-rest-data-services/19.2/orrst/authentication.html\n  - type: Status\n    url: https://status.oracle.com\n  - type: Terms of Service\n    url: https://www.oracle.com/legal/terms.html\n  - type: Privacy Policy\n    url: https://www.oracle.com/legal/privacy/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Composite-Partitioning\n  - Database\n  - Hash-Partitioning\n  - Interval-Partitioning\n  - List-Partitioning\n  - Oracle\n  - Partitioning\n  - Performance\n  - Range-Partitioning\n  - Scalability\n  - VLDB\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-partitioning/refs/heads/main/apis.yml
tags:
- Composite-Partitioning
- Database
- Hash-Partitioning
- Interval-Partitioning
- List-Partitioning
- Oracle
- Partitioning
- Performance
- Range-Partitioning
- Scalability
- VLDB
url: https://raw.githubusercontent.com/api-evangelist/oracle-partitioning/refs/heads/main/apis.yml
use_cases: []
---
