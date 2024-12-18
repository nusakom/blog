---
title: rcore-2024-a-一二阶段实验总结
date: 2024-11-11 16:00:00
tags:
    - author: shengdaozm
---

紧赶慢赶，终于是在交上了最后的实验，带着许多想法，写下了这篇总结。同样作为清朝老兵，我又回来了。

## 一阶段：Rust 110 道算法题
在第一阶段，主要通过编写 110 道算法题，掌握 Rust 编程的基本和高级特性。Rust 语言强调安全性和高效性，
这在算法编程中尤其重要，是的，单个语法题目还是比较轻松的，查阅资料什么的也都可以直接解决。当真正开始算法部分的
题目的时候，才开始慢慢体会到rust的折磨——借用检查器（Borrow Checker）、所有权（Ownership）以及生命周期（Lifetime）等概念
统统在处理复杂数据结构时痛击我，Rust 的强类型系统帮助我减少了运行时错误，经常是我的逻辑天衣无缝，但还是borrowed error。
没事，慢慢折磨吧，折磨多了就会了。。。

实际上，作为清朝老兵，一阶段倒是没花多少时间，翻出以前的仓库，看看填填也就过去了，但是当时熬夜做rustlings的日子仍然是我挥之不去的记忆。酸爽！

## 二阶段：实现 rCore 简单内核

是的，一拳打爆rcore。第二阶段则是操作系统开发，说白了就是补全各种系统调用。我也慢慢感受到书上说的种种在我看起来毫不起眼的东西，真正实现起来是真的困难,(这里点名虚拟内存和文件系统，东西是真的很多)，每个ch都是一脸懵到嘎嘎乱写，然后对着panic疯狂调，期间甚至一度动摇额我的计算机世界观——计算机是真的有玄学啊。不过还好，总是能在某些神奇的地方调调代码就神奇地通过了测试，也是给我留下了不少的未解之谜。

在二阶段确实收获了不少，我现在对于一些较大的工程项目已经没有感觉了，也确实是慢慢熟悉rust了，好玩，爱玩！期待后面的考核。

祝训练营越办越好！希望能在虚拟内存和文件管理那多讲一点，确实很抽象。

最后，感觉你读完我的碎碎念，不管怎样，还是磕磕绊绊弄完了这两个阶段，也算是给上半年自己中间跑路一个交代吧，行文至此，拜拜。