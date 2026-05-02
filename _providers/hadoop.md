---
api_count: 4
api_specs:
- filename: hadoop-openapi.yml
  format: yaml
  label: HDFS REST API (WebHDFS)
  slug: hdfs-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/openapi/hadoop-openapi.yml
- filename: hadoop-openapi.yml
  format: yaml
  label: YARN REST API
  slug: yarn-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/openapi/hadoop-openapi.yml
apis:
- description: RESTful API for Hadoop Distributed File System operations including file operations, directory operations, and file status queries.
  name: HDFS REST API (WebHDFS)
  slug: hdfs-rest-api
- description: RESTful API for Yet Another Resource Negotiator (YARN) for cluster resource management, application submission, and monitoring.
  name: YARN REST API
  slug: yarn-rest-api
- description: REST API for accessing MapReduce job history and statistics.
  name: MapReduce History Server REST API
  slug: mapreduce-history-server-api
- description: HTTP REST API gateway supporting both webhdfs and httpfs operations for HDFS access.
  name: HttpFS REST API
  slug: httpfs-rest-api
common:
- title: ''
  type: Website
  url: https://hadoop.apache.org/
- title: ''
  type: Documentation
  url: https://hadoop.apache.org/docs/stable/
- title: ''
  type: Getting Started
  url: https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-common/SingleCluster.html
- title: ''
  type: GitHub Organization
  url: https://github.com/apache/hadoop
- title: ''
  type: Community
  url: https://hadoop.apache.org/mailing_lists.html
- title: ''
  type: Change Log
  url: https://hadoop.apache.org/releases.html
- title: ''
  type: Terms of Service
  url: https://www.apache.org/licenses/LICENSE-2.0
created: '2024-01-15'
description: Apache Hadoop is an open-source framework for distributed storage and processing of large datasets across clusters of computers using simple programming models. It includes HDFS for distributed storage, YARN for resource management, and MapReduce for parallel data processing.
features: []
image: https://hadoop.apache.org/hadoop-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Apache Hadoop
skills: []
slug: hadoop
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: hadoop\nname: Apache Hadoop\ndescription: >-\n  Apache Hadoop is an open-source framework for distributed storage and\n  processing of large datasets across clusters of computers using simple\n  programming models. It includes HDFS for distributed storage, YARN for\n  resource management, and MapReduce for parallel data processing.\nimage: https://hadoop.apache.org/hadoop-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/apis.yml\ntype: Index\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Big Data\n  - Data Processing\n  - Distributed Computing\n  - HDFS\n  - MapReduce\n  - Open Source\napis:\n  - aid: hadoop:hdfs-rest-api\n    name: HDFS REST API (WebHDFS)\n    description: >-\n      RESTful API for Hadoop Distributed File System operations including\n      file operations, directory operations, and file status queries.\n    humanURL: https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/WebHDFS.html\n\
  \    baseURL: http://host:port/webhdfs/v1/\n    tags:\n      - File System\n      - REST API\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/WebHDFS.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/openapi/hadoop-openapi.yml\n      - type: Rules\n        url: https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/hadoop-rules.yml\n  - aid: hadoop:yarn-rest-api\n    name: YARN REST API\n    description: >-\n      RESTful API for Yet Another Resource Negotiator (YARN) for cluster\n      resource management, application submission, and monitoring.\n    humanURL: https://hadoop.apache.org/docs/stable/hadoop-yarn/hadoop-yarn-site/ResourceManagerRest.html\n    baseURL: http://rm-http-address:port/ws/v1/\n    tags:\n      - Cluster Management\n      - Resource Management\n      - REST API\n    properties:\n      -\
  \ type: Documentation\n        url: https://hadoop.apache.org/docs/stable/hadoop-yarn/hadoop-yarn-site/ResourceManagerRest.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/openapi/hadoop-openapi.yml\n      - type: Rules\n        url: https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/hadoop-rules.yml\n  - aid: hadoop:mapreduce-history-server-api\n    name: MapReduce History Server REST API\n    description: REST API for accessing MapReduce job history and statistics.\n    humanURL: https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapredAppMasterRest.html\n    tags:\n      - Job History\n      - MapReduce\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapredAppMasterRest.html\n  - aid: hadoop:httpfs-rest-api\n    name: HttpFS REST API\n    description:\
  \ >-\n      HTTP REST API gateway supporting both webhdfs and httpfs operations\n      for HDFS access.\n    humanURL: https://hadoop.apache.org/docs/stable/hadoop-hdfs-httpfs/index.html\n    baseURL: http://httpfs-host:port/webhdfs/v1/\n    tags:\n      - File System\n      - Gateway\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://hadoop.apache.org/docs/stable/hadoop-hdfs-httpfs/index.html\ncommon:\n  - type: Website\n    url: https://hadoop.apache.org/\n  - type: Documentation\n    url: https://hadoop.apache.org/docs/stable/\n  - type: Getting Started\n    url: https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-common/SingleCluster.html\n  - type: GitHub Organization\n    url: https://github.com/apache/hadoop\n  - type: Community\n    url: https://hadoop.apache.org/mailing_lists.html\n  - type: Change Log\n    url: https://hadoop.apache.org/releases.html\n  - type: Terms of Service\n    url: https://www.apache.org/licenses/LICENSE-2.0\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/apis.yml
tags:
- Big Data
- Data Processing
- Distributed Computing
- HDFS
- MapReduce
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/hadoop/refs/heads/main/apis.yml
use_cases: []
---
