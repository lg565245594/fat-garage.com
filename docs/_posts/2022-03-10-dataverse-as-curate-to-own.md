---
title: Dataverse as curate-to-own
author: jessie-li
categories: news
tags:
  - home
  - featured
 
image: assets/2022/03/10/2.png
---

<div align=center><img src="/assets/2022/03/10/2.png"/></div>

<div align=center>Dataverse is building a composable *Finder* system which tied to your unified&dynamic persona.</div>

## Problem


<div align=center><img src="/assets/2022/03/10/3.png"/></div>

1) We left our identity and split our attention across diff platforms online, we lack of a sound place to **maintain** our **unified persona** on the web, and left this great wealth to (big) tech companies to make profit. Now with the blockchain, we could be more active with our data and make benefits for our own.

2) With the privacy concern, we deserve a **secure space** to cultivate our unified persona.

## Solution

<div align=center><img src="/assets/2022/03/10/4.png"/></div>
Our solution is to create a **curate-to-own** layer, specifically you could curate the web into personal space and own your behavioral data.

As you can see, within the blockchain landscape, now we have 1) open assets on ethereum, layer 2 and other public blockchains. 2) infrastructure to enable data composition (we have AR, Ceramic, Filecoin, etc) 3) **what's next?**

<div align=center><img src="/assets/2022/03/10/10.png"/></div>


We give one answer by scratching and building a **curation layer** -- **dataverse**.

It's obvious that we split our attention among apps (youtube,twitter) and dApps (mirror,opensea,etc) during our onine-ing.

Dataverse is a secure space for you to curate and aggregate all your belongings generated on those platforms, to compose your unified persona gradually. Here are some questions to draw on:

**1) What is a curation layer?**

Previously when the users do book-marking, they have to interact with the central server in between, now they can curate directly via the protocol.

**2) Why curation layer makes the web ownable?**

a. Cryptography and signature Technology provide guarantee b. the viable design of streamID provided by open protocols like Ceramic.

**3) What's behavioral data? What's the relationship with curation?**

Behavioral data accumulates when you **interact with web3 open assets*** (the process of curation).

**Open assets are those issued without a central entity.*

## Architecture

<div align=center><img src="/assets/2022/03/10/5.png"/></div>
Data can be like defi, in terms of composability. With the technology like zero-knowledge proof, privacy-preserving computation going mature, this supposed to be the very exciting and concrete utility in ownership economy. Why not play our own data Legos?

i read about Vitalik's soulbound[2] and remembered Andy and Jasmine's discussion during kernel fireside about "proof of time (in virtual world) ", we are so troubled by how we could better spend our time on-line, part of the reason is that we rely much on the apps&platforms to "understand" us, but actually they can only do very little job and probably lead to exhaustion.

Let's detail the architecture: You access to all apps&dApps and generate all kinds of curation behavior via **DID** (signature and sign-in), which is controlled by your **private key.**

Your curation behavior is made up of data streams[3] (aka streamID). For instance, when you curate "jpgs" on opensea, videos on youtube or articles on mirror, your data flows in various streams. An streamID is the basic unit of data[4].

we use ceramic's composable data streams to create a private folder system. you can keep it fully private and curate multi-media assets and multi-chain assets are viable via different streams.

In that sense, Our curation behavior can be described through the connections of streamIDs. Imagine cells organizing themselves and forming organs, those streamIDs could form a hiphop🫀 in your dataverse.

## Dataverse (what's like?)

Here are 3 key features that grows🌱 with dataverse.

## "data wallet"

Just like metamask as your assets wallet, dataverse can be your "data wallet"
<div align=center><img src="/assets/2022/03/10/6.png"/></div>

## "Portable folder"

Just like *Finder*, your curations (in the future, data assets) can be categorized, filtered, removed and foresee-ably,composed.
<div align=center><img src="/assets/2022/03/10/7.png"/></div>


## Pluggability

As said, you maintain a **unified persona** in dataverse, which is totally under your control and can be plugged into any third party applications.

<div align=center><img src="/assets/2022/03/10/8.png"/></div>

## Potential impact

The first networked and secure folder system. It's scalable for you to apply batch curations and modify folder indexing trees on encrypted user tables;

Users can own their online behavior data. This makes off-chain data shareable across apps via pluggable SDKs;

Bridge web2 and web3 for tracking favorites in one place, e.g., NFT, Mirror, Youtube, Bilibili. Users can form a dynamic and unified persona via accumulated curations.

*More importantly, we are designing dataverse to be a tool that has the real utility and easy to use like in web2, also it is very different underneath with the data composability architecture.*

## Growth strategy

### Plug into **third party (d)apps.**

For example, we work with MOAC exhibition where they integrate dataverse sdk on website so users could secure their curations.

### Work with **web3 media** to explore decentralized **dynamic media**[5]

Curationa[6] is an important process of "advertising" good content, we are suggesting decentralized curation as a way of making the next "TIMES" "New Yorker" ;)

<div align=center><img src="/assets/2022/03/10/9.png"/></div>
*how about decentralize media and make it dynamic?*

Work with **artists and DAOs** to explore dynamic persona.[7]

## Future Use Cases

### dynamic NFT--

IF an artist wants to know the profiles of their auidences in order to create **dynamic NFTs**(more interactive pieces that combine the REAL&Shareable personality of the audiences) ,he/she can request for persona from his audiences.

For instance, Takentheorem's recent work reflects his attempt at **dynamicNFT[8]**: an NFT that reacts (adaptively) to the user's holdings of digital assets, generating corresponding visual changes while showing the dynamic connection between you and the DAOs. This is no longer a pre-set or static jpg/GIF, it changes according to YOUR on-chain behaviour, it is an "artwork about you". So it could be imaginable if we replace "on-chain behavior" into "curation behavior".

### data exchange--

We will design **datatoken** as a standard for exchanging data, datatoken can provide the basic conversion units for persona.

## Team

We are a distributed team across China (Beijing and Hangzhou); We started from filecoin accelerator and joined gitcoin grants three times where we receive massive support from the community. Qibing, Josephine and Jessie are from kernel (KB5).

## Contact

gitcoin GR13：[https://gitcoin.co/grants/2445/fat-garage-newsletter-as-nft-jpeg](https://gitcoin.co/grants/2445/fat-garage-newsletter-as-nft-jpeg)

mirror：[https://mirror.xyz/dashboard/edit/I9nC9Ebp3NZvEOLh8hnPFSX4mPWQyQfZAM3G8ufSHSA]https://mirror.xyz/dashboard/edit/I9nC9Ebp3NZvEOLh8hnPFSX4mPWQyQfZAM3G8ufSHSA）

twitter：[https://twitter.com/JESSCATE93](https://twitter.com/JESSCATE93)

### References

`[1]` internet's user table: [https://blog.ceramic.network/user-centric-data-on-web3](https://blog.ceramic.network/user-centric-data-on-web3)

`[2]` soulbound: [https://vitalik.ca/general/2022/01/26/soulbound.html](https://vitalik.ca/general/2022/01/26/soulbound.html)

`[3]` streams: [https://developers.ceramic.network/docs/advanced/standards/stream-programs/#custom-streamtypes](https://developers.ceramic.network/docs/advanced/standards/stream-programs/#custom-streamtypes)

`[4]` streamID is the basic unit of data: [https://developers.ceramic.network/learn/glossary/#dids](https://developers.ceramic.network/learn/glossary/#dids)

`[5]` BretVictor The Humane Representation of thought

[https://vimeo.com/115154289](https://vimeo.com/115154289)

`[6]` why curation economy?

[https://gabygoldberg.medium.com/curators-are-the-new-creators-the-business-model-of-good-taste-](https://gabygoldberg.medium.com/curators-are-the-new-creators-the-business-model-of-good-taste-)*5852727d4b54*

[https://forefront.news/blog/feat-nir-curation-economy](https://forefront.news/blog/feat-nir-curation-economy)

`[7]` dynamic persona*:*[https://shimo.im/docs/913JVO2L62c7pG3E#anchor-Mr1e](https://shimo.im/docs/913JVO2L62c7pG3E#anchor-Mr1e)

`[8]` "nfts are adaptive entities" by takensthereom

[https://medium.com/coinmonks/nfts-are-adaptive-entities-e6d1a0796c7c](https://medium.com/coinmonks/nfts-are-adaptive-entities-e6d1a0796c7c)
