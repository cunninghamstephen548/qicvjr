最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计配置敏感信息加密存储
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.87s1od.asia/arts/085829.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.87s1od.asia/arts/386034.Doc

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.87s1od.asia/arts/590269.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.87s1od.asia/arts/538782.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.87s1od.asia/arts/530762.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.87s1od.asia/arts/490950.Doc

原标题：golang mysql 联合索引最左匹配
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.87s1od.asia/arts/129741.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.87s1od.asia/arts/552181.Doc

原标题：golang 系统设计大流量削峰处理方案
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.87s1od.asia/arts/144029.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.87s1od.asia/arts/487283.Doc

原标题：前端国际化多语言方案落地
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.87s1od.asia/arts/308927.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.87s1od.asia/arts/497181.Doc

原标题：GitHub Markdown 文档语法汇总
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.87s1od.asia/arts/425289.Doc

原标题：golang redis 位图用户签到统计
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.87s1od.asia/arts/452451.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.87s1od.asia/arts/823418.Doc

原标题：golang kafka 批量发送消费优化
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.87s1od.asia/arts/596952.Doc

原标题：golang 系统设计灰度发布实现思路
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.87s1od.asia/arts/905333.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.87s1od.asia/arts/948466.Doc

原标题：复盘总结：系统压测报告模板与分析思路
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://wiki.87s1od.asia/arts/271521.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.87s1od.asia/arts/153293.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://wiki.87s1od.asia/arts/460184.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.87s1od.asia/arts/608491.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.87s1od.asia/arts/189826.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.87s1od.asia/arts/237914.Doc

原标题：跨库查询性能优化处理
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.87s1od.asia/arts/319468.Doc

原标题：golang redis 集群 hash 槽讲解
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.87s1od.asia/arts/338925.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.87s1od.asia/arts/934625.Doc

原标题：项目构建脚本编译打包解析
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.87s1od.asia/arts/671163.Doc

原标题：golang 重试退避机制代码实现
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.87s1od.asia/arts/901910.Doc

原标题：GET POST 接口请求参数处理
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.87s1od.asia/arts/758188.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.87s1od.asia/arts/342451.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.87s1od.asia/arts/496574.Doc

原标题：系统文件描述符上限调大
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.87s1od.asia/arts/159985.Doc

原标题：Git 代码冲突正确处理方式
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.87s1od.asia/arts/222440.Doc

原标题：代码格式化工具团队统一风格
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.87s1od.asia/arts/810517.Doc

原标题：后端登录鉴权模块完整开发
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.87s1od.asia/arts/152224.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.87s1od.asia/arts/378887.Doc

原标题：css 变量主题切换方案实现
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.87s1od.asia/arts/202952.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.87s1od.asia/arts/508055.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.87s1od.asia/arts/975255.Doc


二、踩坑排错｜Troubleshooting
原标题：调优方案：CDN优化静态资源访问延迟
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.87s1od.asia/arts/615869.Doc

原标题：从零学习基础的接口请求与参数处理
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.87s1od.asia/arts/256106.Doc

原标题：golang 系统设计 README 开源文档模板
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.87s1od.asia/arts/048388.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.87s1od.asia/arts/394088.Doc

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.87s1od.asia/arts/190739.Doc

原标题：golang redis set 集合去重业务
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.87s1od.asia/arts/233210.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.87s1od.asia/arts/677060.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.87s1od.asia/arts/078451.Doc

原标题：golang docker compose 依赖启动顺序
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.87s1od.asia/arts/278247.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.87s1od.asia/arts/892681.Doc

原标题：动态定时任务业务调度实现
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.87s1od.asia/arts/126307.Doc

原标题：空指针异常判空容错处理
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.87s1od.asia/arts/946240.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.87s1od.asia/arts/379430.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.87s1od.asia/arts/438468.Doc

原标题：网络读取超时设置连接挂起防护
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.87s1od.asia/arts/074358.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.87s1od.asia/arts/830304.Doc

原标题：项目构建脚本编译打包解析
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.87s1od.asia/arts/599259.Doc

原标题：程序日志分级输出规范实践
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.87s1od.asia/arts/461736.Doc

原标题：golang redis 集群 hash 槽讲解
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.87s1od.asia/arts/275817.Doc

原标题：golang 系统设计代码安全审计简单思路
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.87s1od.asia/arts/683811.Doc

原标题：golang 系统设计序列化性能选型对比
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.87s1od.asia/arts/333399.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.87s1od.asia/arts/007841.Doc

原标题：多规则数据脱敏组件开发
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.87s1od.asia/arts/459141.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.87s1od.asia/arts/908407.Doc

原标题：批量数据处理脚本编写技巧
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.87s1od.asia/arts/901091.Doc

原标题：golang 开发环境快速搭建指南
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.87s1od.asia/arts/146147.Doc

原标题：调优方案：CDN优化静态资源访问延迟
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.87s1od.asia/arts/713228.Doc

原标题：前端图片懒加载性能优化
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.87s1od.asia/arts/466670.Doc

原标题：rebase 操作防止代码丢失
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.87s1od.asia/arts/643411.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.87s1od.asia/arts/523036.Doc

原标题：部署实践：DockerCompose管理多服务环境
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.87s1od.asia/arts/084252.Doc

原标题：新手向：项目目录结构规范与含义解析
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.87s1od.asia/arts/141667.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.87s1od.asia/arts/556947.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.87s1od.asia/arts/823136.Doc

原标题：express 中间件开发业务实践
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.87s1od.asia/arts/265851.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.87s1od.asia/arts/058008.Doc

原标题：快速入门日志打印与日志分级基础用法
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.87s1od.asia/arts/270872.Doc

原标题：golang gorm 批量插入性能调优
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.87s1od.asia/arts/537339.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.87s1od.asia/arts/018036.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.87s1od.asia/arts/566142.Doc

三、实战开发｜Practice
原标题：Git 混乱提交历史清理方法
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.87s1od.asia/arts/199893.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.87s1od.asia/arts/340836.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.87s1od.asia/arts/520614.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.87s1od.asia/arts/498007.Doc

原标题：编译打包产物依赖分析解读
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.87s1od.asia/arts/936099.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.87s1od.asia/arts/937732.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.87s1od.asia/arts/041903.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.87s1od.asia/arts/934995.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.87s1od.asia/arts/863666.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.87s1od.asia/arts/978071.Doc

原标题：golang 静态文件服务搭建教程
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.87s1od.asia/arts/569874.Doc

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.87s1od.asia/arts/572715.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.87s1od.asia/arts/267565.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.87s1od.asia/arts/118494.Doc

原标题：golang minio 存储桶权限管控配置
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.87s1od.asia/arts/437933.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.87s1od.asia/arts/460681.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.87s1od.asia/arts/827924.Doc

原标题：SourceMap 生成线上报错定位
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.87s1od.asia/arts/934777.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.87s1od.asia/arts/872965.Doc

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.87s1od.asia/arts/960844.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.87s1od.asia/arts/911461.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.87s1od.asia/arts/529277.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.87s1od.asia/arts/212860.Doc

原标题：vue3 组合式 API 业务开发实战
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.87s1od.asia/arts/299467.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.87s1od.asia/arts/080798.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.87s1od.asia/arts/355184.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.87s1od.asia/arts/520297.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.87s1od.asia/arts/781119.Doc

原标题：文件句柄上限调整上传随机失败
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.87s1od.asia/arts/383373.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.87s1od.asia/arts/011221.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.87s1od.asia/arts/296309.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.87s1od.asia/arts/899423.Doc

原标题：快速入门消息队列基础概念模型
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.87s1od.asia/arts/115448.Doc

原标题：golang html 模板渲染简单示例
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.87s1od.asia/arts/840635.Doc

原标题：CI 持续集成自动构建流程
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.87s1od.asia/arts/089852.Doc

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.87s1od.asia/arts/637583.Doc

原标题：golang url 参数编码处理方案
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.87s1od.asia/arts/353142.Doc

原标题：本地简易配置中心动态管理
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.87s1od.asia/arts/075916.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.87s1od.asia/arts/649172.Doc

原标题：部署实践：容器时区统一配置解决方案
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.87s1od.asia/arts/467764.Doc

四、架构设计｜Architecture
原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.87s1od.asia/arts/226775.Doc

原标题：golang 系统设计分布式配置中心思路
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.87s1od.asia/arts/886395.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.87s1od.asia/arts/399962.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.87s1od.asia/arts/486019.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.87s1od.asia/arts/031374.Doc

原标题：Hands‑on：模板渲染引擎最小原型实现
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.87s1od.asia/arts/331251.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.87s1od.asia/arts/445654.Doc

原标题：golang 系统设计秒杀防超卖方案
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.87s1od.asia/arts/599588.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.87s1od.asia/arts/378412.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.87s1od.asia/arts/938445.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.87s1od.asia/arts/097394.Doc

原标题：golang mysql 防止 sql 注入实践
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.87s1od.asia/arts/355684.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.87s1od.asia/arts/152233.Doc

原标题：golang 系统设计错误码体系完整设计
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.87s1od.asia/arts/640411.Doc

原标题：golang 系统设计 pr 评审合并完整流程
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.87s1od.asia/arts/219990.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.87s1od.asia/arts/108254.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.87s1od.asia/arts/041792.Doc

原标题：数据库主从延迟业务兼容处理
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.87s1od.asia/arts/712662.Doc

?
