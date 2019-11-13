---
layout: post
title: Google工程师是怎么处理大规模数据的？
no-post-nav: true
category: geektime
tags: [geektime]
excerpt: 毫无疑问，Google是公认的大数据鼻祖。
---

毫无疑问，Google是公认的大数据鼻祖。如今很多人提起大数据，还停留在 Google 开启的“三驾马车”时代：Google FS、MapReduce、BigTable。其实，“三驾马车”早已不是浪潮之巅。



近年来，大数据技术的发展，不论是技术迭代，还是生态圈的繁荣，都远超我们的想象。从 Spark 成为 Hadoop 生态的一部分，到 Flink 横空出世挑战 Spark 成为大数据处理领域的新星，再到如今 Google 又决心用 Apache Beam 一统天下。大数据技术的发展可谓跌宕起伏，波澜壮阔。



![](http://favorites.ren/assets/images/2019/geektime/Google01.jpg)

大数据技术生态圈



丰富的工具，繁荣的生态，也增加了开发者选择合适工具的难度。把开源框架，工具，类库，平台整合到一起，所需要的工作量以及复杂度，可想而知。技术的选择与使用，也是大数据开发者非常头疼的问题。



之前和 Google Brain 的工程师交流的时候，他提到在大数据领域，能把技术想明白，用明白的开发者太少了，一些中小型公司的技术 VP ，往往也是在“赶技术的时髦”的状态中，更别说普通的开发者。对大数据处理，比较常见的误区有下面几种：



1.低估了数据处理的重要性。

没有高质量的数据处理，人工智能只有人工没有智能。例如在语义理解上，Google 就曾犯过这样的错误，直到被一家德国的小公司超过，才认识到高质量的数据标注和处理的重要性。



2.低估了数据处理工程师在组织架构上的重要性。

大数据领域泰斗级人物Jesse Anderson曾做过一项研究，一个人工智能团队的合理组织架构，需要4/5的数据处理工程师。其实，即使是一个写前端的工程师，很多工作还是数据处理。很不幸，很多团队没有认识到这一点。



3.低估了数据处理规模变大带来的复杂度。

很多人还没有遇到过“大规模”的问题，因此容易把问题想的过于简单。Google有很多优秀的候选人，他们对常见的编程问题可以很好的解决，但只要追问数据规模变大时怎么设计系统，回答却常常不尽人意。



4.高估了上手数据处理的难度。

一方面我们需要认识到大规模的数据处理是有复杂的因素的。但另一方面，有了正确的工具和技术理念，现在上手数据处理并不困难。在Google，很多应届生入职半年后也能轻松应对上亿的数据量。



为了帮你比别人更准确深入地掌握实用的大规模数据处理技术，甚至达到硅谷一线系统架构师的水平，给你推荐一个极客时间的专栏《大规模数据处理实战》，作者就是我上文提到的 Google Brain 的资深工程师，蔡元楠。



简单提下 Google Brain（谷歌大脑）：这个团队的项目包括使用神经网络的图像增强系统、谷歌神经机器翻译的学习框架以及通过机器学习自动学习获取新技能的机器人。在Android操作系统的语音识别系统，Google+的照片搜索和YouTube中的视频推荐系统中，都用到了Google Brain的技术。



![](http://favorites.ren/assets/images/2019/geektime/Google02.jpg)


为什么是蔡元楠？



蔡元楠是 Google Brain 资深工程师，负责 AI Healthcare (人工智能的健康医疗应用) 领域，领导开发超大规模数据驱动的全新AI应用与商业模式。在 Google 期间，也曾任职于搜索广告系统，智能语音助手系统，除了技术工作外，还兼任 C++ 语言评审，AI 挑战赛评委会委员。



在《大规模数据处理设实战》中，蔡元楠想带你培养 Google 工程师精神，敢于打碎任何权威，从问题出发思考最佳方案。



具体地，他会从两方面入手：一是为你介绍硅谷最前沿技术和真实的案例，例如最新的框架层面的前后端分离理念，和批处理流处理统一的思想。二是带你剖析技术框架产生的原因和他们解决的问题，让你在遇到相似的问题的时候，做到心中有数。



为什么是这个专栏？



我仔细看了下专栏的目录，六个部分非常值得期待：



第一部分，先会用原汁原味最实际的硅谷一线大厂的案例，向你解释 MapReduce 为什么不能应对最新的技术挑战。然后我会从实际的问题出发，从头开始引导你怎样从顶层设计一个数据处理框架。



第二部分，同样是结合实战案例，讲解在数据处理框架的使用和设计中，必需的一些基础知识。这些案例紧贴应用，可能就是你的团队明天会碰到的问题。



第三、第四部分深入拆解了Apache Spark和 Apache Beam。不仅会用实际的案例教会你如何使用，还要教会你为什么它们这么设计，你会发现它们的设计其实大致和第一部分的顶层设计是一致的。这样下一次即使这个世界一无所有，你也能构建类似的框架解决一系列问题。



第五部分按 Google T6 级别设计，是带着代码的真枪实弹的架构设计。毫不夸张地说，能完整掌握第五部分内容，你就能比肩硅谷一线大规模数据处理架构师。



第六部分着重培养你的技术远见。因为是否能现在就开始准备应对10年后人类社会的技术挑战，是你拉开与别人差距的重要一站。

![](http://favorites.ren/assets/images/2019/geektime/Google03.jpg)






对于我的读者，现在订阅有什么福利？



1.上新优惠¥68 （原价¥99）。如果你是极客时间的新用户还能获得5元优惠券，券后仅需¥63

2.凭订阅截图，可加入大数据实战交流群，并领取极客时间50G学习资料包，并仅限500人。（进群方式：公众号后台回复“大数据”）



专栏目录


![](http://favorites.ren/assets/images/2019/geektime/Google04.jpg)