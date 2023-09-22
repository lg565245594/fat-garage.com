---
title: 为一个天使想法/项目做出「时间证明」
author: jessie-li
categories: news
tags:
  - home
  - featured
 
image: assets/2022/02/16/2.png
---

## 网上的时间证明

我总会问自己：我（想）如何在网上度过我的时间？在数字世界什么样的行为可以被认为是 "时间"？我很喜欢Andy对 "时间 "的思考，他以比特币对*时间*的新定义为例。

比特币白皮书中的一个观点是，**由时间标记的服务器组成的全球网络使我们能够摆脱朝九晚五、公共假期等权威机构的惯例，因此我们可以以相当不同的方式体验时间。**

<div align=center><img src="/assets/2022/02/16/2.png"/></div>

除了我们用来强身健体、陪伴家人和朋友、在物理世界体验新事物（真实生活）的时间外，其余的时间都在数字盒子里出现。显然，我们投入进去时间越来越长。

我们如何充分利用我们的时间？如何让我们付出的注意力，我们在数字世界做的事情得到「时间证明」？很显然并不是每个人都是数字“艺术家”能做小图片儿，引用Dror Poleg的博客[2]：但其实每个人其实早已经在网上 "工作 "了。

>这突出了大多数人在考虑NFT时忽略的一个重要问题。不可伪造的代币不是关于艺术、投机、犯罪，或者人们目前用它们做的其他事情。NFT是关于授权人们拥有、控制和货币化知识产权。正如我在《NFTs和工作的未来》中所写的那样。

>"地球上大多数人并不创造小图片或gif。"内容"不仅仅是碧昂丝的新歌或昨天的季后赛的亮点。内容是某个地方的工程师刚刚添加到开源项目中的两行代码。你的同事今天早上发给你的Slack信息也是内容。当然，你上周发给你的72个订阅者的通讯也是内容，即使你不是一个名人。 

>这两行代码、Slack信息或一封无人阅读的电子邮件可以像艺术品一样被出售吗？不能，因为它们不是art work。但它们是“work"。因此，如果它们最终是有用的，就应该有人为它们获得报酬。
以我自己为例，当我思考和写作，研究并分享时，我觉得这个时间应该被认可，就是Andy所说的参与，技能，能力是与**时间**高度相关。[我期待NFTs作为一种更多元的 "时间证明"](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247485073&idx=1&sn=07853b55645be04085ba74834b3e002b&chksm=fe62483fc915c12974201d08b15c8130b4bdaa8dcb531a1eb4abeca51b67fdfc3a92fea588ab&scene=21#wechat_redirect)，而不只是从人为的稀缺性中获取财富。像vitalik在他最近的soulbound[1]文章中所说的：


>当然，即使是金融化的NFTs也能提供重要的好处，比如资助那些本来不会被认可的艺术家和慈善机构。然而，这种方法是有局限性的，在试图超越金融化的过程中，有很多未被开发的机会。让加密货币空间中的更多物品 "有灵魂"，可以是走向另一种选择的途径，在那里，NFT可以代表更多的你是谁，而不仅仅是你能负担得起的东西。
另一件事是，每当我在网上创造数字东西时，我不仅表达自己，而且实际上与其他人、想法、项目产生**（社会）关系**。例如，

*Jessie*写了一篇关于为什么 *Doodles*是一个好的*小头像*的*mirror文章*？（提及doodles纯粹为了举例子）

## Angel-List：为一个天使想法/项目做出「时间证明」

我在上面讨论的内容与[AngelList](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247487038&idx=1&sn=4891eb35d12f331d68066fdf7fd0ae65&chksm=fe624090c915c986f3aba2d2b6a339b57489664d69e160a4ac97cdc94ce9aba79602a11bd493&scene=21#wechat_redirect) 的想法并非无关，而是关键问题所在。

1）时间证明 2）社会关系

举例来说，哪些为项目提供时间证明的开放协议-- mirror、dune analytics、gitcoin、snapshot......帮我补充一下。

### 什么算作是List？

只要你为一个天使想法/项目做出「时间证明」的行为，你就是在 "listing"

一个数据模型，至少显示 `人、项目、应用和事件` 之间的关系。

<div align=center><img src="/assets/2022/02/16/3.png"/></div>

提供时间证明的开放协议

*就像Jessie为Doodles写的一篇Mirror文章。*

<div align=center><img src="/assets/2022/02/16/4.png"/></div>

一个反映人、项目、应用和事件的datamodel

## 潜在的解决方案

*我们可以通过不同的数据模型（datamodel) 来描述 "listing "行为吗？*

### Ceramic的技术组件

我最近最感兴趣的是ceramic[3]提供的技术组件对这件事的帮助，但因为我对技术理解有限，希望和大家一起探讨。

<div align=center><img src="/assets/2022/02/16/5.png"/></div>

Ceramic 技术栈

*DID是去中心化的标识符，这是一个新兴的技术标准，可以实现可验证的、去中心化的、可互操作的数字身份。DID可以指代任何主体（例如，个人、组织、事物、数据模型、抽象实体等）。通过使用DID来管理数据存储，数据可以穿越平台和区块链，并与任何实体，包括NFTs相关联。*

*DataModels描述了与DID链接的数据，这些数据将被存储在数据存储中。DataModel定义了你的数据的形状（或模式），然后它可以被每一个与该数据模型互动的用户的数据存储所引用。开发人员可以为他们的应用程序定义DataModel，然后让用户对所有的数据记录拥有完全的主权控制。*

*DID数据存储本身就是一个DID控制的数据存储表，每个数据存储都指向相关的数据模型。这创造了一种将数据结构化并与任何Web3身份相关联的方式，所有这些都不需要后台或智能合约。由于数据生活在一个由每个用户（DID）控制的去中心化网络（Ceramic）上，来自应用A的数据并没有被锁定在应用A中。*

Ceramic为技能/证书相关的数据模型（skills&creditial datamodel) 开了一个频道[4]，李博说可以用datamodel  构想一些stream之间的联系，比如skill stream和task stream之间有联系。我也发现在另一个频道[5]中，有人认为在Ceramic Self.ID 的背景下，允许内容创作者使用一些工具来回填他们的数据流，值得一看。

<div align=center><img src="/assets/2022/02/16/6.png"/></div>
Ceramic GitHub

**这里我非常好奇的问题是**：是否可以定义和建立更多的数据模型（datamodel）来表示那些 "时间证明"？-- 我已经做了什么事情，而且它属于某种关系。

<div align=center><img src="/assets/2022/02/16/7.png"/></div>

Ceramic Githu

当我对一个项目做出这种 "时间证明（time proof）"时，就是在为Angel-List做贡献-- **我写的mirror文章**、**我在gitcoin上对项目的贡献、我为项目制作的Dune分析板**和**我在snapshot投过的票 等等。**
<div align=center><img src="/assets/2022/02/16/8.png"/></div>

## 总结

写这篇文章是我对脱离了朝九晚五，每天花在web3中的时间的思考。同时，如何理解/对待时间 也是能更好地建立[AngelList](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247487038&idx=1&sn=4891eb35d12f331d68066fdf7fd0ae65&chksm=fe624090c915c986f3aba2d2b6a339b57489664d69e160a4ac97cdc94ce9aba79602a11bd493&scene=21#wechat_redirect)的关键问题。

如果说在web2我们follow Twitter，在web3上就换成follow ENS，追踪ENS（地址），是不是从一个信息泳池跳进另一个信息泳池？

# 小伙伴们对 #AngelList 的想法

**🌱****josephine：****关于time proof 的add-on**


1.思考角度 think - how do we track time daily? refer to products like caldendars, project management tools, etc. ; & time是多维的 同一片时间

2.蕴含多个value capturing的机会 举个通俗的例子 对于演员或模特来说 他们“工作”的时间段 除了拿“报酬” 也在积累“美” “名气” 等多个维度的价值；这里每个人对价值定义不一样 但最基本的那些 比如钱、健康、美、内心的愉悦(比如好奇心满足) 这些基本是大家agree on 的价值

3.你所说的的 How do we make most of our time (online) ? - 这里就要定义 什么算make most of? 我的解答就是怎么在时间碎片里进行value creation / value capturing

**🌱****lin：****挖掘那些「不面向VC创业」的有趣项目**

web3 AngelList 可以创造一些*独特的信息流*，比如挖掘那些「不面向VC创业」的有趣项目和想法。

去更关注那些增加社会存量的efforts，而不是一直吃存量的东西（通过调整分配，某些人财富的增加必须以另一些人财富减少为代价，大家抢一个饼）。

**🌱****80****：关于Lens protocol对AngelList的启发**


<div align=center><img src="/assets/2022/02/16/9.png"/></div>
**如果你对AngelList的想法有相关input，欢迎留言或email 至 jessie@fat-garage.com*

References

[1] soulbound by vitalik

[2] nfts and the future of work by Dror Poleg

[3] User-centric data on Web3 via Ceramic

[4] [https://github.com/ceramicstudio/datamodels/discussions/18](https://github.com/ceramicstudio/datamodels/discussions/18)

[5] [https://github.com/alibama/datamodels/tree/main/packages/nifty-news](https://github.com/alibama/datamodels/tree/main/packages/nifty-news)

 

