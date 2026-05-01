---
api_count: 19
api_specs:
- filename: app-store-connect-openapi-specification.zip
  format: yaml
  label: App Store Connect API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.apple.com/sample-code/app-store-connect/app-store-connect-openapi-specification.zip
apis:
- description: Access Apple Music catalog, user library, and playback controls.
  name: Apple Music API
  slug: ''
- description: Access weather forecasts, current conditions, and historical weather data.
  name: WeatherKit REST API
  slug: ''
- description: Automate tasks for App Store Connect and access app metadata.
  name: App Store Connect API
  slug: ''
- description: Embed interactive Apple Maps on websites.
  name: MapKit JS
  slug: ''
- description: Integrate Sign in with Apple authentication.
  name: Sign in with Apple REST API
  slug: ''
- description: Send push notifications to iOS, macOS, watchOS, and tvOS devices.
  name: Apple Push Notification Service (APNs)
  slug: ''
- description: Manage customer App Store transactions from your server, including in-app purchases and subscriptions.
  name: App Store Server API
  slug: ''
- description: Receive real-time notifications about in-app purchase events and subscription lifecycle changes.
  name: App Store Server Notifications V2
  slug: ''
- description: Server-side geocoding, reverse geocoding, search, and estimated time of arrival using Apple Maps.
  name: Apple Maps Server API
  slug: ''
- description: Publish, manage, update, and delete Apple News Format articles.
  name: Apple News API
  slug: ''
- description: Reduce fraudulent use of your services by managing device state and asserting app integrity.
  name: DeviceCheck API
  slug: ''
- description: Create, manage, and report on Apple Search Ads campaigns programmatically.
  name: Apple Ads Campaign Management API
  slug: ''
- description: Create, distribute, and update passes for the Apple Wallet app via a web service.
  name: Wallet Passes Web Service
  slug: ''
- description: Automate management of users, roles, provisioning profiles, and bundle identifiers for enterprise apps.
  name: Enterprise Program API
  slug: ''
- description: Automate device management actions and access data about devices enrolled via Automated Device Enrollment.
  name: Apple School and Business Manager API
  slug: ''
- description: Accept Apple Pay payments on your website using JavaScript-based APIs.
  name: Apple Pay on the Web
  slug: ''
- description: Create, distribute, and update orders in Apple Wallet for order tracking.
  name: Wallet Orders
  slug: ''
- description: Declare educational activities supported by your app for use with Apple Schoolwork.
  name: ClassKit Catalog API
  slug: ''
- description: Access the Apple Music catalog metadata in bulk for albums, songs, and artists.
  name: Apple Music Feed API
  slug: ''
capabilities:
- description: Unified workflow for managing the Apple app lifecycle including app metadata, builds, TestFlight beta testing, and beta group management. Used by app developers and release managers.
  name: Apple App Lifecycle
  slug: app-lifecycle
common:
- title: ''
  type: DeveloperPortal
  url: https://developer.apple.com
- title: ''
  type: TermsOfService
  url: https://developer.apple.com/terms/
- title: ''
  type: PrivacyPolicy
  url: https://www.apple.com/legal/privacy/
- title: ''
  type: Support
  url: https://developer.apple.com/support/
- title: ''
  type: Blog
  url: https://developer.apple.com/news/
- title: ''
  type: StatusPage
  url: https://developer.apple.com/system-status/
- title: ''
  type: SignUp
  url: https://developer.apple.com/programs/enroll/
- title: ''
  type: Pricing
  url: https://developer.apple.com/support/compare-memberships/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apple
- title: ''
  type: YouTube
  url: https://developer.apple.com/videos/
- title: ''
  type: ChangeLog
  url: https://developer.apple.com/documentation/updates
- title: ''
  type: Authentication
  url: https://developer.apple.com/documentation/appstoreconnectapi/generating-tokens-for-api-requests
- title: ''
  type: Tutorials
  url: https://developer.apple.com/tutorials/
- title: ''
  type: CodeExamples
  url: https://developer.apple.com/sample-code/
- title: ''
  type: SDK
  url: https://developer.apple.com/download/
- title: ''
  type: Contact
  url: https://developer.apple.com/contact/
- title: ''
  type: JSONLD
  url: json-ld/apple-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/apple-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/app-lifecycle.yaml
created: '2024-01-15'
description: Collection of Apple's public APIs and developer resources.
features:
- description: Automate app management, TestFlight, submissions, and analytics through a comprehensive REST API.
  name: App Store Connect
- description: Accept payments seamlessly on web and in apps with secure tokenized transactions.
  name: Apple Pay
- description: Send real-time notifications to billions of Apple devices across iOS, macOS, watchOS, and tvOS.
  name: Push Notifications
- description: Privacy-focused authentication that lets users sign in without sharing personal information.
  name: Sign in with Apple
- description: Embed interactive maps and perform server-side geocoding with Apple Maps infrastructure.
  name: MapKit and Maps Server
- description: Access hyper-local weather forecasts, conditions, and historical data worldwide.
  name: WeatherKit
- description: Integrate Apple Music catalog, user library, and playback into apps and websites.
  name: MusicKit
image: https://www.apple.com/ac/structured-data/images/knowledge_graph_logo.png
integrations:
- description: Full IDE integration for building, testing, and deploying apps across all Apple platforms.
  name: Xcode
- description: Beta testing platform for distributing pre-release builds to internal and external testers.
  name: TestFlight
- description: View app performance metrics, downloads, and user engagement data.
  name: App Analytics
- description: Store and sync app data across devices using Apple's cloud infrastructure.
  name: CloudKit
jsonld:
- class_count: 0
  name: App Store Connect Context
  property_count: 0
  slug: app-store-connect-context
- class_count: 2
  name: Apple Context
  property_count: 9
  slug: apple-context
layout: provider
modified: '2026-04-18'
name: Apple
rules:
- name: Apple API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: apple-spectral-rules
skills: []
slug: apple
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Apple\ndescription: >-\n  Collection of Apple's public APIs and developer resources.\nimage: https://www.apple.com/ac/structured-data/images/knowledge_graph_logo.png\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nurl: https://developer.apple.com\nspecificationVersion: '0.19'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - Developer\n  - iOS\n  - macOS\n  - Mobile\n  - Technology\napis:\n  - name: Apple Music API\n    description: >-\n      Access Apple Music catalog, user library, and playback controls.\n    image: https://www.apple.com/v/apple-music/s/images/shared/og_image.png\n    humanURL: https://developer.apple.com/documentation/applemusicapi\n    baseURL: https://api.music.apple.com/v1\n    tags:\n      - Media\n      - Music\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/applemusicapi\n      - type: Authentication\n        url: https://developer.apple.com/documentation/applemusicapi/getting_keys_and_creating_tokens\n\
  \      - type: GettingStarted\n        url: https://developer.apple.com/documentation/applemusicapi/getting_keys_and_creating_tokens\n      - type: Portal\n        url: https://developer.apple.com/musickit/\n  - name: WeatherKit REST API\n    description: >-\n      Access weather forecasts, current conditions, and historical weather data.\n    humanURL: https://developer.apple.com/documentation/weatherkitrestapi\n    baseURL: https://weatherkit.apple.com/api/v1\n    tags:\n      - Data\n      - Forecast\n      - Weather\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/weatherkitrestapi\n      - type: Authentication\n        url: https://developer.apple.com/documentation/weatherkitrestapi/request_authentication_for_weatherkit_rest_api\n      - type: Portal\n        url: https://developer.apple.com/weatherkit/\n      - type: ChangeLog\n        url: https://developer.apple.com/documentation/updates/weatherkit\n  - name: App Store Connect\
  \ API\n    description: >-\n      Automate tasks for App Store Connect and access app metadata.\n    humanURL: https://developer.apple.com/documentation/appstoreconnectapi\n    baseURL: https://api.appstoreconnect.apple.com/v1\n    tags:\n      - Analytics\n      - App Store\n      - Publishing\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/appstoreconnectapi\n      - type: OpenAPI\n        url: https://developer.apple.com/sample-code/app-store-connect/app-store-connect-openapi-specification.zip\n      - type: OpenAPI\n        url: openapi/app-store-connect-api.yml\n      - type: JSONSchema\n        url: json-schema/apple-app-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-resource-link-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-paged-document-links-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-document-links-schema.json\n \
  \     - type: JSONSchema\n        url: json-schema/app-store-connect-paging-information-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-relationship-links-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-relationship-data-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-error-response-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-error-detail-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-app-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-app-attributes-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-app-relationships-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-app-response-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-apps-response-schema.json\n      - type: JSONSchema\n     \
  \   url: json-schema/app-store-connect-app-update-request-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-build-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-build-attributes-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-build-relationships-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-build-response-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-builds-response-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-build-update-request-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-beta-tester-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-beta-tester-attributes-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-beta-tester-relationships-schema.json\n      - type: JSONSchema\n        url:\
  \ json-schema/app-store-connect-beta-tester-response-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-beta-testers-response-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-beta-tester-create-request-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-beta-group-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-beta-group-attributes-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-beta-group-relationships-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-beta-group-response-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-beta-groups-response-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-beta-group-create-request-schema.json\n      - type: JSONSchema\n        url: json-schema/app-store-connect-beta-group-update-request-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/app-store-connect-beta-group-beta-testers-linkages-request-schema.json\n      - type: JSONLD\n        url: json-ld/app-store-connect-context.jsonld\n      - type: Authentication\n        url: https://developer.apple.com/documentation/appstoreconnectapi/creating_api_keys_for_app_store_connect_api\n      - type: GettingStarted\n        url: https://developer.apple.com/help/app-store-connect/get-started/app-store-connect-api/\n      - type: Portal\n        url: https://developer.apple.com/app-store-connect/api/\n      - type: ChangeLog\n        url: https://developer.apple.com/documentation/appstoreconnectapi/app-store-connect-api-release-notes\n  - name: MapKit JS\n    description: >-\n      Embed interactive Apple Maps on websites.\n    humanURL: https://developer.apple.com/documentation/mapkitjs\n    baseURL: https://cdn.apple-mapkit.com/mk/5.x.x/mapkit.js\n    tags:\n      - Javascript\n      - Location\n      - Maps\n    properties:\n\
  \      - type: Documentation\n        url: https://developer.apple.com/documentation/mapkitjs\n      - type: GettingStarted\n        url: https://developer.apple.com/documentation/mapkitjs/creating_and_using_tokens_with_mapkit_js\n      - type: Portal\n        url: https://developer.apple.com/maps/\n  - name: Sign in with Apple REST API\n    description: >-\n      Integrate Sign in with Apple authentication.\n    humanURL: https://developer.apple.com/documentation/sign_in_with_apple/sign_in_with_apple_rest_api\n    baseURL: https://appleid.apple.com/auth\n    tags:\n      - Authentication\n      - Identity\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/sign_in_with_apple/sign_in_with_apple_rest_api\n      - type: Authentication\n        url: https://developer.apple.com/documentation/sign_in_with_apple/generate_and_validate_tokens\n  - name: Apple Push Notification Service (APNs)\n    description: >-\n      Send push\
  \ notifications to iOS, macOS, watchOS, and tvOS devices.\n    humanURL: https://developer.apple.com/documentation/usernotifications\n    baseURL: https://api.push.apple.com\n    tags:\n      - Messaging\n      - Notifications\n      - Push\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/usernotifications/setting_up_a_remote_notification_server\n      - type: Authentication\n        url: https://developer.apple.com/documentation/usernotifications/setting_up_a_remote_notification_server/establishing_a_token-based_connection_to_apns\n  - name: App Store Server API\n    description: >-\n      Manage customer App Store transactions from your server, including in-app purchases and subscriptions.\n    humanURL: https://developer.apple.com/documentation/appstoreserverapi\n    baseURL: https://api.storekit.itunes.apple.com\n    tags:\n      - In-App Purchases\n      - Subscriptions\n      - Transactions\n    properties:\n      - type: Documentation\n\
  \        url: https://developer.apple.com/documentation/appstoreserverapi\n      - type: Authentication\n        url: https://developer.apple.com/documentation/appstoreserverapi/creating-api-keys-to-authorize-api-requests\n      - type: ChangeLog\n        url: https://developer.apple.com/documentation/appstoreserverapi/app-store-server-api-changelog\n  - name: App Store Server Notifications V2\n    description: >-\n      Receive real-time notifications about in-app purchase events and subscription lifecycle changes.\n    humanURL: https://developer.apple.com/documentation/appstoreservernotifications\n    tags:\n      - In-App Purchases\n      - Subscriptions\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/appstoreservernotifications\n      - type: GettingStarted\n        url: https://developer.apple.com/documentation/appstoreservernotifications/enabling-app-store-server-notifications\n  - name: Apple Maps Server API\n\
  \    description: >-\n      Server-side geocoding, reverse geocoding, search, and estimated time of arrival using Apple Maps.\n    humanURL: https://developer.apple.com/documentation/applemapsserverapi/\n    baseURL: https://maps-api.apple.com\n    tags:\n      - Geocoding\n      - Location\n      - Maps\n      - Search\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/applemapsserverapi/\n      - type: Authentication\n        url: https://developer.apple.com/documentation/applemapsserverapi/creating-and-using-tokens-with-maps-server-api\n      - type: Portal\n        url: https://developer.apple.com/maps/\n      - type: GettingStarted\n        url: https://developer.apple.com/maps/try-maps-server-api/\n  - name: Apple News API\n    description: >-\n      Publish, manage, update, and delete Apple News Format articles.\n    humanURL: https://developer.apple.com/documentation/applenewsapi\n    tags:\n      - Content\n      - News\n    \
  \  - Publishing\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/applenewsapi\n      - type: GettingStarted\n        url: https://developer.apple.com/documentation/applenews/apple-news-api-tutorial\n      - type: Authentication\n        url: https://developer.apple.com/documentation/apple_news/apple_news_api/about_the_apple_news_security_model\n  - name: DeviceCheck API\n    description: >-\n      Reduce fraudulent use of your services by managing device state and asserting app integrity.\n    humanURL: https://developer.apple.com/documentation/devicecheck\n    baseURL: https://api.devicecheck.apple.com\n    tags:\n      - Device\n      - Fraud Prevention\n      - Security\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/devicecheck\n      - type: GettingStarted\n        url: https://developer.apple.com/documentation/devicecheck/establishing-your-app-s-integrity\n  - name: Apple Ads\
  \ Campaign Management API\n    description: >-\n      Create, manage, and report on Apple Search Ads campaigns programmatically.\n    humanURL: https://developer.apple.com/documentation/apple_ads\n    baseURL: https://api.searchads.apple.com\n    tags:\n      - Advertising\n      - Campaigns\n      - Search Ads\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/apple_ads\n      - type: Authentication\n        url: https://developer.apple.com/documentation/apple_search_ads/calling_the_apple_search_ads_api\n      - type: Portal\n        url: https://searchads.apple.com/help/campaigns/0022-use-the-campaign-management-api\n  - name: Wallet Passes Web Service\n    description: >-\n      Create, distribute, and update passes for the Apple Wallet app via a web service.\n    humanURL: https://developer.apple.com/documentation/walletpasses\n    tags:\n      - Passes\n      - Payments\n      - Wallet\n    properties:\n      - type: Documentation\n\
  \        url: https://developer.apple.com/documentation/walletpasses\n      - type: GettingStarted\n        url: https://developer.apple.com/documentation/walletpasses/adding-a-web-service-to-update-passes\n  - name: Enterprise Program API\n    description: >-\n      Automate management of users, roles, provisioning profiles, and bundle identifiers for enterprise apps.\n    humanURL: https://developer.apple.com/documentation/enterpriseprogramapi\n    tags:\n      - Certificates\n      - Enterprise\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/enterpriseprogramapi\n      - type: Authentication\n        url: https://developer.apple.com/documentation/enterpriseprogramapi/creating-api-keys-for-enterprise-program-api\n      - type: ChangeLog\n        url: https://developer.apple.com/documentation/enterpriseprogramapi/enterprise-api-release-notes\n      - type: RateLimits\n        url: https://developer.apple.com/documentation/enterpriseprogramapi/identifying-rate-limits\n\
  \  - name: Apple School and Business Manager API\n    description: >-\n      Automate device management actions and access data about devices enrolled via Automated Device Enrollment.\n    humanURL: https://developer.apple.com/documentation/apple-school-and-business-manager-api\n    tags:\n      - Device Management\n      - Education\n      - Enrollment\n      - Enterprise\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/apple-school-and-business-manager-api\n      - type: Authentication\n        url: https://developer.apple.com/documentation/apple-school-and-business-manager-api/implementing-oauth-for-the-apple-school-and-business-manager-api\n  - name: Apple Pay on the Web\n    description: >-\n      Accept Apple Pay payments on your website using JavaScript-based APIs.\n    humanURL: https://developer.apple.com/documentation/applepayontheweb\n    tags:\n      - Apple Pay\n      - Payments\n      - Web\n    properties:\n      - type:\
  \ Documentation\n        url: https://developer.apple.com/documentation/applepayontheweb\n      - type: GettingStarted\n        url: https://developer.apple.com/documentation/applepayontheweb/choosing-an-api-for-implementing-apple-pay-on-your-website\n      - type: Portal\n        url: https://developer.apple.com/apple-pay/implementation/\n  - name: Wallet Orders\n    description: >-\n      Create, distribute, and update orders in Apple Wallet for order tracking.\n    humanURL: https://developer.apple.com/documentation/walletorders\n    tags:\n      - Orders\n      - Tracking\n      - Wallet\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/walletorders\n  - name: ClassKit Catalog API\n    description: >-\n      Declare educational activities supported by your app for use with Apple Schoolwork.\n    humanURL: https://developer.apple.com/documentation/classkitcatalogapi\n    baseURL: https://classkit-catalog.apple.com\n    tags:\n    \
  \  - ClassKit\n      - Education\n      - Schoolwork\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/classkitcatalogapi\n      - type: Authentication\n        url: https://developer.apple.com/documentation/classkitcatalogapi/authenticating-calls-to-the-classkit-catalog-api\n  - name: Apple Music Feed API\n    description: >-\n      Access the Apple Music catalog metadata in bulk for albums, songs, and artists.\n    humanURL: https://developer.apple.com/documentation/applemusicfeed\n    tags:\n      - Catalog\n      - Feed\n      - Music\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/applemusicfeed\ncommon:\n  - type: DeveloperPortal\n    url: https://developer.apple.com\n  - type: TermsOfService\n    url: https://developer.apple.com/terms/\n  - type: PrivacyPolicy\n    url: https://www.apple.com/legal/privacy/\n  - type: Support\n    url: https://developer.apple.com/support/\n \
  \ - type: Blog\n    url: https://developer.apple.com/news/\n  - type: StatusPage\n    url: https://developer.apple.com/system-status/\n  - type: SignUp\n    url: https://developer.apple.com/programs/enroll/\n  - type: Pricing\n    url: https://developer.apple.com/support/compare-memberships/\n  - type: GitHubOrganization\n    url: https://github.com/apple\n  - type: YouTube\n    url: https://developer.apple.com/videos/\n  - type: ChangeLog\n    url: https://developer.apple.com/documentation/updates\n  - type: Authentication\n    url: https://developer.apple.com/documentation/appstoreconnectapi/generating-tokens-for-api-requests\n  - type: Tutorials\n    url: https://developer.apple.com/tutorials/\n  - type: CodeExamples\n    url: https://developer.apple.com/sample-code/\n  - type: SDK\n    url: https://developer.apple.com/download/\n  - type: Contact\n    url: https://developer.apple.com/contact/\n  - type: JSONLD\n    url: json-ld/apple-context.jsonld\n  - type: SpectralRules\n    url:\
  \ rules/apple-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/app-lifecycle.yaml\n  - type: Features\n    data:\n      - name: App Store Connect\n        description: Automate app management, TestFlight, submissions, and analytics through a comprehensive REST API.\n      - name: Apple Pay\n        description: Accept payments seamlessly on web and in apps with secure tokenized transactions.\n      - name: Push Notifications\n        description: Send real-time notifications to billions of Apple devices across iOS, macOS, watchOS, and tvOS.\n      - name: Sign in with Apple\n        description: Privacy-focused authentication that lets users sign in without sharing personal information.\n      - name: MapKit and Maps Server\n        description: Embed interactive maps and perform server-side geocoding with Apple Maps infrastructure.\n      - name: WeatherKit\n        description: Access hyper-local weather forecasts, conditions, and historical data worldwide.\n  \
  \    - name: MusicKit\n        description: Integrate Apple Music catalog, user library, and playback into apps and websites.\n  - type: UseCases\n    data:\n      - name: App Distribution\n        description: Automate app submissions, manage TestFlight beta testing, and handle app metadata at scale.\n      - name: In-App Purchases\n        description: Manage subscriptions, consumables, and transaction history with server-side verification.\n      - name: Enterprise Device Management\n        description: Automate device enrollment and management for schools and businesses at scale.\n      - name: Content Publishing\n        description: Publish and manage articles in Apple News with rich media and analytics.\n      - name: Location Services\n        description: Build location-aware applications with geocoding, routing, and interactive maps.\n  - type: Integrations\n    data:\n      - name: Xcode\n        description: Full IDE integration for building, testing, and deploying apps across\
  \ all Apple platforms.\n      - name: TestFlight\n        description: Beta testing platform for distributing pre-release builds to internal and external testers.\n      - name: App Analytics\n        description: View app performance metrics, downloads, and user engagement data.\n      - name: CloudKit\n        description: Store and sync app data across devices using Apple's cloud infrastructure.\nmaintainers:\n  - name: Apple Developer Relations\n    email: developer@apple.com\n    url: https://developer.apple.com/contact/\n  - name: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apple/refs/heads/main/apis.yml
tags:
- Developer
- iOS
- macOS
- Mobile
- Technology
url: https://developer.apple.com
use_cases:
- description: Automate app submissions, manage TestFlight beta testing, and handle app metadata at scale.
  name: App Distribution
- description: Manage subscriptions, consumables, and transaction history with server-side verification.
  name: In-App Purchases
- description: Automate device enrollment and management for schools and businesses at scale.
  name: Enterprise Device Management
- description: Publish and manage articles in Apple News with rich media and analytics.
  name: Content Publishing
- description: Build location-aware applications with geocoding, routing, and interactive maps.
  name: Location Services
---
