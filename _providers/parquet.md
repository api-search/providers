---
api_count: 6
apis:
- description: The core specification for the Parquet columnar storage format.
  name: Apache Parquet Format Specification
  slug: format-specification
- description: Python library for reading and writing Parquet files, distributed as part of Apache Arrow.
  name: PyArrow Parquet Python API
  slug: pyarrow
- description: Java implementation for reading and writing Parquet files.
  name: Parquet Java API
  slug: java
- description: C++ implementation as part of Apache Arrow.
  name: Parquet C++ API
  slug: cpp
- description: R package for reading and writing Parquet files via Apache Arrow.
  name: Parquet R API
  slug: r
- description: Alternative Python implementation for Parquet files.
  name: FastParquet Python API
  slug: fastparquet
common:
- title: ''
  type: Mailing Lists
  url: https://parquet.apache.org/community/
- title: ''
  type: Issue Tracker
  url: https://issues.apache.org/jira/projects/PARQUET
- title: ''
  type: Blog
  url: https://parquet.apache.org/blog/
- title: ''
  type: License
  url: https://github.com/apache/parquet-format/blob/master/LICENSE
created: '2024-01-01'
description: APIs and tools for working with Apache Parquet, the open source columnar storage format for efficient analytics workloads. This index covers the format specification along with the major language implementations.
features: []
image: https://parquet.apache.org/assets/img/parquet-logo.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Apache Parquet
skills: []
slug: parquet
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: parquet\nname: Apache Parquet\ndescription: >-\n  APIs and tools for working with Apache Parquet, the open source columnar\n  storage format for efficient analytics workloads. This index covers the\n  format specification along with the major language implementations.\ntype: Index\nposition: Producer\naccess: Open Source\nimage: https://parquet.apache.org/assets/img/parquet-logo.png\ntags:\n  - Apache\n  - Big Data\n  - Columnar Storage\n  - Data Format\n  - Parquet\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/parquet/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: parquet:format-specification\n    name: Apache Parquet Format Specification\n    description: >-\n      The core specification for the Parquet columnar storage format.\n    image: https://parquet.apache.org/assets/img/parquet-logo.png\n    humanURL: https://parquet.apache.org/docs/\n    baseURL: https://github.com/apache/parquet-format\n\
  \    tags:\n      - Format\n      - Schema\n      - Specification\n    properties:\n      - type: Documentation\n        url: https://parquet.apache.org/docs/file-format/\n      - type: GitHub Repository\n        url: https://github.com/apache/parquet-format\n      - type: Thrift Definition\n        url: https://github.com/apache/parquet-format/blob/master/src/main/thrift/parquet.thrift\n  - aid: parquet:pyarrow\n    name: PyArrow Parquet Python API\n    description: >-\n      Python library for reading and writing Parquet files, distributed as\n      part of Apache Arrow.\n    humanURL: https://arrow.apache.org/docs/python/parquet.html\n    baseURL: https://pypi.org/project/pyarrow/\n    tags:\n      - Library\n      - Python\n      - Read\n      - Write\n    properties:\n      - type: Documentation\n        url: https://arrow.apache.org/docs/python/parquet.html\n      - type: PyPI Package\n        url: https://pypi.org/project/pyarrow/\n      - type: GitHub Repository\n        url: https://github.com/apache/arrow\n\
  \      - type: API Reference\n        url: https://arrow.apache.org/docs/python/api/formats.html\n  - aid: parquet:java\n    name: Parquet Java API\n    description: >-\n      Java implementation for reading and writing Parquet files.\n    humanURL: https://github.com/apache/parquet-java\n    baseURL: https://search.maven.org/search?q=g:org.apache.parquet\n    tags:\n      - Hadoop\n      - Java\n      - Library\n    properties:\n      - type: Documentation\n        url: https://github.com/apache/parquet-java/blob/master/README.md\n      - type: GitHub Repository\n        url: https://github.com/apache/parquet-java\n      - type: Maven Repository\n        url: https://search.maven.org/search?q=g:org.apache.parquet\n      - type: JavaDoc\n        url: https://www.javadoc.io/doc/org.apache.parquet/parquet-hadoop\n  - aid: parquet:cpp\n    name: Parquet C++ API\n    description: >-\n      C++ implementation as part of Apache Arrow.\n    humanURL: https://arrow.apache.org/docs/cpp/parquet.html\n\
  \    baseURL: https://github.com/apache/arrow/tree/main/cpp\n    tags:\n      - Cpp\n      - Library\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://arrow.apache.org/docs/cpp/parquet.html\n      - type: GitHub Repository\n        url: https://github.com/apache/arrow\n      - type: API Reference\n        url: https://arrow.apache.org/docs/cpp/api/parquet.html\n  - aid: parquet:r\n    name: Parquet R API\n    description: >-\n      R package for reading and writing Parquet files via Apache Arrow.\n    humanURL: https://arrow.apache.org/docs/r/\n    baseURL: https://cran.r-project.org/package=arrow\n    tags:\n      - Data Analysis\n      - Library\n      - R\n    properties:\n      - type: Documentation\n        url: https://arrow.apache.org/docs/r/articles/parquet.html\n      - type: CRAN Package\n        url: https://cran.r-project.org/package=arrow\n      - type: GitHub Repository\n        url: https://github.com/apache/arrow/tree/main/r\n  - aid:\
  \ parquet:fastparquet\n    name: FastParquet Python API\n    description: >-\n      Alternative Python implementation for Parquet files.\n    humanURL: https://fastparquet.readthedocs.io/\n    baseURL: https://pypi.org/project/fastparquet/\n    tags:\n      - Alternative\n      - Library\n      - Python\n    properties:\n      - type: Documentation\n        url: https://fastparquet.readthedocs.io/en/latest/\n      - type: PyPI Package\n        url: https://pypi.org/project/fastparquet/\n      - type: GitHub Repository\n        url: https://github.com/dask/fastparquet\nmaintainers:\n  - FN: Apache Software Foundation\n    email: dev@parquet.apache.org\n    url: https://parquet.apache.org\ncommon:\n  - type: Mailing Lists\n    url: https://parquet.apache.org/community/\n  - type: Issue Tracker\n    url: https://issues.apache.org/jira/projects/PARQUET\n  - type: Blog\n    url: https://parquet.apache.org/blog/\n  - type: License\n    url: https://github.com/apache/parquet-format/blob/master/LICENSE\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/parquet/refs/heads/main/apis.yml
tags:
- Apache
- Big Data
- Columnar Storage
- Data Format
- Parquet
url: https://raw.githubusercontent.com/api-evangelist/parquet/refs/heads/main/apis.yml
use_cases: []
---
