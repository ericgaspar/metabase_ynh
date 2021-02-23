# Metabase for YunoHost

[![Integration level](https://dash.yunohost.org/integration/streama.svg)](https://dash.yunohost.org/appci/app/streama) ![](https://ci-apps.yunohost.org/ci/badges/streama.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/streama.maintain.svg)  
[![Install Streama with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=streama)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Streama quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Streama is a free self hosted media streaming server running on Java, that you can install on your Linux distribution. Its features are similar to those of Kodi and Plex and it is simply a matter of personal choice which one you would like to use.

**Shipped version:** 0.38.0.1

## Screenshots

![](https://raw.githubusercontent.com/metabase/metabase/master/docs/metabase-product-screenshot.png)

## Demo

* [Official demo](https://streama.demo-version.net)

**User**: demoUser  
**Password**: demoUser

## Installation guide

> :warning: Streama must be installed in the root domain or subdomain.

Default upload directory is: `/home/yunohost.app/streama` (must be mentioned in *Settings* page or can be changed)
 
Default local video directory is: `/home/yunohost.app/streama/upload` (must be mentioned in *Settings* page or can be changed)

## Documentation

 * Official documentation: https://www.metabase.com/docs/latest/

#### Multi-user support

* Are LDAP and HTTP auth supported? **No**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/metabase%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/metabase/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/metabase%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/metabase/)

## Limitations

## Additional information

## Links

 * Report a bug: https://github.com/YunoHost-Apps/metabase_ynh/issues
 * App website: https://metabase.com/
 * Upstream app repository: https://github.com/metabase/metabase
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/metabase_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/metabase_ynh/tree/testing --debug
or
sudo yunohost app upgrade metabase -u https://github.com/YunoHost-Apps/metabase_ynh/tree/testing --debug
```
