<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Chitchatter pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/chitchatter.svg)](https://dash.yunohost.org/appci/app/chitchatter) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/chitchatter.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/chitchatter.maintain.svg)

[![Installer Chitchatter avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chitchatter)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Chitchatter rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Chitchatter est un outil de communication gratuit (comme dans le prix et la liberté). Il est conçu dans un souci de sécurité et de confidentialité.

### Caractéristiques

- Entièrement open source (sous licence GPL v2)
- D'égal à égal
- Chiffré (via WebRTC)
- Sans serveur
- Éphémère
- Décentralisé

**Version incluse :** 1.0~ynh11

**Démo :** <https://chitchatter.im/>

## Captures d’écran

![Capture d’écran de Chitchatter](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://chitchatter.im/>
- Dépôt de code officiel de l’app : <https://github.com/jeremyckahn/chitchatter>
- YunoHost Store : <https://apps.yunohost.org/app/chitchatter>
- Signaler un bug : <https://github.com/YunoHost-Apps/chitchatter_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing --debug
ou
sudo yunohost app upgrade chitchatter -u https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
