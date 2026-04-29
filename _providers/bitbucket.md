---
api_count: 1
api_specs:
- filename: bitbucket-cloud-rest-api-openapi.json
  format: json
  label: Bitbucket Cloud REST API
  slug: bitbucket-cloud-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bitbucket/refs/heads/main/openapi/bitbucket-cloud-rest-api-openapi.json
apis:
- description: The REST API for Bitbucket Cloud allows you to build apps using any language, exposing operations on repositories, pull requests, commits, pipelines, workspaces, projects, webhooks, issues, and users.
  name: Bitbucket Cloud REST API
  slug: bitbucket-cloud-rest-api
capabilities:
- description: Workflow capability for code collaboration using Bitbucket - managing repositories, pull requests, code reviews, and CI/CD pipelines. Used by developers and DevOps engineers.
  name: Bitbucket Code Collaboration
  slug: code-collaboration
common:
- title: ''
  type: Portal
  url: https://developer.atlassian.com/
- title: ''
  type: StatusPage
  url: https://status.atlassian.com/
- title: ''
  type: TermsOfService
  url: https://www.atlassian.com/legal/cloud-terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.atlassian.com/legal/privacy-policy
- title: ''
  type: SignUp
  url: https://bitbucket.org/account/signup/
- title: ''
  type: Blog
  url: https://bitbucket.org/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/atlassian
- title: ''
  type: Support
  url: https://support.atlassian.com/bitbucket-cloud/
- title: ''
  type: JSON-LD
  url: json-ld/bitbucket-cloud-rest-api-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/bitbucket-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/code-collaboration.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/bitbucket-vocabulary.yaml
created: '2024-01-01'
description: Bitbucket is a Git-based source code repository hosting service owned by Atlassian offering both commercial plans and free accounts with unlimited private repositories, along with CI/CD pipelines, code reviews via pull requests, and code collaboration tools for development teams.
features:
- description: Host unlimited private and public Git repositories with fine-grained access controls.
  name: Git Repository Hosting
- description: Code review workflows with inline comments, approvals, and merge checks.
  name: Pull Requests
- description: Integrated CI/CD service for building, testing, and deploying code.
  name: Bitbucket Pipelines
- description: Enforce branch restrictions and merge requirements.
  name: Branch Permissions
- description: Receive real-time notifications about repository events.
  name: Webhooks
- description: Built-in issue tracker for managing bugs and feature requests.
  name: Issue Tracking
- description: Track deployments across multiple environments.
  name: Deployment Environments
- description: Search across repositories, code, and pull requests.
  name: Code Search
- description: Share code snippets with version history.
  name: Snippets
image: /assets/icons/bitbucket.png
integrations:
- description: Deep integration with Jira for issue tracking and project management.
  name: Jira Software
- description: Connect Bitbucket with Trello for visual project management.
  name: Trello
- description: Receive Bitbucket notifications in Slack channels.
  name: Slack
- description: Link documentation in Confluence with code in Bitbucket.
  name: Confluence
- description: Deploy to AWS services using Bitbucket Pipelines.
  name: AWS
- description: Deploy to Azure services using Bitbucket Pipelines.
  name: Azure
- description: Deploy to Google Cloud using Bitbucket Pipelines.
  name: Google Cloud
- description: Build and push Docker images using Bitbucket Pipelines.
  name: Docker
jsonld:
- class_count: 4
  name: Bitbucket Cloud Rest Api Context
  property_count: 23
  slug: bitbucket-cloud-rest-api-context
layout: provider
modified: '2026-04-18'
name: Bitbucket
rules:
- name: Bitbucket API Rules
  rule_count: 19
  severity_counts:
    error: 8
    hint: 0
    info: 2
    warn: 9
  slug: bitbucket-spectral-rules
skills: []
slug: bitbucket
solutions: []
source_filename: apis.yml
source_yaml: "aid: bitbucket\nname: Bitbucket\ndescription: >-\n  Bitbucket is a Git-based source code repository hosting service owned by\n  Atlassian offering both commercial plans and free accounts with unlimited\n  private repositories, along with CI/CD pipelines, code reviews via pull\n  requests, and code collaboration tools for development teams.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Atlassian\n  - CI/CD\n  - Code Collaboration\n  - Code Review\n  - DevOps\n  - Git\n  - Pull Requests\n  - Repository Hosting\n  - Version Control\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bitbucket/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - aid: bitbucket:bitbucket-cloud-rest-api\n    name: Bitbucket Cloud REST API\n    description: >-\n      The REST API for Bitbucket Cloud allows you to build apps using any\n      language, exposing operations\
  \ on repositories, pull requests, commits,\n      pipelines, workspaces, projects, webhooks, issues, and users.\n    humanURL: https://developer.atlassian.com/bitbucket/api/2/reference/\n    baseURL: https://api.bitbucket.org/2.0\n    tags:\n      - Commits\n      - Pipelines\n      - Pull Requests\n      - Repositories\n      - REST\n      - Webhooks\n      - Workspaces\n    properties:\n      - type: Documentation\n        url: https://developer.atlassian.com/bitbucket/api/2/reference/\n      - type: Authentication\n        url: https://developer.atlassian.com/cloud/bitbucket/rest/intro/#authentication\n      - type: OpenAPI\n        url: openapi/bitbucket-cloud-rest-api-openapi.json\n      - type: JSONSchema\n        url: json-schema/bitbucket-cloud-rest-api-repository-schema.json\n      - type: JSONSchema\n        url: json-schema/bitbucket-cloud-rest-api-pullrequest-schema.json\n      - type: JSONSchema\n        url: json-schema/bitbucket-cloud-rest-api-pipeline-schema.json\n    \
  \  - type: JSONSchema\n        url: json-schema/bitbucket-cloud-rest-api-commit-schema.json\n      - type: JSONStructure\n        url: json-structure/bitbucket-cloud-rest-api-repository-structure.json\n      - type: JSONStructure\n        url: json-structure/bitbucket-cloud-rest-api-pullrequest-structure.json\n      - type: JSONStructure\n        url: json-structure/bitbucket-cloud-rest-api-pipeline-structure.json\n      - type: JSONStructure\n        url: json-structure/bitbucket-cloud-rest-api-commit-structure.json\n      - type: Example\n        url: examples/bitbucket-cloud-rest-api-repository-example.json\n      - type: Example\n        url: examples/bitbucket-cloud-rest-api-pullrequest-example.json\n      - type: Example\n        url: examples/bitbucket-cloud-rest-api-pipeline-example.json\n      - type: Example\n        url: examples/bitbucket-cloud-rest-api-commit-example.json\ncommon:\n  - type: Portal\n    url: https://developer.atlassian.com/\n  - type: StatusPage\n    url:\
  \ https://status.atlassian.com/\n  - type: TermsOfService\n    url: https://www.atlassian.com/legal/cloud-terms-of-service\n  - type: PrivacyPolicy\n    url: https://www.atlassian.com/legal/privacy-policy\n  - type: SignUp\n    url: https://bitbucket.org/account/signup/\n  - type: Blog\n    url: https://bitbucket.org/blog/\n  - type: GitHubOrganization\n    url: https://github.com/atlassian\n  - type: Support\n    url: https://support.atlassian.com/bitbucket-cloud/\n  - type: JSON-LD\n    url: json-ld/bitbucket-cloud-rest-api-context.jsonld\n  - type: SpectralRules\n    url: rules/bitbucket-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/code-collaboration.yaml\n  - type: Vocabulary\n    url: vocabulary/bitbucket-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Git Repository Hosting\n        description: Host unlimited private and public Git repositories with fine-grained access controls.\n      - name: Pull Requests\n        description: Code review\
  \ workflows with inline comments, approvals, and merge checks.\n      - name: Bitbucket Pipelines\n        description: Integrated CI/CD service for building, testing, and deploying code.\n      - name: Branch Permissions\n        description: Enforce branch restrictions and merge requirements.\n      - name: Webhooks\n        description: Receive real-time notifications about repository events.\n      - name: Issue Tracking\n        description: Built-in issue tracker for managing bugs and feature requests.\n      - name: Deployment Environments\n        description: Track deployments across multiple environments.\n      - name: Code Search\n        description: Search across repositories, code, and pull requests.\n      - name: Snippets\n        description: Share code snippets with version history.\n  - type: UseCases\n    data:\n      - name: Code Review Workflows\n        description: Enforce code quality through structured pull request reviews with required approvals.\n      - name:\
  \ CI/CD Automation\n        description: Automate build, test, and deployment pipelines triggered by code changes.\n      - name: Team Collaboration\n        description: Enable distributed development teams to collaborate on code with workspaces and projects.\n      - name: Release Management\n        description: Manage releases with deployment tracking and environment promotion.\n      - name: Security Scanning\n        description: Integrate security scanning into CI/CD pipelines for vulnerability detection.\n  - type: Integrations\n    data:\n      - name: Jira Software\n        description: Deep integration with Jira for issue tracking and project management.\n      - name: Trello\n        description: Connect Bitbucket with Trello for visual project management.\n      - name: Slack\n        description: Receive Bitbucket notifications in Slack channels.\n      - name: Confluence\n        description: Link documentation in Confluence with code in Bitbucket.\n      - name: AWS\n \
  \       description: Deploy to AWS services using Bitbucket Pipelines.\n      - name: Azure\n        description: Deploy to Azure services using Bitbucket Pipelines.\n      - name: Google Cloud\n        description: Deploy to Google Cloud using Bitbucket Pipelines.\n      - name: Docker\n        description: Build and push Docker images using Bitbucket Pipelines.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bitbucket/refs/heads/main/apis.yml
tags:
- Atlassian
- CI/CD
- Code Collaboration
- Code Review
- DevOps
- Git
- Pull Requests
- Repository Hosting
- Version Control
url: https://raw.githubusercontent.com/api-evangelist/bitbucket/refs/heads/main/apis.yml
use_cases:
- description: Enforce code quality through structured pull request reviews with required approvals.
  name: Code Review Workflows
- description: Automate build, test, and deployment pipelines triggered by code changes.
  name: CI/CD Automation
- description: Enable distributed development teams to collaborate on code with workspaces and projects.
  name: Team Collaboration
- description: Manage releases with deployment tracking and environment promotion.
  name: Release Management
- description: Integrate security scanning into CI/CD pipelines for vulnerability detection.
  name: Security Scanning
---
