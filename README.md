# awesome-graphql [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Awesome list of GraphQL

If you want to contribute to this list (please do), send me a pull request.

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- <code>197578</code> ![](https://img.shields.io/github/last-commit/sindresorhus/awesome) [awesome-graphql ![Awesome](https://github.com/sindresorhus/awesome)](#awesome-graphql-)
  - [Table of Contents](#table-of-contents)
  - [Specifications](#specifications)
  - [Foundations](#foundations)
  - [Communities](#communities)
  - [Meetups](#meetups)
  - [Implementations](#implementations)
    - [JavaScript/TypeScript](#javascripttypescript)
      - [Clients](#clients)
        - [Frontend Framework Integrations](#frontend-framework-integrations)
          - [React](#react)
      - [Servers](#servers)
        - [Databases & ORMs](#databases--orms)
        - [PubSub](#pubsub)
      - [Custom Scalars](#custom-scalars)
      - [Type](#type)
      - [Miscellaneous](#miscellaneous)
      - [JavaScript Examples](#javascript-examples)
      - [TypeScript Examples](#typescript-examples)
    - [Ruby](#ruby)
      - [Ruby Examples](#ruby-examples)
    - [PHP](#php)
      - [PHP Examples](#php-examples)
    - [Python](#python)
      - [Python Examples](#python-examples)
    - [Java](#java)
      - [Custom Scalars](#custom-scalars-1)
      - [Java Examples](#java-examples)
    - [Kotlin](#kotlin)
      - [Kotlin Examples](#kotlin-examples)
    - [C/C++](#cc)
    - [Go](#go)
      - [Go Examples](#go-examples)
    - [Scala](#scala)
      - [Scala Examples](#scala-examples)
    - [.NET](#net)
    - [Elixir](#elixir)
      - [Elixir Examples](#elixir-examples)
    - [Haskell](#haskell)
    - [SQL](#sql)
    - [Lua](#lua)
    - [Elm](#elm)
    - [Clojure](#clojure)
      - [Clojure Examples](#clojure-examples)
    - [Swift](#swift)
    - [OCaml](#ocaml)
    - [Android](#android)
      - [Android Examples](#android-examples)
    - [iOS](#ios)
      - [iOS Examples](#ios-examples)
    - [ClojureScript](#clojurescript)
    - [ReasonML](#reasonml)
    - [Dart](#dart)
    - [Rust](#rust)
      - [Rust Examples](#rust-examples)
    - [D (dlang)](#d-dlang)
    - [R (Rstat)](#r-rstat)
    - [Julia](#julia)
    - [Crystal](#crystal)
  - [Tools](#tools)
    - [Tools - Editors & IDEs & Explorers](#tools---editors--ides--explorers)
    - [Tools - Security](#tools---security)
    - [Tools - Browser Extensions](#tools---browser-extensions)
    - [Tools - Prototyping](#tools---prototyping)
    - [Tools - Docs](#tools---docs)
    - [Tools - Editor Plugins](#tools---editor-plugins)
    - [Tools - Miscellaneous](#tools---miscellaneous)
  - [Databases](#databases)
  - [Services](#services)
    - [CDN](#cdn)
    - [CMS](#cms)
  - [Books](#books)
  - [Videos](#videos)
  - [Podcasts](#podcasts)
  - [Style Guides](#style-guides)
  - [Blogs](#blogs)
    - [Blogs - Security](#blogs---security)
  - [Posts](#posts)
  - [Workshoppers](#workshoppers)
  - [License](#license)

<!-- /MarkdownTOC -->

<a name="spec" />

## Specifications

- <code>&nbsp;13706</code> ![](https://img.shields.io/github/last-commit/graphql/graphql-spec) [GraphQL](https://github.com/graphql/graphql-spec) - Working draft of the specification for GraphQL.
- <code>&nbsp;&nbsp;&nbsp;220</code> ![](https://img.shields.io/github/last-commit/graphql/graphql-over-http) [GraphQL over HTTP](https://github.com/graphql/graphql-over-http) - Working draft of "GraphQL over HTTP" specification.
- [GraphQL Relay](https://relay.dev/docs/guides/graphql-server-specification/) - Relay-compliant GraphQL server specification.
- <code>&nbsp;&nbsp;&nbsp;382</code> ![](https://img.shields.io/github/last-commit/opencrud/opencrud) [OpenCRUD](https://github.com/opencrud/opencrud) - OpenCRUD is a GraphQL CRUD API specification for databases.
- [Apollo Federation](https://www.apollographql.com/docs/federation/federation-spec/) - Apollo Federation specification

<a name="foundation" />

## Foundations

- [GraphQL Foundation](https://graphql.org/foundation/) - GraphQL Foundation under the Linux Foundation

<a name="community" />

## Communities

- [Slack](https://graphql.slack.com/messages/general/) - Share and help people on the chat. Get your invite [here](https://graphql-slack.herokuapp.com/).
- [Discord](http://join.reactiflux.com/) - Join `#help-graphql` on the Reactiflux Discord server.
- [Facebook](https://www.facebook.com/groups/795330550572866/) - Group for discussions, articles and knowledge sharing.
- [Twitter](https://twitter.com/search?q=%23GraphQL) - Use the hashtag `#graphql`.
- [StackOverflow](https://stackoverflow.com/questions/tagged/graphql) - Questions and answers. Use the tag `graphql`.
- <code>&nbsp;&nbsp;3680</code> ![](https://img.shields.io/github/last-commit/APIs-guru/graphql-apis) [GraphQL APIs](https://github.com/APIs-guru/graphql-apis) - A collective list of public GraphQL APIs.
- [/r/GraphQL](https://old.reddit.com/r/graphql/) - A Subreddit for interesting and informative GraphQL content and discussions.
- [GraphQL Jobs](https://graphql.jobs) - A list of GraphQL-based jobs in startups all over the world.
- [Codever](https://www.codever.land/search?q=graphql) - Dev bookmarks. Use the tag [graphql](https://www.codever.land/bookmarks/t/graphql).
- [Everything GraphQL - Curated by The Guild](https://discord.gg/xud7bH9) - A Discord server dedicated to GraphQL.
- [GraphQL Weekly](https://www.graphqlweekly.com/) - A weekly newsletter highlighting resources and news from the GraphQL community.
- [GraphQL Custom Scalars](https://www.graphqlscalars.com/) - Search graphql custom scalars across Javascript, Java, PHP, Go, Scala, etc....

<a name="meetup" />

## Meetups

- [Relay Meetup](https://relaymeetup.com/) - A global, online meetup on Relay, the GraphQL client.
- [Amsterdam](https://www.meetup.com/Amsterdam-GraphQL-Meetup/)
- [Bangalore](https://www.meetup.com/graphql-bangalore/)
- [Berlin](https://www.meetup.com/graphql-berlin/)
- [Buenos Aires](https://www.meetup.com/es-ES/GraphQL-BA/)
- [Copenhagen](https://www.meetup.com/Copenhagen-GraphQL-Meetup-Group/)
- [Dallas-Fort Worth](https://www.meetup.com/DFW-GraphQL-Meetup/)
- [Hamburg](https://www.meetup.com/GraphQL-Hamburg/)
- [London](https://www.meetup.com/GraphQL-London/)
- [Manchester](https://www.meetup.com/GraphQL-Manchester/)
- [Melbourne](https://www.meetup.com/GraphQL-Melbourne/)
- [Montreal](https://www.meetup.com/GraphQL-Montreal/)
- [Munich](https://www.meetup.com/GraphQL-Munich/)
- [New York City](https://www.meetup.com/GraphQL-NYC/)
- [Portland](https://www.meetup.com/GraphQLPDX/)
- [San Francisco](https://www.meetup.com/GraphQL-SF/)
- [Seattle](https://www.meetup.com/Seattle-GraphQL/)
- [Sydney](https://www.meetup.com/GraphQL-Sydney/)
- [Tel Aviv](https://www.meetup.com/GraphQL-TLV/)
- [Wrocław](https://www.meetup.com/GraphQL-Wroclaw/)
- [Singapore](https://www.meetup.com/GraphQL-SG/)
- [Zurich](https://www.meetup.com/GraphQL-Zurich/)

<a name="impl" />

## Implementations

<a name="js" />

### JavaScript/TypeScript

- <code>&nbsp;18671</code> ![](https://img.shields.io/github/last-commit/graphql/graphql-js) [graphql-js](https://github.com/graphql/graphql-js) - A reference implementation of GraphQL for JavaScript.
- <code>&nbsp;&nbsp;&nbsp;726</code> ![](https://img.shields.io/github/last-commit/zalando-incubator/graphql-jit) [graphql-jit](https://github.com/zalando-incubator/graphql-jit) - GraphQL execution using a JIT compiler.

#### Clients

- <code>&nbsp;17536</code> ![](https://img.shields.io/github/last-commit/apollographql/apollo-client) [apollo-client](https://github.com/apollographql/apollo-client) - A fully-featured, production ready caching GraphQL client for every UI framework and GraphQL server.
- <code>&nbsp;&nbsp;4478</code> ![](https://img.shields.io/github/last-commit/prisma-labs/graphql-request) [graphql-request](https://github.com/prisma-labs/graphql-request) - A minimal GraphQL client for Node and browsers.
- [typescript-graphql-request](https://graphql-code-generator.com/docs/plugins/typescript-graphql-request) - Use GraphQL Request as a fully typed SDK.
- <code>&nbsp;&nbsp;1493</code> ![](https://img.shields.io/github/last-commit/graphql-editor/graphql-zeus) [graphql-zeus](https://github.com/graphql-editor/graphql-zeus) - GraphQL Zeus creates autocomplete client library for `JavaScript` or `TypeScript` which provides autocompletion for strongly typed queries.
- <code>&nbsp;&nbsp;3074</code> ![](https://img.shields.io/github/last-commit/hasura/graphqurl) [graphqurl](https://github.com/hasura/graphqurl) - curl for GraphQL with autocomplete, subscriptions and GraphiQL. Also a dead-simple universal javascript GraphQL client.
- <code>&nbsp;&nbsp;8685</code> ![](https://img.shields.io/github/last-commit/aws-amplify/amplify-js) [aws-amplify](https://github.com/aws-amplify/amplify-js) - A client library developed by Amazon for caching, analytics and more that includes a way to fetch GraphQL queries.

##### Frontend Framework Integrations

- <code>&nbsp;&nbsp;5615</code> ![](https://img.shields.io/github/last-commit/vuejs/vue-apollo) [vue-apollo](https://github.com/vuejs/vue-apollo) - Apollo/GraphQL integration for VueJS.
- <code>&nbsp;&nbsp;1334</code> ![](https://img.shields.io/github/last-commit/kamilkisiela/apollo-angular) [apollo-angular](https://github.com/kamilkisiela/apollo-angular) - A fully-featured, production ready caching GraphQL client for Angular and every GraphQL server.
- <code>&nbsp;&nbsp;&nbsp;812</code> ![](https://img.shields.io/github/last-commit/timhall/svelte-apollo) [svelte-apollo](https://github.com/timhall/svelte-apollo) - Svelte integration for Apollo GraphQL.
- <code>&nbsp;&nbsp;&nbsp;278</code> ![](https://img.shields.io/github/last-commit/ember-graphql/ember-apollo-client) [ember-apollo-client](https://github.com/ember-graphql/ember-apollo-client) - An ember-cli addon for Apollo Client and GraphQL.
- <code>&nbsp;&nbsp;&nbsp;356</code> ![](https://img.shields.io/github/last-commit/apollo-elements/apollo-elements) [apollo-elements](https://github.com/apollo-elements/apollo-elements) - GraphQL web components that work in any frontend framework.
- <code>&nbsp;&nbsp;&nbsp;118</code> ![](https://img.shields.io/github/last-commit/jycouet/kitql) [sveltekit-kitql](https://github.com/jycouet/kitql) - A set of tools, helping you building efficient apps in a fast way with SvelteKit and GraphQL.

###### React

- [react-apollo](https://www.apollographql.com/docs/react/) - The core @apollo/client library provides built-in integration with React.
- <code>&nbsp;16852</code> ![](https://img.shields.io/github/last-commit/facebook/relay) [relay](https://github.com/facebook/relay) - Relay is a JavaScript framework for building data-driven React applications.
- <code>&nbsp;&nbsp;7057</code> ![](https://img.shields.io/github/last-commit/FormidableLabs/urql) [urql](https://github.com/FormidableLabs/urql) - A simple caching GraphQL client for React.
- <code>&nbsp;&nbsp;1674</code> ![](https://img.shields.io/github/last-commit/nearform/graphql-hooks) [graphql-hooks](https://github.com/nearform/graphql-hooks) - Minimal hooks-first GraphQL client with caching and server-side rendering support.
- <code>&nbsp;&nbsp;3579</code> ![](https://img.shields.io/github/last-commit/samdenty/gqless) [gqless](https://github.com/samdenty/gqless) - A GraphQL client without queries ✨
- <code>&nbsp;&nbsp;&nbsp;632</code> ![](https://img.shields.io/github/last-commit/mobxjs/mst-gql) [mst-gql](https://github.com/mobxjs/mst-gql) - Bindings for mobx-state-tree and GraphQL.
- <code>&nbsp;&nbsp;&nbsp;523</code> ![](https://img.shields.io/github/last-commit/arackaf/micro-graphql-react) [micro-graphql-react](https://github.com/arackaf/micro-graphql-react) - A lightweight utility for adding GraphQL to React. components. Includes simple caching and uses GET requests that could additionally be cached through a service-worker.

#### Servers

- <code>&nbsp;12496</code> ![](https://img.shields.io/github/last-commit/apollographql/apollo-server) [apollo-server](https://github.com/apollographql/apollo-server) - Spec-compliant and production ready JavaScript GraphQL server that lets you develop in a schema-first way. Built for Express, Connect, Hapi, Koa, and more.
- <code>&nbsp;&nbsp;6268</code> ![](https://img.shields.io/github/last-commit/graphql/express-graphql) [express-graphql](https://github.com/graphql/express-graphql) - GraphQL Express Middleware.
- <code>&nbsp;&nbsp;&nbsp;115</code> ![](https://img.shields.io/github/last-commit/SimonDegraeve/hapi-graphql) [hapi-graphql](https://github.com/SimonDegraeve/hapi-graphql) - Create a GraphQL HTTP server with Hapi.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/rse/hapi-plugin-graphiql) [hapi-plugin-graphiql](https://github.com/rse/hapi-plugin-graphiql) - HAPI plugin for GraphiQL integration.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> ![](https://img.shields.io/github/last-commit/jaydenseric/graphql-api-koa) [graphql-api-koa](https://github.com/jaydenseric/graphql-api-koa) - GraphQL Koa middleware that implements GraphQL.js from scratch and supports native ESM.
- <code>&nbsp;&nbsp;&nbsp;821</code> ![](https://img.shields.io/github/last-commit/chentsulin/koa-graphql) [koa-graphql](https://github.com/chentsulin/koa-graphql) - GraphQL Koa Middleware.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> ![](https://img.shields.io/github/last-commit/ryanhs/graphql-koa-scripts) [graphql-koa-scripts](https://github.com/ryanhs/graphql-koa-scripts) - GraphQL Koa 1 file simplified. usefull for quick test
- <code>&nbsp;&nbsp;&nbsp;134</code> ![](https://img.shields.io/github/last-commit/deno-libs/gql) [gql](https://github.com/deno-libs/gql) - Universal GraphQL HTTP middleware for Deno.
- <code>&nbsp;&nbsp;1632</code> ![](https://img.shields.io/github/last-commit/mercurius-js/mercurius) [mercurius](https://github.com/mercurius-js/mercurius) - GraphQL plugin for Fastify.
- <code>&nbsp;&nbsp;6768</code> ![](https://img.shields.io/github/last-commit/prisma-labs/graphql-yoga) [graphql-yoga](https://github.com/prisma-labs/graphql-yoga) - Fully-featured GraphQL Server with focus on easy setup, performance and great developer experience.
- <code>&nbsp;&nbsp;&nbsp;119</code> ![](https://img.shields.io/github/last-commit/graphitejs/server) [graphitejs](https://github.com/graphitejs/server) - Framework NodeJS for GraphQL.
- <code>&nbsp;&nbsp;&nbsp;701</code> ![](https://img.shields.io/github/last-commit/contrawork/graphql-helix) [graphql-helix](https://github.com/contrawork/graphql-helix) - A highly evolved GraphQL HTTP Server.

##### Databases & ORMs

- <code>&nbsp;&nbsp;1881</code> ![](https://img.shields.io/github/last-commit/mickhansen/graphql-sequelize) [graphql-sequelize](https://github.com/mickhansen/graphql-sequelize) - Sequelize helpers for GraphQL.
- <code>&nbsp;&nbsp;&nbsp;186</code> ![](https://img.shields.io/github/last-commit/brysgo/graphql-bookshelf) [graphql-bookshelf](https://github.com/brysgo/graphql-bookshelf) - Some help defining GraphQL schema around BookshelfJS models.
- <code>&nbsp;&nbsp;2455</code> ![](https://img.shields.io/github/last-commit/acarl005/join-monster) [join-monster](https://github.com/acarl005/join-monster) - A GraphQL-to-SQL query execution layer for batch data fetching.

##### PubSub

- [graphql-ably-pubsub](https://www.npmjs.com/package/graphql-ably-pubsub) - Ably PubSub implementation for GraphQL to publish mutation updates and subscribe to the result through a subscription query.

#### Custom Scalars

- <code>&nbsp;&nbsp;1459</code> ![](https://img.shields.io/github/last-commit/Urigo/graphql-scalars) [graphql-scalars](https://github.com/Urigo/graphql-scalars) - A library of custom GraphQL Scalars for creating precise type-safe GraphQL schemas.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> ![](https://img.shields.io/github/last-commit/rse/graphql-tools-types) [graphql-tools-types](https://github.com/rse/graphql-tools-types) - Custom GraphQL types for use with GraphQL-Tools (Void, Int, Float, String, Date, UUID, JSON).

#### Type

- <code>&nbsp;&nbsp;7145</code> ![](https://img.shields.io/github/last-commit/19majkel94/type-graphql) [type-graphql](https://github.com/19majkel94/type-graphql) - Create GraphQL schema and resolvers with TypeScript, using classes and decorators!
- <code>&nbsp;&nbsp;2907</code> ![](https://img.shields.io/github/last-commit/graphql-nexus/nexus) [graphql-nexus](https://github.com/graphql-nexus/nexus) - Code-First, Type-Safe, GraphQL Schema Construction.
- <code>&nbsp;&nbsp;8592</code> ![](https://img.shields.io/github/last-commit/dotansimha/graphql-code-generator) [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator): GraphQL code generator with flexible support for custom plugins and templates like TypeScript (frontend and backend), React Hooks, resolvers signatures and more.
- <code>&nbsp;&nbsp;&nbsp;605</code> ![](https://img.shields.io/github/last-commit/hayes/giraphql) [giraphql](https://github.com/hayes/giraphql) - A plugin based schema builder for creating code-first GraphQL schemas in TypeScript.

#### Miscellaneous

- <code>&nbsp;&nbsp;4739</code> ![](https://img.shields.io/github/last-commit/apollographql/graphql-tools) [graphql-tools](https://github.com/apollographql/graphql-tools) - Tool library for building and maintaining GraphQL-JS servers.
- <code>&nbsp;&nbsp;2094</code> ![](https://img.shields.io/github/last-commit/apollographql/graphql-tag) [graphql-tag](https://github.com/apollographql/graphql-tag) - A JavaScript template literal tag that parses GraphQL queries.
- <code>&nbsp;&nbsp;1111</code> ![](https://img.shields.io/github/last-commit/graphql-compose/graphql-compose) [graphql-compose](https://github.com/graphql-compose/graphql-compose) - Tool which allows you to construct flexible graphql schema from different data sources via plugins.
- <code>&nbsp;&nbsp;1154</code> ![](https://img.shields.io/github/last-commit/Urigo/graphql-modules) [graphql-modules](https://github.com/Urigo/graphql-modules) - Separate GraphQL server into smaller, reusable parts by modules or features.
- <code>&nbsp;&nbsp;3238</code> ![](https://img.shields.io/github/last-commit/maticzav/graphql-shield) [graphql-shield](https://github.com/maticzav/graphql-shield) - A library that helps creating a permission layer for a graphql api.
- <code>&nbsp;&nbsp;&nbsp;423</code> ![](https://img.shields.io/github/last-commit/piglovesyou/graphql-let) [graphql-let](https://github.com/piglovesyou/graphql-let) - A webpack loader to import type-protected codegen results directly from GraphQL documents
- <code>&nbsp;&nbsp;1012</code> ![](https://img.shields.io/github/last-commit/kamilkisiela/graphql-config) [graphql-config](https://github.com/kamilkisiela/graphql-config) - One configuration for all your GraphQL tools (supported by most tools, editors & IDEs).
- <code>&nbsp;&nbsp;1852</code> ![](https://img.shields.io/github/last-commit/urigo/graphql-cli) [graphql-cli](https://github.com/urigo/graphql-cli) - A command line tool for common GraphQL development workflows.
- <code>&nbsp;&nbsp;&nbsp;169</code> ![](https://img.shields.io/github/last-commit/ardatan/graphql-toolkit) [graphql-toolkit](https://github.com/ardatan/graphql-toolkit) - A set of utils for faster development of GraphQL tools (Schema and documents loading, Schema merging and more).
- <code>&nbsp;&nbsp;2360</code> ![](https://img.shields.io/github/last-commit/urigo/graphql-mesh) [graphql-mesh](https://github.com/urigo/graphql-mesh) - use GraphQL query language to access data in remote APIs that don't run GraphQL (and also ones that do run GraphQL).
- <code>&nbsp;&nbsp;&nbsp;857</code> ![](https://img.shields.io/github/last-commit/Urigo/sofa) [sofa](https://github.com/Urigo/sofa) - Generate REST API from your GraphQL API.
- <code>&nbsp;&nbsp;&nbsp;383</code> ![](https://img.shields.io/github/last-commit/aerogear/graphback) [graphback](https://github.com/aerogear/graphback) - Framework and CLI to add a GraphQLCRUD API layer to a GraphQL server using data models.
- <code>&nbsp;&nbsp;1000</code> ![](https://img.shields.io/github/last-commit/maticzav/graphql-middleware) [graphql-middleware](https://github.com/maticzav/graphql-middleware) - Split up your GraphQL resolvers in middleware functions.
- <code>&nbsp;&nbsp;1450</code> ![](https://img.shields.io/github/last-commit/graphql/graphql-relay-js) [graphql-relay-js](https://github.com/graphql/graphql-relay-js) - A library to help construct a graphql-js server supporting react-relay.
- <code>&nbsp;&nbsp;&nbsp;186</code> ![](https://img.shields.io/github/last-commit/monojack/graphql-normalizr) [graphql-normalizr](https://github.com/monojack/graphql-normalizr) - Normalize GraphQL responses for persisting in the client cache/state.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;65</code> ![](https://img.shields.io/github/last-commit/ooflorent/babel-plugin-graphql) [babel-plugin-graphql](https://github.com/ooflorent/babel-plugin-graphql) - Babel plugin that compile GraphQL tagged template strings.
- <code>&nbsp;&nbsp;1163</code> ![](https://img.shields.io/github/last-commit/apollographql/eslint-plugin-graphql) [eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) - An ESLint plugin that checks your GraphQL strings against a schema.
- <code>&nbsp;&nbsp;1057</code> ![](https://img.shields.io/github/last-commit/enisdenjo/graphql-ws) [graphql-ws](https://github.com/enisdenjo/graphql-ws) - Coherent, zero-dependency, lazy, simple, GraphQL over WebSocket Protocol compliant server and client.
- <code>&nbsp;&nbsp;&nbsp;315</code> ![](https://img.shields.io/github/last-commit/n1ru4l/graphql-live-query) [graphql-live-query](https://github.com/n1ru4l/graphql-live-query) - Realtime GraphQL Live Queries with JavaScript.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;25</code> ![](https://img.shields.io/github/last-commit/Comcast/graphvinci) [GraphVinci](https://github.com/Comcast/graphvinci) - An interactive schema visualizer for GraphQL APIs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/alexstrat/supertest-graphql) [supertest-graphql](https://github.com/alexstrat/supertest-graphql) - Extends <code>&nbsp;12014</code> ![](https://img.shields.io/github/last-commit/visionmedia/supertest) [supertest](https://github.com/visionmedia/supertest) to easily test a GraphQL endpoint

<a name="js-example" />

#### JavaScript Examples

- <code>&nbsp;21158</code> ![](https://img.shields.io/github/last-commit/kriasoft/react-starter-kit) [React Starter Kit](https://github.com/kriasoft/react-starter-kit) - front-end starter kit using React, Relay, GraphQL, and JAM stack architecture.
- <code>&nbsp;&nbsp;&nbsp;980</code> ![](https://img.shields.io/github/last-commit/graphql/swapi-graphql) [SWAPI GraphQL Wrapper](https://github.com/graphql/swapi-graphql) - A GraphQL schema and server wrapping SWAPI.
- <code>&nbsp;&nbsp;&nbsp;162</code> ![](https://img.shields.io/github/last-commit/taion/relay-todomvc) [Relay TodoMVC](https://github.com/taion/relay-todomvc) - Relay TodoMVC with routing.
- [Apollo Client documentation](https://www.apollographql.com/react/) - Documentation and example for building GraphQL apps using apollo client.
- [Apollo Server tools documentation](https://www.apollographql.com/docs/apollo-server/) - Documentation, tutorial and examples for building GraphQL server and connecting to SQL, MongoDB and REST endpoints.
- <code>&nbsp;14021</code> ![](https://img.shields.io/github/last-commit/fbsamples/f8app) [F8 App 2017](https://github.com/fbsamples/f8app) - Source code of the official F8 app of 2016, powered by React Native and other Facebook open source projects.
- <code>&nbsp;&nbsp;&nbsp;113</code> ![](https://img.shields.io/github/last-commit/katopz/react-apollo-graphql-github-example) [Apollo React example for Github GraphQL API](https://github.com/katopz/react-apollo-graphql-github-example) - Usage Examples Apollo React for Github GraphQL API with create-react-app.
- <code>&nbsp;85406</code> ![](https://img.shields.io/github/last-commit/zeit/next.js) [Next.js TypeScript and GraphQL Example](https://github.com/zeit/next.js/tree/canary/examples/with-typescript-graphql) - A type-protected GraphQL example on Next.js running [graphql-codegen](https://graphql-code-generator.com/) under the hood
- [GraphQL StackBlitz Starter](https://stackblitz.com/fork/graphql) – A live, editable demo spinning up in about 2 seconds and running in a browser.
- <code>&nbsp;&nbsp;&nbsp;724</code> ![](https://img.shields.io/github/last-commit/alan345/naperg) [NAPERG](https://github.com/alan345/naperg) - Fullstack Boilerplate GraphQL. Made with React & Prisma + authentication & roles.
- [VulcanJS](http://vulcanjs.org) - The full-stack React+GraphQL framework
- <code>&nbsp;&nbsp;2146</code> ![](https://img.shields.io/github/last-commit/sly777/ran) [RAN Toolkit](https://github.com/sly777/ran) - Production-ready toolkit/boilerplate with support for GraphQL, SSR, Hot-reload, CSS-in-JS, caching, and more.

<a name="ts-example" />

#### TypeScript Examples

- <code>&nbsp;&nbsp;3475</code> ![](https://img.shields.io/github/last-commit/kriasoft/nodejs-api-starter) [Node.js API Starter](https://github.com/kriasoft/nodejs-api-starter) - Yarn v2 based monorepo template (code-first GraphQL API, PostgreSQL, PnP, Zero-install, serverless).
- <code>&nbsp;&nbsp;&nbsp;197</code> ![](https://img.shields.io/github/last-commit/borisowsky/nextjs-apollo-ts-starter) [Next.js Apollo TypeScript Starter](https://github.com/borisowsky/nextjs-apollo-ts-starter) - Next.js starter project focused on developer experience.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;47</code> ![](https://img.shields.io/github/last-commit/cerino-ligutom/GraphQL-Starter) [GraphQL Starter](https://github.com/cerino-ligutom/GraphQL-Starter) - A boilerplate for TypeScript + Node Express + Apollo GraphQL APIs.
- [Mocked Managed Federation](https://github.com/setchy/apollo-server-3-mocked-federation) - A mocked managed federation supgraph using Apollo Server 3.x

<a name="rb" />

### Ruby

- <code>&nbsp;&nbsp;5038</code> ![](https://img.shields.io/github/last-commit/rmosolgo/graphql-ruby) [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) - Ruby implementation of Facebook's GraphQL.
- <code>&nbsp;&nbsp;1058</code> ![](https://img.shields.io/github/last-commit/github/graphql-client) [graphql-client](https://github.com/github/graphql-client) - A Ruby library for declaring, composing and executing GraphQL queries.
- <code>&nbsp;&nbsp;1279</code> ![](https://img.shields.io/github/last-commit/Shopify/graphql-batch) [graphql-batch](https://github.com/Shopify/graphql-batch) - A query batching executor for the graphql gem.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/o2web/graphql-auth) [graphql-auth](https://github.com/o2web/graphql-auth) - A JWT auth wrapper working with devise.
- <code>&nbsp;&nbsp;&nbsp;769</code> ![](https://img.shields.io/github/last-commit/ohler55/agoo) [agoo](https://github.com/ohler55/agoo) - Ruby web server that implements Facebook's GraphQL.
- <code>&nbsp;&nbsp;&nbsp;207</code> ![](https://img.shields.io/github/last-commit/contentful-labs/gqli.rb) [GQLi](https://github.com/contentful-labs/gqli.rb) - A GraphQL client and DSL. Allowing to write queries in native Ruby.

<a name="rb-example" />

#### Ruby Examples

- <code>&nbsp;&nbsp;&nbsp;222</code> ![](https://img.shields.io/github/last-commit/rmosolgo/graphql-ruby-demo) [graphql-ruby-demo](https://github.com/rmosolgo/graphql-ruby-demo) - Use graphql-ruby to expose a Rails app.
- <code>&nbsp;&nbsp;&nbsp;272</code> ![](https://img.shields.io/github/last-commit/github/github-graphql-rails-example) [github-graphql-rails-example](https://github.com/github/github-graphql-rails-example) - Example Rails app using GitHub's GraphQL API.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> ![](https://img.shields.io/github/last-commit/nethsix/relay-on-rails) [relay-on-rails](https://github.com/nethsix/relay-on-rails) - Barebones starter kit for Relay application with Rails GraphQL server.
- <code>&nbsp;&nbsp;&nbsp;139</code> ![](https://img.shields.io/github/last-commit/gauravtiwari/relay-rails-blog) [relay-rails-blog](https://github.com/gauravtiwari/relay-rails-blog) - A graphql, relay and standard rails application powered demo weblog.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/jcdavison/to_eat_app) [to_eat_app](https://github.com/jcdavison/to_eat_app) - A sample graphql/rails/relay application with a related 3-part article series.
- <code>&nbsp;&nbsp;&nbsp;769</code> ![](https://img.shields.io/github/last-commit/ohler55/agoo) [agoo-demo](https://github.com/ohler55/agoo/tree/develop/example/graphql) - Use of the Agoo server to demonstrate a simple GraphQL application.
- <code>&nbsp;&nbsp;&nbsp;261</code> ![](https://img.shields.io/github/last-commit/zauberware/rails-devise-graphql) [rails-devise-graphql](https://github.com/zauberware/rails-devise-graphql) - A rails 6 boilerplate with devise, graphql & JWT auth.

<a name="php" />

### PHP

- <code>&nbsp;&nbsp;4293</code> ![](https://img.shields.io/github/last-commit/webonyx/graphql-php) [graphql-php](https://github.com/webonyx/graphql-php) - A PHP port of GraphQL reference implementation.
- <code>&nbsp;&nbsp;&nbsp;269</code> ![](https://img.shields.io/github/last-commit/ivome/graphql-relay-php) [graphql-relay-php](https://github.com/ivome/graphql-relay-php) - Relay helpers for webonyx/graphql-php implementation of GraphQL.
- <code>&nbsp;&nbsp;2832</code> ![](https://img.shields.io/github/last-commit/nuwave/lighthouse) [lighthouse](https://github.com/nuwave/lighthouse) - A PHP package that allows to serve a GraphQL endpoint from your Laravel application.
- <code>&nbsp;&nbsp;1814</code> ![](https://img.shields.io/github/last-commit/rebing/graphql-laravel) [graphql-laravel](https://github.com/rebing/graphql-laravel) - Laravel wrapper for Facebook's GraphQL.
- <code>&nbsp;&nbsp;&nbsp;692</code> ![](https://img.shields.io/github/last-commit/overblog/GraphQLBundle) [overblog/graphql-bundle](https://github.com/overblog/GraphQLBundle) - This bundle provides tools to build a complete GraphQL server in your Symfony App. Supports react-relay.
- <code>&nbsp;&nbsp;3192</code> ![](https://img.shields.io/github/last-commit/wp-graphql/wp-graphql) [wp-graphql](https://github.com/wp-graphql/wp-graphql) - GraphQL API for WordPress.
- <code>&nbsp;&nbsp;&nbsp;450</code> ![](https://img.shields.io/github/last-commit/thecodingmachine/graphqlite) [graphqlite](https://github.com/thecodingmachine/graphqlite) - Framework agnostic library that allows you to write GraphQL server by annotating your PHP classes.
- <code>&nbsp;&nbsp;1122</code> ![](https://img.shields.io/github/last-commit/leocavalcante/siler) [siler](https://github.com/leocavalcante/siler) - Plain-old functions providing a declarative API for GraphQL servers with Subscriptions support.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> ![](https://img.shields.io/github/last-commit/dpauli/php-graphql-request-builder) [graphql-request-builder](https://github.com/dpauli/php-graphql-request-builder) - Builds request payload in GraphQL structure.

<a name="php-example" />

#### PHP Examples

- <code>&nbsp;&nbsp;1122</code> ![](https://img.shields.io/github/last-commit/leocavalcante/siler) [siler-graphgl](https://github.com/leocavalcante/siler/tree/main/examples/graphql) - An example GraphQL server written with Siler.

<a name="py" />

### Python

- <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> ![](https://img.shields.io/github/last-commit/tryolabs/graphql-parser) [graphql-parser](https://github.com/tryolabs/graphql-parser) - GraphQL parser for Python.
- <code>&nbsp;&nbsp;&nbsp;420</code> ![](https://img.shields.io/github/last-commit/graphql-python/graphql-core) [graphql-core](https://github.com/graphql-python/graphql-core) - GraphQL implementation for Python based on GraphQL.js v0.6.0 reference implementation
- <code>&nbsp;&nbsp;&nbsp;420</code> ![](https://img.shields.io/github/last-commit/graphql-python/graphql-core-next) [graphql-core-next](https://github.com/graphql-python/graphql-core-next) - Latest GraphQL implementation based on GraphQL.js v14.5.6 reference implementation
- <code>&nbsp;&nbsp;&nbsp;136</code> ![](https://img.shields.io/github/last-commit/graphql-python/graphql-relay-py) [graphql-relay-py](https://github.com/graphql-python/graphql-relay-py) - A library to help construct a graphql-py server supporting react-relay.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/tallstreet/graphql-parser-python) [graphql-parser-python](https://github.com/tallstreet/graphql-parser-python) - A python wrapper around libgraphqlparser.
- <code>&nbsp;&nbsp;7144</code> ![](https://img.shields.io/github/last-commit/graphql-python/graphene) [graphene](https://github.com/graphql-python/graphene) - A package for creating GraphQL schemas/types in a Pythonic easy way.
- <code>&nbsp;&nbsp;&nbsp;119</code> ![](https://img.shields.io/github/last-commit/graphql-python/graphene-gae) [graphene-gae](https://github.com/graphql-python/graphene-gae) - Adds GraphQL support to Google AppEngine (GAE).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> ![](https://img.shields.io/github/last-commit/GraphQL-python-archive/django-graphiql) [django-graphiql](https://github.com/GraphQL-python-archive/django-graphiql) - Integrate GraphiQL easily into your Django project.
- <code>&nbsp;&nbsp;1271</code> ![](https://img.shields.io/github/last-commit/graphql-python/flask-graphql) [flask-graphql](https://github.com/graphql-python/flask-graphql) - Adds GraphQL support to your Flask application.
- <code>&nbsp;&nbsp;&nbsp;145</code> ![](https://img.shields.io/github/last-commit/prisma/python-graphql-client) [python-graphql-client](https://github.com/prisma/python-graphql-client) - Simple GraphQL client for Python 2.7+
- [python-graphjoiner](https://github.com/healx/python-graphjoiner) - Create GraphQL APIs using joins, SQL or otherwise.
- <code>&nbsp;&nbsp;3836</code> ![](https://img.shields.io/github/last-commit/graphql-python/graphene-django) [graphene-django](https://github.com/graphql-python/graphene-django) - A Django integration for Graphene.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> ![](https://img.shields.io/github/last-commit/callsign-viper/Flask-GraphQL-Auth) [Flask-GraphQL-Auth](https://github.com/callsign-viper/Flask-GraphQL-Auth) - An authentication library for Flask inspired from flask-jwt-extended.
- <code>&nbsp;&nbsp;&nbsp;807</code> ![](https://img.shields.io/github/last-commit/dailymotion/tartiflette) [tartiflette](https://github.com/dailymotion/tartiflette) - GraphQL Implementation, SDL First, for python 3.6+ / asyncio.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;56</code> ![](https://img.shields.io/github/last-commit/dailymotion/tartiflette-aiohttp) [tartiflette-aiohttp](https://github.com/dailymotion/tartiflette-aiohttp) - Wrapper of Tartiflette to expose GraphQL API over HTTP based on aiohttp / 3.6+ / asyncio, [official tutorial available on tartiflette.io](https://tartiflette.io/docs/tutorial/getting-started).
- <code>&nbsp;&nbsp;1738</code> ![](https://img.shields.io/github/last-commit/mirumee/ariadne) [Ariadne](https://github.com/mirumee/ariadne) - library for implementing GraphQL servers using schema-first approach. Asynchronous query execution, batteries included for ASGI, WSGI and popular webframeworks, [fully documented](https://ariadnegraphql.org).
- <code>&nbsp;&nbsp;&nbsp;278</code> ![](https://img.shields.io/github/last-commit/PedroBern/django-graphql-auth) [django-graphql-auth](https://github.com/PedroBern/django-graphql-auth) - Django registration and authentication with GraphQL.
- <code>&nbsp;&nbsp;2135</code> ![](https://img.shields.io/github/last-commit/strawberry-graphql/strawberry) [strawberry](https://github.com/strawberry-graphql/strawberry) - A new GraphQL library for Python.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/jhnnsrs/turms) [turms](https://github.com/jhnnsrs/turms) - A pythonic graphql codegenerator built around graphql-core and pydantic
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/jhnnsrs/rath) [rath](https://github.com/jhnnsrs/rath) - An apollo like graphql client with async and sync interface

<a name="py-example" />

#### Python Examples

- <code>&nbsp;&nbsp;&nbsp;172</code> ![](https://img.shields.io/github/last-commit/graphql-python/swapi-graphene) [swapi-graphene](https://github.com/graphql-python/swapi-graphene) - A GraphQL schema and server using [Graphene](https://graphene-python.org).

<a name="java" />

### Java

- <code>&nbsp;&nbsp;5459</code> ![](https://img.shields.io/github/last-commit/graphql-java/graphql-java) [graphql-java](https://github.com/graphql-java/graphql-java) - GraphQL Java implementation.
- <code>&nbsp;&nbsp;2215</code> ![](https://img.shields.io/github/last-commit/Netflix/dgs-framework) [DGS Framework](https://github.com/Netflix/dgs-framework) - A GraphQL server framework for Spring Boot, developed by Netflix.
- [graphql-java-generator](https://github.com/graphql-java-generator) - A <code>&nbsp;&nbsp;&nbsp;&nbsp;60</code> ![](https://img.shields.io/github/last-commit/graphql-java-generator/graphql-maven-plugin-project) [Maven plugin](https://github.com/graphql-java-generator/graphql-maven-plugin-project) and a <code>&nbsp;&nbsp;&nbsp;&nbsp;24</code> ![](https://img.shields.io/github/last-commit/graphql-java-generator/graphql-gradle-plugin-project) [Gradle plugin](https://github.com/graphql-java-generator/graphql-gradle-plugin-project) that can generate both the **Client** and the **Server** (POJOs and utility classes). The server part is based on graphql-java, and hides all its boilerplate codes.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;37</code> ![](https://img.shields.io/github/last-commit/graphql-java/graphql-java-type-generator) [gaphql-java-type-generator](https://github.com/graphql-java/graphql-java-type-generator) - Auto-generates types for use with GraphQL Java
- <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> ![](https://img.shields.io/github/last-commit/bpatters/schemagen-graphql) [schemagen-graphql](https://github.com/bpatters/schemagen-graphql) - Schema generation and execution package that turns POJO's into a GraphQL Java queryable set of objects. Enables exposing any service as a GraphQL service using Annotations.
- <code>&nbsp;&nbsp;&nbsp;359</code> ![](https://img.shields.io/github/last-commit/Enigmatis/graphql-java-annotations) [graphql-java-annotations](https://github.com/Enigmatis/graphql-java-annotations) - Provides annotations-based syntax for schema definition with GraphQL Java.
- <code>&nbsp;&nbsp;&nbsp;757</code> ![](https://img.shields.io/github/last-commit/graphql-java-kickstart/graphql-java-tools) [graphql-java-tools](https://github.com/graphql-java-kickstart/graphql-java-tools) - Schema-first graphql-java convenience library that makes it easy to bring your own implementations as data resolvers. Inspired by <code>&nbsp;&nbsp;4739</code> ![](https://img.shields.io/github/last-commit/apollographql/graphql-tools) [graphql-tools](https://github.com/apollographql/graphql-tools) for JS.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/kobylynskyi/graphql-java-codegen-maven-plugin) [graphql-java-codegen-maven-plugin](https://github.com/kobylynskyi/graphql-java-codegen-maven-plugin) - Schema-first maven plugin for generating Java types and Resolver interfaces. Works perfectly in conjunction with graphql-java-tools. Inspired by <code>&nbsp;14289</code> ![](https://img.shields.io/github/last-commit/swagger-api/swagger-codegen) [swagger-codegen-maven-plugin](https://github.com/swagger-api/swagger-codegen/tree/master/modules/swagger-codegen-maven-plugin).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/kobylynskyi/graphql-java-codegen-gradle-plugin) [graphql-java-codegen-gradle-plugin](https://github.com/kobylynskyi/graphql-java-codegen-gradle-plugin) - Schema-first gradle plugin for generating Java types and Resolver interfaces. Works perfectly in conjunction with graphql-java-tools. Inspired by <code>&nbsp;&nbsp;&nbsp;244</code> ![](https://img.shields.io/github/last-commit/int128/gradle-swagger-generator-plugin) [gradle-swagger-generator-plugin](https://github.com/int128/gradle-swagger-generator-plugin).
- <code>&nbsp;&nbsp;&nbsp;194</code> ![](https://img.shields.io/github/last-commit/graphql-java-kickstart/graphql-java-servlet) [graphql-java-servlet](https://github.com/graphql-java-kickstart/graphql-java-servlet) - A framework-agnostic java servlet for exposing graphql-java query endpoints with GET, POST, and multipart uploads.
- <code>&nbsp;&nbsp;1244</code> ![](https://img.shields.io/github/last-commit/manifold-systems/manifold) [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql) - Comprehensive GraphQL client use. Schema-first. Type-safe GraphQL types, queries, and results, no code generators, no POJOs, no annotations. Excellent [IDE support](http://manifold.systems/images/graphql.mp4) with IntelliJ IDEA and Android Studio. See the [Java example](#example-java) below.
- <code>&nbsp;&nbsp;&nbsp;131</code> ![](https://img.shields.io/github/last-commit/oembedler/spring-graphql-common) [spring-graphql-common](https://github.com/oembedler/spring-graphql-common) - Spring Framework GraphQL Library.
- <code>&nbsp;&nbsp;1361</code> ![](https://img.shields.io/github/last-commit/graphql-java-kickstart/graphql-spring-boot) [graphql-spring-boot](https://github.com/graphql-java-kickstart/graphql-spring-boot) - GraphQL and GraphiQL Spring Framework Boot Starters.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> ![](https://img.shields.io/github/last-commit/engagingspaces/vertx-graphql-service-discovery) [vertx-graphql-service-discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) - Asynchronous GraphQL service discovery and querying for your microservices.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> ![](https://img.shields.io/github/last-commit/engagingspaces/vertx-dataloader) [vertx-dataloader](https://github.com/engagingspaces/vertx-dataloader) - Port of Facebook DataLoader for efficient, asynchronous batching and caching in clustered GraphQL environments.
- <code>&nbsp;&nbsp;&nbsp;962</code> ![](https://img.shields.io/github/last-commit/leangen/GraphQL-SPQR) [graphql-spqr](https://github.com/leangen/GraphQL-SPQR) - Java 8+ API for rapid development of GraphQL services.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> ![](https://img.shields.io/github/last-commit/networknt/light-graphql-4j) [Light Java GraphQL](https://github.com/networknt/light-graphql-4j): A lightweight, fast microservices framework with all cross-cutting concerns addressed and ready to plug in GraphQL schema.
- [Elide](https://elide.io): A Java library that can expose a JPA annotated data model as a GraphQL service over any relational database.
- <code>&nbsp;&nbsp;&nbsp;156</code> ![](https://img.shields.io/github/last-commit/apollographql/federation-jvm) [federation-jvm](https://github.com/apollographql/federation-jvm) - Apollo Federation on the JVM.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;75</code> ![](https://img.shields.io/github/last-commit/graphql-java/graphql-java-extended-validation) [graphql-java-extended-validation](https://github.com/graphql-java/graphql-java-extended-validation) - Provides extended validation of fields and field arguments for graphql-java.

#### Custom Scalars

- <code>&nbsp;&nbsp;&nbsp;108</code> ![](https://img.shields.io/github/last-commit/donbeave/graphql-java-datetime) [graphql-java-datetime](https://github.com/donbeave/graphql-java-datetime) - GraphQL ISO Date is a set of RFC 3339 compliant date/time scalar types to be used with graphql-java.
- <code>&nbsp;&nbsp;&nbsp;145</code> ![](https://img.shields.io/github/last-commit/graphql-java/graphql-java-extended-scalars) [graphql-java-extended-scalars](https://github.com/graphql-java/graphql-java-extended-scalars) - Extended scalars for graphql-java.

<a name="java-example" />

#### Java Examples

- <code>&nbsp;&nbsp;&nbsp;142</code> ![](https://img.shields.io/github/last-commit/networknt/light-example-4j) [light-java-graphql examples](https://github.com/networknt/light-example-4j/tree/master/graphql) - Examples of Light Java GraphQL and tutorials.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;99</code> ![](https://img.shields.io/github/last-commit/leangen/graphql-spqr-samples) [graphql-spqr-samples](https://github.com/leangen/graphql-spqr-samples) - An example GraphQL server written with Spring MVC and GraphQL-SPQR.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;15</code> ![](https://img.shields.io/github/last-commit/manifold-systems/manifold-sample-graphql-app) [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-graphql-app) - A simple application, both client and server, demonstrating the Manifold GraphQL library.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;77</code> ![](https://img.shields.io/github/last-commit/graphql-java-kickstart/samples) [graphql-java-kickstart_samples](https://github.com/graphql-java-kickstart/samples) - Samples for using the GraphQL Java Kickstart projects.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/setchy/spring-boot-federation-example) [spring-boot-federation-example](https://github.com/setchy/spring-boot-federation-example) - A GraphQL Java Kickstart federation example.

<a name="kotlin" />

### Kotlin

- <code>&nbsp;&nbsp;1420</code> ![](https://img.shields.io/github/last-commit/ExpediaGroup/graphql-kotlin) [graphql-kotlin](https://github.com/ExpediaGroup/graphql-kotlin) - GraphQL Kotlin implementation.
- <code>&nbsp;&nbsp;1244</code> ![](https://img.shields.io/github/last-commit/manifold-systems/manifold) [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql) - Comprehensive GraphQL client use. Schema-first. Type-safe GraphQL types, queries, and results, no code generators, no POJOs, no annotations. Excellent [IDE support](http://manifold.systems/images/graphql.mp4) with IntelliJ IDEA and Android Studio. See the [Kotlin example](#example-kotlin) below.
- <code>&nbsp;&nbsp;&nbsp;228</code> ![](https://img.shields.io/github/last-commit/aPureBase/KGraphQL) [KGraphQL](https://github.com/aPureBase/KGraphQL): Pure Kotlin implementation to setup a GraphQL server.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;39</code> ![](https://img.shields.io/github/last-commit/ermadmi78/kobby) [Kobby](https://github.com/ermadmi78/kobby) - Codegen plugin of [Kotlin DSL Client](https://blog.kotlin-academy.com/how-to-generate-kotlin-dsl-client-by-graphql-schema-707fd0c55284) by GraphQL schema. The generated DSL supports execution of complex GraphQL queries, mutation and subscriptions in Kotlin with syntax similar to native GraphQL syntax.

<a name="kotlin-example" />

#### Kotlin Examples

- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/manifold-systems/manifold-sample-kotlin-app) [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-kotlin-app) - A simple GraphQL application, both client and server, demonstrating the Manifold GraphQL library with Kotlin.

<a name="c" />

### C/C++

- <code>&nbsp;&nbsp;&nbsp;960</code> ![](https://img.shields.io/github/last-commit/graphql/libgraphqlparser) [libgraphqlparser](https://github.com/graphql/libgraphqlparser) - A GraphQL query parser in C++ with C and C++ APIs.
- <code>&nbsp;&nbsp;&nbsp;135</code> ![](https://img.shields.io/github/last-commit/ohler55/agoo-c) [agoo-c](https://github.com/ohler55/agoo-c) - A high performance GraphQL server written in C. <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> ![](https://img.shields.io/github/last-commit/the-benchmarker/graphql-benchmarks) [benchmarks](https://github.com/the-benchmarker/graphql-benchmarks)
- <code>&nbsp;&nbsp;&nbsp;234</code> ![](https://img.shields.io/github/last-commit/Microsoft/cppgraphqlgen) [cppgraphqlgen](https://github.com/Microsoft/cppgraphqlgen) - C++ GraphQL schema service generator.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/caffeinetv/CaffQL) [CaffQL](https://github.com/caffeinetv/CaffQL) - Generates C++ client types and request/response serialization from a GraphQL introspection query.

<a name="go" />

### Go

- <code>&nbsp;&nbsp;8434</code> ![](https://img.shields.io/github/last-commit/graphql-go/graphql) [graphql](https://github.com/graphql-go/graphql) - An implementation of GraphQL for Go follows graphql-js
- <code>&nbsp;&nbsp;4105</code> ![](https://img.shields.io/github/last-commit/graph-gophers/graphql-go) [graphql-go](https://github.com/graph-gophers/graphql-go) - GraphQL server with a focus on ease of use.
- <code>&nbsp;&nbsp;7391</code> ![](https://img.shields.io/github/last-commit/99designs/gqlgen) [gqlgen](https://github.com/99designs/gqlgen) - Go generate based graphql server library.
- <code>&nbsp;&nbsp;&nbsp;392</code> ![](https://img.shields.io/github/last-commit/graphql-go/relay) [graphql-relay-go](https://github.com/graphql-go/relay) - A Go/Golang library to help construct a server supporting react-relay.
- <code>&nbsp;&nbsp;1975</code> ![](https://img.shields.io/github/last-commit/dosco/graphjin) [graphjin](https://github.com/dosco/graphjin): Build APIs in 5 minutes with GraphQL. An instant GraphQL to SQL compiler.

<a name="go-example" />

#### Go Examples

- <code>&nbsp;&nbsp;&nbsp;133</code> ![](https://img.shields.io/github/last-commit/sogko/golang-relay-starter-kit) [golang-relay-starter-kit](https://github.com/sogko/golang-relay-starter-kit) - Barebones starting point for a Relay application with Golang GraphQL server.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;64</code> ![](https://img.shields.io/github/last-commit/sogko/todomvc-relay-go) [todomvc-relay-go](https://github.com/sogko/todomvc-relay-go) - Port of the React/Relay TodoMVC app, driven by a Golang GraphQL backend.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;26</code> ![](https://img.shields.io/github/last-commit/ccamel/go-graphql-subscription-example) [go-graphql-subscription-example](https://github.com/ccamel/go-graphql-subscription-example) - A GraphQL schema and server that demonstrates GraphQL <code>&nbsp;&nbsp;1514</code> ![](https://img.shields.io/github/last-commit/apollographql/subscriptions-transport-ws) [subscriptions](https://github.com/apollographql/subscriptions-transport-ws/blob/v0.9.4/PROTOCOL.md) (over Websocket) to consume [Apache Kafka](https://kafka.apache.org/) messages.

<a name="scala" />

### Scala

- <code>&nbsp;&nbsp;1885</code> ![](https://img.shields.io/github/last-commit/sangria-graphql/sangria) [sangria](https://github.com/sangria-graphql/sangria) - Scala GraphQL server implementation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;90</code> ![](https://img.shields.io/github/last-commit/sangria-graphql/sangria-relay) [sangria-relay](https://github.com/sangria-graphql/sangria-relay) - Sangria Relay Support.
- <code>&nbsp;&nbsp;&nbsp;764</code> ![](https://img.shields.io/github/last-commit/ghostdogpr/caliban) [caliban](https://github.com/ghostdogpr/caliban) - Caliban is a purely functional library for creating GraphQL backends in Scala.

<a name="scala-example" />

#### Scala Examples

- <code>&nbsp;&nbsp;&nbsp;245</code> ![](https://img.shields.io/github/last-commit/sangria-graphql/sangria-akka-http-example) [sangria-akka-http-example](https://github.com/sangria-graphql/sangria-akka-http-example) - An example GraphQL server written with akka-http and [sangria](https://sangria-graphql.github.io/)
- <code>&nbsp;&nbsp;&nbsp;&nbsp;84</code> ![](https://img.shields.io/github/last-commit/sangria-graphql/sangria-playground) [sangria-playground](https://github.com/sangria-graphql/sangria-playground) - An example of GraphQL server written with Play and sangria.

<a name="dotnet" />

### .NET

- <code>&nbsp;&nbsp;5162</code> ![](https://img.shields.io/github/last-commit/graphql-dotnet/graphql-dotnet) [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) - GraphQL for .NET.
- <code>&nbsp;&nbsp;&nbsp;882</code> ![](https://img.shields.io/github/last-commit/ckimes89/graphql-net) [graphql-net](https://github.com/ckimes89/graphql-net) - GraphQL to IQueryable for .NET.
- <code>&nbsp;&nbsp;3359</code> ![](https://img.shields.io/github/last-commit/ChilliCream/hotchocolate) [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) - GraphQL server for .Net Core and .NET Framework.
- <code>&nbsp;&nbsp;&nbsp;136</code> ![](https://img.shields.io/github/last-commit/Zaid-Ajaj/Snowflaqe) [Snowflaqe](https://github.com/Zaid-Ajaj/Snowflaqe) - Type-safe GraphQL code generator for F# and <code>&nbsp;&nbsp;2371</code> ![](https://img.shields.io/github/last-commit/fable-compiler/Fable) [Fable](https://github.com/fable-compiler/Fable)

<a name="elixir" />

### Elixir

- <code>&nbsp;&nbsp;3923</code> ![](https://img.shields.io/github/last-commit/absinthe-graphql/absinthe) [absinthe-graphql](https://github.com/absinthe-graphql/absinthe) - Fully Featured Elixir GraphQL Library.
- <code>&nbsp;&nbsp;&nbsp;860</code> ![](https://img.shields.io/github/last-commit/graphql-elixir/graphql) [graphql-elixir](https://github.com/graphql-elixir/graphql) - GraphQL Elixir. (No longer maintained)
- <code>&nbsp;&nbsp;&nbsp;127</code> ![](https://img.shields.io/github/last-commit/graphql-elixir/plug_graphql) [plug_graphql](https://github.com/graphql-elixir/plug_graphql) - Plug integration for GraphQL Elixir.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;35</code> ![](https://img.shields.io/github/last-commit/graphql-elixir/graphql_relay) [graphql_relay](https://github.com/graphql-elixir/graphql_relay) - Relay helpers for GraphQL Elixir.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/graphql-elixir/graphql_parser) [graphql_parser](https://github.com/graphql-elixir/graphql_parser) - Elixir bindings for <code>&nbsp;&nbsp;&nbsp;960</code> ![](https://img.shields.io/github/last-commit/graphql/libgraphqlparser) [libgraphqlparser](https://github.com/graphql/libgraphqlparser)
- <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> ![](https://img.shields.io/github/last-commit/asonge/graphql) [graphql](https://github.com/asonge/graphql) - Elixir GraphQL parser.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;29</code> ![](https://img.shields.io/github/last-commit/peburrows/plot) [plot](https://github.com/peburrows/plot) - GraphQL parser and resolver for Elixir.

<a name="elixir-example" />

#### Elixir Examples

- <code>&nbsp;&nbsp;&nbsp;100</code> ![](https://img.shields.io/github/last-commit/graphql-elixir/hello_graphql_phoenix) [hello_graphql_phoenix](https://github.com/graphql-elixir/hello_graphql_phoenix) - Examples of GraphQL Elixir Plug endpoints mounted in Phoenix - [View demo online](http://playground.graphql-elixir.org).

<a name="haskell" />

### Haskell

- <code>&nbsp;&nbsp;&nbsp;166</code> ![](https://img.shields.io/github/last-commit/jdnavarro/graphql-haskell) [graphql-haskell](https://github.com/jdnavarro/graphql-haskell) - GraphQL AST and parser for Haskell.

<a name="sql" />

### SQL

- <code>&nbsp;&nbsp;1085</code> ![](https://img.shields.io/github/last-commit/solidsnack/GraphpostgresQL) [GraphpostgresQL](https://github.com/solidsnack/GraphpostgresQL) - GraphQL for Postgres.
- <code>&nbsp;&nbsp;&nbsp;579</code> ![](https://img.shields.io/github/last-commit/rexxars/sql-to-graphql) [sql-to-graphql](https://github.com/rexxars/sql-to-graphql) - Generate a GraphQL API based on your SQL database structure.
- <code>&nbsp;11244</code> ![](https://img.shields.io/github/last-commit/graphile/postgraphile) [PostGraphile](https://github.com/graphile/postgraphile) - Lightning-fast GraphQL APIs for PostgreSQL: highly customisable; extensible via plugins; realtime.
- <code>&nbsp;26463</code> ![](https://img.shields.io/github/last-commit/hasura/graphql-engine) [Hasura](https://github.com/hasura/graphql-engine) - Hasura gives Instant Realtime GraphQL APIs over PostgreSQL. Works with an existing database too.
- [subZero](https://subzero.cloud/) - GraphQL & REST API for your database

<a name="lua" />

### Lua

- <code>&nbsp;&nbsp;&nbsp;167</code> ![](https://img.shields.io/github/last-commit/bjornbytes/graphql-lua) [graphql-lua](https://github.com/bjornbytes/graphql-lua) - GraphQL for Lua.

<a name="elm" />

### Elm

- <code>&nbsp;&nbsp;&nbsp;728</code> ![](https://img.shields.io/github/last-commit/dillonkearns/elm-graphql) [elm-graphql](https://github.com/dillonkearns/elm-graphql) - GraphQL for Elm.

<a name="clojure" />

### Clojure

- <code>&nbsp;&nbsp;&nbsp;281</code> ![](https://img.shields.io/github/last-commit/tendant/graphql-clj) [graphql-clj](https://github.com/tendant/graphql-clj) - A Clojure library designed to provide GraphQL implementation.
- <code>&nbsp;&nbsp;1679</code> ![](https://img.shields.io/github/last-commit/walmartlabs/lacinia) [Lacinia](https://github.com/walmartlabs/lacinia) - GraphQL implementation in pure Clojure.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> ![](https://img.shields.io/github/last-commit/district0x/graphql-query) [graphql-query](https://github.com/district0x/graphql-query) - Clojure(Script) GraphQL query generation.

<a name="clojure-example" />

#### Clojure Examples

- <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> ![](https://img.shields.io/github/last-commit/walmartlabs/clojure-game-geek) [Clojure Game Geek](https://github.com/walmartlabs/clojure-game-geek) - Example code for the Lacinia GraphQL framework tutorial.

<a name="swift" />

### Swift

- <code>&nbsp;&nbsp;&nbsp;862</code> ![](https://img.shields.io/github/last-commit/GraphQLSwift/GraphQL) [GraphQL](https://github.com/GraphQLSwift/GraphQL) - The Swift implementation for GraphQL.

<a name="ocaml" />

### OCaml

- <code>&nbsp;&nbsp;&nbsp;606</code> ![](https://img.shields.io/github/last-commit/andreas/ocaml-graphql-server) [ocaml-graphql-server](https://github.com/andreas/ocaml-graphql-server) - GraphQL servers in OCaml.

<a name="android" />

### Android

- <code>&nbsp;&nbsp;3094</code> ![](https://img.shields.io/github/last-commit/apollographql/apollo-android) [apollo-android](https://github.com/apollographql/apollo-android) - 📟 A strongly-typed, caching GraphQL client for Android, written in Java.
- <code>&nbsp;&nbsp;1244</code> ![](https://img.shields.io/github/last-commit/manifold-systems/manifold) [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql) - Comprehensive GraphQL client use. Schema-first. Type-safe GraphQL types, queries, and results, no code generators, no POJOs, no annotations. Excellent [IDE support](http://manifold.systems/images/graphql.mp4) with IntelliJ IDEA and Android Studio. See the [Java example](#example-java) below.

<a name="android-example" />

#### Android Examples

- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code> ![](https://img.shields.io/github/last-commit/rnitame/apollo-frontpage-android-app) [apollo-frontpage-android-app](https://github.com/rnitame/apollo-frontpage-android-app) - 📄 Apollo "hello world" app, for Android.

<a name="ios" />

### iOS

- <code>&nbsp;&nbsp;3313</code> ![](https://img.shields.io/github/last-commit/apollographql/apollo-ios) [apollo-ios](https://github.com/apollographql/apollo-ios) - 📱 A strongly-typed, caching GraphQL client for iOS, written in Swift.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;57</code> ![](https://img.shields.io/github/last-commit/manicmaniac/ApolloDeveloperKit) [ApolloDeveloperKit](https://github.com/manicmaniac/ApolloDeveloperKit) - Apollo Client Devtools bridge for [Apollo iOS].
- <code>&nbsp;&nbsp;&nbsp;438</code> ![](https://img.shields.io/github/last-commit/nerdsupremacist/Graphaello) [Graphaello](https://github.com/nerdsupremacist/Graphaello) - Type Safe GraphQL directly from SwiftUI.

<a name="ios-example" />

#### iOS Examples

- <code>&nbsp;&nbsp;&nbsp;100</code> ![](https://img.shields.io/github/last-commit/apollographql/frontpage-ios-app) [frontpage-ios-app](https://github.com/apollographql/frontpage-ios-app) - 📄 Apollo "hello world" app, for iOS.

<a name="clojurescript" />

### ClojureScript

- <code>&nbsp;&nbsp;&nbsp;410</code> ![](https://img.shields.io/github/last-commit/oliyh/re-graph) [re-graph](https://github.com/oliyh/re-graph) - A GraphQL client for ClojureScript with bindings for re-frame applications.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> ![](https://img.shields.io/github/last-commit/district0x/graphql-query) [graphql-query](https://github.com/district0x/graphql-query) - Clojure(Script) GraphQL query generation.

<a name="reasonml" />

### ReasonML

- <code>&nbsp;&nbsp;&nbsp;559</code> ![](https://img.shields.io/github/last-commit/apollographql/reason-apollo) [reason-apollo](https://github.com/apollographql/reason-apollo) - ReasonML binding for Apollo Client.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;97</code> ![](https://img.shields.io/github/last-commit/sainthkh/reasonql) [ReasonQL](https://github.com/sainthkh/reasonql) - Type-safe and simple GraphQL Client for ReasonML developers.
- <code>&nbsp;&nbsp;&nbsp;229</code> ![](https://img.shields.io/github/last-commit/FormidableLabs/reason-urql) [reason-urql](https://github.com/FormidableLabs/reason-urql) - ReasonML binding for urql Client.

<a name="dart" />

### Dart

- <code>&nbsp;&nbsp;2919</code> ![](https://img.shields.io/github/last-commit/zino-app/graphql-flutter) [graphql-flutter](https://github.com/zino-app/graphql-flutter) - A GraphQL client for Flutter.
- <code>&nbsp;&nbsp;&nbsp;438</code> ![](https://img.shields.io/github/last-commit/comigor/artemis) [Artemis](https://github.com/comigor/artemis) - A GraphQL type and query generator for Dart/Flutter.

<a name="rust" />

### Rust

- <code>&nbsp;&nbsp;2177</code> ![](https://img.shields.io/github/last-commit/async-graphql/async-graphql) [async-graphql](https://github.com/async-graphql/async-graphql) - High-performance server-side library that supports all GraphQL specifications.
- <code>&nbsp;&nbsp;4448</code> ![](https://img.shields.io/github/last-commit/graphql-rust/juniper) [juniper](https://github.com/graphql-rust/juniper) - GraphQL server library for Rust.
- <code>&nbsp;&nbsp;&nbsp;796</code> ![](https://img.shields.io/github/last-commit/tomhoule/graphql-client) [graphql-client](https://github.com/tomhoule/graphql-client) - GraphQL client library for Rust with WebAssembly (wasm) support.
- <code>&nbsp;&nbsp;&nbsp;261</code> ![](https://img.shields.io/github/last-commit/graphql-rust/graphql-parser) [graphql-parser](https://github.com/graphql-rust/graphql-parser) - A parser, formatter and AST for the GraphQL query and schema definition language for Rust.

<a name="rust-example" />

#### Rust Examples

- <code>&nbsp;&nbsp;4448</code> ![](https://img.shields.io/github/last-commit/graphql-rust/juniper) [Warp GraphQL Juniper Demo](https://github.com/graphql-rust/juniper/tree/master/examples/warp_async)

<a name="d" />

### D (dlang)

- <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/burner/graphqld) [graphqld](https://github.com/burner/graphqld) - GraphQL server library for D.

<a name="r" />

### R (Rstat)

- <code>&nbsp;&nbsp;&nbsp;126</code> ![](https://img.shields.io/github/last-commit/ropensci/ghql) [ghql](https://github.com/ropensci/ghql) - General purpose GraphQL R client.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;33</code> ![](https://img.shields.io/github/last-commit/ropensci/graphql) [graphql](https://github.com/ropensci/graphql) - Bindings to the 'libgraphqlparser' C++ library. Parses GraphQL syntax and exports the AST in JSON format.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;56</code> ![](https://img.shields.io/github/last-commit/schloerke/gqlr) [gqlr](https://github.com/schloerke/gqlr) - R GraphQL Implementation.

<a name="julia" />

### Julia

- <code>&nbsp;&nbsp;&nbsp;102</code> ![](https://img.shields.io/github/last-commit/codeneomatrix/Diana.jl) [Diana.jl](https://github.com/codeneomatrix/Diana.jl) - A Julia GraphQL client/server implementation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;23</code> ![](https://img.shields.io/github/last-commit/DeloitteDigitalAPAC/GraphQLClient.jl) [GraphQLClient.jl](https://github.com/DeloitteDigitalAPAC/GraphQLClient.jl) - A Julia GraphQL client for seamless integration with a server.

<a name="crystal" />

### Crystal

- <code>&nbsp;&nbsp;&nbsp;&nbsp;94</code> ![](https://img.shields.io/github/last-commit/graphql-crystal/graphql) [graphql](https://github.com/graphql-crystal/graphql) - GraphQL server library.
- <code>&nbsp;&nbsp;&nbsp;210</code> ![](https://img.shields.io/github/last-commit/ziprandom/graphql-crystal) [graphql-crystal](https://github.com/ziprandom/graphql-crystal) - library inspired by <code>&nbsp;&nbsp;5038</code> ![](https://img.shields.io/github/last-commit/rmosolgo/graphql-ruby) [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) & <code>&nbsp;&nbsp;&nbsp;247</code> ![](https://img.shields.io/github/last-commit/playlyfe/go-graphql) [go-graphql](https://github.com/playlyfe/go-graphql) & <code>&nbsp;&nbsp;&nbsp;185</code> ![](https://img.shields.io/github/last-commit/graphql-dotnet/parser) [graphql-parser](https://github.com/graphql-dotnet/parser).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/itsezc/crystal-gql) [crystal-gql](https://github.com/itsezc/crystal-gql) - GraphQL client shard inspired by Apollo client.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> ![](https://img.shields.io/github/last-commit/garymardell/graphql.cr) [graphql.cr](https://github.com/garymardell/graphql.cr) - GraphQL shard.

<a name="tools" />

## Tools

### Tools - Editors & IDEs & Explorers

- <code>&nbsp;13500</code> ![](https://img.shields.io/github/last-commit/graphql/graphiql) [GraphiQL](https://github.com/graphql/graphiql) - An in-browser IDE for exploring GraphQL.
- <code>&nbsp;&nbsp;5576</code> ![](https://img.shields.io/github/last-commit/graphql-editor/graphql-editor) [GraphQL Editor](https://github.com/graphql-editor/graphql-editor) - Visual Editor & GraphQL IDE.
- <code>&nbsp;&nbsp;6682</code> ![](https://img.shields.io/github/last-commit/APIs-guru/graphql-voyager) [GraphQL Voyager](https://github.com/APIs-guru/graphql-voyager) - Represent any GraphQL API as an interactive graph.
- <code>&nbsp;&nbsp;4121</code> ![](https://img.shields.io/github/last-commit/altair-graphql/altair) [Altair GraphQL Client](https://github.com/altair-graphql/altair) - A beautiful feature-rich GraphQL Client for all platforms.
- [Insomnia](https://insomnia.rest/) - A full-featured API client with first-party GraphQL query editor.
- [Postman](https://learning.postman.com/docs/sending-requests/supported-api-frameworks/graphql/) - An HTTP Client that supports editing GraphQL queries.
- [Apollo Sandbox](https://sandbox.apollo.dev/) - The quickest way to navigate and test your GraphQL endpoints.
- <code>&nbsp;&nbsp;&nbsp;678</code> ![](https://img.shields.io/github/last-commit/Novvum/graphql-birdseye) [GraphQL Birdseye](https://github.com/Novvum/graphql-birdseye) – View any GraphQL schema as a dynamic and interactive graph.
- [AST Explorer](https://astexplorer.net/) - Select "GraphQL" at the top, explore the GraphQL AST and highlight different parts by clicking in the query.
- [Firecamp - GraphQL Playground](https://firecamp.io/graphql) - The fastest collaborative GraphQL playground.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;76</code> ![](https://img.shields.io/github/last-commit/yamafaktory/craftql) [CraftQL](https://github.com/yamafaktory/craftql) - A CLI tool to visualize GraphQL schemas and to output a graph data structure as a graphviz .dot format.

<a name="tool-security" />

### Tools - Security

- [Escape GraphQL Quickscan](https://escape.tech/quickscan/) - One-click security scan of your GraphQL endpoints. Free, no login required.
- [StackHawk - GraphQL Vulnerability Scanner](https://www.stackhawk.com/blog/automated-graphql-security-testing) - [StackHawk](https://www.stackhawk.com)
- [Tinfoil Security - GraphQL Security Scanner](https://www.tinfoilsecurity.com/blog/graphql-security-scanning) - [Tinfoil Security](https://www.tinfoilsecurity.com/solutions/api-scanner)
- <code>&nbsp;&nbsp;&nbsp;939</code> ![](https://img.shields.io/github/last-commit/doyensec/inql) [InQL Scanner](https://github.com/doyensec/inql) - A Burp Extension for GraphQL Security Testing
- [GraphQL Raider](https://portswigger.net/bappstore/4841f0d78a554ca381c65b26d48207e6) [BurpSuite](https://portswigger.net/burp)
- [WAF for graphQL](https://lab.wallarm.com/api-security-solution/) - Web Application Firewall for graphQL APIs
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/davinerd/gql_intruder) [GraphQL Intruder](https://github.com/davinerd/gql_intruder) - Plugin based python script to perform GraphQL vulnerability assessment.

### Tools - Browser Extensions

- <code>&nbsp;&nbsp;1351</code> ![](https://img.shields.io/github/last-commit/apollographql/apollo-client-devtools) [Apollo Client Developer Tools](https://github.com/apollographql/apollo-client-devtools) - GraphQL debugging tools for Apollo Client in the Chrome developer console
- <code>&nbsp;&nbsp;&nbsp;316</code> ![](https://img.shields.io/github/last-commit/Ghirro/graphql-network) [GraphQL Network](https://github.com/Ghirro/graphql-network) - A chrome dev-tools extension for debugging GraphQL network requests.

### Tools - Prototyping

- <code>&nbsp;&nbsp;2432</code> ![](https://img.shields.io/github/last-commit/APIs-guru/graphql-faker) [GraphQL Faker](https://github.com/APIs-guru/graphql-faker) - 🎲 Mock or extend your GraphQL API with faked data. No coding required.
- [GraphQL Designer](http://graphqldesigner.com/) - A developer's web-app tool to rapidly prototype a full stack CRUD implementation of GraphQL with React.

### Tools - Docs

- <code>&nbsp;&nbsp;1408</code> ![](https://img.shields.io/github/last-commit/2fd/graphdoc) [graphdoc](https://github.com/2fd/graphdoc) - Static page generator for documenting GraphQL Schema.
- <code>&nbsp;&nbsp;&nbsp;152</code> ![](https://img.shields.io/github/last-commit/Code-Hex/gqldoc) [gqldoc](https://github.com/Code-Hex/gqldoc) - The easiest way to make API documents for GraphQL.
- <code>&nbsp;&nbsp;&nbsp;506</code> ![](https://img.shields.io/github/last-commit/anvilco/spectaql) [spectaql](https://github.com/anvilco/spectaql) - Autogenerate static GraphQL API documentation

### Tools - Editor Plugins

- [Apollo GraphQL VSCode Extension](https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo) - Rich editor support for GraphQL client and server development that seamlessly integrates with the Apollo platform
- <code>&nbsp;&nbsp;&nbsp;779</code> ![](https://img.shields.io/github/last-commit/jimkyndemeyer/js-graphql-intellij-plugin) [js-graphql-intellij-plugin](https://github.com/jimkyndemeyer/js-graphql-intellij-plugin/) - GraphQL language support for IntelliJ IDEA and WebStorm, including Relay.QL tagged templates in JavaScript and TypeScript.
- <code>&nbsp;&nbsp;&nbsp;427</code> ![](https://img.shields.io/github/last-commit/jparise/vim-graphql) [vim-graphql](https://github.com/jparise/vim-graphql) - A Vim plugin that provides GraphQL file detection and syntax highlighting.
- [Apollo Workbench](https://marketplace.visualstudio.com/items?itemName=apollographql.apollo-workbench) - Tooling to help you develop and mock federated schemas using Apollo Federation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> ![](https://img.shields.io/github/last-commit/orionsoft/atom-graphql-autocomplete) [graphql-autocomplete](https://github.com/orionsoft/atom-graphql-autocomplete) - Autocomplete and lint from a GraphQL endpoint in Atom.

### Tools - Miscellaneous

- <code>&nbsp;&nbsp;8592</code> ![](https://img.shields.io/github/last-commit/dotansimha/graphql-code-generator) [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator) - GraphQL code generator based on schema and documents.
- <code>&nbsp;&nbsp;&nbsp;876</code> ![](https://img.shields.io/github/last-commit/yarax/swagger-to-graphql) [swagger-to-graphql](https://github.com/yarax/swagger-to-graphql) - GraphQL types builder based on REST API described in Swagger. Allows to migrate to GraphQL from REST for 5 minutes
- <code>&nbsp;&nbsp;&nbsp;596</code> ![](https://img.shields.io/github/last-commit/Quramy/ts-graphql-plugin) [ts-graphql-plugin](https://github.com/Quramy/ts-graphql-plugin) - A language service plugin complete and validate GraphQL query in TypeScript template strings.
- <code>&nbsp;&nbsp;&nbsp;457</code> ![](https://img.shields.io/github/last-commit/apollographql/apollo-tracing) [apollo-tracing](https://github.com/apollographql/apollo-tracing) - GraphQL extension that enables you to easily get resolver-level performance information as part of a GraphQL response.
- <code>&nbsp;&nbsp;1710</code> ![](https://img.shields.io/github/last-commit/marmelab/json-graphql-server) [json-graphql-server](https://github.com/marmelab/json-graphql-server) - Get a full fake GraphQL API with zero coding in less than 30 seconds, based on a JSON data file.
- <code>&nbsp;22044</code> ![](https://img.shields.io/github/last-commit/prisma/prisma) [Prisma](https://github.com/prisma/prisma) - Turn your database into a GraphQL API. Prisma lets you design your data model and have a production ready GraphQL API online in minutes.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;27</code> ![](https://img.shields.io/github/last-commit/twinlogix/typetta) [Typetta](https://github.com/twinlogix/typetta) - Node.js ORM written in TypeScript for type lovers. Typetta is the perfect ORM for the GraphQL + NodeJS + Typescript stack.
- <code>&nbsp;&nbsp;&nbsp;637</code> ![](https://img.shields.io/github/last-commit/bradleyboy/tuql) [tuql](https://github.com/bradleyboy/tuql) - Automatically create a GraphQL server from any sqlite database.
- <code>&nbsp;15047</code> ![](https://img.shields.io/github/last-commit/teambit/bit) [Bit](https://github.com/teambit/bit) - Organize GraphQL API as components to be consumed with NPM or modified from any project, [example-explanation](https://hackernoon.com/make-your-graphql-api-easier-to-adopt-through-components-74b022f195c1)).
- <code>&nbsp;&nbsp;1272</code> ![](https://img.shields.io/github/last-commit/ibm/openapi-to-graphql) [openapi-to-graphql](https://github.com/ibm/openapi-to-graphql) - Take any OpenAPI Specification (OAS) or swagger and create a GraphQL interface - Two minute video and resources [here](https://developer.ibm.com/open/projects/openapi-to-graphql/)
- [Retool](https://retool.com/) – Internal tools builder on top of your GraphQL APIs + GraphQL IDE with a schema explorer.
- <code>&nbsp;&nbsp;&nbsp;102</code> ![](https://img.shields.io/github/last-commit/Yelp/dataloader-codegen) [dataloader-codegen](https://github.com/Yelp/dataloader-codegen) - An opinionated JavaScript library for automatically generating predictable, type safe DataLoaders over a set of resources (e.g. HTTP endpoints).
- <code>&nbsp;&nbsp;1320</code> ![](https://img.shields.io/github/last-commit/kamilkisiela/graphql-inspector) [raphql-inspector](https://github.com/kamilkisiela/graphql-inspector): alidate schema, get schema change notifications, validate operations, find breaking changes, look for similar types, schema coverage.
- <code>&nbsp;&nbsp;6916</code> ![](https://img.shields.io/github/last-commit/amplication/amplication) [amplication](https://github.com/amplication/amplication): Amplication is an open‑source low code development tool. It builds database applications with REST API and GraphQL for CRUD with relations, sorting, filtering, pagination.

<a name="databases" />

## Databases

- [Dgraph](https://dgraph.io/) - Scalable, distributed, low latency, high throughput Graph database with GraphQL as the query language
- [EdgeDB](https://edgedb.com/) - The next generation object-relational database with native GraphQL support.
- [FaunaDB](https://fauna.com) - Relational NoSQL database with [GraphQL schema import.](https://fauna.com/blog/getting-started-with-graphql-part-1-importing-and-querying-your-schema) Supports joins, indexes, and multi-region ACID transactions with serverless pay-per-use pricing.
- [ArangoDB](https://arangodb.com/) - Native multi-model database with [GraphQL integration](https://www.arangodb.com/docs/3.4/foxx-reference-modules-graph-ql.html) via the built-in [Foxx Microservices Framework](https://www.arangodb.com/docs/stable/foxx.html).
- <code>&nbsp;&nbsp;2382</code> ![](https://img.shields.io/github/last-commit/semi-technologies/weaviate) [Weaviate](https://github.com/semi-technologies/weaviate) - Weaviate is a cloud-native, modular, real-time vector search engine with a [GraphQL interface](https://www.semi.technology/developers/weaviate/current/graphql-references/) built to scale your machine learning models.
- [Back4App](https://www.back4app.com/graphql-database) - Build a Scalable Database with GraphQL API in minutes.
- [LunaSec](https://www.lunasec.io/) - Key-Value Database for encrypting/tokenizing sensitive data with [GraphQL support](https://www.lunasec.io/docs/pages/getting-started/dedicated-tokenizer/graphql/) to authorize requests. - <code>&nbsp;&nbsp;1039</code> ![](https://img.shields.io/github/last-commit/lunasec-io/lunasec) [Source Code](https://github.com/lunasec-io/lunasec)

<a name="services" />

## Services

- [AWS AppSync](https://aws.amazon.com/appsync/) - Scalable managed GraphQL service with subscriptions for building real-time and offline-first apps
- [FakeQL](https://fakeql.com/) - GraphQL API mocking as a service ... because GraphQL API mocking should be easy!
- [Moesif API Analytics](https://www.moesif.com/features/graphql-analytics) - A GraphQL analaytics and monitoring service to find functional and performance issues.
- [Booster framework](https://booster.cloud/) - An open-source framework that makes you _completely_ forget about infrastructure and allows you to focus exclusively on your business logic. It autogenerates a GraphQL API for your models, supporting mutations, queries, and subscriptions.
- [Hypi](https://hypi.io/) - Low-code, scalable, serverless backend as a service. Your GraphQL & REST over GraphQL backend in minutes.
- [Nhost](https://nhost.io/) - Open source Firebase alternative with GraphQL
- <code>&nbsp;15685</code> ![](https://img.shields.io/github/last-commit/mirumee/saleor) [Saleor](https://github.com/mirumee/saleor/) - GraphQL-first headless e-commerce platform.
- [Stargate](https://stargate.io/docs/stargate/1.0/quickstart/quick_start-graphql.html) - Open source data gateway currently supporting Apache Cassandra&reg; and DataStax Enterprise.

### CDN

- [GraphCDN](https://graphcdn.io/) - GraphQL CDN for caching GraphQL APIs.

### CMS

- [DatoCMS](https://www.datocms.com/) - CDN-based GraphQL based Headless Content Management System.
- [GraphCMS](https://graphcms.com/) - GraphQL based Headless Content Management System.
- [Cosmic](https://www.cosmicjs.com/) - GraphQL-powered Headless CMS and API toolkit.

<a name="book" />

## Books

- [The GraphQL Guide](https://graphql.guide) by John Resig and Loren Sands-Ramshaw
- [Learning GraphQL](https://www.amazon.com/dp/1492030716) by Eve Porcello and Alex Banks
- [Craft GraphQL APIs in Elixir with Absinthe](https://pragprog.com/book/wwgraphql/craft-graphql-apis-in-elixir-with-absinthe) by Bruce Williams and Ben Wilson
- [The Road to GraphQL](https://www.roadtographql.com/)
- [Fullstack GraphQL](https://www.graphql.college/fullstack-graphql) by Julian Mayorga
- [Learning GraphQL and Relay](https://www.packtpub.com/web-development/learning-graphql-and-relay) by Samer Buna
- [Practical GraphQL](https://leanpub.com/book-graphql) by Daniel Schmitz
- [Production Ready GraphQL](https://book.productionreadygraphql.com) by Marc-André Giroux
- [Full Stack GraphQL Applications](https://www.manning.com/books/fullstack-graphql-applications) by William Lyon

<a name="video" />

## Videos

- [GraphQL: The Documentary](https://www.youtube.com/watch?v=783ccP__No8)
- [Zero to GraphQL in 30 Minutes](https://www.youtube.com/embed/UBGzsb2UkeY)
- [Data fetching for React applications at Facebook](https://www.youtube.com/watch?v=9sc8Pyc51uU)
- [React Native & Relay: Bringing Modern Web Techniques to Mobile](https://www.youtube.com/watch?v=X6YbAKiLCLU)
- [Exploring GraphQL](https://www.youtube.com/watch?v=WQLzZf34FJ8)
- [Creating a GraphQL Server](https://www.youtube.com/watch?v=gY48GW87Feo)
- [GraphQL at The Financial Times](https://www.youtube.com/watch?v=S0s935RKKB4)
- [Relay: An Application Framework For React](https://www.youtube.com/watch?v=IrgHurBjQbg)
- [Building and Deploying Relay with Facebook](https://www.youtube.com/watch?t=643&v=Pxdgu2XIAAg)
- [Introduction to GraphQL](https://vimeo.com/144817545)
- [Exploring GraphQL@Scale](https://www.youtube.com/watch?v=_9RgHXqH8J0)
- [What's Next for Phoenix by Chris McCord](https://www.youtube.com/watch?v=IMUpYOc9z3c&feature=youtu.be)
- [GraphQL with Nick Schrock](https://www.youtube.com/watch?v=Ed6oJXKt3-M)
- [Build a GraphQL server for Node.js using PostgreSQL/MySQL](https://www.youtube.com/watch?v=DNPVqK_woRQ)
- [GraphQL server tutorial for Node.js with SQL, MongoDB and REST](https://www.youtube.com/watch?v=PHabPhgRUuU)
- [JavaScript Air Episode 023: Transitioning from REST to GraphQL](https://www.youtube.com/watch?v=ENqDNIp1Nd8)
- [GraphQL Future at react-europe 2016](https://www.youtube.com/watch?v=ViXL0YQnioU)
- [GraphQL at Facebook at react-europe 2016](https://www.youtube.com/watch?v=etax3aEe2dA)
- [Building native mobile apps with GraphQL at react-europe 2016](https://www.youtube.com/watch?v=z5rz3saDPJ8)
- [Build a GraphQL Server](https://www.youtube.com/watch?v=PEcJxkylcRM&list=PLillGF-RfqbYZty73_PHBqKRDnv7ikh68)
- [GraphQL Tutorial](https://www.youtube.com/watch?v=Y0lDGjwRYKw&list=PL4cUxeGkcC9iK6Qhn-QLcXCXPQUov1U7f)
- [Five years of GraphQL](https://www.youtube.com/watch?v=s8meG38iZAM)

<a name="podcast" />

## Podcasts

- [GraphQL.FM](https://podcasts.google.com/feed/aHR0cHM6Ly9hbmNob3IuZm0vcy8zNjE5NmViMC9wb2RjYXN0L3Jzcw==) by Marc-Andre Giroux and Tony Ghita.

<a name="style-guide" />

## Style Guides

- <code>&nbsp;&nbsp;1997</code> ![](https://img.shields.io/github/last-commit/Shopify/graphql-design-tutorial) [Shopify GraphQL Design Tutorial](https://github.com/Shopify/graphql-design-tutorial) - This tutorial was originally created by Shopify for internal purposes. It's based on lessons learned from creating and evolving production schemas at Shopify over almost 3 years.
- [GitLab GraphQL API Style Guide](https://docs.gitlab.com/ee/development/api_graphql_styleguide.html) - This document outlines the style guide for the GitLab GraphQL API.
- [Yelp GraphQL Guidelines](https://yelp.github.io/graphql-guidelines/) - This repo contains documentation and guidelines for a standardized and mostly reasonable approach to GraphQL (at Yelp).
- [Principled GraphQL](https://principledgraphql.com/) - Apollo's 10 GraphQL Principles, broken out into three categories, in a format inspired by the Twelve Factor App.

<a name="blogs" />

## Blogs

- [Official GraphQL blog](https://graphql.org/blog/)
- [Building Apollo](https://blog.apollographql.com/)
- [The Guild blog](https://medium.com/the-guild)
- [Production Ready GraphQL blog](https://productionreadygraphql.com)

<a name="security-blog" />

### Blogs - Security

- [9 GraphQL Security Best Practices](https://blog.escape.tech/9-graphql-security-best-practices/)
- [Discovering GraphQL Endpoints and SQLi Vulnerabilities](https://medium.com/@localh0t/discovering-graphql-endpoints-and-sqli-vulnerabilities-5d39f26cea2e)
- [Securing GraphQL API](https://lab.wallarm.com/securing-graphql-api/)
- [How to secure a GraphQL API (The Complete Vulnerability Checklist)](https://leapgraph.com/graphql-api-security)
- [Security Points to Consider Before Implementing GraphQL](https://nordicapis.com/security-points-to-consider-before-implementing-graphql/)

<a name="post" />

## Posts

- [Using DataLoader to batch GraphQL requests](https://medium.com/@gajus/using-dataloader-to-batch-requests-c345f4b23433)
- [Introducing Relay and GraphQL](https://reactjs.org/blog/2015/02/20/introducing-relay-and-graphql.html)
- [GraphQL Introduction](https://reactjs.org/blog/2015/05/01/graphql-introduction.html)
- [Unofficial Relay FAQ](https://gist.github.com/wincent/598fa75e22bdfa44cf47)
- [Your First GraphQL Server](https://medium.com/the-graphqlhub/your-first-graphql-server-3c766ab4f0a2)
- [GraphQL Overview - Getting Started with GraphQL and Node.js](https://blog.risingstack.com/graphql-overview-getting-started-with-graphql-and-nodejs/)
- [4 Reasons you should try out GraphQL](https://medium.freecodecamp.org/introduction-to-graphql-1d8011b80159)
- [Moving from REST to GraphQL](https://medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247)
- [Writing a Basic API with GraphQL](http://davidandsuzi.com/writing-a-basic-api-with-graphql/)
- [Building a GraphQL Server with Node.js and SQL](https://www.reindex.io/blog/building-a-graphql-server-with-node-js-and-sql/)
- [GraphQL at The Financial Times](https://www.slideshare.net/LondonReact/graph-ql)
- [From REST to GraphQL](https://jacobwgillespie.com/2015-10-09-from-rest-to-graphql)
- [GraphQL: A data query language](https://graphql.org/blog/graphql-a-query-language/)
- [Subscriptions in GraphQL and Relay](https://graphql.org/blog/subscriptions-in-graphql-and-relay/)
- [Relay 101: Building A Hacker News Client](https://medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6)
- [GraphQL Shorthand Notation Cheatsheet](https://wehavefaces.net/graphql-shorthand-notation-cheatsheet-17cd715861b6)
- [The GitHub GraphQL API](https://githubengineering.com/the-github-graphql-api/)
- [Github GraphQL API React Example](https://medium.com/@katopz/github-graphql-api-react-example-eace824d7b61)
- [Testing a GraphQL Server using Jest](https://medium.com/entria/testing-a-graphql-server-using-jest-4e00d0e4980e)
- [How to implement viewerCanSee in GraphQL](https://medium.com/entria/how-to-implement-viewercansee-in-graphql-78cc48de7464)
- [Preventing traversal attacks on your GraphQL API](https://blog.morethancode.dev/preventing-traversal-attacks-in-your-graphql-api/)
- [Mock your GraphQL server realistically with faker.js](https://dev.to/yvonnickfrin/mock-your-graphql-server-realistically-with-faker-js-25oo)
- [Create an infinite loading list with React and GraphQL](https://dev.to/yvonnickfrin/create-an-infinite-loading-list-with-react-and-graphql-19hh)
- [REST vs GraphQL](https://www.moesif.com/blog/technical/graphql/REST-vs-GraphQL-APIs-the-good-the-bad-the-ugly/)
- [Authentication and Authorization for GraphQL APIs](https://www.moesif.com/blog/technical/api-design/Steps-to-Building-Authentication-and-Authorization-For-GraphQL-APIs/)
- [Build a GraphQL API with Siler on top of Swoole](https://www.swoole.co.uk/article/Build-a-GraphQL-API-on-top-of-Swoole)
- [Fluent GraphQL clients: how to write queries like a boss](https://hasura.io/blog/fluent-graphql-clients-how-to-write-queries-like-a-boss/)
- [Level up your serverless game with a GraphQL data-as-a-service layer](https://hasura.io/blog/level-up-your-serverless-game-with-a-graphql-data-as-a-service-layer/)
- [A deep-dive into Relay, the friendly & opinionated GraphQL client](https://hasura.io/blog/deep-dive-into-relay-graphql-client/)
- [make your graphql api easier to adopt through components](https://hackernoon.com/make-your-graphql-api-easier-to-adopt-through-components-74b022f195c1)

<a name="workshopper" />

## Workshoppers

- [How to GraphQL](https://www.howtographql.com) - Fullstack Tutorial Website with Tracks for all Major Frameworks & Languages including React, Apollo, Relay, JavaScript, Ruby, Java, Elixir and many more.
- [Apollo Odyssey](https://odyssey.apollographql.com/) - Apollo's free interactive learning platform.
- <code>&nbsp;&nbsp;&nbsp;920</code> ![](https://img.shields.io/github/last-commit/mugli/learning-graphql) [learning-graphql](https://github.com/mugli/learning-graphql) - An attempt to learn GraphQL.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Chen-Tsu Lin](https://github.com/chentsulin) has waived all copyright and related or neighboring rights to this work.
