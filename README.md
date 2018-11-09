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

* [AIO](https://github.com/tris-foundation/aio) - asynchronous io with syncronous api
* [Stream](https://github.com/tris-foundation/stream) - io abstrations + basic streams, buffered stream, reader/writer

### Cryptography

* [Crypto](https://github.com/tris-foundation/crypto) - digest, encryption, asn.1, uuid
* [TLS](https://github.com/tris-foundation/tls) - work in progress

### Frontend

> "Standards aren't add-ons to the web. They are the web" - Apple

It's time to use [Web Components](https://webcomponents.org).
Please take a look at [Stencil](https://stenciljs.com) and [Polymer](https://www.polymer-project.org).

### Backend

* [Web](https://github.com/tris-foundation/web) - MVC, Controllers, DependencyInjector ([example](https://github.com/tris-foundation/examples/tree/master/web))
* [HTTP](https://github.com/tris-foundation/http) - high performance coders, server + client ([example](https://github.com/tris-foundation/examples/tree/master/http))
* [Node](https://github.com/tris-foundation/node) - embed node.js for server-side rendering ([example](https://github.com/tris-foundation/examples/tree/master/web))
* Nginx - load balancing, tls proxy and static files ([example](https://github.com/tris-foundation/examples/tree/master/nginx-spa))

A pure Swift solution will be available after TLS module is ready.<br>

### Database

* [Storage](https://github.com/tris-foundation/storage) - work in progress
* [Tarantool](https://github.com/tris-foundation/tarantool) with [swift stored procedures](https://github.com/tris-foundation/tarantool#tarantool-module) support ([example](https://github.com/tris-foundation/examples/tree/master/tarantool))<br>

### Formats

* [JSON](https://github.com/tris-foundation/json) - streaming json encoder/decoder
* [MessagePack](https://github.com/tris-foundation/messagepack) - streaming messagepack reader/writer + encoder/decoder
* [XML](https://github.com/tris-foundation/xml) - streaming xml encoder/decoder
* [XML-RPC](https://github.com/tris-foundation/xml-rpc) - request / response codable models

### Other

* [Time](https://github.com/tris-foundation/time) - high precision time, duration, interval
* [Test](https://github.com/tris-foundation/test) - convenience shims

### Contribute

Any contributions are very welcome. If you have any question feel free to open an issue.<br/>
