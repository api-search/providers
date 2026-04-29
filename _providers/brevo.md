---
api_count: 8
api_specs:
- filename: brevo-transactional-email-openapi.yml
  format: yaml
  label: Brevo Transactional Email API
  slug: transactional-email-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/brevo/refs/heads/main/openapi/brevo-transactional-email-openapi.yml
- filename: brevo-email-campaigns-openapi.yml
  format: yaml
  label: Brevo Email Campaigns API
  slug: email-campaigns-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/brevo/refs/heads/main/openapi/brevo-email-campaigns-openapi.yml
- filename: brevo-contacts-openapi.yml
  format: yaml
  label: Brevo Contacts API
  slug: contacts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/brevo/refs/heads/main/openapi/brevo-contacts-openapi.yml
- filename: brevo-transactional-sms-openapi.yml
  format: yaml
  label: Brevo Transactional SMS API
  slug: transactional-sms-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/brevo/refs/heads/main/openapi/brevo-transactional-sms-openapi.yml
- filename: brevo-whatsapp-openapi.yml
  format: yaml
  label: Brevo WhatsApp API
  slug: whatsapp-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/brevo/refs/heads/main/openapi/brevo-whatsapp-openapi.yml
- filename: brevo-ecommerce-openapi.yml
  format: yaml
  label: Brevo eCommerce API
  slug: ecommerce-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/brevo/refs/heads/main/openapi/brevo-ecommerce-openapi.yml
- filename: brevo-conversations-openapi.yml
  format: yaml
  label: Brevo Conversations API
  slug: conversations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/brevo/refs/heads/main/openapi/brevo-conversations-openapi.yml
- filename: brevo-webhooks-openapi.yml
  format: yaml
  label: Brevo Webhooks API
  slug: webhooks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/brevo/refs/heads/main/openapi/brevo-webhooks-openapi.yml
apis:
- description: 'The Brevo Transactional Email API allows developers to send transactional emails such as order confirmations, password resets, and account notifications programmatically. It supports single and batch '
  name: Brevo Transactional Email API
  slug: transactional-email-api
- description: The Brevo Email Campaigns API enables developers to create, manage, and send marketing email campaigns programmatically. It provides endpoints for building campaigns with HTML content or templates, sc
  name: Brevo Email Campaigns API
  slug: email-campaigns-api
- description: The Brevo Contacts API provides programmatic access to contact management features including creating, updating, and deleting contacts. Developers can organize contacts into lists, apply attributes an
  name: Brevo Contacts API
  slug: contacts-api
- description: The Brevo Transactional SMS API allows developers to send non-promotional SMS messages such as order confirmations, delivery notifications, and verification codes using recipients' phone numbers. It s
  name: Brevo Transactional SMS API
  slug: transactional-sms-api
- description: The Brevo WhatsApp API enables developers to send transactional WhatsApp messages such as order confirmations, status updates, and password reset links through the WhatsApp Business platform. It provi
  name: Brevo WhatsApp API
  slug: whatsapp-api
- description: 'The Brevo eCommerce API allows developers to sync product catalogs, categories, and order data with the Brevo platform. It provides endpoints for importing and managing products, organizing them into '
  name: Brevo eCommerce API
  slug: ecommerce-api
- description: The Brevo Conversations API provides programmatic access to live chat and messaging features for customer support and engagement. It enables developers to manage chat conversations, send and receive m
  name: Brevo Conversations API
  slug: conversations-api
- description: The Brevo Webhooks API allows developers to receive real-time notifications when events occur across transactional emails, marketing campaigns, and conversations. By configuring webhook subscriptions,
  name: Brevo Webhooks API
  slug: webhooks-api
asyncapis:
- description: Brevo delivers real-time event notifications via webhooks for transactional emails, marketing campaigns, transactional SMS, and conversations. When configured, Brevo sends HTTP POST requests to your s
  name: Brevo Webhook Events
  slug: brevo-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/brevo-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/brevo-contact-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/brevo-email-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/brevo-order-schema.json
created: ''
description: Send transactional emails with static or dynamic content using the Messaging API.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Brevo Context
  property_count: 10
  slug: brevo-context
layout: provider
modified: '2026-03-20'
name: brevo
skills: []
slug: brevo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: brevo\nurl: https://raw.githubusercontent.com/api-evangelist/brevo/refs/heads/main/apis.yml\napis:\n  - aid: brevo:transactional-email-api\n    name: Brevo Transactional Email API\n    tags:\n      - Email\n      - Messaging\n      - SMTP\n      - Transactional\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.brevo.com/v3\n    humanURL: https://developers.brevo.com/docs/send-a-transactional-email\n    properties:\n      - url: https://developers.brevo.com/docs/send-a-transactional-email\n        type: Documentation\n      - url: openapi/brevo-transactional-email-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Brevo Transactional Email API allows developers to send transactional\n      emails such as order confirmations, password resets, and account\n      notifications programmatically. It supports single and batch sending,\n      scheduled deliveries, template-based emails, and attachment\
  \ handling. The\n      API also provides endpoints for tracking email activity including opens,\n      clicks, bounces, and delivery status through detailed event logs and\n      real-time webhooks.\n  - aid: brevo:email-campaigns-api\n    name: Brevo Email Campaigns API\n    tags:\n      - Automation\n      - Campaigns\n      - Email\n      - Marketing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.brevo.com/v3\n    humanURL: https://developers.brevo.com/docs/getting-started\n    properties:\n      - url: https://developers.brevo.com/docs/getting-started\n        type: Documentation\n      - url: openapi/brevo-email-campaigns-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Brevo Email Campaigns API enables developers to create, manage, and\n      send marketing email campaigns programmatically. It provides endpoints for\n      building campaigns with HTML content or templates, scheduling sends,\n    \
  \  segmenting audiences, and managing sender identities. Developers can\n      retrieve campaign statistics including open rates, click rates, and\n      unsubscribes to measure performance and optimize future campaigns.\n  - aid: brevo:contacts-api\n    name: Brevo Contacts API\n    tags:\n      - Contacts\n      - CRM\n      - Lists\n      - Segmentation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.brevo.com/v3\n    humanURL: https://developers.brevo.com/docs/how-it-works\n    properties:\n      - url: https://developers.brevo.com/docs/how-it-works\n        type: Documentation\n      - url: openapi/brevo-contacts-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Brevo Contacts API provides programmatic access to contact management\n      features including creating, updating, and deleting contacts. Developers\n      can organize contacts into lists, apply attributes and tags, import\n      contacts in\
  \ bulk, and build audience segments for targeted campaigns. The\n      API also supports managing folders, contact attributes, and custom fields\n      to structure contact data according to business needs.\n  - aid: brevo:transactional-sms-api\n    name: Brevo Transactional SMS API\n    tags:\n      - Messaging\n      - Mobile\n      - SMS\n      - Transactional\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.brevo.com/v3\n    humanURL: https://developers.brevo.com/docs/transactional-sms-endpoints\n    properties:\n      - url: https://developers.brevo.com/docs/transactional-sms-endpoints\n        type: Documentation\n      - url: openapi/brevo-transactional-sms-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Brevo Transactional SMS API allows developers to send non-promotional\n      SMS messages such as order confirmations, delivery notifications, and\n      verification codes using recipients' phone\
  \ numbers. It supports sending\n      individual messages with customizable sender names and provides endpoints\n      for tracking SMS delivery status and activity. The API is designed for\n      time-sensitive notifications that require immediate delivery to mobile\n      devices.\n  - aid: brevo:whatsapp-api\n    name: Brevo WhatsApp API\n    tags:\n      - Messaging\n      - Mobile\n      - Transactional\n      - WhatsApp\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.brevo.com/v3\n    humanURL: https://developers.brevo.com/docs/whatsapp-messages\n    properties:\n      - url: https://developers.brevo.com/docs/whatsapp-messages\n        type: Documentation\n      - url: openapi/brevo-whatsapp-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Brevo WhatsApp API enables developers to send transactional WhatsApp\n      messages such as order confirmations, status updates, and password reset\n      links\
  \ through the WhatsApp Business platform. It provides endpoints for\n      sending template-based messages, managing WhatsApp campaigns, and tracking\n      message delivery and read status. The API leverages WhatsApp's high\n      engagement rates to deliver important notifications directly to users on\n      their preferred messaging platform.\n  - aid: brevo:ecommerce-api\n    name: Brevo eCommerce API\n    tags:\n      - Categories\n      - Ecommerce\n      - Orders\n      - Products\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.brevo.com/v3\n    humanURL: https://developers.brevo.com/docs/import-your-products\n    properties:\n      - url: https://developers.brevo.com/docs/import-your-products\n        type: Documentation\n      - url: openapi/brevo-ecommerce-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Brevo eCommerce API allows developers to sync product catalogs,\n      categories, and order\
  \ data with the Brevo platform. It provides endpoints\n      for importing and managing products, organizing them into categories, and\n      tracking customer purchase history. This data integration enables\n      merchants to attribute revenue to marketing campaigns, trigger automated\n      workflows based on purchase behavior, and build product recommendation\n      segments for targeted messaging.\n  - aid: brevo:conversations-api\n    name: Brevo Conversations API\n    tags:\n      - Chat\n      - Conversations\n      - Live Chat\n      - Support\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.brevo.com/v3\n    humanURL: https://developers.brevo.com/docs/getting-started\n    properties:\n      - url: https://developers.brevo.com/docs/getting-started\n        type: Documentation\n      - url: openapi/brevo-conversations-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Brevo Conversations API provides\
  \ programmatic access to live chat and\n      messaging features for customer support and engagement. It enables\n      developers to manage chat conversations, send and receive messages, and\n      integrate Brevo's chat widget into websites and applications. The API\n      supports real-time communication with site visitors and can be used to\n      build custom chat interfaces, automate responses, and route conversations\n      to appropriate team members.\n  - aid: brevo:webhooks-api\n    name: Brevo Webhooks API\n    tags:\n      - Automation\n      - Events\n      - Notifications\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.brevo.com/v3\n    humanURL: https://developers.brevo.com/docs/transactional-webhooks\n    properties:\n      - url: https://developers.brevo.com/docs/transactional-webhooks\n        type: Documentation\n      - url: openapi/brevo-webhooks-openapi.yml\n        type: OpenAPI\n\
  \      - url: asyncapi/brevo-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Brevo Webhooks API allows developers to receive real-time\n      notifications when events occur across transactional emails, marketing\n      campaigns, and conversations. By configuring webhook subscriptions,\n      applications can automatically receive data for events such as email\n      deliveries, opens, clicks, bounces, spam reports, and unsubscribes. This\n      eliminates the need for polling and enables event-driven integrations that\n      respond immediately to changes in messaging activity.\nmodified: '2026-03-20'\ncommon:\n  - type: JSON-LD\n    url: json-ld/brevo-context.jsonld\n  - type: JSONSchema\n    url: json-schema/brevo-contact-schema.json\n  - type: JSONSchema\n    url: json-schema/brevo-email-event-schema.json\n  - type: JSONSchema\n    url: json-schema/brevo-order-schema.json\ndescription: >-\n  Send transactional emails with static or dynamic content using\
  \ the Messaging API.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/brevo/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/brevo/refs/heads/main/apis.yml
use_cases: []
---
