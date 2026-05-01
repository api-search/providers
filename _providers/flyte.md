---
api_count: 1
api_specs:
- filename: flyte-admin-api-openapi.yml
  format: yaml
  label: Flyte Admin API
  slug: flyte-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/flyte/refs/heads/main/openapi/flyte-admin-api-openapi.yml
apis:
- description: The Flyte Admin API is the control-plane REST API exposed by the flyteadmin service. It is generated from the flyteidl protocol buffer definitions via gRPC-Gateway and provides JSON over HTTP access t
  name: Flyte Admin API
  slug: flyte-admin-api
common:
- title: ''
  type: Website
  url: https://flyte.org
- title: ''
  type: Documentation
  url: https://docs.flyte.org
- title: ''
  type: GitHubRepository
  url: https://github.com/flyteorg/flyte
- title: ''
  type: GitHubOrganization
  url: https://github.com/flyteorg
- title: ''
  type: Blog
  url: https://flyte.org/blog
- title: ''
  type: Community
  url: https://flyte.org/community
- title: ''
  type: Slack
  url: https://slack.flyte.org
created: '2026-03-27'
description: Flyte is a Kubernetes-native, open-source workflow orchestration platform for machine learning, data, and analytics pipelines. It provides reproducibility, type safety, strong versioning of tasks and workflows, and a multi-tenant control plane with native first-class scheduling on Kubernetes. Flyte is a Cloud Native Computing Foundation (CNCF) incubating project. Beyond the Python and Go SDKs, Flyte exposes a JSON-over-HTTP REST control-plane API (the Flyte Admin API) generated from the flyteidl protocol buffer definitions via gRPC-Gateway, which is used to register and manage projects, tasks, workflows, and launch plans, to create and inspect executions, to receive lifecycle events, and to read and write matchable attribute overrides.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Flyte
skills: []
slug: flyte
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: flyte\nname: Flyte\ndescription: >-\n  Flyte is a Kubernetes-native, open-source workflow orchestration platform\n  for machine learning, data, and analytics pipelines. It provides\n  reproducibility, type safety, strong versioning of tasks and workflows,\n  and a multi-tenant control plane with native first-class scheduling on\n  Kubernetes. Flyte is a Cloud Native Computing Foundation (CNCF) incubating\n  project. Beyond the Python and Go SDKs, Flyte exposes a JSON-over-HTTP\n  REST control-plane API (the Flyte Admin API) generated from the flyteidl\n  protocol buffer definitions via gRPC-Gateway, which is used to register\n  and manage projects, tasks, workflows, and launch plans, to create and\n  inspect executions, to receive lifecycle events, and to read and write\n  matchable attribute overrides.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/flyte/refs/heads/main/apis.yml\n\
  created: '2026-03-27'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - CNCF\n  - Data Orchestration\n  - Kubernetes\n  - Machine Learning\n  - Workflow Automation\napis:\n  - aid: flyte:flyte-admin-api\n    name: Flyte Admin API\n    description: >-\n      The Flyte Admin API is the control-plane REST API exposed by the\n      flyteadmin service. It is generated from the flyteidl protocol buffer\n      definitions via gRPC-Gateway and provides JSON over HTTP access to\n      the same operations exposed via gRPC. The API is used to register\n      and manage projects, tasks, workflows, and launch plans, to create\n      and inspect workflow, node, and task executions, to receive\n      lifecycle events, to proxy data to and from upstream object stores,\n      and to read and write matchable attribute overrides at the project,\n      domain, and workflow levels. The same REST API powers the Flyte\n      Console UI and is the primary programmatic interface for operating\n\
  \      a Flyte cluster.\n    humanURL: https://docs.flyte.org\n    baseURL: http://localhost:30080\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Workflow Orchestration\n      - Control Plane\n      - Executions\n      - Launch Plans\n      - Projects\n      - Tasks\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://docs.flyte.org\n      - type: OpenAPI\n        url: openapi/flyte-admin-api-openapi.yml\n      - type: GitHubRepository\n        url: https://github.com/flyteorg/flyte\n      - type: SourceSwagger\n        url: https://raw.githubusercontent.com/flyteorg/flyteidl/master/gen/pb-go/flyteidl/service/admin.swagger.json\ncommon:\n  - type: Website\n    url: https://flyte.org\n  - type: Documentation\n    url: https://docs.flyte.org\n  - type: GitHubRepository\n    url: https://github.com/flyteorg/flyte\n  - type: GitHubOrganization\n    url: https://github.com/flyteorg\n  - type: Blog\n\
  \    url: https://flyte.org/blog\n  - type: Community\n    url: https://flyte.org/community\n  - type: Slack\n    url: https://slack.flyte.org\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/flyte/refs/heads/main/apis.yml
tags:
- CNCF
- Data Orchestration
- Kubernetes
- Machine Learning
- Workflow Automation
url: https://raw.githubusercontent.com/api-evangelist/flyte/refs/heads/main/apis.yml
use_cases: []
---
