---
layout: post
title: "技术书籍应该怎样写"
comments: true
---
好的技术书籍应该是这样的：它叙述了基本原理同时具有操作性。原理性内容应该简明扼要地叙述，既突出其重要性，而减少读者在细节的枝蔓中迷失的风险。具体的操作指导内容应该钜细靡遗，最好给出 "best practice" 作为例子。

如果认同这个观点的话，[《编写可读代码的艺术》](https://book.douban.com/subject/10797189/)并不算一本优秀的技术书籍（甚至是糟糕的）。花了两章来叙述“起好变量的名字如何重要”和“如何起一个好的变量名字”并不能减少給变量起糟糕明白的概率。同样，讨论如何給代码排版以提高代码的可读性，也不如介绍PEP8(python), go-format(go)等工具来得有效。简而言之，本书用240页的篇幅讲述了一篇博客可以讲完的内容，并且没有给你的实践提出有益的建议。

作为一个墓碑上可以写 "Here lies one whose name was writ in code."的人（其实是不可以的，毕竟我没有写出什么伟大的代码而济慈写了伟大的诗），我的建议是：

1. 一个清楚统一的代码风格 styleguide, 如果你懒得自己想，直接用 google 的；
2. 采用工具去检查你的格式，如前所述，go 和 python 都用自己的工具去检查你的代码格式，在这方面，自动化比人更可靠， 对于 python 这种动态预言，格式检查有时候还能帮你检查出一些错误；
3. 严格的 code review , 本书第三部分所叙述的原则基本上都可以通过 code review 实践。如果你有糟糕的设计，你的同事会看出来（毕竟人最擅长的不就是挑别人的错吗？）， 有更好的库函数而你不知道，你的同事也会告诉你。