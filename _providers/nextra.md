---
api_count: 3
apis:
- description: Nextra is the core Next.js plugin and library that provides MDX compilation, file-system page mapping, static image handling, search indexing, syntax highlighting, LaTeX support, and i18n utilities. I
  name: Nextra
  slug: nextra
- description: 'The Nextra Docs Theme (`nextra-theme-docs`) is a full-featured documentation theme built on top of the Nextra core. It provides a configurable sidebar with auto-collapse and nesting, a top navigation '
  name: Nextra Docs Theme
  slug: nextra-theme-docs
- description: The Nextra Blog Theme (`nextra-theme-blog`) provides a minimal, clean blog layout built on Nextra. It supports post listings with tags and dates, RSS feed generation, and basic theming. Blog posts are
  name: Nextra Blog Theme
  slug: nextra-theme-blog
common:
- title: ''
  type: Website
  url: https://nextra.site
- title: ''
  type: Documentation
  url: https://nextra.site/docs
- title: ''
  type: GettingStarted
  url: https://nextra.site/docs/guide
- title: ''
  type: GitHub
  url: https://github.com/shuding/nextra
- title: ''
  type: Changelog
  url: https://github.com/shuding/nextra/releases
- title: ''
  type: License
  url: https://github.com/shuding/nextra/blob/main/LICENSE
- title: ''
  type: JSONSchema
  url: json-schema/nextra-config-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/nextra-theme-docs-config-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/nextra-meta-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/nextra-context.jsonld
created: '2026-03-18'
description: Nextra is an open-source, Next.js-based documentation framework for building fast, modern, and beautifully styled documentation sites. It extends Next.js with MDX support, file-system routing, built-in search powered by Pagefind, syntax highlighting via Rehype Pretty Code, LaTeX rendering, static image optimization, i18n support, and a full-featured docs theme with sidebar, navbar, TOC, dark mode, and breadcrumb navigation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Nextra Context
  property_count: 10
  slug: nextra-context
layout: provider
modified: '2026-04-28'
name: Nextra
skills: []
slug: nextra
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nextra\nname: Nextra\ndescription: >-\n  Nextra is an open-source, Next.js-based documentation framework for building fast,\n  modern, and beautifully styled documentation sites. It extends Next.js with MDX\n  support, file-system routing, built-in search powered by Pagefind, syntax highlighting\n  via Rehype Pretty Code, LaTeX rendering, static image optimization, i18n support,\n  and a full-featured docs theme with sidebar, navbar, TOC, dark mode, and breadcrumb\n  navigation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Documentation\n  - MDX\n  - Next.js\n  - Open Source\n  - Static Site Generator\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/nextra/refs/heads/main/apis.yml\ncreated: '2026-03-18'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: nextra:nextra\n    name: Nextra\n    tags:\n      - Documentation\n      - MDX\n      - Next.js\n      - Static Site Generator\n\
  \    humanURL: https://nextra.site\n    description: >-\n      Nextra is the core Next.js plugin and library that provides MDX compilation,\n      file-system page mapping, static image handling, search indexing, syntax highlighting,\n      LaTeX support, and i18n utilities. It is consumed as a JavaScript/TypeScript\n      package installed via npm and configured through the `nextra()` plugin in `next.config`\n      files.\n    properties:\n      - url: https://nextra.site/docs\n        type: Documentation\n      - url: https://nextra.site/docs/guide\n        type: GettingStarted\n      - url: https://github.com/shuding/nextra\n        type: GitHub\n      - url: json-schema/nextra-config-schema.json\n        type: JSONSchema\n  - aid: nextra:nextra-theme-docs\n    name: Nextra Docs Theme\n    tags:\n      - Documentation\n      - React\n      - Theme\n    humanURL: https://nextra.site/docs/docs-theme\n    description: >-\n      The Nextra Docs Theme (`nextra-theme-docs`) is a full-featured\
  \ documentation\n      theme built on top of the Nextra core. It provides a configurable sidebar with\n      auto-collapse and nesting, a top navigation bar, a floating table of contents,\n      dark mode toggle, edit-on-GitHub and feedback links, i18n language switching,\n      next/prev page navigation, breadcrumbs, and a last-updated timestamp. Configuration\n      is supplied as React props to the `` component.\n    properties:\n      - url: https://nextra.site/docs/docs-theme\n        type: Documentation\n      - url: https://nextra.site/docs/docs-theme/theme-configuration\n        type: APIReferenceDocumentation\n      - url: json-schema/nextra-theme-docs-config-schema.json\n        type: JSONSchema\n  - aid: nextra:nextra-theme-blog\n    name: Nextra Blog Theme\n    tags:\n      - Blog\n      - Documentation\n      - React\n      - Theme\n    humanURL: https://nextra.site/docs/blog-theme\n    description: >-\n      The Nextra Blog Theme (`nextra-theme-blog`) provides a minimal,\
  \ clean\n      blog layout built on Nextra. It supports post listings with tags and\n      dates, RSS feed generation, and basic theming. Blog posts are written as\n      MDX files under the `posts/` directory, and front matter fields such as\n      `title`, `date`, `description`, and `tag` drive the post listing index.\n    properties:\n      - url: https://nextra.site/docs/blog-theme\n        type: Documentation\n      - url: https://github.com/shuding/nextra/tree/main/packages/nextra-theme-blog\n        type: GitHub\ncommon:\n  - type: Website\n    url: https://nextra.site\n  - type: Documentation\n    url: https://nextra.site/docs\n  - type: GettingStarted\n    url: https://nextra.site/docs/guide\n  - type: GitHub\n    url: https://github.com/shuding/nextra\n  - type: Changelog\n    url: https://github.com/shuding/nextra/releases\n  - type: License\n    url: https://github.com/shuding/nextra/blob/main/LICENSE\n  - type: JSONSchema\n    url: json-schema/nextra-config-schema.json\n \
  \ - type: JSONSchema\n    url: json-schema/nextra-theme-docs-config-schema.json\n  - type: JSONSchema\n    url: json-schema/nextra-meta-schema.json\n  - type: JSON-LD\n    url: json-ld/nextra-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nextra/refs/heads/main/apis.yml
tags:
- Documentation
- MDX
- Next.js
- Open Source
- Static Site Generator
url: https://raw.githubusercontent.com/api-evangelist/nextra/refs/heads/main/apis.yml
use_cases: []
---
