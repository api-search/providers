---
api_count: 5
api_specs:
- filename: jetbrains-space-openapi.yml
  format: yaml
  label: JetBrains Space HTTP API
  slug: space-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/openapi/jetbrains-space-openapi.yml
- filename: jetbrains-teamcity-openapi.yml
  format: yaml
  label: JetBrains TeamCity REST API
  slug: teamcity-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/openapi/jetbrains-teamcity-openapi.yml
- filename: jetbrains-youtrack-openapi.yml
  format: yaml
  label: JetBrains YouTrack REST API
  slug: youtrack-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/openapi/jetbrains-youtrack-openapi.yml
- filename: jetbrains-hub-openapi.yml
  format: yaml
  label: JetBrains Hub REST API
  slug: hub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/openapi/jetbrains-hub-openapi.yml
- filename: jetbrains-marketplace-openapi.yml
  format: yaml
  label: JetBrains Marketplace API
  slug: marketplace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/openapi/jetbrains-marketplace-openapi.yml
apis:
- description: 'The JetBrains Space HTTP API provides programmatic access to Space functionality including projects, teams, chats, documents, code reviews, packages, and automation jobs. The API uses JSON format and '
  name: JetBrains Space HTTP API
  slug: space-api
- description: The TeamCity REST API provides programmatic access to TeamCity CI/CD server functionality. It allows management of projects, build configurations, builds, agents, VCS roots, users, and more. The API u
  name: JetBrains TeamCity REST API
  slug: teamcity-api
- description: The YouTrack REST API lets you perform programmatic actions in the issue tracker, including creating, modifying, and querying issues, managing projects, agile boards, work items, and more. The API use
  name: JetBrains YouTrack REST API
  slug: youtrack-api
- description: The JetBrains Hub REST API provides programmatic access to Hub, the centralized authentication and authorization service for JetBrains tools. It allows management of users, groups, projects, roles, pe
  name: JetBrains Hub REST API
  slug: hub-api
- description: The JetBrains Marketplace API provides programmatic access to the plugin marketplace for JetBrains IDEs. It allows listing plugins by IDE compatibility, searching for plugins, uploading new plugins an
  name: JetBrains Marketplace API
  slug: marketplace-api
common:
- title: ''
  type: Documentation
  url: https://www.jetbrains.com/help/
- title: ''
  type: Blog
  url: https://blog.jetbrains.com/
- title: ''
  type: Support
  url: https://www.jetbrains.com/support/
- title: ''
  type: Issues
  url: https://youtrack.jetbrains.com/
created: '2025-01-01'
description: JetBrains is a software development company that provides integrated development environments, CI/CD tools, issue tracking, and team collaboration platforms for software developers. Their product suite includes IntelliJ IDEA, TeamCity, YouTrack, Space, Hub, and the JetBrains Marketplace, all of which offer APIs for programmatic integration and automation of development workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 11
  name: Jetbrains Context
  property_count: 7
  slug: jetbrains-context
layout: provider
modified: '2026-04-28'
name: JetBrains
skills: []
slug: jetbrains
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: jetbrains\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/apis.yml\napis:\n  - aid: jetbrains:space-api\n    name: JetBrains Space HTTP API\n    tags:\n      - Collaboration\n      - Developer Tools\n      - Project Management\n    humanURL: https://www.jetbrains.com/help/space/http-api-model.html\n    properties:\n      - url: https://www.jetbrains.com/help/space/http-api-model.html\n        type: Documentation\n      - url: openapi/jetbrains-space-openapi.yml\n        type: OpenAPI\n      - url: json-schema/project.json\n        type: JSONSchema\n      - url: json-schema/user.json\n        type: JSONSchema\n      - url: json-ld/jetbrains-context.jsonld\n        type: JSONLD\n    description: >-\n      The JetBrains Space HTTP API provides programmatic access to Space\n      functionality including projects, teams, chats, documents, code reviews,\n      packages, and automation jobs. The API uses JSON format and supports\n      OAuth\
  \ 2.0 authentication. An HTTP API playground is available within\n      Space for interactive exploration of all available endpoints.\n  - aid: jetbrains:teamcity-api\n    name: JetBrains TeamCity REST API\n    tags:\n      - Build Automation\n      - CI/CD\n      - Developer Tools\n    humanURL: https://www.jetbrains.com/help/teamcity/rest/teamcity-rest-api-documentation.html\n    properties:\n      - url: https://www.jetbrains.com/help/teamcity/rest/teamcity-rest-api-documentation.html\n        type: Documentation\n      - url: openapi/jetbrains-teamcity-openapi.yml\n        type: OpenAPI\n      - url: json-schema/build.json\n        type: JSONSchema\n      - url: json-schema/build-agent.json\n        type: JSONSchema\n      - url: json-schema/project.json\n        type: JSONSchema\n      - url: json-ld/jetbrains-context.jsonld\n        type: JSONLD\n    description: >-\n      The TeamCity REST API provides programmatic access to TeamCity CI/CD\n      server functionality. It allows\
  \ management of projects, build\n      configurations, builds, agents, VCS roots, users, and more. The API\n      uses locators for flexible filtering and supports both JSON and XML\n      formats. The full Swagger specification is available via the\n      /app/rest/swagger.json endpoint.\n  - aid: jetbrains:youtrack-api\n    name: JetBrains YouTrack REST API\n    tags:\n      - Developer Tools\n      - Issue Tracking\n      - Project Management\n    humanURL: https://www.jetbrains.com/help/youtrack/devportal/youtrack-rest-api.html\n    properties:\n      - url: https://www.jetbrains.com/help/youtrack/devportal/youtrack-rest-api.html\n        type: Documentation\n      - url: openapi/jetbrains-youtrack-openapi.yml\n        type: OpenAPI\n      - url: json-schema/issue.json\n        type: JSONSchema\n      - url: json-schema/project.json\n        type: JSONSchema\n      - url: json-schema/user.json\n        type: JSONSchema\n      - url: json-ld/jetbrains-context.jsonld\n        type: JSONLD\n\
  \    description: >-\n      The YouTrack REST API lets you perform programmatic actions in the issue\n      tracker, including creating, modifying, and querying issues, managing\n      projects, agile boards, work items, and more. The API uses JSON format\n      and supports both permanent token and OAuth 2.0 authentication. A\n      Postman collection is available for interactive exploration.\n  - aid: jetbrains:hub-api\n    name: JetBrains Hub REST API\n    tags:\n      - Authentication\n      - Authorization\n      - Identity Management\n    humanURL: https://www.jetbrains.com/help/youtrack/devportal/hub-rest-api-reference.html\n    properties:\n      - url: https://www.jetbrains.com/help/youtrack/devportal/hub-rest-api-reference.html\n        type: Documentation\n      - url: openapi/jetbrains-hub-openapi.yml\n        type: OpenAPI\n      - url: json-schema/user.json\n        type: JSONSchema\n      - url: json-ld/jetbrains-context.jsonld\n        type: JSONLD\n    description: >-\n\
  \      The JetBrains Hub REST API provides programmatic access to Hub, the\n      centralized authentication and authorization service for JetBrains\n      tools. It allows management of users, groups, projects, roles,\n      permissions, and OAuth 2.0 services. Hub serves as the identity\n      provider for YouTrack, TeamCity, and other connected JetBrains services.\n  - aid: jetbrains:marketplace-api\n    name: JetBrains Marketplace API\n    tags:\n      - Developer Tools\n      - Marketplace\n      - Plugins\n    humanURL: https://plugins.jetbrains.com/docs/marketplace/api-reference.html\n    properties:\n      - url: https://plugins.jetbrains.com/docs/marketplace/api-reference.html\n        type: Documentation\n      - url: openapi/jetbrains-marketplace-openapi.yml\n        type: OpenAPI\n      - url: json-schema/plugin.json\n        type: JSONSchema\n      - url: json-ld/jetbrains-context.jsonld\n        type: JSONLD\n    description: >-\n      The JetBrains Marketplace API provides\
  \ programmatic access to the plugin\n      marketplace for JetBrains IDEs. It allows listing plugins by IDE\n      compatibility, searching for plugins, uploading new plugins and updates,\n      downloading plugin files, and checking plugin licenses. The API serves\n      both plugin developers and consumers integrating with the JetBrains\n      plugin ecosystem.\nname: JetBrains\ntags:\n  - CI/CD\n  - Developer Tools\n  - IDE\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://www.jetbrains.com/help/\n    name: JetBrains Documentation\n    type: Documentation\n    description: 'null'\n  - url: https://blog.jetbrains.com/\n    name: JetBrains Blog\n    type: Blog\n    description: 'null'\n  - url: https://www.jetbrains.com/support/\n    name: JetBrains Support\n    type: Support\n    description: 'null'\n  - url: https://youtrack.jetbrains.com/\n    name: JetBrains Issue Tracker\n    type: Issues\n\
  \    description: 'null'\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  JetBrains is a software development company that provides integrated\n  development environments, CI/CD tools, issue tracking, and team\n  collaboration platforms for software developers. Their product suite\n  includes IntelliJ IDEA, TeamCity, YouTrack, Space, Hub, and the\n  JetBrains Marketplace, all of which offer APIs for programmatic\n  integration and automation of development workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/apis.yml
tags:
- CI/CD
- Developer Tools
- IDE
url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/apis.yml
use_cases: []
---
