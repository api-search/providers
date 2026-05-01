---
api_count: 4
apis:
- description: The HUD USER FMR/IL API publishes Fair Market Rents (FMRs), Small Area Fair Market Rents, and Income Limits (IL) for U.S. metropolitan and non-metropolitan areas. It exposes endpoints for listing stat
  name: HUD USER FMR/IL API
  slug: hud-user-fmr-il-api
- description: The HUD eGIS storefront publishes ArcGIS-based REST services and feature layers for the Department's geospatial assets, including Continuum of Care boundaries, CPD activities, public housing locations
  name: HUD eGIS ArcGIS REST Services
  slug: hud-egis-arcgis
- description: The FHA Mortgage Limits service lets users look up the FHA or Government-Sponsored Enterprise (GSE) mortgage limits for one or more areas, by state, county, or Metropolitan Statistical Area, with resu
  name: FHA Mortgage Limits
  slug: fha-mortgage-limits
- description: The HUD Open Data Catalog at data.hud.gov is curated by HUD's Office of the Chief Data Officer and lists the Department's open datasets across housing, community development, and fair housing. Dataset
  name: HUD Open Data Catalog
  slug: hud-data-catalog
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.hud.gov
- title: ''
  type: Open Data
  url: https://data.hud.gov/
- title: ''
  type: HUD USER
  url: https://www.huduser.gov/portal/home.html
- title: ''
  type: HUD GIS
  url: https://hudgis-hud.opendata.arcgis.com/
- title: ''
  type: FHA
  url: https://www.hud.gov/fha
- title: ''
  type: HUD Exchange
  url: https://www.hudexchange.info/
- title: ''
  type: News
  url: https://www.hud.gov/press
- title: ''
  type: Contact
  url: https://www.hud.gov/contact_us
- title: ''
  type: Privacy Policy
  url: https://www.hud.gov/notices/privacy_policy
- title: ''
  type: Data.gov HUD Catalog
  url: https://catalog.data.gov/organization/hud-gov
- title: ''
  type: GitHub Organization
  url: https://github.com/HUD-USER
- title: ''
  type: JSON-LD
  url: json-ld/department-of-housing-and-urban-development-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/department-of-housing-and-urban-development-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/department-of-housing-and-urban-development-capabilities.yml
created: '2024-12-25'
description: The U.S. Department of Housing and Urban Development (HUD) is the federal agency responsible for overseeing programs that address the country's housing needs and promote sustainable urban development. HUD exposes programmatic data through the HUD USER FMR/IL API for Fair Market Rents and Income Limits, the HUD eGIS storefront and ArcGIS REST services for geospatial assets, the data.hud.gov data catalog, and various FHA tools including mortgage limits and condominium lookup services.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Department Of Housing And Urban Development Context
  property_count: 5
  slug: department-of-housing-and-urban-development-context
layout: provider
modified: '2026-04-28'
name: Department of Housing and Urban Development
skills: []
slug: department-of-housing-and-urban-development
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: department-of-housing-and-urban-development\nname: Department of Housing and Urban Development\ndescription: >-\n  The U.S. Department of Housing and Urban Development (HUD) is the federal\n  agency responsible for overseeing programs that address the country's\n  housing needs and promote sustainable urban development. HUD exposes\n  programmatic data through the HUD USER FMR/IL API for Fair Market Rents and\n  Income Limits, the HUD eGIS storefront and ArcGIS REST services for\n  geospatial assets, the data.hud.gov data catalog, and various FHA tools\n  including mortgage limits and condominium lookup services.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Affordable Housing\n  - Fair Market Rents\n  - Federal Government\n  - FHA\n  - GIS\n  - Housing\n  - HUD\n  - Income Limits\n  - Mortgage\n  - Open Data\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/department-of-housing-and-urban-development/refs/heads/main/apis.yml\n\
  created: '2024-12-25'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: government\nposition: Producer\naccess: Public\napis:\n  - aid: department-of-housing-and-urban-development:hud-user-fmr-il-api\n    name: HUD USER FMR/IL API\n    description: >-\n      The HUD USER FMR/IL API publishes Fair Market Rents (FMRs), Small Area\n      Fair Market Rents, and Income Limits (IL) for U.S. metropolitan and\n      non-metropolitan areas. It exposes endpoints for listing states,\n      metros, and counties as well as retrieving annual FMR and IL values for\n      specified geographies and fiscal years. Access requires a free token\n      obtained from the HUD USER portal.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.huduser.gov/portal/dataset/fmr-api.html\n    baseURL: https://www.huduser.gov/hudapi/public\n    tags:\n      - Fair Market Rents\n      - Housing\n      - HUD USER\n      - Income Limits\n      - PD&R\n\
  \    properties:\n      - type: Documentation\n        url: https://www.huduser.gov/portal/dataset/fmr-api.html\n      - type: Datasets\n        url: https://www.huduser.gov/portal/pdrdatas_landing.html\n      - type: FMR Data\n        url: https://www.huduser.gov/portal/datasets/fmr.html\n      - type: Income Limits\n        url: https://www.huduser.gov/portal/datasets/il.html\n      - type: Sign Up\n        url: https://www.huduser.gov/hudapi/public/register\n    contact:\n      - FN: HUD USER\n        email: helpdesk@huduser.gov\n        url: https://www.huduser.gov/portal/home.html\n  - aid: department-of-housing-and-urban-development:hud-egis-arcgis\n    name: HUD eGIS ArcGIS REST Services\n    description: >-\n      The HUD eGIS storefront publishes ArcGIS-based REST services and feature\n      layers for the Department's geospatial assets, including Continuum of\n      Care boundaries, CPD activities, public housing locations, low-income\n      housing tax credit properties, and\
  \ HUD-administered geographies. The\n      services are accessible via the HUD-GIS open data portal as well as\n      directly from egis.hud.gov.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://hudgis-hud.opendata.arcgis.com/\n    baseURL: https://egis.hud.gov/ArcGIS/rest/services\n    tags:\n      - ArcGIS\n      - eGIS\n      - Geospatial\n      - GIS\n      - HUD\n    properties:\n      - type: Open Data Portal\n        url: https://hudgis-hud.opendata.arcgis.com/\n      - type: ArcGIS Services\n        url: https://egis.hud.gov/ArcGIS/rest/services\n      - type: HUD CPD Activities Service\n        url: https://egis.hud.gov/ArcGIS/rest/services/cpdmaps/HudCpdActivities/MapServer\n      - type: GIS Tools\n        url: https://www.hudexchange.info/programs/coc/gis-tools/\n    contact:\n      - FN: HUD GIS\n        email: gis_helpdesk@hud.gov\n        url: https://hudgis-hud.opendata.arcgis.com/\n  - aid: department-of-housing-and-urban-development:fha-mortgage-limits\n\
  \    name: FHA Mortgage Limits\n    description: >-\n      The FHA Mortgage Limits service lets users look up the FHA or\n      Government-Sponsored Enterprise (GSE) mortgage limits for one or more\n      areas, by state, county, or Metropolitan Statistical Area, with\n      results that also include a Median Sale Price for each jurisdiction.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://entp.hud.gov/idapp/html/hicostlook.cfm\n    baseURL: https://entp.hud.gov\n    tags:\n      - FHA\n      - Lookup\n      - Mortgage Limits\n    properties:\n      - type: Documentation\n        url: https://entp.hud.gov/idapp/html/hicostlook.cfm\n      - type: FHA Resources\n        url: https://www.hud.gov/fha\n    contact:\n      - FN: HUD FHA\n        url: https://www.hud.gov/contact_us\n  - aid: department-of-housing-and-urban-development:hud-data-catalog\n    name: HUD Open Data Catalog\n    description: >-\n      The HUD Open Data Catalog\
  \ at data.hud.gov is curated by HUD's Office of\n      the Chief Data Officer and lists the Department's open datasets across\n      housing, community development, and fair housing. Datasets are\n      cross-listed on Data.gov and accessible via Data.gov's CKAN-compatible\n      API.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://data.hud.gov/\n    baseURL: https://catalog.data.gov/api/3\n    tags:\n      - CKAN\n      - Datasets\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://data.hud.gov/open_data\n      - type: Datasets\n        url: https://data.hud.gov/datasets\n      - type: Data.gov HUD Catalog\n        url: https://catalog.data.gov/organization/hud-gov\n      - type: CKAN Reference\n        url: https://docs.ckan.org/en/2.8/api/\n    contact:\n      - FN: HUD Open Data\n        email: OpenData@hud.gov\n        url: https://data.hud.gov/\ncommon:\n  - type: Website\n    url: https://www.hud.gov\n\
  \  - type: Open Data\n    url: https://data.hud.gov/\n  - type: HUD USER\n    url: https://www.huduser.gov/portal/home.html\n  - type: HUD GIS\n    url: https://hudgis-hud.opendata.arcgis.com/\n  - type: FHA\n    url: https://www.hud.gov/fha\n  - type: HUD Exchange\n    url: https://www.hudexchange.info/\n  - type: News\n    url: https://www.hud.gov/press\n  - type: Contact\n    url: https://www.hud.gov/contact_us\n  - type: Privacy Policy\n    url: https://www.hud.gov/notices/privacy_policy\n  - type: Data.gov HUD Catalog\n    url: https://catalog.data.gov/organization/hud-gov\n  - type: GitHub Organization\n    url: https://github.com/HUD-USER\n  - type: JSON-LD\n    url: json-ld/department-of-housing-and-urban-development-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/department-of-housing-and-urban-development-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/department-of-housing-and-urban-development-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email:\
  \ kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/department-of-housing-and-urban-development/refs/heads/main/apis.yml
tags:
- Affordable Housing
- Fair Market Rents
- Federal Government
- FHA
- GIS
- Housing
- HUD
- Income Limits
- Mortgage
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/department-of-housing-and-urban-development/refs/heads/main/apis.yml
use_cases: []
---
