[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A collaborative list of all things Swift NIO.

## Contributing

Do you know of something that's missing on this list? Please [open a pull request](https://github.com/slashmo/awesome-swift-nio/pulls) so other people can enjoy the resource as well :heart:

If you instead want to get started contributing to NIO itself, check out the list of ["good first issues"](https://github.com/apple/swift-nio/labels/good%20first%20issue)

## Articles

- ["Loops" with Futures](https://forums.swift.org/t/loops-with-futures/37216) - Using recursion to asynchronously perform multiple requests
- [SwiftNIO: A simple guide to async on the server](https://www.raywenderlich.com/1124580-swiftnio-a-simple-guide-to-async-on-the-server) - Hands-on tutorial about NIO futures & promises
- [SwiftNIO Tutorial: Pratical Guide for Asynchronous Problems](https://www.raywenderlich.com/8016626-swiftnio-tutorial-practical-guide-for-asynchronous-problems) - Hands-on introduction to building an HTTP service
- [A µTutorial on SwiftNIO 2](http://www.alwaysrightinstitute.com/microexpress-nio2/) - Discover NIO 2 by creating a micro framework inspired by Express

## Books

- [Netty in Action](https://www.manning.com/books/netty-in-action) - *The* book about [Netty](https://github.com/netty/netty), which inspired the creation of NIO

## Videos

- [Event driven networking for Swift](https://youtu.be/QJ3WG9kRLMo) - An overview of NIO, also it's initial open-source unveil :tada:
- [SwiftNIO and Network.framework](https://youtu.be/M9kEtkhEjQ8) - Showcases how to use [NIO transport services](https://github.com/apple/swift-nio-transport-services) to build an iOS SMTP client
- [Testing SwiftNIO Systems](https://youtu.be/EVhliQJuFP0) - How to write automated tests for NIO applications
- [SwiftNIO on the Raspberry PI](https://youtu.be/FPGf652O90Y) - Write NIO code in Xcode & deploy it to a Raspberry PI
- [Implementing JSON-RPC with SwiftNIO](https://youtu.be/Rlhlc6NaO4w) - How you could use NIO to implement a custom protocol

## Projects using SwiftNIO

### Packages & executables

- [Swift NIO HTTP/2](https://github.com/apple/swift-nio-http2) - HTTP/2 support for SwiftNIO
- [Swift NIO transport services](https://github.com/apple/swift-nio-transport-services) - Extensions for SwiftNIO to support Apple platforms as first-class citizens
- [AsyncHTTPClient](https://github.com/swift-server/async-http-client) - HTTP client library built on SwiftNIO
- [Swift gRPC](https://github.com/grpc/grpc-swift) - The Swift language implementation of gRPC
- [Vapor](https://github.com/vapor/vapor) - A server-side Swift web framework
- [Swift AWS Lambda Runtime](https://github.com/swift-server/swift-aws-lambda-runtime) - Swift implementation of AWS Lambda Runtime
- [Swift NIO Extras](https://github.com/apple/swift-nio-extras) - Useful code around SwiftNIO
- [SmokeFramework](https://github.com/amzn/smoke-framework) - A light-weight server-side service framework written in the Swift programming language
- [MongoKitten](https://github.com/OpenKitten/MongoKitten) - A MongoDB driver implementation in Swift
- [netrek-server-swift](https://github.com/darrellroot/netrek-server-swift) - A Swift reimplementation of the original Internet game server: Netrek.  Uses Swift-NIO, Swift Argument Parser, Swift Log, and Swift Service Lifecycle.
- [ClickHouseNIO](https://github.com/patrick-zippenfenig/ClickHouseNIO) - High performance Swift [ClickHouse](https://clickhouse.tech) client written in pure Swift. With [ClickHouseVapor](https://github.com/patrick-zippenfenig/ClickHouseVapor) it offers seamless ORM abstraction and connection pooling with Vapor.
- [Alchemy](https://github.com/alchemy-swift/alchemy) - Elegant, batteries included web framework for Swift.

### Apps

- [Proxyman](https://github.com/ProxymanApp/Proxyman) - HTTP Debugging Proxy, uses SwiftNIO for networking

### Examples

- [Swift NIO Examples](https://github.com/apple/swift-nio-examples) - A set of NIO examples

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Moritz Lang](https://twitter.com/slashmodev) has waived all copyright and related or neighboring rights to this work.
