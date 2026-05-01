---
api_count: 1
api_specs:
- filename: aws-b2b-data-interchange-api-openapi.yml
  format: yaml
  label: AWS B2B Data Interchange API
  slug: aws-b2b-data-interchange-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/openapi/aws-b2b-data-interchange-api-openapi.yml
apis:
- description: The AWS B2B Data Interchange API provides programmatic access to manage EDI transformation workflows, trading partner profiles, capabilities, partnerships, and transformers. It enables creation and ma
  name: AWS B2B Data Interchange API
  slug: aws-b2b-data-interchange-api
capabilities: []
common:
- title: ''
  type: CLI
  url: https://docs.aws.amazon.com/cli/latest/reference/b2bi/
- title: ''
  type: SDK
  url: https://github.com/aws/aws-sdk-js-v3/tree/main/clients/client-b2bi
- title: ''
  type: SDK
  url: https://pkg.go.dev/github.com/aws/aws-sdk-go-v2/service/b2bi
- title: ''
  type: SDK
  url: https://docs.rs/aws-sdk-b2bi
- title: ''
  type: Samples
  url: https://github.com/aws-samples/aws-b2b-data-interchange-toolkit
- title: ''
  type: CloudFormation
  url: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/AWS_B2BI.html
- title: ''
  type: Pricing
  url: https://aws.amazon.com/b2b-data-interchange/pricing/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
created: '2026-03-16'
description: AWS B2B Data Interchange is a fully managed service that automates the transformation and exchange of electronic data interchange (EDI) documents at cloud scale. It enables businesses to onboard trading partners, transform X12 EDI documents to and from JSON or XML, and manage capabilities, profiles, and partnerships with pay-as-you-go pricing. The service supports supply chain, healthcare, and financial services workflows and leverages Amazon Bedrock for AI-assisted mapping generation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 36
  name: context Context
  property_count: 2
  slug: context
layout: provider
modified: '2026-04-19'
name: Amazon B2B Data Interchange
skills: []
slug: amazon-b2b-data-interchange
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-b2b-data-interchange\nname: Amazon B2B Data Interchange\ndescription: >-\n  AWS B2B Data Interchange is a fully managed service that automates the\n  transformation and exchange of electronic data interchange (EDI) documents\n  at cloud scale. It enables businesses to onboard trading partners, transform\n  X12 EDI documents to and from JSON or XML, and manage capabilities,\n  profiles, and partnerships with pay-as-you-go pricing. The service supports\n  supply chain, healthcare, and financial services workflows and leverages\n  Amazon Bedrock for AI-assisted mapping generation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - EDI\n  - B2B\n  - Data Interchange\n  - Supply Chain\n  - Healthcare\n  - Financial Services\n  - Amazon Web Services\n  - AWS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\n\
  specificationVersion: '0.19'\napis:\n  - aid: amazon-b2b-data-interchange:aws-b2b-data-interchange-api\n    name: AWS B2B Data Interchange API\n    description: >-\n      The AWS B2B Data Interchange API provides programmatic access to manage\n      EDI transformation workflows, trading partner profiles, capabilities,\n      partnerships, and transformers. It enables creation and management of\n      inbound and outbound EDI pipelines using X12 standards and supports\n      AI-assisted mapping template generation via Amazon Bedrock.\n    humanURL: https://docs.aws.amazon.com/b2bi/latest/APIReference/api-welcome.html\n    baseURL: https://b2bi.us-east-1.amazonaws.com\n    tags:\n      - EDI\n      - B2B\n      - Transformation\n      - X12\n      - Trading Partners\n      - Capabilities\n      - Profiles\n      - Partnerships\n      - Transformers\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/b2bi/latest/APIReference/api-welcome.html\n      - type:\
  \ Documentation\n        url: https://docs.aws.amazon.com/b2bi/latest/userguide/what-is-b2bi.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/openapi/aws-b2b-data-interchange-api-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/json-schema/profile.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/json-schema/partnership.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/json-schema/transformer.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/json-structure/b2bi-resource-structure.json\n\
  \      - type: JSONLD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/json-ld/context.jsonld\n      - type: SpectralRuleset\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/spectral/ruleset.yml\n      - type: Capabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/capabilities/capabilities.yml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/vocabulary/vocabulary.yml\n    contact:\n      - FN: AWS Support\n        url: https://aws.amazon.com/contact-us/\n    features:\n      - name: EDI Transformation\n        description: >-\n          Transform X12 EDI documents to JSON or XML and generate EDI from\n          JSON/XML data inputs, automating inbound and outbound EDI workflows.\n\
  \      - name: AI-Assisted Mapping\n        description: >-\n          Use Amazon Bedrock to automatically generate mapping templates,\n          reducing mapping code development time by up to 50%.\n      - name: Trading Partner Management\n        description: >-\n          Onboard and manage trading partners through profiles, capabilities,\n          and partnerships with visibility into transactional communications.\n      - name: EDI Splitting\n        description: >-\n          Split inbound X12 EDI documents containing multiple transactions into\n          individually processed single-transaction documents, supporting files\n          up to 5GB.\n      - name: HIPAA Compliance\n        description: >-\n          Supports secure exchange of protected health information for\n          healthcare EDI workflows in compliance with HIPAA requirements.\n    useCases:\n      - name: Supply Chain Partner Onboarding\n        description: >-\n          Automate onboarding of trading partners\
  \ in supply chain networks,\n          enabling rapid EDI integration without custom development.\n      - name: Healthcare Claims Processing\n        description: >-\n          Streamline healthcare enrollment and claims processing workflows\n          using X12 EDI standards with HIPAA-compliant data exchange.\n      - name: Financial Transaction Processing\n        description: >-\n          Expedite complex financial transactions like mortgage applications\n          and tax assessments through automated EDI transformation.\n    integrations:\n      - name: AWS Transfer Family\n        description: >-\n          Integrate with AWS Transfer Family for managed file transfer\n          ingestion workflows into the B2B Data Interchange pipeline.\n      - name: Amazon S3\n        description: >-\n          Monitor S3 locations for inbound EDI documents and write transformed\n          outputs to S3 buckets for downstream processing.\n      - name: Amazon EventBridge\n        description:\
  \ >-\n          Trigger event-driven workflows from EDI transformation events using\n          Amazon EventBridge integration.\n      - name: Amazon Bedrock\n        description: >-\n          Leverage Amazon Bedrock generative AI for automated mapping template\n          generation from source and target schemas.\n    solutions:\n      - name: EDI Modernization\n        description: >-\n          Migrate from legacy EDI infrastructure to a cloud-native managed\n          service with pay-as-you-go pricing and no upfront investment.\n      - name: Multi-Partner EDI Network\n        description: >-\n          Build and manage multi-partner EDI networks with centralized\n          visibility and standardized transformation pipelines.\ncommon:\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/b2bi/\n  - type: SDK\n    url: https://github.com/aws/aws-sdk-js-v3/tree/main/clients/client-b2bi\n  - type: SDK\n    url: https://pkg.go.dev/github.com/aws/aws-sdk-go-v2/service/b2bi\n\
  \  - type: SDK\n    url: https://docs.rs/aws-sdk-b2bi\n  - type: Samples\n    url: https://github.com/aws-samples/aws-b2b-data-interchange-toolkit\n  - type: CloudFormation\n    url: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/AWS_B2BI.html\n  - type: Pricing\n    url: https://aws.amazon.com/b2b-data-interchange/pricing/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/apis.yml
tags:
- EDI
- B2B
- Data Interchange
- Supply Chain
- Healthcare
- Financial Services
- Amazon Web Services
url: https://raw.githubusercontent.com/api-evangelist/amazon-b2b-data-interchange/refs/heads/main/apis.yml
use_cases: []
---
