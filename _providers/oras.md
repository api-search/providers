---
api_count: 2
apis:
- description: Generic command-line registry client used to push and pull OCI artifacts to and from any OCI-compliant container registry.
  name: ORAS CLI
  slug: cli
- description: Client libraries for building custom OCI artifact tools and integrations on top of ORAS, available across multiple language ecosystems including Go, Rust, Python, JavaScript, .NET, and Java.
  name: ORAS Client Libraries
  slug: client-libraries
common:
- title: ''
  type: Website
  url: https://oras.land/
- title: ''
  type: Documentation
  url: https://oras.land/docs/
- title: ''
  type: GitHub Organization
  url: https://github.com/oras-project
- title: ''
  type: Community
  url: https://oras.land/community/
- title: ''
  type: CNCF
  url: https://www.cncf.io/projects/oras/
created: '2026-03-16'
description: ORAS (OCI Registry As Storage) is a CNCF project that provides a CLI and a set of client libraries for pushing and pulling arbitrary OCI artifacts to and from OCI-compliant registries, allowing container registries to be used as a generic artifact distribution mechanism.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: ORAS
skills: []
slug: oras
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oras\nname: ORAS\ndescription: >-\n  ORAS (OCI Registry As Storage) is a CNCF project that provides a CLI and a set\n  of client libraries for pushing and pulling arbitrary OCI artifacts to and from\n  OCI-compliant registries, allowing container registries to be used as a generic\n  artifact distribution mechanism.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Artifact Storage\n  - Cloud Native\n  - Container Registry\n  - OCI\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oras/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: oras:cli\n    name: ORAS CLI\n    description: >-\n      Generic command-line registry client used to push and pull OCI artifacts\n      to and from any OCI-compliant container registry.\n    humanURL: https://oras.land/docs/\n    tags:\n      - CLI\n      - OCI\n \
  \     - Artifacts\n    properties:\n      - type: Documentation\n        url: https://oras.land/docs/\n      - type: Installation\n        url: https://oras.land/docs/installation\n      - type: Commands\n        url: https://oras.land/docs/commands/oras\n      - type: Source Code\n        url: https://github.com/oras-project/oras\n  - aid: oras:client-libraries\n    name: ORAS Client Libraries\n    description: >-\n      Client libraries for building custom OCI artifact tools and integrations on\n      top of ORAS, available across multiple language ecosystems including Go,\n      Rust, Python, JavaScript, .NET, and Java.\n    humanURL: https://oras.land/docs/client_libraries/overview\n    tags:\n      - SDK\n      - Libraries\n      - OCI\n    properties:\n      - type: Documentation\n        url: https://oras.land/docs/client_libraries/overview\n      - type: Go\n        url: https://github.com/oras-project/oras-go\n      - type: Rust\n        url: https://github.com/oras-project/rust-oci-client\n\
  \      - type: Python\n        url: https://github.com/oras-project/oras-py\n      - type: JavaScript\n        url: https://github.com/oras-project/oras-js\ncommon:\n  - type: Website\n    url: https://oras.land/\n  - type: Documentation\n    url: https://oras.land/docs/\n  - type: GitHub Organization\n    url: https://github.com/oras-project\n  - type: Community\n    url: https://oras.land/community/\n  - type: CNCF\n    url: https://www.cncf.io/projects/oras/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oras/refs/heads/main/apis.yml
tags:
- Artifact Storage
- Cloud Native
- Container Registry
- OCI
url: https://raw.githubusercontent.com/api-evangelist/oras/refs/heads/main/apis.yml
use_cases: []
---
