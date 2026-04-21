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
