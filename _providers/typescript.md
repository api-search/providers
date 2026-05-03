---
api_count: 3
apis:
- description: Programmatic access to the TypeScript compiler. The Compiler API allows developers to parse TypeScript files into ASTs, perform type checking, emit JavaScript, and transform code programmatically.
  name: TypeScript Compiler API
  slug: typescript-compiler-api
- description: API for editor integration and language tooling. The Language Service API provides completions, diagnostics, quick fixes, rename, go-to-definition, find references, and other IDE features that power e
  name: TypeScript Language Service API
  slug: typescript-language-service-api
- description: The TypeScript Transform API enables custom AST transformations during compilation. Transformers can modify, add, or remove nodes in the TypeScript AST before code emission.
  name: TypeScript Transform API
  slug: typescript-transform-api
common:
- title: ''
  type: Website
  url: https://www.typescriptlang.org
- title: ''
  type: Documentation
  url: https://www.typescriptlang.org/docs/
- title: ''
  type: GitHub Organization
  url: https://github.com/microsoft/TypeScript
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/typescript/
- title: ''
  type: Community
  url: https://www.typescriptlang.org/community
- title: ''
  type: npm
  url: https://www.npmjs.com/package/typescript
- title: ''
  type: Playground
  url: https://www.typescriptlang.org/play
- title: ''
  type: Handbook
  url: https://www.typescriptlang.org/docs/handbook/intro.html
- title: ''
  type: Release Notes
  url: https://www.typescriptlang.org/docs/handbook/release-notes/overview.html
- title: ''
  type: GitHub Issues
  url: https://github.com/microsoft/TypeScript/issues
- title: ''
  type: Twitter
  url: https://twitter.com/typescript
- title: ''
  type: JSON-LD
  url: json-ld/typescript-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/typescript-vocabulary.yml
- title: ''
  type: JSONSchema
  url: json-schema/typescript-diagnostic-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/typescript-compiler-options-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/typescript-diagnostic-structure.json
created: '2024-01-01'
description: TypeScript is a strongly typed programming language that builds on JavaScript, adding optional static type checking and other features. Developed and maintained by Microsoft, TypeScript compiles to plain JavaScript and is widely used for large-scale web applications, Node.js services, and developer tooling. The TypeScript Compiler API and Language Service API enable programmatic compilation, type checking, code transformation, and IDE integrations.
features: []
image: https://www.typescriptlang.org/favicon-32x32.png
integrations: []
jsonld:
- class_count: 15
  name: Typescript Context
  property_count: 13
  slug: typescript-context
layout: provider
modified: '2026-05-03'
name: TypeScript
skills: []
slug: typescript
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: typescript\nname: TypeScript\ndescription: >-\n  TypeScript is a strongly typed programming language that builds on JavaScript,\n  adding optional static type checking and other features. Developed and maintained\n  by Microsoft, TypeScript compiles to plain JavaScript and is widely used for\n  large-scale web applications, Node.js services, and developer tooling. The\n  TypeScript Compiler API and Language Service API enable programmatic compilation,\n  type checking, code transformation, and IDE integrations.\nimage: https://www.typescriptlang.org/favicon-32x32.png\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/typescript/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Compiler\n  - JavaScript\n  - Language Service\n  - Programming Language\n  - Static Typing\n  - Web Development\ntype: Index\napis:\n  - aid: typescript:typescript-compiler-api\n    name: TypeScript Compiler API\n    description:\
  \ >-\n      Programmatic access to the TypeScript compiler. The Compiler API allows\n      developers to parse TypeScript files into ASTs, perform type checking,\n      emit JavaScript, and transform code programmatically.\n    image: https://www.typescriptlang.org/favicon-32x32.png\n    humanURL: https://www.typescriptlang.org/docs/handbook/compiler-options.html\n    baseURL: https://www.typescriptlang.org\n    tags:\n      - Compiler\n      - Transpilation\n      - Type Checking\n      - AST\n      - Code Generation\n    properties:\n      - type: Documentation\n        url: https://github.com/microsoft/TypeScript/wiki/Using-the-Compiler-API\n      - type: GitHub Repository\n        url: https://github.com/microsoft/TypeScript\n      - type: npm Package\n        url: https://www.npmjs.com/package/typescript\n      - type: API Reference\n        url: https://www.typescriptlang.org/tsconfig\n      - type: Compiler Options\n        url: https://www.typescriptlang.org/tsconfig/\n\n  - aid:\
  \ typescript:typescript-language-service-api\n    name: TypeScript Language Service API\n    description: >-\n      API for editor integration and language tooling. The Language Service API\n      provides completions, diagnostics, quick fixes, rename, go-to-definition,\n      find references, and other IDE features that power editors like VS Code.\n    image: https://www.typescriptlang.org/favicon-32x32.png\n    humanURL: https://www.typescriptlang.org\n    baseURL: https://www.typescriptlang.org\n    tags:\n      - Autocomplete\n      - Diagnostics\n      - IDE\n      - Language Service\n      - Refactoring\n    properties:\n      - type: Documentation\n        url: https://github.com/microsoft/TypeScript/wiki/Using-the-Language-Service-API\n      - type: GitHub Repository\n        url: https://github.com/microsoft/TypeScript\n\n  - aid: typescript:typescript-transform-api\n    name: TypeScript Transform API\n    description: >-\n      The TypeScript Transform API enables custom AST\
  \ transformations during\n      compilation. Transformers can modify, add, or remove nodes in the\n      TypeScript AST before code emission.\n    image: https://www.typescriptlang.org/favicon-32x32.png\n    humanURL: https://www.typescriptlang.org/docs/handbook/2/types-from-types.html\n    baseURL: https://www.typescriptlang.org\n    tags:\n      - AST\n      - Code Transformation\n      - Compilation\n      - Custom Transformers\n    properties:\n      - type: Documentation\n        url: https://github.com/microsoft/TypeScript/wiki/Using-the-Compiler-API#traversing-the-ast-with-a-little-linter\n      - type: GitHub Repository\n        url: https://github.com/microsoft/TypeScript\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Website\n    url: https://www.typescriptlang.org\n  - type: Documentation\n    url: https://www.typescriptlang.org/docs/\n  - type: GitHub Organization\n    url: https://github.com/microsoft/TypeScript\n  - type: Blog\n  \
  \  url: https://devblogs.microsoft.com/typescript/\n  - type: Community\n    url: https://www.typescriptlang.org/community\n  - type: npm\n    url: https://www.npmjs.com/package/typescript\n  - type: Playground\n    url: https://www.typescriptlang.org/play\n  - type: Handbook\n    url: https://www.typescriptlang.org/docs/handbook/intro.html\n  - type: Release Notes\n    url: https://www.typescriptlang.org/docs/handbook/release-notes/overview.html\n  - type: GitHub Issues\n    url: https://github.com/microsoft/TypeScript/issues\n  - type: Twitter\n    url: https://twitter.com/typescript\n  - type: JSON-LD\n    url: json-ld/typescript-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/typescript-vocabulary.yml\n  - type: JSONSchema\n    url: json-schema/typescript-diagnostic-schema.json\n  - type: JSONSchema\n    url: json-schema/typescript-compiler-options-schema.json\n  - type: JSONStructure\n    url: json-structure/typescript-diagnostic-structure.json\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/typescript/refs/heads/main/apis.yml
tags:
- Compiler
- JavaScript
- Language Service
- Programming Language
- Static Typing
- Web Development
url: https://raw.githubusercontent.com/api-evangelist/typescript/refs/heads/main/apis.yml
use_cases: []
---
