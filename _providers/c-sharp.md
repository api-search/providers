---
api_count: 5
apis:
- description: 'The C# language itself: syntax, semantics, type system, and standard library conventions. Maintained by Microsoft with a formal ECMA-334 specification and modern features such as records, pattern matc'
  name: C# Language
  slug: c-sharp-language
- description: Roslyn is the open-source .NET compiler platform that provides C# and Visual Basic compilers with rich code analysis APIs, enabling custom analyzers, refactorings, and tooling.
  name: Roslyn (.NET Compiler Platform)
  slug: roslyn-compiler
- description: The .NET runtime hosts and executes C# programs, providing the CLR, base class libraries, garbage collection, and cross-platform support for Windows, Linux, and macOS.
  name: .NET Runtime
  slug: dotnet-runtime
- description: NuGet is the package manager for .NET, providing a central registry of open-source and commercial libraries distributed as packages for use in C# and other .NET projects. NuGet exposes a documented HT
  name: NuGet Package Manager
  slug: nuget
- description: ASP.NET Core is the cross-platform web framework for C#, used to build web applications, APIs, and real-time services on the .NET runtime.
  name: ASP.NET Core
  slug: aspnet-core
common:
- title: ''
  type: Website
  url: https://learn.microsoft.com/en-us/dotnet/csharp/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/
- title: ''
  type: Language Reference
  url: https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/
- title: ''
  type: Specification
  url: https://learn.microsoft.com/en-us/dotnet/csharp/specification/
- title: ''
  type: GitHub Org
  url: https://github.com/dotnet
- title: ''
  type: Roslyn Compiler
  url: https://github.com/dotnet/roslyn
- title: ''
  type: .NET Runtime
  url: https://github.com/dotnet/runtime
- title: ''
  type: .NET Docs
  url: https://github.com/dotnet/docs
- title: ''
  type: NuGet
  url: https://www.nuget.org
- title: ''
  type: Download .NET
  url: https://dotnet.microsoft.com/download
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/dotnet/
- title: ''
  type: Community
  url: https://dotnet.microsoft.com/platform/community
created: '2025-01-01'
description: C# is a modern, object-oriented programming language developed by Microsoft as part of the .NET platform. It is used for building Windows applications, web services, games (via Unity), and enterprise software, offering strong typing, garbage collection, and rich framework support. The C# language is defined by a standardized specification and implemented by the Roslyn compiler, with packages distributed via NuGet and running on the .NET runtime.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: C#
skills: []
slug: c-sharp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: c-sharp\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/c-sharp/refs/heads/main/apis.yml\nname: C#\ntags:\n  - .NET\n  - C#\n  - Microsoft\n  - Programming Language\n  - Topic\n  - Roslyn\n  - NuGet\n  - Dotnet\n  - Language\ntype: Index\nx-type: topic\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-01'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  C# is a modern, object-oriented programming language developed by Microsoft\n  as part of the .NET platform. It is used for building Windows applications,\n  web services, games (via Unity), and enterprise software, offering strong\n  typing, garbage collection, and rich framework support. The C# language is\n  defined by a standardized specification and implemented by the Roslyn\n  compiler, with packages distributed via NuGet and running on the .NET\n  runtime.\napis:\n  - aid: c-sharp:c-sharp-language\n    name: C# Language\n\
  \    tags:\n      - C#\n      - Programming Language\n      - Microsoft\n    humanURL: https://learn.microsoft.com/en-us/dotnet/csharp/\n    properties:\n      - type: Website\n        url: https://learn.microsoft.com/en-us/dotnet/csharp/\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/\n      - type: Language Reference\n        url: https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/\n      - type: Language Specification\n        url: https://learn.microsoft.com/en-us/dotnet/csharp/specification/\n    description: >-\n      The C# language itself: syntax, semantics, type system, and standard\n      library conventions. Maintained by Microsoft with a formal ECMA-334\n      specification and modern features such as records, pattern matching,\n      async/await, and nullable reference types.\n  - aid: c-sharp:roslyn-compiler\n    name: Roslyn (.NET Compiler Platform)\n    tags:\n      - Compiler\n      - Roslyn\n \
  \     - Open Source\n    humanURL: https://github.com/dotnet/roslyn\n    properties:\n      - type: GitHub\n        url: https://github.com/dotnet/roslyn\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dotnet/csharp/roslyn-sdk/\n    description: >-\n      Roslyn is the open-source .NET compiler platform that provides C# and\n      Visual Basic compilers with rich code analysis APIs, enabling custom\n      analyzers, refactorings, and tooling.\n  - aid: c-sharp:dotnet-runtime\n    name: .NET Runtime\n    tags:\n      - Runtime\n      - Dotnet\n      - Open Source\n    humanURL: https://github.com/dotnet/runtime\n    properties:\n      - type: GitHub\n        url: https://github.com/dotnet/runtime\n      - type: Download\n        url: https://dotnet.microsoft.com/download\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dotnet/core/\n    description: >-\n      The .NET runtime hosts and executes C# programs, providing the CLR,\n  \
  \    base class libraries, garbage collection, and cross-platform support\n      for Windows, Linux, and macOS.\n  - aid: c-sharp:nuget\n    name: NuGet Package Manager\n    tags:\n      - Package Manager\n      - NuGet\n      - Registry\n    humanURL: https://www.nuget.org\n    properties:\n      - type: Website\n        url: https://www.nuget.org\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/nuget/\n      - type: API\n        url: https://learn.microsoft.com/en-us/nuget/api/overview\n      - type: GitHub\n        url: https://github.com/NuGet\n    description: >-\n      NuGet is the package manager for .NET, providing a central registry of\n      open-source and commercial libraries distributed as packages for use in\n      C# and other .NET projects. NuGet exposes a documented HTTP API for\n      package discovery and publishing.\n  - aid: c-sharp:aspnet-core\n    name: ASP.NET Core\n    tags:\n      - Web Framework\n      - ASP.NET\n    humanURL: https://learn.microsoft.com/en-us/aspnet/core\n\
  \    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/aspnet/core\n      - type: GitHub\n        url: https://github.com/dotnet/aspnetcore\n    description: >-\n      ASP.NET Core is the cross-platform web framework for C#, used to build\n      web applications, APIs, and real-time services on the .NET runtime.\ncommon:\n  - type: Website\n    url: https://learn.microsoft.com/en-us/dotnet/csharp/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/\n  - type: Language Reference\n    url: https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/\n  - type: Specification\n    url: https://learn.microsoft.com/en-us/dotnet/csharp/specification/\n  - type: GitHub Org\n    url: https://github.com/dotnet\n  - type: Roslyn Compiler\n    url: https://github.com/dotnet/roslyn\n  - type: .NET Runtime\n    url: https://github.com/dotnet/runtime\n  - type: .NET Docs\n    url: https://github.com/dotnet/docs\n\
  \  - type: NuGet\n    url: https://www.nuget.org\n  - type: Download .NET\n    url: https://dotnet.microsoft.com/download\n  - type: Blog\n    url: https://devblogs.microsoft.com/dotnet/\n  - type: Community\n    url: https://dotnet.microsoft.com/platform/community\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/c-sharp/refs/heads/main/apis.yml
tags:
- .NET
- C#
- Microsoft
- Programming Language
- Topic
- Roslyn
- NuGet
- Dotnet
- Language
url: https://raw.githubusercontent.com/api-evangelist/c-sharp/refs/heads/main/apis.yml
use_cases: []
---
