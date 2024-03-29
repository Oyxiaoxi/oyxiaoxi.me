---
title: '2021 Annual Report'
date: 2021-12-28T15:40:00Z
draft: false
lang: zh
duration: Read · 15min
description: 2021 Annual Report。
plum: true
---

[[toc]]

早晨拉开窗帘，被挡住的阳光终于像是冲开了壁障一般，肆意铺在桌面上。但是窗外被风吹得摇摇晃晃的树枝，俨然是在诉说着刚刚过去的这个夜晚是何等难熬。对它们，对我们，这个冬天似乎比以往都要寒冷，大家都盼望着春天快点到来。

习惯性地打开电脑，习惯性地泡上咖啡，突然想起已经实在是到年底了。去年的年终总结被我硬生生拖到了今年，而今年我也不想再如故蹉跎。在屋子里久了，脑子显然会不清醒，于是我决定披上外套，出门到院子里，呼吸一点新鲜空气。顺便顶着这冬日的寒风的清醒，来捋一捋今年的思绪。当然，在最后我也会整理一下今年看过的书单、动漫和玩过的游戏，算是历来年终总结的传统节目。

### 关于生活

疫情虽然不像去年那么热了，但也逃不出生活的主旋律之一。

从中美贸易战开打，“世界村”就开始坍塌了，加上半路杀出新冠疫情这个程咬金，逆全球化的趋势更是无比明显。各种变异株“你方唱罢我登场”，但看起来都是在往高传染低致命的方向演变。不过无论是德尔塔、奥密克戎的毒性多么不堪，但肉眼预计这种全球闭锁的情况，至少还要持续很长一段时间。只能说希望一切安好，希望能尽早恢复盛况。

其他方面就乏善可陈了。我似乎回到了以前教室食堂宿舍三点一线的生活中，每天逗逗慕琛、思珩她们俩，偶尔去超市屯下货，然后就回家宅起来。也许这就叫平平凡凡才是真？我自认是耐得住寂寞的人，但偶尔也会希望路边不远处的野猫能来院子里晒晒太阳，隔壁的邻居能来一起吐槽一下时事。但现代社会就是这样残酷，别说人了，就算是猫，都要忙着去挨家挨户巡查地盘，完全没有意愿停下它那忙碌的脚步，也根本懒得看你一眼。于是，我也只好收起那期盼的眼神，退回到自己温暖的巢里，然后用厚厚的茧把自己包裹起来：可能这就是性格使然，大概本性也很难改变了吧。

无比感谢老婆大人，让我有了 “**慕琛**、**思珩”** 两个小家伙。

### 关于工作

一切顺利。今年虽然负责事情的总量也没变多，但升职加薪似乎倒也没少。相对于实际的代码工作来说，由于团队缺人，今年有更多的机会面试了一些人，于是对国内的 IT 和职场的情况有了更多的理解 (技术是真的弱也更有实感了)。在线面试和传统的 onsite 确实有很大的区别，面对屏幕的时候，由于音像延迟以及摄像头一般只能拍到面部，所以很难察觉到一些细节：我愿意把这些细节叫做面试中空气的变化 (你懂的)。这种细节的缺失，对于双方来说都有一点损失：本来光靠一两次面试，候选者和公司就已经很难完成对彼此全面良好的判断了，online 面试更是雪上加霜。幸好对于程序员来说，更多时候彼此面对的都是代码而非人，所以只要笔试代码干净漂亮，总还是愿意多给一些机会。降低了实际面试的要求和期望，转而增加笔试时候的比重 (或者说选择在笔试关更加严格)，大概是最近面试时候的一个重要转变吧。

其他工作都有条不紊地进行着，日复一日的版本迭代，在空闲时间找机会重构烂掉的部分，偶尔进行一些技术评估和方向上的把控，保证项目能够长久持续做下去，不拖团队后腿，同时也能让同事们事半功倍，大家开开心心：这些就是我现在工作的重心。

国内的互联网市场真是千变万化，魄力无穷，前脚双减教培大整改，后脚连续约谈各种大厂反垄断，几个大锤下来业界形态就完全改变。我都能够非常明显地感受到，国内正处于一个极端重要的转型期。最近几年的政策方向，肯定会给后续十年甚至二十年的社会结构带来想象不到的影响。对于我这样混日子的底层白领来说，这失去了很多机会；不过另一方面，这种缺乏可能性的安定，也让生活相对平稳，焉知非福吧。

也感谢公司，给我 Work For Home 的机会！（大公司想让你把公司当成家，我想的是回自己家 ~ ）谢谢 HRD 给提供的各种便利及帮助。

### 关于学习

每年充电还是要充的。

在程序设计方面，今年主要用 GoLang 实际写了一点工具类的东西，大概也就两三千行的玩具，来改善开发流程。实际上选择更拿手的语言，比如 Swift，来做这件事情会更好一些，但是既然去年学了些 GoLang，那有明显的钉子，自然是用新锤子比较开心。

实际使用时大概有一大半的时间都花在了研究 Go Modules 和 GORM，代码 refactor 以及 feat 学习上。应该是我很不熟练，所以会有这样的困惑。虽然能直观感受到内存使用上的小心谨慎，但是实际的开发体验确实有些痛苦。除非有对性能和内存安全非常敏感的需求，否则 GoLang 的牛刀用来杀鸡，个人感觉是不太合适的。除此之外，还参与了国内 GoLang 社区的文章翻译工作，也算是对其他 Go 做了些些贡献吧。

Swift 也提出了关于 ARC 改进和 ownership 的[路线图](https://forums.swift.org/t/a-roadmap-for-improving-swift-performance-predictability-arc-improvements-and-ownership-control/54206)。第一感受就是，虽然表面上写的是 Swift，但骨子里真全是 Go。暂时现在很难对这样的改动发表什么看法，只希望 Swift 团队能在易用性和安全性之间找到平衡吧。

在编程之外，我也开始了一些 Blender 的学习。趁着黑五用优惠价买了 [polygon runway 的视频教程](https://polygonrunway.com/)，并没有打算回到游戏行业，只是希望能够在需要的时候至少能在自己力所能及的范围内，做一些 logo 或者 3D 视觉渲染图。我自己有几年前的一些 Unity 经验，对于大部分 3D 和图形渲染的概念也都有所了解，所以上手速度还不错。视频教程虽然是全英文，也没有字幕什么的，不过就算当作工作之余转换脑筋，也还是很不错的。

今年的语言学习丢了好多，以至于 French 老师，一直打电话问我，什么时候开始剩余的私教课程。（替我花的钱不值 ~）

### 关于阅读

今年人慵懒了，读的书不多，需要反省。技术类的书籍都很无聊，大多都是教程级别的就不写了；科普类、视野开拓（iDaily）的杂志订阅了一些 (牛顿科学世界和国家地理什么的)，内容也都零零散散。还是多介绍一些今年看过的人文社科的书吧。

#### **未来简史 从智人到智神**

随着算法将人类挤出就业市场，财富和权力可能会集中在拥有强大算法的极少数精英手中，造成前所未有的社会及政治不平等。 到了21世纪，我们可能看到的是一个全新而庞大的阶级：这一群人没有任何经济、政治或艺术价值，对社会的繁荣、力量和荣耀也没有任何贡献。 传统上，人生主要分为两大时期：学习期，再加上之后的工作期。但这种传统模式很快就会彻底过时，想要不被淘汰只有一条路：一辈子不断学习，不断打造全新的自己。只不过，许多人，甚至是大多数人，大概都做不到这一点。

#### **Seeing Through Statistics**

The fourth edition of this popular book by Jessica Utts develops statistical literacy and critical thinking through real-world applications, with an emphasis on ideas, not calculations. This text focuses on the key concepts that educated citizens need to know about statistics. These ideas are introduced in interesting applied and real contexts, without using an abundance of tec ...

#### **好好学习**

第一个是数据管理的维度。在这个维度上，我们所谈论的知识管理更多是具体的数据层面技巧。比如，下载的文件怎么保存？学到的知识点怎么归类？如何快速搜索文件？如何给文件贴标签？怎样整理文件夹？在哪里找到合适的书单？等等。
第二个是信息管理的维度。在这个维度上，我们关注的是怎样更好地理解、消化和应用获得的各个知识点。有很多非常有用的方法可以组织起来强化这一过程，比如：如何做读书笔记？如何用思维导图增强理解？学习中精读和泛读的区别、行动学习法、刻意练习等等。而能够有效利用这些方法，也是一个学习者进阶的标志——能够有效地把学到的知识用于解决问题。
第三个是底层规律的维度。在这个维度上，我们关心的不仅仅是具体的方法和技巧，更关心自己的认知深度：我们必须在大量具体知识积淀的基础上，形成更宏观和抽象的理解，在深层次上掌握普遍规律，从而将之前学到的繁杂的知识用一根线串起来，在具体知识之外找到新的答案，将有形化为无形，又将无形用于有形。

#### **哈佛的6堂独立思考课**

1. 应对突发情况，重点在于“先思考再行动”。
2. 什么是“批判性思考“ — 有”根据“的说话规则。
    1. 思考信息、意见和想法的对错，从中摸索出更好”答案“，即是批判性思考（Critcal thinking）。
3. 增加观点，思考”相反的意见“。

#### **人性的弱点**

我们应该关心自己的问题，而非担忧。 关注意味着要认清问题，并冷静地采取步骤处理它，忧虑只是慌乱地兜圈子。 伤害人的并非事件本身，而是他对事件的看法。

#### **我真的坐不住了：骨科医生让你上班更轻松**

年纪渐长和在家办公的双重暴击下，最近腰已经到极限了。虽然买了“钱所能及”的最好的椅子和最好的床，也在实践各种站立办公和保持运动（~），但是浑身不舒服的情况还是在持续。这本书分成颈腰膝三个部分，对常见的疼法和原因做了解释，并用图示科普了一些对应方法。

专业医生的谆谆教诲，不敢不铭刻于心啊。

### 关于游戏

去年年底天真地想着买 PS5，于是就早早把 PS4 Pro 拿去二手店卖掉了。哪里想到直到一年后的今天，PS5 都还一机难求。于是干脆彻底躺平放弃，连带着换新的索尼大法电视的计划也无限期推延了。感觉索尼从我这儿少赚了一个亿。

所以今年主要的游戏平台就只有 NS 和 PC 了，PS 再见。(排名不分先后，推荐指数仅代表个人意见）

Switch

| 标题 | 游戏状态 | 短评 | 推荐指数 |
| --- | --- | --- | --- |
| 超级马力欧3D世界+狂怒世界 | 10小时，搁置 | 3D 其实没怎么玩，狂怒世界是打通了。如果马力欧奥德赛找月亮还没过瘾的话，可以把狂怒世界看做一个 DLC，还挺有意思的。 | 4/5 |
| 塞尔达传说 御天之剑 HD | 40小时，通关 | 虽然是冷饭重置版，但是解密部分的设计在今天看来也依然出色。如果没有玩过原版的话，还是非常推荐。 | 4.5/5 |
| 火影忍者究极风暴4 | 10小时，搁置 | 各种火影级的人物对打，释放大招，PK，适合聚会人多的时候玩 | 3/5 |

PC

| 标题 | 游戏状态 | 短评 | 推荐指数 |
| --- | --- | --- | --- |
| Dota2 | 几百小时，一直玩 | 自从 LGD Ti 10 输给 Team Spirit 之后，越发觉内国内自 Wings 之后夺冠无望。 | 4.5/5 |
| CS Go | 10小时，搁置 | 偶尔和朋友打打枪 | 1/5 |
| 泰拉瑞亚 | 10小时，搁置 | Man，老羊一起玩过的游戏 | 3/5 |

写完这个，今年后面也就只剩假期了。我们明年再见！

借用人民日报的文案，结束 2021 年的 Annual Report ~

这一年，口罩 36.5 摄氏度，遇见、获得、失去、成长、释怀、缓解，我与旧事归于庆，来年依旧迎花开。
