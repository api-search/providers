---
api_count: 15
api_specs:
- filename: salesforce-sales-cloud-rest-api-openapi.yml
  format: yaml
  label: Salesforce REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-rest-api-openapi.yml
- filename: salesforce-sales-cloud-bulk-api-openapi.yml
  format: yaml
  label: Bulk API 2.0
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-bulk-api-openapi.yml
- filename: salesforce-sales-cloud-platform-events-api-openapi.yml
  format: yaml
  label: Platform Events API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-platform-events-api-openapi.yml
- filename: salesforce-sales-cloud-analytics-api-openapi.yml
  format: yaml
  label: Analytics REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-analytics-api-openapi.yml
- filename: salesforce-sales-cloud-composite-api-openapi.yml
  format: yaml
  label: Salesforce Composite API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-composite-api-openapi.yml
- filename: salesforce-sales-cloud-graphql-api-openapi.yml
  format: yaml
  label: Salesforce GraphQL API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-graphql-api-openapi.yml
- filename: salesforce-sales-cloud-tooling-api-openapi.yml
  format: yaml
  label: Salesforce Tooling API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-tooling-api-openapi.yml
- filename: salesforce-sales-cloud-change-data-capture-api-openapi.yml
  format: yaml
  label: Salesforce Change Data Capture API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-change-data-capture-api-openapi.yml
- filename: salesforce-sales-cloud-connect-api-openapi.yml
  format: yaml
  label: Salesforce Connect REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-connect-api-openapi.yml
- filename: salesforce-sales-cloud-ui-api-openapi.yml
  format: yaml
  label: Salesforce User Interface API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-ui-api-openapi.yml
- filename: salesforce-sales-cloud-apex-rest-api-openapi.yml
  format: yaml
  label: Salesforce Apex REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/openapi/salesforce-sales-cloud-apex-rest-api-openapi.yml
apis:
- description: Primary REST API for accessing Salesforce data including accounts, contacts, leads, opportunities, and custom objects. Supports JSON and XML formats with a lightweight request and response framework.
  name: Salesforce REST API
  slug: ''
- description: Comprehensive SOAP-based API for enterprise integrations with full CRUD operations on Salesforce objects. Uses WSDL files to define parameters for accessing data through the API.
  name: Salesforce SOAP API
  slug: ''
- description: Optimized API for loading, updating, or deleting large data sets asynchronously with better performance than REST API. Supports CSV, JSON, and XML data formats.
  name: Bulk API 2.0
  slug: ''
- description: API for retrieving, deploying, creating, updating, or deleting customization information such as custom object definitions and page layouts. Essential for managing org configuration and deployment wor
  name: Metadata API
  slug: ''
- description: Push notification API using Bayeux protocol to receive near real-time updates when data changes in Salesforce. Enables event-driven integrations without polling.
  name: Streaming API
  slug: ''
- description: Event-driven architecture API for publishing and subscribing to custom events for app integration. Supports defining custom event channels with schema for loosely coupled systems.
  name: Platform Events API
  slug: ''
- description: Access Salesforce reports, dashboards, and analytics data programmatically. Enables embedding analytics into custom applications and automating report generation.
  name: Analytics REST API
  slug: ''
- description: Executes a series of REST API requests in a single call, reducing round trips between client and server. Supports composite batches, composite requests, and composite graphs for complex multi-step ope
  name: Salesforce Composite API
  slug: ''
- description: Query Salesforce data using GraphQL, allowing clients to request exactly the fields they need in a single request. Reduces payload size and supports aggregation across object relationships.
  name: Salesforce GraphQL API
  slug: ''
- description: Build custom development tools for Salesforce applications by accessing metadata about Apex classes, triggers, Visualforce pages, and other development artifacts. Supports both REST and SOAP interface
  name: Salesforce Tooling API
  slug: ''
- description: gRPC-based API for publishing and subscribing to platform events, change data capture events, and real-time event monitoring events. Uses Apache Avro format for efficient binary event message delivery
  name: Salesforce Pub/Sub API
  slug: ''
- description: Receive near-real-time notifications of changes to Salesforce records including creates, updates, deletes, and undeletes. Enables synchronization of external data stores with Salesforce data.
  name: Salesforce Change Data Capture API
  slug: ''
- description: Integrate mobile apps, intranet sites, and third-party web applications with Salesforce, including access to Chatter feeds, groups, users, and collaboration features.
  name: Salesforce Connect REST API
  slug: ''
- description: Build custom user interfaces for Salesforce data using the same API that powers Lightning Experience. Returns data and metadata in a single response with layout, picklist, and field-level security awa
  name: Salesforce User Interface API
  slug: ''
- description: Create custom REST endpoints in Salesforce using Apex classes annotated with REST resource annotations. Supports OAuth 2.0 authentication and JSON and XML request and response formats.
  name: Salesforce Apex REST API
  slug: ''
capabilities:
- description: Workflow capability for bulk data loading, real-time event streaming, and enterprise data integration in Salesforce Sales Cloud. Combines Bulk API 2.0 for large dataset operations with Change Data Cap
  name: Salesforce Sales Cloud Data Integration
  slug: data-integration
- description: Unified workflow capability for managing the full sales pipeline in Salesforce Sales Cloud. Combines REST API access to accounts, contacts, leads, opportunities, and activities with analytics for pipe
  name: Salesforce Sales Pipeline Management
  slug: sales-pipeline-management
common:
- title: ''
  type: Portal
  url: https://developer.salesforce.com/
- title: ''
  type: Documentation
  url: https://developer.salesforce.com/docs
- title: ''
  type: Getting Started
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/quickstart.htm
- title: ''
  type: Authentication
  url: https://help.salesforce.com/s/articleView?id=sf.remoteaccess_authenticate.htm
- title: ''
  type: Blog
  url: https://developer.salesforce.com/blogs
- title: ''
  type: Status
  url: https://status.salesforce.com/
- title: ''
  type: Support
  url: https://help.salesforce.com/
- title: ''
  type: Terms of Service
  url: https://www.salesforce.com/company/legal/agreements/
- title: ''
  type: Privacy Policy
  url: https://www.salesforce.com/company/privacy/
- title: ''
  type: GitHub Organization
  url: https://github.com/salesforce
- title: ''
  type: Community
  url: https://trailhead.salesforce.com/en/trailblazercommunity
- title: ''
  type: Website
  url: https://www.salesforce.com/products/sales-cloud/
- title: ''
  type: Login
  url: https://login.salesforce.com/
- title: ''
  type: Sign Up
  url: https://developer.salesforce.com/signup
- title: ''
  type: SDKs
  url: https://developer.salesforce.com/tools/sdk
- title: ''
  type: API Console
  url: https://workbench.developerforce.com/
- title: ''
  type: Trailhead Learning
  url: https://trailhead.salesforce.com/en/content/learn/modules/api_basics
- title: ''
  type: API Limits
  url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm
- title: ''
  type: API Library
  url: https://developer.salesforce.com/docs/apis
- title: ''
  type: Postman Collection
  url: https://www.postman.com/salesforce-developers/workspace/salesforce-developers
- title: ''
  type: Change Log
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/rest_rns.htm
- title: ''
  type: SOQL and SOSL Reference
  url: https://developer.salesforce.com/docs/atlas.en-us.soql_sosl.meta/soql_sosl/sforce_api_calls_soql_sosl_intro.htm
- title: ''
  type: JSON-LD Context
  url: json-ld/salesforce-sales-cloud-context.jsonld
- title: ''
  type: Spectral Rules
  url: rules/salesforce-sales-cloud-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/sales-pipeline-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/salesforce-sales-cloud-vocabulary.yml
- title: Account Schema
  type: JSON Schema
  url: json-schema/salesforce-sales-cloud-account-schema.json
- title: Contact Schema
  type: JSON Schema
  url: json-schema/salesforce-sales-cloud-contact-schema.json
- title: Lead Schema
  type: JSON Schema
  url: json-schema/salesforce-sales-cloud-lead-schema.json
- title: Opportunity Schema
  type: JSON Schema
  url: json-schema/salesforce-sales-cloud-opportunity-schema.json
- title: Task Schema
  type: JSON Schema
  url: json-schema/salesforce-sales-cloud-task-schema.json
- title: Case Schema
  type: JSON Schema
  url: json-schema/salesforce-sales-cloud-case-schema.json
- title: Campaign Schema
  type: JSON Schema
  url: json-schema/salesforce-sales-cloud-campaign-schema.json
created: '2024-01-15'
description: Enterprise CRM platform providing sales automation, customer relationship management, and business intelligence capabilities through REST and SOAP APIs.
features: []
image: https://www.salesforce.com/content/dam/web/en_us/www/images/salesforce-logo.svg
integrations: []
jsonld:
- class_count: 2
  name: Salesforce Sales Cloud Context
  property_count: 11
  slug: salesforce-sales-cloud-context
layout: provider
modified: '2026-03-04'
name: Salesforce Sales Cloud
rules:
- name: Salesforce Sales Cloud API Rules
  rule_count: 10
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 4
  slug: salesforce-sales-cloud-rules
skills: []
slug: salesforce-sales-cloud
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Salesforce Sales Cloud\ndescription: Enterprise CRM platform providing sales automation, customer relationship management, and business intelligence capabilities through REST and SOAP APIs.\nimage: https://www.salesforce.com/content/dam/web/en_us/www/images/salesforce-logo.svg\nurl: https://www.salesforce.com/products/sales-cloud/overview/\ncreated: '2024-01-15'\nmodified: '2026-03-04'\nspecificationVersion: '0.18'\ntags:\n  - Cloud\n  - CRM\n  - Customer Management\n  - Enterprise\n  - Sales\napis:\n  - name: Salesforce REST API\n    description: Primary REST API for accessing Salesforce data including accounts, contacts, leads, opportunities, and custom objects. Supports JSON and XML formats with a lightweight request and response framework.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/salesforce-logo.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0\n\
  \    tags:\n      - CRUD\n      - Data\n      - Objects\n      - Records\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_rest.htm\n      - type: OpenAPI\n        url: openapi/salesforce-sales-cloud-rest-api-openapi.yml\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_understanding_authentication.htm\n      - type: Postman Collection\n        url: https://www.postman.com/salesforce-developers/workspace/salesforce-developers\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/quickstart.htm\n      - type: Change Log\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/rest_rns.htm\n  - name: Salesforce SOAP API\n    description: Comprehensive SOAP-based API for enterprise integrations with full CRUD operations on\
  \ Salesforce objects. Uses WSDL files to define parameters for accessing data through the API.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/\n    baseURL: https://yourInstance.salesforce.com/services/Soap/u/59.0\n    tags:\n      - Enterprise\n      - Integration\n      - SOAP\n      - XML\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_quickstart_intro.htm\n      - type: WSDL\n        url: https://yourInstance.salesforce.com/services/wsdl/enterprise\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_calls_login.htm\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_quickstart_steps.htm\n  - name: Bulk API 2.0\n    description: Optimized API for loading, updating, or deleting large data sets asynchronously with better performance than REST\
  \ API. Supports CSV, JSON, and XML data formats.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/jobs/ingest\n    tags:\n      - Async\n      - Bulk\n      - Data Loading\n      - ETL\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/asynch_api_intro.htm\n      - type: Examples\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/asynch_api_code_samples.htm\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/bulk_api_2_0.htm\n      - type: OpenAPI\n        url: openapi/salesforce-sales-cloud-bulk-api-openapi.yml\n  - name: Metadata API\n    description: API for retrieving, deploying, creating, updating, or deleting customization information such as custom object definitions and page\
  \ layouts. Essential for managing org configuration and deployment workflows.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/\n    baseURL: https://yourInstance.salesforce.com/services/Soap/m/59.0\n    tags:\n      - Configuration\n      - Customization\n      - Deployment\n      - Metadata\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_intro.htm\n      - type: WSDL\n        url: https://yourInstance.salesforce.com/services/wsdl/metadata\n      - type: Change Log\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_rns.htm\n  - name: Streaming API\n    description: Push notification API using Bayeux protocol to receive near real-time updates when data changes in Salesforce. Enables event-driven integrations without polling.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/\n\
  \    baseURL: https://yourInstance.salesforce.com/cometd/59.0\n    tags:\n      - Events\n      - Push Notifications\n      - Real-Time\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/intro_stream.htm\n      - type: Examples\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/code_sample_java_client_intro.htm\n  - name: Platform Events API\n    description: Event-driven architecture API for publishing and subscribing to custom events for app integration. Supports defining custom event channels with schema for loosely coupled systems.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/sobjects\n    tags:\n      - Events\n      - Integration\n      - Messaging\n      - Pub/Sub\n    properties:\n      - type: Documentation\n\
  \        url: https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/platform_events_intro.htm\n      - type: Guide\n        url: https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/platform_events_publish_api.htm\n      - type: OpenAPI\n        url: openapi/salesforce-sales-cloud-platform-events-api-openapi.yml\n  - name: Analytics REST API\n    description: Access Salesforce reports, dashboards, and analytics data programmatically. Enables embedding analytics into custom applications and automating report generation.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/analytics\n    tags:\n      - Analytics\n      - Business Intelligence\n      - Dashboards\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/sforce_analytics_rest_api_intro.htm\n\
  \      - type: OpenAPI\n        url: openapi/salesforce-sales-cloud-analytics-api-openapi.yml\n  - name: Salesforce Composite API\n    description: Executes a series of REST API requests in a single call, reducing round trips between client and server. Supports composite batches, composite requests, and composite graphs for complex multi-step operations.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/using_composite_resources.htm\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/composite\n    tags:\n      - Batch\n      - Composite\n      - Integration\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/using_composite_resources.htm\n      - type: Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite_composite.htm\n      - type: Guide\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite_graph_introduction.htm\n\
  \      - type: OpenAPI\n        url: openapi/salesforce-sales-cloud-composite-api-openapi.yml\n  - name: Salesforce GraphQL API\n    description: Query Salesforce data using GraphQL, allowing clients to request exactly the fields they need in a single request. Reduces payload size and supports aggregation across object relationships.\n    humanURL: https://developer.salesforce.com/docs/platform/graphql/overview\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/graphql\n    tags:\n      - Data Access\n      - GraphQL\n      - Query\n      - Schema\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/platform/graphql/guide/intro-graphql-api.html\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/platform/graphql/guide/get-started.html\n      - type: Reference\n        url: https://developer.salesforce.com/docs/platform/graphql/guide/requests-and-responses.html\n      - type: OpenAPI\n       \
  \ url: openapi/salesforce-sales-cloud-graphql-api-openapi.yml\n  - name: Salesforce Tooling API\n    description: Build custom development tools for Salesforce applications by accessing metadata about Apex classes, triggers, Visualforce pages, and other development artifacts. Supports both REST and SOAP interfaces.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/tooling\n    tags:\n      - Apex\n      - Development\n      - Metadata\n      - Tooling\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/intro_rest_overview.htm\n      - type: Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/intro_rest_resources.htm\n      - type: Examples\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/intro_rest_resource_examples.htm\n\
  \      - type: OpenAPI\n        url: openapi/salesforce-sales-cloud-tooling-api-openapi.yml\n  - name: Salesforce Pub/Sub API\n    description: gRPC-based API for publishing and subscribing to platform events, change data capture events, and real-time event monitoring events. Uses Apache Avro format for efficient binary event message delivery over HTTP/2.\n    humanURL: https://developer.salesforce.com/docs/platform/pub-sub-api/guide/intro.html\n    baseURL: https://yourInstance.salesforce.com\n    tags:\n      - Events\n      - gRPC\n      - Pub/Sub\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/platform/pub-sub-api/guide/intro.html\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/platform/pub-sub-api/guide/grpc-api.html\n      - type: Reference\n        url: https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-endpoints.html\n  - name: Salesforce Change Data Capture\
  \ API\n    description: Receive near-real-time notifications of changes to Salesforce records including creates, updates, deletes, and undeletes. Enables synchronization of external data stores with Salesforce data.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/cdc_intro.htm\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0\n    tags:\n      - Change Data Capture\n      - Events\n      - Real-Time\n      - Synchronization\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/cdc_intro.htm\n      - type: Guide\n        url: https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/cdc_what.htm\n      - type: Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/cdc_message_structure.htm\n      - type: OpenAPI\n\
  \        url: openapi/salesforce-sales-cloud-change-data-capture-api-openapi.yml\n  - name: Salesforce Connect REST API\n    description: Integrate mobile apps, intranet sites, and third-party web applications with Salesforce, including access to Chatter feeds, groups, users, and collaboration features.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/intro_what_is_chatter_connect.htm\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/connect\n    tags:\n      - Chatter\n      - Collaboration\n      - Connect\n      - Social\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/intro_what_is_chatter_connect.htm\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/quickstart.htm\n      - type: Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_overview.htm\n\
  \      - type: Examples\n        url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/quickreference.htm\n      - type: Change Log\n        url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/intro_release_notes.htm\n      - type: OpenAPI\n        url: openapi/salesforce-sales-cloud-connect-api-openapi.yml\n  - name: Salesforce User Interface API\n    description: Build custom user interfaces for Salesforce data using the same API that powers Lightning Experience. Returns data and metadata in a single response with layout, picklist, and field-level security awareness.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/ui-api\n    tags:\n      - Layouts\n      - Lightning\n      - Records\n      - User Interface\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_get_started.htm\n\
  \      - type: Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_resources_overview.htm\n      - type: OpenAPI\n        url: openapi/salesforce-sales-cloud-ui-api-openapi.yml\n  - name: Salesforce Apex REST API\n    description: Create custom REST endpoints in Salesforce using Apex classes annotated with REST resource annotations. Supports OAuth 2.0 authentication and JSON and XML request and response formats.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest.htm\n    baseURL: https://yourInstance.salesforce.com/services/apexrest\n    tags:\n      - Apex\n      - Custom Endpoints\n      - Development\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest.htm\n      - type: OpenAPI\n        url: openapi/salesforce-sales-cloud-apex-rest-api-openapi.yml\ncommon:\n  - type: Portal\n    url: https://developer.salesforce.com/\n\
  \  - type: Documentation\n    url: https://developer.salesforce.com/docs\n  - type: Getting Started\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/quickstart.htm\n  - type: Authentication\n    url: https://help.salesforce.com/s/articleView?id=sf.remoteaccess_authenticate.htm\n  - type: Blog\n    url: https://developer.salesforce.com/blogs\n  - type: Status\n    url: https://status.salesforce.com/\n  - type: Support\n    url: https://help.salesforce.com/\n  - type: Terms of Service\n    url: https://www.salesforce.com/company/legal/agreements/\n  - type: Privacy Policy\n    url: https://www.salesforce.com/company/privacy/\n  - type: GitHub Organization\n    url: https://github.com/salesforce\n  - type: Community\n    url: https://trailhead.salesforce.com/en/trailblazercommunity\n  - type: Website\n    url: https://www.salesforce.com/products/sales-cloud/\n  - type: Login\n    url: https://login.salesforce.com/\n  - type: Sign Up\n    url: https://developer.salesforce.com/signup\n\
  \  - type: SDKs\n    url: https://developer.salesforce.com/tools/sdk\n  - type: API Console\n    url: https://workbench.developerforce.com/\n  - type: Trailhead Learning\n    url: https://trailhead.salesforce.com/en/content/learn/modules/api_basics\n  - type: API Limits\n    url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm\n  - type: API Library\n    url: https://developer.salesforce.com/docs/apis\n  - type: Postman Collection\n    url: https://www.postman.com/salesforce-developers/workspace/salesforce-developers\n  - type: Change Log\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/rest_rns.htm\n  - type: SOQL and SOSL Reference\n    url: https://developer.salesforce.com/docs/atlas.en-us.soql_sosl.meta/soql_sosl/sforce_api_calls_soql_sosl_intro.htm\n  - type: JSON-LD Context\n    url: json-ld/salesforce-sales-cloud-context.jsonld\n  - type:\
  \ Spectral Rules\n    url: rules/salesforce-sales-cloud-rules.yml\n  - type: Capabilities\n    url: capabilities/sales-pipeline-management.yaml\n  - type: Vocabulary\n    url: vocabulary/salesforce-sales-cloud-vocabulary.yml\n  - type: JSON Schema\n    url: json-schema/salesforce-sales-cloud-account-schema.json\n    title: Account Schema\n  - type: JSON Schema\n    url: json-schema/salesforce-sales-cloud-contact-schema.json\n    title: Contact Schema\n  - type: JSON Schema\n    url: json-schema/salesforce-sales-cloud-lead-schema.json\n    title: Lead Schema\n  - type: JSON Schema\n    url: json-schema/salesforce-sales-cloud-opportunity-schema.json\n    title: Opportunity Schema\n  - type: JSON Schema\n    url: json-schema/salesforce-sales-cloud-task-schema.json\n    title: Task Schema\n  - type: JSON Schema\n    url: json-schema/salesforce-sales-cloud-case-schema.json\n    title: Case Schema\n  - type: JSON Schema\n    url: json-schema/salesforce-sales-cloud-campaign-schema.json\n    title:\
  \ Campaign Schema\nmaintainer:\n  name: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesforce-sales-cloud/refs/heads/main/apis.yml
tags:
- Cloud
- CRM
- Customer Management
- Enterprise
- Sales
url: https://www.salesforce.com/products/sales-cloud/overview/
use_cases: []
---
