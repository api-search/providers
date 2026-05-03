---
api_count: 1
api_specs:
- filename: spaceflight-news-api-openapi.yml
  format: yaml
  label: Spaceflight News API
  slug: spaceflight-news-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spaceflight-news-api/refs/heads/main/openapi/spaceflight-news-api-openapi.yml
apis:
- description: REST API providing access to spaceflight news, blogs, and reports aggregated from over 43 sources. Supports pagination, filtering by news site, and linking articles to Launch Library 2 launches and ev
  name: Spaceflight News API
  slug: spaceflight-news-api
capabilities:
- description: Workflow capability for monitoring and aggregating spaceflight news, blogs, and mission reports. Useful for applications that want to track space industry developments, follow specific launches, or bu
  name: Spaceflight News Monitoring
  slug: space-news-monitoring
common:
- title: ''
  type: Website
  url: https://www.spaceflightnewsapi.net
- title: ''
  type: Documentation
  url: https://api.spaceflightnewsapi.net/v4/docs/
- title: ''
  type: GitHub
  url: https://github.com/thespacedevs/spaceflightnewsapi
- title: ''
  type: Support
  url: https://discord.gg/thespacedevs
created: '2024-11-07'
description: The Spaceflight News API (SNAPI) is a free, open REST API that aggregates space-related news, blogs, and reports from over 43 sources including NASA, SpaceX, Reuters, NASASpaceflight, and Spaceflight Now. It provides paginated access to articles, blogs, and reports with integration to Launch Library 2 for linking news to specific launches and events.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 14
  name: Spaceflight News Api Context
  property_count: 11
  slug: spaceflight-news-api-context
layout: provider
modified: '2026-05-02'
name: Spaceflight News API
rules:
- name: Spaceflight News API API Rules
  rule_count: 9
  severity_counts:
    error: 1
    hint: 0
    info: 3
    warn: 5
  slug: spaceflight-news-api-rules
skills: []
slug: spaceflight-news-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spaceflight-news-api\nurl: https://raw.githubusercontent.com/api-evangelist/spaceflight-news-api/refs/heads/main/apis.yml\nname: Spaceflight News API\ndescription: >-\n  The Spaceflight News API (SNAPI) is a free, open REST API that aggregates space-related\n  news, blogs, and reports from over 43 sources including NASA, SpaceX, Reuters, NASASpaceflight,\n  and Spaceflight Now. It provides paginated access to articles, blogs, and reports with\n  integration to Launch Library 2 for linking news to specific launches and events.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - News\n  - Space\n  - Spaceflight\n  - Media\ncreated: '2024-11-07'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: spaceflight-news-api:spaceflight-news-api\n    name: Spaceflight News API\n    description: >-\n      REST API providing access to spaceflight news, blogs, and reports aggregated from\n      over 43 sources.\
  \ Supports pagination, filtering by news site, and linking articles\n      to Launch Library 2 launches and events. No authentication required.\n    humanURL: https://www.spaceflightnewsapi.net\n    baseURL: https://api.spaceflightnewsapi.net/v4\n    tags:\n      - News\n      - Space\n      - Spaceflight\n      - Media\n    properties:\n      - url: https://www.spaceflightnewsapi.net\n        type: Documentation\n      - url: https://api.spaceflightnewsapi.net/v4/docs/\n        type: SwaggerUI\n      - url: https://github.com/thespacedevs/spaceflightnewsapi\n        type: GitHubRepository\n      - url: https://raw.githubusercontent.com/api-evangelist/spaceflight-news-api/refs/heads/main/openapi/spaceflight-news-api-openapi.yml\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/spaceflight-news-api/refs/heads/main/rules/spaceflight-news-api-rules.yml\n        type: SpectralRules\n      - url: https://raw.githubusercontent.com/api-evangelist/spaceflight-news-api/refs/heads/main/json-schema/spaceflight-news-api-article-schema.json\n\
  \        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/spaceflight-news-api/refs/heads/main/json-structure/spaceflight-news-api-article-structure.json\n        type: JSONStructure\n      - url: https://raw.githubusercontent.com/api-evangelist/spaceflight-news-api/refs/heads/main/json-ld/spaceflight-news-api-context.jsonld\n        type: JSONLDContext\n      - url: https://raw.githubusercontent.com/api-evangelist/spaceflight-news-api/refs/heads/main/vocabulary/spaceflight-news-api-vocabulary.yml\n        type: Vocabulary\ncommon:\n  - type: Website\n    url: https://www.spaceflightnewsapi.net\n  - type: Documentation\n    url: https://api.spaceflightnewsapi.net/v4/docs/\n  - type: GitHub\n    url: https://github.com/thespacedevs/spaceflightnewsapi\n  - type: Support\n    url: https://discord.gg/thespacedevs\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spaceflight-news-api/refs/heads/main/apis.yml
tags:
- News
- Space
- Spaceflight
- Media
url: https://raw.githubusercontent.com/api-evangelist/spaceflight-news-api/refs/heads/main/apis.yml
use_cases: []
---
