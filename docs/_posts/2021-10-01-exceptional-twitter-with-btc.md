---
title: 由Twitter的BTC打赏和NFT展示所链想的
author: jessie-li
categories: news
tags:
  - home
  - featured
 
image: assets/2021/10/01/1.png
---
看到最近twitter出的新功能：BTC打赏和NFT展示，联想到一些东西。

## Tipping on twitter

看目前的打赏（tipping）功能。

### 两种类型

•  Fiat 法币打赏

•  Bitcoin 通过闪电网络⚡️打赏比特币

看上去是为了推广Twitter自己的支付cashapp（因为当你想用比特币打赏时，你必须先购买比特币）。

### 规则

```plain
* 满18周岁
* 1000位关注者以上
* 过去30天主持了3个空间。满足以上三点才可开启打赏功能
```
## Tipping somewhere else

### gitcoin打赏

比起Twitter的社交媒体平台打赏，以**个人推特账户为单位**的打赏。有一些平台专门用于打赏，比如gitcoin。

严格来说gitcoin是捐赠平台，不过给人的感受差不多。它支持更多的加密货币类型，支持一篮子采购后一块儿结算（采购10几个项目只需要付一个gas），加入二层服务以后gas费也比原来降低了不少。但是gitcoin**不是以个人为单位**的打赏，而是项目制为主（当然很强的个人可能也有）。Mask做了个桥接也很妙，Twitter上的用户直接不出推特就可以给gitcoin项目捐款。
<div align=center><img src="/assets/2021/10/01/2.png"/></div>

比如dataverse最近参与了gitcoin第11轮捐赠，最终得到了7000多位朋友的支持

**微信打赏**

在微信生态中，个人创作者主要通过微信公众号和**视频号**进行创作展示。微信现在支持**微信公众号中文章的****ti****ppi****n****g**，之前还支持法币，最近换成了腾讯搞的一种虚拟货币——微信豆，1块钱7个😅，得先充值再打赏。可预见的是之后可能会支持基于视频号作品，或个人账号的打赏（这豆子得有用是不是）。
<div align=center><img src="/assets/2021/10/01/3.png"/></div>

## NFT在Twitter上的展示

### twitter出的功能——用户可将购买的NFT设置为头像

这个功能可以直接识别用户钱包里的 NFT，在头像编辑界面直接替换。
<div align=center><img src="/assets/2021/10/01/4.png"/></div>

### Mask Network的全套方案

在Twitter上做的比较全面的就是Mask network，其实在Twitter NFT头像功能出现之前，Mask就先一步上线了这个功能，并能通过相关徽章证明当前 NFT 头像的真实性和价格等信息。
<div align=center><img src="/assets/2021/10/01/5.png"/></div>

之前在讨论去中心化社交媒体的话题时，和 Mask一起合作翻译过Bluesky（Twitter正在打造的去中心化社交媒体）的[研究报告](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247485809&idx=1&sn=5cd2dc98707f38ddfd0b5c93d6771cd5&chksm=fe6247dfc915cec9152693b2ed3db5b212a97dd85e73af874474d2259a9d81ade550d2ff59d4&scene=21#wechat_redirect)，所以很早就成为了Mask插件的使用者。

Mask是第一个让我在社交媒体（Twitter）上感受到隐私保护的dApp，不仅如此，它延伸了很多用例和玩法。例如我当时写的一篇[如何在Twitter上买特斯拉股票](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247485934&idx=1&sn=f49eecc2fd199f99f74a64d86f37128b&chksm=fe624740c915ce563c87520f0abf586db44335e965584ed68e67bfbed653dd81c9facb53064f&scene=21#wechat_redirect)，就是M ask与mirror合作，让我体验了一把在社交媒体上直接购买合成资产。

Mask侧重于信息加密和在web2.0社交网络(Twitter)上直接享受web3.0的服务，可以在不离开推特的情况下，玩转NFT。**除了前面提到的头像功能****，****插件可直接识别 Twitter ID 或者 bio 中****的****ENS 域名或 ERC20** **地址中****的** **NFT，****进而展示****。**

比如你查看Vitalik的Twitter主页，只要他的ENS绑定了Twitter（vitalik.eth），就可以直接看到他钱包里的NFT。
<div align=center><img src="/assets/2021/10/01/6.png"/></div>

OS：哇我可以看出V买了什么NFT吗？哈哈你可以看到粉丝们送了哪些NFT给V神 :-)

### MCP--从DID出发

MCP是基于分布式身份协议**Litentry**做的一个应用，目前的功能是在Twitter上有一个Tab展示NFT，为的是打通 Web 2.0 社交关系与 Web 3.0 身份的连接。也就是说，一个Twitter账号可以链接多个钱包地址，一个钱包只可以链接一个Twitter。

Litentry 是一个基于 W3C 标准提出的一个**跨系统的 DID 聚合协议**，可以给不同系统的 **DID 数据提供互操作性和流动性**。并通过分布式去中心化身份（DID）索引和基于 Substrate 框架构建的信用计算网络，为 DID 用户和 DID 应用程序提供了包括 DID 验证、信用计算及评级等身份聚合服务。

由此可以看出其特点是跨系统、和数据互操作。因为目前ENS仍然限于以太坊生态，打通其他链（波卡、BSC、Filecoin等）上的资产、交易记录、行为数据同样重要。

### nametag--域名系统

nametag是一个**基于T****w****itter的域名标准**（以浏览器插件形式），他们认为Twitter不会消失，但会包容。

>*"Our g**o**al is to becom**e th**e sta**n**dard nam**ing**se**r**v**ic**e of the* *I**n**ternet"*

为了在Twitter上展示NFT，你需要先买一个nametag的域名，然后才可以展示你拥有的NFT。也就是说，你需要先拥有一个**去中心化的twitter@Handle**，然后通过它与你的社交账号（中心化的Twitter）进行衔接。
<div align=center><img src="/assets/2021/10/01/7.png"/></div>

## 一些思考

### 关于打赏

打赏的方式变了什么吗🤔？

• 打赏颗粒依次细化...

从打赏组织、到个人、个人的作品、个人的颗粒化观点（gitcoin-Twitter-微信公众号- **?what's next**）

• 流量高地继续优势

对于创作者来说是一件好事，激励更多UGC创作。但是tipping很大程度上还是依赖于「平台的liking机制」，竞争模式依然是流量竞争（看看规则之一），流量里的头部暴利依然享受头部暴利，没什么实质性的改变。

• BTC vs token for tipping

用crypto打赏我觉得也分两种。其实BTC的narrative就是crypto“money”，而不是可编程货币，也不是可编程权益。就是他没有太多的contextual的属性目前，就挺适合Tip，毕竟tipping的文化就是这样的。

打赏作为支持或者表达喜爱的方式，其实可以更进一步。我要是喜欢一个人我一定想和他产生某些联系，成为1000 true fans，投资他。这时候token/crypto(可编程货币)会更好，比如就像gitcoin所创造的「proof of supporting」，起码带来了一种[不对称权益的可能性](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247485073&idx=1&sn=07853b55645be04085ba74834b3e002b&chksm=fe62483fc915c12974201d08b15c8130b4bdaa8dcb531a1eb4abeca51b67fdfc3a92fea588ab&scene=21#wechat_redirect)。

• 全球打赏（universal tipping）

基于以太坊这个世界计算机（universal computer），很多人开始尝试另起炉灶，不分这平台那平台了，还有些尝试去架桥。前者就是各种DID项目，给个人建造分布式身份或者基于分布式身份的分布式空间（比如我们做的dataverse）。

>以**太坊的早期叙事是“世界计算机”，可能取代比特币因为它的可编程性，更容易扩展。但事实上两者的叙事在逐渐发生变化。——jesse walden**

架桥的话，Mask是一个典型例子。前面说了，你可以通过安装插件直接享受web3的服务，打赏、红包、捐赠、投资、NFT... 一切在web2上能干的事儿来感受一下web3的版本。
<div align=center><img src="/assets/2021/10/01/8.png"/></div>
**期待新游戏**

我觉得，Twitter做这些东西都很好，但是就好像再怎么努力也是个局外人。因为你还是要讨好平台的规则，之前占据流量红利的人们依然更欢喜。我会想看到的实质性改变是**「游戏规则的根本改变」「我们自己能决定什么」**，我们如何从一个**「零和游戏到围棋游戏」**。所以，有兴趣的朋友可以多去尝试web3的工具，比如上面提到的M*ask、MCP、nametag*以及我们做的NFT curation收藏插件[dataverse](http://mp.weixin.qq.com/s?__biz=Mzg3MzUzMDE3Mg==&mid=2247483858&idx=1&sn=c46e5197c54b9dc884b396229b2e988b&chksm=cedfd781f9a85e97e92959cb9b5c3ae1d50067a7e4a8a217e043d4caf5daed9d005e8a9a0ac4&scene=21#wechat_redirect)，体验一下不依赖任何平台、所有权掌握在自己手里的感觉。
<div align=center><img src="/assets/2021/10/01/9.png"/></div>

[matti](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247486641&idx=1&sn=b28c7c1b0855d7155c4cbb192dd0d59b&chksm=fe62421fc915cb09ff6eb870bd81cbd2fff25b3d93c44ce7103b3c2ec2542617291c8bd2e19d&scene=21#wechat_redirect)说过，互联网是一个杠杆，crypto将是一个更大的杠杆，它不是用来实现「平等」的，而将是一个新的不平等的来源，但他会为**具有新型技能的一代人创造财富*和机会。**

*推荐阅读[naval如何不靠运气致富（wealth,not money)](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247483924&idx=1&sn=3f748c8437323f43af38773738df7640&chksm=fe624cbac915c5accf5b01fd3cef903bb54a22ecdc9799eb74e84fa427a8df49ee71e4becbc2&scene=21#wechat_redirect)



>*当然**，**这里说到的“财富（w**ea**lth）”是建立在另一种价值体系的基础上。起源于**20**09**年**比特币创造了数字世界的时钟🕤 ，揭开了无穷的开始。这个价值体系中，没有美联储、没有美元、没有政府、央行决定货币发行的中心化机构。基于工作量证明（proof* *of work）的机制决定了时间是唯一的锚定。--who said this*
>[每当我想到围棋......这个以扩建领土为目的的游戏，真的是很美妙的。在那里应该有战争的阶段，但它们只是为实现最终目标，让它们的领土生存。围棋游戏最成功的一点在于，它证明了为了取得胜利，必须生存，同时也必须让对手生存。——刺猬的优雅](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247486617&idx=1&sn=e85ce62d5c0495cb8ee91449140085af&chksm=fe624237c915cb218321d823cd0e611bf66a35d275953c402308b477e698613c91b8d6e65ca5&scene=21#wechat_redirect)
>*有问题的叙事之一是关于平等。互联网是一个杠杆，加密货币是一个更强大的杠杆。Crypt**o**不会解决平等问题，而是****为具有新型技能的新一代人创造财富****（进而出现新的不平等）。--m**at**t**i**fr**o**m* *zeeprime ca**p**it**a**l*
# 无他，期待新游戏而已:-）

 

