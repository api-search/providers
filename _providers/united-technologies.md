---
api_count: 1
api_specs:
- filename: united-technologies-arinc-messaging-openapi.yml
  format: yaml
  label: Collins Aerospace ARINC Messaging API
  slug: arinc-messaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-technologies/refs/heads/main/openapi/united-technologies-arinc-messaging-openapi.yml
apis:
- description: The Collins Aerospace ARINC Messaging API provides access to the ARINC Global Network for aviation messaging and data exchange. Supports ACARS, OOOI flight events, aviation weather, and operational co
  name: Collins Aerospace ARINC Messaging API
  slug: arinc-messaging-api
capabilities:
- description: Workflow capability for airline and airport aviation operations using the Collins Aerospace ARINC Digital Exchange platform. Combines aircraft messaging, flight tracking, and weather data to support o
  name: Collins Aerospace Aviation Operations
  slug: aviation-operations
common:
- title: ''
  type: Website
  url: https://www.rtx.com/collinsaerospace
- title: ''
  type: Portal
  url: https://arinconline.collinsaerospace.com
- title: ''
  type: Documentation
  url: https://www.rtx.com/collinsaerospace/what-we-do/industries/commercial-aviation/ground-operations/messaging-data-exchange
- title: ''
  type: SpectralRules
  url: rules/united-technologies-spectral-rules.yml
- title: Aviation Operations
  type: NaftikoCapability
  url: capabilities/aviation-operations.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/united-technologies-vocabulary.yaml
created: ''
description: United Technologies Corporation (UTC) was an American multinational conglomerate that merged with Raytheon Company in 2020 to form Raytheon Technologies, later renamed RTX Corporation in 2023. Prior to the merger, UTC's major subsidiaries included Otis Elevator (now independent), Carrier Global (now independent), Pratt & Whitney, and Collins Aerospace. Today, Collins Aerospace (formerly UTC Aerospace Systems and Rockwell Collins) provides aviation connectivity and data exchange services through the ARINC Digital Exchange platform, including messaging, flight operations, and weather data APIs for commercial aviation.
features:
- description: Industry-standard aviation communications network connecting aircraft, airlines, airports, and ground operations worldwide.
  name: ARINC Global Network
- description: Aircraft Communications Addressing and Reporting System messaging for digital communications between aircraft and ground.
  name: ACARS Messaging
- description: Real-time Out, Off, On, In flight event tracking for operational efficiency and on-time performance monitoring.
  name: OOOI Flight Events
- description: METARs, TAFs, SIGMETs, PIREPs, and graphical weather services for flight operations and dispatch.
  name: Aviation Weather Data
- description: Flexible integration platform deployable on-premise, SaaS, or in customer cloud for managing aviation data exchange.
  name: ARINC Integrator Platform
- description: InteliSight, GlobalConnect, and FlightHub platforms for comprehensive connected aircraft and ground operations.
  name: Connected Aircraft Solutions
- description: AviNet Airport and GLOBALink network infrastructure for airport ground operations and avionics connectivity.
  name: Airport Network Connectivity
image: ''
integrations:
- description: Collins Aerospace joined the Digital Alliance for Aviation powered by Airbus Skywise for predictive maintenance and health monitoring.
  name: Airbus Skywise
- description: ARINC flight operations data integrates with SAP IS-A for airline operations and financial management.
  name: SAP Aviation
- description: OOOI and flight status data integrates with Amadeus Altea CM for airline departure control and passenger services.
  name: Amadeus
- description: Complementary aviation communications network for shared messaging and airport data exchange services.
  name: SITA
jsonld:
- class_count: 8
  name: United Technologies Arinc Messaging Context
  property_count: 32
  slug: united-technologies-arinc-messaging-context
layout: provider
modified: '2026-05-03'
name: United Technologies
rules:
- name: United Technologies API Rules
  rule_count: 26
  severity_counts:
    error: 13
    hint: 0
    info: 3
    warn: 10
  slug: united-technologies-spectral-rules
skills: []
slug: united-technologies
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: united-technologies\nname: United Technologies\nurl: https://raw.githubusercontent.com/api-evangelist/united-technologies/refs/heads/main/apis.yml\ndescription: >-\n  United Technologies Corporation (UTC) was an American multinational conglomerate\n  that merged with Raytheon Company in 2020 to form Raytheon Technologies, later\n  renamed RTX Corporation in 2023. Prior to the merger, UTC's major subsidiaries\n  included Otis Elevator (now independent), Carrier Global (now independent), Pratt &\n  Whitney, and Collins Aerospace. Today, Collins Aerospace (formerly UTC Aerospace\n  Systems and Rockwell Collins) provides aviation connectivity and data exchange\n  services through the ARINC Digital Exchange platform, including messaging, flight\n  operations, and weather data APIs for commercial aviation.\nmodified: '2026-05-03'\ntags:\n  - Aerospace\n  - Defense\n  - Aviation\n  - Manufacturing\n  - Connectivity\napis:\n  - name: Collins Aerospace ARINC Messaging API\n   \
  \ description: >-\n      The Collins Aerospace ARINC Messaging API provides access to the ARINC Global\n      Network for aviation messaging and data exchange. Supports ACARS, OOOI flight\n      events, aviation weather, and operational communications between aircraft,\n      airlines, airports, and ground operations. Part of the Collins Aerospace ARINC\n      Digital Exchange platform.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.rtx.com/collinsaerospace/what-we-do/industries/commercial-aviation/ground-operations/messaging-data-exchange\n    baseURL: https://api.arinconline.collinsaerospace.com\n    tags:\n      - Aviation\n      - Messaging\n      - ACARS\n      - OOOI\n      - Aerospace\n    properties:\n      - type: Documentation\n        url: https://www.rtx.com/collinsaerospace/what-we-do/industries/commercial-aviation/ground-operations/messaging-data-exchange/arinc-messaging\n      - type: OpenAPI\n        url:\
  \ openapi/united-technologies-arinc-messaging-openapi.yml\n      - type: JSONSchema\n        url: json-schema/arinc-messaging-message-schema.json\n        title: Message Schema\n      - type: JSONSchema\n        url: json-schema/arinc-messaging-flight-schema.json\n        title: Flight Schema\n      - type: JSONStructure\n        url: json-structure/arinc-messaging-message-structure.json\n        title: Message Structure\n      - type: JSON-LD\n        url: json-ld/united-technologies-arinc-messaging-context.jsonld\n      - type: Example\n        url: examples/arinc-messaging-message-example.json\n        title: Message Example\n    aid: united-technologies:arinc-messaging-api\ncommon:\n  - type: Website\n    url: https://www.rtx.com/collinsaerospace\n  - type: Portal\n    url: https://arinconline.collinsaerospace.com\n  - type: Documentation\n    url: https://www.rtx.com/collinsaerospace/what-we-do/industries/commercial-aviation/ground-operations/messaging-data-exchange\n  - type: SpectralRules\n\
  \    url: rules/united-technologies-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/aviation-operations.yaml\n    title: Aviation Operations\n  - type: Vocabulary\n    url: vocabulary/united-technologies-vocabulary.yaml\n  - type: Features\n    data:\n      - name: ARINC Global Network\n        description: Industry-standard aviation communications network connecting aircraft, airlines, airports, and ground operations worldwide.\n      - name: ACARS Messaging\n        description: Aircraft Communications Addressing and Reporting System messaging for digital communications between aircraft and ground.\n      - name: OOOI Flight Events\n        description: Real-time Out, Off, On, In flight event tracking for operational efficiency and on-time performance monitoring.\n      - name: Aviation Weather Data\n        description: METARs, TAFs, SIGMETs, PIREPs, and graphical weather services for flight operations and dispatch.\n      - name: ARINC Integrator Platform\n \
  \       description: Flexible integration platform deployable on-premise, SaaS, or in customer cloud for managing aviation data exchange.\n      - name: Connected Aircraft Solutions\n        description: InteliSight, GlobalConnect, and FlightHub platforms for comprehensive connected aircraft and ground operations.\n      - name: Airport Network Connectivity\n        description: AviNet Airport and GLOBALink network infrastructure for airport ground operations and avionics connectivity.\n  - type: UseCases\n    data:\n      - name: Airline Operations Control\n        description: Monitor real-time flight status, OOOI events, and aircraft communications for dispatch and operations center workflows.\n      - name: Ground Operations Automation\n        description: Automate gate assignments, crew notifications, and turnaround communications using ACARS uplink messaging.\n      - name: Flight Dispatch\n        description: Access METARs, TAFs, and SIGMETs for pre-flight weather briefings and\
  \ in-flight weather monitoring.\n      - name: Maintenance MRO Integration\n        description: Receive ACARS maintenance messages and fault codes from aircraft for predictive maintenance workflows.\n      - name: Passenger Service Messaging\n        description: Send gate change and operational update messages to aircraft for cabin crew announcements.\n      - name: Airport Operations Management\n        description: Integrate OOOI flight data into airport management systems for terminal planning and resource allocation.\n  - type: Integrations\n    data:\n      - name: Airbus Skywise\n        description: Collins Aerospace joined the Digital Alliance for Aviation powered by Airbus Skywise for predictive maintenance and health monitoring.\n      - name: SAP Aviation\n        description: ARINC flight operations data integrates with SAP IS-A for airline operations and financial management.\n      - name: Amadeus\n        description: OOOI and flight status data integrates with Amadeus\
  \ Altea CM for airline departure control and passenger services.\n      - name: SITA\n        description: Complementary aviation communications network for shared messaging and airport data exchange services.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/united-technologies/refs/heads/main/apis.yml
tags:
- Aerospace
- Defense
- Aviation
- Manufacturing
- Connectivity
url: https://raw.githubusercontent.com/api-evangelist/united-technologies/refs/heads/main/apis.yml
use_cases:
- description: Monitor real-time flight status, OOOI events, and aircraft communications for dispatch and operations center workflows.
  name: Airline Operations Control
- description: Automate gate assignments, crew notifications, and turnaround communications using ACARS uplink messaging.
  name: Ground Operations Automation
- description: Access METARs, TAFs, and SIGMETs for pre-flight weather briefings and in-flight weather monitoring.
  name: Flight Dispatch
- description: Receive ACARS maintenance messages and fault codes from aircraft for predictive maintenance workflows.
  name: Maintenance MRO Integration
- description: Send gate change and operational update messages to aircraft for cabin crew announcements.
  name: Passenger Service Messaging
- description: Integrate OOOI flight data into airport management systems for terminal planning and resource allocation.
  name: Airport Operations Management
---
