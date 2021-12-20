---
title: 链上数据可视化的演进，从宏观到微观
author: jessie-li
categories: news
tags:
  - home
  - featured
 
image: assets/2021/12/08/1.png
---
我之前写过很多次数据艺术家[takenstheorem](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzU5NjQxNzQ3Mw==&action=getalbum&album_id=1964995848149188609#wechat_redirect)的作品，从宏观上去呈现以太坊链上数据。以一种艺术作品的方式，把比特币的扩张、以太坊社区的繁荣、opensea等NFT市场的交错迭代，娓娓道来。

艺术归艺术，有时候执着于惊叹数据（的创造物）很美的同时，也不禁想一些更实在的问题：当我们扒开这艺术品一层层的线条，那些没有被刻意放大的细节中，似乎“隐藏”着一个和你我非常相关的世界。

<div align=center><img src="/assets/2021/12/08/2.gif"/></div>

visual from takenstheorem

换句话说，我们退到微观想想，他可视化的每一条数据，都是什么？

## Open data
<div align=center><img src="/assets/2021/12/08/3.png"/></div>
jessiehuade.notart

和李博最近的聊天让我开始思考open data。不可否认（也不可避免）的是，区块链让一切的链上行为暴露在太阳底下。

>digital universe is for people to move their lives into, which has to be on the blockchain to make it *Neutral*. 



1）从每一条链上的transaction都可以被看见：

**ethers can**

2）到每一条链上的transaction都可以被解读或标记：

**tokenview**的数据监测，用于指导交易，或预测市场。

**nansen.ai**的smart money就是根据一些链上行为，人为的给打标签（定义属性）。每个钱包变得有个性了，比如什么样的属于“巨鲸”，什么则属于“躺平”等。

<div align=center><img src="/assets/2021/12/08/4.png"/></div>

nansen.ai

3）再到针对每一个钱包地址的更细节的可视：

**Debank**几乎成了一个链上交易行为追踪器
<div align=center><img src="/assets/2021/12/08/5.png"/></div>
debank.com

## 链上注意力>链上行为

这种链上数据可视化的步伐，因为NFT的出现，从**单纯的金融行为蔓延到了创意和社交活动中**。链上注意力所触及的东西>=链上交易行为。

代表注意力的数据有

•purchase and sell on opensea or other NFT marketplace (收藏行为)

•curation among/across marketplaces（显示出偏好数据） 


这种注意力数据可视化，以**Loop**&**Dataverse**工具组合为例。Loop是以社交流（图谱）的方式，将NFTs的所有权转移以一种社交关系的方式呈现出来。你可以理解为一个NFT的公开twitter流，每一个钱包地址相当于一个twitter账户，你可以关注特定钱包地址（ENS）的NFT收藏动态。
<div align=center><img src="/assets/2021/12/08/6.png"/></div>

useloop.app

而Dataverse则是一种相对克制的形式，触及人和链上原生数据的关系（人的注意力与链上原生数据-- NFT的交互，即[curation](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247486393&idx=1&sn=eca1e490572afa7f6566a8753506c1ba&chksm=fe624517c915cc01bcf47bff5c1322dac3ff88b14d0f1daf31d5184a1404eadbf47725887d6a&scene=21#wechat_redirect)的过程）。这个过程虽不直接上链，但是构成了我们重要的注意力数据。

<div align=center><img src="/assets/2021/12/08/7.png"/></div>dataverse.art

## 链上数据可视化带来的思考

我是这样考虑这个问题的，首先，OpenData趋势一定是不可阻挡的，在这个方面一定会有越来越多的人进来做事，也就是说将来每个人在链上的行为或注意力、每个人的digital identity会变得越来越清晰。那这会引发两种（可能更多种）需求：

1) Financial privacy 涉及金融财产数据的**隐私保护**

2) Onchain behavior as CV 社交/会行为数据被**多元、精细化解读**。简单举几个例子，比如像

    •支持gitcoin的public good 🏷️

    •参与DAO governance（cast 🗳 voting）

    •参与NFT社区的身份认证与交集。像discord里面**Collab.Land, guild**这样的身份认证组件非常值得关注
<div align=center><img src="/assets/2021/12/08/8.png"/></div>
collab.Land

说到组件，这种精细化解读很可能通过组件相互组合的形式。

数据在可视化的过程中会出现一些小的组件，每个组件将承担一部分可视化的功能。比如**POAP** is for participation visualization——参与程度的可视化，也就是将这部分链上数据解读为“参与性”。同样的道理，不难想象还会有其他方面的解读，比如随便想：

```plain
* for correlation vis——看看你和不同链上群体的相关性
* for governance（voting）——看看你参与治理的程度如何
* for kindness（maybe No. times donations)——看看你有多善良；）
* for energy proof (an onchain user who tries everything）
```
<div align=center><img src="/assets/2021/12/08/9.png"/></div>
...

总之，链上数据就在那里，将会出现越来越具象化的各种组件，让我们的[digital identity](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247486535&idx=1&sn=76fdb5847dc1e902593f913c4f7150ee&chksm=fe6242e9c915cbff81797da740857e3c699f1fe128198dbcac578ee83cf5fb0889ba556cd445&scene=21#wechat_redirect)越来越具体，也让我们的注意力得到各式各样的证明。**数据将都将因为不同的目的被赋予意义和有趣的归属。**

与此同时，这些可视化组件可以被不同平台集成，比如Guild集成了POAP。

<div align=center><img src="/assets/2021/12/08/10.png"/></div>
<div align=center><img src="/assets/2021/12/08/11.png"/></div>
Guild.xyz

再比如**Galaxy**要做onchain Credentials（链上Linkedin）的标准，但具体不知道他指的「可操作」的数据是啥。
<div align=center><img src="/assets/2021/12/08/12.png"/></div>

galaxy.eco

## 写在最后——链上CV

既然「被看到一切」已成事实，不如将它转化为某种积极的思考和行动。其实想想，我们已经在无时不刻的塑造着自己的**链上CV**了，将来的竞赛不是有限游戏下的招聘找工作（fill the position)，而更像是一种**升级加buff**，不断地提升、学习，然后proof 技能、学习，这过程本身即在获取财富。

而开放数据便是这过程的证明、流动可见而开放的资源，而且属于每一个人（ownership）。就像前面说的，每个人的digital identity就可以由各种各样的组件拼成。出于不同的目的，这些组件可能定义着**同一个数据的不同属性**。所以这就不存在垄断一说。

<div align=center><img src="/assets/2021/12/08/13.png"/></div>
藤田翔的插画（日）

人们会根据某种purpose去收集数据，同样的这些数据也会围绕着这些purpose形成，这其实会是一个**很大的由大众驱动的推荐算法的迭代过程。**

比如我是一个公益组织，我们是一个保护鸟的这样一个DAO，然后我想找到这样的人，他们需要有一些链上行为属性：  

`#给gitcoin上类似的public good捐过钱` 

 `#收藏了或like了鸟🐦主题的NFT` 

`#ENS注册名称关于charity`

...

那将来也许会这样，**人们因为一个purpose去收集数据**，暂且不说是交易还是怎么着，但一开始可能这些*purposes*就非常关键。我们小伙伴最近真的很关注鸟；）

<div align=center><img src="/assets/2021/12/08/14.png"/></div>

birdDAO propos-ing by [tongyu](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247486532&idx=1&sn=604de9dc1eb0cdfda895ae7255143236&chksm=fe6242eac915cbfcb60443902b83e7e32ea336c5fdd2dea329d2aadb94117b8acd6db0db7a07&scene=21#wechat_redirect)

我们每个人确实已经处在这个无限游戏中了，至于digital identify的完善能够做什么，将是下一篇文章讨论的话题。

## reference

`[1]` [https://decrypt.co/resources/what-is-snapshot-the-decentralized-voting-system](https://decrypt.co/resources/what-is-snapshot-the-decentralized-voting-system)

`[2]` [https://debank.com/](https://debank.com/) 

`[3]` [https://www.nansen.ai/research/why-the-smart-money-matters-more-in-crypto?utm_source=twitter&utm_medium=blog](https://www.nansen.ai/research/why-the-smart-money-matters-more-in-crypto?utm_source=twitter&utm_medium=blog)

`[4]` useloop.app

`[5]` [https://galaxy.eco/](https://galaxy.eco/) 

`[6]` [https://alpha.guild.xyz/dao-masters](https://alpha.guild.xyz/dao-masters)

提到的项目仅仅为我看到并关注的，非常不全面，也欢迎大家帮我补充～ 

