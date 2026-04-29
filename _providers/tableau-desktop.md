---
api_count: 6
apis:
- description: Manage and interact with Tableau Server and Tableau Cloud resources programmatically including workbooks, data sources, users, and permissions.
  name: Tableau REST API
  slug: rest-api
- description: Build dashboard extensions that enable users to interact with data from other applications directly in Tableau dashboards.
  name: Tableau Extensions API
  slug: extensions-api
- description: Create, read, update, and delete data in .hyper files for use in Tableau Desktop and Server with high-performance data extract capabilities.
  name: Tableau Hyper API
  slug: hyper-api
- description: Embed Tableau visualizations into web applications using modern web components with v3 of the Embedding API.
  name: Tableau Embedding API
  slug: embedding-api
- description: Discover and query metadata about Tableau content using GraphQL, including workbooks, data sources, flows, and lineage information.
  name: Tableau Metadata API
  slug: metadata-api
- description: Python library that provides a convenient wrapper for the Tableau Server REST API for automation and integration workflows.
  name: Tableau Server Client (Python)
  slug: server-client-python
common:
- title: ''
  type: Portal
  url: https://www.tableau.com/developer
- title: ''
  type: Documentation
  url: https://www.tableau.com/developer/tools
- title: ''
  type: GettingStarted
  url: https://www.tableau.com/developer/getting-started
- title: ''
  type: Blog
  url: https://www.tableau.com/about/blog/developers
- title: ''
  type: Support
  url: https://www.tableau.com/support
- title: ''
  type: TermsOfService
  url: https://www.tableau.com/tos
- title: ''
  type: PrivacyPolicy
  url: https://www.tableau.com/privacy
- title: ''
  type: Training
  url: https://trailhead.salesforce.com/content/learn/modules/tableau-developer-platform/get-started-with-the-tableau-developer-platform
- title: ''
  type: GitHubOrganization
  url: https://github.com/tableau
created: '2024-01-01'
description: APIs and integration points for Tableau Desktop, a data visualization and business intelligence platform from Salesforce. Tableau provides REST APIs, embedding APIs, extension APIs, and SDK tools for building custom visualizations, automating server operations, and extending analytics capabilities.
features:
- description: Full CRUD operations on Tableau Server and Cloud resources including workbooks, data sources, and users.
  name: REST API Management
- description: Build custom interactive extensions that integrate third-party data and functionality into dashboards.
  name: Dashboard Extensions
- description: Create and manage .hyper data extract files with the Hyper API for optimized data loading.
  name: High-Performance Data Extracts
- description: Embed interactive Tableau visualizations in web applications with modern web components.
  name: Embedded Analytics
- description: Query content metadata and data lineage using GraphQL for governance and impact analysis.
  name: Metadata and Lineage
- description: Automate Tableau Server operations with the Python Server Client library.
  name: Python Automation
image: /assets/icons/tableau-desktop.png
integrations:
- description: Native integration with Salesforce CRM for embedded analytics and data connectivity.
  name: Salesforce
- description: High-performance data connectivity with Snowflake cloud data warehouse.
  name: Snowflake
- description: Cloud deployment on AWS with S3, Redshift, and Athena data source support.
  name: AWS
- description: Azure integration with Synapse Analytics, Blob Storage, and Azure Active Directory.
  name: Azure
- description: TabPy server for executing Python scripts in Tableau calculated fields.
  name: Python
- description: Collaboration integration for sharing and subscribing to Tableau content in Slack.
  name: Slack
layout: provider
modified: '2026-04-18'
name: Tableau Desktop
skills: []
slug: tableau-desktop
solutions: []
source_filename: apis.yml
source_yaml: "aid: tableau-desktop\nname: Tableau Desktop\ndescription: >-\n  APIs and integration points for Tableau Desktop, a data visualization and business\n  intelligence platform from Salesforce. Tableau provides REST APIs, embedding APIs,\n  extension APIs, and SDK tools for building custom visualizations, automating\n  server operations, and extending analytics capabilities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tableau-desktop/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Analytics\n  - Business Intelligence\n  - Data Visualization\n  - Desktop Application\napis:\n  - aid: tableau-desktop:rest-api\n    name: Tableau REST API\n    description: >-\n      Manage and interact with Tableau Server and Tableau Cloud resources\n      programmatically including workbooks, data sources, users, and permissions.\n\
  \    humanURL: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm\n    baseURL: https://tableau-server/api/3.22\n    tags:\n      - Cloud\n      - Publishing\n      - REST\n      - Server\n      - Workbooks\n    properties:\n      - type: Documentation\n        url: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm\n      - type: APIReference\n        url: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_ref.htm\n      - type: Authentication\n        url: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_concepts_auth.htm\n  - aid: tableau-desktop:extensions-api\n    name: Tableau Extensions API\n    description: >-\n      Build dashboard extensions that enable users to interact with data from\n      other applications directly in Tableau dashboards.\n    humanURL: https://tableau.github.io/extensions-api/\n    baseURL: https://tableau.github.io/extensions-api/\n    tags:\n      - Dashboard\n      - Extensions\n  \
  \    - JavaScript\n      - Web Components\n    properties:\n      - type: Documentation\n        url: https://tableau.github.io/extensions-api/docs/trex_overview.html\n      - type: APIReference\n        url: https://tableau.github.io/extensions-api/docs/index.html\n      - type: GitHubRepository\n        url: https://github.com/tableau/extensions-api\n      - type: GettingStarted\n        url: https://tableau.github.io/extensions-api/docs/trex_getstarted.html\n  - aid: tableau-desktop:hyper-api\n    name: Tableau Hyper API\n    description: >-\n      Create, read, update, and delete data in .hyper files for use in Tableau\n      Desktop and Server with high-performance data extract capabilities.\n    humanURL: https://tableau.github.io/hyper-db/docs/\n    baseURL: https://tableau.github.io/hyper-db/\n    tags:\n      - Data Extract\n      - Database\n      - ETL\n      - Hyper\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://tableau.github.io/hyper-db/docs/\n\
  \      - type: APIReference\n        url: https://tableau.github.io/hyper-db/lang_docs/py/tableauhyperapi.html\n      - type: GitHubRepository\n        url: https://github.com/tableau/hyper-api-samples\n      - type: ReleaseNotes\n        url: https://tableau.github.io/hyper-db/docs/releases/\n  - aid: tableau-desktop:embedding-api\n    name: Tableau Embedding API\n    description: >-\n      Embed Tableau visualizations into web applications using modern web\n      components with v3 of the Embedding API.\n    humanURL: https://help.tableau.com/current/api/embedding_api/en-us/index.html\n    baseURL: https://help.tableau.com/current/api/embedding_api/\n    tags:\n      - Embedding\n      - Integration\n      - JavaScript\n      - Web Components\n    properties:\n      - type: Documentation\n        url: https://help.tableau.com/current/api/embedding_api/en-us/index.html\n      - type: GitHubRepository\n        url: https://github.com/tableau/embedding-api-v3-samples\n      - type: Authentication\n\
  \        url: https://help.tableau.com/current/api/embedding_api/en-us/docs/embedding_api_auth.html\n  - aid: tableau-desktop:metadata-api\n    name: Tableau Metadata API\n    description: >-\n      Discover and query metadata about Tableau content using GraphQL, including\n      workbooks, data sources, flows, and lineage information.\n    humanURL: https://help.tableau.com/current/api/metadata_api/en-us/index.html\n    baseURL: https://help.tableau.com/current/api/metadata_api/\n    tags:\n      - Data Governance\n      - GraphQL\n      - Lineage\n      - Metadata\n    properties:\n      - type: Documentation\n        url: https://help.tableau.com/current/api/metadata_api/en-us/index.html\n      - type: GettingStarted\n        url: https://help.tableau.com/current/api/metadata_api/en-us/docs/meta_api_start.html\n  - aid: tableau-desktop:server-client-python\n    name: Tableau Server Client (Python)\n    description: >-\n      Python library that provides a convenient wrapper for the\
  \ Tableau Server\n      REST API for automation and integration workflows.\n    humanURL: https://tableau.github.io/server-client-python/\n    baseURL: https://tableau.github.io/server-client-python/\n    tags:\n      - Automation\n      - Python\n      - REST API\n      - Server\n    properties:\n      - type: Documentation\n        url: https://tableau.github.io/server-client-python/docs/\n      - type: APIReference\n        url: https://tableau.github.io/server-client-python/docs/api-ref\n      - type: GitHubRepository\n        url: https://github.com/tableau/server-client-python\ncommon:\n  - type: Portal\n    url: https://www.tableau.com/developer\n  - type: Documentation\n    url: https://www.tableau.com/developer/tools\n  - type: GettingStarted\n    url: https://www.tableau.com/developer/getting-started\n  - type: Blog\n    url: https://www.tableau.com/about/blog/developers\n  - type: Support\n    url: https://www.tableau.com/support\n  - type: TermsOfService\n    url: https://www.tableau.com/tos\n\
  \  - type: PrivacyPolicy\n    url: https://www.tableau.com/privacy\n  - type: Training\n    url: https://trailhead.salesforce.com/content/learn/modules/tableau-developer-platform/get-started-with-the-tableau-developer-platform\n  - type: GitHubOrganization\n    url: https://github.com/tableau\n  - type: Features\n    data:\n      - name: REST API Management\n        description: Full CRUD operations on Tableau Server and Cloud resources including workbooks, data sources, and users.\n      - name: Dashboard Extensions\n        description: Build custom interactive extensions that integrate third-party data and functionality into dashboards.\n      - name: High-Performance Data Extracts\n        description: Create and manage .hyper data extract files with the Hyper API for optimized data loading.\n      - name: Embedded Analytics\n        description: Embed interactive Tableau visualizations in web applications with modern web components.\n      - name: Metadata and Lineage\n        description:\
  \ Query content metadata and data lineage using GraphQL for governance and impact analysis.\n      - name: Python Automation\n        description: Automate Tableau Server operations with the Python Server Client library.\n  - type: UseCases\n    data:\n      - name: Embedded Analytics\n        description: Embed interactive dashboards and visualizations into customer-facing web applications.\n      - name: Data Pipeline Automation\n        description: Automate data extract creation and refresh workflows using the Hyper API and REST API.\n      - name: Content Migration\n        description: Migrate workbooks and data sources between Tableau Server environments programmatically.\n      - name: Custom Dashboard Extensions\n        description: Build write-back forms, custom controls, and third-party integrations as dashboard extensions.\n      - name: Data Governance\n        description: Track data lineage and content dependencies using the Metadata API for impact analysis.\n  - type:\
  \ Integrations\n    data:\n      - name: Salesforce\n        description: Native integration with Salesforce CRM for embedded analytics and data connectivity.\n      - name: Snowflake\n        description: High-performance data connectivity with Snowflake cloud data warehouse.\n      - name: AWS\n        description: Cloud deployment on AWS with S3, Redshift, and Athena data source support.\n      - name: Azure\n        description: Azure integration with Synapse Analytics, Blob Storage, and Azure Active Directory.\n      - name: Python\n        description: TabPy server for executing Python scripts in Tableau calculated fields.\n      - name: Slack\n        description: Collaboration integration for sharing and subscribing to Tableau content in Slack.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tableau-desktop/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Data Visualization
- Desktop Application
url: https://raw.githubusercontent.com/api-evangelist/tableau-desktop/refs/heads/main/apis.yml
use_cases:
- description: Embed interactive dashboards and visualizations into customer-facing web applications.
  name: Embedded Analytics
- description: Automate data extract creation and refresh workflows using the Hyper API and REST API.
  name: Data Pipeline Automation
- description: Migrate workbooks and data sources between Tableau Server environments programmatically.
  name: Content Migration
- description: Build write-back forms, custom controls, and third-party integrations as dashboard extensions.
  name: Custom Dashboard Extensions
- description: Track data lineage and content dependencies using the Metadata API for impact analysis.
  name: Data Governance
---
