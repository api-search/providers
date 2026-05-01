---
api_count: 3
api_specs:
- filename: fluentd-forward-protocol-asyncapi.yml
  format: yaml
  label: Fluentd Forward Protocol
  slug: fluentd-forward-protocol
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/fluentd/refs/heads/main/asyncapi/fluentd-forward-protocol-asyncapi.yml
- filename: fluentd-http-input-openapi.yml
  format: yaml
  label: Fluentd HTTP Input API
  slug: fluentd-http-input
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fluentd/refs/heads/main/openapi/fluentd-http-input-openapi.yml
apis:
- description: The Fluentd Plugin API allows developers to write custom input, output, filter, parser, formatter, and buffer plugins in Ruby. Plugins are distributed as RubyGems and integrate with Fluentd's plugin m
  name: Fluentd Plugin API
  slug: fluentd-plugin-api
- description: The Fluentd Forward Protocol is a binary protocol used to transport event streams between Fluentd nodes and compatible agents over TCP. It supports multiple transport modes including Message, Forward,
  name: Fluentd Forward Protocol
  slug: fluentd-forward-protocol
- description: The Fluentd HTTP Input plugin exposes an HTTP endpoint that accepts log records posted as JSON or form-encoded data. It allows applications to send events to Fluentd over standard HTTP, making it acce
  name: Fluentd HTTP Input API
  slug: fluentd-http-input
asyncapis:
- description: The Fluentd Forward Protocol is a binary MessagePack-based protocol used to transport event streams between Fluentd nodes, Fluent Bit agents, and compatible forwarders over TCP or TLS. It supports mul
  name: Fluentd Forward Protocol
  slug: fluentd-forward-protocol-asyncapi
common:
- title: ''
  type: JSONSchema
  url: json-schema/fluentd-log-event-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/fluentd-context.jsonld
- title: ''
  type: Website
  url: https://www.fluentd.org/
- title: ''
  type: Documentation
  url: https://docs.fluentd.org/
- title: ''
  type: Getting Started
  url: https://docs.fluentd.org/quickstart
- title: ''
  type: GitHub Organization
  url: https://github.com/fluent
- title: ''
  type: GitHubRepository
  url: https://github.com/fluent/fluentd
- title: ''
  type: Blog
  url: https://www.fluentd.org/blog/
- title: ''
  type: Change Log
  url: https://github.com/fluent/fluentd/blob/master/CHANGELOG.md
- title: ''
  type: Community
  url: https://www.fluentd.org/community/
- title: ''
  type: Support
  url: https://docs.fluentd.org/quickstart/support
- title: ''
  type: Slack
  url: https://slack.fluentd.org/
created: '2025-01-01'
description: Open source data collector for unified logging layer that allows you to unify data collection and consumption for better use and understanding of data.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Fluentd Context
  property_count: 7
  slug: fluentd-context
layout: provider
modified: '2026-04-28'
name: Fluentd
skills: []
slug: fluentd
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fluentd\nname: Fluentd\ndescription: Open source data collector for unified logging layer that allows you to unify data collection and consumption for better use and understanding of data.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/fluentd/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Data Collection\n  - Logging\n  - Open Source\napis:\n  - aid: fluentd:fluentd-plugin-api\n    name: Fluentd Plugin API\n    description: >-\n      The Fluentd Plugin API allows developers to write custom input, output,\n      filter, parser, formatter, and buffer plugins in Ruby. Plugins are\n      distributed as RubyGems and integrate with Fluentd's plugin management\n      system to extend data collection and processing pipelines.\n    humanURL: https://docs.fluentd.org/plugin-development\n    tags:\n      -\
  \ Open Source\n      - Plugin Development\n      - Ruby\n    properties:\n      - type: Documentation\n        url: https://docs.fluentd.org/plugin-development\n      - type: Reference\n        url: https://docs.fluentd.org/plugin-development/api-plugin-base\n  - aid: fluentd:fluentd-forward-protocol\n    name: Fluentd Forward Protocol\n    description: >-\n      The Fluentd Forward Protocol is a binary protocol used to transport event\n      streams between Fluentd nodes and compatible agents over TCP. It supports\n      multiple transport modes including Message, Forward, PackedForward, and\n      CompressedPackedForward, and includes authentication and heartbeat\n      mechanisms.\n    humanURL: https://github.com/fluent/fluentd/wiki/Forward-Protocol-Specification-v1\n    tags:\n      - Logging\n      - Networking\n      - Protocol\n    properties:\n      - type: Documentation\n        url: https://github.com/fluent/fluentd/wiki/Forward-Protocol-Specification-v1\n      - type: Reference\n\
  \        url: https://docs.fluentd.org/input/forward\n      - type: AsyncAPI\n        url: asyncapi/fluentd-forward-protocol-asyncapi.yml\n  - aid: fluentd:fluentd-http-input\n    name: Fluentd HTTP Input API\n    description: >-\n      The Fluentd HTTP Input plugin exposes an HTTP endpoint that accepts\n      log records posted as JSON or form-encoded data. It allows applications\n      to send events to Fluentd over standard HTTP, making it accessible from\n      any language or platform that can make HTTP requests.\n    humanURL: https://docs.fluentd.org/input/http\n    tags:\n      - HTTP\n      - Input\n      - Logging\n    properties:\n      - type: Documentation\n        url: https://docs.fluentd.org/input/http\n      - type: OpenAPI\n        url: openapi/fluentd-http-input-openapi.yml\ncommon:\n  - type: JSONSchema\n    url: json-schema/fluentd-log-event-schema.json\n  - type: JSON-LD\n    url: json-ld/fluentd-context.jsonld\n  - type: Website\n    url: https://www.fluentd.org/\n\
  \  - type: Documentation\n    url: https://docs.fluentd.org/\n  - type: Getting Started\n    url: https://docs.fluentd.org/quickstart\n  - type: GitHub Organization\n    url: https://github.com/fluent\n  - type: GitHubRepository\n    url: https://github.com/fluent/fluentd\n  - type: Blog\n    url: https://www.fluentd.org/blog/\n  - type: Change Log\n    url: https://github.com/fluent/fluentd/blob/master/CHANGELOG.md\n  - type: Community\n    url: https://www.fluentd.org/community/\n  - type: Support\n    url: https://docs.fluentd.org/quickstart/support\n  - type: Slack\n    url: https://slack.fluentd.org/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fluentd/refs/heads/main/apis.yml
tags:
- Data Collection
- Logging
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/fluentd/refs/heads/main/apis.yml
use_cases: []
---
