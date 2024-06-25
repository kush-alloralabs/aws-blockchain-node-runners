# Sample AWS Blockchain Node Runner app for Allora Worker Nodes

| Contributed by |
|:--------------------:|
| [@vladupshot](https://github.com/vladupshot), [@allora-rc](https://github.com/allora-rc) |

[Allora](https://www.allora.network/) is a self-improving decentralized Artificial Intelligence (AI) network. The primary goal of the network is to be the marketplace for intelligence. In other words, Allora aims to incentivize data scientists (workers) to provide high-quality inferences as requested by consumers. Inferences include predictions of arbitrary future events or difficult computations requiring specialized knowledge.

Allora brings together

  - consumers who pay for and acquire inferences or expertise to be revealed
  - workers who reveal inferences
  - reputers who determine how accurate workers are after a ground truth is revealed
  - validators who secure protocol state, history, and reward distributions

This blueprint is designed to assist in deploying a single node or a Highly Available (HA) [Fantom read-only node](https://docs.fantom.foundation/node/tutorials/run-a-read-only-node) on AWS. It is intended for use in development, testing, or Proof of Concept purposes.

## Overview of Deployment Architectures

### Single Worker Node Setup
![Single Worker Node Deployment](./doc/assets/Architecture-Single-Allora-Worker-Node.png)
