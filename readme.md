<body bgcolor="khaki">

# <center><font color="blue">[growdu](https://github.com/growdu/blog/tree/master/page/resume.md)</font></center>

This is grwodu's [blog](https://freecode.top).

# [latest article](https://github.com/growdu/blog/tree/master/page)

* [process](https://github.com/growdu/blog/tree/master/base/process.md)
* [file opreation](https://github.com/growdu/blog/tree/master/base/file.md)
* [how to learn program](https://github.com/growdu/blog/tree/master/page/如何学习编程.md)
* [pdf parse](https://github.com/growdu/blog/tree/master/page/pdfParse.md)
 

# [base](https://github.com/growdu/blog/tree/master/base)

This [directory](https://github.com/growdu/blog/tree/master/base) store basis about program,such as

* program basis([file](https://github.com/growdu/blog/tree/master/base/file.md) and [process](https://github.com/growdu/blog/tree/master/base/process.md))
* algorithm
* data structure
* Software Architecture
* Program logic
* Mathematical knowledge

# [code](https://github.com/growdu/blog/tree/master/code)

This [directory](https://github.com/growdu/blog/tree/master/code) store code include

* [c-work](https://github.com/growdu/blog/tree/master/code/c-work)
* [java-work](https://github.com/growdu/blog/tree/master/code/java-work)
* [C#-work](https://github.com/growdu/blog/tree/master/code/C#-work)
* [python-work](https://github.com/growdu/blog/tree/master/code/python-work)
* [shell-work](https://github.com/growdu/blog/tree/master/code/shell-work)

# [page](https://github.com/growdu/blog/tree/master/page)

This [directory](https://github.com/growdu/blog/tree/master/page) store article.

* [how to learn program](https://github.com/growdu/blog/tree/master/page/如何学习编程.md)
* [pdf parse](https://github.com/growdu/blog/tree/master/page/pdfParse.md)
* [resume](https://github.com/growdu/blog/tree/master/page/resume.md)

# <center>如何学习编程</center>

## 基础

基础是指一些计算机基础知识，如计算机组成原理、数据结构、操作系统、C语言等基础知识。

### 计算机模型

主要是**CPU-内存-文件**模型。即程序保存在文件中，cpu将其读入内存，再从内存中读取程序进行执行。

编程就是把代码写到文件里保存。

cpu执行程序、读取文件到内存，操作系统和专门的编程语言已经写好，编程时调用编程语言或操作系统提供的接口就行。但需要对cpu和内存有一个简单的认识：

* cpu本质是顺序执行，即0到1，1到2
* 内存本质也是顺序，即0号宿舍，1号宿舍
* 程序执行也是顺序，即张三去倒垃圾，李四去打水
* cpu每次执行一条指令，这些指令可以认为从上到下排列，cpu里有一个指针从上到下指向指令，被指向的就会执行

### 数据结构

解决如何高效的存储数据和管理数据之间的关系。重点掌握如下结构：

* 数组（基础）
* 链表（基础）
* 队列（有用）
* 栈（常用）
* 树（常用）
* 图（复杂算法会用到）

### 操作系统

主要是[进程](https://github.com/growdu/blog/tree/master/base/process.md)和[文件](https://github.com/growdu/blog/tree/master/base/file.md)系统。

* 进程是程序执行的实体，了解程序的运行就必须了解进程。
* 编程始于文件，也终于文件，如何和读取文件、写入文件等文件操作是编程上层最基础的操作

### 编程语言

编程语言的本质是抽象和封装，原则是快速、高效、简洁、容易理解。所以哪种语言不重要，即使表面的东西不同，但一层层剥开，最终都是一样的——操作计算机（模型）。语言有一个基础就好，如

* 变量
* 函数
* 对象
* 流程结构（顺序、条件、循环）

至于具体用哪一门语言，可以根据具体的实际用途去考虑。如

* （底层）系统级编程用C或C++
*  （中层）用java或C#
*  （上层）数据分析、数据抓取用python


## 进阶

在编程基础打好后，即对计算机系统有一个完整的认识，对一个程序如何运行有一个完整的理解，或者说能控制自己的计算机。接下来的事情就是组织程序，维护程序以及花费时间。具体为：

* 设计模式
* 软件架构
* 编程框架
* 业务逻辑
* 问题建模

## 网络

以上的基础和所进行的编程仅仅是控制自己的计算机，除此外还有最重要的一环就是[网络](https://github.com/growdu/blog/tree/master/base/network.md)。

### 网络基础

* TCP/IP
* HTTP
* 服务器
* web编程

前面的基础和进阶掌握和熟练后，后续的网络也只是时间问题。
</body>