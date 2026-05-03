---
api_count: 5
api_specs:
- filename: oracle-essbase-rest-api-openapi.yml
  format: yaml
  label: Oracle Essbase REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-essbase/refs/heads/main/openapi/oracle-essbase-rest-api-openapi.yml
apis:
- description: RESTful API for managing and interacting with Oracle Essbase applications, databases, and performing analytical operations. Enables automation of Essbase resource management with endpoints for applica
  name: Oracle Essbase REST API
  slug: ''
- description: 'Java API for developing applications that interact with Oracle Essbase for data loading, calculations, and retrievals. Provides libraries, samples, and documentation for building Essbase client tools '
  name: Essbase Java API
  slug: ''
- description: C API for building high-performance applications that interact with Essbase databases. Includes the Grid API for Smart View-like functionality and the Outline API for programmatic outline manipulation
  name: Essbase C API
  slug: ''
- description: 'MaxL is the multi-dimensional database access language for Essbase that provides a scripting-based interface for administering and querying Essbase. It enables automation of administrative operations '
  name: Essbase MaxL Scripting Interface
  slug: ''
- description: Command-line interface for administering and managing Essbase applications and databases. Provides command-line access for common administrative tasks including application management, data operations
  name: Essbase CLI (Command Line Interface)
  slug: ''
common:
- title: ''
  type: Portal
  url: https://docs.oracle.com/en/database/other-databases/essbase/21/index.html
- title: ''
  type: Getting Started
  url: https://docs.oracle.com/en/database/other-databases/essbase/21/essst/what-is-oracle-essbase.html
- title: ''
  type: Documentation
  url: https://docs.oracle.com/en/database/other-databases/essbase/
- title: ''
  type: Authentication
  url: https://docs.oracle.com/en/database/other-databases/essbase/21/essoa/weblogic-authentication.html
- title: ''
  type: Blog
  url: https://blogs.oracle.com/proactivesupportepm/category/pse-essbase-on-premise
- title: ''
  type: Status
  url: https://ocistatus.oraclecloud.com/
- title: ''
  type: Support
  url: https://support.oracle.com
- title: ''
  type: Terms of Service
  url: https://www.oracle.com/legal/terms/
- title: ''
  type: Privacy Policy
  url: https://www.oracle.com/legal/privacy/privacy-policy/
- title: ''
  type: GitHub Organization
  url: https://github.com/oracle-quickstart/oci-essbase
- title: ''
  type: Community
  url: https://community.oracle.com/customerconnect/categories/oci-essbase
- title: ''
  type: Website
  url: https://www.oracle.com/business-analytics/essbase.html
- title: ''
  type: Login
  url: https://www.oracle.com/cloud/sign-in.html
- title: ''
  type: Sign Up
  url: https://www.oracle.com/cloud/free/
- title: ''
  type: Downloads
  url: https://www.oracle.com/database/technologies/essbase-downloads.html
- title: ''
  type: Tutorials
  url: https://docs.oracle.com/en/database/other-databases/essbase/21/essug/essbase-tutorials.html
- title: ''
  type: Licensing
  url: https://www.oracle.com/corporate/pricing/specialty-topics.html
- title: ''
  type: Change Log
  url: https://docs.oracle.com/en/database/other-databases/essbase/21/essop/index.html
created: '2024-01-01'
description: Oracle Essbase is a multi-dimensional database management system that provides a multidimensional analytical platform for business intelligence applications, financial consolidation, planning, budgeting, and forecasting.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Oracle Essbase Context
  property_count: 13
  slug: oracle-essbase-context
layout: provider
modified: '2026-04-28'
name: Oracle Essbase
skills: []
slug: oracle-essbase
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oracle-essbase\nname: Oracle Essbase\ndescription: >-\n  Oracle Essbase is a multi-dimensional database management system that provides\n  a multidimensional analytical platform for business intelligence applications,\n  financial consolidation, planning, budgeting, and forecasting.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-essbase/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Analytics\n  - Budgeting\n  - Business Intelligence\n  - Financial Consolidation\n  - Multi-Dimensional Database\n  - OLAP\n  - Planning\napis:\n  - name: Oracle Essbase REST API\n    description: RESTful API for managing and interacting with Oracle Essbase applications, databases, and performing analytical operations. Enables automation of Essbase resource management with\
  \ endpoints for applications, databases, calculations, data loads, and user management.\n    image: https://www.oracle.com/a/ocom/img/oracle-essbase.jpg\n    humanURL: https://docs.oracle.com/en/database/other-databases/essbase/21/essrt/index.html\n    baseURL: https://{host}:{port}/essbase/rest/v1\n    tags:\n      - Analytics\n      - Calculations\n      - Data Management\n      - OLAP\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/other-databases/essbase/21/essrt/index.html\n      - type: OpenAPI\n        url: openapi/oracle-essbase-rest-api-openapi.yml\n      - type: Authentication\n        url: https://docs.oracle.com/en/database/other-databases/essbase/21/erest/op-rest-v1-sessions-post.html\n      - type: Reference\n        url: https://docs.oracle.com/en/database/other-databases/essbase/21/essrt/rest-endpoints.html\n      - type: Getting Started\n        url: https://docs.oracle.com/en/database/other-databases/essbase/21/essrt/api-essbase.html\n\
  \      - type: JSON Schema\n        url: json-schema/oracle-essbase-application-schema.json\n      - type: JSON Schema\n        url: json-schema/oracle-essbase-database-schema.json\n      - type: JSON Schema\n        url: json-schema/oracle-essbase-job-schema.json\n      - type: JSON Schema\n        url: json-schema/oracle-essbase-user-schema.json\n      - type: JSON Schema\n        url: json-schema/oracle-essbase-session-schema.json\n      - type: JSON Schema\n        url: json-schema/oracle-essbase-dimension-schema.json\n      - type: JSON Schema\n        url: json-schema/oracle-essbase-connection-schema.json\n      - type: JSON Schema\n        url: json-schema/oracle-essbase-script-schema.json\n      - type: JSON Schema\n        url: json-schema/oracle-essbase-filter-schema.json\n      - type: JSON-LD Context\n        url: json-ld/oracle-essbase-context.jsonld\n    contact:\n      - FN: Oracle Support\n        url: https://support.oracle.com\n  - name: Essbase Java API\n    description:\
  \ Java API for developing applications that interact with Oracle Essbase for data loading, calculations, and retrievals. Provides libraries, samples, and documentation for building Essbase client tools in Java.\n    humanURL: https://docs.oracle.com/en/database/other-databases/essbase/21/esjav/\n    tags:\n      - Client Tools\n      - Data Loading\n      - Java\n      - Programming Interface\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/other-databases/essbase/21/esjav/\n  - name: Essbase C API\n    description: C API for building high-performance applications that interact with Essbase databases. Includes the Grid API for Smart View-like functionality and the Outline API for programmatic outline manipulation.\n    humanURL: https://docs.oracle.com/en/database/other-databases/essbase/21/esoac/\n    tags:\n      - C API\n      - Grid API\n      - Native Interface\n      - Outline API\n      - SDK\n    properties:\n      - type:\
  \ Documentation\n        url: https://docs.oracle.com/en/database/other-databases/essbase/21/esoac/\n  - name: Essbase MaxL Scripting Interface\n    description: MaxL is the multi-dimensional database access language for Essbase that provides a scripting-based interface for administering and querying Essbase. It enables automation of administrative operations using statements rather than a series of commands.\n    humanURL: https://docs.oracle.com/en/database/other-databases/essbase/21/esssr/maxl.html\n    tags:\n      - Administration\n      - Automation\n      - Database Management\n      - Query Language\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/other-databases/essbase/21/esssr/maxl.html\n      - type: Authentication\n        url: https://docs.oracle.com/en/database/other-databases/essbase/21/esssr/login-logout-cli-authentication.html\n  - name: Essbase CLI (Command Line Interface)\n    description: Command-line\
  \ interface for administering and managing Essbase applications and databases. Provides command-line access for common administrative tasks including application management, data operations, and server configuration.\n    humanURL: https://docs.oracle.com/en/database/other-databases/essbase/21/essug/\n    tags:\n      - Administration\n      - Automation\n      - CLI\n      - Command Line\n      - Server Management\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/database/other-databases/essbase/21/essug/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://docs.oracle.com/en/database/other-databases/essbase/21/index.html\n  - type: Getting Started\n    url: https://docs.oracle.com/en/database/other-databases/essbase/21/essst/what-is-oracle-essbase.html\n  - type: Documentation\n    url: https://docs.oracle.com/en/database/other-databases/essbase/\n  - type: Authentication\n    url: https://docs.oracle.com/en/database/other-databases/essbase/21/essoa/weblogic-authentication.html\n\
  \  - type: Blog\n    url: https://blogs.oracle.com/proactivesupportepm/category/pse-essbase-on-premise\n  - type: Status\n    url: https://ocistatus.oraclecloud.com/\n  - type: Support\n    url: https://support.oracle.com\n  - type: Terms of Service\n    url: https://www.oracle.com/legal/terms/\n  - type: Privacy Policy\n    url: https://www.oracle.com/legal/privacy/privacy-policy/\n  - type: GitHub Organization\n    url: https://github.com/oracle-quickstart/oci-essbase\n  - type: Community\n    url: https://community.oracle.com/customerconnect/categories/oci-essbase\n  - type: Website\n    url: https://www.oracle.com/business-analytics/essbase.html\n  - type: Login\n    url: https://www.oracle.com/cloud/sign-in.html\n  - type: Sign Up\n    url: https://www.oracle.com/cloud/free/\n  - type: Downloads\n    url: https://www.oracle.com/database/technologies/essbase-downloads.html\n  - type: Tutorials\n    url: https://docs.oracle.com/en/database/other-databases/essbase/21/essug/essbase-tutorials.html\n\
  \  - type: Licensing\n    url: https://www.oracle.com/corporate/pricing/specialty-topics.html\n  - type: Change Log\n    url: https://docs.oracle.com/en/database/other-databases/essbase/21/essop/index.html\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-essbase/refs/heads/main/apis.yml
tags:
- Analytics
- Budgeting
- Business Intelligence
- Financial Consolidation
- Multi-Dimensional Database
- OLAP
- Planning
url: https://raw.githubusercontent.com/api-evangelist/oracle-essbase/refs/heads/main/apis.yml
use_cases: []
---
