## X-MSG-IM是一套`高可靠`, `高性能`, `可测量`, `可扩展`, `去中心化的`的即时通信基础设施

### 它将具有如下核心能力:

* 单人会话, 包括end to end加密通信

* 多人会话, 万人群组

* 聊天室

* 文件与对象存储

* voip & pstn

* 客服系统

* iot接入

* to c公私有云部署

* to b公私有云部署

* to b多组织, 多地域部署与互通

* 开放联盟`open federation`


### 系统特性:

* gsm核心网设计理念, 可无限扩展.

* 高度可扩展, 向前向后兼容, 低冗余, 低延迟, 多QoS的电信级通信协议栈.

* 核心服务全部基于现代化的c++17标准实现. 高性能低耗能, 基本上你可以将它部署在一个树莓派上.

* 单机可支持百万级并发连接和每秒数十万条消息负载.

* 非侵入式的分布式信令跟踪`distributed signalling tracing`能力, 可极大地提高研发调试与运维效率.

* 核心业务数据库同时支持mysql 8.x or later, mongodb 4.x or later.

* 跨平台多语言客户端sdk,支持windows, linux, mac/ios, android, web.

### implemented:

* 单人会话

* 多人会话, 万人群组

* 文件与对象存储, 试验性地支持ipfs(星际文件系统)

* 开放联盟`open federation`

* to b场景下的组织架构/通讯录管理. to c场景下的联系人/好友管理.

* 多协议同时接入, 现在支持: tcp, websocket, http, 详见[libx-msg-im-xsc](https://github.com/dev5cn/libx-msg-im-xsc)

### in progress:

* 基于[kcp](https://github.com/skywind3000/kcp)的reliable-udp支持, 这使得x-msg-im的[核心通信框架](https://github.com/dev5cn/libx-msg-im-xsc)还可以用作pvp游戏服务器.

* 基于electron的pc客户端.

* 基于flutter?的移动客户端.

![img](https://github.com/dev5cn/x-msg-msc/raw/master/img/multi-domain.svg?sanitize=true)

<br/>
<br/>

更新信息请移步至: http://www.dev5.cn/x_msg_im/

QQ group: 721779037

