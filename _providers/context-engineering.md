---
api_count: 5
apis:
- description: Anthropic's engineering guide to context engineering, framing context as a finite attention budget and walking through system prompts, tool design, few-shot examples, just-in-time retrieval, compactio
  name: Effective Context Engineering for AI Agents
  slug: anthropic-guide
- description: 'RAG is a context engineering pattern that augments LLM prompts with passages retrieved at inference time from a vector store, search index, or knowledge base. RAG keeps facts outside the model and is '
  name: Retrieval-Augmented Generation (RAG)
  slug: retrieval-augmented-generation
- description: Prompt engineering is the discipline of crafting model instructions and examples to guide model behavior. Prompt engineering remains a sub-discipline of context engineering and includes techniques lik
  name: Prompt Engineering
  slug: prompt-engineering
- description: 'Agentic loops are iterative reasoning patterns in which an LLM plans, calls tools, observes results, and refines its plan. Tool design is a central context engineering concern: tools must be token-eff'
  name: Agentic Loops and Tool Use
  slug: agent-loops
- description: Long-horizon strategies handle conversations and tasks that exceed the context window. Techniques include compaction (summarizing history into a smaller representation), structured note taking (persis
  name: Long-Horizon Context Strategies
  slug: long-horizon-strategies
common:
- title: ''
  type: Reference
  url: https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents
- title: ''
  type: Reference
  url: https://www.promptingguide.ai/
- title: ''
  type: Reference
  url: https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview
- title: ''
  type: Reference
  url: https://docs.llamaindex.ai/
- title: ''
  type: Reference
  url: https://python.langchain.com/docs/concepts/rag/
created: '2025-01-01'
description: Context engineering is the practice of curating the information that large language models receive at inference time so that the model can perform a task reliably and cost-effectively. It treats the context window as a finite attention budget and looks for the smallest set of high-signal tokens that maximize the likelihood of the desired outcome. Context engineering subsumes and extends prompt engineering, system prompts, tool design, retrieval, agent loops, structured note taking, compaction, and multi-agent decomposition. It is a foundational discipline for building production AI agents and assistants.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Context Engineering
skills: []
slug: context-engineering
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: context-engineering\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/context-engineering/refs/heads/main/apis.yml\nname: Context Engineering\nx-type: topic\ndescription: >-\n  Context engineering is the practice of curating the information that\n  large language models receive at inference time so that the model can\n  perform a task reliably and cost-effectively. It treats the context\n  window as a finite attention budget and looks for the smallest set of\n  high-signal tokens that maximize the likelihood of the desired outcome.\n  Context engineering subsumes and extends prompt engineering, system\n  prompts, tool design, retrieval, agent loops, structured note taking,\n  compaction, and multi-agent decomposition. It is a foundational\n  discipline for building production AI agents and assistants.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Agents\n  - AI\n  - Anthropic\n  - Compaction\n  - Context Window\n\
  \  - LLM\n  - Memory\n  - Prompt Engineering\n  - RAG\n  - Tools\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: context-engineering:anthropic-guide\n    name: Effective Context Engineering for AI Agents\n    description: >-\n      Anthropic's engineering guide to context engineering, framing context\n      as a finite attention budget and walking through system prompts, tool\n      design, few-shot examples, just-in-time retrieval, compaction,\n      structured note taking, and multi-agent architectures.\n    humanURL: https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents\n    baseURL: https://www.anthropic.com\n    tags:\n      - Anthropic\n      - Best Practices\n      - Engineering\n    properties:\n      - type: Documentation\n        url: https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents\n      - type: Reference\n        url: https://docs.anthropic.com/en/docs/agents-and-tools/agent-best-practices\n\
  \    x-features:\n      - Frames context as a finite attention budget\n      - Distinguishes context engineering from prompt engineering\n      - Covers system prompts, tools, few-shot, and retrieval\n      - Long-horizon strategies (compaction, notes, sub-agents)\n    x-useCases:\n      - Building production AI agents and assistants\n      - Tuning system prompts and toolsets for reliability\n      - Designing memory and compaction for long-running agents\n  - aid: context-engineering:retrieval-augmented-generation\n    name: Retrieval-Augmented Generation (RAG)\n    description: >-\n      RAG is a context engineering pattern that augments LLM prompts with\n      passages retrieved at inference time from a vector store, search\n      index, or knowledge base. RAG keeps facts outside the model and is\n      one of the most widely used context engineering techniques.\n    humanURL: https://arxiv.org/abs/2005.11401\n    baseURL: https://arxiv.org\n    tags:\n      - Embeddings\n      - Knowledge\
  \ Base\n      - RAG\n      - Retrieval\n    properties:\n      - type: Specification\n        url: https://arxiv.org/abs/2005.11401\n      - type: Reference\n        url: https://docs.llamaindex.ai/\n      - type: Reference\n        url: https://python.langchain.com/docs/concepts/rag/\n    x-features:\n      - Pluggable retrievers over vector and keyword indexes\n      - Pre-retrieval rewriting and post-retrieval re-ranking\n      - Hybrid retrieval combining BM25 and dense vectors\n      - Citations and grounding for answer auditing\n    x-useCases:\n      - Domain-specific question answering over private documents\n      - Customer support agents with up-to-date knowledge\n      - Long-tail factual recall outside model training\n  - aid: context-engineering:prompt-engineering\n    name: Prompt Engineering\n    description: >-\n      Prompt engineering is the discipline of crafting model instructions\n      and examples to guide model behavior. Prompt engineering remains a\n      sub-discipline\
  \ of context engineering and includes techniques like\n      role prompting, chain-of-thought, few-shot examples, and structured\n      output formats.\n    humanURL: https://www.promptingguide.ai/\n    baseURL: https://www.promptingguide.ai\n    tags:\n      - Few-Shot\n      - Instructions\n      - Prompting\n    properties:\n      - type: Documentation\n        url: https://www.promptingguide.ai/\n      - type: Reference\n        url: https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview\n      - type: Reference\n        url: https://platform.openai.com/docs/guides/prompt-engineering\n    x-features:\n      - Chain-of-thought and reasoning prompts\n      - Few-shot, zero-shot, and self-consistency prompts\n      - Structured output formatting (JSON, XML)\n      - Role and persona instructions\n    x-useCases:\n      - Steering model behavior in zero-shot tasks\n      - Eliciting structured responses suitable for downstream tools\n      - Mitigating undesired\
  \ outputs through guardrails\n  - aid: context-engineering:agent-loops\n    name: Agentic Loops and Tool Use\n    description: >-\n      Agentic loops are iterative reasoning patterns in which an LLM plans,\n      calls tools, observes results, and refines its plan. Tool design is\n      a central context engineering concern: tools must be token-efficient,\n      have minimal overlap, and include clear, motivating descriptions.\n    humanURL: https://docs.anthropic.com/en/docs/build-with-claude/tool-use/overview\n    baseURL: https://docs.anthropic.com\n    tags:\n      - Agents\n      - Function Calling\n      - ReAct\n      - Tool Use\n    properties:\n      - type: Documentation\n        url: https://docs.anthropic.com/en/docs/build-with-claude/tool-use/overview\n      - type: Reference\n        url: https://platform.openai.com/docs/guides/function-calling\n      - type: Reference\n        url: https://arxiv.org/abs/2210.03629\n    x-features:\n      - Tool definitions with JSON Schema\
  \ arguments\n      - Iterative plan-act-observe loops\n      - Parallel tool invocation\n      - Server- and client-side tool execution\n    x-useCases:\n      - Building task-completing AI agents\n      - Wiring LLMs to internal APIs and databases\n      - Decomposing complex problems with sub-tools\n  - aid: context-engineering:long-horizon-strategies\n    name: Long-Horizon Context Strategies\n    description: >-\n      Long-horizon strategies handle conversations and tasks that exceed\n      the context window. Techniques include compaction (summarizing\n      history into a smaller representation), structured note taking\n      (persistent external memory), and multi-agent decomposition where\n      sub-agents handle bounded subtasks and return condensed summaries.\n    humanURL: https://www.anthropic.com/news/contextual-retrieval\n    baseURL: https://www.anthropic.com\n    tags:\n      - Compaction\n      - Long Context\n      - Memory\n      - Multi-Agent\n    properties:\n   \
  \   - type: Documentation\n        url: https://www.anthropic.com/news/contextual-retrieval\n      - type: Reference\n        url: https://www.anthropic.com/research/swe-bench-sonnet\n      - type: Reference\n        url: https://github.com/microsoft/autogen\n    x-features:\n      - Conversation summarization for compaction\n      - Persistent memory files for cross-session knowledge\n      - Multi-agent decomposition with bounded sub-agents\n      - Hierarchical planning over long-running tasks\n    x-useCases:\n      - Long-running coding agents and SWE assistants\n      - Multi-day customer engagements requiring memory\n      - Complex research tasks decomposed across sub-agents\ncommon:\n  - type: Reference\n    url: https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents\n  - type: Reference\n    url: https://www.promptingguide.ai/\n  - type: Reference\n    url: https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview\n  - type: Reference\n\
  \    url: https://docs.llamaindex.ai/\n  - type: Reference\n    url: https://python.langchain.com/docs/concepts/rag/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/context-engineering/refs/heads/main/apis.yml
tags:
- Agents
- AI
- Anthropic
- Compaction
- Context Window
- LLM
- Memory
- Prompt Engineering
- RAG
- Tools
url: https://raw.githubusercontent.com/api-evangelist/context-engineering/refs/heads/main/apis.yml
use_cases: []
---
