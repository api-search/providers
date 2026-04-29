---
api_count: 4
apis:
- description: 'API-Football provides real-time and historical football (soccer) data including fixtures, live scores, standings, player statistics, team information, injuries, transfers, and predictions across 900+ '
  name: API-Football
  slug: api-football
- description: API-Basketball provides real-time and historical basketball data including games, standings, player statistics, team information, and injuries across NBA, EuroLeague, and 400+ leagues worldwide.
  name: API-Basketball
  slug: api-basketball
- description: API-Baseball provides real-time and historical baseball data including games, standings, player statistics, and team information across MLB and international leagues.
  name: API-Baseball
  slug: api-baseball
- description: API-Tennis provides real-time tennis data including match results, rankings, player statistics, and tournament information across ATP, WTA, and ITF circuits.
  name: API-Tennis
  slug: api-tennis
common:
- title: ''
  type: Website
  url: https://api-sports.io/
- title: ''
  type: Documentation
  url: https://api-sports.io/documentation/
- title: ''
  type: Pricing
  url: https://api-sports.io/#pricing
- title: ''
  type: SignUp
  url: https://dashboard.api-sports.io/register
- title: ''
  type: Login
  url: https://dashboard.api-sports.io/
created: '2025-03-01'
description: API-Sports is a leading provider of real-time sports data and statistics APIs for businesses and developers. They offer 35+ APIs covering football, basketball, baseball, tennis, rugby, volleyball, handball, ice hockey, MMA, and more, with live scores, fixtures, standings, player statistics, and historical data accessible via a unified API key authentication model.
features:
- description: Comprehensive coverage spanning football, basketball, baseball, tennis, rugby, ice hockey, volleyball, handball, MMA, and more.
  name: 35+ Sports APIs
- description: Live score updates, fixture statuses, and in-play event data across all supported sports.
  name: Real-Time Live Scores
- description: Access to historical match results, player statistics, and standings going back multiple seasons.
  name: Historical Data
- description: Unified API key authentication model across all sports APIs with rate limiting by plan.
  name: API Key Authentication
- description: Upcoming and past fixtures with dates, venues, teams, and competition information.
  name: Fixtures and Schedules
- description: Comprehensive player and team performance statistics including goals, assists, ratings, and more.
  name: Player and Team Statistics
- description: All APIs available through the RapidAPI marketplace for simplified subscription management.
  name: RapidAPI Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-19'
name: API-Sports
skills: []
slug: api-sports
solutions: []
source_yaml: "aid: api-sports\nname: API-Sports\ndescription: >-\n  API-Sports is a leading provider of real-time sports data and statistics APIs\n  for businesses and developers. They offer 35+ APIs covering football, basketball,\n  baseball, tennis, rugby, volleyball, handball, ice hockey, MMA, and more, with\n  live scores, fixtures, standings, player statistics, and historical data\n  accessible via a unified API key authentication model.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Baseball\n  - Basketball\n  - Cricket\n  - Football\n  - Ice Hockey\n  - MMA\n  - Real-Time\n  - Rugby\n  - Sports Data\n  - Statistics\n  - Tennis\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/api-sports/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: api-sports:api-football\n    name: API-Football\n    description: >-\n      API-Football provides real-time and\
  \ historical football (soccer) data\n      including fixtures, live scores, standings, player statistics, team\n      information, injuries, transfers, and predictions across 900+ leagues\n      and cups worldwide.\n    humanURL: https://api-sports.io/\n    tags:\n      - Football\n      - Live Scores\n      - Soccer\n      - Sports Data\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://api-sports.io/documentation/football/v3\n  - aid: api-sports:api-basketball\n    name: API-Basketball\n    description: >-\n      API-Basketball provides real-time and historical basketball data including\n      games, standings, player statistics, team information, and injuries across\n      NBA, EuroLeague, and 400+ leagues worldwide.\n    humanURL: https://api-sports.io/\n    tags:\n      - Basketball\n      - NBA\n      - Sports Data\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://api-sports.io/documentation/basketball/v1\n\
  \  - aid: api-sports:api-baseball\n    name: API-Baseball\n    description: >-\n      API-Baseball provides real-time and historical baseball data including\n      games, standings, player statistics, and team information across MLB\n      and international leagues.\n    humanURL: https://api-sports.io/\n    tags:\n      - Baseball\n      - MLB\n      - Sports Data\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://api-sports.io/documentation/baseball/v1\n  - aid: api-sports:api-tennis\n    name: API-Tennis\n    description: >-\n      API-Tennis provides real-time tennis data including match results, rankings,\n      player statistics, and tournament information across ATP, WTA, and ITF circuits.\n    humanURL: https://api-sports.io/\n    tags:\n      - Sports Data\n      - Statistics\n      - Tennis\n    properties:\n      - type: Documentation\n        url: https://api-sports.io/documentation/tennis/v1\ncommon:\n  - type: Website\n    url: https://api-sports.io/\n\
  \  - type: Documentation\n    url: https://api-sports.io/documentation/\n  - type: Pricing\n    url: https://api-sports.io/#pricing\n  - type: SignUp\n    url: https://dashboard.api-sports.io/register\n  - type: Login\n    url: https://dashboard.api-sports.io/\n  - type: Features\n    data:\n      - name: 35+ Sports APIs\n        description: Comprehensive coverage spanning football, basketball, baseball, tennis, rugby, ice hockey, volleyball, handball, MMA, and more.\n      - name: Real-Time Live Scores\n        description: Live score updates, fixture statuses, and in-play event data across all supported sports.\n      - name: Historical Data\n        description: Access to historical match results, player statistics, and standings going back multiple seasons.\n      - name: API Key Authentication\n        description: Unified API key authentication model across all sports APIs with rate limiting by plan.\n      - name: Fixtures and Schedules\n        description: Upcoming and past fixtures\
  \ with dates, venues, teams, and competition information.\n      - name: Player and Team Statistics\n        description: Comprehensive player and team performance statistics including goals, assists, ratings, and more.\n      - name: RapidAPI Integration\n        description: All APIs available through the RapidAPI marketplace for simplified subscription management.\n  - type: UseCases\n    data:\n      - name: Sports Betting Platforms\n        description: Integrate live scores, odds data, and historical statistics to power sports betting applications.\n      - name: Fantasy Sports Apps\n        description: Build fantasy sports platforms with real-time player statistics, injury data, and performance metrics.\n      - name: Sports News Portals\n        description: Automate sports content generation with live scores, match results, and team standings.\n      - name: Sports Analytics\n        description: Conduct in-depth sports analysis using historical data, player statistics, and match\
  \ performance metrics.\n      - name: Mobile Sports Apps\n        description: Build mobile sports companion apps with live scores, notifications, and statistics dashboards.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/api-sports/refs/heads/main/apis.yml
tags:
- Baseball
- Basketball
- Cricket
- Football
- Ice Hockey
- MMA
- Real-Time
- Rugby
- Sports Data
- Statistics
- Tennis
url: https://raw.githubusercontent.com/api-evangelist/api-sports/refs/heads/main/apis.yml
use_cases:
- description: Integrate live scores, odds data, and historical statistics to power sports betting applications.
  name: Sports Betting Platforms
- description: Build fantasy sports platforms with real-time player statistics, injury data, and performance metrics.
  name: Fantasy Sports Apps
- description: Automate sports content generation with live scores, match results, and team standings.
  name: Sports News Portals
- description: Conduct in-depth sports analysis using historical data, player statistics, and match performance metrics.
  name: Sports Analytics
- description: Build mobile sports companion apps with live scores, notifications, and statistics dashboards.
  name: Mobile Sports Apps
---
