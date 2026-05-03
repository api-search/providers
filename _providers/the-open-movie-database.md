---
api_count: 1
api_specs:
- filename: the-open-movie-database-openapi.yml
  format: yaml
  label: The Open Movie Database API
  slug: the-open-movie-database
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-open-movie-database/refs/heads/main/openapi/the-open-movie-database-openapi.yml
apis:
- description: The OMDb API is a RESTful web service to obtain movie, series, and episode information. Search by title or look up by IMDb ID. Returns detailed metadata including ratings from IMDb, Rotten Tomatoes, a
  name: The Open Movie Database API
  slug: the-open-movie-database
capabilities:
- description: ''
  name: Movie Lookup
  slug: movie-lookup
common:
- title: ''
  type: Website
  url: https://www.omdbapi.com/
- title: ''
  type: Documentation
  url: https://www.omdbapi.com/
- title: ''
  type: Sign Up
  url: https://www.omdbapi.com/apikey.aspx
- title: ''
  type: Terms of Service
  url: https://www.omdbapi.com/legal.htm
created: '2025-03-01'
description: The OMDb API is a RESTful web service to obtain movie, series, and episode information. All content and images on the site are contributed and maintained by users. Access movie and TV metadata including title, year, genre, director, cast, plot, ratings, and IMDb data. Search by title or look up by IMDb ID. Requires a free API key obtained at omdbapi.com/apikey.aspx.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 30
  name: The Open Movie Database Context
  property_count: 7
  slug: the-open-movie-database-context
layout: provider
modified: '2026-05-03'
name: The Open Movie Database
rules:
- name: The Open Movie Database API Rules
  rule_count: 9
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 3
  slug: the-open-movie-database-rules
skills: []
slug: the-open-movie-database
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: the-open-movie-database\nname: The Open Movie Database\ndescription: >-\n  The OMDb API is a RESTful web service to obtain movie, series, and episode\n  information. All content and images on the site are contributed and maintained\n  by users. Access movie and TV metadata including title, year, genre, director,\n  cast, plot, ratings, and IMDb data. Search by title or look up by IMDb ID.\n  Requires a free API key obtained at omdbapi.com/apikey.aspx.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Entertainment\n  - Movies\n  - Television\n  - IMDb\n  - Metadata\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/the-open-movie-database/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: the-open-movie-database:the-open-movie-database\n    name: The Open Movie Database API\n    description: >-\n \
  \     The OMDb API is a RESTful web service to obtain movie, series, and episode\n      information. Search by title or look up by IMDb ID. Returns detailed\n      metadata including ratings from IMDb, Rotten Tomatoes, and Metacritic.\n    humanURL: https://www.omdbapi.com/\n    baseURL: https://www.omdbapi.com\n    tags:\n      - Entertainment\n      - Movies\n      - Television\n      - IMDb\n      - Metadata\n    properties:\n      - type: Documentation\n        url: https://www.omdbapi.com/\n      - type: OpenAPI\n        url: openapi/the-open-movie-database-openapi.yml\n      - type: Sign Up\n        url: https://www.omdbapi.com/apikey.aspx\n      - type: Spectral Rules\n        url: rules/the-open-movie-database-rules.yml\n      - type: Naftiko Capability\n        url: capabilities/movie-lookup.yaml\n      - type: Naftiko Shared\n        url: capabilities/shared/the-open-movie-database.yaml\n      - type: JSON Schema\n        url: json-schema/the-open-movie-database-movie-schema.json\n\
  \      - type: JSON Structure\n        url: json-structure/the-open-movie-database-movie-structure.json\n      - type: JSON-LD\n        url: json-ld/the-open-movie-database-context.jsonld\n      - type: Example\n        url: examples/the-open-movie-database-get-movie-example.json\n      - type: Vocabulary\n        url: vocabulary/the-open-movie-database-vocabulary.yml\ncommon:\n  - type: Website\n    url: https://www.omdbapi.com/\n  - type: Documentation\n    url: https://www.omdbapi.com/\n  - type: Sign Up\n    url: https://www.omdbapi.com/apikey.aspx\n  - type: Terms of Service\n    url: https://www.omdbapi.com/legal.htm\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/the-open-movie-database/refs/heads/main/apis.yml
tags:
- Entertainment
- Movies
- Television
- IMDb
- Metadata
url: https://raw.githubusercontent.com/api-evangelist/the-open-movie-database/refs/heads/main/apis.yml
use_cases: []
---
