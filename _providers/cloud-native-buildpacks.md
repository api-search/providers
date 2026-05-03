---
api_count: 7
apis:
- description: The Buildpack API is the contract between a buildpack and the lifecycle. It defines the detect and build executables, layers, build-plan provisions and requirements, and image extension lifecycle that
  name: Buildpack API
  slug: buildpack-api
- description: The Platform API is the contract between the CNB lifecycle and a platform such as pack, kpack, or a CI runner. It defines how builders, stacks, run images, and inputs are passed to the lifecycle phase
  name: Platform API
  slug: platform-api
- description: The Distribution API specifies how buildpacks and builders are packaged as OCI artifacts, signed, and distributed through OCI registries. It also covers how meta-buildpacks compose other buildpacks an
  name: Distribution API
  slug: distribution-api
- description: pack is the reference command-line interface for Cloud Native Buildpacks. It implements the Platform API to build OCI images from source on a developer's workstation, manages builders and buildpack pa
  name: pack CLI
  slug: pack-cli
- description: The CNB Lifecycle is the reference implementation of the Buildpack and Platform APIs. It runs the detect, analyze, restore, build, export, and rebase phases used by all CNB platforms to produce reprod
  name: CNB Lifecycle
  slug: lifecycle
- description: kpack is a community Kubernetes-native implementation of Cloud Native Buildpacks. It exposes Image, Builder, ClusterBuilder, and ClusterStack custom resources for declaring continuously rebuilt OCI im
  name: kpack
  slug: kpack
- description: The Cloud Native Buildpacks registry indexes published buildpacks for discovery and reuse. It mirrors metadata for buildpack packages stored in OCI registries and exposes a browseable catalog at regis
  name: Buildpack Registry
  slug: registry
capabilities:
- description: ''
  name: Cloud Native Buildpacks
  slug: cloud-native-buildpacks
common:
- title: ''
  type: Website
  url: https://buildpacks.io/
- title: ''
  type: Documentation
  url: https://buildpacks.io/docs/
- title: ''
  type: Specification
  url: https://github.com/buildpacks/spec
- title: ''
  type: GitHub
  url: https://github.com/buildpacks
- title: ''
  type: Community
  url: https://buildpacks.io/community/
- title: ''
  type: Slack
  url: https://slack.cncf.io/
- title: ''
  type: Blog
  url: https://medium.com/buildpacks
- title: ''
  type: Roadmap
  url: https://github.com/buildpacks/roadmap
- title: ''
  type: CNCF
  url: https://www.cncf.io/projects/buildpacks/
- title: ''
  type: JSON-LD
  url: json-ld/cloud-native-buildpacks-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloud-native-buildpacks-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cloud-native-buildpacks.yaml
created: '2024-01-01'
description: Cloud Native Buildpacks (CNB) is a CNCF-graduated specification and set of tooling for transforming application source code into OCI images that can run on any cloud. The project unifies the Heroku and Cloud Foundry buildpack ecosystems around an open standard for detection, build, and image export. The reference implementation lifecycle, the pack CLI for local builds, the kpack server-side builder, and a registry of distribution buildpacks together form the CNB ecosystem. CNB is built around a documented Buildpack API, Platform API, and Distribution API, all versioned and published in the github.com/buildpacks specifications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloud Native Buildpacks Context
  property_count: 7
  slug: cloud-native-buildpacks-context
layout: provider
modified: '2026-04-23'
name: Cloud Native Buildpacks
rules:
- name: Cloud Native Buildpacks API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: cloud-native-buildpacks-rules
skills: []
slug: cloud-native-buildpacks
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloud-native-buildpacks\nname: Cloud Native Buildpacks\ndescription: >-\n  Cloud Native Buildpacks (CNB) is a CNCF-graduated specification and\n  set of tooling for transforming application source code into OCI\n  images that can run on any cloud. The project unifies the Heroku and\n  Cloud Foundry buildpack ecosystems around an open standard for\n  detection, build, and image export. The reference implementation\n  lifecycle, the pack CLI for local builds, the kpack server-side\n  builder, and a registry of distribution buildpacks together form the\n  CNB ecosystem. CNB is built around a documented Buildpack API,\n  Platform API, and Distribution API, all versioned and published in\n  the github.com/buildpacks specifications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/cloud-native-buildpacks/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-23'\n\
  specificationVersion: '0.19'\nx-type: opensource\ntags:\n  - Buildpacks\n  - CNCF\n  - Containers\n  - Images\n  - OCI\n  - Open Source\n  - Platform\n  - Reproducible Builds\napis:\n  - aid: cloud-native-buildpacks:buildpack-api\n    name: Buildpack API\n    tags:\n      - Buildpacks\n      - Specification\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/buildpacks/spec/blob/main/buildpack.md\n    properties:\n      - url: https://github.com/buildpacks/spec/blob/main/buildpack.md\n        type: Specification\n      - url: https://buildpacks.io/docs/for-buildpack-authors/\n        type: Documentation\n    description: >-\n      The Buildpack API is the contract between a buildpack and the\n      lifecycle. It defines the detect and build executables, layers,\n      build-plan provisions and requirements, and image extension\n      lifecycle that buildpack authors implement to participate in a\n      CNB build.\n  -\
  \ aid: cloud-native-buildpacks:platform-api\n    name: Platform API\n    tags:\n      - Lifecycle\n      - Platform\n      - Specification\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/buildpacks/spec/blob/main/platform.md\n    properties:\n      - url: https://github.com/buildpacks/spec/blob/main/platform.md\n        type: Specification\n      - url: https://buildpacks.io/docs/for-platform-operators/\n        type: Documentation\n    description: >-\n      The Platform API is the contract between the CNB lifecycle and\n      a platform such as pack, kpack, or a CI runner. It defines how\n      builders, stacks, run images, and inputs are passed to the\n      lifecycle phases (analyze, detect, restore, build, export, and\n      rebase) and how outputs are consumed.\n  - aid: cloud-native-buildpacks:distribution-api\n    name: Distribution API\n    tags:\n      - Distribution\n      - Registries\n      - Specification\n\
  \    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/buildpacks/spec/blob/main/distribution.md\n    properties:\n      - url: https://github.com/buildpacks/spec/blob/main/distribution.md\n        type: Specification\n    description: >-\n      The Distribution API specifies how buildpacks and builders are\n      packaged as OCI artifacts, signed, and distributed through OCI\n      registries. It also covers how meta-buildpacks compose other\n      buildpacks and how stacks and run images are referenced.\n  - aid: cloud-native-buildpacks:pack-cli\n    name: pack CLI\n    tags:\n      - CLI\n      - Tooling\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://buildpacks.io/docs/for-app-developers/how-to/build-inputs/\n    properties:\n      - url: https://buildpacks.io/docs/for-app-developers/how-to/build-inputs/\n        type: Documentation\n      - url: https://github.com/buildpacks/pack\n\
  \        type: Source Code\n    description: >-\n      pack is the reference command-line interface for Cloud Native\n      Buildpacks. It implements the Platform API to build OCI images\n      from source on a developer's workstation, manages builders and\n      buildpack packages, and integrates with Docker and OCI registries.\n  - aid: cloud-native-buildpacks:lifecycle\n    name: CNB Lifecycle\n    tags:\n      - Lifecycle\n      - Reference Implementation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/buildpacks/lifecycle\n    properties:\n      - url: https://github.com/buildpacks/lifecycle\n        type: Source Code\n      - url: https://buildpacks.io/docs/for-platform-operators/concepts/lifecycle/\n        type: Documentation\n    description: >-\n      The CNB Lifecycle is the reference implementation of the\n      Buildpack and Platform APIs. It runs the detect, analyze,\n      restore, build, export, and\
  \ rebase phases used by all CNB\n      platforms to produce reproducible OCI images.\n  - aid: cloud-native-buildpacks:kpack\n    name: kpack\n    tags:\n      - Kubernetes\n      - Server-side Builds\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/buildpacks-community/kpack\n    properties:\n      - url: https://github.com/buildpacks-community/kpack\n        type: Source Code\n      - url: https://github.com/buildpacks-community/kpack/blob/main/docs/image.md\n        type: Documentation\n    description: >-\n      kpack is a community Kubernetes-native implementation of Cloud\n      Native Buildpacks. It exposes Image, Builder, ClusterBuilder,\n      and ClusterStack custom resources for declaring continuously\n      rebuilt OCI images using CNB.\n  - aid: cloud-native-buildpacks:registry\n    name: Buildpack Registry\n    tags:\n      - Discovery\n      - Registry\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://registry.buildpacks.io/\n    properties:\n      - url: https://registry.buildpacks.io/\n        type: Registry\n      - url: https://github.com/buildpacks/registry-api\n        type: Source Code\n    description: >-\n      The Cloud Native Buildpacks registry indexes published\n      buildpacks for discovery and reuse. It mirrors metadata for\n      buildpack packages stored in OCI registries and exposes a\n      browseable catalog at registry.buildpacks.io.\ncommon:\n  - type: Website\n    url: https://buildpacks.io/\n  - type: Documentation\n    url: https://buildpacks.io/docs/\n  - type: Specification\n    url: https://github.com/buildpacks/spec\n  - type: GitHub\n    url: https://github.com/buildpacks\n  - type: Community\n    url: https://buildpacks.io/community/\n  - type: Slack\n    url: https://slack.cncf.io/\n  - type: Blog\n    url: https://medium.com/buildpacks\n  - type: Roadmap\n    url: https://github.com/buildpacks/roadmap\n  - type: CNCF\n    url:\
  \ https://www.cncf.io/projects/buildpacks/\n  - type: JSON-LD\n    url: json-ld/cloud-native-buildpacks-context.jsonld\n  - type: Spectral\n    url: rules/cloud-native-buildpacks-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cloud-native-buildpacks.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloud-native-buildpacks/refs/heads/main/apis.yml
tags:
- Buildpacks
- CNCF
- Containers
- Images
- OCI
- Open Source
- Platform
- Reproducible Builds
url: https://raw.githubusercontent.com/api-evangelist/cloud-native-buildpacks/refs/heads/main/apis.yml
use_cases: []
---
