---
api_count: 1
api_specs:
- filename: tmdb-api.json
  format: json
  label: The Movie Database API
  slug: the-movie-database
  spec_type: OpenAPI
  url: https://developer.themoviedb.org/openapi/tmdb-api.json
apis:
- description: The Movie Database (TMDB) API v3 provides comprehensive access to movie, TV show, person, and image data. Discover movies and series by genre, rating, and release date. Search across all content types
  name: The Movie Database API
  slug: the-movie-database
capabilities:
- description: Workflow capability for discovering, searching, and researching movies, TV series, and people using The Movie Database. Supports entertainment recommendation apps, streaming service aggregators, media
  name: Entertainment Discovery
  slug: entertainment-discovery
common:
- title: ''
  type: Website
  url: https://www.themoviedb.org/
- title: ''
  type: Documentation
  url: https://developer.themoviedb.org/docs/getting-started
- title: ''
  type: Sign Up
  url: https://www.themoviedb.org/signup
- title: ''
  type: Login
  url: https://www.themoviedb.org/login
- title: ''
  type: Support
  url: https://www.themoviedb.org/talk/category/5047951f760ee3318900009d
- title: ''
  type: OpenAPI
  url: https://developer.themoviedb.org/openapi/tmdb-api.json
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-movie-database/refs/heads/main/openapi/the-movie-database-openapi.json
- title: ''
  type: Pricing
  url: https://www.themoviedb.org/api-terms-of-use
created: '2025-03-01'
description: Welcome to version 3 of The Movie Database (TMDB) API. This is where you will find the definitive list of currently available methods for our movie, tv, actor and image API.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: The Movie Database Context
  property_count: 33
  slug: the-movie-database-context
layout: provider
modified: '2026-05-03'
name: The Movie Database
rules:
- name: The Movie Database API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 7
  slug: the-movie-database-rules
skills: []
slug: the-movie-database
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: the-movie-database\nname: The Movie Database\ndescription: >-\n  Welcome to version 3 of The Movie Database (TMDB) API. This is where you will\n  find the definitive list of currently available methods for our movie, tv,\n  actor and image API.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Entertainment\n  - Movies\n  - Television\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/the-movie-database/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: the-movie-database:the-movie-database\n    name: The Movie Database API\n    description: >-\n      The Movie Database (TMDB) API v3 provides comprehensive access to movie,\n      TV show, person, and image data. Discover movies and series by genre, rating,\n      and release date. Search across all content types. Retrieve cast and crew credits,\n \
  \     external IDs, keywords, reviews, recommendations, similar titles, trailers, and\n      watch providers. Manage user accounts with ratings, watchlists, and favorites.\n      Supports multiple languages and regions. 148 endpoints covering movies, TV series,\n      seasons, episodes, people, collections, companies, networks, keywords, and more.\n    humanURL: https://developer.themoviedb.org\n    baseURL: https://api.themoviedb.org/3\n    tags:\n      - Entertainment\n      - Movies\n      - People\n      - Television\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://developer.themoviedb.org/docs/getting-started\n      - type: Reference\n        url: https://developer.themoviedb.org/reference/getting-started\n      - type: GettingStarted\n        url: https://developer.themoviedb.org/docs/getting-started\n      - type: Authentication\n        url: https://developer.themoviedb.org/docs/authentication-application\n      - type: OpenAPI\n        url:\
  \ https://developer.themoviedb.org/openapi/tmdb-api.json\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/the-movie-database/refs/heads/main/openapi/the-movie-database-openapi.json\n    features:\n      - Movie Search and Discovery\n      - TV Series Search and Discovery\n      - Person and Actor Profiles\n      - Cast and Crew Credits\n      - Movie and TV Recommendations\n      - Similar Titles\n      - Trending Content\n      - Watch Providers by Region\n      - User Ratings\n      - Watchlists and Favorites\n      - Image and Video Assets\n      - Multi-Language Support\n      - External ID Mapping (IMDb, TVDB, Wikidata)\n      - Content Change Tracking\n      - Genre and Keyword Filtering\n    useCases:\n      - Entertainment Recommendation Apps\n      - Streaming Service Aggregators\n      - Movie and TV Show Trackers\n      - Media Library Management\n      - Content Discovery Platforms\n      - Review and Rating Apps\n      - Watch\
  \ Provider Comparison\n    integrations:\n      - url: https://developer.themoviedb.org/docs/wrappers-and-libraries\n        name: Official Wrappers and Libraries\n        type: SDK\ncommon:\n  - type: Website\n    url: https://www.themoviedb.org/\n  - type: Documentation\n    url: https://developer.themoviedb.org/docs/getting-started\n  - type: Sign Up\n    url: https://www.themoviedb.org/signup\n  - type: Login\n    url: https://www.themoviedb.org/login\n  - type: Support\n    url: https://www.themoviedb.org/talk/category/5047951f760ee3318900009d\n  - type: OpenAPI\n    url: https://developer.themoviedb.org/openapi/tmdb-api.json\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/the-movie-database/refs/heads/main/openapi/the-movie-database-openapi.json\n  - type: Pricing\n    url: https://www.themoviedb.org/api-terms-of-use\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/the-movie-database/refs/heads/main/apis.yml
tags:
- Entertainment
- Movies
- Television
url: https://raw.githubusercontent.com/api-evangelist/the-movie-database/refs/heads/main/apis.yml
use_cases: []
---
