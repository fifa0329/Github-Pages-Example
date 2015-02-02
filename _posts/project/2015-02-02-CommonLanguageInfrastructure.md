---
layout:     post
title:      关于Common Language Infrastructure
category: work
description: 整理一下对于CLI的理解，会用思维导图的形式呈现

---



##题外话，谈谈我所热衷的博客编写方式
我比较喜欢带图像的叙述方式，方便我表达，也方便我记忆。

不得不说，图像能够表达的信息更多，更有趣。因此，我个人是很乐意使用思维导图去整理知识的。

之前，一直是在PC上使用xmind这款应用。它确实很强大，但是，似乎在分享上面做的不是很好。我曾经尝试过先在PC上进行思维导图绘制，然后截图上传图片至博客。但是这种方式并不是很好，原因：

- 读者不能很清晰的放大缩小从而知道细节以及概括。
- 图片的大小很难把控。
- 图片的上传外链始终是一个比较麻烦的事情。

不过，最近，很高兴能够得知“百度脑图”这款产品。确实分享来说是比较方便的，我只需要粘贴一个链接上去即可。


##关于Common Language Infrastructure
通过阅读[CLI From Wikipedia](http://en.wikipedia.org/wiki/Common_Language_Infrastructure "Common_Language_Infrastructure")，确实有了一个大致的理解，结合最近.Net Opensource计划，可以有一个大概的知识的组织串联。

![Visual overview of the Common Language Infrastructure (CLI)](http://upload.wikimedia.org/wikipedia/commons/thumb/8/85/Overview_of_the_Common_Language_Infrastructure.svg/520px-Overview_of_the_Common_Language_Infrastructure.svg.png)


由图大概可以知道，CLI主要是一套标准，这套标准决定了这么一套运行机制

1. .Net兼容的语言会被**编译**为一种中间语言CIL
2. 这种CIL会被运行时**及时编译**为当前平台的机器语言
3. 程序得以通过这套01得以正确运行

但是，要实现这套Infrastructure，即基础设施，我们需要什么那？
通过阅读[ECMA-335](http://www.ecma-international.org/publications/standards/Ecma-335.htm "ECMA-335")，我有了一个大致的理解



1. 


 




