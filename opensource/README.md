# 开源项目

> Go 语言开源项目，主要分享 Go 语言入门级、Star 数较高的开源项目。

### [聊天机器人 - Chatbot](https://github.com/kevwan/chatbot)

一个用 Go 语言写的聊天机器人，通过已知对话数据集快速生成回答的 Go 问答引擎。

![chatbot](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/chatbot.png)

### [Go 辅助工具库 - goutil](https://github.com/gookit/goutil)

地址：
Go 的一些工具函数，格式化，特殊处理、常用信息获取等等收集、实现和整理，包含：

- arrutil array/slice 相关操作的函数工具包
- dump 简单的变量打印工具，打印 slice, map 会自动换行显示每个元素，同时会显示打印调用位置
- cliutil CLI 的一些工具函数包
- envutil ENV 信息获取判断工具包
- fmtutil format data tool
- fsutil 文件系统操作相关的工具函数包
- jsonutil JSON util
- maputil map 相关操作的函数工具包
- mathutil int/number 相关操作的函数工具包
- strutil string 相关操作的函数工具包
- sysutil system 相关操作的函数工具包
- testutil test help 相关操作的函数工具包

### [分布式事务管理器 - dtm](https://github.com/yedf/dtm)

DTM 是首款 golang 的开源分布事务管理器，优雅的解决了幂等、空补偿、悬挂等分布式事务难题。提供了简单易用、高性能、易水平扩展的分布式事务解决方案。

![dtm](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/dtm.png)

### [日期时间处理库 - carbon](https://github.com/golang-module/carbon)

carbon 是一个轻量级、语义化、对开发者友好的 Golang 时间处理库，支持链式调用和 gorm、xorm、zorm 等主流 orm。

### [灵活的爬虫系统 - digger](https://github.com/hetianyi/digger)

Digger 是用纯 Golang 开发的配置式分布式跨平台爬虫系统，支持使用 Javascript 编写插件来实现各种你想要达到的目标。Digger 及相关组件能够以极低的资源开销运行在各种廉价服务器和开发板上，如树莓派。 Digger 没有复杂的依赖，部署十分简单，支持 Linux 和 Windows 平台，目前支持的 CPU 架构有：amd64, arm, arm64。

![digger](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/digger.png)

### [企业微信 SCRM - OpenSCRM](https://github.com/openscrm/api-server)

OpenSCRM 是一套基于 Go 和 React 的超高质量企业微信私域流量管理系统。

![openscrm](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/openscrm.png)

### [网络爬虫 - gospider](https://github.com/jaeles-project/gospider)

Gospider 是一款运行速度非常快的 Web 爬虫程序，采用 Go 语言开发。其功能介绍包含：

1.  快速 Web 资源爬取
2.  爆破与解析 sitemap.xml
3.  解析 robots.txt
4.  生成和验证来自 JavaScript 文件的链接
5.  链接搜索工具
6.  根据响应源搜索 AWS-S3
7.  根据响应源搜索子域名
8.  从 Wayback Machine, Common Crawl, Virus Total, Alien Vault 获取 URL 资源
9.  格式化输出，可配合 Grep 使用
10. 支持 Burp 输入
11. 支持并行爬取多个站点
12. 随机移动端/Web User-Agent

### [分布式爬虫管理平台 - crawlab](https://github.com/crawlab-team/crawlab)

go 语言分布式爬虫管理平台，支持多种编程语言及框架，诸如 Python、NodeJS、Go、Java、PHP 等。

![crawlab](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/crawlab.png)

### [高性能网络库 - gnet](https://github.com/panjf2000/gnet)

gnet 是一个高性能、轻量级、非阻塞的事件驱动 Go 网络框架，也是性能最高的第三方 Go 语言开源网络库，且应用广泛，目前已经在腾讯、腾讯游戏、爱奇艺、百度、小米等大型互联网公司的生产环境上部署运行，经过大厂们的线上流量考验，gnet 在稳定性方面是有保障的。

![gnet](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/gnet.png)

### [静态网站生成器 - hugo](https://github.com/gohugoio/hugo)

Go 语言的静态网站生成器。静态网站生成器就是在本地把内容文件生成静态网页（HTML+CSS），然后把生成好的页面上传到服务器的工具。这种工具能够帮你轻松且快速地上线网站，而用户仅需选择喜欢的主题，便可以专注于内容创作。Hugo 作为最流行的静态网站生成器之一，拥有丰富的插件和主题，就算没有编程基础也能帮你快速制作出满意的博客或者网站。

![hugo](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/hugo.png)

### [高性能协程池 - Ants](https://github.com/panjf2000/ants)

Ants源码不到1K行，是一个广泛使用的goroutine池，可以有效控制协程数量，防止协程过多影响程序性能，实现了对大规模 goroutine 的调度管理、goroutine 复用，允许使用者在开发并发程序的时候限制 goroutine 数量，复用资源，达到更高效执行任务的效果。

![ants](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/ants.png)

### [依赖注入框架 - wire](https://github.com/google/wire)

Wire是一种代码生成工具，它使用依赖项注入自动连接组件。组件之间的依赖关系在Wire中表示为函数参数，鼓励显式初始化而不是全局变量。由于Wire在没有运行时状态或反射的情况下运行，因此编写用于Wire的代码即使对于手工编写的初始化也很有用。

### [定时任务 - cron](https://github.com/robfig/cron)

Linux中的crontab大家不陌生，go语言版的cron就是一个用于管理定时任务的库，cron库支持5个空格分隔的域来表示时间。

![cron](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/cron.png)

### [即时通讯IM - Open-IM-Server](https://github.com/OpenIMSDK/Open-IM-Server)

OpenIM：由前微信技术专家打造的基于 Go 实现的即时通讯（IM）项目，从服务端到客户端SDK开源即时通讯（IM）整体解决方案，可以轻松替代第三方IM云服务，打造具备聊天、社交功能的app。

![openIM](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/openIM.png)

### [LeetCode-Go](https://github.com/halfrost/LeetCode-Go)

Go语言版的LeetCode解题，100%测试覆盖率，运行时优于100%，如果你想用go语言来刷leetcode的话，必荐。

![leetGo](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/leetGo.png)