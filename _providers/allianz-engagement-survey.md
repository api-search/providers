---
api_count: 1
api_specs:
- filename: allianz-engagement-survey.yaml
  format: yaml
  label: Allianz Engagement Survey API
  slug: engagement-survey-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/allianz-engagement-survey/refs/heads/main/openapi/allianz-engagement-survey.yaml
apis:
- description: REST API for managing the full lifecycle of employee engagement surveys at Allianz. Supports survey creation and configuration, participant management, response collection, results analysis, and repor
  name: Allianz Engagement Survey API
  slug: engagement-survey-api
capabilities:
- description: Workflow capability for HR teams running employee engagement surveys at Allianz, covering survey planning, participant management, results analysis, and action plan tracking.
  name: Allianz Employee Engagement Workflow
  slug: employee-engagement-workflow
common:
- title: ''
  type: Website
  url: https://www.allianz.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/allianz
- title: ''
  type: SpectralRules
  url: rules/allianz-engagement-survey-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/allianz-engagement-survey-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/employee-engagement-workflow.yaml
created: '2024-01-15'
description: The Allianz Engagement Survey API enables management of employee engagement surveys across the Allianz organization. It provides capabilities for survey lifecycle management, participant management, response collection, and analytics reporting to support Allianz's global employee experience initiatives.
features:
- description: Create, configure, publish, and close employee engagement surveys with full lifecycle tracking and audit capabilities.
  name: Survey Lifecycle Management
- description: Manage survey participants, send invitations, track response rates, and send reminders to boost participation across business units.
  name: Participant Management
- description: Collect structured survey responses with support for multiple question types including Likert scales, open text, and multiple choice.
  name: Response Collection
- description: Generate engagement analytics, participation metrics, and comparative reports across departments, regions, and time periods.
  name: Analytics and Reporting
- description: Segment survey results by business unit, geography, role, tenure, and demographic dimensions for targeted insights.
  name: Segmentation
- description: Track and manage action plans created in response to survey insights to drive employee experience improvements.
  name: Action Planning
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration with Workday HCM for automated participant roster management and organizational hierarchy synchronization.
  name: Workday
- description: Survey notifications and reminders delivered through Microsoft Teams to increase employee participation rates.
  name: Microsoft Teams
- description: Export engagement analytics to Power BI for advanced visualization and executive dashboard reporting.
  name: Power BI
jsonld:
- class_count: 16
  name: Allianz Engagement Survey Context
  property_count: 38
  slug: allianz-engagement-survey-context
layout: provider
modified: '2026-04-19'
name: Allianz Engagement Survey
rules:
- name: Allianz Engagement Survey API Rules
  rule_count: 24
  severity_counts:
    error: 15
    hint: 0
    info: 2
    warn: 7
  slug: allianz-engagement-survey-spectral-rules
skills: []
slug: allianz-engagement-survey
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: allianz-engagement-survey\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/allianz-engagement-survey/refs/heads/main/apis.yml\nname: Allianz Engagement Survey\ntags:\n  - Analytics\n  - Enterprise\n  - Human Resources\n  - Insurance\n  - Surveys\n  - Employee Experience\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  The Allianz Engagement Survey API enables management of employee engagement\n  surveys across the Allianz organization. It provides capabilities for survey\n  lifecycle management, participant management, response collection, and\n  analytics reporting to support Allianz's global employee experience\n  initiatives.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: allianz-engagement-survey:engagement-survey-api\n    name: Allianz Engagement Survey API\n    tags:\n      - Surveys\n      - Human Resources\n      - Employee Experience\n \
  \     - Analytics\n    properties:\n      - url: https://www.allianz.com/en/careers/working-at-allianz.html\n        type: Documentation\n      - url: openapi/allianz-engagement-survey.yaml\n        type: OpenAPI\n      - url: json-schema/engagement-survey-survey-schema.json\n        type: JSONSchema\n      - url: json-schema/engagement-survey-response-schema.json\n        type: JSONSchema\n      - url: json-schema/engagement-survey-analytics-schema.json\n        type: JSONSchema\n      - url: json-structure/engagement-survey-survey-structure.json\n        type: JSONStructure\n      - url: json-structure/engagement-survey-response-structure.json\n        type: JSONStructure\n      - url: json-ld/allianz-engagement-survey-context.jsonld\n        type: JSONLD\n      - url: examples/engagement-survey-survey-example.json\n        type: Example\n      - url: examples/engagement-survey-analytics-example.json\n        type: Example\n    description: >-\n      REST API for managing the full lifecycle\
  \ of employee engagement surveys at\n      Allianz. Supports survey creation and configuration, participant management,\n      response collection, results analysis, and reporting across business units\n      and geographies.\n    humanURL: https://www.allianz.com/en/careers/working-at-allianz.html\n    baseURL: https://api.allianz.com/engagement/v1\n\ncommon:\n  - url: https://www.allianz.com/\n    type: Website\n  - url: https://github.com/allianz\n    type: GitHubOrganization\n  - url: rules/allianz-engagement-survey-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/allianz-engagement-survey-vocabulary.yaml\n    type: Vocabulary\n  - url: capabilities/employee-engagement-workflow.yaml\n    type: NaftikoCapability\n  - type: Features\n    data:\n      - name: Survey Lifecycle Management\n        description: >-\n          Create, configure, publish, and close employee engagement surveys\n          with full lifecycle tracking and audit capabilities.\n      - name: Participant\
  \ Management\n        description: >-\n          Manage survey participants, send invitations, track response rates,\n          and send reminders to boost participation across business units.\n      - name: Response Collection\n        description: >-\n          Collect structured survey responses with support for multiple\n          question types including Likert scales, open text, and multiple choice.\n      - name: Analytics and Reporting\n        description: >-\n          Generate engagement analytics, participation metrics, and comparative\n          reports across departments, regions, and time periods.\n      - name: Segmentation\n        description: >-\n          Segment survey results by business unit, geography, role, tenure,\n          and demographic dimensions for targeted insights.\n      - name: Action Planning\n        description: >-\n          Track and manage action plans created in response to survey insights\n          to drive employee experience improvements.\n\
  \  - type: UseCases\n    data:\n      - name: Annual Engagement Survey\n        description: >-\n          Run company-wide annual employee engagement surveys to measure\n          satisfaction, commitment, and advocacy across all Allianz entities.\n      - name: Pulse Surveys\n        description: >-\n          Deploy frequent short pulse surveys to track engagement trends and\n          respond quickly to changing employee sentiment.\n      - name: Onboarding Surveys\n        description: >-\n          Capture new employee experience feedback during onboarding to\n          improve the joining experience and early retention.\n      - name: Exit Surveys\n        description: >-\n          Collect departing employee feedback to understand attrition drivers\n          and improve retention strategies.\n  - type: Integrations\n    data:\n      - name: Workday\n        description: >-\n          Integration with Workday HCM for automated participant roster\n          management and organizational\
  \ hierarchy synchronization.\n      - name: Microsoft Teams\n        description: >-\n          Survey notifications and reminders delivered through Microsoft Teams\n          to increase employee participation rates.\n      - name: Power BI\n        description: >-\n          Export engagement analytics to Power BI for advanced visualization\n          and executive dashboard reporting.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/allianz-engagement-survey/refs/heads/main/apis.yml
tags:
- Analytics
- Enterprise
- Human Resources
- Insurance
- Surveys
- Employee Experience
url: https://raw.githubusercontent.com/api-evangelist/allianz-engagement-survey/refs/heads/main/apis.yml
use_cases:
- description: Run company-wide annual employee engagement surveys to measure satisfaction, commitment, and advocacy across all Allianz entities.
  name: Annual Engagement Survey
- description: Deploy frequent short pulse surveys to track engagement trends and respond quickly to changing employee sentiment.
  name: Pulse Surveys
- description: Capture new employee experience feedback during onboarding to improve the joining experience and early retention.
  name: Onboarding Surveys
- description: Collect departing employee feedback to understand attrition drivers and improve retention strategies.
  name: Exit Surveys
---
