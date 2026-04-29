---
api_count: 8
apis:
- description: Serves vector tables, SQL-query-backed tilesets, tileset sources, and raster/H3/quadbin tilesets for visualization in deck.gl, MapLibre, Google Maps, Amazon Location, or Mapbox GL clients.
  name: CARTO Maps API
  slug: maps-api
- description: Executes SQL (including CARTO's spatial functions and analytics extensions) against a connected data warehouse from applications, returning GeoJSON / JSON results for spatial analysis, scoring, and da
  name: CARTO SQL API
  slug: sql-api
- description: Executes visually-designed CARTO Workflows (spatial data pipelines) programmatically, enabling scheduled, CI-driven, or application- triggered spatial analytics runs.
  name: CARTO Workflows API
  slug: workflows-api
- description: Ingests files and URLs (CSV, GeoJSON, Shapefile, etc.) into a user's connected CARTO data warehouse for downstream spatial analysis and mapping.
  name: CARTO Import API
  slug: import-api
- description: Curated catalog of third-party spatial datasets (demographics, POIs, mobility, financial, environmental) accessible via subscription and queryable directly from the customer's cloud data warehouse.
  name: CARTO Data Observatory
  slug: data-observatory
- description: Manages CARTO user accounts, organizations, and API access tokens, including OAuth clients used for secure programmatic access.
  name: CARTO Accounts API
  slug: accounts-api
- description: Client library providing deck.gl layers for CARTO vector, H3, quadbin, raster, and query sources, simplifying application-layer integration with the Maps API.
  name: CARTO for deck.gl
  slug: deck-gl
- description: React library of components and hooks for building CARTO-powered location intelligence applications with widgets, filters, and deck.gl map integration.
  name: CARTO for React
  slug: carto-for-react
common:
- title: ''
  type: Website
  url: https://carto.com
- title: ''
  type: Portal
  url: https://docs.carto.com/
- title: ''
  type: Developer
  url: https://docs.carto.com/carto-for-developers
- title: ''
  type: GettingStarted
  url: https://docs.carto.com/getting-started/quickstart-guides
- title: ''
  type: Authentication
  url: https://docs.carto.com/carto-for-developers/fundamentals/authorization
- title: ''
  type: FAQ
  url: https://docs.carto.com/faqs
- title: ''
  type: WhatsNew
  url: https://docs.carto.com/whats-new
- title: ''
  type: Glossary
  url: https://carto.com/glossary
- title: ''
  type: Webinars
  url: https://carto.com/webinars
- title: ''
  type: Blog
  url: https://carto.com/blog
- title: ''
  type: Partners
  url: https://carto.com/partners
- title: ''
  type: Pricing
  url: https://carto.com/pricing
- title: ''
  type: Support
  url: https://docs.carto.com/faqs/support-packages
- title: ''
  type: Status
  url: https://status.carto.com
- title: ''
  type: Login
  url: https://auth.carto.com/u/login
- title: ''
  type: SignUp
  url: https://auth.carto.com/u/signup
- title: ''
  type: TermsOfService
  url: https://carto.com/legal
- title: ''
  type: PrivacyPolicy
  url: https://carto.com/privacy
- title: ''
  type: GitHubOrg
  url: https://github.com/CartoDB
created: '2025-01-08'
description: CARTO is a cloud-native location intelligence platform that lets developers and analysts build spatial applications directly on top of modern data warehouses (BigQuery, Snowflake, Redshift, Databricks). It exposes a Maps API for vector and tileset map data, an SQL API for spatial analytics, a Workflows API for executing no-code spatial pipelines, an Import API for data ingestion, and the Data Observatory for curated third-party spatial datasets — all backed by OAuth access tokens and API access tokens.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Carto Context
  property_count: 9
  slug: carto-context
layout: provider
modified: '2026-04-23'
name: Carto
skills: []
slug: carto
solutions: []
source_yaml: "aid: carto\nname: Carto\ndescription: >-\n  CARTO is a cloud-native location intelligence platform that lets developers\n  and analysts build spatial applications directly on top of modern data\n  warehouses (BigQuery, Snowflake, Redshift, Databricks). It exposes a\n  Maps API for vector and tileset map data, an SQL API for spatial\n  analytics, a Workflows API for executing no-code spatial pipelines, an\n  Import API for data ingestion, and the Data Observatory for curated\n  third-party spatial datasets — all backed by OAuth access tokens and\n  API access tokens.\ntype: Index\nposition: Provider\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Location Intelligence\n  - Geospatial\n  - Mapping\n  - GIS\n  - SQL\n  - BigQuery\n  - Snowflake\n  - Data Warehouse\ncreated: '2025-01-08'\nmodified: '2026-04-23'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/carto/refs/heads/main/apis.yml\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: carto:maps-api\n    name: CARTO Maps API\n    description: >-\n      Serves vector tables, SQL-query-backed tilesets, tileset sources, and\n      raster/H3/quadbin tilesets for visualization in deck.gl, MapLibre,\n      Google Maps, Amazon Location, or Mapbox GL clients.\n    humanURL: https://docs.carto.com/carto-for-developers/reference/maps-api-reference\n    baseURL: https://gcp-us-east1.api.carto.com\n    tags:\n      - Maps\n      - Tiles\n      - Vector\n      - Geospatial\n    properties:\n      - type: Documentation\n        url: https://docs.carto.com/carto-for-developers/reference/maps-api-reference\n  - aid: carto:sql-api\n    name: CARTO SQL API\n    description: >-\n      Executes SQL (including CARTO's spatial functions and analytics\n      extensions) against a connected data warehouse from applications,\n      returning GeoJSON / JSON results for spatial analysis, scoring, and\n      dashboarding.\n    humanURL: https://docs.carto.com/carto-for-developers/reference/sql-api-reference\n\
  \    baseURL: https://gcp-us-east1.api.carto.com\n    tags:\n      - SQL\n      - Analytics\n      - Spatial\n    properties:\n      - type: Documentation\n        url: https://docs.carto.com/carto-for-developers/reference/sql-api-reference\n  - aid: carto:workflows-api\n    name: CARTO Workflows API\n    description: >-\n      Executes visually-designed CARTO Workflows (spatial data pipelines)\n      programmatically, enabling scheduled, CI-driven, or application-\n      triggered spatial analytics runs.\n    humanURL: https://docs.carto.com/carto-for-developers/reference/workflows-api-reference\n    baseURL: https://gcp-us-east1.api.carto.com\n    tags:\n      - Workflows\n      - Analytics\n      - Automation\n    properties:\n      - type: Documentation\n        url: https://docs.carto.com/carto-for-developers/reference/workflows-api-reference\n  - aid: carto:import-api\n    name: CARTO Import API\n    description: >-\n      Ingests files and URLs (CSV, GeoJSON, Shapefile, etc.) into\
  \ a user's\n      connected CARTO data warehouse for downstream spatial analysis and\n      mapping.\n    humanURL: https://docs.carto.com/carto-for-developers/reference/import-api-reference\n    baseURL: https://gcp-us-east1.api.carto.com\n    tags:\n      - Import\n      - Ingestion\n      - Data\n    properties:\n      - type: Documentation\n        url: https://docs.carto.com/carto-for-developers/reference/import-api-reference\n  - aid: carto:data-observatory\n    name: CARTO Data Observatory\n    description: >-\n      Curated catalog of third-party spatial datasets (demographics, POIs,\n      mobility, financial, environmental) accessible via subscription and\n      queryable directly from the customer's cloud data warehouse.\n    humanURL: https://docs.carto.com/data-observatory\n    tags:\n      - Data Catalog\n      - Datasets\n      - Third-Party Data\n    properties:\n      - type: Documentation\n        url: https://docs.carto.com/data-observatory\n  - aid: carto:accounts-api\n\
  \    name: CARTO Accounts API\n    description: >-\n      Manages CARTO user accounts, organizations, and API access tokens,\n      including OAuth clients used for secure programmatic access.\n    humanURL: https://docs.carto.com/carto-for-developers/reference/accounts-api-reference\n    baseURL: https://accounts.app.carto.com\n    tags:\n      - Accounts\n      - Authentication\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://docs.carto.com/carto-for-developers/reference/accounts-api-reference\n  - aid: carto:deck-gl\n    name: CARTO for deck.gl\n    description: >-\n      Client library providing deck.gl layers for CARTO vector, H3, quadbin,\n      raster, and query sources, simplifying application-layer integration\n      with the Maps API.\n    humanURL: https://docs.carto.com/carto-for-developers/carto-for-deck.gl\n    tags:\n      - SDK\n      - deck.gl\n      - Client Library\n    properties:\n      - type: Documentation\n        url: https://docs.carto.com/carto-for-developers/carto-for-deck.gl\n\
  \      - type: Repository\n        url: https://github.com/CartoDB/deck.gl\n  - aid: carto:carto-for-react\n    name: CARTO for React\n    description: >-\n      React library of components and hooks for building CARTO-powered\n      location intelligence applications with widgets, filters, and\n      deck.gl map integration.\n    humanURL: https://docs.carto.com/carto-for-developers/carto-for-react\n    tags:\n      - SDK\n      - React\n      - Client Library\n    properties:\n      - type: Documentation\n        url: https://docs.carto.com/carto-for-developers/carto-for-react\ncommon:\n  - type: Website\n    url: https://carto.com\n  - type: Portal\n    name: CARTO Documentation\n    url: https://docs.carto.com/\n  - type: Developer\n    name: CARTO for Developers\n    url: https://docs.carto.com/carto-for-developers\n  - type: GettingStarted\n    url: https://docs.carto.com/getting-started/quickstart-guides\n  - type: Authentication\n    url: https://docs.carto.com/carto-for-developers/fundamentals/authorization\n\
  \  - type: FAQ\n    url: https://docs.carto.com/faqs\n  - type: WhatsNew\n    url: https://docs.carto.com/whats-new\n  - type: Glossary\n    url: https://carto.com/glossary\n  - type: Webinars\n    url: https://carto.com/webinars\n  - type: Blog\n    url: https://carto.com/blog\n  - type: Partners\n    url: https://carto.com/partners\n  - type: Pricing\n    url: https://carto.com/pricing\n  - type: Support\n    url: https://docs.carto.com/faqs/support-packages\n  - type: Status\n    url: https://status.carto.com\n  - type: Login\n    url: https://auth.carto.com/u/login\n  - type: SignUp\n    url: https://auth.carto.com/u/signup\n  - type: TermsOfService\n    url: https://carto.com/legal\n  - type: PrivacyPolicy\n    url: https://carto.com/privacy\n  - type: GitHubOrg\n    url: https://github.com/CartoDB\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/carto/refs/heads/main/apis.yml
tags:
- Location Intelligence
- Geospatial
- Mapping
- GIS
- SQL
- BigQuery
- Snowflake
- Data Warehouse
url: https://raw.githubusercontent.com/api-evangelist/carto/refs/heads/main/apis.yml
use_cases: []
---
