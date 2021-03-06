<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Gossa for YunoHost

[![Integration level](https://dash.yunohost.org/integration/gossa.svg)](https://dash.yunohost.org/appci/app/gossa) ![Working status](https://ci-apps.yunohost.org/ci/badges/gossa.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/gossa.maintain.svg)  
[![Install Gossa with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gossa)

*[Lire ce readme en franΓ§ais.](./README_fr.md)*

> *This package allows you to install Gossa quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A fast and simple webserver for your files, that's dependency-free and with under 250 lines of code, easy to review.

### Features

    π files/directories browser & handler
    π© drag-and-drop uploader
    π₯ fast golang static server
    πΎ 90s web UI that prints in milliseconds
    πΈ video streaming & picture browser
    βοΈ simple note editor
    β¨οΈ keyboard navigation
    π lightweight and dependency free codebase
    π >95% test coverage and reproducible builds
    π easy multi account setup, read-only mode
    β¨ PWA enabled


**Shipped version:** 0.2.1~ynh1

## Screenshots

![Screenshot of Gossa](./doc/screenshots/screenshot.gif)

## Documentation and resources

* Official app website: <https://github.com/pldubouilh/gossa>
* Upstream app code repository: <https://github.com/pldubouilh/gossa>
* YunoHost documentation for this app: <https://yunohost.org/app_gossa>
* Report a bug: <https://github.com/YunoHost-Apps/gossa_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/gossa_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
or
sudo yunohost app upgrade gossa -u https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
