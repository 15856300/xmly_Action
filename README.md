# 须知
原作者:https://github.com/Zero-S1/xmly_speed

### 食用说明
GitHub action自动运行，账号信息读取自 Setting -> Secrets 仓库位置

- cookie 信息抓包自**手机app(喜马拉雅极速版)**，域名为 `m.ximalaya.com`的可以
- fork 本项目
- **必须**  Secrets 新增 `XMLY_SPEED_COOKIE`，填入cookie信息 ，多账号换行
-  **可选**  通知服务, bark服务、server酱或者tg通知可选, 分别在 Secrets  新增 `BARK` 或者 `SCKEY` 或者(`TG_BOT_TOKEN`与`TG_USER_ID`), 并填写对应的参数;每天默认19:30通知一次

### 如何抓包cookie
- [手机抓包工具汇总](https://blog.zengrong.net/post/capture-package-on-phone/)
- [Stream -- iPhone上抓包神器](https://blog.csdn.net/heqiang2015/article/details/84023327)

<p align="center">
  <img src="https://github.com/Zero-S1/xmly_speed/blob/master/%E6%8A%93%E5%8C%85.png" alt="抓包" width='40%' height='40%'/> 

框中信息，不包含开头的`Cookie: `
### 账号注册以及风控
1、使用**不同的手机设备**进行注册、刚注册的账号**不要退出**  
2、同一手机**不要切换**账号  
3、前三天需要手动完成任务
