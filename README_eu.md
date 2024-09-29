<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Simple File Manager YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/simple-file-manager.svg)](https://ci-apps.yunohost.org/ci/apps/simple-file-manager/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/simple-file-manager.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/simple-file-manager.maintain.svg)

[![Instalatu Simple File Manager YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-file-manager)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Simple File Manager YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

A Simple PHP file manager. The code is a single php file.  

### Features

- Single file, there are no images, or css folders.  
- Ajax based so it is fast, but doesn't break the back button
- Allows drag and drop file uploads if the folder is writable by the webserver (`chmod 777 your/folder`)
- Suits my aesthetics.  More like Dropbox, and less like Windows Explorer
- Works with Unicode file names
- The interface is usable from an iPad
- XSRF protection, and an optional password.

**Paketatutako bertsioa:** 1.0~ynh2

## Pantaila-argazkiak

![Simple File Manager(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/jcampbell1/simple-file-manager>
- YunoHost Denda: <https://apps.yunohost.org/app/simple-file-manager>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/simple-file-manager_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing --debug
edo
sudo yunohost app upgrade simple-file-manager -u https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
