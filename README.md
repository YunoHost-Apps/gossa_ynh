<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Gossa for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/gossa)](https://ci-apps.yunohost.org/ci/apps/gossa/)
![Working status](https://apps.yunohost.org/badge/state/gossa)
![Maintenance status](https://apps.yunohost.org/badge/maintained/gossa)

[![Install Gossa with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gossa)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Gossa quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

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


**Shipped version:** 1.1.2~ynh2

## Screenshots

![Screenshot of Gossa](./doc/screenshots/screenshot.png)

## Documentation and resources

- Upstream app code repository: <https://github.com/pldubouilh/gossa>
- YunoHost Store: <https://apps.yunohost.org/app/gossa>
- Report a bug: <https://github.com/YunoHost-Apps/gossa_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/gossa_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
or
sudo yunohost app upgrade gossa -u https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
