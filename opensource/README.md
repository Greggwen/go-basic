# 开源项目

> Go 语言开源项目，主要分享 Go 语言入门级、Star 数较高的开源项目。

|  |  |
| ---- | ---- | 
|[聊天机器人 - Chatbot](#聊天机器人---chatbot)  | [Go 辅助工具库 - goutil](#go-辅助工具库---goutil) |
| [分布式事务管理器 - dtm](#分布式事务管理器---dtm)| [日期时间处理库 - carbon](#日期时间处理库---carbon) | 
| [灵活的爬虫系统 - digger](#灵活的爬虫系统---digger) | [企业微信 SCRM - OpenSCRM](#企业微信-scrm---openscrm) |
| [网络爬虫 - gospider](#网络爬虫---gospider) | [分布式爬虫管理平台 - crawlab](#分布式爬虫管理平台---crawlab) |
| [高性能网络库 - gnet](#高性能网络库---gnet) | [静态网站生成器 - hugo](#静态网站生成器---hugo) |
| [高性能协程池 - Ants](#高性能协程池---ants) | [依赖注入框架 - wire](#依赖注入框架---wire) |
| [定时任务 - cron](#定时任务---cron) | [即时通讯IM - Open-IM-Server](#即时通讯im---open-im-server) |
| [LeetCode-Go](#leetcode-go) | [主机管理工具 - natpass](#主机管理工具---natpass) |
| [轻量原生跨平台 - go-cqhttp](#轻量原生跨平台---go-cqhttp) | [开源社区系统 - bbs-go](#开源社区系统---bbs-go) |
| [API框架 - go-gin-api](#api框架---go-gin-api) | [3D软件渲染器 - Tetra3d](#3d软件渲染器----tetra3d) |
| [开源SQL审计平台 - Yearning](#开源sql审计平台---yearning) | [国密加密 - gmsm](#国密加密---gmsm) |
| [即时通讯 - chat](#即时通讯---chat) | [企业级监控 - Nightingale](#企业级监控---Nightingale) |
| [Redis服务器 - godis](Redis服务器---godis) | |

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

### [主机管理工具 - natpass](https://github.com/lwch/natpass)

一款主机管理工具，支持shell管理，支持远程桌面管理。其功能与特性：
1.  较小的内存占用（约20M左右）
2.  支持tls安全连接
3.  支持多路异步IO
4.  支持虚拟链路层
5.  支持链路和终端会话监控
6.  支持web shell
7.  支持web vnc
8.  支持多种操作系统
9.  protobuf数据编码

![natpass](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/natpass.png)

### [轻量原生跨平台 - go-cqhttp](https://github.com/Mrs4s/go-cqhttp)

cqhttp的golang实现，轻量、原生跨平台。go-cqhttp 兼容 [OneBot-v11](https://github.com/botuniverse/onebot-11) 绝大多数内容，并在其基础上做了一些扩展。基于 [Mirai](https://github.com/mamoe/mirai) 以及 [MiraiGo](https://github.com/Mrs4s/MiraiGo) 的 [OneBot](https://github.com/howmanybots/onebot/blob/master/README.md) Golang 原生实现。

### [开源社区系统 - bbs-go](https://github.com/mlogclub/bbs-go)

bbs-go是一个使用Go语言搭建的开源社区系统，采用前后端分离技术，Go语言提供api进行数据支撑，用户界面使用Nuxt.js进行渲染，后台界面基于element-ui。如果你正在学习Go语言，或者考虑转Go语言的Phper/Javaer...那么该项目对你有的学习会有很大的帮助。

![bbsgo](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/bbsgo.png)


### [API框架 - go-gin-api](https://github.com/xinliangnote/go-gin-api)

基于 Gin 进行模块化设计的 API 框架，封装了常用功能，使用简单，致力于进行快速的业务研发。比如，支持 cors 跨域、jwt 签名验证、zap 日志收集、panic 异常捕获、trace 链路追踪、prometheus 监控指标、swagger 文档生成、viper 配置文件解析、gorm 数据库组件、gormgen 代码生成工具、graphql 查询语言、errno 统一定义错误码、gRPC 的使用、cron 定时任务 等等。

![ginapi](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/ginapi.png)

### [3D软件渲染器  - Tetra3d](https://github.com/SolarLune/Tetra3d)

Tetra3D是一款3D混合软件/硬件渲染器，主要用于视频游戏，使用Ebiten编写。与OpenGL或Vulkan这样的专业3D渲染系统相比，它速度慢、有缺陷，但也很简陋，我喜欢它。Tetra3D主要在软件中实现，但使用GPU渲染三角形和深度测试（通过使用着色器比较和写入深度，并将结果合成到完成的纹理上）。可以关闭深度测试以提高性能，交换条件是不存在对象间交叉。


![tetra3d](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/tetra3d.gif)

### [开源SQL审计平台 - Yearning](https://github.com/cookieY/Yearning)

Go语言编写的一款高颜值、开源 SQL 审核平台，目前支持SQL查询、自动补全、智能提示、结果脱敏等，SQL审核、流程化工单、SQL语法检测等，基于Email和钉钉Webhook机器人工单推送。

![yearning](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/yearning.png)

### [国密加密 - gmsm](https://github.com/tjfoc/gmsm)

GM SM2/3/4 library based on Golang (基于Go语言的国密SM2/SM3/SM4算法库)。

-   SM2：国密椭圆网线算法库，支持Generate Key, Sign，Verify基础操作，支持加密和不加密的pem文件格式
-   SM3：国密Hash算法库，支持基础的sm3Sum操作，以及hash.Hash接口
-   SM4：国密分组密码算法库，支持Generate Key，Encrypt，Decrypt基础操作

![gmsm](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/gmsm.png)

### [即时通讯 - chat](https://github.com/tinode/chat)
这是一个开源的即时通讯软件，既然是即时通讯软件，学习的时候基本上无任何业务负担，可以专注地学习程序逻辑本身，服务端是Go语言写的。

![chat](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/chat.png)

### [企业级监控 - Nightingale](https://gitee.com/cnperl/Nightingale)

夜莺（Nightingale）是一个企业级监控解决方案，对云原生场景、传统物理机虚拟机场景，都有很好的支持。

![nightingale](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/nightingale.png)

### [Redis服务器 - godis](https://github.com/HDT3213/godis)

Godis 是一个用 Go 语言实现的 Redis 服务器。
关键功能:
-   支持 string, list, hash, set, sorted set 数据结构
-   自动过期功能(TTL)
-   发布订阅
-   地理位置
-   AOF 持久化及 AOF 重写
-   Multi 命令开启的事务具有原子性和隔离性. 若在执行过程中遇到错误, godis 会回滚已执行的命令
-   内置集群模式. 集群对客户端是透明的, 您可以像使用单机版 redis 一样使用 godis 集群
-   MSET, DEL 命令在集群模式下原子性执行
-   Rename, RenameNX 命令在集群模式下支持在同一个 slot 内执行
-   Multi 命令开启的事务在集群模式下支持在同一个 slot 内执行
-   并行引擎, 无需担心您的操作会阻塞整个服务器.

![godis](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/godis.png)
### [local-log4j-vuln-scanner](https://github.com/hillu/local-log4j-vuln-scanner)
这是一个简单的工具，可用于查找log4j 1的易受攻击实例。

![local-log4j-vuln-scanner](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/log4shell.png)

### [Apache Dubbo-go](https://github.com/apache/dubbo-go)
Apache Dubbo Go语言实现与gRPC/Dubbo生态互通，覆盖多种网络协议，包括：Triple、Dubbo、JSONRPC、gRPC、HTTP、HTTP2等。支持以下功能：
- 注册中心:支持 Nacos（阿里开源） 、Zookeeper、ETCD、Consul、Polaris-mesh（腾讯开源） 等服务注册中间件，并拥有可扩展能力。我们也会根据用户使用情况，进一步扩展出用户需要的实现。
- 配置中心开发者可以使用Nacos、Apollo（携程开源）、Zookeeper 进行框架/用户的配置的发布和拉取。
- 集群策略: Failover, Failfast, Failsafe/Failback, Available, Broadcast, Forking 等
- 负载均衡策略: 柔性服务, Random, RoundRobin, LeastActive, ConsistentHash 等
- 过滤器: Echo, Hystrix, Token, AccessLog, TpsLimiter, ExecuteLimit, Generic, Auth/Sign, Metrics, Tracing, Active, Seata, Sentinel 等
- 泛化调用
- 监控: Prometheus
- 链路追踪: Jaeger, Zipkin
- 路由器: Dubbo3 Router

![Dubbo-go](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/dubbo-go.png)

### [内网综合扫描工具 - fscan](https://github.com/shadow1ng/fscan)
fscan是一款内网综合扫描工具，方便一键自动化、全方位漏扫扫描。支持主机存活探测、端口扫描、常见服务的爆破、ms17010、redis批量写公钥、计划任务反弹shell、读取win网卡信息、web指纹识别、web漏洞扫描、netbios探测、域控识别等功能。

![fscan](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/fscan.png)

### [CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest)
「自选优选 IP / 过滤假墙」测试 Cloudflare CDN 延迟和速度，获取最快 IP (IPv4+IPv6)！这个项目的建立初衷是因为国外很多网站都在使用 Cloudflare CDN，但分配给中国内地访客的 IP 并不友好（延迟高、丢包多、速度慢）。而该项目主要就是解决这部分问题。

![CloudflareSpeedTest](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/cloudflarespeed.png)

### [内网穿透代理服务器 - nps](https://github.com/ehang-io/nps)
nps是一款轻量级、高性能、功能强大的内网穿透代理服务器。支持tcp、udp、socks5、http等几乎所有流量转发，可用来访问内网网站、本地支付接口调试、ssh访问、远程桌面，内网dns解析、内网socks5代理等等……，并带有功能强大的web管理端。

![nps](https://raw.githubusercontent.com/Greggwen/img-source/main/opensource/nps.png)





