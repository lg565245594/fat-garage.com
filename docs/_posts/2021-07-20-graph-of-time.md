---
title: 时间的图形
author: jessie-li
categories: news
tags:
  - home
  - featured
 
image: assets/2021/07/20/1.png
---
你需要一直关注 takenstheorem 和他的作品，我对自己这样说。

第一个「[5分钟可视化以太坊](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247486218&idx=1&sn=8aa969c4733515f406597619903127a9&chksm=fe6245a4c915ccb21a9c7a0ededf8786105fabd98869c4d8c62a621da8d6717fdcf02e195b97&scene=21#wechat_redirect)」系列，我征求他同意后进行过编译介绍，主要是运用链上数据还原以太坊发展过程中的主要事件。-- 比如下面这幅「衔接bitcoin」，就是链上数据的可视化，展现了当时人们用比特币参与以太坊众筹时的生动情景。

<div align=center><img src="/assets/2021/07/20/2.png"/></div>

[衔接BTC (共6幅作品)——将众筹参与者（橙色）与他们未来的以太坊钱包（虚线）连接起来](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247486218&idx=1&sn=8aa969c4733515f406597619903127a9&chksm=fe6245a4c915ccb21a9c7a0ededf8786105fabd98869c4d8c62a621da8d6717fdcf02e195b97&scene=21#wechat_redirect)

最近他发布了第二个系列作品*the_coin*，主题是——bitcoin的历史。我抢到一幅*issuance*，讲的是比特币2100万枚发行与每4年减半。

<div align=center><img src="/assets/2021/07/20/3.png"/></div>
issuance

通过一个简单的数学证明作为视觉基础，展现出比特币减半的逻辑：每次减半，就对应生成一个固定半径差为 log(2) 的圆。

<div align=center><img src="/assets/2021/07/20/4.png"/></div>
### 时间图形

我一直对时间的data visualization非常感兴趣，但我不知道怎么解释这个话题，大概就是让人们能在某种视觉图形中感受到随时间变化的数据，它可以是历史的记录，或是某种抽象，人们通过这张图看到过去和未来。

<div align=center><img src="/assets/2021/07/20/5.png"/></div>

最近在读一本书叫做《时间图谱--历史年表的历史》——人们整理和抽象各种信息在做历史图谱的过程中，就是在刻画时间的模样。

有趣的是，历史年表作为展示「时间」的图形语言，从18世纪开始，以普雷斯特利《传记图表 chart of biography》为代表的时间线格式 流行了很久，以至于现在仍被广泛接受。历史叙事、信息碎片虽不再通过机械罗列事件的年鉴，但仍然无法逃脱图谱线性叙事的局限 (空间上受到挑战)。斯特恩在「绅士特里斯川·项狄的生平与见解」讽刺线形叙事时说道，“时间的线形呈现是一种复杂的、人工人为的构造。”

人们有过突破的尝试，比如布洛克构思和倡导的了基于圆锥截面状螺旋形的一种图表。

<div align=center><img src="/assets/2021/07/20/6.png"/></div>

任何一份年代纪，其起始日期都放在那不断向外延伸扩展的螺旋形的中心，布洛克就这样灵巧利落的消灭了空白区的问题。同时，布洛克为历史记忆提供了一个几何形的视觉模拟。

### 简化

尽管科技扮演了一个重要角色，却不是驱动力量。这里的首要问题，是观念层面的。

布洛克的方案很好，也传递出了编年史绘图 (或者说时间绘图) 的关键问题：并不是怎么去设计更复杂的视觉方案，而是如何去简化，怎么创造出一种视觉方案，来清晰地传递表达历史时间的*统一性、方向性和不可逆*的特质。

当然，空间感通过技术也可以加上，但我觉得这不是重点，这里缺少的或许不是技术，而是一种*context*。

### Context

我突然想到我看takenstheorem作品时的感受：他在bitcoin这个context下去呈现时间。

>每四年的减半，每个圆之间的log(2)(前面说过了，减半公式的对数差是恒定值log(2))

>通向圆心的奇点*，是2140年的宇宙吗(中心是奇点)

>消灭空白的方式，就是让你留下痕迹(每个购买成功的藏家的钱包地址会自动刻在圈的最外围)

**奇点：根据技术发展史总结出的观点，认为人类正在接近一个使得现有技术被完全抛弃或者人类文明被完全颠覆的事件点，在这个事件点以后的事件就像黑洞的事件视界一样完全无法预测。例如，意识上传技术可能使人类的意识摆脱有机体的约束，在这个奇点之后的人类文明将发展到当今完全无法理解的水准。*

比特币的时钟模样终于初现了。
<div align=center><img src="/assets/2021/07/20/7.png"/></div>

什么？为啥他画了个比特币减半，就呈现出了「时间」呢？比特币和时间有什么关系？

之前非常喜欢的一片文章「[比特币是时钟](http://mp.weixin.qq.com/s?__biz=MzIwODA3NDI5MA==&mid=2652531732&idx=1&sn=85fd04fadf3f2a36c22a2fa8389c89b0&chksm=8ce66f49bb91e65f5d42b628c597d8a550d3959f88ce6df7d19cec8eca038914060a820d7bd3&scene=21#wechat_redirect)」对此有非常精彩的论述，为什么人们对时间着迷——**时间终究是顺序**，不管是通过暴力的、人为的、中心化的还是与之相反的方式，只要让所有人或绝大多数人认同这个顺序，之后的事情才可以发生。

takenstheorem还做了其他视觉，比如这个描绘bitcoin价格历史的图，让我想到对数螺旋线 (logarithmic spirals)。

<div align=center><img src="/assets/2021/07/20/8.gif"/></div>
<div align=center><img src="/assets/2021/07/20/9.gif"/></div>

# NFT in dataverse
<div align=center><img src="/assets/2021/07/20/10.gif"/></div>
dataverse

熟悉胖车库的朋友应该知道[ownershiplabs](http://mp.weixin.qq.com/s?__biz=Mzg3MzUzMDE3Mg==&mid=2247483785&idx=1&sn=a4af7fc56b41426f9639d95ec3f843ca&chksm=cedfd7daf9a85ecc2484d29a182cbd3ed109a7574110c8b0f374c9efc7977fe134e8c28c8bc2&scene=21#wechat_redirect)最近在做一个NFT curation的工具（dataverse)，可以跨平台一键收藏各种形式的NFT作品并为其打###，让每个人有一个属于自己的数据小(kong)窝(jian)。在上线之前，我会在#主题文章（看标题）中介绍我自己curate的一些NFT作品，以及我为什么爱这些艺术家。希望工具早日和大家见面！！

<div align=center><img src="/assets/2021/07/20/11.png"/></div>

[阅读原文](https://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247486335&idx=1&sn=8951b3de6b7b5e27a94b144af72a31dd&chksm=fe6245d1c915ccc7bb88355fc6cb897958ebdea07ad4b2552e2c4eb8cf9b3a8a36fa664606c7&mpshare=1&scene=1&srcid=0721X8vbxl6tPJWWelz6pHDs&sharer_sharetime=1626878867325&sharer_shareid=edb9004eb7bae91e5a4069f84b7cfd3d&key=efaafabd99b724e4da733dd358881c8841c0845e7258cf02fe28ba155e5acdc7e5d62d02cffdcc95cc754e15fa83acc6c5c0a1091ddca05542e4af8e6219b976aa4a1aa7e2611ba788fe91c2487324497379438c511f00f0ce215771b7a394c783ae8bc7ee4ff134060816f1a4d418f6e271250eaf0256a7915a2dbc5d1c28d9&ascene=1&uin=MTMyNDAzMTc1&devicetype=iMac+MacBookPro15%2C2+OSX+OSX+10.16+build(20F71)&version=13010510&nettype=WIFI&lang=zh_CN&fontScale=100&exportkey=AdGOfUF1zgYqETzlIJXCQ9E%3D&pass_ticket=%2BDEye2%2FyXUG15PHbMsK%2BS9UTNDlTidqGe0Uq8z73cLut%2BTvVVS79szJjsaCBAHoi&wx_header=0&fontgear=2.000000##)

