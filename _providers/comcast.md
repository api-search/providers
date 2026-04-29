---
api_count: 3
apis:
- description: Firebolt is Comcast's application platform for building apps that run on TVs, set-top boxes, and other connected home devices. The Firebolt SDK exposes a family of JavaScript APIs (Lifecycle, Metrics,
  name: Comcast Firebolt SDK
  slug: firebolt-sdk
- description: The Comcast Security Access Token (SAT) endpoint issues short-lived bearer tokens used to authenticate calls to Comcast partner APIs such as the Open Ingest service. Clients exchange an x-client-id an
  name: Comcast Authentication API (SAT)
  slug: authentication-api
- description: The Comcast Open Ingest endpoint accepts metadata and content asset packages from NBCUniversal media partners. Clients POST an XML payload describing assets to the Merlin ingest proxy, authenticated w
  name: Comcast Open Ingest API
  slug: open-ingest-api
common:
- title: ''
  type: Website
  url: https://www.comcast.com
- title: ''
  type: DeveloperDocs
  url: https://docs.developer.comcast.com/
- title: ''
  type: DeveloperPortal
  url: https://developer.comcast.com/
- title: ''
  type: GitHub
  url: https://github.com/Comcast
- title: ''
  type: OpenSource
  url: https://comcast.github.io/
- title: ''
  type: Xfinity
  url: https://www.xfinity.com/
- title: ''
  type: NBCUniversal
  url: https://www.nbcuniversal.com/
- title: ''
  type: Investors
  url: https://www.cmcsa.com/
- title: ''
  type: Privacy
  url: https://www.xfinity.com/privacy/policy
- title: ''
  type: Terms
  url: https://developers.xfinity.com/TOS.html
created: '2026-03-21'
description: Comcast Corporation is a global media and technology company with two primary businesses, Comcast Cable (Xfinity) and NBCUniversal, providing video, internet, voice, wireless, and entertainment services to residential and business customers. Comcast publishes a public developer program centered on the Firebolt application platform for connected TV experiences, along with authentication and content ingest endpoints used by NBCUniversal media partners. The Firebolt SDK family is used by app developers to write apps once and deploy across Xfinity X1, Xfinity Flex, Sky Q, and other Comcast set-top boxes and connected devices.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-26'
name: Comcast
skills: []
slug: comcast
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: comcast\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/comcast/refs/heads/main/apis.yml\nname: Comcast\ntags:\n  - Cable\n  - Connected Devices\n  - Entertainment\n  - Internet\n  - Media\n  - Mobile\n  - Streaming\n  - Wireless\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nx-type: company\ncreated: '2026-03-21'\nmodified: '2026-04-26'\nposition: Consumer\ndescription: >-\n  Comcast Corporation is a global media and technology company with two primary\n  businesses, Comcast Cable (Xfinity) and NBCUniversal, providing video,\n  internet, voice, wireless, and entertainment services to residential and\n  business customers. Comcast publishes a public developer program centered on\n  the Firebolt application platform for connected TV experiences, along with\n  authentication and content ingest endpoints used by NBCUniversal media\n  partners. The Firebolt SDK family is used by app developers\
  \ to write apps\n  once and deploy across Xfinity X1, Xfinity Flex, Sky Q, and other Comcast\n  set-top boxes and connected devices.\napis:\n  - aid: comcast:firebolt-sdk\n    name: Comcast Firebolt SDK\n    tags:\n      - Connected Devices\n      - JavaScript\n      - SDK\n      - Set-Top Box\n      - TV Apps\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.developer.comcast.com/docs/firebolt-apis\n    properties:\n      - url: https://docs.developer.comcast.com/docs/firebolt-apis\n        type: Documentation\n      - url: https://docs.developer.comcast.com/docs/intro-to-firebolt\n        type: GettingStarted\n      - url: https://www.npmjs.com/package/@firebolt-js/sdk\n        type: Package\n      - url: https://github.com/rdkcentral/firebolt-openrpc\n        type: Repository\n    description: >-\n      Firebolt is Comcast's application platform for building apps that run on\n      TVs, set-top boxes, and other connected\
  \ home devices. The Firebolt SDK\n      exposes a family of JavaScript APIs (Lifecycle, Metrics, Device,\n      Authentication, Discovery, Profile, Localization, Account) that let\n      developers write once and deploy to any supported device. Firebolt is\n      defined with OpenRPC and ships as a publicly hosted npm package\n      (@firebolt-js/sdk) with zero runtime dependencies.\n    x-features:\n      - OpenRPC-defined JSON-RPC interface across modules\n      - Lifecycle, Metrics, Device, Authentication, Discovery, Profile modules\n      - JavaScript SDK distributed via npm with zero dependencies\n      - Reference implementations and certification tooling\n      - Targets Xfinity X1, Xfinity Flex, Sky Q, and other connected devices\n    x-use-cases:\n      - Building streaming/entertainment apps for Comcast set-top boxes\n      - Cross-device TV app distribution from a single codebase\n      - Capturing standardized app health and usage metrics\n      - Driving sign-in/entitlement\
  \ flows on connected TV devices\n  - aid: comcast:authentication-api\n    name: Comcast Authentication API (SAT)\n    tags:\n      - Authentication\n      - OAuth\n      - Tokens\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://sat-prod.codebig2.net\n    humanURL: https://docs.developer.comcast.com/docs/081-core-authentication\n    properties:\n      - url: https://docs.developer.comcast.com/docs/081-core-authentication\n        type: Documentation\n    description: >-\n      The Comcast Security Access Token (SAT) endpoint issues short-lived\n      bearer tokens used to authenticate calls to Comcast partner APIs such\n      as the Open Ingest service. Clients exchange an x-client-id and\n      x-client-secret pair for an OAuth-style access token valid for 24\n      hours, which is then attached to subsequent requests in the\n      Authorization header.\n    x-features:\n      - Client-credential token exchange\n      - 24-hour\
  \ bearer token lifetime\n      - x-client-id / x-client-secret request headers\n    x-use-cases:\n      - Authenticating against NBCUniversal partner ingest workflows\n      - Obtaining access tokens for Comcast media platform APIs\n  - aid: comcast:open-ingest-api\n    name: Comcast Open Ingest API\n    tags:\n      - Ingest\n      - Media\n      - Metadata\n      - NBCUniversal\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://compass-mmpwebservice-prod.codebig2.net\n    humanURL: https://docs.developer.comcast.com/docs/endpoints\n    properties:\n      - url: https://docs.developer.comcast.com/docs/endpoints\n        type: Documentation\n    description: >-\n      The Comcast Open Ingest endpoint accepts metadata and content asset\n      packages from NBCUniversal media partners. Clients POST an XML payload\n      describing assets to the Merlin ingest proxy, authenticated with a\n      Comcast SAT bearer token and partnered\
  \ through partner identifiers\n      such as globalott. The endpoint returns an OpenIngestResult document\n      with per-asset outcome status.\n    x-features:\n      - XML asset and metadata submission\n      - Bearer-token authentication via Comcast SAT\n      - Partner-scoped ingestion (e.g. globalott)\n      - OpenIngestResult outcome reporting\n    x-use-cases:\n      - Submitting media metadata to NBCUniversal pipelines\n      - Bulk content publication for OTT distribution\ncommon:\n  - type: Website\n    url: https://www.comcast.com\n  - type: DeveloperDocs\n    url: https://docs.developer.comcast.com/\n  - type: DeveloperPortal\n    url: https://developer.comcast.com/\n  - type: GitHub\n    url: https://github.com/Comcast\n  - type: OpenSource\n    url: https://comcast.github.io/\n  - type: Xfinity\n    url: https://www.xfinity.com/\n  - type: NBCUniversal\n    url: https://www.nbcuniversal.com/\n  - type: Investors\n    url: https://www.cmcsa.com/\n  - type: Privacy\n    url:\
  \ https://www.xfinity.com/privacy/policy\n  - type: Terms\n    url: https://developers.xfinity.com/TOS.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/comcast/refs/heads/main/apis.yml
tags:
- Cable
- Connected Devices
- Entertainment
- Internet
- Media
- Mobile
- Streaming
- Wireless
url: https://raw.githubusercontent.com/api-evangelist/comcast/refs/heads/main/apis.yml
use_cases: []
---
