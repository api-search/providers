---
api_count: 21
api_specs:
- filename: google-play-developer-api.yml
  format: yaml
  label: Google Play Developer APIs
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/android/refs/heads/main/openapi/google-play-developer-api.yml
apis:
- description: Core Android framework APIs for building Android applications.
  name: Android Platform APIs
  slug: ''
- description: APIs for integrating Google services into Android apps.
  name: Google Play Services APIs
  slug: ''
- description: Firebase SDKs and APIs for Android app development.
  name: Firebase Android APIs
  slug: ''
- description: Add maps, location, and geospatial data to Android applications.
  name: Google Maps Android API
  slug: ''
- description: Suite of libraries to help developers follow best practices.
  name: Android Jetpack APIs
  slug: ''
- description: Programmatically manage app releases and track analytics.
  name: Google Play Console API
  slug: ''
- description: Implement in-app purchases and subscriptions.
  name: Google Play Billing API
  slug: ''
- description: Native Development Kit for implementing parts of Android apps in C and C++ for performance-critical code.
  name: Android NDK APIs
  slug: ''
- description: On-device machine learning APIs for text recognition, face detection, barcode scanning, image labeling, and more.
  name: Google ML Kit Android APIs
  slug: ''
- description: Health data platform providing a single consolidated interface for accessing user health and fitness data across apps.
  name: Android Health Connect API
  slug: ''
- description: Jetpack library for camera app development with consistent behavior across Android devices.
  name: Android CameraX API
  slug: ''
- description: APIs for building applications for Wear OS smartwatches and wearable devices.
  name: Wear OS APIs
  slug: ''
- description: APIs for building apps for Android Auto and Android Automotive OS in-vehicle experiences.
  name: Android for Cars APIs
  slug: ''
- description: Monetize Android apps with in-app advertising including banner, interstitial, native, and rewarded ad formats.
  name: Google AdMob Android API
  slug: ''
- description: Framework APIs for building accessible applications and custom accessibility services.
  name: Android Accessibility APIs
  slug: ''
- description: APIs and tools for building apps optimized for the television experience using Compose for TV and Leanback.
  name: Android TV APIs
  slug: ''
- description: Verify that interactions and server requests come from genuine apps on genuine Android devices.
  name: Google Play Integrity API
  slug: ''
- description: Unified API for managing user credentials including passkeys, passwords, and federated sign-in.
  name: Android Credential Manager API
  slug: ''
- description: On-device generative AI powered by Gemini Nano for summarization, proofreading, rewriting, and image description without network connectivity.
  name: Gemini Nano On-Device AI API
  slug: ''
- description: Suite of REST-based web service APIs for performing publishing, reporting, and app-management functions programmatically.
  name: Google Play Developer APIs
  slug: ''
- description: Cloud-based Gemini API for integrating generative AI capabilities into Android applications.
  name: Gemini Developer API for Android
  slug: ''
capabilities:
- description: Unified workflow for managing Android app monetization through in-app purchases, subscriptions, reviews, and order management using the Google Play Developer API. Designed for app developers and produ
  name: Android App Monetization and Reviews
  slug: app-monetization
common:
- title: ''
  type: Portal
  url: https://developer.android.com
- title: ''
  type: Blog
  url: https://android-developers.googleblog.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/android
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/android
- title: ''
  type: X
  url: https://twitter.com/AndroidDev
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/androiddevelopers
- title: ''
  type: GettingStarted
  url: https://developer.android.com/get-started/overview
- title: ''
  type: Training
  url: https://developer.android.com/courses
- title: ''
  type: ReleaseNotes
  url: https://developer.android.com/about/versions
created: '2024-01-01'
description: Collection of APIs and services available in the Android ecosystem.
features:
- description: Modern declarative UI toolkit for building native Android interfaces with less code and powerful tools.
  name: Jetpack Compose
- description: Design system providing components, layouts, and guidelines for building consistent Android user experiences.
  name: Material Design
- description: Run machine learning models locally on devices with ML Kit and Gemini Nano for privacy-preserving AI features.
  name: On-Device AI
- description: Unified health data platform allowing apps to share and access user health and fitness data with user consent.
  name: Health Connect
- description: Build apps that work seamlessly across phones, tablets, wearables, TVs, and cars with adaptive layouts.
  name: Multi-Device Experiences
- description: Protect apps with Play Integrity API, Credential Manager for passkeys, and built-in security best practices.
  name: App Security
image: https://www.android.com/static/images/logos/android-logo.png
integrations:
- description: Integrate cloud backend services including authentication, real-time database, cloud messaging, and analytics.
  name: Firebase
- description: Add interactive maps, location services, and geospatial data to Android applications.
  name: Google Maps
- description: Access Google platform capabilities including authentication, location, and Google Drive APIs.
  name: Google Play Services
- description: Deploy custom machine learning models on Android devices for real-time inference with hardware acceleration.
  name: TensorFlow Lite
jsonld:
- class_count: 0
  name: Android Context
  property_count: 19
  slug: android-context
- class_count: 0
  name: Google Play Developer Context
  property_count: 0
  slug: google-play-developer-context
layout: provider
modified: '2026-04-18'
name: Android
rules:
- name: Android API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: android-spectral-rules
skills: []
slug: android
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: android\nname: Android\ndescription: >-\n  Collection of APIs and services available in the Android ecosystem.\nimage: https://www.android.com/static/images/logos/android-logo.png\nurl: https://developer.android.com/reference\ntype: Index\nposition: Consumer\naccess: 3rd-Party\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - AI\n  - Android\n  - Automotive\n  - Google\n  - Machine Learning\n  - Mobile Development\n  - SDK\n  - TV\n  - Wearables\napis:\n  - name: Android Platform APIs\n    description: >-\n      Core Android framework APIs for building Android applications.\n    image: https://www.android.com/static/images/logos/android-logo.png\n    humanURL: https://developer.android.com/reference\n    baseURL: https://developer.android.com\n    tags:\n      - Android\n      - Framework\n      - Mobile\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/docs\n      - type: APIReference\n\
  \        url: https://developer.android.com/reference\n      - type: GettingStarted\n        url: https://developer.android.com/training/basics/firstapp\n      - type: CodeExamples\n        url: https://developer.android.com/samples\n      - type: ReleaseNotes\n        url: https://developer.android.com/tools/releases/platforms\n      - type: Features\n        url: https://developer.android.com/about/versions/16/features\n    contact:\n      - FN: Android Support\n        url: https://developer.android.com/support\n  - name: Google Play Services APIs\n    description: >-\n      APIs for integrating Google services into Android apps.\n    image: https://www.gstatic.com/android/market_images/web/favicon_v2.ico\n    humanURL: https://developers.google.com/android/guides/overview\n    baseURL: https://developers.google.com/android\n    tags:\n      - Authentication\n      - Google Play\n      - Location\n      - Maps\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/android/guides/overview\n\
  \      - type: APIReference\n        url: https://developers.google.com/android/reference\n      - type: GettingStarted\n        url: https://developers.google.com/android/guides/setup\n      - type: ReleaseNotes\n        url: https://developers.google.com/android/guides/releases\n    contact:\n      - FN: Google Android Support\n        url: https://developers.google.com/android/support\n  - name: Firebase Android APIs\n    description: >-\n      Firebase SDKs and APIs for Android app development.\n    image: https://firebase.google.com/images/brand-guidelines/logo-standard.png\n    humanURL: https://firebase.google.com/docs/android/setup\n    baseURL: https://firebase.google.com\n    tags:\n      - Analytics\n      - Authentication\n      - Backend\n      - Cloud Messaging\n      - Database\n      - Firebase\n    properties:\n      - type: Documentation\n        url: https://firebase.google.com/docs/android/setup\n      - type: APIReference\n        url: https://firebase.google.com/docs/reference/android\n\
  \      - type: CodeExamples\n        url: https://github.com/firebase/quickstart-android\n      - type: Console\n        url: https://console.firebase.google.com\n      - type: ReleaseNotes\n        url: https://firebase.google.com/support/release-notes/android\n    contact:\n      - FN: Firebase Support\n        url: https://firebase.google.com/support\n  - name: Google Maps Android API\n    description: >-\n      Add maps, location, and geospatial data to Android applications.\n    image: https://developers.google.com/maps/images/maps-icon.svg\n    humanURL: https://developers.google.com/maps/documentation/android-sdk\n    baseURL: https://maps.googleapis.com\n    tags:\n      - Geolocation\n      - Location\n      - Maps\n      - Navigation\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/maps/documentation/android-sdk\n      - type: APIReference\n        url: https://developers.google.com/android/reference/com/google/android/gms/maps/package-summary\n\
  \      - type: Pricing\n        url: https://developers.google.com/maps/pricing-and-plans\n      - type: GettingStarted\n        url: https://developers.google.com/maps/documentation/android-sdk/start\n      - type: CodeExamples\n        url: https://github.com/googlemaps/android-samples\n    contact:\n      - FN: Google Maps Support\n        url: https://developers.google.com/maps/support\n  - name: Android Jetpack APIs\n    description: >-\n      Suite of libraries to help developers follow best practices.\n    image: https://developer.android.com/images/jetpack/jetpack-hero.svg\n    humanURL: https://developer.android.com/jetpack\n    baseURL: https://developer.android.com/jetpack\n    tags:\n      - Architecture\n      - Compose\n      - Jetpack\n      - Libraries\n      - UI\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/jetpack/getting-started\n      - type: APIReference\n        url: https://developer.android.com/jetpack/androidx\n    \
  \  - type: ReleaseNotes\n        url: https://developer.android.com/jetpack/androidx/versions\n      - type: CodeExamples\n        url: https://developer.android.com/jetpack/samples\n    contact:\n      - FN: Android Support\n        url: https://developer.android.com/support\n  - name: Google Play Console API\n    description: >-\n      Programmatically manage app releases and track analytics.\n    image: https://www.gstatic.com/android/market_images/web/favicon_v2.ico\n    humanURL: https://developers.google.com/android-publisher\n    baseURL: https://androidpublisher.googleapis.com\n    tags:\n      - Analytics\n      - Distribution\n      - Publishing\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/android-publisher\n      - type: APIReference\n        url: https://developers.google.com/android-publisher/api-ref\n      - type: Authentication\n        url: https://developers.google.com/android-publisher/authorization\n    \
  \  - type: ReleaseNotes\n        url: https://developer.android.com/google/play/billing/play-developer-apis-release-notes\n    contact:\n      - FN: Google Play Support\n        url: https://support.google.com/googleplay/android-developer\n  - name: Google Play Billing API\n    description: >-\n      Implement in-app purchases and subscriptions.\n    image: https://www.gstatic.com/android/market_images/web/favicon_v2.ico\n    humanURL: https://developer.android.com/google/play/billing\n    baseURL: https://developer.android.com/google/play/billing\n    tags:\n      - Billing\n      - In-App Purchases\n      - Monetization\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/google/play/billing/integrate\n      - type: APIReference\n        url: https://developer.android.com/google/play/billing/api\n    contact:\n      - FN: Google Play Support\n        url: https://support.google.com/googleplay/android-developer\n  - name: Android\
  \ NDK APIs\n    description: >-\n      Native Development Kit for implementing parts of Android apps in C and C++ for\n      performance-critical code.\n    image: https://www.android.com/static/images/logos/android-logo.png\n    humanURL: https://developer.android.com/ndk\n    baseURL: https://developer.android.com/ndk\n    tags:\n      - C++\n      - Native\n      - NDK\n      - OpenGL\n      - Performance\n      - Vulkan\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/ndk/guides\n      - type: APIReference\n        url: https://developer.android.com/ndk/guides/stable_apis\n      - type: GettingStarted\n        url: https://developer.android.com/ndk/guides\n      - type: CodeExamples\n        url: https://github.com/android/ndk-samples\n    contact:\n      - FN: Android Support\n        url: https://developer.android.com/support\n  - name: Google ML Kit Android APIs\n    description: >-\n      On-device machine learning APIs for text recognition,\
  \ face detection, barcode\n      scanning, image labeling, and more.\n    image: https://www.android.com/static/images/logos/android-logo.png\n    humanURL: https://developers.google.com/ml-kit\n    baseURL: https://developers.google.com/ml-kit\n    tags:\n      - Barcode Scanning\n      - Face Detection\n      - Machine Learning\n      - ML Kit\n      - On-Device\n      - Text Recognition\n      - Vision\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/ml-kit\n      - type: APIReference\n        url: https://developers.google.com/ml-kit/reference/android\n      - type: ReleaseNotes\n        url: https://developers.google.com/ml-kit/release-notes\n      - type: CodeExamples\n        url: https://github.com/googlesamples/mlkit\n    contact:\n      - FN: Android Support\n        url: https://developer.android.com/support\n  - name: Android Health Connect API\n    description: >-\n      Health data platform providing a single consolidated interface\
  \ for accessing\n      user health and fitness data across apps.\n    image: https://www.android.com/static/images/logos/android-logo.png\n    humanURL: https://developer.android.com/health-and-fitness/health-connect\n    baseURL: https://developer.android.com/health-and-fitness\n    tags:\n      - Data Sharing\n      - Fitness\n      - Health\n      - Privacy\n      - Wearables\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/health-and-fitness/health-connect\n      - type: GettingStarted\n        url: https://developer.android.com/health-and-fitness/health-connect/get-started\n      - type: APIReference\n        url: https://developer.android.com/reference/android/health/connect/package-summary\n    contact:\n      - FN: Android Support\n        url: https://developer.android.com/support\n  - name: Android CameraX API\n    description: >-\n      Jetpack library for camera app development with consistent behavior across Android\n      devices.\n\
  \    image: https://www.android.com/static/images/logos/android-logo.png\n    humanURL: https://developer.android.com/media/camera/camerax\n    baseURL: https://developer.android.com/media/camera\n    tags:\n      - Camera\n      - Image Capture\n      - Jetpack\n      - Media\n      - Video\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/media/camera/camerax\n      - type: GettingStarted\n        url: https://developer.android.com/codelabs/camerax-getting-started\n      - type: ReleaseNotes\n        url: https://developer.android.com/jetpack/androidx/releases/camera\n      - type: CodeExamples\n        url: https://github.com/android/camera-samples\n    contact:\n      - FN: Android Support\n        url: https://developer.android.com/support\n  - name: Wear OS APIs\n    description: >-\n      APIs for building applications for Wear OS smartwatches and wearable devices.\n    image: https://www.android.com/static/images/logos/android-logo.png\n\
  \    humanURL: https://developer.android.com/wear\n    baseURL: https://developer.android.com/wear\n    tags:\n      - Smartwatch\n      - Tiles\n      - Watch Face\n      - Wear OS\n      - Wearables\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/training/wearables\n      - type: GettingStarted\n        url: https://developer.android.com/training/wearables\n      - type: CodeExamples\n        url: https://github.com/android/wear-os-samples\n    contact:\n      - FN: Android Support\n        url: https://developer.android.com/support\n  - name: Android for Cars APIs\n    description: >-\n      APIs for building apps for Android Auto and Android Automotive OS in-vehicle\n      experiences.\n    image: https://www.android.com/static/images/logos/android-logo.png\n    humanURL: https://developer.android.com/cars\n    baseURL: https://developer.android.com/cars\n    tags:\n      - Android Auto\n      - Automotive\n      - Cars\n      - Media\n   \
  \   - Navigation\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/training/cars\n      - type: APIReference\n        url: https://developer.android.com/reference/android/car/package-summary\n      - type: CodeExamples\n        url: https://github.com/android/car-samples\n    contact:\n      - FN: Android Support\n        url: https://developer.android.com/support\n  - name: Google AdMob Android API\n    description: >-\n      Monetize Android apps with in-app advertising including banner, interstitial,\n      native, and rewarded ad formats.\n    image: https://www.gstatic.com/android/market_images/web/favicon_v2.ico\n    humanURL: https://developers.google.com/admob\n    baseURL: https://developers.google.com/admob\n    tags:\n      - AdMob\n      - Ads\n      - Advertising\n      - Banner\n      - Interstitial\n      - Monetization\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/admob\n      - type: GettingStarted\n\
  \        url: https://developers.google.com/admob/android/quick-start\n      - type: APIReference\n        url: https://developers.google.com/admob/api\n      - type: CodeExamples\n        url: https://github.com/googleads/googleads-mobile-android-examples\n    contact:\n      - FN: AdMob Support\n        url: https://developers.google.com/admob/support\n  - name: Android Accessibility APIs\n    description: >-\n      Framework APIs for building accessible applications and custom accessibility\n      services.\n    image: https://www.android.com/static/images/logos/android-logo.png\n    humanURL: https://developer.android.com/guide/topics/ui/accessibility\n    baseURL: https://developer.android.com\n    tags:\n      - A11y\n      - Accessibility\n      - Assistive Technology\n      - Screen Reader\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/guide/topics/ui/accessibility\n      - type: APIReference\n        url: https://developer.android.com/reference/android/accessibilityservice/AccessibilityService\n\
  \    contact:\n      - FN: Android Support\n        url: https://developer.android.com/support\n  - name: Android TV APIs\n    description: >-\n      APIs and tools for building apps optimized for the television experience using\n      Compose for TV and Leanback.\n    image: https://www.android.com/static/images/logos/android-logo.png\n    humanURL: https://developer.android.com/tv\n    baseURL: https://developer.android.com/tv\n    tags:\n      - Android TV\n      - Leanback\n      - Living Room\n      - Media\n      - Television\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/tv\n      - type: CodeExamples\n        url: https://github.com/android/tv-samples\n    contact:\n      - FN: Android Support\n        url: https://developer.android.com/support\n  - name: Google Play Integrity API\n    description: >-\n      Verify that interactions and server requests come from genuine apps on genuine\n      Android devices.\n    image: https://www.gstatic.com/android/market_images/web/favicon_v2.ico\n\
  \    humanURL: https://developer.android.com/google/play/integrity\n    baseURL: https://developer.android.com/google/play/integrity\n    tags:\n      - Anti-Fraud\n      - Device Attestation\n      - Integrity\n      - Security\n      - Verification\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/google/play/integrity/overview\n    contact:\n      - FN: Google Play Support\n        url: https://support.google.com/googleplay/android-developer\n  - name: Android Credential Manager API\n    description: >-\n      Unified API for managing user credentials including passkeys, passwords, and\n      federated sign-in.\n    image: https://www.android.com/static/images/logos/android-logo.png\n    humanURL: https://developer.android.com/identity/credential-manager\n    baseURL: https://developer.android.com/identity\n    tags:\n      - Authentication\n      - Credentials\n      - Identity\n      - Passkeys\n      - Security\n      - Sign-In\n    properties:\n\
  \      - type: Documentation\n        url: https://developer.android.com/identity/credential-manager\n    contact:\n      - FN: Android Support\n        url: https://developer.android.com/support\n  - name: Gemini Nano On-Device AI API\n    description: >-\n      On-device generative AI powered by Gemini Nano for summarization, proofreading,\n      rewriting, and image description without network connectivity.\n    image: https://www.android.com/static/images/logos/android-logo.png\n    humanURL: https://developer.android.com/ai/gemini-nano\n    baseURL: https://developer.android.com/ai\n    tags:\n      - AI\n      - Gemini Nano\n      - Generative AI\n      - LLM\n      - Machine Learning\n      - On-Device\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/ai/gemini-nano\n    contact:\n      - FN: Android Support\n        url: https://developer.android.com/support\n  - name: Google Play Developer APIs\n    description: >-\n      Suite of REST-based\
  \ web service APIs for performing publishing, reporting, and\n      app-management functions programmatically.\n    image: https://www.gstatic.com/android/market_images/web/favicon_v2.ico\n    humanURL: https://developer.android.com/google/play/developer-api\n    baseURL: https://androidpublisher.googleapis.com\n    tags:\n      - App Management\n      - Google Play\n      - Publishing\n      - Purchases\n      - Reporting\n      - REST API\n      - Reviews\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/google/play/developer-api\n      - type: APIReference\n        url: https://developers.google.com/android-publisher/api-ref/rest\n      - type: OpenAPI\n        url: openapi/google-play-developer-api.yml\n      - type: JSONSchema\n        url: json-schema/android-app-schema.json\n      - type: JSONLD\n        url: json-ld/android-context.jsonld\n      - type: ReleaseNotes\n        url: https://developer.android.com/google/play/billing/play-developer-apis-release-notes\n\
  \    contact:\n      - FN: Google Play Support\n        url: https://support.google.com/googleplay/android-developer\n  - name: Gemini Developer API for Android\n    description: >-\n      Cloud-based Gemini API for integrating generative AI capabilities into Android\n      applications.\n    image: https://www.android.com/static/images/logos/android-logo.png\n    humanURL: https://developer.android.com/ai/gemini/developer-api\n    baseURL: https://developer.android.com/ai\n    tags:\n      - AI\n      - Cloud\n      - Gemini\n      - Generative AI\n      - LLM\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/ai/gemini/developer-api\n      - type: GettingStarted\n        url: https://developer.android.com/ai/gemini/developer-api\n    contact:\n      - FN: Android Support\n        url: https://developer.android.com/support\ncommon:\n  - type: Portal\n    url: https://developer.android.com\n  - type: Blog\n    url: https://android-developers.googleblog.com\n\
  \  - type: GitHubOrganization\n    url: https://github.com/android\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/android\n  - type: X\n    url: https://twitter.com/AndroidDev\n  - type: YouTube\n    url: https://www.youtube.com/user/androiddevelopers\n  - type: GettingStarted\n    url: https://developer.android.com/get-started/overview\n  - type: Training\n    url: https://developer.android.com/courses\n  - type: ReleaseNotes\n    url: https://developer.android.com/about/versions\n  - type: Features\n    data:\n      - name: Jetpack Compose\n        description: Modern declarative UI toolkit for building native Android interfaces with less code and powerful tools.\n      - name: Material Design\n        description: Design system providing components, layouts, and guidelines for building consistent Android user experiences.\n      - name: On-Device AI\n        description: Run machine learning models locally on devices with ML Kit and Gemini Nano for privacy-preserving\
  \ AI features.\n      - name: Health Connect\n        description: Unified health data platform allowing apps to share and access user health and fitness data with user consent.\n      - name: Multi-Device Experiences\n        description: Build apps that work seamlessly across phones, tablets, wearables, TVs, and cars with adaptive layouts.\n      - name: App Security\n        description: Protect apps with Play Integrity API, Credential Manager for passkeys, and built-in security best practices.\n  - type: UseCases\n    data:\n      - name: Mobile App Development\n        description: Build native Android applications for phones and tablets using Kotlin, Jetpack, and Material Design.\n      - name: Wearable Apps\n        description: Create watch face designs and health-focused apps for Wear OS smartwatches and fitness devices.\n      - name: In-Vehicle Experiences\n        description: Build media, messaging, and navigation apps for Android Auto and Android Automotive OS.\n      - name:\
  \ TV Entertainment\n        description: Develop media streaming and entertainment apps optimized for the large-screen TV experience.\n      - name: In-App Monetization\n        description: Implement subscriptions, in-app purchases, and advertising revenue using Google Play Billing and AdMob.\n  - type: Integrations\n    data:\n      - name: Firebase\n        description: Integrate cloud backend services including authentication, real-time database, cloud messaging, and analytics.\n      - name: Google Maps\n        description: Add interactive maps, location services, and geospatial data to Android applications.\n      - name: Google Play Services\n        description: Access Google platform capabilities including authentication, location, and Google Drive APIs.\n      - name: TensorFlow Lite\n        description: Deploy custom machine learning models on Android devices for real-time inference with hardware acceleration.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\
  \    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/android/refs/heads/main/apis.yml
tags:
- AI
- Android
- Automotive
- Google
- Machine Learning
- Mobile Development
- SDK
- TV
- Wearables
url: https://developer.android.com/reference
use_cases:
- description: Build native Android applications for phones and tablets using Kotlin, Jetpack, and Material Design.
  name: Mobile App Development
- description: Create watch face designs and health-focused apps for Wear OS smartwatches and fitness devices.
  name: Wearable Apps
- description: Build media, messaging, and navigation apps for Android Auto and Android Automotive OS.
  name: In-Vehicle Experiences
- description: Develop media streaming and entertainment apps optimized for the large-screen TV experience.
  name: TV Entertainment
- description: Implement subscriptions, in-app purchases, and advertising revenue using Google Play Billing and AdMob.
  name: In-App Monetization
---
