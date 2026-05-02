---
api_count: 10
api_specs:
- filename: openapi
  format: yaml
  label: Mixpanel Ingestion API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.mixpanel.com/reference/openapi
- filename: openapi
  format: yaml
  label: Mixpanel Query API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.mixpanel.com/reference/openapi
- filename: openapi
  format: yaml
  label: Mixpanel Data Pipelines API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.mixpanel.com/reference/openapi
- filename: mixpanel-identity-openapi.yml
  format: yaml
  label: Mixpanel Identity API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-identity-openapi.yml
- filename: mixpanel-event-export-openapi.yml
  format: yaml
  label: Mixpanel Event Export API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-event-export-openapi.yml
- filename: mixpanel-lexicon-schemas-openapi.yml
  format: yaml
  label: Mixpanel Lexicon Schemas API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-lexicon-schemas-openapi.yml
- filename: mixpanel-service-accounts-openapi.yml
  format: yaml
  label: Mixpanel Service Accounts API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-service-accounts-openapi.yml
- filename: mixpanel-annotations-openapi.yml
  format: yaml
  label: Mixpanel Annotations API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-annotations-openapi.yml
- filename: mixpanel-gdpr-ccpa-openapi.yml
  format: yaml
  label: Mixpanel GDPR and CCPA API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-gdpr-ccpa-openapi.yml
- filename: mixpanel-warehouse-connectors-openapi.yml
  format: yaml
  label: Mixpanel Warehouse Connectors API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-warehouse-connectors-openapi.yml
apis:
- description: API for sending event data to Mixpanel for tracking and analysis, including importing events, tracking events, managing user profiles, group profiles, and lookup tables.
  name: Mixpanel Ingestion API
  slug: ''
- description: API for querying and retrieving analytics data from Mixpanel, including cohorts, funnels, insights, retention, segmentation, activity feeds, and event breakdowns.
  name: Mixpanel Query API
  slug: ''
- description: API for creating, managing, and monitoring data export pipelines in Mixpanel, including creating, editing, pausing, resuming, and deleting pipelines.
  name: Mixpanel Data Pipelines API
  slug: ''
- description: API for managing user identity in Mixpanel, including creating identities, creating aliases, and merging identities to accurately resolve users across multiple devices.
  name: Mixpanel Identity API
  slug: ''
- description: API for downloading raw event data as it is received and stored within Mixpanel, complete with all event properties including distinct_id and exact timestamps.
  name: Mixpanel Event Export API
  slug: ''
- description: 'API for syncing your internal data dictionary or tracking plan with Mixpanel using schemas, allowing you to create, replace, retrieve, and delete schema definitions that describe the data you send to '
  name: Mixpanel Lexicon Schemas API
  slug: ''
- description: API for programmatically managing service accounts within your organization, including creating, deleting, listing service accounts, and managing their project memberships.
  name: Mixpanel Service Accounts API
  slug: ''
- description: API for creating, retrieving, updating, and deleting annotations that label specific points in time on Mixpanel charts with descriptions, useful for marking product launches, campaigns, or data anomal
  name: Mixpanel Annotations API
  slug: ''
- description: API for submitting data retrieval and deletion requests to help meet GDPR and CCPA compliance requirements, including creating and checking the status of retrieval and deletion tasks.
  name: Mixpanel GDPR and CCPA API
  slug: ''
- description: API for connecting a data warehouse to import events, users, groups, and lookup tables into Mixpanel, and for manually triggering specific warehouse import runs.
  name: Mixpanel Warehouse Connectors API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developer.mixpanel.com/
- title: ''
  type: Getting Started
  url: https://developer.mixpanel.com/docs/getting-started
- title: ''
  type: Authentication
  url: https://developer.mixpanel.com/reference/authentication
- title: ''
  type: SDKs
  url: https://developer.mixpanel.com/docs/sdks
- title: ''
  type: Rate Limits
  url: https://developer.mixpanel.com/reference/rate-limits
- title: ''
  type: API Status
  url: https://www.mixpanelstatus.com/
- title: ''
  type: Change Log
  url: https://docs.mixpanel.com/changelogs
- title: ''
  type: GitHub Organization
  url: https://github.com/mixpanel
- title: ''
  type: Security
  url: https://mixpanel.com/legal/security-overview/
- title: ''
  type: Login
  url: https://mixpanel.com/login/
- title: ''
  type: Sign Up
  url: https://mixpanel.com/register/
- title: ''
  type: Terms of Service
  url: https://mixpanel.com/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://mixpanel.com/legal/privacy-policy
- title: ''
  type: Pricing
  url: https://mixpanel.com/pricing
- title: ''
  type: Blog
  url: https://mixpanel.com/blog
- title: ''
  type: Support
  url: https://mixpanel.com/get-support
- title: ''
  type: JSON-LD
  url: json-ld/mixpanel-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/mixpanel-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/mixpanel-user-profile-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/mixpanel-funnel-schema.json
created: '2024'
description: Mixpanel is a business analytics service company that tracks user interactions with web and mobile applications and provides tools for targeted communication with them.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Mixpanel Context
  property_count: 10
  slug: mixpanel-context
layout: provider
modified: '2026-03-16'
name: Mixpanel
skills: []
slug: mixpanel
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: mixpanel\nname: Mixpanel\ndescription: Mixpanel is a business analytics service company that tracks user interactions with web and mobile applications and provides tools for targeted communication with them.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://mixpanel.com\ncreated: '2024'\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\napis:\n  - name: Mixpanel Ingestion API\n    description: API for sending event data to Mixpanel for tracking and analysis, including importing events, tracking events, managing user profiles, group profiles, and lookup tables.\n    image: https://mixpanel.com/wp-content/uploads/2021/07/mixpanel-logo.svg\n    humanURL: https://developer.mixpanel.com/reference/ingestion-api\n    baseURL: https://api.mixpanel.com\n    tags:\n      - Analytics\n      - Events\n      - Group Profiles\n      - Ingestion\n      - Tracking\n      - User Profiles\n    properties:\n      - type: Documentation\n\
  \        url: https://developer.mixpanel.com/reference/ingestion-api\n      - type: OpenAPI\n        url: https://developer.mixpanel.com/reference/openapi\n      - type: OpenAPI\n        url: openapi/mixpanel-ingestion-openapi.yml\n    contact:\n      - FN: Mixpanel Support\n        email: support@mixpanel.com\n        url: https://mixpanel.com/get-support\n  - name: Mixpanel Query API\n    description: API for querying and retrieving analytics data from Mixpanel, including cohorts, funnels, insights, retention, segmentation, activity feeds, and event breakdowns.\n    image: https://mixpanel.com/wp-content/uploads/2021/07/mixpanel-logo.svg\n    humanURL: https://developer.mixpanel.com/reference/query-api\n    baseURL: https://mixpanel.com/api\n    tags:\n      - Analytics\n      - Cohorts\n      - Data Export\n      - Funnels\n      - Query\n      - Retention\n      - Segmentation\n    properties:\n      - type: Documentation\n        url: https://developer.mixpanel.com/reference/query-api\n\
  \      - type: OpenAPI\n        url: https://developer.mixpanel.com/reference/openapi\n      - type: OpenAPI\n        url: openapi/mixpanel-query-openapi.yml\n    contact:\n      - FN: Mixpanel Support\n        email: support@mixpanel.com\n        url: https://mixpanel.com/get-support\n  - name: Mixpanel Data Pipelines API\n    description: API for creating, managing, and monitoring data export pipelines in Mixpanel, including creating, editing, pausing, resuming, and deleting pipelines.\n    image: https://mixpanel.com/wp-content/uploads/2021/07/mixpanel-logo.svg\n    humanURL: https://developer.mixpanel.com/reference/overview-2\n    baseURL: https://data.mixpanel.com\n    tags:\n      - Data Pipeline\n      - Export\n      - Import\n    properties:\n      - type: Documentation\n        url: https://developer.mixpanel.com/reference/raw-data-export-api\n      - type: OpenAPI\n        url: https://developer.mixpanel.com/reference/openapi\n      - type: OpenAPI\n        url: openapi/mixpanel-data-pipelines-openapi.yml\n\
  \    contact:\n      - FN: Mixpanel Support\n        email: support@mixpanel.com\n        url: https://mixpanel.com/get-support\n  - name: Mixpanel Identity API\n    description: API for managing user identity in Mixpanel, including creating identities, creating aliases, and merging identities to accurately resolve users across multiple devices.\n    image: https://mixpanel.com/wp-content/uploads/2021/07/mixpanel-logo.svg\n    humanURL: https://developer.mixpanel.com/reference/create-identity\n    baseURL: https://api.mixpanel.com\n    tags:\n      - ID Merge\n      - Identity\n      - User Management\n    properties:\n      - type: Documentation\n        url: https://developer.mixpanel.com/reference/create-identity\n      - type: OpenAPI\n        url: openapi/mixpanel-identity-openapi.yml\n    contact:\n      - FN: Mixpanel Support\n        email: support@mixpanel.com\n        url: https://mixpanel.com/get-support\n  - name: Mixpanel Event Export API\n    description: API for downloading\
  \ raw event data as it is received and stored within Mixpanel, complete with all event properties including distinct_id and exact timestamps.\n    image: https://mixpanel.com/wp-content/uploads/2021/07/mixpanel-logo.svg\n    humanURL: https://developer.mixpanel.com/reference/raw-event-export\n    baseURL: https://data.mixpanel.com/api/2.0\n    tags:\n      - Data Export\n      - Events\n      - Raw Data\n    properties:\n      - type: Documentation\n        url: https://developer.mixpanel.com/reference/raw-event-export\n      - type: OpenAPI\n        url: openapi/mixpanel-event-export-openapi.yml\n    contact:\n      - FN: Mixpanel Support\n        email: support@mixpanel.com\n        url: https://mixpanel.com/get-support\n  - name: Mixpanel Lexicon Schemas API\n    description: API for syncing your internal data dictionary or tracking plan with Mixpanel using schemas, allowing you to create, replace, retrieve, and delete schema definitions that describe the data you send to Mixpanel.\n\
  \    image: https://mixpanel.com/wp-content/uploads/2021/07/mixpanel-logo.svg\n    humanURL: https://developer.mixpanel.com/reference/lexicon-schemas-api\n    baseURL: https://mixpanel.com/api/app\n    tags:\n      - Data Dictionary\n      - Data Governance\n      - Lexicon\n      - Schemas\n    properties:\n      - type: Documentation\n        url: https://developer.mixpanel.com/reference/lexicon-schemas-api\n      - type: OpenAPI\n        url: openapi/mixpanel-lexicon-schemas-openapi.yml\n    contact:\n      - FN: Mixpanel Support\n        email: support@mixpanel.com\n        url: https://mixpanel.com/get-support\n  - name: Mixpanel Service Accounts API\n    description: API for programmatically managing service accounts within your organization, including creating, deleting, listing service accounts, and managing their project memberships.\n    image: https://mixpanel.com/wp-content/uploads/2021/07/mixpanel-logo.svg\n    humanURL: https://developer.mixpanel.com/reference/service-accounts-api\n\
  \    baseURL: https://mixpanel.com/api/app\n    tags:\n      - Administration\n      - Authentication\n      - Service Accounts\n    properties:\n      - type: Documentation\n        url: https://developer.mixpanel.com/reference/service-accounts-api\n      - type: OpenAPI\n        url: openapi/mixpanel-service-accounts-openapi.yml\n    contact:\n      - FN: Mixpanel Support\n        email: support@mixpanel.com\n        url: https://mixpanel.com/get-support\n  - name: Mixpanel Annotations API\n    description: API for creating, retrieving, updating, and deleting annotations that label specific points in time on Mixpanel charts with descriptions, useful for marking product launches, campaigns, or data anomalies.\n    image: https://mixpanel.com/wp-content/uploads/2021/07/mixpanel-logo.svg\n    humanURL: https://developer.mixpanel.com/reference/create-annotation\n    baseURL: https://mixpanel.com/api/app\n    tags:\n      - Annotations\n      - Charts\n      - Reports\n    properties:\n \
  \     - type: Documentation\n        url: https://developer.mixpanel.com/reference/create-annotation\n      - type: OpenAPI\n        url: openapi/mixpanel-annotations-openapi.yml\n    contact:\n      - FN: Mixpanel Support\n        email: support@mixpanel.com\n        url: https://mixpanel.com/get-support\n  - name: Mixpanel GDPR and CCPA API\n    description: API for submitting data retrieval and deletion requests to help meet GDPR and CCPA compliance requirements, including creating and checking the status of retrieval and deletion tasks.\n    image: https://mixpanel.com/wp-content/uploads/2021/07/mixpanel-logo.svg\n    humanURL: https://developer.mixpanel.com/reference/gdpr-api\n    baseURL: https://mixpanel.com/api/app\n    tags:\n      - CCPA\n      - Compliance\n      - Data Deletion\n      - Data Retrieval\n      - GDPR\n      - Privacy\n    properties:\n      - type: Documentation\n        url: https://developer.mixpanel.com/reference/gdpr-api\n      - type: OpenAPI\n        url:\
  \ openapi/mixpanel-gdpr-ccpa-openapi.yml\n    contact:\n      - FN: Mixpanel Support\n        email: support@mixpanel.com\n        url: https://mixpanel.com/get-support\n  - name: Mixpanel Warehouse Connectors API\n    description: API for connecting a data warehouse to import events, users, groups, and lookup tables into Mixpanel, and for manually triggering specific warehouse import runs.\n    image: https://mixpanel.com/wp-content/uploads/2021/07/mixpanel-logo.svg\n    humanURL: https://developer.mixpanel.com/reference/warehouse-connectors-api\n    baseURL: https://mixpanel.com/api/app\n    tags:\n      - Connectors\n      - Data Import\n      - Integrations\n      - Warehouse\n    properties:\n      - type: Documentation\n        url: https://developer.mixpanel.com/reference/warehouse-connectors-api\n      - type: OpenAPI\n        url: openapi/mixpanel-warehouse-connectors-openapi.yml\n    contact:\n      - FN: Mixpanel Support\n        email: support@mixpanel.com\n        url: https://mixpanel.com/get-support\n\
  common:\n  - type: Portal\n    url: https://developer.mixpanel.com/\n  - type: Getting Started\n    url: https://developer.mixpanel.com/docs/getting-started\n  - type: Authentication\n    url: https://developer.mixpanel.com/reference/authentication\n  - type: SDKs\n    url: https://developer.mixpanel.com/docs/sdks\n  - type: Rate Limits\n    url: https://developer.mixpanel.com/reference/rate-limits\n  - type: API Status\n    url: https://www.mixpanelstatus.com/\n  - type: Change Log\n    url: https://docs.mixpanel.com/changelogs\n  - type: GitHub Organization\n    url: https://github.com/mixpanel\n  - type: Integrations\n    url: https://mixpanel.com/partners/integrations\n  - type: Security\n    url: https://mixpanel.com/legal/security-overview/\n  - type: Login\n    url: https://mixpanel.com/login/\n  - type: Sign Up\n    url: https://mixpanel.com/register/\n  - type: Terms of Service\n    url: https://mixpanel.com/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://mixpanel.com/legal/privacy-policy\n\
  \  - type: Pricing\n    url: https://mixpanel.com/pricing\n  - type: Blog\n    url: https://mixpanel.com/blog\n  - type: Support\n    url: https://mixpanel.com/get-support\n  - type: JSON-LD\n    url: json-ld/mixpanel-context.jsonld\n  - type: JSONSchema\n    url: json-schema/mixpanel-event-schema.json\n  - type: JSONSchema\n    url: json-schema/mixpanel-user-profile-schema.json\n  - type: JSONSchema\n    url: json-schema/mixpanel-funnel-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Analytics\n  - Data Analysis\n  - Event Tracking\n  - Product Analytics\n  - User Behavior\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/apis.yml
tags:
- Analytics
- Data Analysis
- Event Tracking
- Product Analytics
- User Behavior
url: https://mixpanel.com
use_cases: []
---
