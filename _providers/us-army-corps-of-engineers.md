---
api_count: 3
api_specs:
- filename: usace-cwms-data-openapi.yml
  format: yaml
  label: USACE CWMS Data API
  slug: usace-cwms-data
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/openapi/usace-cwms-data-openapi.yml
apis:
- description: The Corps Water Management System Data API (CDA) is a RESTful API providing public access to USACE water management data. It supports retrieval of timeseries data (stream flow, reservoir levels, preci
  name: USACE CWMS Data API
  slug: usace-cwms-data
- description: The National Inventory of Dams (NID) API provides access to the comprehensive database of US dams maintained by the US Army Corps of Engineers. The database contains information on over 70 data fields
  name: USACE National Inventory of Dams API
  slug: usace-national-inventory-of-dams
- description: 'The USACE Open Data program provides public access to geospatial data, regulatory permit information, and other datasets maintained by the US Army Corps of Engineers. Data is available through ArcGIS '
  name: USACE Open Data
  slug: usace-open-data
capabilities:
- description: Unified water data capability composing USACE CWMS Data API resources for water resource monitoring, flood forecasting, reservoir operations, and hydrological analysis. Used by water managers, flood f
  name: USACE Water Data
  slug: water-data
common: []
created: '2024-11-21'
description: The US Army Corps of Engineers is a federal agency that plays a critical role in managing the nation's water resources and infrastructure. They are responsible for building and maintaining dams, levees, and flood control systems, overseeing construction of ports, harbors, and waterways, and providing engineering support to military operations. USACE publishes open APIs including the CWMS Data API for water management timeseries data, the National Inventory of Dams API, and open geospatial datasets.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 30
  name: Us Army Corps Of Engineers Context
  property_count: 3
  slug: us-army-corps-of-engineers-context
layout: provider
modified: '2026-05-03'
name: US Army Corps of Engineers
rules:
- name: US Army Corps of Engineers API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: usace-cwms-data-rules
skills: []
slug: us-army-corps-of-engineers
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-army-corps-of-engineers\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/apis.yml\napis:\n  - aid: us-army-corps-of-engineers:usace-cwms-data\n    name: USACE CWMS Data API\n    tags:\n      - Water Resources\n      - Federal Government\n      - Water Data\n      - Hydrological Data\n      - Open Data\n      - Timeseries\n      - REST API\n    humanURL: https://cwms-data.usace.army.mil/cwms-data/\n    baseURL: https://cwms-data.usace.army.mil/cwms-data\n    properties:\n      - url: https://cwms-data.usace.army.mil/cwms-data/\n        type: Documentation\n      - url: https://cwms-data.usace.army.mil/cwms-data/swagger-ui.html\n        type: SwaggerUI\n      - url: https://github.com/USACE/cwms-data-api\n        type: GitHubRepository\n      - url: https://cwms-data-api.readthedocs.io/latest/\n        type: APIDocumentation\n      - url: https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/openapi/usace-cwms-data-openapi.yml\n\
  \        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/rules/usace-cwms-data-rules.yml\n        type: SpectralRuleset\n      - url: https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/capabilities/water-data.yaml\n        type: NaftikoCapability\n      - url: https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/json-schema/usace-timeseries-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/json-ld/us-army-corps-of-engineers-context.jsonld\n        type: JSONLDContext\n    description: >-\n      The Corps Water Management System Data API (CDA) is a RESTful API providing public access\n      to USACE water management data. It supports retrieval of timeseries data (stream flow,\n      reservoir levels, precipitation), location information, rating\
  \ tables, location levels,\n      reservoirs, and a full data catalog. The API supports pagination, unit conversion, and\n      multiple date/time formats (ISO 8601 or epoch milliseconds). Data is publicly available\n      without authentication for reading.\n  - aid: us-army-corps-of-engineers:usace-national-inventory-of-dams\n    name: USACE National Inventory of Dams API\n    tags:\n      - Dams\n      - Federal Government\n      - Water Infrastructure\n      - Safety\n      - Geospatial Data\n    humanURL: https://nid.sec.usace.army.mil/\n    properties:\n      - url: https://nid.sec.usace.army.mil/\n        type: Documentation\n      - url: https://nid.sec.usace.army.mil/api/developer\n        type: SwaggerUI\n      - url: https://geospatial-usace.opendata.arcgis.com/datasets/1632cb2bb23046569fbf2bc144f06764_0\n        type: GISData\n    description: >-\n      The National Inventory of Dams (NID) API provides access to the comprehensive database of\n      US dams maintained by the\
  \ US Army Corps of Engineers. The database contains information on\n      over 70 data fields for each dam including location, size, type, purpose, hazard classification,\n      last inspection date, and owner information. The API supports searching and filtering dam records.\n  - aid: us-army-corps-of-engineers:usace-open-data\n    name: USACE Open Data\n    tags:\n      - Open Data\n      - Federal Government\n      - Geospatial Data\n      - Water Resources\n      - Infrastructure\n    humanURL: https://www.usace.army.mil/open/\n    properties:\n      - url: https://www.usace.army.mil/open/\n        type: Documentation\n      - url: https://geospatial-usace.opendata.arcgis.com/\n        type: GeoSpatialPortal\n      - url: https://catalog.data.gov/dataset?publisher=US+Army+Corps+of+Engineers\n        type: DataGov\n      - url: https://permits.ops.usace.army.mil/\n        type: PermitsPortal\n    description: >-\n      The USACE Open Data program provides public access to geospatial\
  \ data, regulatory permit\n      information, and other datasets maintained by the US Army Corps of Engineers. Data is\n      available through ArcGIS Open Data, data.gov, and the USACE Regulatory portal.\nname: US Army Corps of Engineers\ntags:\n  - Water Resources\n  - Federal Government\n  - Military Engineering\n  - Infrastructure\n  - Open Data\n  - Geospatial Data\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-21'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  The US Army Corps of Engineers is a federal agency that plays a critical role in\n  managing the nation's water resources and infrastructure. They are responsible for\n  building and maintaining dams, levees, and flood control systems, overseeing construction\n  of ports, harbors, and waterways, and providing engineering support to military operations.\n  USACE publishes open APIs including the CWMS Data API for water\
  \ management timeseries data,\n  the National Inventory of Dams API, and open geospatial datasets.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/apis.yml
tags:
- Water Resources
- Federal Government
- Military Engineering
- Infrastructure
- Open Data
- Geospatial Data
url: https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/apis.yml
use_cases: []
---
