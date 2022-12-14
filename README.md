# Mars_Money

"Mars Money" is a project created to develop a monetary system for a new Mars colony. This new monetary system is based
on blockchain technology. We will use blockchain technology to define a new cryptocurrency called `KaseiCoin`. ("Kasei" means
"Mars" in Japanese). KaseiCoin is a `ERC-20` compliant fungible token. This project will launch a `crowdsale` that will allow
people who are moving to Mars to convert their earthling money to KaseiCoin.

---

## Installations

No installations are necessary to view the use of this particular project.

---

## Technologies

This project uses solidity 0.5.5 and was operated on Remix in conjuction with the following add-ons.

* [Remix IDE](https://remix-project.org/) - The Remix Project is a rich toolset which can be used for complete
contract development.

* [Ganache](https://trufflesuite.com/ganache/) - A program that allows you to quickly set up a local blockchain, which you can use to test and develop
smart contracts.

* [Solidity](https://soliditylang.org/) - A programming language designed for developing smart contracts that run on Ethereum.

* [Metamask](https://metamask.io/) - A token wallet and digital asset exchange.

---
## Usage

`Ganache` is used to provide Ethereum accounts. The `Remix IDE` is launched for the use of smart contracts.
(See the Technologies section above for direct links).

The Following smart contracts where compiled and deployed.

```python
KaseiCoin.sol
KaseiCoinCrowdsale.sol
```
---
## Evaluation Evidence

### Screenshot of successful compilation of KaseiCoin contract.

![KaseiCoin contract](images/KaseiCoinContract.png)

### Screenshot of successful compilation of KaseiCoin Crowdsale constract.

![KaseiCoin Crowdsale](images/KaseiCrowdsale.png)

### Screenshot of successful compilation of KaseiCoin Deployer contract.

![KaseiCoin Deployer](images/KaseiCoinDeployer.png)

### Screenshots of token purchase and balance,metamask transaction and ganache accounts.

![balance](images/balanceof.png)
![metamask](images/metamask.png)
![ganache](images/ganache.png)

### Screenshot of total supply of minted tokens after purchase.

![total supply](images/totalsupply.png)

### Screenshot of wei that has been raised in the crowdsale contract.

![wei raised](images/weiraised.png)



# License
[MIT](license)

## Contributers
Hugo Velazquez

linkedin.com/in/hugoghvelazquez
