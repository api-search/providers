---
api_count: 4
api_specs:
- filename: oracle-primavera-p6-eppm-openapi.yml
  format: yaml
  label: Oracle Primavera P6 EPPM REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-primavera/refs/heads/main/openapi/oracle-primavera-p6-eppm-openapi.yml
apis:
- description: Oracle Primavera P6 EPPM REST API provides programmatic access to enterprise project portfolio management data including WBS structures, activity schedules, resource assignments, critical path analysi
  name: Oracle Primavera P6 EPPM REST API
  slug: ''
- description: Oracle Primavera Gateway provides integration APIs for connecting Primavera P6 with other Oracle and third-party applications. Enables bi-directional data exchange for projects, resources, cost accoun
  name: Oracle Primavera Gateway Integration API
  slug: ''
- description: Oracle Primavera Analytics provides reporting and business intelligence APIs for portfolio performance insights, project health dashboards, resource utilization analysis, and earned value management r
  name: Oracle Primavera Analytics API
  slug: ''
- description: Oracle Primavera P6 provides project scheduling and portfolio management APIs for construction, engineering, and capital projects. REST and XML APIs enable access to WBS structures, activity schedules
  name: Oracle Primavera P6 Scheduling API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://docs.oracle.com/en/industries/construction-engineering/primavera/
- title: ''
  type: Website
  url: https://www.oracle.com/construction-engineering/primavera/
- title: ''
  type: Documentation
  url: https://docs.oracle.com/en/industries/construction-engineering/primavera-p6-project/index.html
- title: ''
  type: Reference
  url: https://docs.oracle.com/cd/G48897_01/index.htm
- title: ''
  type: Change Log
  url: https://docs.oracle.com/cd/E64687_01/EPPM/EPPM_CFO.html
- title: ''
  type: Getting Started
  url: https://mylearn.oracle.com/construction
- title: ''
  type: Support
  url: https://www.oracle.com/support/
- title: ''
  type: Status
  url: https://ocistatus.oraclecloud.com/
- title: ''
  type: Privacy Policy
  url: https://www.oracle.com/legal/privacy/
- title: ''
  type: Terms of Service
  url: https://www.oracle.com/legal/terms.html
- title: ''
  type: OpenAPI
  url: openapi/oracle-primavera-p6-eppm-openapi.yml
- title: ''
  type: JSON Schema
  url: json-schema/oracle-primavera-project-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/oracle-primavera-activity-schema.json
- title: ''
  type: JSON-LD Context
  url: json-ld/oracle-primavera-context.jsonld
created: '2024-01-01'
description: Oracle Primavera is a portfolio of project portfolio management (PPM) applications for construction, engineering, and capital project industries. Primavera APIs provide programmatic access to enterprise project portfolio management data including WBS structures, activity schedules, resource assignments, critical path analysis, and portfolio dashboards across cloud and on-premises deployments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Oracle Primavera Context
  property_count: 26
  slug: oracle-primavera-context
layout: provider
modified: '2026-04-28'
name: Oracle Primavera
skills: []
slug: oracle-primavera
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oracle-primavera\nname: Oracle Primavera\ndescription: >-\n  Oracle Primavera is a portfolio of project portfolio management (PPM)\n  applications for construction, engineering, and capital project industries.\n  Primavera APIs provide programmatic access to enterprise project portfolio\n  management data including WBS structures, activity schedules, resource\n  assignments, critical path analysis, and portfolio dashboards across cloud\n  and on-premises deployments.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-primavera/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Construction\n  - Engineering\n  - Project Management\n  - Scheduling\n  - Portfolio Management\n  - Oracle\napis:\n  - name: Oracle Primavera P6 EPPM REST API\n    description: >-\n  \
  \    Oracle Primavera P6 EPPM REST API provides programmatic access to\n      enterprise project portfolio management data including WBS structures,\n      activity schedules, resource assignments, critical path analysis, and\n      portfolio dashboards. Available for both cloud and on-premises\n      deployments. Documentation covers version 6.2.1 through version 26 (2026).\n    image: https://www.oracle.com/a/ocom/img/social-og-oracle-cloud.jpg\n    humanURL: https://docs.oracle.com/en/industries/construction-engineering/primavera-p6-project/index.html\n    baseURL: https://{host}/p6ws/rest/v1\n    tags:\n      - Construction\n      - EPPM\n      - Project Management\n      - REST\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/industries/construction-engineering/primavera-p6-project/index.html\n      - type: Reference\n        url: https://docs.oracle.com/cd/G48897_01/index.htm\n      - type: Change Log\n        url: https://docs.oracle.com/cd/E64687_01/EPPM/EPPM_CFO.html\n\
  \      - type: OpenAPI\n        url: openapi/oracle-primavera-p6-eppm-openapi.yml\n  - name: Oracle Primavera Gateway Integration API\n    description: >-\n      Oracle Primavera Gateway provides integration APIs for connecting\n      Primavera P6 with other Oracle and third-party applications. Enables\n      bi-directional data exchange for projects, resources, cost accounts, and\n      activity data between P6 EPPM and ERP, asset management, and financial\n      systems.\n    image: https://www.oracle.com/a/ocom/img/social-og-oracle-cloud.jpg\n    humanURL: https://docs.oracle.com/en/industries/construction-engineering/primavera-gateway/index.html\n    tags:\n      - Construction\n      - Integration\n      - Project Management\n      - Scheduling\n      - XML\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/industries/construction-engineering/primavera-gateway/index.html\n  - name: Oracle Primavera Analytics API\n    description: >-\n      Oracle\
  \ Primavera Analytics provides reporting and business intelligence\n      APIs for portfolio performance insights, project health dashboards,\n      resource utilization analysis, and earned value management reporting\n      across construction and engineering portfolios.\n    image: https://www.oracle.com/a/ocom/img/social-og-oracle-cloud.jpg\n    humanURL: https://docs.oracle.com/en/industries/construction-engineering/primavera-analytics/index.html\n    tags:\n      - Analytics\n      - Construction\n      - Project Management\n      - Reporting\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/industries/construction-engineering/primavera-analytics/index.html\n  - name: Oracle Primavera P6 Scheduling API\n    description: >-\n      Oracle Primavera P6 provides project scheduling and portfolio management\n      APIs for construction, engineering, and capital projects. REST and XML\n      APIs enable access to WBS structures, activity\
  \ schedules, resource\n      assignments, and critical path analysis.\n    image: https://www.oracle.com/a/ocom/img/social-og-oracle-cloud.jpg\n    humanURL: https://docs.oracle.com/en/industries/construction-engineering/primavera/\n    tags:\n      - Construction\n      - Project Management\n      - Scheduling\n      - XML\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/industries/construction-engineering/primavera/\ncommon:\n  - type: Portal\n    url: https://docs.oracle.com/en/industries/construction-engineering/primavera/\n  - type: Website\n    url: https://www.oracle.com/construction-engineering/primavera/\n  - type: Documentation\n    url: https://docs.oracle.com/en/industries/construction-engineering/primavera-p6-project/index.html\n  - type: Reference\n    url: https://docs.oracle.com/cd/G48897_01/index.htm\n  - type: Change Log\n    url: https://docs.oracle.com/cd/E64687_01/EPPM/EPPM_CFO.html\n  - type: Getting Started\n    url: https://mylearn.oracle.com/construction\n\
  \  - type: Support\n    url: https://www.oracle.com/support/\n  - type: Status\n    url: https://ocistatus.oraclecloud.com/\n  - type: Privacy Policy\n    url: https://www.oracle.com/legal/privacy/\n  - type: Terms of Service\n    url: https://www.oracle.com/legal/terms.html\n  - type: OpenAPI\n    url: openapi/oracle-primavera-p6-eppm-openapi.yml\n  - type: JSON Schema\n    url: json-schema/oracle-primavera-project-schema.json\n  - type: JSON Schema\n    url: json-schema/oracle-primavera-activity-schema.json\n  - type: JSON-LD Context\n    url: json-ld/oracle-primavera-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-primavera/refs/heads/main/apis.yml
tags:
- Construction
- Engineering
- Project Management
- Scheduling
- Portfolio Management
- Oracle
url: https://raw.githubusercontent.com/api-evangelist/oracle-primavera/refs/heads/main/apis.yml
use_cases: []
---
