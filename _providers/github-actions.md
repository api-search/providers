---
api_count: 1
api_specs:
- filename: github-actions-openapi.yml
  format: yaml
  label: GitHub Actions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/github-actions/refs/heads/main/openapi/github-actions-openapi.yml
apis:
- description: REST API for managing GitHub Actions workflows, runs, artifacts, and secrets.
  name: GitHub Actions API
  slug: ''
capabilities:
- description: Unified capability for GitHub Actions CI/CD automation combining workflow management, run monitoring, artifact handling, secrets/variables management, and runner administration. Used by DevOps enginee
  name: GitHub Actions CI/CD Automation
  slug: ci-cd-automation
common:
- title: ''
  type: TermsOfService
  url: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement
- title: ''
  type: RateLimits
  url: https://docs.github.com/en/rest/overview/rate-limits-for-the-rest-api
- title: ''
  type: Blog
  url: https://github.blog/category/product/actions/
- title: ''
  type: StatusPage
  url: https://www.githubstatus.com
- title: ''
  type: ChangeLog
  url: https://github.blog/changelog/label/actions/
- title: ''
  type: GettingStarted
  url: https://docs.github.com/en/actions/get-started/quickstart
- title: ''
  type: Authentication
  url: https://docs.github.com/en/rest/overview/authenticating-to-the-rest-api
- title: ''
  type: Support
  url: https://support.github.com
- title: ''
  type: Pricing
  url: https://github.com/pricing
- title: ''
  type: GitHubOrganization
  url: https://github.com/github
- title: ''
  type: Portal
  url: https://docs.github.com/en/rest
- title: ''
  type: Documentation
  url: https://docs.github.com/en/actions
- title: ''
  type: SignUp
  url: https://github.com/signup
- title: ''
  type: Login
  url: https://github.com/login
- title: ''
  type: DeveloperPortal
  url: https://developer.github.com/
- title: ''
  type: Marketplace
  url: https://github.com/marketplace?type=actions
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/github-actions
- title: ''
  type: YouTube
  url: https://www.youtube.com/github
- title: JavaScript SDK
  type: SDK
  url: https://github.com/octokit/octokit.js
- title: Ruby SDK
  type: SDK
  url: https://github.com/octokit/octokit.rb
- title: .NET SDK
  type: SDK
  url: https://github.com/octokit/octokit.net
- title: Go SDK
  type: SDK
  url: https://github.com/google/go-github
- title: ''
  type: CLI
  url: https://cli.github.com/
- title: ''
  type: Quickstart
  url: https://docs.github.com/en/rest/quickstart
- title: ''
  type: Security
  url: https://docs.github.com/en/actions/security-for-github-actions
- title: ''
  type: JSONLD
  url: json-ld/github-actions-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/github-actions-workflow-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/github-actions-run-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/github-actions-job-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/github-actions-artifact-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/github-actions-secret-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/github-actions-runner-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/github-actions-variable-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/github-actions-cache-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/github-actions-simple-user-schema.json
- title: CI/CD Automation Capability
  type: Capabilities
  url: capabilities/ci-cd-automation.yaml
- title: Actions API Shared Definition
  type: Capabilities
  url: capabilities/shared/actions.yaml
created: '2024'
description: APIs for GitHub Actions - automation and CI/CD platform.
features:
- Automated CI/CD workflows triggered by repository events
- Matrix builds across multiple OS and language versions
- Reusable workflows and composite actions
- Encrypted secrets and variables at repo, org, and environment scopes
- Self-hosted and GitHub-hosted runner management
- Workflow artifact storage and sharing
- Deployment protection rules and environment approvals
- OIDC integration for cloud provider authentication
- Dependency caching for faster builds
- Runner groups for organizational access control
image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
integrations:
- AWS (via OIDC)
- Azure (via OIDC)
- Google Cloud (via OIDC)
- Docker Hub
- npm
- PyPI
- Slack
- Jira
jsonld:
- class_count: 0
  name: Github Actions Context
  property_count: 0
  slug: github-actions-context
layout: provider
modified: '2026-04-18'
name: GitHub Actions
rules:
- name: GitHub Actions API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: github-actions-spectral-rules
skills: []
slug: github-actions
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: GitHub Actions\ndescription: >-\n  APIs for GitHub Actions - automation and CI/CD platform.\nimage: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png\nurl: https://docs.github.com/en/rest/actions\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\napis:\n  - name: GitHub Actions API\n    description: >-\n      REST API for managing GitHub Actions workflows, runs, artifacts, and secrets.\n    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png\n    humanURL: https://docs.github.com/en/actions\n    baseURL: https://api.github.com\n    tags:\n      - Automation\n      - CI/CD\n      - DevOps\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/rest/actions\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json\n      - type: Authentication\n        url:\
  \ https://docs.github.com/en/rest/overview/authenticating-to-the-rest-api\n      - type: GettingStarted\n        url: https://docs.github.com/en/actions/get-started/quickstart\n      - type: APIReference\n        url: https://docs.github.com/en/rest/actions\n      - type: ChangeLog\n        url: https://github.blog/changelog/label/actions/\n      - type: SDK\n        url: https://github.com/octokit/octokit.js\n        title: JavaScript SDK\n      - type: SDK\n        url: https://github.com/octokit/octokit.rb\n        title: Ruby SDK\n      - type: SDK\n        url: https://github.com/octokit/octokit.net\n        title: .NET SDK\n      - type: SDK\n        url: https://github.com/google/go-github\n        title: Go SDK\n      - type: CLI\n        url: https://cli.github.com/manual/gh_workflow_run\n      - type: RateLimits\n        url: https://docs.github.com/en/rest/overview/rate-limits-for-the-rest-api\n      - type: OpenAPI\n        url: openapi/github-actions-openapi.yml\n      - type:\
  \ JSONSchema\n        url: json-schema/github-actions-workflow-schema.json\n      - type: JSONSchema\n        url: json-schema/github-actions-run-schema.json\n      - type: JSONSchema\n        url: json-schema/github-actions-job-schema.json\n      - type: JSONSchema\n        url: json-schema/github-actions-artifact-schema.json\n      - type: JSONSchema\n        url: json-schema/github-actions-secret-schema.json\n      - type: JSONSchema\n        url: json-schema/github-actions-runner-schema.json\n      - type: JSONSchema\n        url: json-schema/github-actions-variable-schema.json\n      - type: JSONSchema\n        url: json-schema/github-actions-cache-schema.json\n      - type: JSONSchema\n        url: json-schema/github-actions-simple-user-schema.json\n      - type: JSONLD\n        url: json-ld/github-actions-context.jsonld\n    contact:\n      - type: Support\n        url: https://support.github.com\n      - type: StatusPage\n        url: https://www.githubstatus.com\n    endpoints:\n\
  \      - name: Workflows\n        description: Manage workflow files and workflow runs\n        methods:\n          - GET /repos/{owner}/{repo}/actions/workflows\n          - GET /repos/{owner}/{repo}/actions/workflows/{workflow_id}\n          - GET /repos/{owner}/{repo}/actions/workflows/{workflow_id}/runs\n          - POST /repos/{owner}/{repo}/actions/workflows/{workflow_id}/dispatches\n          - PUT /repos/{owner}/{repo}/actions/workflows/{workflow_id}/disable\n          - PUT /repos/{owner}/{repo}/actions/workflows/{workflow_id}/enable\n          - GET /repos/{owner}/{repo}/actions/workflows/{workflow_id}/timing\n      - name: Workflow Runs\n        description: Manage and monitor workflow run executions\n        methods:\n          - GET /repos/{owner}/{repo}/actions/runs\n          - GET /repos/{owner}/{repo}/actions/runs/{run_id}\n          - POST /repos/{owner}/{repo}/actions/runs/{run_id}/rerun\n          - POST /repos/{owner}/{repo}/actions/runs/{run_id}/cancel\n         \
  \ - DELETE /repos/{owner}/{repo}/actions/runs/{run_id}\n          - GET /repos/{owner}/{repo}/actions/runs/{run_id}/approvals\n          - POST /repos/{owner}/{repo}/actions/runs/{run_id}/approve\n          - GET /repos/{owner}/{repo}/actions/runs/{run_id}/attempts/{attempt_number}\n          - GET /repos/{owner}/{repo}/actions/runs/{run_id}/attempts/{attempt_number}/logs\n          - POST /repos/{owner}/{repo}/actions/runs/{run_id}/deployment_protection_rule\n          - POST /repos/{owner}/{repo}/actions/runs/{run_id}/force-cancel\n          - GET /repos/{owner}/{repo}/actions/runs/{run_id}/logs\n          - DELETE /repos/{owner}/{repo}/actions/runs/{run_id}/logs\n          - GET /repos/{owner}/{repo}/actions/runs/{run_id}/pending_deployments\n          - POST /repos/{owner}/{repo}/actions/runs/{run_id}/pending_deployments\n          - POST /repos/{owner}/{repo}/actions/runs/{run_id}/rerun-failed-jobs\n          - GET /repos/{owner}/{repo}/actions/runs/{run_id}/timing\n      - name:\
  \ Artifacts\n        description: Download and manage workflow run artifacts\n        methods:\n          - GET /repos/{owner}/{repo}/actions/artifacts\n          - GET /repos/{owner}/{repo}/actions/artifacts/{artifact_id}\n          - GET /repos/{owner}/{repo}/actions/artifacts/{artifact_id}/{archive_format}\n          - DELETE /repos/{owner}/{repo}/actions/artifacts/{artifact_id}\n          - GET /repos/{owner}/{repo}/actions/runs/{run_id}/artifacts\n      - name: Secrets\n        description: Manage encrypted secrets for Actions\n        methods:\n          - GET /repos/{owner}/{repo}/actions/secrets\n          - GET /repos/{owner}/{repo}/actions/secrets/{secret_name}\n          - PUT /repos/{owner}/{repo}/actions/secrets/{secret_name}\n          - DELETE /repos/{owner}/{repo}/actions/secrets/{secret_name}\n          - GET /repos/{owner}/{repo}/actions/secrets/public-key\n          - GET /repos/{owner}/{repo}/actions/organization-secrets\n          - GET /orgs/{org}/actions/secrets\n\
  \          - GET /orgs/{org}/actions/secrets/public-key\n          - GET /orgs/{org}/actions/secrets/{secret_name}\n          - PUT /orgs/{org}/actions/secrets/{secret_name}\n          - DELETE /orgs/{org}/actions/secrets/{secret_name}\n          - GET /orgs/{org}/actions/secrets/{secret_name}/repositories\n          - PUT /orgs/{org}/actions/secrets/{secret_name}/repositories\n          - PUT /orgs/{org}/actions/secrets/{secret_name}/repositories/{repository_id}\n          - DELETE /orgs/{org}/actions/secrets/{secret_name}/repositories/{repository_id}\n          - GET /repos/{owner}/{repo}/environments/{environment_name}/secrets\n          - GET /repos/{owner}/{repo}/environments/{environment_name}/secrets/public-key\n          - GET /repos/{owner}/{repo}/environments/{environment_name}/secrets/{secret_name}\n          - PUT /repos/{owner}/{repo}/environments/{environment_name}/secrets/{secret_name}\n          - DELETE /repos/{owner}/{repo}/environments/{environment_name}/secrets/{secret_name}\n\
  \      - name: Self-hosted Runners\n        description: Manage self-hosted runners for workflows\n        methods:\n          - GET /repos/{owner}/{repo}/actions/runners\n          - GET /repos/{owner}/{repo}/actions/runners/{runner_id}\n          - DELETE /repos/{owner}/{repo}/actions/runners/{runner_id}\n          - GET /repos/{owner}/{repo}/actions/runners/downloads\n          - POST /repos/{owner}/{repo}/actions/runners/registration-token\n          - POST /repos/{owner}/{repo}/actions/runners/remove-token\n          - POST /repos/{owner}/{repo}/actions/runners/generate-jitconfig\n          - GET /repos/{owner}/{repo}/actions/runners/{runner_id}/labels\n          - POST /repos/{owner}/{repo}/actions/runners/{runner_id}/labels\n          - PUT /repos/{owner}/{repo}/actions/runners/{runner_id}/labels\n          - DELETE /repos/{owner}/{repo}/actions/runners/{runner_id}/labels\n          - DELETE /repos/{owner}/{repo}/actions/runners/{runner_id}/labels/{name}\n          - GET /orgs/{org}/actions/runners\n\
  \          - GET /orgs/{org}/actions/runners/{runner_id}\n          - DELETE /orgs/{org}/actions/runners/{runner_id}\n          - GET /orgs/{org}/actions/runners/downloads\n          - POST /orgs/{org}/actions/runners/registration-token\n          - POST /orgs/{org}/actions/runners/remove-token\n          - POST /orgs/{org}/actions/runners/generate-jitconfig\n          - GET /orgs/{org}/actions/runners/{runner_id}/labels\n          - POST /orgs/{org}/actions/runners/{runner_id}/labels\n          - PUT /orgs/{org}/actions/runners/{runner_id}/labels\n          - DELETE /orgs/{org}/actions/runners/{runner_id}/labels\n          - DELETE /orgs/{org}/actions/runners/{runner_id}/labels/{name}\n      - name: Jobs\n        description: Access information about workflow jobs\n        methods:\n          - GET /repos/{owner}/{repo}/actions/runs/{run_id}/jobs\n          - GET /repos/{owner}/{repo}/actions/jobs/{job_id}\n          - GET /repos/{owner}/{repo}/actions/jobs/{job_id}/logs\n          -\
  \ POST /repos/{owner}/{repo}/actions/jobs/{job_id}/rerun\n          - GET /repos/{owner}/{repo}/actions/runs/{run_id}/attempts/{attempt_number}/jobs\n      - name: Cache\n        description: Manage workflow dependency caches\n        methods:\n          - GET /repos/{owner}/{repo}/actions/caches\n          - DELETE /repos/{owner}/{repo}/actions/caches\n          - DELETE /repos/{owner}/{repo}/actions/caches/{cache_id}\n          - GET /repos/{owner}/{repo}/actions/cache/usage\n          - GET /repos/{owner}/{repo}/actions/cache/retention-limit\n          - PUT /repos/{owner}/{repo}/actions/cache/retention-limit\n          - GET /repos/{owner}/{repo}/actions/cache/storage-limit\n          - PUT /repos/{owner}/{repo}/actions/cache/storage-limit\n          - GET /orgs/{org}/actions/cache/usage\n          - GET /orgs/{org}/actions/cache/usage-by-repository\n          - GET /organizations/{org}/actions/cache/retention-limit\n          - PUT /organizations/{org}/actions/cache/retention-limit\n\
  \          - GET /organizations/{org}/actions/cache/storage-limit\n          - PUT /organizations/{org}/actions/cache/storage-limit\n      - name: Variables\n        description: Create and manage workflow variables at organization, repository, and environment scopes\n        methods:\n          - GET /repos/{owner}/{repo}/actions/variables\n          - POST /repos/{owner}/{repo}/actions/variables\n          - GET /repos/{owner}/{repo}/actions/variables/{name}\n          - PATCH /repos/{owner}/{repo}/actions/variables/{name}\n          - DELETE /repos/{owner}/{repo}/actions/variables/{name}\n          - GET /repos/{owner}/{repo}/actions/organization-variables\n          - GET /orgs/{org}/actions/variables\n          - POST /orgs/{org}/actions/variables\n          - GET /orgs/{org}/actions/variables/{name}\n          - PATCH /orgs/{org}/actions/variables/{name}\n          - DELETE /orgs/{org}/actions/variables/{name}\n          - GET /orgs/{org}/actions/variables/{name}/repositories\n \
  \         - PUT /orgs/{org}/actions/variables/{name}/repositories\n          - PUT /orgs/{org}/actions/variables/{name}/repositories/{repository_id}\n          - DELETE /orgs/{org}/actions/variables/{name}/repositories/{repository_id}\n          - GET /repos/{owner}/{repo}/environments/{environment_name}/variables\n          - POST /repos/{owner}/{repo}/environments/{environment_name}/variables\n          - GET /repos/{owner}/{repo}/environments/{environment_name}/variables/{name}\n          - PATCH /repos/{owner}/{repo}/environments/{environment_name}/variables/{name}\n          - DELETE /repos/{owner}/{repo}/environments/{environment_name}/variables/{name}\n      - name: Permissions\n        description: Control GitHub Actions enablement, allowed actions, and workflow permissions at organization and repository levels\n        methods:\n          - GET /orgs/{org}/actions/permissions\n          - PUT /orgs/{org}/actions/permissions\n          - GET /orgs/{org}/actions/permissions/repositories\n\
  \          - PUT /orgs/{org}/actions/permissions/repositories\n          - PUT /orgs/{org}/actions/permissions/repositories/{repository_id}\n          - DELETE /orgs/{org}/actions/permissions/repositories/{repository_id}\n          - GET /orgs/{org}/actions/permissions/selected-actions\n          - PUT /orgs/{org}/actions/permissions/selected-actions\n          - GET /orgs/{org}/actions/permissions/workflow\n          - PUT /orgs/{org}/actions/permissions/workflow\n          - GET /repos/{owner}/{repo}/actions/permissions\n          - PUT /repos/{owner}/{repo}/actions/permissions\n          - GET /repos/{owner}/{repo}/actions/permissions/access\n          - PUT /repos/{owner}/{repo}/actions/permissions/access\n          - GET /repos/{owner}/{repo}/actions/permissions/selected-actions\n          - PUT /repos/{owner}/{repo}/actions/permissions/selected-actions\n          - GET /repos/{owner}/{repo}/actions/permissions/workflow\n          - PUT /repos/{owner}/{repo}/actions/permissions/workflow\n\
  \      - name: OIDC\n        description: Manage OpenID Connect subject claim customization templates for organizations and repositories\n        methods:\n          - GET /orgs/{org}/actions/oidc/customization/sub\n          - PUT /orgs/{org}/actions/oidc/customization/sub\n          - GET /repos/{owner}/{repo}/actions/oidc/customization/sub\n          - PUT /repos/{owner}/{repo}/actions/oidc/customization/sub\n      - name: Self-hosted Runner Groups\n        description: Create and manage runner groups to control repository access and organize self-hosted runners\n        methods:\n          - GET /orgs/{org}/actions/runner-groups\n          - POST /orgs/{org}/actions/runner-groups\n          - GET /orgs/{org}/actions/runner-groups/{runner_group_id}\n          - PATCH /orgs/{org}/actions/runner-groups/{runner_group_id}\n          - DELETE /orgs/{org}/actions/runner-groups/{runner_group_id}\n          - GET /orgs/{org}/actions/runner-groups/{runner_group_id}/repositories\n          -\
  \ PUT /orgs/{org}/actions/runner-groups/{runner_group_id}/repositories\n          - PUT /orgs/{org}/actions/runner-groups/{runner_group_id}/repositories/{repository_id}\n          - DELETE /orgs/{org}/actions/runner-groups/{runner_group_id}/repositories/{repository_id}\n          - GET /orgs/{org}/actions/runner-groups/{runner_group_id}/runners\n          - PUT /orgs/{org}/actions/runner-groups/{runner_group_id}/runners\n          - PUT /orgs/{org}/actions/runner-groups/{runner_group_id}/runners/{runner_id}\n          - DELETE /orgs/{org}/actions/runner-groups/{runner_group_id}/runners/{runner_id}\n      - name: GitHub-hosted Runners\n        description: Provision and manage GitHub-hosted runners, custom images, and machine specifications for organizations\n        methods:\n          - GET /orgs/{org}/actions/hosted-runners\n          - POST /orgs/{org}/actions/hosted-runners\n          - GET /orgs/{org}/actions/hosted-runners/{hosted_runner_id}\n          - PATCH /orgs/{org}/actions/hosted-runners/{hosted_runner_id}\n\
  \          - DELETE /orgs/{org}/actions/hosted-runners/{hosted_runner_id}\n          - GET /orgs/{org}/actions/hosted-runners/images/github-owned\n          - GET /orgs/{org}/actions/hosted-runners/images/partner\n          - GET /orgs/{org}/actions/hosted-runners/images/custom\n          - GET /orgs/{org}/actions/hosted-runners/images/custom/{image_definition_id}\n          - DELETE /orgs/{org}/actions/hosted-runners/images/custom/{image_definition_id}\n          - GET /orgs/{org}/actions/hosted-runners/images/custom/{image_definition_id}/versions\n          - GET /orgs/{org}/actions/hosted-runners/images/custom/{image_definition_id}/versions/{version}\n          - DELETE /orgs/{org}/actions/hosted-runners/images/custom/{image_definition_id}/versions/{version}\n          - GET /orgs/{org}/actions/hosted-runners/limits\n          - GET /orgs/{org}/actions/hosted-runners/machine-sizes\n          - GET /orgs/{org}/actions/hosted-runners/platforms\nmaintainers:\n  - type: GitHub\n    name:\
  \ GitHub, Inc.\n    url: https://github.com\n    email: support@github.com\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: TermsOfService\n    url: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service\n  - type: PrivacyPolicy\n    url: https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement\n  - type: RateLimits\n    url: https://docs.github.com/en/rest/overview/rate-limits-for-the-rest-api\n  - type: Blog\n    url: https://github.blog/category/product/actions/\n  - type: StatusPage\n    url: https://www.githubstatus.com\n  - type: ChangeLog\n    url: https://github.blog/changelog/label/actions/\n  - type: GettingStarted\n    url: https://docs.github.com/en/actions/get-started/quickstart\n  - type: Authentication\n    url: https://docs.github.com/en/rest/overview/authenticating-to-the-rest-api\n  - type: Support\n    url: https://support.github.com\n  - type: Pricing\n    url: https://github.com/pricing\n  - type:\
  \ GitHubOrganization\n    url: https://github.com/github\n  - type: Portal\n    url: https://docs.github.com/en/rest\n  - type: Documentation\n    url: https://docs.github.com/en/actions\n  - type: SignUp\n    url: https://github.com/signup\n  - type: Login\n    url: https://github.com/login\n  - type: DeveloperPortal\n    url: https://developer.github.com/\n  - type: Marketplace\n    url: https://github.com/marketplace?type=actions\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/github-actions\n  - type: YouTube\n    url: https://www.youtube.com/github\n  - type: SDK\n    url: https://github.com/octokit/octokit.js\n    title: JavaScript SDK\n  - type: SDK\n    url: https://github.com/octokit/octokit.rb\n    title: Ruby SDK\n  - type: SDK\n    url: https://github.com/octokit/octokit.net\n    title: .NET SDK\n  - type: SDK\n    url: https://github.com/google/go-github\n    title: Go SDK\n  - type: CLI\n    url: https://cli.github.com/\n  - type: Quickstart\n\
  \    url: https://docs.github.com/en/rest/quickstart\n  - type: Security\n    url: https://docs.github.com/en/actions/security-for-github-actions\n  - type: JSONLD\n    url: json-ld/github-actions-context.jsonld\n  - type: JSONSchema\n    url: json-schema/github-actions-workflow-schema.json\n  - type: JSONSchema\n    url: json-schema/github-actions-run-schema.json\n  - type: JSONSchema\n    url: json-schema/github-actions-job-schema.json\n  - type: JSONSchema\n    url: json-schema/github-actions-artifact-schema.json\n  - type: JSONSchema\n    url: json-schema/github-actions-secret-schema.json\n  - type: JSONSchema\n    url: json-schema/github-actions-runner-schema.json\n  - type: JSONSchema\n    url: json-schema/github-actions-variable-schema.json\n  - type: JSONSchema\n    url: json-schema/github-actions-cache-schema.json\n  - type: JSONSchema\n    url: json-schema/github-actions-simple-user-schema.json\n  - type: Capabilities\n    url: capabilities/ci-cd-automation.yaml\n    title: CI/CD\
  \ Automation Capability\n  - type: Capabilities\n    url: capabilities/shared/actions.yaml\n    title: Actions API Shared Definition\n  - type: Features\n    data:\n      - Automated CI/CD workflows triggered by repository events\n      - Matrix builds across multiple OS and language versions\n      - Reusable workflows and composite actions\n      - Encrypted secrets and variables at repo, org, and environment scopes\n      - Self-hosted and GitHub-hosted runner management\n      - Workflow artifact storage and sharing\n      - Deployment protection rules and environment approvals\n      - OIDC integration for cloud provider authentication\n      - Dependency caching for faster builds\n      - Runner groups for organizational access control\n  - type: UseCases\n    data:\n      - Continuous integration and testing on every push or pull request\n      - Automated deployment to cloud environments\n      - Scheduled maintenance and cleanup workflows\n      - Building and publishing container\
  \ images\n      - Automated code quality and security scanning\n      - Release management and artifact publishing\n  - type: Integrations\n    data:\n      - AWS (via OIDC)\n      - Azure (via OIDC)\n      - Google Cloud (via OIDC)\n      - Docker Hub\n      - npm\n      - PyPI\n      - Slack\n      - Jira\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/github-actions/refs/heads/main/apis.yml
tags: []
url: https://docs.github.com/en/rest/actions
use_cases:
- Continuous integration and testing on every push or pull request
- Automated deployment to cloud environments
- Scheduled maintenance and cleanup workflows
- Building and publishing container images
- Automated code quality and security scanning
- Release management and artifact publishing
---
