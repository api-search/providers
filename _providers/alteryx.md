---
api_count: 7
apis:
- description: 'REST API for managing workflows, schedules, and jobs on Alteryx Server. Provides Subscription, User V2, Admin V1, Admin V2, and V3 API endpoints for creating, updating, searching, and deleting users, '
  name: Alteryx Server API
  slug: ''
- description: The V3 Admin API for Alteryx Server uses OAuth 2 authentication and implements POST, PUT, GET, and DELETE functionality for modifying assets, users, credentials, and connections so admins can automate
  name: Alteryx Server API V3
  slug: ''
- description: The V1 API for Alteryx Server provides endpoints for admins including the Migratable Endpoint for migrating workflows across Server environments and the Auditlog Endpoint for tracking changes to syste
  name: Alteryx Server API V1
  slug: ''
- description: API for interacting with Alteryx Analytics Gallery for workflow sharing and execution.
  name: Alteryx Gallery API
  slug: ''
- description: API for Alteryx Connect data catalog and collaboration platform.
  name: Alteryx Connect API
  slug: ''
- description: The AlteryxEngine API allows you to call into the Alteryx Engine to build applications that can programmatically execute Alteryx Designer workflows. Workflows and applications can be executed as a sep
  name: Alteryx AlteryxEngine API
  slug: ''
- description: REST API for Alteryx Designer Cloud (powered by Trifacta) providing data preparation, transformation, and pipeline management capabilities. Enables programmatic access to data preparation workflows an
  name: Alteryx Designer Cloud API
  slug: ''
capabilities:
- description: 'Analytics automation workflow combining Alteryx Server V3 API for workflow management, job execution, scheduling, user administration, credential management, and collection organization. Used by data '
  name: Alteryx Analytics Automation
  slug: analytics-automation
common:
- title: ''
  type: DeveloperPortal
  url: https://help.alteryx.com/current/en/developer-help.html
- title: ''
  type: GettingStarted
  url: https://help.alteryx.com/current/en/developer-help/apis/get-started-with-apis.html
- title: ''
  type: SDK
  url: https://help.alteryx.com/current/en/developer-help/platform-sdk.html
- title: ''
  type: StatusPage
  url: https://status.alteryx.com
- title: ''
  type: Support
  url: https://community.alteryx.com
- title: ''
  type: Blog
  url: https://community.alteryx.com/t5/Engine-Works/bg-p/engine-works
- title: ''
  type: X
  url: https://twitter.com/alteryx
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/alteryx
- title: ''
  type: GitHubOrganization
  url: https://github.com/alteryx
- title: ''
  type: Pricing
  url: https://www.alteryx.com/products/pricing
- title: ''
  type: TrustCenter
  url: https://www.alteryx.com/trust
- title: ''
  type: TermsOfService
  url: https://www.alteryx.com/terms-and-conditions
- title: ''
  type: PrivacyPolicy
  url: https://www.alteryx.com/privacy-policy
- title: ''
  type: Legal
  url: https://www.alteryx.com/legal
created: '2024-01-15'
description: Alteryx is an analytics automation platform that enables data analysts and scientists to break data barriers, deliver insights, and experience the thrill of getting to the answer faster.
features:
- description: Visual drag-and-drop workflow builder for automating data preparation, blending, and analytics pipelines.
  name: Workflow Automation
- description: Schedule workflows to run at specific times or intervals for automated recurring analytics processes.
  name: Scheduled Execution
- description: Fine-grained user management with role-based access control for shared workflow environments.
  name: User and Access Management
- description: Secure storage and sharing of data source credentials across workflows and users.
  name: Credential Management
- description: Organize workflows, schedules, and users into collections for logical grouping and permission management.
  name: Collection Organization
- description: Browser-based data preparation and transformation through Designer Cloud with AI-assisted suggestions.
  name: Cloud Data Preparation
image: https://www.alteryx.com/sites/default/files/alteryx-logo-2021.svg
integrations:
- description: Native connector for reading from and writing to Snowflake data warehouse for cloud analytics.
  name: Snowflake
- description: Publish prepared data directly to Tableau Server for visualization and business intelligence.
  name: Tableau
- description: Connect to Salesforce CRM data for analytics, reporting, and automated data synchronization.
  name: Salesforce
- description: Read and write data to Amazon S3 for cloud-based data lake analytics workflows.
  name: AWS S3
- description: Integration with Azure data services including SQL Database, Blob Storage, and Synapse Analytics.
  name: Microsoft Azure
jsonld:
- class_count: 0
  name: Alteryx Context
  property_count: 8
  slug: alteryx-context
- class_count: 0
  name: Alteryx Server V3 Context
  property_count: 0
  slug: alteryx-server-v3-context
layout: provider
modified: '2026-04-18'
name: Alteryx
rules:
- name: Alteryx API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: alteryx-spectral-rules
skills: []
slug: alteryx
solutions: []
source_yaml: "aid: alteryx\nname: Alteryx\ndescription: >-\n  Alteryx is an analytics automation platform that enables data analysts and\n  scientists to break data barriers, deliver insights, and experience the thrill\n  of getting to the answer faster.\nimage: https://www.alteryx.com/sites/default/files/alteryx-logo-2021.svg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/alteryx/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Analytics\n  - Automation\n  - Data Engineering\n  - Data Preparation\n  - Data Science\n  - ETL\n  - Machine Learning\n  - Predictive Analytics\napis:\n  - name: Alteryx Server API\n    description: >-\n      REST API for managing workflows, schedules, and jobs on Alteryx Server.\n      Provides Subscription, User V2, Admin V1, Admin V2, and V3 API endpoints\n      for creating, updating, searching, and deleting users, user groups,\n      schedules, credentials, collections, workflows,\
  \ and Server connections.\n    image: https://www.alteryx.com/sites/default/files/alteryx-logo-2021.svg\n    humanURL: https://help.alteryx.com/current/en/server/api-overview.html\n    baseURL: https://your-server/webapi\n    tags:\n      - Automation\n      - Jobs\n      - Scheduling\n      - Server\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://help.alteryx.com/current/en/server/api-overview.html\n      - type: APIReference\n        url: https://help.alteryx.com/developer-help/server-api-reference\n      - type: Authentication\n        url: https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v3/server-api-configuration-and-authorization.html\n      - type: GettingStarted\n        url: https://help.alteryx.com/current/en/developer-help/apis/get-started-with-apis.html\n    contact:\n      - FN: Alteryx Support\n        email: support@alteryx.com\n        url: https://community.alteryx.com\n  - name: Alteryx Server API V3\n\
  \    description: >-\n      The V3 Admin API for Alteryx Server uses OAuth 2 authentication and\n      implements POST, PUT, GET, and DELETE functionality for modifying assets,\n      users, credentials, and connections so admins can automate tasks and\n      integrate Server with their existing API automation tools.\n    image: https://www.alteryx.com/sites/default/files/alteryx-logo-2021.svg\n    humanURL: https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v3.html\n    baseURL: https://your-server/webapi/v3\n    tags:\n      - Admin\n      - Credentials\n      - OAuth2\n      - Server\n      - Users\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v3.html\n      - type: Authentication\n        url: https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v3/server-api-configuration-and-authorization.html\n      - type: OpenAPI\n        url:\
  \ openapi/alteryx-server-api-v3.yml\n    contact:\n      - FN: Alteryx Support\n        email: support@alteryx.com\n        url: https://community.alteryx.com\n  - name: Alteryx Server API V1\n    description: >-\n      The V1 API for Alteryx Server provides endpoints for admins including the\n      Migratable Endpoint for migrating workflows across Server environments and\n      the Auditlog Endpoint for tracking changes to system entities.\n    image: https://www.alteryx.com/sites/default/files/alteryx-logo-2021.svg\n    humanURL: https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v1.html\n    baseURL: https://your-server/webapi/v1\n    tags:\n      - Admin\n      - Audit\n      - Migration\n      - Server\n    properties:\n      - type: Documentation\n        url: https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v1.html\n    contact:\n      - FN: Alteryx Support\n        email: support@alteryx.com\n        url: https://community.alteryx.com\n\
  \  - name: Alteryx Gallery API\n    description: >-\n      API for interacting with Alteryx Analytics Gallery for workflow sharing and\n      execution.\n    image: https://www.alteryx.com/sites/default/files/alteryx-logo-2021.svg\n    humanURL: https://help.alteryx.com/developer-help/gallery-api-overview\n    baseURL: https://gallery.alteryx.com/api\n    tags:\n      - Gallery\n      - Public API\n      - Sharing\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://help.alteryx.com/developer-help/gallery-api-overview\n      - type: APIReference\n        url: https://help.alteryx.com/developer-help/gallery-api-reference\n      - type: Authentication\n        url: https://help.alteryx.com/developer-help/gallery-api-authentication\n    contact:\n      - FN: Alteryx Support\n        email: support@alteryx.com\n        url: https://community.alteryx.com\n  - name: Alteryx Connect API\n    description: >-\n      API for Alteryx Connect data catalog and collaboration\
  \ platform.\n    image: https://www.alteryx.com/sites/default/files/alteryx-logo-2021.svg\n    humanURL: https://help.alteryx.com/developer-help/connect-api\n    baseURL: https://your-connect-server/api\n    tags:\n      - Collaboration\n      - Data Catalog\n      - Governance\n      - Metadata\n    properties:\n      - type: Documentation\n        url: https://help.alteryx.com/developer-help/connect-api\n      - type: Authentication\n        url: https://help.alteryx.com/developer-help/connect-authentication\n    contact:\n      - FN: Alteryx Support\n        email: support@alteryx.com\n        url: https://community.alteryx.com\n  - name: Alteryx AlteryxEngine API\n    description: >-\n      The AlteryxEngine API allows you to call into the Alteryx Engine to build\n      applications that can programmatically execute Alteryx Designer workflows.\n      Workflows and applications can be executed as a separate child process or\n      in-process.\n    image: https://www.alteryx.com/sites/default/files/alteryx-logo-2021.svg\n\
  \    humanURL: https://help.alteryx.com/current/en/developer-help/apis/alteryxengine-api-overview.html\n    baseURL: https://your-server/api\n    tags:\n      - Designer\n      - Engine\n      - Execution\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://help.alteryx.com/current/en/developer-help/apis/alteryxengine-api-overview.html\n      - type: GettingStarted\n        url: https://help.alteryx.com/current/en/developer-help/apis/alteryxengine-api-overview/alteryxengine-api-example.html\n    contact:\n      - FN: Alteryx Support\n        email: support@alteryx.com\n        url: https://community.alteryx.com\n  - name: Alteryx Designer Cloud API\n    description: >-\n      REST API for Alteryx Designer Cloud (powered by Trifacta) providing data\n      preparation, transformation, and pipeline management capabilities. Enables\n      programmatic access to data preparation workflows and job execution.\n    image: https://www.alteryx.com/sites/default/files/alteryx-logo-2021.svg\n\
  \    humanURL: https://help.alteryx.com/dataprep/en/developer/api-reference.html\n    baseURL: https://api.trifacta.com\n    tags:\n      - Cloud\n      - Data Preparation\n      - Pipelines\n      - Transformation\n      - Trifacta\n    properties:\n      - type: Documentation\n        url: https://help.alteryx.com/dataprep/en/developer/api-reference.html\n      - type: APIReference\n        url: https://api.trifacta.com/\n      - type: Authentication\n        url: https://help.alteryx.com/Dataprep/en/developer/api-reference/manage-api-access-tokens.html\n    contact:\n      - FN: Alteryx Support\n        email: support@alteryx.com\n        url: https://community.alteryx.com\ncommon:\n  - type: DeveloperPortal\n    url: https://help.alteryx.com/current/en/developer-help.html\n  - type: GettingStarted\n    url: https://help.alteryx.com/current/en/developer-help/apis/get-started-with-apis.html\n  - type: SDK\n    url: https://help.alteryx.com/current/en/developer-help/platform-sdk.html\n\
  \  - type: StatusPage\n    url: https://status.alteryx.com\n  - type: Support\n    url: https://community.alteryx.com\n  - type: Blog\n    url: https://community.alteryx.com/t5/Engine-Works/bg-p/engine-works\n  - type: X\n    url: https://twitter.com/alteryx\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/alteryx\n  - type: GitHubOrganization\n    url: https://github.com/alteryx\n  - type: Pricing\n    url: https://www.alteryx.com/products/pricing\n  - type: TrustCenter\n    url: https://www.alteryx.com/trust\n  - type: TermsOfService\n    url: https://www.alteryx.com/terms-and-conditions\n  - type: PrivacyPolicy\n    url: https://www.alteryx.com/privacy-policy\n  - type: Legal\n    url: https://www.alteryx.com/legal\n  - type: Features\n    data:\n      - name: Workflow Automation\n        description: Visual drag-and-drop workflow builder for automating data preparation, blending, and analytics pipelines.\n      - name: Scheduled Execution\n        description: Schedule\
  \ workflows to run at specific times or intervals for automated recurring analytics processes.\n      - name: User and Access Management\n        description: Fine-grained user management with role-based access control for shared workflow environments.\n      - name: Credential Management\n        description: Secure storage and sharing of data source credentials across workflows and users.\n      - name: Collection Organization\n        description: Organize workflows, schedules, and users into collections for logical grouping and permission management.\n      - name: Cloud Data Preparation\n        description: Browser-based data preparation and transformation through Designer Cloud with AI-assisted suggestions.\n  - type: UseCases\n    data:\n      - name: Automated Reporting Pipelines\n        description: Schedule and automate data preparation workflows to generate recurring business reports.\n      - name: Data Migration\n        description: Migrate workflows and configurations\
  \ across Server environments using the V1 migration API.\n      - name: Server Administration Automation\n        description: Automate user provisioning, credential management, and workflow deployment through the V3 admin API.\n      - name: Self-Service Analytics\n        description: Enable business users to discover and run published workflows through the Gallery API.\n      - name: Enterprise Data Catalog\n        description: Catalog and discover data assets across the organization using Alteryx Connect APIs.\n  - type: Integrations\n    data:\n      - name: Snowflake\n        description: Native connector for reading from and writing to Snowflake data warehouse for cloud analytics.\n      - name: Tableau\n        description: Publish prepared data directly to Tableau Server for visualization and business intelligence.\n      - name: Salesforce\n        description: Connect to Salesforce CRM data for analytics, reporting, and automated data synchronization.\n      - name: AWS S3\n\
  \        description: Read and write data to Amazon S3 for cloud-based data lake analytics workflows.\n      - name: Microsoft Azure\n        description: Integration with Azure data services including SQL Database, Blob Storage, and Synapse Analytics.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://www.alteryx.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/alteryx/refs/heads/main/apis.yml
tags:
- Analytics
- Automation
- Data Engineering
- Data Preparation
- Data Science
- ETL
- Machine Learning
- Predictive Analytics
url: https://raw.githubusercontent.com/api-evangelist/alteryx/refs/heads/main/apis.yml
use_cases:
- description: Schedule and automate data preparation workflows to generate recurring business reports.
  name: Automated Reporting Pipelines
- description: Migrate workflows and configurations across Server environments using the V1 migration API.
  name: Data Migration
- description: Automate user provisioning, credential management, and workflow deployment through the V3 admin API.
  name: Server Administration Automation
- description: Enable business users to discover and run published workflows through the Gallery API.
  name: Self-Service Analytics
- description: Catalog and discover data assets across the organization using Alteryx Connect APIs.
  name: Enterprise Data Catalog
---
