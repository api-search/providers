---
api_count: 1
api_specs:
- filename: amazon-lake-formation-openapi.yml
  format: yaml
  label: Amazon Lake Formation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-lake-formation/refs/heads/main/openapi/amazon-lake-formation-openapi.yml
apis:
- description: The AWS Lake Formation API provides programmatic access to create and manage data lakes, configure data permissions and access controls, register data sources, and manage data catalog resources for ce
  name: Amazon Lake Formation API
  slug: ''
capabilities:
- description: Unified workflow capability for Amazon Lake Formation combining resource management and operations.
  name: Amazon Lake Formation Workflow
  slug: amazon-lake-formation-workflow
common:
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/big-data/category/analytics/aws-lake-formation/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/lakeformation/home
- title: ''
  type: CLI
  url: https://docs.aws.amazon.com/cli/latest/reference/lakeformation/
- title: ''
  type: SDK
  url: https://aws.amazon.com/tools/
- title: ''
  type: StatusPage
  url: https://status.aws.amazon.com/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: Portal
  url: https://aws.amazon.com/lake-formation/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/lake-formation/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/lake-formation/pricing/
- title: ''
  type: GettingStarted
  url: https://aws.amazon.com/lake-formation/getting-started/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/lake-formation/faqs/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: SpectralRules
  url: rules/amazon-lake-formation-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-lake-formation-workflow.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-lake-formation-vocabulary.yaml
created: '2024-01-15'
description: AWS Lake Formation is a service that makes it easy to set up a secure data lake in days, providing centralized governance and security for data stored in Amazon S3 and other AWS data stores with fine-grained access control.
features:
- description: Grant table, column, row, and cell-level permissions to data in your data lake.
  name: Fine-Grained Access Control
- description: Centrally define and manage security, governance, and auditing policies across the data lake.
  name: Centralized Governance
- description: Integrates with AWS Glue Data Catalog to discover, catalog, and share metadata.
  name: Data Catalog Integration
- description: Securely share data across AWS accounts without copying it.
  name: Cross-Account Data Sharing
- description: ACID transactions and automatic compaction for governed tables stored in S3.
  name: Governed Tables
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Manage and secure data stored in S3 as the data lake storage layer.
  name: Amazon S3
- description: Use Glue Data Catalog as the metadata store and Glue ETL for data transformation.
  name: AWS Glue
- description: Query data lake data using Athena with Lake Formation access controls enforced.
  name: Amazon Athena
- description: Use Redshift Spectrum to query data lake with Lake Formation permissions.
  name: Amazon Redshift
jsonld:
- class_count: 2
  name: Amazon Lake Formation Context
  property_count: 7
  slug: amazon-lake-formation-context
layout: provider
modified: '2026-04-19'
name: Amazon Lake Formation
rules:
- name: Amazon Lake Formation API Rules
  rule_count: 16
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 7
  slug: amazon-lake-formation-spectral-rules
skills: []
slug: amazon-lake-formation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon Lake Formation\nsegments:\n- Data Lakes\n- Analytics\ndescription: AWS Lake Formation is a service that makes it easy to set up a secure data lake in days, providing centralized governance and security for data stored in Amazon S3 and other AWS data \n  stores with fine-grained access control.\nurl: https://aws.amazon.com/lake-formation/\ntype: Index\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\ntags:\n- Access Control\n- Analytics\n- AWS\n- Data Governance\n- Data Lake\n- S3\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon Lake Formation API\n  description: The AWS Lake Formation API provides programmatic access to create and manage data lakes, configure data permissions and access controls, register data sources, and manage data catalog \n    resources for centralized data governance.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/lake-formation/\n\
  \  baseURL: https://lakeformation.amazonaws.com\n  tags:\n  - Access Control\n  - Data Governance\n  - Data Lake\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/lake-formation/latest/dg/what-is-lake-formation.html\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/lakeformation/2017-03-31/openapi.yaml\n  - type: Pricing\n    url: https://aws.amazon.com/lake-formation/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/lake-formation/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/lake-formation/faqs/\n  - type: Features\n    url: https://aws.amazon.com/lake-formation/features/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/lake-formation/latest/dg/what-is-lake-formation.html\n  - type: APIReference\n    url: https://docs.aws.amazon.com/lake-formation/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-lake-formation-openapi.yml\n  - type: JSONLD\n    url: json-ld/amazon-lake-formation-context.jsonld\n\
  \  - type: JSONSchema\n    url: json-schema/amazon-lake-formation-resource-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-lake-formation-permission-schema.json\ncommon:\n- type: Blog\n  url: https://aws.amazon.com/blogs/big-data/category/analytics/aws-lake-formation/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Console\n  url: https://console.aws.amazon.com/lakeformation/home\n- type: CLI\n  url: https://docs.aws.amazon.com/cli/latest/reference/lakeformation/\n- type: SDK\n  url: https://aws.amazon.com/tools/\n- type: StatusPage\n  url: https://status.aws.amazon.com/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: Portal\n  url: https://aws.amazon.com/lake-formation/\n- type: Documentation\n  url: https://docs.aws.amazon.com/lake-formation/\n- type: Pricing\n  url: https://aws.amazon.com/lake-formation/pricing/\n- type: GettingStarted\n  url: https://aws.amazon.com/lake-formation/getting-started/\n\
  - type: FAQ\n  url: https://aws.amazon.com/lake-formation/faqs/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Features\n  data:\n  - name: Fine-Grained Access Control\n    description: Grant table, column, row, and cell-level permissions to data in your data lake.\n  - name: Centralized Governance\n    description: Centrally define and manage security, governance, and auditing policies across the data lake.\n  - name: Data Catalog Integration\n    description: Integrates with AWS Glue Data Catalog to discover, catalog, and share metadata.\n  - name: Cross-Account Data Sharing\n    description: Securely share data across AWS accounts without copying it.\n  - name: Governed Tables\n    description: ACID transactions and automatic compaction for governed tables stored in S3.\n- type: UseCases\n  data:\n  - name: Data Lake Security\n    description:\
  \ Implement fine-grained access control for data stored in S3 with row and column-level security.\n  - name: Self-Service Analytics\n    description: Enable business users to discover and access approved data without manual provisioning.\n  - name: Cross-Account Data Sharing\n    description: Share data lake resources across AWS accounts and organizations.\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Manage and secure data stored in S3 as the data lake storage layer.\n  - name: AWS Glue\n    description: Use Glue Data Catalog as the metadata store and Glue ETL for data transformation.\n  - name: Amazon Athena\n    description: Query data lake data using Athena with Lake Formation access controls enforced.\n  - name: Amazon Redshift\n    description: Use Redshift Spectrum to query data lake with Lake Formation permissions.\n- type: SpectralRules\n  url: rules/amazon-lake-formation-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-lake-formation-workflow.yaml\n\
  - type: Vocabulary\n  url: vocabulary/amazon-lake-formation-vocabulary.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-lake-formation/refs/heads/main/apis.yml
tags:
- Access Control
- Analytics
- AWS
- Data Governance
- Data Lake
- S3
url: https://aws.amazon.com/lake-formation/
use_cases:
- description: Implement fine-grained access control for data stored in S3 with row and column-level security.
  name: Data Lake Security
- description: Enable business users to discover and access approved data without manual provisioning.
  name: Self-Service Analytics
- description: Share data lake resources across AWS accounts and organizations.
  name: Cross-Account Data Sharing
---
