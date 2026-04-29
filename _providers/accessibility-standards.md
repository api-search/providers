---
api_count: 6
apis:
- description: The current stable web accessibility standard published by the W3C Accessibility Guidelines Working Group (AG WG). WCAG 2.2 comprises 13 guidelines organized under four principles (perceivable, operab
  name: Web Content Accessibility Guidelines (WCAG) 2.2
  slug: ''
- description: Accessible Rich Internet Applications (WAI-ARIA) 1.2 is a W3C Recommendation (June 2023) that defines semantic attributes enabling assistive technologies to interpret dynamic web content and complex i
  name: WAI-ARIA 1.2
  slug: ''
- description: 'ATAG 2.0 is a W3C Recommendation that defines standards for making authoring tools (CMSes, code editors, web-based tools) accessible to authors with disabilities, and for helping those tools generate '
  name: Authoring Tool Accessibility Guidelines (ATAG) 2.0
  slug: ''
- description: UAAG 2.0 is a W3C standard for browsers, browser extensions, media players, and other user agents that render web content. It defines how user agents should make web content accessible to users with d
  name: User Agent Accessibility Guidelines (UAAG) 2.0
  slug: ''
- description: Section 508 of the Rehabilitation Act requires U.S. federal agencies to ensure their information and communication technology (ICT) is accessible to people with disabilities. The Revised 508 Standards
  name: Section 508
  slug: ''
- description: ACT Rules Format 1.1 (W3C Recommendation, February 2026) establishes a standardized format for documenting accessibility conformance testing rules. The framework supports automated, semi-automated, an
  name: Accessibility Conformance Testing (ACT) Rules Format 1.1
  slug: ''
common:
- title: ''
  type: Website
  url: https://www.w3.org/WAI/standards-guidelines/
- title: W3C GitHub Organization
  type: GitHubOrganization
  url: https://github.com/w3c
- title: W3C Accessibility Evaluation Tools List
  type: Tools
  url: https://www.w3.org/WAI/test-evaluate/tools/list/
- title: axe-core Accessibility Testing Engine
  type: Tools
  url: https://github.com/dequelabs/axe-core
- title: Pa11y Automated Accessibility Testing
  type: Tools
  url: https://github.com/pa11y/pa11y
- title: Accessibility Standards JSON-LD Context
  type: JSON-LD
  url: https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/json-ld/accessibility-standards-context.jsonld
- title: Accessibility Standards Vocabulary
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/vocabulary/accessibility-standards-vocabulary.yaml
created: '2025-01-01'
description: Guidelines and technical specifications that ensure digital content, applications, and technologies are usable by people with disabilities, including standards like WCAG, Section 508, and ARIA. These standards help organizations meet regulatory requirements and demonstrate accountability to stakeholders.
features:
- description: Standards requiring that information and user interface components be presentable to users in ways they can perceive, including text alternatives for non-text content.
  name: Perceivable Content
- description: Standards ensuring that user interface components and navigation are operable, including keyboard accessibility and sufficient time limits.
  name: Operable Interface
- description: Standards ensuring that information and the operation of the user interface is understandable, including readable text and predictable navigation.
  name: Understandable Information
- description: Standards requiring that content be robust enough to be reliably interpreted by a wide variety of user agents, including assistive technologies.
  name: Robust Technology
- description: Three-tiered conformance model (Level A, AA, AAA) providing graduated accessibility requirements for organizations to target.
  name: Conformance Levels
- description: ACT Rules Framework providing standardized, machine-readable rules for automated accessibility conformance testing.
  name: Automated Testing Rules
image: /assets/icons/accessibility-standards.png
integrations:
- description: Open-source accessibility testing engine by Deque Systems implementing WCAG 2.0/2.1/2.2 rules, integrates with browsers, testing frameworks, and CI tools.
  name: axe-core
- description: Open-source Node.js tool for automated accessibility testing against WCAG standards, integrates with GitHub Actions and CI/CD pipelines.
  name: Pa11y
- description: GSA's Government-wide IT Accessibility Program providing guidance, training, and resources for federal Section 508 compliance.
  name: Section508.gov
- description: European standard referencing WCAG 2.1 AA, applicable to public and private sector digital services in EU member states.
  name: EU Accessibility Act / EN 301 549
- description: International Standards Organization adoption of WCAG 2.2, enabling global regulatory alignment with the W3C standard.
  name: ISO/IEC 40500:2025
jsonld:
- class_count: 7
  name: Accessibility Standards Context
  property_count: 24
  slug: accessibility-standards-context
layout: provider
modified: '2026-04-19'
name: Accessibility Standards
skills: []
slug: accessibility-standards
solutions: []
source_yaml: "aid: accessibility-standards\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/apis.yml\nname: Accessibility Standards\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Accessibility\n  - Compliance\n  - UX\n  - Web Standards\n  - WCAG\n  - ARIA\n  - Section 508\n  - Disability\ndescription: >-\n  Guidelines and technical specifications that ensure digital content,\n  applications, and technologies are usable by people with disabilities,\n  including standards like WCAG, Section 508, and ARIA. These standards help\n  organizations meet regulatory requirements and demonstrate accountability\n  to stakeholders.\ncreated: '2025-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - name: Web Content Accessibility Guidelines (WCAG) 2.2\n    description: >-\n      The current stable web accessibility standard published by the W3C\n      Accessibility Guidelines\
  \ Working Group (AG WG). WCAG 2.2 comprises 13\n      guidelines organized under four principles (perceivable, operable,\n      understandable, robust) with success criteria at three levels: A, AA, and\n      AAA. It has been adopted as ISO/IEC 40500:2025 and is referenced by\n      Section 508 and the EU Accessibility Act.\n    humanURL: https://www.w3.org/WAI/standards-guidelines/wcag/\n    baseURL: https://www.w3.org/TR/WCAG22/\n    tags:\n      - WCAG\n      - Web Content\n      - Accessibility\n      - W3C\n      - ISO\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/WAI/standards-guidelines/wcag/\n      - type: Specification\n        url: https://www.w3.org/TR/WCAG22/\n      - type: Documentation\n        url: https://www.w3.org/WAI/WCAG22/quickref/\n        title: WCAG 2.2 Quick Reference\n      - type: GitHubRepository\n        url: https://github.com/w3c/wcag\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/json-schema/wcag-success-criterion-schema.json\n\
  \        title: WCAG Success Criterion Schema\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/json-schema/wcag-conformance-report-schema.json\n        title: WCAG Conformance Report Schema\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/json-structure/wcag-success-criterion-structure.json\n        title: WCAG Success Criterion Structure\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/json-structure/wcag-conformance-report-structure.json\n        title: WCAG Conformance Report Structure\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/examples/wcag-success-criterion-example.json\n        title: WCAG Success Criterion\
  \ Example\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/examples/wcag-conformance-report-example.json\n        title: WCAG Conformance Report Example\n  - name: WAI-ARIA 1.2\n    description: >-\n      Accessible Rich Internet Applications (WAI-ARIA) 1.2 is a W3C\n      Recommendation (June 2023) that defines semantic attributes enabling\n      assistive technologies to interpret dynamic web content and complex\n      interfaces. The suite includes Core Accessibility API Mappings, Accessible\n      Name and Description Computation, and HTML/SVG API Mappings.\n    humanURL: https://www.w3.org/WAI/standards-guidelines/aria/\n    baseURL: https://www.w3.org/TR/wai-aria-1.2/\n    tags:\n      - ARIA\n      - Semantic\n      - Screen Reader\n      - W3C\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/WAI/standards-guidelines/aria/\n      - type: Specification\n      \
  \  url: https://www.w3.org/TR/wai-aria-1.2/\n      - type: Documentation\n        url: https://www.w3.org/WAI/ARIA/apg/\n        title: ARIA Authoring Practices Guide\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/json-schema/aria-role-schema.json\n        title: ARIA Role Schema\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/json-structure/aria-role-structure.json\n        title: ARIA Role Structure\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/examples/aria-role-example.json\n        title: ARIA Role Example\n  - name: Authoring Tool Accessibility Guidelines (ATAG) 2.0\n    description: >-\n      ATAG 2.0 is a W3C Recommendation that defines standards for making\n      authoring tools (CMSes, code editors,\
  \ web-based tools) accessible to\n      authors with disabilities, and for helping those tools generate accessible\n      content.\n    humanURL: https://www.w3.org/WAI/standards-guidelines/atag/\n    baseURL: https://www.w3.org/TR/ATAG/\n    tags:\n      - ATAG\n      - Authoring Tools\n      - W3C\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/WAI/standards-guidelines/atag/\n      - type: Specification\n        url: https://www.w3.org/TR/ATAG/\n  - name: User Agent Accessibility Guidelines (UAAG) 2.0\n    description: >-\n      UAAG 2.0 is a W3C standard for browsers, browser extensions, media\n      players, and other user agents that render web content. It defines how\n      user agents should make web content accessible to users with disabilities\n      either directly or in conjunction with assistive technologies.\n    humanURL: https://www.w3.org/WAI/standards-guidelines/uaag/\n    baseURL: https://www.w3.org/TR/UAAG20/\n    tags:\n      - UAAG\n\
  \      - Browsers\n      - User Agents\n      - W3C\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/WAI/standards-guidelines/uaag/\n      - type: Specification\n        url: https://www.w3.org/TR/UAAG20/\n  - name: Section 508\n    description: >-\n      Section 508 of the Rehabilitation Act requires U.S. federal agencies to\n      ensure their information and communication technology (ICT) is accessible\n      to people with disabilities. The Revised 508 Standards (effective January\n      18, 2017) incorporate WCAG 2.0 Level A and AA success criteria for web\n      and electronic content across seven chapters of requirements.\n    humanURL: https://www.access-board.gov/ict/\n    baseURL: https://www.section508.gov/\n    tags:\n      - Section 508\n      - Federal\n      - Government\n      - US Law\n      - ICT\n    properties:\n      - type: Documentation\n        url: https://www.access-board.gov/ict/\n      - type: Documentation\n        url: https://www.section508.gov/develop/web-content/\n\
  \        title: Section 508 Web Content Development Guidance\n  - name: Accessibility Conformance Testing (ACT) Rules Format 1.1\n    description: >-\n      ACT Rules Format 1.1 (W3C Recommendation, February 2026) establishes a\n      standardized format for documenting accessibility conformance testing\n      rules. The framework supports automated, semi-automated, and manual\n      testing and is used to create transparent, interoperable accessibility\n      testing methodologies aligned with WCAG.\n    humanURL: https://www.w3.org/WAI/standards-guidelines/act/\n    baseURL: https://www.w3.org/TR/act-rules-format/\n    tags:\n      - ACT\n      - Testing\n      - Conformance\n      - W3C\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/WAI/standards-guidelines/act/\n      - type: Specification\n        url: https://www.w3.org/TR/act-rules-format/\n      - type: GitHubRepository\n        url: https://github.com/w3c/wcag-act-rules\n        title: WCAG ACT\
  \ Rules Repository\ncommon:\n  - type: Website\n    url: https://www.w3.org/WAI/standards-guidelines/\n  - type: GitHubOrganization\n    url: https://github.com/w3c\n    title: W3C GitHub Organization\n  - type: Tools\n    url: https://www.w3.org/WAI/test-evaluate/tools/list/\n    title: W3C Accessibility Evaluation Tools List\n  - type: Tools\n    url: https://github.com/dequelabs/axe-core\n    title: axe-core Accessibility Testing Engine\n  - type: Tools\n    url: https://github.com/pa11y/pa11y\n    title: Pa11y Automated Accessibility Testing\n  - type: JSON-LD\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/json-ld/accessibility-standards-context.jsonld\n    title: Accessibility Standards JSON-LD Context\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/vocabulary/accessibility-standards-vocabulary.yaml\n    title: Accessibility Standards Vocabulary\n\
  \  - type: Features\n    data:\n      - name: Perceivable Content\n        description: >-\n          Standards requiring that information and user interface components be\n          presentable to users in ways they can perceive, including text\n          alternatives for non-text content.\n      - name: Operable Interface\n        description: >-\n          Standards ensuring that user interface components and navigation are\n          operable, including keyboard accessibility and sufficient time limits.\n      - name: Understandable Information\n        description: >-\n          Standards ensuring that information and the operation of the user\n          interface is understandable, including readable text and predictable\n          navigation.\n      - name: Robust Technology\n        description: >-\n          Standards requiring that content be robust enough to be reliably\n          interpreted by a wide variety of user agents, including assistive\n          technologies.\n  \
  \    - name: Conformance Levels\n        description: >-\n          Three-tiered conformance model (Level A, AA, AAA) providing graduated\n          accessibility requirements for organizations to target.\n      - name: Automated Testing Rules\n        description: >-\n          ACT Rules Framework providing standardized, machine-readable rules for\n          automated accessibility conformance testing.\n  - type: UseCases\n    data:\n      - name: Web Application Accessibility Auditing\n        description: >-\n          Using WCAG 2.2 success criteria and ACT rules to audit web\n          applications for accessibility compliance.\n      - name: Federal Government ICT Procurement\n        description: >-\n          Applying Section 508 standards when procuring or developing\n          information and communication technology for U.S. federal agencies.\n      - name: Accessible Rich Internet Application Development\n        description: >-\n          Using WAI-ARIA attributes to make\
  \ dynamic JavaScript-driven\n          interfaces accessible to screen readers and assistive technologies.\n      - name: Automated CI/CD Accessibility Testing\n        description: >-\n          Integrating axe-core or Pa11y into continuous integration pipelines\n          to catch accessibility regressions automatically.\n      - name: Regulatory Compliance Documentation\n        description: >-\n          Producing Voluntary Product Accessibility Templates (VPATs) and\n          Accessibility Conformance Reports aligned with Section 508 and WCAG.\n  - type: Integrations\n    data:\n      - name: axe-core\n        description: >-\n          Open-source accessibility testing engine by Deque Systems implementing\n          WCAG 2.0/2.1/2.2 rules, integrates with browsers, testing frameworks,\n          and CI tools.\n      - name: Pa11y\n        description: >-\n          Open-source Node.js tool for automated accessibility testing against\n          WCAG standards, integrates with GitHub\
  \ Actions and CI/CD pipelines.\n      - name: Section508.gov\n        description: >-\n          GSA's Government-wide IT Accessibility Program providing guidance,\n          training, and resources for federal Section 508 compliance.\n      - name: EU Accessibility Act / EN 301 549\n        description: >-\n          European standard referencing WCAG 2.1 AA, applicable to public and\n          private sector digital services in EU member states.\n      - name: ISO/IEC 40500:2025\n        description: >-\n          International Standards Organization adoption of WCAG 2.2, enabling\n          global regulatory alignment with the W3C standard.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/apis.yml
tags:
- Accessibility
- Compliance
- UX
- Web Standards
- WCAG
- ARIA
- Section 508
- Disability
url: https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/apis.yml
use_cases:
- description: Using WCAG 2.2 success criteria and ACT rules to audit web applications for accessibility compliance.
  name: Web Application Accessibility Auditing
- description: Applying Section 508 standards when procuring or developing information and communication technology for U.S. federal agencies.
  name: Federal Government ICT Procurement
- description: Using WAI-ARIA attributes to make dynamic JavaScript-driven interfaces accessible to screen readers and assistive technologies.
  name: Accessible Rich Internet Application Development
- description: Integrating axe-core or Pa11y into continuous integration pipelines to catch accessibility regressions automatically.
  name: Automated CI/CD Accessibility Testing
- description: Producing Voluntary Product Accessibility Templates (VPATs) and Accessibility Conformance Reports aligned with Section 508 and WCAG.
  name: Regulatory Compliance Documentation
---
