---
api_count: 1
apis:
- description: 'These examples use the search API to search the PLOS corpus of scientific articles. These examples are not intended to be a full explanation on the use of Solr. A full Solr query language explanation '
  name: PLOS Search API
  slug: plos
common:
- title: ''
  type: Website
  url: https://plos.org
- title: ''
  type: Documentation
  url: https://api.plos.org/solr/examples/
created: '2025-02-06'
description: These examples use the search API to search the PLOS corpus of scientific articles. These examples are not intended to be a full explanation on the use of Solr. A full Solr query language explanation can be found here and a tutorial here. The construction of PLOS search queries deviates from the standard Solr query URL by using search instead of select when making request to the end point. The primary endpoint is http://api.plos.org/search and supports parameters such as q, fl, wt, start, and rows for querying the PLOS Solr index.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: PLOS
skills: []
slug: plos
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: plos\nname: PLOS\ndescription: >-\n  These examples use the search API to search the PLOS corpus of scientific articles.\n  These examples are not intended to be a full explanation on the use of Solr. A full\n  Solr query language explanation can be found here and a tutorial here. The construction\n  of PLOS search queries deviates from the standard Solr query URL by using search\n  instead of select when making request to the end point. The primary endpoint is\n  http://api.plos.org/search and supports parameters such as q, fl, wt, start, and\n  rows for querying the PLOS Solr index.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Scientific Articles\n  - Research\n  - Search\n  - Solr\n  - Open Access\ncreated: '2025-02-06'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/plos/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n \
  \ - aid: plos:plos\n    name: PLOS Search API\n    description: >-\n      These examples use the search API to search the PLOS corpus of scientific articles.\n      These examples are not intended to be a full explanation on the use of Solr.\n      A full Solr query language explanation can be found here and a tutorial here.\n      The construction of PLOS search queries deviates from the standard Solr query\n      URL by using search instead of select when making request to the end point.\n    humanURL: https://api.plos.org/solr/examples/\n    baseURL: http://api.plos.org/search\n    tags:\n      - Scientific Articles\n      - Search\n      - Solr\n    properties:\n      - type: Documentation\n        url: https://api.plos.org/solr/examples/\n      - type: SearchFields\n        url: https://api.plos.org/solr/search-fields/\ncommon:\n  - type: Website\n    url: https://plos.org\n  - type: Documentation\n    url: https://api.plos.org/solr/examples/\nmaintainers:\n  - FN: Kin Lane\n    email:\
  \ kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/plos/refs/heads/main/apis.yml
tags:
- Scientific Articles
- Research
- Search
- Solr
- Open Access
url: https://raw.githubusercontent.com/api-evangelist/plos/refs/heads/main/apis.yml
use_cases: []
---
