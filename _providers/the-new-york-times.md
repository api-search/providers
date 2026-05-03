---
api_count: 9
api_specs:
- filename: new-york-times-archive-openapi-original.yml
  format: yaml
  label: The New York Times Archive API
  slug: archive-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-archive-openapi-original.yml
- filename: new-york-times-article-search-openapi-original.yml
  format: yaml
  label: The New York Times Article Search API
  slug: article-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-article-search-openapi-original.yml
- filename: new-york-times-books-openapi-original.yml
  format: yaml
  label: The New York Times Books API
  slug: books-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-books-openapi-original.yml
- filename: new-york-times-most-popular-openapi-original.yml
  format: yaml
  label: The New York Times Most Popular API
  slug: most-popular
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-most-popular-openapi-original.yml
- filename: new-york-times-movie-review-openapi-original.yml
  format: yaml
  label: The New York Times Movie Reviews API
  slug: movie-reviews-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-movie-review-openapi-original.yml
- filename: new-york-times-semantic-openapi-original.yml
  format: yaml
  label: The New York Times Semantic API
  slug: semantic-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-semantic-openapi-original.yml
- filename: new-york-times-times-tags-openapi-original.yml
  format: yaml
  label: The New York Times TimesTags API
  slug: timestags-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-times-tags-openapi-original.yml
- filename: new-york-times-times-newswire-openapi-original.yml
  format: yaml
  label: The New York Times Times Newswire API
  slug: times-newswire-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-times-newswire-openapi-original.yml
- filename: new-york-times-top-stories-openapi-original.yml
  format: yaml
  label: The New York Times Top Stories API
  slug: top-stories
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/openapi/new-york-times-top-stories-openapi-original.yml
apis:
- description: The Archive API returns an array of NYT articles for a given month, going back to 1851. Its response fields are the same as the Article Search API. Use it to build your own local database of NYT artic
  name: The New York Times Archive API
  slug: archive-api
- description: Use the Article Search API to look up articles by keyword. You can refine your search using filters and facets. The API searches NYT articles from September 18, 1851 to today, retrieving headlines, ab
  name: The New York Times Article Search API
  slug: article-search-api
- description: The Books API provides information about book reviews and The New York Times Best Sellers lists. Access current and historical bestseller lists, book details, and NYT critic reviews.
  name: The New York Times Books API
  slug: books-api
- description: The Most Popular API provides services for getting the most popular articles on NYTimes.com based on emails, shares, or views. Retrieve the most emailed, shared, and viewed articles by section and tim
  name: The New York Times Most Popular API
  slug: most-popular
- description: Search for NYT movie reviews by keyword and get lists of NYT Critics' Picks. As an alternative, use the Article Search API with appropriate filter queries to access movie review content.
  name: The New York Times Movie Reviews API
  slug: movie-reviews-api
- description: The Semantic API complements the Articles API. With the Semantic API, you get access to the long list of people, places, organizations and other locations, entities and descriptors that make up the co
  name: The New York Times Semantic API
  slug: semantic-api
- description: 'With the TimesTags API, you can mine the riches of the New York Times tag set. The TimesTags service matches your query to the controlled vocabularies that fuel NYTimes.com metadata. Note this API is '
  name: The New York Times TimesTags API
  slug: timestags-api
- description: With the Times Newswire API, you can get links and metadata for Times articles as soon as they are published on NYTimes.com. The Times Newswire API provides an up-to-the-minute stream of published art
  name: The New York Times Times Newswire API
  slug: times-newswire-api
- description: The Top Stories API returns an array of articles currently on the specified section (arts, business, health, home, etc.) of NYTimes.com. Use the home section to get articles currently on the homepage.
  name: The New York Times Top Stories API
  slug: top-stories
capabilities:
- description: Unified workflow for researching and discovering NYT content. Combines article search, archive access, top stories, and the newswire to support journalists, researchers, and developers building news a
  name: NYT Article Research
  slug: article-research
- description: Workflow for discovering NYT content trends, popular articles, books, movies, and entertainment coverage. Combines the Most Popular API, Books API, and Movie Reviews API to support media analysts, edi
  name: NYT Content Discovery
  slug: content-discovery
- description: 'Workflow for enriching content with NYT semantic metadata and tags. Combines the Semantic API and TimesTags API to support knowledge graph construction, entity resolution, and metadata classification '
  name: NYT Metadata Enrichment
  slug: metadata-enrichment
common:
- title: ''
  type: Portal
  url: https://developer.nytimes.com/
- title: ''
  type: Getting Started
  url: https://developer.nytimes.com/get-started
- title: ''
  type: Signup
  url: https://developer.nytimes.com/accounts/create
- title: ''
  type: Login
  url: https://developer.nytimes.com/accounts/login
- title: ''
  type: TermsOfService
  url: https://developer.nytimes.com/terms
- title: ''
  type: FAQ
  url: https://developer.nytimes.com/faq
- title: ''
  type: GitHub
  url: https://github.com/nytimes
- title: ''
  type: Website
  url: https://nytimes.com
- title: ''
  type: OpenAPI
  url: https://github.com/nytimes/public_api_specs
- title: ''
  type: SDK
  url: https://github.com/nytimes/times_wire
- title: ''
  type: SDK
  url: https://github.com/nytimes/nytcampfin
- title: ''
  type: SpectralRuleset
  url: rules/new-york-times-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/article-research.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/content-discovery.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/metadata-enrichment.yaml
- title: ''
  type: JSONSchema
  url: json-schema/new-york-times-article-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/new-york-times-book-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/the-new-york-times-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/the-new-york-times-vocabulary.yml
created: '2023-10-06T00:00:00.000Z'
description: The New York Times is one of the world's most respected news organizations, providing comprehensive journalism across politics, culture, business, science, health, and the arts since 1851. The NYT Developer Network exposes a suite of RESTful APIs enabling developers to search and access NYT articles, best-seller book lists, movie reviews, semantic metadata, top stories, and popular content. All APIs require an API key obtained from the NYT Developer Portal.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 40
  name: The New York Times Context
  property_count: 2
  slug: the-new-york-times-context
layout: provider
modified: '2026-05-03'
name: The New York Times
rules:
- name: The New York Times API Rules
  rule_count: 12
  severity_counts:
    error: 3
    hint: 2
    info: 0
    warn: 7
  slug: new-york-times-rules
skills: []
slug: the-new-york-times
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: the-new-york-times\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/apis.yml\nname: The New York Times\ndescription: >-\n  The New York Times is one of the world's most respected news organizations,\n  providing comprehensive journalism across politics, culture, business, science,\n  health, and the arts since 1851. The NYT Developer Network exposes a suite of\n  RESTful APIs enabling developers to search and access NYT articles, best-seller\n  book lists, movie reviews, semantic metadata, top stories, and popular content.\n  All APIs require an API key obtained from the NYT Developer Portal.\ntype: Contract\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ntags:\n  - Articles\n  - Books\n  - Movies\n  - News\n  - Media\n  - Publishing\n  - Journalism\ncreated: '2023-10-06T00:00:00.000Z'\nmodified: '2026-05-03'\nposition: Consuming\nspecificationVersion: '0.19'\napis:\n\
  \  - aid: the-new-york-times:archive-api\n    name: The New York Times Archive API\n    description: >-\n      The Archive API returns an array of NYT articles for a given month, going\n      back to 1851. Its response fields are the same as the Article Search API.\n      Use it to build your own local database of NYT article metadata.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.nytimes.com/svc/archive/v1\n    humanURL: https://developer.nytimes.com/docs/archive-product/1/overview\n    tags:\n      - Archive\n      - Articles\n      - Months\n      - Years\n      - History\n    properties:\n      - url: https://developer.nytimes.com/docs/archive-product/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-archive-openapi-original.yml\n        type: OpenAPI\n\n  - aid: the-new-york-times:article-search-api\n    name: The New York Times Article Search API\n    description: >-\n      Use the Article\
  \ Search API to look up articles by keyword. You can refine\n      your search using filters and facets. The API searches NYT articles from\n      September 18, 1851 to today, retrieving headlines, abstracts, lead\n      paragraphs, links to associated multimedia and other article metadata.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.nytimes.com/svc/search/v2\n    humanURL: https://developer.nytimes.com/docs/articlesearch-product/1/overview\n    tags:\n      - Articles\n      - Search\n      - Keywords\n      - Facets\n    properties:\n      - url: https://developer.nytimes.com/docs/articlesearch-product/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-article-search-openapi-original.yml\n        type: OpenAPI\n\n  - aid: the-new-york-times:books-api\n    name: The New York Times Books API\n    description: >-\n      The Books API provides information about book reviews and The New York\n \
  \     Times Best Sellers lists. Access current and historical bestseller lists,\n      book details, and NYT critic reviews.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.nytimes.com/svc/books/v3\n    humanURL: https://developer.nytimes.com/docs/books-product/1/overview\n    tags:\n      - Books\n      - Best Sellers\n      - Reviews\n      - Lists\n    properties:\n      - url: https://developer.nytimes.com/docs/books-product/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-books-openapi-original.yml\n        type: OpenAPI\n\n  - aid: the-new-york-times:most-popular\n    name: The New York Times Most Popular API\n    description: >-\n      The Most Popular API provides services for getting the most popular\n      articles on NYTimes.com based on emails, shares, or views. Retrieve the\n      most emailed, shared, and viewed articles by section and time period.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.nytimes.com/svc/mostpopular/v2\n    humanURL: https://developer.nytimes.com/docs/most-popular-product/1/overview\n    tags:\n      - Articles\n      - Popular\n      - Social Sharing\n      - Trending\n    properties:\n      - url: https://developer.nytimes.com/docs/most-popular-product/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-most-popular-openapi-original.yml\n        type: OpenAPI\n\n  - aid: the-new-york-times:movie-reviews-api\n    name: The New York Times Movie Reviews API\n    description: >-\n      Search for NYT movie reviews by keyword and get lists of NYT Critics'\n      Picks. As an alternative, use the Article Search API with appropriate\n      filter queries to access movie review content.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.nytimes.com/svc/movies/v2\n    humanURL: https://developer.nytimes.com/docs/movie-reviews-api/1/overview\n    tags:\n\
  \      - Movies\n      - Reviews\n      - Critics\n      - Film\n    properties:\n      - url: https://developer.nytimes.com/docs/movie-reviews-api/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-movie-review-openapi-original.yml\n        type: OpenAPI\n\n  - aid: the-new-york-times:semantic-api\n    name: The New York Times Semantic API\n    description: >-\n      The Semantic API complements the Articles API. With the Semantic API, you\n      get access to the long list of people, places, organizations and other\n      locations, entities and descriptors that make up the controlled vocabulary\n      used as metadata by The New York Times.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.nytimes.com/svc/semantic/v2\n    humanURL: https://developer.nytimes.com/docs/semantic-api-product/1/overview\n    tags:\n      - Concepts\n      - Semantics\n      - Metadata\n      - Entities\n      - People\n\
  \      - Organizations\n    properties:\n      - url: https://developer.nytimes.com/docs/semantic-api-product/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-semantic-openapi-original.yml\n        type: OpenAPI\n\n  - aid: the-new-york-times:timestags-api\n    name: The New York Times TimesTags API\n    description: >-\n      With the TimesTags API, you can mine the riches of the New York Times tag\n      set. The TimesTags service matches your query to the controlled vocabularies\n      that fuel NYTimes.com metadata. Note this API is deprecated; equivalent\n      functionality is available through the Semantic API.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.nytimes.com/svc/suggest/v1\n    humanURL: https://developer.nytimes.com/docs/timestags-product/1/overview\n    tags:\n      - Tags\n      - Autocomplete\n      - Metadata\n      - Search\n    properties:\n      - url: https://developer.nytimes.com/docs/timestags-product/1/overview\n\
  \        type: Documentation\n      - url: openapi/new-york-times-times-tags-openapi-original.yml\n        type: OpenAPI\n\n  - aid: the-new-york-times:times-newswire-api\n    name: The New York Times Times Newswire API\n    description: >-\n      With the Times Newswire API, you can get links and metadata for Times\n      articles as soon as they are published on NYTimes.com. The Times Newswire\n      API provides an up-to-the-minute stream of published articles by section\n      and source.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.nytimes.com/svc/news/v3\n    humanURL: https://developer.nytimes.com/docs/timeswire-product/1/overview\n    tags:\n      - News\n      - Wire\n      - Streaming\n      - Articles\n      - Sections\n    properties:\n      - url: https://developer.nytimes.com/docs/timeswire-product/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-times-newswire-openapi-original.yml\n\
  \        type: OpenAPI\n\n  - aid: the-new-york-times:top-stories\n    name: The New York Times Top Stories API\n    description: >-\n      The Top Stories API returns an array of articles currently on the\n      specified section (arts, business, health, home, etc.) of NYTimes.com.\n      Use the home section to get articles currently on the homepage.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.nytimes.com/svc/topstories/v2\n    humanURL: https://developer.nytimes.com/docs/top-stories-product/1/overview\n    tags:\n      - Articles\n      - Top Stories\n      - Sections\n      - News\n    properties:\n      - url: https://developer.nytimes.com/docs/top-stories-product/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-top-stories-openapi-original.yml\n        type: OpenAPI\n\ncommon:\n  - url: https://developer.nytimes.com/\n    type: Portal\n  - url: https://developer.nytimes.com/get-started\n\
  \    type: Getting Started\n  - url: https://developer.nytimes.com/accounts/create\n    type: Signup\n  - url: https://developer.nytimes.com/accounts/login\n    type: Login\n  - url: https://developer.nytimes.com/terms\n    type: TermsOfService\n  - url: https://developer.nytimes.com/faq\n    type: FAQ\n  - url: https://github.com/nytimes\n    type: GitHub\n  - url: https://nytimes.com\n    type: Website\n  - url: https://github.com/nytimes/public_api_specs\n    type: OpenAPI\n  - url: https://github.com/nytimes/times_wire\n    name: Times Wire Ruby Client\n    type: SDK\n  - url: https://github.com/nytimes/nytcampfin\n    name: Campaign Finance Python Client\n    type: SDK\n  - url: rules/new-york-times-rules.yml\n    type: SpectralRuleset\n  - url: capabilities/article-research.yaml\n    type: NaftikoCapability\n  - url: capabilities/content-discovery.yaml\n    type: NaftikoCapability\n  - url: capabilities/metadata-enrichment.yaml\n    type: NaftikoCapability\n  - url: json-schema/new-york-times-article-schema.json\n\
  \    type: JSONSchema\n  - url: json-schema/new-york-times-book-schema.json\n    type: JSONSchema\n  - url: json-ld/the-new-york-times-context.jsonld\n    type: JSONLDContext\n  - url: vocabulary/the-new-york-times-vocabulary.yml\n    type: Vocabulary\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/apis.yml
tags:
- Articles
- Books
- Movies
- News
- Media
- Publishing
- Journalism
url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/apis.yml
use_cases: []
---
