---
layout:     post
title:      我所理解的Common Language Infrastructure
category: work
description: 整理一下对于CLI的理解，会用思维导图的形式呈现

---



##题外话，谈谈我所热衷的博客编写方式
我比较喜欢带图像的叙述方式，方便我表达，也方便我记忆。

不得不说，图像能够表达的信息更多，更有趣。因此，我个人是很乐意使用思维导图去整理知识的。

之前，一直是在PC上使用**xmind**这款应用。它确实很强大，但是，似乎在**分享**上面做的不是很好。我曾经尝试过先在PC上进行思维导图绘制，然后截图上传图片至博客。但是这种方式并不是很好，原因：

- 读者不能很清晰的放大缩小从而知道细节以及概括。
- 图片的上传外链始终是一个比较麻烦的事情。
- 思维一旦发散开来，导图将会越来越大，很难确定一个合适的截图范围。
- 不能及时更新自己的思路，呈现在导图上。


不过，最近，很高兴能够得知“百度脑图”这款产品。确实分享来说是比较方便的，我只需要粘贴一个链接上去即可。


##关于Common Language Infrastructure
我通过阅读[CLI From Wikipedia](http://en.wikipedia.org/wiki/Common_Language_Infrastructure "Common_Language_Infrastructure")，确实有了一个大致的理解，结合最近[.NET Core is Open Source](http://blogs.msdn.com/b/dotnet/archive/2014/11/12/net-core-is-open-source.aspx)，可以有一个大概的知识的组织串联。

####总的来说，CLI应该被理解为一种标准

![Visual overview of the Common Language Infrastructure (CLI)](http://upload.wikimedia.org/wikipedia/commons/thumb/8/85/Overview_of_the_Common_Language_Infrastructure.svg/520px-Overview_of_the_Common_Language_Infrastructure.svg.png)


由图大概可以知道，CLI主要是一套标准，这套标准决定了这么一套运行机制

1. .Net兼容的语言会被**编译**为一种中间语言CIL
2. 这种CIL会被运行时**及时编译**为当前平台的机器语言
3. 程序得以通过这套01得以正确运行

但是，要实现这套Infrastructure，即基础设施，我们需要什么那？
通过阅读[ECMA-335](http://www.ecma-international.org/publications/standards/Ecma-335.htm "ECMA-335")，我有了一个大致的理解，它主要是有以下几个部分组成：


1. Metadata (CLI)
2. Common Type System (CTS)
3. Virtual Execution System (VES)
4. Framework Libraries
5. The Common Language Specification (CLS)

我准备绘制了一张思维导图，用来表达我个人的理解

[思维导图之Common Language Infrastructure](http://naotu.baidu.com/viewshare.html?shareId=at75c0yiq2w4)

这样的话，

*	我的思路有更新可以及时在思维导图上实现，而不需要去更改现有的文章结构，有点像根据接口编程。
*	百度脑图中的备注支持GFM格式，这真是一个杀手级的能力，因此脑图里面相当于也放置了一些小文章。




 




