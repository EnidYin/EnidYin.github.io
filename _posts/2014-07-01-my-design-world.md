---
layout: post
title: 脑洞君尹毛线的设计世界
description: "伪射鸡屎讲述老百姓自己的故事"
modified: 2014-07-01
tags: [设计脑洞]
image:
  feature: abstract-3.jpg
  credit: dargadgetz
  creditlink: http://www.dargadgetz.com/ios-7-abstract-wallpaper-pack-for-iphone-5-and-ipod-touch-retina/
comments: true
share: true
---

我，叫尹伊，英文名Enid Yin。

在豆瓣上我的个人介绍是：

做过女程序员 干过美工 涉猎过UI 努力向产品奋斗的文艺女213

金牛女 长时间处在蛇精病状态 等待我娃空降拯救

我不是一般人 因为我病起来真的不一般

肩负传递负能量的重任

...此处省略80字...

***

脑洞很大，总爱东西南北的说，抓狂起来是一堆糟毛线，平静下来又是个顺溜的毛线团儿。但毕竟是个毛线团儿，靠的近了总会有时感到扎手。

我有两个梦，一个设计梦，一个北京梦。

今天来聊聊设计梦。

最初的最初，我是一名.NET程序员，也曾幻想啪啦啪啦写下代码千万行的痛快。大学三年级时，开始发奋写程序，跟着老师搞比赛。但让我割舍不下的是... 还是我的设计梦。从看网上乱七八糟的PS教程，到遇见Scott Kelby的《Photoshop CS4 Down Dirty Tricks》。从photoshop到illustrator到coreldraw，更多的尝试让我未知事物的恐惧降低不少，只是相信我可以做到。

设计师大都有个梦想，把内心的世界通过某种介质展现给众人，希望对这个世界产生哪怕再细微的影响力。

####我的梦想很简单，我希望我的产品可以把人们从频繁的按钮click或touch中拯救出来。

通过两种方式来解救我产品用户。

####1、扁平化层级结构

似乎是种中规中矩的解决方法，但却是每个产品在做原型时的必备技能。

我对扁平化的理解是相对于层级的扁平，让用户更直接快捷的到达想要到达的位置，而非单纯的把图形拍扁再放满屏的大色块就是扁平化了。

如果从A地到C地一定要途经B地，那么一定要途经B地的理由是什么呢？这句略绕的话让我开始脑洞大开。让我们把这句话映射到实际的产品中来看，这也是很常见的一个问题，让用户先见到注册页面还是先见到登录页面。

当用户在未登录状态时访问主页，页面显示如下图：

<div style="text-align:center">
    <figure>
        <a><img height="480" width="320" src="/images/blog/2014-07-01-My-Design-World/homepage.gif"/></a>
    </figure>
</div>

顺着页面指向的箭头，点击头像，进入“完善个人信息”页面，如下图：

<div style="text-align:center">
    <figure>
        <a><img height="480" width="320" src="/images/blog/2014-07-01-My-Design-World/Improving-the-personal-information.png"/></a>
    </figure>
</div>

问题出现，如果当前的未登录用户想要进行登录操作，需要在“完善个人信息”页面点击登录按钮才能进入登录页。就是上文提到的从A地到C地，却需要途经B地问题。但其实这名用户完全没有完善个人信息的需求，却需要每次都从完善信息页面绕一圈。Bad Experience!

<div style="text-align:center">
    <figure>
        <a><img height="480" width="320" src="/images/blog/2014-07-01-My-Design-World/login.png"/></a>
    </figure>
</div>

通过页面顺序转换来达到页面层级扁平化的目的，是种常见的做法。

所以解决方案是，如果需要频繁的从A地到B地，那么不如就建立起A地和B地的联系吧。如果建铁路的钢材不够，那就把从A地到C地的铁轨拆除，铺到从A地到C地的路途中吧。

Q：为什么不在主页同时放【登录】【注册】两个入口

A：1、这款应用是一款WAP应用，版面限制。2、客户要求，直接显示出【登录】【注册】入口，会对用户产生被命令的潜意识感觉。

####咳咳咳，以上部分内容作者还表达出了另外一种感情，欢迎投稿至yinyi199205@gmail.com。

####2、这次真的来解放手指了

<div style="text-align:center">
    <figure>
        <a><img height="480" width="320" src="/images/blog/2014-07-01-My-Design-World/personal-center.png"/></a>
    </figure>
</div>

当我们在客户端修改昵称的时候，点击昵称文本框，页面左推到修改昵称页面，页面中只有一个编辑昵称的文本框，修改完成后，点击页面右上的【√】或【保存】按钮，完成昵称修改。我们一起来数一下这其中产生的点击行为：

1.          在“用户个人中心”，点击昵称文本框，进入“编辑昵称”页面
2.          在“编辑昵称”页面，点击昵称文本框，弹出输入法
3.          修改昵称动作完毕，点击页面右上的【√】或【保存】按钮保存修改

在我们的产品里，修改昵称操作只需一次点击。当昵称文本框内的内容产生修改，并保持该修改内容2秒钟不变后，程序自动将用户修改的昵称信息提交，并弹窗提示“昵称修改成功”，弹窗2s中淡出消失。

<div style="text-align:center">
    <figure>
        <a><img height="480" width="320" src="/images/blog/2014-07-01-My-Design-World/personal-center-nickname-changed.PNG"/></a>
    </figure>
</div>

所以我做的后台不够漂亮，但客户在说实用，这对我这种自学摸索成长的伪设计来说，真的超级动听。我做的前台界面还是会有逻辑略微背离用户习惯的部分，我知道一个好的产品经理，首先要热爱自己的产品，不断使用产品，带给产品功能或流程上的革新。

对扁平化结构的界面的偏爱，也着实让我的设计里走不出扁平化的图标按钮，多说一句，我还是Lumia920的首批用户。欢迎抡砖。

欢迎来微博看我的更多面
<a height="480" width="320" href="http://weibo.com/EnidYin" target="_blank">地址戳这里</a>


