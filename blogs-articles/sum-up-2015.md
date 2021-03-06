---
title: 2015年终总结及android学习路线
date: 2016-04-23 16:28:25
categories: [android,学习笔记]
tags: [学习路线,总结]
---
转眼间，一年又过去了，距离毕业也越来越近了。回想过去，感觉自己什么都还不会，顿时感到紧迫感。那么，在接下来的日子里，就要充分利用每分每秒，学习充实自己。我们搞it的就得时刻记着：活到老，学到老。<!--more-->
回想这一年，自己独自学习android，从开始安装配置开发环境，到后来的指导别人并参加实际的项目开发，经历了各种酸甜苦辣。在此，总结下学习的经历。对于android，是个开发上手入门很快的语言，但后期在其他方面需要注意和学习的事情还有很多很多。自己在android学习之路上还有伸长的路要走，但不管怎么样，还是要脚踏实地，一点点的学习，不可骄傲浮躁。下面谈谈android的学习路线(来自网络)：
### 初级

基本知识点：比如四大组件如何使用、如何创建Service、如何进行布局、简单的自定义View、动画等常见技术等。
参考书籍：《第一行代码 Android》、《疯狂Android》
### 中级

稍微深入的知识点：AIDL、Messenger、Binder、多进程、动画、滑动冲突、自定义View、消息队列等。
- AIDL：熟悉AIDL，理解其工作原理，懂transact和onTransact的区别；
- Binder：从Java层大概理解Binder的工作原理，懂Parcel对象的使用；
- 多进程：熟练掌握多进程的运行机制，懂Messenger、Socket等；
- 事件分发：弹性滑动、滑动冲突等；
- 玩转View：View的绘制原理、各种自定义View；
- 动画系列：熟悉View动画和属性动画的不同点，懂属性动画的工作原理；
- 懂性能优化、熟悉mat等工具
- 懂点常见的设计模式
学习方法
阅读进阶书籍，阅读Android源码，阅读官方文档并尝试自己写相关的技术文章，需要有一定技术深度和自我思考。在这个阶段的学习过程中，有2个点是比较困扰大家的，一个是阅读源码，另一个是自定义View以及滑动冲突。
学习view需要注意的地方：
- 搞懂view的滑动原理
- 搞懂如何实现弹性滑动
- 搞懂view的滑动冲突
- 搞懂view的measure、layout和draw
然后再学习几个已有的自定义view的例子，最后就可以搞定自定义view了，所谓万变不离其宗。
书籍推荐：《Android开发艺术探索》、《Android群英传》

### 高级

需要懂的知识：
- 了解系统核心机制：
1. 了解SystemServer的启动过程
2. 了解主线程的消息循环模型
3. 了解AMS和PMS的工作原理
4. 能够回答问题”一个应用存在多少个Window？“
5. 了解四大组件的大概工作流程
6. …
- 基本知识点的细节
1. Activity的启动模式以及异常情况下不同Activity的表现
2. Service的onBind和onReBind的关联
3. onServiceDisconnected(ComponentName className)和binderDied的区别
4. AsyncTask在不同版本上的表现细节
5. 线程池的细节和参数配置
6. …
- 熟悉设计模式，有架构意识

 书籍推荐
《Android开发艺术探索》、《Android 源码设计模式解析与实战》、《Android内核剖析》

除此之外，还可以学习一些好的开源框架的使用（如：Eventbuss），还有第三方sdk的接入使用（如:百度地图）；总之，不管怎么说，需要我们不断地学习，接受新知识，愿在新的一年里不断提高。
