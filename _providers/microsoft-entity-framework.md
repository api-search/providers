---
api_count: 2
apis:
- description: A lightweight, extensible, open source and cross-platform ORM for .NET. Supports SQL Server, PostgreSQL, MySQL, SQLite, Cosmos DB, and in-memory databases.
  name: Entity Framework Core
  slug: ef-core
- description: The mature and stable ORM for .NET Framework with Code First, Database First, and Model First workflows.
  name: Entity Framework 6
  slug: ef6
common:
- title: ''
  type: Portal
  url: https://learn.microsoft.com/en-us/ef/
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/dotnet/tag/entity-framework/
- title: ''
  type: GitHubOrganization
  url: https://github.com/dotnet
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/entity-framework-core
- title: ''
  type: YouTube
  url: https://www.youtube.com/playlist?list=PLdo4fOcmZ0oX0ObHwBrJ0vJpZ7PiYMqeA
- title: ''
  type: Support
  url: https://learn.microsoft.com/en-us/ef/core/get-started/overview/support
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
created: '2024-01-01'
description: Microsoft Entity Framework is an object-relational mapping (ORM) framework for .NET developers enabling database access using .NET objects. EF Core is the modern, cross-platform version supporting SQL Server, PostgreSQL, MySQL, SQLite, and Cosmos DB with LINQ queries, change tracking, migrations, and code-first modeling.
features:
- description: Write database queries using Language Integrated Query (LINQ) with strongly-typed C# expressions.
  name: LINQ Queries
- description: Automatic tracking of entity changes for efficient database updates.
  name: Change Tracking
- description: Database schema versioning with code-first migrations for evolving data models.
  name: Migrations
- description: Define database schemas using C# classes and data annotations or Fluent API.
  name: Code First Modeling
- description: Plugin architecture supporting SQL Server, PostgreSQL, MySQL, SQLite, Cosmos DB, and more.
  name: Database Providers
- description: Control related entity loading with lazy, eager, and explicit loading strategies.
  name: Lazy and Eager Loading
- description: Execute raw SQL and stored procedures alongside LINQ queries.
  name: Raw SQL Queries
- description: Apply automatic filtering to all queries for multi-tenancy and soft deletes.
  name: Global Query Filters
- description: Custom type conversions between .NET types and database column types.
  name: Value Converters
- description: Pre-compile LINQ queries for improved performance in hot paths.
  name: Compiled Queries
image: https://docs.microsoft.com/en-us/ef/images/ef-logo.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Entity Framework
rules:
- name: Microsoft Entity Framework API Rules
  rule_count: 14
  severity_counts:
    error: 13
    hint: 0
    info: 1
    warn: 0
  slug: entity-framework-spectral-rules
skills: []
slug: microsoft-entity-framework
solutions:
- description: Modern, cross-platform ORM for .NET 6+ applications.
  name: Entity Framework Core
- description: Mature ORM for .NET Framework applications.
  name: Entity Framework 6
- description: CLI and Package Manager Console tools for migrations and scaffolding.
  name: EF Core Tools
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-entity-framework\nname: Microsoft Entity Framework\ndescription: Microsoft Entity Framework is an object-relational mapping (ORM) framework\n  for .NET developers enabling database access using .NET objects. EF Core is the\n  modern, cross-platform version supporting SQL Server, PostgreSQL, MySQL, SQLite,\n  and Cosmos DB with LINQ queries, change tracking, migrations, and code-first modeling.\ntype: Index\nimage: https://docs.microsoft.com/en-us/ef/images/ef-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-entity-framework/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n- .NET\n- Data Access\n- Database\n- Entity Framework\n- ORM\napis:\n- aid: microsoft-entity-framework:ef-core\n  name: Entity Framework Core\n  description: A lightweight, extensible, open source and cross-platform ORM for .NET.\n    Supports SQL Server, PostgreSQL, MySQL, SQLite, Cosmos DB, and in-memory\
  \ databases.\n  humanURL: https://learn.microsoft.com/en-us/ef/core/\n  baseURL: https://www.nuget.org/packages/Microsoft.EntityFrameworkCore\n  tags:\n  - .NET Core\n  - Cross-Platform\n  - Database\n  - ORM\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/ef/core/\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/ef/core/get-started/overview/first-app\n  - type: APIReference\n    url: https://learn.microsoft.com/en-us/dotnet/api/microsoft.entityframeworkcore\n  - type: GitHubRepository\n    url: https://github.com/dotnet/efcore\n  - type: ReleaseNotes\n    url: https://learn.microsoft.com/en-us/ef/core/what-is-new/\n  - type: SDK\n    url: https://www.nuget.org/packages/Microsoft.EntityFrameworkCore\n    title: NuGet Package\n- aid: microsoft-entity-framework:ef6\n  name: Entity Framework 6\n  description: The mature and stable ORM for .NET Framework with Code First, Database\n    First, and Model First workflows.\n  humanURL: https://learn.microsoft.com/en-us/ef/ef6/\n\
  \  baseURL: https://www.nuget.org/packages/EntityFramework\n  tags:\n  - .NET Framework\n  - Database\n  - Legacy\n  - ORM\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/ef/ef6/\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/ef/ef6/get-started\n  - type: APIReference\n    url: https://learn.microsoft.com/en-us/dotnet/api/system.data.entity\n  - type: GitHubRepository\n    url: https://github.com/dotnet/ef6\n  - type: SDK\n    url: https://www.nuget.org/packages/EntityFramework\n    title: NuGet Package\ncommon:\n- type: Portal\n  url: https://learn.microsoft.com/en-us/ef/\n- type: Blog\n  url: https://devblogs.microsoft.com/dotnet/tag/entity-framework/\n- type: GitHubOrganization\n  url: https://github.com/dotnet\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/entity-framework-core\n- type: YouTube\n  url: https://www.youtube.com/playlist?list=PLdo4fOcmZ0oX0ObHwBrJ0vJpZ7PiYMqeA\n- type: Support\n  url:\
  \ https://learn.microsoft.com/en-us/ef/core/get-started/overview/support\n- type: TermsOfService\n  url: https://www.microsoft.com/en-us/legal/terms-of-use\n- type: PrivacyPolicy\n  url: https://privacy.microsoft.com/en-us/privacystatement\n- type: Features\n  data:\n  - name: LINQ Queries\n    description: Write database queries using Language Integrated Query (LINQ) with\n      strongly-typed C# expressions.\n  - name: Change Tracking\n    description: Automatic tracking of entity changes for efficient database updates.\n  - name: Migrations\n    description: Database schema versioning with code-first migrations for evolving\n      data models.\n  - name: Code First Modeling\n    description: Define database schemas using C# classes and data annotations or\n      Fluent API.\n  - name: Database Providers\n    description: Plugin architecture supporting SQL Server, PostgreSQL, MySQL, SQLite,\n      Cosmos DB, and more.\n  - name: Lazy and Eager Loading\n    description: Control related\
  \ entity loading with lazy, eager, and explicit loading\n      strategies.\n  - name: Raw SQL Queries\n    description: Execute raw SQL and stored procedures alongside LINQ queries.\n  - name: Global Query Filters\n    description: Apply automatic filtering to all queries for multi-tenancy and soft\n      deletes.\n  - name: Value Converters\n    description: Custom type conversions between .NET types and database column types.\n  - name: Compiled Queries\n    description: Pre-compile LINQ queries for improved performance in hot paths.\n- type: UseCases\n  data:\n  - name: Web Application Data Access\n    description: Data access layer for ASP.NET Core web applications and APIs.\n  - name: Microservices Data Layer\n    description: Database access for .NET microservices with per-service databases.\n  - name: Database Migration Management\n    description: Version-controlled schema evolution with automatic migration generation.\n  - name: Multi-Database Applications\n    description: Applications\
  \ connecting to multiple database providers simultaneously.\n  - name: Domain-Driven Design\n    description: Implement DDD patterns with aggregate roots, value objects, and repositories.\n  - name: Legacy Database Integration\n    description: Map existing database schemas to modern .NET classes with Database\n      First.\n- type: Solutions\n  data:\n  - name: Entity Framework Core\n    description: Modern, cross-platform ORM for .NET 6+ applications.\n  - name: Entity Framework 6\n    description: Mature ORM for .NET Framework applications.\n  - name: EF Core Tools\n    description: CLI and Package Manager Console tools for migrations and scaffolding.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-entity-framework/refs/heads/main/apis.yml
tags:
- .NET
- Data Access
- Database
- Entity Framework
- ORM
url: https://raw.githubusercontent.com/api-evangelist/microsoft-entity-framework/refs/heads/main/apis.yml
use_cases:
- description: Data access layer for ASP.NET Core web applications and APIs.
  name: Web Application Data Access
- description: Database access for .NET microservices with per-service databases.
  name: Microservices Data Layer
- description: Version-controlled schema evolution with automatic migration generation.
  name: Database Migration Management
- description: Applications connecting to multiple database providers simultaneously.
  name: Multi-Database Applications
- description: Implement DDD patterns with aggregate roots, value objects, and repositories.
  name: Domain-Driven Design
- description: Map existing database schemas to modern .NET classes with Database First.
  name: Legacy Database Integration
---
