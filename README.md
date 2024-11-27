<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Grist for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/grist)](https://ci-apps.yunohost.org/ci/apps/grist/)
![Working status](https://apps.yunohost.org/badge/state/grist)
![Maintenance status](https://apps.yunohost.org/badge/maintained/grist)

[![Install Grist with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=grist)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Grist quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Grist is a modern relational spreadsheet. It combines the flexibility of a spreadsheet with the robustness of a database to organize your data and make you more productive.

### Features

Grist is a hybrid database/spreadsheet, meaning that:

- Columns work like they do in databases: they are named, and they hold one kind of data.
- Columns can be filled by formula, spreadsheet-style, with automatic updates when referenced cells change.

More about the features can be found here: <https://github.com/gristlabs/grist-core/#features>

### Limitations

- You cannot log out from Grist, you have to log out from YunoHost to do that.


**Shipped version:** 1.3.0~ynh1

**Demo:** <https://docs.getgrist.com>

## Screenshots

![Screenshot of Grist](./doc/screenshots/grist.jpg)

## Documentation and resources

- Official app website: <https://getgrist.com>
- Official user documentation: <https://support.getgrist.com/>
- Official admin documentation: <https://www.getgrist.com/product/self-managed/>
- Upstream app code repository: <https://github.com/gristlabs/grist-core/>
- YunoHost Store: <https://apps.yunohost.org/app/grist>
- Report a bug: <https://github.com/YunoHost-Apps/grist_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/grist_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/grist_ynh/tree/testing --debug
or
sudo yunohost app upgrade grist -u https://github.com/YunoHost-Apps/grist_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
