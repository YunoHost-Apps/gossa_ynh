<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Gossa para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/gossa)](https://ci-apps.yunohost.org/ci/apps/gossa/)
![Estado funcional](https://apps.yunohost.org/badge/state/gossa)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/gossa)

[![Instalar Gossa con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gossa)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarGossa rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

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


**Versión actual:** 1.1.2~ynh2

## Capturas

![Captura de Gossa](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Repositorio del código fuente oficial de la aplicación : <https://github.com/pldubouilh/gossa>
- Catálogo YunoHost: <https://apps.yunohost.org/app/gossa>
- Reportar un error: <https://github.com/YunoHost-Apps/gossa_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/gossa_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
o
sudo yunohost app upgrade gossa -u https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
