<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Z-Push for YunoHost

[![Integration level](https://dash.yunohost.org/integration/z-push.svg)](https://dash.yunohost.org/appci/app/z-push) ![](https://ci-apps.yunohost.org/ci/badges/z-push.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/z-push.maintain.svg)  
[![Install Z-Push with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=z-push)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Z-Push quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Z-Push is an Exchange ActiveSync fronted written in PHP which lets you synchronize emails (IMAP/SMTP backend) and calendar/contacts (cardDAV and caldDAV backend)


**Shipped version:** 2.6.1~ynh3



## Documentation and resources

* Official app website: http://z-push.org
* Official admin documentation: https://wiki.z-hub.io/display/ZP/Documentation
* Upstream app code repository: https://github.com/Z-Hub/Z-Push
* YunoHost documentation for this app: https://yunohost.org/app_z-push
* Report a bug: https://github.com/YunoHost-Apps/z-push_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/z-push_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/z-push_ynh/tree/testing --debug
or
sudo yunohost app upgrade z-push -u https://github.com/YunoHost-Apps/z-push_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps