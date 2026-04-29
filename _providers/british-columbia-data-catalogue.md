---
api_count: 1
apis:
- description: The BC Data Catalogue exposes a CKAN v3 REST API at https://catalogue.data.gov.bc.ca/api/3/action/ providing programmatic access to BC government open datasets. Key endpoints include package_list (lis
  name: BC Data Catalogue CKAN API
  slug: ckan-api
common:
- title: ''
  type: Website
  url: https://catalogue.data.gov.bc.ca/
- title: ''
  type: APIBaseURL
  url: https://catalogue.data.gov.bc.ca/api/3/action/
- title: ''
  type: DatasetList
  url: https://catalogue.data.gov.bc.ca/api/3/action/package_list
- title: ''
  type: DatasetSearch
  url: https://catalogue.data.gov.bc.ca/api/3/action/package_search
- title: ''
  type: GovernmentPortal
  url: https://www2.gov.bc.ca/gov/content/data/bc-data-catalogue
created: '2024-11-07'
description: The British Columbia Data Catalogue is the official open data portal for the Government of British Columbia, Canada. Built on the CKAN open data platform, it provides programmatic access to thousands of BC government datasets spanning census and demographic data, environmental and climate information, geospatial and mapping data, financial reports, transportation and infrastructure data, and health and social services statistics. The CKAN API at api/3/action/ enables searching, listing, and retrieving dataset metadata and resources without authentication.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: British Columbia Data Catalogue
skills: []
slug: british-columbia-data-catalogue
solutions: []
source_yaml: "aid: british-columbia-data-catalogue\nurl: https://raw.githubusercontent.com/api-evangelist/british-columbia-data-catalogue/refs/heads/main/apis.yml\nname: British Columbia Data Catalogue\ntags:\n  - Open Data\n  - Government\n  - Canadian Government\n  - British Columbia\n  - Provincial Data\n  - CKAN\n  - Geospatial\ntype: Index\nx-type: government\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: Open\ncreated: '2024-11-07'\nmodified: '2026-04-21'\nposition: Consumer\ndescription: >-\n  The British Columbia Data Catalogue is the official open data portal for the\n  Government of British Columbia, Canada. Built on the CKAN open data platform,\n  it provides programmatic access to thousands of BC government datasets spanning\n  census and demographic data, environmental and climate information, geospatial\n  and mapping data, financial reports, transportation and infrastructure data,\n  and health and social services statistics. The\
  \ CKAN API at api/3/action/ enables\n  searching, listing, and retrieving dataset metadata and resources without authentication.\napis:\n  - aid: british-columbia-data-catalogue:ckan-api\n    name: BC Data Catalogue CKAN API\n    tags:\n      - CKAN\n      - Open Data\n      - Dataset Search\n      - Metadata\n      - Government Data\n    humanURL: https://catalogue.data.gov.bc.ca/\n    properties:\n      - url: https://catalogue.data.gov.bc.ca/\n        type: Documentation\n      - url: https://catalogue.data.gov.bc.ca/api/3\n        type: BaseURL\n    description: >-\n      The BC Data Catalogue exposes a CKAN v3 REST API at https://catalogue.data.gov.bc.ca/api/3/action/\n      providing programmatic access to BC government open datasets. Key endpoints include\n      package_list (list all datasets), package_search (search datasets by query),\n      package_show (retrieve dataset metadata and resources), organization_list\n      (list BC government organizations), and resource_show (retrieve\
  \ specific\n      data resource information). Returns JSON with success status and result payloads.\n      No authentication required for read access to public datasets.\ncommon:\n  - type: Website\n    url: https://catalogue.data.gov.bc.ca/\n  - type: APIBaseURL\n    url: https://catalogue.data.gov.bc.ca/api/3/action/\n  - type: DatasetList\n    url: https://catalogue.data.gov.bc.ca/api/3/action/package_list\n  - type: DatasetSearch\n    url: https://catalogue.data.gov.bc.ca/api/3/action/package_search\n  - type: GovernmentPortal\n    url: https://www2.gov.bc.ca/gov/content/data/bc-data-catalogue\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/british-columbia-data-catalogue/refs/heads/main/apis.yml
tags:
- Open Data
- Government
- Canadian Government
- British Columbia
- Provincial Data
- CKAN
- Geospatial
url: https://raw.githubusercontent.com/api-evangelist/british-columbia-data-catalogue/refs/heads/main/apis.yml
use_cases: []
---
