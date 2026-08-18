# Awesome gRPC with stars

[<img src="https://cdn.rawgit.com/grpc/grpc.github.io/master/img/grpc.svg" align="right">](https://grpc.io)

> A curated list of useful resources for gRPC

## Contents

* [Documentation](#documentation)
* [Community](#community)
* [Official Libraries and Tools](#official)
* [Tools](#tools)
  * [CLI](#tools-cli)
  * [GUI](#tools-gui)
  * [Testing](#tools-test)
  * [Other](#tools-other)
* [Language-Specific](#lang)
  * [Go](#lang-go)
  * [Node.js](#lang-nodejs)
  * [Java](#lang-java)
  * [Ruby](#lang-ruby)
  * [Python](#lang-py)
  * [C#](#lang-cs)
  * [Rust](#lang-rust)
  * [Haskell](#lang-hs)
  * [Erlang](#lang-erlang)
  * [Elixir](#lang-elixir)
  * [Elm](#lang-elm)
  * [TypeScript](#lang-ts)
  * [Scala](#lang-scala)
  * [Dart](#lang-dart)
  * [Kotlin](#lang-kotlin)
  * [Perl](#lang-perl)
  * [C++](#lang-cpp)
  * [Ballerina](#lang-ballerina)
* [Resources](#resources)
  * [Tutorials](#res-tuts)
  * [Videos](#res-videos)
  * [Slides](#res-slides)
  * [Examples](#res-examples)
  * [Miscellaneous](#res-misc)
* [Protocol Buffers](#proto)
  * [Documentation](#proto-docs)
  * [Package Managers](#proto-package-managers)
  * [Tools](#proto-tools)
* [Similar](#similar)
* [Archive](#archive)

## Documentation

* [Technical documentation](https://github.com/grpc/grpc/tree/master/doc) ⭐ 45,226 | 🐛 1,380 | 🌐 C++ | 📅 2026-08-18 - Collection of useful technical documentation
* [gRPC status codes](https://github.com/grpc/grpc/blob/master/doc/statuscodes.md) ⭐ 45,226 | 🐛 1,380 | 🌐 C++ | 📅 2026-08-18 - Status codes and their use in gRPC
* [gRPC status code mapping](https://github.com/grpc/grpc/blob/master/doc/http-grpc-status-mapping.md) ⭐ 45,226 | 🐛 1,380 | 🌐 C++ | 📅 2026-08-18 - HTTP to gRPC Status Code Mapping
* [grpc-errors](https://github.com/avinassh/grpc-errors) ⭐ 588 | 🐛 12 | 🌐 C# | 📅 2023-10-25 - Code examples in each language on how to return and handle error statuses.
* [Website](https://grpc.io/) - Official documentation, libraries, resources, samples and FAQ
* [API Design Guide](https://cloud.google.com/apis/design/) - Google Cloud API Design Guide useful for gRPC API design insights

## Community

* [Community links](https://grpc.io/community/) - Mailing list, Gitter, Twitter, Reddit

<a name="official"></a>

## Official Libraries and Tools

* [gRPC Core](https://github.com/grpc/grpc) ⭐ 45,226 | 🐛 1,380 | 🌐 C++ | 📅 2026-08-18 - C, C++, Ruby, Node.js, Python, PHP, C#, Objective-C
* [grpc\_cli](https://github.com/grpc/grpc/blob/master/doc/command_line_tool.md) ⭐ 45,226 | 🐛 1,380 | 🌐 C++ | 📅 2026-08-18 - gRPC CLI tool
* [gRPC Go](https://github.com/grpc/grpc-go) ⭐ 23,035 | 🐛 127 | 🌐 Go | 📅 2026-08-18 - The Go language implementation of gRPC. HTTP/2 based RPC
* [gRPC Java](https://github.com/grpc/grpc-java) ⭐ 12,061 | 🐛 528 | 🌐 Java | 📅 2026-08-17 - The Java gRPC implementation. HTTP/2 based RPC
* [gRPC Web](https://github.com/grpc/grpc-web) ⭐ 9,254 | 🐛 170 | 🌐 JavaScript | 📅 2026-08-07 - gRPC for Web Clients
* [gRPC Node.js](https://github.com/grpc/grpc-node) ⭐ 4,844 | 🐛 238 | 🌐 TypeScript | 📅 2026-06-17 - gRPC for Node.js
* [gRPC C#](https://github.com/grpc/grpc-dotnet) ⭐ 4,479 | 🐛 176 | 🌐 C# | 📅 2026-08-17 - The C# language implementation of gRPC
* [gRPC Swift](https://github.com/grpc/grpc-swift) ⭐ 2,248 | 🐛 99 | 🌐 Swift | 📅 2026-08-10 - The Swift language implementation of gRPC
* [gRPC Kotlin](https://github.com/grpc/grpc-kotlin) ⭐ 1,297 | 🐛 113 | 🌐 Kotlin | 📅 2025-12-19 - The Kotlin gRPC implementation. Based on gRPC Java
* [gRPC Dart](https://github.com/grpc/grpc-dart) ⭐ 892 | 🐛 110 | 🌐 Dart | 📅 2026-08-03 - The Dart language implementation of gRPC
* [gRPC contrib](https://github.com/grpc/grpc-contrib) ⭐ 66 | 🐛 6 | 📅 2026-06-29 - Known useful contributions around github
* [gRPC Ecosystem](https://github.com/grpc-ecosystem) - gRPC Ecosystem that complements gRPC

## Tools

<a name="tools-cli"></a>

### CLI

* [grpcurl](https://github.com/fullstorydev/grpcurl) ⭐ 12,779 | 🐛 121 | 🌐 Go | 📅 2026-08-17 - Like cURL, but for gRPC: Command-line tool for interacting with gRPC servers
* [Evans](https://github.com/ktr0731/evans) ⭐ 4,489 | 🐛 37 | 🌐 Go | 📅 2023-12-26 - more expressive universal gRPC (CLI) client
* [grpcc](https://github.com/njpatel/grpcc) ⭐ 1,133 | 🐛 27 | 🌐 JavaScript | 📅 2019-04-18 - Node.js grpc command-line client
* [polyglot](https://github.com/grpc-ecosystem/polyglot) ⭐ 535 | 🐛 18 | 🌐 Java | 📅 2022-09-05 - A gRPC command line client written in Java
* [protodot](https://github.com/seamia/protodot) ⭐ 469 | 🐛 8 | 🌐 Go | 📅 2023-12-21 - Transforming your .proto files into .dot files (and .svg, .png if you happen to have graphviz installed)
* [grpc-client-cli](https://github.com/vadimi/grpc-client-cli) ⭐ 311 | 🐛 3 | 🌐 Go | 📅 2026-08-17 - interactive gRPC client
* [grpcdebug](https://github.com/grpc-ecosystem/grpcdebug) ⭐ 194 | 🐛 5 | 🌐 Go | 📅 2025-12-04 - Debugs serving gRPC applications with tools like channel trace info, xDS config dump, and health checking
* [gWhisper](https://github.com/IBM/gWhisper) ⭐ 62 | 🐛 28 | 🌐 C++ | 📅 2025-09-17 - Client with interactive tab-completion (uses reflection) and human readable format
* [proto-to-postman](https://github.com/sonatard/proto-to-postman) ⭐ 28 | 🐛 0 | 🌐 Go | 📅 2020-06-19 - Create postman API import collection from .proto files
* [gcall](https://github.com/bojand/gcall) ⭐ 12 | 🐛 1 | 🌐 JavaScript | 📅 2018-09-09 - Simple Node.js gRPC command line interface
* [proto2asciidoc](https://github.com/productsupcom/proto2asciidoc) ⭐ 6 | 🐛 2 | 🌐 Go | 📅 2022-04-21 - Generate AsciiDoc documentation from a .proto file
* [sylk](https://github.com/sylk-build/sylk) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2023-09-17 - A gRPC framework for building projects in **Python**, **Typescript** / **NodeJS** and **Go** from a simple CLI and powerful `Beta` UI platform
* [httpyac](https://httpyac.github.io/guide/installation_cli.html) - a command line client for executing integration tests for all kinds of requests (gRPC, HTTP, MQTT, Websocket).
* [grpcmd](https://grpc.md) - The "grpc" command: A simple, easy-to-use, and developer-friendly CLI tool for gRPC.

<a name="tools-gui"></a>

### GUI

* [grpcui](https://github.com/fullstorydev/grpcui) ⭐ 5,917 | 🐛 79 | 🌐 JavaScript | 📅 2026-08-17 - An interactive web UI for gRPC, along the lines of postman (also, a Go library for embedding these web UIs into Go HTTP servers)
* [Wombat](https://github.com/rogchap/wombat) ⭐ 1,431 | 🐛 39 | 🌐 Svelte | 📅 2024-07-11 - A cross platform gRPC client. Auto-generates input fields from your proto files or the gRPC reflection API. Not another Electron app - built with Qt and Go.
* [Milkman](https://github.com/warmuuh/milkman) ⭐ 1,340 | 🐛 16 | 🌐 Java | 📅 2026-08-04 - Extensible alternative to Postman for crafting all kinds of requests, not only for gRPC, also http, sql etc.
* [ezy](https://github.com/getezy/ezy) ⭐ 1,039 | 🐛 22 | 🌐 TypeScript | 📅 2024-05-26 - 🔥 Fully-featured GUI client for gRPC/gRPC-Web.
* [gRPCox](https://github.com/gusaul/grpcox) ⭐ 712 | 🐛 16 | 🌐 Go | 📅 2024-04-10 - Like Postman, but for gRPC. web based GUI Client for gRPC, extremely easy to use.
* [ptg](https://github.com/crossoverjie/ptg) ⭐ 324 | 🐛 5 | 🌐 Go | 📅 2022-07-11 - GUI gRPC client, it is also a performance testing tool.
* [(Yodelay.io)](https://github.com/oslabs-beta/Yodelay) ⭐ 229 | 🐛 4 | 🌐 TypeScript | 📅 2024-06-27 - A browser GUI Making sure your outbound 🗣️ ‘yodelay’ returns the ‘IiiOoo’ 📣 that you expect.
* [MuninRPC](https://github.com/muninrpc/muninrpc) ⭐ 128 | 🐛 5 | 🌐 TypeScript | 📅 2019-04-18 - Protobuf request and response testing application under the gRPC system.
* [Warthog](https://github.com/forest33/warthog) ⭐ 127 | 🐛 5 | 🌐 Go | 📅 2025-03-06 - A cross platform gRPC client. Input generation for all types, including nested and looped messages. Saving requests and servers.
* [Delivery](https://github.com/kfwerf/delivery) ⭐ 72 | 🐛 8 | 🌐 TypeScript | 📅 2023-05-14 - A simple electron app for gRPC that uses gRPCurl to autodetect all endpoints/methods and their request bodies, just modify the JSON body. Simplicity in mind.
* [Kalisto](https://github.com/Kalisto-Application/kalisto) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2024-02-26 - Automate and test intricate gRPC API workflows with ease using JavaScript-based scripting
* [Postman](https://postman.com/) - Create, test, and debug gRPC services directly from Postman
* [Kreya](https://kreya.app) - A gRPC and gRPC-web client supporting environments, templating, authentication schemes and file based syncing.
* [vscode-httpyac](https://httpyac.github.io/guide/installation_vscode.html) - A VSCode extension which supports sending all kinds of requests (gRPC, HTTP, MQTT, Websocket)
* [grpcmd-gui](https://grpc.md/gui) - A modern cross-platform desktop app and API client for gRPC development and testing.
* [Protocall](https://protocall.dev) - A browser-based gRPC & protobuf API client.  Integrates with Github and automatically resolves all proto imports with no manual configuration.
* [Grip](https://gripgrpc.dev) - Native macOS client for interacting with gRPC services

<a name="tools-test"></a>

### Testing

* [fortio](https://github.com/fortio/fortio) ⭐ 3,718 | 🐛 86 | 🌐 Go | 📅 2026-08-17 - A microservices (http, grpc) load testing library and tool from Istio project.
* [ghz](https://github.com/bojand/ghz) ⭐ 3,346 | 🐛 101 | 🌐 Go | 📅 2026-08-01 - Simple gRPC benchmarking and load testing tool inspired by hey and grpcurl.
* [Microcks](https://github.com/microcks/microcks) ⭐ 2,017 | 🐛 96 | 🌐 Java | 📅 2026-08-13 - A [Cloud Native Computing Sandbox project](https://landscape.cncf.io/?selected=microcks) 🚀 dedicated to API Mocking and Testing ([gRPC supported](https://microcks.io/documentation/using/grpc/))
* [Step CI](https://github.com/stepci/stepci) ⭐ 1,868 | 🐛 73 | 🌐 TypeScript | 📅 2024-08-03 - Open-Source API Testing and Monitoring (now with gRPC support!)
* [grpc-tools](https://github.com/bradleyjkemp/grpc-tools) ⭐ 1,238 | 🐛 39 | 🌐 Go | 📅 2023-11-14 - A suite of gRPC debugging tools. Like Fiddler/Charles but for gRPC.
* [grpc\_bench](https://github.com/LesnyRumcajs/grpc_bench) ⭐ 936 | 🐛 33 | 🌐 Dockerfile | 📅 2026-06-22 - A suite of gRPC benchmarks for different technologies.
* [grpc-swagger](https://github.com/grpc-swagger/grpc-swagger) ⭐ 441 | 🐛 14 | 🌐 Java | 📅 2023-06-30 - Debugging gRPC application with swagger-ui.
* [camouflage](https://github.com/testinggospels/camouflage) ⭐ 294 | 🐛 30 | 🌐 TypeScript | 📅 2025-05-19 - Camouflage is a backend mocking tool for HTTP, gRPC and Websockets protocols.
* [Mediator](https://github.com/ButterCam/Mediator) ⭐ 182 | 🐛 10 | 🌐 Kotlin | 📅 2023-10-27 - Cross-platform GUI gRPC debugging proxy like charles but design for gRPC.
* [grpcdump](https://github.com/rmedvedev/grpcdump) ⭐ 160 | 🐛 8 | 🌐 Go | 📅 2022-06-25 - Tool for capture and decode GRPC messages from ethernet traffic only for Linux
* [strest-grpc](https://github.com/BuoyantIO/strest-grpc) ⭐ 90 | 🐛 7 | 🌐 Go | 📅 2020-06-17 - A load tester for stress testing grpc intermediaries.
* [hazana](https://github.com/emicklei/hazana) ⭐ 74 | 🐛 2 | 🌐 Go | 📅 2025-08-26 - A Go package for creating load test tooling. Supports gRPC.
* [jmeter-grpc-plugin](https://github.com/zalopay-oss/jmeter-grpc-plugin) ⭐ 44 | 🐛 12 | 🌐 Java | 📅 2023-06-14 - A plugin supports load test gRPC service with Jmeter.
* [karate-grpc](https://github.com/karatelabs/karate-examples/blob/main/grpc) ⭐ 38 | 🐛 0 | 🌐 Java | 📅 2026-04-11 - Example of using [Karate](https://github.com/karatelabs/karate) ⭐ 8,924 | 🐛 1 | 🌐 Java | 📅 2026-08-17 to integrate and test gRPC.
* [nosymouse](https://nosymouse.io/) - Saas tool to functional, perfomance and secure testing gRPC
* [grpcmd-script](https://grpc.md/script) - A powerful framework for testing gRPC endpoints using JavaScript within a single binary executable
* [Keploy](https://github/keploy/keploy) - Keploy is developer-centric API testing tool that creates tests along with built-in-mocks, faster than unit tests. ([gRPC supported](https://keploy.io/docs/keploy-explained/api-testing-faq/#3-what-protocols-and-formats-does-keploy-support))

<a name="tools-other"></a>

### Other

* [APISIX](https://github.com/apache/apisix) ⭐ 17,003 | 🐛 242 | 🌐 Lua | 📅 2026-08-18 - An api gateway that supports gRPC, HTTP(s) to gRPC and gRPC web request proxying.
* [ratelimit](https://github.com/lyft/ratelimit) ⭐ 2,684 | 🐛 38 | 🌐 Go | 📅 2026-08-17 - Go/gRPC service designed to enable generic rate limit scenarios from different types of applications
* [Zilla](https://github.com/aklivity/zilla) ⭐ 1,297 | 🐛 224 | 🌐 Java | 📅 2026-08-18 - An API gateway built for event-driven architectures and streaming that supports standard protocols such as HTTP, SSE, gRPC, MQTT and the native Kafka protocol.
* [grpc-proxy](https://github.com/mwitkow/grpc-proxy) ⭐ 1,048 | 🐛 35 | 🌐 Go | 📅 2026-03-18 - gRPC reverse proxy with the goal of making it easy to expose gRPC services over the internet
* [kafka-pixy](https://github.com/mailgun/kafka-pixy) ⭐ 789 | 🐛 17 | 🌐 Go | 📅 2024-04-23 - gRPC/REST proxy for Kafka
* [docker-protoc](https://github.com/namely/docker-protoc) ⭐ 743 | 🐛 40 | 🌐 Shell | 📅 2026-06-09 - Dockerized protoc, grpc-gateway, and grpc\_cli commands bundled with Google API libraries
* [grpc-json-proxy](https://github.com/jnewmano/grpc-json-proxy) ⭐ 516 | 🐛 12 | 🌐 Go | 📅 2026-08-17 - A proxy which allows existing tools like Postman or curl to interact with gRPC servers
* [protoc-gen-gotemplate](https://github.com/moul/protoc-gen-gotemplate) ⭐ 441 | 🐛 26 | 🌐 Go | 📅 2026-08-18 - Generic generator based on golang's template system
* [grpc-http-proxy](https://github.com/mercari/grpc-http-proxy) ⭐ 372 | 🐛 8 | 🌐 Go | 📅 2023-07-05 - A reverse proxy server which translate JSON HTTP requests to gRPC calls based on protoreflect
* [grpc-pentest-suite](https://github.com/nxenon/grpc-pentest-suite) ⭐ 260 | 🐛 0 | 🌐 Python | 📅 2026-06-13 - A collection of tools for pentesting gRPC-Web, including a Burp Suite extension for manipulating gRPC-Web payloads.
* [sabledocs](https://github.com/markvincze/sabledocs) ⭐ 94 | 🐛 9 | 🌐 CSS | 📅 2026-05-09 - A simple static documentation generator for Protobuf and gRPC contracts.
* [limitador](https://github.com/Kuadrant/limitador) ⭐ 88 | 🐛 36 | 🌐 Rust | 📅 2026-08-07 - Generic rate-limiter written in Rust exposing a gRPC service that implements the Envoy Rate Limit protocol (v3).
* [rk-grpc](https://github.com/rookie-ninja/rk-grpc) ⭐ 81 | 🐛 4 | 🌐 Go | 📅 2023-10-31 - Middleware and bootstrapper library for gRPC with logging, metrics, auth, tracing etc.
* [grpc-mate](https://github.com/gdong42/grpc-mate) ⭐ 75 | 🐛 9 | 🌐 Go | 📅 2019-07-05 - A dynamic proxy server that translates JSON HTTP requests into gRPC calls
* [danby](https://github.com/ericbets/danby) ⭐ 32 | 🐛 5 | 🌐 JavaScript | 📅 2022-12-10 - A grpc proxy for the browser
* [jawlb](https://github.com/joa/jawlb) ⭐ 14 | 🐛 2 | 🌐 Go | 📅 2023-08-30 - An unsophisticated grpclb load balancer implementation for Kubernetes and gRPC
* [protoc-gen-hbs](https://github.com/gponsinet/protoc-gen-hbs) ⭐ 9 | 🐛 11 | 🌐 JavaScript | 📅 2026-04-02 - Fast and easy protobuf generation with handlebars and some helpers
* [grpcson](https://github.com/siyanew/grpcson) ⭐ 5 | 🐛 1 | 🌐 HTML | 📅 2021-08-16 - An easy to use proxy which translates JSON HTTP requests to gRPC calls with web ui
* [ProfaneDB](https://gitlab.com/ProfaneDB/ProfaneDB) - A Protocol Buffers database with gRPC API, built in C++ on top of RocksDB
* [PropaneDB](https://github.com/elan8/propanedb) - A Protocol Buffers database with gRPC API and Golang driver.

<a name="lang"></a>

## Language-Specific

<a name="lang-go"></a>

### Go

* [go-kit gRPC](https://github.com/go-kit/kit/tree/master/transport/grpc) ⭐ 27,417 | 🐛 60 | 🌐 Go | 📅 2024-07-19 - [Go Kit](https://github.com/go-kit) with gRPC as transport
* [rpcx](https://github.com/smallnest/rpcx) ⭐ 8,310 | 🐛 3 | 🌐 Go | 📅 2026-07-10 - A RPC service framework based on net/rpc like alibaba Dubbo and weibo Motan
* [grpcui](https://github.com/fullstorydev/grpcui) ⭐ 5,917 | 🐛 79 | 🌐 JavaScript | 📅 2026-08-17 - Embed a gRPC web UI into a Go gRPC/HTTP server
* [cmux](https://github.com/soheilhy/cmux) ⭐ 2,765 | 🐛 36 | 🌐 Go | 📅 2026-06-08 - Connection multiplexer for GoLang: serve different services on the same port! Supports gRPC.
* [lile](https://github.com/lileio/lile) ⭐ 1,497 | 🐛 6 | 🌐 Go | 📅 2023-07-19 - Easily create gRPC services in Go
* [protoreflect](https://github.com/jhump/protoreflect) ⭐ 1,487 | 🐛 12 | 🌐 Go | 📅 2026-07-29 - Reflection (Rich Descriptors) for Go Protocol Buffers
* [grpc-proxy](https://github.com/mwitkow/grpc-proxy) ⭐ 1,048 | 🐛 35 | 🌐 Go | 📅 2026-03-18 - gRPC proxy is a Go reverse proxy that allows for rich routing of gRPC calls with minimum overhead
* [gripmock](https://github.com/tokopedia/gripmock) ⭐ 747 | 🐛 55 | 🌐 Go | 📅 2026-03-19 - gRPC Mock Server
* [gRPC over NATS](https://github.com/rapidloop/nrpc) ⭐ 706 | 🐛 14 | 🌐 Go | 📅 2026-03-24 - nRPC is an RPC framework like gRPC, but for NATS.
* [Mortar](https://github.com/go-masonry/mortar) ⭐ 677 | 🐛 0 | 🌐 Go | 📅 2025-05-13 - GO framework for building gRPC (and REST) web services with DI, Telemetry and more
* [ttrpc](https://github.com/containerd/ttrpc) ⭐ 659 | 🐛 30 | 🌐 Go | 📅 2026-07-25 - GRPC for low-memory environments
* [kuberesolver](https://github.com/sercand/kuberesolver) ⭐ 639 | 🐛 8 | 🌐 Go | 📅 2026-04-01 - gRPC Load Balancer with Kubernetes resolver
* [grpc-gateway-boilerplate](https://github.com/johanbrandhorst/grpc-gateway-boilerplate) ⭐ 497 | 🐛 2 | 🌐 Go | 📅 2023-09-18 - All the boilerplate you need to get started with writing grpc-gateway powered REST services in Go
* [grpc-web-devtools](https://github.com/SafetyCulture/grpc-web-devtools) ⭐ 441 | 🐛 58 | 🌐 JavaScript | 📅 2025-07-25 - Chrome Browser extension to aid gRPC-Web development
* [yarpc](https://github.com/yarpc/yarpc-go) ⭐ 440 | 🐛 56 | 🌐 Go | 📅 2026-08-17 - A message passing platform for Go, including support for gRPC
* [grapi](https://github.com/izumin5210/grapi) ⭐ 429 | 🐛 35 | 🌐 Go | 📅 2025-06-16 - 😮 A surprisingly easy API server and generator in gRPC and Go
* [grpc-consul-resolver](https://github.com/mbobakov/grpc-consul-resolver) ⭐ 353 | 🐛 12 | 🌐 Go | 📅 2026-04-25 - Easy to use endpoints resolver for the services registered in the [Consul](https://www.consul.io/)
* [Pike](https://github.com/sashabaranov/pike) ⭐ 313 | 🐛 0 | 🌐 Go | 📅 2022-06-16 — Generate CRUD gRPC backends from single YAML description
* [clay](https://github.com/utrack/clay) ⭐ 295 | 🐛 15 | 🌐 Go | 📅 2025-12-05 - Minimal server platform for gRPС+REST+Swagger APIs
* [grpchan](https://github.com/fullstorydev/grpchan) ⭐ 229 | 🐛 2 | 🌐 Go | 📅 2026-08-14 - Channels for gRPC: custom transports, such as in-process and HTTP 1.1
* [gRPC for production](https://github.com/apssouza22/grpc-server-go) ⭐ 220 | 🐛 0 | 🌐 Go | 📅 2022-02-28 - A Golang project that provides the core requirements for a production-ready gRPC communication.
* [protoc-gen-struct-transformer](https://github.com/bold-commerce/protoc-gen-struct-transformer) ⚠️ Archived - Transformation function generator for protocol buffers.
* [sqlc-grpc](https://github.com/walterwanderley/sqlc-grpc) ⭐ 158 | 🐛 3 | 🌐 Go | 📅 2026-06-12 - Generate gRPC/HTTP server (with metrics, tracing, swagger and grpcui) from SQL
* [Thunder Framework](https://github.com/Raezil/Thunder) ⭐ 122 | 🐛 0 | 🌐 Go | 📅 2025-12-05 - A gRPC-Gateway-powered framework with Prisma, Kubernetes, and Go for scalable microservices.
* [goprotoc](https://github.com/jhump/goprotoc) ⭐ 89 | 🐛 3 | 🌐 Go | 📅 2025-06-10 - Library for writing protoc plugins in Go; also includes a pure-Go protoc replacement.
* [promgrpc](https://github.com/piotrkowalczuk/promgrpc) ⭐ 56 | 🐛 3 | 🌐 Go | 📅 2026-03-18 - Prometheus instrumentation for gRPC based services
* [protoc-gen-mock](https://github.com/carvalhorr/protoc-gen-mock) ⭐ 49 | 🐛 18 | 🌐 Go | 📅 2021-04-15 - A protoc plugin to generate gRPC mock services from proto definitions in Golang
* [go-grpc-channelz](https://github.com/rantav/go-grpc-channelz) ⭐ 44 | 🐛 7 | 🌐 Go | 📅 2023-12-02 - A channelz UI for Golang. Channelz is an approved and already implemented proposal describing the inner state of gRPC connections/channels. go-grpc-channelz provides a simple UI for channelz for easy diagnosis.
* [gRPC over WebSocket](https://github.com/glerchundi/grpc-boomerang) ⭐ 37 | 🐛 0 | 🌐 Go | 📅 2017-10-27 - connect to a gRPC Server behind a firewall by using a pre-established WebSocket connection
* [protoc-gen-fieldmask](https://github.com/idodod/protoc-gen-fieldmask) ⭐ 30 | 🐛 13 | 🌐 Go | 📅 2026-08-17 - A protoc plugin that generates fieldmask paths as static type properties of proto messages
* [protoc-gen-go-mock](https://github.com/kw510/protoc-gen-go-mock) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2024-01-11 - A protoc plugin for generating minimal gRPC service mocks suitable for use in tests.

<a name="lang-nodejs"></a>

### Node.js

* [Mali](https://github.com/malijs/mali) ⭐ 889 | 🐛 15 | 🌐 JavaScript | 📅 2024-05-15 - A minimalistic gRPC microservice framework for Node.js
* [firecomm](https://github.com/firecomm/firecomm) ⭐ 224 | 🐛 16 | 🌐 JavaScript | 📅 2026-08-04 - Feature library for gRPC-Node
* [grpc-caller](https://github.com/bojand/grpc-caller) ⭐ 185 | 🐛 21 | 🌐 JavaScript | 📅 2023-08-18 - An improved Node.js gRPC client
* [grpc-dynamic-gateway](https://github.com/konsumer/grpc-dynamic-gateway) ⭐ 110 | 🐛 11 | 🌐 JavaScript | 📅 2021-02-12 - Like grpc-gateway, but written in node and dynamic.
* [grpc-promise](https://github.com/carlessistare/grpc-promise) ⭐ 81 | 🐛 5 | 🌐 JavaScript | 📅 2019-10-30 - GRPC promisify module for all Request/Response types: standard and stream
* [Node.js Proto Files](https://github.com/googleapis/nodejs-proto-files) ⚠️ Archived - All of the Google API's protocol buffer files
* [node-protoc-plugin](https://github.com/konsumer/node-protoc-plugin) ⭐ 26 | 🐛 0 | 🌐 Protocol Buffer | 📅 2017-04-20 - Create protoc code-generation plugins easily in nodejs.
* [grpc-reflection-js](https://github.com/redhoyasa/grpc-reflection-js) ⭐ 21 | 🐛 17 | 🌐 JavaScript | 📅 2024-08-03 – gRPC Reflection client for JS
* [grpc-inspect](https://github.com/bojand/grpc-inspect) ⭐ 10 | 🐛 1 | 🌐 JavaScript | 📅 2019-02-05 - gRPC protocol buffer inspection utility
* [grpc-create-error](https://github.com/bojand/grpc-create-error) ⭐ 8 | 🐛 6 | 🌐 JavaScript | 📅 2023-03-04 - Utility function for creating `Errors` for gRPC responses
* [grpc-create-metadata](https://github.com/bojand/grpc-create-metadata) ⭐ 5 | 🐛 6 | 🌐 JavaScript | 📅 2023-03-04 - Helper utility for creating gRPC `Metadata`
* [grpc-error](https://github.com/bojand/grpc-error) ⭐ 4 | 🐛 2 | 🌐 JavaScript | 📅 2022-12-30 - `GRPCError` class that wraps `create-grpc-error`
* [grpc-errors](https://github.com/ortoo/grpc-errors) ⭐ 4 | 🐛 9 | 🌐 JavaScript | 📅 2026-01-24 - A quick and easy way of generating errors for use with grpc

<a name="lang-java"></a>

### Java

* [Armeria](https://github.com/line/armeria) ⭐ 5,133 | 🐛 701 | 🌐 Java | 📅 2026-08-18 - Asynchronous RPC/REST library built on top of Java 8, Netty, HTTP/2, Thrift and gRPC
* [grpc-spring-boot-starter](https://github.com/grpc-ecosystem/grpc-spring) ⭐ 3,710 | 🐛 172 | 🌐 Java | 📅 2026-07-30 - Spring Boot starter module for gRPC framework
* [grpc-spring-boot-starter](https://github.com/LogNet/grpc-spring-boot-starter) ⭐ 2,258 | 🐛 55 | 🌐 Java | 📅 2025-11-13 Spring Boot starter module for gRPC framework from LogNet.
* [grpc-java-contrib](https://github.com/salesforce/grpc-java-contrib) ⭐ 221 | 🐛 15 | 🌐 Java | 📅 2026-06-02 - Useful extensions for the grpc-java library
* [grpcmock](https://github.com/Fadelis/grpcmock) ⭐ 158 | 🐛 2 | 🌐 Java | 📅 2026-04-23 - A gRPC Java testing tool to easily mock endpoints of gRPC services for IT or Unit testing
* [gax-java](https://github.com/googleapis/sdk-platform-java/tree/main/gax-java) ⚠️ Archived - Google API Extensions for Java
* [protoc-gen-java-optional](https://github.com/Fadelis/protoc-gen-java-optional) ⭐ 8 | 🐛 0 | 🌐 Java | 📅 2023-10-27 - A Java Protoc plugin extending generated java classes with null safe `setOrClear` and `getOptional` methods.
* [hoverfly-java-grpc](https://mvnrepository.com/artifact/io.specto/hoverfly-java-grpc) - MITM proxy for recording and simulating gRPC services
* [Vert.x gRPC](https://vertx.io/docs/vertx-grpc/java) - Asynchronous, non-blocking gRPC server and client built with the Vert.x HTTP server and client. It helps you create gRPC applications using a low-level message API or generated stubs.

<a name="lang-ruby"></a>

### Ruby

* [gruf](https://github.com/bigcommerce/gruf) ⭐ 650 | 🐛 21 | 🌐 Ruby | 📅 2026-02-20 - gRPC Ruby Framework
* [gapic-generator-ruby](https://github.com/googleapis/gapic-generator-ruby) ⭐ 50 | 🐛 39 | 🌐 Ruby | 📅 2026-08-11 - Generates Ruby gRPC client libraries from protocol buffer definitions of an API.

<a name="lang-py"></a>

### Python

* [betterproto](https://github.com/danielgtaylor/python-betterproto) ⭐ 1,769 | 🐛 179 | 🌐 Python | 📅 2025-07-17 - More pythonic gRPC based on grpclib and dataclasses
* [grpclib](https://github.com/vmagamedov/grpclib) ⭐ 985 | 🐛 47 | 🌐 Python | 📅 2025-12-14 - Pure-Python gRPC implementation, based on hyper-h2 project
* [django-grpc-framework](https://github.com/fengsp/django-grpc-framework) ⭐ 407 | 🐛 29 | 🌐 Python | 📅 2022-12-10 - A gRPC toolkit for Django inspired by djangorestframework
* [Bali](https://github.com/bali-framework/bali) ⭐ 367 | 🐛 10 | 🌐 Python | 📅 2025-09-10 - Simplify Cloud Native Microservices development base on FastAPI and gRPC.
* [django-grpc](https://github.com/gluk-w/django-grpc) ⭐ 244 | 🐛 3 | 🌐 Python | 📅 2026-08-18 - Django application to build gRPC services with access to ORM, settings and everything else
* [pytest-grpc](https://github.com/kataev/pytest-grpc) ⭐ 134 | 🐛 10 | 🌐 Python | 📅 2024-05-31 - pytest plugin which allow test gRPC services
* [grpcalchemy](https://github.com/GuangTianLi/grpcalchemy) ⭐ 88 | 🐛 1 | 🌐 Python | 📅 2024-09-12 - The Python micro framework for building gPRC application
* [Fast-gRPC](https://github.com/OlegYurchik/fast-grpc) ⭐ 50 | 🐛 0 | 🌐 Python | 📅 2025-09-20 - The Python async micro framework for easy develop gRPC server
* [grpc\_requests](https://github.com/wesky93/grpc_requests) ⭐ 42 | 🐛 12 | 🌐 Python | 📅 2026-04-27 - GRPC for Humans! grpc reflection support client. you can request grpc just like REST(No need Stub!)
* [garuda](https://github.com/dhilipsiva/garuda) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2023-04-26 - Automagically Exposing Django ORM over gRPC for microservices written in any other languages

<a name="lang-cs"></a>

### C\#

* [MagicOnion](https://github.com/neuecc/MagicOnion) ⭐ 4,440 | 🐛 9 | 🌐 C# | 📅 2026-08-14 - gRPC based HTTP/2 RPC Streaming Framework for .NET, .NET Core and Unity
* [GrpcBrowser](https://github.com/thomaswormald/grpc-browser) ⭐ 27 | 🐛 2 | 🌐 C# | 📅 2025-10-17 - a web UI for interactively debugging all types of gRPC endpoints
* [Grpc.Tools](https://www.nuget.org/packages/Grpc.Tools/) - gRPC and Protocol Buffer compiler for managed C# and native C++ projects. See [Introduction to gRPC on .NET Core](https://docs.microsoft.com/en-us/aspnet/core/grpc/?view=aspnetcore-3.0) tutorial.

<a name="lang-rust"></a>

### Rust

* [tonic](https://github.com/hyperium/tonic) ⭐ 12,432 | 🐛 389 | 🌐 Rust | 📅 2026-08-18 - A native gRPC client & server implementation with async/await support
* [grpc-rs](https://github.com/pingcap/grpc-rs) ⭐ 1,852 | 🐛 108 | 🌐 Rust | 📅 2026-07-04 - The gRPC library for Rust built on C Core library and futures
* [wtx](https://github.com/c410-f3r/wtx) ⭐ 397 | 🐛 8 | 🌐 Rust | 📅 2026-08-14 - RFC7541 and RFC9113 implementation with built-in support for `gRPC` connections.

<a name="lang-hs"></a>

### Haskell

* [grpc-haskell](https://github.com/grpc/grpc-haskell) ⭐ 157 | 🐛 8 | 🌐 Haskell | 📅 2018-08-31 - gRPC library binding for Haskell

<a name="lang-erlang"></a>

### Erlang

* [grpcbox](https://github.com/tsloughter/grpcbox) ⭐ 147 | 🐛 40 | 🌐 Erlang | 📅 2026-07-11 - Erlang grpc client and server
* [Erlang grpc](https://github.com/bluehouse-technology/grpc) ⭐ 101 | 🐛 7 | 🌐 Erlang | 📅 2023-07-29 - Erlang library for gRPC
* [bert](https://github.com/synrc/bert) ⭐ 19 | 🐛 4 | 🌐 Erlang | 📅 2026-06-01 - Erlang Google Protobuf V3 generator from HRL files

<a name="lang-elixir"></a>

### Elixir

* [grpc-elixir](https://github.com/tony612/grpc-elixir) ⭐ 1,519 | 🐛 41 | 🌐 Elixir | 📅 2026-08-15 - The Elixir implementation of gRPC

<a name="lang-elm"></a>

### Elm

* [elm-protobuf](https://github.com/tiziano88/elm-protobuf) ⭐ 94 | 🐛 10 | 🌐 Elm | 📅 2022-11-14 - Protoc plugin generating elm code from proto definitions

<a name="lang-ts"></a>

### TypeScript

* [ts-proto](https://github.com/stephenh/ts-proto) ⭐ 2,587 | 🐛 172 | 🌐 TypeScript | 📅 2026-07-03 - Transforms your .proto files into strongly-typed, idiomatic TypeScript files!
* [ts-protoc-gen](https://github.com/improbable-eng/ts-protoc-gen) ⭐ 1,395 | 🐛 49 | 🌐 TypeScript | 📅 2026-01-21 - Protoc Plugin for TypeScript Declarations
* [protobuf-ts](https://github.com/timostamm/protobuf-ts) ⭐ 1,343 | 🐛 81 | 🌐 TypeScript | 📅 2026-07-22 - Protoc plugin and runtime for TypeScript. Generates gRPC server/client for Node.js, gRPC-Web/Twirp clients for browser, uses Fetch API.
* [nice-grpc](https://github.com/deeplay-io/nice-grpc) ⭐ 538 | 🐛 17 | 🌐 TypeScript | 📅 2026-08-04 - gRPC library for Node.js and the Browser with modern API and middleware support.
* [grpc-js-typescript](https://github.com/badsyntax/grpc-js-typescript) ⭐ 204 | 🐛 13 | 📅 2025-09-18 - Examples of how to use gRPC with TypeScript & Node.js.
* [protoc-gen-grpc-gateway-ts](https://github.com/grpc-ecosystem/protoc-gen-grpc-gateway-ts) ⭐ 161 | 🐛 23 | 🌐 Go | 📅 2023-03-24 - TypeScript client generator for the grpc-gateway project that generates idiomatic TypeScript clients that connect the web frontend and golang backend fronted by grpc-gateway.
* [sisyphus.js](https://github.com/ButterCam/sisyphus-js) ⭐ 24 | 🐛 4 | 🌐 TypeScript | 📅 2023-09-08 - gRPC runtime and compiler for Web Clients by HTTP transcoding. Recommend using with [Sisyphus](https://github.com/ButterCam/sisyphus) ⭐ 99 | 🐛 9 | 🌐 Kotlin | 📅 2024-04-08 back-end framework.
* [protoc-gen-tstypes](https://godoc.org/github.com/tmc/grpcutil/protoc-gen-tstypes) - Configurable Protoc Plugin to generate TypeScript types.

<a name="lang-scala"></a>

### Scala

* [fs2-grpc](https://github.com/typelevel/fs2-grpc) ⭐ 284 | 🐛 18 | 🌐 Scala | 📅 2026-08-09 - gRPC implementation for FS2/cats-effect using netty
* [zio-grpc](https://github.com/scalapb/zio-grpc) ⭐ 273 | 🐛 50 | 🌐 Scala | 📅 2026-05-07 - ScalaPB meets ZIO: write purely functional gRPC services and clients using ZIO
* [http4s-grpc](https://github.com/http4s/http4s-grpc) ⭐ 49 | 🐛 8 | 🌐 Scala | 📅 2026-08-08 - A pure Scala gRPC implementation! Use it with http4s Ember and deploy on JVM, Node.js, and Native.
* [ScalaPB](https://scalapb.github.io/) - Protocol Buffer Compiler for Scala
* [Akka-gRPC](https://developer.lightbend.com/docs/akka-grpc/current/) - Akka gRPC provides support for building streaming gRPC servers and clients on top of Akka Streams.
* [Mu](https://higherkindness.github.io/mu/) - Mu RPC is a purely functional library for building RPC endpoint-based services with support for gRPC and HTTP/2

<a name="lang-dart"></a>

### Dart

* [grpc-dart](https://pub.dartlang.org/packages/grpc) - Protocol Buffer Compiler for Dart

<a name="lang-kotlin"></a>

### Kotlin

* [kroto-plus](https://github.com/marcoferrer/kroto-plus) ⭐ 492 | 🐛 32 | 🌐 Kotlin | 📅 2020-12-18 - gRPC Coroutines Integration and Protobuf message DSL support
* [grpc-kotlin](https://github.com/rouzwawi/grpc-kotlin) ⭐ 219 | 🐛 9 | 🌐 Kotlin | 📅 2022-06-20 - A protoc plugin for generating native Kotlin bindings using coroutine primitives for gRPC services
* [sisyphus](https://github.com/ButterCam/sisyphus) ⭐ 99 | 🐛 9 | 🌐 Kotlin | 📅 2024-04-08 - Modern gRPC back-end development framework based on Kotlin/Spring Boot with Message DSL/[HTTP transcoding](https://aip.bybutter.com/127)/[Google AIP](https://aip.bybutter.com) support.

<a name="lang-perl"></a>

### Perl

* [grpc-perl](https://github.com/joyrex2001/grpc-perl) ⭐ 35 | 🐛 4 | 🌐 Perl | 📅 2026-07-24 - Experimental Perl gRPC library supporting grpc client

### C++

<a name="lang-cpp"></a>

* [asio-grpc](https://github.com/Tradias/asio-grpc) ⭐ 471 | 🐛 1 | 🌐 C++ | 📅 2026-03-31 - Asynchronous gRPC with [Boost.Asio](https://github.com/boostorg/asio) ⭐ 1,602 | 🐛 90 | 🌐 C++ | 📅 2026-08-12 or [libunifex](https://github.com/facebookexperimental/libunifex) ⭐ 1,712 | 🐛 104 | 🌐 C++ | 📅 2026-05-31
* [qtgrpc](https://github.com/qt/qtgrpc) ⭐ 25 | 🐛 0 | 🌐 C++ | 📅 2026-08-18 - gRPC and Protobuf generator and bindings for the Qt framework
* [sugar-proto](https://github.com/illegal-instruction-co/sugar-proto) ⭐ 18 | 🐛 0 | 🌐 C++ | 📅 2025-09-21 - A Protobuf wrapper with expressive, minimal, and strongly-typed C++ syntax, close to plain structs.

<a name="lang-ballerina"></a>

### Ballerina

* [Ballerina gRPC](https://github.com/ballerina-platform/module-ballerina-grpc) ⭐ 123 | 🐛 0 | 🌐 Ballerina | 📅 2026-08-05 - Ballerina library for gRPC
* [Ballerina gRPC CLI](https://github.com/ballerina-platform/protoc-tools) ⭐ 103 | 🐛 3 | 🌐 Ballerina | 📅 2026-07-19 - Ballerina gRPC CLI tool

## Resources

<a name="res-tuts"></a>

### Tutorials

* [How to develop Go gRPC microservice with HTTP/REST endpoint, middleware, Kubernetes deployment, etc](https://medium.com/@amsokol.com/tutorial-how-to-develop-go-grpc-microservice-with-http-rest-endpoint-middleware-kubernetes-daebb36a97e9) - A series of blog posts for gRPC development using Go. [Source code](https://github.com/amsokol/go-grpc-http-rest-microservice-tutorial) ⭐ 318 | 🐛 5 | 📅 2019-03-27.
* [The G-Unit Stack: Go, GraphQL, and gRPC](https://iheanyi.com/journal/2018/05/12/the-g-unit-stack-go-graphql-and-grpc/) - A blog post and tutorial on using Go, GraphQL and gRPC. Associated [repo](https://github.com/iheanyi/go-grpc-graphql-simple-example) ⭐ 76 | 🐛 1 | 🌐 Go | 📅 2018-07-21.
* [Getting Started with Microservices using Go, gRPC and Kubernetes](https://outcrawl.com/getting-started-microservices-go-grpc-kubernetes/)
* [gRPC in Production](https://about.sourcegraph.com/blog/grpc-in-production-alan-shreve/)
* [gRPC Go: Beyond the basics](https://blog.gopheracademy.com/advent-2017/go-grpc-beyond-basics/) - GopherAcademy article
* [Building High Performance APIs In Go Using gRPC](http://www.agiratech.com/building-high-performance-apis-go-grpc/) - Small tutorial on building a simple API using gRPC and Go
* [Bidirectional gRPC streaming for Go](https://rakyll.org/grpc-streaming/)
* [How We Build gRPC Services At Namely](https://medium.com/namely-labs/how-we-build-grpc-services-at-namely-52a3ae9e7c35) - Blog article from Namely Labs
* [Our experience designing and building gRPC services](https://blog.bugsnag.com/using-grpc-in-production/) - Blog series from Bugsnag on building a new Releases dashboard backend using gRPC
* [Writing gRPC Interceptors in Go](https://medium.com/@shijuvar/writing-grpc-interceptors-in-go-bf3e7671fe48) - A simple tutorial on gRPC Interceptors
* [An introduction to gRPC](https://devopedia.org/grpc)
* [How we use gRPC to build a client/server system in Go](https://medium.com/pantomath/how-we-use-grpc-to-build-a-client-server-system-in-go-dd20045fa1c2) - A technical presentation on how to use gRPC (and Protobuf) to build a robust client/server system
* [OpenCensus for Go gRPC developers](https://medium.com/@orijtech/opencensus-for-go-grpc-developers-7f3ee1ac3d6d) - Tutorial on how to use OpenCensus with gRPC and Go. Also available for [Java](https://medium.com/@orijtech/opencensus-for-java-grpc-developers-23c25de0a057) and [Python](https://medium.com/@orijtech/opencensus-for-python-grpc-developers-9e460e054395).
* [GopherJS Client and gRPC Server](https://jbrandhorst.com/post/gopherjs-client-grpc-server/) - A guide to implementing a GopherJS frontend to a gRPC backend exposed over HTTP via the gRPC-gateway. Also available [related gRPC-Web with GopherJS tutorial](https://jbrandhorst.com/post/gopherjs-grpcweb/).
* [Envoy, gRPC, and Rate Limiting](https://venilnoronha.io/envoy-grpc-and-rate-limiting) - A tutorial on using gRPC and Envoy to build a rate limit service - [Venil Noronha](https://venilnoronha.io), VMware Open Source Technology Center
* [Seamless Cloud-Native Apps with gRPC-Web and Istio](https://venilnoronha.io/seamless-cloud-native-apps-with-grpc-web-and-istio) - A tutorial on building a Cloud-Native web app using gRPC-Web and Istio - [Venil Noronha](https://venilnoronha.io), VMware Open Source Technology Center
* [Backward and Forward Compatibility, Protobuf Versioning, Serialization](https://www.beautifulcode.co/backward-and-forward-compatibility-protobuf-versioning-serialization) - A small article on making gRPC API changes
* [Node, gRPC, and Postgres](https://mherman.org/blog/node-grpc-postgres/) - This tutorial looks at how to implement an API with Node, gRPC, and Postgres.
* [Building High Performance APIs In Go Using gRPC And Protocol Buffers](https://medium.com/@shijuvar/building-high-performance-apis-in-go-using-grpc-and-protocol-buffers-2eda5b80771b) - An introductory gRPC Go tutorial.
* [Part 1: Demystifying gRPC](https://dev-state.com/posts/grpc_framework_1/) - A simple gRPC service with context cancelation and secure connection over SSL/TLS.
* [Part 2: Demystifying gRPC](https://dev-state.com/posts/grpc_framework_2/) - Extend the service with gRPC streaming and Python backend.
* [Part 3: Demystifying gRPC](https://dev-state.com/posts/grpc_framework_3/) - Add Unary and Stream gRPC Interceptors to a service and provide REST endpoints with grpc-gateway.
* [gRPC in Microservices](https://milad.dev/posts/grpc-in-microservices/) - Tutorial on using gRPC in microservice architetures.
* [gRPC and Protobuffer API Documentation with proto2asciidoc and code2asciidoc](https://blog.productsup.dev/2020/05/grpc-and-protobuffer-api-documentation-with-proto2asciidoc-and-code2asciidoc/) - Tutorial on generating AsciiDoc documentation from a .proto file, includes a small gRPC demo project too.
* [gRPC: Top 6 Things that Bite Newbies](https://charles-thayer.medium.com/grpc-top-6-things-that-bite-newbies-dfa740ffc67d) - A review of stumbling blocks for those moving to gRPC for the first time.
* [A beginners guide to gRPC with Rust](https://dev.to/anshulgoyal15/a-beginners-guide-to-grpc-with-rust-3c7o)
* [Writing a gRPC service with Ballerina](https://ballerina.io/learn/write-a-grpc-service-with-ballerina/) - Getting started guide on building a simple gRPC service with Ballerina and invoking the service through a Ballerina gRPC client application.
* [gRPC-web: Using gRPC in Your Front-End Application](https://grpcguide.com/grpc-web-frontend) - A tutorial on using gRPC-web in a frontend application.
* [Load balancing gRPC in Kubernetes with a service mesh](https://www.useanvil.com/blog/engineering/load-balancing-grpc-in-kubernetes-with-istio) - Explains issues load balancing gRPC, then employs a service mesh (istio) to L7 load balance a gRPC service in Kubernetes.
* [RPC Adoption and Working Architecture](https://www.xenonstack.com/insights/what-is-grpc) - Overview of gRPC and comparison with REST and WebSockets.
* [Protobuf Editions explained](https://kreya.app/blog/protobuf-editions-explained/) - Detailed explanation of Protobuf editions

<a name="res-videos"></a>

### Videos

* [Building Microservices with Go](https://www.youtube.com/playlist?list=PLmD8u-IFdreyh6EUfevBcbiuCKzFk0EW_) - A series of tutorials for building microservices with Go, covers using gRPC ([source](https://github.com/nicholasjackson/building-microservices-youtube) ⭐ 1,168 | 🐛 46 | 🌐 Go | 📅 2024-07-14).
* [gRPC Loadbalancing on Kubernetes](https://www.youtube.com/watch?v=F2znfxn_5Hg) - Presentation at KubeCon Europe 2018. [Source](https://github.com/jtattermusch/grpc-loadbalancing-kubernetes-examples) ⭐ 249 | 🐛 3 | 🌐 C# | 📅 2022-02-11.
* [gRPC: Google's high-performance, open-source RPC framework](https://www.youtube.com/watch?v=sZx3oZt7LVg) - GothamGo 2015 by Sameer Ajmani
* [Introduction to gRPC: A general RPC framework that puts mobile and HTTP/2 first](https://www.youtube.com/watch?v=kUz2zjkKxFg) - Devoxx by Mete Atamel
* [gRPC: The Story of Microservices at Square](https://www.youtube.com/watch?v=-2sWDr3Z0Wo) - Apigee webcast
* [Scalable Realtime Microservices with Kubernetes and gRPC](https://www.youtube.com/watch?v=xb8u2s7cxzg) - Mark Mandel @ Google
* [Text to Speech server with gRPC and Kubernetes](https://www.youtube.com/watch?v=XaMr--wAuSI) - justforfunc #12
* [GRPC Microservices 101](https://www.youtube.com/watch?v=-t57ZQZpjqs) - Google Developer Group Washington by Ray Tsang
* [Efficient Microservices w/ Binary Protocol - gRPC 101](https://www.youtube.com/watch?v=RqK-mwh3-aY) - By Ray Tsang
* [grpc: From Tutorial to Production](https://www.youtube.com/watch?v=7FZ6ZyzGex0) - GopherCon 2017 by Alan Shreve
* [Scalable Microservices with gRPC, Kubernetes, and Docker](https://www.youtube.com/watch?v=xsIwYL-N4vI) - Node Interactive 2016 by Sandeep Dinesh
* [Building Microservices w/gRPC & Kubernetes](https://www.youtube.com/watch?v=27swR9HACWU) - Philly ETE 2016 #49 by Kelsey Hightower
* [Building high performance microservices with Kubernetes, Go, and gRPC](https://www.youtube.com/watch?v=YiNt4kUnnIM) - Google Cloud Next '17 by Andrew Jessup
* [Modifying gRPC Services Over Time](https://www.youtube.com/watch?v=F2WYEFLTKEw) - Eric Anderson, Google at KubeCon + CloudNativeCon 2017 - Austin
* [Next Generation Services at Indeed Using gRPC](https://www.youtube.com/watch?v=aQ2d9iLDR8Y) - Jaye Pitzeruse, Indeed.com at KubeCon + CloudNativeCon 2017 - Austin
* [Generating Unified APIs with Protocol Buffers and gRPC](https://www.infoq.com/presentations/api-pb-grpc) - A video on Protocol Buffers, gRPC and Envoy from Lyft.
* [Intro to gRPC: A Modern Toolkit for Microservice Communication](https://www.youtube.com/watch?v=RoXT_Rkg8LA) - A video from Twilio's Signal Conference
* [gRPC and Go: Developing Efficient and Type-Safe Services](https://www.youtube.com/watch?v=J-NTfvYL_OE)
* [Best Practices for (Go) gRPC Services](https://www.youtube.com/watch?v=Z_yD7YPL2oE)
* [Creating GopherJS Apps with gRPC-Web](https://www.youtube.com/watch?v=R2HaxH7Et64) - At FOSDEM
* [justforfunc #31: gRPC Basics](https://www.youtube.com/watch?v=uolTUtioIrc) - JustForFunc: Programming in Go series Episode 31 covering gRPC
* [Efficient service communication with gRPC](https://www.youtube.com/watch?v=t9SUcf3Uwlg) - Talk at microXchg 2018 Berlin
* [gRPC Java Course on Udemy](http://bit.ly/grpc-java-github) - Online Course (4 hours) that walks through several examples and implementations of gRPC using the Java Language
* [HTTP and JSON for your gRPC Services - Michael Hamrah](https://www.youtube.com/watch?v=AmXo6tPGUdQ) - from Full Stack Fest
* [Types All the Way Down — gRPC and Go Infrastructure at Lyft](https://www.youtube.com/watch?v=ZqPTKJu2QFk) - Christopher Burnett  at Istanbul Tech Talks
* [Using gRPC for Long-lived and Streaming RPCs](https://www.youtube.com/watch?v=Naonb2XD_2Q) - Eric Anderson, Google at KubeCon North America 2018
* [Intro: gRPC-Web](https://www.youtube.com/watch?v=RtyKEDZipsM) - Stanley Cheung & Wenbo Zhu, Google at at KubeCon North America 2018
* [Putting gRPC in Practice](https://www.youtube.com/watch?v=8KWmNw9jQ04) - Presentation on working with gRPC.
* [The Story of Why We Migrate to gRPC and How We Go About It](https://www.youtube.com/watch?v=fMq3IpPE3TU) - Matthias Grüter, Spotify at KubeCon + CloudNativeCon Europe 2019
* [Authentication and Security in gRPC Microservices](https://www.youtube.com/watch?v=_y-lzjdVEf0) - Jan Tattermusch, Google at KubeCon + CloudNativeCon Europe 2019
* [JustFootball’s Journey to gRPC + Linkerd in Production](https://www.youtube.com/watch?v=AxPfa7Mp_WY) - Ben Lambert, & Kevin Lingerfelt at KubeCon + CloudNativeCon Europe 2019
* [gRPC load balancing and Service Mesh](https://www.youtube.com/watch?v=FuXnfGHUZcU) - Vishal Powar, Google at KubeCon + CloudNativeCon Europe 2019
* [Adopting gRPC: Overcoming Team and Technical Hurdles](https://www.youtube.com/watch?v=VNllljvhcnk) - GOTO 2019 • Adopting gRPC: Overcoming Team and Technical Hurdles • Josh Humphries
* [Moving to gRPC Java](https://www.youtube.com/watch?v=vFBuvWVIcYQ) - Mya Pitzeruse at Indeed.com
* [Building a gRPC application in Ballerina](https://www.youtube.com/watch?v=-wHFIPa1-3I\&t=1s) - A Demo on how to build a gRPC application in Ballerina at gRPC Meetup

<a name="res-slides"></a>

### Slides

* [gRPC Overview](http://www.slideshare.net/VarunTalwar4/grpc-overview) - An overview at gRPC: Talk at Slack by
  Varun Talwar
* [gRPC Design and Implementation](https://www.slideshare.net/VarunTalwar4/grpc-design-and-implementation) - April 2016 talk at Stanford by Varun Talwar
* [gRPC - boilerplate to high-performance scalable APIs](https://www.slideshare.net/AboutYouGmbH/robert-kubis-grpc-boilerplate-to-highperformance-scalable-apis-codetalks-2015) - code.talks 2015 by Robert Kubis
* [HTTP2 and gRPC](https://www.slideshare.net/GuoJing8/http2-and-grpc) - A simple introduction about HTTP2 and gRPC by Xin Gong Chang
* [gRPC and Microservices](https://www.slideshare.net/blinkingsquirrel/grpc-and-microservices) - Overview of Google's open source microservices framework - gRPC, based on HTTP2 and protocol buffers. Presented at Golang Melbourne, June 2016 by Jonathan Gomez
* [gRPC and Microservices](https://github.com/jonog/talks/blob/master/src/grpc/grpc-presentation.md) ⭐ 2 | 🐛 0 | 📅 2019-12-05 - Golang Melbourne - June 2016 Go Hack Night by Jonathan Gomez
* [Scalable Microservices with gRPC, Kubernetes, and Containers](https://speakerdeck.com/googlecloudplatform/scalable-microservices-with-grpc-kubernetes-and-containers-devfest-ukraine) - DevFest Ukraine
* [OpenAPI and gRPC Side by-Side](https://www.slideshare.net/timburks/openapi-and-grpc-side-byside) - APIStrat Conference -
  Tim Burks
* [Go+Microservices at Mercari](https://talks.godoc.org/github.com/tcnksm/talks/2017/11/gocon2017/gocon2017.slide) - Taichi Nakashima at Go Conference 2017
* [gRPC - RPC rebirth?](https://www.slideshare.net/LusBarbosa9/grpcrpc-rebirth) - Presentation about gRPC at the 23. NetPonto community meeting in Porto by Luís Barbosa

<a name="res-examples"></a>

### Examples

* [coolstore-microservices](https://github.com/vietnam-devs/coolstore-microservices) ⭐ 2,531 | 🐛 32 | 🌐 C# | 📅 2023-03-07 - A containerized polyglot gRPC microservices based on .NET Core, Nodejs and more running on Istio
* [Text to Speech server with gRPC and Kubernetes](https://github.com/campoy/justforfunc/tree/master/12-say-grpc) ⭐ 1,495 | 🐛 19 | 🌐 Go | 📅 2019-11-21 - justforfunc #12
* [Go Microservices Example](https://github.com/harlow/go-micro-services) ⭐ 1,092 | 🐛 0 | 🌐 Go | 📅 2026-03-06 - HTTP up front, Protobufs in the rear
* [go-micro-services](https://github.com/harlow/go-micro-services) ⭐ 1,092 | 🐛 0 | 🌐 Go | 📅 2026-03-06 - An demonstration of Golang micro-services that expose a HTTP/JSON frontend and then leverages gRPC for inter-service communication
* [Colossus](https://github.com/lucperkins/colossus) ⭐ 1,043 | 🐛 1 | 🌐 Starlark | 📅 2022-06-02 - An example multi-language gRPC microservice architecture built by Bazel and targeting Kubernetes
* [gRPC Java Examples](https://github.com/saturnism/grpc-java-by-example) ⭐ 885 | 🐛 25 | 🌐 Java | 📅 2021-07-26 - A collection of useful/essential gRPC Java Examples
* [Go gRPC features examples](https://github.com/vladimirvivien/go-grpc) ⭐ 253 | 🐛 0 | 🌐 Go | 📅 2022-02-28 - A collection of gRPC and Go examples showcasing features of the framework
* [Making a Multiplayer Game With Go and gRPC](https://mortenson.coffee/blog/making-multiplayer-game-go-and-grpc/) - gRPC game example in Go. [Source](https://github.com/mortenson/grpc-game-example) ⭐ 239 | 🐛 0 | 🌐 Go | 📅 2020-05-17.
* [Detailed examples for Go](https://github.com/lixd/grpc-go-example) ⭐ 167 | 🐛 0 | 🌐 Go | 📅 2022-10-16 - A detailed gRPC example in Go.
* [Streaming RPC's using gRPC](https://github.com/ridha/grpc-streaming-demo) ⭐ 165 | 🐛 0 | 🌐 Go | 📅 2017-03-11 - A quick demo of bi-directional streaming RPC's using grpc, Go and Python
* [gifinator](https://github.com/GoogleCloudPlatform/gifinator) ⚠️ Archived - A sample application demonstrating Kubernetes, gRPC, Go and cute Gophers demoed at Google GCP Next 2017
* [Multiplayer Simon Says - A Game using gRPC and Kubernetes](https://github.com/grpc-ecosystem/grpc-simon-says) ⭐ 138 | 🐛 1 | 🌐 Go | 📅 2016-11-09 - Sample app with Go server and clients using Node.js (on Arduino and web), and Java (Android and CLI)
* [gRPC/OpenCensus Demo](https://github.com/rakyll/opencensus-grpc-demo) ⭐ 59 | 🐛 3 | 🌐 Java | 📅 2018-05-08 - Export metrics and traces from gRPC servers and clients using Java, Go and Prometheus
* [gRPC Goat - An intentionally vulnerable gRPC Security Lab](https://github.com/rootxjs/grpc-goat) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2025-09-22 -  gRPC Goat is a "Vulnerable by Design" lab created to provide an interactive, hands-on playground for learning and practicing gRPC security.
* [gRPC Microservices with Go and Kubernetes](https://github.com/shuza/kubernetes-go-grpc) ⭐ 41 | 🐛 1 | 🌐 Go | 📅 2024-05-21 - A sample application use gRPC in microservice and deploy in kubernetes.
* [Hello gRPC](https://github.com/feuyeux/hello-grpc) ⭐ 19 | 🐛 21 | 🌐 Shell | 📅 2026-08-17 - Simple server and client examples showcasing gRPC features(including proxy and propagate, running in containers and kubernetes) with Java/Kotlin/Go/NodeJs/Python/Rust/C++/C#.
* [Envoy proxy as an API gateway for gRPC microservice](https://ekhabarov.com/post/envoy-as-an-api-gateway/) - A gRPC service in Go, built with Bazel and deployed into Kubernetes cluster with [Tilt](https://tilt.dev) and REST API enabled. [Source](https://github.com/ekhabarov/bazel-k8s-envoy) ⭐ 18 | 🐛 0 | 🌐 Starlark | 📅 2026-01-15
* [GCP - Online Boutique application rewritten in Ballerina](https://github.com/ballerina-guides/gcp-microservices-demo) ⭐ 17 | 🐛 1 | 🌐 Ballerina | 📅 2026-08-06 - Online Boutique application rewritten in Ballerina
* [gRPC Ballerina service Example](https://ballerina.io/learn/by-example/#grpc-service) - A collection of simple gRPC service examples written in Ballerina
* [gRPC Ballerina client Example](https://ballerina.io/learn/by-example/#grpc-client) - A collection of simple gRPC client examples written in Ballerina

<a name="res-misc"></a>

### Miscellaneous

* [gRPC with Load Balancer or Proxy or on AWS](https://gist.github.com/bojand/6a604f7e369d7c7d8c39eb77878a42c2) - Various notes on doing gRPC behind a load balancer or proxy or on AWS
* [gRPC service upgrade, versioning](https://groups.google.com/forum/#!topic/grpc-io/LPsPg5ctQd4) - A short possibly useful discussion on gRPC service upgrade and versioning
* [Packaging Generated Code for gRPC Services](https://blog.bugsnag.com/libraries-for-grpc-services/) - An article demonstrating a strategy on how to version and package gRPC libraries
* [Migrating APIs from REST to gRPC at WePay](https://wecode.wepay.com/posts/migrating-apis-from-rest-to-grpc-at-wepay) - A blog post on migrating from REST to gRPC

<a name="proto"></a>

## Protocol Buffers

<a name="proto-docs"></a>

### Documentation

* [Website](https://developers.google.com/protocol-buffers/) - Official website and documentation
* [Third-Party Add-ons for Protocol Buffers](https://github.com/protocolbuffers/protobuf/blob/master/docs/third_party.md) ⭐ 71,736 | 🐛 291 | 🌐 C++ | 📅 2026-08-18 - List of add-ons for Protocol Buffers in main github repository

<a name="proto-package-managers"></a>

### Package Managers

* [buffrs](https://github.com/helsing-ai/buffrs) ⭐ 377 | 🐛 38 | 🌐 Rust | 📅 2026-06-27 – A modern package manager for protocol buffers and gRPC architectures.

<a name="proto-tools"></a>

### Tools

* [protoc-gen-doc](https://github.com/pseudomuto/protoc-gen-doc) ⭐ 2,836 | 🐛 129 | 🌐 Go | 📅 2026-07-21 - Documentation generator plugin for Google Protocol Buffers
* [Protovalidate](https://github.com/bufbuild/protovalidate) ⭐ 1,551 | 🐛 32 | 🌐 Go | 📅 2026-08-18 - Protovalidate provides standard annotations to validate common rules on messages and fields, as well as the ability to use CEL to write custom rules.
* [go-proto-validators](https://github.com/mwitkow/go-proto-validators) ⭐ 1,100 | 🐛 47 | 🌐 Go | 📅 2023-10-25 - Generate message validators from .proto annotations, used in `grpc_validator` Go gRPC middleware.
* [openapi2proto](https://github.com/NYTimes/openapi2proto) ⭐ 1,002 | 🐛 22 | 🌐 Go | 📅 2023-05-21 - A tool for generating Protobuf v3 schemas and gRPC service definitions from OpenAPI specifications
* [api-linter](https://github.com/googleapis/api-linter) ⭐ 764 | 🐛 60 | 🌐 Go | 📅 2026-08-03 - A linter for APIs defined in protocol buffers.
* [protolint](https://github.com/yoheimuta/protolint) ⭐ 696 | 🐛 62 | 🌐 Go | 📅 2026-08-14 - A pluggable linter and fixer to enforce Protocol Buffer style and conventions.
* [protolock](https://github.com/nilslice/protolock) ⭐ 631 | 🐛 23 | 🌐 Go | 📅 2024-02-12 - Protocol Buffer companion tool to `protoc` and `git`. Track your .proto files and prevent changes to messages and services which impact API compatibilty.
* [protoc-gen-lint](https://github.com/ckaznocha/protoc-gen-lint) ⭐ 288 | 🐛 4 | 🌐 Go | 📅 2024-12-23 - A plug-in for Google's Protocol Buffers (protobufs) compiler to lint .proto files for style violations
* [protoc-gen-struct-transformer](https://github.com/bold-commerce/protoc-gen-struct-transformer) ⚠️ Archived - Transformation functions generator for Protocol Buffers.
* [Wireshark Protobuf Dissector](https://github.com/128technology/protobuf_dissector) ⭐ 192 | 🐛 12 | 🌐 Lua | 📅 2019-01-19 - A Wireshark Lua plugin for decoding Google protobuf packets. [Relevant PR and discussion](https://github.com/google/protobuf/issues/3303) ⭐ 71,736 | 🐛 291 | 🌐 C++ | 📅 2026-08-18.
* [prototools](https://github.com/sourcegraph/prototools) ⭐ 174 | 🐛 6 | 🌐 Go | 📅 2026-07-03 - Documentation generator & other tools for protobuf/gRPC.
* [protoc-gen-map](https://github.com/jackskj/protoc-gen-map) ⚠️ Archived - SQL data mapper framework for Protocol Buffers.
* [intellij-protobuf-plugin](https://github.com/devkanro/intellij-protobuf-plugin) ⭐ 93 | 🐛 17 | 🌐 Kotlin | 📅 2026-05-09 - IntelliJ-based IDEs Protobuf Language Plugin that provides Protobuf language support.
* [protoc-gen-apidocs](https://github.com/tmc/protoc-gen-apidocs) ⭐ 33 | 🐛 0 | 🌐 Go | 📅 2024-04-24 - Documentation generator plugin for protobuf/gRPC.
* [Protoxygen](https://github.com/lisroach/Protoxygen) ⭐ 10 | 🐛 3 | 🌐 Python | 📅 2022-05-13 - [Doxygen](http://doxygen.nl) plugin to generate documentation for protobuf/gRPC
* [pbvm](https://github.com/ekalinin/pbvm) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2020-07-22 - Protocol Buffers Version Manager
* [buf](https://buf.build) - Protobuf tool that includes linting and breaking change detection.
  Allows many types of input including directly checking remote repositories and tarballs, and has a built-in compiler as well.
* [clang-format](https://clang.llvm.org/docs/ClangFormat.html) - Protocol Buffers formating tool
  Can be used to format on save in editor such as [Visual studio code](https://marketplace.visualstudio.com/items?itemName=xaver.clang-format) or [IntelliJ](https://plugins.jetbrains.com/plugin/14004-protocol-buffer-editor).
* [Mouse Melon](https://mousemelon.dev) - A user-friendly Protocol Buffers data editor.

### Similar

* [Twirp](https://github.com/twitchtv/twirp) ⭐ 7,528 | 🐛 14 | 🌐 Go | 📅 2024-08-05 - A simple RPC framework with protobuf service definitions
* [Greenpack](https://github.com/glycerine/greenpack) ⭐ 115 | 🐛 0 | 🌐 Go | 📅 2026-01-23 - Serialization format similar to MessagePack, but adds field versioning and type annotation
* [MessagePack](http://msgpack.org/index.html) - It's like JSON, but fast and small
* [Thrift](https://thrift.apache.org/) - Thrift is an interface definition language and binary communication protocol
* [Cap’n Proto](https://capnproto.org/) - Think Protocol Buffers, except faster
* [FlatBuffers](https://google.github.io/flatbuffers/) - An efficient cross platform serialization library
* [RSocket](http://rsocket.io/) - Application protocol providing Reactive Streams semantics

## Archive

Tools and libraries that are no longer maintained.

### Tools

#### GUI

* [BloomRPC](https://github.com/uw-labs/bloomrpc) ⚠️ Archived - A nice and simple GUI Client. Exploring and interacting with gRPC and gRPC-web services has never been simpler, Inspired By GraphQL-Playground and Postman
* [omgRPC](https://github.com/troylelandshields/omgrpc) ⭐ 462 | 🐛 16 | 🌐 JavaScript | 📅 2018-08-03 - A GUI client for interacting with gRPC services, similar to what Postman is for REST APIs
* [letmegrpc](https://github.com/gogo/letmegrpc) ⭐ 425 | 🐛 21 | 🌐 Go | 📅 2025-07-01 - Generate a web form gui from a grpc specification
* [Plumber](https://github.com/pashkatrick/Plumber) ⚠️ Archived - Another one GUI for GRPC requests (reflection only)
* [Fint](http://bytesmotion.com/fint) - Create, run, manage performance tests and functional tests cases for gRPC service in a single (commercial) tool

#### Testing

* [gatling-grpc](https://github.com/phiSgr/gatling-grpc) ⚠️ Archived - A [Gatling](http://gatling.io/) stress test plugin for gRPC.

### Language-Specific

#### Go

* [grpc-web](https://github.com/improbable-eng/grpc-web) ⭐ 4,473 | 🐛 180 | 🌐 TypeScript | 📅 2023-09-23 - gRPC Web implementation for Golang and TypeScript
* [proteus](https://github.com/src-d/proteus) ⭐ 735 | 🐛 24 | 🌐 Go | 📅 2020-10-19 - Generate .proto files from Go source code
* [go-microservice-helpers](https://github.com/google/go-microservice-helpers) ⚠️ Archived - A collection of handy snippets that simplify creation of gRPC servers and clients
* [grpclb](https://github.com/bsm/grpclb) ⚠️ Archived - External Load Balancing Service solution for gRPC written in Go
* [protoc-gen-cobra](https://github.com/fiorix/protoc-gen-cobra) ⚠️ Archived - Command line tool generator for Go gRPC
* [go-GRPC Micro](https://github.com/micro/go-grpc) - [Micro](https://github.com/micro) based gRPC framework for microservices

#### Node.js

* [grpc-bus](https://github.com/paralin/grpc-bus) ⭐ 44 | 🐛 9 | 🌐 TypeScript | 📅 2017-08-16 - Call gRPC services (even streams!) from the browser over any two-way socket to Node and soon Go
* [grpc-host-builder](https://github.com/litichevskiydv/grpc-host-builder) ⚠️ Archived - Lightweight library for building gRPC services with server side interceptors support
* [grpc-web-gateway](https://github.com/dialogs/grpc-web-gateway) – HTTP & WebSocket proxy gateway for gRPC services

#### Java

* [rejoiner](https://github.com/google/rejoiner) ⚠️ Archived - Generates a GraphQL schema from gRPC microservices
* [reactive-grpc](https://github.com/salesforce/reactive-grpc) ⭐ 840 | 🐛 32 | 🌐 Java | 📅 2026-06-02 - Integrates reactive programming with grpc-java

#### Rust

* [grpc-rust](https://github.com/stepancheg/grpc-rust) ⚠️ Archived - Rust implementation of gRPC
* [tower-grpc](https://github.com/tower-rs/tower-grpc) ⚠️ Archived A client and server gRPC implementation based on Tower. Deprecated in favour of tonic

#### Kotlin

* [gapic-generator-kotlin](https://github.com/googleapis/gapic-generator-kotlin) ⚠️ Archived - Generates coroutine-based gRPC Kotlin client libraries from a protocol buffer description of an API
* [grpc-kapt](https://github.com/google/grpc-kapt) ⚠️ Archived - Annotation driven gRPC clients & servers in Kotlin with coroutines

#### C++

* [QtProtobuf](https://github.com/semlanik/qtprotobuf) ⭐ 177 | 🐛 46 | 🌐 C++ | 📅 2024-09-03 - gRPC and Protobuf generator and bindings for the Qt framework

### Protocol Buffers

#### Tools

* [prototool](https://github.com/uber/prototool) ⚠️ Archived - Compile, lint, and format Protobuf files, and generate stubs for any lanuguage/plugin, along with Vim/IDE integration
* [protoc-gen-map](https://github.com/jackskj/protoc-gen-map) ⚠️ Archived - SQL data mapper framework for Protocol Buffers.
* [protoc-gen-validate](https://github.com/lyft/protoc-gen-validate) - Protoc plugin to generate polyglot message validators
* [GenDocu](https://gendocu.com) - gRPC Documentation and SDK generator as a Service.

#### Similar

* [gogoprotobuf](https://github.com/gogo/protobuf) ⭐ 5,663 | 🐛 233 | 🌐 Go | 📅 2023-07-27 - Fork of golang/protobuf with extra code generation features
* [TChannel](https://github.com/uber/tchannel) ⚠️ Archived - Network multiplexing and framing protocol for RPC

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
