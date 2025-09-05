# Awesome miso [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome things regarding the Haskell [miso](https://haskell-miso.org) :ramen: ecosystem.

- [Miso](#miso)
  - [Miso General Resources](#miso-general-resources)
  <!-- - [Miso Tutorials](#miso-tutorials) -->
  <!-- - [Miso Frameworks](#miso-frameworks) -->
  - [Miso Component Libraries](#miso-component-libraries)
  - [Miso State Management and Data Fetching](#miso-state-management-and-data-fetching)
  - [Miso Styling](#miso-styling)
  - [Miso Routing](#miso-routing)
  - [Miso Development Tools](#miso-development-tools)
  <!-- - [Miso Libraries](#miso-libraries) -->
  <!-- - [Miso Testing](#miso-testing) -->
  <!-- - [Miso Awesome Components](#miso-awesome-components) -->
  <!-- - [Miso Components Sandboxes](#miso-components-sandboxes) -->
  <!-- - [Miso Forms](#miso-forms) -->
  <!-- - [Miso Tables and Grids](#miso-tables-and-grids) -->
  <!-- - [Miso Maps](#miso-maps) -->
  <!-- - [Miso Charts](#miso-charts) -->
  - [Miso Renderers](#miso-renderers)
  <!-- - [Miso Internationalization](#miso-internationalization) -->
  - [Miso Graphics and Animations](#miso-graphics-and-animations)
  <!-- - [Miso Integration](#miso-integration) -->
  - [Miso Real Apps](#miso-real-apps)
  - [Miso Games](#miso-games)
- [Miso Native](#miso-native)
  - [Miso Native General Resources](#miso-native-general-resources)
  <!-- -  - [Miso Native Navigation](#miso-native-navigation)-->
  <!-- -  - [Miso Native Awesome Components](#miso-native-awesome-components)-->
  <!-- -  - [Miso Native Libraries](#miso-native-libraries)-->
- [Contribution](#contribution)

### :ramen: Miso

#### Miso General Resources

- [Miso Official Website](https://haskell-miso.org/)
- [Miso GitHub Repo](https://github.com/dmjio/miso)
- [Miso GitHub Organization](https://github.com/haskell-miso)
- [Miso Discord Channel](https://discord.gg/QVDtfYNSxq)
- [Miso Community](https://github.com/dmjio/miso?tab=readme-ov-file#community)
<!-- - Miso Conferences -->
<!-- - Miso CodeSandbox -->

<!-- #### Miso Tutorials -->

<!-- - [React Official Tutorial](https://react.dev/learn) -->
<!-- - [Using React in Visual Studio Code](https://code.visualstudio.com/docs/nodejs/reactjs-tutorial) -->
<!-- - [React Interview Questions & Answers](https://github.com/sudheerj/reactjs-interview-questions) -->
<!-- - [Design patterns and Component patterns for building powerful Web Apps](https://www.patterns.dev/) -->
<!-- - [A simple, scalable, and powerful architecture for building production ready React applications](https://github.com/alan2207/bulletproof-react) -->
<!-- - [Cheatsheets for experienced React developers getting started with TypeScript](https://github.com/typescript-cheatsheets/react-typescript-cheatsheet) -->
<!-- - [The Fullstack Tutorial for GraphQL](https://github.com/howtographql/howtographql) -->

<!-- #### Miso Frameworks -->

<!-- - [miso](https://github.com/dmjio/miso) - The Miso Framework -->

#### Miso Component Libraries

- [miso-ui](https://github.com/haskell-miso/miso-ui) - Ready-to-use [basecoatui](https://github.com/hunvreus/basecoat) components.

#### Miso State Management and Data Fetching

- [Miso.State](https://haddocks.haskell-miso.org/miso/Miso-State.html) - Regular `MonadState` model management (`modify`, `put`, `get`, etc.).
- [Miso.Lens](https://haddocks.haskell-miso.org/miso/Miso-Lens.html) - Simple, `Lens`-based state management (`.=`, `%=`).
- [Miso.Lens.TH](https://github.com/dmjio/miso/blob/master/src/Miso/Lens/TH.hs) - Automatic deriving of `Lens` using `template-haskell` metaprogramming.
- [Miso.Fetch](https://haddocks.haskell-miso.org/miso/Miso-Fetch.html) - Easy AJAX / Fetch API support.
- [servant-client-js](https://hackage.haskell.org/package/servant-client-js) - Servant-style Fetch API support.

#### Miso Styling

- [miso-ui](https://github.com/haskell-miso/miso-ui) - Tailwind CSS ShadCN-based styling, uses [Basecoat UI](https://basecoatui.com)

#### Miso Routing

- [servant-miso-router](https://github.com/haskell-miso/servant-miso-router) - Declarative `servant`-style routing for `miso`.
- [Miso.Router](https://haddocks.haskell-miso.org/miso/Miso-Router.html) - Generics-based default router shipped with `miso`.

#### Miso Development Tools

- [jsaddle](https://hackage.haskell.org/package/jsaddle) - Hot-reload support when developing `miso` applications.
- [miso-from-html](https://github.com/haskell-miso/miso-from-html) - Convert HTML into miso `View` syntax.
- [bun](https://github.com/oven-sh/bun) - Bundler and JS runtime.

<!-- #### React Testing -->

<!-- - [jest](https://github.com/facebook/jest) - Delightful JavaScript Testing -->
<!-- - [react-testing-library](https://github.com/testing-library/react-testing-library) - Simple and complete React DOM testing utilities -->
<!-- - [cypress](https://github.com/cypress-io/cypress) - Fast, easy and reliable testing for anything that runs in a browser -->

<!-- #### React Awesome Components -->

<!-- - [Awesome React Components](https://github.com/brillout/awesome-react-components) -->
<!-- - [react-select](https://github.com/JedWatson/react-select) - The Select Component for React -->
<!-- - [react-big-calendar](https://github.com/jquense/react-big-calendar) - Calendar component -->
<!-- - [react-datepicker](https://github.com/Hacker0x01/react-datepicker/) - A simple and reusable datepicker component for React -->
<!-- - [react-loading-skeleton](https://github.com/dvtng/react-loading-skeleton) - Create skeleton screens that automatically adapt to your app -->
<!-- - [react-qrcode](https://github.com/zpao/qrcode.react) - QR component for use with React -->
<!-- - [react-archer](https://github.com/pierpo/react-archer) - Draw arrows between React elements -->
<!-- - [react-icons](https://github.com/react-icons/react-icons) - SVG React icons of popular icon packs -->
<!-- - [react-complex-tree](https://github.com/lukasbach/react-complex-tree) - Unopinionated Accessible Tree -->
<!-- - [react-insta-stories](https://github.com/mohitk05/react-insta-stories) - A React component for Instagram like stories -->
<!-- - [swiper](https://github.com/nolimits4web/swiper) - Most modern mobile touch slider -->
<!-- - [keen-slider](https://github.com/rcbyr/keen-slider) - The Touch slider carousel -->
<!-- - [cookie-consent-banner](https://github.com/porscheofficial/cookie-consent-banner) – The lightweight and flexible Cookie Consent Banner -->
<!-- - [heart-switch](https://github.com/anatoliygatt/heart-switch) - A heart-shaped toggle switch component for React -->
<!-- - [kbar](https://github.com/timc1/kbar) - Fast, portable, and extensible cmd+k interface for your site -->
<!-- - [tagify](https://github.com/yairEO/tagify) - Lightweight, efficient Tags input component -->
<!-- - [puck](https://github.com/measuredco/puck) - The visual editor for React -->

<!-- #### React Components Sandboxes -->

<!-- - [storybook](https://github.com/storybookjs/storybook) - Storybook is a frontend workshop for building UI components and pages in isolation -->
<!-- - [react-styleguidist](https://github.com/styleguidist/react-styleguidist) - Isolated React component development environment with a living style guide -->
<!-- - [react-cosmos](https://github.com/react-cosmos/react-cosmos) - Dev tool for creating reusable React components -->
<!-- - [bit](https://github.com/teambit/bit) - A build system for development of composable software -->

<!-- #### React Forms -->

<!-- - [react-hook-form](https://github.com/react-hook-form/react-hook-form) - React Hooks for form state management and validation -->
<!-- - [formik](https://github.com/jaredpalmer/formik) - Build forms in React, without the tears -->
<!-- - [react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) - A React component for building Web forms from JSON Schema -->
<!-- - [formily](https://github.com/alibaba/formily) - Alibaba Group Unified Form Solution -->
<!-- - [vest](https://github.com/ealush/vest) - Declarative validations framework -->

<!-- #### React Tables and Grids -->

<!-- - [react-grid-layout](https://github.com/react-grid-layout/react-grid-layout) - A draggable and resizable grid layout with responsive breakpoints -->
<!-- - [tanstack-table](https://github.com/TanStack/table) - Headless UI for building powerful tables & datagrids -->
<!-- - [react-data-grid](https://github.com/adazzle/react-data-grid) - Feature-rich and customizable data grid React component -->

<!-- #### React Maps -->

<!-- - [react-map-gl](https://github.com/visgl/react-map-gl) - React friendly API wrapper around MapboxGL JS -->
<!-- - [react-leaflet](https://github.com/PaulLeCam/react-leaflet) - React components for Leaflet maps -->

<!-- #### React Charts -->

<!-- - [recharts](https://github.com/recharts/recharts) - Redefined chart library built with React and D3 -->
<!-- - [visx](https://github.com/airbnb/visx) - Visualization components -->
<!-- - [victory](https://github.com/FormidableLabs/victory) - A collection of composable React components for building interactive data visualizations -->
<!-- - [react-vis](https://github.com/uber/react-vis) - Data Visualization Components -->
<!-- - [nivo](https://github.com/plouc/nivo) - Provides a rich set of data visualization components built on top of the D3 and React libraries -->
<!-- - [xyflow](https://github.com/xyflow/xyflow) - A customizable React component for building node-based editors and interactive diagrams -->

#### Miso Renderers

- [miso-lynx](https://github.com/dmjio/miso-lynx) - A Renderer for integrating with [LynxJS.org](https://lynxjs.org)

<!-- #### React Internationalization -->

<!-- - [formatjs](https://github.com/formatjs/formatjs) - Internationalize your web apps -->
<!-- - [react-i18next](https://github.com/i18next/react-i18next) - Internationalization for React done right -->

#### Miso Graphics and Animations

- [SVG](https://svg.haskell-miso.org/) - An example of using `SVG` with [miso](https://github.com/dmjio/miso)
- [Miso.Canvas](https://haddocks.haskell-miso.org/miso/Miso-Canvas.html) - A 2D Canvas library implementation.
- [three.hs](https://github.com/three-hs/three.hs) - Haskell jsaddle bindings to three.js
- [three-miso](https://threejs.haskell-miso.org) - Haskell miso integration w/ three.hs

<!-- #### React Integration -->

<!-- - [rescript-compiler](https://github.com/rescript-lang/rescript-compiler) - A robustly typed language that compiles to efficient and human-readable JavaScript -->
<!-- - [react-rails](https://github.com/reactjs/react-rails) - Integrate React with Rails -->
<!-- - [fulcro](https://github.com/fulcrologic/fulcro) - A library for development of web applications in clj/cljs -->
<!-- - [tailwind-react](https://tw-elements.com/docs/standard/integrations/react-integration/) - Article that shows you how to integrate React application with Tailwind -->

#### Real Miso Apps

- [haskell-miso.org](https://haskell-miso.org) - Haskell miso project main site.
- [Blimp Co](https://github.com/nielsbergsma/blimp_co_haskell) - Example Blimp company website
- [Miso Examples](https://github.com/haskell-miso#-index)

#### Miso Games
- [Card Game](https://github.com/smelc/miso-darkcraw)
<!-- - [kibana](https://github.com/elastic/kibana) - Your window into the Elastic Stack -->
<!-- - [webamp](https://github.com/captbaritone/webamp) - Winamp 2 reimplemented for the browser -->
<!-- - [overreacted](https://github.com/gaearon/overreacted.io) - Personal blog by Dan Abramov -->
<!-- - [wave](https://github.com/wavetermdev/waveterm) - An open-source, cross-platform terminal for seamless workflows -->

### Miso Native

#### Miso Native General Resources

- [Miso Native Official Website](https://lynxjs.haskell-miso.org)
- [Miso Native GitHub](https://github.com/haskell-miso/miso-lynx)
- [Miso Native Community](https://github.com/dmjio/miso?tab=readme-ov-file#community)
- [LynxJS](https://lynxjs.org/)

<!-- #### React Native Navigation -->

<!-- - [react-navigation](https://github.com/react-navigation/react-navigation) - Routing and navigation for your React Native apps -->

<!-- #### React Native Awesome Components -->

<!-- - [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons) - Customizable Icons for React Native -->
<!-- - [react-native-gifted-chat](https://github.com/FaridSafi/react-native-gifted-chat) - The most complete chat UI for React Native -->

<!-- #### React Native Libraries -->

<!-- - [realm-js](https://github.com/realm/realm-js) - A mobile database: an alternative to SQLite & key-value stores -->
<!-- - [react-native-device-info](https://github.com/react-native-device-info/react-native-device-info) - Device Information for React Native iOS and Android -->

### Contribution

Please feel free to add more !

[![CC0](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

