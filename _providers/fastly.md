---
api_count: 14
api_specs:
- filename: fastly-services-openapi.yml
  format: yaml
  label: Fastly Services API
  slug: services-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-services-openapi.yml
- filename: fastly-purging-openapi.yml
  format: yaml
  label: Fastly Purging API
  slug: purging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-purging-openapi.yml
- filename: fastly-logging-openapi.yml
  format: yaml
  label: Fastly Real-Time Logging API
  slug: logging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-logging-openapi.yml
- filename: fastly-metrics-and-stats-openapi.yml
  format: yaml
  label: Fastly Metrics and Stats API
  slug: metrics-and-stats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-metrics-and-stats-openapi.yml
- filename: fastly-tls-openapi.yml
  format: yaml
  label: Fastly TLS API
  slug: tls-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-tls-openapi.yml
- filename: fastly-vcl-services-openapi.yml
  format: yaml
  label: Fastly VCL Services API
  slug: vcl-services-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-vcl-services-openapi.yml
- filename: fastly-account-openapi.yml
  format: yaml
  label: Fastly Account API
  slug: account-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-account-openapi.yml
- filename: fastly-authentication-tokens-openapi.yml
  format: yaml
  label: Fastly Authentication Tokens API
  slug: authentication-tokens-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-authentication-tokens-openapi.yml
- filename: fastly-acls-openapi.yml
  format: yaml
  label: Fastly Access Control Lists API
  slug: acls-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-acls-openapi.yml
- filename: fastly-dictionaries-openapi.yml
  format: yaml
  label: Fastly Edge Dictionaries API
  slug: dictionaries-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-dictionaries-openapi.yml
- filename: fastly-compute-openapi.yml
  format: yaml
  label: Fastly Compute API
  slug: compute-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-compute-openapi.yml
- filename: fastly-waf-openapi.yml
  format: yaml
  label: Fastly Next-Gen WAF API
  slug: waf-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-waf-openapi.yml
- filename: fastly-domain-management-openapi.yml
  format: yaml
  label: Fastly Domain Management API
  slug: domain-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-domain-management-openapi.yml
- filename: fastly-products-openapi.yml
  format: yaml
  label: Fastly Products API
  slug: products-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-products-openapi.yml
apis:
- description: The Fastly Services API allows developers to create, configure, and manage Fastly CDN services and their versions programmatically. Services are the primary organizational unit in Fastly, representing
  name: Fastly Services API
  slug: services-api
- description: 'The Fastly Purging API enables developers to instantly remove cached content from Fastly''s edge network so it can be refreshed from origin servers. It supports single URL purges, surrogate key purges '
  name: Fastly Purging API
  slug: purging-api
- description: 'The Fastly Real-Time Logging API allows developers to configure and manage logging endpoints that receive streamed log data from Fastly''s edge network. Fastly supports logging to a variety of formats '
  name: Fastly Real-Time Logging API
  slug: logging-api
- description: The Fastly Metrics and Stats API provides access to both real-time and historical analytics data for Fastly services. The real-time analytics endpoint, served on rt.fastly.com, delivers second-by-seco
  name: Fastly Metrics and Stats API
  slug: metrics-and-stats-api
- description: The Fastly TLS API enables developers to manage TLS certificates, private keys, and domain configurations for securing traffic delivered through Fastly's edge network. It supports both platform TLS (m
  name: Fastly TLS API
  slug: tls-api
- description: The Fastly VCL Services API provides programmatic access to configure Varnish Configuration Language (VCL) objects that power most Fastly services. Developers can upload custom VCL code or use the API
  name: Fastly VCL Services API
  slug: vcl-services-api
- description: The Fastly Account API provides endpoints for managing customer accounts, users, and identity and access management (IAM) resources. Developers can programmatically manage user invitations, roles, per
  name: Fastly Account API
  slug: account-api
- description: The Fastly Authentication Tokens API enables developers to create and manage API tokens used to authenticate requests to the Fastly API. Tokens can be scoped to specific services and permissions, allo
  name: Fastly Authentication Tokens API
  slug: authentication-tokens-api
- description: 'The Fastly Access Control Lists API allows developers to create and manage ACLs that can be used to control access to content at the edge. ACLs contain entries of IP addresses or CIDR ranges that can '
  name: Fastly Access Control Lists API
  slug: acls-api
- description: The Fastly Edge Dictionaries API provides endpoints for creating and managing key-value lookup tables that are accessible at the edge without requiring a service version change. Dictionaries can store
  name: Fastly Edge Dictionaries API
  slug: dictionaries-api
- description: The Fastly Compute platform enables developers to build and deploy serverless applications that run on Fastly's global edge network using WebAssembly. Compute services support custom application logic
  name: Fastly Compute API
  slug: compute-api
- description: The Fastly Next-Gen WAF API provides programmatic access to configure and manage web application firewall rules that protect applications delivered through Fastly's edge network. It enables developers
  name: Fastly Next-Gen WAF API
  slug: waf-api
- description: The Fastly Domain Management API allows developers to programmatically associate domain names with Fastly services. Domains serve as the entry point for traffic routed through Fastly's edge network. T
  name: Fastly Domain Management API
  slug: domain-management-api
- description: The Fastly Products API provides endpoints for enabling and managing Fastly product features on services, including Bot Management, DDoS Protection, Image Optimizer, API Discovery, and other add-on ca
  name: Fastly Products API
  slug: products-api
common:
- title: ''
  type: JSON-LD
  url: json-ld/fastly-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/fastly-service-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fastly-backend-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fastly-acl-entry-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fastly-dictionary-item-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fastly-tls-certificate-schema.json
created: ''
description: Fastly is an edge cloud platform that helps customers create great digital experiences quickly, securely, and reliably by processing, serving, and securing their applications closer to their users.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Fastly Context
  property_count: 13
  slug: fastly-context
layout: provider
modified: '2026-03-20'
name: fastly
skills: []
slug: fastly
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fastly\nurl: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/apis.yml\napis:\n  - aid: fastly:services-api\n    name: Fastly Services API\n    tags:\n      - CDN\n      - Configuration\n      - Edge Cloud\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fastly.com\n    humanURL: https://www.fastly.com/documentation/reference/api/services/\n    properties:\n      - url: https://www.fastly.com/documentation/reference/api/services/\n        type: Documentation\n      - url: openapi/fastly-services-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fastly Services API allows developers to create, configure, and manage\n      Fastly CDN services and their versions programmatically. Services are the\n      primary organizational unit in Fastly, representing a configuration that\n      maps domains to backends. The API supports creating service versions,\n      activating and\
  \ deactivating configurations, cloning versions, and managing\n      the complete lifecycle of a CDN service deployment.\n  - aid: fastly:purging-api\n    name: Fastly Purging API\n    tags:\n      - Cache\n      - CDN\n      - Content Delivery\n      - Purging\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fastly.com\n    humanURL: https://www.fastly.com/documentation/reference/api/purging/\n    properties:\n      - url: https://www.fastly.com/documentation/reference/api/purging/\n        type: Documentation\n      - url: openapi/fastly-purging-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fastly Purging API enables developers to instantly remove cached\n      content from Fastly's edge network so it can be refreshed from origin\n      servers. It supports single URL purges, surrogate key purges for\n      invalidating groups of related objects, and purge-all operations to clear\n      an entire service\
  \ cache. Surrogate key and URL purges are separately\n      limited to an average of 100,000 purges per hour per customer and are not\n      counted against the general API rate limit.\n  - aid: fastly:logging-api\n    name: Fastly Real-Time Logging API\n    tags:\n      - Analytics\n      - Logging\n      - Monitoring\n      - Observability\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fastly.com\n    humanURL: https://www.fastly.com/documentation/reference/api/logging/\n    properties:\n      - url: https://www.fastly.com/documentation/reference/api/logging/\n        type: Documentation\n      - url: openapi/fastly-logging-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fastly Real-Time Logging API allows developers to configure and manage logging\n      endpoints that receive streamed log data from Fastly's edge network. Fastly\n      supports logging to a variety of formats and platforms including\
  \ syslog, Amazon\n      S3, Google Cloud Storage, BigQuery, Datadog, Splunk, Elasticsearch, and many\n      other providers.\n  - aid: fastly:metrics-and-stats-api\n    name: Fastly Metrics and Stats API\n    tags:\n      - Analytics\n      - Metrics\n      - Monitoring\n      - Real-Time\n      - Statistics\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://rt.fastly.com\n    humanURL: https://www.fastly.com/documentation/reference/api/metrics-stats/\n    properties:\n      - url: https://www.fastly.com/documentation/reference/api/metrics-stats/\n        type: Documentation\n      - url: openapi/fastly-metrics-and-stats-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fastly Metrics and Stats API provides access to both real-time and\n      historical analytics data for Fastly services. The real-time analytics\n      endpoint, served on rt.fastly.com, delivers second-by-second stats\n      including request counts,\
  \ bandwidth, cache hit ratios, and error rates.\n      Historical stats provide aggregated data over longer time periods. The API\n      also includes the Domain Inspector for per-domain metrics and the Origin\n      Inspector for origin-level performance data.\n  - aid: fastly:tls-api\n    name: Fastly TLS API\n    tags:\n      - Certificates\n      - Encryption\n      - Security\n      - SSL\n      - TLS\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fastly.com\n    humanURL: https://www.fastly.com/documentation/reference/api/tls/\n    properties:\n      - url: https://www.fastly.com/documentation/reference/api/tls/\n        type: Documentation\n      - url: openapi/fastly-tls-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fastly TLS API enables developers to manage TLS certificates,\n      private keys, and domain configurations for securing traffic delivered\n      through Fastly's edge network. It\
  \ supports both platform TLS (managed\n      certificates) and custom TLS configurations where customers bring their\n      own certificates. The API allows uploading certificates, managing bulk\n      certificate operations, configuring TLS activations, and managing mutual\n      TLS authentication for origin connections.\n  - aid: fastly:vcl-services-api\n    name: Fastly VCL Services API\n    tags:\n      - Caching\n      - CDN\n      - Configuration\n      - Edge Logic\n      - VCL\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fastly.com\n    humanURL: https://www.fastly.com/documentation/reference/api/vcl-services/\n    properties:\n      - url: https://www.fastly.com/documentation/reference/api/vcl-services/\n        type: Documentation\n      - url: openapi/fastly-vcl-services-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fastly VCL Services API provides programmatic access to configure\n   \
  \   Varnish Configuration Language (VCL) objects that power most Fastly\n      services. Developers can upload custom VCL code or use the API to generate\n      VCL through configuration objects including backends, conditions, cache\n      settings, request settings, response objects, headers, and VCL snippets.\n      This API is central to defining how Fastly processes, routes, and caches\n      HTTP requests at the edge.\n  - aid: fastly:account-api\n    name: Fastly Account API\n    tags:\n      - Account\n      - Administration\n      - IAM\n      - Users\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fastly.com\n    humanURL: https://www.fastly.com/documentation/reference/api/account/\n    properties:\n      - url: https://www.fastly.com/documentation/reference/api/account/\n        type: Documentation\n      - url: openapi/fastly-account-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fastly Account\
  \ API provides endpoints for managing customer accounts,\n      users, and identity and access management (IAM) resources. Developers can\n      programmatically manage user invitations, roles, permissions, and service\n      groups to control access to Fastly resources. The API supports retrieving\n      and updating customer information, managing user profiles, and configuring\n      organizational settings for enterprise accounts.\n  - aid: fastly:authentication-tokens-api\n    name: Fastly Authentication Tokens API\n    tags:\n      - API Keys\n      - Authentication\n      - Security\n      - Tokens\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fastly.com\n    humanURL: https://www.fastly.com/documentation/reference/api/auth-tokens/\n    properties:\n      - url: https://www.fastly.com/documentation/reference/api/auth-tokens/\n        type: Documentation\n      - url: openapi/fastly-authentication-tokens-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The Fastly Authentication Tokens API enables developers to create and\n      manage API tokens used to authenticate requests to the Fastly API. Tokens\n      can be scoped to specific services and permissions, allowing fine-grained\n      access control for users and automated systems. The API supports creating\n      user tokens, automation tokens for CI/CD pipelines, and managing token\n      lifecycle including listing, revoking, and expiring tokens.\n  - aid: fastly:acls-api\n    name: Fastly Access Control Lists API\n    tags:\n      - Access Control\n      - Edge Security\n      - IP Filtering\n      - Security\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fastly.com\n    humanURL: https://www.fastly.com/documentation/reference/api/acls/\n    properties:\n      - url: https://www.fastly.com/documentation/reference/api/acls/\n        type: Documentation\n      - url:\
  \ openapi/fastly-acls-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fastly Access Control Lists API allows developers to create and manage\n      ACLs that can be used to control access to content at the edge. ACLs\n      contain entries of IP addresses or CIDR ranges that can be referenced in\n      VCL to allow or deny requests. The API supports creating ACL containers,\n      adding and removing individual entries, and performing bulk updates to\n      efficiently manage large IP allowlists or blocklists without requiring\n      a new service version deployment.\n  - aid: fastly:dictionaries-api\n    name: Fastly Edge Dictionaries API\n    tags:\n      - Dictionaries\n      - Dynamic Configuration\n      - Edge Configuration\n      - Key-Value\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fastly.com\n    humanURL: https://www.fastly.com/documentation/reference/api/dictionaries/\n    properties:\n\
  \      - url: https://www.fastly.com/documentation/reference/api/dictionaries/\n        type: Documentation\n      - url: openapi/fastly-dictionaries-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fastly Edge Dictionaries API provides endpoints for creating and managing\n      key-value lookup tables that are accessible at the edge without requiring a\n      service version change. Dictionaries can store configuration data, feature flags,\n      redirect mappings, and other dynamic values that VCL or Compute services can\n      reference during request processing.\n  - aid: fastly:compute-api\n    name: Fastly Compute API\n    tags:\n      - Compute\n      - Edge Computing\n      - Serverless\n      - WebAssembly\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fastly.com\n    humanURL: https://www.fastly.com/documentation/guides/compute/\n    properties:\n      - url: https://www.fastly.com/documentation/guides/compute/\n\
  \        type: Documentation\n      - url: openapi/fastly-compute-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fastly Compute platform enables developers to build and deploy serverless\n      applications that run on Fastly's global edge network using WebAssembly. Compute\n      services support custom application logic written in Rust, JavaScript, or Go\n      using official Fastly SDKs.\n  - aid: fastly:waf-api\n    name: Fastly Next-Gen WAF API\n    tags:\n      - DDoS Protection\n      - Security\n      - WAF\n      - Web Application Firewall\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fastly.com\n    humanURL: https://www.fastly.com/documentation/reference/api/waf/\n    properties:\n      - url: https://www.fastly.com/documentation/reference/api/waf/\n        type: Documentation\n      - url: openapi/fastly-waf-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fastly Next-Gen\
  \ WAF API provides programmatic access to configure and manage\n      web application firewall rules that protect applications delivered through Fastly's\n      edge network. It enables developers to manage WAF firewall configurations, rule\n      sets, and exclusions to defend against common web attacks including SQL injection,\n      cross-site scripting, and other OWASP Top 10 vulnerabilities.\n  - aid: fastly:domain-management-api\n    name: Fastly Domain Management API\n    tags:\n      - CDN\n      - Configuration\n      - DNS\n      - Domains\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fastly.com\n    humanURL: https://www.fastly.com/documentation/reference/api/services/domain/\n    properties:\n      - url: https://www.fastly.com/documentation/reference/api/services/domain/\n        type: Documentation\n      - url: openapi/fastly-domain-management-openapi.yml\n        type: OpenAPI\n    description: >-\n    \
  \  The Fastly Domain Management API allows developers to programmatically\n      associate domain names with Fastly services. Domains serve as the entry\n      point for traffic routed through Fastly's edge network. The API supports\n      adding, listing, and removing domains from service versions, checking\n      domain DNS configurations, and validating that domains are correctly\n      pointed to Fastly. It is essential for managing the routing configuration\n      that connects end-user requests to the appropriate Fastly service.\n  - aid: fastly:products-api\n    name: Fastly Products API\n    tags:\n      - Configuration\n      - Features\n      - Platform\n      - Products\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fastly.com\n    humanURL: https://www.fastly.com/documentation/reference/api/products/\n    properties:\n      - url: https://www.fastly.com/documentation/reference/api/products/\n        type: Documentation\n\
  \      - url: openapi/fastly-products-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fastly Products API provides endpoints for enabling and managing Fastly\n      product features on services, including Bot Management, DDoS Protection, Image\n      Optimizer, API Discovery, and other add-on capabilities. Developers can use\n      this API to check which products are enabled for a service, enable or disable\n      product features, and configure product-specific settings.\ncommon:\n  - type: JSON-LD\n    url: json-ld/fastly-context.jsonld\n  - type: JSONSchema\n    url: json-schema/fastly-service-schema.json\n  - type: JSONSchema\n    url: json-schema/fastly-backend-schema.json\n  - type: JSONSchema\n    url: json-schema/fastly-acl-entry-schema.json\n  - type: JSONSchema\n    url: json-schema/fastly-dictionary-item-schema.json\n  - type: JSONSchema\n    url: json-schema/fastly-tls-certificate-schema.json\nmodified: '2026-03-20'\ndescription: >-\n  Fastly is an edge\
  \ cloud platform that helps customers create great digital experiences\n  quickly, securely, and reliably by processing, serving, and securing their applications\n  closer to their users.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/apis.yml
use_cases: []
---
