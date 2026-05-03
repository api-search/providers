---
api_count: 10
apis:
- description: The W3C API provides programmatic access to W3C data including specifications, working groups, editors, translations, and affiliations. It enables developers to query W3C's catalog of technical report
  name: W3C API
  slug: w3c-api
- description: WCAG is the international standard for web accessibility, providing guidelines for making web content more accessible to people with disabilities. WCAG 2.2 is the current Recommendation, with WCAG 3.0
  name: Web Content Accessibility Guidelines (WCAG)
  slug: wcag
- description: The HyperText Markup Language specification maintained by WHATWG as a living standard, published as a W3C Recommendation. HTML defines the semantic structure of web pages and forms the foundation of t
  name: HTML Living Standard
  slug: html
- description: The Cascading Style Sheets (CSS) specification family maintained by the W3C CSS Working Group. CSS defines the presentation and styling of HTML documents. Key modules include CSS Grid Layout, Flexbox,
  name: CSS Specifications
  slug: css
- description: JSON-LD (JSON for Linking Data) is a W3C Recommendation for encoding linked data using JSON. It provides a way to add semantic meaning to JSON documents through the use of @context, @id, and @type key
  name: JSON-LD
  slug: json-ld
- description: The Verifiable Credentials Data Model is a W3C Recommendation enabling cryptographically secure, privacy-respecting digital credentials. The VC family includes the data model, data integrity proof sui
  name: Verifiable Credentials
  slug: verifiable-credentials
- description: WebAssembly (Wasm) is a W3C Recommendation defining a portable binary instruction format for a stack-based virtual machine. It enables near-native performance in web browsers for code compiled from la
  name: WebAssembly
  slug: wasm
- description: Accessible Rich Internet Applications (WAI-ARIA) is a W3C Recommendation defining a set of HTML attributes that define ways to make web content and web applications more accessible to people with disa
  name: WAI-ARIA
  slug: aria
- description: The Resource Description Framework (RDF) is a W3C standard for representing information in the web. RDF 1.2 and SPARQL 1.2 are the latest versions, providing the foundation for the semantic web and li
  name: RDF and SPARQL
  slug: rdf
- description: The W3C Digital Credentials API provides browser support for mediating presentation and issuance of digital credentials such as digital identity documents. It enables web applications to request and r
  name: Digital Credentials API
  slug: digital-credentials
common:
- title: ''
  type: Website
  url: https://www.w3.org/
- title: ''
  type: TechnicalReports
  url: https://www.w3.org/TR/
- title: ''
  type: API
  url: https://api.w3.org/
- title: ''
  type: GitHubOrg
  url: https://github.com/w3c/
- title: ''
  type: News
  url: https://www.w3.org/news/
- title: ''
  type: Blog
  url: https://www.w3.org/blog/
- title: ''
  type: Events
  url: https://www.w3.org/events/
- title: ''
  type: Donations
  url: https://www.w3.org/donate/
- title: ''
  type: Mastodon
  url: https://w3c.social/@w3c
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/w3c/
- title: ''
  type: YouTube
  url: https://www.youtube.com/@W3COfficial
- title: ''
  type: Sponsorship
  url: https://www.w3.org/sponsor/
- title: ''
  type: Vocabulary
  url: vocabulary/w3c-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: json-ld/w3c-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/w3c-rules.yml
created: '2025-08-25'
description: The World Wide Web Consortium (W3C) is the main international standards body for the World Wide Web, founded by Tim Berners-Lee in 1994. W3C develops web standards and guidelines to ensure the long-term growth of the Web, focusing on accessibility, internationalization, privacy, and security. W3C specifications include HTML, CSS, XML, SVG, WebAssembly, ARIA, WCAG, JSON-LD, Verifiable Credentials, and hundreds of other foundational web technologies. W3C operates through Working Groups, Interest Groups, and Community Groups that develop specifications through a consensus-based process, resulting in W3C Recommendations.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: W3C Context
  property_count: 19
  slug: w3c-context
layout: provider
modified: '2026-05-03'
name: W3C
rules:
- name: W3C API Rules
  rule_count: 7
  severity_counts:
    error: 0
    hint: 0
    info: 4
    warn: 3
  slug: w3c-rules
skills: []
slug: w3c
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: w3c\nurl: https://raw.githubusercontent.com/api-evangelist/w3c/refs/heads/main/apis.yml\nname: W3C\ndescription: >-\n  The World Wide Web Consortium (W3C) is the main international standards body\n  for the World Wide Web, founded by Tim Berners-Lee in 1994. W3C develops web\n  standards and guidelines to ensure the long-term growth of the Web, focusing\n  on accessibility, internationalization, privacy, and security. W3C specifications\n  include HTML, CSS, XML, SVG, WebAssembly, ARIA, WCAG, JSON-LD, Verifiable\n  Credentials, and hundreds of other foundational web technologies. W3C operates\n  through Working Groups, Interest Groups, and Community Groups that develop\n  specifications through a consensus-based process, resulting in W3C Recommendations.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Accessibility\n  - Standards\n  - Web\n  - Web Standards\ncreated: '2025-08-25'\nmodified: '2026-05-03'\nspecificationVersion:\
  \ '0.19'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\n\napis:\n  - aid: w3c:w3c-api\n    name: W3C API\n    description: >-\n      The W3C API provides programmatic access to W3C data including specifications,\n      working groups, editors, translations, and affiliations. It enables developers\n      to query W3C's catalog of technical reports, discover active working groups,\n      find specification editors and contributors, and access specification version\n      history and status information.\n    humanURL: https://api.w3.org/\n    baseUrl: https://api.w3.org/\n    tags:\n      - API\n      - Data\n      - Specifications\n      - Standards\n      - W3C\n    properties:\n      - url: https://api.w3.org/doc\n        type: Documentation\n      - url: https://api.w3.org/\n        type: BaseURL\n      - url: https://github.com/w3c/w3c-api\n        type: GitHub\n\n  - aid: w3c:wcag\n    name: Web Content Accessibility Guidelines (WCAG)\n    description: >-\n      WCAG is the international\
  \ standard for web accessibility, providing guidelines\n      for making web content more accessible to people with disabilities. WCAG 2.2\n      is the current Recommendation, with WCAG 3.0 in development. Guidelines cover\n      perceivability, operability, understandability, and robustness (POUR).\n    humanURL: https://www.w3.org/TR/WCAG22/\n    tags:\n      - Accessibility\n      - Guidelines\n      - Standards\n      - W3C\n    properties:\n      - url: https://www.w3.org/TR/WCAG22/\n        type: Specification\n      - url: https://www.w3.org/WAI/standards-guidelines/wcag/\n        type: Documentation\n      - url: https://github.com/w3c/wcag\n        type: GitHub\n\n  - aid: w3c:html\n    name: HTML Living Standard\n    description: >-\n      The HyperText Markup Language specification maintained by WHATWG as a living\n      standard, published as a W3C Recommendation. HTML defines the semantic structure\n      of web pages and forms the foundation of the web platform.\n    humanURL:\
  \ https://html.spec.whatwg.org/\n    tags:\n      - HTML\n      - Standards\n      - Web Platform\n    properties:\n      - url: https://html.spec.whatwg.org/\n        type: Specification\n      - url: https://www.w3.org/TR/html52/\n        type: W3C Recommendation\n      - url: https://github.com/whatwg/html\n        type: GitHub\n\n  - aid: w3c:css\n    name: CSS Specifications\n    description: >-\n      The Cascading Style Sheets (CSS) specification family maintained by the W3C\n      CSS Working Group. CSS defines the presentation and styling of HTML documents.\n      Key modules include CSS Grid Layout, Flexbox, Custom Properties, Animations,\n      and CSS Functions and Mixins.\n    humanURL: https://www.w3.org/Style/CSS/\n    tags:\n      - CSS\n      - Standards\n      - Styling\n      - Web Platform\n    properties:\n      - url: https://www.w3.org/TR/CSS/\n        type: Specification\n      - url: https://www.w3.org/Style/CSS/Overview.en.html\n        type: Documentation\n \
  \     - url: https://github.com/w3c/csswg-drafts\n        type: GitHub\n\n  - aid: w3c:json-ld\n    name: JSON-LD\n    description: >-\n      JSON-LD (JSON for Linking Data) is a W3C Recommendation for encoding linked\n      data using JSON. It provides a way to add semantic meaning to JSON documents\n      through the use of @context, @id, and @type keywords, enabling interoperability\n      through shared vocabularies like schema.org.\n    humanURL: https://www.w3.org/TR/json-ld11/\n    tags:\n      - JSON\n      - Linked Data\n      - Semantic Web\n      - Standards\n    properties:\n      - url: https://www.w3.org/TR/json-ld11/\n        type: Specification\n      - url: https://json-ld.org/\n        type: Website\n      - url: https://json-ld.org/playground/\n        type: Playground\n      - url: https://github.com/w3c/json-ld-syntax\n        type: GitHub\n\n  - aid: w3c:verifiable-credentials\n    name: Verifiable Credentials\n    description: >-\n      The Verifiable Credentials\
  \ Data Model is a W3C Recommendation enabling\n      cryptographically secure, privacy-respecting digital credentials. The VC\n      family includes the data model, data integrity proof suites, and JSON Web\n      Token/COSE encoding methods. VC 2.0 was published as a W3C Recommendation\n      in 2025.\n    humanURL: https://www.w3.org/TR/vc-data-model-2.0/\n    tags:\n      - Credentials\n      - Identity\n      - Privacy\n      - Security\n      - Standards\n    properties:\n      - url: https://www.w3.org/TR/vc-data-model-2.0/\n        type: Specification\n      - url: https://www.w3.org/groups/wg/vc/\n        type: Working Group\n      - url: https://github.com/w3c/vc-data-model\n        type: GitHub\n\n  - aid: w3c:wasm\n    name: WebAssembly\n    description: >-\n      WebAssembly (Wasm) is a W3C Recommendation defining a portable binary\n      instruction format for a stack-based virtual machine. It enables near-native\n      performance in web browsers for code compiled from languages\
  \ like C, C++,\n      and Rust, and is a core web platform technology.\n    humanURL: https://www.w3.org/TR/wasm-core-2/\n    tags:\n      - Performance\n      - Standards\n      - WebAssembly\n      - Web Platform\n    properties:\n      - url: https://www.w3.org/TR/wasm-core-2/\n        type: Specification\n      - url: https://webassembly.org/\n        type: Website\n      - url: https://github.com/WebAssembly/spec\n        type: GitHub\n\n  - aid: w3c:aria\n    name: WAI-ARIA\n    description: >-\n      Accessible Rich Internet Applications (WAI-ARIA) is a W3C Recommendation\n      defining a set of HTML attributes that define ways to make web content and\n      web applications more accessible to people with disabilities. ARIA roles,\n      states, and properties supplement HTML semantics for dynamic content.\n    humanURL: https://www.w3.org/TR/wai-aria-1.2/\n    tags:\n      - Accessibility\n      - ARIA\n      - Standards\n      - W3C\n    properties:\n      - url: https://www.w3.org/TR/wai-aria-1.2/\n\
  \        type: Specification\n      - url: https://www.w3.org/WAI/ARIA/\n        type: Documentation\n      - url: https://github.com/w3c/aria\n        type: GitHub\n\n  - aid: w3c:rdf\n    name: RDF and SPARQL\n    description: >-\n      The Resource Description Framework (RDF) is a W3C standard for representing\n      information in the web. RDF 1.2 and SPARQL 1.2 are the latest versions,\n      providing the foundation for the semantic web and linked data. RDF triples\n      express knowledge as subject-predicate-object relationships.\n    humanURL: https://www.w3.org/RDF/\n    tags:\n      - Linked Data\n      - RDF\n      - Semantic Web\n      - SPARQL\n      - Standards\n    properties:\n      - url: https://www.w3.org/TR/rdf12-primer/\n        type: Specification\n      - url: https://www.w3.org/TR/sparql12-overview/\n        type: SPARQL Specification\n      - url: https://github.com/w3c/rdf-star-wg\n        type: GitHub\n\n  - aid: w3c:digital-credentials\n    name: Digital Credentials\
  \ API\n    description: >-\n      The W3C Digital Credentials API provides browser support for mediating\n      presentation and issuance of digital credentials such as digital identity\n      documents. It enables web applications to request and receive verifiable\n      digital identity credentials from digital wallets in a privacy-preserving way.\n    humanURL: https://www.w3.org/TR/digital-credentials/\n    tags:\n      - Credentials\n      - Identity\n      - Privacy\n      - Security\n      - Standards\n    properties:\n      - url: https://www.w3.org/TR/digital-credentials/\n        type: Specification\n      - url: https://github.com/w3c/digital-credentials\n        type: GitHub\n\ncommon:\n  - url: https://www.w3.org/\n    type: Website\n  - url: https://www.w3.org/TR/\n    type: TechnicalReports\n  - url: https://api.w3.org/\n    type: API\n  - url: https://github.com/w3c/\n    type: GitHubOrg\n  - url: https://www.w3.org/news/\n    type: News\n  - url: https://www.w3.org/blog/\n\
  \    type: Blog\n  - url: https://www.w3.org/events/\n    type: Events\n  - url: https://www.w3.org/donate/\n    type: Donations\n  - url: https://w3c.social/@w3c\n    type: Mastodon\n  - url: https://www.linkedin.com/company/w3c/\n    type: LinkedIn\n  - url: https://www.youtube.com/@W3COfficial\n    type: YouTube\n  - url: https://www.w3.org/sponsor/\n    type: Sponsorship\n  - url: vocabulary/w3c-vocabulary.yml\n    type: Vocabulary\n  - url: json-ld/w3c-context.jsonld\n    type: JSONLDContext\n  - url: rules/w3c-rules.yml\n    type: SpectralRules\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/w3c/refs/heads/main/apis.yml
tags:
- Accessibility
- Standards
- Web
- Web Standards
url: https://raw.githubusercontent.com/api-evangelist/w3c/refs/heads/main/apis.yml
use_cases: []
---
