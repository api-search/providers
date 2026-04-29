---
api_count: 1
api_specs:
- filename: arlula-openapi.yaml
  format: yaml
  label: Arlula API
  slug: arlula-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/arlula/refs/heads/main/openapi/arlula-openapi.yaml
apis:
- description: The Arlula API provides programmatic access to satellite imagery search, ordering, and delivery. It covers archive search for historical imagery, tasking for future satellite captures, and order manag
  name: Arlula API
  slug: arlula-api
capabilities:
- description: ''
  name: Satellite Imagery Operations
  slug: satellite-imagery-operations
common:
- title: ''
  type: Website
  url: https://arlula.com/
- title: ''
  type: Documentation
  url: https://arlula.com/documentation/
- title: ''
  type: GettingStarted
  url: https://arlula.com/documentation/
- title: ''
  type: Portal
  url: https://dashboard.arlula.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/Arlula
- title: ''
  type: SpectralRules
  url: rules/arlula-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/satellite-imagery-operations.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/arlula-vocabulary.yaml
created: '2025-02-06'
description: Arlula is a satellite imagery marketplace and API platform providing programmatic access to archive and tasking satellite imagery from multiple providers. The Arlula API enables developers to search the global satellite archive, discover tasking opportunities, place imagery orders, and download delivered datasets including GeoTIFF imagery, preview images, and metadata files.
features:
- description: Search a global satellite image archive from multiple providers using area-of-interest (polygon/bounding box) and temporal filters to find available historical scenes.
  name: Archive Search
- description: Commission future satellite captures by searching tasking opportunities and placing orders for specific areas of interest and time windows.
  name: Satellite Tasking
- description: Access imagery from multiple satellite providers through a single unified API, enabling price and resolution comparisons across providers.
  name: Multi-Provider Access
- description: Choose from available product bundles (e.g., analytic, visual) when ordering scenes to match data requirements and budget.
  name: Bundle Selection
- description: Download delivered imagery resources including GeoTIFF files, preview images, and metadata through the Orders API after capture and processing.
  name: Dataset Download
- description: Place multiple archive or tasking orders in a single batch API request to efficiently process large-scale imagery acquisitions.
  name: Batch Ordering
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 19
  name: Arlula Api Context
  property_count: 26
  slug: arlula-api-context
layout: provider
modified: '2026-04-19'
name: Arlula
rules:
- name: Arlula API Rules
  rule_count: 30
  severity_counts:
    error: 14
    hint: 0
    info: 2
    warn: 14
  slug: arlula-spectral-rules
skills: []
slug: arlula
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: arlula\nname: Arlula\ndescription: >-\n  Arlula is a satellite imagery marketplace and API platform providing\n  programmatic access to archive and tasking satellite imagery from multiple\n  providers. The Arlula API enables developers to search the global satellite\n  archive, discover tasking opportunities, place imagery orders, and download\n  delivered datasets including GeoTIFF imagery, preview images, and metadata files.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Earth Observation\n  - Geospatial\n  - Imagery\n  - Remote Sensing\n  - Satellites\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/arlula/refs/heads/main/apis.yml\ncreated: '2025-02-06'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: arlula:arlula-api\n    name: Arlula API\n    description: >-\n      The Arlula API provides programmatic access to satellite imagery search,\n      ordering, and delivery. It\
  \ covers archive search for historical imagery,\n      tasking for future satellite captures, and order management including\n      campaign, dataset, and resource download operations. Authentication uses\n      HTTP Basic with API Key and API Secret obtained from the Arlula dashboard.\n    humanURL: https://arlula.com/documentation/\n    baseURL: https://api.arlula.com\n    tags:\n      - Archive\n      - Earth Observation\n      - Imagery\n      - Satellites\n      - Tasking\n    properties:\n      - type: Documentation\n        url: https://arlula.com/documentation/\n      - type: OpenAPI\n        url: openapi/arlula-openapi.yaml\n      - type: JSONSchema\n        url: json-schema/arlula-archive-scene-schema.json\n      - type: JSONSchema\n        url: json-schema/arlula-archive-search-request-schema.json\n      - type: JSONSchema\n        url: json-schema/arlula-tasking-opportunity-schema.json\n      - type: JSONSchema\n        url: json-schema/arlula-order-schema.json\n      - type:\
  \ JSONStructure\n        url: json-structure/arlula-archive-scene-structure.json\n      - type: JSONStructure\n        url: json-structure/arlula-tasking-opportunity-structure.json\n      - type: JSONStructure\n        url: json-structure/arlula-order-structure.json\n      - type: JSON-LD\n        url: json-ld/arlula-api-context.jsonld\ncommon:\n  - type: Website\n    url: https://arlula.com/\n  - type: Documentation\n    url: https://arlula.com/documentation/\n  - type: GettingStarted\n    url: https://arlula.com/documentation/\n  - type: Portal\n    url: https://dashboard.arlula.com\n  - type: GitHubOrganization\n    url: https://github.com/Arlula\n  - type: SpectralRules\n    url: rules/arlula-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/satellite-imagery-operations.yaml\n  - type: Vocabulary\n    url: vocabulary/arlula-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Archive Search\n        description: >-\n          Search a global satellite\
  \ image archive from multiple providers using\n          area-of-interest (polygon/bounding box) and temporal filters to find\n          available historical scenes.\n      - name: Satellite Tasking\n        description: >-\n          Commission future satellite captures by searching tasking opportunities\n          and placing orders for specific areas of interest and time windows.\n      - name: Multi-Provider Access\n        description: >-\n          Access imagery from multiple satellite providers through a single unified\n          API, enabling price and resolution comparisons across providers.\n      - name: Bundle Selection\n        description: >-\n          Choose from available product bundles (e.g., analytic, visual) when\n          ordering scenes to match data requirements and budget.\n      - name: Dataset Download\n        description: >-\n          Download delivered imagery resources including GeoTIFF files, preview\n          images, and metadata through the Orders\
  \ API after capture and processing.\n      - name: Batch Ordering\n        description: >-\n          Place multiple archive or tasking orders in a single batch API request\n          to efficiently process large-scale imagery acquisitions.\n  - type: UseCases\n    data:\n      - name: Agricultural Monitoring\n        description: >-\n          Search and order archive or tasking imagery to monitor crop health,\n          irrigation patterns, and field conditions over growing seasons.\n      - name: Environmental Change Detection\n        description: >-\n          Acquire multi-temporal satellite imagery to detect deforestation,\n          coastal erosion, urban expansion, or disaster impact areas.\n      - name: Infrastructure Inspection\n        description: >-\n          Order high-resolution imagery for remote inspection of pipelines,\n          power lines, roads, and construction site progress monitoring.\n      - name: Disaster Response\n        description: >-\n          Rapidly\
  \ search and order post-event imagery to assess damage extent\n          and support emergency response and recovery planning.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/arlula/refs/heads/main/apis.yml
tags:
- Earth Observation
- Geospatial
- Imagery
- Remote Sensing
- Satellites
url: https://raw.githubusercontent.com/api-evangelist/arlula/refs/heads/main/apis.yml
use_cases:
- description: Search and order archive or tasking imagery to monitor crop health, irrigation patterns, and field conditions over growing seasons.
  name: Agricultural Monitoring
- description: Acquire multi-temporal satellite imagery to detect deforestation, coastal erosion, urban expansion, or disaster impact areas.
  name: Environmental Change Detection
- description: Order high-resolution imagery for remote inspection of pipelines, power lines, roads, and construction site progress monitoring.
  name: Infrastructure Inspection
- description: Rapidly search and order post-event imagery to assess damage extent and support emergency response and recovery planning.
  name: Disaster Response
---
