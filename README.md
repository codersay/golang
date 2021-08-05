# go语言体系课

全栈编程原创的go语言体系课，课程分四个阶段：《第一阶段go语言基础语法篇》，从go语言基础语法篇讲起，go语言环境集成，常用开发工具集成，常用数据类型讲解，流程控制，函数，结构体，方法，包，面向对象（封装，继承，多态，接口）。《第二阶段go语言进阶篇》，go语言web编程相关的知识，包括http协议，web请求与响应解析，数据库操作，模板引擎，随着web编程知识的学习会进行两个项目的实战，主要包括微商城后台管理系统与微商城后端接口.《第三阶段go语言高级篇》，go语言的并发编程，众所周知，go语言高效的并发模式是其最核心的能力，也是其与现代多核cpu完美结合的最佳组合。实战模拟机器人的并发请求与限流处理。海量交易日志的处理与订单交易相关，围绕着电商系统的消息推送，包括小程序支付异步通知完善与权益处理，支付成功之后的消息提醒，站内消息通知等。《第四阶段go语言微服务篇》，protobuf数据格式讲解、grpc讲解、grpc+protobuf实现微服务实例、go-micro从零打造微服务、elasticsearch技术栈,elasticsearch微服务化实战微商城搜索功能。

> ## `阶段一：基础语法篇`
> `本阶段内容：从零开始学习go语言体系课程，go语言环境集成，常用开发工具集成，go语言基础语法部分的数据类型讲解（包括变量，常量，数值类型，字符，字符串，浮点类型，布尔，指针，数组，切片，map），流程控制，函数，结构体，方法，go语言包与第三方扩展库，面向对象（封装，继承，多态，接口）。`

![](https://luboke.com/goserials/luboke.com.goserials.18.png)
### 第1章：go语言总述
 - 1.1 [go语言总述](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-gai-shu/) 

### 第2章：go语言数据类型与流程控制
- 2.1 [go数据类型概述与变量](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-shu-ju-lei-xing-gai-shu-yu-bian-liang/)
- 2.2 [go数据类型常量](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-chang-liang/)
- 2.3 [go数据类型数值类型](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-shu-zhi-lei-xing/)
- 2.4 [go数据类型浮点型、虚数](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-fu-dian-lei-xing/)
- 2.5 [go数据类型字符](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-zi-fu/)
- 2.6 [go数据类型字符串](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-zi-fu-chuan/)
- 2.7 [go数据类型布尔](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-bu-er-lei-xing/)
- 2.8 [go数据类型指针](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-zhi-zhen/)
- 2.9 [go数据类型数组](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-shu-zu/)
- 2.10 [go数据类型切片](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-qie-pian/)
- 2.11 [go数据类型map](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-map/)
- 2.12 [go语言流程控制](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-liu-cheng-kong-zhi/) 

### 第3章：go语言函数、结构体、方法
- 3.1 [go语言函数](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-han-shu/) 
- 3.2 [go语言结构体](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-jie-gou-ti/)  
- 3.3 [go语言方法](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-fang-fa/)

### 第4章：go面向对象
- 4.1 [go语言面向对象概述](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-mian-xiang-dui-xiang-gai-shu/)
- 4.2 [go语言面向对象封装](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-mian-xiang-dui-xiang-feng-zhuang/)
- 4.3 [go语言面向对象继承](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-mian-xiang-dui-xiang-ji-cheng/)  
- 4.4 [go语言面向对象多态](https://luboke.com/go-yu-yan-ti-xi-ke/goserials/go-yu-yan-mian-xiang-dui-xiang-duo-tai/)  

> ## `阶段二：进阶篇` 
> `本阶段内容：go语言进阶篇，主要讲解:go语言web编程相关的知识，包括http协议，web请求与响应解析，数据库操作，模板引擎，承受着web编程知识的学习会进行两个项目的实战，主要包括微商城后台管理系统与微商城后端接口。`  
 

![go语言体系课第二阶段之web编程](https://luboke.com/goserials/luboke.com.goserials.24.png)
 
![go语言体系课第二阶段之微商城核心库设计](https://luboke.com/goserials/luboke.com.goserials.21.png)
 
![go语言体系课第二阶段之微商城后台管理系统](https://luboke.com/goserials/luboke.com.goserials.22.png)

 
![go语言体系课第二阶段之web框架](https://luboke.com/goserials/luboke.com.goserials.25.png)

 
![go语言体系课第二阶段之微商城小程序后端接口](https://luboke.com/goserials/luboke.com.goserials.23.png)

![go语言体系课第二阶段之基于beegoweb框架的微商城小程序接口](https://luboke.com/goserials/luboke.com.goserials.20.png)


> ## `阶段二课程电子书直达`

*   [go语言web编程](javascript:void(0);)
    *   [1.思维导图总览](https://luboke.com/go/go2.0.html "go语言体系课第二阶段思维导图总览")
    *   [2.go语言web编程思维导图](https://luboke.com/go/go2.1.html "go语言web编程思维导图")
    *   [3.web概述与版本](https://luboke.com/go/go2.2.html "web概述与版本")
    *   [4.web网页访问流程与DNS解析](https://luboke.com/go/go2.3.html "web网页访问流程与DNS解析")
    *   [5.HTTP协议](https://luboke.com/go/go2.4.html "HTTP协议")
    *   [6.快速体验Go启动一个web服务器](https://luboke.com/go/go2.5.html "快速体验Go启动一个web服务器")
    *   [7.Go语言中Web的工作原理](https://luboke.com/go/go2.6.html "Go语言中Web的工作原理")
    *   [8.Go语言net/http包详解](https://luboke.com/go/go2.7.html "Go语言net/http包详解")
    *   [9.web请求与响应解析](https://luboke.com/go/go2.8.html "web请求与响应解析")
    *   [10.go语言中操作数据库](https://luboke.com/go/go2.9.html "go语言中操作数据库")
    *   [11.go语言模板引擎](https://luboke.com/go/go2.10.html "go语言模板引擎")
*   [实战：微商城后台管理系统](javascript:void(0);)
    *   [1.微商城数据库分析与构建](https://luboke.com/go/go2.11.html "微商城数据库分析与构建")
    *   [2.手把手构建一套web框架](https://luboke.com/go/go2.12.html "手把手构建一套web框架")
    *   [3.微商城后台管理系统](https://luboke.com/go/go2.13.html "微商城后台管理系统")
*   [实战：微商城后端接口](javascript:void(0);)
    *   [1.beego框架与常用操作](https://luboke.com/go/go2.14.html "beego框架与常用操作")
    *   [2.微商城后端接口](https://luboke.com/go/go2.15.html "微商城后端接口")

> ## `阶段三：高级篇`   
> `本阶段内容：go语言高级篇，主要讲解：go语言的并发编程，众所周知，go语言高效的并发模式是其最核心的能力，也是其与现代多核cpu完美结合的最佳组合。那围绕着并发编程，我们将进行并发编程相关功能实战，包括模拟机器人的并发请求与限流处理。一般涉及到并发编程的应用场景，多数与大型项目，海量用户相关，一般大型项目都会涉及到海量的日志，特别是围绕着我们微商城系统相关的海量交易日志的处理与订单交易相关，这也是我们需要详细讨论的内容。那围绕着电商系统又不得不提到的是消息推送，包括小程序支付异步通知完善与权益处理，支付成功之后的消息提醒，站内消息通知等。`

 
![go语言体系课第三阶段之go语言高并发处理](https://luboke.com/goserials/luboke.com.goserials.26.png)
![go语言体系课第三阶段之大文件与交易日志](https://luboke.com/goserials/luboke.com.goserials.27.png)
![go语言体系课第三阶段之消息推送](https://luboke.com/goserials/luboke.com.goserials.28.png) 

> ## `阶段三电子书直达`

*   [go语言高并发处理](javascript:void(0);)
    *   [1.思维导图总览](https://luboke.com/go/go3.0.html "go语言体系课第二阶段思维导图总览")
    *   [2.线程、进程、并发、并行。。。](https://luboke.com/go/go3.1.html "线程与进程、并发与并行、分时系统与上下文切换")
    *   [3.用户空间与内核空间、中断](https://luboke.com/go/go3.2.html "用户空间与内核空间、中断")
    *   [4.协程运行原理、waitgroup。。。](https://luboke.com/go/go3.3.html "数据访问概述、协程运行原理分析、协程与waitgroup")
    *   [5.unbuffered、buffered channel](https://luboke.com/go/go3.4.html "channel概述、unbuffered channel、buffered channel")
    *   [6.channel中的死锁及解决。。。](https://luboke.com/go/go3.5.html "channel中的死锁及解决办法、buffered channel 实现fibonacci、for ...range channel")
    *   [7.单向channel、异步队列。。。](https://luboke.com/go/go3.6.html "channel方向、buffered channel异步队列 模拟并发请求")
    *   [8.select多路监听、nil channel](https://luboke.com/go/go3.7.html "select多路监听、nil channel、channel的channel")
    *   [9.限流处理](https://luboke.com/go/go3.8.html "限流处理")
*   [go语言海量大文件处理](javascript:void(0);)
    *   [1.系统调用、文件读取方式](https://luboke.com/go/go3.9.html "系统调用、文件读取方式")
    *   [2.fmt包的Scan()、Sscan()、Fscan()](https://luboke.com/go/go3.10.html "fmt包的Scan()、Sscan()、Fscan()")
    *   [3.文件基本操作](https://luboke.com/go/go3.11.html "文件基本操作")
    *   [4.json入门](https://luboke.com/go/go3.12.html "json入门")
    *   [5.json进阶](https://luboke.com/go/go3.13.html "json进阶")
    *   [6.海量大文件切割成小文件](https://luboke.com/go/go3.14.html "海量大文件切割成小文件")
    *   [7.grep结合awk实现日志统计](https://luboke.com/go/go3.15.html "grep结合awk实现日志统计")
    *   [8.拆分小文件处理之后再合并](https://luboke.com/go/go3.16.html "拆分小文件处理之后再合并")
    *   [9.nginx日志切割](https://luboke.com/go/go3.17.html "shell脚本实现nginx日志按照不同的时间进行切割")
    *   [10.os.exec.command系统命令](https://luboke.com/go/go3.18.html "go语言os.exec.command执行系统命令操作日志")
    *   [11.交易日志](https://luboke.com/go/go3.19.html "交易日志")
*   [go语言消息推送](javascript:void(0);)
    *   [1.消息推送概述](https://luboke.com/go/go3.20.html "消息推送概述")
    *   [2.千万级系统消息推送技术瓶颈](https://luboke.com/go/go3.21.html "千万级系统消息推送技术瓶颈")
    *   [3.websocket通信](https://luboke.com/go/go3.22.html "websocket通信")
    *   [4.微信小程序websocket](https://luboke.com/go/go3.23.html "微信小程序websocket")
    *   [5.项目实战:微商城支付异步通知完善与权益处理](https://luboke.com/go/go3.24.html "项目实战:微商城小程序支付异步通知完善与权益处理")
    *   [6.项目实战:微商城消息推送](https://luboke.com/go/go3.25.html "项目实战:微商城小程序消息推送")
  
> ## `阶段四微服务篇(电子书待添加)`
> `本阶段内容：
go语言微服务篇，现代编程特别是大型项目的编程，基本都在向微服务靠拢，这也是项目发展到一定阶段的必然趋势，我们在微服务篇主要讲解：微服务相关的知识，包括微服务相关的protobuf数据格式讲解、grpc讲解、grpc+protobuf实现微服务实例、go-micro从零打造微服务、elasticsearch技术栈,包括elasticsearch部署，常用分词组件详解，elasticsearch结合Postman操作curd,go语言操作elasticsearch,elasticsearch微服务化实战微商城搜索功能。`

![go语言体系课第四阶段微服务篇](https://luboke.com/goserials/luboke.com.goserials.29.png) 
