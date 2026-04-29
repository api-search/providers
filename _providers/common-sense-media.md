---
api_count: 1
api_specs:
- filename: common-sense-media-reviews-api-openapi.yml
  format: yaml
  label: Common Sense Media Reviews API
  slug: common-sense-media-reviews-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/common-sense-media/refs/heads/main/openapi/common-sense-media-reviews-api-openapi.yml
apis:
- description: 'JSON REST API exposing Common Sense Media''s reviews and ratings catalog. Each review includes recommended age, age-rating group (littleKids/kids/tweens/teens), star rating, content grid (educational, '
  name: Common Sense Media Reviews API
  slug: common-sense-media-reviews-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.commonsensemedia.org/
- title: ''
  type: DeveloperCenter
  url: https://www.commonsensemedia.org/developers
- title: ''
  type: APIOverview
  url: https://www.commonsensemedia.org/developers/api-overview
- title: ''
  type: APIv3
  url: https://www.commonsensemedia.org/developers/api/v3
- title: ''
  type: SwaggerUI
  url: https://api.commonsense.org/docs/v3/
- title: ''
  type: ImplementationGuide
  url: https://www.commonsensemedia.org/developers/api/implementation
- title: ''
  type: PartnerProgramContact
  url: https://commonsense.my.site.com/membersupport/s/contactsupport
- title: ''
  type: PrivacyPolicy
  url: https://www.commonsensemedia.org/privacy-policy
- title: ''
  type: JSON-LD
  url: json-ld/common-sense-media-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/common-sense-media-review-schema.json
- title: ''
  type: Spectral
  url: rules/common-sense-media-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/common-sense-media-reviews-capabilities.yml
created: '2025-03-01'
description: Common Sense Media is a nonprofit organization providing independent, age-rated reviews and ratings of movies, TV shows, books, video games, apps, podcasts, websites, and YouTube channels. The Common Sense Media Reviews API (v3) exposes this catalog via a partner-keyed REST surface hosted at api.commonsense.org/api/v3, with the partnership granted through Common Sense's Business Partner Program. The API is used by parenting apps, smart-TV guides, education platforms, and family- discovery products to surface age-appropriate guidance and the Common Sense Selection award.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Common Sense Media Context
  property_count: 8
  slug: common-sense-media-context
layout: provider
modified: '2026-04-26'
name: Common Sense Media
rules:
- name: Common Sense Media API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 3
  slug: common-sense-media-rules
skills: []
slug: common-sense-media
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: common-sense-media\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/common-sense-media/refs/heads/main/apis.yml\nname: Common Sense Media\ntags:\n  - Apps\n  - Books\n  - Media\n  - Movies\n  - Non-Profit\n  - Podcasts\n  - Ratings\n  - Reviews\n  - Television\n  - Video Games\n  - YouTube\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nx-type: company\ncreated: '2025-03-01'\nmodified: '2026-04-26'\nposition: Consumer\ndescription: >-\n  Common Sense Media is a nonprofit organization providing independent,\n  age-rated reviews and ratings of movies, TV shows, books, video games,\n  apps, podcasts, websites, and YouTube channels. The Common Sense Media\n  Reviews API (v3) exposes this catalog via a partner-keyed REST surface\n  hosted at api.commonsense.org/api/v3, with the partnership granted\n  through Common Sense's Business Partner Program. The API is used by\n  parenting apps, smart-TV\
  \ guides, education platforms, and family-\n  discovery products to surface age-appropriate guidance and the\n  Common Sense Selection award.\napis:\n  - aid: common-sense-media:common-sense-media-reviews-api\n    name: Common Sense Media Reviews API\n    tags:\n      - Apps\n      - Books\n      - Media\n      - Movies\n      - Ratings\n      - Reviews\n      - Television\n      - Video Games\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.commonsense.org/api/v3\n    humanURL: https://www.commonsensemedia.org/developers\n    properties:\n      - url: https://www.commonsensemedia.org/developers/api-overview\n        type: Documentation\n      - url: https://www.commonsensemedia.org/developers/api/v3\n        type: APIv3Overview\n      - url: https://api.commonsense.org/docs/v3/\n        type: SwaggerUI\n      - url: https://www.commonsensemedia.org/developers/api/implementation\n        type: ImplementationGuide\n      -\
  \ url: openapi/common-sense-media-reviews-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      JSON REST API exposing Common Sense Media's reviews and ratings\n      catalog. Each review includes recommended age, age-rating group\n      (littleKids/kids/tweens/teens), star rating, content grid\n      (educational, message, role-model, diversity, violence, sex,\n      language, consumerism, drugs), parents-need-to-know guidance,\n      talking points, and product metadata. Clients filter by media type,\n      age range, star range, character strengths, topics, genres, and the\n      Common Sense Selection award. Authentication uses a partner-issued\n      x-api-key header. The API is GET-only, HTTPS-only, rate-limited to\n      100 unique requests per minute, and content is refreshed at most\n      hourly.\n    x-features:\n      - x-api-key header authentication\n      - GET-only, HTTPS-only access\n      - Filter by mediaType (app, book, game, movie, podcast, tv, website,\
  \ youtube)\n      - Age-range and star-range deepObject filters\n      - Filter by character strengths, topics, genres\n      - Common Sense Selection award filter (csmAward=true)\n      - Vocabulary lookup endpoint for filterable fields\n      - English and Spanish (en, es) language responses\n      - Rate limited to 100 unique requests per minute\n    x-use-cases:\n      - Embedding age-rated reviews in parenting and family apps\n      - Powering smart-TV guides with content advisories\n      - Driving content discovery in education platforms\n      - Surfacing Common Sense Selection award lists\n      - Filtering streaming or library catalogs by recommended age\ncommon:\n  - type: Website\n    url: https://www.commonsensemedia.org/\n  - type: DeveloperCenter\n    url: https://www.commonsensemedia.org/developers\n  - type: APIOverview\n    url: https://www.commonsensemedia.org/developers/api-overview\n  - type: APIv3\n    url: https://www.commonsensemedia.org/developers/api/v3\n  - type:\
  \ SwaggerUI\n    url: https://api.commonsense.org/docs/v3/\n  - type: ImplementationGuide\n    url: https://www.commonsensemedia.org/developers/api/implementation\n  - type: PartnerProgramContact\n    url: https://commonsense.my.site.com/membersupport/s/contactsupport\n  - type: PrivacyPolicy\n    url: https://www.commonsensemedia.org/privacy-policy\n  - url: json-ld/common-sense-media-context.jsonld\n    type: JSON-LD\n  - url: json-schema/common-sense-media-review-schema.json\n    type: JSONSchema\n  - url: rules/common-sense-media-rules.yml\n    type: Spectral\n  - url: capabilities/common-sense-media-reviews-capabilities.yml\n    type: NaftikoCapabilities\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/common-sense-media/refs/heads/main/apis.yml
tags:
- Apps
- Books
- Media
- Movies
- Non-Profit
- Podcasts
- Ratings
- Reviews
- Television
- Video Games
- YouTube
url: https://raw.githubusercontent.com/api-evangelist/common-sense-media/refs/heads/main/apis.yml
use_cases: []
---
