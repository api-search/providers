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
