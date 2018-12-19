For a more complete guide and resource list, see https://github.com/ConsenSys/ethereum-developer-tools-list  
Most of the links in this cookbook are included in the linked list as well.

# SmartContractDev-Cookbook
A smart contract development cookbook "for runaways". Mostly ordered links and howtos. Focused on best practices and security.

## Patterns for Smart Contract Development

* [Dappsys: Safe, simple, and flexible Ethereum contract building blocks](https://github.com/dapphub/dappsys)
    * has solutions for common problems in Ethereum/Solidity, eg.
        * [Whitelisting](https://steemit.com/ethereum/@nexusdev/dapp-a-day-11-whitelist-boring)
        * [Upgradable ERC20-Token](https://steemit.com/ethereum/@nikolai/dapp-a-day-6-upgradeable-tokens)
        * [ERC20-Token-Vault](https://steemit.com/ethereum/@nexusdev/dapp-a-day-18-erc20-token-vault)
        * [Authentication (RBAC)](https://steemit.com/ethereum/@nikolai/dapp-a-day-4-access-control-via-auth)
        * [...several more...](https://github.com/dapphub/dappsys)
    * provides building blocks for the [MakerDAO](https://github.com/makerdao/maker-otc) or [The TAO](https://ryepdx.github.io/the-tao/)
    * should be consulted before creating own, untested, solutions
    * usage is described in [Dapp-a-day 1-10](https://steemit.com/@nikolai) and [Dapp-a-day 11-25](https://steemit.com/@nexusdev)
* [OpenZeppelin: An open framework of reusable and secure smart contracts in the Solidity language.](http://zeppelin-solidity.readthedocs.io/en/latest/) 
    * Similar to Dappsys, more integrated into Truffle framework
    * [Blog about Best Practices with Security Audits](https://medium.com/zeppelin-blog)
* [Advanced Workshop with Assembly](https://github.com/androlo/solidity-workshop)
* [Simpler Ethereum Multisig](https://medium.com/@ChrisLundkvist/exploring-simpler-ethereum-multisig-contracts-b71020c19037) - especially section _Benefits_

#### Gamification

* [OpenZeppelin Ethernaut](https://ethernaut.zeppelin.solutions)
* [Attacks on Smart Contracts](https://www.cryptologie.net/article/423/attacks-on-ethereum-smart-contracts/)
* [Cryptozombies](https://cryptozombies.io/)
* [Capture the Ether](https://capturetheether.com/)

### Security Patterns
* [ConsenSys: Smart Contract Best Practices](https://github.com/ConsenSys/smart-contract-best-practices)
    * crucial information on security aspects of Smart Contract Development with Solidity
* [OpenZeppelin: Onwards with Smart Contracts Security](https://medium.com/zeppelin-blog/onward-with-ethereum-smart-contract-security-97a827e47702)

### Security Frameworks
* [Oyente - An Analysis Tool for Smart Contracts](https://github.com/melonproject/oyente)
* [Mythril - A Blockchain Exploration and Bug Discovery Framework](https://hackernoon.com/introducing-mythril-a-framework-for-bug-hunting-on-the-ethereum-blockchain-9dc5588f82f6)

### Upgradebility

* [Blog von Elena Dimitrova, Dev at colony.io](https://blog.colony.io/@elena_di)
    * https://blog.colony.io/writing-more-robust-smart-contracts-99ad0a11e948
    * https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88
* [Techblog von Aragon](https://blog.aragon.one/tagged/development)
    * [Library driven development](https://blog.aragon.one/library-driven-development-in-solidity-2bebcaf88736)
* [OpenZeppelin on Proxy Libraries](https://medium.com/zeppelin-blog/proxy-libraries-in-solidity-79fbe4b970fd)

### Development Environment

* [Dapp - Simple command line tool for Smart Contract development (Dappsys/MakerDAO)](https://dapp.readthedocs.io/)
* [Remix - Solidity IDE](http://remix.ethereum.org/)
* [Truffle](http://truffleframework.com/)

### Runtime Environment

* [Ganache - Personal Blockchain for Ethereum Development](https://github.com/trufflesuite/ganache)
* [Parity Demo-PoA Tutorial](https://wiki.parity.io/Demo-PoA-tutorial.html)
* [Cliquebait](https://github.com/f-o-a-m/cliquebait)
    * [Sample with individual account (extra-accounts)](https://gist.github.com/ice09/04d3272869cfa796d018636a36f23f17)

## Deployment

* [Truffle](http://truffleframework.com/)
* [Populus - Smart Contract development framework in Python](http://populus.readthedocs.io/en/latest/)

## Monitoring

* [Neufund - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) 

## Integration Patterns

### Frontend Integration

* [Designing the Architecture for your Ethereum Application](https://blog.zeppelin.solutions/designing-the-architecture-for-your-ethereum-application-9cec086f8317)
* [Web3 Design Patterns](https://medium.com/@lyricalpolymath/web3-design-principles-f21db2f240c1)

#### SPA with react.js
#### PoC User Management with MetaMask
### Middleware Integration
