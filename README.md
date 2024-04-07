## Unique 0.1.0 (Unique Programming Language)
Unique编程语言是我们写的新代码语法简化比较好，再用这样行吧。为SourceSpace工作室编写代码准备的编程语言。

## Unique 代码语法
```kt
catalog <hello>
directory <hello>
// dir_tree <hello>
// Test println Hello World! ;
// ? System.out.println
import <System.out>
fun main () {
    var text = "New Text?"
    println("Hello World!")
}
```
## 变量整形语法
```kt
catalog <hello>
directory <hello>
// dir_tree <hello>
// System.out.println
import <System.out>
import <util>
// val integer = 5
fun main () {
    val integer = 5
    println("Hello World!")
    println("%d", integer)
}
```








# 如何安装？
1.默认您位于 `Unique` 目录中，并且您的计算机有 `Make` (或者mingw32-make)。

## 1.安装Unique编译器和Unique虚拟机。
1. 使用 `make` 或 `mingw32-make` 安装。
2. 编译器是 `/UCM/build/quec` , 虚拟机是 `/UVM/build/que` 。
3. 我建议设置环境变量之后使用 `quec (文件名)` 运行编译器，
   使用 `que (字节码文件名)` 运行虚拟机。

## 2.尝试编译Unique代码。
1. 在 `./testbench/test1` 中有一个名为 `pro1.que` 的Unique代码文件。
2. `quec ./testbench/test1/pro1.que` 进行编译。
3. `que pro1` 执行Unique字节码。

## 更多语言
1. [中文简体](./doc/README_CN.md)
2. 如果您想支持更多的语言，请与我们联系。

## 更多信息
1. [updateLog](./doc/updateLog.md)
2. [grammar](./doc/garmmar.md)

## 联系
1. QQ : 3572113478
2. e-mail : Kkasi2007@outlook.com
