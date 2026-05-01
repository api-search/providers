---
api_count: 7
api_specs:
- filename: datahub-openapi-openapi.yml
  format: yaml
  label: DataHub OpenAPI
  slug: datahub-openapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/datahub/refs/heads/main/openapi/datahub-openapi-openapi.yml
- filename: datahub-actions-asyncapi.yml
  format: yaml
  label: DataHub Actions Framework
  slug: datahub-actions-framework
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/datahub/refs/heads/main/asyncapi/datahub-actions-asyncapi.yml
apis:
- description: 'Primary API for querying and mutating metadata in DataHub. The GraphQL API serves as the main public API for the platform and can be used to fetch and update metadata programmatically in the language '
  name: DataHub GraphQL API
  slug: datahub-graphql-api
- description: RESTful API endpoints documented using the OpenAPI standard for interacting with DataHub metadata. Provides endpoints for entities, relationships, timeline, and platform events. The OpenAPI spec is au
  name: DataHub OpenAPI
  slug: datahub-openapi
- description: The Rest.li API represents the underlying persistence layer and exposes the raw PDL models used in storage. It powers the GraphQL API under the hood and is used for system-specific ingestion of metada
  name: DataHub REST API
  slug: datahub-rest-api
- description: 'Python client for interacting with DataHub. The acryl-datahub package provides a CLI and SDK for DataHub, including REST and Kafka emitter APIs for pushing metadata programmatically. It is one of the '
  name: DataHub Python SDK
  slug: datahub-python-sdk
- description: Java client for interacting with DataHub. The io.acryl datahub-client package offers REST emitter APIs that can be used to emit metadata from JVM-based systems. It supports all major DataHub entity ty
  name: DataHub Java SDK
  slug: datahub-java-sdk
- description: Command line tool for interacting with DataHub. The datahub CLI allows you to perform common operations including metadata ingestion, entity management, and system administration from the command line
  name: DataHub CLI
  slug: datahub-cli
- description: Event-driven framework for responding to real-time changes in the DataHub metadata graph. The Actions Framework allows you to configure event sources, transformations, and actions using YAML configura
  name: DataHub Actions Framework
  slug: datahub-actions-framework
asyncapis:
- description: Event-driven interface for responding to real-time changes in the DataHub metadata graph. The Actions Framework consumes Metadata Change Log events and Platform Events from Kafka topics, enabling seam
  name: DataHub Actions Framework Events
  slug: datahub-actions-asyncapi
capabilities: []
common:
- title: ''
  type: Website
  url: https://datahub.com
- title: ''
  type: Portal
  url: https://docs.datahub.com
- title: ''
  type: Documentation
  url: https://docs.datahub.com/docs/
- title: ''
  type: Getting Started
  url: https://docs.datahub.com/docs/quickstart
- title: ''
  type: Authentication
  url: https://docs.datahub.com/docs/authentication
- title: ''
  type: GitHubRepository
  url: https://github.com/datahub-project/datahub
- title: ''
  type: Slack
  url: https://slack.datahubproject.io
- title: ''
  type: Blog
  url: https://datahub.com/blog/
- title: ''
  type: Demo
  url: https://demo.datahubproject.io/
- title: ''
  type: Change Log
  url: https://github.com/datahub-project/datahub/releases
- title: ''
  type: Status
  url: https://status.datahub.com
- title: ''
  type: Community
  url: https://forum.datahubproject.io/
- title: ''
  type: YouTube
  url: https://youtube.com/@datahubproject
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/datahub-cloud
- title: ''
  type: Privacy Policy
  url: https://datahub.com/privacy-policy/
- title: ''
  type: Security
  url: https://docs.datahub.com/docs/security_stance
- title: ''
  type: JSON-LD
  url: json-ld/datahub-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/datahub-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/datahub-capabilities.yml
- title: ''
  type: Rules
  url: rules/datahub-rules.yml
created: '2024-01-15'
description: DataHub is LinkedIn's generalized metadata search and discovery platform, providing a unified data catalog, lineage graph, governance tooling, and event-driven Actions Framework. It exposes GraphQL, OpenAPI, and Rest.li APIs along with Python and Java SDKs and a CLI for metadata ingestion.
features: []
image: https://datahubproject.io/img/datahub-logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Datahub Context
  property_count: 9
  slug: datahub-context
layout: provider
modified: '2026-04-28'
name: DataHub
rules:
- name: DataHub API Rules
  rule_count: 5
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 4
  slug: datahub-rules
skills: []
slug: datahub
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: datahub\nname: DataHub\ndescription: >-\n  DataHub is LinkedIn's generalized metadata search and discovery platform,\n  providing a unified data catalog, lineage graph, governance tooling, and\n  event-driven Actions Framework. It exposes GraphQL, OpenAPI, and Rest.li\n  APIs along with Python and Java SDKs and a CLI for metadata ingestion.\nimage: https://datahubproject.io/img/datahub-logo.svg\ntype: Index\ntags:\n  - Data Catalog\n  - Data Discovery\n  - Data Governance\n  - Data Lineage\n  - Metadata\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/datahub/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\nxType: opensource\nposition: Consumer\naccess: 3rd-Party\napis:\n  - aid: datahub:datahub-graphql-api\n    name: DataHub GraphQL API\n    description: >-\n      Primary API for querying and mutating metadata in DataHub. The GraphQL API\n      serves as the main public API for the platform and can be used\
  \ to fetch and\n      update metadata programmatically in the language of your choice. It mirrors\n      the capabilities available in the DataHub UI.\n    image: https://datahubproject.io/img/datahub-logo.svg\n    humanURL: https://docs.datahub.com/docs/api/graphql/overview\n    baseURL: http://localhost:8080/api/graphql\n    tags:\n      - GraphQL\n      - Metadata\n      - Queries\n      - Search\n    properties:\n      - type: Documentation\n        url: https://docs.datahub.com/docs/api/graphql/overview\n      - type: Getting Started\n        url: https://docs.datahub.com/docs/api/graphql/getting-started\n      - type: Reference\n        url: https://docs.datahub.com/docs/graphql/queries\n      - type: Playground\n        url: http://localhost:8080/api/graphiql\n  - aid: datahub:datahub-openapi\n    name: DataHub OpenAPI\n    description: >-\n      RESTful API endpoints documented using the OpenAPI standard for interacting\n      with DataHub metadata. Provides endpoints for entities,\
  \ relationships,\n      timeline, and platform events. The OpenAPI spec is auto-generated and\n      available via Swagger UI for interactive exploration. Recommended for\n      advanced users who need lower-level access to the metadata graph.\n    image: https://datahubproject.io/img/datahub-logo.svg\n    humanURL: https://docs.datahub.com/docs/api/openapi/openapi-usage-guide\n    baseURL: http://localhost:8080/openapi/\n    tags:\n      - Entities\n      - Metadata\n      - OpenAPI\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.datahub.com/docs/api/openapi/openapi-usage-guide\n      - type: OpenAPI\n        url: openapi/datahub-openapi-openapi.yml\n      - type: JSONSchema\n        url: json-schema/datahub-metadata-change-log-event-schema.json\n  - aid: datahub:datahub-rest-api\n    name: DataHub REST API\n    description: >-\n      The Rest.li API represents the underlying persistence layer and exposes the\n      raw PDL models used in storage.\
  \ It powers the GraphQL API under the hood\n      and is used for system-specific ingestion of metadata by the Metadata\n      Ingestion Framework. This API is considered system-internal and is not\n      recommended for direct external use.\n    image: https://datahubproject.io/img/datahub-logo.svg\n    humanURL: https://docs.datahub.com/docs/api/datahub-apis\n    baseURL: http://localhost:8080/\n    tags:\n      - Entities\n      - Internal\n      - Metadata\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.datahub.com/docs/api/datahub-apis\n  - aid: datahub:datahub-python-sdk\n    name: DataHub Python SDK\n    description: >-\n      Python client for interacting with DataHub. The acryl-datahub package\n      provides a CLI and SDK for DataHub, including REST and Kafka emitter APIs\n      for pushing metadata programmatically. It is one of the most recommended\n      tools for extending and customizing DataHub behavior, especially for\n      ingestion\
  \ and bulk metadata operations.\n    image: https://datahubproject.io/img/datahub-logo.svg\n    humanURL: https://docs.datahub.com/docs/metadata-ingestion/as-a-library\n    baseURL: https://pypi.org/project/acryl-datahub/\n    tags:\n      - Emitter\n      - Ingestion\n      - Python\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.datahub.com/docs/metadata-ingestion/as-a-library\n      - type: GitHubRepository\n        url: https://github.com/datahub-project/datahub\n      - type: SDKs\n        url: https://pypi.org/project/acryl-datahub/\n  - aid: datahub:datahub-java-sdk\n    name: DataHub Java SDK\n    description: >-\n      Java client for interacting with DataHub. The io.acryl datahub-client\n      package offers REST emitter APIs that can be used to emit metadata from\n      JVM-based systems. It supports all major DataHub entity types including\n      Dataset, Chart, Dashboard, Container, DataFlow, DataJob, MLModel, and\n      MLModelGroup.\n\
  \    image: https://datahubproject.io/img/datahub-logo.svg\n    humanURL: https://docs.datahub.com/docs/metadata-integration/java/as-a-library\n    baseURL: https://github.com/datahub-project/datahub\n    tags:\n      - Emitter\n      - Java\n      - Metadata\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.datahub.com/docs/metadata-integration/java/as-a-library\n      - type: GitHubRepository\n        url: https://github.com/datahub-project/datahub\n  - aid: datahub:datahub-cli\n    name: DataHub CLI\n    description: >-\n      Command line tool for interacting with DataHub. The datahub CLI allows you\n      to perform common operations including metadata ingestion, entity\n      management, and system administration from the command line. It is installed\n      as part of the acryl-datahub Python package and supports a plugin\n      architecture for different data source connectors.\n    image: https://datahubproject.io/img/datahub-logo.svg\n    humanURL:\
  \ https://docs.datahub.com/docs/cli\n    baseURL: https://pypi.org/project/acryl-datahub/\n    tags:\n      - CLI\n      - Command Line\n      - Ingestion\n      - Metadata\n    properties:\n      - type: Documentation\n        url: https://docs.datahub.com/docs/cli\n      - type: Getting Started\n        url: https://docs.datahub.com/docs/metadata-ingestion/cli-ingestion\n      - type: SDKs\n        url: https://pypi.org/project/acryl-datahub/\n  - aid: datahub:datahub-actions-framework\n    name: DataHub Actions Framework\n    description: >-\n      Event-driven framework for responding to real-time changes in the DataHub\n      metadata graph. The Actions Framework allows you to configure event sources,\n      transformations, and actions using YAML configuration files. It enables\n      seamless integration of DataHub into a broader event-based architecture by\n      consuming Metadata Change Logs and Platform Events.\n    image: https://datahubproject.io/img/datahub-logo.svg\n   \
  \ humanURL: https://docs.datahub.com/docs/actions\n    baseURL: https://pypi.org/project/acryl-datahub-actions/\n    tags:\n      - Actions\n      - Automation\n      - Events\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://docs.datahub.com/docs/actions\n      - type: Getting Started\n        url: https://docs.datahub.com/docs/actions/quickstart\n      - type: SDKs\n        url: https://pypi.org/project/acryl-datahub-actions/\n      - type: AsyncAPI\n        url: asyncapi/datahub-actions-asyncapi.yml\ncommon:\n  - type: Website\n    url: https://datahub.com\n  - type: Portal\n    url: https://docs.datahub.com\n  - type: Documentation\n    url: https://docs.datahub.com/docs/\n  - type: Getting Started\n    url: https://docs.datahub.com/docs/quickstart\n  - type: Authentication\n    url: https://docs.datahub.com/docs/authentication\n  - type: GitHubRepository\n    url: https://github.com/datahub-project/datahub\n  - type: Slack\n    url: https://slack.datahubproject.io\n\
  \  - type: Blog\n    url: https://datahub.com/blog/\n  - type: Demo\n    url: https://demo.datahubproject.io/\n  - type: Change Log\n    url: https://github.com/datahub-project/datahub/releases\n  - type: Status\n    url: https://status.datahub.com\n  - type: Community\n    url: https://forum.datahubproject.io/\n  - type: YouTube\n    url: https://youtube.com/@datahubproject\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/datahub-cloud\n  - type: Privacy Policy\n    url: https://datahub.com/privacy-policy/\n  - type: Security\n    url: https://docs.datahub.com/docs/security_stance\n  - type: JSON-LD\n    url: json-ld/datahub-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/datahub-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/datahub-capabilities.yml\n  - type: Rules\n    url: rules/datahub-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/datahub/refs/heads/main/apis.yml
tags:
- Data Catalog
- Data Discovery
- Data Governance
- Data Lineage
- Metadata
url: https://raw.githubusercontent.com/api-evangelist/datahub/refs/heads/main/apis.yml
use_cases: []
---
