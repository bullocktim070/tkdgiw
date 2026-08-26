最新前沿技术资讯

一、入门教程｜Getting Started
原标题：方案设计：高可用Redis集群架构选型对比
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.9lbtsr.asia/arts/231729.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.9lbtsr.asia/arts/569541.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.9lbtsr.asia/arts/122182.Doc

原标题：部署实践：容器优雅停机配置处理信号
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.9lbtsr.asia/arts/628690.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.9lbtsr.asia/arts/090565.Doc

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.9lbtsr.asia/arts/976816.Doc

原标题：vite 项目配置与构建提速技巧
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.9lbtsr.asia/arts/807931.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.9lbtsr.asia/arts/527472.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.9lbtsr.asia/arts/490986.Doc

原标题：零基础理解版本控制核心概念与工作流
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.9lbtsr.asia/arts/023420.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.9lbtsr.asia/arts/900522.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.9lbtsr.asia/arts/523687.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.9lbtsr.asia/arts/895076.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.9lbtsr.asia/arts/941952.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.9lbtsr.asia/arts/674661.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.9lbtsr.asia/arts/045096.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.9lbtsr.asia/arts/782495.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.9lbtsr.asia/arts/991962.Doc

原标题：eslint prettier 代码规范落地
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.9lbtsr.asia/arts/233257.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.9lbtsr.asia/arts/048303.Doc

原标题：Spring 事务传播机制配置生效
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.9lbtsr.asia/arts/004768.Doc

原标题：数据库事务 ACID 原理讲解
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.9lbtsr.asia/arts/089489.Doc

原标题：项目目录结构规范化最佳实践
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.9lbtsr.asia/arts/485491.Doc

原标题：golang 系统设计分布式任务调度
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.9lbtsr.asia/arts/995426.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.9lbtsr.asia/arts/079423.Doc

原标题：golang 系统设计分布式会话方案对比
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.9lbtsr.asia/arts/084049.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.9lbtsr.asia/arts/070249.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.9lbtsr.asia/arts/869031.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.9lbtsr.asia/arts/092137.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.9lbtsr.asia/arts/611909.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.9lbtsr.asia/arts/718651.Doc

原标题：开源源码阅读拆解学习思路
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.9lbtsr.asia/arts/459794.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.9lbtsr.asia/arts/219132.Doc

原标题：超大数据集分页性能优化方案
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.9lbtsr.asia/arts/278704.Doc

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.9lbtsr.asia/arts/861366.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.9lbtsr.asia/arts/301584.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.9lbtsr.asia/arts/293878.Doc

原标题：golang 简易埋点日志上报实现
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.9lbtsr.asia/arts/714069.Doc

原标题：Architecture：日志、监控、告警整套可观测架构
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.9lbtsr.asia/arts/497770.Doc

原标题：定时任务周期调度 demo 开发
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.9lbtsr.asia/arts/389433.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计告警规则阈值设置方法论
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.9lbtsr.asia/arts/811914.Doc

原标题：express 中间件开发业务实践
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.9lbtsr.asia/arts/728188.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.9lbtsr.asia/arts/630636.Doc

原标题：nodejs http 服务性能调优实战
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.9lbtsr.asia/arts/558896.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.9lbtsr.asia/arts/110626.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.9lbtsr.asia/arts/857588.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.9lbtsr.asia/arts/309114.Doc

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.9lbtsr.asia/arts/312406.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.9lbtsr.asia/arts/304549.Doc

原标题：分布式任务调度集群原型开发
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.9lbtsr.asia/arts/121279.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.9lbtsr.asia/arts/071395.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.9lbtsr.asia/arts/655767.Doc

原标题：golang redis 主从复制哨兵原理
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.9lbtsr.asia/arts/195011.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.9lbtsr.asia/arts/532400.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.9lbtsr.asia/arts/585914.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.9lbtsr.asia/arts/129062.Doc

原标题：手写简易 ORM 理解对象映射
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.9lbtsr.asia/arts/423535.Doc

原标题：nodejs 日志轮转生产环境配置
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.9lbtsr.asia/arts/265354.Doc

原标题：零基础理解幂等性基础概念与场景
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.9lbtsr.asia/arts/674669.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.9lbtsr.asia/arts/497627.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.9lbtsr.asia/arts/590007.Doc

原标题：golang http grpc 全链路埋点示例
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.9lbtsr.asia/arts/414282.Doc

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.9lbtsr.asia/arts/459214.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.9lbtsr.asia/arts/908955.Doc

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.9lbtsr.asia/arts/804688.Doc

原标题：golang 静态文件服务搭建教程
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.9lbtsr.asia/arts/293544.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.9lbtsr.asia/arts/855747.Doc

原标题：golang http 代理客户端配置
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.9lbtsr.asia/arts/839140.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.9lbtsr.asia/arts/687034.Doc

原标题：git rebase 整理提交历史实操
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.9lbtsr.asia/arts/317067.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.9lbtsr.asia/arts/481441.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.9lbtsr.asia/arts/074758.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://wiki.9lbtsr.asia/arts/555584.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.9lbtsr.asia/arts/317328.Doc

原标题：Debug日志：生产环境偶发空指针异常排查
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.9lbtsr.asia/arts/631903.Doc

原标题：golang git 提交信息规范校验
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.9lbtsr.asia/arts/927011.Doc

原标题：方案对比：单体、微服务、模块化单体取舍
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.9lbtsr.asia/arts/440699.Doc

原标题：golang goroutine 协程基础实操
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.9lbtsr.asia/arts/529245.Doc

原标题：golang k8s devops 流水线简单思路
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.9lbtsr.asia/arts/959796.Doc

原标题：跨平台换行符统一异常修复
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.9lbtsr.asia/arts/823066.Doc

三、实战开发｜Practice
原标题：依赖安装失败全方位排错
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.9lbtsr.asia/arts/412870.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.9lbtsr.asia/arts/015336.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.9lbtsr.asia/arts/830955.Doc

原标题：nodejs 中间件模式原理剖析
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.9lbtsr.asia/arts/481185.Doc

原标题：前端打包分包加载提速方案
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.9lbtsr.asia/arts/579426.Doc

原标题：数据库连接池参数调优
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.9lbtsr.asia/arts/870927.Doc

原标题：日志输出规范防止磁盘爆满
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.9lbtsr.asia/arts/014460.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.9lbtsr.asia/arts/905927.Doc

原标题：定时任务重复执行分布式锁
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.9lbtsr.asia/arts/225032.Doc

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.9lbtsr.asia/arts/453230.Doc

原标题：golang 系统设计文件存储选型对比
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.9lbtsr.asia/arts/460251.Doc

原标题：前端防抖节流高频事件处理
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.9lbtsr.asia/arts/070563.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.9lbtsr.asia/arts/235359.Doc

原标题：golang redis 锁超时业务处理
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.9lbtsr.asia/arts/592199.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.9lbtsr.asia/arts/127132.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.9lbtsr.asia/arts/292228.Doc

原标题：golang redis 布隆过滤器安装使用
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.9lbtsr.asia/arts/510579.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.9lbtsr.asia/arts/044470.Doc

原标题：nodejs 流处理大文件不占内存
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.9lbtsr.asia/arts/190779.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.9lbtsr.asia/arts/115994.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.9lbtsr.asia/arts/575509.Doc

原标题：golang 优雅处理 http 超时设置
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.9lbtsr.asia/arts/530112.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.9lbtsr.asia/arts/895967.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.9lbtsr.asia/arts/968024.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.9lbtsr.asia/arts/234797.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.9lbtsr.asia/arts/602452.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.9lbtsr.asia/arts/591820.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.9lbtsr.asia/arts/925174.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.9lbtsr.asia/arts/279889.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.9lbtsr.asia/arts/209467.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.9lbtsr.asia/arts/383066.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.9lbtsr.asia/arts/298168.Doc

原标题：golang 配置文件多环境加载
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.9lbtsr.asia/arts/192974.Doc

原标题：golang docker compose 完整语法
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.9lbtsr.asia/arts/423003.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.9lbtsr.asia/arts/806227.Doc

原标题：golang 分布式锁防死锁处理
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.9lbtsr.asia/arts/555211.Doc

原标题：从零搭建简单的健康检查接口示例
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.9lbtsr.asia/arts/116145.Doc

原标题：Architecture：配置中心架构，动态配置设计思路
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.9lbtsr.asia/arts/487302.Doc

原标题：react 状态管理方案选型对比
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.9lbtsr.asia/arts/292586.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.9lbtsr.asia/arts/691063.Doc

四、架构设计｜Architecture
原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.9lbtsr.asia/arts/465708.Doc

原标题：Nginx 缓冲区调优大文件上传
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.9lbtsr.asia/arts/677702.Doc

原标题：golang 速率限制令牌桶实现
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.9lbtsr.asia/arts/141423.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.9lbtsr.asia/arts/029223.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.9lbtsr.asia/arts/232171.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.9lbtsr.asia/arts/317598.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.9lbtsr.asia/arts/477779.Doc

原标题：浏览器本地存储安全使用技巧
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.9lbtsr.asia/arts/489565.Doc

原标题：数据库死锁成因规避方案
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.9lbtsr.asia/arts/525363.Doc

原标题：golang alertmanager 钉钉告警推送
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.9lbtsr.asia/arts/740407.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.9lbtsr.asia/arts/789210.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.9lbtsr.asia/arts/596005.Doc

原标题：golang mongodb 聚合管道实操案例
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.9lbtsr.asia/arts/140256.Doc

原标题：css 变量主题切换方案实现
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.9lbtsr.asia/arts/269665.Doc

原标题：前端权限路由动态生成实现
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.9lbtsr.asia/arts/580000.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.9lbtsr.asia/arts/879984.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.9lbtsr.asia/arts/134078.Doc

原标题：手写简易 RPC 服务通信原型
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.9lbtsr.asia/arts/529181.Doc

?
