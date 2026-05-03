---
api_count: 5
api_specs:
- filename: radius-applications-core-openapi.json
  format: json
  label: Radius Applications.Core API
  slug: applications-core
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/radius/refs/heads/main/openapi/radius-applications-core-openapi.json
- filename: radius-applications-dapr-openapi.json
  format: json
  label: Radius Applications.Dapr API
  slug: applications-dapr
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/radius/refs/heads/main/openapi/radius-applications-dapr-openapi.json
- filename: radius-applications-datastores-openapi.json
  format: json
  label: Radius Applications.Datastores API
  slug: applications-datastores
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/radius/refs/heads/main/openapi/radius-applications-datastores-openapi.json
- filename: radius-applications-messaging-openapi.json
  format: json
  label: Radius Applications.Messaging API
  slug: applications-messaging
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/radius/refs/heads/main/openapi/radius-applications-messaging-openapi.json
- filename: radius-ucp-openapi.json
  format: json
  label: Radius Universal Control Plane (UCP) API
  slug: ucp
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/radius/refs/heads/main/openapi/radius-ucp-openapi.json
apis:
- description: REST APIs for Applications.Core, providing management of applications, containers, environments, gateways, secret stores, volumes, and extenders within the Radius platform.
  name: Radius Applications.Core API
  slug: applications-core
- description: REST APIs for Applications.Dapr, providing management of Dapr-related building block resources for Radius applications.
  name: Radius Applications.Dapr API
  slug: applications-dapr
- description: REST APIs for Applications.Datastores, providing management of database resources such as Redis, MongoDB, and SQL data stores within Radius.
  name: Radius Applications.Datastores API
  slug: applications-datastores
- description: REST APIs for Applications.Messaging, providing management of messaging service resources within the Radius application platform.
  name: Radius Applications.Messaging API
  slug: applications-messaging
- description: REST APIs for the Radius Universal Control Plane (UCP), the multi-cloud, multi-platform control plane that powers Radius resource management across providers.
  name: Radius Universal Control Plane (UCP) API
  slug: ucp
common:
- title: ''
  type: Documentation
  url: https://docs.radapp.io/
- title: ''
  type: GettingStarted
  url: https://docs.radapp.io/getting-started/
- title: ''
  type: SourceCode
  url: https://github.com/radius-project/radius
- title: ''
  type: SignUp
  url: https://docs.radapp.io/installation/
created: '2025-01-01'
description: Application platform for cloud-native applications that enables developers to define, deploy, and manage applications across multiple clouds and on-premises environments using a unified model.
features: []
image: ''
integrations: []
layout: provider
modified: '2026-04-28'
name: Radius
skills: []
slug: radius
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: radius\nname: Radius\ndescription: Application platform for cloud-native applications that enables developers to define, deploy, and manage applications across multiple clouds and on-premises environments using a unified model.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/radius/refs/heads/main/apis.yml\ntags:\n  - Application Platform\n  - Cloud Native\n  - Infrastructure\n  - Multi Cloud\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: radius:applications-core\n    name: Radius Applications.Core API\n    description: REST APIs for Applications.Core, providing management of applications, containers, environments, gateways, secret stores, volumes, and extenders within the Radius platform.\n    humanURL: https://docs.radapp.io/reference/api/applications.core/\n    baseURL: https://management.azure.com\n    tags:\n      - Applications\n      - Containers\n      - Environments\n      - Gateways\n      - Secret\
  \ Stores\n      - Volumes\n    properties:\n      - type: Documentation\n        url: https://docs.radapp.io/reference/api/applications.core/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/radius/refs/heads/main/openapi/radius-applications-core-openapi.json\n  - aid: radius:applications-dapr\n    name: Radius Applications.Dapr API\n    description: REST APIs for Applications.Dapr, providing management of Dapr-related building block resources for Radius applications.\n    humanURL: https://docs.radapp.io/reference/api/applications.dapr/\n    baseURL: https://management.azure.com\n    tags:\n      - Dapr\n      - Building Blocks\n    properties:\n      - type: Documentation\n        url: https://docs.radapp.io/reference/api/applications.dapr/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/radius/refs/heads/main/openapi/radius-applications-dapr-openapi.json\n  - aid: radius:applications-datastores\n    name: Radius\
  \ Applications.Datastores API\n    description: REST APIs for Applications.Datastores, providing management of database resources such as Redis, MongoDB, and SQL data stores within Radius.\n    humanURL: https://docs.radapp.io/reference/api/applications.datastores/\n    baseURL: https://management.azure.com\n    tags:\n      - Datastores\n      - Databases\n      - Redis\n      - MongoDB\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://docs.radapp.io/reference/api/applications.datastores/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/radius/refs/heads/main/openapi/radius-applications-datastores-openapi.json\n  - aid: radius:applications-messaging\n    name: Radius Applications.Messaging API\n    description: REST APIs for Applications.Messaging, providing management of messaging service resources within the Radius application platform.\n    humanURL: https://docs.radapp.io/reference/api/applications.messaging/\n  \
  \  baseURL: https://management.azure.com\n    tags:\n      - Messaging\n      - Queues\n    properties:\n      - type: Documentation\n        url: https://docs.radapp.io/reference/api/applications.messaging/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/radius/refs/heads/main/openapi/radius-applications-messaging-openapi.json\n  - aid: radius:ucp\n    name: Radius Universal Control Plane (UCP) API\n    description: REST APIs for the Radius Universal Control Plane (UCP), the multi-cloud, multi-platform control plane that powers Radius resource management across providers.\n    humanURL: https://docs.radapp.io/reference/api/ucp/\n    baseURL: https://management.azure.com\n    tags:\n      - Control Plane\n      - UCP\n      - Multi Cloud\n    properties:\n      - type: Documentation\n        url: https://docs.radapp.io/reference/api/ucp/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/radius/refs/heads/main/openapi/radius-ucp-openapi.json\n\
  common:\n  - type: Documentation\n    url: https://docs.radapp.io/\n  - type: GettingStarted\n    url: https://docs.radapp.io/getting-started/\n  - type: SourceCode\n    url: https://github.com/radius-project/radius\n  - type: SignUp\n    url: https://docs.radapp.io/installation/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/radius/refs/heads/main/apis.yml
tags:
- Application Platform
- Cloud Native
- Infrastructure
- Multi Cloud
url: https://raw.githubusercontent.com/api-evangelist/radius/refs/heads/main/apis.yml
use_cases: []
---
