---
api_count: 3
apis:
- description: Netflix Zuul is an L7 application gateway built on Netty that provides dynamic routing, load balancing, authentication, monitoring, and resiliency for edge services. Zuul 3.x is the current release, s
  name: Netflix Zuul Gateway
  slug: netflix-zuul-gateway
- description: The Zuul Filters API provides the core extension point for building custom logic into the Zuul gateway pipeline. Developers implement inbound, endpoint, and outbound filters using synchronous or async
  name: Netflix Zuul Filters API
  slug: netflix-zuul-filters-api
- description: Zuul Push Messaging enables server-to-client push communications over WebSockets and Server Sent Events (SSE). It provides a PushConnectionRegistry for managing connected clients and supports distribu
  name: Netflix Zuul Push Messaging
  slug: netflix-zuul-push-messaging
common:
- title: ''
  type: Website
  url: https://github.com/Netflix/zuul
- title: ''
  type: GitHub Organization
  url: https://github.com/Netflix
- title: ''
  type: GitHubRepository
  url: https://github.com/Netflix/zuul
- title: ''
  type: Documentation
  url: https://github.com/Netflix/zuul/wiki
- title: ''
  type: Getting Started
  url: https://github.com/Netflix/zuul/wiki/Getting-Started-3.0
- title: ''
  type: Change Log
  url: https://github.com/Netflix/zuul/releases
- title: ''
  type: Issue Tracker
  url: https://github.com/Netflix/zuul/issues
- title: ''
  type: Blog
  url: https://netflixtechblog.com/open-sourcing-zuul-2-82ea476cb2b3
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/netflix-zuul
created: '2026-03-16'
description: Netflix Zuul is an open-source L7 application gateway that provides dynamic routing, monitoring, resiliency, and security for edge services. Originally developed by Netflix, Zuul 2 uses Netty for non-blocking I/O and is commonly used as an API gateway and edge service.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Netflix Zuul
skills: []
slug: netflix-zuul
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: netflix-zuul\nname: Netflix Zuul\ndescription: >-\n  Netflix Zuul is an open-source L7 application gateway that provides dynamic\n  routing, monitoring, resiliency, and security for edge services. Originally\n  developed by Netflix, Zuul 2 uses Netty for non-blocking I/O and is commonly\n  used as an API gateway and edge service.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - Edge Service\n  - Netflix\n  - Open Source\nurl: https://raw.githubusercontent.com/api-evangelist/netflix-zuul/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: netflix-zuul:netflix-zuul-gateway\n    name: Netflix Zuul Gateway\n    description: >-\n      Netflix Zuul is an L7 application gateway built on Netty that provides\n      dynamic routing, load balancing, authentication, monitoring, and resiliency\n      for edge services. Zuul 3.x is the current\
  \ release, supporting inbound,\n      endpoint, and outbound filter pipelines for intercepting and modifying\n      HTTP requests and responses at the edge.\n    humanURL: https://github.com/Netflix/zuul\n    tags:\n      - API Gateway\n      - Edge Service\n      - Netty\n      - Routing\n    properties:\n      - type: Documentation\n        url: https://github.com/Netflix/zuul/wiki\n      - type: Getting Started\n        url: https://github.com/Netflix/zuul/wiki/Getting-Started-3.0\n      - type: Reference\n        url: https://github.com/Netflix/zuul/wiki/How-it-Works-3.0\n      - type: GitHubRepository\n        url: https://github.com/Netflix/zuul\n      - type: Change Log\n        url: https://github.com/Netflix/zuul/releases\n      - type: Issue Tracker\n        url: https://github.com/Netflix/zuul/issues\n  - aid: netflix-zuul:netflix-zuul-filters-api\n    name: Netflix Zuul Filters API\n    description: >-\n      The Zuul Filters API provides the core extension point for building\n\
  \      custom logic into the Zuul gateway pipeline. Developers implement\n      inbound, endpoint, and outbound filters using synchronous or asynchronous\n      base classes to handle authentication, routing, rate limiting, metrics,\n      and response decoration.\n    humanURL: https://github.com/Netflix/zuul/wiki/Filters\n    tags:\n      - Extension\n      - Filters\n      - Middleware\n      - Routing\n    properties:\n      - type: Documentation\n        url: https://github.com/Netflix/zuul/wiki/Filters\n      - type: Reference\n        url: https://github.com/Netflix/zuul/wiki/Writing-Filters\n      - type: GitHubRepository\n        url: https://github.com/Netflix/zuul\n  - aid: netflix-zuul:netflix-zuul-push-messaging\n    name: Netflix Zuul Push Messaging\n    description: >-\n      Zuul Push Messaging enables server-to-client push communications over\n      WebSockets and Server Sent Events (SSE). It provides a\n      PushConnectionRegistry for managing connected clients and supports\n\
  \      distributed deployments using external datastores such as Redis,\n      Cassandra, or DynamoDB for multi-node clusters.\n    humanURL: https://github.com/Netflix/zuul/wiki/Push-Messaging\n    tags:\n      - Push Messaging\n      - Real Time\n      - Server Sent Events\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://github.com/Netflix/zuul/wiki/Push-Messaging\n      - type: GitHubRepository\n        url: https://github.com/Netflix/zuul\ncommon:\n  - type: Website\n    url: https://github.com/Netflix/zuul\n  - type: GitHub Organization\n    url: https://github.com/Netflix\n  - type: GitHubRepository\n    url: https://github.com/Netflix/zuul\n  - type: Documentation\n    url: https://github.com/Netflix/zuul/wiki\n  - type: Getting Started\n    url: https://github.com/Netflix/zuul/wiki/Getting-Started-3.0\n  - type: Change Log\n    url: https://github.com/Netflix/zuul/releases\n  - type: Issue Tracker\n    url: https://github.com/Netflix/zuul/issues\n\
  \  - type: Blog\n    url: https://netflixtechblog.com/open-sourcing-zuul-2-82ea476cb2b3\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/netflix-zuul\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/netflix-zuul/refs/heads/main/apis.yml
tags:
- API Gateway
- Edge Service
- Netflix
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/netflix-zuul/refs/heads/main/apis.yml
use_cases: []
---
