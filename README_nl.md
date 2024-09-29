<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Simple File Manager voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/simple-file-manager.svg)](https://ci-apps.yunohost.org/ci/apps/simple-file-manager/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/simple-file-manager.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/simple-file-manager.maintain.svg)

[![Simple File Manager met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-file-manager)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Simple File Manager snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

A Simple PHP file manager. The code is a single php file.  

### Features

- Single file, there are no images, or css folders.  
- Ajax based so it is fast, but doesn't break the back button
- Allows drag and drop file uploads if the folder is writable by the webserver (`chmod 777 your/folder`)
- Suits my aesthetics.  More like Dropbox, and less like Windows Explorer
- Works with Unicode file names
- The interface is usable from an iPad
- XSRF protection, and an optional password.

**Geleverde versie:** 1.0~ynh2

## Schermafdrukken

![Schermafdrukken van Simple File Manager](./doc/screenshots/screenshot.png)

## :red_circle: Anti-eigenschappen

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentatie en bronnen

- Upstream app codedepot: <https://github.com/jcampbell1/simple-file-manager>
- YunoHost-store: <https://apps.yunohost.org/app/simple-file-manager>
- Meld een bug: <https://github.com/YunoHost-Apps/simple-file-manager_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing --debug
of
sudo yunohost app upgrade simple-file-manager -u https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
