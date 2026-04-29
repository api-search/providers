---
api_count: 15
apis:
- description: Core REST API for accessing Salesforce data and metadata programmatically.
  name: Salesforce REST API
  slug: ''
- description: Enterprise-grade SOAP API for complex integrations and bulk operations.
  name: Salesforce SOAP API
  slug: ''
- description: Asynchronous API optimized for loading and querying large data sets.
  name: Salesforce Bulk API 2.0
  slug: ''
- description: API for managing customizations and building tools for application lifecycle management.
  name: Salesforce Metadata API
  slug: ''
- description: Real-time event monitoring and push notifications using Bayeux protocol.
  name: Salesforce Streaming API
  slug: ''
- description: Event-driven architecture for publishing and subscribing to custom events.
  name: Salesforce Platform Events API
  slug: ''
- description: API for accessing and manipulating Analytics dashboards and datasets.
  name: Salesforce Analytics API
  slug: ''
- description: API for building custom development tools for Salesforce applications.
  name: Salesforce Tooling API
  slug: ''
- description: REST API for integrating mobile apps, intranet sites, and third-party web applications with Salesforce, including Chatter feeds, groups, and users.
  name: Salesforce Connect REST API
  slug: ''
- description: gRPC-based API for publishing and subscribing to platform events, change data capture events, and custom channels in real time.
  name: Salesforce Pub/Sub API
  slug: ''
- description: GraphQL API for querying Salesforce data with a single endpoint, reducing round trips and improving application performance.
  name: Salesforce GraphQL API
  slug: ''
- description: API for receiving near-real-time notifications of changes to Salesforce records to synchronize corresponding records in external data stores.
  name: Salesforce Change Data Capture API
  slug: ''
- description: REST API for invoking standard and custom actions programmatically, including flow actions and process automation triggers.
  name: Salesforce Invocable Actions API
  slug: ''
- description: REST API for executing multiple API requests in a single call, with the ability to use the output of one request as input to another.
  name: Salesforce Composite API
  slug: ''
- description: Framework for exposing Apex classes and methods as RESTful web services, enabling custom API endpoints on the Salesforce platform.
  name: Salesforce Apex REST API
  slug: ''
capabilities:
- description: Unified workflow combining the Salesforce REST API and Bulk API for comprehensive data operations including CRUD, queries, search, and bulk data loading. Used by Salesforce admins and integration deve
  name: Salesforce Data Operations
  slug: data-operations
common:
- title: ''
  type: Portal
  url: https://developer.salesforce.com
- title: ''
  type: Website
  url: https://www.salesforce.com
- title: ''
  type: Developer Portal
  url: https://developer.salesforce.com
- title: ''
  type: Documentation
  url: https://developer.salesforce.com/docs
- title: ''
  type: API Library
  url: https://developer.salesforce.com/docs/apis
- title: ''
  type: Trailhead Learning
  url: https://trailhead.salesforce.com
- title: ''
  type: API Status
  url: https://status.salesforce.com
- title: ''
  type: Community
  url: https://developer.salesforce.com/forums
- title: ''
  type: Blog
  url: https://developer.salesforce.com/blogs
- title: ''
  type: Pricing
  url: https://www.salesforce.com/editions-pricing/overview/
- title: ''
  type: Terms of Service
  url: https://www.salesforce.com/company/legal/agreements/
- title: ''
  type: Privacy Policy
  url: https://www.salesforce.com/company/privacy/
- title: ''
  type: Sign Up
  url: https://developer.salesforce.com/signup
- title: ''
  type: Login
  url: https://login.salesforce.com
- title: ''
  type: GitHub
  url: https://github.com/salesforce
- title: ''
  type: GitHub Organization
  url: https://github.com/developerforce
- title: ''
  type: Stack Exchange
  url: https://salesforce.stackexchange.com
- title: ''
  type: X (Twitter)
  url: https://twitter.com/salesforcedevs
- title: ''
  type: Support
  url: https://developer.salesforce.com/support
- title: ''
  type: Contact
  url: https://www.salesforce.com/company/contact-us/
- title: ''
  type: Rate Limits
  url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm
- title: ''
  type: API Versioning
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_versions.htm
- title: ''
  type: Postman Collection
  url: https://www.postman.com/salesforce-developers/workspace/salesforce-developers/overview
- title: ''
  type: Postman GitHub
  url: https://github.com/forcedotcom/postman-salesforce-apis
- title: ''
  type: SDKs
  url: https://jsforce.github.io/
- title: ''
  type: Release Notes
  url: https://help.salesforce.com/s/articleView?id=release-notes.rn_api_nc.htm&language=en_US&release=248&type=5
- title: ''
  type: API End-of-Life Policy
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/api_rest_eol.htm
- title: ''
  type: SpectralRules
  url: rules/salesforce-automation-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/salesforce-automation-vocabulary.yaml
- title: Data Operations Workflow
  type: NaftikoCapability
  url: capabilities/data-operations.yaml
- title: ''
  type: JSONStructure
  url: json-structure/salesforce-automation-flow-structure.json
- title: Flow Example
  type: Example
  url: examples/salesforce-automation-flow-example.json
- title: ''
  type: GitHubOrganization
  url: https://github.com/salesforce
created: '2024-01-01'
description: A collection of Salesforce APIs for automating business processes, sales operations, and customer relationship management.
features:
- description: Supports multiple OAuth flows including authorization code, JWT bearer, and client credentials.
  name: OAuth 2.0 Authentication
- description: Salesforce Object Query Language for structured data queries across objects.
  name: SOQL Queries
- description: Full-text search across multiple objects using Salesforce Object Search Language.
  name: SOSL Search
- description: Asynchronous bulk API for loading, deleting, and querying millions of records.
  name: Bulk Data Operations
- description: Platform events, Change Data Capture, and streaming API for real-time notifications.
  name: Real-Time Events
- description: Declarative automation with Flow Builder for record-triggered, scheduled, and screen flows.
  name: Flow Automation
- description: Execute multiple API requests in a single call with request chaining.
  name: Composite API
- description: Single-endpoint GraphQL API for efficient data queries.
  name: GraphQL Support
- description: Programmatic invocation of standard and custom automation actions.
  name: Invocable Actions
- description: Multi-step approval workflows with programmatic submission and management.
  name: Approval Processes
image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg
integrations:
- description: Native integration platform for connecting Salesforce with enterprise systems.
  name: MuleSoft
- description: Salesforce-owned collaboration platform with deep CRM integration.
  name: Slack
- description: Analytics and visualization platform integrated with Salesforce data.
  name: Tableau
- description: Cloud application platform for extending Salesforce with custom apps.
  name: Heroku
- description: Official Postman workspace with pre-built API collections for testing.
  name: Postman
jsonld:
- class_count: 0
  name: Salesforce Automation Context
  property_count: 16
  slug: salesforce-automation-context
layout: provider
modified: '2026-04-18'
name: Salesforce Automation
rules:
- name: Salesforce Automation API Rules
  rule_count: 37
  severity_counts:
    error: 18
    hint: 0
    info: 7
    warn: 12
  slug: salesforce-automation-spectral-rules
skills: []
slug: salesforce-automation
solutions: []
source_yaml: "name: Salesforce Automation\ndescription: >-\n  A collection of Salesforce APIs for automating business processes, sales operations,\n  and customer relationship management.\nimage: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\nurl: https://developer.salesforce.com\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.16'\ntags:\n  - Automation\n  - Cloud\n  - CRM\n  - Enterprise\n  - Sales\napis:\n  - name: Salesforce REST API\n    description: >-\n      Core REST API for accessing Salesforce data and metadata programmatically.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/\n    baseURL: https://yourInstance.salesforce.com/services/data\n    tags:\n      - CRUD\n      - Data\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/\n\
  \      - type: OpenAPI\n        url: openapi/salesforce-rest-api-openapi.json\n      - type: JSONSchema\n        url: json-schema/salesforce-automation-flow-schema.json\n      - type: JSONLD\n        url: json-ld/salesforce-automation-context.jsonld\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/quickstart.htm\n      - type: API Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_list.htm\n      - type: Rate Limits\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_limits.htm\n      - type: Change Log\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/rest_rns.htm\n      - type: Postman Collection\n        url: https://www.postman.com/salesforce-developers/workspace/salesforce-developers/overview\n\
  \    contact:\n      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce SOAP API\n    description: >-\n      Enterprise-grade SOAP API for complex integrations and bulk operations.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/\n    baseURL: https://yourInstance.salesforce.com/services/Soap/c\n    tags:\n      - Enterprise\n      - Integration\n      - SOAP\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/\n      - type: WSDL\n        url: https://yourInstance.salesforce.com/services/wsdl/enterprise\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_calls_login.htm\n    contact:\n      - FN: Salesforce Developer Support\n    \
  \    email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce Bulk API 2.0\n    description: >-\n      Asynchronous API optimized for loading and querying large data sets.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/\n    baseURL: https://yourInstance.salesforce.com/services/data/v63.0/jobs\n    tags:\n      - Async\n      - Bulk\n      - ETL\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/\n      - type: OpenAPI\n        url: openapi/salesforce-bulk-api-openapi.json\n      - type: JSONLD\n        url: json-ld/salesforce-automation-context.jsonld\n      - type: Best Practices\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/asynch_api_best_practices.htm\n      - type: Getting\
  \ Started\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/asynch_api_quickstart.htm\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/authentication.htm\n    contact:\n      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce Metadata API\n    description: >-\n      API for managing customizations and building tools for application lifecycle\n      management.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/\n    baseURL: https://yourInstance.salesforce.com/services/Soap/m\n    tags:\n      - Deployment\n      - DevOps\n      - Metadata\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/\n\
  \      - type: WSDL\n        url: https://yourInstance.salesforce.com/services/wsdl/metadata\n    contact:\n      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce Streaming API\n    description: >-\n      Real-time event monitoring and push notifications using Bayeux protocol.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/\n    baseURL: https://yourInstance.salesforce.com/cometd\n    tags:\n      - Events\n      - Push\n      - Real-Time\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/\n      - type: OpenAPI\n        url: openapi/salesforce-streaming-api-openapi.json\n      - type: JSONLD\n        url: json-ld/salesforce-automation-context.jsonld\n\
  \      - type: Quick Start\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/quick_start.htm\n    contact:\n      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce Platform Events API\n    description: >-\n      Event-driven architecture for publishing and subscribing to custom events.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/\n    baseURL: https://yourInstance.salesforce.com/services/data/v63.0/sobjects\n    tags:\n      - Events\n      - Integration\n      - Pub/Sub\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/\n      - type: OpenAPI\n        url: openapi/salesforce-platform-events-api-openapi.json\n\
  \      - type: JSONLD\n        url: json-ld/salesforce-automation-context.jsonld\n      - type: Developer Guide\n        url: https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/platform_events_intro.htm\n    contact:\n      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce Analytics API\n    description: >-\n      API for accessing and manipulating Analytics dashboards and datasets.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/\n    baseURL: https://yourInstance.salesforce.com/services/data/v63.0/wave\n    tags:\n      - Analytics\n      - Dashboards\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/\n\
  \      - type: OpenAPI\n        url: openapi/salesforce-analytics-api-openapi.json\n      - type: JSONLD\n        url: json-ld/salesforce-automation-context.jsonld\n    contact:\n      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce Tooling API\n    description: >-\n      API for building custom development tools for Salesforce applications.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/\n    baseURL: https://yourInstance.salesforce.com/services/data/v63.0/tooling\n    tags:\n      - Debugging\n      - Development\n      - Tooling\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/\n      - type: OpenAPI\n        url: openapi/salesforce-tooling-api-openapi.json\n\
  \      - type: JSONSchema\n        url: json-schema/salesforce-automation-flow-schema.json\n      - type: JSONLD\n        url: json-ld/salesforce-automation-context.jsonld\n      - type: Flow Object Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/tooling_api_objects_flow.htm\n    contact:\n      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce Connect REST API\n    description: >-\n      REST API for integrating mobile apps, intranet sites, and third-party web applications\n      with Salesforce, including Chatter feeds, groups, and users.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/intro_what_is_chatter_connect.htm\n    baseURL: https://yourInstance.salesforce.com/services/data/v63.0/connect\n\
  \    tags:\n      - Chatter\n      - Collaboration\n      - Connect\n      - Social\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/intro_what_is_chatter_connect.htm\n      - type: OpenAPI\n        url: openapi/salesforce-connect-rest-api-openapi.json\n      - type: JSONLD\n        url: json-ld/salesforce-automation-context.jsonld\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/quickstart.htm\n      - type: API Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_overview.htm\n      - type: Rate Limits\n        url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/intro_rate_limits.htm\n      - type: Examples\n        url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/quickreference.htm\n    contact:\n\
  \      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce Pub/Sub API\n    description: >-\n      gRPC-based API for publishing and subscribing to platform events, change data\n      capture events, and custom channels in real time.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/platform/pub-sub-api/overview\n    baseURL: https://api.pubsub.salesforce.com:7443\n    tags:\n      - Events\n      - gRPC\n      - Pub/Sub\n      - Real-Time\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/platform/pub-sub-api/overview\n      - type: JSONLD\n        url: json-ld/salesforce-automation-context.jsonld\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/platform/pub-sub-api/guide/intro.html\n      - type:\
  \ Authentication\n        url: https://developer.salesforce.com/docs/platform/pub-sub-api/guide/supported-auth.html\n      - type: API Reference\n        url: https://developer.salesforce.com/docs/platform/pub-sub-api/guide/grpc-api.html\n      - type: Rate Limits\n        url: https://developer.salesforce.com/docs/platform/pub-sub-api/guide/allocations.html\n      - type: GitHub\n        url: https://github.com/forcedotcom/pub-sub-api\n    contact:\n      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce GraphQL API\n    description: >-\n      GraphQL API for querying Salesforce data with a single endpoint, reducing round\n      trips and improving application performance.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/platform/graphql/overview\n    baseURL: https://yourInstance.salesforce.com/services/data/v63.0/graphql\n\
  \    tags:\n      - Data\n      - GraphQL\n      - Query\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/platform/graphql/overview\n      - type: JSONLD\n        url: json-ld/salesforce-automation-context.jsonld\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/platform/graphql/guide/graphql-about.html\n      - type: Quick Start\n        url: https://developer.salesforce.com/docs/platform/graphql/guide/get-started.html\n      - type: API Reference\n        url: https://developer.salesforce.com/docs/platform/graphql/guide/requests-and-responses.html\n    contact:\n      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce Change Data Capture API\n    description: >-\n      API for receiving near-real-time notifications of changes to Salesforce records\n      to synchronize corresponding records in external\
  \ data stores.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture\n    baseURL: https://yourInstance.salesforce.com/services/data/v63.0/sobjects\n    tags:\n      - CDC\n      - Change Data Capture\n      - Events\n      - Real-Time\n      - Synchronization\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture\n      - type: OpenAPI\n        url: openapi/salesforce-change-data-capture-api-openapi.json\n      - type: JSONLD\n        url: json-ld/salesforce-automation-context.jsonld\n      - type: Developer Guide\n        url: https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/cdc_what.htm\n      - type: Trailhead\n        url: https://trailhead.salesforce.com/content/learn/modules/change-data-capture/understand-change-data-capture\n\
  \    contact:\n      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce Invocable Actions API\n    description: >-\n      REST API for invoking standard and custom actions programmatically, including\n      flow actions and process automation triggers.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm\n    baseURL: https://yourInstance.salesforce.com/services/data/v63.0/actions\n    tags:\n      - Actions\n      - Automation\n      - Flows\n      - Invocable\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm\n      - type: OpenAPI\n        url: openapi/salesforce-invocable-actions-api-openapi.json\n      - type: JSONLD\n\
  \        url: json-ld/salesforce-automation-context.jsonld\n      - type: Standard Actions Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable_standard.htm\n      - type: Custom Actions Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable_custom.htm\n      - type: Flow Actions\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_action.meta/api_action/actions_obj_flow.htm\n      - type: Launch a Flow from REST API\n        url: https://help.salesforce.com/s/articleView?id=sf.flow_distribute_system_rest.htm&language=en_US&type=5\n    contact:\n      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce Composite API\n    description: >-\n      REST API for executing multiple API requests in a single call, with the ability\n      to\
  \ use the output of one request as input to another.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite_composite.htm\n    baseURL: https://yourInstance.salesforce.com/services/data/v63.0/composite\n    tags:\n      - Batch\n      - Composite\n      - Performance\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite_composite.htm\n      - type: OpenAPI\n        url: openapi/salesforce-composite-api-openapi.json\n      - type: JSONLD\n        url: json-ld/salesforce-automation-context.jsonld\n      - type: Developer Guide\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/using_composite_resources.htm\n      - type: Composite Batch\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite_batch.htm\n\
  \      - type: Composite Graph\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/using_resources_composite_graph.htm\n    contact:\n      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\n  - name: Salesforce Apex REST API\n    description: >-\n      Framework for exposing Apex classes and methods as RESTful web services, enabling\n      custom API endpoints on the Salesforce platform.\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest.htm\n    baseURL: https://yourInstance.salesforce.com/services/apexrest\n    tags:\n      - Apex\n      - Custom Endpoints\n      - Development\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest.htm\n\
  \      - type: OpenAPI\n        url: openapi/salesforce-apex-rest-api-openapi.json\n      - type: JSONLD\n        url: json-ld/salesforce-automation-context.jsonld\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest_intro.htm\n      - type: API Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.apexref.meta/apexref/apex_methods_system_restrequest.htm\n      - type: Code Samples\n        url: https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest_code_samples.htm\n    contact:\n      - FN: Salesforce Developer Support\n        email: developer@salesforce.com\n        url: https://developer.salesforce.com/support\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ncommon:\n  - type: Portal\n    url: https://developer.salesforce.com\n  - type: Website\n    url: https://www.salesforce.com\n  - type: Developer Portal\n\
  \    url: https://developer.salesforce.com\n  - type: Documentation\n    url: https://developer.salesforce.com/docs\n  - type: API Library\n    url: https://developer.salesforce.com/docs/apis\n  - type: Trailhead Learning\n    url: https://trailhead.salesforce.com\n  - type: API Status\n    url: https://status.salesforce.com\n  - type: Community\n    url: https://developer.salesforce.com/forums\n  - type: Blog\n    url: https://developer.salesforce.com/blogs\n  - type: Pricing\n    url: https://www.salesforce.com/editions-pricing/overview/\n  - type: Terms of Service\n    url: https://www.salesforce.com/company/legal/agreements/\n  - type: Privacy Policy\n    url: https://www.salesforce.com/company/privacy/\n  - type: Sign Up\n    url: https://developer.salesforce.com/signup\n  - type: Login\n    url: https://login.salesforce.com\n  - type: GitHub\n    url: https://github.com/salesforce\n  - type: GitHub Organization\n    url: https://github.com/developerforce\n  - type: Stack Exchange\n\
  \    url: https://salesforce.stackexchange.com\n  - type: X (Twitter)\n    url: https://twitter.com/salesforcedevs\n  - type: Support\n    url: https://developer.salesforce.com/support\n  - type: Contact\n    url: https://www.salesforce.com/company/contact-us/\n  - type: Rate Limits\n    url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm\n  - type: API Versioning\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_versions.htm\n  - type: Postman Collection\n    url: https://www.postman.com/salesforce-developers/workspace/salesforce-developers/overview\n  - type: Postman GitHub\n    url: https://github.com/forcedotcom/postman-salesforce-apis\n  - type: SDKs\n    url: https://jsforce.github.io/\n  - type: Release Notes\n    url: https://help.salesforce.com/s/articleView?id=release-notes.rn_api_nc.htm&language=en_US&release=248&type=5\n\
  \  - type: API End-of-Life Policy\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/api_rest_eol.htm\n  - type: SpectralRules\n    url: rules/salesforce-automation-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/salesforce-automation-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/data-operations.yaml\n    title: Data Operations Workflow\n  - type: JSONStructure\n    url: json-structure/salesforce-automation-flow-structure.json\n  - type: Example\n    url: examples/salesforce-automation-flow-example.json\n    title: Flow Example\n  - type: GitHubOrganization\n    url: https://github.com/salesforce\n  - type: Features\n    data:\n      - name: OAuth 2.0 Authentication\n        description: Supports multiple OAuth flows including authorization code, JWT bearer, and client credentials.\n      - name: SOQL Queries\n        description: Salesforce Object Query Language for structured data queries across objects.\n      - name:\
  \ SOSL Search\n        description: Full-text search across multiple objects using Salesforce Object Search Language.\n      - name: Bulk Data Operations\n        description: Asynchronous bulk API for loading, deleting, and querying millions of records.\n      - name: Real-Time Events\n        description: Platform events, Change Data Capture, and streaming API for real-time notifications.\n      - name: Flow Automation\n        description: Declarative automation with Flow Builder for record-triggered, scheduled, and screen flows.\n      - name: Composite API\n        description: Execute multiple API requests in a single call with request chaining.\n      - name: GraphQL Support\n        description: Single-endpoint GraphQL API for efficient data queries.\n      - name: Invocable Actions\n        description: Programmatic invocation of standard and custom automation actions.\n      - name: Approval Processes\n        description: Multi-step approval workflows with programmatic submission\
  \ and management.\n  - type: UseCases\n    data:\n      - name: Sales Pipeline Automation\n        description: Automate lead assignment, opportunity stage progression, and deal closure workflows.\n      - name: Data Migration\n        description: Bulk import and export of large datasets between Salesforce and external systems.\n      - name: Real-Time Data Sync\n        description: Keep external systems in sync with Salesforce using Change Data Capture events.\n      - name: Custom Integrations\n        description: Build custom REST endpoints using Apex REST for bespoke integration scenarios.\n      - name: Analytics and Reporting\n        description: Programmatic access to Einstein Analytics dashboards and datasets.\n      - name: Process Automation\n        description: Trigger flows, approval processes, and invocable actions based on data changes.\n  - type: Integrations\n    data:\n      - name: MuleSoft\n        description: Native integration platform for connecting Salesforce\
  \ with enterprise systems.\n      - name: Slack\n        description: Salesforce-owned collaboration platform with deep CRM integration.\n      - name: Tableau\n        description: Analytics and visualization platform integrated with Salesforce data.\n      - name: Heroku\n        description: Cloud application platform for extending Salesforce with custom apps.\n      - name: Postman\n        description: Official Postman workspace with pre-built API collections for testing.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/apis.yml
tags:
- Automation
- Cloud
- CRM
- Enterprise
- Sales
url: https://developer.salesforce.com
use_cases:
- description: Automate lead assignment, opportunity stage progression, and deal closure workflows.
  name: Sales Pipeline Automation
- description: Bulk import and export of large datasets between Salesforce and external systems.
  name: Data Migration
- description: Keep external systems in sync with Salesforce using Change Data Capture events.
  name: Real-Time Data Sync
- description: Build custom REST endpoints using Apex REST for bespoke integration scenarios.
  name: Custom Integrations
- description: Programmatic access to Einstein Analytics dashboards and datasets.
  name: Analytics and Reporting
- description: Trigger flows, approval processes, and invocable actions based on data changes.
  name: Process Automation
---
