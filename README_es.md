<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Simple File Manager para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/simple-file-manager.svg)](https://ci-apps.yunohost.org/ci/apps/simple-file-manager/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/simple-file-manager.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/simple-file-manager.maintain.svg)

[![Instalar Simple File Manager con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-file-manager)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarSimple File Manager rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

A Simple PHP file manager. The code is a single php file.  

### Features

- Single file, there are no images, or css folders.  
- Ajax based so it is fast, but doesn't break the back button
- Allows drag and drop file uploads if the folder is writable by the webserver (`chmod 777 your/folder`)
- Suits my aesthetics.  More like Dropbox, and less like Windows Explorer
- Works with Unicode file names
- The interface is usable from an iPad
- XSRF protection, and an optional password.

**Versión actual:** 1.0~ynh2

## Capturas

![Captura de Simple File Manager](./doc/screenshots/screenshot.png)

## :red_circle: Características no deseables

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentaciones y recursos

- Repositorio del código fuente oficial de la aplicación : <https://github.com/jcampbell1/simple-file-manager>
- Catálogo YunoHost: <https://apps.yunohost.org/app/simple-file-manager>
- Reportar un error: <https://github.com/YunoHost-Apps/simple-file-manager_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing --debug
o
sudo yunohost app upgrade simple-file-manager -u https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
