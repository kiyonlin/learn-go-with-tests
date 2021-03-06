# 通过测试学习 Go 语言

_或者通过 Go 语言学习测试驱动开发_

[Read original English version online](https://quii.gitbook.io/learn-go-with-tests)

* 通过编写测试探索 Go 语言
* **上手测试驱动开发**。Go 是学习测试驱动开发的好语言，因为它简单易学而且内置测试功能
* 坚信你将开始在 Go 中编写健壮的、经过良好测试的系统

## 背景

我曾经向一些开发团队介绍过 Go 语言。对于怎样使一群对 Go 好奇的人成长为高效的 Go 系统开发者，我已经尝试过很多不同的方法。

### 无效的方法

#### 读书

我们尝试过阅读[蓝皮书](https://www.amazon.co.uk/Programming-Language-Addison-Wesley-Professional-Computing/dp/0134190440)（The Go Programming Language），每周在练习的同时讨论下一章的内容。

我喜欢这本书，但它需要高度的投入。这本书非常详细地解释了每个概念，这显然是极好的，但也意味着进步是缓慢而稳定的 —— 这不适用于每个人。

我发现虽然有一小部分人会阅读第 x 章并做练习，但很多人不会这么做。

#### 解决一些问题

[Kata](https://en.wikipedia.org/wiki/Kata_%28programming%29)[^注1] 很有趣，但是他们学习语言的范围通常是有限的；你不太可能用 Go 例程来解决 kata 问题。

另一个问题是当你们有不同程度的热情时，有些人只是比其他人学得更多，当他们演示他们所做的事情时，最终导致其他人困惑于他们不熟悉的特性。

这最终会使学习变得非常 _凌乱无序_。

### 有效的方法

到目前为止，最有效的方法是通过 [go by example](https://gobyexample.com/) 来慢慢地介绍语言的基本，通过例子探索学习，并组成小组讨论它们。这是一种比「为完成作业阅读第 x 章」更具互动性的方法。

随着时间的推移，团队获得了坚实的语法基础，这样我们就可以开始构建系统了。

这对我来说就像是在学习吉他时练习音阶。

不管你认为自己多有艺术感，你不可能在不了解基本原理和练习技巧的情况下写出好音乐。

### 对我有效的方法

当学习一种新的编程语言时，我通常开始会纠结在 REPL（Read-Eval-Print-Loop）中，但最终我需要更多的结构。

我喜欢探究概念，然后通过测试来巩固概念。测试验证我编写的代码是正确的，并记录我已经学到的特性。

以我的团队学习经历和我自己的个人风格，我将尝试创造一些东西，希望证明对其他团队也有用。通过编写小测试来学习基础知识，这样你就可以掌握现有的软件设计技巧并交付一些优秀的系统。

## 适用人群

* 有兴趣学习 Go 语言
* 已经对 Go 有一些了解，但是想要探索更多测试的内容

## 准备工作

* 一台电脑
* [安装 Go](https://golang.org/)
* 一个文本编辑器
* 一些编程的经历，理解 `if`、变量、函数等的概念
* 舒适的使用终端

## 反馈

* 提交 issues 或者 [tweet me @quii](https://twitter.com/quii)

[MIT license](LICENSE.md)

---

作者：[Chris James](https://dev.to/quii)
译者：[Donng](https://github.com/Donng)
校对：[flw](https://github.com/flw-cn)、[pityonline](https://github.com/pityonline)

本文由 [GCTT](https://github.com/studygolang/GCTT) 原创编译，[Go 中文网](https://studygolang.com/) 荣誉推出

[^注1]: 针对某一种特定技术或技能进行重复性的练习，从而将其熟练掌握。套路（Kata）这个概念借鉴于武术，指的是可以独自或多人共同练习的一系列动作、招式。
