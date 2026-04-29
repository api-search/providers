---
api_count: 4
apis:
- description: The main Appium server API that implements the W3C WebDriver protocol for mobile, web, desktop, and TV app automation. Supports session management, element interaction, actions, screenshots, and Appiu
  name: Appium Server API
  slug: ''
- description: Standalone GUI inspector for mobile apps that communicates with an Appium server, enabling visual element inspection and XPath generation for test authoring.
  name: Appium Inspector
  slug: ''
- description: The primary Appium driver for Android automation, backed by Google's UiAutomator2 framework. Supports Android 5.0+ devices and emulators.
  name: Appium UiAutomator2 Driver
  slug: ''
- description: The primary Appium driver for iOS and tvOS automation, backed by Apple's XCTest framework. Supports iOS 12+ and macOS Sequoia.
  name: Appium XCUITest Driver
  slug: ''
capabilities:
- description: Workflow capability for mobile app test automation using Appium. Combines session management, element interaction, device control, and screenshot capture into a unified automation workflow for QA engi
  name: Appium Mobile Test Automation
  slug: mobile-test-automation
common:
- title: ''
  type: GettingStarted
  url: https://appium.io/docs/en/latest/quickstart/
- title: ''
  type: GitHubOrganization
  url: https://github.com/appium
- title: ''
  type: Documentation
  url: https://appium.io/docs/en/latest/
- title: ''
  type: Support
  url: https://discuss.appium.io/
- title: ''
  type: Slack
  url: http://appium.slack.com
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/appium
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/AppiumConf
- title: ''
  type: ChangeLog
  url: https://github.com/appium/appium/blob/master/CHANGELOG.md
- title: Python Client
  type: SDK
  url: https://github.com/appium/python-client
- title: Java Client
  type: SDK
  url: https://github.com/appium/java-client
- title: Ruby Client
  type: SDK
  url: https://github.com/appium/ruby_lib_core
- title: .NET Client
  type: SDK
  url: https://github.com/appium/dotnet-client
- title: MCP Server
  type: Tools
  url: https://github.com/appium/appium-mcp
- title: ''
  type: SpectralRules
  url: rules/appium-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/appium-vocabulary.yaml
- title: Appium Server Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/appium-server.yaml
- title: Mobile Test Automation Workflow
  type: NaftikoCapability
  url: capabilities/mobile-test-automation.yaml
created: '2024-01-15'
description: Appium is an open-source test automation framework governed by the OpenJS Foundation, designed to facilitate UI automation of many app platforms including mobile (iOS, Android), browser (Chrome, Firefox, Safari), desktop (macOS, Windows), and TV (Roku, tvOS, Android TV). It implements the W3C WebDriver protocol and provides an extensible ecosystem of drivers, clients, and plugins.
features:
- description: Automate iOS, Android, Windows, macOS, web browsers, and TV platforms from a single framework
  name: Multi-Platform Support
- description: Implements the W3C WebDriver protocol for standard, cross-platform automation
  name: WebDriver Protocol
- description: Plugin-based driver system supports any platform through community and official drivers
  name: Extensible Driver Architecture
- description: Official client libraries for Python, Java, JavaScript, Ruby, .NET, and more
  name: Multiple Language Clients
- description: Supports the next-generation WebDriver BiDi bidirectional protocol
  name: WebDriver BiDi Support
- description: Model Context Protocol server for AI-assisted test automation
  name: MCP Server
- description: Visual app inspector for element discovery and XPath/accessibility ID generation
  name: Inspector GUI
image: https://appium.io/docs/en/latest/assets/images/appium-logo.png
integrations:
- description: Cloud device farm integration for running Appium tests on real devices
  name: BrowserStack
- description: Cloud testing platform with Appium support for real and virtual devices
  name: Sauce Labs
- description: Cloud test execution platform with Appium integration
  name: LambdaTest
- description: Java testing framework commonly used with Appium Java client
  name: TestNG
- description: Python testing framework used with the Appium Python client
  name: pytest
- description: JavaScript test automation framework with built-in Appium support
  name: WebdriverIO
- description: Distributed test execution grid compatible with Appium sessions
  name: Selenium Grid
jsonld:
- class_count: 7
  name: Appium Server Context
  property_count: 15
  slug: appium-server-context
layout: provider
modified: '2026-04-19'
name: Appium
rules:
- name: Appium API Rules
  rule_count: 27
  severity_counts:
    error: 10
    hint: 0
    info: 2
    warn: 15
  slug: appium-spectral-rules
skills: []
slug: appium
solutions: []
source_yaml: "name: Appium\ndescription: >-\n  Appium is an open-source test automation framework governed by the OpenJS Foundation,\n  designed to facilitate UI automation of many app platforms including mobile (iOS, Android),\n  browser (Chrome, Firefox, Safari), desktop (macOS, Windows), and TV (Roku, tvOS, Android TV).\n  It implements the W3C WebDriver protocol and provides an extensible ecosystem of drivers,\n  clients, and plugins.\nimage: https://appium.io/docs/en/latest/assets/images/appium-logo.png\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.18'\nurl: https://appium.io/apis.json\napis:\n  - name: Appium Server API\n    description: >-\n      The main Appium server API that implements the W3C WebDriver protocol for mobile,\n      web, desktop, and TV app automation. Supports session management, element interaction,\n      actions, screenshots, and Appium-specific device commands.\n    image: https://appium.io/docs/en/latest/assets/images/appium-logo.png\n\
  \    humanURL: https://appium.io/\n    baseURL: http://localhost:4723\n    tags:\n      - Android\n      - Automation\n      - iOS\n      - Mobile Testing\n      - WebDriver\n    properties:\n      - type: Documentation\n        url: https://appium.io/docs/en/latest/\n      - type: OpenAPI\n        url: openapi/appium-server-openapi.yaml\n      - type: GitHubRepository\n        url: https://github.com/appium/appium\n      - type: APIReference\n        url: https://appium.io/docs/en/latest/reference/\n      - type: JSONSchema\n        url: json-schema/appium-server-session-info-schema.json\n        title: Session Info Schema\n      - type: JSONSchema\n        url: json-schema/appium-server-find-element-request-schema.json\n        title: Find Element Request Schema\n      - type: JSONSchema\n        url: json-schema/appium-server-app-id-request-schema.json\n        title: App ID Request Schema\n      - type: JSONSchema\n        url: json-schema/appium-server-action-sequence-schema.json\n\
  \        title: Action Sequence Schema\n      - type: JSONSchema\n        url: json-schema/appium-server-cookie-schema.json\n        title: Cookie Schema\n      - type: JSONSchema\n        url: json-schema/appium-server-error-response-schema.json\n        title: Error Response Schema\n  - name: Appium Inspector\n    description: >-\n      Standalone GUI inspector for mobile apps that communicates with an Appium server,\n      enabling visual element inspection and XPath generation for test authoring.\n    humanURL: https://github.com/appium/appium-inspector\n    baseURL: https://github.com/appium/appium-inspector/releases\n    tags:\n      - Debugging\n      - GUI\n      - Inspector\n      - Mobile Testing\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/appium/appium-inspector\n      - type: SDK\n        url: https://github.com/appium/appium-inspector/releases\n        title: Desktop App Downloads\n  - name: Appium UiAutomator2 Driver\n    description:\
  \ >-\n      The primary Appium driver for Android automation, backed by Google's UiAutomator2\n      framework. Supports Android 5.0+ devices and emulators.\n    humanURL: https://github.com/appium/appium-uiautomator2-driver\n    baseURL: http://localhost:4723\n    tags:\n      - Android\n      - Automation\n      - Driver\n      - Mobile Testing\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/appium/appium-uiautomator2-driver\n      - type: Documentation\n        url: https://github.com/appium/appium-uiautomator2-driver#readme\n  - name: Appium XCUITest Driver\n    description: >-\n      The primary Appium driver for iOS and tvOS automation, backed by Apple's XCTest\n      framework. Supports iOS 12+ and macOS Sequoia.\n    humanURL: https://github.com/appium/appium-xcuitest-driver\n    baseURL: http://localhost:4723\n    tags:\n      - Automation\n      - Driver\n      - iOS\n      - Mobile Testing\n      - tvOS\n    properties:\n      - type: GitHubRepository\n\
  \        url: https://github.com/appium/appium-xcuitest-driver\n      - type: Documentation\n        url: https://github.com/appium/appium-xcuitest-driver#readme\nmaintainers:\n  - FN: Appium Contributors\n    email: appium@googlegroups.com\n    url: https://github.com/appium/appium/graphs/contributors\ntags:\n  - Android\n  - Cross-Platform\n  - iOS\n  - Mobile Testing\n  - Open Source\n  - OpenJS Foundation\n  - Test Automation\n  - WebDriver\ncommon:\n  - type: GettingStarted\n    url: https://appium.io/docs/en/latest/quickstart/\n  - type: GitHubOrganization\n    url: https://github.com/appium\n  - type: Documentation\n    url: https://appium.io/docs/en/latest/\n  - type: Support\n    url: https://discuss.appium.io/\n  - type: Slack\n    url: http://appium.slack.com\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/appium\n  - type: YouTube\n    url: https://www.youtube.com/c/AppiumConf\n  - type: ChangeLog\n    url: https://github.com/appium/appium/blob/master/CHANGELOG.md\n\
  \  - type: SDK\n    url: https://github.com/appium/python-client\n    title: Python Client\n  - type: SDK\n    url: https://github.com/appium/java-client\n    title: Java Client\n  - type: SDK\n    url: https://github.com/appium/ruby_lib_core\n    title: Ruby Client\n  - type: SDK\n    url: https://github.com/appium/dotnet-client\n    title: .NET Client\n  - type: Tools\n    url: https://github.com/appium/appium-mcp\n    title: MCP Server\n  - type: SpectralRules\n    url: rules/appium-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/appium-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/appium-server.yaml\n    title: Appium Server Shared Capability\n  - type: NaftikoCapability\n    url: capabilities/mobile-test-automation.yaml\n    title: Mobile Test Automation Workflow\n  - type: Features\n    data:\n      - name: Multi-Platform Support\n        description: Automate iOS, Android, Windows, macOS, web browsers, and TV platforms from a single framework\n\
  \      - name: WebDriver Protocol\n        description: Implements the W3C WebDriver protocol for standard, cross-platform automation\n      - name: Extensible Driver Architecture\n        description: Plugin-based driver system supports any platform through community and official drivers\n      - name: Multiple Language Clients\n        description: Official client libraries for Python, Java, JavaScript, Ruby, .NET, and more\n      - name: WebDriver BiDi Support\n        description: Supports the next-generation WebDriver BiDi bidirectional protocol\n      - name: MCP Server\n        description: Model Context Protocol server for AI-assisted test automation\n      - name: Inspector GUI\n        description: Visual app inspector for element discovery and XPath/accessibility ID generation\n  - type: UseCases\n    data:\n      - name: Mobile App Testing\n        description: Automated functional and regression testing of iOS and Android native apps\n      - name: Cross-Platform Test Suites\n\
  \        description: Single test codebase targeting multiple platforms and devices\n      - name: CI/CD Integration\n        description: Running automated mobile tests in continuous integration pipelines\n      - name: Web Automation\n        description: Browser automation on mobile and desktop via WebDriver\n      - name: AI-Assisted Testing\n        description: Using the MCP server to enable AI agents to drive test execution\n  - type: Integrations\n    data:\n      - name: BrowserStack\n        description: Cloud device farm integration for running Appium tests on real devices\n      - name: Sauce Labs\n        description: Cloud testing platform with Appium support for real and virtual devices\n      - name: LambdaTest\n        description: Cloud test execution platform with Appium integration\n      - name: TestNG\n        description: Java testing framework commonly used with Appium Java client\n      - name: pytest\n        description: Python testing framework used with the\
  \ Appium Python client\n      - name: WebdriverIO\n        description: JavaScript test automation framework with built-in Appium support\n      - name: Selenium Grid\n        description: Distributed test execution grid compatible with Appium sessions\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/appium/refs/heads/main/apis.yml
tags:
- Android
- Cross-Platform
- iOS
- Mobile Testing
- Open Source
- OpenJS Foundation
- Test Automation
- WebDriver
url: https://appium.io/apis.json
use_cases:
- description: Automated functional and regression testing of iOS and Android native apps
  name: Mobile App Testing
- description: Single test codebase targeting multiple platforms and devices
  name: Cross-Platform Test Suites
- description: Running automated mobile tests in continuous integration pipelines
  name: CI/CD Integration
- description: Browser automation on mobile and desktop via WebDriver
  name: Web Automation
- description: Using the MCP server to enable AI agents to drive test execution
  name: AI-Assisted Testing
---
