---
api_count: 1
api_specs:
- filename: nebraska-update-api-openapi.yml
  format: yaml
  label: Flatcar Nebraska Update API
  slug: nebraska-update-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/flatcar-container-linux/refs/heads/main/openapi/nebraska-update-api-openapi.yml
apis:
- description: Nebraska is the update management server for Flatcar Container Linux. It exposes a REST API for managing update applications, packages, channels, groups, instances, and activity. Flatcar instances pol
  name: Flatcar Nebraska Update API
  slug: nebraska-update-api
common:
- title: ''
  type: Website
  url: https://www.flatcar.org
- title: ''
  type: Documentation
  url: https://www.flatcar.org/docs/latest/
- title: ''
  type: GitHubOrganization
  url: https://github.com/flatcar
- title: ''
  type: SourceCode
  url: https://github.com/flatcar/flatcar
- title: ''
  type: NebraskaSource
  url: https://github.com/flatcar/nebraska
- title: ''
  type: Releases
  url: https://www.flatcar.org/releases/
- title: ''
  type: Community
  url: https://www.flatcar.org/community/
created: '2026-03-16'
description: Flatcar Container Linux is a CNCF incubating minimal, immutable Linux distribution designed for running containers. It provides automatic atomic updates through the Nebraska update server, ensuring nodes stay secure and consistent. Flatcar supports Kubernetes deployments on bare metal, cloud, and virtual environments with a focus on security and operational simplicity.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Flatcar Container Linux
skills: []
slug: flatcar-container-linux
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: flatcar-container-linux\nname: Flatcar Container Linux\ndescription: >-\n  Flatcar Container Linux is a CNCF incubating minimal, immutable Linux\n  distribution designed for running containers. It provides automatic\n  atomic updates through the Nebraska update server, ensuring nodes stay\n  secure and consistent. Flatcar supports Kubernetes deployments on bare\n  metal, cloud, and virtual environments with a focus on security and\n  operational simplicity.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/flatcar-container-linux/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Containers\n  - Immutable Infrastructure\n  - Incubating\n  - Linux\n  - Operating System\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\naccess: Open Source\nposition: Producer\napis:\n  - aid: flatcar-container-linux:nebraska-update-api\n    name: Flatcar\
  \ Nebraska Update API\n    description: >-\n      Nebraska is the update management server for Flatcar Container Linux.\n      It exposes a REST API for managing update applications, packages,\n      channels, groups, instances, and activity. Flatcar instances poll\n      Nebraska using the Omaha protocol for controlled rollouts, version\n      pinning, and update monitoring across fleets of Flatcar nodes.\n    humanURL: https://www.flatcar.org/docs/latest/nebraska/\n    baseURL: https://nebraska.flatcar-linux.org/api\n    tags:\n      - Activity\n      - Applications\n      - Channels\n      - Fleet Management\n      - Groups\n      - Instances\n      - Omaha Protocol\n      - Packages\n      - Updates\n    properties:\n      - type: Documentation\n        url: https://www.flatcar.org/docs/latest/nebraska/\n      - type: OpenAPI\n        url: openapi/nebraska-update-api-openapi.yml\n      - type: SourceCode\n        url: https://github.com/flatcar/nebraska\ncommon:\n  - type: Website\n\
  \    url: https://www.flatcar.org\n  - type: Documentation\n    url: https://www.flatcar.org/docs/latest/\n  - type: GitHubOrganization\n    url: https://github.com/flatcar\n  - type: SourceCode\n    url: https://github.com/flatcar/flatcar\n  - type: NebraskaSource\n    url: https://github.com/flatcar/nebraska\n  - type: Releases\n    url: https://www.flatcar.org/releases/\n  - type: Community\n    url: https://www.flatcar.org/community/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/flatcar-container-linux/refs/heads/main/apis.yml
tags:
- Cloud Native
- Containers
- Immutable Infrastructure
- Incubating
- Linux
- Operating System
url: https://raw.githubusercontent.com/api-evangelist/flatcar-container-linux/refs/heads/main/apis.yml
use_cases: []
---
