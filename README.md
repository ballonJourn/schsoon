skywalking_1.0 是一个分布式系统的应用程序性能监视工具，专为微服务、云原生架构和基于容器的架构而设计1。它提供了分布式追踪、服务网格遥测分析、度量聚合和可视化一体化解决方案1。


skywalking-alarm：这个目录是 SkyWalking 的告警模块，负责根据配置的规则，对监控数据进行分析和判断，如果满足告警条件，就会发送告警通知到指定的渠道，比如邮件、Slack、Webhook 等2。
skywalking-api：这个目录是 SkyWalking 的 API 模块，提供了一些公共的接口和类，供其他模块使用，比如 TracingContext、Span 等3。
skywalking-protocol：这个目录是 SkyWalking 的协议模块，定义了 SkyWalking 和 Agent 之间的通信协议，包括数据格式、序列化方式、传输方式等4。
skywalking-sdk-plugin：这个目录是 SkyWalking 的 SDK 插件模块，包含了多种语言的 Agent 插件，用于对不同的框架和库进行自动埋点和监控，比如 Java、Python、Node.js、Go 等5。
skywalking-server：这个目录是 SkyWalking 的服务器模块，包括 OAP Server 和 UI Server 两部分。OAP Server 负责接收 Agent 发送的监控数据，进行分析和存储，并提供查询接口。UI Server 负责提供 Web 界面，展示监控数据和可视化效果6。
skywalking-webui：这个目录是 SkyWalking 的 Web UI 模块，是一个基于 React 的前端项目，用于构建 SkyWalking 的 Web 界面7。

该项目的目标是: 以巨人为基础，造出一个能自动化收集api的监控