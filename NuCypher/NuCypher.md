## NuCypher —— 分布式密钥管理系统，为数据安全保驾护航

### 概览

* 网站：https://www.nucypher.com/
* 团队：来自国外知名创业孵化器YC，团队共有7人，目前大部分成员均为开发工程师和密码学专家。
* 白皮书：https://www.nucypher.com/assets/whitepapers/english.pdf
* 项目当前进度：NuCypher KMS 系统已与3款dApps集成；企业版本的产品已集成Hadoop 和 Kafka

### 众筹信息

* 代币符号：NKMS，ERC 20代币
* 众筹接受代币：ETH
* 硬顶/软顶：未公布
* 预售：预售轮已在2017年结束，从13家加密货币基金和风投共募集430万美元。此轮由Polychain Capital领投，跟投方包括Michael Novogratz’s Galaxy Digital Assets Fund, FBG Capital, Compound VC, Satoshi Fund, and Blockchain Korea Partners 等
* 公募：暂定2018年春季，预计在Q1和Q2时间
* 白名单：需要先加入官方电报群或邮件列表，之后需要进行KYC审核，KYC具体信息官方将在近期公布

### 社区活跃度

* 电报人数：18716
* Twitter 人数：2671
* Medium 订阅人数：445

### 项目简介

NuCypher  KMS 是一个分布式去中心化的密钥管理服务（KMS），提供加密和权限控制服务，它使得在公共网络上任意数量的参与者之间能够安全地共享私有数据，使用代理重加密技术来代理解密权限，这是传统对称加密和公钥加密方案所不能实现。内置的NKMS代币用来激励网络参与者执行密钥管理和权限代理/回收的操作。

![ycNil.jpg](https://s1.ax2x.com/2018/02/13/ycNil.jpg)

### 应用场景

* 共享加密文件（分布式Dropbox）
* 端对端加密群聊（"加密 Slack"）
* 患者控制的电子健康记录
* 分布式数字版权管理
* 盲身份管理
* 脚本和后端应用程序的秘密凭证管理
* 共享凭证和企业密码管理
* 强制访问日志
* 管理移动设备的授权和撤销

### 代币用途

协议经济由矿工网络组成，矿工节点提供稀缺资源并在资源消耗时获得回报。在NuCypher KMS中，矿工是重加密节点，根据提供的重加密操作的数量来区分他们的奖励。代币NKMS既是对矿工贡献工作的奖励，也是消费者为获得重加密服务所付出的代价。代币激励了系统正确计算和保证系统安全。

#### 以下是代币的具体使用场景：

* 矿工可以持有一定数量的重加密密钥，与他们作为抵押款所持有的代币数量成比例，由智能合约锁定，如果矿工作弊提供错误的服务，将损失一部分保证金
* 如果矿工在线并准备好提供服务，可能会获得“可用性奖励”
* 为阻止矿工泄露重加密的密钥，任何人可以使用重加密密钥的哈希挑战矿工，如果证实密钥已泄露，矿工作为担保的NKMS将被罚没

### NuCypher KMS 应用案例

[![yZHad.md.jpg](https://s1.ax2x.com/2018/02/12/yZHad.md.jpg)](https://simimg.com/i/yZHad)

* datum：分布式的社交网络和物联网数据集市
* wolk：基于 Ethereum SWARM 的分布式数据服务
* MediBloc：基于区块链的个人医疗信息生态系统

[![yZTSR.md.jpg](https://s1.ax2x.com/2018/02/12/yZTSR.md.jpg)](https://simimg.com/i/yZTSR)

* 集成Hadoop（著名的分布式系统基础架构），代理访问控制和加密管理系统，为HDFS提供细粒度的加密控制和快速的密钥轮替

[![yZmTr.md.jpg](https://s1.ax2x.com/2018/02/12/yZmTr.md.jpg)](https://simimg.com/i/yZmTr)

* 集成Kafka（著名的分布式消息框架），提供点对点的数据流和消息加密，并且最大程度减少性能消耗

### 项目团队

[![ycEZe.md.jpg](https://s1.ax2x.com/2018/02/13/ycEZe.md.jpg)](https://simimg.com/i/ycEZe)

[![ycLNd.md.jpg](https://s1.ax2x.com/2018/02/13/ycLNd.md.jpg)](https://simimg.com/i/ycLNd)

### 顾问

[![ycU9R.md.jpg](https://s1.ax2x.com/2018/02/13/ycU9R.md.jpg)](https://simimg.com/i/ycU9R)

### 优势

* 密钥管理服务（KMS）的作用自不必多说，目前亚马逊，腾讯，阿里云都已提供中心化的KMS服务，然而这要求这些中心化服务商本身具备极高的安全性和自律性，这本身无法做到完全可靠，对于安全至关重要的应用程序来说可能并不合适。NuCypher KMS的出现提供了一种无需信任的解决方案，在当前市场上并无其他竞争者，潜力巨大
* 使用代理重加密技术，未加密的对称密钥绝不会暴露在服务端，并且没有单点安全失败。即使被攻破，黑客也只能得到重新加密的密钥，并且对文件的访问任然受到保护。这一特性对于目前安全状况频发的互联网环境而言值得关注
* 团队已发布与Hadoop，Kafka 等现有的热门开发框架的集成插件，产品进度良好
* 预售轮获得众多著名机构投资，筹得资金已用于产品开发

### 挑战

* 团队成员目前基本为技术开发人员，KMS的成功不仅依赖技术开发，同样需要在推广方面击败目前市场上众多中心化密钥管理服务产品

### 总结建议

NuCypher KMS 目前在国外热度非常高，CEO MacLane 近期也频频出席多个区块链活动会议，技术团队在产品开发方面进度喜人，已推出企业版本（可以在官网申请Demo）和 热门开发框架的插件，推进效率非常高。可以预见 KMS 作为一项基础服务未来将在 dApps开发 中占据一席之地，并且在去中化KMS领域已占得先发优势。强烈建议大家持续关该项目动态！

***

## 更多优质项目敬请关注公众号 BlockGeeks

![mark](http://p1z55pj7o.bkt.clouddn.com/ico/180103/2dIdaf1Bjf.jpg)