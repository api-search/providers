---
api_count: 3
api_specs:
- filename: git.json
  format: json
  label: Azure DevOps Services REST API - Git
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/MicrosoftDocs/vsts-rest-api-specs/blob/master/specification/git/7.1/git.json
- filename: tfvc.json
  format: json
  label: Azure DevOps Services REST API - TFVC
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/MicrosoftDocs/vsts-rest-api-specs/blob/master/specification/tfvc/7.1/tfvc.json
- filename: policy.json
  format: json
  label: Azure DevOps Services REST API - Policy
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/MicrosoftDocs/vsts-rest-api-specs/blob/master/specification/policy/7.1/policy.json
apis:
- description: REST API for Git repositories in Azure Repos, including repositories, commits, pull requests, branches, and more.
  name: Azure DevOps Services REST API - Git
  slug: ''
- description: REST API for Team Foundation Version Control (TFVC) repositories in Azure Repos.
  name: Azure DevOps Services REST API - TFVC
  slug: ''
- description: REST API for managing repository policies including branch policies, required reviewers, and build validation.
  name: Azure DevOps Services REST API - Policy
  slug: ''
common:
- title: ''
  type: Portal
  url: https://learn.microsoft.com/en-us/azure/devops/repos/?view=azure-devops
- title: ''
  type: Getting Started
  url: https://docs.microsoft.com/en-us/azure/devops/repos/get-started/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/devops/repos/git/?view=azure-devops
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/
- title: ''
  type: Rate Limits
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits
- title: ''
  type: Status
  url: https://status.dev.azure.com/
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Change Log
  url: https://learn.microsoft.com/en-us/azure/devops/release-notes/features-timeline-released
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/devops/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/devops/
- title: ''
  type: Console
  url: https://dev.azure.com
- title: ''
  type: Sign Up
  url: https://learn.microsoft.com/en-us/azure/devops/repos/get-started/sign-up-invite-teammates?view=azure-devops
- title: ''
  type: Website
  url: https://azure.microsoft.com/en-us/services/devops/repos/
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries?view=azure-devops
- title: ''
  type: Community
  url: https://developercommunity.visualstudio.com/AzureDevOps
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/azure-devops
- title: ''
  type: GitHub Organization
  url: https://github.com/MicrosoftDocs/vsts-rest-api-specs
- title: ''
  type: YouTube
  url: https://www.youtube.com/@AzureDevOps
created: '2024-01-01'
description: Azure Repos is a set of version control tools that you can use to manage your code. Whether your software project is large or small, using version control as soon as possible is a good idea.
features: []
image: https://docs.microsoft.com/en-us/azure/devops/repos/media/index/repos.svg
integrations: []
layout: provider
modified: '2026-04-28'
name: Azure Repos
skills: []
slug: microsoft-azure-repo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Repos\ndescription: Azure Repos is a set of version control tools that you can use to manage your code. Whether your software project is large or small, using version control as soon as possible is a good idea.\nimage: https://docs.microsoft.com/en-us/azure/devops/repos/media/index/repos.svg\ntags:\n  - DevOps\n  - Git\n  - Repositories\n  - Source Control\n  - TFVC\n  - Version Control\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nurl: https://azure.microsoft.com/en-us/services/devops/repos/\nspecificationVersion: '0.18'\napis:\n  - name: Azure DevOps Services REST API - Git\n    description: REST API for Git repositories in Azure Repos, including repositories, commits, pull requests, branches, and more.\n    image: https://docs.microsoft.com/en-us/azure/devops/repos/media/index/repos.svg\n    humanURL: https://docs.microsoft.com/en-us/rest/api/azure/devops/git/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/git\n    tags:\n      - Branches\n\
  \      - Commits\n      - Git\n      - Pull Requests\n      - Repositories\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/rest/api/azure/devops/git/\n      - type: OpenAPI\n        url: https://github.com/MicrosoftDocs/vsts-rest-api-specs/blob/master/specification/git/7.1/git.json\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance\n      - type: Rate Limits\n        url: https://docs.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/git/?view=azure-devops-rest-7.1\n      - type: Quickstart\n        url: https://learn.microsoft.com/en-us/azure/devops/repos/git/gitquickstart?view=azure-devops\n      - type: Client Libraries\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries?view=azure-devops\n\
  \    contact:\n      - FN: Azure DevOps Support\n        email:\n          - email protected\n        url: https://azure.microsoft.com/en-us/support/devops/\n  - name: Azure DevOps Services REST API - TFVC\n    description: REST API for Team Foundation Version Control (TFVC) repositories in Azure Repos.\n    image: https://docs.microsoft.com/en-us/azure/devops/repos/media/index/repos.svg\n    humanURL: https://docs.microsoft.com/en-us/rest/api/azure/devops/tfvc/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/tfvc\n    tags:\n      - Changesets\n      - Shelvesets\n      - TFVC\n      - Version Control\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/rest/api/azure/devops/tfvc/\n      - type: OpenAPI\n        url: https://github.com/MicrosoftDocs/vsts-rest-api-specs/blob/master/specification/tfvc/7.1/tfvc.json\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance\n\
  \      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/tfvc/?view=azure-devops-rest-7.1\n      - type: Rate Limits\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits\n      - type: Client Libraries\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries?view=azure-devops\n    contact:\n      - FN: Azure DevOps Support\n        email:\n          - email protected\n        url: https://azure.microsoft.com/en-us/support/devops/\n  - name: Azure DevOps Services REST API - Policy\n    description: REST API for managing repository policies including branch policies, required reviewers, and build validation.\n    image: https://docs.microsoft.com/en-us/azure/devops/repos/media/index/repos.svg\n    humanURL: https://docs.microsoft.com/en-us/rest/api/azure/devops/policy/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/policy\n    tags:\n      - Branch\
  \ Policy\n      - Build Validation\n      - Code Review\n      - Policy\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/rest/api/azure/devops/policy/\n      - type: OpenAPI\n        url: https://github.com/MicrosoftDocs/vsts-rest-api-specs/blob/master/specification/policy/7.1/policy.json\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/policy/?view=azure-devops-rest-7.1\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops\n      - type: Rate Limits\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits\n    contact:\n      - FN: Azure DevOps Support\n        email:\n          - email protected\n        url: https://azure.microsoft.com/en-us/support/devops/\ncommon:\n  - type: Portal\n    url: https://learn.microsoft.com/en-us/azure/devops/repos/?view=azure-devops\n\
  \  - type: Getting Started\n    url: https://docs.microsoft.com/en-us/azure/devops/repos/get-started/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/devops/repos/git/?view=azure-devops\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/\n  - type: Rate Limits\n    url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits\n  - type: Status\n    url: https://status.dev.azure.com/\n  - type: Terms of Service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Change Log\n    url: https://learn.microsoft.com/en-us/azure/devops/release-notes/features-timeline-released\n  - type: Blog\n    url: https://devblogs.microsoft.com/devops/\n\
  \  - type: Support\n    url: https://azure.microsoft.com/en-us/support/devops/\n  - type: Console\n    url: https://dev.azure.com\n  - type: Sign Up\n    url: https://learn.microsoft.com/en-us/azure/devops/repos/get-started/sign-up-invite-teammates?view=azure-devops\n  - type: Website\n    url: https://azure.microsoft.com/en-us/services/devops/repos/\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries?view=azure-devops\n  - type: Community\n    url: https://developercommunity.visualstudio.com/AzureDevOps\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/azure-devops\n  - type: GitHub Organization\n    url: https://github.com/MicrosoftDocs/vsts-rest-api-specs\n  - type: YouTube\n    url: https://www.youtube.com/@AzureDevOps\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-repo/refs/heads/main/apis.yml
tags:
- DevOps
- Git
- Repositories
- Source Control
- TFVC
- Version Control
url: https://azure.microsoft.com/en-us/services/devops/repos/
use_cases: []
---
