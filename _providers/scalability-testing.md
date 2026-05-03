---
api_count: 6
api_specs:
- filename: loadtestservice.json
  format: json
  label: Azure Load Testing API
  slug: azure-load-testing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/loadtestservice/resource-manager/Microsoft.LoadTestService/stable/2022-12-01/loadtestservice.json
apis:
- description: The Grafana k6 Cloud REST API provides programmatic access to run, manage, and retrieve results for load tests executed on the k6 cloud platform. k6 is an open-source load testing tool using JavaScrip
  name: Grafana k6 Cloud API
  slug: k6-cloud-api
- description: The BlazeMeter REST API provides access to the BlazeMeter cloud load testing platform. BlazeMeter supports JMeter, Gatling, Locust, Selenium, and custom test plans. The API enables test execution, mon
  name: BlazeMeter API
  slug: blazemeter-api
- description: Azure Load Testing is a fully managed cloud service that enables running high-scale load tests. Based on Apache JMeter, it provides a REST API for creating, running, and analyzing load tests integrate
  name: Azure Load Testing API
  slug: azure-load-testing
- description: Apache JMeter is the most widely-used open-source load testing tool. It supports HTTP, HTTPS, FTP, JDBC, LDAP, SOAP, REST, and more protocols. JMeter provides a REST API in its distributed mode and in
  name: Apache JMeter
  slug: jmeter
- description: Locust is a scalable, distributed open-source load testing framework written in Python. Test scenarios are defined in pure Python code. Locust exposes a REST API and web UI for controlling test execut
  name: Locust Load Testing
  slug: locust
- description: Gatling is an open-source load testing framework built on Akka and Netty, providing high performance with a Scala/Java/Kotlin DSL for defining test scenarios. The Gatling Enterprise cloud platform pro
  name: Gatling Load Testing
  slug: gatling
common:
- title: ''
  type: Website
  url: https://k6.io/
- title: ''
  type: GitHub
  url: https://github.com/grafana/k6
- title: ''
  type: GitHub
  url: https://github.com/apache/jmeter
- title: ''
  type: GitHub
  url: https://github.com/locustio/locust
- title: ''
  type: GitHub
  url: https://github.com/gatling/gatling
- title: ''
  type: Documentation
  url: https://grafana.com/docs/grafana-cloud/testing/k6/
- title: ''
  type: Vocabulary
  url: vocabulary/scalability-testing-vocabulary.yml
- title: ''
  type: JSONLD
  url: json-ld/scalability-testing-context.jsonld
created: '2024-01-15'
description: A collection of tools, frameworks, APIs, and datasets for performing scalability and load testing of web services, APIs, and distributed systems. Scalability testing evaluates how a system performs as load increases, identifying bottlenecks, capacity limits, and performance degradation points. Key tools include Apache JMeter, k6, Gatling, Locust, and cloud-based platforms like AWS Load Testing, Azure Load Testing, and BlazeMeter.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Scalability Testing Context
  property_count: 22
  slug: scalability-testing-context
layout: provider
modified: '2026-05-02'
name: Scalability Testing
skills: []
slug: scalability-testing
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scalability-testing\nname: Scalability Testing\ndescription: >-\n  A collection of tools, frameworks, APIs, and datasets for performing\n  scalability and load testing of web services, APIs, and distributed systems.\n  Scalability testing evaluates how a system performs as load increases,\n  identifying bottlenecks, capacity limits, and performance degradation points.\n  Key tools include Apache JMeter, k6, Gatling, Locust, and cloud-based platforms\n  like AWS Load Testing, Azure Load Testing, and BlazeMeter.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Testing\n  - Load Testing\n  - Performance Testing\n  - Scalability\n  - Stress Testing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/scalability-testing/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: scalability-testing:k6-cloud-api\n    name: Grafana k6 Cloud API\n \
  \   description: >-\n      The Grafana k6 Cloud REST API provides programmatic access to run, manage,\n      and retrieve results for load tests executed on the k6 cloud platform.\n      k6 is an open-source load testing tool using JavaScript/TypeScript test\n      scripts. The cloud platform adds distributed execution, real-time results,\n      and team collaboration features.\n    humanURL: https://grafana.com/docs/grafana-cloud/testing/k6/\n    baseURL: https://api.k6.io/v3\n    tags:\n      - k6\n      - Load Testing\n      - Performance Testing\n    properties:\n      - type: Documentation\n        url: https://grafana.com/docs/grafana-cloud/testing/k6/reference/rest-api/\n\n  - aid: scalability-testing:blazemeter-api\n    name: BlazeMeter API\n    description: >-\n      The BlazeMeter REST API provides access to the BlazeMeter cloud load\n      testing platform. BlazeMeter supports JMeter, Gatling, Locust, Selenium,\n      and custom test plans. The API enables test execution, monitoring,\n\
  \      result retrieval, and configuration management.\n    humanURL: https://guide.blazemeter.com/hc/en-us/categories/200698715-BlazeMeter-API\n    baseURL: https://a.blazemeter.com/api/v4\n    tags:\n      - BlazeMeter\n      - JMeter\n      - Load Testing\n    properties:\n      - type: Documentation\n        url: https://guide.blazemeter.com/hc/en-us/categories/200698715-BlazeMeter-API\n\n  - aid: scalability-testing:azure-load-testing\n    name: Azure Load Testing API\n    description: >-\n      Azure Load Testing is a fully managed cloud service that enables running\n      high-scale load tests. Based on Apache JMeter, it provides a REST API\n      for creating, running, and analyzing load tests integrated with Azure\n      DevOps and GitHub Actions CI/CD pipelines.\n    humanURL: https://learn.microsoft.com/en-us/azure/load-testing/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.LoadTestService\n \
  \   tags:\n      - Azure\n      - Cloud Load Testing\n      - JMeter\n      - Microsoft\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/load-testing/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/loadtestservice/resource-manager/Microsoft.LoadTestService/stable/2022-12-01/loadtestservice.json\n\n  - aid: scalability-testing:jmeter\n    name: Apache JMeter\n    description: >-\n      Apache JMeter is the most widely-used open-source load testing tool.\n      It supports HTTP, HTTPS, FTP, JDBC, LDAP, SOAP, REST, and more protocols.\n      JMeter provides a REST API in its distributed mode and integrates with\n      BlazeMeter, Azure Load Testing, and other cloud platforms for scaled\n      execution.\n    humanURL: https://jmeter.apache.org/\n    tags:\n      - Apache\n      - JMeter\n      - Load Testing\n      - Open Source\n    properties:\n      - type: Documentation\n\
  \        url: https://jmeter.apache.org/usermanual/index.html\n      - type: GitHub\n        url: https://github.com/apache/jmeter\n\n  - aid: scalability-testing:locust\n    name: Locust Load Testing\n    description: >-\n      Locust is a scalable, distributed open-source load testing framework\n      written in Python. Test scenarios are defined in pure Python code.\n      Locust exposes a REST API and web UI for controlling test execution,\n      viewing real-time metrics, and integrating with CI/CD pipelines.\n    humanURL: https://locust.io/\n    baseURL: http://localhost:8089\n    tags:\n      - Load Testing\n      - Locust\n      - Open Source\n      - Python\n    properties:\n      - type: Documentation\n        url: https://docs.locust.io/en/stable/\n      - type: GitHub\n        url: https://github.com/locustio/locust\n\n  - aid: scalability-testing:gatling\n    name: Gatling Load Testing\n    description: >-\n      Gatling is an open-source load testing framework built on Akka\
  \ and Netty,\n      providing high performance with a Scala/Java/Kotlin DSL for defining\n      test scenarios. The Gatling Enterprise cloud platform provides distributed\n      execution and advanced analytics APIs.\n    humanURL: https://gatling.io/\n    tags:\n      - Gatling\n      - Java\n      - Load Testing\n      - Open Source\n      - Scala\n    properties:\n      - type: Documentation\n        url: https://docs.gatling.io/\n      - type: GitHub\n        url: https://github.com/gatling/gatling\n\ncommon:\n  - type: Website\n    url: https://k6.io/\n  - type: GitHub\n    url: https://github.com/grafana/k6\n  - type: GitHub\n    url: https://github.com/apache/jmeter\n  - type: GitHub\n    url: https://github.com/locustio/locust\n  - type: GitHub\n    url: https://github.com/gatling/gatling\n  - type: Documentation\n    url: https://grafana.com/docs/grafana-cloud/testing/k6/\n  - type: Vocabulary\n    url: vocabulary/scalability-testing-vocabulary.yml\n  - type: JSONLD\n    url:\
  \ json-ld/scalability-testing-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scalability-testing/refs/heads/main/apis.yml
tags:
- API Testing
- Load Testing
- Performance Testing
- Scalability
- Stress Testing
url: https://raw.githubusercontent.com/api-evangelist/scalability-testing/refs/heads/main/apis.yml
use_cases: []
---
