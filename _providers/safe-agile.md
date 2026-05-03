---
api_count: 5
apis:
- description: The official Scaled Agile Framework by Scaled Agile, Inc. provides comprehensive guidance for enterprise agile transformation including roles, events, artifacts, and competencies for Lean Portfolio Ma
  name: Scaled Agile Framework (SAFe)
  slug: scaledagile-framework
- description: Jira by Atlassian provides SAFe-aligned project management and PI planning capabilities through the Advanced Roadmaps feature and SAFe-compatible workflows for Agile Release Trains, Epics, Features, a
  name: Jira SAFe Integration
  slug: jira-safe
- description: Azure DevOps provides SAFe-aligned planning and tracking through work item types aligned to SAFe hierarchy (Epics, Features, User Stories), delivery plans for Program Increment visualization, and REST
  name: Azure DevOps SAFe Integration
  slug: azure-devops-safe
- description: Planview provides enterprise agile planning supporting SAFe through its portfolio management, Lean flow, and Agile delivery capabilities. Enables organizations to connect strategy to delivery across m
  name: Planview SAFe Tool
  slug: planview-safe
- description: SpiraPlan by Inflectra is an enterprise agile portfolio and risk management platform that supports SAFe, Nexus, Scrum of Scrums, and LeSS frameworks. Provides REST API for programmatic access to portf
  name: SpiraPlan SAFe Tool
  slug: spiraplan-safe
common:
- title: ''
  type: Website
  url: https://scaledagile.com/
- title: ''
  type: Documentation
  url: https://framework.scaledagile.com/
- title: ''
  type: Blog
  url: https://scaledagile.com/blog/
- title: ''
  type: Certification
  url: https://scaledagile.com/training/find-training-provider/
- title: ''
  type: JSONSchema
  url: json-schema/safe-agile-program-increment-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/safe-agile-art-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/safe-agile-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/safe-agile-vocabulary.yml
created: '2025'
description: 'The Scaled Agile Framework (SAFe) is an enterprise-scale agile framework developed by Scaled Agile, Inc. that provides guidance for implementing agile practices across large organizations with multiple teams. SAFe organizes around five core disciplines: Lean Portfolio Management, Team and Technical Agility, Product Development Flow, Large Solution Integration and Delivery, and Leadership and Culture. Organizations use SAFe to align stakeholders, coordinate Agile Release Trains (ARTs), track PI objectives, and accelerate delivery of value. SAFe tools integrate with CI/CD pipelines, ERP systems, and planning platforms to support enterprise agile transformation.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 30
  name: Safe Agile Context
  property_count: 0
  slug: safe-agile-context
layout: provider
modified: '2026-05-02'
name: SAFe Agile
skills: []
slug: safe-agile
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: safe-agile\nname: SAFe Agile\ndescription: >-\n  The Scaled Agile Framework (SAFe) is an enterprise-scale agile framework\n  developed by Scaled Agile, Inc. that provides guidance for implementing agile\n  practices across large organizations with multiple teams. SAFe organizes\n  around five core disciplines: Lean Portfolio Management, Team and Technical\n  Agility, Product Development Flow, Large Solution Integration and Delivery,\n  and Leadership and Culture. Organizations use SAFe to align stakeholders,\n  coordinate Agile Release Trains (ARTs), track PI objectives, and accelerate\n  delivery of value. SAFe tools integrate with CI/CD pipelines, ERP systems,\n  and planning platforms to support enterprise agile transformation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Agile\n  - Enterprise\n  - Framework\n  - Project Management\n  - Scaled Agile\n  - Lean Portfolio\n  - DevOps\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/safe-agile/refs/heads/main/apis.yml\n\
  created: '2025'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: safe-agile:scaledagile-framework\n    name: Scaled Agile Framework (SAFe)\n    description: >-\n      The official Scaled Agile Framework by Scaled Agile, Inc. provides\n      comprehensive guidance for enterprise agile transformation including roles,\n      events, artifacts, and competencies for Lean Portfolio Management, Agile\n      Release Trains, and PI Planning. Includes SAFe CoPilot AI assistant,\n      certification programs, and the annual State of SAFe report.\n    humanURL: https://framework.scaledagile.com/\n    tags:\n      - Agile\n      - Enterprise\n      - Framework\n      - Scaled Agile\n    properties:\n      - type: Documentation\n        url: https://framework.scaledagile.com/\n      - type: Website\n        url: https://scaledagile.com/\n\n  - aid: safe-agile:jira-safe\n    name: Jira SAFe Integration\n    description: >-\n      Jira by Atlassian provides SAFe-aligned project management\
  \ and PI planning\n      capabilities through the Advanced Roadmaps feature and SAFe-compatible\n      workflows for Agile Release Trains, Epics, Features, and Stories. Jira's\n      REST API enables programmatic management of SAFe backlogs, sprints, and\n      program increments.\n    humanURL: https://www.atlassian.com/agile/safe\n    tags:\n      - Agile\n      - Project Management\n      - SAFe\n      - PI Planning\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.atlassian.com/cloud/jira/software/rest/intro/\n      - type: Website\n        url: https://www.atlassian.com/agile/safe\n\n  - aid: safe-agile:azure-devops-safe\n    name: Azure DevOps SAFe Integration\n    description: >-\n      Azure DevOps provides SAFe-aligned planning and tracking through work item\n      types aligned to SAFe hierarchy (Epics, Features, User Stories), delivery\n      plans for Program Increment visualization, and REST APIs for programmatic\n      access to backlogs,\
  \ iterations, and boards.\n    humanURL: https://learn.microsoft.com/en-us/azure/devops/\n    tags:\n      - Agile\n      - DevOps\n      - SAFe\n      - REST\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/devops/integrate/\n      - type: Website\n        url: https://azure.microsoft.com/en-us/products/devops/\n\n  - aid: safe-agile:planview-safe\n    name: Planview SAFe Tool\n    description: >-\n      Planview provides enterprise agile planning supporting SAFe through its\n      portfolio management, Lean flow, and Agile delivery capabilities.\n      Enables organizations to connect strategy to delivery across multiple\n      ARTs with real-time program board visualization and PI planning support.\n    humanURL: https://www.planview.com/resources/articles/safe-agile/\n    tags:\n      - Agile\n      - Portfolio Management\n      - SAFe\n      - Enterprise Planning\n    properties:\n      - type: Documentation\n        url: https://success.planview.com/\n\
  \      - type: Website\n        url: https://www.planview.com/\n\n  - aid: safe-agile:spiraplan-safe\n    name: SpiraPlan SAFe Tool\n    description: >-\n      SpiraPlan by Inflectra is an enterprise agile portfolio and risk management\n      platform that supports SAFe, Nexus, Scrum of Scrums, and LeSS frameworks.\n      Provides REST API for programmatic access to portfolio, program, and team\n      level planning artifacts.\n    humanURL: https://www.inflectra.com/SpiraPlan/\n    tags:\n      - Agile\n      - Portfolio Management\n      - SAFe\n      - REST\n    properties:\n      - type: Documentation\n        url: https://www.inflectra.com/Support/KnowledgeBase/\n      - type: Website\n        url: https://www.inflectra.com/SpiraPlan/\n\ncommon:\n  - type: Website\n    url: https://scaledagile.com/\n  - type: Documentation\n    url: https://framework.scaledagile.com/\n  - type: Blog\n    url: https://scaledagile.com/blog/\n  - type: Certification\n    url: https://scaledagile.com/training/find-training-provider/\n\
  \  - type: JSONSchema\n    url: json-schema/safe-agile-program-increment-schema.json\n  - type: JSONStructure\n    url: json-structure/safe-agile-art-structure.json\n  - type: JSONLDContext\n    url: json-ld/safe-agile-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/safe-agile-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/safe-agile/refs/heads/main/apis.yml
tags:
- Agile
- Enterprise
- Framework
- Project Management
- Scaled Agile
- Lean Portfolio
- DevOps
url: https://raw.githubusercontent.com/api-evangelist/safe-agile/refs/heads/main/apis.yml
use_cases: []
---
