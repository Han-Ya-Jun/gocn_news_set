# [gocn_news_set](https://gocn.vip/explore/category-14)
在之前爬虫Go中国技术社区每日新闻的的[小工具](https://github.com/Han-Ya-Jun/news_watch_notice)加了一个功能，自动归档到github上，方便查阅，每天自动更新。
# [gocn_news_set_2017](gocn_news_set_2017.md)
# [gocn_news_set_2018](gocn_news_set_2018.md)
# [gocn_news_set_2019](gocn_news_set_2019.md)
# [gocn_news_set_2020(上)](gocn_news_set_2020_01.md)
# [gocn_news_set_2020(下)](gocn_news_set_2020_02.md)
# gocn_news_set_2021

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

3 [文件系统和裸块设备的page cache问题](http://www.wowotech.net/filesystem/439.html)

### 面试题
1 从用户态与内核态的角度讲一下同步IO和异步IO

2 举例说明进程间通信

3 TCP的网络拥塞控制机制，滑动窗口如何确定

### 每日算法
lc140 单词拆分
https://leetcode-cn.com/problems/word-break-ii/



## go中文网每日资讯--2021-03-30
一、Go语言中文网

1. [对Go 1.16 io/fs设计的第一感觉：得劲儿！](https://mp.weixin.qq.com/s/CMzCHOMeOThzuDMTZzP0AA)

2. [RabbitMQ Go客户端教程4——路由](https://mp.weixin.qq.com/s/NHO3ORUZavqjEXfx_k7W9g)

二、亚军进化史

1. [Go技术日报(2021-03-29)——Goroutine 泄漏防治神器 goleak](https://mp.weixin.qq.com/s/Q3Yp76gJJmlP_ZZm6RAj4w)

三、TechPaper

1. [Go 应用优化指北](https://mp.weixin.qq.com/s/J1PdpX4Mr6crR6cZMAqecQ)

四、polarisxu

1. [Go周刊题解：切片的另类初始化 — 该题正确率出奇的低](https://mp.weixin.qq.com/s/QZdRU7rA93PrJRfSmhACAg)

五、k8s技术圈

1. [Kubernetes APIServer 机制概述](https://mp.weixin.qq.com/s/aPcPx8rZ4nL5hUAgy7aovg)

六、CloudNativeCommunity

1. [分布式系统在 Kubernetes 上的进化](https://mp.weixin.qq.com/s/dtFsp1ano9blR12TcLmY1w)

七、真没什么逻辑

1. [你该如何为 Kubernetes 定制特性](https://mp.weixin.qq.com/s/0XZa2KBubdNtN6sJTonluA)

八、脑子进煎鱼了

1. [手撕 Go 面试官：Go 结构体是否可以比较，为什么？](https://mp.weixin.qq.com/s/HScH6nm3xf4POXVk774jUA)

九、码农桃花源

1. [喜提 Go Contributor](https://mp.weixin.qq.com/s/vMM2tKEGJUproWMhycVtog)

十、Golang技术分享

1. [区区一个单例就想阻止我拿大厂offer？](https://mp.weixin.qq.com/s/2kxEHYJLLi4-0lqmTww0kA)

## GOCN每日新闻--2021-03-30
 1.内存管理设计精要 https://mp.weixin.qq.com/s/ytm8UiulueXgFALPjdlGrQ
 
 2.Go 网络包默认值下的陷阱 https://martin.baillie.id/wrote/gotchas-in-the-go-network-packages-defaults/
 
 3.该如何为 Kubernetes 定制特性 https://mp.weixin.qq.com/s/0XZa2KBubdNtN6sJTonluA
 
 4.Go 应用优化指北 https://mp.weixin.qq.com/s/ZTWJjbXfWygUD8Js-fTaBQ
 
 5.Go 中的"优雅"的错误处理 https://juejin.cn/post/6944996155277672478


## gopherDaily--2021-03-30
 - 1.Go语言的“黑暗角落”：盘点学习Go语言时遇到的那些陷阱 - https://mp.weixin.qq.com/s/fRL1wmOFtoeYQsNjPnZ30g
 
 - 2.Go中集合类型的高阶函数 - https://sergio-franco.me/posts/higher-order-collections/
 
 - 3.Go数据类型-第一部分 - https://medium.com/star-gazers/data-structures-with-go-part-i-3e2c3d950cd4
 
 - 4.x/crypto/openpgp包被建议作废 -  https://github.com/golang/go/issues/44226
 
 - 5.创建一个protoc插件以使用progengen生成Go代码 - https://rotemtam.com/2021/03/22/creating-a-protoc-plugin-to-gen-go-code/
 
 - 6.油管视频：高性能log库zap - https://www.youtube.com/watch?v=oKMktsJXNIk
 
 - 7.Go中生成的依赖项注入容器- https://github.com/sarulabs/dingo
 
 - 8.使用Go和vue.js开发社交应用 - https://medium.com/nerd-for-tech/social-application-with-vue-js-and-go-64978f7c381f
 
 - 9.经典旧文：为Go项目贡献你的知识和技能 -  https://medium.com/@IndianGuru/contribute-your-time-expertise-to-go-3b61760fabbc
 
 - 10.nerdctl: 适用于Containerd的、与docker兼容的cli - https://medium.com/nttlabs/nerdctl-359311b32d0e
 
 - 11.没有人在乎你用什么编程语言 - https://georgestocker.com/2021/03/28/no-one-gives-a-shit-what-programming-language-you-use/
 
 - 12.您的专业下降比您想象的要快（很多） - https://www.theatlantic.com/magazine/archive/2019/07/work-peak-professional-decline/590650/
 
 - 13.实际的OSI模型 - https://computer.rip/2021-03-27-the-actual-osi-model.html
 
 - 14.如何在Alpine Linux上配置静态IP地址 - https://www.cyberciti.biz/faq/how-to-configure-static-ip-address-on-alpine-linux/

## 码农桃花源--2021-03-30
### 文章分享
1 [内核中cgroup的工作机制](https://mp.weixin.qq.com/s/XXUtFbwkcLC7K7aydOSAwA)

2 [Serverless 与轻量级虚拟化 Firecracker](https://draveness.me/papers-firecracker/)

3 [“浅谈”CPU cache](http://www.wowotech.net/memory_management/458.html)

### 面试题
1 描述一下TCP是怎么发送文件的

2 MySQL为什么用B+数，不用二叉查找树、红黑树。

3 策略模式、装饰模式、适配器模式、代理模式

### 每日算法
lc315 计算右侧小于当前元素的个数 
https://leetcode-cn.com/problems/count-of-smaller-numbers-after-self/

## go中文网每日资讯--2021-03-29
一、Go语言中文网

1. [Go 那么多数值类型，应该选哪个？](https://mp.weixin.qq.com/s/zCWzCBnszJ032h5qchk8cA)

2. [RabbitMQ Go客户端教程3—发布/订阅](https://mp.weixin.qq.com/s/nsouScE11fVqelxznEdGhA)

二、亚军进化史

1. [Go技术日报(2021-03-28)——Golang 语言中的非类型安全指针](https://mp.weixin.qq.com/s/srsAMY7Ny1-ubU1Gqq32mw)

三、mohuishou

1. [Go可用性(二) 限流1: 令牌桶原理及使用](https://mp.weixin.qq.com/s/xDk54SE-JPOsokFg12OKfA)

四、微服务实践

1. [一文搞懂如何实现 Go 超时控制](https://mp.weixin.qq.com/s/5Q05d6OwvS-Zj-yNGwoh8A)

五、Go招聘

1. [Go Interview Weekly - 2021/03/28](https://mp.weixin.qq.com/s/iFNVOYHbULoN-J6cFDG7pg)

六、Golang梦工厂

1. [面试官：你能用Go写段代码判断当前系统的存储方式吗？](https://mp.weixin.qq.com/s/ffEsTpO-tyNZFR5navAbdA)

七、Golang技术分享

1. [Go中看似简单的WaitGroup源码设计，竟然暗含这么多知识？](https://mp.weixin.qq.com/s/V2x0Nw3Y8lZxHYJh_yQ0dQ)




## GOCN每日新闻--2021-03-29
1.Golang 语言中的非类型安全指针 https://mp.weixin.qq.com/s/MvULt7x0m4IBmz1bNzLvCQ

2.Goroutine 泄漏防治神器 goleak https://mp.weixin.qq.com/s/3iPqxiK2mf9Fl5CSZ9U7RQ

3.Go 实现的联合 GraphQL 网关 https://movio.co/blog/building-a-new-api-platform-for-movio/

4.我的 Go 最基础总结 https://towardsdev.com/learning-golang-9297e2eee49a

5.Go 的黑暗角落 https://rytisbiel.com/2021/03/06/darker-corners-of-go/

## gopherDaily--2021-03-29

- 1.通过系统建模探索Kubernetes网络模型 - https://dominik-tornow.medium.com/kubernetes-networking-22ea81af44d0

- 2.Goroutine泄漏防治神器: goleak - https://mp.weixin.qq.com/s/3iPqxiK2mf9Fl5CSZ9U7RQ

- 3.油管视频：在2021年开始将Go用于DevOps！- https://www.youtube.com/watch?v=7pLqIIAqZD4

- 4.Bramble简介：Go实现的联合GraphQL网关 - https://movio.co/blog/building-a-new-api-platform-for-movio/

- 5.构建一个超简约的Docker镜像以运行你的Go应用 - https://dev.to/chseki/build-a-super-minimalistic-docker-image-to-run-your-golang-app-33j0

- 6.2021年可观测性发展的预测 - https://blog.newrelic.com/technology/2021-tech-predictions

- 7.为什么我讨厌submodule - https://abildskov.io/2021/03/28/why-i-hate-submodules/

- 8.为什么小对象存储很重要 - https://blog.min.io/small_objects

- 9.在Kubernetes集群上以零停机时间发布和回滚更新 - https://www.fosstechnix.com/rolling-out-and-rolling-back-updates-with-zero-downtime-on-kubernetes-cluster/

- 10.将TFLite与Go和GANs模型一起使用的简短示例 - https://derekg.github.io/tflite.html

- 11.你应该知道的20个Linux监视命令 - https://www.fosstechnix.com/linux-monitoring-commands/

- 12.使用OpenAI的CLIP和Siren（隐式神经表示网络）生成文本到图像的简单命令行工具 - https://github.com/lucidrains/deep-daze


## 码农桃花源--2021-03-29
1.[CPU的缓存一致性问题及解决方案](https://mp.weixin.qq.com/s/PDUqwAIaUxNkbjvRfovaCg)

2 [优化https的手段](https://mp.weixin.qq.com/s/gGOuIvrDuCP057v8KhTgXQ)

3 [go并发编程常见的坑](https://mp.weixin.qq.com/s/FDV77dO9nwtPltmx5cB7Lw)

### 面试题
1 什么是阻塞队列？如何使用阻塞队列来实现生产者-消费者模型？

2 实现生产者、消费者模型，10个生产者，10个消费者，队列容量为30个

3 Chrome是多进程还是多线程的？为什么一个单页面崩溃会导致所有页面崩溃？

### 每日算法
lc329 矩形的最长递增路径
https://leetcode-cn.com/problems/longest-increasing-path-in-a-matrix/


## go中文网每日资讯--2021-03-28
一、Go语言中文网

1. [Go语言爱好者周刊：第 88 期 — 这次还会做错？](https://mp.weixin.qq.com/s/pgIoGnOd0CMPHFc4HD0xFA)

2. [Go函数调用惯例](https://mp.weixin.qq.com/s/f2Zu-sj-i4nO0wmmOBkoUg)

二、亚军进化史

1. [Go技术日报(2021-03-27)——2021后端开发人员学习指南](https://mp.weixin.qq.com/s/q-UaKpbhoQf0a1gE9_pbLA)

三、薯条的自我修养

1. [用汇编带你看Golang里到底有没有值类型、引用类型](https://mp.weixin.qq.com/s/7_p-T7WCW1YxalFmGl-ipg)

四、xueyuanjun

1. [Go 数据结构和算法篇（十二）：字符串匹配之 KMP 算法](https://mp.weixin.qq.com/s/Xs4_Q7d0tXbVhign_dii9A)

五、Golang语言开发栈

1. [Golang 语言中的非类型安全指针](https://mp.weixin.qq.com/s/MvULt7x0m4IBmz1bNzLvCQ)

六、网管叨bi叨

1. [使用 PDB 避免 Kubernetes 集群中断](https://mp.weixin.qq.com/s/BFeMRF4WmPMFbnut8LPYhA)


## GOCN每日新闻--2021-03-28
1.Go 序列化语义 https://alabeduarte.com/the-semantics-of-marshalling-in-go/

2.深入 Go nil https://blog.urth.org/2021/03/27/down-the-golang-nil-rabbit-hole/

3.ant: 功能丰富的 Go 爬虫框架 https://github.com/yields/ant

4.teller: 开源统一密钥管理服务 https://github.com/spectralops/teller

5.Walrus: 安全快速的可靠备份实现 https://github.com/Clivern/Walrus



## gopherDaily--2021-03-28
1.掉入Go nil坑 - https://blog.urth.org/2021/03/27/down-the-golang-nil-rabbit-hole/

2.Go、Rust、C++和Zig语言的生产力对比 - https://zserge.com/posts/better-c-benchmark/

3.编写简洁的Go代码 - https://github.com/Pungyeon/clean-go-article

4.Javascript开发人员学Go指南 - https://dev.to/cali3192/learning-go-from-javascript-4n6e

5.使用conda创建go虚拟环境 - https://ostechnix.com/create-golang-virtual-environments-using-conda-in-linux/

6.Go语言基础总结 - https://towardsdev.com/learning-golang-9297e2eee49a

7.在命令行终端测试打字水平的工具 - https://github.com/maaslalani/typer

8.Go MessagePack编解码库 - https://github.com/vmihailenco/msgpack

10.Kubernetes成为基础架构管理的新标准 - https://tanzu.vmware.com/content/blog/kubernetes-as-the-new-standard-for-infrastructure-management

11.任何人都可以用任何编程语言解决的实际项目列表 - https://github.com/karan/Projects

12.通过学习事物的工作原理来提高编程水平 - https://jvns.ca/blog/learn-how-things-work/

## go中文网每日资讯--2021-03-27
一、Go语言中文网

1. [对 Go 代码进行分析，常用这个技术：AST](https://mp.weixin.qq.com/s/gKnaHxoiBZrBMsXKsz2kvw)

2. [这可能是最容易理解的 Go Mutex 源码剖析**](https://mp.weixin.qq.com/s/BZvfNn_Vre7o2T8BZ4LLMw)

二、亚军进化史

1. [Go技术日报(2021-03-26)——Go 可用性(一) 隔离设计](https://mp.weixin.qq.com/s/4S_tbGNORvFD9NcqOQJ3eQ)

三、InfoQ

1. [一年增加1.2w星，Dapr能否引领云原生中间件的未来？](https://mp.weixin.qq.com/s/KSln4MPWQHICIDeHiY-nWg)

四、光华路程序猿

1. [阅读go源码,你需要了解这几个编译器指示](https://mp.weixin.qq.com/s/HcGFFrjWkBDbwxBKfjn9Dg)

五、Go招聘

1. [360竞对招Go，居然还不加班](https://mp.weixin.qq.com/s/J6ydS_p8KdZ6t8zgnZCV1Q)

## GOCN每日新闻--2021-03-27
1.Intellij 插件新秀【CommentShell】， 让你的注释运行起来 https://gocn.vip/topics/11835
 
2.面对不可避免的故障，我们造了一个 “上帝视角” 的控制台 https://gocn.vip/topics/11837

3.Go 存储基础 — 文件 IO 的姿势 https://mp.weixin.qq.com/s/EkcUJns0gDe8mNgrRMj8Eg

4.大红大紫的 Golang 真的是后端开发中的万能药吗？ https://bbs.huaweicloud.com/blogs/250592

5.Go 可用性 (一) 隔离设计 https://mp.weixin.qq.com/s/9NtAlIh6bfSlA2ILqIzdDQ



## gopherDaily--2021-03-27
1.使用Go实现可用select监听的队列 - https://mp.weixin.qq.com/s/bV097lsHfdIaJFLYjaYYFA

2.Go语言marshal机制探秘 - https://alabeduarte.com/the-semantics-of-marshalling-in-go/

3.Go module的日常 - https://jayconrod.com/posts/118/life-of-a-go-module

4.使用Go进行模块化编程- 第1部分：在init()中注册 - https://entropy.cat/modular-programming-in-go-part-1-the-register-on-init-pattern/

5.在k3s上使用rook - https://itnext.io/using-rook-on-a-k3s-cluster-8a97a75ba25e

6.使用Go开发一个简单的以太坊智能合约 - https://towardsdev.com/creating-a-simple-ethereum-smart-contract-in-golang-138b9439f64e

7.2021流行的无服务优先是什么 - https://thenewstack.io/what-is-serverless-first-in-2021/

8.使用Go和WebAssembly构建渐进式Web应用 - https://github.com/maxence-charriere/go-app

9.teller: 开发人员使用的密码管理器 - https://github.com/spectralops/teller

10.go实现的web爬虫 - https://github.com/yields/ant

11.2021后端开发人员学习指南 - https://twitter.com/dermayank/status/1375381056283496451

## 码农桃花源--2021-03-27
### 优质文章汇总
1. [内核如何管理内存](https://manybutfinite.com/post/how-the-kernel-manages-your-memory/)

2. [为什么TCP/IP数据包需要分片](https://draveness.me/whys-the-design-tcp-segment-ip-packet/)

3. [系统调用的三种方式及性能开销分析](https://draveness.me/whys-the-design-syscall-overhead/)

4. [Go语言调度器之非main goroutine的退出](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483789&idx=1&sn=182631d0d1390a57daea7293133d9ff6&scene=19#wechat_redirect)

5. [Go goroutine调度策略](https://mp.weixin.qq.com/s?_biz=MzU1OTg5NDkzOA==&mid=2247483801&idx=1&sn=ef7f872afccf148661cbd5a3d3b5b0a2&scene=19#wechat_redirect)

### 面试问题
1. epoll单次收包没有收完怎么处理？

2. 讲一下redis的线程模型

3. 多机redis如何保证数据一致性

4. 页高速缓存的作用？怎样保证缓存一致性

5. zerocopy的实现机制

6. linux的内核线程、轻量级进程、用户线程

7. 手写atoi函数

8. linux消息队列的本质

9. 为什么goroutine没有id

10. g0到main goroutine的转换过程

11. 非main goroutine是如何返回到goexit函数的

12. mcall函数如何从用户goroutine切换到g0继续执行

13. 什么时候会发生调度？

14. 使用什么策略来挑选下一个进入运行的goroutine

15. 如何把挑选出来的goroutine放到CPU上运行

## go中文网每日资讯--2021-03-26

一、#公众号：Go语言中文网

1. Go 构建 CLI 实践: 在 ETL 中使用扇出模式 https://mp.weixin.qq.com/s/4tiiZzr_b4OucAQLFXwLAQ

2. RabbitMQ Go教程2——工作队列 https://mp.weixin.qq.com/s/4Jln0-2kMi7bsTdl0qoTRA

二、#公众号：亚军进化史

1. Go技术日报(2021-03-25)——最容易理解的 Go Mutex 源码剖析 https://mp.weixin.qq.com/s/TpIUIS5NS_Ndj4XhuCNNuA

三、#公众号：Gopher指北

1. 有趣！一行代码居然无法获取请求的完整URL https://mp.weixin.qq.com/s/hn3pfcGBG7HyPZnCwTmMhA

四、#公众号：腾讯云CDN

1. 专题 | 深挖腾讯云CDN QUIC的性能优化 https://mp.weixin.qq.com/s/cZfZEtnpizmxa66ni5wHnQ

五、#公众号：腾讯技术工程

1. 快速实现一个分布式定时器 https://mp.weixin.qq.com/s/ggPftQm2ewGOJwlRDQGgDQ

六、#公众号：mohuishou

1. Go可用性(一) 隔离设计 https://mp.weixin.qq.com/s/9NtAlIh6bfSlA2ILqIzdDQ

七、#公众号：MoeLove

1. Docker 构建镜像实践及原理（下篇） https://mp.weixin.qq.com/s/TDQxbB0yFzd5PleS3knnEg

八、#公众号：k8s技术圈

1. Pod 拓扑分布约束使用及调度原理 https://mp.weixin.qq.com/s/xyqqCo0qRgAR7vd6NzeQQQ

九、#公众号：奇伢云存储

1. Go 存储基础 — 文件 IO 的姿势 https://mp.weixin.qq.com/s/EkcUJns0gDe8mNgrRMj8Eg

十、#公众号：脑子进煎鱼了

1. 难以驾驭的 Go timer，一文带你参透计时器的奥秘 https://mp.weixin.qq.com/s/gxX-q2EvgWZEWe-deRITSw

## GOCN每日新闻--2021-03-26 
1. Golang 号称最快的 Json 解析器速度可达 5623ns/op   https://my.oschina.net/u/3081398/blog/4997334

2. Go 语言交叉编译工具 gox   https://juejin.cn/post/6844903865175769102

3. go os/exec 简明教程  https://colobu.com/2020/12/27/go-with-os-exec/

4. Go 构建 CLI 实践: 在 ETL 中使用扇出模式  https://mp.weixin.qq.com/s/4tiiZzr_b4OucAQLFXwLAQ

5. 真正的 Websocket 百万连接，以及 HTTPS 支持  https://gocn.vip/topics/11815

## gopherDaily--2021-03-26
1.Go语言的“黑暗角落”：盘点学习Go语言时遇到的那些陷阱[译] - https://t.zsxq.com/UR7a2vB

2.Go播客：Go设计哲学 - https://changelog.com/gotime/172

3.油管视频：如何在Go中使用OpenTelemetry开始分布式追踪 - https://www.youtube.com/watch?v=yQpyIrdxmQc

4.使用Go构建一个简单的区块链系列 - https://dev.to/nheindev/build-the-hello-world-of-blockchain-in-go-bli

5.IstioCon2021 回顾及开源项目 GetIstio 介绍视频回顾 - https://mp.weixin.qq.com/s/MuZdLXHUC2HcKdl40GmZuw

6.Dapr能否引领云原生中间件的未来？ - https://mp.weixin.qq.com/s/KSln4MPWQHICIDeHiY-nWg

7.现代应用服务器基础 - https://itnext.io/modern-application-server-basics-58a9aa8e9600

8.wayland协议的go实现 - https://github.com/rajveermalviya/go-wayland

9.sqlite不是一个玩具数据库 - https://antonz.org/sqlite-is-not-a-toy-database/

10.用于k8s pod间流量sniff的kubectl插件 - https://github.com/eldadru/ksniff

11.finops简介 - https://dzone.com/articles/a-short-introduction-to-finops


## GOCN每日新闻--2021-03-26
### 文章分享
1. [Go goroutine调度策略](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483801&idx=1&sn=ef7f872afccf148661cbd5a3d3b5b0a2&scene=19#wechat_redirect)

2. [go和syscall](https://mp.weixin.qq.com/s/YPiYNPa3xVD9Il1HeB5pTw)

3. [go mod 七宗罪](https://mp.weixin.qq.com/s/CBiebXjBcik2pHQnbnB51A)

### 面试题
1. 什么时候会发生调度？

2. 使用什么策略来挑选下一个进入运行的goroutine

3. 如何把挑选出来的goroutine放到CPU上运行

### 每日算法
lc1012 至少有 1 位重复的数字

## go中文网每日资讯--2021-03-25 

一、Go语言中文网

1. [终于来了！go tip已经可以使用泛型了](https://mp.weixin.qq.com/s/U781UlKO_30wOaufngKj3Q)

2. [为什么 Kubernetes 要替换 Docker](https://mp.weixin.qq.com/s/4ke9F5h__kG9BoGnzGDoUg)

3. [RabbitMQ Go客户端教程1——HelloWorld](https://mp.weixin.qq.com/s/KSr-soJ9Ls-GWyMdtiPVVA)

二、亚军进化史

1. [Go技术日报(2021-03-24)——在业务系统中寻求技术含量](https://mp.weixin.qq.com/s/jB_6aPmCz7vy48LSCo1oPA)

三、董泽润的技术笔记

1. [聊聊并发安全](https://mp.weixin.qq.com/s/8qXfm0UqK4R1tJyK0_zYQg)

四、转角遇到GitHub

1. [又一本在线免费的 Go 语言图书](https://mp.weixin.qq.com/s/Z01xRLy9dMVbHpejKN1RpA)

五、多颗糖

1. [【MIT 6.824】学习笔记 5: 2021 Raft 实现细节](https://mp.weixin.qq.com/s/djjfz2oGosoj7fChEe9AdQ)

六、Golang技术分享

1. [Go函数闭包底层实现](https://mp.weixin.qq.com/s/kfNcrLZlb5LRi6ILsohwUA)

七、真没什么逻辑

1. [Google 数据中心的电力超售 · OSDI &#39;20](https://mp.weixin.qq.com/s/JdS8ZH0g_Elr1Q0i1PKWlw)

八、HHFCodeRv

1. [这可能是最容易理解的 Go Mutex 源码剖析](https://mp.weixin.qq.com/s/irXUkd9CZMInTUTu7pbriQ)

九、CloudNativeCommunity

1. [文末赠书 | 深度解析DDD中台和微服务设计](https://mp.weixin.qq.com/s/038RfEa5NgUSex0OTFQOkw)



## GOCN每日新闻--2021-03-25 

1.Go Mysql Driver 集成 Seata-Golang 解决分布式事务问题 https://gocn.vip/topics/11831

2.对 Go 1.16 io/fs 设计的第一感觉：得劲儿 https://gocn.vip/topics/11825

3.深入研究 Go interface 底层实现 https://halfrost.com/go_interface/

4.内存管理设计精要 https://draven.co/system-design-memory-management/

5.Go Buffer 重用，避免频繁内存分配 https://ningto.com/post/36D5C2DAD3C2BEBD5F601A7A2ED43188


## gopherDaily--2021-03-25
1.Go免费电子书：《Practical Go lession》- https://www.practical-go-lessons.com/

2.使用Go从头构建一个BitTorrent客户端 - https://blog.jse.li/posts/torrent/

3.使用Go Ebiten重写老旧的flash游戏 - https://github.com/TheTophatDemon/Feta-Feles-Remastered

4.Go中常见的反模式 - https://deepsourcehq.hashnode.dev/common-anti-patterns-in-go

5.令人难以置信的快速代理检查器和IP旋转器 - https://github.com/kitabisa/mubeng

6.Cytora公司Go学术工程blog - https://medium.com/engineering-at-cytora/cytora-golang-academy-part-one-e736944b28e5

7.惠普开源structex: Go结构注释，支持编码和解码；支持位域打包，自描述布局参数和对齐方式 - https://github.com/HewlettPackard/structex

8.Go开发者合同费率 - https://hetvi-samani.medium.com/golang-developer-contract-rates-f3d2fae8088

9.构建浏览器推送通知服务：长轮询和Web套接字协议 - https://medium.com/swlh/building-a-browser-push-notification-service-http-long-polling-and-the-web-socket-protocol-5e83cd1420c1

10.通往Go高手之路：单元测试 - https://medium.com/digio-australia/road-to-go-pro-unit-test-69591a553412

11.go stacktrace信息输出库的对比 - https://dev.to/stevenacoffman/comparison-golang-stacktrace-error-library-output-2fph


## 码农桃花源--2021-03-25
### 文章分享
1. [Go语言调度器之非main goroutine的退出](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483789&idx=1&sn=182631d0d1390a57daea7293133d9ff6&scene=19#wechat_redirect)

2. [go mutex源码剖析](https://mp.weixin.qq.com/s/irXUkd9CZMInTUTu7pbriQ)

3. [为什么goroutine没有id](https://mp.weixin.qq.com/s/qFAtgpbAsHSPVLuo3PYIhg)


### 面试题
1. 为什么goroutine没有id

2. g0到main goroutine的转换过程

3. 非main goroutine是如何返回到goexit函数的

4. mcall函数如何从用户goroutine切换到g0继续执行

### 每日算法
lc871	最低加油次数


## go中文网每日资讯--2021-03-24 


一、Go语言中文网

1. [Go 中基于 IP 地址的 HTTP 请求限流](https://mp.weixin.qq.com/s/aj_hULmeqy3whILr2ytECQ)

2. [图解unicode、utf8和utf8mb4](https://mp.weixin.qq.com/s/gmKGAFBNU97BnQUFZRv1_w)

二、亚军进化史

1. [Go技术日报(2021-03-23)——context使用不当引发的一个bug](https://mp.weixin.qq.com/s/tRhnEuguO5YqiUrmYs1WEw)

三、腾讯技术工程

1. [MySQL 深入学习总结](https://mp.weixin.qq.com/s/sRFmW57KUY3yyyRkyw0L4A)

四、TechPaper

1. [在业务系统中寻求技术含量](https://mp.weixin.qq.com/s/acTlfzQjYf7_hq46R-ZBPg)

五、CloudNativeCommunity

1. [专访 CNCF 大使王炜：让云原生开发回归原始而又简单](https://mp.weixin.qq.com/s/kOjfCPhHRpU1Th6C-lItcw)

六、k8s技术圈

1. [Thanos Receive 实现 Prometheus (几乎)无状态化](https://mp.weixin.qq.com/s/py5BYM5rFdeN6sTYnzsyug)

七、xueyuanjun

1. [Go 数据结构和算法篇（十）：二分查找的变形版本](https://mp.weixin.qq.com/s/bEJ6Ihc8jNFPd7sUmupjEw)

八、脑子进煎鱼了

1. [再见 Go 面试官：GMP 模型，为什么要有 P？](https://mp.weixin.qq.com/s/an7dml9NLOhqOZjEGLdEEw)

九、Go招聘

1. [50k的Go招聘是什么要求？](https://mp.weixin.qq.com/s/kKEduz_MEnVpA_QQ0AzxCA)

## GOCN每日新闻--2021-03-24 
1.网络流量抓包库 gopacket 介绍 https://mp.weixin.qq.com/s/ZutgJ40nug_9bNsZj1u9Kw

2.需要注意的 GO 网络包默认设置 https://martin.baillie.id/wrote/gotchas-in-the-go-network-packages-defaults/

3.基于 Golang 的云原生日志采集服务设计与实践 https://mp.weixin.qq.com/s/fHJ10roQrwIwgm_urF9TyQ#at

4.再见 Go 面试官：GMP 模型，为什么要有 P？ https://mp.weixin.qq.com/s/an7dml9NLOhqOZjEGLdEEw

5.来了！Go 官方 Slice 教程图解版 https://mp.weixin.qq.com/s/GLEdRAOG24I38Zn9nh8F-Q


## gopherDaily--2021-03-24
1.Go网络相关包默认机制下的那些“坑” - https://martin.baillie.id/wrote/gotchas-in-the-go-network-packages-defaults/

2.我为什么爱上Go - https://rejmank.com/post/why-i-started-to-fall-in-love-with-go

3.更好的Go logging - https://codeengineered.com/blog/2021/better-go-logging/

4.何实现Go JWT身份验证和授权 - https://www.bacancytechnology.com/blog/golang-jwt

5.那些年我們追的 Goroutine Pool - https://medium.com/17media-tech/%E9%82%A3%E4%BA%9B%E5%B9%B4%E6%88%91%E5%80%91%E8%BF%BD%E7%9A%84-goroutine-pool-e8d211757ee

6.2021，属于Golang和Gopher的全新纪元 - https://mp.weixin.qq.com/s/zAnXPdd5LvL1EsjNkC21vg

7.《Go in action》联合作者William Kennedy发布了开源书籍《Ultimate Go Notebook》- https://docs.google.com/document/d/1QQq8Yf90ar59OUQM6qRDS6Bwk5hfOCpcqw_WUX43YOg/edit

8.2021年云原生的10大预测-DevOps大会主题演讲 - https://www.oicheryl.com/2021/03/23/10-predictions-for-cloud-native-in-2021-the-devops-conference/

9.AWS Lambda：每种语言的冷启动持续时间 - https://mikhail.io/serverless/coldstarts/aws/languages/

10.MinIO推出了连续可用性和主动-主动存储桶复制 - https://blog.min.io/active-active-replication/

11.Rust安全编程 - https://iris-project.org/pdfs/2021-rustbelt-cacm-final.pdf

12.来自贝尔实验室的Plan 9 - https://www.bell-labs.com/institute/blog/plan-9-bell-labs-cyberspace/


## 码农桃花源--2021-03-24
### 文章分享
1 [mongoDB高可用架构剖析](https://mp.weixin.qq.com/s/jLsviuQ0wCcsmkskXSFdEQ)

2 [为什么mongoDB使用B树/LSM树，而不是B+树](https://blog.csdn.net/weixin_41987908/article/details/105255119)

3 [系统调用的三种方式及性能开销分析](https://draveness.me/whys-the-design-syscall-overhead/)

### 面试题
1.linux的内核线程、轻量级进程、用户线程

2.手写atoi函数

3.linux消息队列的本质

### 每日算法
lc83 删除链表重复元素 https://leetcode-cn.com/problems/remove-duplicates-from-sorted-list/


## go中文网每日资讯--2021-03-23 

一、Go语言中文网

1. [吐槽 Go 依赖管理：Go Module 之痛](https://mp.weixin.qq.com/s/p1iCWg__JoFsHv8oDtyL0g)

2. [使用Prometheus搞定微服务监控](https://mp.weixin.qq.com/s/1OCW38T2xW5D5Las-Nl6uw)

3. [context使用不当引发的一个bug](https://mp.weixin.qq.com/s/Lp3sToRKuk79yzDdPf9-eQ)

二、亚军进化史

1. [Go技术日报(2021-03-22)——Go 泛型尝鲜](https://mp.weixin.qq.com/s/0q_WYnYim172yL_t49swJg)

三、云原生技术爱好者社区

1. [Service Mesh与Istio简述](https://mp.weixin.qq.com/s/-QB4p4w0O9p5_FPmlk0B-Q)

四、架构之家

1. [基于Golang的云原生日志采集服务设计与实践](https://mp.weixin.qq.com/s/fHJ10roQrwIwgm_urF9TyQ)

五、程序员牛不牛

1. [我还不懂什么是分布式事务](https://mp.weixin.qq.com/s/e6QMPfobdf0jDX8CX4vQrA)

六、k8s技术圈

1. [Kubernetes master 节点快炸了!!!](https://mp.weixin.qq.com/s/dUzOpecspViYTbf0JHutHA)

七、mohuishou

1. [Go并发编程(十二) Singleflight](https://mp.weixin.qq.com/s/tORa8F7jxCUvF97dujHx0Q)

八、CloudNativeCommunity

1. [加入 Istio 官方翻译组织的历程记录](https://mp.weixin.qq.com/s/sdJ5tDI-QqXqFkvQzEOoOA)

九、真没什么逻辑

1. [集群管理系统 Mesos 的设计原理 · NSDI &#39;11](https://mp.weixin.qq.com/s/0euIwN7r-KH0S8Yb_wN35g)

十、Go招聘

1. [Go 泛型尝鲜](https://mp.weixin.qq.com/s/jQ3BIJq3Xyi_KmyxmVZMRA)

2. [成都 Go 是要起飞吗？最近职位真不少](https://mp.weixin.qq.com/s/AtvFknQPYGjAs4lFCmwVKw)

## GOCN每日新闻--2021-03-23 

1.手撸 golang GO 与微服务 ES-CQRS 模式之 1 https://segmentfault.com/a/1190000039691281

2.Go 语言 GC 实现原理即源码分析 https://mp.weixin.qq.com/s/yU0N_KOw34BHkyp1VdTMqA 
3.Go 并发编程 (十二) Singleflight https://mp.weixin.qq.com/s/tORa8F7jxCUvF97dujHx0Q

4.对 Go 1.16 io/fs 设计的第一感觉：得劲儿！ https://mp.weixin.qq.com/s/_pUtGQSl_oSRnmmfROJ6ZQ

5.go 语言 copy-on-write 技术实现 https://mp.weixin.qq.com/s/OoWZnJQaQ5xnzLDFsig_SQ



## gopherDaily--2021-03-23
1.Go语言的黑暗角落 - https://rytisbiel.com/2021/03/06/darker-corners-of-go/

2.Go语言的生态系统 - https://henvic.dev/posts/go/

3.Go并发代码评审checklist - https://github.com/code-review-checklists/go-concurrency

4.软件事务存储：通往无锁编程天堂的阶梯？ - https://medium.com/@talhof8/software-transactional-memory-a-stairway-to-lock-free-programming-heaven-9ca1f4dce23f

5.Apache Kafka和Go：入门 - https://medium.com/swlh/apache-kafka-with-golang-227f9f2eb818

6.一个简单的Go自动“重试器” - https://adityarama1210.medium.com/go-background-automatic-retry-function-d6989af3bbf7

7.一次Go应用的性能优化实践 - https://betterprogramming.pub/an-optimization-exercise-in-golang-43fea807441d

8.Go实现的全功能socks5服务器 - https://github.com/realzhangliu/socks5-go

9.在命令行终端查看github状态 - https://github.com/irevenko/octotui

10.使用k8s和concourse-ci构建持续交付流水线 - https://blog.alterway.fr/en/building-a-continious-deployment-pipeline-with-kubernetes-and-concourse-ci.html

## 码农桃花源--2021-03-23
### 文章分享
1 [linux下一种高效多定时器](https://blog.csdn.net/u014026685/article/details/821803722)

2 [为什么linux需要swapping](https://draveness.me/whys-the-design-linux-swapping/)

3 [为什么TCP/IP数据包需要分片](https://draveness.me/whys-the-design-tcp-segment-ip-packet/)

### 面试题
1 页高速缓存的作用？怎样保证缓存一致性

2 zerocopy的实现机制

### 每日算法
lc815 公交路线 https://leetcode-cn.com/problems/bus-routes/

## go中文网每日资讯--2021-03-22 

一、Go语言中文网

1. [微软真给力：出了 Go 语言教程，免费，而且是中文版](https://mp.weixin.qq.com/s/sgqXwqvn2HpYwWnAqmB63Q)

2. [发现 go version 的一个另类用法：你肯定想不到](https://mp.weixin.qq.com/s/IjTQ856JAkHQFM3n3HILnA)

3. [论配置化系统的配置](https://mp.weixin.qq.com/s/Kcg6wQyS79PD9dHWlJT-SA)

二、亚军进化史

1. [Go技术日报(2021-03-21)——Go 语言 GC 实现原理即源码分析](https://mp.weixin.qq.com/s/23XjrSd22HMhNe1ruDCn1A)

三、polarisxu

1. [RedMonk 编程语言排行榜，说 Go 正走向衰退，你认可吗？](https://mp.weixin.qq.com/s/PHG53qPe2ZLYIo1_0crv_w)

四、k8s技术圈

1. [Kubectl 源码分析](https://mp.weixin.qq.com/s/yu06FcezAn4srdQNkCWbhw)

2. [运维开发工程师 - 长桥证券](https://mp.weixin.qq.com/s/Rg8uCso3azJlRFln8qCtNg)

五、luozhiyun很酷

1. [Go语言GC实现原理及源码分析](https://mp.weixin.qq.com/s/W5O_Pnrt3NPcaErlnPmIZQ)

六、CloudNativeCommunity

1. [云原生关乎文化，而不是容器](https://mp.weixin.qq.com/s/GQZODViNUnjDjLZN5R0RvA)

七、脑子进煎鱼了

1. [Go 群友提问：进程、线程都有 ID，为什么 Goroutine 没有 ID？](https://mp.weixin.qq.com/s/qFAtgpbAsHSPVLuo3PYIhg)

八、Go招聘

1. [真区块链项目招Go，就看你来不来吧](https://mp.weixin.qq.com/s/vfFKtajHUUwqGmGjWdZE2Q)

九、鸟窝

1. [Go 泛型尝鲜](https://colobu.com/2021/03/22/try-go-generic/)
## GOCN每日新闻--2021-03-22

1.分布式任务 + 消息队列框架 go-queue https://gocn.vip/topics/11813

2.Go 泛型尝鲜 https://colobu.com/2021/03/22/try-go-generic/

3.Go 群友提问：进程、线程都有 ID，为什么 Goroutine 没有 ID？https://mp.weixin.qq.com/s/qFAtgpbAsHSPVLuo3PYIhg

4.用 prometheus 监控 golang 程序 https://gabrieltanner.org/blog/collecting-prometheus-metrics-in-golang

5.golang 语言临时对象池 - sync.Pool https://mp.weixin.qq.com/s/QH_IW-hUfxs2MxkLEBiexA#at



## gopherDaily--2021-03-22
- 1.编写复杂并发的表驱动单元测试 - https://1pkg.github.io/posts/writing_complex_concurrent_table_driven_tests/
- 2.使用ent生成完全可用的gRPC服务器 - https://entgo.io/blog/2021/03/18/generating-a-grpc-server-with-ent/
- 3.使用Rust和Go通过HTTP服务单个文件 - https://vadosware.io/post/serving-a-single-file-over-http-with-rust-and-go/
- 4.经典视频：驯服作为“一等公民”的函数 - https://www.youtube.com/watch?v=5buaPyJ0XeQ&t=980s
- 5.Go终端字符串样式库，支持多种平台 - https://github.com/jwalton/gchalk
- 6.Go面试问题大全 - https://github.com/shomali11/go-interview
- 7.你应该知道的50个有用的git命令的速查表 - https://www.freecodecamp.org/news/git-cheat-sheet/
- 8.CockroachDB热爱开源 - https://www.cockroachlabs.com/blog/cockroachdb-%EF%B8%8F-open-source/
- 9.将任何脚本或程序的输出放入您的macOS菜单栏中 - https://github.com/matryer/xbar
- 10.替代SOLID的新设计原则：CUPID - https://dannorth.net/2021/03/16/cupid-the-back-story/
- 11.开源的类GPT2和GPT3的模型 - https://github.com/EleutherAI/gpt-neo/
- 12.科普MLOps - https://thenewstack.io/what-is-mlops/

## 码农桃花源--2021-03-22
### 文章分享
1 [linux的页缓存和文件IO](https://blog.csdn.net/GDJ0001/article/details/80136364)

2 [内核如何管理内存](https://manybutfinite.com/post/how-the-kernel-manages-your-memory/)

3 [互斥锁，自旋锁，悲观锁，乐观锁总结](https://blog.csdn.net/qq_34827674/article/details/108608566)

### 面试题
1 epoll单次收包没有收完怎么处理？

2 讲一下redis的线程模型

3 多机redis如何保证数据一致性

### 每日算法
lc143 重排链表 https://leetcode-cn.com/problems/reorder-list/


## go中文网每日资讯--2021-03-21 

一、Go语言中文网

1. [Go语言爱好者周刊：第 87 期 — 螃蟹会夹土拨鼠吗？](https://mp.weixin.qq.com/s/4HI78Yd1ENVFCWHCESlPBg)

2. [Go 笔试题精选一： 25 道选择题](https://mp.weixin.qq.com/s/akJLEx_pllOFvR27ICl2mQ)

3. [Go垃圾回收系列之十：实战一例频繁GC的性能问题](https://mp.weixin.qq.com/s/G46cYgG4NKuGh54hai0yNw)

二、亚军进化史

1. [Go技术日报(2021-03-20)——破解 50 大 Go 语言面试题](https://mp.weixin.qq.com/s/CRC9LYMl19yxiyiFcSL3kQ)

三、luozhiyun很酷

1. [Go语言GC实现原理即源码分析](https://mp.weixin.qq.com/s/yU0N_KOw34BHkyp1VdTMqA)

四、奇伢云存储

1. [图解 MongoDB Sharding 读写](https://mp.weixin.qq.com/s/SQ9IakXtz-gMXdmLIk_XnQ)

五、k8s技术圈

1. [Thanos Receive 模块介绍](https://mp.weixin.qq.com/s/ql5VJPiBO7kpi8BCKdfK0A)

六、新亮笔记

1. [管理认知（三）](https://mp.weixin.qq.com/s/nxg8hxe8pBCiPJ8PbFw4Nw)

七、Go招聘

1. [Go Interview Weekly - 2021/03/21](https://mp.weixin.qq.com/s/tK32DJ3JooJJvMkN3VhNcw)

八、Golang Weekly

1. [Golang Weekly Issue 354: March 19, 2021](https://golangweekly.com/issues/354)

2. [Awesome Go Newsletter - Issue 252, Mar 18, 2021 | LibHunt](https://go.libhunt.com/newsletter/252)
## GOCN每日新闻--2021-03-21
1.我用 go-zero 一周实现了一个中台系统，已开源！ https://gocn.vip/topics/11806

2.TiDB Operator 源码阅读 (二) Operator 模式 https://gocn.vip/topics/11803

3.GO 实现一个简单的博客 https://dev.to/mark_saward/a-simple-blog-in-go-2dhp

4.在 Go PT 中构建区块链工作量证明 https://dev.to/nheindev/building-a-blockchain-in-go-pt-ii-proof-of-work-eel

5.用 Go 构建一个 SQL 解析器 https://blog.51cto.com/15127564/2666790

## gopherDaily--2021-03-21
- 1.对Go 1.16 io/fs设计的第一感觉：得劲儿 -  https://t.zsxq.com/aImIUvr
- 2.2020年Go开发者调查结果(译) - https://mp.weixin.qq.com/s/4eGn0rdiaDQakodX9cAm9A
- 3.使用go module管理私有仓库依赖 - https://1pkg.github.io/posts/private_repository_dependency_management_with_gomod/
- 4.Go实现的极简blog系统 - https://www.josephspurrier.com/polar-bear-blog
- 5.在Go中强制使用构造函数 - https://ranfdev.com/blog/enforcing-use-of-constructor-in-go/
- 6.使用Go构建基于CLI的文件重命名工具 - https://medium.com/swlh/building-cli-based-file-renaming-tool-with-golang-e3c6a16eedf6
- 7.在Go中使用高级RabbitMQ客户端 - https://dev.to/qvault/using-a-high-level-rabbitmq-client-in-golang-4mcl
- 8.结构化并发编程与可能有害的go语句 - https://vorpus.org/blog/notes-on-structured-concurrency-or-go-statement-considered-harmful/
- 9.将k8s通信迁移为gRPC - https://blog.cloudflare.com/moving-k8s-communication-to-grpc/
- 10.如何开始为开源项目做贡献 - https://towardsdatascience.com/how-to-start-contributing-to-open-source-projects-10d0517b13d8
- 11.Kubernetes Pod如何获取IP地址 - https://ronaknathani.com/blog/2020/08/how-a-kubernetes-pod-gets-an-ip-address/
- 12.curl 23岁了 - https://daniel.haxx.se/blog/2021/03/20/curl-is-23-years-old-today/





## go中文网每日资讯--2021-03-20 


一、Go语言中文网

1. [腾讯重磅发布：Go已经成为其第二大编程语言](https://mp.weixin.qq.com/s/dCMpjbADtwbfkj4gwSsI_w)

2. [map 和 switch 如何选？match 又是什么？](https://mp.weixin.qq.com/s/tUM6SPjtLF0IXOirlC-f4g)

3. [删除文件为啥磁盘依然爆满](https://mp.weixin.qq.com/s/lN7KBL4YMR6LAr9f5j7-pw)

二、亚军进化史

1. [Go技术日报(2021-03-19)——Go 笔试题精选 二: 25 道选择题](https://mp.weixin.qq.com/s/g53da--Z4eMOV_s9fFEYeA)

三、奇伢云存储

1. [全面剖析 MongoDB 高可用架构](https://mp.weixin.qq.com/s/jLsviuQ0wCcsmkskXSFdEQ)

四、码农桃花源

1. [一些 eink 设备](https://mp.weixin.qq.com/s/5Urkzb39v_7dzCol25JyWg)

五、Go夜读

1. [【预告】Go 夜读三周年直播活动](https://mp.weixin.qq.com/s/bQfVh_ntQJKI2tIdmV9UyA)

六、薯条的自我修养

1. [论配置化系统的配置](https://mp.weixin.qq.com/s/B4eXu_2ERlIdPSgNOQODXw)

七、xueyuanjun

1. [Go 数据结构和算法篇（八）：快速排序](https://mp.weixin.qq.com/s/dMwnzF_igNv_SeeaHoNlWA)

八、TechPaper

1. [分布式快照](https://mp.weixin.qq.com/s/Wgm-NY4LIGZUNT4DMYPKFQ)
## gopherDaily--2021-03-20 
- 1.破解50大Go语言面试题 - https://dev.to/educative/crack-the-top-50-golang-interview-questions-384i
- 2.使用go开发rest server: 第五部分中间件 - https://eli.thegreenplace.net/2021/rest-servers-in-go-part-5-middleware/
- 3.Go播客：聊聊代码生成 - https://changelog.com/gotime/170
- 4.Terraform命令行工具 - https://github.com/awslabs/tecli
- 5.Go性能剖析笔记 - https://github.com/DataDog/go-profiler-notes
- 6.mage是我最喜欢的Make工具 - https://carolynvanslyck.com/blog/2021/01/mage-is-my-favorite-make/
- 7.使用Go设计和实现websocket server - https://medium.com/geekculture/designing-a-websocket-server-in-golang-reformers-golang-implementation-strategy-bcd2dc9e368e
- 8.使用go实现的实时kv数据库实战 - https://iyer.ai/realtime-db-in-golang/
- 9.使用Swagger开发rest api，支持热加载 - https://medium.com/swlh/build-a-rest-api-in-golang-with-swagger-and-hot-reload-of-everything-6247a8ae8618
- 10.argo cd v2.0 rc1发布 - https://blog.argoproj.io/argo-cd-v2-0-rc1-is-here-f7d21ff1aa64
- 11.经典视频回顾：linux容器的未来 by docker创始人 -  https://www.youtube.com/watch?v=9xciauwbsuo


## GOCN每日新闻--2021-03-20 
1.依赖注入工具代码生成器 wire https://gocn.vip/topics/11802

2.使用 mux 改变中间件的行为 https://dev.to/juanpabloaj/changing-the-middleware-behavior-with-mux-1818

3.Golang 变量遮蔽——Shadowing https://juejin.cn/post/6941284330425548807

4.我如何在 go 中 mock 单元测试 https://dev.to/chseki/how-i-mock-unit-tests-in-golang-3dcp

5.50 个基础面试问题 https://dev.to/educative/crack-the-top-50-golang-interview-questions-384i

## 码农桃花源--2021-03-20
### 优质文章汇总

1. [编译原理概述](https://draveness.me/golang/docs/part1-prerequisite/ch02-compile/golang-compile-intro/)

2. [分布式系统底层原理](https://mp.weixin.qq.com/s/KKrxuVCrjlXXWMPTXQ-fvA)

3. [超大文件http断点续传的实现](https://blog.csdn.net/ababab12345/article/details/80490621)

4. [Go语言调度器之创建main goroutine](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483776&idx=1&sn=a74df39487b4ff22073e97eeb59d48ed&scene=19#wechat_redirect)

5. [Go语言调度器之调度main goroutine](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483783&idx=1&sn=1128dbd7794d7d53c37abab94771a7d7&scene=19#wechat_redirect)

### 面试问题

1. epoll与select的优缺点？

2. http请求的处理过程

3. 事务的隔离级别 底层是如何实现的

4. TCP收到RST报文的几种情况？

5. 说说半连接队列和 SYN Flood 攻击的关系

6. 介绍一下 TCP 报文头部的字段

7. 如果已经建立了TCP连接，但是Client端突然出现故障了怎么办？

8. server端出现大量TIME_WAIT状态的连接的原因

9. 什么时候会抢占P

10. 当在M上运行的goroutine发生阻塞时，会怎么工作

11. 多个线程与多个M如何一一对应？

12. 汇编 操作对比 mov %rdx, %rax   与  mov %rdx, (%rax)

13. 为什么在创建goroutine的newproc函数要传入参数大小

14. 什么时候调用的main函数？

15. g0到main goroutine的转换过程




## go中文网每日资讯--2021-03-19 

一、Go语言中文网

1. [Go招聘：跟果果小姐姐做同事机会来了](https://mp.weixin.qq.com/s/Pk1G3Cc8lcRd_Afib-h-xA)

2. [Go垃圾回收系列之九：内存屏障](https://mp.weixin.qq.com/s/0Vc7-RzMBZJ2oi6_odJdsw)

二、亚军进化史

1. [Go技术日报(2021-03-18)——map 和 switch 如何选？match 又是什么？](https://mp.weixin.qq.com/s/U6pwinkKS2CHwdDh0FIssg)

三、polarisxu

1. [发现 go version 的一个另类用法：你肯定想不到](https://mp.weixin.qq.com/s/RnV752Aez0Xdgscw38kNYw)

四、腾讯云CDN

1. [专题 | QUIC在CDN节点间的技术落地](https://mp.weixin.qq.com/s/ojxhrXxGHgRT1gs4z2zUCg)

五、腾讯技术工程

1. [腾讯广告 3000+万行大代码库主干开发实战](https://mp.weixin.qq.com/s/GZkGfwrfMTzrMfki8LKbIw)

六、分布式系统之美

1. [TiDB Operator 源码阅读 (一) 序](https://mp.weixin.qq.com/s/nr3BP9ys6qwe-9rWyv5E1w)

2. [TiDB Operator 源码阅读 (二) Operator 模式](https://mp.weixin.qq.com/s/MP9QfgBVGIlEtP2AMWzsJw)

七、xueyuanjun

1. [Go 数据结构和算法篇（七）：归并排序](https://mp.weixin.qq.com/s/fGAnnZxjH_A2ULJDAxxTgA)

八、CloudNativeCommunity

1. [IstioCon2021 回顾及开源项目 GetIstio 介绍视频回顾](https://mp.weixin.qq.com/s/MuZdLXHUC2HcKdl40GmZuw)

九、Golang技术分享

1. [面试题型系列：滑动窗口技巧](https://mp.weixin.qq.com/s/EzXqwy1Wew7ZrkSQx7-zfA)

十、Go招聘

1. [Go 笔试题精选 二： 25 道选择题](https://mp.weixin.qq.com/s/RPHTsKdXKqHM_JywR5kxvA)


## GOCN每日新闻--2021-03-19 
1.Go 参数校验 https://github.com/liangyaopei/checker

2.Go 函数调用惯例 https://mp.weixin.qq.com/s/XD8PUr9lm3DH6GqFZTA5cg

3.如何在 Go 中实现百万级 UDP 通信 https://mp.weixin.qq.com/s/BuZwjRNwuKx19PU6E95Oeg

4.Go 特殊字符的 string 怎么转 byte？https://xie.infoq.cn/article/14e4b4b1db4616499065d9112

5.让 Go 程序爱上 json 和 yaml https://sharpend.io/blog/teaching-go-programs-to-love-json-and-yaml


## gopherDaily--2021-03-19
1.为什么已经有了Kubernetes的你会需要Istio？ - https://thenewstack.io/why-do-you-need-istio-when-you-already-have-kubernetes/

2.依赖注入工具代码生成器wire入门 - https://mp.weixin.qq.com/s/hd5QnZQhvjAFza8gae1DiA

3.mattermost开源的看板工具，可自托管，可作为Trello，Notion和Asana的替代 - https://github.com/mattermost/focalboard

4.Go播客：聊聊go:embed - https://changelog.com/gotime/171

5.开源图书：如何设计程序(2nd) - https://htdp.org/2018-01-06/Book/

6.提案：微软开源的事件驱动微服务框架Dapr加入CNCF - https://github.com/cncf/toc/pull/617

7.如何使用Go构建Web前端 - https://philipptanlak.com/web-frontends-in-go/

8.声明式的错误处理 - https://github.com/serhiy-t/errf

9.使用prometheus收集Go应用指标 - https://gabrieltanner.org/blog/collecting-prometheus-metrics-in-golang

10.Karpenter是为Kubernetes构建的节点自动缩放器，可以在任何地方的任何Kubernetes集群中运行 - https://github.com/awslabs/karpenter

11.看看即将加入Go的泛型 - https://devmarkpro.com/generic-in-golang

12.使用kubernetes configmaps，第1部分：卷挂载 - https://itnext.io/working-with-kubernetes-configmaps-part-1-volume-mounts-f0ace283f5aa

13.google brotli压缩算法的Go实现 - https://github.com/andybalholm/brotli

14.ArgoCD + KubeVela：具有以开发人员为中心的经验的GitOps - https://www.cncf.io/blog/2020/12/22/argocd-kubevela-gitops-with-developer-centric-experience/


## 码农桃花源--2021-03-19
### 文章分享
1. [Go语言调度器之调度main goroutine](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483783&idx=1&sn=1128dbd7794d7d53c37abab94771a7d7&scene=19#wechat_redirect)

2. [go函数的一等公民](https://mp.weixin.qq.com/s/NPPzcfp7I50XcDMnR5bU9w)

3. [go build -x](https://mp.weixin.qq.com/s/uzaymD5izrBJMKDrn9OpBw)

### 面试题

1. 为什么在创建goroutine的newproc函数要传入参数大小

2. 什么时候调用的main函数？

3. g0到main goroutine的转换过程

### 每日算法
lc1377	T 秒后青蛙的位置



## go中文网每日资讯--2021-03-18 


一、Go语言中文网

1. [优化Go应用性能就是在浪费时间？你怎么看](https://mp.weixin.qq.com/s/jJM0N5yk9kk4w92yI8jjoQ)

2. [Kubernetes 稳定性保障手册 -- 日志专题](https://mp.weixin.qq.com/s/KIauQSWz1BBfuqyIvbKBWg)

3. [为什么 Go1.16.1 发布的第二天又发布 1.16.2？](https://mp.weixin.qq.com/s/ppUffaFo3k75yRwD7N6KNA)

二、亚军进化史

1. [Go技术日报(2021-03-17)——一招让 Kafka 达到最佳吞吐量](https://mp.weixin.qq.com/s/rKEEAlOQ3IlRX3pqtmSs4Q)

三、k8s技术圈

1. [Kubernetes APIServer 限流方案](https://mp.weixin.qq.com/s/f5FHyM-h_BWrCadk_G1I2A)

2. [资深运维工程师 - 尔湾科技](https://mp.weixin.qq.com/s/q2AVBiTrZ--nstqzFFtaHw)

四、polarisxu

1. [map 和 switch 如何选？match 又是什么？](https://mp.weixin.qq.com/s/MaovIWtQWVp9ZZL1DlppOQ)

五、xueyuanjun

1. [Go 数据结构和算法篇（六）：选择排序](https://mp.weixin.qq.com/s/G5tHf61lmYHNrqIRPEv7lA)

六、Go招聘

1. [北京超高福利公司招Go，你心动吗？](https://mp.weixin.qq.com/s/0IrzVAjPJo4JyCzUyWziog)

七、Golang技术分享

1. [Go函数调用惯例](https://mp.weixin.qq.com/s/XD8PUr9lm3DH6GqFZTA5cg)

八、脑子进煎鱼了

1. [Go 语言中的一等公民：看似普通的函数，凭什么？](https://mp.weixin.qq.com/s/NPPzcfp7I50XcDMnR5bU9w)

九、鸟窝

1. [Go代码覆盖率工具介绍](https://colobu.com/2021/03/15/go-cover-introduction/)

## GOCN每日新闻--2021-03-18 
1.Go 中的单元测试 mock 我是如何做的 https://dev.to/chseki/how-i-mock-unit-tests-in-golang-3dcp

2.如何测试使用了 time.Now() 的函数 https://medium.com/go-for-punks/how-to-test-functions-that-use-time-now-ea4f2453d430

3.GoPath 模式和 GoMoudle 模式的相爱相杀 https://segmentfault.com/a/1190000039650091

4.在 vscode 中 go 编码发生的问题整理 https://segmentfault.com/a/1190000039657544

5.一个 Go 编写的高效图片像素化工具 https://github.com/eleby/pixelizer



## gopherDaily--2021-03-18
1.你应该使用Microsoft Dapr构建事件驱动微服务的五个理由 - https://medium.com/event-driven-utopia/5-reasons-why-you-should-use-microsoft-dapr-to-build-event-driven-microservices-cb2202c579a0

2.如何在Go中实现百万级UDP通信 - https://mp.weixin.qq.com/s/BuZwjRNwuKx19PU6E95Oeg

3.Go module官方参考指南 - https://golang.org/ref/mod

4.Go播客：专访Mat Ryer: 从想法到执行 - https://ardanlabs.buzzsprout.com/1466944/8152259-from-idea-to-execution-with-mat-ryer

5.不太可能的数据库迁移 - https://tailscale.com/blog/an-unlikely-database-migration/

6.服务网格领域的创新与变革- https://thenewstack.io/innovation-and-changes-in-the-service-mesh-landscape-an-invitation-to-solocon/

7.为什么高级工程师厌恶代码评审 - https://medium.com/swlh/why-senior-engineers-hate-coding-interviews-d583d2855757

8.Go cache开源项目的benchmark对比 - https://github.com/vmihailenco/go-cache-benchmark

9.goverter: 用于创建类型安全转换器的工具 - https://github.com/jmattheis/goverter

10.让Go程序爱上json和yaml - https://sharpend.io/blog/teaching-go-programs-to-love-json-and-yaml/

11.Mockc：用于Go的类型安全的编译阶段mock测试生成器 - https://github.com/KimMachineGun/mockc



## 码农桃花源--2021-03-18
### 文章分享
1. [Go语言调度器之创建main goroutine](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483776&idx=1&sn=a74df39487b4ff22073e97eeb59d48ed&scene=19#wechat_redirect)

2. [QUIC原理](https://mp.weixin.qq.com/s/Bm_4M-QCcWYRqv1V8a-J-A)

3. [为什么kubernetes要替换docker](https://mp.weixin.qq.com/s/03RsI1JbjxiizjHnxrK7RQ)

4. [中高级golang面试题](https://www.bilibili.com/video/BV12p4y1W7Dz?t=1965)

### 面试题
1. 什么时候会抢占P

2. 当在M上运行的goroutine发生阻塞时，会怎么工作

3. 多个线程与多个M如何一一对应？

4. 汇编 操作对比 mov %rdx, %rax   与  mov %rdx, (%rax)

### 每日算法
lc1224	最大相等频率


## go中文网每日资讯--2021-03-17 


一、Go语言中文网

1. [关于emoji，Go语言可以这么操作](https://mp.weixin.qq.com/s/sZh9h2gb1X9Gu03A3OexmA)

2. [Go并发编程 — sync.Once 单实例模式的思考](https://mp.weixin.qq.com/s/37gV23UVHRA5SYeMEA5Q9w)

二、亚军进化史

1. [Go技术日报(2021-03-16)——Go 面试题：Go interface 的一个 “坑” 及原理分析](https://mp.weixin.qq.com/s/cyFHBeqFqbZajxHHHNq2Tw)

三、奇伢云存储

1. [Go并发编程 — sync.Once 单实例模式的思考](https://mp.weixin.qq.com/s/ELnUQL-EnK8w8EpdbZKDWA)

四、腾讯云CDN

1. [QUIC专题 | 谈谈QUIC协议原理](https://mp.weixin.qq.com/s/pa5lLcNtsEYRBHrUAJYcJA)

五、微服务实践

1. [一招让Kafka达到最佳吞吐量](https://mp.weixin.qq.com/s/lM1kkrQkXu6eIwVESwsa-w)

六、PingCap

1. [事务前沿研究 | 隔离级别的追溯与究明，带你读懂 TiDB 的隔离级别（上篇） | PingCAP](https://pingcap.com/blog-cn/take-you-through-the-isolation-level-of-tidb-1/)

七、k8s技术圈

1. [DevOps 工程师 - 汇丰软件开发 | 云原生招聘](https://mp.weixin.qq.com/s/MKVBONWugmd_jS1ihgGYJQ)

八、转角遇到GitHub

1. [终于不用愁了，GitHub 上的这些面试题项目我给你找好了](https://mp.weixin.qq.com/s/AqW9UFjuUopxJaehgMRFdg)

九、xueyuanjun

1. [Go 数据结构和算法篇（五）：插入排序](https://mp.weixin.qq.com/s/bfEsbHgk4sONbUc2MTXpiA)

十、Go招聘

1. [这个小公司是要招 Go 负责人？待遇你觉得如何？](https://mp.weixin.qq.com/s/J7xrhAnZ9pENCCwIjgZtyg)
## GOCN每日新闻--2021-03-17
1.Go 中新的安全政策提案 https://github.com/golang/go/issues/44918

2.大多数情况下可读性更重要 https://bitfieldconsulting.com/golang/slower

3.Go mod 中版本管理的权衡 https://utcc.utoronto.ca/~cks/space/blog/programming/GoModulesGoVersionWhy

4.gRPC 长链接实践指南 https://dev.bitolog.com/grpc-long-lived-streaming/

5.硬核论文:自动检测和修复 Go 中的并发错误 https://songlh.github.io/paper/gcatch.pdf


## gopherDaily--2021-03-17

1.Go vs. Node.js - https://medium.com/codex/golang-vs-node-js-214a9f9d0e00

2.如何在本地使用docker安全扫描 - https://brianchristner.io/how-to-use-docker-scan/

3.报告发现Go对公司的成功变得越来越重要 - https://sdtimes.com/softwaredev/report-finds-go-is-becoming-more-critical-to-a-companys-success/

4.如何自动重新加载Go应用 - https://iaziz786.medium.com/how-to-auto-reload-golang-applications-480f8dc43412

5.为什么我们不使用docker - https://launchyourapp.meezeeworkouts.com/2021/03/why-we-dont-use-docker-we-dont-need-it.html

6.Go实现的命令行网络诊断工具 - https://github.com/mehrdadrad/mylg

7.semaphore: Go实现的Ansible UI工具 - https://github.com/ansible-semaphore/semaphore

8.理解Kubernetes中的Taints和Tolerations - https://medium.com/kubernetes-tutorials/making-sense-of-taints-and-tolerations-in-kubernetes-446e75010f4e

9.roumon: 使用pprof和termui实现的通用goroutine监视器 - https://github.com/becheran/roumon

10.停止谈论多云和混合云，开始谈论集成 - https://thenewstack.io/stop-talking-about-multicloud-and-hybrid-cloud-and-start-talking-about-integration/

11.所有事情的摩尔定律 - https://moores.samaltman.com/

12.AIOps vs. MLOps：差别在哪里 - https://opensource.com/article/21/2/aiops-vs-mlops

13.2021年最佳人工智能和机器学习书籍 - https://www.educateai.org/the-best-artificial-intelligence-and-machine-learning-books-in-2021/

## 码农桃花源--2021-03-17
### 文章分享
1 [sendfile：linux中的零拷贝](https://www.cnblogs.com/pengdonglin137/articles/7995528.html)

2 [linux内核全新异步IO引擎io_uring(下)](https://aijishu.com/a/1060000000185685#item-3)

3 [超大文件http断点续传的实现](https://blog.csdn.net/ababab12345/article/details/80490621)

### 面试问题
1 如果已经建立了TCP连接，但是Client端突然出现故障了怎么办？

2 server端出现大量TIME_WAIT状态的连接的原因

### 每日算法
leetcode 5703 最大平均通过率 https://leetcode-cn.com/problems/maximum-average-pass-ratio/


## go中文网每日资讯--2021-03-16
一、Go语言中文网

1. [用Go看到进程中发生的系统调用](https://mp.weixin.qq.com/s/b9TlrMU8skpIlpmk5ph-4A)

2. [Go垃圾回收系列之八：辅助标记](https://mp.weixin.qq.com/s/E5GJtxfU20N6oWasqvXVQw)

二、亚军进化史

1. [Go技术日报(2021-03-15)——Go 笔试题精选 一： 25 道选择题](https://mp.weixin.qq.com/s/WKED5g02V45bAn0NBlZfpQ)

三、polarisxu

1. [周末看完这本 gRPC 的书后，我决定送 10 本给读者](https://mp.weixin.qq.com/s/sWDeK2de5pTLU1wrXYGAIA)

四、TechPaper

1. [一个特征系统的迭代与实现](https://mp.weixin.qq.com/s/vUP4LAA7gAYDo91Wd5rSQQ)

五、真没什么逻辑

1. [为什么 Kubernetes 要替换 Docker](https://mp.weixin.qq.com/s/03RsI1JbjxiizjHnxrK7RQ)

六、taowen

1. [不要以 DRY 之名，发明低代码 DSL 去残害你的同事](https://mp.weixin.qq.com/s/S7BbDwVpq6LKlXoEWx-I5A)

七、脑子进煎鱼了

1. [Go 面试题：Go interface 的一个 “坑” 及原理分析](https://mp.weixin.qq.com/s/vNACbdSDxC9S0LOAr7ngLQ)

八、即时通讯技术圈

1. [一套亿级用户的IM架构技术干货(上篇)：整体架构、服务拆分等](https://mp.weixin.qq.com/s/WxB9fH1I8CJgfcuVGtzlQQ)

九、Go招聘

1. [快来AiBee跟果果小姐姐做同事啦](https://mp.weixin.qq.com/s/zK2FyXMLocwKRXcV5q-LBw)

## GOCN每日新闻--2021-03-16 
1.NBIO 第二弹 —— 支持 Non-Blocking HTTP 1.x https://gocn.vip/topics/11779

2.还在用 crontab? 分布式定时任务了解一下 https://mp.weixin.qq.com/s/IftPwlmubjwGQz1KYTHIIQ

3.Go 空结构体引发的大型打脸现场 https://mp.weixin.qq.com/s/lZMZroOhqvDKDCEsaGPfrQ

4.用 Go 看到进程中发生的系统调用 https://mp.weixin.qq.com/s/b9TlrMU8skpIlpmk5ph-4A

5.如何优雅地关闭 Kubernetes 集群中的 Pod https://blog.gruntwork.io/zero-downtime-server-updates-for-your-kubernetes-cluster-902009df5b33

## gopherDaily--2021-03-16
- 1.Rust vs. Go：为什么强强联合会更好 - https://mp.weixin.qq.com/s/Nx-5e8ssiga4Bjfe6BGSOw
- 2.观点：优化Go应用性能就是在浪费时间 - https://bitfieldconsulting.com/golang/slower
- 3.性能比较：使用Python，Go，C++，C，AWK，Forth和Rust做单词计数 - https://benhoyt.com/writings/count-words/
- 4.教程：使用Ent和gqlgen构建GraphQL服务器 - https://entgo.io/docs/tutorial-setup/
- 5.遵循eBPF的“超级能力”的承诺 - https://thenewstack.io/liz-rice-following-the-superpower-promise-of-ebpf/
- 6.可以识别视频语音自动生成字幕SRT文件的开源 Windows-GUI 软件工具 - https://github.com/wxbool/video-srt-windows
- 7.在AKS上的Statefulset中增加volumeClaimTemplates磁盘大小 - https://adamrushuk.github.io/increasing-the-volumeclaimtemplates-disk-size-in-a-statefulset-on-aks/
- 8.使用Go设计和实现WebSocket服务器 - https://medium.com/geekculture/designing-a-websocket-server-in-golang-reformers-golang-implementation-strategy-bcd2dc9e368e
- 9.REST vs. GraphQL vs. gRPC - https://www.danhacks.com/software/grpc-rest-graphql.html
- 10.wormhole-gui: Wormhole-gui是magic-wormhole的跨平台图形界面，使您可以轻松地在设备之间共享文件，文件夹和文本 - https://github.com/Jacalz/wormhole-gui
- 11.swift语言试验增加actor并发支持 - https://github.com/apple/swift-evolution/blob/main/proposals/0306-actors.md
- 12.可解释性与神经科学：六个主要优点使人工神经网络比生物学神经网络更易于研究 - http://colah.github.io/notes/interp-v-neuro/
## 码农桃花源--2021-03-16
### 文章分享
1 [linux内核全新异步IO引擎io_uring(上)](https://aijishu.com/a/1060000000185659)

2 [浅谈如何构建知识体系](https://mp.weixin.qq.com/s/E0u7LmT__x4R9mWNxfDDjA)

3 [分布式系统底层原理](https://mp.weixin.qq.com/s/KKrxuVCrjlXXWMPTXQ-fvA)

### 面试题
1.TCP收到RST报文的几种情况？

2.说说半连接队列和 SYN Flood 攻击的关系

3.介绍一下 TCP 报文头部的字段

### 每日算法
lc5704 好子数组的最大分数 https://leetcode-cn.com/problems/maximum-score-of-a-good-subarray/

## go中文网每日资讯--2021-03-15 


一、Go语言中文网

1. [不要在生产环境使用 http.DefaultServerMux？](https://mp.weixin.qq.com/s/ldMdmrC32f0o8pQvpPzvCw)

2. [Go垃圾回收系列之七：标记终止与调步算法](https://mp.weixin.qq.com/s/_KizBohpXYiYp0LZO4TQOw)

二、亚军进化史

1. [Go技术日报(2021-03-14)——Go 空结构体引发的大型打脸现场](https://mp.weixin.qq.com/s/pLpwgLA_c5Cpq4ibH3nIcQ)

三、Go招聘

1. [Go 笔试题精选 一： 25 道选择题](https://mp.weixin.qq.com/s/U1EV6qfyvU9gDg9sIDGqww)

四、k8s技术圈

1. [调度器调度队列之 activeQ 分析 | 视频文字稿](https://mp.weixin.qq.com/s/0s4cBAGw4YsU3qEUrr8dVw)

五、代码与远方

1. [CPU 空闲时在干嘛？](https://mp.weixin.qq.com/s/Y0MrsluNeuqAXPLQQrvv4w)

六、ServiceMesher

1. [IstioCon 2021 回顾及 PPT 下载](https://mp.weixin.qq.com/s/Az8Ivznp1l6zHewzcFqyeA)

七、脑子进煎鱼了

1. [Go 群友提问：学习 defer 时很懵逼，这道不会做！](https://mp.weixin.qq.com/s/lELMqKho003h0gfKkZxhHQ)

八、码农桃花源

1. [&quot;go build -X&quot; 的妙用](https://mp.weixin.qq.com/s/uzaymD5izrBJMKDrn9OpBw)

九、MoeLove

1. [万字长文：彻底搞懂容器镜像构建](https://mp.weixin.qq.com/s/zAWr4ezK5kjGVzUqs2eg2Q)

十、奇伢云存储

1. [有趣的3个动画揭开Linux cp的秘密](https://mp.weixin.qq.com/s/rlSi-y0xQE_V-UxBU2AKmA)
## GOCN每日新闻--2021-03-15 
1.让 json 解析更简单高效的 GJSON https://gocn.vip/topics/11778

2.使用观察者模式来观察本地文件的修改 https://www.hildeberto.com/2021/03/observer-design-pattern-golang.html

3."go build -X" 的妙用 https://mp.weixin.qq.com/s/uzaymD5izrBJMKDrn9OpBw

4.Kubernetes 稳定性保障手册（极简版) https://mp.weixin.qq.com/s/DK1BfzY-Ou-_xB6aGO6yTw

5.tiktik: tiktok 终端客户端 https://github.com/irevenko/tiktik


## gopherDaily--2021-03-15
- 1.Go单一仓库的多module实战 - https://irilivibi.medium.com/golang-multimodule-monorepo-tutorial-3f5cf10e9b9a
- 2.2021年的CI/CD战争：最流行的技术一览 - https://blog.thundra.io/the-ci/cd-war-of-2021-a-look-at-the-most-popular-technologies
- 3.Go播客：谈谈Go代码生成 - https://changelog.com/gotime/170
- 4.将你的Go开发环境容器化系列 - https://www.docker.com/blog/containerize-your-go-developer-environment-part-1/
- 5.使用Go构建和推送docker镜像 - https://www.loginradius.com/blog/async/build-push-docker-images-golang/
- 6.常用Go并发模式汇总 - https://github.com/lotusirous/go-concurrency-patterns
- 7.TikTok终端工具：可浏览和下载TikTok视频 - https://github.com/irevenko/tiktik
- 8.sqlfuzz: 生成随机数据并加载到SQL表中以备后续测试 - https://github.com/PumpkinSeed/sqlfuzz
- 9.etcd v3全内存缓存client端 - https://github.com/tailscale/tailetc
- 10.Kubernetes中的CPU限制和节流 - https://medium.com/omio-engineering/cpu-limits-and-aggressive-throttling-in-kubernetes-c5b20bd8a718
- 11.远程工作真正对您的工程生产力有什么影响 - https://www.okayhq.com/blog/what-remote-work-really-does-to-your-engineering-productivity
- 12.使用Go与AWS S3开发应用教程 - https://tutorialedge.net/courses/go-aws-s3-course/
## 码农桃花源--2021-03-15
### 文章分享
1 [编译原理初学者指南](https://mp.weixin.qq.com/s/ZTxVG6KG-4vzbvclC_Q1LQ)

2 [编译原理概述](https://draveness.me/golang/docs/part1-prerequisite/ch02-compile/golang-compile-intro/)

3 [DNS是使用tcp还是udp协议](https://www.cnblogs.com/lsgxeva/p/8321192.html)

4 [复习：etcd如何实现mvcc](https://mp.weixin.qq.com/s/mW4juWcLbkcJ7aoHbXNbQA)

### 面试题
1.epoll与select的优缺点？

2.http请求的处理过程

3.事务的隔离级别 底层是如何实现的

### 每日算法
lc1781 所有子字符串美丽值之和 https://leetcode-cn.com/problems/sum-of-beauty-of-all-substrings/




## gopherDaily--2021-03-14
- 1.为什么go的存在让docker变得没有必要 - https://launchyourapp.meezeeworkouts.com/2021/03/why-we-dont-use-docker-we-dont-need-it.html
- 2.Rust vs. Go：为什么强强联合会更好 - https://t.zsxq.com/emuzvJy
- 3.accelerated-container-image: 论文”DADI: Block-Level Image Service for Agile and Elastic Application Deployment “的开源实现。它以iSCSI块设备的形式提供基于块的层的序列合并视图。它可以用于容器加速，支持按需获取图像数据，而无需在容器运行前下载和解压整个图像。通过OverlayBD图像格式，我们可以瞬间冷启动一个容器。- https://github.com/alibaba/accelerated-container-image
- 4.Golds：一个Go本地文档服务器、文档生成工具以及go代码阅读工具 - https://go101.org/article/tool-golds.html
- 5.netbootd是一个轻量级的网络启动服务器，支持无人值守的操作系统安装 - https://github.com/DSpeichert/netbootd
- 6.图解OAuth2 - https://developer.okta.com/blog/2019/10/21/illustrated-guide-to-oauth-and-oidc
- 7.使用gitlab ci/cd在k8s上构建和部署应用 - https://piotrminkowski.com/2020/10/19/gitlab-ci-cd-on-kubernetes/
- 8.GitOps的魅力不止于眼前的一切 - https://www.weave.works/blog/theres-more-to-gitops-than-meets-the-eye
- 9.微软开源低代码平台语言Fx - https://thenewstack.io/microsoft-open-sources-the-power-fx-language-for-customizing-logic-in-low-code-apps/
- 10.终结k8s namespace的隐藏危险 - https://www.openshift.com/blog/the-hidden-dangers-of-terminating-namespaces
- 11.rust vs. c性能比较 - https://kornel.ski/rust-c-speed
- 12.Linkerd中的协议检测和不透明端口 - https://www.cncf.io/blog/2021/03/10/protocol-detection-and-opaque-ports-in-linkerd/
- 13.bombardier: 跨平台高性能http性能基准测试工具 - https://github.com/codesenberg/bombardier
- 14.用实时观察器扩展数组 - https://khal.web.id/2021/03/13/go-extending-array-with-a-real-time-observer/


## GOCN每日新闻--2021-03-14

1.Go 编写的带有实时分析器的负载测试工具 https://www.reddit.com/r/golang/comments/m4j04y/a_load_testing_tool_with_a_realtime_analyzer/

2.我如何在 Go 中构建 Web 前端 https://philipptanlak.com/web-frontends-in-go/

3.Go maps 和 switches https://adayinthelifeof.nl/2021/03/04/go-map-vs-switch.html

4.为什么我们不使用 Docker https://launchyourapp.meezeeworkouts.com/2021/03/why-we-dont-use-docker-we-dont-need-it.html

5.Rust vs Go 为什么他们在一起会更好 https://thenewstack.io/rust-vs-go-why-theyre-better-together/


## go中文网每日资讯--2021-03-14 

一、Go语言中文网

1. [Go语言爱好者周刊：第 86 期 — 这道题考察什么？](https://mp.weixin.qq.com/s/VWcooMEaCsESpBXLU5c7jg)

2. [Go 空结构体引发的大型打脸现场](https://mp.weixin.qq.com/s/lZMZroOhqvDKDCEsaGPfrQ)

3. [还在用crontab? 分布式定时任务了解一下](https://mp.weixin.qq.com/s/IftPwlmubjwGQz1KYTHIIQ)

二、亚军进化史

1. [Go技术日报(2021-03-13)——Go 官方 2020 年开发者调查报告](https://mp.weixin.qq.com/s/S8UO4NM1d4HMlub-mJhm_w)

三、董泽润的技术笔记

1. [HOL blocking 困扰两个月的问题](https://mp.weixin.qq.com/s/8gajOBLJCHxlVWeyAzgW2w)

四、xueyuanjun

1. [Go 数据结构和算法篇（二）：栈](https://mp.weixin.qq.com/s/NEsgLvdgOkp9JRNnNlSC1A)

五、polarisxu

1. [为什么 Go1.16.1 发布的第二天又发布 1.16.2？](https://mp.weixin.qq.com/s/mbMCxhmz8pF8VUMKm3XYtA)

六、Go招聘

1. [Go Interview Weekly - 2021/03/14](https://mp.weixin.qq.com/s/TGrbynJczOtE4VNuzaHuWw)

七、奇伢云存储

1. [深度剖析 Linux cp 的秘密](https://mp.weixin.qq.com/s/bLiqURdK_dtgr0GqU7yD9w)

八、Go Weekly

1. [Awesome Go Newsletter - Issue 251, Mar 11, 2021 | LibHunt](https://go.libhunt.com/newsletter/251)

2. [Golang Weekly Issue 353: March 12, 2021](https://golangweekly.com/issues/353)



## go中文网每日资讯--2021-03-13 
一、Go语言中文网

1. [Go 官方 2020 年开发者调查报告](https://mp.weixin.qq.com/s/mw3ktRLNL9H4m32Es_nU_A)

2. [Kubernetes 稳定性保障手册 -- 极简版](https://mp.weixin.qq.com/s/Udl25deXsEo7qc_2MAmpFg)

3. [Go垃圾回收之六：扫描灰色对象](https://mp.weixin.qq.com/s/7rK307CTWE72LHRpgVP_9Q)

二、亚军进化史

1. [Go技术日报(2021-03-12)——Go1.16.1 发布：这个 Bug 有点 Low](https://mp.weixin.qq.com/s/ndp-ahd1FOe1q4OsjtVCTw)

三、脑子进煎鱼了

1. [Go 爱好者福利，《Go 语言编程之旅》正式开源！](https://mp.weixin.qq.com/s/Nt1Bd-G7rqrwM8_JbEkAag)

四、k8s技术圈

1. [阿里云与华为云边缘 K8S 使用对比总结](https://mp.weixin.qq.com/s/4JAWNV5ARaChGc5dLZfMTg)

五、xueyuanjun

1. [Go 数据结构和算法篇（一）：链表](https://mp.weixin.qq.com/s/Zvdxs0Ag2_xrnMJ9wC1MFQ)###

## GOCN每日新闻--2021-03-13

1.对抗僵尸依赖 https://dlorenc.medium.com/zombie-dependencies-77c34740a7a8

2.入门 Go 和 eBPF https://networkop.co.uk/post/2021-03-ebpf-intro/

3.掌握 Go HTML Templates https://philipptanlak.com/mastering-html-templates-in-go-the-fundamentals/

4.如何使用 Golang 处理 MySQL 的 binlog https://zhuanlan.zhihu.com/p/335964345

5.使用 SQL 查询文件系统 https://github.com/kashav/fsql

## gopherDaily--2021-03-13
1.[如何成为Go开发人员：6步职业指南 ](https://dev.to/educative/how-to-become-a-golang-developer-6-step-career-guide-476n)

2.[Go 1.16.2和Go 1.15.10紧急发布 ](https://groups.google.com/g/golang-announce/c/ZWvSr9XM4wM/m/t8wy_q5_AgAJ)

3.[go sqlite支持apple M1]( https://pkg.go.dev/modernc.org/sqlite#hdr-Changelog)

4.[paper: 自动检测和修复Go软件系统中的并发性错误 ](https://songlh.github.io/paper/gcatch.pdf)

5.[掌握Go html模板基础]( https://philipptanlak.com/mastering-html-templates-in-go-the-fundamentals/)

6.[在Cloud Run上构建大型聊天服务器 ](https://ahmet.im/blog/cloud-run-chat-server/)

7.[云原生应用交付–2021年我们的发展方向]( https://medium.com/dynatrace-engineering/cloud-native-app-delivery-where-were-heading-in-2021-c0a413610352)

8.[拆解和修复etcd集群 ](https://itnext.io/breaking-down-and-fixing-etcd-cluster-d81e35b9260d)

9.[使用tinygo开发webassembly程序]( https://sendilkumarn.com/blog/tiny-go-wasm/)

10.[经典旧文：SOLID Go设计]( https://dave.cheney.net/2016/08/20/solid-go-design)

11.[我为什么不喜欢tailwind css ](https://www.aleksandrhovhannisyan.com/blog/why-i-dont-like-tailwind-css/)

## 码农桃花源--2021-03-13
### 优质文章汇总
1. [golang 撮合引擎 从思路到MVP](https://mp.weixin.qq.com/s/DvUh0igObcRsyEWrg1NMAw)

2. [造轮子-golang哈希表实现](https://segmentfault.com/a/1190000039219752)

3. [dubbo-go如何实现路由策略功能](https://segmentfault.com/a/1190000022523595?utm_source=sf-related)

4. [redis cluster实现分布式锁](https://tonybai.com/2021/02/13/operate-with-shared-resources-in-a-mutually-exclusive-way-through-distributed-lock-implemented-by-redis-cluster/)

5. [汇编指令简单学习](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483693&idx=1&sn=e5398ae82e2f3484bea5e8858b1a9cd7&scene=19#wechat_redirect)

6. [go语言调度，函数调用过程](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483723&idx=1&sn=772960aa0d5ae4aa6921e9ff43fcb99f&scene=19#wechat_redirect)
### 面试问题
1. Go语言的栈空间管理是怎么样的

2. Go的GPM如何调度

3. Go的Slice如何扩容

4. Go中CAS是怎么回事

5. mov %rdx, (%rax)与mov %rdx, %rax 的区别

6. 函数与被调用函数如何转换(call 和 ret命令)

7. 大小端存储方式是什么样子的

8. 内存中分四个区域布局是？

9. A方法调用B方法调用C方法的栈内存是如何变化的的？

10. nmap扫描如何进行扫描。发包与协议，握手和不握手，哪些协议握手，哪些不握手. 如何不直接接触目标服务器探测对方端口是否开放

11. mysql的读写分离与主从同步

12.  mysql如何保证一致性与持久性

13.  输入 ping IP 后敲回车，发包前会发生什么？

14. 从 innodb 的索引结构分析，为什么索引的 key 长度不能太长？

15. innodb关键特性

16. MySQL 的数据如何恢复到任意时间点？

17. 讲一讲mvcc的redo log、undo log，和binlog有什么不同

18. 关于 epoll 和 select 的区别，哪些说法是正确的？（多选）

A. epoll 和 select 都是 I/O 多路复用的技术，都可以实现同时监听多个 I/O 事件的状态。

B. epoll 相比 select 效率更高，主要是基于其操作系统支持的I/O事件通知机制，而 select 是基于轮询机制。

C. epoll 支持水平触发和边沿触发两种模式。

D. select 能并行支持 I/O 比较小，且无法修改

## go中文网每日资讯--2021-03-12 

一、Go语言中文网

1. [Go 实现的语言了解下【文末福利】](https://mp.weixin.qq.com/s/Aam7AVhgAZyO3WKHV1YuMw)

2. [Go1.16.1 发布：这个 Bug 有点 Low](https://mp.weixin.qq.com/s/m68JeildlCg0cQ88CWLvUg)

3. [Go垃圾回收系列之五：栈与栈对象](https://mp.weixin.qq.com/s/69ZvRHAwVdNzGXpXLRk6lQ)

二、亚军进化史

1. [Go技术日报(2021-03-11)——k8s 调度器启动流程分析](https://mp.weixin.qq.com/s/L2uIv5GPqLZ25V9VX33ixw)

三、taowen

1. [代码写得不好，不要总觉得是自己抽象得不好](https://mp.weixin.qq.com/s/8T0rrl5dkwtYB_XCbAhACQ)

四、多颗糖

1. [【MIT 6.824】学习笔记4: 主从复制(Primary/Backup Replication)](https://mp.weixin.qq.com/s/pnJbd46gEPTpZLF1QYF-mg)

五、Go招聘

1. [珠海怎么样？好几个 Go 相关职位等你来](https://mp.weixin.qq.com/s/11wwK7L1Sfh_64eHVQAPUg)

2. [两天功夫，Go发布1.16.1，接着又发布1.16.2](https://mp.weixin.qq.com/s/0Y48f2OTVmCLnBzVn2s8ZQ)

六、Go101

1. [Go文档和代码阅读神器Golds已更新到0.2.x版本了](https://mp.weixin.qq.com/s/uVX1hQzE6Qc0p-JiTd5ytQ)

## GOCN每日新闻--2021-03-12
1.Go 1.16.2 and Go 1.15.10 发布 https://groups.google.com/g/golang-announce/c/ZWvSr9XM4wM

2.WebAssembly + Go 系列（2）WASI，WebAssembly 不止于 Web https://segmentfault.com/a/1190000039397525

3.Dolt 像 Git 一样操作数据库 https://github.com/dolthub/dolt

4.有道 Kubernetes 容器 API 监控系统设计和实践 https://segmentfault.com/a/1190000039390685

5.Go 一步步实现 TLS 双向认证 https://venilnoronha.io/a-step-by-step-guide-to-mtls-in-go

## gopherDaily--2021-03-12
- 1.2020年Go官网开发者调查结果发布！- https://blog.golang.org/survey2020-results
- 2.Go语言语法速查表 - https://github.com/LeCoupa/awesome-cheatsheets/blob/master/languages/golang.md
- 3.go.mod模块文件中Go版本行为的权衡 - https://utcc.utoronto.ca/~cks/space/blog/programming/GoModulesGoVersionWhy
- 4.我们为什么从python迁移到Go - https://softwareengineeringdaily.com/2021/03/03/why-we-switched-from-python-to-go/
- 5.2021年使用GO Buffalo的API：从零部署 - https://dev.to/alexmercedcoder/api-with-go-buffalo-in-2021-from-zero-to-deploy-5642
- 6.在Go中实现NATS保活订阅 - https://medium.com/swlh/nats-keep-alive-subscription-in-golang-a80073949371
- 7.Go代码到C#代码转换器及策略 - https://go2cs.net/ConversionStrategies.html
- 8.模拟竞争条件以了解多线程（Go）的挑战 - https://dsinecos.github.io/blog/Challenges-of-multithreading
- 9.破解kubernetes节点代理 - http://arthurchiao.art/blog/cracking-k8s-node-proxy/
- 10.欧洲最大的时尚电子商务公司如何使用GraphQL - https://engineering.zalando.com/posts/2021/03/how-we-use-graphql-at-europes-largest-fashion-e-commerce-company.html
## 码农桃花源--2021-03-12
### 文章分享
1. [go语言调度，函数调用过程](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483723&idx=1&sn=772960aa0d5ae4aa6921e9ff43fcb99f&scene=19#wechat_redirect)

2. [内存重排](https://mp.weixin.qq.com/s/r9yC78exkDbXs7Et2pC5PA)

3. [昨天那道问题如果没回答上来，复习一下吧](https://mp.weixin.qq.com/s/MTZ0C9zYsNrb8wyIm2D8BA)

4. [问题链接](https://mp.weixin.qq.com/s?__biz=MzkyMDAzNjQxMg==&mid=2247484139&idx=1&sn=259c87bb327142d1d6ba21927acde276&scene=21#wechat_redirect)

### 面试题
1. Go语言的栈空间管理是怎么样的

2. Go的GPM如何调度

3. Go的Slice如何扩容

4. Go中CAS是怎么回事

### 每日算法
lc1383	最大的团队表现值

## go中文网每日资讯--2021-03-11 

一、Go语言中文网

1. [虽然有争议，但 Go 还是需要泛型的](https://mp.weixin.qq.com/s/UEGI0Zl6XuSGLDzMG6tnng)

2. [白话Go内存模型：Happen-Before](https://mp.weixin.qq.com/s/vTQWxScEo4u6zaFHY9hQ0A)

3. [Go 语言的参数传递](https://mp.weixin.qq.com/s/6EkOBPhSDo5GWlteiH-RZA)

二、亚军进化史

1. [Go技术日报(2021-03-10)——2021 有哪些不容错过的后端技术趋势](https://mp.weixin.qq.com/s/1KdZLOEKS6Llu_GYeV53kA)

三、polarisxu

1. [快一个月，Go1.16 才发现了比较严重的 Bug，但这个 Bug 有点 Low。。。](https://mp.weixin.qq.com/s/AddZm8qaWBY-Hgexq6tWkA)

四、Go招聘

1. [什么？腾讯招前端竟然希望熟悉 Go](https://mp.weixin.qq.com/s/a_fYCkgzmVkieU8YvreJ-w)

五、分布式实验室

1. [容器网络其实并不难](https://mp.weixin.qq.com/s/1hyCPrDb88q-kPSFaP-TPA)

六、mohuishou

1. [Go工程化(九) 项目重构实践](https://mp.weixin.qq.com/s/fZBh6QyRbV7O-rgyoOJblg)

七、The Go Blog

1. [Go Developer Survey 2020 Results](https://blog.golang.org/survey2020-results)

八、k8s技术圈

1. [k8s调度器启动流程分析 | 视频文字稿](https://mp.weixin.qq.com/s/olfA6Ty1vjkRGLj1KudUEw)

2. [k8s调度器启动流程分析](https://mp.weixin.qq.com/s/qmgMdrC8LxEUdyHW1J_aXA)


## GOCN每日新闻--2021-03-11 

1.Go 1.16.1/1.15.9 版本发布，修复两处安全问题 https://groups.google.com/g/golang-announce/c/MfiLYjG-RAw/m/zzhWj5jPAQAJ

2.2020 年 Go 开发者调研结果公开 https://blog.golang.org/survey2020-results

3.Golang 在即刻后端的实践 https://mp.weixin.qq.com/s/cepoYJR5Xeloan31-D1iQg

4.netaddr.IP: 一个新 Go IP 地址类型 https://tailscale.com/blog/netaddr-new-ip-type-for-go/

5.使用 Godot 和 Nakama 构建在线多人游戏 https://heroiclabs.com/blog/announcements/godot-fishgame/



## gopherDaily--2021-03-11 
- 1.Go与eBPF入门 - https://networkop.co.uk/post/2021-03-ebpf-intro/
- 2.Go 1.16.1和Go 1.15.9发布 - https://groups.google.com/g/golang-announce/c/MfiLYjG-RAw/m/zzhWj5jPAQAJ?pli=1
- 3.使用Go实现gRPC长期流式传输(long-lived streaming) - https://dev.bitolog.com/grpc-long-lived-streaming/
- 4.netaddr.IP：Go的新IP地址类型 - https://tailscale.com/blog/netaddr-new-ip-type-for-go/
- 5.使用flag.Func(Go 1.16引入)自定义命令行标志 - https://www.alexedwards.net/blog/custom-command-line-flags
- 6.cosign: 为镜像库中的容器签名，验证和存储, sigstore子项目 - https://github.com/sigstore/cosign
- 7.在Go中创建证书颁发机构(CA)和签名证书 - https://shaneutt.com/blog/golang-ca-and-signed-cert-go/
- 8.接纳Kubernetes需要转变思维方式（第1部分） - https://www.thoughtworks.com/insights/blog/mindset-shift-needed-kubernetes-adoption-part-1
- 9.Go语言的mTLS入门指南 - https://venilnoronha.io/a-step-by-step-guide-to-mtls-in-go
- 10.在k8s上根据rabbitmq中消息数量自动扩展Celery - https://learnk8s.io/scaling-celery-rabbitmq-kubernetes
- 11.人工智能神经网络中的多模态神经元 by openai - https://openai.com/blog/multimodal-neurons/
- 12.使用basecamp规划我的生活 - https://world.hey.com/tassia/how-i-use-basecamp-to-organize-my-life-3e71de07

## 码农桃花源--2021-03-11
### 文章分享
1. [汇编指令简单学习](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483693&idx=1&sn=e5398ae82e2f3484bea5e8858b1a9cd7&scene=19#wechat_redirect)

2. [内存的简单复习](http://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483669&idx=1&sn=39a43fbb3c60a58084d01928ae228b71&scene=19#wechat_redirect)

3. [寄存器的简单复习](https://mp.weixin.qq.com/s?__biz=MzU1OTg5NDkzOA==&mid=2247483660&idx=1&sn=ea75d8fdb4b2e0eac03449d63172fe3e&scene=19#wechat_redirect)

4. [以上我发的是我最近慢慢学习go调度的文章，看完饶大的文章有的地方还是不懂，看看别的大佬文章拓宽一下思维，如果不喜欢这样的系列可以跟我说，明天我换别的文章] 

5. [群友推荐有意思的题目] https://mp.weixin.qq.com/s?__biz=MzkyMDAzNjQxMg==&mid=2247484139&idx=1&sn=259c87bb327142d1d6ba21927acde276&scene=21#wechat_redirect

### 面试问题
看完文章的问题 就当我是面试官好了
1. mov %rdx, (%rax)与mov %rdx, %rax 的区别

2. 函数与被调用函数如何转换(call 和 ret命令)

3. 大小端存储方式是什么样子的

4. 内存中分四个区域布局是？

5. A方法调用B方法调用C方法的栈内存是如何变化的的？

### 学习笔记
栈：https://www.yuque.com/wuguoguoya/iq0d3v/gctugx
汇编： https://www.yuque.com/wuguoguoya/iq0d3v/mkrsrd





## go中文网每日资讯--2021-03-10


一、Go语言中文网

1. [360 加大 Go 招聘，Go 形势大好！你来吗？](https://mp.weixin.qq.com/s/F5SP2s1PrEHx_3IyszCC1Q)

2. [Go垃圾回收系列之四：根对象与全局扫描](https://mp.weixin.qq.com/s/UzfOqRY7DSUC9qCoN9CJPA)

二、亚军进化史

1. [Go技术日报(2021-03-09)——从 MPG 线程模型，探讨 Go 语言的并发程序](https://mp.weixin.qq.com/s/VWgx8_NWxBgTAtij81g4Tw)

三、polarisxu

1. [polarisxu 对话无闻](https://mp.weixin.qq.com/s/RZdSx8C36QdG59XdqQ2svg)

四、腾讯技术工程

1. [2021 有哪些不容错过的后端技术趋势](https://mp.weixin.qq.com/s/EuqJ2Q9CAWSJ0rTc_p_gjg)

五、网管叨bi叨

1. [如何优雅地关闭Kubernetes集群中的Pod](https://mp.weixin.qq.com/s/fbQ2vdJ4bDJdOrhNFChOsQ)

六、Gopher指北

1. [今天看了一道很有意思的切片输出面试题](https://mp.weixin.qq.com/s/G8MrTgwH88ABB-OOYreXIA)

七、Go招聘

1. [计算机系统最底层、最具挑战的领域招 Go，敢不敢来？](https://mp.weixin.qq.com/s/N8J7V_GHjXR5F7bpJH2wLg)


## GOCN每日新闻--2021-03-10
1.Golang 泛型初探 https://gocn.vip/topics/11759

2.TiKV + SPDK，探索存储的性能极限 https://gocn.vip/topics/11760

3.Go 垃圾回收系列之三：并行标记执行模式 https://mp.weixin.qq.com/s/QwZLXfKpFU1OvrJJvsjlzA

4.Golang 的内存对齐 https://studygolang.com/articles/33789

5.Golang 并发模式之扇入 FAN-IN 和扇出 FAN-OUT https://studygolang.com/articles/33808

## gopherDaily--2021-03-10
1.Go自动化测试介绍 - https://dev.to/salesforceeng/intro-to-automated-testing-in-go-4mjl

2.kglb: dropbox开源的用Go开发的基于ip_vs的四层负载均衡器 - https://github.com/dropbox/kglb

3.使用Go标准库heap包 - https://klotzandrew.com/blog/using-the-go-heap-interface

4.vscode-go将staticcheck作为默认lint工具 - https://github.com/golang/vscode-go/commit/fd0328225d16ecc97e09e72c8c354cf106928984

5.使用依赖注入进行Go mock测试 - https://medium.com/everything-full-stack/golang-test-mocking-using-dependency-injection-f48cddbcf6dd

6.在表驱动测试中使用Gomock进行mock测试 - https://gogoapps.io/blog/mocking-with-gomock-in-table-driven-tests/

7.使用go构建一个微型API - https://www.moonclash.com/simple-go-api/

8.数据科学学习路线 - https://docs.google.com/document/d/1Gstaq13qxnk2inIYWVnvpI0ohhK1wuhVwsBzYs1vEno/edit

9..Red Hat OpenShift 4.7：旨在简化和加速应用程序现代化 - https://www.redhat.com/en/about/press-releases/red-hat-refines-kubernetes-both-traditional-and-cloud-native-applications-latest-version-red-hat-openshift

10.机器学习和深度学习数据集 - https://sebastianraschka.com/blog/2021/ml-dl-datasets.html
全球最具创新力的公司2021 - https://www.fastcompany.com/90603436/the-worlds-most-innovative-companies-2021

## 码农桃花源--2021-03-10
### 文章分享
1 [dubbo-go如何实现路由策略功能](https://segmentfault.com/a/1190000022523595?utm_source=sf-related)

2 [造轮子-golang哈希表实现](https://segmentfault.com/a/1190000039219752)

3 [五福背后的3D引擎](https://segmentfault.com/a/1190000039304848)

### 面试题
1 输入 ping IP 后敲回车，发包前会发生什么？

2 关于 epoll 和 select 的区别，哪些说法是正确的？（多选）

A. epoll 和 select 都是 I/O 多路复用的技术，都可以实现同时监听多个 I/O 事件的状态。

B. epoll 相比 select 效率更高，主要是基于其操作系统支持的I/O事件通知机制，而 select 是基于轮询机制。

C. epoll 支持水平触发和边沿触发两种模式。

D. select 能并行支持 I/O 比较小，且无法修改。

### 每日算法
lc895 最大频率栈 https://leetcode-cn.com/problems/maximum-frequency-stack/

## go中文网每日资讯--2021-03-09 


一、Go语言中文网

1. [Go：死锁是如何触发的？](https://mp.weixin.qq.com/s/ZezoXyGn0HA-8j7yForU6Q)

2. [Go垃圾回收系列之三：并行标记执行模式](https://mp.weixin.qq.com/s/QwZLXfKpFU1OvrJJvsjlzA)

二、亚军进化史

1. [Go技术日报(2021-03-08)——Go 并发编程(一) goroutine](https://mp.weixin.qq.com/s/r4O9hJSYAI8I9k0iLbRvVA)

三、真没什么逻辑

1. [Facebook 集群调度管理系统 · OSDI 2020](https://mp.weixin.qq.com/s/9ge-Ro79sl63k0lSuiE2Yw)

四、k8s技术圈

1. [MongoDB 常用运维实践总结](https://mp.weixin.qq.com/s/CZEOpI2WSKZH-FdT4zvJFQ)

五、CloudNativeCommunity

1. [网络研讨会视频 &amp; PPT 分享 | GitOps 及 OAM 的落地实践](https://mp.weixin.qq.com/s/3O9QDnQE4X56d4mXZ9R2zg)

六、mohuishou

1. [Go工程化(八) 单元测试](https://mp.weixin.qq.com/s/UBCiGXGA8DA0V_jegB0VGQ)

2. [Go工程化(二) 项目目录结构](https://mp.weixin.qq.com/s/_yCG3hs3iFxZVUQ6YMhpaA)

3. [Go工程化(一) 架构整洁之道阅读笔记](https://mp.weixin.qq.com/s/XwrLHuWyo0lypT1NGaRh7A)

七、Go招聘

1. [单身的Gopher快来‘探探’路](https://mp.weixin.qq.com/s/wCMKDJfcZQ0gAaLIjqXr7A)
 
## GOCN每日新闻--2021-03-09 

1.从 bug 中学习：六大开源项目告诉你 go 并发编程的那些坑 https://mp.weixin.qq.com/s/FDV77dO9nwtPltmx5cB7Lw

2.从 MPG 线程模型，探讨 Go 语言的并发程序 https://segmentfault.com/a/1190000039371156

3.手撸 golang GO 与微服务 ChatServer 之 3 压测与诊断 https://segmentfault.com/a/1190000039370281

4.Go reflection 三定律与最佳实践 https://mp.weixin.qq.com/s/uGWQLTQuZDZokVNmwwA7bA

5.生成艺术图的 Go 库 https://github.com/jdxyw/generativeart


## gopherDaily--2021-03-09
1.如何在Go中组织项目结构 - https://www.dudley.codes/posts/2021.02.23-golang-struct-organization/

2.gohugo作者Steve Francia专访：gohugo起源、学习go的技巧和开源贡献 - https://www.gremlin.com/blog/podcast-break-things-on-purpose-steve-francia-product-and-strategy-lead-at-google/

3.DeepValueNetwork是一个由其社区管理和托管的点对点数据库网络 - https://github.com/deepvalue-network/software

4.遵循最佳实践可能让你的程序变慢 - https://stackoverflow.blog/2021/03/03/best-practices-can-slow-your-application-down/

5.如何用Go为envoy构建一个Filter - https://github.com/myteksi/ego-demo

6.k9s: kubernetes的命令行UI - https://medium.com/flant-com/k9s-terminal-ui-for-kubernetes-aeead8b0303f

7.pg: Go ORM库，专注于PostgreSQL的特性和性能 - https://github.com/go-pg/pg

8.在数据中寻找趋势 - 使用Go实现线性回归 - https://synchrodynamic.com/finding-trends-in-data-golang-linear-regression/

9.使用Consul时提供过期DNS条目的好处 - https://blog.cloudflare.com/the-benefits-of-serving-stale-dns-entries-when-using-consul/

10.耶鲁公开课：游戏理论 - https://oyc.yale.edu/economics/econ-159

11.为什么软件项目需要的时间比你想象的要长：一个统计模型 - https://erikbern.com/2019/04/15/why-software-projects-take-longer-than-you-think-a-statistical-model.html

## 码农桃花源--2021-03-09
### 文章分享
1 [dubbo-go如何实现路由策略功能](https://segmentfault.com/a/1190000022523595?utm_source=sf-related)

2 [造轮子-golang哈希表实现](https://segmentfault.com/a/1190000039219752)


3 [五福背后的3D引擎](https://segmentfault.com/a/1190000039304848)

### 面试题
1 输入 ping IP 后敲回车，发包前会发生什么？

2 关于 epoll 和 select 的区别，哪些说法是正确的？（多选）

A. epoll 和 select 都是 I/O 多路复用的技术，都可以实现同时监听多个 I/O 事件的状态。

B. epoll 相比 select 效率更高，主要是基于其操作系统支持的I/O事件通知机制，而 select 是基于轮询机制。

C. epoll 支持水平触发和边沿触发两种模式。

D. select 能并行支持 I/O 比较小，且无法修改。

### 每日算法
lc895 最大频率栈 https://leetcode-cn.com/problems/maximum-frequency-stack/

## go中文网每日资讯--2021-03-08 

一、Go语言中文网

1. [我是如何在 Go 中构建 Web 服务的](https://mp.weixin.qq.com/s/lrG-sakk5EfMSLfoJV-Hyw)

2. [Go垃圾回收系列之二：标记准备](https://mp.weixin.qq.com/s/UjGmc9SkUlI48Gl3yVGlSA)

二、亚军进化史

1. [Go技术日报(2021-03-07)——Go 工程化(七) Go Module](https://mp.weixin.qq.com/s/u1jlP2e5rDuy0D4lkcaUYQ)

三、脑子进煎鱼了

1. [问个 Go 问题，字符串 len == 0 和 字符串== &quot;&quot; ，有啥区别？](https://mp.weixin.qq.com/s/rMygbfaLAF5NF206uEUJKA)

四、mohuishou

1. [Go并发编程(一) goroutine](https://mp.weixin.qq.com/s/NJCXUit5tuISl4WSkT5hpA)

2. [Go并发编程(二) Go 内存模型](https://mp.weixin.qq.com/s/toN5tUXnF6sExPb0d78jxQ)

3. [Go并发编程(三) data race](https://mp.weixin.qq.com/s/BYOYE6KCtcuKoI3fCjcO7A)

五、转角遇到GitHub

1. [NutsDB：又一个 Go  内嵌型 K/V 数据库](https://mp.weixin.qq.com/s/8sCNEwchLseycZQh5-oAWQ)

六、taowen

1. [打造杰出软件开发团队的12条指导建议](https://mp.weixin.qq.com/s/fdsczP9vB0XFWMdwtChyEQ)

七、微服务实践

1. [还在用crontab? 分布式定时任务了解一下](https://mp.weixin.qq.com/s/liZl74BeSH56fzqAwjsFeA)

八、k8s技术圈

1. [Kubernetes 原生 CI/CD 构建框架 Tekton 详解！](https://mp.weixin.qq.com/s/jokzB9MgyAl6ZfxJbbgxnQ)

九、五分选手

1. [Go reflection 三定律与最佳实践](https://mp.weixin.qq.com/s/uGWQLTQuZDZokVNmwwA7bA)


## GOCN每日新闻--2021-03-08 

1.[Go 分布式定时任务框架 ](https://segmentfault.com/a/1190000039361384)

2.[Go 问题：字符串 len==0 和字符串== "" 有啥区别？](https://mp.weixin.qq.com/s/rMygbfaLAF5NF206uEUJKA)

3.[手撸 golang GO 与微服务 ChatServer 之 2 ](https://segmentfault.com/a/1190000039362149)

4.[Go 项目中代码组织的两种模式 ](https://mp.weixin.qq.com/s/MB9TDhiZi9vuSnOBX-XdoQ)

5.[Docker 容器技术搭建百万并发压测环境 ](https://mp.weixin.qq.com/s/xbzNpVyOrCD7KWA1Ng3emA)



## gopherDaily--2021-03-08 
- 1.[使用Go构建Web前端]( https://philippta.github.io/web-frontends-in-go/)

- 2.[Go并发模式：pipeline ](https://yuliangunawan19.medium.com/go-concurrency-pattern-pipelines-5935ffaf33fb)
- 3.[带语法高亮的go doc]( https://github.com/ravener/gopherdoc)
- 4.[将CockroachDB从dep迁移到go module](https://www.cockroachlabs.com/blog/dep-go-modules/) 
- 5.[Go错误、panic和recover]( https://dev.to/seventech/error-panic-and-recover-in-golang-486l)
- 6.[k8s本地开发环境候选者比较 ](https://itnext.io/kubernetes-local-playground-alternatives-e1a590632b9f)
- 7.[油管视频：探索k3s和k3sup ](https://www.youtube.com/watch?v=_1kEF-Jd9pw)
- 8.[在k8s内运行ghost博客实战 ](https://blog.appstack.one/how-to-run-ghost-blog-inside-kubernetes/)
- 9.[如何备份fabric区块链网络 ](https://allyourfeeds.com/blockchain/news/how-to-take-a-backup-for-your-hyperledger-fabric-network)
- 10.[hyperledger介绍2021版 ](https://decrypt.co/resources/hyperledger)


## 码农桃花源--2021-03-08
### 文章分享
1 [grpc从实践到原理](https://eddycjy.com/posts/go/talk/2019-06-29-talking-grpc/)

2 [dubbo-go云原生引擎探索](https://segmentfault.com/a/1190000025122783)

3 [golang 撮合引擎 从思路到MVP](https://mp.weixin.qq.com/s/DvUh0igObcRsyEWrg1NMAw)

### 面试问题
1 从 innodb 的索引结构分析，为什么索引的 key 长度不能太长？

2 innodb关键特性

3 MySQL 的数据如何恢复到任意时间点？

4 讲一讲mvcc的redo log、undo log，和binlog有什么不同

### 每日算法
lc891 子序列宽度之和



## go中文网每日资讯--2021-03-07 


一、Go语言中文网

1. [Go语言爱好者周刊：第 85 期 — 女神节快乐](https://mp.weixin.qq.com/s/OQDZSSIMcDhC1IAylyZNLQ)

2. [如何快速成为go语言 contributor](https://mp.weixin.qq.com/s/ITJeSW-kUT5SFAhAaTt0cg)

二、亚军进化史

1. [Go技术日报(2021-03-06)——955 不加班公司名单](https://mp.weixin.qq.com/s/sgzDHFb4PcwbGdBU2huNFQ)

三、吴亲强的深夜食堂

1. [Go 语言的参数传递](https://mp.weixin.qq.com/s/lOQHBJ-oUf9YsnGw4zkmig)

四、luozhiyun很酷

1. [Go中定时器实现原理及源码解析](https://mp.weixin.qq.com/s/B83rfy9nkO4w0_FjyFn4MQ)

五、新亮笔记

1. [管理认知（一）](https://mp.weixin.qq.com/s/gufAKJWDcRQA0vgRFTwcmw)

六、mohuishou

1. [Go工程化(七) Go Module](https://mp.weixin.qq.com/s/w7-usetlAnfpnFmfJNb7rw)

七、GolangWeekly

1. [Awesome Go Newsletter - Issue 250, Mar 04, 2021 | LibHunt](https://go.libhunt.com/newsletter/250)

2. [Golang Weekly Issue 352: March 5, 2021](https://golangweekly.com/issues/352)
## GOCN每日新闻--2021-03-07
1.Go 中定时器实现原理及源码解析 https://www.luozhiyun.com/archives/458

2.Go 工程化 (七) Go Module http://lailin.xyz/post/go-training-week4-go-module.html

3.Alluxio 助力 Kubernetes，加速云端深度学习 https://mp.weixin.qq.com/s/te2QMhcK0Gi_P9yGyvvlFA

4.Go 面向对象编程篇（五）：接口定义及实现 https://mp.weixin.qq.com/s/UdFbW0r8B8nzcb9jT97_ZA

5.手撸 golang GO 与微服务 ChatServer 之 1 https://segmentfault.com/a/1190000039358823

## gopherDaily--2021-03-07 
- 1.Redmonk 2021.1月编程语言排行榜，Go排名第16 - https://redmonk.com/sogrady/2021/03/01/language-rankings-1-21/
- 2.Web开发人员眼中Go的优势、劣势与威胁- https://blog.codonomics.com/2021/03/go-strengths-weaknesses-and-threats.html
- 3.Go实现Bridge模式 - https://golangbyexample.com/bridge-design-pattern-in-go/
- 4.Go包/module vanity url服务器 - https://github.com/nofeaturesonlybugs/goovus
- 5.if-else-switch by Robert C. Martin (Uncle Bob) - http://blog.cleancoder.com/uncle-bob/2021/03/06/ifElseSwitch.html
- 6.如何在GKE的Kubernetes上使用Nginx入口设置内部和外部负载均衡器 - https://spltech.co.uk/how-to-setup-multiple-ingress-controller-with-nginx-ingress-on-gke/
- 7.通过网络管道攻击Kubernetes集群：第1部分 - https://www.cyberark.com/resources/threat-research-blog/attacking-kubernetes-clusters-through-your-network-plumbing-part-1
- 8.Go实现的社区搜索引擎 - https://github.com/cblgh/lieu
- 9.使用多容器pod扩展Kubernetes上的应用程序 - https://learnk8s.io/sidecar-containers-patterns
- 10.将多个VirtualServices附加到Istio Gateway - https://learncloudnative.com/blog/2020-11-23-multiple-vs-gateway
- 11.AWS S3当年的设计决策内幕 - https://cacm.acm.org/magazines/2021/3/250706-a-second-conversation-with-werner-vogels/fulltext
## go中文网每日资讯--2021-03-06

一、Go语言中文网

1. [使用Go进行日志分析并生成excel,再也不担心做日志分析了](https://mp.weixin.qq.com/s/MGeM8XfaIpKSwh9cL5Ti-A)

2. [详解 Go 反射并实战一例](https://mp.weixin.qq.com/s/V2hcadvRmjy6Lr9bUoBLmw)

二、亚军进化史

1. [Go技术日报(2021-03-05)——Go 面试题： new 和 make 是什么，差异在哪？](https://mp.weixin.qq.com/s/JygINRQJj6swuUcuwVw-lA)

三、k8s技术圈

1. [基于 Kubernetes 的微服务项目设计与实现](https://mp.weixin.qq.com/s/AMWjZuJxYVAvHEKznxt-2w)

四、polarisxu

1. [【内推】一大波 Go 相关职位涌来：金山办公 wps 招聘](https://mp.weixin.qq.com/s/zt2RJwCst7Back7k8IKZfg)

五、Go招聘

1. [955 不加班公司名单](https://mp.weixin.qq.com/s/DfrwMYrTWsQaB9RQKHwySg)

六、mohuishou

1. [Go工程化(五) API 设计下: 基于 protobuf 自动生成 gin 代码](https://lailin.xyz/post/go-training-week4-protoc-gen-go-gin.html)

2. [Go工程化(六) 配置管理 - Mohuishou](https://lailin.xyz/post/go-training-week4-config.html)


## GOCN每日新闻--2021-03-06
1.Go channel 的妙用 https://gocn.vip/topics/11747

2.详解 Go 反射并实战一例 https://mp.weixin.qq.com/s/V2hcadvRmjy6Lr9bUoBLmw

3.Deep Learning 部署 TVM Golang 运行时 Runtime https://blog.51cto.com/15103030/2648898

4.Golang+chromedp+goquery 简单爬取动态数据 https://www.cnblogs.com/xiaomotong/p/14488865.html

5.GoLang+Elasticsearch 普通分页过滤查询 https://blog.51cto.com/15103030/2649175

## gopherDaily--2021-03-06 
- 1.Go中的5个常见错误：初学者在编写Go时错过的好模式列表 - https://deepsource.io/blog/common-mistakes-in-go/
- 2.Go事件溯源(event sourcing)框架 - https://github.com/eventually-rs/eventually-go
- 3.在Red Hat Enterprise Linux上使用delve调试Go程序 - https://developers.redhat.com/blog/2021/03/03/using-delve-to-debug-go-programs-on-red-hat-enterprise-linux/
- 4.油管视频：使用WebRTC实现一个在线浏览器多人游戏 - https://www.youtube.com/watch?v=PLmauY3ky4g
- 5.油管视频：解开Kubernetes网络策略的神秘面纱 - https://www.youtube.com/watch?v=LoljdaEaHjY&t=100s
- 6.使用Go、grpc、kafka等实现整洁架构 - https://dev.to/aleksk1ng/go-kafka-grpc-and-mongodb-microservice-with-metrics-and-tracing-448d
- 7.使用Go将文字嵌入图片中 - https://josemyduarte.github.io/2021-02-28-quotes-on-images-with-go/
- 8.关于基于Go的恶意软件，您需要了解什么 - https://nationalcybersecuritynews.today/what-you-need-to-know-about-golang-based-malware-malware-ransomware-hacking/
- 9.观点：自服务的k8s namespace将改变游戏规则 - https://itnext.io/self-service-kubernetes-namespaces-are-a-game-changer-19bd2f59f06b
- 10.git项目中被禁止使用的C函数 - https://github.com/git/git/blob/master/banned.h

## 码农桃花源--2021-03-06
### 优质文章汇总
1. [内存对齐底层原理](https://mp.weixin.qq.com/s/F0NTfz-3x3UxQeF-GSavRg)

2. [复习：图解slab](http://www.wowotech.net/memory_management/426.html)

3. [图解linux网络包接收过程](https://mp.weixin.qq.com/s/GoYDsfy9m0wRoXi_NCfCmg)

4. [复习 g0 栈和用户栈如何完成切换](https://mp.weixin.qq.com/s/sGR_VF13Czd9VuvHb-96iA)

5. [属于曹大的书评](https://www.yuque.com/wegoer/we-reading/epck8l)

### 面试问题

1. redis的同步机制

2. redis有哪几种对象类型，分别适用于什么场景？

3. 最新的redis 6.0用了多线程，是怎么实现的

4. redis的跳表了解吗，数据结构是怎么样的，查询的时间复杂度是多少

5.  Redis 为什么在对数据进行快照持久化时会需要使用子进程

6. redis如何保证重写后的数据库状态和AOF文件一致？

7. Etcd满足了CAP中哪两个特性？应用场景？

8. MVCC是什么，是如何实现的，算法说一下？

9. mysql的隔离级别有几种，默认的隔离级别是什么，互联网常用的隔离级别是什么？

10. B+树索引的最底层单元是什么？什么决定了B+树的高度？B+树的叶子节点是单向链表还是双向链表?

11. B树和B+树区别

12. 聚集索引与非聚集索引

13. 非聚集索引一定回表查询吗(覆盖索引)?

14. 使用过 Redis 分布式锁么，它是什么回事？

15. 假如 Redis 里面有 1 亿个 key，其中有 10w 个 key 是以某个固定的已知的前缀开头的，如果将它们全部找出来？

16. new和make的区别

17. 引用类型都有哪些

18. go的内存模型中，为什么小对象多了会造成gc压力

19. 将10阶对称矩阵压缩存储到一维数组A中，则数组A的长度最少为


## go中文网每日资讯--2021-03-05


一、Go语言中文网

1. [Go：使用 Delve 和 Core Dump 调试代码](https://mp.weixin.qq.com/s/bwC12L1_h0Vl4e1wk50Fjw)

2. [图解Go语言Context](https://mp.weixin.qq.com/s/i3kFGzbaCT9uwdF1Rd3Hpw)

3. [boss: 这小子还不会使用validator库进行数据校验，开了～](https://mp.weixin.qq.com/s/rleIt9uVn0-OobCuOhnlqQ)

二、亚军进化史

1. [Go技术日报(2021-03-04)——一文快速了解 Go+，还有机会和创始人面基](https://mp.weixin.qq.com/s/fS2lzlVIJ8eKHsKeKCyTCA)

三、Go招聘

1. [【上海招聘】数据隐私很重要：招 gopher 保驾护航](https://mp.weixin.qq.com/s/NZmCcj5Pf2PvPCEP4Lsj-Q)

四、学而思网校技术团队

1. [解读从HTTP1.1到HTTP3的进化过程](https://mp.weixin.qq.com/s/COrEqpciflmRBLQykEfZDA)

五、k8s技术圈

1. [Kubernetes 原生 CI/CD 构建框架 Argo 详解！](https://mp.weixin.qq.com/s/Rxq4cTIq-5AIC-k1DWYAMQ)

六、脑子进煎鱼了

1. [Go 面试题： new 和 make 是什么，差异在哪？](https://mp.weixin.qq.com/s/tZg3zmESlLmefAWdTR96Tg)

七、奇伢云存储

1. [Linus Torvalds 命名 [ 冰封荒原 ] 版 Linux 内核的思考](https://mp.weixin.qq.com/s/xZsxYhUmZV5-vrAD6Cb8Bw)

八、MoeLove

1. [K8S 生态周报| Docker v20.10.5 发布，修复 Bug 及提升稳定性](https://mp.weixin.qq.com/s/3LPNJDiBRpRZd09kK3J0XQ)



## GOCN每日新闻--2021-03-05

1. 曹大吐槽 Go mod https://mp.weixin.qq.com/s/N-mztlf9ARJUXd9wJGC4BQ

2. VS Code 中添加 Snippet 提高 Golang 编辑效率 https://gocn.vip/topics/11737

3. 实现一个更全面的 Golang 版本的布谷鸟过滤器 https://gocn.vip/topics/11741

4. 探索 Go1.16 io/fs 包以提高测试性能和可测试性 https://gocn.vip/topics/11740

5. 即時效能分析工具 Pyroscope https://gocn.vip/topics/11742


## gopherDaily--2021-03-05

1.Go中的5个常见错误：初学者在编写Go时错过的好模式列表 - https://deepsource.io/blog/common-mistakes-in-go/

2.Go事件溯源(event sourcing)框架 - https://github.com/eventually-rs/eventually-go

3.在Red Hat Enterprise Linux上使用delve调试Go程序 - https://developers.redhat.com/blog/2021/03/03/using-delve-to-debug-go-programs-on-red-hat-enterprise-linux/

4.油管视频：使用WebRTC实现一个在线浏览器多人游戏 - https://www.youtube.com/watch?v=PLmauY3ky4g

5.油管视频：解开Kubernetes网络策略的神秘面纱 - https://www.youtube.com/watch?v=LoljdaEaHjY&t=100s

6.使用Go、grpc、kafka等实现整洁架构 - https://dev.to/aleksk1ng/go-kafka-grpc-and-mongodb-microservice-with-metrics-and-tracing-448d

7.使用Go将文字嵌入图片中 - https://josemyduarte.github.io/2021-02-28-quotes-on-images-with-go/

8.关于基于Go的恶意软件，您需要了解什么 - https://nationalcybersecuritynews.today/what-you-need-to-know-about-golang-based-malware-malware-ransomware-hacking/

9.观点：自服务的k8s namespace将改变游戏规则 - https://itnext.io/self-service-kubernetes-namespaces-are-a-game-changer-19bd2f59f06b

10.git项目中被禁止使用的C函数 - https://github.com/git/git/blob/master/banned.h

## 码农桃花源--2021-03-05
### 文章分享
1.[go反模式] https://colobu.com/2020/05/26/golang-anti-pattern-yuezudaipao/

2.[如何配置sql.DB获取更好的性能] https://colobu.com/2020/05/18/configuring-sql-DB-for-better-performance-2020/

3.[复习 g0 栈和用户栈如何完成切换] https://mp.weixin.qq.com/s/sGR_VF13Czd9VuvHb-96iA

4.[属于曹大的书评] https://www.yuque.com/wegoer/we-reading/epck8l
### 面试问题
1. new和make的区别

2. 引用类型都有哪些

3. go的内存模型中，为什么小对象多了会造成gc压力

4. 将10阶对称矩阵压缩存储到一维数组A中，则数组A的长度最少为
### 每日算法
lc239 滑动窗口最大值


## go中文网每日资讯--2021-03-04


一、Go语言中文网

1. [Goroutine 的切换过程涉及了什么](https://mp.weixin.qq.com/s/r0y4Fweq-YGo1FZrsNsl3A)

2. [Go：以单件方式创建和获取数据库实例](https://mp.weixin.qq.com/s/noo1C6fYzOQV2PCRZLis9w)

二、亚军进化史

1. [Go技术日报(2021-03-03)——微软真棒：出 Go 语言教程了](https://mp.weixin.qq.com/s/BMcmVU-4SLjnm83t5abJnw)

三、polarisxu

1. [一文快速了解 Go+，还有机会和创始人面基](https://mp.weixin.qq.com/s/wL4GQGTdgGzhtgCVsqnS_Q)

四、TechPaper

1. [Go mod 之痛](https://mp.weixin.qq.com/s/ihtvAyJLtwvAXVkBuqL8kw)

五、网管叨bi叨

1. [Kubernetes群集的零停机服务器更新](https://mp.weixin.qq.com/s/ThwQ7WaczaydO2ppkGh08A)

六、Golang来啦

1. [图解Go语言Context](https://mp.weixin.qq.com/s/SuYSo_APH2viuWiVxezyVQ)

七、多颗糖

1. [【MIT 6.824】学习笔记 3: GFS](https://mp.weixin.qq.com/s/vKsGSciBt14cOn8-5qHk0g)

八、PingCAP

1. [Chaos Mesh® 的 Chaos Engineering as a Service 探索之路](https://mp.weixin.qq.com/s/QbpvyDmSz0r-K20DhMibQw)

九、Go招聘

1. [想跟Gorm作者做同事嘛？一起来字节做性能分析平台吧！](https://mp.weixin.qq.com/s/r_0C9q-Tl7VPW-gyQ6ivuQ)
 
 
 
## GOCN每日新闻--2021-03-04
1.Go 实现 LRU Cache https://dev.to/clavinjune/lru-cache-in-go-1cfk

2.如何在 Go 编写无错误的 Goroutine https://itnext.io/how-to-write-bug-free-goroutines-in-go-golang-59042b1b63fb

3.从实践到原理，带你参透 gRPC https://eddycjy.com/posts/go/talk/2019-06-29-talking-grpc/

4.使用 Go 1.16 创建一个自包含的 Blog 服务器 https://www.brian.dev/self-contained-blog-server-with-go-1-16/

5.Go WebAssembly 运行时引擎 https://github.com/wasmerio/wasmer-go

## gopherDaily--2021-03-04
1. SD Times：为什么开发人员喜欢Go - https://sdtimes.com/softwaredev/why-developers-love-go/

2. 提升Go代码质量的工具 - https://dzone.com/articles/tools-to-improve-your-golang-code-quality

3. sql: 数据操作的瑞士军刀，关系数据的jq, 用于检查，查询，联接，导入和导出数据 - https://sq.io/

4. 在Go中使用javascript插件 - https://www.innoq.com/de/blog/go-plugins-with-javascript/

5. Go中的生成艺术图 - https://github.com/jdxyw/generativeart

6. Harbor v2.2和2020年回顾 - https://goharbor.io/blog/harbor-2.2/

7. 升级到istio 1.8和1.9 - https://karlstoney.com/2021/03/03/upgrading-to-istio-1-8-and-1-9/index.html

8. 编写整洁go代码 - https://github.com/Pungyeon/clean-go-article

9. kubernetes开发环境对比 - https://loft-sh.medium.com/kubernetes-development-environments-a-comparison-f4fa0b3d3d8b

10. 带有热重载和动态本地包的容器中的Go应用 - https://raphaelpralat.medium.com/golang-app-in-a-container-with-hot-reload-and-dynamic-local-package-e860bdc920d5

## 码农桃花源--2021-03-04
### 文章分享
1.[使用 Go 实现 lock-free 的队列](https://colobu.com/2020/08/14/lock-free-queue-in-go/)

2.[main goroutine 的诞生](https://mp.weixin.qq.com/s/ipeLbEnKJ9BkOVtJv6ft0w)

3.[复习 负载均衡和反向代理的区别] https://mp.weixin.qq.com/s/dV0-JJ0PVL-WKSDx57_4-g

4.[微博云原生技术的思考与实践] https://mp.weixin.qq.com/s/KlnmNThKJ2QgiR-2_pZPuQ

### 面试问题
复习，你是否还记得?

1. B树和B+树区别

2. 聚集索引与非聚集索引

3. 非聚集索引一定回表查询吗(覆盖索引)?

4. 使用过 Redis 分布式锁么，它是什么回事？

5. 假如 Redis 里面有 1 亿个 key，其中有 10w 个 key 是以某个固定的已知的前缀开头的，如果将它们全部找出来？
6. 
### 每日算法

lc347  前 K 个高频元素

### 内推
1. [腾讯] https://www.yuque.com/go-interview/set/fqxly6

## go中文网每日资讯--2021-03-03 

一、Go语言中文网

1. [构建微服务的十大 Go 框架/库](https://mp.weixin.qq.com/s/_i31PW_lhuYxKbRM-a8wEA)

2. [超长好文：结合 Java、Go 等讲内存管理设计精要](https://mp.weixin.qq.com/s/0Xhlxm2uZL2I7XHWf3cq1A)

3. [Go 并发编程 — sync.Pool 源码级原理剖析 [2] 终结篇](https://mp.weixin.qq.com/s/bQ2JejnZ4-CZUJlKRTgp8Q)

二、亚军进化史

1. [Go技术日报(2021-03-02)——Go 范型使用介绍](https://mp.weixin.qq.com/s/OUTn4Iw2JARU6p5PPE3Znw)

三、脑子进煎鱼了

1. [令人激动！Go 泛型代码合入 master（附尝鲜方法）](https://mp.weixin.qq.com/s/8kINGyGTYOkNcGEymWK3jQ)

四、Go招聘

1. [360 加大 Go 招聘，Go 形势大好！你来吗？](https://mp.weixin.qq.com/s/gjx3gz6ngTN1d6Sew1nc-w)

五、转角遇到GitHub

1. [微软真棒：出 Go 语言教程了](https://mp.weixin.qq.com/s/7bbJEgmE7LPRpBCVNw_Hcg)


## GOCN每日新闻--2021-03-03 
1.[比 panic 更好的错误处理方式 ](https://tiemma.medium.com/why-is-go-panicking-31ba2351986b)

2.g[olang 实现京东支付 v2 版本 ](https://segmentfault.com/a/1190000039322439)

3.[空结构体引发的大型打脸现场 ](https://mp.weixin.qq.com/s/dNeCIwmPei2jEWGF6AuWQw) 

4.[TiDB 5.0 跨中心部署能力初探 | 中心化还是去中心化？揭秘 TiDB 5.0 事务分布式授时模块](https://gocn.vip/topics/11727 ) 

5.[一个 Go 编写的简易文本编辑器 ](https://github.com/hibiken/mini)


## gopherDaily--2021-03-03 
- 1.[使用Go 1.16创建一个自包含的Blog服务器](https://www.brian.dev/self-contained-blog-server-with-go-1-16/)

- 2.[使用Go实现定制的linter]( https://www.patriscus.com/projects/custom-go-linter/)

- 3.[Go算法：矩阵的螺旋遍历 ](https://habr.com/en/post/543618/)

- 4.[使用gorm操控数据库]( https://blog.feurious.com/total-database-control-in-go-with-gorm)
- 5.[使用Go实现大小端(Endianness)转换 ](https://ariona.fr/blog/posts/2021/golang-sec-1-endian/)

- 6.[通用OPA策略开发](https://itnext.io/universal-opa-policies-development-a3f88226e3d5)

- 7.[微软：迈出使用Go语言的第一步系列](https://docs.microsoft.com/en-us/learn/paths/go-first-steps/)

- 8.[Ristretto-Go中性能最高的并发缓存库](https://webdevstation.com/posts/ristretto-the-most-performant-concurrent-cache-library-for-go/)

- 9.[K8集群设计的OpenShift安全最佳实践](https://www.stackrox.com/post/2020/11/openshift-security-best-practices-part-1-of-5-cluster-design/)

- 10.[如何阅读汇编代码](https://wolchok.org/posts/how-to-read-assembly-language/)

- 11.[DDD被高估 ](https://tilkov.com/post/2021/03/01/ddd-is-overrated/)

- 12.[redhat 2021年企业开源状况报告 ](https://www.redhat.com/rhdc/managed-files/rh-enterprise-open-source-report-f27565-202101-en.pdf)

## 码农桃花源--2021-03-03
### 文章分享
1 [tcp内存开销测试](https://mp.weixin.qq.com/s/BwddYkVLSYlkKFNeA-NUVg)

2 [图解linux网络包接收过程](https://mp.weixin.qq.com/s/GoYDsfy9m0wRoXi_NCfCmg)

3 [复习：布隆过滤器](https://mp.weixin.qq.com/s/0lKehW0Hm_0iL5_wcNjiag)


### 面试问题
1 MVCC是什么，是如何实现的，算法说一下？

2 mysql的隔离级别有几种，默认的隔离级别是什么，互联网常用的隔离级别是什么？

3 B+树索引的最底层单元是什么？什么决定了B+树的高度？B+树的叶子节点是单向链表还是双向链表?

### 每日算法
lc 375 猜数字大小



## go中文网每日资讯--2021-03-02


一、Go语言中文网

1. [惊！Go 编写的恶意软件剧增 2000%](https://mp.weixin.qq.com/s/JtX9ltxHjBm7u3f4h9Nk9Q)

2. [gin框架的几种热加载方法，你值得拥有](https://mp.weixin.qq.com/s/09k6MDYyvJn3tWOqZvJY0Q)

3. [通过实例理解Go标准库http包是如何处理keep-alive连接的](https://mp.weixin.qq.com/s/APjWx-im0LVHdjJt9UkPHw)

二、亚军进化史

1. [Go技术日报(2021-03-01)——常用的分布式唯一 ID 生成方案](https://mp.weixin.qq.com/s/g8cuCA8Ac_wn4hS8kLs2IQ)

三、Go招聘

1. [鹅厂游戏业务招Go这要求，你符合吗？](https://mp.weixin.qq.com/s/Vzeo6YKSArYq29d4WrDflw)

四、CloudNativeCommunity

1. [2021年 Istio 大型“入坑”指南](https://mp.weixin.qq.com/s/WwB49tVZibBEkKOkCVwrBw)

五、真没什么逻辑

1. [内存管理设计精要](https://mp.weixin.qq.com/s/lx0vX-4wlQWxxfj017T9HA)

六、Golang梦工厂

1. [空结构体引发的大型打脸现场](https://mp.weixin.qq.com/s/dNeCIwmPei2jEWGF6AuWQw)

七、mohuishou

1. [Go工程化(四) API 设计上: 项目结构 & 设计](https://lailin.xyz/post/go-training-week4-api-design.html)

八、No Headback

1. [why do we need generics?](https://xargin.com/why-do-we-need-generics/)

## GOCN每日新闻--2021-03-02
1.寻找 Go 依赖中的那个邪恶包 https://michenriksen.com/blog/finding-evil-go-packages/

2.使用 Go + Kqueue 实现一个简单的 TCP Server https://dev.to/frosnerd/writing-a-simple-tcp-server-using-kqueue-cah

3.感受下适配器模式的优势 https://www.hildeberto.com/2021/02/adapter-go-redis.html

4.用 Go 实现 NATs 模式下的实时订阅 https://medium.com/swlh/nats-keep-alive-subscription-in-golang-a80073949371

5.Go 范型使用介绍 https://quii.gitbook.io/learn-go-with-tests/meta/intro-to-generics
## gopherDaily--2021-03-02
1. 通过测试学习Go泛型 - https://quii.gitbook.io/learn-go-with-tests/meta/intro-to-generics

2. 微软文档教程：使用Go控制流 - https://docs.microsoft.com/en-us/learn/modules/go-control-flow/

3. 使用Go开发的类twitter后端 - https://github.com/arman-aminian/twitter-backend

4. 寻找恶意的Go包 - https://michenriksen.com/blog/finding-evil-go-packages/

5. 使用Go进行明智抽象的初学者指南 - https://jonahwintergolang.medium.com/a-beginners-guide-to-sensible-abstractions-using-golang-4faabbabb838

6. 使用Go、React和WebSocket实现在线协作编辑 - https://medium.com/heuristics/collaborative-form-editor-using-websockets-web-sockets-in-golang-and-react-20d123f40447

7. 使用Temporal.io编排微服务架构 - https://spiralscout.com/blog/temporal-workflow-and-microservices

8. 使用Go和yaml实现的kubernetes模式 - https://github.com/sharadbhat/KubernetesPatterns

9. Aqua精彩的四年！ - https://blog.aquasec.com/liz-rice-cloud-native-open-source

10. 基础分布式系统论文推荐列表 - http://muratbuffalo.blogspot.com/2021/02/foundational-distributed-systems-papers.html

11. 文字转换为流程图 - https://flowchart.fun/


## 码农桃花源--2021-03-02
### 文章分享
1 [高并发下的“too many open files”](https://mp.weixin.qq.com/s/GBn94vdL4xUL80WYrGdUWQ)

2 [write一个文件后会引发多大的写IO](https://mp.weixin.qq.com/s/qEsK6X_HwthWUbbMGiydBQ)

3 [复习：图解slab](http://www.wowotech.net/memory_management/426.html)
### 面试问题
1 Redis 为什么在对数据进行快照持久化时会需要使用子进程

2 redis如何保证重写后的数据库状态和AOF文件一致？

3 Etcd满足了CAP中哪两个特性？应用场景？

### 每日算法

lc220 存在重复元素

## go中文网每日资讯--2021-03-01 


一、Go语言中文网

1. [Uber 的 zap 库是如何做到高性能的？](https://mp.weixin.qq.com/s/y8XH4gTo_7l0FkMJe9zxiA)

2. [一份 Go 面经：答案期待一起完善](https://mp.weixin.qq.com/s/CGERaA_hZEjvpSpvzotu9Q)

3. [官发博文：进一步阐明关于 context 的最佳实践](https://mp.weixin.qq.com/s/Xv88vljtnDIRuLM0J_NSpA)

二、亚军进化史

1. [Go技术日报(2021-02-28)——golang 知识总结](https://mp.weixin.qq.com/s/eFWJWx6XlDlfjVe6hlXReg)

三、微服务实践

1. [使用Prometheus搞定微服务监控](https://mp.weixin.qq.com/s/kfI36sEV_lLASbdpu_4S4w)

四、Go招聘

1. [你可能不了解，这两年跨境电商很火的：招 Go 了](https://mp.weixin.qq.com/s/UKAPNHGbWoCPzFirFfWJ5g)

五、polarisxu

1. [那些 Go 语言实现的语言现在发展怎么样了？](https://mp.weixin.qq.com/s/jIdBxFlNnJ_XaGOOsUf_3w)

六、码农桃花源

1. [Go mod 七宗罪](https://mp.weixin.qq.com/s/CBiebXjBcik2pHQnbnB51A)

七、云加社区

1. [详解Go语言调度循环源码实现](https://mp.weixin.qq.com/s/WZqiGvIMyR7QYmGgSWg60g)

八、奇伢云存储

1. [Go 并发编程 — sync.Pool 源码级原理剖析 [2] 终结篇](https://mp.weixin.qq.com/s/u0HZYgPVec9CET5d4wTPbA)


九、Golang梦工厂

1. [高并发系统的限流策略：漏桶和令牌桶(附源码剖析)](https://mp.weixin.qq.com/s/fURwiSTeEE_Wvc95Q_fHnA)
## GOCN每日新闻--2021-03-01 
1.常用的分布式唯一 ID 生成方案 https://mp.weixin.qq.com/s/BNCaeEu-XRqbR-z6VM1QPg

2.高并发系统的限流策略：漏桶和令牌桶 (附源码剖析) https://mp.weixin.qq.com/s/fURwiSTeEE_Wvc95Q_fHnA

3.Golang 语言怎么处理错误？ https://mp.weixin.qq.com/s/DUvLkO5tLUCOp2IeVjgbeg

4.Kubernetes 节点资源不足的高效管理 https://medium.com/kubernetes-tutorials/efficient-node-out-of-resource-management-in-kubernetes-67f158da6e59

5.简单的本地 go git-crypt 实现 https://github.com/jbuchbinder/go-git-crypt

## gopherDaily--2021-03-01
- 1.令我疯狂的Go JSON陷阱，但我已学会应对 - http://okigiveup.net/golang-json-gotchas-that-drove-me-crazy-but-i-have-learned-to-deal-with/
- 2.利用适配器模式将redigo无缝切换为go-redis - https://www.hildeberto.com/2021/02/adapter-go-redis.html
- 3.使用GO和Gorilla Mux进行CRUD操作 - https://pulkitkaushik.medium.com/crud-operations-using-golang-with-gorilla-mux-f1ee6addec4c
- 4.Go工具链介绍 - https://dev.to/honeybadger/an-introduction-to-go-tooling-3cl8
- 5.chkb：可以将你的键盘变成可编程键盘的Go工具 - https://github.com/MetalBlueberry/chkb
- 6.边缘计算云原生开源方案选型比较 - https://mp.weixin.qq.com/s/wl-7ZRUu3l97wpbRAKjQpw
- 7.基于kubeedge的AI套件 - https://github.com/kubeedge/sedna
- 8.在使用kubernetes之前为什么要看看hashicorp nomad - https://atodorov.me/2021/02/27/why-you-should-take-a-look-at-nomad-before-jumping-on-kubernetes/
- 9.5G技术栈的开源状况 - https://github.blog/2021-02-23-open-source-in-the-5g-stack/
## 码农桃花源--2021-03-01
## 文章分享
1 [内存对齐底层原理](https://mp.weixin.qq.com/s/F0NTfz-3x3UxQeF-GSavRg)

2 [从文件中读取一个字节引发的磁盘IO](https://mp.weixin.qq.com/s/LcuWAg10hxZjCoyR1cMJSQ)

3 [复习：如何理解高并发的协程](https://mp.weixin.qq.com/s/UDGVOq1RaP7BRvP0cgd_bg)

## 面试问题
1 redis的同步机制

2 redis有哪几种对象类型，分别适用于什么场景？

3 最新的redis 6.0用了多线程，是怎么实现的

4 redis的跳表了解吗，数据结构是怎么样的，查询的时间复杂度是多少

## 每日算法
lc377 组合优化IV
## go中文网每日资讯--2021-02-28 

一、Go语言中文网

1. [Go语言爱好者周刊：第 84 期 — 有人在写Go泛型图书了](https://mp.weixin.qq.com/s/LdQ1sPIVVm_YAsJvIuy3Lw)

2. [Go 官方应该搞一个类似 Rustup 的管理工具](https://mp.weixin.qq.com/s/OZDmzdC1SMQ7jt-iByhkmA)

3. [一文搞懂 Go 如何利用multipart/form-data实现文件的上传与下载](https://mp.weixin.qq.com/s/OHzXxfcBaf5RNT4dA38LCQ)

二、亚军进化史

1. [Go技术日报(2021-02-27)——关于 context 的一点最佳实践](https://mp.weixin.qq.com/s/wQjMLNMXAPnapm_Xx6E_Rw)

三、新亮笔记

1. [Go - 代码生成工具](https://mp.weixin.qq.com/s/hFasUWIE_mTIIC-tjWUXzg)

四、面向信仰编程

1. [内存管理设计精要 - 面向信仰编程](https://draveness.me//system-design-memory-management)

五、技术琐话

1. [基于Golang的高性能撮合引擎：从思路到MVP](https://mp.weixin.qq.com/s/DvUh0igObcRsyEWrg1NMAw)

六、Golang Weekly

1. [Awesome Go Newsletter - Issue 249, Feb 25, 2021 | LibHunt](https://go.libhunt.com/newsletter/249)

2. [Golang Weekly Issue 351: February 26, 2021](https://golangweekly.com/issues/351)
## GOCN每日新闻--2021-02-28
1.基于 Golang 的高性能撮合引擎：从思路到 MVP https://mp.weixin.qq.com/s/DvUh0igObcRsyEWrg1NMAw

2.如何有效地测试 Go 代码 https://mp.weixin.qq.com/s/_2oqgVaq7vCgMBDWYCASIw

3.手撸 golang 基本数据结构与算法 图的最短路径 贝尔曼 - 福特算法
https://segmentfault.com/a/1190000039299119

4.一套轻量级 Go 微服务框架- kratos https://github.com/go-kratos/kratos

5.golang 知识总结 https://www.cnblogs.com/darope/p/14455404.html

## gopherDaily--2021-02-28
1.过去几年，使用Go编写的新恶意软件增长了2000％，并且已经被APT(国家级黑客组织)和电子犯罪组织所采用 - https://www.zdnet.com/article/go-malware-is-now-common-having-been-adopted-by-both-apts-and-e-crime-groups/

2.一文弄清楚NATS, NATS Streaming和NATS JetStream的区别 - https://gcoolinfo.medium.com/comparing-nats-nats-streaming-and-nats-jetstream-ec2d9f426dc8

3.适用于Go应用程序的PostgreSQL Aiven - https://aiven.io/blog/aiven-for-postgresql-for-your-go-application

4.Go webassembly运行时引擎wasmer-go 发布1.0 - https://wasmer.io/posts/wasmer-go-embedding-1.0

5.可追溯的和安全的错误代码填充代码的工具 - https://github.com/vsrc/isecode

6.油管视频：Go泛型介绍 - https://www.youtube.com/watch?v=x3KULj5406g&list=PLEcwzBXTPUE_YQR7R0BRtHBYJ0LN3Y0i3&index=1

7.bit: Go实现的git全功能客户端 - https://github.com/chriswalz/bit

8.显示你最常用的shell命令 - https://github.com/irevenko/tsukae

9.Go Testify: 如何在失败的测试上强制测试退出 - http://blog.muya.co.ke/golang-testify-force-test-exit/

10.经典旧文：在Go中如何创建常量map、切片和数组 - https://qvault.io/2019/10/21/golang-constant-maps-slices/

11.Chain Replication with Apportioned Queries(CRAQ)的Go实现 - https://github.com/despreston/go-craq

12.nginx日志探索工具(in Rust) - https://github.com/Canop/rhit

13.CTO资料速查表 - https://github.com/kuchin/awesome-cto

14.油管视频：五小时搞定pytorch - https://www.youtube.com/watch?v=c36lUUr864M&feature=youtu.be

15.vim高级指南 - https://thevaluable.dev/vim-advanced/


## go中文网每日资讯--2021-02-27 


一、Go语言中文网

1. [你还缺 Go 实战项目吗？送你一个 Go 构建数字写作社区的开源项目](https://mp.weixin.qq.com/s/65SbmgTbTRPP8-_8wa40Bg)

2. [从 Go 语言一个文件描述符错误讲起](https://mp.weixin.qq.com/s/MGMWkOON3DBkSjBKxGr7Kw)

3. [创业公司招 Go，奖金真不少](https://mp.weixin.qq.com/s/zfxhmINexqkNUNPnfC6nbQ)

二、亚军进化史

1. [Go技术日报(2021-02-26)——​Go 还是需要泛型的](https://mp.weixin.qq.com/s/fInRC5AMy-6OkmkGF4Hq7w)

三、nanko的快乐小窝

1. [​Goalng 校招面经](https://mp.weixin.qq.com/s/Ojz3qRCrZwmkyO9B_4k17Q)

四、taowen

1. [编程就是压缩](https://mp.weixin.qq.com/s/suRIYWo84TORN3lMx4QLwA)

五、k8s技术圈

1. [Go 工程师 – CODING(腾讯系)](https://mp.weixin.qq.com/s/76-89Ii0ep1kvQC1GFNXFg)

2. [如何利用开源框架实现运维编排](https://mp.weixin.qq.com/s/wplsNFuF42ZlLXN-z3h_zw)

六、GoOfficialBlog

1. [The Go Blog: 关于 context 的一点最佳实践](https://mp.weixin.qq.com/s/ayySDQNTRlxjHuiAsaIwhw)

七、奇伢云存储

1. [Go 并发编程 — 有趣的sync.Pool原理动画](https://mp.weixin.qq.com/s/PeVkQN5sHR2d3fgmgoMt3Q)

八、xueyuanjun

1. [Go 函数式编程篇（七）：基于管道技术实现函数的流式调用](https://mp.weixin.qq.com/s/9P1AV6d_Cc4pH9DNJeEHHg)

九、polarisxu

1. [金三银四，聊聊换工作的那些事](https://mp.weixin.qq.com/s/kaOIwV50zUvHv8tIjejFxA)


## GOCN每日新闻--2021-02-27

1.Golang 指针讲解 https://youtu.be/sTFJtxJXkaY

2.Go 实现都配置管理 cli COGS https://github.com/Bestowinc/cogs/

3.golang os.File 的加密替换文件，存储的文件将具有 768 位加密 https://github.com/kuking/seof

4.go 实现的快速，安全，可靠的系统备份 https://github.com/Clivern/Walrus

5.Jupyter 交互的 Go 编程 https://github.com/yunabe/lgo

## gopherDaily--2021-02-27 
- 1.Go观察：一个julia开发人员重新回归go - https://erik-engheim.medium.com/golang-observations-6421f760498b
- 2.基于kqueue编写一个简单的tcp server - https://dev.to/frosnerd/writing-a-simple-tcp-server-using-kqueue-cah
- 3.快速构建Solid Go GraphQL应用程序 - https://github.com/ohler55/graphql-test-tool/blob/develop/example/solid-quick.md
- 4.我如何每周花费4小时便成为Kubernetes的维护者 - https://opensource.com/article/21/2/kubernetes-maintainer
- 5.使用Go构建容器镜像 - https://ahmet.im/blog/building-container-images-in-go/index.html
- 6.Go声明式BDD(行为驱动测试) - https://medium.com/lensesio/declarative-bdd-with-golang-3f5f6a1ac5a8
- 7.为go-sql-server实现一个windows function - https://www.dolthub.com/blog/2021-02-26-implementing-window-functions/
- 8.Go与设计模式 - https://medium.com/swlh/design-patterns-in-go-d90e7866deff
- 9.deferfuzz: 用于对Go defer/panic/recover进行fuzztest - https://github.com/mdempsky/deferfuzz
- 10.Google承认Kubernetes容器技术是如此复杂 - https://www.theregister.com/2021/02/25/google_kubernetes_autopilot/
- 11.油管视频：爬行机器人制作指南 - https://www.youtube.com/watch?v=anp15oVASc4&feature=youtu.be
- 12.10个必读的机器学习文章 - https://elvissaravia.substack.com/p/10-must-read-ml-blog-posts

## 码农桃花源--2021-02-27
### 优质文章汇总
1. [看图学etcd](https://segmentfault.com/a/1190000020742981?utm_source=sf-related)

2. [复习 GPM](https://mp.weixin.qq.com/s/JOjUWp15JbEu54VJHY8i_A)

3. [复习：为什么redis快照使用子进程](https://draveness.me/whys-the-design-redis-bgsave-fork/)

4. [Go netpoller 原生网络模型之源码全面揭秘](https://strikefreedom.top/go-netpoll-io-multiplexing-reactor)

5. [k8s的架构设计与实现原理](https://draveness.me/understanding-kubernetes/)
### 面试问题

1. 多线程的优点有哪些？带来了哪些问题？

2. 死锁产生的条件？如何避免？

3. redis缓存穿透和缓存击穿的区别？分别如何解决？

4. Go指针和unsafe.Pointer有什么区别

5. 如何利用unsafe包修改私有成员

6. 如何利用unsafe获取slice&map的长度

7. 如何实现字符串和byte切片的零拷贝转换

8. redis使用单线程模型，为什么效率也很高？

9.  redis为什么删除缓存而不是更新缓存？

10.  如何保证缓存和数据库的双写一致性？

11. redis快照实现的底层原理

12.  context 如何被取消

13.  context 是什么

14.  context 有什么作用

15.  context.Value 的查找过程是怎样的


16. redis 的过期策略都有哪些？内存淘汰机制都有哪些？手写一下LRU代码实现？

17.  redis 的并发竞争问题是什么？如何解决这个问题？了解 Redis 事务的 CAS 方案吗？

18. HTTP的keep-alive是干什么的？

19. HTTP2相对于HTTP1.x有什么优势和特点？

20. 为什么常说 TCP 有粘包和拆包的问题而不说 UDP ？

21. 介绍一下Linux 中进程的几种状态

22. 针对网站访问慢，怎么去排查？怎么去解决？
## go中文网每日资讯--2021-02-26 

一、Go语言中文网

1. [类似csv的数据日志组件设计与Go实现](https://mp.weixin.qq.com/s/qCVKQCl-LxUbGyQ7HP0sDg)

2. [Go 并发编程 — 深入浅出 sync.Pool ，围观最全的使用姿势，理解最深刻的原理](https://mp.weixin.qq.com/s/7VKtfZPOuo36OGNFYV-L3g)

二、亚军进化史

1. [Go技术日报(2021-02-25)——悄悄告诉你：很可能 Go 1.17 就能尝试泛型](https://mp.weixin.qq.com/s/mB4vzjCqD64R9_suldVZoQ)

三、Golang技术分享

1. [如何有效地测试Go代码](https://mp.weixin.qq.com/s/_2oqgVaq7vCgMBDWYCASIw)

四、学而思网校技术团队

1. [探索Golang协程实现——从v1.0开始](https://mp.weixin.qq.com/s/rYwN5gZXQVvbQ6NZCHC7cA)

五、云加社区

1. [从Paxos到Raft，分布式一致性算法解析](https://mp.weixin.qq.com/s/JfJ8R8qrT-g6G7MDN9Tk6g)

六、Go招聘

1. [实习生Gopher给大家送一份微芯研究院面经](https://mp.weixin.qq.com/s/m5-vhsqEc0o-tRrTUXfF2Q)

2. [上海扩博智能招Gopher，奖金真不少](https://mp.weixin.qq.com/s/R1vkcT1qnMbQPF3oasY7LA)

七、k8s技术圈

1. [运维架构师与运维开发工程师 - DaoCloud](https://mp.weixin.qq.com/s/0Ns3O1q6aEX-HSPNC9j2Dg)

八、TechPaper

1. [Go 还是需要泛型的](https://mp.weixin.qq.com/s/JlNlq8KAZ3jULwkPpXuxzQ)

九、The Go Blog

1. [Contexts and structs](https://blog.golang.org/context-and-structs)
## GOCN每日新闻--2021-02-26
1.探索 "io/fs" 提高测试性能和可测试性 https://www.gopherguides.com/articles/golang-1.16-io-fs-improve-test-performance

2.Go 还是需要泛型的 https://mp.weixin.qq.com/s/JlNlq8KAZ3jULwkPpXuxzQ

3.用 Go 实现事件驱动应用 https://engineering.linecorp.com/zh-hant/blog/20210226-golang-event-driven

4.Great video about Pointers in Go https://www.reddit.com/r/golang/comments/lsb9jc/great_video_about_pointers_in_go/

5.JSON 互操作性漏洞探析 https://labs.bishopfox.com/tech-blog/an-exploration-of-json-interoperability-vulnerabilities

## gopherDaily--2021-02-26
- 1.Go 1.16中值得关注的几个变化 - https://mp.weixin.qq.com/s/UPNn4G_m0zfvJgWxEVl_Tw
- 2.使用io/fs提升测试性能和可测性 - https://www.gopherguides.com/articles/golang-1.16-io-fs-improve-test-performance
- 3.Go时间与日期格式化完全指南 - https://yourbasic.org/golang/format-parse-string-time-date-example/
- 4.对低级I/O进行基准测试：C，C ++，Rust，Go，Java，Python - https://medium.com/star-gazers/benchmarking-low-level-i-o-c-c-rust-golang-java-python-9a0d505f85f7
- 5.Go module管理：实用指南 - https://medium.com/@adiach3nko/package-management-with-go-modules-the-pragmatic-guide-c831b4eaaf31
- 6.gitlab-ci基础入门 - https://techsquad.rocks/blog/gitlab_ci_basics/
- 7.在Kubernetes集群上以零停机时间发布和回滚更新 - https://www.fosstechnix.com/rolling-out-and-rolling-back-updates-with-zero-downtime-on-kubernetes-cluster/
- 8.经典旧文：将happy path向左对齐 - https://medium.com/@matryer/line-of-sight-in-code-186dd7cdea88
- 9.Go播客：那些不该加入go的提案2 - https://changelog.com/gotime/168
- 10.clang LTO(Link Time Optimization) 合并(merge)到linux 5.12内核，后者性能将得到提升 - https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=79db4d2293eba2ce6265a341bedf6caecad5eeb3
- 11.如何使用kong gateway的jwt插件实现服务鉴权 - https://konghq.com/blog/jwt-kong-gateway
- 12.常见的Nginx错误配置使您的Web服务器容易受到攻击 - https://blog.detectify.com/2020/11/10/common-nginx-misconfigurations/
- 13.Web软件的未来是HTML-over-WebSockets - https://alistapart.com/article/the-future-of-web-software-is-html-over-websockets/
- 14.终端命令行形式的密钥管理器 - https://github.com/GGP1/kure
- 15.零依赖的高并发Go应用框架 -https://github.com/autom8ter/machine
- 16.油管视频：详解Go指针 - https://www.youtube.com/watch?v=sTFJtxJXkaY

## 码农桃花源--2021-02-26
### 文章分享
1 [redis IO多线程介绍](http://xiaorui.cc/archives/6918)

2 [复习：先有线程还是先有协程？](https://mp.weixin.qq.com/s/UDGVOq1RaP7BRvP0cgd_bg)

3 [k8s的架构设计与实现原理](https://draveness.me/understanding-kubernetes/)

4 [grpc那些事儿](http://xiaorui.cc/archives/7013)

### 面试问题
1 多线程的优点有哪些？带来了哪些问题？

2 死锁产生的条件？如何避免？

3 redis缓存穿透和缓存击穿的区别？分别如何解决？

### 每日算法
lc212 单词搜索II
## go中文网每日资讯--2021-02-25 

一、Go语言中文网

1. [悄悄告诉你：很可能Go 1.17就能尝试泛型](https://mp.weixin.qq.com/s/iapssANWbSvcOX2qEwI2JQ)

2. [Go 1.16 新特性：撤回模块版本，还有另类用法](https://mp.weixin.qq.com/s/wMUV0J8S-c0HFay6t28r5g)

3. [Go 语言实战：命令行（3）CLI 框架](https://mp.weixin.qq.com/s/zPm5_9e3mPN8J71gB0e_Gg)

二、亚军进化史

1. [Go技术日报(2021-02-24)——滴滴：如何提高代码的可读性，以 Go 为例！](https://mp.weixin.qq.com/s/ZSjAVAExWLrqPZuk-t5Rrg)

三、Go招聘

1. [字节跳动招 Go 要求这么低的吗？这么缺人？](https://mp.weixin.qq.com/s/wizc4W9yo0-3hI5s_nh32A)

四、taowen

1. [代码防腐](https://mp.weixin.qq.com/s/85yWLNQmq99SbBopwNd2MQ)

五、k8s技术圈

1. [Prometheus 通过 consul 实现自动服务发现](https://mp.weixin.qq.com/s/8V4HhbVJ4MVqZOZK3Q_RMA)

六、TonyBai

1. [Go 1.16中值得关注的几个变化](https://mp.weixin.qq.com/s/UPNn4G_m0zfvJgWxEVl_Tw)

七、脑子进煎鱼了

1. [最新提案：维持 GOPATH 的传统使用方式（Go1.17 移除 GOPATH）](https://mp.weixin.qq.com/s/AzfKHfs6AOolxutdVpZibw)

八、polarisxu

1. [Go 官方应该搞一个类似 Rustup 的管理工具](https://mp.weixin.qq.com/s/uqKl8u8Tyz1-d0Ew3dpVJQ)

## gopherDaily--2021-02-25
- 1.Go官博：context与struct - https://blog.golang.org/context-and-structs
- 2.泛型的另一个窘境 - https://matklad.github.io//2021/02/24/another-generic-dilemma.html
- 3.Go 1.16都有哪些变化 - https://blog.logrocket.com/whats-new-in-go-1-16/
- 4.拥抱Go 和云原生的日志系统实践 - https://www.infoq.cn/article/FD43uBOtQ4sq1dTAHxpu
- 5.用Go编写的第二代Matrix家庭服务器 - https://github.com/matrix-org/dendrite
- 6.为什么我们选自tidb作为mysql的替代品 - https://dzone.com/articles/top-car-trading-platform-chooses-scale-out-database-as-mysql-alternative
- 7.tailscale官博：module、大单体与微服务 - https://tailscale.com/blog/modules-monoliths-and-microservices/
- 8.运行时动态构建结构体类型示例 - https://github.com/itsubaki/gostruct
- 9.https://github.com/itsubaki/gostruct
- 10.机器学习中数据准备技术的框架 - https://machinelearningmastery.com/framework-for-data-preparation-for-machine-learning/
- 11.Playstation 2 架构 - https://www.copetti.org/writings/consoles/playstation-2/
- 12.创建一个oracle的docker容器镜像 - https://dzone.com/articles/create-an-oracle-database-docker-image

## 码农桃花源--2021-02-25
### 文章分享
1.  [Go netpoller 原生网络模型之源码全面揭秘](https://strikefreedom.top/go-netpoll-io-multiplexing-reactor)

2.  [gomaxprocs调高引起调度性能损耗](http://xiaorui.cc/archives/6334)

3.  [复习 深入理解WaitGroup](https://lailin.xyz/post/go-training-week3-waitgroup.html)

4.  [go 栈内存的内存和逃逸分析](https://draveness.me/golang/docs/part3-runtime/ch07-memory/golang-stack-management/)

### 面试问题
1. Go指针和unsafe.Pointer有什么区别

2. 如何利用unsafe包修改私有成员

3. 如何利用unsafe获取slice&map的长度

4. 如何实现字符串和byte切片的零拷贝转换

### 每日算法
lc891 子序列宽度之和



## GOCN每日新闻--2021-02-25
1.context 和 struct https://blog.golang.org/context-and-structs 

2.Go 1.17 中将新增对 fuzz test 的支持 https://github.com/golang/go/issues/44551

3.aluma 从 C# 转到 Go 进行后端开发的经验 https://aluma.io/resources/blog/switching-from-c-to-go-for-backend-development 

4.快速构建稳固的 Go GraphQL 应用程序 https://github.com/ohler55/graphql-test-tool/blob/develop/example/solid-quick.md

5.在 Kubernetes 上快速开发 Go 微服务 https://blog.getambassador.io/go-kubernetes-rapidly-developing-golang-microservices-bfe36cfb5893




## go中文网每日资讯--2021-02-24 

一、Go语言中文网

1. [滴滴：如何提高代码的可读性，以 Go 为例！](https://mp.weixin.qq.com/s/FUOUEWOFr-NMJkqZHHengw)

2. [为什么要有字节序？用 Go 解释下](https://mp.weixin.qq.com/s/ZBE5JDPyHuIGRScSfQhO1A)

3. [Go 语言实战：命令行程序（2）](https://mp.weixin.qq.com/s/CLtKN25UFVmeWKh6ULDq8w)

二、亚军进化史

1. [Go技术日报(2021-02-23)——从 go-chi 框架撤回所有主版本聊 Go1.16 的新特性](https://mp.weixin.qq.com/s/HqVtuWehRkykF-g4Kw-VOQ)

三、Go招聘

1. [成都招聘 Go 开发工程师的真不少](https://mp.weixin.qq.com/s/8kU7UlwiDh0sc4_HAdXLIQ)

四、云加社区

1. [从bug中学习：六大开源项目告诉你go并发编程的那些坑](https://mp.weixin.qq.com/s/PmUlFFhf6taeqveLtbHJNQ)

五、k8s技术圈

1. [下一代镜像构建工具 Buildkit 简介](https://mp.weixin.qq.com/s/Y961wEqbXa9zavski-rWLg)

2. [高级Go研发工程师 - 头条医疗部门](https://mp.weixin.qq.com/s/pzhE3PuK8pOa_N_5yEjrwQ)

六、polarisxu

1. [克制挺难的](https://mp.weixin.qq.com/s/Dfclabvj-sea3dMurKzF5w)

七、腾讯技术工程

1. [​网络 IO 演变发展过程和模型介绍](https://mp.weixin.qq.com/s/EDzFOo3gcivOe_RgipkTkQ)

八、xueyuanjun

1. [Go 函数式编程篇（四）：通过高阶函数实现装饰器模式](https://mp.weixin.qq.com/s/WacP4-wvX1zuocDPBaCx6A)

九、FreeWheel

1. [技术天地 | 中台技术解析之 – FreeWheel核心业务团队的测试实践](https://mp.weixin.qq.com/s/i922PtGNs-qd7Er9ztYyzw)

## GOCN每日新闻--2021-02-24 
1.TiDB 条分缕析 Raft 算法 https://gocn.vip/topics/11698

2.Go 高效截取字符串的一些思考 https://mp.weixin.qq.com/s/WtZ93UrpMiEZDSK80CBrWQ

3.什么是大端序和小端序，为什么要有字节序 https://mp.weixin.qq.com/s/ri2tt4nvEJub-wEsh0WPPA

4.从 go-chi 框架撤回所有主版本聊 Go1.16 的新特性 https://mp.weixin.qq.com/s/mBJ3hQ6oR1V9YtdXpkTnow

5.Go 工程化 依赖注入框架 wire https://lailin.xyz/post/go-training-week4-wire.html

## gopherDaily--2021-02-24
- 1.新提案：Go 1.17在go test框架中原生增加对fuzz test的支持 - https://github.com/golang/go/issues/44551
- 2.在Kubernetes上快速开发Go微服务 - https://blog.getambassador.io/go-kubernetes-rapidly-developing-golang-microservices-bfe36cfb5893
- 3.从C#转到Go进行后端开发 - https://aluma.io/resources/blog/switching-from-c-to-go-for-backend-development
- 4.利用go 1.16 embed特性实现单文件web应用 - https://philidor.dev/blog/go-embed-usecase/
- 5.go-kafka客户端使用入门 -  https://darkodjalevski.me/posts/go-client-for-apache-kafka/
- 6.jackal: 支持xmpp的即时消息server - https://github.com/ortuman/jackal
- 7.Go发布/订阅指南 - https://www.ably.io/blog/pubsub-golang
- 8.你应该为企业级应用选择什么架构 - https://kodytechnolab.com/software-architecture-for-enterprise-applications
- 9.超越数据库：第1部分-内存中数据库索引的工作方式 - https://sopin.dev/2021/01/01/Databases-Beyond-the-data-Part-1/
- 10.热爱在linux写代码的5个理由 - https://opensource.com/article/21/2/linux-programming
- 11.针对开发者和开放源代码作者的免费服务列表 - https://free-for.dev/
- 12.关于消息传递和嵌入式消息传递 - https://ielgohary.github.io/blog-embedded-messaging.html
- 13.Git是我的伙伴: 高效使用git的原则 - https://mikkel.ca/blog/git-is-my-buddy-effective-solo-developer/
- 14.d3.js作者的10年开源感悟 - https://observablehq.com/@mbostock/10-years-of-open-source-visualization
- 15.将源码转换为图片的命令行工具 - https://github.com/matsuyoshi30/germanium

## 码农桃花源--2021-02-24
### 文章分享
1 [复习：Linux内核是如何巧妙的初始化各个模块的](https://mp.weixin.qq.com/s/qdBsv3vK-Suczt7gEmI6Dw)

2 [复习：为什么redis快照使用子进程](https://draveness.me/whys-the-design-redis-bgsave-fork/)

3 [微服务架构之rpc框架](https://mp.weixin.qq.com/s/jUgmW3oflsTwyX-6kNZCfw)

### 面试问题
1 redis使用单线程模型，为什么效率也很高？

2 redis为什么删除缓存而不是更新缓存？

3 如何保证缓存和数据库的双写一致性？

4 redis快照实现的底层原理

### 每日算法
lc375 猜数字II
## go中文网每日资讯--2021-02-23

一、Go语言中文网

1. [Go 高效截取字符串的一些思考](https://mp.weixin.qq.com/s/WtZ93UrpMiEZDSK80CBrWQ)

2. [一文完全掌握 Go math/rand](https://mp.weixin.qq.com/s/vufx-L2CkqXa9RTC45wpCg)

3. [Go 语言实战：命令行程序（1）](https://mp.weixin.qq.com/s/SwDW1ILmsILnC6m9lOEa_A)

二、亚军进化史

1. [Go技术日报(2021-02-22)——Go 工程化(三) 依赖注入框架 wire](https://mp.weixin.qq.com/s/AAHtIn0kBDnbz3BXPGyGNQ)

三、脑子进煎鱼了

1. [灵魂拷问 Go 语言：这个变量到底分配到哪里了？](https://mp.weixin.qq.com/s/mFfza7DayFqsiS93Ep15BA)

四、Go 夜读

1. [【本周四 19 点预告】如何让业务应用享受云原生的红利？](https://mp.weixin.qq.com/s/rPMnzmULr8R2eNT0MwsrGw)

五、多颗糖

1. [【MIT 6.824】学习笔记 1： MapReduce](https://mp.weixin.qq.com/s/I0PBo_O8sl18O5cgMvQPYA)

六、真没什么逻辑

1. [如何保证数据中心服务器的时间一致 · OSDI 2020](https://mp.weixin.qq.com/s/JmAF0ZxZ7c59KDlC3uyHJg)

七、阿里云云栖号

1. [高可用的本质](https://mp.weixin.qq.com/s/jTIk6XjsCEWTIgArJ3IpTg)

八、Go招聘

1. [行业黑马直聘golang开发工程师啦，全额五险一金等你来！](https://mp.weixin.qq.com/s/c6NB3Klw6XPdeUK5VTgsKg)

2. [安全企业竹云科技来寻Gopher了](https://mp.weixin.qq.com/s/_qWxAfI32gsHj30s1uncUA)

九、polarisxu

1. [从 go-chi 框架撤回所有主版本聊 Go1.16 的新特性](https://mp.weixin.qq.com/s/mBJ3hQ6oR1V9YtdXpkTnow)

## GOCN每日新闻--2021-02-23
1. Kubernetes Kubernetes vs Docker:了解 2021 年的容器 https://gocn.vip/topics/11691

2.构建微服务的十大 Golang 框架和库 https://mp.weixin.qq.com/s/tPnb0QrLEIZnLyPcMX4EGw

3.Go 不是一种简单的编程语言 https://www.arp242.net/go-easy.html

4.灵魂拷问 Go 语言：这个变量到底分配到哪里了？ https://mp.weixin.qq.com/s/mFfza7DayFqsiS93Ep15BA

5.使用 Go 将音频文件添加至彩铃 https://learn.vonage.com/blog/2021/01/14/play-an-audio-file-into-a-voice-call-with-go


## gopherDaily--2021-02-23
1.观点：Go并不是一门容易的语言 - https://www.arp242.net/go-easy.html

2.REST API设计的最佳实践 - https://stackoverflow.blog/2020/03/02/best-practices-for-rest-api-design/

3.mubeng: 高性能代理检查器和IP旋转器 - https://github.com/kitabisa/mubeng

4.IPCDump: Guardicore用于Linux IPC检查的新开源工具，基于gobpf - https://www.guardicore.com/labs/ipcdump-guardicores-new-open-source-tool-for-linux-ipc-inspection/

5.Calico项目：将k8s安全作为SaaS - https://thenewstack.io/project-calico-kubernetes-security-as-saas/

6.驯服CORS和单页应用 - https://vernonkeenan.com/index.php/2021/02/22/i-had-a-go-cors-and-single-page-app-ordeal-so-you-dont-have-to/

7.使用mozilla rr工具调试Go测试 - http://choly.ca/post/debugging-go-with-rr/

8.gRPC与Go教程 - https://pmihaylov.com/grpc-with-go-crash-course/

9.深度学习如何选择激活函数 - https://machinelearningmastery.com/choose-an-activation-function-for-deep-learning/

11.费曼物理学讲义 - https://www.feynmanlectures.caltech.edu/I_toc.html
## 码农桃花源--2021-02-23
### 文章分享
1.  [复习 GPM](https://mp.weixin.qq.com/s/JOjUWp15JbEu54VJHY8i_A)

2.  [峰云阅读书单](http://xiaorui.cc/archives/3342)

3.  [grpc](http://xiaorui.cc/archives/7013)

4.  [如何设计一个云原生应用的架构](https://strikefreedom.top/how-to-design-an-architecture-of-cloud-native-application)

5.  [四种部署方式](https://www.yuque.com/wuguoguoya/iq0d3v/yusa4i)

### 面试问题
1. context 如何被取消

2. context 是什么

3. context 有什么作用

4. context.Value 的查找过程是怎样的
### 每日算法
lc44 通配符匹配

## go中文网每日资讯--2021-02-22

一、#公众号：Go语言中文网

1. 韩信大招：一致性哈希 https://mp.weixin.qq.com/s/eAQ1_Lsmd57DJWMFH60cgQ

2. BPF和Go：在Linux中内省的现代方式 https://mp.weixin.qq.com/s/J4b8KXqoxoKU-YfUgYbfCw

3. 手摸手Go 深入剖析sync.Pool https://mp.weixin.qq.com/s/nFaS05cluv0D0JladVYRVA

二、#公众号：亚军进化史

1. Go技术日报(2021-02-21)——利好！极大可能在 go 1.17 中就能尝试泛型 https://mp.weixin.qq.com/s/syoXorFDXIIJTu99znSTsQ

三、#公众号：HHFCodeRv

1. 一文完全掌握 Go math/rand https://mp.weixin.qq.com/s/dbdP_Jz9OHCuLO1ffOmCNg

四、#公众号：MoeLove

1. K8S 生态周报| Helm v3.5 正式发布，带来完备的 OCI 支持 https://mp.weixin.qq.com/s/3SdBM26U13nB3vqsP7omRg

五、#公众号：奇伢云存储

1. Go 并发编程 — 深入浅出 sync.Pool ，围观最全的使用姿势，理解最深刻的原理 https://mp.weixin.qq.com/s/6Nx7IGFU_FbM5AOdUzmvcw

六、#公众号：网管叨bi叨

1. 什么是大端序和小端序，为什么要有字节序 https://mp.weixin.qq.com/s/ri2tt4nvEJub-wEsh0WPPA

七、mohuishou

1. Go工程化(三) 依赖注入框架 wire - Mohuishou https://lailin.xyz/post/go-training-week4-wire.html

## GOCN每日新闻--2021-02-22 
1.一文完全掌握 Go math/rand https://gocn.vip/topics/11689

2.详解 Go 语言调度循环源码实现 [Go 15.7 源码] https://www.luozhiyun.com/archives/448

3.使用适配器模式解耦 Go 应用的功能库 https://www.hildeberto.com/2021/02/adapter-design-pattern-golang.html

4.Go 中的 SSRF 攻防战 https://isites.github.io/timeline/go-ssrf/

5.go-frodokem: Frodokem 算法的 Go 实现 https://github.com/kuking/go-frodokem/


## gopherDaily--2021-02-22 
- 1.Ristretto: 一个高性能、并发的缓存库，注重性能和正确性 - https://github.com/dgraph-io/ristretto
- 2.纯Go实现的编程语言 - https://github.com/odddollar/Container-lang
- 3.FrodoKEM的Go实现：(frodokem是一个实用量子安全密钥封装) -  https://github.com/kuking/go-frodokem/
- 4.一个go实现的虚拟文件系统 - https://alysonn.medium.com/a-virtual-filesystem-in-go-creating-our-foundation-9af62b0e82db
- 5.gohugo v0.81.0发布：原生支持apple m1 - https://gohugo.io/news/0.81.0-relnotes/
- 6.Go实现的语音彩铃 - https://learn.vonage.com/blog/2021/01/14/play-an-audio-file-into-a-voice-call-with-go
- 7.gofp: Javascript的lodash函数库的Go移植 - https://github.com/rbrahul/gofp
- 8.Kubernetes 原生 CI/CD 构建框架 Argo 详解！ - https://mp.weixin.qq.com/s/DErVsooKplJf1zDPvGvkfQ
- 9.区块链详解 - https://mp.weixin.qq.com/s/JxJio0cd_I1Q24KKzR6-PA
- 10.自定义gomock matcher加强go 单元测试 - https://dev.to/techschoolguru/how-to-write-stronger-unit-tests-with-a-custom-go-mock-matcher-55pc


## 码农桃花源--2021-02-20
### 文章分享
1 [微服务系统的服务发现机制](https://segmentfault.com/a/1190000004960668?utm_source=sf-related)

2 [微服务设计学习之服务发现](https://segmentfault.com/a/1190000021132907?utm_source=sf-related)

3 [看图学etcd](https://segmentfault.com/a/1190000020742981?utm_source=sf-related)

4 [复习：go语言之interface](https://draveness.me/golang/docs/part2-foundation/ch04-basic/golang-interface/)

### 面试问题
1 redis 的过期策略都有哪些？内存淘汰机制都有哪些？手写一下LRU代码实现？

2 redis 的并发竞争问题是什么？如何解决这个问题？了解 Redis 事务的 CAS 方案吗？

3 HTTP的keep-alive是干什么的？

4 HTTP2相对于HTTP1.x有什么优势和特点？

5 为什么常说 TCP 有粘包和拆包的问题而不说 UDP ？

6 介绍一下Linux 中进程的几种状态

7 针对网站访问慢，怎么去排查？怎么去解决？

### 每日算法
lc381 设计数据结构：O(1)时间插入、删除、获取随机元素。


## go中文网每日资讯--2021-02-20 

一、Go语言中文网

1. [Go 中可取消的读取操作](https://mp.weixin.qq.com/s/eitsMVVqnd3l2xWyrURoDA)

2. [Go1.17 快报：将移除 GOPATH](https://mp.weixin.qq.com/s/RaYAEISybFvYMj99Y42Cjg)

3. [Go：基于Redis Cluster的分布式锁实现以互斥方式操作共享资源](https://mp.weixin.qq.com/s/BK-XnVB44ftxVKf21AMIvw)

二、亚军进化史

1. [Go技术日报(2021-02-19)——Go1.17 快报：将移除 GOPATH](https://mp.weixin.qq.com/s/d0zKZ597ORCDq27rP_SwSw)

三、TechPaper

1. [一个 bad file descriptor 的问题](https://mp.weixin.qq.com/s/fCb9sNEGt1JLQOXVlXr4Aw)

四、Go招聘

1. [成都同程艺龙来招Gopher啦！！！](https://mp.weixin.qq.com/s/xw2AhvbY15f0qnnL-AsiqA)

五、轩脉刃的刀光剑影

1. [设计一个回调要注意哪些事情](https://mp.weixin.qq.com/s/wERneobN7XuVsgnF72UkxQ)

六、polarisxu

1. [为什么学 Rust 及相关学习资料推荐](https://mp.weixin.qq.com/s/iHlLZwq2K7ChsegOFNCJKw)

七、吴亲强的深夜食堂

1. [可视化演示Go并发](https://mp.weixin.qq.com/s/Ykr11N6A5mRF_KIzvHNSpA)

八、后端早读课

1. [树 Story —— LSM 树](https://mp.weixin.qq.com/s/cWS3234YD0zmjpAXImjOkg)

2. [树 Story —— B 树 / B+ 树](https://mp.weixin.qq.com/s/BLiZ1hhQK-QILdLBw6iNjQ)

九、nanko的快乐小窝

1. [关于Java与Golang的GC](https://mp.weixin.qq.com/s/y0ZZboRVyWL1frVbSjLqdQ)

## gopherDaily--2021-02-20 
- 1.官博：Go 1.16中有关go module的变化 - https://blog.golang.org/go116-module-changes
- 2.Go泛型的开发将直接在master分支上进行 - https://github.com/golang/go/commit/9a99515c8f1febe39151a80b2088d0d6fdc55ca2
- 3.分布式应用程序运行时Dapr发布v1.0版本，生产可用 - https://blog.dapr.io/posts/2021/02/17/announcing-dapr-v1.0/
- 4.Go开发的8个安全方面最佳实践 - https://snyk.io/blog/go-security-cheatsheet-for-go-developers/
- 5.从go panic的输出信息中去除源码路径信息 - https://johnpili.com/remove-source-path-from-gos-panic-stack-trace/
- 6.在Docker Images中嵌入源代码版本信息 - https://www.cncf.io/blog/2021/02/17/embedding-source-code-version-information-in-docker-images/
- 7.基准测试不一定是绝对正确的 - https://rauljordan.com/2021/02/18/when-a-solution-is-right-in-front-of-your-eyes.html
- 8.代码仓库中敏感信息的检测工具 - https://github.com/eth0izzle/shhgit
- 9.Go语言入门 - https://levelup.gitconnected.com/learn-the-fundamentals-of-programming-go-51937b3d3105
- 10.haraqa：一个可伸缩消息队列，用于微服务之间的数据持久性和实时数据流传输 - https://github.com/haraqa/haraqa
- 11.基于属性的Go测试 - https://code.egym.de/property-based-testing-in-golang-d3a860a2965
- 12.CentOS之父Gregory Kurtzer谈他的新linux发行版Rocky Linux - https://thenewstack.io/centos-creator-gregory-kurtzer-discusses-his-new-distro-rocky-linux/
- 13.NASA开源毅力号火星车搭载的直升机飞行器的软件框架 - https://github.com/nasa/fprime

## GOCN每日新闻--2021-02-20 
1.Go 1.16 中 Module 功能新变化 https://gocn.vip/topics/11679

2.Golang 代码测试：一点到面用测试驱动开发 https://segmentfault.com/a/1190000039236569

3.“能力越大，责任越大” – Go 语言之父详解将于 Go 1.18 发布的 Go 泛型 https://tonybai.com/2021/02/18/typing-generic-go-by-griesemer-at-gophercon-2020/

4.基于 Redis Cluster 的分布式锁实现以互斥方式操作共享资源 https://tonybai.com/2021/02/13/operate-with-shared-resources-in-a-mutually-exclusive-way-through-distributed-lock-implemented-by-redis-cluster/

5.以单件方式创建和获取数据库实例 https://tonybai.com/2021/02/09/create-and-get-db-access-instance-through-singleton/

## 码农桃花源--2021-02-20
### 文章推荐
1. [go json实现原理] https://draveness.me/golang/docs/part4-advanced/ch09-stdlib/golang-json/

2. [复习 go hashmap原理] https://draveness.me/golang/docs/part2-foundation/ch03-datastructure/golang-hashmap/

3. [interview questions] https://github.com/arialdomartini/Back-End-Developer-Interview-Questions

4. [那些年一起追过的大佬 大佬文章合集] https://mp.weixin.qq.com/s/x2W8Rf1e-a9dSYE53Lu1DA

5. [复习 饶大的interface十问] https://mp.weixin.qq.com/s/EbxkBokYBajkCR-MazL0ZA

### 面试问题
1. float 类型可以作为 map 的 key 吗

2. map 中的 key 为什么是无序的

3. map 是线程安全的吗

4. map 的删除过程是怎样的

5. map 的底层实现原理是什么

6. map 的扩容过程是怎样的

7. map 的赋值过程是怎样的

8. map 的遍历过程是怎样的

9. 可以对 map 的元素取地址吗

10. 可以边遍历边删除吗

11. 如何实现两种 get 操作

12. 如何比较两个 map 相等

13. channel 发送和接收元素的本质是什么

14. channel 在什么情况下会引起资源泄漏

15. channel 底层的数据结构是什么

16. channel 有哪些应用

17. 什么是 CSP

18. 从 channel 接收数据的过程是怎样的

19. 从一个关闭的 channel 仍然能读出数据吗

20. 关于 channel 的 happened-before 有哪些

21. 关闭一个 channel 的过程是怎样的

22. 向 channel 发送数据的过程是怎样的

23. 如何优雅地关闭 channel

24. 操作 channel 的情况总结


## go中文网每日资讯--2021-02-19 


一、Go语言中文网

1. [Go语言中文网牛年春晚回放来咯！！！](https://mp.weixin.qq.com/s/xxbn0mXyJHIse3AAFnupXA)

2. [Go招聘：加入米哈游，技术宅拯救世界](https://mp.weixin.qq.com/s/gx9ZhmVPdfOqGpPUSWeEJQ)

3. [你真的了解 sync.Mutex吗](https://mp.weixin.qq.com/s/lGRCaR9z4xlpU5f_ezkhzw)

二、MoeLove

1. [从Go的二进制文件中获取其依赖的模块信息](https://mp.weixin.qq.com/s/f2ojUG1bMQo-es6jmuX96w)

三、码农桃花源

1. [那些年我们一起追过的大佬](https://mp.weixin.qq.com/s/x2W8Rf1e-a9dSYE53Lu1DA)

四、脑子进煎鱼了

1. [Go1.16 新特性：Go mod 的后悔药，仅需这一招](https://mp.weixin.qq.com/s/0g89yj9sc1oIz9kS9ZIAEA)

五、奇伢云存储

1. [Go 最新资讯：Go 1.16 正式发布，支持 macOS ARM64 架构](https://mp.weixin.qq.com/s/Ezg6yPuVSdu9j6B7Hs0m2A)

六、多颗糖

1. [条分缕析 Raft 算法(续)：日志压缩和性能优化](https://mp.weixin.qq.com/s/Gck3dIfQ7VH_wd6kyNXarw)

七、polarisxu

1. [Go1.17 快报：将移除 GOPATH](https://mp.weixin.qq.com/s/Lwt5c9Z5TD7TAg7-Yt6wAA)

## GOCN每日新闻--2021-02-19
1. Go1.16 新功能：Go Module 支持版本撤回 https://gocn.vip/topics/11667
2. 从 Go 的二进制文件中获取其依赖的模块信息 https://juejin.cn/post/6930762439201914893
3. 在 2 分钟内使用 Go 复制 100 万个 redis 键 https://medium.com/amboss/copy-redis-keys-in-minutes-with-golang-3c06f3cd3af8
4. 两个简单的步骤帮 web 服务创建 Swagger 文档 https://levelup.gitconnected.com/creating-a-swagger-documented-go-web-server-in-two-easy-steps-59f1118bd247
5. 使用 go kit 创建微服务 https://dev.to/eminetto/microservices-in-go-using-the-go-kit-jjf


## gopherDaily--2021-02-19
- 1.使用Go六年来犯过的那些错误 - https://henvic.dev/posts/my-go-mistakes/
- 2.如何使用COBRA来实现简易的Go CLI命令行选项 - https://ethicalhackingguru.com/how-i-use-cobra-for-easy-golang-cli-flags/
- 3.在Go的世界里，即使不用的东西，也要付出代价 - https://notes.volution.ro/v1/2021/02/notes/378ae6f6/
- 4.在Go中阻止SQL注入以及其他安全问题 - https://blog.sqreen.com/preventing-sql-injections-in-go-and-other-vulnerabilities/
- 5.如何使用Go连接到以太坊网络 - https://www.quiknode.io/guides/web3-sdks/how-to-connect-to-ethereum-network-using-go
- 6.LakeFS的存储设计 - https://lakefs.io/concrete-graveler-committing-data-to-pebbledb-sstables/
- 7.Go机器学习框架的性能基准测试对比 - https://github.com/nikolaydubina/go-ml-benchmarks
- 8.如何在Go中使用MQTT - https://levelup.gitconnected.com/how-to-use-mqtt-with-go-89c617915774
- 9.Gitlab-Runner的工作原理 - https://medium.com/scum-gazeta/explaining-gitlab-runner-research-12cbfe9938cd
- 10.io_uring与epoll性能对比 - https://github.com/axboe/liburing/issues/189
- 11.在Go中何时以及如何使用iota - https://www.gopherguides.com/articles/how-to-use-iota-in-golang
- 12.Tracee：Linux的运行时安全和取证工具。它使用Linux eBPF技术在运行时跟踪系统和应用程序，并分析收集的事件以检测可疑的行为模式 - https://github.com/aquasecurity/tracee
- 13.Go播客：阅读文档的艺术 - https://changelog.com/gotime/167


## 码农桃花源--2021-02-19
### 文章分享
1.  [interview questions](https://github.com/arialdomartini/Back-End-Developer-Interview-Questions)

2.  [那些年一起追过的大佬 大佬文章合集](https://mp.weixin.qq.com/s/x2W8Rf1e-a9dSYE53Lu1DA)

3.  [go mod](https://mp.weixin.qq.com/s/0g89yj9sc1oIz9kS9ZIAEA)

4.  [复习 饶大的interface十问](https://mp.weixin.qq.com/s/EbxkBokYBajkCR-MazL0ZA)

5.  [supervisor](https://www.yuque.com/wegoer/set/supervisor)

### 面试问题
1. channel 发送和接收元素的本质是什么
2. channel 在什么情况下会引起资源泄漏
3. channel 底层的数据结构是什么
4. channel 有哪些应用
5. 什么是 CSP
6. 从 channel 接收数据的过程是怎样的
7. 从一个关闭的 channel 仍然能读出数据吗
8. 关于 channel 的 happened-before 有哪些
9. 关闭一个 channel 的过程是怎样的
10. 向 channel 发送数据的过程是怎样的
11. 如何优雅地关闭 channel
12. 操作 channel 的情况总结
### 每日算法
lc891 子序列宽度之和

## go中文网每日资讯--2021-02-18 


一、#公众号：Go语言中文网

1.[Go：gops 如何与 runtime 交互？](https://mp.weixin.qq.com/s/xyG7KYb72qIbmdEZep35Sg)

2.[Go：以单件方式创建和获取数据库实例](https://mp.weixin.qq.com/s/iwCfAHBWXJwVq6uZrEkv1g)

3.[肝了一上午的Golang之Plan9入门](https://mp.weixin.qq.com/s/9bn0foYfqJPtNdRI0NIleQ)

二、#公众号：微服务实践

1.[Go 大数据生态迎来重要产品 CDS](https://mp.weixin.qq.com/s/3sjY-rjdFgsKscD6i7QOIA)

三、#公众号：薯条的自我修养

1.[如何提高代码的可读性 学习笔记](https://mp.weixin.qq.com/s/LW0osX6gvtKHf5Vqnv9u6w)

四、#公众号：远赴星辰

1.[Redis 多线程网络模型全面揭秘](https://mp.weixin.qq.com/s/pm2NsPzTO4lJQfGUC4-sJQ)

五、#公众号：k8s技术圈

1.[Go 1.16 使用 Embed 嵌入静态资源-视频版](https://mp.weixin.qq.com/s/c86IHWh5iJECjl1DZ9vLsw)

六、#公众号：Golang梦工厂

1.[源码剖析sync.cond(条件变量的实现机制）](https://mp.weixin.qq.com/s/szSxatDakPQMUA8Vm9u3qQ)

## GOCN每日新闻--2021-02-18 
1.微服务架构中的延迟任务 https://itnext.io/deferred-tasks-in-a-microservice-architecture-8e7273089ee7

2.如何在 Go 中构建一个线程安全的队列 https://dev.to/har130798/how-to-build-a-thread-safe-queue-in-go-lbh 
3.手撸 Go 基本数据结构与算法哈希表 https://segmentfault.com/a/1190000039219752

4.如何在 Go 中使用 MQTT https://levelup.gitconnected.com/how-to-use-mqtt-with-go-89c617915774

5.一个高效、正确的图像抖动处理类库 https://github.com/makeworld-the-better-one/dither

## gopherDaily--2021-02-18
- 1.Go 1.16版本正式发布! - https://blog.golang.org/go1.16
- 2.油管视频：五分钟详解Go 1.16 embed包 - https://www.youtube.com/watch?v=mBNIZHHi5Rg&feature=youtu.be
- 3.经典旧文：Go内存压舱石：我是如何学会不再担心和爱上这堆东西的？ - https://blog.twitch.tv/en/2019/04/10/go-memory-ballast-how-i-learnt-to-stop-worrying-and-love-the-heap-26c2462549a2/
- 4.infracost: Terraform项目的云成本估算工具 - https://github.com/infracost/infracost
- 5.使用Ego轻松构建机密Go应用(基于Intel SGX: 安全扩展指令集) - https://github.com/edgelesssys/ego
- 6.为什么Go编程语言现在会流行？- https://techaffinity.com/blog/why-use-go-for-you-project/
- 7.最佳Go书籍列表 - https://topminisite.com/blog/best-golang-book-to-learn
- 8.微服务架构中的延迟任务(deferred task) - https://itnext.io/deferred-tasks-in-a-microservice-architecture-8e7273089ee7
- 9.通过多容器pod(边车模式)扩展k8s上的应用 - https://learnk8s.io/sidecar-containers-patterns
- 10.git submodules操作详解 - https://chrisjean.com/git-submodules-adding-using-removing-and-updating/
- 11.将代码转换为可定制的漂亮图片 - https://ray.so/
- 12.WatchDog：揭露开展了两年的加密劫持活动 - https://unit42.paloaltonetworks.com/watchdog-cryptojacking/
- 13.使用TinyGo将2004年的孩之宝Millennium Falcon套装转换为蓝牙播放器/音频可视化器 - https://www.hackster.io/alankrantas/the-falcon-audio-visualizer-a-tinygo-project-260360
- 14.orion: 下一代自动测试工具 - https://ivan-corrales-solera.medium.com/orion-a-next-generation-automation-testing-tool-4ea53eeb2517
- 15.在Go应用程序中使用“103提早提示”状态代码 - https://dunglas.fr/2021/02/using-the-103-early-hints-status-code-in-go-applications/


## go中文网每日资讯--2021-02-17

一、#公众号：Go语言中文网

1.[来了来了！Go1.16 重磅发布](https://mp.weixin.qq.com/s/eqquyrWN0CqEzmwXquRlAA)

2.[Go官博：正式提案将泛型加入Go](https://mp.weixin.qq.com/s/TXUMh5nfCNLaTRIifnMLDA)

二、#公众号：亚军进化史

1.[Go技术日报(2021-02-16)——解密 defer 原理，究竟背着程序猿做了多少事情？](https://mp.weixin.qq.com/s/LURYMXsBNQa6Ccd7MNucIw)

三、#公众号：Go招聘

1.[Go语言中文网牛年春晚回放来咯！！！](https://mp.weixin.qq.com/s/IWsv8__Xj1aj-XrzLuTrBg)

四、#公众号：脑子进煎鱼了

1.[速报：Go1.16 正式发布，新版本特性详解合集](https://mp.weixin.qq.com/s/DwmYIhuy45u7pmo8PwIgoQ)

五、#公众号：GoOfficialBlog

1.[Go 1.16 is released, Apple silicon M1 可以放心买啦](https://mp.weixin.qq.com/s/-dfC4YuIHAoYWxgKErMyqQ)

六、#公众号：后端早读课

1.[树 Story —— 多路查找树](https://mp.weixin.qq.com/s/QJ9l233XMQsiGS3ySRIcxg)

七、#公众号：k8s技术圈

1.[Kubernetes 应用性能分析工具 - Kubectl Flame](https://mp.weixin.qq.com/s/N26J78uk_cjxyqqqsNignA)


## GOCN每日新闻--2021-02-17
1.Go 1.16 正式发布 https://blog.golang.org/go1.16

2.以层的方式而不是组的方式进行包管理 https://mp.weixin.qq.com/s/l0fvcMMpBmMo0WLqHhwmjQ

3.使用 go-kit 构建微服务 https://eltonminetto.dev/en/post/2021-02-06-microservices-gokit/

4.signoz: 开源 Datadog 替代品 https://github.com/SigNoz/signoz

5.GopherCon TW 2020 https://space.bilibili.com/756684/channel/detail?cid=169470



## gopherDaily--2021-02-17 

- 1.Go可执行文件大小比较：从Go 1.7.6到Go 1.16rc1 - https://itnext.io/size-comparison-of-go-executables-9b4ae2aaebb5
- 2.在Go 1.16可执行文件中嵌入一个javascript web站点 - https://blog.lawrencejones.dev/golang-embed/
- 3.使用go kit实现Go微服务 - https://eltonminetto.dev/en/post/2021-02-06-microservices-gokit/
- 4.在Go中实现和使用文件锁 - https://magdy.dev/blog/2021/02/07/file-locking-in-go-part-i/
- 5.使用Go context和WaitGroup优雅处理goroutine - https://justbartek.ca/p/golang-context-wg-go-routines/
- 6.油管视频：Service Mesh（和Istio）在多kubernetes集群网络中的应用方法 - https://www.youtube.com/watch?v=9kl7CR8MH-w
- 7.Coil v2：提供原生网络性能的k8s cni网络插件 - https://blog.kintone.io/entry/coilv2
- 8.kubernetes无服务框架大比较 - https://www.vshn.ch/en/blog/a-very-quick-comparison-of-kubernetes-serverless-frameworks
- 9.OpenTelemetry规范发布1.0 - https://medium.com/opentelemetry/opentelemetry-specification-v1-0-0-tracing-edition-72dd08936978
- 10.esme: 通过json配置生成一个模拟rest服务 - https://github.com/stkr89/esme
- 11.以太坊: 为什么无状态如此重要 - https://dankradfeist.de/ethereum/2021/02/14/why-stateless.html
- 12.开源技能比专有技能更有价值 - https://searchapparchitecture.techtarget.com/news/252496117/Survey-Open-source-skills-more-valued-than-proprietary-ones
- 13.解析微服务 - https://thenewstack.io/primer-microservices-explained/



## go中文网每日资讯--2021-02-16 


一、#公众号：Go语言中文网

1.[Go 语言标准库中 atomic.Value 的前世今生](https://mp.weixin.qq.com/s/9aNfjX2UMQKLLgSW037_uQ)

2.[解密 defer 原理，究竟背着程序猿做了多少事情？](https://mp.weixin.qq.com/s/3-32J0bs2_PbQ74ywMymnw)

3.[搭一个K8s集群](https://mp.weixin.qq.com/s/-mZDL5CRe6Ub7HDuPn7eEw)

二、#公众号：亚军进化史

1.[Go技术日报(2021-02-15)——Rust 的第一印象](https://mp.weixin.qq.com/s/Tk93E-bkOx8ByhMjxWk1bg)

三、#公众号：Go招聘

1.[golang 面试题：能说说 uintptr 和 unsafe.Pointer的区别吗？](https://mp.weixin.qq.com/s/zY-sqds-DhbdqzKq4pAupg)

四、#公众号：分布式实验室

1.[Kubernetes CRD开发实践](https://mp.weixin.qq.com/s/AdSaTEt_l8eePlH0q_jNZg)

五、#公众号：捡田螺的小男孩

1.[MySQL索引底层：B+树详解](https://mp.weixin.qq.com/s/t7l76dVQdBecc-y4EdNTLg)


## GOCN每日新闻--2021-02-16 
1.在浏览器中部署 Go HTTP 服务器 https://github.com/nlepage/go-wasm-http-server

2.在 Go 中开发可用于生产的 REST API https://tutorialedge.net/courses/go-rest-api-course/

3.内联函数和编译器对 Go 代码的优化 https://mp.weixin.qq.com/s/Or4FmVAf9nvMQzPct87Ecw

4.使用 Go 语言编写的使用 K6 工具进行 Web 应用程序负载测试的简便方法 https://webdevstation.com/posts/an-easy-way-to-loadtest-your-web-apps/

5.pdfcpu：Go PDF 处理器 https://github.com/pdfcpu/pdfcpu

## gopherDaily--2021-02-16
- 1.Go项目结构布局详解 - https://manfred.life/golang-project-layout
- 2.Kubernetes的Pod如何获得一个IP地址 - https://ronaknathani.com/blog/2020/08/how-a-kubernetes-pod-gets-an-ip-address/
- 3.油管视频：以图形化方式理解Kubernetes - https://www.youtube.com/watch?v=9dyiSiyET3I&feature=youtu.be
- 4.终端应用的自动暗模式 - https://arslan.io/2021/02/15/automatic-dark-mode-for-terminal-applications/
- 5.油管视频：Go语法教程 by Ardan Labs - https://www.youtube.com/playlist?list=PLADD_vxzPcZATO4tDU_nHApxTEJyxskiS
- 6.基于redis构建无服务go api - https://medium.com/upstash/serverless-golang-api-with-redis-9e7af456dc82
- 7.mdconv: markdown格式的命令行转换工具，支持将md格式转换为pdf或html - https://github.com/Palexer/mdconv
- 8.signoz: 开源的可观察性平台 - https://github.com/SigNoz/signoz
- 9.用Mocks解释Go的接口 - https://bencane.com/2021/02/15/golangs-interfaces-explained-with-mocks/
- 10.使用tinygo编译目标为Gameboy Advance ROM的应用 - https://remyhax.xyz/posts/gba-blog/

## go中文网每日资讯--2021-02-15 


一、#公众号：Go语言中文网

1.[我与sync.Once的爱恨纠缠](https://mp.weixin.qq.com/s/7IrUm-jxIlgmOLe9Tao4DA)

2.[深入剖析 defer 原理篇 —— 函数调用的原理？](https://mp.weixin.qq.com/s/Tl67RsMVkaRIbmKCl0z-Ow)

3.[K8s中Pod的服务发现](https://mp.weixin.qq.com/s/tjKSq79nrzOt9mLX24dblQ)

二、#公众号：亚军进化史

1.[Go技术日报(2021-02-14)——一个程序员是怎么获得第二收入的？ - Go语言中文网 - Golang中文社区](https://studygolang.com/topics/13132)

三、#公众号：polarisxu

1.[Rust 的第一印象](https://polarisxu.studygolang.com/posts/rust/rust-first-impression/)

## GOCN每日新闻--2021-02-15 
1.Go 结构体内存优化指南 https://itnext.io/structure-size-optimization-in-golang-alignment-padding-more-effective-memory-layout-linters-fffdcba27c61

2.Go 1.16 中的 module retract 特性 https://golangtutorial.dev/tips/retract-go-module-versions/

3.用 Go 带你了解缓冲池的工作原理 https://brunocalza.me/how-buffer-pool-works-an-implementation-in-go/

4.BoltDB 作者讲述他为何要开发 Litestream https://litestream.io/blog/why-i-built-litestream/

5.Go 官方最新的依赖管理指南 https://golang.org/doc/modules/managing-dependencies
 
## gopherDaily--2021-02-15 
- 1.深入理解Go测试覆盖率 - https://eleni.blog/2021/01/24/deep-diving-in-the-go-coverage-profile/
- 2.深入了解Go的基准测试 - https://medium.com/better-programming/we-measure-the-power-of-cars-computers-and-cellphones-but-what-about-code-91ed5583f298
- 3.Go微服务项目的结构布局 - https://gochronicles.com/project-structure/
- 4.在controller-runtime和client-go中进行速率限制 - https://danielmangum.com/posts/controller-runtime-client-go-rate-limiting/
- 5.对gorm2的opentracing支持 - https://github.com/go-gorm/opentracing
- 6.使用Go开发azure函数(part1) - https://www.hildeberto.com/2021/01/azure-function-golang.html
- 7.使用Goroutine并行搜索价格 - https://www.hildeberto.com/2021/02/golang-sync-goroutine.html
- 8.Terratest：一个可以轻松地为基础结构代码编写自动化测试的Go库 - https://github.com/gruntwork-io/terratest
- 9.在Windows中使用Go语言基于Ebiten库创建绘画游戏 - https://shores.dev/paint-game-in-golang/
- 10.作为软件工程师必须要知道的有关kafka的那些事儿 - https://levelup.gitconnected.com/kafka-for-engineers-975feaea6067
- 11.iptables：Kubernetes服务如何将流量定向到Pod - https://dustinspecker.com/posts/iptables-how-kubernetes-services-direct-traffic-to-pods/
- 12.Julia 1.6: 自Julia 1.0起都发生了什么变化？ - https://www.oxinabox.net/2021/02/13/Julia-1.6-what-has-changed-since-1.0.html
- 13.图解函数
