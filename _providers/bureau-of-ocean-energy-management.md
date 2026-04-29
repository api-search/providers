---
api_count: 3
apis:
- description: MarineCadastre.gov is the authoritative source for marine cadastre data and services. It provides an interactive map viewer with integrated submerged lands information including legal, property owners
  name: MarineCadastre.gov
  slug: marine-cadastre
- description: BOEM provides ArcGIS REST Services exposing geospatial data for the Outer Continental Shelf (OCS) regions. Data includes active leases, offshore block grids, boundaries, wells, and pipelines for Atlan
  name: BOEM ArcGIS REST Services
  slug: boem-arcgis-rest-services
- description: ESPIS provides access to BOEM's environmental studies data, including research reports, environmental impact studies, and scientific literature related to offshore energy development. Searchable by to
  name: Environmental Studies Program Information System (ESPIS)
  slug: espis
common:
- title: ''
  type: Website
  url: https://www.boem.gov
- title: ''
  type: Portal
  url: https://marinecadastre.gov/
- title: ''
  type: Privacy Policy
  url: https://www.boem.gov/privacy-policy
- title: ''
  type: Mapping and Data
  url: https://www.boem.gov/oil-gas-energy/mapping-and-data
- title: ''
  type: Data Portal
  url: https://catalog.data.gov/dataset?organization=boem-gov
created: '2024-11-30'
description: The Bureau of Ocean Energy Management (BOEM) manages the nation's offshore resources in an environmentally and economically responsible way. BOEM oversees the responsible development of U.S. Outer Continental Shelf energy and mineral resources while protecting the environment and conserving natural resources.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Bureau of Ocean Energy Management
skills: []
slug: bureau-of-ocean-energy-management
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bureau-of-ocean-energy-management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bureau-of-ocean-energy-management/refs/heads/main/apis.yml\nname: Bureau of Ocean Energy Management\ntags:\n  - Energy\n  - Federal Government\n  - Marine\n  - Oceans\n  - GIS\n  - Offshore\n  - Environmental\ntype: Index\nx-type: government\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-30'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  The Bureau of Ocean Energy Management (BOEM) manages the nation's offshore\n  resources in an environmentally and economically responsible way. BOEM\n  oversees the responsible development of U.S. Outer Continental Shelf energy\n  and mineral resources while protecting the environment and conserving natural\n  resources.\napis:\n  - aid: bureau-of-ocean-energy-management:marine-cadastre\n    name: MarineCadastre.gov\n    tags:\n      - Federal Government\n\
  \      - Marine\n      - GIS\n      - Oceans\n    humanURL: https://marinecadastre.gov/\n    baseURL: https://hub.marinecadastre.gov/\n    properties:\n      - url: https://hub.marinecadastre.gov/\n        type: Portal\n      - url: https://marinecadastre.gov/oceanreports\n        type: Tool\n    description: >-\n      MarineCadastre.gov is the authoritative source for marine cadastre data\n      and services. It provides an interactive map viewer with integrated\n      submerged lands information including legal, property ownership (cadastre),\n      physical, biological, ocean uses, and cultural information. Includes Web\n      Map Services (WMS) for GIS integration and downloadable data layers.\n    features:\n      - Web Map Services (WMS)\n      - Interactive Map Viewer\n      - OceanReports Analysis Tool\n      - AIS Vessel Traffic Data\n      - Downloadable Geospatial Layers\n      - Legal and Cadastral Data\n    useCases:\n      - Offshore energy project planning\n      - Marine\
  \ spatial planning\n      - Environmental impact assessment\n      - Coastal and ocean use analysis\n  - aid: bureau-of-ocean-energy-management:boem-arcgis-rest-services\n    name: BOEM ArcGIS REST Services\n    tags:\n      - Federal Government\n      - GIS\n      - Oceans\n      - Offshore\n    humanURL: https://www.boem.gov/oil-gas-energy/mapping-and-data\n    baseURL: https://gis.boem.gov/arcgis/rest/services/\n    properties:\n      - url: https://www.boem.gov/oil-gas-energy/mapping-and-data\n        type: Documentation\n      - url: https://catalog.data.gov/dataset?organization=boem-gov\n        type: DataAPI\n    description: >-\n      BOEM provides ArcGIS REST Services exposing geospatial data for the Outer\n      Continental Shelf (OCS) regions. Data includes active leases, offshore\n      block grids, boundaries, wells, and pipelines for Atlantic, Gulf of Mexico,\n      Pacific, and Alaska regions.\n    features:\n      - Active Lease Boundaries\n      - Offshore Block Grids\n\
  \      - Pipeline Data\n      - Well Locations\n      - OCS Planning Areas\n      - Regional Shapefiles\n    useCases:\n      - Offshore drilling planning\n      - Lease management\n      - Environmental review\n      - Marine infrastructure mapping\n  - aid: bureau-of-ocean-energy-management:espis\n    name: Environmental Studies Program Information System (ESPIS)\n    tags:\n      - Federal Government\n      - Environmental\n      - Marine\n    humanURL: https://esp-boem.hub.arcgis.com/\n    properties:\n      - url: https://esp-boem.hub.arcgis.com/\n        type: Portal\n    description: >-\n      ESPIS provides access to BOEM's environmental studies data, including\n      research reports, environmental impact studies, and scientific literature\n      related to offshore energy development. Searchable by topic, location,\n      and year.\n    features:\n      - Environmental Studies Database\n      - Research Reports\n      - Scientific Literature\n      - Geographic Search\n    useCases:\n\
  \      - Environmental impact research\n      - Offshore energy regulation compliance\n      - Academic marine research\n      - Policy development\ncommon:\n  - type: Website\n    url: https://www.boem.gov\n  - type: Portal\n    url: https://marinecadastre.gov/\n  - type: Privacy Policy\n    url: https://www.boem.gov/privacy-policy\n  - type: Mapping and Data\n    url: https://www.boem.gov/oil-gas-energy/mapping-and-data\n  - type: Data Portal\n    url: https://catalog.data.gov/dataset?organization=boem-gov\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bureau-of-ocean-energy-management/refs/heads/main/apis.yml
tags:
- Energy
- Federal Government
- Marine
- Oceans
- GIS
- Offshore
- Environmental
url: https://raw.githubusercontent.com/api-evangelist/bureau-of-ocean-energy-management/refs/heads/main/apis.yml
use_cases: []
---
