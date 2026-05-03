---
api_count: 1
apis:
- description: Twirp is a simple RPC framework with protobuf service definitions. Define your service in a .proto file and Twirp generates servers and clients implementing the Twirp wire protocol. Services are expos
  name: Twirp RPC Framework
  slug: twirp-framework
common:
- title: ''
  type: Website
  url: https://twitchtv.github.io/twirp/
- title: ''
  type: Documentation
  url: https://twitchtv.github.io/twirp/docs/intro.html
- title: ''
  type: GitHub Organization
  url: https://github.com/twitchtv
- title: ''
  type: GitHub Repository
  url: https://github.com/twitchtv/twirp
- title: ''
  type: Wire Protocol
  url: https://github.com/twitchtv/twirp/blob/main/PROTOCOL.md
- title: ''
  type: License
  url: https://github.com/twitchtv/twirp/blob/main/LICENSE
- title: ''
  type: Contributing
  url: https://github.com/twitchtv/twirp/blob/main/CONTRIBUTING.md
- title: ''
  type: JSONSchema
  url: json-schema/twirp-error-schema.json
- title: ''
  type: JSONLD
  url: json-ld/twirp-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/twirp-vocabulary.yml
created: '2026-03-27'
description: Twirp is a simple RPC framework built on Protocol Buffers, created by Twitch, that generates routing and serialization code from Protobuf service definitions for Go and other languages. Similar to gRPC but runs on the standard library's net/http Server without custom HTTP server or transport implementations. Supports both binary Protobuf and JSON serialization, making debugging easy. Uses HTTP POST for all requests with URLs in the format /twirp/[Package].[Service]/[Method]. Protocol version 7 is the current stable version. Licensed under Apache 2.0.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Twirp Context
  property_count: 5
  slug: twirp-context
layout: provider
modified: '2026-05-03'
name: Twirp
skills: []
slug: twirp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: twirp\nname: Twirp\ndescription: >-\n  Twirp is a simple RPC framework built on Protocol Buffers, created by\n  Twitch, that generates routing and serialization code from Protobuf\n  service definitions for Go and other languages. Similar to gRPC but runs\n  on the standard library's net/http Server without custom HTTP server or\n  transport implementations. Supports both binary Protobuf and JSON serialization,\n  making debugging easy. Uses HTTP POST for all requests with URLs in the format\n  /twirp/[Package].[Service]/[Method]. Protocol version 7 is the current stable\n  version. Licensed under Apache 2.0.\ntype: Contract\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Protocol Buffers\n  - RPC\n  - Go\n  - SDKs\n  - Open Source\n  - Protobuf\ncreated: '2026-03-27'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/twirp/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\n\
  apis:\n  - aid: twirp:twirp-framework\n    name: Twirp RPC Framework\n    description: >-\n      Twirp is a simple RPC framework with protobuf service definitions. Define\n      your service in a .proto file and Twirp generates servers and clients\n      implementing the Twirp wire protocol. Services are exposed over HTTP using\n      POST requests with paths in the form /twirp/[Package].[Service]/[Method].\n      Supports both Protobuf binary encoding (Content-Type: application/protobuf)\n      and JSON encoding (Content-Type: application/json). Includes a Go runtime\n      and protoc-gen-twirp code generator plugin.\n    humanURL: https://twitchtv.github.io/twirp/\n    baseURL: https://twitchtv.github.io/twirp/\n    tags:\n      - Protocol Buffers\n      - RPC\n      - Go\n      - Code Generation\n    properties:\n      - type: Documentation\n        url: https://twitchtv.github.io/twirp/docs/intro.html\n      - type: Getting Started\n        url: https://twitchtv.github.io/twirp/docs/install.html\n\
  \      - type: GitHub\n        url: https://github.com/twitchtv/twirp\n      - type: Wire Protocol\n        url: https://github.com/twitchtv/twirp/blob/main/PROTOCOL.md\n\ncommon:\n  - type: Website\n    url: https://twitchtv.github.io/twirp/\n  - type: Documentation\n    url: https://twitchtv.github.io/twirp/docs/intro.html\n  - type: GitHub Organization\n    url: https://github.com/twitchtv\n  - type: GitHub Repository\n    url: https://github.com/twitchtv/twirp\n  - type: Wire Protocol\n    url: https://github.com/twitchtv/twirp/blob/main/PROTOCOL.md\n  - type: License\n    url: https://github.com/twitchtv/twirp/blob/main/LICENSE\n  - type: Contributing\n    url: https://github.com/twitchtv/twirp/blob/main/CONTRIBUTING.md\n  - type: JSONSchema\n    url: json-schema/twirp-error-schema.json\n  - type: JSONLD\n    url: json-ld/twirp-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/twirp-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/twirp/refs/heads/main/apis.yml
tags:
- Protocol Buffers
- RPC
- Go
- SDKs
- Open Source
- Protobuf
url: https://raw.githubusercontent.com/api-evangelist/twirp/refs/heads/main/apis.yml
use_cases: []
---
