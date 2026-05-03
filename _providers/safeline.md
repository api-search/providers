---
api_count: 2
api_specs:
- filename: safeline-management-openapi.yml
  format: yaml
  label: SafeLine Management API
  slug: safeline
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/safeline/refs/heads/main/openapi/safeline-management-openapi.yml
apis:
- description: SafeLine Management API provides programmatic control of the SafeLine WAF including application management, security rule configuration, attack event analysis, IP allowlist/blocklist management, and t
  name: SafeLine Management API
  slug: safeline
- description: 'SafeLine provides two MCP (Model Context Protocol) Server implementations for AI-assisted WAF management: a Python MCP Server for tool-based API management and a Go MCP Server for high-performance man'
  name: SafeLine MCP Server
  slug: mcp-server
capabilities:
- description: Unified workflow for managing web application firewall protection including website configuration, ACL rules, SSL certificates, security policies, and attack event analysis. Used by security engineers
  name: SafeLine WAF Protection Management
  slug: waf-protection-management
common:
- title: ''
  type: Website
  url: https://waf.chaitin.com/
- title: ''
  type: Documentation
  url: https://docs.waf.chaitin.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/chaitin/SafeLine
- title: ''
  type: Demo
  url: https://demo.waf.chaitin.com/
- title: ''
  type: OpenAPI
  url: openapi/safeline-management-openapi.yml
- title: ''
  type: SpectralRules
  url: rules/safeline-rules.yml
- title: ''
  type: JSONSchema
  url: json-schema/safeline-website-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/safeline-acl-rule-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/safeline-website-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/safeline-acl-rule-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/safeline-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/safeline-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/waf-protection-management.yaml
created: '2026-03-27'
description: SafeLine is an open-source self-hosted Web Application Firewall (WAF) and reverse proxy developed by Chaitin Technology that protects web applications and APIs from attacks including SQL injection, XSS, code injection, OS command injection, SSRF, path traversal, and RCE. With over 180,000 installations protecting more than 1 million websites, SafeLine handles over 30 billion HTTP requests daily. It provides rate limiting, anti-bot defenses, dynamic code protection, and integrates with API gateways including Apache APISIX and Kong. SafeLine exposes a management API on port 9443 and supports MCP server implementations for AI-assisted management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 26
  name: Safeline Context
  property_count: 0
  slug: safeline-context
layout: provider
modified: '2026-05-02'
name: SafeLine
rules:
- name: SafeLine API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 3
    warn: 3
  slug: safeline-rules
skills: []
slug: safeline
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: safeline\nname: SafeLine\ndescription: >-\n  SafeLine is an open-source self-hosted Web Application Firewall (WAF) and\n  reverse proxy developed by Chaitin Technology that protects web applications\n  and APIs from attacks including SQL injection, XSS, code injection, OS command\n  injection, SSRF, path traversal, and RCE. With over 180,000 installations\n  protecting more than 1 million websites, SafeLine handles over 30 billion\n  HTTP requests daily. It provides rate limiting, anti-bot defenses, dynamic\n  code protection, and integrates with API gateways including Apache APISIX\n  and Kong. SafeLine exposes a management API on port 9443 and supports MCP\n  server implementations for AI-assisted management.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Proxy\n  - WAF\n  - Security\n  - Open Source\n  - Reverse Proxy\n  - API Gateway\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/safeline/refs/heads/main/apis.yml\n\
  created: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: safeline:safeline\n    name: SafeLine Management API\n    description: >-\n      SafeLine Management API provides programmatic control of the SafeLine WAF\n      including application management, security rule configuration, attack\n      event analysis, IP allowlist/blocklist management, and traffic monitoring.\n      The management API is exposed on port 9443 and supports authentication\n      via API tokens.\n    humanURL: https://waf.chaitin.com/\n    tags:\n      - Proxy\n      - WAF\n      - Security\n      - REST\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://docs.waf.chaitin.com/\n      - type: Getting Started\n        url: https://docs.waf.chaitin.com/en/getting-started\n      - type: GitHubRepository\n        url: https://github.com/chaitin/SafeLine\n      - type: OpenAPI\n        url: openapi/safeline-management-openapi.yml\n\n  - aid: safeline:mcp-server\n\
  \    name: SafeLine MCP Server\n    description: >-\n      SafeLine provides two MCP (Model Context Protocol) Server implementations\n      for AI-assisted WAF management: a Python MCP Server for tool-based API\n      management and a Go MCP Server for high-performance management. These\n      servers expose tools for application management, security rule\n      configuration, and attack event analysis.\n    humanURL: https://github.com/chaitin/SafeLine\n    tags:\n      - WAF\n      - MCP\n      - AI\n      - Security\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/chaitin/SafeLine\n\ncommon:\n  - type: Website\n    url: https://waf.chaitin.com/\n  - type: Documentation\n    url: https://docs.waf.chaitin.com/\n  - type: GitHubOrganization\n    url: https://github.com/chaitin/SafeLine\n  - type: Demo\n    url: https://demo.waf.chaitin.com/\n  - type: OpenAPI\n    url: openapi/safeline-management-openapi.yml\n  - type: SpectralRules\n    url: rules/safeline-rules.yml\n\
  \  - type: JSONSchema\n    url: json-schema/safeline-website-schema.json\n  - type: JSONSchema\n    url: json-schema/safeline-acl-rule-schema.json\n  - type: JSONStructure\n    url: json-structure/safeline-website-structure.json\n  - type: JSONStructure\n    url: json-structure/safeline-acl-rule-structure.json\n  - type: JSONLDContext\n    url: json-ld/safeline-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/safeline-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/waf-protection-management.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/safeline/refs/heads/main/apis.yml
tags:
- Proxy
- WAF
- Security
- Open Source
- Reverse Proxy
- API Gateway
url: https://raw.githubusercontent.com/api-evangelist/safeline/refs/heads/main/apis.yml
use_cases: []
---
