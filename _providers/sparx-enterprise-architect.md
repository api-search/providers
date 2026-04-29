---
api_count: 4
apis:
- description: COM-based Automation Interface providing programmatic access to Enterprise Architect repositories, models, packages, elements, diagrams, connectors, attributes, and tagged values. Supports creating, r
  name: Enterprise Architect Automation Interface
  slug: automation-interface
- description: Framework for building custom add-ins that extend Enterprise Architect with new functionality. Add-ins can respond to application events, add custom menu items, and integrate with external systems usi
  name: Enterprise Architect Add-In Framework
  slug: add-in-framework
- description: Built-in scripting engine supporting JavaScript, JScript, and VBScript for automating tasks within Enterprise Architect. Scripts can access the full automation interface to manipulate models, generate
  name: Enterprise Architect Scripting
  slug: scripting
- description: HTTP-based API provided by the Sparx Systems Pro Cloud Server for remote access to Enterprise Architect repositories. Enables integration with web-based clients, third-party tools, and automation syst
  name: Pro Cloud Server API
  slug: pro-cloud-server-api
common:
- title: ''
  type: Documentation
  url: https://sparxsystems.com/enterprise_architect_user_guide/17.0/
- title: ''
  type: GettingStarted
  url: https://sparxsystems.com/enterprise_architect_user_guide/17.0/getting_started.htm
- title: ''
  type: Pricing
  url: https://sparxsystems.com/products/ea/pricing.html
- title: ''
  type: Support
  url: https://sparxsystems.com/support/
- title: ''
  type: FAQ
  url: https://sparxsystems.com/resources/faq/
- title: ''
  type: Training
  url: https://sparxsystems.com/training/
- title: ''
  type: ReleaseNotes
  url: https://sparxsystems.com/products/ea/release_notes.html
- title: ''
  type: Blog
  url: https://sparxsystems.com/resources/blog/
- title: ''
  type: X
  url: https://x.com/SparxSystems
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/sparx-systems/
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/SparxSystems
created: '2026-03-16'
description: Sparx Enterprise Architect is a comprehensive modeling, design, and management platform for enterprise architecture, software engineering, and systems engineering. It provides automation APIs including a COM Automation Interface, Add-In Framework, and scripting capabilities for programmatic access to models, diagrams, elements, connectors, and repository management.
features:
- description: Comprehensive support for all 14 UML 2.5 diagram types for software and systems design.
  name: UML Modeling
- description: Native ArchiMate 3.2 modeling for enterprise architecture frameworks.
  name: ArchiMate Support
- description: Business process modeling with BPMN 2.0 for workflow and process documentation.
  name: BPMN Process Modeling
- description: Generate source code in C++, Java, C#, Python, PHP, and other languages from UML models.
  name: Code Generation
- description: Import existing codebases to create UML models from source code automatically.
  name: Reverse Engineering
- description: Execute and simulate state machines and activity diagrams for validation.
  name: Model Simulation
- description: Generate rich documentation from models in RTF, HTML, PDF, and DOCX formats.
  name: Document Generation
- description: Multi-user repository access with role-based security and version control integration.
  name: Team Collaboration
image: /assets/icons/sparx-enterprise-architect.png
integrations:
- description: Integrate with Atlassian Jira for requirements traceability and issue tracking.
  name: Jira
- description: Connect to Azure DevOps for work item synchronization and version control.
  name: Azure DevOps
- description: Version control model packages with Git repositories.
  name: Git
- description: Integrate with Eclipse IDE for model-driven Java development.
  name: Eclipse
- description: Integrate with Microsoft Visual Studio for .NET development workflows.
  name: Visual Studio
layout: provider
modified: '2026-04-18'
name: Sparx Enterprise Architect
skills: []
slug: sparx-enterprise-architect
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sparx-enterprise-architect\nname: Sparx Enterprise Architect\ndescription: >-\n  Sparx Enterprise Architect is a comprehensive modeling, design, and management\n  platform for enterprise architecture, software engineering, and systems\n  engineering. It provides automation APIs including a COM Automation Interface,\n  Add-In Framework, and scripting capabilities for programmatic access to models,\n  diagrams, elements, connectors, and repository management.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sparx-enterprise-architect/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\naccess: 3rd-Party\ntags:\n  - Enterprise Architecture\n  - Modeling\n  - Software Engineering\n  - Systems Engineering\n  - UML\napis:\n  - aid: sparx-enterprise-architect:automation-interface\n    name: Enterprise Architect Automation\
  \ Interface\n    description: >-\n      COM-based Automation Interface providing programmatic access to Enterprise\n      Architect repositories, models, packages, elements, diagrams, connectors,\n      attributes, and tagged values. Supports creating, reading, updating, and\n      deleting model elements through the Repository, Element, Diagram, Package,\n      and Connector object hierarchy.\n    humanURL: https://sparxsystems.com/enterprise_architect_user_guide/17.0/automation.htm\n    tags:\n      - Automation\n      - COM\n      - Diagrams\n      - Elements\n      - Models\n      - Repository\n    properties:\n      - type: Documentation\n        url: https://sparxsystems.com/enterprise_architect_user_guide/17.0/automation.htm\n      - type: APIReference\n        url: https://sparxsystems.com/enterprise_architect_user_guide/17.0/automation_and_scripting/automation_interface.htm\n  - aid: sparx-enterprise-architect:add-in-framework\n    name: Enterprise Architect Add-In Framework\n\
  \    description: >-\n      Framework for building custom add-ins that extend Enterprise Architect\n      with new functionality. Add-ins can respond to application events, add\n      custom menu items, and integrate with external systems using COM\n      interop from .NET, Java, or other languages.\n    humanURL: https://sparxsystems.com/enterprise_architect_user_guide/17.0/add-ins_2.htm\n    tags:\n      - Add-Ins\n      - Extensions\n      - Plugins\n    properties:\n      - type: Documentation\n        url: https://sparxsystems.com/enterprise_architect_user_guide/17.0/add-ins_2.htm\n  - aid: sparx-enterprise-architect:scripting\n    name: Enterprise Architect Scripting\n    description: >-\n      Built-in scripting engine supporting JavaScript, JScript, and VBScript\n      for automating tasks within Enterprise Architect. Scripts can access the\n      full automation interface to manipulate models, generate reports, validate\n      models, and perform bulk operations.\n    humanURL:\
  \ https://sparxsystems.com/enterprise_architect_user_guide/17.0/scripting.htm\n    tags:\n      - Automation\n      - JavaScript\n      - Scripting\n      - VBScript\n    properties:\n      - type: Documentation\n        url: https://sparxsystems.com/enterprise_architect_user_guide/17.0/scripting.htm\n  - aid: sparx-enterprise-architect:pro-cloud-server-api\n    name: Pro Cloud Server API\n    description: >-\n      HTTP-based API provided by the Sparx Systems Pro Cloud Server for remote\n      access to Enterprise Architect repositories. Enables integration with\n      web-based clients, third-party tools, and automation systems via REST-like\n      endpoints for model queries and operations.\n    humanURL: https://sparxsystems.com/enterprise_architect_user_guide/17.0/pcs_overview.htm\n    tags:\n      - Cloud\n      - HTTP\n      - Remote Access\n      - Repository\n    properties:\n      - type: Documentation\n        url: https://sparxsystems.com/enterprise_architect_user_guide/17.0/pcs_overview.htm\n\
  common:\n  - type: Documentation\n    url: https://sparxsystems.com/enterprise_architect_user_guide/17.0/\n  - type: GettingStarted\n    url: https://sparxsystems.com/enterprise_architect_user_guide/17.0/getting_started.htm\n  - type: Pricing\n    url: https://sparxsystems.com/products/ea/pricing.html\n  - type: Support\n    url: https://sparxsystems.com/support/\n  - type: FAQ\n    url: https://sparxsystems.com/resources/faq/\n  - type: Training\n    url: https://sparxsystems.com/training/\n  - type: ReleaseNotes\n    url: https://sparxsystems.com/products/ea/release_notes.html\n  - type: Blog\n    url: https://sparxsystems.com/resources/blog/\n  - type: X\n    url: https://x.com/SparxSystems\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/sparx-systems/\n  - type: YouTube\n    url: https://www.youtube.com/user/SparxSystems\n  - type: Features\n    data:\n      - name: UML Modeling\n        description: Comprehensive support for all 14 UML 2.5 diagram types for software\
  \ and systems design.\n      - name: ArchiMate Support\n        description: Native ArchiMate 3.2 modeling for enterprise architecture frameworks.\n      - name: BPMN Process Modeling\n        description: Business process modeling with BPMN 2.0 for workflow and process documentation.\n      - name: Code Generation\n        description: Generate source code in C++, Java, C#, Python, PHP, and other languages from UML models.\n      - name: Reverse Engineering\n        description: Import existing codebases to create UML models from source code automatically.\n      - name: Model Simulation\n        description: Execute and simulate state machines and activity diagrams for validation.\n      - name: Document Generation\n        description: Generate rich documentation from models in RTF, HTML, PDF, and DOCX formats.\n      - name: Team Collaboration\n        description: Multi-user repository access with role-based security and version control integration.\n  - type: UseCases\n    data:\n\
  \      - name: Enterprise Architecture Governance\n        description: Define and maintain enterprise architecture models aligned with TOGAF, Zachman, or ArchiMate frameworks.\n      - name: Software Design Documentation\n        description: Create detailed software designs with UML class, sequence, and component diagrams.\n      - name: Requirements Management\n        description: Capture, trace, and manage requirements from stakeholder needs through to implementation.\n      - name: Database Design\n        description: Model database schemas with ER diagrams and generate DDL scripts for multiple databases.\n      - name: Model-Driven Development\n        description: Use models as the primary artifact for generating code, tests, and documentation.\n  - type: Integrations\n    data:\n      - name: Jira\n        description: Integrate with Atlassian Jira for requirements traceability and issue tracking.\n      - name: Azure DevOps\n        description: Connect to Azure DevOps for work\
  \ item synchronization and version control.\n      - name: Git\n        description: Version control model packages with Git repositories.\n      - name: Eclipse\n        description: Integrate with Eclipse IDE for model-driven Java development.\n      - name: Visual Studio\n        description: Integrate with Microsoft Visual Studio for .NET development workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sparx-enterprise-architect/refs/heads/main/apis.yml
tags:
- Enterprise Architecture
- Modeling
- Software Engineering
- Systems Engineering
- UML
url: https://raw.githubusercontent.com/api-evangelist/sparx-enterprise-architect/refs/heads/main/apis.yml
use_cases:
- description: Define and maintain enterprise architecture models aligned with TOGAF, Zachman, or ArchiMate frameworks.
  name: Enterprise Architecture Governance
- description: Create detailed software designs with UML class, sequence, and component diagrams.
  name: Software Design Documentation
- description: Capture, trace, and manage requirements from stakeholder needs through to implementation.
  name: Requirements Management
- description: Model database schemas with ER diagrams and generate DDL scripts for multiple databases.
  name: Database Design
- description: Use models as the primary artifact for generating code, tests, and documentation.
  name: Model-Driven Development
---
