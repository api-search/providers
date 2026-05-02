---
api_count: 3
apis:
- description: The Visual Studio Extensibility API enables developers to create extensions that customize and extend Visual Studio IDE functionality. Extensions can add custom tool windows, commands, code analyzers,
  name: Visual Studio Extensibility API
  slug: extensibility-api
- description: The Visual Studio Marketplace API provides access to the extension marketplace for Visual Studio, VS Code, and Azure DevOps. Developers can search extensions, retrieve metadata, manage publisher profi
  name: Visual Studio Marketplace API
  slug: marketplace-api
- description: The VS Code Extension API enables developers to build extensions for Visual Studio Code. It provides APIs for language support, debugging, source control, terminal integration, webviews, custom editor
  name: VS Code Extension API
  slug: vscode-extension-api
common:
- title: ''
  type: Portal
  url: https://marketplace.visualstudio.com/
- title: ''
  type: Website
  url: https://visualstudio.microsoft.com/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/visualstudio/ide/
- title: ''
  type: GitHub Organization
  url: https://github.com/microsoft/vscode
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Support
  url: https://support.microsoft.com/
created: '2024-01-01'
description: Microsoft Visual Studio is an integrated development environment (IDE) for building applications. It provides APIs for extending the IDE functionality, publishing extensions to the marketplace, and building VS Code extensions.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Visual Studio
skills: []
slug: microsoft-visual-studio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-visual-studio\nname: Microsoft Visual Studio\ndescription: >-\n  Microsoft Visual Studio is an integrated development environment (IDE) for\n  building applications. It provides APIs for extending the IDE functionality,\n  publishing extensions to the marketplace, and building VS Code extensions.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Developer Tools\n  - Extensions\n  - IDE\n  - Microsoft\n  - VS Code\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-visual-studio/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: microsoft-visual-studio:extensibility-api\n    name: Visual Studio Extensibility API\n    tags:\n      - Developer Tools\n      - Extensions\n      - IDE\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/visualstudio/extensibility/\n\
  \    properties:\n      - url: https://learn.microsoft.com/en-us/visualstudio/extensibility/\n        type: Documentation\n    description: >-\n      The Visual Studio Extensibility API enables developers to create\n      extensions that customize and extend Visual Studio IDE functionality.\n      Extensions can add custom tool windows, commands, code analyzers,\n      project templates, debugger visualizers, and language services using\n      the VSIX packaging format and MEF composition model.\n  - aid: microsoft-visual-studio:marketplace-api\n    name: Visual Studio Marketplace API\n    tags:\n      - Distribution\n      - Extensions\n      - Marketplace\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://marketplace.visualstudio.com/_apis/\n    humanURL: https://learn.microsoft.com/en-us/azure/devops/extend/develop/data-storage\n    properties:\n      - url: https://learn.microsoft.com/en-us/azure/devops/extend/develop/data-storage\n\
  \        type: Documentation\n    description: >-\n      The Visual Studio Marketplace API provides access to the extension\n      marketplace for Visual Studio, VS Code, and Azure DevOps. Developers\n      can search extensions, retrieve metadata, manage publisher profiles,\n      and publish extensions programmatically through REST endpoints.\n  - aid: microsoft-visual-studio:vscode-extension-api\n    name: VS Code Extension API\n    tags:\n      - Editor\n      - Extensions\n      - VS Code\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://code.visualstudio.com/api\n    properties:\n      - url: https://code.visualstudio.com/api\n        type: Documentation\n      - url: https://code.visualstudio.com/api/get-started/your-first-extension\n        type: Getting Started\n    description: >-\n      The VS Code Extension API enables developers to build extensions for\n      Visual Studio Code. It provides APIs for language support,\
  \ debugging,\n      source control, terminal integration, webviews, custom editors,\n      notebooks, and testing. Extensions can contribute commands, menus,\n      settings, and keybindings to the editor experience.\ncommon:\n  - type: Portal\n    url: https://marketplace.visualstudio.com/\n  - type: Website\n    url: https://visualstudio.microsoft.com/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/visualstudio/ide/\n  - type: GitHub Organization\n    url: https://github.com/microsoft/vscode\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Support\n    url: https://support.microsoft.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-visual-studio/refs/heads/main/apis.yml
tags:
- Developer Tools
- Extensions
- IDE
- Microsoft
- VS Code
url: https://raw.githubusercontent.com/api-evangelist/microsoft-visual-studio/refs/heads/main/apis.yml
use_cases: []
---
