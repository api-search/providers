---
api_count: 3
apis:
- description: The Anthropic Tool Use API allows AI agents built on Claude to call client-defined functions or Anthropic-provided server tools such as web search, code execution, and web fetch. Tools are declared in
  name: Anthropic Tool Use API
  slug: ''
- description: 'Google''s Agent Development Kit (ADK) is a flexible framework for building AI agents and multi-agent systems. It supports LLM agents, workflow agents, and custom agents with capabilities including MCP '
  name: Google Agent Development Kit (ADK)
  slug: ''
- description: The Model Context Protocol (MCP) is an open-source standard for connecting AI applications to external systems. MCP defines a standardized way for AI agents to access data sources, tools, and workflow
  name: Model Context Protocol (MCP)
  slug: ''
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/api-evangelist
- title: Tool Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/json-schema/agent-skills-tool-schema.json
- title: Tool Call Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/json-schema/agent-skills-tool-call-schema.json
- title: Tool Result Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/json-schema/agent-skills-tool-result-schema.json
- title: MCP Server Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/json-schema/agent-skills-mcp-server-schema.json
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/json-ld/agent-skills-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/vocabulary/agent-skills-vocabulary.yaml
created: '2025-01-01'
description: A collection of resources, APIs, and standards related to AI agent skills and capabilities. Agent skills represent the tools, functions, and capabilities that AI agents can invoke to accomplish tasks — spanning web search, code execution, file management, memory, and external API integrations. This topic covers the major platforms and frameworks that define how agent skills are declared, discovered, and invoked.
features:
- description: AI agents can invoke user-defined or platform-provided functions based on natural language instructions, with structured input/output schemas.
  name: Function Calling
- description: Platforms like Anthropic and OpenAI run certain agent skills (web search, code execution) on their own infrastructure, removing the need for client-side execution.
  name: Server-Side Tool Execution
- description: The Model Context Protocol provides a universal adapter layer enabling agents to discover and call any MCP-compatible server as a skill.
  name: MCP Integration
- description: Frameworks like Google ADK support coordinating multiple specialized agents, with skills delegated across agent boundaries via protocols like A2A.
  name: Multi-Agent Orchestration
- description: Agent skill definitions can enforce strict JSON Schema compliance to ensure agents produce well-formed tool calls matching the declared parameter schema.
  name: Strict Schema Enforcement
- description: Anthropic's tool_search server tool enables agents to discover available tools at runtime without statically declaring all tool schemas upfront.
  name: Tool Discovery
image: ''
integrations:
- description: Native support for tool use and MCP via the Anthropic Messages API.
  name: Claude (Anthropic)
- description: Function calling and MCP tool integration via the OpenAI Responses API.
  name: ChatGPT (OpenAI)
- description: Tool use and ADK integration for Gemini-based agents.
  name: Gemini (Google)
- description: GitHub Copilot supports MCP servers as agent skill providers within the VS Code development environment.
  name: VS Code Copilot
- description: Cursor IDE supports MCP tool integration for AI-assisted coding agents.
  name: Cursor
- description: Open-source framework for composing agent skills into chains and graphs across multiple LLM providers.
  name: LangChain
- description: Data framework enabling agents to index and retrieve from external data sources as structured skills.
  name: LlamaIndex
jsonld:
- class_count: 7
  name: Agent Skills Context
  property_count: 16
  slug: agent-skills-context
layout: provider
modified: '2026-04-19'
name: Agent Skills
skills: []
slug: agent-skills
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Agent Skills\ndescription: A collection of resources, APIs, and standards related to AI agent skills and capabilities. Agent skills represent the tools, functions, and capabilities that AI agents can invoke to accomplish tasks — spanning web search, code execution, file management, memory, and external API integrations. This topic covers the major platforms and frameworks that define how agent skills are declared, discovered, and invoked.\nurl: https://github.com/api-evangelist/agent-skills\ncreated: '2025-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.18'\ntags:\n  - Agent Skills\n  - AI Agents\n  - Tool Use\n  - Function Calling\n  - MCP\n  - Agentic AI\n  - Automation\napis:\n  - name: Anthropic Tool Use API\n    description: The Anthropic Tool Use API allows AI agents built on Claude to call client-defined functions or Anthropic-provided server tools such as web search, code execution, and web fetch. Tools are declared in the API request and Claude decides\
  \ when to invoke them based on context. Server tools run on Anthropic infrastructure while client tools execute in the calling application.\n    humanURL: https://platform.claude.com/docs/en/docs/agents-and-tools/tool-use/overview\n    baseURL: https://api.anthropic.com\n    tags:\n      - Anthropic\n      - Tool Use\n      - Function Calling\n      - Claude\n      - AI Agents\n    properties:\n      - type: Documentation\n        url: https://platform.claude.com/docs/en/docs/agents-and-tools/tool-use/overview\n      - type: APIReference\n        url: https://platform.claude.com/docs/en/docs/agents-and-tools/tool-use/tool-reference\n      - type: GettingStarted\n        url: https://platform.claude.com/docs/en/docs/agents-and-tools/tool-use/build-a-tool-using-agent\n\n  - name: Google Agent Development Kit (ADK)\n    description: Google's Agent Development Kit (ADK) is a flexible framework for building AI agents and multi-agent systems. It supports LLM agents, workflow agents, and custom\
  \ agents with capabilities including MCP tool integration, OpenAPI tools, function tools, grounding via Google Search, streaming via Gemini Live API, and Agent-to-Agent (A2A) protocol for inter-agent communication. Available in Python, TypeScript, Go, and Java.\n    humanURL: https://adk.dev/\n    baseURL: https://adk.dev\n    tags:\n      - Google\n      - Agent Development Kit\n      - ADK\n      - Multi-Agent\n      - Gemini\n      - Tool Use\n    properties:\n      - type: Documentation\n        url: https://adk.dev/\n      - type: GettingStarted\n        url: https://adk.dev/get-started\n      - type: GitHubRepository\n        url: https://github.com/google/adk-python\n\n  - name: Model Context Protocol (MCP)\n    description: The Model Context Protocol (MCP) is an open-source standard for connecting AI applications to external systems. MCP defines a standardized way for AI agents to access data sources, tools, and workflows. It enables agents to call external tools, access files,\
  \ databases, and APIs through a consistent protocol supported by Claude, ChatGPT, VS Code, Cursor, and many other AI clients.\n    humanURL: https://modelcontextprotocol.io/introduction\n    baseURL: https://modelcontextprotocol.io\n    tags:\n      - MCP\n      - Model Context Protocol\n      - Standards\n      - Tool Use\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://modelcontextprotocol.io/introduction\n      - type: GettingStarted\n        url: https://modelcontextprotocol.io/docs/develop/build-server\n      - type: GitHubRepository\n        url: https://github.com/modelcontextprotocol/specification\n\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/api-evangelist\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/json-schema/agent-skills-tool-schema.json\n    title: Tool Schema\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/json-schema/agent-skills-tool-call-schema.json\n\
  \    title: Tool Call Schema\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/json-schema/agent-skills-tool-result-schema.json\n    title: Tool Result Schema\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/json-schema/agent-skills-mcp-server-schema.json\n    title: MCP Server Schema\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/json-ld/agent-skills-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/vocabulary/agent-skills-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Function Calling\n        description: AI agents can invoke user-defined or platform-provided functions based on natural language instructions, with structured input/output schemas.\n      - name: Server-Side Tool Execution\n        description: Platforms\
  \ like Anthropic and OpenAI run certain agent skills (web search, code execution) on their own infrastructure, removing the need for client-side execution.\n      - name: MCP Integration\n        description: The Model Context Protocol provides a universal adapter layer enabling agents to discover and call any MCP-compatible server as a skill.\n      - name: Multi-Agent Orchestration\n        description: Frameworks like Google ADK support coordinating multiple specialized agents, with skills delegated across agent boundaries via protocols like A2A.\n      - name: Strict Schema Enforcement\n        description: Agent skill definitions can enforce strict JSON Schema compliance to ensure agents produce well-formed tool calls matching the declared parameter schema.\n      - name: Tool Discovery\n        description: Anthropic's tool_search server tool enables agents to discover available tools at runtime without statically declaring all tool schemas upfront.\n  - type: UseCases\n    data:\n\
  \      - name: Automated Research\n        description: Agents use web search and fetch skills to retrieve, synthesize, and summarize information from the internet in response to user queries.\n      - name: Code Generation and Execution\n        description: Agents invoke code execution skills to write, run, and debug code within sandboxed environments, returning results to the user.\n      - name: Data Integration\n        description: Agents use OpenAPI-backed skills to read and write data across enterprise systems — CRMs, ERPs, databases — through standardized API calls.\n      - name: File and Document Management\n        description: Agents invoke file system skills to read, write, and organize documents, images, and structured data on behalf of users.\n      - name: Multi-Step Workflow Automation\n        description: Agents chain multiple skills in sequence — searching, retrieving, transforming, and storing data — to complete complex multi-step tasks autonomously.\n      - name:\
  \ AI-Assisted Customer Support\n        description: Customer service agents use CRM lookup, ticketing, and knowledge base skills to resolve customer issues without human escalation.\n  - type: Integrations\n    data:\n      - name: Claude (Anthropic)\n        description: Native support for tool use and MCP via the Anthropic Messages API.\n      - name: ChatGPT (OpenAI)\n        description: Function calling and MCP tool integration via the OpenAI Responses API.\n      - name: Gemini (Google)\n        description: Tool use and ADK integration for Gemini-based agents.\n      - name: VS Code Copilot\n        description: GitHub Copilot supports MCP servers as agent skill providers within the VS Code development environment.\n      - name: Cursor\n        description: Cursor IDE supports MCP tool integration for AI-assisted coding agents.\n      - name: LangChain\n        description: Open-source framework for composing agent skills into chains and graphs across multiple LLM providers.\n\
  \      - name: LlamaIndex\n        description: Data framework enabling agents to index and retrieve from external data sources as structured skills.\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/apis.yml
tags:
- Agent Skills
- AI Agents
- Tool Use
- Function Calling
- MCP
- Agentic AI
- Automation
url: https://github.com/api-evangelist/agent-skills
use_cases:
- description: Agents use web search and fetch skills to retrieve, synthesize, and summarize information from the internet in response to user queries.
  name: Automated Research
- description: Agents invoke code execution skills to write, run, and debug code within sandboxed environments, returning results to the user.
  name: Code Generation and Execution
- description: Agents use OpenAPI-backed skills to read and write data across enterprise systems — CRMs, ERPs, databases — through standardized API calls.
  name: Data Integration
- description: Agents invoke file system skills to read, write, and organize documents, images, and structured data on behalf of users.
  name: File and Document Management
- description: Agents chain multiple skills in sequence — searching, retrieving, transforming, and storing data — to complete complex multi-step tasks autonomously.
  name: Multi-Step Workflow Automation
- description: Customer service agents use CRM lookup, ticketing, and knowledge base skills to resolve customer issues without human escalation.
  name: AI-Assisted Customer Support
---
