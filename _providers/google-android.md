---
api_count: 9
apis:
- description: The Android Management API provides remote enterprise management of Android devices by creating and managing policies that control device behavior and apps.
  name: Android Management API
  slug: android-management-api
- description: The Google Play Developer API allows you to perform a number of publishing and app-management tasks including managing in-app purchases and subscriptions.
  name: Google Play Developer API
  slug: google-play-developer-api
- description: Firebase Cloud Messaging (FCM) is a cross-platform messaging solution that lets you reliably send messages to Android devices at no cost.
  name: Firebase Cloud Messaging API
  slug: firebase-cloud-messaging-api
- description: The Google Play Games Services API enables games to integrate with features like achievements, leaderboards, and multiplayer gaming.
  name: Google Play Games Services API
  slug: google-play-games-services-api
- description: The Android Device Provisioning Partner API allows device resellers and enterprise mobility management providers to programmatically manage zero-touch enrollment for enterprise Android devices, includ
  name: Android Device Provisioning Partner API
  slug: android-device-provisioning-partner-api
- description: The Android Over the Air API provides the infrastructure used by the Android partner portal for managing device system updates, including deployments, configurations, groups, and packages.
  name: Android Over the Air API
  slug: android-over-the-air-api
- description: 'The Google Play EMM API enables enterprise mobility management providers to manage the distribution of Android apps and configurations to enterprise users and devices. This API is no longer accepting '
  name: Google Play EMM API
  slug: google-play-emm-api
- description: The Play Integrity API helps protect your apps and games from potentially risky and fraudulent interactions by checking that interactions and server requests are coming from your genuine app binary ru
  name: Play Integrity API
  slug: play-integrity-api
- description: The Cloud Testing API powers Firebase Test Lab, enabling developers to test Android and iOS apps on real and virtual devices hosted in Google data centers, including instrumentation tests and robo tes
  name: Cloud Testing API
  slug: cloud-testing-api
common:
- title: ''
  type: Portal
  url: https://developers.android.com/
- title: ''
  type: Blog
  url: https://android-developers.googleblog.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/android
- title: ''
  type: TermsOfService
  url: https://developers.google.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://policies.google.com/privacy
- title: ''
  type: Support
  url: https://developer.android.com/support
- title: ''
  type: Newsletter
  url: https://developer.android.com/newsletter
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/android
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/androiddevelopers
- title: ''
  type: Support
  url: https://issuetracker.google.com/issues?q=componentid:192735
- title: ''
  type: Training
  url: https://developer.android.com/courses
- title: ''
  type: StatusPage
  url: https://status.cloud.google.com/
created: '2024-01-01'
description: Android is a mobile operating system developed by Google, based on a modified version of the Linux kernel and other open-source software. It powers billions of devices worldwide including smartphones, tablets, TVs, and wearables.
features:
- description: Remotely manage and configure Android devices with policies for enterprise mobility.
  name: Enterprise Device Management
- description: Publish and manage Android apps on Google Play including in-app purchases and subscriptions.
  name: App Publishing and Distribution
- description: Send cross-platform push notifications to Android devices via Firebase Cloud Messaging.
  name: Push Notifications
- description: Verify that interactions come from genuine app binaries running on genuine Android devices.
  name: Play Integrity
- description: Automate enterprise device provisioning and enrollment at scale.
  name: Zero-Touch Enrollment
- description: Test Android apps on real and virtual devices in Google data centers via Firebase Test Lab.
  name: Cloud Testing
- description: Integrate achievements, leaderboards, and multiplayer features into Android games.
  name: Game Services
- description: Manage system updates and firmware deployments for Android device fleets.
  name: Over-the-Air Updates
image: https://www.android.com/static/images/logos/android-logo.png
integrations:
- description: Integrate with Firebase for analytics, crashlytics, authentication, and cloud messaging.
  name: Firebase
- description: Connect Android apps to Google Cloud services for storage, ML, and compute.
  name: Google Cloud
- description: Manage app releases, testing tracks, and performance metrics through the Play Console.
  name: Google Play Console
- description: Develop and debug Android apps with the official IDE and its integrated tools.
  name: Android Studio
- description: Use Android Jetpack libraries for architecture, UI, and behavior best practices.
  name: Jetpack Libraries
layout: provider
modified: '2026-04-18'
name: Google Android
skills: []
slug: google-android
solutions: []
source_filename: apis.yml
source_yaml: "aid: google-android\nname: Google Android\ndescription: Android is a mobile operating system developed by Google, based on a modified version of the Linux kernel and other open-source software. It powers billions of devices worldwide including smartphones, tablets, TVs, and wearables.\ntype: Index\nimage: https://www.android.com/static/images/logos/android-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/google-android/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\naccess: 3rd-Party\nspecificationVersion: '0.19'\ntags:\n  - Android\n  - Google\n  - Mobile Development\n  - Mobile Operating System\n  - Open Source\napis:\n  - aid: google-android:android-management-api\n    name: Android Management API\n    description: The Android Management API provides remote enterprise management of Android devices by creating and managing policies that control device behavior and apps.\n    image: https://www.gstatic.com/devrel-devsite/prod/v2ff77c87c709f3e5e323c03865ecedf5b4afc4446d0e0e2904abf9d5/android/images/touchicon-180.png\n\
  \    humanURL: https://developers.google.com/android/management\n    baseURL: https://androidmanagement.googleapis.com\n    tags:\n      - Device Management\n      - Enterprise\n      - MDM\n      - Policies\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/android/management/reference/rest\n      - type: OpenAPI\n        url: https://androidmanagement.googleapis.com/$discovery/rest?version=v1\n      - type: Authentication\n        url: https://developers.google.com/android/management/authentication\n  - aid: google-android:google-play-developer-api\n    name: Google Play Developer API\n    description: The Google Play Developer API allows you to perform a number of publishing and app-management tasks including managing in-app purchases and subscriptions.\n    image: https://play-lh.googleusercontent.com/BJIR7aQ3sMO0JlxdVcX_Wy8mMv-Inh8J9t3i-ARE6M9aKqBKPDxQMr1JkEALvMECEXRM\n    humanURL: https://developers.google.com/android-publisher\n    baseURL:\
  \ https://androidpublisher.googleapis.com\n    tags:\n      - In-App Purchases\n      - Play Store\n      - Publishing\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/android-publisher/api-ref/rest\n      - type: OpenAPI\n        url: https://androidpublisher.googleapis.com/$discovery/rest?version=v3\n      - type: Getting Started\n        url: https://developers.google.com/android-publisher/getting_started\n  - aid: google-android:firebase-cloud-messaging-api\n    name: Firebase Cloud Messaging API\n    description: Firebase Cloud Messaging (FCM) is a cross-platform messaging solution that lets you reliably send messages to Android devices at no cost.\n    image: https://firebase.google.com/images/social.png\n    humanURL: https://firebase.google.com/docs/cloud-messaging\n    baseURL: https://fcm.googleapis.com\n    tags:\n      - Cloud Messaging\n      - Firebase\n      - Messaging\n      - Push Notifications\n    properties:\n\
  \      - type: Documentation\n        url: https://firebase.google.com/docs/cloud-messaging/server\n      - type: OpenAPI\n        url: https://fcm.googleapis.com/$discovery/rest?version=v1\n      - type: SDK\n        url: https://firebase.google.com/docs/cloud-messaging/android/client\n  - aid: google-android:google-play-games-services-api\n    name: Google Play Games Services API\n    description: The Google Play Games Services API enables games to integrate with features like achievements, leaderboards, and multiplayer gaming.\n    image: https://play-lh.googleusercontent.com/BJIR7aQ3sMO0JlxdVcX_Wy8mMv-Inh8J9t3i-ARE6M9aKqBKPDxQMr1JkEALvMECEXRM\n    humanURL: https://developers.google.com/games/services\n    baseURL: https://www.googleapis.com/games/v1\n    tags:\n      - Achievements\n      - Gaming\n      - Leaderboards\n      - Multiplayer\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/games/services/web/api/rest\n      - type: OpenAPI\n\
  \        url: https://www.googleapis.com/discovery/v1/apis/games/v1/rest\n      - type: SDK\n        url: https://developers.google.com/games/services/android/quickstart\n  - aid: google-android:android-device-provisioning-partner-api\n    name: Android Device Provisioning Partner API\n    description: The Android Device Provisioning Partner API allows device resellers and enterprise mobility management providers to programmatically manage zero-touch enrollment for enterprise Android devices, including creating customers, claiming devices, and managing device metadata.\n    image: https://www.gstatic.com/devrel-devsite/prod/v2ff77c87c709f3e5e323c03865ecedf5b4afc4446d0e0e2904abf9d5/android/images/touchicon-180.png\n    humanURL: https://developers.google.com/zero-touch\n    baseURL: https://androiddeviceprovisioning.googleapis.com\n    tags:\n      - Device Provisioning\n      - Enterprise\n      - Reseller\n      - Zero-Touch Enrollment\n    properties:\n      - type: Documentation\n \
  \       url: https://developers.google.com/zero-touch/reference/reseller/rest\n      - type: Getting Started\n        url: https://developers.google.com/zero-touch/guides/overview\n  - aid: google-android:android-over-the-air-api\n    name: Android Over the Air API\n    description: The Android Over the Air API provides the infrastructure used by the Android partner portal for managing device system updates, including deployments, configurations, groups, and packages.\n    image: https://www.gstatic.com/devrel-devsite/prod/v2ff77c87c709f3e5e323c03865ecedf5b4afc4446d0e0e2904abf9d5/android/images/touchicon-180.png\n    humanURL: https://developers.google.com/android/over-the-air/reference/rest\n    baseURL: https://androidovertheair.googleapis.com\n    tags:\n      - Device Updates\n      - Firmware\n      - OTA Updates\n      - System Updates\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/android/over-the-air/reference/rest\n      - type: OpenAPI\n\
  \        url: https://androidovertheair.googleapis.com/$discovery/rest?version=v1\n      - type: Authentication\n        url: https://developers.google.com/android/over-the-air/v1/how-tos/authorizing\n  - aid: google-android:google-play-emm-api\n    name: Google Play EMM API\n    description: The Google Play EMM API enables enterprise mobility management providers to manage the distribution of Android apps and configurations to enterprise users and devices. This API is no longer accepting new registrations but remains available for existing integrations.\n    image: https://www.gstatic.com/devrel-devsite/prod/v2ff77c87c709f3e5e323c03865ecedf5b4afc4446d0e0e2904abf9d5/android/images/touchicon-180.png\n    humanURL: https://developers.google.com/android/work/play/emm-api/\n    baseURL: https://androidenterprise.googleapis.com\n    tags:\n      - App Management\n      - EMM\n      - Enterprise\n      - Enterprise Mobility\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/android/work/play/emm-api/v1\n\
  \      - type: Getting Started\n        url: https://developers.google.com/android/work/play/emm-api/getstarted\n  - aid: google-android:play-integrity-api\n    name: Play Integrity API\n    description: The Play Integrity API helps protect your apps and games from potentially risky and fraudulent interactions by checking that interactions and server requests are coming from your genuine app binary running on a genuine Android device.\n    image: https://www.gstatic.com/devrel-devsite/prod/v2ff77c87c709f3e5e323c03865ecedf5b4afc4446d0e0e2904abf9d5/android/images/touchicon-180.png\n    humanURL: https://developer.android.com/google/play/integrity\n    baseURL: https://playintegrity.googleapis.com\n    tags:\n      - App Verification\n      - Fraud Prevention\n      - Integrity\n      - Security\n    properties:\n      - type: Documentation\n        url: https://developer.android.com/google/play/integrity/overview\n      - type: Getting Started\n        url: https://developer.android.com/google/play/integrity/standard\n\
  \  - aid: google-android:cloud-testing-api\n    name: Cloud Testing API\n    description: The Cloud Testing API powers Firebase Test Lab, enabling developers to test Android and iOS apps on real and virtual devices hosted in Google data centers, including instrumentation tests and robo tests.\n    image: https://firebase.google.com/images/social.png\n    humanURL: https://firebase.google.com/docs/test-lab\n    baseURL: https://testing.googleapis.com\n    tags:\n      - Firebase\n      - Quality Assurance\n      - Test Lab\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://firebase.google.com/docs/test-lab/reference/testing/rest/\n      - type: Getting Started\n        url: https://firebase.google.com/docs/test-lab/android/get-started\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://developers.android.com/\n  - type: Blog\n    url: https://android-developers.googleblog.com/\n  - type: GitHubOrganization\n\
  \    url: https://github.com/android\n  - type: TermsOfService\n    url: https://developers.google.com/terms\n  - type: PrivacyPolicy\n    url: https://policies.google.com/privacy\n  - type: Support\n    url: https://developer.android.com/support\n  - type: Newsletter\n    url: https://developer.android.com/newsletter\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/android\n  - type: YouTube\n    url: https://www.youtube.com/user/androiddevelopers\n  - type: Support\n    url: https://issuetracker.google.com/issues?q=componentid:192735\n  - type: Training\n    url: https://developer.android.com/courses\n  - type: StatusPage\n    url: https://status.cloud.google.com/\n  - type: Features\n    data:\n      - name: Enterprise Device Management\n        description: Remotely manage and configure Android devices with policies for enterprise mobility.\n      - name: App Publishing and Distribution\n        description: Publish and manage Android apps on Google Play\
  \ including in-app purchases and subscriptions.\n      - name: Push Notifications\n        description: Send cross-platform push notifications to Android devices via Firebase Cloud Messaging.\n      - name: Play Integrity\n        description: Verify that interactions come from genuine app binaries running on genuine Android devices.\n      - name: Zero-Touch Enrollment\n        description: Automate enterprise device provisioning and enrollment at scale.\n      - name: Cloud Testing\n        description: Test Android apps on real and virtual devices in Google data centers via Firebase Test Lab.\n      - name: Game Services\n        description: Integrate achievements, leaderboards, and multiplayer features into Android games.\n      - name: Over-the-Air Updates\n        description: Manage system updates and firmware deployments for Android device fleets.\n  - type: UseCases\n    data:\n      - name: Enterprise Mobility Management\n        description: Deploy and manage corporate Android\
  \ devices with security policies and app distribution.\n      - name: App Store Management\n        description: Automate app publishing, pricing, and subscription management on Google Play.\n      - name: User Engagement\n        description: Drive user engagement with push notifications, in-app messages, and game achievements.\n      - name: Device Fleet Management\n        description: Manage large fleets of Android devices for retail, logistics, or field operations.\n      - name: App Quality Assurance\n        description: Automate testing of Android apps across device configurations using Cloud Testing.\n  - type: Integrations\n    data:\n      - name: Firebase\n        description: Integrate with Firebase for analytics, crashlytics, authentication, and cloud messaging.\n      - name: Google Cloud\n        description: Connect Android apps to Google Cloud services for storage, ML, and compute.\n      - name: Google Play Console\n        description: Manage app releases, testing tracks,\
  \ and performance metrics through the Play Console.\n      - name: Android Studio\n        description: Develop and debug Android apps with the official IDE and its integrated tools.\n      - name: Jetpack Libraries\n        description: Use Android Jetpack libraries for architecture, UI, and behavior best practices.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-android/refs/heads/main/apis.yml
tags:
- Android
- Google
- Mobile Development
- Mobile Operating System
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/google-android/refs/heads/main/apis.yml
use_cases:
- description: Deploy and manage corporate Android devices with security policies and app distribution.
  name: Enterprise Mobility Management
- description: Automate app publishing, pricing, and subscription management on Google Play.
  name: App Store Management
- description: Drive user engagement with push notifications, in-app messages, and game achievements.
  name: User Engagement
- description: Manage large fleets of Android devices for retail, logistics, or field operations.
  name: Device Fleet Management
- description: Automate testing of Android apps across device configurations using Cloud Testing.
  name: App Quality Assurance
---
