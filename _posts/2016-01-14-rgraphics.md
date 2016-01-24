---
layout: post
title: "《R绘图系统》简介"
comments: true
---
我参与翻译的《R绘图系统》（[R Graphics 2nd](http://book.douban.com/subject/6834012/)）。即将出版了。

这本书分5个部分。第零部分是导论，概述全书内容，也向读者示R绘图系统的全貌。第一部分介绍了R自身的绘图函数：你会讶异于只靠R内置的绘图函数，就可以绘出非常复杂的图。第二部分介绍基于Grid的绘图系统，这一部分从lattice和ggplot2切入。第三部分介绍了R绘图系统的一些底层知识，比如图形格式、字体和线条等。第四部分介绍了独立于R绘图系统的一些包，这些包可以帮我们画出诸如韦恩图等特别的图。

我主要负责第二部分的翻译，所以我会详细介绍第二部分的内容。如前所述，lattice和ggplot2都是基于grid的R包。第二部分是以这两个包的介绍开始。