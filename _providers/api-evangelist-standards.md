---
api_count: 3
apis:
- description: Spectral is the open-source API linting framework developed by Stoplight that validates JSON and YAML artifacts including OpenAPI (v2, v3.0, v3.1), AsyncAPI (v2.x), and Arazzo specifications. Spectral
  name: Spectral Rules
  slug: spectral-rules
- description: Vacuum is an ultra-fast OpenAPI linter written in Go, created by pb33f (Dave Shanley) as a high-performance alternative to Spectral CLI. Vacuum rules are a fork of Spectral rules that maintain full ba
  name: Vacuum Rules
  slug: vacuum-rules
- description: A curated collection of publicly available Spectral and Vacuum rulesets published by major organizations as governance references, including Adidas, Microsoft Azure, Digital Ocean, and OWASP. These ru
  name: Published Community Rulesets
  slug: published-rulesets
common:
- title: ''
  type: Website
  url: https://spotlight-rules.com/
- title: ''
  type: Standards
  url: https://github.com/api-evangelist/standards/standards.yml
- title: ''
  type: GitHub
  url: https://github.com/api-evangelist/spotlight-rules
- title: ''
  type: Email
  url: mailto:kin@apievangelist.com
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/in/kinlane/
- title: ''
  type: JSONSchema
  url: json-schema/spectral-rule-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/vacuum-rule-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/spotlight-rules-vocabulary.yml
created: '2024-11-11'
description: Spotlight Rules shines a light on the evolution of API linting rules, specifically Spectral rules and their transformation into Vacuum rules, and the broader ecosystem of tools, platforms, and rulesets that support API governance. The site documents the Spectral rule format (JSON/YAML-based configuration for linting OpenAPI, AsyncAPI, and Arazzo specs), the Vacuum rules format (a backward-compatible fork adding howToFix, id, and category fields), and curates integrations across IDEs, CI/CD pipelines, commercial API management platforms, and open-source developer tools. Spotlight Rules is published by API Evangelist (Kin Lane) as part of ongoing API governance research.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/api-evangelist-logos/api-evangelist-butterfly-vertical.png
integrations: []
jsonld:
- class_count: 24
  name: Spotlight Rules Context
  property_count: 5
  slug: spotlight-rules-context
layout: provider
modified: '2026-05-02'
name: Spotlight Rules
skills: []
slug: api-evangelist-standards
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: api-evangelist-standards\nname: Spotlight Rules\ndescription: >-\n  Spotlight Rules shines a light on the evolution of API linting rules, specifically Spectral\n  rules and their transformation into Vacuum rules, and the broader ecosystem of tools,\n  platforms, and rulesets that support API governance. The site documents the Spectral rule\n  format (JSON/YAML-based configuration for linting OpenAPI, AsyncAPI, and Arazzo specs),\n  the Vacuum rules format (a backward-compatible fork adding howToFix, id, and category fields),\n  and curates integrations across IDEs, CI/CD pipelines, commercial API management platforms,\n  and open-source developer tools. Spotlight Rules is published by API Evangelist (Kin Lane)\n  as part of ongoing API governance research.\nspecificationVersion: '0.19'\ntype: Index\nposition: Provider\naccess: Public\nimage: >-\n  https://kinlane-productions2.s3.amazonaws.com/api-evangelist-logos/api-evangelist-butterfly-vertical.png\ntags:\n  - API Governance\n\
  \  - Linting\n  - Spectral\n  - Vacuum\n  - OpenAPI\n  - Standards\ncreated: '2024-11-11'\nmodified: '2026-05-02'\nurl: https://raw.githubusercontent.com/api-evangelist/spotlight-rules/refs/heads/main/apis.yml\napis:\n  - aid: api-evangelist-standards:spectral-rules\n    name: Spectral Rules\n    description: >-\n      Spectral is the open-source API linting framework developed by Stoplight that validates\n      JSON and YAML artifacts including OpenAPI (v2, v3.0, v3.1), AsyncAPI (v2.x), and\n      Arazzo specifications. Spectral rules are defined in YAML or JavaScript configuration\n      files and consist of rule names, descriptions, severity levels (error/warn/info/hint),\n      given (JSONPath selectors), and then (assertion functions). Originally released in 2018,\n      Spectral has become the de facto standard for API governance linting.\n    humanURL: https://stoplight.io/open-source/spectral\n    baseURL: https://spectral.stoplight.io\n    tags:\n      - Spectral\n      - Linting\n\
  \      - OpenAPI\n      - API Governance\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://docs.stoplight.io/docs/spectral\n      - type: Repository\n        url: https://github.com/stoplightio/spectral\n      - type: NPM\n        url: https://www.npmjs.com/package/@stoplight/spectral-cli\n      - type: VSCode Extension\n        url: https://marketplace.visualstudio.com/items?itemName=stoplight.spectral\n      - type: GitHub Action\n        url: https://github.com/marketplace/actions/spectral-linting\n    features:\n      - type: OpenAPILinting\n        description: Validate OpenAPI 2.0, 3.0, and 3.1 specifications against custom rules\n      - type: AsyncAPILinting\n        description: Validate AsyncAPI 2.x specifications for consistency and standards\n      - type: ArazzoLinting\n        description: Lint Arazzo workflow specifications\n      - type: CustomFunctions\n        description: Extend rules with custom JavaScript functions for complex\
  \ validation logic\n      - type: MultiFormatSupport\n        description: Validate YAML, JSON, and other structured document formats\n      - type: CIIntegration\n        description: GitHub Actions, GitLab CI, Jenkins, Azure DevOps, and CircleCI support\n\n  - aid: api-evangelist-standards:vacuum-rules\n    name: Vacuum Rules\n    description: >-\n      Vacuum is an ultra-fast OpenAPI linter written in Go, created by pb33f (Dave Shanley)\n      as a high-performance alternative to Spectral CLI. Vacuum rules are a fork of Spectral\n      rules that maintain full backward compatibility while adding three new fields: howToFix\n      (remediation guidance), id (stable rule identifier), and category (organizational grouping).\n      Vacuum supports both RFC 9535 JSONPath and JSON Path Plus extensions, and includes a\n      built-in dashboard UI for visualizing lint results.\n    humanURL: https://quobix.com/vacuum/\n    baseURL: https://quobix.com/vacuum\n    tags:\n      - Vacuum\n     \
  \ - Linting\n      - OpenAPI\n      - API Governance\n      - Go\n      - High Performance\n    properties:\n      - type: Documentation\n        url: https://quobix.com/vacuum/\n      - type: Repository\n        url: https://github.com/daveshanley/vacuum\n      - type: JSONSchema\n        url: https://spotlight-rules.com/vacuum-rules-schema.json\n    features:\n      - type: SpectralCompatibility\n        description: 100% compatible with Spectral rulesets - run existing rules without modification\n      - type: HighPerformance\n        description: Written in Go for blazing-fast linting of large OpenAPI specifications\n      - type: HowToFix\n        description: Optional howToFix field providing remediation guidance to developers\n      - type: RuleCategories\n        description: Optional category field for organizing rules into governance domains\n      - type: DashboardUI\n        description: Built-in visual dashboard for browsing and understanding lint results\n      - type: JSONPathRFC9535\n\
  \        description: Supports the official RFC 9535 JSONPath standard plus JSON Path Plus extensions\n\n  - aid: api-evangelist-standards:published-rulesets\n    name: Published Community Rulesets\n    description: >-\n      A curated collection of publicly available Spectral and Vacuum rulesets published\n      by major organizations as governance references, including Adidas, Microsoft Azure,\n      Digital Ocean, and OWASP. These rulesets demonstrate real-world API governance\n      practices and can be extended or adopted by other organizations.\n    humanURL: https://spotlight-rules.com/\n    tags:\n      - Governance\n      - Community\n      - Standards\n      - OpenAPI\n    properties:\n      - type: Reference\n        url: https://github.com/adidas/api-guidelines\n      - type: Reference\n        url: https://github.com/Azure/azure-api-style-guide\n      - type: Reference\n        url: https://github.com/digitalocean/openapi\n      - type: Reference\n        url: https://github.com/stoplightio/spectral-owasp-ruleset\n\
  \ncommon:\n  - type: Website\n    url: https://spotlight-rules.com/\n  - type: Standards\n    url: https://github.com/api-evangelist/standards/standards.yml\n  - type: GitHub\n    url: https://github.com/api-evangelist/spotlight-rules\n  - type: Email\n    url: mailto:kin@apievangelist.com\n  - type: LinkedIn\n    url: https://www.linkedin.com/in/kinlane/\n  - type: JSONSchema\n    url: json-schema/spectral-rule-schema.json\n  - type: JSONSchema\n    url: json-schema/vacuum-rule-schema.json\n  - type: Vocabulary\n    url: vocabulary/spotlight-rules-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    X-github: kinlane\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/api-evangelist-standards/refs/heads/main/apis.yml
tags:
- API Governance
- Linting
- Spectral
- Vacuum
- OpenAPI
- Standards
url: https://raw.githubusercontent.com/api-evangelist/spotlight-rules/refs/heads/main/apis.yml
use_cases: []
---
