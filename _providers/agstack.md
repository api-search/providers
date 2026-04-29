---
api_count: 3
apis:
- description: FastAPI-based weather service providing 5-day forecasts, current conditions, Temperature-Humidity Index (THI) for livestock heat stress, UAV flight condition forecasts, and spray condition assessments
  name: OpenAgri Weather Service
  slug: openagri-weather-service
- description: Django REST API for digital farm calendar management. Records farmer operations (planting, spraying, harvesting, irrigation), farm observations, parcel properties, and farm assets. Provides data in bo
  name: OpenAgri Farm Calendar
  slug: openagri-farm-calendar
- description: The AgStack Asset Registry provides global field boundary registration and identification. Submit a field polygon (WKT or GeoJSON) and receive a permanent 256-bit (16-character alphanumeric) geo ID. S
  name: AgStack Asset Registry
  slug: asset-registry
capabilities:
- description: ''
  name: Precision Agriculture
  slug: precision-agriculture
common:
- title: ''
  type: Portal
  url: https://agstack.org/
- title: ''
  type: Documentation
  url: https://agstack.org/projects/
- title: ''
  type: GitHubOrganization
  url: https://github.com/agstack
- title: ''
  type: About
  url: https://agstack.org/about/
- title: Linux Foundation AI and Data
  type: About
  url: https://lfaidata.foundation/
- title: ''
  type: JSON-LD
  url: json-ld/agstack-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/agstack-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/agstack-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/agstack-openagri-weather-service-api.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/agstack-asset-registry-api.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/precision-agriculture.yaml
created: '2026-03-16'
description: AgStack Foundation is a Linux Foundation project providing open-source digital infrastructure for the agriculture sector. Key projects include the Asset Registry (global field boundary registration with unique geo IDs), the OpenAgri Weather Service (agricultural weather forecasts, THI, spray conditions, UAV flight forecasts), and the OpenAgri Farm Calendar (farm operation recording with JSON-LD/OCSM linked data support). AgStack tools support EUDR compliance, precision agriculture, and interoperability across the agtech ecosystem through the OpenAgri Common Semantic Model.
features:
- description: Global registry for agricultural field boundaries — submit WKT or GeoJSON geometry, receive a permanent unique 16-character geo ID
  name: Field Boundary Registry
- description: 5-day weather forecasts, current conditions, and agricultural indicators including THI, spray conditions, and UAV flight suitability
  name: Agricultural Weather Intelligence
- description: Record and manage farm operations (planting, irrigation, spraying, harvesting) with linked data (JSON-LD/OCSM) output
  name: Digital Farm Calendar
- description: All APIs support JSON-LD output conforming to the OpenAgri Common Semantic Model (OCSM) for semantic interoperability
  name: Linked Data Support
- description: Tools for EU Deforestation Regulation compliance — field boundary registration and supply chain traceability via INATrace
  name: EUDR Compliance Support
- description: Evapotranspiration (ETo) calculations and soil moisture analysis for data-driven irrigation decisions
  name: Irrigation Management
- description: All tools are Apache-2.0 licensed, Docker-ready, and deployable on any cloud or on-premises infrastructure
  name: Open Source Infrastructure
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Weather data source for current conditions and forecasts used by the OpenAgri Weather Service
  name: OpenWeatherMap
- description: EU Horizon Europe project (Grant No. 101134083) that funds and drives the OpenAgri microservices ecosystem
  name: OpenAgri
- description: OpenAgri Common Semantic Model — linked data vocabulary for agricultural interoperability used across all OpenAgri APIs
  name: OCSM
- description: Open-source blockchain-based track and trace system for agricultural supply chains
  name: INATrace
- description: TechnoServe Labs mobile and web application for EUDR compliance field data collection integrated with the asset registry
  name: TerraTrac
jsonld:
- class_count: 30
  name: Agstack Context
  property_count: 6
  slug: agstack-context
layout: provider
modified: '2026-04-19'
name: AgStack Foundation
rules:
- name: AgStack Foundation API Rules
  rule_count: 16
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 10
  slug: agstack-spectral-rules
skills: []
slug: agstack
solutions: []
source_yaml: "aid: agstack\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/agstack/refs/heads/main/apis.yml\napis:\n  - aid: agstack:openagri-weather-service\n    name: OpenAgri Weather Service\n    tags:\n      - Agriculture\n      - Weather\n      - Open Source\n      - Linux Foundation\n    humanURL: https://github.com/agstack/OpenAgri-WeatherService\n    properties:\n      - url: https://github.com/agstack/OpenAgri-WeatherService\n        type: Documentation\n      - url: https://github.com/agstack/OpenAgri-WeatherService/blob/main/README.md\n        type: GettingStarted\n      - url: openapi/agstack-openagri-weather-service-openapi.yml\n        type: OpenAPI\n      - url: json-schema/agstack-openagri-weather-service-predictionout-schema.json\n        type: JSONSchema\n      - url: json-schema/agstack-openagri-weather-service-weatherdataout-schema.json\n        type: JSONSchema\n      - url: json-schema/agstack-openagri-weather-service-thidataout-schema.json\n        type:\
  \ JSONSchema\n      - url: json-schema/agstack-openagri-weather-service-sprayforecastresponse-schema.json\n        type: JSONSchema\n      - url: json-schema/agstack-openagri-weather-service-flightstatusforecastresponse-schema.json\n        type: JSONSchema\n      - url: json-schema/agstack-openagri-weather-service-geojsonout-schema.json\n        type: JSONSchema\n      - url: json-schema/agstack-openagri-weather-service-jsonldgraph-schema.json\n        type: JSONSchema\n      - url: json-schema/agstack-openagri-weather-service-authtoken-schema.json\n        type: JSONSchema\n      - url: json-schema/agstack-openagri-weather-service-pointout-schema.json\n        type: JSONSchema\n      - url: json-schema/agstack-openagri-weather-service-validationerror-schema.json\n        type: JSONSchema\n      - url: json-schema/agstack-openagri-weather-service-httpvalidationerror-schema.json\n        type: JSONSchema\n      - url: json-schema/agstack-openagri-weather-service-body-token-auth-token-post-schema.json\n\
  \        type: JSONSchema\n      - url: json-structure/agstack-openagri-weather-service-predictionout-structure.json\n        type: JSONStructure\n      - url: json-structure/agstack-openagri-weather-service-weatherdataout-structure.json\n        type: JSONStructure\n      - url: json-structure/agstack-openagri-weather-service-thidataout-structure.json\n        type: JSONStructure\n      - url: json-structure/agstack-openagri-weather-service-sprayforecastresponse-structure.json\n        type: JSONStructure\n      - url: json-structure/agstack-openagri-weather-service-flightstatusforecastresponse-structure.json\n        type: JSONStructure\n      - url: json-structure/agstack-openagri-weather-service-geojsonout-structure.json\n        type: JSONStructure\n      - url: json-structure/agstack-openagri-weather-service-jsonldgraph-structure.json\n        type: JSONStructure\n      - url: json-structure/agstack-openagri-weather-service-authtoken-structure.json\n        type: JSONStructure\n\
  \      - url: json-structure/agstack-openagri-weather-service-pointout-structure.json\n        type: JSONStructure\n      - url: json-structure/agstack-openagri-weather-service-validationerror-structure.json\n        type: JSONStructure\n      - url: json-structure/agstack-openagri-weather-service-httpvalidationerror-structure.json\n        type: JSONStructure\n      - url: json-structure/agstack-openagri-weather-service-body-token-auth-token-post-structure.json\n        type: JSONStructure\n      - url: examples/agstack-openagri-weather-service-predictionout-example.json\n        type: Example\n      - url: examples/agstack-openagri-weather-service-weatherdataout-example.json\n        type: Example\n      - url: examples/agstack-openagri-weather-service-thidataout-example.json\n        type: Example\n      - url: examples/agstack-openagri-weather-service-sprayforecastresponse-example.json\n        type: Example\n      - url: examples/agstack-openagri-weather-service-flightstatusforecastresponse-example.json\n\
  \        type: Example\n      - url: examples/agstack-openagri-weather-service-geojsonout-example.json\n        type: Example\n      - url: examples/agstack-openagri-weather-service-jsonldgraph-example.json\n        type: Example\n      - url: examples/agstack-openagri-weather-service-authtoken-example.json\n        type: Example\n      - url: examples/agstack-openagri-weather-service-pointout-example.json\n        type: Example\n      - url: examples/agstack-openagri-weather-service-validationerror-example.json\n        type: Example\n      - url: examples/agstack-openagri-weather-service-httpvalidationerror-example.json\n        type: Example\n      - url: examples/agstack-openagri-weather-service-body-token-auth-token-post-example.json\n        type: Example\n    description: >-\n      FastAPI-based weather service providing 5-day forecasts, current conditions,\n      Temperature-Humidity Index (THI) for livestock heat stress, UAV flight condition\n      forecasts, and spray condition\
  \ assessments. Supports both JSON and JSON-LD/OCSM\n      output formats for linked data interoperability. Part of the OpenAgri EU Horizon\n      Europe project.\n\n  - aid: agstack:openagri-farm-calendar\n    name: OpenAgri Farm Calendar\n    tags:\n      - Agriculture\n      - Farm Management\n      - Open Source\n      - Linux Foundation\n    humanURL: https://github.com/agstack/OpenAgri-FarmCalendar\n    properties:\n      - url: https://github.com/agstack/OpenAgri-FarmCalendar\n        type: Documentation\n      - url: https://github.com/agstack/OpenAgri-FarmCalendar/blob/main/README.md\n        type: GettingStarted\n      - url: openapi/agstack-openagri-farm-calendar-openapi.yml\n        type: OpenAPI\n    description: >-\n      Django REST API for digital farm calendar management. Records farmer operations\n      (planting, spraying, harvesting, irrigation), farm observations, parcel properties,\n      and farm assets. Provides data in both JSON and JSON-LD formats conforming to\
  \ the\n      OpenAgri Common Semantic Model (OCSM). Part of the OpenAgri EU Horizon Europe project.\n\n  - aid: agstack:asset-registry\n    name: AgStack Asset Registry\n    tags:\n      - Agriculture\n      - Geospatial\n      - Open Source\n      - Linux Foundation\n    humanURL: https://github.com/agstack/asset-registry\n    properties:\n      - url: https://github.com/agstack/asset-registry\n        type: Documentation\n      - url: https://api-ar.agstack.org\n        type: APIReference\n      - url: openapi/agstack-asset-registry-openapi.yml\n        type: OpenAPI\n      - url: json-schema/agstack-asset-registry-registerfieldwktrequest-schema.json\n        type: JSONSchema\n      - url: json-schema/agstack-asset-registry-geojsonfeaturecollection-schema.json\n        type: JSONSchema\n      - url: json-schema/agstack-asset-registry-bulkpointresult-schema.json\n        type: JSONSchema\n      - url: json-structure/agstack-asset-registry-registerfieldwktrequest-structure.json\n     \
  \   type: JSONStructure\n      - url: json-structure/agstack-asset-registry-geojsonfeaturecollection-structure.json\n        type: JSONStructure\n      - url: json-structure/agstack-asset-registry-bulkpointresult-structure.json\n        type: JSONStructure\n      - url: examples/agstack-asset-registry-registerfieldwktrequest-example.json\n        type: Example\n      - url: examples/agstack-asset-registry-geojsonfeaturecollection-example.json\n        type: Example\n      - url: examples/agstack-asset-registry-bulkpointresult-example.json\n        type: Example\n    description: >-\n      The AgStack Asset Registry provides global field boundary registration and\n      identification. Submit a field polygon (WKT or GeoJSON) and receive a permanent\n      256-bit (16-character alphanumeric) geo ID. Supports single and bulk registration,\n      field retrieval, centroid calculation, and spatial overlap analysis. Production API\n      available at api-ar.agstack.org.\n\ncommon:\n  - url:\
  \ https://agstack.org/\n    type: Portal\n  - url: https://agstack.org/projects/\n    type: Documentation\n  - url: https://github.com/agstack\n    type: GitHubOrganization\n  - url: https://agstack.org/about/\n    type: About\n  - url: https://lfaidata.foundation/\n    type: About\n    title: Linux Foundation AI and Data\n  - url: json-ld/agstack-context.jsonld\n    type: JSON-LD\n  - url: rules/agstack-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/agstack-vocabulary.yaml\n    type: Vocabulary\n  - url: capabilities/shared/agstack-openagri-weather-service-api.yaml\n    type: NaftikoCapability\n  - url: capabilities/shared/agstack-asset-registry-api.yaml\n    type: NaftikoCapability\n  - url: capabilities/precision-agriculture.yaml\n    type: NaftikoCapability\n  - type: Features\n    data:\n      - name: Field Boundary Registry\n        description: Global registry for agricultural field boundaries — submit WKT or GeoJSON geometry, receive a permanent unique 16-character\
  \ geo ID\n      - name: Agricultural Weather Intelligence\n        description: 5-day weather forecasts, current conditions, and agricultural indicators including THI, spray conditions, and UAV flight suitability\n      - name: Digital Farm Calendar\n        description: Record and manage farm operations (planting, irrigation, spraying, harvesting) with linked data (JSON-LD/OCSM) output\n      - name: Linked Data Support\n        description: All APIs support JSON-LD output conforming to the OpenAgri Common Semantic Model (OCSM) for semantic interoperability\n      - name: EUDR Compliance Support\n        description: Tools for EU Deforestation Regulation compliance — field boundary registration and supply chain traceability via INATrace\n      - name: Irrigation Management\n        description: Evapotranspiration (ETo) calculations and soil moisture analysis for data-driven irrigation decisions\n      - name: Open Source Infrastructure\n        description: All tools are Apache-2.0 licensed,\
  \ Docker-ready, and deployable on any cloud or on-premises infrastructure\n  - type: UseCases\n    data:\n      - name: Farmer Field Registration\n        description: Farmers and agri-cooperatives register field boundaries in the global asset registry to enable data-driven farm management\n      - name: Crop Protection Planning\n        description: Check spray conditions and UAV flight forecasts before applying pesticides or fertilizers to minimize drift and maximize efficacy\n      - name: Livestock Heat Stress Monitoring\n        description: Monitor Temperature-Humidity Index to detect and prevent heat stress events in dairy and beef cattle herds\n      - name: EUDR Supply Chain Compliance\n        description: Register plot geolocations and trace agricultural commodities through the supply chain to demonstrate zero-deforestation compliance\n      - name: Precision Irrigation\n        description: Use evapotranspiration data and soil moisture analysis to schedule irrigation and optimize\
  \ water usage\n      - name: Interoperable Agtech Integration\n        description: Share agricultural data between platforms using JSON-LD/OCSM linked data format for semantic interoperability\n  - type: Integrations\n    data:\n      - name: OpenWeatherMap\n        description: Weather data source for current conditions and forecasts used by the OpenAgri Weather Service\n      - name: OpenAgri\n        description: EU Horizon Europe project (Grant No. 101134083) that funds and drives the OpenAgri microservices ecosystem\n      - name: OCSM\n        description: OpenAgri Common Semantic Model — linked data vocabulary for agricultural interoperability used across all OpenAgri APIs\n      - name: INATrace\n        description: Open-source blockchain-based track and trace system for agricultural supply chains\n      - name: TerraTrac\n        description: TechnoServe Labs mobile and web application for EUDR compliance field data collection integrated with the asset registry\n\nname: AgStack\
  \ Foundation\ntags:\n  - Agriculture\n  - Linux Foundation\n  - Open Source\n  - Geospatial\n  - Precision Agriculture\n  - Linked Data\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nposition: Consumer\ndescription: >-\n  AgStack Foundation is a Linux Foundation project providing open-source digital\n  infrastructure for the agriculture sector. Key projects include the Asset Registry\n  (global field boundary registration with unique geo IDs), the OpenAgri Weather Service\n  (agricultural weather forecasts, THI, spray conditions, UAV flight forecasts), and the\n  OpenAgri Farm Calendar (farm operation recording with JSON-LD/OCSM linked data support).\n  AgStack tools support EUDR compliance, precision agriculture, and interoperability across\n  the agtech ecosystem through the OpenAgri Common Semantic Model.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\
  specificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/agstack/refs/heads/main/apis.yml
tags:
- Agriculture
- Linux Foundation
- Open Source
- Geospatial
- Precision Agriculture
- Linked Data
url: https://raw.githubusercontent.com/api-evangelist/agstack/refs/heads/main/apis.yml
use_cases:
- description: Farmers and agri-cooperatives register field boundaries in the global asset registry to enable data-driven farm management
  name: Farmer Field Registration
- description: Check spray conditions and UAV flight forecasts before applying pesticides or fertilizers to minimize drift and maximize efficacy
  name: Crop Protection Planning
- description: Monitor Temperature-Humidity Index to detect and prevent heat stress events in dairy and beef cattle herds
  name: Livestock Heat Stress Monitoring
- description: Register plot geolocations and trace agricultural commodities through the supply chain to demonstrate zero-deforestation compliance
  name: EUDR Supply Chain Compliance
- description: Use evapotranspiration data and soil moisture analysis to schedule irrigation and optimize water usage
  name: Precision Irrigation
- description: Share agricultural data between platforms using JSON-LD/OCSM linked data format for semantic interoperability
  name: Interoperable Agtech Integration
---
