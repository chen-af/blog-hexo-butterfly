---
layout: _post
title: Hello World
date: 2022-12-05 13:50:00
keywords: Hello World 你好世界
description: Hello World 你好世界
top_img: https://mp-d7930f7b-df5c-4ab2-9b66-d51c38b2bf6c.cdn.bspapp.com/cloudstorage/bce69d22-b969-4ce1-ad77-c83e8f9c94c5.jpg
cover: https://mp-d7930f7b-df5c-4ab2-9b66-d51c38b2bf6c.cdn.bspapp.com/cloudstorage/bce69d22-b969-4ce1-ad77-c83e8f9c94c5.jpg
---

{% note 'fa-solid fa-laptop-code' modern %}
Hello World 中文意思是“你好，世界”。因为 The C Programming Language 中使用它做为第一个演示程序，后来的程序员在学习编程或进行设备调试时延续了这一习惯。
{% endnote %}

---

产生由来
======

“Hello, world"程序是指在计算机屏幕上输出“Hello world”这行字符串的计算机程序，“Hello World”的中文意思是“你好，世界。”。这个例程在 Brian Kernighan 和 Dennis M. Ritchie合著的The C Programme Language使用而广泛流行。因为它的简洁，实用，并包含了一个该版本的C程序首次在1974年 Brian Kernighan 所撰写的 Programming in C: A Tutorial 出现。

---

20种写法
======

C
------

{% note 'fa-solid fa-c' modern %}
C语言是世界上最重要的编程语言。
这是Windows，MacOS，iOS和Android等操作系统、浏览器和3D游戏引擎的主要编程语言。
它的语法和书写习惯影响了无数其他编程语言。
{% endnote %}

```
/* Hello world in C */

#include <stdio.h>

main()
{
    printf("Hello World!\n");
}
```

---
Java
------

{% note 'fa-brands fa-java' modern %}
Java语言是世界上最流行的编程语言，没有之一。
它的特殊之处在于它经过专门设计，你只需要编写一次代码，然后就可以在任何操作系统上运行。
{% endnote %}

```
// Hello World in Java

class HelloWorld {
  static public void main( String args[] ) {
    System.out.println( "Hello World!" );
  }
}
```

---

Python
------

{% note 'fa-brands fa-python' modern %}
与Java或C ++之类的语言相比，Python的语法紧凑，所需的代码要少得多。
它非常流行，并常用于网站和人工智能（AI）任务等。
{% endnote %}

```
# Hello world in Python 3

print("Hello World")
```

---

R
------

{% note 'fa-solid fa-r' modern %}
一种出色的统计语言，也是科学界的流行选择。
{% endnote %}

```
# Hello World in R

cat("Hello world\n")
```

---

JavaScript
------

{% note 'fa-brands fa-js' modern %}
JavaScript是世界上最常见的编程语言。
几乎所有的Web浏览器都在使用这种编程语言，这也使JavaScript成为WEB交互的标准。
{% endnote %}

```
// Hello world in JavaScript

console.log("Hello World");
```

---

C++
------

{% note 'fa-solid fa-c' modern %}
性能接近C，并在许多重要项目（例如Chrome浏览器）中使用。C ++旨在使一种语言更易于构建大型项目，同时仍保持快速和高效。
{% endnote %}

```
// Hello World in C++ (pre-ISO)

#include <iostream.h>

main()
{
    cout << "Hello World!" << endl;
    return 0;
}
```

---

Go
------

{% note 'fa-brands fa-golang' modern %}
Go（又称Golang）是Google开发的一种静态强类型、编译型、并发型，并具有垃圾回收功能的编程语言。
{% endnote %}

```
// Hello world in Go

package main
import "fmt"

func main() {
 fmt.Printf("Hello World\n")
}
```

---

HTML
------

{% note 'fa-brands fa-html5' modern %}
HTML的全称为超文本标记语言，是一种标记语言。
{% endnote %}

```
<HTML>
    <!-- Hello World in HTML -->
    <HEAD>
        <TITLE>Hello World!</TITLE>
    </HEAD>
    <BODY>
        Hello World!
    </BODY>
</HTML>
```

---

MATLAB
------

{% note 'fa-solid fa-code' modern %}
MATLAB是美国MathWorks公司出品的商业数学软件，用于数据分析、无线通信、深度学习、图像处理与计算机视觉、信号处理、量化金融与风险管理、机器人，控制系统等领域。
{% endnote %}

```
% Hello World in MATLAB.

disp('Hello World');
```

---

Node.js
------

{% note 'fa-brands fa-node' modern %}
与其说是一种语言（使用的语言是JavaScript），不如说是一种运行时环境，它可以在服务器而不是浏览器上运行JavaScript。目的是证明异步编程对于现代多核CPU更好。
{% endnote %}

```
/* Hello world in Node.js */

var sys = require('sys');
sys.puts('Hello World');
```

---

RUBY
------

{% note 'fa-solid fa-code' modern %}
旨在成为一种高效有趣的语言来使用，强调人的需求远高于计算机的需求。Rails Web框架是由Ruby编写的，对Web框架设计产生了巨大影响。Ruby仍然是用于创建网站的流行语言。
{% endnote %}

```
puts 'Hello World!'
```

---

Scratch
------

{% note 'fa-solid fa-code' modern %}
一种视觉编程语言，旨在让孩子通过编程来学习技能。适合5-7岁的孩子使用。
全世界数以百万计的学校都使用这两种语言。
{% endnote %}

```
say Hello, World!
```

---

Swift
------

{% note 'fa-brands fa-swift' modern %}
苹果公司开发编程语言，正在推广并替代Objective-C在其手机平台上使用。
{% endnote %}

```
println("Hello, world!")
```

---

Perl
------

{% note 'fa-solid fa-code' modern %}
Perl在文本处理方面非常强大。在动态网站的早期创建网站的一种流行选择。
{% endnote %}

```
print "Hello, World!\n";
```

---

PHP
------

{% note 'fa-brands fa-php' modern %}
PHP是用于构建网站后端的最流行的语言。
{% endnote %}

```
<?php echo "Hello, World";
```

---

BASH (UNIX SHELL)
------

{% note 'fa-solid fa-code' modern %}
用于在命令行与Linux和Unix系统进行交互和管理的脚本语言。
{% endnote %}

```
#!/bin/bash
STR="Hello World!"
echo $STR
```

---

BASIC
------

{% note 'fa-solid fa-code' modern %}
Basic于1964年首次发布，并在80年代初达到鼎盛时期。当时计算机开始进入小型办公室和家庭，那时候大多数的计算机都会预装某些版本的BASIC。
Basic易于学习并小巧的特点在当时的硬件上还是非常理想的。
{% endnote %}

```
10 REM Hello World in BASIC
20 PRINT "Hello World!"
```

---

PASCAL
------

{% note 'fa-solid fa-code' modern %}
80年代和90年代流行的语言，特别是用于编程教学的语言。它发生了很大的变化，并且还是Delphi RAD工具集中使用的语言。
{% endnote %}

```
program HelloWorld(output);
begin
  Write('Hello, world!')
end.
```

---

FORTRAN
------

{% note 'fa-solid fa-code' modern %}
它创建于1950年代，可在大型计算机上运行，​​非常适合数字和科学工作。它已成为当今仍在使用的科学界的标准。
{% endnote %}

```
program helloworld
     print *, "Hello world!"
end program helloworld
```

---

COBOL
------

{% note 'fa-solid fa-code' modern %}
在大型机计算时代曾经非常流行。现在它正在消失，向那个时代致敬。
{% endnote %}

```
* Hello World in COBOL

*****************************
IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO.
ENVIRONMENT DIVISION.
DATA DIVISION.
PROCEDURE DIVISION.
MAIN SECTION.
DISPLAY "Hello World!"
STOP RUN.
****************************
```

---

{% flink %}
- class_name: 参考文献
  link_list:
    - name: 百度百科
      link: https://baike.baidu.com/item/hello%20world/85501
      avatar: https://www.baidu.com/img/flexible/logo/pc/result.png
      descr: 百度一下 你就知道
    - name: 知乎
      link: https://zhuanlan.zhihu.com/p/335285070
      avatar: https://pic1.zhimg.com/v2-b5e4fe8f22096e9e84c5eb58885f448d_l.jpg?source=78e73102
      descr: 有问题 就会有答案
{% endflink %}

---