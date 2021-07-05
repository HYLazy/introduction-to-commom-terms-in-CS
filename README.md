# 计科学习常见术语简介

* 仅以首字母排序
* 尽量做到周更

## A

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

    > 计算机为什么使用补码？**采用补码可以简化计算机硬件电路设计的复杂度**。
    
  * [原码, 反码, 补码 详解](https://www.cnblogs.com/zhangziqiu/archive/2011/03/30/ComputerCode.html)

## C

### CI/CD 管道

* 标签：软件开发

* 简介：

  > 持续集成（continuous integration）/持续部署（continuous deployment）（CI/CD）管道是每个 DevOps 计划的基础。CI/CD 管道打破了传统的开发孤岛，使开发和运营团队能够在整个软件开发生命周期中进行协作。
  >
  > 更好的是，转向 DevOps 和 CI/CD 管道可以帮助你的组织以更高的速度更安全地 交付软件。

* 相关文章：

  * [CI/CD 管道是什么？](https://mp.weixin.qq.com/s?__biz=MzI1NDQwNDYyMg==&mid=2247489555&idx=1&sn=087620951001f972b0402a4e562b1bae&chksm=e9c4e972deb3606494a91fb811a63c192e0700532f6a295a270112fcc380d0ac7c66b03a1a0b&mpshare=1&scene=23&srcid=0705BsBZE27LiMYOL0oTL4Py&sharer_sharetime=1625482988380&sharer_shareid=0dc610b51d544a10fbb7de1d28137982#rd)

## D

## E

## F

## G

## H

## I

## J

## K

## L

## M

## N

## O

## P

## Q

## R

## S

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



