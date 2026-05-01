---
api_count: 2
api_specs:
- filename: most-wanted-api-openapi.yml
  format: yaml
  label: FBI Most Wanted
  slug: most-wanted-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/federal-bureau-of-investigation/refs/heads/main/openapi/most-wanted-api-openapi.yml
apis:
- description: The FBI Most Wanted API is designed to help developers easily get information on the FBI Wanted program, including Ten Most Wanted Fugitives, Most Wanted Terrorists, kidnappings and missing persons, a
  name: FBI Most Wanted
  slug: most-wanted-api
- description: The FBI Crime Data Explorer (CDE) provides public access to Uniform Crime Reporting (UCR) data through a JSON API. The API exposes summary statistics, agency-level participation, offense and arrest co
  name: FBI Crime Data Explorer
  slug: crime-data-explorer
common:
- title: ''
  type: Website
  url: https://www.fbi.gov/
- title: ''
  type: Documentation
  url: https://www.fbi.gov/services
created: '2024-10-18'
description: The Federal Bureau of Investigation (FBI) is the domestic intelligence and security service of the United States and its principal federal law enforcement agency. The FBI publishes public APIs covering its Most Wanted program and Uniform Crime Reporting (UCR) data through the Crime Data Explorer.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Federal Bureau of Investigation
skills: []
slug: federal-bureau-of-investigation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: federal-bureau-of-investigation\nname: Federal Bureau of Investigation\ntype: Index\ndescription: >-\n  The Federal Bureau of Investigation (FBI) is the domestic intelligence and\n  security service of the United States and its principal federal law\n  enforcement agency. The FBI publishes public APIs covering its Most Wanted\n  program and Uniform Crime Reporting (UCR) data through the Crime Data\n  Explorer.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - FBI\n  - Federal Government\ncreated: '2024-10-18'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/federal-bureau-of-investigation/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: federal-bureau-of-investigation:most-wanted-api\n    name: FBI Most Wanted\n    description: >-\n      The FBI Most Wanted API is designed to help developers easily get\n      information on the FBI Wanted program, including Ten Most Wanted\n\
  \      Fugitives, Most Wanted Terrorists, kidnappings and missing persons,\n      and seeking information cases. The API supports filtering by field\n      office and pagination of results.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.fbi.gov/wanted/api\n    baseURL: https://api.fbi.gov\n    tags:\n      - Criminals\n      - Law Enforcement\n      - Most Wanted\n    properties:\n      - type: Documentation\n        url: https://www.fbi.gov/wanted/api\n      - type: OpenAPI\n        url: openapi/most-wanted-api-openapi.yml\n  - aid: federal-bureau-of-investigation:crime-data-explorer\n    name: FBI Crime Data Explorer\n    description: >-\n      The FBI Crime Data Explorer (CDE) provides public access to Uniform\n      Crime Reporting (UCR) data through a JSON API. The API exposes summary\n      statistics, agency-level participation, offense and arrest counts, and\n      hate crime, victimization, and law enforcement officer\
  \ data drawn from\n      the National Incident-Based Reporting System (NIBRS) and Summary\n      Reporting System.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://crime-data-explorer.fbi.gov/\n    baseURL: https://api.usa.gov/crime/fbi/cde\n    tags:\n      - Crime Data\n      - Law Enforcement\n      - Statistics\n      - Uniform Crime Reporting\n    properties:\n      - type: Documentation\n        url: https://crime-data-explorer.fbi.gov/pages/docApi\n      - type: Portal\n        url: https://crime-data-explorer.fbi.gov/\ncommon:\n  - type: Website\n    url: https://www.fbi.gov/\n  - type: Documentation\n    url: https://www.fbi.gov/services\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/federal-bureau-of-investigation/refs/heads/main/apis.yml
tags:
- FBI
- Federal Government
url: https://raw.githubusercontent.com/api-evangelist/federal-bureau-of-investigation/refs/heads/main/apis.yml
use_cases: []
---
