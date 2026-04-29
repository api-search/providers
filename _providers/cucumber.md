---
api_count: 5
apis:
- description: Java/JVM implementation of Cucumber supporting Java, Kotlin, Scala, and other JVM languages. Distributed via Maven Central under the io.cucumber group.
  name: Cucumber JVM
  slug: cucumber-jvm
- description: JavaScript/Node.js implementation of Cucumber for running BDD tests in Node and the browser. Distributed as @cucumber/cucumber on npm.
  name: Cucumber.js
  slug: cucumber-js
- description: Ruby implementation of Cucumber, the original Cucumber project. Distributed as the cucumber gem on RubyGems.
  name: Cucumber Ruby
  slug: cucumber-ruby
- description: Gherkin is the language used to write Cucumber feature files. Parsers are published per language and emit Cucumber Messages that downstream tools consume.
  name: Gherkin
  slug: gherkin
- description: Protocol-buffer / JSON Schema specification of the messages exchanged between Cucumber components (parsers, runners, formatters). Implemented across all language ports for consistent reporting.
  name: Cucumber Messages
  slug: cucumber-messages
common:
- title: ''
  type: Website
  url: https://cucumber.io
- title: ''
  type: Documentation
  url: https://cucumber.io/docs
- title: ''
  type: Reference
  url: https://cucumber.io/docs/gherkin/reference/
- title: ''
  type: School
  url: https://school.cucumber.io
- title: ''
  type: Tools
  url: https://cucumber.io/tools
- title: ''
  type: GitHubOrganization
  url: https://github.com/cucumber
- title: ''
  type: X
  url: https://twitter.com/cucumberbdd
- title: ''
  type: Slack
  url: https://cucumber.io/community#slack
- title: ''
  type: YouTube
  url: https://www.youtube.com/channel/UCVhQ7ulinkFAkUx3eNvzoEg
- title: ''
  type: JSONSchema
  url: json-schema/cucumber-message-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/cucumber-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/cucumber-vocabulary.yml
created: '2024-01-01'
description: Cucumber is an open-source Behavior Driven Development (BDD) tool for running automated tests written in plain language using the Gherkin syntax. It enables collaboration between technical and non-technical team members by expressing executable specifications as Given/When/Then scenarios. Cucumber has implementations for many languages (JVM, JavaScript, Ruby, .NET, Python, Go, Rust) and a shared message protocol that connects parsers, runners, and reporters.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 23
  name: Cucumber Context
  property_count: 2
  slug: cucumber-context
layout: provider
modified: '2026-04-28'
name: Cucumber
skills: []
slug: cucumber
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cucumber\nurl: https://raw.githubusercontent.com/api-evangelist/cucumber/refs/heads/main/apis.yml\nx-type: opensource\nname: Cucumber\ndescription: >-\n  Cucumber is an open-source Behavior Driven Development (BDD) tool for running\n  automated tests written in plain language using the Gherkin syntax. It\n  enables collaboration between technical and non-technical team members by\n  expressing executable specifications as Given/When/Then scenarios. Cucumber\n  has implementations for many languages (JVM, JavaScript, Ruby, .NET, Python,\n  Go, Rust) and a shared message protocol that connects parsers, runners, and\n  reporters.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - BDD\n  - Behavior Driven Development\n  - Gherkin\n  - Open Source\n  - Quality Assurance\n  - Test Framework\n  - Testing\ntype: Index\nspecificationVersion: '0.19'\ncreated: '2024-01-01'\nmodified: '2026-04-28'\napis:\n  - aid: cucumber:cucumber-jvm\n\
  \    name: Cucumber JVM\n    description: >-\n      Java/JVM implementation of Cucumber supporting Java, Kotlin, Scala, and\n      other JVM languages. Distributed via Maven Central under the io.cucumber\n      group.\n    humanURL: https://github.com/cucumber/cucumber-jvm\n    baseURL: https://github.com/cucumber/cucumber-jvm\n    tags:\n      - BDD\n      - Java\n      - JVM\n      - Kotlin\n      - Scala\n      - Testing\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/cucumber/cucumber-jvm\n      - type: Documentation\n        url: https://cucumber.io/docs/cucumber/\n      - type: PackageIndex\n        url: https://search.maven.org/search?q=g:io.cucumber\n  - aid: cucumber:cucumber-js\n    name: Cucumber.js\n    description: >-\n      JavaScript/Node.js implementation of Cucumber for running BDD tests in\n      Node and the browser. Distributed as @cucumber/cucumber on npm.\n    humanURL: https://github.com/cucumber/cucumber-js\n    baseURL: https://github.com/cucumber/cucumber-js\n\
  \    tags:\n      - BDD\n      - JavaScript\n      - Node.js\n      - Testing\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/cucumber/cucumber-js\n      - type: Documentation\n        url: https://github.com/cucumber/cucumber-js/blob/main/docs/\n      - type: PackageIndex\n        url: https://www.npmjs.com/package/@cucumber/cucumber\n  - aid: cucumber:cucumber-ruby\n    name: Cucumber Ruby\n    description: >-\n      Ruby implementation of Cucumber, the original Cucumber project. Distributed\n      as the cucumber gem on RubyGems.\n    humanURL: https://github.com/cucumber/cucumber-ruby\n    baseURL: https://github.com/cucumber/cucumber-ruby\n    tags:\n      - BDD\n      - Ruby\n      - Testing\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/cucumber/cucumber-ruby\n      - type: Documentation\n        url: https://cucumber.io/docs/cucumber/\n      - type: PackageIndex\n        url: https://rubygems.org/gems/cucumber\n\
  \  - aid: cucumber:gherkin\n    name: Gherkin\n    description: >-\n      Gherkin is the language used to write Cucumber feature files. Parsers\n      are published per language and emit Cucumber Messages that downstream\n      tools consume.\n    humanURL: https://github.com/cucumber/gherkin\n    tags:\n      - DSL\n      - Gherkin\n      - Parser\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/cucumber/gherkin\n      - type: Reference\n        url: https://cucumber.io/docs/gherkin/reference/\n  - aid: cucumber:cucumber-messages\n    name: Cucumber Messages\n    description: >-\n      Protocol-buffer / JSON Schema specification of the messages exchanged\n      between Cucumber components (parsers, runners, formatters). Implemented\n      across all language ports for consistent reporting.\n    humanURL: https://github.com/cucumber/messages\n    tags:\n      - Protocol\n      - JSON Schema\n      - Messages\n    properties:\n      - type: GitHubRepository\n\
  \        url: https://github.com/cucumber/messages\n      - type: JSONSchema\n        url: json-schema/cucumber-message-schema.json\nfeatures:\n  - name: Plain-Language Specifications\n    description: Tests written in Gherkin (Given/When/Then) readable by non-engineers.\n  - name: Multi-Language Implementations\n    description: First-class implementations for JVM, JavaScript, Ruby, .NET, Python, Go, and Rust.\n  - name: Step Definitions and Cucumber Expressions\n    description: Pattern-matched code bindings for Gherkin steps via regex or Cucumber Expressions.\n  - name: Hooks and Tags\n    description: Before/After hooks plus tag-driven scenario selection and configuration.\n  - name: Cucumber Messages Protocol\n    description: Shared message format for parsers, runners, and formatters across implementations.\n  - name: Pluggable Formatters\n    description: Built-in pretty, JSON, JUnit, and HTML reporters; third-party formatters supported.\n  - name: Parallel Execution\n    description:\
  \ Implementations support parallel scenario execution.\n  - name: CI Integration\n    description: Reports plug into CI systems (GitHub Actions, Jenkins, GitLab) via JUnit/HTML output.\nuseCases:\n  - name: Acceptance Testing\n    description: Product, QA, and engineering collaborate on acceptance tests written in Gherkin.\n  - name: Living Documentation\n    description: Feature files double as up-to-date documentation of system behavior.\n  - name: API Contract Testing\n    description: BDD scenarios verify external API contracts and integrations.\n  - name: Regression Suites\n    description: Tagged scenarios provide selectable regression suites for CI.\n  - name: Cross-Team Communication\n    description: Bridges product, QA, and engineering with a shared specification language.\ncommon:\n  - type: Website\n    url: https://cucumber.io\n  - type: Documentation\n    url: https://cucumber.io/docs\n  - type: Reference\n    url: https://cucumber.io/docs/gherkin/reference/\n  - type: School\n\
  \    url: https://school.cucumber.io\n  - type: Tools\n    url: https://cucumber.io/tools\n  - type: GitHubOrganization\n    url: https://github.com/cucumber\n  - type: X\n    url: https://twitter.com/cucumberbdd\n  - type: Slack\n    url: https://cucumber.io/community#slack\n  - type: YouTube\n    url: https://www.youtube.com/channel/UCVhQ7ulinkFAkUx3eNvzoEg\n  - type: JSONSchema\n    url: json-schema/cucumber-message-schema.json\n  - type: JSONLDContext\n    url: json-ld/cucumber-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/cucumber-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cucumber/refs/heads/main/apis.yml
tags:
- Automation
- BDD
- Behavior Driven Development
- Gherkin
- Open Source
- Quality Assurance
- Test Framework
- Testing
url: https://raw.githubusercontent.com/api-evangelist/cucumber/refs/heads/main/apis.yml
use_cases: []
---
