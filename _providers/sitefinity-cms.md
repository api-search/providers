---
api_count: 5
api_specs:
- filename: sitefinity-cms-content-api-openapi.yml
  format: yaml
  label: Sitefinity CMS Content API
  slug: content-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitefinity-cms/refs/heads/main/openapi/sitefinity-cms-content-api-openapi.yml
apis:
- description: The Sitefinity CMS Content API provides RESTful access to all content types defined in a Sitefinity instance. Developers use it to create, read, update, and delete content items, manage content transl
  name: Sitefinity CMS Content API
  slug: content-api
- description: The Sitefinity CMS Pages API provides REST endpoints for managing the page hierarchy, page properties, page templates, and page nodes. Developers use it to automate page creation, update navigation st
  name: Sitefinity CMS Pages API
  slug: pages-api
- description: The Sitefinity CMS Users and Roles API provides REST endpoints for managing user accounts, roles, and permissions. Developers use this API to automate user provisioning, manage role assignments, and i
  name: Sitefinity CMS Users and Roles API
  slug: users-roles-api
- description: The Sitefinity CMS Media API provides REST endpoints for managing images, videos, documents, and other media items stored in Sitefinity libraries. Developers use it to upload, retrieve, update, and de
  name: Sitefinity CMS Media API
  slug: media-api
- description: The Sitefinity CMS Taxonomies API provides REST endpoints for managing taxonomies, categories, and tags used to classify and organize content. Developers use it to create classification structures, as
  name: Sitefinity CMS Taxonomies API
  slug: taxonomies-api
capabilities:
- description: Unified capability for managing Sitefinity CMS content including news items, blog posts, events, and media. Enables content operations teams and developers to automate content lifecycle management, pu
  name: Sitefinity CMS Content Management
  slug: content-management
common:
- title: ''
  type: Website
  url: https://www.progress.com/sitefinity-cms
- title: ''
  type: Documentation
  url: https://www.progress.com/documentation/sitefinity-cms
- title: ''
  type: Portal
  url: https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api
- title: ''
  type: Blog
  url: https://www.progress.com/blogs/sitefinity
- title: ''
  type: Support
  url: https://www.progress.com/support
- title: ''
  type: JSON-LD
  url: json-ld/sitefinity-cms-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/sitefinity-cms-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/sitefinity-cms-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/content-management.yaml
created: '2025-01-08'
description: Sitefinity CMS is a .NET-based content management system developed by Progress Software that provides REST APIs for managing content items, pages, users, roles, taxonomies, media, and e-commerce resources. Developers use the Sitefinity REST API to build headless front-ends, integrate third-party systems, automate content operations, and extend the platform with custom modules.
features: []
image: ''
integrations: []
jsonld:
- class_count: 24
  name: Sitefinity Cms Context
  property_count: 2
  slug: sitefinity-cms-context
layout: provider
modified: '2026-05-02'
name: Sitefinity CMS
rules:
- name: Sitefinity CMS API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 3
    warn: 4
  slug: sitefinity-cms-rules
skills: []
slug: sitefinity-cms
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sitefinity-cms\nurl: https://raw.githubusercontent.com/api-evangelist/sitefinity-cms/refs/heads/main/apis.yml\nname: Sitefinity CMS\ndescription: >-\n  Sitefinity CMS is a .NET-based content management system developed by Progress Software\n  that provides REST APIs for managing content items, pages, users, roles, taxonomies,\n  media, and e-commerce resources. Developers use the Sitefinity REST API to build\n  headless front-ends, integrate third-party systems, automate content operations,\n  and extend the platform with custom modules.\ntags:\n  - Content Management\n  - Headless CMS\n  - .NET\n  - REST\ncreated: '2025-01-08'\nmodified: '2026-05-02'\n\napis:\n  - aid: sitefinity-cms:content-api\n    name: Sitefinity CMS Content API\n    description: >-\n      The Sitefinity CMS Content API provides RESTful access to all content types\n      defined in a Sitefinity instance. Developers use it to create, read, update, and\n      delete content items, manage content translations,\
  \ publish and unpublish items,\n      and query content with filtering, sorting, and pagination. The API is organized\n      around content type endpoints generated dynamically from the Sitefinity content\n      model, enabling custom content types to be accessed via consistent patterns.\n    humanURL: https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api\n    baseURL: https://your-site.sitefinity.com/api/default\n    tags:\n      - Content Management\n      - Content Types\n      - REST\n    properties:\n      - url: https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/sitefinity-cms-content-api-openapi.yml\n\n  - aid: sitefinity-cms:pages-api\n    name: Sitefinity CMS Pages API\n    description: >-\n      The Sitefinity CMS Pages API provides REST endpoints for managing the page\n      hierarchy, page properties, page templates, and page nodes. Developers use it\n\
  \      to automate page creation, update navigation structures, manage URL routing,\n      and integrate page management into CI/CD workflows. The Pages API is part of\n      the broader Sitefinity REST infrastructure and supports standard CRUD operations.\n    humanURL: https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-pages\n    baseURL: https://your-site.sitefinity.com/api/default\n    tags:\n      - Pages\n      - Content Management\n      - REST\n    properties:\n      - url: https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-pages\n        type: Documentation\n\n  - aid: sitefinity-cms:users-roles-api\n    name: Sitefinity CMS Users and Roles API\n    description: >-\n      The Sitefinity CMS Users and Roles API provides REST endpoints for managing\n      user accounts, roles, and permissions. Developers use this API to automate user\n      provisioning, manage role assignments, and integrate Sitefinity identity management\n\
  \      with external identity providers. The Roles API exposes operations for listing,\n      creating, and updating roles and their associated permissions.\n    humanURL: https://www.progress.com/documentation/sitefinity-cms/for-developers-roles-api\n    baseURL: https://your-site.sitefinity.com/api/default\n    tags:\n      - Users\n      - Roles\n      - Identity\n      - REST\n    properties:\n      - url: https://www.progress.com/documentation/sitefinity-cms/for-developers-roles-api\n        type: Documentation\n\n  - aid: sitefinity-cms:media-api\n    name: Sitefinity CMS Media API\n    description: >-\n      The Sitefinity CMS Media API provides REST endpoints for managing images, videos,\n      documents, and other media items stored in Sitefinity libraries. Developers use it\n      to upload, retrieve, update, and delete media assets programmatically, supporting\n      headless media workflows and integrations with digital asset management pipelines.\n    humanURL: https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-media\n\
  \    baseURL: https://your-site.sitefinity.com/api/default\n    tags:\n      - Media\n      - Digital Assets\n      - Libraries\n      - REST\n    properties:\n      - url: https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-media\n        type: Documentation\n\n  - aid: sitefinity-cms:taxonomies-api\n    name: Sitefinity CMS Taxonomies API\n    description: >-\n      The Sitefinity CMS Taxonomies API provides REST endpoints for managing taxonomies,\n      categories, and tags used to classify and organize content. Developers use it to\n      create classification structures, assign taxonomy items to content, and query\n      content by taxonomy dimension for filtering and navigation.\n    humanURL: https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api\n    baseURL: https://your-site.sitefinity.com/api/default\n    tags:\n      - Taxonomies\n      - Classification\n      - Content Management\n      - REST\n    properties:\n      - url:\
  \ https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api\n        type: Documentation\n\ncommon:\n  - type: Website\n    url: https://www.progress.com/sitefinity-cms\n  - type: Documentation\n    url: https://www.progress.com/documentation/sitefinity-cms\n  - type: Portal\n    url: https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api\n  - type: Blog\n    url: https://www.progress.com/blogs/sitefinity\n  - type: Support\n    url: https://www.progress.com/support\n  - type: JSON-LD\n    url: json-ld/sitefinity-cms-context.jsonld\n  - type: SpectralRules\n    url: rules/sitefinity-cms-rules.yml\n  - type: Vocabulary\n    url: vocabulary/sitefinity-cms-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/content-management.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sitefinity-cms/refs/heads/main/apis.yml
tags:
- Content Management
- Headless CMS
- .NET
- REST
url: https://raw.githubusercontent.com/api-evangelist/sitefinity-cms/refs/heads/main/apis.yml
use_cases: []
---
