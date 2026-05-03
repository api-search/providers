---
api_count: 1
api_specs:
- filename: podman-openapi.yml
  format: yaml
  label: Podman REST API
  slug: podman-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/podman/refs/heads/main/openapi/podman-openapi.yml
apis:
- description: The Podman REST API (libpod) provides a Docker-compatible API surface plus Podman-specific Libpod endpoints for managing containers, images, pods, volumes, networks, secrets, manifests, and the Podman
  name: Podman REST API
  slug: podman-rest-api
common:
- title: ''
  type: Website
  url: https://podman.io/
- title: ''
  type: Documentation
  url: https://docs.podman.io/
- title: ''
  type: GitHubOrganization
  url: https://github.com/containers
- title: ''
  type: SourceCode
  url: https://github.com/containers/podman
- title: ''
  type: Blog
  url: https://podman.io/blogs/
- title: ''
  type: Community
  url: https://podman.io/community/
- title: ''
  type: GettingStarted
  url: https://podman.io/get-started
created: '2026-03-16'
description: Podman is a daemonless, open-source container engine for developing, managing, and running OCI containers on Linux, supporting both rootful and rootless operation as a drop-in replacement for Docker. The Podman REST API exposes a Docker-compatible surface alongside Libpod-specific endpoints for pods, volumes, networks, secrets, generators, and system management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Podman
skills: []
slug: podman
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: podman\nname: Podman\ndescription: >-\n  Podman is a daemonless, open-source container engine for developing, managing,\n  and running OCI containers on Linux, supporting both rootful and rootless\n  operation as a drop-in replacement for Docker. The Podman REST API exposes a\n  Docker-compatible surface alongside Libpod-specific endpoints for pods,\n  volumes, networks, secrets, generators, and system management.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Containers\n  - DevOps\n  - OCI\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/podman/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: podman:podman-rest-api\n    name: Podman REST API\n    description: >-\n      The Podman REST API (libpod) provides a Docker-compatible API surface plus\n      Podman-specific\
  \ Libpod endpoints for managing containers, images, pods,\n      volumes, networks, secrets, manifests, and the Podman system service.\n      The API is published as a Swagger 2.0 specification generated from the\n      Podman source tree.\n    humanURL: https://docs.podman.io/en/latest/_static/api.html\n    baseURL: http://d/v6.0.0/libpod\n    tags:\n      - Containers\n      - DevOps\n      - OCI\n    properties:\n      - type: Documentation\n        url: https://docs.podman.io/en/latest/_static/api.html\n      - type: GettingStarted\n        url: https://docs.podman.io/en/latest/markdown/podman-system-service.1.html\n      - type: OpenAPI\n        url: openapi/podman-openapi.yml\ncommon:\n  - type: Website\n    url: https://podman.io/\n  - type: Documentation\n    url: https://docs.podman.io/\n  - type: GitHubOrganization\n    url: https://github.com/containers\n  - type: SourceCode\n    url: https://github.com/containers/podman\n  - type: Blog\n    url: https://podman.io/blogs/\n \
  \ - type: Community\n    url: https://podman.io/community/\n  - type: GettingStarted\n    url: https://podman.io/get-started\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/podman/refs/heads/main/apis.yml
tags:
- Cloud Native
- Containers
- DevOps
- OCI
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/podman/refs/heads/main/apis.yml
use_cases: []
---
