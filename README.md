# Amigo-bot-plugin-keeper
基于 [Amigo-bot](https://github.com/mosqu1t0/Amigo-bot) 的插件
## 简介
写了一个简单的管理 bot 的插件来自娱自乐。

指令|作用
--|--
`！改名 [ 新名片 ] [ null/群号 ]` | 更改 bot 在某群中的群名片（在群中使用，允许不使用群号，会默认修改 bot 在该群的名片）
`！好友` | 获取 bot 已添加的好友列表 （需要对 bot 私发）
`！拉黑 [ 好友 qq ]` | 删除 bot 已添加的指定好友 （需要对 bot 私发）
`！群组` | 获取 bot 已进入的群列表 （需要对 bot 私发）
`！退群 [ 群号 ]` | 退出 bot 已进入的指定群 （需要对 bot 私发）

> 注意：
> - `！` 为全角符号
> - 指令和 `[...]` 之间只能有一个空格

> 以上指令都需要有 root 身份的账户发送才有效
