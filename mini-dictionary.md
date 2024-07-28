---
description: >-
  A mini dictionary with all the different terminology, that you can always come
  back to. Useful for quick word search. You can skip
---

# 📚 Mini dictionary

## General terminology <a href="#what-is-coretime" id="what-is-coretime"></a>

**Blockspace**&#x20;

The capacity of a blockchain's blocks to store and record transactions. Each block in a blockchain has a finite amount of space, and this space is used to include transaction data and other necessary information. The availability and cost of blockspace directly impacts transaction fees and their processing speed:  as demand for blockspace increases, it can lead to higher fees and slower transaction times. &#x20;

\
L2 - EVM Specific

**Modularity**&#x20;

Modularity refers to a completely new approach to blockchain architecture. The old paradigm of monolithic chains involved a single blockchain that handled everything: transaction execution, settlement, consensus, and data availability.&#x20;

In modular architecture these tasks are split between different chains, with each blockchain specializing in a specific function. For example, some chains (rollups)  only execute transactions, others provide data availability services, while some serve as settlement layers.&#x20;

Modular architecture is the foundation of all existing solutions to the "blockchain trilemma problem" as it allows networks to scale without compromising on security and decentralization.



**Layer 2**

Layer 2 or L2 solutions are blockchains that run and are built on top of an existing blockchain (Layer 1) that settles transactions. A typical example of L2 are rollups - chains that execute hundreds hundreds of transactions and bundle them into a single transaction that they submit to layer 1. This distributes the L1 transaction fees across everyone in the rollup, making it cheaper for users.&#x20;

Aside from L2s that handle transactions, there are more kinds, such as chains that provide data availability services.&#x20;



**Data Availability**

To ensure blockchain's validity, all network participants should be able to verify transactions. Data availability is the assurance that data required for the verification of blockchain transactions can be accessed and fetched by any node.&#x20;

In monolithic blockchains, nodes must download all the data to verify its availability, which is impractical given the increasing blocksize. Modular chains solve this problem by making it possible for users to verify very large blocks using a technology called data availability sampling - instead of downloading all data, light nodes only download a tiny portion of each block.

## Polkadot specific <a href="#what-is-coretime" id="what-is-coretime"></a>

### What is Coretime?

Coretime refers to the allocation of computational resources within the Polkadot Network, analogous to "blockspace" in traditional blockchain systems. In the context of the Polkadot, Coretime is used to schedule tasks (such as parachains, parathreads or dapps) on available cores, where a task can vary from securing a substrate-based blockchain to other envisioned operations such as zero-knowledge proof computation, smart contracts, synchronous multi-chain tasks, and more once Coreplay and Corejam are implemented.

&#x20;\- Corejam

&#x20;\-&#x20;
