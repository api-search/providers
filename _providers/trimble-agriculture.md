---
api_count: 2
api_specs:
- filename: trimble-agriculture-openapi.yml
  format: yaml
  label: Trimble Agriculture Data API
  slug: trimble-agriculture-data
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trimble-agriculture/refs/heads/main/openapi/trimble-agriculture-openapi.yml
apis:
- description: The Trimble Agriculture Data API (PTxAg FarmENGAGE API) provides REST endpoints for managing farms, fields, crop zones, boundaries, equipment activities, work orders, prescriptions, materials, and ima
  name: Trimble Agriculture Data API
  slug: trimble-agriculture-data
- description: The Trimble Agriculture Telematics API provides access to real-time and historical equipment telematics data from connected Trimble displays and precision agriculture devices. Includes equipment locat
  name: Trimble Agriculture Telematics API
  slug: trimble-agriculture-telematics
capabilities:
- description: Unified precision farming capability combining farm setup, field management, crop zone tracking, equipment activity monitoring, work order dispatch, and prescription management. Powers agricultural da
  name: Trimble Agriculture Precision Farming
  slug: precision-farming
common:
- title: ''
  type: Website
  url: https://agriculture.trimble.com/
- title: ''
  type: DeveloperPortal
  url: https://agdeveloper.trimble.com/
- title: ''
  type: Documentation
  url: https://agdeveloper.trimble.com/api-docs
- title: ''
  type: SignUp
  url: https://agdeveloper.trimble.com/
- title: ''
  type: Contact
  url: mailto:ag_api@trimble.com
created: '2025-02-06'
description: The Trimble Agriculture Cloud is an independent, brand-agnostic platform that connects infield devices and operational workflows to more efficiently execute crop production plans and collect robust agricultural datasets. The Trimble Agriculture API (now operating as PTxAg FarmENGAGE) provides REST APIs for farm setup, field boundaries, task records, work orders, prescriptions, equipment activities, crop zones, materials, and telematics. It enables third-party integrators to exchange as-applied data, send prescriptions to Trimble displays, and align field resources across precision agriculture systems. The platform serves over 180 million customer acres globally.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Trimble Agriculture Context
  property_count: 28
  slug: trimble-agriculture-context
layout: provider
modified: '2026-05-03'
name: Trimble Agriculture
rules:
- name: Trimble Agriculture API Rules
  rule_count: 11
  severity_counts:
    error: 5
    hint: 2
    info: 0
    warn: 4
  slug: trimble-agriculture-rules
skills: []
slug: trimble-agriculture
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trimble-agriculture\nname: Trimble Agriculture\ndescription: >-\n  The Trimble Agriculture Cloud is an independent, brand-agnostic platform that\n  connects infield devices and operational workflows to more efficiently execute\n  crop production plans and collect robust agricultural datasets. The Trimble\n  Agriculture API (now operating as PTxAg FarmENGAGE) provides REST APIs for\n  farm setup, field boundaries, task records, work orders, prescriptions, equipment\n  activities, crop zones, materials, and telematics. It enables third-party\n  integrators to exchange as-applied data, send prescriptions to Trimble displays,\n  and align field resources across precision agriculture systems. The platform serves\n  over 180 million customer acres globally.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Agriculture\n  - Farming\n  - IoT\n  - Precision Agriculture\n  - Field Management\n\
  \  - Prescriptions\n  - Telematics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/trimble-agriculture/refs/heads/main/apis.yml\ncreated: '2025-02-06'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: trimble-agriculture:trimble-agriculture-data\n    name: Trimble Agriculture Data API\n    description: >-\n      The Trimble Agriculture Data API (PTxAg FarmENGAGE API) provides REST endpoints\n      for managing farms, fields, crop zones, boundaries, equipment activities,\n      work orders, prescriptions, materials, and imagery. Enables third-party\n      integrators to exchange precision agriculture data between field devices and\n      farm management platforms. Base URL: https://cloud.api.trimble.com/Trimble-Ag-Software/externalApi/3.0\n    humanURL: https://agdeveloper.trimble.com/api-docs\n    tags:\n      - Agriculture\n      - Farming\n      - Field Management\n      - Prescriptions\n      - Equipment Activities\n      - Work Orders\n      - Crop\
  \ Zones\n      - Boundaries\n    properties:\n      - type: Documentation\n        url: https://agdeveloper.trimble.com/api-docs\n      - type: GettingStarted\n        url: https://agdeveloper.trimble.com/\n      - type: OpenAPI\n        url: openapi/trimble-agriculture-openapi.yml\n\n  - aid: trimble-agriculture:trimble-agriculture-telematics\n    name: Trimble Agriculture Telematics API\n    description: >-\n      The Trimble Agriculture Telematics API provides access to real-time and historical\n      equipment telematics data from connected Trimble displays and precision agriculture\n      devices. Includes equipment location, status, and operational metrics.\n    humanURL: https://agdeveloper.trimble.com/api-docs\n    tags:\n      - Agriculture\n      - Telematics\n      - IoT\n      - Equipment\n      - GPS\n    properties:\n      - type: Documentation\n        url: https://agdeveloper.trimble.com/api-docs\n\nfeatures:\n  - Farm, field, and crop zone management\n  - Equipment activity\
  \ data from precision ag displays\n  - As-applied data for regulatory compliance and productivity analysis\n  - Prescription management (send to and receive from Trimble displays)\n  - Field boundary, guidance line, and landmark synchronization\n  - Work order creation and assignment to farm operators\n  - Materials management for inputs (seeds, fertilizers, chemicals)\n  - GeoTIFF imagery upload and processing for crop zones\n  - Equipment telematics and real-time positioning\n  - Multi-tenant organization support for agronomists and consultants\nuseCases:\n  - Access as-applied data from Trimble displays for compliance reporting\n  - Send variable-rate prescriptions to in-field Trimble displays\n  - Align field boundaries and landmarks with farm management software\n  - Plan and assign work orders to farm equipment operators\n  - Integrate harvest data with third-party yield analysis platforms\n  - Monitor equipment telematics for fleet management\n  - Build agronomist portals accessing\
  \ farmer data with consent\nintegrations:\n  - Trimble Precision-IQ display field application\n  - Trimble Ag Software and Trimble Ag Mobile\n  - PTxAg FarmENGAGE platform\n  - Third-party precision agriculture software systems\nsolutions:\n  - Third-party software vendors integrating with Trimble precision ag ecosystem\n  - Custom applicators and agronomists accessing farm data APIs\n  - Large production farms building multi-vendor data workflows\n  - Regulatory compliance and farm management platforms\ncommon:\n  - type: Website\n    url: https://agriculture.trimble.com/\n  - type: DeveloperPortal\n    url: https://agdeveloper.trimble.com/\n  - type: Documentation\n    url: https://agdeveloper.trimble.com/api-docs\n  - type: SignUp\n    url: https://agdeveloper.trimble.com/\n  - type: Contact\n    url: mailto:ag_api@trimble.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trimble-agriculture/refs/heads/main/apis.yml
tags:
- Agriculture
- Farming
- IoT
- Precision Agriculture
- Field Management
- Prescriptions
- Telematics
url: https://raw.githubusercontent.com/api-evangelist/trimble-agriculture/refs/heads/main/apis.yml
use_cases: []
---
