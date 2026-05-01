---
api_count: 1
api_specs:
- filename: dmi-open-data-api-openapi.yml
  format: yaml
  label: DMI Open Data API
  slug: dmi-open-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/danish-meteorological-institutes/refs/heads/main/openapi/dmi-open-data-api-openapi.yml
apis:
- description: The DMI Open Data API provides access to four core public services - meteorological observations (metObs), climate data (climateData), ocean observations (oceanObs), and lightning data (lightningData)
  name: DMI Open Data API
  slug: dmi-open-data-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.dmi.dk/
- title: ''
  type: Open Data Portal
  url: https://opendatadocs.dmi.govcloud.dk/
- title: ''
  type: Open Data FAQ
  url: https://opendatadocs.dmi.govcloud.dk/en/FAQ
- title: ''
  type: AWS Open Data
  url: https://registry.opendata.aws/dmi-opendata/
- title: ''
  type: GitHub Organization
  url: https://github.com/dmidk
- title: ''
  type: JSON-LD
  url: json-ld/dmi-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/dmi-vocabulary.yml
created: '2025-02-06'
description: The Danish Meteorological Institute is a government agency responsible for providing meteorological and climate services in Denmark. DMI publishes weather observations, climate data, ocean observations, and lightning data through its Open Data API and supplies forecast products via the AWS Open Data registry. The agency operates weather stations, radar systems, and satellites to monitor and forecast weather across Denmark, Greenland, and the Faroe Islands.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 2
  name: Dmi Context
  property_count: 8
  slug: dmi-context
layout: provider
modified: '2026-04-28'
name: Danish Meteorological Institutes
rules:
- name: Danish Meteorological Institutes API Rules
  rule_count: 5
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 4
  slug: dmi-open-data-api-rules
skills: []
slug: danish-meteorological-institutes
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: danish-meteorological-institutes\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/danish-meteorological-institutes/refs/heads/main/apis.yml\napis:\n  - aid: danish-meteorological-institutes:dmi-open-data-api\n    name: DMI Open Data API\n    tags:\n      - Climate\n      - Environment\n      - Lightning\n      - Meteorological\n      - Ocean\n      - Open Data\n      - Weather\n    humanURL: https://opendatadocs.dmi.govcloud.dk/\n    baseURL: https://opendataapi.dmi.dk/v2\n    properties:\n      - url: https://opendatadocs.dmi.govcloud.dk/\n        type: Documentation\n      - url: https://opendatadocs.dmi.govcloud.dk/Authentication\n        type: Authentication\n      - url: openapi/dmi-open-data-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/observation.json\n        type: JSONSchema\n      - url: json-schema/station.json\n        type: JSONSchema\n      - url: rules/dmi-open-data-api-rules.yml\n        type: Rules\n      - url: capabilities/dmi-open-data-api-capabilities.yml\n\
  \        type: Capabilities\n    description: >-\n      The DMI Open Data API provides access to four core public services -\n      meteorological observations (metObs), climate data (climateData), ocean\n      observations (oceanObs), and lightning data (lightningData) - via OGC API\n      compatible feature collections. Each service requires a per-service API\n      key obtained through the DMI Open Data portal.\nname: Danish Meteorological Institutes\ntags:\n  - Climate\n  - Environment\n  - Lightning\n  - Meteorological\n  - Ocean\n  - Open Data\n  - Weather\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-06'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  The Danish Meteorological Institute is a government agency responsible for\n  providing meteorological and climate services in Denmark. DMI publishes\n  weather observations, climate data, ocean observations, and lightning data\n\
  \  through its Open Data API and supplies forecast products via the AWS Open\n  Data registry. The agency operates weather stations, radar systems, and\n  satellites to monitor and forecast weather across Denmark, Greenland, and\n  the Faroe Islands.\ncommon:\n  - type: Website\n    url: https://www.dmi.dk/\n  - type: Open Data Portal\n    url: https://opendatadocs.dmi.govcloud.dk/\n  - type: Open Data FAQ\n    url: https://opendatadocs.dmi.govcloud.dk/en/FAQ\n  - type: AWS Open Data\n    url: https://registry.opendata.aws/dmi-opendata/\n  - type: GitHub Organization\n    url: https://github.com/dmidk\n  - type: JSON-LD\n    url: json-ld/dmi-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/dmi-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\nxType: company\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/danish-meteorological-institutes/refs/heads/main/apis.yml
tags:
- Climate
- Environment
- Lightning
- Meteorological
- Ocean
- Open Data
- Weather
url: https://raw.githubusercontent.com/api-evangelist/danish-meteorological-institutes/refs/heads/main/apis.yml
use_cases: []
---
