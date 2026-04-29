---
api_count: 4
apis:
- description: The BLM Geospatial Business Platform is a public tool and publication platform for exploring and downloading GIS data. Built on ArcGIS Online, it provides REST endpoints for BLM geospatial data includ
  name: BLM Geospatial Business Platform (GBP) Hub
  slug: blm-geospatial-business-platform
- description: 'The Mineral and Land Records System (MLRS) is an online platform delivering state-of-the-art mineral and land records transactions, tracking, mapping, and more for BLM customers and staff. It manages '
  name: BLM Mineral and Land Records System (MLRS)
  slug: blm-mineral-land-records
- description: The General Land Office (GLO) Records provide access to federal land conveyance records including land patents, survey plats, and field notes from 1788 to the present. The system contains over 10 mill
  name: BLM General Land Office Records
  slug: blm-general-land-office-records
- description: BLM ePlanning provides public access to land use planning documents, environmental impact statements, and resource management plans. Citizens can track planning projects and participate in comment per
  name: BLM ePlanning
  slug: blm-eplanning
common:
- title: ''
  type: Website
  url: https://www.blm.gov
- title: ''
  type: Portal
  url: https://gbp-blm-egis.hub.arcgis.com/
- title: ''
  type: Privacy Policy
  url: https://www.blm.gov/privacy-policy
- title: ''
  type: Data Portal
  url: https://catalog.data.gov/dataset?organization=blm-gov
created: '2024-11-30'
description: The Bureau of Land Management (BLM) is a U.S. government agency responsible for managing vast stretches of public lands across the country, primarily focused on activities like outdoor recreation, livestock grazing, mineral development, and energy production, aiming to sustain the health and diversity of these lands for future generations.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Bureau of Land Management
skills: []
slug: bureau-of-land-management
solutions: []
source_filename: apis.yml
source_yaml: "aid: bureau-of-land-management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bureau-of-land-management/refs/heads/main/apis.yml\nname: Bureau of Land Management\ntags:\n  - Environment\n  - Federal Government\n  - Land\n  - Resources\n  - GIS\n  - Geospatial\n  - Mining\ntype: Index\nx-type: government\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-30'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  The Bureau of Land Management (BLM) is a U.S. government agency responsible\n  for managing vast stretches of public lands across the country, primarily\n  focused on activities like outdoor recreation, livestock grazing, mineral\n  development, and energy production, aiming to sustain the health and diversity\n  of these lands for future generations.\napis:\n  - aid: bureau-of-land-management:blm-geospatial-business-platform\n    name: BLM Geospatial Business Platform (GBP) Hub\n\
  \    tags:\n      - Federal Government\n      - Geospatial\n      - GIS\n      - Land\n    humanURL: https://gbp-blm-egis.hub.arcgis.com/\n    baseURL: https://blm-egis.maps.arcgis.com/sharing/rest/\n    properties:\n      - url: https://gbp-blm-egis.hub.arcgis.com/\n        type: Portal\n      - url: https://blm-egis.maps.arcgis.com/home/index.html\n        type: Documentation\n      - url: https://catalog.data.gov/dataset?organization=blm-gov\n        type: DataAPI\n    description: >-\n      The BLM Geospatial Business Platform is a public tool and publication\n      platform for exploring and downloading GIS data. Built on ArcGIS Online,\n      it provides REST endpoints for BLM geospatial data including public lands\n      boundaries, mineral resources, recreation areas, and environmental data.\n    features:\n      - ArcGIS REST Endpoints\n      - ISO-19139 XML Metadata\n      - DCAT-US Compliance\n      - Keyword and Location Search\n      - Public Land Records\n    useCases:\n\
  \      - Public lands research\n      - Recreation planning\n      - Environmental impact assessment\n      - Mineral rights research\n  - aid: bureau-of-land-management:blm-mineral-land-records\n    name: BLM Mineral and Land Records System (MLRS)\n    tags:\n      - Federal Government\n      - Land\n      - Mining\n      - Minerals\n    humanURL: https://mlrs.blm.gov/s/\n    properties:\n      - url: https://mlrs.blm.gov/s/\n        type: Portal\n    description: >-\n      The Mineral and Land Records System (MLRS) is an online platform\n      delivering state-of-the-art mineral and land records transactions,\n      tracking, mapping, and more for BLM customers and staff. It manages\n      land patents, rights-of-way, mining claims, and related records.\n    features:\n      - Mineral Records\n      - Land Patent Records\n      - Rights-of-Way Management\n      - Mining Claims\n    useCases:\n      - Mineral rights research\n      - Land patent lookup\n      - Rights-of-way applications\n\
  \      - Mining claim verification\n  - aid: bureau-of-land-management:blm-general-land-office-records\n    name: BLM General Land Office Records\n    tags:\n      - Federal Government\n      - Land\n      - Historical Records\n    humanURL: https://glorecords.blm.gov/default.aspx\n    properties:\n      - url: https://glorecords.blm.gov/default.aspx\n        type: Portal\n    description: >-\n      The General Land Office (GLO) Records provide access to federal land\n      conveyance records including land patents, survey plats, and field notes\n      from 1788 to the present. The system contains over 10 million Federal\n      land title records.\n    features:\n      - Land Patent Records\n      - Survey Plats\n      - Field Notes\n      - Historical Records Search\n    useCases:\n      - Historical land research\n      - Genealogy research\n      - Property title research\n      - Academic historical study\n  - aid: bureau-of-land-management:blm-eplanning\n    name: BLM ePlanning\n\
  \    tags:\n      - Federal Government\n      - Land Use Planning\n      - Environmental\n    humanURL: https://eplanning.blm.gov/\n    properties:\n      - url: https://eplanning.blm.gov/\n        type: Portal\n    description: >-\n      BLM ePlanning provides public access to land use planning documents,\n      environmental impact statements, and resource management plans. Citizens\n      can track planning projects and participate in comment periods.\n    features:\n      - Land Use Planning Documents\n      - Environmental Impact Statements\n      - Resource Management Plans\n      - Public Comment Access\n    useCases:\n      - Environmental review tracking\n      - Public comment participation\n      - Land use planning research\n      - Policy development support\ncommon:\n  - type: Website\n    url: https://www.blm.gov\n  - type: Portal\n    url: https://gbp-blm-egis.hub.arcgis.com/\n  - type: Privacy Policy\n    url: https://www.blm.gov/privacy-policy\n  - type: Data Portal\n\
  \    url: https://catalog.data.gov/dataset?organization=blm-gov\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bureau-of-land-management/refs/heads/main/apis.yml
tags:
- Environment
- Federal Government
- Land
- Resources
- GIS
- Geospatial
- Mining
url: https://raw.githubusercontent.com/api-evangelist/bureau-of-land-management/refs/heads/main/apis.yml
use_cases: []
---
