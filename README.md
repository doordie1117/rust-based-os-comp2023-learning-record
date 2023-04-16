# record

关于Rust的学习文档


## Toc

*四月*

* [4月1日~4月16日](#0)   
* [4月3日~4月9日](#1)
* [4月10日~4月16日](#2)

<span id="0"></span>

## 4月3日~4月16日

### 计划

   1、阅读 [Rust 程序设计语言](https://kaisery.github.io/trpl-zh-cn/)初步学习Rust编程语言     
   2、学习清华大学计算机系开设的[《程序设计训练（Rust）》](https://lab.cs.tsinghua.edu.cn/rust/)    
   3、参与Github Classroom完成所有Rustling练习

​    
<span id="1"></span>

## 4月3日~4月9日



  1.学习了如下课程：

  [课程介绍](https://lab.cs.tsinghua.edu.cn/rust/slides/00-intro.pdf)与[基本语法](https://lab.cs.tsinghua.edu.cn/rust/slides/01-basic.pdf)（[课堂回放](https://cloud.tsinghua.edu.cn/d/e28e066233b144ddb50c/files/?p=%2F2022-08-15 第一次课.mp4)）

  [所有权与结构化数据](https://lab.cs.tsinghua.edu.cn/rust/slides/02-own-struct.pdf)（[课堂回放](https://cloud.tsinghua.edu.cn/d/e28e066233b144ddb50c/files/?p=%2F2022-08-17 第二次课.mp4)）

  [标准库](https://lab.cs.tsinghua.edu.cn/rust/slides/03-stdlib.pdf)（[课堂回放](https://cloud.tsinghua.edu.cn/d/e28e066233b144ddb50c/files/?p=%2F2022-08-18 第三次课.mp4)）

  [泛型、特型与生命周期](https://lab.cs.tsinghua.edu.cn/rust/slides/04-adv-types.pdf)（[课堂回放](https://cloud.tsinghua.edu.cn/d/e28e066233b144ddb50c/files/?p=%2F2022-08-31 第四次课.mp4)）

  学习了Rust的基本语法，最具特点的所有权，以及生命周期、模式匹配，对rust有了一个直观的认识。Rust 是一种通用、编译型编程语言，其设计准则为“安全、并发、实用”，支持函数式、并发式、过程式以及面向对象的程序设计风格。Rust 的主要设计目标是使设计大型的互联网客户端和服务器的任务变得更容易，因此更加强调安全性、存储器配置、以及并发处理等方面的特性，能高效、便捷、安全地开发系统软件。

2. 完成了如下rustlings练习：

   | Exercise        | Book Chapter |
   | --------------- | ------------ |
   | variables       | §3.1         |
   | functions       | §3.3         |
   | if              | §3.5         |
   | primitive_types | §3.2, §4.3   |
   | vecs            | §8.1         |
   | move_semantics  | §4.1, §4.2   |
   | structs         | §5.1, §5.3   |
   | enums           | §6, §18.3    |
   | strings         | §8.2         |
   | modules         | §7           |

​     练习过程中，存在一些小疑惑都能够在Rust程序设计语言中找到对应的内容，非常有帮助。通过反复练习和看书来加深理解和记忆。

<span id="2"></span>

## 4月10日~4月16日

1.学习了如下课程：

[项目管理与常用库](https://lab.cs.tsinghua.edu.cn/rust/slides/05-org-lib.pdf)（[课堂回放](https://cloud.tsinghua.edu.cn/d/e28e066233b144ddb50c/files/?p=%2F2022-09-01 第五次课.mp4)）

[并发编程](https://lab.cs.tsinghua.edu.cn/rust/slides/06-concurrency.pdf)（[课堂回放](https://cloud.tsinghua.edu.cn/d/e28e066233b144ddb50c/files/?p=%2F2022-09-05 第六次课.mp4)）

[I/O 与异步编程](https://lab.cs.tsinghua.edu.cn/rust/slides/07-io-async.pdf)（[课堂回放](https://cloud.tsinghua.edu.cn/d/e28e066233b144ddb50c/files/?p=%2F2022-09-07 第七次课.mp4)）

[高级特性与编程语言综述](https://lab.cs.tsinghua.edu.cn/rust/slides/08-adv-features-survey.pdf)（[课堂回放](https://cloud.tsinghua.edu.cn/d/e28e066233b144ddb50c/files/?p=%2F2022-09-08 第八次课.mp4)）

更加深入地了解了Rust的相关知识

2.完成了如下rustlings练习：

| Exercise               | Book Chapter        |
| ---------------------- | ------------------- |
| hashmaps               | §8.3                |
| options                | §10.1               |
| error_handling         | §9                  |
| generics               | §10                 |
| traits                 | §10.2               |
| tests                  | §11.1               |
| lifetimes              | §10.3               |
| standard_library_types | §13.2, §15.1, §16.3 |
| threads                | §16.1, §16.2, §16.3 |
| macros                 | §19.6               |
| clippy                 | n/a                 |
| conversions            | n/a                 |

越往后练习的难度增加，不是简单的查阅参考书籍就能直接解决，需要融会贯通以往的知识点，了解到了trait的用途和用法，能够简单编写多线程程序，了解宏定义，更加关注编码时对于内存的安全性的严格要求。
