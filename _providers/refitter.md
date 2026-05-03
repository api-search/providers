---
api_count: 2
apis:
- description: Refitter is a .NET source generator and CLI tool that produces Refit HTTP client interfaces from OpenAPI 2.0 and 3.x specifications. Supports compile-time code generation via MSBuild source generators
  name: Refitter
  slug: refitter
- description: The type-safe REST library for .NET that Refitter generates interfaces for. Refit turns REST APIs into live interfaces by decorating C# interfaces with attributes describing the HTTP endpoints, then g
  name: Refit
  slug: refit
common:
- title: ''
  type: Website
  url: https://refitter.github.io
- title: ''
  type: GitHubRepository
  url: https://github.com/christianhelle/refitter
- title: ''
  type: Documentation
  url: https://refitter.github.io
- title: ''
  type: Issues
  url: https://github.com/christianhelle/refitter/issues
- title: ''
  type: NuGetPackage
  url: https://www.nuget.org/packages/Refitter
- title: ''
  type: License
  url: https://github.com/christianhelle/refitter/blob/main/LICENSE
- title: ''
  type: JSONSchema
  url: json-schema/refitter-settings-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/refitter-output-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/refitter-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/refitter-vocabulary.yml
created: '2026-03-25'
description: Refitter is a .NET tool and source generator that produces Refit HTTP client interfaces from OpenAPI specifications. It runs at compile time as a source generator or as a standalone CLI tool (dotnet-refitter), enabling type-safe API consumption in .NET projects. Refitter reads OpenAPI 2.0 (Swagger) and OpenAPI 3.x specifications and generates strongly-typed C# interface definitions and model classes compatible with the Refit library.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Refitter Context
  property_count: 7
  slug: refitter-context
layout: provider
modified: '2026-05-02'
name: Refitter
skills: []
slug: refitter
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: refitter\nname: Refitter\ndescription: >-\n  Refitter is a .NET tool and source generator that produces Refit HTTP client\n  interfaces from OpenAPI specifications. It runs at compile time as a source\n  generator or as a standalone CLI tool (dotnet-refitter), enabling type-safe\n  API consumption in .NET projects. Refitter reads OpenAPI 2.0 (Swagger) and\n  OpenAPI 3.x specifications and generates strongly-typed C# interface\n  definitions and model classes compatible with the Refit library.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/refitter/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - .NET\n  - C#\n  - Code Generation\n  - OpenAPI\n  - Refit\n  - Source Generator\n  - Type-Safe\napis:\n  - aid: refitter:refitter\n    name: Refitter\n    description: >-\n      Refitter is a .NET source generator\
  \ and CLI tool that produces Refit HTTP\n      client interfaces from OpenAPI 2.0 and 3.x specifications. Supports\n      compile-time code generation via MSBuild source generators and on-demand\n      generation via the dotnet-refitter global tool. Generates C# interfaces,\n      model classes, and optional Refit settings for use with the Refit\n      HttpClient library.\n    humanURL: https://github.com/christianhelle/refitter\n    baseURL: https://refitter.github.io\n    tags:\n      - .NET\n      - C#\n      - Code Generation\n      - OpenAPI\n      - Refit\n      - Source Generator\n    properties:\n      - type: Documentation\n        url: https://refitter.github.io\n      - type: GettingStarted\n        url: https://refitter.github.io/articles/getting-started.html\n      - type: GitHubRepository\n        url: https://github.com/christianhelle/refitter\n      - type: NuGetPackage\n        url: https://www.nuget.org/packages/Refitter\n      - type: NuGetPackage\n        url: https://www.nuget.org/packages/dotnet-refitter\n\
  \      - type: Changelog\n        url: https://github.com/christianhelle/refitter/releases\n      - type: License\n        url: https://github.com/christianhelle/refitter/blob/main/LICENSE\n      - type: Issues\n        url: https://github.com/christianhelle/refitter/issues\n      - type: Discussions\n        url: https://github.com/christianhelle/refitter/discussions\n  - aid: refitter:refit\n    name: Refit\n    description: >-\n      The type-safe REST library for .NET that Refitter generates interfaces for.\n      Refit turns REST APIs into live interfaces by decorating C# interfaces with\n      attributes describing the HTTP endpoints, then generating HttpClient calls\n      at runtime via Castle DynamicProxy or source generators.\n    humanURL: https://reactiveui.github.io/refit/\n    tags:\n      - .NET\n      - HttpClient\n      - REST Client\n      - Type-Safe\n    properties:\n      - type: Documentation\n        url: https://reactiveui.github.io/refit/\n      - type: GitHubRepository\n\
  \        url: https://github.com/reactiveui/refit\n      - type: NuGetPackage\n        url: https://www.nuget.org/packages/Refit\ncommon:\n  - type: Website\n    url: https://refitter.github.io\n  - type: GitHubRepository\n    url: https://github.com/christianhelle/refitter\n  - type: Documentation\n    url: https://refitter.github.io\n  - type: Issues\n    url: https://github.com/christianhelle/refitter/issues\n  - type: NuGetPackage\n    url: https://www.nuget.org/packages/Refitter\n  - type: License\n    url: https://github.com/christianhelle/refitter/blob/main/LICENSE\n  - type: JSONSchema\n    url: json-schema/refitter-settings-schema.json\n  - type: JSONStructure\n    url: json-structure/refitter-output-structure.json\n  - type: JSONLDContext\n    url: json-ld/refitter-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/refitter-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/refitter/refs/heads/main/apis.yml
tags:
- .NET
- C#
- Code Generation
- OpenAPI
- Refit
- Source Generator
- Type-Safe
url: https://raw.githubusercontent.com/api-evangelist/refitter/refs/heads/main/apis.yml
use_cases: []
---
