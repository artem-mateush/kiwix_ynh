<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Kiwix for YunoHost

[![Integration level](https://dash.yunohost.org/integration/kiwix.svg)](https://ci-apps.yunohost.org/ci/apps/kiwix/) ![Working status](https://ci-apps.yunohost.org/ci/badges/kiwix.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/kiwix.maintain.svg)

[![Install Kiwix with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kiwix)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Kiwix quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Kiwix is an offline reader for online content like Wikipedia, Project Gutenberg, or TED Talks. It makes knowledge available to people with no or limited internet access. The software as well as the content is free to use for anyone.

### Features

- Full text search engine
- Search suggestions
- Compatible with almost all browsers
- Available as command line executable
- Embedded in Kiwix UI
- Able to deal with one ZIM file or XML library files


**Shipped version:** 3.6.0~ynh2

**Demo:** <http://library.kiwix.org/>

## Screenshots

![Screenshot of Kiwix](./doc/screenshots/screenshot.png)

## Documentation and resources

- Official app website: <https://www.kiwix.org/>
- Official admin documentation: <https://wiki.kiwix.org/wiki/Kiwix-serve/>
- Upstream app code repository: <https://github.com/kiwix/kiwix-tools>
- YunoHost Store: <https://apps.yunohost.org/app/kiwix>
- Report a bug: <https://github.com/YunoHost-Apps/kiwix_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
or
sudo yunohost app upgrade kiwix -u https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
