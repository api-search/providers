---
api_count: 2
api_specs:
- filename: frp-server-admin-api-openapi.yml
  format: yaml
  label: frp Server Admin API
  slug: server-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/frp/refs/heads/main/openapi/frp-server-admin-api-openapi.yml
- filename: frp-client-admin-api-openapi.yml
  format: yaml
  label: frp Client Admin API
  slug: client-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/frp/refs/heads/main/openapi/frp-client-admin-api-openapi.yml
apis:
- description: The frp server admin API is the HTTP control plane exposed by frps on its dashboard web server. It returns version and traffic information for the server, lists connected clients, lists and inspects a
  name: frp Server Admin API
  slug: server-admin-api
- description: The frp client admin API is the HTTP control plane exposed by frpc on its local web server. It supports hot-reloading the proxy and visitor configuration, stopping the running client, returning the ac
  name: frp Client Admin API
  slug: client-admin-api
common:
- title: ''
  type: Website
  url: https://gofrp.org/
- title: ''
  type: Documentation
  url: https://gofrp.org/en/docs/
- title: ''
  type: GettingStarted
  url: https://gofrp.org/en/docs/setup/
- title: ''
  type: SourceCode
  url: https://github.com/fatedier/frp
- title: ''
  type: Issues
  url: https://github.com/fatedier/frp/issues
- title: ''
  type: Releases
  url: https://github.com/fatedier/frp/releases
- title: ''
  type: License
  url: https://github.com/fatedier/frp/blob/master/LICENSE
created: '2026-03-27'
description: frp is an open-source fast reverse proxy that exposes services running behind a NAT or firewall to the public internet. Both the server (frps) and the client (frpc) include built-in HTTP admin APIs that operators can use to inspect runtime status, manage proxies and visitors, hot-reload configuration, and scrape Prometheus metrics.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: frp
skills: []
slug: frp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: frp\nname: frp\ndescription: >-\n  frp is an open-source fast reverse proxy that exposes services running behind a\n  NAT or firewall to the public internet. Both the server (frps) and the client\n  (frpc) include built-in HTTP admin APIs that operators can use to inspect\n  runtime status, manage proxies and visitors, hot-reload configuration, and\n  scrape Prometheus metrics.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: Open Source\ncreated: '2026-03-27'\nmodified: '2026-04-28'\ntags:\n  - NAT Traversal\n  - Reverse Proxy\n  - Tunneling\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/frp/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: frp:server-admin-api\n    name: frp Server Admin API\n    description: >-\n      The frp server admin API is the HTTP control plane exposed by frps on its\n      dashboard web server. It returns version and traffic information\
  \ for the\n      server, lists connected clients, lists and inspects active proxies of any\n      type, returns daily traffic counters per proxy, and lets operators clear\n      proxies that are offline. The API is secured with HTTP Basic auth using\n      the dashboard user and password configured in the frps webServer block.\n    humanURL: https://gofrp.org/en/docs/features/common/server-dashboard/\n    baseURL: http://localhost:7500\n    tags:\n      - NAT Traversal\n      - Reverse Proxy\n      - Server Admin\n      - Dashboard\n    properties:\n      - type: Documentation\n        url: https://gofrp.org/en/docs/features/common/server-dashboard/\n      - type: OpenAPI\n        url: openapi/frp-server-admin-api-openapi.yml\n  - aid: frp:client-admin-api\n    name: frp Client Admin API\n    description: >-\n      The frp client admin API is the HTTP control plane exposed by frpc on its\n      local web server. It supports hot-reloading the proxy and visitor\n      configuration, stopping\
  \ the running client, returning the active config,\n      replacing the active config, querying per-proxy and per-visitor status,\n      and (when a configuration store is enabled) listing, creating, updating,\n      and deleting persisted proxy and visitor definitions. The API is secured\n      with HTTP Basic auth using the user and password configured in the frpc\n      webServer block.\n    humanURL: https://gofrp.org/en/docs/reference/client-configures/\n    baseURL: http://127.0.0.1:7400\n    tags:\n      - NAT Traversal\n      - Reverse Proxy\n      - Client Admin\n      - Configuration\n    properties:\n      - type: Documentation\n        url: https://gofrp.org/en/docs/reference/client-configures/\n      - type: OpenAPI\n        url: openapi/frp-client-admin-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://gofrp.org/\n  - type: Documentation\n    url: https://gofrp.org/en/docs/\n  - type: GettingStarted\n    url: https://gofrp.org/en/docs/setup/\n  - type: SourceCode\n\
  \    url: https://github.com/fatedier/frp\n  - type: Issues\n    url: https://github.com/fatedier/frp/issues\n  - type: Releases\n    url: https://github.com/fatedier/frp/releases\n  - type: License\n    url: https://github.com/fatedier/frp/blob/master/LICENSE\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/frp/refs/heads/main/apis.yml
tags:
- NAT Traversal
- Reverse Proxy
- Tunneling
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/frp/refs/heads/main/apis.yml
use_cases: []
---
