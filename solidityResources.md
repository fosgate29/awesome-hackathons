## Smart Contracts that we use

* [TF Sale Contracts](https://github.com/tokenfoundry/smart-contracts/tree/master/packages/sale-contracts)
* [TF Token Contracts](https://github.com/tokenfoundry/smart-contracts/tree/master/packages/token-contracts)
* [TF State Machine Framework](https://github.com/tokenfoundry/smart-contracts/tree/master/packages/state-machine)
* [OpenZeppelin Solidity Framework](https://github.com/OpenZeppelin/openzeppelin-solidity)

## Documentation, Tutorials & Best Practices

* [Solidity Docs](http://solidity.readthedocs.io/en/latest/)
* [A Solidity Implementation of the State Machine Design Pattern](https://blog.tokenfoundry.com/a-solidity-implementation-of-the-state-machine-design-pattern/)
* [ConsenSys Smart Contracts Best Practices](https://consensys.github.io/smart-contract-best-practices/)
* Truffle docs/tutorials:
  * [Truffle Docs](http://truffleframework.com/docs/)
  * [Truffle Tutorials](http://truffleframework.com/tutorials/)
  * [Truffle Debugger](http://truffleframework.com/blog/announcing-full-portable-solidity-debugger)
* [I'm just learning blockchain development. Where should I start](https://github.com/gitcoinco/gitcoinco/issues/38)
* [Curated resource for Ethreum](https://github.com/djphillyg/awesome-ethereum)

* [Bare minimum tutorial on deploying smart contracts with python](https://github.com/adamyala/Your_First_Decentralized_Application_Python) (Optional, we will be using just javascrip)

## Code audits
* [0x Protocol v2 Audit](https://github.com/ConsenSys/0x_audit_report_2018-07-23)
* [Gnosis Multisig-wallet Audit](https://blog.zeppelin.solutions/gnosis-multisig-wallet-audit-d702ff0e2b1e)
* [Leverj audit](https://github.com/leverj/staking/tree/master/audit)
* [Aragon token audit](https://medium.com/@jbaylina/aragon-token-and-token-sale-audit-21cade332f1d)
* [Havven audit](https://havven.io/uploads/havven_bloctrax_security_audit_june-6th.pdf)


## Additional reading material

It is also really important to understand the underlying system when programming smart contracts, so here are a few resources for that:

* [Ethereum Whitepaper](https://github.com/ethereum/wiki/wiki/White-Paper)
* [EVM Guide](https://github.com/CoinCulture/evm-tools/blob/master/analysis/guide.md) (A little bit outdated)
* [Diving into the Ethereum VM](https://blog.qtum.org/diving-into-the-ethereum-vm-6e8d5d2f3c30)
* [Awesome Ethereum Virtual Machine](https://github.com/pirapira/awesome-ethereum-virtual-machine)
* [Ethereum Book](https://github.com/ethereumbook/ethereumbook)

## Hyperledger introduction
* [Hyperledger Fabric knowledge share: zoom recording](https://consensys.zoom.us/recording/play/AES3c_GqLFcbUIwZPcROfwURrVh8BtQlngpxbzVXCVEhUglNRyd8mbDRAAjdXo3o?autoplay=true&startTime=1537372415000)

## Cryptography lectures by Peter Robinson

* [Introduction to Security](https://zoom.us/recording/play/DUKWzd7WVYEmSv7RkSsLbKF1b9TatOxG1_WEIVcowhAfRylvYia-M2R-NIXUml5L?autoplay=true)
* [Cryptographic Algorithms](https://consensys.zoom.us/recording/play/zQT1BAnY57jsfwc3NUiatLVorJ5aJOOrTmdib1xjSPQnZH0CkTKM-px6gvDJqZW0)
* [Cryptographic Algorithms Advanced](https://zoom.us/recording/play/TOZJ9Sr_OjMFGji7JsQqXhYdQYzu3_nzCMfPS9hr3jo8dknFuVvc_HBIsBm0Komz?autoplay=true)
* [Crypto Terminology](https://consensys.zoom.us/recording/play/Z_LDCkFOWlLkbdLWsgRX40LvMjQzi_D0wEE1sKan43Keb_RFemUVmTj2fT6a_Kh2)

## TokenWork Demo Sessions - Mike Goldin talks about TCRs
* [Demo sessions list](https://docs.google.com/spreadsheets/d/1eZPqw7fKPbtB-66KjJy9w3FDRlJpKIzkKO_k-tUhokI/edit#gid=0)

## Cryptoeconomics
* [Curated list](https://github.com/jpantunes/awesome-cryptoeconomics)
* [Sample of Prominent Token Designs: Architectures and Cryptoeconomics](https://docs.google.com/document/d/1hKQjstP7iEi6mejAu9fl-gsXbW4bJa7-Anpewr3bjy0/edit#heading=h.nww78cdbz0u9)

## Kauri good articles
* [Decentralization](https://media.consensys.net/the-forgotten-side-of-decentralization-f713aaa8c8b4)
* [Non fungible tutorial](https://beta.kauri.io/collection/5b8fe388e727370001c942e4/non-fungible-token-tutorial-series)
* [Reducing mainnet transactions](https://beta.kauri.io/article/a66d50655f8746edb7df90de4b8eb416)



## Smart Contracts Exploits

* [Storage allocation exploit](https://medium.com/cryptronics/storage-allocation-exploits-in-ethereum-smart-contracts-16c2aa312743)
* [List of attacks](http://www.dasp.co/)
* [Array overflow attack](https://www.youtube.com/watch?v=gUqHgFuSsqg)

## Extra solidity tools

* [eth-gas-reporter](https://github.com/cgewecke/eth-gas-reporter)
  * It works only with TF smart contracts tests when it is ``yarn coverage``. The reason is because  ``coverage`` executes *testrpc* in a separate process. eth-gas-reporter fails when we use ``yarn test`` because Ganache runs in memory.
* [Merkle Tree](https://github.com/miguelmota/merkle-tree)
  * This can be used to build Merkle Tree proofs. 

## Additional tutorials

* [Practical Decompilation of Ethereum Smart Contracts](http://blog.ret2.io/2018/05/16/practical-eth-decompilation/)
* [Building and installing Ethereum compilers](https://www.youtube.com/watch?v=4qbJFpT1ecI&t=186s)

## Ethereum Scaling Solutions

* [Summary of Ethereum Scaling Solutions & Teams Working on Them](https://docs.google.com/spreadsheets/d/1BQ0bK_LhSQvxtvXryVoIcmxeKMuVJCq6oD0aS5_hpC8/edit#gid=0)

### State Channels
* [Alex Miller's Simple Payment Channel](https://blog.gridplus.io/a-simple-ethereum-payment-channel-implementation-2d320d1fad93)
* [Jeff Coleman's Overview of State Channels](http://www.jeffcoleman.ca/state-channels/)
* [Foundations of State Channel Networks](https://eprint.iacr.org/2018/320)
* [Generalized State Channels: Includes References to Several Resources](https://medium.com/spankchain/a-state-channels-adventure-with-counterfactual-rick-part-1-ce68e16252ea)
* [Machinomy's Medium Articles](https://medium.com/machinomy)
* [Connext Medium Articles](https://medium.com/connext)
* [L4 Generalized State Channels](https://medium.com/l4-media/generalized-state-channels-on-ethereum-de0357f5fb44)
##### State Channel Repos
* [Machinomy](https://github.com/machinomy/awesome-state-channels)
* [Raiden Network](https://github.com/raiden-network/raiden)
* [Spankchain](https://github.com/SpankChain/general-state-channels)
* [Connext](https://github.com/ConnextProject/Connext)

### Plasma
* [Plasma Whitepaper](http://plasma.io/plasma.pdf)
* [Alex Miller on Plasma](https://blog.gridplus.io/plasma-and-the-internet-of-money-ccf7d5e8c3be)
* [Eth Research: Plasma](https://ethresear.ch/c/plasma)
* [Minimum Viable Plasma](https://ethresear.ch/t/minimal-viable-plasma/426)
* [Plasma Cash](https://ethresear.ch/t/plasma-cash-plasma-with-much-less-per-user-data-checking/1298)
* [Plasma Implementation Calls](https://www.youtube.com/channel/UCG2MeKuKDJRK4gFNk-dQuZQ)
##### Plasma Repos
* [Omisego](https://github.com/omisego/plasma-mvp)
* [Fourth State](https://github.com/FourthState/plasma-mvp-rootchain)
* [Leverj](https://github.com/leverj)

### Sharding

### Proof of Stake (Casper)


# Style Guidelines

* Follow the official [Solidity Style Guide](https://solidity.readthedocs.io/en/latest/style-guide.html)
  * Constant variables should be listed in all capital letters.
  * Use succinct, descriptive names for functions and variables.
    * Example: `uint256 minContribution` versus `uint256 num` or `uint256 contrib`
  * For new functions, include a description of the expected functionality and parameters. 
  * Write tests for all your code. Use helper functions to make tests as short and concise as possible and use 
    good variable names. 
  * Use [Solium](https://github.com/duaraghav8/Solium) for Solidity linting. 

* For Javascript, use [ESlint](https://eslint.org/docs/user-guide/getting-started). 

* You can use [Git Commands](https://github.com/joshnh/Git-Commands) for a quick reference on Git. 

# Contribution Guidelines

## Step 1

* Create a new branch for each card (i.e. task) or relevantly grouped cards (i.e. If several small changes are 
  required as part of a large tasks, please group the changes into one branch.)
* Branch naming should follow the below convention: 
  * `chore/name-of-branch`: To be used for comment, variable name changes, updating compiler versions, or 
     routine updates in general that do not alter the main functionality of the code.
     * Example branch name for adding comments: `chore/clarify-comments`
  * `refactor/name-of-branch`: To be used when refactoring existing code. 
     * Example branch name for refactoring to add additional require()'s: `refactor/add-requires`
  * `feature/name-of-branch`: To be used when adding a new feature to existing code.
     * Example branch name for new feature: `feature/add-refund-function`
  * `bugfix/name-of-branch`: To be used when fixing a bug
     * Example branch name for bug: `bugfix/fix-reentrancy`
  
* Update Trello to reflect progress (i.e. In Progress). 
* If issues arise that prevent you from finishing the task, alert the team in Solidity Slack channel for 
  assistance. If issues continue without resolution, move the task to the Blocked category in Trello to reflect 
  status and put together a plan for resolution or mitigation. 

## Step 2

* Push changes to your respective branch. 
* Pull requests are meant for quick moves to merge. 
* If the task includes major design or functionality changes that may require extensive review and potential 
  refactoring, then alert the team in the Slack channel to provide comments on the commit.
* Update any relevant documentation for contract design. This may include: Github docs, google docs, diagrams, 
  etc.
* Once the branch is ready to be merged, open a pull request pointing towards the `develop` branch, not 
  `master`.
  * When opening a pull request, add team members for review. 
* When reviewing a pull request, leave comments with detailed feedback and ideas for resolution. If questions 
  arise, use the Solidity Slack channel to discuss thoughts. 
* Pull requests require at least one approval to merge. 

## Step 3

* Look to Trello for next available tasks. 
* If no available tasks, research advanced Solidity topics relevant to Token Foundry Key Initiatives and put 
  together summaries for the team. 

  
 
