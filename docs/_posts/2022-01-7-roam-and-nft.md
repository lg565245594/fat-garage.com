---
title: Roam+NFT 想法的演变
author: jessie-li
categories: news
tags:
  - home
  - featured
 
image: assets/2022/01/07/7.png
---
今天看到VR更新了一条Twitter说roam是web3ify的理想产品，它的block是天然的NFT产物，又点燃了我。我对这个话题讨论已经有一年时间了，从NFT刚火起来那个时候（我写物物交换）开始，我就觉得这两者的结合是必然的趋势。至于如何结合是一个非常复杂的问题。

<div align=center><img src="/assets/2022/01/07/2.png"/></div>

<div align=center><img src="/assets/2022/01/07/3.png"/></div>
Conor：balaji两年前就在催我了[1]

这片文章是为了回顾之前我在各个阶段对这一话题的讨论，试图寻找这其中的**核心问题**，以及我认为现在**可以做的事情**。

### 第一阶段--4.24物物交换

当时的核心想法是：**NFT可以是围绕一个社群的物物交换媒介**。比如roam的核心社群`#roamcult` `#roamfm``#roamstack``#roamcn``#roam42` 都可以发行自己的NFT，并通过roam的ERC20 token $RR 实现彼此链接。

这在现在看来，有些像Loot和其衍生品的关系。围绕Loot的衍生品都发行了自己的NFT，并通过$AGLD治理代币互相链接起来。这期间没有统一的roadmap和narrative，web3就没有公司的概念，而被去中心化共建（collective intelligence）所替代。

相关阅读：[物物交换](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247485324&idx=1&sn=823a31c533d989d2db4e29f6cbb03b28&chksm=fe624922c915c034509add88d20010a45445ffceeba632e89ec877ee4a1634231b68b190e880&scene=21#wechat_redirect)

### 第二阶段——4.25；6.14 关于链上头像和部落化（onchain Avatar ；tribal）

<div align=center><img src="/assets/2022/01/07/4.png"/></div>
图3[2]

这个阶段主要受到Punks，BYAC等头像热的影响。

围绕roam的相关成员可以通过NFT获得一个社区身份。这个身份可以粗暴的生成（比如就随机生成10000个Roamans的头像，然后谁想来买就买那种），也可以根据现有贡献者们的画像去设计。这些画像的设计可以依据一些数据，比如：

- hivedotone[3]在推特上针对#RoamResearch计算的信誉清单

- RoamFM的主理人Norman在过去两年采访了Roam社群的主要节点性人物。这些受访者分布各行各业各学科，大家因为Roam这个思考工具和人类知识图谱的愿景而集结，但拥有多样的focus和特殊技能。比如Joel一直在研究discourse图谱、Robert更关注行为科学（behavior science)，和roam的链接会非常的具象。

### 第三阶段——9.23 NFT和数据
<div align=center><img src="/assets/2022/01/07/5.png"/></div>
networked NFT

这个阶段在思考数据和NFT的关系，原因是我想知道：**NFT怎么组合起来？**

我问这个问题的出发点非常具体，因为我在**写作时会引用别人的观点、别人的作品**，我想把每一个引用的credit给到对应的人，并实现一种**真实的链接**。（在这里我想说，艺术创作其和知识实并不一样，前者注重的是自我感受的表达，而不是知识的传递，reference对知识传递是太重要的事了）。

我觉得这样的reference，需要通过一种登记在区块链上的**标准化载体（就像Roam里每一个文本块block的UID一样）**去链接...

后来在9.28，我和郭老师打了一个非常长时间的电话，给他描述这个knowledge reference network 的想法并讨论在roam上的可行性。郭老师也很兴奋，像他这样的学者型创业者，他团队研究零知识证明，需要攻克的不只是技术问题，还有艰难的学术问题，因此对知识的引用思考颇多。

>在做zkPOd时面临一个巨大的问题：怀疑前面有没有人在做这个事情，是不是被别人做过/想过一遍了，没办法追溯历史；另一方面，提出牛逼idea的人也不知道自己影响了多少人

>真诚的面对自己，引用了谁的idea，站在谁的肩膀上，把原创性的想法隔离粗来，哪些是你的，哪些是借鉴原创的。哪怕一个小delta，也是很大的进步。Reference是一种知识演进的证明（Proof of knowledge evolution）。
他也给我举了一些例子：比如ACM的library是一个reference network，但不够universal。我们也同样都认为：reference将和传统论文引用不同的是，**基于以太坊区块链的引用会是一种credit system**，将来这样的credits即是另一种社会资本的货币，每一个在这个reference网络中的人将会获得相应的激励。

这样一个network不是互联网公司的数据库，而是一种credit system。

讨论到让roam上链的可行性，当时想了一个粗略的方案，就是将page URL写到metadata里：Roam的page是独立的URL，把链接写到metadata里面。

相关阅读：[数据与NFT的关系是什么](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247486625&idx=1&sn=a437f5fbcf6650864be862df3eac467c&chksm=fe62420fc915cb197bb7a97c25ef45e71f9c37f6cb22d5b1fc54500834b43d857a11ec8337b7&scene=21#wechat_redirect)

### 第四阶段——12.27 基于ENS构建wiki

也就是最近。

最近我在研究ENS[[https://mirror.xyz/0x65a0Af703047dfDd270361659d02f4f0E8547202/GXQ7Oc5m8_dg8LomABJfztYZVU7v4h0fJfpiF5qXqEk](https://mirror.xyz/0x65a0Af703047dfDd270361659d02f4f0E8547202/GXQ7Oc5m8_dg8LomABJfztYZVU7v4h0fJfpiF5qXqEk)]。大的方向延续了9.23的思路：**借助NFT去实现knowledge reference**，但是我总觉得这个媒介要收窄。我们看一个wiki的页面

<div align=center><img src="/assets/2022/01/07/6.png"/></div>

**那可不可以基于ENS做一个写wiki的引用系统?**

如果我们把**Neurology.eth**当作是一个源头wiki页面名称，在这个主题下我们收集 "章节"--任何想写的人都可以贡献一个章节。

问题是，每个贡献者在这个"Neurology.eth"下写章节时**，**如何产生一个自然的超链接？这个自然超链接不仅要链到具体的内容和人，而且是该章节的**锚/身份**，用于index**一种与主题的联系**。例如，我认为我写的这个章节属于[neuro--deeplearning]关于深度学习的部分。所以我想到了subdomain，因为@fushang之前的启发，如果ENS**域名解析器可以扩展的话**，自己编写自己的解析器，在满足接口规范的情况下，可以拓展其他逻辑。

<div align=center><img src="/assets/2022/01/07/7.png"/></div>

总结一下，与维基百科的不同之处在于，Neurology.eth每个贡献者的内容都是基于他自己的context，这不是一个**共识的结果**。因此，我们可以

1）在某一主题下获得各种有趣的知识

2）index可识别的联系 [神经--深度学习]

3）最源头的Neurology.eth可用来接收捐款

4）可以设计分配来激励每个内容贡献者


<div align=center><img src="/assets/2022/01/07/8.png"/></div>
### 我想做的事

总之，我一直想做一个 knowledge refeRence network。不管是比特币、roam（twitter）还是ENS，都有一种不止于产品的**链接感**，这和产品发展到哪个阶段没什么关系，它本身就是meme。

对我来说，特别希望的，是让每个人脑子里的**intellectual property**进行链接。我在vitalik 2011年介绍比特币的文章<Bitcoin:what is it?[4]>中看到了非常类似的描述：

>We can say that the acceptance of Bitcoin's value is a sort of virus maintaining itself in the collective society - essentially, **Bitcoin is a meme**. ——vitalik 


>just like a factory is physical capital and knowledge in one's head is intellectual capital (not to be confused with "intellectual property", the idea of a legal property right to market share on physical expressions of certain types of intellectual capital) - they are value stored not in goods, but in connections.


>一个人头脑中的知识是智力资本（不要与 "知识产权 "相混淆，它是指对某些类型的智力资本的物质表现形式的市场份额的法律产权的想法）--它们不是储存在货物中的价值，而是储存在一个人的头脑中。它们的价值不是储存在货物中，而是**储存在联系中。**
### 参考资料

[1][https://twitter.com/vgr/status/1478084641416384512](https://twitter.com/vgr/status/1478084641416384512)


[2][https://twitter.com/JESSCATE93/status/1404337115534557184](https://twitter.com/JESSCATE93/status/1404337115534557184)

[3][https://hive.one/](https://hive.one/)

[4]*Bitcoin: what is it?:*[https://web.archive.org/web/20130310102238/http://bitcoinweekly.com/articles/bitcoin-what-is-it](https://web.archive.org/web/20130310102238/http://bitcoinweekly.com/articles/bitcoin-what-is-it)

 