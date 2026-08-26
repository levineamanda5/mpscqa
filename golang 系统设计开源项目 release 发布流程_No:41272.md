最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源项目 release 发布流程
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://book.36n932.asia/blog/960775.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.36n932.asia/blog/074012.Doc

原标题：golang k8s liveness readiness 探针
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.36n932.asia/blog/317135.Doc

原标题：实践：灰度流量切分简易实现方案
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.36n932.asia/blog/068429.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://book.36n932.asia/blog/387149.Doc

原标题：golang 系统设计用户签到统计方案
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.36n932.asia/blog/330005.Doc

原标题：Git 误提交撤销回退实操教程
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.36n932.asia/blog/318519.Doc

原标题：golang 系统设计接口幂等架构设计
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.36n932.asia/blog/726110.Doc

原标题：nodejs 消息队列消费服务开发
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.36n932.asia/blog/933951.Doc

原标题：golang dockerfile 多阶段构建详解
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.36n932.asia/blog/441183.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.36n932.asia/blog/807733.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.36n932.asia/blog/854405.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.36n932.asia/blog/414345.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.36n932.asia/blog/358288.Doc

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.36n932.asia/blog/406016.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.36n932.asia/blog/166618.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.36n932.asia/blog/894563.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.36n932.asia/blog/810067.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.36n932.asia/blog/689906.Doc

原标题：从零搭建简单定时任务demo
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.36n932.asia/blog/864753.Doc

原标题：项目实践：分布式会话Redis存储落地实践
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.36n932.asia/blog/030493.Doc

原标题：K8s 镜像拉取网络故障修复
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://book.36n932.asia/blog/322908.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.36n932.asia/blog/878864.Doc

原标题：Practice：模拟第三方接口超时服务降级验证
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://book.36n932.asia/blog/825664.Doc

原标题：golang validator 自定义校验规则
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.36n932.asia/blog/482112.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://book.36n932.asia/blog/294578.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.36n932.asia/blog/540038.Doc

原标题：Redis 分布式锁高并发安全实现
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://book.36n932.asia/blog/909504.Doc

原标题：新手指南：本地多版本环境共存配置
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.36n932.asia/blog/740873.Doc

原标题：golang 分库分表简单路由实现
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.36n932.asia/blog/755106.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.36n932.asia/blog/289240.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.36n932.asia/blog/313179.Doc

原标题：JWT 工具封装令牌刷新过期
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.36n932.asia/blog/322604.Doc

原标题：webpack chunk 分包策略详解
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.36n932.asia/blog/839997.Doc

原标题：golang 项目 docker compose 本地调试
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.36n932.asia/blog/677800.Doc

原标题：golang 时间时区处理避坑指南
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.36n932.asia/blog/518852.Doc

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.36n932.asia/blog/882125.Doc

原标题：Architecture：鉴权授权系统架构设计思路
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.36n932.asia/blog/580561.Doc

原标题：接口幂等性防重复请求实现
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.36n932.asia/blog/196223.Doc

原标题：日志切割配置防止日志丢失
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.36n932.asia/blog/788449.Doc


二、踩坑排错｜Troubleshooting
原标题：DNS TTL 配置域名切换生效
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://book.36n932.asia/blog/897901.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.36n932.asia/blog/807761.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.36n932.asia/blog/681874.Doc

原标题：golang elasticsearch 索引设计思路
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.36n932.asia/blog/269739.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://book.36n932.asia/blog/970260.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.36n932.asia/blog/306994.Doc

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.36n932.asia/blog/694717.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.36n932.asia/blog/131952.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.36n932.asia/blog/497140.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.36n932.asia/blog/051155.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://book.36n932.asia/blog/754539.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.36n932.asia/blog/171939.Doc

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.36n932.asia/blog/211803.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.36n932.asia/blog/239257.Doc

原标题：golang url 参数编码处理方案
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://book.36n932.asia/blog/945196.Doc

原标题：echarts 大数据渲染性能调优
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.36n932.asia/blog/456399.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.36n932.asia/blog/495886.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://book.36n932.asia/blog/333004.Doc

原标题：前端国际化多语言方案落地
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.36n932.asia/blog/124293.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.36n932.asia/blog/758315.Doc

原标题：无用对象回收抑制内存上涨
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.36n932.asia/blog/387764.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.36n932.asia/blog/815745.Doc

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.36n932.asia/blog/500016.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.36n932.asia/blog/728110.Doc

原标题：golang alertmanager 钉钉告警推送
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.36n932.asia/blog/021475.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.36n932.asia/blog/621368.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.36n932.asia/blog/304395.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.36n932.asia/blog/028211.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.36n932.asia/blog/755805.Doc

原标题：部署实践：服务器时间同步chrony配置
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.36n932.asia/blog/569146.Doc

原标题：语义化版本依赖管理防错乱
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.36n932.asia/blog/260369.Doc

原标题：接口幂等性防重复请求实现
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.36n932.asia/blog/293053.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.36n932.asia/blog/757783.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.36n932.asia/blog/642114.Doc

原标题：golang 项目 go mod 依赖管理
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://book.36n932.asia/blog/296557.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.36n932.asia/blog/757830.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://book.36n932.asia/blog/724469.Doc

原标题：依赖安装失败全方位排错
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.36n932.asia/blog/993637.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.36n932.asia/blog/481634.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.36n932.asia/blog/673474.Doc

三、实战开发｜Practice
原标题：并发数据覆盖加锁安全处理
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.36n932.asia/blog/393633.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.36n932.asia/blog/722231.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.36n932.asia/blog/545591.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.36n932.asia/blog/273770.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://book.36n932.asia/blog/762635.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.36n932.asia/blog/715520.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://book.36n932.asia/blog/107895.Doc

原标题：golang 系统设计用户签到统计方案
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.36n932.asia/blog/130138.Doc

原标题：Nginx 丢失请求头配置修正
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.36n932.asia/blog/676126.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.36n932.asia/blog/167385.Doc

原标题：golang mysql 存储过程简单使用
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://book.36n932.asia/blog/122610.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.36n932.asia/blog/151927.Doc

原标题：golang redis 过期策略内存淘汰
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.36n932.asia/blog/269447.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://book.36n932.asia/blog/378360.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.36n932.asia/blog/824923.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://book.36n932.asia/blog/869740.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.36n932.asia/blog/918665.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.36n932.asia/blog/428308.Doc

原标题：golang 系统设计分表字段选择路由规则设计
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.36n932.asia/blog/527971.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.36n932.asia/blog/186628.Doc

原标题：golang 系统设计接口返回格式统一规范
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.36n932.asia/blog/016255.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.36n932.asia/blog/325352.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.36n932.asia/blog/156226.Doc

原标题：golang 系统设计开源版本发布 changelog 维护
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.36n932.asia/blog/770747.Doc

原标题：golang 系统设计代码安全审计简单思路
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.36n932.asia/blog/455412.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://book.36n932.asia/blog/244731.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.36n932.asia/blog/103444.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.36n932.asia/blog/184869.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.36n932.asia/blog/715922.Doc

原标题：golang 链路追踪简易实现方案
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.36n932.asia/blog/716606.Doc

原标题：golang 信号量控制并发数量
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.36n932.asia/blog/736547.Doc

原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.36n932.asia/blog/811766.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.36n932.asia/blog/462738.Doc

原标题：golang 系统设计排行榜几种实现
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://book.36n932.asia/blog/951017.Doc

原标题：golang go test 覆盖率统计实操
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://book.36n932.asia/blog/585679.Doc

原标题：开发生产环境资源路径统一
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.36n932.asia/blog/108172.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://book.36n932.asia/blog/588200.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://book.36n932.asia/blog/077169.Doc

原标题：golang 空接口 interface 使用技巧
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.36n932.asia/blog/278718.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.36n932.asia/blog/422109.Doc

四、架构设计｜Architecture
原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://book.36n932.asia/blog/909222.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.36n932.asia/blog/311473.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://book.36n932.asia/blog/888436.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.36n932.asia/blog/794363.Doc

原标题：环境变量不生效问题修复
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.36n932.asia/blog/227126.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.36n932.asia/blog/115704.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.36n932.asia/blog/247996.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.36n932.asia/blog/064175.Doc

原标题：git stash 代码暂存切换分支
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.36n932.asia/blog/666151.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://book.36n932.asia/blog/319058.Doc

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.36n932.asia/blog/989643.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://book.36n932.asia/blog/070022.Doc

原标题：golang 系统设计序列化性能选型对比
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.36n932.asia/blog/995554.Doc

原标题：对象存储上传下载权限实操
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.36n932.asia/blog/270472.Doc

原标题：golang es 高亮搜索结果实现方案
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://book.36n932.asia/blog/184073.Doc

原标题：golang 优雅处理数据库事务
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://book.36n932.asia/blog/771460.Doc

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://book.36n932.asia/blog/289552.Doc

原标题：从零学习简单分页逻辑实现思路
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.36n932.asia/blog/752140.Doc

?
