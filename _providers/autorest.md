---
api_count: 6
apis:
- description: The AutoRest Core package (@autorest/core) is the central engine that orchestrates code generation from OpenAPI specifications. It handles input processing, configuration resolution, pipeline manageme
  name: AutoRest Core
  slug: autorest-core
- description: The AutoRest C# generator (@autorest/csharp) produces .NET client libraries from OpenAPI specifications. It generates strongly-typed C# code with HttpClient-based REST clients, model classes, and asyn
  name: AutoRest C# Generator
  slug: autorest-csharp
- description: The AutoRest Python generator (@autorest/python) produces Python client libraries from OpenAPI specifications, generating typed Python code compatible with the Azure SDK for Python and azure-core libr
  name: AutoRest Python Generator
  slug: autorest-python
- description: The AutoRest Java generator (@autorest/java) produces Java client libraries from OpenAPI specifications, generating Java code compatible with azure-core and the Azure SDK for Java ecosystem.
  name: AutoRest Java Generator
  slug: autorest-java
- description: The AutoRest TypeScript generator (@autorest/typescript) produces TypeScript and JavaScript client libraries from OpenAPI specifications, generating type-safe clients for Node.js and browser environme
  name: AutoRest TypeScript Generator
  slug: autorest-typescript
- description: The AutoRest Go generator (@autorest/go) produces Go client libraries from OpenAPI specifications, generating idiomatic Go code compatible with the Azure SDK for Go and azure-sdk-for-go ecosystem.
  name: AutoRest Go Generator
  slug: autorest-go
common:
- title: ''
  type: Website
  url: https://github.com/Azure/autorest
- title: ''
  type: Documentation
  url: https://github.com/Azure/autorest/blob/main/docs/readme.md
- title: ''
  type: GitHubOrganization
  url: https://github.com/Azure
- title: ''
  type: GitHubRepository
  url: https://github.com/Azure/autorest
- title: ''
  type: GettingStarted
  url: https://github.com/Azure/autorest/blob/main/docs/install/readme.md
- title: ''
  type: ReleaseNotes
  url: https://github.com/Azure/autorest/releases
created: '2026-03-25'
description: 'AutoRest is an open source tool from Microsoft (MIT License) that generates client libraries for accessing RESTful APIs from OpenAPI specifications. It powers generation of Azure SDKs across C#, Python, Java, TypeScript, Go, PowerShell, and Swift with an extensible plugin architecture. Note: AutoRest is deprecated as of 2026 with retirement on July 1, 2026. The recommended successor is TypeSpec, a modern API description language and code generation platform from Microsoft.'
features:
- description: Generate client SDKs from OpenAPI specifications in C#, Python, Java, TypeScript, JavaScript, Go, PowerShell, and Swift using language-specific generator plugins.
  name: Multi-Language Code Generation
- description: AutoRest uses a pipeline-based plugin architecture where language generators, transformers, and validators are loaded as npm packages. Custom plugins can be developed to extend the generation pipeline.
  name: Extensible Plugin Architecture
- description: Supports OpenAPI 2.0 (Swagger) and OpenAPI 3.0 specification formats. The modelerfour plugin normalizes OpenAPI schemas into a consistent code model shared across all language generators.
  name: OpenAPI Processing
- description: Tightly integrated with Microsoft Azure SDK generation for all Azure services, producing SDK packages published to npm, PyPI, Maven, NuGet, and Go Modules.
  name: Azure SDK Integration
- description: Supports literate configuration using Markdown code blocks for per-client customization of generated output including namespace, output folder, and generator-specific options.
  name: Configuration File Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: AutoRest is the primary tool consuming the Azure/azure-rest-api-specs repository to generate official Azure SDK client libraries.
  name: Azure REST API Specs
- description: TypeSpec is the recommended successor to AutoRest for new API definitions, with AutoRest generators serving as code generation backends.
  name: TypeSpec
- description: AutoRest and all language generator plugins are distributed as npm packages under the @autorest scope.
  name: npm
layout: provider
modified: '2026-04-19'
name: AutoRest
skills: []
slug: autorest
solutions: []
source_yaml: "aid: autorest\nname: AutoRest\ndescription: >-\n  AutoRest is an open source tool from Microsoft (MIT License) that generates\n  client libraries for accessing RESTful APIs from OpenAPI specifications. It\n  powers generation of Azure SDKs across C#, Python, Java, TypeScript, Go,\n  PowerShell, and Swift with an extensible plugin architecture. Note: AutoRest\n  is deprecated as of 2026 with retirement on July 1, 2026. The recommended\n  successor is TypeSpec, a modern API description language and code generation\n  platform from Microsoft.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Code Generation\n  - Microsoft\n  - OpenAPI\n  - SDK Generation\n  - Azure SDK\n  - Deprecated\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/autorest/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: autorest:autorest-core\n    name: AutoRest Core\n \
  \   description: >-\n      The AutoRest Core package (@autorest/core) is the central engine that\n      orchestrates code generation from OpenAPI specifications. It handles input\n      processing, configuration resolution, pipeline management, and plugin\n      coordination. All language-specific generators are plugins that extend\n      the core pipeline.\n    humanURL: https://github.com/Azure/autorest\n    tags:\n      - Code Generation\n      - OpenAPI\n      - Plugin System\n      - Pipeline\n    properties:\n      - type: Documentation\n        url: https://github.com/Azure/autorest/blob/main/docs/readme.md\n      - type: GettingStarted\n        url: https://github.com/Azure/autorest/blob/main/docs/install/readme.md\n      - type: GitHubRepository\n        url: https://github.com/Azure/autorest\n      - type: SDK\n        url: https://www.npmjs.com/package/@autorest/core\n        title: npm Package\n\n  - aid: autorest:autorest-csharp\n    name: AutoRest C# Generator\n    description:\
  \ >-\n      The AutoRest C# generator (@autorest/csharp) produces .NET client\n      libraries from OpenAPI specifications. It generates strongly-typed\n      C# code with HttpClient-based REST clients, model classes, and\n      async/await patterns compatible with .NET 6+.\n    humanURL: https://github.com/Azure/autorest.csharp\n    tags:\n      - C#\n      - .NET\n      - Code Generation\n      - Azure SDK\n    properties:\n      - type: Documentation\n        url: https://github.com/Azure/autorest.csharp\n      - type: GitHubRepository\n        url: https://github.com/Azure/autorest.csharp\n\n  - aid: autorest:autorest-python\n    name: AutoRest Python Generator\n    description: >-\n      The AutoRest Python generator (@autorest/python) produces Python client\n      libraries from OpenAPI specifications, generating typed Python code\n      compatible with the Azure SDK for Python and azure-core library.\n    humanURL: https://github.com/Azure/autorest.python\n    tags:\n      - Python\n\
  \      - Code Generation\n      - Azure SDK\n    properties:\n      - type: Documentation\n        url: https://github.com/Azure/autorest.python\n      - type: GitHubRepository\n        url: https://github.com/Azure/autorest.python\n\n  - aid: autorest:autorest-java\n    name: AutoRest Java Generator\n    description: >-\n      The AutoRest Java generator (@autorest/java) produces Java client\n      libraries from OpenAPI specifications, generating Java code compatible\n      with azure-core and the Azure SDK for Java ecosystem.\n    humanURL: https://github.com/Azure/autorest.java\n    tags:\n      - Java\n      - Code Generation\n      - Azure SDK\n    properties:\n      - type: Documentation\n        url: https://github.com/Azure/autorest.java\n      - type: GitHubRepository\n        url: https://github.com/Azure/autorest.java\n\n  - aid: autorest:autorest-typescript\n    name: AutoRest TypeScript Generator\n    description: >-\n      The AutoRest TypeScript generator (@autorest/typescript)\
  \ produces\n      TypeScript and JavaScript client libraries from OpenAPI specifications,\n      generating type-safe clients for Node.js and browser environments\n      compatible with the Azure SDK for JavaScript.\n    humanURL: https://github.com/Azure/autorest.typescript\n    tags:\n      - TypeScript\n      - JavaScript\n      - Code Generation\n      - Azure SDK\n    properties:\n      - type: Documentation\n        url: https://github.com/Azure/autorest.typescript\n      - type: GitHubRepository\n        url: https://github.com/Azure/autorest.typescript\n\n  - aid: autorest:autorest-go\n    name: AutoRest Go Generator\n    description: >-\n      The AutoRest Go generator (@autorest/go) produces Go client libraries\n      from OpenAPI specifications, generating idiomatic Go code compatible\n      with the Azure SDK for Go and azure-sdk-for-go ecosystem.\n    humanURL: https://github.com/Azure/autorest.go\n    tags:\n      - Go\n      - Code Generation\n      - Azure SDK\n    properties:\n\
  \      - type: Documentation\n        url: https://github.com/Azure/autorest.go\n      - type: GitHubRepository\n        url: https://github.com/Azure/autorest.go\n\ncommon:\n  - type: Website\n    url: https://github.com/Azure/autorest\n  - type: Documentation\n    url: https://github.com/Azure/autorest/blob/main/docs/readme.md\n  - type: GitHubOrganization\n    url: https://github.com/Azure\n  - type: GitHubRepository\n    url: https://github.com/Azure/autorest\n  - type: GettingStarted\n    url: https://github.com/Azure/autorest/blob/main/docs/install/readme.md\n  - type: ReleaseNotes\n    url: https://github.com/Azure/autorest/releases\n  - type: Features\n    data:\n      - name: Multi-Language Code Generation\n        description: >-\n          Generate client SDKs from OpenAPI specifications in C#, Python, Java,\n          TypeScript, JavaScript, Go, PowerShell, and Swift using language-specific\n          generator plugins.\n      - name: Extensible Plugin Architecture\n      \
  \  description: >-\n          AutoRest uses a pipeline-based plugin architecture where language\n          generators, transformers, and validators are loaded as npm packages.\n          Custom plugins can be developed to extend the generation pipeline.\n      - name: OpenAPI Processing\n        description: >-\n          Supports OpenAPI 2.0 (Swagger) and OpenAPI 3.0 specification formats.\n          The modelerfour plugin normalizes OpenAPI schemas into a consistent\n          code model shared across all language generators.\n      - name: Azure SDK Integration\n        description: >-\n          Tightly integrated with Microsoft Azure SDK generation for all Azure\n          services, producing SDK packages published to npm, PyPI, Maven,\n          NuGet, and Go Modules.\n      - name: Configuration File Support\n        description: >-\n          Supports literate configuration using Markdown code blocks for\n          per-client customization of generated output including namespace,\n\
  \          output folder, and generator-specific options.\n  - type: UseCases\n    data:\n      - name: Azure Service SDK Generation\n        description: >-\n          Primary use case for generating Azure SDK client libraries for all\n          Azure services from the azure-rest-api-specs OpenAPI repository.\n      - name: REST API Client Generation\n        description: >-\n          Generate strongly-typed client SDKs for any REST API described in\n          OpenAPI format across multiple programming languages simultaneously.\n      - name: SDK Customization\n        description: >-\n          Use AutoRest configuration files and directives to customize generated\n          code including renames, suppressions, and additional properties.\n  - type: Integrations\n    data:\n      - name: Azure REST API Specs\n        description: >-\n          AutoRest is the primary tool consuming the Azure/azure-rest-api-specs\n          repository to generate official Azure SDK client libraries.\n\
  \      - name: TypeSpec\n        description: >-\n          TypeSpec is the recommended successor to AutoRest for new API\n          definitions, with AutoRest generators serving as code generation backends.\n      - name: npm\n        description: >-\n          AutoRest and all language generator plugins are distributed as npm\n          packages under the @autorest scope.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/autorest/refs/heads/main/apis.yml
tags:
- Code Generation
- Microsoft
- OpenAPI
- SDK Generation
- Azure SDK
- Deprecated
url: https://raw.githubusercontent.com/api-evangelist/autorest/refs/heads/main/apis.yml
use_cases:
- description: Primary use case for generating Azure SDK client libraries for all Azure services from the azure-rest-api-specs OpenAPI repository.
  name: Azure Service SDK Generation
- description: Generate strongly-typed client SDKs for any REST API described in OpenAPI format across multiple programming languages simultaneously.
  name: REST API Client Generation
- description: Use AutoRest configuration files and directives to customize generated code including renames, suppressions, and additional properties.
  name: SDK Customization
---
