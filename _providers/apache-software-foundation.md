---
api_count: 2
apis:
- description: The Apache Software Foundation Projects API provides read-only access to JSON data about ASF projects, committees, releases, and podlings. The data is served as static JSON files from projects.apache.
  name: Apache Software Foundation Projects API
  slug: projects-api
- description: The Apache Whimsy Public Data API provides access to publicly available information about the Apache Software Foundation's organizational structure. It exposes data about committees, members, committe
  name: Apache Software Foundation Whimsy Public Data API
  slug: whimsy-api
common:
- title: ''
  type: Portal
  url: https://www.apache.org/
- title: ''
  type: Blog
  url: https://blogs.apache.org/
- title: ''
  type: Documentation
  url: https://www.apache.org/foundation/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: SpectralRules
  url: rules/apache-software-foundation-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-software-foundation-vocabulary.yaml
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
created: '2025-01-01'
description: APIs for the Apache Software Foundation (ASF), a nonprofit organization that supports the development of open-source software projects under the Apache License, providing governance, legal protection, and infrastructure for over 350 projects. The ASF exposes public APIs for project discovery, committee governance data, member information, and organizational structure through its Projects API and Whimsy Public Data API.
features:
- description: Comprehensive directory of all 350+ ASF top-level projects with metadata.
  name: Project Directory
- description: Project Management Committee membership, chair, and governance information.
  name: Committee Data
- description: Apache Incubator podling status, mentors, and graduation tracking.
  name: Podling Tracking
- description: Release version and date history for all ASF projects.
  name: Release History
- description: Public member, committer, and ICLA data from the ASF Whimsy system.
  name: Whimsy Member Data
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: All ASF project repositories hosted under the apache GitHub organization.
  name: Apache GitHub Organization
- description: Issue tracking at issues.apache.org for all ASF project bug reports and features.
  name: ASF JIRA
- description: Wiki documentation at cwiki.apache.org for ASF project and foundation docs.
  name: Apache Confluence
jsonld:
- class_count: 5
  name: Apache Software Foundation Asf Context
  property_count: 22
  slug: apache-software-foundation-asf-context
layout: provider
modified: '2026-04-19'
name: Apache Software Foundation
rules:
- name: Apache Software Foundation API Rules
  rule_count: 18
  severity_counts:
    error: 8
    hint: 0
    info: 3
    warn: 7
  slug: apache-software-foundation-spectral-rules
skills: []
slug: apache-software-foundation
solutions: []
source_yaml: "aid: apache-software-foundation\nname: Apache Software Foundation\ndescription: >-\n  APIs for the Apache Software Foundation (ASF), a nonprofit organization that supports the\n  development of open-source software projects under the Apache License, providing governance,\n  legal protection, and infrastructure for over 350 projects. The ASF exposes public APIs for\n  project discovery, committee governance data, member information, and organizational structure\n  through its Projects API and Whimsy Public Data API.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - ASF\n  - Open Source\n  - Governance\n  - Projects\n  - Apache\ncreated: '2025-01-01'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-software-foundation/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-software-foundation:projects-api\n    name:\
  \ Apache Software Foundation Projects API\n    description: >-\n      The Apache Software Foundation Projects API provides read-only access to JSON data about\n      ASF projects, committees, releases, and podlings. The data is served as static JSON files\n      from projects.apache.org and includes comprehensive information about the foundation's\n      structure, project metadata, committee membership, release histories, and incubating podlings.\n    humanURL: https://projects.apache.org/\n    tags:\n      - Committees\n      - Open Source\n      - Projects\n      - Releases\n      - Podlings\n    properties:\n      - type: Documentation\n        url: https://projects.apache.org/\n      - type: OpenAPI\n        url: openapi/apache-software-foundation-projects-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/apache-software-foundation-project-schema.json\n      - type: JSONSchema\n        url: json-schema/apache-software-foundation-committee-schema.json\n      - type:\
  \ JSONSchema\n        url: json-schema/apache-software-foundation-podling-schema.json\n\n  - aid: apache-software-foundation:whimsy-api\n    name: Apache Software Foundation Whimsy Public Data API\n    description: >-\n      The Apache Whimsy Public Data API provides access to publicly available information about\n      the Apache Software Foundation's organizational structure. It exposes data about committees,\n      members, committers, and ICLA (Individual Contributor License Agreement) information. The\n      data is maintained by the ASF Secretary and Whimsy tooling.\n    humanURL: https://whimsy.apache.org/public/\n    tags:\n      - Governance\n      - Members\n      - Open Source\n      - Committees\n    properties:\n      - type: Documentation\n        url: https://whimsy.apache.org/public/\n      - type: OpenAPI\n        url: openapi/apache-software-foundation-whimsy-api-openapi.yml\n\ncommon:\n  - type: Portal\n    url: https://www.apache.org/\n  - type: Blog\n    url: https://blogs.apache.org/\n\
  \  - type: Documentation\n    url: https://www.apache.org/foundation/\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: SpectralRules\n    url: rules/apache-software-foundation-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-software-foundation-vocabulary.yaml\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: Features\n    data:\n      - name: Project Directory\n        description: Comprehensive directory of all 350+ ASF top-level projects with metadata.\n      - name: Committee Data\n        description: Project Management Committee membership, chair, and governance information.\n      - name: Podling Tracking\n        description: Apache Incubator podling status, mentors, and graduation tracking.\n      - name: Release History\n        description: Release version and date history for all ASF projects.\n      - name: Whimsy Member Data\n        description: Public member, committer, and ICLA data from the\
  \ ASF Whimsy system.\n  - type: UseCases\n    data:\n      - name: Apache Project Discovery\n        description: Discover and explore all Apache Software Foundation projects programmatically.\n      - name: Governance Transparency\n        description: Access committee membership and governance data for ASF organizational research.\n      - name: Release Monitoring\n        description: Track release histories and versions across all ASF projects.\n      - name: Incubator Tracking\n        description: Monitor Apache Incubator podlings and their progression to top-level projects.\n  - type: Integrations\n    data:\n      - name: Apache GitHub Organization\n        description: All ASF project repositories hosted under the apache GitHub organization.\n      - name: ASF JIRA\n        description: Issue tracking at issues.apache.org for all ASF project bug reports and features.\n      - name: Apache Confluence\n        description: Wiki documentation at cwiki.apache.org for ASF project and\
  \ foundation docs.\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-software-foundation/refs/heads/main/apis.yml
tags:
- ASF
- Open Source
- Governance
- Projects
- Apache
url: https://raw.githubusercontent.com/api-evangelist/apache-software-foundation/refs/heads/main/apis.yml
use_cases:
- description: Discover and explore all Apache Software Foundation projects programmatically.
  name: Apache Project Discovery
- description: Access committee membership and governance data for ASF organizational research.
  name: Governance Transparency
- description: Track release histories and versions across all ASF projects.
  name: Release Monitoring
- description: Monitor Apache Incubator podlings and their progression to top-level projects.
  name: Incubator Tracking
---
