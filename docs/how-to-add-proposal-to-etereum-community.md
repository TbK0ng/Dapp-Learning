how-to-add-proposal-to-etereum-community
## 如何向以太坊社区提交一个EIP？

### 前言

+ 以太坊社区需要构建，早期建设者会得到真实的价值回报。
+ 其他公链创造力很多是依靠以太坊社区，这也是以太坊社区的生命力所在。
+ 除了炒币，支持或者参与创造到社区的规划和建设中来，是非常有价值的。
+ EIP是以太坊提升提案，用来讨论任何有意思的建议，EIP721也就是NFT是之EIP一，来自于Lara Labs。

### 资源

+ URL：https://github.com/ethereum/EIPs/issues/new
+ 模板：https://github.com/ethereum/EIPs/blob/master/eip-template.md

### 注意事项

+ 首先深度阅读EIP-1:https://eips.ethereum.org/EIPS/eip-1

+ 要点下面会列出。

+ 注意！如果您想提交一个EIP，并且已经将其写成草稿（参见[模板](https://github.com/ethereum/EIPs/blob/master/eip-template.md)作为示例），请将其作为[Pull Request](https://github.com/ethereum/EIPs/pulls)提交。

+ 如果您正在考虑一个提案，但希望在提交草稿之前获得关于这个想法的一些反馈，那么请继续开一个Issue作为讨论的线程。请注意，您陈述想法的越清晰和完整，您可能收到的反馈质量就越高。

  请记住[EIP-1](./eip-1.md)中的以下指导原则：

  > 每个EIP必须有一个倡导者 - 即使用下面描述的风格和格式撰写EIP，在适当的论坛中引导讨论，并尝试围绕这个想法建立社区共识的人。EIP倡导者（也称为作者）首先应该确定这个想法是否适合成为EIP。在协议讨论论坛上发帖或开一个Issue是最好的方式。

  > 在写EIP之前公开审查一个想法是为了节省潜在作者的时间。首先询问以太坊社区一个想法是否原创，有助于防止在保证会被拒绝的事情上花费太多时间（搜索互联网并不总是能解决问题）。这也有助于确保这个想法适用于整个社区，而不仅仅是作者。仅仅因为一个想法对作者来说听起来不错，并不意味着它对大多数使用以太坊的人在大多数领域都有效。

  > 一旦倡导者已经询问了以太坊社区关于一个想法是否有被接受的可能性，就应该以Pull Request的形式提交一个EIP草稿。这给了作者一个机会来充实EIP草稿，使其格式正确，质量高，并解决关于提案的初步担忧。

### 解释

+ 提案首先是有了一些上下文和想法，思考，大多数来自于实际的工作和开发中遇到的问题和困难，发现需要改进以太坊会更好。
+ 例如社区项目在参与到元宇宙建设过程中，发现如果定义一套标准，会更有利于开发，而这套标准贡献给社区，能够帮助别人提升效率，也可以提升彼此的交互效率。
+ EIP的提交过程，提供了如何说清楚、说明白的标准。

#### 讨论

+ 首先要有一个champion，也就是主笔作者。
+ 然后在对应社区讨论，一般是github上建立一个issue（例如721的https://github.com/ethereum/eips/issues/721）或者一个论坛帖子：[the Ethereum Magicians forum](https://ethereum-magicians.org/)。
+ 讨论过程需要ascertain whether the idea is EIP-able，是不是值得和能够去建立一个EIP。
+ 另外，在写一个EIP之前，最好公开的讨论这个idea，询问以太坊社区是否可行，可以防止浪费太多时间在不必要的idea。
+ PS: 魔法师论坛的readme：https://ethereum-magicians.org/t/welcome-please-readme-first/8，发现需要很多时间逛一逛，熟悉规则。
+ 如果询问和讨论社区后，你的帖子大家觉得有机会接受，则提交一个提案草稿。

#### 草稿

+ Fork EIP库，像我这样：![fork](https://tva1.sinaimg.cn/large/e6c9d24ely1h0ymse1599j21zw0g2acq.jpg)
+ 使用模板[template](https://github.com/ethereum/EIPs/blob/master/eip-template.md) 撰写你的EIP，这里面有一大堆的概念，但先写再说。
+ 完成草稿后，提交一个Pull Request，嗯，就是传说中的PR，哈哈。
+ 提交后会被review，例如周博士的EIP4972:https://github.com/ethereum/EIPs/pull/4972

#### 状态

+ 提交PR后，社区核心审核人群：This PR requires review from one of [[@lightclient](https://github.com/lightclient), [@axic](https://github.com/axic), [@SamWilsn](https://github.com/SamWilsn)]
+ 反复沟通格式、表述，直到草稿被merge，则进入了EIP的状态列表。
+ 状态列表很复杂
+ [Status](https://github.com/qizhou/EIPs/blob/master/assets/eip-1/EIP-process-update.jpg)
+ 核心是：Idea-->Draft-->Review<-->Last Call-->Final
+ Review会进入Living状态，反复迭代修改
+ 也可能进入Stagnant的停滞状态。

#### 其他

+ 以太坊工作PM会议：https://github.com/ethereum/pm，包括议程，记录，对应twitter记录和视频。
+ 例如最近一次会议讨论记录：https://github.com/ethereum/pm/blob/master/AllCoreDevs-Meetings/Meeting%20134.md
+ Kiln和beacon chain的进展等等，目前我个人不清楚是否可以未经邀请去添加自己的agenda以及参与会议，看起来需要成为pm？。
+ 本文会发布在Dapp Learning社区:https://github.com/Dapp-Learning-DAO/Dapp-Learning，以及个人Blog(jLab.tech)

### 如何撰写一个EIP？请看下一篇文章




