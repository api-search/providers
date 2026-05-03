---
api_count: 8
apis:
- description: 'Core Redux library for managing application state through a predictable unidirectional data flow. The library exposes createStore, combineReducers, applyMiddleware, compose, and bindActionCreators as '
  name: Redux Core API
  slug: ''
- description: Official React bindings for Redux, enabling React components to interact with a Redux store. Provides hooks (useSelector, useDispatch, useStore) and a Provider component for connecting the Redux store
  name: React Redux API
  slug: ''
- description: The official, opinionated, batteries-included toolset for efficient Redux development. Redux Toolkit simplifies common Redux use cases including store setup, creating reducers and writing immutable up
  name: Redux Toolkit API
  slug: ''
- description: Developer tools for debugging Redux applications with time-travel debugging capabilities. The Redux DevTools Extension allows inspection of every state and action payload dispatched, going back in tim
  name: Redux DevTools API
  slug: ''
- description: A Redux middleware library that aims to make application side effects such as asynchronous data fetching and accessing browser caches easier to manage and more efficient to execute. Uses ES6 Generator
  name: Redux Saga
  slug: ''
- description: RxJS-based middleware for Redux. Compose and cancel async actions to create side effects and more using Epics. An epic is a function which takes a stream of actions and returns a stream of actions.
  name: Redux Observable
  slug: ''
- description: Thunk middleware for Redux, included by default with Redux Toolkit. Allows writing action creators that return a function instead of an action object, enabling delayed dispatch and conditional dispatc
  name: Redux Thunk
  slug: ''
- description: A selector library for Redux. Selectors are functions that compute derived data from the Redux state, allowing Redux to store the minimal possible state. Reselect creates memoized selector functions t
  name: Reselect
  slug: ''
common:
- title: ''
  type: Website
  url: https://redux.js.org
- title: ''
  type: GitHubOrganization
  url: https://github.com/reduxjs
- title: ''
  type: Blog
  url: https://blog.isquaredsoftware.com/
- title: ''
  type: Community
  url: https://discord.gg/redux
- title: ''
  type: Twitter
  url: https://twitter.com/reduxjs
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/redux
- title: ''
  type: StyleGuide
  url: https://redux.js.org/style-guide/style-guide
- title: ''
  type: Faq
  url: https://redux.js.org/faq
- title: ''
  type: Tutorials
  url: https://redux.js.org/tutorials/essentials/part-1-overview-concepts
- title: ''
  type: License
  url: https://github.com/reduxjs/redux/blob/master/LICENSE.md
- title: ''
  type: JSONSchema
  url: json-schema/redux-store-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/redux-action-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/redux-store-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/redux-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/redux-vocabulary.yml
created: '2024-01-15'
description: Redux is a predictable state container for JavaScript apps. It helps write applications that behave consistently, run in different environments (client, server, and native), and are easy to test. Redux provides a single immutable state tree, pure reducer functions for state transitions, and a unidirectional data flow pattern based on the Flux architecture. The Redux ecosystem includes React Redux for React bindings, Redux Toolkit for simplified development patterns, and Redux DevTools for time-travel debugging. Redux is widely used with React but can be paired with any JavaScript view library.
features: []
image: https://redux.js.org/img/redux-logo-landscape.png
integrations: []
jsonld:
- class_count: 9
  name: Redux Context
  property_count: 11
  slug: redux-context
layout: provider
modified: '2026-05-02'
name: Redux
skills: []
slug: redux
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: redux\nname: Redux\ndescription: >-\n  Redux is a predictable state container for JavaScript apps. It helps write\n  applications that behave consistently, run in different environments (client,\n  server, and native), and are easy to test. Redux provides a single\n  immutable state tree, pure reducer functions for state transitions, and a\n  unidirectional data flow pattern based on the Flux architecture. The Redux\n  ecosystem includes React Redux for React bindings, Redux Toolkit for\n  simplified development patterns, and Redux DevTools for time-travel\n  debugging. Redux is widely used with React but can be paired with any\n  JavaScript view library.\ntype: Index\nimage: https://redux.js.org/img/redux-logo-landscape.png\nurl: https://raw.githubusercontent.com/api-evangelist/redux/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Flux Architecture\n  - Frontend\n  - Javascript\n  - Predictable State\n\
  \  - React\n  - State Management\n  - Typescript\napis:\n  - name: Redux Core API\n    description: >-\n      Core Redux library for managing application state through a predictable\n      unidirectional data flow. The library exposes createStore, combineReducers,\n      applyMiddleware, compose, and bindActionCreators as its primary API surface.\n      State mutations are triggered by dispatching plain action objects to a\n      store, which processes them through pure reducer functions to produce the\n      next immutable state tree.\n    image: https://redux.js.org/img/redux-logo-landscape.png\n    baseURL: https://redux.js.org\n    humanURL: https://redux.js.org\n    tags:\n      - Actions\n      - Middleware\n      - Reducers\n      - State Management\n      - Store\n    properties:\n      - type: Documentation\n        url: https://redux.js.org/introduction/getting-started\n      - type: ApiReference\n        url: https://redux.js.org/api/api-reference\n      - type: GitHubRepository\n\
  \        url: https://github.com/reduxjs/redux\n      - type: NpmPackage\n        url: https://www.npmjs.com/package/redux\n      - type: TypeScript\n        url: https://redux.js.org/usage/usage-with-typescript\n      - type: Changelog\n        url: https://github.com/reduxjs/redux/releases\n      - type: License\n        url: https://github.com/reduxjs/redux/blob/master/LICENSE.md\n  - name: React Redux API\n    description: >-\n      Official React bindings for Redux, enabling React components to interact\n      with a Redux store. Provides hooks (useSelector, useDispatch, useStore)\n      and a Provider component for connecting the Redux store to the React\n      component tree. React Redux ensures that components only re-render when\n      the pieces of state they subscribe to change.\n    image: https://react-redux.js.org/img/redux-logo-landscape.png\n    baseURL: https://react-redux.js.org\n    humanURL: https://react-redux.js.org\n    tags:\n      - Bindings\n      - Components\n\
  \      - Hooks\n      - React\n      - State Management\n    properties:\n      - type: Documentation\n        url: https://react-redux.js.org/introduction/getting-started\n      - type: ApiReference\n        url: https://react-redux.js.org/api/hooks\n      - type: GitHubRepository\n        url: https://github.com/reduxjs/react-redux\n      - type: NpmPackage\n        url: https://www.npmjs.com/package/react-redux\n      - type: Tutorials\n        url: https://react-redux.js.org/tutorials/quick-start\n      - type: Changelog\n        url: https://github.com/reduxjs/react-redux/releases\n  - name: Redux Toolkit API\n    description: >-\n      The official, opinionated, batteries-included toolset for efficient Redux\n      development. Redux Toolkit simplifies common Redux use cases including\n      store setup, creating reducers and writing immutable update logic, and\n      creating entire state slices at once. Includes configureStore, createSlice,\n      createAsyncThunk, createEntityAdapter,\
  \ and the RTK Query data fetching\n      and caching solution.\n    image: https://redux-toolkit.js.org/img/redux-logo-landscape.png\n    baseURL: https://redux-toolkit.js.org\n    humanURL: https://redux-toolkit.js.org\n    tags:\n      - Code Generation\n      - Immer\n      - Redux Toolkit\n      - Rtk Query\n      - Simplified Redux\n      - Toolkit\n    properties:\n      - type: Documentation\n        url: https://redux-toolkit.js.org/introduction/getting-started\n      - type: ApiReference\n        url: https://redux-toolkit.js.org/api/configureStore\n      - type: GitHubRepository\n        url: https://github.com/reduxjs/redux-toolkit\n      - type: NpmPackage\n        url: https://www.npmjs.com/package/@reduxjs/toolkit\n      - type: RtkQuery\n        url: https://redux-toolkit.js.org/rtk-query/overview\n      - type: Tutorials\n        url: https://redux-toolkit.js.org/tutorials/quick-start\n      - type: Changelog\n        url: https://github.com/reduxjs/redux-toolkit/releases\n\
  \  - name: Redux DevTools API\n    description: >-\n      Developer tools for debugging Redux applications with time-travel\n      debugging capabilities. The Redux DevTools Extension allows inspection\n      of every state and action payload dispatched, going back in time by\n      cancelling actions, and replaying state changes. Also available as\n      a standalone NPM package for programmatic integration.\n    image: https://github.com/reduxjs/redux-devtools/raw/main/extension/docs/design/logo.png\n    baseURL: https://github.com/reduxjs/redux-devtools\n    humanURL: https://github.com/reduxjs/redux-devtools\n    tags:\n      - Browser Extension\n      - Debugging\n      - Devtools\n      - Time Travel\n    properties:\n      - type: Documentation\n        url: https://github.com/reduxjs/redux-devtools/blob/main/README.md\n      - type: GitHubRepository\n        url: https://github.com/reduxjs/redux-devtools\n      - type: ChromeExtension\n        url: https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd\n\
  \      - type: FirefoxExtension\n        url: https://addons.mozilla.org/en-US/firefox/addon/reduxdevtools/\n      - type: NpmPackage\n        url: https://www.npmjs.com/package/redux-devtools\n  - name: Redux Saga\n    description: >-\n      A Redux middleware library that aims to make application side effects such\n      as asynchronous data fetching and accessing browser caches easier to manage\n      and more efficient to execute. Uses ES6 Generators to make async flows\n      easy to read, write, and test.\n    humanURL: https://redux-saga.js.org\n    baseURL: https://redux-saga.js.org\n    tags:\n      - Async\n      - Generators\n      - Middleware\n      - Side Effects\n    properties:\n      - type: Documentation\n        url: https://redux-saga.js.org/docs/introduction/GettingStarted\n      - type: GitHubRepository\n        url: https://github.com/redux-saga/redux-saga\n      - type: NpmPackage\n        url: https://www.npmjs.com/package/redux-saga\n  - name: Redux Observable\n\
  \    description: >-\n      RxJS-based middleware for Redux. Compose and cancel async actions to\n      create side effects and more using Epics. An epic is a function which\n      takes a stream of actions and returns a stream of actions.\n    humanURL: https://redux-observable.js.org\n    baseURL: https://redux-observable.js.org\n    tags:\n      - Middleware\n      - Observables\n      - Reactive\n      - Rxjs\n    properties:\n      - type: Documentation\n        url: https://redux-observable.js.org/docs/basics/Epics.html\n      - type: GitHubRepository\n        url: https://github.com/redux-observable/redux-observable\n      - type: NpmPackage\n        url: https://www.npmjs.com/package/redux-observable\n  - name: Redux Thunk\n    description: >-\n      Thunk middleware for Redux, included by default with Redux Toolkit.\n      Allows writing action creators that return a function instead of an\n      action object, enabling delayed dispatch and conditional dispatch based\n      on\
  \ current state.\n    humanURL: https://github.com/reduxjs/redux-thunk\n    baseURL: https://github.com/reduxjs/redux-thunk\n    tags:\n      - Async\n      - Middleware\n      - Thunk\n    properties:\n      - type: Documentation\n        url: https://github.com/reduxjs/redux-thunk#readme\n      - type: GitHubRepository\n        url: https://github.com/reduxjs/redux-thunk\n      - type: NpmPackage\n        url: https://www.npmjs.com/package/redux-thunk\n  - name: Reselect\n    description: >-\n      A selector library for Redux. Selectors are functions that compute\n      derived data from the Redux state, allowing Redux to store the minimal\n      possible state. Reselect creates memoized selector functions that\n      recompute only when their inputs change.\n    humanURL: https://github.com/reduxjs/reselect\n    baseURL: https://github.com/reduxjs/reselect\n    tags:\n      - Memoization\n      - Performance\n      - Selectors\n    properties:\n      - type: Documentation\n       \
  \ url: https://reselect.js.org/\n      - type: GitHubRepository\n        url: https://github.com/reduxjs/reselect\n      - type: NpmPackage\n        url: https://www.npmjs.com/package/reselect\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Website\n    url: https://redux.js.org\n  - type: GitHubOrganization\n    url: https://github.com/reduxjs\n  - type: Blog\n    url: https://blog.isquaredsoftware.com/\n  - type: Community\n    url: https://discord.gg/redux\n  - type: Twitter\n    url: https://twitter.com/reduxjs\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/redux\n  - type: StyleGuide\n    url: https://redux.js.org/style-guide/style-guide\n  - type: Faq\n    url: https://redux.js.org/faq\n  - type: Tutorials\n    url: https://redux.js.org/tutorials/essentials/part-1-overview-concepts\n  - type: License\n    url: https://github.com/reduxjs/redux/blob/master/LICENSE.md\n  - type: JSONSchema\n    url: json-schema/redux-store-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/redux-action-schema.json\n  - type: JSONStructure\n    url: json-structure/redux-store-structure.json\n  - type: JSONLDContext\n    url: json-ld/redux-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/redux-vocabulary.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/redux/refs/heads/main/apis.yml
tags:
- Flux Architecture
- Frontend
- Javascript
- Predictable State
- React
- State Management
- Typescript
url: https://raw.githubusercontent.com/api-evangelist/redux/refs/heads/main/apis.yml
use_cases: []
---
