---
api_count: 4
apis:
- description: Web Content Accessibility Guidelines 2.2, the current stable version and ISO/IEC 40500:2025 standard. Introduces 9 new success criteria beyond WCAG 2.1, including focus appearance, dragging movements,
  name: WCAG 2.2
  slug: wcag-2-2
- description: W3C Accessibility Guidelines 3.0 (working draft), expanding scope beyond web content to cover mobile apps, VR, authoring tools, and digital documents. Introduces outcome-based testing and a new scorin
  name: WCAG 3.0
  slug: wcag-3-0
- description: Accessible Rich Internet Applications (WAI-ARIA) 1.2 specification providing semantic roles, states, and properties for accessible user interface components. Includes API mappings for browsers and ass
  name: WAI-ARIA
  slug: wai-aria
- description: ACT Rules provide machine-executable rules for testing WCAG 2.x conformance, enabling consistent automated and manual accessibility evaluation across tools and methodologies.
  name: Accessibility Conformance Testing (ACT) Rules
  slug: act-rules
common:
- title: W3C Web Accessibility Initiative
  type: Website
  url: https://www.w3.org/WAI/
- title: W3C Accessibility Standards Overview
  type: Documentation
  url: https://www.w3.org/WAI/standards-guidelines/
- title: W3C GitHub Organization
  type: GitHubOrganization
  url: https://github.com/w3c
- title: Web Accessibility Evaluation Tools List
  type: Tools
  url: https://www.w3.org/WAI/test-evaluate/tools/list/
- title: WCAG-EM Report Tool
  type: Tools
  url: https://github.com/w3c/wcag-em-report-tool
- title: WCAG Vocabulary
  type: Vocabulary
  url: vocabulary/wcag-vocabulary.yml
- title: WCAG JSON-LD Context
  type: JSON-LD
  url: json-ld/wcag-context.jsonld
created: '2025'
description: Web Content Accessibility Guidelines (WCAG) are a set of international standards published by the W3C Web Accessibility Initiative (WAI) for making web content accessible to people with disabilities. WCAG covers a wide range of recommendations across four principles (Perceivable, Operable, Understandable, Robust), with conformance levels A, AA, and AAA. WCAG 2.2 (ISO/IEC 40500:2025) is the current standard, while WCAG 3.0 is in active development targeting broader coverage of websites, mobile apps, VR environments, and digital documents.
features:
- description: 'WCAG 2.x guidelines are organized around four principles: Perceivable (information must be presentable to users), Operable (UI must be navigable), Understandable (content must be comprehensible), and Robust (content must be interpretable by assistive technologies).'
  name: Four Accessibility Principles (POUR)
- description: Success criteria are classified as Level A (minimum), Level AA (standard), and Level AAA (enhanced), enabling graduated implementation roadmaps.
  name: Three Conformance Levels
- description: Each guideline contains specific, testable success criteria that provide a clear pass/fail basis for accessibility evaluation and legal compliance.
  name: Testable Success Criteria
- description: Machine-executable ACT Rules enable consistent automated testing of WCAG conformance across multiple evaluation tools.
  name: ACT Rules Integration
- description: Extensive documentation of sufficient techniques, advisory techniques, and common failures for implementing and evaluating each success criterion.
  name: Techniques and Failures Documentation
- description: WCAG 3.0 introduces a scoring-based conformance model with outcomes replacing binary pass/fail for more nuanced accessibility assessment.
  name: WCAG 3.0 Outcome-Based Model
image: ''
integrations:
- description: Popular open-source accessibility testing engine that maps test rules to WCAG success criteria.
  name: axe-core
- description: Web Accessibility Evaluation Tool that visually highlights WCAG issues on web pages.
  name: WAVE
- description: Google Lighthouse includes accessibility audits mapped to WCAG criteria.
  name: Lighthouse
- description: Screen readers that implement WAI-ARIA API mappings to communicate accessible rich web content to blind and low-vision users.
  name: NVDA and JAWS
- description: WCAG 2.2 is identical to ISO/IEC 40500:2025, enabling reference in international procurement and regulatory requirements.
  name: ISO/IEC 40500
jsonld:
- class_count: 6
  name: Wcag Context
  property_count: 19
  slug: wcag-context
layout: provider
modified: '2026-05-03'
name: WCAG
skills: []
slug: wcag
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wcag\nname: WCAG\ndescription: >-\n  Web Content Accessibility Guidelines (WCAG) are a set of international\n  standards published by the W3C Web Accessibility Initiative (WAI) for making\n  web content accessible to people with disabilities. WCAG covers a wide range\n  of recommendations across four principles (Perceivable, Operable,\n  Understandable, Robust), with conformance levels A, AA, and AAA. WCAG 2.2\n  (ISO/IEC 40500:2025) is the current standard, while WCAG 3.0 is in active\n  development targeting broader coverage of websites, mobile apps, VR\n  environments, and digital documents.\ntype: Index\nurl: https://www.w3.org/WAI/standards-guidelines/wcag/\ntags:\n  - Accessibility\n  - W3C\n  - WCAG\n  - Web Standards\n  - Disability\n  - Inclusive Design\ncreated: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: wcag:wcag-2-2\n    name: WCAG 2.2\n    description: >-\n      Web Content Accessibility Guidelines 2.2, the current stable\
  \ version and\n      ISO/IEC 40500:2025 standard. Introduces 9 new success criteria beyond\n      WCAG 2.1, including focus appearance, dragging movements, and consistent\n      help. Organized into four principles: Perceivable, Operable,\n      Understandable, and Robust (POUR).\n    humanURL: https://www.w3.org/TR/WCAG22/\n    tags:\n      - WCAG 2.2\n      - Accessibility\n      - Web Standards\n      - ISO\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/WCAG22/\n        title: WCAG 2.2 Specification\n      - type: Documentation\n        url: https://www.w3.org/WAI/WCAG22/quickref/\n        title: WCAG 2.2 Quick Reference\n      - type: Documentation\n        url: https://github.com/w3c/wcag\n        title: WCAG GitHub Repository\n      - type: JSONSchema\n        url: json-schema/wcag-success-criterion-schema.json\n        title: Success Criterion Schema\n      - type: JSONSchema\n        url: json-schema/wcag-conformance-claim-schema.json\n      \
  \  title: Conformance Claim Schema\n      - type: JSONStructure\n        url: json-structure/wcag-success-criterion-structure.json\n        title: Success Criterion Structure\n      - type: JSONStructure\n        url: json-structure/wcag-conformance-claim-structure.json\n        title: Conformance Claim Structure\n  - aid: wcag:wcag-3-0\n    name: WCAG 3.0\n    description: >-\n      W3C Accessibility Guidelines 3.0 (working draft), expanding scope beyond\n      web content to cover mobile apps, VR, authoring tools, and digital\n      documents. Introduces outcome-based testing and a new scoring model.\n      Working Draft published January 2026; Candidate Recommendation targeted\n      Q4 2027.\n    humanURL: https://www.w3.org/WAI/standards-guidelines/wcag/wcag3-intro/\n    tags:\n      - WCAG 3.0\n      - Accessibility\n      - Web Standards\n      - Working Draft\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/WAI/standards-guidelines/wcag/wcag3-intro/\n\
  \        title: WCAG 3.0 Introduction\n      - type: Documentation\n        url: https://w3c.github.io/wcag3/guidelines/\n        title: WCAG 3.0 Editor Draft\n      - type: Documentation\n        url: https://github.com/w3c/wcag3\n        title: WCAG 3.0 GitHub Repository\n  - aid: wcag:wai-aria\n    name: WAI-ARIA\n    description: >-\n      Accessible Rich Internet Applications (WAI-ARIA) 1.2 specification\n      providing semantic roles, states, and properties for accessible user\n      interface components. Includes API mappings for browsers and assistive\n      technologies.\n    humanURL: https://www.w3.org/TR/wai-aria/\n    tags:\n      - WAI-ARIA\n      - Accessibility\n      - Semantic Web\n      - User Interface\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/wai-aria/\n        title: WAI-ARIA Specification\n      - type: Documentation\n        url: https://www.w3.org/TR/aria-in-html/\n        title: ARIA in HTML\n      - type: Documentation\n\
  \        url: https://github.com/w3c/aria-practices\n        title: ARIA Authoring Practices GitHub\n  - aid: wcag:act-rules\n    name: Accessibility Conformance Testing (ACT) Rules\n    description: >-\n      ACT Rules provide machine-executable rules for testing WCAG 2.x\n      conformance, enabling consistent automated and manual accessibility\n      evaluation across tools and methodologies.\n    humanURL: https://www.w3.org/WAI/standards-guidelines/act/\n    tags:\n      - ACT Rules\n      - Accessibility Testing\n      - Automated Testing\n      - WCAG\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/WAI/standards-guidelines/act/\n        title: ACT Rules Overview\n      - type: Documentation\n        url: https://act-rules.github.io/\n        title: ACT Rules Community\ncommon:\n  - type: Website\n    url: https://www.w3.org/WAI/\n    title: W3C Web Accessibility Initiative\n  - type: Documentation\n    url: https://www.w3.org/WAI/standards-guidelines/\n\
  \    title: W3C Accessibility Standards Overview\n  - type: GitHubOrganization\n    url: https://github.com/w3c\n    title: W3C GitHub Organization\n  - type: Tools\n    url: https://www.w3.org/WAI/test-evaluate/tools/list/\n    title: Web Accessibility Evaluation Tools List\n  - type: Tools\n    url: https://github.com/w3c/wcag-em-report-tool\n    title: WCAG-EM Report Tool\n  - type: Vocabulary\n    url: vocabulary/wcag-vocabulary.yml\n    title: WCAG Vocabulary\n  - type: JSON-LD\n    url: json-ld/wcag-context.jsonld\n    title: WCAG JSON-LD Context\n  - type: Features\n    data:\n      - name: Four Accessibility Principles (POUR)\n        description: >-\n          WCAG 2.x guidelines are organized around four principles: Perceivable\n          (information must be presentable to users), Operable (UI must be\n          navigable), Understandable (content must be comprehensible), and\n          Robust (content must be interpretable by assistive technologies).\n      - name: Three Conformance\
  \ Levels\n        description: >-\n          Success criteria are classified as Level A (minimum), Level AA\n          (standard), and Level AAA (enhanced), enabling graduated\n          implementation roadmaps.\n      - name: Testable Success Criteria\n        description: >-\n          Each guideline contains specific, testable success criteria that\n          provide a clear pass/fail basis for accessibility evaluation and\n          legal compliance.\n      - name: ACT Rules Integration\n        description: >-\n          Machine-executable ACT Rules enable consistent automated testing of\n          WCAG conformance across multiple evaluation tools.\n      - name: Techniques and Failures Documentation\n        description: >-\n          Extensive documentation of sufficient techniques, advisory techniques,\n          and common failures for implementing and evaluating each success\n          criterion.\n      - name: WCAG 3.0 Outcome-Based Model\n        description: >-\n         \
  \ WCAG 3.0 introduces a scoring-based conformance model with outcomes\n          replacing binary pass/fail for more nuanced accessibility assessment.\n  - type: UseCases\n    data:\n      - name: Legal Compliance\n        description: >-\n          Organizations use WCAG 2.1/2.2 Level AA to meet legal accessibility\n          requirements including ADA, Section 508, EN 301 549, and AODA.\n      - name: Automated Accessibility Testing\n        description: >-\n          Development teams integrate ACT Rules into CI/CD pipelines to\n          automatically catch WCAG violations in web applications.\n      - name: Screen Reader Compatibility\n        description: >-\n          WAI-ARIA roles and properties enable web applications to communicate\n          semantic structure and state to screen readers and assistive\n          technologies.\n      - name: Accessibility Auditing\n        description: >-\n          Accessibility specialists use WCAG criteria as the evaluation\n          framework\
  \ for manual and automated accessibility audits.\n      - name: Inclusive Design\n        description: >-\n          Design and engineering teams reference WCAG guidelines during the\n          design phase to build accessibility in from the start rather than\n          retrofitting.\n  - type: Integrations\n    data:\n      - name: axe-core\n        description: >-\n          Popular open-source accessibility testing engine that maps test\n          rules to WCAG success criteria.\n      - name: WAVE\n        description: >-\n          Web Accessibility Evaluation Tool that visually highlights WCAG\n          issues on web pages.\n      - name: Lighthouse\n        description: >-\n          Google Lighthouse includes accessibility audits mapped to WCAG\n          criteria.\n      - name: NVDA and JAWS\n        description: >-\n          Screen readers that implement WAI-ARIA API mappings to communicate\n          accessible rich web content to blind and low-vision users.\n      - name:\
  \ ISO/IEC 40500\n        description: >-\n          WCAG 2.2 is identical to ISO/IEC 40500:2025, enabling reference in\n          international procurement and regulatory requirements.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wcag/refs/heads/main/apis.yml
tags:
- Accessibility
- W3C
- WCAG
- Web Standards
- Disability
- Inclusive Design
url: https://www.w3.org/WAI/standards-guidelines/wcag/
use_cases:
- description: Organizations use WCAG 2.1/2.2 Level AA to meet legal accessibility requirements including ADA, Section 508, EN 301 549, and AODA.
  name: Legal Compliance
- description: Development teams integrate ACT Rules into CI/CD pipelines to automatically catch WCAG violations in web applications.
  name: Automated Accessibility Testing
- description: WAI-ARIA roles and properties enable web applications to communicate semantic structure and state to screen readers and assistive technologies.
  name: Screen Reader Compatibility
- description: Accessibility specialists use WCAG criteria as the evaluation framework for manual and automated accessibility audits.
  name: Accessibility Auditing
- description: Design and engineering teams reference WCAG guidelines during the design phase to build accessibility in from the start rather than retrofitting.
  name: Inclusive Design
---
