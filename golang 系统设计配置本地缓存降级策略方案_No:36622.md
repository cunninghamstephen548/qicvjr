最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计配置本地缓存降级策略方案
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.amd1dg.asia/blog/168550.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://book.amd1dg.asia/blog/655947.Doc

原标题：分布式 ID 生成器高并发实现
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.amd1dg.asia/blog/353936.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.amd1dg.asia/blog/391582.Doc

原标题：golang kafka offset 提交策略
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.amd1dg.asia/blog/538818.Doc

原标题：开发记录：分布式锁超时业务安全处理实践
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.amd1dg.asia/blog/562309.Doc

原标题：axios 二次封装请求拦截处理
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.amd1dg.asia/blog/491561.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.amd1dg.asia/blog/253408.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.amd1dg.asia/blog/001171.Doc

原标题：golang http client 连接池调优
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.amd1dg.asia/blog/917452.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.amd1dg.asia/blog/727899.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.amd1dg.asia/blog/626436.Doc

原标题：大事务拆分回滚日志暴涨解决
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.amd1dg.asia/blog/837259.Doc

原标题：消息消费重试次数限制防爆炸
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.amd1dg.asia/blog/106095.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.amd1dg.asia/blog/465156.Doc

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.amd1dg.asia/blog/484453.Doc

原标题：Git 代码冲突正确处理方式
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.amd1dg.asia/blog/683360.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.amd1dg.asia/blog/688649.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.amd1dg.asia/blog/083786.Doc

原标题：Docker 容器时区错误修复方案
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.amd1dg.asia/blog/685264.Doc

原标题：开发代理服务网络限制解决
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://book.amd1dg.asia/blog/685006.Doc

原标题：golang 日志 zap 结构化日志实践
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.amd1dg.asia/blog/354714.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.amd1dg.asia/blog/941448.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.amd1dg.asia/blog/273601.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.amd1dg.asia/blog/196489.Doc

原标题：golang 系统设计字段命名类型选择最佳实践
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.amd1dg.asia/blog/652948.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.amd1dg.asia/blog/767836.Doc

原标题：Practice：实现业务操作日志记录中间件实践
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.amd1dg.asia/blog/457020.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://book.amd1dg.asia/blog/833655.Doc

原标题：Git commit 钩子提交规范校验
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.amd1dg.asia/blog/036058.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.amd1dg.asia/blog/397122.Doc

原标题：golang es 高亮搜索结果实现方案
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.amd1dg.asia/blog/944499.Doc

原标题：本地运行正常线上报错排查
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.amd1dg.asia/blog/161346.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.amd1dg.asia/blog/577149.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.amd1dg.asia/blog/540977.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://book.amd1dg.asia/blog/783223.Doc

原标题：golang validator 自定义校验规则
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.amd1dg.asia/blog/024377.Doc

原标题：新手向：项目目录结构规范与含义解析
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.amd1dg.asia/blog/761290.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.amd1dg.asia/blog/037560.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.amd1dg.asia/blog/145254.Doc


二、踩坑排错｜Troubleshooting
原标题：Troubleshooting：Redis大key引发集群卡顿
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.amd1dg.asia/blog/032767.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://book.amd1dg.asia/blog/126377.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.amd1dg.asia/blog/660778.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.amd1dg.asia/blog/638485.Doc

原标题：golang docker volume 数据持久化
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.amd1dg.asia/blog/208831.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.amd1dg.asia/blog/275856.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://book.amd1dg.asia/blog/676207.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.amd1dg.asia/blog/234619.Doc

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://book.amd1dg.asia/blog/735999.Doc

原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.amd1dg.asia/blog/542515.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.amd1dg.asia/blog/435993.Doc

原标题：golang 项目环境变量加载方案
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.amd1dg.asia/blog/178878.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.amd1dg.asia/blog/570741.Doc

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.amd1dg.asia/blog/924476.Doc

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.amd1dg.asia/blog/192637.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.amd1dg.asia/blog/243482.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.amd1dg.asia/blog/973338.Doc

原标题：ORM 隐式慢查询问题规避
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.amd1dg.asia/blog/019630.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.amd1dg.asia/blog/383168.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://book.amd1dg.asia/blog/814558.Doc

原标题：后端登录鉴权模块完整开发
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://book.amd1dg.asia/blog/406756.Doc

原标题：看懂报错日志快速定位问题
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.amd1dg.asia/blog/187295.Doc

原标题：golang 结构体 json 序列化坑点
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.amd1dg.asia/blog/614553.Doc

原标题：golang github actions 多平台构建
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.amd1dg.asia/blog/331704.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.amd1dg.asia/blog/734884.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.amd1dg.asia/blog/095890.Doc

原标题：入门实践：使用模板快速生成项目脚手架
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.amd1dg.asia/blog/651536.Doc

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://book.amd1dg.asia/blog/656095.Doc

原标题：golang 系统设计配置多环境隔离方案落地
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://book.amd1dg.asia/blog/861102.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://book.amd1dg.asia/blog/878889.Doc

原标题：容器资源限制防止宿主机过载
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://book.amd1dg.asia/blog/876471.Doc

原标题：Hands‑on：简易消息推送服务开发实践
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.amd1dg.asia/blog/257425.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.amd1dg.asia/blog/832282.Doc

原标题：golang redis 过期策略内存淘汰
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://book.amd1dg.asia/blog/902361.Doc

原标题：golang redis 布隆过滤器安装使用
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.amd1dg.asia/blog/175572.Doc

原标题：时间精度统一业务判断修复
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.amd1dg.asia/blog/008089.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://book.amd1dg.asia/blog/895882.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://book.amd1dg.asia/blog/427416.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.amd1dg.asia/blog/249967.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.amd1dg.asia/blog/880752.Doc

三、实战开发｜Practice
原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.amd1dg.asia/blog/314072.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.amd1dg.asia/blog/447128.Doc

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.amd1dg.asia/blog/145781.Doc

原标题：快速入门简单签名校验实现思路
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.amd1dg.asia/blog/298835.Doc

原标题：golang 项目目录分层规范设计
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.amd1dg.asia/blog/427152.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://book.amd1dg.asia/blog/793418.Doc

原标题：nestjs 权限守卫鉴权实现方案
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://book.amd1dg.asia/blog/010348.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.amd1dg.asia/blog/120937.Doc

原标题：golang 系统设计日志系统架构思路
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://book.amd1dg.asia/blog/473301.Doc

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.amd1dg.asia/blog/490053.Doc

原标题：golang redis 连接池参数最佳值
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.amd1dg.asia/blog/734234.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.amd1dg.asia/blog/345070.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://book.amd1dg.asia/blog/795989.Doc

原标题：开发生产环境资源路径统一
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.amd1dg.asia/blog/403418.Doc

原标题：服务健康检查监控接口开发
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.amd1dg.asia/blog/424554.Doc

原标题：全局本地依赖隔离冲突规避
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.amd1dg.asia/blog/577498.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.amd1dg.asia/blog/241211.Doc

原标题：vue pinia 状态管理实战教程
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.amd1dg.asia/blog/584447.Doc

原标题：快速上手搭建简易内网测试服务
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.amd1dg.asia/blog/020413.Doc

原标题：golang docker 基础命令实操汇总
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.amd1dg.asia/blog/658963.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.amd1dg.asia/blog/892254.Doc

原标题：DevOps：日志标准输出容器日志收集方案
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.amd1dg.asia/blog/971709.Doc

原标题：定时任务周期调度 demo 开发
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://book.amd1dg.asia/blog/255807.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://book.amd1dg.asia/blog/267855.Doc

原标题：部署实践：DockerCompose管理多服务环境
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.amd1dg.asia/blog/781901.Doc

原标题：入门实战：搭建简易静态网页项目
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.amd1dg.asia/blog/763103.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.amd1dg.asia/blog/048974.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.amd1dg.asia/blog/367107.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://book.amd1dg.asia/blog/834640.Doc

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.amd1dg.asia/blog/912776.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://book.amd1dg.asia/blog/796640.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.amd1dg.asia/blog/409691.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://book.amd1dg.asia/blog/512987.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.amd1dg.asia/blog/056711.Doc

原标题：K8s 镜像拉取网络故障修复
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://book.amd1dg.asia/blog/533110.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.amd1dg.asia/blog/724721.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.amd1dg.asia/blog/574264.Doc

原标题：全平台系统环境变量配置
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.amd1dg.asia/blog/584978.Doc

原标题：设计思考：分布式会话架构选型对比
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.amd1dg.asia/blog/856146.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.amd1dg.asia/blog/123606.Doc

四、架构设计｜Architecture
原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://book.amd1dg.asia/blog/585188.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.amd1dg.asia/blog/061141.Doc

原标题：golang prometheus 指标暴露实现
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.amd1dg.asia/blog/808299.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.amd1dg.asia/blog/148634.Doc

原标题：golang 定时任务 cron 使用指南
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.amd1dg.asia/blog/387856.Doc

原标题：实战：对象存储断点续传下载实践
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.amd1dg.asia/blog/768280.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.amd1dg.asia/blog/750264.Doc

原标题：服务熔断防止故障级联传播
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.amd1dg.asia/blog/512348.Doc

原标题：golang 系统设计内部服务调用超时设置要点
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.amd1dg.asia/blog/243769.Doc

原标题：全局异常处理器接口返回统一
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.amd1dg.asia/blog/571690.Doc

原标题：golang 布隆过滤器实现去重
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.amd1dg.asia/blog/049412.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.amd1dg.asia/blog/368282.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.amd1dg.asia/blog/357481.Doc

原标题：golang 系统设计限流服务架构讲解
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.amd1dg.asia/blog/683829.Doc

原标题：JWT 令牌过期异常处理
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.amd1dg.asia/blog/480475.Doc

原标题：业务接口幂等完整落地案例
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.amd1dg.asia/blog/612396.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.amd1dg.asia/blog/940154.Doc

原标题：golang 系统设计数据库版本迁移回滚方案
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://book.amd1dg.asia/blog/201628.Doc

?
