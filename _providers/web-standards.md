---
api_count: 24
apis:
- description: The core markup language of the web, including Web Workers, localStorage, history, the canvas element, forms, and numerous JavaScript APIs. Maintained by WHATWG and published as a continuously updated
  name: WHATWG HTML Living Standard
  slug: whatwg-html
- description: The networking model for resource retrieval on the web. Defines the Fetch API used by browsers and JavaScript to make HTTP requests, replacing the older XMLHttpRequest API.
  name: WHATWG Fetch Living Standard
  slug: whatwg-fetch
- description: The core infrastructure used to define the web. Specifies the Document Object Model (DOM), which represents HTML/XML documents as a tree of nodes that scripts can manipulate.
  name: WHATWG DOM Living Standard
  slug: whatwg-dom
- description: Infrastructure and algorithms around URLs on the web. Defines how URLs are parsed, serialized, and resolved, and specifies the URL and URLSearchParams APIs.
  name: WHATWG URL Living Standard
  slug: whatwg-url
- description: APIs for creating, composing, and consuming streams of data. Defines ReadableStream, WritableStream, and TransformStream interfaces for efficient data processing.
  name: WHATWG Streams Living Standard
  slug: whatwg-streams
- description: APIs to enable web applications to maintain bidirectional communications with server-side processes. Defines the WebSocket interface for full-duplex communication channels over a single TCP connection
  name: WHATWG WebSockets Living Standard
  slug: whatwg-websockets
- description: Persistent storage API, quota management, and platform storage architecture. Defines how web applications can store data persistently and manage storage quotas.
  name: WHATWG Storage Living Standard
  slug: whatwg-storage
- description: Character encoding functionality on the web. Defines the TextEncoder and TextDecoder APIs for converting between strings and binary data using various character encodings.
  name: WHATWG Encoding Living Standard
  slug: whatwg-encoding
- description: Provides an API allowing web pages to control the display of system notifications to end users, enabling alerts outside the context of a web page.
  name: WHATWG Notifications API Living Standard
  slug: whatwg-notifications
- description: Infrastructure and API for accessing the file system. Provides FileSystemHandle, FileSystemFileHandle, and FileSystemDirectoryHandle interfaces for reading and writing files on the user's local device
  name: WHATWG File System Living Standard
  slug: whatwg-file-system
- description: Cascading Style Sheets specifications developed by the W3C CSS Working Group. Covers layout (Flexbox, Grid), selectors, animations, transforms, custom properties, and all aspects of web presentation.
  name: W3C CSS Specifications
  slug: w3c-css
- description: A W3C Recommendation that defines a strong authentication API for web applications, enabling passwordless and multi-factor authentication using public key cryptography and hardware authenticators.
  name: W3C Web Authentication (WebAuthn)
  slug: w3c-webauthn
- description: Web Real-Time Communications specifications enabling peer-to-peer audio, video, and data communication directly between browsers without plugins. Developed by the W3C WebRTC Working Group.
  name: W3C WebRTC
  slug: w3c-webrtc
- description: A W3C specification providing a modern GPU-accelerated graphics and compute interface for the web. Developed by the GPU for the Web Working Group as a successor to WebGL.
  name: W3C WebGPU
  slug: w3c-webgpu
- description: 'A suite of W3C specifications enabling reusable custom elements: Custom Elements v1, Shadow DOM, and HTML Templates. Allows developers to create encapsulated, reusable UI components.'
  name: W3C Web Components
  slug: w3c-web-components
- description: A W3C specification that enables web applications to work offline, do background synchronization, and intercept network requests. Service Workers act as a programmable network proxy between the browse
  name: W3C Service Workers
  slug: w3c-service-workers
- description: A W3C Recommendation that standardizes the checkout process on the web, reducing the need for forms by using browser-stored payment information and supporting multiple payment methods.
  name: W3C Payment Request API
  slug: w3c-payment-request
- description: A portable binary instruction format for a stack-based virtual machine. Enables near-native performance for web applications written in languages like C, C++, and Rust.
  name: W3C WebAssembly
  slug: w3c-webassembly
- description: JSON-LD 1.1 is a W3C Recommendation for Linked Data in JSON format. Provides a method to encode Linked Data using JSON, enabling semantic interoperability and integration with the Semantic Web.
  name: W3C JSON-LD
  slug: w3c-json-ld
- description: A W3C Recommendation that defines a data model for expressing credentials on the web in a cryptographically secure, privacy-respecting, and machine-verifiable way.
  name: W3C Verifiable Credentials
  slug: w3c-verifiable-credentials
- description: A W3C specification enabling hardware-accelerated machine learning inference directly in web browsers, providing a low-level API for neural network operations on CPUs, GPUs, and dedicated ML accelerat
  name: W3C Web Neural Network API (WebNN)
  slug: w3c-web-ml
- description: A W3C Recommendation defining a new type of identifier enabling verifiable, decentralized digital identity. DIDs are globally unique, resolvable with high availability, and cryptographically verifiabl
  name: W3C Decentralized Identifiers (DIDs)
  slug: w3c-did
- description: The IETF HTTP Working Group specifications defining the HyperText Transfer Protocol. Includes HTTP/1.1 (RFC 9110), HTTP/2 (RFC 9113), HTTP/3 (RFC 9114), and related standards for caching, cookies, and
  name: IETF HTTP Specifications
  slug: ietf-http
- description: 'The ECMAScript specification (ECMA-262) defines the JavaScript programming language. Published annually by TC39 with new features, ECMAScript is the foundation for all JavaScript runtime environments '
  name: ECMA JavaScript (ECMAScript)
  slug: ecma-javascript
common:
- title: ''
  type: Website
  url: https://www.w3.org/
- title: ''
  type: Website
  url: https://whatwg.org/
- title: ''
  type: Website
  url: https://ietf.org/
- title: ''
  type: Website
  url: https://ecma-international.org/
- title: ''
  type: Documentation
  url: https://www.w3.org/TR/
- title: ''
  type: APIReference
  url: https://developer.mozilla.org/en-US/docs/Web/API
- title: ''
  type: APIReference
  url: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference
- title: ''
  type: Tools
  url: https://caniuse.com/
- title: ''
  type: Tools
  url: https://wpt.fyi/
- title: ''
  type: GitHubRepository
  url: https://github.com/web-platform-tests/wpt
- title: ''
  type: GitHubOrganization
  url: https://github.com/w3c
- title: ''
  type: GitHubOrganization
  url: https://github.com/whatwg
- title: ''
  type: GitHubOrganization
  url: https://github.com/tc39
- title: ''
  type: GitHubOrganization
  url: https://github.com/WICG
- title: ''
  type: JSONLD
  url: json-ld/web-standards-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/web-standards-vocabulary.yml
created: '2025'
description: Specifications and guidelines that define how web technologies should work, ensuring interoperability and consistency across browsers and platforms. Web standards are developed by organizations like W3C, WHATWG, IETF, and ECMA International. This topic covers the full landscape of web standards including HTML, CSS, JavaScript APIs, networking, security, graphics, media, and emerging technologies.
features:
- description: Web standards ensure that websites and applications work consistently across all browsers and platforms.
  name: Interoperability
- description: Standards enable building experiences that work for all users and are enhanced for capable browsers.
  name: Progressive Enhancement
- description: Standards define security mechanisms like CSP, CORS, WebAuthn, and privacy-preserving APIs.
  name: Security and Privacy
- description: Standards provide APIs for measuring and optimizing web application performance.
  name: Performance APIs
- description: Service Workers and Storage APIs enable web applications to function without network access.
  name: Offline Capabilities
- description: WebRTC and WebSockets enable peer-to-peer and server communication without plugins.
  name: Real-Time Communication
- description: Device APIs provide controlled access to hardware like cameras, microphones, and sensors.
  name: Hardware Access
- description: WebNN enables hardware-accelerated ML inference directly in the browser.
  name: Machine Learning
image: ''
integrations:
- description: Chrome, Firefox, Safari, and Edge implement web standards to provide consistent capabilities across platforms.
  name: Browser Vendors
- description: Node.js, Deno, and Bun implement web standard APIs including Fetch, Streams, WebCrypto, and URL.
  name: JavaScript Runtimes
- description: Express, Fastify, Hono, and other frameworks align with web standard request/response models.
  name: Server Frameworks
- description: Vite, Webpack, and esbuild target web standards to produce optimized web applications.
  name: Build Tools
- description: Playwright, WebDriver, and Puppeteer automate browsers using WebDriver and related specifications.
  name: Testing Frameworks
- description: Cloudflare Workers, Vercel Edge, and Deno Deploy implement web standard APIs for edge computing.
  name: Edge Runtimes
jsonld:
- class_count: 15
  name: Web Standards Context
  property_count: 14
  slug: web-standards-context
layout: provider
modified: '2026-05-03'
name: Web Standards
skills: []
slug: web-standards
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: web-standards\nname: Web Standards\ndescription: >-\n  Specifications and guidelines that define how web technologies should work,\n  ensuring interoperability and consistency across browsers and platforms. Web\n  standards are developed by organizations like W3C, WHATWG, IETF, and ECMA\n  International. This topic covers the full landscape of web standards including\n  HTML, CSS, JavaScript APIs, networking, security, graphics, media, and\n  emerging technologies.\ntype: Index\nurl: https://www.w3.org/standards/\ntags:\n  - Browser Compatibility\n  - CSS\n  - HTML\n  - Interoperability\n  - JavaScript\n  - Standards\n  - Web APIs\n  - Web Development\ncreated: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: web-standards:whatwg-html\n    name: WHATWG HTML Living Standard\n    description: >-\n      The core markup language of the web, including Web Workers, localStorage,\n      history, the canvas element, forms, and numerous JavaScript APIs.\
  \ Maintained\n      by WHATWG and published as a continuously updated Living Standard.\n    humanURL: https://html.spec.whatwg.org/multipage/\n    tags:\n      - HTML\n      - Living Standard\n      - WHATWG\n      - Web APIs\n    properties:\n      - type: Documentation\n        url: https://html.spec.whatwg.org/multipage/\n      - type: GitHubRepository\n        url: https://github.com/whatwg/html\n\n  - aid: web-standards:whatwg-fetch\n    name: WHATWG Fetch Living Standard\n    description: >-\n      The networking model for resource retrieval on the web. Defines the Fetch\n      API used by browsers and JavaScript to make HTTP requests, replacing the\n      older XMLHttpRequest API.\n    humanURL: https://fetch.spec.whatwg.org/\n    tags:\n      - Fetch API\n      - HTTP\n      - Living Standard\n      - Networking\n      - WHATWG\n    properties:\n      - type: Documentation\n        url: https://fetch.spec.whatwg.org/\n      - type: GitHubRepository\n        url: https://github.com/whatwg/fetch\n\
  \n  - aid: web-standards:whatwg-dom\n    name: WHATWG DOM Living Standard\n    description: >-\n      The core infrastructure used to define the web. Specifies the Document\n      Object Model (DOM), which represents HTML/XML documents as a tree of nodes\n      that scripts can manipulate.\n    humanURL: https://dom.spec.whatwg.org/\n    tags:\n      - DOM\n      - Living Standard\n      - WHATWG\n      - Web APIs\n    properties:\n      - type: Documentation\n        url: https://dom.spec.whatwg.org/\n      - type: GitHubRepository\n        url: https://github.com/whatwg/dom\n\n  - aid: web-standards:whatwg-url\n    name: WHATWG URL Living Standard\n    description: >-\n      Infrastructure and algorithms around URLs on the web. Defines how URLs are\n      parsed, serialized, and resolved, and specifies the URL and URLSearchParams\n      APIs.\n    humanURL: https://url.spec.whatwg.org/\n    tags:\n      - Living Standard\n      - URL\n      - WHATWG\n    properties:\n      - type: Documentation\n\
  \        url: https://url.spec.whatwg.org/\n      - type: GitHubRepository\n        url: https://github.com/whatwg/url\n\n  - aid: web-standards:whatwg-streams\n    name: WHATWG Streams Living Standard\n    description: >-\n      APIs for creating, composing, and consuming streams of data. Defines\n      ReadableStream, WritableStream, and TransformStream interfaces for\n      efficient data processing.\n    humanURL: https://streams.spec.whatwg.org/\n    tags:\n      - Living Standard\n      - Streaming\n      - WHATWG\n      - Web APIs\n    properties:\n      - type: Documentation\n        url: https://streams.spec.whatwg.org/\n      - type: GitHubRepository\n        url: https://github.com/whatwg/streams\n\n  - aid: web-standards:whatwg-websockets\n    name: WHATWG WebSockets Living Standard\n    description: >-\n      APIs to enable web applications to maintain bidirectional communications\n      with server-side processes. Defines the WebSocket interface for full-duplex\n      communication\
  \ channels over a single TCP connection.\n    humanURL: https://websockets.spec.whatwg.org/\n    tags:\n      - Living Standard\n      - Real-Time\n      - WebSockets\n      - WHATWG\n    properties:\n      - type: Documentation\n        url: https://websockets.spec.whatwg.org/\n      - type: GitHubRepository\n        url: https://github.com/whatwg/websockets\n\n  - aid: web-standards:whatwg-storage\n    name: WHATWG Storage Living Standard\n    description: >-\n      Persistent storage API, quota management, and platform storage architecture.\n      Defines how web applications can store data persistently and manage storage\n      quotas.\n    humanURL: https://storage.spec.whatwg.org/\n    tags:\n      - Living Standard\n      - Storage\n      - WHATWG\n      - Web APIs\n    properties:\n      - type: Documentation\n        url: https://storage.spec.whatwg.org/\n      - type: GitHubRepository\n        url: https://github.com/whatwg/storage\n\n  - aid: web-standards:whatwg-encoding\n\
  \    name: WHATWG Encoding Living Standard\n    description: >-\n      Character encoding functionality on the web. Defines the TextEncoder and\n      TextDecoder APIs for converting between strings and binary data using\n      various character encodings.\n    humanURL: https://encoding.spec.whatwg.org/\n    tags:\n      - Character Encoding\n      - Living Standard\n      - WHATWG\n    properties:\n      - type: Documentation\n        url: https://encoding.spec.whatwg.org/\n      - type: GitHubRepository\n        url: https://github.com/whatwg/encoding\n\n  - aid: web-standards:whatwg-notifications\n    name: WHATWG Notifications API Living Standard\n    description: >-\n      Provides an API allowing web pages to control the display of system\n      notifications to end users, enabling alerts outside the context of a\n      web page.\n    humanURL: https://notifications.spec.whatwg.org/\n    tags:\n      - Living Standard\n      - Notifications\n      - WHATWG\n    properties:\n   \
  \   - type: Documentation\n        url: https://notifications.spec.whatwg.org/\n      - type: GitHubRepository\n        url: https://github.com/whatwg/notifications\n\n  - aid: web-standards:whatwg-file-system\n    name: WHATWG File System Living Standard\n    description: >-\n      Infrastructure and API for accessing the file system. Provides\n      FileSystemHandle, FileSystemFileHandle, and FileSystemDirectoryHandle\n      interfaces for reading and writing files on the user's local device.\n    humanURL: https://fs.spec.whatwg.org/\n    tags:\n      - File System\n      - Living Standard\n      - Storage\n      - WHATWG\n    properties:\n      - type: Documentation\n        url: https://fs.spec.whatwg.org/\n      - type: GitHubRepository\n        url: https://github.com/whatwg/fs\n\n  - aid: web-standards:w3c-css\n    name: W3C CSS Specifications\n    description: >-\n      Cascading Style Sheets specifications developed by the W3C CSS Working\n      Group. Covers layout (Flexbox,\
  \ Grid), selectors, animations, transforms,\n      custom properties, and all aspects of web presentation.\n    humanURL: https://www.w3.org/Style/CSS/\n    tags:\n      - CSS\n      - Layout\n      - Styling\n      - W3C\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/Style/CSS/\n      - type: GitHubOrganization\n        url: https://github.com/w3c/csswg-drafts\n\n  - aid: web-standards:w3c-webauthn\n    name: W3C Web Authentication (WebAuthn)\n    description: >-\n      A W3C Recommendation that defines a strong authentication API for web\n      applications, enabling passwordless and multi-factor authentication using\n      public key cryptography and hardware authenticators.\n    humanURL: https://www.w3.org/TR/webauthn/\n    tags:\n      - Authentication\n      - Security\n      - W3C\n      - WebAuthn\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/webauthn/\n      - type: GitHubRepository\n        url: https://github.com/w3c/webauthn\n\
  \n  - aid: web-standards:w3c-webrtc\n    name: W3C WebRTC\n    description: >-\n      Web Real-Time Communications specifications enabling peer-to-peer audio,\n      video, and data communication directly between browsers without plugins.\n      Developed by the W3C WebRTC Working Group.\n    humanURL: https://www.w3.org/TR/webrtc/\n    tags:\n      - Communication\n      - Real-Time\n      - Video\n      - W3C\n      - WebRTC\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/webrtc/\n      - type: GitHubRepository\n        url: https://github.com/w3c/webrtc-pc\n\n  - aid: web-standards:w3c-webgpu\n    name: W3C WebGPU\n    description: >-\n      A W3C specification providing a modern GPU-accelerated graphics and compute\n      interface for the web. Developed by the GPU for the Web Working Group as\n      a successor to WebGL.\n    humanURL: https://www.w3.org/TR/webgpu/\n    tags:\n      - GPU\n      - Graphics\n      - W3C\n      - WebGPU\n    properties:\n\
  \      - type: Documentation\n        url: https://www.w3.org/TR/webgpu/\n      - type: GitHubRepository\n        url: https://github.com/gpuweb/gpuweb\n\n  - aid: web-standards:w3c-web-components\n    name: W3C Web Components\n    description: >-\n      A suite of W3C specifications enabling reusable custom elements: Custom\n      Elements v1, Shadow DOM, and HTML Templates. Allows developers to create\n      encapsulated, reusable UI components.\n    humanURL: https://www.w3.org/standards/techs/components\n    tags:\n      - Components\n      - Custom Elements\n      - Shadow DOM\n      - W3C\n      - Web Components\n    properties:\n      - type: Documentation\n        url: https://developer.mozilla.org/en-US/docs/Web/API/Web_Components\n      - type: GitHubRepository\n        url: https://github.com/WICG/webcomponents\n\n  - aid: web-standards:w3c-service-workers\n    name: W3C Service Workers\n    description: >-\n      A W3C specification that enables web applications to work offline,\
  \ do\n      background synchronization, and intercept network requests. Service Workers\n      act as a programmable network proxy between the browser and network.\n    humanURL: https://www.w3.org/TR/service-workers/\n    tags:\n      - Offline\n      - Progressive Web Apps\n      - Service Workers\n      - W3C\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/service-workers/\n      - type: GitHubRepository\n        url: https://github.com/w3c/ServiceWorker\n\n  - aid: web-standards:w3c-payment-request\n    name: W3C Payment Request API\n    description: >-\n      A W3C Recommendation that standardizes the checkout process on the web,\n      reducing the need for forms by using browser-stored payment information\n      and supporting multiple payment methods.\n    humanURL: https://www.w3.org/TR/payment-request/\n    tags:\n      - Commerce\n      - Payments\n      - W3C\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/payment-request/\n\
  \      - type: GitHubRepository\n        url: https://github.com/w3c/payment-request\n\n  - aid: web-standards:w3c-webassembly\n    name: W3C WebAssembly\n    description: >-\n      A portable binary instruction format for a stack-based virtual machine.\n      Enables near-native performance for web applications written in languages\n      like C, C++, and Rust.\n    humanURL: https://www.w3.org/TR/wasm-core-1/\n    tags:\n      - Performance\n      - W3C\n      - WebAssembly\n    properties:\n      - type: Documentation\n        url: https://webassembly.org/\n      - type: GitHubRepository\n        url: https://github.com/WebAssembly/spec\n\n  - aid: web-standards:w3c-json-ld\n    name: W3C JSON-LD\n    description: >-\n      JSON-LD 1.1 is a W3C Recommendation for Linked Data in JSON format.\n      Provides a method to encode Linked Data using JSON, enabling semantic\n      interoperability and integration with the Semantic Web.\n    humanURL: https://www.w3.org/TR/json-ld11/\n    tags:\n\
  \      - JSON-LD\n      - Linked Data\n      - Semantic Web\n      - W3C\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/json-ld11/\n      - type: GitHubRepository\n        url: https://github.com/w3c/json-ld-syntax\n\n  - aid: web-standards:w3c-verifiable-credentials\n    name: W3C Verifiable Credentials\n    description: >-\n      A W3C Recommendation that defines a data model for expressing credentials\n      on the web in a cryptographically secure, privacy-respecting, and\n      machine-verifiable way.\n    humanURL: https://www.w3.org/TR/vc-data-model/\n    tags:\n      - Credentials\n      - Identity\n      - Privacy\n      - Security\n      - W3C\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/vc-data-model/\n      - type: GitHubRepository\n        url: https://github.com/w3c/vc-data-model\n\n  - aid: web-standards:w3c-web-ml\n    name: W3C Web Neural Network API (WebNN)\n    description: >-\n      A W3C specification\
  \ enabling hardware-accelerated machine learning\n      inference directly in web browsers, providing a low-level API for neural\n      network operations on CPUs, GPUs, and dedicated ML accelerators.\n    humanURL: https://www.w3.org/TR/webnn/\n    tags:\n      - Artificial Intelligence\n      - Machine Learning\n      - W3C\n      - WebNN\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/webnn/\n      - type: GitHubRepository\n        url: https://github.com/webmachinelearning/webnn\n\n  - aid: web-standards:w3c-did\n    name: W3C Decentralized Identifiers (DIDs)\n    description: >-\n      A W3C Recommendation defining a new type of identifier enabling verifiable,\n      decentralized digital identity. DIDs are globally unique, resolvable with\n      high availability, and cryptographically verifiable.\n    humanURL: https://www.w3.org/TR/did-core/\n    tags:\n      - Decentralized Identity\n      - DID\n      - Identity\n      - W3C\n    properties:\n\
  \      - type: Documentation\n        url: https://www.w3.org/TR/did-core/\n      - type: GitHubRepository\n        url: https://github.com/w3c/did-core\n\n  - aid: web-standards:ietf-http\n    name: IETF HTTP Specifications\n    description: >-\n      The IETF HTTP Working Group specifications defining the HyperText Transfer\n      Protocol. Includes HTTP/1.1 (RFC 9110), HTTP/2 (RFC 9113), HTTP/3 (RFC\n      9114), and related standards for caching, cookies, and security headers.\n    humanURL: https://httpwg.org/\n    tags:\n      - HTTP\n      - IETF\n      - Networking\n      - Protocol\n    properties:\n      - type: Documentation\n        url: https://httpwg.org/specs/\n      - type: GitHubOrganization\n        url: https://github.com/httpwg\n\n  - aid: web-standards:ecma-javascript\n    name: ECMA JavaScript (ECMAScript)\n    description: >-\n      The ECMAScript specification (ECMA-262) defines the JavaScript programming\n      language. Published annually by TC39 with new features,\
  \ ECMAScript is the\n      foundation for all JavaScript runtime environments including browsers and\n      Node.js.\n    humanURL: https://ecma-international.org/publications-and-standards/standards/ecma-262/\n    tags:\n      - ECMAScript\n      - JavaScript\n      - Programming Language\n      - Standards\n    properties:\n      - type: Documentation\n        url: https://tc39.es/ecma262/\n      - type: GitHubRepository\n        url: https://github.com/tc39/ecma262\n      - type: GitHubOrganization\n        url: https://github.com/tc39\n\ncommon:\n  - url: https://www.w3.org/\n    name: World Wide Web Consortium (W3C)\n    type: Website\n    description: The main standards body for web technologies.\n  - url: https://whatwg.org/\n    name: WHATWG\n    type: Website\n    description: Web Hypertext Application Technology Working Group, maintainers of Living Standards.\n  - url: https://ietf.org/\n    name: Internet Engineering Task Force (IETF)\n    type: Website\n    description: Standards\
  \ body for internet protocols including HTTP.\n  - url: https://ecma-international.org/\n    name: ECMA International\n    type: Website\n    description: Standards body for ECMAScript (JavaScript) and other computing standards.\n  - url: https://www.w3.org/TR/\n    name: W3C Technical Reports\n    type: Documentation\n    description: Complete directory of all W3C specifications and standards.\n  - url: https://developer.mozilla.org/en-US/docs/Web/API\n    name: MDN Web APIs Reference\n    type: APIReference\n    description: Comprehensive reference for all Web APIs implemented in browsers.\n  - url: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference\n    name: MDN JavaScript Reference\n    type: APIReference\n    description: Reference documentation for the JavaScript language and standard library.\n  - url: https://caniuse.com/\n    name: Can I Use\n    type: Tools\n    description: Browser support tables for HTML5, CSS3, and other web standards.\n  - url: https://wpt.fyi/\n\
  \    name: web-platform-tests\n    type: Tools\n    description: Cross-browser test suite for web platform specifications.\n  - url: https://github.com/web-platform-tests/wpt\n    name: web-platform-tests GitHub\n    type: GitHubRepository\n    description: Repository for cross-browser web platform compliance test suite.\n  - url: https://github.com/w3c\n    name: W3C GitHub Organization\n    type: GitHubOrganization\n    description: GitHub organization hosting W3C specification repositories.\n  - url: https://github.com/whatwg\n    name: WHATWG GitHub Organization\n    type: GitHubOrganization\n    description: GitHub organization hosting WHATWG Living Standard repositories.\n  - url: https://github.com/tc39\n    name: TC39 GitHub Organization\n    type: GitHubOrganization\n    description: GitHub organization for ECMAScript proposals and the specification.\n  - url: https://github.com/WICG\n    name: WICG GitHub Organization\n    type: GitHubOrganization\n    description: Web Incubator\
  \ Community Group for incubating new web platform features.\n  - type: JSONLD\n    url: json-ld/web-standards-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/web-standards-vocabulary.yml\n  - name: Web Standards Features\n    type: Features\n    data:\n      - name: Interoperability\n        description: Web standards ensure that websites and applications work consistently across all browsers and platforms.\n      - name: Progressive Enhancement\n        description: Standards enable building experiences that work for all users and are enhanced for capable browsers.\n      - name: Security and Privacy\n        description: Standards define security mechanisms like CSP, CORS, WebAuthn, and privacy-preserving APIs.\n      - name: Performance APIs\n        description: Standards provide APIs for measuring and optimizing web application performance.\n      - name: Offline Capabilities\n        description: Service Workers and Storage APIs enable web applications to function without\
  \ network access.\n      - name: Real-Time Communication\n        description: WebRTC and WebSockets enable peer-to-peer and server communication without plugins.\n      - name: Hardware Access\n        description: Device APIs provide controlled access to hardware like cameras, microphones, and sensors.\n      - name: Machine Learning\n        description: WebNN enables hardware-accelerated ML inference directly in the browser.\n  - name: Web Standards Use Cases\n    type: UseCases\n    data:\n      - name: Progressive Web Apps\n        description: Use Service Workers, Web Storage, Web Push, and Manifest specifications to build installable, offline-capable web applications.\n      - name: Authentication\n        description: Implement passwordless authentication with WebAuthn and Verifiable Credentials for secure, phishing-resistant login.\n      - name: Real-Time Collaboration\n        description: Use WebRTC, WebSockets, and Broadcast Channel API for real-time data sharing and video/audio\
  \ communication.\n      - name: E-Commerce\n        description: Streamline checkout with Payment Request API and Web Authentication for secure, frictionless transactions.\n      - name: Data Visualization\n        description: Use WebGL, WebGPU, Canvas API, and SVG for high-performance, hardware-accelerated graphics and charts.\n      - name: Content Management\n        description: Use Streams API, Fetch API, and IndexedDB for efficient content loading, caching, and storage.\n      - name: Accessibility\n        description: Apply WCAG guidelines and ARIA attributes to make web content accessible to all users.\n      - name: Internationalization\n        description: Use Encoding API and Intl APIs to support global audiences with proper text handling.\n  - name: Web Standards Integrations\n    type: Integrations\n    data:\n      - name: Browser Vendors\n        description: Chrome, Firefox, Safari, and Edge implement web standards to provide consistent capabilities across platforms.\n\
  \      - name: JavaScript Runtimes\n        description: Node.js, Deno, and Bun implement web standard APIs including Fetch, Streams, WebCrypto, and URL.\n      - name: Server Frameworks\n        description: Express, Fastify, Hono, and other frameworks align with web standard request/response models.\n      - name: Build Tools\n        description: Vite, Webpack, and esbuild target web standards to produce optimized web applications.\n      - name: Testing Frameworks\n        description: Playwright, WebDriver, and Puppeteer automate browsers using WebDriver and related specifications.\n      - name: Edge Runtimes\n        description: Cloudflare Workers, Vercel Edge, and Deno Deploy implement web standard APIs for edge computing.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/web-standards/refs/heads/main/apis.yml
tags:
- Browser Compatibility
- CSS
- HTML
- Interoperability
- JavaScript
- Standards
- Web APIs
- Web Development
url: https://www.w3.org/standards/
use_cases:
- description: Use Service Workers, Web Storage, Web Push, and Manifest specifications to build installable, offline-capable web applications.
  name: Progressive Web Apps
- description: Implement passwordless authentication with WebAuthn and Verifiable Credentials for secure, phishing-resistant login.
  name: Authentication
- description: Use WebRTC, WebSockets, and Broadcast Channel API for real-time data sharing and video/audio communication.
  name: Real-Time Collaboration
- description: Streamline checkout with Payment Request API and Web Authentication for secure, frictionless transactions.
  name: E-Commerce
- description: Use WebGL, WebGPU, Canvas API, and SVG for high-performance, hardware-accelerated graphics and charts.
  name: Data Visualization
- description: Use Streams API, Fetch API, and IndexedDB for efficient content loading, caching, and storage.
  name: Content Management
- description: Apply WCAG guidelines and ARIA attributes to make web content accessible to all users.
  name: Accessibility
- description: Use Encoding API and Intl APIs to support global audiences with proper text handling.
  name: Internationalization
---
