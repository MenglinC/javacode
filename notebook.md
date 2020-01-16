参考书目《core Java Volume I-Fundamentals》10th edition(Cay S. Horstmann writed)


写在前面：学习一门程序语言，就像认识一个人，习惯一种表达方式，我也想通过与Java的相处过程中，了解Java的一些“性格特点”，与之成为朋友。

![Javaimage](https://ask.qcloudimg.com/http-save/yehe-1510914/0oevnu9ij1.jpeg?imageView2/2/w/1620)


第一章 Java语言设计概述

一、Java语言的特点

1.简单性2.面向对象3.分布式4.健壮性5.安全性6.体系结构中立7.可移植性8.解释型9.高性能10.多线程11.动态性
（这些特点我暂时还没法理解，说明我之前学的实际上是很浅的）

第二章 Java程序设计环境

第三章 Java的基本程序设计结构

一、对于第一个简单的Java应用程序的解剖

```java

public class FirstSample {

	public static void main(String[] args) {
		
		System.out.println("hello world!");
	}
	
}
```


/*
（1）关键词public
是访问修饰符，用于控制程序的其他部分对这串代码的访问级别。
（2）关键词class
加载程序编辑的容器
（3）类名FristSample
命名规范：
大写字母开头，若由多个单词组成，则每个单词的第一个字母必须大写。不能使用Java保留字。
（4）main方法
Java虚拟机将从指定类的main方法开始执行，因此有效的类的源文件中必须包含一个main方法。
（5）System.out.println()
System.out是一个对象，println是对象中的一个方法，点号（.）用于调用方法。这行指令调用了对象中的println方法，并将字符串作为参数传递给它。
这个方法将字符串参数显示在控制台上。

*/

二、Java注释格式
>>>
1. // 注释单行
2. /* */ 注释整段
3. /** */注释生成文档

三、Java数据类型

1.整型

类型|存储需求|取值范围
-|-|-
int|4字节|-2147483648~2147483647
short|2字节|-32768~32767
long|8字节|-9223372036854775808~9223372036854775807
byte|1字节|-128~127



