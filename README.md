# ipfs glossary

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://ipn.io)
[![](https://img.shields.io/badge/project-IPFS-blue.svg?style=flat-square)](http://ipfs.io/)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)
[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

> A collection of descriptions for terms related to ipfs and surrounding techs

## Table of Contents

- [Terms](#terms)
  - [Protocol](#protocol)
  - [Hash Function](#hash-function)
  - [DHT (Distributed Hash Table)](#dht-distributed-hash-table)
  - [TCP](#tcp)
  - [UDP](#udp)
  - [Merkledag](#merkledag)
  - [unixfs](#unixfs)
- [Contribute](#contribute)
  - [Want to hack on IPFS?](#want-to-hack-on-ipfs)
- [License](#license)

## Terms

These terms are not yet defined, but have been suggested as good terms to work on. Please define them if you can!



### Terms

### IPFS

See https://en.wikipedia.org/wiki/InterPlanetary_File_System.

#### Protocol
A set of rules describing how to communicate

#### Hash Function
A way of generating a unique name for a piece of data

#### MFS

Mutable filesystem (see also: FUSE)

#### Random Walk

Querying the DHT for random keys, in order to discover new peers and fill gaps in keyspace

#### TCP
TCP is a protocol that is used for a huge portion of web traffic. It guarantees that information arrives entirely and in order.

#### UDP
UDP is a protocol that does not have the same guarantees as TCP. Data sent can go missing, or arrive in the wrong order.

### Merkledag
[Deprecated, although this link has more info](https://github.com/ipfs/specs/tree/master/merkledag) in favour of IPLD (see below). Also see https://en.wikipedia.org/wiki/InterPlanetary_File_System#Merkle_data_format and https://github.com/ipfs/specs/tree/master/merkledag.

#### unixfs

Merkle-dag based data structures for representing unix files, directories, and symlinks

### Pubsub
From https://github.com/libp2p/research-pubsub/issues/9, more terminology is there.
- Publishers: they are the authors of the new content that need to be published
- Brokers: they can be subscribers, they receive messages from publishers and send them to subscribers
- Subscribers: simply subscribe to messages

### IPLD
Interplanetary Linked Data (IPLD)
> is the data model of the content-addressable web. It allows us to treat all hash-linked data structures as subsets of a unified information space, unifying all data models that link data with hashes as instances of IPLD. — https://ipld.io/

> IPLD is the format for IPFS objects, but it can be used outside of ipfs (hence a module). It's layered on top of `multihash` and `multicodec`, and provides the heart of ipfs: the merkledag.
>
>Implementations:
- [go-ipld](https://github.com/ipfs/go-ipld)
- [js-ipld](https://github.com/ipld/js-ipld-dag-cbor)
—https://github.com/ipfs/specs/blob/master/overviews/implement-ipfs.md#ipld

### IPNS
Interplanetary Namespace: this is 'a global namespace based on [PKI](https://en.wikipedia.org/wiki/Public_key_infrastructure), which serves to build trust chains, and is compatible with other NSes and can map [DNS](https://en.wikipedia.org/wiki/Domain_Name_System), .onion, .bit, etc. to IPNS.'—https://en.wikipedia.org/wiki/InterPlanetary_File_System#Description

> IPNS provides name resolution on top of IPRS -- and a choice of record routing system.
—https://github.com/ipfs/specs/blob/c22404878e4cbefaf97433bfd8d57d194ef8eb71/overviews/implement-ipfs.md#ipns

### IPRS

> IPRS is the record system for IPFS, but it can be used outside of ipfs (hence a module). This deals with p2p system records -- it is also used by `libp2p`.
>
> Implementations:
- [go-iprs](https://github.com/ipfs/go-iprs)
- js-iprs _Forthcoming_
—https://github.com/ipfs/specs/blob/master/overviews/implement-ipfs.md#iprs

### cbor, starlog, starship, solarnet, DHT (Distributed Hash Table), merkle-dag, Fuse

## Contribute

Feel free to join in. Just edit this main README file in a PR, or open an [issue](https://github.com/ipfs/glossary/issues)!

This repository falls under the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

### Want to hack on IPFS?

[![](https://cdn.rawgit.com/jbenet/contribute-ipfs-gif/master/img/contribute.gif)](https://github.com/ipfs/community/blob/master/contributing.md)
