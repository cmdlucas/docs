# **Build applications**

---

Ceramic provides a decentralized network for building Web3 applications with composable data. Ceramic's APIs enable applications to store, modify, and retrieve data from a scalable decentralized data network, while maintaining composability of data across applications.

## **System requirements**

---

Ceramic clients and tools using them are designed for environments supporting [ECMAScript 11th edition](https://262.ecma-international.org/11.0/), commonly referred to as ES2020.

Most packages are exposed as ECMAScript Modules (ESM), which are supported by most modern browsers and recent versions of Node.

When using Node, we recommend version 16 (LTS), as it is the version used for tests in most Ceramic packages.

## **Get started with frameworks**

---

Frameworks make it easy to build applications on Ceramic by abstracting away much of the complexity and configuration of the underlying [Ceramic stack](the-ceramic-stack.md), providing developers with a simple entrypoint into Ceramic development. If you're new to Ceramic, or even if you're experienced, this is the place to start.

### [**Self.ID SDK →**](../reference/self-id/index.md)

Self.ID is a framework for building Ceramic applications with composable, user-centric data. In addition to including a full Ceramic setup for a variety of development environments, Self.ID allows users to authenticate with their existing blockchain wallets and also includes some of the most popular data models giving you out of the box composability with a rich set of data on the network to bootstrap your application.

## **Go deeper with clients**

---

Clients are a lower-level way to connect your application to the Ceramic network. They come without much pre-configuration, so you'll need to put at least a few different pieces together yourself.

### [**JavaScript HTTP client →**](../reference/core-clients/ceramic-http.md)

The Ceramic JS HTTP client is a Ceramic client that can be used in browsers and Node.js environments to connect your application to a Ceramic node. This is the recommended Ceramic client to build with for most applications, if you're not using a framework.
