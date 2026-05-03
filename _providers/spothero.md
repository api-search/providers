---
api_count: 2
api_specs:
- filename: spothero-parking-openapi.yml
  format: yaml
  label: SpotHero Parking API
  slug: spothero-parking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spothero/refs/heads/main/openapi/spothero-parking-openapi.yml
apis:
- description: The SpotHero Parking API provides programmatic access to the largest network of off-street parking facilities in North America. Partners can search for available parking spots, check real-time availab
  name: SpotHero Parking API
  slug: spothero-parking-api
- description: SpotNow is SpotHero's server and API built in Kotlin for real-time parking availability and instant booking functionality, exposed via the HeroLab platform.
  name: SpotHero SpotNow API
  slug: spotnow-api
capabilities:
- description: Unified parking mobility workflow capability for SpotHero, enabling navigation apps, rideshare platforms, connected car dashboards, and event management systems to search, book, and manage parking res
  name: SpotHero Parking Mobility
  slug: parking-mobility
common:
- title: ''
  type: Documentation
  url: https://spothero.com/developers
- title: ''
  type: Developer Portal
  url: https://api.spothero.com/v2/docs
- title: ''
  type: Terms of Service
  url: https://spothero.com/terms
- title: ''
  type: Privacy Policy
  url: https://spothero.com/privacy
- title: ''
  type: Website
  url: https://spothero.com
- title: ''
  type: Contact
  url: mailto:partner.support@spothero.com
- title: ''
  type: JSONSchema
  url: json-schema/spothero-reservation-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/spothero-facility-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/spothero-reservation-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/spothero-facility-structure.json
- title: ''
  type: JSONLD
  url: json-ld/spothero-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/spothero-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/parking-mobility.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/spothero-vocabulary.yml
created: '2025-02-06'
description: SpotHero is the leading digital parking marketplace in North America, offering a flexible parking API and developer toolkit that connects vehicles, drivers, and mobility apps with the largest network of off-street parking facilities. The platform enables navigation apps, rideshare services, connected cars, and enterprise fleets to seamlessly book and manage parking reservations. SpotHero was acquired by Uber in 2026 to power parking reservation experiences within the Uber app.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 38
  name: Spothero Context
  property_count: 0
  slug: spothero-context
layout: provider
modified: '2026-05-02'
name: SpotHero
rules:
- name: SpotHero API Rules
  rule_count: 14
  severity_counts:
    error: 6
    hint: 0
    info: 1
    warn: 7
  slug: spothero-rules
skills: []
slug: spothero
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spothero\nname: SpotHero\ndescription: >-\n  SpotHero is the leading digital parking marketplace in North America, offering a flexible parking\n  API and developer toolkit that connects vehicles, drivers, and mobility apps with the largest\n  network of off-street parking facilities. The platform enables navigation apps, rideshare services,\n  connected cars, and enterprise fleets to seamlessly book and manage parking reservations. SpotHero\n  was acquired by Uber in 2026 to power parking reservation experiences within the Uber app.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Parking\n  - Mobility\n  - Transportation\n  - Navigation\n  - Reservations\ncreated: '2025-02-06'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/spothero/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: spothero:spothero-parking-api\n \
  \   name: SpotHero Parking API\n    description: >-\n      The SpotHero Parking API provides programmatic access to the largest network of off-street\n      parking facilities in North America. Partners can search for available parking spots, check\n      real-time availability, create and manage reservations, and access facility details including\n      pricing, amenities, and directions. The API supports navigation apps, mobility platforms,\n      connected car dashboards, event ticketing systems, and enterprise fleet management solutions.\n      SpotHero covers 400+ cities with 8,000+ parking locations and has facilitated 100M+ parking\n      reservations.\n    humanURL: https://spothero.com/developers\n    baseURL: https://api.spothero.com/v2\n    tags:\n      - Parking\n      - Reservations\n      - Availability\n      - Mobility\n      - Navigation\n    properties:\n      - type: Documentation\n        url: https://spothero.com/developers\n      - type: Developer Portal\n       \
  \ url: https://api.spothero.com/v2/docs\n      - type: Getting Started\n        url: https://spothero.com/developers\n      - type: OpenAPI\n        url: openapi/spothero-parking-openapi.yml\n    contact:\n      - FN: SpotHero Partner Support\n        email: partner.support@spothero.com\n    features:\n      - type: ParkingSearch\n        description: Search for available parking by location, date, time, and vehicle type\n      - type: RealTimeAvailability\n        description: Real-time availability checks across 8,000+ parking facilities\n      - type: Reservations\n        description: Create, modify, and cancel parking reservations\n      - type: FacilityDetails\n        description: Access facility amenities, pricing, hours, and directions\n      - type: BrandedExperience\n        description: White-label integration with custom branding and logo on parking passes\n      - type: WebWidget\n        description: Copy-and-paste web widget for website integration\n      - type: ParkingLink\n\
  \        description: Deep-link routing to SpotHero app or web for minimal-development integrations\n    useCases:\n      - type: UrbanMobility\n        description: Last-mile parking solutions for rideshare, transit, and navigation apps\n      - type: ConnectedCar\n        description: In-vehicle parking search and reservation from car dashboards\n      - type: EventParking\n        description: Pre-book parking for venues, stadiums, and events\n      - type: FleetManagement\n        description: Enterprise parking management for corporate fleets\n      - type: CarshareRental\n        description: Parking integration for carshare and rental fleet services\n    integrations:\n      - type: AppleMaps\n        url: https://developer.apple.com/maps/\n      - type: Uber\n        url: https://developer.uber.com/\n      - type: Cordova\n        url: https://github.com/spothero/cordova-plugin-spothero\n    solutions:\n      - type: ParkingMarketplace\n        description: Access to North America's\
  \ largest off-street parking network\n      - type: DeveloperToolkit\n        description: API, SDK, Web Widget, and Parking Link routing tools for all integration needs\n  - aid: spothero:spotnow-api\n    name: SpotHero SpotNow API\n    description: >-\n      SpotNow is SpotHero's server and API built in Kotlin for real-time parking availability\n      and instant booking functionality, exposed via the HeroLab platform.\n    humanURL: https://github.com/spothero/herolab-spotnow\n    baseURL: https://api.spothero.com\n    tags:\n      - Parking\n      - Real-Time\n      - Availability\n      - Kotlin\n    properties:\n      - type: Repository\n        url: https://github.com/spothero/herolab-spotnow\ncommon:\n  - type: Documentation\n    url: https://spothero.com/developers\n  - type: Developer Portal\n    url: https://api.spothero.com/v2/docs\n  - type: Terms of Service\n    url: https://spothero.com/terms\n  - type: Privacy Policy\n    url: https://spothero.com/privacy\n  - type: Website\n\
  \    url: https://spothero.com\n  - type: Contact\n    url: mailto:partner.support@spothero.com\n  - type: JSONSchema\n    url: json-schema/spothero-reservation-schema.json\n  - type: JSONSchema\n    url: json-schema/spothero-facility-schema.json\n  - type: JSONStructure\n    url: json-structure/spothero-reservation-structure.json\n  - type: JSONStructure\n    url: json-structure/spothero-facility-structure.json\n  - type: JSONLD\n    url: json-ld/spothero-context.jsonld\n  - type: SpectralRules\n    url: rules/spothero-rules.yml\n  - type: Capabilities\n    url: capabilities/parking-mobility.yaml\n  - type: Vocabulary\n    url: vocabulary/spothero-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spothero/refs/heads/main/apis.yml
tags:
- Parking
- Mobility
- Transportation
- Navigation
- Reservations
url: https://raw.githubusercontent.com/api-evangelist/spothero/refs/heads/main/apis.yml
use_cases: []
---
