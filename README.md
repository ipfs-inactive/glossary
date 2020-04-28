## This repository has been archived!
*This IPFS-related repository has been archived, and all issues are therefore frozen.* If you want to ask a question or open/continue a discussion related to this repo, please visit the [official IPFS forums](https://discuss.ipfs.io).

We archive repos for one or more of the following reasons:
- Code or content is unmaintained, and therefore might be broken
- Content is outdated, and therefore may mislead readers
- Code or content evolved into something else and/or has lived on in a different place
- The repository or project is not active in general

Please note that in order to keep the primary IPFS GitHub org tidy, most archived repos are moved into the [ipfs-inactive](https://github.com/ipfs-inactive) org.

If you feel this repo should **not** be archived (or portions of it should be moved to a non-archived repo), please [reach out](https://ipfs.io/help) and let us know. Archiving can always be reversed if needed.

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

IPLD, IPNS, IPRS, cbor, starlog, starship, solarnet, DHT (Distributed Hash Table), merkle-dag, Fuse

### Terms

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
TODO

#### unixfs

Merkle-dag based data structures for representing unix files, directories, and symlinks

## Contribute

Feel free to join in. Just edit this main README file in a PR, or open an [issue](https://github.com/ipfs/glossary/issues)!

This repository falls under the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

### Want to hack on IPFS?

[![](https://cdn.rawgit.com/jbenet/contribute-ipfs-gif/master/img/contribute.gif)](https://github.com/ipfs/community/blob/master/contributing.md)
