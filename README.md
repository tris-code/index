# Tris Universe

### Current progress
You can track the state of things [here](https://github.com/orgs/tris-foundation/projects/1).

### Requirements

At the moment all the modules should work with Xcode 10 / Swift 4.2.<br>
You can also use our [docker image](https://github.com/tris-foundation/docker).<br>

## What do we have

### Quick start

* [Starters](https://github.com/tris-foundation/starters) - easy way to start new project
* [Examples](https://github.com/tris-foundation/examples) - basic examples for our modules

### Concurrency

* [Async](https://github.com/tris-foundation/async) - simple abstraction to switch between Fiber / Tarantool
* [Fiber](https://github.com/tris-foundation/fiber) - cooperative multitasking with non-blocking asynchronous io written in Swift

We can't wait for Swift's async/await, but when it comes the API won't change much.

### IO

* [AIO](https://github.com/tris-foundation/aio) - asynchronous io with synchronous api
* [Stream](https://github.com/tris-foundation/stream) - io abstractions + basic streams, buffered stream, reader/writer

### Cryptography

* [Crypto](https://github.com/tris-foundation/crypto) - digest, encryption, asn.1, uuid
* [TLS](https://github.com/tris-foundation/tls) - TLS 1.2, 1.3

### Frontend

* [View](https://github.com/tris-foundation/view) - component cross-platform view engine

### Backend

* [Web](https://github.com/tris-foundation/web) - MVC, Controllers, DependencyInjector ([example](https://github.com/tris-foundation/examples/tree/master/web))
* [HTTP](https://github.com/tris-foundation/http) - high performance coders, server + client ([example](https://github.com/tris-foundation/examples/tree/master/http))
* Nginx - load balancing, tls proxy and static files ([example](https://github.com/tris-foundation/examples/tree/master/nginx-spa))

A pure Swift solution will be available after TLS module is ready.<br>

### Database

* [Storage](https://github.com/tris-foundation/storage) - multipurpose data storage
* [Tarantool](https://github.com/tris-foundation/tarantool) with [swift stored procedures](https://github.com/tris-foundation/tarantool#tarantool-module) support ([example](https://github.com/tris-foundation/examples/tree/master/tarantool))<br>

### Format

* [Radix](https://github.com/tris-foundation/radix) - optimized Base64, Hex coding
* [JSON](https://github.com/tris-foundation/json) - streaming json encoder/decoder
* [MessagePack](https://github.com/tris-foundation/messagepack) - streaming messagepack reader/writer + encoder/decoder
* [XML](https://github.com/tris-foundation/xml) - streaming xml encoder/decoder
* [XML-RPC](https://github.com/tris-foundation/xml-rpc) - request / response codable models

### JavaScript

* [JavaScript](https://github.com/tris-foundation/javascript) - embed JavaScript in your Swift application (V8, ChakraCore, JavaScriptCore)
* [Node](https://github.com/tris-foundation/node) - embed node.js in your Swift application
* [SSR](https://github.com/tris-foundation/ssr) - server-side rendering with node.js ([example](https://github.com/tris-foundation/examples/tree/master/server-side-rendering))

### Audio

* [Audio](https://github.com/tris-foundation/audio) - low-level audio abstraction
* [Music](https://github.com/tris-foundation/music) - notes, pitch detection

### Tests

* [Test](https://github.com/tris-foundation/test) - convenience shims for everyday use
* [CI](https://github.com/tris-foundation/continuous-integration) - simple ci server written in Swift

### Other

* [Platform](https://github.com/tris-foundation/platform) - libc abstraction
* [Codable](https://github.com/tris-foundation/codable) - codable helpers
* [Compression](https://github.com/tris-foundation/compression) - gzip, deflate
* [Reflection](https://github.com/tris-foundation/reflection) - construct any value type
* [LinkedList](https://github.com/tris-foundation/linked-list) - unsafe but superfast linked list
* [Process](https://github.com/tris-foundation/process) - fiber-friendly process abstraction
* [Time](https://github.com/tris-foundation/time) - high precision time, duration, interval
* [Log](https://github.com/tris-foundation/log) - general log system

### Third-party

* [GitHub](https://github.com/tris-foundation/github) - github api client
* [OpenSubtitles](https://github.com/tris-foundation/opensubtitles) - opensubtitles api client
* [SuperMemo](https://github.com/tris-foundation/supermemo) - supermemo2 algorithm

### Contribute

Any contributions are very welcome. If you have any question feel free to open an issue.<br/>
