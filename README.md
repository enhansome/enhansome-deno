# Awesome Deno with stars

[<img src="deno-logo.png" align="right" width="100">](https://deno.land)

Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust.

This list is a collection of the best Deno modules and resources.

## Contents

* [Docs](#docs)
  * [Official Docs](#official-docs)
  * [External Docs](#external-docs)
* [Modules](#modules)
  * [Automation](#automation)
  * [CLI utils](#cli-utils)
  * [Cloud APIs](#cloud-apis)
  * [Database](#database)
  * [Editor framework](#editor-framework)
  * [Frontend framework](#frontend-framework)
  * [Game engine](#game-engine)
  * [Logging](#logging)
  * [Mail](#mail)
  * [Markdown](#markdown)
  * [Static site generator](#static-site-generator)
  * [Social Platform APIs](#social-platform-apis)
  * [Template engine](#template-engine)
  * [Testing](#testing)
  * [Utils](#utils)
  * [Web framework](#web-framework)
  * [Web utils](#web-utils)
  * [Webview](#webview)
* [Registries](#registries)
* [Showcases](#showcases)
* [Tools](#tools)
* [Integrations](#integrations)
* [Articles](#articles)
* [Blogs/Newsletters](#blogsnewsletters)
* [Presentations](#presentations)
* [Resources](#resources)
  * [Books](#books)
* [Resources in Other Languages](#resources-in-other-languages)
  * [Chinese](#chinese)
  * [Hebrew](#hebrew)
  * [Indonesian](#indonesian)
  * [Italian](#italian)
  * [Japanese](#japanese)
  * [Russian](#russian)
  * [Spanish](#spanish)
  * [Darija (Arabe marocain)](#darija)
  * [Kurdish (Central)](#kurdish-central)

## Docs

### Official Docs

* [Deno API Reference](https://docs.deno.com/api)
* [Deno Manual](https://docs.deno.com)
* [Deno Standard Library](https://jsr.io/@std)
* [Official Site](https://deno.com)

### External Docs

* [V8 Docs for Deno](https://denolib.github.io/v8-docs/)

## Modules

### Automation

* [zuke](https://github.com/zuke-build/zuke) ⭐ 49 | 🐛 15 | 🌐 TypeScript | 📅 2026-11-21 - Code-first, strongly-typed build automation system where builds are defined as TypeScript classes.

### CLI utils

* [yargs](https://github.com/yargs/yargs) ⭐ 11,508 | 🐛 201 | 🌐 JavaScript | 📅 2026-11-17 - The modern, pirate-themed successor to optimist.
* [cac](https://github.com/cacjs/cac) ⭐ 3,151 | 🐛 32 | 🌐 TypeScript | 📅 2026-11-20 - Simple yet powerful framework for building command-line apps.
* [cliffy](https://github.com/c4spar/cliffy) ⭐ 1,186 | 🐛 34 | 🌐 TypeScript | 📅 2026-09-18 - The complete solution for building interactive command-line tools.
* [commit-sage-cli](https://github.com/AhmedOsman101/commit-sage-cli) ⭐ 65 | 🐛 6 | 🌐 TypeScript | 📅 2026-11-20 - Generates Conventional Commit messages with AI based on Git repository changes.
* [cli-spinner](https://github.com/ameerthehacker/deno-cli-spinners) ⭐ 57 | 🐛 2 | 🌐 TypeScript | 📅 2025-03-18 - Show spinners in the terminal while running long tasks.
* [clinfer](https://github.com/jersou/clinfer) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-28 - Automatically generate CLIs from JS objects, classes or ES modules.

### Cloud APIs

* [sigflint](https://github.com/bompus/sigflint) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-21 - AWS Signature Version 4 and SigV4a request signing with no dependencies, for use with `fetch`.
* [aws-api](https://aws-api.danopia.deno.net/) - From-scratch Typescript AWS API client built for Deno.

### Database

* [postgres](https://github.com/denodrivers/postgres) ⭐ 652 | 🐛 40 | 🌐 TypeScript | 📅 2025-04-24 - Driver for PostgreSQL database.
* [nessie](https://github.com/lmxrd/deno-nessie) ⭐ 518 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-09 - Create, migrate and rollback migrations for PostgreSQL, MySQL and SQLite.
* [deno\_mongo](https://github.com/denodrivers/mongo) ⭐ 511 | 🐛 48 | 🌐 TypeScript | 📅 2025-03-14 - MongoDB database driver.
* [redis](https://github.com/denodrivers/redis) ⭐ 463 | 🐛 38 | 🌐 TypeScript | 📅 2026-11-16 - An experimental implementation of redis client for deno.
* [maxminddb](https://github.com/josh-hemphill/maxminddb-wasm) ⭐ 18 | 🐛 1 | 🌐 TypeScript | 📅 2026-09-12 - A library that enables the usage of MaxmindDB geoIP database files
* [kvdock](https://github.com/zisam-glitch/kvdock) ⭐ 4 | 🐛 6 | 🌐 TypeScript | 📅 2026-11-15 - Zero-dependency key-value and multi-tier caching engine with native Deno KV support and single-flight stampede protection.
* [@iuioiua/redis](https://jsr.io/@iuioiua/redis) - Fast, lightweight Redis client built upon the Web Streams API.

### Editor framework

* [Denops](https://github.com/vim-denops/denops.vim) ⭐ 795 | 🐛 9 | 🌐 TypeScript | 📅 2026-10-31 - 🐜 An ecosystem to write Vim/Neovim plugins with Deno.

### Frontend framework

* [fresh](https://github.com/freshframework/fresh) ⭐ 13,787 | 🐛 162 | 🌐 TypeScript | 📅 2026-10-17 - The next-gen web framework.

### Game engine

* [sdl2](https://github.com/littledivy/deno_sdl2) ⭐ 184 | 🐛 15 | 🌐 TypeScript | 📅 2025-10-18 - SDL2 module for Deno
* [caviar](https://github.com/load1n9/caviar) ⭐ 172 | 🐛 4 | 🌐 TypeScript | 📅 2025-09-03 - ⚡ Blazing fast, modern, Game Engine powered by WebGPU for Deno and the browser

### Image

* [ImageScript](https://github.com/imagescript/ImageScript) ⭐ 685 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-21 - Image processing in JavaScript, utilizing WebAssembly for performance.
* [kavel](https://github.com/hanshs474/kavel-ts) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-14 - Generate and edit images with AI without an API key or account.
* [aigifmaker](https://github.com/hanshs474/aigifmaker-ts) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-09 - Turn text prompts into animated GIFs with the AI GIF Maker API.

### Logging

* [LogTape](https://github.com/dahlia/logtape) ⭐ 2,035 | 🐛 13 | 🌐 TypeScript | 📅 2026-10-19 - Simple logging library with zero dependencies for Deno/Node.js/Bun/browsers.

### Mail

* [dmarc-rua](https://github.com/domaincanary/dmarc-rua) ⭐ 2 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-01 - Parse DMARC aggregate reports from XML, gzip, zip and report emails.

### Markdown

* [LiteMarkup](https://github.com/tuures/LiteMarkup) ⭐ 2 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-17 - AST-first parser. Under 3 KB gzipped, zero dependencies.

### Static site generator

* [lume](https://github.com/lumeland/lume) ⭐ 2,285 | 🐛 48 | 🌐 TypeScript | 📅 2026-11-21 - A static site generator similar to Jekyll or Eleventy with support for multiple file formats.
* [zerho](https://github.com/glastor-core/zerho) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-21 - High-performance documentation engine for Deno 2 and Edge runtimes with interactive playground, OpenAPI explorer, and native llms.txt support.

### Social Platform APIs

* [grammY](https://github.com/grammyjs/grammY) ⭐ 3,808 | 🐛 26 | 🌐 TypeScript | 📅 2026-11-21 - Telegram Bot API framework for Deno.
* [discordeno](https://github.com/discordeno/discordeno) ⭐ 943 | 🐛 25 | 🌐 TypeScript | 📅 2026-11-22 - Discord API library for Deno
* [MTKruto](https://github.com/MTKruto/MTKruto) ⭐ 174 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-12 - Deno-first, cross-runtime client library for Telegram's MTProto API.
* [Circe](https://github.com/sxnnyside-project/circe) ⭐ 1 | 🐛 3 | 🌐 TypeScript | 📅 2026-11-18 - Inversion-of-control framework for discord.js bots with file-system routing, guards and Gateway or HTTP transport.

### Template engine

* [eta](https://github.com/bgub/eta) ⭐ 1,771 | 🐛 13 | 🌐 TypeScript | 📅 2026-11-14 - Fast, lightweight, and configurable embedded template engine.

### Testing

* [keploy](https://github.com/keploy/keploy) ⭐ 19,935 | 🐛 818 | 🌐 Go | 📅 2026-11-22 - Record real traffic to generate integration tests and mock Postgres, Redis, and fetch calls.
* [unexpected](https://github.com/unexpectedjs/unexpected) ⭐ 366 | 🐛 52 | 🌐 JavaScript | 📅 2026-10-14 - Extensible BDD assertion toolkit.
* [superdeno](https://github.com/cmorten/superdeno) ⭐ 123 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-25 - Super-agent driven library for testing Deno HTTP servers.
* [qunitx](https://github.com/izelnakri/qunitx) ⭐ 36 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-17 - Zero dependency, fully customizable, mature, universal test API that can run interchangably in node.js, Deno & browser, using default runtime test runners.
* [tepi](https://github.com/jupegarnica/tepi) ⭐ 6 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-20 - A .http Test Runner

### Utils

* [croner](https://github.com/Hexagon/croner) ⭐ 2,617 | 🐛 3 | 🌐 TypeScript | 📅 2026-11-19 - Cron library with advanced scheduling features, well-documented API, and zero dependencies.
* [fastest-validator](https://github.com/icebob/fastest-validator) ⭐ 1,461 | 🐛 45 | 🌐 JavaScript | 📅 2026-08-20 - Schema validator for all javascript platforms
* [evt](https://github.com/garronej/evt) ⭐ 460 | 🐛 8 | 🌐 TypeScript | 📅 2025-10-01 - Type safe replacement for EventEmitter.
* [computed\_types](https://github.com/neuledge/computed-types) ⭐ 358 | 🐛 2 | 🌐 TypeScript | 📅 2026-11-09 - Joi like validators for Typescript and Deno.
* [rubico](https://github.com/a-synchronous/rubico) ⭐ 283 | 🐛 55 | 🌐 JavaScript | 📅 2026-11-06 - 🏞 \[a]synchronous function composition; it just works.
* [optionals](https://github.com/OliverBrotchie/optionals) ⭐ 193 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-07 - Rust-like error handling and options with exhaustive pattern matching.
* [solc](https://github.com/deno-web3/solc) ⭐ 72 | 🐛 2 | 🌐 TypeScript | 📅 2025-02-27 - 💎 Solidity bindings for Deno.
* [qrcode](https://github.com/denorg/qrcode) ⭐ 47 | 🐛 7 | 🌐 JavaScript | 📅 2026-10-03 - QR code image generator for Deno.
* [envapt](https://github.com/materwelonDhruv/envapt) ⭐ 25 | 🐛 4 | 🌐 TypeScript | 📅 2026-11-10 - Read environment variables as typed values with built-in converters, Standard Schema validation, and zero dependencies.
* [durationjs](https://github.com/retraigo/duration.js) ⭐ 21 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-06 - Get formatted time duration from a timestamp or a human-readable string.
* [fortuna](https://github.com/retraigo/fortuna) ⭐ 21 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-04 - Weighted gacha system.
* [wu-diff-js](https://github.com/bokuweb/wu-diff-js) ⭐ 19 | 🐛 13 | 🌐 TypeScript | 📅 2026-05-12 - A diff library to compute differences between two slices using wu(the O(NP)) algorithm.
* [deno\_kv\_fs](https://github.com/hviana/deno_kv_fs) ⭐ 16 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-20 Deno KV file system, compatible with Deno deploy. Makes use of Web Streams API.
* [csv-pipe](https://github.com/martsinlabs/csv-pipe) ⭐ 15 | 🐛 4 | 🌐 TypeScript | 📅 2026-09-11 - Typed, zero-dependency CSV parser and encoder for every runtime.
* [PLS](https://github.com/xorgram/pls) ⭐ 9 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-22 - Use 2 lines to persist localStorage in any database, including, but not limited to, MongoDB, PostgreSQL and Redis.
* [injecute](https://github.com/Masyaka/injecute) ⭐ 5 | 🐛 3 | 🌐 TypeScript | 📅 2026-11-14 - Type-safe dependency injection container with explicit wiring and no decorators.
* [esm-itter](https://github.com/tillsanders/esm-itter) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-10 – A strongly typed fork of the popular EventEmitter3 with a focus on EcmaScript module syntax, TypeScript and modern tooling.
* [json-schema-for-llms](https://github.com/carmenaresearch/json-schema-for-llms) ⭐ 2 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-13 - Turn a JSON document too large for an LLM context window into a short JSON Schema with counts, ranges and example records.
* [switcher4deno](https://github.com/switcherapi/switcher-client-deno) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-31 - Feature Flag Deno SDK client for Switcher-API.

### Validation

* [zod](https://github.com/colinhacks/zod) ⭐ 44,378 | 🐛 128 | 🌐 TypeScript | 📅 2026-11-20 - TypeScript-first schema validation with static type inference.
* [is-kit](https://github.com/necoz-oss/is-kit) ⭐ 209 | 🐛 6 | 🌐 TypeScript | 📅 2026-11-21 - Build small, composable type guards with natural TypeScript narrowing and zero dependencies.

### Web framework

* [hono](https://github.com/honojs/hono) ⭐ 33,011 | 🐛 376 | 🌐 TypeScript | 📅 2026-11-20 - Ultrafast web framework for Cloudflare Workers, Deno, and Bun. Fast, but not only fast.
* [orpc](https://github.com/middleapi/orpc) ⭐ 5,779 | 🐛 39 | 🌐 TypeScript | 📅 2026-11-22 - End-to-end typesafe APIs with RPC and OpenAPI support, without code generation.
* [drash](https://github.com/drashland/drash) ⭐ 1,063 | 🐛 7 | 🌐 TypeScript | 📅 2026-10-24 - A REST microframework for Deno's HTTP server with zero dependencies.
* [alosaur](https://github.com/alosaur/alosaur) ⭐ 818 | 🐛 23 | 🌐 TypeScript | 📅 2026-07-24 - Alosaur - Deno web framework with many ES Decorators.
* [danet](https://github.com/Savory/Danet) ⭐ 531 | 🐛 3 | 🌐 HTML | 📅 2026-08-17 - A Savory web framework for Deno heavily inspired by [Nest.js](https://nestjs.com).
* [faster\_react](https://github.com/hviana/faster_react) ⭐ 100 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-06 - Full Stack web framework with React + Faster. Fully compatible with Deno Deploy.
* [faster](https://github.com/hviana/faster) ⭐ 57 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-01 - A fast and optimized middleware server with a set of useful middlwares.

### Web utils

* [gql](https://github.com/deno-libs/gql) ⭐ 205 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-10 - Universal GraphQL HTTP middleware.
* [rpc](https://github.com/deno-libs/rpc) ⭐ 23 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-06 - JSONRPC server implementation for Deno.
* [linkpeek](https://github.com/thegruber/linkpeek) ⭐ 19 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-18 - Extract Open Graph, Twitter Card and JSON-LD link-preview metadata from a URL.
* [forwarded](https://github.com/deno-libs/forwarded) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-26 - Deno port of `forwarded` library.
* [graphql-tag](https://github.com/deno-libs/graphql_tag) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-07 - GraphQL schema AST from template literal.

### Webview

* [webview](https://github.com/webview/webview_deno) ⭐ 1,590 | 🐛 43 | 🌐 TypeScript | 📅 2025-02-25 - Deno bindings for webview, a tiny library for creating web-based desktop GUIs.

## Registries

* [deno.land/x/](https://deno.land/x/) - The official 3rd party module registry.

## Showcases

* [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy) ⭐ 6,687 | 🐛 35 | 🌐 TypeScript | 📅 2026-10-27 - 🏆 Add dynamically generated GitHub Trophy on your readme
* [Deno Rest](https://github.com/Prolifode/deno_rest) ⭐ 163 | 🐛 3 | 🌐 TypeScript | 📅 2025-02-09 - A Boilerplate for deno RESTful apis.
* [Chobble Tickets](https://github.com/chobbledotcom/tickets) ⭐ 37 | 🐛 46 | 🌐 TypeScript | 📅 2026-11-21 - Open source ticket sales system with encrypted attendee data and Stripe, Square, or SumUp payments.
* [globnotes](https://github.com/alexindigo/globnotes) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2026-11-22 - Self-hosted Markdown note-taking app for Obsidian vaults and nested folders, with full-text search and sandboxed plugins.
* [Medusa Edge API Gateway](https://github.com/glastor-core/medusa) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-21 - Resilient Edge API Gateway and caching proxy on Deno Deploy with circuit breaker, single-flight deduplication, and Deno KV.
* [ShopSavvy Deno Deploy](https://github.com/shopsavvy/deno-deploy-shopsavvy) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-01 - Deno Deploy router with Hono for product search, real-time pricing, and price history.
* [The Official Showcase](https://deno.com/showcase) - The official showcase of Deno.

## Tools

* [vscode-deno](https://github.com/denoland/vscode_deno) ⭐ 1,548 | 🐛 129 | 🌐 TypeScript | 📅 2026-09-26 - VS Code extension that provides Deno support using the `TypeScript Deno language service plugin`.
* [dnt](https://github.com/denoland/dnt) ⭐ 1,337 | 🐛 65 | 🌐 Rust | 📅 2026-10-01 - Deno to npm package build tool.
* [deno\_docker](https://github.com/denoland/deno_docker) ⭐ 1,014 | 🐛 18 | 🌐 Dockerfile | 📅 2026-10-21 - Latest dockerfiles and images for Deno - alpine, centos, debian, ubuntu.
* [denoify](https://github.com/garronej/denoify) ⭐ 949 | 🐛 14 | 🌐 TypeScript | 📅 2025-10-01 - For NPM module authors that would like to support Deno but do not want to write and maintain a port.
* [denopkg](https://github.com/egoist-labs/denopkg.com) ⭐ 238 | 🐛 8 | 🌐 TypeScript | 📅 2025-08-14 - An easier way to use code from GitHub in your Deno project.
* [pup](https://github.com/Hexagon/pup) ⭐ 197 | 🐛 14 | 🌐 TypeScript | 📅 2026-11-11 - Advanced process manager for Deno. With autorestart, fs watch, cron start, process telemetry, ipc, clustering, load balancer and more.
* [denomander](https://github.com/siokas/denomander) ⭐ 151 | 🐛 3 | 🌐 TypeScript | 📅 2025-02-20 - Deno command-line interfaces inspired from commander.js.
* [studio-pack-generator](https://github.com/jersou/studio-pack-generator) ⭐ 130 | 🐛 3 | 🌐 TypeScript | 📅 2026-06-28 - Convert a folder or a RSS URL to Studio pack for Lunii device
* [denoliver](https://github.com/joakimunge/denoliver) ⭐ 104 | 🐛 5 | 🌐 TypeScript | 📅 2025-07-24 - A simple, dependency free file server with live reload.
* [make-deno-edition](https://github.com/bevry/make-deno-edition) ⭐ 42 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-18 - Automatically makes package.json projects (such as npm packages and node.js modules) compatible with Deno.
* [copilotz](https://github.com/copilotzhq/copilotz) ⭐ 6 | 🐛 2 | 🌐 TypeScript | 📅 2026-11-22 - TypeScript runtime for apps used by people, the app's own agents and AI assistants over MCP, with one set of Actions, access rules and audit record for every caller.
* [clone](https://github.com/ekaragodin/clone) ⭐ 4 | 🐛 2 | 🌐 TypeScript | 📅 2026-11-08 - A simple utility for the convenient clone.
* [CompatLab](https://github.com/siddiksawani/CompatLab) ⭐ 4 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-16 - Check npm package loading across pinned Deno, Node.js and Bun versions with shareable reports.
* [bare-devcontainer/templates](https://github.com/bare-devcontainer/templates/tree/main/src/deno) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2026-11-21 - Security-focused Deno dev container for JS/TS with hardened defaults and cached modules. The base image is available at [bare-devcontainer/images](https://github.com/bare-devcontainer/images/tree/main/src/deno) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2026-11-21.
* [nemesis](https://github.com/glastor-core/nemesis) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-21 - Automated DevSecOps auditing, repository hygiene, auto-fix, and compliance CLI built with Deno 2.
* dvm
  * [justjavac/dvm](https://github.com/justjavac/dvm) ⭐ 713 | 🐛 0 | 🌐 Rust | 📅 2026-10-25 - Deno Version Manager: manage multiple active Deno versions.
  * [asdf-community/asdf-deno](https://github.com/asdf-community/asdf-deno) ⭐ 132 | 🐛 9 | 🌐 Shell | 📅 2026-09-06 - Deno plugin for [asdf](https://asdf-vm.com/)
  * [ghosind/dvm](https://github.com/ghosind/dvm) ⭐ 52 | 🐛 4 | 🌐 Shell | 📅 2025-09-16 - A lightweight Deno Version Manager for Linux/MacOS.

## Integrations

* [Netlify Edge Functions](https://docs.netlify.com/build/edge-functions/overview/) - Edge Functions connect the Netlify platform and workflow.
* [Slack Custom Functions](https://docs.slack.dev/tools/deno-slack-sdk/guides/creating-custom-functions/) - Build custom Run On Slack functions using Deno.
* [Smallweb](https://www.smallweb.run/) - A personal cloud contained in a single directory. You can customize the server behavior using Deno.
* [Supabase Edge Functions](https://supabase.com/docs/guides/functions) - Edge Functions are server-side TypeScript functions, distributed globally at the edge.
* [Astro](https://docs.astro.build/en/guides/deploy/deno/) - Deploy a server-side rendered Astro site to Deno Deploy.

## Blogs/Newsletters

* [Deno Blog](https://deno.com/blog) - The official blog of the Deno Company.
* [Deno News](https://deno.news) - A newsletter of Deno articles, news and cool projects.

## Articles

* [Develop with Deno and Visual Studio Code](https://medium.com/@kitsonk/develop-with-deno-and-visual-studio-code-225ce7c5b1ba)
* [First thoughts on Deno, the JavaScript/TypeScript run-time](https://43081j.com/2019/01/first-look-at-deno)
* [Getting started with Deno](https://dev.to/wuz/getting-started-with-deno-e1m)
* [What's Deno, and how is it different from Node.js?](https://dev.to/bnevilleoneill/what-s-deno-and-how-is-it-different-from-node-js-366g)
* [Write a small API using Deno](https://dev.to/kryz/write-a-small-api-using-deno-1cl0)
* [Deno on Cloud Run](https://medium.com/google-cloud/deno-on-cloud-run-89ae64d1664d)
* [Learn Deno: Chat app](https://aralroca.com/blog/learn-deno-chat-app)
* [From Node to Deno](https://dev.to/aralroca/from-node-to-deno-5gpn)
* [Create a simple Note-taking app with Deno](https://dev.to/jeferson_sb/create-a-simple-note-taking-app-with-deno-3k7g)
* [Building API's using Deno, Oak and MYSQL](https://codeforgeek.com/building-api-server-using-deno-and-mysql/)
* [Create your first News CLI app using Deno](https://medium.com/javascript-in-plain-english/creating-your-first-news-cli-app-using-deno-e1470398c627)
* [Continuous Integration with Deno](https://semaphoreci.com/blog/continuous-integration-with-deno)
* [The Hidden Superpower of Deno: xeval](https://stefanbuck.com/blog/hidden-superpower-deno-xeval)
* [Getting Started with Deno](https://sabe.io/tutorials/getting-started-with-deno)
* [How to deploy a Deno app using Docker](https://sabe.io/tutorials/how-to-deploy-deno-app-docker)

## Presentations

* [10 Things I Regret About Node.js - Ryan Dahl - JSConf EU 2018](https://www.youtube.com/watch?v=M3BM9TB-8yA)
  * [Slides](https://tinyclouds.org/jsconf2018.pdf)
* [JSDC 2018#A01 - Deno, A New Server-Side Runtime By Ryan Dahl](https://www.youtube.com/watch?v=FlTG0UXRAkE)
* [Ryan Dahl. Deno, a new way to JavaScript. JS Fest 2019 Spring](https://www.youtube.com/watch?v=z6JRlx5NC9E)
  * [Slides](https://www.slideshare.net/JSFestUA/js-fest-2019-ryan-dahl-deno-a-new-way-to-javascript)
* [Rafał Pocztarski — From Node.js to Deno - JavaScript/TypeScript runtime built with V8 and Rust \[EN\]](https://www.youtube.com/watch?v=Aib1OZLy0_c)
* [Ryan Dahl: A secure runtime for JavaScript and TypeScript | js.la April 2019](https://www.youtube.com/watch?v=RAmqgbv247s)
  * [Slides](https://docs.google.com/presentation/d/1CSQVTeH5tFzE4AZVXIpx9Xwew5YS-gxJZ03eRFtNeIc/edit)
* [Ryan Dahl: Deno, a new way to JavaScript - HolyJS 2019 Piter](https://www.youtube.com/watch?v=HjdJzNoT_qg)
  * [Slides](https://docs.google.com/presentation/d/1BjvZx5S8noVfFINptH4jfKfqh9jB9nXlFC0I3oIDtg4/edit)
* [Rafał Pocztarski - What is Deno? A new runtime for modern JavaScript and TypeScript backends for 2020s - Deno Warsaw](https://www.youtube.com/watch?v=aI5A9zvYSjk)
* [Michał Sabiniarz - How to contribute to Deno? - Deno Warsaw](https://www.youtube.com/watch?v=LAtjnKLbPpw)
* [Bartek Iwańczuk - Deno internals, how modern runtime is built - Deno Warsaw](https://www.youtube.com/watch?v=qt7fbmypAFk)
  * [Slides](https://docs.google.com/presentation/d/1LYNGpyjx9PemL-P__7hVC8mSqkX-jL8VQLMhCRehy00/edit?usp=sharing)
* [Ryan Dahl & Kitson Kelly: Deno is a New Way to JavaScript - TSConf 2019](https://www.youtube.com/watch?v=1gIiZfSbEAE)
* [Bert Belder - Deno - dotJS 2019](https://www.youtube.com/watch?v=puXyo1jGQys)
* [Kitson P. Kelly - Deno, and The Future of JavaScript Runtimes - CityJS Conf 2020](https://www.youtube.com/watch?v=2eRyZpX4qvI)
* [Matías Insaurralde - Deno: an experimental approach on V8 interoperability \[EN subtitles\] - NodeConf Argentina 2019](https://www.youtube.com/watch?v=N0BRE-0n2cU)
  * [Slides](https://speakerdeck.com/matiasinsaurralde/deno-an-experimental-approach-on-v8-interoperability)

## Resources

### Books

* [Modern Web Development with Deno](https://bpbonline.com/products/modern-web-development-with-deno)

## Resources in Other Languages

### Chinese

* [Deno 并不是下一代 Node.js](https://juejin.im/post/5b14a390e51d4506c1300bbc)
* [玩 Deno 遇到问题的解决方案](https://juejin.im/post/5b1245b3f265da6e4c6cf249)
* [让我们一起来学习别人学不动的 Deno](https://segmentfault.com/a/1190000015151287)
* [Design Mistakes in Node zh-CN](https://zhuanlan.zhihu.com/p/37637923)
* [Node之父ry：Node中的设计错误](https://mp.weixin.qq.com/s/7XAiYw18c8YZc-fXk0-wrw)
* [Node之父 - Deno，一个新的JS运行时](https://www.bilibili.com/video/av52038617)

### Hebrew

* [Deno intro in Hebrew (slides in English)](https://www.youtube.com/watch?v=9tJ_LkI6_qw)

### Indonesian

* [Berkenalan dengan Deno](https://medium.com/@redhajuanda/berkenalan-dengan-dengan-deno-c48cdf3aa31e)
* [Perkenalan Deno dan Instalasi](https://youtu.be/V_kpUTJSd9c)
* [Deno Land Indonesia Telegram group](https://t.me/deno_id)

### Italian

* [Deno - L'anagramma di Node](https://www.slideshare.net/FrancescoSciuti/deno-lanagramma-di-node)

### Japanese

* [Node.js における設計ミス By Ryan Dahl](https://yosuke-furukawa.hatenablog.com/entry/2018/06/07/080335)
* [mizchi/deno\_code\_reading.md](https://gist.github.com/mizchi/31e5628751330b624a0e8ada9e739b1e)
* [Design Mistakes in Node & Deno #kng5 / deno](https://speakerdeck.com/masashi/deno)
* [Dive into Deno：プロセス起動からTypeScriptが実行されるまで](https://blog.leko.jp/post/code-reading-of-deno-boot-process/)

### Russian

* [Telegram channel](https://t.me/denoland_ru)
* [Telegram chat](https://t.me/denoland)

### Spanish

* [Hola Deno! . 🦕](https://medium.com/javascript-espa%C3%B1ol/hola-deno-f31f9f6f2c84)
* [Así puedes crear tu primera API REST con Deno](https://medium.com/@mpampols/as%C3%AD-puedes-crear-tu-primera-api-rest-con-deno-a9094ee5c0b2)
* [Primeros pasos con Deno 🦕 El sucesor de NodeJS desarrollado con Rust y TypeScript](https://medium.com/@manurua/primeros-pasos-con-deno-el-nuevo-nodejs-desarrollado-con-rust-y-typescript-b9ac14f7d0c7)
* [Primer vistazo con deno](https://dev.to/buttercubz/first-look-with-deno-spanish-30dh)

### Darija

* [A first look at Deno | BlaBlaConf 2021 🇲🇦](https://www.youtube.com/watch?v=Y_etUvzAa4s)

### Kurdish (Central)

* [A short introduction to Deno](https://devs.krd/about-deno)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-22._
