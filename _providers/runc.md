---
api_count: 1
apis:
- description: runc is a CLI tool for spawning and running containers on Linux according to the OCI (Open Container Initiative) specification. It is the reference implementation of the OCI runtime specification, pro
  name: Runc
  slug: runc
common:
- title: ''
  type: Website
  url: https://opencontainers.org/
- title: ''
  type: GitHub Organization
  url: https://github.com/opencontainers
- title: ''
  type: GitHub Repository
  url: https://github.com/opencontainers/runc
- title: ''
  type: Blog
  url: https://opencontainers.org/posts/blog/
- title: ''
  type: Documentation
  url: https://github.com/opencontainers/runc/blob/main/README.md
- title: ''
  type: Specification
  url: https://github.com/opencontainers/runtime-spec
- title: ''
  type: Security
  url: https://github.com/opencontainers/runc/blob/main/SECURITY.md
created: '2026-03-26'
description: runc is a CLI tool for spawning and running containers on Linux according to the OCI (Open Container Initiative) specification. It is the reference implementation of the OCI runtime specification and is used as the default low-level container runtime by Docker, containerd, Podman, and other container platforms. runc manages container lifecycle operations including creating, starting, pausing, resuming, killing, and deleting containers. It implements the OCI Runtime Specification and exposes a command-line interface that higher-level runtimes use to manage individual container instances. runc also supports checkpoint/restore via CRIU, rootless containers (no root privileges needed via user namespaces), cgroup v2, seccomp syscall filtering, AppArmor, SELinux, and Intel Memory Protection Extensions. The current stable release line is 1.3.x (runc 1.5.0 expected late April 2026).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 43
  name: Runc Context
  property_count: 5
  slug: runc-context
layout: provider
modified: '2026-05-02'
name: Runc
skills: []
slug: runc
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: runc\nname: Runc\ndescription: >-\n  runc is a CLI tool for spawning and running containers on Linux according to\n  the OCI (Open Container Initiative) specification. It is the reference\n  implementation of the OCI runtime specification and is used as the default\n  low-level container runtime by Docker, containerd, Podman, and other container\n  platforms. runc manages container lifecycle operations including creating, starting,\n  pausing, resuming, killing, and deleting containers. It implements the OCI Runtime\n  Specification and exposes a command-line interface that higher-level runtimes use\n  to manage individual container instances. runc also supports checkpoint/restore via\n  CRIU, rootless containers (no root privileges needed via user namespaces), cgroup v2,\n  seccomp syscall filtering, AppArmor, SELinux, and Intel Memory Protection Extensions.\n  The current stable release line is 1.3.x (runc 1.5.0 expected late April 2026).\ntype: Index\nposition: Consumer\n\
  access: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Container Runtime\n  - Containers\n  - Linux\n  - OCI\n  - Open Source\n  - CNCF\n  - Open Container Initiative\n  - Cloud Native\nurl: https://raw.githubusercontent.com/api-evangelist/runc/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: runc:runc\n    name: Runc\n    description: >-\n      runc is a CLI tool for spawning and running containers on Linux according\n      to the OCI (Open Container Initiative) specification. It is the reference\n      implementation of the OCI runtime specification, providing a lightweight\n      and portable container runtime that can be used independently or embedded\n      into higher-level container systems like Docker and containerd. runc\n      implements the full OCI Runtime Spec lifecycle: create, start, state,\n      kill, delete. It also supports checkpoint/restore\
  \ via CRIU, rootless\n      containers, and cgroup v2. The container configuration is defined in a\n      config.json file following the OCI Runtime Specification schema.\n    humanURL: https://github.com/opencontainers/runc\n    tags:\n      - Container Runtime\n      - Containers\n      - Linux\n      - OCI\n      - Open Source\n      - CNCF\n      - Open Container Initiative\n      - Cloud Native\n    properties:\n      - type: Documentation\n        url: https://github.com/opencontainers/runc/blob/main/README.md\n      - type: Getting Started\n        url: https://github.com/opencontainers/runc#creating-an-oci-bundle\n      - type: GitHub Repository\n        url: https://github.com/opencontainers/runc\n      - type: Specification\n        url: https://github.com/opencontainers/runtime-spec\n      - type: Releases\n        url: https://github.com/opencontainers/runc/releases\n      - type: License\n        url: https://github.com/opencontainers/runc/blob/main/LICENSE\n      - type:\
  \ Security\n        url: https://github.com/opencontainers/runc/blob/main/SECURITY.md\n      - type: Changelog\n        url: https://github.com/opencontainers/runc/blob/main/CHANGELOG.md\n      - type: JSONSchema\n        url: json-schema/runc-container-config-schema.json\n      - type: JSONStructure\n        url: json-structure/runc-container-config-structure.json\n      - type: JSONLD\n        url: json-ld/runc-context.jsonld\n      - type: Example\n        url: examples/runc-container-config-example.json\n      - type: Vocabulary\n        url: vocabulary/runc-vocabulary.yml\ncommon:\n  - type: Website\n    url: https://opencontainers.org/\n  - type: GitHub Organization\n    url: https://github.com/opencontainers\n  - type: GitHub Repository\n    url: https://github.com/opencontainers/runc\n  - type: Blog\n    url: https://opencontainers.org/posts/blog/\n  - type: Documentation\n    url: https://github.com/opencontainers/runc/blob/main/README.md\n  - type: Specification\n    url: https://github.com/opencontainers/runtime-spec\n\
  \  - type: Security\n    url: https://github.com/opencontainers/runc/blob/main/SECURITY.md\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/runc/refs/heads/main/apis.yml
tags:
- Container Runtime
- Containers
- Linux
- OCI
- Open Source
- CNCF
- Open Container Initiative
- Cloud Native
url: https://raw.githubusercontent.com/api-evangelist/runc/refs/heads/main/apis.yml
use_cases: []
---
