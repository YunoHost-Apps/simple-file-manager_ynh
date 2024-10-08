<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Simple File Manager pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/simple-file-manager.svg)](https://ci-apps.yunohost.org/ci/apps/simple-file-manager/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/simple-file-manager.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/simple-file-manager.maintain.svg)

[![Installer Simple File Manager avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-file-manager)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Simple File Manager rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Un gestionnaire de fichiers PHP simple. Le code est un seul fichier php.

### Caractéristiques

- Fichier unique, il n'y a pas d'images ou de dossiers CSS.
- Basé sur Ajax, il est donc rapide, mais ne casse pas le bouton de retour
- Autorise les téléchargements de fichiers par glisser-déposer si le dossier est accessible en écriture par le serveur Web (`chmod 777 votre/dossier`)
- Convient à mon esthétique. Plus comme Dropbox, et moins comme l'Explorateur Windows
- Fonctionne avec les noms de fichiers Unicode
- L'interface est utilisable depuis un iPad
- Protection XSRF et mot de passe en option.

**Version incluse :** 1.0~ynh1

## Captures d’écran

![Capture d’écran de Simple File Manager](./doc/screenshots/screenshot.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://github.com/jcampbell1/simple-file-manager>
- YunoHost Store : <https://apps.yunohost.org/app/simple-file-manager>
- Signaler un bug : <https://github.com/YunoHost-Apps/simple-file-manager_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing --debug
ou
sudo yunohost app upgrade simple-file-manager -u https://github.com/YunoHost-Apps/simple-file-manager_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
