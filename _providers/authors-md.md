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
