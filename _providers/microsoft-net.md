---
api_count: 5
apis:
- description: Comprehensive reference for .NET APIs across all packages, namespaces, and types in the .NET ecosystem including .NET 9, .NET Standard, and .NET Framework.
  name: Microsoft .NET API Browser
  slug: dotnet-api
- description: RESTful API for interacting with nuget.org and private NuGet feeds, supporting package search, download, push, delete, and metadata queries for .NET package management.
  name: NuGet Server API
  slug: nuget-api
- description: Cross-platform command-line interface for developing, building, running, and publishing .NET applications. Provides commands for project creation, package management, testing, and deployment.
  name: .NET CLI
  slug: dotnet-cli
- description: Framework for building HTTP-based RESTful APIs and web services with ASP.NET Core, including controllers, minimal APIs, routing, model binding, authentication, and OpenAPI integration.
  name: ASP.NET Core Web API
  slug: aspnet-core-api
- description: Cloud-ready stack for building observable, production-ready distributed applications in .NET with built-in service discovery, health checks, telemetry, and configuration management.
  name: .NET Aspire
  slug: dotnet-aspire
common:
- title: ''
  type: Portal
  url: https://dotnet.microsoft.com/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/dotnet/
- title: ''
  type: GettingStarted
  url: https://dotnet.microsoft.com/learn
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/dotnet/
- title: ''
  type: GitHubOrganization
  url: https://github.com/dotnet
- title: ''
  type: Support
  url: https://dotnet.microsoft.com/platform/support
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/servicesagreement/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: YouTube
  url: https://www.youtube.com/dotnet
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/.net
- title: ''
  type: X
  url: https://twitter.com/dotnet
- title: ''
  type: ChangeLog
  url: https://github.com/dotnet/core/blob/main/release-notes/README.md
- title: ''
  type: SDK
  url: https://dotnet.microsoft.com/download
- title: ''
  type: Training
  url: https://learn.microsoft.com/en-us/training/dotnet/
created: '2024-01-01'
description: Microsoft .NET is a free, cross-platform, open source developer platform for building many different types of applications. The .NET APIs and developer tools provide programmatic access to .NET runtime services, NuGet package management, project templates, and build tooling across web, mobile, desktop, games, IoT, cloud, and microservices workloads.
features:
- description: Build and run .NET applications on Windows, macOS, and Linux with full platform support.
  name: Cross-Platform Development
- description: .NET runtime with JIT compilation, garbage collection, and ahead-of-time compilation for optimal performance.
  name: High Performance Runtime
- description: Access over 350,000 packages through the NuGet package manager for rapid development.
  name: NuGet Package Ecosystem
- description: Build lightweight HTTP APIs with minimal code using the minimal API pattern in ASP.NET Core.
  name: Minimal APIs
- description: Built-in support for containers, Kubernetes, microservices, and cloud deployment through .NET Aspire.
  name: Cloud Native Support
- description: Apply code changes to running applications without restarting for faster development cycles.
  name: Hot Reload
image: /assets/icons/microsoft-net.png
integrations:
- description: Deep integration with Microsoft Azure cloud services including App Service, Functions, and Container Apps.
  name: Azure
- description: Full IDE support with IntelliSense, debugging, profiling, and project templates in Visual Studio.
  name: Visual Studio
- description: Lightweight development with the C# Dev Kit extension for Visual Studio Code.
  name: VS Code
- description: CI/CD pipeline integration with GitHub Actions for .NET build, test, and deploy workflows.
  name: GitHub Actions
- description: Container support with official .NET Docker images and multi-stage build templates.
  name: Docker
- description: Object-relational mapping for database access with support for SQL Server, PostgreSQL, SQLite, and more.
  name: Entity Framework Core
layout: provider
modified: '2026-04-18'
name: Microsoft .NET
skills: []
slug: microsoft-net
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-net\nname: Microsoft .NET\ndescription: >-\n  Microsoft .NET is a free, cross-platform, open source developer platform for building\n  many different types of applications. The .NET APIs and developer tools provide\n  programmatic access to .NET runtime services, NuGet package management, project\n  templates, and build tooling across web, mobile, desktop, games, IoT, cloud, and\n  microservices workloads.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/microsoft-net/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - .NET\n  - C#\n  - Cloud\n  - Cross-Platform\n  - Developer Tools\n  - Microsoft\n  - Open Source\napis:\n  - aid: microsoft-net:dotnet-api\n    name: Microsoft .NET API Browser\n    description: >-\n      Comprehensive reference for .NET APIs across all packages, namespaces, and\
  \ types\n      in the .NET ecosystem including .NET 9, .NET Standard, and .NET Framework.\n    humanURL: https://learn.microsoft.com/en-us/dotnet/api/\n    baseURL: https://learn.microsoft.com/en-us/dotnet/api/\n    tags:\n      - API Browser\n      - Class Library\n      - Reference\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dotnet/api/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/dotnet/api/\n  - aid: microsoft-net:nuget-api\n    name: NuGet Server API\n    description: >-\n      RESTful API for interacting with nuget.org and private NuGet feeds, supporting\n      package search, download, push, delete, and metadata queries for .NET package\n      management.\n    humanURL: https://learn.microsoft.com/en-us/nuget/api/overview\n    baseURL: https://api.nuget.org/v3/\n    tags:\n      - NuGet\n      - Package Management\n      - Package Registry\n      - REST\n    properties:\n      - type: Documentation\n\
  \        url: https://learn.microsoft.com/en-us/nuget/api/overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/nuget/api/overview\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/nuget/quickstart/install-and-use-a-package-in-visual-studio\n  - aid: microsoft-net:dotnet-cli\n    name: .NET CLI\n    description: >-\n      Cross-platform command-line interface for developing, building, running, and\n      publishing .NET applications. Provides commands for project creation, package\n      management, testing, and deployment.\n    humanURL: https://learn.microsoft.com/en-us/dotnet/core/tools/\n    baseURL: https://learn.microsoft.com/en-us/dotnet/core/tools/\n    tags:\n      - Build\n      - CLI\n      - Developer Tools\n      - Tooling\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dotnet/core/tools/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet\n\
  \  - aid: microsoft-net:aspnet-core-api\n    name: ASP.NET Core Web API\n    description: >-\n      Framework for building HTTP-based RESTful APIs and web services with ASP.NET\n      Core, including controllers, minimal APIs, routing, model binding, authentication,\n      and OpenAPI integration.\n    humanURL: https://learn.microsoft.com/en-us/aspnet/core/web-api/\n    baseURL: https://learn.microsoft.com/en-us/aspnet/core/\n    tags:\n      - ASP.NET Core\n      - REST\n      - Web API\n      - Web Framework\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/aspnet/core/web-api/\n      - type: Tutorials\n        url: https://learn.microsoft.com/en-us/aspnet/core/tutorials/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/aspnet/core/getting-started\n  - aid: microsoft-net:dotnet-aspire\n    name: .NET Aspire\n    description: >-\n      Cloud-ready stack for building observable, production-ready distributed applications\n\
  \      in .NET with built-in service discovery, health checks, telemetry, and\n      configuration management.\n    humanURL: https://learn.microsoft.com/en-us/dotnet/aspire/\n    baseURL: https://learn.microsoft.com/en-us/dotnet/aspire/\n    tags:\n      - Cloud Native\n      - Distributed Systems\n      - Microservices\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dotnet/aspire/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/dotnet/aspire/get-started/build-your-first-aspire-app\ncommon:\n  - type: Portal\n    url: https://dotnet.microsoft.com/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/dotnet/\n  - type: GettingStarted\n    url: https://dotnet.microsoft.com/learn\n  - type: Blog\n    url: https://devblogs.microsoft.com/dotnet/\n  - type: GitHubOrganization\n    url: https://github.com/dotnet\n  - type: Support\n    url: https://dotnet.microsoft.com/platform/support\n\
  \  - type: TermsOfService\n    url: https://www.microsoft.com/en-us/servicesagreement/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: YouTube\n    url: https://www.youtube.com/dotnet\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/.net\n  - type: X\n    url: https://twitter.com/dotnet\n  - type: ChangeLog\n    url: https://github.com/dotnet/core/blob/main/release-notes/README.md\n  - type: SDK\n    url: https://dotnet.microsoft.com/download\n  - type: Training\n    url: https://learn.microsoft.com/en-us/training/dotnet/\n  - type: Features\n    data:\n      - name: Cross-Platform Development\n        description: Build and run .NET applications on Windows, macOS, and Linux with full platform support.\n      - name: High Performance Runtime\n        description: .NET runtime with JIT compilation, garbage collection, and ahead-of-time compilation for optimal performance.\n      - name: NuGet Package Ecosystem\n\
  \        description: Access over 350,000 packages through the NuGet package manager for rapid development.\n      - name: Minimal APIs\n        description: Build lightweight HTTP APIs with minimal code using the minimal API pattern in ASP.NET Core.\n      - name: Cloud Native Support\n        description: Built-in support for containers, Kubernetes, microservices, and cloud deployment through .NET Aspire.\n      - name: Hot Reload\n        description: Apply code changes to running applications without restarting for faster development cycles.\n  - type: UseCases\n    data:\n      - name: Enterprise Web Applications\n        description: Build scalable enterprise web applications using ASP.NET Core with authentication, authorization, and data access.\n      - name: Microservices Architecture\n        description: Design and deploy microservices using .NET with gRPC, message queues, and service discovery.\n      - name: Cloud-Native Applications\n        description: Develop cloud-native\
  \ applications with .NET Aspire, containers, and Azure integration.\n      - name: RESTful API Development\n        description: Create production-ready REST APIs with OpenAPI documentation, versioning, and rate limiting.\n      - name: Desktop Applications\n        description: Build Windows desktop applications using WPF, WinForms, or .NET MAUI for cross-platform desktop.\n  - type: Integrations\n    data:\n      - name: Azure\n        description: Deep integration with Microsoft Azure cloud services including App Service, Functions, and Container Apps.\n      - name: Visual Studio\n        description: Full IDE support with IntelliSense, debugging, profiling, and project templates in Visual Studio.\n      - name: VS Code\n        description: Lightweight development with the C# Dev Kit extension for Visual Studio Code.\n      - name: GitHub Actions\n        description: CI/CD pipeline integration with GitHub Actions for .NET build, test, and deploy workflows.\n      - name: Docker\n\
  \        description: Container support with official .NET Docker images and multi-stage build templates.\n      - name: Entity Framework Core\n        description: Object-relational mapping for database access with support for SQL Server, PostgreSQL, SQLite, and more.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-net/refs/heads/main/apis.yml
tags:
- .NET
- C#
- Cloud
- Cross-Platform
- Developer Tools
- Microsoft
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/microsoft-net/refs/heads/main/apis.yml
use_cases:
- description: Build scalable enterprise web applications using ASP.NET Core with authentication, authorization, and data access.
  name: Enterprise Web Applications
- description: Design and deploy microservices using .NET with gRPC, message queues, and service discovery.
  name: Microservices Architecture
- description: Develop cloud-native applications with .NET Aspire, containers, and Azure integration.
  name: Cloud-Native Applications
- description: Create production-ready REST APIs with OpenAPI documentation, versioning, and rate limiting.
  name: RESTful API Development
- description: Build Windows desktop applications using WPF, WinForms, or .NET MAUI for cross-platform desktop.
  name: Desktop Applications
---
