---
api_count: 5
apis:
- description: 'The Lumen Developer Center publishes Lumen''s enterprise API catalog, including Location, Quote, Order (PX CreateOrder), Service Inventory, Billing, Outbound Notification, and Trouble Ticket APIs. All '
  name: Lumen Developer Center APIs
  slug: lumen-developer-center
- description: The Lumen API Marketplace is the enterprise catalog where partners and customers browse APIs, request credentials, and manage app-level OAuth client IDs for programmatic access to Lumen and legacy Cen
  name: Lumen API Marketplace
  slug: lumen-api-marketplace
- description: The Level 3 / Lumen OpenAPI Services portal provides OpenAPI-described REST services such as the Lumen Location API that returns detailed service location information by locationId, along with referen
  name: Lumen OpenAPI Services (Level 3 legacy)
  slug: lumen-openapi-services
- description: The Public Sector API Center offers government-tailored REST APIs for Lumen network services, enabling federal, state, and local agencies to programmatically order, provision, and monitor connectivity
  name: Lumen Public Sector API Center
  slug: lumen-public-sector-api-center
- description: Quantum Fiber is Lumen's residential multi-gigabit fiber brand that supersedes CenturyLink in markets with fiber deployment, with account and service management exposed through consumer web and mobile
  name: Quantum Fiber Residential Services
  slug: quantum-fiber
common:
- title: ''
  type: Website
  url: https://www.centurylink.com
- title: ''
  type: Corporate
  url: https://www.lumen.com/
- title: ''
  type: Developer
  url: https://developer.lumen.com/
- title: ''
  type: APIMarketplace
  url: https://apimarketplace.lumen.com/
- title: ''
  type: LegacyDeveloper
  url: https://developer.centurylink.com/apis
- title: ''
  type: Documentation
  url: https://docs.lumen.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/centurylink
- title: ''
  type: QuantumFiber
  url: https://www.quantumfiber.com/
created: '2026-03-23'
description: CenturyLink is the residential broadband and home services brand of Lumen Technologies, a Fortune 500 telecommunications provider operating one of the largest fiber networks in North America. Following the Level 3 acquisition and rebrand to Lumen, CenturyLink's developer surface is exposed through the Lumen Developer Center and Lumen API Marketplace, which publish REST APIs secured by OAuth 2.0 for enterprise location qualification, quote-to-order, provisioning, billing, notifications, CDN and edge compute, DDoS mitigation, and Public Sector networking products.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: CenturyLink (Lumen Technologies)
skills: []
slug: centurylink
solutions: []
source_filename: apis.yml
source_yaml: "aid: centurylink\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/centurylink/refs/heads/main/apis.yml\nname: CenturyLink (Lumen Technologies)\ntags:\n  - Broadband\n  - Connectivity\n  - Edge\n  - Fiber\n  - Lumen\n  - Network\n  - OAuth 2.0\n  - Quantum Fiber\n  - SD-WAN\n  - Telecom\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-23'\nmodified: '2026-04-23'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  CenturyLink is the residential broadband and home services brand of Lumen\n  Technologies, a Fortune 500 telecommunications provider operating one of\n  the largest fiber networks in North America. Following the Level 3\n  acquisition and rebrand to Lumen, CenturyLink's developer surface is\n  exposed through the Lumen Developer Center and Lumen API Marketplace,\n  which publish REST APIs secured by OAuth 2.0 for enterprise location\n  qualification, quote-to-order,\
  \ provisioning, billing, notifications, CDN\n  and edge compute, DDoS mitigation, and Public Sector networking products.\napis:\n  - aid: centurylink:lumen-developer-center\n    name: Lumen Developer Center APIs\n    tags:\n      - Enterprise\n      - Lumen\n      - OAuth 2.0\n      - Partner\n      - REST\n    humanURL: https://developer.lumen.com/\n    properties:\n      - url: https://developer.lumen.com/\n        type: Website\n      - url: https://developer.lumen.com/apis\n        type: Reference\n      - url: https://developer.centurylink.com/apis\n        type: LegacyDeveloper\n      - url: https://developer-test.centurylink.com/content/using-oauth-20-access-lumen-apis\n        type: Authentication\n    description: >-\n      The Lumen Developer Center publishes Lumen's enterprise API catalog,\n      including Location, Quote, Order (PX CreateOrder), Service Inventory,\n      Billing, Outbound Notification, and Trouble Ticket APIs. All APIs use\n      OAuth 2.0 Client Credentials\
  \ and require Partner Developer Portal\n      registration and administrator enablement.\n  - aid: centurylink:lumen-api-marketplace\n    name: Lumen API Marketplace\n    tags:\n      - API Marketplace\n      - Enterprise\n      - Partner\n    humanURL: https://apimarketplace.lumen.com/\n    properties:\n      - url: https://apimarketplace.lumen.com/\n        type: Website\n      - url: https://apimarketplace.lumen.com/obtaining-user-credentials-access-centurylink-apis\n        type: Credentials\n    description: >-\n      The Lumen API Marketplace is the enterprise catalog where partners\n      and customers browse APIs, request credentials, and manage app-level\n      OAuth client IDs for programmatic access to Lumen and legacy\n      CenturyLink services.\n  - aid: centurylink:lumen-openapi-services\n    name: Lumen OpenAPI Services (Level 3 legacy)\n    tags:\n      - Connectivity\n      - Level 3\n      - Location\n      - OpenAPI\n    humanURL: https://developer.level3.com/documentation\n\
  \    properties:\n      - url: https://developer.level3.com/documentation\n        type: Documentation\n      - url: https://developer.level3.com/\n        type: Developer\n    description: >-\n      The Level 3 / Lumen OpenAPI Services portal provides OpenAPI-described\n      REST services such as the Lumen Location API that returns detailed\n      service location information by locationId, along with reference\n      specifications inherited from the Level 3 product family.\n  - aid: centurylink:lumen-public-sector-api-center\n    name: Lumen Public Sector API Center\n    tags:\n      - Federal\n      - Government\n      - Public Sector\n      - State and Local\n    humanURL: https://blog.centurylink.com/lumen-launches-public-sector-api-marketplace-which-offers-easy-to-use-apis/\n    properties:\n      - url: https://blog.centurylink.com/lumen-launches-public-sector-api-marketplace-which-offers-easy-to-use-apis/\n        type: Announcement\n      - url: https://www.lumen.com/en-us/solutions/public-sector.html\n\
  \        type: Solutions\n    description: >-\n      The Public Sector API Center offers government-tailored REST APIs for\n      Lumen network services, enabling federal, state, and local agencies\n      to programmatically order, provision, and monitor connectivity and\n      managed services.\n  - aid: centurylink:quantum-fiber\n    name: Quantum Fiber Residential Services\n    tags:\n      - Broadband\n      - Fiber\n      - Residential\n    humanURL: https://www.quantumfiber.com/\n    properties:\n      - url: https://www.quantumfiber.com/\n        type: Website\n      - url: https://www.centurylink.com/\n        type: LegacyBrand\n    description: >-\n      Quantum Fiber is Lumen's residential multi-gigabit fiber brand that\n      supersedes CenturyLink in markets with fiber deployment, with account\n      and service management exposed through consumer web and mobile apps\n      rather than a public developer API.\ncommon:\n  - type: Website\n    url: https://www.centurylink.com\n\
  \  - type: Corporate\n    url: https://www.lumen.com/\n  - type: Developer\n    url: https://developer.lumen.com/\n  - type: APIMarketplace\n    url: https://apimarketplace.lumen.com/\n  - type: LegacyDeveloper\n    url: https://developer.centurylink.com/apis\n  - type: Documentation\n    url: https://docs.lumen.com/\n  - type: GitHubOrganization\n    url: https://github.com/centurylink\n  - type: QuantumFiber\n    url: https://www.quantumfiber.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/centurylink/refs/heads/main/apis.yml
tags:
- Broadband
- Connectivity
- Edge
- Fiber
- Lumen
- Network
- OAuth 2.0
- Quantum Fiber
- SD-WAN
- Telecom
url: https://raw.githubusercontent.com/api-evangelist/centurylink/refs/heads/main/apis.yml
use_cases: []
---
