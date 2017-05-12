# Prometheus 实战

v0.1.0

在过去一年左右时间里，我们使用 Prometheus 完成了对几个机房的基础和业务监控，大大提高了我们服务质量，以及 oncall 水平，在此特别感谢 Promethues 这样优秀的开源软件。

当初选择 Prometheus 并不是偶然，因为：

* Prometheus 是按照 Google SRE 运维之道的理念构建的，具有实用性和前瞻性。

* Prometheus 社区非常活跃，基本稳定在 1个月1个版本的迭代速度；从去年 v1.01 开始接触使用以来，到目前发布的 v1.6.1 以及最新最新的 v2.0 ，你会发现 Prometheus 一直在进步，在优化。

* Go 语言开发，性能不错，安装部署简单，跨平台。

* 丰富的数据收集客户端，官方提供了各种常用 exporter。

* 丰富强大的查询能力。

Prometheus 作为监控后起之秀，虽然还有做的不够好的地方，但是不妨碍我们使用它，根据我们长期的使用经验来看，它足够优秀，足已满足大多数场景需求。只不过因为它是新东西，需要你花费更多力气才能发挥它的威力而已。

本书主要根据个人过去一年多的使用经验总结而成，内容主要包括 Prometheus 基础，进阶，实战等方面，希望对大家有所帮助。

你准备好了吗？接下来我们就一起开始这段神奇旅行吧！

