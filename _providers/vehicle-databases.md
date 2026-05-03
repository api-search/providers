---
api_count: 1
api_specs:
- filename: vehicle-databases-openapi.yml
  format: yaml
  label: Vehicle Databases Maintenance API
  slug: vehicle-databases
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vehicle-databases/refs/heads/main/openapi/vehicle-databases-openapi.yml
apis:
- description: The Vehicle Databases Maintenance API delivers OEM-compliant maintenance schedules for vehicles up to 200,000 miles. Provides service intervals by mileage and time, service item descriptions, fluid sp
  name: Vehicle Databases Maintenance API
  slug: vehicle-databases
capabilities:
- description: Customer workflow capability for vehicle maintenance management. Combines VIN decoding, OEM maintenance schedule retrieval, service item lookup, NHTSA recall checks, and TSB lookups into a unified int
  name: Vehicle Maintenance Workflow
  slug: vehicle-maintenance
common:
- title: ''
  type: Website
  url: https://vehicledatabases.com/
- title: ''
  type: Portal
  url: https://vehicledatabases.com/
- title: ''
  type: Documentation
  url: https://vehicledatabases.com/vehicle-maintenance-api
- title: ''
  type: Pricing
  url: https://vehicledatabases.com/pricing
- title: Vehicle Databases Spectral Rules
  type: SpectralRules
  url: rules/vehicle-databases-spectral-rules.yml
- title: Vehicle Databases Vocabulary
  type: Vocabulary
  url: vocabulary/vehicle-databases-vocabulary.yml
- title: Vehicle Maintenance
  type: NaftikoCapability
  url: capabilities/vehicle-maintenance.yaml
created: '2025-02-12'
description: Vehicle Databases provides automotive maintenance schedule APIs with OEM-compliant service schedules for vehicles up to 200,000 miles. Delivers maintenance intervals, service items, fluids, and recall data for automotive service platforms, fleet management systems, and consumer maintenance reminder applications.
features:
- description: Factory maintenance schedules matching OEM specifications for vehicles up to 200,000 miles with mileage and time-based service intervals.
  name: OEM-Compliant Maintenance Schedules
- description: Detailed service item data including fluid specifications, part numbers, labor time estimates, and OEM-required procedures for each service.
  name: Service Item Details
- description: Decode 17-character VINs to extract make, model, year, engine, trim, and manufacturing details for vehicle identification.
  name: VIN Decoder
- description: NHTSA recall information linked to specific vehicles including recall dates, component affected, risk description, and remedy status.
  name: Recall Data
- description: OEM technical service bulletins (TSBs) for specific vehicle issues including symptom description, diagnosis, and corrective action.
  name: Technical Service Bulletins
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-05-03'
name: Vehicle Databases
rules:
- name: Vehicle Databases API Rules
  rule_count: 21
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 10
  slug: vehicle-databases-spectral-rules
skills: []
slug: vehicle-databases
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vehicle-databases\nname: Vehicle Databases\ndescription: >-\n  Vehicle Databases provides automotive maintenance schedule APIs with OEM-compliant\n  service schedules for vehicles up to 200,000 miles. Delivers maintenance intervals,\n  service items, fluids, and recall data for automotive service platforms, fleet\n  management systems, and consumer maintenance reminder applications.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automotive\n  - Fleet Management\n  - Maintenance\n  - Recalls\n  - Vehicles\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vehicle-databases/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\ncreated: '2025-02-12'\nmodified: '2026-05-03'\napis:\n  - aid: vehicle-databases:vehicle-databases\n    name: Vehicle Databases Maintenance API\n    description: >-\n      The Vehicle Databases Maintenance API delivers OEM-compliant maintenance\n\
  \      schedules for vehicles up to 200,000 miles. Provides service intervals by\n      mileage and time, service item descriptions, fluid specifications, part\n      numbers, labor time estimates, recall notices, technical service bulletins,\n      and vehicle decoder (VIN) information for fleet operators, repair shops,\n      and consumer-facing automotive applications.\n    humanURL: https://vehicledatabases.com/vehicle-maintenance-api\n    tags:\n      - Automotive\n      - Fleet Management\n      - Maintenance\n      - Recalls\n      - Vehicles\n    properties:\n      - type: Documentation\n        url: https://vehicledatabases.com/vehicle-maintenance-api\n      - type: Portal\n        url: https://vehicledatabases.com/\n      - type: OpenAPI\n        url: openapi/vehicle-databases-openapi.yml\n      - type: JSONSchema\n        url: json-schema/vehicle-databases-maintenance-schedule-schema.json\n        title: Maintenance Schedule Schema\n      - type: JSONSchema\n        url: json-schema/vehicle-databases-service-item-schema.json\n\
  \        title: Service Item Schema\n      - type: JSONSchema\n        url: json-schema/vehicle-databases-vehicle-schema.json\n        title: Vehicle Schema\n      - type: JSONStructure\n        url: json-structure/vehicle-databases-maintenance-schedule-structure.json\n        title: Maintenance Schedule Structure\n      - type: JSONStructure\n        url: json-structure/vehicle-databases-service-item-structure.json\n        title: Service Item Structure\n      - type: Example\n        url: examples/vehicle-databases-maintenance-schedule-example.json\n        title: Maintenance Schedule Example\n      - type: Example\n        url: examples/vehicle-databases-vehicle-example.json\n        title: Vehicle Example\n\ncommon:\n  - type: Website\n    url: https://vehicledatabases.com/\n  - type: Portal\n    url: https://vehicledatabases.com/\n  - type: Documentation\n    url: https://vehicledatabases.com/vehicle-maintenance-api\n  - type: Pricing\n    url: https://vehicledatabases.com/pricing\n\
  \  - type: SpectralRules\n    url: rules/vehicle-databases-spectral-rules.yml\n    title: Vehicle Databases Spectral Rules\n  - type: Vocabulary\n    url: vocabulary/vehicle-databases-vocabulary.yml\n    title: Vehicle Databases Vocabulary\n  - type: NaftikoCapability\n    url: capabilities/vehicle-maintenance.yaml\n    title: Vehicle Maintenance\n  - type: Features\n    data:\n      - name: OEM-Compliant Maintenance Schedules\n        description: >-\n          Factory maintenance schedules matching OEM specifications for vehicles\n          up to 200,000 miles with mileage and time-based service intervals.\n      - name: Service Item Details\n        description: >-\n          Detailed service item data including fluid specifications, part numbers,\n          labor time estimates, and OEM-required procedures for each service.\n      - name: VIN Decoder\n        description: >-\n          Decode 17-character VINs to extract make, model, year, engine, trim,\n          and manufacturing\
  \ details for vehicle identification.\n      - name: Recall Data\n        description: >-\n          NHTSA recall information linked to specific vehicles including recall\n          dates, component affected, risk description, and remedy status.\n      - name: Technical Service Bulletins\n        description: >-\n          OEM technical service bulletins (TSBs) for specific vehicle issues\n          including symptom description, diagnosis, and corrective action.\n  - type: UseCases\n    data:\n      - name: Fleet Maintenance Management\n        description: >-\n          Automate maintenance scheduling for commercial and enterprise fleets\n          using OEM-compliant service intervals and mileage-based triggers.\n      - name: Auto Repair Shop Management\n        description: >-\n          Integrate maintenance schedules and TSBs into shop management systems\n          to provide accurate service recommendations and labor estimates.\n      - name: Consumer Maintenance Reminders\n  \
  \      description: >-\n          Power maintenance reminder apps and connected car services with\n          personalized OEM service schedules based on vehicle and mileage.\n      - name: Insurance Telematics\n        description: >-\n          Combine telematics mileage data with maintenance schedules to provide\n          proactive service alerts in usage-based insurance applications.\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vehicle-databases/refs/heads/main/apis.yml
tags:
- Automotive
- Fleet Management
- Maintenance
- Recalls
- Vehicles
url: https://raw.githubusercontent.com/api-evangelist/vehicle-databases/refs/heads/main/apis.yml
use_cases:
- description: Automate maintenance scheduling for commercial and enterprise fleets using OEM-compliant service intervals and mileage-based triggers.
  name: Fleet Maintenance Management
- description: Integrate maintenance schedules and TSBs into shop management systems to provide accurate service recommendations and labor estimates.
  name: Auto Repair Shop Management
- description: Power maintenance reminder apps and connected car services with personalized OEM service schedules based on vehicle and mileage.
  name: Consumer Maintenance Reminders
- description: Combine telematics mileage data with maintenance schedules to provide proactive service alerts in usage-based insurance applications.
  name: Insurance Telematics
---
