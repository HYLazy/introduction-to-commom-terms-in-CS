# 计科学习常见术语简介

* 尽量做到周更。
* 仅以首字母排序。
* 如果对于术语的常见称呼为中文，则按中文首字母排序。否则为英文。
* 部分词条的评价部分具有主观性，请谨慎看待。
* 对于计科新生有帮助的词条会打上新手标签。

### 前言

* 就像zt学长说的，平时可以多关注一些文章，哪怕不仔细看，就在脑子里存个档，那么以后需要用到这些知识的时候就可以更快的想起来。
* 个人认为，计算机学习中，如果倾向于软件开发，那么就更要开阔视野，了解各种各样的新技术、新想法，提升自己的软件开发水平。

## A

### API

* 简介：

  > 应用程序接口（英语：Application Programming Interface），缩写为API，是一种计算接口，它定义多个软件中介之间的交互，以及可以进行的调用（call）或请求（request）的种类，如何进行调用或发出请求，应使用的数据格式，应遵循的惯例等。它还可以提供扩展机制，以便用户可以通过各种方式对现有功能进行不同程度的扩展。一个API可以是完全定制的，针对某个组件的，也可以是基于行业标准设计的以确保互操作性。通过信息隐藏，API实现了模块化编程，从而允许用户实现独立地使用接口。

### auto类型推导

* 标签：C++

* 简介：

  > auto可以让编译器在编译器就推导出变量的类型,利用auto可以通过=右边的类型推导出变量的类型。

* 相关文章：

  * [我常用的 10 个 C++ 新特性](https://mp.weixin.qq.com/s?__biz=MzAxNDI5NzEzNg==&mid=2651163001&idx=1&sn=785da206529f257cc337e75f1becc56f&chksm=80645826b713d130feb765c40ca173b1fc9a8ba7a62ebf9f66bb20c40ee4b75b0c30048f5737&mpshare=1&scene=23&srcid=0702bDK9I3bVmhx3DgJRwJSx&sharer_sharetime=1625215100229&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

## B

### 补码

* 标签：计算机基础

* 简介：

  > 补码的表示方法是:正数的补码就是其本身.负数的补码是在其原码的基础上, 符号位不变, 其余各位取反, 最后+1。(即在反码的基础上+1)

* 相关文章：

  * [计算机为什么要用补码？](https://mp.weixin.qq.com/s?__biz=MzU4Mzc3MzM3NA==&mid=2247485027&idx=1&sn=80e92e7adeb7287ff5739de60fe47809&chksm=fda2bbb2cad532a4dc57c337f90b2a1abc3a51b8d54e891693540afcbaab0e4c36d330ff2a73&mpshare=1&scene=23&srcid=0704daq05x7PRU5jWabBhWIX&sharer_sharetime=1625330272160&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

    > 计算机为什么使用补码？**采用补码可以简化计算机硬件电路设计的复杂度**。.
    
  * [原码, 反码, 补码 详解](https://www.cnblogs.com/zhangziqiu/archive/2011/03/30/ComputerCode.html)

## C

### C语言

* 标签：编程语言，**新手**

* 简介：

  > C语言是一门面向过程的编译型语言，它的运行速度极快，仅次于汇编语言。C语言是计算机产业的核心语言，操作系统、硬件驱动、关键组件、数据库等都离不开C语言。

### C++语言

* 标签：编程语言，**新手**

* 简介：

  > C++是C语言的继承，它既可以进行[C语言](https://baike.baidu.com/item/C语言/105958)的过程化[程序设计](https://baike.baidu.com/item/程序设计/223952)，又可以进行以抽象数据类型为特点的基于对象的程序设计，还可以进行以继承和多态为特点的面向对象的程序设计。C++擅长面向对象程序设计的同时，还可以进行基于过程的程序设计，因而C++就适应的问题规模而论，大小由之。 
  >
  > C++不仅拥有计算机高效运行的实用性特征，同时还致力于提高大规模程序的编程质量与程序设计语言的问题描述能力。 
  
* 相关资料：

  * [重磅干货 ：五万字长文总结 C/C++ 知识（上）](https://mp.weixin.qq.com/s?__biz=MzAxNDI5NzEzNg==&mid=2651163211&idx=1&sn=f445496b3f9260fb14dd94d8576a10d2&chksm=80645b14b713d202366ae0a72124b9b805d23a5ab36e90fde9eae1730e8e4011d23e5142a6f6&mpshare=1&scene=23&srcid=0717693yKdAO2jP1PonSLIj1&sharer_sharetime=1626511878280&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [C++编译期多态与运行期多态](https://mp.weixin.qq.com/s?__biz=MjM5ODg5MDIzOQ==&mid=2650490084&idx=1&sn=2bfbb688a134fe7a5e79b6b830ff9799&chksm=becc3b7489bbb2625ad1577bd3f4c33c25ebe9f4f253e4b5854e258beaada06afae37d1e091a&mpshare=1&scene=23&srcid=0722OqMcSgQnbSPZgl5DBWXM&sharer_sharetime=1626929587812&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [C++ 并发编程（C++11 到 C++17 ）](https://mp.weixin.qq.com/s?__biz=MzAxNDI5NzEzNg==&mid=2651163335&idx=1&sn=2801dfc5589977658b945bacb5514b57&chksm=80645b98b713d28e7aa3f875df53053acbea1c496d3075c1ee75c08591d9bd7665c040ade14b&mpshare=1&scene=23&srcid=0721V73Thl2GDYcnrAD4MHEm&sharer_sharetime=1626860272396&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [C++内存管理](https://mp.weixin.qq.com/s?__biz=MzI3ODQ3OTczMw==&mid=2247490667&idx=1&sn=5f696d798cfd06d1711b31f2e623462e&chksm=eb570a71dc2083673d5a2aa77fda973aa6e13bf02cbe558af65ebd6b78d6522bd95cdd9b43e3&mpshare=1&scene=23&srcid=07218LP6VMRPH719SaNtK1Gv&sharer_sharetime=1626837502826&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [5 大最常用 C++ 经典算法](https://mp.weixin.qq.com/s?__biz=MzA4MjI3NzQ1Nw==&mid=2247494299&idx=1&sn=33ec4ad79b6ff8506c248f15312b20b3&chksm=9f8a8fa5a8fd06b3a8d0ed0a0299be094892941a44d8a92cd6c2e3749266db14711537fa939b&mpshare=1&scene=23&srcid=0721Xg8w7J5e5HRR9ozvNNzj&sharer_sharetime=1626828445016&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [谈谈C++新标准带来的属性（Attribute） ](https://mp.weixin.qq.com/s?__biz=MzIzOTU0NTQ0MA==&mid=2247504289&idx=1&sn=5d3a4c3cef4a44488a40540510e7c7b5&chksm=e92aecaede5d65b84060ef062f0bef56081458464b36eb2782d213683474f488b44217af7c45&mpshare=1&scene=23&srcid=0721lrb1vijm546RLaAY5rAw&sharer_sharetime=1626828380135&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [每个工程师都应该了解的一些 C++ 特性 ](https://mp.weixin.qq.com/s?__biz=MzA4MjI3NzQ1Nw==&mid=2247494281&idx=1&sn=eba073e3283333554de9d9dc40fd1d7f&chksm=9f8a8fb7a8fd06a11b876015d0197371bc00ace21814fef99e2f7ba1c15d002bc19e0d5dfca7&mpshare=1&scene=23&srcid=0719NF08D5ojfWOibB1B5X78&sharer_sharetime=1626710303025&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [重磅干货：五万字长文总结 C/C++ 知识（下） ](https://mp.weixin.qq.com/s?__biz=MzAxNDI5NzEzNg==&mid=2651163271&idx=1&sn=466313fdd12db9bcfc5473bb99d4203f&chksm=80645bd8b713d2ce0535684be16dfa4c8914d5d60c3ca5e7843c13a093c90acab3b90c781be5&mpshare=1&scene=23&srcid=07192SMfNQWbp9JPUVPp5hCM&sharer_sharetime=1626624812953&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [C++ 虚函数表剖析 ](https://mp.weixin.qq.com/s?__biz=MjM5ODg5MDIzOQ==&mid=2650490122&idx=1&sn=87dc5abcacc1c76c75a6a955beead040&chksm=becc3a9a89bbb38c55a0522d498ad04514477df7b4b9ae4afdfd4a30b7161a1d0e348ed3506a&mpshare=1&scene=23&srcid=0726tJgdzw9x0oCjC9KHXneE&sharer_sharetime=1627304599546&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [C++ 并行编程中的“锁”难题 ](https://mp.weixin.qq.com/s?__biz=MzAxNDI5NzEzNg==&mid=2651163356&idx=1&sn=c40d8e2dc810dc4b433e1f4afd00f020&chksm=80645b83b713d2952d32145bd18789c81e4feb241154488ee4816347c48bc77cd1cf05c80ecc&mpshare=1&scene=23&srcid=0726mrzvgzdxuswdxOy4HYEU&sharer_sharetime=1627275530939&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

### CI/CD 管道

* 标签：软件开发

* 简介：

  > 持续集成（continuous integration）/持续部署（continuous deployment）（CI/CD）管道是每个 DevOps 计划的基础。CI/CD 管道打破了传统的开发孤岛，使开发和运营团队能够在整个软件开发生命周期中进行协作。
  >
  > 更好的是，转向 DevOps 和 CI/CD 管道可以帮助你的组织以更高的速度更安全地 交付软件。

* 相关文章：

  * [CI/CD 管道是什么？](https://mp.weixin.qq.com/s?__biz=MzI1NDQwNDYyMg==&mid=2247489555&idx=1&sn=087620951001f972b0402a4e562b1bae&chksm=e9c4e972deb3606494a91fb811a63c192e0700532f6a295a270112fcc380d0ac7c66b03a1a0b&mpshare=1&scene=23&srcid=0705BsBZE27LiMYOL0oTL4Py&sharer_sharetime=1625482988380&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

## D

### Docker

* 简介：

  > Docker是一个开源的引擎，可以轻松的为任何应用创建一个轻量级的、可移植的、自给自足的容器。开发者在笔记本上编译测试通过的容器可以批量地在生产环境中部署，包括VMs（虚拟机）、 [bare metal](http://www.whatis.com.cn/word_5275.htm)、OpenStack 集群和其他的基础应用平台。 
  >
  > #### Docker通常用于如下场景：
  >
  > - web应用的自动化打包和发布；
  > - 自动化测试和持续集成、发布；
  > - 在服务型环境中部署和调整数据库或其他的后台应用；
  > - 从头编译或者扩展现有的OpenShift或Cloud Foundry平台来搭建自己的PaaS环境。

* 相关资料：

  * [Docker 极简入门指南](https://mp.weixin.qq.com/s?__biz=Mzg2MjEwMjI1Mg==&mid=2247519624&idx=3&sn=50437d74f7189b8a2c1aec3ec98ef0cd&chksm=ce0e3a0bf979b31d736fe8de9145f6f0a0c002834c0adf0b28d59fbb52ed56f0a9b2a8f08bb0&mpshare=1&scene=23&srcid=0714A4pBGP8wjWCYna7MKIBa&sharer_sharetime=1626259583414&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [docker专栏](https://mp.weixin.qq.com/mp/appmsgalbum?action=getalbum&__biz=MzAxMjY5NDU2Ng==&scene=23&album_id=1958971875900850179&count=3#wechat_redirect)

### DevOps

* 标签：软件开发

* 简介：

  > DevOps追求更短的迭代周期、更高频的发布。但发布的次数越多，引入故障的可能性就越大。更多的故障将会降低服务的可用性，进而影响到客户体验。所以，为了保证服务质量，守好发布这个最后一道关，阿里逐步发展出了适应DevOps要求的发布策略。

* 相关资料：
  * [DevOps发布策略简介](https://mp.weixin.qq.com/s?__biz=MzIzOTU0NTQ0MA==&mid=2247504053&idx=1&sn=d81ed8301ad290c7f04cbf0a7f6be1d9&chksm=e92aedbade5d64ac0f979275848c4664609e9be8e0254b04129dec214b59bb0c5e26ea549761&mpshare=1&scene=23&srcid=0707NMIx0bb4zqCBdzPpBTsP&sharer_sharetime=1625650520997&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

### Dubbo

* 标签：开发，框架，JAVA

* 简介：

  > Dubbo(读音[ˈdʌbəʊ])是阿里巴巴公司开源的一个高性能优秀的服务框架，使得应用可通过高性能的 RPC 实现服务的输出和输入功能，可以和 Spring框架无缝集成。
  > Dubbo是一款高性能、轻量级的开源Java RPC框架，它提供了三大核心能力：面向接口的远程方法调用，智能容错和负载均衡，以及服务自动注册和发现。

* 相关资料：
  * [有赞服务注册与发现架构演进](https://mp.weixin.qq.com/s?__biz=MzAxOTY5MDMxNA==&mid=2455763062&idx=1&sn=8c798bb34be00fa0a0c777c91d75188c&chksm=8c687e53bb1ff7455b094441d866bf2f2f7f36b2858ece0b9dc02b68a7360ee58bf1300cb05f&mpshare=1&scene=23&srcid=0726Whrsh3WZj5zFMDgKE4FW&sharer_sharetime=1627299000896&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

## F

### 分布式

* 简介：

  > 分布式系统是若干独立计算机的集合，这计算机对用户来说就像单个相关系统。

* 相关资料：
  * [到底什么是分布式系统？](https://zhuanlan.zhihu.com/p/62623474)
  * [Azkaban、Xxl-Job与Airflow对比分析 ](https://mp.weixin.qq.com/s?__biz=MzAxMjY5NDU2Ng==&mid=2651862493&idx=1&sn=981d3741b5ecb5a97e5b2d59448f4402&chksm=80497094b73ef9823f0f6a1eafcc468cf0c01354c5d81ca6e0e812555611b06fd612ce1b2700&mpshare=1&scene=23&srcid=072667X4KcD7auA00fy6IPyW&sharer_sharetime=1627304630832&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

## G

### Github

* 标签：实用网站
* 简介：
* 主观评价：
  * 全球最大的程序员网站，懂得都懂。无论是自我提升，还是分享技术，~~或者是抄作业，~~都能给你带来极大的帮助。

### 工厂模式(Factory)

* 标签：JAVA

* 简介：

  > 系统中总是需要创建对象的，一般使用new()来创建对象。创建对象可以是简单的new()，也可以有复杂的加工逻辑，如果在主程序中创建对象，那么就是将主干逻辑和创建对象的非主干逻辑耦合在了一起，工厂模式要做的就是将非核心的对象创建逻辑与主干逻辑解耦，通过调用工厂的创建方法直接获取到一个对象。

* 相关资料：
  * [重温设计模式之 Factory](https://mp.weixin.qq.com/s?__biz=MzIzOTU0NTQ0MA==&mid=2247504042&idx=1&sn=d6ce7c7ca42807ae9661523e750b9253&chksm=e92aeda5de5d64b349c18cebfad1f25974fe2836cadabea062063a6a4d1604e952a9725e1586&mpshare=1&scene=23&srcid=0707SG2t06QUMcIVHuDNPydj&sharer_sharetime=1625658013529&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

## H

## I

## J

### JAVA语言

* 标签：编程语言，**新手**

* 简介：

  > - Java 是一项用于开发应用程序的技术，可以让 Web 变得更有意思和更实用。 Java 与 javascript 并不相同，后者是一种用于创建 Web 页的简单技术，只能在浏览器中运行。
  > - 使用 Java 可以玩游戏、上载照片、联机聊天以及参与虚拟体验，并能够使用联机培训、网上银行和互动地图等服务。如果没有安装 Java，则许多应用程序和网站都无法工作。

* 相关文章：

  * [什么是 Java？](https://www.java.com/zh-CN/about/whatis_java.jsp)
  * [如何设计一个 Feed 流系统 ](https://mp.weixin.qq.com/s?__biz=MzAxMjY5NDU2Ng==&mid=2651862415&idx=1&sn=fef76b99f7be17b40dc96218cabd4b70&chksm=804970c6b73ef9d082bf2298b9c369bdea29c4219888ee087a34b1746b1ef7dcf06383b19f2c&mpshare=1&scene=23&srcid=0722ierT8yEYzOTFDD0gV2dS&sharer_sharetime=1626929569239&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [Java必会的工具库，让你的代码量减少90%](https://mp.weixin.qq.com/s?__biz=MzAxMjY5NDU2Ng==&mid=2651862390&idx=1&sn=ce1d103c27ebc360c313474ffeb3afc8&chksm=8049703fb73ef929f0ec843f940c7cd7557d634fd83526397ed7bc5b84e9e124aad26827e76b&mpshare=1&scene=23&srcid=0719kW9tPNTQMWpdv7CadqdW&sharer_sharetime=1626624782545&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

### JavaScript

* 标签：编程语言，前端

* 简介

  > 要了解JavaScript，我们首先要回顾一下JavaScript的诞生。
  >
  > 在上个世纪的1995年，当时的网景公司正凭借其Navigator浏览器成为Web时代开启时最著名的第一代互联网公司。
  >
  > 由于网景公司希望能在静态HTML页面上添加一些动态效果，于是叫Brendan Eich这哥们在两周之内设计出了JavaScript语言。你没看错，这哥们只用了10天时间。
  >
  > 为什么起名叫JavaScript？原因是当时Java语言非常红火，所以网景公司希望借Java的名气来推广，但事实上JavaScript除了语法上有点像Java，其他部分基本上没啥关系。
  >
  > ### ECMAScript
  >
  > 因为网景开发了JavaScript，一年后微软又模仿JavaScript开发了JScript，为了让JavaScript成为全球标准，几个公司联合ECMA（European Computer Manufacturers Association）组织定制了JavaScript语言的标准，被称为ECMAScript标准。
  >
  > 所以简单说来就是，ECMAScript是一种语言标准，而JavaScript是网景公司对ECMAScript标准的一种实现。
  >
  > 那为什么不直接把JavaScript定为标准呢？因为JavaScript是网景的注册商标。
  >
  > 不过大多数时候，我们还是用JavaScript这个词。如果你遇到ECMAScript这个词，简单把它替换为JavaScript就行了。
  >
  > ### JavaScript版本
  >
  > JavaScript语言是在10天时间内设计出来的，虽然语言的设计者水平非常NB，但谁也架不住“时间紧，任务重”，所以，JavaScript有很多设计缺陷，我们后面会慢慢讲到。
  >
  > 此外，由于JavaScript的标准——ECMAScript在不断发展，最新版ECMAScript 6标准（简称ES6）已经在2015年6月正式发布了，所以，讲到JavaScript的版本，实际上就是说它实现了ECMAScript标准的哪个版本。
  >
  > 由于浏览器在发布时就确定了JavaScript的版本，加上很多用户还在使用IE6这种古老的浏览器，这就导致你在写JavaScript的时候，要照顾一下老用户，不能一上来就用最新的ES6标准写，否则，老用户的浏览器是无法运行新版本的JavaScript代码的。
  
* 相关资料：
  * [淘宝小部件：全新的开放卡片技术！](https://mp.weixin.qq.com/s?__biz=MzIzOTU0NTQ0MA==&mid=2247504324&idx=1&sn=a0e9226d80b63d683a9047ee8e8052fd&chksm=e92aeccbde5d65ddba2cc3216ca369b6617c7f2e8774b952b0c90cbfdedc0a382460622f8641&mpshare=1&scene=23&srcid=0723mKiVHPdfejC4EFZ5Zdur&sharer_sharetime=1627055914835&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

## K

## L

### Linux

* 标签：操作系统

* 简介：

  > Linux，全称GNU/Linux，是一套免费使用和自由传播的类Unix操作系统，是一个基于POSIX的多用户、多任务、支持多线程和多CPU的操作系统。伴随着互联网的发展，Linux得到了来自全世界软件爱好者、组织、公司的支持。它除了在服务器方面保持着强劲的发展势头以外，在个人电脑、嵌入式系统上都有着长足的进步。使用者不仅可以直观地获取该操作系统的实现机制，而且可以根据自身的需要来修改完善Linux，使其最大化地适应用户的需要。 
  > Linux不仅系统性能稳定，而且是开源软件。其核心防火墙组件性能高效、配置简单，保证了系统的安全。在很多企业网络中，为了追求速度和安全，Linux不仅仅是被网络运维人员当作服务器使用，甚至当作网络防火墙，这是Linux的一大亮点。
  > Linux具有开放源码、没有版权、技术社区用户多等特点，开放源码使得用户可以自由裁剪，灵活性高，功能强大，成本低。尤其系统中内嵌网络协议栈，经过适当的配置就可实现路由器的功能。这些特点使得Linux成为开发路由交换设备的理想开发平台。

* 相关资料：

  * [用开源软件保护你的文件的 5 种方法](https://mp.weixin.qq.com/s?__biz=MzI1NDQwNDYyMg==&mid=2247489483&idx=1&sn=562d7b261eeaf0482f2acbff810cb010&chksm=e9c4e6aadeb36fbc7ee745b5ebb9a7a1395ac0bcf01295db74031b9b9d452f15c21ecccb19be&mpshare=1&scene=23&srcid=0718daFZLwXnWNhy459DKylz&sharer_sharetime=1626582266327&sharer_shareid=95e6b0ec8139f8fdad4d490f3636249e#rd)
  * [在 Linux 命令行中生成密码](https://mp.weixin.qq.com/s?__biz=MzI1NDQwNDYyMg==&mid=2247489581&idx=1&sn=d890a3a3af0430e4ce9598da8b6aa39a&chksm=e9c4e94cdeb3605a24550b3925fd0f70f8c548e8f2beafe378a35cc6d63b2d3081c1f0327a94&mpshare=1&scene=23&srcid=071883BhJTQYaiSCM07aXNdL&sharer_sharetime=1626581480830&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [52 图初探 Linux 通用知识 ](https://mp.weixin.qq.com/s?__biz=MzA4MjI3NzQ1Nw==&mid=2247494631&idx=1&sn=f1b286f1eaa02b548915fb95308b1b96&chksm=9f8a8ed9a8fd07cf733be76c65a316d6e7aff29ad0a0f8bb573f2aa3ffd29c330d2c42b0ec7a&mpshare=1&scene=23&srcid=07233yhJ9XGdq12Q0UOJeOLa&sharer_sharetime=1627055851669&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [Linux下c开发 之 线程通信 ](https://mp.weixin.qq.com/s?__biz=MjM5ODg5MDIzOQ==&mid=2650490099&idx=1&sn=ea3d7df29fcbca1b237887d66ec1b09f&chksm=becc3b6389bbb27574c6233f24a18bd0af8ca121e271d33500b3941224134509e1c7af5fd7ed&mpshare=1&scene=23&srcid=0723QVHUf42NY6iRvqnh1L7z&sharer_sharetime=1627055825276&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [深入理解编程艺术之策略与机制相分离](https://mp.weixin.qq.com/s?__biz=MzAxNDI5NzEzNg==&mid=2651163337&idx=1&sn=d664aa25dfcdf3bdba1815da7258933d&chksm=80645b96b713d2802381af29651c77bcc49ef1a09efdd4e3db9ec0ef0e8573c2f97af5a88917&mpshare=1&scene=23&srcid=0723dR7LSjrEfwc9JXD1VnPR&sharer_sharetime=1627045044681&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [如何在 CentOS、RHEL、Rocky Linux 最小化安装中设置互联网 | Linux 中国](https://mp.weixin.qq.com/s?__biz=MzI1NDQwNDYyMg==&mid=2247489585&idx=1&sn=23087fc1aa7c75491cee11d32279f36b&chksm=e9c4e950deb36046e1f1186a4e8bab943bfc18372b669aeeed3bf9cd1c02facff36a893f4ec0&mpshare=1&scene=23&srcid=0720MfnDOt5sERdVjpIJ22aV&sharer_sharetime=1626788587910&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [其实 Linux IO 模型没那么难 ](https://mp.weixin.qq.com/s?__biz=MzAwNDA2OTM1Ng==&mid=2453152913&idx=2&sn=ec8b967d37e21ca5dccbee274409cc48&chksm=8cfd0612bb8a8f049fc875a0c4abd41ac1530e3b796de6b6853700550d6735370b9d56fc0b70&mpshare=1&scene=23&srcid=08026bXYFM7kS0f5S7oz1ATk&sharer_sharetime=1627876869863&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [扒开 Linux 中断的底裤之 workqueue ](https://mp.weixin.qq.com/s?__biz=MzIxMjE1MzU4OA==&mid=2648926156&idx=1&sn=a785907196fbee0ed9fbd67c78faf652&chksm=8f5da257b82a2b410385758828b17bdf7e44472eb5837056a2fdf9754053370f9bbc9dc775cc&mpshare=1&scene=23&srcid=0802TEHA8EVb2LpyD2trW5Dj&sharer_sharetime=1627876827389&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

### LaTeX

* 标签：实用工具、TEX

* 简介：

  > LaTeX（LATEX，音译“拉泰赫”）是一种基于ΤΕΧ的排版系统，由美国计算机学家莱斯利·兰伯特（Leslie Lamport）在20世纪80年代初期开发，利用这种格式，即使使用者没有排版和程序设计的知识也可以充分发挥由TeX所提供的强大功能，能在几天、甚至几小时内生成很多具有书籍质量的印刷品。对于生成复杂表格和数学公式，这一点表现得尤为突出。因此它非常适用于生成高印刷质量的科技和数学类文档。这个系统同样适用于生成从简单的信件到完整书籍的所有其他种类的文档。

* 相关资料：
  * [笔记：LaTeX不快速入门](https://www.jianshu.com/p/fd7b312a0cad)

## M

### Markdown

* 标签：实用工具，**新手**

* 简介

  > Markdown 是一个 Web 上使用的文本到HTML的转换工具，可以通过简单、易读易写的文本格式生成结构化的HTML文档。目前 github、Stackoverflow 等网站均支持这种格式。

* 主观评价：
  * 入门简单，实用方便。写文章，记笔记必备。推荐使用Typora编辑器，只要几十分钟入门，就可以放下臃肿的Word。

### MATLAB

* 标签：数学软件

* 简介：

  > MATLAB是美国[MathWorks](https://baike.baidu.com/item/MathWorks)公司出品的商业[数学软件](https://baike.baidu.com/item/数学软件)，用于[数据分析](https://baike.baidu.com/item/数据分析/6577123)、[无线通信](https://baike.baidu.com/item/无线通信/80254)、[深度学习](https://baike.baidu.com/item/深度学习/3729729)、[图像处理](https://baike.baidu.com/item/图像处理/294902)与[计算机视觉](https://baike.baidu.com/item/计算机视觉/2803351)、[信号处理](https://baike.baidu.com/item/信号处理/84717)、量化金融与风险管理、机器人，[控制系统](https://baike.baidu.com/item/控制系统/1051898)等领域。 
  >
  > MATLAB是matrix&laboratory两个词的[组合](https://baike.baidu.com/item/组合/1218690)，意为矩阵工厂（矩阵实验室），软件主要面对科学计算、可视化以及交互式程序设计的高科技计算环境。它将[数值分析](https://baike.baidu.com/item/数值分析/20159733)、[矩阵计算](https://baike.baidu.com/item/矩阵计算/8089413)、科学数据可视化以及非[线性](https://baike.baidu.com/item/线性)动态系统的[建模](https://baike.baidu.com/item/建模/814831)和仿真等诸多强大功能集成在一个易于使用的视窗环境中，为科学研究、工程设计以及必须进行有效数值计算的众多科学领域提供了一种全面的解决方案，并在很大程度上摆脱了传统非交互式[程序设计语言](https://baike.baidu.com/item/程序设计语言/2317999)（如C、Fortran）的编辑模式。 
  >
  > MATLAB和[Mathematica](https://baike.baidu.com/item/Mathematica)、[Maple](https://baike.baidu.com/item/Maple/2306572)并称为三大数学软件。它在数学类科技应用软件中在数值计算方面首屈一指。行[矩阵](https://baike.baidu.com/item/矩阵)运算、绘制函数和数据、实现算法、创建用户界面、连接其他编程语言的程序等。MATLAB的基本数据单位是矩阵，它的[指令](https://baike.baidu.com/item/指令/3225201)[表达式](https://baike.baidu.com/item/表达式/7655228)与数学、工程中常用的形式十分相似，故用MATLAB来解算问题要比用C，[FORTRAN](https://baike.baidu.com/item/FORTRAN)等语言完成相同的事情简捷得多，并且MATLAB也吸收了像Maple等软件的优点，使MATLAB成为一个强大的[数学软件](https://baike.baidu.com/item/数学软件/3363734)。在新的版本中也加入了对[C](https://baike.baidu.com/item/C/7252092)，[FORTRAN](https://baike.baidu.com/item/FORTRAN)，[C++](https://baike.baidu.com/item/C%2B%2B)，[JAVA](https://baike.baidu.com/item/JAVA/85979)的支持。

### MyBatis

* 标签：框架，JAVA,MySQL

* 简介：

  > MyBatis 是一款优秀的持久层框架，它支持定制化 SQL、存储过程以及高级映射。MyBatis 避免了几乎所有的 JDBC 代码和手动设置参数以及获取结果集。MyBatis 可以使用简单的 XML 或注解来配置和映射原生信息，将接口和 Java 的 POJOs(Plain Ordinary Java Object,普通的 Java对象)映射成数据库中的记录。

* 相关资料
  * [MyBatis 速成手册](https://mp.weixin.qq.com/s?__biz=Mzg2MjEwMjI1Mg==&mid=2247519940&idx=2&sn=1512f11f5b844e69f409e33a1e717d2e&chksm=ce0e3947f979b0513c5241300b80307380a5a2accef6b2da02905ce4d91703e280d4fb610b9f&mpshare=1&scene=23&srcid=072616dIbgrVMhHRTsQJVoed&sharer_sharetime=1627275604915&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

### MySQL

* 标签：数据库

* 简介：

  > MySQL是一个关系型数据库管理系统，由瑞典MySQL AB 公司开发，属于 Oracle 旗下产品。MySQL 是最流行的关系型数据库管理系统之一，在 WEB 应用方面，MySQL是最好的 RDBMS (Relational Database Management System，关系数据库管理系统) 应用软件之一。
  > MySQL是一种关系型数据库管理系统，关系数据库将数据保存在不同的表中，而不是将所有数据放在一个大仓库内，这样就增加了速度并提高了灵活性。
  > MySQL所使用的 SQL 语言是用于访问数据库的最常用标准化语言。MySQL 软件采用了双授权政策，分为社区版和商业版，由于其体积小、速度快、总体拥有成本低，尤其是开放源码这一特点，一般中小型网站的开发都选择 MySQL 作为网站数据库。

* 相关资料
  * [MySQL 8.0 Server层最新架构详解](https://mp.weixin.qq.com/s?__biz=MzIzOTU0NTQ0MA==&mid=2247504340&idx=1&sn=d061b217a5be9e245964bb5d74a3887d&chksm=e92aecdbde5d65cdb6841d03e3ef124cce2e0d50428e1f3aae7a81582864334d31fa5266e7dd&mpshare=1&scene=23&srcid=072694TtD34dNoYxmyIFrSW4&sharer_sharetime=1627275547492&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

## N

### Node.js

* 标签：前端

* 简介：

  > Node.js 是一个开源与跨平台的 JavaScript 运行时环境。 它是一个可用于几乎任何项目的流行工具！
  >
  > Node.js 在浏览器外运行 V8 JavaScript 引擎（Google Chrome 的内核）。 这使 Node.js 表现得非常出色。
  >
  > Node.js 应用程序运行于单个进程中，无需为每个请求创建新的线程。 Node.js 在其标准库中提供了一组异步的 I/O 原生功能（用以防止 JavaScript 代码被阻塞），并且 Node.js 中的库通常是使用非阻塞的范式编写的（从而使阻塞行为成为例外而不是规范）。
  >
  > 当 Node.js 执行 I/O 操作时（例如从网络读取、访问数据库或文件系统），Node.js 会在响应返回时恢复操作，而不是阻塞线程并浪费 CPU 循环等待。
  >
  > 这使 Node.js 可以在一台服务器上处理数千个并发连接，而无需引入管理线程并发的负担（这可能是重大 bug 的来源）。
  >
  > Node.js 具有独特的优势，因为为浏览器编写 JavaScript 的数百万前端开发者现在除了客户端代码之外还可以编写服务器端代码，而无需学习完全不同的语言。
  >
  > 在 Node.js 中，可以毫无问题地使用新的 ECMAScript 标准，因为不必等待所有用户更新其浏览器，你可以通过更改 Node.js 版本来决定要使用的 ECMAScript 版本，并且还可以通过运行带有标志的 Node.js 来启用特定的实验中的特性。

* 相关资料：
  * [Node.js 中文网 (nodejs.cn)](http://nodejs.cn/)
  * [这些 node 开源工具你值得拥有(上)](https://mp.weixin.qq.com/s?__biz=Mzg2NjU1MjU5Ng==&mid=2247486758&idx=1&sn=45026ba22572fa415e2371ac18569ae0&chksm=ce48535df93fda4ba8c7286a749a36e7892df7c381137e65613e9b293401a7b1c203e6c2528e&mpshare=1&scene=23&srcid=0716QluYTZUKrXmvvKkYCj7t&sharer_sharetime=1626395362861&sharer_shareid=95e6b0ec8139f8fdad4d490f3636249e#rd)

### Nginx

* 标签：网站开发

* 简介：

  > **Nginx**（发音同“engine X”）是异步框架的[网页服务器](https://zh.wikipedia.org/wiki/網頁伺服器)，也可以用作[反向代理](https://zh.wikipedia.org/wiki/反向代理)、[负载平衡器](https://zh.wikipedia.org/wiki/负载均衡)和[HTTP缓存](https://zh.wikipedia.org/wiki/HTTP缓存)。该软件由[伊戈尔·赛索耶夫](https://zh.wikipedia.org/wiki/伊戈爾·賽索耶夫)（Игорь Сысоев）创建并于2004年首次公开发布[[6\]](https://zh.wikipedia.org/wiki/Nginx#cite_note-Mobily-6)。2011年成立同名公司以提供支持。2019年3月11日，Nginx公司被[F5 Networks](https://zh.wikipedia.org/w/index.php?title=F5_Networks&action=edit&redlink=1)以6.7亿美元收购。
  >
  > Nginx是免费的[开源软件](https://zh.wikipedia.org/wiki/开源软件)，根据类[BSD许可证](https://zh.wikipedia.org/wiki/BSD许可证)的条款发布。一大部分Web服务器使用Nginx，通常作为[负载均衡器](https://zh.wikipedia.org/wiki/负载均衡)。

* 相关文章：
  * [彻底搞懂 Nginx 的五大应用场景](https://mp.weixin.qq.com/s?__biz=Mzg2MjEwMjI1Mg==&mid=2247519565&idx=3&sn=30e915d2db38a75d146375d899343a70&chksm=ce0e3acef979b3d8b4ad8e9dd50ac2b1440c4fba15533b86b85e7e615f288a67d44dbe744595&mpshare=1&scene=23&srcid=0713S4sErAchhqZzbI00xqgP&sharer_sharetime=1626158088714&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

## O

## P

### Python语言

* 标签：编程语言，**新手**

* 简介：

  > Python由荷兰数学和计算机科学研究学会的[Guido van Rossum](https://baike.baidu.com/item/Guido van Rossum/3225314) 于1990 年代初设计，作为一门叫做[ABC语言](https://baike.baidu.com/item/ABC语言/334996)的替代品。 Python提供了高效的高级[数据结构](https://baike.baidu.com/item/数据结构/1450)，还能简单有效地[面向对象](https://baike.baidu.com/item/面向对象/2262089)编程。Python语法和动态类型，以及[解释型语言](https://baike.baidu.com/item/解释型语言/8888952)的本质，使它成为多数平台上写脚本和快速开发应用的编程语言，  随着版本的不断更新和语言新功能的添加，逐渐被用于独立的、大型项目的开发。 
  >
  > Python[解释器](https://baike.baidu.com/item/解释器/10418965)易于扩展，可以使用C或[C++](https://baike.baidu.com/item/C%2B%2B/99272)（或者其他可以通过C调用的语言）扩展新的功能和[数据类型](https://baike.baidu.com/item/数据类型/10997964)。  Python 也可用于可定制化软件中的扩展程序语言。Python丰富的标准库，提供了适用于各个主要系统平台的源码或[机器码](https://baike.baidu.com/item/机器码/86125)。

* 相关资料：
  * [Python静态类型解析工具简介和实践](https://mp.weixin.qq.com/s?__biz=MzIzOTU0NTQ0MA==&mid=2247504284&idx=1&sn=16873dbfc3424677c632f931d54b6523&chksm=e92aec93de5d65852bf22051f85d8bd3c10475651c60c3ca3f896a802a20ac5b316d5bfe6d0a&mpshare=1&scene=23&srcid=0720Km6v0CGdc9k7nnE6CtCB&sharer_sharetime=1626788603949&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
* 主观评价：
  * 无论你是什么专业，学点python总没错

## Q

### Qt

* 标签：图形用户界面，C++

* 简介：

  > Qt 是一个1991年由Qt Company开发的跨平台[C++](https://baike.baidu.com/item/C%2B%2B/99272)[图形用户界面](https://baike.baidu.com/item/图形用户界面/3352324)应用程序开发框架。它既可以开发GUI程序，也可用于开发非GUI程序，比如控制台工具和服务器。Qt是面向对象的框架，使用特殊的[代码](https://baike.baidu.com/item/代码/86048)生成扩展（称为元对象编译器(Meta Object Compiler, moc)）以及一些宏，Qt很容易扩展，并且允许真正地组件编程。
  >
  > 2008年，Qt Company科技被[诺基亚公司](https://baike.baidu.com/item/诺基亚公司/10858444)收购，Qt也因此成为诺基亚旗下的编程语言工具。2012年，Qt被Digia收购。
  >
  > 2014年4月，跨平台集成开发环境Qt Creator 3.1.0正式发布，实现了对于[iOS](https://baike.baidu.com/item/iOS/45705)的完全支持，新增WinRT、Beautifier等插件，废弃了无Python接口的GDB调试支持，集成了基于Clang的C/C++代码模块，并对[Android](https://baike.baidu.com/item/Android/60243)支持做出了调整，至此实现了全面支持iOS、Android、[WP](https://baike.baidu.com/item/WP/5165077),它提供给应用程序开发者建立艺术级的图形用户界面所需的所有功能。基本上，Qt 同 [X Window](https://baike.baidu.com/item/X Window/7249336) 上的 Motif，Openwin，GTK 等图形界面库和 Windows 平台上的 MFC，OWL，VCL，ATL 是同类型的东西。
* 主观评价：对于C++基础比较好、学过面向对象的人，从0开始学习Qt到完成一个简单的小游戏大概需要3~7天。学习Qt是一个一劳永逸的事，建议新生尽早学习。

## R

## S

### SSM

* 标签：框架，JAVA

* 简介：

  > SSM（Spring+SpringMVC+MyBatis）框架集由Spring、MyBatis两个开源框架整合而成（SpringMVC是Spring中的部分内容）。常作为数据源较简单的web项目的框架。
  >
  > Spring就像是整个项目中装配bean的大工厂，在配置文件中可以指定使用特定的参数去调用实体类的构造方法来实例化对象。也可以称之为项目中的粘合剂。Spring的核心思想是IoC（控制反转），即不再需要程序员去显式地`new`一个对象，而是让Spring框架帮你来完成这一切。
  > SpringMVC在项目中拦截用户请求，它的核心Servlet即DispatcherServlet承担中介或是前台这样的职责，将用户请求通过HandlerMapping去匹配Controller，Controller就是具体对应请求所执行的操作。SpringMVC相当于SSH框架中struts。
  > mybatis是对jdbc的封装，它让数据库底层操作变的透明。mybatis的操作都是围绕一个sqlSessionFactory实例展开的。mybatis通过配置文件关联到各实体类的Mapper文件，Mapper文件中配置了每个类对数据库所需进行的sql语句映射。在每次与数据库交互时，通过sqlSessionFactory拿到一个sqlSession，再执行sql命令。
  >
  > 页面发送请求给控制器，控制器调用业务层处理逻辑，逻辑层向持久层发送请求，持久层与数据库交互，后将结果返回给业务层，业务层将处理逻辑发送给控制器，控制器再调用视图展现数据。

* 相关资料：

  * [SpringBoot与MyBatis整合详细讲述 ](https://mp.weixin.qq.com/s?__biz=Mzg4MDUxODI2OQ==&mid=2247483743&idx=1&sn=8fa676cda0f617ad1bfd70761b1b0498&chksm=cf72b44df8053d5b63ac4376700734a7fd55b2ce119e426890e36217dde68c68193fb4e6d5e6&mpshare=1&scene=23&srcid=0802rqRPaAXbuqVfHp95litq&sharer_sharetime=1627877019456&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

### SpringBoot

* 标签：JAVA，Spring，框架

* 简介：

  > Spring Boot是由Pivotal团队提供的全新框架，其设计目的是用来简化新Spring应用的初始搭建以及开发过程。该框架使用了特定的方式来进行配置，从而使开发人员不再需要定义样板化的配置。通过这种方式，Spring Boot致力于在蓬勃发展的快速应用开发领域(rapid application development)成为领导者。

* 相关资料：

  * [SpringBoot 的@Value注解](https://mp.weixin.qq.com/s?__biz=MzU4MDUyMDQyNQ==&mid=2247496703&idx=1&sn=6c6989e0d9c58d073551206c6aa9a77a&chksm=fd572379ca20aa6fb593c7c083b556f99294542005e3f65e0f01d749273a37f1573bf4b5d48c&mpshare=1&scene=23&srcid=0718QaEUAiquPWX9SfuRyCvK&sharer_sharetime=1626581382767&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [SpringBoot接入支付宝](https://mp.weixin.qq.com/s?__biz=MzIwMTY0NDU3Nw==&mid=2651953745&idx=1&sn=84f677601cfc7ce6b26505e8f065f1d1&chksm=8d0ff51fba787c09104b821717259330df081b20a53372eca685bf015ea0cfc7ba27d8694dea&mpshare=1&scene=23&srcid=0721Hhmv7wAJ3lQNuBoJ3Xfh&sharer_sharetime=1626860295766&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [40 个 Spring Boot 常用注解](https://mp.weixin.qq.com/s?__biz=Mzg2MjEwMjI1Mg==&mid=2247519940&idx=1&sn=9b2c4f4bd6ec7c3bdb048b31d1a06dc9&chksm=ce0e3947f979b0512ae2c4e48c5561e7ba66be6ab7a5c15a574a99e28fbceeba656ed8f00465&mpshare=1&scene=23&srcid=0726LxDfigSgZdGwlQQssNav&sharer_sharetime=1627275588910&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

### SpringBatch

* 标签：JAVA，Spring，框架

* 简介：

  > SpringBatch 是一个大数据量的并行处理框架。通常用于数据的离线迁移，和数据处理，⽀持事务、并发、流程、监控、纵向和横向扩展，提供统⼀的接⼝管理和任务管理;SpringBatch是SpringSource和埃森哲为了统一业界并行处理标准为广大开发者提供方便开发的一套框架。
  >
  > 官方地址：github.com/spring-projects/spring-batch
  >
  > - SpringBatch 本身提供了重试，异常处理，跳过，重启、任务处理统计，资源管理等特性，这些特性开发者看重他的主要原因;
  > - SpringBatch 是一个轻量级的批处理框架;
  > - SpringBatch 结构分层，业务与处理策略、结构分离;
  > - 任务的运行的实例状态，执行数据，参数都会落地到数据库;

* 相关资料：

  * [Spring Batch：入门篇 ](https://blog.didispace.com/spring-batch-1/)
  * [首次使用批处理框架 Spring Batch ，被震撼到了](https://mp.weixin.qq.com/s?__biz=MzAwOTE3NDY5OA==&mid=2647927232&idx=1&sn=6b8a5df0c59b0326e1ab3a86fc700365&chksm=83432205b434ab13a2cfa26ad32bf5f02828503f8034043fbdd9369d9e9f526d47e1afb3929f&mpshare=1&scene=23&srcid=0717vo1YJpR1284SmkXp5dGs&sharer_sharetime=1626528492160&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

### STL

* 标签：C++，数据结构，算法

* 简介：

  > **标准模板库**是一个C++[软件库](https://baike.baidu.com/item/软件库)，大量影响了[C++标准程序库](https://baike.baidu.com/item/C%2B%2B标准程序库)但并非是其的一部分。其中包含4个组件，分别为算法、[容器](https://baike.baidu.com/item/容器)、函数、[迭代器](https://baike.baidu.com/item/迭代器)。
  >
  > [模板](https://baike.baidu.com/item/模板)是C++程序设计语言中的一个重要特征，而标准模板库正是基于此特征。标准模板库使得[C++](https://baike.baidu.com/item/C%2B%2B)编程语言在有了同[Java](https://baike.baidu.com/item/Java)一样强大的[类库](https://baike.baidu.com/item/类库)的同时，保有了更大的[可扩展性](https://baike.baidu.com/item/可扩展性)。
  >
  > 在C++标准中，STL被组织为下面的13个头文件：<algorithm>、<deque>、<functional>、<iterator>、<vector>、<list>、<map>、<memory>、<numeric>、<queue>、<set>、<stack>和<utility>。

* 相关文章：

  * [图解|从武侠角度探究STL排序算法的奥秘](https://mp.weixin.qq.com/s?__biz=MzI3ODQ3OTczMw==&mid=2247490602&idx=1&sn=28cf3b1bef8b5a7869d174e221948e3d&chksm=eb570a30dc2083269ed79ae217830350d332a98a65033b18b319d9cd332ffada064130d55b2a&mpshare=1&scene=23&srcid=0709yeRKcc5mKeghf3uAfS0z&sharer_sharetime=1625835441042&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

### 数据库(Database)

* 简介：

  > 数据库是结构化信息或数据（一般以电子形式存储在计算机系统中）的有组织的集合，通常由[数据库管理系统 (DBMS)](https://www.oracle.com/cn/database/what-is-database/#WhatIsDBMS) 来控制。在现实中，数据、DBMS 及关联应用一起被称为数据库系统，通常简称为数据库。
  >
  > 为了提高数据处理和查询效率，当今最常见的数据库通常以行和列的形式将数据存储在一系列的表中，支持用户便捷地访问、管理、修改、更新、控制和组织数据。另外，大多数数据库都使用结构化查询语言 (SQL) 来编写和查询数据。

* 相关资料：

  * [数据库是什么 | Oracle 中国](https://www.oracle.com/cn/database/what-is-database/)
  * [分库分表之后，id 主键如何处理？ ](https://mp.weixin.qq.com/s?__biz=MzAxOTQxOTc5NQ==&mid=2650501445&idx=1&sn=67ad7b6e2669c7cda793a8c5f5372d0c&chksm=83c896b9b4bf1fafe49559f9de42220854e4858867cc0f1099811a52c1b1285d2a7c87ebdd66&mpshare=1&scene=23&srcid=0723dopTdDxYLpSoSzQS23l4&sharer_sharetime=1627055896721&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

### SQL(结构化查询语言)

* 标签：数据库

* 简介：

  > 目前几乎所有的[关系数据库](https://www.oracle.com/cn/database/what-is-database/#relational)都使用 SQL 编程语言来查询、操作和定义数据，进行数据访问控制。SQL 最初于 20 世纪 70 年代由 IBM 开发，当时 Oracle 是一个主要的贡献者，这推动了 SQL ANSI 标准的实施，而 SQL 的兴起也刺激了 IBM、Oracle 和 Microsoft 等公司开始全面扩张。时至今日，虽然 SQL 仍被广泛使用，但是新的编程语言也已经崭露头角。

* 相关资料：
  * [结构化查询语言 (SQL) 是什么？](https://www.oracle.com/cn/database/what-is-database/)

### stack（堆栈)

* 标签：数据结构

* 简介：

  > **堆栈**（英语：stack）又称为**栈**或**堆叠**，是[计算机科学](https://zh.wikipedia.org/wiki/計算機科學)中的一种[抽象资料类型](https://zh.wikipedia.org/wiki/抽象資料型別)，只允许在有序的线性资料集合的一端（称为堆栈顶端，英语：top）进行加入数据（英语：push）和移除数据（英语：pop）的运算。因而按照后进先出（LIFO, Last In First Out）的原理运作。
  >
  > 常与另一种有序的线性资料集合[队列](https://zh.wikipedia.org/wiki/佇列)相提并论。
  >
  > 堆栈常用一维[数组](https://zh.wikipedia.org/wiki/陣列)或[链表](https://zh.wikipedia.org/wiki/連結串列)来实现。

* 相关文章：
  * [盘点Java基础中的Stack类及其常用方法](https://mp.weixin.qq.com/s?__biz=Mzg2MDM4OTcxNg==&mid=2247515626&idx=2&sn=1d19b5868e5efeb9b66663b54ff51579&chksm=ce25d5d1f9525cc79d93d3ff5dd27968fe8cf9144171745462a60da9d88a4c8a415d6222e433&mpshare=1&scene=23&srcid=0705lHo9An1OlwyqbszvKkrY&sharer_sharetime=1625482707248&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

### std::lock

* 标签：C++

* 简介：

  > C++11提供了两种锁封装，通过RAII方式可动态的释放锁资源，防止编码失误导致始终持有锁。
  >
  > 这两种封装是std::lock_guard和std::unique_lock，使用方式类似。

* 相关文章：

  * [我常用的 10 个 C++ 新特性](https://mp.weixin.qq.com/s?__biz=MzAxNDI5NzEzNg==&mid=2651163001&idx=1&sn=785da206529f257cc337e75f1becc56f&chksm=80645826b713d130feb765c40ca173b1fc9a8ba7a62ebf9f66bb20c40ee4b75b0c30048f5737&mpshare=1&scene=23&srcid=0702bDK9I3bVmhx3DgJRwJSx&sharer_sharetime=1625215100229&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

### 设计模式

* 标签：软件开发

* 简介：

  > 设计模式（Design pattern）代表了最佳的实践，通常被有经验的面向对象的软件开发人员所采用。设计模式是软件开发人员在软件开发过程中面临的一般问题的解决方案。这些解决方案是众多软件开发人员经过相当长的一段时间的试验和错误总结出来的。

* 相关文章：
  * [2.5 万字详解：23 种设计模式](https://mp.weixin.qq.com/s?__biz=Mzg2MjEwMjI1Mg==&mid=2247519108&idx=1&sn=b24634f5fc0ef9cd8962cedaf0cd2788&chksm=ce0e3c07f979b51138813d96244928d13a94ff974c18dddae17fdcaef0aac613a9644ce3d05d&mpshare=1&scene=23&srcid=0705EJ6y1x2FNR933Htcyurm&sharer_sharetime=1625482901541&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [命令模式&中介者模式 ](https://mp.weixin.qq.com/s?__biz=MzAwNDA2OTM1Ng==&mid=2453152691&idx=1&sn=a30669ef50a3b2e3869b7847d8210cf7&chksm=8cfd0130bb8a88269f61fe62c5265587f5348e92641bf47b5d8fa5fba6ddc53f017908056745&mpshare=1&scene=23&srcid=07208zE3QiieyQdUA2hsx1Fj&sharer_sharetime=1626788664130&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [设计模式在业务系统中的应用](https://mp.weixin.qq.com/s?__biz=MzIzOTU0NTQ0MA==&mid=2247504353&idx=1&sn=e2e91db76cdcdb8ce015ec10e107b749&chksm=e92aeceede5d65f8603919d22f92623bdbd5ae12d671f33f118e7b035fb4c70f3e245e95b5e2&mpshare=1&scene=23&srcid=0727WqRAa9pJQyIYlJjLguv7&sharer_sharetime=1627361130697&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

## T

### TEX

* 标签：实用工具

* 简介：

  > TeX是由著名的计算机科学家Donald E. Knuth（高德纳）发明的排版系统，利用TeX可以很容易地生成高质量的dvi文件，打印输出。利用dvips，dvipdfmx，pdfLaTeX等程序生成pdf，ps文件，LaTeX2html生成html文件。 它在学术界十分流行，特别是数学、物理学、统计学与计算机科学界。TeX被普遍认为是一个很好的 排版工具，特别是在处理复杂的数学公式时。利用诸如是LaTeX等终端软件，TeX就能够排版出精美的文本。通过CTAN上的宏包可以扩展其功能，可以作幻灯片，定义模板。中文支持可以由CCT、CJK、ctex等来完成。

* 相关资料：
  * [笔记：LaTeX不快速入门](https://www.jianshu.com/p/fd7b312a0cad)

### TCP(传输控制协议)

* 标签：计算机网络

* 简介：

  > 传输控制协议（TCP，Transmission Control Protocol）是为了在不可靠的互联网络上提供可靠的端到端字节流而专门设计的一个传输协议。
  > 互联网络与单个网络有很大的不同，因为互联网络的不同部分可能有截然不同的拓扑结构、带宽、延迟、数据包大小和其他参数。TCP的设计目标是能够动态地适应互联网络的这些特性，而且具备面对各种故障时的健壮性。
  > 不同主机的应用层之间经常需要可靠的、像管道一样的连接，但是IP层不提供这样的流机制，而是提供不可靠的包交换。 
  > 应用层向TCP层发送用于网间传输的、用8位字节表示的数据流，然后TCP把数据流分区成适当长度的报文段（通常受该计算机连接的网络的数据链路层的最大传输单元（MTU）的限制）。之后TCP把结果包传给IP层，由它来通过网络将包传送给接收端实体的TCP层。TCP为了保证不发生丢包，就给每个包一个序号，同时序号也保证了传送到接收端实体的包的按序接收。然后接收端实体对已成功收到的包发回一个相应的确认（ACK）；如果发送端实体在合理的往返时延（RTT）内未收到确认，那么对应的数据包就被假设为已丢失将会被进行重传。TCP用一个校验和函数来检验数据是否有错误；在发送和接收时都要计算校验和。 
  > 每台支持TCP的机器都有一个TCP传输实体。TCP实体可以是一个库过程、一个用户进程，或者内核的一部分。在所有这些情形下，它管理TCP流，以及与IP层之间的接口。TCP传输实体接受本地进程的用户数据流，将它们分割成不超过64KB（实际上去掉IP和TCP头，通常不超过1460数据字节）的分段，每个分段以单独的IP数据报形式发送。当包含TCP数据的数据报到达一台机器时，它们被递交给TCP传输实体，TCP传输实体重构出原始的字节流。为简化起见，我们有时候仅仅用“TCP”来代表TCP传输实体（一段软件）或者TCP协议（一组规则）。根据上下文语义你应该能很消楚地推断出其实际含义。例如，在“用户将数据交给TCP”这句话中，很显然这里指的是TCP传输实体。 
  > IP层并不保证数据报一定被正确地递交到接收方，也不指示数据报的发送速度有多快。正是TCP负责既要足够快地发送数据报，以便使用网络容量，但又不能引起网络拥塞：而且，TCP超时后，要重传没有递交的数据报。即使被正确递交的数据报，也可能存在错序的问题，这也是TCP的责任，它必须把接收到的数据报重新装配成正确的顺序。简而言之，TCP必须提供可靠性的良好性能，这正是大多数用户所期望的而IP又没有提供的功能。 

*  相关资料：

  * [最多能创建多少个 TCP 连接？](https://mp.weixin.qq.com/s?__biz=MzAxNDI5NzEzNg==&mid=2651163422&idx=1&sn=188132cc05cab64115bab15f893cf8f2&chksm=80645a41b713d357bb725a1d53f2504255f6eb026e56a36bff038a2a895c9e9f35f787a4da59&mpshare=1&scene=23&srcid=0802XGqvJNjQV0ZExi0oP3cC&sharer_sharetime=1627879699193&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

## U

## V

### Visual Studio Code

* 标签：IDE

* 简介：

  > Visual Studio Code（简称“VS Code”  ）是Microsoft在2015年4月30日Build开发者大会上正式宣布一个运行于 Mac OS X、Windows和 Linux 之上的，针对于编写现代Web和云应用的跨平台源代码编辑器， 可在桌面上运行，并且可用于Windows，macOS和Linux。它具有对JavaScript，TypeScript和Node.js的内置支持，并具有丰富的其他语言（例如C++，C＃，Java，Python，PHP，Go）和运行时（例如.NET和Unity）扩展的生态系统。

* 主观评价：
  * 虽然C++/C的环境配置比较复杂，但是配置完后十分好用，新手必备

### Visual Studio

* 标签：IDE

* 简介：

  > Visual Studio 集成开发环境是一种创新启动板，可用于编辑、调试并生成代码，然后发布应用 。 集成开发环境 (IDE) 是一个功能丰富的程序，可用于软件开发的许多方面。 除了大多数 IDE 提供的标准编辑器和调试器之外，Visual Studio 还包括编译器、代码完成工具、图形设计器和许多其他功能，以简化软件开发过程。

* 主观评价：
  * 相比VSCode显得比较臃肿，但是对于~~C~~/C++的学习来说十分便捷。~~你老惦记着你那Dev-C++干啥？~~

## W

## X

### XML(可扩展标记语言)

* 简介：

  > - XML 指可扩展标记语言（*EX*tensible *M*arkup *L*anguage）
  > - XML 是一种*标记语言*，很类似 HTML
  > - XML 的设计宗旨是*传输数据*，而非显示数据
  > - XML 标签没有被预定义。您需要*自行定义标签*。
  > - XML 被设计为具有*自我描述性*。

* 相关文章：

  * [什么是 XML？](https://mp.weixin.qq.com/s?__biz=MzI1NDQwNDYyMg==&mid=2247489611&idx=1&sn=89004881d4dbaa0e4bfa4d729509a076&chksm=e9c4e92adeb3603cb6e5256742f33cc5059df9c1bd02419b75b526a246aa7f532fbfc7fe93ae&mpshare=1&scene=23&srcid=080246HsIECpWLwuJXEyLoME&sharer_sharetime=1627876777310&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

  * [XML 简介](https://www.w3school.com.cn/xml/xml_intro.asp)
  * [在命令行中使用 XMLStarlet 来解析 XML ](https://mp.weixin.qq.com/s?__biz=MzI1NDQwNDYyMg==&mid=2247489611&idx=2&sn=7e63ff9ea372da9401b573a3c68cd480&chksm=e9c4e92adeb3603c7438f3c12576dd3051032f8ba09eb2096145909e0953d2adc3d337909f62&mpshare=1&scene=23&srcid=0802c7Vq7ZkzcZxip1SBt0NL&sharer_sharetime=1627876794092&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

## Y

### 云原生

* 标签：软件开发

* 简介：

  > 云原生是一种**构建和运行应用程序的方法**，是一套技术体系和方法论。云原生（CloudNative）是一个组合词，Cloud+Native。Cloud表示应用程序位于云中，而不是传统的数据中心；Native表示应用程序从设计之初即考虑到云的环境，原生为云而设计，**在云上以最佳姿势运行**，充分利用和发挥云平台的弹性+分布式优势。
  >
  > Pivotal公司的Matt Stine于2013年首次提出云原生（CloudNative）的概念；2015年，云原生刚推广时，Matt Stine在《迁移到云原生架构》一书中定义了符合云原生架构的几个特征：12因素、微服务、自敏捷架构、基于API协作、扛脆弱性；到了2017年，Matt Stine在接受InfoQ采访时又改了口风，将云原生架构归纳为模块化、可观察、可部署、可测试、可替换、可处理6特质；而Pivotal最新官网对云原生概括为4个要点：**DevOps+持续交付+微服务+容器**。
  >
  > 2015年云原生计算基金会（CNCF）成立，CNCF掺和进来后，最初把云原生定义为包括：容器化封装+自动化管理+面向微服务；到了2018年，CNCF又更新了云原生的定义，把服务网格(Service Mesh)和声明式API给加了进来。
  >
  > 可见，不同的人和组织对云原生有不同的定义，相同的人和组织在不同时间点对云原生也有不同的定义，真是乱的一匹，搞得鄙人非常晕菜，我的应对很简单，选一个我最容易记住和理解的定义：DevOps+持续交付+微服务+容器。
  >
  > **总而言之，符合云原生架构的应用程序应该是：采用开源堆栈（K8S+Docker）进行容器化，基于微服务架构提高灵活性和可维护性，借助敏捷方法、DevOps支持持续迭代和运维自动化，利用云平台设施实现弹性伸缩、动态调度、优化资源利用率。**

* 相关文章：
  * [阿里云肖力：跳过量变过程的安全质变](https://mp.weixin.qq.com/s?__biz=MzIzOTU0NTQ0MA==&mid=2247504031&idx=1&sn=55c1f58c28136a1157ef63df2734bb68&chksm=e92aed90de5d6486e842c03be46053b3221bdf515e365b6f5ea066e342346e6be772d14b0728&mpshare=1&scene=23&srcid=0705DUlHxvmOdSxKRzVUSIR1&sharer_sharetime=1625482829211&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)
  * [什么是云原生？这回终于有人讲明白了](https://zhuanlan.zhihu.com/p/150190166)

## Z

### 智能指针

* 标签：C++
* 相关文章：
  * [我常用的 10 个 C++ 新特性](https://mp.weixin.qq.com/s?__biz=MzAxNDI5NzEzNg==&mid=2651163001&idx=1&sn=785da206529f257cc337e75f1becc56f&chksm=80645826b713d130feb765c40ca173b1fc9a8ba7a62ebf9f66bb20c40ee4b75b0c30048f5737&mpshare=1&scene=23&srcid=0702bDK9I3bVmhx3DgJRwJSx&sharer_sharetime=1625215100229&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)



