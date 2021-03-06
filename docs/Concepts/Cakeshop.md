# Cakeshop

[Cakeshop](https://github.com/ConsenSys/cakeshop) is a set of tools and APIs for working with [Ethereum](https://ethereum.org/),
packaged as a Java web application archive (WAR) that gets you up and running quickly.

Cakeshop can either start up a geth node, which you can then interact with using the Cakeshop front-end,
or it can be connected to an Ethereum-like node, such as Quorum, that you already have running. A given
Cakeshop instance connects with one node on the blockchain network you connect to.

![image](../images/console.png)

Out of the box you get:

* **Node Management** - Fully functioning Ethereum node (via geth), setting up a cluster
* **Blockchain Explorer** - view transactions, blocks and contracts, and see historical contract state at a point in time
* **Admin Console** - start & stop nodes, create a cluster and view the overall status of your network
* **Peer Management** - easily discover, add and remove peers
* **Solidity Sandbox** - develop, compile, deploy and interact with Solidity smart contracts

It provides tools for managing a local blockchain node, setting up clusters,
exploring the state of the chain, and working with contracts.

The Cakeshop package includes [Tessera](https://docs.tessera.consensys.net), a [Solidity](https://solidity.readthedocs.org/en/latest/)
compiler, and all dependencies. 

Cakeshop downloads the latest version of [GoQuorum](https://github.com/ConsenSys/quorum)
and bootnode from [geth](https://github.com/ethereum/go-ethereum). To use a different version, see
[here](https://github.com/ConsenSys/cakeshop/blob/master/docs/configuration.md#custom-quorum-binaries). 

[Get started with Cakeshop.](../HowTo/GetStarted/Cakeshop.md)
