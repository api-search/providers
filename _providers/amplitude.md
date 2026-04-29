---
api_count: 19
api_specs:
- filename: amplitude-http-v2-api-openapi.yml
  format: yaml
  label: Amplitude HTTP V2 API
  slug: http-v2-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-http-v2-api-openapi.yml
- filename: amplitude-identify-api-openapi.yml
  format: yaml
  label: Amplitude Identify API
  slug: identify-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-identify-api-openapi.yml
- filename: amplitude-dashboard-rest-api-openapi.yml
  format: yaml
  label: Amplitude Dashboard REST API
  slug: dashboard-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-dashboard-rest-api-openapi.yml
- filename: amplitude-export-api-openapi.yml
  format: yaml
  label: Amplitude Export API
  slug: export-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-export-api-openapi.yml
- filename: amplitude-behavioral-cohorts-api-openapi.yml
  format: yaml
  label: Amplitude Behavioral Cohorts API
  slug: behavioral-cohorts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-behavioral-cohorts-api-openapi.yml
- filename: amplitude-taxonomy-api-openapi.yml
  format: yaml
  label: Amplitude Taxonomy API
  slug: taxonomy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-taxonomy-api-openapi.yml
- filename: amplitude-attribution-api-openapi.yml
  format: yaml
  label: Amplitude Attribution API
  slug: attribution-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-attribution-api-openapi.yml
- filename: amplitude-chart-annotations-api-openapi.yml
  format: yaml
  label: Amplitude Chart Annotations API
  slug: chart-annotations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-chart-annotations-api-openapi.yml
- filename: amplitude-user-profile-api-openapi.yml
  format: yaml
  label: Amplitude User Profile API
  slug: user-profile-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-user-profile-api-openapi.yml
- filename: amplitude-user-mapping-api-openapi.yml
  format: yaml
  label: Amplitude User Mapping API
  slug: user-mapping-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-user-mapping-api-openapi.yml
- filename: amplitude-scim-api-openapi.yml
  format: yaml
  label: Amplitude SCIM API
  slug: scim-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-scim-api-openapi.yml
- filename: amplitude-dsar-api-openapi.yml
  format: yaml
  label: Amplitude Data Subject Access Request API
  slug: dsar-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-dsar-api-openapi.yml
- filename: amplitude-experiment-evaluation-api-openapi.yml
  format: yaml
  label: Amplitude Experiment Evaluation API
  slug: experiment-evaluation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-experiment-evaluation-api-openapi.yml
- filename: amplitude-experiment-management-api-openapi.yml
  format: yaml
  label: Amplitude Experiment Management API
  slug: experiment-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-experiment-management-api-openapi.yml
apis:
- description: The Amplitude HTTP V2 API enables developers to send event data directly from servers or clients to Amplitude's analytics platform. It supports uploading individual or batched events along with user p
  name: Amplitude HTTP V2 API
  slug: http-v2-api
- description: The Amplitude Batch Event Upload API is optimized for high-volume server-side event ingestion. It accepts batches of events up to 20MB per request and is designed for use cases where data volume may e
  name: Amplitude Batch Event Upload API
  slug: batch-event-upload-api
- description: The Amplitude Identify API allows developers to update user properties for a specific user without needing to send an accompanying event. This is useful for setting or modifying user attributes such a
  name: Amplitude Identify API
  slug: identify-api
- description: The Amplitude Group Identify API allows developers to set or update properties on groups within Amplitude. Groups are entities such as companies, teams, or accounts that users belong to. This API enab
  name: Amplitude Group Identify API
  slug: group-identify-api
- description: 'The Amplitude Dashboard REST API provides programmatic access to the same data displayed in Amplitude''s dashboard charts and graphs. It returns results in JSON format and supports queries filtered by '
  name: Amplitude Dashboard REST API
  slug: dashboard-rest-api
- description: The Amplitude Export API enables bulk export of raw event data for a given project within a specified date range. Results are returned as zipped archives of JSON files containing complete event record
  name: Amplitude Export API
  slug: export-api
- description: The Amplitude Behavioral Cohorts API allows developers to list, export, and upload cohorts in Amplitude. Cohorts are groups of users defined by shared behavioral patterns or properties. This API suppo
  name: Amplitude Behavioral Cohorts API
  slug: behavioral-cohorts-api
- description: 'The Amplitude Taxonomy API provides programmatic management of your analytics tracking plan. It supports creating, reading, updating, and deleting event categories, event types, event properties, and '
  name: Amplitude Taxonomy API
  slug: taxonomy-api
- description: The Amplitude Attribution API allows developers to send attribution campaign events to Amplitude from ad networks, attribution providers, or custom marketing tools. It associates users with the campai
  name: Amplitude Attribution API
  slug: attribution-api
- description: The Amplitude Chart Annotations API enables developers to programmatically create, retrieve, update, and delete annotations on Amplitude charts. Annotations mark significant events such as product rel
  name: Amplitude Chart Annotations API
  slug: chart-annotations-api
- description: The Amplitude Releases API allows developers to programmatically track software releases and deployments in Amplitude. By recording release events, teams can correlate product changes with analytics m
  name: Amplitude Releases API
  slug: releases-api
- description: 'The Amplitude Session Replay API enables developers to upload and manage session replay data for playback within Amplitude. Session replays provide qualitative insights by recording user interactions '
  name: Amplitude Session Replay API
  slug: session-replay-api
- description: The Amplitude User Profile API serves user profiles that include user properties, computed user properties, a list of cohort IDs the user belongs to, and personalized recommendations. It enables real-
  name: Amplitude User Profile API
  slug: user-profile-api
- description: 'The Amplitude User Mapping (Aliasing) API allows developers to merge users with different user IDs together in Amplitude. This is useful when a user initially interacts with a product anonymously and '
  name: Amplitude User Mapping API
  slug: user-mapping-api
- description: The Amplitude User Privacy API provides endpoints for managing user data in compliance with privacy regulations such as GDPR and CCPA. It supports requesting the deletion or suppression of user data b
  name: Amplitude User Privacy API
  slug: user-privacy-api
- description: The Amplitude SCIM API implements the System for Cross-domain Identity Management (SCIM) 2.0 standard for automated user provisioning and deprovisioning. It allows identity providers such as Okta, Azu
  name: Amplitude SCIM API
  slug: scim-api
- description: The Amplitude Data Subject Access Request (DSAR) API enables organizations to programmatically handle privacy requests in compliance with GDPR, CCPA, and other data protection regulations. It supports
  name: Amplitude Data Subject Access Request API
  slug: dsar-api
- description: The Amplitude Experiment Evaluation API retrieves variant assignment data for users through remote evaluation. When called, it evaluates targeting rules and returns the assigned variant for each activ
  name: Amplitude Experiment Evaluation API
  slug: experiment-evaluation-api
- description: The Amplitude Experiment Management API provides programmatic control over feature flags and experiments. It supports creating, updating, activating, and archiving experiments and flags, as well as ma
  name: Amplitude Experiment Management API
  slug: experiment-management-api
capabilities:
- description: Unified workflow for sending events and identifying users. For data engineers.
  name: Amplitude Analytics Ingestion
  slug: amplitude-analytics-ingestion
- description: Export raw event data and manage behavioral cohorts. For data analysts.
  name: Amplitude Data Export and Cohorts
  slug: amplitude-data-export-and-cohorts
- description: Manage and evaluate A/B experiments and feature flags. For product managers.
  name: Amplitude Experimentation
  slug: amplitude-experimentation
- description: Manage event schemas and chart annotations. For data governance teams.
  name: Amplitude Governance and Taxonomy
  slug: amplitude-governance-and-taxonomy
- description: SCIM provisioning and privacy compliance. For IT admins and compliance teams.
  name: Amplitude Identity and Privacy
  slug: amplitude-identity-and-privacy
common:
- title: ''
  type: Portal
  url: https://amplitude.com
- title: ''
  type: Documentation
  url: https://amplitude.com/docs
- title: ''
  type: GettingStarted
  url: https://amplitude.com/docs/get-started
- title: ''
  type: Authentication
  url: https://amplitude.com/docs/apis/authentication
- title: ''
  type: SDK
  url: https://amplitude.com/docs/sdks
- title: ''
  type: GitHubOrganization
  url: https://github.com/amplitude
- title: ''
  type: Blog
  url: https://amplitude.com/blog
- title: ''
  type: Academy
  url: https://academy.amplitude.com
- title: ''
  type: Support
  url: https://help.amplitude.com
- title: ''
  type: Pricing
  url: https://amplitude.com/pricing
- title: ''
  type: StatusPage
  url: https://status.amplitude.com
- title: ''
  type: TermsOfService
  url: https://amplitude.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://amplitude.com/privacy
- title: ''
  type: JSONLD
  url: json-ld/amplitude-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/amplitude-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/amplitude-cohort-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/amplitude-experiment-schema.json
- title: ''
  type: SpectralRules
  url: rules/amplitude-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amplitude-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amplitude-analytics-ingestion.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amplitude-data-export-and-cohorts.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amplitude-experimentation.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amplitude-governance-and-taxonomy.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amplitude-identity-and-privacy.yaml
- title: ''
  type: JSONStructure
  url: json-structure/behavioral-cohorts-api-cohort-request-response-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/dashboard-rest-api-user-search-result-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/scim-api-scim-group-request-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/http-v2-api-event-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/experiment-evaluation-api-flag-configuration-structure.json
created: ''
description: Amplitude is a digital analytics platform that helps product teams understand user behavior, run experiments, and drive growth. It provides a suite of APIs for event ingestion, user management, cohort syncing, taxonomy governance, A/B testing, and data export. Amplitude is widely used by product, data, and engineering teams to build better digital experiences through data-driven insights.
features:
- description: High-throughput server-side and client-side event ingestion via HTTP V2 and Batch APIs.
  name: Event Ingestion
- description: Track user properties, behaviors, and cohorts for deep segmentation and reporting.
  name: User Analytics
- description: Run feature flag experiments and measure variant impact on key metrics.
  name: A/B Experimentation
- description: Define and sync audience segments based on user behavioral patterns.
  name: Behavioral Cohorts
- description: Programmatically manage event schemas, properties, and data governance rules.
  name: Taxonomy Management
- description: Export raw event data in bulk for warehousing and offline analysis.
  name: Data Export
- description: Capture and replay user sessions for qualitative UX research.
  name: Session Replay
- description: SCIM-based provisioning, user aliasing, and identity merging across systems.
  name: Identity Management
- description: GDPR and CCPA compliant data deletion and suppression APIs.
  name: Privacy Compliance
- description: Associate users with acquisition campaigns from ad networks and marketing tools.
  name: Attribution Tracking
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Route events from Segment's customer data platform to Amplitude.
  name: Segment
- description: Export raw event data directly into Snowflake for warehouse-native analytics.
  name: Snowflake
- description: Sync Amplitude data with Google BigQuery for custom SQL analysis.
  name: BigQuery
- description: Enrich Salesforce CRM records with Amplitude behavioral cohort data.
  name: Salesforce
- description: Sync audience cohorts from Amplitude to HubSpot for marketing automation.
  name: HubSpot
- description: Power personalized messaging campaigns using Amplitude behavioral cohorts.
  name: Braze
- description: Automate user provisioning in Amplitude via Okta using the SCIM API.
  name: Okta
- description: Receive automated alerts and chart embeds from Amplitude in Slack channels.
  name: Slack
jsonld:
- class_count: 3
  name: Amplitude Amplitude Cohort Context
  property_count: 7
  slug: amplitude-amplitude-cohort-context
- class_count: 1
  name: Amplitude Amplitude Event Context
  property_count: 36
  slug: amplitude-amplitude-event-context
- class_count: 3
  name: Amplitude Amplitude Experiment Context
  property_count: 15
  slug: amplitude-amplitude-experiment-context
- class_count: 3
  name: Amplitude Attribution Api Context
  property_count: 25
  slug: amplitude-attribution-api-context
- class_count: 8
  name: Amplitude Behavioral Cohorts Api Context
  property_count: 12
  slug: amplitude-behavioral-cohorts-api-context
- class_count: 6
  name: Amplitude Chart Annotations Api Context
  property_count: 8
  slug: amplitude-chart-annotations-api-context
- class_count: 0
  name: Amplitude Context
  property_count: 7
  slug: amplitude-context
- class_count: 7
  name: Amplitude Dashboard Rest Api Context
  property_count: 10
  slug: amplitude-dashboard-rest-api-context
- class_count: 6
  name: Amplitude Dsar Api Context
  property_count: 8
  slug: amplitude-dsar-api-context
- class_count: 4
  name: Amplitude Experiment Evaluation Api Context
  property_count: 19
  slug: amplitude-experiment-evaluation-api-context
- class_count: 16
  name: Amplitude Experiment Management Api Context
  property_count: 32
  slug: amplitude-experiment-management-api-context
- class_count: 4
  name: Amplitude Http V2 Api Context
  property_count: 44
  slug: amplitude-http-v2-api-context
- class_count: 5
  name: Amplitude Identify Api Context
  property_count: 15
  slug: amplitude-identify-api-context
- class_count: 8
  name: Amplitude Scim Api Context
  property_count: 25
  slug: amplitude-scim-api-context
- class_count: 11
  name: Amplitude Taxonomy Api Context
  property_count: 9
  slug: amplitude-taxonomy-api-context
- class_count: 4
  name: Amplitude User Mapping Api Context
  property_count: 6
  slug: amplitude-user-mapping-api-context
- class_count: 3
  name: Amplitude User Profile Api Context
  property_count: 12
  slug: amplitude-user-profile-api-context
layout: provider
modified: '2026-04-19'
name: Amplitude
rules:
- name: Amplitude API Rules
  rule_count: 23
  severity_counts:
    error: 12
    hint: 0
    info: 2
    warn: 9
  slug: amplitude-spectral-rules
skills: []
slug: amplitude
solutions: []
source_filename: apis.yml
source_yaml: "aid: amplitude\nurl: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/apis.yml\nmodified: '2026-04-19'\nname: Amplitude\ndescription: >-\n  Amplitude is a digital analytics platform that helps product teams understand\n  user behavior, run experiments, and drive growth. It provides a suite of APIs\n  for event ingestion, user management, cohort syncing, taxonomy governance,\n  A/B testing, and data export. Amplitude is widely used by product, data, and\n  engineering teams to build better digital experiences through data-driven\n  insights.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- A/B Testing\n- Analytics\n- Experimentation\n- Feature Flags\n- Product Analytics\n- User Behavior\napis:\n- aid: amplitude:http-v2-api\n  name: Amplitude HTTP V2 API\n  tags:\n  - Analytics\n  - Events\n  - Ingestion\n  - Tracking\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL:\
  \ https://api2.amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/http-v2\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/http-v2\n    type: Documentation\n  - url: openapi/amplitude-http-v2-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Amplitude HTTP V2 API enables developers to send event data directly\n    from servers or clients to Amplitude's analytics platform. It supports\n    uploading individual or batched events along with user properties, event\n    properties, and group properties. This API is the primary method for\n    server-side event ingestion and is designed for high-throughput data\n    collection with built-in validation and error reporting.\n- aid: amplitude:batch-event-upload-api\n  name: Amplitude Batch Event Upload API\n  tags:\n  - Analytics\n  - Batch\n  - Events\n  - Ingestion\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api2.amplitude.com\n  humanURL:\
  \ https://amplitude.com/docs/apis/analytics/batch-event-upload\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/batch-event-upload\n    type: Documentation\n  description: >-\n    The Amplitude Batch Event Upload API is optimized for high-volume server-side\n    event ingestion. It accepts batches of events up to 20MB per request and is\n    designed for use cases where data volume may exceed the limits of the standard\n    HTTP V2 API. The API uses the same event structure as the HTTP V2 API and is\n    recommended for data pipelines processing millions of events.\n- aid: amplitude:identify-api\n  name: Amplitude Identify API\n  tags:\n  - Analytics\n  - Identity\n  - Properties\n  - Users\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api2.amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/identify\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/identify\n    type: Documentation\n\
  \  - url: openapi/amplitude-identify-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Amplitude Identify API allows developers to update user properties\n    for a specific user without needing to send an accompanying event. This\n    is useful for setting or modifying user attributes such as demographics,\n    subscription status, or preferences outside of the normal event tracking\n    flow. The API supports operations like set, unset, append, and prepend\n    on user properties.\n- aid: amplitude:group-identify-api\n  name: Amplitude Group Identify API\n  tags:\n  - Analytics\n  - Groups\n  - Identity\n  - Properties\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api2.amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/group-identify\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/group-identify\n    type: Documentation\n  description: >-\n    The Amplitude Group Identify API\
  \ allows developers to set or update properties\n    on groups within Amplitude. Groups are entities such as companies, teams, or\n    accounts that users belong to. This API enables B2B analytics use cases by\n    attaching account-level properties to groups for segmentation and reporting\n    purposes.\n- aid: amplitude:dashboard-rest-api\n  name: Amplitude Dashboard REST API\n  tags:\n  - Analytics\n  - Dashboards\n  - Metrics\n  - Reporting\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/dashboard-rest\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/dashboard-rest\n    type: Documentation\n  - url: openapi/amplitude-dashboard-rest-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Amplitude Dashboard REST API provides programmatic access to the\n    same data displayed in Amplitude's dashboard charts and graphs. It\n    returns\
  \ results in JSON format and supports queries filtered by event\n    types, user segments, cohorts, and date ranges. Developers can use this\n    API to build custom reporting tools, export chart data, or integrate\n    Amplitude analytics into external dashboards and business intelligence\n    systems.\n- aid: amplitude:export-api\n  name: Amplitude Export API\n  tags:\n  - Analytics\n  - Data\n  - Events\n  - Export\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/export\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/export\n    type: Documentation\n  - url: openapi/amplitude-export-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Amplitude Export API enables bulk export of raw event data for a\n    given project within a specified date range. Results are returned as\n    zipped archives of JSON files containing complete event\
  \ records with\n    timestamps, user properties, device information, and attribution data.\n    This API is commonly used for data warehousing, offline analysis, and\n    feeding event data into external processing pipelines.\n- aid: amplitude:behavioral-cohorts-api\n  name: Amplitude Behavioral Cohorts API\n  tags:\n  - Analytics\n  - Cohorts\n  - Segmentation\n  - Users\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/behavioral-cohorts\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/behavioral-cohorts\n    type: Documentation\n  - url: openapi/amplitude-behavioral-cohorts-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Amplitude Behavioral Cohorts API allows developers to list, export,\n    and upload cohorts in Amplitude. Cohorts are groups of users defined by\n    shared behavioral patterns or properties. This API supports downloading\n\
  \    cohort membership lists, creating new cohorts from external data, and\n    retrieving cohort metadata. It is commonly used for syncing audience\n    segments with marketing platforms, CRMs, and other downstream tools.\n- aid: amplitude:taxonomy-api\n  name: Amplitude Taxonomy API\n  tags:\n  - Analytics\n  - Data Governance\n  - Events\n  - Taxonomy\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/taxonomy\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/taxonomy\n    type: Documentation\n  - url: openapi/amplitude-taxonomy-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Amplitude Taxonomy API provides programmatic management of your\n    analytics tracking plan. It supports creating, reading, updating, and\n    deleting event categories, event types, event properties, and user\n    properties. This API is essential for data\
  \ governance workflows, enabling\n    teams to maintain a consistent and well-organized event taxonomy across\n    their instrumentation without needing to use the Amplitude UI directly.\n- aid: amplitude:attribution-api\n  name: Amplitude Attribution API\n  tags:\n  - Analytics\n  - Attribution\n  - Campaigns\n  - Marketing\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api2.amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/attribution\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/attribution\n    type: Documentation\n  - url: openapi/amplitude-attribution-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Amplitude Attribution API allows developers to send attribution\n    campaign events to Amplitude from ad networks, attribution providers,\n    or custom marketing tools. It associates users with the campaigns,\n    channels, and creatives that drove their acquisition or re-engagement.\n\
  \    This API is used to enrich Amplitude user profiles with marketing\n    attribution data for campaign performance analysis and ROI measurement.\n- aid: amplitude:chart-annotations-api\n  name: Amplitude Chart Annotations API\n  tags:\n  - Analytics\n  - Annotations\n  - Charts\n  - Reporting\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/chart-annotations\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/chart-annotations\n    type: Documentation\n  - url: openapi/amplitude-chart-annotations-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Amplitude Chart Annotations API enables developers to programmatically\n    create, retrieve, update, and delete annotations on Amplitude charts.\n    Annotations mark significant events such as product releases, marketing\n    campaigns, or incidents on timeline-based charts. This API allows\
  \ teams\n    to automate annotation management as part of their deployment or release\n    pipelines, ensuring that important context is always visible alongside\n    analytics data.\n- aid: amplitude:releases-api\n  name: Amplitude Releases API\n  tags:\n  - Analytics\n  - Deployments\n  - Releases\n  - Tracking\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/releases\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/releases\n    type: Documentation\n  description: >-\n    The Amplitude Releases API allows developers to programmatically track\n    software releases and deployments in Amplitude. By recording release events,\n    teams can correlate product changes with analytics metrics to understand the\n    impact of each deployment on user behavior, retention, and engagement.\n- aid: amplitude:session-replay-api\n  name: Amplitude Session Replay\
  \ API\n  tags:\n  - Analytics\n  - Replay\n  - Sessions\n  - User Experience\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/session-replay\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/session-replay\n    type: Documentation\n  description: >-\n    The Amplitude Session Replay API enables developers to upload and manage\n    session replay data for playback within Amplitude. Session replays provide\n    qualitative insights by recording user interactions and pairing them with\n    quantitative analytics data. This API is used for server-side ingestion of\n    session replay events and metadata.\n- aid: amplitude:user-profile-api\n  name: Amplitude User Profile API\n  tags:\n  - Analytics\n  - Profiles\n  - Recommendations\n  - Users\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://profile-api.amplitude.com\n\
  \  humanURL: https://amplitude.com/docs/apis/analytics/user-profile\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/user-profile\n    type: Documentation\n  - url: openapi/amplitude-user-profile-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Amplitude User Profile API serves user profiles that include user\n    properties, computed user properties, a list of cohort IDs the user\n    belongs to, and personalized recommendations. It enables real-time\n    access to enriched user data for powering personalization engines,\n    in-app experiences, and targeted content delivery. This API is\n    particularly useful for retrieving recommendation results generated\n    by Amplitude's machine learning models.\n- aid: amplitude:user-mapping-api\n  name: Amplitude User Mapping API\n  tags:\n  - Aliasing\n  - Analytics\n  - Identity\n  - Users\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api2.amplitude.com\n\
  \  humanURL: https://amplitude.com/docs/apis/analytics/user-mapping\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/user-mapping\n    type: Documentation\n  - url: openapi/amplitude-user-mapping-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Amplitude User Mapping (Aliasing) API allows developers to merge\n    users with different user IDs together in Amplitude. This is useful\n    when a user initially interacts with a product anonymously and later\n    creates an account, or when users have multiple identifiers across\n    different systems. The API maps these distinct identities into a single\n    unified user profile to ensure accurate analytics and attribution.\n- aid: amplitude:user-privacy-api\n  name: Amplitude User Privacy API\n  tags:\n  - Compliance\n  - GDPR\n  - Privacy\n  - Users\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/user-privacy\n\
  \  properties:\n  - url: https://amplitude.com/docs/apis/analytics/user-privacy\n    type: Documentation\n  description: >-\n    The Amplitude User Privacy API provides endpoints for managing user data\n    in compliance with privacy regulations such as GDPR and CCPA. It supports\n    requesting the deletion or suppression of user data by user ID or device ID,\n    enabling organizations to fulfill data subject rights requests and maintain\n    regulatory compliance.\n- aid: amplitude:scim-api\n  name: Amplitude SCIM API\n  tags:\n  - Access Management\n  - Identity\n  - Provisioning\n  - Users\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://analytics.amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/scim\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/scim\n    type: Documentation\n  - url: openapi/amplitude-scim-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Amplitude SCIM API\
  \ implements the System for Cross-domain Identity\n    Management (SCIM) 2.0 standard for automated user provisioning and\n    deprovisioning. It allows identity providers such as Okta, Azure AD,\n    and OneLogin to automatically create, update, and deactivate user\n    accounts in Amplitude. This API is essential for enterprise organizations\n    that need centralized user lifecycle management and compliance with\n    security policies.\n- aid: amplitude:dsar-api\n  name: Amplitude Data Subject Access Request API\n  tags:\n  - CCPA\n  - Compliance\n  - GDPR\n  - Privacy\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://amplitude.com\n  humanURL: https://amplitude.com/docs/apis/analytics/ccpa-dsar\n  properties:\n  - url: https://amplitude.com/docs/apis/analytics/ccpa-dsar\n    type: Documentation\n  - url: openapi/amplitude-dsar-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Amplitude Data Subject Access Request (DSAR)\
  \ API enables organizations\n    to programmatically handle privacy requests in compliance with GDPR, CCPA,\n    and other data protection regulations. It supports submitting deletion\n    requests for user data based on user IDs or device IDs. This API allows\n    companies to automate their privacy compliance workflows and ensure timely\n    processing of data subject requests at scale.\n- aid: amplitude:experiment-evaluation-api\n  name: Amplitude Experiment Evaluation API\n  tags:\n  - A/B Testing\n  - Experimentation\n  - Feature Flags\n  - Variants\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.lab.amplitude.com\n  humanURL: https://amplitude.com/docs/apis/experiment/experiment-evaluation-api\n  properties:\n  - url: https://amplitude.com/docs/apis/experiment/experiment-evaluation-api\n    type: Documentation\n  - url: openapi/amplitude-experiment-evaluation-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The\
  \ Amplitude Experiment Evaluation API retrieves variant assignment data\n    for users through remote evaluation. When called, it evaluates targeting\n    rules and returns the assigned variant for each active experiment or\n    feature flag. The API also tracks assignment events automatically in\n    Amplitude Analytics. It is used by server-side applications that need\n    to determine which experiment variant or feature flag value to serve\n    to a given user in real time.\n- aid: amplitude:experiment-management-api\n  name: Amplitude Experiment Management API\n  tags:\n  - A/B Testing\n  - Experimentation\n  - Feature Flags\n  - Management\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://experiment.amplitude.com\n  humanURL: https://amplitude.com/docs/apis/experiment/experiment-management-api\n  properties:\n  - url: https://amplitude.com/docs/apis/experiment/experiment-management-api\n    type: Documentation\n  - url: openapi/amplitude-experiment-management-api-openapi.yml\n\
  \    type: OpenAPI\n  description: >-\n    The Amplitude Experiment Management API provides programmatic control\n    over feature flags and experiments. It supports creating, updating,\n    activating, and archiving experiments and flags, as well as managing\n    deployments, variants, holdout groups, and mutual exclusion groups.\n    This API enables teams to integrate experiment lifecycle management\n    into their CI/CD pipelines, automate flag rollouts, and manage\n    experimentation workflows without using the Amplitude UI.\ncommon:\n- type: Portal\n  url: https://amplitude.com\n- type: Documentation\n  url: https://amplitude.com/docs\n- type: GettingStarted\n  url: https://amplitude.com/docs/get-started\n- type: Authentication\n  url: https://amplitude.com/docs/apis/authentication\n- type: SDK\n  url: https://amplitude.com/docs/sdks\n- type: GitHubOrganization\n  url: https://github.com/amplitude\n- type: Blog\n  url: https://amplitude.com/blog\n- type: Academy\n  url: https://academy.amplitude.com\n\
  - type: Support\n  url: https://help.amplitude.com\n- type: Pricing\n  url: https://amplitude.com/pricing\n- type: StatusPage\n  url: https://status.amplitude.com\n- type: TermsOfService\n  url: https://amplitude.com/terms\n- type: PrivacyPolicy\n  url: https://amplitude.com/privacy\n- type: JSONLD\n  url: json-ld/amplitude-context.jsonld\n- type: JSONSchema\n  url: json-schema/amplitude-event-schema.json\n- type: JSONSchema\n  url: json-schema/amplitude-cohort-schema.json\n- type: JSONSchema\n  url: json-schema/amplitude-experiment-schema.json\n- type: Features\n  data:\n  - name: Event Ingestion\n    description: High-throughput server-side and client-side event ingestion via HTTP V2 and Batch APIs.\n  - name: User Analytics\n    description: Track user properties, behaviors, and cohorts for deep segmentation and reporting.\n  - name: A/B Experimentation\n    description: Run feature flag experiments and measure variant impact on key metrics.\n  - name: Behavioral Cohorts\n    description:\
  \ Define and sync audience segments based on user behavioral patterns.\n  - name: Taxonomy Management\n    description: Programmatically manage event schemas, properties, and data governance rules.\n  - name: Data Export\n    description: Export raw event data in bulk for warehousing and offline analysis.\n  - name: Session Replay\n    description: Capture and replay user sessions for qualitative UX research.\n  - name: Identity Management\n    description: SCIM-based provisioning, user aliasing, and identity merging across systems.\n  - name: Privacy Compliance\n    description: GDPR and CCPA compliant data deletion and suppression APIs.\n  - name: Attribution Tracking\n    description: Associate users with acquisition campaigns from ad networks and marketing tools.\n- type: UseCases\n  data:\n  - name: Product Analytics\n    description: Understand how users interact with your product to prioritize features and reduce churn.\n  - name: Growth Experimentation\n    description: Run controlled\
  \ A/B tests to measure the causal impact of product changes.\n  - name: Marketing Attribution\n    description: Track campaign performance and ROI by connecting acquisition events to user behavior.\n  - name: Data Warehouse Integration\n    description: Export raw event data to Snowflake, BigQuery, or Redshift for custom analysis.\n  - name: Audience Syndication\n    description: Sync behavioral cohorts to ad platforms and CRMs for targeted marketing.\n  - name: Compliance Automation\n    description: Automate GDPR and CCPA data deletion workflows for privacy compliance.\n  - name: Enterprise Identity Management\n    description: Automate user provisioning and deprovisioning via SCIM integration with IdPs.\n- type: Integrations\n  data:\n  - name: Segment\n    description: Route events from Segment's customer data platform to Amplitude.\n  - name: Snowflake\n    description: Export raw event data directly into Snowflake for warehouse-native analytics.\n  - name: BigQuery\n    description:\
  \ Sync Amplitude data with Google BigQuery for custom SQL analysis.\n  - name: Salesforce\n    description: Enrich Salesforce CRM records with Amplitude behavioral cohort data.\n  - name: HubSpot\n    description: Sync audience cohorts from Amplitude to HubSpot for marketing automation.\n  - name: Braze\n    description: Power personalized messaging campaigns using Amplitude behavioral cohorts.\n  - name: Okta\n    description: Automate user provisioning in Amplitude via Okta using the SCIM API.\n  - name: Slack\n    description: Receive automated alerts and chart embeds from Amplitude in Slack channels.\n- type: SpectralRules\n  url: rules/amplitude-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amplitude-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amplitude-analytics-ingestion.yaml\n- type: NaftikoCapability\n  url: capabilities/amplitude-data-export-and-cohorts.yaml\n- type: NaftikoCapability\n  url: capabilities/amplitude-experimentation.yaml\n- type:\
  \ NaftikoCapability\n  url: capabilities/amplitude-governance-and-taxonomy.yaml\n- type: NaftikoCapability\n  url: capabilities/amplitude-identity-and-privacy.yaml\n- type: JSONStructure\n  url: json-structure/behavioral-cohorts-api-cohort-request-response-structure.json\n- type: JSONStructure\n  url: json-structure/dashboard-rest-api-user-search-result-structure.json\n- type: JSONStructure\n  url: json-structure/scim-api-scim-group-request-structure.json\n- type: JSONStructure\n  url: json-structure/http-v2-api-event-structure.json\n- type: JSONStructure\n  url: json-structure/experiment-evaluation-api-flag-configuration-structure.json\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/apis.yml
tags:
- A/B Testing
- Analytics
- Experimentation
- Feature Flags
- Product Analytics
- User Behavior
url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/apis.yml
use_cases:
- description: Understand how users interact with your product to prioritize features and reduce churn.
  name: Product Analytics
- description: Run controlled A/B tests to measure the causal impact of product changes.
  name: Growth Experimentation
- description: Track campaign performance and ROI by connecting acquisition events to user behavior.
  name: Marketing Attribution
- description: Export raw event data to Snowflake, BigQuery, or Redshift for custom analysis.
  name: Data Warehouse Integration
- description: Sync behavioral cohorts to ad platforms and CRMs for targeted marketing.
  name: Audience Syndication
- description: Automate GDPR and CCPA data deletion workflows for privacy compliance.
  name: Compliance Automation
- description: Automate user provisioning and deprovisioning via SCIM integration with IdPs.
  name: Enterprise Identity Management
---
