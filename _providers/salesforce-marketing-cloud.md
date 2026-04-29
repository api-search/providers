---
api_count: 15
api_specs:
- filename: salesforce-marketing-cloud-openapi.yml
  format: yaml
  label: Marketing Cloud REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-marketing-cloud/refs/heads/main/openapi/salesforce-marketing-cloud-openapi.yml
apis:
- description: Core REST API for interacting with Marketing Cloud features including email, SMS, push notifications, and data extensions. REST API uses JSON request and response bodies and resource endpoints to supp
  name: Marketing Cloud REST API
  slug: ''
- description: Legacy SOAP-based API for Marketing Cloud operations, including email sends, subscriber management, and data extension operations.
  name: SOAP API
  slug: ''
- description: Specialized API for sending triggered, transactional messages including order confirmations, password resets, and real-time notifications.
  name: Transactional Messaging API
  slug: ''
- description: API for creating, managing, and automating customer journeys across multiple channels and touchpoints.
  name: Journey Builder API
  slug: ''
- description: API for managing data extensions, which are database tables used to store and segment customer data in Marketing Cloud.
  name: Data Extensions API
  slug: ''
- description: API for creating and managing email send definitions, which define the configuration for sending emails to subscribers.
  name: Email Send Definition API
  slug: ''
- description: API for sending push notifications to mobile devices, managing device registrations, and tracking push message engagement.
  name: Mobile Push API
  slug: ''
- description: API for sending SMS and MMS messages, managing mobile numbers, and handling keyword-based subscriptions.
  name: SMS/MMS API
  slug: ''
- description: API for managing marketing assets including images, documents, content blocks, and templates across Marketing Cloud.
  name: Asset API
  slug: ''
- description: API for leveraging AI-powered product and content recommendations to personalize customer experiences.
  name: Einstein Recommendations API
  slug: ''
- description: REST API for creating and manipulating marketing content in Content Builder, a single cross-channel repository for emails, images, text, content blocks, and other documents.
  name: Content Builder API
  slug: ''
- description: REST API for creating, reading, updating, and deleting contacts in Marketing Cloud.
  name: Contacts API
  slug: ''
- description: API for initiating and managing marketing automations, including file upload, download, decryption, compression, and decompression operations within Automation Studio.
  name: Automation Studio API
  slug: ''
- description: API for managing and performing marketing campaigns within Marketing Cloud.
  name: Campaign API
  slug: ''
- description: API for registering callbacks and subscriptions to receive real-time event notifications from Marketing Cloud.
  name: Event Notification Service API
  slug: ''
capabilities:
- description: Unified workflow for digital marketers to manage contacts, orchestrate customer journeys, and automate multi-channel campaigns across email, SMS, and push channels.
  name: Salesforce Marketing Cloud Automation
  slug: marketing-automation
common:
- title: ''
  type: DeveloperPortal
  url: https://developer.salesforce.com/docs/marketing/marketing-cloud/overview
- title: ''
  type: Documentation
  url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/apis-overview.html
- title: ''
  type: Authentication
  url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/authentication.html
- title: ''
  type: APIReference
  url: https://developer.salesforce.com/docs/marketing/marketing-cloud/references
- title: ''
  type: Support
  url: https://help.salesforce.com/s/
- title: ''
  type: StatusPage
  url: https://status.salesforce.com/
- title: ''
  type: SDK
  url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/sdks.html
- title: ''
  type: TermsOfService
  url: https://www.salesforce.com/company/legal/
- title: ''
  type: Pricing
  url: https://www.salesforce.com/products/marketing-cloud/pricing/
- title: ''
  type: ChangeLog
  url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/release-notes.html
- title: ''
  type: RateLimits
  url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rate-limiting.html
- title: ''
  type: GitHubRepository
  url: https://github.com/salesforce-marketingcloud/SFDC-MC-REST-Style-Guide
- title: ''
  type: Training
  url: https://trailhead.salesforce.com/en/content/learn/trails/get-started-with-marketing-cloud
- title: ''
  type: NaftikoCapability
  url: capabilities/marketing-automation.yaml
created: '2024-01-15'
description: Salesforce Marketing Cloud is a comprehensive digital marketing platform that enables businesses to manage customer journeys, email marketing, mobile messaging, social media marketing, advertising, and data analytics.
features:
- description: Design, send, and track targeted email campaigns with dynamic content, personalization, and A/B testing capabilities.
  name: Email Marketing
- description: Create automated, multi-step customer journeys across email, SMS, push, and advertising channels with branching logic.
  name: Journey Builder
- description: Centralized contact database with attribute sets, segmentation, and cross-channel identity resolution.
  name: Contact Management
- description: Send real-time transactional messages like order confirmations and password resets with guaranteed delivery.
  name: Transactional Messaging
- description: Leverage AI-powered recommendations and predictive analytics to personalize content and optimize send times.
  name: Einstein AI Personalization
- description: Schedule and automate data imports, file transfers, SQL queries, and multi-step marketing workflows.
  name: Automation Studio
- description: Centralized content management system for creating, organizing, and reusing marketing assets across channels.
  name: Content Builder
- description: Subscribe to real-time webhook notifications for email tracking events, data changes, and audit activities.
  name: Event Notifications
image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg
integrations:
- description: Bi-directional sync with Sales Cloud and Service Cloud for unified customer profiles and campaign attribution.
  name: Salesforce CRM
- description: Connect to unified customer data profiles for advanced segmentation and real-time personalization.
  name: Salesforce Data Cloud
- description: Track email campaign performance and website conversions with Google Analytics integration.
  name: Google Analytics
- description: Sync e-commerce customer data, purchase history, and cart events for targeted marketing automation.
  name: Shopify
- description: Integrate commerce data for personalized product recommendations and transactional messaging.
  name: Salesforce Commerce Cloud
jsonld:
- class_count: 0
  name: Salesforce Marketing Cloud Context
  property_count: 0
  slug: salesforce-marketing-cloud-context
layout: provider
modified: '2026-04-19'
name: Salesforce Marketing Cloud
rules:
- name: Salesforce Marketing Cloud API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: salesforce-marketing-cloud-spectral-rules
skills: []
slug: salesforce-marketing-cloud
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Salesforce Marketing Cloud\ndescription: Salesforce Marketing Cloud is a comprehensive digital marketing platform that enables businesses to manage customer journeys, email marketing, mobile messaging, social media marketing, advertising, and data analytics.\nimage: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\nurl: https://www.salesforce.com/products/marketing-cloud/overview/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.18'\ntype:\n  - Index\ntags:\n  - Automation\n  - Customer Journey\n  - Digital Marketing\n  - Email\n  - Marketing\n  - Personalization\napis:\n  - name: Marketing Cloud REST API\n    description: Core REST API for interacting with Marketing Cloud features including email, SMS, push notifications, and data extensions. REST API uses JSON request and response bodies and resource endpoints to support multi-channel use.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n\
  \    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/overview\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rest-api-overview.html\n      - type: OpenAPI\n        url: openapi/salesforce-marketing-cloud-openapi.yml\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/authentication.html\n      - type: APIReference\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/routes.html\n      - type: GettingStarted\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/get-started-index.html\n      - type: RateLimits\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rate-limiting.html\n      - type: BestPractices\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rate-limiting-best-practices.html\n\
  \      - type: Errors\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rate-limiting-errors.html\n    tags:\n      - Email\n      - Push\n      - REST\n      - SMS\n  - name: SOAP API\n    description: Legacy SOAP-based API for Marketing Cloud operations, including email sends, subscriber management, and data extension operations.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.soap.marketingcloudapis.com\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/web_service_guide.html\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/web_service_guide.html\n      - type: APIReference\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/soap_web_service_objects.html\n      - type: GettingStarted\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/getting_started_developers_and_the_exacttarget_api.html\n\
  \      - type: BestPractices\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/working_with_soap_web_service_api.html\n    tags:\n      - Legacy\n      - SOAP\n      - Subscriber\n  - name: Transactional Messaging API\n    description: Specialized API for sending triggered, transactional messages including order confirmations, password resets, and real-time notifications.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com/messaging/v1\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/transactional-messaging-api.html\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/transactional-messaging-api.html\n      - type: GettingStarted\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/getting-started-spec.html\n\
  \      - type: BestPractices\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/transactional-messaging-best-practices.html\n    tags:\n      - Messaging\n      - Transactional\n      - Triggered\n  - name: Journey Builder API\n    description: API for creating, managing, and automating customer journeys across multiple channels and touchpoints.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com/interaction/v1\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/journey-builder-api-overview.html\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/journey-builder-api-overview.html\n      - type: GettingStarted\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/get-started-jb.html\n    tags:\n      - Automation\n\
  \      - Journey\n      - Orchestration\n  - name: Data Extensions API\n    description: API for managing data extensions, which are database tables used to store and segment customer data in Marketing Cloud.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com/data/v1\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/data-extensions.html\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/working-with-data-extensions.html\n      - type: APIReference\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/data-extension-api.html\n    tags:\n      - Data\n      - Segmentation\n      - Storage\n  - name: Email Send Definition API\n    description: API for creating and managing email send definitions, which define the configuration for sending\
  \ emails to subscribers.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com/messaging/v1\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/email-send-definition.html\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/email-send-definition.html\n      - type: CodeExamples\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/code-examples.html\n    tags:\n      - Campaigns\n      - Email\n      - Sending\n  - name: Mobile Push API\n    description: API for sending push notifications to mobile devices, managing device registrations, and tracking push message engagement.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com/push/v1\n\
  \    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/mobile-push.html\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/push-notifications.html\n      - type: SDK\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/mobile-sdk.html\n    tags:\n      - Mobile\n      - Notifications\n      - Push\n  - name: SMS/MMS API\n    description: API for sending SMS and MMS messages, managing mobile numbers, and handling keyword-based subscriptions.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com/sms/v1\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/sms-api.html\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/sms-api.html\n    \
  \  - type: BestPractices\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/sms-best-practices.html\n    tags:\n      - MMS\n      - Mobile Messaging\n      - SMS\n  - name: Asset API\n    description: API for managing marketing assets including images, documents, content blocks, and templates across Marketing Cloud.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com/asset/v1\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/asset-api.html\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/asset-api.html\n    tags:\n      - Assets\n      - Content\n      - Templates\n  - name: Einstein Recommendations API\n    description: API for leveraging AI-powered product and content recommendations to personalize customer experiences.\n    image:\
  \ https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com/einstein/v1\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/einstein-recommendations.html\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/einstein-recommendations.html\n    tags:\n      - AI\n      - Personalization\n      - Recommendations\n  - name: Content Builder API\n    description: REST API for creating and manipulating marketing content in Content Builder, a single cross-channel repository for emails, images, text, content blocks, and other documents.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com/asset/v1\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/content-api.html\n\
  \    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/content-api.html\n    tags:\n      - Assets\n      - Content\n      - Email\n      - Templates\n  - name: Contacts API\n    description: REST API for creating, reading, updating, and deleting contacts in Marketing Cloud.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com/contacts/v1\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/references/mc_rest_contacts/createContacts.html\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/references/mc_rest_contacts/createContacts.html\n    tags:\n      - Contacts\n      - Data\n      - Subscribers\n  - name: Automation Studio API\n    description: API for initiating and managing marketing automations, including\
  \ file upload, download, decryption, compression, and decompression operations within Automation Studio.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com/automation/v1\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/automation-studio-api.html\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/automation-studio-api.html\n    tags:\n      - Automation\n      - Scheduling\n      - Workflows\n  - name: Campaign API\n    description: API for managing and performing marketing campaigns within Marketing Cloud.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com/hub/v1\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/campaign.html\n\
  \    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/campaign.html\n    tags:\n      - Campaigns\n      - Execution\n      - Marketing\n  - name: Event Notification Service API\n    description: API for registering callbacks and subscriptions to receive real-time event notifications from Marketing Cloud.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/nav/logo-salesforce.svg\n    baseURL: https://YOUR_SUBDOMAIN.rest.marketingcloudapis.com/platform/v1\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/ens.html\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/ens.html\n      - type: GettingStarted\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/ens-get-started.html\n    tags:\n      - Events\n      - Notifications\n      - Real-Time\n     \
  \ - Webhooks\ncommon:\n  - type: DeveloperPortal\n    url: https://developer.salesforce.com/docs/marketing/marketing-cloud/overview\n  - type: Documentation\n    url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/apis-overview.html\n  - type: Authentication\n    url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/authentication.html\n  - type: APIReference\n    url: https://developer.salesforce.com/docs/marketing/marketing-cloud/references\n  - type: Support\n    url: https://help.salesforce.com/s/\n  - type: StatusPage\n    url: https://status.salesforce.com/\n  - type: SDK\n    url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/sdks.html\n  - type: TermsOfService\n    url: https://www.salesforce.com/company/legal/\n  - type: Pricing\n    url: https://www.salesforce.com/products/marketing-cloud/pricing/\n  - type: ChangeLog\n    url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/release-notes.html\n\
  \  - type: RateLimits\n    url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rate-limiting.html\n  - type: GitHubRepository\n    url: https://github.com/salesforce-marketingcloud/SFDC-MC-REST-Style-Guide\n  - type: Training\n    url: https://trailhead.salesforce.com/en/content/learn/trails/get-started-with-marketing-cloud\n  - type: Features\n    data:\n      - name: Email Marketing\n        description: Design, send, and track targeted email campaigns with dynamic content, personalization, and A/B testing capabilities.\n      - name: Journey Builder\n        description: Create automated, multi-step customer journeys across email, SMS, push, and advertising channels with branching logic.\n      - name: Contact Management\n        description: Centralized contact database with attribute sets, segmentation, and cross-channel identity resolution.\n      - name: Transactional Messaging\n        description: Send real-time transactional messages like order confirmations\
  \ and password resets with guaranteed delivery.\n      - name: Einstein AI Personalization\n        description: Leverage AI-powered recommendations and predictive analytics to personalize content and optimize send times.\n      - name: Automation Studio\n        description: Schedule and automate data imports, file transfers, SQL queries, and multi-step marketing workflows.\n      - name: Content Builder\n        description: Centralized content management system for creating, organizing, and reusing marketing assets across channels.\n      - name: Event Notifications\n        description: Subscribe to real-time webhook notifications for email tracking events, data changes, and audit activities.\n  - type: UseCases\n    data:\n      - name: Customer Onboarding Journeys\n        description: Automate multi-step welcome sequences across email and SMS to guide new customers through product adoption.\n      - name: Abandoned Cart Recovery\n        description: Trigger personalized follow-up\
  \ emails and push notifications when customers abandon shopping carts.\n      - name: Cross-Channel Campaign Orchestration\n        description: Coordinate marketing messages across email, SMS, push, and advertising for unified campaign execution.\n      - name: Subscriber Lifecycle Management\n        description: Manage subscriber preferences, segment audiences, and automate re-engagement campaigns for inactive contacts.\n      - name: Real-Time Event-Driven Marketing\n        description: React to customer behaviors in real time with triggered messages based on website visits, purchases, or app activity.\n  - type: Integrations\n    data:\n      - name: Salesforce CRM\n        description: Bi-directional sync with Sales Cloud and Service Cloud for unified customer profiles and campaign attribution.\n      - name: Salesforce Data Cloud\n        description: Connect to unified customer data profiles for advanced segmentation and real-time personalization.\n      - name: Google Analytics\n\
  \        description: Track email campaign performance and website conversions with Google Analytics integration.\n      - name: Shopify\n        description: Sync e-commerce customer data, purchase history, and cart events for targeted marketing automation.\n      - name: Salesforce Commerce Cloud\n        description: Integrate commerce data for personalized product recommendations and transactional messaging.\n  - type: NaftikoCapability\n    url: capabilities/marketing-automation.yaml\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ncontact:\n  - name: Salesforce Marketing Cloud Support\n    email: support@salesforce.com\n    url: https://help.salesforce.com/s/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesforce-marketing-cloud/refs/heads/main/apis.yml
tags:
- Automation
- Customer Journey
- Digital Marketing
- Email
- Marketing
- Personalization
url: https://www.salesforce.com/products/marketing-cloud/overview/
use_cases:
- description: Automate multi-step welcome sequences across email and SMS to guide new customers through product adoption.
  name: Customer Onboarding Journeys
- description: Trigger personalized follow-up emails and push notifications when customers abandon shopping carts.
  name: Abandoned Cart Recovery
- description: Coordinate marketing messages across email, SMS, push, and advertising for unified campaign execution.
  name: Cross-Channel Campaign Orchestration
- description: Manage subscriber preferences, segment audiences, and automate re-engagement campaigns for inactive contacts.
  name: Subscriber Lifecycle Management
- description: React to customer behaviors in real time with triggered messages based on website visits, purchases, or app activity.
  name: Real-Time Event-Driven Marketing
---
