---
api_count: 2
apis:
- description: Passkey RegLink APIs are RESTful JSON APIs (with legacy URL-based and SOAP options) that connect Cvent registration with Passkey hotel reservations. Primary functions include sending registrant inform
  name: Cvent Passkey RegLink API
  slug: passkey-reglink
- description: The unified Cvent Platform REST API also covers hospitality use cases including event-driven integrations, contact and attendee data exchange, and webhook-based notifications that can be wired into ho
  name: Cvent Platform REST API (Hospitality)
  slug: rest-api
common:
- title: ''
  type: Website
  url: https://www.cvent.com/en/hospitality-cloud
- title: ''
  type: SupplierNetwork
  url: https://www.cvent.com/en/hospitality-cloud/event-management/cvent-supplier-network
- title: ''
  type: Passkey
  url: https://www.cvent.com/en/hospitality-cloud/passkey
- title: ''
  type: DeveloperPortal
  url: https://developers.cvent.com/
- title: ''
  type: Support
  url: https://support.cvent.com/
- title: ''
  type: Status
  url: https://status.cvent.com/
- title: ''
  type: TermsOfService
  url: https://www.cvent.com/en/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.cvent.com/en/privacy-policy
created: '2024-01-01'
description: Cvent Hospitality Cloud is the hotel and venue product line of the Cvent Platform. It includes the Cvent Supplier Network (the marketplace connecting event planners with hotels and venues for RFPs and bookings), Passkey (hotel room block and housing management), Venue Sourcing (venue search and discovery), and Sales & Catering (booking management, catering, and contracts). Programmatic access is delivered primarily through the Passkey RegLink REST APIs (with legacy SOAP and URL-based options) and the unified Cvent Platform REST API. Authentication uses OAuth 2.0 client credentials with the token endpoint at api-platform.cvent.com/ea/oauth2/token.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Cvent Hospitality Cloud
skills: []
slug: cvent-hospitality-cloud
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cvent-hospitality-cloud\nname: Cvent Hospitality Cloud\nx-type: company\ndescription: >-\n  Cvent Hospitality Cloud is the hotel and venue product line of the\n  Cvent Platform. It includes the Cvent Supplier Network (the marketplace\n  connecting event planners with hotels and venues for RFPs and bookings),\n  Passkey (hotel room block and housing management), Venue Sourcing\n  (venue search and discovery), and Sales & Catering (booking management,\n  catering, and contracts). Programmatic access is delivered primarily\n  through the Passkey RegLink REST APIs (with legacy SOAP and URL-based\n  options) and the unified Cvent Platform REST API. Authentication uses\n  OAuth 2.0 client credentials with the token endpoint at\n  api-platform.cvent.com/ea/oauth2/token.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cvent-hospitality-cloud/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\naccess:\
  \ 3rd-Party\nposition: Consuming\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntags:\n  - Catering\n  - Group Bookings\n  - Hospitality\n  - Hospitality Cloud\n  - Hotels\n  - Housing\n  - OAuth 2.0\n  - Passkey\n  - Reservations\n  - RFP\n  - Room Blocks\n  - Sales\n  - Sourcing\n  - Supplier Network\n  - Venues\napis:\n  - aid: cvent-hospitality-cloud:passkey-reglink\n    name: Cvent Passkey RegLink API\n    description: >-\n      Passkey RegLink APIs are RESTful JSON APIs (with legacy URL-based\n      and SOAP options) that connect Cvent registration with Passkey\n      hotel reservations. Primary functions include sending registrant\n      information to Passkey to streamline hotel reservations, fetching\n      Passkey event and hotel availability, retrieving reservation\n      information, and creating, updating, and cancelling registrant\n      reservations.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  \
  \  humanURL: https://developers.cvent.com/docs/passkey/REST/overview\n    baseURL: https://api-platform.cvent.com\n    tags:\n      - Group Bookings\n      - Hotel\n      - Passkey\n      - Reservations\n      - Room Blocks\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/passkey/REST/overview\n      - type: GettingStarted\n        url: https://developers.cvent.com/docs/passkey/REST/getting-started\n      - type: PasskeyDocs\n        url: https://developers.cvent.com/doc/passkey/\n      - type: Product\n        url: https://www.cvent.com/en/hospitality-cloud/passkey\n  - aid: cvent-hospitality-cloud:rest-api\n    name: Cvent Platform REST API (Hospitality)\n    description: >-\n      The unified Cvent Platform REST API also covers hospitality\n      use cases including event-driven integrations, contact and\n      attendee data exchange, and webhook-based notifications that\n      can be wired into hotel and venue workflows. OAuth 2.0 client\n\
  \      credentials.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.cvent.com/docs/rest-api/overview\n    baseURL: https://api-platform.cvent.com\n    tags:\n      - Events\n      - OAuth 2.0\n      - REST\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/rest-api/overview\n      - type: Concepts\n        url: https://developers.cvent.com/docs/rest-api\n      - type: OAuthTokenEndpoint\n        url: https://api-platform.cvent.com/ea/oauth2/token\ncommon:\n  - type: Website\n    url: https://www.cvent.com/en/hospitality-cloud\n  - type: SupplierNetwork\n    url: https://www.cvent.com/en/hospitality-cloud/event-management/cvent-supplier-network\n  - type: Passkey\n    url: https://www.cvent.com/en/hospitality-cloud/passkey\n  - type: DeveloperPortal\n    url: https://developers.cvent.com/\n  - type: Support\n    url: https://support.cvent.com/\n  - type:\
  \ Status\n    url: https://status.cvent.com/\n  - type: TermsOfService\n    url: https://www.cvent.com/en/terms-of-service\n  - type: PrivacyPolicy\n    url: https://www.cvent.com/en/privacy-policy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cvent-hospitality-cloud/refs/heads/main/apis.yml
tags:
- Catering
- Group Bookings
- Hospitality
- Hospitality Cloud
- Hotels
- Housing
- OAuth 2.0
- Passkey
- Reservations
- RFP
- Room Blocks
- Sales
- Sourcing
- Supplier Network
- Venues
url: https://raw.githubusercontent.com/api-evangelist/cvent-hospitality-cloud/refs/heads/main/apis.yml
use_cases: []
---
