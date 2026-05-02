---
api_count: 5
api_specs:
- filename: amazon-kinesis-data-streams-openapi-original.yml
  format: yaml
  label: Amazon Kinesis Data Streams API
  slug: data-streams-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kinesis/refs/heads/main/openapi/amazon-kinesis-data-streams-openapi-original.yml
- filename: amazon-data-firehose-openapi-original.yml
  format: yaml
  label: Amazon Data Firehose API
  slug: data-firehose-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kinesis/refs/heads/main/openapi/amazon-data-firehose-openapi-original.yml
- filename: amazon-kinesis-data-analytics-openapi-original.yml
  format: yaml
  label: Amazon Kinesis Data Analytics API
  slug: data-analytics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kinesis/refs/heads/main/openapi/amazon-kinesis-data-analytics-openapi-original.yml
- filename: amazon-kinesis-video-streams-openapi-original.yml
  format: yaml
  label: Amazon Kinesis Video Streams API
  slug: video-streams-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kinesis/refs/heads/main/openapi/amazon-kinesis-video-streams-openapi-original.yml
apis:
- description: Amazon Kinesis Data Streams is a scalable and durable real-time data streaming service that can continuously capture gigabytes of data per second from hundreds of thousands of sources. The API support
  name: Amazon Kinesis Data Streams API
  slug: data-streams-api
- description: Amazon Data Firehose (formerly Amazon Kinesis Data Firehose) is the easiest way to reliably load streaming data into data lakes, data stores, and analytics services. Firehose can capture, transform wi
  name: Amazon Data Firehose API
  slug: data-firehose-api
- description: Amazon Kinesis Data Analytics is a managed service for analyzing streaming data using SQL or Apache Flink. The API enables creation and management of streaming applications, input and output stream co
  name: Amazon Kinesis Data Analytics API
  slug: data-analytics-api
- description: 'Amazon Managed Service for Apache Flink (formerly Amazon Kinesis Data Analytics for Apache Flink) is a fully managed service for processing and analyzing streaming data using Apache Flink. Developers '
  name: Amazon Managed Service for Apache Flink API
  slug: managed-flink-api
- description: Amazon Kinesis Video Streams makes it easy to securely stream video, audio, and time-encoded data from connected devices to AWS for analytics, machine learning, playback, and other processing. The API
  name: Amazon Kinesis Video Streams API
  slug: video-streams-api
common:
- title: ''
  type: Website
  url: https://aws.amazon.com/kinesis/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/kinesis/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/big-data/category/analytics/amazon-kinesis/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/kinesis/
- title: ''
  type: SDKs
  url: https://aws.amazon.com/tools/
- title: ''
  type: StatusPage
  url: https://status.aws.amazon.com/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: SLA
  url: https://aws.amazon.com/kinesis/sla/
- title: ''
  type: GettingStarted
  url: https://aws.amazon.com/kinesis/getting-started/
- title: ''
  type: Legal
  url: https://aws.amazon.com/legal/service-level-agreements/
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
created: '2024-01-01'
description: Amazon Kinesis is a family of fully managed AWS services for collecting, processing, and analyzing real-time streaming data. The family includes Kinesis Data Streams for scalable record ingestion, Amazon Data Firehose (formerly Kinesis Data Firehose) for delivery to data lakes and analytics destinations, Amazon Managed Service for Apache Flink (formerly Kinesis Data Analytics) for stateful stream processing, and Kinesis Video Streams for ingest and playback of media from connected devices.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: AWS Kinesis
skills: []
slug: kinesis
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kinesis\nname: AWS Kinesis\ndescription: >-\n  Amazon Kinesis is a family of fully managed AWS services for collecting,\n  processing, and analyzing real-time streaming data. The family includes\n  Kinesis Data Streams for scalable record ingestion, Amazon Data Firehose\n  (formerly Kinesis Data Firehose) for delivery to data lakes and analytics\n  destinations, Amazon Managed Service for Apache Flink (formerly Kinesis\n  Data Analytics) for stateful stream processing, and Kinesis Video Streams\n  for ingest and playback of media from connected devices.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Apache Flink\n  - AWS\n  - Big Data\n  - Data Processing\n  - Real-Time\n  - Streaming\n  - Video\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/kinesis/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: kinesis:data-streams-api\n\
  \    name: Amazon Kinesis Data Streams API\n    description: >-\n      Amazon Kinesis Data Streams is a scalable and durable real-time data\n      streaming service that can continuously capture gigabytes of data per\n      second from hundreds of thousands of sources. The API supports stream\n      creation and lifecycle management, record put and get operations,\n      shard discovery and resharding, enhanced fan-out consumers, and stream\n      consumer registration for downstream processing.\n    humanURL: https://aws.amazon.com/kinesis/data-streams/\n    baseURL: https://kinesis.{region}.amazonaws.com\n    tags:\n      - Data Streams\n      - Ingestion\n      - Real-Time\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/kinesis/latest/APIReference/\n      - type: OpenAPI\n        url: openapi/amazon-kinesis-data-streams-openapi-original.yml\n      - type: Pricing\n        url: https://aws.amazon.com/kinesis/data-streams/pricing/\n\
  \      - type: GettingStarted\n        url: https://aws.amazon.com/kinesis/data-streams/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/kinesis/data-streams/faqs/\n      - type: DeveloperGuide\n        url: https://docs.aws.amazon.com/streams/latest/dev/introduction.html\n      - type: Security\n        url: https://docs.aws.amazon.com/streams/latest/dev/security.html\n      - type: Customers\n        url: https://aws.amazon.com/kinesis/data-streams/customers/\n      - type: Integrations\n        url: https://aws.amazon.com/kinesis/data-streams/integrations/\n    contact:\n      - FN: AWS Support\n        url: https://aws.amazon.com/contact-us/\n  - aid: kinesis:data-firehose-api\n    name: Amazon Data Firehose API\n    description: >-\n      Amazon Data Firehose (formerly Amazon Kinesis Data Firehose) is the\n      easiest way to reliably load streaming data into data lakes, data\n      stores, and analytics services. Firehose can capture, transform with\n   \
  \   Lambda or built-in conversions, and deliver streaming data to Amazon\n      S3, Amazon Redshift, Amazon OpenSearch Service, Splunk, and supported\n      partner destinations with automatic scaling and retry handling.\n    humanURL: https://aws.amazon.com/firehose/\n    baseURL: https://firehose.{region}.amazonaws.com\n    tags:\n      - Data Delivery\n      - ETL\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/firehose/latest/APIReference/\n      - type: OpenAPI\n        url: openapi/amazon-data-firehose-openapi-original.yml\n      - type: Pricing\n        url: https://aws.amazon.com/kinesis/data-firehose/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/kinesis/data-firehose/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/kinesis/data-firehose/faqs/\n      - type: DeveloperGuide\n        url: https://docs.aws.amazon.com/firehose/latest/dev/what-is-this-service.html\n    contact:\n\
  \      - FN: AWS Support\n        url: https://aws.amazon.com/contact-us/\n  - aid: kinesis:data-analytics-api\n    name: Amazon Kinesis Data Analytics API\n    description: >-\n      Amazon Kinesis Data Analytics is a managed service for analyzing\n      streaming data using SQL or Apache Flink. The API enables creation\n      and management of streaming applications, input and output stream\n      configuration, application code deployment, and runtime monitoring,\n      enabling near real-time insights and event-driven actions on\n      continuously arriving data.\n    humanURL: https://aws.amazon.com/kinesis/data-analytics/\n    baseURL: https://kinesisanalytics.{region}.amazonaws.com\n    tags:\n      - Analytics\n      - Apache Flink\n      - SQL\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/kinesisanalytics/latest/apiv2/\n      - type: OpenAPI\n        url: openapi/amazon-kinesis-data-analytics-openapi-original.yml\n \
  \     - type: Pricing\n        url: https://aws.amazon.com/kinesis/data-analytics/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/kinesis/data-analytics/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/kinesis/data-analytics/faqs/\n      - type: DeveloperGuide\n        url: https://docs.aws.amazon.com/kinesisanalytics/latest/dev/how-it-works.html\n      - type: Security\n        url: https://docs.aws.amazon.com/kinesisanalytics/latest/dev/security.html\n    contact:\n      - FN: AWS Support\n        url: https://aws.amazon.com/contact-us/\n  - aid: kinesis:managed-flink-api\n    name: Amazon Managed Service for Apache Flink API\n    description: >-\n      Amazon Managed Service for Apache Flink (formerly Amazon Kinesis Data\n      Analytics for Apache Flink) is a fully managed service for processing\n      and analyzing streaming data using Apache Flink. Developers build\n      streaming applications in Java, Python, SQL, or Scala, and\
  \ the\n      service handles infrastructure provisioning, scaling, state\n      management, and high availability for stateful stream processing.\n    humanURL: https://aws.amazon.com/managed-service-apache-flink/\n    baseURL: https://kinesisanalytics.{region}.amazonaws.com\n    tags:\n      - Analytics\n      - Apache Flink\n      - Real-Time\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/managed-flink/latest/apiv2/Welcome.html\n      - type: DeveloperGuide\n        url: https://docs.aws.amazon.com/managed-flink/latest/java/getting-started.html\n      - type: Pricing\n        url: https://aws.amazon.com/managed-service-apache-flink/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/managed-service-apache-flink/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/managed-service-apache-flink/faqs/\n    contact:\n      - FN: AWS Support\n        url: https://aws.amazon.com/contact-us/\n\
  \  - aid: kinesis:video-streams-api\n    name: Amazon Kinesis Video Streams API\n    description: >-\n      Amazon Kinesis Video Streams makes it easy to securely stream video,\n      audio, and time-encoded data from connected devices to AWS for\n      analytics, machine learning, playback, and other processing. The API\n      supports stream lifecycle management, media ingest and retrieval, HLS\n      and DASH playback URL generation, signaling for WebRTC peer\n      connections, and integration with AWS Rekognition for video analysis.\n    humanURL: https://aws.amazon.com/kinesis/video-streams/\n    baseURL: https://kinesisvideo.{region}.amazonaws.com\n    tags:\n      - IoT\n      - Machine Learning\n      - Streaming\n      - Video\n      - WebRTC\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/kinesisvideostreams/latest/dg/API_Reference.html\n      - type: OpenAPI\n        url: openapi/amazon-kinesis-video-streams-openapi-original.yml\n   \
  \   - type: Pricing\n        url: https://aws.amazon.com/kinesis/video-streams/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/kinesis/video-streams/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/kinesis/video-streams/faqs/\n      - type: DeveloperGuide\n        url: https://docs.aws.amazon.com/kinesisvideostreams/latest/dg/what-is-kinesis-video.html\n      - type: Security\n        url: https://docs.aws.amazon.com/kinesisvideostreams/latest/dg/security.html\n      - type: Customers\n        url: https://aws.amazon.com/kinesis/video-streams/customers/\n      - type: Features\n        url: https://aws.amazon.com/kinesis/video-streams/features/\n      - type: Resources\n        url: https://aws.amazon.com/kinesis/video-streams/resources/\n      - type: WebRTCGuide\n        url: https://docs.aws.amazon.com/kinesisvideostreams-webrtc-dg/latest/devguide/what-is-kvswebrtc.html\n    contact:\n      - FN: AWS Support\n        url: https://aws.amazon.com/contact-us/\n\
  common:\n  - type: Website\n    url: https://aws.amazon.com/kinesis/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/kinesis/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/big-data/category/analytics/amazon-kinesis/\n  - type: Console\n    url: https://console.aws.amazon.com/kinesis/\n  - type: SDKs\n    url: https://aws.amazon.com/tools/\n  - type: StatusPage\n    url: https://status.aws.amazon.com/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: SLA\n    url: https://aws.amazon.com/kinesis/sla/\n  - type: GettingStarted\n    url: https://aws.amazon.com/kinesis/getting-started/\n  - type: Legal\n    url: https://aws.amazon.com/legal/service-level-agreements/\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kinesis/refs/heads/main/apis.yml
tags:
- Analytics
- Apache Flink
- Big Data
- Data Processing
- Real-Time
- Streaming
- Video
url: https://raw.githubusercontent.com/api-evangelist/kinesis/refs/heads/main/apis.yml
use_cases: []
---
