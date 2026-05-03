---
api_count: 3
api_specs:
- filename: openstreetmap-main-openapi.yml
  format: yaml
  label: OpenStreetMap Main Editing API v0.6
  slug: main-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-main-openapi.yml
- filename: openstreetmap-nominatim-openapi.yml
  format: yaml
  label: OpenStreetMap Nominatim Geocoding API
  slug: nominatim-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-nominatim-openapi.yml
apis:
- description: The OpenStreetMap main API v0.6 provides CRUD operations for map data editing including nodes, ways, relations, changesets, and notes. Requires OAuth 2.0 authentication for write operations. Maximum b
  name: OpenStreetMap Main Editing API v0.6
  slug: main-api
- description: The Overpass API is a read-only database engine for complex geospatial queries against the OSM dataset. Accepts Overpass QL or XML queries and returns results in XML, JSON, GeoJSON, or CSV. Safe usage
  name: OpenStreetMap Overpass API
  slug: overpass-api
- description: Nominatim is the OpenStreetMap geocoding API providing search (forward geocoding), reverse geocoding, and address lookup for OSM objects. Rate limit is 1 request/second for the public instance. Requir
  name: OpenStreetMap Nominatim Geocoding API
  slug: nominatim-api
common:
- title: ''
  type: Website
  url: https://www.openstreetmap.org/
- title: ''
  type: Portal
  url: https://www.openstreetmap.org/
- title: ''
  type: Documentation
  url: https://wiki.openstreetmap.org/wiki/API
- title: ''
  type: Reference
  url: https://wiki.openstreetmap.org/wiki/API_v0.6
- title: ''
  type: RateLimits
  url: https://operations.osmfoundation.org/policies/api/
- title: ''
  type: TermsOfService
  url: https://osmfoundation.org/wiki/Terms_of_Use
- title: ''
  type: PrivacyPolicy
  url: https://osmfoundation.org/wiki/Privacy_Policy
- title: ''
  type: Blog
  url: https://blog.openstreetmap.org/
- title: ''
  type: GitHubOrganization
  url: https://github.com/openstreetmap
- title: ''
  type: License
  url: https://www.openstreetmap.org/copyright
- title: ''
  type: License
  url: https://opendatacommons.org/licenses/odbl/
- title: ''
  type: Documentation
  url: https://wiki.openstreetmap.org/wiki/Main_Page
- title: ''
  type: Forum
  url: https://community.openstreetmap.org/
- title: ''
  type: Support
  url: https://help.openstreetmap.org/
- title: ''
  type: Authentication
  url: https://www.openstreetmap.org/copyright
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-main-openapi.yml
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-nominatim-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-schema/openstreetmap-node-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-ld/openstreetmap-context.jsonld
created: '2026-03-18'
description: 'OpenStreetMap (OSM) is a collaborative project to create a free, editable map of the world. The OSM ecosystem exposes a family of public REST APIs: the main editing API (v0.6) for CRUD operations on map data, the Overpass API for complex read-only geospatial queries, and the Nominatim API for forward and reverse geocoding. Map data is licensed under the Open Database License (ODbL) 1.0 and tile imagery under CC BY-SA 2.0.'
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Openstreetmap Context
  property_count: 13
  slug: openstreetmap-context
layout: provider
modified: '2026-04-28'
name: OpenStreetMap
skills: []
slug: openstreetmap
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: openstreetmap\nname: OpenStreetMap\ndescription: >-\n  OpenStreetMap (OSM) is a collaborative project to create a free, editable\n  map of the world. The OSM ecosystem exposes a family of public REST APIs:\n  the main editing API (v0.6) for CRUD operations on map data, the Overpass\n  API for complex read-only geospatial queries, and the Nominatim API for\n  forward and reverse geocoding. Map data is licensed under the Open\n  Database License (ODbL) 1.0 and tile imagery under CC BY-SA 2.0.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Geospatial\n  - Mapping\n  - Open Data\n  - Geocoding\n  - Editing\ncreated: '2026-03-18'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: openstreetmap:main-api\n    name: OpenStreetMap Main Editing API v0.6\n    description:\
  \ >-\n      The OpenStreetMap main API v0.6 provides CRUD operations for map data\n      editing including nodes, ways, relations, changesets, and notes.\n      Requires OAuth 2.0 authentication for write operations. Maximum\n      bounding box query area is 0.25 square degrees. Returns XML or JSON.\n      Intended for editing, not high-volume read access.\n    humanURL: https://wiki.openstreetmap.org/wiki/API_v0.6\n    baseURL: https://api.openstreetmap.org/api/0.6\n    tags:\n      - Geospatial\n      - Mapping\n      - Open Data\n      - REST\n      - Editing\n    properties:\n      - type: Documentation\n        url: https://wiki.openstreetmap.org/wiki/API_v0.6\n      - type: RateLimits\n        url: https://operations.osmfoundation.org/policies/api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-main-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-schema/openstreetmap-node-schema.json\n\
  \      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-ld/openstreetmap-context.jsonld\n  - aid: openstreetmap:overpass-api\n    name: OpenStreetMap Overpass API\n    description: >-\n      The Overpass API is a read-only database engine for complex geospatial\n      queries against the OSM dataset. Accepts Overpass QL or XML queries\n      and returns results in XML, JSON, GeoJSON, or CSV. Safe usage: under\n      10,000 queries/day and under 1 GB/day. Python SDKs include overpass,\n      overpy, and OSMPythonTools; JavaScript SDKs include query-overpass\n      and overpass-ts.\n    humanURL: https://wiki.openstreetmap.org/wiki/Overpass_API\n    baseURL: https://overpass-api.de/api\n    tags:\n      - Geospatial\n      - Mapping\n      - Open Data\n      - XML\n      - Overpass\n    properties:\n      - type: Documentation\n        url: https://wiki.openstreetmap.org/wiki/Overpass_API\n      - type: Reference\n  \
  \      url: https://dev.overpass-api.de/overpass-doc/en/\n      - type: DeveloperTools\n        url: https://overpass-turbo.eu/\n  - aid: openstreetmap:nominatim-api\n    name: OpenStreetMap Nominatim Geocoding API\n    description: >-\n      Nominatim is the OpenStreetMap geocoding API providing search\n      (forward geocoding), reverse geocoding, and address lookup for OSM\n      objects. Rate limit is 1 request/second for the public instance.\n      Requires valid User-Agent header. Open source under GNU GPL v3;\n      self-hosted deployment available for higher volume needs.\n    humanURL: https://nominatim.org/release-docs/latest/api/Overview/\n    baseURL: https://nominatim.openstreetmap.org\n    tags:\n      - Geospatial\n      - Mapping\n      - Geocoding\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://nominatim.org/release-docs/latest/api/Overview/\n      - type: RateLimits\n        url: https://operations.osmfoundation.org/policies/nominatim/\n\
  \      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-nominatim-openapi.yml\ncommon:\n  - url: https://www.openstreetmap.org/\n    name: OpenStreetMap\n    type: Website\n  - url: https://www.openstreetmap.org/\n    name: OSM Map\n    type: Portal\n  - url: https://wiki.openstreetmap.org/wiki/API\n    name: API Documentation\n    type: Documentation\n  - url: https://wiki.openstreetmap.org/wiki/API_v0.6\n    name: API v0.6 Reference\n    type: Reference\n  - url: https://operations.osmfoundation.org/policies/api/\n    name: API Usage Policy and Rate Limits\n    type: RateLimits\n  - url: https://osmfoundation.org/wiki/Terms_of_Use\n    name: Terms of Use\n    type: TermsOfService\n  - url: https://osmfoundation.org/wiki/Privacy_Policy\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://blog.openstreetmap.org/\n    name: OSM Blog\n    type: Blog\n  - url: https://github.com/openstreetmap\n\
  \    name: GitHub Organization\n    type: GitHubOrganization\n  - url: https://www.openstreetmap.org/copyright\n    name: Copyright and License\n    type: License\n  - url: https://opendatacommons.org/licenses/odbl/\n    name: ODbL 1.0 (Map Data)\n    type: License\n  - url: https://wiki.openstreetmap.org/wiki/Main_Page\n    name: OSM Wiki\n    type: Documentation\n  - url: https://community.openstreetmap.org/\n    name: OSM Community Forum\n    type: Forum\n  - url: https://help.openstreetmap.org/\n    name: Help\n    type: Support\n  - url: https://www.openstreetmap.org/copyright\n    name: OAuth 2.0 Authentication\n    type: Authentication\n  - url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-main-openapi.yml\n    name: OSM Main API OpenAPI\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-nominatim-openapi.yml\n    name: Nominatim OpenAPI\n    type:\
  \ OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-schema/openstreetmap-node-schema.json\n    name: OSM Node JSON Schema\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-ld/openstreetmap-context.jsonld\n    name: OSM JSON-LD Context\n    type: JSONLDContext\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/apis.yml
tags:
- Geospatial
- Mapping
- Open Data
- Geocoding
- Editing
url: https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/apis.yml
use_cases: []
---
