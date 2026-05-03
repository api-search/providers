---
api_count: 1
api_specs:
- filename: spin-ai-openapi.yml
  format: yaml
  label: Spin.AI SpinOne API
  slug: spin-ai-spinone-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spin-ai/refs/heads/main/openapi/spin-ai-openapi.yml
apis:
- description: 'The SpinOne Public API provides programmatic access to SaaS data protection management. It enables reading, filtering, and updating the backup status of entities (users, groups, shared drives) across '
  name: Spin.AI SpinOne API
  slug: spin-ai-spinone-api
capabilities:
- description: Workflow capability for managing SaaS data protection and backup entity lifecycle using the Spin.AI SpinOne platform. Enables IT administrators and security teams to audit backup coverage, identify un
  name: Spin.AI SaaS Data Protection
  slug: saas-data-protection
common:
- title: ''
  type: Website
  url: https://www.spin.ai
- title: ''
  type: Documentation
  url: https://spin.ai/help/
- title: ''
  type: Portal
  url: https://spin.ai/help/gworkspace-administration/setting-up-public-api
- title: ''
  type: Support
  url: https://spin.ai/support/
- title: ''
  type: TermsOfService
  url: https://spin.ai/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://spin.ai/privacy-policy/
- title: ''
  type: Blog
  url: https://spin.ai/blog/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/spin-ai/
- title: ''
  type: OpenAPI
  url: openapi/spin-ai-openapi.yml
- title: ''
  type: SpectralRules
  url: rules/spin-ai-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/spin-ai-vocabulary.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/saas-data-protection.yaml
created: '2026-03-27'
description: Spin.AI is a SaaS security platform providing data protection, ransomware detection, and compliance management for cloud applications including Google Workspace, Microsoft 365, Salesforce, and Slack. The SpinOne Public API enables programmatic integration for managing backup entity lifecycle across enterprise SaaS environments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Spin Ai Context
  property_count: 10
  slug: spin-ai-context
layout: provider
modified: '2026-05-02'
name: Spin.AI
rules:
- name: Spin.AI API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: spin-ai-rules
skills: []
slug: spin-ai
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spin-ai\nname: Spin.AI\ndescription: >-\n  Spin.AI is a SaaS security platform providing data protection, ransomware detection,\n  and compliance management for cloud applications including Google Workspace, Microsoft 365,\n  Salesforce, and Slack. The SpinOne Public API enables programmatic integration for managing\n  backup entity lifecycle across enterprise SaaS environments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Backup\n  - Compliance\n  - Data Protection\n  - Ransomware\n  - SaaS Security\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/spin-ai/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: spin-ai:spin-ai-spinone-api\n    name: Spin.AI SpinOne API\n    description: >-\n      The SpinOne Public API provides programmatic access to SaaS data protection\n      management. It enables reading, filtering, and updating the\
  \ backup status of\n      entities (users, groups, shared drives) across Google Workspace, Microsoft 365,\n      Salesforce, and Slack. Authentication uses a custom SPIN_API key scheme combining\n      an App ID and API Key from the SpinOne admin console.\n    humanURL: https://spin.ai/help/gworkspace-administration/setting-up-public-api\n    tags:\n      - Backup\n      - Data Protection\n      - Entities\n      - Google Workspace\n      - Microsoft 365\n      - SaaS Security\n    properties:\n      - type: Documentation\n        url: https://spin.ai/help/gworkspace-administration/setting-up-public-api\n      - type: SwaggerUI\n        url: https://apg-1.spin.ai/swagger-ui/\n      - type: OpenAPI\n        url: openapi/spin-ai-openapi.yml\n      - type: SpectralRules\n        url: rules/spin-ai-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/saas-data-protection.yaml\ncommon:\n  - type: Website\n    url: https://www.spin.ai\n  - type: Documentation\n    url: https://spin.ai/help/\n\
  \  - type: Portal\n    url: https://spin.ai/help/gworkspace-administration/setting-up-public-api\n  - type: Integrations\n    url: https://spin.ai/integrations/\n  - type: Support\n    url: https://spin.ai/support/\n  - type: TermsOfService\n    url: https://spin.ai/terms-of-service/\n  - type: PrivacyPolicy\n    url: https://spin.ai/privacy-policy/\n  - type: Blog\n    url: https://spin.ai/blog/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/spin-ai/\n  - type: OpenAPI\n    url: openapi/spin-ai-openapi.yml\n  - type: SpectralRules\n    url: rules/spin-ai-rules.yml\n  - type: Vocabulary\n    url: vocabulary/spin-ai-vocabulary.yml\n  - type: NaftikoCapabilities\n    url: capabilities/saas-data-protection.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spin-ai/refs/heads/main/apis.yml
tags:
- Backup
- Compliance
- Data Protection
- Ransomware
- SaaS Security
url: https://raw.githubusercontent.com/api-evangelist/spin-ai/refs/heads/main/apis.yml
use_cases: []
---
