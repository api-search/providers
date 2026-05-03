---
api_count: 4
apis:
- description: The core NUnit testing framework programming API for writing and executing unit tests in .NET applications. Provides assertions, attributes, and lifecycle hooks consumed via the NUnit NuGet package.
  name: NUnit Framework API
  slug: nunit-framework-api
- description: Console runner for executing NUnit tests from the command line, enabling automation in build pipelines and CI/CD systems.
  name: NUnit Console Runner
  slug: nunit-console-runner
- description: Test adapter for running NUnit tests in Visual Studio, dotnet test, and other VSTest-compatible test runners.
  name: NUnit3 Test Adapter
  slug: nunit3-test-adapter
- description: Roslyn-based analyzers for NUnit that detect common test authoring mistakes and suggest fixes at compile time.
  name: NUnit Analyzers
  slug: nunit-analyzers
common:
- title: ''
  type: Website
  url: https://nunit.org
- title: ''
  type: Documentation
  url: https://docs.nunit.org
- title: ''
  type: GitHub Organization
  url: https://github.com/nunit
- title: ''
  type: Blog
  url: https://nunit.org/news/
- title: ''
  type: Community
  url: https://nunit.org/community/
- title: ''
  type: Change Log
  url: https://docs.nunit.org/articles/nunit/release-notes/
- title: ''
  type: License
  url: https://docs.nunit.org/articles/nunit/license.html
created: '2024-01-01'
description: NUnit is a unit-testing framework for all .NET languages. Initially ported from JUnit, the current production release has been completely rewritten with many new features and support for a wide range of .NET platforms. NUnit is a software testing framework, not a remote HTTP API service.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: NUnit
skills: []
slug: nunit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nunit\nname: NUnit\ndescription: >-\n  NUnit is a unit-testing framework for all .NET languages. Initially ported\n  from JUnit, the current production release has been completely rewritten with\n  many new features and support for a wide range of .NET platforms. NUnit is\n  a software testing framework, not a remote HTTP API service.\ntype: Index\nposition: Producer\naccess: 1st-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - .NET\n  - C#\n  - Framework\n  - Open Source\n  - TDD\n  - Testing\n  - Unit Testing\nurl: https://raw.githubusercontent.com/api-evangelist/nunit/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: nunit:nunit-framework-api\n    name: NUnit Framework API\n    description: >-\n      The core NUnit testing framework programming API for writing and executing\n      unit tests in .NET applications. Provides assertions, attributes, and\n\
  \      lifecycle hooks consumed via the NUnit NuGet package.\n    humanURL: https://docs.nunit.org/\n    tags:\n      - Assertions\n      - Attributes\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://docs.nunit.org/articles/nunit/intro.html\n      - type: Getting Started\n        url: https://docs.nunit.org/articles/nunit/getting-started.html\n      - type: Reference\n        url: https://docs.nunit.org/api/\n      - type: NuGet Package\n        url: https://www.nuget.org/packages/NUnit\n      - type: Source Code\n        url: https://github.com/nunit/nunit\n  - aid: nunit:nunit-console-runner\n    name: NUnit Console Runner\n    description: >-\n      Console runner for executing NUnit tests from the command line, enabling\n      automation in build pipelines and CI/CD systems.\n    humanURL: https://docs.nunit.org/articles/nunit/running-tests/Console-Runner.html\n    tags:\n      - Console\n      - Test Runner\n      - CLI\n    properties:\n      -\
  \ type: Documentation\n        url: https://docs.nunit.org/articles/nunit/running-tests/Console-Runner.html\n      - type: Command Line Reference\n        url: https://docs.nunit.org/articles/nunit/running-tests/Console-Command-Line.html\n      - type: NuGet Package\n        url: https://www.nuget.org/packages/NUnit.ConsoleRunner\n  - aid: nunit:nunit3-test-adapter\n    name: NUnit3 Test Adapter\n    description: >-\n      Test adapter for running NUnit tests in Visual Studio, dotnet test, and\n      other VSTest-compatible test runners.\n    humanURL: https://docs.nunit.org/articles/vs-test-adapter/Index.html\n    tags:\n      - Visual Studio\n      - Test Adapter\n      - VSTest\n    properties:\n      - type: Documentation\n        url: https://docs.nunit.org/articles/vs-test-adapter/Index.html\n      - type: NuGet Package\n        url: https://www.nuget.org/packages/NUnit3TestAdapter\n      - type: Source Code\n        url: https://github.com/nunit/nunit3-vs-adapter\n  - aid: nunit:nunit-analyzers\n\
  \    name: NUnit Analyzers\n    description: >-\n      Roslyn-based analyzers for NUnit that detect common test authoring\n      mistakes and suggest fixes at compile time.\n    humanURL: https://docs.nunit.org/articles/nunit-analyzers/NUnit-Analyzers.html\n    tags:\n      - Analyzers\n      - Roslyn\n      - Code Quality\n    properties:\n      - type: Documentation\n        url: https://docs.nunit.org/articles/nunit-analyzers/NUnit-Analyzers.html\n      - type: NuGet Package\n        url: https://www.nuget.org/packages/NUnit.Analyzers\n      - type: Source Code\n        url: https://github.com/nunit/nunit.analyzers\ncommon:\n  - type: Website\n    url: https://nunit.org\n  - type: Documentation\n    url: https://docs.nunit.org\n  - type: GitHub Organization\n    url: https://github.com/nunit\n  - type: Blog\n    url: https://nunit.org/news/\n  - type: Community\n    url: https://nunit.org/community/\n  - type: Change Log\n    url: https://docs.nunit.org/articles/nunit/release-notes/\n\
  \  - type: License\n    url: https://docs.nunit.org/articles/nunit/license.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nunit/refs/heads/main/apis.yml
tags:
- .NET
- C#
- Framework
- Open Source
- TDD
- Testing
- Unit Testing
url: https://raw.githubusercontent.com/api-evangelist/nunit/refs/heads/main/apis.yml
use_cases: []
---
