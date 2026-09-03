
# Awesome Hive [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)[<img src="hive@185x160.png" alt="Hive Logo" align="right" height="80">](https://hive.io)

Hive is an open source platform built for blockchain social networks, games and different applications that is fast and scalable.

This is a curated list of awesome Hive frameworks, libraries, applications and resources. Contributions welcome. Add links through pull requests or create an issue to start a discussion.

## Contents
- [Introduction](#introduction)
- [Infrastructure](#infrastructure)
- [Layer 2](#layer-2)
- [SDKs](#sdks)
- [Tutorials](#tutorials)
- [Tools / Utilities](#tools--utilities)
- [dApps](#dapps)
- [Services](#services)
  - [Hive DAO](#hive-dao)
  - [Account Creation](#account-creation)
- [Resources](#resources)
  - [General Community](#general-community)
  - [Developer Community](#developer-community)
  - [Conferences](#conferences)
  - [Projects Summary](#projects-summary)

## Introduction

*Documents & videos about Hive*

- [Developer Portal](https://developers.hive.io/) - The developer portal of Hive.
- [Quickstart](https://developers.hive.io/quickstart/) - Getting started guide on the developer portal.
- [API Definitions](https://developers.hive.io/apidefinitions/) - Reference for every hived and Hivemind API method.
- [Interactive API](https://api.hive.blog/) - Swagger UI for the public Hive API node.
- [Hive Glossary](https://developers.hive.io/glossary/#glossary-chain-basics) - Understanding the common terms used by the Hive blockchain.
- [Whitepaper](https://hive.io/whitepaper.pdf) - The Hive whitepaper.
- [Technical Vision](https://hive.blue/docs/technical-vision.pdf) - Long term technical vision document for Hive.
- [Roadmap](https://hive.io/en/roadmap/) - Development roadmap on hive.io.
- [Hive Chain Documentation](https://hivedocs.info/) - Community maintained documentation hub for Hive.

## Infrastructure

*The Hive blockchain infrastructure*

- [Hive](https://hive.io/eco) - Fast, scalable, powerful blockchain for Web3.0, ([code](https://gitlab.syncad.com/hive/hive), [GitHub mirror](https://github.com/openhive-network/hive)).
- [HAF](https://gitlab.syncad.com/hive/haf) - Hive Application Framework, PostgreSQL based framework for building robust and scalable Hive APIs and apps.
- [Hivemind](https://gitlab.syncad.com/hive/hivemind) - HAF based social media API server powering Hive frontends.
- [HAfAH](https://gitlab.syncad.com/hive/hafah) - HAF based account history API server.
- [HAF API Node](https://gitlab.syncad.com/hive/haf_api_node) - Docker compose stack for running a full HAF API node.
- [HAF Block Explorer](https://gitlab.syncad.com/hive/haf_block_explorer) - HAF based API server for block explorers, ([UI](https://gitlab.syncad.com/hive/block_explorer_ui)).
- [Balance Tracker](https://gitlab.syncad.com/hive/balance_tracker) - Example pure SQL HAF app for graphing account balances.
- [Reputation Tracker](https://gitlab.syncad.com/hive/reputation_tracker) - HAF app computing account reputations.
- [HiveSense](https://gitlab.syncad.com/hive/hivesense) - HAF app for semantic search over Hive posts using ML embeddings.
- [Drone](https://gitlab.syncad.com/hive/drone) - Caching reverse proxy for JSON-RPC requests, replaces Jussi.
- [Imagehoster](https://gitlab.syncad.com/hive/imagehoster) - Image upload and proxy service used by Hive frontends.
- [Denser](https://gitlab.syncad.com/hive/denser) - Next generation social media frontend for Hive.

## Layer 2

*Sidechains and second layer networks built on Hive*

- [Hive-Engine](https://hive-engine.com/) - Smart contracts, tokens, NFTs and tribes on Hive, ([code](https://github.com/hive-engine/hivesmartcontracts)).
- [Magi Network](https://magi.eco/) - Cross chain interoperability and smart contract network powered by Hive, formerly VSC, ([code](https://github.com/vsc-eco/go-vsc-node)).
- [SPK Network](https://spk.network/) - Decentralized storage and media infrastructure for Hive, ([code](https://github.com/spknetwork)).

## SDKs

*SDKs for common languages*

- JavaScript / TypeScript
  - [wax](https://gitlab.syncad.com/hive/wax) - Official multi-language Hive protocol library for TypeScript and Python, ([npm](https://www.npmjs.com/package/@hiveio/wax)).
  - [beekeeper](https://gitlab.syncad.com/hive/beekeeper) - Key management and signing library from the Hive core team, ([npm](https://www.npmjs.com/package/@hiveio/beekeeper)).
  - [workerbee](https://gitlab.syncad.com/hive/workerbee) - Automation and bot library built on wax and beekeeper, ([npm](https://www.npmjs.com/package/@hiveio/workerbee)).
  - [hive-js](https://www.npmjs.com/package/@hiveio/hive-js) - JavaScript library for Hive blockchain.
  - [dhive](https://www.npmjs.com/package/@hiveio/dhive) - JavaScript library for Hive blockchain in Typescript.
  - [hive-tx](https://github.com/mahdiyari/hive-tx) - Lightweight TypeScript SDK for creating, signing and broadcasting Hive transactions.
  - [hive-uri](https://github.com/openhive-network/hive-uri) - Encode Hive operations and transactions into URIs.
  - [Ecency SDK](https://www.npmjs.com/package/@ecency/sdk) - React Query based queries and mutations for Hive apps, ([code](https://github.com/ecency/vision-web)).
  - [hivesigner](https://www.npmjs.com/package/hivesigner) - Hivesigner OAuth2 SDK, ([code](https://github.com/ecency/hivesigner-sdk)).
  - [keychain-sdk](https://github.com/hive-keychain/keychain-sdk) - Typed wrapper around Hive Keychain requests.
  - [Aioha](https://aioha.dev/) - All-in-one Hive authentication API supporting Keychain, HiveAuth, Hivesigner, Ledger and PeakVault, ([code](https://github.com/aioha-hive/aioha)).
- Python
  - [wax](https://gitlab.syncad.com/hive/wax) - Official Hive protocol library, Python package built from the same repository.
  - [hive-nectar](https://github.com/srbde/hive-nectar) - Maintained successor of beem, comprehensive Python library for Hive, ([PyPI](https://pypi.org/project/hive-nectar/)).
  - [nectarengine](https://github.com/srbde/nectarengine) - Python library and CLI for Hive-Engine tokens.
  - [lighthive](https://github.com/emre/lighthive) - A light Python client to interact with the Hive blockchain.
- Ruby
  - [hive-ruby](https://gitlab.syncad.com/hive/hive-ruby) - Ruby library for the Hive blockchain.
- Rust
  - [Xylem](https://github.com/srbde/hive-xylem) - Early stage Hive SDK for Rust.

## Tutorials

*Tutorials for getting started with Hive*

- JavaScript
  - [Developer Portal JavaScript Tutorial](https://developers.hive.io/tutorials/#tutorials-javascript) - JavaScript Tutorials for the Developer Portal, ([code](https://gitlab.syncad.com/hive/devportal/-/tree/develop/tutorials/javascript)).
- Python
  - [Developer Portal Python Tutorial](https://developers.hive.io/tutorials/#tutorials-python) - Python Tutorials for the Developer Portal, ([code](https://gitlab.syncad.com/hive/devportal/-/tree/develop/tutorials/python)).
- Ruby
  - [Developer Portal Ruby Tutorial](https://developers.hive.io/tutorials/#tutorials-ruby) - Ruby Tutorials for the Developer Portal, ([code](https://gitlab.syncad.com/hive/devportal/-/tree/develop/tutorials/ruby)).

## Tools / Utilities

*Useful tools/utilities when building with Hive*

- Block Explorer
  - [Hive Block Explorer](https://explore.openhive.network/) - Official HAF based block explorer, ([code](https://gitlab.syncad.com/hive/block_explorer_ui)).
  - [Hivexplorer](https://hivexplorer.com/) - Block, transaction and account explorer, ([code](https://github.com/ecency/hivexplorer)).
  - [HiveHub](https://hivehub.dev/) - Block explorer and hub for multiple Hive tools.
  - [HiveScan](https://hivescan.info/) - Block explorer with proposals and witness views.
  - [Hive at Ausbit](https://hive.ausbit.dev/) - Block explorer and account tools by [@ausbitbank](https://peakd.com/@ausbitbank).
  - [HIVE Block Explorer](https://hiveblockexplorer.com/) - Block explorer by [@penguinpablo](https://hive.blog/@penguinpablo).
  - [Hive-Engine Explorer](https://he.dtools.dev/) - Explorer for the Hive-Engine sidechain.
- Search
  - [Hivesearcher](https://hivesearcher.com/) - Full text search engine for Hive posts and comments.
- Authentication / Wallet
  - [Hive Keychain](https://hive-keychain.com/) - Browser extension and mobile wallet for Hive, ([extension](https://github.com/hive-keychain/hive-keychain-extension), [mobile](https://github.com/hive-keychain/hive-keychain-mobile)).
  - [HiveAuth](https://hiveauth.com/) - Decentralized authentication for web, desktop and mobile apps without sharing keys, ([code](https://github.com/hiveauth)).
  - [Hivesigner](https://hivesigner.com) - OAuth2 style signer and login for Hive apps, ([code](https://github.com/ecency/hivesigner-ui)).
  - [PeakVault](https://vault.peakd.com/) - Browser extension wallet by the PeakD team.
  - [Vessel](https://gitlab.syncad.com/hive/vessel) - Desktop wallet for Hive from the core team, ([releases](https://gitlab.syncad.com/hive/vessel/-/releases)).
  - [Hive Ledger Wallet](https://hiveledger.io/) - Web wallet for Ledger hardware devices, ([Ledger app](https://gitlab.com/engrave/ledger/app-hive)).
  - [Hive MetaMask Snap](https://snaps.metamask.io/snap/npm/hiveio/metamask-snap/) - Sign Hive transactions from MetaMask, ([code](https://gitlab.syncad.com/hive/metamask-snap)).
  - [HiveWallet.app](https://hivewallet.app/) - Fast, secure and open source web wallet for Hive, ([code](https://github.com/roelandp/hivewallet)).
  - [Hiveblog Wallet](https://wallet.hive.blog) - The wallet functionality of Hiveblog Condenser, ([code](https://gitlab.syncad.com/hive/wallet)).
- Data Service
  - [HiveSQL](https://hivesql.io/) - A publicly available Microsoft SQL database containing all the Hive blockchain data.
  - [HafSQL](https://mahdiyari.gitlab.io/hafsql/) - Public PostgreSQL access to a HAF database.
- Node Status
  - [Hive Node Beacon](https://beacon.peakd.com/) - Health and latency monitor for public API nodes.
- Witness
  - [Witness List](https://explore.openhive.network/witnesses) - Witness ranking on the official block explorer.
  - [Witness List](https://hive.arcange.eu/witnesses/) - Witness List by [@arcange](https://hive.blog/@arcange).
  - [Witness Block Production Schedule](https://hive.arcange.eu/schedule/) - Tool for monitoring block production by witnesses.
- Statistics
  - [HiveStats](https://hivestats.io/) - Track and analyze Hive accounts, rewards and curation.
  - [HiveBuzz](https://hivebuzz.me/) - Badges, achievements and statistics for Hive accounts.
  - [HiveTasks](https://hivetasks.com/) - Account tools and statistics for Hive users.
  - [Rayo](https://rayo.gg/chain/hive) - Usage statistics for dApps on Hive.

## dApps

*Some cool dApps powered by Hive*

- Social Blogging
  - [Hive.blog](https://hive.blog) - The 1st blog dApp for Hive, ([code](https://gitlab.syncad.com/hive/condenser)).
  - [Ecency](https://ecency.com/) - A powerful frontend dApp for Android, iOS, Desktop and Web, ([web](https://github.com/ecency/vision-web), [mobile](https://github.com/ecency/vision-mobile)).
  - [PeakD](https://peakd.com) - User-friendly full-fledged blogging dApp for Hive.
  - [InLeo](https://inleo.io) - Social and finance focused frontend with threads, formerly LeoFinance.
  - [Waivio](https://www.waivio.com/) - Social platform with object reviews and business pages on Hive.
  - [Liketu](https://liketu.social/) - Photo sharing community on Hive.
  - [dBlog](https://dblog.org/) - Personal blog websites powered by Hive, by Engrave.
- Video
  - [3Speak](https://3speak.tv/) - Video sharing community that rewards creators and curators.
  - [DTube](https://d.tube/) - Decentralized video sharing community that rewards creators and curators, ([code](https://github.com/dtube)).
- Music
  - [BlockTunes](https://blocktunes.net/) - Stream, own and earn from music on Hive.
- Travel
  - [TravelFeed](https://travelfeed.com/) - Travel blogging platform with maps and destination pages.
  - [WorldMapPin](https://worldmappin.com/) - Pin your travel posts on a world map.
- Fitness
  - [Actifit](https://actifit.io/) - Fitness tracking app that rewards activity, ([code](https://github.com/actifit/actifit-landingpage)).
- Game
  - [Splinterlands](https://splinterlands.com/) - A collectible trading card game on the Hive blockchain.
  - [Rising Star](https://www.risingstargame.com/) - Collectible card game based on the music industry.
  - [dCrops](https://dcrops.com/) - Farming play to earn game.
  - [Holozing](https://holozing.com/) - Creature collecting RPG.
  - [Terracore](https://www.terracoregame.com/) - Idle mining and battle game.
  - [Wrestling Organization Online](https://play.wrestlingorganizationonline.com/) - Wrestling manager card game.
  - [EXODE](https://exode.io/) - Strategy RPG about space colonization.
  - [Crypto Shots](https://crypto-shots.com/) - First person shooter with NFT assets.
  - [Rise of the Pixels](https://riseofthepixels.com/) - Game studio management game.
  - [Dungeon Cities](https://dungeoncities.com/) - City building and dungeon crawling game.
  - [Beat Brawls](https://beatbrawls.com/) - Music themed battle game.
  - [Stellarch](https://stellarch.io) - A deterministic, provably-fair trading card game on Hive where you draft a team, own your cards on-chain, and win with skill over spend. Closed alpha coming, waitlist open.
- Science
  - [STEMsocial](https://peakd.com/c/hive-196387) - Curation project dedicated to improving the quality of STEM content on Hive.
  - [PEvO](https://pevo.science/) - Open scientific publishing on Hive.
- Finance
  - [Tribaldex](https://tribaldex.com/) - Create and trade tokens and NFTs on Hive-Engine.
  - [Hivedex](https://hivedex.io/) - Interface for the internal HIVE and HBD market.
  - [Distriator](https://distriator.com/) - Spend HBD at merchants and earn cashback.
  - [V4V.app](https://v4v.app/) - Bridge between Hive and Bitcoin Lightning payments.
- NFT
  - [NFT Showroom](https://nftshowroom.com/) - Digital art marketplace on Hive.
- Automation
  - [Hive.vote](https://hive.vote) - Curation trails, fanbase and scheduled posts.
- Podcasting
  - [Podping](https://podping.cloud/) - Podcast feed update notifications written to Hive for the Podcast Index, ([code](https://github.com/Podcastindex-org/podping-hivewriter)).

## Services

Online tools and APIs to simplify development.

### Hive DAO

*Hive DAO is dedicated to improve the Hive platform*

- [Decentralized Hive Fund](https://developers.hive.io/services/#services-dhf) - Propose and vote for projects that improves Hive and promote its growth.
- [Proposals](https://peakd.com/proposals) - Browse and vote on DHF proposals, ([Hive.blog](https://wallet.hive.blog/proposals), [Ecency](https://ecency.com/proposals)).

### Account Creation

- [Signup for Hive](https://signup.hive.io/) - Overview of account creation options.
- [Join Hive](https://hive.io/en/join/) - Account creation page on hive.io.

## Resources

Where to find more resources about Hive.

### General Community

- [Hive Discord](https://discord.gg/QNPwpZH5jj) - General discord community to hangout and get started.
- [Hive Telegram](https://t.me/hiveblockchain) - Hive Telegram group.
- [OpenHive.Chat](https://openhive.chat/) - Off-chain chat with Hive based authentication.
- [Hive on X](https://x.com/hiveblocks) - Official Hive account on X.
- [Hive YouTube](https://www.youtube.com/c/Hivenetwork) - Hive network YouTube channel.
- [Hive Today](https://hivetoday.substack.com/) - Newsletter with weekly Hive ecosystem updates.
- [@hiveio](https://hive.blog/@hiveio) - Official Hive blog.

### Developer Community

- [HiveDevs Chat](https://discord.gg/4mn5S9t) - A Discord channel where Hive developers go to discuss Hive apps, development, libraries and related topics.
- [HiveDevs Community](https://peakd.com/c/hive-139531) - On-chain community for developer updates and discussion.

### Conferences

- [HiveFest](https://hivefe.st/) - Annual gathering for Hive users and the ecosystem.

### Projects Summary

- [Hive Ecosystem](https://hive.io/eco) - Selection of dApps, games and tools on hive.io.
- [Hive Projects](https://hiveprojects.io/) - A collection of cool projects built with or for Hive, ([code](https://github.com/wise-team/hiveprojects.io)).

---

If you have any question about this opinionated list, please contact [@good-karma](https://ecency.com/@good-karma) on Hive or open an issue on GitHub.
