<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Chitchatter for YunoHost

[![Integration level](https://dash.yunohost.org/integration/chitchatter.svg)](https://dash.yunohost.org/appci/app/chitchatter) ![Working status](https://ci-apps.yunohost.org/ci/badges/chitchatter.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/chitchatter.maintain.svg)

[![Install Chitchatter with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chitchatter)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Chitchatter quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Chitchatter is a free (as in both price and freedom) communication tool. It is designed with security and privacy in mind.

### Features

- Fully open source (licensed under GPL v2)
- Peer-to-peer
- Encrypted (via WebRTC)
- Serverless
- Ephemeral
- Decentralized 

**Shipped version:** 1.0~ynh10

**Demo:** https://chitchatter.im/

## Screenshots

![Screenshot of Chitchatter](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://chitchatter.im/>
* Upstream app code repository: <https://github.com/jeremyckahn/chitchatter>
* YunoHost Store: <https://apps.yunohost.org/app/chitchatter>
* Report a bug: <https://github.com/YunoHost-Apps/chitchatter_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing --debug
or
sudo yunohost app upgrade chitchatter -u https://github.com/YunoHost-Apps/chitchatter_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
