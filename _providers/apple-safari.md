---
api_count: 9
apis:
- description: API for building Safari Web Extensions that extend and customize the browsing experience.
  name: Safari Extensions API
  slug: ''
- description: API for creating app extensions that add features and functionality to Safari on macOS.
  name: Safari App Extensions API
  slug: ''
- description: WebKit APIs for interacting with web content, including JavaScript evaluation and DOM manipulation.
  name: Safari Web Content API
  slug: ''
- description: iOS and macOS API for integrating Safari functionality into apps, including Safari View Controller.
  name: Safari Services API
  slug: ''
- description: API for sending push notifications to users through Safari on macOS, iOS, and iPadOS using the Push API, Notifications API, and Service Workers.
  name: Safari Web Push API
  slug: ''
- description: API for creating content blockers and declarative content blocking rules in Safari web extensions to filter and block web content.
  name: Safari Content Blocking API
  slug: ''
- description: APIs and tools for inspecting, debugging, and optimizing web content in Safari, including Web Inspector and the ability to add custom web development tools.
  name: Safari Developer Tools API
  slug: ''
- description: API for authenticating users through web services in Safari using ASWebAuthenticationSession, supporting OAuth, passkeys, and WebAuthn standards.
  name: Safari Authentication Services API
  slug: ''
- description: JavaScript APIs for implementing Apple Pay payments in Safari, supporting both the Apple Pay JS API and the Payment Request API.
  name: Apple Pay on the Web API
  slug: ''
common:
- title: ''
  type: DeveloperPortal
  url: https://developer.apple.com/safari/
- title: ''
  type: ReleaseNotes
  url: https://developer.apple.com/documentation/safari-release-notes
- title: ''
  type: Resources
  url: https://developer.apple.com/safari/resources/
- title: ''
  type: Blog
  url: https://webkit.org/blog/
- title: ''
  type: Documentation
  url: https://docs.webkit.org/
- title: ''
  type: YouTube
  url: https://developer.apple.com/videos/safari-web/
- title: ''
  type: Support
  url: https://developer.apple.com/forums/
created: '2024'
description: Apple's web browser available across macOS, iOS, and iPadOS, providing a fast, efficient, and private browsing experience with features like Intelligent Tracking Prevention, iCloud syncing, and web standards support.
features: []
image: https://www.apple.com/v/safari/q/images/meta/safari__bo5fx1ipmoqq_og.png
integrations: []
layout: provider
modified: '2026-04-19'
name: Apple Safari
skills: []
slug: apple-safari
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Apple Safari\ndescription: Apple's web browser available across macOS, iOS, and iPadOS, providing a fast, efficient, and private browsing experience with features like Intelligent Tracking Prevention, iCloud syncing, and web standards support.\nimage: https://www.apple.com/v/safari/q/images/meta/safari__bo5fx1ipmoqq_og.png\ntags:\n  - Apple\n  - Browser\n  - Privacy\n  - Web Browser\n  - Webkit\ncreated: '2024'\nmodified: '2026-04-19'\nurl: https://www.apple.com/safari/\napis:\n  - name: Safari Extensions API\n    description: >-\n      API for building Safari Web Extensions that extend and customize the browsing\n      experience.\n    image: https://developer.apple.com/assets/elements/icons/safari/safari-96x96_2x.png\n    humanURL: https://developer.apple.com/documentation/safariservices/safari_web_extensions\n    baseURL: https://developer.apple.com\n    tags:\n      - Browser Extensions\n      - Extensions\n      - Web Extensions\n    properties:\n      - type: Documentation\n\
  \        url: https://developer.apple.com/documentation/safariservices/safari_web_extensions\n      - type: GettingStarted\n        url: https://developer.apple.com/documentation/safariservices/safari_web_extensions/creating_a_safari_web_extension\n      - type: Documentation\n        url: https://developer.apple.com/documentation/safariservices/adopting-new-safari-web-extension-apis\n      - type: Documentation\n        url: https://developer.apple.com/documentation/safariservices/assessing-your-safari-web-extension-s-browser-compatibility\n      - type: Documentation\n        url: https://developer.apple.com/documentation/safariservices/running-your-safari-web-extension\n      - type: Documentation\n        url: https://developer.apple.com/documentation/safariservices/packaging-and-distributing-safari-web-extensions-with-app-store-connect\n      - type: Portal\n        url: https://developer.apple.com/safari/extensions/\n    contact:\n      - FN: Apple Developer Support\n        url:\
  \ https://developer.apple.com/contact/\n  - name: Safari App Extensions API\n    description: >-\n      API for creating app extensions that add features and functionality to Safari\n      on macOS.\n    image: https://developer.apple.com/assets/elements/icons/safari/safari-96x96_2x.png\n    humanURL: https://developer.apple.com/documentation/safariservices/safari_app_extensions\n    baseURL: https://developer.apple.com\n    tags:\n      - App Extensions\n      - Macos\n      - Safari Extensions\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/safariservices/safari_app_extensions\n      - type: GettingStarted\n        url: https://developer.apple.com/documentation/safariservices/safari_app_extensions/building_a_safari_app_extension\n    contact:\n      - FN: Apple Developer Support\n        url: https://developer.apple.com/contact/\n  - name: Safari Web Content API\n    description: >-\n      WebKit APIs for interacting with web content,\
  \ including JavaScript evaluation\n      and DOM manipulation.\n    image: https://developer.apple.com/assets/elements/icons/webkit/webkit-96x96_2x.png\n    humanURL: https://developer.apple.com/documentation/webkit\n    baseURL: https://developer.apple.com\n    tags:\n      - Dom\n      - Javascript\n      - Web Content\n      - Webkit\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/webkit\n      - type: APIReference\n        url: https://developer.apple.com/documentation/webkit/wkwebview\n      - type: APIReference\n        url: https://developer.apple.com/documentation/webkit/wkwebviewconfiguration\n      - type: APIReference\n        url: https://developer.apple.com/documentation/webkit/wkwebsitedatastore\n    contact:\n      - FN: Apple Developer Support\n        url: https://developer.apple.com/contact/\n  - name: Safari Services API\n    description: >-\n      iOS and macOS API for integrating Safari functionality into apps,\
  \ including\n      Safari View Controller.\n    image: https://developer.apple.com/assets/elements/icons/safari-services/safari-services-96x96_2x.png\n    humanURL: https://developer.apple.com/documentation/safariservices\n    baseURL: https://developer.apple.com\n    tags:\n      - Ios\n      - Macos\n      - Safari Services\n      - Safari View Controller\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/safariservices\n      - type: APIReference\n        url: https://developer.apple.com/documentation/safariservices/sfsafariviewcontroller\n    contact:\n      - FN: Apple Developer Support\n        url: https://developer.apple.com/contact/\n  - name: Safari Web Push API\n    description: >-\n      API for sending push notifications to users through Safari on macOS, iOS, and\n      iPadOS using the Push API, Notifications API, and Service Workers.\n    image: https://developer.apple.com/assets/elements/icons/safari/safari-96x96_2x.png\n\
  \    humanURL: https://developer.apple.com/documentation/usernotifications/sending-web-push-notifications-in-web-apps-and-browsers\n    baseURL: https://developer.apple.com\n    tags:\n      - Notifications\n      - Push Api\n      - Service Workers\n      - Web Push\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/usernotifications/sending-web-push-notifications-in-web-apps-and-browsers\n      - type: Documentation\n        url: https://developer.apple.com/videos/play/wwdc2022/10098/\n      - type: Blog\n        url: https://webkit.org/blog/13878/web-push-for-web-apps-on-ios-and-ipados/\n    contact:\n      - FN: Apple Developer Support\n        url: https://developer.apple.com/contact/\n  - name: Safari Content Blocking API\n    description: >-\n      API for creating content blockers and declarative content blocking rules in\n      Safari web extensions to filter and block web content.\n    image: https://developer.apple.com/assets/elements/icons/safari/safari-96x96_2x.png\n\
  \    humanURL: https://developer.apple.com/documentation/safariservices/creating-a-content-blocker\n    baseURL: https://developer.apple.com\n    tags:\n      - Ad Blocking\n      - Content Blocking\n      - Declarative Net Request\n      - Web Filtering\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/safariservices/creating-a-content-blocker\n      - type: Documentation\n        url: https://developer.apple.com/documentation/safariservices/blocking-content-with-your-safari-web-extension\n      - type: Documentation\n        url: https://developer.apple.com/documentation/safariservices/adopting-declarative-content-blocking-in-safari-web-extensions\n      - type: APIReference\n        url: https://developer.apple.com/documentation/safariservices/sfcontentblockermanager\n    contact:\n      - FN: Apple Developer Support\n        url: https://developer.apple.com/contact/\n  - name: Safari Developer Tools API\n    description: >-\n    \
  \  APIs and tools for inspecting, debugging, and optimizing web content in Safari,\n      including Web Inspector and the ability to add custom web development tools.\n    image: https://developer.apple.com/assets/elements/icons/safari/safari-96x96_2x.png\n    humanURL: https://developer.apple.com/documentation/safari-developer-tools\n    baseURL: https://developer.apple.com\n    tags:\n      - Debugging\n      - Developer Tools\n      - Web Development\n      - Web Inspector\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/safari-developer-tools\n      - type: Documentation\n        url: https://developer.apple.com/documentation/safari-developer-tools/web-inspector\n      - type: Documentation\n        url: https://developer.apple.com/documentation/safariservices/adding-a-web-development-tool-to-safari-web-inspector\n      - type: GettingStarted\n        url: https://developer.apple.com/documentation/safari-developer-tools/enabling-developer-features\n\
  \      - type: Documentation\n        url: https://developer.apple.com/documentation/safari-developer-tools/inspecting-ios\n      - type: Documentation\n        url: https://developer.apple.com/videos/play/wwdc2023/10262/\n    contact:\n      - FN: Apple Developer Support\n        url: https://developer.apple.com/contact/\n  - name: Safari Authentication Services API\n    description: >-\n      API for authenticating users through web services in Safari using ASWebAuthenticationSession,\n      supporting OAuth, passkeys, and WebAuthn standards.\n    image: https://developer.apple.com/assets/elements/icons/safari/safari-96x96_2x.png\n    humanURL: https://developer.apple.com/documentation/authenticationservices/aswebauthenticationsession\n    baseURL: https://developer.apple.com\n    tags:\n      - Authentication\n      - Oauth\n      - Passkeys\n      - Sign In\n      - Webauthn\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/authenticationservices/aswebauthenticationsession\n\
  \      - type: Documentation\n        url: https://developer.apple.com/documentation/AuthenticationServices\n      - type: Documentation\n        url: https://developer.apple.com/documentation/authenticationservices/authenticating-a-user-through-a-web-service\n      - type: Documentation\n        url: https://developer.apple.com/passkeys/\n      - type: Documentation\n        url: https://developer.apple.com/documentation/authenticationservices/authenticating-people-by-using-passkeys-in-browser-apps\n      - type: Documentation\n        url: https://developer.apple.com/documentation/authenticationservices/supporting-passkeys\n    contact:\n      - FN: Apple Developer Support\n        url: https://developer.apple.com/contact/\n  - name: Apple Pay on the Web API\n    description: >-\n      JavaScript APIs for implementing Apple Pay payments in Safari, supporting both\n      the Apple Pay JS API and the Payment Request API.\n    image: https://developer.apple.com/assets/elements/icons/safari/safari-96x96_2x.png\n\
  \    humanURL: https://developer.apple.com/documentation/applepayontheweb\n    baseURL: https://developer.apple.com\n    tags:\n      - Apple Pay\n      - Javascript\n      - Payment Request\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/applepayontheweb\n      - type: APIReference\n        url: https://developer.apple.com/documentation/applepayontheweb/apple-pay-js-api\n      - type: GettingStarted\n        url: https://developer.apple.com/apple-pay/implementation/\n      - type: Documentation\n        url: https://developer.apple.com/apple-pay/planning/\n      - type: Sandbox\n        url: https://applepaydemo.apple.com/\n    contact:\n      - FN: Apple Developer Support\n        url: https://developer.apple.com/contact/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ncommon:\n  - type: DeveloperPortal\n    url: https://developer.apple.com/safari/\n  - type:\
  \ ReleaseNotes\n    url: https://developer.apple.com/documentation/safari-release-notes\n  - type: Resources\n    url: https://developer.apple.com/safari/resources/\n  - type: Blog\n    url: https://webkit.org/blog/\n  - type: Documentation\n    url: https://docs.webkit.org/\n  - type: YouTube\n    url: https://developer.apple.com/videos/safari-web/\n  - type: Support\n    url: https://developer.apple.com/forums/\n  - type: Features\n    url: https://www.apple.com/safari/\n  - type: UseCases\n    url: https://developer.apple.com/safari/\n  - type: Integrations\n    url: https://developer.apple.com/safari/extensions/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apple-safari/refs/heads/main/apis.yml
tags:
- Apple
- Browser
- Privacy
- Web Browser
- Webkit
url: https://www.apple.com/safari/
use_cases: []
---
