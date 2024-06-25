# Sample AWS Blockchain Node Runner app for Allora Worker Nodes

| Contributed by |
|:--------------------:|
| [@vladupshot](https://github.com/vladupshot), [@allora-rc](https://github.com/allora-rc) |

[Fantom](https://fantom.foundation/) is a permissionless blockchain platform that supports EVM-compatible smart contracts and applications. It utilizes Delegated Proof of Stake (DPoS) and directed acyclic graphs (DAG) of event blocks to achieve fast transaction confirmation with asynchronous Byzantine fault tolerance (aBFT) guarantee.

This blueprint is designed to assist in deploying a single node or a Highly Available (HA) [Fantom read-only node](https://docs.fantom.foundation/node/tutorials/run-a-read-only-node) on AWS. It is intended for use in development, testing, or Proof of Concept purposes.

## Overview of Deployment Architectures

### Single Node setup
![Single Nodes Deployment](./doc/assets/Architecture-Single-FANTOM-Node-Runners.drawio.png)
