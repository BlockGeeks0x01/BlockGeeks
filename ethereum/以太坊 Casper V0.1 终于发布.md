## 以太坊 Casper V0.1 首次发布

![fPMzK.jpg](https://s1.ax2x.com/2018/05/09/fPMzK.jpg)

首先，最近杂事太多更新不及时，抱歉！:cry:



当以太坊用户饱受网络拥堵和手续费膨胀的同时，以太坊开发团队正马不停蹄的开展共识协议和分片等升级扩展工作，就在不久前，2018年5月8日，备受期待的Casper第一版（v0.1，从版本号来看当然还是测试版咯）代码正式发布，这是团队计划中的对以太坊网络共识协议的升级版本。

​	在本周周二，Casper FFG（the Friendly Finality Gadget，友好的终极小工具？:joy:）开发人员 Danny Ryan在GitHub上提交了Casper FFG v0.1，并指出v0.1.0版本可以帮助以太坊客户端和外部审计人员更加清晰的追踪合约和代码变更。

![fPUqq.jpg](https://s1.ax2x.com/2018/05/10/fPUqq.jpg)

这里需要特意提一下，Casper 其实包含两个研究项目：

* Casper the Friendly Finality Gadget（FFG）

  Vitalik参与的Casper版本，POS/POW混合共识机制，通过在当前POW协议上叠加一个POS协议，POW仍将完成大部分出块工作，POS协议将定期验证检查点，即网络验证者进行确定性评估。这个版本主要是考虑为了平稳过渡到完全的POS机制。

* Casper the Friendly GHOST: Correct-by-Construction（CBC）

  Vlad Zamfir领导的Correct-by-construction Casper（实在翻译不出来），大致意思就是初始协议是不完整的，通过一定手段不断微调最终使这个不完全体变成完整版协议。

  ![fP1je.png](https://s1.ax2x.com/2018/05/10/fP1je.png)

针对此次升级，Danny Ryan也在Reddit上回复了很多关注者的留言，并说：

`“目前该合约的使用者不仅仅只有开发团队，还有审计人员，客户端开发人员等等，因此我们希望通过发布更清晰的版本和更新日志来帮助所有人井井有条的开展各自的工作。”`

Casper FFG 在2017年10月被第一次提出，旨在通过网络验证者押金和加密货币激励机制解决经济确定性问题。我们注意到在今年4月下旬提出了EIP1011：引入混合的Casper FFG，建立一个混合共识机制（POW+POS）的系统，并逐步探索剥离加密货币挖矿带来的问题（矿池集中化，资源大量消耗等）。

​	不出意外，Casper FFG混合共识机制应该是混合了POW和POS，最终目的是完全转到POS。根据相关的EIP提议，假如这次改进正式实施，以太坊区块奖励将从目前的3ETH减为0.6ETH。

***

## 更多信息敬请关注公众号 BlockGeeks

![mark](http://p1z55pj7o.bkt.clouddn.com/ico/180103/2dIdaf1Bjf.jpg)

