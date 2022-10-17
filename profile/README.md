# zk3 - Lens Protocol meets ZKP
----

# Introduction

Zk3 is a web3 suite of tools built to integrate on-chain decentralized graph networks with off chain services using Zero Knowledge Proofs.

Zk3 is still in development and is not yet audited for production use.


# Components
----------

1. `ZK3 web-app`: can fully run in the browser and is able to generate, verify and broadcast signals without extra plugins beside a wallet like MetaMask. This will later be turned into a package so other Lens enabled apps can add Zk posting easily.

2. [`ZK3 Semaphore`](https://github.com/monemetrics/semaphore-zk3-alpha/pull/1): is built on top of Semaphore Protocol and uses Semaphore Groups under the hood to create and manage Groups (aka Zk3 Circles). 

2. [`Lens Zk3 Reference Module`](https://github.com/monemetrics/lens-zk3/pull/1): A Lens `Reference Module` that can control the process of interacting with a ZK-enabled post

