---
api_count: 1
apis:
- description: The AGENTS.md specification defines a standard Markdown file format for providing project context, build instructions, coding standards, and testing procedures to AI coding agents. The file is version
  name: AGENTS.md Specification
  slug: agents-md-specification
common:
- title: ''
  type: Portal
  url: https://agents.md/
- title: ''
  type: Documentation
  url: https://agents.md/
- title: ''
  type: GitHubOrganization
  url: https://github.com/agentic-ai-foundation
created: '2025-01-01'
description: AGENTS.md is an open standard file format that provides context and instructions to AI coding agents working on software projects. Like a README for agents, an AGENTS.md file lives in the project repository and tells AI agents how to build, test, and contribute code — including coding standards, build commands, testing procedures, and development conventions. Supported by over 60,000 open-source projects and major platforms including OpenAI Codex, Google Jules, Cursor, Devin, Windsurf, GitHub Copilot, and goose. Stewarded by the Agentic AI Foundation under the Linux Foundation.
features:
- description: Provides AI agents with structured information about the project including its purpose, architecture, and key concepts.
  name: Project Context for AI Agents
- description: Documents the exact commands needed to build, test, lint, and deploy the project so AI agents can execute them correctly.
  name: Build and Test Instructions
- description: Specifies coding conventions, style guides, naming patterns, and best practices that AI agents should follow when generating code.
  name: Coding Standards
- description: Supports nested AGENTS.md files in monorepo subdirectories, allowing different projects to have tailored agent instructions with closest-file-wins precedence.
  name: Monorepo Support
- description: The format uses standard Markdown with no mandatory fields, giving teams flexibility to include only the context their agents need.
  name: Open Standard with No Required Fields
- description: Supported by 60+ AI coding tools and editors including OpenAI Codex, Google Jules, Cursor, Devin, GitHub Copilot, Windsurf, and goose.
  name: Broad Tool Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native AGENTS.md support for AI coding tasks via OpenAI's coding agent.
  name: OpenAI Codex
- description: AGENTS.md context ingestion in Google's AI coding agent for autonomous development tasks.
  name: Google Jules
- description: AGENTS.md file discovery and context loading in Cursor's AI-assisted editor.
  name: Cursor
- description: AGENTS.md support in Cognition's autonomous coding agent Devin.
  name: Devin (Cognition)
- description: AGENTS.md integration in GitHub Copilot for project-aware AI code suggestions.
  name: GitHub Copilot
- description: AGENTS.md context loading in Block's open-source goose AI agent, now under the Agentic AI Foundation.
  name: goose (AAIF)
- description: AGENTS.md support in Windsurf's AI-powered development environment.
  name: Windsurf
- description: AGENTS.md discovery in JetBrains' AI coding assistant Junie.
  name: JetBrains Junie
jsonld:
- class_count: 1
  name: Agents Md Context
  property_count: 13
  slug: agents-md-context
layout: provider
modified: '2026-04-19'
name: AGENTS.md
skills: []
slug: agents-md
solutions: []
source_filename: apis.yml
source_yaml: "aid: agents-md\nname: AGENTS.md\ndescription: AGENTS.md is an open standard file format that provides context and instructions to AI coding agents working on software projects. Like a README for agents, an AGENTS.md file lives in the\n  project repository and tells AI agents how to build, test, and contribute code — including coding standards, build commands, testing procedures, and development conventions. Supported by over 60,000\n  open-source projects and major platforms including OpenAI Codex, Google Jules, Cursor, Devin, Windsurf, GitHub Copilot, and goose. Stewarded by the Agentic AI Foundation under the Linux Foundation.\nurl: https://raw.githubusercontent.com/api-evangelist/agents-md/refs/heads/main/apis.yml\nhumanURL: https://agents.md/\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AI Agents\n- AI Copilot\n- Coding Standards\n- Developer Workflow\n- Open Standard\n- Documentation\ncreated: '2025-01-01'\nmodified:\
  \ '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: agents-md:agents-md-specification\n  name: AGENTS.md Specification\n  description: The AGENTS.md specification defines a standard Markdown file format for providing project context, build instructions, coding standards, and testing procedures to AI coding agents. The \n    file is version-controlled with the project and discovered by AI tools at predictable locations in the repository tree.\n  humanURL: https://agents.md/\n  tags:\n  - Open Standard\n  - AI Agents\n  - Developer Workflow\n  - Specification\n  properties:\n  - type: Documentation\n    url: https://agents.md/\n  - type: GitHubRepository\n    url: https://github.com/openai/agents.md\ncommon:\n- type: Portal\n  url: https://agents.md/\n- type: Documentation\n  url: https://agents.md/\n- type: GitHubOrganization\n  url: https://github.com/agentic-ai-foundation\n- type: Features\n  data:\n  - name: Project Context for AI Agents\n    description: Provides AI agents with\
  \ structured information about the project including its purpose, architecture, and key concepts.\n  - name: Build and Test Instructions\n    description: Documents the exact commands needed to build, test, lint, and deploy the project so AI agents can execute them correctly.\n  - name: Coding Standards\n    description: Specifies coding conventions, style guides, naming patterns, and best practices that AI agents should follow when generating code.\n  - name: Monorepo Support\n    description: Supports nested AGENTS.md files in monorepo subdirectories, allowing different projects to have tailored agent instructions with closest-file-wins precedence.\n  - name: Open Standard with No Required Fields\n    description: The format uses standard Markdown with no mandatory fields, giving teams flexibility to include only the context their agents need.\n  - name: Broad Tool Support\n    description: Supported by 60+ AI coding tools and editors including OpenAI Codex, Google Jules, Cursor, Devin,\
  \ GitHub Copilot, Windsurf, and goose.\n- type: UseCases\n  data:\n  - name: AI-Assisted Code Review\n    description: Provide AI coding agents with project conventions and standards so their generated code passes review without needing manual style corrections.\n  - name: Autonomous Feature Development\n    description: Enable AI agents to independently implement features by giving them the context needed to set up the development environment, run tests, and validate their work.\n  - name: Onboarding AI Agents to Existing Projects\n    description: Accelerate AI agent productivity on legacy codebases by documenting the context that would normally come from exploring the project.\n  - name: Consistent Multi-Agent Workflows\n    description: Ensure all AI agents working on a project operate from the same context, reducing inconsistencies when multiple agents collaborate.\n  - name: Security-Aware AI Development\n    description: Document security considerations and sensitive file locations\
  \ so AI agents avoid introducing vulnerabilities or accidentally exposing credentials.\n- type: Integrations\n  data:\n  - name: OpenAI Codex\n    description: Native AGENTS.md support for AI coding tasks via OpenAI's coding agent.\n  - name: Google Jules\n    description: AGENTS.md context ingestion in Google's AI coding agent for autonomous development tasks.\n  - name: Cursor\n    description: AGENTS.md file discovery and context loading in Cursor's AI-assisted editor.\n  - name: Devin (Cognition)\n    description: AGENTS.md support in Cognition's autonomous coding agent Devin.\n  - name: GitHub Copilot\n    description: AGENTS.md integration in GitHub Copilot for project-aware AI code suggestions.\n  - name: goose (AAIF)\n    description: AGENTS.md context loading in Block's open-source goose AI agent, now under the Agentic AI Foundation.\n  - name: Windsurf\n    description: AGENTS.md support in Windsurf's AI-powered development environment.\n  - name: JetBrains Junie\n    description:\
  \ AGENTS.md discovery in JetBrains' AI coding assistant Junie.\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/agents-md/refs/heads/main/apis.yml
tags:
- AI Agents
- AI Copilot
- Coding Standards
- Developer Workflow
- Open Standard
- Documentation
url: https://raw.githubusercontent.com/api-evangelist/agents-md/refs/heads/main/apis.yml
use_cases:
- description: Provide AI coding agents with project conventions and standards so their generated code passes review without needing manual style corrections.
  name: AI-Assisted Code Review
- description: Enable AI agents to independently implement features by giving them the context needed to set up the development environment, run tests, and validate their work.
  name: Autonomous Feature Development
- description: Accelerate AI agent productivity on legacy codebases by documenting the context that would normally come from exploring the project.
  name: Onboarding AI Agents to Existing Projects
- description: Ensure all AI agents working on a project operate from the same context, reducing inconsistencies when multiple agents collaborate.
  name: Consistent Multi-Agent Workflows
- description: Document security considerations and sensitive file locations so AI agents avoid introducing vulnerabilities or accidentally exposing credentials.
  name: Security-Aware AI Development
---
