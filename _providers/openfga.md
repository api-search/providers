---
api_count: 1
api_specs:
- filename: openfga-openapi.json
  format: json
  label: OpenFGA Authorization API
  slug: openfga-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openfga/refs/heads/main/openapi/openfga-openapi.json
apis:
- description: The OpenFGA API provides HTTP and gRPC endpoints for fine-grained authorization. Key operations include Check for evaluating access decisions, Write for managing relationship tuples, Read for querying
  name: OpenFGA Authorization API
  slug: openfga-api
common:
- title: ''
  type: Documentation
  url: https://openfga.dev/docs/
- title: ''
  type: GitHubOrg
  url: https://github.com/openfga
created: '2026-03-16'
description: OpenFGA is a CNCF incubating high-performance authorization system implementing fine-grained access control based on the Zanzibar model. It provides a flexible relationship-based authorization engine that evaluates access decisions using a type system defined in a modeling language. OpenFGA supports authorization checks, relationship queries, and list operations through its API.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: OpenFGA
skills: []
slug: openfga
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: openfga\nname: OpenFGA\ndescription: >-\n  OpenFGA is a CNCF incubating high-performance authorization system\n  implementing fine-grained access control based on the Zanzibar model.\n  It provides a flexible relationship-based authorization engine that\n  evaluates access decisions using a type system defined in a modeling\n  language. OpenFGA supports authorization checks, relationship queries,\n  and list operations through its API.\nurl: https://openfga.dev\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Access Control\n  - Authorization\n  - Cloud Native\n  - Fine-Grained\n  - Incubating\n  - Zanzibar\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: openfga:openfga-api\n    name: OpenFGA Authorization API\n    description: >-\n      The OpenFGA API provides HTTP and gRPC endpoints for fine-grained\n      authorization. Key operations include Check for evaluating\
  \ access\n      decisions, Write for managing relationship tuples, Read for querying\n      relationships, ListObjects for finding accessible resources, and\n      Expand for debugging authorization models. The API also supports\n      store management and authorization model versioning.\n    humanURL: https://openfga.dev/docs/getting-started\n    properties:\n      - type: Documentation\n        url: https://openfga.dev/docs/getting-started\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/openfga/refs/heads/main/openapi/openfga-openapi.json\n    tags:\n      - Authorization API\n      - Fine-Grained Access\n      - Relationship Tuples\ncommon:\n  - type: Documentation\n    name: OpenFGA Documentation\n    description: Official OpenFGA documentation.\n    url: https://openfga.dev/docs/\n  - type: GitHubOrg\n    name: OpenFGA GitHub\n    description: Source code repository.\n    url: https://github.com/openfga\nmaintainers:\n  - FN: Kin Lane\n    email:\
  \ kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/openfga/refs/heads/main/apis.yml
tags:
- Access Control
- Authorization
- Cloud Native
- Fine-Grained
- Incubating
- Zanzibar
url: https://openfga.dev
use_cases: []
---
