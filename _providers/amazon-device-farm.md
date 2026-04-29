---
api_count: 1
apis:
- description: 'The AWS Device Farm API enables programmatic access to create and manage test runs, device pools, projects, and jobs for testing mobile and web applications across real devices and browsers. Supports '
  name: AWS Device Farm API
  slug: ''
capabilities:
- description: Workflow capability for QA engineers and mobile developers to run automated tests on real physical devices and desktop browsers using AWS Device Farm. Combines project management, device pool configur
  name: AWS Device Farm Mobile and Browser Testing
  slug: mobile-browser-testing
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/device-farm/
- title: ''
  type: Website
  url: https://aws.amazon.com/device-farm/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/devicefarm/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/mobile/category/mobile-services/aws-device-farm/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/devicefarm/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-device-farm-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-device-farm-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/mobile-browser-testing.yaml
created: '2026-03-16'
description: AWS Device Farm is an application testing service that lets you improve the quality of your web and mobile apps by testing them across an extensive range of desktop browsers and real mobile devices without having to provision and manage any testing infrastructure.
features:
- description: Test mobile apps on thousands of real physical Android and iOS devices without managing any device infrastructure.
  name: Real Device Testing
- description: Test web applications on desktop browsers using Selenium RemoteWebDriver through Device Farm's test grid.
  name: Desktop Browser Testing
- description: Supports popular test frameworks including Appium, XCTest, Espresso, Calabash, and built-in fuzz testing.
  name: Automated Test Frameworks
- description: Interactively access real devices via remote desktop to manually test and debug your app.
  name: Remote Access Sessions
- description: Simulate different network conditions including bandwidth, latency, and packet loss using network profiles.
  name: Network Condition Simulation
- description: Provision and manage private dedicated devices for exclusive use in testing your applications.
  name: Private Device Fleet
- description: Test apps hosted in private VPCs using VPC endpoint configurations without exposing them publicly.
  name: VPC Integration
- description: Run tests in parallel across multiple devices simultaneously to reduce overall testing time.
  name: Parallel Test Execution
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Integrate Device Farm tests as a stage in your CodePipeline CI/CD pipelines for automated testing.
  name: AWS CodePipeline
- description: Trigger Device Farm test runs from CodeBuild projects as part of build and deploy workflows.
  name: AWS CodeBuild
- description: Run Device Farm tests from Jenkins CI using the AWS Device Farm plugin for Jenkins.
  name: Jenkins
- description: Supports Appium test scripts for both Android and iOS cross-platform mobile testing.
  name: Appium
- description: Integrates with Selenium RemoteWebDriver for automated desktop browser testing.
  name: Selenium
- description: Trigger Device Farm test runs using the AWS Device Farm GitHub Action in your workflows.
  name: GitHub Actions
jsonld:
- class_count: 29
  name: Amazon Device Farm Context
  property_count: 115
  slug: amazon-device-farm-context
layout: provider
modified: '2026-04-19'
name: Amazon Device Farm
rules:
- name: Amazon Device Farm API Rules
  rule_count: 24
  severity_counts:
    error: 12
    hint: 0
    info: 4
    warn: 8
  slug: amazon-device-farm-spectral-rules
skills: []
slug: amazon-device-farm
solutions: []
source_yaml: "name: Amazon Device Farm\ndescription: >-\n  AWS Device Farm is an application testing service that lets you improve the\n  quality of your web and mobile apps by testing them across an extensive range\n  of desktop browsers and real mobile devices without having to provision and\n  manage any testing infrastructure.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/device-farm/\ncreated: '2026-03-16'\nmodified: '2026-04-19'\napis:\n  - name: AWS Device Farm API\n    description: >-\n      The AWS Device Farm API enables programmatic access to create and manage\n      test runs, device pools, projects, and jobs for testing mobile and web\n      applications across real devices and browsers. Supports 77 operations\n      covering projects, runs, devices, uploads, remote access sessions, Selenium\n      test grid, network profiles, instance profiles, VPC endpoint configurations,\n      and resource tagging.\n    humanURL:\
  \ https://aws.amazon.com/device-farm/\n    baseURL: https://devicefarm.amazonaws.com\n    tags:\n      - Application Testing\n      - Device Management\n      - Mobile Testing\n      - Quality Assurance\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/devicefarm/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-device-farm-openapi.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/device-farm/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/device-farm/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/device-farm/faqs/\n      - type: JSONSchema\n        url: json-schema/amazon-device-farm-project-schema.json\n      - type: JSONSchema\n        url: json-schema/amazon-device-farm-run-schema.json\n      - type: JSONSchema\n        url: json-schema/amazon-device-farm-device-schema.json\n      - type: JSONSchema\n        url: json-schema/amazon-device-farm-upload-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/amazon-device-farm-device-pool-schema.json\n      - type: JSONStructure\n        url: json-structure/amazon-device-farm-project-structure.json\n      - type: JSONStructure\n        url: json-structure/amazon-device-farm-run-structure.json\n      - type: JSONStructure\n        url: json-structure/amazon-device-farm-device-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-device-farm-context.jsonld\n      - type: Example\n        url: examples/amazon-device-farm-project-example.json\n      - type: Example\n        url: examples/amazon-device-farm-run-example.json\n      - type: Example\n        url: examples/amazon-device-farm-device-example.json\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/device-farm/\n  - type: Website\n    url: https://aws.amazon.com/device-farm/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/devicefarm/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n\
  \  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/mobile/category/mobile-services/aws-device-farm/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/devicefarm/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-device-farm-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-device-farm-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/mobile-browser-testing.yaml\n  - type: Features\n    data:\n      - name: Real Device Testing\n        description: Test mobile apps on thousands\
  \ of real physical Android and iOS devices without managing any device infrastructure.\n      - name: Desktop Browser Testing\n        description: Test web applications on desktop browsers using Selenium RemoteWebDriver through Device Farm's test grid.\n      - name: Automated Test Frameworks\n        description: Supports popular test frameworks including Appium, XCTest, Espresso, Calabash, and built-in fuzz testing.\n      - name: Remote Access Sessions\n        description: Interactively access real devices via remote desktop to manually test and debug your app.\n      - name: Network Condition Simulation\n        description: Simulate different network conditions including bandwidth, latency, and packet loss using network profiles.\n      - name: Private Device Fleet\n        description: Provision and manage private dedicated devices for exclusive use in testing your applications.\n      - name: VPC Integration\n        description: Test apps hosted in private VPCs using VPC endpoint\
  \ configurations without exposing them publicly.\n      - name: Parallel Test Execution\n        description: Run tests in parallel across multiple devices simultaneously to reduce overall testing time.\n  - type: UseCases\n    data:\n      - name: Mobile App Quality Assurance\n        description: Validate mobile app functionality, performance, and compatibility across a wide range of real Android and iOS devices.\n      - name: Cross-Device Compatibility Testing\n        description: Ensure your app behaves correctly on different device manufacturers, screen sizes, OS versions, and hardware configurations.\n      - name: Web Application Browser Testing\n        description: Run Selenium-based browser tests against your web application across multiple desktop browser environments.\n      - name: CI/CD Test Integration\n        description: Integrate device testing into your continuous integration and deployment pipelines for automated quality gates.\n      - name: App Performance Benchmarking\n\
  \        description: Measure app performance metrics including CPU usage, memory consumption, and network activity across different devices.\n  - type: Integrations\n    data:\n      - name: AWS CodePipeline\n        description: Integrate Device Farm tests as a stage in your CodePipeline CI/CD pipelines for automated testing.\n      - name: AWS CodeBuild\n        description: Trigger Device Farm test runs from CodeBuild projects as part of build and deploy workflows.\n      - name: Jenkins\n        description: Run Device Farm tests from Jenkins CI using the AWS Device Farm plugin for Jenkins.\n      - name: Appium\n        description: Supports Appium test scripts for both Android and iOS cross-platform mobile testing.\n      - name: Selenium\n        description: Integrates with Selenium RemoteWebDriver for automated desktop browser testing.\n      - name: GitHub Actions\n        description: Trigger Device Farm test runs using the AWS Device Farm GitHub Action in your workflows.\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Application Testing\n  - AWS\n  - Device Testing\n  - Mobile Testing\n  - Quality Assurance\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-device-farm/refs/heads/main/apis.yml
tags:
- Application Testing
- AWS
- Device Testing
- Mobile Testing
- Quality Assurance
url: https://aws.amazon.com/device-farm/
use_cases:
- description: Validate mobile app functionality, performance, and compatibility across a wide range of real Android and iOS devices.
  name: Mobile App Quality Assurance
- description: Ensure your app behaves correctly on different device manufacturers, screen sizes, OS versions, and hardware configurations.
  name: Cross-Device Compatibility Testing
- description: Run Selenium-based browser tests against your web application across multiple desktop browser environments.
  name: Web Application Browser Testing
- description: Integrate device testing into your continuous integration and deployment pipelines for automated quality gates.
  name: CI/CD Test Integration
- description: Measure app performance metrics including CPU usage, memory consumption, and network activity across different devices.
  name: App Performance Benchmarking
---
