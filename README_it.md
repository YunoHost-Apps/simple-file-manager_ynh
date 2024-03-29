<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Simple File Manager per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/simple-file-manager.svg)](https://dash.yunohost.org/appci/app/simple-file-manager) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/simple-file-manager.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/simple-file-manager.maintain.svg)

[![Installa Simple File Manager con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-file-manager)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Simple File Manager su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

A Simple PHP file manager. The code is a single php file.  

### Features

- Single file, there are no images, or css folders.  
- Ajax based so it is fast, but doesn't break the back button
- Allows drag and drop file uploads if the folder is writable by the webserver (`chmod 777 your/folder`)
- Suits my aesthetics.  More like Dropbox, and less like Windows Explorer
- Works with Unicode file names
- The interface is usable from an iPad
- XSRF protection, and an optional password.

**Versione pubblicata:** 1.0~ynh1

## Screenshot

![Screenshot di Simple File Manager](./doc/screenshots/screenshot.png)

## Documentazione e risorse

- Repository upstream del codice dell’app: <https://github.com/jcampbell1/simple-file-manager>
- Store di YunoHost: <https://apps.yunohost.org/app/simple-file-manager>
- Segnala un problema: <https://github.com/YunoHost-Apps/simple-file-manager_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing --debug
o
sudo yunohost app upgrade simple-file-manager -u https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
