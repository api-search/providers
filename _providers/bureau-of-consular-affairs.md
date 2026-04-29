---
api_count: 3
apis:
- description: The CA Data Catalog provides access to datasets from the Bureau of Consular Affairs via the CKAN API. It includes passport issuance statistics, visa issuance data, adoption statistics, and other consu
  name: Bureau of Consular Affairs Data Catalog (CKAN API)
  slug: ca-data-catalog-ckan-api
- description: The State Department publishes travel advisory levels (Level 1-4) for every country. Advisory data is available for consumption by travel applications and services to help inform travelers about safet
  name: Travel Advisories API
  slug: travel-advisories
- description: Annual and monthly passport issuance statistics published by the Bureau of Consular Affairs, available as downloadable datasets through the CA data catalog.
  name: Passport Issuance Statistics
  slug: passport-issuance-statistics
common:
- title: ''
  type: Website
  url: https://travel.state.gov/
- title: ''
  type: Portal
  url: https://cadatacatalog.state.gov/
- title: ''
  type: Privacy Policy
  url: https://travel.state.gov/content/travel/en/legal/privacy-policy.html
- title: ''
  type: CKAN API
  url: https://cadatacatalog.state.gov/api/3/action/package_list
- title: ''
  type: Statistics
  url: https://travel.state.gov/content/travel/en/legal/visa-law0/visa-statistics.html
created: '2024-11-25'
description: The Bureau of Consular Affairs (CA) is a bureau of the United States Department of State responsible for administering laws, formulating regulations, and implementing policies related to consular services and immigration. CA provides travel advisories, passport and visa information, and publishes datasets through its data catalog accessible via the CKAN API.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bureau of Consular Affairs
skills: []
slug: bureau-of-consular-affairs
solutions: []
source_filename: apis.yml
source_yaml: "aid: bureau-of-consular-affairs\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bureau-of-consular-affairs/refs/heads/main/apis.yml\nname: Bureau of Consular Affairs\ntags:\n  - Federal Government\n  - Passports\n  - Travel\n  - Travel Advisories\n  - Visas\ntype: Index\nx-type: government\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-25'\nmodified: '2026-04-21'\nposition: Consumer\ndescription: >-\n  The Bureau of Consular Affairs (CA) is a bureau of the United States\n  Department of State responsible for administering laws, formulating regulations,\n  and implementing policies related to consular services and immigration.\n  CA provides travel advisories, passport and visa information, and publishes\n  datasets through its data catalog accessible via the CKAN API.\napis:\n  - aid: bureau-of-consular-affairs:ca-data-catalog-ckan-api\n    name: Bureau of Consular Affairs Data Catalog (CKAN\
  \ API)\n    tags:\n      - CKAN\n      - Data Catalog\n      - Federal Government\n      - Open Data\n    humanURL: https://cadatacatalog.state.gov/\n    baseURL: https://cadatacatalog.state.gov/api/3/action\n    properties:\n      - url: https://cadatacatalog.state.gov/dataset/\n        type: Documentation\n      - url: https://cadatacatalog.state.gov/api/3\n        type: DataAPI\n    description: >-\n      The CA Data Catalog provides access to datasets from the Bureau of\n      Consular Affairs via the CKAN API. It includes passport issuance statistics,\n      visa issuance data, adoption statistics, and other consular affairs data.\n      The CKAN API supports dataset search, retrieval, and resource downloads.\n  - aid: bureau-of-consular-affairs:travel-advisories\n    name: Travel Advisories API\n    tags:\n      - Federal Government\n      - Travel\n      - Travel Advisories\n    humanURL: https://travel.state.gov/content/travel/en/traveladvisories/traveladvisories.html/\n    baseURL:\
  \ https://travel.state.gov\n    properties:\n      - url: https://travel.state.gov/content/travel/en/traveladvisories/traveladvisories.html/\n        type: Documentation\n      - url: https://travelmaps.state.gov/TSGMap/\n        type: DataAPI\n    description: >-\n      The State Department publishes travel advisory levels (Level 1-4) for\n      every country. Advisory data is available for consumption by travel\n      applications and services to help inform travelers about safety conditions.\n  - aid: bureau-of-consular-affairs:passport-issuance-statistics\n    name: Passport Issuance Statistics\n    tags:\n      - Federal Government\n      - Passports\n      - Statistics\n    humanURL: https://cadatacatalog.state.gov/dataset/passportstatistics\n    properties:\n      - url: https://cadatacatalog.state.gov/dataset/passportstatistics\n        type: DataAPI\n      - url: https://cadatacatalog.state.gov/dataset/passportstatistics\n        type: Documentation\n    description: >-\n    \
  \  Annual and monthly passport issuance statistics published by the Bureau\n      of Consular Affairs, available as downloadable datasets through the CA\n      data catalog.\ncommon:\n  - type: Website\n    url: https://travel.state.gov/\n  - type: Portal\n    url: https://cadatacatalog.state.gov/\n  - type: Privacy Policy\n    url: https://travel.state.gov/content/travel/en/legal/privacy-policy.html\n  - type: CKAN API\n    url: https://cadatacatalog.state.gov/api/3/action/package_list\n  - type: Statistics\n    url: https://travel.state.gov/content/travel/en/legal/visa-law0/visa-statistics.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bureau-of-consular-affairs/refs/heads/main/apis.yml
tags:
- Federal Government
- Passports
- Travel
- Travel Advisories
- Visas
url: https://raw.githubusercontent.com/api-evangelist/bureau-of-consular-affairs/refs/heads/main/apis.yml
use_cases: []
---
