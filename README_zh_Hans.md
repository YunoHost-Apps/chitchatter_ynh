<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Chitchatter

[![集成程度](https://dash.yunohost.org/integration/chitchatter.svg)](https://dash.yunohost.org/appci/app/chitchatter) ![工作状态](https://ci-apps.yunohost.org/ci/badges/chitchatter.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/chitchatter.maintain.svg)

[![使用 YunoHost 安装 Chitchatter](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chitchatter)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Chitchatter。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Chitchatter is a free (as in both price and freedom) communication tool. It is designed with security and privacy in mind.

### Features

- Fully open source (licensed under GPL v2)
- Peer-to-peer
- Encrypted (via WebRTC)
- Serverless
- Ephemeral
- Decentralized 

**分发版本：** 1.0~ynh10

**演示：** <https://chitchatter.im/>

## 截图

![Chitchatter 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://chitchatter.im/>
- 上游应用代码库： <https://github.com/jeremyckahn/chitchatter>
- YunoHost 商店： <https://apps.yunohost.org/app/chitchatter>
- 报告 bug： <https://github.com/YunoHost-Apps/chitchatter_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing --debug
或
sudo yunohost app upgrade chitchatter -u https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
