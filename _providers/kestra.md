---
api_count: 6
api_specs:
- filename: open-source
  format: yaml
  label: Kestra Flows API
  slug: flows-api
  spec_type: OpenAPI
  url: https://kestra.io/docs/api-reference/open-source
- filename: open-source
  format: yaml
  label: Kestra Executions API
  slug: executions-api
  spec_type: OpenAPI
  url: https://kestra.io/docs/api-reference/open-source
- filename: open-source
  format: yaml
  label: Kestra Namespaces API
  slug: namespaces-api
  spec_type: OpenAPI
  url: https://kestra.io/docs/api-reference/open-source
- filename: open-source
  format: yaml
  label: Kestra Key-Value Store API
  slug: kv-store-api
  spec_type: OpenAPI
  url: https://kestra.io/docs/api-reference/open-source
- filename: open-source
  format: yaml
  label: Kestra Namespace Files API
  slug: namespace-files-api
  spec_type: OpenAPI
  url: https://kestra.io/docs/api-reference/open-source
apis:
- description: The Kestra Flows API provides programmatic access to manage workflow definitions in the Kestra orchestration platform. It enables creating, updating, retrieving, and deleting flows defined in YAML, su
  name: Kestra Flows API
  slug: flows-api
- description: The Kestra Executions API allows triggering workflow executions, monitoring their state, retrieving execution details including task run outputs and state transitions, and managing the lifecycle of ru
  name: Kestra Executions API
  slug: executions-api
- description: The Kestra Namespaces API provides endpoints for managing namespaces, which serve as logical groupings for organizing flows, files, secrets, and key-value pairs within the Kestra platform.
  name: Kestra Namespaces API
  slug: namespaces-api
- description: The Kestra Key-Value Store API enables storing and retrieving key-value pairs within namespaces, providing a simple data persistence mechanism for workflows to share state and configuration across exe
  name: Kestra Key-Value Store API
  slug: kv-store-api
- description: The Kestra Namespace Files API provides endpoints for listing, uploading, and downloading files within namespaces, enabling file management for workflows that need to work with scripts, configurations
  name: Kestra Namespace Files API
  slug: namespace-files-api
- description: The Kestra Enterprise API extends the open-source API with additional endpoints for enterprise features including authentication, RBAC, audit logging, multi-tenancy, SSO, and advanced governance capab
  name: Kestra Enterprise API
  slug: enterprise-api
common:
- title: ''
  type: Portal
  url: https://kestra.io/
- title: ''
  type: Documentation
  url: https://kestra.io/docs
- title: ''
  type: GettingStarted
  url: https://kestra.io/docs/quickstart
- title: ''
  type: Tutorials
  url: https://kestra.io/docs/tutorial
- title: ''
  type: APIReference
  url: https://kestra.io/docs/api-reference
- title: ''
  type: APIReference
  url: https://kestra.io/docs/api-reference/open-source
- title: ''
  type: Authentication
  url: https://kestra.io/docs/enterprise/auth/api
- title: ''
  type: SDKs
  url: https://kestra.io/docs/api-reference/kestra-sdk
- title: ''
  type: Blog
  url: https://kestra.io/blogs
- title: ''
  type: ChangeLog
  url: https://kestra.io/docs/changelog
- title: ''
  type: Pricing
  url: https://kestra.io/pricing
- title: ''
  type: Support
  url: https://support.kestra.io/hc/en-us
- title: ''
  type: Community
  url: https://kestra.io/community
- title: ''
  type: FAQ
  url: https://kestra.io/faq
- title: ''
  type: GitHubOrganization
  url: https://github.com/kestra-io
- title: ''
  type: GitHubRepository
  url: https://github.com/kestra-io/kestra
- title: ''
  type: Terraform
  url: https://kestra.io/docs/terraform
- title: ''
  type: PrivacyPolicy
  url: https://kestra.io/privacy-policy
- title: ''
  type: TermsOfService
  url: https://kestra.io/terms-and-services
- title: ''
  type: Contact
  url: https://kestra.io/contact-us
created: '2026-03-03'
description: Kestra is a declarative workflow orchestration platform where pipelines are defined in YAML, combining visual and code-first approaches.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Kestra
skills: []
slug: kestra
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kestra\nname: Kestra\nsegments:\n  - Workflows\ndescription: >-\n  Kestra is a declarative workflow orchestration platform where pipelines are defined in YAML, combining visual and code-first approaches.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - Data Pipelines\n  - Event-Driven\n  - Orchestration\n  - Workflows\ncreated: '2026-03-03'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/kestra/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: kestra:flows-api\n    name: Kestra Flows API\n    description: >-\n      The Kestra Flows API provides programmatic access to manage workflow\n      definitions in the Kestra orchestration platform. It enables creating,\n      updating, retrieving, and deleting flows defined in YAML, supporting\n      the full lifecycle of workflow management via REST endpoints.\n  \
  \  humanURL: https://kestra.io/docs/api-reference\n    tags:\n      - Flows\n      - Orchestration\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://kestra.io/docs/api-reference\n      - type: OpenAPI\n        url: https://kestra.io/docs/api-reference/open-source\n  - aid: kestra:executions-api\n    name: Kestra Executions API\n    description: >-\n      The Kestra Executions API allows triggering workflow executions,\n      monitoring their state, retrieving execution details including task\n      run outputs and state transitions, and managing the lifecycle of\n      running workflows programmatically.\n    humanURL: https://kestra.io/docs/api-reference\n    tags:\n      - Executions\n      - Orchestration\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://kestra.io/docs/api-reference\n      - type: OpenAPI\n        url: https://kestra.io/docs/api-reference/open-source\n  - aid: kestra:namespaces-api\n    name:\
  \ Kestra Namespaces API\n    description: >-\n      The Kestra Namespaces API provides endpoints for managing namespaces,\n      which serve as logical groupings for organizing flows, files, secrets,\n      and key-value pairs within the Kestra platform.\n    humanURL: https://kestra.io/docs/api-reference\n    tags:\n      - Namespaces\n      - Orchestration\n      - Organization\n    properties:\n      - type: Documentation\n        url: https://kestra.io/docs/api-reference\n      - type: OpenAPI\n        url: https://kestra.io/docs/api-reference/open-source\n  - aid: kestra:kv-store-api\n    name: Kestra Key-Value Store API\n    description: >-\n      The Kestra Key-Value Store API enables storing and retrieving key-value\n      pairs within namespaces, providing a simple data persistence mechanism\n      for workflows to share state and configuration across executions.\n    humanURL: https://kestra.io/docs/how-to-guides/api\n    tags:\n      - Key-Value Store\n      - State Management\n\
  \      - Storage\n    properties:\n      - type: Documentation\n        url: https://kestra.io/docs/how-to-guides/api\n      - type: OpenAPI\n        url: https://kestra.io/docs/api-reference/open-source\n  - aid: kestra:namespace-files-api\n    name: Kestra Namespace Files API\n    description: >-\n      The Kestra Namespace Files API provides endpoints for listing,\n      uploading, and downloading files within namespaces, enabling file\n      management for workflows that need to work with scripts, configurations,\n      or other file-based resources.\n    humanURL: https://kestra.io/docs/how-to-guides/api\n    tags:\n      - Files\n      - Namespaces\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://kestra.io/docs/how-to-guides/api\n      - type: OpenAPI\n        url: https://kestra.io/docs/api-reference/open-source\n  - aid: kestra:enterprise-api\n    name: Kestra Enterprise API\n    description: >-\n      The Kestra Enterprise API extends the open-source\
  \ API with additional\n      endpoints for enterprise features including authentication, RBAC,\n      audit logging, multi-tenancy, SSO, and advanced governance\n      capabilities for production deployments.\n    humanURL: https://kestra.io/docs/api-reference/enterprise\n    tags:\n      - Authentication\n      - Enterprise\n      - Governance\n      - RBAC\n    properties:\n      - type: Documentation\n        url: https://kestra.io/docs/api-reference/enterprise\n      - type: Authentication\n        url: https://kestra.io/docs/enterprise/auth/api\ncommon:\n  - type: Portal\n    url: https://kestra.io/\n    name: Kestra Website\n  - type: Documentation\n    url: https://kestra.io/docs\n    name: Kestra Documentation\n  - type: GettingStarted\n    url: https://kestra.io/docs/quickstart\n    name: Kestra Quickstart Guide\n  - type: Tutorials\n    url: https://kestra.io/docs/tutorial\n    name: Kestra Tutorial\n  - type: APIReference\n    url: https://kestra.io/docs/api-reference\n    name:\
  \ Kestra API Reference\n  - type: APIReference\n    url: https://kestra.io/docs/api-reference/open-source\n    name: Kestra Open Source API Reference\n  - type: Authentication\n    url: https://kestra.io/docs/enterprise/auth/api\n    name: Kestra Enterprise API Authentication\n  - type: SDKs\n    url: https://kestra.io/docs/api-reference/kestra-sdk\n    name: Kestra SDKs\n  - type: Blog\n    url: https://kestra.io/blogs\n    name: Kestra Blog\n  - type: ChangeLog\n    url: https://kestra.io/docs/changelog\n    name: Kestra Changelog\n  - type: Pricing\n    url: https://kestra.io/pricing\n    name: Kestra Pricing\n  - type: Support\n    url: https://support.kestra.io/hc/en-us\n    name: Kestra Support\n  - type: Community\n    url: https://kestra.io/community\n    name: Kestra Community\n  - type: FAQ\n    url: https://kestra.io/faq\n    name: Kestra FAQ\n  - type: GitHubOrganization\n    url: https://github.com/kestra-io\n    name: Kestra GitHub Organization\n  - type: GitHubRepository\n\
  \    url: https://github.com/kestra-io/kestra\n    name: Kestra GitHub Repository\n  - type: Integrations\n    url: https://kestra.io/plugins/\n    name: Kestra Plugins\n  - type: Terraform\n    url: https://kestra.io/docs/terraform\n    name: Kestra Terraform Provider\n  - type: PrivacyPolicy\n    url: https://kestra.io/privacy-policy\n    name: Kestra Privacy Policy\n  - type: TermsOfService\n    url: https://kestra.io/terms-and-services\n    name: Kestra Terms of Service\n  - type: Contact\n    url: https://kestra.io/contact-us\n    name: Kestra Contact\n  - type: Features\n    url: https://kestra.io/features/api-first\n    name: Kestra API-First Architecture\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kestra/refs/heads/main/apis.yml
tags:
- Automation
- Data Pipelines
- Event-Driven
- Orchestration
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/kestra/refs/heads/main/apis.yml
use_cases: []
---
