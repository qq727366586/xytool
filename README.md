# YIM 聊天推送系统

该项目可以业务于 推送、聊天等系统，鉴于goim 不怎么维护，所以复刻了此项目。欢迎感兴趣的伙伴一起维护。

Comet:

有状态服务，目前只支持ws通信(支持多节点部署)

Job:

消息分发层

Logic:

logic路由层，目前实现单聊



需要环境:

zookeeper kafka redis golang环境（建议>=1.17）



后续规划:

1. 群聊、广播、事件订阅
2. 离线消息存储漫游
3. ack机制
4. 服务发现注册
5. 等等..

感谢: https://github.com/Terry-Mao/goim带来的灵感，学到很多。
