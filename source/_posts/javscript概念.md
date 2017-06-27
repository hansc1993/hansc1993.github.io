---
title: javascript概念
date: 2017-02-14 22:58:45
categories:
- javascript
tags:
- javacript
---
### javascript分为三部分:

#### ECMAScript:
javascript语言的**核心**部分,独立于浏览器 之外,可以在其他环境中使用

#### DOM:
Document Object Model
**文档对象模型**,提供了一种与HTML,XML文档交互的方式

``` javascript
    function test(a,b) {
        var a = 0;
        console.log(b);
    }
```

#### BOM:
Browser Object Model
**浏览器对象模型**,提供了一个与浏览器环境有关的对象集合
<!--more-->
### js简介:
javascript是**弱类型**语言,**基于对象**和**事件驱动**的脚本语言,应用在客户端(Node已经可以应用在服务器端)
js只需**解释就可以执行**,java需要先编译成字节码文件再执行

### 特点:
- **交互性**
- **安全性(不能访问本地硬盘)**
- **跨平台性**

### 编译型语言:
一次性把代码转换成cpu能看懂的语言,一行一行执行解释(**速度快**)

### 解释型语言:
一行一行解析,解析一行执行一行

### script标签属性:
- async
**异步**,多人同时做多件事情,**立即异步下载js**,不影响页面其他操作,但**js下载完毕后立即执行**
- sync
**同步**,一个人有序做多件事情
- defer
**异步**,脚本延迟到**文档完全被解析和显示后再执行**,只有外部脚本可以用
<!--more-->