---
api_count: 1
api_specs:
- filename: influxdb-openapi.yml
  format: yaml
  label: InfluxDB Cloud API
  slug: influxdb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/influxdb/refs/heads/main/openapi/influxdb-openapi.yml
apis:
- description: InfluxDB Cloud v2 API for managing buckets, organizations, tasks, authorizations, dashboards, and writing and querying time series data. The API exposes the full surface of the InfluxDB Cloud platform
  name: InfluxDB Cloud API
  slug: influxdb
common:
- title: ''
  type: Website
  url: https://www.influxdata.com/
- title: ''
  type: Documentation
  url: https://docs.influxdata.com/
- title: ''
  type: Getting Started
  url: https://docs.influxdata.com/influxdb/cloud/api/v2/#tag/Quick-start
- title: ''
  type: Pricing
  url: https://www.influxdata.com/influxdb-pricing/
- title: ''
  type: Use Cases
  url: https://www.influxdata.com/solutions/
- title: ''
  type: Resources
  url: https://www.influxdata.com/_resources/?pg=1
- title: ''
  type: Webinars
  url: https://www.influxdata.com/_resources/?pg=1&ct=webinar
- title: ''
  type: White Papers
  url: https://www.influxdata.com/_resources/?pg=1&ct=tech_paper
- title: ''
  type: Video
  url: https://www.influxdata.com/_resources/?pg=1&ct=video
- title: ''
  type: Case Studies
  url: https://www.influxdata.com/_resources/?pg=1&ct=case_study
- title: ''
  type: Events
  url: https://www.influxdata.com/events/
- title: ''
  type: Glossary
  url: https://www.influxdata.com/glossary/
- title: ''
  type: Issues
  url: https://github.com/influxdata/influxdb/issues/new/choose/
- title: ''
  type: Support
  url: https://support.influxdata.com/
- title: ''
  type: GitHub
  url: https://github.com/influxdata/influxdb
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/influxdb/
created: '2024-09-25'
description: InfluxData is the company building InfluxDB, the open source time series database used by more than a million developers around the world. Their mission is to help developers build intelligent, real-time systems with their time series data, with offerings spanning open source InfluxDB Core and Enterprise, InfluxDB Cloud Serverless and Dedicated, and Telegraf for data collection.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: InfluxDB
skills: []
slug: influxdb
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: influxdb\nname: InfluxDB\ndescription: >-\n  InfluxData is the company building InfluxDB, the open source time series\n  database used by more than a million developers around the world. Their\n  mission is to help developers build intelligent, real-time systems with\n  their time series data, with offerings spanning open source InfluxDB Core\n  and Enterprise, InfluxDB Cloud Serverless and Dedicated, and Telegraf for\n  data collection.\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/influxdb/refs/heads/main/apis.yml\ncreated: '2024-09-25'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\nposition: Consuming\naccess: 3rd-Party\ntags:\n  - Database\n  - Time Series\n  - Real-Time\n  - Analytics\napis:\n  - aid: influxdb:influxdb\n    name: InfluxDB Cloud API\n    description: >-\n      InfluxDB Cloud v2 API for managing buckets, organizations, tasks,\n  \
  \    authorizations, dashboards, and writing and querying time series data.\n      The API exposes the full surface of the InfluxDB Cloud platform including\n      data ingestion, Flux query execution, task scheduling, alerting, and\n      access control.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.influxdata.com/\n    baseURL: https://cloud2.influxdata.com/api/v2\n    tags:\n      - Database\n      - Time Series\n      - Real-Time\n      - Cloud\n    properties:\n      - type: Documentation\n        url: https://docs.influxdata.com/influxdb/cloud/api/v2/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/influxdb/refs/heads/main/openapi/influxdb-openapi.yml\n      - type: Authentication\n        url: https://docs.influxdata.com/influxdb/cloud/api/v2/#tag/Authentication\n      - type: Getting Started\n        url: https://docs.influxdata.com/influxdb/cloud/api/v2/#tag/Quick-start\n\
  \      - type: Pagination\n        url: https://docs.influxdata.com/influxdb/cloud/api/v2/#tag/Pagination\n      - type: Headers\n        url: https://docs.influxdata.com/influxdb/cloud/api/v2/#tag/Headers\n      - type: Source\n        url: https://github.com/influxdata/openapi\n    contact:\n      - FN: InfluxData Support\n        email: support@influxdata.com\n        url: https://support.influxdata.com/\ncommon:\n  - type: Website\n    url: https://www.influxdata.com/\n  - type: Documentation\n    url: https://docs.influxdata.com/\n  - type: Getting Started\n    url: https://docs.influxdata.com/influxdb/cloud/api/v2/#tag/Quick-start\n  - type: Pricing\n    url: https://www.influxdata.com/influxdb-pricing/\n  - type: Use Cases\n    url: https://www.influxdata.com/solutions/\n  - type: Resources\n    url: https://www.influxdata.com/_resources/?pg=1\n  - type: Webinars\n    url: https://www.influxdata.com/_resources/?pg=1&ct=webinar\n  - type: White Papers\n    url: https://www.influxdata.com/_resources/?pg=1&ct=tech_paper\n\
  \  - type: Video\n    url: https://www.influxdata.com/_resources/?pg=1&ct=video\n  - type: Case Studies\n    url: https://www.influxdata.com/_resources/?pg=1&ct=case_study\n  - type: Events\n    url: https://www.influxdata.com/events/\n  - type: Glossary\n    url: https://www.influxdata.com/glossary/\n  - type: Integrations\n    url: https://www.influxdata.com/products/integrations/\n  - type: Issues\n    url: https://github.com/influxdata/influxdb/issues/new/choose/\n  - type: Support\n    url: https://support.influxdata.com/\n  - type: GitHub\n    url: https://github.com/influxdata/influxdb\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/influxdb/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/influxdb/refs/heads/main/apis.yml
tags:
- Database
- Time Series
- Real-Time
- Analytics
url: https://raw.githubusercontent.com/api-evangelist/influxdb/refs/heads/main/apis.yml
use_cases: []
---
