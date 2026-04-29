---
api_count: 7
apis:
- description: The Coveo Search API is a RESTful interface for issuing queries against the Coveo unified index, retrieving relevance-ranked results with facets, highlights, and personalization context. It supports q
  name: Coveo Search API
  slug: search
- description: 'The Coveo Push API enables programmatic indexing of items into a Coveo Push source, including individual document push, batch push via secure cloud storage, and source state management for partial or '
  name: Coveo Push API
  slug: push
- description: The Coveo Stream API is the modern high-throughput indexing interface used to add and update content in Catalog sources for commerce, replacing batch Push for catalog ingestion.
  name: Coveo Stream API
  slug: stream
- description: The Coveo Commerce API provides endpoints to power product search result pages, product listing pages (PLPs), product recommendations, and product discovery, plus endpoints for managing product invent
  name: Coveo Commerce API
  slug: commerce
- description: The Coveo Usage Analytics (UA) Read and Write APIs record search and click events from end-user search experiences, and expose query and reporting endpoints used by dashboards and Coveo Machine Learni
  name: Coveo Usage Analytics API
  slug: usage-analytics
- description: The Coveo Machine Learning API provides endpoints for managing ML models including Automatic Relevance Tuning (ART), Query Suggestions (QS), Recommendations (PR), and Dynamic Navigation Experience (DN
  name: Coveo Machine Learning API
  slug: machine-learning
- description: The Coveo Platform API provides administrative endpoints for managing organizations, sources, security identities, query pipelines, fields, tokens, and configuration of the Coveo Platform.
  name: Coveo Platform API
  slug: platform
common:
- title: ''
  type: Website
  url: https://www.coveo.com
- title: ''
  type: Documentation
  url: https://docs.coveo.com/
- title: ''
  type: APIOverview
  url: https://docs.coveo.com/en/143/
- title: ''
  type: DeveloperBlog
  url: https://blog.coveo.com/
- title: ''
  type: GitHub
  url: https://github.com/coveo
- title: ''
  type: TermsOfService
  url: https://www.coveo.com/en/company/legal
- title: ''
  type: PrivacyPolicy
  url: https://www.coveo.com/en/company/legal/privacy-statement
- title: ''
  type: Support
  url: https://connect.coveo.com/s/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/coveo
created: '2025-02-08'
description: Coveo is a cloud-based AI-relevance platform that delivers personalized search, recommendations, and discovery experiences across digital workplaces, customer service portals, websites, and commerce storefronts. The Coveo platform exposes a family of REST APIs covering search, content indexing (Push and Stream), usage analytics, machine learning, commerce, and platform administration.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Coveo
skills: []
slug: coveo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: coveo\nname: Coveo\nx-type: company\ndescription: >-\n  Coveo is a cloud-based AI-relevance platform that delivers personalized search,\n  recommendations, and discovery experiences across digital workplaces, customer\n  service portals, websites, and commerce storefronts. The Coveo platform exposes\n  a family of REST APIs covering search, content indexing (Push and Stream),\n  usage analytics, machine learning, commerce, and platform administration.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/coveo/refs/heads/main/apis.yml\ntype: Index\naccess: 3rd-Party\nposition: Consuming\ncreated: '2025-02-08'\nmodified: '2026-04-28'\ntags:\n  - AI\n  - Analytics\n  - Catalog\n  - Commerce\n  - Customers\n  - Experiences\n  - Machine Learning\n  - Personalization\n  - Recommendations\n  - Search\nspecificationVersion: '0.19'\napis:\n  - aid: coveo:search\n    name: Coveo Search API\n   \
  \ description: >-\n      The Coveo Search API is a RESTful interface for issuing queries against\n      the Coveo unified index, retrieving relevance-ranked results with facets,\n      highlights, and personalization context. It supports query pipelines,\n      authentication tokens, and analytics correlation.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.coveo.com/en/52/\n    baseURL: https://platform.cloud.coveo.com/rest/search/v2\n    tags:\n      - Facets\n      - Query Pipelines\n      - REST\n      - Search\n    properties:\n      - type: Documentation\n        url: https://docs.coveo.com/en/52/\n      - type: APIReference\n        url: https://docs.coveo.com/en/13/api-reference/search-api\n      - type: BuildSearchUI\n        url: https://docs.coveo.com/en/1370/\n    features:\n      - name: Query Pipelines\n        description: Server-side query rewriting, ranking, and conditional rules.\n      - name: Personalization\n\
  \        description: Per-user relevance based on profile and activity context.\n      - name: Search Tokens\n        description: Short-lived JWT search tokens for secure end-user querying.\n  - aid: coveo:push\n    name: Coveo Push API\n    description: >-\n      The Coveo Push API enables programmatic indexing of items into a Coveo\n      Push source, including individual document push, batch push via secure\n      cloud storage, and source state management for partial or full indexing\n      operations.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.coveo.com/en/1546/\n    baseURL: https://api.cloud.coveo.com/push/v1\n    tags:\n      - Indexing\n      - Push\n      - REST\n      - Sources\n    properties:\n      - type: Documentation\n        url: https://docs.coveo.com/en/1546/\n      - type: PushSourceManagement\n        url: https://docs.coveo.com/en/68/\n  - aid: coveo:stream\n    name: Coveo Stream API\n    description:\
  \ >-\n      The Coveo Stream API is the modern high-throughput indexing interface used\n      to add and update content in Catalog sources for commerce, replacing batch\n      Push for catalog ingestion.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.coveo.com/en/lb4a0344/\n    baseURL: https://api.cloud.coveo.com/push/v1\n    tags:\n      - Catalog\n      - Commerce\n      - Indexing\n      - Stream\n    properties:\n      - type: Documentation\n        url: https://docs.coveo.com/en/lb4a0344/\n      - type: PushAndUpdateCatalog\n        url: https://docs.coveo.com/en/p5je0317/\n  - aid: coveo:commerce\n    name: Coveo Commerce API\n    description: >-\n      The Coveo Commerce API provides endpoints to power product search result\n      pages, product listing pages (PLPs), product recommendations, and product\n      discovery, plus endpoints for managing product inventories.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://docs.coveo.com/en/p5je0317/\n    baseURL: https://platform.cloud.coveo.com/rest/organizations\n    tags:\n      - Commerce\n      - PLP\n      - Product Listings\n      - Recommendations\n      - Search\n    properties:\n      - type: Documentation\n        url: https://docs.coveo.com/en/p5je0317/\n      - type: CommerceSetup\n        url: https://docs.coveo.com/en/o25a0034/\n  - aid: coveo:usage-analytics\n    name: Coveo Usage Analytics API\n    description: >-\n      The Coveo Usage Analytics (UA) Read and Write APIs record search and\n      click events from end-user search experiences, and expose query and\n      reporting endpoints used by dashboards and Coveo Machine Learning models.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.coveo.com/en/365/\n    baseURL: https://analytics.cloud.coveo.com/rest/ua/v15\n    tags:\n      - Analytics\n      - Events\n      - REST\n      - Reporting\n   \
  \ properties:\n      - type: Documentation\n        url: https://docs.coveo.com/en/365/\n      - type: TrackUsageAnalytics\n        url: https://docs.coveo.com/en/ncd90215/\n  - aid: coveo:machine-learning\n    name: Coveo Machine Learning API\n    description: >-\n      The Coveo Machine Learning API provides endpoints for managing ML models\n      including Automatic Relevance Tuning (ART), Query Suggestions (QS),\n      Recommendations (PR), and Dynamic Navigation Experience (DNE) models.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.coveo.com/en/1727/\n    baseURL: https://platform.cloud.coveo.com/rest/organizations\n    tags:\n      - AI\n      - Machine Learning\n      - Recommendations\n      - Relevance\n    properties:\n      - type: Documentation\n        url: https://docs.coveo.com/en/1727/\n  - aid: coveo:platform\n    name: Coveo Platform API\n    description: >-\n      The Coveo Platform API provides administrative\
  \ endpoints for managing\n      organizations, sources, security identities, query pipelines, fields,\n      tokens, and configuration of the Coveo Platform.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.coveo.com/en/124/\n    baseURL: https://platform.cloud.coveo.com/rest\n    tags:\n      - Administration\n      - Organizations\n      - Pipelines\n      - Sources\n      - Tokens\n    properties:\n      - type: Documentation\n        url: https://docs.coveo.com/en/124/\n      - type: APIOverview\n        url: https://docs.coveo.com/en/143/\ncommon:\n  - type: Website\n    url: https://www.coveo.com\n  - type: Documentation\n    url: https://docs.coveo.com/\n  - type: APIOverview\n    url: https://docs.coveo.com/en/143/\n  - type: DeveloperBlog\n    url: https://blog.coveo.com/\n  - type: GitHub\n    url: https://github.com/coveo\n  - type: TermsOfService\n    url: https://www.coveo.com/en/company/legal\n  - type: PrivacyPolicy\n\
  \    url: https://www.coveo.com/en/company/legal/privacy-statement\n  - type: Support\n    url: https://connect.coveo.com/s/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/coveo\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/coveo/refs/heads/main/apis.yml
tags:
- AI
- Analytics
- Catalog
- Commerce
- Customers
- Experiences
- Machine Learning
- Personalization
- Recommendations
- Search
url: https://raw.githubusercontent.com/api-evangelist/coveo/refs/heads/main/apis.yml
use_cases: []
---
