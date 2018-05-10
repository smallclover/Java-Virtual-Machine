# Java-Virtual-Machine
Java虚拟机资源汇总

## 最后更新时间
**2018-05-10**

## 注意
1. 资料的排列的顺序是字母序
2. 资料的所有权归原作者所有，这里是汇总。
3. 知识水平的限制，导致资料的介绍或者范围有一定的局限性，欢迎指出。

## 理论

### Java 虚拟机规范英文版（官方版）

> 资料类型：.html和.PDF

> 版本：Second Edition~ Java SE 10 Edition

+ [The Java® Virtual Machine Specification](https://docs.oracle.com/javase/specs/index.html)

### Java虚拟机知识宝库
 
> 资料类型：ITeye博客
>
> 内容：关于JVM的各种知识
>
> 作者：[RednaxelaFX](http://rednaxelafx.iteye.com/)
>
> 注：（人形自走代码库，该目录列举数量太多，这里就不具体展开，请自行察看）

+ [自己关于VM的帖的目录](http://rednaxelafx.iteye.com/blog/362738)


### Java虚拟机原理图解专栏

> 资料类型：CSDN博客
>
> 内容：介绍了Java虚拟机类的加载，解析
>
> 作者：[亦山](https://blog.csdn.net/luanlouis)
>
> 注：（作者的标题命名格式不统一，这里保持原状）

+ [Java虚拟机原理图解](https://blog.csdn.net/column/details/jvm-principle.html)
    - [1.1、class文件基本组织结构](http://blog.csdn.net/luanlouis/article/details/39892027)
    - [1.2、class文件中的常量池](http://blog.csdn.net/luanlouis/article/details/40148053)
    - [1.2.2、Class文件中的常量池详解（上）](http://blog.csdn.net/luanlouis/article/details/39960815)
    - [1.2.3、Class文件中的常量池详解（下）](http://blog.csdn.net/luanlouis/article/details/40301985)
    - [1.3、class文件中的访问标志、类索引、父类索引、接口索引集合](http://blog.csdn.net/luanlouis/article/details/41039269)
    - [1.4 class文件中的字段表集合--field字段在class文件中是怎样组织的](http://blog.csdn.net/luanlouis/article/details/41046443)
    - [1.5、 class文件中的方法表集合--method方法在class文件中是怎样组织的](http://blog.csdn.net/luanlouis/article/details/41113695)
    - [3、JVM运行时数据区](http://blog.csdn.net/luanlouis/article/details/40043991)
    - [4.JVM机器指令集](http://blog.csdn.net/luanlouis/article/details/50412126)
    - [5. JVM类加载器机制与类加载过程](http://blog.csdn.net/luanlouis/article/details/50529868)

### 深入理解Java虚拟机
> 资料类型：书籍
>
> 作者：周志明 
>
> 内容：全面的介绍了Java虚拟机

+ 《深入理解Java虚拟机:JVM高级特性与最佳实践》

### 垃圾回收的算法与实现

> 资料类型：书籍
>
> 作者：中村成洋
>
> 内容：介绍了垃圾回收的算法，该书分为两个部分，算法篇和实现篇。
> 算法篇描述时使用伪代码来描述，脱离了具体的语言；
> 实现篇需要有一定的C/C++的基础

+ 《垃圾回收的算法与实现》

### 自己动手写Java虚拟机

> 资料类型：书籍
>
> 作者：张秀宏 
>
> 内容：教你一步步编写一个Java虚拟机，需要Go语言的知识

+ 《自己动手写Java虚拟机》

## toy_jvm

> 作者：[kevinlynx](http://codemacro.com)

github&配套文章：

github：

+ [toy_jvm](https://github.com/kevinlynx/toy_jvm)
+ [toy_jit](https://github.com/kevinlynx/toy_jit)

文章：

+ [写一个玩具Java虚拟机](http://codemacro.com/2017/02/25/toy-jvm/)
+ [实现JVM中的JIT](http://codemacro.com/2017/03/09/toy-jit/)


## write your own JVM
> 作者：[zachaxy](https://zachaxy.github.io/)

github&配套文章：

github：

+ [JVM](https://github.com/zachaxy/JVM)

文章系列:

+ [手写JVM系列](https://zachaxy.github.io/tags/JVM/)
  - [手写JVM系列(1)-准备工作](https://zachaxy.github.io/2017/05/06/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-1-%E5%87%86%E5%A4%87%E5%B7%A5%E4%BD%9C/)          
  - [手写JVM系列(2)-参数解析](https://zachaxy.github.io/2017/05/07/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-2-%E5%8F%82%E6%95%B0%E8%A7%A3%E6%9E%90/)         
  - [手写JVM系列(3)-搜索class文件](https://zachaxy.github.io/2017/05/08/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-3-%E6%90%9C%E7%B4%A2class%E6%96%87%E4%BB%B6/)          
  - [手写JVM系列(4)-分析class文件](https://zachaxy.github.io/2017/05/09/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-4-%E5%88%86%E6%9E%90class%E6%96%87%E4%BB%B6/)
  - [手写JVM系列(5)-分析class文件-常量池](https://zachaxy.github.io/2017/05/09/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-5-%E5%88%86%E6%9E%90class%E6%96%87%E4%BB%B6-%E5%B8%B8%E9%87%8F%E6%B1%A0/)         
  - [手写JVM系列(6)-分析class文件-属性表](https://zachaxy.github.io/2017/05/09/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-6-%E5%88%86%E6%9E%90class%E6%96%87%E4%BB%B6-%E5%B1%9E%E6%80%A7%E8%A1%A8/)          
  - [手写JVM系列(7)-读取class文件](https://zachaxy.github.io/2017/05/10/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-7-%E8%AF%BB%E5%8F%96class%E6%96%87%E4%BB%B6/)          
  - [手写JVM系列(8)-运行时数据](https://zachaxy.github.io/2017/05/12/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-8-%E7%BA%BF%E7%A8%8B%E7%A7%81%E6%9C%89%E7%9A%84%E8%BF%90%E8%A1%8C%E6%97%B6%E6%95%B0%E6%8D%AE/)         
  - [手写JVM系列(9)-指令集](https://zachaxy.github.io/2017/05/13/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-9-%E6%8C%87%E4%BB%A4%E9%9B%86/)  
  - [手写JVM系列(10)-解释器](https://zachaxy.github.io/2017/05/15/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-10%E8%A7%A3%E9%87%8A%E5%99%A8/)   - [手写JVM系列(11)-线程共享的运行时数据](https://zachaxy.github.io/2018/01/03/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-11-%E7%BA%BF%E7%A8%8B%E5%85%B1%E4%BA%AB%E7%9A%84%E8%BF%90%E8%A1%8C%E6%97%B6%E6%95%B0%E6%8D%AE/)
  - [手写JVM系列(12)-类加载器的实现](https://zachaxy.github.io/2018/01/04/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-12-%E7%B1%BB%E5%8A%A0%E8%BD%BD%E5%99%A8%E7%9A%84%E5%AE%9E%E7%8E%B0/)          
  - [手写JVM系列(13)-方法调用机制](https://zachaxy.github.io/2018/01/04/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-13-%E6%96%B9%E6%B3%95%E8%B0%83%E7%94%A8%E6%9C%BA%E5%88%B6/)
  - [手写JVM系列(14)-数组的实现](https://zachaxy.github.io/2018/01/12/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-14-%E6%95%B0%E7%BB%84%E7%9A%84%E5%AE%9E%E7%8E%B0/)  
  - [手写JVM系列(15)-字符串的实现](https://zachaxy.github.io/2018/01/16/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-15-%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9A%84%E5%AE%9E%E7%8E%B0/) 
  - [手写JVM系列(16)反射机制简介](https://zachaxy.github.io/2018/01/18/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-16-%E5%8F%8D%E5%B0%84%E6%9C%BA%E5%88%B6%E7%AE%80%E4%BB%8B/)
  - [手写JVM系列(17)本地方法的调用过程](https://zachaxy.github.io/2018/01/18/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-17-%E6%9C%AC%E5%9C%B0%E6%96%B9%E6%B3%95%E7%9A%84%E8%B0%83%E7%94%A8%E8%BF%87%E7%A8%8B/)          
  - [手写JVM系列(18)异常处理机制](https://zachaxy.github.io/2018/01/20/%E6%89%8B%E5%86%99JVM%E7%B3%BB%E5%88%97-18-%E5%BC%82%E5%B8%B8%E5%A4%84%E7%90%86%E6%9C%BA%E5%88%B6/)          
## 欢迎补充
