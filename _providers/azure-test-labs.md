---
api_count: 1
apis:
- description: The DevTest Labs Client enables you to manage virtual machines, environments, artifacts, formulas, and custom images for development and testing purposes.
  name: Azure DevTest Labs API
  slug: azure-devtest-labs-api
capabilities:
- description: Workflow capability for managing Azure DevTest Labs resources. Used by cloud engineers and DevOps teams.
  name: Azure DevTest Labs Management
  slug: azure-test-labs-management
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://docs.microsoft.com/en-us/azure/devtest-labs/
- title: ''
  type: Getting Started
  url: https://azure.microsoft.com/en-us/get-started/
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/rules/azure-test-labs-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/vocabulary/azure-test-labs-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/json-ld/azure-test-labs-context.jsonld
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/capabilities/azure-test-labs-management.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/capabilities/shared/azure-test-labs.yaml
created: '2024-01-01'
description: Azure DevTest Labs enables developers to efficiently self-manage virtual machines and PaaS resources without waiting for approvals. DevTest Labs creates labs consisting of pre-configured bases or Azure Resource Manager templates for development and testing purposes.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 22
  name: Azure Test Labs Context
  property_count: 27
  slug: azure-test-labs-context
layout: provider
modified: '2026-04-19'
name: Azure DevTest Labs
rules:
- name: Azure DevTest Labs API Rules
  rule_count: 15
  severity_counts:
    error: 5
    hint: 0
    info: 4
    warn: 6
  slug: azure-test-labs-spectral-rules
skills: []
slug: azure-test-labs
solutions: []
source_filename: apis.yml
source_yaml: "aid: azure-test-labs\nname: Azure DevTest Labs\ndescription: >-\n  Azure DevTest Labs enables developers to efficiently self-manage virtual\n  machines and PaaS resources without waiting for approvals. DevTest Labs\n  creates labs consisting of pre-configured bases or Azure Resource Manager\n  templates for development and testing purposes.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Azure\n- Development\n- Infrastructure\n- Labs\n- Testing\n- Virtual Machines\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: azure-test-labs:azure-devtest-labs-api\n  name: Azure DevTest Labs API\n  description: >-\n    The DevTest Labs Client enables you to manage virtual machines,\n    environments, artifacts, formulas, and custom images for development\n    and testing purposes.\n  humanURL:\
  \ https://azure.microsoft.com/en-us/services/devtest-lab/\n  baseURL: https://management.azure.com\n  tags:\n  - Artifacts\n  - Environments\n  - Labs\n  - Virtual Machines\n  properties:\n  - type: Documentation\n    url: https://docs.microsoft.com/en-us/azure/devtest-labs/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/devtestlabs/resource-manager/Microsoft.DevTestLab/stable/2018-09-15/DevTestLabs.json\ncommon:\n- type: Portal\n  url: https://portal.azure.com\n- type: Documentation\n  url: https://docs.microsoft.com/en-us/azure/devtest-labs/\n- type: Getting Started\n  url: https://azure.microsoft.com/en-us/get-started/\n- type: Status\n  url: https://status.azure.com/\n- type: Blog\n  url: https://azure.microsoft.com/en-us/blog/\n- type: Support\n  url: https://azure.microsoft.com/en-us/support/\n- type: Terms of Service\n  url: https://azure.microsoft.com/en-us/support/legal/\n- type: Privacy Policy\n  url: https://privacy.microsoft.com/en-us/privacystatement\n\
  - type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/rules/azure-test-labs-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/vocabulary/azure-test-labs-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/json-ld/azure-test-labs-context.jsonld\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/capabilities/azure-test-labs-management.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/capabilities/shared/azure-test-labs.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/apis.yml
tags:
- Azure
- Development
- Infrastructure
- Labs
- Testing
- Virtual Machines
url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/apis.yml
use_cases: []
---
