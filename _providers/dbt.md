---
api_count: 3
api_specs:
- filename: dbt-cloud-administrative-api-openapi.yml
  format: yaml
  label: dbt Cloud Administrative API
  slug: dbt-cloud-administrative-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/openapi/dbt-cloud-administrative-api-openapi.yml
- filename: dbt-cloud-discovery-api-openapi.yml
  format: yaml
  label: dbt Cloud Discovery API
  slug: dbt-cloud-discovery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/openapi/dbt-cloud-discovery-api-openapi.yml
- filename: dbt-cloud-semantic-layer-api-openapi.yml
  format: yaml
  label: dbt Cloud Semantic Layer API
  slug: dbt-cloud-semantic-layer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/openapi/dbt-cloud-semantic-layer-api-openapi.yml
apis:
- description: The dbt Cloud Administrative API manages accounts, projects, jobs, runs, environments, and other resources. It is the primary integration point for external orchestrators (Airflow, Dagster, Prefect) a
  name: dbt Cloud Administrative API
  slug: dbt-cloud-administrative-api
- description: Every time dbt Cloud runs a project, it generates and stores information about the project. The Discovery API exposes that metadata including details about models, sources, exposures, and execution re
  name: dbt Cloud Discovery API
  slug: dbt-cloud-discovery-api
- description: The dbt Semantic Layer lets teams define metrics in code with MetricFlow and query them consistently from BI tools, notebooks, and applications. The Semantic Layer API exposes metric and dimension que
  name: dbt Cloud Semantic Layer API
  slug: dbt-cloud-semantic-layer-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.getdbt.com/
- title: ''
  type: Documentation
  url: https://docs.getdbt.com/
- title: ''
  type: Portal
  url: https://docs.getdbt.com/docs/dbt-cloud-apis/overview
- title: ''
  type: Authentication
  url: https://docs.getdbt.com/docs/dbt-cloud-apis/authentication
- title: ''
  type: Pricing
  url: https://www.getdbt.com/pricing
- title: ''
  type: GitHub
  url: https://github.com/dbt-labs/dbt-core
- title: ''
  type: SDK
  url: https://docs.getdbt.com/docs/dbt-cloud-apis/sl-python
- title: ''
  type: Terms of Service
  url: https://www.getdbt.com/cloud/terms
- title: ''
  type: Privacy Policy
  url: https://www.getdbt.com/cloud/privacy-policy
- title: ''
  type: JSON-LD
  url: json-ld/dbt-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/dbt-vocabulary.yml
created: '2025-01-08'
description: dbt Labs operates dbt Cloud, the managed platform for the open-source dbt (data build tool) used to transform data inside cloud warehouses. dbt Cloud exposes a set of APIs for managing accounts, projects, jobs, and runs programmatically (Administrative API), inspecting project metadata (Discovery API), and querying governed metrics (Semantic Layer API).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Dbt Context
  property_count: 10
  slug: dbt-context
layout: provider
modified: '2026-04-28'
name: dbt
rules:
- name: dbt API Rules
  rule_count: 5
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 4
  slug: dbt-cloud-administrative-api-rules
skills: []
slug: dbt
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dbt\nname: dbt\nurl: https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/apis.yml\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics Engineering\n  - Data\n  - ELT\n  - Metrics\n  - Projects\n  - SQL\n  - Transformation\ncreated: '2025-01-08'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: company\ndescription: >-\n  dbt Labs operates dbt Cloud, the managed platform for the open-source dbt\n  (data build tool) used to transform data inside cloud warehouses. dbt Cloud\n  exposes a set of APIs for managing accounts, projects, jobs, and runs\n  programmatically (Administrative API), inspecting project metadata\n  (Discovery API), and querying governed metrics (Semantic Layer API).\napis:\n  - aid: dbt:dbt-cloud-administrative-api\n    name: dbt Cloud Administrative API\n    description: >-\n      The dbt Cloud Administrative API manages\
  \ accounts, projects, jobs,\n      runs, environments, and other resources. It is the primary integration\n      point for external orchestrators (Airflow, Dagster, Prefect) and for\n      Terraform-based management of dbt Cloud configuration.\n    humanURL: https://docs.getdbt.com/docs/dbt-cloud-apis/admin-cloud-api\n    baseURL: https://cloud.getdbt.com/api/v3\n    tags:\n      - Accounts\n      - Administration\n      - Jobs\n      - Projects\n      - Runs\n    properties:\n      - type: Documentation\n        url: https://docs.getdbt.com/docs/dbt-cloud-apis/admin-cloud-api\n      - type: OpenAPI\n        url: openapi/dbt-cloud-administrative-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/dbt-job.json\n      - type: JSONSchema\n        url: json-schema/dbt-run.json\n      - type: Rules\n        url: rules/dbt-cloud-administrative-api-rules.yml\n      - type: Capabilities\n        url: capabilities/dbt-cloud-administrative-api-capabilities.yml\n  - aid: dbt:dbt-cloud-discovery-api\n\
  \    name: dbt Cloud Discovery API\n    description: >-\n      Every time dbt Cloud runs a project, it generates and stores\n      information about the project. The Discovery API exposes that metadata\n      including details about models, sources, exposures, and execution\n      results so teams can understand and govern their DAG.\n    humanURL: https://docs.getdbt.com/docs/dbt-cloud-apis/discovery-api\n    baseURL: https://metadata.cloud.getdbt.com/graphql\n    tags:\n      - Discovery\n      - GraphQL\n      - Lineage\n      - Metadata\n    properties:\n      - type: Documentation\n        url: https://docs.getdbt.com/docs/dbt-cloud-apis/discovery-api\n      - type: OpenAPI\n        url: openapi/dbt-cloud-discovery-api-openapi.yml\n  - aid: dbt:dbt-cloud-semantic-layer-api\n    name: dbt Cloud Semantic Layer API\n    description: >-\n      The dbt Semantic Layer lets teams define metrics in code with\n      MetricFlow and query them consistently from BI tools, notebooks, and\n   \
  \   applications. The Semantic Layer API exposes metric and dimension\n      queries via GraphQL, JDBC, and a Python SDK.\n    humanURL: https://docs.getdbt.com/docs/dbt-cloud-apis/sl-api-overview\n    baseURL: https://semantic-layer.cloud.getdbt.com/api/graphql\n    tags:\n      - Dimensions\n      - GraphQL\n      - JDBC\n      - MetricFlow\n      - Metrics\n      - Semantic Layer\n    properties:\n      - type: Documentation\n        url: https://docs.getdbt.com/docs/dbt-cloud-apis/sl-api-overview\n      - type: OpenAPI\n        url: openapi/dbt-cloud-semantic-layer-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.getdbt.com/\n  - type: Documentation\n    url: https://docs.getdbt.com/\n  - type: Portal\n    url: https://docs.getdbt.com/docs/dbt-cloud-apis/overview\n  - type: Authentication\n    url: https://docs.getdbt.com/docs/dbt-cloud-apis/authentication\n  - type: Pricing\n    url: https://www.getdbt.com/pricing\n  - type: GitHub\n    url: https://github.com/dbt-labs/dbt-core\n\
  \  - type: SDK\n    url: https://docs.getdbt.com/docs/dbt-cloud-apis/sl-python\n  - type: Terms of Service\n    url: https://www.getdbt.com/cloud/terms\n  - type: Privacy Policy\n    url: https://www.getdbt.com/cloud/privacy-policy\n  - type: JSON-LD\n    url: json-ld/dbt-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/dbt-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/apis.yml
tags:
- Analytics Engineering
- Data
- ELT
- Metrics
- Projects
- SQL
- Transformation
url: https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/apis.yml
use_cases: []
---
