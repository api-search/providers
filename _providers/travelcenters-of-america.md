---
api_count: 1
api_specs:
- filename: travelcenters-of-america-openapi.yml
  format: yaml
  label: TravelCenters of America API
  slug: travelcenters-of-america
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/travelcenters-of-america/refs/heads/main/openapi/travelcenters-of-america-openapi.yml
apis:
- description: REST APIs for TA and Petro travel center operations including truck service work order management, retail location data, fuel codes, pricing, parking, and shower availability across the largest US tra
  name: TravelCenters of America API
  slug: travelcenters-of-america
capabilities:
- description: Workflow capability for fleet operators and professional truck drivers using TravelCenters of America (TA/Petro) locations. Covers location discovery, parking and shower availability, fuel pricing, tr
  name: TravelCenters of America Fleet and Driver Services
  slug: fleet-and-driver-services
common:
- title: ''
  type: Website
  url: https://www.ta-petro.com/
- title: ''
  type: Documentation
  url: https://developer.accessta.com/
- title: ''
  type: Developers
  url: https://www.ta-petro.com/developers/
- title: ''
  type: Sign Up
  url: https://services.accessta.com/APIRequest/DevApiRequest
created: '2026-03-24'
description: TravelCenters of America is the largest publicly traded full-service travel center network in the United States, operating under the TA, Petro Stopping Centers, and TA Express brands. The company provides REST APIs for truck service work order management, retail location data, fuel codes, pricing, parking availability, and shower availability.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 42
  name: Travelcenters Of America Context
  property_count: 0
  slug: travelcenters-of-america-context
layout: provider
modified: '2026-05-03'
name: TravelCenters of America
rules:
- name: TravelCenters of America API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 3
    info: 0
    warn: 4
  slug: travelcenters-of-america-rules
skills: []
slug: travelcenters-of-america
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: travelcenters-of-america\nname: TravelCenters of America\ndescription: >-\n  TravelCenters of America is the largest publicly traded full-service travel\n  center network in the United States, operating under the TA, Petro Stopping\n  Centers, and TA Express brands. The company provides REST APIs for truck\n  service work order management, retail location data, fuel codes, pricing,\n  parking availability, and shower availability.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Travel Centers\n  - Truck Service\n  - Retail\n  - Fuel\n  - Locations\n  - Trucking\n  - Fleet Management\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/travelcenters-of-america/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: travelcenters-of-america:travelcenters-of-america\n    name: TravelCenters of America API\n\
  \    description: >-\n      REST APIs for TA and Petro travel center operations including truck service\n      work order management, retail location data, fuel codes, pricing, parking,\n      and shower availability across the largest US travel center network.\n    humanURL: https://developer.accessta.com/\n    baseURL: https://api.accessta.com/v1\n    tags:\n      - Travel Centers\n      - Truck Service\n      - Retail\n      - Fuel\n      - Locations\n      - Trucking\n      - Fleet Management\n    properties:\n      - type: Documentation\n        url: https://developer.accessta.com/\n      - type: OpenAPI\n        url: openapi/travelcenters-of-america-openapi.yml\n      - type: JSONSchema\n        url: json-schema/travelcenters-of-america-location-schema.json\n      - type: JSONStructure\n        url: json-structure/travelcenters-of-america-location-structure.json\n      - type: JSONLD\n        url: json-ld/travelcenters-of-america-context.jsonld\n      - type: SpectralRules\n    \
  \    url: rules/travelcenters-of-america-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/fleet-and-driver-services.yaml\n      - type: Vocabulary\n        url: vocabulary/travelcenters-of-america-vocabulary.yml\n      - type: Sign Up\n        url: https://services.accessta.com/APIRequest/DevApiRequest\n      - type: Mobile App\n        url: https://apps.apple.com/us/app/trucksmart/id420579235\n    x-services:\n      - Location and Amenities Lookup\n      - Parking Availability\n      - Shower Availability\n      - Work Order Management\n      - Documentation Search and Retrieval\n      - Fuel Code Management\n      - Fuel Pricing\ncommon:\n  - type: Website\n    url: https://www.ta-petro.com/\n  - type: Documentation\n    url: https://developer.accessta.com/\n  - type: Developers\n    url: https://www.ta-petro.com/developers/\n  - type: Sign Up\n    url: https://services.accessta.com/APIRequest/DevApiRequest\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/travelcenters-of-america/refs/heads/main/apis.yml
tags:
- Travel Centers
- Truck Service
- Retail
- Fuel
- Locations
- Trucking
- Fleet Management
url: https://raw.githubusercontent.com/api-evangelist/travelcenters-of-america/refs/heads/main/apis.yml
use_cases: []
---
