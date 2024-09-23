<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Chitchatter voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/chitchatter.svg)](https://ci-apps.yunohost.org/ci/apps/chitchatter/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/chitchatter.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/chitchatter.maintain.svg)

[![Chitchatter met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chitchatter)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Chitchatter snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Chitchatter is a free (as in both price and freedom) communication tool. It is designed with security and privacy in mind.

### Features

- Fully open source (licensed under GPL v2)
- Peer-to-peer
- Encrypted (via WebRTC)
- Serverless
- Ephemeral
- Decentralized 

**Geleverde versie:** 1.0~ynh11

**Demo:** <https://chitchatter.im/>

## Schermafdrukken

![Schermafdrukken van Chitchatter](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://chitchatter.im/>
- Upstream app codedepot: <https://github.com/jeremyckahn/chitchatter>
- YunoHost-store: <https://apps.yunohost.org/app/chitchatter>
- Meld een bug: <https://github.com/YunoHost-Apps/chitchatter_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing --debug
of
sudo yunohost app upgrade chitchatter -u https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
