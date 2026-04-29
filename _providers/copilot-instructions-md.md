---
api_count: 2
apis:
- description: The copilot-instructions.md format is an unstructured Markdown file placed at .github/copilot-instructions.md. GitHub Copilot detects the file automatically and prepends its contents to prompts sent t
  name: copilot-instructions.md Format
  slug: format
- description: Repository copilot-instructions.md is one layer in a stack of GitHub Copilot customization options. Personal custom instructions apply to a single user across all repositories. Organization custom ins
  name: Copilot Instructions Ecosystem
  slug: related-conventions
common:
- title: ''
  type: Documentation
  url: https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot
- title: ''
  type: Documentation
  url: https://docs.github.com/en/copilot/customizing-copilot
- title: ''
  type: Examples
  url: https://github.com/github/awesome-copilot
- title: ''
  type: Blog
  url: https://github.blog/changelog/2025-01-23-custom-instructions-for-github-copilot-in-vs-code-now-generally-available/
created: '2025-01-01'
description: copilot-instructions.md is a GitHub Copilot custom instructions file placed at .github/copilot-instructions.md in a repository. It provides repository-specific guidance and preferences that GitHub Copilot Chat, Copilot in the IDE, and the Copilot coding agent automatically inject into prompts when working in the repository. The file is plain Markdown in natural language, helping the AI understand build, test, validation, framework, and style conventions so it can produce code that is consistent with the project's expectations and reduce pull request rejections caused by avoidable lint, CI, or convention failures.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: copilot-instructions.md
skills: []
slug: copilot-instructions-md
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: copilot-instructions-md\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/copilot-instructions-md/refs/heads/main/apis.yml\nname: copilot-instructions.md\nx-type: standard\ndescription: >-\n  copilot-instructions.md is a GitHub Copilot custom instructions file\n  placed at .github/copilot-instructions.md in a repository. It provides\n  repository-specific guidance and preferences that GitHub Copilot Chat,\n  Copilot in the IDE, and the Copilot coding agent automatically inject\n  into prompts when working in the repository. The file is plain Markdown\n  in natural language, helping the AI understand build, test, validation,\n  framework, and style conventions so it can produce code that is\n  consistent with the project's expectations and reduce pull request\n  rejections caused by avoidable lint, CI, or convention failures.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI Coding\n  - Coding Standards\n  - Copilot\n\
  \  - Custom Instructions\n  - Developer Workflow\n  - GitHub\n  - GitHub Copilot\n  - Markdown\n  - Repository\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: copilot-instructions-md:format\n    name: copilot-instructions.md Format\n    tags:\n      - Convention\n      - GitHub Copilot\n      - Markdown\n      - Repository\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot\n    properties:\n      - url: https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot\n        type: Documentation\n      - url: https://github.blog/changelog/2025-01-23-custom-instructions-for-github-copilot-in-vs-code-now-generally-available/\n        type: Blog\n      - url: https://docs.github.com/en/copilot/customizing-copilot/about-customizing-github-copilot-chat-responses\n\
  \        type: Documentation\n      - url: https://github.com/github/awesome-copilot\n        type: Examples\n    description: >-\n      The copilot-instructions.md format is an unstructured Markdown file\n      placed at .github/copilot-instructions.md. GitHub Copilot detects the\n      file automatically and prepends its contents to prompts sent to the\n      model in Copilot Chat, Copilot in the IDE, and the Copilot coding\n      agent. The file accepts free-form natural language instructions,\n      with whitespace between sections ignored, and is rendered as a\n      reference in Copilot Chat replies so users can confirm it was\n      consulted.\n    x-features:\n      - Auto-loaded by GitHub Copilot Chat, IDE plugins, and coding agent\n      - Resides at the canonical path .github/copilot-instructions.md\n      - Plain Markdown - no required schema or front matter\n      - Visible reference in Copilot Chat replies that consume the file\n      - Pairs with .github prompt files and\
  \ Copilot agent rulesets\n      - Effective immediately upon save; no Copilot configuration step\n    x-useCases:\n      - Telling Copilot which test runner, linter, and build commands to use\n      - Steering Copilot to preferred libraries or framework patterns\n      - Communicating commit message and branch naming conventions\n      - Documenting code style, naming, and comment conventions\n      - Reducing CI failures caused by Copilot generated code\n\n  - aid: copilot-instructions-md:related-conventions\n    name: Copilot Instructions Ecosystem\n    tags:\n      - AI Coding\n      - Conventions\n      - GitHub Copilot\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.github.com/en/copilot/customizing-copilot\n    properties:\n      - url: https://docs.github.com/en/copilot/customizing-copilot\n        type: Documentation\n      - url: https://docs.github.com/en/copilot/customizing-copilot/adding-personal-custom-instructions-for-github-copilot\n\
  \        type: Documentation\n      - url: https://docs.github.com/en/copilot/customizing-copilot/adding-organization-custom-instructions-for-github-copilot\n        type: Documentation\n      - url: https://docs.github.com/en/copilot/customizing-copilot/adding-prompt-files-to-your-repository\n        type: Documentation\n    description: >-\n      Repository copilot-instructions.md is one layer in a stack of GitHub\n      Copilot customization options. Personal custom instructions apply to a\n      single user across all repositories. Organization custom instructions\n      apply to every repository in a GitHub organization. Path-scoped\n      .github/instructions/*.instructions.md files target specific files or\n      globs. Prompt files in .github/prompts/ provide reusable named\n      prompts. The copilot-instructions.md file sits at the repository tier\n      and travels with the code, providing the same context to every\n      collaborator.\n    x-features:\n      - Composes with\
  \ personal and organization-level instructions\n      - Path-scoped .instructions.md files override repo-wide instructions\n      - Reusable prompts in .github/prompts/*.prompt.md\n      - Effective in Copilot Chat, Copilot in IDE, and Copilot coding agent\n      - Versioned and reviewed alongside code through pull requests\n    x-useCases:\n      - Applying organization-wide guardrails across all repos\n      - Layering repo-specific rules on top of organization defaults\n      - Targeting language-specific conventions to subdirectories\n      - Sharing reusable named prompts with all collaborators\n\ncommon:\n  - type: Documentation\n    url: https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot\n  - type: Documentation\n    url: https://docs.github.com/en/copilot/customizing-copilot\n  - type: Examples\n    url: https://github.com/github/awesome-copilot\n  - type: Blog\n    url: https://github.blog/changelog/2025-01-23-custom-instructions-for-github-copilot-in-vs-code-now-generally-available/\n\
  \nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/copilot-instructions-md/refs/heads/main/apis.yml
tags:
- AI Coding
- Coding Standards
- Copilot
- Custom Instructions
- Developer Workflow
- GitHub
- GitHub Copilot
- Markdown
- Repository
url: https://raw.githubusercontent.com/api-evangelist/copilot-instructions-md/refs/heads/main/apis.yml
use_cases: []
---
