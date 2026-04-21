---
api_count: 1
apis:
- description: Apache Cordova provides a JavaScript plugin API for accessing native device capabilities (camera, GPS, file system, contacts, etc.), a CLI for project management and multi-platform builds, a plugin de
  name: Apache Cordova
  slug: apache-cordova
common:
- title: ''
  type: Portal
  url: https://cordova.apache.org/
- title: ''
  type: Blog
  url: https://cordova.apache.org/blog/
- title: ''
  type: ReleaseNotes
  url: https://cordova.apache.org/blog/
- title: ''
  type: Documentation
  url: https://cordova.apache.org/docs/en/latest/
- title: ''
  type: GettingStarted
  url: https://cordova.apache.org/docs/en/latest/guide/overview/
- title: ''
  type: Support
  url: https://cordova.apache.org/contact/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/cordova
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: CLI
  url: https://github.com/apache/cordova-cli
- title: Plugman Plugin Manager
  type: Tools
  url: https://github.com/apache/cordova-plugman
- title: Paramedic Test Runner
  type: Tools
  url: https://github.com/apache/cordova-paramedic
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/vocabulary/apache-cordova-vocabulary.yaml
created: '2026-03-16'
description: Apache Cordova is an open-source mobile development framework governed by the Apache Software Foundation that enables developers to build mobile applications using standard web technologies — HTML, CSS, and JavaScript. It bridges web code to native device capabilities through a plugin architecture, targeting iOS, Android, Electron, and Browser platforms from a single codebase.
features:
- description: Extensible plugin system that bridges JavaScript to native device APIs for camera, GPS, file system, contacts, battery, and more.
  name: Plugin Architecture
- description: Command-line interface for creating, building, testing, and deploying applications to multiple platforms from a single codebase.
  name: Cross-Platform CLI
- description: Access to native hardware capabilities including camera, geolocation, network information, vibration, media capture, and device info.
  name: Native Device Access
- description: Renders applications in a native WebView, enabling web technologies to run as native mobile apps on iOS, Android, and Electron.
  name: WebView-Based Runtime
- description: Full API for creating custom native plugins in Swift/Objective-C (iOS) and Java/Kotlin (Android) that expose device APIs to JavaScript.
  name: Plugin Development API
- description: Built-in allowlist mechanism for controlling which URLs and resources the application is permitted to access.
  name: Allowlist Security
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Ionic uses Cordova (and Capacitor) as its native runtime, providing UI components on top of the Cordova platform.
  name: Ionic Framework
- description: PhoneGap was a commercial distribution of Apache Cordova, now retired, but helped establish the Cordova ecosystem.
  name: Adobe PhoneGap
- description: Cordova plugins and the CLI are published and distributed via npm, the Node.js package registry.
  name: npm Package Registry
- description: Android platform builds use Gradle for dependency management and compilation.
  name: Gradle (Android)
- description: iOS platform builds require Xcode for compilation, signing, and deployment.
  name: Xcode (iOS)
- description: Cordova-Electron platform target allows packaging Cordova apps as desktop Electron applications.
  name: Electron
jsonld:
- class_count: 1
  name: Apache Cordova Camera Context
  property_count: 11
  slug: apache-cordova-camera-context
- class_count: 5
  name: Apache Cordova Config Context
  property_count: 11
  slug: apache-cordova-config-context
- class_count: 1
  name: Apache Cordova Geolocation Context
  property_count: 9
  slug: apache-cordova-geolocation-context
layout: provider
modified: '2026-04-19'
name: Apache Cordova
skills: []
slug: apache-cordova
solutions: []
tags:
- Apache
- Cross-Platform
- Hybrid Apps
- JavaScript
- Mobile
- Open Source
- Plugins
url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/apis.yml
use_cases:
- description: Build iOS and Android apps from a single HTML/CSS/JavaScript codebase, reducing development time and cost.
  name: Cross-Platform Mobile Apps
- description: Combine web application UIs with native device capabilities for apps that need both web flexibility and native hardware access.
  name: Hybrid App Development
- description: Rapidly prototype and deploy enterprise mobile applications leveraging existing web development skills.
  name: Enterprise Mobile Solutions
- description: Package web apps as Electron desktop applications using the same Cordova plugin model.
  name: Desktop Apps via Electron
- description: Interface with Bluetooth, sensors, and other hardware through community and custom Cordova plugins.
  name: IoT and Device Interfaces
---
