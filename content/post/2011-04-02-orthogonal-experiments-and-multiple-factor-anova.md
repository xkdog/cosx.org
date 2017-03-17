---
title: 正交试验和多因素方差分析
date: '2011-04-02T10:56:31+00:00'
author: 刘飞燕
categories:
  - 经典理论
  - 试验设计
tags:
  - 交互作用
  - 分批试验
  - 多因素方差分析
  - 正交试验
  - 试验设计
  - 部分实施
slug: orthogonal-experiments-and-multiple-factor-anova
---

英国学者R. A. Fisher等在二十世纪前期开创了近代数理统计这门大学科，开始的标志是学生氏t分布的引入。在统计的发展过程中，Fisher又提出：“在进行一批试验之前，考虑到在取得这批试验的结果后，将要进行统计分析，因此，在试验前怎样合理地安排这批试验使得试验后的结果和统计分析取得更好的效果，是值得思考的。”在这种提法的推动下，在数理统计中形成了一种一分为二和合二而一的试验设计与方差分析这两个庞大的子学科。

方差分析主要是为检验因子在试验中作用的显著性而引进的一种方法，最早是由R. A. Fisher于1920年前后对农业试验作统计分析时引进。如果能对观察值的方差进行分解且分解出来的每一部分都可作出明确的统计解释，那么这个分解就是方差分析[1]。单因素方差分析在数学方法及其应用上基本没什么问题，所以这里主要讨论多因素方差分析的一些问题。

方差分析的一个重要假定是各个试验点同方差。这个假定过于强硬，也未必符合实际。例如在农业试验中，高产田产量的方差往往较低产田产量的方差大。当然，在某些条件下可以近似地认为各试验点的方差相等。

多因素方差分析的一个重要问题是在对因素间交互作用的处理上。可以应用多元方差分析的试验数据要符合严格的要求，它们一般来源于两类试验：完全组合试验和正交试验（正交试验的两个重要特点是均衡分散和整齐可比）。

交互作用是完全组合意义上的一个概念[2]。做完全组合试验可以得到各因素间的交互作用，若全体交互作用为零则主效应完全可加。然而，按照普遍联系的法则：主效应之间通常不是完全可加的。完全组合试验时，即使验证出了交互作用为零也没有什么太大的实际意义，何况当试验点作些平移，交互作用便随着改变。也正是由于交互作用是完全组合意义上的一个概念，若在某些试验点上没有观测值，那么有些交互效应或主效应就计算不出来了。

完全搭配且每个搭配的重复次数相同的试验得到的数据的方差分析是一门数学，形式逻辑的推导正确，但这并不意味着是好的应用数学。好的应用数学就是要提高试验效益和效率，尽可能通过少数次试验找到结果好的因素及水平搭配。所以，这里谈多因素方差分析的问题是也主要是从应用的角度。

当试验涉及的因素较多时，完全组合试验代价太大，试验效率很低。这时就要求做部分实施，即选取因素水平的一些组合（完全组合的一部分）来做正交试验。应用多因素方差分析来处理正交试验的数据时，对因素间交互作用的处理比较含糊：1）有时根据经验强行假定因素间不存在交互作用，这时在理论上就直接认定认为主效应完全可加；2）有时把认为可能存在的交互作用安排进正交表；3）另外还有“三阶或三阶以上因素间交互作用可忽略不计”等假定，等等。这些对待交互作用的态度有些让人摸不着头脑，因此在应用上也就有很大的缺陷。

可能也正是由于这些不足，欧美那些偏爱多因素方差分析的学者甚至认为不应该采用部分实施，比如“正交拉丁方限于应用在交互作用可以忽略不计的试验情况”，“当缺乏关于交互作用的信息或者当交互作用为零的假定是否成立还可疑时，应该安排完全搭配”之类，这从根本上剥夺了部分实施的巨大作用，实为一种偏执于方法而忽略实际应用的倒退。

科学试验探索未知，多因素试验的变化范围广，开始时把因素的水平范围选偏在所难免，即使有多年的经验在里面也可能有因素水平选偏的情况。

举一个例子：试验中有4个因素，假定均为三水平。分别用_L_<sub>9</sub>(3<sup>4</sup>)和_K_(81)代表正交部分实施和完全搭配。完全搭配试验时，不用方向，埋头拉车，这时能够找到这81次完全搭配中的第一名。使用正交法：第一阶段，按_L_<sub>9</sub>(3<sup>4</sup>)做9次试验，找到直接看的好搭配。第二阶段，根据这9次试验结果提供的线索，可以为好搭配的进一步搜寻提供帮助，比如，根据趋势图判断因素各水平有没有选偏，如果选偏了可以在下一批的试验中调整因素的水平。这样就可能跳出原来的因素水平范围，得到的好搭配甚至超过完全搭配时的第一名。根据实践经验，这样的分批试验往往至多做三批就可以找到非常好的结果了。

当试验因素比较多时，比如13个因素，也假定均为三水平，这时选用_L_<sub>27</sub>(3<sup>13</sup>)和_K_(3<sup>13</sup>=1594323)作为部分实施和完全搭配这两种方案代表。如果做完全组合试验，除了试验次数大大增加，而且因素水平的范围更易选偏。通过分批的部分实施则可以大大提高试验效率。当试验因素越多，两种方案之间的差距越大。部分实施的巨大作用显而易见。

对于正交试验，除了在处理因素间交互作用上有缺陷，应用多因素方差分析找到好的结果往往至多是局部最优。它分析的仅仅是某一批试验的数据，通过对因素效应的分解以期找到一组好的因素水平搭配。虽然有时可能会发现得到的这组因素水平搭配已超出已经做过试验的各因素水平搭配中，但也仅止于此，然后就匆匆下结论。不仅没有继续试验以检查该水平组合是否真正是好的，而且多因素方差分析对于一开始因素水平范围是否选偏并没有考虑。试验是一项不断探索的过程，而往往不是某一批次的试验就能解决问题的。分批做部分实施是有计划地进行，每一批试验为下一批的试验的布点服务，然后不断调整因素水平的范围，以尽可能接近全局最优的因素水平组合。

其实，正交试验也好，多因素方差分析也好，最终目的还是要找到好的试验因素水平组合。那么又何必固执于求出交互作用，固执于使用多因素方差分析的方法，倒不如跳出“交互作用”的圈子，并尝试从试验全局来考虑如何找到好的因素水平组合。

张里千先生舍弃了田口式的表头设计和方差分析的方法。经过不断研究，并通过大量的深入实践和总结，去伪存真，删繁就简，逐步地提炼出一套实现最优化的正交设计的系统理论和方法，并提出了一般性指导原则和策略，即“由稀到密，分批走着瞧，有苗头处着重加密，过稀处适当加密”。在满足这个指导原则和策略下，各批试验点能充分发挥效率；在限定的试验次数内尽可能地接近全局最优解；如果试验次数可以无限，则以尽快速度可靠地收敛到全局最优解。该方法的另一大优点是简单易学、灵活方便，普通技术人员都可以学会并能在各自岗位上发挥很大作用，拥有巨大的社会潜力。[3]

如果有朋友对张里千先生的这套最优化方法感兴趣，我将在下一期的文章详细介绍该方法。另外，介绍这套实用方法的《实用选优法》一书（由张里千先生编著的最新版本）也即将由科学出版社出版，敬请关注，哈哈！

**注：1.** 本文主要是基于张里千先生对多因素方差分析的一些看法。

**2.** 张里千，数学家和应用统计学家，中国现场统计研究会的主要创始人，早年毕业于北京大学数学系，后来任中科院系统科学研究所研究员。上世纪五、六十年代在非参数统计和试验设计等若干研究领域做出了不少深刻和杰出工作，七十年代以来主要从事正交试验设计与最优化的理论方法研究、应用和推广工作。以上两项主要工作均获得了1978年的全国科学大会奖。

&nbsp;

**参考文献：**

[1] 陈希孺. 数理统计学教程[M]. 北京：中国科学技术出版社. 2009.

[2] 张里千. 交互作用和多因素最优化[J]. 数理统计与管理, 1991(03): 28-35.

[3] 张建方. 张里千传记 from 正交法和应用数学[M]. 北京：科学出版社. 2009.