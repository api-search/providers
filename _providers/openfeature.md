---
api_count: 1
api_specs:
- filename: openfeature-openapi.yaml
  format: yaml
  label: OpenFeature Evaluation API
  slug: openfeature-spec
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openfeature/refs/heads/main/openapi/openfeature-openapi.yaml
apis:
- description: The OpenFeature specification defines a standard API for feature flag evaluation across languages. It includes the Evaluation API for resolving flag values with context, the Provider API for connectin
  name: OpenFeature Evaluation API
  slug: openfeature-spec
common:
- title: ''
  type: Documentation
  url: https://openfeature.dev/docs/
- title: ''
  type: GitHubOrg
  url: https://github.com/open-feature
created: '2026-03-16'
description: OpenFeature is a CNCF incubating open specification for feature flag management. It provides a vendor-agnostic API for evaluating feature flags, enabling developers to use a consistent interface regardless of the underlying feature flag provider. OpenFeature offers SDKs in multiple languages including Go, Java, JavaScript, Python, PHP, and .NET with a provider-based architecture.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: OpenFeature
skills: []
slug: openfeature
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: openfeature\nname: OpenFeature\ndescription: >-\n  OpenFeature is a CNCF incubating open specification for feature flag\n  management. It provides a vendor-agnostic API for evaluating feature\n  flags, enabling developers to use a consistent interface regardless of\n  the underlying feature flag provider. OpenFeature offers SDKs in multiple\n  languages including Go, Java, JavaScript, Python, PHP, and .NET with a\n  provider-based architecture.\nurl: https://openfeature.dev\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Feature Flags\n  - Feature Management\n  - Incubating\n  - SDKs\n  - Specification\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: openfeature:openfeature-spec\n    name: OpenFeature Evaluation API\n    description: >-\n      The OpenFeature specification defines a standard API for feature flag\n      evaluation across languages.\
  \ It includes the Evaluation API for resolving\n      flag values with context, the Provider API for connecting to feature\n      flag backends, the Hook API for intercepting evaluation lifecycle events,\n      and the Event API for reacting to flag configuration changes. Providers\n      can be implemented for any feature flag service.\n    humanURL: https://openfeature.dev/docs/reference/intro\n    properties:\n      - type: Documentation\n        url: https://openfeature.dev/docs/reference/intro\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/openfeature/refs/heads/main/openapi/openfeature-openapi.yaml\n    tags:\n      - Evaluation API\n      - Feature Flags\n      - Specification\ncommon:\n  - type: Documentation\n    name: OpenFeature Documentation\n    description: Official OpenFeature documentation.\n    url: https://openfeature.dev/docs/\n  - type: GitHubOrg\n    name: OpenFeature GitHub\n    description: Source code and SDKs.\n    url: https://github.com/open-feature\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/openfeature/refs/heads/main/apis.yml
tags:
- Cloud Native
- Feature Flags
- Feature Management
- Incubating
- SDKs
- Specification
url: https://openfeature.dev
use_cases: []
---
