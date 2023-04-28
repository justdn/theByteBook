# 消息中间件

微服务、大数据、异步化与事件总线架构设计中，有几个问题无法避免：高并发流量场景下工程复杂度以及服务之间的耦合问题。为了提高系统可用性，就需要引入`消息中间件`通过可靠的异步调用来降低系统的耦合度，引入消息中间件也可以让系统承接大数据量的并发且保持系统稳定性，此外，消息中间件也可以解决系统之间数据的最终一致性问题。

作为互联网架构的基石之一，消息中间件通常作为服务对接之间的桥梁，一旦出现问题，很容易造成严重故障。这就对中间件的要求除了性能之外，还要有高可用、低延迟、支持顺序、容错、事务等能力。

在本章内，笔者将向您概述消息中间件方案的选型，以及具体的RocketMQ方案相关的高可用、容灾等实践话题。

