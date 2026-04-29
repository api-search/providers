---
api_count: 6
apis:
- description: 'The Adobe Analytics 2.0 API provides programmatic access to Adobe Analytics reporting, management, and configuration capabilities. It enables developers to retrieve report data, manage report suites, '
  name: Adobe Analytics 2.0 API
  slug: analytics-api
- description: The Adobe Experience Platform API provides RESTful access to core platform services including data ingestion, unified profile management, identity resolution, dataset management, schema registry, quer
  name: Adobe Experience Platform API
  slug: experience-platform-api
- description: The Adobe Target API provides programmatic access to Adobe Target for managing A/B tests, experience targeting, multivariate tests, automated personalization activities, audiences, offers, and real-ti
  name: Adobe Target API
  slug: target-api
- description: The Adobe Journey Optimizer API enables programmatic management of customer journeys, campaigns, messages, offers, placements, and content templates across email, push, SMS, and in-app channels for or
  name: Adobe Journey Optimizer API
  slug: journey-optimizer-api
- description: The Adobe Campaign API provides RESTful access to Adobe Campaign for managing subscriber profiles, subscription services, marketing workflows, email deliveries, and real-time transactional messaging a
  name: Adobe Campaign API
  slug: campaign-api
- description: Adobe I/O Events enables developers to receive near-real-time notifications from Adobe services via webhooks and journal polling. Events are emitted when significant changes occur across Adobe Experie
  name: Adobe I/O Events
  slug: io-events
asyncapis:
- description: Adobe I/O Events enables developers to receive near-real-time notifications from Adobe services via webhooks and journal polling. Events are emitted when significant changes occur across Adobe Experie
  name: Adobe I/O Events
  slug: adobe-io-events-asyncapi
capabilities:
- description: Unified workflow for managing real-time customer profiles, audience segmentation, and data ingestion using Adobe Experience Platform. Designed for data engineers and customer data platform administrat
  name: Adobe Experience Cloud Customer Data Platform
  slug: customer-data-platform
- description: 'Unified workflow capability combining Adobe Analytics, Adobe Target, and Adobe Journey Optimizer for data-driven marketing campaigns, A/B testing, and personalized journey orchestration. Designed for '
  name: Adobe Experience Cloud Digital Marketing
  slug: digital-marketing
common:
- title: ''
  type: Portal
  url: https://developer.adobe.com/
- title: ''
  type: Documentation
  url: https://developer.adobe.com/developer-console/docs/guides/
- title: ''
  type: Documentation
  url: https://developer.adobe.com/apis/
- title: ''
  type: Blog
  url: https://blog.developer.adobe.com/
- title: ''
  type: Support
  url: https://experienceleague.adobe.com/
- title: ''
  type: TermsOfService
  url: https://www.adobe.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.adobe.com/privacy.html
- title: ''
  type: StatusPage
  url: https://status.adobe.com/
- title: ''
  type: Console
  url: https://developer.adobe.com/console/
- title: ''
  type: SignUp
  url: https://developer.adobe.com/
- title: ''
  type: GettingStarted
  url: https://developer.adobe.com/developer-console/docs/guides/getting-started/
- title: ''
  type: GitHubOrganization
  url: https://github.com/adobe
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AdobeDeveloperTV
- title: ''
  type: ChangeLog
  url: https://developer.adobe.com/events/docs/whats_new/
- title: ''
  type: SpectralRules
  url: rules/adobe-experience-cloud-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/customer-data-platform.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/digital-marketing.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/adobe-experience-cloud-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/adobe-experience-cloud-analytics-api-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/adobe-experience-cloud-campaign-api-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/adobe-experience-cloud-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/adobe-experience-cloud-experience-platform-api-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/adobe-experience-cloud-io-events-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/adobe-experience-cloud-journey-optimizer-api-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/adobe-experience-cloud-target-api-context.jsonld
created: '2025-01-01'
description: Adobe Experience Cloud is an integrated suite of applications and services for digital marketing, analytics, advertising, and commerce. It provides tools for content management, personalization, customer journey orchestration, audience segmentation, real-time customer data platforms, offer decisioning, and cross-channel campaign execution, enabling organizations to deliver personalized customer experiences at scale.
features:
- description: Build and query unified customer profiles from multiple data sources using the Experience Platform APIs.
  name: Real-Time Customer Profiles
- description: Retrieve dimensional reports, calculated metrics, and segment data from Adobe Analytics via REST API.
  name: Analytics Reporting
- description: Create, manage, and retrieve results for A/B tests and automated personalization activities via Adobe Target API.
  name: A/B and Multivariate Testing
- description: Orchestrate email, SMS, push, and in-app campaigns programmatically using Adobe Campaign and Journey Optimizer APIs.
  name: Multi-Channel Campaign Execution
- description: Subscribe to near-real-time events from all Adobe Experience Cloud products via Adobe I/O Events.
  name: Webhook Event Streaming
- description: Manage offers, placements, and decisioning rules for personalized content delivery using Journey Optimizer APIs.
  name: Offer Decisioning
- description: Ingest batch and streaming data and register schemas using Experience Platform APIs.
  name: Data Ingestion and Schema Registry
- description: Resolve customer identities across devices and channels using Experience Platform Identity Service API.
  name: Identity Resolution
- description: Create and evaluate audience segments using Experience Platform Segmentation Service API.
  name: Audience Segmentation
- description: Secure all APIs using OAuth 2.0 server-to-server credentials via Adobe Developer Console.
  name: OAuth 2.0 and JWT Authentication
image: /assets/icons/adobe-experience-cloud.png
integrations:
- description: Sync customer data and campaign results between Adobe Experience Cloud and Salesforce CRM.
  name: Salesforce
- description: Ingest data from Azure Data Lake and Blob Storage into Adobe Experience Platform.
  name: Microsoft Azure
- description: Connect Google BigQuery datasets to Adobe Experience Platform for data ingestion and activation.
  name: Google BigQuery
- description: Integrate Workfront project management with Adobe Experience Cloud for content workflow automation.
  name: Workfront
- description: Sync lead data and campaign activities between Marketo Engage and Adobe Experience Cloud.
  name: Marketo Engage
- description: Connect ServiceNow customer data with Adobe Experience Cloud for unified customer service experiences.
  name: ServiceNow
- description: Connect Snowflake data warehouse to Experience Platform for federated audience composition.
  name: Snowflake
jsonld:
- class_count: 18
  name: Adobe Experience Cloud Analytics Api Context
  property_count: 34
  slug: adobe-experience-cloud-analytics-api-context
- class_count: 14
  name: Adobe Experience Cloud Campaign Api Context
  property_count: 20
  slug: adobe-experience-cloud-campaign-api-context
- class_count: 7
  name: Adobe Experience Cloud Context
  property_count: 11
  slug: adobe-experience-cloud-context
- class_count: 20
  name: Adobe Experience Cloud Experience Platform Api Context
  property_count: 37
  slug: adobe-experience-cloud-experience-platform-api-context
- class_count: 10
  name: Adobe Experience Cloud Io Events Context
  property_count: 122
  slug: adobe-experience-cloud-io-events-context
- class_count: 27
  name: Adobe Experience Cloud Journey Optimizer Api Context
  property_count: 28
  slug: adobe-experience-cloud-journey-optimizer-api-context
- class_count: 15
  name: Adobe Experience Cloud Target Api Context
  property_count: 28
  slug: adobe-experience-cloud-target-api-context
layout: provider
modified: '2026-04-19'
name: Adobe Experience Cloud
rules:
- name: Adobe Experience Cloud API Rules
  rule_count: 31
  severity_counts:
    error: 16
    hint: 0
    info: 2
    warn: 13
  slug: adobe-experience-cloud-spectral-rules
skills: []
slug: adobe-experience-cloud
solutions: []
source_yaml: "aid: adobe-experience-cloud\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/apis.yml\napis:\n- aid: adobe-experience-cloud:analytics-api\n  name: Adobe Analytics 2.0 API\n  tags:\n  - Analytics\n  - Digital Marketing\n  - Reporting\n  humanURL: https://developer.adobe.com/analytics-apis/docs/2.0/\n  properties:\n  - url: https://developer.adobe.com/analytics-apis/docs/2.0/\n    type: Documentation\n  - url: openapi/adobe-analytics-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Adobe Analytics 2.0 API provides programmatic access to Adobe\n    Analytics reporting, management, and configuration capabilities. It\n    enables developers to retrieve report data, manage report suites,\n    configure calculated metrics, segments, and dimensions, and administer\n    users and permissions within Adobe Analytics.\n- aid: adobe-experience-cloud:experience-platform-api\n  name: Adobe Experience Platform API\n  tags:\n\
  \  - Customer Profiles\n  - Data Management\n  - Platform\n  humanURL: https://developer.adobe.com/experience-platform-apis/\n  properties:\n  - url: https://developer.adobe.com/experience-platform-apis/\n    type: Documentation\n  - url: openapi/adobe-experience-platform-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Adobe Experience Platform API provides RESTful access to core\n    platform services including data ingestion, unified profile management,\n    identity resolution, dataset management, schema registry, query service,\n    and segmentation for building real-time customer profiles and orchestrating\n    data workflows.\n- aid: adobe-experience-cloud:target-api\n  name: Adobe Target API\n  tags:\n  - Optimization\n  - Personalization\n  - Testing\n  humanURL: https://developer.adobe.com/target/\n  properties:\n  - url: https://developer.adobe.com/target/\n    type: Documentation\n  - url: openapi/adobe-target-api-openapi.yml\n    type: OpenAPI\n  description:\
  \ >-\n    The Adobe Target API provides programmatic access to Adobe Target for\n    managing A/B tests, experience targeting, multivariate tests, automated\n    personalization activities, audiences, offers, and real-time content\n    delivery for website and application personalization.\n- aid: adobe-experience-cloud:journey-optimizer-api\n  name: Adobe Journey Optimizer API\n  tags:\n  - Journey Orchestration\n  - Messaging\n  - Offer Decisioning\n  humanURL: https://developer.adobe.com/journey-optimizer-apis/\n  properties:\n  - url: https://developer.adobe.com/journey-optimizer-apis/\n    type: Documentation\n  - url: openapi/adobe-journey-optimizer-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Adobe Journey Optimizer API enables programmatic management of\n    customer journeys, campaigns, messages, offers, placements, and content\n    templates across email, push, SMS, and in-app channels for orchestrating\n    personalized multi-channel customer experiences.\n\
  - aid: adobe-experience-cloud:campaign-api\n  name: Adobe Campaign API\n  tags:\n  - Campaign Management\n  - Email Marketing\n  - Transactional Messaging\n  humanURL: https://developer.adobe.com/campaign-standard-apis/\n  properties:\n  - url: https://developer.adobe.com/campaign-standard-apis/\n    type: Documentation\n  - url: openapi/adobe-campaign-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Adobe Campaign API provides RESTful access to Adobe Campaign for\n    managing subscriber profiles, subscription services, marketing workflows,\n    email deliveries, and real-time transactional messaging across email,\n    SMS, and push notification channels.\n- aid: adobe-experience-cloud:io-events\n  name: Adobe I/O Events\n  tags:\n  - Events\n  - Integration\n  - Webhooks\n  humanURL: https://developer.adobe.com/events/docs/\n  properties:\n  - url: https://developer.adobe.com/events/docs/\n    type: Documentation\n  - url: asyncapi/adobe-io-events-asyncapi.yml\n    type:\
  \ AsyncAPI\n  description: >-\n    Adobe I/O Events enables developers to receive near-real-time\n    notifications from Adobe services via webhooks and journal polling.\n    Events are emitted when significant changes occur across Adobe Experience\n    Cloud products for building reactive integrations and automated workflows.\nname: Adobe Experience Cloud\ntags:\n- Analytics\n- Customer Experience\n- Digital Marketing\n- Personalization\n- Campaign Management\n- Journey Orchestration\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n- url: https://developer.adobe.com/\n  type: Portal\n- url: https://developer.adobe.com/developer-console/docs/guides/\n  type: Documentation\n- url: https://developer.adobe.com/apis/\n  type: Documentation\n- url: https://blog.developer.adobe.com/\n  type: Blog\n- url: https://experienceleague.adobe.com/\n  type: Support\n- type: TermsOfService\n  url: https://www.adobe.com/legal/terms.html\n\
  - type: PrivacyPolicy\n  url: https://www.adobe.com/privacy.html\n- type: StatusPage\n  url: https://status.adobe.com/\n- type: Console\n  url: https://developer.adobe.com/console/\n- type: SignUp\n  url: https://developer.adobe.com/\n- type: GettingStarted\n  url: https://developer.adobe.com/developer-console/docs/guides/getting-started/\n- type: GitHubOrganization\n  url: https://github.com/adobe\n- type: YouTube\n  url: https://www.youtube.com/user/AdobeDeveloperTV\n- type: ChangeLog\n  url: https://developer.adobe.com/events/docs/whats_new/\n- type: Features\n  data:\n  - name: Real-Time Customer Profiles\n    description: Build and query unified customer profiles from multiple data sources using the Experience Platform APIs.\n  - name: Analytics Reporting\n    description: Retrieve dimensional reports, calculated metrics, and segment data from Adobe Analytics via REST API.\n  - name: A/B and Multivariate Testing\n    description: Create, manage, and retrieve results for A/B tests\
  \ and automated personalization activities via Adobe Target API.\n  - name: Multi-Channel Campaign Execution\n    description: Orchestrate email, SMS, push, and in-app campaigns programmatically using Adobe Campaign and Journey Optimizer APIs.\n  - name: Webhook Event Streaming\n    description: Subscribe to near-real-time events from all Adobe Experience Cloud products via Adobe I/O Events.\n  - name: Offer Decisioning\n    description: Manage offers, placements, and decisioning rules for personalized content delivery using Journey Optimizer APIs.\n  - name: Data Ingestion and Schema Registry\n    description: Ingest batch and streaming data and register schemas using Experience Platform APIs.\n  - name: Identity Resolution\n    description: Resolve customer identities across devices and channels using Experience Platform Identity Service API.\n  - name: Audience Segmentation\n    description: Create and evaluate audience segments using Experience Platform Segmentation Service API.\n\
  \  - name: OAuth 2.0 and JWT Authentication\n    description: Secure all APIs using OAuth 2.0 server-to-server credentials via Adobe Developer Console.\n- type: UseCases\n  data:\n  - name: Customer Data Platform\n    description: Ingest data from multiple sources, resolve identities, and activate unified customer profiles for personalization.\n  - name: Marketing Automation\n    description: Automate campaign creation, scheduling, and execution across email, SMS, and push channels using Campaign and Journey Optimizer APIs.\n  - name: Digital Analytics Reporting\n    description: Extract Adobe Analytics data into custom dashboards, BI tools, and data warehouses via the Analytics 2.0 API.\n  - name: Real-Time Personalization\n    description: Deliver personalized content and offers in real time using Adobe Target and Journey Optimizer APIs.\n  - name: Event-Driven Workflows\n    description: Build reactive integrations that respond to Experience Cloud events such as profile updates, campaign\
  \ completions, and audience changes.\n  - name: Audience Activation\n    description: Create and activate audiences across paid media, email, and on-site channels using Experience Platform Segmentation API.\n- type: Integrations\n  data:\n  - name: Salesforce\n    description: Sync customer data and campaign results between Adobe Experience Cloud and Salesforce CRM.\n  - name: Microsoft Azure\n    description: Ingest data from Azure Data Lake and Blob Storage into Adobe Experience Platform.\n  - name: Google BigQuery\n    description: Connect Google BigQuery datasets to Adobe Experience Platform for data ingestion and activation.\n  - name: Workfront\n    description: Integrate Workfront project management with Adobe Experience Cloud for content workflow automation.\n  - name: Marketo Engage\n    description: Sync lead data and campaign activities between Marketo Engage and Adobe Experience Cloud.\n  - name: ServiceNow\n    description: Connect ServiceNow customer data with Adobe Experience\
  \ Cloud for unified customer service experiences.\n  - name: Snowflake\n    description: Connect Snowflake data warehouse to Experience Platform for federated audience composition.\n- type: SpectralRules\n  url: rules/adobe-experience-cloud-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/customer-data-platform.yaml\n- type: NaftikoCapability\n  url: capabilities/digital-marketing.yaml\n- type: Vocabulary\n  url: vocabulary/adobe-experience-cloud-vocabulary.yaml\n- type: JSON-LD\n  url: json-ld/adobe-experience-cloud-analytics-api-context.jsonld\n- type: JSON-LD\n  url: json-ld/adobe-experience-cloud-campaign-api-context.jsonld\n- type: JSON-LD\n  url: json-ld/adobe-experience-cloud-context.jsonld\n- type: JSON-LD\n  url: json-ld/adobe-experience-cloud-experience-platform-api-context.jsonld\n- type: JSON-LD\n  url: json-ld/adobe-experience-cloud-io-events-context.jsonld\n- type: JSON-LD\n  url: json-ld/adobe-experience-cloud-journey-optimizer-api-context.jsonld\n- type:\
  \ JSON-LD\n  url: json-ld/adobe-experience-cloud-target-api-context.jsonld\ncreated: '2025-01-01'\nmodified: '2026-04-19'\ndescription: >-\n  Adobe Experience Cloud is an integrated suite of applications and services\n  for digital marketing, analytics, advertising, and commerce. It provides\n  tools for content management, personalization, customer journey\n  orchestration, audience segmentation, real-time customer data platforms,\n  offer decisioning, and cross-channel campaign execution, enabling\n  organizations to deliver personalized customer experiences at scale.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/apis.yml
tags:
- Analytics
- Customer Experience
- Digital Marketing
- Personalization
- Campaign Management
- Journey Orchestration
url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/apis.yml
use_cases:
- description: Ingest data from multiple sources, resolve identities, and activate unified customer profiles for personalization.
  name: Customer Data Platform
- description: Automate campaign creation, scheduling, and execution across email, SMS, and push channels using Campaign and Journey Optimizer APIs.
  name: Marketing Automation
- description: Extract Adobe Analytics data into custom dashboards, BI tools, and data warehouses via the Analytics 2.0 API.
  name: Digital Analytics Reporting
- description: Deliver personalized content and offers in real time using Adobe Target and Journey Optimizer APIs.
  name: Real-Time Personalization
- description: Build reactive integrations that respond to Experience Cloud events such as profile updates, campaign completions, and audience changes.
  name: Event-Driven Workflows
- description: Create and activate audiences across paid media, email, and on-site channels using Experience Platform Segmentation API.
  name: Audience Activation
---
