---
api_count: 3
api_specs:
- filename: census-data-api-openapi.yml
  format: yaml
  label: Census Data API
  slug: census-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-census-bureau/refs/heads/main/openapi/census-data-api-openapi.yml
apis:
- description: The Census Data API provides programmatic access to statistical data from Census Bureau surveys and datasets. Users can query demographic, economic, housing, and social data by geographic level and fi
  name: Census Data API
  slug: census-data-api
- description: The TIGERweb GeoServices REST API provides access to Census Bureau geographic data including boundaries for states, counties, census tracts, block groups, and other geographic entities. Supports stand
  name: TIGERweb GeoServices REST API
  slug: tigerweb-rest-api
- description: The Census Geocoding Services convert addresses to geographic coordinates and census geography identifiers. Supports both single-address lookups and batch geocoding for large address lists.
  name: Census Geocoding Services
  slug: geocoding-api
capabilities:
- description: 'Unified workflow capability for accessing U.S. Census Bureau statistical data for demographic research, economic analysis, geographic enrichment, and population studies. Combines the Census Data API, '
  name: Census Bureau Demographic Research
  slug: demographic-research
common:
- title: ''
  type: Website
  url: https://www.census.gov/
- title: ''
  type: DeveloperPortal
  url: https://www.census.gov/data/developers.html
- title: ''
  type: APIKeySignup
  url: https://api.census.gov/data/key_signup.html
- title: ''
  type: DataExplorer
  url: https://data.census.gov/
- title: ''
  type: GitHub
  url: https://github.com/uscensusbureau
- title: ''
  type: Forum
  url: https://apiforum.uscensusbureau.com/
- title: ''
  type: Newsletter
  url: https://public.govdelivery.com/accounts/USCENSUS/subscriber/new?topic_id=USCENSUS_11933
created: '2024-01-01'
description: The U.S. Census Bureau is the nation's leading provider of quality data about its people and economy. The Census Bureau has been rolling out datasets via APIs, providing programmatic access to demographic, economic, housing, and social statistics. The Census Data API supports queries across datasets including the American Community Survey, Decennial Census, Population Estimates, County Business Patterns, Economic Census, and International Trade, with data available at national, state, county, tract, and block group geographic levels.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: United States Census Bureau Context
  property_count: 21
  slug: united-states-census-bureau-context
layout: provider
modified: '2026-05-03'
name: United States Census Bureau
rules:
- name: United States Census Bureau API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 4
  slug: census-data-api-rules
skills: []
slug: united-states-census-bureau
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: united-states-census-bureau\nname: United States Census Bureau\ndescription: >-\n  The U.S. Census Bureau is the nation's leading provider of quality data about\n  its people and economy. The Census Bureau has been rolling out datasets via APIs,\n  providing programmatic access to demographic, economic, housing, and social\n  statistics. The Census Data API supports queries across datasets including the\n  American Community Survey, Decennial Census, Population Estimates, County\n  Business Patterns, Economic Census, and International Trade, with data available\n  at national, state, county, tract, and block group geographic levels.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/united-states-census-bureau/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Demographics\n  - Federal Government\n  - Open Data\n  -\
  \ Statistics\n  - Economics\n  - Population\napis:\n  - aid: united-states-census-bureau:census-data-api\n    name: Census Data API\n    description: >-\n      The Census Data API provides programmatic access to statistical data from\n      Census Bureau surveys and datasets. Users can query demographic, economic,\n      housing, and social data by geographic level and filter using hundreds of\n      statistical variables. Datasets include the American Community Survey (ACS),\n      Decennial Census, Population Estimates, County Business Patterns, Economic\n      Census, International Trade, and more.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.census.gov/data/developers.html\n    baseURL: https://api.census.gov/data\n    tags:\n      - Demographics\n      - Statistics\n      - Open Data\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://www.census.gov/data/developers.html\n      -\
  \ type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-census-bureau/refs/heads/main/openapi/census-data-api-openapi.yml\n      - type: APIKeySignup\n        url: https://api.census.gov/data/key_signup.html\n      - type: DataSets\n        url: https://www.census.gov/data/developers/data-sets.html\n      - type: DiscoveryTool\n        url: https://www.census.gov/data/developers/updates/new-discovery-tool.html\n      - type: UserGuide\n        url: https://www.census.gov/data/developers/guidance/api-user-guide.html\n      - type: ExampleQueries\n        url: https://www.census.gov/data/developers/guidance/api-user-guide/example-api-queries.html\n\n  - aid: united-states-census-bureau:tigerweb-rest-api\n    name: TIGERweb GeoServices REST API\n    description: >-\n      The TIGERweb GeoServices REST API provides access to Census Bureau\n      geographic data including boundaries for states, counties, census tracts,\n      block groups,\
  \ and other geographic entities. Supports standard ArcGIS REST\n      API queries for geographic features.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://tigerweb.geo.census.gov/tigerwebmain/TIGERweb_main.html\n    baseURL: https://tigerweb.geo.census.gov/arcgis/rest/services\n    tags:\n      - Geography\n      - GIS\n      - Boundaries\n      - Mapping\n    properties:\n      - type: Documentation\n        url: https://tigerweb.geo.census.gov/tigerwebmain/TIGERweb_main.html\n\n  - aid: united-states-census-bureau:geocoding-api\n    name: Census Geocoding Services\n    description: >-\n      The Census Geocoding Services convert addresses to geographic coordinates\n      and census geography identifiers. Supports both single-address lookups and\n      batch geocoding for large address lists.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://geocoding.geo.census.gov/geocoder/\n\
  \    baseURL: https://geocoding.geo.census.gov/geocoder\n    tags:\n      - Geocoding\n      - Geography\n      - Address\n    properties:\n      - type: Documentation\n        url: https://geocoding.geo.census.gov/geocoder/\n      - type: BatchGeocoding\n        url: https://www.census.gov/programs-surveys/geography/technical-documentation/complete-technical-documentation/census-geocoder.html\n\ncommon:\n  - type: Website\n    url: https://www.census.gov/\n  - type: DeveloperPortal\n    url: https://www.census.gov/data/developers.html\n  - type: APIKeySignup\n    url: https://api.census.gov/data/key_signup.html\n  - type: DataExplorer\n    url: https://data.census.gov/\n  - type: GitHub\n    url: https://github.com/uscensusbureau\n  - type: Forum\n    url: https://apiforum.uscensusbureau.com/\n  - type: Newsletter\n    url: https://public.govdelivery.com/accounts/USCENSUS/subscriber/new?topic_id=USCENSUS_11933\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/united-states-census-bureau/refs/heads/main/apis.yml
tags:
- Demographics
- Federal Government
- Open Data
- Statistics
- Economics
- Population
url: https://raw.githubusercontent.com/api-evangelist/united-states-census-bureau/refs/heads/main/apis.yml
use_cases: []
---
