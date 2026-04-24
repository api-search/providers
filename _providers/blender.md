---
api_count: 2
apis:
- description: The Blender Python API (bpy) provides Python access to Blender's internal data, operators, and UI components. It enables developers to automate tasks, create addons, build custom tools, manipulate sce
  name: Blender Python API
  slug: blender-python-api
- description: The Blender Extensions Platform (extensions.blender.org) provides a curated repository of addons, themes, and node presets for Blender. The platform supports structured addon packaging, versioning, an
  name: Blender Extensions Platform
  slug: blender-extensions
capabilities:
- description: ''
  name: Blender Python Api
  slug: blender-python-api
common:
- title: ''
  type: Website
  url: https://www.blender.org/
- title: ''
  type: Documentation
  url: https://docs.blender.org/
- title: ''
  type: GettingStarted
  url: https://docs.blender.org/api/current/info_quickstart.html
- title: ''
  type: Community
  url: https://www.blender.org/community/
- title: ''
  type: Support
  url: https://www.blender.org/support/
- title: ''
  type: GitHubOrganization
  url: https://github.com/blender
- title: ''
  type: GitHub
  url: https://github.com/blender/blender
- title: ''
  type: Blog
  url: https://www.blender.org/news/
- title: ''
  type: Training
  url: https://www.blender.org/training/
- title: ''
  type: FAQ
  url: https://www.blender.org/support/faq/
- title: ''
  type: ReleaseNotes
  url: https://developer.blender.org/docs/release_notes/
- title: GPL-2.0-or-later
  type: License
  url: https://www.blender.org/about/license/
- title: ''
  type: PackageRegistry
  url: https://extensions.blender.org
- title: ''
  type: SpectralRules
  url: rules/blender-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/blender-python-api.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/blender-vocabulary.yaml
created: '2024-01-01'
description: Blender is the free and open source 3D creation suite supporting the entirety of the 3D pipeline including modeling, rigging, animation, simulation, rendering, compositing, motion tracking, video editing, and game creation. Blender's Python API provides extensive scripting capabilities for automation, tool development, and addon creation, enabling developers to extend Blender with custom functionality. The project is governed by the Blender Foundation and maintained at blender.org.
features:
- description: The bpy module provides access to Blender's internal data model, allowing Python scripts to create, read, update, and delete scene objects, materials, animations, constraints, and render settings.
  name: Python Scripting (bpy)
- description: Blender's operator system allows Python developers to create custom operators (commands) accessible from menus, panels, keyboard shortcuts, and scripts.
  name: Operator Framework
- description: Blender addons are Python packages extending functionality across modeling, rigging, animation, rendering, import/export, and UI. Distributed via the Extensions Platform or bundled directly.
  name: Addon Development
- description: Geometry Nodes and Shader Nodes provide visual programming for procedural modeling and materials, scriptable via the Python API.
  name: Node Groups and Geometry Nodes
- description: Python API integrates with Blender's Cycles and EEVEE render engines for batch rendering, render farm integration, and custom render pipeline control.
  name: Render Pipeline Integration
- description: Blender can be invoked headlessly via CLI for batch rendering, script execution, and pipeline automation without a GUI.
  name: Command-Line Interface
- description: Blender 3.x+ includes an asset library system with Python API support for managing and accessing reusable 3D assets across projects.
  name: Asset Library System
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Blender's built-in path-tracing render engine with Python API access for controlling render settings, passes, and denoising.
  name: Cycles X Render Engine
- description: Blender supports import and export of Pixar USD scenes, enabling pipeline integration with VFX and game development workflows.
  name: USD (Universal Scene Description)
- description: Blender has built-in glTF 2.0 import/export support with Python API access, enabling web, AR/VR, and game engine pipelines.
  name: glTF 2.0
- description: Blender supports OpenVDB for volumetric simulation and rendering, with Python API access to volume data and simulation parameters.
  name: OpenVDB
- description: Blender integrates with OpenColorIO for ACES and professional color pipeline support in VFX productions.
  name: ACES Color Management
jsonld:
- class_count: 11
  name: Blender Context
  property_count: 0
  slug: blender-context
layout: provider
modified: '2026-04-21'
name: Blender
rules:
- name: Blender API Rules
  rule_count: 5
  severity_counts:
    error: 0
    hint: 0
    info: 0
    warn: 5
  slug: blender-spectral-rules
skills: []
slug: blender
solutions: []
tags:
- 3D
- Animation
- Game Development
- Modeling
- Open Source
- Python
- Rendering
- VFX
url: https://raw.githubusercontent.com/api-evangelist/blender/refs/heads/main/apis.yml
use_cases:
- description: VFX and animation studios automate Blender production pipelines using Python scripts for batch rendering, asset processing, and scene assembly.
  name: Pipeline Automation
- description: Developers create custom tools and plugins extending Blender's functionality for modeling, rigging, simulation, and export workflows.
  name: Addon Development
- description: Blender is used for headless server-side rendering via CLI and Python scripts in cloud rendering pipelines and automated content generation workflows.
  name: Headless Rendering
- description: Python scripts and Geometry Nodes enable procedural generation of 3D assets for games, VFX, and architectural visualization.
  name: Procedural Content Generation
- description: Universities, research labs, and educators use Blender's Python API for 3D visualization, scientific rendering, and computer graphics research.
  name: Education and Research
---
