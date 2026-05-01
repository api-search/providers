---
api_count: 1
api_specs:
- filename: amazon-ground-station-openapi.yaml
  format: yaml
  label: AWS Ground Station API
  slug: aws-ground-station-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-ground-station/refs/heads/main/openapi/amazon-ground-station-openapi.yaml
apis:
- description: The AWS Ground Station API provides programmatic access to manage satellite contacts, mission profiles, configs, ground stations, and dataflow endpoint groups for satellite communications and data pro
  name: AWS Ground Station API
  slug: aws-ground-station-api
capabilities:
- description: Workflow capability for satellite operators and mission control teams using Amazon Ground Station. Covers contact scheduling, mission profile management, satellite tracking, and dataflow configuration
  name: Amazon Ground Station Satellite Operations
  slug: amazon-ground-station-satellite-operations
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/ground-station/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/ground-station/
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
  url: https://aws.amazon.com/blogs/publicsector/tag/aws-ground-station/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/groundstation/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-ground-station-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-ground-station-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-ground-station-satellite-operations.yaml
created: '2026-03-16'
description: AWS Ground Station is a fully managed service that lets you control satellite communications, process satellite data, and scale your satellite operations without having to worry about building or managing your own ground station infrastructure.
features:
- description: AWS manages a global network of antennas so you do not need to build or operate your own ground station infrastructure.
  name: Managed Ground Station Infrastructure
- description: Schedule satellite contacts through a simple API, selecting the satellite, time window, and ground station location.
  name: Satellite Contact Scheduling
- description: Access AWS ground station antennas deployed at strategic worldwide locations for maximum satellite coverage.
  name: Global Antenna Network
- description: Receive satellite data directly into AWS cloud services for processing, storage, and analysis.
  name: Data Downlink and Processing
- description: Configure mission profiles specifying dataflow endpoints, antenna frequencies, and processing parameters.
  name: Mission Profile Configuration
- description: Stream satellite data directly into Amazon S3, Kinesis, EC2, and other AWS services for processing.
  name: Integration with AWS Services
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Store downlinked satellite data directly in S3 for archival and processing.
  name: Amazon S3
- description: Stream real-time satellite data into Kinesis for immediate processing.
  name: Amazon Kinesis
- description: Process satellite data on EC2 compute instances co-located with ground station endpoints.
  name: Amazon EC2
- description: Trigger Lambda functions when satellite contact data arrives for automated processing.
  name: AWS Lambda
- description: Apply machine learning to satellite imagery and telemetry data.
  name: Amazon SageMaker
jsonld:
- class_count: 114
  name: Amazon Ground Station Context
  property_count: 155
  slug: amazon-ground-station-context
layout: provider
modified: '2026-04-19'
name: Amazon Ground Station
rules:
- name: Amazon Ground Station API Rules
  rule_count: 8
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 2
  slug: amazon-ground-station-spectral-rules
skills: []
slug: amazon-ground-station
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-ground-station\nname: Amazon Ground Station\ndescription: >-\n  AWS Ground Station is a fully managed service that lets you control satellite\n  communications, process satellite data, and scale your satellite operations\n  without having to worry about building or managing your own ground station\n  infrastructure.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Data Processing\n  - IoT\n  - Satellite Communications\n  - Space Technology\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-ground-station/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-ground-station:aws-ground-station-api\n    name: AWS Ground Station API\n    description: >-\n      The AWS Ground Station API provides programmatic access to manage\n      satellite contacts, mission profiles, configs, ground stations, and\n      dataflow\
  \ endpoint groups for satellite communications and data processing.\n    humanURL: https://aws.amazon.com/ground-station/\n    baseURL: https://groundstation.amazonaws.com\n    tags:\n      - Data Processing\n      - Satellite Communications\n      - Space Technology\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/ground-station/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-ground-station-openapi.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/ground-station/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/ground-station/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/ground-station/faqs/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/ground-station/latest/APIReference/Welcome.html\n      - type: Authentication\n        url: https://docs.aws.amazon.com/general/latest/gr/signature-version-4.html\n      - type: JSONSchema\n\
  \        url: json-schema/ground-station-contact-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-ground-station-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/ground-station/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/ground-station/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/publicsector/tag/aws-ground-station/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/groundstation/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-ground-station-spectral-rules.yml\n\
  \  - type: Vocabulary\n    url: vocabulary/amazon-ground-station-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/amazon-ground-station-satellite-operations.yaml\n  - type: Features\n    data:\n      - name: Managed Ground Station Infrastructure\n        description: AWS manages a global network of antennas so you do not need to build or operate your own ground station infrastructure.\n      - name: Satellite Contact Scheduling\n        description: Schedule satellite contacts through a simple API, selecting the satellite, time window, and ground station location.\n      - name: Global Antenna Network\n        description: Access AWS ground station antennas deployed at strategic worldwide locations for maximum satellite coverage.\n      - name: Data Downlink and Processing\n        description: Receive satellite data directly into AWS cloud services for processing, storage, and analysis.\n      - name: Mission Profile Configuration\n        description: Configure mission\
  \ profiles specifying dataflow endpoints, antenna frequencies, and processing parameters.\n      - name: Integration with AWS Services\n        description: Stream satellite data directly into Amazon S3, Kinesis, EC2, and other AWS services for processing.\n  - type: UseCases\n    data:\n      - name: Earth Observation\n        description: Collect and process satellite imagery for environmental monitoring, agriculture, and urban planning.\n      - name: Weather Forecasting\n        description: Receive data from weather satellites for meteorological analysis and forecasting.\n      - name: Maritime Tracking\n        description: Track ship positions and maritime assets using satellite AIS data.\n      - name: Communications Relay\n        description: Use geostationary satellites for communications relay applications.\n      - name: Scientific Research\n        description: Support space-based scientific missions with managed data collection and downlink.\n  - type: Integrations\n   \
  \ data:\n      - name: Amazon S3\n        description: Store downlinked satellite data directly in S3 for archival and processing.\n      - name: Amazon Kinesis\n        description: Stream real-time satellite data into Kinesis for immediate processing.\n      - name: Amazon EC2\n        description: Process satellite data on EC2 compute instances co-located with ground station endpoints.\n      - name: AWS Lambda\n        description: Trigger Lambda functions when satellite contact data arrives for automated processing.\n      - name: Amazon SageMaker\n        description: Apply machine learning to satellite imagery and telemetry data.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-ground-station/refs/heads/main/apis.yml
tags:
- Data Processing
- IoT
- Satellite Communications
- Space Technology
url: https://raw.githubusercontent.com/api-evangelist/amazon-ground-station/refs/heads/main/apis.yml
use_cases:
- description: Collect and process satellite imagery for environmental monitoring, agriculture, and urban planning.
  name: Earth Observation
- description: Receive data from weather satellites for meteorological analysis and forecasting.
  name: Weather Forecasting
- description: Track ship positions and maritime assets using satellite AIS data.
  name: Maritime Tracking
- description: Use geostationary satellites for communications relay applications.
  name: Communications Relay
- description: Support space-based scientific missions with managed data collection and downlink.
  name: Scientific Research
---
