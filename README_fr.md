# Pelican pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/pelican.svg)](https://dash.yunohost.org/appci/app/pelican) ![](https://ci-apps.yunohost.org/ci/badges/pelican.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/pelican.maintain.svg)  
[![Installer Pelican avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pelican)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Pelican rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Pelican is a static site generator, written in Python_.

* Compose content in Markdown_ or reStructuredText_ using your editor of choice
* Simple command-line tool (re)generates HTML, CSS, and JS from your source content
* Easy to interface with version control systems and web hooks
* Completely static output is simple to host anywhere


**Version incluse :** 1.0~ynh2



## Documentations et ressources

* Site officiel de l'app : https://blog.getpelican.com
* Documentation officielle de l'admin : https://docs.getpelican.com/en/latest/index.html
* Dépôt de code officiel de l'app : https://github.com/getpelican/pelican
* Documentation YunoHost pour cette app : https://yunohost.org/app_pelican
* Signaler un bug : https://github.com/YunoHost-Apps/pelican_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/pelican_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/pelican_ynh/tree/testing --debug
ou
sudo yunohost app upgrade pelican -u https://github.com/YunoHost-Apps/pelican_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps