---
api_count: 69
apis:
- description: Qlik provides APIs to support automation, configuration, observability, and integration with third-party applications to incorporate Qlik Cloud capabilities directly into those applications.
  name: Qlik
  slug: qlik
- description: Manages Qlik Cloud Analytics applications, including creating, updating, copying, publishing, and deleting apps. Apps are a core part of Qlik Cloud Analytics and represent either an Analytics app or a
  name: Qlik Apps API
  slug: apps
- description: Manages user resources within Qlik Cloud tenants. Users represent clients accessing the Qlik Cloud tenant, with support for listing, creating, updating, deleting users and managing invitations.
  name: Qlik Users API
  slug: users
- description: Manages logical containers within a Qlik tenant that control access for users and groups through space roles to determine what content users can access.
  name: Qlik Spaces API
  slug: spaces
- description: Provides a list of core resources in the Qlik platform, including resources such as apps, automations, and data sets that a user has access to.
  name: Qlik Items API
  slug: items
- description: Manages API key lifecycle for authenticating with Qlik Cloud APIs, including creating, listing, and revoking API keys.
  name: Qlik API Keys API
  slug: api-keys
- description: Provides access to events emitted upon each action taken in a Qlik Cloud tenant, offering detailed access to what is happening in the tenant. Events are stored for 90 days.
  name: Qlik Audits API
  slug: audits
- description: Manages automations in Qlik Automate, which are no-code workflows connecting applications together. Supports creating, updating, deleting, and executing automations.
  name: Qlik Automations API
  slug: automations
- description: Manages connections used by automations to interact with external services and applications within Qlik Automate.
  name: Qlik Automation Connections API
  slug: automation-connections
- description: Manages connectors available for automations in Qlik Automate, providing integration capabilities with third-party services.
  name: Qlik Automation Connectors API
  slug: automation-connectors
- description: Manages AutoML dataset predictions, enabling batch prediction workflows on datasets using trained machine learning models.
  name: Qlik AutoML Dataset Predictions API
  slug: automl-predictions
- description: Manages AutoML real-time prediction deployments, enabling on-demand predictions using trained machine learning models.
  name: Qlik AutoML Real-Time Predictions API
  slug: automl-deployments
- description: Manages AI assistants within Qlik Cloud, enabling conversational analytics and natural language interactions with data.
  name: Qlik Assistants API
  slug: assistants
- description: Manages tenant-wide banner notifications displayed to users within the Qlik Cloud interface.
  name: Qlik Banners API
  slug: banners
- description: Manages branding and customization of the Qlik Cloud tenant appearance, including logos, colors, and styling.
  name: Qlik Brands API
  slug: brands
- description: Provides the framework to catalog various content a user has access to using tags, public and private collections, and favorites.
  name: Qlik Collections API
  slug: collections
- description: Manages conditions used for evaluating expressions and triggering actions within Qlik Cloud.
  name: Qlik Conditions API
  slug: conditions
- description: Manages Content Security Policy origins, controlling which external domains can interact with the Qlik Cloud tenant.
  name: Qlik CSP Origins API
  slug: csp-origins
- description: Provides CSRF tokens for securing requests to Qlik Cloud APIs against cross-site request forgery attacks.
  name: Qlik CSRF Token API
  slug: csrf-token
- description: Manages data-driven alerts that notify users when conditions in their data are met within Qlik Cloud.
  name: Qlik Data Alerts API
  slug: data-alerts
- description: Manages data assets within the Qlik Cloud catalog, providing metadata and governance for data resources.
  name: Qlik Data Assets API
  slug: data-assets
- description: Manages connections between Qlik Cloud Analytics apps and Data Integration projects and external data sources.
  name: Qlik Data Connections API
  slug: data-connections
- description: Manages credentials used by data connections to authenticate with external data sources.
  name: Qlik Data Credentials API
  slug: data-credentials
- description: Manages data files uploaded to Qlik Cloud for use in analytics applications and data integration projects.
  name: Qlik Data Files API
  slug: data-files
- description: Manages data sets within Qlik Cloud's catalog system. A data set is a member of a data asset, with support for creation, retrieval, update, and profile management.
  name: Qlik Data Sets API
  slug: data-sets
- description: Manages data source configurations for Qlik Cloud, defining the external systems from which data can be loaded.
  name: Qlik Data Sources API
  slug: data-sources
- description: Manages data stores used in Qlik Cloud for data warehousing and integration scenarios.
  name: Qlik Data Stores API
  slug: data-stores
- description: Manages data quality assessments and profiles for data assets within Qlik Cloud.
  name: Qlik Data Qualities API
  slug: data-qualities
- description: Manages data integration projects for building data pipelines and transformation workflows within Qlik Cloud.
  name: Qlik Data Integration Projects API
  slug: di-projects
- description: Manages Direct Access Agents that provide secure connectivity between Qlik Cloud and on-premises data sources.
  name: Qlik Direct Access Agents API
  slug: direct-access-agents
- description: Manages encryption keys and configurations for securing data at rest within Qlik Cloud.
  name: Qlik Encryption API
  slug: encryption
- description: Tracks and reports on entitlement consumption metrics for Qlik Cloud license usage.
  name: Qlik Entitlement Consumption API
  slug: consumption
- description: Manages visualization extensions in Qlik Sense, allowing third-party visualizations and other presentation objects to be used in the Qlik Sense client.
  name: Qlik Extensions API
  slug: extensions
- description: Manages business glossaries for defining and sharing terminology and definitions across the Qlik Cloud tenant.
  name: Qlik Glossaries API
  slug: glossaries
- description: Manages groups within Qlik Cloud to which space and tenant roles can be assigned to simplify access control management.
  name: Qlik Groups API
  slug: groups
- description: Manages identity provider configurations for Qlik Cloud, enabling integration with external authentication systems.
  name: Qlik Identity Providers API
  slug: identity-providers
- description: Manages knowledge bases used by Qlik AI assistants and natural language features for conversational analytics.
  name: Qlik Knowledgebases API
  slug: knowledgebases
- description: Manages tenant and user license entitlements in Qlik Cloud, including assignments, consumption tracking, and auto-assignment configuration.
  name: Qlik Licenses API
  slug: licenses
- description: Manages data lineage graph visualizations that trace the origin and transformation of data across Qlik Cloud resources.
  name: Qlik Lineage Graphs API
  slug: lineage-graphs
- description: Manages login flows and session management for accessing Qlik Cloud.
  name: Qlik Login API
  slug: login
- description: Manages machine learning experiments, models, and deployments within Qlik Cloud for predictive analytics.
  name: Qlik Machine Learning API
  slug: ml
- description: Enables natural language question and answer interactions with data in Qlik Cloud analytics applications.
  name: Qlik Natural Language API
  slug: questions
- description: Manages notes and annotations attached to Qlik Cloud analytics content for collaboration and documentation.
  name: Qlik Notes API
  slug: notes
- description: Manages notification preferences and delivery for Qlik Cloud events and alerts.
  name: Qlik Notifications API
  slug: notifications
- description: Manages OAuth 2.0 authorization flows for secure authentication with Qlik Cloud APIs.
  name: Qlik OAuth API
  slug: oauth
- description: Manages OAuth client registrations for applications integrating with Qlik Cloud through OAuth 2.0.
  name: Qlik OAuth Clients API
  slug: oauth-clients
- description: Lists and revokes active OAuth tokens for managing authenticated sessions in Qlik Cloud.
  name: Qlik OAuth Tokens API
  slug: oauth-tokens
- description: Returns OAuth 2.0 metadata related to the tenant, including authorization endpoint, token endpoint, and supported grant types.
  name: Qlik OAuth Well-Known Configuration API
  slug: well-known
- description: Returns entitled attributes based on the license, providing information about resource limits and usage quotas.
  name: Qlik Quotas API
  slug: quotas
- description: Manages scheduled reload tasks for analytics applications, enabling automated data refresh on defined schedules.
  name: Qlik Reload Tasks API
  slug: reload-tasks
- description: Triggers and manages app data reloads to refresh analytics application data via REST API instead of only through the JSON-RPC WebSocket API.
  name: Qlik Reloads API
  slug: reloads
- description: Manages report templates that define the structure and formatting of generated reports from Qlik analytics data.
  name: Qlik Report Templates API
  slug: report-templates
- description: Generates downloadable report assets from data in analytics applications, supporting multiple output formats including Excel, PDF, PowerPoint, HTML, and images.
  name: Qlik Reports API
  slug: reports
- description: Manages tenant roles that are assigned to users or groups to control permissions and access within Qlik Cloud.
  name: Qlik Roles API
  slug: roles
- description: Manages sharing tasks for distributing analytics content and reports to recipients within Qlik Cloud.
  name: Qlik Sharing Tasks API
  slug: sharing-tasks
- description: Manages general task scheduling and execution within Qlik Cloud for orchestrating platform operations.
  name: Qlik Tasks API
  slug: tasks
- description: Manages temporary content storage for file uploads and transient data within Qlik Cloud.
  name: Qlik Temporary Contents API
  slug: temp-contents
- description: Manages Qlik Cloud tenant configurations, settings, and metadata.
  name: Qlik Tenants API
  slug: tenants
- description: Manages tenant-level configuration settings for customizing the behavior of the Qlik Cloud platform.
  name: Qlik Tenant Settings API
  slug: tenant-settings
- description: Manages themes for customizing the styling and appearance of the Qlik Sense client experience, including uploading, downloading, and managing theme archives.
  name: Qlik Themes API
  slug: themes
- description: Manages email transport configuration for sending notifications and reports from Qlik Cloud.
  name: Qlik Email Configuration API
  slug: transports
- description: Manages administrator-defined pinned links displayed in the Qlik Cloud interface for quick access to resources.
  name: Qlik Pinned Links API
  slug: ui-config
- description: Manages web integration configurations that allow external websites to embed and interact with Qlik Cloud content.
  name: Qlik Web Integrations API
  slug: web-integrations
- description: Manages web-based push notifications for real-time updates within the Qlik Cloud user interface.
  name: Qlik Web Notifications API
  slug: web-notifications
- description: Manages webhooks for providing real-time event information from Qlik Cloud to external applications, with delivery history tracking.
  name: Qlik Webhooks API
  slug: webhooks
- description: Manages IP restriction policies for controlling network access to the Qlik Cloud tenant.
  name: Qlik IP Policies API
  slug: ip-policies
- description: Manages change store configurations for tracking and storing changes in analytics data.
  name: Qlik Change Stores API
  slug: change-stores
- description: Manages data products within the Qlik data governance framework, enabling the packaging and sharing of curated data assets.
  name: Qlik Data Products API
  slug: data-products
- description: The JSON-RPC API over WebSocket that enables interaction with the Qlik Associative Engine for Qlik Sense applications, providing session-based access to app data models, objects, and calculations.
  name: Qlik Engine JSON-RPC API
  slug: qix
common:
- title: ''
  type: DeveloperPortal
  url: https://qlik.dev
- title: ''
  type: Authentication
  url: https://qlik.dev/authenticate
- title: ''
  type: GettingStarted
  url: https://qlik.dev/get-started
- title: ''
  type: SDK
  url: https://qlik.dev/toolkits/qlik-api/
- title: ''
  type: CLI
  url: https://qlik.dev/toolkits/qlik-cli/
- title: ''
  type: Documentation
  url: https://qlik.dev/apis/rest/
- title: ''
  type: RateLimits
  url: https://qlik.dev/apis/rest/rate-limiting/
- title: ''
  type: CodeExamples
  url: https://qlik.dev/examples/
- title: ''
  type: ChangeLog
  url: https://qlik.dev/changelog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/qlik-oss
- title: ''
  type: StatusPage
  url: https://status.qlikcloud.com/
- title: ''
  type: Blog
  url: https://community.qlik.com/t5/Qlik-Design-Blog/bg-p/qlik-design-blog
- title: ''
  type: Community
  url: https://community.qlik.com
- title: ''
  type: Support
  url: https://support.qlik.com
- title: ''
  type: TermsOfService
  url: https://www.qlik.com/us/legal/license-terms
- title: ''
  type: PrivacyPolicy
  url: https://www.qlik.com/us/legal/privacy
created: '2025-02-24'
description: APIs for Qlik's analytics and data integration platform.
features: []
image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo.png
integrations: []
layout: provider
modified: '2026-04-19'
name: Qlik
skills: []
slug: qlik
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: qlik\nname: Qlik\ndescription: >-\n  APIs for Qlik's analytics and data integration platform.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo.png\ntags: []\ncreated: '2025-02-24'\nmodified: '2026-04-19'\nurl: https://raw.githubusercontent.com/api-evangelist/qlik/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: qlik:qlik\n    name: Qlik\n    description: >-\n      Qlik provides APIs to support automation, configuration, observability, and\n      integration with third-party applications to incorporate Qlik Cloud\n      capabilities directly into those applications.\n    humanURL: https://qlik.dev/apis/\n    baseURL: https://{tenant}.{region}.qlikcloud.com/api/v1\n    tags: []\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/\n      - type: GettingStarted\n        url: https://qlik.dev/get-started\n  - aid: qlik:apps\n    name: Qlik Apps API\n\
  \    description: >-\n      Manages Qlik Cloud Analytics applications, including creating, updating,\n      copying, publishing, and deleting apps. Apps are a core part of Qlik Cloud\n      Analytics and represent either an Analytics app or a script.\n    humanURL: https://qlik.dev/apis/rest/apps/\n    tags:\n      - Analytics\n      - Applications\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/apps/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/apps.json\n  - aid: qlik:users\n    name: Qlik Users API\n    description: >-\n      Manages user resources within Qlik Cloud tenants. Users represent clients\n      accessing the Qlik Cloud tenant, with support for listing, creating,\n      updating, deleting users and managing invitations.\n    humanURL: https://qlik.dev/apis/rest/users/\n    tags:\n      - Users\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/users/\n      - type: OpenAPI\n    \
  \    url: https://qlik.dev/specs/rest/users.json\n  - aid: qlik:spaces\n    name: Qlik Spaces API\n    description: >-\n      Manages logical containers within a Qlik tenant that control access for\n      users and groups through space roles to determine what content users can\n      access.\n    humanURL: https://qlik.dev/apis/rest/spaces/\n    tags:\n      - Access Control\n      - Spaces\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/spaces/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/spaces.json\n  - aid: qlik:items\n    name: Qlik Items API\n    description: >-\n      Provides a list of core resources in the Qlik platform, including resources\n      such as apps, automations, and data sets that a user has access to.\n    humanURL: https://qlik.dev/apis/rest/items/\n    tags:\n      - Items\n      - Resources\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/items/\n      - type: OpenAPI\n\
  \        url: https://qlik.dev/specs/rest/items.json\n  - aid: qlik:api-keys\n    name: Qlik API Keys API\n    description: >-\n      Manages API key lifecycle for authenticating with Qlik Cloud APIs, including\n      creating, listing, and revoking API keys.\n    humanURL: https://qlik.dev/apis/rest/api-keys/\n    tags:\n      - API Keys\n      - Authentication\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/api-keys/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/api-keys.json\n  - aid: qlik:audits\n    name: Qlik Audits API\n    description: >-\n      Provides access to events emitted upon each action taken in a Qlik Cloud\n      tenant, offering detailed access to what is happening in the tenant. Events\n      are stored for 90 days.\n    humanURL: https://qlik.dev/apis/rest/audits/\n    tags:\n      - Audits\n      - Events\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/audits/\n\
  \      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/audits.json\n  - aid: qlik:automations\n    name: Qlik Automations API\n    description: >-\n      Manages automations in Qlik Automate, which are no-code workflows connecting\n      applications together. Supports creating, updating, deleting, and executing\n      automations.\n    humanURL: https://qlik.dev/apis/rest/automations/\n    tags:\n      - Automations\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/automations/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/automations.json\n  - aid: qlik:automation-connections\n    name: Qlik Automation Connections API\n    description: >-\n      Manages connections used by automations to interact with external services\n      and applications within Qlik Automate.\n    humanURL: https://qlik.dev/apis/rest/automation-connections/\n    tags:\n      - Automations\n      - Connections\n    properties:\n\
  \      - type: Documentation\n        url: https://qlik.dev/apis/rest/automation-connections/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/automation-connections.json\n  - aid: qlik:automation-connectors\n    name: Qlik Automation Connectors API\n    description: >-\n      Manages connectors available for automations in Qlik Automate, providing\n      integration capabilities with third-party services.\n    humanURL: https://qlik.dev/apis/rest/automation-connectors/\n    tags:\n      - Automations\n      - Connectors\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/automation-connectors/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/automation-connectors.json\n  - aid: qlik:automl-predictions\n    name: Qlik AutoML Dataset Predictions API\n    description: >-\n      Manages AutoML dataset predictions, enabling batch prediction workflows on\n      datasets using trained machine learning models.\n    humanURL: https://qlik.dev/apis/rest/automl-predictions/\n\
  \    tags:\n      - Machine Learning\n      - Predictions\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/automl-predictions/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/automl-predictions.json\n  - aid: qlik:automl-deployments\n    name: Qlik AutoML Real-Time Predictions API\n    description: >-\n      Manages AutoML real-time prediction deployments, enabling on-demand\n      predictions using trained machine learning models.\n    humanURL: https://qlik.dev/apis/rest/automl-deployments/\n    tags:\n      - Machine Learning\n      - Predictions\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/automl-deployments/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/automl-deployments.json\n  - aid: qlik:assistants\n    name: Qlik Assistants API\n    description: >-\n      Manages AI assistants within Qlik Cloud, enabling conversational analytics\n      and natural\
  \ language interactions with data.\n    humanURL: https://qlik.dev/apis/rest/assistants/\n    tags:\n      - AI\n      - Assistants\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/assistants/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/assistants.json\n  - aid: qlik:banners\n    name: Qlik Banners API\n    description: >-\n      Manages tenant-wide banner notifications displayed to users within the Qlik\n      Cloud interface.\n    humanURL: https://qlik.dev/apis/rest/banners/\n    tags:\n      - Banners\n      - Notifications\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/banners/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/banners.json\n  - aid: qlik:brands\n    name: Qlik Brands API\n    description: >-\n      Manages branding and customization of the Qlik Cloud tenant appearance,\n      including logos, colors, and styling.\n    humanURL: https://qlik.dev/apis/rest/brands/\n\
  \    tags:\n      - Branding\n      - Customization\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/brands/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/brands.json\n  - aid: qlik:collections\n    name: Qlik Collections API\n    description: >-\n      Provides the framework to catalog various content a user has access to using\n      tags, public and private collections, and favorites.\n    humanURL: https://qlik.dev/apis/rest/collections/\n    tags:\n      - Catalog\n      - Collections\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/collections/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/collections.json\n  - aid: qlik:conditions\n    name: Qlik Conditions API\n    description: >-\n      Manages conditions used for evaluating expressions and triggering actions\n      within Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/conditions/\n    tags:\n      - Conditions\n\
  \    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/conditions/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/conditions.json\n  - aid: qlik:csp-origins\n    name: Qlik CSP Origins API\n    description: >-\n      Manages Content Security Policy origins, controlling which external domains\n      can interact with the Qlik Cloud tenant.\n    humanURL: https://qlik.dev/apis/rest/csp-origins/\n    tags:\n      - Content Security Policy\n      - Security\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/csp-origins/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/csp-origins.json\n  - aid: qlik:csrf-token\n    name: Qlik CSRF Token API\n    description: >-\n      Provides CSRF tokens for securing requests to Qlik Cloud APIs against\n      cross-site request forgery attacks.\n    humanURL: https://qlik.dev/apis/rest/csrf-token/\n    tags:\n      - CSRF\n      - Security\n    properties:\n\
  \      - type: Documentation\n        url: https://qlik.dev/apis/rest/csrf-token/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/csrf-token.json\n  - aid: qlik:data-alerts\n    name: Qlik Data Alerts API\n    description: >-\n      Manages data-driven alerts that notify users when conditions in their data\n      are met within Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/data-alerts/\n    tags:\n      - Alerts\n      - Data\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/data-alerts/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/data-alerts.json\n  - aid: qlik:data-assets\n    name: Qlik Data Assets API\n    description: >-\n      Manages data assets within the Qlik Cloud catalog, providing metadata and\n      governance for data resources.\n    humanURL: https://qlik.dev/apis/rest/data-assets/\n    tags:\n      - Catalog\n      - Data Assets\n    properties:\n      - type: Documentation\n        url:\
  \ https://qlik.dev/apis/rest/data-assets/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/data-assets.json\n  - aid: qlik:data-connections\n    name: Qlik Data Connections API\n    description: >-\n      Manages connections between Qlik Cloud Analytics apps and Data Integration\n      projects and external data sources.\n    humanURL: https://qlik.dev/apis/rest/data-connections/\n    tags:\n      - Data Connections\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/data-connections/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/data-connections.json\n  - aid: qlik:data-credentials\n    name: Qlik Data Credentials API\n    description: >-\n      Manages credentials used by data connections to authenticate with external\n      data sources.\n    humanURL: https://qlik.dev/apis/rest/data-credentials/\n    tags:\n      - Credentials\n      - Data\n    properties:\n      - type: Documentation\n    \
  \    url: https://qlik.dev/apis/rest/data-credentials/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/data-credentials.json\n  - aid: qlik:data-files\n    name: Qlik Data Files API\n    description: >-\n      Manages data files uploaded to Qlik Cloud for use in analytics applications\n      and data integration projects.\n    humanURL: https://qlik.dev/apis/rest/data-files/\n    tags:\n      - Data Files\n      - Upload\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/data-files/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/data-files.json\n  - aid: qlik:data-sets\n    name: Qlik Data Sets API\n    description: >-\n      Manages data sets within Qlik Cloud's catalog system. A data set is a member\n      of a data asset, with support for creation, retrieval, update, and profile\n      management.\n    humanURL: https://qlik.dev/apis/rest/data-sets/\n    tags:\n      - Catalog\n      - Data Sets\n    properties:\n\
  \      - type: Documentation\n        url: https://qlik.dev/apis/rest/data-sets/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/data-sets.json\n  - aid: qlik:data-sources\n    name: Qlik Data Sources API\n    description: >-\n      Manages data source configurations for Qlik Cloud, defining the external\n      systems from which data can be loaded.\n    humanURL: https://qlik.dev/apis/rest/data-sources/\n    tags:\n      - Data Sources\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/data-sources/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/data-sources.json\n  - aid: qlik:data-stores\n    name: Qlik Data Stores API\n    description: >-\n      Manages data stores used in Qlik Cloud for data warehousing and integration\n      scenarios.\n    humanURL: https://qlik.dev/apis/rest/data-stores/\n    tags:\n      - Data Stores\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/data-stores/\n\
  \      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/data-stores.json\n  - aid: qlik:data-qualities\n    name: Qlik Data Qualities API\n    description: >-\n      Manages data quality assessments and profiles for data assets within Qlik\n      Cloud.\n    humanURL: https://qlik.dev/apis/rest/data-qualities/\n    tags:\n      - Data Quality\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/data-qualities/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/data-qualities.json\n  - aid: qlik:di-projects\n    name: Qlik Data Integration Projects API\n    description: >-\n      Manages data integration projects for building data pipelines and\n      transformation workflows within Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/di-projects/\n    tags:\n      - Data Integration\n      - Projects\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/di-projects/\n      - type: OpenAPI\n     \
  \   url: https://qlik.dev/specs/rest/di-projects.json\n  - aid: qlik:direct-access-agents\n    name: Qlik Direct Access Agents API\n    description: >-\n      Manages Direct Access Agents that provide secure connectivity between Qlik\n      Cloud and on-premises data sources.\n    humanURL: https://qlik.dev/apis/rest/direct-access-agents/\n    tags:\n      - Agents\n      - Direct Access\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/direct-access-agents/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/direct-access-agents.json\n  - aid: qlik:encryption\n    name: Qlik Encryption API\n    description: >-\n      Manages encryption keys and configurations for securing data at rest within\n      Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/encryption/\n    tags:\n      - Encryption\n      - Security\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/encryption/\n      - type: OpenAPI\n  \
  \      url: https://qlik.dev/specs/rest/encryption.json\n  - aid: qlik:consumption\n    name: Qlik Entitlement Consumption API\n    description: >-\n      Tracks and reports on entitlement consumption metrics for Qlik Cloud license\n      usage.\n    humanURL: https://qlik.dev/apis/rest/consumption/\n    tags:\n      - Consumption\n      - Licensing\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/consumption/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/consumption.json\n  - aid: qlik:extensions\n    name: Qlik Extensions API\n    description: >-\n      Manages visualization extensions in Qlik Sense, allowing third-party\n      visualizations and other presentation objects to be used in the Qlik Sense\n      client.\n    humanURL: https://qlik.dev/apis/rest/extensions/\n    tags:\n      - Extensions\n      - Visualizations\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/extensions/\n     \
  \ - type: OpenAPI\n        url: https://qlik.dev/specs/rest/extensions.json\n  - aid: qlik:glossaries\n    name: Qlik Glossaries API\n    description: >-\n      Manages business glossaries for defining and sharing terminology and\n      definitions across the Qlik Cloud tenant.\n    humanURL: https://qlik.dev/apis/rest/glossaries/\n    tags:\n      - Glossaries\n      - Governance\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/glossaries/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/glossaries.json\n  - aid: qlik:groups\n    name: Qlik Groups API\n    description: >-\n      Manages groups within Qlik Cloud to which space and tenant roles can be\n      assigned to simplify access control management.\n    humanURL: https://qlik.dev/apis/rest/groups/\n    tags:\n      - Access Control\n      - Groups\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/groups/\n      - type: OpenAPI\n        url:\
  \ https://qlik.dev/specs/rest/groups.json\n  - aid: qlik:identity-providers\n    name: Qlik Identity Providers API\n    description: >-\n      Manages identity provider configurations for Qlik Cloud, enabling\n      integration with external authentication systems.\n    humanURL: https://qlik.dev/apis/rest/identity-providers/\n    tags:\n      - Authentication\n      - Identity Providers\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/identity-providers/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/identity-providers.json\n  - aid: qlik:knowledgebases\n    name: Qlik Knowledgebases API\n    description: >-\n      Manages knowledge bases used by Qlik AI assistants and natural language\n      features for conversational analytics.\n    humanURL: https://qlik.dev/apis/rest/knowledgebases/\n    tags:\n      - AI\n      - Knowledge Bases\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/knowledgebases/\n\
  \      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/knowledgebases.json\n  - aid: qlik:licenses\n    name: Qlik Licenses API\n    description: >-\n      Manages tenant and user license entitlements in Qlik Cloud, including\n      assignments, consumption tracking, and auto-assignment configuration.\n    humanURL: https://qlik.dev/apis/rest/licenses/\n    tags:\n      - Licenses\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/licenses/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/licenses.json\n  - aid: qlik:lineage-graphs\n    name: Qlik Lineage Graphs API\n    description: >-\n      Manages data lineage graph visualizations that trace the origin and\n      transformation of data across Qlik Cloud resources.\n    humanURL: https://qlik.dev/apis/rest/lineage-graphs/\n    tags:\n      - Data Lineage\n      - Governance\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/lineage-graphs/\n\
  \      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/lineage-graphs.json\n  - aid: qlik:login\n    name: Qlik Login API\n    description: >-\n      Manages login flows and session management for accessing Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/login/\n    tags:\n      - Authentication\n      - Login\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/login/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/login.json\n  - aid: qlik:ml\n    name: Qlik Machine Learning API\n    description: >-\n      Manages machine learning experiments, models, and deployments within Qlik\n      Cloud for predictive analytics.\n    humanURL: https://qlik.dev/apis/rest/ml/\n    tags:\n      - Machine Learning\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/ml/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/ml.json\n  - aid: qlik:questions\n    name: Qlik Natural Language API\n\
  \    description: >-\n      Enables natural language question and answer interactions with data in Qlik\n      Cloud analytics applications.\n    humanURL: https://qlik.dev/apis/rest/questions/\n    tags:\n      - AI\n      - Natural Language\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/questions/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/questions.json\n  - aid: qlik:notes\n    name: Qlik Notes API\n    description: >-\n      Manages notes and annotations attached to Qlik Cloud analytics content for\n      collaboration and documentation.\n    humanURL: https://qlik.dev/apis/rest/notes/\n    tags:\n      - Collaboration\n      - Notes\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/notes/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/notes.json\n  - aid: qlik:notifications\n    name: Qlik Notifications API\n    description: >-\n      Manages notification preferences\
  \ and delivery for Qlik Cloud events and\n      alerts.\n    humanURL: https://qlik.dev/apis/rest/notifications/\n    tags:\n      - Notifications\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/notifications/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/notifications.json\n  - aid: qlik:oauth\n    name: Qlik OAuth API\n    description: >-\n      Manages OAuth 2.0 authorization flows for secure authentication with Qlik\n      Cloud APIs.\n    humanURL: https://qlik.dev/apis/rest/oauth/\n    tags:\n      - Authentication\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/oauth/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/oauth.json\n  - aid: qlik:oauth-clients\n    name: Qlik OAuth Clients API\n    description: >-\n      Manages OAuth client registrations for applications integrating with Qlik\n      Cloud through OAuth 2.0.\n    humanURL: https://qlik.dev/apis/rest/oauth-clients/\n\
  \    tags:\n      - Clients\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/oauth-clients/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/oauth-clients.json\n  - aid: qlik:oauth-tokens\n    name: Qlik OAuth Tokens API\n    description: >-\n      Lists and revokes active OAuth tokens for managing authenticated sessions in\n      Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/oauth-tokens/\n    tags:\n      - OAuth\n      - Tokens\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/oauth-tokens/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/oauth-tokens.json\n  - aid: qlik:well-known\n    name: Qlik OAuth Well-Known Configuration API\n    description: >-\n      Returns OAuth 2.0 metadata related to the tenant, including authorization\n      endpoint, token endpoint, and supported grant types.\n    humanURL: https://qlik.dev/apis/rest/.well-known/\n    tags:\n\
  \      - Configuration\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/.well-known/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/.well-known.json\n  - aid: qlik:quotas\n    name: Qlik Quotas API\n    description: >-\n      Returns entitled attributes based on the license, providing information\n      about resource limits and usage quotas.\n    humanURL: https://qlik.dev/apis/rest/quotas/\n    tags:\n      - Licensing\n      - Quotas\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/quotas/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/quotas.json\n  - aid: qlik:reload-tasks\n    name: Qlik Reload Tasks API\n    description: >-\n      Manages scheduled reload tasks for analytics applications, enabling\n      automated data refresh on defined schedules.\n    humanURL: https://qlik.dev/apis/rest/reload-tasks/\n    tags:\n      - Reloads\n      - Scheduling\n \
  \   properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/reload-tasks/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/reload-tasks.json\n  - aid: qlik:reloads\n    name: Qlik Reloads API\n    description: >-\n      Triggers and manages app data reloads to refresh analytics application data\n      via REST API instead of only through the JSON-RPC WebSocket API.\n    humanURL: https://qlik.dev/apis/rest/reloads/\n    tags:\n      - Data Refresh\n      - Reloads\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/reloads/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/reloads.json\n  - aid: qlik:report-templates\n    name: Qlik Report Templates API\n    description: >-\n      Manages report templates that define the structure and formatting of\n      generated reports from Qlik analytics data.\n    humanURL: https://qlik.dev/apis/rest/report-templates/\n    tags:\n      - Reports\n      - Templates\n\
  \    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/report-templates/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/report-templates.json\n  - aid: qlik:reports\n    name: Qlik Reports API\n    description: >-\n      Generates downloadable report assets from data in analytics applications,\n      supporting multiple output formats including Excel, PDF, PowerPoint, HTML,\n      and images.\n    humanURL: https://qlik.dev/apis/rest/reports/\n    tags:\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/reports/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/reports.json\n  - aid: qlik:roles\n    name: Qlik Roles API\n    description: >-\n      Manages tenant roles that are assigned to users or groups to control\n      permissions and access within Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/roles/\n    tags:\n      - Access Control\n      - Roles\n    properties:\n\
  \      - type: Documentation\n        url: https://qlik.dev/apis/rest/roles/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/roles.json\n  - aid: qlik:sharing-tasks\n    name: Qlik Sharing Tasks API\n    description: >-\n      Manages sharing tasks for distributing analytics content and reports to\n      recipients within Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/sharing-tasks/\n    tags:\n      - Distribution\n      - Sharing\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/sharing-tasks/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/sharing-tasks.json\n  - aid: qlik:tasks\n    name: Qlik Tasks API\n    description: >-\n      Manages general task scheduling and execution within Qlik Cloud for\n      orchestrating platform operations.\n    humanURL: https://qlik.dev/apis/rest/tasks/\n    tags:\n      - Scheduling\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/tasks/\n\
  \      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/tasks.json\n  - aid: qlik:temp-contents\n    name: Qlik Temporary Contents API\n    description: >-\n      Manages temporary content storage for file uploads and transient data within\n      Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/temp-contents/\n    tags:\n      - Temporary Storage\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/temp-contents/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/temp-contents.json\n  - aid: qlik:tenants\n    name: Qlik Tenants API\n    description: >-\n      Manages Qlik Cloud tenant configurations, settings, and metadata.\n    humanURL: https://qlik.dev/apis/rest/tenants/\n    tags:\n      - Tenants\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/tenants/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/tenants.json\n  - aid: qlik:tenant-settings\n    name: Qlik Tenant\
  \ Settings API\n    description: >-\n      Manages tenant-level configuration settings for customizing the behavior of\n      the Qlik Cloud platform.\n    humanURL: https://qlik.dev/apis/rest/tenant-settings/\n    tags:\n      - Settings\n      - Tenants\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/tenant-settings/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/tenant-settings.json\n  - aid: qlik:themes\n    name: Qlik Themes API\n    description: >-\n      Manages themes for customizing the styling and appearance of the Qlik Sense\n      client experience, including uploading, downloading, and managing theme\n      archives.\n    humanURL: https://qlik.dev/apis/rest/themes/\n    tags:\n      - Customization\n      - Themes\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/themes/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/themes.json\n  - aid: qlik:transports\n    name:\
  \ Qlik Email Configuration API\n    description: >-\n      Manages email transport configuration for sending notifications and reports\n      from Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/transports/\n    tags:\n      - Configuration\n      - Email\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/transports/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/transports.json\n  - aid: qlik:ui-config\n    name: Qlik Pinned Links API\n    description: >-\n      Manages administrator-defined pinned links displayed in the Qlik Cloud\n      interface for quick access to resources.\n    humanURL: https://qlik.dev/apis/rest/ui-config/\n    tags:\n      - Links\n      - UI Configuration\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/ui-config/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/ui-config.json\n  - aid: qlik:web-integrations\n    name: Qlik Web Integrations API\n\
  \    description: >-\n      Manages web integration configurations that allow external websites to embed\n      and interact with Qlik Cloud content.\n    humanURL: https://qlik.dev/apis/rest/web-integrations/\n    tags:\n      - Embedding\n      - Web Integrations\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/web-integrations/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/web-integrations.json\n  - aid: qlik:web-notifications\n    name: Qlik Web Notifications API\n    description: >-\n      Manages web-based push notifications for real-time updates within the Qlik\n      Cloud user interface.\n    humanURL: https://qlik.dev/apis/rest/web-notifications/\n    tags:\n      - Notifications\n      - Web\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/web-notifications/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/web-notifications.json\n  - aid: qlik:webhooks\n    name: Qlik\
  \ Webhooks API\n    description: >-\n      Manages webhooks for providing real-time event information from Qlik Cloud to\n      external applications, with delivery history tracking.\n    humanURL: https://qlik.dev/apis/rest/webhooks/\n    tags:\n      - Events\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/webhooks/\n      - type: OpenAPI\n        url: https://qlik.dev/specs/rest/webhooks.json\n  - aid: qlik:ip-policies\n    name: Qlik IP Policies API\n    description: >-\n      Manages IP restriction policies for controlling network access to the Qlik\n      Cloud tenant.\n    humanURL: https://qlik.dev/apis/rest/core/ip-policies/\n    tags:\n      - IP Policies\n      - Security\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/core/ip-policies/\n  - aid: qlik:change-stores\n    name: Qlik Change Stores API\n    description: >-\n      Manages change store configurations for tracking and storing\
  \ changes in\n      analytics data.\n    humanURL: https://qlik.dev/apis/rest/analytics/change-stores/\n    tags:\n      - Analytics\n      - Change Tracking\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/analytics/change-stores/\n  - aid: qlik:data-products\n    name: Qlik Data Products API\n    description: >-\n      Manages data products within the Qlik data governance framework, enabling\n      the packaging and sharing of curated data assets.\n    humanURL: https://qlik.dev/apis/rest/data-governance/data-products/\n    tags\n\n# --- truncated at 32 KB (33 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/qlik/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/qlik/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/qlik/refs/heads/main/apis.yml
use_cases: []
---
