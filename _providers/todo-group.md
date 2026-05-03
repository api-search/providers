---
api_count: 6
apis:
- description: 'Repolinter is an open source linting tool for repositories that validates compliance with open source best practices. It checks repositories for standard files like LICENSE, README, CONTRIBUTING, and '
  name: Repolinter
  slug: repolinter
- description: A GitHub Action that runs Repolinter on repositories as part of CI/CD workflows. Validates repositories against configurable rulesets to enforce open source compliance policies. Supports outputting re
  name: Repolinter Action
  slug: repolinter-action
- description: 'An interactive landscape mapping the Open Source Program Office ecosystem, including OSPO adopter organizations and tools supporting OSPO operations. Data is maintained in landscape.yml and browsable '
  name: OSPO Landscape
  slug: ospo-landscape
- description: A comprehensive collection of 23+ practitioner guides covering all aspects of running Open Source Program Offices. Topics include creating an OSPO, setting open source strategy, measuring program succ
  name: OSPO Guides
  slug: ospo-guides
- description: The OSPOlogy program provides monthly community webinars, working group meetings, and collaborative sessions focused on OSPO practices and challenges. It serves as the primary community engagement pla
  name: OSPOlogy
  slug: ospology
- description: An open source career development framework defining roles, skills, and progression paths for OSPO professionals. Covers job functions from open source program manager to legal counsel, providing orga
  name: OSPO Career Path
  slug: ospo-career-path
common:
- title: ''
  type: Website
  url: https://todogroup.org/
- title: ''
  type: Documentation
  url: https://todogroup.org/guides/
- title: ''
  type: GitHubOrg
  url: https://github.com/todogroup
- title: ''
  type: Slack
  url: https://slack.todogroup.org/
- title: ''
  type: Newsletter
  url: https://todogroup.org/community/newsletter/
- title: ''
  type: SpectralRules
  url: rules/todo-group-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/todo-group-vocabulary.yaml
created: '2026-03-16'
description: The TODO Group is an open community of practitioners under the Linux Foundation who collaborate on best practices, tools, and guidance for running successful Open Source Program Offices (OSPOs). It provides open source tooling including Repolinter for repository linting, the OSPO Landscape mapping OSPO adopters and tools, comprehensive OSPO guides and case studies, and OSPOlogy community programs. The TODO Group serves organizations managing enterprise open source strategies across 120+ member organizations.
features:
- description: Command-line tool for linting open source repositories against configurable compliance rulesets.
  name: Repolinter CLI
- description: Programmatic Node.js API for integrating repository linting into custom workflows and tools.
  name: Repolinter JavaScript API
- description: CI/CD integration for automated repository compliance checks in GitHub workflows.
  name: Repolinter GitHub Action
- description: Interactive ecosystem map of OSPO adopter organizations and supporting tools worldwide.
  name: OSPO Landscape
- description: Comprehensive practitioner guides covering all aspects of running an Open Source Program Office.
  name: OSPO Guides
- description: Monthly community webinars and working group sessions for OSPO practitioners.
  name: OSPOlogy Webinars
- description: Structured career framework defining roles, skills, and progression paths for OSPO professionals.
  name: OSPO Career Path
- description: Curated list of tools and resources for open source program management.
  name: Awesome OSPO
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Repolinter Action integrates repository linting into GitHub CI/CD workflows.
  name: GitHub Actions
- description: TODO Group operates under the Linux Foundation governance and community infrastructure.
  name: Linux Foundation
- description: OSPO Landscape follows the CNCF landscape pattern for ecosystem visualization.
  name: CNCF Landscape
- description: Repolinter is distributed as an npm package and supports Node.js 12+ runtime.
  name: Node.js / npm
- description: Collaboration with Open Source Security Foundation on best practices for open source security and compliance.
  name: OpenSSF
layout: provider
modified: '2026-05-03'
name: TODO Group
rules:
- name: TODO Group API Rules
  rule_count: 29
  severity_counts:
    error: 8
    hint: 0
    info: 5
    warn: 16
  slug: todo-group-spectral-rules
skills: []
slug: todo-group
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: todo-group\nname: TODO Group\ndescription: >-\n  The TODO Group is an open community of practitioners under the Linux Foundation\n  who collaborate on best practices, tools, and guidance for running successful\n  Open Source Program Offices (OSPOs). It provides open source tooling including\n  Repolinter for repository linting, the OSPO Landscape mapping OSPO adopters\n  and tools, comprehensive OSPO guides and case studies, and OSPOlogy community\n  programs. The TODO Group serves organizations managing enterprise open source\n  strategies across 120+ member organizations.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Community\n  - Linux Foundation\n  - Open Source\n  - OSPO\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/todo-group/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: todo-group:repolinter\n\
  \    name: Repolinter\n    description: >-\n      Repolinter is an open source linting tool for repositories that validates\n      compliance with open source best practices. It checks repositories for\n      standard files like LICENSE, README, CONTRIBUTING, and CODE-OF-CONDUCT,\n      and supports configurable rulesets. Available as a CLI tool\n      (repolinter lint) and a JavaScript API for programmatic integration.\n      Installable via npm as the repolinter package.\n    humanURL: https://github.com/todogroup/repolinter\n    tags:\n      - Linting\n      - Open Source\n      - Repository\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://github.com/todogroup/repolinter\n      - type: GitHubRepository\n        url: https://github.com/todogroup/repolinter\n      - type: NpmPackage\n        url: https://www.npmjs.com/package/repolinter\n\n  - aid: todo-group:repolinter-action\n    name: Repolinter Action\n    description: >-\n      A GitHub Action\
  \ that runs Repolinter on repositories as part of CI/CD\n      workflows. Validates repositories against configurable rulesets to enforce\n      open source compliance policies. Supports outputting results as exit codes\n      for PR status checks or creating GitHub issues for non-intrusive\n      notifications. Originally created by New Relic, maintained by TODO Group.\n    humanURL: https://github.com/todogroup/repolinter-action\n    tags:\n      - GitHub Actions\n      - Linting\n      - CI/CD\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://github.com/todogroup/repolinter-action\n      - type: GitHubRepository\n        url: https://github.com/todogroup/repolinter-action\n      - type: GitHubMarketplace\n        url: https://github.com/marketplace/actions/repolinter-action\n\n  - aid: todo-group:ospo-landscape\n    name: OSPO Landscape\n    description: >-\n      An interactive landscape mapping the Open Source Program Office ecosystem,\n     \
  \ including OSPO adopter organizations and tools supporting OSPO operations.\n      Data is maintained in landscape.yml and browsable at landscape.todogroup.org.\n      Modeled after the CNCF landscape approach, covering companies, governments,\n      academic institutions, and supporting tooling.\n    humanURL: https://landscape.todogroup.org/\n    tags:\n      - Landscape\n      - OSPO\n      - Ecosystem\n      - Data\n    properties:\n      - type: Documentation\n        url: https://landscape.todogroup.org/\n      - type: GitHubRepository\n        url: https://github.com/todogroup/ospolandscape\n      - type: Website\n        url: https://landscape.todogroup.org/\n\n  - aid: todo-group:ospo-guides\n    name: OSPO Guides\n    description: >-\n      A comprehensive collection of 23+ practitioner guides covering all aspects\n      of running Open Source Program Offices. Topics include creating an OSPO,\n      setting open source strategy, measuring program success, managing career\n \
  \     development, recruiting open source developers, legal compliance, and\n      community engagement. All guides are open source and community-contributed.\n    humanURL: https://todogroup.org/guides/\n    tags:\n      - Guides\n      - OSPO\n      - Best Practices\n      - Documentation\n    properties:\n      - type: Documentation\n        url: https://todogroup.org/guides/\n      - type: GitHubRepository\n        url: https://github.com/todogroup/guides\n\n  - aid: todo-group:ospology\n    name: OSPOlogy\n    description: >-\n      The OSPOlogy program provides monthly community webinars, working group\n      meetings, and collaborative sessions focused on OSPO practices and\n      challenges. It serves as the primary community engagement platform for\n      TODO Group members and OSPO practitioners worldwide, covering topics\n      from OSPO maturity models to specific industry challenges.\n    humanURL: https://community.linuxfoundation.org/todo-group-ospology/\n    tags:\n   \
  \   - Community\n      - Webinars\n      - OSPO\n      - Education\n    properties:\n      - type: Documentation\n        url: https://github.com/todogroup/ospology\n      - type: GitHubRepository\n        url: https://github.com/todogroup/ospology\n      - type: Website\n        url: https://community.linuxfoundation.org/todo-group-ospology/\n\n  - aid: todo-group:ospo-career-path\n    name: OSPO Career Path\n    description: >-\n      An open source career development framework defining roles, skills, and\n      progression paths for OSPO professionals. Covers job functions from\n      open source program manager to legal counsel, providing organizations\n      with a structured approach to building and growing OSPO teams with\n      defined competencies and seniority levels.\n    humanURL: https://github.com/todogroup/ospo-career-path\n    tags:\n      - Career Development\n      - OSPO\n      - Human Resources\n      - Skills Framework\n    properties:\n      - type: Documentation\n\
  \        url: https://github.com/todogroup/ospo-career-path\n      - type: GitHubRepository\n        url: https://github.com/todogroup/ospo-career-path\n\ncommon:\n  - type: Website\n    url: https://todogroup.org/\n  - type: Documentation\n    url: https://todogroup.org/guides/\n  - type: GitHubOrg\n    url: https://github.com/todogroup\n  - type: Slack\n    url: https://slack.todogroup.org/\n  - type: Newsletter\n    url: https://todogroup.org/community/newsletter/\n  - type: SpectralRules\n    url: rules/todo-group-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/todo-group-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Repolinter CLI\n        description: Command-line tool for linting open source repositories against configurable compliance rulesets.\n      - name: Repolinter JavaScript API\n        description: Programmatic Node.js API for integrating repository linting into custom workflows and tools.\n      - name: Repolinter GitHub Action\n        description:\
  \ CI/CD integration for automated repository compliance checks in GitHub workflows.\n      - name: OSPO Landscape\n        description: Interactive ecosystem map of OSPO adopter organizations and supporting tools worldwide.\n      - name: OSPO Guides\n        description: Comprehensive practitioner guides covering all aspects of running an Open Source Program Office.\n      - name: OSPOlogy Webinars\n        description: Monthly community webinars and working group sessions for OSPO practitioners.\n      - name: OSPO Career Path\n        description: Structured career framework defining roles, skills, and progression paths for OSPO professionals.\n      - name: Awesome OSPO\n        description: Curated list of tools and resources for open source program management.\n  - type: UseCases\n    data:\n      - name: Repository Compliance Automation\n        description: Use Repolinter and Repolinter Action to automate checks that all repos have required open source files and follow organizational\
  \ policies.\n      - name: OSPO Program Launch\n        description: Use TODO Group guides and case studies to establish and launch a new Open Source Program Office within an organization.\n      - name: OSPO Ecosystem Mapping\n        description: Reference the OSPO Landscape to discover tools, peer organizations, and adopters in the OSPO ecosystem.\n      - name: Developer Career Development\n        description: Apply the OSPO Career Path framework to define roles and progression for open source professionals.\n      - name: Open Source Strategy Development\n        description: Leverage TODO Group best practice guides to define and implement an enterprise open source strategy.\n      - name: Community Building\n        description: Participate in OSPOlogy webinars and TODO Group working groups to learn from and contribute to the OSPO community.\n  - type: Integrations\n    data:\n      - name: GitHub Actions\n        description: Repolinter Action integrates repository linting into\
  \ GitHub CI/CD workflows.\n      - name: Linux Foundation\n        description: TODO Group operates under the Linux Foundation governance and community infrastructure.\n      - name: CNCF Landscape\n        description: OSPO Landscape follows the CNCF landscape pattern for ecosystem visualization.\n      - name: Node.js / npm\n        description: Repolinter is distributed as an npm package and supports Node.js 12+ runtime.\n      - name: OpenSSF\n        description: Collaboration with Open Source Security Foundation on best practices for open source security and compliance.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/todo-group/refs/heads/main/apis.yml
tags:
- Community
- Linux Foundation
- Open Source
- OSPO
url: https://raw.githubusercontent.com/api-evangelist/todo-group/refs/heads/main/apis.yml
use_cases:
- description: Use Repolinter and Repolinter Action to automate checks that all repos have required open source files and follow organizational policies.
  name: Repository Compliance Automation
- description: Use TODO Group guides and case studies to establish and launch a new Open Source Program Office within an organization.
  name: OSPO Program Launch
- description: Reference the OSPO Landscape to discover tools, peer organizations, and adopters in the OSPO ecosystem.
  name: OSPO Ecosystem Mapping
- description: Apply the OSPO Career Path framework to define roles and progression for open source professionals.
  name: Developer Career Development
- description: Leverage TODO Group best practice guides to define and implement an enterprise open source strategy.
  name: Open Source Strategy Development
- description: Participate in OSPOlogy webinars and TODO Group working groups to learn from and contribute to the OSPO community.
  name: Community Building
---
