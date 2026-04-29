---
api_count: 7
apis:
- description: 'The CDC Socrata Open Data API (SODA) provides programmatic JSON, CSV, and GeoJSON access to hundreds of data.cdc.gov datasets covering COVID-19 case surveillance, vaccination coverage, excess deaths, '
  name: CDC Socrata Open Data API (data.cdc.gov)
  slug: cdc-socrata-open-data-api
- description: CDC WONDER (Wide-ranging ONline Data for Epidemiologic Research) is a suite of public-use ad-hoc query databases covering underlying and multiple cause of death, natality, cancer statistics, tuberculo
  name: CDC WONDER API
  slug: cdc-wonder-api
- description: PLACES (Population Level Analysis and Community Estimates) provides model-based small-area estimates for chronic disease risk factors, health outcomes, and prevention practices for counties, ZCTAs, ce
  name: CDC PLACES / 500 Cities API
  slug: cdc-places-api
- description: The Environmental Public Health Tracking Network API provides a REST interface over the National Tracking Network's JSON-formatted data for air quality, water quality, climate and health, childhood le
  name: CDC Environmental Public Health Tracking Network API
  slug: cdc-ephtn-api
- description: The CDC Public Health Media Library Content Syndication API lets developers and partner sites programmatically retrieve CDC health content (articles, infographics, videos, widgets, images, and microsi
  name: CDC Public Health Media Library (Content Syndication)
  slug: cdc-content-syndication
- description: open.cdc.gov is CDC's Open Technology landing site that indexes the agency's public APIs, open-source GitHub repositories, and open data assets, serving as a catalog entry point for developers seeking
  name: CDC Open Technology API Index
  slug: open-cdc-apis-index
- description: 'The National Notifiable Diseases Surveillance System (NNDSS) and Morbidity and Mortality Weekly Report (MMWR) tables are published as Socrata datasets on data.cdc.gov, providing weekly and historical '
  name: CDC NNDSS / MMWR Socrata Data
  slug: cdc-tb-nndss-socrata
common:
- title: ''
  type: Website
  url: https://www.cdc.gov/
- title: ''
  type: OpenData
  url: https://data.cdc.gov/
- title: ''
  type: Portal
  url: https://open.cdc.gov/
- title: ''
  type: APIs
  url: https://open.cdc.gov/apis.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/CDCgov
- title: ''
  type: WONDER
  url: https://wonder.cdc.gov/
- title: ''
  type: Socrata
  url: https://dev.socrata.com/
- title: ''
  type: ContentSyndication
  url: https://tools.cdc.gov/medialibrary/
- title: ''
  type: EPHTN
  url: https://ephtracking.cdc.gov/
- title: ''
  type: Privacy Policy
  url: https://www.cdc.gov/other/privacy.html
created: '2024-12-03'
description: The Centers for Disease Control and Prevention (CDC) is the United States' national public health agency, part of the Department of Health and Human Services. CDC operates a broad portfolio of public APIs and open data services including the Socrata-powered data.cdc.gov (Open Data API for hundreds of COVID-19, chronic disease, environmental health, immunization, injury, and mortality datasets), the WONDER online query databases for mortality, natality, and cancer statistics, the PLACES / BRFSS and Environmental Public Health Tracking Network APIs, the Content Syndication platform, and the open.cdc.gov developer portal that indexes these resources for civic technologists and public-health researchers.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Centers for Disease Control and Prevention
skills: []
slug: centers-for-disease-control-and-prevention
solutions: []
source_filename: apis.yml
source_yaml: "aid: centers-for-disease-control-and-prevention\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/centers-for-disease-control-and-prevention/refs/heads/main/apis.yml\nname: Centers for Disease Control and Prevention\ntags:\n  - CDC\n  - Environmental Health\n  - Epidemiology\n  - Federal Government\n  - Healthcare\n  - Open Data\n  - Public Health\n  - Socrata\n  - Surveillance\n  - WONDER\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-04-23'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  The Centers for Disease Control and Prevention (CDC) is the United States'\n  national public health agency, part of the Department of Health and Human\n  Services. CDC operates a broad portfolio of public APIs and open data\n  services including the Socrata-powered data.cdc.gov (Open Data API for\n  hundreds of COVID-19, chronic disease, environmental\
  \ health, immunization,\n  injury, and mortality datasets), the WONDER online query databases for\n  mortality, natality, and cancer statistics, the PLACES / BRFSS and\n  Environmental Public Health Tracking Network APIs, the Content Syndication\n  platform, and the open.cdc.gov developer portal that indexes these\n  resources for civic technologists and public-health researchers.\napis:\n  - aid: centers-for-disease-control-and-prevention:cdc-socrata-open-data-api\n    name: CDC Socrata Open Data API (data.cdc.gov)\n    tags:\n      - Chronic Disease\n      - COVID-19\n      - Datasets\n      - Open Data\n      - SODA\n      - Socrata\n      - Surveillance\n    humanURL: https://data.cdc.gov/\n    baseURL: https://data.cdc.gov/resource/\n    properties:\n      - url: https://data.cdc.gov/\n        type: Website\n      - url: https://dev.socrata.com/\n        type: Documentation\n      - url: https://dev.socrata.com/docs/endpoints.html\n        type: Reference\n      - url: https://dev.socrata.com/consumers/getting-started.html\n\
  \        type: GettingStarted\n      - url: https://evergreen.data.socrata.com/signup\n        type: SignUp\n    description: >-\n      The CDC Socrata Open Data API (SODA) provides programmatic JSON, CSV,\n      and GeoJSON access to hundreds of data.cdc.gov datasets covering\n      COVID-19 case surveillance, vaccination coverage, excess deaths, flu\n      surveillance, PRAMStat, PLACES small-area estimates, environmental\n      public health tracking, and chronic disease indicators. Supports\n      SoQL filtering, aggregation, pagination, and authenticated app tokens\n      for higher rate limits.\n  - aid: centers-for-disease-control-and-prevention:cdc-wonder-api\n    name: CDC WONDER API\n    tags:\n      - Cancer\n      - Mortality\n      - Natality\n      - Query Database\n      - Statistics\n    humanURL: https://wonder.cdc.gov/\n    baseURL: https://wonder.cdc.gov/controller/datarequest/\n    properties:\n      - url: https://wonder.cdc.gov/\n        type: Website\n      - url:\
  \ https://wonder.cdc.gov/wonder/help/WONDER-API.html\n        type: Documentation\n      - url: https://wonder.cdc.gov/wonder/help/faq.html\n        type: FAQ\n    description: >-\n      CDC WONDER (Wide-ranging ONline Data for Epidemiologic Research) is a\n      suite of public-use ad-hoc query databases covering underlying and\n      multiple cause of death, natality, cancer statistics, tuberculosis,\n      STDs, vaccine adverse events, and environmental health indicators.\n      WONDER exposes an XML-based HTTP API that accepts parameter documents\n      and returns aggregate statistics suitable for epidemiologic research.\n  - aid: centers-for-disease-control-and-prevention:cdc-places-api\n    name: CDC PLACES / 500 Cities API\n    tags:\n      - BRFSS\n      - Census Tract\n      - Chronic Disease\n      - Health Indicators\n      - Small Area Estimation\n    humanURL: https://www.cdc.gov/places/\n    baseURL: https://chronicdata.cdc.gov/resource/\n    properties:\n      - url: https://www.cdc.gov/places/\n\
  \        type: Website\n      - url: https://www.cdc.gov/places/methodology/\n        type: Methodology\n      - url: https://chronicdata.cdc.gov/\n        type: OpenData\n    description: >-\n      PLACES (Population Level Analysis and Community Estimates) provides\n      model-based small-area estimates for chronic disease risk factors,\n      health outcomes, and prevention practices for counties, ZCTAs, census\n      tracts, and places across the United States. Data is available via\n      the Socrata chronicdata.cdc.gov portal as JSON, CSV, and GeoJSON\n      endpoints.\n  - aid: centers-for-disease-control-and-prevention:cdc-ephtn-api\n    name: CDC Environmental Public Health Tracking Network API\n    tags:\n      - Air Quality\n      - Environmental Health\n      - Exposure\n      - GIS\n      - Water Quality\n    humanURL: https://ephtracking.cdc.gov/apihelp\n    baseURL: https://ephtracking.cdc.gov:443/apigateway/api/v1\n    properties:\n      - url: https://ephtracking.cdc.gov/\n\
  \        type: Website\n      - url: https://ephtracking.cdc.gov/apihelp\n        type: Documentation\n      - url: https://ephtracking.cdc.gov/DataExplorer/\n        type: Explorer\n    description: >-\n      The Environmental Public Health Tracking Network API provides a REST\n      interface over the National Tracking Network's JSON-formatted data\n      for air quality, water quality, climate and health, childhood lead\n      poisoning, asthma, cancer, and other environmental health indicators\n      at national, state, and county levels.\n  - aid: centers-for-disease-control-and-prevention:cdc-content-syndication\n    name: CDC Public Health Media Library (Content Syndication)\n    tags:\n      - Content Syndication\n      - Health Content\n      - Media\n      - Multimedia\n    humanURL: https://tools.cdc.gov/medialibrary/\n    properties:\n      - url: https://tools.cdc.gov/medialibrary/\n        type: Website\n      - url: https://tools.cdc.gov/api/v2/resources/media\n        type:\
  \ Reference\n      - url: https://tools.cdc.gov/api/docs/info.aspx\n        type: Documentation\n    description: >-\n      The CDC Public Health Media Library Content Syndication API lets\n      developers and partner sites programmatically retrieve CDC health\n      content (articles, infographics, videos, widgets, images, and\n      microsites) in multiple formats to embed on third-party properties\n      with automatic update propagation.\n  - aid: centers-for-disease-control-and-prevention:open-cdc-apis-index\n    name: CDC Open Technology API Index\n    tags:\n      - Developer Portal\n      - Directory\n      - Open Technology\n    humanURL: https://open.cdc.gov/apis.html\n    properties:\n      - url: https://open.cdc.gov/apis.html\n        type: Website\n      - url: https://open.cdc.gov/\n        type: Portal\n      - url: https://github.com/CDCgov\n        type: GitHubOrganization\n    description: >-\n      open.cdc.gov is CDC's Open Technology landing site that indexes the\n\
  \      agency's public APIs, open-source GitHub repositories, and open data\n      assets, serving as a catalog entry point for developers seeking CDC\n      interfaces across programs and centers.\n  - aid: centers-for-disease-control-and-prevention:cdc-tb-nndss-socrata\n    name: CDC NNDSS / MMWR Socrata Data\n    tags:\n      - MMWR\n      - NNDSS\n      - Notifiable Disease\n      - Surveillance\n    humanURL: https://data.cdc.gov/browse?category=NNDSS\n    properties:\n      - url: https://data.cdc.gov/browse?category=NNDSS\n        type: Catalog\n      - url: https://www.cdc.gov/nndss/\n        type: Program\n      - url: https://wonder.cdc.gov/nndss/nndss_table_menus.asp\n        type: Tables\n    description: >-\n      The National Notifiable Diseases Surveillance System (NNDSS) and\n      Morbidity and Mortality Weekly Report (MMWR) tables are published as\n      Socrata datasets on data.cdc.gov, providing weekly and historical\n      case counts for notifiable conditions accessible\
  \ via SoQL and bulk\n      download.\ncommon:\n  - type: Website\n    url: https://www.cdc.gov/\n  - type: OpenData\n    url: https://data.cdc.gov/\n  - type: Portal\n    url: https://open.cdc.gov/\n  - type: APIs\n    url: https://open.cdc.gov/apis.html\n  - type: GitHubOrganization\n    url: https://github.com/CDCgov\n  - type: WONDER\n    url: https://wonder.cdc.gov/\n  - type: Socrata\n    url: https://dev.socrata.com/\n  - type: ContentSyndication\n    url: https://tools.cdc.gov/medialibrary/\n  - type: EPHTN\n    url: https://ephtracking.cdc.gov/\n  - type: Privacy Policy\n    url: https://www.cdc.gov/other/privacy.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/centers-for-disease-control-and-prevention/refs/heads/main/apis.yml
tags:
- CDC
- Environmental Health
- Epidemiology
- Federal Government
- Healthcare
- Open Data
- Public Health
- Socrata
- Surveillance
- WONDER
url: https://raw.githubusercontent.com/api-evangelist/centers-for-disease-control-and-prevention/refs/heads/main/apis.yml
use_cases: []
---
