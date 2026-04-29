---
api_count: 2
apis:
- description: The Cvent Platform REST API is the unified RESTful interface across the Event Cloud product line, providing programmatic access to events, contacts, registrations, attendees, sessions, speakers, exhib
  name: Cvent Platform REST API
  slug: rest-api
- description: Passkey RegLink APIs are RESTful JSON APIs (with legacy URL-based and SOAP options) connecting Cvent with external registration and reservation applications. Primary functions include streamlining the
  name: Cvent Passkey RegLink API
  slug: passkey-reglink
common:
- title: ''
  type: Website
  url: https://www.cvent.com/
- title: ''
  type: DeveloperPortal
  url: https://developers.cvent.com/
- title: ''
  type: APIReference
  url: https://developers.cvent.com/docs/rest-api/overview
- title: ''
  type: Authentication
  url: https://developers.cvent.com/docs/rest-api
- title: ''
  type: OAuthTokenEndpoint
  url: https://api-platform.cvent.com/ea/oauth2/token
- title: ''
  type: SupportArticles
  url: https://support.cvent.com/
- title: ''
  type: Status
  url: https://status.cvent.com/
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
  type: Blog
  url: https://www.cvent.com/blog
- title: ''
  type: Twitter
  url: https://twitter.com/cvent
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/cvent/
created: '2024-01-01'
description: 'Cvent is a leading meetings, events, and hospitality technology provider serving more than 22,000 customers worldwide. The Cvent Platform spans two product groups: Event Cloud (event management, registration, mobile event apps, virtual and hybrid events, Attendee Hub, surveys, and analytics) and Hospitality Cloud (Cvent Supplier Network, Passkey hotel room block management, Venue Sourcing, and Sales & Catering). Programmatic access is delivered through the Cvent Platform REST API protected by OAuth 2.0 client credentials, with the token endpoint at api-platform.cvent.com/ea/oauth2/token. Earlier integrations also use legacy XML SOAP / RegLink web services. The developer portal at developers.cvent.com hosts API references, guides, and OpenAPI downloads.'
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Cvent Platform
skills: []
slug: cvent-platform
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cvent-platform\nname: Cvent Platform\nx-type: company\ndescription: >-\n  Cvent is a leading meetings, events, and hospitality technology\n  provider serving more than 22,000 customers worldwide. The Cvent\n  Platform spans two product groups: Event Cloud (event management,\n  registration, mobile event apps, virtual and hybrid events,\n  Attendee Hub, surveys, and analytics) and Hospitality Cloud (Cvent\n  Supplier Network, Passkey hotel room block management, Venue\n  Sourcing, and Sales & Catering). Programmatic access is delivered\n  through the Cvent Platform REST API protected by OAuth 2.0 client\n  credentials, with the token endpoint at\n  api-platform.cvent.com/ea/oauth2/token. Earlier integrations also\n  use legacy XML SOAP / RegLink web services. The developer portal at\n  developers.cvent.com hosts API references, guides, and OpenAPI\n  downloads.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cvent-platform/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  type: Index\naccess: 3rd-Party\nposition: Consuming\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntags:\n  - Attendee Hub\n  - Conferences\n  - Event Management\n  - Event Marketing\n  - Events\n  - Hospitality\n  - Hospitality Cloud\n  - Hybrid Events\n  - Meetings\n  - OAuth 2.0\n  - Passkey\n  - Registration\n  - REST API\n  - Supplier Network\n  - Surveys\n  - Venue Management\n  - Virtual Events\napis:\n  - aid: cvent-platform:rest-api\n    name: Cvent Platform REST API\n    description: >-\n      The Cvent Platform REST API is the unified RESTful interface\n      across the Event Cloud product line, providing programmatic\n      access to events, contacts, registrations, attendees, sessions,\n      speakers, exhibitors, surveys, webhooks, and Attendee Hub\n      resources. The API uses OAuth 2.0 client credentials. Authorization\n      code flow is available to planner administrators. Developers can\n      download the OpenAPI specification from the\
  \ API reference.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.cvent.com/docs/rest-api/overview\n    baseURL: https://api-platform.cvent.com\n    tags:\n      - Attendees\n      - Contacts\n      - Events\n      - OAuth 2.0\n      - Registration\n      - REST\n      - Sessions\n      - Surveys\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/rest-api/overview\n      - type: Concepts\n        url: https://developers.cvent.com/docs/rest-api\n      - type: Guides\n        url: https://developers.cvent.com/docs/rest-api/guides/rest-guides\n      - type: MigrationGuide\n        url: https://developers.cvent.com/docs/rest-api/migration-guide/benefits\n      - type: RegistrationGuide\n        url: https://developers.cvent.com/docs/rest-api/guides/registration-guide\n      - type: OAuthTokenEndpoint\n        url: https://api-platform.cvent.com/ea/oauth2/token\n\
  \  - aid: cvent-platform:passkey-reglink\n    name: Cvent Passkey RegLink API\n    description: >-\n      Passkey RegLink APIs are RESTful JSON APIs (with legacy URL-based\n      and SOAP options) connecting Cvent with external registration and\n      reservation applications. Primary functions include streamlining\n      the hotel reservation process by sending registrant information\n      to Passkey, fetching event details and hotel room availability,\n      retrieving reservation information, and creating, updating, and\n      cancelling registrant hotel reservations.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.cvent.com/docs/passkey/REST/overview\n    baseURL: https://api-platform.cvent.com\n    tags:\n      - Group Bookings\n      - Hotel\n      - Passkey\n      - Reservations\n      - Room Blocks\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/passkey/REST/overview\n\
  \      - type: GettingStarted\n        url: https://developers.cvent.com/docs/passkey/REST/getting-started\n      - type: PasskeyDocs\n        url: https://developers.cvent.com/doc/passkey/\ncommon:\n  - type: Website\n    url: https://www.cvent.com/\n  - type: DeveloperPortal\n    url: https://developers.cvent.com/\n  - type: APIReference\n    url: https://developers.cvent.com/docs/rest-api/overview\n  - type: Authentication\n    url: https://developers.cvent.com/docs/rest-api\n  - type: OAuthTokenEndpoint\n    url: https://api-platform.cvent.com/ea/oauth2/token\n  - type: SupportArticles\n    url: https://support.cvent.com/\n  - type: Status\n    url: https://status.cvent.com/\n  - type: Pricing\n    url: https://www.cvent.com/en/pricing\n  - type: TermsOfService\n    url: https://www.cvent.com/en/terms-of-service\n  - type: PrivacyPolicy\n    url: https://www.cvent.com/en/privacy-policy\n  - type: Blog\n    url: https://www.cvent.com/blog\n  - type: Twitter\n    url: https://twitter.com/cvent\n\
  \  - type: LinkedIn\n    url: https://www.linkedin.com/company/cvent/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cvent-platform/refs/heads/main/apis.yml
tags:
- Attendee Hub
- Conferences
- Event Management
- Event Marketing
- Events
- Hospitality
- Hospitality Cloud
- Hybrid Events
- Meetings
- OAuth 2.0
- Passkey
- Registration
- REST API
- Supplier Network
- Surveys
- Venue Management
- Virtual Events
url: https://raw.githubusercontent.com/api-evangelist/cvent-platform/refs/heads/main/apis.yml
use_cases: []
---
