# Huginn pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/huginn.svg)](https://dash.yunohost.org/appci/app/huginn) ![](https://ci-apps.yunohost.org/ci/badges/huginn.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/huginn.maintain.svg)  
[![Installer Huginn avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=huginn)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Huginn rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Huginn is a system for building agents that perform automated tasks for you online. They can read the web, watch for events, and take actions on your behalf. Huginn's Agents create and consume events, propagating them along a directed graph. Think of it as a hackable version of IFTTT or Zapier on your own server. You always know who has your data. You do.

**Version incluse :** 2022.03.24~ynh1



## Captures d'écran

![](./doc/screenshots/your-agents.png)

## Documentations et ressources

* Site officiel de l'app : https://github.com/huginn/hugin
* Dépôt de code officiel de l'app : https://github.com/huginn/huginn
* Documentation YunoHost pour cette app : https://yunohost.org/app_huginn
* Signaler un bug : https://github.com/YunoHost-Apps/huginn_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/huginn_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/huginn_ynh/tree/testing --debug
ou
sudo yunohost app upgrade huginn -u https://github.com/YunoHost-Apps/huginn_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps