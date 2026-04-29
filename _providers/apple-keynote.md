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
source_yaml: "name: Apple Keynote\ndescription: >-\n  Apple Keynote is a presentation software application developed by Apple Inc. as part\n  of the iWork productivity suite, available on macOS, iOS, iPadOS, and the web via\n  iCloud. It enables creating visually rich presentations with animations, transitions,\n  charts, and real-time collaboration. Keynote supports automation via AppleScript,\n  JavaScript for Automation (JXA), and Apple Shortcuts, and provides iCloud-based\n  access for cross-device sync and sharing.\nimage: https://www.apple.com/v/keynote/o/images/overview/keynote_icon__e6u8i7ju7e2e_large.jpg\nurl: https://www.apple.com/keynote/\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.18'\napis:\n  - name: Keynote iCloud API\n    description: >-\n      Cloud-based API for accessing and manipulating Keynote presentations through iCloud,\n      enabling programmatic creation, management, slide operations, and multi-format export\n      of presentations\
  \ stored in iCloud.\n    image: https://www.apple.com/v/keynote/o/images/overview/keynote_icon__e6u8i7ju7e2e_large.jpg\n    humanURL: https://www.icloud.com/keynote\n    baseURL: https://p00-keynote.icloud.com\n    tags:\n      - Cloud Storage\n      - Collaboration\n      - Presentations\n      - Slides\n      - iCloud\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/\n      - type: OpenAPI\n        url: openapi/apple-keynote-icloud-openapi.yaml\n      - type: JSONSchema\n        url: json-schema/apple-keynote-presentation-schema.json\n        title: Presentation Schema\n      - type: JSONSchema\n        url: json-schema/apple-keynote-slide-schema.json\n        title: Slide Schema\n      - type: JSONSchema\n        url: json-schema/apple-keynote-theme-schema.json\n        title: Theme Schema\n      - type: JSONSchema\n        url: json-schema/apple-keynote-export-request-schema.json\n        title: Export Request Schema\n    contact:\n\
  \      - FN: Apple Developer Support\n        email: developer@apple.com\n        url: https://developer.apple.com/contact/\n  - name: Keynote AppleScript API\n    description: >-\n      Local automation API for Keynote using AppleScript, enabling programmatic control\n      of presentations, slides, and elements on macOS. Access via the Open Scripting\n      Architecture dictionary.\n    humanURL: https://developer.apple.com/library/archive/documentation/AppleScript/Conceptual/AppleScriptLangGuide/\n    tags:\n      - Automation\n      - Local API\n      - macOS\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/library/archive/documentation/AppleApplications/Conceptual/KeynoteScriptingGuide/\n      - type: APIReference\n        url: https://developer.apple.com/library/archive/documentation/AppleApplications/Conceptual/KeynoteScriptingGuide/\n  - name: Keynote JavaScript for Automation API\n    description: >-\n      JavaScript-based\
  \ automation interface for controlling Keynote on macOS using the\n      Open Scripting Architecture (OSA). Provides the same capabilities as AppleScript\n      using JavaScript syntax via JXA.\n    humanURL: https://developer.apple.com/library/archive/releasenotes/InterapplicationCommunication/RN-JavaScriptForAutomation/\n    tags:\n      - Automation\n      - JavaScript\n      - macOS\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/library/archive/releasenotes/InterapplicationCommunication/RN-JavaScriptForAutomation/\n  - name: Keynote Shortcuts Actions\n    description: >-\n      Shortcuts app actions for Keynote on iOS, iPadOS, and macOS, enabling users to\n      open, create, and export presentations as part of automated workflows including\n      format conversion and template generation.\n    humanURL: https://developer.apple.com/shortcuts/\n    tags:\n      - Automation\n      - iOS\n      - Shortcuts\n      - Workflows\n\
  \    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/appintents/app-shortcuts\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Apple\n  - Design\n  - iWork\n  - Presentations\n  - Productivity\n  - Slides\ncommon:\n  - type: Portal\n    url: https://developer.apple.com/\n  - type: Documentation\n    url: https://support.apple.com/guide/keynote/\n  - type: Support\n    url: https://developer.apple.com/support/\n  - type: TermsOfService\n    url: https://developer.apple.com/support/terms/\n  - type: PrivacyPolicy\n    url: https://www.apple.com/privacy/\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/keynote\n  - type: YouTube\n    url: https://www.youtube.com/@AppleDeveloper\n  - type: JSONLD\n    url: json-ld/apple-keynote-context.jsonld\n  - type: SpectralRules\n    url: rules/apple-keynote-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apple-keynote-vocabulary.yaml\n\
  \  - type: NaftikoCapability\n    url: capabilities/shared/apple-keynote-icloud.yaml\n    title: Apple Keynote iCloud Shared Capability\n  - type: NaftikoCapability\n    url: capabilities/presentation-automation.yaml\n    title: Presentation Automation Workflow\n  - type: Features\n    data:\n      - name: Multi-Platform Availability\n        description: Available on macOS, iOS, iPadOS, and web browsers via iCloud\n      - name: Real-Time Collaboration\n        description: Multiple users can edit presentations simultaneously via iCloud sharing\n      - name: Magic Move Transitions\n        description: Intelligent morph transitions that animate elements between slides\n      - name: AppleScript Automation\n        description: Full scripting support via AppleScript and JavaScript for Automation\n      - name: Shortcuts Integration\n        description: Apple Shortcuts actions for automated presentation workflows on iOS and macOS\n      - name: Multi-Format Export\n        description:\
  \ Export to PDF, PowerPoint (.pptx), HTML, images, and native .key format\n      - name: Live Video Presenter\n        description: Present with live video overlays in video conferencing applications\n      - name: Cinematic Animations\n        description: Rich build-in and build-out animations for slide elements\n      - name: Charts and Data Visualization\n        description: Built-in chart types including bar, line, pie, scatter, and more with live data\n  - type: UseCases\n    data:\n      - name: Business Presentations\n        description: Creating professional pitch decks, board presentations, and quarterly reviews\n      - name: Educational Content\n        description: Designing lecture slides, course materials, and educational presentations\n      - name: Marketing Materials\n        description: Producing brand presentations, product launches, and sales decks\n      - name: Automated Report Generation\n        description: Using AppleScript or Shortcuts to programmatically\
  \ generate recurring presentation reports\n      - name: Conference Presentations\n        description: Creating polished conference talks with animations and transitions\n      - name: Training Materials\n        description: Building step-by-step training and onboarding presentations\n  - type: Integrations\n    data:\n      - name: iCloud Drive\n        description: Automatic sync and storage of presentations across Apple devices\n      - name: Apple Numbers\n        description: Import live chart data from Numbers spreadsheets\n      - name: Apple Pages\n        description: Cross-link documents and share content between Pages and Keynote\n      - name: Microsoft PowerPoint\n        description: Import and export PPTX files for cross-platform compatibility\n      - name: Zoom\n        description: Present directly from Keynote in Zoom video calls\n      - name: Apple Shortcuts\n        description: Automate presentation creation and export workflows on iOS and macOS\n      - name:\
  \ Spotlight\n        description: Index and search Keynote presentation content via macOS Spotlight\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apple-keynote/refs/heads/main/apis.yml
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
