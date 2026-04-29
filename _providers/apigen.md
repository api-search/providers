---
api_count: 1
api_specs:
- filename: apigen-apigen-openapi.yml
  format: yaml
  label: APIGen
  slug: apigen
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apigen/refs/heads/main/openapi/apigen-apigen-openapi.yml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apigen\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apigen/refs/heads/main/apis.yml\nname: APIGen\ndescription: >-\n  ApiGen is an open source PHP API documentation generator that automatically\n  produces smart and simple documentation from PHP source code. It supports\n  PHP 7.1+ including all PHP 8.3 features like enums, union types, readonly\n  classes, and intersection types. ApiGen is maintained by the ApiGen GitHub\n  organization and can be installed via Docker, Phar binary, or Composer.\ntags:\n  - Code\n  - Documentation\n  - Generation\n  - Open Source\n  - PHP\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-04-19'\nposition: Consumer\nspecificationVersion: '0.19'\napis:\n  - aid: apigen:apigen\n    name: APIGen\n    tags:\n      - Documentation\n      - Generation\n      - PHP\n    humanURL: https://github.com/ApiGen/ApiGen\n    baseURL:\
  \ https://api.apigen.com/v1\n    properties:\n      - url: https://github.com/ApiGen/ApiGen\n        type: GitHubRepository\n      - url: https://packagist.org/packages/apigen/apigen\n        type: SDK\n        title: Composer Package\n      - url: openapi/apigen-apigen-openapi.yml\n        type: OpenAPI\n      - url: json-schema/apigen-project-schema.json\n        type: JSONSchema\n      - url: json-schema/apigen-api-schema.json\n        type: JSONSchema\n      - url: json-schema/apigen-endpoint-schema.json\n        type: JSONSchema\n      - url: json-schema/apigen-deployment-schema.json\n        type: JSONSchema\n      - url: json-ld/apigen-context.jsonld\n        type: JSON-LD\n    description: >-\n      ApiGen is an easy to use and modern PHP API documentation generator\n      that automatically builds API documentation from PHP source code\n      with full support for PHP 7.1+ features including typed properties,\n      enums, union types, readonly classes, and typed class constants.\n\
  common:\n  - url: https://github.com/ApiGen/ApiGen\n    type: GitHubOrganization\n  - url: https://packagist.org/packages/apigen/apigen\n    type: SDK\n  - url: https://hub.docker.com/r/apigen/apigen\n    type: Docker\n  - type: Features\n    data:\n      - name: PHP Documentation Generation\n        description: Automatically generates API documentation from PHP source code with phpDoc support.\n      - name: Modern PHP Support\n        description: Full support for PHP 7.1+ including typed properties, enums, union types, readonly classes, and PHP 8.3 features.\n      - name: Advanced Type Systems\n        description: Supports intersection types, disjunctive normal form types, constructor property promotion, and all PHPStan-supported types.\n      - name: Flexible Installation\n        description: Available via Docker, Phar binary, or Composer for flexible integration into any PHP project workflow.\n      - name: Template-Based Output\n        description: Uses Latte templating for\
  \ customizable documentation output with built-in CommonMark support.\n  - type: UseCases\n    data:\n      - name: PHP Library Documentation\n        description: Generate comprehensive API reference documentation for PHP libraries and packages.\n      - name: CI/CD Documentation Pipeline\n        description: Automate API documentation generation as part of continuous integration workflows.\n      - name: Open Source Project Docs\n        description: Create and maintain documentation for open source PHP projects.\n  - type: Integrations\n    data:\n      - name: Composer\n        description: Available as a Composer package for easy installation in PHP projects.\n      - name: Docker\n        description: Official Docker image for containerized documentation generation.\n      - name: GitHub Actions\n        description: Can be integrated into GitHub Actions workflows for automated documentation.\n      - name: PHPStan\n        description: Built on phpstan/phpdoc-parser for comprehensive\
  \ type system support.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apigen/refs/heads/main/apis.yml
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
