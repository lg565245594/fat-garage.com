---
title: 分布式太空专利局
author: jessie-li
categories: news
tags:
  - home
  - featured
 
image: assets/2022/02/25/1.png
---


## 前言

科技乐天派们永远会看到技术将打开的各种可能性。我们不满足于roll-ups已经被使用的场景，比如致力于实现游戏的互操作性，建立一个头号玩家的世界。并不断思考新的最佳用例：**如何发挥区块链的作用，通过可验证的计算，来追溯 idea的进化？**

我在置顶推文*和无数个tweets里面都在具象这个问题，也和本文作者兼好友[Thomas](http://mp.weixin.qq.com/s?__biz=MzU5NjQxNzQ3Mw==&mid=2247486178&idx=1&sn=af2ea543e485390eb32d6b76ea207b96&chksm=fe62444cc915cd5a28f2bb126d8292aa0e4395a9c60b00ce48389f4197679d4710f95280469e&scene=21#wechat_redirect)讨论过多次。我并不知道技术该如何排列组合让这件事成为现实，但至少这一次，我们又可以在一个具体的语境（充满潜力的validity rollup）中探讨方案，并有机会产出持续的概念验证。

[https://twitter.com/JESSCATE93/status/1389895654634262529?s=20&t=yPp67XJoKmAY4Z5QxgDueg](https://twitter.com/JESSCATE93/status/1389895654634262529?s=20&t=yPp67XJoKmAY4Z5QxgDueg)

idea进化的好处有很多：让创新的速度加快，解决实际的问题；让互联网这张网变成一个全球citation network；让Ted Nelson提出的Xanadu成为现实；知道谁与我们的思想相伴，并在这个过程中彼此“激励”...

<div align=center><img src="/assets/2022/02/25/2.png"/></div>
*Project Xanadu Mockup*

如果你关注这些，你一定会感兴趣今天的文章！

Enjoy

## 正文

	原文标题：《Decentralizing patent offices》

  作者：guiltygyoza
  
  翻译：Jessie


特别感谢Jessie Li、Perama、Allison Duettmann、Yijia Chen和Sylve Chevet提供的灵感。

TL;DR：在 validity rollup 上，我们可以建立去中心化的创新协议 (Decentralized Innovation Protoco; DIP)，用于开放可验证的创新。再加上区块链促成的新资本形成机制，我们可以将资本密集型和商业保密型的行业（如半导体行业）去中心化，并提高这些行业的创新率。

**Key words**: *Validity rollup、Open idea、Hyperstructures of libraries and protocols、Idea ledger、去中心化的创新协议/DIPs（decentralized innovation protocols）*

1- 利用零知识证明的 validity rollups 的真正潜力是什么？

2- 最终，我们会有很棒的链上视频游戏，像 Dark Forest、Conquest、Influence、Lattice 和 Curio 这样的开拓者会引领潮流。它们将从用于媒体操作的链上组件中产生，其中Briq和 bitmapbox 等在 StarkNet 生态系统中处于领先地位。借助合约的不可篡改和可组合性，链上游戏将改变我们与游戏的关系：从内容的消费者变为创造新机制的参与者，并共同扩大游戏的边界。

3- 最终，我们将拥有一种新的社交媒体，这种媒体将由**链上开放的社交图谱和知识图谱所构建**，与我们的法定身份没有任何联系，在此基础上，超结构的库和协议（hyperstructures of libraries and protocols）会应声发展。

4- 视频游戏和社交媒体都是已经存在的类别。那，我们能否想到那些现在还没有的、能发挥 validity rollup 的核心属性建立的东西？

5- 要想对这个问题进行推理，我们需要去了解区块链和 validity rollup 的核心属性。

6- 引用Virgil Griffith[1]的话：“以太坊是一个前所未有的共创舞台，通过将合作游戏理论带入新的领域，创造着我们还不能理解的强大经济载体。“对我来说，区块链是一个以去中心化方式协调大规模正和游戏（positive sum game）的引擎，可以推动我们的集体生产力达到一个新水平。

7- validity rollup 将使计算规模扩大多个数量级，并在未来几十年内使用递归证明来产生复利。这不是高性能的计算，而是**可验证的计算**。

8- 我相信在未来的几十年里，我们将借助 validity rollup 建立一种新的知识生产、验证、注册和产生复利的新型范式。这将使全世界逐渐减少对专利局的需求。

9- 专利局的问题有三方面。

(a) 它是一个需人工审查新知识的过程

(b) 它的后台与国家利益挂钩

(c) 它试图将发明人的证明和发明的使用限制捆绑在一起，而后者在耗费大量时间和金钱的专利诉讼程序中被动执行。关于解除这种捆绑，NFT是一个解决方案（虽然很多被滥用的情况），通过在链上生成“赞助证明”，人们可以无需许可地使用和传播与NFT相关的艺术品，Nouns就是很好的例子。通过传播、分叉和创建衍生品，艺术品的可识别性越高，NFT的价值就越大。

10- **这种逻辑从根本上也适用于知识。**一项知识越是被迭代、扩展，并转化为生产，它就越能实现自身的价值，因此它的价值就越大。问题在于**怎么让源头的知识创造者获取下游价值**，既要被认可为可信的、中立的发明者，又要被认可为上述知识的衍生金融价值的受益者。

11- Perama在Open idea[2]写道："开放思想 是一个提高思想向社会开放的速度的系统，它使用 append-only 的开放式知识图谱和retrospective content-address-attribution 的版税模式。”在不同领域的所有可能的想法中，我尤其感兴趣的是这样一个子集：**想法的正确性可以被数字化验证，想法的 "结构 "可以被正式地等价检验，而想法的优点可以被数字量化和比较**。这里的意思是，想法可以包罗万象，这里我们将讨论限制在具有以下属性的想法。举个例子，对于「排序问题」，「想法」即排序算法。想法可以被数字验证 (对于一系列的混乱的数字清单，算法是否都能正确排序)；想法的结构可以被等价检验 (算法和算法之间的相似性，这里是要避免有人重复上传相同的想法，进而鼓励想法的多样性)；想法的效能可以被数字量化和比较 (算法跑的多快，用多少存储空间等等)。

>*“open idea, a system to increase the rate at which ideas are made available to society, using append-only public graphs of ideas and retrospective content-address-attribution royalty model.”*
*append-only 的意思是不能修改，只能追加，和区块链本质一致；而 retrospective content-address-attribution，意思有两个：下游想法以回溯想法链的方式給上游想法的提出者地址 credit，以及当下游想法捕捉商业价值时，以 retroactive funding 的方式把部分价值依照权重分配给上游想法上各想法提出者。

12- 抽象地讲，这个想法的子集可以用数学函数表达，根据目标以特定的方式行事。例如，32b定点乘法器的数字电路实现的想法是一个由逻辑门构成的函数，对输入操作数进行乘法。火箭发动机的想法是一个可能由化学、电气和机械部件构成的功能，在一定的条件下和在一定的触发下将化学/电势转换成机械能。一个乘法器电路的性能可以从其延迟、功耗和门数来判断。火箭发动机的性能可以从其推进剂效率、最大推力和可靠性来判断。

13- 对于任何可量化的输入-输出目标，存在一个仅有插入的**想法分类账（idea ledger）**，其中：

（a）插入的门槛是idea的正确性和想法的结构独特性；

（b）插入指数来自idea的表现。

14- 利用 validity rollup，我们可以

（a）建立**验证器**，通过模拟验证idea的正确性；

（b）建立**模拟器**，量化idea的表现；

（c）建立**检查器**，检验idea之间在形式上的等价性。

15- 当我们建立这些验证器、模拟器、检查器，并建立围绕它们的协议时，我们基本上是在淡化对专利局的需求，并同时改变我们与知识生产的关系。这些协议，我将暂时称**为去中心化的创新协议/DIPs（decentralized innovation protocols）**，将邀请全球范围内的匿名参与者参与知识生产，在链上记录发明人的证明，在insert-only的分类账中记录发明，并执行这些发明的共同所有权。这些发明的链上账本是全球性的，在可量化知识的新兴领域，可以通过去中心化的专利局管理专利记录和专利审查过程。

16- 这表明，**虽然在L1上我们通过开放的DeFi协议加快了金融领域的创新速度，但在L2上我们将能够通过DIP加快许多科学和工程领域的创新速度。**这就是区块链吞噬世界的方式，对我来说，这就是元空间的含义。

17- 举一个更具体的例子，Christopher[3]是一个我用 Cairo 编写的**事件驱动的RTL模拟器**的概念证明，同时还有一个用 Cairo 合约表示逻辑电路的合约标准。该模拟器能够驱动随机刺激 （stimulus）到被测电路（或行业术语中的DUT (design under test）），在电路上产生信号并收集输出。模拟器还能够计算从输入到输出的延迟，以及电路使用的门的数量。由于模拟器跟踪每条线的信号切换，它也应能量化电路的功耗。这是将集成电路设计过程中RTL设计阶段作去中心化的第一步，可以成为集成电路设计的DIP的核心部分。请注意，我们可以利用可验证的随机性来构建随机刺激 (random stimulus) 进行功能验证。

18- 值得注意的是，理论上这个DIP的概念可以向外和向内推动。向外，DIP 可以逐步覆盖集成电路设计过程的绝大部分，从 RTL 阶段开始，最终覆盖整个完全放置和布线的芯片。对内，DIP可以针对改进 DIP 的组件，基本上是利用这个新的创新引擎来改进引擎本身的内部工作原理。例如，设想我们有 DIP-STPOW 和 DIP-SNARK。DIP-STPOW是一个用于创新卫星应用的电源管理IC元件的DIP，而 DIP-SNARK 是一个用于创新 SNARK 加速的 IC 元件的 DIP。这两个 DIP 有可能共享同一个RTL模拟器。为了防止零散/重复的工作，并递归地利用 DIP，我们可以设计一个 DIP-SIM，这是一个用于创新RTL模拟器的 DIP。就像有面向消费者的公司和面向企业的公司，我们可以有面向应用的 DIP 和面向 DIP 的 DIP。

19- 直观的想象是，每一个 DIP 都将与一个 DAO 联系在一起，以**实现激励的一致性**。这个 L2 原生的 DAO 将是高度自主的，因为成员的贡献是直接在链上衡量的，来自于成员对 DIP 的想法分类帐的贡献。将链上可衡量的贡献与链上的激励机制结合起来，似乎可以利用 DAO 的原生优势。

20- 新版《Gaming the Future: Technologies for Intelligent Voluntary Cooperation[4]》一书第五章中引用 Karl Popper 关于知识进化的见解，**知识和生物一样，是通过变异、复制和选择的过程来进化的。知识的变异是指把新的想法扔出去，知识的复制是指通过对话传播想法，而知识的选择是指通过批评否定想法**。

>*“knowledge, much as biology, evolves by a process of variation, replication, and selection. Variation of knowledge as in tossing new ideas out there, replication of knowledge as in spreading ideas through conversation, and selection of knowledge as the discrediting of ideas through criticism”*
从这个角度来看，我认为 DIP 的优点包括：

（a）通过在智能合约中执行可量化的批评指标来简化**知识的选择**。

（b) 通过在链上透明地维护想法分类账，鼓励**知识的复制**，这与许可和商业保密行业的惯例相反，也将影响全球教育系统，因为参与DIPs不需要正式的学位或签证身份，与常规的公司招聘流程相反；

（c) 通过奖励提交新的高性能想法的协议奖励，激励**知识的变化**。

21- 假设集成电路设计的 DIP 大获成功，之后的一个关键问题是，它仍然需要被制造出来才能有实际的效用，而半导体制造成本昂贵。我对这部分不太关心，因为正如我们无数次看到的那样，如ConstitutionDAO 和 NounsDAO，区块链对资本快速积累极为有利。我相信，随着 validity rollup 系统的发展，我们将创造**新的资本形成机制**，为上游的数据采购（例如，收购台积电5纳米节点库，以便为完全放置和布线的芯片创建 DIP，或收购生物数据，为长寿研究所需的人类细胞模拟创建 DIP）以及下游的制造和传播筹集资金。

22- 最后一个想法：如果证明 DIP 作为一种推动工程创新的机制是成功的，那么最好将 DIP 应用于其结果不被民族国家所垄断的领域。太空工业就是这样一个领域。

（完）

### References

`[1]` Virgil Griffith: [https://medium.com/@virgilgr/ethereum-is-game-changing-technology-literally-d67e01a01cf8](https://medium.com/@virgilgr/ethereum-is-game-changing-technology-literally-d67e01a01cf8)

`[2]` Open idea: [https://perama-v.github.io/ethereum/ideas](https://perama-v.github.io/ethereum/ideas)

`[3]` Christopher: [https://github.com/topology-gg/christopher](https://github.com/topology-gg/christopher)

`[4]` Gaming the Future: Technologies for Intelligent Voluntary Cooperation: [https://foresightinstitute.substack.com/p/improve-cooperation](https://foresightinstitute.substack.com/p/improve-cooperation)

 

