---
api_count: 4
apis:
- description: Envirofacts provides a single point of access to U.S. EPA environmental data contained in U.S. EPA databases. The RESTful Data Service API returns output in JSON, CSV, Excel, HTML, JSONP, Parquet, PDF
  name: EPA Envirofacts Data Service API
  slug: envirofacts
- description: The EPA Air Quality System (AQS) API provides programmatic access to ambient air pollution data collected by the EPA, state, local, and tribal air pollution control agencies, including hourly sample d
  name: EPA Air Quality System API
  slug: aqs
- description: The EPA UV Index API provides hourly and daily ultraviolet radiation forecasts by ZIP code or city/state. Output is available in XML, JSON, Excel, and CSV formats.
  name: EPA UV Index API
  slug: uv-index
- description: Enforcement and Compliance History Online (ECHO) provides public access to compliance and enforcement information for EPA-regulated facilities nationwide. The ECHO web services API supports facility s
  name: EPA ECHO Compliance and Enforcement API
  slug: echo
common:
- title: ''
  type: Website
  url: https://www.epa.gov/
- title: ''
  type: Developer Central
  url: https://www.epa.gov/developers
- title: ''
  type: Web Services
  url: https://www.epa.gov/enviro/web-services
- title: ''
  type: Open Data
  url: https://www.data.gov/
created: '2024-12-03'
description: The U.S. Environmental Protection Agency (EPA) provides multiple public data APIs covering environmental records, air quality monitoring, UV forecasts, and internal data holdings. These services enable State and local governments, federal agencies, researchers, and the public to access environmental data about air, water, and land.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Environmental Protection Agency
skills: []
slug: environmental-protection-agency
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: environmental-protection-agency\nname: Environmental Protection Agency\ndescription: >-\n  The U.S. Environmental Protection Agency (EPA) provides multiple public\n  data APIs covering environmental records, air quality monitoring, UV\n  forecasts, and internal data holdings. These services enable State and\n  local governments, federal agencies, researchers, and the public to\n  access environmental data about air, water, and land.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Environment\n  - Federal Government\n  - Air Quality\n  - Open Data\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/environmental-protection-agency/refs/heads/main/apis.yml\ncreated: '2024-12-03'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nposition: Consumer\naccess: 3rd-Party\napis:\n  - aid: environmental-protection-agency:envirofacts\n    name: EPA Envirofacts Data Service API\n    description: >-\n      Envirofacts\
  \ provides a single point of access to U.S. EPA environmental\n      data contained in U.S. EPA databases. The RESTful Data Service API\n      returns output in JSON, CSV, Excel, HTML, JSONP, Parquet, PDF, or XML\n      formats and supports queries across any Envirofacts table.\n    humanURL: https://www.epa.gov/enviro/envirofacts-data-service-api\n    baseURL: https://data.epa.gov/efservice/\n    tags:\n      - Environment\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://www.epa.gov/enviro/envirofacts-data-service-api\n      - type: Web Services\n        url: https://www.epa.gov/enviro/web-services\n  - aid: environmental-protection-agency:aqs\n    name: EPA Air Quality System API\n    description: >-\n      The EPA Air Quality System (AQS) API provides programmatic access to\n      ambient air pollution data collected by the EPA, state, local, and\n      tribal air pollution control agencies, including hourly sample data,\n      daily/quarterly/annual\
  \ summaries, monitor information, and quality\n      assurance data. JSON response format with API key authentication.\n    humanURL: https://aqs.epa.gov/aqsweb/documents/data_api.html\n    baseURL: https://aqs.epa.gov/data/api\n    tags:\n      - Environment\n      - Air Quality\n    properties:\n      - type: Documentation\n        url: https://aqs.epa.gov/aqsweb/documents/data_api.html\n      - type: Sign Up\n        url: https://aqs.epa.gov/data/api/signup\n  - aid: environmental-protection-agency:uv-index\n    name: EPA UV Index API\n    description: >-\n      The EPA UV Index API provides hourly and daily ultraviolet radiation\n      forecasts by ZIP code or city/state. Output is available in XML,\n      JSON, Excel, and CSV formats.\n    humanURL: https://www.epa.gov/enviro/web-services\n    baseURL: https://data.epa.gov/efservice/getEnvirofactsUVHOURLY/\n    tags:\n      - Environment\n      - UV Index\n    properties:\n      - type: Documentation\n        url: https://www.epa.gov/enviro/web-services\n\
  \  - aid: environmental-protection-agency:echo\n    name: EPA ECHO Compliance and Enforcement API\n    description: >-\n      Enforcement and Compliance History Online (ECHO) provides public\n      access to compliance and enforcement information for EPA-regulated\n      facilities nationwide. The ECHO web services API supports facility\n      searches, compliance reports, and enforcement case lookups.\n    humanURL: https://echo.epa.gov/tools/web-services\n    baseURL: https://echodata.epa.gov/echo/\n    tags:\n      - Environment\n      - Compliance\n      - Enforcement\n    properties:\n      - type: Documentation\n        url: https://echo.epa.gov/tools/web-services\ncommon:\n  - type: Website\n    url: https://www.epa.gov/\n  - type: Developer Central\n    url: https://www.epa.gov/developers\n  - type: Web Services\n    url: https://www.epa.gov/enviro/web-services\n  - type: Open Data\n    url: https://www.data.gov/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/environmental-protection-agency/refs/heads/main/apis.yml
tags:
- Environment
- Federal Government
- Air Quality
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/environmental-protection-agency/refs/heads/main/apis.yml
use_cases: []
---
