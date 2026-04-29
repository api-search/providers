---
api_count: 13
apis:
- description: The Tableau REST API allows you to manage and change Tableau Server, Tableau Cloud site, and Tableau Prep Conductor resources programmatically, using HTTP.
  name: Tableau REST API
  slug: ''
- description: GraphQL-based API for querying metadata about Tableau content, data sources, and lineage information.
  name: Tableau Metadata API
  slug: ''
- description: API for creating, reading, and updating Hyper files, which are the data files that power Tableau extracts.
  name: Tableau Hyper API
  slug: ''
- description: JavaScript API for embedding Tableau visualizations in web applications with advanced interaction capabilities.
  name: Tableau Embedding API
  slug: ''
- description: Python library for programmatically updating Tableau workbook and data source files.
  name: Tableau Document API
  slug: ''
- description: Python library that wraps the Tableau REST API for easier programmatic access.
  name: Tableau Server Client (Python)
  slug: ''
- description: The Tableau Extensions API allows developers to create dashboard extensions and viz extensions that users can interact with directly in Tableau, enabling integration with other applications and custom
  name: Tableau Extensions API
  slug: ''
- description: The Tableau Web Data Connector (WDC) provides an SDK for building connectors to any data accessible over HTTP, allowing users to bring external data into Tableau for analysis and visualization.
  name: Tableau Web Data Connector
  slug: ''
- description: SDK for developing custom Tableau connectors using ODBC or JDBC drivers, including documentation, example files, a test harness, and a packaging tool for distribution.
  name: Tableau Connector SDK
  slug: ''
- description: The Analytics Extensions API allows integration of external analytics engines such as Python, R, MATLAB, and data science platforms with Tableau calculations for advanced analytics.
  name: Tableau Analytics Extensions API
  slug: ''
- description: Tableau Webhooks enable event-driven automation by sending HTTP POST notifications to specified URLs when events occur on Tableau Server or Tableau Cloud.
  name: Tableau Webhooks
  slug: ''
- description: The VizQL Data Service provides a programmatic HTTP interface to query published data sources outside of Tableau visualizations, enabling headless data access from any application.
  name: Tableau VizQL Data Service
  slug: ''
- description: The Tableau Pulse API enables programmatic creation, management, and querying of Tableau Pulse metrics and subscriptions, as well as embedding Pulse insights into web applications.
  name: Tableau Pulse API
  slug: ''
capabilities:
- description: Workflow for managing Tableau content including workbooks, data sources, views, sites, users, and permissions. Used by Tableau administrators and content managers.
  name: Tableau Content Management
  slug: content-management
common:
- title: ''
  type: DeveloperPortal
  url: https://www.tableau.com/developer
- title: ''
  type: Blog
  url: https://www.tableau.com/blog/developers
- title: ''
  type: Support
  url: https://www.tableau.com/support
- title: ''
  type: GitHubOrganization
  url: https://github.com/tableau
- title: ''
  type: StatusPage
  url: https://trust.tableau.com/
- title: ''
  type: ReleaseNotes
  url: https://help.tableau.com/current/tableau/en-us/whatsnew_all.htm
- title: ''
  type: TermsOfService
  url: https://www.tableau.com/legal
- title: ''
  type: PrivacyPolicy
  url: https://www.tableau.com/privacy
- title: ''
  type: SignUp
  url: https://www.tableau.com/products/trial
- title: ''
  type: Login
  url: https://www.tableau.com/tableau-login-hub
- title: ''
  type: Documentation
  url: https://help.tableau.com/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/tableau
- title: ''
  type: YouTube
  url: https://www.youtube.com/@Tableau
- title: ''
  type: Training
  url: https://www.tableau.com/developer/learning
- title: ''
  type: SpectralRules
  url: rules/tableau-spectral-rules.yml
- title: Tableau REST API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/tableau-rest.yaml
- title: Content Management Workflow
  type: NaftikoCapability
  url: capabilities/content-management.yaml
created: '2024'
description: Tableau is a visual analytics platform transforming the way we use data to solve problems—empowering people and organizations to make the most of their data.
features:
- description: Publish, query, update, delete, and download data sources that define connections to data shared across workbooks.
  name: Data Source Management
- description: Publish, query, update, delete, and download workbooks containing views, dashboards, and stories.
  name: Workbook Management
- description: Create, configure, and manage Tableau Server and Cloud sites with full lifecycle control.
  name: Site Administration
- description: Add, update, and remove users and groups with role-based access control for content permissions.
  name: User and Group Management
- description: Query and set granular permissions on workbooks, data sources, projects, views, and flows.
  name: Permission Management
- description: Create and manage schedules for extract refreshes and subscriptions for automated content delivery.
  name: Schedule and Subscription Management
- description: Embed Tableau visualizations in web applications with interactive filtering and full API control.
  name: Embedded Analytics
- description: Query metadata about content, data sources, and data lineage using the GraphQL-based Metadata API.
  name: Metadata and Lineage
- description: Build custom connectors using ODBC or JDBC drivers to bring any data source into Tableau.
  name: Custom Connectors
- description: Enable event-driven automation with HTTP POST notifications when events occur on Tableau Server or Cloud.
  name: Webhooks
image: https://www.tableau.com/sites/default/files/tableau_logo_800.png
integrations:
- description: Native integration with Salesforce CRM for unified analytics across sales, service, and marketing data.
  name: Salesforce
- description: Share Tableau visualizations and receive metric alerts directly in Slack channels.
  name: Slack
- description: Extend Tableau calculations with Python and R scripts through the Analytics Extensions API.
  name: Python and R
- description: Optimized connector for Snowflake data warehouse with live query and extract support.
  name: Snowflake
- description: Connect to Google BigQuery for large-scale data analytics and visualization.
  name: Google BigQuery
jsonld:
- class_count: 0
  name: Tableau Context
  property_count: 14
  slug: tableau-context
- class_count: 0
  name: Tableau Rest Context
  property_count: 0
  slug: tableau-rest-context
layout: provider
modified: '2026-04-18'
name: Tableau
rules:
- name: Tableau API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: tableau-spectral-rules
skills: []
slug: tableau
solutions: []
source_yaml: "name: Tableau\ndescription: Tableau is a visual analytics platform transforming the way we use data to solve problems—empowering people and organizations to make the most of their data.\nimage: https://www.tableau.com/sites/default/files/tableau_logo_800.png\ntags:\n  - Analytics\n  - Business Intelligence\n  - Dashboards\n  - Data Visualization\ncreated: '2024'\nmodified: '2026-04-18'\nurl: https://www.tableau.com\nspecificationVersion: '0.18'\napis:\n  - name: Tableau REST API\n    description: The Tableau REST API allows you to manage and change Tableau Server, Tableau Cloud site, and Tableau Prep Conductor resources programmatically, using HTTP.\n    image: https://www.tableau.com/sites/default/files/tableau_logo_800.png\n    humanURL: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm\n    baseURL: https://[server]/api/[api-version]\n    tags:\n      - Data Sources\n      - REST\n      - Server Management\n      - Sites\n      - Workbooks\n    properties:\n\
  \      - type: Documentation\n        url: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm\n      - type: OpenAPI\n        url: openapi/tableau-rest-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/tableau-workbook-schema.json\n      - type: JSONLD\n        url: json-ld/tableau-context.jsonld\n      - type: Authentication\n        url: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_concepts_auth.htm\n      - type: Versioning\n        url: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_concepts_versions.htm\n      - type: ChangeLog\n        url: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_whats_new.htm\n      - type: GettingStarted\n        url: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_get_started_tutorial_part_1.htm\n      - type: APIReference\n        url: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_ref.htm\n      - type: CodeExamples\n  \
  \      url: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_samples.htm\n      - type: SDK\n        url: https://tableau.github.io/server-client-python/\n      - type: GitHubRepository\n        url: https://github.com/tableau/rest-api-samples\n  - name: Tableau Metadata API\n    description: GraphQL-based API for querying metadata about Tableau content, data sources, and lineage information.\n    image: https://www.tableau.com/sites/default/files/tableau_logo_800.png\n    humanURL: https://help.tableau.com/current/api/metadata_api/en-us/index.html\n    baseURL: https://[server]/api/metadata/graphql\n    tags:\n      - Data Catalog\n      - GraphQL\n      - Lineage\n      - Metadata\n    properties:\n      - type: Documentation\n        url: https://help.tableau.com/current/api/metadata_api/en-us/index.html\n      - type: APIReference\n        url: https://help.tableau.com/current/api/metadata_api/en-us/reference/index.html\n      - type: CodeExamples\n        url: https://help.tableau.com/current/api/metadata_api/en-us/docs/use-cases.html\n\
  \      - type: GettingStarted\n        url: https://help.tableau.com/current/api/metadata_api/en-us/docs/meta_api_start.html\n      - type: Authentication\n        url: https://help.tableau.com/current/api/metadata_api/en-us/docs/meta_api_auth.html\n      - type: ChangeLog\n        url: https://help.tableau.com/current/api/metadata_api/en-us/docs/meta_api_release_notes.html\n      - type: GitHubRepository\n        url: https://github.com/tableau/metadata-api-samples\n  - name: Tableau Hyper API\n    description: API for creating, reading, and updating Hyper files, which are the data files that power Tableau extracts.\n    image: https://www.tableau.com/sites/default/files/tableau_logo_800.png\n    humanURL: https://help.tableau.com/current/api/hyper_api/en-us/index.html\n    baseURL: https://github.com/tableau/hyper-api-samples\n    tags:\n      - Data Files\n      - ETL\n      - Extracts\n      - Hyper\n    properties:\n      - type: Documentation\n        url: https://help.tableau.com/current/api/hyper_api/en-us/index.html\n\
  \      - type: GitHubRepository\n        url: https://github.com/tableau/hyper-api-samples\n      - type: GettingStarted\n        url: https://www.tableau.com/developer/learning/tableau-hyper-api\n      - type: ChangeLog\n        url: https://tableau.github.io/hyper-db/docs/releases/\n  - name: Tableau Embedding API\n    description: JavaScript API for embedding Tableau visualizations in web applications with advanced interaction capabilities.\n    image: https://www.tableau.com/sites/default/files/tableau_logo_800.png\n    humanURL: https://help.tableau.com/current/api/embedding_api/en-us/index.html\n    baseURL: https://[server]\n    tags:\n      - Embedding\n      - JavaScript\n      - Visualization\n      - Web Components\n    properties:\n      - type: Documentation\n        url: https://help.tableau.com/current/api/embedding_api/en-us/index.html\n      - type: Tutorials\n        url: https://help.tableau.com/current/api/embedding_api/en-us/docs/embedding_api_get_started.html\n  \
  \    - type: APIReference\n        url: https://help.tableau.com/current/api/embedding_api/en-us/reference/index.html\n      - type: Authentication\n        url: https://help.tableau.com/current/api/embedding_api/en-us/docs/embedding_api_auth.html\n      - type: ChangeLog\n        url: https://help.tableau.com/current/api/embedding_api/en-us/docs/embedding_api_release_notes.html\n      - type: GitHubRepository\n        url: https://github.com/tableau/embedding-api-v3-samples\n  - name: Tableau Document API\n    description: Python library for programmatically updating Tableau workbook and data source files.\n    image: https://www.tableau.com/sites/default/files/tableau_logo_800.png\n    humanURL: https://tableau.github.io/document-api-python/\n    baseURL: https://github.com/tableau/document-api-python\n    tags:\n      - Automation\n      - Data Sources\n      - Python\n      - Workbooks\n    properties:\n      - type: Documentation\n        url: https://tableau.github.io/document-api-python/\n\
  \      - type: GitHubRepository\n        url: https://github.com/tableau/document-api-python\n      - type: GettingStarted\n        url: https://tableau.github.io/document-api-python/docs/\n      - type: APIReference\n        url: https://tableau.github.io/document-api-python/docs/api-ref\n  - name: Tableau Server Client (Python)\n    description: Python library that wraps the Tableau REST API for easier programmatic access.\n    image: https://www.tableau.com/sites/default/files/tableau_logo_800.png\n    humanURL: https://tableau.github.io/server-client-python/\n    baseURL: https://github.com/tableau/server-client-python\n    tags:\n      - Python\n      - REST\n      - SDK\n      - Wrapper\n    properties:\n      - type: Documentation\n        url: https://tableau.github.io/server-client-python/\n      - type: GitHubRepository\n        url: https://github.com/tableau/server-client-python\n      - type: CodeExamples\n        url: https://tableau.github.io/server-client-python/docs/samples\n\
  \      - type: APIReference\n        url: https://tableau.github.io/server-client-python/docs/api-ref\n      - type: GettingStarted\n        url: https://tableau.github.io/server-client-python/docs/\n      - type: ChangeLog\n        url: https://github.com/tableau/server-client-python/blob/master/CHANGELOG.md\n  - name: Tableau Extensions API\n    description: The Tableau Extensions API allows developers to create dashboard extensions and viz extensions that users can interact with directly in Tableau, enabling integration with other applications and custom visualization types.\n    image: https://www.tableau.com/sites/default/files/tableau_logo_800.png\n    humanURL: https://tableau.github.io/extensions-api/docs/\n    baseURL: https://[server]\n    tags:\n      - Dashboard Extensions\n      - Extensibility\n      - JavaScript\n      - Viz Extensions\n      - Web Components\n    properties:\n      - type: Documentation\n        url: https://tableau.github.io/extensions-api/docs/\n    \
  \  - type: GitHubRepository\n        url: https://github.com/tableau/extensions-api\n      - type: GettingStarted\n        url: https://tableau.github.io/extensions-api/docs/dashext/trex_getstarted/\n      - type: APIReference\n        url: https://tableau.github.io/extensions-api/docs/trex_tableau_viz_ref/\n      - type: ChangeLog\n        url: https://tableau.github.io/extensions-api/docs/trex_release-notes/\n      - type: CodeExamples\n        url: https://tableau.github.io/extensions-api/docs/dashext/trex_examples/\n  - name: Tableau Web Data Connector\n    description: The Tableau Web Data Connector (WDC) provides an SDK for building connectors to any data accessible over HTTP, allowing users to bring external data into Tableau for analysis and visualization.\n    image: https://www.tableau.com/sites/default/files/tableau_logo_800.png\n    humanURL: https://help.tableau.com/current/api/webdataconnector/en-us/index.html\n    baseURL: https://[server]\n    tags:\n      - Connectors\n\
  \      - Data Integration\n      - HTTP\n      - JavaScript\n    properties:\n      - type: Documentation\n        url: https://help.tableau.com/current/api/webdataconnector/en-us/index.html\n      - type: APIReference\n        url: https://tableau.github.io/webdataconnector/docs/api_ref.html\n      - type: GitHubRepository\n        url: https://github.com/tableau/webdataconnector\n      - type: ChangeLog\n        url: https://help.tableau.com/current/api/webdataconnector/en-us/docs/wdc_whats_new.html\n      - type: Tutorials\n        url: https://tableau.github.io/webdataconnector/docs/wdc_tutorial.html\n      - type: CodeExamples\n        url: https://tableau.github.io/webdataconnector/docs/wdc_samples.html\n  - name: Tableau Connector SDK\n    description: SDK for developing custom Tableau connectors using ODBC or JDBC drivers, including documentation, example files, a test harness, and a packaging tool for distribution.\n    image: https://www.tableau.com/sites/default/files/tableau_logo_800.png\n\
  \    humanURL: https://tableau.github.io/connector-plugin-sdk/\n    baseURL: https://github.com/tableau/connector-plugin-sdk\n    tags:\n      - Connectors\n      - Custom Connectors\n      - JDBC\n      - ODBC\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://tableau.github.io/connector-plugin-sdk/docs/\n      - type: GitHubRepository\n        url: https://github.com/tableau/connector-plugin-sdk\n      - type: APIReference\n        url: https://tableau.github.io/connector-plugin-sdk/docs/api-reference\n      - type: CodeExamples\n        url: https://tableau.github.io/connector-plugin-sdk/docs/example\n      - type: GettingStarted\n        url: https://tableau.github.io/connector-plugin-sdk/docs/\n  - name: Tableau Analytics Extensions API\n    description: The Analytics Extensions API allows integration of external analytics engines such as Python, R, MATLAB, and data science platforms with Tableau calculations for advanced analytics.\n    image: https://www.tableau.com/sites/default/files/tableau_logo_800.png\n\
  \    humanURL: https://tableau.github.io/analytics-extensions-api/docs/ae_intro.html\n    baseURL: https://[server]\n    tags:\n      - Analytics\n      - Data Science\n      - Machine Learning\n      - Python\n      - R\n    properties:\n      - type: Documentation\n        url: https://tableau.github.io/analytics-extensions-api/docs/ae_intro.html\n      - type: CodeExamples\n        url: https://tableau.github.io/analytics-extensions-api/docs/ae_example_tabpy.html\n      - type: GettingStarted\n        url: https://tableau.github.io/analytics-extensions-api/docs/ae_connect_desktop.html\n      - type: APIReference\n        url: https://tableau.github.io/analytics-extensions-api/docs/ae_summary.html\n      - type: GitHubRepository\n        url: https://github.com/tableau/TabPy\n  - name: Tableau Webhooks\n    description: Tableau Webhooks enable event-driven automation by sending HTTP POST notifications to specified URLs when events occur on Tableau Server or Tableau Cloud.\n    image:\
  \ https://www.tableau.com/sites/default/files/tableau_logo_800.png\n    humanURL: https://help.tableau.com/current/developer/webhooks/en-us/\n    baseURL: https://[server]/api/[api-version]\n    tags:\n      - Automation\n      - Events\n      - Notifications\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://help.tableau.com/current/developer/webhooks/en-us/\n      - type: GitHubRepository\n        url: https://github.com/tableau/webhooks-docs\n      - type: GettingStarted\n        url: https://help.tableau.com/current/developer/webhooks/en-us/docs/webhooks-get-started.html\n      - type: APIReference\n        url: https://help.tableau.com/current/developer/webhooks/en-us/docs/webhooks-events-payload.html\n  - name: Tableau VizQL Data Service\n    description: The VizQL Data Service provides a programmatic HTTP interface to query published data sources outside of Tableau visualizations, enabling headless data access from any application.\n    image:\
  \ https://www.tableau.com/sites/default/files/tableau_logo_800.png\n    humanURL: https://help.tableau.com/current/api/vizql-data-service/en-us/index.html\n    baseURL: https://[server]/api/v1\n    tags:\n      - Data Access\n      - Headless\n      - Query\n      - REST\n    properties:\n      - type: Documentation\n        url: https://help.tableau.com/current/api/vizql-data-service/en-us/index.html\n      - type: APIReference\n        url: https://help.tableau.com/current/api/vizql-data-service/en-us/reference/index.html\n      - type: ChangeLog\n        url: https://help.tableau.com/current/api/vizql-data-service/en-us/docs/vds_whats_new.html\n      - type: GitHubRepository\n        url: https://github.com/tableau/VizQL-Data-Service\n      - type: GettingStarted\n        url: https://help.tableau.com/current/api/vizql-data-service/en-us/docs/vds_create_queries.html\n  - name: Tableau Pulse API\n    description: The Tableau Pulse API enables programmatic creation, management, and querying\
  \ of Tableau Pulse metrics and subscriptions, as well as embedding Pulse insights into web applications.\n    image: https://www.tableau.com/sites/default/files/tableau_logo_800.png\n    humanURL: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_ref_pulse.htm\n    baseURL: https://[server]/api/[api-version]\n    tags:\n      - Analytics\n      - Insights\n      - Metrics\n      - Pulse\n    properties:\n      - type: Documentation\n        url: https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_ref_pulse.htm\n      - type: APIReference\n        url: https://help.tableau.com/current/api/embedding_api/en-us/reference/interfaces/pulse.html\n      - type: GitHubRepository\n        url: https://github.com/tableau/pulse-api-utilities\nmaintainers:\n  - name: Tableau\n    email: developers@tableau.com\n    url: https://www.tableau.com\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ncommon:\n  - type: DeveloperPortal\n\
  \    url: https://www.tableau.com/developer\n  - type: Blog\n    url: https://www.tableau.com/blog/developers\n  - type: Support\n    url: https://www.tableau.com/support\n  - type: GitHubOrganization\n    url: https://github.com/tableau\n  - type: StatusPage\n    url: https://trust.tableau.com/\n  - type: ReleaseNotes\n    url: https://help.tableau.com/current/tableau/en-us/whatsnew_all.htm\n  - type: TermsOfService\n    url: https://www.tableau.com/legal\n  - type: PrivacyPolicy\n    url: https://www.tableau.com/privacy\n  - type: SignUp\n    url: https://www.tableau.com/products/trial\n  - type: Login\n    url: https://www.tableau.com/tableau-login-hub\n  - type: Documentation\n    url: https://help.tableau.com/\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/tableau\n  - type: YouTube\n    url: https://www.youtube.com/@Tableau\n  - type: Training\n    url: https://www.tableau.com/developer/learning\n  - type: SpectralRules\n    url: rules/tableau-spectral-rules.yml\n\
  \  - type: NaftikoCapability\n    url: capabilities/shared/tableau-rest.yaml\n    title: Tableau REST API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/content-management.yaml\n    title: Content Management Workflow\n  - type: Features\n    data:\n      - name: Data Source Management\n        description: Publish, query, update, delete, and download data sources that define connections to data shared across workbooks.\n      - name: Workbook Management\n        description: Publish, query, update, delete, and download workbooks containing views, dashboards, and stories.\n      - name: Site Administration\n        description: Create, configure, and manage Tableau Server and Cloud sites with full lifecycle control.\n      - name: User and Group Management\n        description: Add, update, and remove users and groups with role-based access control for content permissions.\n      - name: Permission Management\n        description: Query and set granular permissions\
  \ on workbooks, data sources, projects, views, and flows.\n      - name: Schedule and Subscription Management\n        description: Create and manage schedules for extract refreshes and subscriptions for automated content delivery.\n      - name: Embedded Analytics\n        description: Embed Tableau visualizations in web applications with interactive filtering and full API control.\n      - name: Metadata and Lineage\n        description: Query metadata about content, data sources, and data lineage using the GraphQL-based Metadata API.\n      - name: Custom Connectors\n        description: Build custom connectors using ODBC or JDBC drivers to bring any data source into Tableau.\n      - name: Webhooks\n        description: Enable event-driven automation with HTTP POST notifications when events occur on Tableau Server or Cloud.\n  - type: UseCases\n    data:\n      - name: Enterprise Reporting\n        description: Automate the creation and distribution of business reports and dashboards\
  \ across organizations.\n      - name: Embedded Analytics\n        description: Embed interactive visualizations and analytics directly into customer-facing applications.\n      - name: Data Governance\n        description: Track data lineage, manage permissions, and enforce data policies across the analytics platform.\n      - name: Self-Service Analytics\n        description: Enable business users to explore data and create visualizations without IT involvement.\n      - name: Content Migration\n        description: Programmatically migrate workbooks, data sources, and configurations between Tableau environments.\n  - type: Integrations\n    data:\n      - name: Salesforce\n        description: Native integration with Salesforce CRM for unified analytics across sales, service, and marketing data.\n      - name: Slack\n        description: Share Tableau visualizations and receive metric alerts directly in Slack channels.\n      - name: Python and R\n        description: Extend Tableau\
  \ calculations with Python and R scripts through the Analytics Extensions API.\n      - name: Snowflake\n        description: Optimized connector for Snowflake data warehouse with live query and extract support.\n      - name: Google BigQuery\n        description: Connect to Google BigQuery for large-scale data analytics and visualization.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tableau/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Dashboards
- Data Visualization
url: https://www.tableau.com
use_cases:
- description: Automate the creation and distribution of business reports and dashboards across organizations.
  name: Enterprise Reporting
- description: Embed interactive visualizations and analytics directly into customer-facing applications.
  name: Embedded Analytics
- description: Track data lineage, manage permissions, and enforce data policies across the analytics platform.
  name: Data Governance
- description: Enable business users to explore data and create visualizations without IT involvement.
  name: Self-Service Analytics
- description: Programmatically migrate workbooks, data sources, and configurations between Tableau environments.
  name: Content Migration
---
