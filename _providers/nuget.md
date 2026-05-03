---
api_count: 5
api_specs:
- filename: nuget-server-api-openapi.yml
  format: yaml
  label: NuGet Server API
  slug: nuget-server-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/openapi/nuget-server-api-openapi.yml
- filename: nuget-catalog-api-openapi.yml
  format: yaml
  label: NuGet Catalog API
  slug: nuget-catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/openapi/nuget-catalog-api-openapi.yml
- filename: nuget-search-api-openapi.yml
  format: yaml
  label: NuGet Search API
  slug: nuget-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/openapi/nuget-search-api-openapi.yml
- filename: nuget-package-metadata-api-openapi.yml
  format: yaml
  label: NuGet Package Metadata API
  slug: nuget-package-metadata-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/openapi/nuget-package-metadata-api-openapi.yml
- filename: nuget-package-content-api-openapi.yml
  format: yaml
  label: NuGet Package Content API
  slug: nuget-package-content-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/openapi/nuget-package-content-api-openapi.yml
apis:
- description: The NuGet Server API is a set of HTTP endpoints used to download packages, fetch metadata, publish new packages, and perform other operations against a NuGet package source. The V3 API uses JSON as it
  name: NuGet Server API
  slug: nuget-server-api
- description: 'The NuGet Catalog API is an append-only resource that records the full history of all package events on nuget.org, including packages being added, modified, listed, unlisted, and deleted. It provides '
  name: NuGet Catalog API
  slug: nuget-catalog-api
- description: The NuGet Search API allows clients to query for packages available on a NuGet package source using the SearchQueryService resource found in the service index. It supports filtering by keyword, target
  name: NuGet Search API
  slug: nuget-search-api
- description: The NuGet Package Metadata API, accessed through the RegistrationsBaseUrl resource, provides detailed metadata about packages available on a NuGet package source. It returns registration information i
  name: NuGet Package Metadata API
  slug: nuget-package-metadata-api
- description: 'The NuGet Package Content API, accessed through the PackageBaseAddress resource, allows clients to download package content files (.nupkg) and package manifests (.nuspec) from a NuGet feed. It uses a '
  name: NuGet Package Content API
  slug: nuget-package-content-api
common:
- title: ''
  type: Portal
  url: https://learn.microsoft.com/en-us/nuget/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/nuget/api/overview
- title: ''
  type: Website
  url: https://www.nuget.org/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: TermsOfService
  url: https://www.nuget.org/policies/Terms
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/nuget/
- title: ''
  type: Login
  url: https://www.nuget.org/users/account/LogOn
created: '2025-03-05'
description: NuGet is the package manager for .NET, providing a centralized repository for developers to discover, share, and consume reusable code libraries. The NuGet developer platform exposes a set of HTTP APIs that enable programmatic access to package search, metadata retrieval, content download, catalog browsing, and package publishing against the nuget.org feed.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Nuget Context
  property_count: 8
  slug: nuget-context
layout: provider
modified: '2026-04-28'
name: NuGet
skills: []
slug: nuget
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nuget\nname: NuGet\ndescription: >-\n  NuGet is the package manager for .NET, providing a centralized repository for\n  developers to discover, share, and consume reusable code libraries. The NuGet\n  developer platform exposes a set of HTTP APIs that enable programmatic access\n  to package search, metadata retrieval, content download, catalog browsing,\n  and package publishing against the nuget.org feed.\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Package Management\n  - .NET\n  - Packages\n  - Dependencies\n  - Software Distribution\n  - Registry\nurl: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/apis.yml\ncreated: '2025-03-05'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: nuget:nuget-server-api\n    name: NuGet Server API\n    description: >-\n      The NuGet Server API is a set of HTTP endpoints used to download\n      packages, fetch metadata, publish\
  \ new packages, and perform other\n      operations against a NuGet package source. The V3 API uses JSON as its\n      underlying media type and is accessed through a service index located at\n      https://api.nuget.org/v3/index.json, which enumerates all available\n      resources and capabilities.\n    humanURL: https://learn.microsoft.com/en-us/nuget/api/overview\n    tags:\n      - Package Management\n      - .NET\n      - Packages\n      - Registry\n      - Dependencies\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/nuget/api/overview\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/nuget/api/service-index\n      - type: GitHubRepository\n        url: https://github.com/NuGet/NuGetGallery\n      - type: OpenAPI\n        url: openapi/nuget-server-api-openapi.yml\n  - aid: nuget:nuget-catalog-api\n    name: NuGet Catalog API\n    description: >-\n      The NuGet Catalog API is an append-only resource that records\
  \ the full\n      history of all package events on nuget.org, including packages being\n      added, modified, listed, unlisted, and deleted. It provides a\n      chronologically ordered log of every change to the package source,\n      enabling consumers to build and maintain their own local copy of the\n      entire set of packages available on nuget.org.\n    humanURL: https://learn.microsoft.com/en-us/nuget/api/catalog-resource\n    tags:\n      - Package Management\n      - .NET\n      - Catalog\n      - Event Log\n      - Packages\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/nuget/api/catalog-resource\n      - type: OpenAPI\n        url: openapi/nuget-catalog-api-openapi.yml\n  - aid: nuget:nuget-search-api\n    name: NuGet Search API\n    description: >-\n      The NuGet Search API allows clients to query for packages available on a\n      NuGet package source using the SearchQueryService resource found in the\n      service index.\
  \ It supports filtering by keyword, target framework,\n      prerelease status, and package type, and returns paginated results with\n      package metadata including versions, descriptions, download counts, and\n      dependency information.\n    humanURL: https://learn.microsoft.com/en-us/nuget/api/search-query-service-resource\n    tags:\n      - Package Management\n      - .NET\n      - Search\n      - Discovery\n      - Packages\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/nuget/api/search-query-service-resource\n      - type: OpenAPI\n        url: openapi/nuget-search-api-openapi.yml\n  - aid: nuget:nuget-package-metadata-api\n    name: NuGet Package Metadata API\n    description: >-\n      The NuGet Package Metadata API, accessed through the RegistrationsBaseUrl\n      resource, provides detailed metadata about packages available on a NuGet\n      package source. It returns registration information including all\n      available versions\
  \ of a package, their dependencies, download URLs,\n      descriptions, authors, license information, and deprecation status.\n    humanURL: https://learn.microsoft.com/en-us/nuget/api/registration-base-url-resource\n    tags:\n      - Package Management\n      - .NET\n      - Metadata\n      - Package Registry\n      - Versions\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/nuget/api/registration-base-url-resource\n      - type: OpenAPI\n        url: openapi/nuget-package-metadata-api-openapi.yml\n  - aid: nuget:nuget-package-content-api\n    name: NuGet Package Content API\n    description: >-\n      The NuGet Package Content API, accessed through the PackageBaseAddress\n      resource, allows clients to download package content files (.nupkg) and\n      package manifests (.nuspec) from a NuGet feed. It uses a flat container\n      structure where packages are organized by lowercase package ID and\n      version, providing direct access\
  \ to the binary package files.\n    humanURL: https://learn.microsoft.com/en-us/nuget/api/package-base-address-resource\n    tags:\n      - Package Management\n      - .NET\n      - Package Download\n      - Content\n      - NuPkg\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/nuget/api/package-base-address-resource\n      - type: OpenAPI\n        url: openapi/nuget-package-content-api-openapi.yml\ncommon:\n  - type: Portal\n    url: https://learn.microsoft.com/en-us/nuget/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/nuget/api/overview\n  - type: Website\n    url: https://www.nuget.org/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: TermsOfService\n    url: https://www.nuget.org/policies/Terms\n  - type: Blog\n    url: https://devblogs.microsoft.com/nuget/\n  - type: Login\n    url: https://www.nuget.org/users/account/LogOn\nmaintainers:\n  - FN: Kin Lane\n    email:\
  \ kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/apis.yml
tags:
- Package Management
- .NET
- Packages
- Dependencies
- Software Distribution
- Registry
url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/apis.yml
use_cases: []
---
