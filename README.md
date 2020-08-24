<img src="GoOEngine.svg">

A simple Lua/Python script engine in C++.

一个简单的Lua/Python 脚本执行引擎.

### 期望的特性

* 能够通过`manager`轻松管理包依赖.
* 提供一个简便的执行脚本的方法, 并使用一个队列来处理脚本与对应的数据.
* 能够方便的与宿主进行数据交互与线程管理, 保证线程安全, 也提供随时启动/终止线程的方法.
* 通过解释器提供的`traceback`尝试修复一些常见小错误并重新尝试执行脚本, 以此来提供容错功能.

### 灵感来源

名称灵感来源于`World Of Goo`信息高速公路章节的容错系统, 以及`MuseDash`中的`Rabot 233`.