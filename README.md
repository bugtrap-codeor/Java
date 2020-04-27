# 零基础Java学习，GeeK

## 学习内容

### 1.Java 语言核心语法2.环境搭建和工具使用3.编程语言基础4.编程语言和概念难点解析5.常用库（工具箱）6.面向对象的思想7.各种大小练兵的例子8.做出一个小游戏

环境变量配置：JAVA_HOME:jdk目录、
PATH：jdk的bin目录

检验环境命令：java -version版本、javac 编译...

### HelloWorld.java编写

```java
//javac HelloWorld.java编译命令、java HelloWorld运行、public class—告诉Java类名要与代码文件名一致、大括号内是类的内容
public class HelloWorld{//·类class、·HelloWorld是类名
    public statc void main(String[] args){//main 方法的定义。告诉Java这是程序入口，也就是程序开始执行的地方，大括号内是方法的内容，又称方法体（method body)、main 方法最为特殊的一点是，它是Java程序的入口。
        System.out.println("HelloWorld!");//·System.out.println是Java提供的内置功能，可以将内容输出、小括号里的内容是参数（parameter）、没有参数的情况下，System.out.printin（)会输出一行空行。
    }
}
//class 后面的名字是类名、类名必须与源文件的文件名相同，文件名后缀必须是小写的java、main 方法是Java程序执行的入口
```

基本数据类型—int：int用来表示一个整数，取值范围在-2^31~2^31-1即-2147483648~2147483647

#### 关键字（key word)和标识符(dertifier)

标示符：
    ·由大小写英文字符，数字和下划线_组成的，区分大小写的，不以数字开头的文字。
    ·可以用作Java中的各种东西的名字，比如类名，方法名等。
    ·标示符是区分大小写的。
    关键字是Java语法的保留字，不能用来做名字。
    我们接触到的关键字：public、class、static、void、int
