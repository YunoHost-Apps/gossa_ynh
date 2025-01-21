<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Gossa voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/gossa)](https://ci-apps.yunohost.org/ci/apps/gossa/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/gossa)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/gossa)

[![Gossa met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gossa)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Gossa snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

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


**Geleverde versie:** 1.1.2~ynh2

## Schermafdrukken

![Schermafdrukken van Gossa](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Upstream app codedepot: <https://github.com/pldubouilh/gossa>
- YunoHost-store: <https://apps.yunohost.org/app/gossa>
- Meld een bug: <https://github.com/YunoHost-Apps/gossa_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/gossa_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
of
sudo yunohost app upgrade gossa -u https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
