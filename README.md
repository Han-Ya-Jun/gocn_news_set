# [gocn_news_set](https://gocn.vip/explore/category-14)
在之前爬虫Go中国技术社区每日新闻的的[小工具](https://github.com/Han-Ya-Jun/news_watch_notice)加了一个功能，自动归档到github上，方便查阅，每天自动更新。
# [gocn_news_set_2017](gocn_news_set_2017.md)
# [gocn_news_set_2018](gocn_news_set_2018.md)
# [gocn_news_set_2019](gocn_news_set_2019.md)
# [gocn_news_set_2020(上)](gocn_news_set_2020_01.md)
# [gocn_news_set_2020(下)](gocn_news_set_2020_02.md)
# gocn_news_set_202

## go中文网每日资讯--2021-07-15
一、Go语言中文网

1. [Go 项目从 Travis 迁移至 GitHub Actions](https://mp.weixin.qq.com/s/P8-ob4F70J03Hv_CQvJVcw)

2. [Go结构体的内存对齐](https://mp.weixin.qq.com/s/qHeM_eJ33m-vH6CmqUYnOg)

二、亚军进化史

1. [Go技术日报(2021-07-14)——Go1.16.6 发布](https://mp.weixin.qq.com/s/a6Qrnn5yirQUl70kP47r3w)

三、k8s技术圈

1. [Argo Rollouts 基于 Analysis 的渐进式发布](https://mp.weixin.qq.com/s/13HOX1j0DcjdH8v8-IVUKA)

四、Golang梦工厂

1. [赏析Singleflight设计](https://mp.weixin.qq.com/s/JUkxGbx1Ufpup3Hx08tI2w)

五、polarisxu

1. [Rust 所有权很难？这个开源工具帮你理解](https://mp.weixin.qq.com/s/ga5EES5wxfvQscJJaw97fw)

六、董泽润的技术笔记

1. [再批 MySQL JSON](https://mp.weixin.qq.com/s/nIpzfpggA1VWNiRBZVTm1A)

七、码农桃花源

1. [曹大带我学 Go（7）—— 如何优雅地指定配置项](https://mp.weixin.qq.com/s/qwzhLKnSAYlRT7oeE93CPg)

八、脑子进煎鱼了

1. [微服务的灾难：折磨人的环境！](https://mp.weixin.qq.com/s/h2tC7X1SEdX2tPnzCV_hWw)

2. [Go1.16.6 发布：又一个小问题引发安全 Bug](https://mp.weixin.qq.com/s/6vxsF2N9LbswnIYCGMsXeQ)

九、网管叨bi叨

1. [用Kubernetes搭建便携式开发环境之MongoDB](https://mp.weixin.qq.com/s/99Bp1GouUKoZVZ6_uF7msw)

十、Go招聘

1. [详解 Go 程序的启动流程，你知道 g0，m0 是什么吗？](https://mp.weixin.qq.com/s/1cKn0fhd_b_kh4Oy3UvYMA)





## GOCN每日新闻--2021-07-15
1.编写高质量的 Go benchmarks 并不容易 https://github.com/go101/go101/wiki/Writing-qualified-Go-benchmarks-is-not-easy

2.安全计数的多种方式 https://brunocalza.me/there-are-many-ways-to-safely-count/

3.Go 中的流水线模式 https://ketansingh.me/posts/pipeline-pattern-in-go-part-1/

4.探究 sync.RWMutex https://sreramk.medium.com/go-sync-rwmutex-internals-and-usage-explained-9eb15865bba#d1f6-c1e9f1b394e4

5.轻量级依赖注入框架 di https://github.com/go-tk/di



## 码农桃花源--2021-07-15
### 文章分享

1.[go g0/m0 ](https://mp.weixin.qq.com/s/1cKn0fhd_b_kh4Oy3UvYMA)

2.[图解 多线程操作同一个资源](https://mp.weixin.qq.com/s?__biz=MzUxODAzNDg4NQ==&mid=2247485264&idx=1&sn=78585cbabd1e0c333b43a3abd2b2ff64&chksm=f98e43facef9caecb8681562a1465fc5e1657b4bd332c6370289454b95737484cdbccd7b8076&scene=178&cur_album_id=1408057986861416450#rd)

### 思考问题

1. 怎样理解同步与互斥

2. 科学家就餐问题：5 个老大哥哲学家，闲着没事做，围绕着一张圆桌吃面；
巧就巧在，这个桌子只有 5 支叉子，每两个哲学家之间放一支叉子；

哲学家围在一起先思考，思考中途饿了就会想进餐；

奇葩的是，这些哲学家要两支叉子才愿意吃面，也就是需要拿到左右两边的叉子才进餐；

吃完后，会把两支叉子放回原处，继续思考；

那么问题来了，如何保证哲学家们的动作有序进行，而不会出现有人永远拿不到叉子呢？

3. 读者-写者的问题描述：
「读-读」允许：同一时刻，允许多个读者同时读

「读-写」互斥：没有写者时读者才能读，没有读者时写者才能写

「写-写」互斥：没有其他写者时，写者才能写


### 每日算法
算法：「反转链表」：https://leetcode-cn.com/problems/reverse-linked-list/



## go中文网每日资讯--2021-07-14


一、Go语言中文网

1. [Go1.16.6 发布](https://mp.weixin.qq.com/s/7DnxMeJr7TAQjfwGIMIoTQ)

二、Go中文网日报

1. [📖 Go相关公众号文章每日推荐【2021-07-13】 - Go语言中文网 - Golang中文社区](https://studygolang.com/topics/13959)

三、脑子进煎鱼了

1. [深入理解 Linux 的 epoll 机制](https://mp.weixin.qq.com/s/GEoG23wz2JfQQQ9MgoM8tg)

四、MoeLove

1. [万字长文：彻底搞懂容器镜像构建](https://mp.weixin.qq.com/s/9bspPi69ZgUMQi2cfZFIbg)

五、polarisxu

1. [一起聊聊 Go Context 的正确使用姿势](https://mp.weixin.qq.com/s/ohqLkq5n6dzOrmrBvc6tOA)

六、腾讯技术工程

1. [浅谈 Protobuf 编码](https://mp.weixin.qq.com/s/enDUynhZ1Pnzg_4xEjR21A)

七、TonyBai

1. [一文告诉你如何用好uber开源的zap日志库](https://mp.weixin.qq.com/s/cU5y465F7bhzVk6cHp0qVA)

八、mohuishou

1. [一个普通 Go 开发的三年](https://mp.weixin.qq.com/s/78xBFKZEM0lupUVdzYVA7A)

九、微服务实践

1. [听说过对 Go map 做 GC 吗？](https://mp.weixin.qq.com/s/s65P0ikv8v-dgI0fXg3F7g)

十、GoUpUp

1. [Go 每日一库之 net/http（基础和中间件）](https://mp.weixin.qq.com/s/OubTTnP1-4MvQMD0qakZxA)

十一、鸟窝

1. [[译]更新Go内存模型](https://colobu.com/2021/07/13/Updating-the-Go-Memory-Model/)

十二、Go招聘

1. [诺瓦科技诚聘Gopher，共同创造智能视界](https://mp.weixin.qq.com/s/Psgfopy8j5sZFX-l9uk4WQ)

2. [如何提高代码的可读性 学习笔记](https://mp.weixin.qq.com/s/_fg_oS74DEd4jKqJFHKHzg)


## GOCN每日新闻--2021-07-14
1.使用 Go 编写一个 VPN 工具 https://www.samlewis.me/2021/07/creating-mesh-vpn-tool-for-fun/

2.Go、微服务和 Twirp https://reshefsharvit.medium.com/golang-microservices-and-twirp-5ef495278ddf

3.MIME 头分析工具 mimeheader https://github.com/aohorodnyk/mimeheader

4.Go 布尔表达式索引器库 https://github.com/csimplestring/bool-expr-indexer

5.Go GTK4 绑定生成器 https://github.com/diamondburned/gotk4


## gopherDaily--2021-07-14
- 1.编程语言内存模型[译] -  https://colobu.com/2021/07/11/Programming-Language-Memory-Models/
- 2.livekit: Go实现的基于WebRTC的分布式视频/音频聊天室 - https://github.com/livekit/livekit-server
- 3.testza: Go的全功能测试框架! 支持断言、mock、输出捕捉等 - https://github.com/MarvinJWendt/testza/
- 4.Go http router框架横向对比 - https://benhoyt.com/writings/go-routing/
- 5.WebAssembly旨在消除文件系统 - https://thenewstack.io/webassembly-aims-to-eliminate-the-file-system/
- 6.改善Kubernetes开发的有用工具 - https://blog.usejournal.com/useful-tools-for-better-kubernetes-development-87820c2b9435
- 7.gan-go: 通过Gorgonia在Go中使用生成对抗性网络(GAN) - https://github.com/LdDl/gan-go
- 8.用WasmEdge和YoMo进行实时数据流的AI推理 - https://www.secondstate.io/articles/yomo-wasmedge-real-time-data-streams/
- 9.Go-clean-template：用于Go服务的clean architecture模板 - https://evrone.com/go-clean-template
- 10.代码搜索的未来 by sourcegraph (刚获得由安德烈森 · 霍洛维茨领投的1.25亿刀D轮投资)- https://about.sourcegraph.com/blog/the-future-of-code-search/




## go中文网每日资讯--2021-07-13


一、Go语言中文网

1. [图解 Go 协程，操作系统线程和 CPU 管理](https://mp.weixin.qq.com/s/INW0vr9_9cQhbTBR5ho0Sw)

2. [Go 依赖注入：为什么把 dig 迁移到 wire](https://mp.weixin.qq.com/s/bHXRSpiIhycoQLN5oz0QMA)

二、亚军进化史

1. [Go技术日报(2021-07-12)——grpc基本概念](https://mp.weixin.qq.com/s/vxni2e0UPXQTPzrm-l7_HA)

三、k8s技术圈

1. [Prometheus 存储层的演进](https://mp.weixin.qq.com/s/TaE2mfJMHLMnw-NLYZRqhA)

四、Golang梦工厂

1. [大厂Golang语法50问!](https://mp.weixin.qq.com/s/gp-4KCc0JcuSA05jXpVYuA)

五、HHFCodeRv

1. [我为什么从 C++ 转到了 Go ?](https://mp.weixin.qq.com/s/2jEwYZJYQLtBYO5pq4bhwA)

六、polarisxu

1. [Rust + Go 双剑合璧：WebAssembly 领域应用](https://mp.weixin.qq.com/s/501wCGxATJ0J7kGZqsKiJw)

2. [Go1.16.6 发布：又一个小问题引发安全 Bug](https://mp.weixin.qq.com/s/s1q6YKzFX0FLec394es-0g)

七、董泽润的技术笔记

1. [如何用 Go 实现 JIT Compiler](https://mp.weixin.qq.com/s/ubxfUg9qAqlBmi-Yw0H-fw)

2. [一文解惑 //go:linkname 指令](https://mp.weixin.qq.com/s/0rOBzMeFHKS0MLRtYGhHvw)

八、Go夜读

1. [Go 紧急修复 crypto/tls 安全问题](https://mp.weixin.qq.com/s/WC0VSOzDk5XTXcc5tLP6fg)

九、Go语言进阶

1. [日志库的使用姿势](https://mp.weixin.qq.com/s/rqmrkUiDtorzEIN00ObbLg)

十、腾讯云中间件

1. [Kratos技术系列｜从Kratos设计看Go微服务工程实践](https://mp.weixin.qq.com/s/ZCoc3qA_r1fKzPOURA2V2g)
 


## GOCN每日新闻--2021-07-13

1.Go 1.16.6 and Go 1.15.14 are released https://groups.google.com/g/golang-announce/c/n9FxMelZGAQ/m/4ZhvTx0dAQAJ

2.更新 Go 内存模型 https://research.swtch.com/gomm

3.Go 依赖注入：为什么把 dig 迁移到 wire https://mp.weixin.qq.com/s/bHXRSpiIhycoQLN5oz0QMA

4.编程模式之 Go 如何实现装饰器 https://mp.weixin.qq.com/s/B_VYr3I525-vjHgzfW3Jhg

5.Go 不是 C，所以没有极快的方法来合并切片 https://github.com/go101/go101/wiki/Go-is-not-C,-so-there-is-not-an-extreme-fast-way-to-merge-slices



## gopherDaily--2021-07-13
- 1.更新Go内存模型 by Russ Cox - https://research.swtch.com/gomm
- 2.Go 1.16.6和1.15.14发布 - https://groups.google.com/g/golang-announce/c/n9FxMelZGAQ/m/4ZhvTx0dAQAJ
- 3.Hashicorp开源cap：一个认证包的集合 - https://github.com/hashicorp/cap
- 4.Go的典型项目目录结构的历史与原因 - https://www.reddit.com/r/golang/comments/oiwht8/reasoninghistory_of_gos_typical_project_directory/
- 5.使用Istio和Kind的多集群流量镜像 - https://piotrminkowski.com/2021/07/12/multicluster-traffic-mirroring-with-istio-and-kind/
- 6.理解Go类型嵌入 - https://octo.vmware.com/golang-embedding/
- 7.成为更好的Go开发者的7个课题（和GitHub存储库) - https://dev.to/avelino/7-subjects-and-github-repositories-to-become-a-better-go-developer-3kb3
- 8.在Go项目中运行的便捷命令 - https://github.com/nikolaydubina/go-recipes
- 9.2D游戏引擎Ebiten作者的8年心路历程（日语) - https://note.com/hajimehoshi/n/nc09751f2dbf9
- 10.在混合云和多云之间做出选择时需要考虑的问题 - https://thenewstack.io/what-to-consider-when-choosing-between-hybrid-and-multicloud/

## 码农桃花源--2021-07-13
### 文章分享

1.[redis ](https://mp.weixin.qq.com/s/mFqn6bQvh2OAxoguY7OGJw)

2.[图解 进程与线程](https://mp.weixin.qq.com/s?__biz=MzUxODAzNDg4NQ==&mid=2247485175&idx=1&sn=eda03758d4e810afd897ade44c19a508&chksm=f98e425dcef9cb4b3da63e6054f34d5012068b16eb3503d7e5a93bc2a857f1e5116ff793f1d9&scene=178&cur_album_id=1408057986861416450#rd)

### 课后问题

1. 进程的五种状态变迁图，七种的呢，是什么样子的？

2. PCB(进程控制块)包含了什么信息？

3. 寄存器，内存，硬盘哪个更快

4. 进程的上下文切换到底是切换什么呢？

5. TCB是什么

6. 内核空间与用户空间的区别

7. 进程的调度时机


### 每日算法

算法：「反转链表」：https://leetcode-cn.com/problems/reverse-linked-list/

## go中文网每日资讯--2021-07-12


一、Go语言中文网

1. [Go 微服务中的熔断器和重试](https://mp.weixin.qq.com/s/4-n-mpSPrT8kbxRT1qv0Xw)

2. [Go 每日一库之 tunny](https://mp.weixin.qq.com/s/Qvh_-TI3Dglp3-ddqC_L1A)

二、亚军进化史

1. [Go技术日报(2021-07-10)——使用反馈控制优化goroutines的数量](https://mp.weixin.qq.com/s/xQrfb071auTY3uahnlwNPg)

2. [Go技术日报(2021-07-11)——为什么大公司里的垃圾系统也能保持稳定](https://mp.weixin.qq.com/s/SMwW1zL0wnDHODJWsoD0pQ)

三、脑子进煎鱼了

1. [一起聊聊 Go Context 的正确使用姿势](https://mp.weixin.qq.com/s/5JDSqNIimNrgm5__Z4FNjw)

2. [Go项目实战：从零构建一个并发文件下载器](https://mp.weixin.qq.com/s/28CjAeINvlvNqLXP0g2oMw)

四、Golang梦工厂

1. [编程模式之Go如何实现装饰器](https://mp.weixin.qq.com/s/B_VYr3I525-vjHgzfW3Jhg)

五、网管叨bi叨

1. [试了试Docker桌面应用自带的K8s集群，一个字“简单”](https://mp.weixin.qq.com/s/Bq2Yckr6QkqFC7i7MCMhGA)

六、Golang技术分享

1. [你有考虑过defer Close() 的风险吗](https://mp.weixin.qq.com/s/7J6zEj_5gksZbFy0ANlvwg)

七、李文周

1. [Go结构体的内存对齐](https://mp.weixin.qq.com/s/gYL9nKIXEKgnZP8BHNADAA)

八、董泽润的技术笔记

1. [Rust 让人迷惑的 “借用”](https://mp.weixin.qq.com/s/F7nkdhUed-M2bhWnN3hiEg)

九、奇伢云存储

1. [Linux fd 系列 — eventfd 是什么？](https://mp.weixin.qq.com/s/7pp3_XdJoffrw9dxoCmnSw)

十、码农桃花源

1. [Go 超时引发大量 fin-wait2](https://mp.weixin.qq.com/s/eePELhDUfUZbHD72SuqmYw)

十一、k8s技术圈

1. [KubeVela 上手体验 - 让云端应用交付更加丝滑](https://mp.weixin.qq.com/s/Xmn8SIPhgU50_UK5ZjP9GA)

十二、polarisxu

1. [这个工具真好：看看你的Go项目依赖有无漏洞](https://mp.weixin.qq.com/s/pzCefw0g82f6fNqiW3wqEg)

十三、Go招聘

1. [Go日志库zero-log大解剖](https://mp.weixin.qq.com/s/knayd7gQSChyDfSJCxh3uA)


## GOCN每日新闻--2021-07-12

1.学习 channel 设计：从入门到放弃 https://mp.weixin.qq.com/s/wWF27OnOUf-GM0UKDfrqUA

2.Golang 官方限流器的用法详解 https://mp.weixin.qq.com/s/S3_YEyhLcaAUuaSabXdimw

3.亿级系统的 Redis 缓存如何设计？ https://mp.weixin.qq.com/s/bkXnbQIpI_GdX4BHkAhPUA

4.面试官：你能聊聊 string 和 [] byte 的转换吗？https://mp.weixin.qq.com/s/gl7bM4M1b2howHnplop8FA

5.Golang 语言中怎么解码 4 种常见 JSON 格式数据？https://mp.weixin.qq.com/s/Oy4cHyROIrkAl9tixzfQ6g

## 码农桃花源--2021-07-12
### 文章分享

1.[grpc基本概念] https://mp.weixin.qq.com/s/I2QHEBO26nGqhGwIw281Pg

2.[图解 内存管理] https://mp.weixin.qq.com/s?__biz=MzUxODAzNDg4NQ==&mid=2247485033&idx=1&sn=bf9ba7aca126ad186922c57a96928593&chksm=f98e42c3cef9cbd514df38d04deb5e7a9ea67dbd478da75fc4a7636ee90b1384d65f68eb23f5&scene=178&cur_album_id=1408057986861416450#rd

### 面试题

1.单片机的 CPU 是否直接操作内存的「物理地址」?如果是的话，操作系统是如何解决这个问题呢？

2.操作系统是如何管理虚拟地址与物理地址之间的关系？

3.分段为什么会产生内存碎片的问题

4.分段为什么会导致内存交换效率低的问题？

5.分页是怎么解决分段的内存碎片、内存交换效率低的问题？

6.内核空间与用户空间的区别

7.不同的用户空间对应的是否是相同的内核空间


### 每日算法
算法：「反转链表」：https://leetcode-cn.com/problems/reverse-linked-list/

 
## go中文网每日资讯--2021-07-11


一、Go语言中文网

1. [微软牛逼：招 Go 编译器全职开发人员](https://mp.weixin.qq.com/s/9hMU4FbTVGQZDwZ7Cdd67A)

2. [Go语言爱好者周刊：第 103 期 — Go 实现的聊天机器人](https://mp.weixin.qq.com/s/-ZJ7lUIYj-7gA22CKlXGLg)

3. [面试官：你能聊聊string和[]byte的转换吗？](https://mp.weixin.qq.com/s/gl7bM4M1b2howHnplop8FA)

二、亚军进化史

1. [Go技术日报(2021-07-09)——关于 Golang 的 4 个小秘密](https://mp.weixin.qq.com/s/0k5dY_TMsnYtdU0ZYjdk4w)

2. [Go技术日报(2021-07-08)——Go 阅读清单](https://mp.weixin.qq.com/s/hQkN3lfExcN0kmLboL87Iw)

三、TechPaper

1. [为什么大公司里的垃圾系统也能保持稳定](https://mp.weixin.qq.com/s/BVg_vK8QTDzvD9MNm23qfg)

四、k8s技术圈

1. [Argo Rollouts 实现蓝绿/金丝雀发布](https://mp.weixin.qq.com/s/vTzrNUrG3UvAIQUfbSruow)

五、HHFCodeRv

1. [连接一个 IP 不存在的主机时，握手过程是怎样的？](https://mp.weixin.qq.com/s/wMzC1iD5hjIwKadHxRBIDQ)

六、分布式实验室

1. [2021 年 Kubernetes 的开发者工具：Helm、Kustomize 和 Skaffold](https://mp.weixin.qq.com/s/-OuKPLp82q4i9s1dkyUAVA)



## GOCN每日新闻--2021-07-11
1. 如何在 Go 中嵌入 Python https://linux.cn/article-13564-1.html 

2. 熔断器原理与 Go 实现 https://ioshellboy.medium.com/circuit-breakers-in-golang-1779da9b001 

3. Go Playground 中如何实现随机 https://deedlefake.com/randomness-in-the-go-playground.html 

4. 如何 Mock AWS API 客户端 https://brandonstrohmeyer.medium.com/aws-api-client-mocking-with-go-b940dde80d9e 

5. Peanut: 一款常用中间件快速部署管理平台 https://github.com/Clivern/Peanut

## gopherDaily--2021-07-11
 - 1.一文告诉你如何用好uber开源的zap日志库 - https://t.zsxq.com/jMBUrjE
 - 2.Go语言中的一些非常规优化 - https://xargin.com/unusual-opt-in-go/
 - 3.Go网络包默认值中的那些陷阱 - https://martin.baillie.id/wrote/gotchas-in-the-go-network-packages-defaults/
 - 4.用gookit/validate进行Go数据验证和过滤 - https://al3rez.github.io/go/input-validaiton/2021/07/11/go-data-validation-and-filtering-with-gookit-validate.html
 - 5.使用Go构建微服务系列 - https://dev.to/mariocarrion/building-microservices-in-go-rest-apis-implementing-and-dealing-with-errors-5gpc
 - 6.自动设置GOMAXPROCS以匹配Linux容器的CPU配额 - https://github.com/uber-go/automaxprocs
 - 7.在Azure上使用Kubeflow和MinIO的机器学习管道 - https://blog.min.io/kubeflow-minio-azure/
 - 8.如何在Kubernetes上运行你自己的准入(admission)控制器 - https://blog.nillsf.com/index.php/2020/12/03/how-to-run-your-own-admission-controller-on-kubernetes/
 - 9.教程：把一个github仓库变成helm仓库 - https://harness.io/blog/devops/helm-chart-repo/
 - 10.Slack如何利用追踪技术改造他们的CI - https://www.honeycomb.io/blog/how-slack-transformed-their-ci-with-tracing/
 - 11.使用IceWM和Raspberry Pi作为我的主电脑，分享我的主题，配置和一些技巧和窍门 - https://raymii.org/s/blog/Using_IceWM_and_sharing_my_config_and_tips_tricks.html

# go中文网每日资讯--2021-07-10
一、Go语言中文网

1. [Go每日一库之带WebUI的HTTP Benchmark](https://mp.weixin.qq.com/s/DbEtp6fsCK1aHroDDkkIMg)

2. [Go Web 框架 Gin 路由的学习](https://mp.weixin.qq.com/s/MJNLgDW1PcapCNj4YrhJLw)

二、亚军进化史

1. [Go技术日报(2021-07-09)——关于 Golang 的 4 个小秘密](https://mp.weixin.qq.com/s/0k5dY_TMsnYtdU0ZYjdk4w)

2. [Go技术日报(2021-07-08)——Go 阅读清单](https://mp.weixin.qq.com/s/hQkN3lfExcN0kmLboL87Iw)

三、幼麟实验室

1. [深度探索Go语言(六)：抢占式调度](https://mp.weixin.qq.com/s/31nZzJ-gUBeAh7X9QdubFQ)

2. [深度探索Go语言(七)：抢占式调度](https://mp.weixin.qq.com/s/ucRS8bxJu7IkHDUW7bMQnA)




## GOCN每日新闻--2021-07-10
1.简单灵活的 Go 健康检查库 https://github.com/alexliesenfeld/health

2.Go 的 WorkerPools 实现

3.硬件内存模型 https://research.swtch.com/hwmm

4.从头编写一个时间序列的数据库引擎 https://nakabonne.dev/posts/write-tsdb-from-scratch/

5.Go 实现的一个快速的 HTML 有害内容 XSS 清除库 https://github.com/microcosm-cc/bluemonday



## gopherDaily--2021-07-10

- 1.长文！编程语言内存模型 by Russ Cox - https://research.swtch.com/plmm
- 2.深入Go Module之未说的秘密 - https://colobu.com/2021/07/04/dive-into-go-module-3/
- 3.使用反馈控制优化goroutines的数量 - https://blog.monochromegane.com/blog/2019/07/25/gophercon_2019_kaburaya/
- 4.一个goroutine的大小 - https://tpaschalis.github.io/goroutines-size/
- 5.Go netpoll I/O 多路复用构建原生网络模型之源码深度解析 - https://www.infoq.cn/article/boEavgkIqmvcj8qJNBxk
- 6.Go: sync.RWMutex的原理和使用说明 - https://sreramk.medium.com/go-sync-rwmutex-internals-and-usage-explained-9eb15865bba#d1f6-c1e9f1b394e4
- 7.关于在Go中实现并发安全计数器的方法汇总 - https://brunocalza.me/there-are-many-ways-to-safely-count/
- 8.油管视频：实现Go worker池 - https://www.youtube.com/watch?v=1iBj5qVyfQA
- 9.一个私人证书机构（X.509和SSH）和ACME服务器用于安全的自动证书管理 - https://github.com/smallstep/certificates
- 10.播客：聊聊即将于go 1.17加入Go的Fuzzing - https://changelog.com/gotime/187







## go中文网每日资讯--2021-07-09


一、Go语言中文网

1. [详解 Go 语言 Protobuf 之 Message](https://mp.weixin.qq.com/s/Q8peFKy8Ftv21E4qmjNCXQ)

2. [Go cmd 服务无法退出的小坑](https://mp.weixin.qq.com/s/4FEt052_CmWCkWLecOgxWg)

二、polarisxu

1. [搞 Go 要了解的 2 个 Header，你知道吗？](https://mp.weixin.qq.com/s/PszksqM4-c-mhQt-TUsMSQ)

三、脑子进煎鱼了

1. [给，你要的 Go 学习路线图来啦](https://mp.weixin.qq.com/s/ZQDr_f0-7yOptOQr46dvQQ)

四、牛儿吃草仗剑天涯

1. [一文读懂 分布式链路追踪系统 Jaeger](https://mp.weixin.qq.com/s/IdAQT3tNsCsGFwOXLf7Anw)

五、网管叨bi叨

1. [学习channel设计：从入门到放弃](https://mp.weixin.qq.com/s/wWF27OnOUf-GM0UKDfrqUA)

六、Go招聘

1. [关于Go Test这些小技巧，Gopher应该知道](https://mp.weixin.qq.com/s/HzET8y7lRa7NzJhB49ATtg)

七、董泽润的技术笔记

1. [弱智的 MySQL NULL](https://mp.weixin.qq.com/s/hmro3mAmEWDgpanH3DsPpQ)

## GOCN每日新闻--2021-07-09
1.编程语言内存模型 https://research.swtch.com/plmm

2.关于 Golang 的 4 个小秘密 https://mp.weixin.qq.com/s/LLJh8CGhRqR3Zu8wPfIxRQ

3.Golang 官方限流器的用法详解 https://mp.weixin.qq.com/s/S3_YEyhLcaAUuaSabXdimw

4.map 的底层实现 https://segmentfault.com/a/1190000040269520

5.Tekton 与 Argo CD 结合实现 GitOps https://mp.weixin.qq.com/s/8jCdM3w3rDpAxLuDkLHn8g


## 码农桃花源--2021-07-09
### 文章分享

1.[FormData 和 Content-Type: multipart/form-data](https://www.cnblogs.com/nicholaswang/p/11459860.html)

2.[图解 Redis | 不就是 AOF 持久化嘛](https://www.cnblogs.com/xiaolincoding/p/14816503.html)

3.[rosedb 及存储模型](https://mp.weixin.qq.com/s/MzBfTuqIaz2ny1B54-iYfw)

### 面试题

1.Go指针和unsafe.Pointer有什么区别

2.如何利用unsafe包修改私有成员

3.如何利用unsafe获取slice&map的长度

4.如何实现字符串和byte切片的零拷贝转换


### 每日算法

「环形链表 II」：https://leetcode-cn.com/problems/linked-list-cycle-ii/


## go中文网每日资讯--2021-07-08


一、Go语言中文网

1. [类似 Go 中的表格驱动测试的步骤驱动评估](https://mp.weixin.qq.com/s/saIuPyEW_yFNrcnP8qG0LQ)

2. [你不知道的 Go 之 pprof](https://mp.weixin.qq.com/s/w6mx89xggITalSOHvx4vPA)

二、亚军进化史

1. [Go技术日报(2021-07-07)——dtm: 国人开源的分布式事务框架](https://mp.weixin.qq.com/s/AGPt0LV5VCXFIiz0jEZ_gA)

三、CloudNativeCommunity

1. [如何调试 Kubernetes 中的微服务 ——proxy、sidecar 还是 service mesh？](https://mp.weixin.qq.com/s/cPmlXiKDtqFBWRc-Wg5Ypw)

四、luozhiyun很酷

1. [endless 如何实现不停机重启 Go 程序？](https://mp.weixin.qq.com/s/VQdRsb-uL2XKB2N0cW6chQ)

五、k8s技术圈

1. [Tekton 与 Argo CD 结合实现 GitOps](https://mp.weixin.qq.com/s/8jCdM3w3rDpAxLuDkLHn8g)

六、脑子进煎鱼了

1. [微服务的灾难：拆的很爽，但服务太小...](https://mp.weixin.qq.com/s/QxxOeOZPiKAXGc73D8wqXA)

七、polarisxu

1. [网友很强大，发现了Go并发下载的Bug](https://mp.weixin.qq.com/s/g_v9ZOotpMfvgQtM5GqB-g)
 

## GOCN每日新闻--2021-07-08
1.私有化仓库的 GO 模块使用实践 https://zhuanlan.zhihu.com/p/384621827

2.Go 阅读清单 https://github.com/qichengzx/gopher-reading-list-zh_CN

3.sync.RWMutex 实现和使用说明 https://sreramk.medium.com/go-sync-rwmutex-internals-and-usage-explained-9eb15865bba

4.Go 使用 WasmEdge 嵌入 WASM https://www.secondstate.io/articles/extend-golang-app-with-webassembly-rust/

5.go-doudou 去中心化微服务敏捷开发框架 https://github.com/unionj-cloud/go-doudou




## gopherDaily--2021-07-08
1.端到端跟踪的三种方法 - https://rakyll.medium.com/three-ways-to-trace-end-to-end-f61181d6db63

2.开启云原生MOSN新篇章—融合Envoy和Go生态 - https://mp.weixin.qq.com/s/IDrvSsdXTzwriAlpDAOQPg

3.用Go在2分钟内复制100万个Redis key - https://medium.com/amboss/copy-redis-keys-in-minutes-with-golang-3c06f3cd3af8

4.Calico：利用新的eBPF数据平面的多种优势 - https://www.tigera.io/blog/calico-enterprise-leverage-multiple-benefits-from-the-new-ebpf-data-plane

5.油管视频：后端迁移的工具和技术 - https://www.youtube.com/watch?v=LD3zB5rYn3I

6.用Go编写的Elf二进制感染器 - https://github.com/sad0p/d0zer

7.数据结构可视化 - https://www.cs.usfca.edu/~galles/visualization/Algorithms.html

8.在部署到Kubernetes时运行数据库迁移 - https://andrewlock.net/deploying-asp-net-core-applications-to-kubernetes-part-7-running-database-migrations/




## go中文网每日资讯--2021-07-07


一、Go语言中文网

1. [在 5 分钟之内部署一个 Go 应用](https://mp.weixin.qq.com/s/ENKYHrWv_Ayz2XdjvQ3sVQ)

2. [Go 每日一库之 ants 源码赏析](https://mp.weixin.qq.com/s/bs0ayyio--xCZZI0paY-Lw)

二、亚军进化史

1. [Go技术日报(2021-07-06)——多 Goroutine 如何优雅处理错误？](https://mp.weixin.qq.com/s/-GBg3Aes7foWSpCasvi8DA)

三、MoeLove

1. [开源中国专访张晋涛：从Web开发者到中国首位K8s ingress-nginx reviewer](https://mp.weixin.qq.com/s/yvP58J8NrUhWW3KEfH4gow)

四、polarisxu

1. [Rust 劝退系列 09：函数](https://mp.weixin.qq.com/s/nrGagd49cIucvq-ULR9Oow)

五、董泽润的技术笔记

1. [Go cmd 服务无法退出的小坑](https://mp.weixin.qq.com/s/mdc8c5Bd0LfLd4fP6SMAsQ)

六、Go夜读

1. [rosedb 及存储模型（PPT及参考资料）](https://mp.weixin.qq.com/s/MzBfTuqIaz2ny1B54-iYfw)

七、CloudNativeCommunity

1. [如何选择最佳的 Kubernetes 集群自动伸缩策略](https://mp.weixin.qq.com/s/hgw_yjCsNKPo7hP01FfSJQ)

八、码农桃花源

1. [高并发场景下 disk io 引发的高时延问题](https://mp.weixin.qq.com/s/e3peaNGwIuNkldvnP0pDug)

2. [开启云原生 MOSN 新篇章 — 融合 Envoy 和 Golang 生态](https://mp.weixin.qq.com/s/dqdt3-nJdu7Y2rABbyksMA)

九、网管叨bi叨

1. [给，你要的Go学习路线图来啦](https://mp.weixin.qq.com/s/lTD6I_Aq_JR0pE_W3dTHnw)

十、Go招聘

1. [gRPC服务注册发现及负载均衡的实现方案与源码解析](https://mp.weixin.qq.com/s/fLmK1CRWxpPoJvcUaZK-LA)

十一、吴亲强的深夜食堂

1. [为什么把 dig 迁移到 wire](https://mp.weixin.qq.com/s/ZAHInPGKT4UZqzmfkqUCMQ)
 

## GOCN每日新闻--2021-07-07
1.开启云原生 MOSN 新篇章 — 融合 Envoy 和 Golang 生态 https://mp.weixin.qq.com/s/ioewVcwiB5QA8w3A3gaikg

2.Go 中性能测试可以是令人惊讶的 https://leveluppp.ghost.io/benchmarks-in-go-can-be-surprising/

3.构建 Splitz：Razorpay 的大规模线上测试平台 https://engineering.razorpay.com/building-splitz-razorpays-platform-for-high-scale-experimentation-c917fe15d8f6

4.entgo 中自动生成 GraphQL 过滤器https://entgo.io/blog/2021/07/01/automatic-graphql-filter-generation/

5.dtm: 国人开源的分布式事务框架 https://github.com/yedf/dtm

## gopherDaily--2021-07-07
1.GO中的基准测试可能令人惊讶 - https://leveluppp.ghost.io/benchmarks-in-go-can-be-surprising/

2.深入kubernetes controller - https://speakerdeck.com/govargo/inside-of-kubernetes-controller

3.di: 小巧的依赖注入框架 - https://github.com/go-tk/di

4.用WasmEdge中的嵌入式WebAssembly函数扩展你的Go应用程序 - https://www.secondstate.io/articles/extend-golang-app-with-webassembly-rust/

5.Dave讲故事：Go是如何避免隐式整数提升和类型转换的 - https://www.youtube.com/watch?v=bwQS7PO6_Ho

6.在谷歌Kubernetes引擎中开始使用Litmus 2.0 - https://medium.com/litmus-chaos/getting-started-with-litmus-2-0-in-google-kubernetes-engine-42dddb264a12

7.Kubernetes存储解析 - https://medium.com/swlh/kubernetes-storage-explained-558e85596d0c

8.在运行Istio的亚马逊EKS上观察基于gRPC的微服务 - https://itnext.io/observing-grpc-based-microservices-on-amazon-eks-running-istio-77ba90dd8cc0




## go中文网每日资讯--2021-07-06


一、Go语言中文网

1. [Go开源实战项目推荐：用来练手挺好](https://mp.weixin.qq.com/s/UJXbqcH9bO7utZJxXxWgUg)

2. [如何选择一门编程语言](https://mp.weixin.qq.com/s/M-NlM8lzzL7IZJMNi0hIIw)

3. [你真的了解 Load Balance 嘛](https://mp.weixin.qq.com/s/90nd-rh2P4QJF8fDPu3CVg)

二、CloudNativeCommunity

1. [云原生社区 meetup 第五期成都站视频及 PPT 分享](https://mp.weixin.qq.com/s/_Uf9dLa5yH5LpQcQgWAc8A)

三、TonyBai

1. [使用go-metrics在Go应用中增加度量](https://mp.weixin.qq.com/s/pFTLGOsyl5DgohbSTBSr-w)

四、亚军进化史

1. [Go技术日报(2021-07-05)——从零构建一个并发文件下载器](https://mp.weixin.qq.com/s/d8kwhR5OK4RZs7CGRCKYpg)

五、polarisxu

1. [小技巧分享：在 Go 如何实现枚举？](https://mp.weixin.qq.com/s/JJ2XmFK28FJwzhD-mYk8Iw)

六、董泽润的技术笔记

1. [真实环境下大内存 Go 服务性能优化一例](https://mp.weixin.qq.com/s/jGGCccMOx4s5asG2IXWNMQ)

七、腾讯技术

1. [技术人员的修炼手册](https://mp.weixin.qq.com/s/hK8i1Vl5xdFRX2SnNCUDKg)

八、yifhao

1. [几行代码为老板省百万-某高并发服务GOGC及UDP Pool优化](https://mp.weixin.qq.com/s/EuJ3Pw0s24Nr1h2edn5Sgg)

九、脑子进煎鱼了

1. [Go 中的 error 居然可以这样封装](https://mp.weixin.qq.com/s/-X8MKIQFRXmENsdwyRXcCg)

十、Go招聘

1. [在Go中如何用Redlock实现分布式锁呢？](https://mp.weixin.qq.com/s/e8sUwTBfgzXdCXd3ViCNdw)


## GOCN每日新闻--2021-07-06
1.GopherChina 2021 Ian 说完整泛型实现将在 Go1.18 发布 (会议实录) https://mp.weixin.qq.com/s/RFfa-A0DomH2pXz4arAVnA

2.ADBTuiFM-基于 tui 的 ADB 文件管理器  https://github.com/darkhz/adbtuifm

3.Semverbot 用 GoLang 编写的 semver 版本管理 CLI 工具 https://github.com/restechnica/semverbot

4.多 Goroutine 如何优雅处理错误？https://mp.weixin.qq.com/s/NX6kVJP-RdUzcCmG2MF31w

5.优化 Golang 分布式行情推送的性能瓶颈  https://mp.weixin.qq.com/s/DF8GeW2Nx3s9yjzcvEunJA


## gopherDaily--2021-07-06
1.Myreads：一个使用Go、React与Typescript、HarperDB、基于JWT的认证和Docker的数字书架 - https://pratikjagrut.hashnode.dev/myreads-a-digital-bookshelf-using-golang-react-with-typescript-harperdb-jwt-based-auth-and-docker

2.使用Go, Gin, MySQL和Docker开发blog项目 - https://dev.to/umschaudhary/blog-project-with-go-gin-mysql-and-docker-part-1-3cg1

3.用OpenTelemetry和Jaeger进行分布式追踪 - https://medium.com/@iqfarhad/distributed-tracing-with-opentelemetry-and-jaeger-e21e53b5c24e

4.OpenShift 4.8增加Serverless支持 - https://thenewstack.io/red-hat-openshift-4-8-adds-serverless-functions-pipelines-as-code/

5.如何在VS代码中打开任何Repo而不克隆它 - https://www.freecodecamp.org/news/you-can-now-edit-anything-on-github-in-vs-code-without-cloning/

6.单一云 vs 多云 + 混合云 - https://blog.min.io/monoclouds-vs-multiclouds-hybridclouds/

7.GitLab正在为DevSecOps设定标准 - https://about.gitlab.com/blog/2021/06/01/gitlab-is-setting-standard-for-devsecops/

8.什么是Polaris？Kubernetes开源配置验证 - https://www.cncf.io/blog/2021/07/01/what-is-fairwinds-polaris-kubernetes-open-source-configuration-validation/

9.探索k8s operator模式 - https://iximiuz.com/en/posts/kubernetes-operator-pattern/

## 码农桃花源--2021-07-06
### 文章分享

1.[https 开篇](https://halfrost.com/https-begin/)

2.[redis 哨兵 故障自动转移](https://hellokangning.github.io/zh/post/redis-sentinel-automatic-failover/)

3.[go性能优化](https://mp.weixin.qq.com/s/yX0hgIOLuaKsAcrWfOfcUQ)

### 面试题

1.什么是无状态协议，HTTP 是无状态协议吗，怎么解决

2.HTTPS 是如何建立连接的？其间交互了什么？

3.说说 HTTP/1.1 相比 HTTP/1.0 提高了什么性能？HTTP/2 做了什么优化？HTTP/3 做了哪些优化？


每日算法
「算法：「奇偶链表」：https://leetcode-cn.com/problems/odd-even-linked-list/

## go中文网每日资讯--2021-07-05


一、Go语言中文网

1. [在 Go 中我是如何组织包的](https://mp.weixin.qq.com/s/Y-tQ8AYMGHEgXphKVK1afA)

2. [Golang net/rpc 包的深度解读和学习](https://mp.weixin.qq.com/s/Ojm1FLtNG6ogVrUaaQzqVw)

二、亚军进化史

1. [Go技术日报(2021-07-04)——深入Go Module之未说的秘密](https://mp.weixin.qq.com/s/hvsYI-_9qw1OzBnOvlJy4w)

三、奇伢云存储

1. [深入理解 Linux 的 epoll 机制](https://mp.weixin.qq.com/s/LGMNEsWuXjDM7V9HlnxSuQ)

四、k8s技术圈

1. [Prometheus 中使用 PrometheusAlert 进行聚合报警](https://mp.weixin.qq.com/s/VF1P4lQ53NQciuvm2wPHBw)

2. [Pod 高性能网络分析|回放|云原生公开课](https://mp.weixin.qq.com/s/N7CE-IXainwcA6bwUTqYHA)

五、新亮笔记

1. [关于处理电商系统订单状态的流转，分享下我的技术方案（附带源码）](https://mp.weixin.qq.com/s/7xOeQKomT9GVTUghyZgaxA)

六、脑子进煎鱼了

1. [技巧分享：多 Goroutine 如何优雅处理错误？](https://mp.weixin.qq.com/s/NX6kVJP-RdUzcCmG2MF31w)

2. [惊呆了！Go 代码的第一次提交竟然是 1972 年。。。](https://mp.weixin.qq.com/s/InNA3e8UkpCJlE2fr-p9gA)

七、码农桃花源

1. [优化 Golang 分布式行情推送的性能瓶颈](https://mp.weixin.qq.com/s/DF8GeW2Nx3s9yjzcvEunJA)

八、Golang梦工厂

1. [面试官：你能聊聊string和[]byte的转换吗？](https://mp.weixin.qq.com/s/jztwFH6thFdcySzowXOH_Q)

九、技术岁月

1. [微服务注册中心分布式集群设计原理与 Golang 实现](https://mp.weixin.qq.com/s/xvI1hLqZ0ev1_l_vQMOsIg)

十、网管叨bi叨

1. [Golang官方限流器的用法详解](https://mp.weixin.qq.com/s/S3_YEyhLcaAUuaSabXdimw)

十一、polarisxu

1. [Go项目实战：从零构建一个并发文件下载器](https://mp.weixin.qq.com/s/MxjLrYfvgk5kdi43xm6kVA)

十二、Go招聘

1. [CloudFine多云转晴 寻找优秀的你](https://mp.weixin.qq.com/s/CzJSmvXrb7D6p6i1nxjH1A)


## GOCN每日新闻--2021-07-05
1.自建的视频网站管理器，支持 b 站，YouTube  https://github.com/horahoradev/horahora

2.golang pipeline 实战 https://itnext.io/golang-pipeline-in-practise-6007dafbb85f

3.简单 web 框架 dragon  https://github.com/azerothyang/dragon

4. golang 实现的 spotify 客户端  https://github.com/brianstrauch/spotify-cli

5. mock mongo-go-driver  https://medium.com/@victor.neuret/mocking-the-official-mongo-golang-driver-5aad5b226a78


## gopherDaily--2021-07-05
1.Myreads：一个使用Go、React与Typescript、HarperDB、基于JWT的认证和Docker的数字书架 - https://pratikjagrut.hashnode.dev/myreads-a-digital-bookshelf-using-golang-react-with-typescript-harperdb-jwt-based-auth-and-docker

2.使用Go, Gin, MySQL和Docker开发blog项目 - https://dev.to/umschaudhary/blog-project-with-go-gin-mysql-and-docker-part-1-3cg1

3.用OpenTelemetry和Jaeger进行分布式追踪 - https://medium.com/@iqfarhad/distributed-tracing-with-opentelemetry-and-jaeger-e21e53b5c24e

4.OpenShift 4.8增加Serverless支持 - https://thenewstack.io/red-hat-openshift-4-8-adds-serverless-functions-pipelines-as-code/

5.如何在VS代码中打开任何Repo而不克隆它 - https://www.freecodecamp.org/news/you-can-now-edit-anything-on-github-in-vs-code-without-cloning/

6.单一云 vs 多云 + 混合云 - https://blog.min.io/monoclouds-vs-multiclouds-hybridclouds/

7.GitLab正在为DevSecOps设定标准 - https://about.gitlab.com/blog/2021/06/01/gitlab-is-setting-standard-for-devsecops/

8.什么是Polaris？Kubernetes开源配置验证 - https://www.cncf.io/blog/2021/07/01/what-is-fairwinds-polaris-kubernetes-open-source-configuration-validation/

9.探索k8s operator模式 - https://iximiuz.com/en/posts/kubernetes-operator-pattern/



## go中文网每日资讯--2021-07-04


一、Go语言中文网

1. [一本 Go 新书](https://mp.weixin.qq.com/s/GfZxuc6zTVaeuAxmtQN_fQ)

2. [Go语言爱好者周刊：第 102 期](https://mp.weixin.qq.com/s/Sjeb3j1Un2mO-m_J-u1oNw)

3. [通过 Go 学习浮点数精度](https://mp.weixin.qq.com/s/ezMI6SZnb9uTrbmBu5EUDw)

二、亚军进化史

1. [Go技术日报(2021-07-02)——你真的了解 Load Balance 嘛？](https://mp.weixin.qq.com/s/QiN8bMAvLQz0wgFfAbCgXQ)

2. [Go技术日报(2021-07-03)——亿级系统的Redis缓存如何设计？？？](https://mp.weixin.qq.com/s/w21MZ5wBa6Ruw0uG8Hfo5Q)

三、奇伢云存储

1. [堆排序，怎么个堆法？](https://mp.weixin.qq.com/s/IWI3Gy_KhAshFiZaeaKl6w)

2. [Go timer 是如何被调度的？](https://mp.weixin.qq.com/s/F8-74FozAqD2dPkw9HrDHQ)

四、云原生技术爱好者社区

1. [关于多集群Kubernetes的一些思考](https://mp.weixin.qq.com/s/haBM1BSDWLhRYBJH4cJHvA)

五、TechPaper

1. [Go 语言中的一些非常规优化](https://mp.weixin.qq.com/s/X7OU9JjSThB5IZF_KVT1Jg)

六、鸟窝

1. [深入Go Module之未说的秘密](https://colobu.com/2021/07/04/dive-into-go-module-3/)

## GOCN每日新闻--2021-07-04

1.Golang 中的一些非常规优化 https://mp.weixin.qq.com/s/X7OU9JjSThB5IZF_KVT1Jg

2.使用 tableflip 实现应用的优雅热升级 https://gocn.vip/topics/12270

3.netlink 是 Go 和内核模块之间优秀的通信兵 https://gocn.vip/topics/12268

4.在 go 中实现一个 worker-pool https://mp.weixin.qq.com/s/0-cbZVAWgiTWIEcd4bInQA

5.亿级系统的 Redis 缓存如何设计 https://mp.weixin.qq.com/s/bkXnbQIpI_GdX4BHkAhPUA

## gopherDaily--2021-07-04
1.使用go-metrics在Go应用中增加度量 - https://t.zsxq.com/VzJURr7

2.使用Go从头开始编写一个时序数据库引擎 - https://nakabonne.dev/posts/write-tsdb-from-scratch/

3.如何在你的产品中加入eBPF的可观察性 - https://brendangregg.com/blog/2021-07-03/how-to-add-bpf-observability.html

4.经常提交，事后完善，一次发布：Git最佳实践 - https://sethrobertson.github.io/GitBestPractices/

5.cue项目迁移到github.com/cue-lang/cue - https://github.com/cue-lang/cue/issues/1078

6.创建Kubernetes mutating和validating网络钩子的Go框架 - https://github.com/slok/kubewebhook

7.Kubernetes的readiness探测–例子和常见的陷阱 - https://itnext.io/kubernetes-readiness-probes-examples-common-pitfalls-136e3a9a058d

8.因copilot滥用github用户代码数据而放弃github - https://thelig.ht/abandoning-github/

9.不为人知的SQLite的故事 - https://corecursive.com/066-sqlite-with-richard-hipp/

10.github copilot: 一个强大的、有争议的开发者自动完成器 - https://thenewstack.io/github-copilot-a-powerful-controversial-autocomplete-for-developers/


## go中文网每日资讯--2021-07-03


一、Go语言中文网

1. [重磅！Go 启用新的官方问答社区](https://mp.weixin.qq.com/s/sHDSK_HgjTiaDDYdrVSn9A)

2. [如何在 go 中实现一个 worker-pool?](https://mp.weixin.qq.com/s/0-cbZVAWgiTWIEcd4bInQA)

3. [Go面试中如果这样写二分查找！](https://mp.weixin.qq.com/s/pmUwpvPOPUciyVYAQLaYvg)

二、亚军进化史

1. [Go技术日报(2021-07-01)——Redis 和 Golang 的可扩展事件流](https://mp.weixin.qq.com/s/iLpBAxp7nTStdkLqpbR2mg)

三、网管叨bi叨

1. [亿级系统的Redis缓存如何设计？？？](https://mp.weixin.qq.com/s/bkXnbQIpI_GdX4BHkAhPUA)

四、奇伢云存储

1. [Go语言如何实现可重入锁？](https://mp.weixin.qq.com/s/AodhIH4HdIW0aFdhxeeuQA)

2. [从零实现一个 k-v 存储引擎](https://mp.weixin.qq.com/s/srCHe6hkiWL4Lg9OKFK-dA)

五、Golang梦工厂

1. [假如 Go 能说话，听听 GMP 的心声](https://mp.weixin.qq.com/s/BUuuw-hRWyPeAod5O2CkhQ)

六、Pearl的仲夏夜之梦

1. [浅析Golang的内存管理(二)](https://mp.weixin.qq.com/s/9O5XRoBWAgQ_PU7kVLVotQ)

七、k8s技术圈

1. [GitOps 持续部署工具 Argo CD 初体验](https://mp.weixin.qq.com/s/Hgp7N_HPkpFjfP_qcl4Fzg)

八、幼麟实验室

1. [深度探索Go语言(六)：抢占式调度(1)](https://mp.weixin.qq.com/s/5Ny7JFQKIjQbkb1A4gdySQ)

九、Go招聘

1. [给，你要的Go学习路线图来啦](https://mp.weixin.qq.com/s/rPKO23mHDGofeyzeCIHJxQ)




## GOCN每日新闻--2021-07-03

1.如何实现跨设备的双向连接？ Labo 涂鸦鸿蒙亲子版分布式开发技术分享 https://gocn.vip/topics/12264

2.徒手用 Go 写个 Redis 服务器 https://mp.weixin.qq.com/s/zK_As1RklzwSEV0hlf2fZw

3.从头开始编写时间序列数据库引擎 https://nakabonne.dev/posts/write-tsdb-from-scratch/

4.用于音乐创作的基于文本的编程语言 Alda2 发布 https://blog.djy.io/announcing-alda-2/

5.Google Map Android SDK 自定义 Marker，InfoWindow https://juejin.cn/post/6980556734234361887

## gopherDaily--2021-07-03
1.将Keras模型打包到Go二进制文件中提供服务 - https://sdeoras.medium.com/building-go-binaries-with-tensorflow-on-packaging-a-keras-model-for-serving-15cd5f9d9e40

2.经典旧文：构建更小的Go二进制文件 - https://www.pixelstech.net/article/1576288399-GoLang-to-build-smaller-executable-file

3.播客：通过pop quiz来学习Go - https://changelog.com/gotime/186

4.Ultimate Go Notebook最终版 - https://education.ardanlabs.com/courses/ultimate-go-notebook

5.非关系数据库的进化历程 - https://www.techrepublic.com/google-amp/article/non-relationals-quiet-revolution-in-databases/

6.Linux基金会：为什么开放源代码现在需要做研究 - https://thenewstack.io/linux-foundation-research-why-open-source-needs-it-now/

7.一文读懂Thanos多集群监控 - https://mp.weixin.qq.com/s/RP-NoPsStFflCACZrDFa9g

8.在生产中学习机器学习的建议：汇集了一些书籍、课程和资源库 - https://elvissaravia.substack.com/p/my-recommendations-to-learn-machine


## go中文网每日资讯--2021-07-02


一、Go语言中文网

1. [全面分析Uber的高性能日志库Zap](https://mp.weixin.qq.com/s/ghCINPYXo7Xsm_aIXhlbmA)

2. [听说Mutex源码是出名的不好看，我不信，来试一下](https://mp.weixin.qq.com/s/gLnKwcSjjR1aCsuhiJZOfg)

二、亚军进化史

1. [Go技术日报(2021-07-01)——Redis 和 Golang 的可扩展事件流](https://mp.weixin.qq.com/s/iLpBAxp7nTStdkLqpbR2mg)

三、polarisxu

1. [惊呆了！Go 代码的第一次提交竟然是 1972 年。。。](https://mp.weixin.qq.com/s/LlX1a2DoaYjTEChc7Dbyqg)

四、董泽润的技术笔记

1. [你真的了解 Load Balance 嘛](https://mp.weixin.qq.com/s/nif6blio5ksQNbOF5hfsSQ)

五、高可用架构

1. [聊聊知乎订单系统迁移](https://mp.weixin.qq.com/s/x9MfWM2yzTf-CMPJLE01Tw)

六、杨旭技术专栏

1. [[Go语言] 检查枚举值的合理性](https://mp.weixin.qq.com/s/aFioobOWlWtl3kWB14Pclw)

七、吴亲强的深夜食堂

1. [如何在 go 中实现一个 worker-pool?](https://mp.weixin.qq.com/s/VEevmkq2cbYUakYO1zvU9Q)

八、GoUpUp

1. [Go 每日一库之 colly](https://mp.weixin.qq.com/s/L8BmzqbuptCEgU9468C6ig)

九、Go招聘

1. [回响科技招聘 | 潮玩社区由你来打造](https://mp.weixin.qq.com/s/utVTOWRpD6hQoDTyIH1-JA)

## GOCN每日新闻--2021-07-02

1.『每周译 Go』硬件内存模型 https://mp.weixin.qq.com/s/t0mWCya8DH0hXl21viAIRA

2.函数传递指针真的比传值效率高吗 https://juejin.cn/post/6979939230810112030

3.请不要使用==符号比较哈希密码 https://nowhereref.com/posts/please-dont-use-equal-operator-when-comparing-password-hashes/

4.Gopher China 2021 https://mp.weixin.qq.com/s/m_qmqOKmRNqW5omrJ6ZxsA

5.听说 Mutex 源码是出名的不好看，我不信，来试一下 https://mp.weixin.qq.com/s/kTlpaV22vaprJSEZy8KPsw



## gopherDaily--2021-07-02
1.github copilot的Go编码实践 - https://github.com/Pisush/copilot-go-experiments

2.构建和保护Go和Gin开发的网络应用程序 - https://developer.okta.com/blog/2021/02/17/building-and-securing-a-go-and-gin-web-application

3.编写高质量的Go应用程序的三种方法 - https://www.cobyeastwood.com/posts#writingProgramsInGolang

4.油管视频：为事件驱动的系统设计有效载荷 - https://www.youtube.com/watch?v=tn7I17XlNEI

5.golang 垃圾回收器如何标记内存？ - https://mp.weixin.qq.com/s/4mGWTzxvWMqGxgoHf4o2jA

6.解密Go的fmt.Sprintf和Printf - https://faun.pub/golangs-fmt-sprintf-and-printf-demystified-4adf6f9722a2

7.全链路压测体系建设方案的思考与实践 - https://mp.weixin.qq.com/s/BF8Q6eiLZyESMyPovk70jw




## go中文网每日资讯--2021-07-01
一、Go语言中文网

1. [Go 字符串中的潜在问题](https://mp.weixin.qq.com/s/_ScaGaB8mr2aSyQjL-VIaA)

2. [Go 每日一库之 ants](https://mp.weixin.qq.com/s/wjs6GJsK6c31rb_QbNATRg)

二、亚军进化史

1. [Go技术日报(2021-06-30)——深入Go Module](https://mp.weixin.qq.com/s/nN-qAHBEbP0AahwS6z7xPg)

三、k8s技术圈

1. [Prometheus Discovery 之 K8S 代码分析](https://mp.weixin.qq.com/s/0QWCFM6aeprb3JfW82wVMA)

四、CloudNativeCommunity

1. [《Istio 大咖说》直播回放 | 腾讯云服务网格生产落地最佳实践](https://mp.weixin.qq.com/s/7EezmabChBTN7flSs2S42A)

五、奇伢云存储

1. [Go语言的IO库那么多，我该怎么选？](https://mp.weixin.qq.com/s/l-l2GFsuNWxJiXg2xSnBwA)

六、脑子进煎鱼了

1. [《漫谈 MQ》设计 MQ 的 3 个难点](https://mp.weixin.qq.com/s/_QZ1mOtSFECab7TkvPePvQ)

2. [自制文件系统 — 来看看文件系统的样子](https://mp.weixin.qq.com/s/7qq3AugMKqjlwx26PT20sw)

七、码农桃花源

1. [从 wiscKey 看 LSMtree 的不足](https://mp.weixin.qq.com/s/HRyak0gNdeisf0KpoY4lsA)

八、GoOfficialBlog

1. [官方 Go Collective 入驻 Stack Overflow](https://mp.weixin.qq.com/s/VRnm5yIQDDGRG0yimNgi-g)

九、腾讯云原生

1. [云原生应用负载均衡系列 (2): 入口流量分发、容错与高可用调度](https://mp.weixin.qq.com/s/0f9Z8yIsT7-iJ2AUHfgqiw)



## GOCN每日新闻--2021-07-01

1.减少 Golang 程序的内存分配 https://chris124567.github.io/2021-06-21-go-performance/

2.Redis 和 Golang 的可扩展事件流 https://ably.com/blog/event-streaming-with-redis-and-golang

3.Go context 入门学习 https://dev.to/gopher/getting-started-with-go-context-l7g

4.Golang 底层实现系列——map 的底层实现 https://segmentfault.com/a/1190000040269520

5.通过浏览器运行 cmd 命令、启动 steam https://juejin.cn/post/6979391468309839879

## gopherDaily--2021-07-01

1.硬件内存模型[译] - https://colobu.com/2021/06/30/hwmm/

2.请不要在比较密码哈希值时使用等值比较运算符 - https://nowhereref.com/posts/please-dont-use-equal-operator-when-comparing-password-hashes/

3.使用Go开发代码的原因 - https://dev.to/abdadeel/reason-for-developing-in-go-5g0c

4.2021年最具进步性的编程技术 - https://www.instinctools.com/blog/top-most-progressive-programming-technologies-in-2021

5.经典旧文：神秘的SetFinalizer - https://lk4d4.darth.io/posts/finalizers/

6.新的勒索软件突出了网络攻击者对Golang语言的广泛采用 - https://www.zdnet.com/article/this-new-malware-highlights-widespread-adoption-of-golang-language-by-cyberattackers/

7.Golang vs. Node.js: 谁在后端框架之战中胜出？- https://javascript.plainenglish.io/golang-vs-node-js-who-trumps-the-battle-of-backend-frameworks-e5fc31faa3b5

8.https://ploffay.medium.com/five-years-evolution-of-open-source-distributed-tracing-ec1c5a5dd1ac

9.公布Kubernetes社区小组年度报告 - https://kubernetes.io/blog/2021/06/28/announcing-kubernetes-community-group-annual-reports/

10.Go语言批判列表 - https://github.com/ksimka/go-is-not-good

## 码农桃花源--2021-07-01
### 文章分享

1.[MQ 面试题](https://www.yuque.com/u2278269/gq5x74/zi680f)

2.[漫谈MQ](https://mp.weixin.qq.com/s/_QZ1mOtSFECab7TkvPePvQ)

3. [云原声](https://mp.weixin.qq.com/s/yX0hgIOLuaKsAcrWfOfcUQ)

### 面试题

1.在使用 MQ 消息队列时，如何确保消息不丢失？ 


2.怎么解决消息被重复消费的问题？


3.如何处理消息积压问题？


### 每日算法
「路径总和（非递归）」: https://leetcode-cn.com/problems/path-sum/



## go中文网每日资讯--2021-06-30

一、Go语言中文网

1. [知乎热议：java太卷了，要不要转go啊？](https://mp.weixin.qq.com/s/Hb41qkaUTaXCCZrhQSO0QQ)

2. [validator库你知多少？govalidator了解一下](https://mp.weixin.qq.com/s/AYfMAfHbFX40EQyLMbQ5EQ)

3. [小技巧！k8s 环境下调试服务](https://mp.weixin.qq.com/s/cfMC02OgArnxgPrjAM_4NQ)

二、亚军进化史

1. [Go技术日报(2021-06-29)——深入理解Kafka的设计思想](https://mp.weixin.qq.com/s/xRfXGJVyXGvHlnycUH8xlA)

三、polarisxu

1. [这本 Go 新书挺期待的](https://mp.weixin.qq.com/s/ZDMHec34ixqMaVo365InHg)

四、APISIX云原生微服务网关

1. [差之毫厘：etcd 3 完美支持 HTTP 访问？](https://mp.weixin.qq.com/s/BS69w8aJdK2B6IJYN4g0AQ)

五、后端技术指南针

1. [图解|深入理解跳表及其在Redis中的应用](https://mp.weixin.qq.com/s/0Pm1n-tHGSRUht8bWVGjWQ)

六、鸟窝

1. [深入Go Module之go.mod文件解析](https://colobu.com/2021/06/28/dive-into-go-module-1/)

2. [深入Go Module之讨厌的v2](https://colobu.com/2021/06/28/dive-into-go-module-2/)

七、HHFCodeRv

1. [开发中的一些坑](https://mp.weixin.qq.com/s/HR3ZrByrc50Pl3B52lvJcQ)

八、Golang来啦

1. [gRPC入门指南 — 双向流式RPC（四）](https://mp.weixin.qq.com/s/a5QxxEoyVwq-lnJR8dLlAA)

九、Go招聘

1. [Go中的error居然可以这样封装](https://mp.weixin.qq.com/s/q2VrY8ksNsmYzvqhUNv72A)

## GOCN每日新闻--2021-06-30

1.TiDB Operator 源码阅读 (四) 组件的控制循环 https://gocn.vip/topics/12253

2.golang 垃圾回收器如何标记内存？ https://mp.weixin.qq.com/s/4mGWTzxvWMqGxgoHf4o2jA

3.深入 Go 语言内部做技术优化，我学到了什么？https://mp.weixin.qq.com/s/HuGudn8ViKXAz0mIawquyQ

4.通过实例理解 Go Execution Tracer https://mp.weixin.qq.com/s/L7HiqA02g-l-b2pD6aRtbw

5.Go timer 是如何被调度的？https://mp.weixin.qq.com/s/eRWPdWWBDyc9TZHB3u197Q


## gopherDaily--2021-06-30
1.硬件内存模型: 为Go内存模型的演化建立背景 by Russ Cox - https://research.swtch.com/hwmm#introduction

2.实现Go流水线模式 - https://zhimin-wen.medium.com/golang-pipeline-in-practise-6007dafbb85f

3.用于音乐创作的基于文本的编程语言Alda2发布 - https://blog.djy.io/announcing-alda-2/

4.Go: sync.Map的LoadAndDelete和LoadOrStore。为什么需要它们？- https://dev.to/sreramk/go-loadanddelete-and-loadorstore-in-sync-map-why-are-they-needed-30f7

5.如何在Linux上建立一个etcd集群 - 初学者指南 - https://devopscube.com/setup-etcd-cluster-linux/

6.开放源代码许可证：谁掌握着权力？ - https://thenewstack.io/open-source-licenses-who-holds-the-power/

## go中文网每日资讯--2021-06-29


一、Go语言中文网

1. [在 Go 中编写令人愉快的 HTTP 中间件](https://mp.weixin.qq.com/s/ZUdUdlrnndcCZnjwqC6PcQ)

2. [这个好：Go 中国开发者团队](https://mp.weixin.qq.com/s/wTtmY0c_ykzND33fhiwXYQ)

二、亚军进化史

1. [Go技术日报(2021-06-28)——Gopher China 2021](https://mp.weixin.qq.com/s/srDX0D5vI0hi95uWHOnbFg)

三、k8s技术圈

1. [Longhorn 微服务化存储初探](https://mp.weixin.qq.com/s/05o3zUbxWOzKp8xhvtAL7Q)

四、Go夜读

1. [第 117 期详解开源项目 rosedb 及存储模型](https://mp.weixin.qq.com/s/YHQapaVsMuEozewtnaehWw)

五、脑子进煎鱼了

1. [Go1.17 快报之标准库越来越注重易用性](https://mp.weixin.qq.com/s/MfiITK7gEe3hED5cZjRzJQ)

六、polarisxu

1. [详解 Go 空结构体的 3 种使用场景](https://mp.weixin.qq.com/s/qqfzFcLhb4SZjHLsYUqEHQ)

七、奇伢云存储

1. [深入理解Kafka的设计思想](https://mp.weixin.qq.com/s/vqC6qiT2SIvU4HPtEDyk2w)

2. [大厂Golang语法50问!](https://mp.weixin.qq.com/s/gUPkqXi2FFrlC6IeMixAMg)

八、MoeLove

1. [10+款Redis容器化技术选型对比，K8S并非万金油](https://mp.weixin.qq.com/s/Njx43Atvf2QIKAtOCABLfA)

九、CloudNativeCommunity

1. [有了 NGINX 和 Kong，为什么还需要 Apache APISIX？](https://mp.weixin.qq.com/s/GVs3X1i5kW0QtXvtqdXBiw)

十、Go招聘

1. [看了这篇 Go map 并发不用慌](https://mp.weixin.qq.com/s/EZeNJPPiaHLbRfg5Hm0ohg)

2. [【北京|深圳-腾讯微视】短视频Top企业招聘Gopher](https://mp.weixin.qq.com/s/qnh5LdNtVShO0qizWc7EJQ)


## GOCN每日新闻--2021-06-29

1.内存屏障 https://github.com/cch123/golang-notes/blob/master/memory_barrier.md

2.深入 Go Module 之讨厌的 v2 https://colobu.com/2021/06/28/dive-into-go-module-2/

3.Go 每日一库之 resty https://segmentfault.com/a/1190000040247099?utm_source=tag-newest

4.哈啰在分布式消息治理和微服务治理中的实践 https://gocn.vip/topics/12235

5.Go 初始化流程分析 https://juejin.cn/post/6969230952685895694

## gopherDaily--2021-06-29
1.通过实例理解Go Execution Tracer - https://mp.weixin.qq.com/s/L7HiqA02g-l-b2pD6aRtbw

2.理解go.mod和go.num - https://janteshital.medium.com/understanding-go-mod-and-go-sum-5fd7ec9bcc34

3.Fackbook Ent框架支持集成gPRC - https://entgo.io/blog/2021/06/28/gprc-ready-for-use/

4.通俗解释一下什么是Go并发工作池模式 - https://itnext.io/explain-to-me-go-concurrency-worker-pool-pattern-like-im-five-e5f1be71e2b0

5.Pinterest的Kubernetes扩展实战 - https://medium.com/pinterest-engineering/scaling-kubernetes-with-assurance-at-pinterest-a23f821168da

6.iptables和ipvs模式下的kube-proxy性能比较 - https://www.projectcalico.org/comparing-kube-proxy-modes-iptables-or-ipvs/

7.YoMo：一个开源的流式无服务器框架，用于构建低延迟的边缘计算应用 - https://github.com/yomorun/yomo

8.DevSecOps：为什么不应该为了速度而牺牲安全？ - https://thenewstack.io/devsecops-why-security-shouldnt-be-sacrificed-for-speed/

9.审视现代企业的GitOps - https://thenewstack.io/a-look-at-gitops-for-the-modern-enterprise/

10.用Docker的Buildx将Kubernetes驱动构建时间减少一半 - https://releasehub.com/blog/cutting-build-time-in-half-docker-buildx-kubernetes

11.devops管道与Kubernetes认证 - https://www.tremolosecurity.com/post/pipelines-and-kubernetes-authentication



## 码农桃花源--2021-06-29
### 文章分享

- [redis ](https://mp.weixin.qq.com/s/k8agEub4qmhm3kX_TpETrA)


- [go map并发](https://mp.weixin.qq.com/s/EZeNJPPiaHLbRfg5Hm0ohg)


- [go 设计模式 结构型 桥接模式](https://lailin.xyz/post/bridge.html)

- [http与https](https://www.cnblogs.com/xiaolincoding/p/12442435.html)


### 面试题

1.详细讲一下拥塞控制？ 

2.详细讲一下拥塞控制？HTTPS 解决了 HTTP 的哪些问题？

3.HTTPS 是如何解决上面的三个风险的


### 每日算法

「路径总和（非递归）」：https://leetcode-cn.com/problems/path-sum/


## go中文网每日资讯--2021-06-28


一、Go语言中文网

1. [在 Golang 中使用 -w 和 -s 标志](https://mp.weixin.qq.com/s/aPP1Eb6jEJS7oKy4KZLI4g)

2. [Go 监听信号退出并回收资源](https://mp.weixin.qq.com/s/Ca5ZG33NgIkKPSyVivwdsg)

二、亚军进化史

1. [Go技术日报(2021-06-27)——Gopher China2021大会观感](https://mp.weixin.qq.com/s/pM-5gXM2B1gxnQwoXIOGRA)

三、k8s技术圈

1. [K8s遇上Jenkins&amp;制品库](https://mp.weixin.qq.com/s/gjMZhVPhROPA49KFVcMgjA)

四、奇伢云存储

1. [自制文件系统 —— 05 总结：一切都为了狙击“文件”](https://mp.weixin.qq.com/s/x7WZmFULZ1AKXu6Kgw0P-Q)

五、polarisxu

1. [推荐三个Go实战开源项目](https://mp.weixin.qq.com/s/v_wonIeuxQWT_qPTGv7GIw)

六、TonyBai

1. [通过实例理解Go Execution Tracer](https://mp.weixin.qq.com/s/L7HiqA02g-l-b2pD6aRtbw)

七、董泽润的技术笔记

1. [我看 Gopher China 2021](https://mp.weixin.qq.com/s/Velw1jpnmsbX44G9CSBL3A)

八、Golang梦工厂

1. [学习channel设计：从入门到放弃](https://mp.weixin.qq.com/s/E2XwSIXw1Si1EVSO1tMW7Q)

九、章老师说

1. [Gopher China 分享：深入理解BFE](https://mp.weixin.qq.com/s/m8lXEnGIcApe8mrlNUmmCw)

十、TechPaper

1. [Gopher China 2021](https://mp.weixin.qq.com/s/m_qmqOKmRNqW5omrJ6ZxsA)

十一、Pearl的仲夏夜之梦

1. [浅析Golang的内存管理(一)](https://mp.weixin.qq.com/s/Y8m3tOOpUMFQGyq897oYiA)

十二、Go招聘

1. [Aibee开放大量Golang职位，快来和小姐姐做同事喽！](https://mp.weixin.qq.com/s/MD71qYFeCXQOrRgRvbgjUQ)



## GOCN每日新闻--2021-06-28
1.100 个 Go 经典错误 https://medium.com/solvingalgo/100-go-mistakes-2022-4debd9449a72

2.减少你的 Go 程序内存占用 https://chris124567.github.io/2021-06-21-go-performance/

3.深入浅出 Go 并发工作池 https://itnext.io/explain-to-me-go-concurrency-worker-pool-pattern-like-im-five-e5f1be71e2b0

4.具有位图索引的内存列存储工具 column https://github.com/kelindar/column

5.单机限流器 time/rate 库 https://gocn.vip/topics/12239


## 码农桃花源--2021-06-28
### 文章分享

1.[如何在容器中做时间漫游者](https://mp.weixin.qq.com/s/c1MNwLIs6Z6luQiQmReJ7g)


2.[channel底层实现] https://halfrost.com/go_channel/


3.[go 设计模式 结构型 代理模式] https://lailin.xyz/post/proxy.html


### 面试题

1.为什么客户端的 TIME-WAIT 状态必须等待 2MSL 

2.TIME-WAIT 状态过多会产生什么后果？怎样处理

3.详细讲一下TCP的滑动窗口


### 每日算法

「寻找旋转排序数组中的最小值」：https://leetcode-cn.com/problems/find-minimum-in-rotated-sorted-array/


## go中文网每日资讯--2021-06-27


一、Go语言中文网

1. [Go1.17 快报之标准库的易用性](https://mp.weixin.qq.com/s/aE81r1Wc9a41b9GUsZ2qvw)

2. [Go语言爱好者周刊：第 101 期 — Go Team 休假两周。。。](https://mp.weixin.qq.com/s/oM61Mk0Ut6xgPjKV8TeLLg)

3. [Go timer 是如何被调度的？](https://mp.weixin.qq.com/s/eRWPdWWBDyc9TZHB3u197Q)

二、亚军进化史

1. [Go技术日报(2021-06-26)——分布式锁实现原理与最佳实践](https://mp.weixin.qq.com/s/AvEIWwa6cpDHoqr7F2g5ZA)

三、新亮笔记

1. [我是怎么写 Git Commit message 的？](https://mp.weixin.qq.com/s/PuYEiaI4T3VFJMhi-_qQ8w)

四、k8s技术圈

1. [使用 Tekton 重构自动化流水线](https://mp.weixin.qq.com/s/2tS_SsYYr5lm-BYpLw88ig)

五、polarisxu

1. [这个好：Go 中国开发者团队](https://mp.weixin.qq.com/s/_qigE7lAYMln-aayUzscWA)

六、GoUpUp

1. [Go 每日一库之 resty](https://mp.weixin.qq.com/s/ye9hlsGP9q-CkTCChZOY2g)

七、golang算法架构leetcode技术php

1. [Gopher China2021大会观感(day2)](https://mp.weixin.qq.com/s/EO0qsCBHVPl-HQb3HhS4Cg)

2. [Gopher China2021大会首日观感](https://mp.weixin.qq.com/s/O2-ronZUyl6JjHbNobnt-g)

八、Go招聘

1. [为什么Redis集群有16384个槽？](https://mp.weixin.qq.com/s/dDlOLTHDYt1nr0Ke_tVRtg)

## gopherDaily--2021-06-27
1.播客：测试驱动开发（TDD）如何帮助你写出更好的Go代码 - https://changelog.com/gotime/185

2.Go的隐秘世界：Go程序的启动和runtime初始化 - https://zhuanlan.zhihu.com/p/241308426

3.Go核心团队进入安静周（6.26 ~ 7.11），- https://github.com/golang/go/issues/46934

4.Go命令行实用命令 - https://github.com/nikolaydubina/go-recipes

5.Go开发者的Docker workshop - https://contribute.docker.com/docs/communityleaders/eventhandbooks/go/

6.编写Go单元测试：testify入门 - https://medium.com/nerd-for-tech/writing-unit-tests-in-golang-part-1-introducing-testify-c0d458442412

7.经典旧文：go代码性能调试 - https://software.intel.com/content/www/us/en/develop/blogs/debugging-performance-issues-in-go-programs.html

8.WebAssembly现状报告2021 - https://blog.scottlogic.com/2021/06/21/state-of-wasm.html

9.使用Tekton的云原生CI/CD 构建自定义任务 - https://itnext.io/cloud-native-ci-cd-with-tekton-building-custom-tasks-663e63c1f4fb

10.OpenShift中的gRPC或HTTP/2入口连接 - https://www.openshift.com/blog/grpc-or-http/2-ingress-connectivity-in-openshift







## go中文网每日资讯--2021-06-26


一、Go语言中文网

1. [Go 问题排查实战: 请求无响应](https://mp.weixin.qq.com/s/-RmAIuPwT-bAwdKriwMg-w)

2. [小技巧！Mac 环境下编译 Go 服务](https://mp.weixin.qq.com/s/XQ2D5OpxkUSH2V_MR3Htmg)

3. [Go：神奇的init函数](https://mp.weixin.qq.com/s/xag2pzC8LDqhcjcXeNxVrA)

二、亚军进化史

1. [Go技术日报(2021-06-25)——Go语言微服务开发快速上手指南](https://mp.weixin.qq.com/s/ZgPRQm3Cuy-fHXTQq3hTYw)

2. [Go技术日报(2021-06-24)——Go gctrace引起 runtime 调度阻塞](https://mp.weixin.qq.com/s/w5HP-zMO3RZ-VMv7parFDw)

三、k8s技术圈

1. [KubeSphere Helm 应用仓库源码分析](https://mp.weixin.qq.com/s/aXN-VHomqYuivch1hOrV4w)

四、云原生技术爱好者社区

1. [工业互联网大数据中心使用 KubeEdge 实践](https://mp.weixin.qq.com/s/iM8AUzvdhNuDA1yHYcfLHQ)

五、码农桃花源

1. [参加了 Go 贡献者大会](https://mp.weixin.qq.com/s/p7Ggli11gC8xkoxMi9UXaQ)

六、Pearl的仲夏夜之梦

1. [浅析Golang的调度器(一)](https://mp.weixin.qq.com/s/X1-zYDjINmJEWFYhBzSvEQ)

2. [《Kubernetes In Action》阅读笔记(二)](https://mp.weixin.qq.com/s/Ik3MSHBbmitAq8qt7B3joQ)

七、luozhiyun很酷

1. [1.深入TiDB：初见TiDB](https://mp.weixin.qq.com/s/25OMDwCiXxbWytnHrV_gBQ)

八、Go招聘

1. [带有WebUI的HTTP Benchmark小工具你用过吗？](https://mp.weixin.qq.com/s/JQA4Noq2FQYISKJRwtl99A)


## GOCN每日新闻--2021-06-26

1.Go 1.17 弃用了 'go get'的传统用法 https://utcc.utoronto.ca/~cks/space/blog/programming/GoAndDeprecatingGoGet

2.用 Go 复制 MySQL 所有功能的替代品 https://www.dolthub.com/blog/2021-06-21-copying-mysqls-dumb-decisions/

3.在你的 Android 手机上运行 Golang 程序 https://mp.weixin.qq.com/s/EFHmjoTh0ji9Zc_YS6aPoQ

4.分布式锁实现原理与最佳实践 https://mp.weixin.qq.com/s/M92bQQ4ESeE-RkiPiu-oRw

5.Go 语言的 IO 库那么多，我该怎么选？https://mp.weixin.qq.com/s/TtN6NZ8hQ2AIf0C8wVzkjA



## gopherDaily--2021-06-26
1.Go 1.17将废除 “go get “的传统用法 - https://utcc.utoronto.ca/~cks/space/blog/programming/GoAndDeprecatingGoGet

2.用Go建立一个成功的创业公司 - https://goingwithgo.com/2021/06/building-successful-startups-with-go/

3.减少Go中内存分配的实践技巧 - https://chris124567.github.io/2021-06-21-go-performance/

4.Diretiv：基于Kubernetes和Knative上运行的无服务器工作流和自动化引擎 - https://github.com/vorteil/direktiv

5.Go实现的交互式shell - https://github.com/elves/elvish

6.wiretrustee: 将您的设备连接到一个基于WireGuard的安全私有网状网络 - https://github.com/wiretrustee/wiretrustee

7.Kubernetes API Server增加tracing(基于OpenTelemetry) - https://github.com/kubernetes/kubernetes/pull/94942

8.私有云与公共云：k8s是如何改变平衡的 - https://thenewstack.io/private-vs-public-cloud-how-kubernetes-shifts-the-balance/

9.使用Notary和OPA确保Kubernetes上的内容信任 - https://siegert-maximilian.medium.com/ensure-content-trust-on-kubernetes-using-notary-and-open-policy-agent-485ab3a9423c

10.如何使技术面试不那么糟糕 - https://thenewstack.io/how-to-make-tech-interviews-suck-less/



## go中文网每日资讯--2021-06-25
一、Go语言中文网

1. [Go: GC 是怎样监听你的应用的？](https://mp.weixin.qq.com/s/Nqr096q51NWbyN6VujFTzA)

2. [面试官：你能用Go写段代码判断当前系统的存储方式吗？](https://mp.weixin.qq.com/s/RrpGbu5ld9mQect6vNExoQ)

二、MoeLove

1. [更优雅的 Kubernetes 集群事件度量方案](https://mp.weixin.qq.com/s/0V_qTDCgDoUWBiFYRSK_Ag)

2. [[译]数据包在 Kubernetes 中的一生（3）](https://mp.weixin.qq.com/s/7z_fUgxwKfDzetJcOxDDRQ)

三、脑子进煎鱼了

1. [注释竟然还有特殊用途？一文解惑 //go:linkname 指令](https://mp.weixin.qq.com/s/_d1Q0Sx_KPrzEd4psPccMg)

四、码农桃花源

1. [分析 Go time.After 引起内存暴增 OOM 问题](https://mp.weixin.qq.com/s/jaIdqF0bFpHz_eyPsHjbwQ)

五、GoUpUp

1. [Go 每日一库之 dateparse](https://mp.weixin.qq.com/s/n9P65sFgfZF8Bbkc2-fhkA)

六、polarisxu

1. [重磅！Go 启用新的官方问答社区](https://mp.weixin.qq.com/s/nEWD2SBzTpCTe_kmpq2c1w)

七、Go招聘

1. [有问题，上知乎。找Gopher，来Go招聘](https://mp.weixin.qq.com/s/LZCpRFDgYFiuJOSE0GENPw)

## GOCN每日新闻--2021-06-25
1.项目中如何内嵌 Submodule https://medium.com/@RashadAnsari/working-with-go-sub-module-as-a-library-93e5db59a0f2

2.Go 语言微服务开发快速上手指南 https://kaushalprajapati-25586.medium.com/golang-project-starter-60bfbbe63845

3.为你的 Go 应用创建轻量级 Docker 镜像 http://www.cnblogs.com/you-men/p/14929232.html

4.TDD 是如何帮助我们更好地开发 Go 代码,原理与实践 https://changelog.com/gotime/185

5.Google 提出开源软件漏洞处理框架 https://security.googleblog.com/2021/06/announcing-unified-vulnerability-schema.html

## gopherDaily--2021-06-25
- 1.黑带Go程序员 - https://bitfieldconsulting.com/golang/black-belt
- 2.谷歌宣布宣布开放源代码的统一漏洞模式 - https://security.googleblog.com/2021/06/announcing-unified-vulnerability-schema.html
- 3.容忍容器镜像仓库的故障 - https://blog.kintone.io/entry/neco-registry
- 4.红帽：人为错误是导致Kubernetes安全事故的主要原因 - https://thenewstack.io/red-hat-human-error-a-leading-cause-of-kubernetes-security-mishaps/
- 5.分布式追踪是个麻烦事，原因在此 - https://thenewstack.io/distributed-tracing-is-a-hassle-heres-why/
- 6.字节开源的高性能json编解码包 - https://github.com/bytedance/sonic
- 7.深度 | 字节跳动微服务架构体系演进 - https://zhuanlan.zhihu.com/p/382833278
- 8.JWT对用户会话是危险的–有一个解决方案 - https://redislabs.com/blog/json-web-tokens-jwt-are-dangerous-for-user-sessions/
- 9.Windows 11介绍 - https://blogs.windows.com/windowsexperience/2021/06/24/introducing-windows-11/
- 10.随着区块链炒作的消退，开发者对以太坊进行了认真的研究 - https://thenewstack.io/as-blockchain-hype-fades-developers-give-ethereum-a-serious-look/

## 码农桃花源--2021-06-25
### 文章分享

- [channel 实现](https://halfrost.com/go_channel/)


- [计算机网络常见面试题](https://mp.weixin.qq.com/s/xzPcrw5Eh3P-9NtnGd5ycg)


- [go 设计模式三  原型模式](https://lailin.xyz/post/prototype.html)


### 面试题

1.计算机网络的各层协议及作用？

2.为什么需要三次握手，而不是两次？或者是四次

3.什么是 SYN洪泛攻击？如何防范？


### 每日算法

「字符串转换整数」：https://leetcode-cn.com/problems/string-to-integer-atoi/


## go中文网每日资讯--2021-06-24
一、Go语言中文网

1. [图解 Go GC 内存标记法](https://mp.weixin.qq.com/s/t3SffaVmHUb_vqB9pn5yqA)

2. [Go 语言保姆级教程（2021版下）](https://mp.weixin.qq.com/s/cSoPfFxPP7rR9AtDnSVWrg)

二、亚军进化史

1. [Go技术日报(2021-06-23)——一文深入理解 Kubernetes](https://mp.weixin.qq.com/s/04tZOu6G7fNIauSH1apyEw)

三、k8s技术圈

1. [Kubernetes 持续交付工作流管理软件 - Devtron](https://mp.weixin.qq.com/s/FFLUe-Uzw0ucEnpA2fIlOA)

四、码农桃花源

1. [Go gctrace引起 runtime 调度阻塞](https://mp.weixin.qq.com/s/eHEvVzmpPYXAQgcdd_B55w)

五、polarisxu

1. [这是要干嘛？！微软招 Go 编译器全职开发人员](https://mp.weixin.qq.com/s/gKeFG5mCLUsmXPPWratSGw)

六、CloudNativeCommunity

1. [《Istio 大咖说》第4期回放及问答整理|百度的 Istio 大规模生产落地实践](https://mp.weixin.qq.com/s/REJdsvwaiW7ZgFy5ATQRtA)

七、脑子进煎鱼了

1. [用 Go 来了解一下 Redis 通讯协议](https://mp.weixin.qq.com/s/pLwRiG1H_EAANadzz3VaLg)

八、Go招聘

1. [50KGopher的面试题是什么样的？](https://mp.weixin.qq.com/s/BXazVYFpDWKKQj9taRNc_g)

九、Golang来啦

1. [gRPC入门指南 — 客户端流式RPC（三）](https://mp.weixin.qq.com/s/06IQa335XPXDRa2qoz9mRg)

## GOCN每日新闻--2021-06-24
1.使用 Go 泛型的函数式编程 https://gocn.vip/topics/12233

2.一文读懂 eBPF 对 Kubernetes 可观测的重要性 https://mp.weixin.qq.com/s/xsCvDbCuVyn6kT2BFtHAjg

3.Golang 语言中的 channel 实现原理 https://mp.weixin.qq.com/s/6Q4lqlIBWl2g-EqU-M-rHw

4.Go 性能工具小抄 https://gocn.vip/topics/12198

5.23 种设计模式的 Go 语言实现（二）https://bbs.huaweicloud.com/blogs/280291


## gopherDaily--2021-06-24
1.通过实例理解Go Execution Tracer - https://t.zsxq.com/fYnIQ3N

2.为什么企业应该使用Go编程语言？ - https://mobisoftinfotech.com/resources/blog/why-companies-use-golang/

3.Go在stackoverflow建立官方文档频道 - https://blog.golang.org/stackoverflow

4.devtron: k8s软件交付工作流 - https://github.com/devtron-labs/devtron

5.致gohugo的情书 - https://akondas.com/blog/a-love-letter-to-hugo/#netlify-is-beautiful

6.GoFiber：Express框架的高性能替代品 - https://dev.to/karanpratapsingh/introduction-to-go-fiber-2m0a

6.Sidero是一个支持Kubernetes集群API的裸金属供应系统 - https://github.com/talos-systems/sidero

7.为什么Golang是构建人工智能驱动的应用程序的主流编程语言？- https://medium.com/devtechtoday/why-golang-is-a-mainstream-programming-language-for-building-ai-powered-apps-805f29f08a1f

8.pipeline: 一个帮助你在Go中创建流水线的库 - https://github.com/deliveryhero/pipeline

9.使用WSL2 + Goland进行Go项目（Thanos）开发及测试 - https://hangzhi.github.io/2021/06/24/wsl2GolandThanosDev/

10.使用go构建云应用教程 - https://www.golang.dk/courses/build-cloud-apps-in-go

11.PlayStation架构 - https://www.copetti.org/writings/consoles/playstation/



## 码农桃花源--2021-06-24
### 文章分享

- [今日面试题](https://www.yuque.com/u2278269/gq5x74/cfqx6z)


- [vim操作命令大全](https://blog.csdn.net/weixin_37657720/article/details/80645991)


- [go 设计模式二  建造者模式](https://lailin.xyz/post/builder.html)


### 面试题

1.进程和线程的区别？

2.说说你了解的进程同步机制

3.说说你了解的进程通信方式？


### 每日算法

「字符串转换整数」：https://leetcode-cn.com/problems/string-to-integer-atoi/




## go中文网每日资讯--2021-06-23


一、Go语言中文网

1. [Go：随机数是怎样产生的？](https://mp.weixin.qq.com/s/lg0LhtK4CiM7-OC790aYCQ)

2. [Go 语言保姆级教程（2021版上）](https://mp.weixin.qq.com/s/Q4mHlT3jjsh-D_PTgmPUvA)

二、亚军进化史

1. [Go技术日报(2021-06-22)——毛老师的管理之道](https://mp.weixin.qq.com/s/JmpBIeZqVdGiEydVY10_kA)

三、码农桃花源

1. [Go gomaxprocs 调高引起调度性能损耗](https://mp.weixin.qq.com/s/k9Zg3ji4Hp8dmYEkqx-gAg)

四、腾讯技术工程

1. [一文深入理解 Kubernetes](https://mp.weixin.qq.com/s/OXiqHvWJkmqz7FbclDd1jA)

五、董泽润的技术笔记

1. [小技巧！k8s 环境下调试服务](https://mp.weixin.qq.com/s/dSCNm-Yh1UQyaBz_J33UWQ)

2. [Strace 解决性能问题案例一则](https://mp.weixin.qq.com/s/B7WWNNwZ23kVeXP8ufLnAQ)

六、奇伢云存储

1. [深度好文：进程和线程这 19 个问题太强了](https://mp.weixin.qq.com/s/wTicQwTu8Ta8gLv2fZ3rCA)

七、k8s技术圈

1. [GitLab 触发 Tekton 任务构建](https://mp.weixin.qq.com/s/Pc0DhHLtg-_n5vQ-IfzDCQ)

八、云原生玩码部落

1. [了解一下Go中的&quot;sb&quot;代码？](https://mp.weixin.qq.com/s/jXHqpNkTs6SwB9_JDIl85Q)

九、MoeLove

1. [开源项目的 5 年长跑，runc v1.0 终于正式发布！](https://mp.weixin.qq.com/s/NbJ8rsUBMNCyEygUqaxXpA)

十、网管叨bi叨

1. [Go语言的IO库那么多，我该怎么选？](https://mp.weixin.qq.com/s/TtN6NZ8hQ2AIf0C8wVzkjA)

十一、脑子进煎鱼了

1. [Go 缓冲系列之-free-cache](https://mp.weixin.qq.com/s/VmPIW6HhVrDyeADiRmkC_Q)

十二、Go招聘

1. [回答我，停止 Goroutine 有几种方法？](https://mp.weixin.qq.com/s/5y4Njz0tTLrO9rLPmbBT2A)

2. [待遇比肩字节的招聘，你要来挑战嘛？](https://mp.weixin.qq.com/s/xv0dme8y2N9-R_ulmrfbpw)



## GOCN每日新闻--2021-06-23

1.如何在 Go 中正确使用基本身份验证 https://www.alexedwards.net/blog/basic-authentication-in-go

2.Go 处理错误的方式 https://www.bacancytechnology.com/blog/golang-error-handling

3.Go 实现的用于与源代码一起版本控制数据的工具 https://github.com/kevin-hanselman/dud/

4.GO 抓取网页信息 https://javarustacean.wordpress.com/2021/06/21/web-scrapping-in-go/

5.Go 实时 Web UI 和终端显示的高性能 HTTP 基准测试工具 https://github.com/six-ddc/plow

## gopherDaily--2021-06-23
1.Go语言错误处理之道 - https://www.bacancytechnology.com/blog/golang-error-handling

2.用Go实现网络抓取 - https://javarustacean.wordpress.com/2021/06/21/web-scrapping-in-go/

3.liqo: 实现跨Kubernetes集群的动态和分散的资源共享 - https://github.com/liqotech/liqo

4。如何在Go中正确使用基本认证 - https://www.alexedwards.net/blog/basic-authentication-in-go

5.OpenFaaS和Inlets作者Alex Ellis出版新书《Everyday Go》- https://blog.alexellis.io/i-wrote-a-book-about-golang/

6.Dud：一个与源代码一起进行数据版本管理和建立数据管道的工具 - https://github.com/kevin-hanselman/dud/

7.MOSN 子项目 Layotto：开启服务网格+应用运行时新篇章 - https://mp.weixin.qq.com/s/gKY7dsVRU0glf-n-fEsr3g

8.traefik Go维护者指南 - https://doc.traefik.io/traefik/contributing/maintainers-guidelines/

9.2021年的软件开发人员短缺即将到来 - https://cacm.acm.org/magazines/2021/7/253461-the-2021-software-developer-shortage-is-coming/fulltext

10.三万字 | 2021 年 Rust 行业调研报告 - https://mp.weixin.qq.com/s/9rjeVgVzmrC0wWhV4wA9FA

## 码农桃花源--2021-06-23
### 文章分享


- [k8s 调试小技巧](https://mp.weixin.qq.com/s/dSCNm-Yh1UQyaBz_J33UWQ)


- [go nil到底是什么](https://github.com/lindb/lindb)


- [go 设计模式一  创建型 工厂模式](https://lailin.xyz/post/factory.html)


### 面试题

##### reids总结：

- 1.说说 Redis 哈希槽的概念？

- 2.Redis 有哪几种数据“淘汰”策略？

- 3.一个字符串类型的值能存储最大容量是多少？

- 4.Redis 宕机后如何实现快速恢复？

- 5.Redis 的哨兵有什么功能？

- 6.Redis 哨兵和集群的区别是什么？

- 7.缓存命中率表示什么？

- 8.假如 Redis 里面有 1 亿个 key，其中有 10w 个 key 是以某个固定的已知的前缀开头的，如果将它们全部找出来？

- 9.Redis的字典是如何实现的？简述渐进式rehash过程

- 10.谈谈对Redis的反应堆模式的认识

- 11.谈谈Redis的ZIPLIST的底层设计和实现
 
- 12.谈谈对Redis的内存回收机制的理解

- 13.Redis List底层实现

- 14.Redis主从分布 主服务挂了会怎样(Sentinel 如何进行选举) 

- 15.Redis为什么用跳表而不用平衡树？


### 每日算法

「买卖股票的最佳时机」：https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock/

## go中文网每日资讯--2021-06-22


一、Go语言中文网

1. [Go项目推荐：一个快速安全的批量重命名开源工具](https://mp.weixin.qq.com/s/QOfLjr1RllbT0BPdqNNOzA)

2. [一文讲懂 Go 服务的优雅重启和更新](https://mp.weixin.qq.com/s/_yIwbQCNxO-9CJvPqCAd1w)

3. [在你的 Android 手机上运行 Golang 程序](https://mp.weixin.qq.com/s/EFHmjoTh0ji9Zc_YS6aPoQ)

二、亚军进化史

1. [Go技术日报(2021-06-21)——Golang 整洁接口最佳实践](https://mp.weixin.qq.com/s/BMBRD7m8WabCTp5eOhgrLw)

三、Golang来啦

1. [gRPC入门指南 — 服务端流式RPC（二）](https://mp.weixin.qq.com/s/f2-yA_Q9wPOClndKEwakMw)

四、polarisxu

1. [Go1.17 快报之标准库越来越注重易用性](https://mp.weixin.qq.com/s/6MWl8eT0KetLpLql_YLf4A)

2. [难以驾驭的 Go timer，一文带你参透计时器的奥秘](https://mp.weixin.qq.com/s/a481CXU6VymHTH8OOVimGQ)

五、脑子进煎鱼了

1. [编程思考：对象生命周期的问题](https://mp.weixin.qq.com/s/Hoy9cqHe9RZqEA5T9Dys5w)

六、MoeLove

1. [为什么我们需要一个容器镜像的包管理器](https://mp.weixin.qq.com/s/91jhyW5UrKLH12RYKSXBGQ)

七、高可用架构

1. [dubbogo 是如何炼成的？](https://mp.weixin.qq.com/s/attVemCAHybGm9xli9JlUw)

八、Go夜读

1. [Go 1.17 因安全问题修改的 URL query parsing](https://mp.weixin.qq.com/s/LM2zzbk1lr7KC0bV801qTw)

九、GoUpUp

1. [Go 每日一库之 ozzo-validation](https://mp.weixin.qq.com/s/TWlmXSl8xH5gMj0ziIkuYg)

十、TGO鲲鹏会

1. [B站数据平台负责人毛剑：从管理到下一线，优秀管理者应具备什么样的素质？](https://mp.weixin.qq.com/s/zyl5pjPiyE4FgCNH0HK2VA)

十一、Go招聘

1. [网易游戏招聘Gopher，这福利有点香哦](https://mp.weixin.qq.com/s/8ZVpsngJC2_GxfhD4mj3AQ)



## GOCN每日新闻--2021-06-22

1.向 Go 编译器开发代码 https://medium.com/trendyol-tech/contributing-the-go-compiler-adding-new-tilde-operator-f66d0c6cff7

2.Go 减少内存分配 https://chris124567.github.io/2021-06-21-go-performance/

3.Go 1.17 因安全问题修改的 URL query parsing https://mp.weixin.qq.com/s/LM2zzbk1lr7KC0bV801qTw

4.Go 自然语言检测库 https://github.com/pemistahl/lingua-go

5.在 Golang 中是锁或 Channel 还是 Atomic https://mp.weixin.qq.com/s/DNFAcTLtXO5UEkSZ-zCOKg


## gopherDaily--2021-06-22

1.Gopher夏季阅读清单 - https://github.com/ardanlabs/gotraining/tree/master/reading

2.Dmitry Vyukov提交一个变更，该变更是的读写锁的写锁性能有40%以上的大幅提升 - https://go-review.googlesource.com/c/go/+/329769

3.向Go编译器贡献代码实战指南（内容详尽） - https://medium.com/trendyol-tech/contributing-the-go-compiler-adding-new-tilde-operator-f66d0c6cff7

4.在go中减少内存分配实战 - https://chris124567.github.io/2021-06-21-go-performance/

5.Go语言中的竞态条件 - https://ercangercek.medium.com/race-conditions-in-golang-511314c0b85

6.Dolt：一个100%兼容的、可直接替换的MySQL - https://www.dolthub.com/blog/2021-06-21-copying-mysqls-dumb-decisions/

7.为实现云计算独立而需要考虑的5项开放技术 - https://thenewstack.io/5-open-technologies-to-consider-for-cloud-independence/

8.超越块和文件：COSI使Kubernetes中的对象存储成为可能 - https://thenewstack.io/beyond-block-and-file-cosi-enables-object-storage-in-kubernetes/

9.你不知道的关于Open Policy Agent的5件事 - https://thenewstack.io/5-things-you-didnt-know-about-open-policy-agent/

10.Google消息应用简史 - https://www.theverge.com/2021/6/21/22538240/google-chat-allo-hangouts-talk-messaging-mess-timeline

11.最准确的Go自然语言检测库，长文本和短文本均适用 - https://github.com/pemistahl/lingua-go


## 码农桃花源--2021-06-22
### 文章分享


- [redis 47连问](https://zhuanlan.zhihu.com/p/364787132)


- [用Go重新实现饿了么在用的分布式时序数据库](https://github.com/lindb/lindb)


- [go 设计模式一  创建型](https://lailin.xyz/post/singleton.html)


### 面试题

- 说说 Redis 哈希槽的概念？

- Redis 有哪几种数据“淘汰”策略？

- 一个字符串类型的值能存储最大容量是多少？


### 每日算法

「二分查找」：https://leetcode-cn.com/problems/binary-search/




## go中文网每日资讯--2021-06-21


一、Go语言中文网

1. [为什么 Go 关心 unsafe.Pointer 和 uintptr 之间的差别](https://mp.weixin.qq.com/s/v37jHYwt-msNIwIntlRZPg)

2. [Go：你真的了解 timeout 嘛？](https://mp.weixin.qq.com/s/dbZYwa7a9Q6I6-tb7T44QQ)

二、亚军进化史

1. [Go技术日报(2021-06-20)——有赞TCP网络编程最佳实践](https://mp.weixin.qq.com/s/qBNZAGmlzbeN-bk-1AoRRw)

三、k8s技术圈

1. [阿里云容器服务-Kubernetes高级工程师 | 云原生招聘](https://mp.weixin.qq.com/s/TElu3901a77Kr3KvgWsRew)

四、Go招聘

1. [灵魂一问：unsafe 包真的不安全吗？](https://mp.weixin.qq.com/s/PtAWvFrEUC8qXT3b46F7Rg)

五、CloudNativeCommunity

1. [蚂蚁开源多运行时项目 Layotto 简介](https://mp.weixin.qq.com/s/IkvsQqpyCTVhnXOfUXswcA)

六、脑子进煎鱼了

1. [漫谈 MQ：要消息队列（MQ）有什么用？](https://mp.weixin.qq.com/s/UrAJrUBKHNG7-UAabsqLZA)

2. [我无语了，Go 中 +-*/ 四个运算符竟然可以连着用](https://mp.weixin.qq.com/s/8GRq6At23fMho3BKkylcGw)

七、董泽润的技术笔记

1. [一次有趣的 Docker 容器网络排查](https://mp.weixin.qq.com/s/LtgGcS9b8X-TqbfaLfBldQ)

2. [小技巧！如何用 systemtap 排查问题](https://mp.weixin.qq.com/s/f9bPJOW2OR-vwp5DlZsDZQ)

八、PingCAP

1. [TiDB 在网易游戏的应用实践](https://mp.weixin.qq.com/s/Zh6baRekrZSDWYtFna8ZZg)

九、Go夜读

1. [理论结合实践详解 lsm 树存储引擎（bitcask、moss、leveldb 等） PPT （多图）](https://mp.weixin.qq.com/s/QxTtNdtkrJxRhaxUEKTqSg)

十、奇伢云存储

1. [自制文件系统 — 04 HelloFS 进阶 分布式加密文件系统](https://mp.weixin.qq.com/s/rxabk_o5YuSko8SM8EdouA)


## gopherDaily--2021-06-21

1.Go语言零拷贝优化 - https://zhuanlan.zhihu.com/p/381788230

2.使用harbor operator部署harbor - https://mp.weixin.qq.com/s/O7P3ODQlitjSPnOaKiJetQ

3.观点：对Go语言的4个批判 - https://www.toptal.com/go/4-go-language-criticisms

4.mahi: 多合一的HTTP服务，用于文件的上传、处理、服务和存储 - https://github.com/threeaccents/mahi

5.Go实现的基于命令行的时间跟踪工具 - https://github.com/dominikbraun/timetrace

6.掌握Git命令的本质 - https://mp.weixin.qq.com/s/f4dEz4ckDIo6dF51cqopIA

7.授权（authorization）的架构挑战 - https://thenewstack.io/the-architectural-challenge-of-authorization/

8.每个程序员都应该知道的关于SSD的事情 - https://databasearchitects.blogspot.com/2021/06/what-every-programmer-should-know-about.html

9.使用XMind图文并茂地记录的计算机科学基础知识 - https://github.com/smartkeyerror/psyduck

10.常见unix命令的现代/更快/更安全的替代品集合 - https://github.com/ibraheemdev/modern-unix

11.Kubernetes：对主要攻击的检验 - https://thenewstack.io/kubernetes-an-examination-of-major-attacks/

12.修复由MongoDB损坏和Heketi/GlusterFS配置失败引起的生产故障 - https://tilsupport.wordpress.com/2021/03/14/fixing-production-down-caused-by-mongodb-corruption-and-heketi-glusterfs-failed-provisioning/

## GOCN每日新闻--2021-06-21

1.一切皆有可能——Golang 中的” ThreadLocal“库 https://mp.weixin.qq.com/s/CPthQSqUIO-u-VkTQSMVXA

2.Golang 整洁接口最佳实践 https://mp.weixin.qq.com/s/eNoZTfh3L7mT-501g04YWQ

3.使用 Github Action 自动发布 Go 程序 https://web3.coach/golang-github-actions-release-binaries-tutorial

4.column: 位图索引高性能列式内存数据库 https://github.com/kelindar/column

5.有赞 TCP 网络编程最佳实践 https://tech.youzan.com/you-zan-tcpwang-luo-bian-cheng-zui-jia-shi-jian/


## 码农桃花源--2021-06-21
### 文章分享

- [上周股文](https://mp.weixin.qq.com/s/W1bsgGVfHURYUuAUlfenjg)


- [redis 多线程网络模型](https://mp.weixin.qq.com/s/-op5WR1wSkgAuP7JYZWP8g)


- [redis 分布式锁的实现](https://maimai.cn/article/detail?fid=1605049738&efid=PD1d90-MQAF-0GlPVbRoQw&share_channel=2&use_rn=1)



### 面试题

1.什么是内存抖动，有什么解决方案？

2.Redis 宕机后如何实现快速恢复？

3.GMP 模型中为什么需要 P？

4. 简述 epoll 模型的底层数据结构以及工作流程？

### 每日算法

「堆排序」：https://leetcode-cn.com/problems/sort-an-array/
## go中文网每日资讯--2021-06-20


一、Go语言中文网

1. [搭建了一个Go官网](https://mp.weixin.qq.com/s/S21fFc0U3K8ZPJx_vbeX2w)

2. [Go语言爱好者周刊：第 100 期 — 父亲节快乐](https://mp.weixin.qq.com/s/ZC4HS1cssK1nal9VuGP6-A)

二、薯条的编程修养

1. [Mutex和上厕所居然有这么多异曲同工之妙](https://mp.weixin.qq.com/s/wh_JIPxmo1V2gm6AeK4idQ)

三、亚军进化史

1. [Go技术日报(2021-06-19)——基于fasthttp实现的高性能http压测工具](https://mp.weixin.qq.com/s/Y4_735gdz-Fv9lX0T_fY9w)

四、k8s技术圈

1. [使用 Tekton Sidecar 实现 Docker IN Docker 构建](https://mp.weixin.qq.com/s/3cWv3Djmr84ysU9GBzZbSQ)

五、有赞技术团队

1. [有赞TCP网络编程最佳实践](https://tech.youzan.com/you-zan-tcpwang-luo-bian-cheng-zui-jia-shi-jian/)

六、云原生技术爱好者社区

1. [A Big Picture of Kubernetes](https://mp.weixin.qq.com/s/xMlvQzfgFZGgghV31tTVyw)

七、Go招聘

1. [股友说：Redis 主从复制就这？另外下周股什么，留言区告诉我](https://mp.weixin.qq.com/s/W1bsgGVfHURYUuAUlfenjg)
 


## GOCN每日新闻--2021-06-20

1.Casnode: React + Beego 的开源论坛 https://github.com/casbin/casnode

2.YoyoGo v1.7.2 发布,支持 Nacos&Apollo 配置中心   https://gocn.vip/topics/12216

3.Go 结构体的另类玩法：命名空间   https://mp.weixin.qq.com/s/8QRLiFMM8c5MX04f4ScUtA

4.Go1.17 新特性之切片变数组 https://polarisxu.studygolang.com/posts/go/dynamic/go1.17-slice-to-array/

5.深入理解 Golang Map https://mp.weixin.qq.com/s/gdzeDxD8zQopcIUYiLgjbw


## gopherDaily--2021-06-20
- 1.有赞TCP网络编程最佳实践 - https://tech.youzan.com/you-zan-tcpwang-luo-bian-cheng-zui-jia-shi-jian/
- 2.重写certificate parser，去除大部分反射，性能大幅提升 - https://github.com/golang/go/commit/51ff3a6965b3fc40aceebe90eaf15a8a1a00a452
- 3.Go问题实战：时钟源为什么会影响性能 - https://mp.weixin.qq.com/s/-czIqAldLTM4rp63g6O-Og
- 4.go实现的简单的视频会议工具 - https://github.com/boratanrikulu/quik.do
- 5.在Go 1.16版本中使用embed - https://lakefs.io/working-with-embed-in-go/
- 6.油管视频：IPFS工作原理 - https://www.youtube.com/watch?v=0IGzEYixJHk
- 7.理解kubernetes operator模式 - https://iximiuz.com/en/posts/kubernetes-operator-pattern/
- 8.Argo-CD自动驾驶仪：提供了一种安装Argo-CD和管理GitOps仓库的参考方式 - https://github.com/argoproj-labs/argocd-autopilot
- 9.2021年应该知道的7个区块链趋势 -  https://blockchain.51cto.com/art/202106/666970.htm
- 10.软件工程领域实用资料大全 - https://github.com/ixaxaar/awesome-engineering-management
- 11.在k8s上运行vault和consul - https://testdriven.io/blog/running-vault-and-consul-on-kubernetes/
- 12.超实用的基于ASCII字符的绘图工具 - https://asciiflow.com/

## go中文网每日资讯--2021-06-19
一、Go语言中文网

1. [一本花了2.5年写成的Go免费在线图书](https://mp.weixin.qq.com/s/6OFl3r7MynoRNt8KSptG2g)

2. [不能错过的 Go 图书](https://mp.weixin.qq.com/s/Wunq6VA1vIQohsNJ6x8rsw)

3. [站长8年前的Go代码竟然进大厂的项目里了](https://mp.weixin.qq.com/s/timJJRvAOul3oT8v4Hw4AA)

二、飞雪无情

1. [Go语言实现的在终端演示幻灯片工具](https://mp.weixin.qq.com/s/Y6-K4jgRfCIafgYn_6gphw)

三、亚军进化史

1. [Go技术日报(2021-06-18)——几张图讲清 Go 内存分配管理](https://mp.weixin.qq.com/s/4TVJTHw1jzYHqdRdwaq4wg)

四、k8s技术圈

1. [使用 Workspaces 加速 Tekton 流水线](https://mp.weixin.qq.com/s/c9xC36H8-vaxgmhp2JEaBw)


## GOCN每日新闻--2021-06-19
1.Golang 的自然语言处理包   https://pkg.go.dev/github.com/james-bowman/nlp

2.把 vue.js 应用打包进 golang   https://hackandsla.sh/posts/2021-06-18-embed-vuejs-in-go/

3.一个高性能 http benchemark 工具拥有实时的 web ui 和命令行展示 https://github.com/six-ddc/plow

4. 类似于 curl 但是是用于 grpc 的，跟 grpc server 交互的命令行工具 https://github.com/fullstorydev/grpcurl

5. 一个商业级别的构建部署监控平台  https://github.com/erda-project/erda


## gopherDaily--2021-06-19

1.将vue.js嵌入到Go二进制文件中 - https://hackandsla.sh/posts/2021-06-18-embed-vuejs-in-go/

2.基于fasthttp实现的高性能http压测工具 - https://github.com/six-ddc/plow

3.油管视频：Go编程之禅 - https://www.youtube.com/watch?v=yd_rtwYaXps

4.go定长或变长二进制编码https://nakabonne.dev/posts/binary-encoding-go/

5.go-vcr: 通过记录你的HTTP交互并重放，以提供快速、确定和准确的代码测试 - https://github.com/dnaeon/go-vcr

6.2021年可观察性(observability)的现状 - https://www.honeycomb.io/blog/state-of-observability-2021/

7.Go实现的具有位图索引的高性能、列式、内存存储库 - https://github.com/kelindar/column

8.面向开发者的Kubernetes上的现代持续交付 - https://dev.to/gabrieltanner/modern-continuous-delivery-on-kubernetes-for-developers-5chf

9.深入理解k8s集群的DNS服务 - https://medium.com/kubernetes-tutorials/kubernetes-dns-for-services-and-pods-664804211501

10.github上项目的k8s最佳实践徽章代表什么 - https://www.fairwinds.com/blog/github-kubernetes-best-practices-badge


## go中文网每日资讯--2021-06-18
一、Go语言中文网

1. [Go 结构体的另类玩法：命名空间](https://mp.weixin.qq.com/s/8QRLiFMM8c5MX04f4ScUtA)

2. [深入理解 Golang Map](https://mp.weixin.qq.com/s/gdzeDxD8zQopcIUYiLgjbw)

二、亚军进化史

1. [Go技术日报(2021-06-17)——通过实例理解 Go 逃逸分析](https://mp.weixin.qq.com/s/IXNSqiymGW0ONd-VP0id-g)

三、MoeLove

1. [Apache APISIX Ingress Controller 首个 GA 版本 v1.0 正式发布！](https://mp.weixin.qq.com/s/Ou_MS56MlySvlJuHFkWRqA)

四、脑子进煎鱼了

1. [说好 defer 在 return 之后执行，为什么结果却不是？](https://mp.weixin.qq.com/s/oP90maykSzMXjdnudOKdSw)

五、polarisxu

1. [不能错过的 Go 图书](https://mp.weixin.qq.com/s/FigQswolXHWO9py_gt8xYQ)

2. [手撕 Go 面试官：Go 结构体是否可以比较，为什么？](https://mp.weixin.qq.com/s/lugf6FzOjkQC4txssLa_9g)

六、k8s技术圈

1. [WiFi 万能钥匙-容器技术高级工程师 | 云原生招聘](https://mp.weixin.qq.com/s/5G3d05YRAVAZhDCzRkEtTA)

七、Go招聘

1. [几张图讲清 Go 内存分配管理](https://mp.weixin.qq.com/s/ZBm36JvtQQJ3FO_SivTrSw)

2. [百度健康急聘Gopher](https://mp.weixin.qq.com/s/xOJNa5EWXtYOIi_h76r32Q)





## GOCN每日新闻--2021-06-18

1.Golang 开发的一站式云原生 PaaS 平台 https://github.com/erda-project/erda

2.深度剖析 Go 的 nil https://mp.weixin.qq.com/s/0WhlsrMk_-wBHsUldZ60sg

3.浅入深解读 Go Zap 的高性能 https://mp.weixin.qq.com/s/zqYNu2uTJe1UXiWvm98dOw

4.我要提高 Go 程序健壮性，Fuzzing 来了 https://mp.weixin.qq.com/s/zdsrmlwVR0bP1Q_Xg_VlpQ

5.Go 问题实战：时钟源为什么会影响性能 https://mp.weixin.qq.com/s/-czIqAldLTM4rp63g6O-Og


## gopherDaily--2021-06-18
1.致力于打造精品Go社区且每天都有新内容的“gopher部落”为广大Gopher准备了端午节+618福利，福利一直持续到6月18日，先到先得！欢迎广大gopher加入！ - https://t.zsxq.com/bUZzJ27

2.使用Redis和Go实现可扩展的事件流(event streaming) - https://ably.com/blog/event-streaming-with-redis-and-golang

3.nancy：由Sonatype OSS Index提供的检查Go依赖项中漏洞的工具 - https://github.com/sonatype-nexus-community/nancy

4.access-controller：“谷歌一致性全球授权系统”论文的一个实现 - https://github.com/authorizer-tech/access-controller

5.云原生应用打包(CNAB)工具 - https://github.com/getporter/porter

6.观点：全局变量不是问题 - https://stonecode.ca/global-variables-arent-the-problem/

7.经典旧文：https://www.freecodecamp.org/news/how-i-investigated-memory-leaks-in-go-using-pprof-on-a-large-codebase-4bec4325e192/

8.Go template使用的三个tip - https://krishbhanushali.medium.com/3-simple-techniques-using-go-templates-6718e2cc77e2

10.在k8s上运行flink - https://medium.com/empathyco/running-apache-flink-on-kubernetes-10815a26559e

11.使用kubernetes custom resources管理临时环境 - https://medium.com/beamdental/using-kubernetes-custom-resources-to-manage-our-ephemeral-environments-f298610893e1

12.社区不等于营销——为什么我们要社区化，而不仅是市场化？ - https://cloudnative.to/blog/community-marketing-why-we-need-go-to-community-not-just-go-to-market/

13.apache kafka入门（精美动画版）- https://www.gentlydownthe.stream/

14.map[uint]bool and map[uint]struct{}性能比较 - https://itnext.io/set-in-go-map-bool-and-map-struct-performance-comparison-5315b4b107b

## 码农桃花源--2021-06-18
### 文章分享
- [redis skiplist实现](https://mp.weixin.qq.com/s?__biz=Mzg5MTYyNzM3OQ==&mid=2247483959&idx=1&sn=7cb4da8022cabb61ec7a222e0d2817ba&chksm=cfcb302bf8bcb93dde85f3b573d7811fd37af9973615d132e8ee81acd1752e2614e72e0431e9&scene=178&cur_album_id=1899308563211091969#rd)


- [redis 面试题](https://zhuanlan.zhihu.com/p/364787132)


- [Redis如何删除数量过万以上Key而不影响业务](https://maimai.cn/article/detail?fid=1605049738&efid=PD1d90-MQAF-0GlPVbRoQw&share_channel=2&use_rn=1)


### 面试题

- Redis 的哨兵有什么功能？

- Redis 哨兵和集群的区别是什么？

- 缓存命中率表示什么？

- 假如 Redis 里面有 1 亿个 key，其中有 10w 个 key 是以某个固定的已知的前缀开头的，如果将它们全部找出来？


### 每日算法

「x的平方根」：https://leetcode-cn.com/problems/sqrtx/

## go中文网每日资讯--2021-06-17


一、Go语言中文网

1. [从一道题讲起：Go 的不可寻址值和切片](https://mp.weixin.qq.com/s/mY_Tf2M-su-urHw2ItbC1A)

2. [女朋友问我：你知道Go语言参数传递是传值还是传引用吗？](https://mp.weixin.qq.com/s/f7tCrLn3Iah6WB5ANqmCsA)

二、亚军进化史

1. [Go技术日报(2021-06-16)——详解Redis的架构演化之路](https://mp.weixin.qq.com/s/yMVEW2rzwg_5ApX-BcGu-Q)

三、polarisxu

1. [Go1.17 新特性之切片变数组](https://mp.weixin.qq.com/s/cl-Qsj6oK_6MKuMZHSDV5Q)

四、脑子进煎鱼了

1. [回答我，停止 Goroutine 有几种方法？](https://mp.weixin.qq.com/s/tN8Q1GRmphZyAuaHrkYFEg)

2. [招聘：Go 工程师  年薪40-100万，没有996和007！](https://mp.weixin.qq.com/s/ncXdLQA4muB9WRGPZa9YzA)

五、HHFCodeRv

1. [localhost 就一定是 localhost 么?](https://mp.weixin.qq.com/s/I69v_lX-Wx7jxx9ddjT2Og)

六、码农桃花源

1. [通过实例理解 Go 逃逸分析](https://mp.weixin.qq.com/s/wNIX6LeHnBsl1UQuRtmC1g)

七、k8s技术圈

1. [创建 Tekton 流水线](https://mp.weixin.qq.com/s/M08CrTEeriZwvNCjlaZdkg)

八、好未来技术

1. [服务网格在网校平台研发部的实践和思考](https://mp.weixin.qq.com/s/Lbu228IknOJy6lmhTxFtcQ)

九、mohuishou

1. [Go timer 是如何被调度的？](https://mp.weixin.qq.com/s/YXYCmypE5qCK2SG342tcpg)

十、Go招聘

1. [全球语音视频云服务提供商ZEGO招聘](https://mp.weixin.qq.com/s/SYxgH3o2gzMON1dTGvvMvQ)]




 
## GOCN每日新闻--2021-06-17
1.译文 Go 性能工具小抄 https://gocn.vip/topics/12198

2.徒手用 Go 写个 Redis 服务器（Godis）https://www.cnblogs.com/xueweihan/p/14891859.html

3.Go 所有设计模式的流程图与代码实现 https://dev.to/gopher/go-all-design-patterns-code-with-workflow-ea1

4.详解 Go 程序的启动流程，你知道 g0，m0 是什么吗？ https://eddycjy.com/posts/go/go-bootstrap0/

5.一篇文章带你搞懂 etcd 3.5 的核心特性 https://mp.weixin.qq.com/s/AYdDdFfJMRvaye0Esh7ImQ



## gopherDaily--2021-06-17
1.致力于打造精品Go社区且每天都有新内容的“gopher部落”为广大Gopher准备了端午节+618福利，福利一直持续到6月18日，先到先得！欢迎广大gopher加入！ - https://t.zsxq.com/bUZzJ27

2.傻瓜式的Go Vim开发环境安装与设置 - https://akondas.com/blog/Go-Vim-Setup-For-Dummies

3.2021 SRE报告 - https://f.hubspotusercontent30.net/hubfs/5595333/Catchpoint-2021-SRE-Report.pdf

4.LinDB: 用Go重新实现饿了么在用的分布式时序数据库 - https://github.com/lindb/lindb

5.基于sql.DB和fs.FS实现的数据库迁移工具 - https://github.com/maragudk/migrate

6.使用Telepresence 2进行k8s调试和本地开发 - https://codefresh.io/kubernetes-tutorial/telepresence-2-local-development/

7.使用Sloth让SLO(service level objectives)更容易 - https://itnext.io/slos-should-be-easy-say-hi-to-sloth-9c8a225df0d4

8.wasmer 2.0发布，性能提升50% - https://wasmer.io/posts/wasmer-2.0

9.理解kubernetes架构 - https://dev.to/pghildiyal/understanding-kubernetes-architecture-2k0l

10.Clusternet: 让你的k8s集群（包括公共、私人、混合、边缘等）管理像访问互联网一样容易 - https://github.com/clusternet/clusternet

11.有史以来被复制最多的StackOverflow片段是有缺陷的! - https://programming.guide/worlds-most-copied-so-snippet.html

12.我们对Knative的营销是否有误？- https://ahmet.im/blog/knative-positioning/

13.使用k8s和istio进行多集群管理 - https://thenewstack.io/multicluster-management-with-kubernetes-and-istio/




## go中文网每日资讯--2021-06-16


一、Go语言中文网

1. [Go：字符串以及转换优化](https://mp.weixin.qq.com/s/PbmhUrfNu3slmnVyRK_KRw)

2. [Go问题实战：时钟源为什么会影响性能](https://mp.weixin.qq.com/s/-czIqAldLTM4rp63g6O-Og)

二、亚军进化史

1. [Go技术日报(2021-06-15)——图解 Go 逃逸分析](https://mp.weixin.qq.com/s/FfYQLjJ_cGppz8K_cN3SpQ)

三、Go夜读

1. [【本周四】第 116 期理论结合实践详解 LSM 树存储引擎（bitcask、moss、leveldb 等）](https://mp.weixin.qq.com/s/wddlMDTtedXcvYZK76j_gA)

四、腾讯云原生

1. [一篇文章带你搞懂 etcd 3.5 的核心特性](https://mp.weixin.qq.com/s/mhHPyCAmdbT5wXF0vBiGzQ)

五、腾讯技术工程

1. [一文带你理解云原生](https://mp.weixin.qq.com/s/yX0hgIOLuaKsAcrWfOfcUQ)

六、CloudNativeCommunity

1. [知名图片分享平台 Pinterest 如何有把握地扩展 Kubernetes](https://mp.weixin.qq.com/s/gzImUEAxLKTNjY_JFraODg)

七、k8s技术圈

1. [使用 kube-vip 搭建高可用 Kubernetes 集群](https://mp.weixin.qq.com/s/yNYWOY9HWvLuVPmT9XZInw)

八、董泽润的技术笔记

1. [Rust 居然允许变量 shadowing](https://mp.weixin.qq.com/s/CL40UIHgxam3KQ0iqMVHGA)

2. [深度剖析 Go 的 nil](https://mp.weixin.qq.com/s/0WhlsrMk_-wBHsUldZ60sg)

九、网管叨bi叨

1. [详解Redis的架构演化之路（附16张图解）](https://mp.weixin.qq.com/s/NjFVo0ht9tk1g9fOkHniTA)

十、Go招聘

1. [厉害了我的Go!   快来看看这份书单吧！](https://mp.weixin.qq.com/s/-ADK6w-eOighcjUfmhFCkg)

十一、GoUpUp

1. [Go 每日一库之 bubbletea](https://mp.weixin.qq.com/s/Hwlxbm1hQ5HfzA3yakg1Ig)

十二、脑子进煎鱼了

1. [我要提高 Go 程序健壮性，Fuzzing 来了！](https://mp.weixin.qq.com/s/zdsrmlwVR0bP1Q_Xg_VlpQ)

2. [一文带你由浅入深地解读 Go Zap 的高性能](https://mp.weixin.qq.com/s/zqYNu2uTJe1UXiWvm98dOw)




## GOCN每日新闻--2021-06-16

1.说说 Golang goroutine 并发那些事儿 https://blog.51cto.com/u_15162069/2907504

2.fasthttp：比 net/http 快十倍的 Go 框架 (server 篇)  https://www.luozhiyun.com/archives/574

3.详解 Go 程序的启动流程，你知道 g0，m0 是什么吗？ https://segmentfault.com/a/1190000040181868

4.一个 Gin 缓存中间件的设计与实现 https://www.cyhone.com/articles/gin-cache

5.用于加载 csv 和 excel (xlsx) 文件并运行 sql 命令的命令行工具 https://github.com/dhamith93/csv-sql




## gopherDaily--2021-06-16
1.致力于打造精品Go社区且每天都有新内容的“gopher部落”为广大Gopher准备了端午节+618福利，福利一直持续到6月18日，先到先得！欢迎广大gopher加入！ - https://t.zsxq.com/bUZzJ27

2.如何用signoz监控go应用 - https://signoz.io/blog/monitoring-your-go-application-with-signoz/

3.2021年呈爆炸式增长的编程语言 - https://preettheman.medium.com/programming-languages-with-exploding-growth-in-2021-c5860e13050b

4.Mmark: 面向IETF RFC文档的markdown处理器 - https://github.com/mmarkdown/mmark

5.kubernetes与vm并行 - https://thenewstack.io/parallels-of-vms-and-kubernetes/

6.基于BadgerDB和raft的分区容错key-value存储 - https://github.com/adityameharia/ravel

7.gobrew: 另一个go版本管理器 - https://github.com/kevincobain2000/gobrew

8.使用应用网关在Azure上实现Kubernetes ingress：如何在一台主机上暴露多个服务 - https://itnext.io/kubernetes-ingress-on-azure-using-the-application-gateway-2779b647deb5

9.使用ytt, kbld和kapp部署k8s应用 - https://carvel.dev/blog/deploying-apps-with-ytt-kbld-kapp/

10.使用 kube-vip 搭建高可用 Kubernetes 集群 - https://mp.weixin.qq.com/s/yNYWOY9HWvLuVPmT9XZInw

11.我们如何使用metamonitoring Prometheus服务器来监控Grafana实验室的所有其他Prometheus服务器 - https://grafana.com/blog/2021/04/08/how-we-use-metamonitoring-prometheus-servers-to-monitor-all-other-prometheus-servers-at-grafana-labs/





## 码农桃花源--2021-06-16
### 文章分享

1.[如何搞坏redis](https://mp.weixin.qq.com/s/YKAEjPVABpSxyxLieyqPsg)

2.[redis 1-10一个系列推荐阅读](https://mp.weixin.qq.com/s/mkL7rs5AojIlcjlPwk2xBg)

3.[超硬核redis面试题](https://mp.weixin.qq.com/s/YStMnPw8V_-cqBhQrHsN8Q)

### 面试题

1.Redis的字典是如何实现的？简述渐进式rehash过程

2.谈谈对Redis的反应堆模式的认识

3.谈谈Redis的ZIPLIST的底层设计和实现 

4.谈谈对Redis的内存回收机制的理解

### 每日算法

「搜索旋转排序数组」：https://leetcode-cn.com/problems/search-in-rotated-sorted-array/

## go中文网每日资讯--2021-06-15


一、Go语言中文网

1. [GoLand 2021.2 EAP 发布](https://mp.weixin.qq.com/s/YKuur9QjU6BFnuHqqW5xDw)

2. [图解 Go 逃逸分析](https://mp.weixin.qq.com/s/80pv2gpnbKMPNLDr3dnSCA)

3. [高并发系统的限流策略：漏桶和令牌桶(附Go源码剖析)](https://mp.weixin.qq.com/s/w1z5nDZmb-bYV4E66e2rzw)

二、亚军进化史

1. [Go技术日报(2021-06-14)——Go 语言学习路线来啦](https://mp.weixin.qq.com/s/ZsucDNBf0NXA6th09_31jg)

三、脑子进煎鱼了

1. [Go 存储基础 — 内存结构体怎么写入文件？](https://mp.weixin.qq.com/s/Jeo23MdIljMr3X8sGs_nvA)

四、mohuishou

1. [localhost 就一定是 localhost 么?](https://mp.weixin.qq.com/s/DhuEN4XncTHtITyXAnmhug)

五、MoeLove

1. [K8S 生态周报| Docker v20.10.7 发布，修复了死锁和容器启动失败的问题](https://mp.weixin.qq.com/s/NudSiti0IADkpkoPcpGUeg)

六、polarisxu

1. [搭建了一个Go官网](https://mp.weixin.qq.com/s/7lkBRmjEkElvqHmJVVBWwQ)

七、云加社区

1. [分布式一致性算法Raft](https://mp.weixin.qq.com/s/9JnMQjjqb1Tjg3SUrRWoBQ)

八、Go招聘

1. [招聘：Golang 工程师  年薪40-100万，没有996和007！](https://mp.weixin.qq.com/s/rC44vuhx7p473rgkVk1Nyw)

九、GoUpUp

1. [为 tunny 提交的一次 PR](https://mp.weixin.qq.com/s/hxRaFtpMgvbTAfMfn70S5Q)

十、Golang梦工厂

1. [面试中如果这样写二分查找！](https://mp.weixin.qq.com/s/bLuqKWnTGlcxyhVK1913FQ)
 
## GOCN每日新闻--2021-06-15

1.从零学 Go：列表与字典 https://juejin.cn/post/6972316925795762183

2.Go 1.16 如何使用 go:embed 资源文件内嵌功能 https://blog.jetbrains.com/go/2021/06/09/how-to-use-go-embed-in-go-1-16/

3.Golang 如何调度你的程序的 https://juejin.cn/post/6972893426425528357

4.初探 Golang ReverseProxy 源码 https://coderdao.github.io/2021/06/13/%E5%88%9D%E6%8E%A2-ReverseProxy-%E6%BA%90%E7%A0%81/

5.在终端以幻灯片方式阅读 Markdown 文件 https://github.com/maaslalani/slides

## gopherDaily--2021-06-15
1.致力于打造精品Go社区且每天都有新内容的“gopher部落”为广大Gopher准备了端午节+618福利，福利一直持续到6月18日，先到先得！欢迎广大gopher加入！ - https://t.zsxq.com/bUZzJ27

2.CUE是一种令人兴奋的配置语言 - https://bitfieldconsulting.com/golang/cuelang-exciting

3.加载csv和excel（xlsx）文件并运行sql命令的命令行工具 - https://github.com/dhamith93/csv-sql

4.eBPF内幕 by brendan gregg - https://brendangregg.com/blog/2021-06-15/bpf-internals.html

5.mqtt协议安全检查工具 - https://github.com/SPuerBRead/mqtts

6.使用纯go语言编写web应用的框架 - https://github.com/reusee/domui

7.Go中值得怀疑的实现，以及它在rust中的表现如何：从Python开发者的角度来看 - https://faun.pub/questionable-implementation-in-golang-and-how-it-fares-with-rust-from-
prospective-of-python-ddbdb594b364

8.贝尔实验室的两位研究人员如何为现代编译器制定了规则 - https://thenewstack.io/how-two-bell-labs-researchers-set-the-rules-for-the-modern-compiler/

9.2021 年 Kubernetes 的状况以及 CISO(首席信息安全官) 可以做些什么 - https://enterprisetalk.com/featured/the-state-of-kubernetes-in-2021-and-what-cisos-can-do-about-it/

10.向数据湖仓一体(lakehouse)的演化 - https://databricks.com/blog/2021/05/19/evolution-to-the-data-lakehouse.html
面向程序员的实用Reed-Solomon编码算法 - https://berthub.eu/articles/posts/reed-solomon-for-programmers/

## 码农桃花源--2021-06-15
### 文章分享

1. [使用 litmus 验证内存重排](https://mp.weixin.qq.com/s/WOYC7KskgVOtBUc2WLqXkA)

2. [go math/rand](https://mp.weixin.qq.com/s/zQq9lEDLGPh7shvJLm0AuQ)

3. [pulsar](https://mp.weixin.qq.com/s/wITNF8Mwuf5Zeujo78s_ZQ)

### 面试题

1.Redis List底层实现

2.Redis 宕机后如何实现快速恢复?

3.Redis主从分布 主服务挂了会怎样(Sentinel 如何进行选举) 

4.Redis为什么用跳表而不用平衡树？

### 每日算法

「二叉树的锯齿形层序遍历」：https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/





## go中文网每日资讯--2021-06-14


一、Go语言中文网

1. [Go就这待遇？2021年6月程序员工资排行榜](https://mp.weixin.qq.com/s/HTb0R7qrAP5ElZFchaHCjw)

2. [鸭子类型 vs 结构化类型 vs 标称类型？Go是哪种？](https://mp.weixin.qq.com/s/IITCKfywi-9FUq47fq4Iuw)

3. [聊聊 Go 并发安全](https://mp.weixin.qq.com/s/ybW8sW7Xq6XpqQzMQlIlHA)

二、亚军进化史

1. [Go技术日报(2021-06-12)——分布式锁实现原理与最佳实践](https://mp.weixin.qq.com/s/1Mm-ip0J4DZXCekZG3Emaw)

2. [Go技术日报(2021-06-13)——Go 高性能之建议和实践](https://mp.weixin.qq.com/s/MEc_XQgzZfb7Ttt1_T2cQA)

三、码农桃花源

1. [使用 litmus 验证内存重排](https://mp.weixin.qq.com/s/WOYC7KskgVOtBUc2WLqXkA)

四、luozhiyun很酷

1. [fasthttp：比net/http快十倍的Go框架(server 篇)](https://mp.weixin.qq.com/s/pbuMkiPCcif5871CdLcehA)

五、董泽润的技术笔记

1. [开发搞跨 redis 的一万种方法](https://mp.weixin.qq.com/s/YKAEjPVABpSxyxLieyqPsg)

六、后端技术指南针

1. [如何科学破解慢SQL?](https://mp.weixin.qq.com/s/OOh1G1DvtQ3-dEIXEKuWtw)

七、奇伢云存储

1. [这 7 个 Linux 命令，你是怎么来使用的？](https://mp.weixin.qq.com/s/yi-0hB9i7Q2XpXHouZ7pnQ)

2. [动图图解！既然IP层会分片，为什么TCP层也还要分段？](https://mp.weixin.qq.com/s/LkuDO0Wc2c4ksgukO2NFqA)

八、Pearl的仲夏夜之梦

1. [深入理解Linux IO模型(二)](https://mp.weixin.qq.com/s/6AXO0mY2xSiQ7140f9UJuQ)

九、Go招聘

1. [面试官：如何避免Go变量被GC？](https://mp.weixin.qq.com/s/JkTVv52WZXhP3KDH1eNLPg)
 1


## GOCN每日新闻--2021-06-14

1.Go 高性能系列教程之六：一些建议和实践 https://gocn.vip/topics/12187

2.Go 模糊测试 beta 版准备好了 https://mp.weixin.qq.com/s/wR3B50lh5-CK5Zs9-zNnDg

3.go 学习笔记（二）派生类型 https://mp.weixin.qq.com/s/HAkcgwnLy3W2XT4YRXYcJg

4.聊聊 Go 并发安全 https://mp.weixin.qq.com/s/ybW8sW7Xq6XpqQzMQlIlHA

5.Go 语言学习路线来啦 https://mp.weixin.qq.com/s/aU5WqMxVS2vgGLGedZEu7w

## gopherDaily--2021-06-14
- 1.所有设计模式的Go实现代码与流程图 - https://dev.to/gopher/go-all-design-patterns-code-with-workflow-ea1
- 2.油管视频：Go中我从来不用的东西 - https://www.youtube.com/watch?v=5DVV36uqQ4E&list=PLEcwzBXTPUE9V1o8mZdC9tNnRZaTgI-1P&index=9
- 3.trivy: 一个针对容器镜像、Git存储库和文件系统的漏洞扫描器，适用于CI - https://github.com/aquasecurity/trivy
- 4.充分发挥Helm模板的作用 - https://blog.flant.com/advanced-helm-templating/
- 5.基于角色的访问控制（RBAC），支持数据库持久化 - https://github.com/harranali/authority
- 6.oracle推出terraform课程 - https://blogs.oracle.com/developers/learn-terraform-today-on-oci
- 7.OpenTelemetry与可观察性的未来 - https://thenewstack.io/splunk-opentelemetry-and-the-future-of-observability/
- 8.Argo CD和OpenShift如何为开发者实现GitOps - https://thenewstack.io/how-argo-cd-and-openshift-enable-gitops-for-developers/
- 9.如何处理命令行中的密码 - https://smallstep.com/blog/command-line-secrets/
- 10.计算机科学家的git原理指南 - https://eagain.net/articles/git-for-computer-scientists/



## go中文网每日资讯--2021-06-13


一、Go语言中文网

1. [我这样升级 Go 版本，你呢？](https://mp.weixin.qq.com/s/pra9g1nIbzRnZ9KhodUGMw)

2. [Go语言爱好者周刊：第 99 期 — 端午节快乐](https://mp.weixin.qq.com/s/TSgv-UStXC0NTqHwIk8YGg)

3. [Go 模糊测试是什么？官方博文讲解](https://mp.weixin.qq.com/s/ypn17Ty74pWbhLSArmpbuQ)

二、亚军进化史

1. [Go技术日报(2021-06-11)——Go 1.17beta1发布](https://mp.weixin.qq.com/s/lcZZfN6C7KPD0HadEKwi9Q)

三、奇伢云存储

1. [编程思考：对象生命周期的问题](https://mp.weixin.qq.com/s/6GEj1XmkX731yw4kDuPYaQ)

四、polarisxu

1. [站长8年前的Go代码竟然进大厂的项目里了](https://mp.weixin.qq.com/s/-j8ohEXPS6d6wqvQZxDz5g)

五、Go招聘

1. [端午安康—Go中如何实现文件监听？文末有红包彩蛋o](https://mp.weixin.qq.com/s/5kqmigJRCvvrhKLKBoW4SQ)

## GOCN每日新闻--2021-06-13
1.Go 系统监控利器-gopsutil https://gocn.vip/topics/12183

2.Go 高性能系列教程之六：一些建议和实践 https://gocn.vip/topics/12187

3.在 Go 中使用位掩码 https://www.ardanlabs.com/blog/2021/04/using-bitmasks-in-go.html

4.Goroutine 泄漏 - 被遗弃的接收器 https://www.ardanlabs.com/blog/2018/12/goroutine-leaks-the-abandoned-receivers.html

5.Go 初始化流程分析 https://juejin.cn/post/6969230952685895694

## gopherDaily--2021-06-13
- 1.Python vs Go:哪一个是最好的，为什么？- https://techbiason.com/go-vs-python/
- 2.gitops成熟度模型 - https://www.weave.works/blog/the-gitops-maturity-model
- 3.提高Kubernetes可理解性的5个技巧 - https://www.rookout.com/blog/5-tips-to-improve-kubernetes-understandability
- 4.异步和持久化的推送通知服务，支持APNS、FCM、网络推送、Telegram和电子邮件 - https://github.com/pennersr/shove
- 5.用OpenTracing、Jaeger和Ingress-NGINX在Kubernetes中设置分布式追踪功能 - https://awkwardferny.medium.com/setting-up-distributed-tracing-with-opentelemetry-jaeger-in-kubernetes-ingress-nginx-cfdda7d9441d
- 6.Orkestra：一个云原生的发布编排和生命周期管理（LCM）平台 - https://github.com/Azure/orkestra
- 7.使用kubeadm在Ubuntu的VirtualBox上创建一个Kubernetes 1.20集群 - https://kosyfrances.com/kubernetes-cluster/
- 8.cve-2021-31440: 使用eBPF的Kubernetes容器漏洞 - https://www.tigera.io/blog/cve-2021-31440-kubernetes-container-escape-using-ebpf/
- 9.你真的需要redis吗？如果只用PostgreSQL就可以实现呢？- https://spin.atomicobject.com/2021/02/04/redis-postgresql/
- 10.vscode增加remote repositories插件，可直接从GitHub上浏览甚至编辑任何GitHub repo而无需先pull源码 - https://code.visualstudio.com/blogs/2021/06/10/remote-repositories


## go中文网每日资讯--2021-06-12


一、Go语言中文网

1. [Go1.17 Beta1 发布](https://mp.weixin.qq.com/s/2UeuFECPBoxh2nUDxohVNg)

2. [也许是 Go Context 最佳实践](https://mp.weixin.qq.com/s/8iBQWs7LAXEMCoXc5PpSaQ)

3. [源码剖析sync.Cond(条件变量的实现机制）](https://mp.weixin.qq.com/s/uD_3C43zPqWI-VKfQfAzTw)

二、亚军进化史

1. [Go技术日报(2021-06-11)——Go 1.17beta1发布](https://mp.weixin.qq.com/s/lcZZfN6C7KPD0HadEKwi9Q)

三、奇伢云存储

1. [网络排障全景指南手册v1.0精简版pdf 发布](https://mp.weixin.qq.com/s/fR46xxkoGvMltV-8F0pMxA)

2. [i/o timeout ， 希望你不要踩到这个net/http包的坑](https://mp.weixin.qq.com/s/5cVM5vM4zmltwb77p4NZKQ)

四、k8s技术圈

1. [为什么集群需要 Overlay 网络](https://mp.weixin.qq.com/s/a1omUj17yNVUuymh6DYpRQ)

五、polarisxu

1. [Go图书翻译：一个好消息，一个坏消息](https://mp.weixin.qq.com/s/wbXEq7NwxHkMIGBbY_dKUQ)

六、杨旭技术专栏

1. [Go 简单分布式系统 4.2 服务状态监控](https://mp.weixin.qq.com/s/kDd-BuDrKkV2odMoskmqzg)

七、网管叨bi叨

1. [分布式锁实现原理与最佳实践](https://mp.weixin.qq.com/s/M92bQQ4ESeE-RkiPiu-oRw)


 
## GOCN每日新闻--2021-06-12
1.Go 实现正向代理服务器 https://juejin.cn/post/6972563525361369125

2.编写友好的 Go 命令行应用程序 https://mp.weixin.qq.com/s/qOhdWkIG5lZG6hV7QHIsaQ

3.你不知道的 Go 之 const https://mp.weixin.qq.com/s/EKnphU752SY1vp_O_qY1ag

4.Go 高性能系列教程之五：内存和垃圾回收 https://gocn.vip/topics/12186

5.Go Race Detector with ThreadSanitizer https://medium.com/a-journey-with-go/go-race-detector-with-threadsanitizer-8e497f9e42db

## gopherDaily--2021-06-12
- 1.Go代码静态分析实战指南 -  https://github.com/amit-davidson/GopherCon2021IsraelStaticAnalysisWorkshop
- 2.vagrant 3.0将使用Go重写 - https://www.hashicorp.com/blog/toward-vagrant-3-0
- 3.如何使用Goland升级一个module的major版本号 - https://blog.jetbrains.com/go/2021/06/11/how-to-increment-the-major-version-of-a-go-module-using-goland/
- 4.使用Go实现GraphQL服务器 - https://eli.thegreenplace.net/2021/rest-servers-in-go-part-7-graphql/
- 5.Go 2D游戏引擎ebiten支持任天堂Switch游戏机 - https://ebiten.org/blog/nintendo_switch.html
- 6.Go WebAssembly与Javascript的互操作 - https://withblue.ink/2020/10/03/go-webassembly-http-requests-and-promises.html
- 7.使用本地Go库的Flutter - https://openprivacy.ca/discreet-log/09-flutter-with-native-go-libraries/
- 8.通过测试学习Go - https://quii.gitbook.io/learn-go-with-tests/
- 9.油管视频：使用eBPF跟踪Go代码 - https://www.youtube.com/watch?v=f1jr9nR25EA
- 10.Go代码整洁之道 - https://dev.to/gopher/clean-go-code-53hn




## go中文网每日资讯--2021-06-11


一、Go语言中文网

1. [go test 的这些用途你都懂吗？](https://mp.weixin.qq.com/s/rt737Zdt30sYw9Fk-5n71A)

2. [源码剖析sync.WaitGroup(文末思考题你能解释一下吗?)](https://mp.weixin.qq.com/s/xT2NdxyMAyRteqtjQbbbyg)

二、亚军进化史

1. [Go技术日报(2021-06-10)——一文教你搞懂 Go 中栈操作](https://mp.weixin.qq.com/s/g_wo4KL5DIQ-7P-ea4ZzTw)

三、奇伢云存储

1. [图解｜进程怎么绑定 CPU](https://mp.weixin.qq.com/s/mbyHJNVyN_0mV5efa2DAXg)

四、学而思网校技术团队

1. [学而思网校直播课堂业务容器化演进](https://mp.weixin.qq.com/s/qsLld2ECUNdhsMLeXfYlDA)

五、polarisxu

1. [不怕烂尾！决定组织翻译这本 Go 图书](https://mp.weixin.qq.com/s/ry-qn0-7GuS0qb6ylU_4qA)

六、脑子进煎鱼了

1. [推荐一位 Go 布道师，另附几百道 Go 面试题](https://mp.weixin.qq.com/s/eHPKzXe5Dmw4rygd3uQ1_A)

七、GoUpUp

1. [Go 每日一库之 tunny](https://mp.weixin.qq.com/s/yXmnijfusgHhJiqXWlw54Q)

八、腾讯技术工程

1. [为什么磁盘存储引擎用 b+树来作为索引结构？](https://mp.weixin.qq.com/s/8gDVqlywLBl-MZa6XrtXug)

九、Go招聘

1. [运维开发有点香哦，广州Gopher这下又有福了](https://mp.weixin.qq.com/s/g737LlDDxsEnQDTd6wgy5Q)

2. [kubernetes面试相关总结(下)](https://mp.weixin.qq.com/s/Tc292lVE1Lue267N5RdunA)





## GOCN每日新闻--2021-06-11

1.Go 1.17 beta 1 发布 (泛型支持) https://groups.google.com/g/golang-dev/c/TfpiXhSOMRM/m/wROPV0blAgAJ 
2.如何使用 GitHub Actions 自动发布你的 Go 二进制应用 https://web3.coach/golang-github-actions-release-binaries-tutorial

3.Go、WebAssembly、HTTP 请求和 Promises https://withblue.ink/2020/10/03/go-webassembly-http-requests-and-promises.html

4.GraphQL 聚合网关 Bramble https://github.com/movio/bramble

5.最后测试开发模式介绍 https://bitfieldconsulting.com/golang/test-last-development



## gopherDaily--2021-06-11

- 1.Go 1.17beta1发布 - https://groups.google.com/g/golang-dev/c/TfpiXhSOMRM/m/wROPV0blAgAJ
- 2.使用Go加快Postgres集成测试的速度 - https://www.maragu.dk/blog/speeding-up-postgres-integration-tests-in-go/
- 3.播客：以不寻常的方式使用Go - https://changelog.com/gotime/183
- 4.Harbor operator 1.0发布 - https://www.cncf.io/blog/2021/06/09/harbor-operator-1-0-is-available-now/
- 5.使用Go编写简单的蒙特卡洛模拟 - https://itnext.io/write-simple-monte-carlo-simulation-5ceb4c9b0eb3
- 6.Go官方语言服务器gopls发布 v0.7.0 - https://github.com/golang/tools/releases/tag/gopls/v0.7.0
- 7.以TDD的方式用Go实现排序算法 - https://alabeduarte.com/test-driven-algorithms/sorting/
- 8.经典旧文：为什么Go不是好语言 - https://yager.io/programming/go.html
- 9.在Kubernetes上如何进行数据库变更的蓝绿部署 - https://piotrminkowski.com/2021/02/18/blue-green-deployment-with-a-database-on-kubernetes/
- 10.开发人员无法修复不良的管理 - https://iism.org/article/developers-can-t-fix-bad-management-57



## go中文网每日资讯--2021-06-10


一、Go语言中文网

1. [Go：内存管理与内存清理](https://mp.weixin.qq.com/s/gTk2UcVCv4a0xuP44oqZhg)

2. [Go看源码必会知识之unsafe包](https://mp.weixin.qq.com/s/dulgHWM-mjrYIdD9nHZyYg)

二、亚军进化史

1. [Go技术日报(2021-06-09)——在 Go 如何实现枚举？](https://mp.weixin.qq.com/s/3qiPaTI3GlDO_ygolZ9wpw)

三、polarisxu

1. [漫画：寻找无序数组的第k大元素（文末送书）](https://mp.weixin.qq.com/s/ycZ8Lh1mjzlrfZoN8lRvEQ)

四、Cloud Native Community

1. [《Istio 大咖说》第3期直播回放|如何让 Istio 变得更为高效和智能](https://mp.weixin.qq.com/s/k3tj6n6lcWfAbu_8k9l5eg   )

五、k8s技术圈

1. [或许这是目前为止最好的 Git 教程了](https://mp.weixin.qq.com/s/MsAO29B05AizHHuOQe_p3g)

六、码农桃花源

1. [曹大带我学 Go（6）—— 技术之外](https://mp.weixin.qq.com/s/OHljMca3k7m__puOUCrrtA)

七、luozhiyun很酷

1. [全网最牛X的！MySQL两阶段提交串讲！没有之一！](https://mp.weixin.qq.com/s/NNRH4TQcCQr4aQw7Cm6zLg)

八、Golang来啦

1. [gRPC入门指南 — 简单RPC（一）](https://mp.weixin.qq.com/s/GnDKAx9bLe90h0rvCQYb6g)

九、奇伢云存储

1. [面试题：mysql 一棵 B+ 树能存多少条数据？](https://mp.weixin.qq.com/s/ItFtW9OLt-x-J--IVzvJ_A)

2. [TCP 连接的前世今生](https://mp.weixin.qq.com/s/f3rDqiDe4isTIBx-RPPN4g)

十、新亮笔记

1. [分享两个在开发中需注意的小点](https://mp.weixin.qq.com/s/-QCG61vh6NVJUWz6tOY7Gw)

十一、Go招聘

1. [一文教你搞懂 Go 中栈操作](https://mp.weixin.qq.com/s/hU6Xmp5zeh9vgUEV5otjWg)

2. [kubernetes面试相关总结(下)](https://mp.weixin.qq.com/s/Tc292lVE1Lue267N5RdunA)


## GOCN每日新闻--2021-06-10

1.Go Runtime 的调度器 https://mp.weixin.qq.com/s/hU6Xmp5zeh9vgUEV5otjWg

2.一文讲懂服务的优雅重启和更新 https://mp.weixin.qq.com/s/yryqf8SCzvt-BFj8j5bZ2w

3.你不知道的 Go 之 pprof https://mp.weixin.qq.com/s/pSD2k1uNH9WFZumw24I4uQ

4.源码剖析 Go 语言的 timer https://mp.weixin.qq.com/s/GwY6650MNF07MOb79-A-jQ

5.一文教你搞懂 Go 中栈操作 https://mp.weixin.qq.com/s/hU6Xmp5zeh9vgUEV5otjWg



## gopherDaily--2021-06-10

1.将一个巨大的金融系统迁移到云端的20,000个pod上 - https://medium.com/virtuslab/migrating-a-gigantic-financial-system-to-20-000-pods-in-the-cloud-220d5fcfcbc0

2.如何使用go 1.16中的go:embed by The GoLand Blog - https://blog.jetbrains.com/go/2021/06/09/how-to-use-go-embed-in-go-1-16/

3.什么是eBPF，为什么它对可观察性很重要？ - https://www.cncf.io/blog/2021/06/07/what-is-ebpf-and-why-does-it-matter-for-observability/

5.如何用Github Actions自动发布你的Go二进制文件 - https://web3.coach/golang-github-actions-release-binaries-tutorial

6.基于OAuth 2.0/OIDC的UI优先的集中认证/单点登录（SSO）平台 - https://github.com/casbin/casdoor

7.用Trimaran在Kubernetes中进行真正的负载感知调度 - https://medium.com/paypal-tech/real-load-aware-scheduling-in-kubernetes-with-trimaran-a8efe14d51e2

8.Hashicorp发布Packer云服务 - https://www.hashicorp.com/blog/announcing-hcp-packer

9.bramble: 生产可用的GraphQL网关 - https://github.com/movio/bramble

10.Redis 作者谈如何处理维护开源项目面对的精神压力 - https://news.ycombinator.com/item?id=27423526

11.用Terraform在Linode上配置Kubernetes集群 - https://learnk8s.io/terraform-lke

12.你使用的开源软件比你想象的要多 - https://github.com/readme/unseen-oss


## 码农桃花源--2021-06-10
### 文章分享
1. [go 栈操作](https://mp.weixin.qq.com/s/hU6Xmp5zeh9vgUEV5otjWg)

2. [go pprof](https://mp.weixin.qq.com/s/pSD2k1uNH9WFZumw24I4uQ)

3. [索引下推](https://mp.weixin.qq.com/s/i2CWsDi8pqISGbwdn9Wm3g)
### 面试题
1. 进程间通信方法，共享内存用了什么系统调用？

2. 段页式内存管理下的逻辑地址和物理地址转换

3. 堆排序建堆的时间复杂度？

4. 常用的GC有哪些？介绍一下Go语言的GC
### 每日算法
[排序]：https://leetcode-cn.com/problems/sort-an-array/（快速排序解法）



## go中文网每日资讯--2021-06-09


一、Go语言中文网

1. [编写友好的Go命令行应用程序](https://mp.weixin.qq.com/s/qOhdWkIG5lZG6hV7QHIsaQ)

2. [优雅地处理Go错误真是一门学问啊！](https://mp.weixin.qq.com/s/_7AHxKJjiS2CRPM8dxdU1Q)

二、亚军进化史

1. [Go技术日报(2021-06-08)——ants源码赏析](https://mp.weixin.qq.com/s/thPxVIT7-X0nccK4px3oPQ)

三、GoUpUp

1. [你不知道的 Go 之 pprof](https://mp.weixin.qq.com/s/pSD2k1uNH9WFZumw24I4uQ)

四、脑子进煎鱼了

1. [小技巧分享：在 Go 如何实现枚举？](https://mp.weixin.qq.com/s/4jvhRQvKlMiYweSOG6xCrA)

2. [答应我，这次一定彻底搞懂 Go 中的类型别名](https://mp.weixin.qq.com/s/pd4KyjikYtZ6UX9jDpYdPw)

五、GoOfficialBlog

1. [Golang Fuzzing is Beta Ready](https://mp.weixin.qq.com/s/wR3B50lh5-CK5Zs9-zNnDg)

六、polarisxu

1. [match 是什么语法？PHP8 也加了](https://mp.weixin.qq.com/s/jUZkFMaC5FThEMHICBwllg)

2. [灵魂拷问：Go 语言这个变量到底分配到哪里了？](https://mp.weixin.qq.com/s/nlpeaMsG90PQ-X44j6mKSg)

七、APISIX云原生微服务网关

1. [开源 API 网关架构分析](https://mp.weixin.qq.com/s/L3X3xfGggjf52a8GofFHEQ)

2. [开源 API 网关架构分析](https://mp.weixin.qq.com/s/L3X3xfGggjf52a8GofFHEQ)

八、杨旭技术专栏

1. [Go 简单分布式系统 3.6 服务发现（4）依赖变化的通知](https://mp.weixin.qq.com/s/Gk43o-85uxbJbgSP7lJomg)

九、码农桃花源

1. [深度解密 Go math/rand](https://mp.weixin.qq.com/s/zQq9lEDLGPh7shvJLm0AuQ)

十、远赴星辰

1. [Go 语言中的零拷贝优化](https://mp.weixin.qq.com/s/SnO_pl8WUmWY9RBFZF7-rA)

十一、Go招聘

1. [东南亚最大的外卖出行公司招聘，这福利，酸了，酸了](https://mp.weixin.qq.com/s/wynt1zdgsRJywFva_gE5dA)

2. [Top云厂商招Gopher，你看你行吗？](https://mp.weixin.qq.com/s/GE05WZBz2SqlwswUhZaJ-Q)


## GOCN每日新闻--2021-06-09

1.Go 语言中的零拷贝优化 https://developer.51cto.com/art/202106/665738.htm

2.Go timer 是如何被调度的？ https://mp.weixin.qq.com/s/iseiQ20eIUR9i02fy1tFhg

3.relite6.0.0 设计，让集群更具鲁棒性 https://www.philipotoole.com/rqlite-6-0-0-building-for-the-future/

4.terraform v1.0.0 正式发布: 兼容性更好,稳定性更强 https://www.terraform.io/docs/language/v1-compatibility-promises.html

5.小技巧分享：在 Go 如何实现枚举？ hhttps://mp.weixin.qq.com/s/4jvhRQvKlMiYweSOG6xCrA


## gopherDaily--2021-06-09

1.Terraform 1.0正式发布！- https://www.hashicorp.com/blog/announcing-hashicorp-terraform-1-0-general-availability

2.godis: 纯Go实现的redis server - https://github.com/HDT3213/godis

3.vault的轻量级Go客户端 - https://github.com/canidam/libvault

4.Go实现的开源分布式关系数据库rqlite发布6.0.0 - https://www.philipotoole.com/rqlite-6-0-0-building-for-the-future/

5.Netflix如何大规模地使用eBPF流量日志来了解网络情况 - https://netflixtechblog.com/how-netflix-uses-ebpf-flow-logs-at-scale-for-network-insight-e3ea997dca96

6.Docker hub将停止提供免费镜像自动构建服务 - https://www.docker.com/blog/changes-to-docker-hub-autobuilds/

7.kuma: Go实现的通用服务网格, CNCF sandbox项目 - https://github.com/kumahq/kuma

8.使用Istio和Nginx ingress - https://www.giffgaff.io/tech/using-istio-with-nginx-ingress

9.通过nginx的优雅退出了解k8s pod的生命周期 - https://itnext.io/kubernetes-nginx-php-fpm-graceful-shutdown-and-502-errors-b2878cc3df5d

10.SQLite作者用C实现的webserver - https://sqlite.org/althttpd/doc/trunk/althttpd.md


## gopherDaily--2021-06-09
### 文章分享
1. [Redis 面试集锦](https://www.yuque.com/u2278269/gq5x74/xalawt)

2. [Redis 通用命令](https://www.yuque.com/u2278269/gq5x74/ud8u4y)

3. [timeout](https://mp.weixin.qq.com/s/SllMlL_94cir-x8Hw9D-8g)

### 面试题
1. Redis 数据类型有哪些

2. Redis List底层实现

3. AOF 为什么要先执行命令再记日志呢 

4. Redis AOF 三种写回策略

### 每日算法
「二叉树的后序遍历」：https://leetcode-cn.com/problems/binary-tree-postorder-traversal/



## go中文网每日资讯--2021-06-08


一、Go语言中文网

1. [字节跳动打造的轮子：Go 表单验证器](https://mp.weixin.qq.com/s/Oc90iCYyZGj5uDKhj8eGWw)

2. [Go1.16 中的新函数 signal.NotifyContext 怎么用？](https://mp.weixin.qq.com/s/LLKgeGmhU_GpQQeivEvi1g)

3. [Go 每日一库之 reflect](https://mp.weixin.qq.com/s/3kE_M9jKTG14t3KIlkqhgA)

二、亚军进化史

1. [Go技术日报(2021-06-07)——如何进行 Golang 单元测试](https://mp.weixin.qq.com/s/FJ26X5wrqFqB7XJEgMsV5w)

三、码农桃花源

1. [一个高逼格的 Go 招聘](https://mp.weixin.qq.com/s/lFrmy68XTF79kO3iCD9l6A)

2. [你真的了解 timeout 吗？](https://mp.weixin.qq.com/s/SllMlL_94cir-x8Hw9D-8g)

四、k8s技术圈

1. [云原生 CI/CD 框架 Tekton 初体验](https://mp.weixin.qq.com/s/ZI9vWJ4giVsMhxZYHjjd5A)

五、杨旭技术专栏

1. [Go 简单分布式系统 3.4 服务发现（2）](https://mp.weixin.qq.com/s/dLtyKjJ5_p0aiyx9BMGEYg)

2. [Go 简单分布式系统 3.5 服务发现（3）](https://mp.weixin.qq.com/s/SQbOS1xRECM2Oa-tXjEkfw)

六、GoUpUp

1. [Go 每日一库之 ants（源码赏析）](https://mp.weixin.qq.com/s/a84T6Hpbrhop7vQA01N1Bg)

七、GolangContributorClub

1. [2021 中国 Go 语言开源贡献者峰会预告](https://mp.weixin.qq.com/s/-FWxWGVJEVe8JPPcGqHxgw)

八、HHFCodeRv

1. [Go timer 是如何被调度的？](https://mp.weixin.qq.com/s/iseiQ20eIUR9i02fy1tFhg)

九、polarisxu

1. [一本花了2.5年写成的Go免费在线图书](https://mp.weixin.qq.com/s/Z97eT7FrqeJhygQwKvJaIw)

十、Go招聘

1. [一文带你深究无线缓冲channel的实现](https://mp.weixin.qq.com/s/7P3Gn7JFvMWUh0iuNExPKA)

2. [东南亚最大的外卖出行公司招聘，这福利，酸了，酸了](https://mp.weixin.qq.com/s/wynt1zdgsRJywFva_gE5dA)

## GOCN每日新闻--2021-06-08

1.在 Golang 中创建自定义应用程序 logger https://jilsonfreddy.medium.com/create-a-custom-application-logger-in-golang-cdd11ba106d5

2.在 Go 1.16+ 中构建 GUI 桌面应用程序 https://blog.ctrlshiftmake.com/build-tray-gui-desktop-application-go

3.Go 实现为以太坊智能合约创建绑定 https://www.metachris.com/2021/05/creating-go-bindings-for-ethereum-smart-contracts/

4.Go 中简单、可定制、分级且高效的日志记录 https://github.com/ermanimer/log

5.Go 实现的发送原始 HTTP 请求的基准测试和压力测试工具 https://github.com/utkusen/reqstress


## gopherDaily--2021-06-08
1.为什么Go应该是你开发区块链的首选语言？ - https://www.rnssol.com/blog/why-golang-should-be-your-go-to-language-for-developing-blockchains

2.微软招聘高级软件工程师参与Go官方编译器、工具生态开发 - https://careers.microsoft.com/us/en/job/1038385/Senior-Software-Engineer

3.2021 中国 Go 语言开源贡献者峰会预告 - https://mp.weixin.qq.com/s/-FWxWGVJEVe8JPPcGqHxgw

4.使用Go和cube.js构建你自己的网站分析工具 - https://itnext.io/build-your-own-website-analytics-with-cube-js-in-10-minutes-f195ed5d4d21

5.使用Go 1.16构建桌面GUI应用 - https://blog.ctrlshiftmake.com/build-tray-gui-desktop-application-go

6.最后测试(TLD)简介(Test-Last Development)：https://bitfieldconsulting.com/golang/test-last-development

7.2021年及以后的DevOps预测 - https://harness.io/blog/devops/devops-predictions/

8.Docker安全实践速查表 - https://cheatsheetseries.owasp.org/cheatsheets/Docker_Security_Cheat_Sheet.html

9.提高开发人员的工作效率：BuildKit CLI for kubectl是docker build的替代品 - https://container-registry.com/posts/productivity-lift-buildkit-cli-for-kubectl/

10.理解defer关键字 - https://syed-hasan-83344.medium.com/understanding-defer-keyword-in-go-lang-b02c7f406870

11.开源项目维护不易，docz维护者的心路历程 - https://github.com/pedronauck/docz/issues/1634

## go中文网每日资讯--2021-06-07


一、Go语言中文网

1. [Go 调度器的任务窃取（Work-Stealing）](https://mp.weixin.qq.com/s/trBAi976eaaTDcSzpAqPkQ)

2. [通过实例理解Go逃逸分析](https://mp.weixin.qq.com/s/bR9shJGRXsRHJhh-GcY83A)

二、亚军进化史

1. [Go技术日报(2021-06-06)——微服务拆分之道](https://mp.weixin.qq.com/s/GgBhnYS1KYFHq4mzgIFj7w)

三、脑子进煎鱼了

1. [Go 凭什么不支持三元运算符？](https://mp.weixin.qq.com/s/LmHR7Y674dSo-Xa0tajL_w)

2. [一文搞懂如何实现 Go 超时控制](https://mp.weixin.qq.com/s/S4d9CJYmViJT8EbhyNCIMg)

四、Golang梦工厂

1. [神奇的init函数](https://mp.weixin.qq.com/s/y-H0y1ahq8a_TgJ4c4otuQ)

五、杨旭技术专栏

1. [Go 简单分布式系统 3.3 服务发现（1）](https://mp.weixin.qq.com/s/QoDwEbl02nSHjRci8yRbyQ)

六、Go招聘

1. [Golang 并发编程核心篇 —— 内存可见性](https://mp.weixin.qq.com/s/vvKNAarcc3kz1hz9o4B1ZQ)

七、腾讯技术工程

1. [​手把手教你如何进行 Golang 单元测试](https://mp.weixin.qq.com/s/N5wby-aWWEPc7mHN_lN3lQ)

八、云加社区

1. [主干开发、主干发布，CI 如何为大型项目提供最优解？](https://mp.weixin.qq.com/s/mQihX1VbEEArHpcx6s5KFQ)

九、奇伢云存储

1. [自制文件系统 —— 03 Go实战：hello world 的文件系统](https://mp.weixin.qq.com/s/Yf6yBoEQe6ijMlPgZ6P2sA)

十、码农桃花源

1. [曹大带我学 Go（5）—— 哪里来的 goexit](https://mp.weixin.qq.com/s/xrDZ2Z7KkHL0vZ3k6KGcyg)

## GOCN每日新闻--2021-06-07

1.Code Review 引发的 Golang Memory Model 深入思考 https://juejin.cn/post/6970513766509182984

2.Go 高性能系列教程之一：基准测试 https://gocn.vip/topics/12126

3.监控是手段，而不是目的  https://www.robustperception.io/monitoring-is-a-means-not-an-end

4.Calico 路由反射模式权威指南 https://mp.weixin.qq.com/s/hLiI9fsPQ7w4PS2ALff09g

5.从栈上理解 Go 语言函数调用 https://www.cnblogs.com/luozhiyun/p/14844710.html


## gopherDaily--2021-06-07

- 1.Go context包的上下文 - https://asheetbhaskar.medium.com/context-about-context-package-in-golang-487ef60d9acc
- 2.为什么服务跟踪将替代所有日志手段 - https://go.lightstep.com/rs/260-KGM-472/images/Tracing-Will-Replace-Logging-Guide.pdf
- 3.内部服务的go单点登录方案 - https://github.com/buzzfeed/sso
- 4.在Go中创建自定义logger - https://jilsonfreddy.medium.com/create-a-custom-application-logger-in-golang-cdd11ba106d5
- 5.惊！这个 Go 开源项目号称「不改一行代码做秒杀」 - https://mp.weixin.qq.com/s/NSJmV-hBucaXoBAfD3TKLA
- 6.一文讲懂服务的优雅重启和更新 - https://mp.weixin.qq.com/s/yryqf8SCzvt-BFj8j5bZ2w
- 7.视频教程：Go初学者教程 - https://tutorialedge.net/courses/go-beginners-guide/
- 8.Kubernetes单点登录指南 - http://www.talkingquickly.co.uk/kubernetes-sso-a-detailed-guide
- 9.kubestr: 一个工具集合，用于发现、验证和评估你的kubernetes存储选项 - https://kubestr.io/
- 10.除了编码之外，高级工程师所需技能的不完整清单 - https://skamille.medium.com/an-incomplete-list-of-skills-senior-engineers-need-beyond-coding-8ed4a521b29f
- 11.主流分布式文件系统对比 - https://mp.weixin.qq.com/s/XgCjWKtqc2Mi_cqRj9_2xw




## 码农桃花源--2021-06-07
### 文章分享
1. [互斥锁，自旋锁，悲观锁，乐观锁总结](https://blog.csdn.net/qq_34827674/article/details/108608566)

2. [高并发服务遇 redis 瓶颈引发的事故](https://mp.weixin.qq.com/s/MtdU1xhOI5XkuSDrIYFRMA)

3. [redis实现自动输入完成](https://www.cnblogs.com/like-minded/p/5239444.html)

### 面试题
1. redis分布式锁是如何实现的?

2. 使用过redis做异步队列吗？如何用？有什么缺点？

3. redis相比于memcached，有何优势？

4. redis的数据淘汰策略？

### 每日算法
「二叉树的后序遍历」：https://leetcode-cn.com/problems/binary-tree-postorder-traversal/

## go中文网每日资讯--2021-06-06


一、Go语言中文网

1. [Go1.17这个新特性竟然是6年前提出来的](https://mp.weixin.qq.com/s/7OY_2FRpD0QvzuWTACVqyw)

2. [Go语言爱好者周刊：第 98 期 — 附上期题解](https://mp.weixin.qq.com/s/MAaCJGqJlf9cY_c1Urtadw)

3. [你不知道的 Go 之 const](https://mp.weixin.qq.com/s/EKnphU752SY1vp_O_qY1ag)

二、亚军进化史

1. [Go技术日报(2021-06-05)——Go 内存管理概述](https://mp.weixin.qq.com/s/08ROk0QSZopAL6wZMN715A)

三、k8s技术圈

1. [Kubernetes 资源对象序列化实现](https://mp.weixin.qq.com/s/fJf1mtCR49XO7BOUn2FRTg)

四、爱倒腾的程序员

1. [人均估值5000万RMB，53岁程序员能做到的，你也能！](https://mp.weixin.qq.com/s/iT-wWGskSJdtAkJsOLJWuw)

五、董泽润的技术笔记

1. [我用kafka两年踩过的一些非比寻常的坑](https://mp.weixin.qq.com/s/18qn85grHRF7iIVobJVUwA)

六、Go招聘

1. [股友问：Kafka为什么会丢消息，如何解决呢？](https://mp.weixin.qq.com/s/qv4-KuUfv1UwuDzcFahW4w)



## GOCN每日新闻--2021-06-06
1.详解 Go 团队不建议用的 unsafe.Pointer https://mp.weixin.qq.com/s/8qtHdw2JiRQ1cXlzbJ0ANA

2.新 Goland 插件支持 TinyGo https://blog.jetbrains.com/go/2021/06/02/tinygo-for-tiny-applications-discover-a-new-plugin-for-goland/

3.使用 go-i18n 实现国际化 https://lokalise.com/blog/go-internationalization-using-go-i18n/

4.awesome-go-orms https://github.com/d-tsuji/awesome-go-orms

5.Go 实现终端 slide 展示工具 https://github.com/maaslalani/slides


## gopherDaily--2021-06-06

1.为什么要从头开始编写你自己的API网关 - https://itnext.io/why-should-you-write-your-own-api-gateway-from-scratch-378074bfc49e

2.Go实现的基于命令行终端的slide演示工具 - https://github.com/maaslalani/slides

3.promdump：支持读取和打印Prometheus持久性数据块，支持按时间范围过滤持久性块 - https://github.com/ihcsim/promdump

4.搭建云原生配置中心的技术选型和落地实践 - https://mp.weixin.qq.com/s/_Ir3dhbWjl_miQba_RuayQ

5.关于kubernetes configmap，初学者不可能知道的事情 - https://blog.gopaddle.io/2021/04/01/strange-things-you-never-knew-about-kubernetes-configmaps-on-day-one/

6.微服务拆分之道 - https://mp.weixin.qq.com/s/oBfEwwOyrSwGag8zs8ljFA

7.k8s ssl证书管理 - https://betterprogramming.pub/kubernetes-and-ssl-certificate-management-5f6a4b6f5ae9

8.go orm开源项目大全 - https://github.com/d-tsuji/awesome-go-orms

9.Kubernetes中的混沌工程开源解决方案 - https://blog.flant.com/chaos-engineering-in-kubernetes-open-source-tools/

10.minideb: 一个基于Debian的极简镜像，专门用来作为容器的基础镜像 - https://github.com/bitnami/minideb

11.油管视频：硬件破解教程 - https://www.youtube.com/playlist?list=PLoFdAHrZtKkhcd9k8ZcR4th8Q8PNOx7iU

12.艰苦的工作和微薄的报酬给开源维护者带来压力 - https://www.zdnet.com/article/hard-work-and-poor-pay-stresses-out-open-source-maintainers/

13.观点：你越快停止对OOP的学习，对你和你的软件就越有利 - https://dpc.pw/the-faster-you-unlearn-oop-the-better-for-you-and-your-software



## go中文网每日资讯--2021-06-05


一、Go语言中文网

1. [Go实战项目：打造一个七牛云图片处理服务](https://mp.weixin.qq.com/s/SEVpbHyhohX8tpX130T7lQ)

2. [Go 中的动态作用域变量是什么鬼？](https://mp.weixin.qq.com/s/bU6U5LfRsPLAN7DSoVkbUA)

3. [Leetcode 上的小偷太难了！！](https://mp.weixin.qq.com/s/xdEDhpTT9lyeyJZIXxduGQ)

二、亚军进化史

1. [Go技术日报(2021-06-04)——Go 1.16.5 和 Go 1.15.13 发布](https://mp.weixin.qq.com/s/cIhuWRAyTkXqdz7iswj4Ng)

2. [Go技术日报(2021-06-03)——Go 重构和转换工具](https://mp.weixin.qq.com/s/iVhk1EdzQvWboQXdf8HiAA)

三、k8s技术圈

1. [在 Kubernetes 上使用 Spinnaker 构建部署流水线](https://mp.weixin.qq.com/s/znkK6mJw3JNhUNkeEeRDrg)

四、云原生技术爱好者社区

1. [使用Kubernetes重新思考系统架构并减轻技术债务](https://mp.weixin.qq.com/s/BFf2MQQYUpNu8xZ-QqMcMw)



## GOCN每日新闻--2021-06-05

1.vtprotobuf: 高性能 gogoprotobuf 替代品，兼容 ProtoBuf APIv2 https://vitess.io/blog/2021-06-03-a-new-protobuf-generator-for-go/

2.『每周译 Go』Go 内存管理概述 https://mp.weixin.qq.com/s/PNRhtdS_gZVTtrkkRmx7yA

3.LazyLRU 应用至生产环境 https://medium.com/bluecore-engineering/lazylru-laughing-all-the-way-to-production-19d2a053c3cb

4.GoLand 发布 2021.2 EAP build #2 https://blog.jetbrains.com/go/2021/06/04/goland-2021-2-eap-build-2-is-here/

5.photoprism：开源的 Google Photos 替代品 https://github.com/photoprism/photoprism


## gopherDaily--2021-06-05
1.生产环境被破坏：原因居然是在Go中进行前一个月的计算 - https://dev.to/nordcloud/how-a-calculation-of-previous-month-in-golang-can-break-production-1ppi

2。为什么go工具链需要原生支持fuzz test - https://docs.google.com/document/d/1N-12_6YBPpF9o4_Zys_E_ZQndmD06wQVAM_0y9nZUIE/edit

3.新提案：syscall包增加Syscall21和Syscall24 - https://github.com/golang/go/issues/46552

4.panicparse v1.6.0发布在v2.0.1之后，作者咋想的？ - https://maruel.ca/post/panicparse-1.6.0/

5.以太坊智能合约的go绑定 - https://www.metachris.com/2021/05/creating-go-bindings-for-ethereum-smart-contracts/

6.新提案：添加net/netaddr包：增加新的IP地址类型 - https://github.com/golang/go/issues/46518

7.Uber 的 API 网关架构[译] - https://mp.weixin.qq.com/s/Z6IwBkCc357u3OxWMDRH2g

8.已成为RFC9000的QUIC协议的Go实现 - https://github.com/goburrow/quic

9.terraform教程 by hashicorp learn - https://www.hashicorp.com/blog/new-terraform-tutorials-on-hashicorp-learn

10.使用静态分析工具分析linux内核代码 - https://thenewstack.io/checking-linuxs-code-with-static-analysis-tools/

11.如何在Go中使用chrono调度task - https://itnext.io/how-to-schedule-tasks-using-chrono-in-golang-16a39b14a79a


## go中文网每日资讯--2021-06-04


一、Go语言中文网

1. [Go1.16.5 发布](https://mp.weixin.qq.com/s/-dYlKTEWuGTqIQYKQ3sETQ)

2. [用 cgo 生成用于 cgo 的 C 兼容的结构体](https://mp.weixin.qq.com/s/bqUPN6wwua4x2_FOwyzkYg)

3. [详解并发编程之sync.Once的实现(附上三道面试题)](https://mp.weixin.qq.com/s/S4xnlFgnU0kM3h1gOv774g)

二、脑子进煎鱼了

1. [一道 Go 闭包题，面试官说原来自己答错了：面别人也涨知识](https://mp.weixin.qq.com/s/OLgsdhXGEMltmjcpTW2ICw)

三、董泽润的技术笔记

1. [你真的了解 timeout 嘛？](https://mp.weixin.qq.com/s/GihBqN5m0vGxxvFdHWRc7Q)

2. [格步科技招聘](https://mp.weixin.qq.com/s/h_EvR33U3c0bRQCIkkr7xQ)

四、GoUpUp

1. [Go 每日一库之 ants](https://mp.weixin.qq.com/s/ysG0q9LIYgWHIoY_LK-W9A)

五、polarisxu

1. [被黑惨了：一句话，说明自己会 Go，咋整？](https://mp.weixin.qq.com/s/igB7Zl-InaWdDCAX7OdVWQ)

六、Go招聘

1. [详解 Go 空结构体的 3 种使用场景](https://mp.weixin.qq.com/s/8NJLe_11uvu22HfDjKqKjQ)

2. [小博居然被表白](https://mp.weixin.qq.com/s/Vc0QBmFVh5ct6ttTMqc-_w)

七、taowen

1. [噢，你的代码像一坨翔。然后呢？](https://mp.weixin.qq.com/s/mHDY9RbTAjsArqX3S5jxNw)

八、吴亲强的深夜食堂

1. [i/o timeout ， 希望你不要踩到这个net/http包的坑](https://mp.weixin.qq.com/s/Isjv1fTYd0m8yrjONINsWw)
 
 
## GOCN每日新闻--2021-06-04
1.Go 1.16.5 和 Go 1.15.13 发布 https://groups.google.com/g/golang-announce/c/RgCMkAEQjSI/m/r_EP-NlKBgAJ

2.自动测试工具 Fuzzing 发布 beta  https://blog.golang.org/fuzz-beta

3.OpenYurt v0.4.0 新特性发布：高效地管理边缘存储资源  https://gocn.vip/topics/12152

4.stringer 命令，通过代码生成提高效率  https://mp.weixin.qq.com/s/Ik3PxNRbddtbm6E-Xo_rdA

5.假如 Go 能说话，听听 GMP 的心声 https://mp.weixin.qq.com/s/eHXAPQkzwMTaLVrXESowBg


## gopherDaily--2021-06-04
1.Go原生fuzzing test开启beta测试 - https://blog.golang.org/fuzz-beta

2.Go 1.16.5和Go 1.15.13发布 - https://groups.google.com/g/golang-announce/c/RgCMkAEQjSI/m/r_EP-NlKBgAJ

3.vtprotobuf: 一个protobuf编译器，为ProtoBuf APIv2生成优化的marshaling和unmarshaling Go代码 - https://github.com/planetscale/vtprotobuf

4.kubernetes水族馆 - https://medium.com/@AnneLoVerso/the-kubernetes-aquarium-6a3d1d7a2afd

5.谷歌发布”Open Source Insights”站点，提供开源项目的依赖包的互动视图 - https://opensource.googleblog.com/2021/06/introducing-open-source-insights-project.html

6.使用go-i18n实现Go国际化 - https://lokalise.com/blog/go-internationalization-using-go-i18n/

7.gProfiler：结合多个采样分析器，对CPU开销进行统一的可视化分析，支持Go、Java和Python - https://github.com/Granulate/gprofiler

8.Kubernetes资源大全 - https://kubernetesreadme.com/

9.用Docker的Buildx Kubernetes驱动将构建时间减少一半 - https://releasehub.com/blog/cutting-build-time-in-half-docker-buildx-kubernetes

10.经典旧文：理解linux网络协议栈 - https://www.privateinternetaccess.com/blog/linux-networking-stack-from-the-ground-up-part-1/

11.docker公司开发人员从以办公室为中心到以远程为中心的历程 - https://www.docker.com/blog/our-journey-from-office-centric-to-remote-first/

## 码农桃花源--2021-06-04
### 文章分享
1. [go编程模式](https://coolshell.cn/articles/21140.html)

2. [mysql面试题](https://www.yuque.com/u2278269/gq5x74/nef7ro)

3. [go修养之路](https://www.kancloud.cn/aceld/golang/1958303)

### 面试题
1. 输出什么
```go
package main
import "fmt"
func DeferFunc1(i int) (t int) {
    t = i
    defer func() {
        t += 3
    }()
    return t
}
func DeferFunc2(i int) int {
    t := i
    defer func() {
        t += 3
    }()
    return t
}
func DeferFunc3(i int) (t int) {
    defer func() {
        t += i
    }()
    return 2
}
func DeferFunc4() (t int) {
    defer func(i int) {
        fmt.Println(i)
        fmt.Println(t)
    }(t)
    t = 1
    return 2
}
func main() {
    fmt.Println(DeferFunc1(1))
    fmt.Println(DeferFunc2(1))
    fmt.Println(DeferFunc3(1))
    DeferFunc4()
}
```

2.  new的变量在栈还是堆?

3. 背景:我们现在有一张表,每天生成300W数据, 然后每天用delete xx where id = x 这样的方式来删除.
> 不用truncate是因为DBA说truncate会重建自适应哈希索引,可能对整个库性能有影响.
操作:
这个表的主键id是递增的.
当我执行 explain select min(id) from t 时,是走的全表扫描.
而且我目前在从库执行这个sql,直接就卡住了.
执行 explain select max(id) from t 时, 结果是 Select tables optimized away
(目前最大id 5亿左右,实际数据量只有300W)
问题:

1. 为什么 min(id) 会是全表扫描呢? 是和存在大量的delete后未释放空间有关系吗?

2. 像这种业务场景,mysql怎么处理比较快速呢? 使用rename 表名有什么风险吗?

### 每日算法
「N叉树的前序遍历」：https://leetcode-cn.com/problems/n-ary-tree-preorder-traversal/

## go中文网每日资讯--2021-06-03


一、Go语言中文网

1. [Go: stringer 命令，通过代码生成提高效率](https://mp.weixin.qq.com/s/Ik3PxNRbddtbm6E-Xo_rdA)

2. [详解并发编程基础之原子操作(atomic包)](https://mp.weixin.qq.com/s/-KE6jNKkVxNrm-e3laibzw)

二、亚军进化史

1. [Go技术日报(2021-06-02)——从数据库创建 gRPC 服务器](https://mp.weixin.qq.com/s/JqM9c9vW6nkwQH9gcVQojg)

三、新亮笔记

1. [函数的不定参数你是这样用吗？](https://mp.weixin.qq.com/s/jvSbZ0_g_EFqaR2TmjjO8w)

四、taowen

1. [如何不 Review 每一行代码，同时保持代码不被写乱？](https://mp.weixin.qq.com/s/UtBkJYpQHIvRQ_AQnzxxMw)

五、码农桃花源

1. [假如 Go 能说话，听听 GMP 的心声](https://mp.weixin.qq.com/s/eHXAPQkzwMTaLVrXESowBg)

六、CloudNativeCommunity

1. [直播回放 | Istio 大咖说第 2 期：从微服务架构到 Istio—— 架构升级实践分享](https://mp.weixin.qq.com/s/huZaJVK5qXVrQFfDlha5zQ)

七、polarisxu

1. [惊！这个 Go 开源项目号称「不改一行代码做秒杀」](https://mp.weixin.qq.com/s/NSJmV-hBucaXoBAfD3TKLA)

八、云加社区

1. [超全代码！详解Go中内存分配源码实现](https://mp.weixin.qq.com/s/_SYT7zWqvFnfH02cHFOgow)

九、腾讯技术工程

1. [十个问题理解Linux epoll工作原理](https://mp.weixin.qq.com/s/h3CBZt2KEA-ScXFSKHaRBg)

十、脑子进煎鱼了

1. [详解 Go 团队不建议用的 unsafe.Pointer](https://mp.weixin.qq.com/s/8qtHdw2JiRQ1cXlzbJ0ANA)

十一、Go招聘

1. [一文带你由浅入深地解读Zap的高性能](https://mp.weixin.qq.com/s/Qc5tGELKPZOA9LEBOEkuow)

## GOCN每日新闻--2021-06-03

1.基于 cdp 协议开发的浏览器自动化工具 rod  https://go-rod.github.io/i18n/zh-CN/#/get-started/README

2.Go 重构和转换工具  https://github.com/uber-go/gopatch#gopatch
3.开发小应用的 jetbrains 插件 tinygo   https://blog.jetbrains.com/go/2021/06/02/tinygo-for-tiny-applications-discover-a-new-plugin-for-goland/

3.使用 httputil 反向代理工具将 grpc rest & html 绑定到一个端口上  https://medium.com/james-reads-public-cloud-technology-blog/using-a-httputil-reverse-proxy-to-host-grpc-rest-html-on-a-single-port-9d3f629762b7

4.Pre-commit-golang 支持 revive 了 https://github.com/TekWizely/pre-commit-golang/releases/tag/v0.8.3

## gopherDaily--2021-06-03

- 1.Go应用lint指南 - https://freshman.tech/linting-golang/

- 2.用eBPF编写的简单跨语言（Go、Rust、C/C++）连续性能剖析器 - https://blog.px.dev/cpu-profiling-2/

- 3.Go学习资源 - https://kush01.hashnode.dev/resources-for-learning-go

- 4.探索goland上的tinygo插件 - https://blog.jetbrains.com/go/2021/06/02/tinygo-for-tiny-applications-discover-a-new-plugin-for-goland/

- 5.gopatch：又一款go重构工具 - https://github.com/uber-go/gopatch

- 6.使用httputil反向代理在单一端口托管gRPC REST和HTML - https://medium.com/james-reads-public-cloud-technology-blog/using-a-httputil-reverse-proxy-to-host-grpc-rest-html-on-a-single-port-9d3f629762b7

- 7.基于IPv6的无状态k8s overlay网络 - https://john-millikin.com/stateless-kubernetes-overlay-networks-with-ipv6

- 8.netz: 发现互联网组件服务的配置错误  - https://github.com/SpectralOps/netz

- 9.在github上搭建私有helm仓库 - https://jasiek-petryk.medium.com/setting-up-a-private-helm-chart-repository-on-github-4a767703cec8

- 10.揭秘有状态服务上 Kubernetes 的核心技术 - https://mp.weixin.qq.com/s/TvZZVow5H9HwMrNBLLoSsQ

- 11.开放原子开源基金会项目毕业标准V1.0发布 - https://mp.weixin.qq.com/s/CTetamKpZFcQdXBtQbqBPw


## 码农桃花源--2021-06-03
### 文章分享
1. [mvcc](https://blog.csdn.net/filling_l/article/details/112854716)

2. [行格式和行溢出](https://www.yuque.com/u2278269/gq5x74/pzkge7)

3. [白话GPM](https://mp.weixin.qq.com/s/eHXAPQkzwMTaLVrXESowBg)

### 面试题
1. 如何优化 BLOB这类变长大字段

2.  Read Committed隔离级别是如何基于ReadView机制实现的

3. 背景:我们现在有一张表,每天生成300W数据, 然后每天用delete xx where id = x 这样的方式来删除.
不用truncate是因为DBA说truncate会重建自适应哈希索引,可能对整个库性能有影响.
操作:
这个表的主键id是递增的.
当我执行 explain select min(id) from t 时,是走的全表扫描.
而且我目前在从库执行这个sql,直接就卡住了.
执行 explain select max(id) from t 时, 结果是 Select tables optimized away
(目前最大id 5亿左右,实际数据量只有300W)
> 问题:
1. 为什么 min(id) 会是全表扫描呢? 是和存在大量的delete后未释放空间有关系吗?

2. 像这种业务场景,mysql怎么处理比较快速呢? 使用rename 表名有什么风险吗?

### 每日算法
「N叉树的前序遍历」：https://leetcode-cn.com/problems/n-ary-tree-preorder-traversal/

## go中文网每日资讯--2021-06-02

一、Go语言中文网

1. [Go避坑指南：这些错误你犯过吗？](https://mp.weixin.qq.com/s/UPvMC-JD5qpE0_4MdczwwA)

2. [LeetCode 啥题都有：Go 刷「打家劫舍」二](https://mp.weixin.qq.com/s/X8AYwdWJa90vRZX_PDFfqA)

3. [Go基础：利用反射来修改变量的值](https://mp.weixin.qq.com/s/1bMNJmfLbjOgBGjofyBiJg)

二、亚军进化史

1. [Go技术日报(2021-06-01)—— 初识 ast 的威力](https://mp.weixin.qq.com/s/-qJ3_H-mi6BoRpKX-7erFA)

三、脑子进煎鱼了

1. [Go 开发要了解的 1 个内存模型细节](https://mp.weixin.qq.com/s/zwY0FaTZZuj4tTuvWubOww)

2. [Go 并发编程 — 深入浅出 sync.Pool](https://mp.weixin.qq.com/s/1hLgu2XBBJkLzvI6pOR80g)

四、k8s技术圈

1. [使用 Flux+Flagger+Istio+Kubernetes 实战 GitOps 云原生渐进式(金丝雀)交付](https://mp.weixin.qq.com/s/1NrYXTvN5G8L1xdP4lVGtQ)

五、幼麟实验室

1. [【Golang】T和*T的方法集是啥关系？](https://mp.weixin.qq.com/s/wq6O4dyYC9dwzyUzNLkybg)

六、polarisxu

1. [牛逼，一位年轻有为的 Go 大佬！](https://mp.weixin.qq.com/s/RU7lPhQ8YceQ6BCNzpfZ3g)

七、腾讯云原生

1. [揭秘有状态服务上  Kubernetes 的核心技术](https://mp.weixin.qq.com/s/TvZZVow5H9HwMrNBLLoSsQ)

八、Go夜读

1. [MySQL：好好的索引，为什么要下推？](https://mp.weixin.qq.com/s/i2CWsDi8pqISGbwdn9Wm3g)



## GOCN每日新闻--2021-06-02

1.OpenKruise v0.9.0 版本发布：新增 Pod 重启、删除防护等重磅功能 https://gocn.vip/topics/12146

2.Go 正则表达式库之 commonregex https://gocn.vip/topics/12143

3.使用 httputil 反向代理在单个端口上托管 gRPC REST 和 HTML https://medium.com/james-reads-public-cloud-technology-blog/using-a-httputil-reverse-proxy-to-host-grpc-rest-html-on-a-single-port-9d3f629762b7

4.Go 泛型在函数式编程中的应用 https://ani.dev/2021/05/25/functional-programming-in-go-with-generics/

5.从数据库创建 gRPC 服务器 https://github.com/walterwanderley/xo-grpc

## gopherDaily--2021-06-02
- 1.如何在Golang中正确地使用defer - https://qvault.io/golang/defer-golang/

- 2.tstorage: go实现的时序数据库 - https://github.com/nakabonne/tstorage

- 3.easegress: 全能型流量编排系统 - https://github.com/megaease/easegress

- 4.Go函数作为“一等公民”的基础 - https://dev.to/andyhaskell/basics-of-first-class-functions-in-go-d5p
 
- 5.calico网络插件集成WireGuard - https://thenewstack.io/calico-integration-with-wireguard-using-kops/

- 6.kubernetes vs. openshift，你应该知道的事情 - https://faun.dev/c/stories/qudems/kubernetes-vs-openshift-this-is-what-you-need-to-know/

- 7.Kubernetes: 选择最佳的自动伸缩策略 - https://learnk8s.io/kubernetes-autoscaling-strategies
 
- 8.将redhat Keycloak打包到Distroless镜像中再部署在k8s上 - https://dev.to/stack-labs/keycloak-on-distroless-into-kubernetes-f5g

- 9.破坏和修复Kubernetes - https://itnext.io/breaking-down-and-fixing-kubernetes-4df2f22f87c3

- 10.DevOps网站如何打击加密货币矿工 - https://thenewstack.io/how-devops-sites-are-battling-cryptocurrency-miners/

## 码农桃花源--2021-06-02
### 文章分享
1. [mysql 面试题](https://mp.weixin.qq.com/s?__biz=MzkzNTEwOTAxMA==&mid=2247484479&idx=1&sn=97358231f0f7086f0056fc5bb4e8afff&chksm=c2b24cc2f5c5c5d4935a4a0c0c8adb912a08e3aa7d7ac06f62dad5826e4093b732e4e3ff73b4&scene=178&cur_album_id=1512519209967271939#rd)

2. [MySQL中binlog和redo log的一致性问题](https://blog.csdn.net/huangjw_806/article/details/100927097)

3. [泽润大佬聊聊并发安全](https://mp.weixin.qq.com/s/8qXfm0UqK4R1tJyK0_zYQg)

### 面试题
1. 什么是间隙锁

2. MySQL是怎么做到binlog和redo log的一致性的呢？

3.  MySQL 自增主键什么情况下顺序会出现断裂？

### 每日算法

「N叉树的后序遍历」：https://leetcode-cn.com/problems/n-ary-tree-postorder-traversal/




## go中文网每日资讯--2021-06-01


一、Go语言中文网

1. [推荐一本免费的 Go 新书：用 Go 讲架构的书](https://mp.weixin.qq.com/s/SoqxlvEOyV6EtjKTWGEyxw)

2. [Go 每日一库之 fasttemplate](https://mp.weixin.qq.com/s/_ZIB3H1kJwb8s53lIQ-7Sw)

3. [在容器里设置GOMAXPROCS的正确姿势](https://mp.weixin.qq.com/s/jVyKb_3YS9ETX4JmIuhWJA)

二、亚军进化史

1. [Go技术日报(2021-05-31)——GM到GMP，Golang经历了什么？](https://mp.weixin.qq.com/s/C8div9JeTabqgp9dzVDe8w)

三、微服务实践

1. [自适应微服务治理背后的算法](https://mp.weixin.qq.com/s/OpF4JVWHA9W1v0yefeo56w)

四、k8s技术圈

1. [用 Rust 编写的 Git 极速终端 UI](https://mp.weixin.qq.com/s/NlVq30gs6qcdg3CQBS8-IA)

五、新亮笔记

1. [优雅地处理错误真是一门学问啊！](https://mp.weixin.qq.com/s/W_LsZtnjGIKQ-LB6EkRgBA)

六、GoUpUp

1. [Go 每日一库之 reflect](https://mp.weixin.qq.com/s/KoHYoQ0q9qVjOWLPAIWaAA)

七、Go招聘

1. [kubernetes面试相关总结(上)](https://mp.weixin.qq.com/s/33cKjVFf7pERyRHQtDwXoQ)

2. [百度健康急招Gopher](https://mp.weixin.qq.com/s/5zyEHVz258IgnIpjOfFADQ)

八、polarisxu

1. [Go1.16 中的新函数 signal.NotifyContext 怎么用？](https://mp.weixin.qq.com/s/mnR_wADjyHtyjdkSwcnkSw)

九、CloudNativeCommunity

1. [蚂蚁开源 OceanBase，开源分布式数据库又迎新玩家](https://mp.weixin.qq.com/s/iDBpa3w2iP8XUr9fb-QWoA)

十、码农桃花源

1. [曹大带我学 Go（4）—— 初识 ast 的威力](https://mp.weixin.qq.com/s/K_iyVFOqg0_2wWmkvXgD8Q)

##  GOCN每日新闻--2021-06-01

1.Go 高性能系列教程之三：编译器优化 https://gocn.vip/topics/12144

2.理解 Golang 中函数调用的原理 https://blog.51cto.com/u_15127695/2829851

3.Go 微服务全链路跟踪详解 https://mp.weixin.qq.com/s/C6OtNYtskdPpfw-HsP76vQ

4.自适应微服务治理背后的算法 https://mp.weixin.qq.com/s/OpF4JVWHA9W1v0yefeo56w

5.消息队列解耦是骗小孩儿的 https://mp.weixin.qq.com/s/O0KGm3nVUSWMSKwHlPiJpg

## gopherDaily--2021-06-01
1.go channel惯用法 - https://blog.kevinhu.me/2021/05/31/31-go-channel-examples/

2.经典旧文：k8s pod的request和limit的正确设置方法 - https://learnk8s.io/setting-cpu-memory-limits-requests

3.用Go实现一个并发文件下载工具 - https://returnfn.com/lets-build-a-concurrent-file-downloader-in-go

4.Go并发API模式 - https://tech.deliveryhero.com/concurrent-api-patterns-in-go/

5.使用Go生成你自己的O’RLY动物书封面 - https://github.com/nanmu42/orly

6.使用Go实现一个简单但强大的反向代理 - https://blog.joshsoftware.com/2021/05/25/simple-and-powerful-reverseproxy-in-go/

7.使用falco分析k3s集群的审计日志 - https://github.com/developer-guy/falco-analyze-audit-log-from-k3s-cluster

8.docker live视频：利用Cue和Buildkit重新思考应用交付问题 - https://docker.events.cube365.net/dockercon-live/2021/content/Videos/TamRA3F2zT8fycvq5

9.阿里的Oceanbase开源 - https://github.com/oceanbase/oceanbase

10.开源社区需要更多的安全空间和行为准则 - https://thenewstack.io/open-source-communities-need-more-safe-spaces-and-codes-of-conducts-now/


## 码农桃花源--2021-06-01
### 文章分享
1. [高性能的goroutine池](https://www.yuque.com/u2278269/gq5x74/puzrkf)

2. [流？I/O操作？阻塞？epoll?](https://www.kancloud.cn/aceld/golang/1958320)

3. [曹大带你看ast](https://mp.weixin.qq.com/s/K_iyVFOqg0_2wWmkvXgD8Q)

4. [最常用的调试 golang 的 bug以及性能问题的实践方法](https://www.kancloud.cn/aceld/golang/1958304)

### 面试题
1. 解决阻塞死等待的办法


2. 如何分析golang程序的内存使用情况？

3. 如何分析Golang程序的CPU性能情况

### 每日算法
「
最长回文子串」：https://leetcode-cn.com/problems/longest-palindromic-substring/



## go中文网每日资讯--2021-05-31


一、Go语言中文网

1. [竟然还在争论是否学Go？本文彻底终结该话题](https://mp.weixin.qq.com/s/2jYX2iMp0z7v09-AxdLDMg)

2. [GM到GMP，Golang经历了什么？](https://mp.weixin.qq.com/s/RR3ducI2gK7JuLAzeILRzg)

3. [全面了解虚拟内存：更好学习Go](https://mp.weixin.qq.com/s/g5I7un3-lpffAk6UFes8DA)

二、亚军进化史

1. [Go技术日报(2021-05-30)——Go小知识：%v %+v %#v的区别](https://mp.weixin.qq.com/s/WJBMz1W_5qW0H_4J9eL6lA)

三、脑子进煎鱼了

1. [搞 Go 要了解的 2 个 Header，你知道吗？](https://mp.weixin.qq.com/s/rGqM1wMlqQEoJSgyrgZNLg)

2. [我这样升级 Go 版本，你呢？](https://mp.weixin.qq.com/s/bGS5D0UYVp6BxSLjuZy0pg)

四、章老师说

1. [软件工程能力漫谈](https://mp.weixin.qq.com/s/hJS5LJRZkMZmHm6g2R_jpw)

五、k8s技术圈

1. [Harbor 结合 Traefik 的 HA 安装配置](https://mp.weixin.qq.com/s/LGI7ZWSK8YGzPVddJxcAUA)

六、新亮笔记

1. [如何设计 API 接口，实现统一格式返回？](https://mp.weixin.qq.com/s/6c6uapjIzJC9wmjUFyZuZA)

七、Go招聘

1. [【阿里巴巴】云原生布道师的机会，这要求。。。](https://mp.weixin.qq.com/s/3cQLB7hEp5snlFmc1ueAfA)

2. [Go 应用优化指北](https://mp.weixin.qq.com/s/KFT1hw02Zih1TMMlDWztCQ)

八、Golang梦工厂

1. [Go语言如何实现可重入锁？](https://mp.weixin.qq.com/s/wBp4k7pJLNeSzyLVhGHLEA)

九、奇伢云存储

1. [自制文件系统 — 02 FUSE 框架，开发者的福音](https://mp.weixin.qq.com/s/HvbMxNiVudjNPRgYC8nXyg)

十、腾讯数据库技术

1. [深入浅出查询优化器](https://mp.weixin.qq.com/s/G_KSkRREXm9fws37gFKoBg)

十一、Golang技术分享

1. [小菜刀面试归来](https://mp.weixin.qq.com/s/xWGHV1_7qvDPhyWJiVr-4g)




## GOCN每日新闻--2021-05-31

1.GM 到 GMP，Golang 经历了什么？ https://mp.weixin.qq.com/s/RR3ducI2gK7JuLAzeILRzg#at

2.Go 语言如何实现可重入锁？ https://mp.weixin.qq.com/s/wBp4k7pJLNeSzyLVhGHLEA

3.如何使用 Golang 进行测试驱动开发 https://medium.com/@jilsonfreddy/how-to-do-test-driven-development-using-golang-unit-testing-945256aa45cf

4.Go 性能工具备忘录 https://steveazz.xyz/blog/go-performance-tools-cheat-sheet

5.字节跳动的 JSON 处理库 https://github.com/bytedance/sonic


## gopherDaily--2021-05-31
1.etcd工作原理 - https://blog.px.dev/etcd-6-tips/

2.在Go中，你可能并不希望为了性能而使用这种并发性 - https://medium.com/nerd-for-tech/you-probably-dont-want-that-concurrency-in-go-109421e8d23

3.字节开源的高性能json编解码库 - https://github.com/bytedance/sonic

4.argo rollouts项目发布1.0版本 - https://www.cncf.io/blog/2021/05/27/argo-rollouts-1-0-released/

5.Yor：一个开源工具，有助于在Terraform、CloudFormation和Serverless等基础设施即代码框架中添加内容丰富且一致的标签 - https://bridgecrew.io/blog/announcing-yor-open-source-iac-tag-trace-cloud-resources/

6.Terraform 0.4的云开发包(CDK)发布 - https://www.hashicorp.com/blog/announcing-cdk-for-terraform-0-4

7.最糟糕的所谓Docker “最佳实践” - https://pythonspeed.com/articles/security-updates-in-docker

8.为kubernetes CRD编写controller - https://vivilearns2code.github.io/k8s/2021/03/11/writing-controllers-for-kubernetes-custom-resources.html

9.比较postgresal的kubernetes operators - https://blog.flant.com/comparing-kubernetes-operators-for-postgresql/

10.容忍容器镜像仓库的故障 - https://blog.kintone.io/entry/neco-registry

11.微软研究院的新工具帮助开发人员更快地编写无缺陷的代码 - https://blogs.microsoft.com/ai-for-business/Microsoft-Research-tools-help-developers-write-bug-free-code-faster/

12.作为一名高级工程师，我学到的东西 - https://old.reddit.com/r/ExperiencedDevs/comments/nmodyl/drunk_post_things_ive_learned_as_a_sr_engineer/

## 码农桃花源--2021-05-31
### 文章分享
1. [context 使用场景到源码解读](https://xie.infoq.cn/article/3e18dd6d335d1a6ab552a88e8)

2. [go并发进阶路线](https://www.yuque.com/u2278269/gq5x74/ggpvz6)

3. [go channel](https://www.yuque.com/wuguoguoya/iq0d3v/uvvvnw)

### 面试题
1. 创建数组时，是分配到栈上还是堆上？创建时默认大小?

2. goroutine在什么时候会发生上下文切换

3. channel 原理

4. 小对象GC频繁，引起的服务吞吐问题，QPS毛刺现象，go 线上性能优化，如何分析|如何优化

### 每日算法
合并两个排序数组




## go中文网每日资讯--2021-05-30
一、Go语言中文网

1. [发现了众多 Go 好书](https://mp.weixin.qq.com/s/x6h8xpbn9kuV2wlk-wtULA)

2. [Go语言爱好者周刊：第 97 期](https://mp.weixin.qq.com/s/6kXbi8OyubJv6opOomb4zg)

3. [Go小知识：%v %+v %#v的区别](https://mp.weixin.qq.com/s/g4qgn1b_LvpvMqRZD-k8LA)

二、亚军进化史

1. [Go技术日报(2021-05-29)——读懂 pprof 生成的报告](https://mp.weixin.qq.com/s/OmUrwjFiQ99DJFaFgRfi4Q)

三、k8s技术圈

1. [优化 Kubernetes 横向扩缩容 HPA](https://mp.weixin.qq.com/s/x_yID1QFt8vV7ioy_o5LlA)

四、后端技术指南针

1. [Go语言内存逃逸之谜](https://mp.weixin.qq.com/s/zm5rp4DkgrWIduZAMhzNzA)

五、奇伢云存储

1. [图解 数据安全的3 种 IO 姿势](https://mp.weixin.qq.com/s/a-SQgKzVYVmJ-qWUXy7c8A)

六、网管叨bi叨

1. [在容器里设置GOMAXPROCS的正确姿势](https://mp.weixin.qq.com/s/kbZsJncgVZv30_TwVrLyLQ)

七、一手代码一首诗

1. [深挖Map的读写性能](https://mp.weixin.qq.com/s/quNpj1MQQwWCKeEENGinUg)

八、TechPaper

1. [消息队列解耦是骗小孩儿的](https://mp.weixin.qq.com/s/O0KGm3nVUSWMSKwHlPiJpg)

九、Go招聘

1. [五月最后1股—MySQL 是怎么实现 ACID 的](https://mp.weixin.qq.com/s/YUSbm0T6si-EqK2-wNLh8g)

十、polarisxu

1. [Go1.17这个新特性竟然是6年前提出来的](https://mp.weixin.qq.com/s/8Ju2-daS0s-esDAezP-lZw)

## GOCN每日新闻--2021-05-30

1.Go 高性能系列教程之二：性能评估和分析 https://gocn.vip/topics/12133

2.深度理解 golang map https://juejin.cn/post/6967274139065253902

3.sync.Pool 原理解析 https://juejin.cn/post/6965421491588431909

4.Kratos 学习笔记 - 通过 layout 简单分析应用是如何跑起来的 https://juejin.cn/post/6967941646138736653

5.来瞧一瞧 gRPC 的拦截器 https://segmentfault.com/a/1190000040087672



## gopherDaily--2021-05-30
- 1.Go性能剖析工具速查表 - https://steveazz.xyz/blog/go-performance-tools-cheat-sheet/
 - 2.sealer：阿里开源的分布式应用打包交付运行的解决方案，可以把分布式应用及其数据库中间件等依赖一起打包发布 - https://github.com/alibaba/sealer
 - 3.基于Go控制器的组件框架和热重载插件系统 - https://github.com/aperturerobotics/controllerbus
 - 4.自动化的服务健康仪表板 - https://github.com/TwinProduction/gatus
 - 5.CNCF的制品库hub - https://github.com/artifacthub/hub
 - 6.Linux之父：我们不会用Rust取代C语言开发内核 - https://mp.weixin.qq.com/s/mVo3S_F0RoxCToawrTCnlA
 - 7.基于KubeEdge实现中国移动10086客服云边协同平台 - https://mp.weixin.qq.com/s/pn0UEL2LFUN63__RVgHBLw
 - 8.面向Kubernetes的红帽高级集群安全简介 - https://www.openshift.com/blog/a-brief-introduction-to-red-hat-advanced-cluster-security-for-kubernetes
 - 9.阿里基于PostgreSQL开源的PolarDB - https://github.com/alibaba/PolarDB-for-PostgreSQL
 - 10.奈飞性能架构师Brendan Gregg搬去澳大利亚 - http://www.brendangregg.com/blog/2021-05-29/moving-to-australia.html


## go中文网每日资讯--2021-05-29


一、Go语言中文网

1. [国外竟然有这么多公司使用 Go](https://mp.weixin.qq.com/s/fKXIBfxvk1wgZMujuz9hWA)

2. [Go 中如何让消息队列达到最大吞吐量？](https://mp.weixin.qq.com/s/K9qZVNP4AKsHNcrDyZq_eA)

3. [Go 每日一库之 gotalk](https://mp.weixin.qq.com/s/VnpQilljVokGssECVyFjWw)

二、亚军进化史

1. [Go技术日报(2021-05-28)——validator库你知多少？](https://mp.weixin.qq.com/s/raQG5PZkxtOu9Qg2P_KO0w)

三、k8s技术圈

1. [Istio 完败？Linkerd 和 Istio 基准测试](https://mp.weixin.qq.com/s/7A7eXQONpiNdCrfwt1HfhQ)

四、分布式实验室

1. [9 种开源的服务网格比较](https://mp.weixin.qq.com/s/3XwKE1pLgMkiH7xuQix25w)

五、aoho求索

1. [如何在 Go-kit 和 Service Mesh 中进行服务注册与发现？](https://mp.weixin.qq.com/s/TZoq5CRQ_QIYTG4W_cU4dg)

六、Go招聘

1. [这可能是最容易理解的 Go Mutex 源码剖析](https://mp.weixin.qq.com/s/XUOQqQ-CRPJ9oxpharxPuQ)


## GOCN每日新闻--2021-05-29
1.dubbo-go v3 版本 go module 踩坑记 https://gocn.vip/topics/12136

2.Go 高性能系列教程：读懂 pprof 生成的报告 https://gocn.vip/topics/12134

3.K8s 工作负载图表工具 https://github.com/Trois-Six/k8s-diagrams

4.灵活的 Go http client 库-Sling https://mp.weixin.qq.com/s/liCnGt0-me4cv-1WAJSSBQ

5.go web client 单元测试实践 chttps://dev.to/chen/practical-unit-testing-web-client-in-go-1o2m


## gopherDaily--2021-05-28
1.为什么Go引入泛型后不会改变Go惯用法？- http://www.jerf.org/iri/post/2955

2.GoLand 2021.2开发计划 - https://blog.jetbrains.com/go/2021/05/28/goland-2021-2-early-access-program-is-open/

3.使用cobra和go实现shell命令补全 - https://jmtirado.net/shell-completion-with-cobra-and-go/

4.dubbo-go v3版本go module踩坑记 - https://mp.weixin.qq.com/s/NFwL7YAtzkSsqZi8AYA6tw

5.如何像专家那样写benchmark测试 - https://hackernoon.com/how-to-write-benchmarks-in-golang-like-an-expert-0w1834gs

6.Go hosts文件操作包 - https://github.com/areYouLazy/libhosty

7.Go实现的磁盘分析工具 - https://github.com/dundee/gdu

8.如何在EKS上安装Cilium - https://miles-seth.medium.com/eks-unchained-with-ebpf-and-bottlerocket-1639b011a36a

9.https://ongres.com/blog/63-node-eks-cluster-running-on-a-single-instance-with-firecracker/

10.Kubernetes集群压力测试工具 - https://github.com/cloud-bulldozer/kube-burner

11.不可变数据库immudb发布v1.0版本 - https://www.codenotary.com/blog/immudb-release-1-0/

## go中文网每日资讯--2021-05-28

一、Go语言中文网

1. [Go：近期两个开源免费好资源](https://mp.weixin.qq.com/s/wXrIztN5MXsNvBKg2LR3hA)

2. [再次探讨 Go 的无限缓冲的channel](https://mp.weixin.qq.com/s/wZNLOywbQWdju_-7TN_48Q)

3. [读者问答：Go 编程怎么也有内存问题？](https://mp.weixin.qq.com/s/51xEfULa1cWaltkTkg1cUA)

二、亚军进化史

1. [Go技术日报(2021-05-27)——Go可用性(七) 总结](https://mp.weixin.qq.com/s/rWD5H4JHVLcka0Xl7z1jOw)

三、Go招聘

1. [validator库你知多少？govalidator了解一下](https://mp.weixin.qq.com/s/FnvvREHWeN1UdRliFjxQ9A)

2. [睡前故事|用Bitmap与AST做一个配置化时长系统](https://mp.weixin.qq.com/s/th5HgpibwZkRlj1EzxmMTw)

四、Go夜读

1. [理论结合实践详解 B+ 树存储引擎（PPT）（多图）](https://mp.weixin.qq.com/s/aSNdEkNdeCAC7O6b3coo-A)

五、奇伢云存储

1. [图解 | epoll怎么实现的](https://mp.weixin.qq.com/s/XW561JURm5zxsXHnD1lV6A)

六、薯条的自我修养

1. [硬核！如何在容器中做时间漫游者](https://mp.weixin.qq.com/s/dTVwpi60_URx1P9c1OPEug)

七、k8s技术圈

1. [Pod Terminating 状态排查](https://mp.weixin.qq.com/s/IattDivoyFSWCq26IV457g)

八、杨旭技术专栏

1. [Go 简单分布式系统 3.1 业务服务（1）](https://mp.weixin.qq.com/s/GzoMpMIUWtM2qNFp5xNiWQ)


## GOCN每日新闻--2021-05-28
1.NSQ 如何实现文件队列 https://reposkeeper.net/2020/11/nsq-disk-queue-implement.html

2.Go sync.Pool 浅析 https://blog.csdn.net/haohongfan/article/details/116978613

3.Golang 指针和 C++ 指针的简单剖析 https://juejin.cn/post/6967315069310861319

4.在 Go 中使用位掩码 https://www.ardanlabs.com/blog/2021/04/using-bitmasks-in-go.html

5.Go 中的垃圾收集 https://www.ardanlabs.com/blog/2019/07/garbage-collection-in-go-part3-gcpacing.html


## gopherDaily--2021-05-27
1.鹅厂的Go编码安全指南 - https://github.com/Tencent/secguide/blob/main/Go%E5%AE%89%E5%85%A8%E6%8C%87%E5%8D%97.md

2.OpenTelemetry Go应用入门 - https://speakerdeck.com/riferrei/opentelemetry-for-dummies-instrumenting-go-apps

3.使用Go进行benchmark测试 - https://stonecode.ca/benchmarking-with-go/

4.使用Go语言进行位操作 - https://www.ardanlabs.com/blog/2021/04/using-bitmasks-in-go.html

5.基于eBPF的网络开源项目Cilium发布1.10 - https://cilium.io/blog/2021/05/20/cilium-110

6.Linkerd和Istio的性能对比(2021版) - https://linkerd.io/2021/05/27/linkerd-vs-istio-benchmarks/

7.使用Fio来判断你的存储是否足够快，以满足Etcd的需要 - https://www.ibm.com/cloud/blog/using-fio-to-tell-whether-your-storage-is-fast-enough-for-etcd

8.Kubernetes API的优先级和公平性 - https://itnext.io/kubernetes-api-priority-and-fairness-b1ef2b8a26a2

9.用于替代TCP的QUIC协议被IETF确定为RFC9000 - https://www.fastly.com/blog/quic-is-now-rfc-9000

10.云的成本，一万亿美元的悖论 - https://a16z.com/2021/05/27/cost-of-cloud-paradox-market-cap-cloud-lifecycle-scale-growth-repatriation-optimization/

## 码农桃花源--2021-05-28
### 文章分享
1. [分布式事务的实现原理](https://draveness.me/distributed-transaction-principle/)

2. [facebook全球用户流量管理系统](https://draveness.me/papers-taiji/)

3. [goroutine调度机制概览](https://zhuanlan.zhihu.com/p/244054940?utm_source=wechat_session&utm_medium=social&utm_oi=1034363224250163200&utm_campaign=shareopn)

### 面试题
1. 说说半连接队列和 SYN Flood 攻击的关系

2. 介绍一下 TCP 报文头部的字段

3. Go Runtime什么时候从堆和从栈分配内存呢

4. 简要介绍go运行时分配内存的策略。
### 每日算法
 lc 1632 矩阵转换后的秩



## go中文网每日资讯--2021-05-27

一、Go语言中文网

1. [如何让 Go 的缓存库 BigCache 更好用？](https://mp.weixin.qq.com/s/Zn1rP18GtmZsbaRnRfJ8ug)

2. [在 Go 语言中，有时 nil 并不是一个 nil](https://mp.weixin.qq.com/s/_REGCKxs0ymIdZXN5a6Tgg)

二、亚军进化史

1. [Go技术日报(2021-05-26)——Go 1.17新特性](https://mp.weixin.qq.com/s/ot_48XSupyyZwfhXaz1vNA)

三、k8s技术圈

1. [AWS 容器服务的安全实践](https://mp.weixin.qq.com/s/GYMXc4HXBGOGgA_7mdenhA)

2. [骚操作，这款工具可以把Kubernetes集群打包成一个镜像](https://mp.weixin.qq.com/s/ssZSMqogjP6CTOKOOR2e5Q)

四、云加社区

1. [总结 Kafka 背后的优秀设计](https://mp.weixin.qq.com/s/dfOP2MeBOqFqg_BdcJCYug)

五、董泽润的技术笔记

1. [硬核！如何在容器中做时间漫游者](https://mp.weixin.qq.com/s/PtYKA-lviJO6A2sXfEaNWA)

六、码农桃花源

1. [曹大带我学 Go（3）—— 如何用汇编打同事的脸](https://mp.weixin.qq.com/s/2Y3qPkysRLaWDcIyLOerZg)

七、Go招聘

1. [华顺信安招Gopher](https://mp.weixin.qq.com/s/xQoEj43nRNkW_g4caLs3XA)

八、mohuishou

1. [Go可用性(七) 总结: 一张图串联可用性知识点](https://mp.weixin.qq.com/s/OXopl6FpwtE6P-k0GEP9qA)


## GOCN每日新闻--2021-05-27

1.Go 基准测试 https://gocn.vip/topics/12126

2.Go 指针 https://sher-chowdhury.medium.com/pointers-in-go-507ec33446b0

3.Go 自定义 http 错误 https://dev.to/clavinjune/my-custom-http-error-in-golang-5ab

4.Go 语言 JSON 使用技巧 https://www.liwenzhou.com/posts/Go/json_tricks_in_go

5.Go 简单快速模板引擎 https://github.com/valyala/fasttemplate


## gopherDaily--2021-05-27
1.Go 1.18加入泛型后的Go函数式编程的未来 - https://ani.dev/2021/05/25/functional-programming-in-go-with-generics/

2.Go团队如何解bug[1]: 乱序执行与内存屏障 - https://mzh.io/how-go-core-team-debug-1-memory-model/

3.提案：将Go移植到中科龙芯指令架构 - https://github.com/golang/go/issues/46229

4.实验性Go重构工具rf - https://pkg.go.dev/rsc.io/rf

5.成为Kubernetes专家的47件事 - https://ymmt2005.hatenablog.com/entry/k8s-things

6.Go自动化测试介绍 - https://dev.to/salesforceeng/intro-to-automated-testing-in-go-4mjl

7.油管视频：Go 还是 Rust，看Go专家与Rust专家的圆桌辩论 - https://www.youtube.com/watch?v=N-E-qtQhsHw

8.欧洲电信巨头优先选择基于Kubernetes的开放云平台 - https://thenewstack.io/european-telecom-giants-prioritize-a-kubernetes-based-open-cloud-platform/

9.5分钟内从零到入门Kubernetes - https://dev.to/ahmednader10/zero-to-kubernetes-in-5-mins-2hbp

10.用这4个最佳实践提高你的CI/CD可观察性 - https://thenewstack.io/improve-your-ci-cd-observability-with-these-4-best-practices/



## go中文网每日资讯--2021-05-26


一、Go语言中文网

1. [为什么Go程序占用那么大的虚拟内存？](https://mp.weixin.qq.com/s/tkAWtSJ4ebAUcQG9AmeXWA)

2. [你不知道的 Go 之 string](https://mp.weixin.qq.com/s/6miIgsZN_Fh79Aixv5BlTg)

二、亚军进化史

1. [Go技术日报(2021-05-25)——Go 编码安全指南](https://mp.weixin.qq.com/s/9cu9R-7E1wqmCVg7O2hC8Q)

三、脑子进煎鱼了

1. [又吵起来了，Go 是传值还是传引用？](https://mp.weixin.qq.com/s/qsxvfiyZfRCtgTymO9LBZQ)

2. [Go 编程怎么也有踩内存？](https://mp.weixin.qq.com/s/tXAP8_U63QLNj1h0ZMvXPw)

四、云原生技术爱好者社区

1. [kubectl debug | 调试Kubernetes的最简方法](https://mp.weixin.qq.com/s/8uN2MySGlgxTed5vwqfFlA)

五、polarisxu

1. [果然，连流程控制都这么另类](https://mp.weixin.qq.com/s/tO8CFBDZ2UsOonqARxOQUA)

六、CloudNativeCommunity

1. [带你走进云原生技术：云原生开放运维体系探索和实践](https://mp.weixin.qq.com/s/zasjqGBDjyeg91jVaa5Xwg)

七、微服务实践

1. [通用连接池帮你解决资源管理难题](https://mp.weixin.qq.com/s/X-xzEzlVrEKYo78eiHwDKw)

八、Go 101

1. [Go 1.17新特性](https://mp.weixin.qq.com/s/T14M_s5qOA6LKvWGgNa0Ow )

九、吴亲强的深夜食堂

1. [无限缓冲的channel(2)](https://mp.weixin.qq.com/s/wDrOBRaPqHx6g-Ir-Yx8kA)

十、Go招聘

1. [跟着Go圈女神一起管理时间](https://mp.weixin.qq.com/s/cbVh_dg0AqJRkeHMCZHGIQ)



## GOCN每日新闻--2021-05-26

1.如何运行并行功能测试 https://medium.com/fiverr-engineering/running-parallel-functional-tests-2f6609bfbf4e

2.Go 中一些不曾注意的点 https://arash-cordi.medium.com/dark-corners-of-go-4e29aafcd4b9

3.如何像专家一样编写 Golang 基准测试 https://hackernoon.com/how-to-write-benchmarks-in-golang-like-an-expert-0w1834gs

4.详解 Go 空结构体的 3 种使用场景 https://mp.weixin.qq.com/s/zbYIdB0HlYwYSQRXFFpqSg

5.Promtheus rules lint 工具 https://github.com/cloudflare/pint



## gopherDaily--2021-05-26

1.Go 1.17新特性 - https://mp.weixin.qq.com/s/T14M_s5qOA6LKvWGgNa0Ow

2.详解Go语言的栈跟踪 - https://github.com/DataDog/go-profiler-notes/blob/main/stack-traces.md

3.关于go结构体字段布局优化 - https://dev.to/deleplace/data-oriented-ant-in-go-3eki

4.使用Go实现《Head First Design Patterns》中的设计模式 - https://faun.pub/head-first-design-patterns-using-go-introduction-d9f05a4c243a

5.使用taildrop在终端间安全的发送文件 - https://tailscale.com/blog/sending-files-with-taildrop/

6.Vanilla Kubernetes对Raspberry Pi来说真的太重了吗？ - https://www.talos-systems.com/blog/is-vanilla-kubernetes-really-too-heavy-for-the-raspberry-pi/

7.使用Go, Gin, MySQL和Docker构建blog项目 - https://nizu.tech/go-blog-1

8.20大Dockerfile最佳实践 - https://sysdig.com/blog/dockerfile-best-practices/

9.在kubernetes上运行consul和vault - https://testdriven.io/blog/running-vault-and-consul-on-kubernetes/

10.使用tekton构建云原生ci/cd - https://itnext.io/cloud-native-ci-cd-with-tekton-building-custom-tasks-663e63c1f4fb

11.观点：是时候停止推荐clean code了 - https://qntm.org/clean

12.关于编程语言的思考 - https://itnext.io/my-thoughts-about-programming-languages-43a8d23ead1f




## 码农桃花源--2021-05-26
## 文章分享
1. [redis和IO多路复用](https://zhuanlan.zhihu.com/p/24252862)

2. [mysql核心知识](https://zhuanlan.zhihu.com/p/363639169)

## 面试题
1、数据库的三范式是什么?

2、DDL、DML、DCL、TCL分表代码什么含义？

3、熟悉MySQL的整体架构吗？

4、说说存储引擎 Inno DB和MyISAM的区别

5、熟悉哪些日志文件？

6、熟悉慢查询吗？

7、MySQL优化手段有哪些？

8、什么是事务？

9、事务的四大特性是什么？

10、说说Mysql的四种隔离级别

11、MySQL默认隔离级别是哪个？

12、知道MySQL中哪些锁？

13、并发读写容易带来什么问题？

14、说说你对MySQL中MVCC的认识

16、是如何解决幻读的？

17、MySQL索引数据结构有哪几种？

18、有哪些类型的索引呢？

19、Hash和BTree作为MySQL索引，说说你对此有什么想法？

20、索引优化有哪些方式？

21、哪些场景建议创建索引？

22、哪些场景不建议使用索引？

23、用过explain吗？怎么用的？

24、熟悉MySQL锁优化吗？

25、熟悉哪些MySQL调优策略？

26、索引是什么？

### 每日算法
算法：「两数相加」：https://leetcode-cn.com/problems/add-two-numbers/

## go中文网每日资讯--2021-05-25

一、Go语言中文网

1. [gRPC 可以不用 pb 而使用 JSON 吗？](https://mp.weixin.qq.com/s/oQ4aG0pIJmQFQd2TKGxsXg)

2. [什么？无限缓冲 channel。。。](https://mp.weixin.qq.com/s/0TJRcbaWlfwEjbKMKAxNAQ)

二、亚军进化史

1. [Go技术日报(2021-05-24)——你知道 Goroutine 是怎么来的吗？](https://mp.weixin.qq.com/s/3pX86YbojfsO9VR8wefiUQ)

三、MoeLove

1. [K8S 生态周报| Cilium v1.10.0 有史以来性能最优](https://mp.weixin.qq.com/s/qJ7HQ2BVS6DEO6sPTJzeAA)

2. [最强 CNI 基准测试：Cilium 网络性能分析](https://mp.weixin.qq.com/s/NR7gDpp2i5gCRRwZjxaASA)

四、Go招聘

1. [Go：发现两个好资源](https://mp.weixin.qq.com/s/fdt1rlpx43YmjW-SGCF1qA)

五、k8s技术圈

1. [使用kubebuilder开发简单的Operator](https://mp.weixin.qq.com/s/uhOIPfTs4o5MDKbdhh_kEQ)

六、polarisxu

1. [我这样升级 Go 版本，你呢？](https://mp.weixin.qq.com/s/jEhX5JHAo9L6iD3N54x6aA)

七、CloudNativeCommunity

1. [B 站直播 | Istio 开源四周年回顾与展望](https://mp.weixin.qq.com/s/tYIP1_s1jHXu6j4mjLuJIw)

八、Go夜读

1. [【北京】Opera 招聘 Go 工程师](https://mp.weixin.qq.com/s/nP8P-0hcAYrr6zvKOIo3gw)

九、图解源码

1. [PAAS平台开发的自我救赎](https://mp.weixin.qq.com/s/0vuneQ-rweCZ-kKLvhe_6g)

十、GoUpUp

1. [Go 每日一库之 fasttemplate](https://mp.weixin.qq.com/s/uNE94IBUmTp2PJ4boFz8OQ)

十一、分布式实验室

1. [60道重要的Kubernetes面试题](https://mp.weixin.qq.com/s/G1kNSmXLaAzAOQ-ja2pKVQ)


## GOCN每日新闻--2021-05-25
 1.Go 编码安全指南 https://github.com/Tencent/secguide/blob/main/Go%E5%AE%89%E5%85%A8%E6%8C%87%E5%8D%97.md
 
 2.私钥安全分发工具 cocert https://github.com/Dentrax/cocert
 
 3.两年 Go 经验学到的东西 https://sayedalesawy.hashnode.dev/top-5-lessons-i-learned-while-working-with-go-for-two-years
 
 4.Go 如何进行栈追踪 https://github.com/DataDog/go-profiler-notes/blob/main/stack-traces.md
 
 5.Linux 中的 macOS 子系统 lima https://github.com/AkihiroSuda/lima


## gopherDaily--2021-05-25
1.使用Go的两年后我学到的五大教训 - https://sayedalesawy.hashnode.dev/top-5-lessons-i-learned-while-working-with-go-for-two-years

2.Manning出版社《Go语言实战》英文版 5.31日前限免下载 - https://freecontent.manning.com/free-ebook-go-in-action/

3.Ransomware：Kasten K8s存储平台如何克服终极数据复制挑战 - https://thenewstack.io/ransomware-how-the-kasten-k8s-storage-platform-overcomes-the-ultimate-data-replication-challenge/

4.新提案：bytes、strings包增加Cut函数 - https://github.com/golang/go/issues/46336

5.将eBPF用于高级Linux基础设施监控 - https://www.linuxjournal.com/content/ebpf-advanced-linux-infrastructure-monitoring

6.使用podman从docker compose转换到kubernetes - https://www.redhat.com/sysadmin/compose-kubernetes-podman

7.像函数一样调用的go模板 - https://github.com/rsc/tmplfunc

10.FIFO、LRU、CLOCK和LFU四种缓存替换策略的Go实现 - https://brunocalza.me/the-cache-is-full/

11.使用Thanos监控多k8s集群 - https://particule.io/en/blog/thanos-monitoring/

12.在kubernetes上运行apache flink - https://medium.com/empathyco/running-apache-flink-on-kubernetes-10815a26559e

13.kubecost：使用kubectl监控kubernetes消耗 - https://thenewstack.io/kubecost-monitor-kubernetes-costs-with-kubectl/

## 码农桃花源--2021-05-25
### 文章分享
1. [go应用性能优化](https://xargin.com/go-perf-optimization/)

2. [Kubernetes 集群灾备环境部署](https://mp.weixin.qq.com/s/3rOKOT7bg17K3SKNUFIiIQ)

3. [mvcc多版本并发控制](https://blog.csdn.net/filling_l/article/details/112854716)

### 面试题
1. undo log版本链是什么东西？通过undo log多版本链条实现的ReadView机制

2. Read Committed隔离级别是如何基于ReadView机制实现的

3. ReadView是如何实现RR隔离级别的




### 每日算法
「环形链表 II」：https://leetcode-cn.com/problems/linked-list-cycle-ii/

## go中文网每日资讯--2021-05-24


一、Go语言中文网

1. [Go 中为什么应该使用接口](https://mp.weixin.qq.com/s/KqXI9ekYAZYd5oYmhqFH8Q)

2. [图解Go sync.Pool](https://mp.weixin.qq.com/s/aiOjUcN89nxwEUJzVNkl3A)

二、亚军进化史

1. [Go技术日报(2021-05-23)——深入 Go 中各个高性能 JSON 解析库](https://mp.weixin.qq.com/s/f6vIa8cUMutZ2nxAM6XqPA)

三、奇伢云存储

1. [自制文件系统 — 01 文件系统的样子](https://mp.weixin.qq.com/s/0FpQGDzFh_D7IJi6z7oXjg)

四、Go招聘

1. [贝壳找房找Gopher咯，快到壳里来。](https://mp.weixin.qq.com/s/JyHCNufE7jYPd20nTH4jlw)

五、luozhiyun很酷

1. [深入 Go 中各个高性能 JSON 解析库](https://mp.weixin.qq.com/s/FBT5QN_Pja6vRntWY0wFeA)

六、Go夜读

1. [【预告】理论结合实践详解 b+ 树存储引擎（innodb、boltdb、buntdb）](https://mp.weixin.qq.com/s/lAD6GmqjElmgXduSDA6kAg)

七、微服务实践

1. [懂得取舍才是缓存设计的真谛](https://mp.weixin.qq.com/s/CWV_rssaz3fTvi7AqEo92w)

八、脑子进煎鱼了

1. [详解 Go 空结构体的 3 种使用场景](https://mp.weixin.qq.com/s/zbYIdB0HlYwYSQRXFFpqSg)

九、薯条的自我修养

1. [配置化系统中的图模型](https://mp.weixin.qq.com/s/ZDW9mg_iYI6a8dkpo31Sdw)

十、码农桃花源

1. [曹大带我学 Go（2）—— 迷惑的 goroutine 执行顺序](https://mp.weixin.qq.com/s/WWfm7Ui7g_gGlb8XkIZigg)

十一、mohuishou

1. [Go可用性(六) 熔断](https://mp.weixin.qq.com/s/b5Wi1TqFVCCmpjvfmUcQBQ)
 

## GOCN每日新闻--2021-05-24
1.懂得取舍才是缓存设计的真谛 https://my.oschina.net/kevwan/blog/5056791

2.immudb v1.0 released https://www.codenotary.com/blog/immudb-release-1-0/

3.你知道 Goroutine 是怎么来的吗？ https://mp.weixin.qq.com/s/DZavvanPnRwZMPU-5_wOeg

4.分布式链路跟踪中的 traceid 和 spanid 代表什么？ https://mp.weixin.qq.com/s/eKbFYwnH4vwgWm6_5sWs3w

5.Dart Flutter 数据库 ObjectBox 1.0 版本 https://objectbox.io/dart-flutter-database-1_0-release/

## gopherDaily--2021-05-24
- 1.区块链可扩展性的局限 by 以太坊之父 - https://vitalik.ca/general/2021/05/23/scaling.html
 - 2.学习golang.org/x/sync下的包 - https://ketansingh.me/posts/golang-x-sync/
 - 3.什么是可观察性 by Brendan Gregg - http://www.brendangregg.com/blog/2021-05-23/what-is-observability.html
 - 4.Uber API网关的架构 - https://eng.uber.com/architecture-api-gateway/
 - 5.Uber API网关的演化史- https://eng.uber.com/gatewayuberapi/
 - 6.在Go 1.16中如何嵌入静态资源文件 - https://www.josephspurrier.com/how-to-embed-assets-in-go-1-16
 - 7.Zadig：一个云原生、分布式、面向开发者的持续交付产品 - https://github.com/koderover/zadig
 - 8.给Kubernetes服务提供人类可懂的注解 - https://kubernetes.io/blog/2021/04/20/annotating-k8s-for-humans/
 - 9.Kubernetes应用程序的预检工具，并支持捆绑其他框架 - https://github.com/replicatedhq/troubleshoot
 - 10.使用kubernetes自定义资源(CRD)来管理我们的短暂环境 - https://medium.com/beamdental/using-kubernetes-custom-resources-to-manage-our-ephemeral-environments-f298610893e1
 - 11.使用Kubeadm在Ubuntu virtualbox上安装kubernetes集群 - https://kosyfrances.com/kubernetes-cluster/

## 码农桃花源--2021-05-24
### 文章分享
1. [MySQL索引失效的底层原理](https://www.yuque.com/u2278269/gq5x74/sotkoz)

2. [goroutine 执行顺序](https://mp.weixin.qq.com/s/WWfm7Ui7g_gGlb8XkIZigg)

3. [调度本质](https://mp.weixin.qq.com/s/5E5V56wazp5gs9lrLvtopA)

### 面试题
1. 如何分析sql慢查询

2. 数据库到达瓶颈时，如何选择分库分表(水平分库，水平分表，垂直分库，垂直分表)

3. Mvcc和Redolog和Undolog以及Binlog有什么不同

### 每日算法
「两两交换链表中的节点」：https://leetcode-cn.com/problems/swap-nodes-in-pairs/


## go中文网每日资讯--2021-05-23
一、Go语言中文网

1. [2021 年 5 月程序员工资排行：Go的工资满意吗？](https://mp.weixin.qq.com/s/cX25jSXo_wI22x2CKWW2Cg)

2. [Go语言爱好者周刊：第 96 期 — 用 Go 实现一个计算器](https://mp.weixin.qq.com/s/yKRK4cfcdJcdwh2u0tyi7w)

3. [源码级剖析new和make怎么用！](https://mp.weixin.qq.com/s/ClbdoJXPWlq0hP9ABzVJvQ)

二、亚军进化史

1. [Go技术日报(2021-05-22)——假如 Go 能说话，听听 GMP 的心声](https://mp.weixin.qq.com/s/OxUMTSGvX29M5HQ_VbrQxg)

三、k8s技术圈

1. [在 EKS 中实现基于 Promtail + Loki + Grafana 容器日志解决方案](https://mp.weixin.qq.com/s/Qotk0CNgsBrFy0Ot7AL0jQ)

四、架构之家

1. [代码重构的原则和技巧](https://mp.weixin.qq.com/s/HlbURQBw35RUJOu5XEX9KA)

五、幼麟实验室

1. [深度探索Go语言（四）：包装方法](https://mp.weixin.qq.com/s/9KCIaWfka-z5GDEHfAnKzg)

2. [深度探索Go语言（五）：包装方法](https://mp.weixin.qq.com/s/yZpnWXfnrSPfAa6qXM4CUw)

六、polarisxu

1. [一本开源免费的 Go 进阶图书](https://mp.weixin.qq.com/s/C2y8WqjVnLXHRMYJa-hqvA)

七、网管叨bi叨

1. [分布式链路跟踪中的traceid和spanid代表什么？](https://mp.weixin.qq.com/s/eKbFYwnH4vwgWm6_5sWs3w)

八、分布式实验室

1. [使用gRPC改造Kubernetes通信](https://mp.weixin.qq.com/s/MUW_CcsXYH1RXQGfLcb6yw)

九、Go招聘

1. [什么技巧，能优化 Go 服务 40% 以上的 CPU？](https://mp.weixin.qq.com/s/1BUAy84aXOxWwHy0ZYOD1Q)

2. [五月第三股来袭，文末有彩蛋哦！](https://mp.weixin.qq.com/s/a-iNzl9kggG-oY28ShAhxw)



## GOCN每日新闻--2021-05-23
1. API 网关架构 https://eng.uber.com/architecture-api-gateway/ 

2. 使用 Go 语言对网页进行截屏 https://www.youtube.com/watch?v=4hrFtF6OuiM
 
3. Go 并发同步包 https://ketansingh.me/posts/golang-x-sync/  

4. 深入 Go 中各个高性能 JSON 解析库 https://www.luozhiyun.com/archives/535 

5. lima: 一款 Go 语言实现的 Linux 虚拟机 https://github.com/AkihiroSuda/lima


## gopherDaily--2021-05-23
- 1.初探Go代码混淆 - https://paper.seebug.org/1586/
- 2.有争议的Go错误处理 - https://dev.to/hlmerscher/the-controversial-go-way-of-handling-errors-2ka1
- 3.高性能、自我托管的通讯和邮件列表管理器 listmonk发布1.0 - https://github.com/knadh/listmonk
- 4.Go错误处理：从拒绝到接受 - https://evilmartians.com/chronicles/errors-in-go-from-denial-to-acceptance
- 5.一个简单而完整的功能开关解决方案 - https://github.com/thomaspoignant/go-feature-flag
- 6.Go实现的短链接应用 - https://github.com/go-awesome/shortlink
- 7.我们如何在CockroachDB中建立可扩展的空间数据和空间索引 - https://www.cockroachlabs.com/blog/how-we-built-spatial-indexing/
- 8.CI/CD pipeline的pipeline模式 - https://harness.io/blog/devops/deployment-pipeline-patterns/
- 9.对Postgres 14的早期看法：性能和监控的改进 - https://pganalyze.com/blog/postgres-14-performance-monitoring
- 10.如何建立你作为开发者的个人品牌 - https://www.freecodecamp.org/news/build-your-personal-brand-as-a-developer/
- 11.Rust进入Linux内核开发？- https://lwn.net/Articles/853423/
- 12.知识图谱入门  - http://ai.stanford.edu/blog/introduction-to-knowledge-graphs/

## go中文网每日资讯--2021-05-22


一、Go语言中文网

1. [用Go实现一个直播系统难吗？看看这个开源项目](https://mp.weixin.qq.com/s/5YPp7WFgVfPlGxim7tmQ5A)

二、

1. [Go语言数据争用与race原理](https://mp.weixin.qq.com/s/gGGg6wqQX5b1kEOeRbTQlA)

三、Go语言中文网

1. [Go 标准库之 unsafe 包详解](https://mp.weixin.qq.com/s/Pj4Q_8sj2pCmXe2cHNqdvw)

四、亚军进化史

1. [Go技术日报(2021-05-21)——细谈Go变量的内存分布](https://mp.weixin.qq.com/s/linOKTZYmM9MqPEPQ8h7cw)

五、新亮笔记

1. [Go - 开箱即用，WEB 界面一键安装，没有项目经验，可以拿这个练手](https://mp.weixin.qq.com/s/6RlAb7iWc3Tj6g7ttiBoRQ)

六、k8s技术圈

1. [Loki 源码分析之日志写入](https://mp.weixin.qq.com/s/9BKZvNANqGJwziygytJ1ag)

七、吴亲强的深夜食堂

1. [无限缓冲的channel(1)](https://mp.weixin.qq.com/s/ETfrSqQczbW2SnaFjoUx0A)

八、分布式实验室

1. [基于 Kubernetes 的微服务项目设计与实现](https://mp.weixin.qq.com/s/BjDx-pDQsuj6p_X01Vw92g)

九、奇伢云存储

1. [假如 Go 能说话，听听 GMP 的心声](https://mp.weixin.qq.com/s/Tgf-JU9YDume4jRHex65NA)
 
## GOCN每日新闻--2021-05-22
1.利用 eBPF 支撑大规模 Kubernetes Service https://mp.weixin.qq.com/s/BJHzU4LxLdLnNzOnAqIptg

2.Golang 中的适配器设计模式 https://www.smartscribs.com/adapter-design-pattern-in-golang/

3.【深度】阿里巴巴万级规模 K8s 集群全局高可用体系之美 https://gocn.vip/topics/12079

4.假如 Go 能说话，听听 GMP 的心声 https://mp.weixin.qq.com/s/Tgf-JU9YDume4jRHex65NA

5.小函数的调用开销需要考虑吗? https://mp.weixin.qq.com/s/nW0Cye1G_A72fm7MuBAM1A



## go中文网每日资讯--2021-05-21
一、Go语言中文网

1. [94期Go周刊题解：做错了的一定看看 ](https://mp.weixin.qq.com/s/hFmwCc7fNzRLRZs9RCZ9cg)

2. [你真的知道 Goroutine 是怎么来的吗？ ](https://mp.weixin.qq.com/s/edW9q7pKwRrYbI8uKxSMiQ)

二、亚军进化史

1. [Go技术日报(2021-05-20)——初探 Golang 代码混淆 ](https://mp.weixin.qq.com/s/FaruKe5WwSKbo7crA4dFQg)

三、k8s技术圈

1. [kubernetes 实用技巧: 使用 ksniff 抓包 ](https://mp.weixin.qq.com/s/Z4zxadtE0gLSZ_aq00ov2Q)

四、polarisxu

1. [出 Rust 书了！！！ ](https://mp.weixin.qq.com/s/a0pwSZwPziD-JHnTi5KGiQ)

五、互联网技术窝

1. [细谈Go变量的内存分布](https://mp.weixin.qq.com/s/tL0-lg8KXJhROzC-N8Xhcg
) 
六、Go招聘

1. [成都Gopher可真香，上班还能开黑打王者]( https://mp.weixin.qq.com/s/C06NmbVU0Mj5fYrmXMbIGw)




## GOCN每日新闻--2021-05-21

1.[golang 中的 AES 加密解密](https://youtu.be/Q2jsrhDS-JA)

2.[Go 中实现的加密货币机器人](https://github.com/rodrigo-brito/ninjabot) 

3.[Go 中同名的方法](https://youtu.be/UUVZb8ctSoU)

4.[Go 实现的 JSON 类型检查工具]( https://github.com/Kangaroux/go-map-schema)

5.[使用 Wails 在 Go 中构建桌面应用](https://youtu.be/Dg9rUXxNV-c)


## gopherDaily--2021-05-21
- 1.通过实例理解Go逃逸分析 - https://t.zsxq.com/qZrfYzn

- 2.浅谈如何组织Go代码结构[译] - https://mp.weixin.qq.com/s/9_WQUpvHKli4btPqCA89Aw

- 3.用NATS服务器v2.2.0+替换你的MQTT代理服务器 - https://nats.io/blog/replace-your-mqtt-broker-with-nats/

- 4.为什么你要在2021年学习Go？ - https://invozone.com/blog/why-you-shoud-learn-golang-in-2021/

- 5.油管视频：Prometheus是怎么存储数据的 - https://www.youtube.com/watch?v=qB40kqhTyYM

- 6.gitpod使用caddy替换nginx - https://github.com/gitpod-io/gitpod/pull/3964

- 7.一个go-ethereum的替代品 - https://github.com/binance-chain/bsc

- 8.openshift中的镜像垃圾回收 - https://www.openshift.com/blog/image-garbage-collection-in-openshift

- 9.改善你的Kubernetes授权：不要使用system:masters - https://blog.aquasec.com/kubernetes-authorization

- 10.极端的HTTP性能优化：在4个vCPU的EC2实例上实现每秒120万API请求 - https://talawah.io/blog/extreme-http-performance-tuning-one-point-two-million/

- 11.基于Fyne Go UI框架的计算器 -  https://github.com/fyne-io/calculator

- 12.使用signal.NotifyContext实现Go应用的优雅退出 - https://millhouse.dev/posts/graceful-shutdowns-in-golang-with-signal-notify-context





## go中文网每日资讯--2021-05-20

一、Go语言中文网

1. [优化 Golang 服务来减少 40% 以上的 CPU](https://mp.weixin.qq.com/s/dgVv6p8HQtc-krPGEdU2cQ)

2. [fuckdb 新功能上线，开箱即用、更加强大的代码生成器](https://mp.weixin.qq.com/s/ysOlv8xsc7wF7cPcV5pu7g)

二、亚军进化史

1. [Go技术日报(2021-05-19)——pprof++: 一个带有硬件监控的 Go Profiler](https://mp.weixin.qq.com/s/3xtuxe6fi_9hWsdoLGJGew)

三、脑子进煎鱼了

1. [Go 面试官问我如何实现面向对象？](https://mp.weixin.qq.com/s/2x4Sajv7HkAjWFPe4oD96g)

2. [一文搞懂缓存系统稳定性](https://mp.weixin.qq.com/s/eNLB1BKZi4L3aNxbL0TqWQ)

四、k8s技术圈

1. [kubernetes 平台开发者的几个小技巧](https://mp.weixin.qq.com/s/RVYJd_3xzDps-1xFwtl01g)

五、polarisxu

1. [周刊题解：常量表达式这个规则应该了解下](https://mp.weixin.qq.com/s/8fG0OMvwKziMSRs8bZFj2Q)

六、腾讯技术工程

1. [企业微信万亿级日志检索系统](https://mp.weixin.qq.com/s/opxvlddsSQctb3nwcxaW_g)

七、码农桃花源

1. [曹大带我学 Go（1）——调度的本质](https://mp.weixin.qq.com/s/5E5V56wazp5gs9lrLvtopA)



## GOCN每日新闻--2021-05-20
1.初探 Go 代码混淆 https://mp.weixin.qq.com/s/q9xUFQ7HdHAis70WrFHuOQ

2.优化 Golang 服务减少 40% 以上的 CPU https://mp.weixin.qq.com/s/dgVv6p8HQtc-krPGEdU2cQ

3.Go 实现 bridge 设计模式 https://www.smartscribs.com/bridge-design-pattern-in-golang/

4.Go 模板引擎 templ https://adrianhesketh.com/2021/05/18/introducing-templ/

5.使用 Viper 和 Consul 配置 Go 应用 https://bencane.com/2021/05/18/using-viper-with-consul-to-configure-go-apps/



## gopherDaily--2021-05-20
1.实现无限缓存的channel - https://colobu.com/2021/05/11/unbounded-channel-in-go/

2.pprof++: 一个带有硬件监控的 Go Profiler[译] - https://mp.weixin.qq.com/s/-BSzD_wIEjHnHbs0xnsHXA

3.istio 1.10发布，让StatefulSet使用起来更容易 - https://istio.io/latest/blog/2021/statefulsets-made-easier/

4.templ：一个可用于go web的新模板引擎 - https://adrianhesketh.com/2021/05/18/introducing-templ/

5.Go实现bridge设计模式 - https://www.smartscribs.com/bridge-design-pattern-in-golang/

6.Kubernetes The Hard Way(aws版) - https://github.com/prabhatsharma/kubernetes-the-hard-way-aws

7.用于在k8s上创建和管理postgresql数据库的k8s operator - https://github.com/reactive-tech/kubegres

8.服务网格战争：和istio说byebye - https://medium.com/polymatic-systems/service-mesh-wars-goodbye-istio-b047d9e533c7#--responses

9.你的技术项目需要Go时的5个场景 - https://hackernoon.com/lets-go-5-use-cases-when-you-need-golang-for-your-tech-project-wp1931r0

10.python开发者的Go语言指南 - https://www.coderedcorp.com/blog/golang-for-python-devs/

## go中文网每日资讯--2021-05-19


一、Go语言中文网

1. [小函数的调用开销需要考虑吗？Go 内联了解下](https://mp.weixin.qq.com/s/nW0Cye1G_A72fm7MuBAM1A)

2. [LeetCode 啥题都有：Go 刷「打家劫舍」](https://mp.weixin.qq.com/s/IOC4uUXkT0QcgmguKPwehQ)

二、亚军进化史

1. [Go技术日报(2021-05-18)——你不知道的 Go 之 string](https://mp.weixin.qq.com/s/6QlUlYwg06xBc572I0XznQ)

三、董泽润的技术笔记

1. [什么是好的一致性 hash 实现](https://mp.weixin.qq.com/s/5p--sMUfy4Kw7piw8heicA)

四、polarisxu

1. [盘点那些使用 Go 语言的国外公司](https://mp.weixin.qq.com/s/_3ef_wwuZG2BC9AHBjYGew)

五、k8s技术圈

1. [记一次 Kubernetes 节点内核问题排查](https://mp.weixin.qq.com/s/mDHXC98NU4_zBMUtuK6_HA)

六、奇伢云存储

1. [在Linux上，使用time优雅的统计程序运行时间](https://mp.weixin.qq.com/s/ugI6gXdRzgyFJOVvAKP41g)

2. [深入理解mmap 0拷贝技术](https://mp.weixin.qq.com/s/ZmZdolLuZyiZOpiAzDqRlw)

七、ServiceMesher

1. [Istio 1.10 发布及官网改版](https://mp.weixin.qq.com/s/Lq6zF90FR-ohT9ON-88Z_Q)

八、Go招聘

1. [辣妹子、辣火锅、辣个工作，咱Gopher都值得拥有](https://mp.weixin.qq.com/s/wzb6YDt1BBw62X0MfTPOCg)

## GOCN每日新闻--2021-05-19

1.进程内缓存助你提高并发能力 https://gocn.vip/topics/12091

2.Chaos Mesh® 在腾讯——腾讯互娱混沌工程实践 https://gocn.vip/topics/12092

3.pprof++: 一个带有硬件监控的 Go Profiler https://mp.weixin.qq.com/s/-BSzD_wIEjHnHbs0xnsHXA

4.graphjin: 基于数据库快速生成 GraphQL 服务器 https://github.com/dosco/graphjin

5.Gmocker: 使用 JSON 文件生成 mock 服务器 https://github.com/Ananto30/mocker




## gopherDaily--2021-05-19
- 1.使用Viper和Consul来配置Go应用程序 - https://bencane.com/2021/05/18/using-viper-with-consul-to-configure-go-apps/
- 2.利用Go进行游戏开发和运营 - https://technology.riotgames.com/news/leveraging-golang-game-development-and-operations
- 3.油管视频：在Go中为Ethereum构建系统 - https://www.youtube.com/watch?v=oXgcPKhQy6w
- 4.以太坊将于未来几个月完成向Proof-of-Stake的过渡，能耗将至少减少99.95% - https://blog.ethereum.org/2021/05/18/country-power-no-more/
- 5.argocd的消息通知引擎 - https://github.com/argoproj-labs/argocd-notifications
- 6.kubewarden: kubernetes policy引擎 - https://www.kubewarden.io/
- 7.云原生远景：可观察性和分析 - https://thenewstack.io/the-cloud-native-landscape-observability-and-analysis/
- 8.Envoy宣布支持Windows平台 - https://blog.envoyproxy.io/general-availability-of-envoy-on-windows-267e4544994a
- 9.KOps增加了对Calico的eBPF数据平面的支持 - https://thenewstack.io/kops-adds-support-for-calicos-ebpf-dataplane/
- 10.云部署模式：解释和比较5种主要模式 - https://launchdarkly.com/blog/cloud-deployment-models-explaining-and-comparing-the/
- 11.构建和可视化你的第一个机器人：使用Duckiebot和Foxglove Studio开始学习机器人技术 - https://foxglove.dev/blog/building-and-visualizing-your-first-robot
- 12.1Password支持linux - https://blog.1password.com/welcoming-linux-to-the-1password-family/
- 13.为什么特性管理是软件交付的未来 - https://thenewstack.io/why-feature-management-is-the-future-of-software-delivery/



## go中文网每日资讯--2021-05-18


一、Go语言中文网

1. [写了50万行Go代码是一种什么样的体验？](https://mp.weixin.qq.com/s/pzoTAl8xA9sefI_Ckpv8PA)

2. [国外似乎更喜欢几分钟学会系列：10分钟能学会 Go 吗？](https://mp.weixin.qq.com/s/ot7l6p_h5OEtpz-gDgwsyA)

3. [用Kubernetes搭建Etcd集群和WebUI](https://mp.weixin.qq.com/s/NaU4N22vlQ2aIvxtwsYPfQ)

二、亚军进化史

1. [Go技术日报(2021-05-17)——如何打造高性能的 Go 缓存库](https://mp.weixin.qq.com/s/FBRNkhODBia1TJBr4dwP3g)

三、GoUpUp

1. [你不知道的 Go 之 string](https://mp.weixin.qq.com/s/_R_2xJxSN8GRbgS-n3xApg)

四、polarisxu

1. [推荐一位高产的 Go 开源库作者](https://mp.weixin.qq.com/s/NlbUsovyqlIfnY9xQE-crA)

五、k8s技术圈

1. [Loki 查询语言 LogQL 使用](https://mp.weixin.qq.com/s/0dXT0fIreZk6_4ZL4S8lHg)

六、Go招聘

1. [Go缓冲系列之-free-cache](https://mp.weixin.qq.com/s/SwGTdFe9AgHPGqkDbZoUjQ)

2. [券商公司招Gopher，不会炒股你觉得还有戏嘛？](https://mp.weixin.qq.com/s/MdBxyU7bfeuQzrUZS7YZzw)

七、mohuishou

1. [10. 总结](https://mp.weixin.qq.com/s/BJHTn2j2QiR5SgKErTiLzw)

八、HHFCodeRv

1. [Go sync.Pool 浅析](https://mp.weixin.qq.com/s/MTf_4WEvCnCMKeQC_Wm_xw)

九、脑子进煎鱼了

1. [一口气搞懂 Go sync.map 所有知识点](https://mp.weixin.qq.com/s/8aufz1IzElaYR43ccuwMyA)


## GOCN每日新闻--2021-05-18

1.强大的模糊测试工具 go-fuzz https://gocn.vip/topics/12075

2.单机内存内缓存怎么做？go-cache 了解下 https://mp.weixin.qq.com/s/LzfLySMPtbCO91q87UKRcQ

3.深度探索 Go 语言（三）：动态派发 https://mp.weixin.qq.com/s/XLj_AKqETZy4cUBNiNZPBw

4.golang 日期与时间完全指南 https://qvault.io/golang/golang-date-time/

5.GopherChina 全部议程和讲师出炉了  https://mp.weixin.qq.com/s/G_M4yw6VCTfF03b2L21ZGQ



## gopherDaily--2021-05-18
1.Go time和date操作完全指南 - https://qvault.io/golang/golang-date-time/

2.Go原生对fuzzing test的支持在其开发分支已具备Beta测试条件 - https://go.googlesource.com/proposal/+/master/design/draft-fuzzing.md

3.审校Learning Go - https://bitfieldconsulting.com/golang/jon-bodner-learning-go

4.使用构建标志(build flag)以实现后向兼容 - https://play-with-go.dev/build-flags-backwards-compatibility_go115_en/

5.用Repository模式实现数据库事务 - https://medium.com/wesionary-team/implement-database-transactions-with-repository-pattern-golang-gin-and-gorm-application-907517fd0743

6.Go Crash Course：类型、转换和推理 - https://dev.to/moficodes/go-crash-course-part-4-types-conversion-and-inference-1np6

7.kube-spawn：一个使用kubeadm和systemd-nspawn在Linux机器上创建多节点Kubernetes集群的工具 - https://github.com/kinvolk/kube-spawn

8.Multus CNI能够将多个网络接口连接到Kubernetes中的pod - https://github.com/k8snetworkplumbingwg/multus-cni

9.Linus Torvalds 谈为什么开源能解决最大的问题 - https://thenewstack.io/linus-torvalds-on-why-open-source-solves-the-biggest-problems/

10.监控应用性能的安全边缘的技巧 - https://thenewstack.io/tips-for-monitoring-the-secure-edge-for-app-performance/

## 码农桃花源--2021-05-18
### 文章分享
1. [事务隔离](https://www.yuque.com/u2278269/gq5x74/hmf9lc)

2. [一次http请求经历了什么](https://maimai.cn/article/detail?fid=1605252795&efid=PETqhzTx3SaEyNnNtrEk9g&share_channel=2&use_rn=1)

3. [go sync map](https://mp.weixin.qq.com/s/8aufz1IzElaYR43ccuwMyA)

### 面试题
1. 为什么读操作性能这么高，写操作性能低的可怕

2. 一次 HTTP 请求到底经历了什么？

3. 如何避免长事务的出现?
### 每日算法
三数之和


## go中文网每日资讯--2021-05-17


一、Go语言中文网

1. [也许是你从来没用过的利器：GODEBUG](https://mp.weixin.qq.com/s/lqOs34aMs7AYCxM_Jv0Hug)

2. [从0开发上线一个web项目（下）](https://mp.weixin.qq.com/s/W5lHCgA_SzzyCoDaHDmz1Q)

二、亚军进化史

1. [Go技术日报(2021-05-16)——高性能 Go 代码工坊（Part7)](https://mp.weixin.qq.com/s/RdrLC5r8mOCnWRjVqPi3-A)

三、luozhiyun很酷

1. [如何打造高性能的 Go 缓存库](https://mp.weixin.qq.com/s/G8LJ1HBuWoQfWV2dILi6Rg)

四、Go夜读

1. [【本周四预告】JetBrains GoLand 2021.1 新特性介绍](https://mp.weixin.qq.com/s/9DbBwdkBvECl11jSd-hbYw)

五、奇伢云存储

1. [用 Go struct 不能犯的一个低级错误！](https://mp.weixin.qq.com/s/EKbsUwLABjpadxPZ9AJGTg)

六、Golang梦工厂

1. [Go语言中new和make你使用哪个来分配内存？](https://mp.weixin.qq.com/s/XJ9O9O4KS3LbZL0jYnJHPg)

七、k8s技术圈

1. [同步secret和config到指定namespace](https://mp.weixin.qq.com/s/i1fI58MhbWnPx7RFftLXkg)

八、微服务实践

1. [缓存数据一致性 - 架构师峰会演讲实录](https://mp.weixin.qq.com/s/DhIv9RACxa5igJTYg4N1mA)

九、mohuishou

1. [9. kubebuilder 进阶: 源码分析](https://mp.weixin.qq.com/s/mlpNUwoqcNdT0kAowb_zrQ)

十、Go招聘

1. [咱Gopher好香啊，输入法、搜索Top行业招Gopher，还不快到碗里来？](https://mp.weixin.qq.com/s/HY4CpoPqXroMhJJ250quZQ)

## GOCN每日新闻--2021-05-17
1.如何管理多版本的 go   https://lakefs.io/managing-multiple-go-versions-with-go/

2.一个 SQL 数据库只使用了 2000 行 golang 代码并且没有任何第三方依赖 https://github.com/auxten/go-sqldb

3.使用 go 开发一个监控剪贴板的服务  https://www.reddit.com/r/golang/comments/ncsnj2/monitoring_clipboard_as_service_with_go/

4. Gorm 复杂关系举例：  https://github.com/harranali/gorm-relationships-examples

5.写了 500，000 行 go 代码之后  https://blog.khanacademy.org/half-a-million-lines-of-go

6.* GopherChina 全部日程出炉 https://gc.gocn.vip



## gopherDaily--2021-05-17
1.Go http应用的错误处理 - https://www.joeshaw.org/error-handling-in-go-http-applications/

2.使用 Open Telemetry为Go服务自动埋点 - https://varunksaini.com/auto-instrument-open-telemetry-go/

3.关于（过早）优化的思考 - https://www.tnotes.dev/posts/thoughts-on-premature-optimization

4.使用2000行go代码实现的sql关系数据库 - https://github.com/auxten/go-sqldb/blob/main/README-zh.md

5.使用Go管理多个Go版本 - https://lakefs.io/managing-multiple-go-versions-with-go/

6.Go算法基础 - https://yourbasic.org/algorithms/

7.2021年最适合初学者学习的4种编程语言 - https://qvault.io/news/top-coding-languages-for-beginners/

8.哪些公司使用了Go（按领域) - https://www.softkraft.co/companies-using-golang/

9.面向云原生企业的统一事件驱动架构 - https://thenewstack.io/unified-event-driven-architecture-for-the-cloud-native-enterprise/

10.Harbor仓库中锁定镜像避免误删的简便方法 - https://mp.weixin.qq.com/s/sj6Nj9etH-Z4B7GPjHOZng

11.从几百个生产环境总结出的Redis性能问题排查解决手册 - https://mp.weixin.qq.com/s/WcY-h_vxXVca94Xnw0Wrgg

## 码农桃花源--2021-05-17
### 文章分享
1. [MySQL一条语句的执行](https://www.yuque.com/u2278269/gq5x74/ubr2zr)

2. [kafka知识导图](https://processon.com/view/5fff01bb6376897ae0b610ff#map)

3. [go luki 日志报警](https://mp.weixin.qq.com/s/wO0w1f8ptZf4Rv1KQ6I1sw)

### 面试题
```sql
select * from T where ID=10;
```
1. 简述这句话在MySQL的执行过程

2. Mvcc和Redolog和Undolog以及Binlog有什么不同

3. InnoDB的行锁模式

### 每日算法
盛最多水的容器

## go中文网每日资讯--2021-05-16
一、Go语言中文网

1. [单机内存内缓存怎么做？go-cache 了解下](https://mp.weixin.qq.com/s/LzfLySMPtbCO91q87UKRcQ)

2. [Go语言爱好者周刊：第 95 期 — 自信点，这道题一定会](https://mp.weixin.qq.com/s/yBUlIhhGNSDUv7_J8Y0NmA)

3. [从0写一个 Go Web 服务 (上)](https://mp.weixin.qq.com/s/vNUBJERfgmeV_qk_cdFoVQ)

二、亚军进化史

1. [Go技术日报(2021-05-15)——服务注册中心和配置中心的选择](https://mp.weixin.qq.com/s/iRvT2ye1P_7JNnT6qQkE0Q)

三、GoOfficialBlog

1. [高性能 Go 代码工坊（Part7)](https://mp.weixin.qq.com/s/ptUH-9dvRlA558SNakIbFQ)

四、k8s技术圈

1. [使用 Loki 进行日志报警(二)](https://mp.weixin.qq.com/s/wO0w1f8ptZf4Rv1KQ6I1sw)

五、网管叨bi叨

1. [用Kubernetes搭建Etcd集群和WebUI](https://mp.weixin.qq.com/s/AkIvkW22dvqcdFXkiTpv8Q)

六、吴亲强的深夜食堂

1. [Leetcode:House Robber II](https://mp.weixin.qq.com/s/-mUMeklJdajaSxlpqJB0MA)

七、幼麟实验室

1. [深度探索Go语言（三）：动态派发](https://mp.weixin.qq.com/s/XLj_AKqETZy4cUBNiNZPBw)

八、polarisxu

1. [通过例子，让你彻底搞懂微服务的演化过程](https://mp.weixin.qq.com/s/wWBlrjUUn-tx0v7ZTkha1g)

九、Go招聘

1. [5月你好，第二股来喽](https://mp.weixin.qq.com/s/onnAaqM8GoaphEtZ-KHO6g)
## GOCN每日新闻--2021-05-16 
1.http.Client 的连接行为控制详解 https://mp.weixin.qq.com/s/2fAj_8vEQYLxddllqjsYFg

2.unsafe.Pointer 和 uintptr 的区别和联系 https://mp.weixin.qq.com/s/l-ZQws4SH4QsvMhmJddiww

3.Common anti-patterns in Go https://mp.weixin.qq.com/s/k-Use24-UCB3y_hV0tihVg

4.详解 http.Handle 与 http.HandleFunc 区别 https://ckarchive.com/b/75u7h8h730p5

5.i/o timeout ， 希望你不要踩到这个 net/http 包的坑 https://mp.weixin.qq.com/s/AKhRFKgs-I46Lnqhbk6Iog

## gopherDaily--2021-05-16 
- 1.当GOPATH与go module相遇时的混乱情况 - https://arxiv.org/pdf/2102.12105.pdf
- 2.使用NATS作为http.RoundTripper的实现 - https://github.com/ripienaar/nats-roundtripper
- 3.油管视频：用net包建立一个DIY代理 - https://www.youtube.com/watch?v=J4J-A9tcjcA
- 4.使用Telepresence 2进行Kubernetes调试和本地开发 - https://codefresh.io/kubernetes-tutorial/telepresence-2-local-development/
- 5.Kubernetes the Hard Way (azure版) - https://github.com/carlosonunez/kubernetes-the-hard-way-on-azure
- 6.像top那样的容器度量数据采集工具 - https://github.com/bcicen/ctop
- 7.UTF-8历史 by Rob Pike - http://doc.cat-v.org/bell_labs/utf-8_history
- 8.10分钟内学会go - https://www.codingholygrail.com/learn-go-in-10-mins
- 9.为Go项目逐步构建优化的Docker镜像 - https://www.codingholygrail.com/build-docker-image-for-golang-projects
- 10.软件测试的角色 - https://blog.thundra.io/4-software-testing-roles
- 11.在Rust中做不了的事情（以及该怎么做）- https://blog.logrocket.com/what-you-cant-do-in-rust-and-what-to-do-instead/

 
## go中文网每日资讯--2021-05-15 


一、Go语言中文网

1. [面试官：说说unsafe.Pointer和uintptr的区别和联系](https://mp.weixin.qq.com/s/l-ZQws4SH4QsvMhmJddiww)

2. [http.Client的连接行为控制详解](https://mp.weixin.qq.com/s/2fAj_8vEQYLxddllqjsYFg)

3. [你不知道的 Go 之 slice](https://mp.weixin.qq.com/s/-VRyRg9d-65lNTFRPvoCLw)

二、亚军进化史

1. [go每日新闻(2021-05-14)——Go语言内存分配](https://mp.weixin.qq.com/s/wembkRjdv8IErolT4IpnCg)

三、云原生技术爱好者社区

1. [说说常见数据库及中间件的主从设计](https://mp.weixin.qq.com/s/EXTdTsOcCuWpaNXOATpGFQ)

四、Gopher指北

1. [i/o timeout ， 希望你不要踩到这个net/http包的坑](https://mp.weixin.qq.com/s/AKhRFKgs-I46Lnqhbk6Iog)

五、一手代码一首诗

1. [Common anti-patterns in Go](https://mp.weixin.qq.com/s/k-Use24-UCB3y_hV0tihVg)

六、大魏分享

1. [服务注册中心和配置中心的选择](https://mp.weixin.qq.com/s/4gOoYI9GsfauCcDoq_6Wxw)
## GOCN每日新闻--2021-05-15 

1.golang 并发底层实现竟然都是它！！！ https://mp.weixin.qq.com/s/7BeLEzqmA1IR-rjVig0Qbw

2.golang 编写的 GBA 模拟器 https://github.com/pokemium/magia

3.漫谈 Go 语言编译器（01）https://mp.weixin.qq.com/s/0q0k8gGX56SBKJvfMquQkQ

4.semaphore 的原理与实现 https://mp.weixin.qq.com/s/GB649snXQ5rDF2BXO9V55Q

5.pprof++：具有硬件性能监控的 Go 探查器 https://eng.uber.com/pprof-go-profiler


## gopherDaily--2021-05-15 
- 1.对cni benchmark中Cilium网络性能的理解 - https://cilium.io/blog/2021/05/11/cni-benchmark
- 2.编程与写作 by redis之父 - http://antirez.com/news/135
- 3.fly.io的Prometheus度量采集实践 - https://fly.io/blog/measuring-fly/
- 4.go实现的GBA游戏模拟器 - https://github.com/pokemium/magia
- 5.使用go构建rest server：身份验证 - https://eli.thegreenplace.net/2021/rest-servers-in-go-part-6-authentication
- 6.使用go和无服务框架构建OKR跟踪工具 - https://arjitjaiswal.medium.com/building-okayar-part-1-how-it-started-back-end-crud-serverless-lambda-api-in-go-3248ae93c97c
- 7.了解如何使用Rancher的kim和K3s更快地构建函数 - https://www.openfaas.com/blog/kim/
- 8.减少Kubernetes的AWS账单的8个最佳做法 - https://cast.ai/blog/8-best-practices-to-reduce-your-aws-bill-for-kubernetes
- 9.Go实现的bloom filter包 - https://github.com/bits-and-blooms/bloom
- 10.iptables: kubernetes service是如何将流量打到pod中的 - https://dustinspecker.com/posts/iptables-how-kubernetes-services-direct-traffic-to-pods/
- 11.经过8年努力，scala 3终于发布了！- https://scala-lang.org/blog/2021/05/14/scala3-is-here.html
- 12.在大规模数据中心运行BGP协议 by facebook - https://engineering.fb.com/2021/05/13/data-center-engineering/bgp/



## go中文网每日资讯--2021-05-14 


一、Go语言中文网

1. [Uber 使用 Go 的规模这么大？！都自己定制的 Go 编译器了](https://mp.weixin.qq.com/s/oJ6BD8AXbKKe_OBj9kCx6A)

2. [Go：如何优雅地实现并发编排任务](https://mp.weixin.qq.com/s/5RhaUEk33kf4LkcZphyt_g)

3. [grpc Go Client 源码分析](https://mp.weixin.qq.com/s/SQ22u7l17mWl2nQlSqvGXg)

二、亚军进化史

1. [Go技术日报(2021-05-13)——深度解密Go之信号抢占式调度](https://mp.weixin.qq.com/s/iWgFdyyvAt6kZPkU4x2TfQ)

三、k8s技术圈

1. [使用 Loki 进行日志报警(一)](https://mp.weixin.qq.com/s/s4g_lg9k1QjGa-GLRfZtEg)

四、Go夜读

1. [Go 程序运行时数据统计的可视化工具 statsviz](https://mp.weixin.qq.com/s/gaQhIo544VHYeGcKq34GIw)

五、polarisxu

1. [Rust 劝退系列 06：常量](https://mp.weixin.qq.com/s/y5WJbP8qcvdm4WASXEEibQ)

六、码农桃花源

1. [semaphore 的原理与实现](https://mp.weixin.qq.com/s/GB649snXQ5rDF2BXO9V55Q)

七、mohuishou

1. [8. kubebuilder 进阶: webhook](https://mp.weixin.qq.com/s/CFggTa7E91Rf1N1EZZpOBA)

八、技术岁月

1. [【直播】5.15（周六）9:00 聊聊风控系统构建演进过程~欢迎扫码报名](https://mp.weixin.qq.com/s/KctKKf0VUCt0AppLyEEtrg)

九、脑子进煎鱼了

1. [为什么 Go map 和 slice 是非线性安全的？](https://mp.weixin.qq.com/s/TzHvDdtfp0FZ9y1ndqeCRw)

2. [深度剖析 Go 的 nil](https://mp.weixin.qq.com/s/wwpDqXZ8VsDL0N2IKjJNDA)
 
## GOCN每日新闻--2021-05-14 
1.熔断原理与实现 Golang 版 https://blog.51cto.com/u_15175878/2774901

2.Golang 语言中怎么拦截系统信号和优雅退出 http server？ https://mp.weixin.qq.com/s/yvK42TntdzAI9S6kBFFZ-w

3.关于如何组织 Go 项目结构的思考 https://changelog.com/posts/on-go-application-structure

4.kubernetes 问题排查: 系统时间被修改导致 sandbox 冲突 https://mp.weixin.qq.com/s/DJMrRBP237BE69pTyrKmnQ

5.可汗学院 Go 语言实践 https://blog.khanacademy.org/half-a-million-lines-of-go/


## gopherDaily--2021-05-14
1.编写50w行Go代码之后：可汗学院工程师的Go感悟 - https://blog.khanacademy.org/half-a-million-lines-of-go/

2.为什么你应该在你的Go服务器处理程序中使用errgroup.WithContext - https://bionic.fullstory.com/why-you-should-be-using-errgroup-withcontext-in-golang-server-handlers/

3.BuildKit CLI for kubectl是docker build的替代品 - https://container-registry.com/posts/productivity-lift-buildkit-cli-for-kubectl/

4.docker和kubernetes是如何创建ip地址的 - https://dustinspecker.com/posts/how-do-kubernetes-and-docker-create-ip-addresses/

5.Go语言eBPF入门 - https://networkop.co.uk/post/2021-03-ebpf-intro/

6.k8s集群中如何切换容器运行时 - https://dev.to/stack-labs/how-to-switch-container-runtime-in-a-kubernetes-cluster-1628

7.gohugo vs. jekyll，哪个才是你的菜 - https://draft.dev/learn/posts/hugo-vs-jekyll-which-is-right-for-your-blog

8.mk48: go实现的开源游戏项目 - https://github.com/SoftbearStudios/mk48

9.如何构建良好的远程工作文化 - https://liuandrewk.medium.com/how-to-build-a-good-remote-work-culture-5f482cd4f1dd

10.油管视频：git和github教程 - https://www.youtube.com/watch?v=RGOj5yH7evk

## 码农桃花源--2021-05-14
### 文章分享
1. [Go语言内存分配](https://mp.weixin.qq.com/s/Hm8egXrdFr5c4-v--VFOtg)

2. [用100行Go代码实现容器](https://medium.com/@ssttehrani/containers-from-scratch-with-golang-5276576f9909)

3. [图解kafka架构原理](https://mp.weixin.qq.com/s/4zH9kfuC6FYh4hYo0CLtTg)

### 面试题
1. 有了 GC，为什么还会发生内存泄露？

2. kafka consumer是否可以消费指定分区消息？

3. Kafka消息是采用Pull模式，还是Push模式？

4. 什么时候用消息队列？怎么决定选 Kafka 还是 RocketMQ ？

### 每日算法
粉刷房子 https://leetcode-cn.com/problems/paint-house-iii/

## go中文网每日资讯--2021-05-13 


一、Go语言中文网

1. [面试官：聊聊 defer 的工作原理。。。](https://mp.weixin.qq.com/s/oWlQU9c9z11CHdOwOMOHxA)

2. [深度解密Go语言之基于信号的抢占式调度](https://mp.weixin.qq.com/s/xdhv24Lh-7smOT5ESw2dBw)

二、亚军进化史

1. [Go技术日报(2021-05-12)——跳出Go module的泥潭](https://mp.weixin.qq.com/s/Wgm33pXqt3i5NWUyZthllQ)

三、董泽润的技术笔记

1. [聊聊如何做技术分享](https://mp.weixin.qq.com/s/iRe1aGShDBeVhLhOSHwbMQ)

四、polarisxu

1. [Uber 使用 Go 的规模这么大？！都自己定制的 Go 编译器了](https://mp.weixin.qq.com/s/MO0WNlwecDVLx4QfWklamA)

五、微服务实践

1. [如何让消息队列达到最大吞吐量？](https://mp.weixin.qq.com/s/Y1qWYdzNs8EXCFu_DtBH9g)

六、Go招聘

1. [薪资比肩北上广，你会考虑回老家吗？急招哦](https://mp.weixin.qq.com/s/koCxSjX8tXMMY3Yn8c4KpA)

七、mohuishou

1. [7. kubebuilder 进阶: 测试](https://mp.weixin.qq.com/s/tcLIx3E0LyRkNhPO0U8zmg)

八、薯条的自我修养

1. [从0.5到1用golang上线一个web项目](https://mp.weixin.qq.com/s/ZqbDY3IjtH2s5_oeDvhQVQ)

2. [从0到0.5用golang写一个web项目](https://mp.weixin.qq.com/s/XXLFwlmOUaD7a3hftYCd2A)
 

> 来源: https://studygolang.com/go/godaily


## GOCN每日新闻--2021-05-13 

1.[译文 Go 的抢占式调度 ](https://gocn.vip/topics/12062)

2.[深度解密 Go 语言之基于信号的抢占式调度 ](https://mp.weixin.qq.com/s/ESfbVoCGUIdpwFOfGyvz1w)

3.[使用 Golang 的交叉编译 ](https://linux.cn/article-13385-1.html)

4.[Go 无分支编码 ](https://mattnakama.com/blog/go-branchless-coding/)

5.[Go 数组比切片好在哪？ ](https://mp.weixin.qq.com/s/zp1vdhGukEYKpzAdPt--Mw)

> 来源：https://gocn.vip/topics/node18

## gopherDaily--2021-05-13
1.[minikube v1.20.0版本的一个bug ](https://t.zsxq.com/RbEufqr)


2.[关于Go项目代码结构的思考 ](https://changelog.com/posts/on-go-application-structure)

3.[使用Semgrep发现goroutine泄露](ttps://www.trailofbits.com/post/discovering-goroutine-leaks-with-semgrep)

4.[Kubernetes的三个租户模型]( https://kubernetes.io/blog/2021/04/15/three-tenancy-models-for-kubernetes/)

5.[经典旧文：对go测试的崇拜 ](https://danmux.com/posts/the_cult_of_go_test/)

6.[Calico的可插拔式数据平面的重要性 ](https://thenewstack.io/the-importance-of-calicos-pluggable-data-plane/)

7.[使用curl探索kubernetes](https://blog.tilt.dev/2021/03/18/kubernetes-is-so-simple.html) 

8.[用eStargz加快在各种工具上pull容器镜像的速度 ](https://medium.com/nttlabs/lazy-pulling-estargz-ef35812d73de)

9.[Kubernetes中AWS NLB超时的一个奇怪的案例 ](https://build.thebeat.co/a-curious-case-of-aws-nlb-timeouts-in-kubernetes-522bd88a3399)

10.[为SQL数据库dolt构建fuzz testing](https://www.dolthub.com/blog/2021-05-12-dolt-and-fuzz-testing/) 

11.[使用Go CDK(Cloud Development Kit )创建Elastic Kubernetes Service ](https://www.steveyackey.com/post/eks-cdk-go/)



## 码农桃花源--2021-05-13
### 文章分享
1. [pause容器源码](https://mp.weixin.qq.com/s/2kkD6Dx40Ilu7HWpCe43hw)

2. [MySQL 学习](https://mp.weixin.qq.com/s/sRFmW57KUY3yyyRkyw0L4A)

3. [etcd 操作 boltdb 的优化实现](https://mp.weixin.qq.com/s/Cv1lagwtSkonQQes_0Sndw)

### 面试题
1. 负载均衡原理是什么

2. LVS原理是什么

3. 哪些排序算法是稳定的
### 每日算法
lc 1307 口算难题


## go中文网每日资讯--2021-05-12

一、Go语言中文网

1. [Go：跨团队协作时如何共享对象](https://mp.weixin.qq.com/s/zJaruocUDSzld8ttDyawng)

2. [template源码分析](https://mp.weixin.qq.com/s/HqcaFEXgQbcRyjYjI6oKGQ)

二、mohuishou

1. [6. kubebuilder 实战: status &amp; event](https://mp.weixin.qq.com/s/JuRlClCX7TnQKaW-Rr3Z7g)

三、亚军进化史

1. [Go技术日报(2021-05-11)——实现无限缓存的channel](https://mp.weixin.qq.com/s/bx_cWcT2MSBic6yV7Zq9bg)

四、吴亲强的深夜食堂

1. [如何优雅地实现并发编排任务](https://mp.weixin.qq.com/s/M88-VS_H7o754mw5Ra7BYg)

五、k8s技术圈

1. [Prometheus 二次开发之 API 接口](https://mp.weixin.qq.com/s/K7ERtE2KKflYSA9KJOukYg)

六、云加社区

1. [从TDSQL，看分布式数据库的技术之美](https://mp.weixin.qq.com/s/CbzlPmGJCQKi3UmvwjFC1Q)

七、polarisxu

1. [Go Team Leader — rsc大神新开源了一个库，增强模板功能](https://mp.weixin.qq.com/s/3DFejimkPY9tg9QQL2QTqw)

八、Go招聘

1. [Wow，联通数科也招Gopher了](https://mp.weixin.qq.com/s/tVY3AuUOYEnMKi7Km4eBCw)

九、脑子进煎鱼了

1. [Go 数组比切片好在哪？](https://mp.weixin.qq.com/s/zp1vdhGukEYKpzAdPt--Mw)

2. [Go 缓存系列之 go-cache](https://mp.weixin.qq.com/s/dKlfwJ69s3fUBWYIV57hyg)

十、奇伢云存储

1. [Go 存储基础 — 内存结构体怎么写入文件？](https://mp.weixin.qq.com/s/mfNz7r76vZOOgiMSmuVeJA)

十一、码农桃花源

1. [深度解密Go语言之基于信号的抢占式调度](https://mp.weixin.qq.com/s/ESfbVoCGUIdpwFOfGyvz1w)
## GOCN每日新闻--2021-05-12 
1.实现无限缓存的 channel https://colobu.com/2021/05/11/unbounded-channel-in-go/

2.Go RIP 协议简单的模拟实现 https://segmentfault.com/a/1190000039984330

3.Golang 框架 gin 运行源码分析 https://mp.weixin.qq.com/s/D6Ls3fUZnmimg8EgBDuXcQ

4.Golang MySQL 查询更轻松 https://mp.weixin.qq.com/s/Sdt_wYJCXepoUwIIy7h9yw

5.golang 如何使用原生 RPC 及微服务简述 https://segmentfault.com/a/1190000039990286

## gopherDaily--2021-05-12 
- 1.Go并发：高级话题 - https://t.zsxq.com/yJMRjiI
- 2.pprof++: 带有硬件性能监控的Go性能剖析器 by uber - https://eng.uber.com/pprof-go-profiler/
- 3.Kubernetes中混沌工程的开源解决方案 - https://blog.flant.com/chaos-engineering-in-kubernetes-open-source-tools/
- 4.用GoPacket对数据包进行捕获和程序化分析 - https://blog.apnic.net/2021/05/12/programmatically-analyse-packet-captures-with-gopacket/
- 5.KrakenD：高性能API网关框架项目加入linux基金会 - https://www.krakend.io/blog/krakend-framework-joins-the-linux-foundation/
- 6.跳出Go module的泥潭 - https://mp.weixin.qq.com/s/EndbbH0Cxw7jBmUOovs6Ew
- 7.在Kubernetes上用多容器pod扩展应用程序 - https://learnk8s.io/sidecar-containers-patterns
- 8.Popeye是一个实时扫描Kubernetes集群并报告部署资源和配置的潜在问题的工具 - https://github.com/derailed/popeye
- 9.分布式账本技术（DLT）和数字凭证–完美的搭配 - https://www.memberpass.com/2021/05/distributed-ledger-technology-dlt-and-digital-credentials-a-perfect-match/
- 10.通过microsoft learn零基础学习Go编程语言 - https://dev.to/azure/get-started-with-the-go-programming-language-with-microsoft-learn-no-experience-needed-1npg
- 11.通过AI和机器学习扩大网络防御 - https://thenewstack.io/expanding-cyber-defense-through-ai-and-ml/

## 码农桃花源--2021-05-12
### 文章分享
1. [云开发如何扛过大流量活动洪峰](https://mp.weixin.qq.com/s/WOhY_bTj213XP6tdUYQCZQ)

2. [MySQL 学习](https://mp.weixin.qq.com/s/sRFmW57KUY3yyyRkyw0L4A)

3. [煎鱼 数组比切片好在哪里](https://mp.weixin.qq.com/s/zp1vdhGukEYKpzAdPt--Mw)

### 面试题
1. Mysql联合索引最左匹配原则

2. Mysql高可用方案有哪些

3. TIME_WAIT的作用
### 每日算法
lc 1307 口算难题

## go中文网每日资讯--2021-05-11 


一、Go语言中文网

1. [unsafe 包真的不安全吗？](https://mp.weixin.qq.com/s/rIqkKNUecvnZ6gadThf4gg)

2. [go-callvis 源码分析](https://mp.weixin.qq.com/s/dUXXGd8hqEhKE_Cj4EY2Lw)

二、亚军进化史

1. [Go技术日报(2021-05-10)——缓存系统稳定性](https://mp.weixin.qq.com/s/Jukr1P_NWksTdOPRGpHRcQ)

三、幼麟实验室

1. [深度探索Go语言（二）：动态派发](https://mp.weixin.qq.com/s/fhpKBRqhRAxFnESQ4vTbWQ)

四、polarisxu

1. [再一次看到了 Go 的节制：int128 类型要不要支持？](https://mp.weixin.qq.com/s/5uW2rcIEhFPCCTPqrhwOow)

五、Go招聘

1. [Go 笔试题精选 三： 19 道填空题](https://mp.weixin.qq.com/s/5Zd1DmQGDvjMySOUf7eFMg)

六、taowen

1. [在提赋能之前，先想想这5个问题](https://mp.weixin.qq.com/s/V8l7S7A-kRF_WDb7tlJJ0Q)

2. [代码无可避免腐化是因为这 5 个原因](https://mp.weixin.qq.com/s/IzDgV6AmK-2ph1ctcz9liA)

七、mohuishou

1. [5. kubebuilder 实战: CRUD](https://mp.weixin.qq.com/s/UDA55y5RCpzyDvfSfs9d2w)

八、鸟窝

1. [实现无限缓存的channel](https://colobu.com/2021/05/11/unbounded-channel-in-go/)
## GOCN每日新闻--2021-05-11 

1.轻轻松松打印网页并生成 pdf 文档  https://colobu.com/2021/05/05/generate-pdf-for-a-web-page-by-using-chromedp/

2.Go 1.16 的 signal.NotifyContext 让你的服务重启更优雅  https://juejin.cn/post/6960578101755510798

3.一种持锁被调度的情况  https://xargin.com/schedule-when-holding-lock-causes-latency-spike/

4.assembly 完全解析：https://segmentfault.com/a/1190000039978109?utm_source=tag-newest

5.strace 的 10 个命令 https://colobu.com/2021/04/30/strace-commands-for-troubleshooting-and-debugging-linux/
## gopherDaily--2021-05-11

- 1.使eBPF工作在windows操作系统上 - https://cloudblogs.microsoft.com/opensource/2021/05/10/making-ebpf-work-on-windows/
- 2.油管视频：调试你的Go test代码：用printf还是delve - https://www.youtube.com/watch?v=nmNVd7FbSYs
- 3.如何在你的本地项目中使用未发布的Go module - https://iaziz786.com/blog/use-unpublished-go-modules
- 4.Prometheus监控告警规则大全 - https://awesome-prometheus-alerts.grep.to/
- 5.dblab: 支持与PostgreSQL和MySQL交互的终端命令行工具 - https://github.com/danvergara/dblab
- 6.终端应用的自动黑暗模式 by vim-go作者 - https://arslan.io/2021/02/15/automatic-dark-mode-for-terminal-applications/
- 7.另一个开源的容器平台 - https://github.com/sylabs/singularity
- 8.在Go中没有一个完美的切片克隆方案 - https://github.com/go101/go101/wiki/There-is-not-a-perfect-slice-clone-way-in-Go
- 9.理解nil接口类型与值为nil的接口变量 - https://trstringer.com/go-nil-interface-and-interface-with-nil-concrete-value/
- 10.微软Teams的命令行终端UI工具 - https://github.com/fossteams/teams-cli
- 11.Kubernetes GUI大全 - http://kokizzu.blogspot.com/2021/03/kubernetes-gui.html
- 12.如何做出你的第一个开源贡献 - https://dev.to/codesandboxio/how-to-make-your-first-open-source-contribution-2oim


## 码农桃花源--2021-05-11
### 文章分享
1. [无服务器下的数据库](https://mp.weixin.qq.com/s/_MfuhpSAtZFnB8p-xp5HUw)

2. [MySQL AUTO_UNCREMENT](https://mp.weixin.qq.com/s/Ya3JrUftN0ASI8dTzb1lvw)

3. [facebook google网络架构揭秘](https://mp.weixin.qq.com/s/MPBk9wdYsE48H7OXWAd5bA)
### 面试题
1. 网络的性能指标有哪些

2. Http1和Http2和Grpc之间的区别是什么

3. Redis事物的了解CheckAndSet操作实现乐观锁

### 每日算法
lc 1307 口算难题


## go中文网每日资讯--2021-05-10


一、Go语言中文网

1. [图解 Go 内存管理分配](https://mp.weixin.qq.com/s/bMr4lZgf-Fn1oaOSPPSDIQ)

2. [Go 刷 leetcode 之任务调度器](https://mp.weixin.qq.com/s/oI441vsKhYninXJjg3t3yA)

二、亚军进化史

1. [Go技术日报(2021-05-09)——Go 实现各类限流](https://mp.weixin.qq.com/s/7tv3hiEVYoKPaMLc6MmM-g)

三、k8s技术圈

1. [自己动手实现一个 kubectl exec](https://mp.weixin.qq.com/s/VmEcIYfsUbgh-p4RCssGFQ)

四、CloudNativeCommunity

1. [云上细粒度访问管理的参考架构](https://mp.weixin.qq.com/s/3sfWGKFa1POMFcWYJbk6Ug)

五、脑子进煎鱼了

1. [Go 工程师必学：Go 大杀器之跟踪剖析 trace](https://mp.weixin.qq.com/s/7DY0hDwidgx0zezP1ml3Ig)

2. [Go并发编程 — sync.Once 单实例模式的思考](https://mp.weixin.qq.com/s/nMHNujmbIx7uMqMtjUMTvQ)

六、mohuishou

1. [4. kustomize 简明教程](https://mp.weixin.qq.com/s/JDsDOYaACgyt97-Nz5ScDw)

七、GoUpUp

1. [你不知道的 Go 之 slice](https://mp.weixin.qq.com/s/aOIp7jeBWubT-u85vQJxzA)

八、微服务实践

1. [缓存系统稳定性 - 架构师峰会演讲实录](https://mp.weixin.qq.com/s/o0qUY5zUjBQuOkx_4XGB6Q)

九、TechPaper

1. [微服务的灾难](https://mp.weixin.qq.com/s/bY2s7wjfggSt77kj8exYLQ)


## GOCN每日新闻--2021-05-10 
1.利用 NATS JetStream 构建分布式事件流系统 https://shijuvar.medium.com/building-distributed-event-streaming-systems-in-go-with-nats-jetstream-3938e6dc7a13

2.100 行 Golang 代码构建一个简单的终端仿真器 https://ishuah.com/2021/03/10/build-a-terminal-emulator-in-100-lines-of-go

3.编写简单的 CLI 程序：Python vs Go https://dev.to/jidicula/writing-a-simple-cli-program-python-vs-go-59kf

4.如何使用 Go，Maroto 和 GoFakeIt 创建 PDF https://dev.to/divrhino/creating-a-pdf-with-go-maroto-gofakeit-3c7m

5.一个用 Go 编写的类似 cowsay 的开源程序 weebsay https://github.com/irevenko/weebsay


## gopherDaily--2021-05-10
1.最受欢迎的编程语言（1965/2021）- https://statisticsanddata.org/data/the-most-popular-programming-languages-1965-2021/

2.用NATS JetStream在Go中构建分布式事件流系统 - https://shijuvar.medium.com/building-distributed-event-streaming-systems-in-go-with-nats-jetstream-3938e6dc7a13

3.外部secret管理系统与k8s的集成 - https://github.com/external-secrets/kubernetes-external-secrets

4.生成随机的、可发音的名字，像docker给容器起的默认名字那样 - https://github.com/lucasepe/codename

5.Pixie为CNCF带来Kubernetes集群内的调试能力 - https://thenewstack.io/pixie-brings-in-cluster-kubernetes-debugging-to-cncf/

6.bofied: 一个网络启动服务器，支持PXE服务协议 - https://github.com/pojntfx/bofied

7.糟糕的磁盘性能 by Brendan Gregg - http://www.brendangregg.com/blog/2021-05-09/poor-disk-performance.html

8.油管视频：使用go重头构建container - https://www.youtube.com/watch?v=8fi7uSYlOdc

9.milvus：开源向量数据库搜索引擎 - https://github.com/milvus-io/milvus

10.使用go加速python代码 - https://medium.com/geekculture/speed-up-python-with-golang-9a1d2c6067ab



## 码农桃花源--2021-05-10
### 文章分享
1. [go语言编译器](https://mp.weixin.qq.com/s/UhxFOQBpW8EUVpFvqH2tMg)

2. [虚拟内存工作原理](https://mp.weixin.qq.com/s/c81Fvws0J2tHjcdTgxvv6g)

3. [redis vs tendis](https://mp.weixin.qq.com/s/MeYkfOIdnU6LYlsGb24KjQ)
### 面试题
1. Mysql高可用方案有哪些

2. Redis的LRU具体实现

3. k8s的服务发现如何做的
### 每日算法
反转字符串 写出最优解

## go中文网每日资讯--2021-05-09 

一、Go语言中文网

1. [Go语言爱好者周刊：第 94 期 — 这道题目别不会](https://mp.weixin.qq.com/s/_La7pqzLreCl50-9ASoBkQ)

2. [goproxy 源码分析](https://mp.weixin.qq.com/s/qVIzxuu8yZv7arfr2E8Cmg)

二、亚军进化史

1. [Go技术日报(2021-05-08)——Go1.16.4 发布](https://mp.weixin.qq.com/s/Qv1WU-2JgMR1XeJZYXURyQ)

三、k8s技术圈

1. [使用 Loki 收集 Traefik 日志](https://mp.weixin.qq.com/s/L-dGf4dwr7b8hz4IM0qg8A)

四、云原生技术爱好者社区

1. [谈谈对K8S CNI、CRI和CSI插件的理解](https://mp.weixin.qq.com/s/vLfWUiZuap9RWjFuPfqMEg)

五、TechPaper

1. [nocode 和 lowcode](https://mp.weixin.qq.com/s/gvCQqNFaGSWCJv9XHMl94A)

六、GoUpUp

1. [Go 每日一库之 bytebufferpool](https://mp.weixin.qq.com/s/SVqpZubE_X4W8uAwmNV79w)

七、Go招聘

1. [面试官：Go 结构体是否可以比较，为什么？](https://mp.weixin.qq.com/s/S2nVZ-xmHqsTOyQp7jWWSg)

2. [五一假期的股文来咯](https://mp.weixin.qq.com/s/oTqguz5KwHVky-3cXt8hLQ)




## GOCN每日新闻--2021-05-09 

1.Go 实现各类限流 https://juejin.cn/post/6959436201443426311

2.如何使用 Github actions 测试 Go 代码 https://gfgfddgleb.medium.com/how-to-test-your-go-code-with-github-actions-f15881d46089

3.Go 机器学习 https://towardsdatascience.com/golang-for-machine-learning-bd4bb84594ee

4.为什么 Go 接口比 Java 和 C# 更好 https://khanakia.medium.com/why-go-interface-is-better-than-java-and-c-ece85aef0123

5.Go JSON 终极指南 https://qvault.io/golang/json-golang/


## gopherDaily--2021-05-09 
- 1.当你去获取时，会发生什么–近距离观察Go模块的内部结构 - https://tobyokewole.medium.com/what-happens-when-you-go-get-a-closer-look-at-the-internals-of-go-modules-347780643292
- 2.go中如何实现枚举 - https://marcofranssen.nl/how-to-do-enums-in-go
- 3.如何在ipfs上建立单页web站点 - https://docs.ipfs.io/how-to/websites-on-ipfs/single-page-website/
- 4.分析开源Helm chart的安全态势的主要趋势 - https://bridgecrew.io/blog/open-source-helm-security-research-part-2/
- 5.通过kubernetes CSI获取HashiCorp Vault Secrets - https://www.hashicorp.com/blog/retrieve-hashicorp-vault-secrets-with-kubernetes-csi
- 6.使用gitlab operator在k8s和openshift上部署gitlab - https://about.gitlab.com/releases/2021/04/22/gitlab-13-11-released/
- 7.kubernetes手册 - https://www.freecodecamp.org/news/the-kubernetes-handbook/
- 8.经典旧文：使用Go实现Clean Architecture  - https://eminetto.medium.com/clean-architecture-using-golang-b63587aa5e3f
- 9.WebAssembly不仅仅是一个JavaScript的替代品  - https://thenewstack.io/kubecon-eu-why-webassembly-is-more-than-a-javascript-replacement/
- 10.运维ETCD的经验教训 - https://docs.google.com/presentation/d/1uOpawkCoqPQuxD5MuEhXeCrJV1Nw9fopUBq2IRTvwcI/edit#slide=id.gc963048e26_0_73
- 11.对Rust的第二印象 - https://deepu.tech/my-second-impression-of-rust/



## go中文网每日资讯--2021-05-08 

一、Go语言中文网

1. [Go1.16.4 发布](https://mp.weixin.qq.com/s/Iw4LeBgD5xxLtUy3mcws-w)

2. [一个 Go 语言实现的高性能 NoSQL 数据库](https://mp.weixin.qq.com/s/fo_hhABF8leihxSp7YSt2Q)

3. [echo 源码分析之校验器：Validator](https://mp.weixin.qq.com/s/LRF6wC83fbHtELiiym-krQ)

二、亚军进化史

1. [Go技术日报(2021-05-07)——进程和线程的19问](https://mp.weixin.qq.com/s/yljnaWZB-uiy17Bj89ql2Q)

三、微服务实践

1. [ArchSummit架构师峰会-海量并发下的缓存架构设计](https://mp.weixin.qq.com/s/9tblPSzLvEagjlYuA-RnUw)

四、CloudNativeCommunity

1. [Kubernetes API Server 源码图解（续）](https://mp.weixin.qq.com/s/mJzV1964mPMjnLc5pA4A2Q)

五、刘丹冰Aceld

1. [Linux深入理解I/O复用并发模型](https://mp.weixin.qq.com/s/kWDKpgmcOQFjoBAK3LyPTg)

六、k8s技术圈

1. [探索使用 Golang 和 Webassembly 构建一个多人游戏服务器](https://mp.weixin.qq.com/s/YnYrNnTKIaYvY1-baBA_wQ)

七、分布式实验室

1. [图解 Kafka](https://mp.weixin.qq.com/s/JxPsvj7dqBsa1Dmu8yjiJQ)

八、TechPaper

1. [如何避免大规模线上故障](https://mp.weixin.qq.com/s/nG_tanEw8FjNxT6VGrDatA)

九、奇伢云存储

1. [深度剖析 Linux 的 3 种“拷贝”命令](https://mp.weixin.qq.com/s/e-G7o8MtTup8ievdzY501Q)

十、mohuishou

1. [3. KubeBuilder 简明教程](https://mp.weixin.qq.com/s/Y0GwLgz9o2HONkl4FJdlVQ)

## GOCN每日新闻--2021-05-08  
1.Go 枚举最佳实践 https://marcofranssen.nl/how-to-do-enums-in-go

2.如何使用 Proto.Cluster 做高可用 https://proto.actor/docs/cluster/intro/clusterintro/

3.在 Go 中实现声明式校验 https://hackernoon.com/golang-declarative-validation-made-similar-to-ruby-on-rails-1d2z34c0

4.Go 中的无分支编码 https://mattnakama.com/blog/go-branchless-coding/

5.不要 mock 数据库连接 https://qvault.io/clean-code/writing-good-unit-tests-dont-mock-database-connections/


## gopherDaily--2021-05-08
- 1.《深入理解BFE》电子书开源 - https://github.com/baidu/bfe-book
- 2.新提案：标准库增加slices包，提供关于切片的泛型函数 - https://github.com/golang/go/issues/45955
- 3.油管视频：用ImmuDB和Go构建防篡改系统 - https://www.youtube.com/watch?v=01_wEMdOp1U
- 4.Kubernetes的5个admission控制策略的OPEN POLICY AGENT实现 - https://blog.styra.com/blog/open-policy-agent-the-top-5-kubernetes-admission-control-policies
- 5.Rook: 在Kubernetes上运行ceph的最佳实践 - https://documentation.suse.com/sbp/all/pdf/SBP-rook-ceph-kubernetes_color_en.pdf
- 6.如何使用CockroachDB在Go应用程序中对JSON数据进行建模 - https://www.cockroachlabs.com/blog/json-go-cockroachdb/
- 7.用100行Go代码搭建一个简单的终端仿真器 - https://ishuah.com/2021/03/10/build-a-terminal-emulator-in-100-lines-of-go/
- 8.六个月过去了，godocs.io的当前状态 - https://drewdevault.com/2021/05/07/godocs.io-six-months-later.html
- 9.新手必备的18个关于go module 小知识 - https://zaracooper.github.io/blog/posts/go-module-tidbits/
- 10.Go泛型介绍 - https://blogtitle.github.io/go-generics/
- 11.继DevOps和GitOps之后的下一步是云工程 - https://thenewstack.io/the-next-step-after-devops-and-gitops-is-cloud-engineering-pulumi-says/


## go中文网每日资讯--2021-05-07


一、Go语言中文网

1. [期待这个 Go 新特性：让 Go 漏洞无处遁形](https://mp.weixin.qq.com/s/eLV8XM3rJwfKteuhoMh0Mw)

2. [微软粉丝一定喜欢这个 Go 工具](https://mp.weixin.qq.com/s/cqiny6vQhsnOhUSK1sigOw)

3. [echo 源码分析之数据绑定过程](https://mp.weixin.qq.com/s/iKB8-tHtQTIjrWJl0pwZEA)

二、亚军进化史

1. [Go技术日报(2021-05-06)——Go语言之禅](https://mp.weixin.qq.com/s/_l33vS0gSqO96WGyexyXIQ)

三、k8s技术圈

1. [云原生平台开发工程师-新加坡-Shopee | 云原生招聘](https://mp.weixin.qq.com/s/7WqROYTzGfrqh_WmXBH1JA)

四、GolangContributorClub

1. [漫谈Go语言编译器（01）](https://mp.weixin.qq.com/s/0q0k8gGX56SBKJvfMquQkQ)

五、polarisxu

1. [Rust 劝退系列 05：复合数据类型](https://mp.weixin.qq.com/s/dtYnwOy3FkGjnOV7vshzvg)

六、幼麟实验室

1. [深度探索Go语言（一）：装箱](https://mp.weixin.qq.com/s/odFKyj63Jr756HHZOwg2YA)

七、mohuishou

1. [2. Kind: 如何快速搭建本地 K8s 开发环境？](https://mp.weixin.qq.com/s/N5RdUxUx4f58qXKL5ha0OQ)

八、脑子进煎鱼了

1. [上帝视角看 “Go 项目标准布局” 之争](https://mp.weixin.qq.com/s/KnsB9cTGnM0X7hNR9VDzxg)

九、章老师说

1. [《深入理解BFE》对外发布](https://mp.weixin.qq.com/s/8TyaVWz0MZ2MkPDGnB65Gw)


## GOCN每日新闻--2021-05-07

1.Go 1.16.4 和 1.15.12 发布 https://groups.google.com/g/golang-nuts/c/_buc5blnKQw

2.新手必备的 Go Module 的 18 个知识 https://zaracooper.github.io/blog/posts/go-module-tidbits/

3.使用 WebRTC，WebSockets 和 Go 在我的个人网站中进行视频聊天 https://mattbutterfield.com/blog/2021-05-02-adding-video-chat

4.Goroutine Local Storage 的一些实现方案和必要性讨论 https://mp.weixin.qq.com/s/luUxiLZCf_x7ZA1LUlP7sA

5.Golang 语言中 kafka 客户端库 sarama https://mp.weixin.qq.com/s/T3dWcf5v1cWMdNbsK3_w2A


## gopherDaily--2021-05-07 

- 1.Go modules速查表 - https://encore.dev/guide/go.mod
- 2.我学到的关于Go的事情  - https://dev.to/belkheir/things-i-learned-about-go-23p6
- 3.Go Crash课程：第一部分 - https://dev.to/moficodes/go-crash-course-part-1-18h1
- 4.深入Go GC源码 - https://zhuanlan.zhihu.com/p/359582221
- 5.Go 1.16.4和1.15.12发布 - https://groups.google.com/g/golang-announce/c/cu9SP4eSXMc
- 6.Kubernetes 上如何控制容器的启动顺序？ - https://mp.weixin.qq.com/s/VulB3tiXTRAjYsuWxgU1Zg
- 7.浅析开源项目之io_uring - https://zhuanlan.zhihu.com/p/361955546
- 8.kubernetes部署反模式 - https://dev.to/codefreshio/kubernetes-deployment-antipatterns-part-1-2116
- 9.SigNoz: datadog的开源替代项目，帮助开发人员监控和诊断应用 - https://github.com/SigNoz/signoz
- 10.分支预测：多少if才算是多？- https://blog.cloudflare.com/branch-predictor/


## 码农桃花源--2021-05-07
### 文章分享
1. [进程和线程的19问](https://mp.weixin.qq.com/s/NCl17jrOwP_A017nUqOkJQ)

2. [Linux内存管理知识点总结](https://mp.weixin.qq.com/s/Y7UhKFJR613hSBOo7kYGoQ)
 
3. [Go for-range排坑指南](https://mp.weixin.qq.com/s/klJBAi5LvdJOGvma2Ir0OA)
### 面试题
1. 缺页中断是什么？linux系统怎么看缺页中断？发现运行着tcp服务器的系统发生大量缺页中断，可能的原因？

2. 讲一下http协议，cookie的跨域

3. redis的zset是如何实现的？为什么只在数据量小的时候用ziplist

### 每日算法
1472 设计浏览器历史浏览记录 https://leetcode-cn.com/problems/design-browser-history/
 


## go中文网每日资讯--2021-05-06 


一、Go语言中文网

1. [Go: 延长变量的生命周期](https://mp.weixin.qq.com/s/S_lO8jQY0TGS7_zvDIUcfw)

2. [echo源码分析](https://mp.weixin.qq.com/s/9FJwmUrqmch9kdjLbldibw)

二、亚军进化史

1. [Go技术日报(2021-05-05)——如何成为一个更好的开发者](https://mp.weixin.qq.com/s/pPnN9ANOI63zGIzOiOEcZA)

三、鸟窝

1. [Go sync.Once的三重门](https://colobu.com/2021/05/05/triple-gates-of-sync-Once/)

四、Go招聘

1. [Go缓存系列之go-cache](https://mp.weixin.qq.com/s/hz7mViPQIwca0mSylfS-ww)

五、多颗糖

1. [Raft 的 Figure 8 讲了什么问题？为什么需要 no-op 日志？](https://mp.weixin.qq.com/s/jzx05Q781ytMXrZ2wrm2Vg)

六、polarisxu

1. [「卷」有理论依据：海勒姆定律—Go又是怎么卷的](https://mp.weixin.qq.com/s/I2Rm1d8LbOQg3V_CFSKgtg)

七、腾讯技术工程

1. [深入剖析虚拟内存工作原理](https://mp.weixin.qq.com/s/c81Fvws0J2tHjcdTgxvv6g)

八、k8s技术圈

1. [Grafana Loki 架构](https://mp.weixin.qq.com/s/dnG4Yye0cP5XtxY0VWiEDg)

九、mohuishou

1. [1. Operator概述: 如何对 Kubernetes 进行扩展](https://mp.weixin.qq.com/s/JX9kt2yg9KsFOsMNxONiew)

## GOCN每日新闻--2021-05-06

1. 《Head First 设计模式》 Go 语言代码示例版本 https://pi-sin0.medium.com/head-first-design-patterns-using-go-introduction-d9f05a4c243a 

2. Go 性能测试实践: 图形化输出比对结果 https://tiagocmelo.medium.com/golang-benchmarking-made-easy-2cefc330701 

3. 给 Go error 增加附加信息 https://romanyx90.medium.com/go-errors-with-additional-details-66873577f3a9

4. 使用 Go 编写一个简单的 REPL https://desmondcheongzx.medium.com/writing-a-simple-repl-in-go-b279e6f4469a 

5. zenity: 支持 windows,mac os 平台的 go zenity 风格对话框库 https://github.com/ncruces/zenity


## gopherDaily--2021-05-06 
- 1.Go语言之禅 - https://mp.weixin.qq.com/s/mKe0w3urHJEe9iYJ7svCuA
- 2.Go vs. Python: 6个问题决定哪种编程语言最适合你 - https://towardsdatascience.com/golang-vs-python-6-questions-to-decide-which-programming-language-is-best-for-you-cf5aa5902c57
- 3.高德 Serverless 平台建设及实践 - https://mp.weixin.qq.com/s/xDBYX3cNYmMU28y5m9COUw
- 4.GitOps 1.0之痛 - https://codefresh.io/devops/pains-gitops-1-0/
- 5.电子书：The Art of Go - https://read.amazon.com/kp/kshare?asin=B08WYNG6YP&id=rxhdkk7jtnefbk2gej35ogfc6m&reshareId=7VR8WH36061JZXH1AJC5&reshareChannel=system
- 6.Go与NUMA架构体系 - https://jbd.dev/numa/
- 7.Open Container Initiative(OCI)发布1.0版本容器规范 - https://opencontainers.org/posts/announcements/2021-05-04-oci-dist-spec-v1/
- 8.Kubernetes IDE - https://github.com/lensapp/lens
- 9.2020 年 CNCF 中国云原生调查报告 - https://mp.weixin.qq.com/s/qz0Fe79iBFDMR1KVvPC6Bw
- 10.使用encore.dev构建bingo游戏后端 - https://eaglewas.me/blog/en/bingo-backend-encore
- 11.IPCDump：linux进程间通信跟踪工具，基于eBPF - https://github.com/guardicore/IPCDump




## go中文网每日资讯--2021-05-05 

一、Go语言中文网

1. [假期余额不足：Gopher们该“卷”起来了！读书、送书](https://mp.weixin.qq.com/s/nZ6cVyclkRCj0vOCvbZxUg)

2. [每日一库之实战项目推荐：rosedb](https://mp.weixin.qq.com/s/xl4XFjPwMAkx2F3v18msTg)

3. [有趣的面试题：Go语言字符串的字节长度和字符个数](https://mp.weixin.qq.com/s/KJ6L8RulYnzJv4gzQn-z5A)

二、亚军进化史

1. [Go技术日报(2021-05-04)——高性能 Go 代码工坊（Part6)](https://mp.weixin.qq.com/s/F8p705mxo82GEd8pPaO7hQ)

三、k8s技术圈

1. [开源云原生应用可观测平台 Pixie](https://mp.weixin.qq.com/s/kwmGF01cJOeJ2OIn-DyyGw)

四、吴亲强的深夜食堂

1. [如何成为一个更好的开发者](https://mp.weixin.qq.com/s/ZNZO0AQLwScYFbOardqY4Q)

五、技术琐话

1. [一位老工程师在谷歌工作十年后的总结：宁愿把团队交给别人带](https://mp.weixin.qq.com/s/05lZHs3TrWzMR-xOCI9KTA)

## GOCN每日新闻--2021-05-05 

1.Golang 中的错误处理 https://gabrieltanner.org/blog/golang-error-handling-definitive-guide

2.Go 实现的测试覆盖率分析工具 https://github.com/kjellkvinge/gocover

3.用于构建现代 API 的 golang 框架 https://github.com/gocondor/gocondor

4.Go 中实现的构建 pipelines 工具 https://github.com/goyek/goyek

5.使用 React 和 Go 实现无限滚动 https://dev.to/josh2604/scroll-infinito-con-react-js-y-go-3112


## gopherDaily--2021-05-05 
- 1.Gopher部落劳动节专属优惠，仅限这5天假期有效，数量有限，先到先得 - https://t.zsxq.com/FQzf6Iq
- 2.Kubernetes的治理、风险和合规性 - https://thenewstack.io/governance-risk-and-compliance-with-kubernetes/
- 3.不使用分支语句的位操作 - https://mattnakama.com/blog/go-branchless-coding/
- 4.油管视频：基于docker构建macos上的Go IDE - https://www.youtube.com/watch?v=zy9PUDqCLHQ
- 5.对分布式跟踪的再思考 - https://encore.dev/blog/tracing-reimagined
- 6.Go json操作与陷阱 - https://hakaselogs.me/2021-05-03/working-with-json-in-go/
- 7.使用strings.Builder快速连接字符串 - https://qvault.io/golang/strings-builder-concatenation-golang/
- 8.Go语言错误处理 - https://gabrieltanner.org/blog/golang-error-handling-definitive-guide
- 9.实时Kubernetes原生应用观察与诊断 - https://github.com/pixie-labs/pixie
- 10.为什么Argo CD是GitOps的生命线？ - https://thenewstack.io/why-argo-cd-is-the-lifeline-of-gitops/
- 11.在多云多集群环境下使用gitops管理k8s - https://www.weave.works/blog/managing-kubernetes-with-gitops-in-a-multi-cluster-multi-cloud-world
- 12.一个VS Code扩展包，帮助用户可视化、理解并与数据互动 - https://github.com/dynamicwebpaige/thinking-in-data
- 13.用Pixie收集对Kubernetes应用、服务和网络流量 - https://aws.amazon.com/cn/blogs/opensource/gathering-insights-on-kubernetes-applications-services-and-network-traffic-with-pixie/
- 14.linux终端工具 - https://ketancmaheshwari.github.io/pdfs/LPT_LISA.pdf
- 15.OpenTelemetry Trace 1.0就绪 - https://cloud.google.com/blog/products/operations/opentelemetry-specification-enables-standardized-tracing


## go中文网每日资讯--2021-05-04 


一、Go语言中文网

1. [Docker 将 “ 跳过更新 ” 设为付费功能，引发网友吐槽](https://mp.weixin.qq.com/s/csGdmpRmy4GATtBUQevxig)

2. [Go语言中常见的几种反模式](https://mp.weixin.qq.com/s/KmKvwc0eeUuKAWASnTHBRA)

3. [谈谈 Kubernetes 的问题和局限性](https://mp.weixin.qq.com/s/ZjRAKzDaMuNJquJBONJe-g)

二、TechPaper

1. [长尾延迟问题的一些解决思路](https://mp.weixin.qq.com/s/y_bQIsKHwyWauwaXB_8fXg)

三、k8s技术圈

1. [Promtail 配置文件说明](https://mp.weixin.qq.com/s/x7qik5HGzngH8rTiusiKMA)

四、分布式实验室

1. [2020 年 CNCF 中国云原生调查报告](https://mp.weixin.qq.com/s/qz0Fe79iBFDMR1KVvPC6Bw)

五、GoOfficialBlog

1. [高性能 Go 代码工坊（Part6)](https://mp.weixin.qq.com/s/1HmYMBvc1uSYE_zVhJITTQ)
## GOCN每日新闻--2021-05-04 

1.pprof 的原理与实现 https://mp.weixin.qq.com/s/to1g7mk8JuFapDbnqhsFPw

2.深入 Go 语言 defer 实现原理 https://www.luozhiyun.com/archives/523

3.新细节，Go 1.17 将允许切片转换为数组指针 https://mp.weixin.qq.com/s/v1czjzlUsaSQTpAOG9Ub3w

4.Promtail Pipeline 日志处理配置 https://mp.weixin.qq.com/s/PPNa7CYk6aaYDcvH9eTw1w

5.文章转视频 text-to-video https://github.com/leoython/text-to-video




## gopherDaily--2021-05-04 
- 1.Gopher部落劳动节专属优惠，仅限这5天假期有效，数量有限，先到先得 - https://t.zsxq.com/FQzf6Iq
- 2.如何使用Go对helm chart进行单元测试 - https://blog.heyal.co.uk/unit-testing-helm-charts/
- 3.使用discovery selector在istio服务网格中配置namespace - https://istio.io/latest/blog/2021/discovery-selectors/
- 4.如何使用Go将一个html文件转换为pdf - https://hackernoon.com/how-to-generate-a-pdf-report-from-html-with-go-p02f33kx
- 5.用于编写构建流水线的Go库 - https://github.com/goyek/goyek
- 6.Go版本的github action - https://github.com/marketplace/actions/go-version-action
- 7.使用自动协调的7种方法，DevOps可以克服可扩展性的挑战 - https://thenewstack.io/7-ways-devops-can-overcome-scalability-challenges-using-automated-orchestration/
- 8.通过部署etcd集群来解读Kubernetes上的有状态应用程序 - https://blog.harbur.io/demystifying-stateful-apps-on-kubernetes-by-deploying-an-etcd-cluster-b85bf8c16fea
- 9.使用Tekton为GitHub仓库建立云原生CI/CD的七个步骤 - https://blog.harbur.io/the-seven-steps-to-build-a-cloud-native-ci-cd-for-github-repos-using-tekton-31a445a3bde7
- 10.使用WebRTC、Websockets和Golang在我的个人网站上建立视频聊天 - https://mattbutterfield.com/blog/2021-05-02-adding-video-chat
- 11.如何使用SQL来进行快速和有效的数据分析 - https://hakibenita.com/sql-for-data-analysis
- 12.用蒙特卡洛模拟解决问题的艺术 - https://ggcarvalho.dev/posts/montecarlo/



## go中文网每日资讯--2021-05-03 

一、Go语言中文网

1. [Russ Cox 看不下去了：golang-standards/project-layout 不是 Go 标准布局](https://mp.weixin.qq.com/s/i5zv5CK7YkkcFwzpRdBicg)

2. [Go 笔试题精选 二： 25 道选择题](https://mp.weixin.qq.com/s/xMXRafxVHud1yyz8GVM3GA)

3. [更简的并发代码，更强的并发控制](https://mp.weixin.qq.com/s/zLmlOPYnqmQtv8ZKIu92Gg)

二、k8s技术圈

1. [Promtail Pipeline 日志处理配置](https://mp.weixin.qq.com/s/PPNa7CYk6aaYDcvH9eTw1w)

三、Go招聘

1. [祝大家5.1快乐，4/26-4/30股文请接收](https://mp.weixin.qq.com/s/6PoolfReXr2vz0JNOeDKHw)

四、medium-Syafdia Okta

1. [Go concurrency pattern: Pipeline](https://syafdia.medium.com/go-concurrency-pattern-pipeline-635dfae01af1)

2. [Go concurrency pattern: Worker Pool](https://syafdia.medium.com/go-concurrency-pattern-worker-pool-a437117025b1)

## GOCN每日新闻--2021-05-03 
1.Go 与 WebAssembly https://www.bradcypert.com/an-introduction-to-targeting-web-assembly-with-golang/

2.配置 VSCode 和 Docker 开发调试 Go https://dev.to/andreidascalu/setup-go-with-vscode-in-docker-for-debugging-24ch

3.Proposal: Go 漏洞数据库 https://go.googlesource.com/proposal/+/master/design/draft-vulndb.md

4.Go Modules 速查表 https://encore.dev/guide/go.mod

5.使用 knative 部署 serverless 服务 https://aymen-segni.com/index.php/2020/07/22/deploying-your-serverless-services-on-kubernetes-using-knative/



## gopherDaily--2021-05-03 
- 1.Gopher部落劳动节专属优惠，仅限这5天假期有效，数量有限，先到先得 - https://t.zsxq.com/FQzf6Iq
- 2.在你的CI/CD管道中使用Docker指南 - https://circleci.com/blog/guide-to-using-docker-for-your-ci-cd-pipelines/
- 3.Go gRPC初学者指南 - https://www.youtube.com/watch?v=BdzYdN_Zd9Q&feature=youtu.be
- 4.从头学Go性能剖析 - https://www.youtube.com/watch?v=-twKyx5KU0c
- 5.Go是后端语言的未来吗 - https://medium.com/@lilligroeneveld/is-go-golang-the-future-of-backend-943b87dc9cdb
- 6.使用knative在k8s集群上部署serveless服务 - https://aymen-segni.com/index.php/2020/07/22/deploying-your-serverless-services-on-kubernetes-using-knative/
- 7.在gitpub page上跑sqlite数据库 - https://phiresky.github.io/blog/2021/hosting-sqlite-databases-on-github-pages/
- 8.bloaty: 一个二进制文件大小剖析工具，对go提供了支持 - https://github.com/google/bloaty/issues/204#event-4673913000
- 9.动态共享库不是个好东西 - https://lore.kernel.org/lkml/CAHk-=whs8QZf3YnifdLv57+FhBi5_WeNTG1B-suOES=RcUSmQg@mail.gmail.com/
- 10.Go实现的命令行多协议下载工具 - https://github.com/Imputes/fdlr
- 11.了解软件开发生命周期的各个阶段 - https://harness.io/blog/devops/software-development-life-cycle/



## go中文网每日资讯--2021-05-02 


一、Go语言中文网

1. [Go语言爱好者周刊：第 93 期 — 架构师的自我修炼](https://mp.weixin.qq.com/s/lkNHnIrEPAE-C7p3YK4hFg)

2. [为什么我们需要在  Go 中使用 iota](https://mp.weixin.qq.com/s/ygapABjP6JJ9uBGSf8pc4g)

3. [Go - 一个对新手很友好的项目(带界面)](https://mp.weixin.qq.com/s/vPnOrwnuq0zRISuimNCfnQ)

二、亚军进化史

1. [Go技术日报(2021-05-01)——pprof 的原理与实现](https://mp.weixin.qq.com/s/C4uWiAKyVhC8fJqg4pjSnA)

三、k8s技术圈

1. [使用 Loki 收集 nginx 日志](https://mp.weixin.qq.com/s/5EW8HPlmqZ7XVPD-1lRlSA)

四、polarisxu

1. [五一快乐！又来送书了，节后提升实力](https://mp.weixin.qq.com/s/TQgYP24H_Qgm5BZdGMI1hA)

五、TechPaper

1. [画好图才能做好 PPT](https://mp.weixin.qq.com/s/xai1fWwJiD6rSvIBvzIuog)

六、luozhiyun很酷

1. [Go语言实现Snowflake雪花算法](https://mp.weixin.qq.com/s/V0W5AcN4viWvX_w7yW0dzQ)

七、网管叨bi叨

1. [Goroutine Local Storage的一些实现方案和必要性讨论](https://mp.weixin.qq.com/s/luUxiLZCf_x7ZA1LUlP7sA)


## GOCN每日新闻--2021-05-02 
1.Open Saves: Google 开源的为游戏设计的云原生存储 https://cloud.google.com/blog/products/media-entertainment/introducing-open-saves

2.Go 用户案例: 各领域公司使用案例 https://medium.com/@softkraft/companies-using-golang-by-domain-golang-use-cases-6870b9001e82

3.构建强壮的电商 Service Mesh https://resources.fabric.inc/blog/ecommerce-service-mesh

4.Go 实现的 Apollo Federation Gateway 替代品 https://github.com/jensneuse/graphql-go-tools

5.YoyoGo (web&grpc) 微服务框架 https://gocn.vip/topics/12015




## go中文网每日资讯--2021-05-01 


一、Go语言中文网

1. [翻车了，记一次 Go 线上事故](https://mp.weixin.qq.com/s/TCLYIxhuLdXnHXezKM660g)

2. [这一次，彻底搞懂 Go Cond](https://mp.weixin.qq.com/s/YcXC9Bxz34EYl20p8_TQIg)

3. [Go语言内部包--控制包成员的对外暴露](https://mp.weixin.qq.com/s/Y2I0IVEC3oosORxJ5sRGTA)

二、亚军进化史

1. [Go技术日报(2021-04-30)——如何提高代码的扩展性](https://mp.weixin.qq.com/s/71PiTxeyCdM0SgWpLfNACw)

三、TechPaper

1. [pprof 的原理与实现](https://mp.weixin.qq.com/s/1VoZ9dZYk7-yWS3mP0Nc-w)

四、GoOfficialBlog

1. [fuckdb 新功能上线，开箱即用、更加强大的代码生成器](https://mp.weixin.qq.com/s/3wCZRWBoZG9RGuyjd-Aekg)




## GOCN每日新闻--2021-05-01
1.[Golang Http 库指定 dns 服务器进行解析 ](https://gocn.vip/topics/12017)

2.[Go 真的也可以进行 GUI 开发：还有这样的图书呢 ](https://mp.weixin.qq.com/s/2kms7zoK39CL6aVSWrpAbQ)

3.[基于 golang 爬虫框架 gathertool 快速编写并发抓取国内 ip 信息]( https://gocn.vip/topics/12002)

4.[cronexpr 定时任务解析器 ](https://gocn.vip/topics/11989)

5.[小米 Site Reliability Engineer ](https://gocn.vip/topics/12012)



## gopherDaily--2021-05-01 

- 1.[Gopher部落劳动节专属优惠，仅限这5天假期有效，数量有限，先到先得]( https://t.zsxq.com/FQzf6Iq)

- 2.[Go官方漏洞数据库设计草案 ](https://go.googlesource.com/proposal/+/master/design/draft-vulndb.md)

- 3.[Elasticsearch的Go开发者指南 ]( https://developer.okta.com/blog/2021/04/23/elasticsearch-go-developers-guide)

- 4.[Go present演示文稿工具入门 ](https://dev.to/charly3pins/level-up-your-presentations-with-go-59lo)

- 5.[open save: Google为游戏开源的云原生存储 ](https://cloud.google.com/blog/products/media-entertainment/introducing-open-saves)

- 6.[使用Go和github action自动更新github profile readme ](https://charly3pins.dev/blog/automate-your-github-profile-readme-with-go-and-github-actions/)


- 7.[HashiTalks 2021 Terraform合集 ](https://www.hashicorp.com/blog/hashitalks-2021-highlights-terraform)


- 8.[minio优化小对象存储 ](https://blog.min.io/minio-optimizes-small-objects)

- 9.[devdash: 高度可配置的基于命令行终端的开发者仪表盘](https://github.com/Phantas0s/devdash) 


- 10.[医疗IT领域的区块链 ](https://www.himss.org/resources/blockchain-healthcare)

- 11.[构建一个健壮的电商服务网格]( https://resources.fabric.inc/blog/ecommerce-service-mesh)

- 12.[服务网格用例](https://lucperkins.dev/blog/service-mesh-use-cases/) 

- 13.[油管视频：eBFP、cilium和wireguard ](https://www.youtube.com/watch?v=-awkPi3D60E)

- 14.[如何在goland中使用docker编译和运行go代码]( https://blog.jetbrains.com/go/2021/04/30/how-to-use-docker-to-compile-go-from-goland/)

## go中文网每日资讯--2021-04-30 
一、Go语言中文网

1. [Go 运行时调度器处理系统调用的巧妙方式](https://mp.weixin.qq.com/s/zyvCj2bC9aTkrFB_J_kQcA)

2. [掌握 cgo 的字符串函数](https://mp.weixin.qq.com/s/RFMKhSmc22GwxeIeI8MAGQ)

二、亚军进化史

1. [Go技术日报(2021-04-29)——QUIC 协议在蚂蚁落地综述](https://mp.weixin.qq.com/s/wboDsOAA_TuOx-rzyWmNnw)

三、奇伢云存储

1. [存储进阶—怎么才能保证 IO 数据的安全？](https://mp.weixin.qq.com/s/2lUjSnidY_RVQ4jNWGHvLw)

四、腾讯云CDN

1. [大咖聊QUIC—腾讯CDN技术总监李丛](https://mp.weixin.qq.com/s/-9JfPnnPL-mM5fNYXVksLw)

五、k8s技术圈

1. [KubeSphere 3.1.0 GA：混合多云走向边缘，让应用无处不在](https://mp.weixin.qq.com/s/lwEMVwJ1h1hL2N8mr3Bj1A)

2. [k8s 内网和办公网络的打通实践](https://mp.weixin.qq.com/s/AHuGtMjfHo7-Wi_CBGiBkQ)

六、polarisxu

1. [五一快乐！Go 团队开始重视安全问题了](https://mp.weixin.qq.com/s/-Zv1QwM1lYNWEvIoUNjmXQ)

七、技术琐话

1. [如何提高代码的扩展性](https://mp.weixin.qq.com/s/KHgaB3K5ikz1caZkpaFZGA)

八、Go招聘

1. [国际电商福利好还不加班，爱了爱了](https://mp.weixin.qq.com/s/T7jhXipYkCezKN9LjK_sEQ)

九、腾讯技术工程​

1. [「直播回放」Go语言并发调度器和网络模型解析 - 知乎](https://www.zhihu.com/zvideo/1371214468270071808)

十、Go夜读

1. [视频回放-#113 性能优化究竟应该怎么做？- By 曹大](https://www.bilibili.com/video/BV1Z64y1m7uc)


## gopherDaily--2021-04-30
1.Go播客：使用Go构建初创公司技术栈 - https://changelog.com/gotime/177

2.并行的表驱动测试 - https://www.gopherguides.com/articles/table-driven-testing-in-parallel

3.litestream如何以0.03美元/月的价格替代了我的数据库服务器 - https://mtlynch.io/litestream/

4.在Go中为什么以及如何实现枚举 - https://dev.to/qvault/how-and-why-to-write-enums-in-go-1lmb

5.Go channel深度使用 - https://g14a.github.io/tags/channels/

6.Redis实验室：为什么延迟不应该是人工智能时代的问题？ - https://thenewstack.io/redis-labs-why-latency-shouldnt-be-an-issue-in-the-age-of-ai/

7.为什么Kubernetes需要istio - https://www.tetrate.io/blog/what-is-istio-and-why-does-kubernetes-need-it/

8.优雅的Go rest api框架 - https://github.com/go-goyave/goyave

9.编写高性能GraphQL应用的go包 - https://github.com/jensneuse/graphql-go-tools

10.trivy: 一个针对容器镜像、Git存储库和文件系统的简单而全面的漏洞扫描器 - https://github.com/aquasecurity/trivy

11.我们如何使用Golang和Dataflow构建一个金融犯罪特征库 - https://medium.com/sardineai/building-a-fincrime-feature-store-how-we-use-golang-and-dataflow-e1b8edc0f535

## 码农桃花源--2021-04-30
### 文章分享
1. [编程模式 pipeline](https://coolshell.cn/articles/21228.html)

2. [了解rust](https://coolshell.cn/articles/20845.html)

3. [rust 02](https://mp.weixin.qq.com/s/dUFJMEzOJGwM5YY8cP9MBQ)

4. [数据库19年2月月报](http://mysql.taobao.org/monthly/2019/02/)

### 面试题
1. redis 全局 Hash 表又是什么？如何扩容的？

2. 什么是渐进式 rehash？Redis 怎么做到的？

3. IO 多路复用是什么？多路是什么？复用了什么？

4. AOF 和 RDB 又是什么？为什么 Redis 没有实现 WAL 机制？AOF 持久化策略有哪三种？你们是怎么选的？

5. AOF 什么时候重写？为什么重写？
### 每日算法
反转字符串 写出最优解


## go中文网每日资讯--2021-04-29 

一、Go语言中文网

1. [Go 切片的一种有趣内存泄漏方式](https://mp.weixin.qq.com/s/gMt7hY9PEWW0XMt70vI84w)

2. [Go 切片的一种有趣内存泄漏方式](https://mp.weixin.qq.com/s/gMt7hY9PEWW0XMt70vI84w)

二、亚军进化史

1. [Go技术日报(2021-04-28)——在Go中，你犯过这些错误吗](https://mp.weixin.qq.com/s/IovH52ZlEfvOwW1PSrM-3w)

三、码农桃花源

1. [QUIC 协议在蚂蚁落地综述](https://mp.weixin.qq.com/s/PEfz04LHOjVrZK6K45OgzA)

2. [KubeSphere 3.1.0 GA：混合多云走向边缘，让应用无处不在](https://mp.weixin.qq.com/s/jJsldNRijylB_EBUhOXULA)

四、腾讯技术

1. [“鹅厂老司机”谈破局：做自己的破壁人](https://mp.weixin.qq.com/s/UE5T29ZZmnvJ7_WA-ztgEQ)

五、polarisxu

1. [Go 真的也可以进行 GUI 开发：还有这样的图书呢](https://mp.weixin.qq.com/s/2kms7zoK39CL6aVSWrpAbQ)

六、CloudNativeCommunity

1. [Kubernetes 源码图解](https://mp.weixin.qq.com/s/s1vJu7TmANzE4r0se0OF0g)

2. [云原生学院第19直播视频回放](https://mp.weixin.qq.com/s/c3akppn1E1BEfuLEwB-JKg)

七、脑子进煎鱼了

1. [Go 程序崩了？煎鱼教你用 PProf 工具来救火！](https://mp.weixin.qq.com/s/9yLd7kkYzmbCriolhbvK_g)


## GOCN每日新闻--2021-04-29 
1.GO 重复利用 Prepare 后的 stmt 来提高 MySQL 的执行效率  https://learnku.com/go/t/49736

2.到处都是 GO111MODULE，这到底什么？ https://learnku.com/go/t/39086

3.谈谈 Redis 的 9 种数据结构以及它们的内部编码实现  https://gobea.cn/blog/detail/OrJRxArd.html

4.Golang 服务之坑：too many open files  https://gobea.cn/blog/detail/NoW32Qob.html 

5.为什么 HTTPS 需要 7 次握手以及 9 倍时延  https://draveness.me/whys-the-design-https-latency/


## gopherDaily--2021-04-29
1.Go Json操作终极指南 - https://qvault.io/golang/json-golang/

2.在生产环境使用dapr(分布式应用运行时) - https://blog.dapr.io/posts/2021/02/09/running-dapr-in-production-at-roadwork/

3.加密UDP传输库 - https://github.com/balacode/udpt

4.基于Gorgonia实现的生成式对抗性网络示例 - https://github.com/LdDl/gan-go

5.从头构建一个kubectl plugin - https://www.pixelstech.net/article/1606901393-Build-a-Kubectl-Plugin-from-Scratch

6.kubernetes: 使用拓扑感知路由的高效多区网络 - https://opensource.googleblog.com/2020/11/kubernetes-efficient-multi-zone.html

7.我如何在Go中构造服务 - https://medium.com/@ott.kristian/how-i-structure-services-in-go-19147ad0e6bd

8.Go语法树入门——开启自制编程语言和编译器之旅 - https://github.com/chai2010/go-ast-book

9.hashicorp go-plugin构建golang插件系统 - https://mp.weixin.qq.com/s/N1BWGheV8ZIpO5L90vaZyg

10.减少aws k8s账单的七个方法 - https://thenewstack.io/7-tips-for-cutting-down-your-aws-kubernetes-bill


## 码农桃花源--2021-04-29
### 文章分享
1. [pprof](https://mp.weixin.qq.com/s/9yLd7kkYzmbCriolhbvK_g)

2. [go map](https://mp.weixin.qq.com/s/MzAktbjNyZD0xRVTPRKHpw)

3. [rust 01](https://mp.weixin.qq.com/s/2GGY_q90NqMd_A2SssOKog)	

4. [数据库19年2月月报](http://mysql.taobao.org/monthly/2019/02/)

### 面试题
1. Redis 它的 5 种基础类型和 6 个数据结构说下。

2. HyperLogLog、BitMap、GEO、Stream 有接触过吗？

3. 什么时候用这些特殊数据结构？跳表又是什么，画一下？

4. 为什么使用跳表？

5. 为什么不用红黑树？

### 每日算法
反转字符串 写出最优解

## go中文网每日资讯--2021-04-28 


一、Go语言中文网

1. [Go 语言中 runtime.KeepAlive() 方法的一些随笔](https://mp.weixin.qq.com/s/0-14E7Enk6TsZ1_vifznvA)

2. [在Go中，你犯过这些错误吗](https://mp.weixin.qq.com/s/bzYTYwKN2J6rIMjfYn-eZA)

二、亚军进化史

1. [Go技术日报(2021-04-27)——图解 g0：特殊的 goroutine](https://mp.weixin.qq.com/s/eZYQyWREOFJS6x9-TzfXvA)

三、polarisxu

1. [Rust 劝退系列 04：基本数据类型](https://mp.weixin.qq.com/s/kHVGK2b0oAidORE5C8Yopg)

四、Go招聘

1. [Russ Cox 看不下去了：golang-standards/project-layout 不是 Go 标准布局](https://mp.weixin.qq.com/s/eZrIRO3Etu9vgZi7lkR81A)

五、多颗糖

1. [运行 3000 次都不出错的 MIT 6.824 Raft 实验](https://mp.weixin.qq.com/s/KuiSHx9iObnTtGYh4Gxbpg)

六、Go夜读

1. [性能优化究竟应该怎么做？](https://mp.weixin.qq.com/s/_69pA5aQPhqXCOJpmrSmQQ)

七、逸言

1. [领域驱动架构风格](https://mp.weixin.qq.com/s/nMkxatKgjQLLiEa5fFFxmg)

八、No Headback

1. [《写作的逻辑》简单读书笔记](https://xargin.com/notes-on-logic-writing/)



## GOCN每日新闻--2021-04-28
1.快速 TCP/UDP 通道 https://github.com/jpillora/chisel

2.Golang 中并发 API 模式 https://tech.deliveryhero.com/concurrent-api-patterns-in-go/

3.图解 g0：特殊的 goroutine https://mp.weixin.qq.com/s/_Tl1cGTdPxwSF1ctHc1yZg

4.边开飞机边换引擎？我们造了个新功能保障业务流量无损迁移 https://gocn.vip/topics/11998

5.用 Go map 要注意这 1 个细节，避免依赖 https://mp.weixin.qq.com/s/MzAktbjNyZD0xRVTPRKHpw

## gopherDaily--2021-04-28
1.Go web开发的当前状态 - https://tnotes.dev/posts/state-of-web-dev-in-golang

2.Russ Cox：这不是Go项目的标准布局！ - https://github.com/golang-standards/project-layout/issues/117

3.DRPC介绍：gRPC的替代者 - https://www.storj.io/blog/introducing-drpc-our-replacement-for-grpc

4.使用Go和next.js开发可移植的应用 - https://v0x.nl/articles/portable-apps-go-nextjs

5.大规模系统的逆向调试 - https://engineering.fb.com/2021/04/27/developer-tools/reverse-debugging/

6.Go系统编程 - https://t.zsxq.com/bAuNZzF

7.使用testify进行go包测试 - https://shores.dev/testify-golang-package-for-go/

8.在遗留Go项目中启用go module会发生什么 - https://speakerdeck.com/line_developers_tw2/what-will-happen-when-you-enable-go-modules-on-the-legacy-go-projects

9.第三方微信公众平台和微信商户平台Go SDK - https://github.com/chanxuehong/wechat

10.开放的航班、航线等数据 - https://openflights.org/data.html

11.k8s原生serverless框架 - https://github.com/kubeless/kubeless


## 码农桃花源--2021-04-28
### 文章分享
1. [dealline调度器原理](http://www.wowotech.net/process_management/deadline-scheduler-1.html)

2. [编译原理理论与实战](https://cloud.tencent.com/developer/article/1776822)

3. [高性能队列——Disruptor](https://tech.meituan.com/2016/11/18/disruptor.html)

### 面试题
1. golang 的 runtime 机制?

2. 如何获取 go 程序运行时的协程数量, gc 时间, 对象数, 堆栈信息?

3. 对map进行并发访问，需要同步操作吗？

### 每日算法
lc1793 好子数组的最大分数 https://leetcode-cn.com/problems/maximum-score-of-a-good-subarray/



## go中文网每日资讯--2021-04-27 


一、Go语言中文网

1. [图解 g0：特殊的 goroutine](https://mp.weixin.qq.com/s/_Tl1cGTdPxwSF1ctHc1yZg)

2. [Go 数据结构和算法篇（十三）：字符串匹配之 Trie 树](https://mp.weixin.qq.com/s/myq1qAWREN_sKgWwIT_O4w)

二、亚军进化史

1. [Go技术日报(2021-04-26)——Go 语言的 “黑暗角落”](https://mp.weixin.qq.com/s/6PtqhYFJExxLf12ySS19_w)

三、polarisxu

1. [Rust语言24个绝佳框架、项目及资料库](https://mp.weixin.qq.com/s/muLkr6ICfsbsRc-BVVtwGg)

四、脑子进煎鱼了

1. [用 Go map 要注意这 1 个细节，避免依赖他！](https://mp.weixin.qq.com/s/MzAktbjNyZD0xRVTPRKHpw)

五、真没什么逻辑

1. [为什么 Linux 和 macOS 不需要碎片整理](https://mp.weixin.qq.com/s/6UzsOL7NivThJTQOfJDNbQ)

六、百度Geek说

1. [百度商业大规模微服务分布式监控系统——凤睛](https://mp.weixin.qq.com/s/99fESnkMpiJsKJmTdN2G0g)

七、k8s技术圈

1. [使用 EFKLK 搭建 Kubernetes 日志收集工具栈](https://mp.weixin.qq.com/s/lPeYavvFJ6GdivkT0iwTGw)

八、网管叨bi叨

1. [Interceptor拦截器 -- gRPC生态里的中间件](https://mp.weixin.qq.com/s/kHW5t0bqLuJZUNNknBJnAA)

九、Go招聘

1. [一手资源在手，说Go就Go](https://mp.weixin.qq.com/s/t4bxO8PBUf0BLhlWFs-O_A)
## GOCN每日新闻--2021-04-27

1.基于 getty 的分布式事务框架 seata-golang 通信模型详解 https://blog.51cto.com/u_4313251/2731656

2.Go 标准库 http 与 fasthttp 服务端性能比较 https://tonybai.com/2021/04/25/server-side-performance-nethttp-vs-fasthttp/

3.Go 可用性 (五) 限流 4: 自适应限流 http://lailin.xyz/post/go-training-week6-4-auto-limiter.html

4.Go 实现的云盘系统 https://github.com/eyebluecn/tank

5.构建 golang 插件系统的利器--go-plugin https://gocn.vip/topics/11990


## gopherDaily--2021-04-27


1.一文看懂容器网络 - https://iximiuz.com/en/posts/container-networking-is-simple/

2.Schema即代码：facebook Ent教程 - https://developers.facebook.com/blog/post/2021/04/26/eli5-ent-schema-as-code-go/

3.超越块与文件：COSI开启kubernetes上的对象存储 - https://thenewstack.io/beyond-block-and-file-cosi-enables-object-storage-in-kubernetes/

4.基于k8s persistent卷配置nfs - https://www.linuxtechi.com/configure-nfs-persistent-volume-kubernetes/

5.图解Kubernetes中的服务发现 - https://iximiuz.com/en/posts/service-discovery-in-kubernetes/

6.Karmada：多云多k8s集群应用编排 - https://github.com/karmada-io/karmada

7.你可能需要配置Kubernetes liveness和readiness探针 - https://itnext.io/you-probably-need-liveness-and-readiness-probes-a52e213cd38b

8.没有人关心你的漂亮代码 - https://felipecsl.com/2021/04/26/nobody-cares-about-your-beautiful-code.html

9.使用goreleaser分发你的cli应用 - https://appliedgo.net/release/

10.基于gocv的对象检测系统 - https://github.com/wimspaargaren/yolov3

11.cilium支持arm64架构 - https://github.com/cilium/cilium/issues/9898#issuecomment-824218940

## 码农桃花源--2021-04-27
### 文章分享
1. [Linux内存管理知识总结1](https://zhuanlan.zhihu.com/p/366957562)

2. [Dapr—云原生的抽象与实现](https://www.imooc.com/article/316767)

3. [console、terminal、tty都是啥？](http://www.wowotech.net/tty_framework/tty_concept.html)

### 面试题
1. 一致性hash算法知道吗？有什么用？

2. 介绍一下linux的磁盘调度算法？noop算法和什么硬件搭配使用

3. 事务ACID特性中的C(一致性)和CAP理论的C(一致性)有什么区别?

4. 数据库的隔离性指的是什么？你知道哪些隔离级别？

### 每日算法
lc363 矩形区域不超过K的最大数值和

## go中文网每日资讯--2021-04-26

一、Go语言中文网

1. [使用 timeout、deadline 和 context 取消参数使 Go net/http 服务更灵活](https://mp.weixin.qq.com/s/Wse5avtLhhtMeBTVRPNwow)

2. [Go 数据结构和算法篇（十二）：字符串匹配之 KMP 算法](https://mp.weixin.qq.com/s/sBz1r5tvEYoX3cqupCdGRA)

二、亚军进化史

1. [Go技术日报(2021-04-25)——协程，协程和线程](https://mp.weixin.qq.com/s/AfRzKFd4j21cLsUY-972GA)

三、吴亲强的深夜食堂

1. [为什么我们需要在  Go 中使用 iota](https://mp.weixin.qq.com/s/HOkquS6bA1I18TyT1lR8zQ)

四、polarisxu

1. [Go 语言一些最佳实践：建议收藏](https://mp.weixin.qq.com/s/75e43zUD4ClpTQGZtZwU2Q)

五、MoeLove

1. [K8S 生态周报| Docker v20.10.6 发布， 修正了 K8S 中 dind 的异常行为](https://mp.weixin.qq.com/s/o--duARxH2AS04S8vCZcNw)

六、CloudNativeCommunity

1. [基准测试五宗罪](https://mp.weixin.qq.com/s/7QfzpQvIK-9hLsQAIcQyCg)

七、Golang梦工厂

1. [有趣的面试题：Go语言字符串的字节长度和字符个数](https://mp.weixin.qq.com/s/p0plkyH1OpiAhjE8Gxvpog)

八、即时通讯技术圈

1. [直播系统聊天技术(四)：百度直播的海量用户实时消息系统架构演进实践](https://mp.weixin.qq.com/s/xUR1_7vfsr8TkcZA72Trvg)





## GOCN每日新闻--2021-04-26
1.Go 泛型的示例代码 https://github.com/mattn/go-generics-example

2.盘点一下 Go 语言的 “黑暗角落” https://mp.weixin.qq.com/s/XLvWg9kRoiR4WPhjXE5X_g

3.golang 面向对象分析 https://www.cnblogs.com/457220157-FTD/p/14703692.html

4.使用 Go defer 要小心这 2 个雷区！ https://mp.weixin.qq.com/s/ZEsWa4xUb0a7tWemVZMXVw

5.Boyer-Moore 快速字符串搜索算法在 Go 中的实现 https://github.com/sarpdag/boyermoore



## gopherDaily--2021-04-26
1.使用Go开发一个代码生成器 - https://levelup.gitconnected.com/writing-a-code-generator-in-go-420e69151ab1

2.油管视频：全面理解Go rune类型 - https://www.youtube.com/watch?v=7isCXLWPTqI

3.Go实现的云盘系统 - https://github.com/eyebluecn/tank

4.大白话认识 Kafka 背后优秀的架构设计 - https://mp.weixin.qq.com/s/ed-BTtLwOy_BmD946F3ioQ

5.k8s CPU和内存分配的简单快速调整 - https://itnext.io/easy-and-fast-adjustment-of-kubernetes-cpu-and-memory-709394cc2cb1

6.使用docker和git tag实现heroku式的部署 - https://ricardoanderegg.com/posts/git-push-deployments-docker-tags/

7.理解云复杂性的根源 - https://www.transposit.com/blog/understanding-the-roots-of-our-cloud-complexity/

8.Slim：一个空间效率高效的数据类型的集合，可通过序列化API将数据持久化在磁盘上或用于传输 - https://github.com/openacid/slim

9.Rust语言速查表 - https://cheats.rs/

10.基于markdown的在线slide演示工具 - https://mark.show/#/

11.swift语言在服务端的现状 - https://theswiftdev.com/swift-on-the-server-in-2020/




## 码农桃花源--2021-04-26
### 文章分享
1. [Nginx架构分析](https://cloud.tencent.com/developer/article/1812708)

2. [QUIC协议原理分析](https://cloud.tencent.com/developer/article/1017235?from=article.detail.1812708)

3. [分布式定时器介绍](https://cloud.tencent.com/developer/article/1807494)

### 面试题
1. 进程间通信方法，共享内存用了什么系统调用？

2. 段页式内存管理下的逻辑地址和物理地址转换

3. 堆排序建堆的时间复杂度？

4. 常用的GC有哪些？介绍一下Go语言的GC


### 每日算法
1011 在D天内送达包裹的能力

## go中文网每日资讯--2021-04-25 


一、Go语言中文网

1. [Go语言爱好者周刊：第 92 期](https://mp.weixin.qq.com/s/IZo3-G07Us6q_XKi6EXxLg)

2. [Go 数据结构和算法篇（十一）：字符串匹配之 BF 算法](https://mp.weixin.qq.com/s/PYIav0RQSGq8Vcc9JD8_cg)

二、亚军进化史

1. [Go技术日报(2021-04-24)——go 语言的 31 个坑](https://mp.weixin.qq.com/s/zn3iMrW4808zt-44stwgHA)

三、k8s技术圈

1. [应该了解的 10 个 Kubernetes 安全上下文配置](https://mp.weixin.qq.com/s/NFgQrvn_LyU0qQbhMZwDAQ)

2. [招聘 SRE 工程师 - 合合信息 | 云原生招聘](https://mp.weixin.qq.com/s/lSOsp3fyAmfRo0egRPtshg)

四、脑子进煎鱼了

1. [Go 面试官：什么是协程，协程和线程的区别和联系？](https://mp.weixin.qq.com/s/vW5n_JWa3I-Qopbx4TmIgQ)

五、Golang梦工厂

1. [面试官：两个nil比较结果是什么？](https://mp.weixin.qq.com/s/Dt46eoEXXXZc2ymr67_LVQ)

六、TonyBai

1. [Go标准库http与fasthttp服务端性能比较](https://mp.weixin.qq.com/s/aX9_ZAXfDQZQZrkq-6DZew)

七、Go招聘

1. [4/19-4/25股文请接收](https://mp.weixin.qq.com/s/f8MWmVTwfpZBxiUu_stubA)
## go中文网每日资讯--2021-04-24


一、Go语言中文网

1. [Go 在 AI 领域也火了？这招聘不错，薪资不低](https://mp.weixin.qq.com/s/eb_Ilz_G7vZHQwCVqLxToQ)

2. [redis 跳表分析并用 Go 实现 — 碾压面试官](https://mp.weixin.qq.com/s/c3mOGotVOzUrl1P8r-PSxA)

3. [源码剖析Go类型断言是如何实现的！附性能损耗测试](https://mp.weixin.qq.com/s/ZpdggO78kTX4bDHyKlzF-g)

二、亚军进化史

1. [Go技术日报(2021-04-23)——站长的Go语言书单](https://mp.weixin.qq.com/s/230JbBZEngEtyNtBE5N03w)

三、polarisxu

1. [true != true？面试官，你坑人！！！](https://mp.weixin.qq.com/s/3cPsMRrsk4CaNAbpx283kw)

四、吴亲强的深夜食堂

1. [在Go中，你犯过这些错误吗](https://mp.weixin.qq.com/s/zMfukmRvVOXl9Fq3nyjgIg)

五、后端技术指南针

1. [Redis 6.0多线程探秘(上)](https://mp.weixin.qq.com/s/KQ_j4-3BP32aBH2-XOIw9Q)

六、五分选手

1. [什么是树状数组？现在就带你研究](https://mp.weixin.qq.com/s/gLne35DARbLIAUTGLPZEAQ)

七、HHFCodeRv

1. [这一次，彻底搞懂 Go Cond](https://mp.weixin.qq.com/s/2NsAl5yEPxwbpyATpuEa3Q)

八、脑子进煎鱼了

1. [一个新细节，Go 1.17 将允许切片转换为数组指针！](https://mp.weixin.qq.com/s/v1czjzlUsaSQTpAOG9Ub3w)

九、Go招聘

1. [愿你我同在阳光下出行，Gophers Coming](https://mp.weixin.qq.com/s/CfXknlNVZbnqP5QHaANVuA)


## GOCN每日新闻--2021-04-25 
1.rpcx 支持 websocket 协议了! https://colobu.com/2021/04/11/support-websocket-in-rpcx/

2.Go 1.17 将允许将切片转换成数组指针 https://utcc.utoronto.ca/~cks/space/blog/programming/GoConvertSliceToArray

3.interface 的类型断言是如何实现 https://segmentfault.com/a/119000003989416

4.有趣的面试题：Go 语言中 nil 的比较结果 https://segmentfault.com/a/1190000039894167

5.Uber 基于 GPU 的开源实时分析引擎 aresdb https://github.com/uber/aresdb


## gopherDaily--2021-04-25
1.微抽象：Go的函数钩子 - https://world.hey.com/mat/tiny-abstractions-function-hooks-in-go-92924f11

2.Java真的比Go性能好吗？ - https://dabase.com/blog/2021/java-vs-go-load-test/

3.kubectl-cost: 展示k8s集群负载情况的kubectl插件工具 - https://github.com/kubecost/kubectl-cost

4.Go服务端渲染引擎与组件 - https://github.com/yuriizinets/go-ssc

5.经典旧文：使用Go从头实现容器 - https://medium.com/@ssttehrani/containers-from-scratch-with-golang-5276576f9909

6.Boyer-Moore高性能字符串搜索算法的go实现 - https://github.com/sarpdag/boyermoore

7.k8s的主主PostgreSQL联邦集群 - https://blog.crunchydata.com/blog/active-active-postgres-federation-on-kubernetes

8.cron表达式解析库 - https://github.com/adhocore/gronx

9.业余编译器编写者的资源 - https://c9x.me/compile/bib/

10.图形化展示Go应用module依赖的详细信息 - https://github.com/nikolaydubina/import-graph

11.管理单体应用与微服务的可靠性：SRE的最佳实践 - https://stackpulse.com/blog/monoliths-vs-microservices-best-practices/

12.我为什么要在2021年使用Go - https://medium.com/@mdcfrancis/why-do-i-write-golang-in-2021-3ab8f2fff31c




## GOCN每日新闻--2021-04-24 

1.Go 语言基础系列（八）：面向对象编程之接口 https://mp.weixin.qq.com/s/cJf660raLfQ4HmSijkD7RA

2.go 语言的 31 个坑 https://www.jianshu.com/p/311649bb2894

3.Go - 一个对新手很友好的项目 (带界面) https://juejin.cn/post/6954542723747708936

4.聊聊 dbsync 的 jobs https://juejin.cn/post/6954359234528018445

5.聊聊 dbsync 的 Schedulable https://juejin.cn/post/6953999719672578055


## gopherDaily--2021-04-24
1.Go正在为企业开发者提供动力：Go开发者调查的结果分析 - https://cloud.google.com/blog/topics/developers-practitioners/go-powering-enterprise-developers-developer-survey-results

2.关于Go与Elixir语言的思考 - https://preslav.me/2021/04/23/between-golang-and-elixir/

3.面向Go应用的统一存储层 - https://github.com/aos-dev/go-storage

4.Go 1.17支持将一个切片转换为一个数组指针 - https://utcc.utoronto.ca/~cks/space/blog/programming/GoConvertSliceToArray

5.minio更换license：由Apache2换为AGPL 3.0 - https://github.com/minio/minio/commit/069432566fcfac1f1053677cc925ddafd750730a

6.多语言gRPC性能测试结果，Go rpc实现随着cpu数量的增加而线性增加, cpu利用率也很线性 - https://github.com/LesnyRumcajs/grpc_bench/wiki/2021-04-13-bench-results

7.kubernetes将版本发布次数从一年四次改为一年发布三次 - https://groups.google.com/g/kubernetes-announce/c/is_pjOd5hho

8.高性能对象存储技术雷达 - https://gigaom.com/report/gigaom-radar-for-high-performance-object-storage/

9.Go goroutine worker池考量 - https://adtac.in/2021/04/23/note-on-worker-pools-in-go.html

10.油管视频：使用Fyne实现国际象棋游戏 - https://www.youtube.com/watch?v=zlPDWBLhn6c

11.Kubernetes Dashboard的桌面应用(非官方) - https://github.com/trntv/kubernetes-dashboard-desktop-app


## 码农桃花源--2021-04-24
### 优质文章汇总
1. [Go语言GC20问](https://mp.weixin.qq.com/s/o2oMMh0PF5ZSoYD0XOBY2Q)
2. [Go语言内存分配](https://mp.weixin.qq.com/s/Hm8egXrdFr5c4-v--VFOtg)
3. [tcp连接处于异常状态的一点总结](http://hopehook.com/blog/time_wait_close_wait)
4. [数据库19年1月月报](http://mysql.taobao.org/monthly/2019/01/01/)
5. [tcp hol blocking](https://mp.weixin.qq.com/s/KQV6yBvcd_gWDuVIFpJpcQ)

### 面试问题
1. 空 struct{} 的用途

2. 什么是协程泄露(Goroutine Leak)？

3. 无缓冲的 channel 和有缓冲的 channel 的区别？

4. 有了 GC，为什么还会发生内存泄露？

5. Go 语言中对 GC 的触发时机


6. 伪共享(false sharing)问题

7. cp和mv的区别，硬链接和软链接的区别

8. 页高速缓存的作用？怎样保证缓存一致性

9. zerocopy的实现机制

10. Mysql索引用的是什么算法

11. Mysql事务的基本要素

12. Mysql的存储引擎

13. 什么是聚簇索引？何时使用聚簇索引与非聚簇索引

14. 联合索引是什么？为什么需要注意联合索引中的顺序？

## go中文网每日资讯--2021-04-23 

一、Go语言中文网

1. [Go 语言如何实现垃圾回收中的 Stop the World (STW)](https://mp.weixin.qq.com/s/0yIlm79EKgIUlL3TW_rcVw)

2. [Go 数据结构和算法篇（十）：二分查找的变形版本](https://mp.weixin.qq.com/s/09ErIc5arIdqzFsWVHmqRw)

二、亚军进化史

1. [Go技术日报(2021-04-22)——大咖聊QUIC](https://mp.weixin.qq.com/s/iaXe1sTmoQ_5KO14QyjFIQ)

三、TechPaper

1. [事故驱动开发](https://mp.weixin.qq.com/s/I20sqkvLuWjVoPMaOZXjhw)

四、polarisxu

1. [世界读书日：分享我的 Go 语言书单](https://mp.weixin.qq.com/s/--Ea9Vz69JpRJBzFKxaxxQ)

五、Go夜读

1. [带你开始探究 Go iota](https://mp.weixin.qq.com/s/MwkeB-6OgoTw2JWFcu7bXA)

六、GolangContributorClub

1. [2021 中国 Go 语言开源贡献者峰会](https://mp.weixin.qq.com/s/-nzjufasWevwrWHf-2_iiA)

七、脑子进煎鱼了

1. [使用 Go defer 要小心这 2 个雷区！](https://mp.weixin.qq.com/s/ZEsWa4xUb0a7tWemVZMXVw)

八、Go招聘

1. [Go 在 AI 领域也火了？这招聘不错，薪资不低](https://mp.weixin.qq.com/s/ePqrEN40ch6NGShHRHPx2Q)
## GOCN每日新闻--2021-04-23 

1.Golang net/http 性能优化 https://gocn.vip/topics/11970

2.Go 中的并发 API 模式 https://marksalpeter.com/concurrent-api-patterns-in-go-52fcb5a9c681

3.Go 中的通道  https://juejin.cn/post/6953882304963936263

4.Go 中的并发 https://juejin.cn/post/6953632279085776903

5.为什么以及如何在 go 中写枚举 https://medium.com/qvault/how-and-why-to-write-enums-in-go-9c1a25649df0


## gopherDaily--2021-04-23
1.我是如何在3天内学完Go的 - https://dev.to/santiagova/how-i-learn-golang-in-3-days-3a1d

2.Kubernetes加入网关类API - https://kubernetes.io/blog/2021/04/22/evolving-kubernetes-networking-with-the-gateway-api/

3.使用go开发一个kong的插件 - https://konghq.com/blog/kong-gateway-go-plugin

4.播客：与《Network Programming with Go》的作者聊聊TCP&UDP - https://changelog.com/gotime/176

5.如何使用Go验证SSL证书 - https://www.freecodecamp.org/news/how-to-validate-ssl-certificates-in-go/

6.Kubernetes原生网关系列：扩展envoy - https://dzone.com/articles/the-kubernetes-native-gateway-series-part-1-envoy

7.在centos上搭建k8s集群 - https://dzone.com/articles/create-a-kubernetes-cluster-with-centos

8.Cron表达式的Go解析工具 - https://github.com/adhocore/gronx

9.Go项目的架构检查工具 - https://github.com/fdaines/arch-go

10.使用Terraform在linode上设置k8s集群 - https://learnk8s.io/terraform-lke

11.同时操作多个git仓库的工具 - https://github.com/gruntwork-io/git-xargs

## 码农桃花源--2021-04-23
### 文章分享
1. [tcp hol blocking](https://mp.weixin.qq.com/s/KQV6yBvcd_gWDuVIFpJpcQ)

2. [站长的书单](https://mp.weixin.qq.com/s/--Ea9Vz69JpRJBzFKxaxxQ)

3. [事故驱动开发]  https://mp.weixin.qq.com/s/I20sqkvLuWjVoPMaOZXjhw	

4. [数据库19年1月月报] http://mysql.taobao.org/monthly/2019/01/01/

### 面试题
1. 回答输出结果
```go
func main() {
    //len 2, cap 2
    s := []int{1,2}
    fmt.Printf("s append before len=%d, cap=%d \n",len(s),cap(s))
    s = append(s,4)
    fmt.Printf("s append 4 len=%d, cap=%d \n",len(s),cap(s))
    
    s = append(s,5)
    fmt.Printf("s append 5 len=%d, cap=%d \n",len(s),cap(s))
        
    s = append(s,6)
    fmt.Printf("s append 6 len=%d, cap=%d \n",len(s),cap(s))
    fmt.Println("====================")
    s1 := []int{1,2}
    fmt.Printf("s1 append before len=%d, cap=%d \n",len(s1),cap(s1))
    s1 = append(s1, 4,5,6)
    fmt.Printf("s1 append after  len=%d, cap=%d \n",len(s1),cap(s1))
}
```
2. 什么是聚簇索引？何时使用聚簇索引与非聚簇索引

3. 联合索引是什么？为什么需要注意联合索引中的顺序？

### 每日算法
反转字符串 写出最优解

## go中文网每日资讯--2021-04-22

一、Go语言中文网

1. [图文讲解：Go 中的循环是如何转为汇编的？](https://mp.weixin.qq.com/s/GRkXojUmoC4HuuR8wJ1Cjw)

2. [Go 数据结构和算法篇（九）：二分查找](https://mp.weixin.qq.com/s/Q8HhYaCURrnBAvN6-Rmyug)

二、亚军进化史

1. [GO技术日报(2021-04-21)——Go 异步抢占](https://mp.weixin.qq.com/s/gM5gU7GoJKcASRDCVcmKHw)

三、polarisxu

1. [用 Go 搭建一个自己的照片管理神器](https://mp.weixin.qq.com/s/7rFJKE14cTIIIKI9ahQ38g)

四、腾讯云CDN

1. [大咖聊QUIC——快手CDN架构师沈坤](https://mp.weixin.qq.com/s/YofN_SM-fAL9EgEc9zHQ5Q)

五、k8s技术圈

1. [Fluentd 简明教程](https://mp.weixin.qq.com/s/C9Nq1qI41rqsnfcCbArF1g)

2. [腾讯 PCG 中台容器开发 | 云原生招聘](https://mp.weixin.qq.com/s/qNsrBISMtGSqf3lHAsCbRQ)

六、Go招聘

1. [不加班还不够香？那见明星呢](https://mp.weixin.qq.com/s/UZ8XdmWK43TWFD1pnzSqww)

七、GolangCoutributorClub

1. [Go 语言源码贡献官方指导文档](https://mp.weixin.qq.com/s/dJ0t4owm3ChIljP4hL1e1Q)

## GOCN每日新闻--2021-04-22 

1.在 Go 中搜索和替换字符串的 5 个示例 https://dev.to/qvault/search-and-replace-strings-in-golang-top-5-examples-968

2.Go 项目架构检查 https://github.com/fdaines/arch-go

3.如何使用 Go 正确处理并发性和并行性 https://medium.com/analytics-vidhya/how-to-properly-handle-concurrency-and-parallelism-with-golang-89dd054b739f

4.Python 运行 Go 代码 https://rene-manqueros.medium.com/running-go-code-from-python-a65b3ae34a2d

5.Go 中使用位掩码 https://www.ardanlabs.com/blog/2021/04/using-bitmasks-in-go.html




## gopherDaily--2021-04-22
1.Go标准库http与fasthttp服务端性能比较 - https://t.zsxq.com/Rv7Y7Mj

2.使用webrtc实现的命令行语音通讯 - https://github.com/smf8/kenny

3.Go 1.17泛型语法样例集 - https://github.com/mattn/go-generics-example

4.Go并发API模式 - https://marksalpeter.com/concurrent-api-patterns-in-go-52fcb5a9c681

5.kubernetes node网络管理器 - https://github.com/kakao/network-node-manager

6.与Kubernetes共存：API生命周期 - https://thenewstack.io/living-with-kubernetes-api-lifecycles-and-you/

7.与Kubernetes共存：集群升级 - https://thenewstack.io/living-with-kubernetes-cluster-upgrades/

8.ROS与docker指南 - https://roboticseabass.wordpress.com/2021/04/21/docker-and-ros/

9.实时性能数据监控 - https://github.com/netdata/netdata

10.从头学git - https://jwiegley.github.io/git-from-the-bottom-up/

11.谷歌实现24/7无碳能源目标的新进展 - https://blog.google/outreach-initiatives/sustainability/new-progress-toward-our-247-carbon-free-energy-goal/

12.新兴边缘云和计算基础设施 - https://thenewstack.io/emerging-edge-cloud-and-computing-infrastructure/

13.油管视频：运行于windows subsystem for linux(WSL)的linux gui程序 - https://www.youtube.com/watch?v=f8_nvJzuaSU

## 码农桃花源--2021-04-2２
### 文章分享
1. [go Map-Reduce编程模式](https://github.com/robpike/filter/blob/master/reduce.go)
2. [分析Go程序的Off-CPU性能](https://colobu.com/2020/11/12/analyze-On-CPU-in-go/)
3. [web框架gin源码解读](https://gocn.vip/topics/9319)
4. [数据库19年1月月报](http://mysql.taobao.org/monthly/2019/01/01/)
### 面试题
1. Mysql索引用的是什么算法

2. Mysql事务的基本要素

3. Mysql的存储引擎

###每日算法

lc710  找到处理最多请求的服务器

## go中文网每日资讯--2021-04-21 

一、Go语言中文网

1. [代码会死循环吗？Go 异步抢占](https://mp.weixin.qq.com/s/NIYxzycAqHzeVSgU7ixhNg)

2. [Go 数据结构和算法篇（八）：快速排序](https://mp.weixin.qq.com/s/XpwVsmG-Fd85T9qE1gFsEw)

二、亚军进化史

1. [Go技术日报(2021-04-20)——Go程序员进化史](https://mp.weixin.qq.com/s/nKv0TEs7U68XWFaraVgpnA)

三、新亮笔记

1. [Go - 一个对新手很友好的项目(带界面)](https://mp.weixin.qq.com/s/UKBFgNcseLO6b-8eFsGHXg)

四、脑子进煎鱼了

1. [生产环境遇到一个 Go 问题，整组人都懵逼了...](https://mp.weixin.qq.com/s/F9II4xc4yimOCSTeKBDWqw)

五、k8s技术圈

1. [Logging Operator - 优雅的云原生日志管理方案 (一)](https://mp.weixin.qq.com/s/01t87UphWxB7XJT8Go4Vgg)

2. [Logging Operator - 优雅的云原生日志管理方案 (二)](https://mp.weixin.qq.com/s/4mcie165w-es7b8YWQVXcQ)

六、奇伢云存储

1. [存储基础 —— 磁盘 IO 为什么总叫你对齐？](https://mp.weixin.qq.com/s/rqq-GgZMMs5gj6p_VJqEVA)
 

## GOCN每日新闻--2021-04-21 

1.如何在 Go 中构建可配置的责任链 https://betterprogramming.pub/build-a-configurable-chain-of-responsibility-in-go-80a7cdcd1ab2

2.i/o timeout ， 希望你不要踩到这个 net/http 包的坑 https://mp.weixin.qq.com/s/UBiZp2Bfs7z1_mJ-JnOT1Q

3.嗯，你觉得 Go 在什么时候会抢占 P？ https://mp.weixin.qq.com/s/WAPogwLJ2BZvrquoKTQXzg

4.9 款最佳开源网络监控工具 https://www.metricfire.com/blog/9-best-open-source-network-monitoring-tools

5.简单的边缘代理服务器 https://github.com/umputun/reproxy


## gopherDaily--2021-04-21

1.编写好的单元测试：不要mock数据库连接 - https://qvault.io/clean-code/writing-good-unit-tests-dont-mock-database-connections/

2.纯Go实现的浏览器和浏览器引擎 - https://github.com/danfragoso/thdwb

3.Goldmark markdown解析器的pdf渲染工具 - https://github.com/stephenafamo/goldmark-pdf

4.应用授权构建教程 - https://www.osohq.com/developers/authorization-academy

5.学习Go之前你应该知道的10件事 - https://bitfieldconsulting.com/golang/how

6.基于kratos微服务框架的电商应用demo - https://github.com/go-kratos/beer-shop

7.Rob Pike提议Go增加简化创建简单类型的指针的语法 - https://github.com/golang/go/issues/45624

8.飞书非官方Go SDK - https://github.com/go-lark/lark

9.vcluster：在k8s集群中创建虚拟k8s集群 - https://github.com/loft-sh/vcluster

10.grafana将开源许可证改为AGPLv3 - https://grafana.com/blog/2021/04/20/grafana-loki-tempo-relicensing-to-agplv3/

11.NASA下一代月球车将运行大量开源软件 - https://www.technologyreview.com/2021/04/12/1022420/nasa-lunar-rover-viper-open-source-software/


## 码农桃花源--2021-04-21
### 文章分享
1. [tcp连接处于异常状态的一点总结](http://hopehook.com/blog/time_wait_close_wait)

2. [linux内核是如何巧妙的初始化各个模块的](https://mp.weixin.qq.com/s/qdBsv3vK-Suczt7gEmI6Dw)

3. [为了变得更快，CPU，内存，IO做了哪些努力](https://mp.weixin.qq.com/s/P-mPAWxScFAThoNF3M2y3A)

### 面试题
1. cp和mv的区别，硬链接和软链接的区别

2. 页高速缓存的作用？怎样保证缓存一致性

3. zerocopy的实现机制

### 每日算法
lc815 公交路线 https://leetcode-cn.com/problems/bus-routes/

## go中文网每日资讯--2021-04-20 


一、Go语言中文网

1. [Go 中使用别名，简单且高效](https://mp.weixin.qq.com/s/xiSD2cmDC50qncqNL-7fEQ)

2. [Go 数据结构和算法篇（七）：归并排序](https://mp.weixin.qq.com/s/kTLhl3hvbs-R_RR3VX0Xhw)

二、亚军进化史

1. [Go技术日报(2021-04-19)——深度阅读之《Mastering Go》](https://mp.weixin.qq.com/s/FTDS8eX_vUHrl67ZBHSsIQ)

三、Go招聘

1. [广告公司真香，不加班美女还多，文末有彩蛋哦](https://mp.weixin.qq.com/s/QXt72JsZgxl19AyvdHeKcg)

四、薯条的自我修养

1. [Go程序员进化史](https://mp.weixin.qq.com/s/FsTmsNBN7nM3vl5w6R1vJA)

五、CloudNativeCommunity

1. [云原生社区 meetup 第三期杭州站回顾及幻灯片下载](https://mp.weixin.qq.com/s/Ad3TMXmUV9ka7cA-M7zJnA)

六、k8s技术圈

1. [99.99%面试中被问的Go语言并发模式，你会如何回答 | 文末送书](https://mp.weixin.qq.com/s/q5AmA6JANvaTYuQ8Hx-kPQ)

2. [开源持续性能剖析平台 Pyroscope](https://mp.weixin.qq.com/s/g5obUptQQwsBcJLLC7e4mg)

七、云加社区

1. [Redis 进阶笔记](https://mp.weixin.qq.com/s/o66KCbJUj4RsgXFjXzLzoQ)

八、polarisxu

1. [我又来推荐免费 Go 新书了：一本用 Go 讲架构的书](https://mp.weixin.qq.com/s/UqTvfvwhIHARnClCJftjMg)



## GOCN每日新闻--2021-04-20

1.TiDB 深度解读 Chaos Mesh https://gocn.vip/topics/11945

2.Go 语言控制 CPU 占用率呈正弦曲线 https://juejin.cn/post/6953034008351473678

3.如何在 Go 中优雅使用 packages https://jonathanseow.medium.com/working-with-packages-in-golang-5f247f49090f

4.理解 NSQ consumer https://eriyantovetanusi.medium.com/nsq-consumer-101-b815267b5fec

5.Triangula: 基于遗传算法的低多边形效果工具 https://github.com/RH12503/Triangula





## gopherDaily--2021-04-20
1.使用reflect包在反射世界里读写各类型变量 - https://mp.weixin.qq.com/s/KgUZGVF08yEO2oARryOLcg

2.使用go embed在go中嵌入函数式编程引擎 - https://programmingfunl.wordpress.com/2021/04/19/using-funl-as-functional-core-embedded-in-go/

3.go embed简明教程 - https://colobu.com/2021/01/17/go-embed-tutorial/

4.尾部延迟可能比您想象的更重要 - https://brooker.co.za/blog/2021/04/19/latency.html

5.分布式sql速查表，兼容PostgreSQL - https://blog.yugabyte.com/a-postgresql-compatible-distributed-sql-cheat-sheet-the-basics

6.软件基础架构 2.0： 心愿单 - https://erikbern.com/2021/04/19/software-infrastructure-2.0-a-wishlist.html

7.炫酷的比特币3D图形化查看工具 - https://symphony.iohk.io/en/

8.高性能易用的网络扫描工具 - https://github.com/v-byte-cpu/sx

9.制作可配置的Go应用 - https://www.hildeberto.com/2021/04/configurable-go-app.html

10.谈谈 Kubernetes 的问题和局限性 - https://mp.weixin.qq.com/s/ULfmxZh2PBYK-298Xskf2Q

11.开源产品登陆火星 - https://github.blog/2021-04-19-open-source-goes-to-mars/


## 码农桃花源--2021-04-20
### 文章分享
1. [内存的读写指令重排] https://cch123.github.io/ooo/

2. [Go语言内存分配] https://mp.weixin.qq.com/s/Hm8egXrdFr5c4-v--VFOtg

3. [HugePages为什么能提高数据库性能] https://draveness.me/whys-the-design-linux-hugepages
### 面试题
1. 有了 GC，为什么还会发生内存泄露？

2. Go 语言中对 GC 的触发时机

3. 伪共享(false sharing)问题

### 每日算法
粉刷房子 https://leetcode-cn.com/problems/paint-house-iii/



## go中文网每日资讯--2021-04-19

一、Go语言中文网

1. [转 Go 的 PHPer 总是忘不了 PHP 的好？试试这个开源项目](https://mp.weixin.qq.com/s/o5wHJg8SlylaGJ_YPWu0hg)

2. [Go 数据结构和算法篇（六）：选择排序](https://mp.weixin.qq.com/s/Paqrb2ywjyciwEzfo1VefQ)

二、亚军进化史

1. [Go技术日报(2021-04-18)——高性能 Go 代码工坊（Part5)](https://mp.weixin.qq.com/s/xd0lCPnSvvN9wMOM8K577g)

三、polarisxu

1. [Rust 劝退系列 03：变量](https://mp.weixin.qq.com/s/VheT027N71946GyoT3BxTw)

四、图解源码

1. [统一运维平台的思考](https://mp.weixin.qq.com/s/mLnqR2kwGNiFLL39g-Ml8Q)

五、微服务实践

1. [一文带你更方便的控制 goroutine](https://mp.weixin.qq.com/s/FBo2Ghpb5rBETJP0tFVaXg)

六、码农桃花源

1. [深度阅读之《Mastering Go》](https://mp.weixin.qq.com/s/3JnJskE_bK6AeUSeQThhfg)

七、脑子进煎鱼了

1. [嗯，你觉得 Go 在什么时候会抢占 P？](https://mp.weixin.qq.com/s/WAPogwLJ2BZvrquoKTQXzg)

八、k8s技术圈

1. [揭秘高性能Linux服务器内存池技术是如何实现的](https://mp.weixin.qq.com/s/AkABAitHI_BBlH4AP_2fIQ)

九、远赴星辰

1. [虚拟内存精粹](https://mp.weixin.qq.com/s/Ghu-0Qc9PyEHHmIaRVtMyA)

十、luozhiyun很酷

1. [从栈上理解 Go 语言函数调用](https://mp.weixin.qq.com/s/-xn2i2depcN4uWT3wV63Pw)

十一、Go招聘

1. [我靠！Gopher推荐成功居然给0.5个BTC](https://mp.weixin.qq.com/s/iQpVTT378kHDX9xgIxT7rA)



## GOCN每日新闻--2021-04-19
1.hash 表在 go 语言中的实现 https://gocn.vip/topics/11937

2.Go 语言内部包 -- 控制包成员的对外暴露 https://mp.weixin.qq.com/s/XNiP6EpJGEJGVb55ZpI9oQ

3.gRPC 的平滑关闭和在 Kubernetes 上的服务摘流方案总结 https://mp.weixin.qq.com/s/lCTyZgSK3b-rJtV9l6PNYA

4.Golang 语言中基础同步原语 Mutex 和 RWMutex 的区别 https://mp.weixin.qq.com/s/nU-WFszIP1Sk1rC4q5cI1A

5.Go 语言中切片操作的那些技巧 https://mp.weixin.qq.com/s/ElZUEgi-tiU63D4AFw9XMg



## gopherDaily--2021-04-19

1.油管视频：一小时学习Go - https://www.youtube.com/watch?v=N0fIANJkwic

2.谈谈go与gRPC的组合 - https://levelup.gitconnected.com/an-up-to-date-review-of-grpc-with-golang-b8cc78b584f7

3.开发人员是如何在编码过程中进行命名的 - https://arxiv.org/pdf/2103.07487.pdf

4.播客：开源但不开放贡献 - https://changelog.com/podcast/433

5.Go: 快速构建应用的完美方案 - https://sagarjiyani3010.medium.com/googles-golang-the-perfect-solution-to-super-fast-building-5ed4de6caa95

6.经典旧文：uber的go编程规范 - https://github.com/uber-go/guide/blob/master/style.md

7.使用Go Ebiten库实现的Windows画图程序 - https://shores.dev/paint-game-in-golang/

8.有用的go模板函数 - https://github.com/Masterminds/sprig

9.如何赢得任何机器学习比赛 - https://medium.com/machine-learning-insights/how-to-win-any-ml-contest-244a12c62f30

10.企业PaaS在企业架构中的角色 - https://thenewstack.io/the-role-of-eipaas-in-enterprise-architecture-part-1/

11.微软rust入门教程 - https://docs.microsoft.com/zh-cn/learn/paths/rust-first-steps/


## 码农桃花源--2021-04-19
### 文章分享
1. [设计模式在外卖营销业务中的实践](https://tech.meituan.com/2020/03/19/design-pattern-practice-in-marketing.html)

2. [Go语言GC20问](https://mp.weixin.qq.com/s/o2oMMh0PF5ZSoYD0XOBY2Q)

3. [Go协作与抢占](https://mp.weixin.qq.com/s/nib0OD-LvNG57JAs4vB9RA)

### 面试题
1. 空 struct{} 的用途

2. 什么是协程泄露(Goroutine Leak)？

3. 无缓冲的 channel 和有缓冲的 channel 的区别？

### 每日算法
lc1792 最大平均通过率 https://leetcode-cn.com/problems/maximum-average-pass-ratio/


## go中文网每日资讯--2021-04-18 

一、Go语言中文网

1. [GoLand 2021.1 重磅发布：新特性不少，有些不错](https://mp.weixin.qq.com/s/0NjNNLAdZZjx8GPZXR1MjQ)

2. [Go语言爱好者周刊：第 91 期 — Error 和 String 的题目](https://mp.weixin.qq.com/s/tJXF0JD6Dwm66Kl7xUCrRg)

3. [Go 数据结构和算法篇（五）：插入排序](https://mp.weixin.qq.com/s/UV1oelB_h5zx20KCWD-Feg)

二、亚军进化史

1. [Go技术日报(2021-04-17)——切片操作的那些技巧](https://mp.weixin.qq.com/s/ZwlP-wLcStj1NBdAm16LGQ)

三、k8s技术圈

1. [多行日志收集管理搞不定？](https://mp.weixin.qq.com/s/yY6I2vhIn_jziuY4W4GBng)

2. [精选中的精选 Github 项目](https://mp.weixin.qq.com/s/IdmBJCEQ6vm3Gqij2FhNeg)

四、董泽润的技术笔记

1. [时钟源为什么会影响性能](https://mp.weixin.qq.com/s/06SDQLzDprJf2AEaDnX-QQ)

五、GoOfficialBlog

1. [高性能 Go 代码工坊（Part5)](https://mp.weixin.qq.com/s/vn9KPDi2GWC1MzVSIw8xQg)

六、吴亲强的深夜食堂

1. [etcd 实战基础篇(二)](https://mp.weixin.qq.com/s/VCIPmAD5YSWz0DAuFqfwyg)

七、Go招聘

1. [4/12-4/18股文请接收](https://mp.weixin.qq.com/s/NY7wIkLOQiSceGG2m3Lf6w)

八、Golang Weekly

1. [Golang Weekly Issue 358: April 16, 2021](https://golangweekly.com/issues/358)

2. [Awesome Go Newsletter - Issue 256, Apr 15, 2021 | LibHunt](https://go.libhunt.com/newsletter/256)
## GOCN每日新闻--2021-04-18

1.Go 测试的考验与困难 https://changelog.com/gotime/174

2.教你自定义 Go 代码静态分析工具 https://developer20.com/custom-go-linter/

3.Go 简洁架构示例 https://github.com/bxcodec/go-clean-arch

4.支持多种协议的转发代理工具 glider https://github.com/nadoo/glider

5.Go 设计模式之策略模式 https://triumph-job.medium.com/strategy-design-pattern-in-golang-722e1b145c5f



## gopherDaily--2021-04-18 
- 1.开发开源数据库的7年经验教训 - https://www.philipotoole.com/7-years-of-open-source-database-development-lessons-learned/
- 2.Russ Cox指明“Go二进制文件变得越来越大”文章中信息有误 - https://news.ycombinator.com/item?id=26834128
- 3.gitleaks: 扫描git仓库（或文件）中的敏感信息  - https://github.com/zricethezav/gitleaks
- 4.Go中实现RSA加密和签名 - https://www.sohamkamani.com/golang/rsa-encryption/
- 5.Go基于寄存器的ABI规范的改造基本完工，平均性能提升6% - https://github.com/golang/go/issues/40724#issuecomment-821758073
- 6.Rancher, Red Hat OpenShift和 Weave Kubernetes 比较 - https://www.weave.works/a-comparison-of-rancher-red-hat-openshift-and-wkp/
- 7.Go系统字体操作包 - https://github.com/go-swiss/fonts
- 8.使用go实现一个反向代理 - https://developer20.com/writing-proxy-in-go/
- 9.处于边缘的容器：它不是你想的那样 - https://blog.cloudflare.com/containers-on-the-edge/
- 10.git和gitflow实践指南 - https://www.freecodecamp.org/news/practical-git-and-git-workflows/
- 11.为何我们使用kanban而不是scrum - https://www.cloudzero.com/blog/why-cloudzero-uses-kanban
- 12.为什么我们使用时序数据库提升安全监控能力 - https://thenewstack.io/why-using-a-time-series-database-improves-security-monitoring/


## go中文网每日资讯--2021-04-17 

一、Go语言中文网

1. [用 Golang 实现 RSA 加密和签名（有示例）](https://mp.weixin.qq.com/s/w976zzchogZy8xkWGN--Ww)

2. [Go语言中切片操作的那些技巧](https://mp.weixin.qq.com/s/ElZUEgi-tiU63D4AFw9XMg)

二、亚军进化史

1. [Go技术日报(2021-04-16)——go scheduler 超级总结](https://mp.weixin.qq.com/s/xLDF4MY54qglO1SksMxAfw)

三、图解源码

1. [以应用为中心的云原生2.0白皮书学习笔记](https://mp.weixin.qq.com/s/9qUedU_6oDXpzAgWR07sMw)

四、网管叨bi叨

1. [Golang atomic.Value 的前世今生](https://mp.weixin.qq.com/s/UrLCyT7GTNJLi37sJU2PTg)

五、腾讯云原生

1. [如何使用 OpenTracing 在 TCM 中实现异步消息调用跟踪](https://mp.weixin.qq.com/s/_541vL4nHIXPx_ZKrx362g)
## GOCN每日新闻--2021-04-17

1.Golang 实现的 iOS 设备通信工具 https://github.com/electricbubble/gidevice

2.在 Go 共享对象下的 python 更快 https://blog.kchung.co/faster-python-with-go-shared-objects/

3.什么是 “同步条件” https://dtyler.io/articles/2021/04/13/sync_cond/

4.Encore 用于构建分布式系统的 Go 框架 https://github.com/encoredev/encore

5.Go 中的 URL 解码 https://gosamples.dev/url-decode/

## gopherDaily--2021-04-17 
- 1.使用go和netrasp管理网络设备 - https://networklore.com/hello-netrasp/
- 2.email-verifier: 可上生产环境的邮箱地址校验器 - https://github.com/AfterShip/email-verifier
- 3.分布式应用运行时Dapr是如何在阿里落地的 - https://mp.weixin.qq.com/s/Dsb7rwu5tRAizJ7Wdr23Fw
- 4.go播客：聊聊Go应用的发布  - https://changelog.com/gotime/173
- 5.Go应用程序漏洞分析 - https://developers.redhat.com/blog/2021/04/15/vulnerability-analysis-for-golang-applications-with-red-hat-codeready-dependency-analytics/
- 6.解读如何仅用1台服务器支持百万DAU - https://mp.weixin.qq.com/s/wv19bUZW4U6wjw5DmCg3Yg
- 7.网络信息收集工具 - https://github.com/edoardottt/scilla
- 8.使用Terraform部署k8s系列 - https://blog.kasten.io/concepts-behind-terraform-and-kubernetes
- 9.wasi: 让webassembly走出浏览器 - https://training.linuxfoundation.org/announcements/wasi-bringing-webassembly-way-beyond-browsers
- 10.在生产环境部署机器学习模型 - https://www.kdnuggets.com/2019/06/approaches-deploying-machine-learning-production.html
- 11.ftp 50岁了！ - https://www.filestash.app/2021/04/16/ftp-is-50-years-old/
- 12.为什么linkerd没有使用envoy - https://www.cncf.io/blog/2020/12/11/why-linkerd-doesnt-use-envoy/
- 13.linus对rust编写内核代码的回复 - https://lkml.org/lkml/2021/4/14/1099
- 14.使用react和tailwind css实现的ubuntu桌面 - https://vivek9patel.github.io/


## go中文网每日资讯--2021-04-16

一、Go语言中文网

1. [大佬的思路很清晰：Go+的设计原来是怎么思考的](https://mp.weixin.qq.com/s/at8L7bM64OmMK9qSAROqsQ)

2. [gopher们都想有个好未来？那就来这吧](https://mp.weixin.qq.com/s/H3uksQ0i4cKfYA24bcIHsw)

3. [Go 数据结构和算法篇（四）：冒泡排序](https://mp.weixin.qq.com/s/NPlesVsgptB7acPfli5vcg)

二、亚军进化史

1. [Go技术日报(2021-04-15)——大型生产系统的问题定位](https://mp.weixin.qq.com/s/2M5QWcffuK3PMPzsCPB47Q)

三、k8s技术圈

1. [Grafana 图表加速神器 - Trickster](https://mp.weixin.qq.com/s/TamLSfT4dVReqBt2_2YTvA)

四、polarisxu

1. [注释竟然还有特殊用途？一文解惑 //go:linkname 指令](https://mp.weixin.qq.com/s/4OlbpQwchWwxnQmSOL6xYA)

五、奇伢云存储

1. [读者问答：Go 编程怎么也有踩内存？](https://mp.weixin.qq.com/s/BJJ9jDUT7oB-B0o_dNmNvQ)

六、Go招聘

1. [当下最流行的全职开源，你不心动吗？](https://mp.weixin.qq.com/s/Tuf4tPRrCJ48Ml5Y6uCXBg)


## gopherDaily--2021-04-16

1.如何使用ArgoCD根据GitOps原则管理OpenFaaS功能 - https://www.openfaas.com/blog/bring-gitops-to-your-openfaas-functions-with-argocd/

2.k8s集群上分布式应用的leader选举 - https://carlosbecker.dev/posts/k8s-leader-election

3.分布式、自托管的云游戏服务平台 - https://github.com/giongto35/cloud-morph

4.Go URL解码 - https://gosamples.dev/url-decode/

5.播客：Gophercon提案的终极指南 - https://changelog.com/gotime/175

6.k8s存储插件rook发布1.6版本 - https://blog.rook.io/rook-v1-6-storage-enhancements-2d5144c21b6a

7.支持苹果M1的docker desktop发布 - https://www.docker.com/press-release/Docker-Desktop-for-M1-powered-Macs

8.开源电子书: 用Go构建现代商业软件 - https://threedots.tech/go-with-the-domain/

9.工程师的职业阶梯 - https://career-ladders.dev/engineering

10.Go与jwt的安全集成 - https://dev.to/abrichak/jwt-and-go-how-to-integrate-them-with-security-requirements-eh5

11.使用Go编写Kubernetes Admission Controller - https://dev.to/fdns/writing-a-kubernetes-admission-controller-4eko

12.linux kernel对rust的支持情况 - https://security.googleblog.com/2021/04/rust-in-linux-kernel.html


## 码农桃花源--2021-04-1６
### 文章分享
1. [go struct](https://mp.weixin.qq.com/s/K5B2ItkzOb4eCFLxZI5Wvw)

2. [作为曹大粉丝，饶大能做到什么地步](https://mp.weixin.qq.com/s/g5AZxFOS9kwnAPmb3e3OUQ)

3. [go scheduler 超级总结](https://www.yuque.com/wuguoguoya/iq0d3v/wurlky)
###　面试题
1. Go中对nil的Slice和空Slice的处理是一致的吗

2. Go语言的栈空间管理是怎么样的

3. 怎么限制Goroutine的数量
### 每日算法
lc710  不含连续1的非负整数


## go中文网每日资讯--2021-04-15


一、Go语言中文网

1. [Goroutine 开启和退出到底做了什么？](https://mp.weixin.qq.com/s/_ngJ6QfZRK5sGTA-CfsORg)

2. [Go 数据结构和算法篇（三）：队列](https://mp.weixin.qq.com/s/fI_cY7vnMsMTW6q32fuulQ)

二、亚军进化史

1. [Go技术日报(2021-04-14)——Go+的设计原来是怎么思考的](https://mp.weixin.qq.com/s/JZfnnyPUQyhI0lMKMw8IpQ)

三、奇伢云存储

1. [推荐几个优秀的技术分享者，和他们在一起你也会优秀](https://mp.weixin.qq.com/s/jlYoDiFiMHgxgiR5XCcELw)

四、k8s技术圈

1. [Prometheus Operator 对接 Thanos](https://mp.weixin.qq.com/s/E614onyF2acjrke7vYUKMw)

2. [阿里云SLS研发-可观察性方向 | 云原生招聘](https://mp.weixin.qq.com/s/nIbr7nd0uP8yZ0Fo381oVQ)

五、脑子进煎鱼了

1. [用 Go struct 不能犯的一个低级错误！](https://mp.weixin.qq.com/s/K5B2ItkzOb4eCFLxZI5Wvw)

六、TechPaper

1. [大型生产系统的问题定位](https://mp.weixin.qq.com/s/QtHEUzSdRBZpB0Yw3FtTiw)


## GOCN每日新闻--2021-04-15
1.Go 性能传说 http://jmoiron.net/blog/go-performance-tales

2.通过 Go 揭开 pprof 神秘面纱 https://www.polarsignals.com/blog/posts/2021/04/13/demystifying-pprof-labels-with-go/

3.通过 Go 共享对象加速 Python 程序 https://blog.kchung.co/faster-python-with-go-shared-objects/

4.gotuna: 渐进式 Web 开发框架 https://github.com/gotuna/gotuna

5.mugo: Go 子集玩具编译器并实现自我编译 https://benhoyt.com/writings/mugo/

## 码农桃花源--2021-04-15
### 文章分享
1. [活文档](https://mp.weixin.qq.com/s/Tkc_eisDB3SFwWLaWktB2Q)

2. [go scheduler 主动调度](https://mp.weixin.qq.com/s/zA7KY_25NGjip9pP38RIvg)

3. [go scheduler 抢占调度](https://mp.weixin.qq.com/s/i8DQ0HrO5Bt-qE5cX7c1ng)

4. [系统调用执行时间过长的goroutine](https://mp.weixin.qq.com/s/If0-35Pt8dN7G1gD4L9-hw)


### 面试题
至此一个go scheduler 系列学习完成，你是否有跟我一起学习呢，今天明天我们总结复习一下所有跟scheduler有关的问题，下周开始新篇章

• 为什么需要 P 这个组件，直接把 runqueues 放到 M 不行吗？

• gpm到底是什么

• scheduler是如何调度的

• 什么时候会触发调度

• 当在M上运行的goroutine发生阻塞时，会怎么工作

• 为什么每个P都会对应一个g0，m0 (g0是用于调度每个线程中的goroutine，包括gc等等，拥有比较大的栈内存)

• 什么时候会抢占P

• 调度的本质

• 多个线程与多个M如何一一对应？

• 为什么要把工作线程与m对应

• 为什么在创建goroutine的newproc函数要传入参数大小

• 什么时候调用的main函数？

• g0到main goroutine的转换过程

• 非main goroutine是如何返回到goexit函数的；

• mcall函数如何从用户goroutine切换到g0继续执行

• 调度循环

• 使用什么策略来挑选下一个进入运行的goroutine

• 如何把挑选出来的goroutine放到CPU上运行

• schdule的三种调度方式
### 每日算法
lc710  黑名单中的随机数

## gopherDaily--2021-04-15
- 1.给expvarmon插上数据持久化的“翅膀” - https://tonybai.com/2021/04/14/expvarmon-save-and-convert-to-xlsx
- 2.Dapr | 云原生的抽象与实现 - https://mp.weixin.qq.com/s/4HHMVxa3l_gCsltoX4euyg
- 3.Go panic惯用法 - https://stonecode.ca/idiomatic-panics/
- 4.Go实现Couchbase原子计数器 - https://towardsdev.com/atomic-couchbase-counters-golang-817df91c41dc
- 5.为什么Go可执行文件仍在变得越来越大(2021版) - https://dr-knz.net/go-executable-size-visualization-with-d3-2021.html
- 6.经典演讲：设计原型 - by Robert Griesemer - https://www.youtube.com/watch?v=vLxX3yZmw5Q
- 7.docker cli增加compose子命令 - https://docs.docker.com/compose/cli-command/
- 8.使用ebpf扩展systemd安全特性 - https://kinvolk.io/blog/2021/04/extending-systemd-security-features-with-ebpf/
- 9.pingme: 可向多个消息平台和电子邮件发送消息或警报的cli工具 - https://github.com/kha7iq/pingme
- 10.为azure k8s定制core dump策略 - https://blog.nillsf.com/index.php/2020/12/06/customize-core-dump-in-azure-kubernetes/





## go中文网每日资讯--2021-04-14

一、Go语言中文网

1. [又一个 Go 新书出版，送送送](https://mp.weixin.qq.com/s/QBFAwIwYMEJJMloW_yjsBw)

2. [Go 数据结构和算法篇（二）：栈](https://mp.weixin.qq.com/s/Q2Ev1C4P825_9fvUOo2b3A)

二、亚军进化史

1. [Go技术日报(2021-04-13)——flag包的“小陷阱”](https://mp.weixin.qq.com/s/3ItWZFugW_AwZhRGAM0wRQ)

三、polarisxu

1. [大佬的思路很清晰：Go+的设计原来是怎么思考的](https://mp.weixin.qq.com/s/AuJv6wnMbo2iryXvopAFag)

四、TechPaper

1. [从代码自动生成文档](https://mp.weixin.qq.com/s/zM5wX4oPB3XKicZfKCCYhw)

五、腾讯云原生

1. [Dapr | 云原生的抽象与实现](https://mp.weixin.qq.com/s/4HHMVxa3l_gCsltoX4euyg)

六、HHFCodeRv

1. [看过这篇剖析，你还不懂 Go sync.Map 吗？](https://mp.weixin.qq.com/s/kblDTqKlUaTITIppigq9yA)

七、TechPaper

1. [从代码自动生成文档](https://mp.weixin.qq.com/s/zM5wX4oPB3XKicZfKCCYhw)

八、Go招聘

1. [没错，可以全职参与开源语言开发：国人开发的语言 Go+ 团队招人](https://mp.weixin.qq.com/s/9xlQsW5X57fBYLRkwOELxA)


## gopherDaily--2021-04-14

1.谷歌SRE工程团队如何使用Go - https://go.dev/solutions/google/sitereliability

2.用Go解开Pprof标签的神秘面纱 - https://www.polarsignals.com/blog/posts/2021/04/13/demystifying-pprof-labels-with-go/

3.在python中使用go共享库 - https://blog.kchung.co/faster-python-with-go-shared-objects/

4.使用curl探索k8s - https://blog.tilt.dev/2021/03/18/kubernetes-is-so-simple.html

5.使用bash手撸一份k8s cni插件 - https://www.altoros.com/blog/kubernetes-networking-writing-your-own-simple-cni-plug-in-with-bash/

6.经典旧文：Go性能的那些事 - http://jmoiron.net/blog/go-performance-tales

7.分分钟学习Go - https://learnxinyminutes.com/docs/go/

8.inspr: 用于简单、快速和安全地开发分布式应用程序的应用网格(app mesh) - https://github.com/inspr/inspr

9.类unix系统标准密码管理工具 - https://www.passwordstore.org/

10.深入理解CORS：历史、工作原理和最佳实践 - https://ieftimov.com/post/deep-dive-cors-history-how-it-works-best-practices/


## 码农桃花源--2021-04-14
### 文章分享
1. [mysql分库分表及高可用集群经验——下](http://xiaorui.cc/archives/3923)

2. [go内置数据结构原理](https://zhuanlan.zhihu.com/p/341945051)

3. [Git内部原理揭秘](https://mp.weixin.qq.com/s/UQKrAR3zsdTRz8nFiLk2uQ)

### 面试题
1. 三次握手详细过程？SYN攻击底层原理是什么？

2. 四次挥手TIME_WAIT状态作用？为什么是2MSL？MSL和TTL什么关系？

3. innoDB底层索引和行锁、表锁的关系

### 每日算法

最小跳跃次数 https://leetcode-cn.com/problems/zui-xiao-tiao-yue-ci-shu/
 
## go中文网每日资讯--2021-04-13

一、Go语言中文网

1. [把 Go 当脚本语言用](https://mp.weixin.qq.com/s/7Svvbh1BRPkmlpZLpWP8FQ)

2. [深度剖析 Go 的 nil](https://mp.weixin.qq.com/s/GP74nN6ptAwpvwq3BSZxaA)

二、亚军进化史

1. [Go技术日报(2021-04-12)—— Channel 底层实现](https://mp.weixin.qq.com/s/quk0wabAxZpza8F4ytgb6w)

三、真没什么逻辑

1. [CPU 和 GPU - 异构计算的演进与发展](https://mp.weixin.qq.com/s/xVJ_M_2aDxN90lCY9KpSFw)

四、polarisxu

1. [一道 Go 闭包题，面试官说原来自己答错了：面别人也涨知识](https://mp.weixin.qq.com/s/gfyW0pBIHsf2oYluQNbP8A)

五、云原生技术爱好者社区

1. [SRE最佳实践](https://mp.weixin.qq.com/s/OVToFabSR5kHwQjBEmDafQ)

六、Go招聘

1. [Go远程工作越来越多了，真羡慕](https://mp.weixin.qq.com/s/weIMgKlFinQvaqpHKXYi1g)

七、李文周

1. [Go语言中切片操作的那些技巧](https://mp.weixin.qq.com/s/362m-GsKqLmrh5kbHp4Maw)

八、脑子进煎鱼了

1. [详解 Go 程序的启动流程，你知道 g0，m0 是什么吗？](https://mp.weixin.qq.com/s/YK-TD3bZGEgqC0j-8U6VkQ)

九、分布式实验室

1. [etcd分布式锁内存泄露](https://mp.weixin.qq.com/s/tAc-f5_b9MDBJJri7SqA6w)




 
## GOCN每日新闻--2021-04-13
1.Gopher China 2021 开启报名 https://gopherchina.org/

2.MixGo v1.1 Go 快速开发标准工具 https://www.oschina.net/news/137106/mixgo-1-1-released

3.深入 Go 并发原语 — Channel 底层实现 https://mp.weixin.qq.com/s/VyLyhtJCcLwpwhUpSCqJZA

4.高性能 Go 代码工坊（Part4) https://mp.weixin.qq.com/s/HEE_9gq11fY8uwqFvrNFYw

5.Go 语言内部包 -- 控制包成员的对外暴露 https://mp.weixin.qq.com/s/XNiP6EpJGEJGVb55ZpI9oQ

## gopherDaily--2021-04-13
1.深入 Go 并发原语 — Channel 底层实现 - https://github.com/halfrost/Halfrost-Field/blob/master/contents/Go/go_channel.md

2.Go标准库flag包的“小陷阱” - https://mp.weixin.qq.com/s/5ZrZ35ycwtJE2if6rs9dEQ

3.Go实现的可编译Go语法子集的玩具编译器 - https://benhoyt.com/writings/mugo/

4.encore: 快速创建API和分布式系统的 Go 后端框架，使用静态分析和代码生成来减少您必须编写的样板 - https://github.com/encoredev/encore

5.Go标准库sync.Cond详解 - https://dtyler.io/articles/2021/04/13/sync_cond/

6.Go git代码托管工具gitea 1.14发布 - https://blog.gitea.io/2021/04/gitea-1.14.0-is-released/

7.k3s上使用traefik实现ingress - https://itnext.io/ingress-with-treafik-on-k3s-53db6e751ed3

8.从”战争游戏”到网络策略 - https://cilium.io/blog/2021/04/06/war-games-network-policy

9.Go语言国际化的简便路径 - https://dev.to/koddr/an-easy-way-to-translate-your-golang-application-5ege

10.weaviate: 云原生、模块化、实时矢量搜索引擎 - https://github.com/semi-technologies/weaviate

11.aws开源opensearch，基于对elasticsearch和kibana的fork - https://aws.amazon.com/cn/blogs/opensource/introducing-opensearch/


## 码农桃花源--2021-04-13
### 文章分享
1. [mysql分库分表及高可用集群经验——下](http://xiaorui.cc/archives/3923)

2. [go内置数据结构原理] https://zhuanlan.zhihu.com/p/341945051

3. [Git内部原理揭秘](https://mp.weixin.qq.com/s/UQKrAR3zsdTRz8nFiLk2uQ)
### 面试题
1. 三次握手详细过程？SYN攻击底层原理是什么？

2. 四次挥手TIME_WAIT状态作用？为什么是2MSL？MSL和TTL什么关系？

3. innoDB底层索引和行锁、表锁的关系
### 每日算法
最小跳跃次数 https://leetcode-cn.com/problems/zui-xiao-tiao-yue-ci-shu/

## go中文网每日资讯--2021-04-12 

一、Go语言中文网

1. [极速精简 Go 版 Logstash](https://mp.weixin.qq.com/s/pYmp3ZVWhY_jbQc0mRDu-A)

2. [Go 数据结构和算法篇（一）：链表](https://mp.weixin.qq.com/s/Cn39YN8R6jOJZS-istaTKA)

二、亚军进化史

1. [Go技术日报(2021-04-11)——rpcx支持websocket协议了!](https://mp.weixin.qq.com/s/JzM4lyxfRPutWL5_hHbzEA)

三、CloudNativeCommunity

1. [同程旅行大数据集群在 Kubernetes 上的服务化实践](https://mp.weixin.qq.com/s/iiWFqQ-_WTXJUzIGQ-qhdw)

四、k8s技术圈

1. [Dockerd资源泄露系列 - 内存&amp;FD泄露 - 1](https://mp.weixin.qq.com/s/nADu7VqNGjP00pSep3Do3A)

五、MoeLove

1. [K8S 生态周报| Kubernetes v1.21 发布, 带来新的内存管理器](https://mp.weixin.qq.com/s/zxGHQ8hDmzS4SCDXu8NkcA)

六、微服务实践

1. [更简的并发代码，更强的并发控制](https://mp.weixin.qq.com/s/jpZHqTKD5uukbMrSzzhtUw)

七、GoOfficialBlog

1. [高性能 Go 代码工坊（Part4)](https://mp.weixin.qq.com/s/HEE_9gq11fY8uwqFvrNFYw)

八、分布式实验室

1. [分布式系统在 Kubernetes 上的进化](https://mp.weixin.qq.com/s/10pKYUnw-xUsNl0OTejaMA)

九、五分选手

1. [深入 Go 并发原语 — Channel 底层实现](https://mp.weixin.qq.com/s/VyLyhtJCcLwpwhUpSCqJZA)

十、polarisxu

1. [Rust 劝退系列 02：第一个 Rust 程序](https://mp.weixin.qq.com/s/dUFJMEzOJGwM5YY8cP9MBQ)

## gopherDaily--2021-04-12 
0. 给expvarmon插上数据持久化的“翅膀”  - https://t.zsxq.com/ZJIuvF6

1. 如何搭建Go Vim开发环境 - https://pmihaylov.com/vim-for-go-development/

2. Go ANSI字符串解析器 - https://github.com/leaanthony/go-ansi-parser

3. 使用Docker和Prometheus监控你的网速 - https://github.com/geerlingguy/internet-monitoring

4. reproxy: Go实现的极简反向代理 - https://github.com/umputun/reproxy

5. 经典旧文：minikube vs.kind vs. k3s，我究竟该用哪个？- https://brennerm.github.io/posts/minikube-vs-kind-vs-k3s.html

6. dasel: 使用选择符(.)查询和修改数据结构中的字段，支持JSON, TOML, YAML, XML和CSV等 - https://github.com/TomWright/dasel

7. MiSTer：一个开放的项目，旨在利用现代硬件重现各种经典计算机、游戏机和街机 - https://github.com/MiSTer-devel/Main_MiSTer/wiki

8. 没人再关心操作系统了 - https://www.lastweekinaws.com/blog/nobody-cares-about-the-operating-system-anymore/

9. 创建README的最简单方法 - https://readme.so/

10. Docker起死回生了 - https://mp.weixin.qq.com/s/mB74MVYa9uxYgFb96kxl5w

## 码农桃花源--2021-04-12
### 文章分享
1. [go并发调度器解析之实现高性能协程库](https://zhuanlan.zhihu.com/p/37754274)

2. [go语言gc部分源码解析](https://zhuanlan.zhihu.com/p/359582221)

3. [2021年后端技术趋势](https://zhuanlan.zhihu.com/p/357532224)

### 面试题
1. 讲一下http协议，cookie的跨域

2. 哈希冲突的解决方式

3. 平时用过库函数sort吗，内部使用什么排序算法

### 每日算法
lc138 复制带随机指针的链表

## go中文网每日资讯--2021-04-11 

一、Go语言中文网

1. [这个Go开源工具有点意思](https://mp.weixin.qq.com/s/s6NpA9AaziFTb3wqjsqd5A)

2. [Go语言爱好者周刊：第 90 期](https://mp.weixin.qq.com/s/Qa60JCXfGGiCjc6b5CZmbQ)

二、亚军进化史

1. [Go技术日报(2021-04-10)——Go语言“十诫”[译]](https://mp.weixin.qq.com/s/YnWiYoa3PrE6_tI5SX44Jg)

三、薯条的自我修养

1. [睡前故事|用Bitmap与AST做一个配置化时长系统](https://mp.weixin.qq.com/s/zWZILWkojj8PDJ8dfs5SWQ)

四、k8s技术圈

1. [OpenKruise Cloneset 使用](https://mp.weixin.qq.com/s/D448uNOnk62vVfdamLREpg)

五、网管叨bi叨

1. [Go语言内部包--控制包成员的对外暴露](https://mp.weixin.qq.com/s/XNiP6EpJGEJGVb55ZpI9oQ)

六、鸟窝

1. [rpcx支持websocket协议了!](https://colobu.com/2021/04/11/support-websocket-in-rpcx/)

七、Go招聘

1. [4/5-4/11股文请接收](https://mp.weixin.qq.com/s/0R-Y_I45xAAC9gu8D5QOwA)

八、Golang Weekly

1. [Golang Weekly Issue 357: April 9, 2021](https://golangweekly.com/issues/357)

2. [Awesome Go Newsletter - Issue 255, Apr 08, 2021 | LibHunt](https://go.libhunt.com/newsletter/255)
 
 
## GOCN每日新闻--2021-04-11 

1.荣誉体验官，TiDB 5.0 在等你 https://gocn.vip/topics/11905

2.GoLand 2021.1 重磅发布：新特性试用报告 https://studygolang.com/topics/13460

3.使用 Go 每分钟处理百万请求 https://mp.weixin.qq.com/s/-gKgduM8Cw_GGYyzrzSbXw

4.Go 语言 “十诫”[译] https://mp.weixin.qq.com/s/YcmNN6DwQiI7b0Pj0Co-vg

5.rpcx 支持 websocket 协议了 https://colobu.com/2021/04/11/support-websocket-in-rpcx/




## gopherDaily--2021-04-11 
- 1.asynq: 为您的下一个Go项目提供简单、可靠、高效的分布式任务队列 - https://dev.to/koddr/asynq-simple-reliable-efficient-distributed-task-queue-for-your-next-go-project-4jhg
- 2.Go播客：Go中测试的磨难 - https://changelog.com/gotime/174
- 3.比较Helm和Kustomize  - https://harness.io/blog/devops/helm-vs-kustomize/
- 4.我如何使用Go构建Iot系统的每一个部分 - https://dev.to/stanleynguyen/going-places-how-i-used-golang-for-literally-every-part-of-an-iot-system-19fm
- 5.微服务注册中心产品ZooKeeper、Eureka、Consul、Nacos对比 - https://mp.weixin.qq.com/s/MNPy5TGarr2xdiljWsvbrA
- 6.轻量级日志分析平台Loki实战 - https://mp.weixin.qq.com/s/DR6kDdor6rPjjSLSJOySNQ
- 7.您的编程语言并不重要 - https://itnext.io/your-programming-language-does-not-matter-63a7ca4a6094
- 8.一个开源的、支持定制的特性开关解决方案 - https://github.com/markphelps/flipt
- 9.面向分布式基础设施的科学 - https://dl.acm.org/doi/abs/10.1145/3428662.3429744
- 10.mongdb集群的k8s operator入门 - https://www.mongodb.com/blog/post/introducing-atlas-operator-kubernetes
- 11.云数据湖 vs. 数据仓库 vs. 数据市场 - https://www.ibm.com/cloud/blog/cloud-data-lake-vs-data-warehouse-vs-data-mart
- 12.Go Context: go语言中最有用的包之一 - https://levelup.gitconnected.com/context-in-golang-98908f042a57



## go中文网每日资讯--2021-04-10 

一、Go语言中文网

1. [错过金三，别错过银四：看看这个Go招聘你符合吗？](https://mp.weixin.qq.com/s/MD6a3l6yWoKgiQ8Q1kztBA)

2. [使用 Go 每分钟处理百万请求](https://mp.weixin.qq.com/s/-gKgduM8Cw_GGYyzrzSbXw)

3. [有趣！一行 Go 代码居然无法获取请求的完整URL](https://mp.weixin.qq.com/s/7PnD--vHTQlDqNuINYMoSQ)

二、亚军进化史

1. [Go技术日报(2021-04-09)——GoLand 2021.1 重磅发布](https://mp.weixin.qq.com/s/OMprvyghrgSnF2S19Mbu2A)

三、吴亲强的深夜食堂

1. [etcd 实战基础篇(一)](https://mp.weixin.qq.com/s/Z9flTpcP4I1sAqxwzV_7NQ)

四、TonyBai

1. [Go语言“十诫”[译]](https://mp.weixin.qq.com/s/YcmNN6DwQiI7b0Pj0Co-vg)
## GOCN每日新闻--2021-04-10 
1.Go 程序配置利器-viper 库 https://gocn.vip/topics/11898

2.服务注册中心设计原理与 Golang 实现 https://mp.weixin.qq.com/s/WZ6HG-ZLFiBJLbE29vTr3g#at

3.基于 Golang 的云原生日志采集服务设计与实践 https://mp.weixin.qq.com/s/3sCyWg-HwfZ4ymm8T9s4zg#at

4.Go 进阶 40:2FA-Google-Authenticator 双因素认证后端实现 https://mojotv.cn/go/golang-2fa

5.错误标志 https://npf.io/2021/04/errorflags/
## gopherDaily--2021-04-10 
- 1.使用libbpfgo构建eBPF应用 - https://blog.aquasec.com/libbpf-ebpf-programs
- 2.错误标记：替代“面向行为进行错误断言”的方案 - https://npf.io/2021/04/errorflags/
- 3.迈向企业级核心场景的 TiDB 5.0 - https://pingcap.com/blog-cn/tidb-5.0-ga-is-now/
- 4.Go程序配置利器-viper库 - https://mp.weixin.qq.com/s/_2H6L-pTXrIS1XH3tQvDMQ
- 5.创建带tls支持的go https server - https://eli.thegreenplace.net/2021/go-https-servers-with-tls/
- 6.使用go、kafka和eventrouter监视k8s集群事件 - https://hackernoon.com/monitor-your-kubernetes-cluster-events-with-eventrouter-golang-and-kafka-wh2a35l0
- 7.Go json编解码解析 - http://saidvandeklundert.net/2021-04-02-go-json/
8.记录一次使用Go和nginx建立gRPC服务时遇到的误导性错误 - https://kennethjenkins.net/posts/go-nginx-grpc/
- 8.datadog开源的go stack输出解析工具 - https://github.com/DataDog/gostackparse
- 9.linux内核将支持apple M1 - https://git.kernel.org/pub/scm/linux/kernel/git/soc/soc.git/commit/?h=for-next&id=0d5fe4b31785b732b71e764b55cda5c8d6e3bbbf
- 10.用树莓派构建构建生长盒, 实时分享植物生长的进展 - https://blog.alexellis.io/iot-growbox/

## go中文网每日资讯--2021-04-09 

一、Go语言中文网

1. [Go 惯用模式：函数选项模式](https://mp.weixin.qq.com/s/58rdkWbWpA4OnvQJF4u_ew)

2. [最清晰易懂的 Go WaitGroup 剖析](https://mp.weixin.qq.com/s/P8Dvy4iAPKywMH6ZlMF19Q)

二、亚军进化史

1. [Go技术日报(2021-04-08)——RLock 过程被调出的悲剧](https://mp.weixin.qq.com/s/3lOpZN7KCks0rUE5yMfbJA)

三、学而思网校技术团队

1. [redis基本原理及缓存应用实践](https://mp.weixin.qq.com/s/WptwD1HPmC0rymZYPyqEWg)

四、CloudNativeCommunity

1. [是否选择多集群 —— 使用服务网格的集群间通信](https://mp.weixin.qq.com/s/pZ2bMCnbt8TBCaoXfDs9QA)

五、k8s技术圈

1. [Prometheus Operator 使用 AlertmanagerConfig 进行报警配置](https://mp.weixin.qq.com/s/bGcYo67lCXIiSZCszZCAUA)

六、多颗糖

1. [【MIT 6.824】学习笔记 6: ZooKeeper 设计原理](https://mp.weixin.qq.com/s/Qk23ADoyCyHijgZi45Haug)

七、polarisxu

1. [GoLand 2021.1 重磅发布：新特性试用报告](https://mp.weixin.qq.com/s/Wt1ADroTJmWUL9bcpZ44pw)

八、Go招聘

1. [高薪不加班的远程工作了解一下？](https://mp.weixin.qq.com/s/eMt7vHflqzbOM27NmSxxVw)


## GOCN每日新闻--2021-04-09 

1.Go 泛型语法又出 “幺蛾子”：引入 type set 概念和移除 type list 中的 type 关键字
https://gocn.vip/topics/11895

2.Go 程序配置利器-viper 库 https://gocn.vip/topics/11898

3.GoLand 2021.1 新增功能 https://www.jetbrains.com/go/promo/whatsnew/

4.Go 可用性 (四) 限流 3: 漏桶算法 https://lailin.xyz/post/go-training-week6-4-leaky-bucket.html

5.Golang+Protobuf+PixieJS 开发 Web 多人在线射击游戏 (原创翻译)
https://www.cnblogs.com/hacker-linner/p/14631031.html



## gopherDaily--2021-04-09
1.Go构建混淆工具 - https://github.com/burrowers/garble

2.谷歌全球一致性授权系统的开源Go实现 - https://github.com/ory/keto

3.什么是Fuzz Testing? - https://blog.fuzzbuzz.io/what-is-fuzz-testing/

4.播客：定位开源：Prometheus的两位维护者朱利安·皮沃托和理查德·哈特曼访谈 - https://www.emilyomier.com/podcast/positioning-open-source-prometheus

5.单人技术初创公司背后的架构 - https://anthonynsimon.com/blog/one-man-saas-architecture/

6.在分布式系统中实现可靠的双写 - https://engineering.razorpay.com/achieving-reliable-dual-writes-in-distributed-systems-cb9ff3b9bfc1

7.发布MinIO Kubernetes Operator和Operator Console - https://blog.min.io/minio-kubernetes-operator/

8.如何使用k8s和glusterFS实现分布式系统 - https://betterprogramming.pub/how-to-implement-your-distributed-filesystem-with-glusterfs-and-kubernetes-83ee7f5f834f

10.jennifer：go代码生成器 - https://github.com/dave/jennifer

11.kubernetes 1.21发布 - https://kubernetes.io/blog/2021/04/08/kubernetes-1-21-release-announcement/

12.IntelliJ Rust更新说明 - https://blog.jetbrains.com/rust/2021/04/08/intellij-rust-updates-for-2021-1/

13.为什么长命令行选项用两个破折号开始？ - https://blog.djmnet.org/2019/08/02/why-do-long-options-start-with/


## 码农桃花源--2021-04-09
### 文章分享
1. [工作线程的唤醒及创建](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483822&idx=1&sn=82e9328c3bb1d1153145261d932ab54b&scene=19#wechat_redirect)

2. [读锁调度导致高延迟的 case 一例](https://mp.weixin.qq.com/s/MI2B9cnbuu-vqiz_JhD0CQ)

3. [煎鱼的goroutine泄漏](https://mp.weixin.qq.com/s/ql01K1nOnEZpdbp--6EDYw)

### 面试题
1. Goroutine 泄露原因

2. 如何定位gouroutine泄漏

3. 之前问过的调度循环

### 每日算法
lc1307  口算难题



## go中文网每日资讯--2021-04-08 

一、Go语言中文网

1. [【文末送书】你知道 Go 之父 Ken&amp;Rob 之前的故事吗？](https://mp.weixin.qq.com/s/BzheVWnEnFNQywaGxMZWDw)

2. [服务注册中心设计原理与Golang实现](https://mp.weixin.qq.com/s/WZ6HG-ZLFiBJLbE29vTr3g)

二、亚军进化史

1. [Go技术日报(2021-04-07)——使用 Go 每分钟处理百万请求](https://mp.weixin.qq.com/s/4EMPHBjsJiasHGqLNQKkOw)

三、Gopher指北

1. [今天看了一道很有意思的切片输出面试题（三）](https://mp.weixin.qq.com/s/qdABTKsNjeG7KpKFRaKMww)

四、polarisxu

1. [Rust 劝退系列 01：打造开发环境](https://mp.weixin.qq.com/s/2GGY_q90NqMd_A2SssOKog)

五、TechPaper

1. [RLock 过程被调出的悲剧](https://mp.weixin.qq.com/s/AGJpvfbB1GoMZ0IRQdFRUQ)

六、脑子进煎鱼了

1. [跟读者聊 Goroutine 泄露的 N 种方法，真刺激！](https://mp.weixin.qq.com/s/ql01K1nOnEZpdbp--6EDYw)

七、xueyuanjun

1. [Go 数据结构和算法篇（十四）：哈希表、哈希函数、哈希冲突和哈希算法](https://mp.weixin.qq.com/s/It1Rtci_A3dwZp1l3ZT90w)

八、k8s技术圈

1. [Go + gRPC-Gateway(V2) 构建微服务实战系列，小程序登录鉴权服务](https://mp.weixin.qq.com/s/P9WBtE4rZ2wepT5OtLjKGw)

九、Go招聘

1. [Baidu职位来啦，高薪不加班还真香](https://mp.weixin.qq.com/s/_lcrbfGZiciKbhnTzwIbgw)



## GOCN每日新闻--2021-04-08 

1.Go time.Now 是如何获取当前时间的？ https://tpaschalis.github.io/golang-time-now/

2.跟读者聊 Goroutine 泄露的 N 种方法，真刺激！ https://mp.weixin.qq.com/s/ql01K1nOnEZpdbp--6EDYw

3.RLock 过程被调出的悲剧 https://mp.weixin.qq.com/s/AGJpvfbB1GoMZ0IRQdFRUQ

4.用 vscode 在 k8s 中调试微服务 https://blog.getambassador.io/debugging-go-microservices-in-kubernetes-with-vscode-a36beb48ef1

5.Go + gRPC-Gateway(V2) 构建微服务实战系列，小程序登录鉴权服务 https://mp.weixin.qq.com/s/P9WBtE4rZ2wepT5OtLjKGw



## gopherDaily--2021-04-08

1.Go泛型语法又出“幺蛾子”：引入type set概念和移除type list中的type关键字 - https://mp.weixin.qq.com/s/W8KMDXHy4tU8kVrgFKkmXg

2.Go运行时与标准库源码分析 - https://github.com/cch123/golang-notes

3.Go并发模式 - https://medium.com/engineering-at-cytora/cytora-golang-academy-part-three-e53af7d7d3e1

4.在WSL 2的k3s上部署rancher - https://boxofcables.dev/deploying-rancher-on-k3s-on-wsl2/

5.将现有应用通过隧道连接到公有云的简单方法 - https://inlets.dev/blog/2021/04/07/simple-hybrid-cloud.html

6.揭秘腾讯内部 Go Modules Proxy 服务 - https://mp.weixin.qq.com/s/GuUHq3uyPiMCQg_G1odAWA

7.AWS Go Cloud Development Kit 发布 - https://aws.amazon.com/cn/blogs/developer/getting-started-with-the-aws-cloud-development-kit-and-go/

8.与gitlab交互的go client api - https://github.com/xanzy/go-gitlab

9.Argo CD v2.0发布 - https://www.cncf.io/blog/2021/04/07/argo-cd-2-0-released/

10.为什么我的go api比node api慢10倍 - https://jason150.medium.com/golang-why-my-go-api-was-10x-slower-than-node-api-b9433d01c490

11.非官方microsoft team go api包 - https://github.com/fossteams/teams-api

## 码农桃花源--2021-04-08
### 文章分享
1. [调度系统设计概念精要](https://draveness.me/system-design-scheduler/)

2. [iftop流量监控](https://www.cnblogs.com/chenqionghe/p/10680075.html)

3. [redis性能问题排查指南](https://mp.weixin.qq.com/s/rw42cFbJXwPtsGiqkFErfw)

### 面试题
1. 讲一下http协议，cookie的跨域

2. 哈希冲突的解决方式

3. 平时用过库函数sort吗，内部使用什么排序算法

### 每日算法
lc424 替换后的最长重复字符



## go中文网每日资讯--2021-04-07 

一、Go语言中文网

1. [使用Go实现可用select监听的队列](https://mp.weixin.qq.com/s/GeM_W3Ea7uHCCgbfrHGHsg)

2. [&quot;go build -X&quot; 的妙用](https://mp.weixin.qq.com/s/nd0ynZfRbgIZktG5TkfWbg)

二、亚军进化史

1. [Go技术日报(2021-04-06)——高性能 Go 代码工坊](https://mp.weixin.qq.com/s/a3-OlgMhkWhoenN1s5C4Rg)

三、MoeLove

1. [K8S 生态周报| Prometheus v2.26 发布, 带来众多实用特性](https://mp.weixin.qq.com/s/w4tqY3G01icJKodD6MF1Cw)

四、吴亲强的深夜食堂

1. [使用 Go 每分钟处理百万请求](https://mp.weixin.qq.com/s/BPCxSYEr6ww2F0b9tqPdSQ)

五、k8s技术圈

1. [kube-scheduler 的 Cache 解析](https://mp.weixin.qq.com/s/xIw4RZUjl2SMzxCRfW3fig)

六、polarisxu

1. [答应我，这次一定彻底搞懂 Go 中的类型别名](https://mp.weixin.qq.com/s/vtgFEXkjaItmkqUzcj64tg)

七、mohuishou

1. [Go可用性(四) 限流3: 漏桶算法](https://mp.weixin.qq.com/s/dJ3hiuA-8BdNF_ENL-WIUg)

八、Golang梦工厂

1. [源码剖析类型断言是如何实现的！附性能损耗测试](https://mp.weixin.qq.com/s/dq5PVHdMBMkbyGSxN28DHA)

九、Golang技术分享

1. [算法系列：广度优先搜索](https://mp.weixin.qq.com/s/p4nDIF6jWTnv5Q8QRKKjpQ)

十、奇伢云存储

1. [存储基础 — 文件描述符 fd 究竟是什么？](https://mp.weixin.qq.com/s/hLq7Pp8CkJD9B-Xqym50dA)

十一、刻舟求荐

1. [第 0002 荐：Fiber，超高性能的Go Web框架](https://mp.weixin.qq.com/s/o70a_zlA43pvbzzbyDXjtg)

十二、Go招聘

1. [gopher们都想有个好未来？那就来这吧](https://mp.weixin.qq.com/s/Le4-3rAjGyFdNyRRUAG4vg)

## GOCN每日新闻--2021-04-07 

1.GAPI 网关 gRPC-Gateway V2 初探 https://mp.weixin.qq.com/s/Mse5UTek6lUmqBxN5ry6iQ

2.【dubbo-go 源码解析】URL：如何应用到 Dubbo-go？https://juejin.cn/post/6948214701470220301

3.使用 Go 实现可用 select 监听的队列 https://mp.weixin.qq.com/s/GeM_W3Ea7uHCCgbfrHGHsg

4.Go ast https://www.jianshu.com/p/443bd82863f8

5.如何规范使用 Design Pattern With Go 设计模式 - 工厂模式 https://www.jianshu.com/p/f6cbc8a44d73

## gopherDaily--2021-04-07
1.go webrtc项目pion的创始人专访 - https://webrtchacks.com/how-go-based-pion-attracted-webrtc-mass-qa-with-sean-dubois/

2.Chaos Mesh 云原生混沌工程测试平台 - https://mp.weixin.qq.com/s/cXz7zbASAWx_m4JnFxC1qQ

3.是否选择多集群 —— 使用服务网格的集群间通信 - https://mp.weixin.qq.com/s/Kn4KDlwMAmDvzr-dRv95dw

4.为什么k8s上对象存储很重要 - https://blog.min.io/why-kubernetes-managed

5.k8s官博：作废PodSecurityPolicy: https://kubernetes.io/blog/2021/04/06/podsecuritypolicy-deprecation-past-present-and-future/

6.KubeLinter 是一种静态分析工具，可检查k8s YAML 文件和helm chart，以确保其中应用程序符合最佳实践 - https://github.com/stackrox/kube-linter

7.使用Go实现一个自定义go linter - https://developer20.com/custom-go-linter/

8.Go实现的rss阅读工具 - https://gitlab.com/microo8/photon

9.我讨厌PostgreSQL的 10 件事 - https://rbranson.medium.com/10-things-i-hate-about-postgresql-20dbab8c2791

10.使用Go语言在电子表格中生成从属下拉列表 - https://dzone.com/articles/quick-tutorial-generate-dependent-drop-list-in-spr

11.google开源下一代音频编解码器：Lyra - https://github.com/google/lyra

## 码农桃花源--2021-04-07
### 文章分享
1. [write文件一个字节后何时发起写磁盘IO](https://mp.weixin.qq.com/s/qEsK6X_HwthWUbbMGiydBQ)

2. [zk一致性原理](https://www.cnblogs.com/sunddenly/p/4138580.html)

3. [操作系统三大调度算法] https://mp.weixin.qq.com/s/JWj6_BF9Xc84kQcyx6Nf_g

### 面试题
1. redis的zset是如何实现的？为什么只在数据量小的时候用ziplist

2. 知道哪些限流算法？

### 每日算法
lc222 完全二叉树的节点个数

## go中文网每日资讯--2021-04-06 

一、Go语言中文网

1. [Go：使用 Ebiten 在 2D 视频游戏中进行图像渲染](https://mp.weixin.qq.com/s/KMPpwMiAoXoh0eicVjwblA)

2. [Go垃圾回收系列之十一：finalizer的妙用](https://mp.weixin.qq.com/s/E076Svi1EAkEz63d1jVpKw)

二、亚军进化史

1. [Go技术日报(2021-04-05)——图形化展示go包依赖关系](https://mp.weixin.qq.com/s/YnQst2VnoaZh0eGux2rJsA)

三、 MoeLove

1. [深入源码彻底搞懂 Docker 镜像](https://mp.weixin.qq.com/s/AHR_IRAbytB46nCgYvrFiw)

四、ServiceMesher

1. [是否选择多集群 —— 使用服务网格的集群间通信](https://mp.weixin.qq.com/s/Kn4KDlwMAmDvzr-dRv95dw)

五、luozhiyun很酷

1. [一文教你搞懂 Go 中栈操作](https://mp.weixin.qq.com/s/H9ZYnJevZAnFaNsIH2wbjQ)

六、k8s技术圈

1. [API 网关 gRPC-Gateway V2 初探](https://mp.weixin.qq.com/s/Mse5UTek6lUmqBxN5ry6iQ)

七、脑子进煎鱼了

1. [你知道 Go 结构体和结构体指针调用有什么区别吗？](https://mp.weixin.qq.com/s/g-D_eVh-8JaIoRne09bJ3Q)

八、Golang梦工厂

1. [如何平滑切换线上Elasticsearch索引](https://mp.weixin.qq.com/s/8VQxK_Xh-bkVoOdMZs4Ujw)

九、GoOfficialBlog

1. [高性能 Go 代码工坊（Part3)](https://mp.weixin.qq.com/s/74FQ0PB-idCVLa_hKyQuag)

十、微服务实践

1. [极速精简 Go 版 Logstash](https://mp.weixin.qq.com/s/UeeSZi_-ZiiHf3P4tmyszw)

十一、技术岁月

1. [服务注册发现之服务注册中心设计原理与Golang实现](https://mp.weixin.qq.com/s/ZWJBuszbaso1KuE9BjNBHg)

## GOCN每日新闻--2021-04-06 

1.揭秘腾讯内部 Go Modules Proxy 服务 https://mp.weixin.qq.com/s/GuUHq3uyPiMCQg_G1odAWA

2.像大神一样调试 Go https://juejin.cn/post/6947868469270577159

3.一文教你搞懂 Go 中栈操作 https://www.luozhiyun.com/archives/513

4.Goroutine 实现并发应该思考的问题 https://juejin.cn/post/6947548031793233957

5.让 Go 程序以 systemd 服务运行 https://khanakia.medium.com/golang-running-a-go-binary-as-a-systemd-service-on-ubuntu-18-04-in-10-minutes-without-docker-e5a1e933bb7e

## gopherDaily--2021-04-06 
- 1.Go语言的“十条戒律” - https://bitfieldconsulting.com/golang/commandments

- 2.pterm: 强大的控制台输出美化包 - https://github.com/pterm/pterm

- 3.标准库context包探秘 - https://steveazz.xyz/blog/import-context/

- 4.使用Go构建一个基础区块链 - https://levelup.gitconnected.com/how-to-build-a-basic-blockchain-in-go-c5745ea06456

- 5.通过goroutine加速你的go应用 - https://betterprogramming.pub/golang-basics-speed-up-your-program-with-goroutines-4ce84945aba8

- 6.为什么我从wordpress迁移到gohugo - https://sspaeti.com/blog/why-i-moved-away-from-wordpress/

- 7.packiffer: 跨平台包嗅探器 - https://github.com/massoudasadi/packiffer

- 8.docuowl: Go实现的文档生产工具 - https://github.com/docuowl/docuowl

- 9.云原生世界的服务网格 - https://thenewstack.io/service-meshes-in-the-cloud-native-world/

- 10.Git作为一个NoSql数据库 - https://www.kenneth-truyers.net/2016/10/13/git-nosql-database/

## 码农桃花源--2021-04-06
### 文章分享
1. [工作线程的唤醒及创建](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483822&idx=1&sn=82e9328c3bb1d1153145261d932ab54b&scene=19#wechat_redirect)

2. [bad file descriptor](https://xargin.com/case-bad-file-descriptor/)

3. [Go netpoller 原生网络模型之源码全面揭秘](https://zhuanlan.zhihu.com/p/91042195)
### 面试题
1. Go语言的栈空间管理是怎么样的

2. 堆内存管理怎么分配的

3. 栈的内存是怎么分配的

### 每日算法
lc600 不含连续1的非负整数

## go中文网每日资讯--2021-04-05 


一、Go语言中文网

1. [为什么你应该慎重考虑使用 Kubernetes](https://mp.weixin.qq.com/s/3Od9u1YUH5KGQvo7Ky3O6w)

2. [Go 语言格式化动词，一篇理清](https://mp.weixin.qq.com/s/SCsxIYvyt5N-tRlwLnECzQ)

二、亚军进化史

1. [Go技日报(2021-04-04)——Gopher 值得收藏的一些书签](https://mp.weixin.qq.com/s/ZGCWngrtey6gclGpj885aQ)

三、k8s技术圈

1. [Traefik SRE 之使用 Prometheus 进行监控报警](https://mp.weixin.qq.com/s/yWtv25Bt2Y7vGSJjJ4Y0KA)

2. [K8S 云平台/Go 工程师/专家 - 小鹏汽车 | 云原生招聘](https://mp.weixin.qq.com/s/WPxFuGZMfCGON02ZvohGCg)

四、Golang Weekly

1. [Golang Weekly Issue 356: April 2, 2021](https://golangweekly.com/issues/356)

2. [Awesome Go Newsletter - Issue 254, Apr 01, 2021 | LibHunt](https://go.libhunt.com/newsletter/254)

五、Go招聘

1. [三月你股了么](https://mp.weixin.qq.com/s/Wv9jSRj_wyKrUUfwbxZ1tw)
## GOCN每日新闻--2021-04-05 

1.使用 TLS 的 Go HTTPS 服务器 https://eli.thegreenplace.net/2021/go-https-servers-with-tls/

2.Go 构建区块链 https://dev.to/nheindev/build-the-hello-world-of-blockchain-in-go-bli

3.Go 中的第三方认证集成 https://dev.to/stephenafamo/authenticating-3rd-party-integrations-in-go-ldj

4.Go Stringer 代码生成 https://medium.com/a-journey-with-go/go-stringer-command-efficiency-through-code-generation-df49f97f3954

5.如何恢复 Go 程序 https://medium.com/a-journey-with-go/go-how-does-a-program-recover-fbbbf27cc31e


## gopherDaily--2021-04-05 
- 1.Go团队针对泛型语法又出“幺蛾子” - 新type set语法替代原type list - https://t.zsxq.com/nY7AeyJ
- 2.探索kubernetes operator模式 - https://iximiuz.com/en/posts/kubernetes-operator-pattern/
- 3.如何快速创建Go应用 - https://adhoc.team/2021/03/29/simple-web-app-in-golang/
- 4.使用ent在两分钟内构建全功能gRPC服务 - https://entgo.io/blog/2021/03/18/generating-a-grpc-server-with-ent/
- 5.兼容XPath 1.0的Go包 - https://github.com/ChrisTrenkamp/xsel
- 6.图形化展示go包依赖关系 - https://gographs.io/
- 7.Teleport：一种身份识别、支持多协议的访问代理 - https://github.com/gravitational/teleport
- 8.OpenShift安全最佳实践 - https://www.stackrox.com/post/2020/11/openshift-security-best-practices-part-1-of-5-cluster-design/
- 9.使用docker构建集成开发环境 - https://medium.com/@ls12styler/docker-as-an-integrated-development-environment-95bc9b01d2c1
- 10.tmux入门 - https://sunainapai.in/blog/get-started-with-tmux/
- 11.测试Operator SDK并为Kubernetes建立预取机制 - https://itnext.io/testing-the-operator-sdk-and-making-a-prefetch-mechanism-for-kubernetes-7508577efdd7




## go中文网每日资讯--2021-04-04 


一、Go语言中文网

1. [Go语言爱好者周刊：第 89 期 — 泛型又有变动](https://mp.weixin.qq.com/s/XMc_wMGgLgCXRJecGMx93g)

2. [不知道如何组织项目结构，这个项目也许可以给你启发](https://mp.weixin.qq.com/s/PUBshhETz7kcJ-0VNhpvdw)

3. [面试官：你能用Go写段代码判断当前系统的存储方式吗？](https://mp.weixin.qq.com/s/JNef8fGc3jyHqdqgCoYkPg)

二、亚军进化史

1. [Go技术日报(2021-04-03)——揭秘WaitGroup源码设计](https://mp.weixin.qq.com/s/pNM2su7jeBn7UYvEMkY3_A)

三、云原生技术爱好者社区

1. [Linkerd、Consul、Istio、Kuma、Traefik、AWS App服务网格全方位对比](https://mp.weixin.qq.com/s/22OYzOGhygIFU09ofZ1hig)

四、网管叨bi叨

1. [gRPC的平滑关闭和在Kubernetes上的服务摘流方案总结](https://mp.weixin.qq.com/s/lCTyZgSK3b-rJtV9l6PNYA)
## GOCN每日新闻--2021-04-04 
1.针对前端开发者的 Go 入门指南 https://medium.com/star-gazers/golang-for-frontend-developers-beginner-guide-to-golang-87aa036b932f

2.系统受控 - 如何自动化集成测试 https://medium.com/bumble-tech/system-under-control-how-to-automate-integration-tests-52383be28d07

3.Go 与 RabbitMQ 集成示例 https://dev.to/koddr/working-with-rabbitmq-in-golang-by-examples-2dcn

4.成为更好的 Gopher 值得收藏的一些书签 https://dev.to/rubenwap/must-bookmarks-to-become-good-in-go-ln8

5.Go 包依赖分析工具 https://github.com/adonovan/spaghetti

## gopherDaily--2021-04-04 
- 1.大厂Go语法50问 - https://www.readfog.com/a/1631467208759676928
- 2.基于docker-compose在google云上运行集成测试 - https://threedots.tech/post/running-integration-tests-on-google-cloud-build/
- 3.利用接口在Go中模拟测试外部API - https://levelup.gitconnected.com/utilizing-the-power-of-interfaces-when-mocking-and-testing-external-apis-in-golang-1178b0db5a32
- 4.漂亮的终端布局的样式定义(基于TUI) -  https://github.com/charmbracelet/lipgloss
- 5.分布式操作系统不存在 - https://nivenly.com/lib/2021-04-02-operating-system-interface/
- 6.Windows 10上不用Docker的Windows容器（使用containerd） - https://www.jamessturtevant.com/posts/Windows-Containers-on-Windows-10-without-Docker-using-Containerd/
- 7.网络错误配置扫描器 - https://github.com/SpectralOps/netz
- 8.使用go开发一个区块链：持久化 - https://dev.to/nheindev/building-a-blockchain-in-go-pt-iii-persistence-3884
- 9.互联网测速命令行工具 - https://github.com/adhocore/fast
- 10.编程语言引发了隐私问题 - https://www.bleepingcomputer.com/news/security/most-loved-programming-language-rust-sparks-privacy-concerns/
## go中文网每日资讯--2021-04-03 

一、Go语言中文网

1. [Hugo作者、Go核心团队成员Steve Francia谈诞生13年的Go语言：生态系统、演化与未来[译]](https://mp.weixin.qq.com/s/P5_wFaNgWkoNZKA7w3g_xA)

2. [Go中看似简单的WaitGroup源码设计，竟然暗含这么多知识？](https://mp.weixin.qq.com/s/NYusaV42VyYtMByD-JuA3A)

3. [Go 存储基础 — 文件 IO 的姿势](https://mp.weixin.qq.com/s/kHGxXEz7lahDeXhrDxvmHw)

二、亚军进化史

1. [Go技术日报(2021-04-02)——Go 1.16.3 发布](https://mp.weixin.qq.com/s/YzhYbyFQmDrO90-OT8zhkA)

三、k8s技术圈

1. [Prometheus Operator 安装配置|最新版](https://mp.weixin.qq.com/s/vUsi4OrVopav46QHEBDNsA)

2. [高级 SRE/DevOps 专家 - 理想汽车 | 云原生招聘](https://mp.weixin.qq.com/s/B1d6qBrhiAZNYcLcdluJkA)




## GOCN每日新闻--2021-04-03 
1.Go map vs switch https://adayinthelifeof.nl/2021/03/04/go-map-vs-switch.html

2.Go nil 类型的理论与实践 https://utcc.utoronto.ca/~cks/space/blog/programming/GoNilIsTypedSortOf

3.Go http handler 的小细节 https://vladimir.varank.in/notes/2021/03/little-things-of-go-http-handlers/

4.一个 Go module 的生命流程 https://jayconrod.com/posts/118/life-of-a-go-module

5.Go 自动测试实践 https://dev.to/salesforceeng/intro-to-automated-testing-in-go-4mjl

## gopherDaily--2021-04-03 
- 1.Go 应用优化指北 -  https://mp.weixin.qq.com/s/J1PdpX4Mr6crR6cZMAqecQ
- 2.在线重加载Go应用 - https://github.com/cosmtrek/air
- 3.油管视频：理解Go内存分配：栈与堆 - https://www.youtube.com/watch?v=ZMZpH4yT7M0
- 4.不要在集成测试中使用build tag - https://peter.bourgon.org/blog/2021/04/02/dont-use-build-tags-for-integration-tests.html
- 5.2021年，Go还值得初学者学习吗 - https://medium.com/geekculture/is-golang-worth-learning-for-beginners-in-2021-2d189ea3419e
- 6.Go与rabbitmq实例 - https://dev.to/koddr/working-with-rabbitmq-in-golang-by-examples-2dcn
- 7.semver版本号解析工具 - https://github.com/hashicorp/go-version
- 8.Omniparser：原生的GoETL解析器，支持提取各种格式的输入数据 - https://github.com/jf-tech/omniparser
- 9.Argo Workflows 3.0发布 - https://www.cncf.io/blog/2021/04/02/argo-workflows-3-0-released/
- 10.71张图详解IP 地址、IP 路由、分片和重组、三层转发、ARP、ICMP - https://mp.weixin.qq.com/s/e0MsxZn0-hZ5KIOUF8p6IA
- 11.单个C源文件的http server - https://unix4lyfe.org/darkhttpd/
- 12.Go是一门伟大的编程语言 - https://drewdevault.com/2021/04/02/Go-is-a-great-language.html

## go中文网每日资讯--2021-04-02 


一、Go语言中文网

1. [那些想替代 C 的语言怎么样？Go、Rust、C++ 和 Zig 生产力对比](https://mp.weixin.qq.com/s/jUWLmeqwVJyI9HTw66yLiA)

2. [Go 1.16.3 发布](https://mp.weixin.qq.com/s/lOfOw7y3qxqtuGmO-T937A)

3. [RedMonk 编程语言排行榜，说 Go 正走向衰退](https://mp.weixin.qq.com/s/QLoet9MHPCdSdJ3t-Q13Iw)

4. [Go 面试题：滑动窗口技巧](https://mp.weixin.qq.com/s/F0UhJBqMBl8IQCjF10AgvQ)

二、亚军进化史

1. [Go技术日报(2021-04-01)—— 令牌桶的实现 rate/limt](https://mp.weixin.qq.com/s/tWH8FhDZev9Cjfp0weaNTg)

三、polarisxu

1. [「Hello, World」发明者的传奇人生 — 文末送书](https://mp.weixin.qq.com/s/vGDU8okV30XHZCvFEJR4Sg)

四、字节跳动技术团队

1. [火山引擎 Redis 云原生实践](https://mp.weixin.qq.com/s/VCpuZ0lvgSgfvG7voBl9fw)

五、云原生技术爱好者社区

1. [Kubernetes常见面试问题总结](https://mp.weixin.qq.com/s/tgP-Vk8O83UbxlHCfjIHgQ)

六、脑子进煎鱼了

1. [再见 Go 面试官：单核 CPU，开两个 Goroutine，其中一个死循环，会怎么样？](https://mp.weixin.qq.com/s/h27GXmfGYVLHRG3Mu_8axw)

七、Go招聘

1. [西安也是起飞的节奏，大厂狂招Gopher](https://mp.weixin.qq.com/s/Fha7qOzLreG1aoKJ7oFyjA)


## GOCN每日新闻--2021-04-02 😛
1.Golang 语言的编程技巧之类型 https://mp.weixin.qq.com/s/NwJY4-QULFT8Cd5R2un6cw

2.context 使用不当引发的一个 bug https://mp.weixin.qq.com/s/FkgPzlwJtVUvCL_O7M-_jw

3.Go 函数闭包底层实现 https://mp.weixin.qq.com/s/w5aq4PuLG1tT57nRzuzaFw

4.go 中 semaphore 源码解读 https://boilingfrog.github.io/2021/04/02/semaphore/

5.你能用 Go 写段代码判断当前系统的存储方式吗？ https://mp.weixin.qq.com/s/ffEsTpO-tyNZFR5navAbdA


## gopherDaily--2021-04-02 
- 1.spaghetti：基于Web的交互式的Go包依赖分析工具 - https://github.com/adonovan/spaghetti
- 2.Go原生支持fuzz test的提案被accept - https://github.com/golang/go/issues/44551
- 3.用于Go语言开发的Top 10 IDE和工具 -  https://www.mindinventory.com/blog/golang-ide-tools-for-go-development/
- 4.使用Promtail, Loki, Grafana搭建k8s日志分析系统 - https://itnext.io/logging-in-kubernetes-with-loki-and-the-plg-stack-93b27c90ec34
- 5.google开源的与容器镜像仓库交互的go包与命令行工具 - https://github.com/google/go-containerregistry
- 6.go tip版本已经实现基于寄存器的ABI规范(以前是基于栈的) - https://github.com/golang/go/issues/40724#issuecomment-811561715
- 7.Go 1.16.3和Go 1.15.11 发布 -  https://groups.google.com/g/golang-announce/c/wVRzkWSQpO0/m/EUykHAm0CAAJ
- 8.Go设计草案：Go漏洞数据库 - https://go.googlesource.com/proposal/+/master/design/draft-vulndb.md
- 9.使用Go和kotlin重写alda - https://blog.djy.io/why-im-rewriting-alda-in-go-and-kotlin/
- 10.云提供商的CPU基准测试 - https://thenewstack.io/cpu-benchmarks-for-cloud-providers-intel-vs-amd-vs-amazons-arm-based-graviton2/
- 11.Go泛型设计又有新简化：约束中的type关键字被去掉 - https://github.com/golang/go/issues/45346



## 码农桃花源--2021-04-02
### 文章分享
1. [go 被动调动一](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483817&idx=1&sn=18e0f78465a67e4d87a27065607401e4&scene=19#wechat_redirect)

2. [go 为服务的破坏](https://mp.weixin.qq.com/s/2fuJbXHDmve52mwXXvfxHQ)

3. [go 如果你的+-*/一起用](https://mp.weixin.qq.com/s/kMFfSkKbV7w0lwPOgGK-CQ)

### 面试题

1.
 ```go
 v := new(int)
    *v = 2
    println(5/+-*v)
```
输出什么？

2. 当在M上运行的goroutine发生阻塞时，会怎么工作

3. g0，m0 的作用

4. 什么时候会抢占P

### 每日算法
lc1307 口算难题

## go中文网每日资讯--2021-04-01 

一、Go语言中文网

1. [想使用 Go 开发 GUI 项目的可以看看这个](https://mp.weixin.qq.com/s/pkJgXK2tEC7B5KPGMWkA_w)

2. [Go爱好者周刊 87、88期题解](https://mp.weixin.qq.com/s/WRB0lJ_XBBDqei48bvaNKg)

3. [RabbitMQ Go客户端教程6——RPC](https://mp.weixin.qq.com/s/4cSfAFo11mWJhZ9txW3B1A)

二、亚军进化史

1. [Go技术日报(2021-03-31)——用 Go + WebSocket 快速实现一个 chat 服务](https://mp.weixin.qq.com/s/Cm9zCr2umFspNBPmlV2MFQ)

三、luozhiyun很酷

1. [如何编译调试Go runtime源码](https://mp.weixin.qq.com/s/iQ3wnJh6hpBsZVM1ca5B3Q)

四、TechPaper

1. [让微服务失败的 10 个 tips](https://mp.weixin.qq.com/s/eAfjKul0BVgXI0w_ZVTPZA)

五、k8s技术圈

1. [拥抱云原生，基于eBPF技术实现Serverless节点访问K8S Service](https://mp.weixin.qq.com/s/0zOxvNKBtVEDMa_YgAr22Q)

六、CloudNativeCommunity

1. [Kubernetes Scheduler Cache 架构设计源码阅读](https://mp.weixin.qq.com/s/Rx7z6UrhV849aWUj5TUo8Q)

七、真没什么逻辑

1. [2020 年总结 · 渐入佳境](https://mp.weixin.qq.com/s/Nbcrw5kj_uaW7O6DBdzm5Q)

八、mohuishou

1. [Go可用性(三) 限流2: 令牌桶的实现 rate/limt](https://mp.weixin.qq.com/s/7AMTD6fZY6q0_zdBs90tRQ)

九、脑子进煎鱼了

1. [Go 内存泄露之痛，这篇把 Go timer.After 问题根因讲透了！](https://mp.weixin.qq.com/s/KSBdPkkvonSES9Z9iggElg)

十、polarisxu

1. [我无语了，Go 中 +-*/ 四个运算符竟然可以连着用](https://mp.weixin.qq.com/s/kMFfSkKbV7w0lwPOgGK-CQ)
 
## gopherDaily--2021-04-01 

- 1.使用vscode调试k8s集群中的微服务 - https://blog.getambassador.io/debugging-go-microservices-in-kubernetes-with-vscode-a36beb48ef1
- 2.关于http handler的一些考量 - https://vladimir.varank.in/notes/2021/03/little-things-of-go-http-handlers/
- 3.在Go中，nil在理论上是有类型的，但在实践中有些时候又是无类型的 - https://utcc.utoronto.ca/~cks/space/blog/programming/GoNilIsTypedSortOf
- 4.使用闭包简化Go程序编写 - https://betterprogramming.pub/closures-made-simple-with-golang-69db3017cd7b
- 5.istio赢得了服务网格的战争 - https://thenewstack.io/solo-io-istio-is-winning-the-service-mesh-war/
- 6.caddy web服务器的限速插件 - https://github.com/mholt/caddy-ratelimit
- 7.使威胁图可扩展：利用DSL改善数据摄取 - https://www.crowdstrike.com/blog/how-crowdstrike-threat-graph-leverages-dsl-to-improve-data-ingestion-part-1/
- 8.油管视频：eBPF：安全的内核编程模型 - https://www.youtube.com/watch?v=AV8xY318rtc
- 9.calico使用eBFP进行数据平面的主机保护 - https://thenewstack.io/calico-extends-ebpf-data-plane-to-offer-host-protection/
- 10.“编译器”的先驱Jeffrey Ullman和Alfred Aho 获得图灵奖殊荣 - https://www.nytimes.com/2021/03/31/technology/turing-award-aho-ullman.html
- 11.使用kong k8s ingress controller作为api网关 - https://konghq.com/blog/kubernetes-ingress-api-gateway
- 12.服务网格何时真正体现出价值 - https://containerjournal.com/features/when-is-service-mesh-worth-it/


## GOCN每日新闻--2021-04-01 

1.Go 语言中常见的几种反模式 [译] https://gocn.vip/topics/11857

2.最好的 Go IDE 和工具 https://www.mindinventory.com/blog/golang-ide-tools-for-go-development/

3.如何编译调试 Go runtime 源码 https://www.luozhiyun.com/archives/506

4.使用 VScode 调试 Kubernetes 中的 Go 微服务 https://blog.getambassador.io/debugging-go-microservices-in-kubernetes-with-vscode-a36beb48ef1

5.simgo: Go 离散事件仿真库 https://github.com/fschuetz04/simgo

## 码农桃花源--2021-04-01
## 文章分享
1. [go 盗取goroutine](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483806&idx=1&sn=e375be6b5a3690204f335d845b3be412&scene=19#wechat_redirect)

2. [go 应用优化](https://mp.weixin.qq.com/s/J1PdpX4Mr6crR6cZMAqecQ)

3. [go K8s argo workflow](https://www.yuque.com/wuguoguoya/iq0d3v/ya3oc4)

## 面试题
1. go 盗用goroutine时的算法

2. 调度循环

3. 什么时候会抢占P

## 每日算法
lc710 黑名单中的随机数


## go中文网每日资讯--2021-03-31

一、Go语言中文网

1. [重磅发布：第一本包含泛型的 Go 图书](https://mp.weixin.qq.com/s/8YZzVtdSxegT6K956sf0oA)

2. [RabbitMQ Go客户端教程5——topic](https://mp.weixin.qq.com/s/wZD7D187DmS1RjZuxebbcw)

二、亚军进化史

1. [Go技术日报(2021-03-30)——Go 应用优化指北](https://mp.weixin.qq.com/s/8lcDwohk1UVFJkRIHYrP_w)

三、Gopher指北

1. [今天看了一道很有意思的切片输出面试题（二）](https://mp.weixin.qq.com/s/O5533KWvDkyrsiCpBRP9EA)

四、polarisxu

1. [一本 Go 新书：美国盗版图书这么厉害？](https://mp.weixin.qq.com/s/CSgQDfW9v_-tmbGkkQDqQg)

五、CloudNativeCommunity

1. [手把手教你玩转 Kubeflow on EKS（一）](https://mp.weixin.qq.com/s/1ofdU3kZNQAnOlJC2T98Hg)

六、TonyBai

1. [Go语言中常见的几种反模式[译]](https://mp.weixin.qq.com/s/BKPXIrubvoPCqAhH2Kv3Zw)

七、TechPaper

1. [依赖反转相关](https://mp.weixin.qq.com/s/cahh0DvCl6ua3TsckcYh3g)

八、微服务实践

1. [用 Go + WebSocket 快速实现一个 chat 服务](https://mp.weixin.qq.com/s/8pBKZ8Mx_P2QyCBT_nvNuw)

九、k8s技术圈

1. [kube-apiserver 重启引起的全量对象更新](https://mp.weixin.qq.com/s/aE9sitph2HoLnX4ixl7RtA)

十、奇伢云存储

1. [存储入门进阶推荐：存储技术通关看这几本书](https://mp.weixin.qq.com/s/zyNb5N05un8w5AakAXv8Kg)

十一、Go招聘

1. [风水轮流转：这次大广州 Gopher 走一波，福利还不错哦](https://mp.weixin.qq.com/s/t6-fLG1LPthb13kY1SSh_Q)



## GOCN每日新闻--2021-03-31

1.Go 如何知道 time.Now 的时间 https://tpaschalis.github.io/golang-time-now/

2.构建一个超简约的 Docker 镜像运行 Golang App https://dev.to/chseki/build-a-super-minimalistic-docker-image-to-run-your-golang-app-33j0

3.Go 中集合的高阶函数 https://sergio-franco.me/posts/higher-order-collections/

4.go 实现的 url 短链接服务 https://github.com/adhocore/urlsh

5.go 实现的构建虚拟网络工具 https://github.com/gravitl/netmaker



## gopherDaily--2021-03-31

1.http.Client的连接行为控制 - https://t.zsxq.com/3VbIMbU

2.Go time.Now的工作原理 - https://tpaschalis.github.io/golang-time-now/

3.我如何快速创建小型Go应用 - https://adhoc.team/2021/03/29/simple-web-app-in-golang/

4.netmaker: 一站式创建安全、快速的专用网络将任何计算机连接在一起，并从中央服务器管理多个网络 - https://github.com/gravitl/netmaker

5.播客：基于Go技术栈构建初创企业 - https://okteto.com/blog/build-your-startup-with-go/

6.Yearning: SQL审核平台 - https://github.com/cookieY/Yearning

7.学习Go的十大网站 - https://dev.to/pluralsight/the-top-10-places-to-learn-go-3lhp

8.Go开发的优势与劣势 - https://codism.io/pros-and-cons-of-golang-development

9.经典旧文：理解你的nil - http://jeremymikkola.com/posts/2017_03_29_know_your_nil.html

10.分布式系统在 Kubernetes 上的进化 - https://mp.weixin.qq.com/s/dtFsp1ano9blR12TcLmY1w

11.机器学习数学学习速查表 - https://twitter.com/MLsummaries/status/1376631183589699586

12免费电子书：逆向工程指南 - https://0xinfection.github.io/reversing/reversing-for-everyone.pdf

## 码农桃花源--2021-03-31
### 文章分享
1 [linux任务调度器的演进](http://www.wowotech.net/process_management/scheduler-history.html)

2 [为什么linux需要虚拟内存](https://draveness.me/whys-the-design-os-virtual-memory/)

3 [
