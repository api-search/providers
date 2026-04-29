---
api_count: 4
api_specs:
- filename: whatsapp-cloud-api-openapi.yml
  format: yaml
  label: WhatsApp Business Platform API
  slug: business-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/whatsapp/refs/heads/main/openapi/whatsapp-cloud-api-openapi.yml
- filename: whatsapp-business-management-api-openapi.yml
  format: yaml
  label: WhatsApp Business Account Management API
  slug: business-account-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/whatsapp/refs/heads/main/openapi/whatsapp-business-management-api-openapi.yml
- filename: whatsapp-flows-api-openapi.yml
  format: yaml
  label: WhatsApp Flows API
  slug: flows-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/whatsapp/refs/heads/main/openapi/whatsapp-flows-api-openapi.yml
apis:
- description: The Cloud API and On-Premises API that enables medium and large businesses to communicate with customers at scale.
  name: WhatsApp Business Platform API
  slug: business-platform-api
- description: API for managing WhatsApp Business Accounts, phone numbers, and messaging templates.
  name: WhatsApp Business Account Management API
  slug: business-account-management-api
- description: 'API for creating structured, interactive forms and multi-step flows within WhatsApp conversations, enabling appointment booking, surveys, lead capture, and other guided experiences using a JSON-based '
  name: WhatsApp Flows API
  slug: flows-api
- description: 'The self-hosted version of the WhatsApp Business API that allowed businesses to run the API on their own infrastructure. This API was deprecated on October 23, 2025, and all users must migrate to the '
  name: WhatsApp On-Premises API
  slug: on-premises-api
asyncapis:
- description: 'WhatsApp Business Platform webhooks deliver real-time notifications for incoming messages, message status updates, template status changes, account updates, phone number quality changes, and security '
  name: WhatsApp Webhooks
  slug: whatsapp-webhooks-asyncapi
capabilities:
- description: Unified workflow for managing WhatsApp Business Accounts, phone numbers, business profiles, user assignments, product catalogs, and phone registration. Combines Business Management API and Cloud API c
  name: WhatsApp Account And Phone Management
  slug: account-and-phone-management
- description: Unified workflow for creating and managing interactive flows, publishing lifecycle management, and webhook subscriptions. Combines Flows API and Business Management API webhook capabilities used by de
  name: WhatsApp Flows And Automation
  slug: flows-and-automation
- description: Unified workflow for sending messages, managing media files, and creating QR codes for customer conversations. Combines WhatsApp Cloud API messaging, media management, and QR code capabilities used by
  name: WhatsApp Messaging And Media
  slug: messaging-and-media
- description: 'Unified workflow for managing message templates and analyzing conversation and template performance. Combines Business Management API template CRUD and analytics capabilities used by marketing teams, '
  name: WhatsApp Templates And Analytics
  slug: templates-and-analytics
common:
- title: ''
  type: TermsOfService
  url: https://www.whatsapp.com/legal/business-terms
- title: ''
  type: PrivacyPolicy
  url: https://www.whatsapp.com/legal/privacy-policy-eea
- title: ''
  type: Commerce Policy
  url: https://www.whatsapp.com/legal/commerce-policy
- title: ''
  type: Developer Portal
  url: https://developers.facebook.com/
- title: ''
  type: GettingStarted
  url: https://developers.facebook.com/docs/whatsapp/cloud-api/get-started
- title: ''
  type: Authentication
  url: https://developers.facebook.com/docs/whatsapp/business-management-api/get-started
- title: ''
  type: Best Practices
  url: https://developers.facebook.com/docs/whatsapp/cloud-api/best-practices
- title: ''
  type: Use Cases
  url: https://business.whatsapp.com/products/business-platform
- title: ''
  type: Change Log
  url: https://developers.facebook.com/docs/whatsapp/cloud-api/changelog
- title: ''
  type: StatusPage
  url: https://metastatus.com/
- title: ''
  type: Blog
  url: https://business.whatsapp.com/blog
- title: ''
  type: Support
  url: https://developers.facebook.com/support/
- title: ''
  type: Console
  url: https://developers.facebook.com/apps/
- title: ''
  type: GitHub Organization
  url: https://github.com/WhatsApp
- title: ''
  type: Community
  url: https://business.whatsapp.com/developers/developer-hub
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/whatsapp-cloud-api
- title: ''
  type: Security
  url: https://www.whatsapp.com/security/WhatsApp-Security-Whitepaper.pdf
- title: ''
  type: PostmanCollection
  url: https://www.postman.com/meta/whatsapp-business-platform/overview
- title: ''
  type: Pricing
  url: https://business.whatsapp.com/products/platform-pricing
- title: ''
  type: JSON-LD
  url: json-ld/whatsapp-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/whatsapp-webhook-payload-schema.json
- title: ''
  type: Node.js SDK
  url: https://github.com/WhatsApp/WhatsApp-Nodejs-SDK
- title: ''
  type: API Examples
  url: https://github.com/fbsamples/whatsapp-api-examples
- title: ''
  type: Business Messaging Policy
  url: https://business.whatsapp.com/policy
- title: ''
  type: Meta Terms
  url: https://www.whatsapp.com/legal/meta-terms-whatsapp-business
- title: ''
  type: FAQ
  url: https://business.whatsapp.com/resources/faq
- title: ''
  type: Sandbox
  url: https://business.whatsapp.com/developers/developer-hub
- title: ''
  type: Versioning
  url: https://developers.facebook.com/docs/graph-api/guides/versioning
- title: ''
  type: Migration Guide
  url: https://developers.facebook.com/docs/whatsapp/cloud-api/migrate-to-cloud-api
- title: ''
  type: RateLimits
  url: https://developers.facebook.com/docs/whatsapp/cloud-api/overview#throughput
- title: ''
  type: Error Codes
  url: https://developers.facebook.com/docs/whatsapp/cloud-api/support/error-codes
created: '2024-01-15'
description: APIs for the WhatsApp messaging platform, enabling businesses to communicate with customers through the world's most popular messaging app.
features:
- description: Send and receive messages, media, and interactive content through Meta-hosted WhatsApp infrastructure.
  name: Cloud API
- description: Pre-approved message templates for proactive customer communication with variable substitution.
  name: Message Templates
- description: Buttons, lists, product catalogs, and flows for rich customer engagement.
  name: Interactive Messages
- description: Send and receive images, videos, documents, audio, stickers, and location data.
  name: Media Messaging
- description: Real-time notifications for incoming messages, delivery status, and account events.
  name: Webhooks
- description: Manage WhatsApp Business accounts, phone numbers, and messaging limits.
  name: Business Management API
- description: Build interactive multi-step forms and workflows within WhatsApp conversations.
  name: Flows
- description: Share product catalogs and enable in-chat commerce experiences.
  name: Catalogs and Commerce
- description: End-to-end encryption for all messages and media.
  name: Encryption
- description: Route conversations to multiple agents with conversation assignment.
  name: Multi-Agent Support
image: /assets/icons/whatsapp.png
integrations:
- description: Manage WhatsApp alongside Facebook and Instagram from a unified dashboard.
  name: Meta Business Suite
- description: CRM integration for managing customer conversations and contact history.
  name: Salesforce
- description: E-commerce integration for order notifications and customer messaging.
  name: Shopify
- description: Marketing and sales integration for lead nurturing via WhatsApp.
  name: HubSpot
- description: Help desk integration for ticketed WhatsApp customer support.
  name: Zendesk
jsonld:
- class_count: 33
  name: Whatsapp Context
  property_count: 109
  slug: whatsapp-context
layout: provider
modified: '2026-04-17'
name: WhatsApp
rules:
- name: WhatsApp API Rules
  rule_count: 17
  severity_counts:
    error: 14
    hint: 0
    info: 1
    warn: 2
  slug: whatsapp-spectral-rules
skills: []
slug: whatsapp
solutions:
- description: Cloud API and On-Premises API for medium and large businesses at scale.
  name: WhatsApp Business Platform
- description: Free mobile app for small businesses with basic messaging features.
  name: WhatsApp Business App
- description: Interactive forms and workflows within WhatsApp conversations.
  name: WhatsApp Flows
source_filename: apis.yml
source_yaml: "aid: whatsapp\nname: WhatsApp\ndescription: APIs for the WhatsApp messaging platform, enabling businesses to communicate\n  with customers through the world's most popular messaging app.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/whatsapp/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-17'\nspecificationVersion: '0.19'\napis:\n- name: WhatsApp Business Platform API\n  description: The Cloud API and On-Premises API that enables medium and large businesses\n    to communicate with customers at scale.\n  image: https://www.whatsapp.com/img/fb-post.jpg\n  humanURL: https://developers.facebook.com/docs/whatsapp\n  baseURL: https://graph.facebook.com/v21.0\n  tags:\n  - Business\n  - Chat\n  - Communications\n  - Messaging\n  properties:\n  - type: Documentation\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api\n  - type: OpenAPI\n    url: openapi/whatsapp-cloud-api-openapi.yml\n\
  \  - type: Authentication\n    url: https://developers.facebook.com/docs/whatsapp/business-management-api/get-started\n  - type: Documentation\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/webhooks\n  - type: AsyncAPI\n    url: asyncapi/whatsapp-webhooks-asyncapi.yml\n  - type: JSONSchema\n    url: json-schema/whatsapp-message-schema.json\n  - type: Reference\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/reference/messages\n  - type: GettingStarted\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/get-started\n  - type: Pricing\n    url: https://developers.facebook.com/docs/whatsapp/pricing\n  - type: RateLimits\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/overview#throughput\n  - type: StatusPage\n    url: https://metastatus.com/\n  - type: Change Log\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/changelog\n  - type: Error Codes\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/support/error-codes\n\
  \  - type: PostmanCollection\n    url: https://www.postman.com/meta/whatsapp-business-platform/collection/wlk6lh4/whatsapp-cloud-api\n  - type: Node.js SDK\n    url: https://github.com/WhatsApp/WhatsApp-Nodejs-SDK\n  - type: Sandbox\n    url: https://business.whatsapp.com/developers/developer-hub\n  - type: Migration Guide\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/migrate-to-cloud-api\n  - type: Media Reference\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/reference/media\n  - type: Phone Numbers Reference\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/reference/phone-numbers\n  - type: Business Profiles Reference\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/reference/business-profiles\n  - type: Two-Step Verification\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/reference/two-step-verification\n  - type: Versioning\n    url: https://developers.facebook.com/docs/graph-api/guides/versioning\n\
  \  contact:\n  - type: Support\n    url: https://developers.facebook.com/support/\n  - type: Twitter\n    url: https://twitter.com/WhatsApp\n  aid: whatsapp:business-platform-api\n- name: WhatsApp Business Account Management API\n  description: API for managing WhatsApp Business Accounts, phone numbers, and messaging\n    templates.\n  image: https://www.whatsapp.com/img/fb-post.jpg\n  humanURL: https://developers.facebook.com/docs/whatsapp/business-management-api\n  baseURL: https://graph.facebook.com/v21.0\n  tags:\n  - Accounts\n  - Business\n  - Management\n  - Templates\n  properties:\n  - type: Documentation\n    url: https://developers.facebook.com/docs/whatsapp/business-management-api\n  - type: OpenAPI\n    url: openapi/whatsapp-business-management-api-openapi.yml\n  - type: Authentication\n    url: https://developers.facebook.com/docs/whatsapp/business-management-api/get-started\n  - type: JSONSchema\n    url: json-schema/whatsapp-message-template-schema.json\n  - type: GettingStarted\n\
  \    url: https://developers.facebook.com/docs/whatsapp/business-management-api/get-started\n  - type: PostmanCollection\n    url: https://www.postman.com/meta/whatsapp-business-platform/collection/3kru5r6/whatsapp-business-management-api\n  - type: Reference\n    url: https://developers.facebook.com/docs/whatsapp/business-management-api/message-templates\n  - type: Change Log\n    url: https://developers.facebook.com/docs/whatsapp/business-management-api/changelog\n  - type: Error Codes\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/support/error-codes\n  - type: RateLimits\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/overview#throughput\n  aid: whatsapp:business-account-management-api\n- name: WhatsApp Flows API\n  description: API for creating structured, interactive forms and multi-step flows\n    within WhatsApp conversations, enabling appointment booking, surveys, lead capture,\n    and other guided experiences using a JSON-based screen definition\
  \ format.\n  image: https://www.whatsapp.com/img/fb-post.jpg\n  humanURL: https://developers.facebook.com/docs/whatsapp/flows\n  baseURL: https://graph.facebook.com/v21.0\n  tags:\n  - Flows\n  - Forms\n  - Interactive\n  - Messaging\n  properties:\n  - type: Documentation\n    url: https://developers.facebook.com/docs/whatsapp/flows\n  - type: OpenAPI\n    url: openapi/whatsapp-flows-api-openapi.yml\n  - type: Reference\n    url: https://developers.facebook.com/docs/whatsapp/flows/reference/components\n  - type: JSONSchema\n    url: json-schema/whatsapp-flow-json-schema.json\n  - type: Change Log\n    url: https://developers.facebook.com/docs/whatsapp/flows/changelogs\n  - type: Error Codes\n    url: https://developers.facebook.com/docs/whatsapp/flows/reference/error-codes\n  - type: PostmanCollection\n    url: https://www.postman.com/meta/whatsapp-business-platform/collection/y5swede/whatsapp-flows-api\n  - type: GitHubRepository\n    url: https://github.com/WhatsApp/WhatsApp-Flows-Tools\n\
  \  - type: GettingStarted\n    url: https://developers.facebook.com/docs/whatsapp/flows/gettingstarted\n  - type: Authentication\n    url: https://developers.facebook.com/docs/whatsapp/business-management-api/get-started\n  aid: whatsapp:flows-api\n- name: WhatsApp On-Premises API\n  description: The self-hosted version of the WhatsApp Business API that allowed businesses\n    to run the API on their own infrastructure. This API was deprecated on October\n    23, 2025, and all users must migrate to the Cloud API.\n  image: https://www.whatsapp.com/img/fb-post.jpg\n  humanURL: https://developers.facebook.com/docs/whatsapp/on-premises\n  baseURL: https://localhost:443\n  tags:\n  - Deprecated\n  - Messaging\n  - On-Premises\n  - Self-Hosted\n  properties:\n  - type: Documentation\n    url: https://developers.facebook.com/docs/whatsapp/on-premises\n  - type: GettingStarted\n    url: https://developers.facebook.com/docs/whatsapp/on-premises/get-started/installation\n  - type: Deprecation Notice\n\
  \    url: https://developers.facebook.com/docs/whatsapp/on-premises\n  - type: PostmanCollection\n    url: https://www.postman.com/meta/whatsapp-business-platform/collection/vdi189b/whatsapp-on-premises-api-deprecated\n  - type: Migration Guide\n    url: https://developers.facebook.com/docs/whatsapp/cloud-api/migrate-to-cloud-api\n  aid: whatsapp:on-premises-api\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\ncommon:\n- type: TermsOfService\n  url: https://www.whatsapp.com/legal/business-terms\n- type: PrivacyPolicy\n  url: https://www.whatsapp.com/legal/privacy-policy-eea\n- type: Commerce Policy\n  url: https://www.whatsapp.com/legal/commerce-policy\n- type: Developer Portal\n  url: https://developers.facebook.com/\n- type: GettingStarted\n  url: https://developers.facebook.com/docs/whatsapp/cloud-api/get-started\n- type: Authentication\n  url: https://developers.facebook.com/docs/whatsapp/business-management-api/get-started\n- type: Best Practices\n  url: https://developers.facebook.com/docs/whatsapp/cloud-api/best-practices\n\
  - type: Use Cases\n  url: https://business.whatsapp.com/products/business-platform\n- type: Change Log\n  url: https://developers.facebook.com/docs/whatsapp/cloud-api/changelog\n- type: StatusPage\n  url: https://metastatus.com/\n- type: Blog\n  url: https://business.whatsapp.com/blog\n- type: Support\n  url: https://developers.facebook.com/support/\n- type: Console\n  url: https://developers.facebook.com/apps/\n- type: GitHub Organization\n  url: https://github.com/WhatsApp\n- type: Community\n  url: https://business.whatsapp.com/developers/developer-hub\n- type: Stack Overflow\n  url: https://stackoverflow.com/questions/tagged/whatsapp-cloud-api\n- type: Security\n  url: https://www.whatsapp.com/security/WhatsApp-Security-Whitepaper.pdf\n- type: PostmanCollection\n  url: https://www.postman.com/meta/whatsapp-business-platform/overview\n- type: Pricing\n  url: https://business.whatsapp.com/products/platform-pricing\n- type: JSON-LD\n  url: json-ld/whatsapp-context.jsonld\n- type: JSONSchema\n\
  \  url: json-schema/whatsapp-webhook-payload-schema.json\n- type: Node.js SDK\n  url: https://github.com/WhatsApp/WhatsApp-Nodejs-SDK\n- type: API Examples\n  url: https://github.com/fbsamples/whatsapp-api-examples\n- type: Business Messaging Policy\n  url: https://business.whatsapp.com/policy\n- type: Meta Terms\n  url: https://www.whatsapp.com/legal/meta-terms-whatsapp-business\n- type: FAQ\n  url: https://business.whatsapp.com/resources/faq\n- type: Sandbox\n  url: https://business.whatsapp.com/developers/developer-hub\n- type: Versioning\n  url: https://developers.facebook.com/docs/graph-api/guides/versioning\n- type: Migration Guide\n  url: https://developers.facebook.com/docs/whatsapp/cloud-api/migrate-to-cloud-api\n- type: RateLimits\n  url: https://developers.facebook.com/docs/whatsapp/cloud-api/overview#throughput\n- type: Error Codes\n  url: https://developers.facebook.com/docs/whatsapp/cloud-api/support/error-codes\n- type: Features\n  data:\n  - name: Cloud API\n    description:\
  \ Send and receive messages, media, and interactive content through\n      Meta-hosted WhatsApp infrastructure.\n  - name: Message Templates\n    description: Pre-approved message templates for proactive customer communication\n      with variable substitution.\n  - name: Interactive Messages\n    description: Buttons, lists, product catalogs, and flows for rich customer engagement.\n  - name: Media Messaging\n    description: Send and receive images, videos, documents, audio, stickers, and\n      location data.\n  - name: Webhooks\n    description: Real-time notifications for incoming messages, delivery status, and\n      account events.\n  - name: Business Management API\n    description: Manage WhatsApp Business accounts, phone numbers, and messaging limits.\n  - name: Flows\n    description: Build interactive multi-step forms and workflows within WhatsApp\n      conversations.\n  - name: Catalogs and Commerce\n    description: Share product catalogs and enable in-chat commerce experiences.\n\
  \  - name: Encryption\n    description: End-to-end encryption for all messages and media.\n  - name: Multi-Agent Support\n    description: Route conversations to multiple agents with conversation assignment.\n- type: UseCases\n  data:\n  - name: Customer Support\n    description: Provide real-time customer service and support through WhatsApp messaging.\n  - name: Order Notifications\n    description: Send order confirmations, shipping updates, and delivery notifications.\n  - name: Appointment Reminders\n    description: Send appointment reminders and allow rescheduling via interactive\n      messages.\n  - name: Marketing Campaigns\n    description: Send promotional messages using approved templates to opted-in customers.\n  - name: Two-Factor Authentication\n    description: Send OTP codes and verification messages for account security.\n  - name: Chatbot Integration\n    description: Build automated conversational bots for FAQs and self-service workflows.\n  - name: E-commerce\n  \
  \  description: Share product catalogs, process orders, and send payment reminders.\n  - name: Healthcare Communication\n    description: Send appointment reminders, test results, and health tips to patients.\n- type: Integrations\n  data:\n  - name: Meta Business Suite\n    description: Manage WhatsApp alongside Facebook and Instagram from a unified dashboard.\n  - name: Salesforce\n    description: CRM integration for managing customer conversations and contact history.\n  - name: Shopify\n    description: E-commerce integration for order notifications and customer messaging.\n  - name: HubSpot\n    description: Marketing and sales integration for lead nurturing via WhatsApp.\n  - name: Zendesk\n    description: Help desk integration for ticketed WhatsApp customer support.\n- type: Solutions\n  data:\n  - name: WhatsApp Business Platform\n    description: Cloud API and On-Premises API for medium and large businesses at\n      scale.\n  - name: WhatsApp Business App\n    description:\
  \ Free mobile app for small businesses with basic messaging features.\n  - name: WhatsApp Flows\n    description: Interactive forms and workflows within WhatsApp conversations.\ntype: Index\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/whatsapp/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/whatsapp/refs/heads/main/apis.yml
use_cases:
- description: Provide real-time customer service and support through WhatsApp messaging.
  name: Customer Support
- description: Send order confirmations, shipping updates, and delivery notifications.
  name: Order Notifications
- description: Send appointment reminders and allow rescheduling via interactive messages.
  name: Appointment Reminders
- description: Send promotional messages using approved templates to opted-in customers.
  name: Marketing Campaigns
- description: Send OTP codes and verification messages for account security.
  name: Two-Factor Authentication
- description: Build automated conversational bots for FAQs and self-service workflows.
  name: Chatbot Integration
- description: Share product catalogs, process orders, and send payment reminders.
  name: E-commerce
- description: Send appointment reminders, test results, and health tips to patients.
  name: Healthcare Communication
---
