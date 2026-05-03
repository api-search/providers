---
api_count: 5
apis:
- description: Semantic Versioning is a versioning scheme using a MAJOR.MINOR.PATCH format where MAJOR increments denote breaking changes, MINOR increments indicate new backward-compatible features, and PATCH increm
  name: Semantic Versioning (SemVer)
  slug: semver
- description: Calendar Versioning (CalVer) uses the release date as the version identifier, typically in YYYY.MM.DD or YYYY-MM-DD format. Used by APIs like Stripe (date-based versions e.g., 2024-06-01) to communica
  name: Calendar Versioning (CalVer)
  slug: calver
- description: URI path versioning embeds the API version in the URL path, typically as the major version number (e.g., /v1/users, /v2/users). The most widely adopted strategy for public REST APIs due to its explici
  name: URI Path Versioning
  slug: uri-path-versioning
- description: 'Header-based versioning passes the API version in a custom HTTP request header (e.g., API-Version: 2026-04-01 or Accept: application/vnd.api.v2+json), keeping URLs clean and enabling more granular ver'
  name: Header-Based Versioning
  slug: header-versioning
- description: OpenAPI handles versioning through the info.version field (using SemVer), the deprecated flag on individual operations, parameters, and schemas, and multiple server entries for different API versions.
  name: OpenAPI Versioning
  slug: openapi-versioning
common:
- title: ''
  type: Website
  url: https://semver.org/
- title: ''
  type: Documentation
  url: https://semver.org/spec/v2.0.0.html
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/versioning-protocols/refs/heads/main/vocabulary/versioning-protocols-vocabulary.yaml
created: '2025'
description: Standards and methodologies for managing changes and updates to APIs, software interfaces, and data formats while maintaining backward compatibility and clear communication of breaking changes. Covers Semantic Versioning (SemVer), Calendar Versioning (CalVer), URI path versioning, header-based versioning, and deprecation management strategies. Used by developers, platform teams, and API governance programs to build maintainable and predictable API lifecycle policies.
features:
- description: MAJOR.MINOR.PATCH versioning that communicates the impact of changes on API consumers.
  name: Semantic Versioning
- description: Date-based versioning (YYYY.MM.DD) that communicates the freshness of an API release.
  name: Calendar Versioning
- description: Embedding the API major version in the URL path for explicit, cache-friendly versioning.
  name: URI Path Versioning
- description: Passing the API version in HTTP headers for clean URL structures and content negotiation.
  name: Header-Based Versioning
- description: Appending the version to request URLs as a query string parameter (e.g., ?version=2).
  name: Query Parameter Versioning
- description: Structured policies for communicating and retiring old API versions with adequate notice.
  name: Deprecation Management
- description: Tooling and processes to identify breaking changes between API versions using spec diffing.
  name: Breaking Change Detection
- description: Support policy maintaining the current major version plus the two previous versions before retirement.
  name: N-2 Support Policy
image: ''
integrations:
- description: Deploy version routing plugins, deprecation headers, and logging in Kong for API versioning.
  name: Kong API Gateway
- description: Support versioned API proxies and detailed version analytics in Google Apigee.
  name: Apigee
- description: Run different stages for version control and access management in AWS API Gateway.
  name: AWS API Gateway
- description: First-class support for multiple API versions and revisions in Azure APIM.
  name: Azure API Management
- description: Open-source tool for detecting breaking changes between OpenAPI specification versions.
  name: oasdiff
- description: API documentation and governance platform with versioning and deprecation management features.
  name: Redocly
jsonld:
- class_count: 3
  name: Versioning Protocols Context
  property_count: 22
  slug: versioning-protocols-context
layout: provider
modified: '2026-05-03'
name: Versioning Protocols
skills: []
slug: versioning-protocols
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: versioning-protocols\nname: Versioning Protocols\ndescription: >-\n  Standards and methodologies for managing changes and updates to APIs, software\n  interfaces, and data formats while maintaining backward compatibility and clear\n  communication of breaking changes. Covers Semantic Versioning (SemVer), Calendar\n  Versioning (CalVer), URI path versioning, header-based versioning, and deprecation\n  management strategies. Used by developers, platform teams, and API governance\n  programs to build maintainable and predictable API lifecycle policies.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/versioning-protocols/refs/heads/main/apis.yml\ncreated: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - API Design\n  - Backward Compatibility\n  - Software Development\n  - Version Control\n  - Semantic Versioning\n  - API Lifecycle\n  - Deprecation\napis:\n  - aid: versioning-protocols:semver\n    name: Semantic Versioning (SemVer)\n\
  \    description: >-\n      Semantic Versioning is a versioning scheme using a MAJOR.MINOR.PATCH format\n      where MAJOR increments denote breaking changes, MINOR increments indicate\n      new backward-compatible features, and PATCH increments represent backward-compatible\n      bug fixes. SemVer 2.0.0 is the canonical specification maintained at semver.org.\n    humanURL: https://semver.org/\n    tags:\n      - Semantic Versioning\n      - SemVer\n      - Breaking Changes\n      - API Versioning\n    properties:\n      - type: Documentation\n        url: https://semver.org/\n      - type: Specification\n        url: https://semver.org/spec/v2.0.0.html\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/versioning-protocols/refs/heads/main/json-schema/versioning-protocols-semver-schema.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/versioning-protocols/refs/heads/main/json-structure/versioning-protocols-semver-structure.json\n\
  \n  - aid: versioning-protocols:calver\n    name: Calendar Versioning (CalVer)\n    description: >-\n      Calendar Versioning (CalVer) uses the release date as the version identifier,\n      typically in YYYY.MM.DD or YYYY-MM-DD format. Used by APIs like Stripe (date-based\n      versions e.g., 2024-06-01) to communicate when an API version was released\n      rather than the impact of changes.\n    humanURL: https://calver.org/\n    tags:\n      - Calendar Versioning\n      - CalVer\n      - Date-Based Versioning\n      - API Versioning\n    properties:\n      - type: Documentation\n        url: https://calver.org/\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/versioning-protocols/refs/heads/main/json-schema/versioning-protocols-calver-schema.json\n\n  - aid: versioning-protocols:uri-path-versioning\n    name: URI Path Versioning\n    description: >-\n      URI path versioning embeds the API version in the URL path, typically as the\n      major\
  \ version number (e.g., /v1/users, /v2/users). The most widely adopted\n      strategy for public REST APIs due to its explicitness, cache-friendliness, and\n      ease of documentation. Minor and patch changes are deployed in place under\n      the same major version path.\n    humanURL: https://www.askantech.com/api-versioning-strategies-rest-header-url-deprecation-guide/\n    tags:\n      - URI Versioning\n      - Path Versioning\n      - REST\n      - API Design\n    properties:\n      - type: Documentation\n        url: https://www.askantech.com/api-versioning-strategies-rest-header-url-deprecation-guide/\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/versioning-protocols/refs/heads/main/json-schema/versioning-protocols-uri-path-versioning-schema.json\n\n  - aid: versioning-protocols:header-versioning\n    name: Header-Based Versioning\n    description: >-\n      Header-based versioning passes the API version in a custom HTTP request header\n\
  \      (e.g., API-Version: 2026-04-01 or Accept: application/vnd.api.v2+json), keeping\n      URLs clean and enabling more granular version control. Aligns well with full\n      SemVer strings and content negotiation patterns.\n    humanURL: https://redocly.com/blog/api-versioning-best-practices\n    tags:\n      - Header Versioning\n      - Content Negotiation\n      - REST\n      - API Design\n    properties:\n      - type: Documentation\n        url: https://redocly.com/blog/api-versioning-best-practices\n\n  - aid: versioning-protocols:openapi-versioning\n    name: OpenAPI Versioning\n    description: >-\n      OpenAPI handles versioning through the info.version field (using SemVer),\n      the deprecated flag on individual operations, parameters, and schemas, and\n      multiple server entries for different API versions. Tools like oasdiff enable\n      automated breaking change detection between OpenAPI spec versions.\n    humanURL: https://openapispec.com/docs/how/how-does-openapi-handle-api-versioning/\n\
  \    tags:\n      - OpenAPI\n      - API Specification\n      - Breaking Changes\n      - Deprecation\n    properties:\n      - type: Documentation\n        url: https://openapispec.com/docs/how/how-does-openapi-handle-api-versioning/\n\ncommon:\n  - type: Website\n    url: https://semver.org/\n  - type: Documentation\n    url: https://semver.org/spec/v2.0.0.html\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/versioning-protocols/refs/heads/main/vocabulary/versioning-protocols-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Semantic Versioning\n        description: MAJOR.MINOR.PATCH versioning that communicates the impact of changes on API consumers.\n      - name: Calendar Versioning\n        description: Date-based versioning (YYYY.MM.DD) that communicates the freshness of an API release.\n      - name: URI Path Versioning\n        description: Embedding the API major version in the URL path for explicit, cache-friendly versioning.\n  \
  \    - name: Header-Based Versioning\n        description: Passing the API version in HTTP headers for clean URL structures and content negotiation.\n      - name: Query Parameter Versioning\n        description: Appending the version to request URLs as a query string parameter (e.g., ?version=2).\n      - name: Deprecation Management\n        description: Structured policies for communicating and retiring old API versions with adequate notice.\n      - name: Breaking Change Detection\n        description: Tooling and processes to identify breaking changes between API versions using spec diffing.\n      - name: N-2 Support Policy\n        description: Support policy maintaining the current major version plus the two previous versions before retirement.\n  - type: UseCases\n    data:\n      - name: API Lifecycle Governance\n        description: Establish organizational versioning policies that balance innovation with backward compatibility.\n      - name: Breaking Change Communication\n\
  \        description: Communicate breaking changes clearly to API consumers with version bumps and deprecation notices.\n      - name: Multi-Version Support\n        description: Maintain multiple active API versions simultaneously to support consumers at different adoption stages.\n      - name: Automated Change Detection\n        description: Integrate spec diffing tools into CI/CD pipelines to detect breaking changes before release.\n      - name: Deprecation Planning\n        description: Plan and execute API version deprecations with 12-18 months notice and migration guides.\n  - type: Integrations\n    data:\n      - name: Kong API Gateway\n        description: Deploy version routing plugins, deprecation headers, and logging in Kong for API versioning.\n      - name: Apigee\n        description: Support versioned API proxies and detailed version analytics in Google Apigee.\n      - name: AWS API Gateway\n        description: Run different stages for version control and access management\
  \ in AWS API Gateway.\n      - name: Azure API Management\n        description: First-class support for multiple API versions and revisions in Azure APIM.\n      - name: oasdiff\n        description: Open-source tool for detecting breaking changes between OpenAPI specification versions.\n      - name: Redocly\n        description: API documentation and governance platform with versioning and deprecation management features.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/versioning-protocols/refs/heads/main/apis.yml
tags:
- API Design
- Backward Compatibility
- Software Development
- Version Control
- Semantic Versioning
- API Lifecycle
- Deprecation
url: https://raw.githubusercontent.com/api-evangelist/versioning-protocols/refs/heads/main/apis.yml
use_cases:
- description: Establish organizational versioning policies that balance innovation with backward compatibility.
  name: API Lifecycle Governance
- description: Communicate breaking changes clearly to API consumers with version bumps and deprecation notices.
  name: Breaking Change Communication
- description: Maintain multiple active API versions simultaneously to support consumers at different adoption stages.
  name: Multi-Version Support
- description: Integrate spec diffing tools into CI/CD pipelines to detect breaking changes before release.
  name: Automated Change Detection
- description: Plan and execute API version deprecations with 12-18 months notice and migration guides.
  name: Deprecation Planning
---
