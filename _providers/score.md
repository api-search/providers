---
api_count: 3
apis:
- description: The Score Specification (score.yaml) is a declarative, platform-agnostic workload definition format that captures containers, service ports, and resource dependencies in a single file. Reference CLI i
  name: Score Specification
  slug: score-specification
- description: score-compose is the reference Score implementation that translates Score YAML workload specifications into Docker Compose configuration files. It enables local development environments that mirror pr
  name: score-compose
  slug: score-compose
- description: score-k8s is the reference Score implementation that translates Score YAML workload specifications into Kubernetes manifests including Deployments, Services, ConfigMaps, and Secrets. It supports Kuber
  name: score-k8s
  slug: score-k8s
common:
- title: ''
  type: Website
  url: https://score.dev/
- title: ''
  type: GitHub Organization
  url: https://github.com/score-spec
- title: ''
  type: Documentation
  url: https://docs.score.dev/
- title: ''
  type: Slack Channel
  url: https://cloud-native.slack.com/archives/C07DN0D1UCW
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/score/refs/heads/main/json-ld/score-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/score/refs/heads/main/vocabulary/score-vocabulary.yml
created: '2026-05-02'
description: Score is an open-source, platform-agnostic workload specification developed under the Cloud Native Computing Foundation (CNCF) Sandbox program. It provides a developer-centric YAML specification that enables teams to define application workloads once and deploy them across multiple container platforms including Docker Compose, Kubernetes, and cloud runtimes without environment-specific configuration drift. The score-spec organization provides reference CLI implementations (score-compose and score-k8s) that translate Score YAML into platform-specific manifests, eliminating YAML bloat and reducing cognitive load for platform engineering teams.
features: []
image: ''
integrations: []
jsonld:
- class_count: 44
  name: Score Context
  property_count: 1
  slug: score-context
layout: provider
modified: '2026-05-02'
name: Score
skills: []
slug: score
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: score\nname: Score\ndescription: >-\n  Score is an open-source, platform-agnostic workload specification developed\n  under the Cloud Native Computing Foundation (CNCF) Sandbox program. It provides\n  a developer-centric YAML specification that enables teams to define application\n  workloads once and deploy them across multiple container platforms including\n  Docker Compose, Kubernetes, and cloud runtimes without environment-specific\n  configuration drift. The score-spec organization provides reference CLI\n  implementations (score-compose and score-k8s) that translate Score YAML into\n  platform-specific manifests, eliminating YAML bloat and reducing cognitive\n  load for platform engineering teams.\nurl: https://raw.githubusercontent.com/api-evangelist/score/refs/heads/main/apis.yml\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Platform Engineering\n  - Cloud Native\n  - CNCF\n  - Workload Specification\n  - Kubernetes\n\
  \  - Docker\n  - Developer Experience\n  - Open Source\napis:\n  - aid: score:score-specification\n    name: Score Specification\n    description: >-\n      The Score Specification (score.yaml) is a declarative, platform-agnostic\n      workload definition format that captures containers, service ports, and\n      resource dependencies in a single file. Reference CLI implementations\n      (score-compose and score-k8s) translate Score files into Docker Compose\n      manifests or Kubernetes manifests respectively. The specification supports\n      metadata, container definitions with environment variables and volume mounts,\n      service port exposure, health probes, and resource references using\n      placeholder syntax.\n    humanURL: https://score.dev/\n    tags:\n      - Platform Engineering\n      - Workload Specification\n      - Cloud Native\n      - CNCF\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://docs.score.dev/\n      - type: Specification\n\
  \        url: https://docs.score.dev/docs/score-specification/score-spec-reference/\n      - type: GitHub Repository\n        url: https://github.com/score-spec/spec\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/score/refs/heads/main/vocabulary/score-vocabulary.yml\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/score/refs/heads/main/json-ld/score-context.jsonld\n  - aid: score:score-compose\n    name: score-compose\n    description: >-\n      score-compose is the reference Score implementation that translates Score\n      YAML workload specifications into Docker Compose configuration files. It\n      enables local development environments that mirror production workload\n      definitions, supports resource provisioners for common dependencies like\n      databases and message queues, and generates runnable Docker Compose files\n      from a single score.yaml source.\n    humanURL: https://score.dev/\n\
  \    tags:\n      - Docker Compose\n      - CLI\n      - Local Development\n      - Platform Engineering\n    properties:\n      - type: Documentation\n        url: https://docs.score.dev/docs/score-implementation/score-compose/\n      - type: GitHub Repository\n        url: https://github.com/score-spec/score-compose\n  - aid: score:score-k8s\n    name: score-k8s\n    description: >-\n      score-k8s is the reference Score implementation that translates Score YAML\n      workload specifications into Kubernetes manifests including Deployments,\n      Services, ConfigMaps, and Secrets. It supports Kubernetes resource\n      provisioners, patch templates for customizing generated manifests, and\n      enables consistent workload configuration from development to production\n      on Kubernetes.\n    humanURL: https://score.dev/\n    tags:\n      - Kubernetes\n      - CLI\n      - Platform Engineering\n      - Cloud Native\n    properties:\n      - type: Documentation\n        url: https://docs.score.dev/docs/score-implementation/score-k8s/\n\
  \      - type: GitHub Repository\n        url: https://github.com/score-spec/score-k8s\ncommon:\n  - type: Website\n    url: https://score.dev/\n  - type: GitHub Organization\n    url: https://github.com/score-spec\n  - type: Documentation\n    url: https://docs.score.dev/\n  - type: Slack Channel\n    url: https://cloud-native.slack.com/archives/C07DN0D1UCW\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/score/refs/heads/main/json-ld/score-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/score/refs/heads/main/vocabulary/score-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/score/refs/heads/main/apis.yml
tags:
- Platform Engineering
- Cloud Native
- CNCF
- Workload Specification
- Kubernetes
- Docker
- Developer Experience
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/score/refs/heads/main/apis.yml
use_cases: []
---
