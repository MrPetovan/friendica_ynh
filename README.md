<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Friendica for YunoHost

[![Integration level](https://dash.yunohost.org/integration/friendica.svg)](https://dash.yunohost.org/appci/app/friendica) ![](https://ci-apps.yunohost.org/ci/badges/friendica.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/friendica.maintain.svg)  
[![Install Friendica with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=friendica)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Friendica quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Social Communication Server

**Shipped version:** 2021.07~ynh1

**Demo:** https://demo.example.com

## Screenshots

![](./doc/screenshots/friendica-vier-profile.png)

## Disclaimers / important information

## Installation

### Register a new domain and add it to YunoHost

Before installing, read the [Friendica installation instructions](https://github.com/friendica/friendica/blob/develop/doc/Install.md) for important information about installation.

- Dedicated domain (must install under web root like **https://friendica.example.com/** not **https://example.com/friendica/** )

- Friendica requires browser-approved SSL certificates.

### Install Friendica
Use the YunoHost admin panel to install Friendica by entering the GitHub repo address in the custom app URL:

		https://github.com/YunoHost-Apps/friendica_ynh

## User with LDAP admin rights
**For admin rights**: When installation is complete, you will need to visit your domain page and login with the **admin account username and password** which was entered at the time of installation process. You can then create your profile and access the admin panel.

 **For normal YunoHost users :** Normal LDAP users can login through Ldap authentication and create there profiles.

## Documentation and resources

* Official app website: http://friendi.ca
* Official user documentation: https://wiki.friendi.ca/
* Official admin documentation: https://github.com/friendica/friendica/wiki
* Upstream app code repository: https://github.com/friendica/friendica
* YunoHost documentation for this app: https://yunohost.org/app_friendica
* Report a bug: https://github.com/YunoHost-Apps/friendica_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/friendica_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/friendica_ynh/tree/testing --debug
or
sudo yunohost app upgrade friendica -u https://github.com/YunoHost-Apps/friendica_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps