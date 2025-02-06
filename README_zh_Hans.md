<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 OPcache GUI

[![集成程度](https://apps.yunohost.org/badge/integration/opcache-gui)](https://ci-apps.yunohost.org/ci/apps/opcache-gui/)
![工作状态](https://apps.yunohost.org/badge/state/opcache-gui)
![维护状态](https://apps.yunohost.org/badge/maintained/opcache-gui)

[![使用 YunoHost 安装 OPcache GUI](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opcache-gui)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 OPcache GUI。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A clean and responsive interface for Zend OPcache information, showing statistics, settings and cached files, and providing a real-time update for the information.


**分发版本：** 3.5.5~ynh1

## 截图

![OPcache GUI 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 上游应用代码库： <https://github.com/amnuts/opcache-gui>
- YunoHost 商店： <https://apps.yunohost.org/app/opcache-gui>
- 报告 bug： <https://github.com/YunoHost-Apps/opcache-gui_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/opcache-gui_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opcache-gui_ynh/tree/testing --debug
或
sudo yunohost app upgrade opcache-gui -u https://github.com/YunoHost-Apps/opcache-gui_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
