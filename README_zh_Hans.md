<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Gossa

[![集成程度](https://apps.yunohost.org/badge/integration/gossa)](https://ci-apps.yunohost.org/ci/apps/gossa/)
![工作状态](https://apps.yunohost.org/badge/state/gossa)
![维护状态](https://apps.yunohost.org/badge/maintained/gossa)

[![使用 YunoHost 安装 Gossa](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gossa)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Gossa。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A fast and simple webserver for your files, that's dependency-free and with under 250 lines of code, easy to review.

### Features

    🔍 files/directories browser & handler
    📩 drag-and-drop uploader
    🥂 fast golang static server
    💾 90s web UI that prints in milliseconds
    📸 video streaming & picture browser
    ✍️ simple note editor
    ⌨️ keyboard navigation
    🚀 lightweight and dependency free codebase
    🔒 >95% test coverage and reproducible builds
    💑 easy multi account setup, read-only mode
    ✨ PWA enabled


**分发版本：** 1.1.2~ynh2

## 截图

![Gossa 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 上游应用代码库： <https://github.com/pldubouilh/gossa>
- YunoHost 商店： <https://apps.yunohost.org/app/gossa>
- 报告 bug： <https://github.com/YunoHost-Apps/gossa_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/gossa_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
或
sudo yunohost app upgrade gossa -u https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
