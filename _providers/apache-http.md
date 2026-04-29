---
api_count: 2
api_specs:
- filename: apache-http-client-openapi.yml
  format: yaml
  label: Apache HttpComponents Client API
  slug: apache-http-client-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-http/refs/heads/main/openapi/apache-http-client-openapi.yml
apis:
- description: Java HTTP client library API for executing HTTP requests with connection pooling, async I/O, TLS/SSL, authentication, cookie management, and proxy support via Apache HttpComponents 5.x.
  name: Apache HttpComponents Client API
  slug: apache-http-client-api
- description: Maven artifact for Apache HttpComponents HttpClient 5.x providing full HTTP client functionality including fluent API, async client, and reactive streams support.
  name: Apache HttpComponents Java SDK
  slug: apache-http-java-sdk
capabilities:
- description: ''
  name: Http Client Integration
  slug: http-client-integration
common:
- title: ''
  type: Documentation
  url: https://hc.apache.org/
- title: ''
  type: GettingStarted
  url: https://hc.apache.org/httpcomponents-client-5.3.x/quickstart.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/httpcomponents-client
- title: ''
  type: SpectralRules
  url: rules/apache-http-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-http-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/http-client-integration.yaml
created: '2026-03-16'
description: Apache HttpComponents is a set of Java HTTP components, including a feature-rich HTTP client (HttpClient 5.x) and HTTP server components. It provides connection pooling, async I/O, TLS/SSL support, authentication, cookie management, and content negotiation for Java applications making HTTP requests.
features:
- description: Configurable connection pool with per-route and total connection limits for efficient HTTP connection reuse.
  name: Connection Pooling
- description: Non-blocking async HTTP client based on Java NIO for high-concurrency request execution.
  name: Async HTTP Client
- description: Full TLS/SSL support with customizable trust stores, client certificates, and hostname verification.
  name: TLS/SSL Support
- description: Pluggable authentication framework supporting Basic, Digest, NTLM, and Bearer token schemes.
  name: Authentication Framework
- description: RFC-compliant cookie management with customizable cookie stores and policies.
  name: Cookie Management
- description: HTTP, HTTPS, and SOCKS proxy support with proxy authentication.
  name: Proxy Support
- description: Built-in content encoding, compression (gzip/deflate), and charset negotiation.
  name: Content Negotiation
- description: High-level fluent API for simplified one-liner HTTP request execution.
  name: Fluent API
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Spring RestTemplate and WebClient use Apache HttpComponents as a configurable HTTP backend.
  name: Spring Framework
- description: Apache CXF JAX-RS client uses HttpComponents for HTTP transport in web service calls.
  name: Apache CXF
- description: Elasticsearch Java client uses HttpComponents for transport-layer HTTP communication.
  name: Elasticsearch Java Client
- description: Apache Solr Java client (SolrJ) uses HttpComponents for Solr HTTP API calls.
  name: Apache Solr
jsonld:
- class_count: 17
  name: Apache Http Client Context
  property_count: 0
  slug: apache-http-client-context
layout: provider
modified: '2026-04-19'
name: Apache HttpComponents
rules:
- name: Apache HttpComponents API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 4
  slug: apache-http-spectral-rules
skills: []
slug: apache-http
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-http\nname: Apache HttpComponents\ndescription: >-\n  Apache HttpComponents is a set of Java HTTP components, including a feature-rich HTTP client (HttpClient 5.x) and HTTP server components. It provides connection pooling, async I/O, TLS/SSL support, authentication, cookie management, and content negotiation for Java applications making HTTP requests.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - HTTP Client\n  - Java\n  - Open Source\n  - SDK\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-http/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-http:apache-http-client-api\n    name: Apache HttpComponents Client API\n    description: >-\n      Java HTTP client library API for executing HTTP requests with connection pooling, async I/O, TLS/SSL, authentication,\
  \ cookie management, and proxy support via Apache HttpComponents 5.x.\n    humanURL: https://hc.apache.org/httpcomponents-client-5.3.x/\n    tags:\n      - Authentication\n      - Connection Pooling\n      - HTTP Client\n      - Java\n      - TLS\n    properties:\n      - type: Documentation\n        url: https://hc.apache.org/httpcomponents-client-5.3.x/\n      - type: OpenAPI\n        url: openapi/apache-http-client-openapi.yml\n      - type: JSONSchema\n        url: json-schema/http-client-httprequest-schema.json\n      - type: JSON-LD\n        url: json-ld/apache-http-client-context.jsonld\n\n  - aid: apache-http:apache-http-java-sdk\n    name: Apache HttpComponents Java SDK\n    description: >-\n      Maven artifact for Apache HttpComponents HttpClient 5.x providing full HTTP client functionality including fluent API, async client, and reactive streams support.\n    humanURL: https://hc.apache.org/httpcomponents-client-5.3.x/dependency-info.html\n    tags:\n      - Java\n      - Maven\n\
  \      - SDK\n    properties:\n      - type: Documentation\n        url: https://hc.apache.org/httpcomponents-client-5.3.x/dependency-info.html\n      - type: SDK\n        url: https://search.maven.org/artifact/org.apache.httpcomponents.client5/httpclient5\n        title: Java SDK (Maven Central)\n\ncommon:\n  - type: Documentation\n    url: https://hc.apache.org/\n  - type: GettingStarted\n    url: https://hc.apache.org/httpcomponents-client-5.3.x/quickstart.html\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/httpcomponents-client\n  - type: SpectralRules\n    url: rules/apache-http-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-http-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/http-client-integration.yaml\n  - type: Features\n    data:\n      - name: Connection Pooling\n        description: Configurable connection pool with per-route and total connection limits\
  \ for efficient HTTP connection reuse.\n      - name: Async HTTP Client\n        description: Non-blocking async HTTP client based on Java NIO for high-concurrency request execution.\n      - name: TLS/SSL Support\n        description: Full TLS/SSL support with customizable trust stores, client certificates, and hostname verification.\n      - name: Authentication Framework\n        description: Pluggable authentication framework supporting Basic, Digest, NTLM, and Bearer token schemes.\n      - name: Cookie Management\n        description: RFC-compliant cookie management with customizable cookie stores and policies.\n      - name: Proxy Support\n        description: HTTP, HTTPS, and SOCKS proxy support with proxy authentication.\n      - name: Content Negotiation\n        description: Built-in content encoding, compression (gzip/deflate), and charset negotiation.\n      - name: Fluent API\n        description: High-level fluent API for simplified one-liner HTTP request execution.\n  -\
  \ type: UseCases\n    data:\n      - name: REST API Client Integration\n        description: Consume REST APIs from Java applications with connection pooling and retry logic.\n      - name: Web Scraping\n        description: Crawl and fetch web content with cookie handling and redirect following.\n      - name: Microservices HTTP Communication\n        description: Make service-to-service HTTP calls with connection reuse and timeout configuration.\n      - name: Authentication Token Refresh\n        description: Implement OAuth2 token refresh flows using the authentication interceptor framework.\n      - name: File Upload and Download\n        description: Stream large file uploads and downloads via multipart or chunked transfer encoding.\n  - type: Integrations\n    data:\n      - name: Spring Framework\n        description: Spring RestTemplate and WebClient use Apache HttpComponents as a configurable HTTP backend.\n      - name: Apache CXF\n        description: Apache CXF JAX-RS client\
  \ uses HttpComponents for HTTP transport in web service calls.\n      - name: Elasticsearch Java Client\n        description: Elasticsearch Java client uses HttpComponents for transport-layer HTTP communication.\n      - name: Apache Solr\n        description: Apache Solr Java client (SolrJ) uses HttpComponents for Solr HTTP API calls.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-http/refs/heads/main/apis.yml
tags:
- Apache
- HTTP Client
- Java
- Open Source
- SDK
url: https://raw.githubusercontent.com/api-evangelist/apache-http/refs/heads/main/apis.yml
use_cases:
- description: Consume REST APIs from Java applications with connection pooling and retry logic.
  name: REST API Client Integration
- description: Crawl and fetch web content with cookie handling and redirect following.
  name: Web Scraping
- description: Make service-to-service HTTP calls with connection reuse and timeout configuration.
  name: Microservices HTTP Communication
- description: Implement OAuth2 token refresh flows using the authentication interceptor framework.
  name: Authentication Token Refresh
- description: Stream large file uploads and downloads via multipart or chunked transfer encoding.
  name: File Upload and Download
---
