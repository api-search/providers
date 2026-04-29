---
api_count: 1
api_specs:
- filename: amazon-appflow-openapi.yml
  format: yaml
  label: Amazon AppFlow API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-appflow/refs/heads/main/openapi/amazon-appflow-openapi.yml
apis:
- description: The Amazon AppFlow API enables programmatic creation and management of data flows between SaaS applications and AWS services, including configuring connectors, flow definitions, triggers, and data map
  name: Amazon AppFlow API
  slug: ''
capabilities:
- description: Workflow capability for data engineers and integration architects who need to orchestrate, monitor, and manage SaaS-to-AWS data flows using Amazon AppFlow. Combines flow lifecycle management, connecto
  name: Amazon AppFlow Data Integration
  slug: data-integration
common:
- title: ''
  type: Portal
  url: https://console.aws.amazon.com/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/appflow/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/appflow/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/aws/category/application-integration/amazon-appflow/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/appflow
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://status.aws.amazon.com/
- title: ''
  type: FAQ
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-appflow
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://aws.amazon.com/security/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-appflow-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-appflow-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-integration.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/appflow-api.yaml
created: '2024-01-15'
description: Amazon AppFlow is a fully managed integration service that enables you to securely transfer data between SaaS applications like Salesforce, SAP, Zendesk, Slack, and ServiceNow, and AWS services like Amazon S3 and Amazon Redshift, in just a few clicks.
features:
- description: Create data flows between SaaS applications and AWS services without writing code.
  name: No-Code Data Flows
- description: Schedule data flows to run at configurable intervals using cron or rate expressions.
  name: Scheduled Transfers
- description: Trigger data flows in response to business events from connected SaaS applications.
  name: Event-Triggered Flows
- description: Manually trigger data flows for ad-hoc data transfers.
  name: On-Demand Execution
- description: Apply field mapping, filtering, masking, merging, and arithmetic transformations during transfer.
  name: Data Transformations
- description: Transfer only new or changed records since the last flow run using datetime-based incremental pulls.
  name: Incremental Data Pull
- description: Register custom Lambda-backed connectors for proprietary or unsupported data sources.
  name: Custom Connectors
- description: Automatically catalog transferred data in AWS Glue Data Catalog for discoverability.
  name: Data Catalog Integration
- description: Encrypt data in transit and at rest using AWS KMS customer-managed keys.
  name: KMS Encryption
- description: Transfer data privately over AWS PrivateLink without traversing the public internet.
  name: Private Link Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Bidirectional data transfer between Salesforce CRM and AWS services.
  name: Salesforce
- description: Transfer data from SAP ERP systems via SAPOData connector.
  name: SAP
- description: Sync ServiceNow ITSM data to AWS for analytics and reporting.
  name: ServiceNow
- description: Export Slack workspace data to Amazon S3.
  name: Slack
- description: Transfer Zendesk customer support tickets and data to AWS.
  name: Zendesk
- description: Import Marketo marketing automation data into Amazon Redshift or S3.
  name: Marketo
- description: Export Google Analytics data to Amazon S3 for custom analytics pipelines.
  name: Google Analytics
- description: Use Amazon S3 as both source and destination for AppFlow data flows.
  name: Amazon S3
- description: Load SaaS data directly into Amazon Redshift for SQL analytics.
  name: Amazon Redshift
- description: Send AppFlow data to Amazon EventBridge for event-driven architectures.
  name: Amazon EventBridge
- description: Catalog AppFlow output data automatically in AWS Glue Data Catalog.
  name: AWS Glue
- description: Feed SaaS data into SageMaker Data Wrangler for ML preparation.
  name: Amazon SageMaker
jsonld:
- class_count: 61
  name: Amazon Appflow Context
  property_count: 120
  slug: amazon-appflow-context
layout: provider
modified: '2026-04-19'
name: Amazon AppFlow
rules:
- name: Amazon AppFlow API Rules
  rule_count: 34
  severity_counts:
    error: 17
    hint: 0
    info: 2
    warn: 15
  slug: amazon-appflow-spectral-rules
skills: []
slug: amazon-appflow
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-appflow\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-appflow/refs/heads/main/apis.yml\nname: Amazon AppFlow\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nspecificationVersion: '0.19'\ndescription: >-\n  Amazon AppFlow is a fully managed integration service that enables you to\n  securely transfer data between SaaS applications like Salesforce, SAP,\n  Zendesk, Slack, and ServiceNow, and AWS services like Amazon S3 and\n  Amazon Redshift, in just a few clicks.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\ntags:\n- AWS\n- Connectors\n- Data Flow\n- Data Integration\n- ETL\n- Integration\n- SaaS\n- Data Transfer\napis:\n- name: Amazon AppFlow API\n  description: >-\n    The Amazon AppFlow API enables programmatic creation and management of\n    data flows between SaaS applications and AWS services, including\n    configuring connectors, flow definitions, triggers, and data mappings.\n  image:\
  \ https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/appflow/\n  baseURL: https://appflow.amazonaws.com\n  tags:\n  - Connectors\n  - Data Integration\n  - Data Transfer\n  - ETL\n  - Integration\n  - SaaS\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/appflow/latest/userguide/what-is-appflow.html\n  - type: OpenAPI\n    url: openapi/amazon-appflow-openapi.yml\n  - type: APIReference\n    url: https://docs.aws.amazon.com/appflow/1.0/APIReference/Welcome.html\n  - type: Pricing\n    url: https://aws.amazon.com/appflow/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/appflow/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/appflow/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-appflow-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-cancel-flow-executions-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-cancel-flow-executions-response-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/appflow-connector-detail-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-connector-entity-field-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-connector-entity-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-connector-profile-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-create-connector-profile-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-create-connector-profile-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-create-flow-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-create-flow-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-delete-connector-profile-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-delete-flow-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-describe-connector-entity-request-schema.json\n  - type: JSONSchema\n  \
  \  url: json-schema/appflow-describe-connector-entity-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-describe-connector-profiles-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-describe-connector-profiles-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-describe-connector-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-describe-connector-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-describe-connectors-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-describe-connectors-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-describe-flow-execution-records-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-describe-flow-execution-records-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-describe-flow-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-describe-flow-response-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/appflow-destination-flow-config-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-execution-details-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-execution-result-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-flow-definition-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-flow-execution-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-list-connector-entities-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-list-connector-entities-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-list-connectors-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-list-connectors-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-list-flows-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-list-flows-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-list-tags-for-resource-response-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/appflow-metadata-catalog-config-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-register-connector-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-register-connector-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-reset-connector-metadata-cache-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-scheduled-trigger-properties-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-source-flow-config-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-start-flow-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-start-flow-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-stop-flow-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-stop-flow-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-tag-resource-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-task-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/appflow-trigger-config-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-unregister-connector-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-update-connector-profile-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-update-connector-profile-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-update-connector-registration-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-update-connector-registration-response-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-update-flow-request-schema.json\n  - type: JSONSchema\n    url: json-schema/appflow-update-flow-response-schema.json\n  - type: JSONStructure\n    url: json-structure/amazon-appflow-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-cancel-flow-executions-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-cancel-flow-executions-response-structure.json\n\
  \  - type: JSONStructure\n    url: json-structure/appflow-connector-detail-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-connector-entity-field-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-connector-entity-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-connector-profile-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-create-connector-profile-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-create-connector-profile-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-create-flow-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-create-flow-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-delete-connector-profile-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-delete-flow-request-structure.json\n  - type: JSONStructure\n    url:\
  \ json-structure/appflow-describe-connector-entity-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-describe-connector-entity-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-describe-connector-profiles-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-describe-connector-profiles-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-describe-connector-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-describe-connector-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-describe-connectors-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-describe-connectors-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-describe-flow-execution-records-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-describe-flow-execution-records-response-structure.json\n\
  \  - type: JSONStructure\n    url: json-structure/appflow-describe-flow-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-describe-flow-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-destination-flow-config-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-execution-details-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-execution-result-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-flow-definition-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-flow-execution-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-list-connector-entities-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-list-connector-entities-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-list-connectors-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-list-connectors-response-structure.json\n\
  \  - type: JSONStructure\n    url: json-structure/appflow-list-flows-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-list-flows-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-list-tags-for-resource-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-metadata-catalog-config-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-register-connector-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-register-connector-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-reset-connector-metadata-cache-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-scheduled-trigger-properties-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-source-flow-config-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-start-flow-request-structure.json\n  - type: JSONStructure\n\
  \    url: json-structure/appflow-start-flow-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-stop-flow-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-stop-flow-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-tag-resource-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-task-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-trigger-config-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-unregister-connector-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-update-connector-profile-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-update-connector-profile-response-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-update-connector-registration-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-update-connector-registration-response-structure.json\n\
  \  - type: JSONStructure\n    url: json-structure/appflow-update-flow-request-structure.json\n  - type: JSONStructure\n    url: json-structure/appflow-update-flow-response-structure.json\n  - type: JSONLD\n    url: json-ld/amazon-appflow-context.jsonld\n  - type: Example\n    url: examples/amazon-appflow-example.json\n  - type: Example\n    url: examples/appflow-cancel-flow-executions-request-example.json\n  - type: Example\n    url: examples/appflow-cancel-flow-executions-response-example.json\n  - type: Example\n    url: examples/appflow-connector-detail-example.json\n  - type: Example\n    url: examples/appflow-connector-entity-example.json\n  - type: Example\n    url: examples/appflow-connector-entity-field-example.json\n  - type: Example\n    url: examples/appflow-connector-profile-example.json\n  - type: Example\n    url: examples/appflow-create-connector-profile-request-example.json\n  - type: Example\n    url: examples/appflow-create-connector-profile-response-example.json\n  -\
  \ type: Example\n    url: examples/appflow-create-flow-request-example.json\n  - type: Example\n    url: examples/appflow-create-flow-response-example.json\n  - type: Example\n    url: examples/appflow-delete-connector-profile-request-example.json\n  - type: Example\n    url: examples/appflow-delete-flow-request-example.json\n  - type: Example\n    url: examples/appflow-describe-connector-entity-request-example.json\n  - type: Example\n    url: examples/appflow-describe-connector-entity-response-example.json\n  - type: Example\n    url: examples/appflow-describe-connector-profiles-request-example.json\n  - type: Example\n    url: examples/appflow-describe-connector-profiles-response-example.json\n  - type: Example\n    url: examples/appflow-describe-connector-request-example.json\n  - type: Example\n    url: examples/appflow-describe-connector-response-example.json\n  - type: Example\n    url: examples/appflow-describe-connectors-request-example.json\n  - type: Example\n    url: examples/appflow-describe-connectors-response-example.json\n\
  \  - type: Example\n    url: examples/appflow-describe-flow-execution-records-request-example.json\n  - type: Example\n    url: examples/appflow-describe-flow-execution-records-response-example.json\n  - type: Example\n    url: examples/appflow-describe-flow-request-example.json\n  - type: Example\n    url: examples/appflow-describe-flow-response-example.json\n  - type: Example\n    url: examples/appflow-destination-flow-config-example.json\n  - type: Example\n    url: examples/appflow-execution-details-example.json\n  - type: Example\n    url: examples/appflow-execution-result-example.json\n  - type: Example\n    url: examples/appflow-flow-definition-example.json\n  - type: Example\n    url: examples/appflow-flow-execution-example.json\n  - type: Example\n    url: examples/appflow-list-connector-entities-request-example.json\n  - type: Example\n    url: examples/appflow-list-connector-entities-response-example.json\n  - type: Example\n    url: examples/appflow-list-connectors-request-example.json\n\
  \  - type: Example\n    url: examples/appflow-list-connectors-response-example.json\n  - type: Example\n    url: examples/appflow-list-flows-request-example.json\n  - type: Example\n    url: examples/appflow-list-flows-response-example.json\n  - type: Example\n    url: examples/appflow-list-tags-for-resource-response-example.json\n  - type: Example\n    url: examples/appflow-metadata-catalog-config-example.json\n  - type: Example\n    url: examples/appflow-register-connector-request-example.json\n  - type: Example\n    url: examples/appflow-register-connector-response-example.json\n  - type: Example\n    url: examples/appflow-reset-connector-metadata-cache-request-example.json\n  - type: Example\n    url: examples/appflow-scheduled-trigger-properties-example.json\n  - type: Example\n    url: examples/appflow-source-flow-config-example.json\n  - type: Example\n    url: examples/appflow-start-flow-request-example.json\n  - type: Example\n    url: examples/appflow-start-flow-response-example.json\n\
  \  - type: Example\n    url: examples/appflow-stop-flow-request-example.json\n  - type: Example\n    url: examples/appflow-stop-flow-response-example.json\n  - type: Example\n    url: examples/appflow-tag-resource-request-example.json\n  - type: Example\n    url: examples/appflow-task-example.json\n  - type: Example\n    url: examples/appflow-trigger-config-example.json\n  - type: Example\n    url: examples/appflow-unregister-connector-request-example.json\n  - type: Example\n    url: examples/appflow-update-connector-profile-request-example.json\n  - type: Example\n    url: examples/appflow-update-connector-profile-response-example.json\n  - type: Example\n    url: examples/appflow-update-connector-registration-request-example.json\n  - type: Example\n    url: examples/appflow-update-connector-registration-response-example.json\n  - type: Example\n    url: examples/appflow-update-flow-request-example.json\n  - type: Example\n    url: examples/appflow-update-flow-response-example.json\n\
  common:\n- type: Portal\n  url: https://console.aws.amazon.com/\n- type: DeveloperPortal\n  url: https://aws.amazon.com/appflow/\n- type: Documentation\n  url: https://docs.aws.amazon.com/appflow/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/aws/category/application-integration/amazon-appflow/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/appflow\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://status.aws.amazon.com/\n- type: FAQ\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-appflow\n\
  - type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Security\n  url: https://aws.amazon.com/security/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: SpectralRules\n  url: rules/amazon-appflow-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-appflow-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/data-integration.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/appflow-api.yaml\n- type: Features\n  data:\n  - name: No-Code Data Flows\n    description: Create data flows between SaaS applications and AWS services without writing code.\n  - name: Scheduled Transfers\n    description: Schedule data flows to run at configurable intervals using cron or rate expressions.\n  - name: Event-Triggered Flows\n    description: Trigger data flows in response to business events from connected SaaS applications.\n  - name: On-Demand Execution\n    description: Manually trigger data flows for ad-hoc data transfers.\n  -\
  \ name: Data Transformations\n    description: Apply field mapping, filtering, masking, merging, and arithmetic transformations during transfer.\n  - name: Incremental Data Pull\n    description: Transfer only new or changed records since the last flow run using datetime-based incremental pulls.\n  - name: Custom Connectors\n    description: Register custom Lambda-backed connectors for proprietary or unsupported data sources.\n  - name: Data Catalog Integration\n    description: Automatically catalog transferred data in AWS Glue Data Catalog for discoverability.\n  - name: KMS Encryption\n    description: Encrypt data in transit and at rest using AWS KMS customer-managed keys.\n  - name: Private Link Support\n    description: Transfer data privately over AWS PrivateLink without traversing the public internet.\n- type: UseCases\n  data:\n  - name: Customer 360\n    description: Consolidate marketing, sales, and support data from Salesforce, Marketo, and ServiceNow into Amazon Redshift or\
  \ S3 for unified customer analytics.\n  - name: ML Data Preparation\n    description: Ingest SaaS data into Amazon SageMaker Data Wrangler for machine learning feature engineering and model training.\n  - name: Data Lake Ingestion\n    description: Load SaaS application data into Amazon S3 data lakes for centralized analytics and reporting.\n  - name: Real-Time Analytics\n    description: Transfer Salesforce data in near real-time to Amazon Redshift for operational dashboards and BI reporting.\n  - name: Cross-Application Automation\n    description: Automate workflows by triggering data flows when records are created or updated in SaaS applications.\n  - name: Data Compliance\n    description: Securely extract and archive regulated data from SaaS applications into encrypted AWS storage for compliance auditing.\n- type: Integrations\n  data:\n  - name: Salesforce\n    description: Bidirectional data transfer between Salesforce CRM and AWS services.\n  - name: SAP\n    description: Transfer\
  \ data from SAP ERP systems via SAPOData connector.\n  - name: ServiceNow\n    description: Sync ServiceNow ITSM data to AWS for analytics and reporting.\n  - name: Slack\n    description: Export Slack workspace data to Amazon S3.\n  - name: Zendesk\n    description: Transfer Zendesk customer support tickets and data to AWS.\n  - name: Marketo\n    description: Import Marketo marketing automation data into Amazon Redshift or S3.\n  - name: Google Analytics\n    description: Export Google Analytics data to Amazon S3 for custom analytics pipelines.\n  - name: Amazon S3\n    description: Use Amazon S3 as both source and destination for AppFlow data flows.\n  - name: Amazon Redshift\n    description: Load SaaS data directly into Amazon Redshift for SQL analytics.\n  - name: Amazon EventBridge\n    description: Send AppFlow data to Amazon EventBridge for event-driven architectures.\n  - name: AWS Glue\n    description: Catalog AppFlow output data automatically in AWS Glue Data Catalog.\n  -\
  \ name: Amazon SageMaker\n    description: Feed SaaS data into SageMaker Data Wrangler for ML preparation.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-appflow/refs/heads/main/apis.yml
tags:
- AWS
- Connectors
- Data Flow
- Data Integration
- ETL
- Integration
- SaaS
- Data Transfer
url: https://raw.githubusercontent.com/api-evangelist/amazon-appflow/refs/heads/main/apis.yml
use_cases:
- description: Consolidate marketing, sales, and support data from Salesforce, Marketo, and ServiceNow into Amazon Redshift or S3 for unified customer analytics.
  name: Customer 360
- description: Ingest SaaS data into Amazon SageMaker Data Wrangler for machine learning feature engineering and model training.
  name: ML Data Preparation
- description: Load SaaS application data into Amazon S3 data lakes for centralized analytics and reporting.
  name: Data Lake Ingestion
- description: Transfer Salesforce data in near real-time to Amazon Redshift for operational dashboards and BI reporting.
  name: Real-Time Analytics
- description: Automate workflows by triggering data flows when records are created or updated in SaaS applications.
  name: Cross-Application Automation
- description: Securely extract and archive regulated data from SaaS applications into encrypted AWS storage for compliance auditing.
  name: Data Compliance
---
