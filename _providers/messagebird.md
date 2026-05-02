---
api_count: 12
api_specs:
- filename: messagebird-sms-messaging-openapi.yml
  format: yaml
  label: MessageBird SMS Messaging API
  slug: sms-messaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-sms-messaging-openapi.yml
- filename: messagebird-voice-calling-openapi.yml
  format: yaml
  label: MessageBird Voice Calling API
  slug: voice-calling-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-voice-calling-openapi.yml
- filename: messagebird-voice-messaging-openapi.yml
  format: yaml
  label: MessageBird Voice Messaging API
  slug: voice-messaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-voice-messaging-openapi.yml
- filename: messagebird-conversations-openapi.yml
  format: yaml
  label: MessageBird Conversations API
  slug: conversations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-conversations-openapi.yml
- filename: messagebird-whatsapp-openapi.yml
  format: yaml
  label: MessageBird WhatsApp API
  slug: whatsapp-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-whatsapp-openapi.yml
- filename: messagebird-verify-openapi.yml
  format: yaml
  label: MessageBird Verify API
  slug: verify-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-verify-openapi.yml
- filename: messagebird-lookup-openapi.yml
  format: yaml
  label: MessageBird Lookup API
  slug: lookup-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-lookup-openapi.yml
- filename: messagebird-hlr-openapi.yml
  format: yaml
  label: MessageBird HLR API
  slug: hlr-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-hlr-openapi.yml
- filename: messagebird-contacts-openapi.yml
  format: yaml
  label: MessageBird Contacts API
  slug: contacts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-contacts-openapi.yml
- filename: messagebird-numbers-openapi.yml
  format: yaml
  label: MessageBird Numbers API
  slug: numbers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-numbers-openapi.yml
- filename: messagebird-balance-openapi.yml
  format: yaml
  label: MessageBird Balance API
  slug: balance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-balance-openapi.yml
- filename: messagebird-integrations-openapi.yml
  format: yaml
  label: MessageBird Integrations API
  slug: integrations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/openapi/messagebird-integrations-openapi.yml
apis:
- description: The MessageBird SMS Messaging API allows developers to send and receive SMS messages to and from any country in the world through a REST interface. It supports features such as message scheduling, del
  name: MessageBird SMS Messaging API
  slug: sms-messaging-api
- description: The MessageBird Voice Calling API enables developers to make, receive, and control phone calls programmatically. It supports call flows for building interactive voice response systems, call recording,
  name: MessageBird Voice Calling API
  slug: voice-calling-api
- description: The MessageBird Voice Messaging API enables developers to transform text messages into voice messages delivered to any country. It supports 26 languages with configurable attributes such as male or fe
  name: MessageBird Voice Messaging API
  slug: voice-messaging-api
- description: The MessageBird Conversations API provides a unified interface for managing omnichannel messaging across platforms such as SMS, WhatsApp, Facebook Messenger, Telegram, and more. It consolidates messag
  name: MessageBird Conversations API
  slug: conversations-api
- description: The MessageBird WhatsApp API allows developers to send and receive WhatsApp messages for alerts, notifications, customer support, and two-factor authentication. It provides access to all WhatsApp Busi
  name: MessageBird WhatsApp API
  slug: whatsapp-api
- description: The MessageBird Verify API provides a simple way to implement two-factor authentication and phone number verification. It generates and validates one-time passwords delivered via SMS or voice call, ha
  name: MessageBird Verify API
  slug: verify-api
- description: The MessageBird Lookup API enables developers to validate and look up mobile phone numbers. It performs HLR lookups on the mobile network to identify number format, country, operator, and availability
  name: MessageBird Lookup API
  slug: lookup-api
- description: The MessageBird HLR API provides a way to send Home Location Register network queries to any mobile number globally. It allows developers to determine which operator a mobile number belongs to in real
  name: MessageBird HLR API
  slug: hlr-api
- description: 'The MessageBird Contacts API allows developers to manage contact information for end-users and customers across messaging platforms. It supports creating, reading, updating, and deleting contacts, as '
  name: MessageBird Contacts API
  slug: contacts-api
- description: The MessageBird Numbers API enables developers to search for, purchase, and manage phone numbers programmatically. It supports local, toll-free, and mobile number types across multiple countries, with
  name: MessageBird Numbers API
  slug: numbers-api
- description: The MessageBird Balance API provides developers with access to their account balance information. It returns the current payment type, available amount, and currency for the account associated with th
  name: MessageBird Balance API
  slug: balance-api
- description: The MessageBird Integrations API allows developers to create, fetch, and delete message templates for supported platforms. It currently supports template management for the WhatsApp platform, enabling
  name: MessageBird Integrations API
  slug: integrations-api
asyncapis:
- description: The MessageBird Conversations webhook system delivers real-time notifications for conversation events across all messaging channels including SMS, WhatsApp, Facebook Messenger, Telegram, and more. Web
  name: MessageBird Conversations Events
  slug: messagebird-conversations-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/messagebird-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/messagebird-message-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/messagebird-conversation-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/messagebird-contact-schema.json
created: ''
description: Build powerful apps using the fastest and most reliable cloud communications APIs.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Messagebird Context
  property_count: 8
  slug: messagebird-context
layout: provider
modified: '2026-03-20'
name: messagebird
skills: []
slug: messagebird
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: messagebird\nurl: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/apis.yml\nmodified: '2026-03-20'\napis:\n  - aid: messagebird:sms-messaging-api\n    name: MessageBird SMS Messaging API\n    tags:\n      - Communications\n      - Messaging\n      - SMS\n      - Text Messages\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://rest.messagebird.com\n    humanURL: https://developers.messagebird.com/api/sms-messaging/\n    properties:\n      - url: https://developers.messagebird.com/api/sms-messaging/\n        type: Documentation\n      - url: openapi/messagebird-sms-messaging-openapi.yml\n        type: OpenAPI\n    description: >-\n      The MessageBird SMS Messaging API allows developers to send and receive\n      SMS messages to and from any country in the world through a REST\n      interface. It supports features such as message scheduling, delivery\n      reports, Unicode messages,\
  \ and concatenated messages for longer content.\n      The API provides both HTTP and SMPP connectivity options for high-volume\n      messaging use cases.\n  - aid: messagebird:voice-calling-api\n    name: MessageBird Voice Calling API\n    tags:\n      - Calling\n      - Communications\n      - Telephony\n      - Voice\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://voice.messagebird.com\n    humanURL: https://developers.messagebird.com/api/voice-calling/\n    properties:\n      - url: https://developers.messagebird.com/api/voice-calling/\n        type: Documentation\n      - url: openapi/messagebird-voice-calling-openapi.yml\n        type: OpenAPI\n    description: >-\n      The MessageBird Voice Calling API enables developers to make, receive,\n      and control phone calls programmatically. It supports call flows for\n      building interactive voice response systems, call recording, call\n      transfers, and real-time\
  \ webhooks for call events. The API provides\n      global coverage and can be used to build contact center solutions,\n      automated calling systems, and voice-enabled applications.\n  - aid: messagebird:voice-messaging-api\n    name: MessageBird Voice Messaging API\n    tags:\n      - Communications\n      - Messaging\n      - Text-To-Speech\n      - Voice\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://rest.messagebird.com\n    humanURL: https://developers.messagebird.com/api/voice-messaging/\n    properties:\n      - url: https://developers.messagebird.com/api/voice-messaging/\n        type: Documentation\n      - url: openapi/messagebird-voice-messaging-openapi.yml\n        type: OpenAPI\n    description: >-\n      The MessageBird Voice Messaging API enables developers to transform text\n      messages into voice messages delivered to any country. It supports 26\n      languages with configurable attributes such as male\
  \ or female voice,\n      speaking rate, repeat options, and scheduling. The API is useful for\n      sending voice notifications, alerts, and one-time passwords to users\n      who may not have access to SMS.\n  - aid: messagebird:conversations-api\n    name: MessageBird Conversations API\n    tags:\n      - Chat\n      - Communications\n      - Messaging\n      - Omnichannel\n      - WhatsApp\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://conversations.messagebird.com\n    humanURL: https://developers.messagebird.com/api/conversations/\n    properties:\n      - url: https://developers.messagebird.com/api/conversations/\n        type: Documentation\n      - url: openapi/messagebird-conversations-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/messagebird-conversations-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The MessageBird Conversations API provides a unified interface for\n      managing\
  \ omnichannel messaging across platforms such as SMS, WhatsApp,\n      Facebook Messenger, Telegram, and more. It consolidates messages from\n      multiple channels into a single conversation thread per contact,\n      enabling consistent customer communication. The API supports sending\n      and receiving messages, managing conversation state, and handling\n      webhooks for real-time event processing.\n  - aid: messagebird:whatsapp-api\n    name: MessageBird WhatsApp API\n    tags:\n      - Communications\n      - Messaging\n      - Notifications\n      - WhatsApp\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://conversations.messagebird.com\n    humanURL: https://developers.messagebird.com/api/whatsapp\n    properties:\n      - url: https://developers.messagebird.com/api/whatsapp\n        type: Documentation\n      - url: openapi/messagebird-whatsapp-openapi.yml\n        type: OpenAPI\n    description: >-\n      The MessageBird\
  \ WhatsApp API allows developers to send and receive\n      WhatsApp messages for alerts, notifications, customer support, and\n      two-factor authentication. It provides access to all WhatsApp Business\n      features through a single API, including template messages, media\n      messages, and interactive message types. The API supports rich media\n      content and provides delivery and read receipts for message tracking.\n  - aid: messagebird:verify-api\n    name: MessageBird Verify API\n    tags:\n      - OTP\n      - Security\n      - Two-Factor Authentication\n      - Verification\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://rest.messagebird.com\n    humanURL: https://developers.messagebird.com/api/verify/\n    properties:\n      - url: https://developers.messagebird.com/api/verify/\n        type: Documentation\n      - url: openapi/messagebird-verify-openapi.yml\n        type: OpenAPI\n    description: >-\n     \
  \ The MessageBird Verify API provides a simple way to implement two-factor\n      authentication and phone number verification. It generates and validates\n      one-time passwords delivered via SMS or voice call, handling token\n      generation, delivery, and verification in a single workflow. The API\n      supports configurable token length, expiration time, and delivery\n      channel selection for flexible integration into sign-up and login flows.\n  - aid: messagebird:lookup-api\n    name: MessageBird Lookup API\n    tags:\n      - HLR\n      - Number Intelligence\n      - Phone Numbers\n      - Validation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://rest.messagebird.com\n    humanURL: https://developers.messagebird.com/api/lookup/\n    properties:\n      - url: https://developers.messagebird.com/api/lookup/\n        type: Documentation\n      - url: openapi/messagebird-lookup-openapi.yml\n        type: OpenAPI\n  \
  \  description: >-\n      The MessageBird Lookup API enables developers to validate and look up\n      mobile phone numbers. It performs HLR lookups on the mobile network to\n      identify number format, country, operator, and availability in\n      real-time. The API is useful for cleaning contact lists, validating\n      user-provided phone numbers, and determining the correct format before\n      sending messages.\n  - aid: messagebird:hlr-api\n    name: MessageBird HLR API\n    tags:\n      - HLR\n      - Mobile Network\n      - Network Query\n      - Phone Numbers\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://rest.messagebird.com\n    humanURL: https://developers.messagebird.com/api/hlr/\n    properties:\n      - url: https://developers.messagebird.com/api/hlr/\n        type: Documentation\n      - url: openapi/messagebird-hlr-openapi.yml\n        type: OpenAPI\n    description: >-\n      The MessageBird HLR API provides\
  \ a way to send Home Location Register\n      network queries to any mobile number globally. It allows developers to\n      determine which operator a mobile number belongs to in real-time and\n      check whether the number is currently active on the network. This API\n      is commonly used for number portability checks, fraud prevention, and\n      optimizing message routing.\n  - aid: messagebird:contacts-api\n    name: MessageBird Contacts API\n    tags:\n      - Address Book\n      - Contacts\n      - Customer Data\n      - Groups\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://rest.messagebird.com\n    humanURL: https://developers.messagebird.com/api/contacts/\n    properties:\n      - url: https://developers.messagebird.com/api/contacts/\n        type: Documentation\n      - url: openapi/messagebird-contacts-openapi.yml\n        type: OpenAPI\n    description: >-\n      The MessageBird Contacts API allows developers to\
  \ manage contact\n      information for end-users and customers across messaging platforms. It\n      supports creating, reading, updating, and deleting contacts, as well as\n      organizing them into groups for targeted messaging campaigns. A single\n      contact can be associated with multiple communication channels such as\n      SMS, WhatsApp, and Telegram.\n  - aid: messagebird:numbers-api\n    name: MessageBird Numbers API\n    tags:\n      - Number Management\n      - Phone Numbers\n      - Provisioning\n      - Telecommunications\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://numbers.messagebird.com\n    humanURL: https://developers.messagebird.com/api/numbers/\n    properties:\n      - url: https://developers.messagebird.com/api/numbers/\n        type: Documentation\n      - url: openapi/messagebird-numbers-openapi.yml\n        type: OpenAPI\n    description: >-\n      The MessageBird Numbers API enables developers\
  \ to search for, purchase,\n      and manage phone numbers programmatically. It supports local, toll-free,\n      and mobile number types across multiple countries, with the ability to\n      filter by pattern, type, and region. Purchased numbers can be configured\n      for SMS and voice capabilities and assigned to specific messaging or\n      calling workflows.\n  - aid: messagebird:balance-api\n    name: MessageBird Balance API\n    tags:\n      - Account\n      - Balance\n      - Billing\n      - Credits\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://rest.messagebird.com\n    humanURL: https://developers.messagebird.com/api/balance/\n    properties:\n      - url: https://developers.messagebird.com/api/balance/\n        type: Documentation\n      - url: openapi/messagebird-balance-openapi.yml\n        type: OpenAPI\n    description: >-\n      The MessageBird Balance API provides developers with access to their\n      account\
  \ balance information. It returns the current payment type,\n      available amount, and currency for the account associated with the\n      API key. This API is useful for monitoring credit usage, building\n      billing dashboards, and setting up automated alerts when account\n      balances fall below a threshold.\n  - aid: messagebird:integrations-api\n    name: MessageBird Integrations API\n    tags:\n      - Integrations\n      - Message Templates\n      - Templates\n      - WhatsApp\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://integrations.messagebird.com\n    humanURL: https://developers.messagebird.com/api/integrations/\n    properties:\n      - url: https://developers.messagebird.com/api/integrations/\n        type: Documentation\n      - url: openapi/messagebird-integrations-openapi.yml\n        type: OpenAPI\n    description: >-\n      The MessageBird Integrations API allows developers to create, fetch,\n     \
  \ and delete message templates for supported platforms. It currently\n      supports template management for the WhatsApp platform, enabling\n      developers to programmatically manage the templates required for\n      sending WhatsApp Business notifications and messages. The API handles\n      template submission, approval status tracking, and lifecycle management.\ncommon:\n  - type: JSON-LD\n    url: json-ld/messagebird-context.jsonld\n  - type: JSONSchema\n    url: json-schema/messagebird-message-schema.json\n  - type: JSONSchema\n    url: json-schema/messagebird-conversation-schema.json\n  - type: JSONSchema\n    url: json-schema/messagebird-contact-schema.json\ndescription: >-\n  Build powerful apps using the fastest and most reliable cloud communications APIs.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/apis.yml
use_cases: []
---
