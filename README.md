# awesome-wanchain
A collection of resources related to Wanchain

# About

Awesome-wanchain aims to be the hub to find useful information about the Wanchain network. 
__This document is intended to serve our community and we hope you will be able to contribute to it ! If you find anything missing  please feel free to make a pull request.__

# Overview Of Wanchain


[Wanchain](https://wanchain.org) is a public blockchain working on solving cross-chain interoperability. 

The financial ecosystem of tomorrow will be built on many assets relying on heterogeneous chains, protocols and technologies. Wanchain aims to link all these assets, in a decentralized trustless and permissionless manner.

A decentralized interoperability solution is the required component that’s necessary to create a new financial system.  The current industry is relying on too many third parties such as centralized exchanges and custodians in order to operate. 

The whole purpose of Blockchain technology was to create a decentralized world where value and data could flow freely without intermediaries, in a fully peer to peer manner.

Wanchain aims to become a hub, where financial applications will host services that provide access to assets such as BTC/ETH/ERC20s, with many more blockchain integrations planned for the near future.

We integrated Ethereum in our 2.0 release, which means users can now transfer ETH to Wanchain. Bitcoin integration is currently on beta testnet as well as the DAI stable coin and MKR token. The release of 3.0 (Bitcoin and ERC20 integration) allows DEXs built on Wanchain to list ETH/BTC trading pairs for the **first time in the industry.**

We already proved that our approach to solving the cross-chain transfer of assets works between 2 networks that use different hashing functions. We can lock assets on native chains and issue their worth in proxy tokens which can be redeemed for the underlying asset at any moment. The entire process is distributed and will be fully decentralized with the advent of POS in 2019. 

Below is a collection of resources for anyone interested in learning more about Wanchain or building on our platform.

---
## Table of Contents
- [Official Links](#official-links)
- [Official Communication Channels](#official-communication-channels)
- [Media](#media)
   - [Beginner Guides](#beginner-guides)
   - [Tutorials](#tutorials)
   - [Technology Analysis](#technology-analysis)
      - [Dive into Secure Multi Party Computation](#dive-into-secure-multi-party-computation)
      - [Dive into Sharmir's Secret Sharing Scheme](#dive-into-sharmir's-secret-sharing-scheme)
   - [AMAs And Messages To Community](#amas-and-messages-to-community)
   - [Important Milestones](#technology-analysis)
   - [Partnerships And Collaborations](#partnerships-and-collaborations)  
   - [Interviews And Conferences](#interviews-and-conferences)  
   - [Articles And Videos](#articles-and-videos )  
- [Get Wancoins](#get-wancoins)
- [Tools](#tools)
   - [Store your Wancoins](#store-your-wancoins)
       - [Hardware wallets](#hardware-wallets)
       - [Extension wallets](#extension-wallets)
       - [Web wallets](#web-wallets)
       - [Mobile wallets](#mobile-wallets)         
   - [Explorers](#explorers)
   - [Faucets](#faucets)
   - [Wanchain Name Server](#wanchain-name-service)
- [New developers start here](#new-developers-start-here)
- [Developer Resources](#developer-resources)
   - [Smart Contract Languages](#smart-contract-languages)
   - [Frameworks](#frameworks)
   - [IDEs](#ides)
   - [Github Repos](#github-repos)
   

**Official Links**
--

- [Main website](https://wanchain.org)
- [Whitepaper](https://wanchain.org/files/Wanchain-Whitepaper-EN-version.pdf) 
- [Yellow paper](https://wanchain.org/files/Wanchain-Yellowpaper-EN-version.pdf) 
- [Commercial paper](https://wanchain.org/files/Wanchain-Commercial-Whitepaper-EN-version.pdf)
- [Official wallet download page](https://wanchain.org/product)
- [Explorer](https://www.wanscan.org/)

## Official Communication Channels


- [Twitter](https://twitter.com/wanchain_org)
- [Reddit](https://www.reddit.com/r/wanchain/)
- [Medium](https://medium.com/wanchain-foundation)
- [Youtube](https://www.youtube.com/channel/UCW_i8cncT0d1RyX7YCA_oKQ)
- [Telegram Chat](https://t.me/WanchainCHAT)
- [Telegram Ann](https://t.me/WanchainANN)
- [Discord](https://discord.gg/6mp442)

---
# Media

### Beginner Guides 

- [Overview Of Wanchain](https://coincentral.com/wanchain-beginner-guide/) - Article by Stillman
- [Wanchain Introduction Video](https://www.youtube.com/watch?v=caCXal3ZwfA&feature=youtu.be) - Video by Wanchain
- [The Importance Of Blockchain Interoperability](https://medium.com/wanchain-foundation/the-importance-of-blockchain-interoperability-b6a0bbd06d11) - Article by Jack Lu
- [Wanchain - A new way of connection Blockchains](https://medium.com/@interblockchains/wanchain-interoperability-420e5022c138) - Article by Oliver Birch
- [An Overview of the Wanchain Cross-Chain Implementation Model](https://medium.com/wanchain-foundation/an-overview-of-the-wanchain-2-0-cross-chain-implementation-model-c455cfd25664) - Article by Dan Reecer
- [What is Wanchain?](https://coincentral.com/wanchain-beginner-guide/) - Article by CoinCentral(.com)
- [Wanchain Architecture](https://www.reddit.com/r/wanchain/comments/7qyixh/still_skeptical_would_anyone_who_understands_the/dstb7lk) - Reddit post by u/phoeniciaStrategy

### Tutorials

- [How To Deploy Smart Contract On Wanchain](http://www.wanchaindocs.org/en/latest/contracts-and-transactions/how-to-deploy-smart-contract.html) - Wanchain Documentation
- [Developing Wanchain Applications](https://wanchain.org/files/WanchainHackathonHandbook_SanJose.pdf) - Hackathon Handbook by Weijia Zhang
- [Trezor Wallet for Wan](https://www.wanchain.org/files/wanchain_trezor_wallet_overview.pdf) - Instruction manual to setup Wan on Trezor
- [Ledger Wallet For Wan](https://wanchain.org/files/Wanchain_Ledger_Wallet_Overview.pdf) - Instruction manual to setup Wan on Ledger wallet
- [Wanwallet 2.0 Cross chain transactions](https://github.com/wanchain/go-wanchain/wiki/Wanwallet-2.0-Cross-chain-transactions) - Instruction to initiate cross chain transaction using our Wanwallet 

### Technology Analysis 

The 2 core technologies that allow Wanchain's cross chain functionalities to securely work are SMPC(Secure Multi Party Computing) and SSSS (Shamir's Secet Sharing Scheme) 

- [Introduction to Shamir's Secret Sharing and Secure Multi Party Computing](https://medium.com/wanchain-foundation/secure-multiparty-computation-and-shamirs-secret-sharing-on-wanchain-e502012b80ef) - Article by Oliver Birch that goes in depth into the 2 core components of Wanchain's technology

#### Dive into Secure Multi Party Computation

- [Tutorial on Secure Multi Party Computation](https://www.iitk.ac.in/eeold/archive/courses/2013/intel-info/d4pdf1.pdf) - Presentation by Somitra Sanadhya
- [Protecting Privacy with Secure Multi Party Computation](https://www.newamerica.org/oti/blog/protecting-privacy-secure-multi-party-computation/) - Blog post by Christopher Sadler
- [awesome-mpc](https://github.com/rdragos/awesome-mpc) - A collection of resources to learn more about MPC compiled by rdragos

#### Dive into Sharmir's Secret Sharing Scheme

- [What is Shamir's Secret Sharing Scheme?](http://point-at-infinity.org/ssss/) - Article published on point-at-infinity(.org)
- [Splitting your secrets with Shamir's Secret Sharing Scheme](https://www.future-processing.pl/blog/splitting-your-secrets-with-shamirs-secret-sharing-scheme/) - Technical Blog by Michal Witas on Future Processing
- [Example implementation of Shamir's Secret Sharing in Java](https://github.com/timtiemens/secretshare) - Github Repo by timtiemens

### AMAs And Messages To Community 

- [A Letter To The Wanchain Community](https://medium.com/wanchain-foundation/a-letter-to-our-community-8bba64ff1cc0) - Letter by Jack Lu 
- [Wanchain Reddit AMA](https://www.reddit.com/r/wanchain/comments/8wnrj5/wanchain_reddit_ama_is_live/) - AMA by Wanchain team
- [CryptoCurve And Wanchain AMA](https://www.reddit.com/r/wanchain/comments/9qpug9/crypto_curve_and_wanchain_ama/) - AMA by Wanchain and Cryptocurve teams
- [This Is Wanchain Ask Us Anything](https://www.reddit.com/r/wanchain/comments/7qkh8m/this_is_wanchain_ask_us_anything/) - AMA by the Wanchain team
- [Meet The Wanchain Team](https://www.youtube.com/watch?v=Itsbuh1HtJY) - Video by Wanchain
- [The Path Toward a Decentralized Financial System](https://medium.com/wanchain-foundation/the-path-towards-a-decentralized-financial-system-250e763dc00d) - Article by Johann Eid

### Important Milestones 

- [Wanchain 3.0 Alpha Testnet Is Live](https://medium.com/wanchain-foundation/wanchain-3-0-bridging-bitcoin-ethereum-alpha-testnet-is-live-4fe89a6c1f05) - Article by Jack Lu
- [Wanchain's Bridge To The Ethereum Blockchain Is Now Open](https://altcointoday.com/wanchains-bridge-to-the-ethereum-blockchain-is-now-open/) - Article by AltcoinToday(.com) for the release of version 2.0 
- [Wanchain's Mainnet Is Live Video](https://www.youtube.com/watch?v=sxQe0NiZvB0) - Short video by Wanchain

### Partnerships And Collaborations

- [MakerDAO’s Dai Stablecoin and MKR are Live on Wanchain, Bringing Interoperability with Bitcoin](https://medium.com/wanchain-foundation/makerdaos-dai-stablecoin-and-mkr-are-live-on-wanchain-bringing-interoperability-with-bitcoin-98d7d808d996) - Article by Johann Eid
- [Wanchain Adds Real-World Data with Chainlink Integration and Partnership](https://medium.com/wanchain-foundation/wanchain-adds-real-world-data-in-partnership-with-chainlink-a7ecf919e181) - Article by Dan Reecer 
- [Wanchain Joins The Ethereum Entreprise Alliance](https://medium.com/wanchain-foundation/wanchain-joins-the-enterprise-ethereum-alliance-6822dfb659d2) - Article by Michael Picone 
- [0xcert and Wanchain enter Stretegic Alliance](https://0xcert.org/news/0xcert-and-wanchain-strategic-alliance/) - Article by 0xcert
- [Wanchain Teams Up With Various Austin Companies to Form Regional Blockchain Innovation Hub](https://www.crowdfundinsider.com/2018/02/128591-wanchain-teams-various-austin-companies-form-regional-blockchain-innovation-hub/) - Article by Samantha Hurst


### Interviews And Conferences 

- [Jack Lu's Interview On Wanchain](https://www.youtube.com/watch?v=-GQtPvL2qqM) - Interview by Eugene Tay
- [Jack Lu's Speech On Wanchain And Its Ecosystem](https://www.youtube.com/watch?v=OeOp0BkZP9U&t=1s) - Speech at Beyond Blocks
- [Interview With Jack Lu, Founder And CEO At Wanchain](https://medium.com/@liluzivertcoin/interview-with-jack-lu-founder-and-ceo-wanchain-1a994e43ef1a) - Interview by Uzi
- [Texas Bitcoin Conference](https://www.youtube.com/watch?v=CxL8Saqx5qA&t=1938s) - Jack Lu presenting at Texas Bitcoin conference
- [Austin Blockchain Collective - Town Hall](https://www.youtube.com/watch?v=T2vy7kgTENc&feature=youtu.be&t=3453) - Wanchain team presenting at Austin Blockchain conference
- [Oliver Birch Interview](https://www.youtube.com/watch?v=ca0uHqiZmsM&feature=youtu.be) - Interview by CryptoDealers
- [Scott Trowbridge and Oliver Birch Interview](https://www.youtube.com/watch?v=7PUauCKQP1c&t=1s) - Interview by Crypto Bulk
- [Interviw With Oliver Birch And Dan Reecer About Marketing And Community](https://www.youtube.com/watch?v=HOuEqQ9HqTE) - Interview by Unifi
- [Johann Eid's Presentation Of Wanchain](https://www.youtube.com/watch?v=OuCxORB2Uqg) - Conference at StartupToken
- [Oliver Birch And Johann Eid Talk About Wanchain](https://www.youtube.com/watch?v=cNhKLb5BCOw&t=604s) - Wanchain's meetup in France
- [Wanchain Introduction For 2.0](https://www.youtube.com/watch?v=pDZk5_O32Yw) - Conference at Wuhzen World Blockchain Conference

### Articles And Video About Us :heart:

- [Cryptocurrencies With Working Products](https://www.investinblockchain.com/top-cryptocurrencies-working-products/) - Article by Invest In Blockchain (.com). Wanchain mentioned as one of the few cryptos with a working product
- [Wanchain Review](https://www.youtube.com/watch?v=QB2_5EFRjGw) - Video by the Crypto Lark

---
# Find Wancoins

### Exchanges 

- [Wanchain markets](https://coinmarketcap.com/fr/currencies/wanchain/#markets)
- [Binance](https://www.binance.com/en/trade/WAN_BTC)
- [Huobi](https://www.huobi.com/)
- [Kucoin](https://www.kucoin.com/#/)
- [Bitrue](https://www.bitrue.com/)
- [Bitkub](https://www.bitkub.com/)
- [Dragonex](https://dragonex.io/)
- [Bitbns](https://bitbns.com/)

---
# Tools


### Store Your Wancoins


#### Hardware Wallets
  
- [Trezor](https://trezor.io/) - The first hardware walllet
- [Ledger Nano S](https://www.ledger.com/products/ledger-nano-s) - The French hardware wallet :blush: 
  
#### Extension Wallets

- [Wanmask](https://wanmask.io/)
  
#### Web Wallets

- [MyWanWallet](http://mywanwallet.com/) - Open source web wallet with Wancoin and WRC20 support 

#### Mobile Wallets

- [Trust Wallet](https://trustwallet.com/) - Binance's official wallet supports Wancoin 
  
#### Explorers
 
- [Wanchain block explorer](https://www.wanscan.org/) - The official Wanchain explorer
- [Wanscan](https://wanscan.io/home) - A community built block explorer
- [Wanchain network stats ](https://wanstats.net//)

#### Faucets

- [WanFaucet](https://wanfaucet.net/) - Instantly get Wancoins to fund your OTA transactions 

#### Wanchain name service 

- [Portal Network](https://www.portal.network/) - Portal Network supports the auction and trading of Wanchain domain names
- [MyWanWallet](http://mywanwallet.com/) - MyWanWallet supports the auction and trading of Wanchain domain names

# Developer Tools 

Wanchain leverages the EVM. As such, any tools that Ethereum are familiar with can be used on Wanchain. Here is a list of  tools developers can use to build on Wanchain. It that was copied fom this [Ethereum developers tools list](https://github.com/ConsenSys/ethereum-developer-tools-list) compiled by our awesome friends at Consensys! 

## New developers start here
* [Solidity](http://solidity.readthedocs.io/en/latest/) - The most popular smart contract language.
* [Truffle](http://truffleframework.com) - Most popular smart contract development, testing, and deployment framework. Install the cli via npm and start here to write your first smart contracts.
* [Wanmask](https://wanmask.io/) - Chrome extension wallet to interact with Dapps.
* [Truffle boxes](http://truffleframework.com/boxes/) - Packaged components for the Ethereum ecosystem

## Developer Resources
### Developing Smart Contracts
#### Smart Contract Languages
* [Solidity](http://solidity.readthedocs.io/en/latest/)- EVM smart contracting language
* [Bamboo](https://github.com/pirapira/bamboo) - A morphing smart contract language
* [Vyper](https://github.com/ethereum/vyper) - New experimental pythonic programming language
* [LLL](https://media.consensys.net/an-introduction-to-lll-for-ethereum-smart-contract-development-e26e38ea6c23) - Low-level Lisp-like Language
* [Flint](https://docs.flintlang.org/) - New language under development with security features including asset types, state transition, and safe integers

#### Frameworks
* [Truffle](http://truffleframework.com) - Most popular smart contract development, testing, and deployment framework. The Truffle suite includes Truffle, and [Drizzle](https://github.com/truffle-box/drizzle-box) and Ganache, which we forked and adapted to Wanchain with [Wanache](https://github.com/C3Devs/wanache)
* [Embark](https://github.com/embark-framework/embark) - Framework for DApp development
* [Dapp](https://dapp.tools/dapp/) - Framework for DApp development, successor to DApple
* [Populus](https://github.com/ethereum/populus) - The EVM development framework with the most cute animal pictures
* [Etherlime](https://github.com/LimeChain/etherlime) - ethers.js based framework for Dapp deployment


#### IDEs
* [Remix](https://remix.ethereum.org/) - Web IDE with built in static analysis, test blockchain VM.
* [Superblocks Lab](https://superblocks.com/lab/) - Web IDE. Built in browser blochain VM, Metamask integration (one click deployments to Testnet/Mainnet), transaction logger and live code your WebApp among many other features.
* [Atom](https://atom.io/) - Atom editor with [Atom Solidity Linter](https://atom.io/packages/atom-solidity-linter), [Etheratom](https://atom.io/packages/etheratom)
* [Pragma](https://www.withpragma.com/) - Very simple web IDE for solidity, and auto-generated interfaces for smart contracts.
[autocomplete-solidity](https://atom.io/packages/autocomplete-solidity), and [language-solidity](https://atom.io/packages/language-solidity) packages
* [Vim solidity](https://github.com/tomlion/vim-solidity) - Vim syntax file for solidity
* [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - Visual Studio Code extension that adds support for Solidity
* [Intellij Solidity Plugin](https://github.com/intellij-solidity/intellij-solidity/wiki) - Open-source plug-in for [JetBrains IntelliJ Idea IDE](https://www.jetbrains.com/idea/) (free/commercial) with syntax highlighting, formatting, code completion etc.
* [YAKINDU Solidity Tools](https://github.com/Yakindu/solidity-ide) - Eclipse based IDE. Features context sensitive code completion and help, code navigation, syntax coloring, build in compiler, quick fixes and templates.
* [Eth Fiddle](https://ethfiddle.com/) - IDE developed by [The Loom Network](https://loomx.io/) that allows you to write, compile and debug your smart contract. Easy to share and find code snippets.

#### Github Repos
- [Wanx](https://github.com/wanchain/wanx) - Utility for making cross chain transactions on the wanchain network.  
- [go-wanchain](https://github.com/wanchain/go-wanchain) - Official go implementation of the Wanchain client
- [Wanchain ICO verification tool](https://github.com/wanchain/wanchain-ico-verification) - Wanchian ICO verification tool
- [wanchain storeman](https://github.com/wanchain/wanchain-js-storeman) - Storemen code 
- [wanchain crosschain contracts](https://github.com/wanchain/wanchain-crosschain-contracts) - Wanchain crosschain contracts 
- [wanchain name service](https://github.com/wanchain/wns) - Wanchain Name service 

# Interoperability Overview 

### Media 

- [Comparison of Inter-Blockchain Communication Technologies](http://troubles.md/posts/comparison-of-inter-blockchain-communication-technologies/) - Article sponsored by Parity
- [Blockchains Are Verticalizing, So We Need Interoperability](https://www.forbes.com/sites/adrianbridgwater/2018/02/07/blockchains-are-verticalizing-so-we-need-interoperability/#d98e6017ab95) - Article published by Forbes (.com)
- [Looking Ahead To Blockchain Interoperability : Issues And Future Solutions](https://blockonomi.com/blockchain-interoperability/) - Article published by Blockonomi (.com)
- [The Opportunity For Interoperable Chains Of Chains](https://multicoin.capital/2018/01/27/opportunity-interoperable-chains-chains/) - Article published by Multicoin capital (.com)
- [Cross-chain infrastructure](https://blog.havven.io/cross-chain-infrastructure-eebe7ad7d7a2) - Blog by Havven 


### Other Projects 

- [Blocknet](https://www.blocknet.co/)
- [Cosmos](https://cosmos.network/)
- [Polkadot](https://polkadot.network/)
- [Aion](https://aion.network/)
- [Lamden](https://lamden.io/)
- [Icon](https://icon.foundation/)
- [ARK](https://ark.io/)
- [Quant Network](https://www.quant.network/)
- [ARK](https://ark.io/)
- [Block Collider](https://www.blockcollider.org/)

