---
api_count: 6
api_specs:
- filename: marinetraffic-ais-openapi.yml
  format: yaml
  label: MarineTraffic AIS Vessel Tracking API
  slug: marinetraffic-ais-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/openapi/marinetraffic-ais-openapi.yml
apis:
- description: MarineTraffic AIS API provides real-time vessel position data from over 13,000 AIS receivers globally. Returns vessel positions, speeds, headings, and voyage information for fleet monitoring, port ope
  name: MarineTraffic AIS Vessel Tracking API
  slug: marinetraffic-ais-api
- description: MarineTraffic Real-time Events API delivers live updates on port calls, bunkering operations, ship-to-ship transfers, and other maritime events as they occur.
  name: MarineTraffic Real-time Events API
  slug: marinetraffic-real-time-events-api
- description: MarineTraffic Predictive Events API delivers predicted destinations, estimated time of arrivals (ETAs), and voyage forecasts using AI and AIS data analysis.
  name: MarineTraffic Predictive Events API
  slug: marinetraffic-predictive-events-api
- description: MarineTraffic Past Events API provides access to historical vessel movements and events, enabling retrospective analysis of shipping patterns, port call history, and voyage records.
  name: MarineTraffic Past Events API
  slug: marinetraffic-past-events-api
- description: MarineTraffic Ship Database API provides detailed information on vessel characteristics, ownership, photos, vessel type, flag state, dimensions, and technical specifications for ships worldwide.
  name: MarineTraffic Ship Database API
  slug: marinetraffic-ship-database-api
- description: MarineTraffic provides AIS (Automatic Identification System) vessel tracking APIs delivering real-time vessel positions, speeds, headings, destinations, and ETAs. The REST API returns XML-formatted AI
  name: MarineTraffic AIS Vessel Tracking API
  slug: marinetraffic-api
common:
- title: ''
  type: Portal
  url: https://www.kpler.com/product/maritime/data-services
- title: ''
  type: Documentation
  url: https://developers.kpler.com/
- title: ''
  type: TermsOfService
  url: https://www.kpler.com/company/terms-of-use
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/openapi/marinetraffic-ais-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/json-schema/marinetraffic-vessel-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/json-ld/marinetraffic-context.jsonld
created: '2026-03-18'
description: MarineTraffic, a Kpler company, is a global provider of vessel tracking and maritime intelligence data. The platform offers AIS-based real-time vessel positions, port calls, predictive ETAs, historical voyage data, and ship registry information used for fleet monitoring, port operations, and supply chain visibility.
features: []
image: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/image.png
integrations: []
jsonld:
- class_count: 7
  name: Marinetraffic Context
  property_count: 19
  slug: marinetraffic-context
layout: provider
modified: '2026-04-28'
name: MarineTraffic
skills: []
slug: marinetraffic
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: marinetraffic\nname: MarineTraffic\ndescription: >-\n  MarineTraffic, a Kpler company, is a global provider of vessel tracking and maritime\n  intelligence data. The platform offers AIS-based real-time vessel positions, port\n  calls, predictive ETAs, historical voyage data, and ship registry information used\n  for fleet monitoring, port operations, and supply chain visibility.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/image.png\ntags:\n  - AIS\n  - Maritime\n  - Shipping\n  - Vessel Tracking\ncreated: '2026-03-18'\nspecificationVersion: '0.19'\nurl: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/apis.yml\napis:\n  - aid: marinetraffic:marinetraffic-ais-api\n    name: MarineTraffic AIS Vessel Tracking API\n    tags:\n      - AIS\n      - Maritime\n      - Real-Time\n      - Shipping\n      - Vessel Tracking\n    image: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/image.png\n\
  \    humanURL: https://www.kpler.com/product/maritime/data-services\n    baseURL: https://services.marinetraffic.com/api\n    properties:\n      - url: https://www.kpler.com/product/maritime/data-services\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/openapi/marinetraffic-ais-openapi.yml\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/json-schema/marinetraffic-vessel-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/json-ld/marinetraffic-context.jsonld\n        type: JSONLDContext\n    description: >-\n      MarineTraffic AIS API provides real-time vessel position data from over 13,000\n      AIS receivers globally. Returns vessel positions, speeds, headings, and voyage\n      information for fleet monitoring, port operations, and supply chain visibility.\n  - aid:\
  \ marinetraffic:marinetraffic-real-time-events-api\n    name: MarineTraffic Real-time Events API\n    tags:\n      - Bunkering\n      - Events\n      - Maritime\n      - Port Calls\n    image: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/image.png\n    humanURL: https://www.kpler.com/product/maritime/data-services\n    baseURL: https://services.marinetraffic.com/api\n    properties:\n      - url: https://www.kpler.com/product/maritime/data-services\n        type: Documentation\n    description: >-\n      MarineTraffic Real-time Events API delivers live updates on port calls, bunkering\n      operations, ship-to-ship transfers, and other maritime events as they occur.\n  - aid: marinetraffic:marinetraffic-predictive-events-api\n    name: MarineTraffic Predictive Events API\n    tags:\n      - ETA\n      - Maritime\n      - Predictions\n      - Voyage Forecasting\n    image: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/image.png\n\
  \    humanURL: https://www.kpler.com/product/maritime/data-services\n    baseURL: https://services.marinetraffic.com/api\n    properties:\n      - url: https://www.kpler.com/product/maritime/data-services\n        type: Documentation\n    description: >-\n      MarineTraffic Predictive Events API delivers predicted destinations, estimated\n      time of arrivals (ETAs), and voyage forecasts using AI and AIS data analysis.\n  - aid: marinetraffic:marinetraffic-past-events-api\n    name: MarineTraffic Past Events API\n    tags:\n      - Historical\n      - Maritime\n      - Vessel Movements\n    image: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/image.png\n    humanURL: https://www.kpler.com/product/maritime/data-services\n    baseURL: https://services.marinetraffic.com/api\n    properties:\n      - url: https://www.kpler.com/product/maritime/data-services\n        type: Documentation\n    description: >-\n      MarineTraffic Past Events API provides access\
  \ to historical vessel movements\n      and events, enabling retrospective analysis of shipping patterns, port call\n      history, and voyage records.\n  - aid: marinetraffic:marinetraffic-ship-database-api\n    name: MarineTraffic Ship Database API\n    tags:\n      - Maritime\n      - Ship Registry\n      - Vessel Data\n    image: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/image.png\n    humanURL: https://www.kpler.com/product/maritime/data-services\n    baseURL: https://services.marinetraffic.com/api\n    properties:\n      - url: https://www.kpler.com/product/maritime/data-services\n        type: Documentation\n    description: >-\n      MarineTraffic Ship Database API provides detailed information on vessel characteristics,\n      ownership, photos, vessel type, flag state, dimensions, and technical specifications\n      for ships worldwide.\n  - aid: marinetraffic:marinetraffic-api\n    name: MarineTraffic AIS Vessel Tracking API\n    tags:\n\
  \      - AIS\n      - Maritime\n      - Shipping\n      - Vessel Tracking\n      - XML\n    image: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/image.png\n    humanURL: https://www.marinetraffic.com/en/ais-api-services\n    baseURL: https://services.marinetraffic.com/api\n    properties:\n      - url: https://www.marinetraffic.com/en/ais-api-services\n        type: Documentation\n    description: >-\n      MarineTraffic provides AIS (Automatic Identification System) vessel tracking\n      APIs delivering real-time vessel positions, speeds, headings, destinations,\n      and ETAs. The REST API returns XML-formatted AIS data for fleet monitoring,\n      port operations, and supply chain visibility.\ncommon:\n  - url: https://www.kpler.com/product/maritime/data-services\n    type: Portal\n  - url: https://developers.kpler.com/\n    type: Documentation\n  - url: https://www.kpler.com/company/terms-of-use\n    type: TermsOfService\n  - url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/openapi/marinetraffic-ais-openapi.yml\n\
  \    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/json-schema/marinetraffic-vessel-schema.json\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/json-ld/marinetraffic-context.jsonld\n    type: JSONLDContext\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nmodified: '2026-04-28'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/apis.yml
tags:
- AIS
- Maritime
- Shipping
- Vessel Tracking
url: https://raw.githubusercontent.com/api-evangelist/marinetraffic/refs/heads/main/apis.yml
use_cases: []
---
