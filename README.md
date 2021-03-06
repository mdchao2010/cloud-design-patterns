# 介绍

随着技术的快速发展，应用的架构逐渐的从单体、分层、SOA逐渐向微服务的方向演进，而基础设施也逐渐从大型机，自建机房，到托管在云平台的各种服务上。所有这一切都是为了让应用（web/mobile）更快、更安全的上线，同时让应用从架构角度和基础设施的角度，拥有高扩展性、伸缩性和自恢复性。

微服务让应用从架构的角度拥有扩展性，更适于运行在云平台提供的VM或者容器上，而云平台服务提供的可编程接口让基础设施的自动化变的异常容易，也让DevOps的落地更加轻松。企业上云已经成为一种不可逆转的趋势。

然而，因为大量的存量应用系统，企业应用架构不加修改直接移植到云上的可能性比较低，虽然我们可以采用微服务的拆分策略（功能、数据、DDD的原则等）来将拆分应用，使其更适于部署在云上。但是在实际的实施过程中，还是会面临很多问题。

Azure云计算团队从可用性、数据管理、设计与实现、消息、管理和监控、性能和可扩展性、弹性、安全等角度总结的[云设计模式](https://docs.microsoft.com/en-us/azure/architecture/patterns/)，提供了企业应用上云的实用模式以及案例，具有一定的参考价值。虽然文章中的案例都是基于Azure的服务，但是你完全可以用其它的云服务提供商，如AWS，GCP，华为云等，的服务，应用相同的模式，让上云的过程变的更加顺畅。

恰好我和同事目前研究的方向也是CloudNative，所以我们挤出周末的时间，把这32个云设计模式翻译完成。水平和时间有限，只是尽力而为，如果在阅读的过程中发现什么问题，敬请原谅之余，烦劳在github中创建对应的issue或者发起PR，感激不尽。

> 注: 文章翻译过程中，发现已经有人翻译了一部分云设计模式的内容，但是只有部分模式，而且是3年前的内容，可读性也一般，所以坚持翻译完了。

## 反馈和贡献

请在github创建相应的[issue](https://github.com/iambowen/cloud-design-patterns/issues)来反馈问题

## 贡献者

* [iambowen@github](https://github.com/iambowen/), [boweniam@twitter](https://twitter.com/boweniam)
* [@tongzh](https://github.com/tongzh)
