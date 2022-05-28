> There are active miner communities on [Discord](https://discord.gg/Q86PNMwRsu) and [Telegram](https://t.me/ergo_mining).

# Mining

Ergo mining is based on [Autolykos](/mining/autolykos), an ASIC resistant Proof of Work algorithm written in Scala that runs cool and increases mining equipment longevity. Combined with the eUTXO model, this creates a highly efficient Proof of Work. Ergo had a fair launch with no premine, ICO or VC funding. 

**Getting Started**


- [Join a pool](setup/join)
- [Solo Mine](setup/solo)
- [Host a pool](setup/pool)


## [Autolykos](autolykos)

**History**

- **Launch:** Ergo mainnet launched in 2019. Total Supply: `97,739,925` ERG.
- **The Hardening** *(block `417,792`)`* Autolykos v1 originally had pool-resistance built-in through the use of non-outsourceable puzzles. Ergo had to adapt and support pooled mining to protect the chain’s consensus as unfortunately the non-out-sourceable puzzles concept was broken with smart contracts. See ["Bypassing Non-Outsourceable Proof-of-Work Schemes Using Collateralized Smart Contracts"](https://ia.cr/2020/044).
- [**EIP27:**](../dev/protocol/eip27) Extends mining rewards to 2045. Activated block `777,272`





## [Governance](governance.md)

Ergo Miners have the ability to adjust the block size which increases the amount of transactions per block. This increases potential rewards but also adds additional storage requirements. adjust the emission macroeconomics, meaning the long term economic security of the protocol is up to miners to decide. 

In addition to the protocol parameters above that can be changed via on-chain miner voting, most things on Ergo can be changed via a soft-forking protocol (90% support required). This excludes critical changes such as changing the max supply. 


## [Storage Rent](rent)



Storage Rent is a nominal fee (.14ERG per 4 years from an unmoved box) + transaction fees.

The problem with “storage rent fee” is this “fee” part — which may look like a disadvantage. However, programmers can quickly realize the importance of it by just imagining life without garbage collection in their language of choice.

> *Claiming fees sound great… But what happens if a UTXO cannot pay the fee?*

Miners can take over assets inside a UTXO if there are not enough ERGs to pay for rent. This feature is one of the most interesting reward mechanisms a PoW blockchain can offer miners. The relevance of this is particularly important in a blockchain that has the capacity to have a wide variety of assets.

As Ergo matures, more revenue streams will become available to miners. 

- Sidechain Rewards
- Bridge Infrastructure
- L2 Infrastructure
