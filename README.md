# scua

An exploration into distributed identity, addressing the Bluesky 'satellite' challenge.

*scua* is the Old English word for cloud, which ended up as today's word *sky*. I couldn't pass up a word containing <abbr title="User Agent">UA</abbr> (User-Agent).

## Tooling

This project uses:

* [DID](https://w3c-ccg.github.io/did-primer/)s as stable service- and resource-independent identifiers.
* [ION](https://blog.ipfs.io/2021-03-24-own-your-identity-with-ion/) as an identity network that uses DIDs and Sidetree to provide DPKI.
* Verifiable Credentials as a document format to make and verify assertions.

## Dependencies

### macOS

For development you should install [HomeBrew](https://brew.sh/), then the following:

#### ipfs

See [the detailed instructions](https://docs.ipfs.io/install/command-line/#official-distributions), particularly for M1 Macs. The easy way to install is via HomeBrew:

```sh
brew install ipfs
ipfs --version         # Should print "ipfs version 0.9.1" at time of writing.
```

#### NodeJS

NodeJS is at v16 now. Some systems (e.g., ION) are only tested with NodeJS 14. Use [nvm](https://github.com/nvm-sh/nvm) to manage your NodeJS versions:

```sh
brew install nvm
nvm install 14
nvm install 16
nvm use 16
```

## Getting started

This is a NodeJS project, so run

```sh
npm install
```

## Creating an ION identity

```sh
npm run TODO
```

## Critique of tooling

## Discussion

### Identities
### DPKI