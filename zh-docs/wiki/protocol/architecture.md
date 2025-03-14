# 协议架构概述

> :warning: 这篇文章是一个[存根条目](https://en.wikipedia.org/wiki/Wikipedia:Stub)，请通过[贡献](/contributing.md)来帮助 wiki 扩展它。

当前的架构是多年演变的结果。该协议由两个主要部分组成——执行层和共识层。执行层 (EL) 处理实际的交易和用户交互，是全球计算机执行程序的地方。共识层 (CL) 提供权益证明共识机制——一种加密经济学安全机制，确保所有节点遵循相同的提示，并推动执行层的规范链。

在实际操作中，这些层在各自的客户端中实现，并通过 API 连接。每个层都有自己的对等网络，处理不同类型的数据。

![](./img/clients-overview.png)

从每个客户端的底层来看，它们由许多基础功能组成：

![](./img/protocol-overview.png)
