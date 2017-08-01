#Java语言基础
###一、java语言的特点
1.简单性

2.解释性

3.高性能

4.分布式处理

5.多线程

6.健壮性

7.动态

8.结构中立

9.安全性开放

10.跨平台

java语言跨平台的原理：只要在需要运行java应用程序的操作系统上先装一个JVM(Java Virtual Machine)，由JVM来负责Java程序在该系统中运行。

### 二、JRE和JDK概述

1.JRE(Java Runtime Enviroment)

包括了JVM和Java程序所需要的核心类库，如果想运行一个Java程序，只需要安装好JRE即可。

JRE = JVM + 核心类库

2.JDK

其中是供开发人员使用的，包括了Java的开发工具，也包含了JRE。

Java的开发工具：编译工具(javac)，打包工具(jar)。

jdk = JRE + java开发工具

![jre+jdk+jvm的关系](/Users/wangjun/Desktop/git/Java学习/java基础/day1/jre+jdk+jvm.png)