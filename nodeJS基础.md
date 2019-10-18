# node.js 基础

## node 基本安装

- 用nvm 安装不同版本的node.js



## node REPL环境

- 不常用 



## 全局对象

- global

  类似浏览器javascript运行环境中的window

- progress

  - 用于获取当前Node进程信息，一般用于获取环境变量之类的信息
  - process.argv:   属性返回一个数组，其中包含当启动 Node.js 进程时传入的命令行参数（数组前两位一般没啥用）。
  - process.env: 属性返回包含用户环境的对象。
  - process.stdin:  属性返回连接到 `stdin` (fd `0`) 的流。
  - process.stdout: 属性返回连接到 `stdout` (fd `1`) 的流
    - console.log()  实现就是靠 process.stdout.write(‘hello world’)实现的

- console

  - Node中内置的console模块，提供操作控制台的输入输出功能，常见使用方式和浏览器端类似
  

## debugger
- 可以用debugger 打断点。
- vscode 直接打断点 + 配合vscode调试工具
- 