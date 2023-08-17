Kafka核心源码解读 / 从底层到实战，深度解析源码
===========================

胡夕 **Apache Kafka Committer，老虎证券技术总监**
--------------------------------------

![Kafka核心源码解读](https://www.geekgay.com/storage/geek/geek_1a4faf20a5482b4c44a2aeb3158b4a11.jpg)  
  
👉👉[**订阅返现**](https://time.geekbang.org/column/intro/100050101?code=xpQ7i6R%2Ff0ptTHL-Hb5bjodbR8zgxSBfheAi2sHXLlU%3D "Kafka核心源码解读")  
  
课程目录
----

  
  
- 开篇词 | 阅读源码，逐渐成了职业进阶道路上的“必选项”
- 导读 | 构建Kafka工程和源码阅读环境、Scala语言热身
- 重磅加餐 | 带你快速入门Scala语言
- 01 | 日志段：保存消息文件的对象是怎么实现的？
- 02 | 日志（上）：日志究竟是如何加载日志段的？
- 03 | 日志（下）：彻底搞懂Log对象的常见操作
- 04 | 索引（上）：改进的二分查找算法在Kafka索引的应用
- 05 | 索引（下）：位移索引和时间戳索引的区别是什么？
- 06 | 请求通道：如何实现Kafka请求队列？
- 07 | SocketServer（上）：Kafka到底是怎么应用NIO实现网络通信的？
- 08 | SocketServer（中）：请求还要区分优先级？
- 09 | SocketServer（下）：请求处理全流程源码分析
- 10 | KafkaApis：Kafka最重要的源码入口，没有之一
- 11 | Controller元数据：Controller都保存有哪些东西？有几种状态？
- 12 | ControllerChannelManager：Controller如何管理请求发送？
- 13 | ControllerEventManager：变身单线程后的Controller如何处理事件？
- 14 | Controller选举是怎么实现的？
- 15 | 如何理解Controller在Kafka集群中的作用？
- 16 | TopicDeletionManager： Topic是怎么被删除的？
- 17 | ReplicaStateMachine：揭秘副本状态机实现原理
- 18 | PartitionStateMachine：分区状态转换如何实现？
- 19 | TimingWheel：探究Kafka定时器背后的高效时间轮算法
- 20 | DelayedOperation：Broker是怎么延时处理请求的？
- 21 | AbstractFetcherThread：拉取消息分几步？
- 22 | ReplicaFetcherThread：Follower如何拉取Leader消息？
- 23 | ReplicaManager（上）：必须要掌握的副本管理类定义和核心字段
- 24 | ReplicaManager（中）：副本管理器是如何读写副本的？
- 25 | ReplicaManager（下）：副本管理器是如何管理副本的？
- 26 | MetadataCache：Broker是怎么异步更新元数据缓存的？
- 27 | 消费者组元数据（上）：消费者组都有哪些元数据？
- 28 | 消费者组元数据（下）：Kafka如何管理这些元数据？
- 29 | GroupMetadataManager：组元数据管理器是个什么东西？
- 30 | GroupMetadataManager：位移主题保存的只是位移吗？
- 31 | GroupMetadataManager：查询位移时，不用读取位移主题？
- 32 | GroupCoordinator：在Rebalance中，Coordinator如何处理成员入组？
- 33 | GroupCoordinator：在Rebalance中，如何进行组同步？
- 特别放送（一）| 经典的Kafka学习资料有哪些？
- 特别放送（二）| 一篇文章带你了解参与开源社区的全部流程
- 特别放送（三）| 我是怎么度过日常一天的？
- 特别放送（四）| 20道经典的Kafka面试题详解
- 特别放送（五） | Kafka 社区的重磅功能：移除 ZooKeeper 依赖
- 期中测试 | 这些源码知识，你都掌握了吗？
- 期末测试 | 一套习题，测试你的掌握程度
- 结束语 | 源码学习，我们才刚上路呢