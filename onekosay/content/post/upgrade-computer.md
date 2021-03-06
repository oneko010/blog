---
title: "升级电脑"
date: 2022-06-28T08:47:31+08:00
---
<style>
.content-card img{
    max-width: 60%;
}
</style>
很喜欢Apple的产品。从2010年开始使用Mac，后来专职iOS开发，Mac更是成了我离不开的工具。用过的Apple设备已经超过2位数了。以前总是很关注Apple每年的产品发布，近几年Apple变得越来越平庸，使用的还是Apple的产品，基本上谈不上当初的那种的激动了。

这次升级电脑主要是因为疫情居家，粗算起来今年各种原因居家时间差不多有1.5个月，随即就开启了远程办公模式。居家办公最大的问题是因为家里空间有限，只放了1台显示器，我的Mac Mini和家里的PC共享，家里人用电脑的时候，我就被迫只能用那台2017款air，跑工作的项目实在是慢到无法忍受。

痛定思痛之后，决定二手出掉2018 Mini和2017 air，更新成新款。于是开始研究更新的对象，这里需要决定的一个问题是M1还是x86的版本，去年接触过M1 Mac，当时因为软件兼容性问题换回了x86的Mac。为了比较两种架构，我在youtube上找到了3位作者的视频，对我帮助很大。

[![Is the M1 MacBook Air good enough for iOS developers? Apple M1 base model product review](https://i.ytimg.com/vi/zMJ9My1Qv_k/hq720.jpg)](https://youtu.be/zMJ9My1Qv_k)
这个姑娘喜欢养猫，看起来和国内的女程序员气质很相似。她也经常发布一些教程，需要的可以订阅她。

[![程序员小姐姐硬核测试M1 MacBook Air | 性能碾压i9 Macbook Pro? 值得程序员购买吗?](https://i.ytimg.com/vi/o6q8zPmfVLU/hq720.jpg)](https://youtu.be/o6q8zPmfVLU)
在美国生活的华人女程序员，全栈工程师，生活在西雅图，她的视频会夹杂一些英文，普通话也很标准。不考颜值靠实力在国外生活，会不会是美国人不懂得欣赏中国美女？分享的内容包括但不限于开发知识、生活分享、找工作建议等等，很丰富。

[![M1 Mac vs Intel Core i9 Mac | Xcode Build Test](https://i.ytimg.com/vi/dM_bP_8aPaU/hq720.jpg)](https://youtu.be/dM_bP_8aPaU)
这个老兄的视频大部分都是对比的，感觉是个专业的电脑评测或者极客，口音的关系吧，没太听清楚他讲的话，重点是视频测试结果。这集Intel i9 vs M1很震撼我。

在M1-16G到手之后，迫不及待就拿工作的项目跑了一下，编译耗时确实把那台Intel i7 16G mini远远抛在后面。对比了一下2017 air，发现其实电池的容量相比M1 air还大了4瓦时，换句话说用更低的能耗实现了性能的碾压。觉得Apple还是骨子里的自己这点从没变过。

为什么arm架构的性能可以超越x86？找到一篇资料供大家参考。
[为什么苹果M1芯片如此之快？](https://www.techug.com/post/why-is-apple-s-m1-chip-so-fast/)我总结了一下文章内容，主要包括以下几个方面：
* M1是System on a Chip，就是说在一块芯片上集成了CPU、GPU、内存、输入输出控制器和其他计算相关组件
* 使用专用的芯片处理对应的任务，而不是作为通用任务交给CPU
* 使用统一内存，其实这点和前面说的SoC相关，因为不再受总线限制，CPU/GPU可以同时访问内存避免了数据的复制

为什么传统CPU厂不按照Apple这套方案来实现？这篇文章的作者的观点是：CPU厂商需要考虑操作系统方面还有PC厂商的需要，而这些企业之间往往有各自的看法很难统一，这点上Apple的软硬件整合优势就是PC产业链的企业无法企及的。其他还有一些技术细节，感兴趣的话可以点开原文阅读。

从2008年乔布斯先生从信封里掏出初代MacBook Air已经过去14年了，Apple的市值已经超过3万亿美元，相比商业价值Apple的创新更具潜力，M系列芯片的问世一举突破了PC性能前进缓慢的状态，真正体现了科技改善生活。希望中国出现更多夯实技术能力的企业，不止步于巨大消费市场的红利当中，努力创新成为像Apple一样伟大的科技企业。


