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
  label: The New York Times Most Popular
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
apis:
- description: The Archive API returns an array of NYT articles for a given month, going back to 1851. Its response fields are the same as the Article Search API.
  name: The New York Times Archive API
  slug: archive-api
- description: Use the Article Search API to look up articles by keyword. You can refine your search using filters and facets.
  name: The New York Times Article Search API
  slug: article-search-api
- description: The Books API provides information about book reviews and The New York Times Best Sellers lists.
  name: The New York Times Books API
  slug: books-api
- description: Provides services for getting the most popular articles on NYTimes.com based on emails, shares, or views.
  name: The New York Times Most Popular
  slug: most-popular
- description: As an alternative, use the Article Search API to get New York Times movie reviews using the following filter query.
  name: The New York Times Movie Reviews API
  slug: movie-reviews-api
- description: The Semantic API complements the Articles API. With the Semantic API, you get access to the long list of people, places, organizations and other locations, entities and descriptors that make up the co
  name: The New York Times Semantic API
  slug: semantic-api
- description: With the TimesTags API, you can mine the riches of the New York Times tag set. The TimesTags service matches your query to the controlled vocabularies that fuel NYTimes.com metadata.
  name: The New York Times TimesTags API
  slug: timestags-api
- description: With the Times Newswire API, you can get links and metadata for Times' articles as soon as they are published on NYTimes.com. The Times Newswire API provides an up-to-the-minute stream of published ar
  name: The New York Times Times Newswire API
  slug: times-newswire-api
- description: The Top Stories API returns an array of articles currently on the specified section (arts, business, ...).
  name: The New York Times Top Stories
  slug: top-stories
common:
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
created: '2023-10-06T00:00:00.000Z'
description: The New York Times is one of the most well-known and respected newspapers in the world. It covers a wide range of topics including news, politics, culture, business, and sports. The Times is known for its in-depth reporting and analysis, providing readers with comprehensive coverage of important issues and events. In addition to its print publication, The New York Times has a robust online presence, offering digital content to a global audience.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-16'
name: The New York Times
skills: []
slug: the-new-york-times
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: the-new-york-times\nurl: >-\n  https://raw.githubusercontent.com/api-search/news/main/_apis/new-york-times/apis.md\napis:\n  - aid: the-new-york-times:archive-api\n    name: The New York Times Archive API\n    tags:\n      - Archive\n      - Months\n      - Years\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.nytimes.com\n    humanURL: https://developer.nytimes.com/docs/archive-product/1/overview\n    properties:\n      - url: https://developer.nytimes.com/docs/archive-product/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-archive-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      The Archive API returns an array of NYT articles for a given month, going back\n      to 1851. Its response fields are the same as the Article Search API.\n  - aid: the-new-york-times:article-search-api\n    name: The New York Times Article Search API\n    tags:\n      - Articles\n\
  \      - Search\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.nytimes.com\n    humanURL: https://developer.nytimes.com/docs/articlesearch-product/1/overview\n    properties:\n      - url: https://developer.nytimes.com/docs/articlesearch-product/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-article-search-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      Use the Article Search API to look up articles by keyword. You can refine\n      your search using filters and facets.\n  - aid: the-new-york-times:books-api\n    name: The New York Times Books API\n    tags: []\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.nytimes.com/docs/books-product/1/overview\n    properties:\n      - url: https://developer.nytimes.com/docs/books-product/1/overview\n        type: Documentation\n\
  \      - url: openapi/new-york-times-books-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      The Books API provides information about book reviews and The New York\n      Times Best Sellers lists.\n  - aid: the-new-york-times:most-popular\n    name: The New York Times Most Popular\n    tags: []\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.nytimes.com\n    humanURL: https://developer.nytimes.com/docs/most-popular-product/1/overview\n    properties:\n      - url: https://developer.nytimes.com/docs/most-popular-product/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-most-popular-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      Provides services for getting the most popular articles on NYTimes.com\n      based on emails, shares, or views.\n  - aid: the-new-york-times:movie-reviews-api\n    name: The New York Times Movie Reviews API\n    tags:\n     \
  \ - Bio\n      - Critics\n      - Images\n      - Movie\n      - Names\n      - Reviewers\n      - Reviews\n      - Search\n      - Types\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: >-\n      https://api.apis.guru/v2/specs/nytimes.com/movie_reviews/2.0.0/openapi.yaml\n    humanURL: https://developer.nytimes.com/docs/movie-reviews-api/1/overview\n    properties:\n      - url: https://example.com/documentation\n        type: Documentation\n      - url: openapi/new-york-times-movie-review-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      As an alternative, use the Article Search API to get New York Times movie\n      reviews using the following filter query.\n  - aid: the-new-york-times:semantic-api\n    name: The New York Times Semantic API\n    tags:\n      - Concepts\n      - Names\n      - Search\n      - Specific\n      - Types\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.example.com\n    humanURL: https://developer.nytimes.com/docs/semantic-api-product/1/overview\n    properties:\n      - url: https://developer.nytimes.com/docs/semantic-api-product/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-semantic-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      The Semantic API complements the Articles API. With the Semantic API, you\n      get access to the long list of people, places, organizations and other\n      locations, entities and descriptors that make up the controlled vocabulary\n      used as metadata by The New York Times.\n  - aid: the-new-york-times:timestags-api\n    name: The New York Times TimesTags API\n    tags: []\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.nytimes.com/docs/timestags-product/1/overview\n    properties:\n      - url: https://developer.nytimes.com/docs/timestags-product/1/overview\n\
  \        type: Documentation\n      - url: openapi/new-york-times-times-tags-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      With the TimesTags API, you can mine the riches of the New York Times tag set.\n      The TimesTags service matches your query to the controlled vocabularies that\n      fuel NYTimes.com metadata.\n  - aid: the-new-york-times:times-newswire-api\n    name: The New York Times Times Newswire API\n    tags:\n      - Content\n      - Sections\n      - Sources\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.nytimes.com/docs/timeswire-product/1/overview\n    properties:\n      - url: https://developer.nytimes.com/docs/timeswire-product/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-times-newswire-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      With the Times Newswire API, you can get links\
  \ and metadata for Times' articles\n      as soon as they are published on NYTimes.com. The Times Newswire API provides\n      an up-to-the-minute stream of published articles.\n  - aid: the-new-york-times:top-stories\n    name: The New York Times Top Stories\n    tags: []\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.nytimes.com/docs/top-stories-product/1/overview\n    properties:\n      - url: https://developer.nytimes.com/docs/top-stories-product/1/overview\n        type: Documentation\n      - url: openapi/new-york-times-top-stories-openapi-original.ymll\n        type: OpenAPI\n    description: >-\n      The Top Stories API returns an array of articles currently on the\n      specified section (arts, business, ...).\nname: The New York Times\ntags:\n  - Articles\n  - Books\n  - Movies\n  - News\ntype: Contract\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  access: 3rd-Party\ncommon:\n  - url: https://developer.nytimes.com/get-started\n    type: Getting Started\n  - url: https://developer.nytimes.com/accounts/create\n    type: Signup\n  - url: https://developer.nytimes.com/accounts/login\n    type: Login\n  - url: https://developer.nytimes.com/terms\n    type: TermsOfService\ncreated: '2023-10-06T00:00:00.000Z'\nmodified: '2026-03-16'\nposition: Consuming\ndescription: >-\n  The New York Times is one of the most well-known and respected newspapers in the\n  world. It covers a wide range of topics including news, politics, culture, business,\n  and sports. The Times is known for its in-depth reporting and analysis, providing\n  readers with comprehensive coverage of important issues and events. In addition\n  to its print publication, The New York Times has a robust online presence, offering\n  digital content to a global audience.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/the-new-york-times/refs/heads/main/apis.yml
tags:
- Articles
- Books
- Movies
- News
url: https://raw.githubusercontent.com/api-search/news/main/_apis/new-york-times/apis.md
use_cases: []
---
