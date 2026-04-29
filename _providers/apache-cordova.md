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
source_yaml: "aid: apache-cordova\nname: Apache Cordova\ndescription: >-\n  Apache Cordova is an open-source mobile development framework governed by the Apache Software Foundation that enables developers to build mobile applications using standard web technologies — HTML, CSS,\n  and JavaScript. It bridges web code to native device capabilities through a plugin architecture, targeting iOS, Android, Electron, and Browser platforms from a single codebase.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Apache\n- Cross-Platform\n- Hybrid Apps\n- JavaScript\n- Mobile\n- Open Source\n- Plugins\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-cordova:apache-cordova\n  name: Apache Cordova\n  description: >-\n    Apache Cordova provides a JavaScript\
  \ plugin API for accessing native device capabilities (camera, GPS, file system, contacts, etc.), a CLI for project management and multi-platform builds, a plugin\n    development API for creating native bridges, and platform-specific runtimes for iOS, Android, and Electron.\n  humanURL: https://cordova.apache.org/docs/en/latest/\n  tags:\n  - Android\n  - CLI\n  - Electron\n  - iOS\n  - JavaScript\n  - Mobile\n  - Plugins\n  properties:\n  - type: Documentation\n    url: https://cordova.apache.org/docs/en/latest/\n  - type: GettingStarted\n    url: https://cordova.apache.org/docs/en/latest/guide/overview/\n  - type: APIReference\n    url: https://cordova.apache.org/docs/en/latest/config_ref/\n  - type: CLI\n    url: https://github.com/apache/cordova-cli\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova\n    title: npm Package\n  - type: GitHubRepository\n    url: https://github.com/apache/cordova\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type:\
  \ SDK\n    url: https://www.npmjs.com/package/cordova-android\n    title: Android Platform\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-ios\n    title: iOS Platform\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-electron\n    title: Electron Platform\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-browser\n    title: Browser Platform\n  - type: SDK\n    url: https://github.com/apache/cordova-js\n    title: JavaScript Bridge\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-camera\n    title: Camera Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-file\n    title: File Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-geolocation\n    title: Geolocation Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-inappbrowser\n    title: InAppBrowser Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-media\n    title: Media\
  \ Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-media-capture\n    title: Media Capture Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-dialogs\n    title: Dialogs Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-device\n    title: Device Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-network-information\n    title: Network Information Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-vibration\n    title: Vibration Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-battery-status\n    title: Battery Status Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-screen-orientation\n    title: Screen Orientation Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-statusbar\n    title: Statusbar Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-device-motion\n\
  \    title: Device Motion Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-device-orientation\n    title: Device Orientation Plugin\n  - type: SDK\n    url: https://www.npmjs.com/package/cordova-plugin-file-transfer\n    title: File Transfer Plugin\n  - type: Tools\n    url: https://github.com/apache/cordova-plugman\n    title: Plugman Plugin Manager\n  - type: CodeExamples\n    url: https://github.com/apache/cordova-app-hello-world\n    title: Hello World Template\n  - type: CodeExamples\n    url: https://github.com/apache/cordova-mobile-spec\n    title: Mobile Spec Test Suite\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/json-schema/apache-cordova-camera-options-schema.json\n    title: Camera Options\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/json-schema/apache-cordova-config-widget-schema.json\n    title: Config Widget\n \
  \ - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/json-schema/apache-cordova-geolocation-position-schema.json\n    title: Geolocation Position\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/json-structure/apache-cordova-camera-options-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/json-structure/apache-cordova-config-widget-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/json-structure/apache-cordova-geolocation-position-structure.json\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/json-ld/apache-cordova-camera-context.jsonld\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/json-ld/apache-cordova-config-context.jsonld\n\
  \  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/json-ld/apache-cordova-geolocation-context.jsonld\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/examples/apache-cordova-camera-options-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/examples/apache-cordova-config-widget-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/examples/apache-cordova-geolocation-position-example.json\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: Portal\n  url: https://cordova.apache.org/\n- type: Blog\n  url: https://cordova.apache.org/blog/\n- type: ReleaseNotes\n  url: https://cordova.apache.org/blog/\n- type: Documentation\n  url: https://cordova.apache.org/docs/en/latest/\n- type: GettingStarted\n  url: https://cordova.apache.org/docs/en/latest/guide/overview/\n\
  - type: Support\n  url: https://cordova.apache.org/contact/\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/cordova\n- type: GitHubOrganization\n  url: https://github.com/apache\n- type: Features\n  data:\n  - name: Plugin Architecture\n    description: Extensible plugin system that bridges JavaScript to native device APIs for camera, GPS, file system, contacts, battery, and more.\n  - name: Cross-Platform CLI\n    description: Command-line interface for creating, building, testing, and deploying applications to multiple platforms from a single codebase.\n  - name: Native Device Access\n    description: Access to native hardware capabilities including camera, geolocation, network information, vibration, media capture, and device info.\n  - name: WebView-Based Runtime\n    description: Renders applications in a native WebView, enabling web technologies to run as native mobile apps on iOS, Android, and Electron.\n  - name: Plugin Development API\n    description:\
  \ Full API for creating custom native plugins in Swift/Objective-C (iOS) and Java/Kotlin (Android) that expose device APIs to JavaScript.\n  - name: Allowlist Security\n    description: Built-in allowlist mechanism for controlling which URLs and resources the application is permitted to access.\n- type: UseCases\n  data:\n  - name: Cross-Platform Mobile Apps\n    description: Build iOS and Android apps from a single HTML/CSS/JavaScript codebase, reducing development time and cost.\n  - name: Hybrid App Development\n    description: Combine web application UIs with native device capabilities for apps that need both web flexibility and native hardware access.\n  - name: Enterprise Mobile Solutions\n    description: Rapidly prototype and deploy enterprise mobile applications leveraging existing web development skills.\n  - name: Desktop Apps via Electron\n    description: Package web apps as Electron desktop applications using the same Cordova plugin model.\n  - name: IoT and Device Interfaces\n\
  \    description: Interface with Bluetooth, sensors, and other hardware through community and custom Cordova plugins.\n- type: Integrations\n  data:\n  - name: Ionic Framework\n    description: Ionic uses Cordova (and Capacitor) as its native runtime, providing UI components on top of the Cordova platform.\n  - name: Adobe PhoneGap\n    description: PhoneGap was a commercial distribution of Apache Cordova, now retired, but helped establish the Cordova ecosystem.\n  - name: npm Package Registry\n    description: Cordova plugins and the CLI are published and distributed via npm, the Node.js package registry.\n  - name: Gradle (Android)\n    description: Android platform builds use Gradle for dependency management and compilation.\n  - name: Xcode (iOS)\n    description: iOS platform builds require Xcode for compilation, signing, and deployment.\n  - name: Electron\n    description: Cordova-Electron platform target allows packaging Cordova apps as desktop Electron applications.\n- type: CLI\n\
  \  url: https://github.com/apache/cordova-cli\n- type: Tools\n  url: https://github.com/apache/cordova-plugman\n  title: Plugman Plugin Manager\n- type: Tools\n  url: https://github.com/apache/cordova-paramedic\n  title: Paramedic Test Runner\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/vocabulary/apache-cordova-vocabulary.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/apis.yml
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
