---
api_count: 1
apis:
- description: The All Contributors specification provides a standardized way to recognize contributions to open-source projects beyond just code. It includes a bot API for automating contributor management, a confi
  name: All Contributors API
  slug: authors-md-all-contributors
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/api-evangelist
- title: ''
  type: GitHubRepository
  url: https://github.com/api-evangelist/authors-md
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/authors-md/refs/heads/main/vocabulary/authors-md-vocabulary.yaml
created: '2025-01-01'
description: AUTHORS.md is a file format standard used in open-source and collaborative software projects to list the original creators, primary authors, and significant contributors of a project. Often required by open-source licenses such as GPL and Apache 2.0 to provide proper attribution, the AUTHORS.md file documents who wrote what portions of a codebase, their email addresses, and the scope of their contributions. Related standards include CONTRIBUTORS.md, All Contributors specification, and REUSE/SPDX contributor attribution frameworks.
features:
- description: Documents original creators and primary authors of a project, fulfilling attribution requirements for open-source licenses like GPL and Apache 2.0.
  name: Author Attribution
- description: Supports recognition of diverse contribution types beyond code including documentation, design, translation, testing, and community management.
  name: Contributor Types
- description: The All Contributors .all-contributorsrc configuration file provides a machine-readable JSON format for managing contributor metadata programmatically.
  name: Machine-Readable Format
- description: The All Contributors bot automates contributor recognition by responding to GitHub issue and pull request comments to update contributor tables.
  name: Bot Automation
- description: Helps projects satisfy attribution requirements in open-source licenses including GPL, LGPL, Apache 2.0, and MPL that require author documentation.
  name: License Compliance
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: All Contributors bot integrates directly with GitHub repositories, responding to issue and pull request comments to manage contributor attribution.
  name: GitHub
- description: The REUSE specification by FSFE provides structured SPDX-based attribution that complements AUTHORS.md files with machine-readable copyright headers.
  name: REUSE / SPDX
- description: GNU project guidelines specify conventions for AUTHORS files in free software projects, requiring attribution of significant code contributions.
  name: GNU Coding Standards
- description: AUTHORS.md files work alongside CONTRIBUTING.md files to document both past contributors and guidelines for future contributions.
  name: CONTRIBUTING.md
- description: AUTHORS.md attribution works in conjunction with CHANGELOG.md files to provide a complete history of a project's contributors and changes.
  name: CHANGELOG.md
jsonld:
- class_count: 3
  name: Authors Md Context
  property_count: 24
  slug: authors-md-context
layout: provider
modified: '2026-04-19'
name: AUTHORS.md
skills: []
slug: authors-md
solutions: []
source_filename: apis.yml
source_yaml: "aid: authors-md\nname: AUTHORS.md\ndescription: >-\n  AUTHORS.md is a file format standard used in open-source and collaborative\n  software projects to list the original creators, primary authors, and\n  significant contributors of a project. Often required by open-source licenses\n  such as GPL and Apache 2.0 to provide proper attribution, the AUTHORS.md file\n  documents who wrote what portions of a codebase, their email addresses, and\n  the scope of their contributions. Related standards include CONTRIBUTORS.md,\n  All Contributors specification, and REUSE/SPDX contributor attribution\n  frameworks.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Attribution\n  - Documentation\n  - Open Source\n  - Repository\n  - File Format\n  - Contributor Management\n  - License Compliance\n  - Standard\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/authors-md/refs/heads/main/apis.yml\ncreated: '2025-01-01'\n\
  modified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: authors-md-all-contributors\n    name: All Contributors API\n    description: >-\n      The All Contributors specification provides a standardized way to\n      recognize contributions to open-source projects beyond just code. It\n      includes a bot API for automating contributor management, a configuration\n      schema (.all-contributorsrc), and an emoji-based contribution type\n      taxonomy. The bot responds to GitHub comments to add contributors to the\n      project README.\n    humanURL: https://allcontributors.org\n    baseURL: https://allcontributors.org\n    tags:\n      - Contributors\n      - Attribution\n      - Open Source\n      - Bot\n      - GitHub\n    properties:\n      - type: Documentation\n        url: https://allcontributors.org/docs/en/overview\n      - type: GettingStarted\n        url: https://allcontributors.org/docs/en/bot/installation\n      - type: Specification\n        url: https://allcontributors.org/docs/en/specification\n\
  \      - type: GitHubRepository\n        url: https://github.com/all-contributors/all-contributors\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/authors-md/refs/heads/main/json-schema/all-contributors-config-schema.json\n\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/api-evangelist\n  - type: GitHubRepository\n    url: https://github.com/api-evangelist/authors-md\n  - type: Features\n    data:\n      - name: Author Attribution\n        description: >-\n          Documents original creators and primary authors of a project, fulfilling\n          attribution requirements for open-source licenses like GPL and Apache 2.0.\n      - name: Contributor Types\n        description: >-\n          Supports recognition of diverse contribution types beyond code including\n          documentation, design, translation, testing, and community management.\n      - name: Machine-Readable Format\n        description: >-\n     \
  \     The All Contributors .all-contributorsrc configuration file provides a\n          machine-readable JSON format for managing contributor metadata programmatically.\n      - name: Bot Automation\n        description: >-\n          The All Contributors bot automates contributor recognition by responding\n          to GitHub issue and pull request comments to update contributor tables.\n      - name: License Compliance\n        description: >-\n          Helps projects satisfy attribution requirements in open-source licenses\n          including GPL, LGPL, Apache 2.0, and MPL that require author documentation.\n  - type: UseCases\n    data:\n      - name: Open Source License Compliance\n        description: >-\n          Satisfying attribution requirements in GPL, Apache, and other licenses\n          that require listing authors and contributors in distributed software.\n      - name: Project Governance\n        description: >-\n          Documenting contributors for project governance\
  \ purposes, recognition,\n          and historical record-keeping of who built what portions of a codebase.\n      - name: Contributor Onboarding\n        description: >-\n          Helping new contributors understand the project's authorship history and\n          providing a clear path for getting recognized for their contributions.\n      - name: Copyright Documentation\n        description: >-\n          Maintaining accurate copyright records for legal clarity around\n          intellectual property ownership and contributor rights in collaborative projects.\n      - name: Community Recognition\n        description: >-\n          Publicly recognizing contributors in README files and project documentation\n          to build community engagement and acknowledge diverse contributions.\n  - type: Integrations\n    data:\n      - name: GitHub\n        description: >-\n          All Contributors bot integrates directly with GitHub repositories,\n          responding to issue and pull request\
  \ comments to manage contributor attribution.\n      - name: REUSE / SPDX\n        description: >-\n          The REUSE specification by FSFE provides structured SPDX-based attribution\n          that complements AUTHORS.md files with machine-readable copyright headers.\n      - name: GNU Coding Standards\n        description: >-\n          GNU project guidelines specify conventions for AUTHORS files in free\n          software projects, requiring attribution of significant code contributions.\n      - name: CONTRIBUTING.md\n        description: >-\n          AUTHORS.md files work alongside CONTRIBUTING.md files to document both\n          past contributors and guidelines for future contributions.\n      - name: CHANGELOG.md\n        description: >-\n          AUTHORS.md attribution works in conjunction with CHANGELOG.md files\n          to provide a complete history of a project's contributors and changes.\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/authors-md/refs/heads/main/vocabulary/authors-md-vocabulary.yaml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/authors-md/refs/heads/main/apis.yml
tags:
- Attribution
- Documentation
- Open Source
- Repository
- File Format
- Contributor Management
- License Compliance
- Standard
url: https://raw.githubusercontent.com/api-evangelist/authors-md/refs/heads/main/apis.yml
use_cases:
- description: Satisfying attribution requirements in GPL, Apache, and other licenses that require listing authors and contributors in distributed software.
  name: Open Source License Compliance
- description: Documenting contributors for project governance purposes, recognition, and historical record-keeping of who built what portions of a codebase.
  name: Project Governance
- description: Helping new contributors understand the project's authorship history and providing a clear path for getting recognized for their contributions.
  name: Contributor Onboarding
- description: Maintaining accurate copyright records for legal clarity around intellectual property ownership and contributor rights in collaborative projects.
  name: Copyright Documentation
- description: Publicly recognizing contributors in README files and project documentation to build community engagement and acknowledge diverse contributions.
  name: Community Recognition
---
