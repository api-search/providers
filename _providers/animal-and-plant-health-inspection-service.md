---
api_count: 4
apis:
- description: The APHIS Public Search Tool provides public access to search APHIS program data, permits, and regulatory information related to animal and plant health programs.
  name: APHIS Public Search Tool
  slug: aphis-public-search-api
- description: APHIS eFile is the web-based permitting system for submitting animal and plant health import/export permit applications, tracking application status, applying for renewals and amendments, and receivin
  name: APHIS eFile Permitting System
  slug: aphis-efile-api
- description: The Agricultural Commodity Import Requirements (ACIR) system provides searchable access to APHIS import requirements for agricultural commodities, including plants, plant products, animals, and animal
  name: Agricultural Commodity Import Requirements (ACIR)
  slug: aphis-acir-api
- description: The APHIS and AMS Geospatial Hub provides GIS mapping applications, spatial data layers, and geospatial analysis tools for animal and plant health surveillance, pest and disease tracking, and quaranti
  name: APHIS and AMS Geospatial Hub
  slug: aphis-geospatial-hub
common:
- title: ''
  type: Website
  url: https://www.aphis.usda.gov/
- title: ''
  type: Portal
  url: https://www.aphis.usda.gov/efile
- title: ''
  type: Portal
  url: https://efile.aphis.usda.gov/s/
- title: ''
  type: Portal
  url: https://acir.aphis.usda.gov/s/
- title: ''
  type: Portal
  url: https://aphis.my.site.com/PublicSearchTool/s/
- title: ''
  type: GISPortal
  url: https://www.aphis.usda.gov/aphis-ams-geospatial-hub
- title: ''
  type: DataVisualization
  url: https://www.aphis.usda.gov/data-visualization-tools
- title: ''
  type: DataAPI
  url: https://www.aphis.usda.gov/wildlife-services/publications/pdr
- title: ''
  type: OpenData
  url: https://catalog.data.gov/organization/aphis-usda-gov
- title: ''
  type: Contact
  url: https://www.aphis.usda.gov/contact/mrpbs-informatics
- title: ''
  type: FOIA
  url: https://www.aphis.usda.gov/about/foia
- title: ''
  type: PrivacyPolicy
  url: https://www.aphis.usda.gov/about/privacy-policy
created: '2024-11-21'
description: USDA's Animal and Plant Health Inspection Service (APHIS) protects the health and value of U.S. agriculture and natural resources by safeguarding against agricultural pests and diseases, ensuring the welfare of animals, and supporting sustainable agricultural practices. APHIS provides digital services including the eFile permitting system for import/export permits, the Agricultural Commodity Import Requirements (ACIR) portal, a geospatial hub for spatial analysis, data visualization tools, and open datasets via data.gov.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-19'
name: Animal and Plant Health Inspection Service
skills: []
slug: animal-and-plant-health-inspection-service
solutions: []
source_filename: apis.yml
source_yaml: "aid: animal-and-plant-health-inspection-service\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/animal-and-plant-health-inspection-service/refs/heads/main/apis.yml\napis:\n  - aid: animal-and-plant-health-inspection-service:aphis-public-search-api\n    name: APHIS Public Search Tool\n    tags:\n      - Agriculture\n      - Animal Health\n      - Federal Government\n      - Permits\n      - Plant Health\n      - Search\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://aphis.my.site.com/PublicSearchTool/s/\n    humanURL: https://aphis.my.site.com/PublicSearchTool/s/\n    properties:\n      - url: https://aphis.my.site.com/PublicSearchTool/s/\n        type: Portal\n    description: >-\n      The APHIS Public Search Tool provides public access to search APHIS\n      program data, permits, and regulatory information related to animal and\n      plant health programs.\n  - aid: animal-and-plant-health-inspection-service:aphis-efile-api\n\
  \    name: APHIS eFile Permitting System\n    tags:\n      - Agriculture\n      - Animal Health\n      - Federal Government\n      - Import Export\n      - Permits\n      - Plant Health\n      - Regulatory\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://efile.aphis.usda.gov\n    humanURL: https://efile.aphis.usda.gov/s/\n    properties:\n      - url: https://efile.aphis.usda.gov/s/\n        type: Portal\n      - url: https://www.aphis.usda.gov/efile\n        type: Documentation\n    description: >-\n      APHIS eFile is the web-based permitting system for submitting animal and\n      plant health import/export permit applications, tracking application status,\n      applying for renewals and amendments, and receiving permit copies online.\n      Integrated with CBP's ACE system for automated permit verification at ports\n      of entry. Requires USDA eAuthentication account.\n  - aid: animal-and-plant-health-inspection-service:aphis-acir-api\n\
  \    name: Agricultural Commodity Import Requirements (ACIR)\n    tags:\n      - Agriculture\n      - Commodities\n      - Federal Government\n      - Import\n      - Plant Health\n      - Regulatory\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://acir.aphis.usda.gov\n    humanURL: https://acir.aphis.usda.gov/s/\n    properties:\n      - url: https://acir.aphis.usda.gov/s/\n        type: Portal\n    description: >-\n      The Agricultural Commodity Import Requirements (ACIR) system provides\n      searchable access to APHIS import requirements for agricultural commodities,\n      including plants, plant products, animals, and animal products by country\n      of origin.\n  - aid: animal-and-plant-health-inspection-service:aphis-geospatial-hub\n    name: APHIS and AMS Geospatial Hub\n    tags:\n      - Agriculture\n      - Animal Health\n      - Federal Government\n      - Geospatial\n      - GIS\n      - Mapping\n      - Plant\
  \ Health\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://www.aphis.usda.gov/aphis-ams-geospatial-hub\n    humanURL: https://www.aphis.usda.gov/aphis-ams-geospatial-hub\n    properties:\n      - url: https://www.aphis.usda.gov/aphis-ams-geospatial-hub\n        type: Portal\n      - url: https://www.aphis.usda.gov/plant-pests-diseases/mobile-data-collection/gis-portal\n        type: GISPortal\n    description: >-\n      The APHIS and AMS Geospatial Hub provides GIS mapping applications,\n      spatial data layers, and geospatial analysis tools for animal and plant\n      health surveillance, pest and disease tracking, and quarantine management.\nname: Animal and Plant Health Inspection Service\ntags:\n  - Agriculture\n  - Animal Health\n  - Animal Welfare\n  - Biotechnology\n  - Federal Government\n  - Import Export\n  - Permits\n  - Pest Control\n  - Plant Health\n  - Regulatory\n  - USDA\n  - Wildlife\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  access: Government\ncommon:\n  - url: https://www.aphis.usda.gov/\n    name: APHIS Website\n    type: Website\n  - url: https://www.aphis.usda.gov/efile\n    name: APHIS eFile Permitting Portal\n    type: Portal\n  - url: https://efile.aphis.usda.gov/s/\n    name: APHIS eFile Application\n    type: Portal\n  - url: https://acir.aphis.usda.gov/s/\n    name: Agricultural Commodity Import Requirements\n    type: Portal\n  - url: https://aphis.my.site.com/PublicSearchTool/s/\n    name: APHIS Public Search Tool\n    type: Portal\n  - url: https://www.aphis.usda.gov/aphis-ams-geospatial-hub\n    name: APHIS Geospatial Hub\n    type: GISPortal\n  - url: https://www.aphis.usda.gov/data-visualization-tools\n    name: APHIS Data Visualization Tools\n    type: DataVisualization\n  - url: https://www.aphis.usda.gov/wildlife-services/publications/pdr\n    name: APHIS Wildlife Services Program Data Reports\n    type: DataAPI\n  - url: https://catalog.data.gov/organization/aphis-usda-gov\n    name: APHIS\
  \ Datasets on Data.gov\n    type: OpenData\n  - url: https://www.aphis.usda.gov/contact/mrpbs-informatics\n    name: Contact APHIS\n    type: Contact\n  - url: https://www.aphis.usda.gov/about/foia\n    name: FOIA Requests\n    type: FOIA\n  - url: https://www.aphis.usda.gov/about/privacy-policy\n    name: Privacy Policy\n    type: PrivacyPolicy\ncreated: '2024-11-21'\nmodified: '2026-04-19'\nposition: Consumer\ndescription: >-\n  USDA's Animal and Plant Health Inspection Service (APHIS) protects the health\n  and value of U.S. agriculture and natural resources by safeguarding against\n  agricultural pests and diseases, ensuring the welfare of animals, and\n  supporting sustainable agricultural practices. APHIS provides digital services\n  including the eFile permitting system for import/export permits, the\n  Agricultural Commodity Import Requirements (ACIR) portal, a geospatial hub\n  for spatial analysis, data visualization tools, and open datasets via data.gov.\nmaintainers:\n  - FN:\
  \ Kin Lane\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/animal-and-plant-health-inspection-service/refs/heads/main/apis.yml
tags:
- Agriculture
- Animal Health
- Animal Welfare
- Biotechnology
- Federal Government
- Import Export
- Permits
- Pest Control
- Plant Health
- Regulatory
- USDA
- Wildlife
url: https://raw.githubusercontent.com/api-evangelist/animal-and-plant-health-inspection-service/refs/heads/main/apis.yml
use_cases: []
---
