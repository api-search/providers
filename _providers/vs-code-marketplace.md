---
api_count: 1
api_specs:
- filename: vs-code-marketplace-gallery-api-openapi.yml
  format: yaml
  label: VS Code Marketplace Gallery API
  slug: vs-code-marketplace-gallery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vs-code-marketplace/refs/heads/main/openapi/vs-code-marketplace-gallery-api-openapi.yml
apis:
- description: The VS Code Marketplace Gallery API provides programmatic access to the Visual Studio Marketplace, enabling search, discovery, and retrieval of extensions for Visual Studio Code and other Microsoft de
  name: VS Code Marketplace Gallery API
  slug: vs-code-marketplace-gallery-api
capabilities:
- description: Extension discovery and management workflow for the VS Code Marketplace Gallery API. Enables searching for extensions by keyword, tag, or category; retrieving publisher details; and downloading VSIX p
  name: VS Code Extension Discovery
  slug: extension-discovery
common:
- title: ''
  type: Website
  url: https://marketplace.visualstudio.com/
- title: ''
  type: Documentation
  url: https://code.visualstudio.com/docs
- title: ''
  type: Guide
  url: https://code.visualstudio.com/api/working-with-extensions/publishing-extension
- title: ''
  type: Portal
  url: https://marketplace.visualstudio.com/manage
- title: ''
  type: Documentation
  url: https://code.visualstudio.com/api
- title: ''
  type: GettingStarted
  url: https://code.visualstudio.com/api/get-started/your-first-extension
- title: ''
  type: Catalog
  url: https://marketplace.visualstudio.com/VSCode
- title: ''
  type: ChangeLog
  url: https://code.visualstudio.com/updates
- title: ''
  type: Blog
  url: https://code.visualstudio.com/blogs
- title: ''
  type: GitHub
  url: https://github.com/microsoft/vscode
- title: ''
  type: IssueTracker
  url: https://github.com/microsoft/vscode/issues
- title: ''
  type: Community
  url: https://code.visualstudio.com/community
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/visual-studio-code
- title: ''
  type: X
  url: https://x.com/code
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/showcase/microsoft-visual-studio-code
- title: ''
  type: YouTube
  url: https://www.youtube.com/@code
- title: ''
  type: TermsOfService
  url: https://marketplace.visualstudio.com/policies/agree
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/privacystatement
created: '2024-01-01'
description: VS Code Marketplace is Microsoft's official extension marketplace for Visual Studio Code, offering thousands of extensions for languages, debuggers, themes, and developer tools. It provides a Gallery API for programmatically searching, discovering, and retrieving extension metadata, enabling integration with editors, tooling, and automation workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Vs Code Marketplace Context
  property_count: 8
  slug: vs-code-marketplace-context
layout: provider
modified: '2026-05-03'
name: VS Code Marketplace
rules:
- name: VS Code Marketplace API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 3
    warn: 4
  slug: vs-code-marketplace-rules
skills: []
slug: vs-code-marketplace
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vs-code-marketplace\nurl: https://raw.githubusercontent.com/api-evangelist/vs-code-marketplace/refs/heads/main/apis.yml\napis:\n  - aid: vs-code-marketplace:vs-code-marketplace-gallery-api\n    name: VS Code Marketplace Gallery API\n    description: The VS Code Marketplace Gallery API provides programmatic access to the Visual Studio Marketplace, enabling search, discovery, and retrieval of extensions for Visual Studio Code and other Microsoft developer tools. It supports querying extensions by name, publisher, category, and tags, as well as fetching extension details, versions, statistics, and reviews.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/microsoft/vscode/blob/main/src/vs/platform/extensionManagement/common/extensionGalleryService.ts\n    baseURL: https://marketplace.visualstudio.com/_apis/public/gallery\n    tags:\n      - Developer Tools\n      - Extensions\n      - IDE\n      - Marketplace\n\
  \      - Microsoft\n      - Visual Studio Code\n    properties:\n      - url: https://marketplace.visualstudio.com/\n        type: Documentation\n      - url: https://marketplace.visualstudio.com/_apis/public/gallery\n        type: BaseURL\n      - url: https://github.com/microsoft/vscode/blob/main/src/vs/platform/extensionManagement/common/extensionGalleryService.ts\n        type: SourceCode\n      - url: https://code.visualstudio.com/api/working-with-extensions/publishing-extension\n        type: Guide\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/vs-code-marketplace/refs/heads/main/openapi/vs-code-marketplace-gallery-api-openapi.yml\n        type: OpenAPI\nname: VS Code Marketplace\ndescription: VS Code Marketplace is Microsoft's official extension marketplace for Visual Studio Code, offering thousands of extensions for languages, debuggers, themes, and developer tools. It provides a Gallery API for programmatically searching, discovering, and retrieving\
  \ extension metadata, enabling integration with editors, tooling, and automation workflows.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Developer Tools\n  - Extensions\n  - IDE\n  - Microsoft\ntype: Index\naccess: 3rd-Party\ncommon:\n  - url: https://marketplace.visualstudio.com/\n    name: VS Code Marketplace Website\n    type: Website\n  - url: https://code.visualstudio.com/docs\n    name: Documentation\n    type: Documentation\n  - url: https://code.visualstudio.com/api/working-with-extensions/publishing-extension\n    name: Publishing Extensions Guide\n    type: Guide\n  - url: https://marketplace.visualstudio.com/manage\n    name: Publisher Management\n    type: Portal\n  - url: https://code.visualstudio.com/api\n    name: Extension API Documentation\n    type: Documentation\n  - url: https://code.visualstudio.com/api/get-started/your-first-extension\n    name: Getting Started\n    type: GettingStarted\n  - url: https://marketplace.visualstudio.com/VSCode\n\
  \    name: VS Code Extensions\n    type: Catalog\n  - url: https://code.visualstudio.com/updates\n    name: Release Notes\n    type: ChangeLog\n  - url: https://code.visualstudio.com/blogs\n    name: Blog\n    type: Blog\n  - url: https://github.com/microsoft/vscode\n    name: GitHub\n    type: GitHub\n  - url: https://github.com/microsoft/vscode/issues\n    name: GitHub Issues\n    type: IssueTracker\n  - url: https://code.visualstudio.com/community\n    name: Community\n    type: Community\n  - url: https://stackoverflow.com/questions/tagged/visual-studio-code\n    name: Stack Overflow\n    type: StackOverflow\n  - url: https://x.com/code\n    name: X (Twitter)\n    type: X\n  - url: https://www.linkedin.com/showcase/microsoft-visual-studio-code\n    name: LinkedIn\n    type: LinkedIn\n  - url: https://www.youtube.com/@code\n    name: YouTube\n    type: YouTube\n  - url: https://marketplace.visualstudio.com/policies/agree\n    name: Terms of Use\n    type: TermsOfService\n  - url: https://privacy.microsoft.com/privacystatement\n\
  \    name: Privacy Policy\n    type: PrivacyPolicy\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vs-code-marketplace/refs/heads/main/apis.yml
tags:
- Developer Tools
- Extensions
- IDE
- Microsoft
url: https://raw.githubusercontent.com/api-evangelist/vs-code-marketplace/refs/heads/main/apis.yml
use_cases: []
---
