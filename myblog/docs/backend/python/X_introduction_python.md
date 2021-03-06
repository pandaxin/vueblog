# Python介绍
[[toc]]


本文简要介绍一下Python。

## 概要

Python是一种计算机程序设计语言。是一门高级的、动态的、面向对象、解释性的脚本语言，最初被设计用于编写自动化脚本(shell)，随着版本的不断更新和语言新功能的添加，越来越多被用于独立的、大型项目的开发。

说明：

- 高级语言：高级语言贴近开发者(Python，Java)，对应于底层语言(如C、C++、汇编)，底层语言贴近机器。越底层的语言越能操作计算机硬件。
- 动态语言：相对于静态语言，静态语言要求在必须声明每个变量的类型，它会使用多少内存以及允许使用的方法；动态语言并不需要在使用变量进行声明。动态语言通常比编译后的静态语言更慢。
- 面向对象：对应于面向过程，是开发人员在开发过程当中的思路，是程序员的世界观。是Python开发的核心，是一种编程思维。
- 解释性：对应于编译性语言(如C语言)，Python每次执行都需要执行脚本，不会被编译，而是由解释器程序来解释执行。

## Python 发展历史


Python的创始人为荷兰人吉多·范罗苏姆（Guido van Rossum）。1989年圣诞节期间，在阿姆斯特丹，Guido为了打发圣诞节的无趣，决心开发一个新的脚本解释程序，作为ABC 语言的一种继承。之所以选中Python（大蟒蛇的意思）作为该编程语言的名字，是取自英国20世纪70年代首播的电视喜剧《蒙提·派森干的飞行马戏团》（Monty Python's Flying Circus）。

Python已经成为最受欢迎的程序设计语言之一。自从2004年以后，python的使用率呈线性增长。Python 2于2000年10月16日发布，稳定版本是Python 2.7。Python 3于2008年12月3日发布，不完全兼容Python 2。 2011年1月，它被TIOBE编程语言排行榜评为2010年度语言。JavaScript，Java和Python是2018年学习工作的最佳编程语言。TIOBE编程语言排行榜评定Python是2018年的Programming Language Hall of Fame(编程语言名人堂)获得者。

- Python之父: Guido van Rossum

## Python应用


Python的应用非常广泛：

- 系统编程：提供API，能够方便的进行系统维护和管理。Linux下标志性语言之一，是很多系统管理员理想的编程工具。如yum，trash-put等工具。
- 图形处理：有PIL、Tkinter等图形库支持，能方便进行图形处理。
- 数学处理：NumPy扩展提供大量与许多标准数学库的接口。
- 文本处理：python提供的re模块能支持正则表达式，还提供SGML，XML分析模块，许多程序员利用python进行XML程序的开发。
- 数据库编程：程序员可通过遵循Python DB-API（数据库应用程序编程接口）规范的模块与Microsoft SQL Server，Oracle，Sybase，DB2，MySQL、SQLite等数据库通信。python自带有一个Gadfly模块，提供了一个完整的SQL环境。
- 网络编程：提供丰富的模块支持sockets编程，能方便快速地开发分布式应用程序。很多大规模软件开发计划例如Zope，Mnet 及BitTorrent. Google都在广泛地使用它。
- Web编程：应用的开发语言，支持最新的XML技术。
- 自动化运维：这几乎是Python应用的自留地，作为运维工程师首选的编程语言，Python在自动化运维方面已经深入人心，比如Saltstack和Ansible都是大名鼎鼎的自动化平台。
- 云计算: 开源云计算解决方案OpenStack就是基于Python开发的。
- 网络爬虫：也称网络蜘蛛，是大数据行业获取数据的核心工具。没有网络爬虫自动地、不分昼夜地、高智能地在互联网上爬取免费的数据，那些大数据相关的公司恐怕要少四分之三。能够编写网络爬虫的编程语言有不少，但Python绝对是其中的主流之一，其Scripy爬虫框架应用非常广泛。

- 数据分析：在大量数据的基础上，结合科学计算、机器学习等技术，对数据进行清洗、去重、规格化和针对性的分析是大数据行业的基石。Python是数据分析的主流语言之一。
- 人工智能：Python在人工智能大范畴领域内的机器学习、神经网络、深度学习等方面都是主流的编程语言，得到广泛的支持和应用。

## Python2 or Python3


Python语言作者Guido van Rossum在 [邮件](https://mail.python.org/pipermail/python-dev/2018-March/152348.html)  列表上宣布 Python 2.7将于2020年1月1日终止支持。用户如果想要在这个日期之后继续得到与Python 2.7有关的支持，则需要付费给商业供应商。

由Python2即将失去官方支持，后续进行Python开发时，请使用Python3。

## Python优缺点


优点：

- 简单易学
- 可移植
- 丰富的库

缺点：

- 运行速度慢：代码执行时需要一行一行地翻译成计算机的机器码，翻译过程耗时，但是大量的应用程序不需要这么快的运行速度，因为用户根本感觉不出来。

![do_not_care_about_runtime.jpg](/img/do_not_care_about_runtime.jpg)

- 代码不能加密：如果要发布你的Python程序，实际上就是发布源代码，凡是编译型的语言，都没有这个问题，而解释型的语言，则必须把源码发布出去。

![have_no_time_check_your_fuck_code.jpg](/img/have_no_time_check_your_fuck_code.jpg)


参考文献：

- [廖雪峰的Python教程](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000/001431608990315a01b575e2ab041168ff0df194698afac000)


