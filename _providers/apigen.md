---
api_count: 1
apis:
- description: ApiGen is an easy to use and modern PHP API documentation generator that automatically builds API documentation from PHP source code with full support for PHP 7.1+ features including typed properties,
  name: APIGen
  slug: apigen
capabilities:
- description: Workflow for generating, publishing, and managing API documentation using APIGen - creating projects from PHP source code, configuring endpoints, and deploying documentation sites.
  name: APIGen Documentation Generation
  slug: api-documentation-generation
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/ApiGen/ApiGen
- title: ''
  type: SDK
  url: https://packagist.org/packages/apigen/apigen
- title: ''
  type: Docker
  url: https://hub.docker.com/r/apigen/apigen
created: '2025-01-08'
description: ApiGen is an open source PHP API documentation generator that automatically produces smart and simple documentation from PHP source code. It supports PHP 7.1+ including all PHP 8.3 features like enums, union types, readonly classes, and intersection types. ApiGen is maintained by the ApiGen GitHub organization and can be installed via Docker, Phar binary, or Composer.
features:
- description: Automatically generates API documentation from PHP source code with phpDoc support.
  name: PHP Documentation Generation
- description: Full support for PHP 7.1+ including typed properties, enums, union types, readonly classes, and PHP 8.3 features.
  name: Modern PHP Support
- description: Supports intersection types, disjunctive normal form types, constructor property promotion, and all PHPStan-supported types.
  name: Advanced Type Systems
- description: Available via Docker, Phar binary, or Composer for flexible integration into any PHP project workflow.
  name: Flexible Installation
- description: Uses Latte templating for customizable documentation output with built-in CommonMark support.
  name: Template-Based Output
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Available as a Composer package for easy installation in PHP projects.
  name: Composer
- description: Official Docker image for containerized documentation generation.
  name: Docker
- description: Can be integrated into GitHub Actions workflows for automated documentation.
  name: GitHub Actions
- description: Built on phpstan/phpdoc-parser for comprehensive type system support.
  name: PHPStan
jsonld:
- class_count: 29
  name: Apigen Context
  property_count: 10
  slug: apigen-context
layout: provider
modified: '2026-04-19'
name: APIGen
rules:
- name: APIGen API Rules
  rule_count: 7
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 3
  slug: apigen-spectral-rules
skills: []
slug: apigen
solutions: []
tags:
- Code
- Documentation
- Generation
- Open Source
- PHP
url: https://raw.githubusercontent.com/api-evangelist/apigen/refs/heads/main/apis.yml
use_cases:
- description: Generate comprehensive API reference documentation for PHP libraries and packages.
  name: PHP Library Documentation
- description: Automate API documentation generation as part of continuous integration workflows.
  name: CI/CD Documentation Pipeline
- description: Create and maintain documentation for open source PHP projects.
  name: Open Source Project Docs
---
