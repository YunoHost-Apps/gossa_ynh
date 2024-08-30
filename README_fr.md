<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Gossa pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/gossa.svg)](https://ci-apps.yunohost.org/ci/apps/gossa/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/gossa.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/gossa.maintain.svg)

[![Installer Gossa avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gossa)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Gossa rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Un serveur Web rapide et simple pour vos fichiers, sans dépendance et avec moins de 250 lignes de code, facile à réviser.

### Fonctionnalités

🔍 navigateur et gestionnaire de fichiers/répertoires
📩 téléchargeur par glisser-déposer
🥂 serveur statique golang rapide
💾 interface utilisateur Web des années 90 qui imprime en quelques millisecondes
📸 streaming vidéo et navigateur d'images
✍️ éditeur de notes simple
⌨️ navigation au clavier
🚀 base de code légère et sans dépendance
🔒 >95 % de couverture de test et builds reproductibles
💑 configuration multi-compte facile, mode lecture seule
✨ PWA activé

**Version incluse :** 1.1.2~ynh1

## Captures d’écran

![Capture d’écran de Gossa](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://github.com/pldubouilh/gossa>
- YunoHost Store : <https://apps.yunohost.org/app/gossa>
- Signaler un bug : <https://github.com/YunoHost-Apps/gossa_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/gossa_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
ou
sudo yunohost app upgrade gossa -u https://github.com/YunoHost-Apps/gossa_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
