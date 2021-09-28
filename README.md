# Solana-Explain

# What is Solana?
Solana is a web-scale, open-source blockchain protocol that supports developers and institutions around the world to build decentralized applications (DApps) and marketplaces. Solana’s protocol is fast, secure, and censorship-resistant, which provides the flexibility of an open infrastructure required to build applications for mass adoption.

This high-performance blockchain provides the fully decentralized, secure, and highly scalable infrastructure necessary for tomorrow’s DApps and decentralized marketplaces. It leverages a set of breakthrough computational technologies that can support thousands of nodes, allowing for transaction throughput to proportionally scale with network bandwidth.

Solana uses a combination of proof-of-stake (PoS) and proof of history (PoH) consensus mechanisms to improve throughput and scalability. Consequently, the network claims to support 50,000 transactions per second (TPS), making it the fastest blockchain in the world.

Solana’s core features
To understand how Solana works, we first need to take a look at its architecture. Below are 8 core innovations that make Solana the first web-scale blockchain.

1. Proof of history (PoH) — a clock before consensus
Despite its name, PoH is not a consensus mechanism, but a cryptographic clock that enables nodes to agree on the time order of the events on the chain, without having to talk to each other — since each node has its own clock.

PoH helps create more efficiency and higher throughput within the network by storing historical records of transactions and allowing the system to keep track of the order of events more easily.

2. Tower BFT (Byzantine fault tolerance)
Tower BFT is Solana’s implementation of pBFT (practical Byzantine fault tolerance), optimized for PoH. In essence, this is a consensus algorithm that takes advantage of the cryptographic clock, reaching consensus without having to go through a multitude of messages among nodes — consequently improving the transaction speed.

3. Gulf Stream — mempool-less transaction forwarding protocol
Gulf Stream is what enables Solana to reach 50,000 TPS. This is the protocol responsible for transaction caching and for forwarding them to the edge of the network. This allows network validators to execute transactions ahead of time, drastically reducing confirmation time and the memory requirements on validators from unconfirmed transaction pools. 

4. Turbine — a block propagation protocol
Turbine is a block propagation protocol that breaks data down into smaller increments — making data transfer easier among the nodes. Turbine helps Solana address bandwidth-related issues and increase the network’s overall transaction processing speed.

5. Sealevel — parallel smart contracts run-time
This is a parallelized transaction processing engine that enables Solana to scale horizontally across GPUs and SSDs. In a nutshell, Sealevel allows for concurrent transactions on the same chain, resulting in a better runtime for the network.

6. Pipelining — a transaction processing unit for validation optimization
Pipelining is a common procedure used in CPU design. It refers to the process of assigning a stream of input data to different hardware for processing. This enables quick transaction information to be replicated and validated faster across the nodes of the network.

7. Cloudbreak — horizontally-scaled accounts database
Cloudbreak is a data structure required for the network’s scalability and throughput. It organizes the database of accounts, making concurrent reads and writes between the network’s 32 threads possible.

8. Archivers — distributed ledger storage
Solana’s validators offload the data to a network of nodes known as Archivers. Archiver nodes can be basic laptops or PCs that the network leverages for data storage.

4. How does Solana work?
Solana is considered one of the most high-performance permissionless blockchain on the market, with a network of 200 distinct nodes that generate a throughput of 50,000 TPS when running with GPUs. The network achieves this due to its unique consensus architecture.

Solana uses a proof-of-stake (PoS) consensus model, like Cardano and Tron, except it is reinforced by Tower BFT consensus. Tower consensus enables the network to reach consensus, despite potential attacks from malicious nodes.

Tower BFT enforces a universal source of time across the network through proof of history. This creates a common record of all the events and transactions on the blockchains, as a permanent reference for the nodes running the network.

People often mistake PoH, one of Solana’s core innovations, for a consensus protocol; however, this is a permissionless, globally available source of time on the blockchain that works before the network reaches consensus. Proof of history is not a consensus protocol or anti-Sybil mechanism. Rather, it is a decentralized clock that helps secure the blockchain.

Tower BFT leverages this permissionless clock to reduce the processing power necessary for transactions — since the timestamps of the previous transactions don’t need to be processed anymore. This is one of the features that make Solana’s leading throughput possible.

Sealevel, Solana’s transaction parallelization system, also plays a fundamental role, by enabling parallel smart contract runtime. This optimizes the network’s resource usage and enables its horizontal scaling across GPUs and SSDs.

Solana’s mempool system (contraction of memory and pool), Gulf Stream, is also different from other popular blockchains, as it forwards the transactions to validators before the previous set of transactions was even finalized. This mempool-less transaction forwarding protocol helps maximize transaction confirmation speed, as well as the concurrent and parallel transaction capacity of the network.
