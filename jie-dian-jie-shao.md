# 节点介绍

<details>

<summary>普通节点（例如HK01）</summary>



</details>

### 线路

本站线路均采用AWS和Azure及华为CC

### Azure

Microsoft 拥有并运营全球最大的主干网络之一。 此全球性的复杂体系结构跨越 165,000 英里以上，将我们的数据中心和客户连接到一起。

世界各地的客户每天都会连接 Microsoft Azure、必应、Dynamics 365、Microsoft 365、XBox 等服务并向其传递数以万亿的请求。 不管是哪种类型的客户，他们都希望我们的服务能够保持可靠并即时做出响应。

[Microsoft 全球网络](https://azure.microsoft.com/global-infrastructure/global-network/) (WAN) 是提供卓越云体验的核心所在。 我们的全球网络连接了 61 个 Azure 区域中的 Microsoft [数据中心](https://azure.microsoft.com/global-infrastructure/)以及战略性地放置于全球的边缘节点的庞大网格，提供可满足任何需求的可用性、容量和灵活性。

![Microsoft global networ](https://docs.microsoft.com/zh-cn/azure/networking/media/microsoft-global-network/microsoft-global-wan.png)

参考文档：[https://docs.microsoft.com/zh-cn/azure/networking/microsoft-global-network?toc=/azure/networking/fundamentals/toc.json](https://docs.microsoft.com/zh-cn/azure/networking/microsoft-global-network?toc=/azure/networking/fundamentals/toc.json)

### Aws

Aws是全球最大的云服务提供商，AWS 的网络可用性在所有云服务提供商中最高。每个区域均完全隔离并由多个可用区组成，每个可用区也是我们基础设施中完全隔离的分区。为了更好地隔离任何问题并实现高可用性，您可以跨同一区域中的多个可用区对应用程序进行分区。此外，AWS 控制平面和 AWS 管理控制台跨区域分布，包括区域性 API 终端节点。这些终端节点与全局控制平面功能隔离后，可以至少安全运行 24 小时，无需客户在隔离期间通过外部网络访问区域或其 API 终端节点。

![](https://1-1306085497.cos.ap-shanghai.myqcloud.com/img/image-20220408015937124.png)

参考文档：[https://aws.amazon.com/cn/about-aws/global-infrastructure/?pg=WIAWS](https://aws.amazon.com/cn/about-aws/global-infrastructure/?pg=WIAWS)\


### 华为云CC

云连接（Cloud Connect）为用户提供一种能够快速构建跨区域VPC之间以及云上多VPC与云下多数据中心之间的高速、优质、稳定的网络能力，帮助用户打造一张具有企业级规模和通信能力的全球云上网络。

通过创建云连接，将用户所需要实现互通的不同区域的网络实例加载到创建的云连接实例中，这里的网络实例可以是用户自己创建的VPC实例或用户创建的用于本地数据中心接入的VGW实例，也可以是其它用户授予权限允许加载的VPC实例，最后通过配置需要互通的网络实例之间的域间带宽，就可以快速的为您提供全球网络互通服务。

![](<.gitbook/assets/image (1).png>)

参考文档：[https://support.huaweicloud.com/productdesc-cc/cc\_01\_0001.html](https://support.huaweicloud.com/productdesc-cc/cc\_01\_0001.html)

