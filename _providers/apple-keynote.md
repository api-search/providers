---
api_count: 4
apis:
- description: Cloud-based API for accessing and manipulating Keynote presentations through iCloud, enabling programmatic creation, management, slide operations, and multi-format export of presentations stored in iC
  name: Keynote iCloud API
  slug: ''
- description: Local automation API for Keynote using AppleScript, enabling programmatic control of presentations, slides, and elements on macOS. Access via the Open Scripting Architecture dictionary.
  name: Keynote AppleScript API
  slug: ''
- description: JavaScript-based automation interface for controlling Keynote on macOS using the Open Scripting Architecture (OSA). Provides the same capabilities as AppleScript using JavaScript syntax via JXA.
  name: Keynote JavaScript for Automation API
  slug: ''
- description: Shortcuts app actions for Keynote on iOS, iPadOS, and macOS, enabling users to open, create, and export presentations as part of automated workflows including format conversion and template generation
  name: Keynote Shortcuts Actions
  slug: ''
capabilities:
- description: 'Workflow capability for automating Keynote presentation creation and management via iCloud. Combines presentation lifecycle management, slide operations, theme selection, and multi-format export into '
  name: Apple Keynote Presentation Automation
  slug: presentation-automation
common:
- title: ''
  type: Portal
  url: https://developer.apple.com/
- title: ''
  type: Documentation
  url: https://support.apple.com/guide/keynote/
- title: ''
  type: Support
  url: https://developer.apple.com/support/
- title: ''
  type: TermsOfService
  url: https://developer.apple.com/support/terms/
- title: ''
  type: PrivacyPolicy
  url: https://www.apple.com/privacy/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/keynote
- title: ''
  type: YouTube
  url: https://www.youtube.com/@AppleDeveloper
- title: ''
  type: JSONLD
  url: json-ld/apple-keynote-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/apple-keynote-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apple-keynote-vocabulary.yaml
- title: Apple Keynote iCloud Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/apple-keynote-icloud.yaml
- title: Presentation Automation Workflow
  type: NaftikoCapability
  url: capabilities/presentation-automation.yaml
created: '2024-01-01'
description: Apple Keynote is a presentation software application developed by Apple Inc. as part of the iWork productivity suite, available on macOS, iOS, iPadOS, and the web via iCloud. It enables creating visually rich presentations with animations, transitions, charts, and real-time collaboration. Keynote supports automation via AppleScript, JavaScript for Automation (JXA), and Apple Shortcuts, and provides iCloud-based access for cross-device sync and sharing.
features:
- description: Available on macOS, iOS, iPadOS, and web browsers via iCloud
  name: Multi-Platform Availability
- description: Multiple users can edit presentations simultaneously via iCloud sharing
  name: Real-Time Collaboration
- description: Intelligent morph transitions that animate elements between slides
  name: Magic Move Transitions
- description: Full scripting support via AppleScript and JavaScript for Automation
  name: AppleScript Automation
- description: Apple Shortcuts actions for automated presentation workflows on iOS and macOS
  name: Shortcuts Integration
- description: Export to PDF, PowerPoint (.pptx), HTML, images, and native .key format
  name: Multi-Format Export
- description: Present with live video overlays in video conferencing applications
  name: Live Video Presenter
- description: Rich build-in and build-out animations for slide elements
  name: Cinematic Animations
- description: Built-in chart types including bar, line, pie, scatter, and more with live data
  name: Charts and Data Visualization
image: https://www.apple.com/v/keynote/o/images/overview/keynote_icon__e6u8i7ju7e2e_large.jpg
integrations:
- description: Automatic sync and storage of presentations across Apple devices
  name: iCloud Drive
- description: Import live chart data from Numbers spreadsheets
  name: Apple Numbers
- description: Cross-link documents and share content between Pages and Keynote
  name: Apple Pages
- description: Import and export PPTX files for cross-platform compatibility
  name: Microsoft PowerPoint
- description: Present directly from Keynote in Zoom video calls
  name: Zoom
- description: Automate presentation creation and export workflows on iOS and macOS
  name: Apple Shortcuts
- description: Index and search Keynote presentation content via macOS Spotlight
  name: Spotlight
jsonld:
- class_count: 9
  name: Apple Keynote Context
  property_count: 17
  slug: apple-keynote-context
layout: provider
modified: '2026-04-19'
name: Apple Keynote
rules:
- name: Apple Keynote API Rules
  rule_count: 22
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 13
  slug: apple-keynote-spectral-rules
skills: []
slug: apple-keynote
solutions: []
tags:
- Apple
- Design
- iWork
- Presentations
- Productivity
- Slides
url: https://www.apple.com/keynote/
use_cases:
- description: Creating professional pitch decks, board presentations, and quarterly reviews
  name: Business Presentations
- description: Designing lecture slides, course materials, and educational presentations
  name: Educational Content
- description: Producing brand presentations, product launches, and sales decks
  name: Marketing Materials
- description: Using AppleScript or Shortcuts to programmatically generate recurring presentation reports
  name: Automated Report Generation
- description: Creating polished conference talks with animations and transitions
  name: Conference Presentations
- description: Building step-by-step training and onboarding presentations
  name: Training Materials
---
