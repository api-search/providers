---
api_count: 43
api_specs:
- filename: salesforce-openapi.yml
  format: yaml
  label: Salesforce REST API
  slug: salesforce-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/openapi/salesforce-openapi.yml
- filename: salesforce-bulk-api-2-openapi.yml
  format: yaml
  label: Salesforce Bulk API 2.0
  slug: salesforce-bulk-api-2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/openapi/salesforce-bulk-api-2-openapi.yml
- filename: salesforce-streaming-asyncapi.yml
  format: yaml
  label: Salesforce Streaming API
  slug: salesforce-streaming-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/asyncapi/salesforce-streaming-asyncapi.yml
- filename: salesforce-platform-events-asyncapi.yml
  format: yaml
  label: Salesforce Platform Events API
  slug: salesforce-platform-events-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/asyncapi/salesforce-platform-events-asyncapi.yml
- filename: salesforce-change-data-capture-asyncapi.yml
  format: yaml
  label: Salesforce Change Data Capture API
  slug: salesforce-change-data-capture-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/asyncapi/salesforce-change-data-capture-asyncapi.yml
- filename: salesforce-ui-api-openapi.yml
  format: yaml
  label: Salesforce UI API
  slug: salesforce-ui-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/openapi/salesforce-ui-api-openapi.yml
- filename: salesforce-marketing-cloud-rest-openapi.yml
  format: yaml
  label: Salesforce Marketing Cloud REST API
  slug: salesforce-marketing-cloud-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/openapi/salesforce-marketing-cloud-rest-openapi.yml
- filename: salesforce-openapi.yml
  format: yaml
  label: Salesforce
  slug: salesforce-salesforce
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/openapi/salesforce-openapi.yml
apis:
- description: The Salesforce REST API provides a simple and powerful web service interface to interact with Salesforce org data. It supports creating, reading, updating, deleting, and querying records using SOQL an
  name: Salesforce REST API
  slug: salesforce-rest-api
- description: The Salesforce SOAP API enables developers to use SOAP calls to create, retrieve, update, and delete records such as accounts, leads, and custom objects. It provides robust enterprise-grade integratio
  name: Salesforce SOAP API
  slug: salesforce-soap-api
- description: 'The Salesforce Bulk API is a specialized REST-based interface that enables asynchronous processing of large numbers of records. It is optimized for loading or deleting large sets of data and supports '
  name: Salesforce Bulk API
  slug: salesforce-bulk-api
- description: Salesforce Bulk API 2.0 is a simplified, REST-based interface for bulk data operations that improves on the original Bulk API. It uses a straightforward job model and supports CSV format for ingest an
  name: Salesforce Bulk API 2.0
  slug: salesforce-bulk-api-2
- description: The Salesforce Streaming API uses a publish-subscribe model based on Bayeux/CometD to push near-real-time event notifications to subscribed clients. It supports PushTopic events for record changes and
  name: Salesforce Streaming API
  slug: salesforce-streaming-api
- description: The Salesforce Metadata API is a SOAP-based API that enables developers to retrieve, deploy, create, update, and delete customizations for Salesforce organizations. It is the foundation for tools like
  name: Salesforce Metadata API
  slug: salesforce-metadata-api
- description: The Salesforce Tooling API provides SOAP and REST interfaces for building developer tools for Force.com applications. It exposes fine-grained access to Apex code, Visualforce pages, and other metadata
  name: Salesforce Tooling API
  slug: salesforce-tooling-api
- description: 'The Salesforce Connect REST API (formerly Chatter API) provides access to Salesforce Chatter feeds, groups, users, topics, and file sharing features. It also exposes Experience Cloud (community) data '
  name: Salesforce Connect API (Chatter)
  slug: salesforce-connect-api
- description: The Salesforce Analytics REST API (also known as CRM Analytics or Wave API) provides programmatic access to CRM Analytics datasets, lenses, dashboards, and queries. Developers can read and write analy
  name: Salesforce Analytics REST API
  slug: salesforce-analytics-rest-api
- description: The Salesforce Reports and Dashboards REST API enables developers to programmatically access report results, list reports and dashboards, and run and filter reports. It supports accessing standard and
  name: Salesforce Reports and Dashboards REST API
  slug: salesforce-reports-and-dashboards-rest-api
- description: The Salesforce Einstein Platform Services API provides REST-based access to Salesforce AI capabilities including image classification, object detection, and sentiment analysis. Developers can train cu
  name: Salesforce Einstein Platform Services API
  slug: salesforce-einstein-platform-services-api
- description: The Salesforce Einstein Prediction Service API enables programmatic access to Einstein Analytics predictions and forecasts built on CRM data. It allows applications to retrieve AI-driven predictions f
  name: Salesforce Einstein Prediction Service API
  slug: salesforce-einstein-prediction-service-api
- description: The Salesforce GraphQL API provides a GraphQL interface to query and mutate Salesforce data. It allows clients to request exactly the data they need in a single request, reducing over-fetching and und
  name: Salesforce GraphQL API
  slug: salesforce-graphql-api
- description: The Salesforce Pub/Sub API is a gRPC-based API for publishing and subscribing to platform events, change data capture events, and other event types in real time. It supersedes the CometD-based Streami
  name: Salesforce Pub/Sub API
  slug: salesforce-pub-sub-api
- description: Salesforce Platform Events enables event-driven integration architectures built on the Salesforce platform. Developers define custom event types as Salesforce objects and publish or subscribe to event
  name: Salesforce Platform Events API
  slug: salesforce-platform-events-api
- description: Salesforce Change Data Capture delivers change events that represent changes to Salesforce records including creates, updates, deletes, and undeletes. It enables external systems to receive near-real-
  name: Salesforce Change Data Capture API
  slug: salesforce-change-data-capture-api
- description: The Salesforce UI API provides a comprehensive REST interface for building UIs that work with Salesforce metadata and data. It returns layout information, picklist values, list views, record data, and
  name: Salesforce UI API
  slug: salesforce-ui-api
- description: The Salesforce Composite API allows developers to combine multiple Salesforce REST API requests into a single HTTP call. It reduces the number of round trips to the server and supports dependent reque
  name: Salesforce Composite API
  slug: salesforce-composite-api
- description: Salesforce Apex REST enables developers to expose custom Apex classes as RESTful web services. By annotating Apex classes and methods with @RestResource and HTTP method annotations, developers can cre
  name: Salesforce Apex REST API
  slug: salesforce-apex-rest-api
- description: The Salesforce Data Cloud API provides programmatic access to Data Cloud (formerly Customer Data Platform) for ingesting, querying, and managing unified customer profiles. It enables applications to r
  name: Salesforce Data Cloud API
  slug: salesforce-data-cloud-api
- description: 'The Salesforce Marketing Cloud REST API provides access to Marketing Cloud resources including contacts, journeys, data extensions, triggered sends, and transactional messaging. It uses OAuth 2.0 for '
  name: Salesforce Marketing Cloud REST API
  slug: salesforce-marketing-cloud-rest-api
- description: The Salesforce Marketing Cloud SOAP API is a full-featured SOAP web service interface for Marketing Cloud that supports subscriber management, email send operations, automation activities, and data ex
  name: Salesforce Marketing Cloud SOAP API
  slug: salesforce-marketing-cloud-soap-api
- description: The Salesforce Pardot API (now called Account Engagement API) provides programmatic access to Pardot marketing automation data including prospects, campaigns, forms, lists, and email statistics for B2
  name: Salesforce Pardot API (Account Engagement)
  slug: salesforce-pardot-api
- description: The Salesforce Commerce Cloud Open Commerce API (OCAPI) provides a REST interface for accessing Salesforce B2C Commerce data and functionality including products, catalogs, orders, promotions, and cus
  name: Salesforce Commerce Cloud OCAPI
  slug: salesforce-commerce-cloud-ocapi
- description: The Salesforce Commerce Cloud Shopper APIs (SCAPI) are a modern set of REST APIs for building B2C Commerce storefronts and headless commerce experiences. They cover shopper authentication, products, s
  name: Salesforce Commerce Cloud Shopper APIs (SCAPI)
  slug: salesforce-commerce-cloud-shopper-apis
- description: The Salesforce Field Service API provides access to Field Service Lightning data and operations including work orders, service appointments, resource scheduling, and mobile workforce management. It en
  name: Salesforce Field Service API
  slug: salesforce-field-service-api
- description: The Salesforce Health Cloud API provides FHIR R4-compliant REST APIs and platform APIs for accessing patient and provider data in Health Cloud. It enables healthcare applications to interact with clin
  name: Salesforce Health Cloud API
  slug: salesforce-health-cloud-api
- description: The Salesforce Financial Services Cloud API exposes financial services-specific data objects including financial accounts, assets, liabilities, financial goals, and household relationships. It enables
  name: Salesforce Financial Services Cloud API
  slug: salesforce-financial-services-cloud-api
- description: The Salesforce Experience Cloud API provides REST access to Experience Cloud (formerly Community Cloud) data including community membership, navigation, managed content, and knowledge articles. It ena
  name: Salesforce Experience Cloud API
  slug: salesforce-experience-cloud-api
- description: The MuleSoft Anypoint Platform API provides programmatic access to the MuleSoft integration platform including API Manager, Runtime Manager, Exchange, and Access Management. It enables automation of A
  name: Salesforce MuleSoft Anypoint Platform API
  slug: salesforce-mulesoft-anypoint-platform-api
- description: The Tableau REST API enables developers to programmatically manage Tableau Server and Tableau Cloud resources including workbooks, data sources, views, sites, users, and groups. It supports automation
  name: Salesforce Tableau REST API
  slug: salesforce-tableau-rest-api
- description: Lightning Web Components (LWC) is Salesforce's standards-based JavaScript framework for building UI components on the Salesforce platform. It uses modern web standards including custom elements, templ
  name: Salesforce Lightning Web Components (LWC)
  slug: salesforce-lightning-web-components
- description: Salesforce Aura Components is the legacy JavaScript component framework for building dynamic web applications on the Salesforce platform. It provides a data binding model, event system, and Apex contr
  name: Salesforce Aura Components
  slug: salesforce-aura-components
- description: The Salesforce Lightning Design System (SLDS) provides HTML and CSS component blueprints, design tokens, and utility classes for building applications visually consistent with Salesforce Lightning Exp
  name: Salesforce Lightning Design System (SLDS)
  slug: salesforce-lightning-design-system
- description: The Salesforce Agentforce Agent API is a REST API that enables developers to communicate with AI agents directly, starting sessions, sending messages, receiving responses, and ending sessions. It supp
  name: Salesforce Agentforce Agent API
  slug: salesforce-agentforce-agent-api
- description: The Salesforce Models API provides Apex classes and REST endpoints that connect applications to large language models (LLMs) from Salesforce partners including Anthropic, Google, and OpenAI. It suppor
  name: Salesforce Models API
  slug: salesforce-models-api
- description: The Salesforce Interaction Service API enables automation and customization of the Bring Your Own Channel (BYOC) experience for messaging. It sends inbound messaging interactions from external end-use
  name: Salesforce Interaction Service API
  slug: salesforce-interaction-service-api
- description: The Salesforce B2B Commerce API provides REST endpoints for handling commerce data in B2B and D2C storefronts. It offers support for address management, cart management, checkout processing, order man
  name: Salesforce B2B Commerce API
  slug: salesforce-b2b-commerce-api
- description: The Salesforce Actions API provides a unified interface for invoking standard and custom actions across the Salesforce platform. It supports Apex actions, Flow actions, quick actions, and invocable ac
  name: Salesforce Actions API
  slug: salesforce-actions-api
- description: The Salesforce IoT REST API provides programmatic access to Salesforce IoT data including contexts, orchestrations, and usage data. It enables developers to manage IoT events and orchestration rules f
  name: Salesforce IoT REST API
  slug: salesforce-iot-api
- description: The Salesforce Service Cloud Voice API provides Telephony Integration REST API and Voice Toolkit API for programmatically managing voice calls and integrating telephony systems with Salesforce. It sup
  name: Salesforce Service Cloud Voice API
  slug: salesforce-service-cloud-voice-api
- description: The Salesforce Mobile SDK provides libraries and tools for building native and hybrid mobile applications on iOS and Android that integrate with the Salesforce platform. It supports Swift, Objective-C
  name: Salesforce Mobile SDK
  slug: salesforce-mobile-sdk
- description: Salesforce is a cloud-based customer relationship management (CRM) platform that helps organizations manage and grow customer relationships across the entire lifecycle. It unifies sales, service, mark
  name: Salesforce
  slug: salesforce-salesforce
asyncapis:
- description: Salesforce Change Data Capture (CDC) delivers change events that represent changes to Salesforce records including creates, updates, deletes, and undeletes. Subscribers receive rich change events with
  name: Salesforce Change Data Capture API
  slug: salesforce-change-data-capture-asyncapi
- description: Salesforce Platform Events enables event-driven integration architectures on the Salesforce platform. Developers define custom event types as Salesforce objects with the __e suffix and publish or subs
  name: Salesforce Platform Events API
  slug: salesforce-platform-events-asyncapi
- description: The Salesforce Streaming API uses a publish-subscribe model based on Bayeux/CometD to push near-real-time event notifications to subscribed clients. It supports PushTopic events (triggered by SOQL que
  name: Salesforce Streaming API
  slug: salesforce-streaming-asyncapi
capabilities:
- description: Unified capability for CRM data management workflows combining the REST API, Bulk API 2.0, and UI API. Used by Salesforce admins, developers, and data teams to manage SObject records, run queries, per
  name: Salesforce CRM Data Management
  slug: crm-data-management
- description: 'Unified capability for marketing automation workflows combining the Marketing Cloud REST API for contact management, journey orchestration, email and SMS messaging, data extensions, and content asset '
  name: Salesforce Marketing Automation
  slug: marketing-automation
- description: Unified capability for Salesforce platform administration workflows combining the platform API and UI API for identity management, OAuth administration, metadata exploration, and application configura
  name: Salesforce Platform Administration
  slug: platform-administration
common:
- title: ''
  type: Portal
  url: https://developer.salesforce.com/
- title: ''
  type: Documentation
  url: https://developer.salesforce.com/
- title: ''
  type: GettingStarted
  url: https://trailhead.salesforce.com/
- title: ''
  type: StatusPage
  url: https://status.salesforce.com/
- title: ''
  type: Support
  url: https://help.salesforce.com/
- title: ''
  type: Community
  url: https://trailblazers.salesforce.com/
- title: ''
  type: Authentication
  url: https://help.salesforce.com/s/articleView?id=sf.remoteaccess_authenticate.htm
- title: ''
  type: OAuth Documentation
  url: https://help.salesforce.com/s/articleView?id=sf.remoteaccess_oauth_flows.htm
- title: ''
  type: API Versions
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/dome_versions.htm
- title: ''
  type: Postman Collection
  url: https://www.postman.com/salesforce-developers/
- title: ''
  type: GitHubOrganization
  url: https://github.com/salesforce
- title: ''
  type: TermsOfService
  url: https://www.salesforce.com/company/legal/agreements/
- title: ''
  type: PrivacyPolicy
  url: https://www.salesforce.com/company/privacy/
- title: ''
  type: SignUp
  url: https://login.salesforce.com/
- title: ''
  type: SignUp
  url: https://developer.salesforce.com/signup
- title: ''
  type: Console
  url: https://login.salesforce.com/
- title: ''
  type: Marketplace
  url: https://appexchange.salesforce.com/
- title: ''
  type: Blog
  url: https://developer.salesforce.com/blogs/
- title: ''
  type: SDK
  url: https://developer.salesforce.com/tools/salesforcecli
- title: ''
  type: SDK
  url: https://developer.salesforce.com/tools/
- title: ''
  type: ChangeLog
  url: https://developer.salesforce.com/release-notes/
- title: ''
  type: StackOverflow
  url: https://salesforce.stackexchange.com/
- title: ''
  type: Pricing
  url: https://www.salesforce.com/pricing/
- title: ''
  type: X
  url: https://twitter.com/salesforcedevs
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/showcase/salesforce-developers
- title: ''
  type: YouTube
  url: https://www.youtube.com/@salesforcedevelopers
- title: ''
  type: RateLimits
  url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm
- title: ''
  type: Security
  url: https://security.salesforce.com/security-advisories
- title: ''
  type: Security
  url: https://developer.salesforce.com/developer-centers/security
- title: ''
  type: Security
  url: https://developer.salesforce.com/docs/atlas.en-us.secure_coding_guide.meta/secure_coding_guide/secure_coding_guidelines.htm
- title: ''
  type: ReleaseNotes
  url: https://help.salesforce.com/s/articleView?id=release-notes.salesforce_release_notes.htm&language=en_US
- title: ''
  type: Events
  url: https://www.salesforce.com/events/
- title: ''
  type: Events
  url: https://www.salesforce.com/dreamforce/
- title: ''
  type: Portal
  url: https://developer.salesforce.com/developer-centers/integration-apis
- title: ''
  type: API Library
  url: https://developer.salesforce.com/docs/apis
- title: ''
  type: Portal
  url: https://developer.salesforce.com/developer-centers/mobile
- title: ''
  type: JSONLD
  url: json-ld/salesforce-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/salesforce-sobject-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/salesforce-query-result-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/salesforce-bulk-job-schema.json
- title: ''
  type: JSONLD
  url: json-ld/salesforce-rest-context.jsonld
- title: ''
  type: JSONLD
  url: json-ld/salesforce-bulk-2-context.jsonld
- title: ''
  type: JSONLD
  url: json-ld/salesforce-ui-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/salesforce-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/salesforce-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/crm-data-management.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/marketing-automation.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/platform-administration.yaml
created: '2025-06-05'
description: Salesforce is a cloud-based customer relationship management (CRM) platform that provides a comprehensive suite of enterprise applications for sales, service, marketing, and more.
features:
- description: Unified sales, service, marketing, and commerce applications accessible from a single cloud platform.
  name: Multi-Cloud CRM Platform
- description: Comprehensive REST and SOAP APIs for programmatic access to all Salesforce data and metadata.
  name: REST And SOAP APIs
- description: Asynchronous bulk API for loading and querying millions of records in CSV format.
  name: Bulk Data Processing
- description: Pub/Sub and Streaming APIs for near-real-time event-driven integrations using platform events and change data capture.
  name: Real-Time Event Streaming
- description: Agentforce and Einstein APIs for building AI agents, predictions, and generative AI experiences.
  name: AI-Powered Agents
- description: Modern GraphQL interface for efficient, client-driven queries against Salesforce data.
  name: GraphQL API
- description: Programmatic access to journeys, contacts, data extensions, and transactional messaging.
  name: Marketing Cloud Automation
- description: B2B and B2C commerce APIs for storefronts, product catalogs, carts, and orders.
  name: Commerce APIs
- description: Build custom REST endpoints using Apex classes with full platform integration.
  name: Custom Apex Endpoints
- description: Combine multiple API requests into a single call with dependent reference IDs for performance.
  name: Composite And Batch Requests
image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg
integrations:
- description: Native integration platform for connecting Salesforce with any application, data source, or API.
  name: MuleSoft Anypoint
- description: Advanced analytics and data visualization through the Tableau REST API and Salesforce data connectors.
  name: Tableau
- description: Embed Salesforce data and workflows into Slack channels for team collaboration.
  name: Slack
- description: Deploy custom applications on Heroku with direct Salesforce data synchronization via Heroku Connect.
  name: Heroku
- description: AWS integrations for Service Cloud Voice with Amazon Connect and Data Cloud event bridges.
  name: Amazon Web Services
- description: BigQuery connectors and Google Workspace integrations for analytics and productivity.
  name: Google Cloud
- description: Outlook and Teams integrations for email tracking, calendar sync, and collaborative selling.
  name: Microsoft
- description: Thousands of pre-built integrations and applications available through the Salesforce AppExchange marketplace.
  name: AppExchange Partners
jsonld:
- class_count: 0
  name: Salesforce Bulk 2 Context
  property_count: 5
  slug: salesforce-bulk-2-context
- class_count: 0
  name: Salesforce Context
  property_count: 1770
  slug: salesforce-context
- class_count: 0
  name: Salesforce Rest Context
  property_count: 8
  slug: salesforce-rest-context
- class_count: 0
  name: Salesforce Ui Context
  property_count: 12
  slug: salesforce-ui-context
layout: provider
modified: '2026-04-18'
name: Salesforce
rules:
- name: Salesforce API Rules
  rule_count: 21
  severity_counts:
    error: 19
    hint: 0
    info: 1
    warn: 1
  slug: salesforce-spectral-rules
skills: []
slug: salesforce
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: salesforce\nurl: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/apis.yml\napis:\n  - aid: salesforce:salesforce-rest-api\n    name: Salesforce REST API\n    tags:\n      - CRM\n      - Objects\n      - Records\n      - REST\n      - SOQL\n      - SOSL\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/\n    baseURL: https://{instance}.salesforce.com/services/data\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/quickstart.htm\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/dome_versions.htm\n        type: APIReference\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_understanding_authentication.htm\n\
  \        type: Authentication\n      - url: openapi/salesforce-openapi.yml\n        type: OpenAPI\n      - url: openapi/salesforce-rest-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/salesforce-sobject-schema.json\n        type: JSONSchema\n      - url: json-schema/salesforce-query-result-schema.json\n        type: JSONSchema\n    description: The Salesforce REST API provides a simple and powerful web service interface to interact with Salesforce org data. It supports creating, reading, updating, deleting, and querying records using SOQL and SOSL, and is the primary API for building connected applications against Salesforce.\n  - aid: salesforce:salesforce-soap-api\n    name: Salesforce SOAP API\n    tags:\n      - CRM\n      - Enterprise\n      - Objects\n      - Records\n      - SOAP\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/\n    baseURL: https://{instance}.salesforce.com/services/Soap\n\
  \    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_quickstart_intro.htm\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_calls_list.htm\n        type: APIReference\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_concepts_security.htm\n        type: Authentication\n    description: The Salesforce SOAP API enables developers to use SOAP calls to create, retrieve, update, and delete records such as accounts, leads, and custom objects. It provides robust enterprise-grade integration capabilities and supports batch processing of records.\n  - aid: salesforce:salesforce-bulk-api\n    name: Salesforce Bulk API\n    tags:\n      - Bulk\n      - CRM\n      - Data Loading\n      - ETL\n      - Records\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n\
  \    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/\n    baseURL: https://{instance}.salesforce.com/services/async\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/asynch_api_quickstart.htm\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/asynch_api_reference.htm\n        type: APIReference\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/asynch_api_concepts_security.htm\n        type: Authentication\n    description: The Salesforce Bulk API is a specialized REST-based interface that enables asynchronous processing of large numbers of records. It is optimized for loading or deleting large sets of data and supports CSV, XML, and JSON formats.\n  - aid: salesforce:salesforce-bulk-api-2\n\
  \    name: Salesforce Bulk API 2.0\n    tags:\n      - Bulk\n      - CRM\n      - Data Loading\n      - ETL\n      - Records\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/\n    baseURL: https://{instance}.salesforce.com/services/data/v{version}/jobs\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/get_job_info.htm\n        type: APIReference\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/bulk_api_2_0_security.htm\n        type: Authentication\n      - url: openapi/salesforce-bulk-api-2-openapi.yml\n        type: OpenAPI\n      - url: json-schema/salesforce-bulk-job-schema.json\n        type: JSONSchema\n    description: Salesforce\
  \ Bulk API 2.0 is a simplified, REST-based interface for bulk data operations that improves on the original Bulk API. It uses a straightforward job model and supports CSV format for ingest and query jobs processing millions of records.\n  - aid: salesforce:salesforce-streaming-api\n    name: Salesforce Streaming API\n    tags:\n      - CRM\n      - Events\n      - Push Notifications\n      - Real-Time\n      - Streaming\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/\n    baseURL: https://{instance}.salesforce.com/cometd\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/intro_stream.htm\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/resources_top.htm\n\
  \        type: APIReference\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/using_streaming_api_auth.htm\n        type: Authentication\n      - url: asyncapi/salesforce-streaming-asyncapi.yml\n        type: AsyncAPI\n    description: The Salesforce Streaming API uses a publish-subscribe model based on Bayeux/CometD to push near-real-time event notifications to subscribed clients. It supports PushTopic events for record changes and Generic Streaming events for custom notifications.\n  - aid: salesforce:salesforce-metadata-api\n    name: Salesforce Metadata API\n    tags:\n      - Configuration\n      - CRM\n      - Deployment\n      - DevOps\n      - Metadata\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/\n    baseURL: https://{instance}.salesforce.com/services/Soap/m\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/\n\
  \        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_quickstart.htm\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_types_list.htm\n        type: APIReference\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_auth.htm\n        type: Authentication\n    description: The Salesforce Metadata API is a SOAP-based API that enables developers to retrieve, deploy, create, update, and delete customizations for Salesforce organizations. It is the foundation for tools like Salesforce CLI, Ant Migration Tool, and CI/CD pipelines.\n  - aid: salesforce:salesforce-tooling-api\n    name: Salesforce Tooling API\n    tags:\n      - Apex\n      - CRM\n      - Development\n      - IDE\n      - Tooling\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/\n\
  \    baseURL: https://{instance}.salesforce.com/services/data/v{version}/tooling\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/tooling_api_objects_list.htm\n        type: APIReference\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/intro_rest_resources.htm\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/intro_rest_overview.htm\n        type: Authentication\n    description: The Salesforce Tooling API provides SOAP and REST interfaces for building developer tools for Force.com applications. It exposes fine-grained access to Apex code, Visualforce pages, and other metadata for IDE integration, code coverage, and debugging workflows.\n  - aid: salesforce:salesforce-connect-api\n    name:\
  \ Salesforce Connect API (Chatter)\n    tags:\n      - Chatter\n      - Collaboration\n      - Connect\n      - CRM\n      - Feed\n      - Social\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/\n    baseURL: https://{instance}.salesforce.com/services/data/v{version}/chatter\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/quickstart.htm\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_list.htm\n        type: APIReference\n      - url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/authentication.htm\n        type: Authentication\n    description: The Salesforce\
  \ Connect REST API (formerly Chatter API) provides access to Salesforce Chatter feeds, groups, users, topics, and file sharing features. It also exposes Experience Cloud (community) data and supports building custom social and collaboration experiences.\n  - aid: salesforce:salesforce-analytics-rest-api\n    name: Salesforce Analytics REST API\n    tags:\n      - Analytics\n      - CRM\n      - CRM Analytics\n      - Dashboards\n      - Reports\n      - Tableau CRM\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/\n    baseURL: https://{instance}.salesforce.com/services/data/v{version}/wave\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/bi_rest_overview.htm\n\
  \        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/bi_rest_resources_list.htm\n        type: APIReference\n    description: The Salesforce Analytics REST API (also known as CRM Analytics or Wave API) provides programmatic access to CRM Analytics datasets, lenses, dashboards, and queries. Developers can read and write analytics assets and run SAQL queries against analytics datasets.\n  - aid: salesforce:salesforce-reports-and-dashboards-rest-api\n    name: Salesforce Reports and Dashboards REST API\n    tags:\n      - Analytics\n      - CRM\n      - Dashboards\n      - Reports\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/\n    baseURL: https://{instance}.salesforce.com/services/data/v{version}/analytics\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/\n\
  \        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/sforce_analytics_rest_api_getstarted.htm\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/sforce_analytics_rest_api_resource_index.htm\n        type: APIReference\n    description: The Salesforce Reports and Dashboards REST API enables developers to programmatically access report results, list reports and dashboards, and run and filter reports. It supports accessing standard and custom Salesforce reports without the need to navigate the UI.\n  - aid: salesforce:salesforce-einstein-platform-services-api\n    name: Salesforce Einstein Platform Services API\n    tags:\n      - AI\n      - Computer Vision\n      - Einstein\n      - Machine Learning\n      - Natural Language Processing\n      - Prediction\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n\
  \    humanURL: https://metamind.readme.io/\n    baseURL: https://api.einstein.ai/v2\n    properties:\n      - url: https://metamind.readme.io/\n        type: Documentation\n      - url: https://metamind.readme.io/docs/getting-started\n        type: GettingStarted\n      - url: https://metamind.readme.io/reference\n        type: APIReference\n      - url: https://metamind.readme.io/docs/authentication\n        type: Authentication\n      - url: https://trailhead.salesforce.com/en/content/learn/modules/einstein_platform_services\n        type: GettingStarted\n    description: The Salesforce Einstein Platform Services API provides REST-based access to Salesforce AI capabilities including image classification, object detection, and sentiment analysis. Developers can train custom models or use pre-built models for vision and natural language processing tasks.\n  - aid: salesforce:salesforce-einstein-prediction-service-api\n    name: Salesforce Einstein Prediction Service API\n    tags:\n  \
  \    - AI\n      - CRM\n      - Einstein\n      - Machine Learning\n      - Prediction\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.einstein_platform_services.meta/einstein_platform_services/\n    baseURL: https://{instance}.salesforce.com/services/data/v{version}/einstein\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.einstein_platform_services.meta/einstein_platform_services/\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.einstein_platform_services.meta/einstein_platform_services/einstein_platform_intro.htm\n        type: GettingStarted\n    description: The Salesforce Einstein Prediction Service API enables programmatic access to Einstein Analytics predictions and forecasts built on CRM data. It allows applications to retrieve AI-driven predictions for leads, opportunities, and custom objects configured\
  \ in Salesforce.\n  - aid: salesforce:salesforce-graphql-api\n    name: Salesforce GraphQL API\n    tags:\n      - CRM\n      - GraphQL\n      - Queries\n      - Records\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/platform/graphql/guide/graphql-about.html\n    baseURL: https://{instance}.salesforce.com/services/data/v{version}/graphql\n    properties:\n      - url: https://developer.salesforce.com/docs/platform/graphql/guide/graphql-about.html\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/platform/graphql/guide/graphql-get-started.html\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/platform/graphql/guide/graphql-reference.html\n        type: APIReference\n      - url: https://developer.salesforce.com/docs/platform/graphql/guide/graphql-auth.html\n        type: Authentication\n    description: The Salesforce GraphQL API\
  \ provides a GraphQL interface to query and mutate Salesforce data. It allows clients to request exactly the data they need in a single request, reducing over-fetching and under-fetching compared to traditional REST calls.\n  - aid: salesforce:salesforce-pub-sub-api\n    name: Salesforce Pub/Sub API\n    tags:\n      - CRM\n      - Events\n      - gRPC\n      - Platform Events\n      - Pub/Sub\n      - Real-Time\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-intro.html\n    baseURL: https://api.pubsub.salesforce.com\n    properties:\n      - url: https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-intro.html\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-get-started.html\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/platform/pub-sub-api/references/pubsub-api-reference.html\n\
  \        type: APIReference\n      - url: https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-auth.html\n        type: Authentication\n      - url: https://github.com/developerforce/pub-sub-api\n        type: GitHubRepository\n    description: The Salesforce Pub/Sub API is a gRPC-based API for publishing and subscribing to platform events, change data capture events, and other event types in real time. It supersedes the CometD-based Streaming API for high-throughput event-driven integrations.\n  - aid: salesforce:salesforce-platform-events-api\n    name: Salesforce Platform Events API\n    tags:\n      - CRM\n      - Event-Driven\n      - Events\n      - Integration\n      - Platform Events\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/\n    baseURL: https://{instance}.salesforce.com/services/data/v{version}/sobjects\n\
  \    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/platform_events_intro.htm\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/platform_events_subscribe_api.htm\n        type: APIReference\n      - url: asyncapi/salesforce-platform-events-asyncapi.yml\n        type: AsyncAPI\n    description: Salesforce Platform Events enables event-driven integration architectures built on the Salesforce platform. Developers define custom event types as Salesforce objects and publish or subscribe to events using the REST API, Apex, or Salesforce Flows.\n  - aid: salesforce:salesforce-change-data-capture-api\n    name: Salesforce Change Data Capture API\n    tags:\n      - CDC\n      - Change Data Capture\n      - CRM\n      - Events\n\
  \      - Integration\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/\n    baseURL: https://{instance}.salesforce.com/cometd\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/cdc_intro.htm\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/cdc_subscribe_api.htm\n        type: APIReference\n      - url: asyncapi/salesforce-change-data-capture-asyncapi.yml\n        type: AsyncAPI\n    description: Salesforce Change Data Capture delivers change events that represent changes to Salesforce records including creates, updates, deletes, and undeletes.\
  \ It enables external systems to receive near-real-time changes to Salesforce data for data replication and synchronization use cases.\n  - aid: salesforce:salesforce-ui-api\n    name: Salesforce UI API\n    tags:\n      - Components\n      - CRM\n      - Lightning\n      - UI\n      - User Interface\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/\n    baseURL: https://{instance}.salesforce.com/services/data/v{version}/ui-api\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_get_started.htm\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_resources_list.htm\n        type: APIReference\n      - url: openapi/salesforce-ui-api-openapi.yml\n\
  \        type: OpenAPI\n    description: The Salesforce UI API provides a comprehensive REST interface for building UIs that work with Salesforce metadata and data. It returns layout information, picklist values, list views, record data, and object metadata that Lightning components rely on.\n  - aid: salesforce:salesforce-composite-api\n    name: Salesforce Composite API\n    tags:\n      - Batch\n      - Composite\n      - CRM\n      - Performance\n      - REST\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite.htm\n    baseURL: https://{instance}.salesforce.com/services/data/v{version}/composite\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite.htm\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite_intro.htm\n\
  \        type: APIReference\n    description: The Salesforce Composite API allows developers to combine multiple Salesforce REST API requests into a single HTTP call. It reduces the number of round trips to the server and supports dependent requests using reference IDs, improving integration performance.\n  - aid: salesforce:salesforce-apex-rest-api\n    name: Salesforce Apex REST API\n    tags:\n      - Apex\n      - CRM\n      - Custom APIs\n      - Development\n      - REST\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest.htm\n    baseURL: https://{instance}.salesforce.com/services/apexrest\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest.htm\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest_code_sample_intro.htm\n\
  \        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest_methods.htm\n        type: APIReference\n    description: Salesforce Apex REST enables developers to expose custom Apex classes as RESTful web services. By annotating Apex classes and methods with @RestResource and HTTP method annotations, developers can create custom API endpoints that extend Salesforce functionality.\n  - aid: salesforce:salesforce-data-cloud-api\n    name: Salesforce Data Cloud API\n    tags:\n      - CDP\n      - CRM\n      - Customer Data Platform\n      - Data Cloud\n      - Identity Resolution\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/platform/data-cloud-api/overview\n    baseURL: https://{instance}.salesforce.com/api/v1\n    properties:\n      - url: https://developer.salesforce.com/docs/platform/data-cloud-api/overview\n        type: Documentation\n\
  \      - url: https://developer.salesforce.com/docs/platform/data-cloud-api/guide/dc-api-getting-started.html\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/platform/data-cloud-api/references/data-cloud-api.html\n        type: APIReference\n      - url: https://developer.salesforce.com/docs/platform/data-cloud-api/guide/dc-api-auth.html\n        type: Authentication\n    description: The Salesforce Data Cloud API provides programmatic access to Data Cloud (formerly Customer Data Platform) for ingesting, querying, and managing unified customer profiles. It enables applications to read and write segments, calculated insights, and identity-resolved profile data.\n  - aid: salesforce:salesforce-marketing-cloud-rest-api\n    name: Salesforce Marketing Cloud REST API\n    tags:\n      - Email\n      - Journeys\n      - Marketing Automation\n      - Marketing Cloud\n      - REST\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n\
  \    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rest-api.html\n    baseURL: https://{subdomain}.rest.marketingcloudapis.com\n    properties:\n      - url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rest-api.html\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/get-started-spec.html\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/marketing/marketing-cloud/references/mc_rest_overview.html\n        type: APIReference\n      - url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/access-token-s2s.html\n        type: Authentication\n      - url: openapi/salesforce-marketing-cloud-rest-openapi.yml\n        type: OpenAPI\n    description: The Salesforce Marketing Cloud REST API provides access to Marketing Cloud resources including contacts, journeys, data extensions, triggered sends, and transactional messaging.\
  \ It uses OAuth 2.0 for authentication and is the primary interface for programmatic Marketing Cloud integrations.\n  - aid: salesforce:salesforce-marketing-cloud-soap-api\n    name: Salesforce Marketing Cloud SOAP API\n    tags:\n      - Email\n      - Marketing Automation\n      - Marketing Cloud\n      - SOAP\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/soap-api.html\n    baseURL: https://{subdomain}.soap.marketingcloudapis.com\n    properties:\n      - url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/soap-api.html\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/getting-started-with-mc-sdk.html\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/marketing/marketing-cloud/references/mc_soap_objects.html\n        type: APIReference\n   \
  \ description: The Salesforce Marketing Cloud SOAP API is a full-featured SOAP web service interface for Marketing Cloud that supports subscriber management, email send operations, automation activities, and data extension management.\n  - aid: salesforce:salesforce-pardot-api\n    name: Salesforce Pardot API (Account Engagement)\n    tags:\n      - Account Engagement\n      - B2B Marketing\n      - Lead Generation\n      - Marketing\n      - Pardot\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/marketing/pardot/guide/overview.html\n    baseURL: https://pi.pardot.com/api\n    properties:\n      - url: https://developer.salesforce.com/docs/marketing/pardot/guide/overview.html\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/marketing/pardot/guide/getting-started.html\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/marketing/pardot/references/pardot-api-overview.html\n\
  \        type: APIReference\n      - url: https://developer.salesforce.com/docs/marketing/pardot/guide/authentication.html\n        type: Authentication\n    description: The Salesforce Pardot API (now called Account Engagement API) provides programmatic access to Pardot marketing automation data including prospects, campaigns, forms, lists, and email statistics for B2B marketing use cases.\n  - aid: salesforce:salesforce-commerce-cloud-ocapi\n    name: Salesforce Commerce Cloud OCAPI\n    tags:\n      - B2C Commerce\n      - Commerce\n      - OCAPI\n      - Orders\n      - Storefront\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/OCAPI.html\n    baseURL: https://{instance}.dx.commercecloud.salesforce.com\n    properties:\n      - url: https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/OCAPI.html\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/ocapi-get-started.html\n\
  \        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/commerce/b2c-commerce/references/b2c-commerce-api.html\n        type: APIReference\n      - url: https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/auth-overview.html\n        type: Authentication\n    description: The Salesforce Commerce Cloud Open Commerce API (OCAPI) provides a REST interface for accessing Salesforce B2C Commerce data and functionality including products, catalogs, orders, promotions, and customer accounts for storefronts and back-office integrations.\n  - aid: salesforce:salesforce-commerce-cloud-shopper-apis\n    name: Salesforce Commerce Cloud Shopper APIs (SCAPI)\n    tags:\n      - B2C Commerce\n      - Commerce\n      - Orders\n      - Products\n      - Shopper\n      - Storefront\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/web-api.html\n\
  \    baseURL: https://{shortCode}.api.commercecloud.salesforce.com\n    properties:\n      - url: https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/web-api.html\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/build-your-first-commerce-app.html\n        type: GettingStarted\n      - url: https://developer.salesforce.com/docs/commerce/salesforce-commerce/references/shopper-products.html\n        type: APIReference\n      - url: https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/slas.html\n        type: Authentication\n    description: The Salesforce Commerce Cloud Shopper APIs (SCAPI) are a modern set of REST APIs for building B2C Commerce storefronts and headless commerce experiences. They cover shopper authentication, products, search, baskets, orders, and customer account management.\n  - aid: salesforce:salesforce-field-service-api\n    name: Salesforce Field Service API\n\
  \    tags:\n      - Field Service\n      - Mobile\n      - Scheduling\n      - Service Cloud\n      - Work Orders\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.field_service_dev.meta/field_service_dev/\n    baseURL: https://{instance}.salesforce.com/services/data/v{version}\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.field_service_dev.meta/field_service_dev/\n        type: Documentation\n      - url: https://developer.salesforce.com/docs/atlas.en-us.field_service_dev.meta/field_service_dev/fsl_developer_guide_intro.htm\n        type: GettingStarted\n    description: The Salesforce Field Service API provides access to Field Service Lightning data and operations including work orders, service appointments, resource scheduling, and mobile workforce management. It enables custom integrations with scheduling systems and field service tools.\n  -\
  \ aid: salesforce:salesforce-health-cloud-api\n    name: Salesforce Health Cloud API\n    tags:\n      - Clinical\n      - FHIR\n      - Health Cloud\n      - Healthcare\n      - Patients\n    image: https://www.salesforce.com/content/dam/sfdc-docs/www/logos/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.health_cloud_object_reference.meta/health_cloud_object_reference/\n    baseURL: https://{instance}.salesforce.com/services/data/v{version}\n    properties:\n      - url: https://developer.salesforce.com/docs/atlas.en-us.health_cloud_object_reference.meta\n\n# --- truncated at 32 KB (60 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/apis.yml
tags:
- AI
- Analytics
- Cloud
- Commerce
- CRM
- Customer Service
- Enterprise
- Marketing
- Platform
- Sales
url: https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/apis.yml
use_cases:
- description: Synchronize customer, lead, and opportunity data between Salesforce and external systems.
  name: CRM Data Integration
- description: Load and extract large volumes of records for data warehouse synchronization and ETL workflows.
  name: Bulk Data Migration
- description: Build reactive integrations using platform events and change data capture for real-time data replication.
  name: Event-Driven Architecture
- description: Automate multi-channel marketing journeys and manage subscriber engagement via Marketing Cloud APIs.
  name: Marketing Campaign Orchestration
- description: Deploy Einstein predictions and Agentforce agents for intelligent lead scoring and customer service automation.
  name: AI-Powered Customer Insights
- description: Build Lightning Web Components and custom Apex REST APIs to extend the Salesforce platform.
  name: Custom Application Development
- description: Power headless commerce experiences with shopper APIs for products, baskets, and orders.
  name: Commerce Storefront Integration
- description: Automate metadata deployments and manage org configurations using Metadata and Tooling APIs.
  name: DevOps And CI/CD Automation
---
