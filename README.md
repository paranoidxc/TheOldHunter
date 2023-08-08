# TheOldHunter CLI-HTTP-SERVER-WITH-FRAMEWORK

** 实现一个基于 cli 常驻内存模式的 最小化 http 带个人 orm 和 lib 的服务框架 **

** 本仓库用于展示目的 暂时只更新 README.md 中的 todo list 字面意思 实际代码暂不会更新到仓库中 **

Usage:
- php >= 7.1
- 编译php configure --enable-pcntl --enable-sockets
- 启动服务 php server_for_github.php
- 浏览器打开
  - 127.0.0.1:9000/
  - 127.0.0.1:9000/a.php
  - 127.0.0.1:9000/b.php
  - 127.0.0.1:9000/c.php

Todo List:
- [x] 守护进程模式运行
- [x] 监控子进程
- [x] 多进程模式
- [ ] IO复用
  - [x] Select 模式
  - [ ] EPOLL 模式
- [x] 支持 HTTP 协议
  - [x] POST
  - [x] GET
- [ ] 支持 HTTPS 协议
- [x] 代码重构成面向对象模式
- [ ] WEB 框架
- [x] 自动热更新
  - [x] fswatch
  - [x] inotify
- [x] TINY LOG
