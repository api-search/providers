---
api_count: 10
api_specs:
- filename: google-chrome-management-api-openapi.json
  format: json
  label: Chrome Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-chrome/refs/heads/main/openapi/google-chrome-management-api-openapi.json
apis:
- description: APIs for building Chrome browser extensions.
  name: Chrome Extensions API
  slug: ''
- description: Instrument, inspect, debug and profile Chromium, Chrome and other Blink-based browsers.
  name: Chrome DevTools Protocol
  slug: ''
- description: API for publishing and managing extensions in the Chrome Web Store.
  name: Chrome Web Store API
  slug: ''
- description: API for managing Chrome browser and Chrome OS devices in enterprise environments.
  name: Chrome Management API
  slug: ''
- description: Access real-world user experience data for popular websites.
  name: Chrome User Experience Report API
  slug: ''
- description: API for programmatically viewing and managing Chrome policies assigned to Organizational Units.
  name: Chrome Policy API
  slug: ''
- description: API to cryptographically verify that ChromeOS clients are genuine and conform to corporate policy.
  name: Chrome Verified Access API
  slug: ''
- description: API to check URLs against Google lists of unsafe web resources including phishing and malware sites.
  name: Google Safe Browsing API
  slug: ''
- description: API to measure web page performance and receive optimization suggestions using Lighthouse and CrUX data.
  name: PageSpeed Insights API
  slug: ''
- description: On-device AI APIs powered by Gemini Nano built into Chrome for text generation, summarization, translation, and more.
  name: Chrome Built-in AI APIs
  slug: ''
capabilities: []
common:
- title: ''
  type: DeveloperPortal
  url: https://developer.chrome.com/
- title: ''
  type: Blog
  url: https://developer.chrome.com/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/GoogleChrome
- title: ''
  type: X
  url: https://twitter.com/ChromiumDev
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/GoogleChromeDevelopers
- title: ''
  type: TermsOfService
  url: https://developers.google.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://policies.google.com/privacy
- title: ''
  type: ReleaseNotes
  url: https://developer.chrome.com/release-notes
- title: ''
  type: ChangeLog
  url: https://developer.chrome.com/new
- title: ''
  type: StatusPage
  url: https://chromestatus.com/
- title: ''
  type: Documentation
  url: https://developer.chrome.com/origintrials/
- title: ''
  type: Documentation
  url: https://developer.chrome.com/docs/web-platform/origin-trials
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/google-chrome-extension
- title: ''
  type: Portal
  url: https://chromeenterprise.google/
- title: ''
  type: Resources
  url: https://source.chromium.org/chromium
- title: ''
  type: JSONSchema
  url: json-schema/google-chrome-extension-manifest-schema.json
- title: ''
  type: JSONLD
  url: json-ld/google-chrome-context.jsonld
created: '2024'
description: Collection of APIs and resources for the Google Chrome browser and Chrome platform.
features:
- Chrome Extensions Manifest V3 platform
- Chrome DevTools Protocol for browser automation
- Chrome Web Store publishing and management APIs
- Enterprise device and policy management
- Real user experience metrics (CrUX)
- Safe Browsing URL threat detection
- PageSpeed Insights performance analysis
- Built-in AI APIs (Gemini Nano)
- Verified Access for ChromeOS device attestation
image: https://www.google.com/chrome/static/images/chrome-logo.svg
integrations:
- Google Workspace Admin
- Google Cloud
- Puppeteer
- Playwright
- Selenium
- BigQuery
- Lighthouse
- Google Search Console
jsonld:
- class_count: 7
  name: Google Chrome Context
  property_count: 19
  slug: google-chrome-context
layout: provider
modified: '2026-04-18'
name: Google Chrome
skills: []
slug: google-chrome
solutions: []
source_filename: apis.yml
source_yaml: "aid: google-chrome\nname: Google Chrome\ndescription: >-\n  Collection of APIs and resources for the Google Chrome browser and Chrome platform.\nimage: https://www.google.com/chrome/static/images/chrome-logo.svg\nurl: https://www.google.com/chrome/\ntype: Index\nspecificationVersion: '0.19'\ntags:\n  - Browser\n  - Chrome Extensions\n  - Developer Tools\n  - Web Platform\ncreated: '2024'\nmodified: '2026-04-18'\napis:\n  - name: Chrome Extensions API\n    description: >-\n      APIs for building Chrome browser extensions.\n    image: https://www.google.com/chrome/static/images/chrome-logo.svg\n    humanUrl: https://developer.chrome.com/docs/extensions/\n    baseUrl: chrome://extensions/\n    tags:\n      - Add-Ons\n      - Browser\n      - Extensions\n    properties:\n      - type: Documentation\n        url: https://developer.chrome.com/docs/extensions/reference/\n      - type: GettingStarted\n        url: https://developer.chrome.com/docs/extensions/mv3/getstarted/\n    \
  \  - type: CodeExamples\n        url: https://github.com/GoogleChrome/chrome-extensions-samples\n      - type: APIReference\n        url: https://developer.chrome.com/docs/extensions/reference/api\n      - type: APIReference\n        url: https://developer.chrome.com/docs/extensions/reference\n      - type: Documentation\n        url: https://developer.chrome.com/docs/extensions/develop/migrate\n    contact:\n      - type: Support\n        url: https://support.google.com/chrome/\n  - name: Chrome DevTools Protocol\n    description: >-\n      Instrument, inspect, debug and profile Chromium, Chrome and other Blink-based\n      browsers.\n    humanUrl: https://chromedevtools.github.io/devtools-protocol/\n    baseUrl: ws://localhost:9222/devtools/browser\n    tags:\n      - Automation\n      - Debugging\n      - DevTools\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://chromedevtools.github.io/devtools-protocol/\n      - type: APIReference\n        url:\
  \ https://chromedevtools.github.io/devtools-protocol/tot/\n      - type: GitHubRepository\n        url: https://github.com/ChromeDevTools/devtools-protocol\n      - type: Resources\n        url: https://github.com/ChromeDevTools/awesome-chrome-devtools\n    contact:\n      - type: GitHub Issues\n        url: https://github.com/ChromeDevTools/devtools-protocol/issues\n  - name: Chrome Web Store API\n    description: >-\n      API for publishing and managing extensions in the Chrome Web Store.\n    humanUrl: https://developer.chrome.com/docs/webstore/\n    baseUrl: https://www.googleapis.com/chromewebstore/v1.1/\n    tags:\n      - Distribution\n      - Publishing\n      - Web Store\n    properties:\n      - type: Documentation\n        url: https://developer.chrome.com/docs/webstore/using_webstore_api/\n      - type: APIReference\n        url: https://developer.chrome.com/docs/webstore/webstore_api/items/\n      - type: Console\n        url: https://chrome.google.com/webstore/devconsole\n\
  \      - type: Authentication\n        url: https://developer.chrome.com/docs/webstore/using_webstore_api/#beforeyoubegin\n      - type: APIReference\n        url: https://developer.chrome.com/docs/webstore/api/reference/rest\n      - type: Documentation\n        url: https://developer.chrome.com/docs/webstore/using-api\n      - type: Blog\n        url: https://developer.chrome.com/blog/cws-api-v2\n    contact:\n      - type: Support\n        url: https://support.google.com/chrome_webstore/\n  - name: Chrome Management API\n    description: >-\n      API for managing Chrome browser and Chrome OS devices in enterprise environments.\n    humanUrl: https://developers.google.com/chrome/management\n    baseUrl: https://chromemanagement.googleapis.com/\n    tags:\n      - Administration\n      - Device Management\n      - Enterprise\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/chrome/management/reference/rest\n      - type: OpenAPI\n        url: openapi/google-chrome-management-api-openapi.json\n\
  \      - type: APIReference\n        url: https://developers.google.com/chrome/management/reference/rest/v1/customers.apps\n      - type: Console\n        url: https://admin.google.com/\n      - type: Documentation\n        url: https://developers.google.com/chrome/management/guides/telemetry_api\n      - type: Documentation\n        url: https://developers.google.com/chrome/management/guides/reports_api\n      - type: CodeExamples\n        url: https://developers.google.com/chrome/management/guides/samples_telemetryapi\n      - type: CodeExamples\n        url: https://developers.google.com/chrome/management/guides/samples_reportsapi\n      - type: GitHubRepository\n        url: https://github.com/google/ChromeBrowserEnterprise\n    contact:\n      - type: Support\n        url: https://support.google.com/chrome/a/\n  - name: Chrome User Experience Report API\n    description: >-\n      Access real-world user experience data for popular websites.\n    humanUrl: https://developers.google.com/web/tools/chrome-user-experience-report\n\
  \    baseUrl: https://chromeuxreport.googleapis.com/\n    tags:\n      - Analytics\n      - Metrics\n      - Performance\n      - User Experience\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/web/tools/chrome-user-experience-report/api/reference\n      - type: APIReference\n        url: https://developers.google.com/web/tools/chrome-user-experience-report/api/reference/rest\n      - type: Documentation\n        url: https://developers.google.com/web/tools/chrome-user-experience-report/bigquery/getting-started\n      - type: Resources\n        url: https://developer.chrome.com/docs/crux/methodology/tools\n    contact:\n      - type: Support\n        url: https://support.google.com/webmasters/\n  - name: Chrome Policy API\n    description: >-\n      API for programmatically viewing and managing Chrome policies assigned to Organizational\n      Units.\n    humanUrl: https://developers.google.com/chrome/policy\n    baseUrl: https://chromepolicy.googleapis.com/\n\
  \    tags:\n      - Administration\n      - Chrome OS\n      - Enterprise\n      - Policies\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/chrome/policy\n      - type: Documentation\n        url: https://developers.google.com/chrome/policy/guides/overview\n      - type: Documentation\n        url: https://developers.google.com/chrome/policy/guides/policy-schemas\n      - type: GettingStarted\n        url: https://developers.google.com/chrome/policy/guides/setup\n      - type: CodeExamples\n        url: https://developers.google.com/chrome/policy/guides/samples\n    contact:\n      - type: Support\n        url: https://support.google.com/chrome/a/\n  - name: Chrome Verified Access API\n    description: >-\n      API to cryptographically verify that ChromeOS clients are genuine and conform\n      to corporate policy.\n    humanUrl: https://developers.google.com/chrome/verified-access\n    baseUrl: https://verifiedaccess.googleapis.com/\n    tags:\n\
  \      - Chrome OS\n      - Enterprise\n      - Security\n      - Verification\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/chrome/verified-access\n      - type: Documentation\n        url: https://developers.google.com/chrome/verified-access/developer-guide\n      - type: Documentation\n        url: https://developers.google.com/chrome/verified-access/overview\n    contact:\n      - type: Support\n        url: https://support.google.com/chrome/a/\n  - name: Google Safe Browsing API\n    description: >-\n      API to check URLs against Google lists of unsafe web resources including phishing\n      and malware sites.\n    humanUrl: https://developers.google.com/safe-browsing\n    baseUrl: https://safebrowsing.googleapis.com/\n    tags:\n      - Malware\n      - Phishing\n      - Security\n      - URL Checking\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/safe-browsing\n      - type: APIReference\n \
  \       url: https://developers.google.com/safe-browsing/reference/rest\n      - type: GettingStarted\n        url: https://developers.google.com/safe-browsing/v4/get-started\n      - type: Documentation\n        url: https://developers.google.com/safe-browsing/v4/lookup-api\n      - type: GitHubRepository\n        url: https://github.com/google/safebrowsing\n    contact:\n      - type: Support\n        url: https://safebrowsing.google.com/\n  - name: PageSpeed Insights API\n    description: >-\n      API to measure web page performance and receive optimization suggestions using\n      Lighthouse and CrUX data.\n    humanUrl: https://developers.google.com/speed/docs/insights/v5/about\n    baseUrl: https://pagespeedonline.googleapis.com/\n    tags:\n      - Analytics\n      - Lighthouse\n      - Optimization\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/speed/docs/insights/rest\n      - type: APIReference\n        url: https://developers.google.com/speed/docs/insights/v5/reference\n\
  \      - type: GettingStarted\n        url: https://developers.google.com/speed/docs/insights/v5/get-started\n    contact:\n      - type: Support\n        url: https://support.google.com/webmasters/\n  - name: Chrome Built-in AI APIs\n    description: >-\n      On-device AI APIs powered by Gemini Nano built into Chrome for text generation,\n      summarization, translation, and more.\n    humanUrl: https://developer.chrome.com/docs/ai/built-in\n    baseUrl: chrome://flags/#optimization-guide-on-device-model\n    tags:\n      - AI\n      - Gemini Nano\n      - Machine Learning\n      - On-Device AI\n    properties:\n      - type: Documentation\n        url: https://developer.chrome.com/docs/ai/built-in\n      - type: APIReference\n        url: https://developer.chrome.com/docs/ai/built-in-apis\n      - type: GettingStarted\n        url: https://developer.chrome.com/docs/ai/get-started\n      - type: Documentation\n        url: https://developer.chrome.com/docs/ai/prompt-api\n      - type:\
  \ Documentation\n        url: https://developer.chrome.com/docs/ai/summarizer-api\n      - type: Documentation\n        url: https://developer.chrome.com/docs/ai/writer-api\n      - type: Documentation\n        url: https://developer.chrome.com/docs/ai/rewriter-api\n      - type: Documentation\n        url: https://developer.chrome.com/docs/ai/language-detection\n      - type: Documentation\n        url: https://developer.chrome.com/docs/ai/proofreader-api\n    contact:\n      - type: Support\n        url: https://developer.chrome.com/docs/ai/built-in\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com/\ncommon:\n  - type: DeveloperPortal\n    url: https://developer.chrome.com/\n  - type: Blog\n    url: https://developer.chrome.com/blog/\n  - type: GitHubOrganization\n    url: https://github.com/GoogleChrome\n  - type: X\n    url: https://twitter.com/ChromiumDev\n  - type: YouTube\n    url: https://www.youtube.com/c/GoogleChromeDevelopers\n\
  \  - type: TermsOfService\n    url: https://developers.google.com/terms\n  - type: PrivacyPolicy\n    url: https://policies.google.com/privacy\n  - type: ReleaseNotes\n    url: https://developer.chrome.com/release-notes\n  - type: ChangeLog\n    url: https://developer.chrome.com/new\n  - type: StatusPage\n    url: https://chromestatus.com/\n  - type: Documentation\n    url: https://developer.chrome.com/origintrials/\n  - type: Documentation\n    url: https://developer.chrome.com/docs/web-platform/origin-trials\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/google-chrome-extension\n  - type: Portal\n    url: https://chromeenterprise.google/\n  - type: Resources\n    url: https://source.chromium.org/chromium\n  - type: JSONSchema\n    url: json-schema/google-chrome-extension-manifest-schema.json\n  - type: JSONLD\n    url: json-ld/google-chrome-context.jsonld\n  - type: Features\n    data:\n      - Chrome Extensions Manifest V3 platform\n      - Chrome DevTools\
  \ Protocol for browser automation\n      - Chrome Web Store publishing and management APIs\n      - Enterprise device and policy management\n      - Real user experience metrics (CrUX)\n      - Safe Browsing URL threat detection\n      - PageSpeed Insights performance analysis\n      - Built-in AI APIs (Gemini Nano)\n      - Verified Access for ChromeOS device attestation\n  - type: UseCases\n    data:\n      - Building and publishing Chrome browser extensions\n      - Automating browser testing and debugging\n      - Managing Chrome enterprise deployments at scale\n      - Monitoring web performance with real user metrics\n      - Protecting users from phishing and malware URLs\n      - Running on-device AI inference in the browser\n      - Enforcing Chrome policies across organizational units\n  - type: Integrations\n    data:\n      - Google Workspace Admin\n      - Google Cloud\n      - Puppeteer\n      - Playwright\n      - Selenium\n      - BigQuery\n      - Lighthouse\n      - Google\
  \ Search Console\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-chrome/refs/heads/main/apis.yml
tags:
- Browser
- Chrome Extensions
- Developer Tools
- Web Platform
url: https://www.google.com/chrome/
use_cases:
- Building and publishing Chrome browser extensions
- Automating browser testing and debugging
- Managing Chrome enterprise deployments at scale
- Monitoring web performance with real user metrics
- Protecting users from phishing and malware URLs
- Running on-device AI inference in the browser
- Enforcing Chrome policies across organizational units
---
