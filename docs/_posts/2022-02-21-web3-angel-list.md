---
title: 建一个web3的AngelList
author: jessie-li
categories: news
tags:
  - home
  - featured
 
image: assets/2022/01/21/3.png
---
一个想讨论的话题：在web3中建立一个AngelList的可行性，基于[每个人都是天使投资人的理想愿望](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247485715&idx=1&sn=3f22d58f255469bc3dd4762a5678e7bd&chksm=fe6247bdc915ceab7435429d8056a41e905d3eb3e8ff6771f7ba77c0af3175dfe03cc0c84c14&scene=21#wechat_redirect)。

让我们从一些基本问题开始

## 什么是AngelList？

AngelList由[Naval](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247483924&idx=1&sn=3f748c8437323f43af38773738df7640&chksm=fe624cbac915c5accf5b01fd3cef903bb54a22ecdc9799eb74e84fa427a8df49ee71e4becbc2&scene=21#wechat_redirect)于2010年创立，开始是为需要**种子资金的科技初创公司提供的自我介绍板子，**即使不需要融资的企业也会在那建一个profile档案。自2015年起，初创企业可以通过它免费向天使投资人寻求融资。

也就是说，1）为VC提供项目信息 2）为初创企业寻求早期投资（从VC）提供便利。简而言之，它是一个匹配的平台--**想法和那些想要加速它的人。**

<div align=center><img src="/assets/2022/01/21/2.png"/></div>

图1.techcrunch article "profit from a profile on AngelList" in 2016[1]

<div align=center><img src="/assets/2022/01/21/3.png"/></div>
图2.AngelList的初创公司介绍板

web3的情况（context）显然发生了变化，我们在这里需要什么样的AngelList呢？

我注意到以下几件事：

1）每天都有大量的想法涌现，其中许多是来自于原始的经典想法，或者至少是相互启发。关键是项目之间有一定的关系（这绝对不是一件坏事）。就像我喜欢的那些--Loot和DopeWar，Uniswap和Sushiswap--后者分叉了前者，但发展了不同的故事情节。

2）一个项目超越了初创企业/公司的概念，它从一开始就是一个社区。

3）那些能够加速的人的大门似乎是广泛开放的，"VC是唯一的受益者 "在web3中并不存在（具有讽刺意味的是，一些DAO项目对VC说NO THANK YOU。） 那些想真正做出贡献的人有不同的背景，编码员、设计师、营销人员、内容创造者或纯粹的投机者。但共同点是，他们都是Hodlers（尽管是流动的）。

## 为什么？

让我们回到web2的目的：1）为VC获得项目的信息 2）为创业公司寻求早期投资（从VC）提供便利，相比之下，web3的AngeList的目的有所拓展：

•1）为任何天使投资人/想贡献的人提供项目信息

•2）为项目获DAO社区寻求贡献者/支持者（不限于资金支持，而是各种贡献）提供方便，而且这些贡献是**可衡量的**

•3）形成用于分类和curate web3的''祖先图''（谁和谁的亲缘关系）*

## 如何做？

为了以上三个主要目的，我们需要一个地方来：

1）呈现早期项目/社区的信息板子

2）一个显示个人贡献的系统--链上行为和策展行为（curation则是一个新的资产类型）

```plain
* 让个人能够创建和展示自己的贡献板
* 让项目能够更容易地看和衡量贡献（如果大部分是链上数据，应该是可以的）
```
3）一个精妙的分类设计（我不知道它到底是什么样子的，但我觉得**分类**是非常重要的部分，可以实现关系追踪）。
我粗略想了一下prototype，

Dune Analytics已经做出了类似的dashboard模式，可以借鉴。不过不是展示金融数据，而是更偏向项目信息的聚合；

链上行为和curation的贡献 是可衡量的，每一部分链上信息都将作为组件可以被拼接到板子（dashboard）上。

<div align=center><img src="/assets/2022/01/21/4.png"/></div>
图3.一种信息聚合板样子[3]

# 写在最后

### **分类**的意义

达尔文在物种起源中论述了兼变传衍（decent with modifications）的概念，每一个物种呢不是单独被创造出来的，而是有着共同的祖先，经历变异，接受自然选择后留存或淘汰。那如果类比到idea，idea也不是单纯进化（evolution），而是兼变传衍。有趣的点在于，idea 是否也遵循某种谱系结构？或我们假设它遵循谱系结构，那现在重要的事情即是设计**分类的系统**、和**激励优化分类的模式，**来作为打造这个AngelList的重点。

>Evolution means change through time, decent with modifications indicates common ancestry. 
>进化强调随着时间的变化，而兼变传衍表明了共同祖先的概念
### 个人品牌出发

以上事情一定是建立在为个人更好构建Web3品牌的基础之上，之所以选择用「个人品牌」而不是「个人身份」这个词，是因为我觉得身份更偏向于匿名性，而品牌则是我们每个人渴望被熟知而面向大众的部分。这个启发来自Kyle Harrison的文章「The Unbundling of Venture Capital」[2]，Kyle在文章中论述了随着资本逐渐不稀缺，**个人品牌**在风险投资领域中的崛起，

>虽然Naked Brands主要关注名人、影响者和创造者，但我相信有一个潜在的事实因素也在影响着风险投资。信任从品牌到个人的重新分配，正影响着创始人对他们想邀请的投资者类型的看法。风险投资中的影响力已经逐渐从核心品牌（VC名）分散到利用自身品牌力量的叛逆者身上。——Kyle Harrison
并且我认为，如果不嫁接web2中那些既有指标（比如各种社交媒体followers数量、流量等等），在web3**个人品牌即是个人贡献**。

如果你对这个web3的AngelList想法感兴趣，欢迎发邮件给我：jessie@fat-garage.com

# Reference

[1] https://techcrunch.com/2016/01/22/get-backed/

[2] [https://investing1012dot0.substack.com/p/the-unbundling-of-venture-capital?r=4ljql&utm_campaign=post&utm_medium=email](https://investing1012dot0.substack.com/p/the-unbundling-of-venture-capital?r=4ljql&utm_campaign=post&utm_medium=email)

[3] [https://www.businessmodelsinc.com/angellist-reinventing-startups/](https://www.businessmodelsinc.com/angellist-reinventing-startups/)

[4] [https://venturebeat.com/2014/06/29/an-angel-investors-ultimate-guide-to-angellist-syndicates/](https://venturebeat.com/2014/06/29/an-angel-investors-ultimate-guide-to-angellist-syndicates/)

[5] [http://soleun.com/2013/03/making-sense-of-angellist-1-investors/](http://soleun.com/2013/03/making-sense-of-angellist-1-investors/)

*关于“祖先图”，其实我想说的是一个**关系的概念**，比如在web2 AngelList的例子中（下图），他可能呈现的是主要的VC机构节点，硅谷哪些主要的VC支持着哪些主要的初创企业，这之间的overlap是什么样子。那在web3中，就可能是

•who inspired by who

•who and who belongs to same category

•who's founder is also who's core member/contributor

•   ...


<div align=center><img src="/assets/2022/01/21/5.png"/></div>
图4 credit:Geir Freysson[4]


<div align=center><img src="/assets/2022/01/21/6.png"/></div>
图. 2013年有人用AngelList的API生成的硅谷的投资cluster[5]

 

