# 介绍
本仓库作为学习《计算机程序的构造和解释》(sicp)第二版书籍练习题代码仓库储存，使用的语言是scheme，为lisp的一种。

# 结构分层
## 文件目录分层
结构分层以大章为**文件夹**，以chap为开头命名。
小节为**文件**，以小节名命名。
比如第一章构造构成抽象，第一节程序设计的基本元素的习题，可以去/chap-1/1.1.scm当中查看。每章的习题号是唯一的。
## 通用函数
每一章通用到的函数，会放在章节文件夹的**chapCommon.scm**文件下。总用到的函数，会放在最外层的**common.scm**文件下。
由于scheme没有模块引入系统。每次用到外部的函数会在底部以注释的方式声明。届时可以去相关的文件下面去查找。

# 关于习题
本书的习题没有完整实现。由于工作强度导致的时间的问题，会跳过以下习题：
1. 难点在数学性上面，而非编程逻辑上面的习题。(如帕斯卡三角形、黄金分割等)
2. 太过编程基础性的内容(如查看这些代码的运算结果)
3. 知识点重复的内容
具体跳过的内容和代码的分析，可以参考阅读分析。

# 阅读分析
对书籍的阅读分析请移步我的[个人博客](https://www.tangdingblog.cn/blog/)。
