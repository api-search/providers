---
api_count: 3
apis:
- description: The Census Activations REST API (formerly Census Management API) lets teams programmatically manage reverse ETL pipelines, sources, models, destinations, syncs, and sync runs. The API is region-scoped
  name: Census Activations REST API
  slug: census-activations-api
- description: 'Custom Destinations API lets partners declare the type of data a destination can process, the operations allowed on that data, and the loading mechanism so that Activations can orchestrate loads into '
  name: Census Custom Destinations API
  slug: census-custom-destinations-api
- description: Connect Links enable embedded Activations flows for Powered by Fivetran partners, letting end users configure destinations and syncs from within a host application via hosted URLs.
  name: Census Connect Links (Powered by Fivetran)
  slug: census-connect-links-api
common:
- title: ''
  type: Website
  url: https://www.getcensus.com/
- title: ''
  type: Documentation
  url: https://fivetran.com/docs/activations/
- title: ''
  type: Reference
  url: https://fivetran.com/docs/activations/rest-api/api-reference/introduction
- title: ''
  type: GettingStarted
  url: https://docs.getcensus.com/basics/getting-started
- title: ''
  type: Parent Company
  url: https://www.fivetran.com/
- title: ''
  type: GitHub
  url: https://github.com/sutrolabs
created: '2026-03-27'
description: Census is a reverse ETL and data activation platform that syncs data from cloud data warehouses (Snowflake, BigQuery, Databricks, Redshift) into operational SaaS applications. Census was acquired by Fivetran and is now branded as Fivetran Activations, offering a REST API for managing workspaces, datasets, syncs, destinations, and custom destinations, plus embedded Activations (Connect Links) for Powered by Fivetran use cases.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Census
skills: []
slug: census
solutions: []
source_yaml: "aid: census\nurl: https://raw.githubusercontent.com/api-evangelist/census/refs/heads/main/apis.yml\nname: Census\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Connectors\n  - Data Activation\n  - Data Warehouse\n  - Destinations\n  - Fivetran Activations\n  - Reverse ETL\n  - Unified API\ncreated: '2026-03-27'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\ndescription: >-\n  Census is a reverse ETL and data activation platform that syncs data from\n  cloud data warehouses (Snowflake, BigQuery, Databricks, Redshift) into\n  operational SaaS applications. Census was acquired by Fivetran and is now\n  branded as Fivetran Activations, offering a REST API for managing workspaces,\n  datasets, syncs, destinations, and custom destinations, plus embedded\n  Activations (Connect Links) for Powered by Fivetran use cases.\napis:\n  - aid: census:census-activations-api\n    name: Census Activations REST API\n    tags:\n\
  \      - Data Activation\n      - REST\n      - Reverse ETL\n    humanURL: https://fivetran.com/docs/activations/rest-api/api-reference/introduction\n    properties:\n      - url: https://fivetran.com/docs/activations/rest-api/api-reference/introduction\n        type: Documentation\n      - url: https://docs.getcensus.com/\n        type: LegacyDocumentation\n      - url: https://docs.getcensus.com/basics/getting-started\n        type: GettingStarted\n    description: >-\n      The Census Activations REST API (formerly Census Management API) lets\n      teams programmatically manage reverse ETL pipelines, sources, models,\n      destinations, syncs, and sync runs. The API is region-scoped and\n      authenticated with personal access tokens, with organization-level\n      resources (workspaces, users, invitations) and workspace-level\n      resources (datasets, destinations, syncs).\n  - aid: census:census-custom-destinations-api\n    name: Census Custom Destinations API\n    tags:\n  \
  \    - Custom Destinations\n      - Destinations\n      - Integration\n    humanURL: https://fivetran.com/docs/activations/rest-api/custom-destinations/destination-spec\n    properties:\n      - url: https://fivetran.com/docs/activations/rest-api/custom-destinations/destination-spec\n        type: Documentation\n    description: >-\n      Custom Destinations API lets partners declare the type of data a\n      destination can process, the operations allowed on that data, and the\n      loading mechanism so that Activations can orchestrate loads into any\n      custom SaaS or application system.\n  - aid: census:census-connect-links-api\n    name: Census Connect Links (Powered by Fivetran)\n    tags:\n      - Embedded\n      - Connect Links\n      - Powered by Fivetran\n    humanURL: https://fivetran.com/docs/activations/rest-api/activations-in-powered-by-fivetran/features/connect-links/connect-links\n    properties:\n      - url: https://fivetran.com/docs/activations/rest-api/activations-in-powered-by-fivetran/features/connect-links/connect-links\n\
  \        type: Documentation\n      - url: https://fivetran.com/docs/activations/rest-api/embedded\n        type: Overview\n    description: >-\n      Connect Links enable embedded Activations flows for Powered by Fivetran\n      partners, letting end users configure destinations and syncs from within\n      a host application via hosted URLs.\ncommon:\n  - type: Website\n    url: https://www.getcensus.com/\n  - type: Documentation\n    url: https://fivetran.com/docs/activations/\n  - type: Reference\n    url: https://fivetran.com/docs/activations/rest-api/api-reference/introduction\n  - type: GettingStarted\n    url: https://docs.getcensus.com/basics/getting-started\n  - type: Parent Company\n    url: https://www.fivetran.com/\n  - type: GitHub\n    url: https://github.com/sutrolabs\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/census/refs/heads/main/apis.yml
tags:
- Connectors
- Data Activation
- Data Warehouse
- Destinations
- Fivetran Activations
- Reverse ETL
- Unified API
url: https://raw.githubusercontent.com/api-evangelist/census/refs/heads/main/apis.yml
use_cases: []
---
