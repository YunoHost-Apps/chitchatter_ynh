<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Chitchatter YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/chitchatter.svg)](https://ci-apps.yunohost.org/ci/apps/chitchatter/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/chitchatter.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/chitchatter.maintain.svg)

[![Instalatu Chitchatter YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chitchatter)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Chitchatter YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Chitchatter is a free (as in both price and freedom) communication tool. It is designed with security and privacy in mind.

### Features

- Fully open source (licensed under GPL v2)
- Peer-to-peer
- Encrypted (via WebRTC)
- Serverless
- Ephemeral
- Decentralized 

**Paketatutako bertsioa:** 1.0~ynh11

**Demoa:** <https://chitchatter.im/>

## Pantaila-argazkiak

![Chitchatter(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://chitchatter.im/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/jeremyckahn/chitchatter>
- YunoHost Denda: <https://apps.yunohost.org/app/chitchatter>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/chitchatter_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing --debug
edo
sudo yunohost app upgrade chitchatter -u https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
