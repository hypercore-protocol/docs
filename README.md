# Hypercore Protocol Docs
The Hypercore Protocol is a set of data structures and networking tools you can use to build fast and safe P2P systems. In this repo you'll find links to resources that will help get you up and running with Hypercore.

We'll be continually adding new introductory docs to this repo, so check back soon!

## Getting Started
If you're new to the Hypercore Protocol, we recommend you install [Hyperspace](https://github.com/hypercore-protocol/hyperspace), which is a server that handles a bunch of the nitty-gritty of P2P networking for you.

## Main Modules
* [Hypercore](https://github.com/hypercore-protocol/hypercore): A secure, distributed append-only log. The foundational module in our ecosystem.
* [Hypercore Protocol](https://github.com/hypercore-protocol/hypercore-protocol): The wire protocol for transferring Hypercores between peers.
* [Hyperswarm](https://github.com/hypercore-protocol/hyperswarm): A DHT with distributed hole-punching, designed for discovering and sharing Hypercores.
* [Hyperspace](https://github.com/hypercore-protocol/hyperspace): A "batteries-included" server and CLI for managing Hypercores.
* [Hyperdrive](https://github.com/hypercore-protocol/hyperdrive): A P2P filesystem that supports syncing files on-demand.
* [Hyperbee](https://github.com/mafintosh/hyperbee): An append-only B-Tree implementation built on Hypercore.

## Workshops

### [Intro to P2P Indexing and Search](https://github.com/hypercore-protocol/p2p-indexing-and-search)
Our workshop for [NodeConf Remote 2020](https://www.nodeconfremote.com/) has a bunch of exercises, starting at square one, that guide you through setting up Hyperspace, designing data structures on Hypercore, and eventually building and querying a large P2P database of IMDB data (metadata about movies and TV shows). 

## FAQs
### [Why Hypercore?](https://github.com/tradle/why-hypercore/blob/master/FAQ.md)
[@urbien](https://github.com/urbien), [@pgmemk](https://github.com/pgmemk) and the folks at [Tradle](https://github.com/tradle) have put together a great general FAQ. It's super thorough, so definitely check that out if you have questions.

## Chat with us
Come say hello and ask us questions in our [Discord](https://chat.hypercore-protocol.org).

## APIs
For more detailed info about APIs, and specific usage examples, it's best to jump directly to the GitHub repos for the various modules in this org.

You can could also use the [Hyper SDK](https://github.com/datproject/sdk#readme) which puts the main modules together and works out of the box in Node and the web.
