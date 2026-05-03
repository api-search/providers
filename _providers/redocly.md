---
api_count: 6
apis:
- description: Redocly Realm is a comprehensive API lifecycle management platform that combines Redoc, Revel, and Reef into a single integrated product. Realm includes API documentation, mock servers, linting, catal
  name: Redocly Realm
  slug: redocly-realm
- description: Redocly Reunite is a collaboration and deployment tool that prepares, deploys, and hosts documentation projects and mock servers in a Git-connected way. Provides Webview for uncommitted previews, Bran
  name: Redocly Reunite
  slug: redocly-reunite
- description: Redocly Revel is an external developer showcase that renders Markdown, Markdoc, and React pages with multi-product and localization capabilities, enabling organizations to create polished developer-fa
  name: Redocly Revel
  slug: redocly-revel
- description: Redocly Reef is an internal service catalog and API governance platform that organizes, aids discovery, and monitors APIs throughout their lifecycle. Reef includes Catalog for organizing and searching
  name: Redocly Reef
  slug: redocly-reef
- description: Redoc is the open-source engine that renders API reference documentation from OpenAPI definitions with unmatched clarity and usability. Supports OpenAPI 3.2, 3.1, 3.0 and OpenAPI 2.0 (legacy Swagger).
  name: Redocly Redoc
  slug: redocly-redoc
- description: Redocly CLI is an open-source command-line tool for working with OpenAPI descriptions, developer portals, and other API lifecycle operations. Supports linting, validation, bundling, splitting, and dec
  name: Redocly CLI
  slug: redocly-cli
common:
- title: ''
  type: Documentation
  url: https://redocly.com/docs
- title: ''
  type: Customers
  url: https://redocly.com/customers
- title: ''
  type: Pricing
  url: https://redocly.com/pricing
- title: ''
  type: Blog
  url: https://redocly.com/blog
- title: ''
  type: Webinars
  url: https://redocly.com/webinars
- title: ''
  type: Security
  url: https://redocly.com/security
- title: ''
  type: Status
  url: https://status.redocly.com/
- title: ''
  type: ServiceLevelAgreement
  url: https://redocly.com/sla
- title: ''
  type: CLI
  url: https://redocly.com/redocly-cli
- title: ''
  type: About
  url: https://redocly.com/about
- title: ''
  type: Support
  url: https://redocly.com/contact-us
- title: ''
  type: Products
  url: https://redocly.com/products
- title: ''
  type: Login
  url: https://auth.cloud.redocly.com/login
- title: ''
  type: SignUp
  url: https://redocly.com/billing/signup
- title: ''
  type: PrivacyPolicy
  url: https://redocly.com/privacy-notice
- title: ''
  type: TermsOfService
  url: https://redocly.com/subscription-agreement
- title: ''
  type: Careers
  url: https://redocly.com/careers
- title: ''
  type: GitHubOrg
  url: https://github.com/Redocly
- title: ''
  type: X
  url: https://twitter.com/Redocly
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/redocly
- title: ''
  type: Governance
  url: https://redocly.com/api-governance
- title: ''
  type: Changelog
  url: https://redocly.com/docs/realm/changelog
- title: ''
  type: VulnerabilityDisclosure
  url: https://redocly.com/vulnerability-disclosure-policy
- title: ''
  type: DataProcessingAddendum
  url: https://redocly.com/dpa
- title: ''
  type: Pricing
  url: https://redocly.com/startup-discount
- title: ''
  type: Reference
  url: https://redocly.com/reference
created: '2026-01-05'
description: Redocly is a company that specializes in API documentation and governance tools. Their platform helps organizations create, manage, and publish API documentation through Realm (their integrated lifecycle platform), Revel (developer portal), Reef (internal catalog and scorecard), and Redoc (open-source OpenAPI renderer). The Redocly CLI provides linting, bundling, splitting, decoration, and documentation generation for OpenAPI, AsyncAPI, and Arazzo specifications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Redocly Context
  property_count: 4
  slug: redocly-context
layout: provider
modified: '2026-05-02'
name: Redocly
skills: []
slug: redocly
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: redocly\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/redocly/refs/heads/main/apis.yml\nname: Redocly\ndescription: >-\n  Redocly is a company that specializes in API documentation and governance\n  tools. Their platform helps organizations create, manage, and publish API\n  documentation through Realm (their integrated lifecycle platform), Revel\n  (developer portal), Reef (internal catalog and scorecard), and Redoc\n  (open-source OpenAPI renderer). The Redocly CLI provides linting, bundling,\n  splitting, decoration, and documentation generation for OpenAPI, AsyncAPI,\n  and Arazzo specifications.\ntags:\n  - API Catalog\n  - API Documentation\n  - Developer Portal\n  - Governance\n  - Linting\n  - OpenAPI\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-01-05'\nmodified: '2026-05-02'\nposition: Consumer\nsegments:\n  - Documentation\nspecificationVersion: '0.19'\napis:\n\
  \  - aid: redocly:redocly-realm\n    name: Redocly Realm\n    description: >-\n      Redocly Realm is a comprehensive API lifecycle management platform that\n      combines Redoc, Revel, and Reef into a single integrated product. Realm\n      includes API documentation, mock servers, linting, catalog, scorecard,\n      API functions, markdown docs, API Scout for discovering hidden or\n      duplicate APIs, and dynamic client registration features.\n    humanURL: https://redocly.com/realm\n    tags:\n      - API Catalog\n      - Developer Portal\n      - Documentation\n    properties:\n      - type: Documentation\n        url: https://redocly.com/docs/realm\n      - type: Changelog\n        url: https://redocly.com/docs/realm/changelog\n\n  - aid: redocly:redocly-reunite\n    name: Redocly Reunite\n    description: >-\n      Redocly Reunite is a collaboration and deployment tool that prepares,\n      deploys, and hosts documentation projects and mock servers in a\n      Git-connected way.\
  \ Provides Webview for uncommitted previews, Branch\n      Previews for committed work-in-progress, and automated GitOps production\n      releases. Integrates with GitHub, GitLab, and Azure DevOps.\n    humanURL: https://redocly.com/docs/realm\n    tags:\n      - Collaboration\n      - Deployment\n      - Documentation\n      - GitOps\n    properties:\n      - type: Documentation\n        url: https://redocly.com/docs/realm\n\n  - aid: redocly:redocly-revel\n    name: Redocly Revel\n    description: >-\n      Redocly Revel is an external developer showcase that renders Markdown,\n      Markdoc, and React pages with multi-product and localization capabilities,\n      enabling organizations to create polished developer-facing portals and\n      documentation experiences for external API consumers.\n    humanURL: https://redocly.com/docs/realm\n    tags:\n      - Developer Portal\n      - Documentation\n      - Localization\n    properties:\n      - type: Documentation\n        url: https://redocly.com/docs/realm\n\
  \n  - aid: redocly:redocly-reef\n    name: Redocly Reef\n    description: >-\n      Redocly Reef is an internal service catalog and API governance platform\n      that organizes, aids discovery, and monitors APIs throughout their\n      lifecycle. Reef includes Catalog for organizing and searching APIs,\n      Scorecard for running linting rules against APIs, API Scout for\n      discovering hidden APIs, and developer onboarding with dynamic client\n      registration.\n    humanURL: https://redocly.com/reef\n    tags:\n      - API Catalog\n      - Governance\n      - Scorecard\n    properties:\n      - type: Documentation\n        url: https://redocly.com/reef\n      - type: Reference\n        url: https://redocly.com/docs/realm/config/scorecard\n\n  - aid: redocly:redocly-redoc\n    name: Redocly Redoc\n    description: >-\n      Redoc is the open-source engine that renders API reference documentation\n      from OpenAPI definitions with unmatched clarity and usability. Supports\n  \
  \    OpenAPI 3.2, 3.1, 3.0 and OpenAPI 2.0 (legacy Swagger). Available as a\n      CLI tool, HTML tag, React component, and Docker image with over 23,000\n      GitHub stars.\n    humanURL: https://redocly.com/redoc\n    tags:\n      - Documentation\n      - OpenAPI\n      - Reference\n    properties:\n      - type: Documentation\n        url: https://redocly.com/docs/redoc\n      - type: Reference\n        url: https://redocly.com/redoc\n      - type: GitHubOrg\n        url: https://github.com/Redocly/redoc\n\n  - aid: redocly:redocly-cli\n    name: Redocly CLI\n    description: >-\n      Redocly CLI is an open-source command-line tool for working with OpenAPI\n      descriptions, developer portals, and other API lifecycle operations.\n      Supports linting, validation, bundling, splitting, and decorating OpenAPI\n      files. Supports OpenAPI 3.2, 3.1, 3.0 and OpenAPI 2.0, AsyncAPI 3.0\n      and 2.6, and Arazzo 1.0. Provides built-in rulesets including spec,\n      recommended, minimal,\
  \ and recommended-strict.\n    humanURL: https://redocly.com/redocly-cli\n    tags:\n      - CLI\n      - Governance\n      - Linting\n      - OpenAPI\n    properties:\n      - type: Documentation\n        url: https://redocly.com/docs/cli\n      - type: Reference\n        url: https://redocly.com/docs/cli/commands/lint\n      - type: Changelog\n        url: https://redocly.com/docs/cli/changelog\n      - type: GitHubOrg\n        url: https://github.com/Redocly/redocly-cli\n      - type: JSONSchema\n        url: json-schema/redocly-config-schema.json\n      - type: JSONSchema\n        url: json-schema/redocly-lint-result-schema.json\n      - type: JSONStructure\n        url: json-structure/redocly-config-structure.json\n      - type: JSONStructure\n        url: json-structure/redocly-lint-result-structure.json\n      - type: JSONLd\n        url: json-ld/redocly-context.jsonld\n      - type: Vocabulary\n        url: vocabulary/redocly-vocabulary.yml\n\ncommon:\n  - name: About Redocly Documentation\n\
  \    url: https://redocly.com/docs\n    type: Documentation\n  - name: Customers\n    url: https://redocly.com/customers\n    type: Customers\n  - name: Pricing\n    url: https://redocly.com/pricing\n    type: Pricing\n  - name: Redocly Blog\n    url: https://redocly.com/blog\n    type: Blog\n  - name: Webinars\n    url: https://redocly.com/webinars\n    type: Webinars\n  - name: Security at Redocly\n    url: https://redocly.com/security\n    type: Security\n  - name: Redocly Status Page\n    url: https://status.redocly.com/\n    type: Status\n  - name: Service Level Agreement\n    url: https://redocly.com/sla\n    type: ServiceLevelAgreement\n  - name: Redocly CLI\n    url: https://redocly.com/redocly-cli\n    type: CLI\n  - name: About Redocly\n    url: https://redocly.com/about\n    type: About\n  - name: Contact Redocly\n    url: https://redocly.com/contact-us\n    type: Support\n  - name: Redocly Products\n    url: https://redocly.com/products\n    type: Products\n  - name: Redocly\
  \ Login\n    url: https://auth.cloud.redocly.com/login\n    type: Login\n  - name: Redocly Sign Up\n    url: https://redocly.com/billing/signup\n    type: SignUp\n  - name: Redocly Privacy Notice\n    url: https://redocly.com/privacy-notice\n    type: PrivacyPolicy\n  - name: Redocly Subscription Agreement\n    url: https://redocly.com/subscription-agreement\n    type: TermsOfService\n  - name: Redocly Careers\n    url: https://redocly.com/careers\n    type: Careers\n  - name: Redocly on GitHub\n    url: https://github.com/Redocly\n    type: GitHubOrg\n  - name: Redocly on X\n    url: https://twitter.com/Redocly\n    type: X\n  - name: Redocly on LinkedIn\n    url: https://www.linkedin.com/company/redocly\n    type: LinkedIn\n  - name: Redocly API Governance\n    url: https://redocly.com/api-governance\n    type: Governance\n  - name: Redocly Changelog\n    url: https://redocly.com/docs/realm/changelog\n    type: Changelog\n  - name: Redocly Vulnerability Disclosure Policy\n    url: https://redocly.com/vulnerability-disclosure-policy\n\
  \    type: VulnerabilityDisclosure\n  - name: Redocly Data Processing Addendum\n    url: https://redocly.com/dpa\n    type: DataProcessingAddendum\n  - name: Redocly Startup Discount\n    url: https://redocly.com/startup-discount\n    type: Pricing\n  - name: Redocly OpenAPI Reference Docs\n    url: https://redocly.com/reference\n    type: Reference\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/redocly/refs/heads/main/apis.yml
tags:
- API Catalog
- API Documentation
- Developer Portal
- Governance
- Linting
- OpenAPI
url: https://raw.githubusercontent.com/api-evangelist/redocly/refs/heads/main/apis.yml
use_cases: []
---
