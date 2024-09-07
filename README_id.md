<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Simple File Manager untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/simple-file-manager.svg)](https://ci-apps.yunohost.org/ci/apps/simple-file-manager/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/simple-file-manager.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/simple-file-manager.maintain.svg)

[![Pasang Simple File Manager dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-file-manager)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Simple File Manager secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

A Simple PHP file manager. The code is a single php file.  

### Features

- Single file, there are no images, or css folders.  
- Ajax based so it is fast, but doesn't break the back button
- Allows drag and drop file uploads if the folder is writable by the webserver (`chmod 777 your/folder`)
- Suits my aesthetics.  More like Dropbox, and less like Windows Explorer
- Works with Unicode file names
- The interface is usable from an iPad
- XSRF protection, and an optional password.

**Versi terkirim:** 1.0~ynh2

## Tangkapan Layar

![Tangkapan Layar pada Simple File Manager](./doc/screenshots/screenshot.png)

## :red_circle: Antifitur

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Dokumentasi dan sumber daya

- Depot kode aplikasi hulu: <https://github.com/jcampbell1/simple-file-manager>
- Gudang YunoHost: <https://apps.yunohost.org/app/simple-file-manager>
- Laporkan bug: <https://github.com/YunoHost-Apps/simple-file-manager_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing --debug
atau
sudo yunohost app upgrade simple-file-manager -u https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
