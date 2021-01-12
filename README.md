###须知
原作者:https://github.com/Zero-S1/xmly_speed

GitHub action自动运行，账号信息读取自 Setting -> Secrets 仓库位置

cookie 信息抓包自手机app(喜马拉雅极速版)，域名为 m.ximalaya.com的可以
fork 本项目
必须 Secrets 新增 XMLY_SPEED_COOKIE，填入cookie信息 ，多账号换行

可选 通知服务, bark服务、server酱或者tg通知可选, 分别在 Secrets 新增 BARK 或者 SCKEY 或者(TG_BOT_TOKEN与TG_USER_ID), 并填写对应的参数;每天默认19:30通知一次
