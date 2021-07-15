# 计科学习常见术语简介

* 尽量做到周更。
* 仅以首字母排序。
* 如果对于术语的常见称呼为中文，则按中文首字母排序。否则为英文。
* 部分词条的评价部分具有主观性，请谨慎看待。
* 对于计科新生有帮助的词条会打上新手标签。

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

* 标签：编程语言，新手

* 简介：

  > C语言是一门面向过程的编译型语言，它的运行速度极快，仅次于汇编语言。C语言是计算机产业的核心语言，操作系统、硬件驱动、关键组件、数据库等都离不开C语言。

### C++语言

* 标签：编程语言，新手

* 简介：

  > C++是C语言的继承，它既可以进行[C语言](https://baike.baidu.com/item/C语言/105958)的过程化[程序设计](https://baike.baidu.com/item/程序设计/223952)，又可以进行以抽象数据类型为特点的基于对象的程序设计，还可以进行以继承和多态为特点的面向对象的程序设计。C++擅长面向对象程序设计的同时，还可以进行基于过程的程序设计，因而C++就适应的问题规模而论，大小由之。 
  >
  > C++不仅拥有计算机高效运行的实用性特征，同时还致力于提高大规模程序的编程质量与程序设计语言的问题描述能力。 

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

### DevOps

* 标签：软件开发

* 简介：

  > DevOps追求更短的迭代周期、更高频的发布。但发布的次数越多，引入故障的可能性就越大。更多的故障将会降低服务的可用性，进而影响到客户体验。所以，为了保证服务质量，守好发布这个最后一道关，阿里逐步发展出了适应DevOps要求的发布策略。

* 相关资料：
  * [DevOps发布策略简介](https://mp.weixin.qq.com/s?__biz=MzIzOTU0NTQ0MA==&mid=2247504053&idx=1&sn=d81ed8301ad290c7f04cbf0a7f6be1d9&chksm=e92aedbade5d64ac0f979275848c4664609e9be8e0254b04129dec214b59bb0c5e26ea549761&mpshare=1&scene=23&srcid=0707NMIx0bb4zqCBdzPpBTsP&sharer_sharetime=1625650520997&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

## E

## F

### 分布式

* 简介：

  > 分布式系统是若干独立计算机的集合，这计算机对用户来说就像单个相关系统。

* 相关资料：
  * [到底什么是分布式系统？]([到底什么是分布式系统？ - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/62623474))

## G

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

* 标签：编程语言，新手

* 简介：

  > - Java 是一项用于开发应用程序的技术，可以让 Web 变得更有意思和更实用。 Java 与 javascript 并不相同，后者是一种用于创建 Web 页的简单技术，只能在浏览器中运行。
  > - 使用 Java 可以玩游戏、上载照片、联机聊天以及参与虚拟体验，并能够使用联机培训、网上银行和互动地图等服务。如果没有安装 Java，则许多应用程序和网站都无法工作。

* 相关文章：

  * [什么是 Java？](https://www.java.com/zh-CN/about/whatis_java.jsp)

## K

## L

### LaTeX

* 标签：实用工具、TEX

* 简介：

  > LaTeX（LATEX，音译“拉泰赫”）是一种基于ΤΕΧ的排版系统，由美国计算机学家莱斯利·兰伯特（Leslie Lamport）在20世纪80年代初期开发，利用这种格式，即使使用者没有排版和程序设计的知识也可以充分发挥由TeX所提供的强大功能，能在几天、甚至几小时内生成很多具有书籍质量的印刷品。对于生成复杂表格和数学公式，这一点表现得尤为突出。因此它非常适用于生成高印刷质量的科技和数学类文档。这个系统同样适用于生成从简单的信件到完整书籍的所有其他种类的文档。

* 相关资料：
  * [笔记：LaTeX不快速入门](https://www.jianshu.com/p/fd7b312a0cad)

## M

### MATLAB

* 标签：数学软件

* 简介：

  > MATLAB是美国[MathWorks](https://baike.baidu.com/item/MathWorks)公司出品的商业[数学软件](https://baike.baidu.com/item/数学软件)，用于[数据分析](https://baike.baidu.com/item/数据分析/6577123)、[无线通信](https://baike.baidu.com/item/无线通信/80254)、[深度学习](https://baike.baidu.com/item/深度学习/3729729)、[图像处理](https://baike.baidu.com/item/图像处理/294902)与[计算机视觉](https://baike.baidu.com/item/计算机视觉/2803351)、[信号处理](https://baike.baidu.com/item/信号处理/84717)、量化金融与风险管理、机器人，[控制系统](https://baike.baidu.com/item/控制系统/1051898)等领域。 
  >
  > MATLAB是matrix&laboratory两个词的[组合](https://baike.baidu.com/item/组合/1218690)，意为矩阵工厂（矩阵实验室），软件主要面对科学计算、可视化以及交互式程序设计的高科技计算环境。它将[数值分析](https://baike.baidu.com/item/数值分析/20159733)、[矩阵计算](https://baike.baidu.com/item/矩阵计算/8089413)、科学数据可视化以及非[线性](https://baike.baidu.com/item/线性)动态系统的[建模](https://baike.baidu.com/item/建模/814831)和仿真等诸多强大功能集成在一个易于使用的视窗环境中，为科学研究、工程设计以及必须进行有效数值计算的众多科学领域提供了一种全面的解决方案，并在很大程度上摆脱了传统非交互式[程序设计语言](https://baike.baidu.com/item/程序设计语言/2317999)（如C、Fortran）的编辑模式。 
  >
  > MATLAB和[Mathematica](https://baike.baidu.com/item/Mathematica)、[Maple](https://baike.baidu.com/item/Maple/2306572)并称为三大数学软件。它在数学类科技应用软件中在数值计算方面首屈一指。行[矩阵](https://baike.baidu.com/item/矩阵)运算、绘制函数和数据、实现算法、创建用户界面、连接其他编程语言的程序等。MATLAB的基本数据单位是矩阵，它的[指令](https://baike.baidu.com/item/指令/3225201)[表达式](https://baike.baidu.com/item/表达式/7655228)与数学、工程中常用的形式十分相似，故用MATLAB来解算问题要比用C，[FORTRAN](https://baike.baidu.com/item/FORTRAN)等语言完成相同的事情简捷得多，并且MATLAB也吸收了像Maple等软件的优点，使MATLAB成为一个强大的[数学软件](https://baike.baidu.com/item/数学软件/3363734)。在新的版本中也加入了对[C](https://baike.baidu.com/item/C/7252092)，[FORTRAN](https://baike.baidu.com/item/FORTRAN)，[C++](https://baike.baidu.com/item/C%2B%2B)，[JAVA](https://baike.baidu.com/item/JAVA/85979)的支持。

## N

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

* 标签：编程语言，新手

* 简介：

  > Python由荷兰数学和计算机科学研究学会的[Guido van Rossum](https://baike.baidu.com/item/Guido van Rossum/3225314) 于1990 年代初设计，作为一门叫做[ABC语言](https://baike.baidu.com/item/ABC语言/334996)的替代品。 Python提供了高效的高级[数据结构](https://baike.baidu.com/item/数据结构/1450)，还能简单有效地[面向对象](https://baike.baidu.com/item/面向对象/2262089)编程。Python语法和动态类型，以及[解释型语言](https://baike.baidu.com/item/解释型语言/8888952)的本质，使它成为多数平台上写脚本和快速开发应用的编程语言，  随着版本的不断更新和语言新功能的添加，逐渐被用于独立的、大型项目的开发。 
  >
  > Python[解释器](https://baike.baidu.com/item/解释器/10418965)易于扩展，可以使用C或[C++](https://baike.baidu.com/item/C%2B%2B/99272)（或者其他可以通过C调用的语言）扩展新的功能和[数据类型](https://baike.baidu.com/item/数据类型/10997964)。  Python 也可用于可定制化软件中的扩展程序语言。Python丰富的标准库，提供了适用于各个主要系统平台的源码或[机器码](https://baike.baidu.com/item/机器码/86125)。

## Q

### Qt

* 标签：图形用户界面，C++

* 简介：

  > Qt 是一个1991年由Qt Company开发的跨平台[C++](https://baike.baidu.com/item/C%2B%2B/99272)[图形用户界面](https://baike.baidu.com/item/图形用户界面/3352324)应用程序开发框架。它既可以开发GUI程序，也可用于开发非GUI程序，比如控制台工具和服务器。Qt是面向对象的框架，使用特殊的[代码](https://baike.baidu.com/item/代码/86048)生成扩展（称为元对象编译器(Meta Object Compiler, moc)）以及一些宏，Qt很容易扩展，并且允许真正地组件编程。
  >
  > 2008年，Qt Company科技被[诺基亚公司](https://baike.baidu.com/item/诺基亚公司/10858444)收购，Qt也因此成为诺基亚旗下的编程语言工具。2012年，Qt被Digia收购。
  >
  > 2014年4月，跨平台集成开发环境Qt Creator 3.1.0正式发布，实现了对于[iOS](https://baike.baidu.com/item/iOS/45705)的完全支持，新增WinRT、Beautifier等插件，废弃了无Python接口的GDB调试支持，集成了基于Clang的C/C++代码模块，并对[Android](https://baike.baidu.com/item/Android/60243)支持做出了调整，至此实现了全面支持iOS、Android、[WP](https://baike.baidu.com/item/WP/5165077),它提供给应用程序开发者建立艺术级的图形用户界面所需的所有功能。基本上，Qt 同 [X Window](https://baike.baidu.com/item/X Window/7249336) 上的 Motif，Openwin，GTK 等图形界面库和 Windows 平台上的 MFC，OWL，VCL，ATL 是同类型的东西。
  * 评价：对于C++基础比较好、学过面向对象的人，从0开始学习Qt到完成一个简单的小游戏大概需要3~7天。学习Qt是一个一劳永逸的事，建议新生尽早学习。

## R

## S

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

  * [数据库的定义]([数据库是什么 | Oracle 中国](https://www.oracle.com/cn/database/what-is-database/))

### SQL(结构化查询语言)

* 标签：数据库

* 简介：

  > 目前几乎所有的[关系数据库](https://www.oracle.com/cn/database/what-is-database/#relational)都使用 SQL 编程语言来查询、操作和定义数据，进行数据访问控制。SQL 最初于 20 世纪 70 年代由 IBM 开发，当时 Oracle 是一个主要的贡献者，这推动了 SQL ANSI 标准的实施，而 SQL 的兴起也刺激了 IBM、Oracle 和 Microsoft 等公司开始全面扩张。时至今日，虽然 SQL 仍被广泛使用，但是新的编程语言也已经崭露头角。

* 相关资料：
  * [结构化查询语言 (SQL) 是什么？]([数据库是什么 | Oracle 中国](https://www.oracle.com/cn/database/what-is-database/))

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

## T

### TEX

* 标签：实用工具

* 简介：

  > TeX是由著名的计算机科学家Donald E. Knuth（高德纳）发明的排版系统，利用TeX可以很容易地生成高质量的dvi文件，打印输出。利用dvips，dvipdfmx，pdfLaTeX等程序生成pdf，ps文件，LaTeX2html生成html文件。 它在学术界十分流行，特别是数学、物理学、统计学与计算机科学界。TeX被普遍认为是一个很好的 排版工具，特别是在处理复杂的数学公式时。利用诸如是LaTeX等终端软件，TeX就能够排版出精美的文本。通过CTAN上的宏包可以扩展其功能，可以作幻灯片，定义模板。中文支持可以由CCT、CJK、ctex等来完成。

* 相关资料：
  * [笔记：LaTeX不快速入门](https://www.jianshu.com/p/fd7b312a0cad)

## U

## V

## W

## X

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
  * [什么是云原生？这回终于有人讲明白了]([什么是云原生？这回终于有人讲明白了 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/150190166))

## Z

### 智能指针

* 标签：C++
* 相关文章：
  * [我常用的 10 个 C++ 新特性](https://mp.weixin.qq.com/s?__biz=MzAxNDI5NzEzNg==&mid=2651163001&idx=1&sn=785da206529f257cc337e75f1becc56f&chksm=80645826b713d130feb765c40ca173b1fc9a8ba7a62ebf9f66bb20c40ee4b75b0c30048f5737&mpshare=1&scene=23&srcid=0702bDK9I3bVmhx3DgJRwJSx&sharer_sharetime=1625215100229&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)



