---
api_count: 2
apis:
- description: The CONVENTIONS.md format is a free-form Markdown file describing the coding rules an AI coding agent should follow inside a repository. The file is loaded into the chat context, typically in read-onl
  name: CONVENTIONS.md Format
  slug: format
- description: CONVENTIONS.md sits alongside several closely related AI coding conventions. CLAUDE.md is used by Claude Code for repository memory. .cursor/rules and .cursorrules are used by Cursor. .github/copilot-
  name: AI Coding Conventions Ecosystem
  slug: related-conventions
common:
- title: ''
  type: Documentation
  url: https://aider.chat/docs/usage/conventions.html
- title: ''
  type: Documentation
  url: https://docs.anthropic.com/en/docs/claude-code/memory
- title: ''
  type: Documentation
  url: https://docs.cursor.com/context/rules-for-ai
- title: ''
  type: Documentation
  url: https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot
created: '2025-01-01'
description: CONVENTIONS.md is a Markdown convention popularized by AI pair programming tools such as aider and adopted by AI coding agents like Cursor, Cline, and Claude Code. It documents project-specific coding standards, library preferences, naming conventions, architecture decisions, and development practices in plain natural language so both human developers and AI assistants share the same expectations. The file is loaded into the model context to steer code generation toward project conventions.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: CONVENTIONS.md
skills: []
slug: conventions-md
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: conventions-md\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/conventions-md/refs/heads/main/apis.yml\nname: CONVENTIONS.md\nx-type: standard\ndescription: >-\n  CONVENTIONS.md is a Markdown convention popularized by AI pair programming\n  tools such as aider and adopted by AI coding agents like Cursor, Cline, and\n  Claude Code. It documents project-specific coding standards, library\n  preferences, naming conventions, architecture decisions, and development\n  practices in plain natural language so both human developers and AI\n  assistants share the same expectations. The file is loaded into the model\n  context to steer code generation toward project conventions.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI Coding\n  - Aider\n  - Best Practices\n  - Coding Standards\n  - Conventions\n  - Developer Workflow\n  - Documentation\n  - Markdown\n  - Project Configuration\ncreated: '2025-01-01'\nmodified: '2026-04-28'\n\
  specificationVersion: '0.19'\napis:\n  - aid: conventions-md:format\n    name: CONVENTIONS.md Format\n    tags:\n      - AI Coding\n      - Convention\n      - Markdown\n      - Project Configuration\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://aider.chat/docs/usage/conventions.html\n    properties:\n      - url: https://aider.chat/docs/usage/conventions.html\n        type: Documentation\n      - url: https://aider.chat/docs/config/aider_conf.html\n        type: Documentation\n      - url: https://github.com/Aider-AI/aider\n        type: Repository\n    description: >-\n      The CONVENTIONS.md format is a free-form Markdown file describing the\n      coding rules an AI coding agent should follow inside a repository. The\n      file is loaded into the chat context, typically in read-only mode, and\n      may be referenced via /read CONVENTIONS.md, the --read CLI flag, or a\n      persistent read entry in .aider.conf.yml. Common\
  \ content includes\n      preferred libraries, language and version targets, type system rules,\n      lint and format expectations, error handling style, and architectural\n      patterns the project favors.\n    x-features:\n      - Plain Markdown bullet list of project rules\n      - Loaded into AI agent context per session or via config\n      - Supports prompt caching when marked read-only\n      - Composable alongside CLAUDE.md, .cursor/rules, and copilot-instructions\n      - No required schema, allowing each project to define what matters\n    x-useCases:\n      - Steering AI agents toward preferred libraries and frameworks\n      - Documenting type hint, naming, and lint requirements\n      - Capturing architecture decisions for AI assisted refactors\n      - Aligning human and AI contributors on a single source of conventions\n      - Reducing rework caused by AI generated code that misses team norms\n\n  - aid: conventions-md:related-conventions\n    name: AI Coding Conventions\
  \ Ecosystem\n    tags:\n      - AI Coding\n      - Comparison\n      - Conventions\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.anthropic.com/en/docs/claude-code/memory\n    properties:\n      - url: https://docs.anthropic.com/en/docs/claude-code/memory\n        type: Documentation\n      - url: https://docs.cursor.com/context/rules-for-ai\n        type: Documentation\n      - url: https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot\n        type: Documentation\n      - url: https://aider.chat/docs/usage/conventions.html\n        type: Documentation\n    description: >-\n      CONVENTIONS.md sits alongside several closely related AI coding\n      conventions. CLAUDE.md is used by Claude Code for repository memory.\n      .cursor/rules and .cursorrules are used by Cursor. .github/copilot-\n      instructions.md is used by GitHub Copilot. Each follows a similar\n\
  \      pattern: a Markdown or text file describing repository-specific rules\n      that gets injected into the AI assistant prompt context. CONVENTIONS.md\n      is the most tool-agnostic option and is widely adopted across multiple\n      AI coding agents.\n    x-features:\n      - Tool-agnostic file naming compared to CLAUDE.md or .cursorrules\n      - Often committed to repo root for visibility to humans and AI\n      - Frequently referenced by other agent files such as CLAUDE.md\n      - Composable with .editorconfig, .prettierrc, and lint configurations\n    x-useCases:\n      - Sharing one set of rules across aider, Cursor, Cline, and Claude Code\n      - Consolidating coding standards for human and AI contributors\n      - Documenting cross-cutting concerns separate from tool-specific config\n\ncommon:\n  - type: Documentation\n    url: https://aider.chat/docs/usage/conventions.html\n  - type: Documentation\n    url: https://docs.anthropic.com/en/docs/claude-code/memory\n  - type:\
  \ Documentation\n    url: https://docs.cursor.com/context/rules-for-ai\n  - type: Documentation\n    url: https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/conventions-md/refs/heads/main/apis.yml
tags:
- AI Coding
- Aider
- Best Practices
- Coding Standards
- Conventions
- Developer Workflow
- Documentation
- Markdown
- Project Configuration
url: https://raw.githubusercontent.com/api-evangelist/conventions-md/refs/heads/main/apis.yml
use_cases: []
---
