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
