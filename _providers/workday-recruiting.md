---
api_count: 2
api_specs:
- filename: Recruiting_OpenAPI.yaml
  format: yaml
  label: Workday Recruiting REST API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v41.2/Recruiting_OpenAPI.yaml
apis:
- description: 'RESTful API for managing recruiting operations including job requisitions, candidates, applications, and hiring processes in Workday. Supports OAuth 2.0 authentication and returns data in JSON format '
  name: Workday Recruiting REST API
  slug: ''
- description: SOAP-based web service providing comprehensive access to Workday Recruiting business services data for integration with talent management and applicant tracking systems. Includes over 120 operations c
  name: Workday Recruiting SOAP Web Services API
  slug: ''
capabilities:
- description: Recruiter and sourcer workflow for managing the candidate pipeline from sourcing through application progression. Covers candidate profile and attachment management, candidate assessments and referral
  name: Workday Recruiting Candidate Pipeline
  slug: candidate-pipeline
- description: Recruiter and hiring manager workflow for scheduling interviews, collecting and reviewing interviewer feedback, and running pre-hire background screening. Combines the Workday Recruiting interview and
  name: Workday Recruiting Interview and Screening
  slug: interview-and-screening
- description: Recruiting administrator workflow for retrieving recruiting configuration and reference data — job posting sites, screening questionnaires, and veteran status reference values used for EEO and OFCCP c
  name: Workday Recruiting Configuration
  slug: recruiting-configuration
- description: Hiring manager and recruiter workflow for opening, modifying, freezing, and closing job requisitions and evergreen requisitions, creating positions in the position management staffing model, and posti
  name: Workday Recruiting Requisition Management
  slug: requisition-management
common:
- title: ''
  type: Portal
  url: https://community.workday.com
- title: ''
  type: GettingStarted
  url: https://community.workday.com/api-start
- title: ''
  type: Documentation
  url: https://community.workday.com/api
- title: ''
  type: Authentication
  url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication
- title: ''
  type: Console
  url: https://developer.workday.com/about
- title: ''
  type: Blog
  url: https://blog.workday.com/en-us/application-development.html
- title: ''
  type: StatusPage
  url: https://community.workday.com/trust/status
- title: ''
  type: Support
  url: https://www.workday.com/en-us/services/support.html
- title: ''
  type: SignUp
  url: https://resourcecenter.workday.com/
- title: ''
  type: TermsOfService
  url: https://www.workday.com/en-us/legal.html
- title: ''
  type: PrivacyPolicy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: RateLimits
  url: https://community.workday.com/articles/16827
- title: ''
  type: ChangeLog
  url: https://community.workday.com/api-versions
- title: ''
  type: GitHubOrganization
  url: https://github.com/Workday
- title: Workday Everywhere SDK
  type: Tools
  url: https://www.npmjs.com/package/@workday/everywhere
- title: Workday Canvas Kit
  type: Tools
  url: https://github.com/Workday/canvas-kit
- title: Workday Extend JavaScript Example
  type: CodeExamples
  url: https://github.com/Workday/extend-js-example
- title: ''
  type: Marketplace
  url: https://marketplace.workday.com/en-US/home
- title: ''
  type: Partners
  url: https://www.workday.com/en-us/company/partners/overview.html
- title: ''
  type: SpectralRules
  url: rules/workday-recruiting-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/requisition-management.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/candidate-pipeline.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/interview-and-screening.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/recruiting-configuration.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/recruiting.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/workday-recruiting-vocabulary.yaml
created: '2024-01-01'
description: APIs for Workday's cloud-based recruiting and talent acquisition solution, providing programmatic access to job requisitions, candidate management, applications, interviews, job postings, and hiring workflows.
features:
- description: Create, edit, close, freeze, and reopen job requisitions for open positions, with full lifecycle and approval workflow support.
  name: Job Requisition Management
- description: Manage ongoing requisitions used for continuous hiring needs without a specific number of openings or close date.
  name: Evergreen Requisitions
- description: Create, retrieve, and update candidate profiles including personal information, attachments, photos, and assessment data.
  name: Candidate Management
- description: Manage applications from submission through disposition, including stage movement, advancement, and offer initiation.
  name: Job Application Lifecycle
- description: Post, update, and unpost jobs to internal and external career sites and manage job posting site brands and configurations.
  name: Job Posting Distribution
- description: Schedule interviews, submit interview feedback, configure interview settings, and manage self-schedule calendars.
  name: Interview Scheduling
- description: Submit and retrieve background check results and manage background check packages for candidate screening.
  name: Background Check Integration
- description: Manage agency relationships, agency users, and agency candidate submissions tied to job requisitions.
  name: Recruiting Agency Workflows
- description: Bulk applicant import operations to support high-volume hiring and third-party sourcing pipelines.
  name: High-Volume Applicant Import
- description: Create and manage positions and position restrictions within the position management staffing model.
  name: Position Management
- description: Manage recruiting configuration including questionnaires, assessment categories, veteran statuses, site brands, and regions.
  name: Recruiting Configuration
- description: Standards-based OAuth 2.0 authentication for secure programmatic access to recruiting data.
  name: OAuth 2.0 Authentication
- description: Comprehensive SOAP web services with over 120 recruiting operations for deep enterprise integration.
  name: SOAP Web Services
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integration with Workday Human Capital Management for seamless transition from candidate to employee.
  name: Workday HCM
- description: Connect with LinkedIn Recruiter and LinkedIn Job Postings for sourcing and posting workflows.
  name: LinkedIn Talent Solutions
- description: Distribute Workday job postings to Indeed and ingest applications back into Workday.
  name: Indeed
- description: Background check integration for criminal, employment, and education verification.
  name: HireRight
- description: Background screening, drug testing, and identity verification integration.
  name: Sterling
- description: Technical assessment integration for engineering and developer hiring pipelines.
  name: HackerRank
- description: Self-schedule interview integration for candidate-driven scheduling.
  name: Calendly
- description: Calendar and meeting integration for interview scheduling and coordination.
  name: Microsoft Outlook and Teams
- description: Calendar and meeting integration for interview scheduling.
  name: Google Workspace
- description: E-signature integration for offer letter and onboarding document workflows.
  name: DocuSign
- description: Pre-built integrations with talent acquisition vendors listed in the Workday Marketplace.
  name: Workday Marketplace Partners
jsonld:
- class_count: 31
  name: Workday Recruiting Rest Api Context
  property_count: 99
  slug: workday-recruiting-rest-api-context
layout: provider
modified: '2026-05-03'
name: Workday Recruiting
rules:
- name: Workday Recruiting API Rules
  rule_count: 67
  severity_counts:
    error: 25
    hint: 0
    info: 6
    warn: 36
  slug: workday-recruiting-spectral-rules
skills: []
slug: workday-recruiting
solutions:
- description: End-to-end recruiting solution from sourcing through hire, unifying recruiting with the broader Workday HCM platform.
  name: Workday Talent Acquisition
- description: AI-driven candidate matching, screening, and recruiter productivity embedded in Workday Recruiting.
  name: HiredScore AI for Recruiting
- description: Native onboarding handoff that converts hires into engaged employees inside the Workday HCM system of record.
  name: Workday Onboarding
- description: Skills-driven hiring leveraging the Workday skills ontology across requisitions and candidate profiles.
  name: Workday Skills Cloud
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: workday-recruiting\nname: Workday Recruiting\ndescription: >-\n  APIs for Workday's cloud-based recruiting and talent acquisition solution,\n  providing programmatic access to job requisitions, candidate management,\n  applications, interviews, job postings, and hiring workflows.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday-recruiting/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - HCM\n  - Human Resources\n  - Recruiting\n  - SaaS\n  - Talent Acquisition\napis:\n  - name: Workday Recruiting REST API\n    description: >-\n      RESTful API for managing recruiting operations including job requisitions,\n      candidates, applications, and hiring processes in Workday. Supports OAuth\n      2.0 authentication and returns data in JSON format for integration with\n      talent management and applicant tracking\
  \ systems.\n    image: https://www.workday.com/content/dam/web/images/logos/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/recruiting/\n    tags:\n      - Applications\n      - Candidates\n      - Job Requisitions\n      - Recruiting\n      - Talent Acquisition\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v41.2/Recruiting_OpenAPI.yaml\n      - type: OpenAPI\n        url: openapi/workday-recruiting-rest-api-openapi.yml\n      - type: Authentication\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication\n      - type: RateLimits\n        url: https://community.workday.com/articles/16827\n\
  \      - type: JSON-LD\n        url: json-ld/workday-recruiting-rest-api-context.jsonld\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-applicant-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-applicant-import-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-attachment-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-background-check-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-background-check-create-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-background-check-package-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-candidate-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-candidate-create-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-candidate-assessment-schema.json\n  \
  \    - type: JSONSchema\n        url: json-schema/recruiting-rest-api-evergreen-requisition-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-evergreen-requisition-create-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-interview-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-interview-create-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-interview-feedback-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-interview-feedback-create-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-job-application-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-job-posting-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-job-posting-site-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-job-requisition-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-job-requisition-create-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-offer-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-offer-create-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-position-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-position-create-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-questionnaire-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-recruiting-agency-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-reference-schema.json\n      - type: JSONSchema\n        url: json-schema/recruiting-rest-api-veteran-status-schema.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-applicant-structure.json\n      - type: JSONStructure\n\
  \        url: json-structure/recruiting-rest-api-applicant-import-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-attachment-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-background-check-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-background-check-create-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-background-check-package-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-candidate-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-candidate-create-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-candidate-assessment-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-evergreen-requisition-structure.json\n      - type: JSONStructure\n\
  \        url: json-structure/recruiting-rest-api-evergreen-requisition-create-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-interview-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-interview-create-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-interview-feedback-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-interview-feedback-create-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-job-application-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-job-posting-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-job-posting-site-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-job-requisition-structure.json\n      - type: JSONStructure\n\
  \        url: json-structure/recruiting-rest-api-job-requisition-create-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-offer-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-offer-create-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-position-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-position-create-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-questionnaire-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-recruiting-agency-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-reference-structure.json\n      - type: JSONStructure\n        url: json-structure/recruiting-rest-api-veteran-status-structure.json\n      - type: Example\n        url: examples/recruiting-rest-api-applicant-example.json\n\
  \      - type: Example\n        url: examples/recruiting-rest-api-applicant-import-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-attachment-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-background-check-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-background-check-create-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-background-check-package-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-candidate-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-candidate-create-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-candidate-assessment-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-evergreen-requisition-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-evergreen-requisition-create-example.json\n      - type: Example\n\
  \        url: examples/recruiting-rest-api-interview-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-interview-create-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-interview-feedback-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-interview-feedback-create-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-job-application-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-job-posting-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-job-posting-site-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-job-requisition-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-job-requisition-create-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-offer-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-offer-create-example.json\n\
  \      - type: Example\n        url: examples/recruiting-rest-api-position-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-position-create-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-questionnaire-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-recruiting-agency-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-reference-example.json\n      - type: Example\n        url: examples/recruiting-rest-api-veteran-status-example.json\n  - name: Workday Recruiting SOAP Web Services API\n    description: >-\n      SOAP-based web service providing comprehensive access to Workday Recruiting\n      business services data for integration with talent management and applicant\n      tracking systems. Includes over 120 operations covering candidate\n      management, job requisitions, evergreen requisitions, job postings,\n      interviews, background checks, recruiting agencies,\
  \ and self-schedule\n      calendars.\n    image: https://www.workday.com/content/dam/web/images/logos/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service/\n    tags:\n      - Candidates\n      - Job Requisitions\n      - Recruiting\n      - SOAP API\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.html\n      - type: APIReference\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n      - type: WSDL\n        url: wsdl/workday-recruiting-soap.wsdl\n      - type: WSDL\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.wsdl\n      - type: XSD\n        url: xsd/workday-recruiting-soap.xsd\n\
  \      - type: XSD\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.xsd\n      - type: ChangeLog\n        url: https://community.workday.com/api-versions\ncommon:\n  - type: Portal\n    url: https://community.workday.com\n  - type: GettingStarted\n    url: https://community.workday.com/api-start\n  - type: Documentation\n    url: https://community.workday.com/api\n  - type: Authentication\n    url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication\n  - type: Console\n    url: https://developer.workday.com/about\n  - type: Blog\n    url: https://blog.workday.com/en-us/application-development.html\n  - type: StatusPage\n    url: https://community.workday.com/trust/status\n  - type: Support\n    url: https://www.workday.com/en-us/services/support.html\n  - type: SignUp\n    url: https://resourcecenter.workday.com/\n  - type: TermsOfService\n    url: https://www.workday.com/en-us/legal.html\n\
  \  - type: PrivacyPolicy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: RateLimits\n    url: https://community.workday.com/articles/16827\n  - type: ChangeLog\n    url: https://community.workday.com/api-versions\n  - type: GitHubOrganization\n    url: https://github.com/Workday\n  - type: Tools\n    url: https://www.npmjs.com/package/@workday/everywhere\n    title: Workday Everywhere SDK\n  - type: Tools\n    url: https://github.com/Workday/canvas-kit\n    title: Workday Canvas Kit\n  - type: CodeExamples\n    url: https://github.com/Workday/extend-js-example\n    title: Workday Extend JavaScript Example\n  - type: Marketplace\n    url: https://marketplace.workday.com/en-US/home\n  - type: Partners\n    url: https://www.workday.com/en-us/company/partners/overview.html\n  - type: SpectralRules\n    url: rules/workday-recruiting-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/requisition-management.yaml\n  - type: NaftikoCapability\n    url: capabilities/candidate-pipeline.yaml\n\
  \  - type: NaftikoCapability\n    url: capabilities/interview-and-screening.yaml\n  - type: NaftikoCapability\n    url: capabilities/recruiting-configuration.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/recruiting.yaml\n  - type: Vocabulary\n    url: vocabulary/workday-recruiting-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Job Requisition Management\n        description: >-\n          Create, edit, close, freeze, and reopen job requisitions for open\n          positions, with full lifecycle and approval workflow support.\n      - name: Evergreen Requisitions\n        description: >-\n          Manage ongoing requisitions used for continuous hiring needs without\n          a specific number of openings or close date.\n      - name: Candidate Management\n        description: >-\n          Create, retrieve, and update candidate profiles including personal\n          information, attachments, photos, and assessment data.\n      - name: Job Application Lifecycle\n\
  \        description: >-\n          Manage applications from submission through disposition, including\n          stage movement, advancement, and offer initiation.\n      - name: Job Posting Distribution\n        description: >-\n          Post, update, and unpost jobs to internal and external career sites\n          and manage job posting site brands and configurations.\n      - name: Interview Scheduling\n        description: >-\n          Schedule interviews, submit interview feedback, configure interview\n          settings, and manage self-schedule calendars.\n      - name: Background Check Integration\n        description: >-\n          Submit and retrieve background check results and manage background\n          check packages for candidate screening.\n      - name: Recruiting Agency Workflows\n        description: >-\n          Manage agency relationships, agency users, and agency candidate\n          submissions tied to job requisitions.\n      - name: High-Volume Applicant Import\n\
  \        description: >-\n          Bulk applicant import operations to support high-volume hiring and\n          third-party sourcing pipelines.\n      - name: Position Management\n        description: >-\n          Create and manage positions and position restrictions within the\n          position management staffing model.\n      - name: Recruiting Configuration\n        description: >-\n          Manage recruiting configuration including questionnaires, assessment\n          categories, veteran statuses, site brands, and regions.\n      - name: OAuth 2.0 Authentication\n        description: >-\n          Standards-based OAuth 2.0 authentication for secure programmatic\n          access to recruiting data.\n      - name: SOAP Web Services\n        description: >-\n          Comprehensive SOAP web services with over 120 recruiting operations\n          for deep enterprise integration.\n  - type: UseCases\n    data:\n      - name: Applicant Tracking System Integration\n        description:\
  \ >-\n          Sync requisitions, candidates, and applications between Workday and\n          third-party ATS or CRM platforms.\n      - name: Talent Sourcing Automation\n        description: >-\n          Push candidates from sourcing tools and job boards into Workday\n          requisition pipelines.\n      - name: Job Board Distribution\n        description: >-\n          Automatically distribute Workday job postings to external job boards\n          and career site networks.\n      - name: Background Screening Workflow\n        description: >-\n          Trigger and ingest background check results from screening vendors\n          tied to candidate stages.\n      - name: Interview Coordination\n        description: >-\n          Integrate with calendar and scheduling tools to coordinate\n          interviewer availability and candidate self-scheduling.\n      - name: Assessment and Skills Testing\n        description: >-\n          Connect Workday Recruiting to assessment platforms\
  \ for skills,\n          behavioral, and technical evaluations.\n      - name: Hiring Analytics and Reporting\n        description: >-\n          Extract recruiting data for reporting in BI tools, data warehouses,\n          and people analytics platforms.\n      - name: Onboarding Handoff\n        description: >-\n          Trigger onboarding workflows in HRIS or onboarding platforms upon\n          requisition fill or hire stage.\n      - name: Recruiting Agency Submissions\n        description: >-\n          Enable third-party staffing agencies to submit candidates directly\n          into Workday requisitions.\n      - name: Compliance and EEO Reporting\n        description: >-\n          Capture self-identification data and applicant flow logs to satisfy\n          EEO, OFCCP, and regional reporting requirements.\n      - name: Internal Mobility\n        description: >-\n          Connect internal career site workflows to surface roles to existing\n          employees.\n      - name:\
  \ High-Volume Hiring\n        description: >-\n          Power retail, hospitality, and seasonal hiring with bulk applicant\n          import and rapid-disposition workflows.\n  - type: Integrations\n    data:\n      - name: Workday HCM\n        description: >-\n          Native integration with Workday Human Capital Management for\n          seamless transition from candidate to employee.\n      - name: LinkedIn Talent Solutions\n        description: >-\n          Connect with LinkedIn Recruiter and LinkedIn Job Postings for\n          sourcing and posting workflows.\n      - name: Indeed\n        description: >-\n          Distribute Workday job postings to Indeed and ingest applications\n          back into Workday.\n      - name: HireRight\n        description: >-\n          Background check integration for criminal, employment, and\n          education verification.\n      - name: Sterling\n        description: >-\n          Background screening, drug testing, and identity verification\n\
  \          integration.\n      - name: HackerRank\n        description: >-\n          Technical assessment integration for engineering and developer\n          hiring pipelines.\n      - name: Calendly\n        description: >-\n          Self-schedule interview integration for candidate-driven scheduling.\n      - name: Microsoft Outlook and Teams\n        description: >-\n          Calendar and meeting integration for interview scheduling and\n          coordination.\n      - name: Google Workspace\n        description: >-\n          Calendar and meeting integration for interview scheduling.\n      - name: DocuSign\n        description: >-\n          E-signature integration for offer letter and onboarding document\n          workflows.\n      - name: Workday Marketplace Partners\n        description: >-\n          Pre-built integrations with talent acquisition vendors listed in\n          the Workday Marketplace.\n  - type: Solutions\n    data:\n      - name: Workday Talent Acquisition\n\
  \        description: >-\n          End-to-end recruiting solution from sourcing through hire,\n          unifying recruiting with the broader Workday HCM platform.\n      - name: HiredScore AI for Recruiting\n        description: >-\n          AI-driven candidate matching, screening, and recruiter productivity\n          embedded in Workday Recruiting.\n      - name: Workday Onboarding\n        description: >-\n          Native onboarding handoff that converts hires into engaged\n          employees inside the Workday HCM system of record.\n      - name: Workday Skills Cloud\n        description: >-\n          Skills-driven hiring leveraging the Workday skills ontology across\n          requisitions and candidate profiles.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday-recruiting/refs/heads/main/apis.yml
tags:
- HCM
- Human Resources
- Recruiting
- SaaS
- Talent Acquisition
url: https://raw.githubusercontent.com/api-evangelist/workday-recruiting/refs/heads/main/apis.yml
use_cases:
- description: Sync requisitions, candidates, and applications between Workday and third-party ATS or CRM platforms.
  name: Applicant Tracking System Integration
- description: Push candidates from sourcing tools and job boards into Workday requisition pipelines.
  name: Talent Sourcing Automation
- description: Automatically distribute Workday job postings to external job boards and career site networks.
  name: Job Board Distribution
- description: Trigger and ingest background check results from screening vendors tied to candidate stages.
  name: Background Screening Workflow
- description: Integrate with calendar and scheduling tools to coordinate interviewer availability and candidate self-scheduling.
  name: Interview Coordination
- description: Connect Workday Recruiting to assessment platforms for skills, behavioral, and technical evaluations.
  name: Assessment and Skills Testing
- description: Extract recruiting data for reporting in BI tools, data warehouses, and people analytics platforms.
  name: Hiring Analytics and Reporting
- description: Trigger onboarding workflows in HRIS or onboarding platforms upon requisition fill or hire stage.
  name: Onboarding Handoff
- description: Enable third-party staffing agencies to submit candidates directly into Workday requisitions.
  name: Recruiting Agency Submissions
- description: Capture self-identification data and applicant flow logs to satisfy EEO, OFCCP, and regional reporting requirements.
  name: Compliance and EEO Reporting
- description: Connect internal career site workflows to surface roles to existing employees.
  name: Internal Mobility
- description: Power retail, hospitality, and seasonal hiring with bulk applicant import and rapid-disposition workflows.
  name: High-Volume Hiring
---
