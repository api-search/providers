---
api_count: 1
apis:
- description: Vegeta is an open source HTTP load testing tool and library written in Go for generating constant request rates. Supports targets from files or stdin, rate limiting (req/s), duration control, configur
  name: Vegeta Load Testing Tool
  slug: vegeta
common:
- title: ''
  type: Website
  url: https://github.com/tsenart/vegeta
- title: ''
  type: Documentation
  url: https://github.com/tsenart/vegeta#readme
- title: ''
  type: GitHub Organization
  url: https://github.com/tsenart
- title: ''
  type: GitHub Repository
  url: https://github.com/tsenart/vegeta
- title: Vegeta Vocabulary
  type: Vocabulary
  url: vocabulary/vegeta-vocabulary.yml
created: '2026-03-25'
description: Vegeta is an open source HTTP load testing tool and library written in Go for generating constant request rates to measure API performance and reliability under sustained load. Supports CLI and library usage with attack plans, rate limiting, duration control, and detailed result metrics including latency histograms and success rates.
features:
- description: Generates HTTP requests at a constant rate (requests per second) for a specified duration, simulating sustained load on API endpoints.
  name: Constant Rate Attack
- description: Supports text, JSON, and binary result output formats with encoding/decoding support for pipeline-based workflows.
  name: Multiple Output Formats
- description: Produces detailed latency histograms with configurable buckets for analyzing p50, p95, p99, and max latency distributions.
  name: Latency Histograms
- description: Accepts HTTP targets from files or stdin with support for custom headers, request bodies, and per-target configuration.
  name: Target Formats
- description: Configurable TLS settings including certificate pinning, insecure mode, and redirect following for testing secured endpoints.
  name: TLS and Redirects
- description: Go library (vegeta/lib) for programmatic integration of load testing into test suites, CI/CD pipelines, and monitoring tools.
  name: Library API
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-05-03'
name: Vegeta
skills: []
slug: vegeta
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vegeta\nname: Vegeta\ndescription: >-\n  Vegeta is an open source HTTP load testing tool and library written in Go for generating\n  constant request rates to measure API performance and reliability under sustained load.\n  Supports CLI and library usage with attack plans, rate limiting, duration control,\n  and detailed result metrics including latency histograms and success rates.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Go\n  - HTTP\n  - Load Testing\n  - Performance\n  - Testing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vegeta/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: vegeta:vegeta\n    name: Vegeta Load Testing Tool\n    description: >-\n      Vegeta is an open source HTTP load testing tool and library written in Go for\n      generating constant request rates. Supports targets from files or stdin, rate\n\
  \      limiting (req/s), duration control, configurable timeouts, TLS settings, and\n      multiple output formats (text, JSON, binary). Produces detailed result metrics\n      including latency histograms, success rates, status code distributions, and\n      throughput measurements.\n    humanURL: https://github.com/tsenart/vegeta\n    tags:\n      - Go\n      - HTTP\n      - Load Testing\n      - Performance\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://github.com/tsenart/vegeta#readme\n      - type: GitHub Repository\n        url: https://github.com/tsenart/vegeta\n      - type: JSONSchema\n        url: json-schema/vegeta-attack-schema.json\n        title: Attack Configuration Schema\n      - type: JSONSchema\n        url: json-schema/vegeta-result-schema.json\n        title: Result Schema\n      - type: JSONSchema\n        url: json-schema/vegeta-metrics-schema.json\n        title: Metrics Schema\n      - type: JSONStructure\n        url: json-structure/vegeta-attack-structure.json\n\
  \        title: Attack Configuration Structure\n      - type: JSONStructure\n        url: json-structure/vegeta-result-structure.json\n        title: Result Structure\n      - type: JSONStructure\n        url: json-structure/vegeta-metrics-structure.json\n        title: Metrics Structure\n      - type: Example\n        url: examples/vegeta-attack-example.json\n        title: Attack Configuration Example\n      - type: Example\n        url: examples/vegeta-result-example.json\n        title: Result Example\n      - type: Example\n        url: examples/vegeta-metrics-example.json\n        title: Metrics Example\n\ncommon:\n  - type: Website\n    url: https://github.com/tsenart/vegeta\n  - type: Documentation\n    url: https://github.com/tsenart/vegeta#readme\n  - type: GitHub Organization\n    url: https://github.com/tsenart\n  - type: GitHub Repository\n    url: https://github.com/tsenart/vegeta\n  - type: Vocabulary\n    url: vocabulary/vegeta-vocabulary.yml\n    title: Vegeta Vocabulary\n\
  \  - type: Features\n    data:\n      - name: Constant Rate Attack\n        description: >-\n          Generates HTTP requests at a constant rate (requests per second) for a\n          specified duration, simulating sustained load on API endpoints.\n      - name: Multiple Output Formats\n        description: >-\n          Supports text, JSON, and binary result output formats with encoding/decoding\n          support for pipeline-based workflows.\n      - name: Latency Histograms\n        description: >-\n          Produces detailed latency histograms with configurable buckets for analyzing\n          p50, p95, p99, and max latency distributions.\n      - name: Target Formats\n        description: >-\n          Accepts HTTP targets from files or stdin with support for custom headers,\n          request bodies, and per-target configuration.\n      - name: TLS and Redirects\n        description: >-\n          Configurable TLS settings including certificate pinning, insecure mode,\n      \
  \    and redirect following for testing secured endpoints.\n      - name: Library API\n        description: >-\n          Go library (vegeta/lib) for programmatic integration of load testing\n          into test suites, CI/CD pipelines, and monitoring tools.\n  - type: UseCases\n    data:\n      - name: API Performance Benchmarking\n        description: >-\n          Measure API throughput, latency percentiles, and success rates at various\n          request rates to establish performance baselines and SLA compliance.\n      - name: Load Testing in CI/CD\n        description: >-\n          Integrate vegeta as a library in Go test suites to run automated load tests\n          as part of continuous integration pipelines.\n      - name: Capacity Planning\n        description: >-\n          Determine maximum sustainable request rates before latency degradation\n          or error rates exceed acceptable thresholds for capacity planning.\n      - name: Regression Detection\n        description:\
  \ >-\n          Compare latency and throughput metrics across API versions to detect\n          performance regressions before deployment to production.\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vegeta/refs/heads/main/apis.yml
tags:
- Go
- HTTP
- Load Testing
- Performance
- Testing
url: https://raw.githubusercontent.com/api-evangelist/vegeta/refs/heads/main/apis.yml
use_cases:
- description: Measure API throughput, latency percentiles, and success rates at various request rates to establish performance baselines and SLA compliance.
  name: API Performance Benchmarking
- description: Integrate vegeta as a library in Go test suites to run automated load tests as part of continuous integration pipelines.
  name: Load Testing in CI/CD
- description: Determine maximum sustainable request rates before latency degradation or error rates exceed acceptable thresholds for capacity planning.
  name: Capacity Planning
- description: Compare latency and throughput metrics across API versions to detect performance regressions before deployment to production.
  name: Regression Detection
---
