---
api_count: 5
apis:
- description: The Entertainment API ingests and serves metadata for movies, television shows, and games, including identifiers used to retrieve associated videos and images from sibling APIs. Responses are availabl
  name: Fabric Origin Entertainment API
  slug: entertainment-api
- description: The Celebrity API serves metadata about celebrities, including actors, directors, and other entertainment industry figures, with cross references to titles served by the Entertainment API.
  name: Fabric Origin Celebrity API
  slug: celebrity-api
- description: The Video API generates playable links for trailers and other video assets using video identifiers returned from the Entertainment API, allowing customers to embed Fabric Origin video content into the
  name: Fabric Origin Video API
  slug: video-api
- description: The Image API provides access to images hosted on Fabric Origin's servers, including posters, stills, and promotional artwork referenced from the Entertainment and Celebrity APIs. Customers are encour
  name: Fabric Origin Image API
  slug: image-api
- description: The Common Data API exposes reference data used across the Fabric Origin product family, including country codes, image type lookups, and video type lookups required when working with the Entertainmen
  name: Fabric Origin Common Data API
  slug: common-data-api
common:
- title: ''
  type: Website
  url: https://www.fabricdata.com/
- title: ''
  type: Knowledge Base
  url: https://knowledgebase.fabricdata.com/origin
- title: ''
  type: Developer Portal
  url: https://developer.origin.fabricdata.com/portal/login
- title: ''
  type: Documentation
  url: https://knowledgebase.fabricdata.com/origin/apis-all/
created: '2025-03-01'
description: Fabric Origin (formerly IVA) is the entertainment data platform powering content discovery experiences for movies, television, games, and trailers. Fabric Origin offers comprehensive entertainment data solutions including metadata, images, trailers, TV listings, and celebrity information through a family of REST APIs. With 30 percent more coverage than other providers and tailored products for every stage of the release cycle, Fabric Origin is an affordable, scalable solution trusted by startups and Fortune 50 companies alike.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Fabric Origin
skills: []
slug: fabric-origin
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fabric-origin\nname: Fabric Origin\ndescription: >-\n  Fabric Origin (formerly IVA) is the entertainment data platform powering\n  content discovery experiences for movies, television, games, and trailers.\n  Fabric Origin offers comprehensive entertainment data solutions including\n  metadata, images, trailers, TV listings, and celebrity information through\n  a family of REST APIs. With 30 percent more coverage than other providers\n  and tailored products for every stage of the release cycle, Fabric Origin\n  is an affordable, scalable solution trusted by startups and Fortune 50\n  companies alike.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/fabric-origin/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\nposition: Consumer\naccess: 3rd-Party\ntags:\n  - Entertainment\n  - Movies\n  - Television\n  - Games\n\
  \  - Trailers\n  - Metadata\napis:\n  - aid: fabric-origin:entertainment-api\n    name: Fabric Origin Entertainment API\n    description: >-\n      The Entertainment API ingests and serves metadata for movies, television\n      shows, and games, including identifiers used to retrieve associated\n      videos and images from sibling APIs. Responses are available in JSON,\n      XML, CSV, and HTML formats via Accept headers or the format query\n      parameter.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://knowledgebase.fabricdata.com/origin/apis-all/\n    baseURL: https://ee.iva-api.com/api/\n    tags:\n      - Entertainment\n      - Metadata\n      - Movies\n      - Television\n      - Games\n    properties:\n      - type: Documentation\n        url: https://knowledgebase.fabricdata.com/origin/apis-all/\n      - type: Knowledge Base\n        url: https://knowledgebase.fabricdata.com/origin\n  - aid: fabric-origin:celebrity-api\n\
  \    name: Fabric Origin Celebrity API\n    description: >-\n      The Celebrity API serves metadata about celebrities, including actors,\n      directors, and other entertainment industry figures, with cross\n      references to titles served by the Entertainment API.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://knowledgebase.fabricdata.com/origin/apis-all/\n    baseURL: https://ee.iva-api.com/api/\n    tags:\n      - Celebrities\n      - People\n      - Metadata\n    properties:\n      - type: Documentation\n        url: https://knowledgebase.fabricdata.com/origin/apis-all/\n  - aid: fabric-origin:video-api\n    name: Fabric Origin Video API\n    description: >-\n      The Video API generates playable links for trailers and other video\n      assets using video identifiers returned from the Entertainment API,\n      allowing customers to embed Fabric Origin video content into their\n      content discovery experiences.\n\
  \    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://knowledgebase.fabricdata.com/origin/apis-all/\n    baseURL: https://ee.iva-api.com/api/\n    tags:\n      - Video\n      - Trailers\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://knowledgebase.fabricdata.com/origin/apis-all/\n  - aid: fabric-origin:image-api\n    name: Fabric Origin Image API\n    description: >-\n      The Image API provides access to images hosted on Fabric Origin's\n      servers, including posters, stills, and promotional artwork referenced\n      from the Entertainment and Celebrity APIs. Customers are encouraged to\n      host and serve images from their own infrastructure for production use.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://knowledgebase.fabricdata.com/origin/apis-all/\n    baseURL: https://ee.iva-api.com/api/\n    tags:\n      - Images\n  \
  \    - Posters\n      - Artwork\n    properties:\n      - type: Documentation\n        url: https://knowledgebase.fabricdata.com/origin/apis-all/\n  - aid: fabric-origin:common-data-api\n    name: Fabric Origin Common Data API\n    description: >-\n      The Common Data API exposes reference data used across the Fabric Origin\n      product family, including country codes, image type lookups, and video\n      type lookups required when working with the Entertainment, Celebrity,\n      Video, and Image APIs.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://knowledgebase.fabricdata.com/origin/apis-all/\n    baseURL: https://ee.iva-api.com/api/\n    tags:\n      - Reference Data\n      - Lookups\n    properties:\n      - type: Documentation\n        url: https://knowledgebase.fabricdata.com/origin/apis-all/\ncommon:\n  - type: Website\n    url: https://www.fabricdata.com/\n  - type: Knowledge Base\n    url: https://knowledgebase.fabricdata.com/origin\n\
  \  - type: Solutions\n    url: https://knowledgebase.fabricdata.com/origin/solutions\n  - type: Developer Portal\n    url: https://developer.origin.fabricdata.com/portal/login\n  - type: Documentation\n    url: https://knowledgebase.fabricdata.com/origin/apis-all/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fabric-origin/refs/heads/main/apis.yml
tags:
- Entertainment
- Movies
- Television
- Games
- Trailers
- Metadata
url: https://raw.githubusercontent.com/api-evangelist/fabric-origin/refs/heads/main/apis.yml
use_cases: []
---
