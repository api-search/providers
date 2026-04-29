---
api_count: 4
api_specs:
- filename: microsoft-edge-addons-api.yaml
  format: yaml
  label: Microsoft Edge Add-ons API
  slug: edge-addons-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-edge/refs/heads/main/openapi/microsoft-edge-addons-api.yaml
- filename: microsoft-edge-devtools-api.yaml
  format: yaml
  label: Microsoft Edge DevTools Protocol HTTP API
  slug: edge-devtools-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-edge/refs/heads/main/openapi/microsoft-edge-devtools-api.yaml
apis:
- description: REST API for managing Microsoft Edge browser extensions through the Partner Center. Enables programmatic publishing, updating, and managing Edge extensions in the Microsoft Edge Add-ons store, support
  name: Microsoft Edge Add-ons API
  slug: edge-addons-api
- description: HTTP endpoints for the Microsoft Edge DevTools Protocol, based on the Chromium DevTools Protocol. These endpoints allow programmatic discovery and management of debuggable browser targets including pa
  name: Microsoft Edge DevTools Protocol HTTP API
  slug: edge-devtools-api
- description: Build browser extensions for Microsoft Edge using the Chromium-based extensions platform. Supports the WebExtensions API standard for cross-browser compatibility.
  name: Microsoft Edge Extensions API
  slug: edge-extensions-api
- description: Modern web APIs and standards supported in Microsoft Edge, including Progressive Web App capabilities, Web Components, and emerging web platform features.
  name: Microsoft Edge Web Platform APIs
  slug: edge-web-platform-apis
capabilities:
- description: Unified workflow for Microsoft Edge browser development combining DevTools Protocol debugging with Add-ons extension lifecycle management. Used by extension developers, web developers, and QA engineer
  name: Microsoft Edge Browser Development
  slug: browser-development
common:
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/microsoft-edge/
- title: ''
  type: DeveloperPortal
  url: https://developer.microsoft.com/microsoft-edge/
- title: ''
  type: Blog
  url: https://blogs.windows.com/msedgedev/
- title: ''
  type: GitHubOrganization
  url: https://github.com/MicrosoftEdge
- title: ''
  type: GitHubRepository
  url: https://github.com/MicrosoftEdge/WebView2Samples
- title: ''
  type: GitHubRepository
  url: https://github.com/nicedoc/nicedoc.io
- title: ''
  type: Support
  url: https://learn.microsoft.com/en-us/microsoft-edge/devtools-guide-chromium/
- title: ''
  type: ReleaseNotes
  url: https://learn.microsoft.com/en-us/microsoft-edge/web-platform/release-notes/
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/en-us/deployedge/microsoft-edge-relnote-stable-channel
- title: ''
  type: StatusPage
  url: https://developer.microsoft.com/en-us/microsoft-edge/status/
- title: ''
  type: X
  url: https://twitter.com/MSEdgeDev
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/privacystatement
- title: ''
  type: SDK
  url: https://www.nuget.org/packages/Microsoft.Web.WebView2
- title: ''
  type: SignUp
  url: https://partner.microsoft.com/dashboard/microsoftedge/
- title: ''
  type: Login
  url: https://partner.microsoft.com/dashboard/
- title: ''
  type: Marketplace
  url: https://microsoftedge.microsoft.com/addons/
- title: DevTools API Context
  type: JSONLD
  url: json-ld/microsoft-edge-devtools-api-context.jsonld
- title: Add-ons API Context
  type: JSONLD
  url: json-ld/microsoft-edge-addons-api-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/microsoft-edge-spectral-rules.yml
- title: Browser Development Workflow
  type: NaftikoCapability
  url: capabilities/browser-development.yaml
- title: DevTools API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/devtools-api.yaml
- title: Add-ons API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/addons-api.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/microsoft-edge-vocabulary.yaml
created: '2024-01-01'
description: APIs and resources for Microsoft Edge browser development and integration, including the Edge Add-ons API for extension management, DevTools Protocol for browser debugging and automation, Extensions API for building browser extensions, and Web Platform APIs for progressive web app development.
features:
- description: Programmatically publish, update, and manage browser extensions in the Edge Add-ons store via REST API.
  name: Extension Publishing API
- description: Debug and inspect web pages, service workers, and extensions using the Chrome DevTools Protocol over WebSocket.
  name: Remote Debugging Protocol
- description: Embed Microsoft Edge rendering engine in native desktop applications using the WebView2 SDK.
  name: WebView2 Embedding
- description: Build installable PWAs with offline capability, push notifications, and system integration.
  name: Progressive Web App Support
- description: Build extensions using the Chromium WebExtensions API standard for cross-browser portability.
  name: Cross-Browser Extension Compatibility
- description: Automate browser tasks including page navigation, target management, and performance profiling.
  name: Browser Automation
- description: Load and test unpacked extensions locally during development without publishing to the store.
  name: Extension Sideloading
- description: Build extensions using the latest Manifest V3 specification with service workers and declarative APIs.
  name: Manifest V3 Support
image: https://www.microsoft.com/edge/favicon.ico
integrations:
- description: Authenticate to the Edge Add-ons API using Azure AD OAuth 2.0 client credentials flow.
  name: Azure Active Directory
- description: Manage extension listings, submissions, and analytics through the Partner Center dashboard.
  name: Microsoft Partner Center
- description: Debug Edge browser content directly from VS Code using the Edge DevTools extension.
  name: Visual Studio Code
- description: Automate Microsoft Edge browser for testing using Selenium with the Edge WebDriver.
  name: Selenium WebDriver
- description: Cross-browser automation framework with first-class support for Microsoft Edge testing.
  name: Playwright
- description: Control headless Microsoft Edge instances programmatically using the Puppeteer Node.js library.
  name: Puppeteer
- description: Automate extension publishing and browser testing in CI/CD workflows using GitHub Actions.
  name: GitHub Actions
- description: Integrate WebView2 into Windows desktop applications built with WinUI 3 and the Windows App SDK.
  name: Windows App SDK
jsonld:
- class_count: 3
  name: Microsoft Edge Addons Api Context
  property_count: 13
  slug: microsoft-edge-addons-api-context
- class_count: 3
  name: Microsoft Edge Devtools Api Context
  property_count: 16
  slug: microsoft-edge-devtools-api-context
layout: provider
modified: '2026-04-18'
name: Microsoft Edge
rules:
- name: Microsoft Edge API Rules
  rule_count: 27
  severity_counts:
    error: 15
    hint: 0
    info: 0
    warn: 12
  slug: microsoft-edge-spectral-rules
skills: []
slug: microsoft-edge
solutions: []
source_filename: apis.yml
source_yaml: "aid: microsoft-edge\nname: Microsoft Edge\ndescription: >-\n  APIs and resources for Microsoft Edge browser development and integration,\n  including the Edge Add-ons API for extension management, DevTools Protocol\n  for browser debugging and automation, Extensions API for building browser\n  extensions, and Web Platform APIs for progressive web app development.\nimage: https://www.microsoft.com/edge/favicon.ico\nurl: https://www.microsoft.com/edge\nhumanURL: https://developer.microsoft.com/microsoft-edge/\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\nposition: Consumer\naccess: 3rd-Party\ntags:\n  - Browser\n  - Chromium\n  - Developer Tools\n  - Edge\n  - Extensions\n  - Microsoft\n  - Progressive Web Apps\n  - Web Development\n  - WebView\napis:\n  - aid: microsoft-edge:edge-addons-api\n    name: Microsoft Edge Add-ons API\n    description: >-\n      REST API for managing Microsoft Edge browser extensions through the\n      Partner\
  \ Center. Enables programmatic publishing, updating, and managing\n      Edge extensions in the Microsoft Edge Add-ons store, supporting the\n      full extension lifecycle from upload to publication.\n    image: https://docs.microsoft.com/en-us/media/logos/logo_edge.svg\n    humanURL: https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/publish/api/using-addons-api\n    baseURL: https://api.addons.microsoftedge.microsoft.com\n    tags:\n      - Add-Ons\n      - Browser Extensions\n      - Extension Publishing\n      - Package Management\n      - Partner Center\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/publish/api/using-addons-api\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/publish/api/using-addons-api#before-you-begin\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/publish/api/addons-api-reference\n\
  \      - type: Authentication\n        url: https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/publish/api/using-addons-api#registering-the-client-application-in-azure-active-directory\n      - type: OpenAPI\n        url: openapi/microsoft-edge-addons-api.yaml\n      - type: JSONSchema\n        url: json-schema/addons-api-product-schema.json\n        title: Product Schema\n      - type: JSONSchema\n        url: json-schema/addons-api-submission-schema.json\n        title: Submission Schema\n      - type: JSONSchema\n        url: json-schema/addons-api-product-list-schema.json\n        title: Product List Schema\n      - type: JSONSchema\n        url: json-schema/addons-api-package-upload-result-schema.json\n        title: Package Upload Result Schema\n      - type: JSONLD\n        url: json-ld/microsoft-edge-addons-api-context.jsonld\n      - type: JSONSchema\n        url: json-structure/addons-api-product-structure.json\n        title: JSON Structure\n      - type: JSONSchema\n\
  \        url: json-structure/addons-api-submission-structure.json\n        title: JSON Structure\n      - type: JSONSchema\n        url: json-structure/addons-api-product-list-structure.json\n        title: JSON Structure\n      - type: JSONSchema\n        url: json-structure/addons-api-package-upload-result-structure.json\n        title: JSON Structure\n      - type: CodeExamples\n        url: examples/addons-api-product-example.json\n      - type: CodeExamples\n        url: examples/addons-api-product-list-example.json\n      - type: CodeExamples\n        url: examples/addons-api-submission-example.json\n      - type: CodeExamples\n        url: examples/addons-api-package-upload-result-example.json\n  - aid: microsoft-edge:edge-devtools-api\n    name: Microsoft Edge DevTools Protocol HTTP API\n    description: >-\n      HTTP endpoints for the Microsoft Edge DevTools Protocol, based on the\n      Chromium DevTools Protocol. These endpoints allow programmatic discovery\n      and management\
  \ of debuggable browser targets including pages, service\n      workers, and extensions.\n    image: https://docs.microsoft.com/en-us/media/logos/logo_edge.svg\n    humanURL: https://learn.microsoft.com/en-us/microsoft-edge/devtools-protocol-chromium/\n    baseURL: http://localhost:9222\n    tags:\n      - Automation\n      - Browser Debugging\n      - DevTools\n      - Remote Debugging\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoft-edge/devtools-protocol-chromium/\n      - type: APIReference\n        url: https://chromedevtools.github.io/devtools-protocol/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/microsoft-edge/devtools-protocol-chromium/\n      - type: OpenAPI\n        url: openapi/microsoft-edge-devtools-api.yaml\n      - type: JSONSchema\n        url: json-schema/devtools-api-target-schema.json\n        title: Target Schema\n      - type: JSONSchema\n        url: json-schema/devtools-api-browser-version-schema.json\n\
  \        title: Browser Version Schema\n      - type: JSONSchema\n        url: json-schema/devtools-api-protocol-schema-schema.json\n        title: Protocol Schema Schema\n      - type: JSONLD\n        url: json-ld/microsoft-edge-devtools-api-context.jsonld\n      - type: JSONSchema\n        url: json-structure/devtools-api-target-structure.json\n        title: JSON Structure\n      - type: JSONSchema\n        url: json-structure/devtools-api-browser-version-structure.json\n        title: JSON Structure\n      - type: JSONSchema\n        url: json-structure/devtools-api-protocol-schema-structure.json\n        title: JSON Structure\n      - type: CodeExamples\n        url: examples/devtools-api-target-example.json\n      - type: CodeExamples\n        url: examples/devtools-api-browser-version-example.json\n      - type: CodeExamples\n        url: examples/devtools-api-protocol-schema-example.json\n  - aid: microsoft-edge:edge-extensions-api\n    name: Microsoft Edge Extensions API\n   \
  \ description: >-\n      Build browser extensions for Microsoft Edge using the Chromium-based\n      extensions platform. Supports the WebExtensions API standard for\n      cross-browser compatibility.\n    image: https://docs.microsoft.com/en-us/media/logos/logo_edge.svg\n    humanURL: https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/\n    baseURL: https://microsoftedge.microsoft.com/addons\n    tags:\n      - Add-Ons\n      - Browser Extensions\n      - Chromium Extensions\n      - Web Extensions\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/getting-started/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/developer-guide/api-support\n      - type: Tutorials\n        url: https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/getting-started/part1-simple-extension\n\
  \  - aid: microsoft-edge:edge-web-platform-apis\n    name: Microsoft Edge Web Platform APIs\n    description: >-\n      Modern web APIs and standards supported in Microsoft Edge, including\n      Progressive Web App capabilities, Web Components, and emerging\n      web platform features.\n    image: https://docs.microsoft.com/en-us/media/logos/logo_edge.svg\n    humanURL: https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/\n    baseURL: https://www.microsoft.com/edge\n    tags:\n      - Progressive Web Apps\n      - PWA\n      - Web Platform\n      - Web Standards\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/how-to/\n      - type: ReleaseNotes\n        url: https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/whats-new/\n\
  common:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/microsoft-edge/\n    name: Microsoft Edge Documentation\n  - type: DeveloperPortal\n    url: https://developer.microsoft.com/microsoft-edge/\n    name: Microsoft Edge Developer Portal\n  - type: Blog\n    url: https://blogs.windows.com/msedgedev/\n    name: Microsoft Edge Blog\n  - type: GitHubOrganization\n    url: https://github.com/MicrosoftEdge\n    name: MicrosoftEdge GitHub Organization\n  - type: GitHubRepository\n    url: https://github.com/MicrosoftEdge/WebView2Samples\n    name: WebView2 Samples Repository\n  - type: GitHubRepository\n    url: https://github.com/nicedoc/nicedoc.io\n    name: Microsoft Edge DevTools Repository\n  - type: Support\n    url: https://learn.microsoft.com/en-us/microsoft-edge/devtools-guide-chromium/\n    name: Microsoft Edge DevTools Documentation\n  - type: ReleaseNotes\n    url: https://learn.microsoft.com/en-us/microsoft-edge/web-platform/release-notes/\n    name: Microsoft\
  \ Edge Release Notes\n  - type: ChangeLog\n    url: https://learn.microsoft.com/en-us/deployedge/microsoft-edge-relnote-stable-channel\n    name: Microsoft Edge Stable Channel Release Notes\n  - type: StatusPage\n    url: https://developer.microsoft.com/en-us/microsoft-edge/status/\n    name: Microsoft Edge Platform Status\n  - type: X\n    url: https://twitter.com/MSEdgeDev\n    name: Microsoft Edge Dev on X\n  - type: TermsOfService\n    url: https://www.microsoft.com/legal/terms-of-use\n    name: Microsoft Terms of Use\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/privacystatement\n    name: Microsoft Privacy Statement\n  - type: SDK\n    url: https://www.nuget.org/packages/Microsoft.Web.WebView2\n    name: WebView2 SDK (NuGet)\n  - type: SignUp\n    url: https://partner.microsoft.com/dashboard/microsoftedge/\n    name: Microsoft Edge Partner Center\n  - type: Login\n    url: https://partner.microsoft.com/dashboard/\n    name: Microsoft Partner Center Login\n  - type:\
  \ Marketplace\n    url: https://microsoftedge.microsoft.com/addons/\n    name: Microsoft Edge Add-ons Store\n  - type: JSONLD\n    url: json-ld/microsoft-edge-devtools-api-context.jsonld\n    title: DevTools API Context\n  - type: JSONLD\n    url: json-ld/microsoft-edge-addons-api-context.jsonld\n    title: Add-ons API Context\n  - type: SpectralRules\n    url: rules/microsoft-edge-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/browser-development.yaml\n    title: Browser Development Workflow\n  - type: NaftikoCapability\n    url: capabilities/shared/devtools-api.yaml\n    title: DevTools API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/shared/addons-api.yaml\n    title: Add-ons API Shared Definition\n  - type: Vocabulary\n    url: vocabulary/microsoft-edge-vocabulary.yaml\n  - type: Features\n    name: Features\n    data:\n      - name: Extension Publishing API\n        description: Programmatically publish, update, and manage browser extensions\
  \ in the Edge Add-ons store via REST API.\n      - name: Remote Debugging Protocol\n        description: Debug and inspect web pages, service workers, and extensions using the Chrome DevTools Protocol over WebSocket.\n      - name: WebView2 Embedding\n        description: Embed Microsoft Edge rendering engine in native desktop applications using the WebView2 SDK.\n      - name: Progressive Web App Support\n        description: Build installable PWAs with offline capability, push notifications, and system integration.\n      - name: Cross-Browser Extension Compatibility\n        description: Build extensions using the Chromium WebExtensions API standard for cross-browser portability.\n      - name: Browser Automation\n        description: Automate browser tasks including page navigation, target management, and performance profiling.\n      - name: Extension Sideloading\n        description: Load and test unpacked extensions locally during development without publishing to the store.\n \
  \     - name: Manifest V3 Support\n        description: Build extensions using the latest Manifest V3 specification with service workers and declarative APIs.\n  - type: UseCases\n    name: Use Cases\n    data:\n      - name: Automated Extension Deployment\n        description: Use the Add-ons API to automate CI/CD pipelines for publishing and updating browser extensions.\n      - name: Browser Testing and QA\n        description: Leverage DevTools Protocol for automated browser testing, performance auditing, and regression detection.\n      - name: Custom Browser Controls\n        description: Embed Edge rendering in desktop applications for custom browser experiences using WebView2.\n      - name: Enterprise Content Filtering\n        description: Build enterprise extensions for content filtering, security policy enforcement, and compliance monitoring.\n      - name: Web Scraping and Data Extraction\n        description: Use DevTools Protocol to programmatically navigate pages and extract\
  \ structured data.\n      - name: Accessibility Testing\n        description: Automate accessibility audits using DevTools Protocol to inspect DOM, ARIA attributes, and contrast ratios.\n      - name: Performance Monitoring\n        description: Collect real-time performance metrics, network traces, and JavaScript profiling data via DevTools Protocol.\n      - name: Progressive Web App Distribution\n        description: Build and distribute PWAs through the Microsoft Store with native-like installation and system integration.\n  - type: Integrations\n    name: Integrations\n    data:\n      - name: Azure Active Directory\n        description: Authenticate to the Edge Add-ons API using Azure AD OAuth 2.0 client credentials flow.\n      - name: Microsoft Partner Center\n        description: Manage extension listings, submissions, and analytics through the Partner Center dashboard.\n      - name: Visual Studio Code\n        description: Debug Edge browser content directly from VS Code using\
  \ the Edge DevTools extension.\n      - name: Selenium WebDriver\n        description: Automate Microsoft Edge browser for testing using Selenium with the Edge WebDriver.\n      - name: Playwright\n        description: Cross-browser automation framework with first-class support for Microsoft Edge testing.\n      - name: Puppeteer\n        description: Control headless Microsoft Edge instances programmatically using the Puppeteer Node.js library.\n      - name: GitHub Actions\n        description: Automate extension publishing and browser testing in CI/CD workflows using GitHub Actions.\n      - name: Windows App SDK\n        description: Integrate WebView2 into Windows desktop applications built with WinUI 3 and the Windows App SDK.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-edge/refs/heads/main/apis.yml
tags:
- Browser
- Chromium
- Developer Tools
- Edge
- Extensions
- Microsoft
- Progressive Web Apps
- Web Development
- WebView
url: https://www.microsoft.com/edge
use_cases:
- description: Use the Add-ons API to automate CI/CD pipelines for publishing and updating browser extensions.
  name: Automated Extension Deployment
- description: Leverage DevTools Protocol for automated browser testing, performance auditing, and regression detection.
  name: Browser Testing and QA
- description: Embed Edge rendering in desktop applications for custom browser experiences using WebView2.
  name: Custom Browser Controls
- description: Build enterprise extensions for content filtering, security policy enforcement, and compliance monitoring.
  name: Enterprise Content Filtering
- description: Use DevTools Protocol to programmatically navigate pages and extract structured data.
  name: Web Scraping and Data Extraction
- description: Automate accessibility audits using DevTools Protocol to inspect DOM, ARIA attributes, and contrast ratios.
  name: Accessibility Testing
- description: Collect real-time performance metrics, network traces, and JavaScript profiling data via DevTools Protocol.
  name: Performance Monitoring
- description: Build and distribute PWAs through the Microsoft Store with native-like installation and system integration.
  name: Progressive Web App Distribution
---
