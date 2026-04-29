---
api_count: 9
apis:
- description: The unified Cvent Platform REST API providing programmatic access to events, contacts, registrations, attendees, sessions, speakers, exhibitors, surveys, webhooks, and Attendee Hub resources. OAuth 2.
  name: Cvent REST API
  slug: rest-api
- description: Cvent Webhooks notify external applications when actions occur in Cvent and send relevant data to a specified URL, automatically pushing event, attendee, speaker, and meeting request data to subscribe
  name: Cvent Webhooks API
  slug: webhooks
- description: The Cvent Supplier Network (CSN) API provides integration with a database of 280,000+ hotels, suppliers, and destinations worldwide. Planners search and compare venues and manage RFPs; suppliers creat
  name: Cvent Supplier Network (CSN) API
  slug: csn-api
- description: Passkey RegLink APIs are RESTful JSON APIs (with legacy URL-based and SOAP options) connecting Cvent registration with Passkey hotel reservations. Send registrant info, fetch event and hotel availabil
  name: Cvent Passkey RegLink API
  slug: passkey-reglink
- description: The Cvent SOAP API is the original legacy API for pushing and pulling data between Cvent and internal systems. Supports contact and event management, custom fields, address book, and metadata. Being s
  name: Cvent SOAP API (Legacy)
  slug: soap-api
- description: The Cvent Custom Widgets API allows developers to build custom interactive widgets for Cvent Event Registration pages. SDK for widget elements, configuration files, and navigation methods.
  name: Cvent Custom Widgets API
  slug: custom-widgets
- description: Cvent SSO enables identity provider integration via SAML and OpenID Connect for planner login, access portals, event registrant and Attendee Hub, Events+, and portal applications.
  name: Cvent Single Sign-On (SSO) Integration
  slug: sso
- description: The Cvent White Label API enables venues and suppliers to embed Cvent RFP functionality into their own websites with custom branding, theming, and analytics for embedded RFP forms.
  name: Cvent White Label API
  slug: white-label
- description: The Cvent Salesforce App integrates Cvent event data with Salesforce CRM, enabling users to view events from Salesforce, invite contacts and leads, and sync attendee data bidirectionally.
  name: Cvent Salesforce App
  slug: salesforce-app
common:
- title: ''
  type: Website
  url: https://www.cvent.com/
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
  type: SignUp
  url: https://developers.cvent.com/register
- title: ''
  type: Standards
  url: https://developers.cvent.com/docs/rest-api/reference/api-standards
- title: ''
  type: ChangeLog
  url: https://developers.cvent.com/docs/rest-api/changelog
- title: ''
  type: Status
  url: https://status.cvent.com
- title: ''
  type: Support
  url: https://support.cvent.com/
- title: ''
  type: Pricing
  url: https://www.cvent.com/en/event-management-software/cvent-pricing
- title: ''
  type: TermsOfService
  url: https://www.cvent.com/en/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.cvent.com/en/privacy-policy
- title: ''
  type: Security
  url: https://www.cvent.com/en/security
- title: ''
  type: Training
  url: https://www.cvent.com/en/academy
- title: ''
  type: Community
  url: https://community.cvent.com/home
- title: ''
  type: Blog
  url: https://www.cvent.com/en/blog
- title: ''
  type: GitHub
  url: https://github.com/cvent
- title: ''
  type: Twitter
  url: https://twitter.com/cvent
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/cvent
created: '2025-11-19'
description: Cvent is a leading meetings, events, and hospitality technology provider with over 4,800 employees and 22,000+ customers worldwide. The Cvent platform spans Event Cloud (event management, registration, mobile event apps, virtual and hybrid events, Attendee Hub, surveys, Diagramming, and analytics) and Hospitality Cloud (Cvent Supplier Network, Passkey, Venue Sourcing, and Sales & Catering). Programmatic access is delivered through the unified Cvent Platform REST API (api-platform.cvent.com) using OAuth 2.0 client credentials, with legacy SOAP, BadgeKit, Jifflenow, and CSN APIs documented for historical integrations. The developer portal at developers.cvent.com hosts API references, guides, OpenAPI downloads, webhooks, SSO, custom widgets, white-label, and integration documentation.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Cvent
skills: []
slug: cvent
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cvent\nname: Cvent\nx-type: company\ndescription: >-\n  Cvent is a leading meetings, events, and hospitality technology\n  provider with over 4,800 employees and 22,000+ customers worldwide.\n  The Cvent platform spans Event Cloud (event management, registration,\n  mobile event apps, virtual and hybrid events, Attendee Hub, surveys,\n  Diagramming, and analytics) and Hospitality Cloud (Cvent Supplier\n  Network, Passkey, Venue Sourcing, and Sales & Catering). Programmatic\n  access is delivered through the unified Cvent Platform REST API\n  (api-platform.cvent.com) using OAuth 2.0 client credentials, with\n  legacy SOAP, BadgeKit, Jifflenow, and CSN APIs documented for\n  historical integrations. The developer portal at developers.cvent.com\n  hosts API references, guides, OpenAPI downloads, webhooks, SSO,\n  custom widgets, white-label, and integration documentation.\nurl: https://raw.githubusercontent.com/api-evangelist/cvent/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  type: Index\naccess: 3rd-Party\nposition: Consuming\ncreated: '2025-11-19'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntags:\n  - Attendee Hub\n  - Attendee Management\n  - Conferences\n  - Diagramming\n  - Event Management\n  - Event Marketing\n  - Events\n  - Exhibitors\n  - Hospitality\n  - Hospitality Cloud\n  - Hybrid Events\n  - Meetings\n  - OAuth 2.0\n  - Passkey\n  - Registration\n  - REST API\n  - SOAP API\n  - SSO\n  - Supplier Network\n  - Surveys\n  - Venue Management\n  - Venue Sourcing\n  - Virtual Events\n  - Webhooks\n  - White Label\napis:\n  - aid: cvent:rest-api\n    name: Cvent REST API\n    description: >-\n      The unified Cvent Platform REST API providing programmatic access\n      to events, contacts, registrations, attendees, sessions, speakers,\n      exhibitors, surveys, webhooks, and Attendee Hub resources. OAuth\n      2.0 client credentials with the token endpoint at\n      api-platform.cvent.com/ea/oauth2/token.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://developers.cvent.com/docs/rest-api/overview\n    baseURL: https://api-platform.cvent.com\n    tags:\n      - Attendees\n      - Contacts\n      - Events\n      - OAuth 2.0\n      - Registration\n      - REST\n      - Sessions\n      - Surveys\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/rest-api/overview\n      - type: APIReference\n        url: https://developers.cvent.com/docs/rest-api/reference/reference\n      - type: GettingStarted\n        url: https://developers.cvent.com/docs/rest-api/tutorials/developer-quickstart\n      - type: Concepts\n        url: https://developers.cvent.com/docs/rest-api/explanation/concepts\n      - type: ChangeLog\n        url: https://developers.cvent.com/docs/rest-api/changelog\n      - type: MigrationGuide\n        url: https://developers.cvent.com/docs/rest-api/migration-guide/benefits\n  - aid: cvent:webhooks\n    name: Cvent Webhooks API\n    description: >-\n\
  \      Cvent Webhooks notify external applications when actions occur in\n      Cvent and send relevant data to a specified URL, automatically\n      pushing event, attendee, speaker, and meeting request data to\n      subscriber endpoints for real-time integration.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.cvent.com/docs/webhooks/overview\n    tags:\n      - Attendees\n      - Events\n      - Notifications\n      - Sessions\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/webhooks/overview\n      - type: Guide\n        url: https://developers.cvent.com/docs/webhooks/understanding-webhooks\n      - type: GettingStarted\n        url: https://developers.cvent.com/docs/webhooks/tutorials/account-setup\n      - type: TechnicalRequirements\n        url: https://developers.cvent.com/docs/webhooks/technical-requirements\n  - aid: cvent:csn-api\n    name:\
  \ Cvent Supplier Network (CSN) API\n    description: >-\n      The Cvent Supplier Network (CSN) API provides integration with a\n      database of 280,000+ hotels, suppliers, and destinations\n      worldwide. Planners search and compare venues and manage RFPs;\n      suppliers create and update proposals via a push-pull workflow.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.cvent.com/docs/legacy-api/csn/overview\n    tags:\n      - Hospitality\n      - Proposals\n      - RFP\n      - Suppliers\n      - Venues\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/legacy-api/csn/overview\n      - type: PlannerGuide\n        url: https://developers.cvent.com/docs/legacy-api/csn/planner-guide/overview\n      - type: SupplierGuide\n        url: https://developers.cvent.com/docs/legacy-api/csn/supplier-guide/authentication\n  - aid: cvent:passkey-reglink\n    name: Cvent Passkey\
  \ RegLink API\n    description: >-\n      Passkey RegLink APIs are RESTful JSON APIs (with legacy URL-based\n      and SOAP options) connecting Cvent registration with Passkey\n      hotel reservations. Send registrant info, fetch event and hotel\n      availability, retrieve reservations, and create / update / cancel\n      hotel bookings.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.cvent.com/docs/passkey/REST/overview\n    tags:\n      - Accommodations\n      - Hotels\n      - Registration\n      - Reservations\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/passkey/REST/overview\n      - type: GettingStarted\n        url: https://developers.cvent.com/docs/passkey/REST/getting-started\n      - type: Callbacks\n        url: https://developers.cvent.com/docs/passkey/REST/callbacks\n      - type: FAQ\n        url: https://developers.cvent.com/docs/passkey/REST/faq\n\
  \  - aid: cvent:soap-api\n    name: Cvent SOAP API (Legacy)\n    description: >-\n      The Cvent SOAP API is the original legacy API for pushing and\n      pulling data between Cvent and internal systems. Supports contact\n      and event management, custom fields, address book, and metadata.\n      Being sunset in favor of the REST API.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.cvent.com/docs/legacy-api/soap-api/overview\n    tags:\n      - Contacts\n      - Deprecated\n      - Events\n      - Legacy\n      - Registration\n      - SOAP\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/legacy-api/soap-api/overview\n      - type: APIReference\n        url: https://developers.cvent.com/docs/legacy-api/soap-api/call-definitions/overview\n      - type: ObjectDefinitions\n        url: https://developers.cvent.com/docs/legacy-api/soap-api/object-definitions/overview\n \
  \     - type: MigrationGuide\n        url: https://developers.cvent.com/docs/rest-api/migration-guide/benefits\n  - aid: cvent:custom-widgets\n    name: Cvent Custom Widgets API\n    description: >-\n      The Cvent Custom Widgets API allows developers to build custom\n      interactive widgets for Cvent Event Registration pages. SDK for\n      widget elements, configuration files, and navigation methods.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.cvent.com/docs/custom-widgets/overview\n    tags:\n      - Customization\n      - Embedding\n      - Registration\n      - Widgets\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/custom-widgets/overview\n      - type: GitHubRepository\n        url: https://github.com/cvent/custom-widgets-labs\n  - aid: cvent:sso\n    name: Cvent Single Sign-On (SSO) Integration\n    description: >-\n      Cvent SSO enables identity provider\
  \ integration via SAML and\n      OpenID Connect for planner login, access portals, event\n      registrant and Attendee Hub, Events+, and portal applications.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.cvent.com/docs/sso/overview\n    tags:\n      - Authentication\n      - Identity\n      - OpenID Connect\n      - SAML\n      - SSO\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/sso/overview\n      - type: Concepts\n        url: https://developers.cvent.com/docs/sso/explanation/concepts\n  - aid: cvent:white-label\n    name: Cvent White Label API\n    description: >-\n      The Cvent White Label API enables venues and suppliers to embed\n      Cvent RFP functionality into their own websites with custom\n      branding, theming, and analytics for embedded RFP forms.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL:\
  \ https://developers.cvent.com/docs/white-label/overview\n    tags:\n      - Branding\n      - RFP\n      - White Label\n      - Widgets\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/white-label/overview\n  - aid: cvent:salesforce-app\n    name: Cvent Salesforce App\n    description: >-\n      The Cvent Salesforce App integrates Cvent event data with\n      Salesforce CRM, enabling users to view events from Salesforce,\n      invite contacts and leads, and sync attendee data bidirectionally.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.cvent.com/docs/cvent-salesforce-app/overview\n    tags:\n      - CRM\n      - Events\n      - Integration\n      - Salesforce\n    properties:\n      - type: Documentation\n        url: https://developers.cvent.com/docs/cvent-salesforce-app/overview\n      - type: GettingStarted\n        url: https://developers.cvent.com/docs/cvent-salesforce-app/app-installation\n\
  \      - type: Authentication\n        url: https://developers.cvent.com/docs/cvent-salesforce-app/salesforce-oauth\ncommon:\n  - type: Website\n    url: https://www.cvent.com/\n  - type: DeveloperPortal\n    url: https://developers.cvent.com/\n  - type: APIReference\n    url: https://developers.cvent.com/docs/rest-api/reference/reference\n  - type: Authentication\n    url: https://developers.cvent.com/docs/rest-api/explanation/authentication\n  - type: OAuthTokenEndpoint\n    url: https://api-platform.cvent.com/ea/oauth2/token\n  - type: SignUp\n    url: https://developers.cvent.com/register\n  - type: Standards\n    url: https://developers.cvent.com/docs/rest-api/reference/api-standards\n  - type: ChangeLog\n    url: https://developers.cvent.com/docs/rest-api/changelog\n  - type: Status\n    url: https://status.cvent.com\n  - type: Support\n    url: https://support.cvent.com/\n  - type: Pricing\n    url: https://www.cvent.com/en/event-management-software/cvent-pricing\n  - type: TermsOfService\n\
  \    url: https://www.cvent.com/en/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.cvent.com/en/privacy-policy\n  - type: Security\n    url: https://www.cvent.com/en/security\n  - type: Training\n    url: https://www.cvent.com/en/academy\n  - type: Community\n    url: https://community.cvent.com/home\n  - type: Blog\n    url: https://www.cvent.com/en/blog\n  - type: GitHub\n    url: https://github.com/cvent\n  - type: Twitter\n    url: https://twitter.com/cvent\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/cvent\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n  - FN: Cvent Developer Relations\n    email: developersupport@cvent.com\n    url: https://developers.cvent.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cvent/refs/heads/main/apis.yml
tags:
- Attendee Hub
- Attendee Management
- Conferences
- Diagramming
- Event Management
- Event Marketing
- Events
- Exhibitors
- Hospitality
- Hospitality Cloud
- Hybrid Events
- Meetings
- OAuth 2.0
- Passkey
- Registration
- REST API
- SOAP API
- SSO
- Supplier Network
- Surveys
- Venue Management
- Venue Sourcing
- Virtual Events
- Webhooks
- White Label
url: https://raw.githubusercontent.com/api-evangelist/cvent/refs/heads/main/apis.yml
use_cases: []
---
