<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Gossa per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/gossa.svg)](https://dash.yunohost.org/appci/app/gossa) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/gossa.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/gossa.maintain.svg)

[![Installa Gossa con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gossa)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Gossa su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

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


**Versione pubblicata:** 1.0.0~ynh1

## Screenshot

![Screenshot di Gossa](./doc/screenshots/screenshot.png)

## Documentazione e risorse

- Repository upstream del codice dell’app: <https://github.com/pldubouilh/gossa>
- Store di YunoHost: <https://apps.yunohost.org/app/gossa>
- Segnala un problema: <https://github.com/YunoHost-Apps/gossa_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/gossa_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
o
sudo yunohost app upgrade gossa -u https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
