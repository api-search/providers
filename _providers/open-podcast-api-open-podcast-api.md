---
api_count: 6
apis:
- description: Authenticate users against an Open Podcast compliant server, establishing the session used for subsequent subscription, action, and device endpoints.
  name: Open Podcast Authentication API
  slug: authentication-api
- description: Synchronize a user's podcast subscriptions across clients, including adding and removing feed URLs and retrieving the current subscription set per device.
  name: Open Podcast Subscriptions API
  slug: subscriptions-api
- description: Record and synchronize per-episode listening actions such as play, pause, download, delete, and flag, including timestamp and position metadata.
  name: Open Podcast Episode Actions API
  slug: episode-actions-api
- description: Register and manage the devices a user syncs from, allowing servers to track per-device subscription state and last-sync timestamps.
  name: Open Podcast Devices API
  slug: devices-api
- description: Synchronize a user's favorited episodes across clients so that liked or starred items remain consistent regardless of which app or device the user is on.
  name: Open Podcast Favorites API
  slug: favorites-api
- description: Synchronize the user's playback queue (up-next list) across clients, including ordering, additions, and removals of episodes.
  name: Open Podcast Queue API
  slug: queue-api
common:
- title: ''
  type: Website
  url: https://openpodcastapi.org/
- title: ''
  type: Documentation
  url: https://openpodcastapi.org/
- title: ''
  type: GitHub Organization
  url: https://github.com/openpodcastapi
- title: ''
  type: Discussions
  url: https://github.com/orgs/openpodcastapi/discussions
- title: ''
  type: Matrix Chat
  url: https://matrix.to/#/#openpodcastapi:matrix.org
created: '2025-05-02'
description: The Open Podcast API is an initiative aiming to provide a feature-complete synchronization API specification for podcast (web) apps and user-focused servers. The specification covers synchronization of subscriptions, listening progress, favorites, queues, and device state across compliant clients and self-hosted servers, with the goal of giving listeners portable control of their podcast data.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Open Podcast API
skills: []
slug: open-podcast-api-open-podcast-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: open-podcast-api-open-podcast-api\nname: Open Podcast API\ndescription: >-\n  The Open Podcast API is an initiative aiming to provide a feature-complete\n  synchronization API specification for podcast (web) apps and user-focused\n  servers. The specification covers synchronization of subscriptions, listening\n  progress, favorites, queues, and device state across compliant clients and\n  self-hosted servers, with the goal of giving listeners portable control of\n  their podcast data.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Audio\n  - Episodes\n  - Open Standards\n  - Podcasts\n  - Subscriptions\n  - Sync\ncreated: '2025-05-02'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/open-podcast-api-open-podcast-api/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: open-podcast-api-open-podcast-api:authentication-api\n\
  \    name: Open Podcast Authentication API\n    description: >-\n      Authenticate users against an Open Podcast compliant server, establishing\n      the session used for subsequent subscription, action, and device endpoints.\n    humanURL: https://openpodcastapi.org/\n    tags:\n      - Authentication\n      - Sessions\n    properties:\n      - type: Documentation\n        url: https://openpodcastapi.org/\n  - aid: open-podcast-api-open-podcast-api:subscriptions-api\n    name: Open Podcast Subscriptions API\n    description: >-\n      Synchronize a user's podcast subscriptions across clients, including adding\n      and removing feed URLs and retrieving the current subscription set per\n      device.\n    humanURL: https://openpodcastapi.org/\n    tags:\n      - Feeds\n      - Subscriptions\n      - Sync\n    properties:\n      - type: Documentation\n        url: https://openpodcastapi.org/\n  - aid: open-podcast-api-open-podcast-api:episode-actions-api\n    name: Open Podcast Episode\
  \ Actions API\n    description: >-\n      Record and synchronize per-episode listening actions such as play, pause,\n      download, delete, and flag, including timestamp and position metadata.\n    humanURL: https://openpodcastapi.org/\n    tags:\n      - Episodes\n      - Listening Progress\n      - Sync\n    properties:\n      - type: Documentation\n        url: https://openpodcastapi.org/\n  - aid: open-podcast-api-open-podcast-api:devices-api\n    name: Open Podcast Devices API\n    description: >-\n      Register and manage the devices a user syncs from, allowing servers to\n      track per-device subscription state and last-sync timestamps.\n    humanURL: https://openpodcastapi.org/\n    tags:\n      - Devices\n      - Registration\n      - Sync\n    properties:\n      - type: Documentation\n        url: https://openpodcastapi.org/\n  - aid: open-podcast-api-open-podcast-api:favorites-api\n    name: Open Podcast Favorites API\n    description: >-\n      Synchronize a user's favorited\
  \ episodes across clients so that liked or\n      starred items remain consistent regardless of which app or device the user\n      is on.\n    humanURL: https://openpodcastapi.org/\n    tags:\n      - Favorites\n      - Sync\n    properties:\n      - type: Documentation\n        url: https://openpodcastapi.org/\n  - aid: open-podcast-api-open-podcast-api:queue-api\n    name: Open Podcast Queue API\n    description: >-\n      Synchronize the user's playback queue (up-next list) across clients,\n      including ordering, additions, and removals of episodes.\n    humanURL: https://openpodcastapi.org/\n    tags:\n      - Playback\n      - Queue\n      - Sync\n    properties:\n      - type: Documentation\n        url: https://openpodcastapi.org/\ncommon:\n  - type: Website\n    url: https://openpodcastapi.org/\n  - type: Documentation\n    url: https://openpodcastapi.org/\n  - type: GitHub Organization\n    url: https://github.com/openpodcastapi\n  - type: Discussions\n    url: https://github.com/orgs/openpodcastapi/discussions\n\
  \  - type: Matrix Chat\n    url: https://matrix.to/#/#openpodcastapi:matrix.org\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/open-podcast-api-open-podcast-api/refs/heads/main/apis.yml
tags:
- Audio
- Episodes
- Open Standards
- Podcasts
- Subscriptions
- Sync
url: https://raw.githubusercontent.com/api-evangelist/open-podcast-api-open-podcast-api/refs/heads/main/apis.yml
use_cases: []
---
