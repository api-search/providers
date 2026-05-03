---
api_count: 2
apis:
- description: The Sunset HTTP header field (RFC 8594) communicates the deprecation timeline of API endpoints to consumers. The header value is an HTTP-date timestamp indicating when a URI is expected to become unre
  name: Sunset Header (RFC 8594)
  slug: sunset-header
- description: RFC 9745 defines the Deprecation HTTP response header field, which signals to clients that a resource has been or will be deprecated. It complements the Sunset header by marking the start of the depre
  name: Deprecation HTTP Header Field (RFC 9745)
  slug: deprecation-header
common:
- title: ''
  type: Website
  url: https://datatracker.ietf.org/doc/html/rfc8594
- title: ''
  type: IETF Specification
  url: https://www.rfc-editor.org/rfc/rfc8594
created: '2026-03-29'
description: The Sunset HTTP header field (RFC 8594) is an informational IETF specification that allows servers to communicate to clients that a URI is likely to become unresponsive at a specified future point in time. Published in May 2019, it provides a standardized mechanism for API deprecation signaling, enabling clients to plan migrations before service retirement. The header value is an HTTP-date timestamp following RFC 7231 syntax. A complementary sunset link relation type allows resources to reference documentation covering the sunset policy, migration guidance, and alternatives. RFC 9745 (Deprecation HTTP Header Field) extends this pattern by providing a two-phase deprecation + sunset lifecycle where Deprecation marks the start of deprecation and Sunset marks the end-of-life. These two headers are widely adopted in REST API governance practices and API lifecycle management tooling.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Sunset Header Context
  property_count: 15
  slug: sunset-header-context
layout: provider
modified: '2026-05-02'
name: Sunset Header
skills: []
slug: sunset-header
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sunset-header\nname: Sunset Header\ndescription: >-\n  The Sunset HTTP header field (RFC 8594) is an informational IETF specification\n  that allows servers to communicate to clients that a URI is likely to become\n  unresponsive at a specified future point in time. Published in May 2019, it\n  provides a standardized mechanism for API deprecation signaling, enabling\n  clients to plan migrations before service retirement. The header value is an\n  HTTP-date timestamp following RFC 7231 syntax. A complementary sunset link\n  relation type allows resources to reference documentation covering the sunset\n  policy, migration guidance, and alternatives. RFC 9745 (Deprecation HTTP Header\n  Field) extends this pattern by providing a two-phase deprecation + sunset\n  lifecycle where Deprecation marks the start of deprecation and Sunset marks\n  the end-of-life. These two headers are widely adopted in REST API governance\n  practices and API lifecycle management tooling.\ntype:\
  \ Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Deprecation\n  - HTTP Headers\n  - RFC 8594\n  - RFC 9745\n  - API Lifecycle\n  - REST APIs\n  - Standards\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sunset-header/refs/heads/main/apis.yml\ncreated: '2026-03-29'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: sunset-header:sunset-header\n    name: Sunset Header (RFC 8594)\n    description: >-\n      The Sunset HTTP header field (RFC 8594) communicates the deprecation\n      timeline of API endpoints to consumers. The header value is an HTTP-date\n      timestamp indicating when a URI is expected to become unresponsive. It is\n      accompanied by a sunset link relation type for linking to deprecation\n      documentation and migration guidance.\n    humanURL: https://datatracker.ietf.org/doc/html/rfc8594\n    tags:\n      - HTTP Headers\n      - API Deprecation\n      - RFC 8594\n      - Sunset\n\
  \      - API Lifecycle\n    properties:\n      - type: Documentation\n        url: https://datatracker.ietf.org/doc/html/rfc8594\n      - type: Specification\n        url: https://www.rfc-editor.org/rfc/rfc8594\n  - aid: sunset-header:deprecation-header\n    name: Deprecation HTTP Header Field (RFC 9745)\n    description: >-\n      RFC 9745 defines the Deprecation HTTP response header field, which signals\n      to clients that a resource has been or will be deprecated. It complements\n      the Sunset header by marking the start of the deprecation lifecycle. The\n      header value is a structured date (Unix timestamp per RFC 9651). The\n      Sunset timestamp, if present, must not be earlier than the Deprecation\n      timestamp.\n    humanURL: https://www.rfc-editor.org/rfc/rfc9745.html\n    tags:\n      - HTTP Headers\n      - API Deprecation\n      - RFC 9745\n      - Deprecation\n      - API Lifecycle\n    properties:\n      - type: Documentation\n        url: https://www.rfc-editor.org/rfc/rfc9745.html\n\
  \      - type: Specification\n        url: https://datatracker.ietf.org/doc/html/rfc9745\ncommon:\n  - type: Website\n    url: https://datatracker.ietf.org/doc/html/rfc8594\n  - type: IETF Specification\n    url: https://www.rfc-editor.org/rfc/rfc8594\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sunset-header/refs/heads/main/apis.yml
tags:
- API Deprecation
- HTTP Headers
- RFC 8594
- RFC 9745
- API Lifecycle
- REST APIs
- Standards
url: https://raw.githubusercontent.com/api-evangelist/sunset-header/refs/heads/main/apis.yml
use_cases: []
---
