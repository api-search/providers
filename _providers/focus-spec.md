---
api_count: 1
apis:
- description: FOCUS defines a common normalized data schema for cloud and technology billing data. The specification is delivered as a set of normative documents and supporting artifacts (column library, requiremen
  name: FOCUS (FinOps Open Cost and Usage Specification)
  slug: focus-spec
common:
- title: ''
  type: Website
  url: https://focus.finops.org/
- title: ''
  type: Documentation
  url: https://focus.finops.org/
- title: ''
  type: GitHubRepository
  url: https://github.com/FinOps-Open-Cost-and-Usage-Spec/FOCUS_Spec
- title: ''
  type: GitHubOrganization
  url: https://github.com/FinOps-Open-Cost-and-Usage-Spec
- title: ''
  type: JSONSchema
  url: json-schema/focus-billing-record-schema.json
created: '2026-03-27'
description: FOCUS, the FinOps Open Cost and Usage Specification, is an open standard maintained under the FinOps Foundation that normalizes cost and usage data across cloud, SaaS, data center, and other technology vendors. FOCUS defines a common data schema, a controlled vocabulary of column names, allowed values, and pricing attributes so that practitioners can apply a consistent set of FinOps practices regardless of which provider generated the underlying billing dataset. FOCUS is purely a data specification rather than a REST API; conforming providers expose exports of their billing data in the FOCUS format, and tooling consumes those exports against the published column library, data model, and validator.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: FOCUS (FinOps Open Cost and Usage Specification)
skills: []
slug: focus-spec
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: focus-spec\nname: FOCUS (FinOps Open Cost and Usage Specification)\ndescription: >-\n  FOCUS, the FinOps Open Cost and Usage Specification, is an open standard\n  maintained under the FinOps Foundation that normalizes cost and usage\n  data across cloud, SaaS, data center, and other technology vendors.\n  FOCUS defines a common data schema, a controlled vocabulary of column\n  names, allowed values, and pricing attributes so that practitioners can\n  apply a consistent set of FinOps practices regardless of which provider\n  generated the underlying billing dataset. FOCUS is purely a data\n  specification rather than a REST API; conforming providers expose\n  exports of their billing data in the FOCUS format, and tooling consumes\n  those exports against the published column library, data model, and\n  validator.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/focus-spec/refs/heads/main/apis.yml\n\
  created: '2026-03-27'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Billing\n  - Cost and Usage\n  - FinOps\n  - Open Standard\n  - Specification\napis:\n  - aid: focus-spec:focus-spec\n    name: FOCUS (FinOps Open Cost and Usage Specification)\n    description: >-\n      FOCUS defines a common normalized data schema for cloud and\n      technology billing data. The specification is delivered as a set of\n      normative documents and supporting artifacts (column library,\n      requirements model, validator, Excel/CSV samples) rather than as a\n      REST API. This entry tracks the specification itself and links to\n      a JSON Schema representation of a single FOCUS-conformant billing\n      record so that data consumers and integrators can validate\n      individual rows produced by FOCUS-aligned exports.\n    humanURL: https://focus.finops.org/\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - FinOps\n   \
  \   - Specification\n      - Cost and Usage\n      - Billing\n    properties:\n      - type: Documentation\n        url: https://focus.finops.org/\n      - type: Getting Started\n        url: https://focus.finops.org/focus-getting-started/\n      - type: GitHubRepository\n        url: https://github.com/FinOps-Open-Cost-and-Usage-Spec/FOCUS_Spec\n      - type: GitHubOrganization\n        url: https://github.com/FinOps-Open-Cost-and-Usage-Spec\n      - type: JSONSchema\n        url: json-schema/focus-billing-record-schema.json\ncommon:\n  - type: Website\n    url: https://focus.finops.org/\n  - type: Documentation\n    url: https://focus.finops.org/\n  - type: GitHubRepository\n    url: https://github.com/FinOps-Open-Cost-and-Usage-Spec/FOCUS_Spec\n  - type: GitHubOrganization\n    url: https://github.com/FinOps-Open-Cost-and-Usage-Spec\n  - type: JSONSchema\n    url: json-schema/focus-billing-record-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/focus-spec/refs/heads/main/apis.yml
tags:
- Billing
- Cost and Usage
- FinOps
- Open Standard
- Specification
url: https://raw.githubusercontent.com/api-evangelist/focus-spec/refs/heads/main/apis.yml
use_cases: []
---
