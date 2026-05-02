---
api_count: 4
apis:
- description: API for managing .NET packages through NuGet Gallery.
  name: NuGet Package API
  slug: nuget-package-api
- description: API for the Windows Package Manager client for discovering and installing applications.
  name: Windows Package Manager (WinGet) API
  slug: winget-api
- description: API for managing app submissions and accessing Microsoft Store catalog.
  name: Microsoft Store API
  slug: microsoft-store-api
- description: API for managing packages in Azure Artifacts including NuGet, npm, Maven, and Python packages.
  name: Azure Artifacts Package API
  slug: azure-artifacts-api
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Support
  url: https://support.microsoft.com/
created: '2024-01-15'
description: A collection of Microsoft package management APIs covering NuGet, Windows Package Manager (WinGet), Microsoft Store, and Azure Artifacts for managing and distributing software packages across Microsoft platforms.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Package
skills: []
slug: microsoft-package
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-package\nname: Microsoft Package\ndescription: >-\n  A collection of Microsoft package management APIs covering NuGet, Windows\n  Package Manager (WinGet), Microsoft Store, and Azure Artifacts for managing\n  and distributing software packages across Microsoft platforms.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Azure Artifacts\n  - Microsoft\n  - NuGet\n  - Package Management\n  - WinGet\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-package/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: microsoft-package:nuget-package-api\n    name: NuGet Package API\n    description: >-\n      API for managing .NET packages through NuGet Gallery.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.nuget.org/\n    baseURL: https://api.nuget.org/v3/index.json\n \
  \   tags:\n      - .NET\n      - Libraries\n      - NuGet\n      - Packages\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/nuget/api/overview\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/nuget/api/authentication\n  - aid: microsoft-package:winget-api\n    name: Windows Package Manager (WinGet) API\n    description: >-\n      API for the Windows Package Manager client for discovering and installing applications.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/windows/package-manager/\n    baseURL: https://winget.azureedge.net/cache\n    tags:\n      - Applications\n      - Package Manager\n      - Windows\n      - WinGet\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/windows/package-manager/\n      - type: GitHub Organization\n        url: https://github.com/microsoft/winget-cli\n\
  \  - aid: microsoft-package:microsoft-store-api\n    name: Microsoft Store API\n    description: >-\n      API for managing app submissions and accessing Microsoft Store catalog.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/windows/uwp/monetize/create-and-manage-submissions-using-windows-store-services\n    baseURL: https://manage.devcenter.microsoft.com/v1.0/my/\n    tags:\n      - Apps\n      - Commercial\n      - Microsoft Store\n      - Submissions\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/windows/uwp/monetize/create-and-manage-submissions-using-windows-store-services\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/windows/uwp/monetize/create-and-manage-submissions-using-windows-store-services\n  - aid: microsoft-package:azure-artifacts-api\n    name: Azure Artifacts Package API\n    description: >-\n      API for\
  \ managing packages in Azure Artifacts including NuGet, npm, Maven, and\n      Python packages.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://azure.microsoft.com/en-us/services/devops/artifacts/\n    baseURL: https://pkgs.dev.azure.com/{organization}/\n    tags:\n      - Artifacts\n      - Azure\n      - DevOps\n      - Packages\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/artifacts/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Support\n    url: https://support.microsoft.com/\nmaintainers:\n  -\
  \ FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-package/refs/heads/main/apis.yml
tags:
- Azure Artifacts
- Microsoft
- NuGet
- Package Management
- WinGet
url: https://raw.githubusercontent.com/api-evangelist/microsoft-package/refs/heads/main/apis.yml
use_cases: []
---
