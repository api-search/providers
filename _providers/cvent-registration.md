---
api_count: 2
apis:
- description: The Cvent Registration REST API is the registration surface of the unified Cvent Platform REST API. It allows integrations to create and manage events, registration types, fees, sessions, contacts, at
  name: Cvent Registration REST API
  slug: rest-api
- description: Cvent Webhooks deliver real-time push notifications when registration, attendee, session, and meeting request events occur in Cvent. Webhook subscribers receive event payloads at a configured URL, ena
  name: Cvent Registration Webhooks
  slug: webhooks
common:
- title: ''
  type: Website
  url: https://www.cvent.com/en/event-management-software/online-registration-software
- title: ''
  type: DeveloperPortal
  url: https://developers.cvent.com/
- title: ''
  type: APIReference
  url: https://developers.cvent.com/docs/rest-api/reference/reference
- title: ''
  type: Authentication
  url: https://developers.cvent.com/docs/rest-api/explanation/authentication
- title: ''
  type: OAuthTokenEndpoint
  url: https://api-platform.cvent.com/ea/oauth2/token
- title: ''
  type: Status
  url: https://status.cvent.com/
- title: ''
  type: Support
  url: https://support.cvent.com/
- title: ''
  type: Pricing
  url: https://www.cvent.com/en/pricing
- title: ''
  type: TermsOfService
  url: https://www.cvent.com/en/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.cvent.com/en/privacy-policy
- title: ''
  type: Twitter
  url: https://twitter.com/cvent
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/cvent/
created: '2024-01-15'
description: Cvent Registration is the event registration product within the Cvent Event Cloud, providing online registration websites, attendee data capture, payment processing, registration travel, group registration, custom field collection, and badge / on-site check-in workflows. Registration data is exposed programmatically through the unified Cvent Platform REST API at api-platform.cvent.com (OAuth 2.0 client credentials), with a dedicated Registration Guide on the Cvent developer portal. Real-time registration changes are also delivered through Cvent Webhooks. Earlier integrations relied on the legacy Cvent SOAP API.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Cvent Registration
skills: []
slug: cvent-registration
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cvent-registration\nname: Cvent Registration\nx-type: company\ndescription: >-\n  Cvent Registration is the event registration product within the Cvent\n  Event Cloud, providing online registration websites, attendee data\n  capture, payment processing, registration travel, group registration,\n  custom field collection, and badge / on-site check-in workflows.\n  Registration data is exposed programmatically through the unified\n  Cvent Platform REST API at api-platform.cvent.com (OAuth 2.0 client\n  credentials), with a dedicated Registration Guide on the Cvent\n  developer portal. Real-time registration changes are also delivered\n  through Cvent Webhooks. Earlier integrations relied on the legacy\n  Cvent SOAP API.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cvent-registration/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\naccess: 3rd-Party\nposition: Consuming\ncreated: '2024-01-15'\n\
  modified: '2026-04-28'\nspecificationVersion: '0.20'\ntags:\n  - Attendee Management\n  - Attendees\n  - Conferences\n  - Event Management\n  - Events\n  - OAuth 2.0\n  - On-Site Check-In\n  - Payments\n  - Registration\n  - REST API\n  - Ticketing\n  - Webhooks\napis:\n  - aid: cvent-registration:rest-api\n    name: Cvent Registration REST API\n    description: >-\n      The Cvent Registration REST API is the registration surface of\n      the unified Cvent Platform REST API. It allows integrations to\n      create and manage events, registration types, fees, sessions,\n      contacts, attendees, registrations, payments, and travel data.\n      Authentication uses OAuth 2.0 client credentials with the token\n      endpoint at api-platform.cvent.com/ea/oauth2/token. Detailed\n      registration workflows are documented in the Registration Guide.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.cvent.com/docs/rest-api/guides/registration-guide\n\
  \    baseURL: https://api-platform.cvent.com\n    tags:\n      - Attendees\n      - Contacts\n      - Events\n      - OAuth 2.0\n      - Payments\n      - Registration\n      - REST\n      - Sessions\n      - Ticketing\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/rest-api/overview\n      - type: RegistrationGuide\n        url: https://developers.cvent.com/docs/rest-api/guides/registration-guide\n      - type: APIReference\n        url: https://developers.cvent.com/docs/rest-api/reference/reference\n      - type: Authentication\n        url: https://developers.cvent.com/docs/rest-api/explanation/authentication\n      - type: OAuthTokenEndpoint\n        url: https://api-platform.cvent.com/ea/oauth2/token\n      - type: ChangeLog\n        url: https://developers.cvent.com/docs/rest-api/changelog\n  - aid: cvent-registration:webhooks\n    name: Cvent Registration Webhooks\n    description: >-\n      Cvent Webhooks deliver real-time push notifications\
  \ when\n      registration, attendee, session, and meeting request events occur\n      in Cvent. Webhook subscribers receive event payloads at a\n      configured URL, enabling reactive integration with CRM, marketing\n      automation, data warehouses, and analytics without polling the\n      REST API.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.cvent.com/docs/webhooks/overview\n    tags:\n      - Attendees\n      - Events\n      - Notifications\n      - Real-Time\n      - Registration\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/webhooks/overview\n      - type: GettingStarted\n        url: https://developers.cvent.com/docs/webhooks/tutorials/account-setup\n      - type: Guide\n        url: https://developers.cvent.com/docs/webhooks/understanding-webhooks\n      - type: TechnicalRequirements\n        url: https://developers.cvent.com/docs/webhooks/technical-requirements\n\
  common:\n  - type: Website\n    url: https://www.cvent.com/en/event-management-software/online-registration-software\n  - type: DeveloperPortal\n    url: https://developers.cvent.com/\n  - type: APIReference\n    url: https://developers.cvent.com/docs/rest-api/reference/reference\n  - type: Authentication\n    url: https://developers.cvent.com/docs/rest-api/explanation/authentication\n  - type: OAuthTokenEndpoint\n    url: https://api-platform.cvent.com/ea/oauth2/token\n  - type: Status\n    url: https://status.cvent.com/\n  - type: Support\n    url: https://support.cvent.com/\n  - type: Pricing\n    url: https://www.cvent.com/en/pricing\n  - type: TermsOfService\n    url: https://www.cvent.com/en/terms-of-service\n  - type: PrivacyPolicy\n    url: https://www.cvent.com/en/privacy-policy\n  - type: Twitter\n    url: https://twitter.com/cvent\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/cvent/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cvent-registration/refs/heads/main/apis.yml
tags:
- Attendee Management
- Attendees
- Conferences
- Event Management
- Events
- OAuth 2.0
- On-Site Check-In
- Payments
- Registration
- REST API
- Ticketing
- Webhooks
url: https://raw.githubusercontent.com/api-evangelist/cvent-registration/refs/heads/main/apis.yml
use_cases: []
---
