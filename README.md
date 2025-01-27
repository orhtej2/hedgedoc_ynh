<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# HedgeDoc for YunoHost

[![Integration level](https://dash.yunohost.org/integration/hedgedoc.svg)](https://dash.yunohost.org/appci/app/hedgedoc) ![Working status](https://ci-apps.yunohost.org/ci/badges/hedgedoc.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/hedgedoc.maintain.svg)

[![Install HedgeDoc with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hedgedoc)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install HedgeDoc quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

HedgeDoc (formerly known as CodiMD) is an open-source, web-based, self-hosted, collaborative markdown editor.
You can use it to easily collaborate on notes, graphs and even presentations in real-time. All you need to do is to share your note-link to your co-workers and they’re ready to go.

### Features

- Real-time collaboration
- Graphs & diagrams
- Revisions
- Presentation mode
- Easy to use permission system
- Low system requirements


**Shipped version:** 1.9.9~ynh1

**Demo:** https://demo.hedgedoc.org/

## Screenshots

![Screenshot of HedgeDoc](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://hedgedoc.org>
* Official admin documentation: <https://docs.hedgedoc.org/>
* Upstream app code repository: <https://github.com/hedgedoc/hedgedoc>
* YunoHost documentation for this app: <https://yunohost.org/app_hedgedoc>
* Report a bug: <https://github.com/YunoHost-Apps/hedgedoc_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
or
sudo yunohost app upgrade hedgedoc -u https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
