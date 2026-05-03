---
api_count: 1
api_specs:
- filename: shuffle-openapi.yml
  format: yaml
  label: Shuffle API
  slug: shuffle-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shuffle/refs/heads/main/openapi/shuffle-openapi.yml
apis:
- description: The Shuffle REST API provides programmatic access to all platform capabilities including workflow management, app integration, execution control, user and organization management, file storage, datast
  name: Shuffle API
  slug: shuffle-api
capabilities:
- description: 'Workflow capability for security operations automation using the Shuffle SOAR platform. Enables SOC analysts and security engineers to manage automation workflows, trigger security playbooks, monitor '
  name: Shuffle Security Workflow Automation
  slug: security-workflow-automation
common: []
created: '2026-05-02'
description: Shuffle is an open source security automation platform (SOAR) built for and by security professionals. The platform enables security teams to orchestrate workflows across their entire security tool stack using a no-code/low-code interface powered by OpenAPI integrations. Shuffle provides workflow automation, app integration, webhook triggers, scheduled executions, file storage, and organization management via a comprehensive REST API. It follows the Unix philosophy of doing one thing well — connecting security tools through REST APIs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 13
  name: Shuffle Context
  property_count: 18
  slug: shuffle-context
layout: provider
modified: '2026-05-02'
name: Shuffle
rules:
- name: Shuffle API Rules
  rule_count: 9
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 4
  slug: shuffle-rules
skills: []
slug: shuffle
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: shuffle\nname: Shuffle\ndescription: >-\n  Shuffle is an open source security automation platform (SOAR) built for and\n  by security professionals. The platform enables security teams to orchestrate\n  workflows across their entire security tool stack using a no-code/low-code\n  interface powered by OpenAPI integrations. Shuffle provides workflow automation,\n  app integration, webhook triggers, scheduled executions, file storage, and\n  organization management via a comprehensive REST API. It follows the Unix\n  philosophy of doing one thing well — connecting security tools through REST APIs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Security\n  - Workflows\n  - Automation\n  - SOAR\n  - Orchestration\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/shuffle/refs/heads/main/apis.yml\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ shuffle:shuffle-api\n    name: Shuffle API\n    description: >-\n      The Shuffle REST API provides programmatic access to all platform\n      capabilities including workflow management, app integration, execution\n      control, user and organization management, file storage, datastore\n      operations, and webhook triggers. Authentication uses a Bearer token from\n      the user's profile settings. The API is available for both the cloud\n      service at shuffler.io and self-hosted on-premises deployments.\n    humanURL: https://shuffler.io/docs/API\n    baseURL: https://shuffler.io/api/v1\n    tags:\n      - Security\n      - Workflows\n      - Automation\n      - SOAR\n      - Orchestration\n    properties:\n      - type: Documentation\n        url: https://shuffler.io/docs\n      - type: ApiReference\n        url: https://shuffler.io/docs/API\n      - type: GettingStarted\n        url: https://shuffler.io/docs/getting_started\n      - type: GitHubOrganization\n        url: https://github.com/Shuffle\n\
  \      - type: OpenSource\n        url: https://github.com/Shuffle/Shuffle\n      - type: Pricing\n        url: https://shuffler.io/pricing\n      - type: SignUp\n        url: https://shuffler.io\n      - type: Blog\n        url: https://medium.com/shuffle-automation\n      - type: Discord\n        url: https://discord.com/invite/B2CBzUm\n      - type: OpenAPI\n        url: openapi/shuffle-openapi.yml\n      - type: JSONSchema\n        url: json-schema/shuffle-workflow-schema.json\n      - type: JSONSchema\n        url: json-schema/shuffle-execution-schema.json\n      - type: JSONStructure\n        url: json-structure/shuffle-workflow-structure.json\n      - type: JSONLD\n        url: json-ld/shuffle-context.jsonld\n      - type: SpectralRules\n        url: rules/shuffle-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/security-workflow-automation.yaml\n      - type: Vocabulary\n        url: vocabulary/shuffle-vocabulary.yml\n    contact:\n      - FN: Shuffle Support\n\
  \        url: https://shuffler.io/docs\n        email: frikky@shuffler.io\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/shuffle/refs/heads/main/apis.yml
tags:
- Security
- Workflows
- Automation
- SOAR
- Orchestration
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/shuffle/refs/heads/main/apis.yml
use_cases: []
---
