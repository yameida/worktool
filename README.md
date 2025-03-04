## WorkTool

本安卓应用是一个依附于企业微信来运行的无人值守群管理机器人，非hook侵入式函数修改，使用安卓系统原生支持的无障碍服务能力，手机无需Root，应用兼容99%的手机，长时间运行稳定且因为没有修改系统和软件所以理论上不存在被外挂监测和封号风险。
机器人支持查看问答记录，创建群、群管理，群发等功能，还支持接入自己的问答接口来全面接管机器人。

## 演示

**发送消息**

<img src="https://github.com/gallonyin/worktool/blob/master/images/send_message.gif"  height="500" width="280">
注：动图为机器人自动运行
更多演示看这里
https://www.apifox.cn/apidoc/project-1035094/doc-840833


<img src="https://github.com/gallonyin/worktool/blob/master/images/chatgpt.png"  height="500" width="360">
机器人集成ChatGPT效果


## 兼容版本（重要）

经过测试验证的版本：企业微信 4.0.2 至 4.1.6 (5月19日上架)、企业微信政务版
建议使用 WorkTool 已兼容的最新企业微信版本

## 快速使用

[快速入门文档](https://worktool.apifox.cn/)

1. 准备一台无人使用的可联网安卓手机（本APP兼容99%安卓机型 系统要求>=Android7.0）
2. 手机登录企业微信（账号需要提前实名认证，不然很多功能无法正常使用）
3. 建议提前给该企业微信账号开通"工作台"-"客户群"权限（如无需外部群创建和管理可不开启）
4. 自助申请一个[机器人链接号(点击这里)](https://wt.asrtts.cn/regist.html)，您也可以加入QQ群向管理员咨询如何操作。
5. 在这台手机上安装[WorkTool APP安装包(点击下载)](https://cdn.asrtts.cn/uploads/worktool/apk/worktool-2.6.1.apk)
6. 打开WorkTool APP，按照APP提示保存链接号，开启主功能，并打开到企业微信界面，不要关闭屏幕即可。

如果您想使用自己开发的QA回调接口接收机器人收到的所有消息并定制回答，请参考[第三方QA回调接口规范(点击这里)](https://www.apifox.cn/apidoc/project-1035094/doc-861677)开发接口，并在[机器人第三方QA配置(点击这里)](https://www.apifox.cn/apidoc/project-1035094/api-22587884)提交您的机器人id和回调接口地址

## 文档

这里有所有详细的API文档和调用示例！！！

这里有所有详细的API文档和调用示例！！！

这里有所有详细的API文档和调用示例！！！

https://worktool.apifox.cn/doc-850007

## 零代码集成

- 集简云: https://www.jijyun.cn/apps/detail/1000983

## 混淆

绝大部分代码均可以混淆，但由于使用的类库如okhttp、umeng不能混淆等情况，已经列在proguard-rules.pro当中，可以直接使用

#  Copyright

Apache License, Version 2.0

#  联系方式

- 官网: http://wt.asrtts.cn/
- Email: gallonyin@163.com
- QQ群: 716513331, 801199277（链接号申请/问题反馈）
- 如果遇到问题欢迎在群里提问或提交issue。
- WorkTool志愿者开发群: 716217439

# 版本更新

tag 2.6.1 2023-06-13 控件检索优化;其他已知问题修复

tag 2.6.0 2023-05-28 anr自动处理;其他已知问题修复

tag 2.5.9 2023-05-12 自动通过群邀请;拉人进群发送邀请;获取群聊全称;获取群二维码;其他已知问题修复

tag 2.5.8 2023-04-06 优化消息一致性检查;执行异常自动重试;兼容性更新;其他已知问题修复

tag 2.5.7 2023-03-15 自动通过群邀请;优化消息识别;异常环境监测;其他已知问题修复

tag 2.5.6 2023-02-06 兼容主流模拟器;其他已知缺陷修复

tag 2.5.5 2023-02-02 文件发送优化;新消息增强校验;其他已知缺陷修复

tag 2.5.4 2023-01-28 文件发送优化;消息列表识别优化;切换企业;其他已知缺陷修复

tag 2.5.3 2023-01-11 群模板兼容新版;消息类型识别优化;其他已知缺陷修复

tag 2.5.2 2023-01-05 返回首页缺陷修复

tag 2.5.1 2023-01-04 优化返回首页和回复速度;支持群二维码回调;其他已知缺陷修复

tag 2.4.2 2022-12-14 优化at;优化通过好友请求;其他已知缺陷修复

tag 2.4.1 2022-12-9 集成悬浮窗启停功能;房间检索优化;界面更新;其他已知缺陷修复

tag 2.4.0 2022-11-23 修改用户备注;添加待办;重要宕机缺陷修复

tag 2.3.3 2022-10-28 解散群;改群模板;其他已知问题优化

tag 2.3.1 2022-10-25 优化推送文件;特殊符号兼容;交互提示;其他已知问题修复

tag 2.3.0 2022-10-17 支持at多人;支持推送任意文件;支持群备注修改;交互提示优化;其他已知问题修复

tag 2.2.6 2022-09-16 优化搜索

tag 2.2.5 2022-09-15 主动加好友可改附言;移除[自动回复]前缀;群内回复@提醒;搜索更加精准;学校类企业兼容

tag 2.2.3 2022-08-26 兼容主动添加好友;文本匹配优化;其他已知问题优化

tag 2.2.1 2022-08-25 多控件类型兼容;兼容多版本系统;其他已知问题修复

tag 2.1.2 2022-08-18 多控件类型兼容;兼容多版本系统

tag 2.1 2022-08-17 真@提醒;获取未读消息优化;其他已知问题修复

tag 2.0 2022-08-11 全面兼容企业微信最新版本(4.0.12)和政务微信;控件搜索优化;已知问题修复

tag 1.3 2022-08-02 被动添加好友优化

tag 1.2 2022-07-11 内部群已读数过滤;避免群名重复创建;可回调获取群二维码;其他稳定性优化

tag 1.1 2022-06-20 大幅度提高系统稳定性和响应速度

tag 1.0 2022-05-27 首次可用版本更新
