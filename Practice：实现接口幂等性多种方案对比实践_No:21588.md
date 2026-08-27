最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.zojwdsa.asia/blog/1898777.sHtMl

原标题：golang 系统设计压测环境隔离避免影响生产
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.zojwdsa.asia/blog/6018506.sHtMl

原标题：nodejs 单元测试 jest 实操教程
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.zojwdsa.asia/blog/3272616.sHtMl

原标题：Practice：实现限流之后友好业务返回处理
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://book.zojwdsa.asia/blog/8923220.sHtMl

原标题：Practice：实现文件监控自动重启开发服务工具
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://book.zojwdsa.asia/blog/4404013.sHtMl

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.zojwdsa.asia/blog/3801922.sHtMl

原标题：线上接口超时故障排查思路
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.zojwdsa.asia/blog/7132834.sHtMl

原标题：golang 系统设计分库分表扩容平滑迁移
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.zojwdsa.asia/blog/6117423.sHtMl

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.zojwdsa.asia/blog/2889495.sHtMl

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.zojwdsa.asia/blog/0585545.sHtMl

原标题：实践：多配置文件合并加载组件实现
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.zojwdsa.asia/blog/8202983.sHtMl

原标题：实战：搭建日志收集分析简易完整演示环境
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.zojwdsa.asia/blog/6094424.sHtMl

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.zojwdsa.asia/blog/7156787.sHtMl

原标题：Git LFS 大文件推送失败解决
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.zojwdsa.asia/blog/8617075.sHtMl

原标题：多环境配置中心灵活切换方案
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.zojwdsa.asia/blog/5686228.sHtMl

原标题：调优方案：服务实例扩容，水平扩展性能
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.zojwdsa.asia/blog/7408560.sHtMl

原标题：OOMKilled 容器被杀完整排查
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://book.zojwdsa.asia/blog/0972888.sHtMl

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.zojwdsa.asia/blog/0101679.sHtMl

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.zojwdsa.asia/blog/7092689.sHtMl

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.zojwdsa.asia/blog/5320352.sHtMl

原标题：gRPC 服务端客户端入门示例
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.zojwdsa.asia/blog/4558834.sHtMl

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.zojwdsa.asia/blog/3295742.sHtMl

原标题：DevOps：制品仓库管理二进制产物版本
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.zojwdsa.asia/blog/1203530.sHtMl

原标题：golang 系统设计 mq 消息丢失完整防护
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.zojwdsa.asia/blog/3783947.sHtMl

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.zojwdsa.asia/blog/6088200.sHtMl

原标题：golang k8s configmap secret 配置
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.zojwdsa.asia/blog/0307747.sHtMl

原标题：nodejs 全局异常捕获进程防护
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.zojwdsa.asia/blog/0451194.sHtMl

原标题：OpenSource：开源项目许可证License选型指南
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://book.zojwdsa.asia/blog/3359714.sHtMl

原标题：golang redis 主从复制哨兵原理
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.zojwdsa.asia/blog/1784842.sHtMl

原标题：golang redis 缓存更新策略讲解
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.zojwdsa.asia/blog/1316457.sHtMl

原标题：golang 分布式 ID 雪花算法实现
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.zojwdsa.asia/blog/3990567.sHtMl

原标题：GraphQL 接口查询优化实操
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://book.zojwdsa.asia/blog/3690076.sHtMl

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://book.zojwdsa.asia/blog/1791393.sHtMl

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://book.zojwdsa.asia/blog/4590553.sHtMl

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://book.zojwdsa.asia/blog/7574601.sHtMl

原标题：golang 系统设计 changelog 变更日志维护
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.zojwdsa.asia/blog/4653705.sHtMl

原标题：内存广播本地进程消息通知
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.zojwdsa.asia/blog/7802420.sHtMl

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.zojwdsa.asia/blog/4382197.sHtMl

原标题：golang 系统设计缓存预热脚本编写实操
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.zojwdsa.asia/blog/4016411.sHtMl

原标题：golang 系统设计开源版本发布 changelog 维护
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.zojwdsa.asia/blog/3854664.sHtMl


二、踩坑排错｜Troubleshooting
原标题：手写简易 MQ 理解消息存储消费
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.zojwdsa.asia/blog/6824476.sHtMl

原标题：golang 内存 pprof 定位内存泄漏
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.zojwdsa.asia/blog/3174194.sHtMl

原标题：golang 速率限制令牌桶实现
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.zojwdsa.asia/blog/2233197.sHtMl

原标题：Hands‑on：简易请求转发代理中间件实现
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.zojwdsa.asia/blog/2209094.sHtMl

原标题：缓存过期打散防止缓存雪崩
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://book.zojwdsa.asia/blog/5705589.sHtMl

原标题：golang redis zset 延时队列实现
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.zojwdsa.asia/blog/0893000.sHtMl

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://book.zojwdsa.asia/blog/7396044.sHtMl

原标题：Redis 大 key 拆分集群卡顿解决
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.zojwdsa.asia/blog/3821836.sHtMl

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://book.zojwdsa.asia/blog/4393850.sHtMl

原标题：golang 系统设计数据库慢请求排查流程
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.zojwdsa.asia/blog/6355782.sHtMl

原标题：golang redis zset 延时队列实现
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.zojwdsa.asia/blog/0041679.sHtMl

原标题：项目实践：MySQL读写分离本地模拟实践
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.zojwdsa.asia/blog/2328936.sHtMl

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.zojwdsa.asia/blog/4783673.sHtMl

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://book.zojwdsa.asia/blog/0561925.sHtMl

原标题：全局异常处理器接口返回统一
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.zojwdsa.asia/blog/9858548.sHtMl

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.zojwdsa.asia/blog/8882422.sHtMl

原标题：golang 系统设计联合索引设计避坑要点
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.zojwdsa.asia/blog/2702008.sHtMl

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.zojwdsa.asia/blog/0649374.sHtMl

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.zojwdsa.asia/blog/4188135.sHtMl

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.zojwdsa.asia/blog/5859536.sHtMl

原标题：项目实践：多环境配置管理组件设计与实现
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.zojwdsa.asia/blog/1457774.sHtMl

原标题：golang mysql json 字段查询使用
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.zojwdsa.asia/blog/2890893.sHtMl

原标题：设计思考：API网关和BFF职责边界划分
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.zojwdsa.asia/blog/1778801.sHtMl

原标题：OOMKilled 容器被杀完整排查
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.zojwdsa.asia/blog/8864505.sHtMl

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.zojwdsa.asia/blog/1450838.sHtMl

原标题：golang 系统设计缓存降级开关快速切库实现
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.zojwdsa.asia/blog/6827443.sHtMl

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://book.zojwdsa.asia/blog/4708218.sHtMl

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.zojwdsa.asia/blog/7986182.sHtMl

原标题：开发测试生产多环境配置区分
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.zojwdsa.asia/blog/1290379.sHtMl

原标题：程序预加载加快服务启动速度
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://book.zojwdsa.asia/blog/9976882.sHtMl

原标题：Git commit 钩子提交规范校验
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.zojwdsa.asia/blog/5707191.sHtMl

原标题：golang 雪花 id 重复问题排查
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.zojwdsa.asia/blog/6635285.sHtMl

原标题：golang 系统设计数据库连接池调优实践
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.zojwdsa.asia/blog/0715122.sHtMl

原标题：Hands‑on：简易配置中心本地原型实现
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.zojwdsa.asia/blog/1005390.sHtMl

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.zojwdsa.asia/blog/4531921.sHtMl

原标题：golang 系统设计 commit 提交规范约定
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.zojwdsa.asia/blog/7814148.sHtMl

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.zojwdsa.asia/blog/2843310.sHtMl

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://book.zojwdsa.asia/blog/9848602.sHtMl

原标题：数据库死锁成因规避方案
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.zojwdsa.asia/blog/8125949.sHtMl

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://book.zojwdsa.asia/blog/3341708.sHtMl

三、实战开发｜Practice
原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.zojwdsa.asia/blog/7024536.sHtMl

原标题：开源实践：开源项目本地调试构建排坑经验
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.zojwdsa.asia/blog/7034702.sHtMl

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.zojwdsa.asia/blog/5504693.sHtMl

原标题：golang 雪花 id 重复问题排查
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://book.zojwdsa.asia/blog/3505446.sHtMl

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.zojwdsa.asia/blog/1443301.sHtMl

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.zojwdsa.asia/blog/4197404.sHtMl

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.zojwdsa.asia/blog/6179306.sHtMl

原标题：操作系统内核版本适配服务
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://book.zojwdsa.asia/blog/9294478.sHtMl

原标题：SDK 版本兼容线上崩溃修复
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.zojwdsa.asia/blog/0961237.sHtMl

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.zojwdsa.asia/blog/6447075.sHtMl

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.zojwdsa.asia/blog/9655043.sHtMl

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.zojwdsa.asia/blog/3337903.sHtMl

原标题：golang 系统设计缓存一致性方案对比
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.zojwdsa.asia/blog/2530289.sHtMl

原标题：golang 系统设计本地缓存与分布式缓存
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.zojwdsa.asia/blog/7346865.sHtMl

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.zojwdsa.asia/blog/4645425.sHtMl

原标题：golang 结构体 json 序列化坑点
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.zojwdsa.asia/blog/6538668.sHtMl

原标题：缓存基础原理与简单代码实现
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://book.zojwdsa.asia/blog/4726842.sHtMl

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://book.zojwdsa.asia/blog/2564957.sHtMl

原标题：golang gorm 批量插入性能调优
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.zojwdsa.asia/blog/3776003.sHtMl

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.zojwdsa.asia/blog/0368099.sHtMl

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.zojwdsa.asia/blog/4042929.sHtMl

原标题：调试工具断点调试变量查看技巧
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.zojwdsa.asia/blog/6201221.sHtMl

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.zojwdsa.asia/blog/6126990.sHtMl

原标题：golang k8s service 服务暴露几种类型
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.zojwdsa.asia/blog/4048434.sHtMl

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.zojwdsa.asia/blog/3289996.sHtMl

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://book.zojwdsa.asia/blog/9823844.sHtMl

原标题：慢查询分析索引调优数据库实战
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://book.zojwdsa.asia/blog/7097242.sHtMl

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.zojwdsa.asia/blog/6114920.sHtMl

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.zojwdsa.asia/blog/5156149.sHtMl

原标题：CORS 跨域问题多种解决方案
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.zojwdsa.asia/blog/4797704.sHtMl

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://book.zojwdsa.asia/blog/6604093.sHtMl

原标题：实战：基于DockerCompose搭建本地开发栈
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.zojwdsa.asia/blog/3962388.sHtMl

原标题：golang mysql 行锁表锁场景区分
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.zojwdsa.asia/blog/4594396.sHtMl

原标题：数据库连接池参数调优
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.zojwdsa.asia/blog/9252660.sHtMl

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.zojwdsa.asia/blog/8825647.sHtMl

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.zojwdsa.asia/blog/3699369.sHtMl

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.zojwdsa.asia/blog/5755871.sHtMl

原标题：接口幂等性防重复请求实现
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://book.zojwdsa.asia/blog/9454570.sHtMl

原标题：批量数据处理脚本编写技巧
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://book.zojwdsa.asia/blog/4001848.sHtMl

原标题：Redis 分布式锁高并发安全实现
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.zojwdsa.asia/blog/5589556.sHtMl

四、架构设计｜Architecture
原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.zojwdsa.asia/blog/7993848.sHtMl

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.zojwdsa.asia/blog/8712886.sHtMl

原标题：避坑：版本升级之后项目直接无法启动
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.zojwdsa.asia/blog/1783793.sHtMl

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.zojwdsa.asia/blog/4094159.sHtMl

原标题：Security：业务操作审计日志安全留存
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.zojwdsa.asia/blog/0277069.sHtMl

原标题：golang kafka 消费者偏移量管理
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://book.zojwdsa.asia/blog/7064820.sHtMl

原标题：golang 协程泄露问题排查方法
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://book.zojwdsa.asia/blog/1674655.sHtMl

原标题：从零搭建本地数据库开发环境
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://book.zojwdsa.asia/blog/1855067.sHtMl

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.zojwdsa.asia/blog/4703707.sHtMl

原标题：golang 系统设计 json 解析性能优化实操
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://book.zojwdsa.asia/blog/6891553.sHtMl

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.zojwdsa.asia/blog/0635896.sHtMl

原标题：Docker 容器网络不通排查
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.zojwdsa.asia/blog/1448001.sHtMl

原标题：golang 系统设计分布式事务几种方案
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.zojwdsa.asia/blog/3692711.sHtMl

原标题：golang mysql 存储过程简单使用
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.zojwdsa.asia/blog/0186224.sHtMl

原标题：golang 系统设计 changelog 变更日志维护
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://book.zojwdsa.asia/blog/8704068.sHtMl

原标题：快速启动：本地运行开源项目排障清单
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.zojwdsa.asia/blog/3816826.sHtMl

原标题：golang 系统设计网络超时故障排查思路
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.zojwdsa.asia/blog/2706601.sHtMl

原标题：golang 接口限流中间件开发
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.zojwdsa.asia/blog/3634782.sHtMl

?
