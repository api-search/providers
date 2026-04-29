---
api_count: 1
api_specs:
- filename: google-forms-api.yaml
  format: yaml
  label: Google Forms API v1
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-forms/refs/heads/main/openapi/google-forms-api.yaml
apis:
- description: Create and modify Google Forms, read form responses and structure, set up watches for change notifications, and integrate forms with external applications via Cloud Pub/Sub.
  name: Google Forms API v1
  slug: ''
capabilities:
- description: Workflow capability for managing Google Forms - creating forms, collecting responses, and monitoring changes via watches. Used by form administrators and data analysts.
  name: Google Forms Form Management
  slug: form-management
common:
- title: ''
  type: Console
  url: https://console.cloud.google.com/apis/library/forms.googleapis.com
- title: ''
  type: GettingStarted
  url: https://developers.google.com/forms/api/guides
- title: ''
  type: Authentication
  url: https://developers.google.com/identity/protocols/oauth2
- title: ''
  type: StatusPage
  url: https://status.cloud.google.com/
- title: ''
  type: PrivacyPolicy
  url: https://policies.google.com/privacy
- title: ''
  type: TermsOfService
  url: https://policies.google.com/terms
- title: ''
  type: RateLimits
  url: https://developers.google.com/forms/api/guides/quota
- title: ''
  type: Support
  url: https://developers.google.com/forms/api/support
- title: ''
  type: JSON-LD
  url: json-ld/google-forms-api-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/google-forms-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/form-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/google-forms-vocabulary.yaml
created: '2024-01-15'
description: The Google Forms API is a RESTful interface that lets you create and modify Google Forms programmatically, read form responses, set up watches for notifications on form changes and new responses, and integrate forms with external applications.
features:
- description: Programmatically create Google Forms with custom titles and descriptions.
  name: Form Creation
- description: Apply multiple changes to a form in a single API call.
  name: Batch Updates
- description: Read and analyze form responses programmatically.
  name: Response Collection
- description: Receive real-time notifications via Cloud Pub/Sub when forms change or responses are submitted.
  name: Watch Notifications
- description: Create and grade quiz forms with correct answers and scoring.
  name: Quiz Support
- description: Control whether forms are published and accepting responses.
  name: Publish Settings
- description: Support for file upload question types.
  name: File Upload Questions
- description: Support for rating-style questions with customizable icons.
  name: Rating Questions
image: https://www.gstatic.com/images/branding/product/2x/forms_2020q4_48dp.png
integrations:
- description: Automatically link form responses to Google Sheets for analysis.
  name: Google Sheets
- description: Receive real-time notifications about form events via Pub/Sub topics.
  name: Google Cloud Pub/Sub
- description: Store file upload responses in Google Drive.
  name: Google Drive
- description: Integrate with other Google Workspace apps for collaboration.
  name: Google Workspace
jsonld:
- class_count: 5
  name: Google Forms Api Context
  property_count: 17
  slug: google-forms-api-context
layout: provider
modified: '2026-04-18'
name: Google Forms
rules:
- name: Google Forms API Rules
  rule_count: 27
  severity_counts:
    error: 16
    hint: 0
    info: 1
    warn: 10
  slug: google-forms-spectral-rules
skills: []
slug: google-forms
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-forms\nname: Google Forms\ndescription: >-\n  The Google Forms API is a RESTful interface that lets you create and modify\n  Google Forms programmatically, read form responses, set up watches for\n  notifications on form changes and new responses, and integrate forms with\n  external applications.\nurl: https://developers.google.com/forms/api\ntype: Index\nimage: https://www.gstatic.com/images/branding/product/2x/forms_2020q4_48dp.png\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Data Collection\n  - Forms\n  - Google\n  - Google Workspace\n  - Questionnaires\n  - Responses\n  - Surveys\napis:\n  - name: Google Forms API v1\n    description: >-\n      Create and modify Google Forms, read form responses and structure, set up\n      watches for change notifications, and integrate forms with external\n      applications via Cloud Pub/Sub.\n    image: https://www.gstatic.com/images/branding/product/2x/forms_2020q4_48dp.png\n\
  \    humanURL: https://developers.google.com/forms/api\n    baseURL: https://forms.googleapis.com/v1\n    tags:\n      - Forms\n      - Google\n      - Questionnaires\n      - Responses\n      - Surveys\n      - Watches\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/forms/api/reference/rest\n      - type: OpenAPI\n        url: openapi/google-forms-api.yaml\n      - type: JSONSchema\n        url: json-schema/google-forms-api-form-schema.json\n      - type: JSONSchema\n        url: json-schema/google-forms-api-form-response-schema.json\n      - type: JSONSchema\n        url: json-schema/google-forms-api-watch-schema.json\n      - type: JSONSchema\n        url: json-schema/google-forms-api-question-schema.json\n      - type: JSONStructure\n        url: json-structure/google-forms-api-form-structure.json\n      - type: JSONStructure\n        url: json-structure/google-forms-api-form-response-structure.json\n      - type: JSONStructure\n        url:\
  \ json-structure/google-forms-api-watch-structure.json\n      - type: JSONStructure\n        url: json-structure/google-forms-api-question-structure.json\n      - type: Example\n        url: examples/google-forms-api-form-example.json\n      - type: Example\n        url: examples/google-forms-api-form-response-example.json\n      - type: Example\n        url: examples/google-forms-api-watch-example.json\n      - type: Example\n        url: examples/google-forms-api-question-example.json\n      - type: APIReference\n        url: https://developers.google.com/forms/api/reference/rest\n      - type: Quickstart\n        url: https://developers.google.com/forms/api/quickstart/python\n      - type: Authentication\n        url: https://developers.google.com/forms/api/guides/auth\n    contact:\n      - type: Support\n        url: https://support.google.com/docs/answer/6281888\ncommon:\n  - type: Console\n    url: https://console.cloud.google.com/apis/library/forms.googleapis.com\n  - type: GettingStarted\n\
  \    url: https://developers.google.com/forms/api/guides\n  - type: Authentication\n    url: https://developers.google.com/identity/protocols/oauth2\n  - type: StatusPage\n    url: https://status.cloud.google.com/\n  - type: PrivacyPolicy\n    url: https://policies.google.com/privacy\n  - type: TermsOfService\n    url: https://policies.google.com/terms\n  - type: RateLimits\n    url: https://developers.google.com/forms/api/guides/quota\n  - type: Support\n    url: https://developers.google.com/forms/api/support\n  - type: JSON-LD\n    url: json-ld/google-forms-api-context.jsonld\n  - type: SpectralRules\n    url: rules/google-forms-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/form-management.yaml\n  - type: Vocabulary\n    url: vocabulary/google-forms-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Form Creation\n        description: Programmatically create Google Forms with custom titles and descriptions.\n      - name: Batch Updates\n        description:\
  \ Apply multiple changes to a form in a single API call.\n      - name: Response Collection\n        description: Read and analyze form responses programmatically.\n      - name: Watch Notifications\n        description: Receive real-time notifications via Cloud Pub/Sub when forms change or responses are submitted.\n      - name: Quiz Support\n        description: Create and grade quiz forms with correct answers and scoring.\n      - name: Publish Settings\n        description: Control whether forms are published and accepting responses.\n      - name: File Upload Questions\n        description: Support for file upload question types.\n      - name: Rating Questions\n        description: Support for rating-style questions with customizable icons.\n  - type: UseCases\n    data:\n      - name: Automated Survey Distribution\n        description: Create and distribute surveys programmatically as part of CRM or marketing workflows.\n      - name: Response Analytics\n        description: Automatically\
  \ collect and analyze form responses for reporting dashboards.\n      - name: Event-Driven Processing\n        description: Trigger downstream workflows when new responses are submitted using watches.\n      - name: Quiz and Assessment Automation\n        description: Build automated grading systems for educational quizzes.\n      - name: Data Collection Pipelines\n        description: Integrate forms into data collection pipelines for research or operations.\n  - type: Integrations\n    data:\n      - name: Google Sheets\n        description: Automatically link form responses to Google Sheets for analysis.\n      - name: Google Cloud Pub/Sub\n        description: Receive real-time notifications about form events via Pub/Sub topics.\n      - name: Google Drive\n        description: Store file upload responses in Google Drive.\n      - name: Google Workspace\n        description: Integrate with other Google Workspace apps for collaboration.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-forms/refs/heads/main/apis.yml
tags:
- Data Collection
- Forms
- Google
- Google Workspace
- Questionnaires
- Responses
- Surveys
url: https://developers.google.com/forms/api
use_cases:
- description: Create and distribute surveys programmatically as part of CRM or marketing workflows.
  name: Automated Survey Distribution
- description: Automatically collect and analyze form responses for reporting dashboards.
  name: Response Analytics
- description: Trigger downstream workflows when new responses are submitted using watches.
  name: Event-Driven Processing
- description: Build automated grading systems for educational quizzes.
  name: Quiz and Assessment Automation
- description: Integrate forms into data collection pipelines for research or operations.
  name: Data Collection Pipelines
---
