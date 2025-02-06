<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# OPcache GUI YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/opcache-gui)](https://ci-apps.yunohost.org/ci/apps/opcache-gui/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/opcache-gui)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/opcache-gui)

[![Instalatu OPcache GUI YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opcache-gui)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek OPcache GUI YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

A clean and responsive interface for Zend OPcache information, showing statistics, settings and cached files, and providing a real-time update for the information.


**Paketatutako bertsioa:** 3.5.5~ynh1

## Pantaila-argazkiak

![OPcache GUI(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/amnuts/opcache-gui>
- YunoHost Denda: <https://apps.yunohost.org/app/opcache-gui>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/opcache-gui_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/opcache-gui_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/opcache-gui_ynh/tree/testing --debug
edo
sudo yunohost app upgrade opcache-gui -u https://github.com/YunoHost-Apps/opcache-gui_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
