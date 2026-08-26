最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计蓝绿发布滚动发布对比
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.jg37lt.asia/blog/187933.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.jg37lt.asia/blog/099410.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.jg37lt.asia/blog/826623.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://book.jg37lt.asia/blog/104700.Doc

原标题：golang es 分页深分页性能优化
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://book.jg37lt.asia/blog/633963.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.jg37lt.asia/blog/929792.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://book.jg37lt.asia/blog/752739.Doc

原标题：极简 API 网关路由转发实现
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.jg37lt.asia/blog/444006.Doc

原标题：Dockerfile 编写容器打包实战
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.jg37lt.asia/blog/145710.Doc

原标题：开发代理服务网络限制解决
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.jg37lt.asia/blog/754376.Doc

原标题：golang prometheus 告警规则编写
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.jg37lt.asia/blog/573217.Doc

原标题：时间同步修复令牌提前过期
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.jg37lt.asia/blog/423319.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.jg37lt.asia/blog/330221.Doc

原标题：golang 系统设计配置敏感信息加密存储
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://book.jg37lt.asia/blog/752711.Doc

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.jg37lt.asia/blog/930282.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.jg37lt.asia/blog/150981.Doc

原标题：golang grafana 面板变量模板制作
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.jg37lt.asia/blog/594372.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.jg37lt.asia/blog/415674.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.jg37lt.asia/blog/714824.Doc

原标题：golang 系统设计分布式配置中心思路
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.jg37lt.asia/blog/681776.Doc

原标题：业务错误码体系设计方案
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://book.jg37lt.asia/blog/464327.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.jg37lt.asia/blog/590751.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.jg37lt.asia/blog/804496.Doc

原标题：环境变量不生效问题修复
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://book.jg37lt.asia/blog/961037.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.jg37lt.asia/blog/264090.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.jg37lt.asia/blog/453584.Doc

原标题：空指针异常判空容错处理
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.jg37lt.asia/blog/852809.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.jg37lt.asia/blog/317396.Doc

原标题：Debug：多线程共享可变变量产生脏数据
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.jg37lt.asia/blog/355179.Doc

原标题：golang es 索引生命周期管理思路
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://book.jg37lt.asia/blog/517461.Doc

原标题：多线程线程安全脏数据规避
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.jg37lt.asia/blog/996928.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.jg37lt.asia/blog/466363.Doc

原标题：golang 系统信号信号量处理
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://book.jg37lt.asia/blog/115189.Doc

原标题：实践：数据库回滚点业务调试实践
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.jg37lt.asia/blog/927076.Doc

原标题：定时任务重复执行分布式锁
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.jg37lt.asia/blog/537927.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.jg37lt.asia/blog/555035.Doc

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://book.jg37lt.asia/blog/662597.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.jg37lt.asia/blog/563954.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.jg37lt.asia/blog/115976.Doc

原标题：golang go test 覆盖率统计实操
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.jg37lt.asia/blog/417089.Doc


二、踩坑排错｜Troubleshooting
原标题：golang k8s helm chart 简单编写
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.jg37lt.asia/blog/502245.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.jg37lt.asia/blog/810217.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://book.jg37lt.asia/blog/237337.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.jg37lt.asia/blog/868492.Doc

原标题：golang 灰度权重流量分发简单实现
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.jg37lt.asia/blog/900353.Doc

原标题：前端错误监控上报系统搭建
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.jg37lt.asia/blog/337626.Doc

原标题：前后端交互跨域问题完整处理
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://book.jg37lt.asia/blog/026925.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://book.jg37lt.asia/blog/376981.Doc

原标题：从零编写简易 CLI 命令行工具
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.jg37lt.asia/blog/593011.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.jg37lt.asia/blog/494069.Doc

原标题：接口签名验签完整安全方案
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.jg37lt.asia/blog/750512.Doc

原标题：Git LFS 大文件推送失败解决
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.jg37lt.asia/blog/199480.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.jg37lt.asia/blog/169290.Doc

原标题：Practice：实现IP黑名单拦截中间件实践
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.jg37lt.asia/blog/893333.Doc

原标题：死信队列处理消息阻塞业务
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://book.jg37lt.asia/blog/684109.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.jg37lt.asia/blog/033778.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.jg37lt.asia/blog/567321.Doc

原标题：全局本地依赖隔离冲突规避
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.jg37lt.asia/blog/525144.Doc

原标题：golang github actions 缓存依赖提速
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.jg37lt.asia/blog/897745.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.jg37lt.asia/blog/344004.Doc

原标题：golang 单例模式实现几种方式
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.jg37lt.asia/blog/930091.Doc

原标题：nodejs 定时任务生产环境避坑
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://book.jg37lt.asia/blog/315923.Doc

原标题：golang 系统设计压测指标确定与分析
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://book.jg37lt.asia/blog/373369.Doc

原标题：golang mongodb 索引优化查询速度
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.jg37lt.asia/blog/453326.Doc

原标题：开发生产环境资源路径统一
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.jg37lt.asia/blog/696146.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://book.jg37lt.asia/blog/593305.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.jg37lt.asia/blog/774440.Doc

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://book.jg37lt.asia/blog/163665.Doc

原标题：golang 系统设计技术债务识别登记治理思路
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.jg37lt.asia/blog/597881.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.jg37lt.asia/blog/229171.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.jg37lt.asia/blog/196509.Doc

原标题：大文件导出内存溢出防护
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.jg37lt.asia/blog/600606.Doc

原标题：golang 消息队列 kafka 消费开发
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.jg37lt.asia/blog/880032.Doc

原标题：包管理器依赖冲突解决方案
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.jg37lt.asia/blog/726522.Doc

原标题：golang docker compose 部署 minio
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.jg37lt.asia/blog/837414.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.jg37lt.asia/blog/547307.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.jg37lt.asia/blog/467982.Doc

原标题：项目依赖安全扫描漏洞防范
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.jg37lt.asia/blog/893173.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.jg37lt.asia/blog/160173.Doc

原标题：DNS TTL 配置域名切换生效
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.jg37lt.asia/blog/234577.Doc

三、实战开发｜Practice
原标题：Hands‑on：简易反向代理中间件实现
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.jg37lt.asia/blog/082626.Doc

原标题：Docker 网络模式容器互通设置
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.jg37lt.asia/blog/833737.Doc

原标题：nodejs 接口限流防刷代码实现
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.jg37lt.asia/blog/523792.Doc

原标题：调试工具断点调试变量查看技巧
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.jg37lt.asia/blog/799214.Doc

原标题：文件锁正确使用避免死锁
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.jg37lt.asia/blog/637760.Doc

原标题：golang 系统设计延迟队列业务实现
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.jg37lt.asia/blog/370163.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.jg37lt.asia/blog/895866.Doc

原标题：入门实践：本地简单代理服务搭建
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.jg37lt.asia/blog/273365.Doc

原标题：Git commit 钩子提交规范校验
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.jg37lt.asia/blog/820339.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://book.jg37lt.asia/blog/325132.Doc

原标题：golang 系统设计采样策略降低链路存储开销
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.jg37lt.asia/blog/045825.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.jg37lt.asia/blog/673469.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.jg37lt.asia/blog/059245.Doc

原标题：golang k8s service 服务暴露几种类型
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.jg37lt.asia/blog/757068.Doc

原标题：golang gorm ORM 数据库操作
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.jg37lt.asia/blog/536383.Doc

原标题：Git commit 钩子提交规范校验
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.jg37lt.asia/blog/761769.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://book.jg37lt.asia/blog/556717.Doc

原标题：golang k8s ingress 路由域名转发
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.jg37lt.asia/blog/088875.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://book.jg37lt.asia/blog/823996.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.jg37lt.asia/blog/202262.Doc

原标题：业务错误码完整落地实践
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.jg37lt.asia/blog/198404.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.jg37lt.asia/blog/611778.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.jg37lt.asia/blog/384296.Doc

原标题：gitignore 文件编写过滤规则
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.jg37lt.asia/blog/649107.Doc

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://book.jg37lt.asia/blog/915877.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.jg37lt.asia/blog/234669.Doc

原标题：golang mysql 行锁表锁场景区分
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.jg37lt.asia/blog/382172.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://book.jg37lt.asia/blog/193144.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.jg37lt.asia/blog/671366.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.jg37lt.asia/blog/604632.Doc

原标题：时间同步修复令牌提前过期
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://book.jg37lt.asia/blog/126853.Doc

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.jg37lt.asia/blog/642435.Doc

原标题：golang channel 通道并发处理
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.jg37lt.asia/blog/044360.Doc

原标题：动态定时任务业务调度实现
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.jg37lt.asia/blog/896201.Doc

原标题：golang 系统设计开源 issue 处理回复沟通技巧
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.jg37lt.asia/blog/583326.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.jg37lt.asia/blog/763686.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.jg37lt.asia/blog/424848.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.jg37lt.asia/blog/600938.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.jg37lt.asia/blog/275293.Doc

原标题：从零搭建简单Mock接口服务
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.jg37lt.asia/blog/922229.Doc

四、架构设计｜Architecture
原标题：golang 分布式锁防死锁处理
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.jg37lt.asia/blog/844636.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.jg37lt.asia/blog/663929.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.jg37lt.asia/blog/686257.Doc

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.jg37lt.asia/blog/532856.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.jg37lt.asia/blog/587403.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://book.jg37lt.asia/blog/651182.Doc

原标题：golang k8s 节点污点容忍度配置
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://book.jg37lt.asia/blog/636734.Doc

原标题：golang 限流熔断降级完整示例
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://book.jg37lt.asia/blog/277385.Doc

原标题：golang docker 镜像体积优化技巧
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.jg37lt.asia/blog/059031.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.jg37lt.asia/blog/377549.Doc

原标题：golang gin 静态资源访问配置
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.jg37lt.asia/blog/580575.Doc

原标题：定时任务重复执行分布式锁
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.jg37lt.asia/blog/933992.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.jg37lt.asia/blog/932980.Doc

原标题：系统字符集统一乱码修复
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.jg37lt.asia/blog/011136.Doc

原标题：golang docker 部署 prometheus 整套
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.jg37lt.asia/blog/598737.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.jg37lt.asia/blog/094411.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://book.jg37lt.asia/blog/230379.Doc

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.jg37lt.asia/blog/470603.Doc

?
