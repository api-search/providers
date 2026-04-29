---
api_count: 7
apis:
- description: Amazon Kinesis Data Streams is a massively scalable and durable real-time data streaming service. It can continuously capture gigabytes of data per second from hundreds of thousands of sources such as
  name: Amazon Kinesis Data Streams
  slug: ''
- description: Amazon Data Firehose (formerly Amazon Kinesis Data Firehose) is the easiest way to reliably load streaming data into data lakes, data stores, and analytics services. It can capture, transform, and del
  name: Amazon Data Firehose
  slug: ''
- description: Amazon Managed Service for Apache Flink (formerly Amazon Kinesis Data Analytics) is a fully managed service for processing and analyzing streaming data in real time using Apache Flink. You can build a
  name: Amazon Managed Service for Apache Flink
  slug: ''
- description: Amazon Kinesis Video Streams makes it easy to securely stream video from connected devices to AWS for analytics, machine learning, playback, and other processing. It automatically provisions and elast
  name: Amazon Kinesis Video Streams
  slug: ''
- description: The Amazon Kinesis Video Streams Media API provides operations for reading and writing media data to and from a Kinesis video stream, enabling real-time media ingestion and consumption.
  name: Amazon Kinesis Video Streams Media
  slug: ''
- description: The Amazon Kinesis Video Streams Archived Media API provides operations for accessing archived video data from Kinesis video streams, including retrieving clips, HLS and DASH streaming session URLs, i
  name: Amazon Kinesis Video Streams Archived Media
  slug: ''
- description: The Amazon Kinesis Video Signaling Channels API facilitates peer-to-peer WebRTC communication by enabling applications to securely discover each other and exchange connection offers and answers throug
  name: Amazon Kinesis Video Signaling Channels
  slug: ''
asyncapis:
- description: Amazon Kinesis Data Streams is a massively scalable and durable real-time data streaming service. This AsyncAPI specification describes the event-driven consumer patterns for Kinesis Data Streams, inc
  name: Amazon Kinesis Data Streams
  slug: amazon-kinesis-streams-asyncapi
capabilities:
- description: Unified workflow capability for Amazon Kinesis combining resource management and operations.
  name: Amazon Kinesis Workflow
  slug: amazon-kinesis-workflow
common:
- title: ''
  type: FAQ
  url: https://aws.amazon.com/kinesis/data-streams/faqs/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/big-data/category/analytics/amazon-kinesis/
- title: ''
  type: Customers
  url: https://aws.amazon.com/kinesis/customers/
- title: ''
  type: Resources
  url: https://aws.amazon.com/kinesis/resources/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/kinesis/
- title: ''
  type: SDK & Tools
  url: https://aws.amazon.com/tools/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/kinesis/
- title: ''
  type: Firehose Blog
  url: https://aws.amazon.com/blogs/big-data/category/analytics/amazon-kinesis/kinesis-data-firehose/
- title: ''
  type: Video Streams FAQs
  url: https://aws.amazon.com/kinesis/video-streams/faqs/
- title: ''
  type: Firehose FAQs
  url: https://aws.amazon.com/firehose/faqs/
- title: ''
  type: Managed Flink FAQs
  url: https://aws.amazon.com/managed-service-apache-flink/faqs/
- title: ''
  type: Video Streams Resources
  url: https://aws.amazon.com/kinesis/video-streams/resources/
- title: ''
  type: Portal
  url: https://aws.amazon.com/kinesis/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/kinesis/data-streams/pricing/
- title: ''
  type: Authentication
  url: https://docs.aws.amazon.com/streams/latest/dev/tutorial-stock-data-kplkcl-iam.html
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
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
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/amazon-kinesis
- title: ''
  type: SpectralRules
  url: rules/amazon-kinesis-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-kinesis-workflow.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-kinesis-vocabulary.yaml
created: 2024-01-01 00:00:00+00:00
description: Amazon Kinesis makes it easy to collect, process, and analyze real-time streaming data so you can get timely insights and react quickly to new information. Amazon Kinesis offers key capabilities to cost-effectively process streaming data at any scale, along with the flexibility to choose the tools that best suit the requirements of your application.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Trigger Lambda functions to process records from Kinesis streams.
  name: AWS Lambda
- description: Use Kinesis streams as source for Firehose delivery.
  name: Amazon Kinesis Data Firehose
- description: Store processed streaming records in DynamoDB.
  name: Amazon DynamoDB
jsonld:
- class_count: 2
  name: Amazon Kinesis Context
  property_count: 7
  slug: amazon-kinesis-context
layout: provider
modified: '2026-04-19'
name: Amazon Kinesis
rules:
- name: Amazon Kinesis API Rules
  rule_count: 16
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 7
  slug: amazon-kinesis-spectral-rules
skills: []
slug: amazon-kinesis
solutions: []
source_yaml: "name: Amazon Kinesis\ndescription: Amazon Kinesis makes it easy to collect, process, and analyze real-time streaming data so you can get timely insights and react quickly to new information. Amazon Kinesis offers key \n  capabilities to cost-effectively process streaming data at any scale, along with the flexibility to choose the tools that best suit the requirements of your application.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-search/amazon-web-services/main/apis/kinesis.yml\ncreated: 2024-01-01 00:00:00+00:00\nmodified: '2026-04-19'\nspecificationVersion: '0.18'\ntags:\n- Analytics\n- Big Data\n- Data Processing\n- Real-Time\n- Streaming\napis:\n- name: Amazon Kinesis Data Streams\n  description: Amazon Kinesis Data Streams is a massively scalable and durable real-time data streaming service. It can continuously capture gigabytes of data per second from hundreds of thousands of \n    sources\
  \ such as website clickstreams, database event streams, financial transactions, social media feeds, IT logs, and location-tracking events.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://aws.amazon.com/kinesis/data-streams/\n  baseURL: https://kinesis.amazonaws.com\n  tags:\n  - Data Ingestion\n  - Real-Time\n  - Streams\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/kinesis/latest/APIReference/\n  - type: OpenAPI\n    url: openapi/amazon-kinesis-data-streams-openapi.yml\n  - type: AsyncAPI\n    url: asyncapi/amazon-kinesis-streams-asyncapi.yml\n  - type: JSONSchema\n    url: json-schema/amazon-kinesis-record-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-kinesis-context.jsonld\n  - type: OpenAPI (Third-Party)\n    url: https://api.apis.guru/v2/specs/amazonaws.com/kinesis/2013-12-02/openapi.yaml\n  - type: Pricing\n    url: https://aws.amazon.com/kinesis/data-streams/pricing/\n  - type: GettingStarted\n\
  \    url: https://aws.amazon.com/kinesis/data-streams/getting-started/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/streams/latest/dev/introduction.html\n  - type: Features\n    url: https://aws.amazon.com/kinesis/data-streams/features/\n  - type: FAQ\n    url: https://aws.amazon.com/kinesis/data-streams/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/kinesis/latest/APIReference/\n  - type: Quotas\n    url: https://docs.aws.amazon.com/streams/latest/dev/service-sizes-and-limits.html\n  - type: JSONSchema\n    url: json-schema/amazon-kinesis-stream-schema.json\n- name: Amazon Data Firehose\n  description: Amazon Data Firehose (formerly Amazon Kinesis Data Firehose) is the easiest way to reliably load streaming data into data lakes, data stores, and analytics services. It can capture, \n    transform, and deliver streaming data to destinations like Amazon S3, Amazon Redshift, Amazon OpenSearch Service, Snowflake, Splunk, and more.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \  humanURL: https://aws.amazon.com/kinesis/data-firehose/\n  baseURL: https://firehose.amazonaws.com\n  tags:\n  - Data Loading\n  - ETL\n  - Streaming\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/firehose/latest/APIReference/\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/firehose/2015-08-04/openapi.yaml\n  - type: Pricing\n    url: https://aws.amazon.com/kinesis/data-firehose/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/kinesis/data-firehose/getting-started/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/firehose/latest/dev/what-is-this-service.html\n  - type: Features\n    url: https://aws.amazon.com/kinesis/data-firehose/features/\n  - type: FAQ\n    url: https://aws.amazon.com/firehose/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-kinesis-stream-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-kinesis-record-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-kinesis-context.jsonld\n\
  - name: Amazon Managed Service for Apache Flink\n  description: Amazon Managed Service for Apache Flink (formerly Amazon Kinesis Data Analytics) is a fully managed service for processing and analyzing streaming data in real time using Apache Flink. \n    You can build applications using Java, Python, Scala, or SQL to transform and analyze streaming data with sub-second latencies.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://aws.amazon.com/managed-service-apache-flink/\n  baseURL: https://kinesisanalytics.amazonaws.com\n  tags:\n  - Analytics\n  - Apache Flink\n  - SQL\n  - Stream Processing\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/managed-flink/latest/apiv2/Welcome.html\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/kinesisanalyticsv2/2018-05-23/openapi.yaml\n  - type: Pricing\n    url: https://aws.amazon.com/managed-service-apache-flink/pricing/\n  - type: GettingStarted\n\
  \    url: https://docs.aws.amazon.com/managed-flink/latest/java/getting-started.html\n  - type: Documentation\n    url: https://docs.aws.amazon.com/managed-flink/latest/java/what-is.html\n  - type: Features\n    url: https://aws.amazon.com/managed-service-apache-flink/features/\n  - type: FAQ\n    url: https://aws.amazon.com/managed-service-apache-flink/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-kinesis-stream-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-kinesis-record-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-kinesis-context.jsonld\n- name: Amazon Kinesis Video Streams\n  description: Amazon Kinesis Video Streams makes it easy to securely stream video from connected devices to AWS for analytics, machine learning, playback, and other processing. It automatically \n    provisions and elastically scales infrastructure needed to ingest streaming video data from millions of devices.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \  humanURL: https://aws.amazon.com/kinesis/video-streams/\n  baseURL: https://kinesisvideo.amazonaws.com\n  tags:\n  - IoT\n  - Machine Learning\n  - Streaming\n  - Video\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/kinesisvideostreams/latest/dg/\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/kinesisvideo/2017-09-30/openapi.yaml\n  - type: Pricing\n    url: https://aws.amazon.com/kinesis/video-streams/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/kinesis/video-streams/getting-started/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/kinesisvideostreams/latest/dg/API_Reference.html\n  - type: Features\n    url: https://aws.amazon.com/kinesis/video-streams/features/\n  - type: FAQ\n    url: https://aws.amazon.com/kinesis/video-streams/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-kinesis-stream-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-kinesis-record-schema.json\n\
  \  - type: JSONLD\n    url: json-ld/amazon-kinesis-context.jsonld\n- name: Amazon Kinesis Video Streams Media\n  description: The Amazon Kinesis Video Streams Media API provides operations for reading and writing media data to and from a Kinesis video stream, enabling real-time media ingestion and consumption.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://docs.aws.amazon.com/kinesisvideostreams/latest/dg/API_Operations_Amazon_Kinesis_Video_Streams_Media.html\n  baseURL: https://kinesisvideo.amazonaws.com\n  tags:\n  - Media\n  - Real-Time\n  - Streaming\n  - Video\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/kinesisvideostreams/latest/dg/API_Operations_Amazon_Kinesis_Video_Streams_Media.html\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/kinesis-video-media/2017-09-30/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-kinesis-stream-schema.json\n  - type:\
  \ JSONSchema\n    url: json-schema/amazon-kinesis-record-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-kinesis-context.jsonld\n- name: Amazon Kinesis Video Streams Archived Media\n  description: The Amazon Kinesis Video Streams Archived Media API provides operations for accessing archived video data from Kinesis video streams, including retrieving clips, HLS and DASH streaming \n    session URLs, images, and fragment lists.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://docs.aws.amazon.com/kinesisvideostreams/latest/dg/API_Operations_Amazon_Kinesis_Video_Streams_Archived_Media.html\n  baseURL: https://kinesisvideo.amazonaws.com\n  tags:\n  - Archived Media\n  - DASH\n  - HLS\n  - Playback\n  - Video\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/kinesisvideostreams/latest/dg/API_Operations_Amazon_Kinesis_Video_Streams_Archived_Media.html\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/kinesis-video-archived-media/2017-09-30/openapi.yaml\n\
  \  - type: JSONSchema\n    url: json-schema/amazon-kinesis-stream-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-kinesis-record-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-kinesis-context.jsonld\n- name: Amazon Kinesis Video Signaling Channels\n  description: The Amazon Kinesis Video Signaling Channels API facilitates peer-to-peer WebRTC communication by enabling applications to securely discover each other and exchange connection offers and\n    answers through signaling channels for real-time media streaming.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://docs.aws.amazon.com/kinesisvideostreams-webrtc-dg/latest/devguide/what-is-kvswebrtc.html\n  baseURL: https://kinesisvideo.amazonaws.com\n  tags:\n  - Real-Time\n  - Signaling\n  - Video\n  - WebRTC\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/kinesisvideostreams-webrtc-dg/latest/devguide/what-is-kvswebrtc.html\n  -\
  \ type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/kinesis-video-signaling/2019-12-04/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-kinesis-stream-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-kinesis-record-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-kinesis-context.jsonld\ncommon:\n- type: Features\n  url: https://aws.amazon.com/kinesis/features/\n- type: FAQ\n  url: https://aws.amazon.com/kinesis/data-streams/faqs/\n- type: Blog\n  url: https://aws.amazon.com/blogs/big-data/category/analytics/amazon-kinesis/\n- type: Customers\n  url: https://aws.amazon.com/kinesis/customers/\n- type: Resources\n  url: https://aws.amazon.com/kinesis/resources/\n- type: Documentation\n  url: https://docs.aws.amazon.com/kinesis/\n- type: SDK & Tools\n  url: https://aws.amazon.com/tools/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Console\n  url: https://console.aws.amazon.com/kinesis/\n- type: Firehose Blog\n\
  \  url: https://aws.amazon.com/blogs/big-data/category/analytics/amazon-kinesis/kinesis-data-firehose/\n- type: Video Streams FAQs\n  url: https://aws.amazon.com/kinesis/video-streams/faqs/\n- type: Firehose FAQs\n  url: https://aws.amazon.com/firehose/faqs/\n- type: Managed Flink FAQs\n  url: https://aws.amazon.com/managed-service-apache-flink/faqs/\n- type: Video Streams Resources\n  url: https://aws.amazon.com/kinesis/video-streams/resources/\n- type: Portal\n  url: https://aws.amazon.com/kinesis/\n- type: Pricing\n  url: https://aws.amazon.com/kinesis/data-streams/pricing/\n- type: Authentication\n  url: https://docs.aws.amazon.com/streams/latest/dev/tutorial-stock-data-kplkcl-iam.html\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: GitHubOrganization\n \
  \ url: https://github.com/aws\n- type: Stack Overflow\n  url: https://stackoverflow.com/questions/tagged/amazon-kinesis\n- type: UseCases\n  data:\n  - name: Real-Time Analytics\n    description: Analyze streaming data for operational metrics and business intelligence.\n  - name: Event-Driven Architectures\n    description: Build event-driven microservices that react to real-time data streams.\n  - name: Machine Learning\n    description: Feed real-time data into ML models for online training and inference.\n- type: Integrations\n  data:\n  - name: AWS Lambda\n    description: Trigger Lambda functions to process records from Kinesis streams.\n  - name: Amazon Kinesis Data Firehose\n    description: Use Kinesis streams as source for Firehose delivery.\n  - name: Amazon DynamoDB\n    description: Store processed streaming records in DynamoDB.\n- type: SpectralRules\n  url: rules/amazon-kinesis-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-kinesis-workflow.yaml\n\
  - type: Vocabulary\n  url: vocabulary/amazon-kinesis-vocabulary.yaml\nmaintainers:\n- FN: Kin Lane\n  url: http://apievangelist.com\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-kinesis/refs/heads/main/apis.yml
tags:
- Analytics
- Big Data
- Data Processing
- Real-Time
- Streaming
url: https://raw.githubusercontent.com/api-search/amazon-web-services/main/apis/kinesis.yml
use_cases:
- description: Analyze streaming data for operational metrics and business intelligence.
  name: Real-Time Analytics
- description: Build event-driven microservices that react to real-time data streams.
  name: Event-Driven Architectures
- description: Feed real-time data into ML models for online training and inference.
  name: Machine Learning
---
